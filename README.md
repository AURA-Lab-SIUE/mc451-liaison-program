# MC451 Liaison Program - Complete Development Handoff

**Status:** MVP Complete & Ready for Development Pod  
**Last Updated:** January 27, 2026  
**Maintained By:** [Development Team]

---

## 📌 Quick Navigation for Developers

New to the project? **Start here:**
1. Read [DEVELOPER_GUIDE.md](DEVELOPER_GUIDE.md) (15 min) - Technical overview
2. Review [ROADMAP.md](ROADMAP.md) (10 min) - What needs to be done
3. Set up locally using [DEVELOPER_GUIDE.md](DEVELOPER_GUIDE.md) → "Development Setup"
4. Join the team Slack/Discord and introduce yourself

For other needs:
- **Instructors customizing:** [CUSTOMIZATION_GUIDE.md](CUSTOMIZATION_GUIDE.md)
- **Team workflow:** [GIT_WORKFLOW.md](GIT_WORKFLOW.md)
- **Deployment:** [DEPLOYMENT.md](DEPLOYMENT.md)
- **QA & Testing:** [TESTING_CHECKLIST.md](TESTING_CHECKLIST.md)
- **Tech details:** [ARCHITECTURE.md](ARCHITECTURE.md)
- **Content planning:** [CONTENT_PLAN.md](CONTENT_PLAN.md)

---

## 🎯 Project Vision

The Liaison Program teaches students to be **bridges between data and communication**—translating research findings into clear action for stakeholders. This website is the platform where students learn through a five-phase journey: Orientation → Discovery → Dictionary → Execution → Delivery.

### What You've Built

A **professional, student-ready resource website** for your Liaison Program course. Here's everything that's included:

### Website Features
- ✅ **Home page** with course overview and quick-start buttons
- ✅ **Setup guide** - Step-by-step Obsidian configuration for students
- ✅ **Resources page** - Central hub for downloads and tools
- ✅ **Five course modules** - Navigation ready for your content
- ✅ **Professional design** - Built with Quarto (responsive, clean, modern)
- ✅ **Search functionality** - Students can search all course content

### Student Resources
- ✅ **Liaison_Vault.zip** - Pre-configured Obsidian vault with:
  - Folder structure for organizing research
  - Weekly journal templates (Connector/Troubleshooter/Critic)
  - Data dictionary template for codebook creation
  - .gitkeep files in all folders
  - README with configuration instructions

### Built & Ready
- ✅ **Website compiled** - All pages are in `_site/` folder
- ✅ **Deployment guide** - Instructions for GitHub Pages, Netlify, or university server
- ✅ **Vault created** - 6 main folders + 4 project subfolders

---

## Your Next Steps (In Order)

### Step 1: Add Your Course Details (5 minutes)
Edit these files with your information:
- `index.qmd` - Add instructor name, meeting time, office hours
- `syllabus.qmd` - Create your full course syllabus
- `modules/01_orientation/index.qmd` - Add orientation content

### Step 2: Choose a Deployment Option (15 minutes)
Pick ONE:

**🌟 Option 1: GitHub Pages (Easiest)**
- Free hosting, automatic updates
- See DEPLOYMENT.md for full instructions
- Share URL in Blackboard: `https://yourname.github.io/quarto_website`

**Option 2: Netlify**
- Extra features, easy to set up
- See DEPLOYMENT.md for details

**Option 3: University Server**
- Contact your IT department
- Upload the `_site/` folder

### Step 3: Test Student Access (5 minutes)
1. Deploy your site (Step 2)
2. Try downloading Liaison_Vault.zip from the Resources page
3. Test the Setup guide on your own machine
4. Share the link with a test user

### Step 4: Post to Blackboard (2 minutes)
Add course link as an announcement or web link:
```
📚 Course Resources & Materials
Visit the Liaison Program website: [YOUR_DEPLOYED_URL]

Everything you need is here:
✓ Getting started guide
✓ Liaison Obsidian Vault download
✓ Course modules and materials
✓ Resource links and tools
```



| Phase | Status | Completeness | Dev Owner |
|-------|--------|--------------|-----------|
| **Phase 1: Orientation** | ✅ Complete | 100% | Ready for students |
| **Phase 2: Discovery** | 🟡 Partial | 60% | HIGH priority |
| **Phase 3: Dictionary** | ⚠️ Stub | 20% | HIGH priority |
| **Phase 4: Execution** | ⚠️ Stub | 20% | MEDIUM priority |
| **Phase 5: Delivery** | ⚠️ Stub | 20% | MEDIUM priority |

**Status key:** ✅ Production-ready | 🟡 Usable but incomplete | ⚠️ Framework only, needs content

See [CONTENT_PLAN.md](CONTENT_PLAN.md) for what each phase needs.

---

## 👥 Team Handoff

### What You're Inheriting
- ✅ Functional website (already deployed)
- ✅ Pre-built student workspace system
- ✅ Extensive documentation (10+ guides)
- ✅ Clean codebase with comments
- ✅ CI/CD pipeline (GitHub Actions)

### What You're Building Next
- 🔨 Complete course content (Phases 2-5)
- 🎨 Enhanced visual design & branding
- ⚙️ Instructor customization tools
- 🧪 Testing & QA processes
- 📖 Team knowledge transfer

### Key Decisions Already Made
- **Platform:** Quarto (static site) + Obsidian (student vault)
- **Hosting:** GitHub Pages (free, automatic)
- **Styling:** Bootstrap + custom SCSS
- **Content:** Markdown-based, version-controlled
- **Development:** Git workflow with pull requests

### For New Team Members
1. **Read DEVELOPER_GUIDE.md** (15 min) - Get oriented
2. **Clone the repo locally** (5 min) - Set up your workspace
3. **Run `quarto render`** (2 min) - Verify setup works
4. **Review ROADMAP.md** (10 min) - Understand priorities
5. **Join team communication** - Slack, Discord, etc.
6. **Pick a task from ROADMAP** - Start contributing!

---

## 🚦 Getting Started (For Developers)

### Prerequisites
- Git installed
- Quarto 1.3+ installed
- Python 3.8+ installed
- Text editor (VS Code recommended)
- GitHub account with repo access

### Quick Start (5 minutes)

```bash
# 1. Clone
git clone <repo-url>
cd mc451-liaison-program

# 2. Verify Quarto works
quarto --version
python --version

# 3. Build locally
quarto render

# 4. Open in browser
open _site/index.html

# Done! You have the site running locally.
```

### Next Steps
- Read [DEVELOPER_GUIDE.md](DEVELOPER_GUIDE.md) - Full setup & workflows
- Read [GIT_WORKFLOW.md](GIT_WORKFLOW.md) - How to work with the team
- Read [ROADMAP.md](ROADMAP.md) - Pick a task to work on

---

## 📚 Complete Documentation Index

| Document | Purpose | Read If... |
|----------|---------|-----------|
| [DEVELOPER_GUIDE.md](DEVELOPER_GUIDE.md) | Technical setup & architecture | You're a developer joining the team |
| [ARCHITECTURE.md](ARCHITECTURE.md) | Tech stack & design decisions | You want to understand why things are built this way |
| [ROADMAP.md](ROADMAP.md) | Prioritized improvements | You're planning work or assigning tasks |
| [CONTENT_PLAN.md](CONTENT_PLAN.md) | Module completion status | You're writing course content |
| [CUSTOMIZATION_GUIDE.md](CUSTOMIZATION_GUIDE.md) | How to personalize the site | You're an instructor or non-technical user |
| [TESTING_CHECKLIST.md](TESTING_CHECKLIST.md) | QA procedures | You're doing quality assurance |
| [GIT_WORKFLOW.md](GIT_WORKFLOW.md) | Team collaboration & git | You're working with the dev team |
| [DEPLOYMENT.md](DEPLOYMENT.md) | Publishing the site | You're deploying to production |
| [GITHUB_SETUP.md](GITHUB_SETUP.md) | GitHub repository config | You're setting up the repo |
| [LAUNCH_CHECKLIST.md](LAUNCH_CHECKLIST.md) | Pre-launch tasks | It's close to course start date |
| [UX_IMPROVEMENT_PLAN.md](UX_IMPROVEMENT_PLAN.md) | Design specifications | You're working on UI/UX improvements |
| [START_HERE.md](START_HERE.md) | Student onboarding guide | You're a student or need student perspective |
| [QUICK_START.md](QUICK_START.md) | Visual quick reference | You need a quick overview |

---

## 🎯 For Different Roles

### Content Developer
1. Read [CONTENT_PLAN.md](CONTENT_PLAN.md) - See what's needed
2. Read [ROADMAP.md](ROADMAP.md) → Phase 1 section for content guidelines
3. Pick a phase to complete
4. Follow [GIT_WORKFLOW.md](GIT_WORKFLOW.md) to submit changes

### Frontend Developer
1. Read [DEVELOPER_GUIDE.md](DEVELOPER_GUIDE.md)
2. Read [ROADMAP.md](ROADMAP.md) → Phase 2 "Improve Visual Design"
3. Review [ARCHITECTURE.md](ARCHITECTURE.md) for design decisions
4. Start with navigation fixes or color customization

### DevOps / Deployment
1. Read [DEPLOYMENT.md](DEPLOYMENT.md)
2. Check GitHub Actions configuration
3. Verify GitHub Pages settings
4. Consider performance/monitoring improvements

### Project Manager
1. Read [ROADMAP.md](ROADMAP.md) - Full roadmap with priorities
2. Review [CONTENT_PLAN.md](CONTENT_PLAN.md) - Content status
3. Check [LAUNCH_CHECKLIST.md](LAUNCH_CHECKLIST.md) - Pre-launch items
4. Use for sprint planning and status updates

### Instructor (Non-Technical)
1. Read [CUSTOMIZATION_GUIDE.md](CUSTOMIZATION_GUIDE.md) - How to personalize
2. Skip all the technical docs
3. Contact development team for custom requests
- [ ] Create discovery prompts in Module 2
- [ ] Add data dictionary examples in Module 3
- [ ] Include project details in Module 4
- [ ] Create presentation rubric in Module 5

### Advanced (Optional)
- [ ] Add a discussion forum link
- [ ] Create assignment submission guidelines
- [ ] Link to external tools (Zotero, GitHub, etc.)
- [ ] Add lecture slides to each module
- [ ] Create video tutorials

---

## Key Commands

**Build/Update your site:**
```bash
cd C:\mc451-sp26\quarto_website
quarto render
```

**Preview locally before deploying:**
```bash
quarto preview
```

**Deploy to GitHub (after initial setup):**
```bash
git add .
git commit -m "Update course materials"
git push
```

---

## Support & Resources

- **Quarto documentation**: https://quarto.org
- **Obsidian vault help**: https://help.obsidian.md
- **GitHub Pages guide**: https://pages.github.com
- **Netlify deployment**: https://netlify.com

---

## Final Checklist Before Sharing

- [ ] Added your instructor details to home page
- [ ] Created/updated syllabus.qmd
- [ ] Tested Liaison_Vault.zip download works
- [ ] Tested setup guide steps yourself
- [ ] Deployed to GitHub/Netlify/server
- [ ] Tested the deployed URL in a browser
- [ ] Added link to Blackboard
- [ ] Tested as a student (incognito/private browser)

---

## You're All Set! 🚀

Your Liaison Program website is ready to serve your students. Deploy it, share the link, and watch them succeed!

Questions? Refer to DEPLOYMENT.md for detailed instructions on any deployment option.

---

## Textbook Website

For more information, visit the textbook's official website: [Vibes to Variables](https://sim-lab-siue.github.io/vibes-to-variables/)

---

**Built with Quarto + GitHub Copilot** ✨

## License

The course materials in this repository are licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0); see `LICENSE`. The build script `build_vault.py` is released under the MIT License, Copyright (c) 2026 Alex P. Leith.
