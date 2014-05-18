yql_query_tool
==============

a simple node tool to execute YQL queries

get yahoo answers questions about horses that have been resolved


/yql --query 'select * from answers.search where query="horse"  and type="resolved"'


and syntax highlight it


/yql --query 'select * from answers.search where query="horse"  and type="resolved"' --color

