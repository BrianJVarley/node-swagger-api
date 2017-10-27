> An example Epxress node.js service running with swagger-jsdoc to provide api description.
> Forked from  mjhea0/node-swagger-api.


| Details        | Route    |
| ------------- |:-------------:| 
| API Description  |  http://localhost:3000/api-docs/ | 


## Build and Run (Ubuntu)

1. cd to `node-swagger-api`
2. `sudo -u postgres psql -f puppies.sql` (creates the table)
2. npm start
3. Browse to `http://localhost:3000/api/`

## Troubleshooting

error: `psql: command not found`
solution: follow installation guide for postgresdb
