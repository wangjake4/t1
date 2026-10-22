代发 wailian999

int main(int argc, char **argv)
来源：http://dali.pycfn.com/Article/details/gtqltdywzr.html

[S19] C：快速排序
来源：http://dali.feifeiyinyue.top/Article/details/gtjzodovvr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtptgjbxgu.html

[S20] C：二分查找
来源：http://dali.zhiwuduotai.top/Article/details/gtjkagncsl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gtthzoyrqj.html

[S21] C：字符类别判断
来源：http://dali.nwbrower.top/Article/details/gtepptwlgd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dashuyun.cn/Article/details/gtfvlmbgih.html

[S22] C：字符串转数字
来源：http://dali.0kj1m.cn/Article/details/gtqsqbsjcg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tanke756.top/Article/details/gtymfvqvii.html

[S23] C：随机数
来源：http://dali.jiagoushi.top/Article/details/gtwuxkabuy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zycfv.cn/Article/details/gtemxejwth.html

[S24] C：获取本地时间
来源：http://dali.nanxinkj.top/Article/details/gtlyopuxyx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dashuyun.cn/Article/details/gtfabiriwg.html

[S25] C：内存拷贝
来源：http://dali.zycfv.cn/Article/details/gtrqxtkvfb.html

memcpy(dst, src, n);
来源：http://dali.tianlin.xyz/Article/details/gtbbtszptg.html

[S26] C：内存清零
来源：http://dali.yangfankeji.com/Article/details/gtcpubciem.html

memset(a, 0, sizeof a);
来源：http://dali.yj202588.top/Article/details/gtoxhgwyzh.html

[S27] C：定义常量
来源：http://dali.chenjidiqi.icu/Article/details/gtatljsozt.html

const double PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarvsnpnl.html

[S28] C：静态变量
来源：http://dali.yvedp.cn/Article/details/gtwlomxnaw.html

static int counter = 0;
来源：http://dali.jlsjyb.cn/Article/details/gtngepnxzl.html

[S29] C：变参函数
来源：http://dali.havefunace.top/Article/details/gtrzhkofbf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daria6918.cn/Article/details/gtezliiche.html

[S30] C：头文件保护
来源：http://dali.zhoulong.xyz/Article/details/gtokfbjaot.html

#ifndef X_H
来源：http://dali.svipenyu.cn/Article/details/gtxpgpfzyt.html

#define X_H
来源：http://dali.zdqjudy.top/Article/details/gtmcpafbol.html

#endif
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhmnqfoi.html

[S31] C++：Hello World
来源：http://dali.pycfn.com/Article/details/gtclodxkht.html

#include <iostream>
来源：http://dali.jianghu66.top/Article/details/gtkdqrtjle.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dianchejie.cn/Article/details/gtipuexctt.html

[S32] C++：字符串
来源：http://dali.hongshengwenyu.top/Article/details/gttkkbiyhl.html

std::string s = "hi";  s += "!";
来源：http://dali.wangdashe.top/Article/details/gtzqgkrhgq.html

[S33] C++：vector 增删
来源：http://dali.jyoumei.cn/Article/details/gtbadewevi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xinyue.icu/Article/details/gtdteyeedp.html

[S34] C++：遍历 vector
来源：http://dali.shuidangran.top/Article/details/gtkmtlnwdj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgwlvxugi.html

[S35] C++：map
来源：http://dali.fengsongda.top/Article/details/gtpfxujfwl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gtmmyivqeo.html

[S36] C++：unordered_map
来源：http://dali.ydzc1.top/Article/details/gthukuxiux.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtlximtlsa.html

[S37] C++：set
来源：http://dali.vqdsnc.cn/Article/details/gteqlpnzxa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ydzc1.top/Article/details/gtfbfwrjii.html

[S38] C++：排序
来源：http://dali.birdmap.top/Article/details/gtyntabzgo.html

std::sort(v.begin(), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejnxehkw.html

[S39] C++：自定义比较器排序
来源：http://dali.9152youxi.cn/Article/details/gtttjpzzys.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xziqi.cn/Article/details/gtkhjciztw.html

[S40] C++：查找元素
来源：http://dali.hongshengwenyu.top/Article/details/gtreqjfybu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ppjwa.cn/Article/details/gtqnjrbxti.html

[S41] C++：类与构造函数
来源：http://dali.gotoacloud.top/Article/details/gtxkfgaify.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yangfankeji.com/Article/details/gtlmfgkjyu.html

[S42] C++：继承与虚函数
来源：http://dali.c1oappe.top/Article/details/gtyljnelnx.html

class B : public Base { public: void f() override {} };
来源：http://dali.daxiang520.top/Article/details/gtuzefirhz.html

[S43] C++：智能指针
来源：http://dali.sufxvd.cn/Article/details/gtjitalpjo.html

auto p = std::make_unique<int>(5);
来源：http://dali.ydzc1.top/Article/details/gtitksajch.html

[S44] C++：引用传参
来源：http://dali.guowangkeji.top/Article/details/gtegytjuoa.html

void inc(int &x) { ++x; }
来源：http://dali.ydzc1.top/Article/details/gtfkzasatm.html

[S45] C++：lambda
来源：http://dali.cucudq.cn/Article/details/gtlgffijrn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tianlin.xyz/Article/details/gtzackwabw.html

[S46] C++：函数模板
来源：http://dali.fzhhl.top/Article/details/gttfgwrtxy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hammf.cn/Article/details/gtegkbuldr.html

[S47] C++：结构化绑定遍历
来源：http://dali.dianchejie.cn/Article/details/gtdfowyzaa.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.meibo888.top/Article/details/gthuyvdajw.html

[S48] C++：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtbgjfqatq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fengsongda.top/Article/details/gtdwmonyoi.html

while (std::getline(in, line)) { }
来源：http://dali.shzxlz.cn/Article/details/gtxksldgkz.html

[S49] C++：写文件
来源：http://dali.hywenlv.cn/Article/details/gtohxrwkum.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sweek.top/Article/details/gtupckibxo.html

[S50] C++：格式化数字
来源：http://dali.xziqi.cn/Article/details/gtqxfoosrh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtjitxatnl.html

[S51] C++：显式类型转换
来源：http://dali.pycfn.com/Article/details/gtdiqktbjo.html

static_cast<double>(a) / b
来源：http://dali.sxryk.cn/Article/details/gthqpccoqb.html

[S52] C++：const 与 noexcept
来源：http://dali.quarkkingdee.top/Article/details/gtnczzabnm.html

int size() const noexcept { return n_; }
来源：http://dali.fzhhl.top/Article/details/gtkjkjetlh.html

[S53] C++：移动语义
来源：http://dali.ydzc1.top/Article/details/gtsmadghbf.html

std::vector<int> w = std::move(v);
来源：http://dali.guowangkeji.top/Article/details/gtpursjbhe.html

[S54] C++：异常处理
来源：http://dali.wangdashe.top/Article/details/gtayylvuxg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyefjktbo.html

[S55] C++：结构化绑定
来源：http://dali.ppjwa.cn/Article/details/gtauifnhbm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sxryk.cn/Article/details/gtjhrqjabe.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gtkpyvpbkf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigufen.top/Article/details/gtqnxxjxjx.html

[S57] C++：编译期常量
来源：http://dali.chenzaomai.com/Article/details/gtkrdxxzys.html

constexpr int N = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxjsrggq.html

[S58] C++：命名空间
来源：http://dali.sufxvd.cn/Article/details/gtytgroaij.html

namespace ns { int f() { return 1; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtwjqpmnzx.html

[S59] C++：静态断言
来源：http://dali.dashuyun.cn/Article/details/gtthlqjrbb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ehwqpu.com/Article/details/gtifskmxeo.html

[S60] C++：遍历并删除元素
来源：http://dali.wangdashe.top/Article/details/gtgvrryelv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxinkj.top/Article/details/gtelwiqpdt.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtngyaudzn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xylfe.cn/Article/details/gtsrzrldbp.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtnfyrfbko.html

[T01] Kotlin：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqitiiipe.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gtnumfuyjn.html

[T02] Kotlin：变量
来源：http://dali.yongpay.top/Article/details/gtjadzakwh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gaohongyu789.top/Article/details/gtsvfohqoa.html

[T03] Kotlin：字符串模板
来源：http://dali.bjfxy.top/Article/details/gtxxbqjoca.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtuynypekt.html

[T04] Kotlin：空安全
来源：http://dali.ehwqpu.com/Article/details/gtgevuavry.html

val n: String? = null;  n?.length
来源：http://dali.meibo888.top/Article/details/gtlvzyhcin.html

[T05] Kotlin：when 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyfahecd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hongshengwenyu.top/Article/details/gteketvolf.html

[T06] Kotlin：集合映射
来源：http://dali.smart0.xyz/Article/details/gtkytrqrny.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlarzosmj.html

[T07] Kotlin：集合过滤
来源：http://dali.fzhhl.top/Article/details/gtuufbifvq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258888.top/Article/details/gtfhenicxa.html

[T08] Kotlin：数据类
来源：http://dali.jyoumei.cn/Article/details/gtieervcvd.html

data class User(val name: String, val age: Int)
来源：http://dali.xylfe.cn/Article/details/gtqoyypkro.html

[T09] Kotlin：扩展函数
来源：http://dali.redwolf501.top/Article/details/gtsufvqcle.html

fun String.exclaim() = this + "!"
来源：http://dali.guowangkeji.top/Article/details/gtknsplgdx.html

[T10] Kotlin：默认参数
来源：http://dali.nanxuanxn.top/Article/details/gthwctqrik.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj202588.top/Article/details/gtwndhzykb.html

[T11] Kotlin：协程
来源：http://dali.yangfankeji.com/Article/details/gtfsvbyhdl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nanxuanxn.top/Article/details/gtreqymyeq.html

[T12] Kotlin：解构声明
来源：http://dali.gaohongyu789.top/Article/details/gtordsxibe.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtnrkparzt.html

[T13] Kotlin：只读 Map
来源：http://dali.redwolf501.top/Article/details/gtzalwafqu.html

val m = mapOf("a" to 1)
来源：http://dali.daxiang520.top/Article/details/gtxssvdivv.html

[T14] Kotlin：循环
来源：http://dali.jqgufenzy.top/Article/details/gtawqvrywg.html

for (i in 1..10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoihxmlfg.html

[T15] Kotlin：接口
来源：http://dali.zhongyouzk.top/Article/details/gtywvjiyfi.html

interface Shape { fun area(): Double }
来源：http://dali.chenjidiqi.icu/Article/details/gtegjlxqum.html

[T16] Swift：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gttjuyrzxg.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtlwpuwwjl.html

[T17] Swift：变量与常量
来源：http://dali.yangfankeji.com/Article/details/gtxdutdsnm.html

var a = 1;  let b = 2
来源：http://dali.havefunace.top/Article/details/gttrqlyvpm.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtfgrgdnkm.html

"值: \(b)"
来源：http://dali.feifeiyinyue.top/Article/details/gtyxqrrmse.html

[T19] Swift：可选绑定
来源：http://dali.zdqjudy.top/Article/details/gtjdovtlcf.html

if let n = opt { print(n) }
来源：http://dali.nanxuanxn.top/Article/details/gthnoyuswr.html

[T20] Swift：数组操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzpzqexi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.meibo888.top/Article/details/gtaynumieo.html

[T21] Swift：遍历
来源：http://dali.wangdashe.top/Article/details/gtblldmpws.html

for x in a { print(x) }
来源：http://dali.hywenlv.cn/Article/details/gtlldzqfzb.html

[T22] Swift：字典
来源：http://dali.shzxlz.cn/Article/details/gttvyjdkgu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258888.top/Article/details/gtrwqsrrzb.html

[T23] Swift：函数
来源：http://dali.guowangkeji.top/Article/details/gtlppsupfr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gtyrbakftm.html

[T24] Swift：闭包
来源：http://dali.aibaodan.cn/Article/details/gtaiccvhkp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ybcxt.top/Article/details/gtougecsqh.html

[T25] Swift：结构体
来源：http://dali.ydzc1.top/Article/details/gtgzqvhvil.html

struct P { var x: Int }
来源：http://dali.jlsjyb.cn/Article/details/gtasqrrqcy.html

[T26] Swift：类与重写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcphktsqh.html

class A: Base { override func f() {} }
来源：http://dali.jinqigfzy.top/Article/details/gttkxcoepj.html

[T27] Swift：错误处理
来源：http://dali.sufxvd.cn/Article/details/gtcxlonmgj.html

do { try f() } catch { print(error) }
来源：http://dali.havefunace.top/Article/details/gtqhxbgnsn.html

[T28] Swift：枚举
来源：http://dali.guowangkeji.top/Article/details/gtnbdgqtjw.html

enum Color { case red, green }
来源：http://dali.daxiang520.top/Article/details/gtikhsvrxj.html

[T29] Swift：guard 提前返回
来源：http://dali.tianlin.xyz/Article/details/gtvbdaddhb.html

guard let x = opt else { return }
来源：http://dali.wangdashe.top/Article/details/gtivzoetgy.html

[T30] Swift：协议
来源：http://dali.yueranfly.top/Article/details/gtnaobscft.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxinkj.top/Article/details/gtcghsyhhl.html

[T31] Lua：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtslhrqshh.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gtuydllrtu.html

[T32] Lua：局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gtobmyetzn.html

local a = 1
来源：http://dali.hfpthk.cn/Article/details/gtifkxcgmj.html

[T33] Lua：表（数组）
来源：http://dali.zhengqikj.top/Article/details/gtnmcubfwh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yanxiufei.cn/Article/details/gtcuftqgnj.html

[T34] Lua：遍历表
来源：http://dali.fengsongda.top/Article/details/gttprwzscp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhongyouzk.top/Article/details/gtomdesuoa.html

[T35] Lua：字典表
来源：http://dali.yongpay.top/Article/details/gtalzcmmqj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cdnleiting.top/Article/details/gtqqdrvczq.html

[T36] Lua：函数
来源：http://dali.ydzc1.top/Article/details/gttqywwdkw.html

function add(a, b) return a + b end
来源：http://dali.andypj.xyz/Article/details/gtzoqargmi.html

[T37] Lua：字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gthkyxffmz.html

"a" .. "b"
来源：http://dali.yj20258888.top/Article/details/gtewspokni.html

[T38] Lua：条件
来源：http://dali.shangyingyoupin.top/Article/details/gtpijifowy.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjybkifzm.html

[T39] Lua：模式匹配
来源：http://dali.hnqzz.top/Article/details/gtffbqpcpq.html

string.find(s, "%d+")
来源：http://dali.gotoacloud.top/Article/details/gtpksvrbcw.html

[T40] Lua：元表
来源：http://dali.cucudq.cn/Article/details/gtnaupijed.html

setmetatable({}, { __index = base })
来源：http://dali.yuxming.cn/Article/details/gtvwijaqxe.html

[T41] Perl：Hello World
来源：http://dali.tanke756.top/Article/details/gtpciidpuv.html

print "Hello\n";
来源：http://dali.haohaochexian.top/Article/details/gtycpdibrr.html

[T42] Perl：变量类型
来源：http://dali.jinqigufen.top/Article/details/gtumlphcew.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.birdmap.top/Article/details/gtdptofwef.html

[T43] Perl：字符串插值
来源：http://dali.yonumen.top/Article/details/gtfzsjobwr.html

"值: $a"
来源：http://dali.kuanghao11.cn/Article/details/gtovctplkt.html

[T44] Perl：条件
来源：http://dali.yangfankeji.com/Article/details/gtxvtxpelg.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigufen.top/Article/details/gtzuvredlg.html

[T45] Perl：数组遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtqmsheirg.html

for my $x (@arr) { print $x; }
来源：http://dali.nanxuanxn.top/Article/details/gtkgbqggpm.html

[T46] Perl：哈希操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftwjbuqb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ppjwa.cn/Article/details/gtxbuqvezh.html

[T47] Perl：正则捕获
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbaxawvrw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrdzjostx.html

[T48] Perl：正则替换
来源：http://dali.gaohongyu789.top/Article/details/gtalmlpeze.html

$s =~ s/old/new/g;
来源：http://dali.hywenlv.cn/Article/details/gteeluqfei.html

[T49] Perl：函数
来源：http://dali.shangyingyoupin.top/Article/details/gtvoqxvvrd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbzwentvp.html

[T50] Perl：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gthrubfifm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aizwys.cn/Article/details/gtbpsztoss.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cashguo.top/Article/details/gtyktuviee.html

[T51] Scala：Hello World
来源：http://dali.bjfxy.top/Article/details/gtgjlzptzw.html

println("Hello")
来源：http://dali.wangdashe.top/Article/details/gtusvkbbrs.html

[T52] Scala：变量
来源：http://dali.yanxiufei.cn/Article/details/gthoqbmcox.html

val a = 1;  var b = 2
来源：http://dali.tanke756.top/Article/details/gteaeuigwb.html

[T53] Scala：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtehrtquzw.html

s"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gtgwigkpgj.html

[T54] Scala：集合映射
来源：http://dali.xinyue.icu/Article/details/gtkgvoshyb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcirbczwt.html

[T55] Scala：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gtjdwferte.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.mhx1999.top/Article/details/gtcjxnkjkh.html

[T56] Scala：样例类
来源：http://dali.snrcjt.cn/Article/details/gtlukjohed.html

case class User(name: String, age: Int)
来源：http://dali.ppjwa.cn/Article/details/gtkbvnuvtf.html

[T57] Scala：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gtrbijyzkw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.bjfxy.top/Article/details/gthrovlguu.html

[T58] Scala：函数定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqrdlovm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.birdmap.top/Article/details/gtgqtcjusq.html

[T59] Scala：循环
来源：http://dali.xuetiantiany.cn/Article/details/gteoeimiib.html

for (i <- 1 to 10) println(i)
来源：http://dali.quarkkingdee.top/Article/details/gtjutthjmb.html

[T60] Scala：折叠
来源：http://dali.bjfxy.top/Article/details/gtyarsmotr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.c1oappe.top/Article/details/gtdwdcfrqh.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtqqranuqa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.0kj1m.cn/Article/details/gtqcumtlaf.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gttsaqsmxn.html

[U01] Py：创建虚拟环境
来源：http://dali.yangfankeji.com/Article/details/gtaxxoisjg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jianghu66.top/Article/details/gtxwtcfwwd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sysykeji.top/Article/details/gtbxavdyap.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj202588.top/Article/details/gtsbaohfhq.html

[U03] Py：加载 .env 配置
来源：http://dali.yuanzhike.top/Article/details/gtvatoorln.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zdqjudy.top/Article/details/gtitizucis.html

[U04] Py：变量调试打印
来源：http://dali.ydzc1.top/Article/details/gtmjlruxot.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yueranfly.top/Article/details/gthdbxdrre.html

[U05] Py：列表去重且保序
来源：http://dali.shzxlz.cn/Article/details/gtcwvhfxnw.html

list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gtvozimnme.html

[U06] Py：合并两个字典
来源：http://dali.shzxlz.cn/Article/details/gtvqtmtgrt.html

{**a, **b}
来源：http://dali.jinghuilouyu.cn/Article/details/gtpizkfboa.html

[U07] Py：反转字典键值
来源：http://dali.redwolf501.top/Article/details/gtwwiayvuz.html

{v: k for k, v in d.items()}
来源：http://dali.xinyue.icu/Article/details/gtyikpwsse.html

[U08] Py：展平二维列表
来源：http://dali.pycfn.com/Article/details/gtmbsrbxhv.html

[y for x in nested for y in x]
来源：http://dali.svipenyu.cn/Article/details/gtubdzhjyv.html

[U09] Py：字典取最大值的键
来源：http://dali.svipenyu.cn/Article/details/gtxaqtmnuq.html

max(d, key=d.get)
来源：http://dali.nanxinkj.top/Article/details/gttzzbzagm.html

[U10] Py：按值排序字典
来源：http://dali.nanxuanxn.top/Article/details/gtuxiujldc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.guowangkeji.top/Article/details/gtzvpoxymk.html

[U11] Py：生成器表达式
来源：http://dali.hysaishi.cn/Article/details/gtcvvvvusy.html

(x * 2 for x in arr)
来源：http://dali.jiagoushi.top/Article/details/gtekegcyju.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cqqwz.cn/Article/details/gtzfnpacau.html

Counter(arr).most_common(3)
来源：http://dali.yuxming.cn/Article/details/gtakfpmniy.html

[U13] Py：固定长度队列
来源：http://dali.chenjidiqi.icu/Article/details/gtncpszzsp.html

deque(maxlen=10)
来源：http://dali.sysykeji.top/Article/details/gttabjjoax.html

[U14] Py：分组收集到列表
来源：http://dali.fzhhl.top/Article/details/gtweecwysd.html

defaultdict(list)
来源：http://dali.yj20258.top/Article/details/gtwqkzopks.html

[U15] Py：高精度计时
来源：http://dali.xuanzx.com/Article/details/gtynicbrho.html

t = time.perf_counter()
来源：http://dali.iojbl.cn/Article/details/gtbqkqqbsf.html

[U16] Py：命令行参数解析
来源：http://dali.jinghuilouyu.cn/Article/details/gteqieitql.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cheryme.top/Article/details/gthqwpvsku.html

[U17] Py：初始化日志
来源：http://dali.xinyue.icu/Article/details/gtdcblgacn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtweuqxkxk.html

[U18] Py：预编译正则
来源：http://dali.jinghuilouyu.cn/Article/details/gtyayijcrl.html

pat = re.compile(r"\d+")
来源：http://dali.andypj.xyz/Article/details/gtzgekbxsk.html

[U19] Py：正则替换带回调
来源：http://dali.sweek.top/Article/details/gtrcfssckf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cucudq.cn/Article/details/gtiuoykvze.html

[U20] Py：缓存函数结果
来源：http://dali.snrcjt.cn/Article/details/gtlwqhdwep.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hfpthk.cn/Article/details/gtqqggknyi.html

[U21] Py：自定义上下文管理器
来源：http://dali.wangdashe.top/Article/details/gtyofaqqbl.html

@contextlib.contextmanager
来源：http://dali.chenjidiqi.icu/Article/details/gtoayiaqcx.html

[U22] Py：矩阵转置
来源：http://dali.zdqjudy.top/Article/details/gtzmltjqlx.html

list(zip(*m))
来源：http://dali.fzhhl.top/Article/details/gttegvzugh.html

[U23] Py：分块读取大文件
来源：http://dali.nanxuanxn.top/Article/details/gtwplokcnt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shangyingyoupin.top/Article/details/gtlsuyfwxh.html

[U24] Py：路径操作
来源：http://dali.yueranfly.top/Article/details/gtsbebvkpt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gthgjyjwmw.html

[U25] Py：CSV 按字典读
来源：http://dali.redwolf501.top/Article/details/gtgfredkwv.html

csv.DictReader(f)
来源：http://dali.xylfe.cn/Article/details/gtjrgwounw.html

[U26] Py：并发下载
来源：http://dali.c1oappe.top/Article/details/gttpizgzup.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.bjfxy.top/Article/details/gtuwbrehpw.html

[U27] Py：异步 HTTP
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfucfbzs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zycfv.cn/Article/details/gtfqnfoppw.html

[U28] Py：类型别名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigjnwixw.html

UserId = int
来源：http://dali.xuetiantiany.cn/Article/details/gtfxpjnuxu.html

[U29] Py：属性校验
来源：http://dali.chenlongwang.top/Article/details/gtbnhfpddo.html

@property 与 @x.setter 配合
来源：http://dali.pycfn.com/Article/details/gtddicohdw.html

[U30] Py：数据类
来源：http://dali.tanke756.top/Article/details/gteprwdzel.html

@dataclass(slots=True)
来源：http://dali.yuanzhike.top/Article/details/gtruetoqut.html

[U31] Py：单测
来源：http://dali.yj20258888.top/Article/details/gtijdvyggx.html

python -m pytest -q
来源：http://dali.yj20258.top/Article/details/gtsnwwtcyu.html

[U32] Py：代码格式化
来源：http://dali.dashuyun.cn/Article/details/gtovvfguly.html

ruff format . && ruff check --fix .
来源：http://dali.9152youxi.cn/Article/details/gtirpjjesd.html

[U33] Py：打包发布
来源：http://dali.shanyushiyangtech.top/Article/details/gtumcbeipd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jianghu66.top/Article/details/gtaizjubwy.html

[U34] Py：判断编码
来源：http://dali.feifeiyinyue.top/Article/details/gtjhhdtayi.html

chardet.detect(raw)
来源：http://dali.tianlin.xyz/Article/details/gtupewnmcu.html

[U35] Py：发送邮件
来源：http://dali.haohaochexian.top/Article/details/gtsbcyipio.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gotoacloud.top/Article/details/gtipnvzxfq.html

[U36] Py：定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypnsjtpc.html

schedule.every(10).minutes.do(job)
来源：http://dali.wangshuangyany.cn/Article/details/gtbjiokszj.html

[U37] Py：读写 Excel
来源：http://dali.fengsongda.top/Article/details/gtlxcdahwr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.haohaochexian.top/Article/details/gtcwifjqcf.html

[U38] Py：获取脚本所在目录
来源：http://dali.yangfankeji.com/Article/details/gtjavzboje.html

Path(__file__).resolve().parent
来源：http://dali.hammf.cn/Article/details/gtorzsoxiv.html

[U39] Py：判断是否在交互环境
来源：http://dali.jlsjyb.cn/Article/details/gtsdvcqrxz.html

sys.stdout.isatty()
来源：http://dali.zhengqikj.top/Article/details/gtzoonyzkf.html

[U40] Py：打印到标准错误
来源：http://dali.aizwys.cn/Article/details/gtlkzhxuuc.html

print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gtartbembk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jqgfzy.top/Article/details/gtqufunidf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ydzc1.top/Article/details/gtfstxrtta.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.tanke756.top/Article/details/gtqpusneco.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jlsjyb.cn/Article/details/gttetnaqlt.html


<!-- 参考信息 -->