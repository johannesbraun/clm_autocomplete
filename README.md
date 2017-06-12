http://localhost:8983/solr/olx/spell?df=query&spellcheck.q=zakati&spellcheck=true&spellcheck.collateParam.q.op=AND&wt=json

http://localhost:8983/solr/popular_queries/select?q=query_ngram:za&%20sort=product(popularity,reply_conversion,pow(strdist(%22za%22,query,ngram),2))%20desc&rows=10&fl=query&wt=json&fl=query,popularity,reply_conversion,research_quote,first_cat_name,second_cat_name,second_cat_significance,first_cat_significance,product(popularity,reply_conversion,pow(strdist(%22za%22,query,ngram),2)),strdist(%22za%22,query,ngram),pow(strdist(%22za%22,query,ngram),2),score&debugQuery=on
