## Learning to Generate Piano Music With Sustain Pedals

This is the demo page for the paper **“Learning to Generate Piano Music With Sustain Pedals”**

### Abstract

Current existing research on piano sustain pedal has not been a widely investigated area. Neither has sustain pedal information in symbolic domain. It was not until the last four years did research papers regarding piano pedals had been published. This work demonstrates the possibility of automatic piano music generation with information of sustain pedal included. Based on the work of Yeh et al., the Compound Word Transformer, we modified the model such that it is adapted to generate piano music with sustain pedals included. The AILabs1k7 dataset, consisted of 1,748 pop piano music collected from the Internet, was used for the task. While the work is done by using second-hand sustain pedal information as training data, the result shows hope for further improvement and importance of the involvement of sustain pedal in tasks of piano performance generations. Details on dataset choice, as well as how the training data is prepared for the task will be explained.

### Audio Samples

Here are some examples of the generation result! For each example, both versions of with/without pedals are provided as a reference for how the pedals are affecting the sounding.
> Please wear headphones for best result :)

<table class="VA-example" style="width:100%" cellspacing="0" cellpadding="0">
  <tr>
    <td style="text-align: center; vertical-align: middle;"></td>
    <td style="text-align: center; vertical-align: middle;">With Pedal</td>
    <td style="text-align: center; vertical-align: middle;">Without Pedal</td>
  </tr>

  <tr>
      <td style="text-align: center; vertical-align: middle;">Example 1</td>

      <td><audio controls=""><source src="./assets/audio_samples/demo2.mp3" type="audio/mpeg" /></audio></td>
      <td><audio controls=""><source src="./assets/audio_samples/demo2_noPed.mp3" type="audio/mpeg" /></audio></td>
  </tr>
  
  <tr>
      <td style="text-align: center; vertical-align: middle;">Example 2</td>

      <td><audio controls=""><source src="./assets/audio_samples/demo3.mp3" type="audio/mpeg" /></audio></td>
      <td><audio controls=""><source src="./assets/audio_samples/demo3_noPed.mp3" type="audio/mpeg" /></audio></td>
  </tr>
    
  <tr>
      <td style="text-align: center; vertical-align: middle;">Example 3</td>

      <td><audio controls=""><source src="./assets/audio_samples/demo4.mp3" type="audio/mpeg" /></audio></td>
      <td><audio controls=""><source src="./assets/audio_samples/demo4_noPed.mp3" type="audio/mpeg" /></audio></td>
  </tr>
    
  <tr>
      <td style="text-align: center; vertical-align: middle;">Example 4</td>

      <td><audio controls=""><source src="./assets/audio_samples/demo6.mp3" type="audio/mpeg" /></audio></td>
      <td><audio controls=""><source src="./assets/audio_samples/demo6_noPed.mp3" type="audio/mpeg" /></audio></td>
  </tr>
    
  
</table>
      
      
### Contact
* Joann Ching<br/>Former Research Assistant @ Academia Sinica<br/>MSMT student @ Center for Music Technology, Georgia Institute of Technology<br/>jching9@gatech.edu
