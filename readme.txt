[version]
    RSA-Sakura 231029 (the edition for the 5th anniversary of IZ*ONE debut)
    build number : 831.250430.1201 (240314.319_303_209_201)
          Author : Derek Fu
[copyright]
    Copyright (C) 2023-2025 Derek Fu
[Installation/Setup]
    "xrsa_shareware_[Sakura.G_831.250430.1201_x64_arm64].zip" is RSA-Sakura 
executable binaries (arm64-Linux/macOS, x64-Linux/macOS/Windows, x86-Windows)
    Other zip files are plugins, extract them into "xrsa_shareware/misc".
    All the other files are support packages.
1) On Linux/macOS, just run following 2 commands in terminal window:
       "chmod +x misc/xs_install_symlnk_sw.sh"
       "misc/xs_install_symlnk_sw.sh
2) On Windows, there is no installation application. Just run following command
     in console window, or just double-click this bat file to launch a new 
     console window.
       "misc\cmd_cd_x.bat"
3) On Linux/macOS, "misc/xs_uninstall_symlnk_sw.sh" is used for uninstallation.
   On Windows, an uninstallation application is not needed.
[help]
1) linux/mac  :    (this part is only for non-bash environment.)
   On linux (/macOS), an other flexible & convenient usage is to configure 
     terminal environment with the following command, and run RSA-Sakura by 
     "xsrsaoapp.sw".
   [configure Terminal library-loading method]
        macOS :    "export DYLD_LIBRARY_PATH=./:/usr/local/lib"
        linux :    "export LD_LIBRARY_PATH=./"
   (this section is useful for software developer.)
2) help : "xrsaoappsw.exe -?" or "xrsaoapp.sw -?"
   "n_pem_ini_cp.sh"/"n_pem_ini_cp.bat" are used to create "xrsao.ini" (RSA 
     key-chain) in the same directory (for RSA-Sakura initialization), then 
     ini will be copied into arm/linux/mac/osx/x64/x86 sub-directories.
   There are 2 mainly tools used for multiple files encryption/decryption:
       "sxrsa","dxrsa"
   There are 4 tools used for rsa-sakura lock:
       "sige","sigd","sigx"(,"sigrm")
   There are 2 tools used for rsa-keeper:
       "config-keeper","rsa-keeper"
   Other plugin tools: "ezip","eunzip","kzip","kunzip"(,"ctgz","xtgx")
       "erar","eunrar","krar","kunrar",
       "ssmx","dsmx"(,"dcp","clearnoise","lsdx")

Get more details from release, please. ("xrsa_shareware_[Sakura.G_831.250430.1201_x64_arm64].zip"
is renamed with "xrsa_shareware_v831.250430.1201_x64_arm64.zip", because github cannot use '[]'.)
