php-solr4
=========

A patched version of the php solr extension, supports Solr 4. 
Based on http://pecl.php.net/package/solr

Api Changes
===========

  * SolrClient::commit (...) changed to: SolrClient::commit ([int $maxSegments = "1" [, bool $softCommit = false [, bool $waitSearcher = true ]]] )
  * SolrClient::optimize(...) changed to: SolrClient::optimize([int $maxSegments = "1" [, bool $softCommit = false [, bool $waitSearcher = true ]]] )
  * SolrClient::addDocument(...) changed to: SolrClient::addDocument (SolrInputDocument $doc [, bool $overwrite = true[, int $commitWithin = 0 ]] )
  * SolrClient::addDocuments(...) changed to: SolrClient::addDocuments (array $docs [, bool $overwrite = true[, int $commitWithin = 0 ]] )

Everything else remain the same.


LICENSE
=======

[PHP License](http://www.php.net/license/3_01.txt)




