# fullsetupsnort
IDS snort setup in windows in easy way with some basic implementation . This pdf developed by me in over 3 weeks . Snort is a IDS and IPS mechanism , but this contain about snort IDS not IPS Process

SNORT is a powerful open-source intrusion detection system (IDS) and intrusion prevention system (IPS) that provides real-time network traffic analysis and data packet logging. With its real-time protection mechanisms, Snort can safeguard the system from any new threats or malicious software. 

Maintain the Process Follow As Line Mentioned (Any mistake may issue with connection)*
                                                                                                OS Type : Windows | Snort V : 2_9_20 (Only IDS)

At first simply download some tools & config snapshots 

    Download Snort installer example : Snort_2_9_20_Installer.exe
    Download WinPcap installer example : WinPcap_4_1_3.exe
    Download nPcap installer example : nPcap-1.79.exe
    Download Notepad ++
    Download snort rules after login snort website get below snapshots of latest example : snortrules-snapshot-29111.tar.gz
    Download snort community rules of snort V 2.9.tar.gz

                                                           Extract last both tar.gz in download path

Steps 1


After Extracting the snortrules-snapshot-29111 ->
Open it ->
You see rules & preproc_rules -> copy the files -> minimise it
Check on local disk ( C file ) -> Snort Folder -> Paste there -> Select replace files of both

Open etc -> snort.conf -> open in notepad ++ -> there are some need to set rules (carefully edit) 




Step 2


double click to open the snort installer.exe file -> Install in C folder or Local PC  

Unzip the snort snapshot file -> mention to copy ( rules & Preproc File ) -> paste into C:\Snort -> Replace 

Install WinPcap files 

Install nPcap file -> If you use wifi then select 2nd option otherwise not -> select third option -> install

Install Notepad ++ 

Unzip the community rules



Step 3 ( As per change the line )


![Screenshot 2024-08-31 at 3 12 30 PM](https://github.com/user-attachments/assets/76969923-29cd-4bdd-a755-540e940c3418)







