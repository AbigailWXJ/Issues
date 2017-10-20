# 第10章问题集锦
请问练习题10.9节答案中：template<typename Sequence> 
auto println(Sequence const& seq) -> std::ostream& 
{ 
for (auto const& elem : seq) 
std::cout << elem << " "; 
return std::cout << std::endl; 
}
  请问上面这段程序中的箭头操作符是什么意思呢？才接触C++不是很了解，还请知道的朋友介绍一下，非常感谢
