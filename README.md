# Digital Forensics Investigation: Insider Data Exfiltration Case — CYS301 Coursework

A simulated digital forensics investigation into unauthorized data transmission from a company laptop and USB drive, performed for the Digital Forensic and Investigation course.

## Scenario

Investigated a suspected insider data exfiltration case at a fictional manufacturing company, following formal chain-of-custody procedure from evidence intake through to findings.

## What I did

- Acquired and imaged the suspect's disk, maintaining a documented chain of custody throughout
- Used **FTK Imager** to recover deleted files from the disk image, including financial records, pricing data, and customer invoices
- Reviewed recovered email logs for signs of unauthorized communication
- Conducted network traffic analysis using **Wireshark** to identify data exfiltration and unauthorized network activity
- Compiled all findings into a formal multi-evidence report with a documented investigative conclusion

## Tools used

FTK Imager, Autopsy, Wireshark

## Deliverables in this repo

- `chain-of-custody-form.pdf`
- `multi-evidence-report.pdf` — recovered-file descriptions, evidence analysis, and conclusion
- `screenshots/` — evidence recovery and network analysis output

---
*Completed as part of CYS301: Digital Forensic and Investigation. This was a simulated case using provided disk images in a controlled academic environment — no real individuals or organizations were involved.*
