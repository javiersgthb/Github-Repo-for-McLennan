# Configuring Auto-MDIX

en
conf t
int (range) gi/fe 0/0/0
mdix auto
end
write mem (copy running-config startup-config)
