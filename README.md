# ABCrowdMed
Crowdsourcing for medical and healthcare which is an application of crowd intelligence has become a novel and important auxiliary way for traditional healthcare.
It gets popular and shows a huge application perspective. In a crowdsourcing platform for healthcare, by posting a task, patient can be a requester who recruits
workers, i.e. doctors, to provide professional advice. However, privacy concerns make a huge obstacle to patients willing to participate the crowdsourcing as 
task data definitely contains much sensitive personal information. In this article, we propose a novel attribute-based lightweight and dynamic ﬁne-grained 
worker selection scheme, ABCrowdMed, with privacy-preserving in which a requester can select workers in a non-interactive way by exploiting an elaborated novel 
CP-ABE scheme with online/offline encryption, verifiable outscouring decryption, revocation, and hidden policy properties. Moreover, a requester can revoke, 
and update his/her tasks by withdrawing some workers' decryption privileges. Participants can also release the computation burden with aid of a third-party 
server. Our proposed scheme's security is been proved selectively secure under the decisional (q-1) assumption, it also satisfies forward/backward security.
We also evaluate ABCrowdMed's performance and compare it with the most related scheme. The evaluation results show that our scheme achieves the lowest 
computation costs with low complexity compared with other state-of-the-art model placement methods, and also show that our scheme is suitable for computing 
resource-constrained environments.


Implementation
The hardware environment is Intel(R) Core(TM) i5-6600 CPU @ 3.30GHz (4 CPUs), 8GB RAM, and the software environment is JDK 17.0.4.1 and IntelliJ IDEA Community Edition 2022.2.3. For portability, we chose the JPBC framework by De Caro and Iovino in 2011, a Java library that ported the Pairing-Based Cryptography (PBC) library (instead of calling PBC written in C via JNI).


Acknowledgments
This work was supported by the Foundation of Science and Technology On Communication Security 
Laboratory of China(61421030108022110), the Open Fund of the State Key Laboratory of Integrated Services Networks, Xidian University, No.ISN23-23, the National Natural Science Foundation of China (U2001205, 61802241, 61802242), and the Fundamental Research Funds for the Central Universities (GK202007031).
