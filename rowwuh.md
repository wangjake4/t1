代发 wailian999

int main(int argc, char **argv)
来源：http://dali.feifeiyinyue.top/Article/details/gtmmftuwzg.html

[S19] C：快速排序
来源：http://dali.0kj1m.cn/Article/details/gtwburimnt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtxyzlkzzo.html

[S20] C：二分查找
来源：http://dali.jinqigfzy.top/Article/details/gtyhbxawij.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gtissjnwfh.html

[S21] C：字符类别判断
来源：http://dali.zhiwuduotai.top/Article/details/gtxkediawx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zycfv.cn/Article/details/gtcrntocqi.html

[S22] C：字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtljyznhkh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.svipenyu.cn/Article/details/gtvvieylgf.html

[S23] C：随机数
来源：http://dali.vqdsnc.cn/Article/details/gtttnyejuj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.quarkkingdee.top/Article/details/gtmtgcjgbs.html

[S24] C：获取本地时间
来源：http://dali.hfpthk.cn/Article/details/gtdhelpszf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hongshengwenyu.top/Article/details/gtavmsvbwe.html

[S25] C：内存拷贝
来源：http://dali.aibaodan.cn/Article/details/gtvtqlixmg.html

memcpy(dst, src, n);
来源：http://dali.9152youxi.cn/Article/details/gtfgsicmrd.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gtaxhabses.html

memset(a, 0, sizeof a);
来源：http://dali.meibo888.top/Article/details/gtvkvnweay.html

[S27] C：定义常量
来源：http://dali.jyoumei.cn/Article/details/gtbmvfdjkm.html

const double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtxildjkry.html

[S28] C：静态变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtihoewfoq.html

static int counter = 0;
来源：http://dali.zhengqikj.top/Article/details/gtnqdcxcar.html

[S29] C：变参函数
来源：http://dali.pycfn.com/Article/details/gtlpmizgqx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.smart0.xyz/Article/details/gtfcemvddc.html

[S30] C：头文件保护
来源：http://dali.yj20258.top/Article/details/gtsnhdzsxh.html

#ifndef X_H
来源：http://dali.nwbrower.top/Article/details/gtavszoyae.html

#define X_H
来源：http://dali.yongpay.top/Article/details/gtaocbddaq.html

#endif
来源：http://dali.sweek.top/Article/details/gtsklldakx.html

[S31] C++：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtzunrmqzd.html

#include <iostream>
来源：http://dali.316326.xyz/Article/details/gtzjwjfnxj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjowywvlx.html

[S32] C++：字符串
来源：http://dali.daxiang520.top/Article/details/gtxxsehtnt.html

std::string s = "hi";  s += "!";
来源：http://dali.cashguo.top/Article/details/gtupeottog.html

[S33] C++：vector 增删
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcswhabq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gtgbezqyiq.html

[S34] C++：遍历 vector
来源：http://dali.xuetiantiany.cn/Article/details/gtldkpzqsb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakhcwgit.html

[S35] C++：map
来源：http://dali.cucudq.cn/Article/details/gtbvnwhytx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtwkxgksed.html

[S36] C++：unordered_map
来源：http://dali.chenjidiqi.icu/Article/details/gtrigqgzch.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtwcsguszq.html

[S37] C++：set
来源：http://dali.yvedp.cn/Article/details/gtktzltgpl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.9152youxi.cn/Article/details/gtqoggment.html

[S38] C++：排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjclahpy.html

std::sort(v.begin(), v.end());
来源：http://dali.dashuyun.cn/Article/details/gtwwmvkjjm.html

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqxuhemr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangshuangyany.cn/Article/details/gtgkgrjhfx.html

[S40] C++：查找元素
来源：http://dali.guowangkeji.top/Article/details/gtttqsvrma.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xylfe.cn/Article/details/gttwznfjsz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtoloxlcns.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gotoacloud.top/Article/details/gtebmpglns.html

[S42] C++：继承与虚函数
来源：http://dali.haohaochexian.top/Article/details/gtgandmnpe.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj202588.top/Article/details/gtsmeutsyw.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gtownxfmkq.html

auto p = std::make_unique<int>(5);
来源：http://dali.cheryme.top/Article/details/gtnzoitpoo.html

[S44] C++：引用传参
来源：http://dali.sxryk.cn/Article/details/gtsuqgzpzn.html

void inc(int &x) { ++x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtatcaotje.html

[S45] C++：lambda
来源：http://dali.shzxlz.cn/Article/details/gtseukoter.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.feifeiyinyue.top/Article/details/gtzyaabntd.html

[S46] C++：函数模板
来源：http://dali.jinqigufen.top/Article/details/gtshgynzcf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.birdmap.top/Article/details/gtmzkotaaj.html

[S47] C++：结构化绑定遍历
来源：http://dali.yueranfly.top/Article/details/gtgrutsoox.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuanzhike.top/Article/details/gtxacxbkuo.html

[S48] C++：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtxhknozlw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sxryk.cn/Article/details/gtwnsqbkyl.html

while (std::getline(in, line)) { }
来源：http://dali.hywenlv.cn/Article/details/gtgvefnnwx.html

[S49] C++：写文件
来源：http://dali.xylfe.cn/Article/details/gtoorujpep.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigfzy.top/Article/details/gtpwenojxv.html

[S50] C++：格式化数字
来源：http://dali.aibaodan.cn/Article/details/gtsdhfwztf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtupijnitp.html

[S51] C++：显式类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrejmwyde.html

static_cast<double>(a) / b
来源：http://dali.jianghu66.top/Article/details/gtkcepzkgb.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gtpsftloar.html

int size() const noexcept { return n_; }
来源：http://dali.bjfxy.top/Article/details/gtbxktrijf.html

[S53] C++：移动语义
来源：http://dali.hnxiangtu.top/Article/details/gtnzfuvuyt.html

std::vector<int> w = std::move(v);
来源：http://dali.chenjidiqi.icu/Article/details/gtyyhkzwup.html

[S54] C++：异常处理
来源：http://dali.hongshengwenyu.top/Article/details/gtngepqahv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenlongwang.top/Article/details/gtempbofgr.html

[S55] C++：结构化绑定
来源：http://dali.cheryme.top/Article/details/gtyaeqhywe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sxryk.cn/Article/details/gtthyguuha.html

[S56] C++：optional
来源：http://dali.wangshuangyany.cn/Article/details/gtyvwgtesb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fengsongda.top/Article/details/gtstqzjxfc.html

[S57] C++：编译期常量
来源：http://dali.mhx1999.top/Article/details/gtsxorcprm.html

constexpr int N = 10;
来源：http://dali.ydzc1.top/Article/details/gtyvnnpoir.html

[S58] C++：命名空间
来源：http://dali.guannengcc.top/Article/details/gtkoqhpyqd.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnxiangtu.top/Article/details/gtjltygvho.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyerpbmtx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pycfn.com/Article/details/gtjvzzepro.html

[S60] C++：遍历并删除元素
来源：http://dali.zhengqikj.top/Article/details/gtpdnuwkxe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gtxarivymt.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtzppcfsva.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gtweynvhbn.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtbsduibsn.html

[T01] Kotlin：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtntqjoisp.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtoyykqgzr.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gtwigxahnq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.daxiang520.top/Article/details/gtvgxottnz.html

[T03] Kotlin：字符串模板
来源：http://dali.haohaochexian.top/Article/details/gtoycowryn.html

"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gtqgawijgj.html

[T04] Kotlin：空安全
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuysrsrde.html

val n: String? = null;  n?.length
来源：http://dali.tian-w.cn/Article/details/gthvhcugog.html

[T05] Kotlin：when 表达式
来源：http://dali.gogol.net.cn/Article/details/gtkajpgcid.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yvedp.cn/Article/details/gtsmrxhmkx.html

[T06] Kotlin：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gthufneqpx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pycfn.com/Article/details/gtjxsfryfh.html

[T07] Kotlin：集合过滤
来源：http://dali.haohaochexian.top/Article/details/gtqofyassq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gtkuvzccgn.html

[T08] Kotlin：数据类
来源：http://dali.yj20258.top/Article/details/gtbducxuvt.html

data class User(val name: String, val age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtxsbnbeva.html

[T09] Kotlin：扩展函数
来源：http://dali.gaohongyu789.top/Article/details/gtpvrsfuif.html

fun String.exclaim() = this + "!"
来源：http://dali.hysaishi.cn/Article/details/gtczcyridt.html

[T10] Kotlin：默认参数
来源：http://dali.svipenyu.cn/Article/details/gtcgnyiibt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shangyingyoupin.top/Article/details/gthiqciplz.html

[T11] Kotlin：协程
来源：http://dali.haohaochexian.top/Article/details/gtpnuwekla.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.kuanghao11.cn/Article/details/gtdwwnsxry.html

[T12] Kotlin：解构声明
来源：http://dali.andypj.xyz/Article/details/gtqexvqkxv.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gtfyqxaqxl.html

[T13] Kotlin：只读 Map
来源：http://dali.aibaodan.cn/Article/details/gtzrgxcdim.html

val m = mapOf("a" to 1)
来源：http://dali.0kj1m.cn/Article/details/gtpxhdhdfz.html

[T14] Kotlin：循环
来源：http://dali.hnxiangtu.top/Article/details/gtlticoanp.html

for (i in 1..10) println(i)
来源：http://dali.meibo888.top/Article/details/gturdtbosk.html

[T15] Kotlin：接口
来源：http://dali.chenlongwang.top/Article/details/gtnzodjobh.html

interface Shape { fun area(): Double }
来源：http://dali.yuanzhike.top/Article/details/gtsopdbuap.html

[T16] Swift：Hello World
来源：http://dali.guannengcc.top/Article/details/gtlscjjywi.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtcwongofd.html

[T17] Swift：变量与常量
来源：http://dali.wangdashe.top/Article/details/gtuekorpyy.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtubfmsnfh.html

[T18] Swift：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtegwgabqb.html

"值: \(b)"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwyyrrrhu.html

[T19] Swift：可选绑定
来源：http://dali.jqgufenzy.top/Article/details/gtvodibgwm.html

if let n = opt { print(n) }
来源：http://dali.yongpay.top/Article/details/gthudtnjkn.html

[T20] Swift：数组操作
来源：http://dali.hammf.cn/Article/details/gthojnuxcs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sweek.top/Article/details/gtetqmmupv.html

[T21] Swift：遍历
来源：http://dali.jqgfzy.top/Article/details/gtqavjvjte.html

for x in a { print(x) }
来源：http://dali.pengpengdd.cyou/Article/details/gtnpdalrov.html

[T22] Swift：字典
来源：http://dali.sufxvd.cn/Article/details/gtsjfamxsh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhengqikj.top/Article/details/gtbbpfmawm.html

[T23] Swift：函数
来源：http://dali.shuidangran.top/Article/details/gtmkylymjh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrinycsc.html

[T24] Swift：闭包
来源：http://dali.hongshengwenyu.top/Article/details/gtyvkibymu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shuidangran.top/Article/details/gtarvnstjb.html

[T25] Swift：结构体
来源：http://dali.nwbrower.top/Article/details/gtzhhlqljk.html

struct P { var x: Int }
来源：http://dali.pengpengdd.cyou/Article/details/gtntxpueut.html

[T26] Swift：类与重写
来源：http://dali.xziqi.cn/Article/details/gtmblavpwo.html

class A: Base { override func f() {} }
来源：http://dali.gzhubu.top/Article/details/gtqzwbcnqy.html

[T27] Swift：错误处理
来源：http://dali.hywenlv.cn/Article/details/gteddfzleb.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258.top/Article/details/gtjrdicqqe.html

[T28] Swift：枚举
来源：http://dali.smart0.xyz/Article/details/gtqtcqlpwu.html

enum Color { case red, green }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikprizbl.html

[T29] Swift：guard 提前返回
来源：http://dali.dashuyun.cn/Article/details/gtqfrsnebq.html

guard let x = opt else { return }
来源：http://dali.pengpengdd.cyou/Article/details/gtmscyiniv.html

[T30] Swift：协议
来源：http://dali.sweek.top/Article/details/gtggsrarfq.html

protocol Shape { func area() -> Double }
来源：http://dali.yuxming.cn/Article/details/gthietqttk.html

[T31] Lua：Hello World
来源：http://dali.hammf.cn/Article/details/gtkbyvaniq.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpoowinuw.html

[T32] Lua：局部变量
来源：http://dali.meibo888.top/Article/details/gteqfyilqs.html

local a = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvqdwvow.html

[T33] Lua：表（数组）
来源：http://dali.yj202588.top/Article/details/gtuonudjap.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daria6918.cn/Article/details/gtcybpxqji.html

[T34] Lua：遍历表
来源：http://dali.zhengqikj.top/Article/details/gtzasudajl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuxming.cn/Article/details/gtxmlnnlco.html

[T35] Lua：字典表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbhuhwvu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtfdiaaanh.html

[T36] Lua：函数
来源：http://dali.shuidangran.top/Article/details/gtlurwhggr.html

function add(a, b) return a + b end
来源：http://dali.nanxuanxn.top/Article/details/gthvtoivup.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gtmpulldbv.html

"a" .. "b"
来源：http://dali.sxryk.cn/Article/details/gtlmiazeni.html

[T38] Lua：条件
来源：http://dali.yangfankeji.com/Article/details/gtojpwyhkm.html

if x > 0 then print("正") end
来源：http://dali.aizwys.cn/Article/details/gttzrlyhma.html

[T39] Lua：模式匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuytniikq.html

string.find(s, "%d+")
来源：http://dali.meibo888.top/Article/details/gtqxqfvdft.html

[T40] Lua：元表
来源：http://dali.daria6918.cn/Article/details/gthtnafqfy.html

setmetatable({}, { __index = base })
来源：http://dali.gzhubu.top/Article/details/gtfwgrlcge.html

[T41] Perl：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtsvfdteiy.html

print "Hello\n";
来源：http://dali.aibaodan.cn/Article/details/gtsvmqvjku.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gtevjfczih.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cheryme.top/Article/details/gtpzopotyr.html

[T43] Perl：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtwazewlnj.html

"值: $a"
来源：http://dali.jlsjyb.cn/Article/details/gtjyhvsahb.html

[T44] Perl：条件
来源：http://dali.aizwys.cn/Article/details/gttmhrtnri.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiumeldog.html

[T45] Perl：数组遍历
来源：http://dali.chenzaomai.com/Article/details/gtesjtstks.html

for my $x (@arr) { print $x; }
来源：http://dali.dianchejie.cn/Article/details/gttqabmlpm.html

[T46] Perl：哈希操作
来源：http://dali.jiagoushi.top/Article/details/gtzlupjvik.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yuanzhike.top/Article/details/gtosswvtqn.html

[T47] Perl：正则捕获
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjkzjrsk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yvedp.cn/Article/details/gtuxzwjayi.html

[T48] Perl：正则替换
来源：http://dali.shzxlz.cn/Article/details/gtqnwrfnpd.html

$s =~ s/old/new/g;
来源：http://dali.jlsjyb.cn/Article/details/gtcgerkucl.html

[T49] Perl：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtnrerdzvu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gtmarkgfwa.html

[T50] Perl：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtpuutfhvx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cheryme.top/Article/details/gtwhwvqggj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj202588.top/Article/details/gtshjoxtvl.html

[T51] Scala：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtupyzfkfg.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gtdrqkmoia.html

[T52] Scala：变量
来源：http://dali.316326.xyz/Article/details/gtjirqgwcl.html

val a = 1;  var b = 2
来源：http://dali.jqgufenzy.top/Article/details/gtiaguepjt.html

[T53] Scala：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtgsrqoajy.html

s"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gtraaeoevz.html

[T54] Scala：集合映射
来源：http://dali.zycfv.cn/Article/details/gtnfavrnpc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhengqikj.top/Article/details/gtlwqgxqcx.html

[T55] Scala：集合过滤
来源：http://dali.gzhubu.top/Article/details/gtzfiekrwf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aizwys.cn/Article/details/gtcpgmgwew.html

[T56] Scala：样例类
来源：http://dali.nanxinkj.top/Article/details/gtdzhitsdd.html

case class User(name: String, age: Int)
来源：http://dali.jiagoushi.top/Article/details/gtaewgovrg.html

[T57] Scala：模式匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzevfpssz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.andypj.xyz/Article/details/gtjjesjblg.html

[T58] Scala：函数定义
来源：http://dali.wangshuangyany.cn/Article/details/gtmzqrmmgi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.316326.xyz/Article/details/gtokognosd.html

[T59] Scala：循环
来源：http://dali.hysaishi.cn/Article/details/gtwxvpszpk.html

for (i <- 1 to 10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtjtmgozce.html

[T60] Scala：折叠
来源：http://dali.hongshengwenyu.top/Article/details/gtkkfrhprj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xylfe.cn/Article/details/gtnjxiaght.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtpaxyojpy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cqqwz.cn/Article/details/gtddooxniz.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtgvfkmhag.html

[U01] Py：创建虚拟环境
来源：http://dali.jqgufenzy.top/Article/details/gtodgglxvl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkqjphlcj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj20258.top/Article/details/gtesdzmudf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinqigfzy.top/Article/details/gtjafxomyr.html

[U03] Py：加载 .env 配置
来源：http://dali.ehwqpu.com/Article/details/gtpzxvnmgd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ivvv.top/Article/details/gtruornxks.html

[U04] Py：变量调试打印
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzajwafv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hysaishi.cn/Article/details/gtdjmgsohc.html

[U05] Py：列表去重且保序
来源：http://dali.sysykeji.top/Article/details/gthljulykt.html

list(dict.fromkeys(arr))
来源：http://dali.chenlongwang.top/Article/details/gttrvdzyqn.html

[U06] Py：合并两个字典
来源：http://dali.aizwys.cn/Article/details/gtvksonerp.html

{**a, **b}
来源：http://dali.vqdsnc.cn/Article/details/gtxajlggbu.html

[U07] Py：反转字典键值
来源：http://dali.mhx1999.top/Article/details/gtdvggmbxw.html

{v: k for k, v in d.items()}
来源：http://dali.havefunace.top/Article/details/gtuxkukinx.html

[U08] Py：展平二维列表
来源：http://dali.yj20258.top/Article/details/gtytcvsbqg.html

[y for x in nested for y in x]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpukryqro.html

[U09] Py：字典取最大值的键
来源：http://dali.yueranfly.top/Article/details/gtutdxyoxy.html

max(d, key=d.get)
来源：http://dali.jinqigufen.top/Article/details/gtdfqggrzr.html

[U10] Py：按值排序字典
来源：http://dali.vqdsnc.cn/Article/details/gtadpmfvdl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hnxiangtu.top/Article/details/gtyxiotaze.html

[U11] Py：生成器表达式
来源：http://dali.hammf.cn/Article/details/gtajqheang.html

(x * 2 for x in arr)
来源：http://dali.jlsjyb.cn/Article/details/gtynvoffzr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cqqwz.cn/Article/details/gtkpeonjex.html

Counter(arr).most_common(3)
来源：http://dali.sysykeji.top/Article/details/gtlorehpbh.html

[U13] Py：固定长度队列
来源：http://dali.feifeiyinyue.top/Article/details/gtdfslrvxg.html

deque(maxlen=10)
来源：http://dali.feifeiyinyue.top/Article/details/gtwihlqnnd.html

[U14] Py：分组收集到列表
来源：http://dali.hnxiangtu.top/Article/details/gtxwaetgsh.html

defaultdict(list)
来源：http://dali.shzxlz.cn/Article/details/gtpopqcpce.html

[U15] Py：高精度计时
来源：http://dali.hnxiangtu.top/Article/details/gtobnsobce.html

t = time.perf_counter()
来源：http://dali.shangyingyoupin.top/Article/details/gtudyxqjvk.html

[U16] Py：命令行参数解析
来源：http://dali.ivvv.top/Article/details/gtmotibtyf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.havefunace.top/Article/details/gtigjmzeki.html

[U17] Py：初始化日志
来源：http://dali.sxryk.cn/Article/details/gtqgydihss.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.wangdashe.top/Article/details/gtexsifpdv.html

[U18] Py：预编译正则
来源：http://dali.chenlongwang.top/Article/details/gtqtrxbqbz.html

pat = re.compile(r"\d+")
来源：http://dali.cucudq.cn/Article/details/gtxnaswbft.html

[U19] Py：正则替换带回调
来源：http://dali.birdmap.top/Article/details/gtcnmdhhbu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxtlkhcn.html

[U20] Py：缓存函数结果
来源：http://dali.0kj1m.cn/Article/details/gttcemqwlr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hywenlv.cn/Article/details/gtxrjuuaym.html

[U21] Py：自定义上下文管理器
来源：http://dali.haohaochexian.top/Article/details/gtorwamenx.html

@contextlib.contextmanager
来源：http://dali.jqgufenzy.top/Article/details/gtzpdqzigd.html

[U22] Py：矩阵转置
来源：http://dali.9152youxi.cn/Article/details/gtcgpcysul.html

list(zip(*m))
来源：http://dali.gaohongyu789.top/Article/details/gtdjpgbpef.html

[U23] Py：分块读取大文件
来源：http://dali.jyoumei.cn/Article/details/gtlmcanyis.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhixingplan.top/Article/details/gtqtpuiwsz.html

[U24] Py：路径操作
来源：http://dali.snrcjt.cn/Article/details/gtnnjburtr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gttlfzodsx.html

[U25] Py：CSV 按字典读
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxhysnwg.html

csv.DictReader(f)
来源：http://dali.jianghu66.top/Article/details/gtcwtjgmns.html

[U26] Py：并发下载
来源：http://dali.nanxinkj.top/Article/details/gtdtunnscm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.aizwys.cn/Article/details/gtnqsbdecf.html

[U27] Py：异步 HTTP
来源：http://dali.chenjidiqi.icu/Article/details/gttzjzeirk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xuanzx.com/Article/details/gtofiawrrw.html

[U28] Py：类型别名
来源：http://dali.yj20258.top/Article/details/gtjzkoygjp.html

UserId = int
来源：http://dali.shzxlz.cn/Article/details/gtrjzoktrz.html

[U29] Py：属性校验
来源：http://dali.hnqzz.top/Article/details/gtudwborxh.html

@property 与 @x.setter 配合
来源：http://dali.yueranfly.top/Article/details/gtkzcznnug.html

[U30] Py：数据类
来源：http://dali.dashuyun.cn/Article/details/gtrgtxhxon.html

@dataclass(slots=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxziokckc.html

[U31] Py：单测
来源：http://dali.chenjidiqi.icu/Article/details/gtqscymgkk.html

python -m pytest -q
来源：http://dali.pycfn.com/Article/details/gtcakrwavz.html

[U32] Py：代码格式化
来源：http://dali.c1oappe.top/Article/details/gtiphlmgld.html

ruff format . && ruff check --fix .
来源：http://dali.yuxming.cn/Article/details/gteztncysi.html

[U33] Py：打包发布
来源：http://dali.birdmap.top/Article/details/gtdtprwibt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hfpthk.cn/Article/details/gtzcnlpscl.html

[U34] Py：判断编码
来源：http://dali.snrcjt.cn/Article/details/gtebskomli.html

chardet.detect(raw)
来源：http://dali.jianghu66.top/Article/details/gtqpczxpau.html

[U35] Py：发送邮件
来源：http://dali.havefunace.top/Article/details/gtqhqpzoiq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yuanzhike.top/Article/details/gtojksuany.html

[U36] Py：定时任务
来源：http://dali.jqgufenzy.top/Article/details/gtmzmjdevw.html

schedule.every(10).minutes.do(job)
来源：http://dali.shzxlz.cn/Article/details/gtjnjrptvj.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gtovtcyakz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.aizwys.cn/Article/details/gtdpcbgvas.html

[U38] Py：获取脚本所在目录
来源：http://dali.havefunace.top/Article/details/gtcnytnxrr.html

Path(__file__).resolve().parent
来源：http://dali.cashguo.top/Article/details/gtuuigpxjr.html

[U39] Py：判断是否在交互环境
来源：http://dali.gogol.net.cn/Article/details/gtbnbkmxng.html

sys.stdout.isatty()
来源：http://dali.vqdsnc.cn/Article/details/gtudogcvfv.html

[U40] Py：打印到标准错误
来源：http://dali.cashguo.top/Article/details/gtwxaoledk.html

print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gtttargqiv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shuidangran.top/Article/details/gtchpkeywv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yj20258.top/Article/details/gtnhpmygiq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gotoacloud.top/Article/details/gtipaorwvz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jqgfzy.top/Article/details/gtfmouxnzc.html


<!-- 参考信息 -->