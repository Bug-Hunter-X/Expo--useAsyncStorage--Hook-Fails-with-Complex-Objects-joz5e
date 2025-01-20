# Expo AsyncStorage Bug with Complex Objects

This repository demonstrates a bug encountered when using Expo's `useAsyncStorage` hook with complex objects. The hook sometimes fails to store or retrieve data correctly, particularly when dealing with nested structures or large datasets. This issue leads to data loss and unpredictable application behavior.  The provided solutions explore alternative approaches to manage complex data with AsyncStorage.

## Problem Description

Storing and retrieving deeply nested objects or large JSON structures using `useAsyncStorage` can lead to silent failures or inconsistent data.  Debugging this behavior is challenging due to the lack of explicit error messages.