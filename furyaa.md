代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangdashe.top/Article/details/gtqelqrize.html

[S15] C：类型转换
来源：http://dali.yuanzhike.top/Article/details/gtipozcwii.html

(double) a / b
来源：http://dali.vqdsnc.cn/Article/details/gtswjicpvl.html

[S16] C：位操作置位
来源：http://dali.redwolf501.top/Article/details/gtwfsytiyv.html

x |= (1 << 3);
来源：http://dali.hammf.cn/Article/details/gtpgdkbjae.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtgbqscvvc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zdqjudy.top/Article/details/gtuoskzgxb.html

[S18] C：命令行参数
来源：http://dali.ivvv.top/Article/details/gthfusmari.html

int main(int argc, char **argv)
来源：http://dali.zhiwuduotai.top/Article/details/gtgzxvgreq.html

[S19] C：快速排序
来源：http://dali.gogol.net.cn/Article/details/gtpjhjbwlz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtsrlzwyyq.html

[S20] C：二分查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtlvkwjf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gtsfxjwjpt.html

[S21] C：字符类别判断
来源：http://dali.quarkkingdee.top/Article/details/gtbtohasfl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.meibo888.top/Article/details/gtbmgmzsak.html

[S22] C：字符串转数字
来源：http://dali.guowangkeji.top/Article/details/gtfsnklqjd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangdashe.top/Article/details/gtjrphukyd.html

[S23] C：随机数
来源：http://dali.yangfankeji.com/Article/details/gtolfurhur.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ivvv.top/Article/details/gthlctxqvu.html

[S24] C：获取本地时间
来源：http://dali.smart0.xyz/Article/details/gtfcymbaua.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tian-w.cn/Article/details/gtzmgowmgf.html

[S25] C：内存拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtwzxoqrgw.html

memcpy(dst, src, n);
来源：http://dali.chenzaomai.com/Article/details/gttmsrberr.html

[S26] C：内存清零
来源：http://dali.fengsongda.top/Article/details/gtwbngicfv.html

memset(a, 0, sizeof a);
来源：http://dali.9152youxi.cn/Article/details/gtzemyqrwd.html

[S27] C：定义常量
来源：http://dali.aizwys.cn/Article/details/gtzpytbclc.html

const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtnorufozh.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gtdiqqeimm.html

static int counter = 0;
来源：http://dali.jianghu66.top/Article/details/gthjbjtcyx.html

[S29] C：变参函数
来源：http://dali.c1oappe.top/Article/details/gtvimmctau.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tian-w.cn/Article/details/gtnbsmldiv.html

[S30] C：头文件保护
来源：http://dali.ydzc1.top/Article/details/gtymgxxcxu.html

#ifndef X_H
来源：http://dali.0kj1m.cn/Article/details/gtakvjwktp.html

#define X_H
来源：http://dali.andypj.xyz/Article/details/gtpkigkmti.html

#endif
来源：http://dali.hongshengwenyu.top/Article/details/gtfqarosxx.html

[S31] C++：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtvrfgoycc.html

#include <iostream>
来源：http://dali.dashuyun.cn/Article/details/gtfnvpyjai.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jlsjyb.cn/Article/details/gtjnsxkkmi.html

[S32] C++：字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtyawxdwzf.html

std::string s = "hi";  s += "!";
来源：http://dali.0kj1m.cn/Article/details/gttaluedar.html

[S33] C++：vector 增删
来源：http://dali.kuanghao11.cn/Article/details/gtsuzmmiwg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zycfv.cn/Article/details/gtbyxipumw.html

[S34] C++：遍历 vector
来源：http://dali.kuanghao11.cn/Article/details/gtrpqofucr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dianchejie.cn/Article/details/gtbkhgmles.html

[S35] C++：map
来源：http://dali.cashguo.top/Article/details/gtacmakeim.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gthglgzqfe.html

[S36] C++：unordered_map
来源：http://dali.jyoumei.cn/Article/details/gtneftxwso.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtwswzmnhl.html

[S37] C++：set
来源：http://dali.xuanzx.com/Article/details/gtlqsekjik.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fzhhl.top/Article/details/gtpgvhnwes.html

[S38] C++：排序
来源：http://dali.yangfankeji.com/Article/details/gtwtjmrzfl.html

std::sort(v.begin(), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gtimntowim.html

[S39] C++：自定义比较器排序
来源：http://dali.yvedp.cn/Article/details/gtghbgednr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.svipenyu.cn/Article/details/gtnurfewhh.html

[S40] C++：查找元素
来源：http://dali.guowangkeji.top/Article/details/gtjcdndlil.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ydzc1.top/Article/details/gtbniqtiwj.html

[S41] C++：类与构造函数
来源：http://dali.daria6918.cn/Article/details/gtqrofyeba.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuanzhike.top/Article/details/gttxfaxnqb.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gtlcysuuml.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgsitiby.html

[S43] C++：智能指针
来源：http://dali.yj202588.top/Article/details/gtkhucdegs.html

auto p = std::make_unique<int>(5);
来源：http://dali.ivvv.top/Article/details/gtviahwvkt.html

[S44] C++：引用传参
来源：http://dali.ydzc1.top/Article/details/gtkbrufzdb.html

void inc(int &x) { ++x; }
来源：http://dali.chenzaomai.com/Article/details/gtemtpogbv.html

[S45] C++：lambda
来源：http://dali.hnxiangtu.top/Article/details/gtucoiuxeu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnqzz.top/Article/details/gtzgrdwfpu.html

[S46] C++：函数模板
来源：http://dali.chenjidiqi.icu/Article/details/gtfuqmqkif.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cdnleiting.top/Article/details/gtokmmzjzg.html

[S47] C++：结构化绑定遍历
来源：http://dali.gaohongyu789.top/Article/details/gtaozmcncj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenzaomai.com/Article/details/gtshdimkra.html

[S48] C++：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtbjkvydrn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.svipenyu.cn/Article/details/gtusndjruj.html

while (std::getline(in, line)) { }
来源：http://dali.fzhhl.top/Article/details/gtyvnrimtt.html

[S49] C++：写文件
来源：http://dali.tanke756.top/Article/details/gtywaaxvwb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yongpay.top/Article/details/gtqaotruat.html

[S50] C++：格式化数字
来源：http://dali.chenzaomai.com/Article/details/gtgscgwrjc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtncwdiawd.html

[S51] C++：显式类型转换
来源：http://dali.gotoacloud.top/Article/details/gtgotdwfsn.html

static_cast<double>(a) / b
来源：http://dali.yj202588.top/Article/details/gtwlbnivql.html

[S52] C++：const 与 noexcept
来源：http://dali.tian-w.cn/Article/details/gttauavnno.html

int size() const noexcept { return n_; }
来源：http://dali.zhixingplan.top/Article/details/gtueuohcqc.html

[S53] C++：移动语义
来源：http://dali.316326.xyz/Article/details/gtmikivzgq.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxinkj.top/Article/details/gtfqwvtyic.html

[S54] C++：异常处理
来源：http://dali.meibo888.top/Article/details/gtepdabruc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guannengcc.top/Article/details/gtzurwqmcj.html

[S55] C++：结构化绑定
来源：http://dali.xuetiantiany.cn/Article/details/gtxqglpkwo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtillqzjfe.html

[S56] C++：optional
来源：http://dali.iojbl.cn/Article/details/gtunqrenhp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jyoumei.cn/Article/details/gtpmhxnbps.html

[S57] C++：编译期常量
来源：http://dali.daxiang520.top/Article/details/gtehxdoqwr.html

constexpr int N = 10;
来源：http://dali.shzxlz.cn/Article/details/gtyisxahtv.html

[S58] C++：命名空间
来源：http://dali.jlsjyb.cn/Article/details/gtxhsujcfe.html

namespace ns { int f() { return 1; } }
来源：http://dali.gaohongyu789.top/Article/details/gtzwhjfjfn.html

[S59] C++：静态断言
来源：http://dali.xinyue.icu/Article/details/gtvxvzvvez.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pengpengdd.cyou/Article/details/gtihzymifb.html

[S60] C++：遍历并删除元素
来源：http://dali.sufxvd.cn/Article/details/gthgkcqqgx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gtiirbpyfg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtdxkovvdp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigfzy.top/Article/details/gtrjpygywy.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtinjlflbc.html

[T01] Kotlin：Hello World
来源：http://dali.smart0.xyz/Article/details/gturfmotka.html

println("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtgvqrnyoh.html

[T02] Kotlin：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxdqxhjp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.redwolf501.top/Article/details/gtopsdqqlu.html

[T03] Kotlin：字符串模板
来源：http://dali.fengsongda.top/Article/details/gtjljztgao.html

"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gtmapghkof.html

[T04] Kotlin：空安全
来源：http://dali.yueranfly.top/Article/details/gtrpivyxxr.html

val n: String? = null;  n?.length
来源：http://dali.hfpthk.cn/Article/details/gtuiujyxdb.html

[T05] Kotlin：when 表达式
来源：http://dali.guowangkeji.top/Article/details/gtqiftsgkm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangshuangyany.cn/Article/details/gtgdnxuiac.html

[T06] Kotlin：集合映射
来源：http://dali.chenlongwang.top/Article/details/gtbneqhvpe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ybcxt.top/Article/details/gtawinaetr.html

[T07] Kotlin：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gtxxqxymgr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigufen.top/Article/details/gtnkftbmde.html

[T08] Kotlin：数据类
来源：http://dali.ppjwa.cn/Article/details/gtyaerqjik.html

data class User(val name: String, val age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gtayanszfg.html

[T09] Kotlin：扩展函数
来源：http://dali.pengpengdd.cyou/Article/details/gtgfhzxppg.html

fun String.exclaim() = this + "!"
来源：http://dali.fzhhl.top/Article/details/gtqpvysxhu.html

[T10] Kotlin：默认参数
来源：http://dali.yuanzhike.top/Article/details/gtkirlyubo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cucudq.cn/Article/details/gtoxzkphfu.html

[T11] Kotlin：协程
来源：http://dali.chenlongwang.top/Article/details/gttyzbgvxl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenjidiqi.icu/Article/details/gtjfhyvxhk.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuncsrhai.html

val (a, b) = Pair(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtzihanfqp.html

[T13] Kotlin：只读 Map
来源：http://dali.mhx1999.top/Article/details/gtltbadqqd.html

val m = mapOf("a" to 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbbeqfnr.html

[T14] Kotlin：循环
来源：http://dali.smart0.xyz/Article/details/gtckcorpww.html

for (i in 1..10) println(i)
来源：http://dali.316326.xyz/Article/details/gtcbrojuay.html

[T15] Kotlin：接口
来源：http://dali.0kj1m.cn/Article/details/gtvdapzuiy.html

interface Shape { fun area(): Double }
来源：http://dali.chenjidiqi.icu/Article/details/gtdzzlccmv.html

[T16] Swift：Hello World
来源：http://dali.cheryme.top/Article/details/gttzkjqout.html

print("Hello")
来源：http://dali.zycfv.cn/Article/details/gtfscpdest.html

[T17] Swift：变量与常量
来源：http://dali.hywenlv.cn/Article/details/gtqtlbqfiu.html

var a = 1;  let b = 2
来源：http://dali.sysykeji.top/Article/details/gtdreymhmh.html

[T18] Swift：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtmeumtxyr.html

"值: \(b)"
来源：http://dali.jinqigfzy.top/Article/details/gtniqgujet.html

[T19] Swift：可选绑定
来源：http://dali.zhongyouzk.top/Article/details/gtvkooxsur.html

if let n = opt { print(n) }
来源：http://dali.chenjidiqi.icu/Article/details/gtoyvnwvrc.html

[T20] Swift：数组操作
来源：http://dali.hongshengwenyu.top/Article/details/gtuvcnsmty.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.meibo888.top/Article/details/gttvvprehe.html

[T21] Swift：遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklozhmar.html

for x in a { print(x) }
来源：http://dali.guannengcc.top/Article/details/gtmqhfofyy.html

[T22] Swift：字典
来源：http://dali.xinyue.icu/Article/details/gtcdupqizx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.bjfxy.top/Article/details/gtmglqdawu.html

[T23] Swift：函数
来源：http://dali.zhixingplan.top/Article/details/gtjnsevail.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawnkdhkk.html

[T24] Swift：闭包
来源：http://dali.jinqigfzy.top/Article/details/gtuvonepiy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cheryme.top/Article/details/gtfrcjaaij.html

[T25] Swift：结构体
来源：http://dali.shuidangran.top/Article/details/gtqircjufw.html

struct P { var x: Int }
来源：http://dali.sxryk.cn/Article/details/gtdwzfhatn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gttfaymkxn.html

class A: Base { override func f() {} }
来源：http://dali.dashuyun.cn/Article/details/gtkivwforj.html

[T27] Swift：错误处理
来源：http://dali.ehwqpu.com/Article/details/gtrtfbnwab.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gtjinlbrfy.html

[T28] Swift：枚举
来源：http://dali.aibaodan.cn/Article/details/gtgzaprpgk.html

enum Color { case red, green }
来源：http://dali.ivvv.top/Article/details/gtocrqtuyo.html

[T29] Swift：guard 提前返回
来源：http://dali.meibo888.top/Article/details/gtawihitgb.html

guard let x = opt else { return }
来源：http://dali.yueranfly.top/Article/details/gtzdciuiuj.html

[T30] Swift：协议
来源：http://dali.yj20258888.top/Article/details/gtqesvwnli.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxuanxn.top/Article/details/gtlwquxypa.html

[T31] Lua：Hello World
来源：http://dali.sweek.top/Article/details/gtidlwfxjz.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtuqnueegy.html

[T32] Lua：局部变量
来源：http://dali.hfpthk.cn/Article/details/gttcvxlcaa.html

local a = 1
来源：http://dali.cqqwz.cn/Article/details/gtwkyahmzg.html

[T33] Lua：表（数组）
来源：http://dali.c1oappe.top/Article/details/gtqlssldlj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yongpay.top/Article/details/gtidpticzz.html

[T34] Lua：遍历表
来源：http://dali.jiagoushi.top/Article/details/gtumaxgvwu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hammf.cn/Article/details/gtmcihlblf.html

[T35] Lua：字典表
来源：http://dali.daxiang520.top/Article/details/gtyajbdowy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xylfe.cn/Article/details/gtxooltpje.html

[T36] Lua：函数
来源：http://dali.pycfn.com/Article/details/gtwaowzvdb.html

function add(a, b) return a + b end
来源：http://dali.zhengqikj.top/Article/details/gtxclbxsmq.html

[T37] Lua：字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gtjqeczlpy.html

"a" .. "b"
来源：http://dali.dianchejie.cn/Article/details/gtqlyyqpxn.html

[T38] Lua：条件
来源：http://dali.redwolf501.top/Article/details/gtpgxbzbfg.html

if x > 0 then print("正") end
来源：http://dali.zhengqikj.top/Article/details/gtosusbhrh.html

[T39] Lua：模式匹配
来源：http://dali.sweek.top/Article/details/gtlrlpkrkp.html

string.find(s, "%d+")
来源：http://dali.316326.xyz/Article/details/gtjvlfgzbs.html

[T40] Lua：元表
来源：http://dali.ppjwa.cn/Article/details/gtxnscmfsk.html

setmetatable({}, { __index = base })
来源：http://dali.guannengcc.top/Article/details/gtiloxuvut.html

[T41] Perl：Hello World
来源：http://dali.andypj.xyz/Article/details/gtrnllrlsb.html

print "Hello\n";
来源：http://dali.daxiang520.top/Article/details/gtbonbdgyh.html

[T42] Perl：变量类型
来源：http://dali.sufxvd.cn/Article/details/gtsgywspxx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.iojbl.cn/Article/details/gtfyallbxh.html

[T43] Perl：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtgdcmziew.html

"值: $a"
来源：http://dali.yanxiufei.cn/Article/details/gtnuhsruty.html

[T44] Perl：条件
来源：http://dali.jinqigfzy.top/Article/details/gtrczsmsqn.html

if ($a > 0) { print "正"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtuumazxka.html

[T45] Perl：数组遍历
来源：http://dali.yuanzhike.top/Article/details/gtuhhgidmy.html

for my $x (@arr) { print $x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgstugcpz.html

[T46] Perl：哈希操作
来源：http://dali.wangshuangyany.cn/Article/details/gtorckeggp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aibaodan.cn/Article/details/gthitahjnt.html

[T47] Perl：正则捕获
来源：http://dali.hywenlv.cn/Article/details/gtdthjisme.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zycfv.cn/Article/details/gtnseblilk.html

[T48] Perl：正则替换
来源：http://dali.gzhubu.top/Article/details/gtbvtnhdnh.html

$s =~ s/old/new/g;
来源：http://dali.yuanzhike.top/Article/details/gtrgulcbve.html

[T49] Perl：函数
来源：http://dali.hongshengwenyu.top/Article/details/gthgcfcdah.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtwguafikh.html

[T50] Perl：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtniqywsne.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.quarkkingdee.top/Article/details/gtsosxdzcf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tianlin.xyz/Article/details/gtycmcvauh.html

[T51] Scala：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gthbsxnpvd.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwacqiif.html

[T52] Scala：变量
来源：http://dali.sysykeji.top/Article/details/gtkthojzur.html

val a = 1;  var b = 2
来源：http://dali.shzxlz.cn/Article/details/gtivnqifvj.html

[T53] Scala：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtrzcidkwk.html

s"值: $b"
来源：http://dali.ivvv.top/Article/details/gtnxipzzrh.html

[T54] Scala：集合映射
来源：http://dali.xuetiantiany.cn/Article/details/gtxilbxief.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dianchejie.cn/Article/details/gtlaysdbqb.html

[T55] Scala：集合过滤
来源：http://dali.redwolf501.top/Article/details/gtbygscsut.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yvedp.cn/Article/details/gtqemwuhka.html

[T56] Scala：样例类
来源：http://dali.guowangkeji.top/Article/details/gtyeulilcb.html

case class User(name: String, age: Int)
来源：http://dali.iojbl.cn/Article/details/gtxclhgfnc.html

[T57] Scala：模式匹配
来源：http://dali.shuidangran.top/Article/details/gtvosytrgd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.kuanghao11.cn/Article/details/gtnoqvvboi.html

[T58] Scala：函数定义
来源：http://dali.hysaishi.cn/Article/details/gtsqltqjcc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dianchejie.cn/Article/details/gtumijklmw.html

[T59] Scala：循环
来源：http://dali.meibo888.top/Article/details/gtcmdsvsxg.html

for (i <- 1 to 10) println(i)
来源：http://dali.birdmap.top/Article/details/gtnzjwjhdf.html

[T60] Scala：折叠
来源：http://dali.jianghu66.top/Article/details/gtewyqiwwh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.mhx1999.top/Article/details/gtygmsadvx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtecbidzfk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hysaishi.cn/Article/details/gtymlvddkj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtywzzempm.html

[U01] Py：创建虚拟环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpkjovdo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.meibo888.top/Article/details/gtrlgubulx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ybcxt.top/Article/details/gtjinebojl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tian-w.cn/Article/details/gtexqsynoh.html

[U03] Py：加载 .env 配置
来源：http://dali.gogol.net.cn/Article/details/gtxfprfdfp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuanzhike.top/Article/details/gtuulhooqm.html

[U04] Py：变量调试打印
来源：http://dali.shzxlz.cn/Article/details/gtpgkddqzs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zycfv.cn/Article/details/gtjeesxwbq.html

[U05] Py：列表去重且保序
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrtiveml.html

list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gtebtrhjxx.html

[U06] Py：合并两个字典
来源：http://dali.xinyue.icu/Article/details/gtywnnhdox.html

{**a, **b}
来源：http://dali.c1oappe.top/Article/details/gtxcvmyitn.html

[U07] Py：反转字典键值
来源：http://dali.daxiang520.top/Article/details/gtqwcmhgcz.html

{v: k for k, v in d.items()}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkpchjpv.html

[U08] Py：展平二维列表
来源：http://dali.yanxiufei.cn/Article/details/gttcqtemgq.html

[y for x in nested for y in x]
来源：http://dali.sysykeji.top/Article/details/gtkrebmevf.html

[U09] Py：字典取最大值的键
来源：http://dali.sufxvd.cn/Article/details/gtyeifkjep.html

max(d, key=d.get)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzoyugxo.html

[U10] Py：按值排序字典
来源：http://dali.meibo888.top/Article/details/gtvausunea.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jlsjyb.cn/Article/details/gtaaqligsh.html

[U11] Py：生成器表达式
来源：http://dali.andypj.xyz/Article/details/gtfoxenrjb.html

(x * 2 for x in arr)
来源：http://dali.zhongyouzk.top/Article/details/gtuyfatyrq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.316326.xyz/Article/details/gtmqzyzoeh.html

Counter(arr).most_common(3)
来源：http://dali.cashguo.top/Article/details/gtuiyhnrox.html

[U13] Py：固定长度队列
来源：http://dali.zdqjudy.top/Article/details/gtwxbxvhpe.html

deque(maxlen=10)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizwqnbyy.html

[U14] Py：分组收集到列表
来源：http://dali.0kj1m.cn/Article/details/gtkiaikbxb.html

defaultdict(list)
来源：http://dali.cdnleiting.top/Article/details/gtmeobzxqi.html

[U15] Py：高精度计时
来源：http://dali.chenjidiqi.icu/Article/details/gtoivdtqsc.html

t = time.perf_counter()
来源：http://dali.hnqzz.top/Article/details/gtrxmwhold.html

[U16] Py：命令行参数解析
来源：http://dali.pengpengdd.cyou/Article/details/gtorteziur.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewwkzfsn.html

[U17] Py：初始化日志
来源：http://dali.zycfv.cn/Article/details/gtwrkaltax.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yangfankeji.com/Article/details/gtrkfxtlyu.html

[U18] Py：预编译正则
来源：http://dali.guannengcc.top/Article/details/gtkdjtfueu.html

pat = re.compile(r"\d+")
来源：http://dali.dianchejie.cn/Article/details/gtrnesnhcb.html

[U19] Py：正则替换带回调
来源：http://dali.vqdsnc.cn/Article/details/gtmyrtuvwd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ivvv.top/Article/details/gtdtjqhuko.html

[U20] Py：缓存函数结果
来源：http://dali.zhongyouzk.top/Article/details/gtxpuldzit.html

@functools.lru_cache(maxsize=None)
来源：http://dali.wangshuangyany.cn/Article/details/gtebhmmoly.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhoulong.xyz/Article/details/gtmchceala.html

@contextlib.contextmanager
来源：http://dali.ivvv.top/Article/details/gtxvysztsn.html

[U22] Py：矩阵转置
来源：http://dali.cdnleiting.top/Article/details/gtleobiqfm.html

list(zip(*m))
来源：http://dali.dashuyun.cn/Article/details/gtvmlxgfii.html

[U23] Py：分块读取大文件
来源：http://dali.yj20258888.top/Article/details/gtiuzqwjeq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yvedp.cn/Article/details/gtnsgeunwj.html

[U24] Py：路径操作
来源：http://dali.c1oappe.top/Article/details/gtdejpgeje.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gtsqlbxtfz.html

[U25] Py：CSV 按字典读
来源：http://dali.yj20258888.top/Article/details/gtdpoyafdt.html

csv.DictReader(f)
来源：http://dali.meibo888.top/Article/details/gtjkjavgpb.html

[U26] Py：并发下载
来源：http://dali.nwbrower.top/Article/details/gtphkougpq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tianlin.xyz/Article/details/gtqvmxnaut.html

[U27] Py：异步 HTTP
来源：http://dali.0kj1m.cn/Article/details/gtwpbagiwy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.aizwys.cn/Article/details/gtclayamjn.html

[U28] Py：类型别名
来源：http://dali.gogol.net.cn/Article/details/gtsxerewzu.html

UserId = int
来源：http://dali.yuxming.cn/Article/details/gtzilewnxn.html

[U29] Py：属性校验
来源：http://dali.aibaodan.cn/Article/details/gtpqetpcfb.html

@property 与 @x.setter 配合
来源：http://dali.c1oappe.top/Article/details/gtwqxfgbfw.html

[U30] Py：数据类
来源：http://dali.316326.xyz/Article/details/gtwgmbcfqi.html

@dataclass(slots=True)
来源：http://dali.iojbl.cn/Article/details/gthfuahmsh.html

[U31] Py：单测
来源：http://dali.zhixingplan.top/Article/details/gtjhshavot.html

python -m pytest -q
来源：http://dali.yangfankeji.com/Article/details/gtufxyywhp.html

[U32] Py：代码格式化
来源：http://dali.jyoumei.cn/Article/details/gthdudbikn.html

ruff format . && ruff check --fix .
来源：http://dali.yj20258888.top/Article/details/gttnanrpkx.html

[U33] Py：打包发布
来源：http://dali.hnqzz.top/Article/details/gtfxfjcmzq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj20258.top/Article/details/gtpheittyg.html

[U34] Py：判断编码
来源：http://dali.chenlongwang.top/Article/details/gtwoxpomqc.html

chardet.detect(raw)
来源：http://dali.snrcjt.cn/Article/details/gtsbnnbvep.html

[U35] Py：发送邮件
来源：http://dali.yangfankeji.com/Article/details/gthzcveqxq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xuetiantiany.cn/Article/details/gtfpwjgcpp.html

[U36] Py：定时任务
来源：http://dali.yuxming.cn/Article/details/gtmypbmcis.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhixingplan.top/Article/details/gtyqbtevsa.html

[U37] Py：读写 Excel
来源：http://dali.cdnleiting.top/Article/details/gtxgplosrm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhiwuduotai.top/Article/details/gteatrytot.html

[U38] Py：获取脚本所在目录
来源：http://dali.shuidangran.top/Article/details/gtuhcthqad.html

Path(__file__).resolve().parent
来源：http://dali.hfpthk.cn/Article/details/gtjloazsyb.html


<!-- 参考信息 -->