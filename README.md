# Alfred-workflow-Firefox-search-Google-from-DuckDuckGo
# Introduction

As a Firefox user I like to use DuckDuckGo as a search engine because it [does not track me](https://help.duckduckgo.com/duckduckgo-help-pages/privacy/anonymous-localized-results/). However, sometimes the results are not as good as those you can obtain from Google. This workflow allows for a direct seach using Google even when:

- DuckDuckGo is your default search engine;
- you are in a Firefox private window (although being in a private window is not a prerequisite for the workflow).

# Usage

This workflow:

- relies on Firefox being installed (and uses Firefox for the search);
- relies on DuckDuckGo being the default search engine in Firefox;
- uses a DuckDuckGo !Bang to search Google (see [this DuckDuckGo help page](https://help.duckduckgo.com/duckduckgo-help-pages/features/bangs/) for more about !Bangs);
- will work in a Firefox private window.

(Note that `<https://duckduckgo.com/?t=ffab&q=!guk {query} -amazon -youtube -ebay>` can be configured as a fallback search in Alfred *but* cannot be forced to execute in a Firefox private window. This workflow *will* execute in a private window.)

In the User Configuration you can change:

- the default keyword (`guk`);
- the default !Bang (so, e.g., you could use `!g` to search Google generally as opposed to the default UK Google site);
- the default exclusions from the search result (`-ebay -amazon -youtube`).
