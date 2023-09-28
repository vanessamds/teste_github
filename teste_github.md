Escrevendo uma linha 
mais uma linha //Initialized empty Git repository in C:/Users/CLIENTE/Desktop/GitHub_teste/.git/
PS C:\Users\CLIENTE\Desktop\GitHub_teste> git add .
PS C:\Users\CLIENTE\Desktop\GitHub_teste> git commit -n "escrevendo as linhas de teste"
error: pathspec 'escrevendo as linhas de teste' did not match any file(s) known to git
PS C:\Users\CLIENTE\Desktop\GitHub_teste> git commit -m "escrevendo as linhas de teste"
[master (root-commit) 8980bc8] escrevendo as linhas de teste
 1 file changed, 1 insertion(+)
 create mode 100644 teste_github.md
PS C:\Users\CLIENTE\Desktop\GitHub_teste> git branch -M main
PS C:\Users\CLIENTE\Desktop\GitHub_teste> git remote add origin git@github.com:vanessamds/teste_github.git
PS C:\Users\CLIENTE\Desktop\GitHub_teste> git push -u origin main
The authenticity of host 'github.com (20.201.28.151)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 257 bytes | 128.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:vanessamds/teste_github.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\CLIENTE\Desktop\GitHub_teste> //