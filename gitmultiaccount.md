#shh config ~/.ssh/config

#user1 account
Host github.com
HostName github.com
User git
IdentityFile ~/.ssh/id_ed25519
IdentitiesOnly yes

#user2 account
Host github.com-user2
HostName github.com
User git
IdentityFile /Users/mugunthan/Documents/mugu/LearnNative/gitssh/user_mugu
IdentitiesOnly yes
