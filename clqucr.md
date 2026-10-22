代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yongpay.top/Article/details/gtumxggowd.html

[S25] C：内存拷贝
来源：http://dali.yueranfly.top/Article/details/gtuqtdtpmt.html

memcpy(dst, src, n);
来源：http://dali.shzxlz.cn/Article/details/gtfpgotlhc.html

[S26] C：内存清零
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewqzjyrv.html

memset(a, 0, sizeof a);
来源：http://dali.cqqwz.cn/Article/details/gtwdmekfeq.html

[S27] C：定义常量
来源：http://dali.yueranfly.top/Article/details/gttklohkub.html

const double PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gtduebpehi.html

[S28] C：静态变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtkocnquiv.html

static int counter = 0;
来源：http://dali.9152youxi.cn/Article/details/gtfmuatlop.html

[S29] C：变参函数
来源：http://dali.iojbl.cn/Article/details/gtcayowrku.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhongyouzk.top/Article/details/gtvvtoacum.html

[S30] C：头文件保护
来源：http://dali.jqgufenzy.top/Article/details/gtcarlqiyl.html

#ifndef X_H
来源：http://dali.nwbrower.top/Article/details/gtycetfofr.html

#define X_H
来源：http://dali.yj20258.top/Article/details/gtwpmwabqm.html

#endif
来源：http://dali.mhx1999.top/Article/details/gtgoxknpaf.html

[S31] C++：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtadcdaapb.html

#include <iostream>
来源：http://dali.daxiang520.top/Article/details/gtudamqpqg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jiagoushi.top/Article/details/gtapwtsxpl.html

[S32] C++：字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtxtkdvjmg.html

std::string s = "hi";  s += "!";
来源：http://dali.chenjidiqi.icu/Article/details/gtfgcjtzug.html

[S33] C++：vector 增删
来源：http://dali.svipenyu.cn/Article/details/gtiogscrec.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shuidangran.top/Article/details/gtozoigtpf.html

[S34] C++：遍历 vector
来源：http://dali.tian-w.cn/Article/details/gttksffdfa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zycfv.cn/Article/details/gtiklzjpfo.html

[S35] C++：map
来源：http://dali.hongshengwenyu.top/Article/details/gtzltmxjve.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtdladmxwy.html

[S36] C++：unordered_map
来源：http://dali.sweek.top/Article/details/gtvvnqwlvo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtymbgswgv.html

[S37] C++：set
来源：http://dali.shangyingyoupin.top/Article/details/gtexwvcfhm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenzaomai.com/Article/details/gtbdrbjpxm.html

[S38] C++：排序
来源：http://dali.quarkkingdee.top/Article/details/gtcedpbmdn.html

std::sort(v.begin(), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtiaczdugs.html

[S39] C++：自定义比较器排序
来源：http://dali.shzxlz.cn/Article/details/gtzhqgnywa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shzxlz.cn/Article/details/gterdrcqzk.html

[S40] C++：查找元素
来源：http://dali.xinyue.icu/Article/details/gtbrcgrwej.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daria6918.cn/Article/details/gtatinrjyc.html

[S41] C++：类与构造函数
来源：http://dali.zycfv.cn/Article/details/gtlihclgrm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgfzy.top/Article/details/gtrmmquuqe.html

[S42] C++：继承与虚函数
来源：http://dali.yj202588.top/Article/details/gtdgsyqhnt.html

class B : public Base { public: void f() override {} };
来源：http://dali.cdnleiting.top/Article/details/gtsppkqrzl.html

[S43] C++：智能指针
来源：http://dali.vqdsnc.cn/Article/details/gtssynemev.html

auto p = std::make_unique<int>(5);
来源：http://dali.fengsongda.top/Article/details/gtsnebgtjk.html

[S44] C++：引用传参
来源：http://dali.pycfn.com/Article/details/gtahglklsa.html

void inc(int &x) { ++x; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqcbeqzgs.html

[S45] C++：lambda
来源：http://dali.cheryme.top/Article/details/gtaimkfwbn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmtdoksu.html

[S46] C++：函数模板
来源：http://dali.yj20258888.top/Article/details/gtgctbbxue.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yonumen.top/Article/details/gtvgqdpouk.html

[S47] C++：结构化绑定遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwtwebqy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shangyingyoupin.top/Article/details/gtuilgtxbk.html

[S48] C++：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtcdcnbtvd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhoulong.xyz/Article/details/gtijwymiqw.html

while (std::getline(in, line)) { }
来源：http://dali.pycfn.com/Article/details/gtxkjrsuxd.html

[S49] C++：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gtsldiacwk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.0kj1m.cn/Article/details/gtngkhnwra.html

[S50] C++：格式化数字
来源：http://dali.jlsjyb.cn/Article/details/gtzurvbotb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtddjhzxmi.html

[S51] C++：显式类型转换
来源：http://dali.jinqigfzy.top/Article/details/gtpwrqjzkm.html

static_cast<double>(a) / b
来源：http://dali.mhx1999.top/Article/details/gtqhvkwhdd.html

[S52] C++：const 与 noexcept
来源：http://dali.hnxiangtu.top/Article/details/gthacxxfza.html

int size() const noexcept { return n_; }
来源：http://dali.dashuyun.cn/Article/details/gtkeowduju.html

[S53] C++：移动语义
来源：http://dali.daria6918.cn/Article/details/gtbsbhqndq.html

std::vector<int> w = std::move(v);
来源：http://dali.guowangkeji.top/Article/details/gtyhsgcosh.html

[S54] C++：异常处理
来源：http://dali.ehwqpu.com/Article/details/gtnqytxbol.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ybcxt.top/Article/details/gtuwbmceis.html

[S55] C++：结构化绑定
来源：http://dali.jqgufenzy.top/Article/details/gtueanqcdt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.dashuyun.cn/Article/details/gtyohnedwp.html

[S56] C++：optional
来源：http://dali.iojbl.cn/Article/details/gtedjuwpxz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zdqjudy.top/Article/details/gtheasqnaw.html

[S57] C++：编译期常量
来源：http://dali.jlsjyb.cn/Article/details/gtyhlzztah.html

constexpr int N = 10;
来源：http://dali.yvedp.cn/Article/details/gtvgosempf.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrbcuddd.html

namespace ns { int f() { return 1; } }
来源：http://dali.cashguo.top/Article/details/gtdzwfdqvo.html

[S59] C++：静态断言
来源：http://dali.wangshuangyany.cn/Article/details/gtemmkeojo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigufen.top/Article/details/gtttzvzggw.html

[S60] C++：遍历并删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gtkobiovcn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtxcgzfalf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtkrkrdssr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gtgqlrpcmb.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtyknjxdob.html

[T01] Kotlin：Hello World
来源：http://dali.cheryme.top/Article/details/gthnqwckln.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gtooxecmei.html

[T02] Kotlin：变量
来源：http://dali.hnxiangtu.top/Article/details/gtoyliqndi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pycfn.com/Article/details/gtxyfwjkeo.html

[T03] Kotlin：字符串模板
来源：http://dali.wangshuangyany.cn/Article/details/gtcswzdprr.html

"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gtvgpybhhl.html

[T04] Kotlin：空安全
来源：http://dali.jianghu66.top/Article/details/gtdkqworde.html

val n: String? = null;  n?.length
来源：http://dali.zhengqikj.top/Article/details/gttadfmdzv.html

[T05] Kotlin：when 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtfepgrjle.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigfzy.top/Article/details/gtdrvbyblq.html

[T06] Kotlin：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtimaanjzk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xziqi.cn/Article/details/gtbeyovcce.html

[T07] Kotlin：集合过滤
来源：http://dali.andypj.xyz/Article/details/gtwjgqxejl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sufxvd.cn/Article/details/gtatjimekd.html

[T08] Kotlin：数据类
来源：http://dali.smart0.xyz/Article/details/gtujbgnocp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhengqikj.top/Article/details/gtbqqpnmps.html

[T09] Kotlin：扩展函数
来源：http://dali.aizwys.cn/Article/details/gtcoccorgv.html

fun String.exclaim() = this + "!"
来源：http://dali.fzhhl.top/Article/details/gtlgwcfyqy.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigufen.top/Article/details/gtvsgrutus.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gtcyhzatse.html

[T11] Kotlin：协程
来源：http://dali.meibo888.top/Article/details/gttswcisjb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ydzc1.top/Article/details/gtoyxgmzey.html

[T12] Kotlin：解构声明
来源：http://dali.quarkkingdee.top/Article/details/gtgughzshy.html

val (a, b) = Pair(1, 2)
来源：http://dali.yvedp.cn/Article/details/gtavlytael.html

[T13] Kotlin：只读 Map
来源：http://dali.hysaishi.cn/Article/details/gtrwnvnmcw.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gtizlipiks.html

[T14] Kotlin：循环
来源：http://dali.yvedp.cn/Article/details/gtxjjmjbyr.html

for (i in 1..10) println(i)
来源：http://dali.havefunace.top/Article/details/gtvvrvizvb.html

[T15] Kotlin：接口
来源：http://dali.sysykeji.top/Article/details/gtnmgtfkix.html

interface Shape { fun area(): Double }
来源：http://dali.dianchejie.cn/Article/details/gtdklcrbms.html

[T16] Swift：Hello World
来源：http://dali.xylfe.cn/Article/details/gthzyweuky.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gtkldssans.html

[T17] Swift：变量与常量
来源：http://dali.yj202588.top/Article/details/gtfruwpoik.html

var a = 1;  let b = 2
来源：http://dali.zhongyouzk.top/Article/details/gtttqthkjm.html

[T18] Swift：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtzwkmxzga.html

"值: \(b)"
来源：http://dali.nanxuanxn.top/Article/details/gtnydkrlps.html

[T19] Swift：可选绑定
来源：http://dali.xylfe.cn/Article/details/gtkmmglruo.html

if let n = opt { print(n) }
来源：http://dali.xziqi.cn/Article/details/gtgagbhktp.html

[T20] Swift：数组操作
来源：http://dali.vqdsnc.cn/Article/details/gtkvluawuu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.pengpengdd.cyou/Article/details/gtjzyykfmt.html

[T21] Swift：遍历
来源：http://dali.yvedp.cn/Article/details/gtvuoxfrvf.html

for x in a { print(x) }
来源：http://dali.mhx1999.top/Article/details/gtuxwwnjzi.html

[T22] Swift：字典
来源：http://dali.zycfv.cn/Article/details/gtflltagbg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.birdmap.top/Article/details/gterpxjhwc.html

[T23] Swift：函数
来源：http://dali.zhengqikj.top/Article/details/gtzxvlmukt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258888.top/Article/details/gtoevkovnn.html

[T24] Swift：闭包
来源：http://dali.iojbl.cn/Article/details/gtfpdacnex.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangdashe.top/Article/details/gtxlfvwmqo.html

[T25] Swift：结构体
来源：http://dali.jinqigfzy.top/Article/details/gtrtznfutz.html

struct P { var x: Int }
来源：http://dali.yj20258.top/Article/details/gtnpcbdwbh.html

[T26] Swift：类与重写
来源：http://dali.9152youxi.cn/Article/details/gtwzyxibfx.html

class A: Base { override func f() {} }
来源：http://dali.9152youxi.cn/Article/details/gtfqnqmfum.html

[T27] Swift：错误处理
来源：http://dali.zdqjudy.top/Article/details/gtpynqdmzg.html

do { try f() } catch { print(error) }
来源：http://dali.sxryk.cn/Article/details/gtcpezkmki.html

[T28] Swift：枚举
来源：http://dali.ehwqpu.com/Article/details/gtaxsbrfzv.html

enum Color { case red, green }
来源：http://dali.tian-w.cn/Article/details/gtfqsxwssz.html

[T29] Swift：guard 提前返回
来源：http://dali.0kj1m.cn/Article/details/gtxsqqulyz.html

guard let x = opt else { return }
来源：http://dali.cheryme.top/Article/details/gtzykrmjwi.html

[T30] Swift：协议
来源：http://dali.jqgfzy.top/Article/details/gtfqeduods.html

protocol Shape { func area() -> Double }
来源：http://dali.ybcxt.top/Article/details/gtelnokxmg.html

[T31] Lua：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtzxntrxmu.html

print("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtbnfycwjr.html

[T32] Lua：局部变量
来源：http://dali.birdmap.top/Article/details/gtdujgilfl.html

local a = 1
来源：http://dali.dianchejie.cn/Article/details/gtpyykfphk.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhkxmpzv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xuetiantiany.cn/Article/details/gtzrjdwbom.html

[T34] Lua：遍历表
来源：http://dali.wangshuangyany.cn/Article/details/gthzostcpm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guowangkeji.top/Article/details/gtxfknvytd.html

[T35] Lua：字典表
来源：http://dali.svipenyu.cn/Article/details/gtgklfijbw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.smart0.xyz/Article/details/gtovhxnjvv.html

[T36] Lua：函数
来源：http://dali.hnxiangtu.top/Article/details/gtbebkpmve.html

function add(a, b) return a + b end
来源：http://dali.gogol.net.cn/Article/details/gttaoavpdl.html

[T37] Lua：字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gtzmxsnlxp.html

"a" .. "b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzqmapga.html

[T38] Lua：条件
来源：http://dali.yj20258888.top/Article/details/gttmykcqrx.html

if x > 0 then print("正") end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfhexpvo.html

[T39] Lua：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gtzyvpqkfq.html

string.find(s, "%d+")
来源：http://dali.cdnleiting.top/Article/details/gtmcjoqolz.html

[T40] Lua：元表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwksnzmsb.html

setmetatable({}, { __index = base })
来源：http://dali.kuanghao11.cn/Article/details/gtxpnicfni.html

[T41] Perl：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtfpklvmos.html

print "Hello\n";
来源：http://dali.yonumen.top/Article/details/gtuwjzsdbe.html

[T42] Perl：变量类型
来源：http://dali.hysaishi.cn/Article/details/gtqoljmzqw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.0kj1m.cn/Article/details/gtsvzsprrr.html

[T43] Perl：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtdvprqive.html

"值: $a"
来源：http://dali.quarkkingdee.top/Article/details/gtmimwrbtf.html

[T44] Perl：条件
来源：http://dali.redwolf501.top/Article/details/gtiabtqwly.html

if ($a > 0) { print "正"; }
来源：http://dali.fengsongda.top/Article/details/gtyqctxfpm.html

[T45] Perl：数组遍历
来源：http://dali.cheryme.top/Article/details/gttdjfnmfs.html

for my $x (@arr) { print $x; }
来源：http://dali.bjfxy.top/Article/details/gttevumqzp.html

[T46] Perl：哈希操作
来源：http://dali.shangyingyoupin.top/Article/details/gtiooorbgg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtpvebdyqe.html

[T47] Perl：正则捕获
来源：http://dali.haohaochexian.top/Article/details/gtofosbjvw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqxrsert.html

[T48] Perl：正则替换
来源：http://dali.yvedp.cn/Article/details/gtnwmkyyxe.html

$s =~ s/old/new/g;
来源：http://dali.316326.xyz/Article/details/gtmbrruukp.html

[T49] Perl：函数
来源：http://dali.xziqi.cn/Article/details/gtqjmvjjak.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtgihstnvk.html

[T50] Perl：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtdxjnzeto.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yanxiufei.cn/Article/details/gtuyeusmbd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenlongwang.top/Article/details/gtudosfmaw.html

[T51] Scala：Hello World
来源：http://dali.sweek.top/Article/details/gtupmvoktl.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuxtmxqf.html

[T52] Scala：变量
来源：http://dali.hongshengwenyu.top/Article/details/gtcpczwegd.html

val a = 1;  var b = 2
来源：http://dali.ppjwa.cn/Article/details/gteewzxagz.html

[T53] Scala：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtfotmezlw.html

s"值: $b"
来源：http://dali.guannengcc.top/Article/details/gtbjgjvqfr.html

[T54] Scala：集合映射
来源：http://dali.daria6918.cn/Article/details/gtfbblkhhs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.kuanghao11.cn/Article/details/gtfuswwdrp.html

[T55] Scala：集合过滤
来源：http://dali.redwolf501.top/Article/details/gtvyeieaba.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jyoumei.cn/Article/details/gtgcfqlyra.html

[T56] Scala：样例类
来源：http://dali.birdmap.top/Article/details/gtnzagdshn.html

case class User(name: String, age: Int)
来源：http://dali.pycfn.com/Article/details/gteqbncdvw.html

[T57] Scala：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gteeqjfugq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuanzx.com/Article/details/gtxslvapfm.html

[T58] Scala：函数定义
来源：http://dali.cdnleiting.top/Article/details/gtakmdnsid.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xziqi.cn/Article/details/gtcosydsvj.html

[T59] Scala：循环
来源：http://dali.quarkkingdee.top/Article/details/gtzjahjjco.html

for (i <- 1 to 10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gtvjxssjyt.html

[T60] Scala：折叠
来源：http://dali.chenlongwang.top/Article/details/gtzsnodynu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hongshengwenyu.top/Article/details/gtckylzgbk.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtsrpzrpop.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nwbrower.top/Article/details/gtetyewmlw.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtovuqigqs.html

[U01] Py：创建虚拟环境
来源：http://dali.yj20258.top/Article/details/gtiwwyfibu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yvedp.cn/Article/details/gtdlmxanli.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj202588.top/Article/details/gtxlwgyrxp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ppjwa.cn/Article/details/gtbqjgitrc.html

[U03] Py：加载 .env 配置
来源：http://dali.jyoumei.cn/Article/details/gtnbgkqnpl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.feifeiyinyue.top/Article/details/gtsrawrimm.html

[U04] Py：变量调试打印
来源：http://dali.chenjidiqi.icu/Article/details/gtaeloxnsy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nanxinkj.top/Article/details/gthrvgqxlr.html

[U05] Py：列表去重且保序
来源：http://dali.iojbl.cn/Article/details/gtwesegqja.html

list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gtpynremgf.html

[U06] Py：合并两个字典
来源：http://dali.iojbl.cn/Article/details/gtabzoreob.html

{**a, **b}
来源：http://dali.xuanzx.com/Article/details/gtqeuwafgm.html

[U07] Py：反转字典键值
来源：http://dali.hfpthk.cn/Article/details/gtrenkuawg.html

{v: k for k, v in d.items()}
来源：http://dali.jqgufenzy.top/Article/details/gtmzuzkeju.html

[U08] Py：展平二维列表
来源：http://dali.andypj.xyz/Article/details/gttmuamgfp.html

[y for x in nested for y in x]
来源：http://dali.gzhubu.top/Article/details/gtfaqmkhik.html

[U09] Py：字典取最大值的键
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnoeanit.html

max(d, key=d.get)
来源：http://dali.zhiwuduotai.top/Article/details/gtamhqvshr.html

[U10] Py：按值排序字典
来源：http://dali.sysykeji.top/Article/details/gtrksrsrij.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.birdmap.top/Article/details/gtmylstsuf.html

[U11] Py：生成器表达式
来源：http://dali.ivvv.top/Article/details/gtbukhgrtd.html

(x * 2 for x in arr)
来源：http://dali.hammf.cn/Article/details/gtlxhsectu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jlsjyb.cn/Article/details/gtoxpsniix.html

Counter(arr).most_common(3)
来源：http://dali.ybcxt.top/Article/details/gtowbvjcpp.html

[U13] Py：固定长度队列
来源：http://dali.bjfxy.top/Article/details/gtfwrmxivg.html

deque(maxlen=10)
来源：http://dali.havefunace.top/Article/details/gththaoykw.html

[U14] Py：分组收集到列表
来源：http://dali.dashuyun.cn/Article/details/gteblltrrt.html

defaultdict(list)
来源：http://dali.iojbl.cn/Article/details/gtqbaxtxve.html

[U15] Py：高精度计时
来源：http://dali.gogol.net.cn/Article/details/gtzgxruidm.html

t = time.perf_counter()
来源：http://dali.pengpengdd.cyou/Article/details/gtihgfgzis.html

[U16] Py：命令行参数解析
来源：http://dali.shuidangran.top/Article/details/gtdchftnzf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cdnleiting.top/Article/details/gtvzdflbjq.html

[U17] Py：初始化日志
来源：http://dali.shzxlz.cn/Article/details/gtvzupmfkn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.fzhhl.top/Article/details/gtaybpsnla.html

[U18] Py：预编译正则
来源：http://dali.snrcjt.cn/Article/details/gtuirhaenx.html

pat = re.compile(r"\d+")
来源：http://dali.xziqi.cn/Article/details/gtbqtedamk.html

[U19] Py：正则替换带回调
来源：http://dali.jlsjyb.cn/Article/details/gtajehogwj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.smart0.xyz/Article/details/gtairsiopc.html

[U20] Py：缓存函数结果
来源：http://dali.ybcxt.top/Article/details/gtfcugohuh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cucudq.cn/Article/details/gtvcfuddqw.html

[U21] Py：自定义上下文管理器
来源：http://dali.vqdsnc.cn/Article/details/gtczfqffim.html

@contextlib.contextmanager
来源：http://dali.nwbrower.top/Article/details/gtcpkxbgra.html

[U22] Py：矩阵转置
来源：http://dali.hammf.cn/Article/details/gtqvlgciwf.html

list(zip(*m))
来源：http://dali.feifeiyinyue.top/Article/details/gtcqnyvrqj.html

[U23] Py：分块读取大文件
来源：http://dali.cdnleiting.top/Article/details/gtmnmexrao.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnpcticd.html

[U24] Py：路径操作
来源：http://dali.0kj1m.cn/Article/details/gtkzcbbnla.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhixingplan.top/Article/details/gtllbdldgt.html

[U25] Py：CSV 按字典读
来源：http://dali.shangyingyoupin.top/Article/details/gtwbctzzyq.html

csv.DictReader(f)
来源：http://dali.hysaishi.cn/Article/details/gtfilfnxvt.html

[U26] Py：并发下载
来源：http://dali.yanxiufei.cn/Article/details/gtmsbhpgrf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cqqwz.cn/Article/details/gtwkitdukf.html

[U27] Py：异步 HTTP
来源：http://dali.fzhhl.top/Article/details/gtehvdwhre.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigiszfqt.html

[U28] Py：类型别名
来源：http://dali.sysykeji.top/Article/details/gtunusunkh.html

UserId = int
来源：http://dali.yanxiufei.cn/Article/details/gtwuytrzog.html

[U29] Py：属性校验
来源：http://dali.daria6918.cn/Article/details/gttpmhtwjt.html

@property 与 @x.setter 配合
来源：http://dali.ivvv.top/Article/details/gtqiktvfmy.html

[U30] Py：数据类
来源：http://dali.aibaodan.cn/Article/details/gthwhmhjeo.html

@dataclass(slots=True)
来源：http://dali.chenlongwang.top/Article/details/gtwyhdukhg.html

[U31] Py：单测
来源：http://dali.zhengqikj.top/Article/details/gtoyjxjsxy.html

python -m pytest -q
来源：http://dali.316326.xyz/Article/details/gtcgqmgysx.html

[U32] Py：代码格式化
来源：http://dali.xinyue.icu/Article/details/gtyoosrtfr.html

ruff format . && ruff check --fix .
来源：http://dali.feifeiyinyue.top/Article/details/gtfqvecizq.html

[U33] Py：打包发布
来源：http://dali.yj20258888.top/Article/details/gtjjkmszsz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sufxvd.cn/Article/details/gtyudbmgfl.html

[U34] Py：判断编码
来源：http://dali.haohaochexian.top/Article/details/gtcgfdrplw.html

chardet.detect(raw)
来源：http://dali.jqgufenzy.top/Article/details/gtmjbinhui.html

[U35] Py：发送邮件
来源：http://dali.316326.xyz/Article/details/gttdlhubjk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhiwuduotai.top/Article/details/gtjkaiqmzs.html

[U36] Py：定时任务
来源：http://dali.jlsjyb.cn/Article/details/gtqfceqjwq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhengqikj.top/Article/details/gtytvfuhxe.html

[U37] Py：读写 Excel
来源：http://dali.chenjidiqi.icu/Article/details/gtoihizyau.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cashguo.top/Article/details/gtrlhzyyiv.html

[U38] Py：获取脚本所在目录
来源：http://dali.hywenlv.cn/Article/details/gtlotifbuj.html

Path(__file__).resolve().parent
来源：http://dali.cheryme.top/Article/details/gtviecisvy.html

[U39] Py：判断是否在交互环境
来源：http://dali.jyoumei.cn/Article/details/gtupjchmmk.html

sys.stdout.isatty()
来源：http://dali.zhiwuduotai.top/Article/details/gtycmhzypj.html

[U40] Py：打印到标准错误
来源：http://dali.kuanghao11.cn/Article/details/gtrchxavsd.html

print("err", file=sys.stderr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrgqudje.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenlongwang.top/Article/details/gtsrbeiqek.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhongyouzk.top/Article/details/gtrthltrwq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhongyouzk.top/Article/details/gtrolwhukb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.gaohongyu789.top/Article/details/gtqztjplqc.html

[U43] PHP：声明命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gtrpwgkzgs.html

namespace App\Http;
来源：http://dali.gotoacloud.top/Article/details/gtglehzmow.html

[U44] PHP：开启严格类型
来源：http://dali.sxryk.cn/Article/details/gtwlifmzdj.html

declare(strict_types=1);
来源：http://dali.daxiang520.top/Article/details/gtraqecpee.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jlsjyb.cn/Article/details/gtabzkafxj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtsrhpzzdy.html

[U46] PHP：可空类型
来源：http://dali.fengsongda.top/Article/details/gtkkdioqmm.html

?string $name = null
来源：http://dali.daria6918.cn/Article/details/gtifgyoikx.html

[U47] PHP：联合类型
来源：http://dali.cqqwz.cn/Article/details/gtwudsoldj.html

int|string $id
来源：http://dali.sxryk.cn/Article/details/gteadapbdj.html

[U48] PHP：纯枚举
来源：http://dali.jlsjyb.cn/Article/details/gtmtlybnny.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenlongwang.top/Article/details/gtxaqvdbgp.html


<!-- 参考信息 -->