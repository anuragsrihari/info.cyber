# Fundamentals of computer security
## Identification, authentication, and authorization
| concept             | Description              | Example                             |
| ------------------- | ------------------------ | ----------------------------------- |
| **Identification**  | claiming by an identity  | typing username                     |
| **Authendication**  | proving identity         | entering password / fingureprint    |
| **Authorization**   | granting access          | Accessing certain files after login |

## Key principles:
"Authentication verifies who you are. Authorization decides what you can do."
# Authentication Methods
- knowladge-based: passwords, PINs
- possesion-based: smart cards, OTP tokens
- Interfernce-based: biometrics (fingureprint, face ID)
- Multifactor Authentication (MFA): combination of 2 or more above
- Single sign-on (SSO): one-time login across multiple systems (e.g., Google or Microsoft SSO)

# Authorization Models 
- DAC (Discetionary Access Control): owner decides who can access (windows permissions)
- MAC (Mandatory Access Control): Access based on classification levels (military systems)
- RBAC (Role-BAsed Access Control): permissions assigned to roles (Admin, Manager, user)
- ABAC (Attribute-Based Access Control): access based on conditions (time, location, user types)

## Example:
An "HR Manager" role can view employee data while "Employee" role can only view their own profile 
# Best Practices
- Use Strong, unique passwords.
- Apply MFA whereever possible.
- Review role-based permissions regularl.
- Log all authentication and access event.
