# Scale-UI  - Leader

_Scale UI_ is meant to manage an entire web site with different sub applications.

The sub applications will be managed in different git repos.

This system is useful for big web portal containing lots of applications and managed by different teams.

During CI/CD, the leader will download all sub applications and integrate in its tree folder.

Advantages :
 - One security for all apps
 - One global styling
 - One global deployment
 - One global monitoring
 - Reusable leader components/assets
 - Very fast new app creation !

Difficulties :
 - One global package.json, sub applications must follow new deps versions
 - Keep small amount of dependencies

