CLR (Common Language Runtime)
    - Runtime that manages a bunch of stuff, garbage collection etc
    -  JIT just in time Compiler
        - takes in code tranforms into machine code that is understood
obj, bin folders
    - build output
    - result of running dotnet build
dotnet run
- dotnet build + run the code
dotnet build
-compiles code

TLDR compilation process
.cs file > compiled using MSBUILD > IL (Intermediate Language) > CLR (common language runtime) processed by JIT > machine code