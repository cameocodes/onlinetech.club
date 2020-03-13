# Which meetups and tech events have been moved online due to COVID-19?
Many events - from local meetups to international conferences - are moving their gatherings online due to the risk of COVID-19. Please open a new pull request to add your event.

Jump to: <a href="#meetups">Meetups</a> || <a href="#conferences">Conferences</a>

<a name="meetups"></a>
## Meetups by date

{% assign sorted = (site.data.meetups | sort: 'meetup_date') %}

| Meetup Date | Meetup Name | City | Announcement | Last Updated |
| --- | --- | --- | --- | --- | --- | --- |
{% for meetup in sorted %}| {{meetup.meetup_date}} | {{meetup.meetup_name}} | {{meetup.city}} | {{meetup.announcement}} | {{meetup.last_updated}} |
{% endfor %}

<a name="conferences"></a>
## Conferences by date

{% assign sorted = (site.data.conferences | sort: 'conference_date') %}

| Conference Date | Conference Name | Announcement | Free to Join? | Last Updated |
| --- | --- | --- | --- | --- | --- | 
{% for conference in sorted %}| {{conference.conference_date}} | {{conference.conference_name}} | {{conference.announcement}} | {{conference.free_to_join}} | {{conference.last_updated}} |
{% endfor %}


# Tips for moving your in-person event online

Brian Rinaldi has written a great article full of [tips for running virtual meetups and events](https://dev.to/remotesynth/tips-for-running-virtual-meetups-and-events-2bo1), including:
- how to choose the right streaming software
- considering how scheduling virtual meetups might differ to in-person meetups
- taking registrations for the event
- sending out any materials before the event
- testing your virtual meetup setup prior to starting
- expect the unexpected!

Sarah Thiam [also suggests:](https://dev.to/truckerfling/community-management-in-a-crisis-coronavirus-lessons-part-2-6da)
- making the decision to go virtual or cancel _with_ your community
- considering the pros of going virtual (low costs, greater accessibility etc.)
- choosing the right streaming software (with a great table of comparisons)
- what to look for in a great moderator 
- considering recording the event for in-demand viewing
- inviting an overseas expert