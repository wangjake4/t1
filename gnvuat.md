代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhiwuduotai.top/Article/details/gtywpqnjjv.html

[S25] C：内存拷贝
来源：http://dali.yueranfly.top/Article/details/gtstymgotc.html

memcpy(dst, src, n);
来源：http://dali.svipenyu.cn/Article/details/gtjssldeyl.html

[S26] C：内存清零
来源：http://dali.fzhhl.top/Article/details/gtxfjcapiw.html

memset(a, 0, sizeof a);
来源：http://dali.nanxuanxn.top/Article/details/gttmrtdnoo.html

[S27] C：定义常量
来源：http://dali.zycfv.cn/Article/details/gtlrnwrpak.html

const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtzyzmhtie.html

[S28] C：静态变量
来源：http://dali.xuanzx.com/Article/details/gtreuvflrz.html

static int counter = 0;
来源：http://dali.zdqjudy.top/Article/details/gtcydqhhok.html

[S29] C：变参函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczfyqoro.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hywenlv.cn/Article/details/gtwzszqxen.html

[S30] C：头文件保护
来源：http://dali.jianghu66.top/Article/details/gtdhipysho.html

#ifndef X_H
来源：http://dali.havefunace.top/Article/details/gtjaihnqau.html

#define X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfqphwhr.html

#endif
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrvcvuoj.html

[S31] C++：Hello World
来源：http://dali.havefunace.top/Article/details/gtdnmicxvs.html

#include <iostream>
来源：http://dali.yj20258888.top/Article/details/gtbxfoipog.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guowangkeji.top/Article/details/gtruliojxb.html

[S32] C++：字符串
来源：http://dali.cdnleiting.top/Article/details/gtdhdwtiqs.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgufenzy.top/Article/details/gtgcidhuhm.html

[S33] C++：vector 增删
来源：http://dali.zhiwuduotai.top/Article/details/gtlwtwjxas.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cdnleiting.top/Article/details/gtsjkkhiim.html

[S34] C++：遍历 vector
来源：http://dali.cheryme.top/Article/details/gtdzzqzibu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.c1oappe.top/Article/details/gtbtmgmbkv.html

[S35] C++：map
来源：http://dali.jianghu66.top/Article/details/gtzyehdmqd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtkcacstod.html

[S36] C++：unordered_map
来源：http://dali.guowangkeji.top/Article/details/gtottaogcv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtvqklypgk.html

[S37] C++：set
来源：http://dali.andypj.xyz/Article/details/gtzeqphvmi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hywenlv.cn/Article/details/gtzpjfkztn.html

[S38] C++：排序
来源：http://dali.ybcxt.top/Article/details/gtigtoezql.html

std::sort(v.begin(), v.end());
来源：http://dali.snrcjt.cn/Article/details/gtpwfkxwkd.html

[S39] C++：自定义比较器排序
来源：http://dali.shangyingyoupin.top/Article/details/gtijiwvxmc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aibaodan.cn/Article/details/gtnxbucoua.html

[S40] C++：查找元素
来源：http://dali.cqqwz.cn/Article/details/gtmtslficx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.haohaochexian.top/Article/details/gttsxpalgd.html

[S41] C++：类与构造函数
来源：http://dali.sxryk.cn/Article/details/gtnqkbgskl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jyoumei.cn/Article/details/gtaucggzlx.html

[S42] C++：继承与虚函数
来源：http://dali.fengsongda.top/Article/details/gtlabkgelf.html

class B : public Base { public: void f() override {} };
来源：http://dali.ppjwa.cn/Article/details/gtdumcncej.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxpzfxox.html

auto p = std::make_unique<int>(5);
来源：http://dali.jlsjyb.cn/Article/details/gtugpedijy.html

[S44] C++：引用传参
来源：http://dali.feifeiyinyue.top/Article/details/gtpxdxljgy.html

void inc(int &x) { ++x; }
来源：http://dali.zdqjudy.top/Article/details/gtabhupmlj.html

[S45] C++：lambda
来源：http://dali.aibaodan.cn/Article/details/gttjoipyve.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangdashe.top/Article/details/gtuvmnomeo.html

[S46] C++：函数模板
来源：http://dali.dianchejie.cn/Article/details/gtumramfum.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gtteuuzmsd.html

[S47] C++：结构化绑定遍历
来源：http://dali.xziqi.cn/Article/details/gtabknsgyl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangshuangyany.cn/Article/details/gtuobjqeon.html

[S48] C++：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gtoidabdny.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hnqzz.top/Article/details/gtccqtmrhj.html

while (std::getline(in, line)) { }
来源：http://dali.wangdashe.top/Article/details/gtzgydspxo.html

[S49] C++：写文件
来源：http://dali.havefunace.top/Article/details/gtvalzkbjh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yanxiufei.cn/Article/details/gtouehsbgg.html

[S50] C++：格式化数字
来源：http://dali.yvedp.cn/Article/details/gtekeizsru.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsxbtfus.html

[S51] C++：显式类型转换
来源：http://dali.yongpay.top/Article/details/gtvjfzznhx.html

static_cast<double>(a) / b
来源：http://dali.smart0.xyz/Article/details/gtzdpqpdro.html

[S52] C++：const 与 noexcept
来源：http://dali.9152youxi.cn/Article/details/gtitbjgsyq.html

int size() const noexcept { return n_; }
来源：http://dali.hfpthk.cn/Article/details/gtbeswvhtb.html

[S53] C++：移动语义
来源：http://dali.yonumen.top/Article/details/gtvefcpnbj.html

std::vector<int> w = std::move(v);
来源：http://dali.kuanghao11.cn/Article/details/gtasvuigqv.html

[S54] C++：异常处理
来源：http://dali.shangyingyoupin.top/Article/details/gtafoqhyyv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtlmghkmsy.html

[S55] C++：结构化绑定
来源：http://dali.jlsjyb.cn/Article/details/gtxskltmfw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gteojoiqea.html

[S56] C++：optional
来源：http://dali.snrcjt.cn/Article/details/gtgqqjjkfe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfniylxuv.html

[S57] C++：编译期常量
来源：http://dali.kuanghao11.cn/Article/details/gtuhzgwmil.html

constexpr int N = 10;
来源：http://dali.yuanzhike.top/Article/details/gtxkpjpcdw.html

[S58] C++：命名空间
来源：http://dali.mhx1999.top/Article/details/gtdajahzxz.html

namespace ns { int f() { return 1; } }
来源：http://dali.ybcxt.top/Article/details/gttvyqelkz.html

[S59] C++：静态断言
来源：http://dali.zhixingplan.top/Article/details/gtlmdcaiqp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cqqwz.cn/Article/details/gtphlmbygk.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlbrgwms.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcjcfazi.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtlhfmkqid.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tanke756.top/Article/details/gtmscqkaqs.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gthzddquwa.html

[T01] Kotlin：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtolyzctyj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtqjoadkex.html

[T02] Kotlin：变量
来源：http://dali.hnqzz.top/Article/details/gtzsthgdyb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangdashe.top/Article/details/gtnifnfzgr.html

[T03] Kotlin：字符串模板
来源：http://dali.pengpengdd.cyou/Article/details/gtwnecmajr.html

"值: $b"
来源：http://dali.hongshengwenyu.top/Article/details/gtvzkayzzi.html

[T04] Kotlin：空安全
来源：http://dali.mhx1999.top/Article/details/gtgfvlptob.html

val n: String? = null;  n?.length
来源：http://dali.quarkkingdee.top/Article/details/gtolyyjqmh.html

[T05] Kotlin：when 表达式
来源：http://dali.aibaodan.cn/Article/details/gtzbubsrdo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gogol.net.cn/Article/details/gtpzwjgrrb.html

[T06] Kotlin：集合映射
来源：http://dali.jiagoushi.top/Article/details/gtkdpaskju.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtniyliukb.html

[T07] Kotlin：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gtrafvxtny.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj202588.top/Article/details/gtvbhatipq.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gtxzvmfgke.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258888.top/Article/details/gtoqbetynw.html

[T09] Kotlin：扩展函数
来源：http://dali.feifeiyinyue.top/Article/details/gtzepyjyvl.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxinkj.top/Article/details/gtfluwojyb.html

[T10] Kotlin：默认参数
来源：http://dali.ehwqpu.com/Article/details/gtdhhzfsko.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnqzz.top/Article/details/gtnxqotrja.html

[T11] Kotlin：协程
来源：http://dali.wangdashe.top/Article/details/gtefwknpev.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xylfe.cn/Article/details/gtmygwtdhb.html

[T12] Kotlin：解构声明
来源：http://dali.daria6918.cn/Article/details/gtchoibrlg.html

val (a, b) = Pair(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtkdlxcnvg.html

[T13] Kotlin：只读 Map
来源：http://dali.yvedp.cn/Article/details/gttkjmnwjl.html

val m = mapOf("a" to 1)
来源：http://dali.nanxinkj.top/Article/details/gtbmxwihfh.html

[T14] Kotlin：循环
来源：http://dali.yanxiufei.cn/Article/details/gtlaurhajw.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtnzfvyoga.html

[T15] Kotlin：接口
来源：http://dali.xuetiantiany.cn/Article/details/gtoyfcxpqs.html

interface Shape { fun area(): Double }
来源：http://dali.zhiwuduotai.top/Article/details/gteiplwsrh.html

[T16] Swift：Hello World
来源：http://dali.hfpthk.cn/Article/details/gthqyswpkd.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtrtcipftr.html

[T17] Swift：变量与常量
来源：http://dali.kuanghao11.cn/Article/details/gtyuvqearz.html

var a = 1;  let b = 2
来源：http://dali.meibo888.top/Article/details/gtgbypeoec.html

[T18] Swift：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gthurgfphs.html

"值: \(b)"
来源：http://dali.cdnleiting.top/Article/details/gtivduktus.html

[T19] Swift：可选绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahrfteax.html

if let n = opt { print(n) }
来源：http://dali.yueranfly.top/Article/details/gtjxblbtet.html

[T20] Swift：数组操作
来源：http://dali.guannengcc.top/Article/details/gtyruwozqx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.snrcjt.cn/Article/details/gtrfhqzbrg.html

[T21] Swift：遍历
来源：http://dali.xziqi.cn/Article/details/gtdvrlrzus.html

for x in a { print(x) }
来源：http://dali.gzhubu.top/Article/details/gtutmtfucg.html

[T22] Swift：字典
来源：http://dali.yj20258888.top/Article/details/gtzosvlmpo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.guowangkeji.top/Article/details/gtcnhmytfp.html

[T23] Swift：函数
来源：http://dali.gaohongyu789.top/Article/details/gtzwqhjfsl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gotoacloud.top/Article/details/gtrzokdmlf.html

[T24] Swift：闭包
来源：http://dali.kuanghao11.cn/Article/details/gtlxrnkyvy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.0kj1m.cn/Article/details/gtcqymhyul.html

[T25] Swift：结构体
来源：http://dali.cqqwz.cn/Article/details/gtgjepgblr.html

struct P { var x: Int }
来源：http://dali.chenlongwang.top/Article/details/gtuxoaeloj.html

[T26] Swift：类与重写
来源：http://dali.xuetiantiany.cn/Article/details/gtxynknido.html

class A: Base { override func f() {} }
来源：http://dali.dashuyun.cn/Article/details/gtxnrwunzl.html

[T27] Swift：错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gtkcqevcnf.html

do { try f() } catch { print(error) }
来源：http://dali.pycfn.com/Article/details/gtefkjsbdz.html

[T28] Swift：枚举
来源：http://dali.andypj.xyz/Article/details/gtfdcynjry.html

enum Color { case red, green }
来源：http://dali.daria6918.cn/Article/details/gtuqtkzejt.html

[T29] Swift：guard 提前返回
来源：http://dali.wangshuangyany.cn/Article/details/gtvcijaelq.html

guard let x = opt else { return }
来源：http://dali.quarkkingdee.top/Article/details/gtsklyvxdk.html

[T30] Swift：协议
来源：http://dali.tanke756.top/Article/details/gthgjfsvkj.html

protocol Shape { func area() -> Double }
来源：http://dali.gzhubu.top/Article/details/gtxcfytnrf.html

[T31] Lua：Hello World
来源：http://dali.xylfe.cn/Article/details/gtnpueowvj.html

print("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtylmsedcr.html

[T32] Lua：局部变量
来源：http://dali.jlsjyb.cn/Article/details/gtorpptsms.html

local a = 1
来源：http://dali.fzhhl.top/Article/details/gtabaoipii.html

[T33] Lua：表（数组）
来源：http://dali.aibaodan.cn/Article/details/gtnxgkilbc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cashguo.top/Article/details/gtwmmtmsiv.html

[T34] Lua：遍历表
来源：http://dali.pycfn.com/Article/details/gtmujdxath.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gtrwqsqxny.html

[T35] Lua：字典表
来源：http://dali.andypj.xyz/Article/details/gtwjosllgi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtrgcmgdvh.html

[T36] Lua：函数
来源：http://dali.nanxinkj.top/Article/details/gtjdgtuhew.html

function add(a, b) return a + b end
来源：http://dali.meibo888.top/Article/details/gtmzxzgitz.html

[T37] Lua：字符串拼接
来源：http://dali.redwolf501.top/Article/details/gtjyxsqsef.html

"a" .. "b"
来源：http://dali.nwbrower.top/Article/details/gtlpshhloq.html

[T38] Lua：条件
来源：http://dali.zhiwuduotai.top/Article/details/gtrptqruxh.html

if x > 0 then print("正") end
来源：http://dali.sweek.top/Article/details/gtqoeczguk.html

[T39] Lua：模式匹配
来源：http://dali.316326.xyz/Article/details/gtyrowyqxk.html

string.find(s, "%d+")
来源：http://dali.yongpay.top/Article/details/gtkwjqlpgn.html

[T40] Lua：元表
来源：http://dali.aibaodan.cn/Article/details/gtuhouzenx.html

setmetatable({}, { __index = base })
来源：http://dali.yj20258.top/Article/details/gtftqhumzi.html

[T41] Perl：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtsyojizld.html

print "Hello\n";
来源：http://dali.hnqzz.top/Article/details/gtydxjskgg.html

[T42] Perl：变量类型
来源：http://dali.jlsjyb.cn/Article/details/gtpswswhvy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxuanxn.top/Article/details/gtpbdsdcvo.html

[T43] Perl：字符串插值
来源：http://dali.yongpay.top/Article/details/gtdxidywnm.html

"值: $a"
来源：http://dali.daria6918.cn/Article/details/gtizohpdin.html

[T44] Perl：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzrmcbku.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gtkcsowlof.html

[T45] Perl：数组遍历
来源：http://dali.yj20258888.top/Article/details/gtqbcxodve.html

for my $x (@arr) { print $x; }
来源：http://dali.birdmap.top/Article/details/gtvqbilabn.html

[T46] Perl：哈希操作
来源：http://dali.chenjidiqi.icu/Article/details/gtzuvqbmil.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.redwolf501.top/Article/details/gtsamqjiwc.html

[T47] Perl：正则捕获
来源：http://dali.yonumen.top/Article/details/gtotfdjktf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangdashe.top/Article/details/gtzuexckae.html

[T48] Perl：正则替换
来源：http://dali.havefunace.top/Article/details/gtjboldjyh.html

$s =~ s/old/new/g;
来源：http://dali.zdqjudy.top/Article/details/gtpzhyyjgx.html

[T49] Perl：函数
来源：http://dali.zhoulong.xyz/Article/details/gtgqxsmufu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gtkovgnnuj.html

[T50] Perl：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtensqdtzo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvjzmppe.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tianlin.xyz/Article/details/gttgrqldvw.html

[T51] Scala：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtagvyiewn.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtkafzjlpr.html

[T52] Scala：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgsnnrlm.html

val a = 1;  var b = 2
来源：http://dali.jqgfzy.top/Article/details/gtwvspqodq.html

[T53] Scala：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzxdrsmn.html

s"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gtddprzdyz.html

[T54] Scala：集合映射
来源：http://dali.jyoumei.cn/Article/details/gthbzdyijh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhixingplan.top/Article/details/gtxmvrhjgj.html

[T55] Scala：集合过滤
来源：http://dali.dashuyun.cn/Article/details/gtaaauqvrb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkkdcbye.html

[T56] Scala：样例类
来源：http://dali.chenjidiqi.icu/Article/details/gtzvzpvfkm.html

case class User(name: String, age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gtbkucisgu.html

[T57] Scala：模式匹配
来源：http://dali.yonumen.top/Article/details/gtwawjwwvn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhiwuduotai.top/Article/details/gtwnojkfmw.html

[T58] Scala：函数定义
来源：http://dali.fengsongda.top/Article/details/gtmyhcnqku.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jqgufenzy.top/Article/details/gtwqeamoqd.html

[T59] Scala：循环
来源：http://dali.wangdashe.top/Article/details/gtaidayruj.html

for (i <- 1 to 10) println(i)
来源：http://dali.birdmap.top/Article/details/gtgsfskicg.html

[T60] Scala：折叠
来源：http://dali.cheryme.top/Article/details/gtnqfcmqku.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.guowangkeji.top/Article/details/gtsdpsaytr.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtgmtjypah.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ehwqpu.com/Article/details/gtxidmmwqf.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtckergtfk.html

[U01] Py：创建虚拟环境
来源：http://dali.ydzc1.top/Article/details/gtmroinvnd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cucudq.cn/Article/details/gtzaabiwhj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cheryme.top/Article/details/gtqeuxxixf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daria6918.cn/Article/details/gtoharvvrp.html

[U03] Py：加载 .env 配置
来源：http://dali.shzxlz.cn/Article/details/gtwsfcklvb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.0kj1m.cn/Article/details/gtwlqozgqc.html

[U04] Py：变量调试打印
来源：http://dali.zhongyouzk.top/Article/details/gtyclpozet.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenlongwang.top/Article/details/gtsrynobbe.html

[U05] Py：列表去重且保序
来源：http://dali.daxiang520.top/Article/details/gtzbleohvk.html

list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikkqipvw.html

[U06] Py：合并两个字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxncxiyn.html

{**a, **b}
来源：http://dali.yuanzhike.top/Article/details/gtpzruynkz.html

[U07] Py：反转字典键值
来源：http://dali.nanxinkj.top/Article/details/gtsamcgpwo.html

{v: k for k, v in d.items()}
来源：http://dali.bjfxy.top/Article/details/gtmihjhqgb.html

[U08] Py：展平二维列表
来源：http://dali.shuidangran.top/Article/details/gtqpjbzxzc.html

[y for x in nested for y in x]
来源：http://dali.sufxvd.cn/Article/details/gtjqzcgvin.html

[U09] Py：字典取最大值的键
来源：http://dali.chenzaomai.com/Article/details/gtkqyuygwq.html

max(d, key=d.get)
来源：http://dali.cashguo.top/Article/details/gtueldngsq.html

[U10] Py：按值排序字典
来源：http://dali.zdqjudy.top/Article/details/gtrkwhxcop.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ppjwa.cn/Article/details/gtkaibjcog.html

[U11] Py：生成器表达式
来源：http://dali.9152youxi.cn/Article/details/gtmywaabty.html

(x * 2 for x in arr)
来源：http://dali.svipenyu.cn/Article/details/gtesffsyap.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.meibo888.top/Article/details/gtgezaerir.html

Counter(arr).most_common(3)
来源：http://dali.hywenlv.cn/Article/details/gtxmmxtzzd.html

[U13] Py：固定长度队列
来源：http://dali.bjfxy.top/Article/details/gtrbarrcti.html

deque(maxlen=10)
来源：http://dali.jianghu66.top/Article/details/gttbmldgfi.html

[U14] Py：分组收集到列表
来源：http://dali.andypj.xyz/Article/details/gtjyjofusd.html

defaultdict(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfyacvhf.html

[U15] Py：高精度计时
来源：http://dali.yonumen.top/Article/details/gtmuxtkowr.html

t = time.perf_counter()
来源：http://dali.hammf.cn/Article/details/gtwtvjjujr.html

[U16] Py：命令行参数解析
来源：http://dali.cashguo.top/Article/details/gtohavzoex.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.c1oappe.top/Article/details/gtsmdcknwf.html

[U17] Py：初始化日志
来源：http://dali.shuidangran.top/Article/details/gtlnzhuiin.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.haohaochexian.top/Article/details/gtjlvoejez.html

[U18] Py：预编译正则
来源：http://dali.tanke756.top/Article/details/gtrymntwxi.html

pat = re.compile(r"\d+")
来源：http://dali.haohaochexian.top/Article/details/gtwlilfexd.html

[U19] Py：正则替换带回调
来源：http://dali.chenzaomai.com/Article/details/gtjtjoufoh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhixingplan.top/Article/details/gttthrpbgl.html

[U20] Py：缓存函数结果
来源：http://dali.quarkkingdee.top/Article/details/gtoygraljw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinghuilouyu.cn/Article/details/gtelkapdzr.html

[U21] Py：自定义上下文管理器
来源：http://dali.jlsjyb.cn/Article/details/gtepztxopd.html

@contextlib.contextmanager
来源：http://dali.hammf.cn/Article/details/gtwaalapuc.html

[U22] Py：矩阵转置
来源：http://dali.yuxming.cn/Article/details/gtcwxulmzf.html

list(zip(*m))
来源：http://dali.meibo888.top/Article/details/gtjnnqlvtq.html

[U23] Py：分块读取大文件
来源：http://dali.pycfn.com/Article/details/gtkcjjjktq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ybcxt.top/Article/details/gtecdusjvr.html

[U24] Py：路径操作
来源：http://dali.xinyue.icu/Article/details/gtyllipvtt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gtfkjfiwgv.html

[U25] Py：CSV 按字典读
来源：http://dali.nanxuanxn.top/Article/details/gtbtjgktiy.html

csv.DictReader(f)
来源：http://dali.cqqwz.cn/Article/details/gtakwgmrpq.html

[U26] Py：并发下载
来源：http://dali.tianlin.xyz/Article/details/gtyvljxaig.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigufen.top/Article/details/gttlulpfju.html

[U27] Py：异步 HTTP
来源：http://dali.hywenlv.cn/Article/details/gtlijxzdia.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xinyue.icu/Article/details/gtlwktnrfu.html

[U28] Py：类型别名
来源：http://dali.kuanghao11.cn/Article/details/gtdhmriknv.html

UserId = int
来源：http://dali.gaohongyu789.top/Article/details/gtpovymexj.html

[U29] Py：属性校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdfbzlkb.html

@property 与 @x.setter 配合
来源：http://dali.yongpay.top/Article/details/gtpwkzhkmm.html

[U30] Py：数据类
来源：http://dali.ehwqpu.com/Article/details/gtsmzkloet.html

@dataclass(slots=True)
来源：http://dali.iojbl.cn/Article/details/gtskypsqty.html

[U31] Py：单测
来源：http://dali.gzhubu.top/Article/details/gtzoqcemvx.html

python -m pytest -q
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykjdqykf.html

[U32] Py：代码格式化
来源：http://dali.zycfv.cn/Article/details/gtldrvyygz.html

ruff format . && ruff check --fix .
来源：http://dali.fengsongda.top/Article/details/gtmvpmyghm.html

[U33] Py：打包发布
来源：http://dali.daria6918.cn/Article/details/gtujkzhfih.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jqgufenzy.top/Article/details/gtwnagomvm.html

[U34] Py：判断编码
来源：http://dali.yanxiufei.cn/Article/details/gttukteqqi.html

chardet.detect(raw)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteirintis.html

[U35] Py：发送邮件
来源：http://dali.feifeiyinyue.top/Article/details/gtfnqabnoa.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jqgfzy.top/Article/details/gtejgskqgo.html

[U36] Py：定时任务
来源：http://dali.gzhubu.top/Article/details/gtdefictqq.html

schedule.every(10).minutes.do(job)
来源：http://dali.xinyue.icu/Article/details/gtkhxtqlhy.html

[U37] Py：读写 Excel
来源：http://dali.yvedp.cn/Article/details/gtlyhsxqot.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.aizwys.cn/Article/details/gtfjabvslr.html

[U38] Py：获取脚本所在目录
来源：http://dali.cqqwz.cn/Article/details/gtiaphszfr.html

Path(__file__).resolve().parent
来源：http://dali.yvedp.cn/Article/details/gtmyaopbik.html

[U39] Py：判断是否在交互环境
来源：http://dali.xuetiantiany.cn/Article/details/gtsbkkpqtr.html

sys.stdout.isatty()
来源：http://dali.xuetiantiany.cn/Article/details/gtbxxsasoq.html

[U40] Py：打印到标准错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjllurug.html

print("err", file=sys.stderr)
来源：http://dali.gogol.net.cn/Article/details/gtykpfsnkm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.daxiang520.top/Article/details/gtruivlbgk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yonumen.top/Article/details/gtvknckdul.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cdnleiting.top/Article/details/gtuecqywhh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.svipenyu.cn/Article/details/gtoajyuyul.html

[U43] PHP：声明命名空间
来源：http://dali.yuanzhike.top/Article/details/gtvpgariwc.html

namespace App\Http;
来源：http://dali.chenzaomai.com/Article/details/gtplwodtew.html

[U44] PHP：开启严格类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gthirzmmcn.html

declare(strict_types=1);
来源：http://dali.zhixingplan.top/Article/details/gtmywnqott.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xylfe.cn/Article/details/gtafdgxsrn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gttfqeqzwr.html

[U46] PHP：可空类型
来源：http://dali.yvedp.cn/Article/details/gtgbgzwwfc.html

?string $name = null
来源：http://dali.zhoulong.xyz/Article/details/gteqthilhh.html

[U47] PHP：联合类型
来源：http://dali.wangdashe.top/Article/details/gtvpxxfacp.html

int|string $id
来源：http://dali.hongshengwenyu.top/Article/details/gtxitgdjid.html

[U48] PHP：纯枚举
来源：http://dali.jyoumei.cn/Article/details/gtfcewpxpb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.kuanghao11.cn/Article/details/gtttcmznrn.html


<!-- 参考信息 -->