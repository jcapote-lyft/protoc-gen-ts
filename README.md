# Protoc Gen Typescript

Generates appropriate Protocol Buffer sources from Proto files directly through *TypeScript Compiler API*.

This plugin generates plain **Typescript** files that can be used AMD,UMD,CommonJS module systems.

**See examples folder**

Aim of this protoc plugin is to support modern approaches by making usage of protocol buffers easy in Javascript/Typescript.

## Key Differences
This protoc plugin does generate fields as **getter** **setters**.


## Roadmap
- Support for repeated non-integer fields
- Generate appropriate service code that is usable with node **grpc** package.
- Support for creating protocol buffer messages directly from their constructors with object.