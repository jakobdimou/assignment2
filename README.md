# Assignment 2 
## ACIT 2420 Jakob Dimou A01398523

This project contains several scripts to manage user creation, package installation, and symbolic link creation. Below is a brief description and example on how to use each script:


## `newuser`
Creates a new user with specified options.

### Example usage:
```
sudo newuser -a <groupname> -u <username> -s <shell>
sudo newuser -a blue-lock -u itoshi-rin -s /bin/bash
```

## `installpackages`
Installs a predefined list of packages.

### Example usage:
```
sudo installpackages
```

## `symboliclink`
Creates symbolic links for `bin`, `config`, and `bashrc`.

### Example usage:
```
sudo symboliclink
```

## `scriptrunner`
Runs either the package installation or symbolic link creation script.

### Example usage:
```
sudo scriptrunner -4
```

### Options
- `-4`: Run the package installation script.
- `-9`: Run the symbolic link creation script.

