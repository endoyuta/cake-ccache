# cake-ccache

This is a tool to delete caches in the cache directory of cakephp.

- This delete files in `app/tmp/cache`.
- After deletion, This create an empty file named `empty` in` app/tmp/cache/models` and `app/tmp/cache/persistent` respectively.
- Before deleting, This check whether the above three directory paths exist.
- The execution location must be the parent directory of the app directory.

# LICENSE

This software is released under the MIT License, see LICENSE.txt.
