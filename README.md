1. Foundations before working on projects

- Learn about how data should be stored on disks (FAT32, NTFS, ext4, APFS)

- Understand what it means by "deleted" means at a storgate level (data is often still there until overwritten)

- Grasp RAM vs disk vs cache - knowing what kind of evidence can live where.

- Study chain of custody and evidence handling (this is so i can relfect real forensic workflow)

2. Core Tools to get Hands-On With

- Autops / Sleuth Kit
- FTK Imager - creating forensic disk images
- Volatility - memory forensic
- Wireshark - network forensic

3. Up-incoming practice scenarios

- I will create my own test cases: delete files, browse the web, send emails, then make a forensic image and try to recover artifacts.

- I will then download forensic challenge images (there are some online for me to ues)

- Analyze metadata (pictures, documents, PDFs)

4. Learn how to analytically think

- Tools will parse data for me, but I'll need to interpret it.

- For example:

    "I see a browser history record...what does it mean to the context of the case?"
    
    "This file was deleted at 3 PM, but a registry log shows USB activity at 3:05... suspicious."
    
    
5. Documentation

- In forensics, I'll need to know that reporting is as important as finding evidence. Practice documenting EVERYTHING in my findings clearly, step by step, like if I submit it in court.
