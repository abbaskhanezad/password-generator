# password-generator
## generete safe and custom password

## How To Install

```sh
pip install git+https://github.com/abbaskhanezad/password-generator

```
## Examples

```sh
from PasswordGenerator import generate_password

password = generate_password()  # tEr#IJ}U7n

password = generate_password(length=20)   #AYD<Z2bse33/'RCB}6jj
 
password = generate_password(length=10, use_lower=False)  #"K+UH4:OV}

password = generate_password(use_lower=False, use_punctuation=False)  #xhulpubsxp

password = generate_password(use_number=False)   #bcM,yLX[i}

password = generate_password(use_punctuation=False, use_lower=False, use_upper=False)  #3663572030
```
