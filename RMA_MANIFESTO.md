# Criteo RMA process - Manifesto

## The Hardware vendor trust Criteo qualification

The hardware monitoring that Criteo developed uses information provided by the BMC of the Hardware vendor to detect Hardware issues. If the BMC is clearly detecting a hardware issue on a part, Criteo will request a new healthy part.

If an issue is too complicated and cannot be associated easily to a part replacement, Hardware vendor must dedicate an advanced engineering support to Criteo to find quickly the root cause of hardware issues.

## Access to advanced support engineering

When diagnostic is difficult, Criteo need a direct advanced support engineering to speed up the repair process (find the good part to change). Skipping the basic L1 support is mandatory.

Only during this process, Criteo will be able to send specifics Logs.

## Minimize on-site interventions due to high travel cost

Sending an authorized technician on site is taking a lot of resource and time.

We don’t want diagnostics to require lots of back and forth, that require specific access to the hardware: for example swapping parts. And the reparation process should be streamlined to require a minimum amount of steps

## No access to datacenter

Due to strict regulations and security procedures, Criteo will never allow a technician who is not approved by us (and who does not work directly for our authorized contractor) on site.

That said, if a really specific issue arises, there is still the possibility to send back the impacted parts if really needed for investigations.

if Criteo or authorized contractors are not certified to operate on servers, the priority is to get certified. In the mean time, exceptional access could be created for hardware vendors to access servers.

## Criteo don't need day+1 part delivery

Rapid delivery (next-day) is not a priority for Criteo. What is essential, however, is having a streamlined ordering process and the ability to order a large quantity of hardware parts.

## Automation is a priority

Ordering a part to the vendor portal, should be easy and as much as possible automated:
* API to order part
* A bulk way to order multiple parts on multiple different servers

Reducing manual administrative tasks is a priority.

## Sustainability is a part of Criteo’s values

Sending and receiving parts should contain the minimum number of boxes to reduce the environmental impact.
