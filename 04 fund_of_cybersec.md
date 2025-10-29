# Fundamentals of Computer Security 
## Identification,Authentication and Authorization
CONCEPT - DESCRIPTION - EXAMPLE

**Identification** - Claiming an identity - Typing username

**Authentication** - Proving identity - Entering password/fingerprint

**Authorization** - Granting access - Accessing certain files after login

## Key Principle:
"Authentication vertices who you are.Authorization decides what you can do."

# Authentication Methods 
- Knowledge-based: Passwords,PINS
- Possession-based: Smart cards,OTP tokens
- Inherence-based: Biometric (fingerprint,face ID)
- Multifactor Authentication(MFA): Combination of 2 or more above
- SIngle Sign-On (SSO): One-time login across multiple system (eg:Google or Microsoft SSO)

# Authorization Models
- DAC (Discretionary Access Control): Owner decides who can access(Windows permissions)
- MAC (Mandatory Access Control): Access based on classification levels (Military systems)
- RBAC (Role-Based Access Control): Permissions assigned to roles (Admin,Manager,User)
- ABAC (Attribute-Based Access Control): Access based on conditions (Time,Location,User type)

## Example:
An "HR Manager" role can view employee data,while "Employee" role can only view their own profile
# Best Practices:
- Use strong,unique passwords
- Apply MFA wherever possible
- Review role-based permissions regularly
- Log all authentication and access events
  
