Performance on UI
Metrics 
- Load page time
	- zip/brottli
	- bundles
	- async load
- First content shown
	- parsing tyme - Ahead-of-Time compilation 
- First interaction with page
	- trick with collection events 

- Page interactions (each action should be less 200ms)
	- JS payload
		JS is one tread (v8 implementation)

		- Do less
			- avoid ngZones change detections
			- Observables
			- Filters 
			- workers 
		- Evaluate complexity O(n)
		- debounce
		- memo
	- DOM
		- avoid reflow, repaint
			- changes at once (virtula DOM, incremental DOM)
		- CPU to GPU
	- Memory leaks
		- GC 
		- closures (unsubscribe)


Practical exersize
	Billing 

Conclusion
	Customers 6M customers
	

https://www.mokkapps.de/blog/the-last-guide-for-angular-change-detection-you-will-ever-need/

https://mrale.ph/blog/2012/06/03/explaining-js-vms-in-js-inline-caches.html

https://www.youtube.com/watch?v=jvKGQSFQf10



