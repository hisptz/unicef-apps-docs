## 2.6 Standard data analytics

Data which is entered into DHIS2 must first be processed with the DHIS2 “analytics” engine. This means that data is not immediately available in the analytics resources (such as the BNA chart, sub-org unit level analysis tables, pivot tables, data visualizer, GIS or report) after it has been entered. If scheduling is active, the analytics process will run automatically at the scheduled time. After that, new data which was entered since the last time the analytics process ran, will become visible.

You can trigger the analytics process manually by selecting Data Administration->Analytics Tables from the main menu and pressing the “Start export” button. Note, the process may take a significant amount of time depending on the amount of data in your database.

## 2.7 Functions data analytics

Functions selections are extended analytics calculations supporting a more open-ended logic of computation, such as logical operations, predictors and other complex analytics use cases. To create functions to work with BNA App, download the function maintenance application from this link: https://play.dhis2.org/appstore/app/dXX2Fk6jwCX. The Function maintenance application makes use of pure good old JavaScript(vanilla JavaScript) logic to do calculations purely on the browser, without the need for a server. This is accomplished by execution of JavaScript codes that expect period and data selections and return standard DHIS2 analytics results.

## 2.8 Maintenance of functions

Functions comprises of three key building blocks:

    i)Input/Selection parameters: Function expects standard DHIS2 periods and organization units selections.

    ii)Computation logic: This is an open-ended workspace for writing of calculation logic to work on given period and organization unit selections, computation logic is usually classified into rules dimensions, thus allowing one function to support different use cases by defining multiple rules that will control the computation logic. Possibilities are limitless, among major operations done includes.

        A.Fetching data from aggregate and event analytics and modifying results with custom logic, and reformatting the results back in standard analytics format.

        B.Fetching data from existing sql Views, performing custom logics and formatting results in standard analytics format.

        C.Fetching data from other DHIS2 API endpoints(such as data-value and events api) and other data sources (including external sources), performing custom logic and formatting results in standard analytics format.

    iii)Output/Returned analytics: This is the end-result output from functions, formatted in 	standard analytics format, to allow compatibility with standard DHIS2 analytics applications. To support open-ended support for any level of complexity, function maintenance application has been developed, to allow any developer with basic JavaScript knowledge to quickly develop custom calculations either not supported natively by DHIS2 or to allow developers to work-around limitations or miscalculations from standard analytics.

Main requirements for the developing functions includes:

    > Basic web programming knowledge with JavaScript (jQuery is an advantage).

    > Understanding of DHIS2 Web API and analytics.

    > A working installation of Functions maintenance application. When a function maintenance application is installed for the first time, it creates five standard functions  with generic use cases as example functions to allow reuse of codes to create other functions. The auto created functions will also be listed in the functions selection list.
