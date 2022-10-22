# Must use java verison < 17 !

Problem: "JSPs can't be compiled on Java 17+"
- https://github.com/eclipse-platform/eclipse.platform.ua/issues/18
  - https://bugs.eclipse.org/bugs/show_bug.cgi?id=578221
- https://github.com/eclipse-platform/eclipse.platform.swt/issues/439

Solution: Install jdt.core in Eclipse
- https://github.com/eclipse-platform/eclipse.platform.ua/issues/18#issuecomment-1284195308

Solution: Java-11-openjdk
- https://docs.fedoraproject.org/en-US/quick-docs/installing-java/


# Set Java version with 'alternatives'
https://stackoverflow.com/questions/62141660/automatically-run-the-command-alternatives-config-java-to-choose-the-option-pr

`echo -e "2" | sudo alternatives --config java`
