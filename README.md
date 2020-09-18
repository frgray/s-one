# Signature Checker
Computes the percentage of virus engines that detected requested signature as malicious and prints the result

## Common Usage
```bash
[user@host:~/] pip3 install -r ./requirements.txt
[user@host:~/] sha1_checker 4af001b3c3816b860660cf2de2c0fd3c1dfb4878 --key <api_key>
not malicious
```

## Malicious File
```bash
[user@host:~/] sha1_checker 7b4fe9c5d40f0a67a2544bcc92c39f673323584f7f011e0b454ea5932e48c70f --key <api_key>
malicious
```

## Suspicious File
```bash
[user@host:~/] sha1_checker 213b71a8096af1d6d179c2145d4e499a481a9de4 --key <api_key>
suspicious
```

## Unknown File
```bash
[user@host:~/] sha1_checker 4af001b3c3816b860660cf2d1dfb4878 --key  <api_key>
unknown
```

## Authors
- Francisco Gray, <frgray@gmail.com>
