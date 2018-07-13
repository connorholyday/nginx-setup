# NGINX Setup

Here's a rough guide on how to setup your local machine to serve local websites with nginx, based on an article by [Jonas Friedmann](https://blog.frd.mn/install-nginx-php-fpm-mysql-and-phpmyadmin-on-os-x-mavericks-using-homebrew/)

## Aliases
Copy the aliases to your home directory or append the contents to your existing alias setup.
```
$ cp bash_aliases ~/.bash_aliases
```

Source them from your shell config

**bash**
```
# ~/.bash_profile
export source ~/.bash_aliases >> ~/.bash_profile
```

**zsh**
```
# ~/.zshrc
export source ~/.bash_aliases >> ~/.zshrc
```
