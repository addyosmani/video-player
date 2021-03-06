# &lt;video-player&gt; ![Bower version](https://badge.fury.io/bo/video-player.svg)

> A Polymer video player element

## Demo

[Check it live!](http://addyosmani.github.io/video-player)

## Usage

1. Install the component using [Bower](http://bower.io/):

    ```sh
    $ bower install video-player --save
    ```

2. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

3. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/video-player/dist/video-player.html">
    ```

4. Start using it!

    ```html
    <video-player></video-player>
    ```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`width`     | *integer*                  | `320`             | Width of the video
`height`     | *integer*                  | `240`             | Height of the video
`theme`     | *string*                  | `red`             | Which of the built-in themes to use (red/blue/green)

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

1. Install [Bower](http://bower.io/) & [Grunt](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g bower grunt-cli
    ```

2. Install local dependencies:

    ```sh
    $ bower install && npm install
    ```

3. To test your project, start the development server and open `http://localhost:8000`.

    ```sh
    $ grunt
    ```

4. Once you finish developing it, build the distribution files and publish it on Bower.

    ```sh
    $ grunt build
    $ bower register video-player https://github.com/you/video-player
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/addyosmani/video-player/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
