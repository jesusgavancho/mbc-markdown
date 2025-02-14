<table>
<tr>
<td><b>ID</b></td>
<td><b>E1510</b></td>
</tr>
<tr>
<td><b>Objective(s)</b></td>
<td><b><a href="../impact">Impact</a></b></td>
</tr>
<tr>
<td><b>Related ATT&CK Techniques</b></td>
<td><b>Clipboard Modification (<a href="https://attack.mitre.org/techniques/T1510/">T1510</a>)</b></td>
</tr>
<tr>
<td><b>Impact Type</b></td>
<td><b>Integrity</b></td>
</tr>
<tr>
<td><b>Version</b></td>
<td><b>2.0</b></td>
</tr>
<tr>
<td><b>Created</b></td>
<td><b>4 December 2020</b></td>
</tr>
<tr>
<td><b>Last Modified</b></td>
<td><b>21 November 2022</b></td>
</tr>
</table>


# Clipboard Modification

ATT&CK defines Clipboard Modification as a Mobile technique (Android platform). MBC extends it to the Windows platform. 

## Use in Malware

|Name|Date|Method|Description|
|---|---|---|---|
|[**Clipminer**](../xample-malware/clipminer.md)|2011|--|Clipminer monitors the clipboard for cryptocurrency addresses and replaces them with ones controlled by the adversary [[1]](#1)|
|[**Dark Comet**](../xample-malware/dark-comet.md)|2008|--|Write clipboard data (This capa rule had 4 matches) [[2]](#2)|
|[**Emotet**](../xample-malware/emotet.md)|2018|--|Write clipboard data (this capa rule had 1 match) [[2]](#2)|
|[**Hupigon**](../xample-malware/hupigon.md)|2013|--|Replace clipboard data (This capa rule had 1 match) [[2]](#2)|
|[**Rombertik**](../xample-malware/rombertik.md)|2015|--|Replace clipboard data (This capa rule had 1 match) [[2]](#2)|

## References

<a name="1">[1]</a> https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/clipminer-bitcoin-mining-hijacking

<a name="2">[2]</a> capa v4.0, analyzed at MITRE on 10/12/2022

