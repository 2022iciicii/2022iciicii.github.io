---
permalink: /Speech/
redirect_from:
  - /resume
---

{% include base_path %}
<div class="speech-container">
    <h1>Keynote / Invited Speech</h1>
    <div class="speeches">
        <div class="speech-column">
            <h2>2022</h2>
            <ul>
                <li><a href="talk3-1/">Prof. Wenjun Zhang: Some Landmark works of Madan M. Gupta with his Collaborators</a></li>
                <li><a href="talk3-2/">Prof. Dingfang Chen : "Smart Manufacturing" the Popularization of Science Report</a></li>
                <li><a href="talk3-3/">Prof. Qingfu Zhang: Use of Models in MOEA/D</a></li>
                <li><a href="talk3-4/">Prof. Shouyong Jiang: When Evolutionary Computation Meets Biology</a></li>
                <li><a href="talk3-5/">Prof. Zhifeng Hao: New Thoughts of Sciences Inspired by the Metaverse</a></li>
                <li><a href="talk3-6/">Prof. Kaushik Rajashekara: Energy Impacts of Autonomous and Connected Vehicles and the Future Trends</a></li>
                <li><a href="talk3-7/">Prof. Haibin Zhu: Computational Social Simulation using E-CARGO</a></li>
                <li><a href="talk3-8/">Prof. Leonid Ivanov: Promising Areas of Research and Techonlogical Cooperation in Different Fields of Engineering</a></li>
                <li><a href="talk3-9/">Prof. Jiang Zhu: Challenge for the Next Generation Smart Manufacturing Revolutionized by Digital Technology-- Towards the Realization for Super Smart Society (Society 5.0)</a></li>
                <li><a href="talk3-10/">Prof. Huawei Tu: Human-Computer Interaction Design Based on the Crossing Paradigm</a></li>
                <li><a href="talk3-11/">Prof. Jiang Wu: Evaluation of Nonlinear Vibration Characteristics and Stiffness Compensation of Functional Polymer Ultrasonic Actuators</a></li>
                <li><a href="talk3-12/">Prof. Arturo Suman Bretas: Towards Smart Grids Enhanced Situation Awareness: A Bi-Level Quasi-Static State Estimation Model</a></li>
                <li><a href="talk3-13/">Prof. Yanjie Wang : Ionic Flexible Sensors: from Mechanism, Fabrication to Applications</a></li>
                <li><a href="talk3-14/">Prof. Hui Cheng: Control and Perception of Intelligent Robots</a></li>
                <li><a href="talk3-15/">Prof. Xiaomin Zhu: Automatic Design Method of Behavior Logic for Swarm Robotics</a></li>
                <li><a href="talk3-16/">Prof. Liangming Chen: Angle Rigidity Graph Theory for Multi-agent Formations</a></li>
                <li><a href="talk3-17/">Prof. Geng Zhang: An Introduction to Hyperspectral Imaging Technology and Its Potential Applications in Intelligent System</a></li>
                <li><a href="talk3-18/">Prof. Zhongtao Fu: Lie-Theory-Based Robot Kinematics-Dynamics Modelling and Application</a></li>
                <li><a href="talk3-19/">Prof. Chunxu Li: Core Research on Human-robot Skill Transfer:an Application to Human-centred Domestic Caregiving Robots</a></li>
                <li><a href="talk3-20/">Prof. Qing Zhang: Dynamic Semiconductor Junctions for Mechanical-to-electric Power Conversion and Sensing</a></li>
            </ul>
        </div>
    </div>
</div>

<style>
  
.speeches {
    display: flex;
    flex-wrap: wrap;
    justify-content: center; /* 使所有列居中对齐 */
    gap: 20px; /* 每列之间的间距 */
}

.speech-column {
    width: 50%; /* 设置每列宽度为 22%，以便能够容纳四列，并留出间隙 */
    box-sizing: border-box; /* 确保 padding 和 border 不影响整体宽度 */
    padding: 10px;
    background-color: #f9f9f9; /* 给每列添加背景色，使它们更明显 */
    text-align: center; /* 每列内文本居中 */
}

.speech-column h2 {
    font-size: 1.2em; /* 调整标题大小 */
    color: #2c3e50; /* 设置标题颜色 */
    margin-bottom: 12px; /* 与列表之间的间距 */
    text-align: center;
}

.speech-column ul {
    list-style-type: none;
    padding: 0;
}

.speech-column li {
    margin: 15px 0;
    padding: 20px;
    background-color: #f1f1f1;
    border: 1px solid #ddd;
    border-radius: 5px;
    height: 200px; /* 设置固定高度，确保每个框的大小一致 */
    display: flex;
    align-items: center; /* 使文字在框内垂直居中 */
    transition: transform 0.3s, box-shadow 0.3s;
}

.speech-column li:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
}

.speech-column li a {
    text-decoration: none;
    color: #2980b9;
    font-weight: bold;
    text-align: center; /* 链接文字居中 */
    width: 100%;
}

.speech-column li a:hover {
    text-decoration: underline;
}


.speech-container {
    position: relative; /* 可选：如果不想保持相对定位，删除这行 */
    width: 100vw; /* 删除这一行，使容器不再强制占满整个视口宽度 */
    margin-left: calc(50% - 50vw); /* 删除这一行，取消强制容器宽度从页面边界开始 */
    padding: 30px;
    background-color: #ffffff;
    border-radius: 10px;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
}

.speech-container h1 {
    font-size: 2em;
    color: #2c3e50;
    margin-bottom: 20px;
    text-align: center;
    position: sticky; /* 保持标题在页面顶部可见 */
    top: 0;
    background-color: #ffffff;
    padding: 20px;
    z-index: 10;
}
  
</style>
