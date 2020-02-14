How to deploy infrastructure

> Login to <http://15.222.85.250:8080/> with credentails shared
>
> Run Job - <http://15.222.85.250:8080/job/SnapPay_demo_infra/>
>
> Once Successful All resources will be created on aws
>
> Check job status <http://15.222.85.250:8080/job/SnapPay_demo_infra/1/console> (change the jobnumber <jobnumber/console> as per the current job. Also before creating infrastructure is it already exist then run the job - <http://15.222.85.250:8080/job/SnapPay_demo_infra_delete/> to delete resources first.
>
> Successful Job log on sole will display Loadbalancer DNS Name and VM IPs
>
> After Infrastructure creation run website deployment job
>
> It required jenkins admin to first update IP of server where code need to be deployed in jenkins settings or update destination directories as requried.
>
> Once ready with previous step exectute job to deploy code on server - <http://15.222.85.250:8080/job/SnapPay_demo_website-server1/>
>
> Once job is successful website will be accessible from VM IPs
>
> Proposed Architecture:- Here is architecture solution diagram 

![Solution Diagram.pdf](/index.php/f/622#mimetype=application%2Fpdf&hasPreview=false&fileId=622)