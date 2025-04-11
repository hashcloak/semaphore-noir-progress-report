# Project progress

In the first month of the project, we've finalized the first 2 deliverables: 
1. Semaphore circuits implementation in Noir
2. SDK functionality enhancements

Both deliverables include tests written in TypeScript, with the Noir circuit also featuring native tests. To facillitate the SDK functionality, we've forked and updated the snark-artifacts repo to add the necessary helper functionality and precompiled circuits. 

We've initiated implementation of the verifier contract and will continue refining this component over the next month, as we detail further in the subsequent sections. 

With the circuit and SDK complete, we began benchmarking to evaluate performance and identify areas for improvements. Benchmarking will remain a continuous effort throughout the next month as we assess whether we're able to make the library faster. 

Links to relevant repositories: 
- [semaphore-noir](https://github.com/hashcloak/semaphore-noir/tree/noir-support)
- [snark-artifacts](https://github.com/hashcloak/snark-artifacts/tree/semaphore-noir)
- [semaphore-noir-benchmarks](https://github.com/hashcloak/semaphore-noir-benchmarks)
