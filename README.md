----AWS LIFT AND SHIFT PROJECT----

Prerequsites For LIFT and SHIFT 

OnPremise VM (Preferably in VMWare / Virtualbox)

If you have *.vmdk image of your VM that will also be enough

MUST: You should have the uid/password to log into this VM

AWS CLI with access to Administrator privileges

You can tighten it down based on your requirements

Export VM & Upload to S3

Depending on virtualization tool, use the appropriate procedure to export your VM into *.vmdk or *.ova image. Upload the image to S3 Bucket and note down the bucket_name and vm_image_name.
