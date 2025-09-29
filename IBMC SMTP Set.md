# IBMC SMTP Set
## IBMC 접속하기 
### BIOS환경에서 설정한 IBMC IP주소 또는 서버에 부착된 IBMC IP주소를 이용하여 로그인


<img width="1919" height="981" alt="image" src="https://github.com/user-attachments/assets/3d276cde-2e11-49a6-857c-9e0e09329f4c" />

- 기본 ID : Administrator PW : Admin@9000

---
### Alarm Settings 접속 

- 경로 : Maintenance -> Alarm Settings

<img width="338" height="288" alt="image" src="https://github.com/user-attachments/assets/3b17f396-b446-46ce-95de-ab06722b8f53" />


### Email Notification 설정 
#### SMTP Settings 
SMTPFunction : Yes
SMTP Server Address : 사내에서 쓰고있는 SMTP 서버명을 사용하면 된다. 


<img width="305" height="98" alt="image" src="https://github.com/user-attachments/assets/6da32ad5-cae7-47f0-b5a4-b8cd183feb52" />

SMTP Server Port : 587 (TLS Port)
TLS Enabled : Yes

---
#### Email Info
Anonymouis Login Allowed : No
Sender User Name : 자신의 Email 주소를 입력
Sender Password : 나의 Email Password를 입력
Sender Email : Sender User Name과 동일하게 작성
Email Subject : Server Alert 
Email Subject Contains : Board serial number / Product asset label / Host Name 필요한것만 체크 
Include Alarm Severities : Informational 


<img width="1631" height="801" alt="image" src="https://github.com/user-attachments/assets/e2c6a766-bbcb-4cf5-b0ce-62934dc4b1eb" />

---
#### Recipient Addresses
Operation에 Edit을 클릭하여 보낼 Email주소를 입력하면 된다.


<img width="1595" height="321" alt="image" src="https://github.com/user-attachments/assets/405cbefb-5899-4e10-aa94-f09a4a1449a9" />

