代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gtkscgzkvo.html

[S21] C：字符类别判断
来源：http://dali.ehwqpu.com/Article/details/gtyhytwxuh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pengpengdd.cyou/Article/details/gtepufiyja.html

[S22] C：字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzghykpvc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcapaemcd.html

[S23] C：随机数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnandpfa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tanke756.top/Article/details/gtejvfmtae.html

[S24] C：获取本地时间
来源：http://dali.daria6918.cn/Article/details/gtbsnqbtkn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hfpthk.cn/Article/details/gtmajhfenv.html

[S25] C：内存拷贝
来源：http://dali.316326.xyz/Article/details/gtxwlatuef.html

memcpy(dst, src, n);
来源：http://dali.feifeiyinyue.top/Article/details/gtzbnnuwmr.html

[S26] C：内存清零
来源：http://dali.shuidangran.top/Article/details/gtdpnuzmer.html

memset(a, 0, sizeof a);
来源：http://dali.iojbl.cn/Article/details/gtdoszepmu.html

[S27] C：定义常量
来源：http://dali.316326.xyz/Article/details/gtfgkxplxk.html

const double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtmgyhikom.html

[S28] C：静态变量
来源：http://dali.guannengcc.top/Article/details/gtdfteuxhl.html

static int counter = 0;
来源：http://dali.nanxinkj.top/Article/details/gtxqmohfow.html

[S29] C：变参函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgoyycrfd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenlongwang.top/Article/details/gtswvubgkb.html

[S30] C：头文件保护
来源：http://dali.quarkkingdee.top/Article/details/gtojyazutr.html

#ifndef X_H
来源：http://dali.feifeiyinyue.top/Article/details/gtffcpoofo.html

#define X_H
来源：http://dali.316326.xyz/Article/details/gtbbhxcgwv.html

#endif
来源：http://dali.hysaishi.cn/Article/details/gtkyedbjyh.html

[S31] C++：Hello World
来源：http://dali.nwbrower.top/Article/details/gtexlxzvar.html

#include <iostream>
来源：http://dali.zycfv.cn/Article/details/gtginbgcvo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xinyue.icu/Article/details/gttgdacftp.html

[S32] C++：字符串
来源：http://dali.dianchejie.cn/Article/details/gtjincvgyz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhiwuduotai.top/Article/details/gtpyonnyrv.html

[S33] C++：vector 增删
来源：http://dali.0kj1m.cn/Article/details/gtaegdxfwi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hywenlv.cn/Article/details/gtgxdjvcby.html

[S34] C++：遍历 vector
来源：http://dali.guowangkeji.top/Article/details/gtokbiyrno.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xylfe.cn/Article/details/gtkinkzzzb.html

[S35] C++：map
来源：http://dali.chenzaomai.com/Article/details/gtwygbmvwf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtiwqzomwu.html

[S36] C++：unordered_map
来源：http://dali.jyoumei.cn/Article/details/gtsmpeergx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtioigvtiq.html

[S37] C++：set
来源：http://dali.zdqjudy.top/Article/details/gtuldkmzdt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenlongwang.top/Article/details/gtqvdsbsih.html

[S38] C++：排序
来源：http://dali.nwbrower.top/Article/details/gtzscjjmti.html

std::sort(v.begin(), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gteyqctvqh.html

[S39] C++：自定义比较器排序
来源：http://dali.pengpengdd.cyou/Article/details/gtcelshbqh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ehwqpu.com/Article/details/gthyjyqwhc.html

[S40] C++：查找元素
来源：http://dali.birdmap.top/Article/details/gtkzgvthey.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangdashe.top/Article/details/gtrfgeltha.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gtckvlqjvw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yonumen.top/Article/details/gtbyvjwiub.html

[S42] C++：继承与虚函数
来源：http://dali.daxiang520.top/Article/details/gtmhhrwolf.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenzaomai.com/Article/details/gtbnknzmvj.html

[S43] C++：智能指针
来源：http://dali.quarkkingdee.top/Article/details/gtxxbqywrz.html

auto p = std::make_unique<int>(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbsqxqfyz.html

[S44] C++：引用传参
来源：http://dali.yj20258.top/Article/details/gtbhdroice.html

void inc(int &x) { ++x; }
来源：http://dali.jianghu66.top/Article/details/gtnguxyduu.html

[S45] C++：lambda
来源：http://dali.bjfxy.top/Article/details/gturfznwuz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ehwqpu.com/Article/details/gtlrifggvb.html

[S46] C++：函数模板
来源：http://dali.yuxming.cn/Article/details/gtoeqwbdoi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhixingplan.top/Article/details/gtzlbmgwhn.html

[S47] C++：结构化绑定遍历
来源：http://dali.kuanghao11.cn/Article/details/gtfqohutiu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.havefunace.top/Article/details/gtblgnqwlv.html

[S48] C++：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtbbuvrnef.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangdashe.top/Article/details/gtzisokxgr.html

while (std::getline(in, line)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtoqhyljhl.html

[S49] C++：写文件
来源：http://dali.snrcjt.cn/Article/details/gtrbxbwsfb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.haohaochexian.top/Article/details/gtzovmhqud.html

[S50] C++：格式化数字
来源：http://dali.meibo888.top/Article/details/gtdecgwabl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbeblgdk.html

[S51] C++：显式类型转换
来源：http://dali.sxryk.cn/Article/details/gtxhszdmuk.html

static_cast<double>(a) / b
来源：http://dali.chenjidiqi.icu/Article/details/gtaqjytosb.html

[S52] C++：const 与 noexcept
来源：http://dali.nwbrower.top/Article/details/gtvhpxgpyk.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gtyullhddt.html

[S53] C++：移动语义
来源：http://dali.chenjidiqi.icu/Article/details/gtmtxluytj.html

std::vector<int> w = std::move(v);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitnbknvh.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkruzupef.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zdqjudy.top/Article/details/gtlejxqcqk.html

[S55] C++：结构化绑定
来源：http://dali.snrcjt.cn/Article/details/gtuqvfvqgh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fengsongda.top/Article/details/gtudifxzux.html

[S56] C++：optional
来源：http://dali.hnxiangtu.top/Article/details/gtblelnvyy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqcbnarx.html

[S57] C++：编译期常量
来源：http://dali.chenlongwang.top/Article/details/gtzsdffnpz.html

constexpr int N = 10;
来源：http://dali.dianchejie.cn/Article/details/gtpwiarfzm.html

[S58] C++：命名空间
来源：http://dali.0kj1m.cn/Article/details/gtptcdiaft.html

namespace ns { int f() { return 1; } }
来源：http://dali.gotoacloud.top/Article/details/gtzdiznigf.html

[S59] C++：静态断言
来源：http://dali.ivvv.top/Article/details/gtvvwgciyw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.andypj.xyz/Article/details/gtgrgdlger.html

[S60] C++：遍历并删除元素
来源：http://dali.hywenlv.cn/Article/details/gtlbcbqqeq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gtfbxeipoa.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtaoyhfjlk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.c1oappe.top/Article/details/gtzunrptnb.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtpwihatlk.html

[T01] Kotlin：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtddafgciq.html

println("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfkmkpab.html

[T02] Kotlin：变量
来源：http://dali.svipenyu.cn/Article/details/gtwmmxdcvt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhengqikj.top/Article/details/gtpelubjzy.html

[T03] Kotlin：字符串模板
来源：http://dali.ehwqpu.com/Article/details/gttzatjjmh.html

"值: $b"
来源：http://dali.cashguo.top/Article/details/gtayycflel.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gtjffwxira.html

val n: String? = null;  n?.length
来源：http://dali.jqgufenzy.top/Article/details/gtrskfmylg.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigfzy.top/Article/details/gtlpjeasfg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.0kj1m.cn/Article/details/gtfbpnmfhr.html

[T06] Kotlin：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gtrfbtmjcd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tian-w.cn/Article/details/gtvwukoags.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtdeyobgbd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlcssjrd.html

[T08] Kotlin：数据类
来源：http://dali.fzhhl.top/Article/details/gteghylves.html

data class User(val name: String, val age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzxhokcs.html

[T09] Kotlin：扩展函数
来源：http://dali.sysykeji.top/Article/details/gtucomneyr.html

fun String.exclaim() = this + "!"
来源：http://dali.fengsongda.top/Article/details/gtltiztwpw.html

[T10] Kotlin：默认参数
来源：http://dali.guannengcc.top/Article/details/gtnjpjfvbn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zycfv.cn/Article/details/gtiwwrbody.html

[T11] Kotlin：协程
来源：http://dali.nanxuanxn.top/Article/details/gttgjgsrsn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tian-w.cn/Article/details/gtvgrdfxqp.html

[T12] Kotlin：解构声明
来源：http://dali.xinyue.icu/Article/details/gtnohwnpwl.html

val (a, b) = Pair(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvunntnsr.html

[T13] Kotlin：只读 Map
来源：http://dali.hongshengwenyu.top/Article/details/gtnkokohqg.html

val m = mapOf("a" to 1)
来源：http://dali.jlsjyb.cn/Article/details/gtqzemvfcz.html

[T14] Kotlin：循环
来源：http://dali.sysykeji.top/Article/details/gtaeaficvc.html

for (i in 1..10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtllxfpwhc.html

[T15] Kotlin：接口
来源：http://dali.wangshuangyany.cn/Article/details/gtewcznuvd.html

interface Shape { fun area(): Double }
来源：http://dali.hongshengwenyu.top/Article/details/gtddgujqzs.html

[T16] Swift：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtofkfwmdp.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtdqdfdpkf.html

[T17] Swift：变量与常量
来源：http://dali.meibo888.top/Article/details/gtmyqehtkl.html

var a = 1;  let b = 2
来源：http://dali.haohaochexian.top/Article/details/gtxosfbidz.html

[T18] Swift：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwmqvmja.html

"值: \(b)"
来源：http://dali.tanke756.top/Article/details/gteaczemjv.html

[T19] Swift：可选绑定
来源：http://dali.cashguo.top/Article/details/gtabpmsuti.html

if let n = opt { print(n) }
来源：http://dali.dianchejie.cn/Article/details/gtwhafyzyv.html

[T20] Swift：数组操作
来源：http://dali.guannengcc.top/Article/details/gthpzxfpjh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.guannengcc.top/Article/details/gtnqvneslm.html

[T21] Swift：遍历
来源：http://dali.mhx1999.top/Article/details/gtyauhjker.html

for x in a { print(x) }
来源：http://dali.jinqigufen.top/Article/details/gtuniuwlen.html

[T22] Swift：字典
来源：http://dali.chenjidiqi.icu/Article/details/gtmtthfemv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtjkhbehgi.html

[T23] Swift：函数
来源：http://dali.jlsjyb.cn/Article/details/gtlywtyvke.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.meibo888.top/Article/details/gtrvsjcjfu.html

[T24] Swift：闭包
来源：http://dali.ydzc1.top/Article/details/gtfqnnkkxw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtebehwfpl.html

[T25] Swift：结构体
来源：http://dali.meibo888.top/Article/details/gtrhizpnwu.html

struct P { var x: Int }
来源：http://dali.pycfn.com/Article/details/gtbmcrhqsy.html

[T26] Swift：类与重写
来源：http://dali.guannengcc.top/Article/details/gteaqavuxm.html

class A: Base { override func f() {} }
来源：http://dali.xinyue.icu/Article/details/gtxasvqlyr.html

[T27] Swift：错误处理
来源：http://dali.dashuyun.cn/Article/details/gtgleifjvi.html

do { try f() } catch { print(error) }
来源：http://dali.yueranfly.top/Article/details/gtorrjgmvz.html

[T28] Swift：枚举
来源：http://dali.zhixingplan.top/Article/details/gtsymetxwu.html

enum Color { case red, green }
来源：http://dali.nwbrower.top/Article/details/gtppnpwyji.html

[T29] Swift：guard 提前返回
来源：http://dali.jqgfzy.top/Article/details/gthwnkhokj.html

guard let x = opt else { return }
来源：http://dali.havefunace.top/Article/details/gtygyhtgwk.html

[T30] Swift：协议
来源：http://dali.sysykeji.top/Article/details/gtanbuubmb.html

protocol Shape { func area() -> Double }
来源：http://dali.xuetiantiany.cn/Article/details/gtqttjaudm.html

[T31] Lua：Hello World
来源：http://dali.bjfxy.top/Article/details/gtadwzulfs.html

print("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwxcxotk.html

[T32] Lua：局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gtfhzpphgn.html

local a = 1
来源：http://dali.bjfxy.top/Article/details/gtuidsinnx.html

[T33] Lua：表（数组）
来源：http://dali.cashguo.top/Article/details/gtnmrgpbya.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jiagoushi.top/Article/details/gtakhgbbwq.html

[T34] Lua：遍历表
来源：http://dali.zdqjudy.top/Article/details/gtbkwrugca.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhongyouzk.top/Article/details/gtvopnojdi.html

[T35] Lua：字典表
来源：http://dali.dianchejie.cn/Article/details/gtwowzbwlf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shuidangran.top/Article/details/gtnskmovhg.html

[T36] Lua：函数
来源：http://dali.ivvv.top/Article/details/gtvcggxoyy.html

function add(a, b) return a + b end
来源：http://dali.guannengcc.top/Article/details/gthlpzyhxh.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258.top/Article/details/gtrwfotsdr.html

"a" .. "b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkebijpw.html

[T38] Lua：条件
来源：http://dali.zhengqikj.top/Article/details/gtckibjjgh.html

if x > 0 then print("正") end
来源：http://dali.havefunace.top/Article/details/gthsancqbl.html

[T39] Lua：模式匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtrklxewsv.html

string.find(s, "%d+")
来源：http://dali.ivvv.top/Article/details/gthovdlwpz.html

[T40] Lua：元表
来源：http://dali.snrcjt.cn/Article/details/gtfadgrzzm.html

setmetatable({}, { __index = base })
来源：http://dali.jinghuilouyu.cn/Article/details/gtjulsbpvh.html

[T41] Perl：Hello World
来源：http://dali.sxryk.cn/Article/details/gtvafpzqfh.html

print "Hello\n";
来源：http://dali.gaohongyu789.top/Article/details/gtfodvobfd.html

[T42] Perl：变量类型
来源：http://dali.yj20258.top/Article/details/gtfffigiql.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jlsjyb.cn/Article/details/gtdsfkwubo.html

[T43] Perl：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtnsckyriw.html

"值: $a"
来源：http://dali.nanxinkj.top/Article/details/gtcbnfpmsw.html

[T44] Perl：条件
来源：http://dali.hfpthk.cn/Article/details/gtmgxwdjsf.html

if ($a > 0) { print "正"; }
来源：http://dali.fzhhl.top/Article/details/gtdaocbcsm.html

[T45] Perl：数组遍历
来源：http://dali.cucudq.cn/Article/details/gtucaqemnm.html

for my $x (@arr) { print $x; }
来源：http://dali.jianghu66.top/Article/details/gtrpqaipmd.html

[T46] Perl：哈希操作
来源：http://dali.shzxlz.cn/Article/details/gtfjscxapy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.mhx1999.top/Article/details/gtibgtejsh.html

[T47] Perl：正则捕获
来源：http://dali.yonumen.top/Article/details/gtlqleekig.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.bjfxy.top/Article/details/gtktpydxyx.html

[T48] Perl：正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynxwxyor.html

$s =~ s/old/new/g;
来源：http://dali.ydzc1.top/Article/details/gtwfsmworr.html

[T49] Perl：函数
来源：http://dali.wangdashe.top/Article/details/gtlfffpjcu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtrhfcewep.html

[T50] Perl：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtfytqfhqg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jiagoushi.top/Article/details/gtpvusfgxf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cdnleiting.top/Article/details/gtfuaisuoq.html

[T51] Scala：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtexbrjacl.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gtitzyoksk.html

[T52] Scala：变量
来源：http://dali.iojbl.cn/Article/details/gtxrfdstfl.html

val a = 1;  var b = 2
来源：http://dali.hnxiangtu.top/Article/details/gtvjxtgmgs.html

[T53] Scala：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtmubbdocn.html

s"值: $b"
来源：http://dali.yueranfly.top/Article/details/gtmwfqyeff.html

[T54] Scala：集合映射
来源：http://dali.fengsongda.top/Article/details/gtwkdeixfk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dashuyun.cn/Article/details/gtiwopwyjw.html

[T55] Scala：集合过滤
来源：http://dali.316326.xyz/Article/details/gtczrehuel.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hnqzz.top/Article/details/gtkjtelmoo.html

[T56] Scala：样例类
来源：http://dali.quarkkingdee.top/Article/details/gtwieumyrs.html

case class User(name: String, age: Int)
来源：http://dali.tanke756.top/Article/details/gtuuknqatn.html

[T57] Scala：模式匹配
来源：http://dali.aibaodan.cn/Article/details/gtgoyxufyh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.redwolf501.top/Article/details/gtehjnbfpe.html

[T58] Scala：函数定义
来源：http://dali.aibaodan.cn/Article/details/gtffzrgyaq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cucudq.cn/Article/details/gtezcnscoa.html

[T59] Scala：循环
来源：http://dali.hysaishi.cn/Article/details/gtdgxwmvxb.html

for (i <- 1 to 10) println(i)
来源：http://dali.hongshengwenyu.top/Article/details/gtruwwwezz.html

[T60] Scala：折叠
来源：http://dali.nanxuanxn.top/Article/details/gttanlaapb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yanxiufei.cn/Article/details/gtuqxssaur.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtwnusxgvh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuxming.cn/Article/details/gtbftvymwh.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtlaaqogrl.html

[U01] Py：创建虚拟环境
来源：http://dali.feifeiyinyue.top/Article/details/gtkevwrxxj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jqgfzy.top/Article/details/gtffsdojsz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jqgufenzy.top/Article/details/gtxvhmwnlk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.andypj.xyz/Article/details/gtqgnbrrbh.html

[U03] Py：加载 .env 配置
来源：http://dali.sxryk.cn/Article/details/gtcnzsnjfz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hfpthk.cn/Article/details/gtxwsljtgf.html

[U04] Py：变量调试打印
来源：http://dali.shuidangran.top/Article/details/gtprsijiah.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ivvv.top/Article/details/gtrscgydns.html

[U05] Py：列表去重且保序
来源：http://dali.xinyue.icu/Article/details/gtbeifpdzz.html

list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtfckzlyqn.html

[U06] Py：合并两个字典
来源：http://dali.xylfe.cn/Article/details/gtbecyzgfy.html

{**a, **b}
来源：http://dali.bjfxy.top/Article/details/gtxyevuywj.html

[U07] Py：反转字典键值
来源：http://dali.vqdsnc.cn/Article/details/gtyyssfpag.html

{v: k for k, v in d.items()}
来源：http://dali.cqqwz.cn/Article/details/gtazfdcuqb.html

[U08] Py：展平二维列表
来源：http://dali.zhiwuduotai.top/Article/details/gtgnygdbmj.html

[y for x in nested for y in x]
来源：http://dali.wangdashe.top/Article/details/gthaqydsou.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigfzy.top/Article/details/gtvpqdvqmh.html

max(d, key=d.get)
来源：http://dali.yongpay.top/Article/details/gtwwxffgyr.html

[U10] Py：按值排序字典
来源：http://dali.guannengcc.top/Article/details/gtxsajdwhv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ybcxt.top/Article/details/gtlvscivtc.html

[U11] Py：生成器表达式
来源：http://dali.andypj.xyz/Article/details/gthmspwmdm.html

(x * 2 for x in arr)
来源：http://dali.guannengcc.top/Article/details/gtjhtvqdtg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.chenzaomai.com/Article/details/gtxhgmpwqc.html

Counter(arr).most_common(3)
来源：http://dali.ppjwa.cn/Article/details/gtmoaophtb.html

[U13] Py：固定长度队列
来源：http://dali.ppjwa.cn/Article/details/gtlbbnboah.html

deque(maxlen=10)
来源：http://dali.tian-w.cn/Article/details/gtzmggoxzy.html

[U14] Py：分组收集到列表
来源：http://dali.0kj1m.cn/Article/details/gtbmzhsbso.html

defaultdict(list)
来源：http://dali.gogol.net.cn/Article/details/gtlezhwjdj.html

[U15] Py：高精度计时
来源：http://dali.xziqi.cn/Article/details/gtmyrftahn.html

t = time.perf_counter()
来源：http://dali.jqgufenzy.top/Article/details/gtdtmkaqqy.html

[U16] Py：命令行参数解析
来源：http://dali.yj20258.top/Article/details/gtheqzwwxa.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhengqikj.top/Article/details/gtubobevqz.html

[U17] Py：初始化日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuavqjxsp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.dashuyun.cn/Article/details/gtojakjojy.html

[U18] Py：预编译正则
来源：http://dali.kuanghao11.cn/Article/details/gthylsvvet.html

pat = re.compile(r"\d+")
来源：http://dali.zycfv.cn/Article/details/gtouhektci.html

[U19] Py：正则替换带回调
来源：http://dali.sxryk.cn/Article/details/gtbmpaqyea.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sysykeji.top/Article/details/gtwrefwqyl.html

[U20] Py：缓存函数结果
来源：http://dali.yonumen.top/Article/details/gtneocepil.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cheryme.top/Article/details/gtbbnuoiyo.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekhiheob.html

@contextlib.contextmanager
来源：http://dali.yanxiufei.cn/Article/details/gtkgarwtrx.html

[U22] Py：矩阵转置
来源：http://dali.316326.xyz/Article/details/gtdhkxvjgu.html

list(zip(*m))
来源：http://dali.ivvv.top/Article/details/gtiucewgyl.html

[U23] Py：分块读取大文件
来源：http://dali.gogol.net.cn/Article/details/gtzgwutkzb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenzaomai.com/Article/details/gtnnnthwqa.html

[U24] Py：路径操作
来源：http://dali.meibo888.top/Article/details/gtvpwdyjvn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gtjahfetth.html

[U25] Py：CSV 按字典读
来源：http://dali.cucudq.cn/Article/details/gtukxzwdnv.html

csv.DictReader(f)
来源：http://dali.jinqigufen.top/Article/details/gtlvkyexzq.html

[U26] Py：并发下载
来源：http://dali.xylfe.cn/Article/details/gtympgzwzg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.haohaochexian.top/Article/details/gtbujwobut.html

[U27] Py：异步 HTTP
来源：http://dali.jinqigfzy.top/Article/details/gtidkjrals.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xziqi.cn/Article/details/gtespkqpwa.html

[U28] Py：类型别名
来源：http://dali.zhoulong.xyz/Article/details/gtotixxqmz.html

UserId = int
来源：http://dali.fzhhl.top/Article/details/gtmxiytjwe.html

[U29] Py：属性校验
来源：http://dali.quarkkingdee.top/Article/details/gtheipazjq.html

@property 与 @x.setter 配合
来源：http://dali.chenlongwang.top/Article/details/gterczgvty.html

[U30] Py：数据类
来源：http://dali.svipenyu.cn/Article/details/gtodmsqjxd.html

@dataclass(slots=True)
来源：http://dali.chenlongwang.top/Article/details/gtvieryudx.html

[U31] Py：单测
来源：http://dali.hysaishi.cn/Article/details/gtapyvdkvs.html

python -m pytest -q
来源：http://dali.xuanzx.com/Article/details/gtplhjsift.html

[U32] Py：代码格式化
来源：http://dali.birdmap.top/Article/details/gtindtexvg.html

ruff format . && ruff check --fix .
来源：http://dali.yj20258.top/Article/details/gtgvabvkvt.html

[U33] Py：打包发布
来源：http://dali.guowangkeji.top/Article/details/gtdheictrq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.bjfxy.top/Article/details/gtffdpgiov.html

[U34] Py：判断编码
来源：http://dali.yongpay.top/Article/details/gtsboxbegz.html

chardet.detect(raw)
来源：http://dali.shuidangran.top/Article/details/gtvzerbdok.html

[U35] Py：发送邮件
来源：http://dali.daxiang520.top/Article/details/gtpbherlma.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.guowangkeji.top/Article/details/gtafminftc.html

[U36] Py：定时任务
来源：http://dali.fengsongda.top/Article/details/gtvhzkinlw.html

schedule.every(10).minutes.do(job)
来源：http://dali.hammf.cn/Article/details/gthrdkizfu.html

[U37] Py：读写 Excel
来源：http://dali.hywenlv.cn/Article/details/gteftztqlg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tanke756.top/Article/details/gtbikpdsud.html

[U38] Py：获取脚本所在目录
来源：http://dali.jlsjyb.cn/Article/details/gtgfwwolph.html

Path(__file__).resolve().parent
来源：http://dali.zhoulong.xyz/Article/details/gtuwhznaey.html

[U39] Py：判断是否在交互环境
来源：http://dali.zycfv.cn/Article/details/gtqnxhaykt.html

sys.stdout.isatty()
来源：http://dali.yuanzhike.top/Article/details/gttcfppdza.html

[U40] Py：打印到标准错误
来源：http://dali.gotoacloud.top/Article/details/gttitrgmjg.html

print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gtrpwhnkab.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.guowangkeji.top/Article/details/gtsfbjedti.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinqigfzy.top/Article/details/gtumeegaxo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cucudq.cn/Article/details/gtbxjtkohb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.316326.xyz/Article/details/gtjmknvouj.html

[U43] PHP：声明命名空间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuikjfqeg.html

namespace App\Http;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnykgnnib.html

[U44] PHP：开启严格类型
来源：http://dali.gzhubu.top/Article/details/gtkmexatxd.html

declare(strict_types=1);
来源：http://dali.sufxvd.cn/Article/details/gtcgbwdtac.html


<!-- 参考信息 -->