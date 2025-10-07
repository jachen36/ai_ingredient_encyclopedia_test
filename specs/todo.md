# Project Plan: Ingredient Reference Guide Generation

## Overview
This plan outlines the step-by-step process to create a comprehensive ingredient reference guide using the ingredient_template.md. Each task builds upon previous tasks to ensure a logical, complete workflow.

---

## Task Breakdown

### Phase 1: Project Setup & Research

#### Task 1.0: Initialize Project
- [ ] **1.0.1** Create project folder structure: `000 Project Management/workflow/ai_output/`
- [ ] **1.0.2** Select the target ingredient to document
- [ ] **1.0.3** Check for existing versions in `ai_output/` folder, determine next version number (v1, v2, v3, etc.), and create the output file: `[ingredient_name]_v#.md`
- [ ] **1.0.4** Duplicate the todo.md file to create ingredient-specific working checklist: `[ingredient_name]_v#_todo.md` in the same folder as the output file. Use this duplicated file as your working checklist for all subsequent "Update todo checklist" tasks.
- [ ] **1.0.5** Copy the ingredient_template.md structure into the new ingredient file
- **Dependencies:** None
- **Context:** This establishes the foundation. Choose a single ingredient (e.g., "tomatoes", "chickpeas", "ginger"). Check the output folder for files like `tomatoes_v1.md` - if it exists, create `tomatoes_v2.md`. If no versions exist, start with v1. The duplicated todo file serves as your working checklist.

#### Task 1.1: Conduct Preliminary Research
- [ ] **1.1.1** Research alternate names and regional variations of the ingredient
- [ ] **1.1.2** Gather information about the ingredient's basic characteristics (appearance, texture, smell)
- [ ] **1.1.3** Document common uses and culinary applications
- [ ] **1.1.4** Identify reputable sources (culinary websites, agricultural guides, food science resources)
- [ ] **1.1.5** Create research notes section at bottom of ingredient file: add "---" separator and "# Hidden" header, then document all findings
- [ ] **1.1.6** Update todo checklist by marking Task 1.1 as complete
- **Dependencies:** 1.0.5
- **Context:** Gather foundational knowledge before writing. Focus on 5-7 reliable sources. Research notes go in Hidden section at bottom of ingredient file - this keeps everything in one place but separate from reader content.

---

### Phase 2: Quick Reference Section

#### Task 2.0: Draft Quick Reference Table
- [ ] **2.0.1** List all synonymous names for the ingredient (or mark N/A)
- [ ] **2.0.2** Write a 1-2 sentence taste profile description
- [ ] **2.0.3** Document 2-4 key visual/quality indicators for buying
- [ ] **2.0.4** Specify primary storage method with duration (e.g., "Refrigerate in crisper, 5-7 days")
- [ ] **2.0.5** List extended storage options (freezing, drying, canning, or N/A)
- [ ] **2.0.6** Specify which parts are edible vs. discarded
- [ ] **2.0.7** Write 2-3 essential prep steps (washing, peeling, cutting)
- [ ] **2.0.8** List 3-5 spoilage indicators (visual, smell, texture)
- [ ] **2.0.9** Update todo checklist by marking Task 2.0 as complete
- **Dependencies:** 1.1.6
- **Context:** This is the most frequently referenced section. Keep each entry concise (under 10 words where possible). This serves as a cheat sheet for daily use.

#### Task 2.1: Source Quick Reference Image
- [ ] **2.1.1** Find a high-quality representative image of the ingredient from a reliable source (Unsplash, Pexels, Wikimedia Commons, or culinary websites)
- [ ] **2.1.2** Ensure image shows the ingredient in typical purchased state
- [ ] **2.1.3** Copy the image URL and test it in a browser to confirm it loads and analyze each image to confirm image is related ingredient to be documented
- [ ] **2.1.4** Add image using markdown format: `![Ingredient name in typical form](image_url)`
- [ ] **2.1.5** Verify the URL works and image displays correctly in markdown preview
- [ ] **2.1.6** If any images fail verification in 2.1.5, return to 2.1.1 to find replacement images
- [ ] **2.1.7** Update todo checklist by marking Task 2.1 as complete only when all images are verified working
- **Dependencies:** 2.0.9
- **Context:** Use royalty-free image sources. The image should be clear, well-lit, and show what readers will see at the market. Always test URLs before adding to document.

---

### Phase 3: Buying Guide Section

#### Task 3.0: Determine Optional Subsections
- [ ] **3.0.1** Decide if "Synonymous" subsection is needed (if >3 alternate names exist)
- [ ] **3.0.2** Decide if "Confusing Names" subsection is needed (if commonly mistaken for other ingredients)
- [ ] **3.0.3** Decide if "Other Names" subsection is needed (if regional variations exist)
- [ ] **3.0.4** Decide if "Substitutions" subsection is needed (if common alternatives exist)
- [ ] **3.0.5** Draft content for each selected subsection (2-3 sentences each)
- [ ] **3.0.6** Update todo checklist by marking Task 3.0 as complete
- **Dependencies:** 2.1.6
- **Context:** Only include subsections that add value. For simple ingredients like rice, you may skip all of these. For complex ingredients like cilantro/coriander, include them.

#### Task 3.1: Complete "What to Look At" Table - Safety
- [ ] **3.1.1** Identify 2-4 safety indicators (mold, bruising, damage, recalls)
- [ ] **3.1.2** Write clear descriptions of what to look for
- [ ] **3.1.3** Explain why each indicator matters for food safety (e.g., bacterial growth, toxins)
- [ ] **3.1.4** Format as bullet points under "Safety" row
- [ ] **3.1.5** Update todo checklist by marking Task 3.1 as complete
- **Dependencies:** 3.0.6
- **Context:** Safety comes first. Focus on indicators that could cause illness or contamination. Be specific: "Avoid produce with dark spots or soft patches that may harbor bacteria."

#### Task 3.2: Complete "What to Look At" Table - Freshness
- [ ] **3.2.1** Identify 3-5 freshness indicators (color, firmness, stem condition, moisture)
- [ ] **3.2.2** Write clear descriptions of optimal freshness signs
- [ ] **3.2.3** Explain how freshness affects shelf life and nutritional value
- [ ] **3.2.4** Format as bullet points under "Freshness" row
- [ ] **3.2.5** Update todo checklist by marking Task 3.2 as complete
- **Dependencies:** 3.1.5
- **Context:** Help readers identify peak freshness. Example: "Stems should be bright green and crisp, not wilted or yellowed, indicating recent harvest."

#### Task 3.3: Complete "What to Look At" Table - Taste
- [ ] **3.3.1** Identify 2-4 taste-related selection criteria (ripeness, variety, size)
- [ ] **3.3.2** Explain how each factor affects flavor and texture
- [ ] **3.3.3** Include tips for selecting based on intended use (immediate vs. later use)
- [ ] **3.3.4** Format as bullet points under "Taste" row
- [ ] **3.3.5** Update todo checklist by marking Task 3.3 as complete
- **Dependencies:** 3.2.5
- **Context:** Connect visual cues to flavor outcomes. Example: "Smaller specimens tend to be sweeter and more tender than larger ones."

#### Task 3.4: Complete "What to Look At" Table - Practical
- [ ] **3.4.1** Identify 2-3 practical considerations (ease of peeling, seedlessness, portion size)
- [ ] **3.4.2** Explain how these factors affect kitchen convenience
- [ ] **3.4.3** Note any time-saving characteristics
- [ ] **3.4.4** Format as bullet points under "Practical" row
- [ ] **3.4.5** Update todo checklist by marking Task 3.4 as complete
- **Dependencies:** 3.3.5
- **Context:** Focus on user experience. Example: "Pre-washed packages save prep time but may have shorter shelf life."

#### Task 3.5: Complete "What to Look At" Table - Aesthetic
- [ ] **3.5.1** Identify 1-3 aesthetic factors (uniformity, color vibrancy, presentation)
- [ ] **3.5.2** Note when aesthetics matter (serving guests vs. cooking down)
- [ ] **3.5.3** Explain any trade-offs (perfect appearance may cost more)
- [ ] **3.5.4** Format as bullet points under "Aesthetic" row
- [ ] **3.5.5** Update todo checklist by marking Task 3.5 as complete
- **Dependencies:** 3.4.5
- **Context:** This is the least critical category. Keep it brief. Example: "Uniform size makes for better presentation in salads."

#### Task 3.6: Add Buying Guide Images
- [ ] **3.6.1** Determine if visual aids would help (comparison images, quality indicators, ripeness stages)
- [ ] **3.6.2** Find 1-3 supporting images from royalty-free sources that show good vs. bad examples or quality comparisons
- [ ] **3.6.3** Test each image URL in browser to confirm it loads and analyze each image to confirm image is the ingredient to be documented
- [ ] **3.6.4** Add images using markdown format: `![Descriptive caption](image_url)` below the relevant content
- [ ] **3.6.5** Verify all URLs work and images display correctly in markdown preview
- [ ] **3.6.6** If any images fail verification in 3.6.5, return to 3.6.2 to find replacement images
- [ ] **3.6.7** Update todo checklist by marking Task 3.6 as complete only when all images are verified working
- **Dependencies:** 3.5.5
- **Context:** Use images to show good vs. bad examples, ripeness stages, or confusing varieties. Only add if they clarify the text. Always test URLs before adding.

---

### Phase 4: Anatomy Section (Conditional)

#### Task 4.0: Determine if Anatomy Section is Needed
- [ ] **4.0.1** Assess if ingredient has distinct parts with different uses (e.g., broccoli: florets, stems; chicken: breast, thighs, wings)
- [ ] **4.0.2** If YES, proceed to Task 4.1; if NO, skip to Task 5.0
- [ ] **4.0.3** Document decision rationale in Hidden section
- [ ] **4.0.4** Update todo checklist by marking Task 4.0 as complete
- **Dependencies:** 3.6.6
- **Context:** Simple ingredients (rice, canned beans, flour) should skip this section. Complex ingredients (whole vegetables, proteins, herbs with stems/leaves) need it.

#### Task 4.1: Create Anatomy Table
- [ ] **4.1.1** List all distinct parts (typically 2-5 parts)
- [ ] **4.1.2** Write 1-2 sentence description for each part's physical characteristics
- [ ] **4.1.3** Explain culinary relevance (how each part cooks differently, when to use each)
- [ ] **4.1.4** Note which parts are often wasted but are actually usable
- [ ] **4.1.5** Format as table with Part, Description, Kitchen Relevance columns
- [ ] **4.1.6** Update todo checklist by marking Task 4.1 as complete
- **Dependencies:** 4.0.4
- **Context:** Help readers maximize the ingredient. Example for broccoli: "Stems: Fibrous outer layer with tender interior | Peel outer layer, slice thin for stir-fries or roasting."

#### Task 4.2: Add Anatomy Images
- [ ] **4.2.1** Find a labeled diagram or clear image showing all parts from royalty-free sources
- [ ] **4.2.2** Ensure image clearly shows the parts mentioned in the table
- [ ] **4.2.3** Test image URL in browser to confirm it loads and analyze each image to confirm image is the ingredient to be documented
- [ ] **4.2.4** Add image using markdown format: `![Anatomy of [ingredient] showing [parts]](image_url)` with clear caption
- [ ] **4.2.5** Verify URL works and image displays correctly in markdown preview
- [ ] **4.2.6** If any images fail verification in 4.2.5, return to 4.2.1 to find replacement images
- [ ] **4.2.7** Update todo checklist by marking Task 4.2 as complete only when all images are verified working
- **Dependencies:** 4.1.6
- **Context:** A single annotated image is often sufficient. The image should show where to cut, what to remove, what to keep. Always test URLs before adding.

---

### Phase 5: Storing Section

#### Task 5.0: Assess Storing Complexity
- [ ] **5.0.1** Count the number of viable storage methods (room temp, refrigerated, frozen, dried, pickled, etc.)
- [ ] **5.0.2** If 1-2 methods, plan simple paragraph format (Task 5.1)
- [ ] **5.0.3** If 3+ methods, plan complex table format (Task 5.2)
- [ ] **5.0.4** Document storage method list in Hidden section
- [ ] **5.0.5** Update todo checklist by marking Task 5.0 as complete
- **Dependencies:** 4.2.6 (or 4.0.4 if Anatomy skipped)
- **Context:** Simple ingredients need simple instructions. Complex ingredients with multiple storage options need organized tables for clarity.

#### Task 5.1: Write Simple Storage Format (if applicable)
- [ ] **5.1.1** Write 2-4 sentence paragraph covering primary storage method
- [ ] **5.1.2** Include container type, location, and duration
- [ ] **5.1.3** Add one alternative method if it exists (e.g., freezing)
- [ ] **5.1.4** Note any special conditions (away from sunlight, in airtight container)
- [ ] **5.1.5** Update todo checklist by marking Task 5.1 as complete
- [ ] **5.1.6** Skip to Task 6.0 when complete
- **Dependencies:** 5.0.5
- **Context:** Example: "Store in airtight container in pantry for up to 1 year. For longer storage, refrigerate or freeze in sealed bags for up to 2 years."

#### Task 5.2: Create Complex Storage Table (if applicable)
- [ ] **5.2.1** Create table with columns: Stage, Method, How Long It Lasts, Signs It's Gone Bad
- [ ] **5.2.2** Fill in Room Temperature row (if applicable)
- [ ] **5.2.3** Fill in Refrigerated row (if applicable)
- [ ] **5.2.4** Fill in Freezing row (if applicable)
- [ ] **5.2.5** Fill in additional method rows (drying, canning, pickling, etc.)
- [ ] **5.2.6** Ensure duration is specific (e.g., "3-5 days" not "several days")
- [ ] **5.2.7** Update todo checklist by marking Task 5.2 as complete
- **Dependencies:** 5.0.5
- **Context:** Each row should be scannable. Keep method descriptions brief in table. Example: "Refrigerate in crisper drawer in perforated bag | 5-7 days | Wilting, sliminess, off odor."

#### Task 5.3: Write Expanded Storage Explanations (if complex format used)
- [ ] **5.3.1** Write 2-4 sentences for each storage method below the table
- [ ] **5.3.2** Include specific tips (optimal temperature, humidity, container types)
- [ ] **5.3.3** Add troubleshooting advice (common mistakes, how to prevent spoilage)
- [ ] **5.3.4** Note any preparation needed before storage (blanching before freezing, etc.)
- [ ] **5.3.5** Update todo checklist by marking Task 5.3 as complete
- **Dependencies:** 5.2.7
- **Context:** This is where detail lives. Explain the "why" behind storage methods. Example: "Freezing: Blanch for 2-3 minutes first to preserve color and texture. Cool completely before freezing in single layer on tray, then transfer to bags to prevent clumping."

---

### Phase 6: Preparing Section

#### Task 6.0: Assess Preparation Complexity
- [ ] **6.0.1** List all preparation steps required (washing, peeling, cutting, soaking, etc.)
- [ ] **6.0.2** Count preparation methods (raw, blanched, roasted, etc.)
- [ ] **6.0.3** If minimal prep (1-2 steps, 1 method), plan simple format (Task 6.1)
- [ ] **6.0.4** If complex prep (3+ steps, 2+ methods), plan complex format (Task 6.2)
- [ ] **6.0.5** Update todo checklist by marking Task 6.0 as complete
- **Dependencies:** 5.1.6 or 5.3.5
- **Context:** Simple ingredients like canned beans need minimal prep instructions. Complex ingredients like whole artichokes need detailed, numbered steps.

#### Task 6.1: Write Simple Preparation Format (if applicable)
- [ ] **6.1.1** Write 1-3 sentence paragraph covering basic prep
- [ ] **6.1.2** Include washing/cleaning instructions
- [ ] **6.1.3** Note if no special prep is needed
- [ ] **6.1.4** Update todo checklist by marking Task 6.1 as complete
- [ ] **6.1.5** Skip to Task 7.0 when complete
- **Dependencies:** 6.0.5
- **Context:** Example: "Rinse under cold water, sort to remove debris or damaged pieces. No peeling or special prep needed. Use directly in recipes."

#### Task 6.2: Write Numbered Prep Steps (if complex format needed)
- [ ] **6.2.1** Break preparation into 3-8 numbered steps
- [ ] **6.2.2** Start with initial cleaning/washing steps
- [ ] **6.2.3** Progress through cutting/peeling/trimming steps
- [ ] **6.2.4** End with final prep before cooking
- [ ] **6.2.5** Keep each step to 1-2 sentences
- [ ] **6.2.6** Use clear action verbs (rinse, peel, slice, remove, pat dry)
- [ ] **6.2.7** Update todo checklist by marking Task 6.2 as complete
- **Dependencies:** 6.0.5
- **Context:** Walk through the process chronologically. Example: "1. Rinse thoroughly under cold water. 2. Pat dry with clean towel. 3. Trim stem end, leaving 1 inch intact..."

#### Task 6.3: Create Preparation Methods Table (if complex format needed)
- [ ] **6.3.1** Create table with columns: Method, Best Use, How to / Tricks
- [ ] **6.3.2** Add row for each preparation method (raw, blanched, roasted, grilled, etc.)
- [ ] **6.3.3** Specify when each method is optimal
- [ ] **6.3.4** Provide brief technique details for each method
- [ ] **6.3.5** Include timing and temperature where relevant
- [ ] **6.3.6** Update todo checklist by marking Task 6.3 as complete
- **Dependencies:** 6.2.7
- **Context:** Help readers choose the right method. Example: "Blanching | For freezing or salads | Boil 2-3 min, shock in ice bath to stop cooking and preserve color."

#### Task 6.4: Add Preparation Images (if complex format needed)
- [ ] **6.4.1** Identify steps that benefit from visual demonstration (knife techniques, trimming, etc.)
- [ ] **6.4.2** Find 1-3 process images from royalty-free sources showing key techniques
- [ ] **6.4.3** Test each image URL in browser to confirm it loads and analyze each image to confirm image is the ingredient to be documented
- [ ] **6.4.4** Place images near relevant steps using markdown format: `![Descriptive technique caption](image_url)`
- [ ] **6.4.5** Verify all URLs work and images display correctly in markdown preview
- [ ] **6.4.6** If any images fail verification in 6.4.5, return to 6.4.2 to find replacement images
- [ ] **6.4.7** Update todo checklist by marking Task 6.4 as complete only when all images are verified working
- **Dependencies:** 6.3.6
- **Context:** Show knife techniques, proper trimming, or "before and after" comparisons. Images should clarify, not decorate. Always test URLs before adding.

#### Task 6.5: Add Tricks Subsection (if applicable)
- [ ] **6.5.1** List 3-5 practical tips that make prep easier or better
- [ ] **6.5.2** Include time-saving tricks
- [ ] **6.5.3** Note common mistakes to avoid
- [ ] **6.5.4** Add any professional chef techniques
- [ ] **6.5.5** Format as bulleted list
- [ ] **6.5.6** Update todo checklist by marking Task 6.5 as complete
- **Dependencies:** 6.4.6 or 6.3.6 (if no images)
- **Context:** This is for "insider knowledge." Example: "Use the back of a spoon to easily peel ginger instead of a peeler—it follows the contours better and wastes less."

---

### Phase 7: Waste Not / Bulk Usage Section

#### Task 7.0: Add Spoilage Warning and Storage Cross-Reference
- [ ] **7.0.1** Write the safety disclaimer: "Play it safe and throw it away if you question it"
- [ ] **7.0.2** Add sentence referring readers back to Storing section for preservation options
- [ ] **7.0.3** Update todo checklist by marking Task 7.0 as complete
- **Dependencies:** 6.5.6 or 6.1.5 (if simple prep format used)
- **Context:** Always prioritize food safety. This is a brief intro before the bulk usage ideas.

#### Task 7.1: Compile Recipes & Usage Ideas
- [ ] **7.1.1** Brainstorm 8-12 ways to use excess ingredient
- [ ] **7.1.2** Include quick everyday recipes (smoothies, stir-fries, salads)
- [ ] **7.1.3** Include bulk processing ideas (sauces, purees, stocks)
- [ ] **7.1.4** Include preservation methods (freezing prep, drying, fermenting, pickling)
- [ ] **7.1.5** Add creative/unexpected uses
- [ ] **7.1.6** Write 1 sentence description for each idea
- [ ] **7.1.7** Format as bulleted list with bold idea name + description
- [ ] **7.1.8** Update todo checklist by marking Task 7.1 as complete
- **Dependencies:** 7.0.3
- **Context:** Focus on practical, achievable ideas. Example: "**Herb butter:** Blend with softened butter, roll into log, freeze in portions for easy flavoring of dishes."

---

### Phase 8: Details Section

#### Task 8.0: Identify Topics for Details Section
- [ ] **8.0.1** Review all previous sections for topics that need deeper explanation
- [ ] **8.0.2** List 2-5 topics that deserve expanded coverage (nutrition, varieties, cooking science, history, common issues)
- [ ] **8.0.3** Prioritize topics based on reader value
- [ ] **8.0.4** Create subsection structure in Hidden section for planning
- [ ] **8.0.5** Update todo checklist by marking Task 8.0 as complete
- **Dependencies:** 7.1.8
- **Context:** This is where nuance lives. Topics might include: "Understanding Ripeness Stages," "Nutritional Benefits," "Different Varieties Explained," "Cooking Science: Why It Behaves That Way."

#### Task 8.1: Write First Details Subsection
- [ ] **8.1.1** Choose the highest-priority topic from Task 8.0.2
- [ ] **8.1.2** Write 2-5 paragraphs of in-depth content
- [ ] **8.1.3** Include comparisons, explanations, or techniques
- [ ] **8.1.4** Find supporting images if helpful from royalty-free sources
- [ ] **8.1.5** Test any image URLs in browser to confirm functionality
- [ ] **8.1.6** Add images using markdown format: `![Descriptive caption](image_url)` 
- [ ] **8.1.7** Use clear headers and formatting
- [ ] **8.1.8** Verify image URLs work and display correctly in markdown preview
- [ ] **8.1.9** Update todo checklist by marking Task 8.1 as complete
- **Dependencies:** 8.0.5
- **Context:** Go deeper than other sections. Example topic: "Understanding Heirloom vs. Hybrid Varieties" with paragraphs explaining differences in taste, appearance, growing conditions, and best uses.

#### Task 8.2: Write Additional Details Subsections
- [ ] **8.2.1** Write second subsection (2-5 paragraphs)
- [ ] **8.2.2** Write third subsection if applicable (2-5 paragraphs)
- [ ] **8.2.3** Write fourth subsection if applicable (2-5 paragraphs)
- [ ] **8.2.4** Ensure each subsection has clear header
- [ ] **8.2.5** Add images, tables, or diagrams as needed using markdown format with external URLs
- [ ] **8.2.6** Test any image URLs in browser to confirm functionality
- [ ] **8.2.7** Verify all image URLs work and display correctly in markdown preview
- [ ] **8.2.8** Update todo checklist by marking Task 8.2 as complete
- **Dependencies:** 8.1.9
- **Context:** Maintain consistent depth across subsections. Each should provide actionable insights or interesting knowledge that enhances the reader's understanding.

#### Task 8.3: Create FAQ Subsection
- [ ] **8.3.1** Compile 5-10 frequently asked questions about the ingredient
- [ ] **8.3.2** Include questions not fully answered in other sections
- [ ] **8.3.3** Write clear, concise answers (2-4 sentences each)
- [ ] **8.3.4** Format as bulleted list with bold question + answer
- [ ] **8.3.5** Order questions logically (basic to advanced, or by topic grouping)
- [ ] **8.3.6** Update todo checklist by marking Task 8.3 as complete
- **Dependencies:** 8.2.8
- **Context:** Answer real user queries. Examples: "Can I eat the skin?" "Why does mine taste bitter?" "Is it safe to eat raw?" "Can I substitute X for Y?"

---

### Phase 9: Review & Finalization

#### Task 9.0: Content Review and Consistency Check
- [ ] **9.0.1** Read through entire document for flow and coherence
- [ ] **9.0.2** Verify all template sections are addressed (or marked N/A)
- [ ] **9.0.3** Check that terminology is consistent throughout
- [ ] **9.0.4** Ensure measurements and durations are specific and consistent
- [ ] **9.0.5** Verify all internal cross-references work
- [ ] **9.0.6** Update todo checklist by marking Task 9.0 as complete
- **Dependencies:** 8.3.6
- **Context:** Read as if you're the end user. Does it make sense? Are instructions clear? Is anything contradictory or confusing?

#### Task 9.1: Formatting and Structure Check
- [ ] **9.1.1** Verify all markdown formatting is correct (headers, tables, lists, bold/italic)
- [ ] **9.1.2** Check that all tables are properly aligned
- [ ] **9.1.3** Ensure consistent spacing between sections
- [ ] **9.1.4** Verify all image markdown syntax is correct: `![Alt text](url)`
- [ ] **9.1.5** Check that all bullet points and numbered lists render correctly
- [ ] **9.1.6** Update todo checklist by marking Task 9.1 as complete
- **Dependencies:** 9.0.6
- **Context:** Use VS Code's markdown preview to verify formatting. Tables should align, bullets should indent properly, headers should create proper hierarchy, and all images should display.

#### Task 9.2: External Links Verification
- [ ] **9.2.1** Test all image URLs individually in browser to ensure they load correctly
- [ ] **9.2.2** Verify images are high-quality and relevant to content
- [ ] **9.2.3** Check that alt text is descriptive and accessible for all images
- [ ] **9.2.4** Ensure no broken image links exist
- [ ] **9.2.5** Replace any broken URLs with working alternatives if needed
- [ ] **9.2.6** Test all links in markdown preview to confirm they display properly
- [ ] **9.2.7** Update todo checklist by marking Task 9.2 as complete
- **Dependencies:** 9.1.6
- **Context:** Click through each image URL in a browser to confirm it works. Images should load quickly and be from reliable sources (Unsplash, Pexels, Wikimedia Commons). Poor quality or broken images undermine credibility.

#### Task 9.3: Fact-Checking and Accuracy Review
- [ ] **9.3.1** Verify storage durations against reliable sources
- [ ] **9.3.2** Check that cooking times and temperatures are accurate
- [ ] **9.3.3** Confirm food safety information is current and correct
- [ ] **9.3.4** Validate any nutritional claims or health statements
- [ ] **9.3.5** Ensure substitution suggestions are appropriate
- [ ] **9.3.6** Update todo checklist by marking Task 9.3 as complete
- **Dependencies:** 9.2.7
- **Context:** Food safety is critical. Cross-reference with USDA guidelines, culinary institutes, or reputable food science sources. When in doubt, add a disclaimer.

#### Task 9.4: Completeness and Usability Check
- [ ] **9.4.1** Verify the Quick Reference table is complete and useful
- [ ] **9.4.2** Ensure Buying Guide provides actionable advice
- [ ] **9.4.3** Check that Storing section covers all common scenarios
- [ ] **9.4.4** Verify Preparing section is clear for beginners
- [ ] **9.4.5** Confirm Waste Not section provides practical ideas
- [ ] **9.4.6** Ensure Details section adds meaningful value
- [ ] **9.4.7** Update todo checklist by marking Task 9.4 as complete
- **Dependencies:** 9.3.6
- **Context:** Put yourself in the reader's shoes at different skill levels. Can a beginner follow this? Does an experienced cook find new insights?

#### Task 9.5: Final Polish and Publication Prep
- [ ] **9.5.1** Run spell-check and grammar check
- [ ] **9.5.2** Remove any placeholder text or template instructions (e.g., "SCALE BASED ON COMPLEXITY:", format examples, "[INSERT IMAGE]" placeholders)
- [ ] **9.5.3** Remove any remaining template guidance text that doesn't belong in final document
- [ ] **9.5.4** Resize all images to 350px width by updating markdown format from `![alt text](url)` to `![alt text|350](url)`
- [ ] **9.5.5** Add creation date and version number at top of document
- [ ] **9.5.6** Verify file is saved in correct location: `000 Project Management/workflow/ai_output/[ingredient_name]_v#.md` with correct incremental version number
- [ ] **9.5.7** Ensure Hidden section remains at bottom with research notes
- [ ] **9.5.8** Final check of todo checklist to ensure all tasks are marked complete
- [ ] **9.5.9** Update todo checklist by marking Task 9.5 as complete
- **Dependencies:** 9.4.7
- **Context:** This is final cleanup. Remove all template-specific text that guided writing but shouldn't appear in final reader version. The document should be polished and ready to share. Version number allows for future updates and tracking of iterations.

---

## Task Dependency Map

```
1.0 → 1.1
1.1 → 2.0
2.0 → 2.1
2.1 → 3.0
3.0 → 3.1
3.1 → 3.2
3.2 → 3.3
3.3 → 3.4
3.4 → 3.5
3.5 → 3.6
3.6 → 4.0
4.0 → [4.1 OR 5.0]
4.1 → 4.2
4.2 → 5.0
5.0 → [5.1 OR 5.2]
5.1 → 6.0
5.2 → 5.3
5.3 → 6.0
6.0 → [6.1 OR 6.2]
6.1 → 7.0
6.2 → 6.3
6.3 → 6.4
6.4 → 6.5
6.5 → 7.0
7.0 → 7.1
7.1 → 8.0
8.0 → 8.1
8.1 → 8.2
8.2 → 8.3
8.3 → 9.0
9.0 → 9.1
9.1 → 9.2
9.2 → 9.3
9.3 → 9.4
9.4 → 9.5
```

---

## Estimated Completion

- **Simple ingredient** (e.g., canned beans, flour): 3-4 hours
- **Medium complexity** (e.g., onions, chicken breast): 5-6 hours
- **Complex ingredient** (e.g., whole fish, artichokes): 7-9 hours

The task structure ensures no orphaned tasks and allows for flexibility based on ingredient complexity while maintaining a clear, buildable workflow.