# Code Refactor Starter Code
# Horieson
Horieson is a company that assists with SEO (Search Engine Optimization), Online Reputation Management and Social Media Marketing.
This site will inform on how they assist with these features as well as others such as lead generation, brand awareness and cost management.

This README is for the refactoring of the site, updates, changes and fixes are below.
## HTML

### Changes
#### Semantic Element Changes
<ul>
    <li>
       Divs changed to element 'header' 
    </li>
    <li>
       Divs changed to element 'nav'
    </li>
    <li>
        Divs changed to element 'section'
    </li>
    <li>
        Div changed to element 'main'
    </li>
    <li>
        Divs under 'main' changed to 'article'
    </li>
    <li>
        Div changed to element 'aside'
    </li>
    <li>
        Divs under 'aside' changed to 'article'
    </li>
    <li>
        Id for elements under benefits 'aside' changed to 'benefits-sub'
    </li>
    <li>
        Divs changed to element 'footer'
    </li>

</ul>

#### Fixes
<ul>
    <li>
        Updated Title to include company name "Horieson"
    </li>
    <li>
        Removed redundant div class elements under aside: benefits-lead; benefits-brand; benefits-cost;
        Updated div element under main section for search engine optimization to include an id.
    </li>
    <li>
        Removed redundant class elements under main elements: 'search-engine-optimization'; 'online-reputation-management'; 'social-media-marketing';
        Updated class element under main section for each 
    </li>
    <li>
        Added alt attributes to images.
    </li>
</ul>

## CSS


#### Changes
<ul>
    <li>
        'Div's changed to semantic element 'nav'
    </li>
    <li>
         Removed redundant coding for: 'search-engine-optimization'; 'online-reputation-management'; 'social-media-marketing';
        Updated to single coding as '.main'
    </li>
    <li>
        Removed redundant coding for 'benefits-lead'; 'benefits-brand'; 'benefits-cost'
        Updated to single coding as 'benefits-sub'
    </li>
    <li>
