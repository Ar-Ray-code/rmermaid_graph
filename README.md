# rmermaid_graph

My rqt_graph outputs **mermaid** and GUI.


```bash
# Download
mkdir -p ~/ws_galactic/src
cd ~/ws_galactic/src
git clone https://github.com/Ar-Ray-code/rmermaid_graph.git
cd ../

# build
source /opt/ros/galactic/setup.bash
colcon build --symlink-install

# run
source ~/ws_galactic/install/setup.bash
rmermaid_graph

# # output example
# > ==== Export mermaid ====
# > '''mermaid
# > graph LR
# > /talker--> |/chatter| /_ros2cli_1955625
# > /talker--> |/chatter| /listener
# > '''
# > ========================

```

```mermaid
graph LR
/talker--> |/chatter| /_ros2cli_1955625
/talker--> |/chatter| /listener
```

<br>

![](image_readme/mermaid.png)