gpx2tcx
=======

Combine gpx and hrm fles to trc

This application is forked from 

http://colby.id.au/combining-gpx-and-hrm-files/

Usage

    gawk -f gpx2tcx.awk [-v ALTITUDE=1.0] -v HRMFILE=file.hrm file.gpx > file.tcx

Change log

    v1.0.0  Fork from Colby's version
    v1.1.0  Added single-line note capability
    v1.1.1  Added multi-line note capability
