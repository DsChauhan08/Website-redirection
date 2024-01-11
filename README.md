# Website redirection 

## Idea Discussed:
I want to make some crazy changes my wifi like: 
- When someone searches for Youtube or any website, they are redirected to my Motivation website.

## Guide
This guide is intended for educational and ethical purposes only. Redirecting websites on your own network should be done with proper permissions and respect for others' content.

**Note**: Always comply with the terms of service of the websites you are interacting with.

## Prerequisites

1. A basic understanding of networking concepts.
2. Access to your home router settings.

## Steps

### Step 1: Access Your Router Settings

1. Open your web browser and enter the default gateway IP address in the address bar. Typically, it's `192.168.1.1` or `192.168.0.1`. Refer to your router's manual for specific details.

2. Log in with your router's administrator credentials.

### Step 2: Locate DNS Settings

1. Look for the DNS (Domain Name System) settings in your router's control panel. This is where you can configure how your network resolves domain names.

### Step 3: Modify DNS Settings

1. Change the DNS server addresses to a custom DNS server that allows redirection. Some public DNS services like OpenDNS or Google Public DNS may have features for redirection.

   - **Example (OpenDNS):**
     - Primary DNS: `208.67.222.222`
     - Secondary DNS: `208.67.220.220`

   - **Example (Google Public DNS):**
     - Primary DNS: `8.8.8.8`
     - Secondary DNS: `8.8.4.4`

### Step 4: Redirect Configuration

1. Access the settings of the chosen DNS service (e.g., OpenDNS account settings).

2. Look for options related to domain redirection or blocking. Configure the redirection rules according to your educational purpose.

### Step 5: Save and Apply Changes

1. Save the changes in your router settings.

2. Restart your router or renew the DHCP lease on your devices to apply the new DNS settings.

## Conclusion

Ensure that your actions comply with the laws and terms of service. Responsible use of such techniques is crucial to maintain a secure and ethical online environment.
