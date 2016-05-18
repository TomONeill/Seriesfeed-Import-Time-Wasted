# Decrease the requests
Currently, this script takes an episode from Bierdopje.com,
converts the episode tag (SxxExx) to an id usable on Seriesfeed
and then checks if the episode was actually obtained/seen or not.

The obtained/seen status needs to be checked before that,
because now there are a lot of requests that are NOT needed.

This causes the script to be slower than it needs to be,
plus, Seriesfeed's database is receiving more load
than needed.
