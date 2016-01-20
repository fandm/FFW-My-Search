# FFW-My-Search

1. Renamed mysearch.module.php to mysearch.module.
2. Created mysearch.info file.
3. Some modifications in function mysearch_menu(). Changed “$items['mysearch']“ to the “$items['mysearch/%']“ and “$items['mysearch/%/%’]“. Added “'page arguments' => array(1, 2),”.
4. Changed definition of the function mysearch_searchpage() to the function mysearch_searchpage($searchterm, $count).
5. Rewrited body of the function mysearch_searchpage().
6. Added calls of the function t() for strings, which can be localized.
