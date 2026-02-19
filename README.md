# microservices-contract-testing-pact
**Structure:**
```
microservices-contract-testing-pact/
├── consumer-tests/          # Tests from consumer microservice perspective
│   └── PatientConsumerPactTest.java
├── provider-verification/   # Provider side verification
│   └── FHIRProviderPactTest.java
├── pacts/                   # Generated contract JSON files (commit these!)
│   └── PatientMicroservice-HealthlakeFHIRProvider.json
├── docs/
│   └── contract-testing-explained.md
└── README.md

The pacts/ folder is important — commit the generated JSON files. When an interviewer opens the repo and sees actual contract JSON, they know you've actually run this, not just read about it.
Write a docs/contract-testing-explained.md that explains in your own words:

What problem contract testing solves in your pipeline
How you'd apply it to EHR → Microservices communication
What happens when a contract breaks

