# DADE Planning Guide

An outline of a planning guide for your digital estate for Cybersecurity Awareness Month 2025.

## Overview

TBD

## Getting Started

- What is your digital estate?
- Why do you need to plan for the management of your digital estate?
- What can go wrong if you don't effectively plan for your digital estate?
  
- How to plan
    - What are your digital assets?
    - Prioritizing digital assets 
        - Why prioritize?  Often, your digital accounts exist in a state where unlocking access to a few key services - usually an email address and phone - can be used to recover access to *other* accounts.  
            - Everyone is different, but generally the most important assets are your email account(s), mobile ecosystems (mobile phone providers, Apple iCloud/Google), and credential managers (Apple Passwords, Google Password Manager, 1Password, Bitwarden, etc), utilities (land line, home networking via fiber/cable/DSL/sattelite, water, electric, etc.)
            - These accounts *usually* unlock access to everything else... but not always.  If you have hardware security keys or similar devices... 
        - Next, cryptocurrencies
        - Next up are accounts with large platforms (social media, shopping, search,), digital data including photos, home movies, etc.
            - Multiple services may hold photos (e.g. Flickr, Apple Photos, Google Photos, Snapfish, etc.).  The same is true for files, and other kinds of digital data.  If you have a credential manager, use it to find where your data is stored!
            - Alternatively, search your email inbox to find where you have accounts at common platforms.)
        - Local data - what exists on your phone, laptop?  Is this backed up to the cloud?  
        - Backups
            - Home based (local disk, NAS)
            - Online service
        - Home network
          - Local configuration - networks, WiFi SSIDs and passwords
          - Remote configuration via managed provider (e.g. UniFi) 
        - IoT - light switches, robot vacuums, home video surveillance, automobiles, home solar controllers, doors
    - Building the plan
        - Create a list following the priority above for recovery as part of your digital estate
            - You might not get all the details right at first and that's ok!
        - For each element of your digital estate list
            - Name
            - URL (or other relevant identifier)
            - user name
            - Where is the credential stored? (e.g. in 1Password? Apple Passwords? Does the account use single sign on, if so from which account? If there's a second factor, what is it?)
            - are there any other related credentials? (e.g. KBA secret questions?)
            - Does the service offer a legacy contact or other mechanism for delegation of control?  
                - If so, what was the chosen mechanism?  Include URLs or other data as needed.
                - Does the service explicitly ban taking over access to a personal account?
            - How do you want your account managed by your estate?  
                - Need to list options here.
    - Who will manage your digital estate?  
        - How will they know your wishes?  Have you communicated any recovery mechanisms to them already, e.g. Apple's recovery QR code?  
        - How will they get access to your passwords, passkeys, OTPs (SMS and TOTP), and other credentials necessary to access your accounts?
            - If you store data securely in a safe deposit box, it may not be accessible when needed.  Consider how you might be able to store this in a more accessible location, e.g. fireproof safe.  (Consult local laws.)
        - How will you ensure the manager does not get access to the accounts/data before necessary?
        - Have you considered an estate attorney? If so, make sure you share this plan with them.


