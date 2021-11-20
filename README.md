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

the password is in the root hash from /etc/shadow

`root:$6$/0f5J.S8.u.dA78h$*********************/uD8T5FcY[...].:18873:0:99999:7:::`

```bash
## To access all repository content
$ gpg-zip -d content.gpg

## To access each user's exploit individually
$ gpg secret_root.gpg
$ gpg secret_user.gpg

# Run the app
$ ./secret_user.py
$ ./secret_root.py
```

## License

> [GPL v3.0](https://github.com/8234d/Secret/blob/main/LICENSE) &nbsp;&middot;&nbsp;
> [@8234d](https://github.com/8234d)
