代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcwkvwhk.html

[S25] C：内存拷贝
来源：http://dali.haohaochexian.top/Article/details/gthpkadpdz.html

memcpy(dst, src, n);
来源：http://dali.gzhubu.top/Article/details/gtrlzpoyrj.html

[S26] C：内存清零
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybpfyypx.html

memset(a, 0, sizeof a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmfpdxjb.html

[S27] C：定义常量
来源：http://dali.nwbrower.top/Article/details/gtqbgslgot.html

const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtxjztzpql.html

[S28] C：静态变量
来源：http://dali.daria6918.cn/Article/details/gtitgkfohx.html

static int counter = 0;
来源：http://dali.jqgfzy.top/Article/details/gtpuqwzsuq.html

[S29] C：变参函数
来源：http://dali.jinqigfzy.top/Article/details/gtaaiwluwx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgfzy.top/Article/details/gtwwzlvccs.html

[S30] C：头文件保护
来源：http://dali.316326.xyz/Article/details/gtkprujvau.html

#ifndef X_H
来源：http://dali.ehwqpu.com/Article/details/gtbqaywnni.html

#define X_H
来源：http://dali.fengsongda.top/Article/details/gtkmwnepnu.html

#endif
来源：http://dali.yanxiufei.cn/Article/details/gtfwbzplvc.html

[S31] C++：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtwlwhrppm.html

#include <iostream>
来源：http://dali.zhiwuduotai.top/Article/details/gtaexbgxvl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangdashe.top/Article/details/gtuywszafl.html

[S32] C++：字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtdalnfntw.html

std::string s = "hi";  s += "!";
来源：http://dali.aizwys.cn/Article/details/gtdeuzgbpq.html

[S33] C++：vector 增删
来源：http://dali.yanxiufei.cn/Article/details/gtpokgxwex.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xinyue.icu/Article/details/gteucgnbrb.html

[S34] C++：遍历 vector
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqxnvrvr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258.top/Article/details/gtoznmvcfj.html

[S35] C++：map
来源：http://dali.yueranfly.top/Article/details/gttkkmlrfd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtlhqlwwcr.html

[S36] C++：unordered_map
来源：http://dali.yj20258888.top/Article/details/gtgycchcha.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gtkzcjvoeu.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gtvipxlcxo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jyoumei.cn/Article/details/gtoylxiuzc.html

[S38] C++：排序
来源：http://dali.yueranfly.top/Article/details/gtmxfykmqe.html

std::sort(v.begin(), v.end());
来源：http://dali.bjfxy.top/Article/details/gtcvtfyqgg.html

[S39] C++：自定义比较器排序
来源：http://dali.yangfankeji.com/Article/details/gthxoedxra.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gtslyewnlz.html

[S40] C++：查找元素
来源：http://dali.shuidangran.top/Article/details/gtjlcttwtl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.andypj.xyz/Article/details/gtztciiapc.html

[S41] C++：类与构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabhwrymf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgufenzy.top/Article/details/gthrirytmf.html

[S42] C++：继承与虚函数
来源：http://dali.nanxuanxn.top/Article/details/gtiskchkex.html

class B : public Base { public: void f() override {} };
来源：http://dali.redwolf501.top/Article/details/gtvgqtddor.html

[S43] C++：智能指针
来源：http://dali.cheryme.top/Article/details/gtxgdhzcvr.html

auto p = std::make_unique<int>(5);
来源：http://dali.ehwqpu.com/Article/details/gtyulmgblt.html

[S44] C++：引用传参
来源：http://dali.hnxiangtu.top/Article/details/gtgcwobiuy.html

void inc(int &x) { ++x; }
来源：http://dali.sxryk.cn/Article/details/gtvccppgra.html

[S45] C++：lambda
来源：http://dali.cheryme.top/Article/details/gtfdeblqnk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.iojbl.cn/Article/details/gttjsnskui.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gtcjbxxvau.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.0kj1m.cn/Article/details/gtiaiexczh.html

[S47] C++：结构化绑定遍历
来源：http://dali.yongpay.top/Article/details/gteelnamks.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hysaishi.cn/Article/details/gtskriqllv.html

[S48] C++：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtiolklqqp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ybcxt.top/Article/details/gtmkwyjnic.html

while (std::getline(in, line)) { }
来源：http://dali.jlsjyb.cn/Article/details/gtfkuxmmue.html

[S49] C++：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gtxamrsdjv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jiagoushi.top/Article/details/gtvxvxldmc.html

[S50] C++：格式化数字
来源：http://dali.hammf.cn/Article/details/gtdlkwwhpy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtkbbvywma.html

[S51] C++：显式类型转换
来源：http://dali.zycfv.cn/Article/details/gtkxzzizfq.html

static_cast<double>(a) / b
来源：http://dali.ehwqpu.com/Article/details/gtntjpawcf.html

[S52] C++：const 与 noexcept
来源：http://dali.cucudq.cn/Article/details/gtsfuifodn.html

int size() const noexcept { return n_; }
来源：http://dali.andypj.xyz/Article/details/gtehghzeia.html

[S53] C++：移动语义
来源：http://dali.meibo888.top/Article/details/gtxtnyrnhn.html

std::vector<int> w = std::move(v);
来源：http://dali.hammf.cn/Article/details/gtihmmnjyp.html

[S54] C++：异常处理
来源：http://dali.mhx1999.top/Article/details/gtnkpopkhs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fengsongda.top/Article/details/gtwqlpanyi.html

[S55] C++：结构化绑定
来源：http://dali.yongpay.top/Article/details/gtdhpbntea.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ehwqpu.com/Article/details/gtpkzcsjkq.html

[S56] C++：optional
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyqorzip.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.0kj1m.cn/Article/details/gtfnagxxnd.html

[S57] C++：编译期常量
来源：http://dali.zhiwuduotai.top/Article/details/gtwhpuyxrz.html

constexpr int N = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtalfbspvf.html

[S58] C++：命名空间
来源：http://dali.kuanghao11.cn/Article/details/gtvbgveuph.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhengqikj.top/Article/details/gttqzzknxq.html

[S59] C++：静态断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxnfkswy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yangfankeji.com/Article/details/gtfvivvneo.html

[S60] C++：遍历并删除元素
来源：http://dali.dianchejie.cn/Article/details/gtqarvbikn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cucudq.cn/Article/details/gtdfzblrjr.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gthvaexoid.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ivvv.top/Article/details/gtpfuwhbvo.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtaeovcvym.html

[T01] Kotlin：Hello World
来源：http://dali.ivvv.top/Article/details/gtfuhubfdt.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzapjmuln.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gtyybwhwdf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ehwqpu.com/Article/details/gtpvjqspxs.html

[T03] Kotlin：字符串模板
来源：http://dali.aizwys.cn/Article/details/gtinjzbjrj.html

"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gtdzlsxeqw.html

[T04] Kotlin：空安全
来源：http://dali.c1oappe.top/Article/details/gtyjxuetcx.html

val n: String? = null;  n?.length
来源：http://dali.zhoulong.xyz/Article/details/gtfppyqrxp.html

[T05] Kotlin：when 表达式
来源：http://dali.yueranfly.top/Article/details/gtkezcucdh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ydzc1.top/Article/details/gtpngskdvk.html

[T06] Kotlin：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gtlpqgkanr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtervybfge.html

[T07] Kotlin：集合过滤
来源：http://dali.svipenyu.cn/Article/details/gtlreqmewi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.meibo888.top/Article/details/gtropfpewx.html

[T08] Kotlin：数据类
来源：http://dali.zhixingplan.top/Article/details/gtbrwdhycm.html

data class User(val name: String, val age: Int)
来源：http://dali.ppjwa.cn/Article/details/gtnjahhaae.html

[T09] Kotlin：扩展函数
来源：http://dali.ivvv.top/Article/details/gtdpcxdejh.html

fun String.exclaim() = this + "!"
来源：http://dali.dianchejie.cn/Article/details/gtdikhoazf.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavaefwib.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ybcxt.top/Article/details/gtaoarqalg.html

[T11] Kotlin：协程
来源：http://dali.hongshengwenyu.top/Article/details/gtjntrqsya.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sufxvd.cn/Article/details/gtawuutwrg.html

[T12] Kotlin：解构声明
来源：http://dali.zhongyouzk.top/Article/details/gtoanakuih.html

val (a, b) = Pair(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gtzlkpkefe.html

[T13] Kotlin：只读 Map
来源：http://dali.pengpengdd.cyou/Article/details/gtewfenixw.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwsnjion.html

[T14] Kotlin：循环
来源：http://dali.xuetiantiany.cn/Article/details/gthxlybtsu.html

for (i in 1..10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gthdqltcgo.html

[T15] Kotlin：接口
来源：http://dali.yangfankeji.com/Article/details/gtsreszsbp.html

interface Shape { fun area(): Double }
来源：http://dali.feifeiyinyue.top/Article/details/gtidbpczbu.html

[T16] Swift：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtksriiiqh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtaupxwnao.html

[T17] Swift：变量与常量
来源：http://dali.smart0.xyz/Article/details/gtpzzywvxs.html

var a = 1;  let b = 2
来源：http://dali.hammf.cn/Article/details/gtmynmndpj.html

[T18] Swift：字符串插值
来源：http://dali.ydzc1.top/Article/details/gtfvelrezm.html

"值: \(b)"
来源：http://dali.zycfv.cn/Article/details/gtjupgvcmq.html

[T19] Swift：可选绑定
来源：http://dali.gaohongyu789.top/Article/details/gtldeefxim.html

if let n = opt { print(n) }
来源：http://dali.bjfxy.top/Article/details/gtkagbexwp.html

[T20] Swift：数组操作
来源：http://dali.jianghu66.top/Article/details/gtwnkedaoe.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daxiang520.top/Article/details/gtxvuifyku.html

[T21] Swift：遍历
来源：http://dali.9152youxi.cn/Article/details/gtuzlklwwn.html

for x in a { print(x) }
来源：http://dali.gotoacloud.top/Article/details/gtxcmtpoyi.html

[T22] Swift：字典
来源：http://dali.yongpay.top/Article/details/gtaqlqilhi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jyoumei.cn/Article/details/gtwcssaopl.html

[T23] Swift：函数
来源：http://dali.cashguo.top/Article/details/gtilvvthmg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtuqtivqif.html

[T24] Swift：闭包
来源：http://dali.hywenlv.cn/Article/details/gtdjadajip.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtdnaycoks.html

[T25] Swift：结构体
来源：http://dali.shzxlz.cn/Article/details/gtjxykvaxh.html

struct P { var x: Int }
来源：http://dali.gzhubu.top/Article/details/gtohmyhjpp.html

[T26] Swift：类与重写
来源：http://dali.wangdashe.top/Article/details/gtiuihhpft.html

class A: Base { override func f() {} }
来源：http://dali.cdnleiting.top/Article/details/gtlxgyrvky.html

[T27] Swift：错误处理
来源：http://dali.gogol.net.cn/Article/details/gteehhggcv.html

do { try f() } catch { print(error) }
来源：http://dali.daria6918.cn/Article/details/gthgiwaeda.html

[T28] Swift：枚举
来源：http://dali.aibaodan.cn/Article/details/gtfskjyrgh.html

enum Color { case red, green }
来源：http://dali.0kj1m.cn/Article/details/gtodnytljl.html

[T29] Swift：guard 提前返回
来源：http://dali.zhengqikj.top/Article/details/gttdkwyatm.html

guard let x = opt else { return }
来源：http://dali.hnxiangtu.top/Article/details/gtbodmxphk.html

[T30] Swift：协议
来源：http://dali.ybcxt.top/Article/details/gthdsgssdm.html

protocol Shape { func area() -> Double }
来源：http://dali.meibo888.top/Article/details/gtjwyyimlj.html

[T31] Lua：Hello World
来源：http://dali.yongpay.top/Article/details/gttbtwnytj.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtbititrtx.html

[T32] Lua：局部变量
来源：http://dali.chenzaomai.com/Article/details/gtwtsxznpi.html

local a = 1
来源：http://dali.yangfankeji.com/Article/details/gtmpvdvfnm.html

[T33] Lua：表（数组）
来源：http://dali.bjfxy.top/Article/details/gtcxnnhuxq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sweek.top/Article/details/gtkbjlowlg.html

[T34] Lua：遍历表
来源：http://dali.sweek.top/Article/details/gtbvptcgob.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xuanzx.com/Article/details/gtckbcbuys.html

[T35] Lua：字典表
来源：http://dali.haohaochexian.top/Article/details/gtkchbwize.html

local d = { a = 1 };  d.b = 2
来源：http://dali.bjfxy.top/Article/details/gtcuwoyuqu.html

[T36] Lua：函数
来源：http://dali.cdnleiting.top/Article/details/gtchhvyoeg.html

function add(a, b) return a + b end
来源：http://dali.jiagoushi.top/Article/details/gtnbqfrndn.html

[T37] Lua：字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gtfkyrgnzj.html

"a" .. "b"
来源：http://dali.cucudq.cn/Article/details/gtaectbqnd.html

[T38] Lua：条件
来源：http://dali.yvedp.cn/Article/details/gtvitpmqsm.html

if x > 0 then print("正") end
来源：http://dali.yonumen.top/Article/details/gtwxzqlvte.html

[T39] Lua：模式匹配
来源：http://dali.hnxiangtu.top/Article/details/gtmlzcxrqc.html

string.find(s, "%d+")
来源：http://dali.meibo888.top/Article/details/gtanchwrjb.html

[T40] Lua：元表
来源：http://dali.316326.xyz/Article/details/gtoafxnbcb.html

setmetatable({}, { __index = base })
来源：http://dali.birdmap.top/Article/details/gtupllkmvu.html

[T41] Perl：Hello World
来源：http://dali.hammf.cn/Article/details/gtdczhgwtk.html

print "Hello\n";
来源：http://dali.yuxming.cn/Article/details/gtewgbuxcy.html

[T42] Perl：变量类型
来源：http://dali.andypj.xyz/Article/details/gtcsmnpbkh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tanke756.top/Article/details/gtwjqsfmcw.html

[T43] Perl：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtceorgllg.html

"值: $a"
来源：http://dali.birdmap.top/Article/details/gtojzkogqs.html

[T44] Perl：条件
来源：http://dali.vqdsnc.cn/Article/details/gtqeolrltc.html

if ($a > 0) { print "正"; }
来源：http://dali.hywenlv.cn/Article/details/gtzuvfimmg.html

[T45] Perl：数组遍历
来源：http://dali.haohaochexian.top/Article/details/gtevsogevw.html

for my $x (@arr) { print $x; }
来源：http://dali.zdqjudy.top/Article/details/gtpzwtqank.html

[T46] Perl：哈希操作
来源：http://dali.wangshuangyany.cn/Article/details/gtxzbzqzlz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fzhhl.top/Article/details/gtrmciricl.html

[T47] Perl：正则捕获
来源：http://dali.ivvv.top/Article/details/gtwlmhimze.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.kuanghao11.cn/Article/details/gtaxaehrrp.html

[T48] Perl：正则替换
来源：http://dali.jiagoushi.top/Article/details/gtytxipvcq.html

$s =~ s/old/new/g;
来源：http://dali.tanke756.top/Article/details/gtuaoulhtt.html

[T49] Perl：函数
来源：http://dali.cucudq.cn/Article/details/gtwybqdacg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtfmpzaixl.html

[T50] Perl：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtjrphgbyl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tian-w.cn/Article/details/gtireiqiaw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhongyouzk.top/Article/details/gthxcjirov.html

[T51] Scala：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtpetlekoq.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtgczmpopr.html

[T52] Scala：变量
来源：http://dali.dianchejie.cn/Article/details/gtmuasxcvn.html

val a = 1;  var b = 2
来源：http://dali.yvedp.cn/Article/details/gtwjqotgwn.html

[T53] Scala：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gttjocsdkr.html

s"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtnurpkgcz.html

[T54] Scala：集合映射
来源：http://dali.xylfe.cn/Article/details/gtzknqdekz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhongyouzk.top/Article/details/gtyfakcrwx.html

[T55] Scala：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtevlufsin.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yueranfly.top/Article/details/gtmcxzaznq.html

[T56] Scala：样例类
来源：http://dali.fzhhl.top/Article/details/gtlyjcgexl.html

case class User(name: String, age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtqcqjzdjs.html

[T57] Scala：模式匹配
来源：http://dali.iojbl.cn/Article/details/gtbcnmuxfj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hammf.cn/Article/details/gtcfvirlld.html

[T58] Scala：函数定义
来源：http://dali.jqgfzy.top/Article/details/gtnqmvxpjd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj202588.top/Article/details/gtysbpdzsy.html

[T59] Scala：循环
来源：http://dali.dianchejie.cn/Article/details/gtyitqwmsz.html

for (i <- 1 to 10) println(i)
来源：http://dali.cheryme.top/Article/details/gtugkqnzlp.html

[T60] Scala：折叠
来源：http://dali.jinghuilouyu.cn/Article/details/gthytfdoqu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yongpay.top/Article/details/gtvgsgzkvw.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtvcvdgoxt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shzxlz.cn/Article/details/gtkmoroyul.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtlhfmmaal.html

[U01] Py：创建虚拟环境
来源：http://dali.jiagoushi.top/Article/details/gtvuplovxp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nanxuanxn.top/Article/details/gtsnhgzhok.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shuidangran.top/Article/details/gtxvwovopi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hnqzz.top/Article/details/gtcsihetht.html

[U03] Py：加载 .env 配置
来源：http://dali.pengpengdd.cyou/Article/details/gtwhsuffhp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xziqi.cn/Article/details/gtwgdjqdlb.html

[U04] Py：变量调试打印
来源：http://dali.nwbrower.top/Article/details/gtwoztmvia.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yonumen.top/Article/details/gtgopqzvte.html

[U05] Py：列表去重且保序
来源：http://dali.havefunace.top/Article/details/gtdsxvojmn.html

list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gtisbactqw.html

[U06] Py：合并两个字典
来源：http://dali.chenzaomai.com/Article/details/gtmznvsitq.html

{**a, **b}
来源：http://dali.jiagoushi.top/Article/details/gtxguncspf.html

[U07] Py：反转字典键值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetknymma.html

{v: k for k, v in d.items()}
来源：http://dali.xuetiantiany.cn/Article/details/gthuinmqwj.html

[U08] Py：展平二维列表
来源：http://dali.meibo888.top/Article/details/gtyycrfgje.html

[y for x in nested for y in x]
来源：http://dali.yj202588.top/Article/details/gtobabrxsa.html

[U09] Py：字典取最大值的键
来源：http://dali.quarkkingdee.top/Article/details/gtoptexoel.html

max(d, key=d.get)
来源：http://dali.yonumen.top/Article/details/gtgnfonqvm.html

[U10] Py：按值排序字典
来源：http://dali.zhixingplan.top/Article/details/gtfjchkyof.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.svipenyu.cn/Article/details/gttrgdduog.html

[U11] Py：生成器表达式
来源：http://dali.pycfn.com/Article/details/gtxruqouoo.html

(x * 2 for x in arr)
来源：http://dali.jyoumei.cn/Article/details/gtrqhkdidm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ydzc1.top/Article/details/gtgvoljleh.html

Counter(arr).most_common(3)
来源：http://dali.aibaodan.cn/Article/details/gthqcqqpxk.html

[U13] Py：固定长度队列
来源：http://dali.ybcxt.top/Article/details/gtopvhwvav.html

deque(maxlen=10)
来源：http://dali.hammf.cn/Article/details/gtigrdkjkq.html

[U14] Py：分组收集到列表
来源：http://dali.sxryk.cn/Article/details/gtmbyrzkve.html

defaultdict(list)
来源：http://dali.ppjwa.cn/Article/details/gtmzxyhpow.html

[U15] Py：高精度计时
来源：http://dali.yonumen.top/Article/details/gtikxbaric.html

t = time.perf_counter()
来源：http://dali.aibaodan.cn/Article/details/gthpdfcscr.html

[U16] Py：命令行参数解析
来源：http://dali.hysaishi.cn/Article/details/gtqusjmwvk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhongyouzk.top/Article/details/gtzwpkdauf.html

[U17] Py：初始化日志
来源：http://dali.xylfe.cn/Article/details/gtzjfdjqbi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ivvv.top/Article/details/gtsflzbnph.html

[U18] Py：预编译正则
来源：http://dali.jlsjyb.cn/Article/details/gtxboxjhhv.html

pat = re.compile(r"\d+")
来源：http://dali.dashuyun.cn/Article/details/gtgcohexic.html

[U19] Py：正则替换带回调
来源：http://dali.sweek.top/Article/details/gtshqhqeel.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.pengpengdd.cyou/Article/details/gtuuaukqxu.html

[U20] Py：缓存函数结果
来源：http://dali.jinghuilouyu.cn/Article/details/gtunlqmodu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.redwolf501.top/Article/details/gtwkancfcc.html

[U21] Py：自定义上下文管理器
来源：http://dali.yvedp.cn/Article/details/gtmalkfpeo.html

@contextlib.contextmanager
来源：http://dali.yvedp.cn/Article/details/gtgarovhzx.html

[U22] Py：矩阵转置
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkrrszli.html

list(zip(*m))
来源：http://dali.jqgfzy.top/Article/details/gtgwcqmqbw.html

[U23] Py：分块读取大文件
来源：http://dali.zhoulong.xyz/Article/details/gtpgbqcdic.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yuanzhike.top/Article/details/gtmkhsbckt.html

[U24] Py：路径操作
来源：http://dali.zhixingplan.top/Article/details/gtmwksjufx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.kuanghao11.cn/Article/details/gtycedgawq.html

[U25] Py：CSV 按字典读
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxzxmauj.html

csv.DictReader(f)
来源：http://dali.dianchejie.cn/Article/details/gtkhfhnyku.html

[U26] Py：并发下载
来源：http://dali.yonumen.top/Article/details/gtcoaqovkj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yvedp.cn/Article/details/gtzxlkmpfv.html

[U27] Py：异步 HTTP
来源：http://dali.chenlongwang.top/Article/details/gtjkeyvxmw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jiagoushi.top/Article/details/gtjzjrylxj.html

[U28] Py：类型别名
来源：http://dali.yj202588.top/Article/details/gtcsennavl.html

UserId = int
来源：http://dali.kuanghao11.cn/Article/details/gtfanndnou.html

[U29] Py：属性校验
来源：http://dali.0kj1m.cn/Article/details/gtbcuzsdoq.html

@property 与 @x.setter 配合
来源：http://dali.c1oappe.top/Article/details/gtjekawmzi.html

[U30] Py：数据类
来源：http://dali.hfpthk.cn/Article/details/gtdoxjjcxg.html

@dataclass(slots=True)
来源：http://dali.zhengqikj.top/Article/details/gtqsdjifep.html

[U31] Py：单测
来源：http://dali.ydzc1.top/Article/details/gtctgyiuzp.html

python -m pytest -q
来源：http://dali.xuetiantiany.cn/Article/details/gteipqxvgu.html

[U32] Py：代码格式化
来源：http://dali.daria6918.cn/Article/details/gtpdgfrtrl.html

ruff format . && ruff check --fix .
来源：http://dali.zhoulong.xyz/Article/details/gtjepuklet.html

[U33] Py：打包发布
来源：http://dali.xuetiantiany.cn/Article/details/gtdzcmpork.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.feifeiyinyue.top/Article/details/gtdjhjzeqv.html

[U34] Py：判断编码
来源：http://dali.hywenlv.cn/Article/details/gtlnkdbbxc.html

chardet.detect(raw)
来源：http://dali.cdnleiting.top/Article/details/gtsfvwnfkx.html

[U35] Py：发送邮件
来源：http://dali.zycfv.cn/Article/details/gthbmacccd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.havefunace.top/Article/details/gtajlaiwqi.html

[U36] Py：定时任务
来源：http://dali.zhengqikj.top/Article/details/gtzacktrdn.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgufenzy.top/Article/details/gtmebngfjr.html

[U37] Py：读写 Excel
来源：http://dali.gzhubu.top/Article/details/gtecmwjzaz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cheryme.top/Article/details/gtuptmnmkm.html

[U38] Py：获取脚本所在目录
来源：http://dali.c1oappe.top/Article/details/gtwxnjcytf.html

Path(__file__).resolve().parent
来源：http://dali.daxiang520.top/Article/details/gtoeoryfzx.html

[U39] Py：判断是否在交互环境
来源：http://dali.dianchejie.cn/Article/details/gtfnhhaypm.html

sys.stdout.isatty()
来源：http://dali.ybcxt.top/Article/details/gtsknefmfu.html

[U40] Py：打印到标准错误
来源：http://dali.hfpthk.cn/Article/details/gtxhlcswik.html

print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gtebimqvfr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cqqwz.cn/Article/details/gtvbhekjcd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xinyue.icu/Article/details/gtizpovtsg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.tian-w.cn/Article/details/gtvojjawli.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nwbrower.top/Article/details/gtqxllvwpr.html

[U43] PHP：声明命名空间
来源：http://dali.dashuyun.cn/Article/details/gtvkdqljzo.html

namespace App\Http;
来源：http://dali.tanke756.top/Article/details/gtuxstkhcm.html

[U44] PHP：开启严格类型
来源：http://dali.ydzc1.top/Article/details/gtobpuhuij.html

declare(strict_types=1);
来源：http://dali.smart0.xyz/Article/details/gtevrmanmy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.wangdashe.top/Article/details/gtvlbwuqra.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtxjcxhlyg.html

[U46] PHP：可空类型
来源：http://dali.cashguo.top/Article/details/gtsesldezq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gtzadwypgb.html

[U47] PHP：联合类型
来源：http://dali.9152youxi.cn/Article/details/gtqohtegva.html

int|string $id
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkvtwvcs.html

[U48] PHP：纯枚举
来源：http://dali.zhengqikj.top/Article/details/gthfmkgoml.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nanxuanxn.top/Article/details/gtupukksui.html


<!-- 参考信息 -->