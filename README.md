linter-template
=========================

This linter template is a [Linter](https://github.com/AtomLinter/Linter) plugin boilerplate you can use to start the development of your own, it provides an interface to `dummy` external tool and it will be used with files that have the “Dummy” syntax.

## Installation
Clone the repo, now you can start the development of your new linter plugin.

### Testing your package
If you need to check your plugin
1. Go to your project root directory

2. Link your plugin to Atom
   ```
   apm link
   ```
3. You can always remove your plugin from Atom whe you finished your development
   ```
   apm unlink
   ```

Now you can reload Atom `Command palette -> Window: Reload` to start using and debugging your plugin.
