# single-transferable-vote

Computes winners to single transferable vote elections for the University of Texas at Austin.  For an overview of single transferable vote, see [this video](https://youtu.be/l8XOZJkozfI) or [this article](https://www.opavote.com/methods/single-transferable-vote).  This implementation follows [Scottish STV rules](https://blog.opavote.com/2016/11/plain-english-explanation-of-scottish.html), including the [Droop quota](https://en.wikipedia.org/wiki/Droop_quota).

The command-line program takes two arguments.  The first is the pathname of a JSON file describing the election.  The second is the pathname of a CSV file generated by HornsLink of the ballots.

The JSON file must list the races in the order that they appear on the CSV file.  For example JSON and CSV files see the doc folder.
