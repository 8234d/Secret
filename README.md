<h1 align="center">
  <br>
  <a href="https://github.com/8234d/Secret"><img src="https://github.com/8234d/Secret/blob/main/secret_htb.png" alt="Secret" width="200"></a>
  <br>
  Secret
  <br>
</h1>

<h4 align="center">HackTheBox - <a href="https://app.hackthebox.com/machines/Secret" target="_blank">Secret</a></h4>

![Secret_img](https://github.com/8234d/Secret/blob/main/secret.png)

## How To Use

To clone and run this application from your command line:

```bash
# Clone this repository
$ git clone https://github.com/8234d/Secret/

# Go into the repository
$ cd Secret

# Install dependencies
$ pip3 install -r requirements.txt

# Run the app
$ ./secret_user.py
$ ./secret_root.py
```

Please think that this is done to share techniques not for spoilers, the authors of these exploits are not responsible for the misuse that can be given to the corresponding programs.

As this is an active machine, you have to decrypt the files before you can use the exploits.

```bash
## To access all repository content
$ gpg-zip -d content.gpg
# the password is the hash inside root.txt

## To access each user's exploit individually
$ gpg secret_root.gpg
# the password is the hash inside root.txt
$ gpg secret_user.gpg
# the password is the hash inside user.txt

# Run the app
$ ./secret_user.py
$ ./secret_root.py
```

## License

> [GPL v3.0](https://github.com/8234d/Secret/blob/main/LICENSE) &nbsp;&middot;&nbsp;
> [@8234d](https://github.com/8234d)
