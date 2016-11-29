# Decrease the requests
Currently, this script takes an episode from Bierdopje.com,
converts the episode tag (SxxExx) to an id usable on Seriesfeed
and then sets the obtained/seen status. Setting this information
doesn't need to happen if the episode was already seen.

This causes the script to be slower than it needs to be,
plus, Seriesfeed's database is receiving more load
than needed.
