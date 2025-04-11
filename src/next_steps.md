# Next steps

In the second and final month of this grant project, we'll be working on several tasks, following the [initial proposal](https://github.com/orgs/noir-lang/discussions/7523). 

A major focus is to improve the verifier contract. We plan to do some refactoring to lower the gas usage and the deployment cost. We will also replace the delegatecall for security. The current version of the contract was generated for `bb 0.72` and this will be upgraded to `0.82.2`. Finally, the contracts will be deployed to Sepolia for testing. 

With regard to the Noir circuit, we hope to uncover further optimization opportunities after the Noir team already shaved off a good amount of gates from the initial implementation. We also plan to expand benchmarking to include timings on proof generation and verification directly with `bb` instead of on the SDK. This will provide the Noir team a better foundation to assist us in analyzing and sharing suggestions for optimizing these numbers. 

Of course, we hope developers will be eager to integrate Semaphore-Noir into their projects. To support this, we'll create a simple write-up to guide them throughout the process. For this, we plan to publish all necessary packages for easy usage. 

Finally, we'll ensure that all code is reviewed and fixed, and we will deliver the final benchmarks and final report. 