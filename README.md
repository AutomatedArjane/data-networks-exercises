# Data Networks course exercise documentation

## This course is finished

## Learning how to create and use virtual networks using Lubuntu and Virtual Box
These assignments are from the Data Networks course of the 30 credit Digiosaaja open studies in JAMK. Each assignment focusses on increasingly complicated network creation skills and includes topologies and screenshots.



## How to create the documentation for this course

Please write your documentation the following markdowns created as templates under the `/documentation/` -folder.

- [E01.md](/documentation/E01.md)
- [E02.md](/documentation/E02.md)
- [E03.md](/documentation/E03.md)
- [E04.md](/documentation/E04.md)
- [E05.md](/documentation/E05.md)

If you have additional material (pictures, topologies), please save them in the repository to the correct folder e.g. `/documentation/E01/jamk.png`

## Example markdown

### Plain text

Your name here: Arjane Kerkhoven
Student group: K2023 Digiosaajat

### Image

This is a reference to an image

![](/documentation/E01/jamk.png)

### Configuration example

Either as a file

- [switch.cfg](/documentation/switch.cfg)

Or as a blockquote/snippet

```
EXOS-VM.1 # show configuration
#
# Module devmgr configuration.
#
configure snmp sysContact "https://www.extremenetworks.com/support/"
configure sys-recovery-level switch reset

#
# Module vlan configuration.
#
configure vlan default delete ports all
configure vr VR-Default delete ports 1-2
configure vr VR-Default add ports 1-2
```
