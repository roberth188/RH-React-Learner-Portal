

Below are my responses to the questions. Other materials are as provided in the email.

1. Explain your design decisions

    The textured background for the search and footer panels helps to break up the page into separate sections while keeping visual clutter at a minimum. This background, in particular, parallels similar textures seen on other platforms, and it has soothing qualities.

    The logo is a placeholder, though it symbolizes how education is tied to nodes, evoking ideas of circuitry and internet connectivity. 

    The two-column visual layout of the courses smoothly functions in both mobile and desktop settings.

    Buttons are indicated by curved features, shadows, and fade upon hovering.

    The Dashboard, Calendar, and Catalog buttons all have simple colors and geometries to improve use and accessibility. Their large size aids in reducing misclicks while making their presence known to users with poor eyesight. The choice of text over icons similarly helps disabled users who are using accessibility services like screen readers. According to the 12 Rules (Meyer), reducing cognitive load, through limiting clutter, improves focus and overall success with an elearning platform. 

    The calendar page features a Google Calendar integration. Google calendar offers developer access, which could in turn be a suitable platform for hosting deadlines and related event content for the platform.

    The quotations at the bottom of the page are the second integration, and they serve to motivate users with every new refresh. 

    The account icon has the users profile photo in the background; this was added more for personalization, and if it was found to be distracting with user testing, then it could be removed. The relatively square shape helps to further set it apart from the other buttons around it.

    The course boxes have two sections in contrasting color palettes; the dark top with white text is visually distinct from the assignments listed below. The assignment rectangles could link to content, and they currently list what is due, and when. The icons help to distinguish between types of content. The background images are connected with the courses, and add levity while further distinguishing courses from each other.

    My interactivity involved hovers for buttons, where the buttons lose opacity. I chose this because it matched what other sites offered, and it appeared minimally distracting and resource-intensive. Course blocks also fade in, which could accompany loading data, reducing the total page load time if done in parallel.


2. Explain your development decisions

    Initially, I used create-react-app for initializing the boilerplate for the webapp, but the workflow was too slow for the timeframe. I decided to use a WYSIWYG editor, builder.io, which enabled me to reduce the amount of time between successive iterations of the design. Builder.io integrates smoothly into the build workflow and modifies CSS and related code directly; every design decision translated to React seamlessly and transparently. Builder.io also has features like auto-save and revert as part of its integrated version control.

    React itself is a library, and for routing and related libraries outside of a single-page-application use case, a Framework like Next.js is useful. I initialized the app with Next.js then embedded Builder.io and installed its module. 

    Builder.io with Next.js is a smooth workflow, with refreshing through localhost on the order of seconds. With this combination of tools, I was able to test out more ideas and add more features than with React in a text editor. Viewing the results in a tablet-or mobile form factor is also straightforward. Vendor lock-in is minimal considering how Builder.io exports React JSX code and how it works with standard parameters typically seen with CSS.


3. Explain areas for future improvement

    While the scope of the assignment and my time constraints limited the total set of features I could implement, I was able to draft the bulk of my aesthetic design decisions.

    Features that I gathered from other sites, read about in the literature, or would like to implement with A/B testing include:

    Playlists of lecture content, assignments, and other materials. Students could organize material based on their patterns, such as video-consumption or assignment completion frames of mind. Playlists empower uses to organize content in a way that breaks from the course- or search result-focused forms of organization.

    Constrained feedback and ratings. The norm for learning platforms is to limit feedback, especially feedback that has public visibility. Naturally, sites like rate my professor aim to fill the void. With this platform, on every page or lecture, there could be a rating system consisting of feedback in a dropdown setting; by constraining the communication to a few options, as opposed to a text box, sensitive information is not a concern, and professors can get more feedback than they otherwise would. A five-point rating system could be too little information. Publicly-visible information raises the concerns of students cheating or otherwise compromising the platform.

    Closed-captioning search for material in videos and assignments. Assuming the site hosts videos of lectures, pdf’s of problem sets, and otherwise non-discretized content, students could access material ata a more granular level with search. For example, all videos could have search based on the closed-captioning data. Similarly, all documents could be indexed for search. By offering search, students could more quickly access past material and similarly find relevant content for assignments and other tasks.


4. Add anything else you think is important

    The dashboard, account, and calendar pages are implemented, and their links function. Most other links respond to interaction, but they do not lead anywhere.


-----

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Localhost

First, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000/dashboard) with your browser to see the result.