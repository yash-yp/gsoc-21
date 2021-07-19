# Coding Period- Week 6

The weekly meeting took place after a gap of two weeks. The meeting involved project updates and a live demo of the Docker implementation of MARS. 

The Docker approach required the scripts to be run as a root user which we decided was not favorable. Additionally, we discussed the improvements that could be made in the translations release process.

The first task of the week was modifying the Docker configuration that would allow a user to run MARS without being root. This involved a lot of scanning through the documentation, Stack Overflow searches, exploring blogs, etc. In the end, Ritik came up with a feasible solution and was able to implement it 🎉

The above task particularly took more time than expected which resulted in some delays with the documentation.

Further, I participated in the Asia-Pacific call this week to discuss the need of having a process for the translations metrics release. Thanks to Kevin for helping with that 🙌

I also opened an issue- [chaoss/translations/#29](https://github.com/chaoss/translations/issues/29) that could help us get any feedback/suggestions. The guidelines are being reviewed by the translations community. 

Additionally, I created a draft PR- [chaoss/translations/#30](https://github.com/chaoss/translations/pull/30) that standardizes some of the translated metrics. This PR mainly acts as a guide to the standardization process of more translated metrics.

Next, we were able to work on the documentation of the automation system. The documentation is almost done. We thought it would be good to add some checks and error handling before sending people on MARS for user testing.
