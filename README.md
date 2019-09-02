# ADB FacePay

ADB FacePay is a <b>digital payment solution that utilizes facial recognition</b> to authenticate customers.
It will be <b>seamlessly integrated with country's leading digital wallet solutions - GCash and Paymaya</b>.
It was a proposal I submitted to the "ADB Pay: Digital Payments" challenge of <b>ADB-AIM Hackathon 2019</b>.

https://challenges.adb.org/en/challenges/adb-pay


### Problem:

ADB employees currently use a closed-loop cashless payment system that allows them to purchase goods from vendors within the ADB Food Services outlets. To date, there are less than 200 users, and at a time of active promotions, it reached beyond 300 users.

Around 5000 staff/contractors/consultants/dependents/visitors mostly use cash for their daily transactions. There are about 40 food services, laundry, courier and other merchants in ADB HQ that can use the future innovative payment solution.

HOW CAN YOU ENCOURAGE STAFF, CONTRACTORS, CONSULTANTS, DEPENDENTS AND VISITORS TO USE MORE DIGITAL SOLUTIONS? 


### Core ideas:

- <b>Face Recognition</b> (with options of Fingerprint biometrics and RFID employee ID)

  <b>Having a facial recognition payment solution will entice employees to use the digital wallet solution instead of cash 
  because it is a bold and exciting new technology.</b>
  
  The hype will eventually subside after a few weeks so to make the use of technology sustainable, usage must be tied up to some <b>point system</b>.
  Employees who opts to use the technology will gain points that can be <b>converted into cash</b>.
  Discounts for senior citizen employees will automatically be deducted.
  Additional gimmicks can be added that will make users acquire more points and thus use the technology more.


- <b>Secure</b> (integrated to Amazon Cognito user signup/signin with MFA/OTP via SMS/email)

  People don’t use technogies because they think it is not easy and not safe to use.

  <b>To make FacePay more secure, an OTP code will be sent to user pre-registered SMS mobile number after user's face has been recognised.</b>
  
  This enhances security by preventing fraud activities and 
  ensuring user is who he says he is and therefore has access to his mobile phone. 
  This is also known as 2-factor authentication.
  This feature can be removed by user after some time when accuracy of face recognition has reached to acceptable levels.


- <b>Fun and Easy to use</b> (with voice enabled instructions)

  The face recognition solution will be deployed in kiosks located in each stores inside ADB. 
  The kiosk is a <b>touch-screen monitor</b> that is connected to ADB's private servers and can be accessed and controlled remotely by the IT department for management and monitoring.

  A <b>digital voice assistant</b> named <b> DeBbie will guide user through the process.</b>
  This would be really helpful for first time users.


- Integration to <b>Globe's GCash and Smart's Paymaya</b> digital wallet solutions

  <b> There's a lot of digital payments solutions in the country already.
  This includes Globe’s GCash (partnered with Ali Pay), Smart’s PayMaya (partnered with Tencent/WeChat Pay), Coins.ph, GrabPay, etc.
  To create another one will prevent wide-spread usage of the technology.
  </b>

  We don’t want to create another one.
  Rather, we should focus on integrating to country's leading digital wallets solutions. 
  Based on research, we should integrate with GCash and Paymaya.

  This will make employees use the technology more often because they can use it outside ADB premises.
  <b>If employees use the digital wallet solution outside the office, more likely that they will use it inside the ADB office.</b>

  

- Integration to <b>ADB's accounting system</b> for food allowance and bonus allocations

  Food allowances and transportation allowances will automatically be transferred to employee's digital wallets.
  A certain portion of yearly bonuses will also be transferred automatically.
  
  <b>Employees will be allowed to configure how much of their salary will automatically be transfered to their digital wallets every payday</b>.



### Feasibility:

Facial recognition is already very popular in China.
Paying food using face is already available commercially. 
It is made possible via backend integration with leading digital payment solutions - <b>WeChat Pay</b> and <b>Ali Pay</b>.

- WeChat Pay

  <a href="https://www.youtube.com/watch?v=9HHW0mj2EDc"
    target="_blank"><img src="https://img.youtube.com/vi/9HHW0mj2EDc/0.jpg" 
    alt="Buying Food with Facial Recognition in China" width="480" border="10" /></a>

- AliPay

  <a href="https://www.youtube.com/watch?v=W4P0zt4cnmU"
    target="_blank"><img src="https://img.youtube.com/vi/W4P0zt4cnmU/0.jpg" 
    alt="Buying Food with Facial Recognition in China" width="480" border="10" /></a>



### Challenges:

Deploying a facial recognition project can be a challenging task. 

1. Ensuring <b>high accurracy for about 5000 employees</b> can be challenging. ML/DL models will need to be trained and retrained as more employees use the technology.
   Adding backup alternatives such as fingerprint biometrics or RFID employee id card will be critical in the early stages of deployment.
2. Upper managers can be quite hesitant to adapt to this technology especially due to <b>privacy and ethical issues</b> surrounding face recognition.



### Presentation:
	   
Proof of concept prototype

- ADB FacePay
  
  Note that this interface is intended to be displayed on a touch screen device. 
  The kiosk is to be deployed on each store in the ADB premises.

  <a href="https://youtu.be/SCYkW_XRK2c"
    target="_blank"><img src="https://img.youtube.com/vi/SCYkW_XRK2c/0.jpg" 
    alt="Face Pay demo prototype" width="480" border="10" /></a>
 


### Notes:

Its a digital project initiative for the well-funded companies with technology savvy directors and managers who are not afraid to risk, experiment, fail, learn and iterate. This is a risky project but there’s tremendous opportunities once we make it perfect.

Let's make it happen! Message me!
