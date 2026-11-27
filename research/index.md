---
layout: page
title: Research
---

<style>
/* matches the Research/Publication/Project reference page */
.artifact-copy{max-width:698px;margin:0 auto}
.artifact-copy h1.sec{font-size:36px;line-height:1.6;margin:0 0 8px}
.artifact-copy h2{font-size:30px;line-height:1.6;margin:0 0 8px}
.artifact-copy h3{font-size:24px;line-height:1.4;margin:0 0 8px;color:#008aff}
.artifact-copy ul{margin:0 0 16px;padding-left:40px}
.artifact-copy ul ul{margin:0;list-style-type:circle}
.artifact-copy ul ul ul{list-style-type:square}
.artifact-copy ul.pubs li{margin-bottom:27px;overflow-wrap:anywhere}
@media (max-width:767px){.artifact-copy h2{font-size:26px;line-height:1.4}.artifact-copy ul{padding-left:24px}}
</style>

<div class="artifact-copy">
<h2 id="robotics-area">Robotics Area</h2>
<ul>
  <li>General Agent Framework for Embodied Robots
    <ul>
      <li>Household service robots must understand open-ended natural-language requests, act safely in real time, and remember what they have learned about a home across sessions.</li>
      <li><strong>Large language models (LLMs)</strong> are strong at understanding requests but too slow and unreliable for direct motor control, while reactive controllers are fast but cannot re-plan when the world no longer matches their map.</li>
      <li>Our research builds a <strong>general agent framework</strong> that separates these roles into cooperating layers, inspired by <strong>dual-process (System 1 · System 2) cognition</strong>.</li>
      <li>The AI Lab Robotics team is currently researching about
        <ul>
          <li>Dual-process architecture that bridges LLM-based deliberation and reflexive robot control</li>
          <li>Agent harness with long-term memory for lifelong household robots</li>
          <li>Robust perception and 3D mapping for long-running robot operation</li>
        </ul>
      </li>
    </ul>
  </li>
  <li>Optical Flow-Guided Visual SLAM for Robust Bird's-Eye-View (BEV) Map Construction in Dynamic Environments
    <ul>
      <li><strong>Visual SLAM</strong> estimates the robot's pose from camera input while incrementally building a map, but moving objects such as people and vehicles degrade both pose accuracy and map quality.</li>
      <li>The AI Lab Robotics team is currently researching about
        <ul>
          <li>Optical flow-based separation of static and dynamic regions for robust visual SLAM</li>
          <li>Temporal fusion of camera features into a consistent BEV representation</li>
          <li>Global BEV map construction for autonomous navigation and exploration</li>
        </ul>
      </li>
    </ul>
  </li>
  <li>Offline-to-Online Fine-Tuning for Goal-Conditioned RL with Quasimetric Distances
    <ul>
      <li><strong>Goal-conditioned reinforcement learning (RL)</strong> trains an agent to reach any given goal state, and <strong>quasimetric</strong> methods do this by learning the temporal distance between states and goals from offline data.</li>
      <li>Our research studies how such agents can keep improving when training moves from offline data to online interaction.</li>
      <li>The AI Lab Robotics team is currently researching about
        <ul>
          <li>Policy learning via selective imitation of online experience with realized progress toward the goal</li>
          <li>The effect of offline dataset characteristics on online fine-tuning</li>
          <li>Stable integration of online experience into offline-trained agents</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<h2 id="llm-agent-area">LLM Agent Area</h2>
<ul>
  <li>Self-Evolving AI Agent &amp; Harness Engineering
    <ul>
      <li>An <strong>AI agent</strong> is a system in which an LLM uses tools, memory and external environments to plan and carry out multi-step tasks on its own.</li>
      <li><strong>Harness engineering</strong> improves agent performance without updating model weights, by designing and refining the components around the LLM, such as skills, memory, prompts and context.</li>
      <li>The AI Lab AI Agent team is currently researching about
        <ul>
          <li>Self-evolving skills for small LLM-based agents</li>
          <li>Robust skill updates for out-of-distribution (OOD) environments</li>
          <li>Reliable acceptance of newly learned skills</li>
        </ul>
      </li>
    </ul>
  </li>
  <li>Efficient Prompt Optimization for LLM Agents
    <ul>
      <li>Automatic prompt optimizers such as <strong>GEPA</strong> improve a prompt through repeated run–reflect–rewrite cycles, which often costs hundreds of target-model calls per prompt.</li>
      <li>Our research aims to reduce this cost, so that prompts can be optimized efficiently while remaining editable natural-language prompts.</li>
      <li>The AI Lab AI Agent team is currently researching about
        <ul>
          <li>Cost-efficient automatic prompt optimization</li>
          <li>Learning-based approaches to prompt improvement</li>
          <li>Large-scale collection of prompt optimization data</li>
        </ul>
      </li>
    </ul>
  </li>
  <li>Selective Long-Term Memory for Conversational AI Agents
    <ul>
      <li><strong>Long-term memory</strong> lets a conversational agent use what a user said in earlier sessions, but many memory systems call an LLM on every turn to decide what to store, which is slow and also stores wrong or short-lived information.</li>
      <li>Our research studies how an agent can decide efficiently and reliably what is worth remembering.</li>
      <li>The AI Lab AI Agent team is currently researching about
        <ul>
          <li>Efficient selection of information worth remembering</li>
          <li>Reliable long-term memory across sessions</li>
          <li>On-device memory and forgetting for in-vehicle AI companions</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<h2 id="software-engineering-area">Software Engineering Area</h2>
<ul>
  <li>Software engineering is the systematic, disciplined and quantifiable development of software, so that it is reliable, maintainable, and delivered on time and within budget.</li>
  <li>It covers the whole software lifecycle, not just programming: requirements, design, implementation, testing, deployment and long-term maintenance.</li>
  <li>As software grows larger and more complex, ad-hoc coding leads to late, over-budget and buggy projects (the "software crisis"). Engineering principles help control this complexity.</li>
  <li>The AI Lab Software Engineering team is currently researching about
    <ul>
      <li>The effects of LLM code smells</li>
      <li>Model checking for Agent-Oriented Software Engineering (AOSE) with LLM-based agents</li>
    </ul>
  </li>
</ul>
</div>
