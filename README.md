# Zangambaro Education

Android educational app for South Sudan secondary students.

- Biology S1–S4 first
- Examination-style revision and quizzes
- Created by Zangambaro
- Motto: Learn, build, launch. All on your android.

## Cloud build
The included GitHub Actions workflow builds a debug APK on every push to `main`/`master` and on manual dispatch. The APK is published as a workflow artifact.

## Local Android build
- name: Set up Android SDK
  uses: android-actions/setup-android@v4
