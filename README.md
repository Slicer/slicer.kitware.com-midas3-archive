# slicer.kitware.com (Midas3 archive)

This project is a snapshot of the data historically served from `http://slicer.kitware.com/midas3`.

## Archived Collections & Users

* `NA-MIC` collection historically available at `http://slicer.kitware.com/midas3/folder/298`

* Content of each user's `Public` folder have been archived in folder named accordingly.

* The files organized in the source tree are content link with extension matching the hash algorithm and the
  file content being the checksum (or hash).

* [Releases](https://github.com/Slicer/slicer.kitware.com-midas3-archive/releases) associated with this project
  are organized by hash algorithm and associated assets are named after the checksum.

## Metadata

A dictionary of file paths to metadata is stored in the [midas_metadata.json](./midas_metadata.json) file.

For each item, the available metadata are:

* `checksums`
  * `md5`
  * `sha256`
  * `sha512`
* `downloads`
* `views`
* `initial_revision_date`
* `latest_revision_item_url`
* `prior_revision_item_urls`

## Contributing

While this collection of datasets is **NOT** intended to be expanded, contributions to the associated documentation are welcome.

## Acknowledgments

The `slicer.kitware.com/midas3` server was hosted by Kitware using the Midas Platform.

This work was supported by NIH Grant 3P41RR013218-12S1, NA-MIC, NAC, and the Slicer community.

## License

The datasets historically available in the `NA-MIC` collection are distributed under the [3D Slicer Software License Agreement][3d-slicer-license-txt], a BSD-style open source license.

The datasets historically available in each user's `Public` folder may also be distributed under the `3D Slicer Software License Agreement`, re-using these datasets may require additional research.

To learn more, please see the `3D Slicer Software License Agreement`, see the [Slicer documentation][3d-slicer-license-doc].

[3d-slicer-license-txt]: https://github.com/Slicer/slicer.kitware.com-midas3-archive/blob/master/License.txt
[3d-slicer-license-doc]: https://slicer.readthedocs.io/en/latest/user_guide/about.html#license
