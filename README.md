# suricataFIT

This project contains DSM modul for QRadar with 30 000 mappings. It can be downloaded and installed as extension via Extension Manager in QRadar system.

Custom properties used in this module:


Custom event mappings and QID records contains about 30 000 mappings. They were created from rulesets of Suricata with basic setup. I used rules from ET/Open and basic Suricata rules. For every rules was created QID record and event mapping. When QID is created, it has to be assigned some QRadar rule. Folder QRadar contains files, which names are names of QRadar low level categories. Inside files it can be found rules from these sections. In the folder some rules are duplicated. Duplicated rules are in files which are named by some "general" rule, like Suspicious Unknown Event.

Feel free to contribute
