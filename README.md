# todoMVC code optimization

## Contribution to todoMVC.com 

Optimization of todoMVC project with attention to DOM/render-tree optimization, and MVC architecture to ensure proper decoupling of Model View and Controller components

Optimizations have resulted in performance increase of 20-50 fold over existing code base in both Developer Tools and performanceNow() calculated methodologies

For performanceNow() testing method, see js/performacetimer.

To use performanceNow: function start(name of timer: string);
call get recorded time and output time to console: call stop();

Multiple simultaneous times are currently not possibe but can be added.
