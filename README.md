# Little Otter


## Diagram
 

https://app.cloudcraft.co/view/c5857d4f-4dc9-448f-a82a-d6fb1d7fade9?key=YxDs0CkzpPE0AYxh6IK9yA

 

## Questions


-   What does testing new code/features look like?

     - Run test locally then commit CI/Cd pipe line

     - Can create containers to maintain consistency of the testing environment between developers.

-   How can we feel confident on application health?

     - There will be health check in the auto-scaling group based on the CPU load or network load.

     - Configure cloudwatch to mornitor the instances

    - Setup monitoring tool like ELK stack, datadog, pagerduty to ensure we get notified in real time

-   How we can feel confident on the privacy and security of our clients' personal health information?

    - Make full use of AWS KMS

    - Encrypt data at rest and in transit

    - Implement frequent environment security posture evaluation

    - Implement Zero-trust model in the whole organization

    - Seraperate of duty. Not one should have "god" power in the environment


