## Instructions
### Notes
- `Text that looks like this` or <var>Test that looks like this</var> is a placeholder.
- `‹Text enclosed within single guillemets like this›` is either optional or must be filled with one of the given options, or both, depending on the context.
- The ✂️ emoji means the line or entry is optional.
- Abbreviate the months **if and only if** they precede days. Do NOT abbreviate May, June, or July. Abbreviate September as "Sept." Use three-letter abbreviations (followed by a <kbd>.</kbd>) for others.
- Use pages for bills passed during the 14<sup>th</sup> NPC for reference.

#### 1. English Title
##### Content
- Statutes
	- **Form #1:** `*` Law of the People's Republic of China
  - **Form #2:** Law of the People's Republic of China on `*`
- Decision of `‹the Standing Committee of the National People's Congress›` on `*`

##### Details
- For a statute, use Form #1 unless Form #2 is more appropriate. Please check with me if you are unsure.
- Adapt the format other statutory forms—e.g., "条例" (regulations), "规则" (rules), "法典" (code)—accordingly.
- Apply "Heading 3" in WordPress.

#### 2. 中文标题
##### Content
- 中华人民共和国`*`
- 全国人民代表大会`‹常务委员会›`关于`*`的决定

#### Details
- Apply "Heading 3" in WordPress.
- Start 中文标题 on a new line with a "soft return" (<kbd>⇧ shift</kbd> + <kbd>↩ return</kbd>).

#### 3. Current Text
##### Content
- Defaults
  - [<span class="smcp">Current Text</span>: _not yet enacted_]
  - <span style="color: #DE2910">[Cᴜʀʀᴇɴᴛ Tᴇxᴛ: _not yet available_]</span>
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
  - Link to comparison charts here **only** in the case of a new law or revision. For amendments, see "Legislative History and Text."
  - When a webpage or file includes both a text and a comparison chart, do NOT include <kdb>·</kbd>; instead, apply its link to both the relevant language name and the 🆚 emoji.
- **Bills passed but not yet available**
  - In the case of an amendment or a revision, (1) change the text to "Chinese only" but do NOT alter the link; (2) apply the native <span style="color:white; background-color:#abb8c3">cyan bluish gray</span>; and (3) add "_Full text of the Law as `‹amended / revised›` is not yet available_" below (see next row). **At my discretion, exceptions will be made for closely watched bills.**
  - In the case of a new law, apply the native <span style="color:white; background-color:#cf2e2e">vivid red</span>, which will be converted to <span style="color:white; background-color:#DE2910">#DE2910</span> automatically.

#### 4. Full Text Unavailable
##### Content
✂️ <span style="color:#DE2910">_Full text of the Law as `‹amended / revised›` is not yet available_</span>

##### Details
- Apply the native <span style="color:white; background-color:#cf2e2e">vivid red</span>, which will be converted to <span style="color:white; background-color:#DE2910">#DE2910</span> automatically.
- Add this line when the amended or revised text is not yet available on 维基文库, **whether or not** an official text has been released. **At my discretion, exceptions will be made for closely watched bills.**
- When this line is added, change the color of the Current Text line to the native <span style="color:white; background-color:#abb8c3">cyan bluish gray</span>.

#### 5. Statutory History
##### Content
- Building blocks
  - `‹adopted / amended / revised›` `month day, year`, effective `month day, year`
  - `‹adopted / amended / revised›` and effective `month day, year`
- Together
  - (`Event1`; `Event2`; `...`)

##### Details
Abbreviate the months.

#### 6. Status
##### Content
- Bill passed
  - <span style="color:hsl(123, 70%, 40%)">**`‹Amendment / Revision›` passed**</span>
- Bill already scheduled for deliberation
  - <span style="color:#ff6900">**`‹Amendment / Revision›` pending**</span>
- Bill submitted but not yet scheduled for deliberation
  - <span style="color:#ff6900">**`‹Amendment / Revision›` submitted on `month day, year`**</span>
- Project planned
  - <span style="color:#2962FF">**`‹Amendment / Revision / Modification›` planned**</span>
- Unplanned bill released for public comment
  - <span style="color:#2962FF">**`‹State Council / other body›` solicited public comment `‹on draft amendment / revision›`**</span>
- Bill withdrawn
  - <span style="color:#FF0000">**`‹Amendment / Revision›` withdrawn**</span>

##### Details
- **Always capitalize** the first letter after the colon—e.g., "Planned" when appearing alone.
- Apply color using the "Highlight" function in WordPress editor.
  - Passed: native <span style="color:white; background-color:#00d084)">vivid green cyan</span> (which will be converted to <span style="color:white; background-color:hsl(123, 70%, 40%)">hsl(123, 70%, 40%)</span> automatically)
  - Pending / Submitted: native <span style="color:white; background-color:#ff6900">luminous vivid orange</span>
  - Planned / Solicited public comment: <span style="color:white; background-color:#2962FF">#2962FF</span>
  - Withdrawn: <span style="color:white; background-color:#FF0000">#FF0000</span>
- For a bill that has been submitted (almost always by the State Council) but hasn't been scheduled for deliberation, fill in the date of the State Council Executive Meeting that approved the bill. Abbreviate the month.
- Consider a project "planned" **only if** it has appeared in an NPCSC legislative plan (even as a 预备审议项目). Use "modification" if it's unclear whether the law will be amended or revised (the State Council's annual legislative plans may be used to determine the method of modification).

#### 6. Proposed New Title
##### Content
`_English title_` [`中文标题`]

##### Details
- Use when a revision would change the law's title. Omit "中华人民共和国" and its translation from the titles.
- After the revision has passed:
  - Delete this item;
  - Add "Law Repealed";
  - Change "Status" to "Passed" (from "Revision pending"); and
  - Change the bill page's title and the law's title to the new one.

#### 7. Legislative Body (Vote)
##### Content
`‹NPCSC / NPC›` (<code>‹TBD / N/A / <var>for–against–abstain</var>›</code>)

##### Details
- Change (1) "NPCSC" to "NPC" and (2) "Submitter" to "Initial Submitter" **only after** the NPCSC has decided to submit a bill to the NPC.
- Separate votes with en-dashes (<kbd>⌥ Option</kbd>+<kbd>-</kbd> in macOS) without any space before or after.

#### 8.
##### Content
##### Details

#### 9.
##### Content
##### Details

#### 10.
##### Content
##### Details

#### 11.
##### Content
##### Details
