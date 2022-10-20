# xlsmcurltest

sample27062022CURL.xlsm - CURL command running by macros embeded in xlsm file. Used for download 7zip2200.exe in temp directory Embedded command: Call Shell("cmd.exe /S /K curl.exe -vk https://www.7-zip.org/a/7z2200.exe -o %TEMP%\7z2200.exe", vbNormalFocus). Macros run after opening file and enabling macros.

sample19102022CURLeicar_download.xlsm - CURL command running by macros embeded in xlsm file. Used for download 7zip2200.exe in temp directory Embedded command: Call Shell("cmd.exe /S /K curl.exe -vk https://secure.eicar.org/eicar.com -o %TEMP%\eicar.com", vbNormalFocus). Macros run after opening file and enabling macros. 

click_download_macros.xlsm - CURL command running by macros embeded in xlsm file. Used for download 7zip2200.exe in temp directory Embedded command: Call Shell("cmd.exe /S /K curl.exe -vk https://www.7-zip.org/a/7z2200.exe -o %TEMP%\7z2200.exe", vbNormalFocus). Macros run after clicking button and enabling macros.

Sandbox use case:
Download files and check your sandbox logs

Antivirus use cases:
Download files and scan it by antivirus
Download files and run file 



This is simple CURL macros embeded in xlsm file. Command: start "MyProgram" "cmd.exe" /S /K curl.exe -vk https://www.7-zip.org/a/7z2200.exe -o %TEMP%\7z2200.exe
