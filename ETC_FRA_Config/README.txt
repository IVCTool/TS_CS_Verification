To use this example

1) Set the global variables:

1.1) IVCT_CONF   to the absolute path of the folder where the   IVCTconfig.xml   file is located.

1.2) IVCT_HOME   to the absolute path of the   IVCT_Framework   folder (inclusive).

1.3) IVCT_TS_HOME   to the absolute path of the folder where the test suite sources (parent folder of e.g. TS_HelloWorld, TS_NETN_2.0 or TS_RPR_FOM_2.0) are located.


2) Edit the   IVCTconfig.xml   file to set the absolute path of the sutDir folder.

The   sutDir   contains the SUT folders where the SUT specific files are loaded e.g. the   TcParam.json   describing the SUT specific values that will be used in the test cases. The IVCT will, when implemented, write the log files and summary reports into the specific SUT\testsuite\log folder.

The   testSuites   folder contains a   IVCTtestsuites.xml   file listing the currently valid testsuites. Older or newer testsuites may located in this folder, but are not visible to the IVCT unless included in the   IVCTtestsuites.xml   file. For each test suite, the badges (test schedules) are located in test suite specific folders.

3)  Move the IVCTtestsuites.xml  to the absolute path pointed by IVCT_TS_HOME variable
