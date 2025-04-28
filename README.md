youtube's algorithms and "AI" generated videos made searching youtube nearly impossible, even with alternative frontends/clients. here are some things making it slightly less so (IMHO).


### uBlock Origin add-on

DandelionSprout's [Yet Even More Pure Video Experience](https://raw.githubusercontent.com/DandelionSprout/adfilt/master/YouTubeEvenMorePureVideoExperience.txt).

these filters in My Filters:
```
##ytd-shelf-renderer.ytd-item-section-renderer.style-scope:has-text(explore more)
##ytd-shelf-renderer.ytd-item-section-renderer.style-scope:has-text(People also watched)
###dismissible.ytd-shelf-renderer.style-scope:has-text(explore more)
###dismissible.ytd-shelf-renderer.style-scope:has-text(People also watched)
###contents > .ytd-shelf-renderer.style-scope:has-text(explore more)
###contents > .ytd-shelf-renderer.style-scope:has-text(People also watched)
##.ytd-shelf-renderer.style-scope:has-text(People also watched)
##.ytd-shelf-renderer.style-scope:has-text(explore more)
```


### BlockTube (add-on)

dragitz's [blocktube filters](https://github.com/dragitz/blocktube-filters).

surasshu's [blocklist for AI music on youtube](https://surasshu.com/blocklist-for-ai-music-on-youtube/).

SEXYISM's [BlockTube-Upload-Range-Blocker](https://github.com/SEXYISM/BlockTube-Upload-Range-Blocker), modified to last month.
to go nuclar, change it to 2023-01-01.

video titles filters:
```
ai video
ai cover
/^ai /i
/ai.*generat(ed|ive)/i
#ai
```





