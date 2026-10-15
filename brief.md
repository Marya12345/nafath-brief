Version: NAFATH-V1
Track:  Software

#Overview
A secure national digital login service allows citizens to access different government services using one account through a website or mobile app. Software technologies such as OAuth 2.0 and OpenID Connect support secure access and user authentication. Artificial intelligence can help identify suspicious login activity, but its risks must be assessed before use. Mobile security protects information stored on users’ devices and controls access to sensitive features. Networking technologies help devices communicate securely, while DNS over HTTPS can protect DNS queries from being easily observed by others on the network. Cybersecurity methods, including phishing-resistant authentication, reduce the risk of account theft. Data protection practices help the authority collect, store, and process citizens’ personal information responsibly under Oman’s Personal Data Protection Law. These six fields work together to make the service reliable, secure, and convenient for citizens. This brief also examines how OAuth 2.0 and OpenID Connect support secure login and delegated access.
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
#Cybersecurity
#Data
#Misconception in My Track
#Open Question
