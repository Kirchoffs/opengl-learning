# Notes

## GL_SILENCE_DEPRECATION
Starting from macOS Catalina, Apple chose to deprecate OpenGL in favor of their proprietary technology, Metal. This decision was motivated by the fact that OpenGL, which was created 25 years ago, no longer encompasses many essential features. Moreover, it doesn't align well with modern hardware architecture due to disparities in the GPU pipeline, lack of support for multithreaded operations, and other factors.

As a consequence, compiling a project without the appropriate flag will result in numerous warnings indicating that OpenGL is no longer supported on Apple devices and platforms. By utilizing the 'GL_SILENCE_DEPRECATION' directive, developers can effectively suppress a significant portion of these warning flags, enabling them to concentrate on addressing genuine issues.