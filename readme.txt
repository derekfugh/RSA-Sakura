[version]
    RSA-Sakura 231029 (the edition for the 5th anniversary of IZ*ONE debut)
    build number : 831.250430.1201 (240314.319_303_209_201)
          Author : Derek Fu
[copyright]
    Copyright (C) 2023-2025 Derek Fu
[Installation/Setup]
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
1) linux/mac  :    "chmod +x xrsaoapp.sw"
   On linux (/macOS), an other flexible & convenient usage is to configure 
     terminal environment with the following command, and run Sakura by 
     "./xsrsaoapp.sw".
   [configure Terminal library-loading method]
        macOS :    "export DYLD_LIBRARY_PATH=./:/usr/local/lib"
        linux :    "export LD_LIBRARY_PATH=./"
   (The content of this section is useful for software developer.)
2) help : "xrsaoappsw.exe -?" (win), or "xrsaoapp.sw -?" (osx/linux)
   "n_pem_ini_cp.sh"/"n_pem_ini_cp.bat" are used to create "xrsao.ini" (RSA 
     key-chain) in the same directory (for RSA-Sakura initialization), then 
     ini will be copied into linux/osx/x64/x86 sub-directories.
   There are (mainly) 4 tools used for multiple files encryption/decryption:
       "sxrsa","dxrsa","ezip","eunzip" ("kzip","kunzip")
   There are 3 tools used for rsa-sakura lock:
       "sige","sigd","sigx"
   There are 2 tools used for rsa-keeper:
       "config-keeper","rsa-keeper"
   Other plugin tools are packed by zip.
3) license/purchase/contact:    www.taobao.com (search for 'RSA-Sakura')
   (Mobile/Weixin) (86+)15380473198    (ID:rsa-sakura)
   (QQ)            3782184068
   (E-mail)        rsa-sakura@aliyun.com
   (Mobile)        (86+)15380483198
   (Mobile/Weixin) (86+)13501777140

[notes]
   Some antivirus software (windows definder) may mistreat RSA-Sakura (EXE/DLL)
     as a virus. Or some Windows setting disabled launching command line 
     window. Make correct OS settings, such like diabling antivirus tool 
     (windows definder), before use RSA-Skaura, please.
   Please check all files with the following MD5 list after download package.

[ arm ]MD5 (linux\libskapplyfor.so) = baccc0c6203767bf7b5489175d31f61fMD5 (linux\libxmdx.so) = 042aaf41aa3468636910a42ebc111aacMD5 (linux\libxmdxex.so) = 5b02faf5b3718f136693fc58d7e3795aMD5 (linux\libxrsao.so) = 97883642c357bcbe07b1f841869f4de9MD5 (linux\libxscmutil.so) = e2a4b546f101454adac7b9d763aa4f3fMD5 (linux\libxsxml.so) = eb5c4cc762e3013bf85e3cf9899a5fe5MD5 (linux\xrsaoapp.sw) = 1648e6dc538e98f93e70f23e9f4b594d[ linux ]MD5 (linux\libskapplyfor.so) = baccc0c6203767bf7b5489175d31f61fMD5 (linux\libxmdx.so) = 042aaf41aa3468636910a42ebc111aacMD5 (linux\libxmdxex.so) = 5b02faf5b3718f136693fc58d7e3795aMD5 (linux\libxrsao.so) = 97883642c357bcbe07b1f841869f4de9MD5 (linux\libxscmutil.so) = e2a4b546f101454adac7b9d763aa4f3fMD5 (linux\libxsxml.so) = eb5c4cc762e3013bf85e3cf9899a5fe5MD5 (linux\xrsaoapp.sw) = 1648e6dc538e98f93e70f23e9f4b594d[ mac ]MD5 (mac\libskapplyfor.dylib) = 665f07ac0a27194b050aba76356f4d0fMD5 (mac\libxmdx.dylib) = 7668fb095b6933ff779434f2de49b443MD5 (mac\libxmdxex.dylib) = a579e723f6658bc8c45e7598a90c3aadMD5 (mac\libxrsao.dylib) = cbce5a2dc8124b0dff907eb1134bc25cMD5 (mac\libxscmutil.dylib) = 1b09405206e86bc96505b9542bae1088MD5 (mac\libxsxml.dylib) = 51d54a98bd260fe60b955f2044cf07b6MD5 (mac\xrsaoapp.sw) = b4a430adeda1a0c89a9c2d28ebb0411d[ osx ]MD5 (osx\libskapplyfor.dylib) = 3b30f6a948f42eb86982e59fa62046baMD5 (osx\libxmdx.dylib) = f7d9f92431d440bb2083fb9057ca55e2MD5 (osx\libxmdxex.dylib) = 00bc6950de6edaab53de61a786bb9046MD5 (osx\libxrsao.dylib) = f50a1ac34f17f12a7b2a2fac259d0c57MD5 (osx\libxscmutil.dylib) = 2dabfa993b82d342ad9b19f631dd8340MD5 (osx\libxsxml.dylib) = e5c4c126ecd667c2bc16f8266ed7b21aMD5 (osx\xrsaoapp.sw) = ed016e390c39ec5b346447ed11facde3[ x64 ]MD5 (x64\mdx.dll) = fbea54d398cf0fe07dfa61e01b4d2852MD5 (x64\mdxex.dll) = a067e8d66f71b0b80e0a65ef8ab232cfMD5 (x64\skapplyfor.dll) = 943252cb3e8db7cf2a23215a894b9247MD5 (x64\xrsao.dll) = 6b471aa3eabde353cb56d83f34becebaMD5 (x64\xrsaoappsw.exe) = 6c23ceeb11a84b64d04d3aa2504f1b4dMD5 (x64\xscmutil.dll) = c7a45ae57679ac94267d506b0ef7bf81MD5 (x64\xsxml.dll) = ae25eabecfa886d16197898d9c6ff088[ x86 ]MD5 (x86\mdx.dll) = bd696ec4f1599fb5d46a4293dfad9cb9MD5 (x86\mdxex.dll) = 4e19aab605cb4f6a73767f2005719b00MD5 (x86\skapplyfor.dll) = 987407531ac9f24d014de772cd351979MD5 (x86\xrsao.dll) = 1b2b52d69dc5ccd3d627afbe958bff15MD5 (x86\xrsaoappsw.exe) = 150afd109e5c00ed180eb1c949e27f22MD5 (x86\xscmutil.dll) = 67662313ca1a07e57e03b5372efe85c9MD5 (x86\xsxml.dll) = 5bbd70aaf7ffbaab7da6277e00ecc8a7