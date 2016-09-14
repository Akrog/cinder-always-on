Cinder Always On
October 2016

Slides for Barcelona OpenStack Summit

Speakers:

- Michal Dulko
- Gorka Eguileor

Cinder (OpenStack Block Storage project) can be found in >80% of OpenStack
deployments. Configuring it to be robust, resilient and fast is important.
However considering its high customizability, such as choice of deployment
architecture, volume backend or backup backend, an always on Cinder is not a
simple goal to achieve.

In this talk we will explain how Cinder can be deployed in ways guaranteeing
increased reliability and performance, as close as possible to "always on". We
will walk you through latest innovations that are letting you keep your control
plane and data plane up during upgrades, increased load or when experiencing
breakdowns. These features include:

- cinder-volume service in A/A mode
- rolling upgrades support
- volume replication
- volume migration
- We will also share insight on the improvements in these matters that are
  planned for the future cycles.
