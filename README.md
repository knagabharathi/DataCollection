# Web Scraping

## What is Web Scraping?
- Web scraping is a technique used to extract large amounts of data from websites. It involves programmatically visiting web pages andextracting information from them. This process can range from simple data collection tasks, like scraping prices from an e-commerce site, tomore complex activities, such as harvesting contact information for research purposes.

## Is web scraping legal?
- The legality of web scraping depends on several factors and can vary by country. Generally, scraping publicly accessible data for personal, non-commercial use is considered legal. However, issues arise when scraping:
- Data behind a login or other access controls.
- Copyrighted material or proprietary information.
- Websites with explicit terms of service that prohibit scraping.
It's crucial to respect privacy laws (like GDPR in Europe), adhere to the website's terms of service, and avoid overloading servers.
When in doubt, seeking legal advice or obtaining explicit permission from the website owner is advisable.


# How to make sure that whatever we are scraping is appropriate?
-Websites often use a
robots.txt
file to communicate with web crawlers. Access this fi le by appending
/robots.txt
to the website's baseURL (e.g.,
https://en.wikipedia.org/robots.txt
).
This fi le provides guidelines on what parts of the site can or can't be crawled by automated agents. However, note that
robots.txt
is more ofa guideline for search engines and does not have legal standing.
Most websites have a Terms of Service (ToS) or Terms of Use agreement, often found in the footer of the homepage. Review this document tosee if it explicitly prohibits scraping.

