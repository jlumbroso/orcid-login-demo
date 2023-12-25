# orcid-login-demo
This is a minimal project to test/demo ORCID OAuth login and identification.

# Information access

- Using only the client ID, we can do implicit OAuth on a purely client-side basis.
- Once the ORCID has been identified, information about the user can be obtained by querying: `https://pub.orcid.org/v3.0/<ORCID>/record`
    - Information that is only available to **Trusted Parties** can only be obtained after 3-legged OAuth (which requires server-side code).
