# Dirigo-IoT : A Method for Integrating IoT Data into Industrial Process Analysis

With the increasing adoption of the Internet of Things (IoT) in industries, large volumes of IoT data are generated with the potential to improve process performance and transparency. However, in practice, IoT data are not integrated with process execution data and remain limited to isolated monitoring applications, limiting their usefulness for process analysis and decision support. Integrating IoT data with event logs is challenging due to differences in abstraction levels between IoT data and process events, as well as the separation of their data sources. Although existing research addresses IoT data integration, there is limited guidance on identifying process-relevant IoT
data and integrating it into process event logs. To address these gaps, this paper proposes Dirigo-IoT, a method for systematically integrating IoT data into event logs to support the analysis of IoT-enhanced business processes. It
builds on a classification of process-relevant IoT context to identify relevant IoT data for integration. The method leverages object-centric event logs (OCEL) to capture interactions between multiple business objects, which
are common in industrial settings where IoT devices are associated with multiple objects during process execution. To support practical application, we develop a tool, **IoTEL**, that enables semi-automated generation of IoT-
enriched event logs. Dirigo-IoT is demonstrated and evaluated through two real-world case studies in manufacturing and smart port environments. The results show that integrating IoT data enhances process performance anal-
ysis and enables the detection of patterns, such as operational inefficiencies and suspicious behaviours, that are not observable from event logs alone.

![alt text](<An Overview of Dirigo-IoT.png>)
