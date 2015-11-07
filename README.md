## run local hugo server

    hugo server --theme=(theme name)

#### the following themes compile and show my journal content:

                                        d ペ pag pre pn あ E 1 笑 r S + X
    hugo server --theme=purehugo        O     O   O                S +  R (sharing links) (RSS feed)
    hugo server --theme=herring-cove    O             O        O   S      (prev next on each entry)  (has a sidebar)
    hugo server --theme=gindoro         O         O     あ   O            (あいうえお) (read time in minutes)
    hugo server --theme=cactus          O  O               E              (links About page) (compiles with errors)
    hugo server --theme=detox           O     O   O                       (dates on index)  (paginates the top index)

    hugo server --theme=heather-hugo              O                       (preview entry on top list)
    hugo server --theme=hyde            O         O                S
    hugo server --theme=hugo-zen        O
    hugo server --theme=hugo-bootswatch O         O
    hugo server --theme=hugo-h5bp       O     X   O              O        (pagination links broken) (recent entries box)
    hugo server --theme=hurock                             E
    hugo server --theme=html5                                             (basic, with no dates on index)
    hugo server --theme=projecthub      O         O


    hugo server --theme=startboostrap-clean-blog has allll the page numbers in pagination 
    hugo server --theme=tachyons has interesting year-tag on long index




#### the following themes compile but don't show journal entries in current configuration

    hugo server
    hugo server --theme=agency
    hugo server --theme=artists
    hugo server --theme=bootie-docs
    hugo server --theme=bootstrap
    hugo server --theme=cocoa
    hugo server --theme=creative
    hugo server --theme=freelancer
    hugo server --theme=greyshade
    hugo server --theme=grid-side
    hugo server --theme=hugo-base-theme
    hugo server --theme=hugo-multi-bootswatch
    hugo server --theme=hugo-uno
    hugo server --theme=journal
    hugo server --theme=pixyll                    shows tags, but no content



## upgrading Hugo on OS X

    brew unlink hugo

    brew install hugo
