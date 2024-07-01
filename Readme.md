Robust APIs with Django and Django Rest Framework. Practice of the principles of the 12 Factor App methodology (https://12factor.net) to guide our development for scalable, maintainable, and efficient backends.


- Setting up Django and Django Rest Framework from scratch
- Applying the 12 Factor App methodology to design a clean, efficient backend
- Creating RESTful APIs to interact seamlessly with your frontend
- Implementing authentication, serialization, and database models
- Tips and best practices for testing and deploying your API

Flutter


- flutter create dj_app
- main.dart
- analysis options


- install packages

Riverpod

flutter pub add flutter_riverpod riverpod_annotation
flutter pub add dev:build_runner dev:riverpod_generator dev:riverpod_lint dev:custom_lint


Freezed
flutter pub add freezed_annotation json_annotation
flutter pub add dev:build_runner dev:freezed dev:json_serializable

Dio
flutter pub add dio

FPdart
flutter pub add fpdart

flutter pub add sembast


- make folder structure

lib->src->feature->post/comment

mkdir models providers services components screens

====

auth
 - token model, auth state
 - auth provider
 - auth interceptor

 core
 - api service

src/core/services/api_service.dart