## Project Management Template

This is a tentative template for managing an experimental project via gitHub. The important sections are:

  1. Protocols: collected in [protocols folder](protocols)

  2. Sequences: collected in [sequences folder](sequences)

  3. Project Management Board: see the [Projects section](https://github.com/graik/wetproject/projects) on github

  4. Customized templates for the [issue tracker](https://github.com/graik/wetproject/issues)

  5. Low-key web site: edit pages in [docs folder](docs), access it under https://graik.github.io/wetproject/

### Tentative Workflow

Example cards and issues are supposed to show how this can be useful. A more detailed description how the workflow *could* look like is given here: [suggested workflow](suggested_workflow.md)

 
### Creating your own experimental project

  1. Fork this repository (see `Fork` Button up right)
  
  2. Copy the project board -- [GitHub help](https://help.github.com/articles/copying-a-project-board/)
  
      - navigate to the original project board (in this repo)
      - open `Menu` (upper right)
      - click the *** (the three dots for additional options)
      - select `copy` and chose your new repository as a destination

  3. Adapt the links in this `README.md` to point to your new project rather than the template
  
  4. Issue templates will be copied but [Issue labels](https://github.com/graik/wetproject/labels) won't -- re-create the labels manually
  

### Protocol sharing ###

A potential problem is that protocols will get spread out over many project repositories. This could be avoided if we either:

* ... collect protocols in one separate repository that is used by the whole lab (e.g. strube-protocols) 
     and create project-specific repositories only for project management

* ... or use this template repository as the central protocol repository 

* ... and / or merge any changes in protocols that happen in forked repositories back to this central 
  repository using pull requests. Project boards and issues will not be affected by the merge and will
  remain separate. Issue templates and the minimal website in [docs](docs) will be affected though and
  child repositories could in theory mess up the common templates or website.

### Help

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

