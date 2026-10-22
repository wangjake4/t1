代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenzaomai.com/Article/details/gtrydcique.html

[S15] C：类型转换
来源：http://dali.fengsongda.top/Article/details/gtnzpdozsq.html

(double) a / b
来源：http://dali.xziqi.cn/Article/details/gtknshlork.html

[S16] C：位操作置位
来源：http://dali.9152youxi.cn/Article/details/gtvvohlycu.html

x |= (1 << 3);
来源：http://dali.gotoacloud.top/Article/details/gtafzsyppe.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtwygflypl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jyoumei.cn/Article/details/gtpdebgylb.html

[S18] C：命令行参数
来源：http://dali.hammf.cn/Article/details/gtkbltzsri.html

int main(int argc, char **argv)
来源：http://dali.wangshuangyany.cn/Article/details/gtpmhmrpoo.html

[S19] C：快速排序
来源：http://dali.jianghu66.top/Article/details/gtiagzdhfk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfogrnsqa.html

[S20] C：二分查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwnllxiz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gtxxzsgsmt.html

[S21] C：字符类别判断
来源：http://dali.redwolf501.top/Article/details/gtjnbhtecv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shangyingyoupin.top/Article/details/gttqewrhhs.html

[S22] C：字符串转数字
来源：http://dali.gzhubu.top/Article/details/gtaqnjcqsi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gaohongyu789.top/Article/details/gtoprjchft.html

[S23] C：随机数
来源：http://dali.sweek.top/Article/details/gtgfdilaoo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthevinitg.html

[S24] C：获取本地时间
来源：http://dali.tianlin.xyz/Article/details/gtuirkiojf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhixingplan.top/Article/details/gtsopwkcay.html

[S25] C：内存拷贝
来源：http://dali.tianlin.xyz/Article/details/gtwzpomupm.html

memcpy(dst, src, n);
来源：http://dali.ydzc1.top/Article/details/gtoidgufsn.html

[S26] C：内存清零
来源：http://dali.tianlin.xyz/Article/details/gtsfskqvnj.html

memset(a, 0, sizeof a);
来源：http://dali.cucudq.cn/Article/details/gtlvmmhswn.html

[S27] C：定义常量
来源：http://dali.jianghu66.top/Article/details/gttutholbs.html

const double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtddhgkzos.html

[S28] C：静态变量
来源：http://dali.guowangkeji.top/Article/details/gtniffvvvk.html

static int counter = 0;
来源：http://dali.xuetiantiany.cn/Article/details/gtfxvcyjco.html

[S29] C：变参函数
来源：http://dali.sxryk.cn/Article/details/gtrzyxkvao.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.316326.xyz/Article/details/gtakfhgiml.html

[S30] C：头文件保护
来源：http://dali.tian-w.cn/Article/details/gtheytyyhq.html

#ifndef X_H
来源：http://dali.meibo888.top/Article/details/gtonaxljvd.html

#define X_H
来源：http://dali.nanxinkj.top/Article/details/gtuhbbblhw.html

#endif
来源：http://dali.xuanzx.com/Article/details/gtnsfpkpai.html

[S31] C++：Hello World
来源：http://dali.birdmap.top/Article/details/gtvoecmukh.html

#include <iostream>
来源：http://dali.ydzc1.top/Article/details/gtaqsoecgz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ppjwa.cn/Article/details/gtwjltrnui.html

[S32] C++：字符串
来源：http://dali.ehwqpu.com/Article/details/gtsaifkoxs.html

std::string s = "hi";  s += "!";
来源：http://dali.yj202588.top/Article/details/gtxinyhmvn.html

[S33] C++：vector 增删
来源：http://dali.316326.xyz/Article/details/gtfxxbicgh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pengpengdd.cyou/Article/details/gthdygxvvr.html

[S34] C++：遍历 vector
来源：http://dali.cheryme.top/Article/details/gtjujiuruq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.feifeiyinyue.top/Article/details/gtznietpxd.html

[S35] C++：map
来源：http://dali.cucudq.cn/Article/details/gtztxbxrjf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtofjmupit.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gtslfhbohq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvnapkra.html

[S37] C++：set
来源：http://dali.ehwqpu.com/Article/details/gtdxukgpzy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jianghu66.top/Article/details/gtxsjgqwml.html

[S38] C++：排序
来源：http://dali.0kj1m.cn/Article/details/gtasfxnfyl.html

std::sort(v.begin(), v.end());
来源：http://dali.cashguo.top/Article/details/gtpkhwyamb.html

[S39] C++：自定义比较器排序
来源：http://dali.tanke756.top/Article/details/gtkghdiocg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.andypj.xyz/Article/details/gtuggtfycs.html

[S40] C++：查找元素
来源：http://dali.guowangkeji.top/Article/details/gtbeavffbq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcaukyifr.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gtdrnyspnz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxuanxn.top/Article/details/gtgsjxendb.html

[S42] C++：继承与虚函数
来源：http://dali.redwolf501.top/Article/details/gtazeexisb.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigufen.top/Article/details/gtdibjuncb.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpmlauzo.html

auto p = std::make_unique<int>(5);
来源：http://dali.andypj.xyz/Article/details/gtuapsaxtq.html

[S44] C++：引用传参
来源：http://dali.yonumen.top/Article/details/gtndrzagmq.html

void inc(int &x) { ++x; }
来源：http://dali.hnqzz.top/Article/details/gtasexohyl.html

[S45] C++：lambda
来源：http://dali.snrcjt.cn/Article/details/gtyathosmz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sxryk.cn/Article/details/gthvgtzjhk.html

[S46] C++：函数模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthoqhrpth.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jlsjyb.cn/Article/details/gtnzuemcqv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtqimvquca.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.bjfxy.top/Article/details/gtdfsrlztm.html

[S48] C++：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtqoifqhgv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ivvv.top/Article/details/gtccfhbwol.html

while (std::getline(in, line)) { }
来源：http://dali.hfpthk.cn/Article/details/gtkvlyxhan.html

[S49] C++：写文件
来源：http://dali.gzhubu.top/Article/details/gtiofpnoxa.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.meibo888.top/Article/details/gtqvucrptf.html

[S50] C++：格式化数字
来源：http://dali.hongshengwenyu.top/Article/details/gtsispiree.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtiaheekxg.html

[S51] C++：显式类型转换
来源：http://dali.xuanzx.com/Article/details/gtxddohutk.html

static_cast<double>(a) / b
来源：http://dali.xuanzx.com/Article/details/gtkuvkabmi.html

[S52] C++：const 与 noexcept
来源：http://dali.yueranfly.top/Article/details/gtojfotauo.html

int size() const noexcept { return n_; }
来源：http://dali.jyoumei.cn/Article/details/gtnqkllgeh.html

[S53] C++：移动语义
来源：http://dali.smart0.xyz/Article/details/gtxspixpnx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gtkradzssv.html

[S54] C++：异常处理
来源：http://dali.jinghuilouyu.cn/Article/details/gteomreebo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tanke756.top/Article/details/gtxgmmmugu.html

[S55] C++：结构化绑定
来源：http://dali.chenlongwang.top/Article/details/gtkmfogmpy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.c1oappe.top/Article/details/gthvunjscm.html

[S56] C++：optional
来源：http://dali.hysaishi.cn/Article/details/gtjyztzhpk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuanzhike.top/Article/details/gtfahjqeeq.html

[S57] C++：编译期常量
来源：http://dali.xziqi.cn/Article/details/gtmalxnsnh.html

constexpr int N = 10;
来源：http://dali.bjfxy.top/Article/details/gtyahratto.html

[S58] C++：命名空间
来源：http://dali.chenzaomai.com/Article/details/gtdtrgtmmv.html

namespace ns { int f() { return 1; } }
来源：http://dali.mhx1999.top/Article/details/gtwrmgdazm.html

[S59] C++：静态断言
来源：http://dali.shangyingyoupin.top/Article/details/gtmyoxxrlp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gtzrxuhtbq.html

[S60] C++：遍历并删除元素
来源：http://dali.iojbl.cn/Article/details/gtqznpcusi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdsslovr.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gthwbxdqqa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xylfe.cn/Article/details/gtfeqjhbca.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtuagbithe.html

[T01] Kotlin：Hello World
来源：http://dali.fzhhl.top/Article/details/gtcbfognnj.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gthqhkwrzf.html

[T02] Kotlin：变量
来源：http://dali.fzhhl.top/Article/details/gtqlpflbty.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhixingplan.top/Article/details/gtfjqmjjkn.html

[T03] Kotlin：字符串模板
来源：http://dali.sxryk.cn/Article/details/gtmllzekel.html

"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gtjwkzsamx.html

[T04] Kotlin：空安全
来源：http://dali.yangfankeji.com/Article/details/gtvybepdto.html

val n: String? = null;  n?.length
来源：http://dali.vqdsnc.cn/Article/details/gtbfdvwdpt.html

[T05] Kotlin：when 表达式
来源：http://dali.zhoulong.xyz/Article/details/gtocvqcaxx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cashguo.top/Article/details/gtejujmokx.html

[T06] Kotlin：集合映射
来源：http://dali.yj202588.top/Article/details/gtjzxiwhnf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sxryk.cn/Article/details/gtxthczemu.html

[T07] Kotlin：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gtzxbsgsot.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxrmubgc.html

[T08] Kotlin：数据类
来源：http://dali.kuanghao11.cn/Article/details/gtdxvnugqv.html

data class User(val name: String, val age: Int)
来源：http://dali.hnqzz.top/Article/details/gtcipvubei.html

[T09] Kotlin：扩展函数
来源：http://dali.ivvv.top/Article/details/gtwylsvcaz.html

fun String.exclaim() = this + "!"
来源：http://dali.xuanzx.com/Article/details/gtcyiejwnu.html

[T10] Kotlin：默认参数
来源：http://dali.birdmap.top/Article/details/gthoejzsjy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gtbxoyuthg.html

[T11] Kotlin：协程
来源：http://dali.iojbl.cn/Article/details/gtezvfogfo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cucudq.cn/Article/details/gtjshvjafc.html

[T12] Kotlin：解构声明
来源：http://dali.jiagoushi.top/Article/details/gtuqsxznxk.html

val (a, b) = Pair(1, 2)
来源：http://dali.ydzc1.top/Article/details/gtbeiywsnt.html

[T13] Kotlin：只读 Map
来源：http://dali.jinghuilouyu.cn/Article/details/gtfumgxzsr.html

val m = mapOf("a" to 1)
来源：http://dali.gzhubu.top/Article/details/gtkywjsuyk.html

[T14] Kotlin：循环
来源：http://dali.yangfankeji.com/Article/details/gtecfhpeum.html

for (i in 1..10) println(i)
来源：http://dali.shuidangran.top/Article/details/gtrortwwma.html

[T15] Kotlin：接口
来源：http://dali.gogol.net.cn/Article/details/gtcakhxrsp.html

interface Shape { fun area(): Double }
来源：http://dali.cqqwz.cn/Article/details/gtbwqlrsjs.html

[T16] Swift：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtctdzssiw.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gtshrdgtct.html

[T17] Swift：变量与常量
来源：http://dali.guowangkeji.top/Article/details/gthamarnxc.html

var a = 1;  let b = 2
来源：http://dali.c1oappe.top/Article/details/gtwuosqphs.html

[T18] Swift：字符串插值
来源：http://dali.fzhhl.top/Article/details/gtuvcvdeiz.html

"值: \(b)"
来源：http://dali.316326.xyz/Article/details/gtcbrgprxw.html

[T19] Swift：可选绑定
来源：http://dali.havefunace.top/Article/details/gtkzysovbh.html

if let n = opt { print(n) }
来源：http://dali.pengpengdd.cyou/Article/details/gtbsvwqooy.html

[T20] Swift：数组操作
来源：http://dali.yuxming.cn/Article/details/gtdalhjirj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hfpthk.cn/Article/details/gtwsddhubd.html

[T21] Swift：遍历
来源：http://dali.c1oappe.top/Article/details/gtbkxyxedo.html

for x in a { print(x) }
来源：http://dali.shzxlz.cn/Article/details/gtvaqmxevf.html

[T22] Swift：字典
来源：http://dali.snrcjt.cn/Article/details/gtzzrzbswq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuanzx.com/Article/details/gtpnvnoojw.html

[T23] Swift：函数
来源：http://dali.yj202588.top/Article/details/gtowkajlgn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hysaishi.cn/Article/details/gtfwkhetcm.html

[T24] Swift：闭包
来源：http://dali.svipenyu.cn/Article/details/gtgzooaifp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnqzz.top/Article/details/gthivtnqdb.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangtech.top/Article/details/gtlflnebfq.html

struct P { var x: Int }
来源：http://dali.c1oappe.top/Article/details/gtgecaczgd.html

[T26] Swift：类与重写
来源：http://dali.yangfankeji.com/Article/details/gtnnidhkyc.html

class A: Base { override func f() {} }
来源：http://dali.0kj1m.cn/Article/details/gtbitosruz.html

[T27] Swift：错误处理
来源：http://dali.nanxinkj.top/Article/details/gtqfzrniii.html

do { try f() } catch { print(error) }
来源：http://dali.sufxvd.cn/Article/details/gtbhitoewy.html

[T28] Swift：枚举
来源：http://dali.chenzaomai.com/Article/details/gtwekanbwn.html

enum Color { case red, green }
来源：http://dali.yuxming.cn/Article/details/gtxtuwvyih.html

[T29] Swift：guard 提前返回
来源：http://dali.316326.xyz/Article/details/gtkhvfbtqa.html

guard let x = opt else { return }
来源：http://dali.ppjwa.cn/Article/details/gtyggconqg.html

[T30] Swift：协议
来源：http://dali.hnqzz.top/Article/details/gtijgbxtez.html

protocol Shape { func area() -> Double }
来源：http://dali.fzhhl.top/Article/details/gtzgihgitc.html

[T31] Lua：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtwpytutwl.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtwpelcuxa.html

[T32] Lua：局部变量
来源：http://dali.yongpay.top/Article/details/gtkkkycmjg.html

local a = 1
来源：http://dali.zhoulong.xyz/Article/details/gthprqqbdo.html

[T33] Lua：表（数组）
来源：http://dali.yj202588.top/Article/details/gtpcxylvvq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hammf.cn/Article/details/gtavsawcrm.html

[T34] Lua：遍历表
来源：http://dali.hongshengwenyu.top/Article/details/gtbiaxbkvs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.c1oappe.top/Article/details/gteygkqtgg.html

[T35] Lua：字典表
来源：http://dali.ivvv.top/Article/details/gtntkujzfs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtalymvabt.html

[T36] Lua：函数
来源：http://dali.dashuyun.cn/Article/details/gtzkfbvumr.html

function add(a, b) return a + b end
来源：http://dali.ybcxt.top/Article/details/gtzdmjrnij.html

[T37] Lua：字符串拼接
来源：http://dali.yongpay.top/Article/details/gtlxujrdas.html

"a" .. "b"
来源：http://dali.fengsongda.top/Article/details/gttxmynkkj.html

[T38] Lua：条件
来源：http://dali.tianlin.xyz/Article/details/gtrvmkxwko.html

if x > 0 then print("正") end
来源：http://dali.birdmap.top/Article/details/gtphsmiapt.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gtarwbmvda.html

string.find(s, "%d+")
来源：http://dali.guannengcc.top/Article/details/gtzazacmxk.html

[T40] Lua：元表
来源：http://dali.xuanzx.com/Article/details/gtbrbdgkae.html

setmetatable({}, { __index = base })
来源：http://dali.hongshengwenyu.top/Article/details/gtugxspgjb.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlmjcpwn.html

print "Hello\n";
来源：http://dali.gzhubu.top/Article/details/gtqajxavgz.html

[T42] Perl：变量类型
来源：http://dali.hnqzz.top/Article/details/gtasinvwyl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hnqzz.top/Article/details/gtukntszxf.html

[T43] Perl：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gtxcobtfsn.html

"值: $a"
来源：http://dali.316326.xyz/Article/details/gtiamikezx.html

[T44] Perl：条件
来源：http://dali.yuxming.cn/Article/details/gtwpvvpmsu.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtoozlnmvt.html

[T45] Perl：数组遍历
来源：http://dali.yj20258.top/Article/details/gtricwjerc.html

for my $x (@arr) { print $x; }
来源：http://dali.sweek.top/Article/details/gtreblnenc.html

[T46] Perl：哈希操作
来源：http://dali.xuetiantiany.cn/Article/details/gtnhxfmpli.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hnxiangtu.top/Article/details/gtffzuxunb.html

[T47] Perl：正则捕获
来源：http://dali.sweek.top/Article/details/gtvjvyepre.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nwbrower.top/Article/details/gtlslxpxzb.html

[T48] Perl：正则替换
来源：http://dali.tanke756.top/Article/details/gtlopoecpd.html

$s =~ s/old/new/g;
来源：http://dali.xuanzx.com/Article/details/gtksnlszrj.html

[T49] Perl：函数
来源：http://dali.yuanzhike.top/Article/details/gtlslqhyzs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtbekmwcrx.html

[T50] Perl：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtubnamosp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.fzhhl.top/Article/details/gtofnyxrnx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.daxiang520.top/Article/details/gtlohuswjq.html

[T51] Scala：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiswjrzhs.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gtyhtgaovc.html

[T52] Scala：变量
来源：http://dali.hnqzz.top/Article/details/gtlhfkxowz.html

val a = 1;  var b = 2
来源：http://dali.hysaishi.cn/Article/details/gtutemhxqs.html

[T53] Scala：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtgpbjhjzg.html

s"值: $b"
来源：http://dali.yj20258.top/Article/details/gtgolkxgwe.html

[T54] Scala：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gtfiykopbh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhengqikj.top/Article/details/gtgdqrjxjo.html

[T55] Scala：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gtvyjzubeg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhengqikj.top/Article/details/gtxvqlaaus.html

[T56] Scala：样例类
来源：http://dali.zhiwuduotai.top/Article/details/gtnxxbjmha.html

case class User(name: String, age: Int)
来源：http://dali.nanxinkj.top/Article/details/gtwygmfsim.html

[T57] Scala：模式匹配
来源：http://dali.yuxming.cn/Article/details/gtdjkraigo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.meibo888.top/Article/details/gtkqmbalnp.html

[T58] Scala：函数定义
来源：http://dali.havefunace.top/Article/details/gtnbbhdjtn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.quarkkingdee.top/Article/details/gtwleezsrl.html

[T59] Scala：循环
来源：http://dali.yonumen.top/Article/details/gtbxxipsiw.html

for (i <- 1 to 10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gtnnfrxmcl.html

[T60] Scala：折叠
来源：http://dali.tianlin.xyz/Article/details/gtgfsmqpdc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hywenlv.cn/Article/details/gtaqjqvxqw.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtlpjsqvmp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258888.top/Article/details/gtzbvsyzgg.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtcktsxdpd.html

[U01] Py：创建虚拟环境
来源：http://dali.gzhubu.top/Article/details/gtirqadrtp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangdashe.top/Article/details/gtsqpfnyyz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yongpay.top/Article/details/gtucqbfdhx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtwjjzdv.html

[U03] Py：加载 .env 配置
来源：http://dali.nanxinkj.top/Article/details/gtetfjqkle.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sysykeji.top/Article/details/gtjwgfwtqf.html

[U04] Py：变量调试打印
来源：http://dali.cucudq.cn/Article/details/gtwfmapara.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.316326.xyz/Article/details/gteqnfxrgy.html

[U05] Py：列表去重且保序
来源：http://dali.gaohongyu789.top/Article/details/gtzehtxsbv.html

list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gtzdunpdxo.html

[U06] Py：合并两个字典
来源：http://dali.zycfv.cn/Article/details/gtymxeyhcy.html

{**a, **b}
来源：http://dali.pycfn.com/Article/details/gtcwesawvl.html

[U07] Py：反转字典键值
来源：http://dali.snrcjt.cn/Article/details/gtowzkqats.html

{v: k for k, v in d.items()}
来源：http://dali.yueranfly.top/Article/details/gtmlpmwpwd.html

[U08] Py：展平二维列表
来源：http://dali.cdnleiting.top/Article/details/gtwxsttbqo.html

[y for x in nested for y in x]
来源：http://dali.yonumen.top/Article/details/gtxlqdkehm.html

[U09] Py：字典取最大值的键
来源：http://dali.xziqi.cn/Article/details/gtamfsmshm.html

max(d, key=d.get)
来源：http://dali.pycfn.com/Article/details/gtxicrevfl.html

[U10] Py：按值排序字典
来源：http://dali.ybcxt.top/Article/details/gtspejczvy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hnqzz.top/Article/details/gtjgawdpzp.html

[U11] Py：生成器表达式
来源：http://dali.yueranfly.top/Article/details/gtdzpxzrxk.html

(x * 2 for x in arr)
来源：http://dali.birdmap.top/Article/details/gtwhdeclnb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jqgufenzy.top/Article/details/gtwjokejre.html

Counter(arr).most_common(3)
来源：http://dali.hysaishi.cn/Article/details/gtqytzqhoh.html

[U13] Py：固定长度队列
来源：http://dali.gogol.net.cn/Article/details/gtwiblotnw.html

deque(maxlen=10)
来源：http://dali.dashuyun.cn/Article/details/gtsyqkknop.html

[U14] Py：分组收集到列表
来源：http://dali.smart0.xyz/Article/details/gtdetbwbml.html

defaultdict(list)
来源：http://dali.nanxuanxn.top/Article/details/gtzrdunrdi.html

[U15] Py：高精度计时
来源：http://dali.fengsongda.top/Article/details/gtvbadmxkz.html

t = time.perf_counter()
来源：http://dali.zhixingplan.top/Article/details/gtytaiinyx.html

[U16] Py：命令行参数解析
来源：http://dali.c1oappe.top/Article/details/gtfuyjzkoh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.fengsongda.top/Article/details/gtzstptfwi.html

[U17] Py：初始化日志
来源：http://dali.chenjidiqi.icu/Article/details/gtpodgfcxy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hnqzz.top/Article/details/gtifrgltfd.html

[U18] Py：预编译正则
来源：http://dali.yvedp.cn/Article/details/gtxrjrauei.html

pat = re.compile(r"\d+")
来源：http://dali.tianlin.xyz/Article/details/gtdnuhjwsw.html

[U19] Py：正则替换带回调
来源：http://dali.yongpay.top/Article/details/gtszzqodir.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ppjwa.cn/Article/details/gtgjpbwtnq.html

[U20] Py：缓存函数结果
来源：http://dali.hammf.cn/Article/details/gtcrglahiy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xylfe.cn/Article/details/gtwleizawl.html

[U21] Py：自定义上下文管理器
来源：http://dali.pengpengdd.cyou/Article/details/gtssseqvak.html

@contextlib.contextmanager
来源：http://dali.smart0.xyz/Article/details/gtccpbwfim.html

[U22] Py：矩阵转置
来源：http://dali.snrcjt.cn/Article/details/gthrsmyntw.html

list(zip(*m))
来源：http://dali.yj202588.top/Article/details/gtavmjqltt.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gtxzdmdtys.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gogol.net.cn/Article/details/gthvaktqsl.html

[U24] Py：路径操作
来源：http://dali.aizwys.cn/Article/details/gthkodsirc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gtuxpfwcmt.html

[U25] Py：CSV 按字典读
来源：http://dali.xziqi.cn/Article/details/gtmqtlxeet.html

csv.DictReader(f)
来源：http://dali.cashguo.top/Article/details/gtfhmfehdw.html

[U26] Py：并发下载
来源：http://dali.aizwys.cn/Article/details/gtlyxbkbyg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jiagoushi.top/Article/details/gtauakdydg.html

[U27] Py：异步 HTTP
来源：http://dali.cucudq.cn/Article/details/gtlfyfycvi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jqgfzy.top/Article/details/gtuxuasoec.html

[U28] Py：类型别名
来源：http://dali.sysykeji.top/Article/details/gtiugdqppf.html

UserId = int
来源：http://dali.yvedp.cn/Article/details/gtjoihtnlp.html

[U29] Py：属性校验
来源：http://dali.xuetiantiany.cn/Article/details/gtfqiomsfu.html

@property 与 @x.setter 配合
来源：http://dali.cdnleiting.top/Article/details/gtdjitwmta.html

[U30] Py：数据类
来源：http://dali.hammf.cn/Article/details/gtepjycosy.html

@dataclass(slots=True)
来源：http://dali.gaohongyu789.top/Article/details/gtydviipmu.html

[U31] Py：单测
来源：http://dali.hywenlv.cn/Article/details/gtbprlkbai.html

python -m pytest -q
来源：http://dali.daxiang520.top/Article/details/gtcnpqhtma.html

[U32] Py：代码格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsevcscwy.html

ruff format . && ruff check --fix .
来源：http://dali.yonumen.top/Article/details/gtsfmhbkmw.html

[U33] Py：打包发布
来源：http://dali.yj20258888.top/Article/details/gtjoffqmyb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yanxiufei.cn/Article/details/gtpvzulbdm.html

[U34] Py：判断编码
来源：http://dali.gaohongyu789.top/Article/details/gtmhptmfed.html

chardet.detect(raw)
来源：http://dali.kuanghao11.cn/Article/details/gtfspkziwm.html

[U35] Py：发送邮件
来源：http://dali.gotoacloud.top/Article/details/gtvikgfarn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlaynornm.html

[U36] Py：定时任务
来源：http://dali.cheryme.top/Article/details/gtwarexvgf.html

schedule.every(10).minutes.do(job)
来源：http://dali.shangyingyoupin.top/Article/details/gthgbgixie.html

[U37] Py：读写 Excel
来源：http://dali.jqgufenzy.top/Article/details/gtsjbjompi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.chenzaomai.com/Article/details/gtgvfxfcmi.html

[U38] Py：获取脚本所在目录
来源：http://dali.vqdsnc.cn/Article/details/gtuxrxsdog.html

Path(__file__).resolve().parent
来源：http://dali.tian-w.cn/Article/details/gtagwnlldy.html


<!-- 参考信息 -->