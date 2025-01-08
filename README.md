# Generate-random-strings

### Here are a few examples of using python to generate random strings

import random \
alphabet = 'abcdefghijklmnopqrstuvwxyz!@#$%^&*()+=' \
char = random.choice(alphabet) \
print(char) 


import random \
import string \
value = ''.join(random.sample(string.ascii_letters + string.digits, 8)) \
print(value) 


import secrets  \
import string 

def generate_secure_random_string(length): \
letters = string.ascii_letters + string.digits \
secure_str = ''.join(secrets.choice(letters) for _ in range(length)) \
return secure_str 

secure_random_string = generate_secure_random_string(16) \
print(secure_random_string) 


here are some examples: \
~2AfVLJmCGyvzuMRdxS`3+Ygvde1de*aO<HR \
WvLsm5]&.S05]5^auaM^UkZlfYjR9W0oZ[>f \
52 qCob*<UEFCtfr>b #Or=bu+-mn=!ur7|q \
<M4=#nzWt+W#P h5E=0-oF1^_/TM yTF-[53 \
rn2DTfYFbly9BIbwAvYmdDP36REuJIBfnYA=
