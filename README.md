This template uses a text-based configuration file in YAML standards which is read with Autossential.Configuration.Activities package resulting in a ConfigSection object which is more rich in terms of features than a Dictionary object.

This specific version of the framework take advantage on the global variable available natively from UiPath to keep the configuration data, this will help accelerate the development by skipping the necessity to pass the config variable through an argument in every flow that is needed.

* SAMPLE CODE *

This template comes with a sample code embedded. Just run it and see the results on Data\Sample.csv
Before start using this template for your project, please make sure to remove the sample code (marked with "Remove Me") on the following files:

- Framework\Process\Consumer.xaml
- Framework\Process\Producer.xaml
- Framework\Actions\Events\OnTransactionComplete.xaml