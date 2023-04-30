# TEXT-To-Audio-Accoustic
Generate Audio from Text and Prompt(Chat-GPT Support)


## Steps

1. Prepare running environment
```shell
conda create -n audioldm python=3.8; conda activate audioldm
pip3 install audioldm
git clone https://github.com/saba99/TEXT-To-Audio-Accoustic; cd AudioLDM
```
2. Start the web application (powered by Gradio)
```shell
python3 app.py
```
3. A link will be printed out. Click the link to open the browser and play.

## Commandline Usage
Prepare running environment
```shell
# Optional
conda create -n audioldm python=3.8; conda activate audioldm
# Install AudioLDM
pip3 install audioldm
```

:star2: **Text-to-Audio Generation**: generate an audio guided by a text
```shell
# The default --mode is "generation"
audioldm -t "A hammer is hitting a wooden surface" 
# Result will be saved in "./output/generation"
```

:star2: **Audio-to-Audio Generation**: generate an audio guided by an audio (output will have similar audio events as the input audio file).
```shell
audioldm --file_path trumpet.wav
# Result will be saved in "./output/generation_audio_to_audio/trumpet"
```



<table class="center">
<tr>
  <td style="text-align:center;"><b>Long Example</b></td>
  <td style="text-align:center;"><b>Long Example</b></td>
   <td style="text-align:center;"><b>Long Example</b></td>
</tr>
  
<tr>
 <td>


https://user-images.githubusercontent.com/33378412/235372224-12b1d879-bf53-44e5-8de0-08378d1f548d.mp4

</td>
  <td>
  

https://user-images.githubusercontent.com/33378412/235372819-a2736d60-d05c-4a8c-a669-25eca8173566.mp4



  </td>
  <td>


https://user-images.githubusercontent.com/33378412/235372169-58518cf2-3062-43ad-bdb5-609e9d111a94.mp4

</td>
</tr>

<tr>
  <td width=25% style="text-align:center;color:gray;">Cat gently meowing and purring in long intervels</td>
  <td width=25% style="text-align:center;">Peaceful and calming ambient music with singing bowl and other instruments</td>
  <td width=25% style="text-align:center;">Nature environmental noise with various bird vocalization, high fidelity, children playing far away and light wind</td>
</tr>

<tr>
  <td style="text-align:center;"><b>Temporal Order Control</b></td>
  <td style="text-align:center;"><b>Temporal Order Control</b></td>
   <td style="text-align:center;"><b>Temporal Order Control</b></td>
</tr>
<tr>
  <td>


https://user-images.githubusercontent.com/33378412/235372278-7954f105-58f4-4f27-8d2c-221ee586f450.mp4



  </td>
  <td>

https://user-images.githubusercontent.com/33378412/235372864-a50dba77-aa95-4f29-906f-f028afb70411.mp4

  </td>
  <td>
 

https://user-images.githubusercontent.com/33378412/235372323-ff6c3f5c-abdf-4ba3-9a1b-8fa18e52dff9.mp4


  </td>              
 
</tr>


<tr>
  <td width=25% style="text-align:center;color:gray;">A female is speaking followed by footstep sound</td>
  <td width=25% style="text-align:center;">A racing car is passing by and disappear</td>
  <td width=25% style="text-align:center;">Wooden table tapping sound followed by water pouring sound</td>
 </tr>
 
 <tr>
  <td style="text-align:center;"><b>HUMAN Question For Chat-GPT</b></td>
  <td style="text-align:center;"><b>HUMAN Question For Chat-GPT</b></td>
   <td style="text-align:center;"><b>HUMAN Question For Chat-GPT</b></td>
</tr>

<tr>
  <td>

https://user-images.githubusercontent.com/33378412/235372728-45d18452-aa7e-4101-a5b3-8933b508b392.mp4


  </td>
  <td>
  

https://user-images.githubusercontent.com/33378412/235372781-a8909270-f541-4c16-99d1-461830c64165.mp4


  </td>              
  <td>
  

https://user-images.githubusercontent.com/33378412/235372746-ccf3886a-d4e6-423a-bb1b-5322d8524d44.mp4


  </td>
</tr>
<tr>
  <td width=25% style="text-align:center;color:gray;">Describe the sound of the battlefiled</td>
  <td width=25% style="text-align:center;">Describe what does a pop music sound</td>
  <td width=25% style="text-align:center;">Describe the sound of the outer space</td>

 
</tr>


 <tr>
  <td style="text-align:center;"><b>
Simplified Chat-GPT Answer</b></td>
  <td style="text-align:center;"><b>
Simplified Chat-GPT Answer</b></td>
   <td style="text-align:center;"><b>
Simplified Chat-GPT Answer</b></td>
</tr>

<tr>
<td>
  
https://user-images.githubusercontent.com/33378412/235373177-81b5c1cf-faf8-4a11-88b8-a7f47c711454.mp4

</td>
 <td>
 

https://user-images.githubusercontent.com/33378412/235373101-ed2c0abe-5ab0-493b-9cd3-b6ff3c24ee57.mp4

  </td>
  <td>
  

https://user-images.githubusercontent.com/33378412/235372996-4453711c-c4eb-4a2b-aa82-627f45461558.mp4

  
  </td>              

</tr>
<tr>
  <td width=25% style="text-align:center">Loud and chaotic. Hum and buzz of machinery such as power tools, high fidelity. Clanking and clattering of metal parts, the whirring of motors and engines, and the beeping and alarms of various instruments</td>
  <td width=25% style="text-align:center;">Pop music that upbeat, catchy, and easy to listen, high fidelity, with simple melodies, electronic instruments and polished production</td>
  <td width=25% style="text-align:center;">The steady crashing of waves against the shore,high fidelity, the whooshing sound of water receding back into the ocean, the sound of seagulls and other coastal birds, and the distant sound of ships or boats</td>

</tr>

</table>

