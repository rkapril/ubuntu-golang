### Install golang in Ubuntu

**Remove any existing Go installation**

```
sudo apt purge golang*
```

```
sudo add-apt-repository ppa:longsleep/golang-backports
```

```
sudo apt update
```

**Install the latest Go version**
```
sudo apt install golang-go
```

**Verify the installation and version number**
```
go version
```