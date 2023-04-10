# hasura-graphql-engine

Hasura graphql-engine packages extracted from oficial hasura docker

Hasura is an open source project. See oficial repository here: https://github.com/hasura/graphql-engine


## Instructions

```sh
git clone --branch v2.22.1 https://github.com/iMDT/hasura-graphql-engine.git
cat hasura-graphql-engine/hasura-graphql.part-a* > hasura-graphql 
rm -rf hasura-graphql-engine/
chmod 755 hasura-graphql
./hasura-graphql version
```

