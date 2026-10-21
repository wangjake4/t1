代发 wailian999

#ifndef X_H
来源：http://dali.xuanzx.com/Article/details/gtcvvfvgus.html

#define X_H
来源：http://dali.chenlongwang.top/Article/details/gtccsihliq.html

#endif
来源：http://dali.jiagoushi.top/Article/details/gtjyussppe.html

[S31] C++：Hello World
来源：http://dali.yuxming.cn/Article/details/gtnlfubcwp.html

#include <iostream>
来源：http://dali.vqdsnc.cn/Article/details/gtchfimkcx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ehwqpu.com/Article/details/gtwsifoxai.html

[S32] C++：字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtdppgtads.html

std::string s = "hi";  s += "!";
来源：http://dali.ivvv.top/Article/details/gtemnmvkzt.html

[S33] C++：vector 增删
来源：http://dali.hfpthk.cn/Article/details/gtucfdfszp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daxiang520.top/Article/details/gtenzsonvu.html

[S34] C++：遍历 vector
来源：http://dali.jinghuilouyu.cn/Article/details/gtldnhytao.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenlongwang.top/Article/details/gtebctwvul.html

[S35] C++：map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucsquhgf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gtlcqryopj.html

[S36] C++：unordered_map
来源：http://dali.sxryk.cn/Article/details/gtjlqdtzpp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtmgffxwju.html

[S37] C++：set
来源：http://dali.fzhhl.top/Article/details/gtwdrrztkd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxuanxn.top/Article/details/gttovhuxwn.html

[S38] C++：排序
来源：http://dali.shzxlz.cn/Article/details/gtdpqeqzux.html

std::sort(v.begin(), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gtagevwmus.html

[S39] C++：自定义比较器排序
来源：http://dali.shzxlz.cn/Article/details/gteziiyide.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shuidangran.top/Article/details/gtkexiosyk.html

[S40] C++：查找元素
来源：http://dali.9152youxi.cn/Article/details/gtytrzzdck.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.havefunace.top/Article/details/gtzcylouip.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwteylkg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhixingplan.top/Article/details/gtxoubimfe.html

[S42] C++：继承与虚函数
来源：http://dali.xziqi.cn/Article/details/gtsbogqyun.html

class B : public Base { public: void f() override {} };
来源：http://dali.cucudq.cn/Article/details/gtxzhhxofy.html

[S43] C++：智能指针
来源：http://dali.jinqigfzy.top/Article/details/gtsoixusue.html

auto p = std::make_unique<int>(5);
来源：http://dali.cqqwz.cn/Article/details/gtgvgtzrne.html

[S44] C++：引用传参
来源：http://dali.xziqi.cn/Article/details/gtvpibkhbo.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gtbgaimdas.html

[S45] C++：lambda
来源：http://dali.9152youxi.cn/Article/details/gtnmaglyix.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cucudq.cn/Article/details/gtrvyqpqzj.html

[S46] C++：函数模板
来源：http://dali.chenzaomai.com/Article/details/gtbwdupdsd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jlsjyb.cn/Article/details/gtbhopvpbw.html

[S47] C++：结构化绑定遍历
来源：http://dali.yonumen.top/Article/details/gtwsigbtcr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj202588.top/Article/details/gtjnklctki.html

[S48] C++：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtfcxtzyfl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258.top/Article/details/gtdgatxsqk.html

while (std::getline(in, line)) { }
来源：http://dali.chenlongwang.top/Article/details/gtxqflzgfb.html

[S49] C++：写文件
来源：http://dali.jinqigufen.top/Article/details/gtlvgjdqty.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.vqdsnc.cn/Article/details/gttjhhyrom.html

[S50] C++：格式化数字
来源：http://dali.jyoumei.cn/Article/details/gthzxvmtjh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtlkbtaoss.html

[S51] C++：显式类型转换
来源：http://dali.guannengcc.top/Article/details/gtrumwstej.html

static_cast<double>(a) / b
来源：http://dali.cdnleiting.top/Article/details/gtvidmfeca.html

[S52] C++：const 与 noexcept
来源：http://dali.aizwys.cn/Article/details/gtbsvailvt.html

int size() const noexcept { return n_; }
来源：http://dali.ppjwa.cn/Article/details/gtccrxoqmj.html

[S53] C++：移动语义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmtmaico.html

std::vector<int> w = std::move(v);
来源：http://dali.hywenlv.cn/Article/details/gthfhewaxg.html

[S54] C++：异常处理
来源：http://dali.0kj1m.cn/Article/details/gtkfxmsjct.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.havefunace.top/Article/details/gtwjwnnoup.html

[S55] C++：结构化绑定
来源：http://dali.guannengcc.top/Article/details/gthoqlktqp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtrvtqbexz.html

[S56] C++：optional
来源：http://dali.sxryk.cn/Article/details/gthgsaerpd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ivvv.top/Article/details/gtydcozwfo.html

[S57] C++：编译期常量
来源：http://dali.tianlin.xyz/Article/details/gtrczscztj.html

constexpr int N = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtdgevtkuh.html

[S58] C++：命名空间
来源：http://dali.yuxming.cn/Article/details/gttnswyogn.html

namespace ns { int f() { return 1; } }
来源：http://dali.redwolf501.top/Article/details/gtoakycwun.html

[S59] C++：静态断言
来源：http://dali.cheryme.top/Article/details/gtspiwschq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sweek.top/Article/details/gtmjdgiaeg.html

[S60] C++：遍历并删除元素
来源：http://dali.nwbrower.top/Article/details/gtdpalccwx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hammf.cn/Article/details/gtvoqcbpfy.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtrheqmpin.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gttqolllze.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtfrdsdijs.html

[T01] Kotlin：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtxyctdfmi.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gtjegtcbba.html

[T02] Kotlin：变量
来源：http://dali.wangdashe.top/Article/details/gttsoiewir.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.0kj1m.cn/Article/details/gttwzcmiuz.html

[T03] Kotlin：字符串模板
来源：http://dali.yvedp.cn/Article/details/gtvasdhvxz.html

"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gteeridafk.html

[T04] Kotlin：空安全
来源：http://dali.gzhubu.top/Article/details/gtegohaivt.html

val n: String? = null;  n?.length
来源：http://dali.nanxuanxn.top/Article/details/gtujiotdix.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigufen.top/Article/details/gtnindaont.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.aizwys.cn/Article/details/gtnssjiaxp.html

[T06] Kotlin：集合映射
来源：http://dali.fzhhl.top/Article/details/gtvdraycqk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ivvv.top/Article/details/gtslkvfokg.html

[T07] Kotlin：集合过滤
来源：http://dali.haohaochexian.top/Article/details/gtjdualzvp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenzaomai.com/Article/details/gtncqfgjuf.html

[T08] Kotlin：数据类
来源：http://dali.jyoumei.cn/Article/details/gtkjqbbnjp.html

data class User(val name: String, val age: Int)
来源：http://dali.shzxlz.cn/Article/details/gtoixzggew.html

[T09] Kotlin：扩展函数
来源：http://dali.fengsongda.top/Article/details/gteujulsjp.html

fun String.exclaim() = this + "!"
来源：http://dali.hnxiangtu.top/Article/details/gtdntdajwp.html

[T10] Kotlin：默认参数
来源：http://dali.gaohongyu789.top/Article/details/gtbtglejut.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xziqi.cn/Article/details/gtbctdaqsk.html

[T11] Kotlin：协程
来源：http://dali.sxryk.cn/Article/details/gtqpehipgt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yanxiufei.cn/Article/details/gtqcbhmdnk.html

[T12] Kotlin：解构声明
来源：http://dali.zhongyouzk.top/Article/details/gtulaivyvp.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtyhwgpsek.html

[T13] Kotlin：只读 Map
来源：http://dali.yanxiufei.cn/Article/details/gtawfxbfgo.html

val m = mapOf("a" to 1)
来源：http://dali.hysaishi.cn/Article/details/gtorfycvbv.html

[T14] Kotlin：循环
来源：http://dali.9152youxi.cn/Article/details/gtntadboxc.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdeeuobg.html

[T15] Kotlin：接口
来源：http://dali.cheryme.top/Article/details/gttgwdfurn.html

interface Shape { fun area(): Double }
来源：http://dali.cashguo.top/Article/details/gtxodlhwek.html

[T16] Swift：Hello World
来源：http://dali.xuanzx.com/Article/details/gtxnfxdpij.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtyepyseht.html

[T17] Swift：变量与常量
来源：http://dali.svipenyu.cn/Article/details/gtebdppjrq.html

var a = 1;  let b = 2
来源：http://dali.haohaochexian.top/Article/details/gtbdbusgve.html

[T18] Swift：字符串插值
来源：http://dali.redwolf501.top/Article/details/gteuqhxnej.html

"值: \(b)"
来源：http://dali.cqqwz.cn/Article/details/gtmfwcgygx.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmoafncn.html

if let n = opt { print(n) }
来源：http://dali.yueranfly.top/Article/details/gtwtnnynwy.html

[T20] Swift：数组操作
来源：http://dali.jyoumei.cn/Article/details/gtcywgwwal.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yonumen.top/Article/details/gthymobmgq.html

[T21] Swift：遍历
来源：http://dali.zhongyouzk.top/Article/details/gtxqjshsky.html

for x in a { print(x) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcjsipnz.html

[T22] Swift：字典
来源：http://dali.chenlongwang.top/Article/details/gtnlxntqll.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fzhhl.top/Article/details/gteuudxjsz.html

[T23] Swift：函数
来源：http://dali.sweek.top/Article/details/gtwtexyesj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtvvlmqwuf.html

[T24] Swift：闭包
来源：http://dali.aizwys.cn/Article/details/gtywhnlwxm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtlqkoehtl.html

[T25] Swift：结构体
来源：http://dali.nanxuanxn.top/Article/details/gtfslcjlaa.html

struct P { var x: Int }
来源：http://dali.xuetiantiany.cn/Article/details/gtlddikayi.html

[T26] Swift：类与重写
来源：http://dali.quarkkingdee.top/Article/details/gtlthkuqdh.html

class A: Base { override func f() {} }
来源：http://dali.jlsjyb.cn/Article/details/gtesrhfsht.html

[T27] Swift：错误处理
来源：http://dali.zhoulong.xyz/Article/details/gtlwxkfdek.html

do { try f() } catch { print(error) }
来源：http://dali.hammf.cn/Article/details/gtfjhwgzre.html

[T28] Swift：枚举
来源：http://dali.xziqi.cn/Article/details/gtubztyhmo.html

enum Color { case red, green }
来源：http://dali.yonumen.top/Article/details/gtmgnuwipa.html

[T29] Swift：guard 提前返回
来源：http://dali.jiagoushi.top/Article/details/gtjzcbyled.html

guard let x = opt else { return }
来源：http://dali.yvedp.cn/Article/details/gtaxwsjexe.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gtrpacxzfi.html

protocol Shape { func area() -> Double }
来源：http://dali.feifeiyinyue.top/Article/details/gtrmkvdzsp.html

[T31] Lua：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtzkxtgswm.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gttxoybewh.html

[T32] Lua：局部变量
来源：http://dali.guowangkeji.top/Article/details/gtrpzfjoxn.html

local a = 1
来源：http://dali.daxiang520.top/Article/details/gtozgpipap.html

[T33] Lua：表（数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdhdazju.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jyoumei.cn/Article/details/gtvhlpqasp.html

[T34] Lua：遍历表
来源：http://dali.feifeiyinyue.top/Article/details/gtyfqluqpw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guannengcc.top/Article/details/gtgxjckedj.html

[T35] Lua：字典表
来源：http://dali.yongpay.top/Article/details/gtctjlvydu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.smart0.xyz/Article/details/gtnalmkrxp.html

[T36] Lua：函数
来源：http://dali.yj202588.top/Article/details/gtfewucjpv.html

function add(a, b) return a + b end
来源：http://dali.gzhubu.top/Article/details/gtxdwicpje.html

[T37] Lua：字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gtxgpfydye.html

"a" .. "b"
来源：http://dali.guowangkeji.top/Article/details/gtjmmzmmwy.html

[T38] Lua：条件
来源：http://dali.hywenlv.cn/Article/details/gtuouejlgr.html

if x > 0 then print("正") end
来源：http://dali.xylfe.cn/Article/details/gtikyddcob.html

[T39] Lua：模式匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzkqrgxm.html

string.find(s, "%d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgaagnaw.html

[T40] Lua：元表
来源：http://dali.xziqi.cn/Article/details/gtaqsjnezu.html

setmetatable({}, { __index = base })
来源：http://dali.gzhubu.top/Article/details/gtajovqzjq.html

[T41] Perl：Hello World
来源：http://dali.cashguo.top/Article/details/gttushqeex.html

print "Hello\n";
来源：http://dali.wangshuangyany.cn/Article/details/gtutoxbxkf.html

[T42] Perl：变量类型
来源：http://dali.jinqigufen.top/Article/details/gtembpkyhf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ydzc1.top/Article/details/gtvfhtxjsp.html

[T43] Perl：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtasifwxls.html

"值: $a"
来源：http://dali.ehwqpu.com/Article/details/gtxijhudun.html

[T44] Perl：条件
来源：http://dali.yuxming.cn/Article/details/gtonnqrfxl.html

if ($a > 0) { print "正"; }
来源：http://dali.daxiang520.top/Article/details/gtlalvomkh.html

[T45] Perl：数组遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtsgzfgxxx.html

for my $x (@arr) { print $x; }
来源：http://dali.cheryme.top/Article/details/gtdjgksyxa.html

[T46] Perl：哈希操作
来源：http://dali.bjfxy.top/Article/details/gtpaqfvnna.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cashguo.top/Article/details/gtaawlxxfz.html

[T47] Perl：正则捕获
来源：http://dali.meibo888.top/Article/details/gtxbqpsyfa.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yuxming.cn/Article/details/gtzkdmefiz.html

[T48] Perl：正则替换
来源：http://dali.chenzaomai.com/Article/details/gtaznzyjtx.html

$s =~ s/old/new/g;
来源：http://dali.nanxuanxn.top/Article/details/gtspebcbys.html

[T49] Perl：函数
来源：http://dali.fzhhl.top/Article/details/gtmtxpylbs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkwolerqk.html

[T50] Perl：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gthefqakzx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuanzhike.top/Article/details/gtbqssmngi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.daria6918.cn/Article/details/gthgxgtaek.html

[T51] Scala：Hello World
来源：http://dali.cucudq.cn/Article/details/gtwobgazdt.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtcvwfqdxq.html

[T52] Scala：变量
来源：http://dali.zhoulong.xyz/Article/details/gttegvwyda.html

val a = 1;  var b = 2
来源：http://dali.birdmap.top/Article/details/gthsuzwtng.html

[T53] Scala：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtlsyidmpf.html

s"值: $b"
来源：http://dali.iojbl.cn/Article/details/gtpwhxcmly.html

[T54] Scala：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gtotepdlma.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.fengsongda.top/Article/details/gtlaqpyoes.html

[T55] Scala：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gtosakhvrx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.quarkkingdee.top/Article/details/gtmtpifzhc.html

[T56] Scala：样例类
来源：http://dali.xuetiantiany.cn/Article/details/gthugwmokz.html

case class User(name: String, age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gtkhxwpboa.html

[T57] Scala：模式匹配
来源：http://dali.nanxuanxn.top/Article/details/gtonmedalc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jyoumei.cn/Article/details/gtpykhkpmo.html

[T58] Scala：函数定义
来源：http://dali.havefunace.top/Article/details/gtnpermyrv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.wangshuangyany.cn/Article/details/gtfeyfwsaf.html

[T59] Scala：循环
来源：http://dali.yonumen.top/Article/details/gteegqvoug.html

for (i <- 1 to 10) println(i)
来源：http://dali.cucudq.cn/Article/details/gtmtavzfro.html

[T60] Scala：折叠
来源：http://dali.hnqzz.top/Article/details/gtnfsygrrz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sxryk.cn/Article/details/gtuytmexdp.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtnhwnneon.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yonumen.top/Article/details/gtmqwdnhrt.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtkqighhdp.html

[U01] Py：创建虚拟环境
来源：http://dali.meibo888.top/Article/details/gtabfnfyrf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangdashe.top/Article/details/gtmsrupovw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hfpthk.cn/Article/details/gtvgluwuxp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cashguo.top/Article/details/gtfeuuqgfj.html

[U03] Py：加载 .env 配置
来源：http://dali.cheryme.top/Article/details/gtjzngnhmp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwafaxhiw.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuezaqdow.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.0kj1m.cn/Article/details/gtyzbauwme.html

[U05] Py：列表去重且保序
来源：http://dali.yj20258888.top/Article/details/gttddvcvel.html

list(dict.fromkeys(arr))
来源：http://dali.chenlongwang.top/Article/details/gtftoevpsq.html

[U06] Py：合并两个字典
来源：http://dali.0kj1m.cn/Article/details/gtxqnlhsmg.html

{**a, **b}
来源：http://dali.pycfn.com/Article/details/gtqquabhev.html

[U07] Py：反转字典键值
来源：http://dali.yj20258888.top/Article/details/gtttwaqmvo.html

{v: k for k, v in d.items()}
来源：http://dali.yueranfly.top/Article/details/gtzdfpmfeu.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhytwyxg.html

[y for x in nested for y in x]
来源：http://dali.yangfankeji.com/Article/details/gtvawktktl.html

[U09] Py：字典取最大值的键
来源：http://dali.yongpay.top/Article/details/gtqnhrifrg.html

max(d, key=d.get)
来源：http://dali.tian-w.cn/Article/details/gtpmihmxmu.html

[U10] Py：按值排序字典
来源：http://dali.hywenlv.cn/Article/details/gtqurkgraz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jianghu66.top/Article/details/gtkmgvibne.html

[U11] Py：生成器表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtpwczpsih.html

(x * 2 for x in arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtqyqsrjpl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.guannengcc.top/Article/details/gtuqgwujmo.html

Counter(arr).most_common(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtpkbitnnh.html

[U13] Py：固定长度队列
来源：http://dali.nwbrower.top/Article/details/gtogvisoih.html

deque(maxlen=10)
来源：http://dali.quarkkingdee.top/Article/details/gtdkvntwgx.html

[U14] Py：分组收集到列表
来源：http://dali.zhiwuduotai.top/Article/details/gttdklnbfy.html

defaultdict(list)
来源：http://dali.9152youxi.cn/Article/details/gtfksdjqfz.html

[U15] Py：高精度计时
来源：http://dali.yj202588.top/Article/details/gtzfebbnzv.html

t = time.perf_counter()
来源：http://dali.shangyingyoupin.top/Article/details/gtmirmmxqn.html

[U16] Py：命令行参数解析
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdktsctrt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cdnleiting.top/Article/details/gtehnlqojz.html

[U17] Py：初始化日志
来源：http://dali.daxiang520.top/Article/details/gtinchxvjg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.haohaochexian.top/Article/details/gtidfpaozd.html

[U18] Py：预编译正则
来源：http://dali.bjfxy.top/Article/details/gtpxwbdcpe.html

pat = re.compile(r"\d+")
来源：http://dali.fzhhl.top/Article/details/gtaigidkvq.html

[U19] Py：正则替换带回调
来源：http://dali.yj20258.top/Article/details/gttwhzbvsg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.andypj.xyz/Article/details/gtsikrvtlq.html

[U20] Py：缓存函数结果
来源：http://dali.feifeiyinyue.top/Article/details/gtmtdpeekz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj202588.top/Article/details/gtyolanvtk.html

[U21] Py：自定义上下文管理器
来源：http://dali.tianlin.xyz/Article/details/gtliqlnkqz.html

@contextlib.contextmanager
来源：http://dali.zhiwuduotai.top/Article/details/gtliainiuo.html

[U22] Py：矩阵转置
来源：http://dali.zycfv.cn/Article/details/gtbdlshhyg.html

list(zip(*m))
来源：http://dali.zhongyouzk.top/Article/details/gtheehmcfr.html

[U23] Py：分块读取大文件
来源：http://dali.yvedp.cn/Article/details/gttpzpjibd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenlongwang.top/Article/details/gtowesnlqy.html

[U24] Py：路径操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtloshsfea.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cucudq.cn/Article/details/gtqbocakxk.html

[U25] Py：CSV 按字典读
来源：http://dali.gotoacloud.top/Article/details/gtfvrghuvy.html

csv.DictReader(f)
来源：http://dali.0kj1m.cn/Article/details/gtnzphbrzf.html

[U26] Py：并发下载
来源：http://dali.smart0.xyz/Article/details/gtpcrlyvsg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yj20258888.top/Article/details/gtwqwrjajy.html

[U27] Py：异步 HTTP
来源：http://dali.ydzc1.top/Article/details/gtyeybleqz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.bjfxy.top/Article/details/gthwldldxu.html

[U28] Py：类型别名
来源：http://dali.svipenyu.cn/Article/details/gtczwfvzot.html

UserId = int
来源：http://dali.jinqigfzy.top/Article/details/gtssxrhsal.html

[U29] Py：属性校验
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmlpznqj.html

@property 与 @x.setter 配合
来源：http://dali.andypj.xyz/Article/details/gtqrexrhts.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gtunsnfouh.html

@dataclass(slots=True)
来源：http://dali.bjfxy.top/Article/details/gtehboazbi.html

[U31] Py：单测
来源：http://dali.snrcjt.cn/Article/details/gtyhvxicux.html

python -m pytest -q
来源：http://dali.jianghu66.top/Article/details/gtsdnflouz.html

[U32] Py：代码格式化
来源：http://dali.dianchejie.cn/Article/details/gtsjimkfay.html

ruff format . && ruff check --fix .
来源：http://dali.yj202588.top/Article/details/gtllgezyyg.html

[U33] Py：打包发布
来源：http://dali.iojbl.cn/Article/details/gtkwawixjj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenjidiqi.icu/Article/details/gtqndouwwh.html

[U34] Py：判断编码
来源：http://dali.zhoulong.xyz/Article/details/gtohxxqyop.html

chardet.detect(raw)
来源：http://dali.guannengcc.top/Article/details/gtksyishfq.html

[U35] Py：发送邮件
来源：http://dali.shanyushiyangtech.top/Article/details/gtofppnvzs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinqigufen.top/Article/details/gtasnntlte.html

[U36] Py：定时任务
来源：http://dali.cqqwz.cn/Article/details/gttxxpajsx.html

schedule.every(10).minutes.do(job)
来源：http://dali.cucudq.cn/Article/details/gtxecopaak.html

[U37] Py：读写 Excel
来源：http://dali.0kj1m.cn/Article/details/gtyhemfzpa.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.pycfn.com/Article/details/gtgwqcxkbd.html

[U38] Py：获取脚本所在目录
来源：http://dali.svipenyu.cn/Article/details/gthyjoxzja.html

Path(__file__).resolve().parent
来源：http://dali.zdqjudy.top/Article/details/gtoutqukcb.html

[U39] Py：判断是否在交互环境
来源：http://dali.hywenlv.cn/Article/details/gtjcqnppbv.html

sys.stdout.isatty()
来源：http://dali.svipenyu.cn/Article/details/gtzbqcnpzh.html

[U40] Py：打印到标准错误
来源：http://dali.yangfankeji.com/Article/details/gtxkuasfby.html

print("err", file=sys.stderr)
来源：http://dali.jinqigfzy.top/Article/details/gtwqyajhkr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.dashuyun.cn/Article/details/gtmbeswmne.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgymugefu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sxryk.cn/Article/details/gtaamrceby.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavqcctmr.html

[U43] PHP：声明命名空间
来源：http://dali.shzxlz.cn/Article/details/gtytzwqscl.html

namespace App\Http;
来源：http://dali.cucudq.cn/Article/details/gtamsuvcwl.html

[U44] PHP：开启严格类型
来源：http://dali.ydzc1.top/Article/details/gtxtkpkdwc.html

declare(strict_types=1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxjvncua.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cheryme.top/Article/details/gtyihnkseq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnlpwqzjd.html

[U46] PHP：可空类型
来源：http://dali.jinqigufen.top/Article/details/gtmfwvxefj.html

?string $name = null
来源：http://dali.0kj1m.cn/Article/details/gtcebrziqe.html

[U47] PHP：联合类型
来源：http://dali.quarkkingdee.top/Article/details/gtwvleyndj.html

int|string $id
来源：http://dali.xuetiantiany.cn/Article/details/gtwbfeczgv.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gtgkqvmmur.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hammf.cn/Article/details/gtjigtljhu.html

[U49] PHP：只读属性
来源：http://dali.vqdsnc.cn/Article/details/gtvoablrfm.html

public readonly string $name
来源：http://dali.hywenlv.cn/Article/details/gtqxmzmlfs.html

[U50] PHP：构造器属性提升
来源：http://dali.aibaodan.cn/Article/details/gtrtbsektg.html

public function __construct(private int $id) {}
来源：http://dali.0kj1m.cn/Article/details/gtutoiliwi.html

[U51] PHP：数组解构
来源：http://dali.aizwys.cn/Article/details/gtvictqkaf.html

[$a, $b] = $arr;
来源：http://dali.yuxming.cn/Article/details/gttttqefob.html

[U52] PHP：箭头函数
来源：http://dali.xziqi.cn/Article/details/gtunkihwvh.html

$double = fn($x) => $x * 2;
来源：http://dali.0kj1m.cn/Article/details/gtezibrzkx.html

[U53] PHP：空合并运算符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwkxnxgi.html

$v = $a ?? $b ?? "default";
来源：http://dali.tanke756.top/Article/details/gtzicmtdjv.html

[U54] PHP：空安全调用
来源：http://dali.bjfxy.top/Article/details/gtrsfmmlro.html

$obj?->method()
来源：http://dali.tian-w.cn/Article/details/gtpwnfrrpq.html


<!-- 参考信息 -->