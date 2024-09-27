# err-trace
> 前端监控稳定性

## 介绍

`err-trace` 是一套专注于前端稳定性监控的解决方案，旨在通过对页面性能、用户行为、接口调用、以及前端异常等情况的监控，帮助团队及时发现和解决潜在问题。我们通过无埋点的监控方式，减少开发者的负担，快速捕获用户体验中的异常数据。

### 项目目标：
1. **提升用户体验**：通过监控性能和错误，优化系统稳定性和用户体验。
2. **快速问题定位**：提供问题复现线索，加速排查与修复流程。
3. **降低维护成本**：减少因系统不稳定带来的维护成本，帮助团队专注于功能开发。

## 功能特点

- **页面性能监控**：涵盖加载耗时、关键性能指标（如 FCP、LCP、CLS）。
- **用户行为追踪**：包括 PV、UV、访问路径、路由跳转等。
- **接口请求监控**：捕获 HTTP 接口的请求耗时、成功率等数据。
- **异常监控**：自动捕捉前端代码运行中的错误与异常。
- **数据上报优化**：通过批量上报、延迟上报等策略减少性能开销。

## 前端监控 npm 包
   1. [@err-trace/browser](https://www.npmjs.com/package/@err-trace/browser)：前端稳定性监控 页面监控；
   2. [@err-trace/core](https://www.npmjs.com/package/@err-trace/core)：前端稳定性监控 核心功能；
   3. [@err-trace/react](https://www.npmjs.com/package/@err-trace/react)：前端稳定性监控 React 监控；
   4. [@err-trace/vue](https://www.npmjs.com/package/@err-trace/vue)：前端稳定性监控 Vue 监控；
   5. [@err-trace/web](https://www.npmjs.com/package/@err-trace/web)：前端稳定性监控 Web 监控；
   6. [@err-trace/web-performance](https://www.npmjs.com/package/@err-trace/web-performance)：前端稳定性监控 Web 性能监控；