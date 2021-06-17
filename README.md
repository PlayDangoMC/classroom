<p align="right">
    <p>Distributed exclusively by fnageer.ml.</p>
</p>
<br><br>
<p align="center">
    <img align="center" src="title-white.png" />
    <!--<h1 align="center">Just the Docs</h1>-->
    <p align="center" id="changeText" style="color:black">There Is An Error In The Site Code.</p>
    <p align="center"><strong><a href="https://pmarsceill.github.io/just-the-docs/">See it in action!</a></strong></p>
    <br><br><br>
</p>
    <script>
        var text = ["Survival", "Survival", "Survival", "Survival", "Survival", "Survival", "Survival", "Survival", "Survival", "Survival", "Surviva", "Surviv", "Survi", "Surv", "Sur", "Su", "S", " ", "P", "Po", "Poc", "Pock", "Pocke", "Pocket ", "Pocket E", "Pocket Ed", "Pocket Edi", "Pocket Edit", "Pocket Editi", "Pocket Editio", "Pocket Edition", "Pocket Edition", "Pocket Edition", "Pocket Edition", "Pocket Edition", "Pocket Edition", "Pocket Edition", "Pocket Edition", "Pocket Edition", "Pocket Edition", "Pocket Editio", "Pocket Editi", "Pocket Edit", "Pocket Edi", "Pocket Ed", "Pocket E", "Pocket ", "Pocket", "Pocke", "Pock", "Poc", "Po", "P", " ", "P", "PV", "PVP", "PVP", "PVP", "PVP", "PVP", "PVP", "PVP", "PVP", "PVP", "PVP", "PV", "P", " ", "R", "Ra", "Rai", "Raid", "Raidi", "Raidin", "Raiding", "Raiding", "Raiding", "Raiding", "Raiding", "Raiding", "Raiding", "Raiding", "Raiding", "Raiding", "Raidin", "Raidi", "Raid", "Rai", "Ra", "R", " ", "P", "PV", "PVE", "PVE", "PVE", "PVE", "PVE", "PVE", "PVE", "PVE", "PVE", "PVE", "PV", "P", " ", "J", "Ja", "Jav", "Java", "Java", "Java", "Java", "Java", "Java", "Java", "Java", "Java", "Java", "Jav", "Ja", "J", " ", "B", "Be", "Bed", "Bedr", "Bedro", "Bedroc", "Bedrock", "Bedrock", "Bedrock", "Bedrock", "Bedrock", "Bedrock", "Bedrock", "Bedrock", "Bedrock", "Bedrock", "Bedroc", "Bedro", "Bedr", "Bed", "Be", "B"];
        var counter = 0;
        var elem = document.getElementById("changeText");
        setInterval(change, 100);
        function change() {
            elem.innerHTML = text[counter];
            counter++;
            if (counter >= text.length) { counter = 0; }
        }
    </script>

![jtd](https://user-images.githubusercontent.com/896475/47384541-89053c80-d6d5-11e8-98dc-dba16e192de9.gif)

## Installation

Add this line to your Jekyll site's Gemfile:

```ruby
gem "just-the-docs"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: just-the-docs
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install just-the-docs

Alternatively, you can run it inside Docker while developing your site

    $ docker-compose up

## Usage

[View the documentation](https://pmarsceill.github.io/just-the-docs/) for usage information.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/pmarsceill/just-the-docs. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

### Submitting code changes:

- Open a [Pull Request](https://github.com/pmarsceill/just-the-docs/pulls)
- Ensure all CI tests pass
- Await code review
- Bump the version number in `just-the-docs.gemspec` and `package.json` according to [semantic versioning](https://semver.org/).

### Design and development principles of this theme:

1. As few dependencies as possible
2. No build script needed
3. First class mobile experience
4. Make the content shine

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is set up just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When the theme is released, only the files in `_layouts`, `_includes`, and `_sass` tracked with Git will be released.

## License

The theme is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
