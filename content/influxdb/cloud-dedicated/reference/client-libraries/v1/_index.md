---
title: InfluxDB v1 client libraries
description: >
  InfluxDB v1 client libraries use the InfluxDB 1.7 API and should be fully compatible with InfluxDB 1.5+.
  View the list of available client libraries.
menu:
  influxdb_cloud_dedicated:
    weight: 201
    name: v1 client libraries
    parent: Client libraries
influxdb/cloud-dedicated/tags: [client libraries, API, developer tools]
---

InfluxDB client libraries are language-specific tools that integrate with InfluxDB APIs.
Client libraries for InfluxDB v1 work with the InfluxDB 1.7 API and should be fully compatible with InfluxDB 1.5+.

{{% note %}}
We highly recommend upgrading to InfluxDB 1.8 to use new client libraries compatible with both InfluxDB 1.8 and InfluxDB 2.0. For more information, see [InfluxDB client libraries](/influxdb/v1.8/tools/api_client_libraries/).
{{% /note %}}

Functionality varies among client libraries.
These client libraries are in active development and may not be feature-complete.

For specifics about a client library, see the library's GitHub repository.

## C++
* [influxdb-cxx](https://github.com/offa/influxdb-cxx)
  * Maintained by [offa](https://github.com/offa)

## Elixir

* [Instream (instream)](https://github.com/mneudert/instream)
  * Maintained by [Marc Neudert (mneudert)](https://github.com/mneudert)

## Erlang

* [Erlang InfluxDB UDP Writer](https://github.com/palkan/influx_udp)
  * Maintained by [Vladimir Dementyev (palkan)](https://github.com/palkan)
* [InfluxDB line encoder](https://github.com/Pouriya-Jahanbakhsh/influxdb_encoderl)
  * Maintained by [Pouriya Jahanbakhsh](https://github.com/Pouriya-Jahanbakhsh)

## Go

* [InfluxDB Client](https://github.com/influxdata/influxdb1-client)
  * Maintained by [InfluxData](https://github.com/influxdata)

## Haskell

* [influxdb-haskell](https://github.com/maoe/influxdb-haskell)
  * Maintained by [Mitsutoshi Aoe (maoe)](https://github.com/maoe)

## Java

* [influxdb-java](https://github.com/influxdb/influxdb-java)
  * Maintained by [Stefan Majer (majst01)](https://github.com/majst01)
* [Alpakka InfluxDB](https://doc.akka.io/docs/alpakka/current/influxdb.html)
  * Maintained by the Alpakka community with help from [Lightbend](https://www.lightbend.com/)
* [JFlux](https://github.com/nickRm/jflux)
  * Maintained by [Nick Rammos (nickRm)](https://github.com/nickRm)

## JavaScript/Node.js

* [node-influx](https://github.com/node-influx/node-influx)
  * Maintained by [Ben Evans (bencevans)](https://github.com/bencevans) and [Connor Peet (connor4312)](https://github.com/connor4312)

## Lisp

* [CL-INFLUXDB](https://github.com/mmaul/cl-influxdb)
  * Maintained by [Mike Maul (mmaul)](https://github.com/mmaul)

## MATLAB

* [influxdb-matlab](https://github.com/EnricSala/influxdb-matlab)
  * Maintained by [Enric Sala (EnricSala)](https://github.com/EnricSala)

## .Net

* [InfluxDB.Client.Net](https://github.com/AdysTech/InfluxDB.Client.Net)
  * Maintained by [Adarsha (mvadu)](https://github.com/mvadu)
  * Supports .Net and .Net Core
* [InfluxData.Net](https://github.com/pootzko/InfluxData.Net)
  * Maintained by [Tijhomir Kit (pootzko)](https://github.com/pootzko)
* [InfluxDB Client for .NET](https://github.com/MikaelGRA/InfluxDB.Client)
  * Maintained by [Mikael Guldborg Rask Andersen (MikaelGRA)](https://github.com/MikaelGRA)
* [InfluxClient](https://github.com/danesparza/InfluxClient)
  * Maintained by [Dan Esparza (danesparza)](https://github.com/danesparza)

## Perl

* [AnyEvent::InfluxDB](https://github.com/ajgb/anyevent-influxdb)
  * Maintained by [Alex Burzyński (ajgb)](https://github.com/ajgb)
* [InfluxDB-LineProtocol](http://search.cpan.org/~domm/InfluxDB-LineProtocol/)
  * Maintained by [Thomas Klausner (domm)](https://domm.plix.at/)
* [InfluxDB::HTTP](https://github.com/raphaelthomas/InfluxDB-HTTP)
  * Maintained by [Raphael Seebacher (raphaelthomas)](https://github.com/raphaelthomas)

## PHP

* [influxdb-php](https://github.com/influxdb/influxdb-php)
  * Maintained by [TheCodeAssassin (thecodeassassin)](https://github.com/thecodeassassin) and [Gianluca Arbezzano (gianarb)](https://github.com/gianarb)
* [InfluxDB PHP SDK (influxdb-php-sdk)](https://github.com/corley/influxdb-php-sdk)
  * Maintained by [Corley (corley)](https://github.com/corley)

## Python

* [InfluxDB-Python (influxdb-python)](https://github.com/influxdb/influxdb-python)
  * Maintained by [Alexandre Viau (aviau)](https://github.com/aviau), [xginn8](https://github.com/xginn8), and [Sebastian Borza (sebito91)](https://github.com/sebito91)

## R

* [influxdbr](https://cran.r-project.org/web/packages/influxdbr/)
  * Maintained by [Dominik Leutnant (dleutant)](https://github.com/dleutnant)

## Ruby

* [influxdb-ruby](https://github.com/influxdb/influxdb-ruby)
  * Maintained by [Todd Persen (toddboom)](https://github.com/toddboom) and [Dominik Menke (dmke)](https://github.com/dmke).
* [Influxer (influxer)](https://github.com/palkan/influxer)
  * Maintained by [Vladimir Dementyev (palkan)](https://github.com/palkan).

## Rust

* [Flux (flux)](https://crates.io/crates/flux)
  * Maintained by [Chris Holcombe (cholcombe973)](https://crates.io/users/cholcombe973) and [Chris MacNaughton](https://crates.io/users/ChrisMacNaughton)
* [Influent (influent)](https://crates.io/crates/influent)
  * Maintained by [gobwas](https://crates.io/users/gobwas) and [Eijebong](https://crates.io/users/Eijebong).

## Scala

* [scala-influxdb-client](https://github.com/paulgoldbaum/scala-influxdb-client)
  * Maintained by [Paul Goldbaum (paulgoldbaum)](https://github.com/paulgoldbaum)
* [chronicler](https://github.com/fsanaulla/chronicler)
  * Maintained by [Faiaz Sanaulla (fsanaulla)](https://github.com/fsanaulla)
* [Alpakka InfluxDB](https://doc.akka.io/docs/alpakka/current/influxdb.html)
  * Maintained by the Alpakka community with help from [Lightbend](https://www.lightbend.com/)

## Sensu

* [sensu-influxdb-extension](https://github.com/jhrv/sensu-influxdb-extension)
  * Maintained by [Johnny Horvi (jhrv)](https://github.com/jhrv)

## SNMP agent

* [SnmpCollector (snmpcollector)](https://github.com/toni-moreno/snmpcollector)
  * Maintained by [Toni Moreno (toni-moreno)](https://github.com/toni-moreno).
  * A full featured Generic SNMP data collector with Web Administration Interface for InfluxDB.
