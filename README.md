# Securing your application software supply-chain - WeAreDevelopers World Congress 2022

## Abstract

With our complete software development process becoming more complex we also got a lot more security problems to deal with. What starts with code and ends with releasing/deploying software is also being referred at as the software-supply chain. The software supply-chain consists of a lot of moving parts. Each of them facing their own security risks starting from access to source code, compromised third-party libraries and tools, or even hacked build servers. For example with SolarWinds the compromised build server added malicious functionality to the end product used by their customers. And a tool called CodeCov had their upload script compromised which resulted in it stealing used access-keys.
In this session we'll get hands-on with securing an application it's supply chain and look how we can limit the security risks in all the different area's. We're going to look into he concept of Software-Bill-Of-Materials (SBOM), Google's SLSA and tools like in-toto, cyclonedx and sigstore.

## Demo

- MyAwesome-WebApp: https://github.com/nielstanis/myawesome-webapp
  - CI: https://github.com/nielstanis/myawesome-webapp/blob/main/.github/workflows/ci.yml
  - Release: https://github.com/nielstanis/myawesome-webapp/blob/main/.github/workflows/release.yml
