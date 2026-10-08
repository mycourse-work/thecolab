# Ask useful questions of a file

Allow 5 minutes.

Claude accepts common documents such as PDF, DOCX, CSV and TXT. In a chat, select **+**, then **Add files or photos**. Choose an approved practice file and attach it.

## Try it: read a tiny practice file

Spend five minutes on this exercise. Save the text below as `practice-quote-notes.txt` on your computer. It describes an invented Christchurch building job.

```text
Practice job: paint one office room.
Included: prepare walls and apply two coats of paint.
Excluded: ceiling, doors and repairs to damaged plaster.
Proposed start: Tuesday next week, subject to client approval.
Price: not yet confirmed.
```

Attach it and ask:

```text
Using only the attached practice file, list scope, exclusions,
proposed start, and missing information in a table.
Include a short source excerpt beside each item.
Keep "subject to client approval". Do not infer a price.
```

Check each row against the original file. “Tuesday next week” alone loses an important condition. A price is missing and must stay missing.

## Know the limits

Project files have a 30 MB limit per file. Other upload limits depend on the route used and the content. Keep practice files small.

Claude reads PDF visuals only in PDFs of 100 pages or fewer. For longer supported PDFs, it reads text. Non-PDF documents use text extraction, so embedded images may be missed. Uploading a file does not prove that every part was understood.

If a figure matters, inspect it yourself. Ask about one section at a time and use the PDF viewer's page numbers when you ask for evidence.


## Sources

[Files](https://support.claude.com/en/articles/8241126-upload-files-to-claude).
