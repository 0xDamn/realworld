# Plan to do

## Part one: Telemetry System

1. Converting from `log/env_log` to `tracing/tracing_subscriber`.
2. Basic tracing setup:

- Tracing Side: setup http network tracing with `tower_http::TracingLayer`
   middleware; Sample handler tracing instrument for `async fn login_user()`;
- Subscriber Side: Setting up basic subscriber with `tracing_subscriber`
  in a separated module `telemetry`;  

3. TODO: Integrate the tracing data with `Opentelemetry`
4. TODO: Redesign the telemetry System for showing different network information.

---

## Part tow: CI/CD
