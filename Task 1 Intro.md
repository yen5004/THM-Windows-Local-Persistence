
After gaining the first foothold on your target's internal network, you'll want to ensure you don't lose access to it before actually getting to the crown jewels. Establishing persistence is one of the first tasks we'll have as attackers when gaining access to a network. In simple terms, persistence refers to creating alternate ways to regain access to a host without going through the exploitation phase all over again.
|![image](https://github.com/user-attachments/assets/19c2fa9f-c662-4d95-9bca-37f16ab72920)|
|---|
Backdoored Phone

There are many reasons why you'd want to establish persistence as quick as possible, including:

* **Re-exploitation isn't always possible:** Some unstable exploits might kill the vulnerable process during exploitation, getting you a single shot at some of them.
* **Gaining a foothold is hard to reproduce:** For example, if you used a phishing campaign to get your first access, repeating it to regain access to a host is simply too much work. Your second campaign might also not be as effective, leaving you with no access to the network.
* **The blue team is after you:** Any vulnerability used to gain your first access might be patched if your actions get detected. You are in a race against the clock!

While you could do with keeping some administrator's password hash and reusing it to connect back, you always risk those credentials getting rotated at some point. Plus, there are sneakier ways in which you could regain access to a compromised machine, making life harder for the blue team.

In this room, we'll look at the most common techniques attackers use to establish persistence in Windows systems. Before going into this room, it is recommended to be familiar with Windows systems fundamentals. You can check rooms on the matter in the following links:

Windows Fundamentals 1
Windows Fundamentals 2
Powershell is also used extensively throughout this room. You can learn more about it in the Hacking with Powershell room.
(All links found on readme page)

![image](https://github.com/user-attachments/assets/8a0e0d54-5d68-47bc-986e-027cc7ef6231)
