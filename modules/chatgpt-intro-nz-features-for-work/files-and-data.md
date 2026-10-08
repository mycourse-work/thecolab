# Upload a practice file and check the numbers

**Allow 5 minutes, including any practice below.**

## Prepare a small, clear file

ChatGPT can work with documents and structured data. CSV and spreadsheet files are useful for calculations. Clear column names and one record per row help. Exact values in scanned tables can be harder to extract reliably.

Copy this **invented** data into a plain text file called `practice-jobs.csv`. All figures are example NZD amounts excluding GST; no tax calculation is needed.

```csv
month,quoted_nzd,accepted_nzd
Month 1,12000,9000
Month 2,15000,12000
Month 3,10000,8000
```

Use the attachment control beside the prompt to upload the CSV when available. If you cannot upload, paste the three rows as text instead.

## Five-minute exercise

Ask:

```text
Use only this fictional jobs data.
Show the total quoted value, total accepted value, and the ratio
of accepted value to quoted value across all three months.
Do not average the monthly percentages.
Label amounts NZD excluding GST. Show the formula and inputs.
State what this small dataset cannot tell us.
```

Check the answer yourself:

| Check | Expected result |
| --- | --- |
| Quoted total | 12000 + 15000 + 10000 = 37000 |
| Accepted total | 9000 + 12000 + 8000 = 29000 |
| Accepted value / quoted value | 29000 / 37000 = about 78.4% |

This is a ratio of **values**, not a count of jobs won. The data does not explain why a quote was accepted or show profitability.

If ChatGPT runs code, ask it to show the method and assumptions. You can also request a simple chart when available. Check the labels and totals against the original rows.

## Work within limits

Free has limited uploads and data-analysis access. If you reach a limit, use the text version or do the sums manually. Do not pay just to finish this exercise.

For a real work file, first check approval, hidden sheets, comments, and personal or confidential details. A successful upload does not prove that the file was safe to share or fully analysed.

## Official sources

- [Data analysis, supported files, and limitations](https://help.openai.com/en/articles/8437071-data-analysis-with-chatgpt)
- [Free-plan feature access](https://chatgpt.com/pricing/)
- [File upload limits](https://help.openai.com/en/articles/8555545-file-uploads-faq)
