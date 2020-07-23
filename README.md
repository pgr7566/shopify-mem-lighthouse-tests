#  Lighthouse-Tests
Using Google Puppeteer to run Google Lighthouse programmatically within a CI-CD environment and generate reports to measure performance accessibility and security on the fly.

### What is Lighthouse?
[Google Lighthouse](https://developers.google.com/web/tools/lighthouse/) is an open-source, automated tool for improving the quality of web pages. You can run it against any web page, public or requiring authentication. It has audits for performance, accessibility, progressive web apps, and more.

### What is Puppeteer?
 Most things that you can do manually in the browser can be done using [Google Puppeteer](https://developers.google.com/web/tools/puppeteer/)! Automate form submission, UI testing, keyboard input, etc. Create an up-to-date, automated testing environment. Run your tests directly in the latest version of Chrome using the latest JavaScript and browser features.

### Baseline scores
    eg: baselineScores
            "Performance": 0.80,
            "Accessibility": 0.70,
            "Best Practices": 0.80,
            "SEO": 0.80

 ### Slack-Alerts
 We are sending slack alserts using slack-webhook in case of test fail

### Setup 
Install node via `brew install node`

### Run it locally

`npm install`

`node lighthouse-MEM.js`



### Output
Reports will be stored in ./reports folder

