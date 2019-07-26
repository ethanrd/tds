![TDS icon](https://www.unidata.ucar.edu/images/logos/thredds_tds-150x150.png)
<br>
<br>

## THREDDS Data Server (TDS)

The THREDDS Data Server (TDS) provides metadata and data access to scientific
datasets. Datasets can be served through OPeNDAP, OGC's WMS and WCS, HTTP, and other
remote data access protocols. It can be configured to aggregate a collection of
datasets so the collection is seen as a single dataset when viewed through the
various data access protocols. The TDS is a server-based system that can be easily
installed in any servlet container such as Apache Tomcat.

For more information about the TDS, see the TDS web page at

* https://docs.unidata.ucar.edu/tds/5.0.0/userguide/

You can obtain a copy of the latest released version of TDS software from

* https://www.unidata.ucar.edu/downloads/tds/

A mailing list, thredds@unidata.ucar.edu, exists for discussion of the TDS and
THREDDS catalogs including announcements about TDS bugs, fixes, enhancements,
and releases. For information about how to subscribe, see the
"Subscribe" link on this page

* https://www.unidata.ucar.edu/mailing_lists/archives/thredds/

We appreciate feedback from users of this package. Please send comments,
suggestions, and bug reports to <support-thredds@unidata.ucar.edu>.
Please identify the version of the package.

## THREDDS Catalogs

THREDDS Catalogs can be thought of as representing logical directories of on-line
data resources. They are encoded as XML and provide a place for annotations and
other metadata about the data resources. These XML documents are how THREDDS-enabled
data consumers find out what data is available from data providers.

THREDDS Catalog documentation (including the specification) is available at

* https://www.unidata.ucar.edu/software/thredds/current/tds/catalog/

## Licensing

The THREDDS Data Server is released under the BSD-3 licence, which can be found can be found [here](https://github.com/Unidata/tds/blob/master/LICENSE)

Furthermore, this project includes code from third-party open-source software components:
* [Gretty](https://github.com/akhikhl/gretty): for details, see `buildSrc/README.md`
* [JUnit](https://github.com/junit-team/junit4): for details, see `testUtil/README.md`

Each of these software components have their own license. Please see `docs/src/private/licenses/third-party/`.

## Previous releases

Prior to `v5.0.0`, the netCDF-Java/CDM library and the THREDDS Data Server (TDS) have been built and released together. Starting with version 5, these two packages have been decoupled, allowing new features or bug fixes to be implemented in each package separately, and released independently. Releases prior to `v5.0.0` were managed at <https://github.com/unidata/thredds>, which holds the combined code based used by `v4.6` and earlier.
