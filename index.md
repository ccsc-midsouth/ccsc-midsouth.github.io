---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# For courses with a single offering in the _config.yml,
# uncomment the following line and comment out the course-multi line

layout: conference
---
<br/>

# <a name="description">Overview</a>

{{ site.description }}

{% if site.participation %}

## <a name="cfp">Call for Participation</a>

Thank you for considering a submission to our conference. We invite paper submissions for in-person presentation at the conference. We are also accepting submissions for in-person panels, tutorials, workshops, and posters.

#### Submission is an Easy 3-Step Process:

1. Develop your manuscript (for papers) or abstract (for proposals for panels, tutorials, workshops, or posters). Papers must be 10 pages or less.

1. Make sure that your submission is properly formatted to CCSC’s guidelines, in length and layout. To do so, please visit [this repository for sample templates and additional instructions](https://ccsc-journal.github.io/ccsc-editor/authors.html).

1. Submit your manuscript PDF at our [submission portal](https://www.conftool.org/ccsc-ms/).

#### Timeline

| Event | Date |
|:------|:-----|
| Submissions Due | Monday, January 12, 2026 |
| Paper / Panel / Tutorial / Workshop Notification | Wednesday, February 4, 2026 |
| Poster Submissions Due | Monday, March 16, 2026 |
| Poster Notification | Monday, March 23, 2026 |

#### Reviewers

CCSC conferences rely on volunteers and assistance in many ways. Individuals who are interested in reviewing papers for CCSC can use [this form](https://forms.gle/BuBMkC2UQaNCmgh38) to submit their information.

### Papers

We invite professionals to submit papers that will enhance their knowledge of academic computing topics. All topics will be considered and those papers that are accepted will be presented at the conference and published in the [Journal of Computing Sciences in Colleges](https://www.ccsc.org/journal/) and the [ACM Digital Library](https://dl.acm.org/). Papers (at most 10 pages, single-spaced) must be **anonymized to allow blind reviewing.** 

### Panels / Tutorials / Workshops

We invite professionals to submit abstracts describing panels, tutorials, and workshops related to academic computing topics which they believe conference attendees will find timely. All topics will be considered; those that are accepted will be presented at the conference and their **one-page abstracts** published in the conference proceedings.

### Posters

We invite professionals **and students** to submit abstracts describing posters related to academic computing topics which they believe conference attendees will find timely. All topics will be considered; those that are accepted will be presented at the conference and their **one-page abstracts** published in the conference proceedings. 

{% endif %}

## <a name="programming">Student Programming Contest</a>

We will be hosting a student programming contest Friday afternoon, April 10. The contest will be ICPC style, with provided Linux computers and a restricted network environment. More details are forthcoming.

{% if site.registration %}

## <a name="registration">Registration</a>

Registration for the CCSC:Midsouth conference is open. INCLUDE LINK!!!

{% include important.html content="Early Registration ends April 1, 2026. Regular Registration is from April 2, 2026 to April 10, 2025." %}

| Category  | Early Bird (until 4/1) | Regular (4/2 - 4/12) |
|:------|------:|------:|
| Author/Presenter          | $150  | $175 |
| Full Attendee             | $100  | $120 |
| Full Attendee w. no meals | $50  | $50 |
| Retired Faculty           | $50  | $50 |
| K-12 Faculty              | $50  | $50 |
| Student Full              | $75  | $75 |
| Student w. no meals       | $30  | $30 |
| Extra dinner              |       | $40 |
| Extra lunch               |       | $20 |

{% include tip.html content="Retired? You must be 62 years of age or over, and retired from full time employment to qualify." %}

{% include warning.html content="We do not accept cash payments." %}

{% endif %}

{% if site.program %}

## <a name="Program">Program</a>

Program TBA

{% endif %}

## <a name="travel">Travel</a>

Lipscomb University is located at [1 University Park Dr, Nashville, TN 37204](https://maps.app.goo.gl/4k2ZM1m62JaqTTgM6).

 <div id="map"></div>
 <script>
    var map = L.map('map').setView([36.104, -86.798], 15);
    var ccsc = L.marker([36.104398546933275, -86.79885670680494]).addTo(map);
    L.tileLayer('https://tile.openstreetmap.org/{z}/{x}/{y}.png', {
    maxZoom: 19,
    attribution: '&copy; <a href="http://www.openstreetmap.org/copyright">OpenStreetMap</a>'
    }).addTo(map);
 </script>

### Hotel Recommendations

Multiple Hotels are available near Lipscomb University. Please visit the Lipscomb University website for [recommended hotels and booking codes](https://lipscomb.edu/student-life/nashville/staying).

## <a name="committee">Organizers</a>

The CCSC:MidSouth Conference would not happen without the volunteers listed below. If you would like to volunteer to help organize future
conferences, please contact [Gabe Ferrer](https://www.hendrix.edu/mathcs/profile.aspx?id=70718), CCSC MidSouth Regional Representative.

### Steering Committee

| Position  | Volunteer | Institution | 
|:------|:------|
| Regional Representative         | Gabe Ferrer | Hendrix College |
| Editor            | TBA | |
| Registrar         | TBA | |
| Treasurer         | Ed Lindoo | Regis University|
| Webmaster         | Mark Goadrich | Hendrix College

### Conference Committee

| Position  | Volunteer | Institution |
|:------|:------|
| Conference Chair         | Susan Hammond | Lipscomb University |
| Papers Chair         | Robin Ghosh | Arkansas Tech University |
| Poster Chair         | Kriti Chauhan | Austin Peay State University |
| Workshops/Tutorials/Panels Chair | Olivera Grujic | California State University - Stanislaus |
| Exhibitors Chair | Mario Guimares | Southeast Missouri State University |
| Publicity Chair | Rao Li | University of South Carolina - Aiken |

## <a name="sponsors">Sponsors</a>

{% include resources.html content=site.resources %}