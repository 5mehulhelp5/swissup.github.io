---
layout: default
title: Navigationpro and EasyCatalogImages Widget
description: Using EasyCatalogImages Widget instead of standard dropdown
category: Navigationpro
---

# Easy Catalog Images Widget

![EasyCatalogImages Widget](/images/m2/navigationpro/use-cases/easycatalogimages-widget.png)

Navigate to _Swissup > NavigationPro_ page, select item to edit and use
[layout builder][layout-builder] to get something similar to the screenshot below:

![EasyCatalogImages Widget Backend](/images/m2/navigationpro/use-cases/easycatalogimages-widget-backend.png)

HTML Content:

```html
{% raw %}<div class="text-center">
{{widget type="Swissup\Easycatalogimg\Block\Widget\SubcategoriesList" category_id="category/20" category_count="100" subcategory_count="0" column_count="4" show_image="1" image_width="294" image_height="450" template="Swissup_Easycatalogimg::list.phtml" hide_when_filter_is_used="0"}}
</div>{% endraw %}
```

#### Next up
{:.no_toc}

 -  [Back to Main Page](/m2/extensions/navigationpro/)
 -  [CSS Helpers][css-helpers]

[layout-builder]: /m2/extensions/navigationpro/ui/dropdown-layout-builder/ "Layout Builder"
[item-renderer]: /m2/extensions/navigationpro/ui/menu-item-name-as-html/ "Item Name Renderer"
[menu-settings]: /m2/extensions/navigationpro/backend/menu-settings/ "Menu Settings Panel"
[css-helpers]: /m2/extensions/navigationpro/customization/css-helpers/ "CSS Helpers"