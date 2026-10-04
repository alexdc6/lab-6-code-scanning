# Answers to Part 3

Add your answers to the questions in Part 3, Step 2 below. 

## Vulernability Remediation:
### Vulnerability 1: 
1. Which package or library are you addressing?
The package I am addressing is the Pillow package.
2. Which CVE is linked to this vulnerability?
The CVE linked to this vulnerability is: CVE-2023-50447. This vulnerability suggests that the following code has external code that is not part of the original code that is not restrictive of any input.
3. What remediation steps do you suggest?
A remediation for this vulnerability would involve restricting what is possible to input by only accepting a list of posssible inputs. This stops from code injecting that could change how the original code functions.
### Vulnerability 2:
1. Which vulnerability are you addressing?
The package I am addressing is the pkg:pypi/pyjwt@2.4.0 or PyJWT package.
2. Which CVE is linked to this vulnerability?
The CVE that is linked to this vulnerability is: CVE-2026-102268. This vulnerability relates to PyJWT that is used for JSON Web Tokens via Python. Before the verison 2.14.0, PyJWT would not verify, or incorrectly verify, specific public keys as HMAC secrets when an application would support both HMAC and assymetric JWT algorithms. Due to this issue, attackers that knew the public key could forge authentication HMAC tokens and use it to have the application think it is legimiate.
3. What remediation steps do you suggest? 
The best remediation steps for this vulnerability would be to update PyJWT to 2.14.0 where this issue was patched.