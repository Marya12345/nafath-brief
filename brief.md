Version: NAFATH-V1
Track:  Software

#Overview
A government single sign-on service allows citizens to access different government services through one account using a website or mobile app. Software technologies such as OAuth 2.0 and OpenID Connect support authorization and authentication. Artificial intelligence can help detect suspicious login attempts, but its risks must be assessed before launch. Mobile security controls access to sensitive device features, while networking technologies protect communication and DNS queries. Cybersecurity measures, including phishing-resistant authentication, help reduce account theft. Data protection practices support the responsible collection, storage, and processing of citizens’ personal information under Oman’s Personal Data Protection Law. These six areas work together to make the service secure, reliable, and convenient. This brief examines how OAuth 2.0 and OpenID Connect differ and how they support secure login and delegated access.


#Software
OAuth 2.0 and OpenID Connect are related but have different purposes. OAuth 2.0 allows an application to access resources with permission from the user. OpenID Connect adds an identity layer to OAuth 2.0 and helps an application verify who the user is. For the government login service, OpenID Connect is suitable for user login, while OAuth 2.0 supports authorized access to other services and resources.

Resource: OpenID Connect Core 1.0 - https://openid.net/specs/openid-connect-core-1_0.html


#AI
An AI model can help detect suspicious login attempts by identifying unusual patterns, such as unexpected locations or unfamiliar devices. Before launching the model, the authority should assess risks such as incorrect alerts, missed attacks, privacy issues, and unfair results. The NIST AI Risk Management Framework provides guidance for identifying, assessing, and managing AI risks. The authority should test the model and monitor its performance regularly.

Resource: NIST AI Risk Management Framework - https://www.nist.gov/itl/ai-risk-management-framework


#Mobile
Android runtime permissions allow users to control an app’s access to sensitive features and information, such as the camera, microphone, and location. An app should request a permission when the user tries to use the feature that needs it, rather than asking for every permission at the beginning. The app should explain why access is needed and continue to work where possible if the user denies permission.

Resource: Android Developers — Request app permissions - https://developer.android.com/training/permissions/requesting

#Networking
DNS over HTTPS (DoH) sends DNS queries through an encrypted HTTPS connection. This helps prevent other people on the same network from easily reading or changing DNS queries. However, DoH does not hide all internet activity, protect against phishing, or make a website safe. The government login service should use DoH as one layer of protection alongside other security controls.


Resource: Cloudflare Learning Center — What is DNS over HTTPS? - https://www.cloudflare.com/learning/dns/dns-over-https/


#Cybersecurity
Phishing-resistant authentication helps protect users from fake login pages that try to steal passwords or verification codes. Passkeys and security keys using FIDO2/WebAuthn can provide phishing-resistant authentication. By contrast, SMS codes and ordinary one-time passwords can still be stolen or tricked from users. The authority should consider phishing-resistant methods to protect citizens’ accounts, especially when accessing sensitive government services.

Resource: CISA — Implementing Phishing-Resistant MFA - https://www.cisa.gov/resources-tools/resources/implementing-phishing-resistant-mfa


#Data
Oman’s Personal Data Protection Law regulates how personal data is processed. An authority operating a government login service should identify a lawful basis for processing, explain how citizens’ data will be used, apply appropriate security measures, and respect individuals’ rights under the law. It should also manage data sharing and retention responsibly and check the applicable executive regulations and requirements before launching the service.

Resource: Oman Ministry of Transport, Communications and Information Technology - https://www.mtcit.gov.om/

#Misconception in My Track
A common misconception is that OAuth 2.0 and OpenID Connect are the same technology and can be used interchangeably. In fact, OAuth 2.0 is mainly designed to provide authorized access to resources, while OpenID Connect adds an identity layer that allows an application to verify a user’s identity. This difference matters for the government login service because secure login requires identity verification, not only permission to access resources. OpenID Connect is therefore suitable for authentication, while OAuth 2.0 supports delegated authorization.

Evidence: OpenID Connect Core 1.0, section 1 — Introduction.


#Open Question
How can the government login service balance strong account security with an easy login experience for citizens who use different devices and have different levels of digital knowledge?
