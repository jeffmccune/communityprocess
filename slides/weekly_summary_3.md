<!SLIDE>
# Summary Template

Header:

    ## Puppet Dev Community Summary

     * Finished Card Total: **{{ cards.size }}**
    {% for section in sections %} * {{ section[0] }}: {{ section[1].size }}
    {% endfor %}

Sections:

    {% for section in sections %}## {{ section[0] }}

Cards:

    {% for card in section[1] %}#### [{{card.title}}]({{card.url}})
    
    {{card.message }}
