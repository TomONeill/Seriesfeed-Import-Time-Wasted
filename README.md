# Seriesfeed-Import-Time-Wasted
Import your time wasted from Bierdopje.com to Seriesfeed.com
<BR/>
Enjoy.
<BR/><BR/>
Version <strong>0.2.1</strong> (BETA!)

# Information
With this userscript, you can import your time wasted from Bierdopje.com to Seriesfeed.com.<BR />
In the first step, the userscript checks up on which account you're logged into on Bierdopje.com. If this information is correct, proceed to the next step. If not, log in and refresh the page.<BR />
At step 2 your time wasted is being checked on availability. This means every single series is being checked on existance on Seriesfeed. Series which are not available on Seriesfeed yet are listed with an 'x'. You can request those and check back later. Check the checkboxes on the series you want the Time Wasted to be imported from and proceed.<BR />
At the last step, the actual importing is being done. Every episode of every series is being checked one by one (could be several at the time depending on your browser and userscript version) and updated on Seriesfeed. This may take 30-60 minutes depending on your internet connection, browser and userscript version.

# Screenshots
<img src="https://raw.githubusercontent.com/TomONeill/Seriesfeed-Import-Time-Wasted/master/Screenshots/v0.2-1.png" alt="Version 0.2" width="250px" />
<img src="https://raw.githubusercontent.com/TomONeill/Seriesfeed-Import-Time-Wasted/master/Screenshots/v0.2-2.png" alt="Version 0.2" width="250px" />
<img src="https://raw.githubusercontent.com/TomONeill/Seriesfeed-Import-Time-Wasted/master/Screenshots/v0.2-3.png" alt="Version 0.2" width="250px" />

# Warning
Do not use this userscript on series in which you have episodes obtained/seen manually or before with this userscript. Executing another import on them will uncheck those you have already checked before.

# Which version to use?
I recommend you use <strong>SeriesfeedImportTimeWasted.safe.user.js</strong> which does a fine job, but may be slow.<BR />
Version SeriesfeedImportTimeWasted.user.js does two requests a time, which is a bit faster, but may skip some episodes accidentally.<BR />
If you're a developer and don't want to wait a long time, use the unsafe version (Chrome recommended). Errors can happen and if so, you can view them on the browsers console. Filter on Logs, though, because there will be some images not found errors from Bierdopje.<BR />
Checking your episode data afterwards is always recommended. 

# Changelog
<A HREF="https://raw.githubusercontent.com/TomONeill/Seriesfeed-Import-Time-Wasted/master/Changelog.txt">View changelog</A>

# Other userscripts
Check out other userscripts for Seriesfeed by me:<BR/>
<ul>
    <li><A HREF="https://github.com/TomONeill/Seriesfeed-Import-Time-Wasted">Import Time Wasted</A></li>
    <li><A HREF="https://github.com/TomONeill/Seriesfeed-Move">Move cards on frontpage</A></li>
</ul>

# About userscripts
This is a userscript which you can use in combination with a browser extension to inject JavaScript (Greasemonkey, Tampermonkey).<BR />
This means new functionality can be added, or bugs can be fixed on (discontinued) websites.<BR />
DO NOT INSTALL USERSCRIPTS YOU DON'T TRUST! Check always for urls like the @domain tag at the top of a script before installation. Sensitive data (like usernames, passwords, or banktransactions even, may be sent to other sources.

# Donate
If you like my work so much you feel like doing something nice for me, a complete stranger of the internet, you can.<BR />
<A HREF="https://www.paypal.me/TomONeill">Donate here</A>.
