# SemanticSegmentationModel
#本代码在MainGpu中设定num与batch_size用于设定网络训练过程中的使用的BatchSize，BatchSize=batch_size*num;
#num 以时间为代价换取BatchSize的增大。
#本代码主要服务于语义分割，使用的网络为Deeplabv3,包括多GPU数据并行功能。
