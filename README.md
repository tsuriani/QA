# QA Automation
Aprendiendo Git con mi cuenta personal

- git init
- git clone
- git add
- git stash
- git checkout -b
- Solucion de conflictos con Git Merge
- Rebase y que hace
- git pull
- git push para subir cambios a remoto
- Cherry Pick (toma un commit en particular del PR ó Branch)
- Reset (hay varios)

**Git clone**: clona un repositorio Remoto (GitHub) hacia Local (PC), para eso requiere el path del proyecto (git@github.com:tsuriani/QA.git) y tener configurada la SSH Public Key configuradas en Git y GitHub

1. Open GitBash
2. Write “ssh-keygen” and press enter
3. Press enter to accept the default key and path
4. Write a passphrase and press enter
5. Write the same passphrase again, then press enter
6. Write “dir .ssh” and press enter
7. Write “eval $(ssh-agent)” and press enter
8. Write “ssh-add ~/.ssh/id_rsa” (private key file and its location)
9. Write the same passphrase again, then press enter
10. Go to Bitbucket > Personal Setting > Add key (https://bitbucket.org/account/settings/ssh-keys/)
11. Go to the location of the Public key file
12. Open that file with Notepad and copy all its contents
13. Return to Bitbucket, then write “Default public key” on “Label” input
14. Paste the copied content from the Public key file on “Key” input, and press “Save”
15. Return to Git Bash, write “ssh -T git@bitbucket.org” and press enter

