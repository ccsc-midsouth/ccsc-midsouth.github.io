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

Thank you for considering a submission to our conference. We invite paper submissions for in-person presentation at the conference. We are also accepting submissions for in-person panels, tutorials, workshops, and posters. There are also opportunities for student papers.

#### Submission is an Easy 3-Step Process:

1. Develop your manuscript (for papers) or abstract (for proposals for panels, tutorials, workshops, or posters). Papers must be 10 pages or less.

1. Make sure that your submission is properly formatted to CCSC’s guidelines, in length and layout. To do so, please visit [this repository for sample templates and additional instructions](https://ccsc-journal.github.io/ccsc-editor/authors.html).

1. Submit your manuscript PDF at our [submission portal](https://www.conftool.org/ccsc-ms/).

#### Timeline

| Event | Date |
|:------|:-----|
| Submissions Due |  November 30, 2025 |
| Author Notification | January 7, 2026 |
| Final Submissions | January 18, 2026 |
| Student Paper Submissions Due | March 10, 2026 |
| Student Paper Notification | March 23, 2026 |

### Papers

We invite professionals to submit papers that will enhance their knowledge of academic computing topics. All topics will be considered and those papers that are accepted will be presented at the conference and published in the [Journal of Computing Sciences in Colleges](https://www.ccsc.org/journal/) and the [ACM Digital Library](https://dl.acm.org/). Papers (at most 10 pages, single-spaced) must be **anonymized to allow blind reviewing.** 

### Panels / Tutorials / Workshops

We invite professionals to submit abstracts describing panels, tutorials, and workshops related to academic computing topics which they believe conference attendees will find timely. All topics will be considered; those that are accepted will be presented at the conference and their abstracts published in the conference proceedings.

### Posters

We invite professionals and students to submit abstracts describing posters related to academic computing topics which they believe conference attendees will find timely. All topics will be considered; those that are accepted will be presented at the conference. 

### Student Papers

The MidSouth region seeks to encourage student projects and research by providing a forum for them to present their work. Student papers will be accepted for presentation during the conference. *Student papers will not be published in the Journal*. Both undergraduate and graduate students may submit papers.

{% include note.html content="All papers submitted should be the original work of the student. Mentoring faculty may be acknowledged in the body of the paper but should not be included in the list of authors." %}

Students papers should be formatted as professional academic papers. As such, the paper must:

* Include an abstract of between 100 and 350 words that describes the work.
* Include an introduction, a body, and a conclusion/summary.
* If a research paper, discuss related work.
* Discuss methods, techniques, and results in the body. The content of the body, of course, will depend upon whether the paper addresses a development project or a research project. The body of the paper should be organized using appropriate subsections.
* Provide appropriate reference to works that are not the author’s work. The reference style may follow an accepted form or style (eg., MLA, AMA, Chicago Style, for example). You may also follow the reference style for a computing journal. When in doubt, choose the reference style of the Journal of Computing Sciences in Colleges.
* Be 10 pages or shorter

{% endif %}

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

{% include tip.html content="Retired? You must Must be 62 years of age or over, and retired from full time employmentn to qualify." %}

{% include warning.html content="We do not accept cash payments." %}

{% endif %}

## <a name="Program">Program</a>

Program TBA

## <a name="travel">Travel</a>

Lipscomb University is located at 1 University Park Dr, Nashville, TN 37204.

 <div id="map"></div>
 <script>
    var map = L.map('map').setView([36.104, -86.798], 13);
    L.tileLayer('https://tile.openstreetmap.org/{z}/{x}/{y}.png', {
    maxZoom: 19,
    attribution: '&copy; <a href="http://www.openstreetmap.org/copyright">OpenStreetMap</a>'
    }).addTo(map);
 </script>

### Hotel Recommendations

Hotels TBA

## <a name="committee">Organizers</a>

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