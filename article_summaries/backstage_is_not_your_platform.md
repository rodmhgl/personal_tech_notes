# Backstage is not your platform - PlatformEngineering.org (Humanitec) Webinar

## Platform Engineering is tough, but game changing

39% average return on investment / 63% faster time to market. 

[Netflix's experience](https://www.youtube.com/watch?v=36FcxlPerdQ) revealed that after 2 years, "the 'view and asses' experience provides value but on its own is not yet complelling enough to pull users in, away from existing habits and routines."

This experience reveals shortcomings with Netflix's approach, as the goal isn't to change habits but to meet the developers where they are and focus on their needs. 

Platform Engineering is about achieving greater efficiency and requires more than just placing Backstage on top of existing systems. This fails to achieve [Pareto efficiency](https://en.wikipedia.org/wiki/Pareto_efficiency), where an outcome is better in every way. The bloat of the platform should not intefere with the developers ability to operate the platform. PEs should always strive for Pareto efficiency. The impact should be greater than the pain. 

Platform Engineering teams are often heavy with Infra and Ops engineers but are designed with DevEx in mind. For success PE efforts, it must be viewed as a multi-discipline effort. 

In studies, successful PE teams tend to be balanced between Infra and DevEx resources. To achieve the highest return on investment, it is essential to embrace standardization and automation. 

In a low-automation example where Redis is added to a workload, GHA + Terraform can create Redis and then the Developer is responsible for updating app configs, checking policies, run sign-off, secret references, and then repeat for each env. A high degress of automation would implement business logic to perform all of the tasks for the developer. 

In a low-standardization environment, you may have 5 workloads each using 5 redis configs. Ideally, all 5 workloads would use the redis config unless there was a very strong driver for a variant. 

Backstage/UI is only one interface (of many possible) to your Platform. For successful adoption, you must meet the developers where they are. Developers accustomed to a CLI are not likely to switch to a UI experience. 

Humanitec Platform Orchestrator is a graph-based backend for Platform Engineering. It allows a developer to define a workload specification and deploy that specification using resource configs written by Platform Engineers. 

Golden Paths for devs, Infra and Ops, and security teams drive automation and standardization. 
