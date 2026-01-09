## Multi-Factor Authentication (MFA)

- Enabled OTP-based multi-factor authentication in Keycloak.
- Forced MFA enrollment using the Configure OTP required action.
- Differentiated between MFA enrollment and MFA enforcement.
- Tested MFA login using authenticator applications.

### MFA Lockout & Recovery Scenario
- Simulated a user losing access to the MFA device.
- Observed authentication failure at the OTP stage.
- Reset OTP credentials securely.
- Forced re-enrollment and successfully restored user access.

This scenario reflects common IAM incidents handled in enterprise environments.
