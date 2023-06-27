# Resources on confidential computing


## Intel SGX | TDX

### Official resources

* TDX [https://www.intel.com/content/www/us/en/developer/articles/technical/intel-trust-domain-extensions.html](https://www.intel.com/content/www/us/en/developer/articles/technical/intel-trust-domain-extensions.html)
* SGX [https://www.intel.com/content/www/us/en/developer/tools/software-guard-extensions/overview.html](https://www.intel.com/content/www/us/en/developer/tools/software-guard-extensions/overview.html)

### Tools (SGX)

* Official
  - https://01.org/intel-softwareguard-extensions
  - https://github.com/intel/linux-sgx
  - https://github.com/intel/linux-sgx-driver

### Research Papers

#### Design
* [Intel SGX Explained](https://eprint.iacr.org/2016/086.pdf)

#### Attacks

* [A Survey of Published Attacks on Intel SGX](https://arxiv.org/pdf/2006.13598.pdf)
* [Security Vulnerabilities of SGX and Countermeasures: A Survey](https://dl.acm.org/doi/10.1145/3456631)
* [SmashEx: Smashing SGX Enclaves Using Exceptions](https://n.ethz.ch/~sshivaji/publications/smashex_ccs21.pdf)
* [SGX-Step: A Practical Attack Framework for Precise Enclave Execution Control](https://core.ac.uk/download/pdf/129863707.pdf)
* [Faulty Point Unit: ABI Poisoning Attacks on Intel SGX](https://jovanbulck.github.io/files/acsac20-fpu.pdf)
* [The Guard's Dilemma: Efficient Code-Reuse Attacks Against Intel SGX](https://www.usenix.org/conference/usenixsecurity18/presentation/biondo)
* [AsyncShock: Exploiting Synchronisation Bugs in Intel SGX Enclaves](https://link.springer.com/content/pdf/10.1007%2F978-3-319-45744-4_22.pdf)
* Foreshadow
  - [FORESHADOW: Extracting the Keys to the Intel SGX Kingdom with Transient Out-of-Order Execution](https://foreshadowattack.eu/foreshadow.pdf)
  - [Foreshadow-NG: Breaking the Virtual Memory Abstraction with Transient Out-of-Order Execution](https://foreshadowattack.eu/foreshadow-NG.pdf)
  - [Breaking Virtual Memory Protection and the SGX Ecosystem with Foreshadow](https://ieeexplore.ieee.org/abstract/document/8691527)
* [Software Grand Exposure: SGX Cache Attacks Are Practical](https://www.usenix.org/conference/woot17/workshop-program/presentation/brasser)
* [ÆPIC Leak: Architecturally Leaking Uninitialized Data from the Microarchitecture](https://www.usenix.org/system/files/sec22-borrello.pdf)

## AMD SEV, SEV-ES, SEV-SNP

### Official resources

* [https://developer.amd.com/sev/](https://developer.amd.com/sev/)
* Linux kernel doc [https://www.kernel.org/doc/html/latest/virt/kvm/amd-memory-encryption.html](https://www.kernel.org/doc/html/latest/virt/kvm/amd-memory-encryption.html)
* SEV API doc [https://www.amd.com/system/files/TechDocs/55766_SEV-KM_API_Specification.pdf](https://www.amd.com/system/files/TechDocs/55766_SEV-KM_API_Specification.pdf)

### Tools

* https://github.com/AMDESE/AMDSEV
* Secure VM Service Module (SVSM)
  - https://github.com/AMDESE/linux-svsm
  - https://github.com/coconut-svsm/svsm

### Research Papers

#### Design

* [SEV-SNP White paper](https://www.amd.com/system/files/TechDocs/SEV-SNP-strengthening-vm-isolation-with-integrity-protection-and-more.pdf)

**2023**

* Usenix ATC'23 [Bifrost: Analysis and Optimization of Network I/O Tax in Confidential Virtual Machines](https://ipads.se.sjtu.edu.cn/_media/publications/liatc23.pdf)
**2022**

* ACSAC'22 [CoCoTPM: Trusted Platform Modules for Virtual Machines in Confidential Computing Environments](https://dl.acm.org/doi/abs/10.1145/3564625.3564648)


#### Attacks/Mitigations

**2023**

* DIMVA'23 [PwrLeak: Exploiting Power Reporting Interface for Side-Channel Attacks on AMD SEV](https://link.springer.com/chapter/10.1007/978-3-031-35504-2_3)
* CODASPY'23 [Protecting Encrypted Virtual Machines from Nested Page Fault Controlled Channel](https://dl.acm.org/doi/pdf/10.1145/3577923.3583659)
* Usenix Sec'23 [CipherH: Automated Detection of Ciphertext Side-channel Vulnerabilities in Cryptographic Implementations](https://www.usenix.org/system/files/sec23summer_289-deng-prepub.pdf)

**2022**
* IEEE S&P'22 [A Systematic Look at Ciphertext Side Channels on AMD SEV-SNP](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9833768)
* Arxiv [Cipherfix: Mitigating Ciphertext Side-Channel Attacks in Software](https://arxiv.org/pdf/2210.13124.pdf)

**2021**
* ACSAC'21 [TLB Poisoning Attacks on AMD Secure Encrypted Virtualization](https://dl.acm.org/doi/10.1145/3485832.3485876)
* CCS'21
  - [CrossLine: Breaking “Security-by-Crash” based Memory Isolation in AMD SEV](https://dl.acm.org/doi/pdf/10.1145/3460120.3485253)
  - [One Glitch to Rule Them All: Fault Injection Attacks Against AMD's Secure Encrypted Virtualization](https://dl.acm.org/doi/10.1145/3460120.3484779)
* IEEE S&P'21 [undeSErVed trust: Exploiting Permutation-Agnostic Remote Attestation](https://ieeexplore.ieee.org/abstract/document/9474294)
* Usenix Sec'21 [CipherLeaks: Breaking Constant-time Cryptography on AMD SEV via the Ciphertext Side Channel](https://www.usenix.org/system/files/sec21-li-mengyuan.pdf)

**2020**
* IEEE S&P'20 [SEVurity: No Security Without Integrity : Breaking Integrity-Free Memory Encryption with Minimal Assumptions](https://www.computer.org/csdl/proceedings-article/sp/2020/349700b746/1j2LgvKzg1q)
* ROOTS'20 [Exploiting Interfaces of Secure Encrypted Virtual Machines](https://dl.acm.org/doi/abs/10.1145/3433667.3433668)

**2019**
* AsiaCCS'19 [The SEVerESt Of Them All: Inference Attacks Against Secure Virtual Enclaves](https://dl.acm.org/doi/pdf/10.1145/3321705.3329820)
* CODASPY'19 [Extracting Secrets from Encrypted Virtual Machines](https://dl.acm.org/doi/10.1145/3292006.3300022)
* Usenix Sec'19 [Exploiting Unprotected I/O Operations in AMD’s Secure Encrypted Virtualization](https://www.usenix.org/system/files/sec19-li-mengyuan_0.pdf)

**2018**
* EuroSec'18 [SEVered: Subverting AMD's Virtual Machine Encryption](https://dl.acm.org/doi/10.1145/3193111.3193112)

**2017**
* VEE'17 [Security Analysis of Encrypted Virtual Machines](https://dl.acm.org/doi/10.1145/3050748.3050763)

## IBM Power Protected Execution Facility (PEF)

### Official resources
* PEF [https://developer.ibm.com/articles/l-support-protected-computing/](https://developer.ibm.com/articles/l-support-protected-computing)
* Linux kernel documentation [https://www.kernel.org/doc/html/latest/powerpc/ultravisor.html](https://www.kernel.org/doc/html/latest/powerpc/ultravisor.html)

### Research Papers
#### Design

* [Confidential computing for OpenPOWER](https://dl.acm.org/doi/10.1145/3447786.3456243)

#### Attacks

## Keystone (RISC-V)

### Official resources

* https://keystone-enclave.org/

### Tools

* Official
  - https://github.com/keystone-enclave

### Research Papers

#### Design

* [Keystone: an open framework for architecting trusted execution environments](https://dl.acm.org/doi/abs/10.1145/3342195.3387532)

#### Attack
