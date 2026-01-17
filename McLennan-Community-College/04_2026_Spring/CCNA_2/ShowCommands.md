# Cisco Show Commands

!Information about flash system
sh flash

!Display system hardware and software status
sh ver

!History of command entered
terminal history size *size*
sh history

!Running or Startup Configuration
sh running-config
sh startup-config

!Interface Show Commands
sh ip(v6) int *interface* (brief)
sh running-config int *interface*
sh ip(v6) route

!Display MAC address table
sh mac-address-table or sh mac address-table

!Config filter outputs
*any show command*  | section *section*
                    | include *requested*
                    | exclude *requested*
                    | begin *requested*
