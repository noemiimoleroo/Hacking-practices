
Noemí Molero


**Security in Mobile and IoT Devices**
## <a name="_toc189561370"></a><a name="_toc189561585"></a><a name="_toc189564196"></a>**Security in Systems, Networks, and Services**
**Hacking Android phone with msfvenom**


### <a name="_toc189564197"></a>**Introduction:**
In this practice, we'll explore how to ethically hack an Android device using **Msfvenom** and **Metasploit**. Our goal is to create a malicious APK capable of establishing a **remote Meterpreter session** with the attacker’s Kali Linux machine.



















NOEMÍ MOLERO





**INDEX**
#
[Security in Systems, Networks, and Services	1](#_toc189564196)

[Introduction	1](#_toc189564197)

[Exercise 1: **Hack an Android Mobile with Msfvenom**	3](#_toc189564198)

[Conclusion	7](#_toc189564199)




##
##
## <a name="_toc189564198"></a>**Exercise 1: Hack an Android Mobile with Msfvenom**
##### **a.** Create a malicious APK with Msfvenom
We’ll generate a malicious APK containing a **Meterpreter payload** to establish a remote connection between the Android device and the attacker.

![](img/HAP/spose.Words.794fd418-b75c-4d75-abf7-1b5d86a1386a.001.png)

![](img/HAP/Aspose.Words.794fd418-b75c-4d75-abf7-1b5d86a1386a.002.png)


**b.** Set up the Metasploit listener

![](img/HAP/Aspose.Words.794fd418-b75c-4d75-abf7-1b5d86a1386a.003.png)

![](img/HAP/Aspose.Words.794fd418-b75c-4d75-abf7-1b5d86a1386a.004.png)

**c.** Run the malware on your mobile or Android virtual machine

Access the APK from your mobile device or emulator and install it.

- Enable installation from **unknown sources** if necessary.
- Grant the app all permissions requested.

![](img/HAP/Aspose.Words.794fd418-b75c-4d75-abf7-1b5d86a1386a.005.png)    ![](img/HAP/Aspose.Words.794fd418-b75c-4d75-abf7-1b5d86a1386a.006.png)


















![](img/HAP/Aspose.Words.794fd418-b75c-4d75-abf7-1b5d86a1386a.007.png)

![](img/HAP/Aspose.Words.794fd418-b75c-4d75-abf7-1b5d86a1386a.008.png)

![](img/HAP/Aspose.Words.794fd418-b75c-4d75-abf7-1b5d86a1386a.009.png)
#####
#####
##### **d.** Hide the malware icon
This removes the malware icon from the home screen, making it less likely for the victim to notice.

![](img/HAP/Aspose.Words.794fd418-b75c-4d75-abf7-1b5d86a1386a.010.png)


**e.** Send an SMS from Meterpreter

![](img/HAP/Aspose.Words.794fd418-b75c-4d75-abf7-1b5d86a1386a.011.png)

![](img/HAP/Aspose.Words.794fd418-b75c-4d75-abf7-1b5d86a1386a.012.png)

##### **f.** Extract contacts from the device
![](img/HAP/Aspose.Words.794fd418-b75c-4d75-abf7-1b5d86a1386a.013.png)

![](img/HAP/Aspose.Words.794fd418-b75c-4d75-abf7-1b5d86a1386a.014.png)    ![](img/HAP/Aspose.Words.794fd418-b75c-4d75-abf7-1b5d86a1386a.015.png)

##### **g.** Extract SMS messages
![](img/HAP/Aspose.Words.794fd418-b75c-4d75-abf7-1b5d86a1386a.016.png)

![](img/HAP/Aspose.Words.794fd418-b75c-4d75-abf7-1b5d86a1386a.017.png)



**h.** Download an image from the device

![](img/HAP/Aspose.Words.794fd418-b75c-4d75-abf7-1b5d86a1386a.018.png)

Note: Virtual machines may restrict file access.
##### **i.** List available cameras
![](img/HAP/Aspose.Words.794fd418-b75c-4d75-abf7-1b5d86a1386a.019.png)

**j.** Capture a photo

This may not work on a virtual machine but will function on a real Android device.

![](img/HAP/Aspose.Words.794fd418-b75c-4d75-abf7-1b5d86a1386a.020.png)




##### **k.** Experiment with other Meterpreter commands
View running processes:

Useful for identifying interesting or vulnerable processes.

![](img/HAP/Aspose.Words.794fd418-b75c-4d75-abf7-1b5d86a1386a.021.png)

Open a shell on the device

Execute Android-specific commands.

![](img/HAP/Aspose.Words.794fd418-b75c-4d75-abf7-1b5d86a1386a.022.png)















## <a name="_toc189564199"></a>**Conclusion:**
This practice provided a powerful insight into how attackers can exploit vulnerabilities in Android devices using tools like **Msfvenom** and **Metasploit**. By creating a malicious APK and establishing a reverse Meterpreter session, we demonstrated the extensive control that can be gained over a compromised device.

From extracting sensitive information such as contacts and SMS to taking remote photos and executing system commands, we saw firsthand how devastating these attacks can be if devices are not adequately protected.

However, the true value of this exercise lies in understanding how to **prevent and defend against such threats**. By recognizing the signs of malware, regularly updating systems, limiting app permissions, and avoiding downloads from untrusted sources, users can significantly enhance their device security.

Ultimately, this practice underscores the need for vigilance in the digital age, empowering us to better protect our mobile devices and data from malicious actors.

