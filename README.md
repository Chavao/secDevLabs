# secDevLabs

<img src="images/blinking-panda.gif" align="" height="120" />

The main goal of this project is to provide a laboratory for those who are interested in learning about web security development in a practical manner. 

## Build your own lab!

By provisioning a local lab via docker-compose, you will learn how to find, test and mitigate the most critical web application security risks.

## Disclaimer

These are vulnerable applications! 🔥
 
## OWASP Top 10 (2017) Apps

- A1 - Injection - [CopyNPaste API](owasp-top10-2017-apps/a1/copy-n-paste) 
- A2 - Broken Authentication - [Saidajaula Monster Fit](owasp-top10-2017-apps/a2/saidajaula-monster)
- A3 - Sensitive Data Exposure - [Insecure Go Project](owasp-top10-2017-apps/a3/insecure-go-project)
- A4 - XML External Entities (XXE) - [ViniJr Blog](owasp-top10-2017-apps/a4/vinijr-blog)
- A5 - Broken Access Control - [Vulnerable Ecommerce API](owasp-top10-2017-apps/a5/ecommerce-api)
- A6 - Security Misconfiguration - [Vulnerable Wordpress Misconfig](owasp-top10-2017-apps/a6/misconfig-wordpress)
- A7 - Cross-Site Scripting (XSS) - [Gossip World](owasp-top10-2017-apps/a7/gossip-world)
- A8 - Insecure Deserialization - [Amarelo Designs](owasp-top10-2017-apps/a8/amarelo-designs)
- A9 - Using Components With Known Vulnerabilities - [Cimentech](owasp-top10-2017-apps/a9/cimentech)
- A10 - Insufficient Logging&Monitoring - [GamesIrados.com](owasp-top10-2017-apps/a10/games-irados)

## So you think you know how to solve a vulnerability?

Nice! You can send us your mitigation of the vulnerability directly through a Pull Request, using the [review requested 👀](https://github.com/globocom/secDevLabs/issues?utf8=%E2%9C%93&q=label%3A%22review+requested+%F0%9F%91%80%22+) label. We expect your mitigation proposal to have all the changes needed to completely fix the vulnerability and a short explanation on what you are doing. If you're feeling a bit lost, try having a look at [this mitigation solution](https://github.com/globocom/secDevLabs/pull/29), it might help!

## Contributing
We encourage you to contribute to SecDevLabs! Please check out the [Contributing to SecDevLabs](/docs/CONTRIBUTING.md) guide for guidelines on how to proceed! 

## License

This project is licensed under the BSD 3-Clause "New" or "Revised" License - read [LICENSE.md](LICENSE.md) file for details.
