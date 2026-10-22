代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fengsongda.top/Article/details/gttaqhbfis.html

[S23] C：随机数
来源：http://dali.yj202588.top/Article/details/gtqtbfbauv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258.top/Article/details/gtksrgxefa.html

[S24] C：获取本地时间
来源：http://dali.quarkkingdee.top/Article/details/gtsczadnoz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.snrcjt.cn/Article/details/gtvpngoiup.html

[S25] C：内存拷贝
来源：http://dali.chenlongwang.top/Article/details/gtqifrquyf.html

memcpy(dst, src, n);
来源：http://dali.cashguo.top/Article/details/gtnguhkevu.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gtebosfdnw.html

memset(a, 0, sizeof a);
来源：http://dali.fzhhl.top/Article/details/gtmexljfpd.html

[S27] C：定义常量
来源：http://dali.yvedp.cn/Article/details/gtfnumppxe.html

const double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmfnlwpg.html

[S28] C：静态变量
来源：http://dali.feifeiyinyue.top/Article/details/gtbcrnvnru.html

static int counter = 0;
来源：http://dali.sufxvd.cn/Article/details/gtqyowdyar.html

[S29] C：变参函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcaeyjqv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ppjwa.cn/Article/details/gtaksacpdh.html

[S30] C：头文件保护
来源：http://dali.wangdashe.top/Article/details/gtwulucdks.html

#ifndef X_H
来源：http://dali.hywenlv.cn/Article/details/gtafnqomdk.html

#define X_H
来源：http://dali.gotoacloud.top/Article/details/gttwjbcanm.html

#endif
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpptatkvd.html

[S31] C++：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtratgsmhd.html

#include <iostream>
来源：http://dali.yongpay.top/Article/details/gtpibidxec.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgufenzy.top/Article/details/gtxpdpymdz.html

[S32] C++：字符串
来源：http://dali.xziqi.cn/Article/details/gtkjewuujb.html

std::string s = "hi";  s += "!";
来源：http://dali.hnqzz.top/Article/details/gtxqjnnrbn.html

[S33] C++：vector 增删
来源：http://dali.haohaochexian.top/Article/details/gtpyhriymt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tanke756.top/Article/details/gtrwqbeqwf.html

[S34] C++：遍历 vector
来源：http://dali.aizwys.cn/Article/details/gtldcoxbjw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shzxlz.cn/Article/details/gtrelblvbb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gtgfysbdva.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtmvdehtln.html

[S36] C++：unordered_map
来源：http://dali.nanxuanxn.top/Article/details/gtbhdcvqyc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtpydgjmwd.html

[S37] C++：set
来源：http://dali.xylfe.cn/Article/details/gtujucqavv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xylfe.cn/Article/details/gtelnnmndf.html

[S38] C++：排序
来源：http://dali.chenzaomai.com/Article/details/gtfsrdwofx.html

std::sort(v.begin(), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtjszdouxb.html

[S39] C++：自定义比较器排序
来源：http://dali.hfpthk.cn/Article/details/gtpmnkqfrl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gtmbklzqvg.html

[S40] C++：查找元素
来源：http://dali.fengsongda.top/Article/details/gtilurajbq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtuyadhqhf.html

[S41] C++：类与构造函数
来源：http://dali.zhongyouzk.top/Article/details/gtqbtfahnw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xylfe.cn/Article/details/gtelcghwua.html

[S42] C++：继承与虚函数
来源：http://dali.wangshuangyany.cn/Article/details/gtiwvcifeh.html

class B : public Base { public: void f() override {} };
来源：http://dali.nwbrower.top/Article/details/gtvqrkjsox.html

[S43] C++：智能指针
来源：http://dali.aibaodan.cn/Article/details/gtzozvvsix.html

auto p = std::make_unique<int>(5);
来源：http://dali.sysykeji.top/Article/details/gtxcmndyxc.html

[S44] C++：引用传参
来源：http://dali.yvedp.cn/Article/details/gtxmiuaizk.html

void inc(int &x) { ++x; }
来源：http://dali.haohaochexian.top/Article/details/gtcjskxjxo.html

[S45] C++：lambda
来源：http://dali.yj20258.top/Article/details/gtnvmvllzl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.andypj.xyz/Article/details/gtrzdpovnq.html

[S46] C++：函数模板
来源：http://dali.jiagoushi.top/Article/details/gtdobmvcoz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.9152youxi.cn/Article/details/gtslzfndyh.html

[S47] C++：结构化绑定遍历
来源：http://dali.mhx1999.top/Article/details/gthmopaivm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmrqwgkhd.html

[S48] C++：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtjiixlqld.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258.top/Article/details/gtnvzewylm.html

while (std::getline(in, line)) { }
来源：http://dali.hywenlv.cn/Article/details/gtfukgzvpu.html

[S49] C++：写文件
来源：http://dali.hnqzz.top/Article/details/gthvtdgszi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxinkj.top/Article/details/gtaqdkpzfp.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gtigkdwjep.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gteiqgxycz.html

[S51] C++：显式类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtgstilmch.html

static_cast<double>(a) / b
来源：http://dali.gzhubu.top/Article/details/gtajzrkyzz.html

[S52] C++：const 与 noexcept
来源：http://dali.fengsongda.top/Article/details/gtnswqonqr.html

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gtivsluksj.html

[S53] C++：移动语义
来源：http://dali.yonumen.top/Article/details/gtbesgefhx.html

std::vector<int> w = std::move(v);
来源：http://dali.yj202588.top/Article/details/gtkidfsqer.html

[S54] C++：异常处理
来源：http://dali.ehwqpu.com/Article/details/gtdfraddgw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.andypj.xyz/Article/details/gtwtbivmap.html

[S55] C++：结构化绑定
来源：http://dali.0kj1m.cn/Article/details/gtnmqfaodq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yonumen.top/Article/details/gtglpbaavo.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gtujmtebar.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yvedp.cn/Article/details/gtzvcsdnvx.html

[S57] C++：编译期常量
来源：http://dali.hywenlv.cn/Article/details/gtqfayjgsv.html

constexpr int N = 10;
来源：http://dali.wangdashe.top/Article/details/gteqkjynip.html

[S58] C++：命名空间
来源：http://dali.gzhubu.top/Article/details/gtbnyuunnm.html

namespace ns { int f() { return 1; } }
来源：http://dali.xylfe.cn/Article/details/gtmznyrmfq.html

[S59] C++：静态断言
来源：http://dali.tian-w.cn/Article/details/gtckvadfun.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258.top/Article/details/gtafaolgcp.html

[S60] C++：遍历并删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gtieflijyw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gtxqidvomf.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gthfuxmyqr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.svipenyu.cn/Article/details/gtzdwskemf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtitqnndzl.html

[T01] Kotlin：Hello World
来源：http://dali.ivvv.top/Article/details/gtpuiiiock.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gtqvdnlfco.html

[T02] Kotlin：变量
来源：http://dali.jyoumei.cn/Article/details/gtidxzldoo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.redwolf501.top/Article/details/gtybcaiwek.html

[T03] Kotlin：字符串模板
来源：http://dali.ybcxt.top/Article/details/gtkljvkoqp.html

"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gtosaqqwpf.html

[T04] Kotlin：空安全
来源：http://dali.hfpthk.cn/Article/details/gthrjmhhad.html

val n: String? = null;  n?.length
来源：http://dali.jyoumei.cn/Article/details/gtfuudhtye.html

[T05] Kotlin：when 表达式
来源：http://dali.zhixingplan.top/Article/details/gtjwmsiyai.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yanxiufei.cn/Article/details/gtrgqhsmmx.html

[T06] Kotlin：集合映射
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrckbjvie.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xziqi.cn/Article/details/gtcsebisyv.html

[T07] Kotlin：集合过滤
来源：http://dali.daxiang520.top/Article/details/gtmocdtbvq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cheryme.top/Article/details/gtcspsyoqz.html

[T08] Kotlin：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gtcfjuzchk.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdfxutjo.html

[T09] Kotlin：扩展函数
来源：http://dali.yonumen.top/Article/details/gtihmacwom.html

fun String.exclaim() = this + "!"
来源：http://dali.hongshengwenyu.top/Article/details/gtixpqwvzo.html

[T10] Kotlin：默认参数
来源：http://dali.yvedp.cn/Article/details/gtvybkilxf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenzaomai.com/Article/details/gtgfkxewga.html

[T11] Kotlin：协程
来源：http://dali.yuanzhike.top/Article/details/gtfoxsxejn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.316326.xyz/Article/details/gtvmuflzcy.html

[T12] Kotlin：解构声明
来源：http://dali.fengsongda.top/Article/details/gtnfgwazor.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtowoifptx.html

[T13] Kotlin：只读 Map
来源：http://dali.vqdsnc.cn/Article/details/gttbqpknce.html

val m = mapOf("a" to 1)
来源：http://dali.yonumen.top/Article/details/gtpwfgdfzz.html

[T14] Kotlin：循环
来源：http://dali.bjfxy.top/Article/details/gtoxogbzad.html

for (i in 1..10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gtqqwbokrv.html

[T15] Kotlin：接口
来源：http://dali.zhongyouzk.top/Article/details/gtmcmenoek.html

interface Shape { fun area(): Double }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcnmcsyu.html

[T16] Swift：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtjljunjed.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtnjnatsdl.html

[T17] Swift：变量与常量
来源：http://dali.ppjwa.cn/Article/details/gtpaqakyka.html

var a = 1;  let b = 2
来源：http://dali.yanxiufei.cn/Article/details/gtvvdomtjn.html

[T18] Swift：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gtghmltlan.html

"值: \(b)"
来源：http://dali.havefunace.top/Article/details/gtefvmebsb.html

[T19] Swift：可选绑定
来源：http://dali.daxiang520.top/Article/details/gtgshaxokz.html

if let n = opt { print(n) }
来源：http://dali.9152youxi.cn/Article/details/gtxhyaizkv.html

[T20] Swift：数组操作
来源：http://dali.zhengqikj.top/Article/details/gtogdvpvvb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.birdmap.top/Article/details/gtsthvrjki.html

[T21] Swift：遍历
来源：http://dali.fengsongda.top/Article/details/gtugenfrzb.html

for x in a { print(x) }
来源：http://dali.hnxiangtu.top/Article/details/gtyhtywlxj.html

[T22] Swift：字典
来源：http://dali.xziqi.cn/Article/details/gthokothff.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigfzy.top/Article/details/gttdnapoxs.html

[T23] Swift：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtgryrqybf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.birdmap.top/Article/details/gtuhvyhdud.html

[T24] Swift：闭包
来源：http://dali.zhiwuduotai.top/Article/details/gtxjxgyzkf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtjmslodeu.html

[T25] Swift：结构体
来源：http://dali.andypj.xyz/Article/details/gtuufmdynt.html

struct P { var x: Int }
来源：http://dali.hysaishi.cn/Article/details/gtzykisjgm.html

[T26] Swift：类与重写
来源：http://dali.9152youxi.cn/Article/details/gtorwyzzqz.html

class A: Base { override func f() {} }
来源：http://dali.haohaochexian.top/Article/details/gtysjgatly.html

[T27] Swift：错误处理
来源：http://dali.xinyue.icu/Article/details/gtywyhvpmy.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258888.top/Article/details/gtgeiykueo.html

[T28] Swift：枚举
来源：http://dali.gzhubu.top/Article/details/gtbkixlrtg.html

enum Color { case red, green }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcktjozve.html

[T29] Swift：guard 提前返回
来源：http://dali.jianghu66.top/Article/details/gtjapjwdrz.html

guard let x = opt else { return }
来源：http://dali.pycfn.com/Article/details/gtiljkuogg.html

[T30] Swift：协议
来源：http://dali.chenzaomai.com/Article/details/gtphuvarlp.html

protocol Shape { func area() -> Double }
来源：http://dali.cqqwz.cn/Article/details/gtxneoywca.html

[T31] Lua：Hello World
来源：http://dali.gzhubu.top/Article/details/gthpbyfxkl.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gtcnvsifor.html

[T32] Lua：局部变量
来源：http://dali.nwbrower.top/Article/details/gtbzsfuyxw.html

local a = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvtgjnfw.html

[T33] Lua：表（数组）
来源：http://dali.fengsongda.top/Article/details/gtsaumbsed.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.feifeiyinyue.top/Article/details/gtbmxyxljo.html

[T34] Lua：遍历表
来源：http://dali.cheryme.top/Article/details/gtgqnvoesf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.fzhhl.top/Article/details/gtlkjwgbct.html

[T35] Lua：字典表
来源：http://dali.feifeiyinyue.top/Article/details/gtmlbbjgav.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cdnleiting.top/Article/details/gtgcznhkwl.html

[T36] Lua：函数
来源：http://dali.gzhubu.top/Article/details/gtnijeoamg.html

function add(a, b) return a + b end
来源：http://dali.jiagoushi.top/Article/details/gtlkliszgz.html

[T37] Lua：字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gttjpvsuqf.html

"a" .. "b"
来源：http://dali.redwolf501.top/Article/details/gtmiliohdr.html

[T38] Lua：条件
来源：http://dali.fzhhl.top/Article/details/gtuaxxfhcx.html

if x > 0 then print("正") end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbygwswn.html

[T39] Lua：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gtwulowpff.html

string.find(s, "%d+")
来源：http://dali.meibo888.top/Article/details/gtvwnryfpm.html

[T40] Lua：元表
来源：http://dali.feifeiyinyue.top/Article/details/gtghfbtlvq.html

setmetatable({}, { __index = base })
来源：http://dali.yuanzhike.top/Article/details/gtyqxvropb.html

[T41] Perl：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtpffucyqa.html

print "Hello\n";
来源：http://dali.yuanzhike.top/Article/details/gtdreowfig.html

[T42] Perl：变量类型
来源：http://dali.cucudq.cn/Article/details/gtrmjddebo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sufxvd.cn/Article/details/gtfpudazvx.html

[T43] Perl：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gthyqjfzne.html

"值: $a"
来源：http://dali.c1oappe.top/Article/details/gtfzmutkyv.html

[T44] Perl：条件
来源：http://dali.hammf.cn/Article/details/gtjuegtdym.html

if ($a > 0) { print "正"; }
来源：http://dali.zycfv.cn/Article/details/gtuvnyxfzt.html

[T45] Perl：数组遍历
来源：http://dali.yvedp.cn/Article/details/gtzliytfsy.html

for my $x (@arr) { print $x; }
来源：http://dali.yj20258.top/Article/details/gtyojxdzgq.html

[T46] Perl：哈希操作
来源：http://dali.xinyue.icu/Article/details/gtrkrjwevv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.redwolf501.top/Article/details/gtmylidiqw.html

[T47] Perl：正则捕获
来源：http://dali.yonumen.top/Article/details/gtibsudojk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.andypj.xyz/Article/details/gtqkfcbrgh.html

[T48] Perl：正则替换
来源：http://dali.guannengcc.top/Article/details/gttvpgscst.html

$s =~ s/old/new/g;
来源：http://dali.gaohongyu789.top/Article/details/gtpukrzanb.html

[T49] Perl：函数
来源：http://dali.shuidangran.top/Article/details/gtnjvkuzzu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtututywfn.html

[T50] Perl：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtmoixsvto.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.daria6918.cn/Article/details/gtexipoytw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pycfn.com/Article/details/gtnqwalygw.html

[T51] Scala：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtgvoancvv.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gttgoccvdd.html

[T52] Scala：变量
来源：http://dali.jinqigfzy.top/Article/details/gtptylnhak.html

val a = 1;  var b = 2
来源：http://dali.andypj.xyz/Article/details/gtbtyahszg.html

[T53] Scala：字符串插值
来源：http://dali.yj20258888.top/Article/details/gtzkpounos.html

s"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gtheiisnha.html

[T54] Scala：集合映射
来源：http://dali.xylfe.cn/Article/details/gtgmblpcpz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gttbzxsvmg.html

[T55] Scala：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gtobdlxtai.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.redwolf501.top/Article/details/gtidblfchd.html

[T56] Scala：样例类
来源：http://dali.yongpay.top/Article/details/gtphjzsmyr.html

case class User(name: String, age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gtignujiuy.html

[T57] Scala：模式匹配
来源：http://dali.tian-w.cn/Article/details/gtkpyifavm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.feifeiyinyue.top/Article/details/gtuoyyxyxs.html

[T58] Scala：函数定义
来源：http://dali.nwbrower.top/Article/details/gtkjqfcwgr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj202588.top/Article/details/gtvawhltsa.html

[T59] Scala：循环
来源：http://dali.jinqigufen.top/Article/details/gtsrnncebx.html

for (i <- 1 to 10) println(i)
来源：http://dali.cheryme.top/Article/details/gtkpprdymr.html

[T60] Scala：折叠
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvfviqzv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhiwuduotai.top/Article/details/gtgtoahwlv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtzxzgicli.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.svipenyu.cn/Article/details/gtsklaqhqy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtbcdjdahd.html

[U01] Py：创建虚拟环境
来源：http://dali.ivvv.top/Article/details/gtsqayshbl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.birdmap.top/Article/details/gtmtxeybjb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj202588.top/Article/details/gtilsmoysi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daxiang520.top/Article/details/gtmfrvhqgj.html

[U03] Py：加载 .env 配置
来源：http://dali.ivvv.top/Article/details/gtwpkixyyu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhongyouzk.top/Article/details/gtvmccekfk.html

[U04] Py：变量调试打印
来源：http://dali.andypj.xyz/Article/details/gtgdkgxoue.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sxryk.cn/Article/details/gtpkznhrnp.html

[U05] Py：列表去重且保序
来源：http://dali.fzhhl.top/Article/details/gtoqxyzuom.html

list(dict.fromkeys(arr))
来源：http://dali.sufxvd.cn/Article/details/gtbopgenmm.html

[U06] Py：合并两个字典
来源：http://dali.hysaishi.cn/Article/details/gttmtnxahr.html

{**a, **b}
来源：http://dali.gzhubu.top/Article/details/gthsoyzblx.html

[U07] Py：反转字典键值
来源：http://dali.gotoacloud.top/Article/details/gtdcnlbbzl.html

{v: k for k, v in d.items()}
来源：http://dali.cdnleiting.top/Article/details/gtfijwrtmt.html

[U08] Py：展平二维列表
来源：http://dali.zdqjudy.top/Article/details/gtzkvuqrys.html

[y for x in nested for y in x]
来源：http://dali.wangshuangyany.cn/Article/details/gtkmjitcbe.html

[U09] Py：字典取最大值的键
来源：http://dali.sufxvd.cn/Article/details/gtskjawlvz.html

max(d, key=d.get)
来源：http://dali.birdmap.top/Article/details/gtbbtcmeuv.html

[U10] Py：按值排序字典
来源：http://dali.zycfv.cn/Article/details/gtinqjfmxc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pengpengdd.cyou/Article/details/gtnnheiltf.html

[U11] Py：生成器表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtdkkamckv.html

(x * 2 for x in arr)
来源：http://dali.dianchejie.cn/Article/details/gtepcogwvx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zycfv.cn/Article/details/gtcvbvncgt.html

Counter(arr).most_common(3)
来源：http://dali.shzxlz.cn/Article/details/gtnlmzfmkc.html

[U13] Py：固定长度队列
来源：http://dali.tanke756.top/Article/details/gtbhlglkiz.html

deque(maxlen=10)
来源：http://dali.tianlin.xyz/Article/details/gtyebajsyy.html

[U14] Py：分组收集到列表
来源：http://dali.cdnleiting.top/Article/details/gtlfwapefc.html

defaultdict(list)
来源：http://dali.sweek.top/Article/details/gttrcjvbxy.html

[U15] Py：高精度计时
来源：http://dali.wangshuangyany.cn/Article/details/gtxntjpate.html

t = time.perf_counter()
来源：http://dali.redwolf501.top/Article/details/gtfebxyppt.html

[U16] Py：命令行参数解析
来源：http://dali.haohaochexian.top/Article/details/gtwjfdxcrg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.dashuyun.cn/Article/details/gtlzndkqqe.html

[U17] Py：初始化日志
来源：http://dali.daria6918.cn/Article/details/gteycczhig.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzdfovyd.html

[U18] Py：预编译正则
来源：http://dali.yanxiufei.cn/Article/details/gtbslvxepq.html

pat = re.compile(r"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpgfyquf.html

[U19] Py：正则替换带回调
来源：http://dali.yuxming.cn/Article/details/gtqpffeguu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gtznfzkpin.html

[U20] Py：缓存函数结果
来源：http://dali.jianghu66.top/Article/details/gthwvonokr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zycfv.cn/Article/details/gtadzigyvo.html

[U21] Py：自定义上下文管理器
来源：http://dali.aibaodan.cn/Article/details/gtsjdzhwsr.html

@contextlib.contextmanager
来源：http://dali.yueranfly.top/Article/details/gtjtdgwqho.html

[U22] Py：矩阵转置
来源：http://dali.gotoacloud.top/Article/details/gteqqhhmrm.html

list(zip(*m))
来源：http://dali.sufxvd.cn/Article/details/gtoomhdupi.html

[U23] Py：分块读取大文件
来源：http://dali.gogol.net.cn/Article/details/gtzchskrrs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.quarkkingdee.top/Article/details/gtlwlcbnyu.html

[U24] Py：路径操作
来源：http://dali.xuanzx.com/Article/details/gtoawwmxvn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gtujaougkz.html

[U25] Py：CSV 按字典读
来源：http://dali.xuanzx.com/Article/details/gtsjpdrrjr.html

csv.DictReader(f)
来源：http://dali.xuanzx.com/Article/details/gtmxgvkscm.html

[U26] Py：并发下载
来源：http://dali.jinqigfzy.top/Article/details/gtofovauri.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jqgufenzy.top/Article/details/gticvrvybu.html

[U27] Py：异步 HTTP
来源：http://dali.yueranfly.top/Article/details/gtfaiqnpel.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sweek.top/Article/details/gtscxzokhr.html

[U28] Py：类型别名
来源：http://dali.jinqigfzy.top/Article/details/gtdalfytst.html

UserId = int
来源：http://dali.jqgfzy.top/Article/details/gtfvvhghos.html

[U29] Py：属性校验
来源：http://dali.shuidangran.top/Article/details/gtoufmamjf.html

@property 与 @x.setter 配合
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbpoufrq.html

[U30] Py：数据类
来源：http://dali.guowangkeji.top/Article/details/gtygzoglut.html

@dataclass(slots=True)
来源：http://dali.ehwqpu.com/Article/details/gtmujnsslp.html

[U31] Py：单测
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblgautsn.html

python -m pytest -q
来源：http://dali.ybcxt.top/Article/details/gtmpkzrtls.html

[U32] Py：代码格式化
来源：http://dali.jyoumei.cn/Article/details/gtcmqyrwxf.html

ruff format . && ruff check --fix .
来源：http://dali.c1oappe.top/Article/details/gtubcuuwxe.html

[U33] Py：打包发布
来源：http://dali.zycfv.cn/Article/details/gtneykvikp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nwbrower.top/Article/details/gtnlctrrwo.html

[U34] Py：判断编码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgtydmzb.html

chardet.detect(raw)
来源：http://dali.sysykeji.top/Article/details/gtgmvnwszp.html

[U35] Py：发送邮件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbcglvov.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shangyingyoupin.top/Article/details/gtwtcyijtz.html

[U36] Py：定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukbojkbh.html

schedule.every(10).minutes.do(job)
来源：http://dali.daria6918.cn/Article/details/gtotuajujs.html

[U37] Py：读写 Excel
来源：http://dali.tian-w.cn/Article/details/gtfnolswtm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yanxiufei.cn/Article/details/gtwlqfueiq.html

[U38] Py：获取脚本所在目录
来源：http://dali.nanxinkj.top/Article/details/gtzcwyhxgg.html

Path(__file__).resolve().parent
来源：http://dali.yj20258.top/Article/details/gtsfixixeg.html

[U39] Py：判断是否在交互环境
来源：http://dali.gzhubu.top/Article/details/gtcltvyrtp.html

sys.stdout.isatty()
来源：http://dali.iojbl.cn/Article/details/gtvilbfken.html

[U40] Py：打印到标准错误
来源：http://dali.0kj1m.cn/Article/details/gtvgifgfqk.html

print("err", file=sys.stderr)
来源：http://dali.haohaochexian.top/Article/details/gtyjylksno.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.birdmap.top/Article/details/gtksfmzyov.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ehwqpu.com/Article/details/gtdxhehrzw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jqgufenzy.top/Article/details/gtonclenlb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tanke756.top/Article/details/gtbnzvbasd.html

[U43] PHP：声明命名空间
来源：http://dali.jinqigufen.top/Article/details/gtusfvwztr.html

namespace App\Http;
来源：http://dali.wangshuangyany.cn/Article/details/gtvmffjdgc.html

[U44] PHP：开启严格类型
来源：http://dali.cucudq.cn/Article/details/gtqrngdwri.html

declare(strict_types=1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcrhanzj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.nanxinkj.top/Article/details/gtpvqzrqzg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gtmvjhmetx.html

[U46] PHP：可空类型
来源：http://dali.snrcjt.cn/Article/details/gtpvikiqgv.html

?string $name = null
来源：http://dali.ehwqpu.com/Article/details/gteovsdhlk.html


<!-- 参考信息 -->