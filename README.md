# SoundCloud plugin for Jekyll

Helps you embed stuff from soundcloud more easily to your Octopress.

## How to use it?

There are 2 easy steps.

1. Add ```soundcloud.rb``` to your ```plugin``` folder.
2. Now you can easily embed sounds using the ```type``` and ```id``` or you can simply use the ```url```:

```markdown
# Soundcloud example 1 (uses type and id)

{% soundcloud tracks 55172922 [option=value [option=value [...]]]%}

# Soundcloud example 2 (uses url)

{% soundcloud https://soundcloud.com/marinelli/fort-knox-five-presents-funk [option=value [option=value [...]]]%}
```

## Kudos

Thanks go to [Nick Fisher](http://spadgos.github.com) for imeplenting the first version of this plugin for his blog.