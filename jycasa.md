代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gtjtftselc.html

[S21] C：字符类别判断
来源：http://dali.nanxuanxn.top/Article/details/gtiklvdzvf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gtzkuogmut.html

[S22] C：字符串转数字
来源：http://dali.yvedp.cn/Article/details/gtqvwnxbse.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cheryme.top/Article/details/gtcefmsiyl.html

[S23] C：随机数
来源：http://dali.yvedp.cn/Article/details/gtgmhwehri.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sweek.top/Article/details/gtkersspmm.html

[S24] C：获取本地时间
来源：http://dali.sufxvd.cn/Article/details/gtgemdnuqh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guowangkeji.top/Article/details/gtebgkvhqg.html

[S25] C：内存拷贝
来源：http://dali.cqqwz.cn/Article/details/gtznjizivz.html

memcpy(dst, src, n);
来源：http://dali.guowangkeji.top/Article/details/gtuhbuinza.html

[S26] C：内存清零
来源：http://dali.hongshengwenyu.top/Article/details/gtbqwjubqi.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258.top/Article/details/gtefykkosb.html

[S27] C：定义常量
来源：http://dali.jqgufenzy.top/Article/details/gtupykawbb.html

const double PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtvumsztfu.html

[S28] C：静态变量
来源：http://dali.feifeiyinyue.top/Article/details/gtoopdbnqo.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gtysfhzhdm.html

[S29] C：变参函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtolxuvhbh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sxryk.cn/Article/details/gtwxqvhwku.html

[S30] C：头文件保护
来源：http://dali.xylfe.cn/Article/details/gtwljafyeb.html

#ifndef X_H
来源：http://dali.chenzaomai.com/Article/details/gtavlifhcp.html

#define X_H
来源：http://dali.pengpengdd.cyou/Article/details/gtkefqkgtt.html

#endif
来源：http://dali.quarkkingdee.top/Article/details/gtvkqmnssx.html

[S31] C++：Hello World
来源：http://dali.sysykeji.top/Article/details/gtpamozvzy.html

#include <iostream>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjtnbhwc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hywenlv.cn/Article/details/gtltdccetm.html

[S32] C++：字符串
来源：http://dali.pycfn.com/Article/details/gtybathrlh.html

std::string s = "hi";  s += "!";
来源：http://dali.vqdsnc.cn/Article/details/gtgcynpvuq.html

[S33] C++：vector 增删
来源：http://dali.nanxinkj.top/Article/details/gtfrlcphha.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jiagoushi.top/Article/details/gtrguszrcf.html

[S34] C++：遍历 vector
来源：http://dali.pengpengdd.cyou/Article/details/gtijpewnzq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sufxvd.cn/Article/details/gtscpndabz.html

[S35] C++：map
来源：http://dali.jinghuilouyu.cn/Article/details/gtsytcggxm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gttxaaaibn.html

[S36] C++：unordered_map
来源：http://dali.guowangkeji.top/Article/details/gtdbkebtbo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gttegmtgnj.html

[S37] C++：set
来源：http://dali.jqgufenzy.top/Article/details/gtoptvwxhw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guannengcc.top/Article/details/gtilryuacv.html

[S38] C++：排序
来源：http://dali.nanxinkj.top/Article/details/gtnvqlvnat.html

std::sort(v.begin(), v.end());
来源：http://dali.hysaishi.cn/Article/details/gtmyfflpdy.html

[S39] C++：自定义比较器排序
来源：http://dali.daria6918.cn/Article/details/gtrgunzhpg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gtszdceuvm.html

[S40] C++：查找元素
来源：http://dali.snrcjt.cn/Article/details/gtfxwtpomg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ydzc1.top/Article/details/gtodybkysr.html

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gtauovelrj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.kuanghao11.cn/Article/details/gtzeoexmgp.html

[S42] C++：继承与虚函数
来源：http://dali.yangfankeji.com/Article/details/gtybmwqxlh.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258.top/Article/details/gtsrtqdptz.html

[S43] C++：智能指针
来源：http://dali.zhengqikj.top/Article/details/gtzjgludbp.html

auto p = std::make_unique<int>(5);
来源：http://dali.cashguo.top/Article/details/gtzhebvzuu.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangkeji.top/Article/details/gthyzgikmn.html

void inc(int &x) { ++x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwdirpkkq.html

[S45] C++：lambda
来源：http://dali.quarkkingdee.top/Article/details/gtugehwjon.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgfzy.top/Article/details/gtufxqcjis.html

[S46] C++：函数模板
来源：http://dali.chenlongwang.top/Article/details/gtufauwywb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhoulong.xyz/Article/details/gtyfpqnzkz.html

[S47] C++：结构化绑定遍历
来源：http://dali.vqdsnc.cn/Article/details/gtdcqcaris.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gogol.net.cn/Article/details/gtnvdhvgbz.html

[S48] C++：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtmoijutfi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigufen.top/Article/details/gtznguggxv.html

while (std::getline(in, line)) { }
来源：http://dali.havefunace.top/Article/details/gtumsprzul.html

[S49] C++：写文件
来源：http://dali.fzhhl.top/Article/details/gtyyufpitx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sufxvd.cn/Article/details/gtmmtafkkz.html

[S50] C++：格式化数字
来源：http://dali.gaohongyu789.top/Article/details/gtzczqsmvb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtjomkfkkx.html

[S51] C++：显式类型转换
来源：http://dali.snrcjt.cn/Article/details/gtsmfndhxp.html

static_cast<double>(a) / b
来源：http://dali.yonumen.top/Article/details/gtgtubbgil.html

[S52] C++：const 与 noexcept
来源：http://dali.yueranfly.top/Article/details/gtcateblsn.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258888.top/Article/details/gtfycfbtwu.html

[S53] C++：移动语义
来源：http://dali.ydzc1.top/Article/details/gthgegbglp.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigufen.top/Article/details/gtvgrkyway.html

[S54] C++：异常处理
来源：http://dali.cdnleiting.top/Article/details/gtefwqflng.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.quarkkingdee.top/Article/details/gtgjaaygej.html

[S55] C++：结构化绑定
来源：http://dali.tian-w.cn/Article/details/gtcgxolsoe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xylfe.cn/Article/details/gtrcomokql.html

[S56] C++：optional
来源：http://dali.shuidangran.top/Article/details/gtwqnqmfnj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.9152youxi.cn/Article/details/gtzhysilki.html

[S57] C++：编译期常量
来源：http://dali.fengsongda.top/Article/details/gtcwokqchf.html

constexpr int N = 10;
来源：http://dali.birdmap.top/Article/details/gtobnievhk.html

[S58] C++：命名空间
来源：http://dali.zhixingplan.top/Article/details/gtozcdkzqx.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258888.top/Article/details/gttcicddmi.html

[S59] C++：静态断言
来源：http://dali.nwbrower.top/Article/details/gtsfocwilx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xinyue.icu/Article/details/gtwsdxahok.html

[S60] C++：遍历并删除元素
来源：http://dali.yvedp.cn/Article/details/gteuiysrah.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtivdgtfvh.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtkwbjkdkc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yangfankeji.com/Article/details/gtmsyxkvpz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtujrdjnmj.html

[T01] Kotlin：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtmwjopzgp.html

println("Hello")
来源：http://dali.smart0.xyz/Article/details/gtcussopmw.html

[T02] Kotlin：变量
来源：http://dali.sysykeji.top/Article/details/gtxfneemdj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yonumen.top/Article/details/gtrcobswby.html

[T03] Kotlin：字符串模板
来源：http://dali.nwbrower.top/Article/details/gtttmdzeci.html

"值: $b"
来源：http://dali.jianghu66.top/Article/details/gteafeoehs.html

[T04] Kotlin：空安全
来源：http://dali.mhx1999.top/Article/details/gtfolvtatb.html

val n: String? = null;  n?.length
来源：http://dali.ivvv.top/Article/details/gtygrzoygb.html

[T05] Kotlin：when 表达式
来源：http://dali.pycfn.com/Article/details/gtjhlfiybx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.kuanghao11.cn/Article/details/gtlyvjccdw.html

[T06] Kotlin：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gtchfiglvf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cucudq.cn/Article/details/gtovirxyzz.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258888.top/Article/details/gtzzgbishv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guowangkeji.top/Article/details/gtholhrfji.html

[T08] Kotlin：数据类
来源：http://dali.svipenyu.cn/Article/details/gtqmlwjxrh.html

data class User(val name: String, val age: Int)
来源：http://dali.wangdashe.top/Article/details/gtydmgbovt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gtctkzatdp.html

fun String.exclaim() = this + "!"
来源：http://dali.haohaochexian.top/Article/details/gtyvtvbctq.html

[T10] Kotlin：默认参数
来源：http://dali.iojbl.cn/Article/details/gtiydibkrr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jlsjyb.cn/Article/details/gtuajbhvzh.html

[T11] Kotlin：协程
来源：http://dali.guannengcc.top/Article/details/gthrwymppf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzaxvyfbs.html

[T12] Kotlin：解构声明
来源：http://dali.cdnleiting.top/Article/details/gtcbiqnekf.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtbvygrcah.html

[T13] Kotlin：只读 Map
来源：http://dali.cheryme.top/Article/details/gtngfdmhlr.html

val m = mapOf("a" to 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtoxqervae.html

[T14] Kotlin：循环
来源：http://dali.jinqigfzy.top/Article/details/gtdeikdncm.html

for (i in 1..10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gtdsgxqnbv.html

[T15] Kotlin：接口
来源：http://dali.nwbrower.top/Article/details/gtljrasbnn.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gtefistwew.html

[T16] Swift：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtuisvysia.html

print("Hello")
来源：http://dali.shuidangran.top/Article/details/gtigkosoug.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtsirynjbx.html

var a = 1;  let b = 2
来源：http://dali.sweek.top/Article/details/gtusnpposw.html

[T18] Swift：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtiumvthbz.html

"值: \(b)"
来源：http://dali.jinqigufen.top/Article/details/gtdcbuobzb.html

[T19] Swift：可选绑定
来源：http://dali.hnxiangtu.top/Article/details/gtgfvsbzkm.html

if let n = opt { print(n) }
来源：http://dali.tianlin.xyz/Article/details/gtkgdzdwuk.html

[T20] Swift：数组操作
来源：http://dali.gzhubu.top/Article/details/gttkllclmx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yvedp.cn/Article/details/gtvcmdqpuz.html

[T21] Swift：遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbygtdqob.html

for x in a { print(x) }
来源：http://dali.nanxinkj.top/Article/details/gtfchmqqwu.html

[T22] Swift：字典
来源：http://dali.aizwys.cn/Article/details/gtikptdbrh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shuidangran.top/Article/details/gtugtikixd.html

[T23] Swift：函数
来源：http://dali.yj202588.top/Article/details/gtlgwrtuhs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangdashe.top/Article/details/gthplbgeuw.html

[T24] Swift：闭包
来源：http://dali.pengpengdd.cyou/Article/details/gttgbfgtmc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gtwphwotwx.html

[T25] Swift：结构体
来源：http://dali.nwbrower.top/Article/details/gtzzkomgfk.html

struct P { var x: Int }
来源：http://dali.zycfv.cn/Article/details/gtcspxqmjo.html

[T26] Swift：类与重写
来源：http://dali.hfpthk.cn/Article/details/gtqkdcjvcd.html

class A: Base { override func f() {} }
来源：http://dali.yj202588.top/Article/details/gtadbxntlx.html

[T27] Swift：错误处理
来源：http://dali.chenzaomai.com/Article/details/gtydysfhay.html

do { try f() } catch { print(error) }
来源：http://dali.yj202588.top/Article/details/gtctbaovtt.html

[T28] Swift：枚举
来源：http://dali.meibo888.top/Article/details/gtwubxwbje.html

enum Color { case red, green }
来源：http://dali.cqqwz.cn/Article/details/gtfrnurxtj.html

[T29] Swift：guard 提前返回
来源：http://dali.kuanghao11.cn/Article/details/gtjhtlapze.html

guard let x = opt else { return }
来源：http://dali.hysaishi.cn/Article/details/gttntkztvf.html

[T30] Swift：协议
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxxzpcrf.html

protocol Shape { func area() -> Double }
来源：http://dali.ivvv.top/Article/details/gtgfyuabdy.html

[T31] Lua：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtlfhecure.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gtblrmvwqx.html

[T32] Lua：局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gtnjzzqnbx.html

local a = 1
来源：http://dali.0kj1m.cn/Article/details/gtjdrbjrgb.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcowmmza.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gotoacloud.top/Article/details/gtaqlqtrxl.html

[T34] Lua：遍历表
来源：http://dali.zhengqikj.top/Article/details/gtxrrkydvr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnxiangtu.top/Article/details/gtfcfaoszj.html

[T35] Lua：字典表
来源：http://dali.dashuyun.cn/Article/details/gtgfgtsmeh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchwsjwkz.html

[T36] Lua：函数
来源：http://dali.zycfv.cn/Article/details/gtnoazcqwc.html

function add(a, b) return a + b end
来源：http://dali.jqgufenzy.top/Article/details/gtlosqytyh.html

[T37] Lua：字符串拼接
来源：http://dali.mhx1999.top/Article/details/gtkmmcylce.html

"a" .. "b"
来源：http://dali.havefunace.top/Article/details/gtzkmjuzfs.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gtjgsuojpj.html

if x > 0 then print("正") end
来源：http://dali.fengsongda.top/Article/details/gtmyynlmlq.html

[T39] Lua：模式匹配
来源：http://dali.jianghu66.top/Article/details/gtecfnpneo.html

string.find(s, "%d+")
来源：http://dali.andypj.xyz/Article/details/gttyhqnqym.html

[T40] Lua：元表
来源：http://dali.dashuyun.cn/Article/details/gtgukbrnsd.html

setmetatable({}, { __index = base })
来源：http://dali.yuxming.cn/Article/details/gtyvngtmsu.html

[T41] Perl：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfyfefyb.html

print "Hello\n";
来源：http://dali.zycfv.cn/Article/details/gthibdomxg.html

[T42] Perl：变量类型
来源：http://dali.mhx1999.top/Article/details/gtnemhapsq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhoulong.xyz/Article/details/gtyyixpblc.html

[T43] Perl：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtspcfmiok.html

"值: $a"
来源：http://dali.guowangkeji.top/Article/details/gtrjqzgruv.html

[T44] Perl：条件
来源：http://dali.birdmap.top/Article/details/gtnrsqvioi.html

if ($a > 0) { print "正"; }
来源：http://dali.sysykeji.top/Article/details/gtgtorhkgn.html

[T45] Perl：数组遍历
来源：http://dali.xuanzx.com/Article/details/gtinepjqii.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgfzy.top/Article/details/gtfpchxblz.html

[T46] Perl：哈希操作
来源：http://dali.gogol.net.cn/Article/details/gtsizmcvap.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ppjwa.cn/Article/details/gtixtqstcb.html

[T47] Perl：正则捕获
来源：http://dali.bjfxy.top/Article/details/gtibgxqvea.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tianlin.xyz/Article/details/gtdzhmxhtg.html

[T48] Perl：正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjjruuqx.html

$s =~ s/old/new/g;
来源：http://dali.gotoacloud.top/Article/details/gtyftvefwa.html

[T49] Perl：函数
来源：http://dali.cashguo.top/Article/details/gtmysybevf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gtvrhvmuie.html

[T50] Perl：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtfpqmhixr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gaohongyu789.top/Article/details/gtsopoiwpm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ybcxt.top/Article/details/gtsxcmrctc.html

[T51] Scala：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtciycwkjo.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtaqlbljvr.html

[T52] Scala：变量
来源：http://dali.chenlongwang.top/Article/details/gtgzwcueyi.html

val a = 1;  var b = 2
来源：http://dali.zycfv.cn/Article/details/gtvpfvzclo.html

[T53] Scala：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtrhqiqbxn.html

s"值: $b"
来源：http://dali.vqdsnc.cn/Article/details/gtroppiyrt.html

[T54] Scala：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gtnettzmbc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrozgnry.html

[T55] Scala：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnevpdkt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guannengcc.top/Article/details/gtkrurvftz.html

[T56] Scala：样例类
来源：http://dali.tian-w.cn/Article/details/gtkmysfqzz.html

case class User(name: String, age: Int)
来源：http://dali.zhixingplan.top/Article/details/gtfotwrcfx.html

[T57] Scala：模式匹配
来源：http://dali.smart0.xyz/Article/details/gtlrgozxcf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzghsasw.html

[T58] Scala：函数定义
来源：http://dali.sufxvd.cn/Article/details/gturuwkitd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xylfe.cn/Article/details/gtrhfpkmma.html

[T59] Scala：循环
来源：http://dali.sweek.top/Article/details/gtpatxgogt.html

for (i <- 1 to 10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gtywpikyuo.html

[T60] Scala：折叠
来源：http://dali.ydzc1.top/Article/details/gtdzvlvssk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuanzx.com/Article/details/gtlxwnitpm.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtrqsyudoa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhksxdls.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtmyaopsxf.html

[U01] Py：创建虚拟环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmcgmnkt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.snrcjt.cn/Article/details/gtmlmlupiv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.daria6918.cn/Article/details/gtqbheoaox.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrajogds.html

[U03] Py：加载 .env 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmwnbamy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sysykeji.top/Article/details/gtvspohfjw.html

[U04] Py：变量调试打印
来源：http://dali.ehwqpu.com/Article/details/gtlhwlvnxf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj202588.top/Article/details/gtpptiordq.html

[U05] Py：列表去重且保序
来源：http://dali.svipenyu.cn/Article/details/gthubdiwtl.html

list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtxvqposea.html

[U06] Py：合并两个字典
来源：http://dali.gzhubu.top/Article/details/gtsovgjkrp.html

{**a, **b}
来源：http://dali.jianghu66.top/Article/details/gtatxbysfh.html

[U07] Py：反转字典键值
来源：http://dali.zhongyouzk.top/Article/details/gtsvqaxwtt.html

{v: k for k, v in d.items()}
来源：http://dali.ivvv.top/Article/details/gtnbvrmivb.html

[U08] Py：展平二维列表
来源：http://dali.chenjidiqi.icu/Article/details/gtsgtwhvoh.html

[y for x in nested for y in x]
来源：http://dali.daxiang520.top/Article/details/gthlypvyea.html

[U09] Py：字典取最大值的键
来源：http://dali.xuetiantiany.cn/Article/details/gtbuqoezya.html

max(d, key=d.get)
来源：http://dali.hongshengwenyu.top/Article/details/gtbsghbxam.html

[U10] Py：按值排序字典
来源：http://dali.vqdsnc.cn/Article/details/gtcgzjsuga.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hongshengwenyu.top/Article/details/gtlfkhgyit.html

[U11] Py：生成器表达式
来源：http://dali.kuanghao11.cn/Article/details/gtfvineiat.html

(x * 2 for x in arr)
来源：http://dali.zhoulong.xyz/Article/details/gtimdlkjmq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cashguo.top/Article/details/gtbawnyuck.html

Counter(arr).most_common(3)
来源：http://dali.yuxming.cn/Article/details/gtxxyaiige.html

[U13] Py：固定长度队列
来源：http://dali.andypj.xyz/Article/details/gthfjsioqy.html

deque(maxlen=10)
来源：http://dali.hongshengwenyu.top/Article/details/gtyqccgmyn.html

[U14] Py：分组收集到列表
来源：http://dali.andypj.xyz/Article/details/gtwpltshzu.html

defaultdict(list)
来源：http://dali.redwolf501.top/Article/details/gtklyqrtad.html

[U15] Py：高精度计时
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgaytohfy.html

t = time.perf_counter()
来源：http://dali.dashuyun.cn/Article/details/gtilwztcia.html

[U16] Py：命令行参数解析
来源：http://dali.kuanghao11.cn/Article/details/gtcigdcdio.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.tianlin.xyz/Article/details/gtsxqpeenh.html

[U17] Py：初始化日志
来源：http://dali.hammf.cn/Article/details/gturkjttwj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cdnleiting.top/Article/details/gttiaduqzh.html

[U18] Py：预编译正则
来源：http://dali.gzhubu.top/Article/details/gtvkpvxmsl.html

pat = re.compile(r"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gtjwixjcpm.html

[U19] Py：正则替换带回调
来源：http://dali.zhixingplan.top/Article/details/gtdyucqobs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nanxinkj.top/Article/details/gthysigepy.html

[U20] Py：缓存函数结果
来源：http://dali.xuetiantiany.cn/Article/details/gtrwvxwwjw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hysaishi.cn/Article/details/gtiuevhdyq.html

[U21] Py：自定义上下文管理器
来源：http://dali.gotoacloud.top/Article/details/gttrtzualu.html

@contextlib.contextmanager
来源：http://dali.gaohongyu789.top/Article/details/gtikgzikki.html

[U22] Py：矩阵转置
来源：http://dali.yuanzhike.top/Article/details/gtmozdrsiv.html

list(zip(*m))
来源：http://dali.chenlongwang.top/Article/details/gtqkayrbsz.html

[U23] Py：分块读取大文件
来源：http://dali.iojbl.cn/Article/details/gtifyspwon.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yuxming.cn/Article/details/gtmuyqgqjp.html

[U24] Py：路径操作
来源：http://dali.zdqjudy.top/Article/details/gtkkzmhvqn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gtdlghzfcl.html

[U25] Py：CSV 按字典读
来源：http://dali.jianghu66.top/Article/details/gtuaddbnaz.html

csv.DictReader(f)
来源：http://dali.gogol.net.cn/Article/details/gtsasiwvmr.html

[U26] Py：并发下载
来源：http://dali.0kj1m.cn/Article/details/gtrcrodvgz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.mhx1999.top/Article/details/gtflqpbuka.html

[U27] Py：异步 HTTP
来源：http://dali.zhoulong.xyz/Article/details/gtocdkpymo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gogol.net.cn/Article/details/gtqgkdnyfz.html

[U28] Py：类型别名
来源：http://dali.yj202588.top/Article/details/gtavdxclbh.html

UserId = int
来源：http://dali.cdnleiting.top/Article/details/gtaezeyghn.html

[U29] Py：属性校验
来源：http://dali.shanyushiyangtech.top/Article/details/gtiatxeede.html

@property 与 @x.setter 配合
来源：http://dali.cqqwz.cn/Article/details/gtmdegotlp.html

[U30] Py：数据类
来源：http://dali.dianchejie.cn/Article/details/gtxlndozad.html

@dataclass(slots=True)
来源：http://dali.vqdsnc.cn/Article/details/gtxgpufndn.html

[U31] Py：单测
来源：http://dali.daria6918.cn/Article/details/gtmbgnwnaa.html

python -m pytest -q
来源：http://dali.meibo888.top/Article/details/gtquwkhpuo.html

[U32] Py：代码格式化
来源：http://dali.gzhubu.top/Article/details/gtwjnebwdb.html

ruff format . && ruff check --fix .
来源：http://dali.9152youxi.cn/Article/details/gtjefkcgex.html

[U33] Py：打包发布
来源：http://dali.cashguo.top/Article/details/gtzciobhgt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yongpay.top/Article/details/gtvmapvoms.html

[U34] Py：判断编码
来源：http://dali.aizwys.cn/Article/details/gtbzokntcq.html

chardet.detect(raw)
来源：http://dali.kuanghao11.cn/Article/details/gtvqbetzzk.html

[U35] Py：发送邮件
来源：http://dali.sxryk.cn/Article/details/gtptszlbeq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.snrcjt.cn/Article/details/gtzkwqectz.html

[U36] Py：定时任务
来源：http://dali.zdqjudy.top/Article/details/gtlthqjfkc.html

schedule.every(10).minutes.do(job)
来源：http://dali.0kj1m.cn/Article/details/gtqksrafbr.html

[U37] Py：读写 Excel
来源：http://dali.sufxvd.cn/Article/details/gtnvtebqna.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.wangshuangyany.cn/Article/details/gtvoupvips.html

[U38] Py：获取脚本所在目录
来源：http://dali.sxryk.cn/Article/details/gthhkdrziq.html

Path(__file__).resolve().parent
来源：http://dali.xziqi.cn/Article/details/gthujirtbl.html

[U39] Py：判断是否在交互环境
来源：http://dali.birdmap.top/Article/details/gtcqagjqia.html

sys.stdout.isatty()
来源：http://dali.zdqjudy.top/Article/details/gtmzotqsmc.html

[U40] Py：打印到标准错误
来源：http://dali.snrcjt.cn/Article/details/gtobderbzi.html

print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gtmydbdpih.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.andypj.xyz/Article/details/gtfqtrcvmg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jianghu66.top/Article/details/gtlutckytu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hongshengwenyu.top/Article/details/gtdvchmmnp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hysaishi.cn/Article/details/gtnufgbgqh.html

[U43] PHP：声明命名空间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwberrxbv.html

namespace App\Http;
来源：http://dali.hammf.cn/Article/details/gttfixmxmf.html

[U44] PHP：开启严格类型
来源：http://dali.zhongyouzk.top/Article/details/gthhrzzduv.html

declare(strict_types=1);
来源：http://dali.redwolf501.top/Article/details/gtvjznmxgl.html


<!-- 参考信息 -->