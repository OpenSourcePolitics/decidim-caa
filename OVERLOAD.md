# List of overloaded files for specific needs in this repository

## Add Deepl automatic translation
### Overrides 
- **app/services/deepl_translator.rb**
- **config/initializers/deepl.rb**
- **config/initializers/decidim.rb**
```ruby
  # Machine Translation Configuration
  #
  # Enable machine translations
  config.enable_machine_translations = true
  config.machine_translation_service = "DeeplTranslator"
```
### Tests 
- **spec/jobs/decidim/machine_translation_fields_job_spec.rb**
- **spec/jobs/decidim/machine_translation_resource_job_spec.rb**
- **spec/jobs/decidim/machine_translation_save_job_spec.rb**
