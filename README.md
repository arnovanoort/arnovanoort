👋 Hi, I’m @arnovanoort<br/>
I use this repository to expiriment with new techiques/frameworks.
- stock-reader imports stock data into a local database. It is an excuse to build a fully non blocking application using Spring/webflux/R2DBC
- stock-trading-algorithms uses the data gathered by stock reader and implements different strategies buying stocks. It is build up using Kotlin and the exposed framework.
- stocks-k8 contains the configuration to deploy the previous 2 services onto a kubernetes cluster
- stocks-terraform-aws builds on that and will set up the complete environment on AWS(k8s deployments with loadbalancers, and the postgres databases all tied together.)
