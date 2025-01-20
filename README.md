# proxmox-nextcloud
## Installation Summary
|                   |                           |                                          |
|-------------------|---------------------------|------------------------------------------|
| **Localization**  | Keyboard                  | German                                   |
|                   | Language Support          | English                                  |
|                   | Time & Date               | Europe/Berlin                            |
|-------------------|---------------------------|------------------------------------------|
| **Software**      | Installation Source       | Closest mirror                           |
|                   | Software Selection        | Minimal Install                          |
|-------------------|---------------------------|------------------------------------------|
| **System**        | Installation Destination  | Automatic partitioning selected          |
|                   | KDUMP                     | Kdump is enabled                         |
|                   | Network & Host Name       | Connected: ens18                         |
|                   | Security Profile          | No profile selected                      |
|-------------------|---------------------------|------------------------------------------|
| **User Settings** | Root Password             | Root password is set                     |
|                   | User Creation             | User tobias will be created              |
|-------------------|---------------------------|------------------------------------------|

<details>
<summary>Lösungen</summary>

  ```bash
mkdir myfirst-repo-student111 && cd $_
(echo -n "which git -> ";which  git)  > ls01-git-basics-installation.txt
(echo -n "rpm -qf /us/bin/git -> ";rpm -qf /usr/bin/git) >> ls01-git-basics-installation.txt
(echo "dnf info git ->";dnf info git) >> ls01-git-basics-installation.txt
```

</details>

