
---
## 📁 Folder structure (14 folders, flat, no sub-nesting)

Folder order below roughly follows our own learning path: UI basics → navigation → state → data → backend services → polish → hardening → tooling → quality → shipping → integrations → ML.

### 01_Widgets_and_UI

Core widget catalog + everything about how things _look_.

- f1_common_flutter_widgets_self_study
- f2_buttons_checkbox_and_sliders_widgets
- f3_more_flutter_widgets_self_study
- f4_flutter_navigation_widgets
- f5_more_flutter_widgets_with_changing_state
- f6_advanced_flutter_widgets
- f7_newly_added_flutter_widgets
- f13_statefulwidget_lifecycle_methods
- f22_flutter_theme_colorscheme_self_study
- f23_flutter_responsive_ui
- f24_flutter_context_extras
- f25_flutter_extras_of_basic
- f26_part2_of_flutter_extras_of_basic
- f54_advanced_ui_designs_of_flutter

### 02_Navigation

- f8_navigation_in_flutter
- f9_navigator_two_or_go_router_advanced

### 03_State_Management

Every state-management system we've studied, kept together so we can compare them side by side.

- f34_state_management_flutter
- f35_provider_state_management_flutter
- f36_riverpod_state_management
- f37_code_generation_using_@riverpod
- f38_getx_state_management
- f39_getx_media_query_theme_and_localization
- f40_bloc_state_management
- f41_part_two_of_bloc_state_management
- f42_get_it_service_locator_flutter_advanced

### 04_Networking_and_Data

- f10_flutter_databases_self_study
- f18_parsing_json_and_reading_api_in_flutter
- f20_rest_api_basics_flutter
- f21_dio_and_retrofit_advanced_api_calling

### 05_Firebase_and_Notifications

- f43_firebase_flutter
- f44_firestore_flutter
- f45_firebase_authentication_flutter
- f46_firebase_crashlytics_and_analytics_for
- f47_flutter_push_notifications

### 06_Animations_and_Splash

- f28_flutter_animations
- f29_animation_transitions_flutter
- f30_navigation_animations _(rename from "navigaton")_
- f31_advanced_animations_rive_and_flutter _(rename from "advaned")_
- f32_flutter_splash_screen

### 07_Security_and_Auth

- f27_flutter_mobile_security_info
- f33_flutter_authentication_controller

### 08_Packages_Tools_and_CLI

Dev-environment and tooling notes — not app features, but things that make you productive.

- f14_flutter_debug_and_android_studio_tools
- f15_packages_of_flutter_self_study
- f16_part_two_of_flutter_packages
- f17_flutter_CLI_and_common_issues
- f49_fvm_flutter_version_management
- vscode_for_flutter _(rename → f60_vscode_for_flutter)_
- mason_cli_for_flutter_app_template _(rename → f61_mason_cli_for_flutter_app_template)_

### 09_Testing_and_Code_Quality

- f56_flutter_analyze_and_lint_rules
- f57_flutter_testing_unit_widget_and_integration

### 10_Deployment_and_Release

- f11_flutter_App_customization
- f12_build_apks_of_flutter_project_self_study
- f51_reduce_app_size_flutter
- f52_flutter_flavors_in_deployment
- f53_flutter_ci_cd_deployment

### 11_Platform_Integrations

Third-party services/OS features we're bolting on, not core Flutter.

- f48_google_maps_for_flutter
- f50_flutter_localization_or_internationalization
- f58_flutter_url_launcher_and_deep_linking

### 12_Machine_Learning

- f55_machine_learning_in_flutter

### 13_Code_Generation

- f59_dart_build_runner_and_code_generation
- f62_json_serializable_code_generation

### 14_Native_Interop_and_Platform_Channels

Anything crossing the Dart ↔ native boundary: `MethodChannel`, `EventChannel`, Dart FFI, writing our own platform-specific plugin (the Kotlin/Swift/ObjC/Java side included). This does **not** belong in [11_Platform_Integrations](#11_Platform_Integrations) that folder is for *consuming* someone else's SDK (Maps, url_launcher); this one is for *building the bridge ourself*

---