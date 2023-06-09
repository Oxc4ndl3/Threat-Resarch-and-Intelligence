# BianLian Ransomware Encrypts Files in the Blink of an Eye

## Summary

Minutes make the difference to defenders in responding to a ransomware attack on a victim’s network. BianLian ransomware raises the cybercriminal bar by encrypting files with exceptional speed.

Threat actors built the new BianLian ransomware in the Go programming language (aka Golang). Despite the large size of files created in Go, threat actors are turning to this [“exotic” programming language](https://blogs.blackberry.com/en/2021/07/old-dogs-new-tricks-attackers-adopt-exotic-programming-languages) more often for a variety of reasons, particularly its robust support for concurrency. This is the ability for various malicious functions to run independently of each other, which speeds up the attack.

In addition to an overview of the BianLian ransomware, this post also highlights some of the unique aspects of Golang that makes it an increasingly popular choice for malware authors.

## Actionable Intelligence

| File | Description | Type | 
|--------|--------|--------|
| [BianLian-iocs.csv](https://github.com/blackberry/threat-research-and-intelligence/blob/main/Blogs%20%26%20Reports/Blogs/2022-10-13%20-%20BianLian%20Ransomware%20Encrypts%20Files%20in%20the%20Blink%20of%20an%20Eye/BianLian-iocs.csv) | Indicators of compromise related to BianLian Ransomware | CSV File |
| [BianLian_Go_ransomware.yar](https://github.com/blackberry/threat-research-and-intelligence/blob/main/Blogs%20%26%20Reports/Blogs/2022-10-13%20-%20BianLian%20Ransomware%20Encrypts%20Files%20in%20the%20Blink%20of%20an%20Eye/BianLian_Go_ransomware.yar) | Detects BianLian ransomware | YARA Rule |

## Reference

Blog: https://blogs.blackberry.com/en/2022/10/bianlian-ransomware-encrypts-files-in-the-blink-of-an-eye
