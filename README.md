# KeychainItemWrapper
Keychain Item Wrapper from Apple. I do some change to fit for me.

KeychainItemWrapper is from Apple, you can download the origin version from https://developer.apple.com/library/ios/documentation/Security/Conceptual/keychainServConcepts/iPhoneTasks/iPhoneTasks.html 



Init a keychain wrapper 
- (id)initWithIdentifier: (NSString *)identifier accessGroup:(NSString *) accessGroup;
 
Save an object to keychain, with custome key [custKey].
- (void)setObject:(id)inObject custKey:(NSString *)custKey;

Get an object from keychain with [custKey]
- (id)objectForCustKey:(NSString *) custKey;

Delete an object from keychain using [custKey]
- (void)removeKeyChainWithCustKey:(NSString *) custKey;


Eric Poon
