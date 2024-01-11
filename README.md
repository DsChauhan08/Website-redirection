# 🌐 Website Redirection Extravaganza 🌟

## 🚀 Crazy Wi-Fi Ideas Discussed:

I'm on a mission to spice up my Wi-Fi – picture this: anyone searching for YouTube or any site ends up on my Motivation website. Let's dive into the wild world of Wi-Fi redirection!

## 🤓 Keep It Ethical

Before we embark on this coding adventure, a friendly reminder: it's all in good fun and for learning purposes. No mischief here! Stick to the rules and let's keep it ethical.

**Quick Note:** Coders with principles – we follow terms of service.

## 🛠️ Basic Gear

1. **Networking Basics:** A dash of network know-how.
2. **Router Control:** Have your router credentials ready for the grand entrance.

## 🚀 Step-by-Step Dive

### Step 1: Router HQ 🕵️‍♂️

1. Open your browser and teleport to the router's base (`192.168.1.1` or `192.168.0.1`). Check the router's manual for the secret handshake.
2. Slide in using your admin credentials – you're now in control.

### Step 2: DNS Discovery 🔍

1. Embark on a quest to find the DNS (Domain Name System) settings. This is where the magic brews.

### Step 3: Code Adjustment 🌪️

- **Tweak the DNS Server Addresses:**
  - We're playing DNS maestro – changing default addresses to custom ones. DNS translates human-friendly names to computer-friendly IP addresses.
  - **Example (Using Google Public DNS):**
    - Primary DNS: `8.8.8.8`
    - Secondary DNS: `8.8.4.4`
  - Configuring the router to use Google's DNS servers – the wizards of reliability and speed.
  - **To implement this:**
    - Navigate to DNS settings in your router.
    - Replace the old addresses with Google's magic numbers.
  - **Why Change DNS?**
    - Custom DNS = control over name resolution. Some offer extra features – ours is redirection.
  - **Save Changes:**
    - Seal the spell by saving in your router settings. The router is now under your DNS charm.

### Step 4: Redirect Script 🎭

1. Journey to your chosen DNS service settings (e.g., OpenDNS's lair).
2. Hunt for domain redirection options. For YouTube and Instagram redirection, add these magical spells:
   - Redirect `www.youtube.com` to "website.com"
   - Redirect `www.instagram.com` to "website.com"

### Step 5: Save & Deploy 🤞

1. Hit 'Save' in your router settings – a stroke of the keyboard to make it permanent.
2. Reboot the router or perform a DHCP dance to unleash the new DNS wizardry – our spell is cast.

