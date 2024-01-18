## Using the automatic plugin installer

When you enable the "Install Custom Plugins" variable in the startup tab and after installation go to the `.egg` file in your root directory and you will see a file called `customplugins.txt`
You can put the Github link to any plugin in there, one per line but it must be in the correct format (see below) for it to work.

Note: This will not work for NWApi plugins, though there is a way to automatically install/update plugins using Northwood's built in plugin manager which you can access by using the `p` command.

### Format
```
https://api.github.com/repos/<PLUGIN-AUTHOR>/<REPO-NAME>/releases/latest
```

### Example for [BetterScp939](https://github.com/iopietro/BetterScp939)
```
https://api.github.com/repos/iopietro/BetterScp939/releases/latest
```

### ⚠️**WARNING**⚠️
If you need to make more than
 60 GitHub requests in an hour you NEED to use authentication or else the installation could possibly fail leaving you with a failed install state!
Each install/reinstall makes at least one request to check the egg version and one request per plugin that you add in so if you add 19 plugins and reinstall a few times within a short time frame it _will_ rate-limit you.

![Failed Install State](https://media.discordapp.net/attachments/867104159907840031/867106088767062027/unknown.png)

## How to use authentication

You should authenticate because it allows you to make up to _5000_ GitHub requests per hour as well as letting you download from private repos.

In order to use authentication all you need to do is fill out your GitHub username and Access Token in the startup configuration.
You can find a tutorial on how to get a token [here](https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token).

It is important to follow the [principle of least privilege](https://en.wikipedia.org/wiki/Principle_of_least_privilege) and only grant the permissions it needs. 
In this case you don't need to add any scopes because we are just validating we are a user.|

If you would like to dowload from private repositories you need to give private repo scopes to your access token.
![image](https://user-images.githubusercontent.com/68636315/142776718-e0107ced-b4c7-4170-9a49-11023aef646d.png) 
