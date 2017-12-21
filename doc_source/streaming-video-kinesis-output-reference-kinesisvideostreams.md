# KinesisVideo<a name="streaming-video-kinesis-output-reference-kinesisvideostreams"></a>

Information about the Kinesis video stream that streams the source video into Rekognition Video\. For more information, see [Working with Streaming Videos](streaming-video.md)\.

**StreamArn**

The Amazon Resource Name \(ARN\) of the Kinesis video stream\.

Type: String 

**FragmentNumber**

The fragment of streaming video that contains the frame that this record represents\.

Type: String

**ProducerTimestamp**

The producer\-side time stamp of the fragment\. For more information, see [GetMedia](http://docs.aws.amazon.com/kinesisvideostreams/latest/dg/API_dataplane_GetMedia.html#API_dataplane_GetMedia_ResponseElements)\.

Type: Timestamp

**ServerTimestamp**

The server\-side time stamp of the fragment\. For more information, see [GetMedia](http://docs.aws.amazon.com/kinesisvideostreams/latest/dg/API_dataplane_GetMedia.html#API_dataplane_GetMedia_ResponseElements)\.

Type: Timestamp

**FrameOffsetInMillis**

The offset of the frame \(in milliseconds\) inside the fragment\.

Type: Number 