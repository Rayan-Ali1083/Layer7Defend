# Layer7Defend

The Edge-IIoT dataset has been featured as a "Document in the top 1% of Web of Science." This indicates that it is ranked within the top 1% of all publications indexed by the Web of Science (WoS) in terms of citations and impact.

In the project we will create a model to predict attack type based on the following 63 features:
frame.time
ip.src_host
ip.dst_host
arp.dst.proto_ipv4
arp.opcode
arp.hw.size
arp.src.proto_ipv4
icmp.checksum
icmp.seq_le
icmp.transmit_timestamp
icmp.unused
http.file_data
http.content_length
http.request.uri.query
http.request.method
http.referer
http.request.full_uri
http.request.version
http.response
http.tls_port
tcp.ack
tcp.ack_raw
tcp.checksum
tcp.connection.fin
tcp.connection.rst
tcp.connection.syn
tcp.connection.synack
tcp.dstport
tcp.flags
tcp.flags.ack
tcp.len
tcp.options
tcp.payload
tcp.seq
tcp.srcport
udp.port
udp.stream
udp.time_delta
dns.qry.name
dns.qry.name.len
dns.qry.qu
dns.qry.type
dns.retransmission
dns.retransmit_request
dns.retransmit_request_in
mqtt.conack.flags
mqtt.conflag.cleansess
mqtt.conflags
mqtt.hdrflags
mqtt.len
mqtt.msg_decoded_as
mqtt.msg
mqtt.msgtype
mqtt.proto_len
mqtt.protoname
mqtt.topic
mqtt.topic_len
mqtt.ver
mbtcp.len
mbtcp.trans_id
mbtcp.unit_id
Attack_label
Attack_type

Dataset link: https://www.kaggle.com/datasets/mohamedamineferrag/edgeiiotset-cyber-security-dataset-of-iot-iiot/data
