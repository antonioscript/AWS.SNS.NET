This repository demonstrates how to integrate Amazon SNS (Simple Notification Service) with .NET applications

## AWS SQS

## Create SNS Topic
![image](https://github.com/user-attachments/assets/22b6a11a-0b55-4887-b721-30c8a15c68c2)

----
![image](https://github.com/user-attachments/assets/54ccc1e1-51c5-4b47-9f61-c1b039efe465)

----

![image](https://github.com/user-attachments/assets/e0d2cae9-bdf3-423c-b1aa-414ca46ad02b)


## Application

## Test Email
https://temp-mail.org/pt/

![image](https://github.com/user-attachments/assets/cc7256cf-2606-4bd2-8502-e9661e71e59f)

----




## Create a subscription
![image](https://github.com/user-attachments/assets/7cb1d908-6adc-4a5c-a5fa-4abd2c8de8c2)

------
![image](https://github.com/user-attachments/assets/82857f3d-8eb8-4095-aa1f-8e53679965ad)

------


## Test Message
![image](https://github.com/user-attachments/assets/87635eff-005c-40da-b84f-6e10e9ee6955)

-------


![image](https://github.com/user-attachments/assets/fff56a88-f2da-43ee-b425-b7ff2aa94a62)

----

![image](https://github.com/user-attachments/assets/4c97ba5a-4f4a-4918-b02f-fce625c3c016)


## LambdaSubscriber
**Create a Projetc Lambda and deploy to AWS**

</br>

![image](https://github.com/user-attachments/assets/5ef4b52c-e810-4342-b31d-7f0563375fe1)

------------

![image](https://github.com/user-attachments/assets/38373822-b165-4d5a-820c-d8cad79f665f)

### Create a Trigger
![image](https://github.com/user-attachments/assets/dcd4c427-f04f-4db3-81c8-a3e60a118e26)

----
![image](https://github.com/user-attachments/assets/f26cc20e-e7fa-4e3a-859a-aeba51b36bb3)

-----
Go back to SNS and refresh the Subscriptions

</br>

![image](https://github.com/user-attachments/assets/2d4d48fc-c6fd-4b58-a3de-668ba54635fe)

----

_> This means that if our ASP.NET Core Publisher endpoint is hit again, a new email will be sent, and also the Lambda will be invoked. Go to the Log Group of the Lambda function and you will see that it has received this information_

-----



# References
https://codewithmukesh.com/blog/scalable-notifications-with-amazon-sns-and-aspnet-core/
