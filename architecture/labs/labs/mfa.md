## Multi-Factor Authentication (MFA)

- Enabled OTP-based MFA in Keycloak.
- Forced MFA enrollment using Configure OTP required action.
- Differentiated between MFA enrollment and MFA enforcement.
- Tested authentication using authenticator applications.

### MFA Lockout & Recovery
- Simulated loss of MFA device.
- Observed authentication failure at OTP stage.
- Reset OTP credentials securely.
- Forced re-enrollment and restored access.
