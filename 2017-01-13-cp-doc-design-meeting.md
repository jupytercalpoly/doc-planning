# Cal Poly Design Meeting - Documentation [Friday, January 13, 2017]

Attendees: Brian, Carol, Cameron, Charnpreet

**Target next meeting date**: Friday, January 27, 2017

## Next actions

- Continue design work on theme
- Investigate cards and user testing (optimalworkshop.com)
- Check if Cameron's design of single Sphinx page can be easily implemented
  for Jupyter RTD docs i.e. colors, fonts
- Continue prototype of a Jupyter theme based on work done by Charnpreet.
  [Repo](https://github.com/jupytercalpoly/documentation-theme) is now on Cal Poly Jupyter organization.

---

## Good design examples: documentation landing pages

- Apple

    - top level navbar you can tell where you are i.e. Distribute (greyed)


- Wolfram Alpha

    - https://reference.wolfram.com/language/
    - Embodies "don't make me think" principles 
    - Users make one choice - what am i trying to do now
    - UI cards are focused on user tasks and goals
    - Home page easily leads to finding something -> you are looking at is what you want
    - Dropdowns - detailed enough that you don't have to go further down
      in more dropdowns 
    - flat dropdown documentation structure instead of
      lots of levels

## Content organization, Sphinx stuff, one vs many repos

Addressing these will come after finding a user friendly and effective
design.

### Examples

- JupyterHub federated docs - Consolidated repo using Git submodules for individual projects
[Repo](https://github.com/willingc/jhubdocs) [Rendered docs](https://jhubdocs.readthedocs.io/en/latest/)
- sentry - armin ronacher (flask/jinja) [Docs](https://docs.sentry.io/) [Repo](https://github.com/getsentry/sentry-docs)
- openstack

## General categories for Jupyter documentation

### User focused subprojects

- Jupyterlab
- Notebook
- JupyterHub

### Plumbing

- message subprojects
- developer oriented

### Community

- design
- governance


## Design: Jupyter-wide universal navbar

This navbar would be available across everything - website, documentation,
nbviewer.
- Jupyter
- Install
- documentation

## Design: Jupyter documentation landing page

Consistent Documentation band that persists on all pages
- title: Documentation
- search box global

Smaller topic boxes
- design: color
- card - overlay or on card itself

## Design: Individual sphinx page

- top level navbar
- sphinx documentation

## Design: nbviewer

- main site header
- nbviewer tool bar

Considerations for nbviewer:
- widgets
- custom mime types
- altair notebooks in nbviewer

## Design: lessons

- dark grey looks really good on all things jupyter
- See social media updates with dark grey - work by Spoo

## Testing resource: optimalworkshop.com

[Site](https://optimalworkshop.com)

Card design testing - card sorting

dendrograms

Tree testing - discoverability (TreeJack)
