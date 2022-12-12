# 导入相关模块
import web3

# 创建web3实例
w3 = web3.Web3()

#向web3发送爱的信息
w3.eth.sendTransaction({
    'to’:’0x...’， # web3的地址
    from’:0x...’，  # 您的地址
    value’:’1 ether’， # 您想要传递的价值
})

# 显示您对web3的爱的表达
print(*I love web3!)
