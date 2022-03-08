# Dummy weather prediction service

It is just a dummy/simple Helm Chart I use for testing. It is based on a [dummy/simple REST service](https://github.com/jgato/DummyWeather) that does pretty much nothing


## Values

I just allow to configure some values useful during my tests. I would add more in the future, as long as I add more templates

- The number of **replicas** of the service to be deployed.
- A message that will be stored on a ConfiMap and shared as an env variable into pods. The REST service then shows that message

