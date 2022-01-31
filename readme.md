## Changelog

Currently this fork of the main plugin adds two hooks into the main plugin code. The details are as follows:

### Filter
1. **duplicate_page_new_post_args** (Array $args, WP_Post $post)

Run before new post is created with the args, the args are supplied to this filter so can be changed before the new post is created.


### Action
1. **duplicate_page_after_post_duplicate**(Int $new_post_id, Int $source_post_id)

Fires after the new duplicate post is created and before the post metas are created, argument contains the newly created post id and the source post's id from which the duplication is done.

1. **duplicate_page_finished_post_duplicate**(Int $new_post_id, Int $source_post_id)
Fires after the new duplicate post is created and the post metas are also duplicated, argument contains the newly created post id and the source post's id from which the duplication is done.

### Original Credits remain intact to the author: 

- mndpsingh287
- https://profiles.wordpress.org/mndpsingh287/


**Contributed by:**
Umair Akram
https://github.com/meumairakram
