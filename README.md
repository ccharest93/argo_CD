Example of how to keep ARGO CD templates in a version controlled way, independently from their configurations. Configurations can then be reffered to using github tags, allowing for version control and separation of production and development configurations.

Changes to the configuration files can be used to make the argocd container reload the deployments with the correct configurations.
