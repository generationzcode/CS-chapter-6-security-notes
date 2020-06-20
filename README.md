# CS-chapter-6-security-notes
## Definitions:
*  Assymetric encryption - An encryption system where the key is kept secret by one side of the communication
*  Biometric check - A security check relying on checking one or more of your physical features such as fingerprints
*  Cypher text - Text which has been hidden using encryption. Cypher text can only be read by a computer which knows the encryption key
*  Decryption - Turning cypher text into plain text which is readable
*  Denial of sevice - An attack on a computer overloading it with messages and queries so it stops working.
*  Encryption key - A hidden number value which the computer can use to decrypt text
*  Firewall - a combination of software and hardware which screens the data coming in and out of the system
*  Identitiy theft - pretending to be another person online
*  Malpractice - Making mistakes while using a computer system. Can result in loss of data or loss of privacy
*  Pharming - Making a fake website to trick people into sending you their identity details
*  Phishing - sending fake emails to trick people into sending you their identity details
*  Symmetric encryption - an encryption system where the encryption key is knonwn by both sides of the communication
## Accidental Damage And Malicious Actions On Data
*  data is an asset to a bussiness
*  a bussiness invests time and money into collecting data
### Data loss
*  Data can be lost by mislaying the data storage device or accidentally deleting it
*  This can severely affect bussinesses. For example the data loss of a database of customers bank details would mean the company will not be able to get money from its consumers
### Data corruption
*  Data corruption is when the data is damaged or changed.
*  Changes to the data can be changing the file format to a wrong format or causing the data to be innacurate
*  Damage to data like in the case of scratching a CD-R can lead to corruption of that data
*  If data is severely damaged it doesnt make sense anynmore at all and cant be read.
### Unauthorised access to data
*  Privacy means data can only be read from or copied by those who have permission.
*  Unauthorised access is when someone without permission copies or reads that data. 
*  An example would be someone copying user's login credentials from a database without permission to do so
### Unauthorised changing of data
*  Integrity of data refers to the data being protected from unauthorised changes
*  Someone doing this would be "hacking"
*  Doing this would be a threat to the data integrity
*  some people might want to do this to increase the amount of money in their bank accounts
### Internal threats to data
#### Hardware fault
*  faults in storage devices or media can result in data loss.
*  the computer may be damaged by careless handling
*  there may be a fire in the computer
*  cables might have problems
*  A backup if the can be a good solution to these issues
#### Software fault
*  Software faults can cause the data to be corrupted or accidentally deleted
*  it can give out the wrong outputs causing corruption
*  It can accidentally delete data or send it to a person who doesnt have permission to see it
*  These can be prevented by testing software before using it
### External threats
*  earthquakes,power cuts, floods
*  social unrest
*  companies solve such problems by having backup of data and power generators in case of power loss
*  crime and malpractice
*  computer viruses and other malware
*  hackers (computer hackers)
### Malpractice
*  this means not doing your work properly usually by mistake
*  mistakes might include:
*  leaving the computer logged in when you go out of the room so that  someone else can access your files
*  telling someone your credentials
*  downloading trojan horses or opening damaged emails
*  using work computers for personal bussiness causing higher chance of downloading malware
### Crime
*  piracy of movies/books/games without permission
*  hacking
*  creating and distributing malware
*  identity theft
*  damaging/stealing storage media or coputer not possessed by you
malware run in executable files. These run on your computer without you noticing them
## The need to keep online systems safe from attacks including denial of service attacks,phishing, pharming
### DOS(denial of service attacks)
*  denial of service attacks are a way of harming  a companies computer sevices by flooding them with more requests than they can handle. This makes them go very slowly and crash. Thus making it impossible for customers to contact the compnay because of how busy the servers are
*  A normal denial of service attack can be bloacked easily by blocking tha address flooding the server
*  A ditributed denial of service attack is much more serious (DDOS). This sends in millions of requests from many different computers making it impossible to block all of them
### Identity theft
*  This happens when a criminal finds out your personal details. They can pretend to be you online and do all sorts of things
*  They can withdraw money from your bank account and then use that money to buys something
### Phishing
*  this is done by sending a fake email/message.
*  it will look like its from a trusted company
*  the fake email will ask you to send your credentials
*  This is a trick the criminals want to commit identity theft
### Pharming
*  typically done by making a fake website
*  website looks like that of a real company/bank
*  They will ask for your personal details and then commit identity theft
##  How data is kept safe when stored and transmitted
*  proof of identity is used to control access to data
*  it prevents identity theft
*  the three main kinds are passwords,ID cards and Biometric checks
### passwords:
*  a password is a string of letters and numbers to prove who you are
*  it can easily be typed in
*  criminals will try a lot of combinations of passwords before they get the right one so use a complex password
### ID cards:
*  read by a special card reader.
*  often used along with password(such as a 4 digit pascode)
*  also often has a photograph on it as additional check
### Biometric check:
*  This is a record of physical characteristics used to confirm your identity
*  features used include - fingerprint/thumb print/palm print, pattern of iris, features of face such as distance between eyes
*  special equipment such as a palm reader, an iris scanner and a facial recognition system are used for these
*  impossible to steal these features (like thumb print and iris)
### Adtvantages and disadvantages of each
#### passwords:
##### advantages:
*  easy to imput into device
*  can be changed often
##### disadvantages:
*  easy to forget
*  many use weak passwords
#### Biometrics:
##### advantages:
*  You dont need to remember anything
*  Uses features unique to you
##### disadvantages:
*  Requires special equipment
*  More expensive than other options
*  Cannot be changed if system is compromised
#### ID card:
##### advantages:
*  can be changed or taken away if permissions change
*  can be check by a person as well as computer
##### disadvantages:
*  requires special equipment
*  cards can be lost or stolen
### routers
*  A LAN is something that connects all computers in a network
*  A LAN is connected to the internet through a router
### proxy servers
*  A proxy server handles all communications between the two computers or networks
*  A user will request data from the internet, the proxy server will take that data from the internet and the user wil get that data from the proxy server
*  proxy server a lot like a middle man
*  the user does not make a connection directly to the web page
*  proxy server speeds up the connection. After going to a website once, it keeps that data stored
*  people who run the proxy server can look at the websites people look at
*  privacy for the user. no direct connection to the website
*  safer. All content can be checked before it is passed to the user
### firewalls
*  barrier between LAN and internet
*  it will only pass data that it checks and sees that its safe
*  hardware firewalls are pieces of hardware. They have processors. The wired or wireless link must pass through the firewall to get into the network
*  software firewalls are sets of instructions that tell the processor what to do with the signals . A software firewall will have rules to tell the difference between safe data and dangerous malware
### Open Systems interconnection(OSI)
*  A protocol is a standard of communication
*  the OSI model describes these protocols
*  layer 1 for hardware and layer 2 for transmitting binary digits
### Transport layer
*  this is layer 4 of the OSI  mode. It has protocols for how two devices at either end of a communication link talk to each other
*  transport protocols control the end-to-end communications, not the links in between. The TCP/IP protocolis part of the transport layer
### Transport layer security
*  transport layer protocol controls communication between two distant decvices
*  it makes the communication private
*  The TLS has 2 parts - tls record protocol(standard to break the communication up into records) and the tls handshake
### TLS handshake
*  The TLS handshake is a signal sent between two devices at the start of communication. 
*  The handshake protocol lets each device check that the other is genuine
*  A genuine website has a certificate issued by a recognised certificate authority
*  during the handshake the certificate is checked
*  during this handshake an encryption key is exchanged
### CA (certification authority)
*  authentication is important in the TLS handshake
*  Certificates are issued by a certification authority. An example of a CA is Verisign
*  If a business requests for a certificate from a CA, it will check the business and see if it really does what it says it is doing
*  It will check the bussiness regularly. If it is doing any fraud it will revoke the certificate
*  Your computer has a list of trusted CAs. If the website has a certificate from one of these CAs, then the certificate is good and communication an proceed on safety
### SSL(secure sockets layer)
*  this was the protocol used before TLS
*  it is less secure than TLS
*  it does the same thing as TLS
*  You can only use either TLS or SSL
when you go shopping, you need to provide your bank details. A criminal could abuse this and trick you into giving these details to him. The TLS protocol prevents this by checking whether the website you are using is real. Then it sends your bank details using encryption.
### Encryption
*  plain text are ordinary words and numbers. It is insecure. Can be read by anyone
*  cypher text is plain text that has been scrambled or changed by a secret formula.It is secure. Can only be read by the people who have the encryption key
*  the process of converting plain text to cypher text is called encryption
*  two stages of encryption are:encrypt -> decrypt
*  the sender encrypts the message
*  the reciever decrypts the message
#### symmetric encryption
*  in symmetric encryption the key is the same on both sides of communication. The key is kept secret.
*  The issue with symmetric encryption is that the key must be sent through the internet before being used
*  anyone with the key can intercept the messages
#### asymmetric encryption
*  in assymetric encryption there are two keys - the public and private key. The two are mathematically linked.A message encrypted with one key can only be decrypted with the other key
*  the public key is used to encrypt the data
*  the private key is used to decrypt thr data
*  suppose alice wants to send bob a message but eve is listening in. Alice sees Bob's pubic key (which is available to everyone) and encrypts the message. Bob decrypts the message with his private key. Eve who only has access to Bob's public key, not private key will now be able to decrpyt the data alice sends bob.
*  assymetric encryption is slower than symmetric encryption. But slower
## examples of these systems in use
*  banking - online banks use encryption,passwords and security protocols so no one else can access your account
*  ecommerce - these sites require you to prove your identity, encrypt your message and check if the site is real or not to be safe
*  teleworking (working from home) - these have an secure link where all data is encrypted to your office so it is safe
*  cloud services - these require passwords and have enryption
