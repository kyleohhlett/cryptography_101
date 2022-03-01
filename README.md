> ⚠ This is a Work In Progress ⚠

# Cryptography 101

## The Thing About Apps
Private messaging applications, especially those on Android and iOS devices, are certainly a cut above using regular SMS messaging when it comes to privacy.

However, it should be taken into consideration that some of these apps are not open-source. And some of them are, but are compiled in advance for you. As a result, you don't get to see, for sure, the actual code that the build of the application you're using was built from. This leaves the user having to just "trust" that the application really does what it says it does (and nothing else) in regard to privacy.

> Signal and a couple others do get somewhat of a pass here. For example, if you've rooted your Android device, you can compile and install Signal from source here: https://github.com/signalapp/Signal-Android  
>  
> How many Signal users have gone to that length though?

## Encryption Fundmentals

### Symmetric Encryption

### Asymmetric Encryption

## Installing gpg

### Building gpg From Source
As gpg is an open-source utlitiy, you can look through its code for yourself. You can also compile/build it from its code. The Gnupg project, AKA gpg, is hosted here: https://github.com/gpg/gnupg

## Generating a Keypair

## Exchanging Keypairs

## How to Encrypt Messages

[//]: <> (# include CLI usage for how to use gpg or something)
1.
2.
3.

## How to Decrypt Messages
[//]: <> (# include CLI usage for how to use gpg or something)
1. `code`  
2.  
3.  

## Encrypting or Decrypting Other File Formats
Great news: you can encrypt or decrypt anything the same way, regardless of its file format. Keep in mind though that if you don't name the file in a way that allows the recipient to know what format the file is in, they will be able to decrypt the file, but may not know what application to open it with.  

It's generally good practice to leave the file's original extension as part of the encrypted file name. The final `.gpg` extension denotes that the file has been encrypted with the `gpg` command line utlity.

> Examples:  
>- `tax_return.docx.gpg`  
>- `monthly_payments.txt.gpg`
>- `accounting.xlsx.gpg`

However, adding these file extensions is just a common convention rather than a required rule.
