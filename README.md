# Elasticsearch Cookbook

This is the cookbook for the Elasticsearch instance within our infrastructure. The kitchencloud.yml completes this action on AWS, kitchen.yml can be used for local. Elasticsearch is a search engine that supports real-time search. This is extremely useful for viewing live metric data about our instances. It can also search through our nginx access and MongoDB logs. 

## Unit tests:

To start the unit test, run the command:

```
chef exec rspec spec
```

To run integration tests, run the command:

```
kitchen test
```

![Elasticsearch logo](https://i0.wp.com/www.thecuriousdev.org/wp-content/uploads/2018/01/Elasticsearch-Logo-Color-V.jpg.png?fit=3422%2C1781&ssl=1)

test