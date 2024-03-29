.swiftlint.yml

```
whitelist_rules:
  
  # Closure expressions should have a single space inside each brace.
  - closure_spacing
  
  # Colons should be next to the identifier when specifying a type.
  - colon
  
  # There should be no space before and one after any comma.
  - comma
  
  # Arguments can be omitted when matching enums with associated types if they
  # are not used.
  - empty_enum_arguments
  
  # A fatalError call should have a message.
  - fatal_error_message
  
  # Force casts should be avoided.
  - force_cast
  
  # Force tries should be avoided.
  - force_try
  
  # Force unwrapping should be avoided.
  - force_unwrapping
  
  # Struct extension properties and methods are preferred over legacy functions
  - legacy_cggeometry_functions
  
  # Struct-scoped constants are preferred over legacy global constants.
  - legacy_constant
  
  # Swift constructors are preferred over legacy convenience functions.
  - legacy_constructor
  
  # Struct extension properties and methods are preferred over legacy functions
  - legacy_nsgeometry_functions
  
  # Operators should be surrounded by a single whitespace when they are being used.
  - operator_usage_whitespace
  
  # String enum values can be omitted when they are equal to the enumcase name.
  - redundant_string_enum_value
  
  # Returning Void in a function declaration is redundant.
  - redundant_void_return
  
  # Return arrow and return type should be separated by a single space or on a separate line.
  - return_arrow_whitespace
  
  # MARK comment should be in valid format.
  - mark
  
  # Opening braces should be preceded by a single space and on the same line as
  # the declaration.
  - opening_brace
  
  # Prefer `() -> ` over `Void -> `.
  - empty_parameters
  
  # Files should have a single trailing newline.
  - trailing_newline
  
  # Lines should not have trailing semicolons.
  - trailing_semicolon
  
  # Lines should not have trailing whitespace.
  - trailing_whitespace
  
  # Type name should only contain alphanumeric characters,
  # start with an uppercase character and span between 3 and 40 characters in length.
  - type_name
  
  # Unused parameter in a closure should be replaced with _.
  - unused_closure_parameter
  
  # Prefer `!= nil` over `let _ =`
  - unused_optional_binding
  
  # Include a single empty line between switch cases.
  - vertical_whitespace
  
  # Returning Void in a function declaration is redundant.
  - void_return
  
  # Create custom rules by providing a regex string.
  # Optionally specify what syntax kinds to match against,
  # the severity level, and what message to display.
  - custom_rules
  
excluded:
  - Pods
  - Carthage
  - R.generated.swift

colon:
  apply_to_dictionaries: false

indentation: 2

```
