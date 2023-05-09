# GAN_progan
generating faces based on celebrity dataset

Using progressive gan generator and discriminator.

4x4 to to desired resolution, uses WGAN and gradient penalty, more improvements will come after I upgrade my pc.



BATCH_SIZE = [16, 16, 16, 16, 16, 16, 4]
EPOCHS = 10
STEPS_PER_EPOCH = 25


Some generations
![plot_0_init_00000](https://user-images.githubusercontent.com/40152283/237008032-07961d61-104d-4a2e-a9d8-4a5031e53222.png)
![plot_1_fade_in_00027](https://user-images.githubusercontent.com/40152283/237008045-193d1e84-a87e-4bb6-a82b-6f342bdba1ca.png)
![plot_1_fade_in_00028](https://user-images.githubusercontent.com/40152283/237008050-69d6e791-3f3b-4e29-b909-f3e7b679023e.png)
![plot_1_stabilize_00005](https://user-images.githubusercontent.com/40152283/237008058-bbc3addc-8098-45a3-ae35-f8caff2fae6d.png)
![plot_1_stabilize_00010](https://user-images.githubusercontent.com/40152283/237008060-cd00da11-84f7-47ff-8bd8-47a12f7a1e85.png)
![plot_0_init_00000](https://user-images.githubusercontent.com/40152283/237008320-f39a019f-bf12-432a-8c9c-a6724387edff.png)
![plot_1_fade_in_00000](https://user-images.githubusercontent.com/40152283/237008326-4c80f38c-611a-4255-9b1a-7a0947afe6fc.png)
![plot_2_fade_in_00006](https://user-images.githubusercontent.com/40152283/237008335-4c12b224-43d7-4a0b-9eed-fa19c709fe8b.png)
![plot_3_fade_in_00002](https://user-images.githubusercontent.com/40152283/237008350-497633d5-7d1e-4784-bfb4-0b35d8848fc2.png)
![plot_4_stabilize_00005](https://user-images.githubusercontent.com/40152283/237008357-11ef2508-7205-4c22-ba13-706514a2f032.png)
![plot_6_fade_in_00020](https://user-images.githubusercontent.com/40152283/237008364-6c31b430-71b5-411d-8857-7962db1ef900.png)
![plot_6_stabilize_00031](https://user-images.githubusercontent.com/40152283/237008377-601b4f47-15aa-4179-a2f8-1086b9bced4e.png)
![plot_6_stabilize_00035](https://user-images.githubusercontent.com/40152283/237008387-61852363-e79a-4cab-bf91-92ebf8d53eb9.png)
![plot_6_stabilize_00039](https://user-images.githubusercontent.com/40152283/237008394-20e1a1df-98f6-40e8-bfda-1dc05091ea65.png)




This was done with really limited epochs iterations and limited photo samples. Without a powerful GPU, it was going to take too long. But you can clearly see that it was going to generator some faces near the end even with such limited epochs.

