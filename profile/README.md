# **🚀 DartZen: The Simple, Balanced Core Foundation for Dart & Flutter**

<img width="3200" height="420" alt="DartZen banner wide" src="https://github.com/user-attachments/assets/c3eacbaf-7316-4d5c-8999-0d8165dac514" />

## **🎯 Motivation: Why DartZen?**

In the vast landscape of application development, choosing the right foundation is crucial. While available solutions offer comprehensive full-stack Dart, and minimalist templates provide barebones starts, we recognized a unique gap: the need for a **simple, balanced, and opinionated core foundation** that embraces the full power of the **Google ecosystem** — without inheriting the hidden server-side execution pitfalls common to event-loop-based architectures.

DartZen was created to eliminate the common friction points in Dart & Flutter development. We bridge the gap between overly simplistic "hello world" projects and overly complex, bloated frameworks. Our motivation is to provide developers with a ready-to-use, optimized foundation that encourages best practices, streamlines integration with Google's powerful cloud services, and allows teams to focus on delivering value, not boilerplate.

If you're building with Dart & Flutter and value simplicity, seamless Google integration, and a clear architectural path, DartZen is your answer.

## **💡 Project Overview**

**DartZen** is your go-to core starter kit for building high-quality, scalable, and maintainable applications with Dart and Flutter. It provides a robust, yet minimalist, architectural foundation that fosters a clear, composable structure that scales without ceremony. By design, DartZen offers deep, seamless integration with Google Cloud Platform (GCP) and Firebase, ensuring a cohesive and efficient development experience from frontend to backend. We've crafted this kit to accelerate your project's launch while providing the stability and simplicity needed for long-term success, allowing you to "Build with Zen."

## **✨ Key Principles**

Our strategic decisions and development philosophy are guided by these core principles, ensuring DartZen remains true to its "Zen" ethos:

* **Zen Architecture:** A calm, pragmatic approach focused on clarity and maintainability. Our architecture is designed to be easily understood and maintained, minimizing cognitive load for developers.  
* **"See With Your Eyes":** There's **zero magic** in DartZen. All components and integrations are explicit, making the codebase predictable and easy to debug. You'll always know exactly how things work under the hood.  
* **Minimal Cognitive Load:** We strive to reduce the mental overhead for developers. Our conventions and structures aim to make common tasks intuitive, allowing you to focus on your application's unique features.  
* **Deterministic Server Execution:** DartZen enforces a strict execution model where HTTP transport is fully decoupled from execution. Unlike traditional event-loop-based servers (Node.js and most Dart `shelf` setups), CPU-heavy and long-running operations never block request handling. Execution is isolate-based, explicit, and deterministic — with no shared state, no worker folklore, and no hidden magic.
* **Package-Based Development:** Structuring the project into well-defined packages with clear responsibilities (via Melos). This ensures clear boundaries, better scalability, and independent testing of modules.
* **Google Ecosystem First:** Embracing a deep, native integration with Dart, Flutter, Google Cloud Platform (GCP), and Firebase services. This ensures a unified, optimized, and powerful stack.  
* **Accelerated Development:** Providing a ready-to-use foundation that significantly reduces setup time, allowing developers to focus on unique business logic from day one.
* **Universal Reach & Superior Experience:** We prioritize the best Developer Experience (DX) to help you deliver the best User Experience (UX). DartZen is rigorously developed and tested across **all platforms** (Android, iOS, Web, macOS, Windows, Linux). We support adaptive UI patterns (Material, Cupertino, or Flat) and optimized data transport (JSON or high-performance binary streams) to ensure your app feels native and performs flawlessly everywhere.

## **💻 Stack & Core Modules**

DartZen provides a comprehensive, yet modular, stack tightly integrated with the Google ecosystem:

* **Core Technologies:** Dart, Flutter.  
* **Backend:** Custom backend implemented with `shelf` for ultimate simplicity and control.  
* **Authentication & Authorization:** Google Cloud Identity Platform & Firebase Authentication.  
* **Primary Database:** Google Cloud Firestore.  
* **Caching:** Google Cloud Memorystore (Redis/Memcached).  
* **File Storage:** Google Cloud Storage.  
* **AI Services:** Google Cloud Vertex AI / Gemini API.  
* **Analytics:** Google Analytics.  
* **Admin Panel:** A built-in Flutter-based admin interface for operating real products.  
* **Project Management:** Monorepo structure managed by Melos for streamlined development and package management.

## **❤️ Maintained By**
DartZen is proudly maintained and supported by **jLogic Software.** We live by the principle of "Customer Zero": We are our own first customer. This means the code you use is battle-tested daily in jLogic's production systems, ensuring every feature is robust, reliable, and necessary for real-world projects.

## **⚖️ Licensing**

The core components of DartZen are released under the **Apache License 2.0**. This permissive license allows you to use, modify, and distribute the code freely, even for commercial projects.

Individual packages and dependencies within this project may be licensed under different, but compatible, open-source licenses. Please refer to the `pubspec.yaml` file of each package for specific licensing information.

## **⚠️ Disclaimer**

DartZen is an independent open-source project. Neither DartZen, the DartZenDev organization, nor its contributors are affiliated with, endorsed by, or sponsored by Google LLC. All trademarks, including Google, Firebase, GCP, Flutter, Dart, Vertex AI, Gemini API, and any other mentioned products, are the property of their respective owners. The use of Google product names is solely for the purpose of describing compatibility and integration.
