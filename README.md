# Lab8-Starter

## Lab Partner(s)
- Yannis Smith (solo)

## Deployed GitHub Pages URL
https://ywreckz.github.io/Lab8_Starter/

## Graceful Degradation and Service Workers
Graceful degradation is the practice of building an application with full functionality first, then ensuring it still works at a basic level when certain features are unavailable. Service workers are a perfect example of this in action — when a user has no internet connection, the service worker intercepts network requests and serves cached resources instead, allowing the app to continue functioning offline. Without the service worker, the app would simply fail to load. With it, users get a degraded but still usable experience, which is exactly what graceful degradation aims for.
