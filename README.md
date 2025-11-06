# Style_Transfer_using_GAN

*Misdiagnosis in medical field is a very serious issue having adverse implications on the patient. With skilled radiologists overwhelmed by volume of work, there is critical need for Artifical Intelligence to assist them in taking the right decisions.*

*Magnetic Resonance Imaging (MRI) is a key imaging technology which offers superb soft tissue contrast with different contrast mechanisms such as T1 weighted and T2 weighted. A radiologist often needs multi contrast images to arrive at the right decision but is often cost prohibitive.*

*Using CycleGAN to translate the style of one MRI image to another, which will help in a better understanding of the scanned image. Using GANs you will create T2 weighted images from T1 weighted MRI image and vice-versa.*

### <b><u>Problem statement:</u></b> To build a Generative adversarial model(modified U-Net) which can generate artificial MRI images of different contrast levels from existing MRI scans.
##### <b>T1 v T2 images</b>

- On T1 images FAT is white
- On T2 images both FAT and WATER are white

The two basic types of MRI images are T1-weighted and T2-weighted images, often referred to as T1 and T2 images.

The timing of radiofrequency pulse sequences used to make T1 images results in images which highlight fat tissue within the body.The timing of radiofrequency pulse sequences used to make T2 images results in images which highlight fat AND water within the body.

