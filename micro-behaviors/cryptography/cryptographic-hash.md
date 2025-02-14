<table>
<tr>
<td><b>ID</b></td>
<td><b>C0029</b></td>
</tr>
<tr>
<td><b>Objective(s)</b></td>
<td><b><a href="../cryptography">Cryptography</a></b></td>
</tr>
<tr>
<td><b>Related ATT&CK Techniques</b></td>
<td><b>None</b></td>
</tr>
<tr>
<td><b>Version</b></td>
<td><b>2.0</b></td>
</tr>
<tr>
<td><b>Created</b></td>
<td><b>13 October 2020</b></td>
</tr>
<tr>
<td><b>Last Modified</b></td>
<td><b>31 October 2022</b></td>
</tr>
</table>


# Cryptographic Hash

Malware may use a cryptographic hash. 

## Methods

|Name|ID|Description|
|---|---|---|
|**MD5**|C0029.001|Malware uses an MD5 hash.|
|**SHA1**|C0029.002|Malware uses a SHA-1 hash.|
|**SHA224**|C0029.004|Malware uses a SHA-224 hash.|
|**SHA256**|C0029.003|Malware uses a SHA-256 hash.|
|**Snefru**|C0029.006|Malware uses a Snefru hash.|
|**Tiger**|C0029.005|Malware uses a Tiger hash.|

## Use in Malware

|Name|Date|Method|Description|
|---|---|---|---|
|[**BlackEnergy**](../xample-malware/blackenergy.md)|2007|C0029, C0029.001, C0029.002|Please see the BlackEnergy malware page for details. [[1]](#1)|
|[**Kovter**](../xample-malware/kovter.md)|2016|--|Hash data via WinCrypt (This capa rule had 22 matches) [[1]](#1)|
|[**Redhip**](../xample-malware/rebhip.md)|2011|C0029, C0029.002|Please see the Redhip malware page for details. [[1]](#1)|
|[**UP007 Malware Family**](../xample-malware/up007.md)|2016|C0029.002|Hash data using SHA1 (This capa rule had 1 match) [[1]](#1)|

## References

<a name="1">[1]</a> capa v4.0, analyzed at MITRE on 10/12/2022

