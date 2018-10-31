包来源：https://github.com/feng18/aliyun-opensearch

感谢feng18提供的包，由于该作者的composer包中用到each方法，该方法从php版本7.2开始已被废弃，故在该作者的基础上将each方法改动并自封composer包

如有人需要用到此包，建议根据opensearch文档https://help.aliyun.com/document_detail/29140.html?spm=a2c4g.11186623.6.611.6f021b62QXLErQ 在自身架构的services（或工具类）层重写该包src目录下的search方法，以便于扩展！
