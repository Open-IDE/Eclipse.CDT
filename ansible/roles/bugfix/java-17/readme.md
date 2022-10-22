# Must use java verison < 17 !

https://bugs.eclipse.org/bugs/show_bug.cgi?id=578221


Solution:
- https://docs.fedoraproject.org/en-US/quick-docs/installing-java/


# Set Java version with 'alternatives'
https://stackoverflow.com/questions/62141660/automatically-run-the-command-alternatives-config-java-to-choose-the-option-pr

`echo -e "2" | sudo alternatives --config java`
