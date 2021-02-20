# adminer-nord

A theme inspired by [pepa-linha-dark](https://github.com/pepa-linha/Adminer-Design-Dark) but with nord defaults.

# Disclaimer

The theme files are still being changed as not everything from pepa-linha-dark has been changed and a lot of styles still inherit colors from the original theme.

Please report issues for things or places that I might have missed

# Screenshots
**Dark**

<img height="500" src="/screenshots/dark.png"/>

**Light**

<img height="500" src="/screenshots/light.png"/>


# Usage

- Rename the file to `adminer.css` and place it beside the `adminer.php` file.

**Docker**
These instructions have been tested with this particular docker image[docker-adminer](https://hub.docker.com/_/adminer/)

- copy the a themed css and rename it to `adminer.css` and place it in you directory
- in your dockerfile, add the following line
```dockerfile
    ADD ./adminer.css /var/www/html/adminer.css
```

# Credits 
[pepa-linha](https://github.com/pepa-linha) - for the original theme
