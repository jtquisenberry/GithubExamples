# SSH Authentication

https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/github-clone-with-ssh-keys

Create SSH Public and Private Keys

```
# ssh-keygen -o -t rsa -C “ssh@github.com”
```

Check that keys are in ~/.ssh

```
# cd ~/.ssh
# ls
id_rsa id_rsa.pub
```

Display the public key.

```
# cat id_rsa.pub
ssh-rsa DSSEXaasdf2EEEEAsdaEBgQCwsawea
sd9YNasdfaXxkasdfHZgyW7/3WXghBbKasdfKb
ewf17c4asdfHQrasdfasPXai6pMsdfsfXQH00L
```

Copy the text to the clipboard. 

Add public key to GitHub

https://github.com/settings/keys : Profile Picture -> Settings -> SSH and GPG Keys



