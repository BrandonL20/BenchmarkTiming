# BenchmarkTiming
A quantitative trading strategy to tilt into benchmark ETF on days where market risk (beta) is rewarded

The jupyter notebook contains 3 tests:<br />
  (1) A replication confirming the findings of Savor & Wilson (2012) on macro-announcements and market beta risk-return relationship.<br />
  (2) An out-of-sample test (2012-2019) finding support that these results continue to persist even after being published.<br />
  (3) A robustness test on the implementation timing of a trading strategy based around macro-announcement days.

Source for data files: <br />
•	Inflation and unemployment announcement dates come from the US Bureau of Labor Statistics website (http://www.bls.gov), where they are available starting in 1958<br />
  o	https://www.bls.gov/bls/histreleasedates.pdf<br />
  o	https://www.bls.gov/bls/archived_sched.htm<br />
•	We use consumer price index (CPI) announcements before February 1972 and producer price index (PPI) thereafter<br />
•	The dates for the FOMC scheduled interest rate announcement dates are available from the Federal Reserve website (Unscheduled FOMC meetings are not included in the sample.)<br />     o https://www.federalreserve.gov/monetarypolicy/fomccalendars.htm<br />
  o https://www.federalreserve.gov/monetarypolicy/fomc_historical_year.htm<br />
• Daily stock data from CRSP<br />
• Treasury yields and Fama-French factor portfolio returns from ken from:<br />
  o https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html<br />
•	Strategy based on work of Pavel G. Savor and Mungo Ivor Wilson<br />
  o Savor, Pavel G. and Wilson, Mungo Ivor, Asset Pricing: A Tale of Two Days (Mar 2012). AFA 2013 San Diego Meetings Paper, Available at SSRN:     <br />   https://ssrn.com/abstract=2024422 or http://dx.doi.org/10.2139/ssrn.2024422
  
Special thanks to BYU professors Brandon Bates and Brian Boyer for mentorship over this project.
