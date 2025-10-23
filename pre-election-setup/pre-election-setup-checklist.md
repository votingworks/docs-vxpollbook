# Pre-Election Setup Checklist

Use this checklist process to prepare VxPollBook for election day. To see detailed instructions, including screenshots, use the [.](./ "mention") instructions.

### Configuring First VxPollBook

* [ ] Copy the poll book package provided by VotingWorks onto a USB drive
* [ ] Turn on VxPollBook
* [ ] Log in with a system administrator card
* [ ] Insert the USB drive
* [ ] Confirm the election title and date are correct
* [ ] Select a precinct (only if there are multiple precincts)

### Programming Smart Cards

If you are also using VotingWorks's voting system for this election, you should already have cards programmed from VxAdmin. Program any additional cards you need at VxAdmin.

Otherwise, proceed with programming cards at VxPollBook:

* [ ] Log in with a system administrator card (if not already logged in)
* [ ] Select the `Smart Cards` tab from the side menu
* [ ] For each election manager card - insert the card, program the card, and record the PIN
* [ ] For each poll worker card - insert the card and program the card

### Configuring Other VxPollBooks

For each of your remaining poll books:

* [ ] Turn on VxPollBook
* [ ] Log in with the newly programmed election manager card
* [ ] Confirm the election title and date are correct
* [ ] Select a precinct (only if there are multiple precincts)
* [ ] Confirm that the time at the top is correct&#x20;

### Double Check Configurations

On any poll book, open the network details menu by selecting the antennae at the top of the screen and verifying:

* [ ] Number of poll books listed matches total number of poll books
* [ ] The hashes in the `Election` column of the network details menu match
* [ ] The poll books from the same precinct show as `Synced` whereas the other poll books show as `Different Precinct`
