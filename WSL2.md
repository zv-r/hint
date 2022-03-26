
<details>
<summary>English translation</summary>
  
  
# PowerShell

> Easy (auto install)



1. win+x
2. run PowerShell (administrator)
3. `wsl --install`




---

> With my own hands


1. win+x
2. run PowerShell (administrator)
3. `dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart`
4. Reboot PC :exclamation:
5. run PS(adm) 
6. `dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart`
7. Reboot PC :exclamation: :exclamation:
8. [download "Update wsl2"](https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi) 
[alternative for - arm64](https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_arm64.msi)
9. open the downloaded file and agree with everything
10. run PS(adm)
11. `wsl --set-default-version 2`  
> Thus, we have chosen WSL2 as the default version
12. Reboot PC :exclamation: :exclamation: :exclamation:

## Mission complete ! 


> links to the distribution's official pages (Microsoft Store)

<details>
<summary>Details</summary>

<ul>
<li><a href="https://www.microsoft.com/store/apps/9N9TNGVNDL3Q" data-linktype="external">Ubuntu 18.04 LTS</a></li>
<li><a href="https://www.microsoft.com/store/apps/9n6svws3rx71" data-linktype="external">Ubuntu 20.04 LTS</a></li>
<li><a href="https://www.microsoft.com/store/apps/9NJFZK00FGKV" data-linktype="external">openSUSE Leap 15.1</a></li>
<li><a href="https://www.microsoft.com/store/apps/9MZ3D1TRP8T1" data-linktype="external">SUSE Linux Enterprise Server&nbsp;12&nbsp;SP5</a></li>
<li><a href="https://www.microsoft.com/store/apps/9PN498VPMF3Z" data-linktype="external">SUSE Linux Enterprise Server&nbsp;15&nbsp;SP1</a></li>
<li><a href="https://www.microsoft.com/store/apps/9PKR34TNCV07" data-linktype="external">Kali Linux</a></li>
<li><a href="https://www.microsoft.com/store/apps/9MSVKQC78PK6" data-linktype="external">Debian GNU/Linux</a></li>
<li><a href="https://www.microsoft.com/store/apps/9n6gdm4k2hnc" data-linktype="external">Fedora Remix for WSL</a></li>
<li><a href="https://www.microsoft.com/store/apps/9NV1GV1PXZ6P" data-linktype="external">Pengwin</a></li>
<li><a href="https://www.microsoft.com/store/apps/9N8LP0X93VCP" data-linktype="external">Pengwin Enterprise</a></li>
<li><a href="https://www.microsoft.com/store/apps/9p804crf0395" data-linktype="external">Alpine WSL</a></li>
</li>
</ul>


</details>

