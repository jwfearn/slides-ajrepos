#HSLIDE
## Ad Product repos
- Database Services
- Integration Services
- Libraries
- Web Apps


#HSLIDE
## Database API Services
- account (users)
- gnomon (geo data, sales regions)
- ledger
- quasi (quotes)
- solicitor (attorney data, practice areas)
- soca (sales cart checkout?)
- barrister?


#HSLIDE
## Integration Services
- `billboard` (serves ads to web & mobile clients)
- `stanger_forces` (links our dbs with Salesforce)
- `pbx` (telephone call API using Twilio)
- `nrt` (used for EDW, phasing out in favor of Kafka)


#HSLIDE
## Libraries
- Avvo
- Forks


#HSLIDE
## Avvo Libraries
- `avvo_ex_works` (like `avvo_app_works` but for Elixir)
- `meta_pid`, `meta_pid_request` (process management libs in Elixir)
- Events


#HSLIDE
## Events
- `avvo_events`
- Kafka Event Contracts in Avro
- Avro is an Apache standard schema definition language
- `*.avdl` (source files)
- `*.avpr` (output files for protocols)
- `*.avsc` (output files for schemas)
- `avrolixir` (Avro encode/decode, wraps erlavro)


#HSLIDE
## Service Bindings in Elixir
- `avro_http_client_generator`
Queries Webster API and generates Elixir client bindings
- `*_client_ex (generated)`


#HSLIDE
## Forked Libraries
- erlavro (fork: an Avro API in Erlang)


#HSLIDE
## Web Apps
- banana_stand (aka "Sales Tool")
- kafkamon (in-house Kafka monitoring utility, written in Elixir)
- tps (Tomahawk Pricing Service)


#HSLIDE
## Obsolete
- franz_force (replaced by stranger_forces)
- eavro (fork: an Avro API in Erlang, no longer used)
- ex_avro (fork: an Avro API in Elixir, no longer used)
- kafka_ex (fork no longer used)
- salesforce-migration
- ex_quasi (experimental Elixir version of Quasi)
- admon (ad product dashboard, unfinished)


#HSLIDE
## Q & A


<!--
# TODO
stargate
billy_mays (replaced by billboard)
switchboard (APIs called by Salesforce)
shippable
*_kafka_consumer?
kafka_impl (share w/Leslie)
-->
