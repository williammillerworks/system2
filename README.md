# Simple Personal Blog for GitHub Pages

[bolt prototype](https://import-williammiller-odl6.bolt.host/)

09.10.25: Hedvig Letters Serif, Pretendard, Inter font applied

09.12.25: Add Now page with URL-based navigation

09.13.25: Fix font sizing consistency, add structured content.json, and implement text truncation with ellipsis for main content on narrow screens

09.14.25: Add post detail page with content loading / Enhanced markdown rendering with typography and page transitions

## TL;DR
The **Simple Personal Blog for GitHub Pages** project enables anyone to quickly launch a clean, easy-to-edit blog hosted for free via GitHub Pages. It solves the problem of setting up and maintaining a personal blog with minimal configuration, offering essential features like article lists, post pages, and a "Now" page—ideal for solo writers or developers seeking a portfolio or content hub.

***

## Goals

### Business Goals
- Establish a professional online presence for the author with clear branding.  
- Lower the barrier to publishing and maintaining content through a simple, static site solution.  
- Drive regular updates by streamlining the writing and publishing process.  
- Enable future audience engagement or portfolio referencing with tracked, public content.  
- Set a scalable foundation for future blog features or integration (e.g., custom domains, analytics).  

### User Goals
- Publish new posts easily without technical overhead.  
- Present a curated list of articles and personal information for visitors.  
- Maintain a visually satisfying, mobile-friendly site with minimal design effort.  
- Ensure platform reliability without regular maintenance or complex updates.  
- Enable straightforward updates (e.g., adding posts or tweaking pages) directly from GitHub.  

### Non-Goals
- Advanced content management (e.g., rich in-browser editing, multi-author workflows).  
- User authentication, comments, or interactive features.  
- Automated deployment pipelines or complex integrations beyond basic GitHub Pages support.  

***

## User Stories

### Persona: Blog Owner/Author
- As a blog owner, I want to list all my published posts on the homepage so that visitors can quickly browse my content.  
- As a blog owner, I want to create individual article pages, so that each post can be easily read and shared.  
- As a blog owner, I want a simple "Now" page, so that I can introduce myself and my blog’s purpose.  
- As a blog owner, I want clear navigation (header/footer), so readers can easily move between pages.  
- As a blog owner, I want to update my blog content by editing markdown or HTML files in my repo, so managing posts is fast and hassle-free.  

### Persona: Reader/Visitor
- As a reader, I want to access the blog without login or paywalls, so I can freely consume content.  
- As a reader, I want to view posts in a clean, readable format, so I can enjoy the content without distractions.  
- As a reader, I want concise information about the author, so I can establish credibility and learn more if interested.  

***

## Functional Requirements

### Core Blog Features (High Priority)
- **Homepage (Post List):** Reverse-chronological list of articles with titles, excerpts, and dates.  
- **Article Pages:** Dedicated page for each blog post with consistent typography and layout.  
- **Now Page:** Static author intro, optional photo, and mission statement.  
- **Header/Footer Layout:** Simple navigation, blog title/branding, and copyright.  

### Design & Navigation (Medium Priority)
- Responsive design for mobile and desktop.  
- Readable typography & consistent fonts.  
- Basic SEO with HTML title, meta, and OG tags.  

### Future Extensibility (Low Priority)
- Posts added via markdown/HTML in repo.  
- Easy styling customization with theme variables.  
- Analytics script hook for future use.  

***

## User Experience

### Entry Point & First-Time User Experience
- Blog accessible via GitHub Pages URL or custom domain.  
- Landing page shows blog title and recent posts.  
- First-time visitors see a clean design and easy access to "About."  

### Core Experience
1. **Homepage** → Titles, dates, summaries with navigation.  
2. **Click post title** → Clean article detail page.  
3. **About page** → Author bio, intro, vision, optional photo.  
4. **Author updates content** → New markdown = new post automatically.  
5. **Repeat visitors** → Can freely explore archives or bookmark.  

### Advanced Features & Edge Cases
- Branded **404 page** if content missing.  
- Accessibility: contrast, readable font sizes.  
- Progressive enhancement: content works without JavaScript.  

### UI/UX Highlights
- Consistent navigation and footer.  
- Minimalist, readable design.  
- Responsive layout for small screens.  
- Accessible contrast and typography.  
- Simple favicon/branding.  

***

## Narrative
An aspiring developer wanted a simple, elegant blog to share ideas and projects. Overwhelmed by heavy CMS platforms, he created a GitHub Pages–hosted blog: minimal, reliable, beautiful.  

Now, writing a new post is effortless—just push a markdown file, and it’s live. The site loads fast, adapts on all devices, and highlights the content without distractions. Over time, he customizes colors and layouts, proud his blog grows with him—no plugins, no hidden costs, no loss of control.  

The project becomes not only a portfolio but a professional gateway: showcasing both creativity and technical clarity.  

***

## Success Metrics

### User-Centric
- Time required to publish a new post.  
- Reader engagement (# visitors, avg. reading time).  
- Feedback (mentions, personal comments).  

### Business
- Number of posts per month.  
- Portfolio-driven contacts/opportunities.  
- Brand recognition improvement.  

### Technical
- Uptime and load speed.  
- Cross-browser correctness.  
- Reliability of commit/push updates.  

### Tracking Plan
- Homepage views.  
- Article page views.  
- About page visits.  
- 404 incidents.  
- Number of posts created/updated.  

***

## Technical Considerations

### Technical Needs
- Static site on GitHub Pages (no DB).  
- HTML, CSS, minimal JS.  
- Markdown support.  
- Consistent folder structure for posts.  

### Integration Points
- GitHub Pages deployment.  
- Optional: Analytics, social links, domain setup.  

### Data Storage & Privacy
- All content stored in public GitHub repo.  
- No user authentication.  

### Scalability & Performance
- Optimized for small/medium traffic.  
- CDN-delivered static assets.  
- Future extensibility supported.  

### Potential Challenges
- Keeping design minimal yet flexible.  
- Handling updates if GitHub Pages changes.  
- Managing missing content gracefully.  

***

## Milestones & Sequencing

### Team
- 1 person (designer, developer, product owner).  

### Phases

#### Phase 1: MVP Launch
- **Deliverables:** Homepage, article template, About page, navigation, branding, deployment.  
- **Dependencies:** GitHub repo, initial color palette & font.  

#### Phase 2: Design Polish & Mobile Optimization
- **Deliverables:** Responsive design, typography/theme, 404, favicon, SEO tags.  
- **Dependencies:** MVP completion.  

#### Phase 3: Customization & Extensibility (Optional/Future)
- **Deliverables:** Analytics snippet support, category/tag filters.  
