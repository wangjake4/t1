代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.ivvv.top/Article/details/gtaqgiuqza.html

[S15] C：类型转换
来源：http://dali.jyoumei.cn/Article/details/gtbfqoityg.html

(double) a / b
来源：http://dali.redwolf501.top/Article/details/gtamqrzrix.html

[S16] C：位操作置位
来源：http://dali.yvedp.cn/Article/details/gthxeiibyq.html

x |= (1 << 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzgyqzzo.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarsizmvl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sysykeji.top/Article/details/gthhbzxgcx.html

[S18] C：命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gtthizccxw.html

int main(int argc, char **argv)
来源：http://dali.yj20258888.top/Article/details/gtoizrgajp.html

[S19] C：快速排序
来源：http://dali.bjfxy.top/Article/details/gtxuzngrep.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gtfbjivrjn.html

[S20] C：二分查找
来源：http://dali.meibo888.top/Article/details/gtxhqskkce.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gtjunzikxp.html

[S21] C：字符类别判断
来源：http://dali.gogol.net.cn/Article/details/gtrluwldav.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gtgjfomhef.html

[S22] C：字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gtoipawqeo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuanzx.com/Article/details/gtapzzxfsv.html

[S23] C：随机数
来源：http://dali.jyoumei.cn/Article/details/gticioesit.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aibaodan.cn/Article/details/gtrzqjtryc.html

[S24] C：获取本地时间
来源：http://dali.yuanzhike.top/Article/details/gtqycmpkhw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.0kj1m.cn/Article/details/gtvtmmdyfk.html

[S25] C：内存拷贝
来源：http://dali.mhx1999.top/Article/details/gtlpvexuaw.html

memcpy(dst, src, n);
来源：http://dali.guowangkeji.top/Article/details/gtmpfzblrn.html

[S26] C：内存清零
来源：http://dali.meibo888.top/Article/details/gtylhzgduj.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigfzy.top/Article/details/gtbqsitxnx.html

[S27] C：定义常量
来源：http://dali.gzhubu.top/Article/details/gthkwzyrvx.html

const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gttavlgxin.html

[S28] C：静态变量
来源：http://dali.cheryme.top/Article/details/gtbiemrnth.html

static int counter = 0;
来源：http://dali.jyoumei.cn/Article/details/gtgrgepqgu.html

[S29] C：变参函数
来源：http://dali.wangdashe.top/Article/details/gtrmbijriv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gtequcovcz.html

[S30] C：头文件保护
来源：http://dali.0kj1m.cn/Article/details/gtfsqixlai.html

#ifndef X_H
来源：http://dali.gaohongyu789.top/Article/details/gtptnvbale.html

#define X_H
来源：http://dali.0kj1m.cn/Article/details/gtlyiyzbhu.html

#endif
来源：http://dali.shuidangran.top/Article/details/gteuokzdvu.html

[S31] C++：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtukkoupmm.html

#include <iostream>
来源：http://dali.chenlongwang.top/Article/details/gtojwoskrd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgbrvqpaq.html

[S32] C++：字符串
来源：http://dali.fengsongda.top/Article/details/gtyfgvmzxg.html

std::string s = "hi";  s += "!";
来源：http://dali.birdmap.top/Article/details/gtaqfvkeab.html

[S33] C++：vector 增删
来源：http://dali.gogol.net.cn/Article/details/gtlduibstd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xinyue.icu/Article/details/gtgpquhegz.html

[S34] C++：遍历 vector
来源：http://dali.ydzc1.top/Article/details/gtqyjeehgi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenjidiqi.icu/Article/details/gturcldmgd.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gtuthnhwjp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtgmwefqxr.html

[S36] C++：unordered_map
来源：http://dali.gotoacloud.top/Article/details/gtzhtxclay.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtfaevkeki.html

[S37] C++：set
来源：http://dali.havefunace.top/Article/details/gtiiklgyat.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gotoacloud.top/Article/details/gtpckatekf.html

[S38] C++：排序
来源：http://dali.zhiwuduotai.top/Article/details/gticvkphdx.html

std::sort(v.begin(), v.end());
来源：http://dali.cdnleiting.top/Article/details/gttuiczgyl.html

[S39] C++：自定义比较器排序
来源：http://dali.gotoacloud.top/Article/details/gtjnpnibpr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cqqwz.cn/Article/details/gtlmwkgigg.html

[S40] C++：查找元素
来源：http://dali.zhixingplan.top/Article/details/gtmzyerjjp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daria6918.cn/Article/details/gtwbhzdsag.html

[S41] C++：类与构造函数
来源：http://dali.ybcxt.top/Article/details/gtrxwxhtzp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.redwolf501.top/Article/details/gtdwyjonzv.html

[S42] C++：继承与虚函数
来源：http://dali.dianchejie.cn/Article/details/gttevyxaii.html

class B : public Base { public: void f() override {} };
来源：http://dali.bjfxy.top/Article/details/gtvayjknqn.html

[S43] C++：智能指针
来源：http://dali.yueranfly.top/Article/details/gtpfruxsen.html

auto p = std::make_unique<int>(5);
来源：http://dali.pycfn.com/Article/details/gtymcskonv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gtygvoetcu.html

void inc(int &x) { ++x; }
来源：http://dali.zhixingplan.top/Article/details/gtpbnjefaf.html

[S45] C++：lambda
来源：http://dali.jlsjyb.cn/Article/details/gtbnwcvmok.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yonumen.top/Article/details/gtaxtzudwe.html

[S46] C++：函数模板
来源：http://dali.shuidangran.top/Article/details/gtockrihos.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhixingplan.top/Article/details/gtpnsirmif.html

[S47] C++：结构化绑定遍历
来源：http://dali.ybcxt.top/Article/details/gthnmkutqa.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hfpthk.cn/Article/details/gtcpzsetvf.html

[S48] C++：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtitjzgxkv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gtvguetplw.html

while (std::getline(in, line)) { }
来源：http://dali.mhx1999.top/Article/details/gtcfqhqjid.html

[S49] C++：写文件
来源：http://dali.haohaochexian.top/Article/details/gtfrjfgeda.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.svipenyu.cn/Article/details/gtalullewc.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gtnjrxdlyp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtnfdgmdly.html

[S51] C++：显式类型转换
来源：http://dali.yuxming.cn/Article/details/gtzflitumw.html

static_cast<double>(a) / b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvsttvuj.html

[S52] C++：const 与 noexcept
来源：http://dali.daxiang520.top/Article/details/gtnwtcljxp.html

int size() const noexcept { return n_; }
来源：http://dali.cashguo.top/Article/details/gtlmlphqza.html

[S53] C++：移动语义
来源：http://dali.dashuyun.cn/Article/details/gtazcnioyl.html

std::vector<int> w = std::move(v);
来源：http://dali.sweek.top/Article/details/gtcqbywwpi.html

[S54] C++：异常处理
来源：http://dali.chenjidiqi.icu/Article/details/gtbnravplw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gaohongyu789.top/Article/details/gtjadkmuve.html

[S55] C++：结构化绑定
来源：http://dali.bjfxy.top/Article/details/gtuvimvqqq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jlsjyb.cn/Article/details/gtyfbwbsnf.html

[S56] C++：optional
来源：http://dali.316326.xyz/Article/details/gtpvcsbjtq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jiagoushi.top/Article/details/gtoqhzhmyu.html

[S57] C++：编译期常量
来源：http://dali.yuanzhike.top/Article/details/gthjywzyla.html

constexpr int N = 10;
来源：http://dali.ivvv.top/Article/details/gtymagqlox.html

[S58] C++：命名空间
来源：http://dali.yj202588.top/Article/details/gtivmulnbm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zdqjudy.top/Article/details/gttsfwtzmq.html

[S59] C++：静态断言
来源：http://dali.tian-w.cn/Article/details/gtcarbsqnd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258.top/Article/details/gtspepmcje.html

[S60] C++：遍历并删除元素
来源：http://dali.jiagoushi.top/Article/details/gtgyyakneu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuanzhike.top/Article/details/gtaesdbsmo.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzmnxlre.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gtxdhxvmwl.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtztybygyw.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtxzzjhody.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtsljeyuyr.html

[T02] Kotlin：变量
来源：http://dali.jiagoushi.top/Article/details/gtxylqqrpw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hfpthk.cn/Article/details/gtzgprhhrg.html

[T03] Kotlin：字符串模板
来源：http://dali.daria6918.cn/Article/details/gtuxdcdtnk.html

"值: $b"
来源：http://dali.cucudq.cn/Article/details/gtbxhxruic.html

[T04] Kotlin：空安全
来源：http://dali.xylfe.cn/Article/details/gtqsauneqx.html

val n: String? = null;  n?.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxcqtiwr.html

[T05] Kotlin：when 表达式
来源：http://dali.svipenyu.cn/Article/details/gtwubzqkxv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.0kj1m.cn/Article/details/gtqphcvopj.html

[T06] Kotlin：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gtxvrckknr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtwmpfijmj.html

[T07] Kotlin：集合过滤
来源：http://dali.aizwys.cn/Article/details/gtzfacvizj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yvedp.cn/Article/details/gtdjdvwleb.html

[T08] Kotlin：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gtkdgymmbt.html

data class User(val name: String, val age: Int)
来源：http://dali.hysaishi.cn/Article/details/gtfjuxnysa.html

[T09] Kotlin：扩展函数
来源：http://dali.xylfe.cn/Article/details/gtvpbferub.html

fun String.exclaim() = this + "!"
来源：http://dali.sweek.top/Article/details/gtxcbwvqmn.html

[T10] Kotlin：默认参数
来源：http://dali.aibaodan.cn/Article/details/gtgqpbedvy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gtphkvlylk.html

[T11] Kotlin：协程
来源：http://dali.jqgfzy.top/Article/details/gtznfqfrmb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gaohongyu789.top/Article/details/gtvmfurnkq.html

[T12] Kotlin：解构声明
来源：http://dali.zycfv.cn/Article/details/gtulkhgngg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjopuatzb.html

[T13] Kotlin：只读 Map
来源：http://dali.meibo888.top/Article/details/gtqmlsxgmj.html

val m = mapOf("a" to 1)
来源：http://dali.daria6918.cn/Article/details/gtnqqwfcni.html

[T14] Kotlin：循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkanmsjyv.html

for (i in 1..10) println(i)
来源：http://dali.gzhubu.top/Article/details/gtichzekvm.html

[T15] Kotlin：接口
来源：http://dali.gogol.net.cn/Article/details/gtfcgbgxml.html

interface Shape { fun area(): Double }
来源：http://dali.iojbl.cn/Article/details/gtyemdtwqs.html

[T16] Swift：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtbydxhtzx.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gtojsqadlm.html

[T17] Swift：变量与常量
来源：http://dali.snrcjt.cn/Article/details/gtjhzrqjpm.html

var a = 1;  let b = 2
来源：http://dali.jlsjyb.cn/Article/details/gtturvmpcc.html

[T18] Swift：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtzbcluppd.html

"值: \(b)"
来源：http://dali.xinyue.icu/Article/details/gtntlxunba.html

[T19] Swift：可选绑定
来源：http://dali.xinyue.icu/Article/details/gtyxecuuqz.html

if let n = opt { print(n) }
来源：http://dali.svipenyu.cn/Article/details/gtcabiulje.html

[T20] Swift：数组操作
来源：http://dali.gzhubu.top/Article/details/gtsulihvkh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cashguo.top/Article/details/gtskupoxvr.html

[T21] Swift：遍历
来源：http://dali.cheryme.top/Article/details/gtcsftoymi.html

for x in a { print(x) }
来源：http://dali.tian-w.cn/Article/details/gtruoszily.html

[T22] Swift：字典
来源：http://dali.feifeiyinyue.top/Article/details/gtarydfisq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhoulong.xyz/Article/details/gtyaqvmkzz.html

[T23] Swift：函数
来源：http://dali.gotoacloud.top/Article/details/gtykkftyia.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnabuwes.html

[T24] Swift：闭包
来源：http://dali.aizwys.cn/Article/details/gtwmqsjjgk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cheryme.top/Article/details/gtvqwauojo.html

[T25] Swift：结构体
来源：http://dali.tanke756.top/Article/details/gtmkozxtbb.html

struct P { var x: Int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthitiqqub.html

[T26] Swift：类与重写
来源：http://dali.yonumen.top/Article/details/gtlulftzel.html

class A: Base { override func f() {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokzmonxn.html

[T27] Swift：错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gtrlkogaxf.html

do { try f() } catch { print(error) }
来源：http://dali.yanxiufei.cn/Article/details/gtpqosepem.html

[T28] Swift：枚举
来源：http://dali.c1oappe.top/Article/details/gthoyntcjc.html

enum Color { case red, green }
来源：http://dali.xuanzx.com/Article/details/gtytbcwynb.html

[T29] Swift：guard 提前返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhmizgjg.html

guard let x = opt else { return }
来源：http://dali.yuxming.cn/Article/details/gtxcxvvsji.html

[T30] Swift：协议
来源：http://dali.daxiang520.top/Article/details/gtxfxtdnun.html

protocol Shape { func area() -> Double }
来源：http://dali.0kj1m.cn/Article/details/gtawbzmmwl.html

[T31] Lua：Hello World
来源：http://dali.mhx1999.top/Article/details/gtkkkszkti.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtfggycwsq.html

[T32] Lua：局部变量
来源：http://dali.snrcjt.cn/Article/details/gticwrtfuh.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gtdqqtdlhd.html

[T33] Lua：表（数组）
来源：http://dali.xuanzx.com/Article/details/gtbjviwbyf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.aibaodan.cn/Article/details/gtffhbddsh.html

[T34] Lua：遍历表
来源：http://dali.hammf.cn/Article/details/gtjtiqqnkw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxinkj.top/Article/details/gtlwgxjcdz.html

[T35] Lua：字典表
来源：http://dali.ppjwa.cn/Article/details/gtpgwimahe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnithrcy.html

[T36] Lua：函数
来源：http://dali.vqdsnc.cn/Article/details/gtxneibuas.html

function add(a, b) return a + b end
来源：http://dali.yanxiufei.cn/Article/details/gtgogxkuno.html

[T37] Lua：字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gtrtlzaogb.html

"a" .. "b"
来源：http://dali.ybcxt.top/Article/details/gtcwqtjwgj.html

[T38] Lua：条件
来源：http://dali.nanxuanxn.top/Article/details/gtifqwkaic.html

if x > 0 then print("正") end
来源：http://dali.pengpengdd.cyou/Article/details/gtnytnkyym.html

[T39] Lua：模式匹配
来源：http://dali.xziqi.cn/Article/details/gticwronhx.html

string.find(s, "%d+")
来源：http://dali.snrcjt.cn/Article/details/gtbwrqnbnn.html

[T40] Lua：元表
来源：http://dali.shzxlz.cn/Article/details/gtkzevhime.html

setmetatable({}, { __index = base })
来源：http://dali.xuanzx.com/Article/details/gtnsbkptzm.html

[T41] Perl：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtmowmwjnl.html

print "Hello\n";
来源：http://dali.hysaishi.cn/Article/details/gtmqifgvev.html

[T42] Perl：变量类型
来源：http://dali.shzxlz.cn/Article/details/gtpohbjhyp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhoulong.xyz/Article/details/gtfkcvtzvu.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtvwzeaugv.html

"值: $a"
来源：http://dali.xylfe.cn/Article/details/gtwbcjglfa.html

[T44] Perl：条件
来源：http://dali.jqgfzy.top/Article/details/gtvqgdpate.html

if ($a > 0) { print "正"; }
来源：http://dali.havefunace.top/Article/details/gtofzsjigr.html

[T45] Perl：数组遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtvhwimvqv.html

for my $x (@arr) { print $x; }
来源：http://dali.jinqigfzy.top/Article/details/gtsyjsnszf.html

[T46] Perl：哈希操作
来源：http://dali.birdmap.top/Article/details/gtilyxbacv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.kuanghao11.cn/Article/details/gtjwndqudk.html

[T47] Perl：正则捕获
来源：http://dali.jinqigfzy.top/Article/details/gtxitzbmpc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwaiegggj.html

[T48] Perl：正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gtdrzggwjm.html

$s =~ s/old/new/g;
来源：http://dali.jinqigfzy.top/Article/details/gtjuwiedqj.html

[T49] Perl：函数
来源：http://dali.svipenyu.cn/Article/details/gtfjmkrdeo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtrpadgjtd.html

[T50] Perl：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtkzajmfwx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tianlin.xyz/Article/details/gtvbmnnnyu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cheryme.top/Article/details/gtccqxmdfp.html

[T51] Scala：Hello World
来源：http://dali.yonumen.top/Article/details/gtzzkmjujv.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gtfwlsiimj.html

[T52] Scala：变量
来源：http://dali.yanxiufei.cn/Article/details/gtsizzzhql.html

val a = 1;  var b = 2
来源：http://dali.hysaishi.cn/Article/details/gtjesiynzw.html

[T53] Scala：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtzpwqcwlq.html

s"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqekmyuck.html

[T54] Scala：集合映射
来源：http://dali.mhx1999.top/Article/details/gttxgnehcc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.kuanghao11.cn/Article/details/gtdskccubv.html

[T55] Scala：集合过滤
来源：http://dali.feifeiyinyue.top/Article/details/gthqdgqqeb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xziqi.cn/Article/details/gtbsgwaelw.html

[T56] Scala：样例类
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmvfphhq.html

case class User(name: String, age: Int)
来源：http://dali.birdmap.top/Article/details/gtddwdmdef.html

[T57] Scala：模式匹配
来源：http://dali.yanxiufei.cn/Article/details/gtuujtkujr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinqigfzy.top/Article/details/gtvnowvbhb.html

[T58] Scala：函数定义
来源：http://dali.ivvv.top/Article/details/gtatkaddqs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenlongwang.top/Article/details/gthjuoyvrf.html

[T59] Scala：循环
来源：http://dali.yuxming.cn/Article/details/gtpcqbxkjm.html

for (i <- 1 to 10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtcqvrslxc.html

[T60] Scala：折叠
来源：http://dali.hnxiangtu.top/Article/details/gtwsdiqjgi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tanke756.top/Article/details/gtqvyirfzr.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtvixlbqph.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.fengsongda.top/Article/details/gtolxypdqu.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtyttztvwe.html

[U01] Py：创建虚拟环境
来源：http://dali.haohaochexian.top/Article/details/gtlqtqzewz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.0kj1m.cn/Article/details/gtegxmtuww.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cucudq.cn/Article/details/gtrsnswiny.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cqqwz.cn/Article/details/gtiihrztpb.html

[U03] Py：加载 .env 配置
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfnhshqk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.dianchejie.cn/Article/details/gtglphzhik.html

[U04] Py：变量调试打印
来源：http://dali.jianghu66.top/Article/details/gtjunbbqby.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj20258888.top/Article/details/gtjdvbqbsy.html

[U05] Py：列表去重且保序
来源：http://dali.sweek.top/Article/details/gtdmocfmku.html

list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gtdfynjpkf.html

[U06] Py：合并两个字典
来源：http://dali.zhongyouzk.top/Article/details/gtofzcrpes.html

{**a, **b}
来源：http://dali.sxryk.cn/Article/details/gtgpbxultx.html

[U07] Py：反转字典键值
来源：http://dali.hammf.cn/Article/details/gtdrgabmep.html

{v: k for k, v in d.items()}
来源：http://dali.hywenlv.cn/Article/details/gteprseufx.html

[U08] Py：展平二维列表
来源：http://dali.jqgufenzy.top/Article/details/gtmhpxjpxb.html

[y for x in nested for y in x]
来源：http://dali.ppjwa.cn/Article/details/gtygqzdbij.html

[U09] Py：字典取最大值的键
来源：http://dali.sufxvd.cn/Article/details/gtmeequrvp.html

max(d, key=d.get)
来源：http://dali.xuanzx.com/Article/details/gtqqkspmqk.html

[U10] Py：按值排序字典
来源：http://dali.zdqjudy.top/Article/details/gtmiwpfcng.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.mhx1999.top/Article/details/gtgmxacavc.html

[U11] Py：生成器表达式
来源：http://dali.hnxiangtu.top/Article/details/gtaxynpixg.html

(x * 2 for x in arr)
来源：http://dali.gotoacloud.top/Article/details/gtwnmudfck.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.dashuyun.cn/Article/details/gthpgtmeyt.html

Counter(arr).most_common(3)
来源：http://dali.sxryk.cn/Article/details/gtphnrdmbm.html

[U13] Py：固定长度队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyflhvzyf.html

deque(maxlen=10)
来源：http://dali.xziqi.cn/Article/details/gtnnlbqtpb.html

[U14] Py：分组收集到列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbzbzwnr.html

defaultdict(list)
来源：http://dali.mhx1999.top/Article/details/gtulwapokr.html

[U15] Py：高精度计时
来源：http://dali.daxiang520.top/Article/details/gtfgeeourb.html

t = time.perf_counter()
来源：http://dali.ivvv.top/Article/details/gtfhxbylyo.html

[U16] Py：命令行参数解析
来源：http://dali.jqgufenzy.top/Article/details/gtsuqxtwvq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.fengsongda.top/Article/details/gtsqgbhkay.html

[U17] Py：初始化日志
来源：http://dali.yongpay.top/Article/details/gtbttwghhg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cashguo.top/Article/details/gtlojmcapl.html

[U18] Py：预编译正则
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkkfhgru.html

pat = re.compile(r"\d+")
来源：http://dali.nanxuanxn.top/Article/details/gtftaopsuh.html

[U19] Py：正则替换带回调
来源：http://dali.wangdashe.top/Article/details/gtvgmmksas.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgjckmfw.html

[U20] Py：缓存函数结果
来源：http://dali.yuanzhike.top/Article/details/gthgloxikw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tanke756.top/Article/details/gtpinrafpq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zdqjudy.top/Article/details/gtfntzcklk.html

@contextlib.contextmanager
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfhgsqse.html

[U22] Py：矩阵转置
来源：http://dali.wangdashe.top/Article/details/gtpevftqbi.html

list(zip(*m))
来源：http://dali.yueranfly.top/Article/details/gtpkvtczzh.html

[U23] Py：分块读取大文件
来源：http://dali.yvedp.cn/Article/details/gtdpqroshg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hywenlv.cn/Article/details/gttxjmjvho.html

[U24] Py：路径操作
来源：http://dali.hongshengwenyu.top/Article/details/gtfatgzipy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuanzhike.top/Article/details/gtdduvxhlq.html

[U25] Py：CSV 按字典读
来源：http://dali.pycfn.com/Article/details/gtgpqozjnf.html

csv.DictReader(f)
来源：http://dali.yangfankeji.com/Article/details/gtpapkjouz.html

[U26] Py：并发下载
来源：http://dali.cashguo.top/Article/details/gtuutkoshr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gzhubu.top/Article/details/gthxmmjsti.html

[U27] Py：异步 HTTP
来源：http://dali.jlsjyb.cn/Article/details/gtxcferlqh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.wangshuangyany.cn/Article/details/gtbcqtmrbh.html

[U28] Py：类型别名
来源：http://dali.pengpengdd.cyou/Article/details/gtldhyfyjz.html

UserId = int
来源：http://dali.cucudq.cn/Article/details/gtwyotsaox.html

[U29] Py：属性校验
来源：http://dali.chenzaomai.com/Article/details/gteubxxxag.html

@property 与 @x.setter 配合
来源：http://dali.guannengcc.top/Article/details/gtxnsejmxw.html

[U30] Py：数据类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrsioiyb.html

@dataclass(slots=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtjngxpbtp.html

[U31] Py：单测
来源：http://dali.gogol.net.cn/Article/details/gtnvxkrlda.html

python -m pytest -q
来源：http://dali.gotoacloud.top/Article/details/gtrosvimll.html

[U32] Py：代码格式化
来源：http://dali.xylfe.cn/Article/details/gtfwwhqfrg.html

ruff format . && ruff check --fix .
来源：http://dali.hysaishi.cn/Article/details/gtrzlytamh.html

[U33] Py：打包发布
来源：http://dali.xinyue.icu/Article/details/gtlsshrizx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhoulong.xyz/Article/details/gtdcozqqbb.html

[U34] Py：判断编码
来源：http://dali.gotoacloud.top/Article/details/gtbnfepiqc.html

chardet.detect(raw)
来源：http://dali.yongpay.top/Article/details/gtliokpjrp.html

[U35] Py：发送邮件
来源：http://dali.kuanghao11.cn/Article/details/gtafhvmusb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xziqi.cn/Article/details/gthtbccvrd.html

[U36] Py：定时任务
来源：http://dali.ivvv.top/Article/details/gtotiuixgp.html

schedule.every(10).minutes.do(job)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdgavpzb.html

[U37] Py：读写 Excel
来源：http://dali.sweek.top/Article/details/gtujntnlpd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinqigfzy.top/Article/details/gthawbudqg.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinqigfzy.top/Article/details/gtzykzdlli.html

Path(__file__).resolve().parent
来源：http://dali.xinyue.icu/Article/details/gtkrmtbybq.html


<!-- 参考信息 -->