---
layout: home
titles:
  # @start locale config
  en      : &EN       Updates
  en-GB   : *EN
  en-US   : *EN
  en-CA   : *EN
  en-AU   : *EN
  it      : &IT       Aggiornamenti
  it-IT   : *IT
  it-CH   : *IT
  # @end locale config
key: page-updates
articles:
  data_source: site.posts
  article_type: BlogPosting
  show_cover: false
  show_excerpt: true
  show_readmore: true
  show_info: true
---
<div class="layout--home">
  {%- include paginator.html -%}
</div>