
📘 Cisco Introduction to Cybersecurity — Study Notes


🔐 Module 3: Protecting Your Data and Privacy

💻 3.1 Protecting Your Devices

Device_Protection_Checklist:
  - Firewall: "Enable it — controls incoming/outgoing traffic"
  - Antivirus/Antispyware: "Keep installed & updated"
  - OS_and_Software: "Update regularly (patches close vulnerabilities)"
  - Bluetooth:
      status: "OFF when not in use"
    
      reason: "Prevents eavesdropping, remote access, malware spread"
  - Public_WiFi:
      risk: "Data can be intercepted"
    
      solution: "Use a VPN (encrypts your connection)"
  - Wireless_Router:
      mistake: "Hiding SSID or changing default SSID is NOT enough"
    
      fix: "Use strong encryption + strong password"


 💾 3.2 Data Maintenance


 $ backup --schedule regular
> Keep regular backups of important data
> ☁️ Cloud storage = provider handles maintenance cost

$ delete --file secret.docx
> ⚠️ Normal delete does NOT fully erase data (recoverable!)

$ destroy --method physical
> ✅ ONLY guaranteed way to make data permanently unrecoverable
> = physically destroy the hard drive / storage device

$ define encryption
> "Converting data into a form that only an authorized person
>  can read/decrypt, using a secret key or password"
