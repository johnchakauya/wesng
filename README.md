# wes-ng
WES-NG is a tool based on the output of Windows' systeminfo utility which provides the list of vulnerabilities the OS is vulnerable to, including any exploits for these vulnerabilities. Every Windows OS between Windows XP and Windows 10, including their Windows Server counterparts, is supported.

USAGE Example
1. systeminfo > sysinfo.txt
2. wes.py sysinfo.txt