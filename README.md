# WordPress Authentication Security Lab

**Cybersecurity internship project**

This project examines how repeated password guesses can expose weak credentials on a Bitnami WordPress instance. I used WPScan from BlackArch Linux to run a wordlist-based password test in a lab environment and documented the process in the project report.

## Lab setup

| Component | Role |
| --- | --- |
| Bitnami WordPress | WordPress instance used for authentication testing |
| BlackArch Linux | Security testing environment |
| WPScan | Tool used to test candidate passwords against WordPress authentication |

## Assessment

The lab focused on the risk posed by predictable passwords when a login endpoint accepts repeated attempts. The exercise covered running the password test and documenting the procedure. Keep testing within systems you own or have explicit permission to assess.

## Defensive takeaways

- Use strong, unique passwords and enable multi-factor authentication for administrator accounts.
- Rate-limit repeated login attempts to reduce the number of guesses an attacker can make.
- Monitor failed login attempts and investigate unusual patterns.

## Project report

[Original internship lab report (.odt)](./wordpress-authentication-security-lab-report.odt)
