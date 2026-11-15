ISBAT University needs a Student Self-Service Portal. Build the Dashboard and My
Courses pages; the Fee Statement link may point to a placeholder page. Use all three
CSS methods (inline, internal, external) in appropriate contexts. Required Tasks:
(a) Student Dashboard — dashboard.html External CSS (portal.css) for all layout;
inline CSS only for the status badge; internal CSS for the quick-links grid:
• Sidebar (position fixed, 200px wide, background #1A1A2E): ISBAT logo, student
name, nav links to the 3 pages
• Main area: greeting 'Welcome, [Student Name]', today's date, and a status badge
'Active' — apply badge colour (background #EAF3DE, color #27500A) using inline
style
• 3 summary metric cards (Flexbox): GPA, Credit Hours, Outstanding Fee Balance —
white background, border, border-radius in portal.css
• Quick-links grid (2×2) using internal CSS: Dashboard, My Courses, Fee Statement,
Update Profile — each as a large card with label and link
(b) My Courses Page — courses.html. External CSS (portal.css) for layout; internal
CSS for timetable colours; inline CSS for course status badges:
• An 'Enrolled Courses' table: Course Code, Course Name, Credits, Lecturer, Room,
Status — 6 courses with realistic ISBAT data
• Status badges directly on the <td>: Active → inline style background #E1F5EE,
color #085041; Pending → inline style background #FAEEDA, color #633806
• A weekly timetable (Mon–Fri, 8am–5pm in 1-hour rows): fill in 4 courses using
colspan where a lecture spans 2 hours; colour each course using a CSS class in
internal CSS (e.g. .webtech, .cprog)
