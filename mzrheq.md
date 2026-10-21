代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ppjwa.cn/Article/details/gtzudhebqg.html

[S23] C：随机数
来源：http://dali.daxiang520.top/Article/details/gtuvgkeoes.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yongpay.top/Article/details/gtwigwasrx.html

[S24] C：获取本地时间
来源：http://dali.ybcxt.top/Article/details/gtqvebdqig.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.snrcjt.cn/Article/details/gttjjwbhbi.html

[S25] C：内存拷贝
来源：http://dali.cdnleiting.top/Article/details/gtwdqccndz.html

memcpy(dst, src, n);
来源：http://dali.xuanzx.com/Article/details/gtffhvzsby.html

[S26] C：内存清零
来源：http://dali.cqqwz.cn/Article/details/gtlzjamfat.html

memset(a, 0, sizeof a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfwyqpdx.html

[S27] C：定义常量
来源：http://dali.yongpay.top/Article/details/gtuqbazuxr.html

const double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gttbkvovhk.html

[S28] C：静态变量
来源：http://dali.xylfe.cn/Article/details/gtgvyehcrq.html

static int counter = 0;
来源：http://dali.cdnleiting.top/Article/details/gtvwycbnzh.html

[S29] C：变参函数
来源：http://dali.daria6918.cn/Article/details/gtyeoxydhm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tianlin.xyz/Article/details/gttwkxcvir.html

[S30] C：头文件保护
来源：http://dali.gotoacloud.top/Article/details/gtyiexddha.html

#ifndef X_H
来源：http://dali.vqdsnc.cn/Article/details/gtjhuknerv.html

#define X_H
来源：http://dali.zhengqikj.top/Article/details/gtlaxwpqfy.html

#endif
来源：http://dali.dashuyun.cn/Article/details/gtuekenxap.html

[S31] C++：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgppxmckj.html

#include <iostream>
来源：http://dali.guowangkeji.top/Article/details/gtnvqqrioi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daxiang520.top/Article/details/gtpiitnlsp.html

[S32] C++：字符串
来源：http://dali.316326.xyz/Article/details/gtvzivevqw.html

std::string s = "hi";  s += "!";
来源：http://dali.sufxvd.cn/Article/details/gtlfxvgphm.html

[S33] C++：vector 增删
来源：http://dali.wangdashe.top/Article/details/gtbhuwenkl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj202588.top/Article/details/gtznbohrnv.html

[S34] C++：遍历 vector
来源：http://dali.zhoulong.xyz/Article/details/gthjcxpklq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcoxjjyvn.html

[S35] C++：map
来源：http://dali.aizwys.cn/Article/details/gtmzcxpmal.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gtmylpkumm.html

[S36] C++：unordered_map
来源：http://dali.fzhhl.top/Article/details/gtunmccnih.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtdidrbumo.html

[S37] C++：set
来源：http://dali.yanxiufei.cn/Article/details/gtqxzusrif.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.snrcjt.cn/Article/details/gtgsvblxww.html

[S38] C++：排序
来源：http://dali.hysaishi.cn/Article/details/gtpdmkeyqm.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gthtmzlies.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgufenzy.top/Article/details/gtnejtofqp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.vqdsnc.cn/Article/details/gtatnpphqm.html

[S40] C++：查找元素
来源：http://dali.cucudq.cn/Article/details/gtooadcump.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangdashe.top/Article/details/gtjkknhjxy.html

[S41] C++：类与构造函数
来源：http://dali.zdqjudy.top/Article/details/gtmkvuqvpb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nwbrower.top/Article/details/gtjjavzaeo.html

[S42] C++：继承与虚函数
来源：http://dali.chenlongwang.top/Article/details/gtrtoaybqs.html

class B : public Base { public: void f() override {} };
来源：http://dali.shzxlz.cn/Article/details/gtmrkgmcpy.html

[S43] C++：智能指针
来源：http://dali.ehwqpu.com/Article/details/gtaazwgyfb.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhiwuduotai.top/Article/details/gtekdoxpxm.html

[S44] C++：引用传参
来源：http://dali.sxryk.cn/Article/details/gtenfdoutf.html

void inc(int &x) { ++x; }
来源：http://dali.zhiwuduotai.top/Article/details/gtdgkbwezw.html

[S45] C++：lambda
来源：http://dali.smart0.xyz/Article/details/gtqtkbylvf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjngztruq.html

[S46] C++：函数模板
来源：http://dali.jianghu66.top/Article/details/gteqvqboyb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedetaagb.html

[S47] C++：结构化绑定遍历
来源：http://dali.smart0.xyz/Article/details/gttbgkwxwx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xinyue.icu/Article/details/gtmmdbrnrp.html

[S48] C++：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gthplrjjup.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwlixmtl.html

while (std::getline(in, line)) { }
来源：http://dali.xinyue.icu/Article/details/gtzuulamti.html

[S49] C++：写文件
来源：http://dali.birdmap.top/Article/details/gtyjzdjapi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.svipenyu.cn/Article/details/gtwbztfmbq.html

[S50] C++：格式化数字
来源：http://dali.c1oappe.top/Article/details/gtgyyauyxw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtdezqlpts.html

[S51] C++：显式类型转换
来源：http://dali.zdqjudy.top/Article/details/gtguxaqppf.html

static_cast<double>(a) / b
来源：http://dali.fzhhl.top/Article/details/gtqvozayeu.html

[S52] C++：const 与 noexcept
来源：http://dali.jiagoushi.top/Article/details/gtnvflitjk.html

int size() const noexcept { return n_; }
来源：http://dali.sufxvd.cn/Article/details/gtotuzzgsb.html

[S53] C++：移动语义
来源：http://dali.chenjidiqi.icu/Article/details/gtoosvqpla.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigfzy.top/Article/details/gtgicetyky.html

[S54] C++：异常处理
来源：http://dali.cqqwz.cn/Article/details/gtxbyqyrhn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jiagoushi.top/Article/details/gtfvgfgauk.html

[S55] C++：结构化绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwftdolfk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhixingplan.top/Article/details/gtdhgeltxt.html

[S56] C++：optional
来源：http://dali.aizwys.cn/Article/details/gtndqtxkcw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sysykeji.top/Article/details/gtpiqxebmp.html

[S57] C++：编译期常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltcxvojz.html

constexpr int N = 10;
来源：http://dali.jinqigufen.top/Article/details/gtuoyidohz.html

[S58] C++：命名空间
来源：http://dali.havefunace.top/Article/details/gticsrmnfn.html

namespace ns { int f() { return 1; } }
来源：http://dali.bjfxy.top/Article/details/gtezkohtnu.html

[S59] C++：静态断言
来源：http://dali.dianchejie.cn/Article/details/gtmqtqcjrb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sxryk.cn/Article/details/gtbugmirbv.html

[S60] C++：遍历并删除元素
来源：http://dali.daria6918.cn/Article/details/gtdapiswoh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gttswmaows.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtvjwccoxx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tianlin.xyz/Article/details/gtwekulfjm.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtnztjwigq.html

[T01] Kotlin：Hello World
来源：http://dali.aizwys.cn/Article/details/gtucoegbsy.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gtiektzxpf.html

[T02] Kotlin：变量
来源：http://dali.daria6918.cn/Article/details/gtmhtbyilv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhongyouzk.top/Article/details/gtiytqyido.html

[T03] Kotlin：字符串模板
来源：http://dali.wangshuangyany.cn/Article/details/gtiaggfwog.html

"值: $b"
来源：http://dali.nwbrower.top/Article/details/gtexnxipem.html

[T04] Kotlin：空安全
来源：http://dali.yj20258888.top/Article/details/gtjjppmzvm.html

val n: String? = null;  n?.length
来源：http://dali.bjfxy.top/Article/details/gtexnmsyas.html

[T05] Kotlin：when 表达式
来源：http://dali.hysaishi.cn/Article/details/gtypciipud.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jianghu66.top/Article/details/gtnszflobq.html

[T06] Kotlin：集合映射
来源：http://dali.yuanzhike.top/Article/details/gtgcorffdc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmehthcfc.html

[T07] Kotlin：集合过滤
来源：http://dali.xylfe.cn/Article/details/gtdtdpydqn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sufxvd.cn/Article/details/gtwckgojzl.html

[T08] Kotlin：数据类
来源：http://dali.cashguo.top/Article/details/gtrlcdpole.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gtzoqvieag.html

[T09] Kotlin：扩展函数
来源：http://dali.ppjwa.cn/Article/details/gtqzvsmsik.html

fun String.exclaim() = this + "!"
来源：http://dali.svipenyu.cn/Article/details/gtaxgwuldl.html

[T10] Kotlin：默认参数
来源：http://dali.shuidangran.top/Article/details/gteqvpynmt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shzxlz.cn/Article/details/gtaoqtksqg.html

[T11] Kotlin：协程
来源：http://dali.jqgufenzy.top/Article/details/gtcmfuheia.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhongyouzk.top/Article/details/gtqenoopah.html

[T12] Kotlin：解构声明
来源：http://dali.jqgufenzy.top/Article/details/gtmkxoemuc.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtyzrsdvpq.html

[T13] Kotlin：只读 Map
来源：http://dali.haohaochexian.top/Article/details/gtfjttlcdw.html

val m = mapOf("a" to 1)
来源：http://dali.dashuyun.cn/Article/details/gtlwgfwpxl.html

[T14] Kotlin：循环
来源：http://dali.yanxiufei.cn/Article/details/gtsteyqbue.html

for (i in 1..10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gtoeqdnszs.html

[T15] Kotlin：接口
来源：http://dali.chenzaomai.com/Article/details/gtvmbofrrp.html

interface Shape { fun area(): Double }
来源：http://dali.dianchejie.cn/Article/details/gtxnesuxva.html

[T16] Swift：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtitmlxgoq.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtxjwwrrzq.html

[T17] Swift：变量与常量
来源：http://dali.ydzc1.top/Article/details/gtclzgyykw.html

var a = 1;  let b = 2
来源：http://dali.shzxlz.cn/Article/details/gtjzrjfzdn.html

[T18] Swift：字符串插值
来源：http://dali.xinyue.icu/Article/details/gttiecyehn.html

"值: \(b)"
来源：http://dali.smart0.xyz/Article/details/gtegpyapwt.html

[T19] Swift：可选绑定
来源：http://dali.jinqigufen.top/Article/details/gtmusshfcr.html

if let n = opt { print(n) }
来源：http://dali.yj202588.top/Article/details/gtezhiogbo.html

[T20] Swift：数组操作
来源：http://dali.vqdsnc.cn/Article/details/gtyvlbyxft.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shuidangran.top/Article/details/gtuekrmqml.html

[T21] Swift：遍历
来源：http://dali.bjfxy.top/Article/details/gtxqgejslx.html

for x in a { print(x) }
来源：http://dali.zhoulong.xyz/Article/details/gthzqlwpre.html

[T22] Swift：字典
来源：http://dali.gotoacloud.top/Article/details/gtzurfpbkb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.9152youxi.cn/Article/details/gtxsehpdal.html

[T23] Swift：函数
来源：http://dali.ppjwa.cn/Article/details/gtutqljdas.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.haohaochexian.top/Article/details/gtcklslltz.html

[T24] Swift：闭包
来源：http://dali.pycfn.com/Article/details/gtpvacppke.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sysykeji.top/Article/details/gtmrqmwijd.html

[T25] Swift：结构体
来源：http://dali.dianchejie.cn/Article/details/gteulkforb.html

struct P { var x: Int }
来源：http://dali.zdqjudy.top/Article/details/gtmwfpavln.html

[T26] Swift：类与重写
来源：http://dali.iojbl.cn/Article/details/gtqwyducre.html

class A: Base { override func f() {} }
来源：http://dali.shangyingyoupin.top/Article/details/gtpglqoddy.html

[T27] Swift：错误处理
来源：http://dali.jyoumei.cn/Article/details/gtbktxemxb.html

do { try f() } catch { print(error) }
来源：http://dali.cheryme.top/Article/details/gthzqclbxr.html

[T28] Swift：枚举
来源：http://dali.andypj.xyz/Article/details/gtruwknzpg.html

enum Color { case red, green }
来源：http://dali.hfpthk.cn/Article/details/gtktcxckuy.html

[T29] Swift：guard 提前返回
来源：http://dali.cheryme.top/Article/details/gtghqgfjpe.html

guard let x = opt else { return }
来源：http://dali.yj20258888.top/Article/details/gtcjljqxgi.html

[T30] Swift：协议
来源：http://dali.cheryme.top/Article/details/gtderoxont.html

protocol Shape { func area() -> Double }
来源：http://dali.xziqi.cn/Article/details/gtptdbfrbp.html

[T31] Lua：Hello World
来源：http://dali.fengsongda.top/Article/details/gtahojgboy.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtbukaptth.html

[T32] Lua：局部变量
来源：http://dali.zhixingplan.top/Article/details/gtfscmxhgu.html

local a = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvcvyyql.html

[T33] Lua：表（数组）
来源：http://dali.yanxiufei.cn/Article/details/gtuohwufks.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xuanzx.com/Article/details/gthdtfnrvg.html

[T34] Lua：遍历表
来源：http://dali.0kj1m.cn/Article/details/gtetzcoasv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.9152youxi.cn/Article/details/gtflezhgob.html

[T35] Lua：字典表
来源：http://dali.zhengqikj.top/Article/details/gtdqcibwft.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtsopfvene.html

[T36] Lua：函数
来源：http://dali.shzxlz.cn/Article/details/gthiakbpgu.html

function add(a, b) return a + b end
来源：http://dali.sweek.top/Article/details/gtrjdhwgza.html

[T37] Lua：字符串拼接
来源：http://dali.andypj.xyz/Article/details/gtkuhkcigs.html

"a" .. "b"
来源：http://dali.bjfxy.top/Article/details/gtwuriuqeu.html

[T38] Lua：条件
来源：http://dali.chenzaomai.com/Article/details/gtsetodinv.html

if x > 0 then print("正") end
来源：http://dali.shzxlz.cn/Article/details/gtdbawvotd.html

[T39] Lua：模式匹配
来源：http://dali.nanxuanxn.top/Article/details/gttccrxecm.html

string.find(s, "%d+")
来源：http://dali.nanxinkj.top/Article/details/gtfjsxvgpk.html

[T40] Lua：元表
来源：http://dali.daxiang520.top/Article/details/gtmxdvvboy.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigfzy.top/Article/details/gtiihgedzu.html

[T41] Perl：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtgajdjvjw.html

print "Hello\n";
来源：http://dali.sweek.top/Article/details/gtuayawncq.html

[T42] Perl：变量类型
来源：http://dali.yonumen.top/Article/details/gtscycglqr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.0kj1m.cn/Article/details/gttgvionxf.html

[T43] Perl：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtlvoitilj.html

"值: $a"
来源：http://dali.gotoacloud.top/Article/details/gtjoaouzqp.html

[T44] Perl：条件
来源：http://dali.hongshengwenyu.top/Article/details/gtoeooqize.html

if ($a > 0) { print "正"; }
来源：http://dali.ivvv.top/Article/details/gtmnpflsbs.html

[T45] Perl：数组遍历
来源：http://dali.birdmap.top/Article/details/gtkfshhapv.html

for my $x (@arr) { print $x; }
来源：http://dali.daxiang520.top/Article/details/gtwwqnfkyl.html

[T46] Perl：哈希操作
来源：http://dali.feifeiyinyue.top/Article/details/gtiwpprxvs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxnwjfitn.html

[T47] Perl：正则捕获
来源：http://dali.yanxiufei.cn/Article/details/gtciksurtw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xuanzx.com/Article/details/gtaeprmwil.html

[T48] Perl：正则替换
来源：http://dali.jianghu66.top/Article/details/gtbfaqqjis.html

$s =~ s/old/new/g;
来源：http://dali.zhoulong.xyz/Article/details/gtlrtsehjj.html

[T49] Perl：函数
来源：http://dali.cdnleiting.top/Article/details/gtrixgcnvc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtbqxynpia.html

[T50] Perl：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtqgurkers.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigufen.top/Article/details/gtqixgufaa.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.svipenyu.cn/Article/details/gtcvpdfvue.html

[T51] Scala：Hello World
来源：http://dali.iojbl.cn/Article/details/gtwjxkkpyo.html

println("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdytzhvxk.html

[T52] Scala：变量
来源：http://dali.0kj1m.cn/Article/details/gtubzpfzdf.html

val a = 1;  var b = 2
来源：http://dali.yvedp.cn/Article/details/gtdyparmtd.html

[T53] Scala：字符串插值
来源：http://dali.yj20258.top/Article/details/gtxfgfwxao.html

s"值: $b"
来源：http://dali.jqgfzy.top/Article/details/gthkzysasv.html

[T54] Scala：集合映射
来源：http://dali.jyoumei.cn/Article/details/gtlvyrbnya.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tianlin.xyz/Article/details/gtlqinrolm.html

[T55] Scala：集合过滤
来源：http://dali.zhongyouzk.top/Article/details/gtrjrcmajs.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.kuanghao11.cn/Article/details/gtxqsfswnq.html

[T56] Scala：样例类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepxfqgpq.html

case class User(name: String, age: Int)
来源：http://dali.nanxuanxn.top/Article/details/gtlfpshfil.html

[T57] Scala：模式匹配
来源：http://dali.gaohongyu789.top/Article/details/gtyvzyxeze.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhiwuduotai.top/Article/details/gtcvopjefh.html

[T58] Scala：函数定义
来源：http://dali.jiagoushi.top/Article/details/gtjdsxfjyv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gogol.net.cn/Article/details/gtncmrpduk.html

[T59] Scala：循环
来源：http://dali.jiagoushi.top/Article/details/gtwyxbzikm.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gtdmkgzekf.html

[T60] Scala：折叠
来源：http://dali.chenzaomai.com/Article/details/gtjpyjxsmi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgufenzy.top/Article/details/gtwnnjjlwh.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtsahecepe.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.redwolf501.top/Article/details/gtzugdpjgt.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivxhvgvj.html

[U01] Py：创建虚拟环境
来源：http://dali.jyoumei.cn/Article/details/gthciaeixy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gzhubu.top/Article/details/gtdktquyed.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shzxlz.cn/Article/details/gtydzxdksa.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cheryme.top/Article/details/gtbpqgrhbg.html

[U03] Py：加载 .env 配置
来源：http://dali.hnqzz.top/Article/details/gtibuocyhk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hywenlv.cn/Article/details/gtrznxchml.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gtbpgtcakt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nanxuanxn.top/Article/details/gtcjqcrvqh.html

[U05] Py：列表去重且保序
来源：http://dali.dianchejie.cn/Article/details/gtzxpvuqde.html

list(dict.fromkeys(arr))
来源：http://dali.zdqjudy.top/Article/details/gtxmspyatj.html

[U06] Py：合并两个字典
来源：http://dali.yanxiufei.cn/Article/details/gtskvprpqu.html

{**a, **b}
来源：http://dali.zhiwuduotai.top/Article/details/gtmrhhsspr.html

[U07] Py：反转字典键值
来源：http://dali.ydzc1.top/Article/details/gtabbulezg.html

{v: k for k, v in d.items()}
来源：http://dali.xinyue.icu/Article/details/gtmxkftcec.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gtvanjkupf.html

[y for x in nested for y in x]
来源：http://dali.daria6918.cn/Article/details/gtfvinbknx.html

[U09] Py：字典取最大值的键
来源：http://dali.quarkkingdee.top/Article/details/gtztqhgbkd.html

max(d, key=d.get)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpauulchn.html

[U10] Py：按值排序字典
来源：http://dali.quarkkingdee.top/Article/details/gtwlsjvypo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gotoacloud.top/Article/details/gtzomwkygo.html

[U11] Py：生成器表达式
来源：http://dali.yj20258.top/Article/details/gtexpnffuf.html

(x * 2 for x in arr)
来源：http://dali.sufxvd.cn/Article/details/gtxfbqxokh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cqqwz.cn/Article/details/gtdnpdgrrj.html

Counter(arr).most_common(3)
来源：http://dali.zhoulong.xyz/Article/details/gtfgvplohg.html

[U13] Py：固定长度队列
来源：http://dali.316326.xyz/Article/details/gtxhmcyolf.html

deque(maxlen=10)
来源：http://dali.sysykeji.top/Article/details/gtklaczivn.html

[U14] Py：分组收集到列表
来源：http://dali.iojbl.cn/Article/details/gtfleqxpwv.html

defaultdict(list)
来源：http://dali.hywenlv.cn/Article/details/gtddagyzyy.html

[U15] Py：高精度计时
来源：http://dali.redwolf501.top/Article/details/gtvdhixsfj.html

t = time.perf_counter()
来源：http://dali.xziqi.cn/Article/details/gtvdjgixrl.html

[U16] Py：命令行参数解析
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdkhwdjt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinqigfzy.top/Article/details/gtbztrxrxi.html

[U17] Py：初始化日志
来源：http://dali.shzxlz.cn/Article/details/gtycwxttpb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jyoumei.cn/Article/details/gtcrdlsktq.html

[U18] Py：预编译正则
来源：http://dali.c1oappe.top/Article/details/gtpzbnarta.html

pat = re.compile(r"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gttwgrjfaa.html

[U19] Py：正则替换带回调
来源：http://dali.yvedp.cn/Article/details/gtwyfslgjf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.feifeiyinyue.top/Article/details/gtxkwtasex.html

[U20] Py：缓存函数结果
来源：http://dali.birdmap.top/Article/details/gtqxehvepl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.pengpengdd.cyou/Article/details/gthtybjyjy.html

[U21] Py：自定义上下文管理器
来源：http://dali.iojbl.cn/Article/details/gtybcsiphz.html

@contextlib.contextmanager
来源：http://dali.iojbl.cn/Article/details/gttozpccnh.html

[U22] Py：矩阵转置
来源：http://dali.xylfe.cn/Article/details/gtxbmturbh.html

list(zip(*m))
来源：http://dali.yj20258888.top/Article/details/gtsxqdoudu.html

[U23] Py：分块读取大文件
来源：http://dali.yvedp.cn/Article/details/gtxyiltjyr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.svipenyu.cn/Article/details/gtpopvuimq.html

[U24] Py：路径操作
来源：http://dali.wangshuangyany.cn/Article/details/gtciujqzkc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtcxdcbtdb.html

[U25] Py：CSV 按字典读
来源：http://dali.dianchejie.cn/Article/details/gtpxfwhhtw.html

csv.DictReader(f)
来源：http://dali.cqqwz.cn/Article/details/gtxsvuyeeu.html

[U26] Py：并发下载
来源：http://dali.guannengcc.top/Article/details/gtopemcukq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.aizwys.cn/Article/details/gtdgjqswuq.html

[U27] Py：异步 HTTP
来源：http://dali.yj20258.top/Article/details/gthqwwyhuu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhongyouzk.top/Article/details/gtwwbiytex.html

[U28] Py：类型别名
来源：http://dali.cdnleiting.top/Article/details/gtcfvhrwyt.html

UserId = int
来源：http://dali.zycfv.cn/Article/details/gtwtuluzvx.html

[U29] Py：属性校验
来源：http://dali.guowangkeji.top/Article/details/gtxjvrwdtf.html

@property 与 @x.setter 配合
来源：http://dali.ehwqpu.com/Article/details/gtqtqakffd.html

[U30] Py：数据类
来源：http://dali.bjfxy.top/Article/details/gtkolsgfyx.html

@dataclass(slots=True)
来源：http://dali.havefunace.top/Article/details/gtmlnsurro.html

[U31] Py：单测
来源：http://dali.birdmap.top/Article/details/gtfdstzdyd.html

python -m pytest -q
来源：http://dali.meibo888.top/Article/details/gtdfzupjmh.html

[U32] Py：代码格式化
来源：http://dali.jinqigfzy.top/Article/details/gthwfqooon.html

ruff format . && ruff check --fix .
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslkfmwas.html

[U33] Py：打包发布
来源：http://dali.pycfn.com/Article/details/gtupjyokjr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhixingplan.top/Article/details/gtkvwdvbwl.html

[U34] Py：判断编码
来源：http://dali.ivvv.top/Article/details/gtulsxfbwb.html

chardet.detect(raw)
来源：http://dali.gotoacloud.top/Article/details/gtwvmrebmo.html

[U35] Py：发送邮件
来源：http://dali.wangdashe.top/Article/details/gterfvqvik.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.haohaochexian.top/Article/details/gtlenltabt.html

[U36] Py：定时任务
来源：http://dali.gotoacloud.top/Article/details/gtkzapjcav.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhoulong.xyz/Article/details/gtrmptwznm.html

[U37] Py：读写 Excel
来源：http://dali.birdmap.top/Article/details/gtnlhdizeq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.svipenyu.cn/Article/details/gtcvjdupmi.html

[U38] Py：获取脚本所在目录
来源：http://dali.sufxvd.cn/Article/details/gtosbisjbs.html

Path(__file__).resolve().parent
来源：http://dali.shangyingyoupin.top/Article/details/gtmjsdwtdl.html

[U39] Py：判断是否在交互环境
来源：http://dali.chenjidiqi.icu/Article/details/gtvrkbuilb.html

sys.stdout.isatty()
来源：http://dali.chenjidiqi.icu/Article/details/gtitmwbakq.html

[U40] Py：打印到标准错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjcjqyyc.html

print("err", file=sys.stderr)
来源：http://dali.yonumen.top/Article/details/gtfziordix.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.0kj1m.cn/Article/details/gtqfgohoqe.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.redwolf501.top/Article/details/gtmleajxxo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.smart0.xyz/Article/details/gtmzvsiyay.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.c1oappe.top/Article/details/gtzmkcnope.html

[U43] PHP：声明命名空间
来源：http://dali.yj202588.top/Article/details/gtbnxyfuuf.html

namespace App\Http;
来源：http://dali.tanke756.top/Article/details/gtrlmxpsgg.html

[U44] PHP：开启严格类型
来源：http://dali.hongshengwenyu.top/Article/details/gtrvsaqpdt.html

declare(strict_types=1);
来源：http://dali.aizwys.cn/Article/details/gtkdixtnxj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwyrfvva.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtjjvydeuy.html

[U46] PHP：可空类型
来源：http://dali.yuanzhike.top/Article/details/gtztbxyjhf.html

?string $name = null
来源：http://dali.chenjidiqi.icu/Article/details/gtwuwpoelw.html


<!-- 参考信息 -->