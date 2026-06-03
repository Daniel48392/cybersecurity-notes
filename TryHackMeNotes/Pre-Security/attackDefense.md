## What I learned:
  - Pillars of CyberSecurity (CIA Triad):
      - Confidentiality - sensitive data can only be accessed by authorised individuals
      - Integrity - ensures unauthorised individuals cannot modify data
      - Availability - data and services must be available to authorised individuals when needed, example when this is jeopardized is in a DDoS attack
  - Plain text - "Standard text"
  - Ciphertext - scrambled text, "dsufdsf dssd"
  - Key - the value that tells the algorithm how to scramble and unscramble text
  - Encryption alogrithm - process that uses the key on the message
  - Symmetric encryption - sender and recipient both have the same key used to encrypt and decrypt messages, its fast however the shared key can be intercepted
  - Asymmetric encryption - solves the issue of symmetric encryption uses a public and private key, messager uses the recipients public key to encrypt the message, the recipient decrypts the message with their private key, this is because there public and private key are mathmatically related
  - Encryption with HTTPS - browser requests websites public key, website sends public key wrapped in certificate, browser and website then communicate to get a shared symmetric key and then switch to much faster symmetric encryption, asymmetric encryption guarantees the symmetric key was never intercepted
  - Certificate - contains public key, who it belongs to and a trusted authority digitally signs it
  - Enumeration - collecting information regarding systems, services and users to find vulnerabilities
  - Dictionary attack - Using a predefined wordlist to guess a password or username
  - Threat Anticipation - imagine paths a hacker may take to achieve their goals
  - Attack Awareness - study common attack chains as attacks usually occur in stages
  - Risk Prioritisaton - defenders need to identify which systems carry more risk than others
  - Continuous Adaptation - threats evolve and vulnerabilities emerge, defense is a continuous process

## Commands
  - `gobuster dir --url http://website.com -w usr/files/wordlist.txt` - used to find hidden files and directories on web servers using the provided list via brute force
  - `hydra -l insertUsername -P passlist.txt www.website.com http-post-form "/login:username=^USER^&password=^PASS^:F=incorrect" -V` - used to brute force into accounts
      - `-l insertUsername` - username being used
      - `-P passlist.txt` - passwords being attempted
      - `www.website.com` - target website
      - `http-post-form` - specifies its a http POST request
      - `"/login:username=^USER^&password=^PASS^:F=incorrect"` - specifies how the login request is sent and how to determine if it successful or unsuccessful
      - `-V` - displays each username and password attempted
