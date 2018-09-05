Strube Lab Protocol collection
==============================

### In order to create a new protocol:

  Click the "Create new file" button on GitHub, copy-paste the raw content of the [template](lp001_labprotocol_template.md) into the new file and then edit and commit directly from the GitHub website.

  Alternatively, offline editing using the `git` program is the more efficient and professional choice for larger protocols:
  
  1. create a local copy of the protocols repo on your computer (into a folder `strubeprotocols`)
  
      ```sh
      git clone https://github.com/strubelab/protocols.git strubeprotocols
      ```

  2. copy the protocol template [lp001_labprotocol_template.md](lp001_labprotocol_template.md)

  3. file name format `lp000_title.md`

      - `lp` is lowercase for 'lab protocol'
          - we may introduce other prefixes such as `ip` (instrument protocol), `rp` (reagent protocol)
      - replace `000` by the next available number; use leading zeros
      - append `_` and a very short but descriptive title or acronym in lowercase letters
      - append file ending `.md` (indicating markdown format)

  4. Edit the file, adapting title, description and procedure as indicated in
  the template

  5. Add and commit the file to the repository. E.g. using `git`, the following
  commands work (repeat as you make changes, adapt the file name):

      ```sh
      git add lp000_title.md
      git commit -m 'initial commit protocol lp000'
      ```

  6. Once finalized, push the new version to the central repository on github:

      ```sh
      git pull
      git push
      ```
