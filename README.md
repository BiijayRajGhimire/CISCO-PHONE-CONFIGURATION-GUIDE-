# CISCO-PHONE-CONFIGURATION-GUIDE-
This comprehensive guide ensures the successful deployment of Cisco's communication solution, providing a streamlined process for configuring phone devices and directory numbers.  
CISCO PHONE  
CONFIGURATION GUIDE  
  
This is a detailed resource designed to assist users in setting up the Cisco IP communicator soft client on their laptops. This document combines step-by-step instructions with helpful screenshots to ensure a seamless installation and configuration experience. From installing the client software to establishing VPN connectivity and accessing the CUCM portal.   
This comprehensive guide ensures the successful deployment of Cisco's communication solution, providing a streamlined process for configuring phone devices and directory numbers.  
  
  
  
•	Install the cisco client software in your laptop   
•	Rt click the downloaded software and run as administrator
<img width="789" height="563" alt="image" src="https://github.com/user-attachments/assets/f8bd9147-b80a-44cd-b94f-426783c5e9ba" />
<img width="794" height="601" alt="image" src="https://github.com/user-attachments/assets/d6c7672e-b703-4c90-bf43-8bee6001a470" />
<img width="820" height="623" alt="image" src="https://github.com/user-attachments/assets/36484895-c786-47a1-8dbc-a0dfdc626d92" />
•	Once installed it will prompt you to restart the pc   
•	Select yes to restart the pc   
<img width="608" height="309" alt="image" src="https://github.com/user-attachments/assets/e9461f3f-84f8-4b01-8f33-01c41ddca42b" />
•	Once the pc restarts start the application and proceed to configure the initial setup   
<img width="975" height="593" alt="image" src="https://github.com/user-attachments/assets/88452a18-6cdb-4c36-ac85-5d15a3077b32" />
<img width="975" height="571" alt="image" src="https://github.com/user-attachments/assets/2bef5df2-7edb-49cd-8268-6fcb6b684bda" />
•	It will prompt you to allow accept the prompt and complete the audio tuning wizard  
<img width="975" height="590" alt="image" src="https://github.com/user-attachments/assets/9cf2a80f-c14c-4aa6-a6c6-35a88d17c13f" />
•	Connect to Everest it vpn   
•	Ping this ip 172.16.0.16  once you get a successful ping then only proceed to the next step  
<img width="925" height="634" alt="image" src="https://github.com/user-attachments/assets/822ea39d-9ae8-4f81-992e-1155d9c9dfd9" />
The soft client should automatically turn on, other wise double click it to open   • 	Click on menu>preference   
<img width="438" height="469" alt="image" src="https://github.com/user-attachments/assets/51051ce2-1716-4be6-8814-83228cfd3373" /> <img width="445" height="472" alt="image" src="https://github.com/user-attachments/assets/72bce7ce-ab98-41e3-aee4-614bde13893c" />
•	Go to network tab   
•	If you see the TFTP server greyed out   
<img width="537" height="571" alt="image" src="https://github.com/user-attachments/assets/9291a1cc-3045-4c21-922a-dff5865822c2" />
Close the app   
<img width="973" height="478" alt="image" src="https://github.com/user-attachments/assets/8133b76c-713b-41fd-928c-80fe0f5511b8" />
•	Run the app again as an administrator   
•	This should resolve the issue   
•	In the network tab fill out the provided ip and click OK  
<img width="514" height="548" alt="image" src="https://github.com/user-attachments/assets/49b0207b-9253-47c6-8b88-534eab3b5fd5" />
Open browser and navigate to the same ip address   
<img width="633" height="443" alt="image" src="https://github.com/user-attachments/assets/ffbc66f3-c2a5-48c7-8312-7d7f1b0f139b" />
•	Select the first option   
<img width="975" height="471" alt="image" src="https://github.com/user-attachments/assets/51772068-dab5-4da0-a6d6-ae00727f988d" />
•	Fill out the provided credentials  
<img width="975" height="468" alt="image" src="https://github.com/user-attachments/assets/1c48e599-2e5f-4cb9-bcf2-15ad755347c1" />
•	Navigate to devices > phone   
<img width="975" height="447" alt="image" src="https://github.com/user-attachments/assets/2053afd8-f7d2-47e9-a6fc-222a5ef8341e" />
•	Click on add new   
<img width="975" height="373" alt="image" src="https://github.com/user-attachments/assets/ea70fe36-844e-4ee4-a9d5-e82471bedfee" />
•	Select the model number, in our case it is the “cisco ip communicator”  • next  
<img width="964" height="707" alt="image" src="https://github.com/user-attachments/assets/d75a39e8-0675-429a-89d4-e9888e68d746" />
<img width="975" height="509" alt="image" src="https://github.com/user-attachments/assets/a74ad9c0-fee9-466b-8722-c7c8750bcb95" />
•	Next, we need to configure rest of the information  
•	Go to cmd prompt in your laptop and find its mac address, using that information we need to fill the device name    
•	In the device name type in SEP and paste that mac address removing all the hyphen between the numbers
<img width="782" height="680" alt="image" src="https://github.com/user-attachments/assets/1e880209-f46d-4831-959b-664f24eb9c45" />
<img width="769" height="665" alt="image" src="https://github.com/user-attachments/assets/6e451847-8ec0-48b5-8c90-5faa1946981d" />
<img width="765" height="687" alt="image" src="https://github.com/user-attachments/assets/faad4c37-0fed-4598-b7b7-9da48764110a" />
<img width="802" height="661" alt="image" src="https://github.com/user-attachments/assets/d5ecac41-1550-41b8-a82b-18c365a4dbfe" />
•	Save the configuration   
•	Next page , click on (line 1 add a new DN)  
<img width="641" height="565" alt="image" src="https://github.com/user-attachments/assets/76084dfc-7804-4de3-947f-aebf05aba651" />
•	Provide a unique number that is not used already and save   
•	To find out the numbers that are available and not taken already follow the steps below   
<img width="557" height="625" alt="image" src="https://github.com/user-attachments/assets/8cbe9d99-cd0a-44de-8119-e0fad61b2ecc" />
•	U will see an empty page, just click find, this will show you the list of numbers that is already taken   
•	Just choose the one that is not taken   
<img width="805" height="504" alt="image" src="https://github.com/user-attachments/assets/bd49ad9c-e786-47a2-a997-b45902afabb1" />
<img width="789" height="573" alt="image" src="https://github.com/user-attachments/assets/0ba75229-4763-43e4-a464-206876654bf1" />
•	Once saved, select apply config | ok   
<img width="716" height="597" alt="image" src="https://github.com/user-attachments/assets/0f41dc57-3954-46db-9d8b-e530b517260f" />
<img width="824" height="660" alt="image" src="https://github.com/user-attachments/assets/54fcfa49-f50c-423b-8a7d-4a70b81886ec" />
•	Once that’s done go back to your pc and exit the cisco ip communicator   
<img width="959" height="478" alt="image" src="https://github.com/user-attachments/assets/8d98d763-b4a4-484d-8036-19cee9b3e052" />
•	Restart the app as administrator  
•	It should configure the phone with the new number  
•	Try making a phone call the other numbers in the directory    
<img width="486" height="525" alt="image" src="https://github.com/user-attachments/assets/f1052e14-3ca3-4f55-abaa-deca3155c5bc" />
In conclusion, with the successful completion of these steps, users can confidently set up their soft clients and verify functionality through test calls. This document empowers users to manage communication systems effectively, enhancing productivity within their organization.  


