+ issue1 pom中引入了两个jar，它们有同名的Class(完全限定名一样)，那么运行时会优先使用谁呢？  
  当前工程的pom中，dependencies标签的前面的jar会优先使用；当前工程pom中的jar优先于parent工程pom
  