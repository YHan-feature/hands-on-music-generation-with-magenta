# Model diverged with loss nan

```bash
drums_rnn_train --config="drum_kit" --run_dir="logdir\run1" --sequence_example_file="sequence_examples/training_drum_tracks.tfrecord" --hparams="batch_size=128,rnn_layer_sizes=[128,128,128]" --num_training_steps=20000
```

```
I1112 17:25:35.547452 10460 basic_session_run_hooks.py:606] Saving checkpoints for 0 into logdir\run1\train\model.ckpt.
I1112 17:25:39.727416 10460 basic_session_run_hooks.py:262] Accuracy = 0.0013636927, Global Step = 0, Loss = 6.241381, Perplexity = 513.5673
I1112 17:26:09.920347 10460 basic_session_run_hooks.py:260] Accuracy = 0.46023715, Global Step = 10, Loss = 4.002368, Perplexity = 54.72759 (30.193 sec)
I1112 17:26:09.921347 10460 basic_session_run_hooks.py:692] global_step/sec: 0.331203
I1112 17:26:25.051867 10460 basic_session_run_hooks.py:260] Accuracy = 0.46769518, Global Step = 20, Loss = 2.66347, Perplexity = 14.3459835 (15.132 sec)
I1112 17:26:25.052867 10460 basic_session_run_hooks.py:692] global_step/sec: 0.660872
I1112 17:26:37.369868 10460 basic_session_run_hooks.py:606] Saving checkpoints for 29 into logdir\run1\train\model.ckpt.
I1112 17:26:40.768866 10460 basic_session_run_hooks.py:260] Accuracy = 0.45866925, Global Step = 30, Loss = 2.2617729, Perplexity = 9.600094 (15.717 sec)
I1112 17:26:40.769867 10460 basic_session_run_hooks.py:692] global_step/sec: 0.636254
I1112 17:26:55.863867 10460 basic_session_run_hooks.py:260] Accuracy = 0.45427752, Global Step = 40, Loss = 2.4126613, Perplexity = 11.163631 (15.095 sec)
I1112 17:26:55.864868 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662471
I1112 17:27:11.114867 10460 basic_session_run_hooks.py:260] Accuracy = 0.45875785, Global Step = 50, Loss = 2.296695, Perplexity = 9.941272 (15.251 sec)
I1112 17:27:11.114867 10460 basic_session_run_hooks.py:692] global_step/sec: 0.655738
I1112 17:27:26.198948 10460 basic_session_run_hooks.py:260] Accuracy = 0.44874015, Global Step = 60, Loss = 2.2016037, Perplexity = 9.039497 (15.084 sec)
I1112 17:27:26.199949 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662907
I1112 17:27:38.364948 10460 basic_session_run_hooks.py:606] Saving checkpoints for 69 into logdir\run1\train\model.ckpt.
I1112 17:27:41.735948 10460 basic_session_run_hooks.py:260] Accuracy = 0.4473176, Global Step = 70, Loss = 2.4018326, Perplexity = 11.043395 (15.537 sec)
I1112 17:27:41.736948 10460 basic_session_run_hooks.py:692] global_step/sec: 0.643625
I1112 17:28:09.017217 10460 basic_session_run_hooks.py:260] Accuracy = 0.44686618, Global Step = 80, Loss = 2.2803032, Perplexity = 9.779646 (27.281 sec)
I1112 17:28:09.017217 10460 basic_session_run_hooks.py:692] global_step/sec: 0.366565
I1112 17:28:24.864222 10460 basic_session_run_hooks.py:260] Accuracy = 0.43369594, Global Step = 90, Loss = 2.4131439, Perplexity = 11.16902 (15.847 sec)
I1112 17:28:24.865219 10460 basic_session_run_hooks.py:692] global_step/sec: 0.630994
I1112 17:28:39.595218 10460 basic_session_run_hooks.py:606] Saving checkpoints for 100 into logdir\run1\train\model.ckpt.
I1112 17:28:41.492218 10460 basic_session_run_hooks.py:692] global_step/sec: 0.550162
I1112 17:28:41.493219 10460 basic_session_run_hooks.py:260] Accuracy = 0.46544084, Global Step = 100, Loss = 2.3191757, Perplexity = 10.16729 (16.629 sec)
I1112 17:28:41.494218 10460 basic_session_run_hooks.py:692] global_step/sec: 0.601359
I1112 17:28:56.577217 10460 basic_session_run_hooks.py:260] Accuracy = 0.4475231, Global Step = 110, Loss = 2.3816056, Perplexity = 10.822266 (15.084 sec)
I1112 17:28:56.577217 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662998
I1112 17:29:11.758733 10460 basic_session_run_hooks.py:260] Accuracy = 0.43026087, Global Step = 120, Loss = 2.4244304, Perplexity = 11.295793 (15.182 sec)
I1112 17:29:11.759733 10460 basic_session_run_hooks.py:692] global_step/sec: 0.658652
I1112 17:29:28.168734 10460 basic_session_run_hooks.py:260] Accuracy = 0.46936196, Global Step = 130, Loss = 2.1805518, Perplexity = 8.851189 (16.410 sec)
I1112 17:29:28.169734 10460 basic_session_run_hooks.py:692] global_step/sec: 0.609385
I1112 17:29:40.570733 10460 basic_session_run_hooks.py:606] Saving checkpoints for 139 into logdir\run1\train\model.ckpt.
I1112 17:29:43.935734 10460 basic_session_run_hooks.py:260] Accuracy = 0.42310524, Global Step = 140, Loss = 2.4041138, Perplexity = 11.068617 (15.766 sec)
I1112 17:29:43.935734 10460 basic_session_run_hooks.py:692] global_step/sec: 0.634276
I1112 17:29:58.954733 10460 basic_session_run_hooks.py:260] Accuracy = 0.44014993, Global Step = 150, Loss = 2.406198, Perplexity = 11.09171 (15.020 sec)
I1112 17:29:58.955733 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665779
I1112 17:30:14.073733 10460 basic_session_run_hooks.py:260] Accuracy = 0.45627546, Global Step = 160, Loss = 2.1489255, Perplexity = 8.57564 (15.119 sec)
I1112 17:30:14.073733 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661463
I1112 17:30:30.649733 10460 basic_session_run_hooks.py:260] Accuracy = 0.46197903, Global Step = 170, Loss = 2.3002212, Perplexity = 9.976389 (16.576 sec)
I1112 17:30:30.650733 10460 basic_session_run_hooks.py:692] global_step/sec: 0.603245
I1112 17:30:41.172733 10460 basic_session_run_hooks.py:606] Saving checkpoints for 178 into logdir\run1\train\model.ckpt.
I1112 17:30:46.140733 10460 basic_session_run_hooks.py:260] Accuracy = 0.47617775, Global Step = 180, Loss = 2.2958791, Perplexity = 9.933165 (15.491 sec)
I1112 17:30:46.141733 10460 basic_session_run_hooks.py:692] global_step/sec: 0.645536
I1112 17:31:01.215733 10460 basic_session_run_hooks.py:260] Accuracy = 0.46825412, Global Step = 190, Loss = 2.2895205, Perplexity = 9.870204 (15.075 sec)
I1112 17:31:01.215733 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663394
I1112 17:31:16.322733 10460 basic_session_run_hooks.py:692] global_step/sec: 0.645868
I1112 17:31:16.322733 10460 basic_session_run_hooks.py:260] Accuracy = 0.47408855, Global Step = 200, Loss = 2.4150188, Perplexity = 11.1899805 (15.107 sec)
I1112 17:31:16.323734 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661901
I1112 17:31:32.973734 10460 basic_session_run_hooks.py:260] Accuracy = 0.4231756, Global Step = 210, Loss = 2.4063125, Perplexity = 11.092979 (16.651 sec)
I1112 17:31:32.974734 10460 basic_session_run_hooks.py:692] global_step/sec: 0.600565
I1112 17:31:41.993203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 217 into logdir\run1\train\model.ckpt.
I1112 17:31:48.369203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4174261, Global Step = 220, Loss = 2.3315523, Perplexity = 10.293908 (15.395 sec)
I1112 17:31:48.370203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.649542
I1112 17:32:03.414203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4554574, Global Step = 230, Loss = 2.3552935, Perplexity = 10.541223 (15.045 sec)
I1112 17:32:03.415203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664673
I1112 17:32:18.422202 10460 basic_session_run_hooks.py:260] Accuracy = 0.4740806, Global Step = 240, Loss = 2.2822685, Perplexity = 9.798884 (15.008 sec)
I1112 17:32:18.422202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666356
I1112 17:32:35.078203 10460 basic_session_run_hooks.py:260] Accuracy = 0.45567563, Global Step = 250, Loss = 2.2456746, Perplexity = 9.446786 (16.656 sec)
I1112 17:32:35.079203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.600348
I1112 17:32:42.608203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 256 into logdir\run1\train\model.ckpt.
I1112 17:32:50.523202 10460 basic_session_run_hooks.py:260] Accuracy = 0.44760936, Global Step = 260, Loss = 2.2806995, Perplexity = 9.783522 (15.445 sec)
I1112 17:32:50.524204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.647459
I1112 17:33:05.573203 10460 basic_session_run_hooks.py:260] Accuracy = 0.46419355, Global Step = 270, Loss = 2.150322, Perplexity = 8.587623 (15.050 sec)
I1112 17:33:05.573203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664496
I1112 17:33:20.586203 10460 basic_session_run_hooks.py:260] Accuracy = 0.46911845, Global Step = 280, Loss = 2.203171, Perplexity = 9.053678 (15.013 sec)
I1112 17:33:20.587203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666045
I1112 17:33:37.022203 10460 basic_session_run_hooks.py:260] Accuracy = 0.44597661, Global Step = 290, Loss = 2.3230517, Perplexity = 10.206775 (16.436 sec)
I1112 17:33:37.023203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.608421
I1112 17:33:43.099203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 295 into logdir\run1\train\model.ckpt.
I1112 17:33:52.460202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.640461
I1112 17:33:52.461203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4575204, Global Step = 300, Loss = 2.371337, Perplexity = 10.711703 (15.439 sec)
I1112 17:33:52.462203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.64771
I1112 17:34:07.737202 10460 basic_session_run_hooks.py:260] Accuracy = 0.46981734, Global Step = 310, Loss = 2.2363265, Perplexity = 9.358888 (15.276 sec)
I1112 17:34:07.738203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.654665
I1112 17:34:22.949204 10460 basic_session_run_hooks.py:260] Accuracy = 0.43865368, Global Step = 320, Loss = 2.3182712, Perplexity = 10.158097 (15.212 sec)
I1112 17:34:22.951205 10460 basic_session_run_hooks.py:692] global_step/sec: 0.657289
I1112 17:34:39.418203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5008696, Global Step = 330, Loss = 2.0789413, Perplexity = 7.9959993 (16.469 sec)
I1112 17:34:39.419202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.607238
I1112 17:34:43.984203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 334 into logdir\run1\train\model.ckpt.
I1112 17:34:54.837203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4645407, Global Step = 340, Loss = 2.2560127, Perplexity = 9.544954 (15.419 sec)
I1112 17:34:54.838203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.64855
I1112 17:35:10.009203 10460 basic_session_run_hooks.py:260] Accuracy = 0.47683698, Global Step = 350, Loss = 2.1829627, Perplexity = 8.872554 (15.172 sec)
I1112 17:35:10.010203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.659109
I1112 17:35:25.835205 10460 basic_session_run_hooks.py:260] Accuracy = 0.44933406, Global Step = 360, Loss = 2.269254, Perplexity = 9.672182 (15.826 sec)
I1112 17:35:25.836204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.631872
I1112 17:35:41.670203 10460 basic_session_run_hooks.py:260] Accuracy = 0.45870635, Global Step = 370, Loss = 2.3399432, Perplexity = 10.380647 (15.835 sec)
I1112 17:35:41.671204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.631512
I1112 17:35:44.759203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 373 into logdir\run1\train\model.ckpt.
W1112 17:35:44.957227 10460 deprecation.py:323] From c:\users\claire\appdata\local\programs\python\python35\lib\site-packages\tensorflow\python\training\saver.py:960: remove_checkpoint (from tensorflow.python.training.checkpoint_management) is deprecated and will be removed in a future version.
Instructions for updating:
Use standard file APIs to delete files with this prefix.
I1112 17:35:57.131203 10460 basic_session_run_hooks.py:260] Accuracy = 0.44932476, Global Step = 380, Loss = 2.2845678, Perplexity = 9.821441 (15.461 sec)
I1112 17:35:57.132204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.646789
I1112 17:36:12.219203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4610517, Global Step = 390, Loss = 2.1390235, Perplexity = 8.491142 (15.088 sec)
I1112 17:36:12.220203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662778
I1112 17:36:28.419205 10460 basic_session_run_hooks.py:692] global_step/sec: 0.641194
I1112 17:36:28.420203 10460 basic_session_run_hooks.py:260] Accuracy = 0.43359062, Global Step = 400, Loss = 2.3664541, Perplexity = 10.659528 (16.201 sec)
I1112 17:36:28.422204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.617208
I1112 17:36:43.844204 10460 basic_session_run_hooks.py:260] Accuracy = 0.44896406, Global Step = 410, Loss = 2.3153255, Perplexity = 10.12822 (15.424 sec)
I1112 17:36:43.844204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.648424
I1112 17:36:45.328203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 412 into logdir\run1\train\model.ckpt.
I1112 17:36:59.101203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4796554, Global Step = 420, Loss = 2.171571, Perplexity = 8.772054 (15.257 sec)
I1112 17:36:59.101203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.655437
I1112 17:37:14.187203 10460 basic_session_run_hooks.py:260] Accuracy = 0.46420532, Global Step = 430, Loss = 2.3156717, Perplexity = 10.131726 (15.086 sec)
I1112 17:37:14.188203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662822
I1112 17:37:30.712203 10460 basic_session_run_hooks.py:260] Accuracy = 0.46499717, Global Step = 440, Loss = 2.2401521, Perplexity = 9.39476 (16.525 sec)
I1112 17:37:30.712203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.60518
I1112 17:37:45.860203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 451 into logdir\run1\train\model.ckpt.
I1112 17:37:46.204227 10460 basic_session_run_hooks.py:260] Accuracy = 0.4554321, Global Step = 450, Loss = 2.224058, Perplexity = 9.244769 (15.492 sec)
I1112 17:37:46.205204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.645453
I1112 17:38:01.250203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4467434, Global Step = 460, Loss = 2.2950966, Perplexity = 9.925395 (15.046 sec)
I1112 17:38:01.250203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664673
I1112 17:38:16.369202 10460 basic_session_run_hooks.py:260] Accuracy = 0.46150902, Global Step = 470, Loss = 2.2673976, Perplexity = 9.654243 (15.119 sec)
I1112 17:38:16.370203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661376
I1112 17:38:33.038203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4482792, Global Step = 480, Loss = 2.2428489, Perplexity = 9.42013 (16.669 sec)
I1112 17:38:33.038203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.599952
I1112 17:38:46.664203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 490 into logdir\run1\train\model.ckpt.
I1112 17:38:48.509203 10460 basic_session_run_hooks.py:260] Accuracy = 0.47848007, Global Step = 490, Loss = 2.1931348, Perplexity = 8.963266 (15.471 sec)
I1112 17:38:48.509203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.646371
I1112 17:39:03.610203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.644367
I1112 17:39:03.611203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4728389, Global Step = 500, Loss = 2.293267, Perplexity = 9.907252 (15.102 sec)
I1112 17:39:03.612203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.66212
I1112 17:39:18.841203 10460 basic_session_run_hooks.py:260] Accuracy = 0.42964897, Global Step = 510, Loss = 2.4113662, Perplexity = 11.149182 (15.230 sec)
I1112 17:39:18.842223 10460 basic_session_run_hooks.py:692] global_step/sec: 0.656598
I1112 17:39:35.318204 10460 basic_session_run_hooks.py:260] Accuracy = 0.47366643, Global Step = 520, Loss = 2.1790442, Perplexity = 8.837855 (16.477 sec)
I1112 17:39:35.319204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.606907
I1112 17:39:47.409203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 529 into logdir\run1\train\model.ckpt.
I1112 17:39:50.765209 10460 basic_session_run_hooks.py:260] Accuracy = 0.43829098, Global Step = 530, Loss = 2.5183318, Perplexity = 12.40788 (15.447 sec)
I1112 17:39:50.766203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.647375
I1112 17:40:05.818203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4530533, Global Step = 540, Loss = 2.351028, Perplexity = 10.496354 (15.053 sec)
I1112 17:40:05.819204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664319
I1112 17:40:20.951203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4342732, Global Step = 550, Loss = 2.3076844, Perplexity = 10.051124 (15.133 sec)
I1112 17:40:20.951203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.660851
I1112 17:40:37.506203 10460 basic_session_run_hooks.py:260] Accuracy = 0.46606135, Global Step = 560, Loss = 2.2117503, Perplexity = 9.131685 (16.555 sec)
I1112 17:40:37.507204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.604011
I1112 17:40:48.014203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 568 into logdir\run1\train\model.ckpt.
I1112 17:40:52.915203 10460 basic_session_run_hooks.py:260] Accuracy = 0.48300132, Global Step = 570, Loss = 2.2614796, Perplexity = 9.597279 (15.409 sec)
I1112 17:40:52.916203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.648971
I1112 17:41:07.997203 10460 basic_session_run_hooks.py:260] Accuracy = 0.45785558, Global Step = 580, Loss = 2.1690392, Perplexity = 8.749873 (15.082 sec)
I1112 17:41:07.998204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663086
I1112 17:41:23.065204 10460 basic_session_run_hooks.py:260] Accuracy = 0.48373127, Global Step = 590, Loss = 2.14295, Perplexity = 8.5245495 (15.068 sec)
I1112 17:41:23.068205 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663526
I1112 17:41:39.591202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.641104
I1112 17:41:39.592203 10460 basic_session_run_hooks.py:260] Accuracy = 0.46649522, Global Step = 600, Loss = 2.205936, Perplexity = 9.078745 (16.527 sec)
I1112 17:41:39.592203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.60518
I1112 17:41:48.629203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 607 into logdir\run1\train\model.ckpt.
I1112 17:41:54.961203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4665603, Global Step = 610, Loss = 2.1789896, Perplexity = 8.837373 (15.369 sec)
I1112 17:41:54.962203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.650618
I1112 17:42:10.138203 10460 basic_session_run_hooks.py:260] Accuracy = 0.46946904, Global Step = 620, Loss = 2.237302, Perplexity = 9.368023 (15.177 sec)
I1112 17:42:10.138203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.658935
I1112 17:42:25.993204 10460 basic_session_run_hooks.py:260] Accuracy = 0.47928265, Global Step = 630, Loss = 2.2349944, Perplexity = 9.34643 (15.855 sec)
I1112 17:42:25.995204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.630636
I1112 17:42:41.901202 10460 basic_session_run_hooks.py:260] Accuracy = 0.45472303, Global Step = 640, Loss = 2.2824442, Perplexity = 9.800606 (15.908 sec)
I1112 17:42:41.902204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.628654
I1112 17:42:49.468203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 646 into logdir\run1\train\model.ckpt.
I1112 17:42:57.339202 10460 basic_session_run_hooks.py:260] Accuracy = 0.4701508, Global Step = 650, Loss = 2.2527502, Perplexity = 9.513865 (15.438 sec)
I1112 17:42:57.339202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.647794
I1112 17:43:12.373203 10460 basic_session_run_hooks.py:260] Accuracy = 0.42498335, Global Step = 660, Loss = 2.2950914, Perplexity = 9.9253435 (15.034 sec)
I1112 17:43:12.373203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665159
I1112 17:43:28.602204 10460 basic_session_run_hooks.py:260] Accuracy = 0.4534647, Global Step = 670, Loss = 2.3257096, Perplexity = 10.233939 (16.228 sec)
I1112 17:43:28.602204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.616181
I1112 17:43:43.972203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4583141, Global Step = 680, Loss = 2.2442586, Perplexity = 9.43342 (15.371 sec)
I1112 17:43:43.972203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.650618
I1112 17:43:49.998203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 685 into logdir\run1\train\model.ckpt.
I1112 17:43:59.433203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4434052, Global Step = 690, Loss = 2.3265028, Perplexity = 10.242061 (15.461 sec)
I1112 17:43:59.434204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.646747
I1112 17:44:14.796203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.644309
I1112 17:44:14.797204 10460 basic_session_run_hooks.py:260] Accuracy = 0.46225965, Global Step = 700, Loss = 2.2733014, Perplexity = 9.711409 (15.364 sec)
I1112 17:44:14.798204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.650872
I1112 17:44:31.338203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4292596, Global Step = 710, Loss = 2.3030825, Perplexity = 10.004974 (16.541 sec)
I1112 17:44:31.338203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.604595
I1112 17:44:46.430203 10460 basic_session_run_hooks.py:260] Accuracy = 0.45758772, Global Step = 720, Loss = 2.2691185, Perplexity = 9.670873 (15.092 sec)
I1112 17:44:46.430203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662603
I1112 17:44:50.898203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 724 into logdir\run1\train\model.ckpt.
I1112 17:45:01.734204 10460 basic_session_run_hooks.py:260] Accuracy = 0.46212065, Global Step = 730, Loss = 2.2727501, Perplexity = 9.706057 (15.304 sec)
I1112 17:45:01.735204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.653381
I1112 17:45:16.772204 10460 basic_session_run_hooks.py:260] Accuracy = 0.45568594, Global Step = 740, Loss = 2.274637, Perplexity = 9.724388 (15.038 sec)
I1112 17:45:16.772204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665026
I1112 17:45:33.292203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4363416, Global Step = 750, Loss = 2.2256205, Perplexity = 9.259227 (16.520 sec)
I1112 17:45:33.293203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.60529
I1112 17:45:48.282203 10460 basic_session_run_hooks.py:260] Accuracy = 0.42159992, Global Step = 760, Loss = 2.4462082, Perplexity = 11.54449 (14.990 sec)
I1112 17:45:48.283204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.667156
I1112 17:45:51.296203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 763 into logdir\run1\train\model.ckpt.
I1112 17:46:03.688203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4504825, Global Step = 770, Loss = 2.2884688, Perplexity = 9.859829 (15.406 sec)
I1112 17:46:03.689203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.649056
I1112 17:46:18.692203 10460 basic_session_run_hooks.py:260] Accuracy = 0.48590678, Global Step = 780, Loss = 2.1610286, Perplexity = 8.680062 (15.004 sec)
I1112 17:46:18.692203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666533
I1112 17:46:35.201203 10460 basic_session_run_hooks.py:260] Accuracy = 0.49449506, Global Step = 790, Loss = 2.1410437, Perplexity = 8.508313 (16.509 sec)
I1112 17:46:35.201203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.60573
I1112 17:46:50.213203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.64343
I1112 17:46:50.213203 10460 basic_session_run_hooks.py:260] Accuracy = 0.44791806, Global Step = 800, Loss = 2.3028572, Perplexity = 10.002721 (15.012 sec)
I1112 17:46:50.214203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666089
I1112 17:46:51.749203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 802 into logdir\run1\train\model.ckpt.
I1112 17:47:05.582203 10460 basic_session_run_hooks.py:260] Accuracy = 0.46286637, Global Step = 810, Loss = 2.1923592, Perplexity = 8.956318 (15.369 sec)
I1112 17:47:05.583203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.65066
I1112 17:47:20.682203 10460 basic_session_run_hooks.py:260] Accuracy = 0.43046826, Global Step = 820, Loss = 2.2320497, Perplexity = 9.318948 (15.100 sec)
I1112 17:47:20.682203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662296
I1112 17:47:37.129203 10460 basic_session_run_hooks.py:260] Accuracy = 0.43776312, Global Step = 830, Loss = 2.313053, Perplexity = 10.105228 (16.446 sec)
I1112 17:47:37.129203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.608014
I1112 17:47:52.222203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 841 into logdir\run1\train\model.ckpt.
I1112 17:47:52.529233 10460 basic_session_run_hooks.py:260] Accuracy = 0.47136632, Global Step = 840, Loss = 2.180556, Perplexity = 8.851227 (15.401 sec)
I1112 17:47:52.530235 10460 basic_session_run_hooks.py:692] global_step/sec: 0.649307
I1112 17:48:07.561203 10460 basic_session_run_hooks.py:260] Accuracy = 0.47399148, Global Step = 850, Loss = 2.234839, Perplexity = 9.344976 (15.032 sec)
I1112 17:48:07.562204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665249
I1112 17:48:22.590203 10460 basic_session_run_hooks.py:260] Accuracy = 0.47729903, Global Step = 860, Loss = 2.1557713, Perplexity = 8.634547 (15.029 sec)
I1112 17:48:22.591203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.66538
I1112 17:48:39.098203 10460 basic_session_run_hooks.py:260] Accuracy = 0.45253387, Global Step = 870, Loss = 2.16875, Perplexity = 8.747343 (16.508 sec)
I1112 17:48:39.098203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.605804
I1112 17:48:52.774203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 880 into logdir\run1\train\model.ckpt.
I1112 17:48:54.586203 10460 basic_session_run_hooks.py:260] Accuracy = 0.48919958, Global Step = 880, Loss = 2.0855672, Perplexity = 8.049156 (15.488 sec)
I1112 17:48:54.587203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.645619
I1112 17:49:09.526203 10460 basic_session_run_hooks.py:260] Accuracy = 0.43267685, Global Step = 890, Loss = 2.3764834, Perplexity = 10.7669735 (14.940 sec)
I1112 17:49:09.526203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.669389
I1112 17:49:25.093203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.645661
I1112 17:49:25.094204 10460 basic_session_run_hooks.py:260] Accuracy = 0.45142233, Global Step = 900, Loss = 2.2390993, Perplexity = 9.384874 (15.568 sec)
I1112 17:49:25.096203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.642261
I1112 17:49:41.191204 10460 basic_session_run_hooks.py:260] Accuracy = 0.46247947, Global Step = 910, Loss = 2.1927097, Perplexity = 8.959457 (16.097 sec)
I1112 17:49:41.192204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.621272
I1112 17:49:53.335203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 919 into logdir\run1\train\model.ckpt.
I1112 17:49:56.648203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4486896, Global Step = 920, Loss = 2.2685697, Perplexity = 9.665566 (15.457 sec)
I1112 17:49:56.649203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.646956
I1112 17:50:11.652203 10460 basic_session_run_hooks.py:260] Accuracy = 0.44351298, Global Step = 930, Loss = 2.322485, Perplexity = 10.200992 (15.004 sec)
I1112 17:50:11.653203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666489
I1112 17:50:27.556203 10460 basic_session_run_hooks.py:260] Accuracy = 0.444705, Global Step = 940, Loss = 2.3398206, Perplexity = 10.3793745 (15.904 sec)
I1112 17:50:27.557204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.628773
I1112 17:50:43.108202 10460 basic_session_run_hooks.py:260] Accuracy = 0.5078158, Global Step = 950, Loss = 2.0826752, Perplexity = 8.025911 (15.552 sec)
I1112 17:50:43.109203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.643004
I1112 17:50:53.662203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 958 into logdir\run1\train\model.ckpt.
I1112 17:50:58.504203 10460 basic_session_run_hooks.py:260] Accuracy = 0.45025137, Global Step = 960, Loss = 2.3074298, Perplexity = 10.048565 (15.396 sec)
I1112 17:50:58.505203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.649519
I1112 17:51:13.522203 10460 basic_session_run_hooks.py:260] Accuracy = 0.43986216, Global Step = 970, Loss = 2.4085808, Perplexity = 11.11817 (15.018 sec)
I1112 17:51:13.523204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665868
I1112 17:51:30.159203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4591092, Global Step = 980, Loss = 2.2016702, Perplexity = 9.040099 (16.637 sec)
I1112 17:51:30.160203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.60107
I1112 17:51:45.213203 10460 basic_session_run_hooks.py:260] Accuracy = 0.46574217, Global Step = 990, Loss = 2.2799807, Perplexity = 9.776492 (15.054 sec)
I1112 17:51:45.213203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664319
I1112 17:51:54.247203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 997 into logdir\run1\train\model.ckpt.
I1112 17:52:00.685203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.642707
I1112 17:52:00.686203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4426762, Global Step = 1000, Loss = 2.3027105, Perplexity = 10.001254 (15.473 sec)
I1112 17:52:00.687203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.646245
I1112 17:52:15.841203 10460 basic_session_run_hooks.py:260] Accuracy = 0.43718478, Global Step = 1010, Loss = 2.215628, Perplexity = 9.167164 (15.155 sec)
I1112 17:52:15.842203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.659848
I1112 17:52:32.267203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4752471, Global Step = 1020, Loss = 2.1591763, Perplexity = 8.663999 (16.426 sec)
I1112 17:52:32.268203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.608791
I1112 17:52:47.374203 10460 basic_session_run_hooks.py:260] Accuracy = 0.47734007, Global Step = 1030, Loss = 2.2814827, Perplexity = 9.791187 (15.107 sec)
I1112 17:52:47.375204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661989
I1112 17:52:54.870202 10460 basic_session_run_hooks.py:606] Saving checkpoints for 1036 into logdir\run1\train\model.ckpt.
I1112 17:53:02.791203 10460 basic_session_run_hooks.py:260] Accuracy = 0.44658494, Global Step = 1040, Loss = 2.1597462, Perplexity = 8.668937 (15.417 sec)
I1112 17:53:02.791203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.648635
I1112 17:53:17.876203 10460 basic_session_run_hooks.py:260] Accuracy = 0.45710936, Global Step = 1050, Loss = 2.1888099, Perplexity = 8.924585 (15.085 sec)
I1112 17:53:17.877204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.66291
I1112 17:53:34.572203 10460 basic_session_run_hooks.py:260] Accuracy = 0.44357356, Global Step = 1060, Loss = 2.3350945, Perplexity = 10.330436 (16.696 sec)
I1112 17:53:34.573203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.59891
I1112 17:53:49.662203 10460 basic_session_run_hooks.py:260] Accuracy = 0.43531168, Global Step = 1070, Loss = 2.367424, Perplexity = 10.669871 (15.090 sec)
I1112 17:53:49.663203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662691
I1112 17:53:55.653203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 1075 into logdir\run1\train\model.ckpt.
I1112 17:54:04.901203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4655223, Global Step = 1080, Loss = 2.29397, Perplexity = 9.914221 (15.239 sec)
I1112 17:54:04.902202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.656211
I1112 17:54:20.035203 10460 basic_session_run_hooks.py:260] Accuracy = 0.45081776, Global Step = 1090, Loss = 2.311798, Perplexity = 10.092556 (15.134 sec)
I1112 17:54:20.036204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.660764
I1112 17:54:36.447203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.642009
I1112 17:54:36.447203 10460 basic_session_run_hooks.py:260] Accuracy = 0.46636474, Global Step = 1100, Loss = 2.2868009, Perplexity = 9.843396 (16.412 sec)
I1112 17:54:36.448203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.60931
I1112 17:54:51.500203 10460 basic_session_run_hooks.py:260] Accuracy = 0.48054168, Global Step = 1110, Loss = 2.2611763, Perplexity = 9.594369 (15.053 sec)
I1112 17:54:51.501204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664319
I1112 17:54:55.998203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 1114 into logdir\run1\train\model.ckpt.
I1112 17:55:06.893203 10460 basic_session_run_hooks.py:260] Accuracy = 0.46658534, Global Step = 1120, Loss = 2.37067, Perplexity = 10.704562 (15.393 sec)
I1112 17:55:06.893203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.649688
I1112 17:55:21.884204 10460 basic_session_run_hooks.py:260] Accuracy = 0.46113712, Global Step = 1130, Loss = 2.3152325, Perplexity = 10.127277 (14.991 sec)
I1112 17:55:21.885204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.667022
I1112 17:55:38.372204 10460 basic_session_run_hooks.py:260] Accuracy = 0.4489058, Global Step = 1140, Loss = 2.144857, Perplexity = 8.540819 (16.488 sec)
I1112 17:55:38.372204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.606538
I1112 17:55:53.453203 10460 basic_session_run_hooks.py:260] Accuracy = 0.46344197, Global Step = 1150, Loss = 2.2383285, Perplexity = 9.377643 (15.081 sec)
I1112 17:55:53.453203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663086
I1112 17:55:56.463203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 1153 into logdir\run1\train\model.ckpt.
I1112 17:56:08.837203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4474089, Global Step = 1160, Loss = 2.3097875, Perplexity = 10.072284 (15.383 sec)
I1112 17:56:08.837203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.650026
I1112 17:56:24.424204 10460 basic_session_run_hooks.py:260] Accuracy = 0.47109628, Global Step = 1170, Loss = 2.3074815, Perplexity = 10.049085 (15.588 sec)
I1112 17:56:24.424204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.64156
I1112 17:56:40.514203 10460 basic_session_run_hooks.py:260] Accuracy = 0.47312677, Global Step = 1180, Loss = 2.2144384, Perplexity = 9.156265 (16.090 sec)
I1112 17:56:40.515204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.621465
I1112 17:56:55.514204 10460 basic_session_run_hooks.py:260] Accuracy = 0.44729128, Global Step = 1190, Loss = 2.1972651, Perplexity = 9.000365 (15.000 sec)
I1112 17:56:55.515203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666667
I1112 17:56:57.038204 10460 basic_session_run_hooks.py:606] Saving checkpoints for 1192 into logdir\run1\train\model.ckpt.
I1112 17:57:10.946203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.647249
I1112 17:57:10.947203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4619682, Global Step = 1200, Loss = 2.2655537, Perplexity = 9.636459 (15.433 sec)
I1112 17:57:10.948203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.647962
I1112 17:57:26.714203 10460 basic_session_run_hooks.py:260] Accuracy = 0.45451996, Global Step = 1210, Loss = 2.1268473, Perplexity = 8.388378 (15.767 sec)
I1112 17:57:26.716205 10460 basic_session_run_hooks.py:692] global_step/sec: 0.634196
I1112 17:57:42.490203 10460 basic_session_run_hooks.py:260] Accuracy = 0.43472737, Global Step = 1220, Loss = 2.3034978, Perplexity = 10.009131 (15.776 sec)
I1112 17:57:42.491203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.633915
I1112 17:57:57.557203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 1231 into logdir\run1\train\model.ckpt.
I1112 17:57:57.896232 10460 basic_session_run_hooks.py:260] Accuracy = 0.45867568, Global Step = 1230, Loss = 2.3294568, Perplexity = 10.27236 (15.405 sec)
I1112 17:57:57.896232 10460 basic_session_run_hooks.py:692] global_step/sec: 0.649139
I1112 17:58:13.053203 10460 basic_session_run_hooks.py:260] Accuracy = 0.46292415, Global Step = 1240, Loss = 2.2179017, Perplexity = 9.188032 (15.158 sec)
I1112 17:58:13.054203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.659719
I1112 17:58:29.275204 10460 basic_session_run_hooks.py:260] Accuracy = 0.4645202, Global Step = 1250, Loss = 2.2818592, Perplexity = 9.794874 (16.222 sec)
I1112 17:58:29.276204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.616447
I1112 17:58:44.605202 10460 basic_session_run_hooks.py:260] Accuracy = 0.47160214, Global Step = 1260, Loss = 2.1702297, Perplexity = 8.760296 (15.330 sec)
I1112 17:58:44.605202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.652358
I1112 17:58:58.159204 10460 basic_session_run_hooks.py:606] Saving checkpoints for 1270 into logdir\run1\train\model.ckpt.
I1112 17:58:59.973203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4476219, Global Step = 1270, Loss = 2.3630211, Perplexity = 10.622996 (15.368 sec)
I1112 17:58:59.974203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.65066
I1112 17:59:15.064203 10460 basic_session_run_hooks.py:260] Accuracy = 0.488881, Global Step = 1280, Loss = 2.1294913, Perplexity = 8.410587 (15.091 sec)
I1112 17:59:15.064203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662691
I1112 17:59:31.481203 10460 basic_session_run_hooks.py:260] Accuracy = 0.42026103, Global Step = 1290, Loss = 2.3975508, Perplexity = 10.996212 (16.417 sec)
I1112 17:59:31.482203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.609088
I1112 17:59:46.641203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.642281
I1112 17:59:46.641203 10460 basic_session_run_hooks.py:260] Accuracy = 0.44097495, Global Step = 1300, Loss = 2.2644846, Perplexity = 9.626163 (15.160 sec)
I1112 17:59:46.642203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.659631
I1112 17:59:58.675203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 1309 into logdir\run1\train\model.ckpt.
I1112 18:00:02.013203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4625156, Global Step = 1310, Loss = 2.2823899, Perplexity = 9.800074 (15.372 sec)
I1112 18:00:02.014202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.650533
I1112 18:00:17.014203 10460 basic_session_run_hooks.py:260] Accuracy = 0.45907918, Global Step = 1320, Loss = 2.2025046, Perplexity = 9.047646 (15.001 sec)
I1112 18:00:17.015203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666622
I1112 18:00:33.491203 10460 basic_session_run_hooks.py:260] Accuracy = 0.43657786, Global Step = 1330, Loss = 2.3413439, Perplexity = 10.395197 (16.477 sec)
I1112 18:00:33.492204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.606907
I1112 18:00:48.631203 10460 basic_session_run_hooks.py:260] Accuracy = 0.47462478, Global Step = 1340, Loss = 2.248908, Perplexity = 9.477381 (15.140 sec)
I1112 18:00:48.632203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.660502
I1112 18:00:59.180203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 1348 into logdir\run1\train\model.ckpt.
I1112 18:01:03.992202 10460 basic_session_run_hooks.py:260] Accuracy = 0.47083524, Global Step = 1350, Loss = 2.2284396, Perplexity = 9.285366 (15.361 sec)
I1112 18:01:03.993243 10460 basic_session_run_hooks.py:692] global_step/sec: 0.650998
I1112 18:01:19.069203 10460 basic_session_run_hooks.py:260] Accuracy = 0.47220606, Global Step = 1360, Loss = 2.221845, Perplexity = 9.224334 (15.077 sec)
I1112 18:01:19.070204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663308
I1112 18:01:35.503203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4683667, Global Step = 1370, Loss = 2.12884, Perplexity = 8.40511 (16.434 sec)
I1112 18:01:35.504204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.608458
I1112 18:01:50.564204 10460 basic_session_run_hooks.py:260] Accuracy = 0.44220176, Global Step = 1380, Loss = 2.2853446, Perplexity = 9.829073 (15.061 sec)
I1112 18:01:50.565203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663967
I1112 18:01:59.607203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 1387 into logdir\run1\train\model.ckpt.
I1112 18:02:05.973203 10460 basic_session_run_hooks.py:260] Accuracy = 0.45652258, Global Step = 1390, Loss = 2.2474859, Perplexity = 9.463912 (15.409 sec)
I1112 18:02:05.974204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.648971
I1112 18:02:21.109203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.647383
I1112 18:02:21.110203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4504572, Global Step = 1400, Loss = 2.1628966, Perplexity = 8.696291 (15.137 sec)
I1112 18:02:21.111202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.660633
I1112 18:02:37.636203 10460 basic_session_run_hooks.py:260] Accuracy = 0.44576466, Global Step = 1410, Loss = 2.2986767, Perplexity = 9.960992 (16.526 sec)
I1112 18:02:37.636203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.605144
I1112 18:02:52.647203 10460 basic_session_run_hooks.py:260] Accuracy = 0.46483132, Global Step = 1420, Loss = 2.241475, Perplexity = 9.407198 (15.011 sec)
I1112 18:02:52.648203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666134
I1112 18:03:00.160203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 1426 into logdir\run1\train\model.ckpt.
I1112 18:03:08.046203 10460 basic_session_run_hooks.py:260] Accuracy = 0.44549903, Global Step = 1430, Loss = 2.2380688, Perplexity = 9.375208 (15.399 sec)
I1112 18:03:08.047202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.649393
I1112 18:03:23.126205 10460 basic_session_run_hooks.py:260] Accuracy = 0.44172361, Global Step = 1440, Loss = 2.3522022, Perplexity = 10.508686 (15.080 sec)
I1112 18:03:23.128205 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663086
I1112 18:03:39.520203 10460 basic_session_run_hooks.py:260] Accuracy = 0.43160093, Global Step = 1450, Loss = 2.3954926, Perplexity = 10.973601 (16.394 sec)
I1112 18:03:39.521203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.610017
I1112 18:03:54.575202 10460 basic_session_run_hooks.py:260] Accuracy = 0.4836729, Global Step = 1460, Loss = 2.22593, Perplexity = 9.262093 (15.055 sec)
I1112 18:03:54.576203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664231
I1112 18:04:00.605203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 1465 into logdir\run1\train\model.ckpt.
I1112 18:04:09.924203 10460 basic_session_run_hooks.py:260] Accuracy = 0.45178464, Global Step = 1470, Loss = 2.222716, Perplexity = 9.232373 (15.349 sec)
I1112 18:04:09.925203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.651508
I1112 18:04:25.536203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4709456, Global Step = 1480, Loss = 2.1248028, Perplexity = 8.371246 (15.612 sec)
I1112 18:04:25.537204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.640533
I1112 18:04:41.453203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4847105, Global Step = 1490, Loss = 2.2468302, Perplexity = 9.457709 (15.917 sec)
I1112 18:04:41.453203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.628299
I1112 18:04:56.482227 10460 basic_session_run_hooks.py:692] global_step/sec: 0.643612
I1112 18:04:56.483225 10460 basic_session_run_hooks.py:260] Accuracy = 0.43401182, Global Step = 1500, Loss = 2.282171, Perplexity = 9.797929 (15.030 sec)
I1112 18:04:56.484204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665335
I1112 18:05:00.994203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 1504 into logdir\run1\train\model.ckpt.
I1112 18:05:11.908203 10460 basic_session_run_hooks.py:260] Accuracy = 0.45084038, Global Step = 1510, Loss = 2.2187912, Perplexity = 9.196209 (15.425 sec)
I1112 18:05:11.909204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.648257
I1112 18:05:28.091204 10460 basic_session_run_hooks.py:260] Accuracy = 0.46555936, Global Step = 1520, Loss = 2.1096294, Perplexity = 8.245185 (16.183 sec)
I1112 18:05:28.092204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.617932
I1112 18:05:43.493203 10460 basic_session_run_hooks.py:260] Accuracy = 0.46467444, Global Step = 1530, Loss = 2.128884, Perplexity = 8.405481 (15.402 sec)
I1112 18:05:43.494203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.649309
I1112 18:05:58.496203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4714247, Global Step = 1540, Loss = 2.0841405, Perplexity = 8.037681 (15.003 sec)
I1112 18:05:58.496203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666533
I1112 18:06:01.477203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 1543 into logdir\run1\train\model.ckpt.
I1112 18:06:13.896203 10460 basic_session_run_hooks.py:260] Accuracy = 0.45537803, Global Step = 1550, Loss = 2.2965755, Perplexity = 9.940084 (15.400 sec)
I1112 18:06:13.896203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.649351
I1112 18:06:30.475203 10460 basic_session_run_hooks.py:260] Accuracy = 0.46953788, Global Step = 1560, Loss = 2.1609802, Perplexity = 8.679642 (16.579 sec)
I1112 18:06:30.476203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.603136
I1112 18:06:45.540204 10460 basic_session_run_hooks.py:260] Accuracy = 0.45054692, Global Step = 1570, Loss = 2.1641428, Perplexity = 8.707135 (15.065 sec)
I1112 18:06:45.541203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.66379
I1112 18:07:00.650203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4639185, Global Step = 1580, Loss = 2.2910125, Perplexity = 9.884942 (15.110 sec)
I1112 18:07:00.651203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661813
I1112 18:07:02.143203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 1582 into logdir\run1\train\model.ckpt.
I1112 18:07:16.107203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4778616, Global Step = 1590, Loss = 2.1977074, Perplexity = 9.004347 (15.457 sec)
I1112 18:07:16.108203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.646956
I1112 18:07:32.490203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.640997
I1112 18:07:32.490203 10460 basic_session_run_hooks.py:260] Accuracy = 0.46714628, Global Step = 1600, Loss = 2.1322608, Perplexity = 8.433913 (16.383 sec)
I1112 18:07:32.491204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.610389
I1112 18:07:47.545203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4790249, Global Step = 1610, Loss = 2.2072108, Perplexity = 9.090326 (15.055 sec)
I1112 18:07:47.546203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664275
I1112 18:08:02.546203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 1621 into logdir\run1\train\model.ckpt.
I1112 18:08:02.887236 10460 basic_session_run_hooks.py:260] Accuracy = 0.46578208, Global Step = 1620, Loss = 2.3237042, Perplexity = 10.213437 (15.342 sec)
I1112 18:08:02.888227 10460 basic_session_run_hooks.py:692] global_step/sec: 0.651762
I1112 18:08:17.991203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4501188, Global Step = 1630, Loss = 2.239555, Perplexity = 9.389152 (15.104 sec)
I1112 18:08:17.992203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662077
I1112 18:08:34.450204 10460 basic_session_run_hooks.py:260] Accuracy = 0.45664194, Global Step = 1640, Loss = 2.2270098, Perplexity = 9.272099 (16.459 sec)
I1112 18:08:34.451204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.60757
I1112 18:08:49.521203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4409499, Global Step = 1650, Loss = 2.3094742, Perplexity = 10.069129 (15.071 sec)
I1112 18:08:49.522203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663526
I1112 18:09:03.051203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 1660 into logdir\run1\train\model.ckpt.
I1112 18:09:04.885203 10460 basic_session_run_hooks.py:260] Accuracy = 0.47833487, Global Step = 1660, Loss = 2.1594398, Perplexity = 8.666282 (15.364 sec)
I1112 18:09:04.885203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.650915
I1112 18:09:19.955203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4381503, Global Step = 1670, Loss = 2.1990938, Perplexity = 9.016839 (15.070 sec)
I1112 18:09:19.956204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663526
I1112 18:09:36.501203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4616748, Global Step = 1680, Loss = 2.2187052, Perplexity = 9.195416 (16.546 sec)
I1112 18:09:36.502203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.604376
I1112 18:09:51.588203 10460 basic_session_run_hooks.py:260] Accuracy = 0.42659566, Global Step = 1690, Loss = 2.3715353, Perplexity = 10.713829 (15.087 sec)
I1112 18:09:51.589203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662822
I1112 18:10:03.590203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 1699 into logdir\run1\train\model.ckpt.
I1112 18:10:06.903203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.64761
I1112 18:10:06.904203 10460 basic_session_run_hooks.py:260] Accuracy = 0.48008302, Global Step = 1700, Loss = 2.2143514, Perplexity = 9.155469 (15.316 sec)
I1112 18:10:06.905204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.652912
I1112 18:10:21.929203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5054283, Global Step = 1710, Loss = 2.1222682, Perplexity = 8.350056 (15.025 sec)
I1112 18:10:21.930203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665557
I1112 18:10:38.425203 10460 basic_session_run_hooks.py:260] Accuracy = 0.46409917, Global Step = 1720, Loss = 2.265006, Perplexity = 9.631183 (16.496 sec)
I1112 18:10:38.426203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.606208
I1112 18:10:53.568202 10460 basic_session_run_hooks.py:260] Accuracy = 0.4572433, Global Step = 1730, Loss = 2.1975977, Perplexity = 9.003359 (15.143 sec)
I1112 18:10:53.568202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.660415
I1112 18:11:04.038203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 1738 into logdir\run1\train\model.ckpt.
I1112 18:11:08.941203 10460 basic_session_run_hooks.py:260] Accuracy = 0.38988695, Global Step = 1740, Loss = 2.260805, Perplexity = 9.590806 (15.373 sec)
I1112 18:11:08.941203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.650491
I1112 18:11:24.382205 10460 basic_session_run_hooks.py:260] Accuracy = 0.46618393, Global Step = 1750, Loss = 2.1854455, Perplexity = 8.894611 (15.441 sec)
I1112 18:11:24.383204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.647584
I1112 18:11:40.539204 10460 basic_session_run_hooks.py:260] Accuracy = 0.48204935, Global Step = 1760, Loss = 2.1635394, Perplexity = 8.701883 (16.157 sec)
I1112 18:11:40.539204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.618965
I1112 18:11:55.613203 10460 basic_session_run_hooks.py:260] Accuracy = 0.46423525, Global Step = 1770, Loss = 2.313832, Perplexity = 10.113105 (15.074 sec)
I1112 18:11:55.614203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.66335
I1112 18:12:04.638203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 1777 into logdir\run1\train\model.ckpt.
I1112 18:12:11.008203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4568035, Global Step = 1780, Loss = 2.2961218, Perplexity = 9.9355755 (15.395 sec)
I1112 18:12:11.008203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.649604
I1112 18:12:26.823204 10460 basic_session_run_hooks.py:260] Accuracy = 0.4705536, Global Step = 1790, Loss = 2.0763216, Perplexity = 7.975079 (15.814 sec)
I1112 18:12:26.824205 10460 basic_session_run_hooks.py:692] global_step/sec: 0.632271
I1112 18:12:42.554204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.642463
I1112 18:12:42.555203 10460 basic_session_run_hooks.py:260] Accuracy = 0.44717982, Global Step = 1800, Loss = 2.3654156, Perplexity = 10.648462 (15.733 sec)
I1112 18:12:42.556203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.635647
I1112 18:12:57.660204 10460 basic_session_run_hooks.py:260] Accuracy = 0.47046262, Global Step = 1810, Loss = 2.3487072, Perplexity = 10.472022 (15.105 sec)
I1112 18:12:57.660204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662076
I1112 18:13:05.118203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 1816 into logdir\run1\train\model.ckpt.
I1112 18:13:12.955203 10460 basic_session_run_hooks.py:260] Accuracy = 0.47154427, Global Step = 1820, Loss = 2.1544302, Perplexity = 8.622975 (15.295 sec)
I1112 18:13:12.956203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.653808
I1112 18:13:29.171204 10460 basic_session_run_hooks.py:260] Accuracy = 0.4819377, Global Step = 1830, Loss = 2.0947988, Perplexity = 8.123806 (16.216 sec)
I1112 18:13:29.172205 10460 basic_session_run_hooks.py:692] global_step/sec: 0.616637
I1112 18:13:44.532203 10460 basic_session_run_hooks.py:260] Accuracy = 0.47997066, Global Step = 1840, Loss = 2.1892185, Perplexity = 8.928233 (15.361 sec)
I1112 18:13:44.533203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.651042
I1112 18:13:59.526203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4709009, Global Step = 1850, Loss = 2.2834997, Perplexity = 9.810956 (14.994 sec)
I1112 18:13:59.527203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666889
I1112 18:14:05.555203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 1855 into logdir\run1\train\model.ckpt.
I1112 18:14:14.938203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4440285, Global Step = 1860, Loss = 2.2725976, Perplexity = 9.7045765 (15.412 sec)
I1112 18:14:14.939204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.648845
I1112 18:14:31.309202 10460 basic_session_run_hooks.py:260] Accuracy = 0.48396844, Global Step = 1870, Loss = 2.14574, Perplexity = 8.548365 (16.371 sec)
I1112 18:14:31.310203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.610836
I1112 18:14:46.366203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4388013, Global Step = 1880, Loss = 2.264939, Perplexity = 9.630538 (15.057 sec)
I1112 18:14:46.367203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664143
I1112 18:15:01.462203 10460 basic_session_run_hooks.py:260] Accuracy = 0.45849496, Global Step = 1890, Loss = 2.0838325, Perplexity = 8.035205 (15.096 sec)
I1112 18:15:01.463204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662427
I1112 18:15:05.951203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 1894 into logdir\run1\train\model.ckpt.
I1112 18:15:16.850203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.648105
I1112 18:15:16.851203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4549877, Global Step = 1900, Loss = 2.2124264, Perplexity = 9.137862 (15.389 sec)
I1112 18:15:16.851203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.649857
I1112 18:15:33.397202 10460 basic_session_run_hooks.py:260] Accuracy = 0.45325345, Global Step = 1910, Loss = 2.1781964, Perplexity = 8.830365 (16.546 sec)
I1112 18:15:33.398232 10460 basic_session_run_hooks.py:692] global_step/sec: 0.604338
I1112 18:15:48.451203 10460 basic_session_run_hooks.py:260] Accuracy = 0.45152414, Global Step = 1920, Loss = 2.2253723, Perplexity = 9.256928 (15.054 sec)
I1112 18:15:48.451203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664321
I1112 18:16:03.542203 10460 basic_session_run_hooks.py:260] Accuracy = 0.44215277, Global Step = 1930, Loss = 2.2187157, Perplexity = 9.195514 (15.091 sec)
I1112 18:16:03.543204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662603
I1112 18:16:06.572203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 1933 into logdir\run1\train\model.ckpt.
I1112 18:16:18.944203 10460 basic_session_run_hooks.py:260] Accuracy = 0.49932593, Global Step = 1940, Loss = 2.021553, Perplexity = 7.550041 (15.402 sec)
I1112 18:16:18.944203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.649309
I1112 18:16:35.554203 10460 basic_session_run_hooks.py:260] Accuracy = 0.46823016, Global Step = 1950, Loss = 2.2028005, Perplexity = 9.0503235 (16.610 sec)
I1112 18:16:35.554203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.602047
I1112 18:16:50.645203 10460 basic_session_run_hooks.py:260] Accuracy = 0.43653584, Global Step = 1960, Loss = 2.3088953, Perplexity = 10.063302 (15.091 sec)
I1112 18:16:50.645203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662647
I1112 18:17:05.838203 10460 basic_session_run_hooks.py:260] Accuracy = 0.52294415, Global Step = 1970, Loss = 2.089456, Perplexity = 8.080519 (15.193 sec)
I1112 18:17:05.839204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.658155
I1112 18:17:07.356203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 1972 into logdir\run1\train\model.ckpt.
I1112 18:17:21.346203 10460 basic_session_run_hooks.py:260] Accuracy = 0.45973095, Global Step = 1980, Loss = 2.1692486, Perplexity = 8.751705 (15.508 sec)
I1112 18:17:21.347204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.644828
I1112 18:17:37.914203 10460 basic_session_run_hooks.py:260] Accuracy = 0.45374143, Global Step = 1990, Loss = 2.3130462, Perplexity = 10.105161 (16.568 sec)
I1112 18:17:37.915203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.603573
I1112 18:17:53.035203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.640266
I1112 18:17:53.036203 10460 basic_session_run_hooks.py:260] Accuracy = 0.49287966, Global Step = 2000, Loss = 2.0926251, Perplexity = 8.106167 (15.122 sec)
I1112 18:17:53.037204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661288
I1112 18:18:08.028213 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2011 into logdir\run1\train\model.ckpt.
I1112 18:18:08.337232 10460 basic_session_run_hooks.py:260] Accuracy = 0.48749977, Global Step = 2010, Loss = 2.1192484, Perplexity = 8.324878 (15.301 sec)
I1112 18:18:08.338232 10460 basic_session_run_hooks.py:692] global_step/sec: 0.653551
I1112 18:18:23.597204 10460 basic_session_run_hooks.py:260] Accuracy = 0.4655611, Global Step = 2020, Loss = 2.132139, Perplexity = 8.432885 (15.260 sec)
I1112 18:18:23.599205 10460 basic_session_run_hooks.py:692] global_step/sec: 0.655266
I1112 18:18:40.049202 10460 basic_session_run_hooks.py:260] Accuracy = 0.45274514, Global Step = 2030, Loss = 2.3308852, Perplexity = 10.287043 (16.452 sec)
I1112 18:18:40.050203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.607866
I1112 18:18:55.147203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5118396, Global Step = 2040, Loss = 2.1207957, Perplexity = 8.3377695 (15.098 sec)
I1112 18:18:55.148203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662339
I1112 18:19:08.663204 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2050 into logdir\run1\train\model.ckpt.
I1112 18:19:10.493203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4801138, Global Step = 2050, Loss = 2.1078312, Perplexity = 8.230372 (15.346 sec)
I1112 18:19:10.493203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.651678
I1112 18:19:26.247204 10460 basic_session_run_hooks.py:260] Accuracy = 0.475514, Global Step = 2060, Loss = 2.2105815, Perplexity = 9.121018 (15.754 sec)
I1112 18:19:26.249204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.634679
I1112 18:19:41.969202 10460 basic_session_run_hooks.py:260] Accuracy = 0.46870348, Global Step = 2070, Loss = 2.1733882, Perplexity = 8.78801 (15.722 sec)
I1112 18:19:41.970203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.636092
I1112 18:19:57.014203 10460 basic_session_run_hooks.py:260] Accuracy = 0.48195598, Global Step = 2080, Loss = 2.1840563, Perplexity = 8.882262 (15.045 sec)
I1112 18:19:57.015203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664673
I1112 18:20:09.048203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2089 into logdir\run1\train\model.ckpt.
I1112 18:20:12.418203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5163521, Global Step = 2090, Loss = 1.9765959, Perplexity = 7.2181296 (15.404 sec)
I1112 18:20:12.419203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.649182
I1112 18:20:28.676203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.642504
I1112 18:20:28.677203 10460 basic_session_run_hooks.py:260] Accuracy = 0.52536356, Global Step = 2100, Loss = 2.025007, Perplexity = 7.576164 (16.259 sec)
I1112 18:20:28.680205 10460 basic_session_run_hooks.py:692] global_step/sec: 0.614968
I1112 18:20:44.026203 10460 basic_session_run_hooks.py:260] Accuracy = 0.47036752, Global Step = 2110, Loss = 2.2276757, Perplexity = 9.2782755 (15.349 sec)
I1112 18:20:44.027203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.651593
I1112 18:20:59.087203 10460 basic_session_run_hooks.py:260] Accuracy = 0.49368128, Global Step = 2120, Loss = 2.096958, Perplexity = 8.141365 (15.061 sec)
I1112 18:20:59.088203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663966
I1112 18:21:09.588203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2128 into logdir\run1\train\model.ckpt.
I1112 18:21:14.479203 10460 basic_session_run_hooks.py:260] Accuracy = 0.50996214, Global Step = 2130, Loss = 2.0231495, Perplexity = 7.562104 (15.392 sec)
I1112 18:21:14.480203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.649688
I1112 18:21:31.094204 10460 basic_session_run_hooks.py:260] Accuracy = 0.5047129, Global Step = 2140, Loss = 2.0916426, Perplexity = 8.098206 (16.615 sec)
I1112 18:21:31.094204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.601902
I1112 18:21:46.200203 10460 basic_session_run_hooks.py:260] Accuracy = 0.44318748, Global Step = 2150, Loss = 2.2450635, Perplexity = 9.441015 (15.106 sec)
I1112 18:21:46.200203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661989
I1112 18:22:01.207203 10460 basic_session_run_hooks.py:260] Accuracy = 0.47590545, Global Step = 2160, Loss = 2.1503394, Perplexity = 8.587772 (15.007 sec)
I1112 18:22:01.208204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666311
I1112 18:22:10.203203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2167 into logdir\run1\train\model.ckpt.
I1112 18:22:16.575203 10460 basic_session_run_hooks.py:260] Accuracy = 0.48663923, Global Step = 2170, Loss = 2.1069987, Perplexity = 8.223523 (15.368 sec)
I1112 18:22:16.575203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.650745
I1112 18:22:33.079204 10460 basic_session_run_hooks.py:260] Accuracy = 0.4904181, Global Step = 2180, Loss = 2.203946, Perplexity = 9.060698 (16.504 sec)
I1112 18:22:33.080203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.605877
I1112 18:22:48.196203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5031409, Global Step = 2190, Loss = 2.14477, Perplexity = 8.540076 (15.117 sec)
I1112 18:22:48.196203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661551
I1112 18:23:03.199203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.647153
I1112 18:23:03.200203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4920117, Global Step = 2200, Loss = 2.1859004, Perplexity = 8.898658 (15.003 sec)
I1112 18:23:03.200203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666489
I1112 18:23:10.683204 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2206 into logdir\run1\train\model.ckpt.
I1112 18:23:18.540203 10460 basic_session_run_hooks.py:260] Accuracy = 0.47628376, Global Step = 2210, Loss = 2.4046793, Perplexity = 11.074878 (15.341 sec)
I1112 18:23:18.541203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.651848
I1112 18:23:35.112203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4622273, Global Step = 2220, Loss = 2.202189, Perplexity = 9.04479 (16.572 sec)
I1112 18:23:35.113204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.603427
I1112 18:23:50.181203 10460 basic_session_run_hooks.py:260] Accuracy = 0.51596415, Global Step = 2230, Loss = 2.1293693, Perplexity = 8.409561 (15.069 sec)
I1112 18:23:50.182204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663614
I1112 18:24:05.252203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4534102, Global Step = 2240, Loss = 2.2159162, Perplexity = 9.1698065 (15.071 sec)
I1112 18:24:05.252203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.66357
I1112 18:24:11.276203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2245 into logdir\run1\train\model.ckpt.
I1112 18:24:20.662203 10460 basic_session_run_hooks.py:260] Accuracy = 0.46138242, Global Step = 2250, Loss = 2.1477013, Perplexity = 8.565147 (15.410 sec)
I1112 18:24:20.662203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.648929
I1112 18:24:37.078203 10460 basic_session_run_hooks.py:260] Accuracy = 0.48784783, Global Step = 2260, Loss = 2.2731338, Perplexity = 9.709782 (16.416 sec)
I1112 18:24:37.078203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.609162
I1112 18:24:52.174203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4928514, Global Step = 2270, Loss = 2.0222068, Perplexity = 7.554979 (15.096 sec)
I1112 18:24:52.175204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662383
I1112 18:25:07.280203 10460 basic_session_run_hooks.py:260] Accuracy = 0.48282862, Global Step = 2280, Loss = 2.1284459, Perplexity = 8.401799 (15.105 sec)
I1112 18:25:07.280203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662032
I1112 18:25:11.796203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2284 into logdir\run1\train\model.ckpt.
I1112 18:25:22.702204 10460 basic_session_run_hooks.py:260] Accuracy = 0.4881329, Global Step = 2290, Loss = 1.8735491, Perplexity = 6.5113654 (15.423 sec)
I1112 18:25:22.703203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.648382
I1112 18:25:39.090203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.641474
I1112 18:25:39.091203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4765745, Global Step = 2300, Loss = 1.9511851, Perplexity = 7.037022 (16.389 sec)
I1112 18:25:39.092203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.610165
I1112 18:25:54.047228 10460 basic_session_run_hooks.py:260] Accuracy = 0.4660135, Global Step = 2310, Loss = 2.2269096, Perplexity = 9.271171 (14.956 sec)
I1112 18:25:54.048229 10460 basic_session_run_hooks.py:692] global_step/sec: 0.668627
I1112 18:26:09.102203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5235079, Global Step = 2320, Loss = 1.9009484, Perplexity = 6.6922383 (15.055 sec)
I1112 18:26:09.103203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664232
I1112 18:26:12.107203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2323 into logdir\run1\train\model.ckpt.
I1112 18:26:24.915204 10460 basic_session_run_hooks.py:260] Accuracy = 0.47557935, Global Step = 2330, Loss = 2.1171775, Perplexity = 8.307656 (15.813 sec)
I1112 18:26:24.916203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.632391
I1112 18:26:41.088203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4880316, Global Step = 2340, Loss = 1.9989984, Perplexity = 7.3816586 (16.173 sec)
I1112 18:26:41.088203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.618353
I1112 18:26:56.094202 10460 basic_session_run_hooks.py:260] Accuracy = 0.47637472, Global Step = 2350, Loss = 2.121429, Perplexity = 8.343051 (15.006 sec)
I1112 18:26:56.095226 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666355
I1112 18:27:11.213202 10460 basic_session_run_hooks.py:260] Accuracy = 0.46673498, Global Step = 2360, Loss = 2.0513446, Perplexity = 7.7783527 (15.119 sec)
I1112 18:27:11.214203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.66142
I1112 18:27:12.719203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2362 into logdir\run1\train\model.ckpt.
I1112 18:27:27.453205 10460 basic_session_run_hooks.py:260] Accuracy = 0.46389642, Global Step = 2370, Loss = 2.1139867, Perplexity = 8.28119 (16.240 sec)
I1112 18:27:27.455204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.615726
I1112 18:27:43.151203 10460 basic_session_run_hooks.py:260] Accuracy = 0.50766224, Global Step = 2380, Loss = 1.9007691, Perplexity = 6.691039 (15.698 sec)
I1112 18:27:43.152204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.637064
I1112 18:27:58.198202 10460 basic_session_run_hooks.py:260] Accuracy = 0.50411826, Global Step = 2390, Loss = 2.0022914, Perplexity = 7.406007 (15.047 sec)
I1112 18:27:58.198202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664629
I1112 18:28:13.285203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.648529
I1112 18:28:13.287203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2401 into logdir\run1\train\model.ckpt.
I1112 18:28:13.621232 10460 basic_session_run_hooks.py:260] Accuracy = 0.4946177, Global Step = 2400, Loss = 1.9575218, Perplexity = 7.081755 (15.423 sec)
I1112 18:28:13.622204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.64834
I1112 18:28:30.120203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5028672, Global Step = 2410, Loss = 1.9533006, Perplexity = 7.051924 (16.499 sec)
I1112 18:28:30.120203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.606134
I1112 18:28:45.159203 10460 basic_session_run_hooks.py:260] Accuracy = 0.48885146, Global Step = 2420, Loss = 1.9161415, Perplexity = 6.7946906 (15.039 sec)
I1112 18:28:45.160203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664894
I1112 18:29:00.177203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4653012, Global Step = 2430, Loss = 2.0578675, Perplexity = 7.829256 (15.018 sec)
I1112 18:29:00.178203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665868
I1112 18:29:13.763203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2440 into logdir\run1\train\model.ckpt.
I1112 18:29:15.588203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4867137, Global Step = 2440, Loss = 2.063343, Perplexity = 7.872243 (15.411 sec)
I1112 18:29:15.589204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.648887
I1112 18:29:32.076203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4727532, Global Step = 2450, Loss = 2.0000188, Perplexity = 7.3891954 (16.488 sec)
I1112 18:29:32.077203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.606502
I1112 18:29:47.165203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4803705, Global Step = 2460, Loss = 2.0835881, Perplexity = 8.033241 (15.089 sec)
I1112 18:29:47.165203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662778
I1112 18:30:02.282203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5111706, Global Step = 2470, Loss = 1.9234924, Perplexity = 6.844822 (15.117 sec)
I1112 18:30:02.283204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661463
I1112 18:30:14.327203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2479 into logdir\run1\train\model.ckpt.
I1112 18:30:17.643203 10460 basic_session_run_hooks.py:260] Accuracy = 0.47843793, Global Step = 2480, Loss = 2.066075, Perplexity = 7.8937798 (15.361 sec)
I1112 18:30:17.644203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.650999
I1112 18:30:34.138203 10460 basic_session_run_hooks.py:260] Accuracy = 0.52500236, Global Step = 2490, Loss = 1.8963878, Perplexity = 6.661787 (16.495 sec)
I1112 18:30:34.138203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.606281
I1112 18:30:49.158203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.641548
I1112 18:30:49.159204 10460 basic_session_run_hooks.py:260] Accuracy = 0.49903318, Global Step = 2500, Loss = 1.9399126, Perplexity = 6.9581428 (15.021 sec)
I1112 18:30:49.160203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.66569
I1112 18:31:04.249203 10460 basic_session_run_hooks.py:260] Accuracy = 0.49886847, Global Step = 2510, Loss = 1.9882315, Perplexity = 7.3026085 (15.090 sec)
I1112 18:31:04.249203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662734
I1112 18:31:14.730203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2518 into logdir\run1\train\model.ckpt.
I1112 18:31:19.563205 10460 basic_session_run_hooks.py:260] Accuracy = 0.46525255, Global Step = 2520, Loss = 2.0537536, Perplexity = 7.7971134 (15.314 sec)
I1112 18:31:19.564203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.652955
I1112 18:31:35.987203 10460 basic_session_run_hooks.py:260] Accuracy = 0.55769867, Global Step = 2530, Loss = 1.8904155, Perplexity = 6.6221204 (16.424 sec)
I1112 18:31:35.987203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.608902
I1112 18:31:51.129203 10460 basic_session_run_hooks.py:260] Accuracy = 0.51701784, Global Step = 2540, Loss = 1.9936796, Perplexity = 7.342502 (15.142 sec)
I1112 18:31:51.130203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.660371
I1112 18:32:06.171203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5195969, Global Step = 2550, Loss = 1.9941945, Perplexity = 7.3462834 (15.042 sec)
I1112 18:32:06.171203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664849
I1112 18:32:15.159203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2557 into logdir\run1\train\model.ckpt.
I1112 18:32:21.502203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5132602, Global Step = 2560, Loss = 1.9399172, Perplexity = 6.958175 (15.331 sec)
I1112 18:32:21.503203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.652231
I1112 18:32:38.133203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5241463, Global Step = 2570, Loss = 1.8978283, Perplexity = 6.6713905 (16.631 sec)
I1112 18:32:38.134203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.601287
I1112 18:32:53.123203 10460 basic_session_run_hooks.py:260] Accuracy = 0.47683433, Global Step = 2580, Loss = 2.0858133, Perplexity = 8.051137 (14.990 sec)
I1112 18:32:53.124203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.667111
I1112 18:33:08.209204 10460 basic_session_run_hooks.py:260] Accuracy = 0.46681476, Global Step = 2590, Loss = 2.0395389, Perplexity = 7.6870637 (15.086 sec)
I1112 18:33:08.209204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.66291
I1112 18:33:15.761204 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2596 into logdir\run1\train\model.ckpt.
I1112 18:33:23.902204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.646229
I1112 18:33:23.903204 10460 basic_session_run_hooks.py:260] Accuracy = 0.5332635, Global Step = 2600, Loss = 1.917477, Perplexity = 6.803771 (15.694 sec)
I1112 18:33:23.906204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.637064
I1112 18:33:40.623203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4983237, Global Step = 2610, Loss = 2.0077844, Perplexity = 7.4467998 (16.720 sec)
I1112 18:33:40.624203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.598158
I1112 18:33:55.823203 10460 basic_session_run_hooks.py:260] Accuracy = 0.51657486, Global Step = 2620, Loss = 1.9305567, Perplexity = 6.8933463 (15.200 sec)
I1112 18:33:55.824204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.657895
I1112 18:34:10.778203 10460 basic_session_run_hooks.py:260] Accuracy = 0.52768904, Global Step = 2630, Loss = 1.8904167, Perplexity = 6.622128 (14.955 sec)
I1112 18:34:10.779234 10460 basic_session_run_hooks.py:692] global_step/sec: 0.668671
I1112 18:34:16.844204 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2635 into logdir\run1\train\model.ckpt.
I1112 18:34:26.897203 10460 basic_session_run_hooks.py:260] Accuracy = 0.538533, Global Step = 2640, Loss = 1.8786838, Perplexity = 6.5448847 (16.118 sec)
I1112 18:34:26.899204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.620349
I1112 18:34:42.730203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5262216, Global Step = 2650, Loss = 1.942469, Perplexity = 6.9759536 (15.834 sec)
I1112 18:34:42.731203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.631632
I1112 18:34:57.807203 10460 basic_session_run_hooks.py:260] Accuracy = 0.49835426, Global Step = 2660, Loss = 2.0065157, Perplexity = 7.4373584 (15.077 sec)
I1112 18:34:57.807203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663306
I1112 18:35:12.931227 10460 basic_session_run_hooks.py:260] Accuracy = 0.4891217, Global Step = 2670, Loss = 2.1032047, Perplexity = 8.192382 (15.124 sec)
I1112 18:35:12.932203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661157
I1112 18:35:17.430203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2674 into logdir\run1\train\model.ckpt.
I1112 18:35:29.472204 10460 basic_session_run_hooks.py:260] Accuracy = 0.5130483, Global Step = 2680, Loss = 1.9531648, Perplexity = 7.050967 (16.541 sec)
I1112 18:35:29.473205 10460 basic_session_run_hooks.py:692] global_step/sec: 0.604558
I1112 18:35:44.719203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5151751, Global Step = 2690, Loss = 1.8974364, Perplexity = 6.668776 (15.247 sec)
I1112 18:35:44.720203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.655867
I1112 18:35:59.693203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.641886
I1112 18:35:59.693203 10460 basic_session_run_hooks.py:260] Accuracy = 0.49123967, Global Step = 2700, Loss = 2.012736, Perplexity = 7.4837656 (14.974 sec)
I1112 18:35:59.694203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.667824
I1112 18:36:14.703204 10460 basic_session_run_hooks.py:260] Accuracy = 0.5020977, Global Step = 2710, Loss = 2.017222, Perplexity = 7.5174117 (15.010 sec)
I1112 18:36:14.704204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666222
I1112 18:36:17.740202 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2713 into logdir\run1\train\model.ckpt.
I1112 18:36:31.502203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5201296, Global Step = 2720, Loss = 1.969752, Perplexity = 7.168898 (16.799 sec)
I1112 18:36:31.503203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.595274
I1112 18:36:46.490203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5218234, Global Step = 2730, Loss = 2.0758214, Perplexity = 7.9710913 (14.988 sec)
I1112 18:36:46.491203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.6672
I1112 18:37:01.564203 10460 basic_session_run_hooks.py:260] Accuracy = 0.519073, Global Step = 2740, Loss = 2.0283966, Perplexity = 7.601887 (15.073 sec)
I1112 18:37:01.564203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663438
I1112 18:37:16.551203 10460 basic_session_run_hooks.py:260] Accuracy = 0.53535354, Global Step = 2750, Loss = 1.9251624, Perplexity = 6.8562627 (14.988 sec)
I1112 18:37:16.552203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.6672
I1112 18:37:18.056203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2752 into logdir\run1\train\model.ckpt.
I1112 18:37:33.322203 10460 basic_session_run_hooks.py:260] Accuracy = 0.518017, Global Step = 2760, Loss = 1.9800645, Perplexity = 7.2432103 (16.771 sec)
I1112 18:37:33.323204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.596267
I1112 18:37:48.500204 10460 basic_session_run_hooks.py:260] Accuracy = 0.52455693, Global Step = 2770, Loss = 2.0015638, Perplexity = 7.40062 (15.178 sec)
I1112 18:37:48.501244 10460 basic_session_run_hooks.py:692] global_step/sec: 0.658847
I1112 18:38:03.479203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5454867, Global Step = 2780, Loss = 1.8630974, Perplexity = 6.4436646 (14.979 sec)
I1112 18:38:03.479203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.667648
I1112 18:38:18.555203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2791 into logdir\run1\train\model.ckpt.
I1112 18:38:18.882233 10460 basic_session_run_hooks.py:260] Accuracy = 0.50284654, Global Step = 2790, Loss = 1.9932668, Perplexity = 7.339472 (15.403 sec)
I1112 18:38:18.883229 10460 basic_session_run_hooks.py:692] global_step/sec: 0.649181
I1112 18:38:35.490203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.641861
I1112 18:38:35.491204 10460 basic_session_run_hooks.py:260] Accuracy = 0.51977843, Global Step = 2800, Loss = 1.9484406, Perplexity = 7.017735 (16.608 sec)
I1112 18:38:35.492204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.602084
I1112 18:38:50.546205 10460 basic_session_run_hooks.py:260] Accuracy = 0.51705813, Global Step = 2810, Loss = 1.9277989, Perplexity = 6.874362 (15.056 sec)
I1112 18:38:50.546205 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664275
I1112 18:39:05.685203 10460 basic_session_run_hooks.py:260] Accuracy = 0.54002315, Global Step = 2820, Loss = 1.8889862, Perplexity = 6.612662 (15.139 sec)
I1112 18:39:05.686203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.660502
I1112 18:39:19.180203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2830 into logdir\run1\train\model.ckpt.
I1112 18:39:21.018203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5371264, Global Step = 2830, Loss = 1.9112549, Perplexity = 6.7615685 (15.333 sec)
I1112 18:39:21.019203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.652188
I1112 18:39:37.464203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5429251, Global Step = 2840, Loss = 1.9159589, Perplexity = 6.79345 (16.446 sec)
I1112 18:39:37.465203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.608051
I1112 18:39:52.522204 10460 basic_session_run_hooks.py:260] Accuracy = 0.5174731, Global Step = 2850, Loss = 1.9985696, Perplexity = 7.3784943 (15.058 sec)
I1112 18:39:52.522204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664143
I1112 18:40:07.495204 10460 basic_session_run_hooks.py:260] Accuracy = 0.5277995, Global Step = 2860, Loss = 1.927266, Perplexity = 6.8707 (14.973 sec)
I1112 18:40:07.496203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.667824
I1112 18:40:19.566202 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2869 into logdir\run1\train\model.ckpt.
I1112 18:40:22.945204 10460 basic_session_run_hooks.py:260] Accuracy = 0.5245406, Global Step = 2870, Loss = 1.9468042, Perplexity = 7.006261 (15.450 sec)
I1112 18:40:22.946206 10460 basic_session_run_hooks.py:692] global_step/sec: 0.647249
I1112 18:40:39.625204 10460 basic_session_run_hooks.py:260] Accuracy = 0.53073066, Global Step = 2880, Loss = 1.972091, Perplexity = 7.1856856 (16.680 sec)
I1112 18:40:39.626204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.59952
I1112 18:40:54.690203 10460 basic_session_run_hooks.py:260] Accuracy = 0.51607144, Global Step = 2890, Loss = 1.9744283, Perplexity = 7.202501 (15.065 sec)
I1112 18:40:54.691203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663834
I1112 18:41:09.681203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.64855
I1112 18:41:09.681203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5094933, Global Step = 2900, Loss = 2.0504887, Perplexity = 7.7716985 (14.991 sec)
I1112 18:41:09.682203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.667022
I1112 18:41:20.147203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2908 into logdir\run1\train\model.ckpt.
I1112 18:41:25.480202 10460 basic_session_run_hooks.py:260] Accuracy = 0.51867056, Global Step = 2910, Loss = 1.968214, Perplexity = 7.1578817 (15.799 sec)
I1112 18:41:25.481203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.632951
I1112 18:41:41.584203 10460 basic_session_run_hooks.py:260] Accuracy = 0.52178633, Global Step = 2920, Loss = 2.0721176, Perplexity = 7.941622 (16.104 sec)
I1112 18:41:41.585203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.620964
I1112 18:41:56.721203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5227783, Global Step = 2930, Loss = 2.006121, Perplexity = 7.434423 (15.137 sec)
I1112 18:41:56.721203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.660677
I1112 18:42:11.805203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5205276, Global Step = 2940, Loss = 1.9277356, Perplexity = 6.873927 (15.084 sec)
I1112 18:42:11.805203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662954
I1112 18:42:20.724203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2947 into logdir\run1\train\model.ckpt.
I1112 18:42:28.038204 10460 basic_session_run_hooks.py:260] Accuracy = 0.53768617, Global Step = 2950, Loss = 1.8430318, Perplexity = 6.3156567 (16.233 sec)
I1112 18:42:28.041204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.615915
I1112 18:42:43.518203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5204017, Global Step = 2960, Loss = 1.9854218, Perplexity = 7.282118 (15.480 sec)
I1112 18:42:43.518203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.64612
I1112 18:42:58.557203 10460 basic_session_run_hooks.py:260] Accuracy = 0.50117296, Global Step = 2970, Loss = 2.029247, Perplexity = 7.6083555 (15.039 sec)
I1112 18:42:58.558204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664894
I1112 18:43:13.622203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5021113, Global Step = 2980, Loss = 1.8975971, Perplexity = 6.669848 (15.065 sec)
I1112 18:43:13.623203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.66379
I1112 18:43:21.122202 10460 basic_session_run_hooks.py:606] Saving checkpoints for 2986 into logdir\run1\train\model.ckpt.
I1112 18:43:30.418203 10460 basic_session_run_hooks.py:260] Accuracy = 0.55135936, Global Step = 2990, Loss = 1.8692453, Perplexity = 6.483402 (16.796 sec)
I1112 18:43:30.419203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.59538
I1112 18:43:45.498203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.641774
I1112 18:43:45.499203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5184193, Global Step = 3000, Loss = 2.0009522, Perplexity = 7.3960953 (15.081 sec)
I1112 18:43:45.500203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.66313
I1112 18:44:00.594202 10460 basic_session_run_hooks.py:260] Accuracy = 0.54339975, Global Step = 3010, Loss = 1.938602, Perplexity = 6.9490294 (15.095 sec)
I1112 18:44:00.595203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662427
I1112 18:44:15.694204 10460 basic_session_run_hooks.py:260] Accuracy = 0.54105115, Global Step = 3020, Loss = 1.881695, Perplexity = 6.5646224 (15.100 sec)
I1112 18:44:15.695203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662252
I1112 18:44:21.716203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 3025 into logdir\run1\train\model.ckpt.
I1112 18:44:32.487203 10460 basic_session_run_hooks.py:260] Accuracy = 0.55666345, Global Step = 3030, Loss = 1.8222737, Perplexity = 6.185908 (16.793 sec)
I1112 18:44:32.488203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.595486
I1112 18:44:47.601203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5088823, Global Step = 3040, Loss = 1.8979387, Perplexity = 6.6721272 (15.114 sec)
I1112 18:44:47.601203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661682
I1112 18:45:02.665203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5647377, Global Step = 3050, Loss = 1.7907809, Perplexity = 5.9941316 (15.064 sec)
I1112 18:45:02.666203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.66379
I1112 18:45:17.652203 10460 basic_session_run_hooks.py:260] Accuracy = 0.52823746, Global Step = 3060, Loss = 1.9444749, Perplexity = 6.9899607 (14.987 sec)
I1112 18:45:17.653203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.667245
I1112 18:45:22.190203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 3064 into logdir\run1\train\model.ckpt.
I1112 18:45:34.478204 10460 basic_session_run_hooks.py:260] Accuracy = 0.51708096, Global Step = 3070, Loss = 1.9168562, Perplexity = 6.799548 (16.826 sec)
I1112 18:45:34.478204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.594354
I1112 18:45:49.617203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5457477, Global Step = 3080, Loss = 1.8479017, Perplexity = 6.3464885 (15.139 sec)
I1112 18:45:49.617203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.660546
I1112 18:46:04.680202 10460 basic_session_run_hooks.py:260] Accuracy = 0.55050236, Global Step = 3090, Loss = 1.8254765, Perplexity = 6.2057514 (15.063 sec)
I1112 18:46:04.681203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663834
I1112 18:46:19.732203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.64837
I1112 18:46:19.732203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5086051, Global Step = 3100, Loss = 1.961752, Perplexity = 7.111777 (15.052 sec)
I1112 18:46:19.733204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664363
I1112 18:46:22.706203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 3103 into logdir\run1\train\model.ckpt.
I1112 18:46:36.639203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5328527, Global Step = 3110, Loss = 1.8438619, Perplexity = 6.320902 (16.907 sec)
I1112 18:46:36.640203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.591471
I1112 18:46:51.602203 10460 basic_session_run_hooks.py:260] Accuracy = 0.502272, Global Step = 3120, Loss = 2.011154, Perplexity = 7.4719343 (14.963 sec)
I1112 18:46:51.603203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.668315
I1112 18:47:06.674203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5061335, Global Step = 3130, Loss = 2.0038095, Perplexity = 7.4172583 (15.072 sec)
I1112 18:47:06.675203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663482
I1112 18:47:21.831203 10460 basic_session_run_hooks.py:260] Accuracy = 0.52444977, Global Step = 3140, Loss = 1.9231434, Perplexity = 6.8424335 (15.157 sec)
I1112 18:47:21.832203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.659761
I1112 18:47:23.341202 10460 basic_session_run_hooks.py:606] Saving checkpoints for 3142 into logdir\run1\train\model.ckpt.
I1112 18:47:38.615203 10460 basic_session_run_hooks.py:260] Accuracy = 0.52748865, Global Step = 3150, Loss = 1.872489, Perplexity = 6.504466 (16.784 sec)
I1112 18:47:38.616203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.595806
I1112 18:47:53.679203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5101237, Global Step = 3160, Loss = 1.9583914, Perplexity = 7.087917 (15.064 sec)
I1112 18:47:53.680203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663834
I1112 18:48:08.776202 10460 basic_session_run_hooks.py:260] Accuracy = 0.52355206, Global Step = 3170, Loss = 1.9039358, Perplexity = 6.7122602 (15.097 sec)
I1112 18:48:08.777203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662383
I1112 18:48:23.791203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 3181 into logdir\run1\train\model.ckpt.
I1112 18:48:24.121227 10460 basic_session_run_hooks.py:260] Accuracy = 0.51706773, Global Step = 3180, Loss = 1.9768276, Perplexity = 7.219803 (15.345 sec)
I1112 18:48:24.122204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.651678
I1112 18:48:40.460203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5158687, Global Step = 3190, Loss = 1.9221501, Perplexity = 6.83564 (16.339 sec)
I1112 18:48:40.460203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.61207
I1112 18:48:55.581203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.641643
I1112 18:48:55.582202 10460 basic_session_run_hooks.py:260] Accuracy = 0.46426433, Global Step = 3200, Loss = 2.1776989, Perplexity = 8.825973 (15.122 sec)
I1112 18:48:55.582202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661288
I1112 18:49:10.696203 10460 basic_session_run_hooks.py:260] Accuracy = 0.47274444, Global Step = 3210, Loss = 1.982233, Perplexity = 7.2589345 (15.114 sec)
I1112 18:49:10.697203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661594
I1112 18:49:24.215203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 3220 into logdir\run1\train\model.ckpt.
I1112 18:49:26.215204 10460 basic_session_run_hooks.py:260] Accuracy = 0.53352576, Global Step = 3220, Loss = 1.9559488, Perplexity = 7.070625 (15.519 sec)
I1112 18:49:26.216209 10460 basic_session_run_hooks.py:692] global_step/sec: 0.644371
I1112 18:49:42.447203 10460 basic_session_run_hooks.py:260] Accuracy = 0.50666845, Global Step = 3230, Loss = 2.0854735, Perplexity = 8.048402 (16.232 sec)
I1112 18:49:42.448203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.616067
I1112 18:49:57.573203 10460 basic_session_run_hooks.py:260] Accuracy = 0.51810884, Global Step = 3240, Loss = 1.9512998, Perplexity = 7.0378294 (15.126 sec)
I1112 18:49:57.574203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661113
I1112 18:50:12.709203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5603403, Global Step = 3250, Loss = 1.8119761, Perplexity = 6.122534 (15.136 sec)
I1112 18:50:12.709203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.66072
I1112 18:50:24.814203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 3259 into logdir\run1\train\model.ckpt.
I1112 18:50:28.588203 10460 basic_session_run_hooks.py:260] Accuracy = 0.54634315, Global Step = 3260, Loss = 1.8169743, Perplexity = 6.1532125 (15.879 sec)
I1112 18:50:28.589220 10460 basic_session_run_hooks.py:692] global_step/sec: 0.629722
I1112 18:50:44.593203 10460 basic_session_run_hooks.py:260] Accuracy = 0.50786984, Global Step = 3270, Loss = 1.9687392, Perplexity = 7.161641 (16.005 sec)
I1112 18:50:44.593203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.624844
I1112 18:50:59.623203 10460 basic_session_run_hooks.py:260] Accuracy = 0.527817, Global Step = 3280, Loss = 1.9520535, Perplexity = 7.043136 (15.030 sec)
I1112 18:50:59.624203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665292
I1112 18:51:14.662203 10460 basic_session_run_hooks.py:260] Accuracy = 0.48221594, Global Step = 3290, Loss = 2.1241581, Perplexity = 8.365852 (15.039 sec)
I1112 18:51:14.663203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664938
I1112 18:51:25.166203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 3298 into logdir\run1\train\model.ckpt.
I1112 18:51:30.824204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.644151
I1112 18:51:30.825204 10460 basic_session_run_hooks.py:260] Accuracy = 0.5305118, Global Step = 3300, Loss = 1.8802575, Perplexity = 6.5551925 (16.163 sec)
I1112 18:51:30.827204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.618659
I1112 18:51:46.425203 10460 basic_session_run_hooks.py:260] Accuracy = 0.52691776, Global Step = 3310, Loss = 1.887205, Perplexity = 6.6008935 (15.600 sec)
I1112 18:51:46.426203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.641067
I1112 18:52:01.433203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5439526, Global Step = 3320, Loss = 1.7918954, Perplexity = 6.000816 (15.008 sec)
I1112 18:52:01.434203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666311
I1112 18:52:16.540204 10460 basic_session_run_hooks.py:260] Accuracy = 0.5328653, Global Step = 3330, Loss = 1.9359163, Perplexity = 6.930392 (15.107 sec)
I1112 18:52:16.541204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661945
I1112 18:52:25.574203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 3337 into logdir\run1\train\model.ckpt.
I1112 18:52:33.036203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5416852, Global Step = 3340, Loss = 1.8401268, Perplexity = 6.297336 (16.496 sec)
I1112 18:52:33.037206 10460 basic_session_run_hooks.py:692] global_step/sec: 0.606207
I1112 18:52:48.447203 10460 basic_session_run_hooks.py:260] Accuracy = 0.53237486, Global Step = 3350, Loss = 1.874278, Perplexity = 6.5161123 (15.411 sec)
I1112 18:52:48.448203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.648887
I1112 18:53:03.529203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5099538, Global Step = 3360, Loss = 2.0360003, Perplexity = 7.6599097 (15.082 sec)
I1112 18:53:03.529203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663086
I1112 18:53:18.625202 10460 basic_session_run_hooks.py:260] Accuracy = 0.5640913, Global Step = 3370, Loss = 1.7375474, Perplexity = 5.6833873 (15.096 sec)
I1112 18:53:18.626203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662383
I1112 18:53:26.127203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 3376 into logdir\run1\train\model.ckpt.
I1112 18:53:35.331203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5468386, Global Step = 3380, Loss = 1.8313729, Perplexity = 6.2424507 (16.706 sec)
I1112 18:53:35.332203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.598587
I1112 18:53:50.447203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5142952, Global Step = 3390, Loss = 1.9855726, Perplexity = 7.283216 (15.116 sec)
I1112 18:53:50.448204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661594
I1112 18:54:05.513203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.646458
I1112 18:54:05.514202 10460 basic_session_run_hooks.py:260] Accuracy = 0.51094025, Global Step = 3400, Loss = 1.9784808, Perplexity = 7.231748 (15.067 sec)
I1112 18:54:05.514202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663702
I1112 18:54:20.529202 10460 basic_session_run_hooks.py:260] Accuracy = 0.50117475, Global Step = 3410, Loss = 2.0383506, Perplexity = 7.677934 (15.015 sec)
I1112 18:54:20.530203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665956
I1112 18:54:26.559203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 3415 into logdir\run1\train\model.ckpt.
I1112 18:54:37.394203 10460 basic_session_run_hooks.py:260] Accuracy = 0.51428574, Global Step = 3420, Loss = 2.012525, Perplexity = 7.4821863 (16.865 sec)
I1112 18:54:37.394203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.592979
I1112 18:54:52.472203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5180702, Global Step = 3430, Loss = 1.9695165, Perplexity = 7.1672106 (15.078 sec)
I1112 18:54:52.473203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663174
I1112 18:55:07.520203 10460 basic_session_run_hooks.py:260] Accuracy = 0.51660585, Global Step = 3440, Loss = 1.9421241, Perplexity = 6.973548 (15.048 sec)
I1112 18:55:07.521203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.66454
I1112 18:55:22.617202 10460 basic_session_run_hooks.py:260] Accuracy = 0.5312064, Global Step = 3450, Loss = 1.9887921, Perplexity = 7.306702 (15.097 sec)
I1112 18:55:22.617202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662427
I1112 18:55:27.120203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 3454 into logdir\run1\train\model.ckpt.
I1112 18:55:39.350203 10460 basic_session_run_hooks.py:260] Accuracy = 0.51922584, Global Step = 3460, Loss = 2.0309837, Perplexity = 7.62158 (16.733 sec)
I1112 18:55:39.351203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.597586
I1112 18:55:54.418203 10460 basic_session_run_hooks.py:260] Accuracy = 0.55930924, Global Step = 3470, Loss = 1.8777353, Perplexity = 6.5386796 (15.068 sec)
I1112 18:55:54.419203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663658
I1112 18:56:09.479202 10460 basic_session_run_hooks.py:260] Accuracy = 0.5731384, Global Step = 3480, Loss = 1.7265861, Perplexity = 5.62143 (15.061 sec)
I1112 18:56:09.480203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663967
I1112 18:56:24.545203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5261276, Global Step = 3490, Loss = 1.9307346, Perplexity = 6.894573 (15.066 sec)
I1112 18:56:24.546204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663746
I1112 18:56:27.576203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 3493 into logdir\run1\train\model.ckpt.
I1112 18:56:41.454204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.641268
I1112 18:56:41.455204 10460 basic_session_run_hooks.py:260] Accuracy = 0.51389366, Global Step = 3500, Loss = 1.9459363, Perplexity = 7.000183 (16.910 sec)
I1112 18:56:41.456204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.591366
I1112 18:56:56.442203 10460 basic_session_run_hooks.py:260] Accuracy = 0.53695315, Global Step = 3510, Loss = 1.8328105, Perplexity = 6.2514315 (14.987 sec)
I1112 18:56:56.443203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.667245
I1112 18:57:11.534203 10460 basic_session_run_hooks.py:260] Accuracy = 0.54054916, Global Step = 3520, Loss = 1.8552346, Perplexity = 6.393198 (15.092 sec)
I1112 18:57:11.535203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662603
I1112 18:57:26.605203 10460 basic_session_run_hooks.py:260] Accuracy = 0.51940477, Global Step = 3530, Loss = 1.9144478, Perplexity = 6.783192 (15.071 sec)
I1112 18:57:26.605203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.66357
I1112 18:57:28.132203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 3532 into logdir\run1\train\model.ckpt.
I1112 18:57:43.433203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5473017, Global Step = 3540, Loss = 1.8116363, Perplexity = 6.120455 (16.828 sec)
I1112 18:57:43.434203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.594212
I1112 18:57:58.509203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5807255, Global Step = 3550, Loss = 1.7123867, Perplexity = 5.5421734 (15.076 sec)
I1112 18:57:58.510203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663306
I1112 18:58:13.546203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5383903, Global Step = 3560, Loss = 1.9129584, Perplexity = 6.773097 (15.037 sec)
I1112 18:58:13.547203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665026
I1112 18:58:28.569203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 3571 into logdir\run1\train\model.ckpt.
I1112 18:58:28.888232 10460 basic_session_run_hooks.py:260] Accuracy = 0.539063, Global Step = 3570, Loss = 1.8450178, Perplexity = 6.3282127 (15.342 sec)
I1112 18:58:28.889222 10460 basic_session_run_hooks.py:692] global_step/sec: 0.651805
I1112 18:58:45.438203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5448825, Global Step = 3580, Loss = 1.8537123, Perplexity = 6.3834734 (16.550 sec)
I1112 18:58:45.439203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.60423
I1112 18:59:00.451203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5269069, Global Step = 3590, Loss = 1.9282206, Perplexity = 6.8772616 (15.013 sec)
I1112 18:59:00.452203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666089
I1112 18:59:15.575203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.648841
I1112 18:59:15.575203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5413636, Global Step = 3600, Loss = 1.9078133, Perplexity = 6.738338 (15.124 sec)
I1112 18:59:15.576203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661201
I1112 18:59:29.113203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 3610 into logdir\run1\train\model.ckpt.
I1112 18:59:31.083205 10460 basic_session_run_hooks.py:260] Accuracy = 0.5341353, Global Step = 3610, Loss = 1.8051989, Perplexity = 6.081181 (15.508 sec)
I1112 18:59:31.084204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.644828
I1112 18:59:47.394203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5483413, Global Step = 3620, Loss = 1.8719277, Perplexity = 6.500816 (16.311 sec)
I1112 18:59:47.395204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.613083
I1112 19:00:02.542203 10460 basic_session_run_hooks.py:260] Accuracy = 0.52948815, Global Step = 3630, Loss = 1.9389712, Perplexity = 6.951596 (15.148 sec)
I1112 19:00:02.543203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.660153
I1112 19:00:17.625203 10460 basic_session_run_hooks.py:260] Accuracy = 0.52168435, Global Step = 3640, Loss = 1.8353854, Perplexity = 6.267549 (15.083 sec)
I1112 19:00:17.625203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663042
I1112 19:00:29.654203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 3649 into logdir\run1\train\model.ckpt.
I1112 19:00:33.450203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5465106, Global Step = 3650, Loss = 1.8003008, Perplexity = 6.0514674 (15.825 sec)
I1112 19:00:33.452204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.631832
I1112 19:00:49.513203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5500581, Global Step = 3660, Loss = 1.7947425, Perplexity = 6.017925 (16.063 sec)
I1112 19:00:49.513203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.622626
I1112 19:01:04.581204 10460 basic_session_run_hooks.py:260] Accuracy = 0.48881838, Global Step = 3670, Loss = 1.9855523, Perplexity = 7.2830687 (15.068 sec)
I1112 19:01:04.582247 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663612
I1112 19:01:19.673203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5296057, Global Step = 3680, Loss = 1.8731189, Perplexity = 6.5085645 (15.092 sec)
I1112 19:01:19.674203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662605
I1112 19:01:30.240203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 3688 into logdir\run1\train\model.ckpt.
I1112 19:01:35.982203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5301594, Global Step = 3690, Loss = 1.9583539, Perplexity = 7.0876503 (16.309 sec)
I1112 19:01:35.983204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.613158
I1112 19:01:51.674203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.640619
I1112 19:01:51.675204 10460 basic_session_run_hooks.py:260] Accuracy = 0.53099173, Global Step = 3700, Loss = 1.858564, Perplexity = 6.4145193 (15.693 sec)
I1112 19:01:51.676204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.637227
I1112 19:02:06.741203 10460 basic_session_run_hooks.py:260] Accuracy = 0.53483784, Global Step = 3710, Loss = 1.925559, Perplexity = 6.858982 (15.066 sec)
I1112 19:02:06.742203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663746
I1112 19:02:21.945203 10460 basic_session_run_hooks.py:260] Accuracy = 0.56571996, Global Step = 3720, Loss = 1.7007272, Perplexity = 5.4779296 (15.204 sec)
I1112 19:02:21.946203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.657765
I1112 19:02:30.954203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 3727 into logdir\run1\train\model.ckpt.
I1112 19:02:38.533203 10460 basic_session_run_hooks.py:260] Accuracy = 0.51544, Global Step = 3730, Loss = 1.9146034, Perplexity = 6.784247 (16.588 sec)
I1112 19:02:38.535207 10460 basic_session_run_hooks.py:692] global_step/sec: 0.602773
I1112 19:02:53.696203 10460 basic_session_run_hooks.py:260] Accuracy = 0.51483, Global Step = 3740, Loss = 1.9146644, Perplexity = 6.7846613 (15.163 sec)
I1112 19:02:53.697203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.659544
I1112 19:03:08.717203 10460 basic_session_run_hooks.py:260] Accuracy = 0.54057455, Global Step = 3750, Loss = 1.8568751, Perplexity = 6.4036946 (15.021 sec)
I1112 19:03:08.718204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665735
I1112 19:03:23.843203 10460 basic_session_run_hooks.py:260] Accuracy = 0.49689606, Global Step = 3760, Loss = 2.0128453, Perplexity = 7.4845824 (15.126 sec)
I1112 19:03:23.843203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661157
I1112 19:03:31.343203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 3766 into logdir\run1\train\model.ckpt.
I1112 19:03:40.597203 10460 basic_session_run_hooks.py:260] Accuracy = 0.50423104, Global Step = 3770, Loss = 1.919368, Perplexity = 6.816649 (16.754 sec)
I1112 19:03:40.597203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.596872
I1112 19:03:55.665203 10460 basic_session_run_hooks.py:260] Accuracy = 0.56732166, Global Step = 3780, Loss = 1.7570131, Perplexity = 5.795102 (15.068 sec)
I1112 19:03:55.665203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663658
I1112 19:04:10.687203 10460 basic_session_run_hooks.py:260] Accuracy = 0.51307756, Global Step = 3790, Loss = 1.9300992, Perplexity = 6.890194 (15.022 sec)
I1112 19:04:10.688203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665646
I1112 19:04:25.802203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.648811
I1112 19:04:25.803203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5159533, Global Step = 3800, Loss = 1.8715773, Perplexity = 6.4985385 (15.116 sec)
I1112 19:04:25.804204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661551
I1112 19:04:31.741203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 3805 into logdir\run1\train\model.ckpt.
I1112 19:04:42.537204 10460 basic_session_run_hooks.py:260] Accuracy = 0.5167952, Global Step = 3810, Loss = 1.9367115, Perplexity = 6.935905 (16.734 sec)
I1112 19:04:42.538204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.597586
I1112 19:04:57.496204 10460 basic_session_run_hooks.py:260] Accuracy = 0.54003817, Global Step = 3820, Loss = 1.9988115, Perplexity = 7.380279 (14.959 sec)
I1112 19:04:57.496204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.668539
I1112 19:05:12.500203 10460 basic_session_run_hooks.py:260] Accuracy = 0.541028, Global Step = 3830, Loss = 1.806636, Perplexity = 6.0899262 (15.004 sec)
I1112 19:05:12.501203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666445
I1112 19:05:27.548203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5211885, Global Step = 3840, Loss = 1.879062, Perplexity = 6.5473604 (15.048 sec)
I1112 19:05:27.548203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664584
I1112 19:05:32.107203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 3844 into logdir\run1\train\model.ckpt.
I1112 19:05:44.377203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5310219, Global Step = 3850, Loss = 1.9391413, Perplexity = 6.952778 (16.829 sec)
I1112 19:05:44.378202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.594177
I1112 19:05:59.568203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5354116, Global Step = 3860, Loss = 1.8836248, Perplexity = 6.5773034 (15.191 sec)
I1112 19:05:59.568203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.658328
I1112 19:06:14.623202 10460 basic_session_run_hooks.py:260] Accuracy = 0.5100715, Global Step = 3870, Loss = 1.9684291, Perplexity = 7.1594205 (15.055 sec)
I1112 19:06:14.624204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664187
I1112 19:06:29.627203 10460 basic_session_run_hooks.py:260] Accuracy = 0.53071475, Global Step = 3880, Loss = 1.9483559, Perplexity = 7.0171413 (15.004 sec)
I1112 19:06:29.628203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666489
I1112 19:06:32.617202 10460 basic_session_run_hooks.py:606] Saving checkpoints for 3883 into logdir\run1\train\model.ckpt.
I1112 19:06:46.456203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5223536, Global Step = 3890, Loss = 1.8683307, Perplexity = 6.477475 (16.829 sec)
I1112 19:06:46.456203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.594248
I1112 19:07:01.528203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.642154
I1112 19:07:01.529204 10460 basic_session_run_hooks.py:260] Accuracy = 0.53234607, Global Step = 3900, Loss = 1.8042351, Perplexity = 6.0753226 (15.073 sec)
I1112 19:07:01.530204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663394
I1112 19:07:16.554203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5385374, Global Step = 3910, Loss = 1.8578439, Perplexity = 6.4099016 (15.025 sec)
I1112 19:07:16.555203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665557
I1112 19:07:31.627203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5397586, Global Step = 3920, Loss = 1.8438222, Perplexity = 6.320651 (15.073 sec)
I1112 19:07:31.627203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663482
I1112 19:07:33.147204 10460 basic_session_run_hooks.py:606] Saving checkpoints for 3922 into logdir\run1\train\model.ckpt.
I1112 19:07:48.432203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5148012, Global Step = 3930, Loss = 1.9729213, Perplexity = 7.191654 (16.805 sec)
I1112 19:07:48.432203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.595061
I1112 19:08:03.435204 10460 basic_session_run_hooks.py:260] Accuracy = 0.53272533, Global Step = 3940, Loss = 1.9514482, Perplexity = 7.0388737 (15.002 sec)
I1112 19:08:03.435204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666533
I1112 19:08:18.603203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5295194, Global Step = 3950, Loss = 1.9054794, Perplexity = 6.72263 (15.169 sec)
I1112 19:08:18.604202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.659239
I1112 19:08:33.630203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 3961 into logdir\run1\train\model.ckpt.
I1112 19:08:33.947228 10460 basic_session_run_hooks.py:260] Accuracy = 0.48730025, Global Step = 3960, Loss = 1.9973906, Perplexity = 7.3698006 (15.344 sec)
I1112 19:08:33.948252 10460 basic_session_run_hooks.py:692] global_step/sec: 0.651718
I1112 19:08:50.637203 10460 basic_session_run_hooks.py:260] Accuracy = 0.51586413, Global Step = 3970, Loss = 1.803044, Perplexity = 6.0680904 (16.690 sec)
I1112 19:08:50.637203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.599199
I1112 19:09:05.669203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5149332, Global Step = 3980, Loss = 1.9997853, Perplexity = 7.38747 (15.032 sec)
I1112 19:09:05.670203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665203
I1112 19:09:20.825203 10460 basic_session_run_hooks.py:260] Accuracy = 0.51166505, Global Step = 3990, Loss = 1.9013003, Perplexity = 6.694594 (15.156 sec)
I1112 19:09:20.826204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.659805
I1112 19:09:34.349203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4000 into logdir\run1\train\model.ckpt.
I1112 19:09:36.350203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.645903
I1112 19:09:36.352206 10460 basic_session_run_hooks.py:260] Accuracy = 0.5348552, Global Step = 4000, Loss = 1.8528056, Perplexity = 6.377688 (15.527 sec)
I1112 19:09:36.353205 10460 basic_session_run_hooks.py:692] global_step/sec: 0.644039
I1112 19:09:52.705203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5511829, Global Step = 4010, Loss = 1.7762719, Perplexity = 5.9077907 (16.353 sec)
I1112 19:09:52.706202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.611509
I1112 19:10:07.820202 10460 basic_session_run_hooks.py:260] Accuracy = 0.51846135, Global Step = 4020, Loss = 1.8722998, Perplexity = 6.5032353 (15.115 sec)
I1112 19:10:07.821203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661594
I1112 19:10:22.813203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5333681, Global Step = 4030, Loss = 1.7349095, Perplexity = 5.6684146 (14.993 sec)
I1112 19:10:22.814203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666978
I1112 19:10:34.936227 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4039 into logdir\run1\train\model.ckpt.
I1112 19:10:38.756203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5359842, Global Step = 4040, Loss = 1.8779365, Perplexity = 6.539995 (15.943 sec)
I1112 19:10:38.757203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.627235
I1112 19:10:54.906203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5144379, Global Step = 4050, Loss = 1.959051, Perplexity = 7.092593 (16.150 sec)
I1112 19:10:54.907204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.619195
I1112 19:11:09.964205 10460 basic_session_run_hooks.py:260] Accuracy = 0.55282354, Global Step = 4060, Loss = 1.7459527, Perplexity = 5.7313595 (15.058 sec)
I1112 19:11:09.965204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664143
I1112 19:11:25.016203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5399083, Global Step = 4070, Loss = 1.7974489, Perplexity = 6.0342336 (15.052 sec)
I1112 19:11:25.017203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664319
I1112 19:11:35.531203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4078 into logdir\run1\train\model.ckpt.
I1112 19:11:41.466204 10460 basic_session_run_hooks.py:260] Accuracy = 0.5384126, Global Step = 4080, Loss = 1.7260416, Perplexity = 5.6183696 (16.450 sec)
I1112 19:11:41.467204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.607903
I1112 19:11:56.950203 10460 basic_session_run_hooks.py:260] Accuracy = 0.537336, Global Step = 4090, Loss = 1.8369352, Perplexity = 6.27727 (15.484 sec)
I1112 19:11:56.950203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.64587
I1112 19:12:12.031202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.642339
I1112 19:12:12.032203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5415067, Global Step = 4100, Loss = 1.888726, Perplexity = 6.610941 (15.082 sec)
I1112 19:12:12.033203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662998
I1112 19:12:26.974203 10460 basic_session_run_hooks.py:260] Accuracy = 0.52418077, Global Step = 4110, Loss = 1.8764002, Perplexity = 6.529956 (14.942 sec)
I1112 19:12:26.975203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.669254
I1112 19:12:35.975203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4117 into logdir\run1\train\model.ckpt.
I1112 19:12:43.746203 10460 basic_session_run_hooks.py:260] Accuracy = 0.52530074, Global Step = 4120, Loss = 1.9343438, Perplexity = 6.919502 (16.772 sec)
I1112 19:12:43.748204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.596196
I1112 19:12:59.087203 10460 basic_session_run_hooks.py:260] Accuracy = 0.49742898, Global Step = 4130, Loss = 1.9008472, Perplexity = 6.691561 (15.341 sec)
I1112 19:12:59.088203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.651891
I1112 19:13:14.019203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5666295, Global Step = 4140, Loss = 1.7016662, Perplexity = 5.4830756 (14.932 sec)
I1112 19:13:14.019203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.669748
I1112 19:13:29.132203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5600619, Global Step = 4150, Loss = 1.7504807, Perplexity = 5.7573695 (15.113 sec)
I1112 19:13:29.133203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661638
I1112 19:13:36.630203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4156 into logdir\run1\train\model.ckpt.
I1112 19:13:46.253203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5603196, Global Step = 4160, Loss = 1.6519542, Perplexity = 5.2171655 (17.121 sec)
I1112 19:13:46.254203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.584112
I1112 19:14:01.359203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5123702, Global Step = 4170, Loss = 1.9459764, Perplexity = 7.0004635 (15.106 sec)
I1112 19:14:01.360203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661945
I1112 19:14:16.423203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5254811, Global Step = 4180, Loss = 1.8694855, Perplexity = 6.484959 (15.064 sec)
I1112 19:14:16.424203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663834
I1112 19:14:31.442203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5281892, Global Step = 4190, Loss = 1.8779533, Perplexity = 6.5401053 (15.019 sec)
I1112 19:14:31.442203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665868
I1112 19:14:37.511203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4195 into logdir\run1\train\model.ckpt.
I1112 19:14:48.410202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.639472
I1112 19:14:48.410202 10460 basic_session_run_hooks.py:260] Accuracy = 0.51330715, Global Step = 4200, Loss = 1.8833004, Perplexity = 6.57517 (16.968 sec)
I1112 19:14:48.411203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.58931
I1112 19:15:03.493204 10460 basic_session_run_hooks.py:260] Accuracy = 0.5174891, Global Step = 4210, Loss = 1.9613163, Perplexity = 7.108679 (15.083 sec)
I1112 19:15:03.494204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662998
I1112 19:15:18.566203 10460 basic_session_run_hooks.py:260] Accuracy = 0.52703846, Global Step = 4220, Loss = 1.8811613, Perplexity = 6.56112 (15.073 sec)
I1112 19:15:18.567203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663482
I1112 19:15:33.640203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5440222, Global Step = 4230, Loss = 1.7441454, Perplexity = 5.7210107 (15.073 sec)
I1112 19:15:33.640203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663394
I1112 19:15:38.171203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4234 into logdir\run1\train\model.ckpt.
I1112 19:15:50.505203 10460 basic_session_run_hooks.py:260] Accuracy = 0.53765875, Global Step = 4240, Loss = 1.8013772, Perplexity = 6.0579844 (16.866 sec)
I1112 19:15:50.505203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.592944
I1112 19:16:05.537203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5596417, Global Step = 4250, Loss = 1.7461344, Perplexity = 5.732401 (15.032 sec)
I1112 19:16:05.538204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665247
I1112 19:16:20.689203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5492302, Global Step = 4260, Loss = 1.7562553, Perplexity = 5.7907124 (15.152 sec)
I1112 19:16:20.689203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.659979
I1112 19:16:35.797203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5246819, Global Step = 4270, Loss = 2.0047543, Perplexity = 7.424269 (15.108 sec)
I1112 19:16:35.797203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661901
I1112 19:16:38.807204 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4273 into logdir\run1\train\model.ckpt.
I1112 19:16:52.759202 10460 basic_session_run_hooks.py:260] Accuracy = 0.54695255, Global Step = 4280, Loss = 1.8033488, Perplexity = 6.06994 (16.962 sec)
I1112 19:16:52.760203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.589518
I1112 19:17:07.849231 10460 basic_session_run_hooks.py:260] Accuracy = 0.5387232, Global Step = 4290, Loss = 1.8221709, Perplexity = 6.185271 (15.090 sec)
I1112 19:17:07.850203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662691
I1112 19:17:22.981203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.646952
I1112 19:17:22.981203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5243336, Global Step = 4300, Loss = 1.9134749, Perplexity = 6.776596 (15.132 sec)
I1112 19:17:22.982204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.660851
I1112 19:17:38.015203 10460 basic_session_run_hooks.py:260] Accuracy = 0.52443266, Global Step = 4310, Loss = 1.8911558, Perplexity = 6.627024 (15.034 sec)
I1112 19:17:38.016204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665159
I1112 19:17:39.537203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4312 into logdir\run1\train\model.ckpt.
I1112 19:17:54.880203 10460 basic_session_run_hooks.py:260] Accuracy = 0.50466317, Global Step = 4320, Loss = 1.9406441, Perplexity = 6.963235 (16.865 sec)
I1112 19:17:54.881203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.592944
I1112 19:18:09.826203 10460 basic_session_run_hooks.py:260] Accuracy = 0.51043624, Global Step = 4330, Loss = 1.9772241, Perplexity = 7.2226663 (14.946 sec)
I1112 19:18:09.827203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.669075
I1112 19:18:24.844204 10460 basic_session_run_hooks.py:260] Accuracy = 0.5065798, Global Step = 4340, Loss = 2.0313041, Perplexity = 7.6240225 (15.018 sec)
I1112 19:18:24.844204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665912
I1112 19:18:39.812203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4351 into logdir\run1\train\model.ckpt.
I1112 19:18:40.148227 10460 basic_session_run_hooks.py:260] Accuracy = 0.5245792, Global Step = 4350, Loss = 1.8671749, Perplexity = 6.4699917 (15.304 sec)
I1112 19:18:40.149228 10460 basic_session_run_hooks.py:692] global_step/sec: 0.65338
I1112 19:18:56.579202 10460 basic_session_run_hooks.py:260] Accuracy = 0.5171733, Global Step = 4360, Loss = 1.9343128, Perplexity = 6.9192877 (16.431 sec)
I1112 19:18:56.579202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.608644
I1112 19:19:11.735203 10460 basic_session_run_hooks.py:260] Accuracy = 0.55129784, Global Step = 4370, Loss = 1.832819, Perplexity = 6.2514844 (15.156 sec)
I1112 19:19:11.736203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.659761
I1112 19:19:26.752205 10460 basic_session_run_hooks.py:260] Accuracy = 0.52805597, Global Step = 4380, Loss = 1.8798834, Perplexity = 6.552741 (15.017 sec)
I1112 19:19:26.752205 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665956
I1112 19:19:40.299227 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4390 into logdir\run1\train\model.ckpt.
I1112 19:19:42.271203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5656002, Global Step = 4390, Loss = 1.6689291, Perplexity = 5.3064823 (15.519 sec)
I1112 19:19:42.272205 10460 basic_session_run_hooks.py:692] global_step/sec: 0.64433
I1112 19:19:58.689203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.642228
I1112 19:19:58.690204 10460 basic_session_run_hooks.py:260] Accuracy = 0.5454563, Global Step = 4400, Loss = 1.7562691, Perplexity = 5.790792 (16.419 sec)
I1112 19:19:58.691204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.609051
I1112 19:20:13.765202 10460 basic_session_run_hooks.py:260] Accuracy = 0.53613514, Global Step = 4410, Loss = 1.8708428, Perplexity = 6.4937673 (15.075 sec)
I1112 19:20:13.765202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663394
I1112 19:20:28.901203 10460 basic_session_run_hooks.py:260] Accuracy = 0.45164105, Global Step = 4420, Loss = 2.1658132, Perplexity = 8.721691 (15.136 sec)
I1112 19:20:28.902202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.660633
I1112 19:20:40.879203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4429 into logdir\run1\train\model.ckpt.
I1112 19:20:44.769203 10460 basic_session_run_hooks.py:260] Accuracy = 0.51686925, Global Step = 4430, Loss = 1.9186251, Perplexity = 6.811587 (15.868 sec)
I1112 19:20:44.769203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.630239
I1112 19:21:00.732203 10460 basic_session_run_hooks.py:260] Accuracy = 0.53160924, Global Step = 4440, Loss = 1.8771925, Perplexity = 6.535132 (15.963 sec)
I1112 19:21:00.732203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.626449
I1112 19:21:15.797202 10460 basic_session_run_hooks.py:260] Accuracy = 0.54275656, Global Step = 4450, Loss = 1.7135504, Perplexity = 5.5486264 (15.065 sec)
I1112 19:21:15.798203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663746
I1112 19:21:30.841203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5130307, Global Step = 4460, Loss = 1.9363129, Perplexity = 6.9331408 (15.044 sec)
I1112 19:21:30.841203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664761
I1112 19:21:41.417203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4468 into logdir\run1\train\model.ckpt.
I1112 19:21:47.063204 10460 basic_session_run_hooks.py:260] Accuracy = 0.5330262, Global Step = 4470, Loss = 1.8197591, Perplexity = 6.170372 (16.222 sec)
I1112 19:21:47.064203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.616409
I1112 19:22:02.654203 10460 basic_session_run_hooks.py:260] Accuracy = 0.511071, Global Step = 4480, Loss = 1.964093, Perplexity = 7.128444 (15.591 sec)
I1112 19:22:02.655203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.641396
I1112 19:22:17.687203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5288725, Global Step = 4490, Loss = 1.821848, Perplexity = 6.1832747 (15.033 sec)
I1112 19:22:17.688203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665203
I1112 19:22:32.724203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.649203
I1112 19:22:32.725203 10460 basic_session_run_hooks.py:260] Accuracy = 0.529375, Global Step = 4500, Loss = 1.8113527, Perplexity = 6.1187186 (15.038 sec)
I1112 19:22:32.726203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664982
I1112 19:22:41.744203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4507 into logdir\run1\train\model.ckpt.
I1112 19:22:49.248204 10460 basic_session_run_hooks.py:260] Accuracy = 0.51703376, Global Step = 4510, Loss = 1.865587, Perplexity = 6.4597263 (16.523 sec)
I1112 19:22:49.250203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.605217
I1112 19:23:04.597203 10460 basic_session_run_hooks.py:260] Accuracy = 0.51081556, Global Step = 4520, Loss = 1.8822701, Perplexity = 6.568399 (15.349 sec)
I1112 19:23:04.597203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.651551
I1112 19:23:19.547203 10460 basic_session_run_hooks.py:260] Accuracy = 0.56830525, Global Step = 4530, Loss = 1.6318903, Perplexity = 5.1135316 (14.950 sec)
I1112 19:23:19.548203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.668852
I1112 19:23:34.616203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5176591, Global Step = 4540, Loss = 1.867448, Perplexity = 6.471759 (15.069 sec)
I1112 19:23:34.617203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663658
I1112 19:23:42.194203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4546 into logdir\run1\train\model.ckpt.
I1112 19:23:51.473202 10460 basic_session_run_hooks.py:260] Accuracy = 0.5572723, Global Step = 4550, Loss = 1.7807754, Perplexity = 5.9344563 (16.857 sec)
I1112 19:23:51.474203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.59319
I1112 19:24:06.550203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5206871, Global Step = 4560, Loss = 1.843262, Perplexity = 6.3171105 (15.077 sec)
I1112 19:24:06.551204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663262
I1112 19:24:21.691203 10460 basic_session_run_hooks.py:260] Accuracy = 0.52493876, Global Step = 4570, Loss = 1.8771037, Perplexity = 6.534551 (15.141 sec)
I1112 19:24:21.692203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.660458
I1112 19:24:36.887202 10460 basic_session_run_hooks.py:260] Accuracy = 0.53057754, Global Step = 4580, Loss = 1.7689643, Perplexity = 5.864776 (15.196 sec)
I1112 19:24:36.888203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.658068
I1112 19:24:42.897203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4585 into logdir\run1\train\model.ckpt.
I1112 19:24:53.752203 10460 basic_session_run_hooks.py:260] Accuracy = 0.50986576, Global Step = 4590, Loss = 1.896877, Perplexity = 6.665047 (16.865 sec)
I1112 19:24:53.752203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.592979
I1112 19:25:08.766203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.640853
I1112 19:25:08.766203 10460 basic_session_run_hooks.py:260] Accuracy = 0.56426847, Global Step = 4600, Loss = 1.6616615, Perplexity = 5.268057 (15.014 sec)
I1112 19:25:08.767204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666001
I1112 19:25:23.824203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5342188, Global Step = 4610, Loss = 1.8456959, Perplexity = 6.3325047 (15.058 sec)
I1112 19:25:23.825203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664099
I1112 19:25:38.834203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5324405, Global Step = 4620, Loss = 1.8442572, Perplexity = 6.323401 (15.010 sec)
I1112 19:25:38.835203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666223
I1112 19:25:43.355203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4624 into logdir\run1\train\model.ckpt.
I1112 19:25:55.644202 10460 basic_session_run_hooks.py:260] Accuracy = 0.5456935, Global Step = 4630, Loss = 1.7833412, Perplexity = 5.9497023 (16.810 sec)
I1112 19:25:55.645203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.594884
I1112 19:26:10.633203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5389726, Global Step = 4640, Loss = 1.8032924, Perplexity = 6.069598 (14.989 sec)
I1112 19:26:10.634204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.667156
I1112 19:26:25.761203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5420633, Global Step = 4650, Loss = 1.8527733, Perplexity = 6.377482 (15.128 sec)
I1112 19:26:25.761203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.66107
I1112 19:26:40.872203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5462304, Global Step = 4660, Loss = 1.7678369, Perplexity = 5.8581676 (15.111 sec)
I1112 19:26:40.873203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661726
I1112 19:26:43.864203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4663 into logdir\run1\train\model.ckpt.
I1112 19:26:57.625203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5284278, Global Step = 4670, Loss = 1.938026, Perplexity = 6.9450274 (16.753 sec)
I1112 19:26:57.626203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.596908
I1112 19:27:12.712204 10460 basic_session_run_hooks.py:260] Accuracy = 0.50894845, Global Step = 4680, Loss = 1.866475, Perplexity = 6.465465 (15.087 sec)
I1112 19:27:12.713202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662822
I1112 19:27:27.761203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5550829, Global Step = 4690, Loss = 1.8669705, Perplexity = 6.46867 (15.049 sec)
I1112 19:27:27.762203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664496
I1112 19:27:42.893203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.648816
I1112 19:27:42.894204 10460 basic_session_run_hooks.py:260] Accuracy = 0.59011364, Global Step = 4700, Loss = 1.5431329, Perplexity = 4.6792264 (15.133 sec)
I1112 19:27:42.895204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.660851
I1112 19:27:44.384203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4702 into logdir\run1\train\model.ckpt.
I1112 19:27:59.694202 10460 basic_session_run_hooks.py:260] Accuracy = 0.52621734, Global Step = 4710, Loss = 1.8700429, Perplexity = 6.488575 (16.800 sec)
I1112 19:27:59.695203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.595203
I1112 19:28:14.863203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5423117, Global Step = 4720, Loss = 1.7554862, Perplexity = 5.7862606 (15.169 sec)
I1112 19:28:14.863203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.659283
I1112 19:28:29.844203 10460 basic_session_run_hooks.py:260] Accuracy = 0.51500505, Global Step = 4730, Loss = 1.865528, Perplexity = 6.4593453 (14.981 sec)
I1112 19:28:29.845204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.667468
I1112 19:28:44.976212 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4741 into logdir\run1\train\model.ckpt.
I1112 19:28:45.306227 10460 basic_session_run_hooks.py:260] Accuracy = 0.5408388, Global Step = 4740, Loss = 1.8798221, Perplexity = 6.552339 (15.462 sec)
I1112 19:28:45.307227 10460 basic_session_run_hooks.py:692] global_step/sec: 0.646746
I1112 19:29:01.820203 10460 basic_session_run_hooks.py:260] Accuracy = 0.52694744, Global Step = 4750, Loss = 1.8717822, Perplexity = 6.4998703 (16.514 sec)
I1112 19:29:01.821203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.605548
I1112 19:29:16.816203 10460 basic_session_run_hooks.py:260] Accuracy = 0.525431, Global Step = 4760, Loss = 1.8168633, Perplexity = 6.1525292 (14.996 sec)
I1112 19:29:16.817204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666844
I1112 19:29:31.829204 10460 basic_session_run_hooks.py:260] Accuracy = 0.52467, Global Step = 4770, Loss = 1.9513826, Perplexity = 7.0384126 (15.013 sec)
I1112 19:29:31.830203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666089
I1112 19:29:45.437203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4780 into logdir\run1\train\model.ckpt.
I1112 19:29:47.465204 10460 basic_session_run_hooks.py:260] Accuracy = 0.54883444, Global Step = 4780, Loss = 1.7361293, Perplexity = 5.675333 (15.636 sec)
I1112 19:29:47.466206 10460 basic_session_run_hooks.py:692] global_step/sec: 0.63955
I1112 19:30:03.894203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5364363, Global Step = 4790, Loss = 1.7921779, Perplexity = 6.002511 (16.429 sec)
I1112 19:30:03.894203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.608717
I1112 19:30:18.928203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.640882
I1112 19:30:18.929204 10460 basic_session_run_hooks.py:260] Accuracy = 0.51662356, Global Step = 4800, Loss = 1.947576, Perplexity = 7.0116715 (15.035 sec)
I1112 19:30:18.930204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.66507
I1112 19:30:33.912203 10460 basic_session_run_hooks.py:260] Accuracy = 0.52806157, Global Step = 4810, Loss = 1.8207724, Perplexity = 6.176627 (14.983 sec)
I1112 19:30:33.913202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.667423
I1112 19:30:45.880202 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4819 into logdir\run1\train\model.ckpt.
I1112 19:30:49.650203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5243673, Global Step = 4820, Loss = 1.7476175, Perplexity = 5.7409086 (15.738 sec)
I1112 19:30:49.652205 10460 basic_session_run_hooks.py:692] global_step/sec: 0.635364
I1112 19:31:05.692203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5581959, Global Step = 4830, Loss = 1.7152039, Perplexity = 5.557808 (16.042 sec)
I1112 19:31:05.693204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.623403
I1112 19:31:20.762203 10460 basic_session_run_hooks.py:260] Accuracy = 0.50416476, Global Step = 4840, Loss = 1.9515283, Perplexity = 7.039438 (15.070 sec)
I1112 19:31:20.763204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663614
I1112 19:31:35.896203 10460 basic_session_run_hooks.py:260] Accuracy = 0.54757476, Global Step = 4850, Loss = 1.7797621, Perplexity = 5.9284463 (15.134 sec)
I1112 19:31:35.896203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.660764
I1112 19:31:46.427203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4858 into logdir\run1\train\model.ckpt.
I1112 19:31:52.107204 10460 basic_session_run_hooks.py:260] Accuracy = 0.5427407, Global Step = 4860, Loss = 1.7679862, Perplexity = 5.8590426 (16.211 sec)
I1112 19:31:52.108203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.616827
I1112 19:32:07.773203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5403985, Global Step = 4870, Loss = 1.8155432, Perplexity = 6.144413 (15.665 sec)
I1112 19:32:07.773203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.638366
I1112 19:32:22.850203 10460 basic_session_run_hooks.py:260] Accuracy = 0.52207816, Global Step = 4880, Loss = 1.8225641, Perplexity = 6.187704 (15.078 sec)
I1112 19:32:22.851203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663218
I1112 19:32:37.927203 10460 basic_session_run_hooks.py:260] Accuracy = 0.52507395, Global Step = 4890, Loss = 1.8271083, Perplexity = 6.215886 (15.077 sec)
I1112 19:32:37.928203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663262
I1112 19:32:46.938203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4897 into logdir\run1\train\model.ckpt.
I1112 19:32:54.353204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.643397
I1112 19:32:54.354204 10460 basic_session_run_hooks.py:260] Accuracy = 0.5328294, Global Step = 4900, Loss = 1.8960506, Perplexity = 6.659541 (16.427 sec)
I1112 19:32:54.356203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.608717
I1112 19:33:09.749203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5269675, Global Step = 4910, Loss = 1.8753732, Perplexity = 6.5232534 (15.395 sec)
I1112 19:33:09.750202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.649604
I1112 19:33:24.876203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5558803, Global Step = 4920, Loss = 1.8280294, Perplexity = 6.2216144 (15.127 sec)
I1112 19:33:24.877203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.66107
I1112 19:33:39.968203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5834221, Global Step = 4930, Loss = 1.6312424, Perplexity = 5.1102195 (15.092 sec)
I1112 19:33:39.969203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662603
I1112 19:33:47.663204 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4936 into logdir\run1\train\model.ckpt.
I1112 19:33:57.148203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5439113, Global Step = 4940, Loss = 1.7650998, Perplexity = 5.8421555 (17.180 sec)
I1112 19:33:57.148203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.582106
I1112 19:34:12.404202 10460 basic_session_run_hooks.py:260] Accuracy = 0.5220895, Global Step = 4950, Loss = 1.8369005, Perplexity = 6.277052 (15.256 sec)
I1112 19:34:12.405203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.655437
I1112 19:34:27.514203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5407994, Global Step = 4960, Loss = 1.7705593, Perplexity = 5.874138 (15.110 sec)
I1112 19:34:27.515202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661813
I1112 19:34:42.784203 10460 basic_session_run_hooks.py:260] Accuracy = 0.52502865, Global Step = 4970, Loss = 1.7782332, Perplexity = 5.919389 (15.270 sec)
I1112 19:34:42.784203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.654922
I1112 19:34:48.819203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 4975 into logdir\run1\train\model.ckpt.
I1112 19:34:59.736203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5621376, Global Step = 4980, Loss = 1.7416953, Perplexity = 5.7070103 (16.952 sec)
I1112 19:34:59.736203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.589901
I1112 19:35:14.800203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5740232, Global Step = 4990, Loss = 1.7154785, Perplexity = 5.5593348 (15.064 sec)
I1112 19:35:14.801203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.66379
I1112 19:35:29.783203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.643376
I1112 19:35:29.784203 10460 basic_session_run_hooks.py:260] Accuracy = 0.54560643, Global Step = 5000, Loss = 1.867417, Perplexity = 6.4715586 (14.984 sec)
I1112 19:35:29.784203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.667423
I1112 19:35:44.749203 10460 basic_session_run_hooks.py:260] Accuracy = 0.51659733, Global Step = 5010, Loss = 1.8813121, Perplexity = 6.5621095 (14.965 sec)
I1112 19:35:44.750203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.668181
I1112 19:35:49.336203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5014 into logdir\run1\train\model.ckpt.
I1112 19:36:02.106203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5633591, Global Step = 5020, Loss = 1.6984845, Perplexity = 5.4656577 (17.357 sec)
I1112 19:36:02.106203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.57617
I1112 19:36:17.269204 10460 basic_session_run_hooks.py:260] Accuracy = 0.52604175, Global Step = 5030, Loss = 1.850832, Perplexity = 6.365113 (15.163 sec)
I1112 19:36:17.270203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.659457
I1112 19:36:32.582203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5277841, Global Step = 5040, Loss = 1.846253, Perplexity = 6.3360343 (15.313 sec)
I1112 19:36:32.583203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.65304
I1112 19:36:47.756203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5196196, Global Step = 5050, Loss = 1.8633773, Perplexity = 6.4454684 (15.174 sec)
I1112 19:36:47.756203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.659065
I1112 19:36:50.789202 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5053 into logdir\run1\train\model.ckpt.
I1112 19:37:04.742202 10460 basic_session_run_hooks.py:260] Accuracy = 0.5383192, Global Step = 5060, Loss = 1.8346735, Perplexity = 6.2630887 (16.986 sec)
I1112 19:37:04.742202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.58872
I1112 19:37:19.883203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5359581, Global Step = 5070, Loss = 1.7466946, Perplexity = 5.735613 (15.141 sec)
I1112 19:37:19.883203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.660458
I1112 19:37:35.002204 10460 basic_session_run_hooks.py:260] Accuracy = 0.5580132, Global Step = 5080, Loss = 1.7140504, Perplexity = 5.551401 (15.119 sec)
I1112 19:37:35.003204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661376
I1112 19:37:50.191202 10460 basic_session_run_hooks.py:260] Accuracy = 0.5589882, Global Step = 5090, Loss = 1.7193884, Perplexity = 5.581114 (15.189 sec)
I1112 19:37:50.192203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.658371
I1112 19:37:51.715203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5092 into logdir\run1\train\model.ckpt.
I1112 19:38:07.121202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.635574
I1112 19:38:07.122203 10460 basic_session_run_hooks.py:260] Accuracy = 0.54049003, Global Step = 5100, Loss = 1.7806219, Perplexity = 5.933545 (16.931 sec)
I1112 19:38:07.122203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.590667
I1112 19:38:22.238203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5416285, Global Step = 5110, Loss = 1.769674, Perplexity = 5.8689394 (15.116 sec)
I1112 19:38:22.238203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661551
I1112 19:38:37.416203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5552126, Global Step = 5120, Loss = 1.7694616, Perplexity = 5.867694 (15.178 sec)
I1112 19:38:37.417203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.658805
I1112 19:38:52.500203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5131 into logdir\run1\train\model.ckpt.
I1112 19:38:52.823233 10460 basic_session_run_hooks.py:260] Accuracy = 0.54515475, Global Step = 5130, Loss = 1.7973609, Perplexity = 6.033703 (15.407 sec)
I1112 19:38:52.824232 10460 basic_session_run_hooks.py:692] global_step/sec: 0.649054
I1112 19:39:09.486203 10460 basic_session_run_hooks.py:260] Accuracy = 0.53663325, Global Step = 5140, Loss = 1.7757547, Perplexity = 5.904736 (16.663 sec)
I1112 19:39:09.487203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.600133
I1112 19:39:24.574203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5665921, Global Step = 5150, Loss = 1.6616678, Perplexity = 5.26809 (15.088 sec)
I1112 19:39:24.574203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662822
I1112 19:39:39.693203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5527032, Global Step = 5160, Loss = 1.7806319, Perplexity = 5.9336047 (15.119 sec)
I1112 19:39:39.694203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661376
I1112 19:39:53.338203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5170 into logdir\run1\train\model.ckpt.
I1112 19:39:55.380207 10460 basic_session_run_hooks.py:260] Accuracy = 0.5749191, Global Step = 5170, Loss = 1.688153, Perplexity = 5.40948 (15.687 sec)
I1112 19:39:55.382204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.63747
I1112 19:40:12.089203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5535986, Global Step = 5180, Loss = 1.6733133, Perplexity = 5.3297977 (16.709 sec)
I1112 19:40:12.090203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.598516
I1112 19:40:27.203203 10460 basic_session_run_hooks.py:260] Accuracy = 0.53906083, Global Step = 5190, Loss = 1.8005209, Perplexity = 6.052799 (15.114 sec)
I1112 19:40:27.203203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661638
I1112 19:40:42.302203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.644409
I1112 19:40:42.303204 10460 basic_session_run_hooks.py:260] Accuracy = 0.56418616, Global Step = 5200, Loss = 1.6775056, Perplexity = 5.3521886 (15.100 sec)
I1112 19:40:42.304205 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662208
I1112 19:40:54.344203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5209 into logdir\run1\train\model.ckpt.
I1112 19:40:58.372204 10460 basic_session_run_hooks.py:260] Accuracy = 0.5525532, Global Step = 5210, Loss = 1.7619452, Perplexity = 5.8237553 (16.069 sec)
I1112 19:40:58.374205 10460 basic_session_run_hooks.py:692] global_step/sec: 0.622278
I1112 19:41:14.583203 10460 basic_session_run_hooks.py:260] Accuracy = 0.56416345, Global Step = 5220, Loss = 1.6978955, Perplexity = 5.4624395 (16.211 sec)
I1112 19:41:14.584204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.616903
I1112 19:41:29.771203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5368534, Global Step = 5230, Loss = 1.8371066, Perplexity = 6.278346 (15.187 sec)
I1112 19:41:29.771203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.658458
I1112 19:41:44.853203 10460 basic_session_run_hooks.py:260] Accuracy = 0.53990734, Global Step = 5240, Loss = 1.7967193, Perplexity = 6.0298333 (15.083 sec)
I1112 19:41:44.854203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662998
I1112 19:41:55.317203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5248 into logdir\run1\train\model.ckpt.
I1112 19:42:00.892206 10460 basic_session_run_hooks.py:260] Accuracy = 0.5671693, Global Step = 5250, Loss = 1.6957222, Perplexity = 5.450581 (16.039 sec)
I1112 19:42:00.893204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.62348
I1112 19:42:16.678204 10460 basic_session_run_hooks.py:260] Accuracy = 0.5514809, Global Step = 5260, Loss = 1.698791, Perplexity = 5.467334 (15.785 sec)
I1112 19:42:16.678204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.633513
I1112 19:42:31.703203 10460 basic_session_run_hooks.py:260] Accuracy = 0.54820174, Global Step = 5270, Loss = 1.709669, Perplexity = 5.5271316 (15.026 sec)
I1112 19:42:31.703203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665557
I1112 19:42:46.771203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5463271, Global Step = 5280, Loss = 1.6833143, Perplexity = 5.3833685 (15.068 sec)
I1112 19:42:46.772203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663614
I1112 19:42:55.815203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5287 into logdir\run1\train\model.ckpt.
I1112 19:43:03.413203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5660065, Global Step = 5290, Loss = 1.6365952, Perplexity = 5.137647 (16.641 sec)
I1112 19:43:03.413203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.600925
I1112 19:43:18.602203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.639795
I1112 19:43:18.603203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5547211, Global Step = 5300, Loss = 1.7270162, Perplexity = 5.6238484 (15.191 sec)
I1112 19:43:18.603203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.658328
I1112 19:43:33.648205 10460 basic_session_run_hooks.py:260] Accuracy = 0.5452145, Global Step = 5310, Loss = 1.7994134, Perplexity = 6.0461 (15.045 sec)
I1112 19:43:33.648205 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664673
I1112 19:43:48.733203 10460 basic_session_run_hooks.py:260] Accuracy = 0.56051844, Global Step = 5320, Loss = 1.6763102, Perplexity = 5.3457947 (15.085 sec)
I1112 19:43:48.734203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662866
I1112 19:43:56.341203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5326 into logdir\run1\train\model.ckpt.
I1112 19:44:05.628202 10460 basic_session_run_hooks.py:260] Accuracy = 0.53138214, Global Step = 5330, Loss = 1.7743775, Perplexity = 5.8966093 (16.895 sec)
I1112 19:44:05.629203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.591891
I1112 19:44:20.639202 10460 basic_session_run_hooks.py:260] Accuracy = 0.528135, Global Step = 5340, Loss = 1.8780183, Perplexity = 6.54053 (15.011 sec)
I1112 19:44:20.640203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666178
I1112 19:44:35.663203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5411491, Global Step = 5350, Loss = 1.7196643, Perplexity = 5.582654 (15.024 sec)
I1112 19:44:35.664203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665646
I1112 19:44:50.684203 10460 basic_session_run_hooks.py:260] Accuracy = 0.56925994, Global Step = 5360, Loss = 1.7008145, Perplexity = 5.4784074 (15.021 sec)
I1112 19:44:50.685203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.66569
I1112 19:44:56.709203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5365 into logdir\run1\train\model.ckpt.
I1112 19:45:07.453203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5512724, Global Step = 5370, Loss = 1.6967963, Perplexity = 5.4564385 (16.769 sec)
I1112 19:45:07.454204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.596374
I1112 19:45:22.509203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5409219, Global Step = 5380, Loss = 1.7579526, Perplexity = 5.800549 (15.056 sec)
I1112 19:45:22.510203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664143
I1112 19:45:37.522203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5551907, Global Step = 5390, Loss = 1.6699294, Perplexity = 5.3117924 (15.013 sec)
I1112 19:45:37.523203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666134
I1112 19:45:52.683203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.649009
I1112 19:45:52.683203 10460 basic_session_run_hooks.py:260] Accuracy = 0.56022036, Global Step = 5400, Loss = 1.7417278, Perplexity = 5.707196 (15.161 sec)
I1112 19:45:52.684203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.659544
I1112 19:45:57.192203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5404 into logdir\run1\train\model.ckpt.
I1112 19:46:09.466203 10460 basic_session_run_hooks.py:260] Accuracy = 0.52822566, Global Step = 5410, Loss = 1.7843925, Perplexity = 5.9559608 (16.783 sec)
I1112 19:46:09.467204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.595841
I1112 19:46:24.566204 10460 basic_session_run_hooks.py:260] Accuracy = 0.56427443, Global Step = 5420, Loss = 1.6846242, Perplexity = 5.390425 (15.100 sec)
I1112 19:46:24.566204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662296
I1112 19:46:39.625203 10460 basic_session_run_hooks.py:260] Accuracy = 0.55282867, Global Step = 5430, Loss = 1.7470866, Perplexity = 5.737862 (15.059 sec)
I1112 19:46:39.626203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664011
I1112 19:46:54.798203 10460 basic_session_run_hooks.py:260] Accuracy = 0.56658727, Global Step = 5440, Loss = 1.6371757, Perplexity = 5.1406302 (15.173 sec)
I1112 19:46:54.798203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.659109
I1112 19:46:57.786203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5443 into logdir\run1\train\model.ckpt.
I1112 19:47:11.549203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5499439, Global Step = 5450, Loss = 1.8072169, Perplexity = 6.0934653 (16.751 sec)
I1112 19:47:11.550203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.596944
I1112 19:47:26.608203 10460 basic_session_run_hooks.py:260] Accuracy = 0.56466794, Global Step = 5460, Loss = 1.6307696, Perplexity = 5.1078043 (15.059 sec)
I1112 19:47:26.608203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664099
I1112 19:47:41.794203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5462942, Global Step = 5470, Loss = 1.6923686, Perplexity = 5.4323325 (15.186 sec)
I1112 19:47:41.794203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.658501
I1112 19:47:56.949203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5552926, Global Step = 5480, Loss = 1.7021531, Perplexity = 5.485746 (15.155 sec)
I1112 19:47:56.949203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.659848
I1112 19:47:58.433203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5482 into logdir\run1\train\model.ckpt.
I1112 19:48:13.762202 10460 basic_session_run_hooks.py:260] Accuracy = 0.53362185, Global Step = 5490, Loss = 1.850809, Perplexity = 6.3649664 (16.813 sec)
I1112 19:48:13.763203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.594742
I1112 19:48:28.827203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.640434
I1112 19:48:28.828203 10460 basic_session_run_hooks.py:260] Accuracy = 0.53196627, Global Step = 5500, Loss = 1.7930546, Perplexity = 6.0077753 (15.066 sec)
I1112 19:48:28.829204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663746
I1112 19:48:43.921203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5291258, Global Step = 5510, Loss = 1.8206046, Perplexity = 6.175591 (15.093 sec)
I1112 19:48:43.922205 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662559
I1112 19:48:58.983203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5521 into logdir\run1\train\model.ckpt.
I1112 19:48:59.307232 10460 basic_session_run_hooks.py:260] Accuracy = 0.56275845, Global Step = 5520, Loss = 1.6945156, Perplexity = 5.444008 (15.386 sec)
I1112 19:48:59.308202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.649942
I1112 19:49:15.993203 10460 basic_session_run_hooks.py:260] Accuracy = 0.55276495, Global Step = 5530, Loss = 1.6977513, Perplexity = 5.461652 (16.686 sec)
I1112 19:49:15.994203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.599305
I1112 19:49:31.078203 10460 basic_session_run_hooks.py:260] Accuracy = 0.56855184, Global Step = 5540, Loss = 1.6433755, Perplexity = 5.1726003 (15.085 sec)
I1112 19:49:31.079202 10460 basic_session_run_hooks.py:692] global_step/sec: 0.66291
I1112 19:49:46.184203 10460 basic_session_run_hooks.py:260] Accuracy = 0.552472, Global Step = 5550, Loss = 1.7186806, Perplexity = 5.577165 (15.105 sec)
I1112 19:49:46.184203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662032
I1112 19:49:59.754203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5560 into logdir\run1\train\model.ckpt.
I1112 19:50:01.824204 10460 basic_session_run_hooks.py:260] Accuracy = 0.5620806, Global Step = 5560, Loss = 1.6865898, Perplexity = 5.401031 (15.641 sec)
I1112 19:50:01.825209 10460 basic_session_run_hooks.py:692] global_step/sec: 0.639345
I1112 19:50:18.074203 10460 basic_session_run_hooks.py:260] Accuracy = 0.519045, Global Step = 5570, Loss = 1.9111216, Perplexity = 6.7606673 (16.250 sec)
I1112 19:50:18.074203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.615423
I1112 19:50:33.076204 10460 basic_session_run_hooks.py:260] Accuracy = 0.54995847, Global Step = 5580, Loss = 1.7365403, Perplexity = 5.677666 (15.002 sec)
I1112 19:50:33.077203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.666533
I1112 19:50:48.219202 10460 basic_session_run_hooks.py:260] Accuracy = 0.52115655, Global Step = 5590, Loss = 1.8181481, Perplexity = 6.1604395 (15.143 sec)
I1112 19:50:48.220203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.660371
I1112 19:51:00.271203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5599 into logdir\run1\train\model.ckpt.
I1112 19:51:04.061203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.644189
I1112 19:51:04.062203 10460 basic_session_run_hooks.py:260] Accuracy = 0.56070346, Global Step = 5600, Loss = 1.6722465, Perplexity = 5.324115 (15.843 sec)
I1112 19:51:04.062203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.631233
I1112 19:51:20.023203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5363942, Global Step = 5610, Loss = 1.7400162, Perplexity = 5.697436 (15.961 sec)
I1112 19:51:20.023203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.626527
I1112 19:51:35.050203 10460 basic_session_run_hooks.py:260] Accuracy = 0.56231993, Global Step = 5620, Loss = 1.7201941, Perplexity = 5.5856123 (15.027 sec)
I1112 19:51:35.050203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665469
I1112 19:51:50.139203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5430044, Global Step = 5630, Loss = 1.7173624, Perplexity = 5.569818 (15.089 sec)
I1112 19:51:50.139203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662734
I1112 19:52:00.785203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5638 into logdir\run1\train\model.ckpt.
I1112 19:52:06.516203 10460 basic_session_run_hooks.py:260] Accuracy = 0.51556563, Global Step = 5640, Loss = 1.8215102, Perplexity = 6.181186 (16.377 sec)
I1112 19:52:06.516203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.610612
I1112 19:52:22.071205 10460 basic_session_run_hooks.py:260] Accuracy = 0.5080654, Global Step = 5650, Loss = 1.9452008, Perplexity = 6.9950366 (15.555 sec)
I1112 19:52:22.072203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.642839
I1112 19:52:37.178203 10460 basic_session_run_hooks.py:260] Accuracy = 0.47956297, Global Step = 5660, Loss = 2.0347245, Perplexity = 7.650144 (15.107 sec)
I1112 19:52:37.179203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661945
I1112 19:52:52.221203 10460 basic_session_run_hooks.py:260] Accuracy = 0.49635786, Global Step = 5670, Loss = 1.9239457, Perplexity = 6.8479247 (15.043 sec)
I1112 19:52:52.221203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664805
I1112 19:53:01.180203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5677 into logdir\run1\train\model.ckpt.
I1112 19:53:08.652204 10460 basic_session_run_hooks.py:260] Accuracy = 0.52598333, Global Step = 5680, Loss = 1.9023297, Perplexity = 6.7014885 (16.431 sec)
I1112 19:53:08.653204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.608569
I1112 19:53:24.047203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5137245, Global Step = 5690, Loss = 2.0178595, Perplexity = 7.5222063 (15.395 sec)
I1112 19:53:24.048203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.649562
I1112 19:53:39.186203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.644641
I1112 19:53:39.187204 10460 basic_session_run_hooks.py:260] Accuracy = 0.51591754, Global Step = 5700, Loss = 2.0274034, Perplexity = 7.594341 (15.140 sec)
I1112 19:53:39.187204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.660546
I1112 19:53:54.250204 10460 basic_session_run_hooks.py:260] Accuracy = 0.5353369, Global Step = 5710, Loss = 1.855905, Perplexity = 6.3974857 (15.063 sec)
I1112 19:53:54.251204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663834
I1112 19:54:01.734202 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5716 into logdir\run1\train\model.ckpt.
I1112 19:54:10.962204 10460 basic_session_run_hooks.py:260] Accuracy = 0.5130634, Global Step = 5720, Loss = 1.9193454, Perplexity = 6.8164945 (16.712 sec)
I1112 19:54:10.963203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.598372
I1112 19:54:26.127203 10460 basic_session_run_hooks.py:260] Accuracy = 0.52243465, Global Step = 5730, Loss = 1.9238403, Perplexity = 6.8472033 (15.165 sec)
I1112 19:54:26.128203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.659413
I1112 19:54:41.172203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5044032, Global Step = 5740, Loss = 1.944279, Perplexity = 6.988591 (15.045 sec)
I1112 19:54:41.173203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664673
I1112 19:54:56.222203 10460 basic_session_run_hooks.py:260] Accuracy = 0.57595354, Global Step = 5750, Loss = 1.629936, Perplexity = 5.103548 (15.050 sec)
I1112 19:54:56.223204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664452
I1112 19:55:02.293203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5755 into logdir\run1\train\model.ckpt.
I1112 19:55:13.028202 10460 basic_session_run_hooks.py:260] Accuracy = 0.5456667, Global Step = 5760, Loss = 1.8420553, Perplexity = 6.309493 (16.806 sec)
I1112 19:55:13.029203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.595026
I1112 19:55:28.141203 10460 basic_session_run_hooks.py:260] Accuracy = 0.51838815, Global Step = 5770, Loss = 1.8809559, Perplexity = 6.5597725 (15.113 sec)
I1112 19:55:28.142203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.661682
I1112 19:55:43.203203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5357904, Global Step = 5780, Loss = 1.8324548, Perplexity = 6.2492085 (15.062 sec)
I1112 19:55:43.204203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663922
I1112 19:55:58.268203 10460 basic_session_run_hooks.py:260] Accuracy = 0.484771, Global Step = 5790, Loss = 2.1035745, Perplexity = 8.195413 (15.065 sec)
I1112 19:55:58.268203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663834
I1112 19:56:02.746203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5794 into logdir\run1\train\model.ckpt.
I1112 19:56:15.049203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.641589
I1112 19:56:15.049203 10460 basic_session_run_hooks.py:260] Accuracy = 0.47671315, Global Step = 5800, Loss = 2.083247, Perplexity = 8.030501 (16.781 sec)
I1112 19:56:15.050203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.595877
I1112 19:56:30.094203 10460 basic_session_run_hooks.py:260] Accuracy = 0.5109966, Global Step = 5810, Loss = 2.020149, Perplexity = 7.5394483 (15.045 sec)
I1112 19:56:30.095203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664673
I1112 19:56:45.154202 10460 basic_session_run_hooks.py:260] Accuracy = 0.49885997, Global Step = 5820, Loss = 1.9885409, Perplexity = 7.3048673 (15.060 sec)
I1112 19:56:45.155203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664011
I1112 19:57:00.211203 10460 basic_session_run_hooks.py:260] Accuracy = 0.49860883, Global Step = 5830, Loss = 1.9194065, Perplexity = 6.816911 (15.057 sec)
I1112 19:57:00.212203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664143
I1112 19:57:03.232204 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5833 into logdir\run1\train\model.ckpt.
I1112 19:57:17.197204 10460 basic_session_run_hooks.py:260] Accuracy = 0.5111136, Global Step = 5840, Loss = 1.9882543, Perplexity = 7.3027744 (16.986 sec)
I1112 19:57:17.197204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.588755
I1112 19:57:32.229244 10460 basic_session_run_hooks.py:260] Accuracy = 0.4960392, Global Step = 5850, Loss = 1.9959706, Perplexity = 7.359342 (15.032 sec)
I1112 19:57:32.230205 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665203
I1112 19:57:47.298202 10460 basic_session_run_hooks.py:260] Accuracy = 0.48474997, Global Step = 5860, Loss = 2.077321, Perplexity = 7.983054 (15.069 sec)
I1112 19:57:47.299203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663614
I1112 19:58:02.356203 10460 basic_session_run_hooks.py:260] Accuracy = 0.49055335, Global Step = 5870, Loss = 1.990001, Perplexity = 7.3155413 (15.058 sec)
I1112 19:58:02.356203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664143
I1112 19:58:03.848203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5872 into logdir\run1\train\model.ckpt.
I1112 19:58:19.184203 10460 basic_session_run_hooks.py:260] Accuracy = 0.49211496, Global Step = 5880, Loss = 2.1377447, Perplexity = 8.48029 (16.828 sec)
I1112 19:58:19.184203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.594248
I1112 19:58:34.221203 10460 basic_session_run_hooks.py:260] Accuracy = 0.45754534, Global Step = 5890, Loss = 2.1730132, Perplexity = 8.784715 (15.037 sec)
I1112 19:58:34.222203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664982
I1112 19:58:49.267203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.648433
I1112 19:58:49.267203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4297704, Global Step = 5900, Loss = 2.116167, Perplexity = 8.299266 (15.046 sec)
I1112 19:58:49.268203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664628
I1112 19:59:04.348203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5911 into logdir\run1\train\model.ckpt.
I1112 19:59:04.649233 10460 basic_session_run_hooks.py:260] Accuracy = 0.48760125, Global Step = 5910, Loss = 2.169169, Perplexity = 8.751008 (15.382 sec)
I1112 19:59:04.650203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.650111
I1112 19:59:21.200202 10460 basic_session_run_hooks.py:260] Accuracy = 0.4701966, Global Step = 5920, Loss = 2.2484362, Perplexity = 9.47291 (16.551 sec)
I1112 19:59:21.201203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.604193
I1112 19:59:36.244203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4588126, Global Step = 5930, Loss = 2.1582, Perplexity = 8.655544 (15.044 sec)
I1112 19:59:36.245204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664717
I1112 19:59:51.273203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4649611, Global Step = 5940, Loss = 2.131285, Perplexity = 8.425687 (15.029 sec)
I1112 19:59:51.274203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.66538
I1112 20:00:04.787202 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5950 into logdir\run1\train\model.ckpt.
I1112 20:00:06.836203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4899645, Global Step = 5950, Loss = 2.0643878, Perplexity = 7.8804717 (15.563 sec)
I1112 20:00:06.837205 10460 basic_session_run_hooks.py:692] global_step/sec: 0.642591
I1112 20:00:23.256202 10460 basic_session_run_hooks.py:260] Accuracy = 0.46710333, Global Step = 5960, Loss = 2.0516171, Perplexity = 7.7804728 (16.420 sec)
I1112 20:00:23.257204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.608976
I1112 20:00:38.337203 10460 basic_session_run_hooks.py:260] Accuracy = 0.4732272, Global Step = 5970, Loss = 2.0955892, Perplexity = 8.130229 (15.081 sec)
I1112 20:00:38.338203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.663086
I1112 20:00:53.438203 10460 basic_session_run_hooks.py:260] Accuracy = 0.47448277, Global Step = 5980, Loss = 2.0339272, Perplexity = 7.6440473 (15.101 sec)
I1112 20:00:53.439203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.662208
I1112 20:01:05.454202 10460 basic_session_run_hooks.py:606] Saving checkpoints for 5989 into logdir\run1\train\model.ckpt.
I1112 20:01:09.205203 10460 basic_session_run_hooks.py:260] Accuracy = 0.51546574, Global Step = 5990, Loss = 1.9605951, Perplexity = 7.1035533 (15.767 sec)
I1112 20:01:09.205203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.634276
I1112 20:01:25.440203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.640316
I1112 20:01:25.440203 10460 basic_session_run_hooks.py:260] Accuracy = 0.512974, Global Step = 6000, Loss = 1.9588783, Perplexity = 7.091368 (16.235 sec)
I1112 20:01:25.441203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.615915
I1112 20:01:40.461203 10460 basic_session_run_hooks.py:260] Accuracy = 0.50322104, Global Step = 6010, Loss = 1.9281276, Perplexity = 6.8766227 (15.021 sec)
I1112 20:01:40.461203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.665779
I1112 20:01:55.509202 10460 basic_session_run_hooks.py:260] Accuracy = 0.47040108, Global Step = 6020, Loss = 2.1207173, Perplexity = 8.337115 (15.048 sec)
I1112 20:01:55.510203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.66454
I1112 20:02:06.082203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 6028 into logdir\run1\train\model.ckpt.
I1112 20:02:11.984203 10460 basic_session_run_hooks.py:260] Accuracy = 0.47873828, Global Step = 6030, Loss = 2.0044918, Perplexity = 7.4223213 (16.475 sec)
I1112 20:02:11.985203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.606943
I1112 20:02:27.325203 10460 basic_session_run_hooks.py:260] Accuracy = 0.49878725, Global Step = 6040, Loss = 1.9814745, Perplexity = 7.2534304 (15.341 sec)
I1112 20:02:27.325203 10460 basic_session_run_hooks.py:692] global_step/sec: 0.651891
I1112 20:02:42.366204 10460 basic_session_run_hooks.py:260] Accuracy = 0.50656706, Global Step = 6050, Loss = 2.078356, Perplexity = 7.99132 (15.041 sec)
I1112 20:02:42.366204 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664849
I1112 20:02:57.417242 10460 basic_session_run_hooks.py:260] Accuracy = 0.49890554, Global Step = 6060, Loss = 2.057629, Perplexity = 7.8273897 (15.050 sec)
I1112 20:02:57.417242 10460 basic_session_run_hooks.py:692] global_step/sec: 0.664406
I1112 20:03:06.452203 10460 basic_session_run_hooks.py:606] Saving checkpoints for 6067 into logdir\run1\train\model.ckpt.
E1112 20:03:08.279203 10460 basic_session_run_hooks.py:760] Model diverged with loss = NaN.
Traceback (most recent call last):
  File "c:\users\claire\appdata\local\programs\python\python35\lib\runpy.py", line 193, in _run_module_as_main
    "__main__", mod_spec)
  File "c:\users\claire\appdata\local\programs\python\python35\lib\runpy.py", line 85, in _run_code
    exec(code, run_globals)
  File "C:\Users\Claire\AppData\Local\Programs\Python\Python35\Scripts\drums_rnn_train.exe\__main__.py", line 9, in <module>
  File "c:\users\claire\appdata\local\programs\python\python35\lib\site-packages\magenta\models\drums_rnn\drums_rnn_train.py", line 108, in console_entry_point
    tf.app.run(main)
  File "c:\users\claire\appdata\local\programs\python\python35\lib\site-packages\tensorflow\python\platform\app.py", line 40, in run
    _run(main=main, argv=argv, flags_parser=_parse_flags_tolerate_undef)
  File "c:\users\claire\appdata\local\programs\python\python35\lib\site-packages\absl\app.py", line 300, in run
    _run_main(main, args)
  File "c:\users\claire\appdata\local\programs\python\python35\lib\site-packages\absl\app.py", line 251, in _run_main
    sys.exit(main(argv))
  File "c:\users\claire\appdata\local\programs\python\python35\lib\site-packages\magenta\models\drums_rnn\drums_rnn_train.py", line 104, in main
    checkpoints_to_keep=FLAGS.num_checkpoints)
  File "c:\users\claire\appdata\local\programs\python\python35\lib\site-packages\magenta\models\shared\events_rnn_train.py", line 84, in run_training
    is_chief=task == 0)
  File "c:\users\claire\appdata\local\programs\python\python35\lib\site-packages\tensorflow\contrib\training\python\training\training.py", line 549, in train
    loss = session.run(train_op, run_metadata=run_metadata)
  File "c:\users\claire\appdata\local\programs\python\python35\lib\site-packages\tensorflow\python\training\monitored_session.py", line 754, in run
    run_metadata=run_metadata)
  File "c:\users\claire\appdata\local\programs\python\python35\lib\site-packages\tensorflow\python\training\monitored_session.py", line 1252, in run
    run_metadata=run_metadata)
  File "c:\users\claire\appdata\local\programs\python\python35\lib\site-packages\tensorflow\python\training\monitored_session.py", line 1353, in run
    raise six.reraise(*original_exc_info)
  File "c:\users\claire\appdata\local\programs\python\python35\lib\site-packages\six.py", line 693, in reraise
    raise value
  File "c:\users\claire\appdata\local\programs\python\python35\lib\site-packages\tensorflow\python\training\monitored_session.py", line 1338, in run
    return self._sess.run(*args, **kwargs)
  File "c:\users\claire\appdata\local\programs\python\python35\lib\site-packages\tensorflow\python\training\monitored_session.py", line 1419, in run
    run_metadata=run_metadata))
  File "c:\users\claire\appdata\local\programs\python\python35\lib\site-packages\tensorflow\python\training\basic_session_run_hooks.py", line 761, in after_run
    raise NanLossDuringTrainingError
tensorflow.python.training.basic_session_run_hooks.NanLossDuringTrainingError: NaN loss during training.
```