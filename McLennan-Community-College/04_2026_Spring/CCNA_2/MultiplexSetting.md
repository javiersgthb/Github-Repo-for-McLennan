# Multiplex Settings for Layer 2 Switch

conf t

int *interface*
duplex auto ( full, or half - only for 10/100)
speed auto (*speed*)
mdix auto
end
write mem (copy running-config startup-config)
