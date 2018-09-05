Strube Lab Protocol collection
==============================

### In order to create a new protocol:

  1. copy the protocol template [lp001_protocol_template.md](lp001_protocoltemplate.md)

  2. file name format `lp000_title.md`

      - `lp` is lowercase for 'lab protocol'
          - we may introduce other prefixes such as `ip` (instrument protocol), `rp` (reagent protocol)
      - replace `000` by the next available number; use leading zeros
      - append `_` and a very short but descriptive title or acronym in lowercase letters
      - append file ending `.md` (indicating markdown format)

  3. Edit the file, adapting title, description and procedure as indicated in
  the template

  4. Add and commit the file to the repository. E.g. using `git`, the following
  commands work (repeat as you make changes, adapt the file name):

      ```sh
      git add lp000_title.md
      git commit -m 'initial commit protocol lp000'
      ```

  5. Once finalized, push the new version to the central repository on github:

      ```sh
      git pull
      git push
      ```

Alternatively, and perhaps easier, you can also simply click the "Create new file" button on GitHub, copy-paste the content of the template into the new file and then edit and commit directly from the GitHub website.


