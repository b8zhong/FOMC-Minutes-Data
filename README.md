**Federal Open Market Committee (FOMC) Meeting Statements & Minutes Repository**

This repository automatically scrapes, aggregates, and updates a dataset comprising the Federal Reserve's FOMC meeting statements and minutes, providing a robust historical view of changes in U.S. monetary policy over time.

The scraper operates via a scheduled GitHub Actions workflow, which periodically polls the Federal Reserve's website for new statements and minutes as they become available.

The dataset spans communications from the year 2000 onward, with the data presented exactly as found on the Federal Reserve's website.

**Dataset Usage**

The most up-to-date dataset can be found at [communications.csv]. New data is appended based on your configured update frequency (set to intervals greater than one week).

**Dataset Fields**

-  Date: The date of the FOMC meeting.

-  Release Date: The publication date of the statement or minutes. Note: minutes are typically released approximately three weeks after the meeting.

-  Type: Specifies the communication type, either statement or minutes.

-  Text: The content of the communication release.

**Research Significance**

Monetary policy decisions articulated in FOMC statements have been extensively studied, demonstrating significant real-time impacts on market volatility and movements, including changes to equity indices[^1] and interest rate sensitivity[^2].

[^1]: Rosa, C. (2011). "Words that shake traders: The stock market's reaction to central bank communication in real time." *Journal of Empirical Finance*, 18(5), 915-934.

[^2]: Gürkaynak, R. S., Sack, B., & Swanson, E. (2005). "The sensitivity of long-term interest rates to economic news: Evidence and implications for macroeconomic models." *American Economic Review*, 95(1), 425-436.

**Background on the FOMC**

The [Federal Open Market Committee (FOMC)](https://www.federalreserve.gov/monetarypolicy/fomc.htm) meets eight times annually to make pivotal decisions regarding U.S. monetary policy. The committee's mission centers on the Federal Reserve's dual mandate: fostering maximum employment and maintaining price stability (i.e., managing inflation).

The FOMC meeting statement serves as one of the Federal Reserve's principal channels for formal communication. It contains critical insights into interest rate decisions, economic outlook assessments, inflation perspectives, and forward guidance. This information is instrumental for businesses, investors, and the public in understanding and adapting to monetary policy directions.
