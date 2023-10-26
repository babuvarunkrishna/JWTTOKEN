# JWTTOKEN

Session, cookie, JWT, token, SSO, and OAuth 2.0 - what are they?

These terms relate to managing user identity when logging into websites. You declare who you are (identification), your identity is verified (authentication), and you're granted appropriate permissions (authorization). Many solutions exist and continue to emerge.

From simple to more complex:

🔹WWW-Authenticate is very basic. The browser prompts for username and password. It lacks control over the login lifecycle, so is rarely used today.

🔹Session-cookie is prevalent in browsers. Servers maintain session storage, and browsers store session IDs in cookies. While browsers primarily use cookies, mobile apps can use them in web views but often prefer tokens for native functions.

🔹Tokens are encoded data used for validation, allowing clients to avoid sending credentials repeatedly. They ensure data integrity but aren't always encrypted.

🔹JWT provides a standardized format for tokens. They are digitally signed to ensure their authenticity. Because JWTs can hold session or user data in their claims, servers don't need to store this information separately for verification.

🔹SSO (single sign-on) lets you log in once then access multiple sites. Uses central authentication service (CAS) to maintain cross-site info.

🔹OAuth 2.0 authorizes one site to access your info on another site.

How do you see this landscape evolving? Will any particular standards dominate for web and mobile login?

![JWTTOKEN](https://github.com/babuvarunkrishna/JWTTOKEN/assets/116940622/651f68e0-7f46-4d3a-89ac-701aa92c8e19)
