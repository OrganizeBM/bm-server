bm-server
=========

Server for OrganizeBM


Purpose: To receive  a set of bookmarks to and return them back organized
  Main Questions:
    - what type of data-formats can bookmarks be submitted in, e.g JSON, xml, etc?
    - What structure of data is allowed, how flexible should service be?
    - Is the data set suppose to be returned in the same format as the format it was given in?
    - How much control does each request have over how to organize bookmarks?
      - Will certain filters be given to organize by?
        - what kind of filters?
      - Will categories to organize by be given.
      - Should there be set defined categories to organize by?
      - Should categories be created dynamically through the service?
    - How are bookmarks suppose to be filtered?
      - Any API avail. for categorizing phrases?
      - How much data will be needed to process per bookmark?
        - Only title vs title + page content vs page content vs etc ...
