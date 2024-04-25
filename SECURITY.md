# Security Notice

This is the security notice for all DfE (Department for Education) repositories. The notice explains how vulnerabilities should be reported to the DfE. At the DfE there are cyber security and information assurance teams, as well as security-conscious people within the programmes, that assess and triage all reported vulnerabilities.

## Reporting a Vulnerability

The Department for Education is an advocate of responsible vulnerability disclosure. If you’ve found a vulnerability, we would like to know so we can fix it.

If you believe you have found a security vulnerability, please submit your report to us using the following link:

https://hackerone.com/41ff5198-0e21-4656-9f54-03cce570d7ff/embedded_submissions/new

In your report please include details of:

* the website, page or repository where the vulnerability can be observed
* a brief description of the vulnerability
* optionally, the type of vulnerability and any related [OWASP category](https://owasp.org/www-community/vulnerabilities/)
* steps to reproduce. These should be a benign, non-destructive, proof of concept. This helps to ensure that the report can be triaged quickly and accurately. It also reduces the likelihood of duplicate reports, or malicious exploitation of some vulnerabilities, such as sub-domain takeovers.

## Scope

The following are **not** in scope:

* volumetric vulnerabilities, for example overwhelming a service with a high volume of requests
* reports indicating that our services do not fully align with "best practice", for example missing security headers

If you are not sure, you can still contact us via email at <CHANGE TO VDP>.

## Bug bounty

Unfortunately, the DfE doesn't offer a paid bug bounty programme. The DfE will make efforts to show appreciation to people who take the time and effort to disclose vulnerabilities responsibly via our [thanks.txt](https://vdp.security.education.gov.uk/thanks.txt).

## What to expect

After you have submitted your report, we will respond to your report within 5 working days and aim to triage your report within 10 working days. We’ll also aim to keep you informed of our progress.

Priority for remediation is assessed by looking at the impact, severity and exploit complexity. Vulnerability reports might take some time to triage or address. You are welcome to enquire on the status but should avoid doing so more than once every 14 days. This allows our teams to focus on the remediation.

We will notify you when the reported vulnerability is remediated, and you may be invited to confirm that the solution covers the vulnerability adequately.

Once your vulnerability has been resolved, we welcome requests to disclose your report. We’d like to unify guidance to affected users, so please do continue to coordinate public release with us.

Where a report qualifies, we will offer to include you on [our thanks and acknowledgement page](https://vdp.security.education.gov.uk/thanks.txt). We will ask you to confirm the details you want included before they are published.

## Code of Conduct

The DfE has a contributors code of conduct, which you can find here: [CODE_OF_CONDUCT.md](https://github.com/dfe-digital/.github/blob/master/CODE_OF_CONDUCT.md)

---

### Further reading and inspiration about responsible disclosure and `SECURITY.md`

* [Ministry of Justice vulnerability disclosure policy](https://mojdigital.blog.gov.uk/vulnerability-disclosure-policy)
* [NCSC vulnerability reporting](https://www.ncsc.gov.uk/information/vulnerability-reporting)
