# SSH cheat sheet

#### Generate new key pair
``ssh-keygen``

#### Convert public key form ssh-rsa into encoded public key

Generated format:
> ssh-rsa AAAA... melanie@melanie-ThinkPad-P50

encoded format:
> -----BEGIN RSA PUBLIC KEY-----
MIIBCgKCAQE
-----END RSA PUBLIC KEY-----



``ssh-keygen -f key.pub -e -m pem``

[link to blog post](https://blog.oddbit.com/post/2011-05-08-converting-openssh-public-keys/)
