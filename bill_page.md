## Instructions
### Notes
- `Text that looks like this` is a placeholder.
- <mark>Text that looks like this</mark> is either optional or must be filled with one of the given options, or both, depending on the context. It may also be explanatory.
- The ✂️ emoji means the line or entry is optional.
- Abbreviate the months **if and only if** they precede days. Do NOT abbreviate May, June, or July. Abbreviate September as "Sept." Use three-letter abbreviations (followed by a <kbd>.</kbd>) for others.
- Use pages for bills passed during the 14<sup>th</sup> NPC for reference.

#### 1. English Title
##### Content
- Statutes
	- **Form #1:** `*` Law of the People's Republic of China
  - **Form #2:** Law of the People's Republic of China on `*`
- Decision of <mark>the Standing Committee of the National People's Congress</mark> on `*`

##### Details
- For a statute, use Form #1 unless Form #2 is more appropriate. Please check with me if you are unsure.
- Adapt the format other statutory forms—e.g., "条例" (regulations), "规则" (rules), "法典" (code)—accordingly.
- Apply "Heading 3" in WordPress.

#### 2. 中文标题
##### Content
- 中华人民共和国`*`
- 全国人民代表大会<mark>常务委员会</mark>关于`*`的决定

#### Details
- Apply "Heading 3" in WordPress.
- Start 中文标题 on a new line with a "soft return" (<kbd>⇧ shift</kbd> + <kbd>↩ return</kbd>).

#### 3. Current Text
##### Content
- Defaults
  - [<span class="smcp">Current Text</span>: _not yet enacted_]
  - <span style="color: #DE2910">[<span class="smcp">Current Text</span>: _not yet available_]</span>
  - [<span class="smcp">Current Text</span>: Chinese only]
  - [<span class="smcp">Current Text</span>: Chinese, English]
- With comparison charts
  - [<span class="smcp">Current Text</span>: Chinese only · 🆚]
  - [<span class="smcp">Current Text</span>: Chinese \| English · 🆚]
- Multiple translations
  - [<span class="smcp">Current Text</span>: Chinese \| English › `Outlet1`; `Outlet2`]
- Insignificantly outdated translation
  - [<span class="smcp">Available Text</span>: Chinese (current) \| English (v. `year`)]

##### Details
- Enter <span class="smcp">Current Text</span> in "Edit as HTML" mode as <kbd>[&lt;span class="small-caps"&gt;Current Text&lt;/span&gt;: *]</kbd>.
- **Comparison chart**
  - Link to comparison charts here **only** in the case of a new law or revision. For amendments, see "[Legislative History and Text](#11-legislative-history--text)."
  - When a webpage or file includes both a text and a comparison chart, do NOT include <kbd>·</kbd>; instead, apply its link to both the relevant language name and the 🆚 emoji.
- **Bills passed but not yet available**
  - In the case of an amendment or a revision, (1) change the text to "Chinese only" but do NOT alter the link; (2) apply the native <span style="color:white; background-color:#abb8c3">cyan bluish gray</span>; and (3) add "_Full text of the Law as <mark>amended / revised</mark> is not yet available_" below (see next section). **At my discretion, exceptions will be made for closely watched bills.**
  - In the case of a new law, apply the native <span style="color:white; background-color:#cf2e2e">vivid red</span>, which will be converted to <span style="color:white; background-color:#DE2910">#DE2910</span> automatically.

#### 4. Full Text Unavailable
##### Content
✂️ <span style="color:#DE2910">_Full text of the Law as <mark>amended / revised</mark> is not yet available_</span>

##### Details
- Apply the native <span style="color:white; background-color:#cf2e2e">vivid red</span>, which will be converted to <span style="color:white; background-color:#DE2910">#DE2910</span> automatically.
- Add this line when the amended or revised text is not yet available on 维基文库, **whether or not** an official text has been released. **At my discretion, exceptions will be made for closely watched bills.**
- When this line is added, change the color of the Current Text line to the native <span style="color:white; background-color:#abb8c3">cyan bluish gray</span>.

#### 5. Statutory History
##### Content
- Building blocks
  - <mark>adopted / amended / revised</mark> `month day, year`, effective `month day, year`
  - <mark>adopted / amended / revised</mark> and effective `month day, year`
- Together
  - (`Event1`; `Event2`; `...`)

##### Details
Abbreviate the months.

#### 6. Status
##### Content
- Bill passed
  - <span style="color:hsl(123, 70%, 40%)">**<mark>Amendment / Revision</mark> passed**</span>
- Bill already scheduled for deliberation
  - <span style="color:#ff6900">**<mark>Amendment / Revision</mark> pending**</span>
- Bill submitted but not yet scheduled for deliberation
  - <span style="color:#ff6900">**<mark>Amendment / Revision</mark> submitted on `month day, year`**</span>
- Project planned
  - <span style="color:#2962FF">**<mark>Amendment / Revision / Modification</mark> planned**</span>
- Unplanned bill released for public comment
  - <span style="color:#2962FF">**<mark>State Council / other body</mark> solicited public comment <mark>on draft amendment / revision</mark>**</span>
- Bill withdrawn
  - <span style="color:#FF0000">**<mark>Amendment / Revision</mark> withdrawn**</span>

##### Details
- **Always capitalize** the first letter after the colon—e.g., "Planned" when appearing alone.
- Apply color using the "Highlight" function in WordPress editor.
  - Passed: native <span style="color:white; background-color:#00d084">vivid green cyan</span> (which will be converted to <span style="color:white; background-color:hsl(123, 70%, 40%)">hsl(123, 70%, 40%)</span> automatically)
  - Pending / Submitted: native <span style="color:white; background-color:#ff6900">luminous vivid orange</span>
  - Planned / Solicited public comment: <span style="color:white; background-color:#2962FF">#2962FF</span>
  - Withdrawn: <span style="color:white; background-color:#FF0000">#FF0000</span>
- For a bill that has been submitted (almost always by the State Council) but hasn't been scheduled for deliberation, fill in the date of the State Council Executive Meeting that approved the bill. Abbreviate the month.
- Consider a project "planned" **only if** it has appeared in an NPCSC legislative plan (even as a 预备审议项目). Use "modification" if it's unclear whether the law will be amended or revised (the State Council's annual legislative plans may be used to determine the method of modification).

#### 6. Proposed New Title
##### Content
_`English title`_ [`中文标题`]

##### Details
- Use when a revision would change the law's title. Omit "中华人民共和国" and its translation from the titles.
- After the revision has passed:
  - Delete this item;
  - Add "Law Repealed";
  - Change "Status" to "Passed" (from "Revision pending"); and
  - Change the bill page's title and the law's title to the new one.

#### 7. Legislative Body (Vote)
##### Content
<mark>NPCSC / NPC</mark> (<mark>TBD / N/A / <code>for–against–abstain</code></mark>)

##### Details
- Change (1) "NPCSC" to "NPC" and (2) "Submitter" to "Initial Submitter" **only after** the NPCSC has decided to submit a bill to the NPC.
- Separate votes with en-dashes (<kbd>⌥ Option</kbd>+<kbd>-</kbd> in macOS) without any space before or after.

#### 8. Principal Drafter & Submitter
##### Content
- When same (one bullet)
  - **Principal Drafter & <mark>Designated / Presumptive / Initial</mark> Submitter**: `body`
- When different (two bullets)
  - **Principal Drafter(s)**: `body or bodies`
  - **<mark>Designated / Presumptive / Initial</mark> Submitter**: `body`

##### Details
- Principal Drafter(s)
  - If known, specify the component(s) of the Communist Party, NPCSC, State Council, and/or Central Military Commission (CMC) that drafted the bill. Where there are multiple drafting bodies, separate the last two with <kbd>&</kbd>.
  - In the case of a Party entity, don't refer to the Party in its name; instead, use its shortened, colloquial name and add <kbd>☭</kbd> (set off by a space) before it, as done [here](https://npcobserver.com/legislation/national-security-law/), [here](https://npcobserver.com/legislation/national-defense-education-law/), or [here](https://npcobserver.com/constitution/). CMC components and nominal State Council agencies do NOT count as Party entities.
  - Update this field based on new annual legislative plans of the State Council or new 草案说明.
- Submitter
  - For a planned project that hasn't been submitted, use "Designated Submitter".
  - For an unplanned project, use "Presumptive Submitter".
  - For a bill that has been submitted to the NPC, change the entry name to "Initial Submitter" and do NOT fill in "NPCSC".

#### 9. Law / Regulations Repealed
##### Content
**<mark>Law(s) / Regulations Repealed / Proposed for Repeal</mark>:** _`English title`_ [`中文标题`]

##### Details
- Use "Proposed for Repeal" when the bill is pending.
- Omit "中华人民共和国," "全国人民代表大会[常务委员会]," and their translations from the titles.

#### 10. Legislative Plans
##### Content
- Five-year: <mark><code>ordinal #</code> NPCSC Category <code>Upper Roman #</code> / N/A</mark>
- ✂️ Special: Public Health Category <code>Upper Roman #</code>
- Annual: <mark><code>year</code> / N/A</mark>

##### Details
- Five-year plans
  - Separate different plans by <kbd>;</kbd>.
  - Use the information given in the "Bill Pages_五年立法规划统计.docx" file on Dropbox.
- Annual plans
  - Separate different plans by <kbd>,</kbd>. Add "(backup)" after a year (set off by a space) if the bill was a 预备审议项目.
  - Check all annual plans since 2013. In the case of a 法律修改 project that has appeared in an older annual plan, don't include it if the project was subsequently completed (before reappearing in a more recent annual plan).

#### 11. Legislative History & Text
##### Content
- Legislative Deliberation
  - Variations
    - NPC deliberation – final round: `date` (`text`)
    - NPCSC deliberation – round #3 (final): `date` (`text`)
    - NPCSC deliberation – round #`*`: `date` (`text`) `consultation shortcode`
    - NPCSC deliberation – only round: `date` (`text`)
  - Date
    - _planned for / originally planned for / likely by / expected by <mark><code>month year</code> / <code>other time</code></mark>_
    - `month da`y – `day, year`
    - `month day` – `month day, year`
    - `month day, year` – `month day, year`
  - Text
    - (<span class="smcp">Current Text</span> 🔝)
    - (text pending)
    - (Chinese only)
    - (Chinese, English)
    - (Chinese 🆚 \| English)
    - (Chinese \| English › `Outlet1`; `Outlet2`)
    - (text N/A)
  - Consultation Shortcode
    - <kbd>[consultation link="<code>url of public consultation post</code>" date="<code>date</code>"]</kbd>
- Other Public Consultations
  - <mark>State Council / other body</mark> public consultation <mark>– round #<code>*</code></mark>: `date` (`text`) ✍️

##### Details
- List entries reverse chronologically, with the newest at the top.
- **Date**
  - Abbreviate the months.
  - Use en-dashes (<kbd>⌥ Option</kbd>+<kbd>-</kbd> in macOS) to separate two dates. Adding a space before and after the en-dash is **optional**; the site will automatically add either a "six-per-em space" (`U+2006`; <span style="background-color: #0F52BD">&#x2006;</span>) or "thin space" (`U+2009`; <span style="background-color: #0F52BD">&#x2009;</span>) before and after an en-dash or replace any space with it.
  - Do NOT repeat the month or year if it's the same on both sides of the en-dash.
- **Text**
  - If a webpage or file includes both a text and a comparison chart, apply its link to the relevant language name and the 🆚 emoji. Otherwise, separate them with <kbd>·</kbd> (with a space before and after it).
  - "(<span class="smcp">Current Text</span> 🔝)"
    - Enter this code in "Edit in HTML" mode: <kbd>(&lt;span class="small-caps"&gt;Current Text&lt;/span&gt;&nbsp;&lt;span class="emoji-jump-link"&gt;🔝&lt;/span&gt;)</kbd>. If the code is entered correctly, clicking the 🔝 emoji will make the page scroll up to the <span class="smcp">Current Text</span> at the top of page (or to the nearest <span class="smcp">Current Text</span> above, as seen [here](https://npcobserver.com/legislation/hong-kong-basic-law/)).
    - Use **only** in the case of a new law or a revision, not an amendment. Add it **even when** the text of the new law or revised law is not yet available.
- **NPCSC Consultation Shortcode**
  - Add a space between the "text" parenthentical and the shortcode.
  - Make sure the URL entered is NOT active (i.e., can't be clicked).
  - If entered correctly, the shortcode will generate the 💬 emoji at the end of the line and begin a new indented bullet with information like <kbd>[Public Consultation](https://npcobserver.com/2025/06/china-npc-consultation-emergency-aviation-community-governance-social-assistance-healthcare-food-safety-law/): June 27 – July 26, 2025</kbd>. While the consultation is ongoing, the shortcode will also add the 🔔 emoji and a <span style="background-color:#F9EBBE">yellow background</span>.
- **Other Public Consultations**
  - In general, use "State Council" when an administrative agency solicited public comment, even a nominal one.
  - Do NOT specify the State Council agency that solicited public comment.
  - Link the ✍️ emoji to the official notice.
- **Explanatory Parentheticals**
  - In the case of 法律修改, number multiple State Council consultations by round **only if** (1) the method of modification was the same; and (2) in the case of an amendment, the changes were not substantially different (may rely on 草案说明, if available). Otherwise, add an explanatory parenthetical immediately after "public consultation"—and before the <kbd>—</kbd> or <kbd>:</kbd>—to distinguish the drafts, as done [here](https://npcobserver.com/legislation/tax-collection-administration-law/) and [here](https://npcobserver.com/legislation/food-safety-law/).
  - In the case of a codification bill, add similar explanatory parentheticals if necessary, as done [here](https://npcobserver.com/legislation/civil-code/) and [here](https://npcobserver.com/legislation/ecological-and-environmental-code/).
 
#### 12. Legislative Records
##### Content
**NPCSC Enactments**
- Explanation (`date`) <mark>=说明</mark>
- ✂️ Report on Status of Revision (`date`) <mark>=修改情况的汇报</mark>
- Report on Results of Deliberation (`date`) <mark>=审议结果的报告</mark>
- ✂️ Report on Suggestions for Revision (`date`) <mark>=修改意见的报告</mark>
- Presidential Order (`date`)
**NPC Enactments**
  - NPCSC Stage
  - Explanation (`date`)
  - Report on Status of Revision (`date`)
  - ✂️ Report on Deliberation Opinions (`date`) <mark>=审议意见的报告</mark>
- NPC Stage
  - Explanation (`date`)
  - Report on Results of Deliberation (`date`)
  - Report on Suggestions for Revision (`date`)
  - <mark>Presidential Order / NPC Public Announcement</mark> (`date`)
**Date**
- `month day, year`
- pending
- N/A

##### Details
- Include "Report on Status of Revision" and "Report on Suggestions for Revision" by default. But delete the former when the bill is expected to pass after only two reviews; and both when the bill is expected to pass after a single review.
- Include "Report on Deliberation Opinions" **only when** it is publicly available.
- Do NOT include the number of a presidential order or NPC public announcement.
- Before these documents are released after a bill's passage, link to the relevant pages in our PDFs compiling the explanatory documents released during prior public consultations by adding <kbd>#page=<code>*</code></kbd> at the end of the URL. Assume a document is dated the start date of the relevant NPCSC session.
- **Always** link presidential orders to [维基文库](https://en.wikisource.org/wiki/zh:%E4%B8%AD%E5%8D%8E%E4%BA%BA%E6%B0%91%E5%85%B1%E5%92%8C%E5%9B%BD%E4%B8%BB%E5%B8%AD%E4%BB%A4/%E7%AC%AC%E5%8D%81%E5%9B%9B%E5%B1%8A) versions. Make sure to click on the relevant presidential order in the navigation sidebar, so that the link ends in <kbd>#第<code>×</code>号</kbd>.

#### 13. Official Q&A & Press Conference
##### Content
- ✂️ **Official Q&A:** `body providing the Q&A` (`month day, year`)
- ✂️ **Press Conference:** `body holding the press conference` (`month day, year`)

##### Details
- For a source to count as an "Official Q&A", it must be in the question-and-answer format. State media reports on interviews with officials that include information other than the questions and answers themselves do NOT count.
- List a "Press Conference" only if the relevant bill is at least one of the designated topics of the press conference.
- Abbreviate the month.
- If both "Official Q&A" and "Press Conference" are listed, order them chronologically; if both have the same date, list the "Official Q&A" first.
