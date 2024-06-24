# Syndioctl Installer

## Using the Installer

Syndioctl installer can be run via the following script:

```shell
curl -L https://github.com/syndio/syndioctl-installer/raw/main/syndioctl-installer -o installer && chmod +x installer && ./installer && rm installer
```

The installer will automatically pull the latest binary release of Syndioctl down and place it at `~/.syndio/syndioctl/bin/`, after which you'll then need to update your shell configuration to add the following:

 ```sh
 export PATH="${HOME}/.syndio/syndioctl/bin:$PATH"