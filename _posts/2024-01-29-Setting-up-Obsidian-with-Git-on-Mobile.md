Managing my notes, tasks and todo items on the go


###  Obsidian on the go
Since I use obsidian to manage ephemeral things like my daily todo list, active tasks and to keep track of reminders I found myself needing to interact with my Obsidian Vault on my phone. There have been a few times I've meant to copy something from my phone's note taking application to obsidian only for it to get lost in the day. This serves mostly as a reminder to myself if I ever have to do it again, but if an internet stranger stumbles on this page in the same predicament perhaps it could be helpful for them as well

### Requirements
Thankfully nothing is *really* required that you likely don't already have, but to be thorough; you will need:
1. [Obsidian Mobile](https://obsidian.md/mobile)
2. [Obsidian Git Plugin](https://github.com/denolehov/obsidian-git)
3. [GitHub Account](https://github.com) (or other remote git provider)

### Step 1: Getting your vault on to your cellphone
I currently own an android device, that is not *rooted* so installing git on the device itself was not an option. Thankfully it was easy enough to plug my phone into my machine and manually copy my Obsidian Vault into my phones storage. Although I'm not 100% sure, iPhones likely have the same capacity.

Once your Obsidian Vault is on your phone there is only one additional step

[!important]
Your remote in Git must be set to use HTTPS and not SSH


### Step 2: Configuring Obsidian-Git on your phone
Given that we can't install git on the mobile device and likely can't configure SSH keys we'll have to rely on two things
1. Obsidian Git's built in JS-Git client
2. Personal Key Authentication w/ Github
The first of which is configured automagically when installing obsidian git and the second is incredibly easy. 

For GitHub:
1. Login
2. Navigate to Settings
3. Navigate to Developer Settings
4. Navigate to Personal Access Tokens 
5. Click Generate New

This will serve as your password when configuring the [Obsidian Git Plugin](https://github.com/denolehov/obsidian-git).  





### That's it!