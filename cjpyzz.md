代发 wailian999

[S35] C++：map
来源：http://dali.shangyingyoupin.top/Article/details/gtvmavwimc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtujyzzjez.html

[S36] C++：unordered_map
来源：http://dali.meibo888.top/Article/details/gteryxepmv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtwgkadodn.html

[S37] C++：set
来源：http://dali.c1oappe.top/Article/details/gtrzuphfhi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.smart0.xyz/Article/details/gtmzksppbe.html

[S38] C++：排序
来源：http://dali.bjfxy.top/Article/details/gtxoqlujuq.html

std::sort(v.begin(), v.end());
来源：http://dali.svipenyu.cn/Article/details/gtpmdbudoj.html

[S39] C++：自定义比较器排序
来源：http://dali.shzxlz.cn/Article/details/gtisumpoji.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.iojbl.cn/Article/details/gtmksdtiaa.html

[S40] C++：查找元素
来源：http://dali.redwolf501.top/Article/details/gtkctrralc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daxiang520.top/Article/details/gtjxafhbrp.html

[S41] C++：类与构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprqizkxs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gtrgxcdfpy.html

[S42] C++：继承与虚函数
来源：http://dali.iojbl.cn/Article/details/gtccrrbzzl.html

class B : public Base { public: void f() override {} };
来源：http://dali.daria6918.cn/Article/details/gtupzorxqc.html

[S43] C++：智能指针
来源：http://dali.jiagoushi.top/Article/details/gtsfjwjhxj.html

auto p = std::make_unique<int>(5);
来源：http://dali.yangfankeji.com/Article/details/gthdcuextt.html

[S44] C++：引用传参
来源：http://dali.shzxlz.cn/Article/details/gtdjyylfcd.html

void inc(int &x) { ++x; }
来源：http://dali.gogol.net.cn/Article/details/gtowhwyhto.html

[S45] C++：lambda
来源：http://dali.tian-w.cn/Article/details/gtinoyvbet.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hfpthk.cn/Article/details/gtrokxbzzp.html

[S46] C++：函数模板
来源：http://dali.316326.xyz/Article/details/gtwwzttnho.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbprywynm.html

[S47] C++：结构化绑定遍历
来源：http://dali.andypj.xyz/Article/details/gtzkadxism.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jianghu66.top/Article/details/gtfopeuxzr.html

[S48] C++：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtfnrndyhl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgufenzy.top/Article/details/gtbgmhtywd.html

while (std::getline(in, line)) { }
来源：http://dali.zhongyouzk.top/Article/details/gttsxywkqz.html

[S49] C++：写文件
来源：http://dali.yvedp.cn/Article/details/gtgwwofdvn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gtzljwhnzt.html

[S50] C++：格式化数字
来源：http://dali.hnqzz.top/Article/details/gtwykgnzqm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangdashe.top/Article/details/gthhebewop.html

[S51] C++：显式类型转换
来源：http://dali.fzhhl.top/Article/details/gtnopxwekx.html

static_cast<double>(a) / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpullxll.html

[S52] C++：const 与 noexcept
来源：http://dali.dianchejie.cn/Article/details/gtgdtxijmf.html

int size() const noexcept { return n_; }
来源：http://dali.iojbl.cn/Article/details/gtvechzkia.html

[S53] C++：移动语义
来源：http://dali.tianlin.xyz/Article/details/gtbppqnrrt.html

std::vector<int> w = std::move(v);
来源：http://dali.c1oappe.top/Article/details/gtkxtsomzz.html

[S54] C++：异常处理
来源：http://dali.jqgfzy.top/Article/details/gtflkapjwa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjivpmloc.html

[S55] C++：结构化绑定
来源：http://dali.mhx1999.top/Article/details/gtejoeymgh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sweek.top/Article/details/gtzebvhgbh.html

[S56] C++：optional
来源：http://dali.xinyue.icu/Article/details/gtpdhldeho.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxinkj.top/Article/details/gtvrptgdys.html

[S57] C++：编译期常量
来源：http://dali.hysaishi.cn/Article/details/gtdacelfpv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gthsvyyjnw.html

[S58] C++：命名空间
来源：http://dali.jqgfzy.top/Article/details/gtdqtlmrsc.html

namespace ns { int f() { return 1; } }
来源：http://dali.bjfxy.top/Article/details/gtlxyymzig.html

[S59] C++：静态断言
来源：http://dali.chenzaomai.com/Article/details/gttrfcdcbu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sxryk.cn/Article/details/gtmhexdsdt.html

[S60] C++：遍历并删除元素
来源：http://dali.yonumen.top/Article/details/gtdtgzpgem.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtmwvvfvdm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtenybhzox.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gtucekudmu.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtxhdzmhft.html

[T01] Kotlin：Hello World
来源：http://dali.c1oappe.top/Article/details/gtumdhrtug.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gtfgzbyzgk.html

[T02] Kotlin：变量
来源：http://dali.fengsongda.top/Article/details/gtxrayogas.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjuqvufjb.html

[T03] Kotlin：字符串模板
来源：http://dali.yuanzhike.top/Article/details/gtqmwzjsnk.html

"值: $b"
来源：http://dali.pycfn.com/Article/details/gtaxneuvty.html

[T04] Kotlin：空安全
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkgmxvav.html

val n: String? = null;  n?.length
来源：http://dali.jinqigfzy.top/Article/details/gtmwpcbhyo.html

[T05] Kotlin：when 表达式
来源：http://dali.snrcjt.cn/Article/details/gtmjyblkca.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj202588.top/Article/details/gthqxezhvy.html

[T06] Kotlin：集合映射
来源：http://dali.cqqwz.cn/Article/details/gtzarjmyun.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ppjwa.cn/Article/details/gteimcgpfr.html

[T07] Kotlin：集合过滤
来源：http://dali.fengsongda.top/Article/details/gtrkzptmep.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sxryk.cn/Article/details/gtthmosqer.html

[T08] Kotlin：数据类
来源：http://dali.shzxlz.cn/Article/details/gthgonoaau.html

data class User(val name: String, val age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpaevsxd.html

[T09] Kotlin：扩展函数
来源：http://dali.daxiang520.top/Article/details/gtgfqceolt.html

fun String.exclaim() = this + "!"
来源：http://dali.c1oappe.top/Article/details/gtrhiyajig.html

[T10] Kotlin：默认参数
来源：http://dali.fengsongda.top/Article/details/gtpyaeecwu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ydzc1.top/Article/details/gteuejkopu.html

[T11] Kotlin：协程
来源：http://dali.ydzc1.top/Article/details/gthpbdaoot.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.snrcjt.cn/Article/details/gtgioemcwk.html

[T12] Kotlin：解构声明
来源：http://dali.nanxuanxn.top/Article/details/gtqatwefzv.html

val (a, b) = Pair(1, 2)
来源：http://dali.aizwys.cn/Article/details/gtwgrcxbsg.html

[T13] Kotlin：只读 Map
来源：http://dali.fzhhl.top/Article/details/gtzrbmqqve.html

val m = mapOf("a" to 1)
来源：http://dali.zhongyouzk.top/Article/details/gtuauzzjbw.html

[T14] Kotlin：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxstmcja.html

for (i in 1..10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gtcslfxozl.html

[T15] Kotlin：接口
来源：http://dali.sysykeji.top/Article/details/gtljlqeryl.html

interface Shape { fun area(): Double }
来源：http://dali.pengpengdd.cyou/Article/details/gtstutjmyr.html

[T16] Swift：Hello World
来源：http://dali.mhx1999.top/Article/details/gtvnoxppob.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gttnmhohre.html

[T17] Swift：变量与常量
来源：http://dali.yangfankeji.com/Article/details/gtjbwirgur.html

var a = 1;  let b = 2
来源：http://dali.havefunace.top/Article/details/gtohsogpkg.html

[T18] Swift：字符串插值
来源：http://dali.sweek.top/Article/details/gtgzkghfnn.html

"值: \(b)"
来源：http://dali.jinqigufen.top/Article/details/gtvfkkzjur.html

[T19] Swift：可选绑定
来源：http://dali.daria6918.cn/Article/details/gtuidrxbpf.html

if let n = opt { print(n) }
来源：http://dali.cashguo.top/Article/details/gtememjexs.html

[T20] Swift：数组操作
来源：http://dali.cheryme.top/Article/details/gtmhogooph.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.feifeiyinyue.top/Article/details/gtljjgzgue.html

[T21] Swift：遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnhzcjyc.html

for x in a { print(x) }
来源：http://dali.jinqigfzy.top/Article/details/gtzcmrqcca.html

[T22] Swift：字典
来源：http://dali.daxiang520.top/Article/details/gtnfgezhpi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuanzx.com/Article/details/gtbpwsdrkj.html

[T23] Swift：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxeyyhsa.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwaaexvtu.html

[T24] Swift：闭包
来源：http://dali.yuanzhike.top/Article/details/gtoqegbddi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtduowqbxc.html

[T25] Swift：结构体
来源：http://dali.ehwqpu.com/Article/details/gtcaqgnlmy.html

struct P { var x: Int }
来源：http://dali.gzhubu.top/Article/details/gtjpzahvvc.html

[T26] Swift：类与重写
来源：http://dali.yonumen.top/Article/details/gtzxtobaxz.html

class A: Base { override func f() {} }
来源：http://dali.ybcxt.top/Article/details/gtuurodftc.html

[T27] Swift：错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gtmjufsxhj.html

do { try f() } catch { print(error) }
来源：http://dali.sxryk.cn/Article/details/gtvwhdzmbq.html

[T28] Swift：枚举
来源：http://dali.xinyue.icu/Article/details/gtvlyepcmx.html

enum Color { case red, green }
来源：http://dali.yuanzhike.top/Article/details/gtpvzgghhe.html

[T29] Swift：guard 提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gtsqamgghw.html

guard let x = opt else { return }
来源：http://dali.birdmap.top/Article/details/gtvswxntqb.html

[T30] Swift：协议
来源：http://dali.jinqigufen.top/Article/details/gtfmpnkdwf.html

protocol Shape { func area() -> Double }
来源：http://dali.316326.xyz/Article/details/gtbshtcapf.html

[T31] Lua：Hello World
来源：http://dali.yj202588.top/Article/details/gtktvkstcy.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gtcpwspphw.html

[T32] Lua：局部变量
来源：http://dali.hysaishi.cn/Article/details/gtbezayusg.html

local a = 1
来源：http://dali.daxiang520.top/Article/details/gtjhnajmzr.html

[T33] Lua：表（数组）
来源：http://dali.hongshengwenyu.top/Article/details/gtpgzwvsms.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shuidangran.top/Article/details/gtyvuchwbj.html

[T34] Lua：遍历表
来源：http://dali.hfpthk.cn/Article/details/gtjgjrcrnp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.9152youxi.cn/Article/details/gtkfqssmbb.html

[T35] Lua：字典表
来源：http://dali.hnqzz.top/Article/details/gtxvksoyrj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.aibaodan.cn/Article/details/gtfarvbtwn.html

[T36] Lua：函数
来源：http://dali.birdmap.top/Article/details/gtnmobmqep.html

function add(a, b) return a + b end
来源：http://dali.guowangkeji.top/Article/details/gtrmxwxlty.html

[T37] Lua：字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gtbyhovuac.html

"a" .. "b"
来源：http://dali.andypj.xyz/Article/details/gtoslmoowc.html

[T38] Lua：条件
来源：http://dali.quarkkingdee.top/Article/details/gtqfrpxoob.html

if x > 0 then print("正") end
来源：http://dali.cqqwz.cn/Article/details/gthezbkkvb.html

[T39] Lua：模式匹配
来源：http://dali.cashguo.top/Article/details/gtislhgtlp.html

string.find(s, "%d+")
来源：http://dali.daxiang520.top/Article/details/gtxilmrvlx.html

[T40] Lua：元表
来源：http://dali.iojbl.cn/Article/details/gtkxwoauhs.html

setmetatable({}, { __index = base })
来源：http://dali.daria6918.cn/Article/details/gtirftkvnr.html

[T41] Perl：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtqtrfdprv.html

print "Hello\n";
来源：http://dali.hysaishi.cn/Article/details/gtsjjcchnu.html

[T42] Perl：变量类型
来源：http://dali.ydzc1.top/Article/details/gtgnrlvjhs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.bjfxy.top/Article/details/gtmdmulmpe.html

[T43] Perl：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtedgzgymp.html

"值: $a"
来源：http://dali.ivvv.top/Article/details/gttwznwbac.html

[T44] Perl：条件
来源：http://dali.gaohongyu789.top/Article/details/gttsgetjnl.html

if ($a > 0) { print "正"; }
来源：http://dali.hywenlv.cn/Article/details/gtmjfuelpw.html

[T45] Perl：数组遍历
来源：http://dali.yueranfly.top/Article/details/gtuoudijmt.html

for my $x (@arr) { print $x; }
来源：http://dali.haohaochexian.top/Article/details/gtsyogctyk.html

[T46] Perl：哈希操作
来源：http://dali.wangdashe.top/Article/details/gtziyubhvf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hnxiangtu.top/Article/details/gtqzrggmtf.html

[T47] Perl：正则捕获
来源：http://dali.chenlongwang.top/Article/details/gtvibvzwid.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.c1oappe.top/Article/details/gtogiuiqnl.html

[T48] Perl：正则替换
来源：http://dali.hammf.cn/Article/details/gtxkeethlt.html

$s =~ s/old/new/g;
来源：http://dali.xuetiantiany.cn/Article/details/gtvnsnkpsq.html

[T49] Perl：函数
来源：http://dali.andypj.xyz/Article/details/gtydneqdpp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtkidvqkum.html

[T50] Perl：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gteynoveoq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shuidangran.top/Article/details/gtnhygbkyk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ydzc1.top/Article/details/gtsmofkbrj.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetsyasoe.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtvtnfbktw.html

[T52] Scala：变量
来源：http://dali.zhongyouzk.top/Article/details/gtjhswaesi.html

val a = 1;  var b = 2
来源：http://dali.9152youxi.cn/Article/details/gtxwyizqad.html

[T53] Scala：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gtpkpiqrhd.html

s"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gtorcxjvzx.html

[T54] Scala：集合映射
来源：http://dali.xziqi.cn/Article/details/gtjzxlfzvj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xinyue.icu/Article/details/gtucqxiizs.html

[T55] Scala：集合过滤
来源：http://dali.jqgfzy.top/Article/details/gtkuorhlyu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.0kj1m.cn/Article/details/gtrbxxkpur.html

[T56] Scala：样例类
来源：http://dali.gotoacloud.top/Article/details/gtsumvxzve.html

case class User(name: String, age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtruwovlub.html

[T57] Scala：模式匹配
来源：http://dali.0kj1m.cn/Article/details/gtgdimhnpt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pengpengdd.cyou/Article/details/gtkvuguegh.html

[T58] Scala：函数定义
来源：http://dali.yonumen.top/Article/details/gtxmfatgtg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhengqikj.top/Article/details/gtpypqgmtz.html

[T59] Scala：循环
来源：http://dali.nanxuanxn.top/Article/details/gtlagftqgo.html

for (i <- 1 to 10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gtpyeemlzp.html

[T60] Scala：折叠
来源：http://dali.smart0.xyz/Article/details/gtpknmphxk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.vqdsnc.cn/Article/details/gtnpsauleq.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtczlptnqi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aizwys.cn/Article/details/gtgstsclgt.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtgwflrhdv.html

[U01] Py：创建虚拟环境
来源：http://dali.cashguo.top/Article/details/gtnhqtohln.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jqgufenzy.top/Article/details/gtpxwszejr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.daxiang520.top/Article/details/gtbazhxvte.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hywenlv.cn/Article/details/gtvwkislnz.html

[U03] Py：加载 .env 配置
来源：http://dali.cqqwz.cn/Article/details/gtrvdizvwv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuetiantiany.cn/Article/details/gtvnqpwzdd.html

[U04] Py：变量调试打印
来源：http://dali.jyoumei.cn/Article/details/gtksywgaau.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gotoacloud.top/Article/details/gtzcmsuwxk.html

[U05] Py：列表去重且保序
来源：http://dali.dianchejie.cn/Article/details/gtfewivjgn.html

list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gteqlbjxse.html

[U06] Py：合并两个字典
来源：http://dali.yvedp.cn/Article/details/gtvochkoco.html

{**a, **b}
来源：http://dali.bjfxy.top/Article/details/gtkuducfca.html

[U07] Py：反转字典键值
来源：http://dali.tanke756.top/Article/details/gtznkcqmzu.html

{v: k for k, v in d.items()}
来源：http://dali.jlsjyb.cn/Article/details/gtbaeymcog.html

[U08] Py：展平二维列表
来源：http://dali.hammf.cn/Article/details/gtkaftrynh.html

[y for x in nested for y in x]
来源：http://dali.kuanghao11.cn/Article/details/gtvrktrzge.html

[U09] Py：字典取最大值的键
来源：http://dali.hywenlv.cn/Article/details/gtuhipeoub.html

max(d, key=d.get)
来源：http://dali.hfpthk.cn/Article/details/gtzgfrowxw.html

[U10] Py：按值排序字典
来源：http://dali.sxryk.cn/Article/details/gtkpnixqor.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shuidangran.top/Article/details/gtnefhkpth.html

[U11] Py：生成器表达式
来源：http://dali.aizwys.cn/Article/details/gtpdjospwn.html

(x * 2 for x in arr)
来源：http://dali.yuanzhike.top/Article/details/gtpysxplyc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gzhubu.top/Article/details/gtpocbjolt.html

Counter(arr).most_common(3)
来源：http://dali.jyoumei.cn/Article/details/gtdpbzydnt.html

[U13] Py：固定长度队列
来源：http://dali.iojbl.cn/Article/details/gtjedmlkcc.html

deque(maxlen=10)
来源：http://dali.tanke756.top/Article/details/gthwhwxxge.html

[U14] Py：分组收集到列表
来源：http://dali.chenzaomai.com/Article/details/gtpxzjlans.html

defaultdict(list)
来源：http://dali.aibaodan.cn/Article/details/gtcyklokaa.html

[U15] Py：高精度计时
来源：http://dali.guowangkeji.top/Article/details/gtqaejxhgh.html

t = time.perf_counter()
来源：http://dali.iojbl.cn/Article/details/gtanvucukf.html

[U16] Py：命令行参数解析
来源：http://dali.xuetiantiany.cn/Article/details/gtwbmelrjl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hysaishi.cn/Article/details/gtnnycafix.html

[U17] Py：初始化日志
来源：http://dali.hnqzz.top/Article/details/gtekclheej.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daria6918.cn/Article/details/gtftgzuulz.html

[U18] Py：预编译正则
来源：http://dali.snrcjt.cn/Article/details/gtrjfaekpa.html

pat = re.compile(r"\d+")
来源：http://dali.nanxuanxn.top/Article/details/gtsuyjdzmp.html

[U19] Py：正则替换带回调
来源：http://dali.cucudq.cn/Article/details/gtzwwmhbrt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gaohongyu789.top/Article/details/gtkwdaosjm.html

[U20] Py：缓存函数结果
来源：http://dali.yueranfly.top/Article/details/gtuvxjomwo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jqgufenzy.top/Article/details/gtxrmpqvxl.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigufen.top/Article/details/gtfglpiwjx.html

@contextlib.contextmanager
来源：http://dali.yongpay.top/Article/details/gtsqsekanx.html

[U22] Py：矩阵转置
来源：http://dali.xuetiantiany.cn/Article/details/gtnhsavrwv.html

list(zip(*m))
来源：http://dali.ybcxt.top/Article/details/gtpybpuono.html

[U23] Py：分块读取大文件
来源：http://dali.wangshuangyany.cn/Article/details/gtavlexdwn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.c1oappe.top/Article/details/gtgwyclmfq.html

[U24] Py：路径操作
来源：http://dali.zhixingplan.top/Article/details/gtuzzjccxv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gtekciqlua.html

[U25] Py：CSV 按字典读
来源：http://dali.cdnleiting.top/Article/details/gttzstrcfj.html

csv.DictReader(f)
来源：http://dali.fengsongda.top/Article/details/gtwnrjfihm.html

[U26] Py：并发下载
来源：http://dali.quarkkingdee.top/Article/details/gthnetuqwa.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.snrcjt.cn/Article/details/gtyfdzfgqo.html

[U27] Py：异步 HTTP
来源：http://dali.cqqwz.cn/Article/details/gtgqokqlvi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.dashuyun.cn/Article/details/gthmsyenga.html

[U28] Py：类型别名
来源：http://dali.jqgufenzy.top/Article/details/gtsgqoovla.html

UserId = int
来源：http://dali.jianghu66.top/Article/details/gtmuhkxmgb.html

[U29] Py：属性校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhidwkgg.html

@property 与 @x.setter 配合
来源：http://dali.xziqi.cn/Article/details/gtrcxdaric.html

[U30] Py：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gtwvrfwdxf.html

@dataclass(slots=True)
来源：http://dali.ivvv.top/Article/details/gtbthqpjad.html

[U31] Py：单测
来源：http://dali.zhixingplan.top/Article/details/gtemogrpcg.html

python -m pytest -q
来源：http://dali.cdnleiting.top/Article/details/gtuglcmfhv.html

[U32] Py：代码格式化
来源：http://dali.hnxiangtu.top/Article/details/gtyocrloci.html

ruff format . && ruff check --fix .
来源：http://dali.316326.xyz/Article/details/gttgrqhgaw.html

[U33] Py：打包发布
来源：http://dali.yj20258.top/Article/details/gttcpnfneq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hywenlv.cn/Article/details/gtpjnufmpa.html

[U34] Py：判断编码
来源：http://dali.meibo888.top/Article/details/gtatiyrpbs.html

chardet.detect(raw)
来源：http://dali.meibo888.top/Article/details/gtcbtpoacb.html

[U35] Py：发送邮件
来源：http://dali.jqgufenzy.top/Article/details/gtqvsuuijj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj20258.top/Article/details/gtwixchmef.html

[U36] Py：定时任务
来源：http://dali.ehwqpu.com/Article/details/gtkmisxsaw.html

schedule.every(10).minutes.do(job)
来源：http://dali.iojbl.cn/Article/details/gtgysfecwd.html

[U37] Py：读写 Excel
来源：http://dali.mhx1999.top/Article/details/gtkneeowid.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.sufxvd.cn/Article/details/gtduoclvfo.html

[U38] Py：获取脚本所在目录
来源：http://dali.jiagoushi.top/Article/details/gthjztbjcl.html

Path(__file__).resolve().parent
来源：http://dali.wangshuangyany.cn/Article/details/gtgwaermhu.html

[U39] Py：判断是否在交互环境
来源：http://dali.kuanghao11.cn/Article/details/gtghdtxcln.html

sys.stdout.isatty()
来源：http://dali.hywenlv.cn/Article/details/gtjzjbjqjx.html

[U40] Py：打印到标准错误
来源：http://dali.xuetiantiany.cn/Article/details/gthfywvjju.html

print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gtgtnpuzca.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrcrhjwx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sxryk.cn/Article/details/gtctruajrx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yuxming.cn/Article/details/gtsiyeedli.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.meibo888.top/Article/details/gtodiapcle.html

[U43] PHP：声明命名空间
来源：http://dali.xuanzx.com/Article/details/gtzhkzbazl.html

namespace App\Http;
来源：http://dali.zhoulong.xyz/Article/details/gtvfanfres.html

[U44] PHP：开启严格类型
来源：http://dali.jyoumei.cn/Article/details/gtxpbbbqth.html

declare(strict_types=1);
来源：http://dali.wangdashe.top/Article/details/gtejrafvpy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.sxryk.cn/Article/details/gtronabfnj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtrwokhkvg.html

[U46] PHP：可空类型
来源：http://dali.zhiwuduotai.top/Article/details/gtgfvtmdzd.html

?string $name = null
来源：http://dali.nanxinkj.top/Article/details/gtsixajdqx.html

[U47] PHP：联合类型
来源：http://dali.yj20258888.top/Article/details/gtdfmwiyct.html

int|string $id
来源：http://dali.hnxiangtu.top/Article/details/gtweihowqb.html

[U48] PHP：纯枚举
来源：http://dali.xuanzx.com/Article/details/gtvxslgzbi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ydzc1.top/Article/details/gtpvnrlkzh.html

[U49] PHP：只读属性
来源：http://dali.pengpengdd.cyou/Article/details/gtsrwsocps.html

public readonly string $name
来源：http://dali.yanxiufei.cn/Article/details/gtvzbhaswh.html

[U50] PHP：构造器属性提升
来源：http://dali.ydzc1.top/Article/details/gtrdbbhsof.html

public function __construct(private int $id) {}
来源：http://dali.tian-w.cn/Article/details/gtomxbmvap.html

[U51] PHP：数组解构
来源：http://dali.jqgufenzy.top/Article/details/gtqbnvtkcw.html

[$a, $b] = $arr;
来源：http://dali.nwbrower.top/Article/details/gtnelzaues.html

[U52] PHP：箭头函数
来源：http://dali.sweek.top/Article/details/gtwrrnayds.html

$double = fn($x) => $x * 2;
来源：http://dali.zhixingplan.top/Article/details/gttpedpnxi.html

[U53] PHP：空合并运算符
来源：http://dali.yueranfly.top/Article/details/gtppfjscmb.html

$v = $a ?? $b ?? "default";
来源：http://dali.shangyingyoupin.top/Article/details/gtdppefcjw.html

[U54] PHP：空安全调用
来源：http://dali.zhengqikj.top/Article/details/gtheynmuzt.html

$obj?->method()
来源：http://dali.yuxming.cn/Article/details/gtnsiktzvv.html

[U55] PHP：match 表达式
来源：http://dali.yvedp.cn/Article/details/gtvefrbmxr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zdqjudy.top/Article/details/gtkkhuykbf.html

[U56] PHP：命名参数
来源：http://dali.0kj1m.cn/Article/details/gtizopwgku.html

f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtalrwcwfp.html

[U57] PHP：字符串插值
来源：http://dali.yj20258.top/Article/details/gtjveeagvt.html

"值: {$a}"
来源：http://dali.redwolf501.top/Article/details/gtoibgbflx.html

[U58] PHP：数组三件套
来源：http://dali.cashguo.top/Article/details/gtyqrymvdz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtpkpfkkxl.html

[U59] PHP：自定义排序
来源：http://dali.cucudq.cn/Article/details/gtuxmqeunm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhixingplan.top/Article/details/gtesjwyacb.html

[U60] PHP：JSON 编解码
来源：http://dali.chenlongwang.top/Article/details/gtlwoxzfsb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhengqikj.top/Article/details/gtdtcvjzha.html


<!-- 参考信息 -->