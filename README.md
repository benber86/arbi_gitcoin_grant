# Arbitrum/GC21 Grant

## Network

Arbitrum One

## Project Name

Vyper

## Project Website

https://www.vyperlang.org

## Project Logo

![2024-06-11_23-25](https://github.com/user-attachments/assets/70a918fb-7153-4ffc-acbc-f6255f46d0eb)


## Project Banner

![snek-developer](https://github.com/user-attachments/assets/7b6c064c-5e9c-440e-b602-b89d3d83e1ce)

## Project Description

Vyper is a pythonic smart contract programming language forthe Ethereum Virtual Machine (EVM). Vyper contracts account for over $100m of TVL on Arbitrum and secure more than $2 billion across multiple chains for major protocols such as Curve, Lido and Yearn (https://defillama.com/languages).

It is currently the second most popular EVM programming language with over 30,000 contracts deployed across a dozen chains. Vyper is fully free and open source, released under a permissive Apache license.

## Describe your previous work or plans related to the Arbitrum ecosystem. How does your project strengthen Arbitrum's foundational infrastructure, improve developer efficiency, or accelerate the adoption of novel applications?


As one of the main smart contract programming languages Vyper strengthens Arbitrum's foundational infrastructure, accelerate the adoption of novel applications and improves developer efficiency in several ways:

- Increased Security: Since 2023, Vyper has worked with 3 major auditing companies (ChainSecurity, Statemind, Ottersec) for regular reviews of the codebase and full audits of every new release. The compiler was subject to a security contest and the team is currently working on implementing state of the art compiler verification methods. Vyper's readability, simple syntax and disabling of security pitfalls (inline assembly, class inheritance or operator and function overloading) also help to prevent common security vulnerabilities. 
- Cheaper Audit Costs: Vyper's focus on readability and simplicty make contracts easier and cheaper to audit, roughly 20% less than an equivalent Solidity contract, based on auditors' feedback.
- Gas and Bytecode Size Optimization: Vyper's compiler offers exceptional performance, producing binaries that are consistently 50% smaller than Solidity and much less gas intensive (https://blog.chain.link/solidity-vs-vyper/, https://github.com/z80dev/gascomps, https://github.com/benber86/vyper_bytecode). This lets developers write longer, more complex contracts than they could in other languages such as Solidity. 
- Easy Onboarding of New Developers: Vyper's pythonic syntax makes it easy to onboard new developers to web3, as Python is now the most popular programming language (Stack Overflow survey 2024, https://survey.stackoverflow.co/2024/). A recent Twitter poll with 164 participants showed that a majority of developers would pick Vyper and Ape over Solidity and Foundry to start a new project (https://x.com/0xKoga/status/1805524364948893756).
- Faster, Better Testing Capabilities: Vyper frameworks like Titanoboa and Gaboon use an interpreter to offer considerable speed ups when testing smart contracts, up to 10 times faster than other frameworks (https://github.com/vyperlang/gaboon/tree/refactor). These tools also include features such as automated fuzzing and integration with other testing tools to make testing much more efficient for developers.
- Superior Developer Experience: Vyper comes with composable modules and an extensive set of libraries (https://github.com/pcaversaccio/snekmate) with secure implementations of common smart contract functionalities. Support for Vyper contracts in Jupyter and Collab notebooks through Titanoboa makes it easy to document, collaborate and iterate on smart contracts. Vyper is also now well supported by popular web3 development tools such as Tenderly or Foundry and major IDEs such as VSCode and IntelliJ.
- Blue Chip Projects: Vyper brings innovative and prominent DeFi projects like Curve and Yearn to Arbitrum. Arbitrum is also the only L2 on which Curve's new LlammaLend product, entirely written in Vyper, was deployed.

## If applicable, describe how your project leverages Stylus or Arbitrum Orbit Chains. What unique capabilities or use cases does this enable?

While Vyper does not currently leverage Stylus, adding support for it to compile Vyper to WASM would result in more efficient bytecode.

## Describe your team's expertise in your chosen focus area within the Arbitrum ecosystem. Include relevant experience, publications, or past projects

The Vyper team is composed of highly experienced web3 engineers with expertise in compilers and security, with an extensive understanding of the EVM, smart contract development, and the associated security considerations. They have collaborated extensively with auditors and security researchers, contributed to the growth of the Ethereum ecosystems via EIPs and their expertise is widely recognized within the EVM developers and security communities. The project also has over 20 regular contributors. The team currently consists of:

- Charles (https://github.com/charles-cooper, https://x.com/big_tech_sux). Charles is the lead developer of Vyper and Titanoboa (https://github.com/vyperlang/titanoboa). Charles also contributes to multiple Ethereum tooling projects (py-evm, pyrevm, eth-abi) and is the author of several EIPs.
- Harry (https://github.com/harkal, https://x.com/harkal). Harry has been working on Vyper's intermediate representation (Venom) since 2023. Harry has over 10 years of experience in embedded programming and computer graphics.
- cyberthirst (https://github.com/cyberthirst). Cyberthirst is a Vyper contributor who has worked on compiler security since 2023 and has an academic background in compiler verification research. 
- Adam (https://github.com/hodanplodky). Adam is a web3 engineer working on Vyper's intermediate representation.

## Please provide a link to Karma GAP, where you are tracking and reporting on milestones.

https://gap.karmahq.xyz/project/vyper/grants?tab=milestones-and-updates


