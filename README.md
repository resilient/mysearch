Blink Reaction Test Module

1. Renamed file mysearch.module.php to mysearch.module
2. Created mysearch.info
3. Added translatable title and description in hook_permission
4. Changed hook_menu
  - Added page argument
  - Changed menu type to MENU_CALLBACK
5. Added function mysearch_search_result (moved changed query from mysearch_searchpage)
6. Changed callback mysearch_searchpage
  - Changed title
  - Added case "No results for this query."
  - Changed list output to theme_item_list
