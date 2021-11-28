# Anti Procrastination hosts file for uBlock and Windows..
Host file collection created primarily for linking to my uBlock Origin add-on in various browsers I use. List primarily created to avoid procrastination, blocks garbage sites designed to waste your time. Do note, some sites like Reddit, Twitter and YouTube are left unblocked cause they are needed for "work" these days (necessary evil), but you can still block them using [XS](https://raw.githubusercontent.com/zero5zero6zero7/anti-procrastination-hosts-file/main/anti-procrastination-hosts-file-XS) and [XS-ULTRA](https://raw.githubusercontent.com/zero5zero6zero7/anti-procrastination-hosts-file/main/anti-procrastination-hosts-file-XS-ULTRA) hosts files (read below for more info).

---

## Which hosts file to use?
[anti-procrastination-hosts-file](https://raw.githubusercontent.com/zero5zero6zero7/anti-procrastination-hosts-file/main/anti-procrastination-hosts-file) doesn't block Twitter, YouTube and Reddit. 
[anti-procrastination-hosts-file-XS](https://raw.githubusercontent.com/zero5zero6zero7/anti-procrastination-hosts-file/main/anti-procrastination-hosts-file-XS) blocks Twitter.

[anti-procrastination-hosts-file-XS-ULTRA](https://raw.githubusercontent.com/zero5zero6zero7/anti-procrastination-hosts-file/main/anti-procrastination-hosts-file-XS-ULTRA) blocks Twitter, Reddit and YouTube.

All hosts files only differ in blocking Twitter, Reddit and YouTube. Rest of the blocks remain the same. I personally use [anti-procrastination-hosts-file-XS](https://raw.githubusercontent.com/zero5zero6zero7/anti-procrastination-hosts-file/main/anti-procrastination-hosts-file-XS).


---

## What does this host file block?
Primarily, porn sites or sites that are borderline softcore porn sites these days (Instagram). 

Do note, even Twitter is pretty much a porn paradise, but ONLY when you follow people who do porn or someone you follow is following such pornographic accounts. Unfollow those people and block porn "stars" if you don't want to see porn on Twitter. I generally avoid Twitter but never follow porn related content on my account, so this is why Twitter isn't blocked. 

Instagram on the other hand is 99% porn and 1% content nobody cares about. So it gets blocked.


---

## Are these hosts originally compiled by you? What about updates?
No, I have combined multiple other hosts files into one "mega" file for my personal use. I do end up adding custom sites here and there to the list though. Use this if you're a game developer or a writer and want a more "curated" online experience. A lot of sites for reference, 3D models, discussions, etc., are left unblocked. Whole reason I'm adding this to Github is to make it easy to add it to [uBlock Origin](https://github.com/gorhill/uBlock#ublock-origin).

RAW files will keep getting updated. I've been using these hosts for years so I keep adding more pointless garbage to block, especially these days thanks to Covid when most of us are glued to computers 24/7.


---

## uBlock Origin vs Windows system HOSTS file block, which is better?
Personally, I use both, however I tend to move some hosts to uBlock only on Firefox (or Chrome). uBlock allows you to temporarily unblock a host, or just disabling uBlock on that site will allow you to browse it. Host file block on Windows makes it harder and sometimes, you'll be forced to restart system to unblock a domain completely or even edit the host file. Do note, using Windows hosts will block any app from connecting to the domain blocked in hosts file. This is pretty useful to disallow ANY app from connecting to a specific domain (especially malware).


---
---



# How to add this host file to uBlock Origin?

>1. Open uBlock Settings

>2. Select the "Filter Lists" tab, scroll down to the end.

>3. Under "Custom" section, checkbox "Import" and paste the URL of the [RAW hosts list](https://raw.githubusercontent.com/zero5zero6zero7/anti-procrastination-hosts-file/main/anti-procrastination-hosts-file).

>4. Apply changes.

>5. Done.



# How to add this host file to Windows hosts?
>1. Open the [RAW hosts list](https://raw.githubusercontent.com/zero5zero6zero7/anti-procrastination-hosts-file/main/anti-procrastination-hosts-file).

>2. Backup default Windows HOSTS file, Copy and paste all entries from RAW list to the Windows HOSTS file "C:\Windows\System32\drivers\etc\HOSTS" using Notepad, then save the hosts file (without txt extention).
 
>3. Restart browsers for changes to be visible (or maybe PC).


# Use Hostman to edit Windows HOSTS.
>You can also use a freeware app like [Hostman](https://www.abelhadigital.com/hostsman/) to edit, manage and update Windows hosts. Makes sure to create backups of default HOSTS file first.

