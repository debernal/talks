Title: Detecting Malicious Files with YARA Rules as They Traverse the Network

Abstract:
YARA, the pattern matching swiss knife for malware researchers, has been extremely useful at detecting suspicious files on the endpoint. However, little or no information is publicly available on how to leverage this useful tool to scan for files as they are traversing the network.

In this presentation I showed how open source Zeek IDS (formerly bro) and  some custom developed scripts can be used to extract files from the network and identify attacks on an early stage before they cause more damage. Scanning for YARA files on the network has the benefit of increased performance, as compared to scanning several gigabytes or terabytes on the endpoint, as well as target specific mime types, used for malware delivery. Additionally, Zeek IDS can provide additional context whenever a YARA rule is triggered, that provides defenders with more information to act more rapidly.

Thanks to my Black Hat coach Phil Young (@mainframed767 aka The Soldier of Fortran) for helping me preparing the slides/talk.
