# quoteService
Node.js service based on memoize feature for quick quotation

The following libraries are used:
- https://www.npmjs.com/package/fast-memoize
- https://www.npmjs.com/package/csv-parser
- https://www.npmjs.com/package/fastify

Way of working:
1) you update quote.csv file with parameters to be matched
2) based on that parameters memoization happens
3) memoization is wrapped with a Fastify web service
4) web service requires all fields which were provided with a csv
