crypto-config
├── ordererOrganizations
│   └── example.com
│       ├── ca
│       │   ├── 72a70b9399229bb5250c121e3b73b6b0614980830bcc79971ab91535fbb7901e_sk
│       │   └── ca.example.com-cert.pem
│       ├── msp
│       │   ├── admincerts
│       │   │   └── Admin@example.com-cert.pem
│       │   ├── cacerts
│       │   │   └── ca.example.com-cert.pem
│       │   └── tlscacerts
│       │       └── tlsca.example.com-cert.pem
│       ├── orderers
│       │   ├── orderer0.example.com
│       │   │   ├── msp
│       │   │   │   ├── admincerts
│       │   │   │   │   └── Admin@example.com-cert.pem
│       │   │   │   ├── cacerts
│       │   │   │   │   └── ca.example.com-cert.pem
│       │   │   │   ├── keystore
│       │   │   │   │   └── 09fe5ff94b7055f14db91db8edca7416980ebef8115d9ed4d740add10ad6087d_sk
│       │   │   │   ├── signcerts
│       │   │   │   │   └── orderer0.example.com-cert.pem
│       │   │   │   └── tlscacerts
│       │   │   │       └── tlsca.example.com-cert.pem
│       │   │   └── tls
│       │   │       ├── ca.crt
│       │   │       ├── server.crt
│       │   │       └── server.key
│       │   ├── orderer1.example.com
│       │   │   ├── msp
│       │   │   │   ├── admincerts
│       │   │   │   │   └── Admin@example.com-cert.pem
│       │   │   │   ├── cacerts
│       │   │   │   │   └── ca.example.com-cert.pem
│       │   │   │   ├── keystore
│       │   │   │   │   └── 16d7087b4b8722c989695de03dbaa5b5910bfadd12206ea72e108230cadbe1c3_sk
│       │   │   │   ├── signcerts
│       │   │   │   │   └── orderer1.example.com-cert.pem
│       │   │   │   └── tlscacerts
│       │   │   │       └── tlsca.example.com-cert.pem
│       │   │   └── tls
│       │   │       ├── ca.crt
│       │   │       ├── server.crt
│       │   │       └── server.key
│       │   └── orderer2.example.com
│       │       ├── msp
│       │       │   ├── admincerts
│       │       │   │   └── Admin@example.com-cert.pem
│       │       │   ├── cacerts
│       │       │   │   └── ca.example.com-cert.pem
│       │       │   ├── keystore
│       │       │   │   └── 9ee2c2fa7eca4f7d1cee455ba9a378d9a2c36b9163940b50fc011927c452ee6c_sk
│       │       │   ├── signcerts
│       │       │   │   └── orderer2.example.com-cert.pem
│       │       │   └── tlscacerts
│       │       │       └── tlsca.example.com-cert.pem
│       │       └── tls
│       │           ├── ca.crt
│       │           ├── server.crt
│       │           └── server.key
│       ├── tlsca
│       │   ├── 6f47b1c01ebe9fa844c4f0ceb9402d33c955cf4d109ee7f69af30fdc1c5a9250_sk
│       │   └── tlsca.example.com-cert.pem
│       └── users
│           └── Admin@example.com
│               ├── msp
│               │   ├── admincerts
│               │   │   └── Admin@example.com-cert.pem
│               │   ├── cacerts
│               │   │   └── ca.example.com-cert.pem
│               │   ├── keystore
│               │   │   └── e3c75ec3544425c3f1bf98c29ceee01e4ea8decb04b49528af65731b46d4a830_sk
│               │   ├── signcerts
│               │   │   └── Admin@example.com-cert.pem
│               │   └── tlscacerts
│               │       └── tlsca.example.com-cert.pem
│               └── tls
│                   ├── ca.crt
│                   ├── server.crt
│                   └── server.key
└── peerOrganizations
    ├── org1.example.com
    │   ├── ca
    │   │   ├── b20bc54a463a3e55a50b68a0f23719749722fc1e964a7b5f7529a0788c8c006f_sk
    │   │   └── ca.org1.example.com-cert.pem
    │   ├── msp
    │   │   ├── admincerts
    │   │   │   └── Admin@org1.example.com-cert.pem
    │   │   ├── cacerts
    │   │   │   └── ca.org1.example.com-cert.pem
    │   │   └── tlscacerts
    │   │       └── tlsca.org1.example.com-cert.pem
    │   ├── peers
    │   │   ├── peer0.org1.example.com
    │   │   │   ├── msp
    │   │   │   │   ├── admincerts
    │   │   │   │   │   └── Admin@org1.example.com-cert.pem
    │   │   │   │   ├── cacerts
    │   │   │   │   │   └── ca.org1.example.com-cert.pem
    │   │   │   │   ├── keystore
    │   │   │   │   │   └── d320d80699bd01741c4b2e5280f4040608c4ae0049a4a463e911b259028ed106_sk
    │   │   │   │   ├── signcerts
    │   │   │   │   │   └── peer0.org1.example.com-cert.pem
    │   │   │   │   └── tlscacerts
    │   │   │   │       └── tlsca.org1.example.com-cert.pem
    │   │   │   └── tls
    │   │   │       ├── ca.crt
    │   │   │       ├── server.crt
    │   │   │       └── server.key
    │   │   └── peer1.org1.example.com
    │   │       ├── msp
    │   │       │   ├── admincerts
    │   │       │   │   └── Admin@org1.example.com-cert.pem
    │   │       │   ├── cacerts
    │   │       │   │   └── ca.org1.example.com-cert.pem
    │   │       │   ├── keystore
    │   │       │   │   └── 6dcbdbc951e244e4232fafc69a22254879f1437e24543afe1fd760cd02f14faa_sk
    │   │       │   ├── signcerts
    │   │       │   │   └── peer1.org1.example.com-cert.pem
    │   │       │   └── tlscacerts
    │   │       │       └── tlsca.org1.example.com-cert.pem
    │   │       └── tls
    │   │           ├── ca.crt
    │   │           ├── server.crt
    │   │           └── server.key
    │   ├── tlsca
    │   │   ├── c9961fa9f2339a5847ed04069c82c596685190c2984ad2826907472d2ba25987_sk
    │   │   └── tlsca.org1.example.com-cert.pem
    │   └── users
    │       ├── Admin@org1.example.com
    │       │   ├── msp
    │       │   │   ├── admincerts
    │       │   │   │   └── Admin@org1.example.com-cert.pem
    │       │   │   ├── cacerts
    │       │   │   │   └── ca.org1.example.com-cert.pem
    │       │   │   ├── keystore
    │       │   │   │   └── 5b4ccbad7832ba73bd1e579d56f648ebddbddee98d0c492e849908dbf861fe63_sk
    │       │   │   ├── signcerts
    │       │   │   │   └── Admin@org1.example.com-cert.pem
    │       │   │   └── tlscacerts
    │       │   │       └── tlsca.org1.example.com-cert.pem
    │       │   └── tls
    │       │       ├── ca.crt
    │       │       ├── server.crt
    │       │       └── server.key
    │       └── User1@org1.example.com
    │           ├── msp
    │           │   ├── admincerts
    │           │   │   └── User1@org1.example.com-cert.pem
    │           │   ├── cacerts
    │           │   │   └── ca.org1.example.com-cert.pem
    │           │   ├── keystore
    │           │   │   └── ba5f205d0829cf08fd988d1b8cebd049745e40f12a98081f8d5a309e1e770611_sk
    │           │   ├── signcerts
    │           │   │   └── User1@org1.example.com-cert.pem
    │           │   └── tlscacerts
    │           │       └── tlsca.org1.example.com-cert.pem
    │           └── tls
    │               ├── ca.crt
    │               ├── server.crt
    │               └── server.key
    └── org2.example.com
        ├── ca
        │   ├── 382dc4e7d00e6fad0fbf4885cbdf9362718c82317cee3fb2076d7ac962e8bfe3_sk
        │   └── ca.org2.example.com-cert.pem
        ├── msp
        │   ├── admincerts
        │   │   └── Admin@org2.example.com-cert.pem
        │   ├── cacerts
        │   │   └── ca.org2.example.com-cert.pem
        │   └── tlscacerts
        │       └── tlsca.org2.example.com-cert.pem
        ├── peers
        │   ├── peer0.org2.example.com
        │   │   ├── msp
        │   │   │   ├── admincerts
        │   │   │   │   └── Admin@org2.example.com-cert.pem
        │   │   │   ├── cacerts
        │   │   │   │   └── ca.org2.example.com-cert.pem
        │   │   │   ├── keystore
        │   │   │   │   └── cbf7cbcb621ff5a06fd84ee0d7e37848b6451bba1094f2a5294e518625136e08_sk
        │   │   │   ├── signcerts
        │   │   │   │   └── peer0.org2.example.com-cert.pem
        │   │   │   └── tlscacerts
        │   │   │       └── tlsca.org2.example.com-cert.pem
        │   │   └── tls
        │   │       ├── ca.crt
        │   │       ├── server.crt
        │   │       └── server.key
        │   └── peer1.org2.example.com
        │       ├── msp
        │       │   ├── admincerts
        │       │   │   └── Admin@org2.example.com-cert.pem
        │       │   ├── cacerts
        │       │   │   └── ca.org2.example.com-cert.pem
        │       │   ├── keystore
        │       │   │   └── cc578968dc82d8cf13162875f67eaf6128f704f46612dae94b9679dcfef27115_sk
        │       │   ├── signcerts
        │       │   │   └── peer1.org2.example.com-cert.pem
        │       │   └── tlscacerts
        │       │       └── tlsca.org2.example.com-cert.pem
        │       └── tls
        │           ├── ca.crt
        │           ├── server.crt
        │           └── server.key
        ├── tlsca
        │   ├── 48334104ee783b24d1e5dc67f94efa6a633f1936e6b849aeaf2d64dd24e18a4b_sk
        │   └── tlsca.org2.example.com-cert.pem
        └── users
            ├── Admin@org2.example.com
            │   ├── msp
            │   │   ├── admincerts
            │   │   │   └── Admin@org2.example.com-cert.pem
            │   │   ├── cacerts
            │   │   │   └── ca.org2.example.com-cert.pem
            │   │   ├── keystore
            │   │   │   └── 7be6e04ba1579ba872eee94ccc1da132b0648c6a38d7a37547ef150bccb76c96_sk
            │   │   ├── signcerts
            │   │   │   └── Admin@org2.example.com-cert.pem
            │   │   └── tlscacerts
            │   │       └── tlsca.org2.example.com-cert.pem
            │   └── tls
            │       ├── ca.crt
            │       ├── server.crt
            │       └── server.key
            └── User1@org2.example.com
                ├── msp
                │   ├── admincerts
                │   │   └── User1@org2.example.com-cert.pem
                │   ├── cacerts
                │   │   └── ca.org2.example.com-cert.pem
                │   ├── keystore
                │   │   └── 90a16b982b43d68f62e0b13dc9074705be4a5a0c550f7bc3310324ae27f06f90_sk
                │   ├── signcerts
                │   │   └── User1@org2.example.com-cert.pem
                │   └── tlscacerts
                │       └── tlsca.org2.example.com-cert.pem
                └── tls
                    ├── ca.crt
                    ├── server.crt
                    └── server.key
