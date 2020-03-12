## onlinetech.club

[onlinetech.club](http://onlinetech.club)

# Which meetups and tech events have been moved online due to COVID-19?
Many events - from local meetups to international conferences - are moving online due to the risk of COVID-19. Please open a new pull request to add your event.

Jump to: <a href="#meetups">Meetups</a> || <a href="#conferences">Conferences</a>

<a name="meetups"></a>
## Meetups by Date

{% assign sorted = (site.data.meetups | sort: 'meetup_date') %}

| Meetup Date | Meetup Name | City | Announcement | Last Updated |
| --- | --- | --- | --- | --- | --- | --- |
{% for meetup in sorted %}| {{meetup.meetup_date}} | {{meetup.meetup_name}} | {{meetup.city}} | {{meetup.announcement}} | {{meetup.last_updated}} |
{% endfor %}

<a name="conferences"></a>
## Conferences by Date

{% assign sorted = (site.data.conferences | sort: 'conference_date') %}

| Conference Date | Conference Name | Announcement | Free to Join? | Last Updated |
| --- | --- | --- | --- | --- | --- | 
<<<<<<< HEAD
{% for conference in sorted %}| {{conference.conference_date}} | {{conference.conference_name}} | {{conference.announcement}} | {{conference.free_to_join}} | {{conference.last_updated}} |
=======
{% for conference in sorted %}| {{conference.conference_date}} | {{conference.conference_name}} | {{conference.announcement}) | {{conference.free_to_join}} | {{conference.last_updated}} |
>>>>>>> 60c47d5b0c51b98d09533bf5afdce88118b53a4c
{% endfor %}


# Tips for moving your in-person meetup online

- https://dev.to/truckerfling/community-management-in-a-crisis-coronavirus-lessons-part-2-6da
- https://dev.to/remotesynth/tips-for-running-virtual-meetups-and-events-2bo1

#### Acknowledgements

Big thank you to [@phildini](https://github.com/phildini) and his [stayinghome.club](https://stayinghome.club/) for the idea.

