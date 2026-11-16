# Script queue for the teleprompter

`queue.json` lists the scripts the owner records. Form TV-1 in the workstation reads it (**Studio scripts**) and opens
the chosen script on its teleprompter. Recordings go into the Drive folder named in `inboxName`/`inbox`, under each
script's `file` name; the studio picks them up from there.

This file is public. Only scripts meant for published videos go here: never a client's, student's or family's details.

Fields per script: `id`, `series`, `episode`, `title`, `due` (YYYY-MM-DD), `record` (`audio` or `video`), `file`
(file name without extension), `status` (`to-record` or `recorded`), `notes`, and `segments` (each with `seg`, `title`,
`say`, optional `body`).
