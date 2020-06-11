---
title: Design Articles Mind Dump 29 Jan 2020
id: ds-6
---

#### The Kano Model

<https://medium.com/@jmspool/understanding-the-kano-model-a-tool-for-sophisticated-designers-d91d092ad885>

A model conceived by Noriaka Kanom in the 1980s. Kanom was an expert in Customer Satisfaction and Quality Management.

<img src="https://miro.medium.com/max/1000/0*oG75eyU8TMBCjz-c.png" alt="img" caption="Test" style="zoom:50%;" />

*The Kano 2-2 Grid*

<img src="https://miro.medium.com/max/1000/0*pcWjis16G82F3jDb.png" alt="img" style="zoom:50%;" />

*Overlaying a performance payoff trend-line*

<img src="https://miro.medium.com/max/1000/0*XlOzTSnBxeiqbg5C.png" alt="img" style="zoom:50%;" />

*Minimum standards of expectations; doing the job goes unrewarded*

<img src="https://miro.medium.com/max/1000/0*udnQBX3FEBTdfY8n.png" alt="img" style="zoom:50%;" />

*Excitement Generators: Design elements and features that delight the user.*

------

#### Proportional Visual Design

<https://www.lullabot.com/articles/designing-rhythm-and-proportion>

Proportional design is an approach for achieving greater visual consistency within your [design system](https://www.invisionapp.com/inside-design/guide-to-design-systems). The concept allows designers to create a proportional scale which then informs sizing and rhythm decisions for every element that lives on a webpage.

##### The benefits of designing with a proportional system

- Experience a next-level beautiful and professional feel in your design work. Proportion is beauty!
- Within the constraint and focus of a scaled system, I think you’ll find that inspired ideas come more quickly.
- Stop spending time guessing spacing and snap elements into perfect placement the first time you add them to your artboard.
- Developers have less guesswork and are empowered to add undefined future styles to style guides within a mathematical framework.
- Supports consistency for large design systems that can grow over time.
- Creates consistency when multiple designers are working on the same project simultaneously.

##### Process

1. Create a type scale (using [Modular Scale.com](https://modularscale.com) or similar)

2. Setup project artboards and frames for mobile, tablet and desktop in the design tool

3. Define a vertical rhythm unit **(VRU)** size; Lullabot often matches the base font size (e.g. 18px font, 18px VRU)

4. Align horizontal columns with VRU size;

   1. Desktop:

      Lullabot uses the base font size for gutter width, and lets the design tool auto-size based on selected columns (e.g. 12, 9, 8, 6, 4) + an outer margin, again matching the base font size

   2. Tablet:

      Reduce the column number from 12 to 8, keep the same outer grid margins. The design tool will adjust accordingly.

   3. Mobile:

      Reduce from 8 to 6 for mobile, again keeping the same outer margin and column/row gutter matching base font size

5. Decide line-height for type. This could be expressed through VRU units, e.g. 2 VRU for desktop and tablet, 1.5 VRU for mobile

| Example of Type documentation:                               |
| ------------------------------------------------------------ |
| Ratio for type scale: 1.125                                  |
| Desktop, tablet and mobile body size: 18px                   |
| Desktop body line-height: 36px (2 VRU)                       |
| Tablet body line-height: 36px (2 VRU)                        |
| Mobile body line-height: 27 (1.5 VRU)                        |
| VRU size for desktop, tablet and mobile: 18px                |
| Column gutter width for desktop, tablet and mobile: 18px (1 VRU) |
| Row gutter height for desktop, tablet and mobile: 18px (1 VRU) |

### **Final type documentation can be expressed as:**

*font / weight / size / line-height in VRU’s / letter spacing / transform*

Heading A (Page Heading):
Mobile: Tablet Gothic / Bold / ms(1) / 1 VRU
Desktop: Tablet Gothic / Bold / ms(8) / 1.5 VRU’s

Heading B (Content Heading 1):
Mobile: Tablet Gothic / Regular / ms(2) / 1 VRU / -0.3px
Desktop: Tablet Gothic / Regular / ms(6) / 1.5 VRU’s / -0.3px

Heading C (Content Heading 3):
Mobile: Tablet Gothic / Bold / ms(1) / 1 VRU
Desktop: Tablet Gothic / Bold / ms(2) / .75 VRU’s

#### Incremental Leading Typography

<https://markboulton.co.uk/journal/incremental-leading/>

Incremental leading: Side by side text elements having a fractional line-height of the main element.

E.g. blog post with a sidenote; give the sidenote a smaller line-height (and font size) relative to the body text, and then align using incremental leading.

This can be achieved via an incremental ratio of 5:4 towards the body paragraph. That would mean that one in every five lines aligns perfectly, the remaining are slightly unaligned. This produces an overall more cohesive look.

### Form Best Practices: Do's and Don'ts

<https://uxdesign.cc/form-best-practices-8e560e9f8bd0>

1. Stick to a single-column layout

   ![img](https://miro.medium.com/max/4000/1*5h4HyulyhLH5QKV6r1AoSw.png)

2. Use left-aligned text for LtR readers

![img](https://miro.medium.com/max/4000/1*kesshTCttXrdFs4TELap-g.png)

3. Use a form wizard and progress bar for long forms

   <u>Form wizard tips:</u>

   1. Group form fields with sections
   2. Add a save button
   3. Display step-by-step progress

   ![img](https://miro.medium.com/max/4000/1*nnjNceDuyaya1fTs-K1cJQ.png)

4. Group related content with sections, titles and white space

![img](https://miro.medium.com/max/4000/1*LkifDTRY-9GPtZBBAanqdg.png)

5. Decide between a *required* and *optional* field strategy

![img](https://miro.medium.com/max/4000/1*JMN_wg3PdqPhHSJqoYyVpQ.png)

6. User autocomplete/autofill/semantic form inputs!

7. Use relevant input field formats
   1. Radio buttons
   2. Switches
   3. Labels with currency / auto separate $ thousands
   4. Phone numbers
   5. Dates
   6. Advanced search and auto-suggestion for addresses

![img](https://miro.medium.com/max/4000/1*a08DMlc062smtGeC9aPbFA.png)

7. Input field tips
   - The length of the field affords the answer length
   - Validation for email fields
   - Pre-fill and auto-detect whenever possible
   - Min or maximum input length
   - Numeric, alphabetic, alphanumeric, symbols
   - Dependencies
   - Placeholders
8. CTA Design should clearly define the primary and secondary actions; using colour, copy, iconography and layout

![img](https://miro.medium.com/max/4400/1*mJkpu4h1G6QJCvDcNq65Qg.png)

9. CTA Microcopy: Keep the action clear, straightforward and relevant (subscribe vs submit!)

10. Use inline input field validaton

    ![img](https://miro.medium.com/max/4000/1*QBe-OwXS3uYqzIg8UYTAXw.png)

11. JC: Forms are important, and tough! Spend time on them!

------

### UI Cheat Sheet: Text Fields

<https://uxdesign.cc/ui-cheat-sheet-text-fields-2152112615f8>

**So what’s in this cheat sheet:**

- Text field anatomy

<img src="https://miro.medium.com/max/2800/1*Zyk2yx_3Iie9uXlqVW3-yA.png" alt="img" style="zoom: 25%;" />-

- Text field structure

![img](https://miro.medium.com/max/2800/1*J1GvaHUBhYddxEZWTmbcTQ.png)

- Common text field styles

<img src="https://miro.medium.com/max/2800/1*h5L1_Vw6JNoz9m770S5Scg.png" alt="img" style="zoom:67%;" />

- Icons

![img](https://miro.medium.com/max/2800/1*70dkL5dk7EiYJqTFwYsKfA.png)

- Text field states

![img](https://miro.medium.com/max/2800/1*DfIgUR8G84BC9wzdtd4CTg.png)

- Text field labelling & prompt text

![img](https://miro.medium.com/max/2800/1*gcCTcSI8JZ9Sp192pywK5w.png)

- Feedback

![img](https://miro.medium.com/max/2800/1*NxSsFXubxpa0KSfQNL72SA.png)

- Autoformat

![img](https://miro.medium.com/max/1568/1*AFvCKjB9i72hv8R24Pu56g.gif)

- Touch targets

Tough targets should be 48 x 48px per Material and HIG

- Accessibility checklist
  - Colour contrast
  - Text fields and label size
  - Label always visible
  - Inline validation
- Text field hall of fame

![img](https://miro.medium.com/max/1216/1*CyGDsrq0xvsWTI3nYaPy3Q.gif)

------

### 10 Bites of UX Wisdom (via @uxbites)

<https://blog.maze.design/things-ux-designer-should-know/?ref=heydesigner>

1. Ask as many questions as possible

2. Don't build on assumptions

3. Test and validate your ideas

4. Design with people's mental models in mind

5. What peoples say and what they do can be totally different

6. Don't think in features, think in user needs

7. Be open-minded, listen and empathise

8. Understand business requirements as much as users

9. Embrace the technical side to understand how products are build

10. Be a team player

    ------

### Critique at Figma

<https://www.figma.com/blog/design-critiques-at-figma/>

After realising some problems with their current approach, the Figma team documented six different critique methods they would use, each intended to take 20-30 mins (2 reviews per 1 hour meeting)

![Standard Critique. What: Typical “present and critique” format. Why: Looking for something slightly formal, and exhaustive. Jam /  Workshop. What: Brainstorms, Crazy 8’s, Affininity Diagrams, Group sketching, etc. Why: Best for the way beginning of the design process— or if you’re stuck and want to see something in new ways. Pair Design. What: Pair up in smaller groups of 2-3 rather than a big group. Why: You need deeper collaboration on a problem — flexible and hands-on. Silent Critique. What: Everyone stays silent and reviews a document and adds feedback digitally. Why: Need a mass volume of feedback, to keep people focused, or you want feedback async / remotely. Paper Print-Out. What: Print out work and pin them up on walls or foam core. Stand or crowd around them. Why: Invite broader team collaboration. Keep an open and creative feeling, where you can see more at once. FYI. What: Give a quick heads up on a project while people are together, can chat later/async. Why: You’re not ready for discussion, but want people to know what’s going on early.](https://images.ctfassets.net/1khq4uysbvty/1SfI3XJSNz2tiv24PJ3mxU/10d9441408f6ee53ece4567c78cb3b5a/3._CritiqueToolbelt.png?w=736)

------

### Responsive Grids and How to Use Them

<https://uxdesign.cc/responsive-grids-and-how-to-actually-use-them-970de4c16e01>

Full bleed elements or graphics should go edge to edge of the artboard, often called bleeding out the columns

<img src="https://miro.medium.com/max/2516/1*_-1qozzDnDpE3jp4DCPbkw.png" alt="img" style="zoom:50%;" />



------

### UI Terms Glossary

<https://uxdesign.cc/cheat-sheets-ui-terms-cadf9dc49689>

A glossary of Material, HIG and Microsoft UI terms

------

### The New Double Design Process

<https://medium.com/design-leadership-notebook/the-new-double-diamond-design-process-7c8f12d7945e>

![img](https://miro.medium.com/max/1590/0*pGwdqYYkQgeJ09G0)

In the new model, under “design principles”, they added the main other mental models that are a good help in innovation projects:

1. User Centered Design: “be people centered”
2. Visual Thinking: “communicate visually”
3. Co-creation: “collaborate and co-create”
4. Agile / Lean Startup: “iterate, iterate, iterate”

**Source:** <https://www.designcouncil.org.uk/news-opinion/what-framework-innovation-design-councils-evolved-double-diamond>

------

#### IBM Carbon Design System

<https://www.carbondesignsystem.com/guidelines/2x-grid/basics/?ref=heydesigner#2x-grid-fundamentals>

Interesting explanation of using a 2x grid *repeated* to create visual rhythm.

------

### Space, Grids and Layout

<https://www.designsystems.com/space-grids-and-layouts/>

![14 adaptive](https://images.ctfassets.net/7jw9uvgmirvi/2K52M7zFYb9q2fw2laNq6g/42c93ceb26841b2ff2992f277298d102/14_adaptive.png)

***Responsive***

![15 responsive](https://images.ctfassets.net/7jw9uvgmirvi/5d4yH1xwhPtmOOoWwBlKMs/ef866c7bf3fc649898f2b34a2b9e7fc4/15_responsive.png)

***Fluid***

![16 Strict](https://images.ctfassets.net/7jw9uvgmirvi/4xJy6y0PUKJ63ip7ZZElbO/b83b879448f44096a904eefaa275c016/16_Strict.png)

***Strict***

------

### 5 Rules for Writing Great UX Copy (via GV)

<https://www.fastcompany.com/3026463/from-google-ventures-5-rules-for-writing-great-interface-copy>

1. Clarity is champion

2. Personality doesn't matter as much as you think

3. Just tell me

4. By the way, people do read

5. Writing is part of the design process

------

### Principles of User Interface Design

<http://bokardo.com/principles-of-user-interface-design/>

1. Clarity is job #1
2. Interfaces exist to enable interaction
3. Conserve attention at all costs
4. Keep users in control
5. Direct manipulation is best
6. One primary action per screen
7. Keep secondary actions secondary
8. Provide a natural next step
9. Appearance follows behaviour
10. Consistency matters
11. Strong visual hierarchies work best
12. Smart organisation reduces cognitive load
13. Highlight, don't determine, with colour (e.g. used as an extension to guide attention, not the sole differentiator)
14. Progressive disclosure
15. Help people inline
16. Empty states are a crucial moment: design for them
17. Great design gets out of the way
18. Build on other design disciplines (Visual and graphic design, typography, copywriting, information architecture and visualisation)
19. Interfaces exist to be used

------

### Principles of Product Design

<http://bokardo.com/principles-of-product-design/>

1. Usefulness is job #1
2. The experience *is* the product
3. Solve existing problems
4. Look for problems people are already investing energy into solving
5. Model features on real, existing artefacts
6. Fit and finish matter
7. Release quality sets expectations
8. Release a smaller, better product
9. The last 10% is the hardest
10. Know who you real competitors are
11. Understand people's actual vs. desired use-cases
12. Personal value precedes social value
13. Users are not product designers
14. The behaviour you're seeing is the behaviour you designed into the product, even if unexpectedly
15. Disruptive products look like toys, at first, sometimes
16. Positioning is crucial
17. Product/market fit is when people sell for you

------

### Formative vs. Summative research

Quick and dirty versus slow and rigorous usability research.

<https://uxdesign.cc/formative-vs-summative-usability-research-3dd2317b8b75>

*“First, formative and summative evaluations are both a form of **evaluative usability research.** They are each conducted to understand how a product performs compared to benchmarks in the products history. Unlike summative, formative is also considered to be an exploratory research method, whereby it is used to gain insight into the subject the product deals with and helps in problem identification and solving. Regardless if the research is formative or summative, the goal is to identify and resolve usability issues in order to improve a product’s design.”*

##### Formative Research Process

In general, **formative usability evaluation** is done to find and fix problems with an existing product in order to make it more usable. It is done early with simulations and early working prototypes of designs and explores whether usability objectives are obtainable or not.

**Steps of Process**

1. Statement of evaluation purpose
2. Description of interface to be evaluated
3. Use case scenarios and tasks involved in the testing process
4. Evaluation of the end users — how many groups are there?
5. Data collection and data analysis methods to be used
6. Explanation of how results will be used to trigger design modifications that will mitigate hazards

##### Summative Research

**Summative usability evaluation** is done to understand what is usable about a design after it is complete, or, what is working. It is done when a design is finished (i.e. ready to be released to the public/safe for the public) in order to test that it performs better than a previously released product (or competitive product). Summative evaluations are done for verification and validation that it is safe to release to the public. It is recommended best practice to have formal acceptance criteria (e.g., usability objectives for human performance and user satisfaction rates).

**Steps of Summative Research process (Handbook of Human Factors in Medical Device Design)**

1. Develop a usability task list (tasks that the product must satisfy)
2. Determine methods, equipment, materials, procedures and measurements necessary for the evaluation
3. Definition of user groups and recruitment for each (15–20 users/group)
4. Definition of acceptance criteria. For example, eighty percent of all participants will give the device a rating of 5 or higher (on a 7-point scale) with respect to their overall satisfaction with the device.
5. Conduct the validation test using a real (not prototype or simulation) market-ready product
6. Analyze data qualitatively by aggregating objective and subjective data to identify potential use errors and determine root causes
7. Explanation of how results will be used to trigger design modifications that will mitigate hazards
8. Address use errors through risk management strategies
9. Conduct human factors (re)validation testing (until no new errors are introduced)
10. Document Human Factors Engineering/Usability Engineering process

------

### Ueno Design Process

<https://loremipsum.ueno.co/dear-ueno-whats-your-design-process-ee28e8e3dbfc>

1. Immersion in the brief
2. Strategy (an articulated view of why the project exists)
3. Foundational research report
4. Concept exploration
   1. User story vignettes / storyboards (product)
   2. Moodboards (brand)
5. Testing
   1. Usability studies (product)
   2. Future proofing (brand)
6. Creating he system
   1. Information architecture (product & marketing)
   2. User flows (product)
7. Documentation and delivery
   1. A well annotated design system
   2. Training in how to use the design system, brand and other resources

------

### Ueno UX Tips & Tricks

<https://loremipsum.ueno.co/dear-ueno-do-you-have-any-ux-tips-and-tricks-66879f9662a6>

Tip #1: Read the brief, and keep it for later.

Tip #2: Take lots and lots of notes at the kick-off meeting.

Tip #3: Nail down who the users are and what they want.

Tip #4: Don’t think about two things at a time.

Tip #5: Don’t wait until you’ve got a perfect sitemap before you move on to wireframes.

Tip #6: Use Blokk for wireframe copy that you don't have it. It represents sentences with text blocks — perfect for placeholder content.
