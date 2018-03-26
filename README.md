# Samvera-Basebox

This is a very simple Vagrantfile for provisioning a base box suitable for future
Vangrant-based Samvera experimentation. It's a nice starting point, and will
hopefully speed up future such endeavors, by including all the compiled
dependencies for Samvera (like ImageMagick and FFMPEG, etc.).

This is most helpful if you plan on utilizing the Curation Experts
[Ansible-Samvera roles](https://github.com/curationexperts/ansible-samvera). But if you just want a nice Ubuntu-based base box
for hacking digital library projects, this might come in handy?

Here are some helpful links for using this:

 * [How to Create a Vagrant Base Box from an Existing One](https://scotch.io/tutorials/how-to-create-a-vagrant-base-box-from-an-existing-one)

##But, also, Guest Additions!
This base box will endeavor to keep up with Guest Additions so you don't have to.

Yes, the Virtual Box Guest Additions version number increases with each new version
of Virtual Box. And, alas, most generic Vagrant base box images don't ever
seem able to keep up. Darn them. One easy, though somewhat time-consuming, way to
deal with this is to install the [VB Guest plugin](https://github.com/dotless-de/vagrant-vbguest).

##License
[BSD 3-Clause](http://opensource.org/licenses/BSD-3-Clause).
