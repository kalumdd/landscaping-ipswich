IPSWICH SEO SITES - deploy notes

Three separate sites, one folder each. Upload a folder's contents to the root of its own domain.

landscaping/  index.html (Landscaper Ipswich), landscaping-ipswich.html (Landscaping Ipswich)
flooring/     index.html (Flooring Ipswich), commercial-flooring-ipswich.html (Commercial Flooring Ipswich)
cleaning/     index.html (Commercial Cleaners Ipswich), office-cleaners-ipswich.html, contract-cleaners-ipswich.html

Phone numbers and emails have been removed for now. Add them back to the header,
footer and schema when you have them.

Before going live, find and replace in every file:
  [Your address] / IP1 0XX           -> real address (must match Google Business Profile)
  https://www.your...domain.co.uk    -> real domain (canonical tags, schema, sitemap.xml, robots.txt)
  Brand names                        -> check they are not already used by a local business

Quote forms: currently show a preview message only. Connect them to a form handler
(e.g. Formspree, Netlify Forms, or your CRM) by adding an action URL and removing the preview script.

Each page already has: unique title + meta description, one H1 with the keyword, canonical tag,
LocalBusiness + FAQPage schema, internal links between pages, and a sitemap.xml.

ipswich-waste/  41 pages: homepage (Waste Removal Ipswich) + 40 service pages, each targeting
                "[service] Ipswich" (skip hire, grab hire, house clearance, sofa disposal, etc.).
                Also replace "[registration number]" in the footer with your Environment Agency
                waste carrier registration. Copy mentions being a registered carrier, so only go
                live once that registration is in place.
