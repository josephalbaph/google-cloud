```
gcloud -h
gcloud config --help
gcloud help config
gcloud config list
gcloud config list --all
gcloud components list
```
```
gcloud components install beta
gcloud beta interactive
gcloud compute instances describe <your_vm>
```
F2:help:STATE Toggles the active help section, ON when enabled, OFF when disabled.

SSH into your vm instance
```
gcloud compute ssh gcelab2 --zone $ZONE
```
```
cd $HOME
```
Open your .bashrc configuration file using vi text editor:
```
vi ./.bashrc
```
The editor opens and displays the contents of the file. Press the ESC key and then :wq to exit the editor.

