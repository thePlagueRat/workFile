# workFile
艾欧尼亚
user:2571363970	
password:appc572923

男爵
user:1692313569
password:a1843807

configurations.all {
   resolutionStrategy.eachDependency { DependencyResolveDetails details ->
      def requested = details.requested
        if (requested.group == 'com.android.support') {
           if (!requested.name.startsWith("multidex")) {
               details.useVersion '28.0.0'
              }
         }
   }
}
