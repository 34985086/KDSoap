project(logbook_wsdl)

set(WSDL_FILES logbookifv3.wsdl)
set(logbook_wsdl_SRCS test_logbook_wsdl.cpp wsdl_logbookifv3.cpp)

set(EXTRA_LIBS ${QT_QTXML_LIBRARY})

add_unittest(${logbook_wsdl_SRCS} )
