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
* 
#### Attack

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
* 

## AMD SEV, SEV-ES, SEV-SNP

### Official resources

* [https://developer.amd.com/sev/](https://developer.amd.com/sev/)
* Linux kernel doc [https://www.kernel.org/doc/html/latest/virt/kvm/amd-memory-encryption.html](https://www.kernel.org/doc/html/latest/virt/kvm/amd-memory-encryption.html)

### Tools

* https://github.com/AMDESE/AMDSEV
 

### Research Papers

#### Design

* [SEV-SNP White paper](https://www.amd.com/system/files/TechDocs/SEV-SNP-strengthening-vm-isolation-with-integrity-protection-and-more.pdf)
 
#### Attack

* [CipherLeaks: Breaking Constant-time Cryptography on AMD SEV via the Ciphertext Side Channel](https://www.usenix.org/system/files/sec21-li-mengyuan.pdf)
* [SEVurity: No Security Without Integrity : Breaking Integrity-Free Memory Encryption with Minimal Assumptions](https://www.computer.org/csdl/proceedings-article/sp/2020/349700b746/1j2LgvKzg1q)
* [Exploiting Unprotected I/O Operations in AMD’s Secure Encrypted Virtualization](https://www.usenix.org/system/files/sec19-li-mengyuan_0.pdf)
* [SEVered: Subverting AMD's Virtual Machine Encryption](https://dl.acm.org/doi/10.1145/3193111.3193112)

## IBM Power Protected Execution Facility (PEF)

### Official resources
* PEF [https://developer.ibm.com/articles/l-support-protected-computing/](https://developer.ibm.com/articles/l-support-protected-computing)
* Linux kernel documentation [https://www.kernel.org/doc/html/latest/powerpc/ultravisor.html](https://www.kernel.org/doc/html/latest/powerpc/ultravisor.html)

### Research Papers
#### Design

* [Confidential computing for OpenPOWER](https://dl.acm.org/doi/10.1145/3447786.3456243)

#### Attack


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
