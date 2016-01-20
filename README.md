# FFW-My-Search

1. Renamed mysearch.module.php to mysearch.module. It should be so.
2. Created mysearch.info file. This file needed.
3. Some modifications in function mysearch_menu(). Changed “$items['mysearch']“ to the “$items['mysearch/%']“ and “$items['mysearch/%/%’]“. Added “'page arguments' => array(1, 2),”. For send the search term and/or count of the nodes per page via url.
4. Changed definition of the function mysearch_searchpage() to the function mysearch_searchpage($searchterm, $count). To receive the search term and count of the nodes per page.
5. Rewrited body of the function mysearch_searchpage(). Because now it's works properly. :)
6. Added calls of the function t() for strings, which can be localized. Because we can and we should.
