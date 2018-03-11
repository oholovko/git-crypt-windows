### A short list of commands

**Decrypt the repository**

*Linux*

```sh
git-crypt unlock /path/to/the/key/keyname
```

*Windows*
```cmd
git-crypt unlock "/disk/path/to/the/key/keyname"
```

**Encrypt the repository**
```sh
git-crypt lock
```

**Check the list of encrypted files**
```sh
git-crypt status -e
```

Note:
> If you are making commits in the IDE, you need to execute all commands in the IDE console.

For more information go to [AGWA/git-crypt](https://github.com/AGWA/git-crypt) and use:
```sh
git-crypt help
```

**Thats all.**
