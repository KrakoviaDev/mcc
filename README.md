All available 3 character/letter Minecraft names
=====

This is a small clojure script that queries the Minecraft API to test for all available 3 character names.

The found playernames are in *available-now.txt* (currently available names) and *soon-available.txt* (not currently in use but still under the 37 day protection.) Do note that these lists are NOT automatically updated, but instead show which names were available when the script was last run. If you've got a newer copy of these lists, feel free to submit a pull request.

The old get-names.sh script is included as well, it should still work but is significantly slower (requiring over 100k requests to the Minecraft API compared to about 20k for get-names.clj)
