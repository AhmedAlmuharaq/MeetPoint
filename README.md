# MeetPoint / PointCommun

**Find the earliest time and place a group can meet, then plan how each person gets there.**

MeetPoint is a bilingual mobility app for Belfort and Montbéliard. It combines walking, local buses and regional trains with each participant’s availability and the opening hours of candidate meeting places.

[Open the live demo](https://revolution-arbor-card-atlanta.trycloudflare.com/) · [Run locally](#run-locally) · [Screenshot tour](#screenshot-tour) · [Android app](#android-app) · [Hosting](#hosting)

*Mobility in Smart Cities · IoT Master 2 · Université Marie & Louis Pasteur*

[![MeetPoint recommendation and route map](docs/images/09-recommended-meeting.png)](docs/images/09-recommended-meeting.png)

## What you can do

| Feature | How it works |
| --- | --- |
| Plan a group meeting | Create a meeting, choose its duration and invite people by name. Each participant sets a starting point, availability and allowed modes. |
| Choose where and when to meet | Compare candidate places by earliest feasible start or lowest combined travel time. The planner accounts for travel times, room hours, group capacity where known and the requested meeting duration. |
| Follow individual journeys | See each person’s departure, transfers, walking segments and arrival time. Display journeys together on the map or focus on one. |
| Export travel costs | Download the origin–destination matrix as CSV from the meeting view. |
| Confirm and coordinate | Accept the recommendation, chat with the group, share location by consent and mark progress during the journey. |
| Manage places and meetings | Browse and filter venues, add a place with a map pin, and edit, cancel, reopen or delete meetings. |
| Use English or French | Switch between MeetPoint and PointCommun on desktop, mobile web or the Android WebView client. |

## Screenshot tour

The screens use fictional participants and public locations.

### Plan a meeting

<table>
<tr><td width="50%" valign="top"><a href="docs/images/03-meetings-dashboard.png"><img src="docs/images/03-meetings-dashboard.png" alt="Meetings dashboard" width="540"></a><br><strong>Meetings dashboard</strong><br>See existing meetings, venue pins and transit-data status.</td><td width="50%" valign="top"><a href="docs/images/04-create-meeting.png"><img src="docs/images/04-create-meeting.png" alt="Create a meeting" width="540"></a><br><strong>Create a meeting</strong><br>Set the date, duration and planning objective.</td></tr>
<tr><td width="50%" valign="top"><a href="docs/images/05-invite-by-name.png"><img src="docs/images/05-invite-by-name.png" alt="Invite participants" width="540"></a><br><strong>Invite participants</strong><br>Look up an account by name and send a private invitation.</td><td width="50%" valign="top"><a href="docs/images/07-invitation-response.png"><img src="docs/images/07-invitation-response.png" alt="Respond to an invitation" width="540"></a><br><strong>Respond to an invitation</strong><br>Join the group or decline the request.</td></tr>
<tr><td width="50%" valign="top"><a href="docs/images/17-invitation-popup.png"><img src="docs/images/17-invitation-popup.png" alt="Invitation alert" width="540"></a><br><strong>Invitation alert</strong><br>New invitations surface while the app is open.</td><td width="50%" valign="top"><a href="docs/images/06-invitation-inbox.png"><img src="docs/images/06-invitation-inbox.png" alt="Invitation inbox" width="540"></a><br><strong>Invitation inbox</strong><br>Review invitations and manage notification sound.</td></tr>
<tr><td width="50%" valign="top"><a href="docs/images/08-choose-origin.png"><img src="docs/images/08-choose-origin.png" alt="Choose a starting point" width="540"></a><br><strong>Choose a starting point</strong><br>Pin an origin on the map and set availability and travel modes.</td></tr>
</table>

### Review and follow journeys

<table>
<tr><td width="50%" valign="top"><a href="docs/images/09-recommended-meeting.png"><img src="docs/images/09-recommended-meeting.png" alt="Group recommendation" width="540"></a><br><strong>Group recommendation</strong><br>Review the proposed place, meeting window and conditions.</td><td width="50%" valign="top"><a href="docs/images/10-route-map.png"><img src="docs/images/10-route-map.png" alt="Routes on the map" width="540"></a><br><strong>Routes on the map</strong><br>See the origins, selected venue and available route geometry.</td></tr>
<tr><td width="50%" valign="top"><a href="docs/images/11-individual-itineraries.png"><img src="docs/images/11-individual-itineraries.png" alt="Individual itineraries" width="540"></a><br><strong>Individual itineraries</strong><br>Read each person’s departure, transport legs and arrival.</td><td width="50%" valign="top"><a href="docs/images/18-departure-schedule.png"><img src="docs/images/18-departure-schedule.png" alt="Personal departure schedule" width="540"></a><br><strong>Personal departure schedule</strong><br>Check when to leave after the group approves the plan.</td></tr>
<tr><td width="50%" valign="top"><a href="docs/images/19-bus-train-and-walking.png"><img src="docs/images/19-bus-train-and-walking.png" alt="Campus route by bus, train and foot" width="540"></a><br><strong>Campus route by bus, train and foot</strong><br>A separate reference run to BU Montbéliard using the bundled timetable.</td><td width="50%" valign="top"><a href="docs/images/20-campus-route-map.png"><img src="docs/images/20-campus-route-map.png" alt="Campus route map" width="540"></a><br><strong>Campus route map</strong><br>See the connections across Belfort and Montbéliard.</td></tr>
<tr><td width="50%" valign="top"><a href="docs/images/12-journey-tracking-and-chat.png"><img src="docs/images/12-journey-tracking-and-chat.png" alt="Location sharing and chat" width="540"></a><br><strong>Location sharing and chat</strong><br>Share a demo location and coordinate privately with the group.</td><td width="50%" valign="top"><a href="docs/images/23-proposal-card.png"><img src="docs/images/23-proposal-card.png" alt="Recommended venue and meeting window" width="540"></a><br><strong>Venue recommendation details</strong><br>See the meeting window, total travel time and reservation conditions.</td></tr>
</table>

### Manage meetings, places and your account

<table>
<tr><td width="50%" valign="top"><a href="docs/images/21-edit-meeting.png"><img src="docs/images/21-edit-meeting.png" alt="Edit a meeting" width="540"></a><br><strong>Edit a meeting</strong><br>Change meeting details and recalculate the proposal.</td><td width="50%" valign="top"><a href="docs/images/22-cancel-and-reopen.png"><img src="docs/images/22-cancel-and-reopen.png" alt="Cancel or reopen a meeting" width="540"></a><br><strong>Cancel or reopen a meeting</strong><br>Review a cancelled meeting and restore it when the group is ready.</td></tr>
<tr><td width="50%" valign="top"><a href="docs/images/13-venue-catalogue.png"><img src="docs/images/13-venue-catalogue.png" alt="Venue catalogue" width="540"></a><br><strong>Venue catalogue</strong><br>Filter places by category, city or suitability.</td><td width="50%" valign="top"><a href="docs/images/14-add-a-venue.png"><img src="docs/images/14-add-a-venue.png" alt="Add a place" width="540"></a><br><strong>Add a place</strong><br>Choose a map position and enter place details.</td></tr>
<tr><td width="50%" valign="top"><a href="docs/images/02-register.png"><img src="docs/images/02-register.png" alt="Create an account" width="540"></a><br><strong>Create an account</strong><br>Set up a local demo account.</td><td width="50%" valign="top"><a href="docs/images/15-profile.png"><img src="docs/images/15-profile.png" alt="Edit profile photo" width="540"></a><br><strong>Edit profile photo</strong><br>Upload or remove a profile picture.</td></tr>
<tr><td width="50%" valign="top"><a href="docs/images/01-sign-in.png"><img src="docs/images/01-sign-in.png" alt="Sign in" width="540"></a><br><strong>Sign in</strong><br>Return to your group’s shared meeting space.</td><td width="50%" valign="top"><a href="docs/images/16-mobile-french.png"><img src="docs/images/16-mobile-french.png" alt="PointCommun on mobile web" width="220"></a><br><strong>PointCommun on mobile web</strong><br>Use the French interface from a phone-sized viewport.</td></tr>
</table>

[Sample OD export](docs/od-matrix-example.csv) with three participants travelling to the same candidate venue.

## Try the example

1. Create two demo accounts in separate browser profiles so both users can sign in.
2. Create a 30-minute meeting and invite the second account by name. Accept the invitation from that account.
3. Set your starts near **Belfort-Ville station** and **Montbéliard station**, select walking and public transport, and give both participants a broad availability window such as 08:00–18:00.
4. For a reproducible timetable example, use **3 November 2026**, the date in the bundled reference scenario. For another date, check the included feed coverage and service calendars.
5. Calculate the recommendation, inspect the journeys and export the OD CSV. Approve the proposal from both accounts to open the group chat and location-sharing view.

## Run locally

Clone the repository and start MeetPoint with Python 3.11 or newer. The first run creates a virtual environment and installs the dependencies.

```bash
git clone https://github.com/AhmedAlmuharaq/MeetPoint.git
cd MeetPoint
python3 start.py
```

On Windows, double-click `START.cmd` or run `py -3 start.py`. On all platforms, open [http://localhost:8000](http://localhost:8000). The API schema is available at [/docs](http://localhost:8000/docs).

### Docker Compose

```bash
docker compose up --build -d
curl -fsS http://localhost:8000/api/health
```

Compose binds the service to loopback and stores SQLite in the `meetpoint-db` volume. If you are upgrading an older Compose setup, back up the existing SQLite file and migrate it to the volume before switching. The local Python launcher uses `data/meetings.sqlite3` by default. Set `DB_PATH` to use another database location.

## Android app

Download the [Android 0.4.2 demo APK](MeetPoint-Android-0.4.2-debug.apk), open it on Android 8.0 or newer, and enter the HTTPS address of a running MeetPoint server. Android uses that server’s accounts, meetings and transit data. See the [Android build guide](android/README.md) for Android Studio and Gradle instructions.

## Architecture

```mermaid
flowchart TD
    Client["Web browser or Android WebView"] --> API["FastAPI service"]
    API --> Planner["Meeting and journey planner"]
    API --> DB["SQLite accounts and meetings"]
    Planner --> Data["Venue catalogue and GTFS"]
    Planner --> Walk["Walking cache and optional route verification"]
    Client --> Map["Leaflet and OpenStreetMap"]
```

The planner builds timetable journeys for each participant and candidate venue. It intersects arrivals, attendance windows and venue hours to find a feasible meeting slot, then ranks feasible candidates by the chosen objective. It looks for individual departures that still reach the venue on time. The course’s static Dijkstra and OD calculations are implemented in [app/graph.py](app/graph.py). The timetable planner is in [app/planner.py](app/planner.py).

| Directory | Contents |
| --- | --- |
| [app/](app/) | FastAPI routes, SQLite storage, transport planning and web interface |
| [android/](android/) | Java Android WebView client and Gradle project |
| [data/](data/) | Venue catalogue, transit data, source metadata and reference scenario |
| [scripts/](scripts/) | Feed import, download and reference checks |
| [tests/](tests/) | Planner, API, meeting lifecycle and interface regression tests |
| [docs/](docs/) | Course requirements and screenshot gallery |

Run the tests after local setup with `.venv/bin/python -m pytest -q` on Linux or macOS, or `.\.venv\Scripts\python.exe -m pytest -q` on Windows.

## Hosting

The linked demo uses a Cloudflare Quick Tunnel. It stays available while the host runs both MeetPoint and the tunnel. [Cloudflare Quick Tunnel documentation](https://developers.cloudflare.com/tunnel/get-started/quick-tunnels/)

For a lasting URL, deploy the Docker image on an always-on server. Mount persistent storage at `/var/lib/meetpoint`, route HTTPS to port `8000` through a reverse proxy or named Cloudflare Tunnel, and check `/api/health`. GitHub hosts the source code and this gallery. GitHub Pages serves static files, while MeetPoint needs a running Python API and writable SQLite storage. [GitHub Pages documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)

## Data and scope

- The included **évolitY, Optymo and SNCF** GTFS snapshots share an advertised coverage window of **26 October 2026 to 3 January 2027**. Individual services follow their own calendars and exceptions. [Feed sources and ODbL attribution](data/feed_sources.json)
- Timetable results represent scheduled service. Walking segments can be approximate, and room reservations must be confirmed with the venue. [Data status](data/DATA_STATUS.md)
- The prototype is designed for a trusted demo group. Email ownership is unverified, and signed-in users can edit the shared default venue catalogue. Location sharing requires user consent and a secure browser origin. Individual progress is based on the app’s schedule and participant updates. [Validation notes](VALIDATION.md)

**Project contributors** · Ahmed Al-Muharaq and Owais Ahmed Khan. Course supervised by Philippe Canalda. [Course requirements](docs/COURSE_REQUIREMENTS.md)
