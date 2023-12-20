# ISR 
Code at  https://idealo.github.io/image-super-resolution
Command is test.py
 
Libraries are at tf39.yml

# Waifu2x
Using nunif
Code at https://github.com/nagadomi/nunif
Command is
 python -m waifu2x.cli -m noise_scale4x -n 3 -i /data/data1/users/ksismanis/samples/samples/photo_color -o photo_color --format jpeg
 
Libraries are rcan.yml, nunif.yml

# Real-ESRGAN
Code at https://github.com/xinntao/Real-ESRGAN

Command is  ./realesrgan-ncnn-vulkan -i /data/data1/users/ksismanis/samples/samples/drawing/  -o drawing/   -f jpg -g 1

Binary no libraries configured


# SwinIR
Code is at 
https://github.com/JingyunLiang/SwinIR
Pretrained models are at https://github.com/JingyunLiang/SwinIR/releases/tag/v0.0
Command is 
python main_test_swinir.py --task real_sr --scale 4 --tile 400 --model_path model_zoo/swinir/003_realSR_BSRGAN_DFO_s64w8_SwinIR-M_x4_GAN.pth --folder_lq testsets/photo_color/

 python main_test_swinir.py --task real_sr --scale 2 --tile 400 --model_path model_zoo/swinir/003_realSR_BSRGAN_DFO_s64w8_SwinIR-M_x2_GAN.pth --folder_lq /data/data1/users/ksismanis/samples/photo_color

Libraries are at swinir.yml

