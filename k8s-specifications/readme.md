added the temporary fix
https://github.com/dockersamples/example-voting-app/issues/162
as in the comment here
https://github.com/dockersamples/example-voting-app/issues/162#issuecomment-636432631
    ` - name: POSTGRES_HOST_AUTH_METHOD `
    `   value: trust`
    
    
WARNING: POSTGRES_HOST_AUTH_METHOD has been set to "trust". This will allow
anyone with access to the Postgres port to access your database without
a password, even if POSTGRES_PASSWORD is set. See PostgreSQL
documentation about "trust":
https://www.postgresql.org/docs/current/auth-trust.html
