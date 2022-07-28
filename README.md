
# ShodanIsh
Shodan Favicon Murmur Hash Converter By Aziz Hakim @eternyle

This script retrieves the decimal hash that corresponds to an image,
the hash can be used on [shodan.io](https://shodan.io).

# Requirements:

- mmh3 Installation
```bash
python get-pip.py install mmh3
get-pip.py ( https://bootstrap.pypa.io/get-pip.py )
```
- Download the script
```bash
git clone https://github.com/malwarejuice/ShodanIsh
```

# USAGE
- Interactive
```bash
$ python shodanish.py
```
Enter Domain/URL : azizhakim.com

- Non-Interactive
```bash
$ python shodanish.py --url azizhakim.com
$ python shodanish.py --url https://azizhakim.com
$ python shodanish.py --url https://azizhakim.com
$ python shodanish.py --url https://azizhakim.com/favicon.ico
```

The input can be given in one of the following formats:
- hostname, http is used: `azizhakim.com` 
- base url: `https://azizhakim.com` or `https://azizhakim.com/`
- full url: `https://azizhakim.com/favicon.ico`
