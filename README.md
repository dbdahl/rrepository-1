# Maintenance

Over time the binary files accumulate such that the git repository gets very large.

The solution is to:

1. copy the current repository.
2. in the copy, delete all but the most recent binaries.
3. create another git repository on GitHub with this most recent content.
4. for the new repository, go to Settings -> GitHub Pages, a set it serve the /docs directory.
5. test that its servers pages correctly, just like the old repository, apart from the different URL.
6. then, in GitHub pages, have the old repository no longer serve https://r.ddahl.org and make the new one do this.
7. eventually delete the old git repository.

Test, test, test.

