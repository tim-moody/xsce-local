======================================================
School Server Community Edition (XSCE)- Local Versions
======================================================

This repo is a home for files changed by a local installation of xsce.  Because it is
PUBLICLY VIEWABLE it is not recommended to put passwords here.  However, password hashes
should be OK.

A local_vars.yml file here can contain installation specific overrides of ansible variables.

It is not a fork of the xsce repository with ansible playbooks, but just the files themselves
with enough directory information to indicate where they go in the install. It should be possible
to copy any file in this repo over top of the one put there by the ansible install.

Diffent instances of installs are handled by branches.  However, these are expected to
represent multiple servers rather than a branch for each server.  So, there is a branch for
Haiti, but not a branch for every school in Haiti.  We will try to find a balance between
the completely generic that is in the xsce repo and small changes to each install.

Eventually this will become too cumbersome and a new mechanism will be needed for manually
changing files installed by ansible.