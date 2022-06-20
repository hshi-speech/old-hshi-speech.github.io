
## <i class="fa fa-chevron-right"></i> Publications

Representative publications that I am a primary author on are
<span style='background-color: #ffffd0'>highlighted.</span><br>
[<a href="https://scholar.google.com/citations?user=DclFbLwAAAAJ&hl">Google Scholar</a>]


<h2>First Author</h2>
<table class="table table-hover">
<tr id="tr-shi21_apsipa" style="background-color: #ffffd0">
<td>
    Hao&nbsp;Shi, Longbiao&nbsp;Wang, Sheng&nbsp;Li, Cunhang&nbsp;Fan, Jianwu&nbsp;Dang, and Tatsuya&nbsp;Kawahara<br>
    <em><a href='https://github.com/hshi-speech/resume/blob/main/pdf/APSIPA-2021.pdf' target='_blank'>Spectrograms Fusion-based End-to-end Robust Automatic Speech Recognition</a> </em><br>
    In Proc. APSIPA ASC, pp.438--442, 2021.<br>
</td>
</tr>

<tr id="tr-shi20_interspeech" style="background-color: #ffffd0">
<td>
    Hao&nbsp;Shi, Longbiao&nbsp;Wang, Sheng&nbsp;Li, Chenchen&nbsp;Ding, Meng&nbsp;Ge, Nan&nbsp;Li, Jianwu&nbsp;Dang, and Hiroshi&nbsp;Seki<br>
    <em><a href='https://github.com/hshi-speech/resume/blob/main/pdf/Wed-1-11-1.pdf' target='_blank'>Singing Voice Extraction with Attention-Based Spectrograms Fusion</a> </em><br>
    In Proc. INTERSPEECH, pp.2412--2416, 2020.<br>
</td>
</tr>


<tr id="tr-9054661" style="background-color: #ffffd0">
<td>
    Hao&nbsp;Shi, Longbiao&nbsp;Wang, Meng&nbsp;Ge, Sheng&nbsp;Li, and Jianwu&nbsp;Dang<br>
    <em><a href='https://github.com/hshi-speech/resume/blob/main/pdf/0007539.pdf' target='_blank'>Spectrograms Fusion with Minimum Difference Masks Estimation for Monaural Speech Dereverberation</a> </em><br>
    In Proc. ICASSP, pp.7539--7543, 2020.<br>
</td>
</tr>


</table>



<h2>Co-first Author</h2>
<table class="table table-hover">

<tr id="tr-qiang21_iconip" style="background-color: #ffffd0">
<td>
    <em><a href='https://github.com/hshi-speech/resume/blob/main/pdf/SaSD.pdf' target='_blank'>Speech Dereverberation Based on Scale-aware Mean Square Error Loss</a> </em><br>
    Luya&nbsp;Qiang, <strong><a href='https://scholar.google.com/citations?user=DclFbLwAAAAJ' target='_blank'>Hao&nbsp;Shi&nbsp;(Joint&nbsp;First&nbsp;Author)</a></strong>, <a href='https://scholar.google.com/citations?user=Ody4GF0AAAAJ' target='_blank'>Meng&nbsp;Ge</a>, Haoran&nbsp;Yin, <a href='https://scholar.google.com/citations?user=9BVJbdsAAAAJ' target='_blank'>Nan&nbsp;Li</a>, <a href='https://scholar.google.com/citations?user=1Z9_5ZgAAAAJ' target='_blank'>Longbiao&nbsp;Wang</a>, <a href='https://scholar.google.com/citations?user=zHAhs0IAAAAJ' target='_blank'>Sheng&nbsp;Li</a>, and <a href='https://scholar.google.com/citations?user=Wk5ApskAAAAJ' target='_blank'>Jianwu&nbsp;Dang</a><br>
    ICONIP 2021  <br>
    [1] 
[<a href='javascript:;'
    onclick='$("#abs_qiang21_iconip").toggle()'>abs</a>]<br>
    
<div id="abs_qiang21_iconip" style="text-align: justify; display: none" markdown="1">
Recently, deep learning-based speech dereverberation approaches have achieved remarkable performance by directly
mapping the input spectrogram to a target spectrogram or time-frequency mask. However, these approaches are usually
optimized under distance-related objective functions: the mean square error (MSE). The traditional MSE training
criterion results in a strong inherent uniform variance statistical assumption on the target speech and noise during
training, which cannot be satisfied in real-world scenarios. To alleviate such an assumption mismatch problem, we
propose a speech dereverberation solution called Scale-aware Speech Dereverberation (SaSD) based on scaled-MSE.
Specifically, we modify the MSE with different scales for each frequency band and progressively reduce the gap
between the low- and high-frequency ranges to make the error follow the assumption of MSE assumption. Experiments
demonstrated that SaSD achieved 1.0 SRMR and 0.8 PESQ improvements over the mapping baseline system.
</div>

</td>
</tr>


<tr id="tr-yin21_iconip" style="background-color: #ffffd0">
<td>
    <em><a href='https://github.com/hshi-speech/resume/blob/main/pdf/iconip2021-yin.pdf' target='_blank'>Simultaneous Progressive Filtering-based Monaural Speech Enhancement</a> </em><br>
    Haoran&nbsp;Yin, <strong><a href='https://scholar.google.com/citations?user=DclFbLwAAAAJ' target='_blank'>Hao&nbsp;Shi&nbsp;(Joint&nbsp;First&nbsp;Author)</a></strong>, <a href='https://scholar.google.com/citations?user=1Z9_5ZgAAAAJ' target='_blank'>Longbiao&nbsp;Wang</a>, Luya&nbsp;Qiang, <a href='https://scholar.google.com/citations?user=zHAhs0IAAAAJ' target='_blank'>Sheng&nbsp;Li</a>, <a href='https://scholar.google.com/citations?user=Ody4GF0AAAAJ' target='_blank'>Meng&nbsp;Ge</a>, Gaoyan&nbsp;Zhang, and <a href='https://scholar.google.com/citations?user=Wk5ApskAAAAJ' target='_blank'>Jianwu&nbsp;Dang</a><br>
    ICONIP 2021  <br>
    [2] 
[<a href='javascript:;'
    onclick='$("#abs_yin21_iconip").toggle()'>abs</a>]<br>
    
<div id="abs_yin21_iconip" style="text-align: justify; display: none" markdown="1">
Speech enhancement (SE) benefits from multi-stage stacking. However, this will introduce a lot of new
parameters to the neural network. In this paper, we propose a simultaneous progressive filtering based
monaural SE model. Mapping-based and masking-based SE systems are simultaneously obtained with
multi-target learning (MTL). Different from other MTL systems, our proposed model addresses different
enhancement needs. The mapping-based SE system aims to recover speech signals from noisy features. While
the masking-based SE system serves as a post-filtering to further reduce the noise that still exists
after the mapping-based SE system. With the high signal-to-noise ratio inputs, noise reduction of the
masking-based SE system is obvious with little speech signal loss. These two stages share one neural
network which controls the parameters of the entire system with little or no increase. In addition, our approach is easy to integrate with existing methods and improve their performance significantly and
stably. The experiments on Valentini-Botinhao data set show our proposed model achieves 0.12 PESQ
improvement compared with directly mapping-based and masking-based SE systems both in single-target
and multi-target learning. Furthermore, by comparing spectrograms, we find that our proposed models are
able to recover better harmonic information.
</div>

</td>
</tr>
</table>



<h2>Co-author</h2>
<table class="table table-hover">

<tr id="tr-ge19_interspeech" >
<td>
    <em><a href='https://github.com/hshi-speech/resume/blob/main/pdf/1477.pdf' target='_blank'>Environment-Dependent Attention-Driven Recurrent Convolutional Neural Network for Robust Speech Enhancement</a> </em><br>
    <a href='https://scholar.google.com/citations?user=Ody4GF0AAAAJ' target='_blank'>Meng&nbsp;Ge</a>, <a href='https://scholar.google.com/citations?user=1Z9_5ZgAAAAJ' target='_blank'>Longbiao&nbsp;Wang</a>, <a href='https://scholar.google.com/citations?user=9BVJbdsAAAAJ' target='_blank'>Nan&nbsp;Li</a>, <strong><a href='https://scholar.google.com/citations?user=DclFbLwAAAAJ' target='_blank'>Hao&nbsp;Shi</a></strong>, <a href='https://scholar.google.com/citations?user=Wk5ApskAAAAJ' target='_blank'>Jianwu&nbsp;Dang</a>, and Xiangang&nbsp;Li<br>
    INTERSPEECH 2019  <br>
    [6] 
[<a href='javascript:;'
    onclick='$("#abs_ge19_interspeech").toggle()'>abs</a>]<br>
    
<div id="abs_ge19_interspeech" style="text-align: justify; display: none" markdown="1">
Speech enhancement aims to keep the real speech signal and reduce noise for building robust communication systems.
Under the success of DNN, significant progress has been made. Nevertheless, accuracy of the speech enhancement
system is not satisfactory due to insufficient consideration of varied environmental and contextual information in
complex cases. To address these problems, this research proposes an end-to-end environment-dependent attention-driven
approach. The local frequency-temporal pattern via convolutional neural network is fully employed without pooling
operation. It then integrates an attention mechanism into bidirectional long short-term memory to acquire the weighted
dynamic context between consecutive frames. Furthermore, dynamic environment estimation and phase correction further
improve the generalization ability. Extensive experimental results on REVERB challenge demonstrated that the proposed
approach outperformed existing methods, improving PESQ from 2.56 to 2.87 and SRMR from 4.95 to 5.50 compared with conventional DNN.
</div>

</td>
</tr>

</table>

