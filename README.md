# NSObject_ObjectiveC
NSObject_ObjectiveC

- NSObject is the root class of Cocoa.

# Basic Properties

self
class (name of the class)
superclass (superclass of current class)

# NSObject

### Methods

- (instanceType)init
- (instanceType)new
- (instanceType)alloc

# For copy any object

- (id)copy
- (id)mutableCopy

# For compare objects

- (BOOL)isEqual:(id)object

# to get superclass of current class

superclass

# to check which kind of class is this

- (BOOL)isKindOfClass:(Class)aClass

# Some property of NON-ARC classes:

- (instancetype)retain OBJC_ARC_UNAVAILABLE;
- (oneway void)release OBJC_ARC_UNAVAILABLE;
- (instancetype)autorelease OBJC_ARC_UNAVAILABLE;
- (NSUInteger)retainCount



