# age-decrypt-action

Decrypt a file using age (https://github.com/FiloSottile/age).

## Inputs

#### secret-key
* description: The age secret key to decrypt with
* required: true

#### input-file
* description: The file to decrypt
* required: true

#### output-file
* description: Where to place the decrypted file
* required: true

#### setup
* description: Setup age and age-keygen
* required: false
* default: "true"

#### version
* description: The `age` version to use
* required: false
* default: "1.0.0"
