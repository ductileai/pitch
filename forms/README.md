# Sample forms

Four hosted-form definitions in the shape the Ductile AI console takes. Paste one into a new form,
attach it to a process, publish. Each submission starts the process; the person who filled it in
gets a status page.

| file | what it shows |
|---|---|
| `contact.json` | half-width rows, a word cap, a follow-up question that appears only for "Other" |
| `job-application.json` | two pages, a CV upload, a URL that must be on linkedin.com, money and date questions |
| `order-intake.json` | an address question, a PO number with help text, a character cap |
| `event-feedback.json` | a rating, a yes/no, a question shown only after a "no" |

Question types: `short_text`, `long_text`, `email`, `phone`, `number`, `money`, `date`, `time`,
`single_select`, `multi_select`, `yes_no`, `rating`, `file`, `url`, `address`, `page` (a page break).
`showWhen` points at an earlier question. `width: "half"` shares a row on a wide screen and stacks on
a phone. Choices can also be fetched from a process, a job, a file or a saved list instead of typed.

Behind every form, at the owner's choice: a captcha before Send, save-and-finish-later, an email to
the owners and a copy to the sender, a retention period after which answers and files are deleted,
and a table the answers land in.
