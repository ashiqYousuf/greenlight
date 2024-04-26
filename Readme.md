# Greenlight :- A dumb open source movies API

<hr>

##### Requirements:

* Install Go version >= 17 (https://go.dev/doc/install)

* Postgres as database (https://www.postgresql.org/download/)

* Install Deps using `go get`

* Replicating env, run the following command to check for command line variables:-

`
./bin/api -help
`

* The Makefile in the root directory of the project will guide you for configuration. Run the following command, make sure you are in the root dir (greenlight):-
<br><br>
`
make help
`

* Add the following variables to your .envrc file (in the root dir):-

export GREENLIGHT_DB_DSN=postgres://user:password@host/db

export SMTP_HOST=sandbox.smtp.mailtrap.io (any mail hosting service)

Add the following credentials from your smtp service provider

export SMTP_USER=2yr23fhfkjnfk

export SMTP_PASSWORD=wndlfn3j2oi2

export SMTP_PORT=2525
