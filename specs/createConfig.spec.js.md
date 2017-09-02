# Snapshot report for `specs/createConfig.spec.js`

The actual snapshot is saved in `createConfig.spec.js.snap`.

Generated by [AVA](https://ava.li).

## createConfig: basic

> Snapshot 1

    {
      context: '/parent_context/',
      entry: {
        animationStuff: [
          'pixi.js',
          'gsap',
        ],
        reactStuff: [
          'react',
          'react-dom',
        ],
      },
      output: {
        filename: '[name].js',
        library: '[name]_[hash]',
        path: '/.cache/fake-cache-dir/FAKE_ENV_instance_2_1c2416a464231cb8a54aab9155d721e6',
      },
      plugins: [
        DllPlugin {
          options: {
            name: '[name]_[hash]',
            path: '/.cache/fake-cache-dir/FAKE_ENV_instance_2_1c2416a464231cb8a54aab9155d721e6/[name].manifest.json',
          },
        },
      ],
    }