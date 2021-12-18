# RouterOS-Resource-Email
Send RouterOS Resource Report Via Email

## Instruction
The sending email used in the script is 163 mailbox, so you need to customize your sending mailbox provider and mail smtp server.  
The receiving email used in the script is QQ mailbox, so you need to customize your receiving email provider.  

Go to Tool -> Email：  
<img width="441" alt="image" src="https://user-images.githubusercontent.com/11908641/146632314-10b0fb22-47dc-4ace-ac96-edda9cde4f25.png">  

If needed, please customize:
```
:local SendFrom "aaa@163.com";         # Need to customize
:local SendTo "bbb@qq.com";            # Need to customize
:local WanInterface "pppoe-out1";      # Need to customize
:set MailIp [:resolve smtp.163.com ];  # Need to customize
```

## Permission request  
<img width="440" alt="image" src="https://user-images.githubusercontent.com/11908641/146632420-0b648d58-34d0-4c95-8e2b-c91bc6156662.png">
