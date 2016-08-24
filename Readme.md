# DRF Dynamic Model Serializer [WARNING IN DEVELOPMENT]

## Intro

Dynamic model serializer designed to create more dynamic REST.
Despite spherical REST in vacuum works with the full models,
very often it's really inconvenient to fetch from database and pass to user
the full instance. It leads to overhead or to having multiple views with different
attribute sets.
Having ability to specify REST endpoint which attributes to return on demand, allows
us to reuse same endpoint in different cases. In some manner it's a simple replacement
of GraphQL.

## Installation

```code
pip install rest_framework_dyn_serializer
```