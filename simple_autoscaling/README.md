### Simple Autoscale Demo

Run the following command to deploy a stack of (2) Cirros instances that will
max out the CPU and scale out to 5 instances over time.

heat stack-create autoscale -f autoscale-cirros.yaml -e autoscale-environment.yaml