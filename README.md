# Hyperledger-Fabric-Based-Post-Quantum-Cryptography-HFPQC-
/fabric-pqc-healthcare-sim/
│
├── chaincode/                   # Smart contracts for healthcare use case
│   ├── ehr/
│   │   ├── ehr.go               # Example: Electronic Health Record chaincode
│   │   └── go.mod
│   └── README.md
│
├── network/                     # Network, deployment, and configuration files
│   ├── docker-compose.yaml
│   ├── configtx.yaml            # Fabric network config
│   ├── crypto-config.yaml
│   ├── scripts/
│   │   └── network.sh           # Bring up/down network, create channels, etc
│   ├── artifacts/
│   │   └── genesis.block
│   └── README.md
│
├── pqc-integration/             # Post-quantum cryptography (PQC) code/libraries
│   ├── liboqs/                  # Integration or submodule of liboqs or similar
│   ├── fabric-bccsp-pqc/        # Patch or extension of Fabric's CSP to PQC
│   ├── test/
│   │   └── pqc_demo.go
│   └── README.md
│
├── simulation/                  # Discrete event simulation code & scenarios
│   ├── simulator.py             # Python DES script (e.g., using SimPy/blocksims)
│   ├── scenarios/
│   │   └── basic_healthcare.yml
│   ├── results/
│   │   └── run1.csv
│   └── README.md
│
├── app/                         # Application/client code for demo/UI/testing
│   ├── server/
│   │   └── app.js               # API server for interacting with Fabric
│   ├── client/
│   │   └── ui.html              # (Optional) Web or CLI frontend
│   └── README.md
│
├── docs/                        # Project documentation
│   ├── overview.md
│   ├── pqc-integration.md
│   ├── simulation-methodology.md
│   ├── results.md
│   └── references.md
│
├── scripts/                     # Utility scripts (setup, tests, monitoring)
│   └── test.sh
│
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt             # For Python dependencies (simulation etc.)
