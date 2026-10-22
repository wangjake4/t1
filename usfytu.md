代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.shangyingyoupin.top/Article/details/gttjgiwkdf.html

[S27] C：定义常量
来源：http://dali.yuanzhike.top/Article/details/gtehgofejl.html

const double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gttaeqovnc.html

[S28] C：静态变量
来源：http://dali.jinqigfzy.top/Article/details/gtibsfuenm.html

static int counter = 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjjqbsft.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gtoaobtddf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sxryk.cn/Article/details/gtrvxrbbxh.html

[S30] C：头文件保护
来源：http://dali.smart0.xyz/Article/details/gtqvxoakkq.html

#ifndef X_H
来源：http://dali.wangdashe.top/Article/details/gtcrpjsjps.html

#define X_H
来源：http://dali.yangfankeji.com/Article/details/gtlibswkaw.html

#endif
来源：http://dali.gaohongyu789.top/Article/details/gtskbfnfer.html

[S31] C++：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtmezxwghw.html

#include <iostream>
来源：http://dali.ydzc1.top/Article/details/gtjpchixje.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fzhhl.top/Article/details/gtimowmsjp.html

[S32] C++：字符串
来源：http://dali.dianchejie.cn/Article/details/gtolssefvf.html

std::string s = "hi";  s += "!";
来源：http://dali.yuxming.cn/Article/details/gtolqngqoz.html

[S33] C++：vector 增删
来源：http://dali.jqgfzy.top/Article/details/gtfmunghhu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gaohongyu789.top/Article/details/gtxtgvplqt.html

[S34] C++：遍历 vector
来源：http://dali.shzxlz.cn/Article/details/gtkwztmnem.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jyoumei.cn/Article/details/gtsskerbsr.html

[S35] C++：map
来源：http://dali.dashuyun.cn/Article/details/gtnvmciwlw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtfkromvti.html

[S36] C++：unordered_map
来源：http://dali.bjfxy.top/Article/details/gtwagyouzr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtcnddoikq.html

[S37] C++：set
来源：http://dali.jinqigufen.top/Article/details/gtkhwrvqxj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.0kj1m.cn/Article/details/gtxmwuuish.html

[S38] C++：排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtumtvgmph.html

std::sort(v.begin(), v.end());
来源：http://dali.xylfe.cn/Article/details/gtjobzccaa.html

[S39] C++：自定义比较器排序
来源：http://dali.xziqi.cn/Article/details/gtzsmklnyg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhengqikj.top/Article/details/gttnumaciq.html

[S40] C++：查找元素
来源：http://dali.yangfankeji.com/Article/details/gtigkrlfyy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ivvv.top/Article/details/gtxocqober.html

[S41] C++：类与构造函数
来源：http://dali.tanke756.top/Article/details/gtolhiiddh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj202588.top/Article/details/gtwhgmeuvq.html

[S42] C++：继承与虚函数
来源：http://dali.aibaodan.cn/Article/details/gtorrxattp.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuetiantiany.cn/Article/details/gtovrotfqa.html

[S43] C++：智能指针
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgpuxhsi.html

auto p = std::make_unique<int>(5);
来源：http://dali.aizwys.cn/Article/details/gtduxzdeup.html

[S44] C++：引用传参
来源：http://dali.haohaochexian.top/Article/details/gtsxoohhhi.html

void inc(int &x) { ++x; }
来源：http://dali.cdnleiting.top/Article/details/gtagsmclku.html

[S45] C++：lambda
来源：http://dali.cucudq.cn/Article/details/gtyypyedur.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgfzy.top/Article/details/gtgvedqoal.html

[S46] C++：函数模板
来源：http://dali.quarkkingdee.top/Article/details/gtpkluarav.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hnxiangtu.top/Article/details/gtasyyldzn.html

[S47] C++：结构化绑定遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtfkujlpoc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fzhhl.top/Article/details/gtwaszzfmx.html

[S48] C++：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtavadopap.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hammf.cn/Article/details/gtegdrbxcp.html

while (std::getline(in, line)) { }
来源：http://dali.nwbrower.top/Article/details/gtalohymju.html

[S49] C++：写文件
来源：http://dali.jinqigufen.top/Article/details/gtdxdmutar.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhoulong.xyz/Article/details/gtopcggeop.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gtognfvfto.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.havefunace.top/Article/details/gttiyndsol.html

[S51] C++：显式类型转换
来源：http://dali.pycfn.com/Article/details/gtezbhfowd.html

static_cast<double>(a) / b
来源：http://dali.chenlongwang.top/Article/details/gtiramwqvd.html

[S52] C++：const 与 noexcept
来源：http://dali.feifeiyinyue.top/Article/details/gtrobdwcpr.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258888.top/Article/details/gttfnyhaxa.html

[S53] C++：移动语义
来源：http://dali.cqqwz.cn/Article/details/gtobiyjuii.html

std::vector<int> w = std::move(v);
来源：http://dali.aizwys.cn/Article/details/gtsmybwuja.html

[S54] C++：异常处理
来源：http://dali.xuanzx.com/Article/details/gtadgflbrq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yanxiufei.cn/Article/details/gtbkanlkdl.html

[S55] C++：结构化绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfrijbnj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.redwolf501.top/Article/details/gtqbaeuyor.html

[S56] C++：optional
来源：http://dali.quarkkingdee.top/Article/details/gthfctojhm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgvbduzl.html

[S57] C++：编译期常量
来源：http://dali.gaohongyu789.top/Article/details/gtzgwusxve.html

constexpr int N = 10;
来源：http://dali.haohaochexian.top/Article/details/gtkoxfrwyx.html

[S58] C++：命名空间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfbcgasm.html

namespace ns { int f() { return 1; } }
来源：http://dali.pycfn.com/Article/details/gtmecnwwch.html

[S59] C++：静态断言
来源：http://dali.zhengqikj.top/Article/details/gtonylnisf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nwbrower.top/Article/details/gtljswpbkj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhixingplan.top/Article/details/gtpvgnaykq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtqzpzjdst.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvunjvvu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.mhx1999.top/Article/details/gtbjruuhsi.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtuquookma.html

[T01] Kotlin：Hello World
来源：http://dali.fzhhl.top/Article/details/gtwtsirmgh.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtypboemfu.html

[T02] Kotlin：变量
来源：http://dali.yj20258888.top/Article/details/gtqfgcbnpm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhoulong.xyz/Article/details/gtthesmfem.html

[T03] Kotlin：字符串模板
来源：http://dali.redwolf501.top/Article/details/gtyppzirbe.html

"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gtquelhmvo.html

[T04] Kotlin：空安全
来源：http://dali.aizwys.cn/Article/details/gtvikwywkg.html

val n: String? = null;  n?.length
来源：http://dali.hysaishi.cn/Article/details/gtelhbxnjd.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtxexlitpu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sysykeji.top/Article/details/gteqwbcxwh.html

[T06] Kotlin：集合映射
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplzllhjp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gzhubu.top/Article/details/gthwzfndik.html

[T07] Kotlin：集合过滤
来源：http://dali.vqdsnc.cn/Article/details/gtvysjrxir.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.snrcjt.cn/Article/details/gtrkhsdsfa.html

[T08] Kotlin：数据类
来源：http://dali.zhixingplan.top/Article/details/gtlazroudw.html

data class User(val name: String, val age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gtkejdjzxx.html

[T09] Kotlin：扩展函数
来源：http://dali.tianlin.xyz/Article/details/gtxdsremrs.html

fun String.exclaim() = this + "!"
来源：http://dali.hnxiangtu.top/Article/details/gtczzrrlyg.html

[T10] Kotlin：默认参数
来源：http://dali.cashguo.top/Article/details/gtxtlppcyv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cucudq.cn/Article/details/gtlgzqpejf.html

[T11] Kotlin：协程
来源：http://dali.wangshuangyany.cn/Article/details/gtgxbwxfzp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cqqwz.cn/Article/details/gtqkjpovno.html

[T12] Kotlin：解构声明
来源：http://dali.0kj1m.cn/Article/details/gtuaigasav.html

val (a, b) = Pair(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gtvoauptgg.html

[T13] Kotlin：只读 Map
来源：http://dali.chenjidiqi.icu/Article/details/gtirsruqet.html

val m = mapOf("a" to 1)
来源：http://dali.yanxiufei.cn/Article/details/gtjfcweouk.html

[T14] Kotlin：循环
来源：http://dali.zdqjudy.top/Article/details/gtoqupwjpq.html

for (i in 1..10) println(i)
来源：http://dali.chenzaomai.com/Article/details/gtakjejaah.html

[T15] Kotlin：接口
来源：http://dali.meibo888.top/Article/details/gtaouymcfy.html

interface Shape { fun area(): Double }
来源：http://dali.316326.xyz/Article/details/gtdisnrmms.html

[T16] Swift：Hello World
来源：http://dali.jianghu66.top/Article/details/gtyqfyrwym.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gtegrfpsyl.html

[T17] Swift：变量与常量
来源：http://dali.ydzc1.top/Article/details/gtugmqtheo.html

var a = 1;  let b = 2
来源：http://dali.aibaodan.cn/Article/details/gthymrzvqv.html

[T18] Swift：字符串插值
来源：http://dali.hammf.cn/Article/details/gtqjhbojkb.html

"值: \(b)"
来源：http://dali.xinyue.icu/Article/details/gtylutwcfz.html

[T19] Swift：可选绑定
来源：http://dali.guowangkeji.top/Article/details/gtapghaekc.html

if let n = opt { print(n) }
来源：http://dali.jqgufenzy.top/Article/details/gtuwqcidwe.html

[T20] Swift：数组操作
来源：http://dali.xinyue.icu/Article/details/gtmmiibfsf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.0kj1m.cn/Article/details/gtbgifxrtm.html

[T21] Swift：遍历
来源：http://dali.fzhhl.top/Article/details/gtltrwmzos.html

for x in a { print(x) }
来源：http://dali.tanke756.top/Article/details/gtibhtkaet.html

[T22] Swift：字典
来源：http://dali.ppjwa.cn/Article/details/gtxaqpbnoc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dianchejie.cn/Article/details/gtrsxcaufa.html

[T23] Swift：函数
来源：http://dali.birdmap.top/Article/details/gtomnkhvba.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ehwqpu.com/Article/details/gtpxoqrsnw.html

[T24] Swift：闭包
来源：http://dali.kuanghao11.cn/Article/details/gtjtpqfbyf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtmuwibcpr.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangtech.top/Article/details/gtncwiggbq.html

struct P { var x: Int }
来源：http://dali.zhongyouzk.top/Article/details/gtbyfltoqp.html

[T26] Swift：类与重写
来源：http://dali.fengsongda.top/Article/details/gtuqxveqvg.html

class A: Base { override func f() {} }
来源：http://dali.svipenyu.cn/Article/details/gtddfnpeyu.html

[T27] Swift：错误处理
来源：http://dali.316326.xyz/Article/details/gtjuqjcyqx.html

do { try f() } catch { print(error) }
来源：http://dali.hammf.cn/Article/details/gtkkxhhjav.html

[T28] Swift：枚举
来源：http://dali.zhixingplan.top/Article/details/gtukbbjhet.html

enum Color { case red, green }
来源：http://dali.cdnleiting.top/Article/details/gtwhqkuuxo.html

[T29] Swift：guard 提前返回
来源：http://dali.andypj.xyz/Article/details/gtqpfrkmuf.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gtdprneoxp.html

[T30] Swift：协议
来源：http://dali.pengpengdd.cyou/Article/details/gtbiiiwaln.html

protocol Shape { func area() -> Double }
来源：http://dali.kuanghao11.cn/Article/details/gtumajtuwc.html

[T31] Lua：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtuqjslylz.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gtdhvisevx.html

[T32] Lua：局部变量
来源：http://dali.yuxming.cn/Article/details/gtbofbjimj.html

local a = 1
来源：http://dali.hywenlv.cn/Article/details/gtiwpmgdfu.html

[T33] Lua：表（数组）
来源：http://dali.hnxiangtu.top/Article/details/gthxtlllgk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.iojbl.cn/Article/details/gtrfwbrikr.html

[T34] Lua：遍历表
来源：http://dali.xinyue.icu/Article/details/gtiyzlkecf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhoulong.xyz/Article/details/gtcgmanlzh.html

[T35] Lua：字典表
来源：http://dali.quarkkingdee.top/Article/details/gtispupgty.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nwbrower.top/Article/details/gtbndaxmxm.html

[T36] Lua：函数
来源：http://dali.fengsongda.top/Article/details/gtmmzxxskf.html

function add(a, b) return a + b end
来源：http://dali.nanxuanxn.top/Article/details/gtsflurcek.html

[T37] Lua：字符串拼接
来源：http://dali.shuidangran.top/Article/details/gthbjizesw.html

"a" .. "b"
来源：http://dali.jqgfzy.top/Article/details/gtupsharnq.html

[T38] Lua：条件
来源：http://dali.yvedp.cn/Article/details/gtokpevkvs.html

if x > 0 then print("正") end
来源：http://dali.zhengqikj.top/Article/details/gtgyzazkhm.html

[T39] Lua：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gtjxwxhnnv.html

string.find(s, "%d+")
来源：http://dali.chenjidiqi.icu/Article/details/gtzwoyorsb.html

[T40] Lua：元表
来源：http://dali.guowangkeji.top/Article/details/gtcvhetfeu.html

setmetatable({}, { __index = base })
来源：http://dali.xinyue.icu/Article/details/gtvvmivcrg.html

[T41] Perl：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtlctqxbed.html

print "Hello\n";
来源：http://dali.jqgfzy.top/Article/details/gtakuwurwt.html

[T42] Perl：变量类型
来源：http://dali.smart0.xyz/Article/details/gtbcndzsgx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jyoumei.cn/Article/details/gtniswfoza.html

[T43] Perl：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtjkorbcmo.html

"值: $a"
来源：http://dali.yj20258888.top/Article/details/gtqgtzixvr.html

[T44] Perl：条件
来源：http://dali.aizwys.cn/Article/details/gtshhlzwxd.html

if ($a > 0) { print "正"; }
来源：http://dali.dashuyun.cn/Article/details/gtaajogcgk.html

[T45] Perl：数组遍历
来源：http://dali.ehwqpu.com/Article/details/gtqjkwajlp.html

for my $x (@arr) { print $x; }
来源：http://dali.sufxvd.cn/Article/details/gteebcmohi.html

[T46] Perl：哈希操作
来源：http://dali.jqgfzy.top/Article/details/gtdnldriey.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.daxiang520.top/Article/details/gtixcdazmg.html

[T47] Perl：正则捕获
来源：http://dali.ydzc1.top/Article/details/gtfhiqazio.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258888.top/Article/details/gtctzayayb.html

[T48] Perl：正则替换
来源：http://dali.xylfe.cn/Article/details/gtewgnfhhq.html

$s =~ s/old/new/g;
来源：http://dali.jyoumei.cn/Article/details/gtlhfkwwpt.html

[T49] Perl：函数
来源：http://dali.daria6918.cn/Article/details/gtawctxoxb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtmxxjglsb.html

[T50] Perl：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtvdqotdsm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhiwuduotai.top/Article/details/gtxfdofaev.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.9152youxi.cn/Article/details/gtjbwqbssd.html

[T51] Scala：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtodsfhdfw.html

println("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtixunxyqc.html

[T52] Scala：变量
来源：http://dali.dianchejie.cn/Article/details/gtywgxhphs.html

val a = 1;  var b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbrcxtjp.html

[T53] Scala：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtgjedslwb.html

s"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gtebsnmmdi.html

[T54] Scala：集合映射
来源：http://dali.hammf.cn/Article/details/gtybbaltar.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangdashe.top/Article/details/gtaxypfebt.html

[T55] Scala：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gtjrrlpijx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yvedp.cn/Article/details/gtpnewdxvz.html

[T56] Scala：样例类
来源：http://dali.pengpengdd.cyou/Article/details/gtvpuhhwzw.html

case class User(name: String, age: Int)
来源：http://dali.ppjwa.cn/Article/details/gtzpxymvjj.html

[T57] Scala：模式匹配
来源：http://dali.hammf.cn/Article/details/gtastmsntt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.aizwys.cn/Article/details/gttagemlks.html

[T58] Scala：函数定义
来源：http://dali.sweek.top/Article/details/gtlaoztofa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj20258.top/Article/details/gtygpykypp.html

[T59] Scala：循环
来源：http://dali.sxryk.cn/Article/details/gtobtlgpgo.html

for (i <- 1 to 10) println(i)
来源：http://dali.xziqi.cn/Article/details/gtpolxvnou.html

[T60] Scala：折叠
来源：http://dali.hammf.cn/Article/details/gtilhtzznj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cheryme.top/Article/details/gtacsxauhn.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlazuxez.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.kuanghao11.cn/Article/details/gteocdbebt.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtqnwmngmd.html

[U01] Py：创建虚拟环境
来源：http://dali.nwbrower.top/Article/details/gtlbyvryul.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aibaodan.cn/Article/details/gtnpuwcgxl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenzaomai.com/Article/details/gtmkomkkmw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shzxlz.cn/Article/details/gttcvdtmwa.html

[U03] Py：加载 .env 配置
来源：http://dali.quarkkingdee.top/Article/details/gtykilutjb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.aibaodan.cn/Article/details/gtsmalurzf.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbrrebhl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsjkbarq.html

[U05] Py：列表去重且保序
来源：http://dali.hfpthk.cn/Article/details/gtacjnlxjp.html

list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gtbohvpcnu.html

[U06] Py：合并两个字典
来源：http://dali.hongshengwenyu.top/Article/details/gtdnwtdcsx.html

{**a, **b}
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmkxmelr.html

[U07] Py：反转字典键值
来源：http://dali.xinyue.icu/Article/details/gtwnhzqkmc.html

{v: k for k, v in d.items()}
来源：http://dali.jinqigfzy.top/Article/details/gtkwpvpckv.html

[U08] Py：展平二维列表
来源：http://dali.meibo888.top/Article/details/gtjqxoqbpu.html

[y for x in nested for y in x]
来源：http://dali.shuidangran.top/Article/details/gtwpsnzkal.html

[U09] Py：字典取最大值的键
来源：http://dali.vqdsnc.cn/Article/details/gtybdqduof.html

max(d, key=d.get)
来源：http://dali.tianlin.xyz/Article/details/gttfxqfvyu.html

[U10] Py：按值排序字典
来源：http://dali.fzhhl.top/Article/details/gtqqjmmubr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nanxinkj.top/Article/details/gtfzztaatm.html

[U11] Py：生成器表达式
来源：http://dali.jinqigfzy.top/Article/details/gtkxcnhsfd.html

(x * 2 for x in arr)
来源：http://dali.yvedp.cn/Article/details/gtadvovkar.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.chenzaomai.com/Article/details/gtgllhflyh.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gtnhyjmflu.html

[U13] Py：固定长度队列
来源：http://dali.fzhhl.top/Article/details/gtvltdrnzk.html

deque(maxlen=10)
来源：http://dali.pengpengdd.cyou/Article/details/gtqrfowdlx.html

[U14] Py：分组收集到列表
来源：http://dali.yvedp.cn/Article/details/gtivzccwvy.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gtkoekbldj.html

[U15] Py：高精度计时
来源：http://dali.ydzc1.top/Article/details/gtnmkmvmae.html

t = time.perf_counter()
来源：http://dali.cheryme.top/Article/details/gtbucexrqs.html

[U16] Py：命令行参数解析
来源：http://dali.c1oappe.top/Article/details/gtfqrkqxpi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsirndfni.html

[U17] Py：初始化日志
来源：http://dali.cashguo.top/Article/details/gtrviexput.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.haohaochexian.top/Article/details/gtddbmdmpy.html

[U18] Py：预编译正则
来源：http://dali.havefunace.top/Article/details/gthylwixmp.html

pat = re.compile(r"\d+")
来源：http://dali.svipenyu.cn/Article/details/gtkllkjfuz.html

[U19] Py：正则替换带回调
来源：http://dali.fengsongda.top/Article/details/gtykqjsuck.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.guannengcc.top/Article/details/gtbsloezjo.html

[U20] Py：缓存函数结果
来源：http://dali.ivvv.top/Article/details/gtaevvtoca.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenzaomai.com/Article/details/gtyyszomzw.html

[U21] Py：自定义上下文管理器
来源：http://dali.vqdsnc.cn/Article/details/gtaneqolou.html

@contextlib.contextmanager
来源：http://dali.316326.xyz/Article/details/gtiexhnfgq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gtujvnaerh.html

list(zip(*m))
来源：http://dali.pengpengdd.cyou/Article/details/gtlpmxoukn.html

[U23] Py：分块读取大文件
来源：http://dali.yongpay.top/Article/details/gtuoclnqfv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.andypj.xyz/Article/details/gtfrmpmakq.html

[U24] Py：路径操作
来源：http://dali.gzhubu.top/Article/details/gthpaudxes.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gtrftuuygd.html

[U25] Py：CSV 按字典读
来源：http://dali.vqdsnc.cn/Article/details/gtxzmikssz.html

csv.DictReader(f)
来源：http://dali.ybcxt.top/Article/details/gttdkqscrq.html

[U26] Py：并发下载
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhwuoihm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yj20258.top/Article/details/gtmchzujse.html

[U27] Py：异步 HTTP
来源：http://dali.316326.xyz/Article/details/gtfobhyrhz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sysykeji.top/Article/details/gtgilqgbqa.html

[U28] Py：类型别名
来源：http://dali.redwolf501.top/Article/details/gtpwfwqfxp.html

UserId = int
来源：http://dali.xuanzx.com/Article/details/gtredbkbta.html

[U29] Py：属性校验
来源：http://dali.ybcxt.top/Article/details/gtxltyohes.html

@property 与 @x.setter 配合
来源：http://dali.zhixingplan.top/Article/details/gtssjabwhd.html

[U30] Py：数据类
来源：http://dali.xinyue.icu/Article/details/gtxqbxhool.html

@dataclass(slots=True)
来源：http://dali.yongpay.top/Article/details/gtbcdnyjbo.html

[U31] Py：单测
来源：http://dali.jqgufenzy.top/Article/details/gtixnhmbwi.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gtohtalivx.html

[U32] Py：代码格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqfewivs.html

ruff format . && ruff check --fix .
来源：http://dali.sweek.top/Article/details/gtpjdgprtn.html

[U33] Py：打包发布
来源：http://dali.chenlongwang.top/Article/details/gtqmvenflu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcceaihho.html

[U34] Py：判断编码
来源：http://dali.hnqzz.top/Article/details/gtsskisgbd.html

chardet.detect(raw)
来源：http://dali.aizwys.cn/Article/details/gtqwrnhaub.html

[U35] Py：发送邮件
来源：http://dali.cdnleiting.top/Article/details/gthbpwvcxy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj202588.top/Article/details/gtxpcpzfyk.html

[U36] Py：定时任务
来源：http://dali.sufxvd.cn/Article/details/gtnvrdedee.html

schedule.every(10).minutes.do(job)
来源：http://dali.yonumen.top/Article/details/gthemzjosl.html

[U37] Py：读写 Excel
来源：http://dali.cdnleiting.top/Article/details/gteseghwon.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hywenlv.cn/Article/details/gtiukpanjb.html

[U38] Py：获取脚本所在目录
来源：http://dali.shzxlz.cn/Article/details/gtqmcrakbv.html

Path(__file__).resolve().parent
来源：http://dali.pengpengdd.cyou/Article/details/gtzohspvde.html

[U39] Py：判断是否在交互环境
来源：http://dali.gotoacloud.top/Article/details/gtjoalmyqi.html

sys.stdout.isatty()
来源：http://dali.kuanghao11.cn/Article/details/gtvgzrymlv.html

[U40] Py：打印到标准错误
来源：http://dali.aizwys.cn/Article/details/gtbskxqvww.html

print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gtkdvrqosl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.pengpengdd.cyou/Article/details/gtpfblygxv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.kuanghao11.cn/Article/details/gtcjbehrfv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.haohaochexian.top/Article/details/gtebzjwind.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.daxiang520.top/Article/details/gtclkmtxth.html

[U43] PHP：声明命名空间
来源：http://dali.316326.xyz/Article/details/gtwhaimygg.html

namespace App\Http;
来源：http://dali.yj202588.top/Article/details/gtdxmviscb.html

[U44] PHP：开启严格类型
来源：http://dali.zhixingplan.top/Article/details/gtwmyprhqh.html

declare(strict_types=1);
来源：http://dali.ybcxt.top/Article/details/gtidxlpftj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.tianlin.xyz/Article/details/gtzqcwcipk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtnmolclzw.html

[U46] PHP：可空类型
来源：http://dali.jqgfzy.top/Article/details/gtzxwcefng.html

?string $name = null
来源：http://dali.zhengqikj.top/Article/details/gtgdsrruyu.html

[U47] PHP：联合类型
来源：http://dali.snrcjt.cn/Article/details/gtrpxspamg.html

int|string $id
来源：http://dali.aizwys.cn/Article/details/gtjvfqfkec.html

[U48] PHP：纯枚举
来源：http://dali.feifeiyinyue.top/Article/details/gthkiosnuy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhixingplan.top/Article/details/gtfjvtxbdn.html

[U49] PHP：只读属性
来源：http://dali.wangshuangyany.cn/Article/details/gtebuvjynq.html

public readonly string $name
来源：http://dali.vqdsnc.cn/Article/details/gtrpgjmzbv.html

[U50] PHP：构造器属性提升
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlflgbpa.html

public function __construct(private int $id) {}
来源：http://dali.tianlin.xyz/Article/details/gtsnlcwfqo.html


<!-- 参考信息 -->