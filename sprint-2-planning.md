# Sprint 3 Planning  
**Duration:** November 13 – December 20, 2025 (1 week)  

---

## Sprint Goal  
Finalize and deploy a **fully interactive MVP** that enables real user contribution and content discovery.  
This sprint focuses on completing the contributor submission workflow, implementing admin approval functionality, and integrating a simple site-wide search.  
By the end of Sprint 3, the platform should allow new users to log in, create posts, submit them for review, and see approved content appear under corresponding categories.  

---

## Selected User Stories  

- **E3 (Search)(5 pts):** Implement site-wide search endpoint & template  
  *Build search functionality allowing users to find posts by keywords across titles, content, and categories.*  

- **E3 (Search)(3 pts):** ExternalLinks table & display  
  *Enable each post to include curated external resources displayed under post detail and search results.*  

- **E4 (Content)(5 pts):** Contributor submit/edit form  
  *Allow logged-in contributors to create or edit draft posts with Markdown/TinyMCE editor and optional image uploads.*  

- **E4 (Content)(5 pts):** Pending queue view for Admin  
  *Develop admin interface to review pending posts, with Approve/Reject actions and updated post status flow.*  

- **E4 (Content)(3 pts):** Email/flash notifications  
  *Notify contributors when their submissions are approved or rejected through in-app alerts and email.*  

- **E4 (Content)(3 pts):** Audit trail  
  *Record all admin actions (approval/rejection) with timestamps and user IDs for transparency and debugging.*  

- **E5 (Styling)(3 pts):** Apply consistent Bootstrap layout  
  *Refine styling of hub, post list, and search pages to ensure usability and visual consistency.*  

**Total Committed Story Points:** 27  
**Team Capacity:** 3 people × 9 pts = 27 pts  

---

## Dependencies and Risks  

- **Search depends on Post model** from Sprint 1; any schema adjustment could delay testing.  
- **Email feature** requires verified SMTP configuration; fallback plan is flash-only alerts if not ready.  
- **Short sprint duration (1 week)** means no buffer for unplanned issues—scope must remain fixed.  
- **Deployment dependency:** staging auto-deploy pipeline must remain stable for live testing.  

---

- Functional submission workflow from contributor → admin → published.  
- Search bar operational across categories and posts.  
- Admin dashboard for moderation and audit history.  
- Updated and styled front-end consistent across pages.  
- Staging site live with ≥ 10 test users and at least 10 approved posts.  
