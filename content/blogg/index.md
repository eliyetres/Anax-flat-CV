---
views:
    main:
        template: default/article
        data:
            class: blog

    byline: false
    share-this: false
    block-about: false
    article-toc: false

    blog-list:
        region: main
        template: default/blog-list
        sort: 2
        data:
            dateFormat: j F Y
            meta: 
                type: toc
                items: 10

    blog-toc:
        region: sidebar-right
        template: default/blog-toc
        sort: 2
        data:
            meta: 
                type: copy
                view: blog-list

...
Min portfolio
===========================

Min blogg innehåller delar av min portfolio från de projekt som jag varit med och skapat eller pågående projekt.

Det finns även beskrivningar av olika typer av designelement som hjälper till att bygga en hemsida eller ett varumärke.
