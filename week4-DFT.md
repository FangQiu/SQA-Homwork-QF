#Group A How to use DFT in synchronization testing?
In synchronization testing, we would combine the above two conditions to test the individual tasks executed in parallel in all different arriving orders, and to check for the correct outcome. The testing of the correct handling of such synchronizations involves two elements:
* Correct result is obtained or appropriate processing is applied for given inputs. One special case for this is that no result should be produced or no processing should be applied if we do not have all the tasks available.
* Synchronization of arrivals among tasks in all possible orders, including time ordered arrivals as well as the possibility of one or more tasks arriving at exactly the same time.
