### V-RGBX
生成重光照结果：
使用 `vrgbx_edit_inference.py` 脚本，给定输入视频和一张参考图生成重光照视频，选择 `--task light_color`

```bash
python vrgbx_edit_inference.py \
    --video_path /home/csm/V-RGBX/examples/LIGHT/luo/luo2.mp4 \
    --task light_color --ref_rgb_path /home/csm/V-RGBX/output/inverse_rendering/luo/image2.png\
    --edit_type irradiance --drop_type normal --width 1280 --height 720 --num_frames 49
```