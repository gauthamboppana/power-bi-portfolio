# Power BI portfolio publishing checklist

Use this checklist for every report before publishing it to GitHub.

## 1. Confirm permission

- [ ] I own the work or have explicit permission to showcase it.
- [ ] Employer, client, licensing, and dataset terms allow publication.
- [ ] Branding and logos are permitted or have been replaced.

## 2. Protect data and access

- [ ] Screenshots contain no names, emails, IDs, addresses, or other personal data.
- [ ] Confidential metrics are removed, anonymized, indexed, or replaced with synthetic values.
- [ ] Tenant names, workspace names, report URLs, gateway details, and internal links are hidden.
- [ ] Credentials, tokens, connection strings, and local paths are absent.
- [ ] Hidden pages, tooltip pages, filters, and model metadata have also been checked.

## 3. Choose safe artifacts

- [ ] Prefer screenshots, a GIF/video, a model diagram, selected DAX, and a written case study.
- [ ] Publish a `.pbix` only if every embedded row is public or synthetic and sharing rights are clear.
- [ ] If using PBIP/source-control files, inspect all text files for server, database, tenant, and user details.
- [ ] Sample data is synthetic or comes from a clearly cited public source.

## 4. Make the story strong

- [ ] The case study starts with the business decision, not a list of visuals.
- [ ] It explains audience, KPIs, model design, important DAX, and report UX.
- [ ] Insights are linked to actions and outcomes.
- [ ] Screenshots are legible, consistently cropped, and include useful captions.
- [ ] Limitations and lessons learned are honest and concise.

## 5. Final repository check

- [ ] Search the full repository for sensitive terms before committing.
- [ ] Open every image at full size and inspect it.
- [ ] Verify all links and image paths from GitHub's rendered README.
- [ ] Ask a trusted person to review the first case study before making it public.

