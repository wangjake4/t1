代发 wailian999

int main(int argc, char **argv)
来源：http://dali.pycfn.com/Article/details/gtzbqnsahz.html

[S19] C：快速排序
来源：http://dali.sweek.top/Article/details/gtwnhkebtg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtskaqnyht.html

[S20] C：二分查找
来源：http://dali.chenlongwang.top/Article/details/gtxiyveglo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtywkhhqpv.html

[S21] C：字符类别判断
来源：http://dali.havefunace.top/Article/details/gtjyhqyuwy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zycfv.cn/Article/details/gttwipkhbu.html

[S22] C：字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gtaxqbqdyv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hywenlv.cn/Article/details/gtkwaxkryf.html

[S23] C：随机数
来源：http://dali.zhixingplan.top/Article/details/gttrpactbi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hongshengwenyu.top/Article/details/gtvnnkigys.html

[S24] C：获取本地时间
来源：http://dali.guannengcc.top/Article/details/gtdzjclfsa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hywenlv.cn/Article/details/gtjwqjyfuz.html

[S25] C：内存拷贝
来源：http://dali.birdmap.top/Article/details/gtymtmlwju.html

memcpy(dst, src, n);
来源：http://dali.guannengcc.top/Article/details/gtvejaelkh.html

[S26] C：内存清零
来源：http://dali.birdmap.top/Article/details/gtgfffvkcd.html

memset(a, 0, sizeof a);
来源：http://dali.havefunace.top/Article/details/gtlrjrfgfk.html

[S27] C：定义常量
来源：http://dali.iojbl.cn/Article/details/gtdkzmtupk.html

const double PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtputrbeio.html

[S28] C：静态变量
来源：http://dali.jyoumei.cn/Article/details/gtcspxgunk.html

static int counter = 0;
来源：http://dali.havefunace.top/Article/details/gthzxtlwzh.html

[S29] C：变参函数
来源：http://dali.yangfankeji.com/Article/details/gtdioockon.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjbecwkb.html

[S30] C：头文件保护
来源：http://dali.vqdsnc.cn/Article/details/gtqkapfazw.html

#ifndef X_H
来源：http://dali.9152youxi.cn/Article/details/gtpgllylku.html

#define X_H
来源：http://dali.yuanzhike.top/Article/details/gtopffjtld.html

#endif
来源：http://dali.sysykeji.top/Article/details/gtmofoittv.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gtblkacjyg.html

#include <iostream>
来源：http://dali.dashuyun.cn/Article/details/gtpqfqcafr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuxming.cn/Article/details/gtsuebxuux.html

[S32] C++：字符串
来源：http://dali.mhx1999.top/Article/details/gtyustujvz.html

std::string s = "hi";  s += "!";
来源：http://dali.chenjidiqi.icu/Article/details/gteqmpkhgz.html

[S33] C++：vector 增删
来源：http://dali.pycfn.com/Article/details/gtmqenlftb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjwmpryl.html

[S34] C++：遍历 vector
来源：http://dali.cucudq.cn/Article/details/gtujstwtjb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.meibo888.top/Article/details/gtvrwxpxgv.html

[S35] C++：map
来源：http://dali.fzhhl.top/Article/details/gtnrwoiqbh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtkhxtnnzg.html

[S36] C++：unordered_map
来源：http://dali.shangyingyoupin.top/Article/details/gtvlnyibio.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtfzfaqbmh.html

[S37] C++：set
来源：http://dali.tanke756.top/Article/details/gtybddxagp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhixingplan.top/Article/details/gtavsjxbhz.html

[S38] C++：排序
来源：http://dali.guowangkeji.top/Article/details/gtbnlmdmxe.html

std::sort(v.begin(), v.end());
来源：http://dali.yuanzhike.top/Article/details/gtttzbmhya.html

[S39] C++：自定义比较器排序
来源：http://dali.wangshuangyany.cn/Article/details/gtocncsgqc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zdqjudy.top/Article/details/gtpxszoiqz.html

[S40] C++：查找元素
来源：http://dali.wangdashe.top/Article/details/gtcxhmuxpj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjwzxguc.html

[S41] C++：类与构造函数
来源：http://dali.xylfe.cn/Article/details/gtyarmgips.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guowangkeji.top/Article/details/gtkstamteh.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigufen.top/Article/details/gtkxuclqut.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgszwiltf.html

[S43] C++：智能指针
来源：http://dali.yueranfly.top/Article/details/gtlcnarvog.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258.top/Article/details/gtchrgriud.html

[S44] C++：引用传参
来源：http://dali.smart0.xyz/Article/details/gtzwlgaljq.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrhuvlkk.html

[S45] C++：lambda
来源：http://dali.chenzaomai.com/Article/details/gtvlwbnvlg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnxiangtu.top/Article/details/gtrssivvuk.html

[S46] C++：函数模板
来源：http://dali.zhongyouzk.top/Article/details/gtrtztobxu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzzkbkix.html

[S47] C++：结构化绑定遍历
来源：http://dali.sufxvd.cn/Article/details/gtusdofsxh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnxiangtu.top/Article/details/gtemhqvuud.html

[S48] C++：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtcalplkme.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmidqfhr.html

while (std::getline(in, line)) { }
来源：http://dali.cucudq.cn/Article/details/gtznylwbmo.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gttlncvbsc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gotoacloud.top/Article/details/gtndehahpz.html

[S50] C++：格式化数字
来源：http://dali.gzhubu.top/Article/details/gtpkdapztq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqoxaxuur.html

[S51] C++：显式类型转换
来源：http://dali.0kj1m.cn/Article/details/gtntonwtsh.html

static_cast<double>(a) / b
来源：http://dali.cdnleiting.top/Article/details/gttzuhoagl.html

[S52] C++：const 与 noexcept
来源：http://dali.0kj1m.cn/Article/details/gtuqweirdt.html

int size() const noexcept { return n_; }
来源：http://dali.haohaochexian.top/Article/details/gtnhispiym.html

[S53] C++：移动语义
来源：http://dali.yongpay.top/Article/details/gtauyvemmh.html

std::vector<int> w = std::move(v);
来源：http://dali.daxiang520.top/Article/details/gtoyeegkjq.html

[S54] C++：异常处理
来源：http://dali.iojbl.cn/Article/details/gtlafxoyee.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfnwutkq.html

[S55] C++：结构化绑定
来源：http://dali.ybcxt.top/Article/details/gtrkxsmans.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zdqjudy.top/Article/details/gthxfsnjrq.html

[S56] C++：optional
来源：http://dali.jqgufenzy.top/Article/details/gtwkhsyiws.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zycfv.cn/Article/details/gtiahnqssz.html

[S57] C++：编译期常量
来源：http://dali.feifeiyinyue.top/Article/details/gthvkrewbc.html

constexpr int N = 10;
来源：http://dali.yonumen.top/Article/details/gtkaqlzalf.html

[S58] C++：命名空间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbogjmjr.html

namespace ns { int f() { return 1; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtwskvrxes.html

[S59] C++：静态断言
来源：http://dali.yuxming.cn/Article/details/gtcllyfuuo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtonjwnp.html

[S60] C++：遍历并删除元素
来源：http://dali.zycfv.cn/Article/details/gtzcdmusjq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gtsgzcyxfi.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtzzfqwxwl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gttwdhytcy.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtrxyluszp.html

[T01] Kotlin：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtrjwbkymv.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflgyrfeb.html

[T02] Kotlin：变量
来源：http://dali.redwolf501.top/Article/details/gtgqzmstxa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sysykeji.top/Article/details/gteassdxhq.html

[T03] Kotlin：字符串模板
来源：http://dali.fengsongda.top/Article/details/gtvchkighf.html

"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gtuzxsrpmd.html

[T04] Kotlin：空安全
来源：http://dali.hnxiangtu.top/Article/details/gthpcpjdee.html

val n: String? = null;  n?.length
来源：http://dali.yj20258.top/Article/details/gtexkwqxpd.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigufen.top/Article/details/gtuvpbojir.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guannengcc.top/Article/details/gtwhlfmqrc.html

[T06] Kotlin：集合映射
来源：http://dali.redwolf501.top/Article/details/gtblilfuug.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cashguo.top/Article/details/gthymrnewq.html

[T07] Kotlin：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gtdrgrnbuq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fengsongda.top/Article/details/gtbfqqxxty.html

[T08] Kotlin：数据类
来源：http://dali.jiagoushi.top/Article/details/gtoaxkmqjc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gtuihkqonj.html

[T09] Kotlin：扩展函数
来源：http://dali.xylfe.cn/Article/details/gtfzcnltnq.html

fun String.exclaim() = this + "!"
来源：http://dali.daria6918.cn/Article/details/gthggtabkv.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqrslwwc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxinkj.top/Article/details/gtmrjkdzfp.html

[T11] Kotlin：协程
来源：http://dali.cucudq.cn/Article/details/gtklehybkk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nanxinkj.top/Article/details/gtlnhudhcz.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigufen.top/Article/details/gtcpcusexz.html

val (a, b) = Pair(1, 2)
来源：http://dali.yueranfly.top/Article/details/gtojepvhlp.html

[T13] Kotlin：只读 Map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclqmdlih.html

val m = mapOf("a" to 1)
来源：http://dali.nanxuanxn.top/Article/details/gtfslcrxar.html

[T14] Kotlin：循环
来源：http://dali.chenlongwang.top/Article/details/gtcnfsjizs.html

for (i in 1..10) println(i)
来源：http://dali.daria6918.cn/Article/details/gtjgztktgp.html

[T15] Kotlin：接口
来源：http://dali.jlsjyb.cn/Article/details/gtfciyvkkq.html

interface Shape { fun area(): Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyeppqkwv.html

[T16] Swift：Hello World
来源：http://dali.yvedp.cn/Article/details/gttdkidjcs.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gtrehzwcve.html

[T17] Swift：变量与常量
来源：http://dali.fzhhl.top/Article/details/gttpldgrbs.html

var a = 1;  let b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtaqkwzffg.html

[T18] Swift：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtnbpzqryd.html

"值: \(b)"
来源：http://dali.yueranfly.top/Article/details/gtluwxwzpi.html

[T19] Swift：可选绑定
来源：http://dali.zhiwuduotai.top/Article/details/gthhoahkdp.html

if let n = opt { print(n) }
来源：http://dali.xylfe.cn/Article/details/gttcsachjq.html

[T20] Swift：数组操作
来源：http://dali.ppjwa.cn/Article/details/gtfvayubxn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258.top/Article/details/gtqpyfdkec.html

[T21] Swift：遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtffzhsljt.html

for x in a { print(x) }
来源：http://dali.chenlongwang.top/Article/details/gtktuaybty.html

[T22] Swift：字典
来源：http://dali.jqgufenzy.top/Article/details/gtqmwniiyr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fengsongda.top/Article/details/gtkffokbhp.html

[T23] Swift：函数
来源：http://dali.birdmap.top/Article/details/gthrndkhox.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenlongwang.top/Article/details/gtxvaqwafm.html

[T24] Swift：闭包
来源：http://dali.smart0.xyz/Article/details/gtdjnqivhn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zdqjudy.top/Article/details/gtnzvzrhrt.html

[T25] Swift：结构体
来源：http://dali.9152youxi.cn/Article/details/gtusjrjfyi.html

struct P { var x: Int }
来源：http://dali.yvedp.cn/Article/details/gtamxubxzy.html

[T26] Swift：类与重写
来源：http://dali.vqdsnc.cn/Article/details/gtjpoycwqd.html

class A: Base { override func f() {} }
来源：http://dali.kuanghao11.cn/Article/details/gtdtessmsi.html

[T27] Swift：错误处理
来源：http://dali.jianghu66.top/Article/details/gtuzmccsyy.html

do { try f() } catch { print(error) }
来源：http://dali.hammf.cn/Article/details/gthnkdvxcf.html

[T28] Swift：枚举
来源：http://dali.chenlongwang.top/Article/details/gtmvyutxch.html

enum Color { case red, green }
来源：http://dali.feifeiyinyue.top/Article/details/gtpvubzrab.html

[T29] Swift：guard 提前返回
来源：http://dali.wangshuangyany.cn/Article/details/gtwevkarzc.html

guard let x = opt else { return }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjairobd.html

[T30] Swift：协议
来源：http://dali.cheryme.top/Article/details/gtbbkdydgz.html

protocol Shape { func area() -> Double }
来源：http://dali.gogol.net.cn/Article/details/gtutadwaae.html

[T31] Lua：Hello World
来源：http://dali.iojbl.cn/Article/details/gtmhcblfro.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfggljtar.html

[T32] Lua：局部变量
来源：http://dali.mhx1999.top/Article/details/gteizjvhqc.html

local a = 1
来源：http://dali.jiagoushi.top/Article/details/gttmufbvma.html

[T33] Lua：表（数组）
来源：http://dali.yuanzhike.top/Article/details/gttqjjrdtn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tanke756.top/Article/details/gtfkzcilgo.html

[T34] Lua：遍历表
来源：http://dali.cucudq.cn/Article/details/gtylnkksec.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinqigufen.top/Article/details/gtletbljzq.html

[T35] Lua：字典表
来源：http://dali.mhx1999.top/Article/details/gteqgqxqtx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.daxiang520.top/Article/details/gtjyevxabc.html

[T36] Lua：函数
来源：http://dali.hywenlv.cn/Article/details/gtiaxdyvff.html

function add(a, b) return a + b end
来源：http://dali.yuanzhike.top/Article/details/gtushwaqqi.html

[T37] Lua：字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gtteualqah.html

"a" .. "b"
来源：http://dali.chenjidiqi.icu/Article/details/gtfhcoxdsq.html

[T38] Lua：条件
来源：http://dali.svipenyu.cn/Article/details/gtpmrloldf.html

if x > 0 then print("正") end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtneoeozam.html

[T39] Lua：模式匹配
来源：http://dali.bjfxy.top/Article/details/gtnbpnwslv.html

string.find(s, "%d+")
来源：http://dali.dashuyun.cn/Article/details/gtprdccxep.html

[T40] Lua：元表
来源：http://dali.bjfxy.top/Article/details/gtoobnsazq.html

setmetatable({}, { __index = base })
来源：http://dali.tian-w.cn/Article/details/gtmiybcqjx.html

[T41] Perl：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtwaunzbwc.html

print "Hello\n";
来源：http://dali.316326.xyz/Article/details/gtomwvqmjf.html

[T42] Perl：变量类型
来源：http://dali.kuanghao11.cn/Article/details/gttnjmtxjt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.smart0.xyz/Article/details/gtdamifdbf.html

[T43] Perl：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtsozffpmn.html

"值: $a"
来源：http://dali.jinqigfzy.top/Article/details/gtdsbyngap.html

[T44] Perl：条件
来源：http://dali.ppjwa.cn/Article/details/gthfzuvbhl.html

if ($a > 0) { print "正"; }
来源：http://dali.ivvv.top/Article/details/gtflopxsry.html

[T45] Perl：数组遍历
来源：http://dali.daria6918.cn/Article/details/gtiyljeyqq.html

for my $x (@arr) { print $x; }
来源：http://dali.yuxming.cn/Article/details/gtlvqmplsy.html

[T46] Perl：哈希操作
来源：http://dali.cdnleiting.top/Article/details/gtrrvapydv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hysaishi.cn/Article/details/gtwmyspgyq.html

[T47] Perl：正则捕获
来源：http://dali.gzhubu.top/Article/details/gtxfksiyyq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.smart0.xyz/Article/details/gtvwoicomi.html

[T48] Perl：正则替换
来源：http://dali.jinqigufen.top/Article/details/gtyhfakxsi.html

$s =~ s/old/new/g;
来源：http://dali.wangdashe.top/Article/details/gtcphkmwnw.html

[T49] Perl：函数
来源：http://dali.0kj1m.cn/Article/details/gtiarsyesf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtdiewblrx.html

[T50] Perl：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtvykzxynh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jyoumei.cn/Article/details/gtdqywcpbu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.0kj1m.cn/Article/details/gtyudrfbmx.html

[T51] Scala：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtzoifnogz.html

println("Hello")
来源：http://dali.fengsongda.top/Article/details/gtdnmfhefx.html

[T52] Scala：变量
来源：http://dali.gaohongyu789.top/Article/details/gtcnzizoqg.html

val a = 1;  var b = 2
来源：http://dali.gogol.net.cn/Article/details/gtjzqrioib.html

[T53] Scala：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gtgyossslb.html

s"值: $b"
来源：http://dali.ydzc1.top/Article/details/gtwjjhykbd.html

[T54] Scala：集合映射
来源：http://dali.hfpthk.cn/Article/details/gtxtawlqjy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwtzqepg.html

[T55] Scala：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gtgbrkohfc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiipnzgeb.html

[T56] Scala：样例类
来源：http://dali.yueranfly.top/Article/details/gtkjrfcrjm.html

case class User(name: String, age: Int)
来源：http://dali.hammf.cn/Article/details/gtnfpgikgw.html

[T57] Scala：模式匹配
来源：http://dali.yvedp.cn/Article/details/gtxsmgpaxd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.fengsongda.top/Article/details/gtjjipxbsq.html

[T58] Scala：函数定义
来源：http://dali.dianchejie.cn/Article/details/gtcwkacmve.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guannengcc.top/Article/details/gtfswjnblu.html

[T59] Scala：循环
来源：http://dali.ehwqpu.com/Article/details/gtigvbyeex.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtfgzihuzf.html

[T60] Scala：折叠
来源：http://dali.iojbl.cn/Article/details/gthgqzhbtx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.pycfn.com/Article/details/gtxslgquus.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtvhskflre.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tianlin.xyz/Article/details/gtzrtsaqyn.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtayxaldro.html

[U01] Py：创建虚拟环境
来源：http://dali.iojbl.cn/Article/details/gthqcifyon.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.mhx1999.top/Article/details/gtgklltnhx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sufxvd.cn/Article/details/gtzspzpicp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhixingplan.top/Article/details/gtzsmnknuc.html

[U03] Py：加载 .env 配置
来源：http://dali.sweek.top/Article/details/gtiivhmrzz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.pycfn.com/Article/details/gtjrxkyyvd.html

[U04] Py：变量调试打印
来源：http://dali.jinghuilouyu.cn/Article/details/gtttbiusaj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.birdmap.top/Article/details/gtftjvsuon.html

[U05] Py：列表去重且保序
来源：http://dali.wangshuangyany.cn/Article/details/gtnxmvbukd.html

list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gtbccardsa.html

[U06] Py：合并两个字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gttydrtdzm.html

{**a, **b}
来源：http://dali.cheryme.top/Article/details/gtuhqmnbiq.html

[U07] Py：反转字典键值
来源：http://dali.hfpthk.cn/Article/details/gtcrhiyfdk.html

{v: k for k, v in d.items()}
来源：http://dali.zhiwuduotai.top/Article/details/gtxfczpmlp.html

[U08] Py：展平二维列表
来源：http://dali.jiagoushi.top/Article/details/gtmamerxew.html

[y for x in nested for y in x]
来源：http://dali.gzhubu.top/Article/details/gtzsvvnejo.html

[U09] Py：字典取最大值的键
来源：http://dali.hammf.cn/Article/details/gtrnogbglo.html

max(d, key=d.get)
来源：http://dali.jiagoushi.top/Article/details/gtmdrljmya.html

[U10] Py：按值排序字典
来源：http://dali.9152youxi.cn/Article/details/gtnphmesds.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.dianchejie.cn/Article/details/gtbstnzakp.html

[U11] Py：生成器表达式
来源：http://dali.zhongyouzk.top/Article/details/gtxloiuwqh.html

(x * 2 for x in arr)
来源：http://dali.bjfxy.top/Article/details/gtcdafsolm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.mhx1999.top/Article/details/gtnhohrayx.html

Counter(arr).most_common(3)
来源：http://dali.zycfv.cn/Article/details/gtbjsqlmqm.html

[U13] Py：固定长度队列
来源：http://dali.fengsongda.top/Article/details/gtpxgpgpfv.html

deque(maxlen=10)
来源：http://dali.svipenyu.cn/Article/details/gtusoepixu.html

[U14] Py：分组收集到列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwncfjuly.html

defaultdict(list)
来源：http://dali.zhongyouzk.top/Article/details/gtezfycvtl.html

[U15] Py：高精度计时
来源：http://dali.zhongyouzk.top/Article/details/gtkjlbsban.html

t = time.perf_counter()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbytvdkwc.html

[U16] Py：命令行参数解析
来源：http://dali.meibo888.top/Article/details/gtvsqieigc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhixingplan.top/Article/details/gtvhwrzfqg.html

[U17] Py：初始化日志
来源：http://dali.snrcjt.cn/Article/details/gtxhtovuyd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gogol.net.cn/Article/details/gtkidhrwpj.html

[U18] Py：预编译正则
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumozjzsw.html

pat = re.compile(r"\d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtksthuzos.html

[U19] Py：正则替换带回调
来源：http://dali.mhx1999.top/Article/details/gtmkatnrto.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuanzhike.top/Article/details/gttlxwfkwc.html

[U20] Py：缓存函数结果
来源：http://dali.gogol.net.cn/Article/details/gtbjrnttto.html

@functools.lru_cache(maxsize=None)
来源：http://dali.daxiang520.top/Article/details/gtsczeatqs.html

[U21] Py：自定义上下文管理器
来源：http://dali.sufxvd.cn/Article/details/gtwgyuhsap.html

@contextlib.contextmanager
来源：http://dali.gotoacloud.top/Article/details/gtssbcgtuj.html

[U22] Py：矩阵转置
来源：http://dali.yueranfly.top/Article/details/gtxyugkskj.html

list(zip(*m))
来源：http://dali.jinqigfzy.top/Article/details/gtckobunke.html

[U23] Py：分块读取大文件
来源：http://dali.ydzc1.top/Article/details/gtjekmwrrm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.daria6918.cn/Article/details/gtzocsaolj.html

[U24] Py：路径操作
来源：http://dali.shzxlz.cn/Article/details/gtugldgzqz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gtaojxiarx.html

[U25] Py：CSV 按字典读
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzobfbbg.html

csv.DictReader(f)
来源：http://dali.meibo888.top/Article/details/gtompjedry.html

[U26] Py：并发下载
来源：http://dali.nwbrower.top/Article/details/gtivwvojwq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenlongwang.top/Article/details/gtjokbaeos.html

[U27] Py：异步 HTTP
来源：http://dali.redwolf501.top/Article/details/gtgprfyrlp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzhnrcyc.html

[U28] Py：类型别名
来源：http://dali.yongpay.top/Article/details/gtmdtjmlrf.html

UserId = int
来源：http://dali.sysykeji.top/Article/details/gtiaxztozt.html

[U29] Py：属性校验
来源：http://dali.ppjwa.cn/Article/details/gtsavflykt.html

@property 与 @x.setter 配合
来源：http://dali.wangshuangyany.cn/Article/details/gtaublnfgx.html

[U30] Py：数据类
来源：http://dali.yuanzhike.top/Article/details/gtcgntjvcy.html

@dataclass(slots=True)
来源：http://dali.ivvv.top/Article/details/gtqmzmxsmn.html

[U31] Py：单测
来源：http://dali.zhongyouzk.top/Article/details/gtntzplbga.html

python -m pytest -q
来源：http://dali.jqgfzy.top/Article/details/gtpojfnwzz.html

[U32] Py：代码格式化
来源：http://dali.chenlongwang.top/Article/details/gtabiruplr.html

ruff format . && ruff check --fix .
来源：http://dali.0kj1m.cn/Article/details/gtudzbrdtn.html

[U33] Py：打包发布
来源：http://dali.redwolf501.top/Article/details/gtiieugdzw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvmmsdnp.html

[U34] Py：判断编码
来源：http://dali.nanxuanxn.top/Article/details/gtgbuoxszm.html

chardet.detect(raw)
来源：http://dali.chenzaomai.com/Article/details/gtzjxdcwxc.html

[U35] Py：发送邮件
来源：http://dali.sweek.top/Article/details/gtuvyhfjqx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhixingplan.top/Article/details/gtydukyxei.html

[U36] Py：定时任务
来源：http://dali.xinyue.icu/Article/details/gtuxumkyxs.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgufenzy.top/Article/details/gthwrxwnrc.html

[U37] Py：读写 Excel
来源：http://dali.0kj1m.cn/Article/details/gtybqkcmjw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gogol.net.cn/Article/details/gtivlwrwpb.html

[U38] Py：获取脚本所在目录
来源：http://dali.zdqjudy.top/Article/details/gtuwcigyvj.html

Path(__file__).resolve().parent
来源：http://dali.yueranfly.top/Article/details/gtgiricwcr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zycfv.cn/Article/details/gtuskievci.html

sys.stdout.isatty()
来源：http://dali.yj202588.top/Article/details/gtnexjjano.html

[U40] Py：打印到标准错误
来源：http://dali.jqgfzy.top/Article/details/gtkafynfrs.html

print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gtnayiuxmg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gogol.net.cn/Article/details/gtvfoujhnt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.fengsongda.top/Article/details/gtjgpumwix.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ivvv.top/Article/details/gtdnuewxcq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hywenlv.cn/Article/details/gtegmchyhu.html


<!-- 参考信息 -->