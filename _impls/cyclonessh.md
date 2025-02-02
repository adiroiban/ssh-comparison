---
title: CycloneSSH
homepage: https://www.oryx-embedded.com/products/CycloneSSH
source-repository: https://www.oryx-embedded.com/download
license: "Dual license: [GPLv2](http://www.gnu.org/licenses/old-licenses/gpl-2.0) or [commercial](https://www.oryx-embedded.com/licensing/CycloneSSH)"
first-release:
    date: 2019-07-19
latest-release:
    version: 2.1.6
    date: 2022-05-31
changelog: https://www.oryx-embedded.com/download.html#changelog
client: yes
server: yes
library: both
protocols:
    cipher:
        - chacha20-poly1305@openssh.com
        - aes128-gcm@openssh.com
        - aes256-gcm@openssh.com
        - AEAD_AES_128_GCM
        - AEAD_AES_256_GCM
        - AEAD_CAMELLIA_128_GCM
        - AEAD_CAMELLIA_256_GCM
        - aes128-ctr
        - aes192-ctr
        - aes256-ctr
        - camellia128-ctr
        - camellia192-ctr
        - camellia256-ctr
        - aes128-cbc
        - aes192-cbc
        - aes256-cbc
        - camellia128-cbc
        - camellia192-cbc
        - camellia256-cbc
        - seed-ctr@ssh.com
        - seed-cbc@ssh.com
        - 3des-ctr
        - 3des-cbc
        - blowfish-ctr
        - blowfish-cbc
        - idea-ctr
        - idea-cbc
        - arcfour256
        - arcfour128
    compression:
        - none
    hostkey:
        - ssh-ed25519-cert-v01@openssh.com
        - ssh-ed25519
        - ssh-ed448
        - ecdsa-sha2-nistp256-cert-v01@openssh.com
        - ecdsa-sha2-nistp256
        - ecdsa-sha2-nistp384-cert-v01@openssh.com
        - ecdsa-sha2-nistp384
        - ecdsa-sha2-nistp521-cert-v01@openssh.com
        - ecdsa-sha2-nistp521
        - rsa-sha2-256-cert-v01@openssh.com
        - rsa-sha2-256
        - rsa-sha2-512-cert-v01@openssh.com
        - rsa-sha2-512
        - ssh-rsa-cert-v01@openssh.com
        - ssh-rsa
        - ssh-dss-cert-v01@openssh.com
        - ssh-dss
    kex:
        - curve25519-sha256
        - curve25519-sha256@libssh.org
        - curve448-sha512
        - ecdh-sha2-nistp256
        - ecdh-sha2-nistp384
        - ecdh-sha2-nistp521
        - diffie-hellman-group16-sha512
        - diffie-hellman-group15-sha512
        - diffie-hellman-group14-sha256
        - diffie-hellman-group14-sha1
        - diffie-hellman-group1-sha1
        - ext-info-c
        - ext-info-s
    mac:
        - hmac-sha2-256
        - hmac-sha2-256-etm@openssh.com
        - hmac-sha2-512
        - hmac-sha2-512-etm@openssh.com
        - hmac-sha1
        - hmac-sha1-etm@openssh.com
        - hmac-sha1-96
        - hmac-sha1-96-etm@openssh.com
        - hmac-ripemd160@openssh.com
        - hmac-ripemd160-etm@openssh.com
        - hmac-md5
        - hmac-md5-etm@openssh.com
        - hmac-md5-96
        - hmac-md5-96-etm@openssh.com
        - AEAD_AES_128_GCM
        - AEAD_AES_256_GCM
        - AEAD_CAMELLIA_128_GCM
        - AEAD_CAMELLIA_256_GCM
    userauth:
        - publickey
        - password
    extension:
        - server-sig-algs
        - global-requests-ok

first_kex_packet_follows: 0
---
* SSHv2 library dedicated to microcontrollers
* SCP client and server implementations
* SFTP client and server implementations
* C programming language
