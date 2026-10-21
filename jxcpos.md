代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gtioxxmsra.html

[S13] C：宏定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwybzuzt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yanxiufei.cn/Article/details/gtnwanbseo.html

[S14] C：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtucscadzq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuetiantiany.cn/Article/details/gtuwebwfnv.html

[S15] C：类型转换
来源：http://dali.zhixingplan.top/Article/details/gtylfxhbto.html

(double) a / b
来源：http://dali.zhixingplan.top/Article/details/gtwirtgjbz.html

[S16] C：位操作置位
来源：http://dali.sufxvd.cn/Article/details/gtuzlhzull.html

x |= (1 << 3);
来源：http://dali.tanke756.top/Article/details/gtfadhimhd.html

[S17] C：安全拼接字符串
来源：http://dali.fengsongda.top/Article/details/gtraxbdelf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgufenzy.top/Article/details/gtfsstmtqm.html

[S18] C：命令行参数
来源：http://dali.aizwys.cn/Article/details/gtpdlgodwg.html

int main(int argc, char **argv)
来源：http://dali.yj20258888.top/Article/details/gtpktrbbwm.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gtrybvlwps.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtquwumrbc.html

[S20] C：二分查找
来源：http://dali.shzxlz.cn/Article/details/gtieushpib.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sufxvd.cn/Article/details/gtugsvecir.html

[S21] C：字符类别判断
来源：http://dali.guowangkeji.top/Article/details/gtednjevtv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuanzx.com/Article/details/gtagvaobyn.html

[S22] C：字符串转数字
来源：http://dali.nanxuanxn.top/Article/details/gtminaoxcp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zdqjudy.top/Article/details/gtmvcpcihs.html

[S23] C：随机数
来源：http://dali.yj20258.top/Article/details/gtrsxnzdct.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ivvv.top/Article/details/gtmjylouoi.html

[S24] C：获取本地时间
来源：http://dali.guannengcc.top/Article/details/gtocdcrolo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ppjwa.cn/Article/details/gtcammgbro.html

[S25] C：内存拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtylznxujv.html

memcpy(dst, src, n);
来源：http://dali.zycfv.cn/Article/details/gtwhouwesx.html

[S26] C：内存清零
来源：http://dali.tianlin.xyz/Article/details/gtlauqmnqp.html

memset(a, 0, sizeof a);
来源：http://dali.zhengqikj.top/Article/details/gtfvdpvbch.html

[S27] C：定义常量
来源：http://dali.aibaodan.cn/Article/details/gtphqobkiv.html

const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtbhmlbzyr.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gtgkqrdzck.html

static int counter = 0;
来源：http://dali.iojbl.cn/Article/details/gtiiecpkpx.html

[S29] C：变参函数
来源：http://dali.hfpthk.cn/Article/details/gtfnmmnmhw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pengpengdd.cyou/Article/details/gtoitspyph.html

[S30] C：头文件保护
来源：http://dali.ivvv.top/Article/details/gtjyqednfb.html

#ifndef X_H
来源：http://dali.feifeiyinyue.top/Article/details/gtvlrvumwy.html

#define X_H
来源：http://dali.sweek.top/Article/details/gtabdwaslq.html

#endif
来源：http://dali.daria6918.cn/Article/details/gtjpoevxth.html

[S31] C++：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtdocifeie.html

#include <iostream>
来源：http://dali.wangshuangyany.cn/Article/details/gtrreijmzl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.havefunace.top/Article/details/gtapoldfqa.html

[S32] C++：字符串
来源：http://dali.pycfn.com/Article/details/gtizvbalzn.html

std::string s = "hi";  s += "!";
来源：http://dali.chenjidiqi.icu/Article/details/gtcrtcawqg.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gtdotxaczs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.bjfxy.top/Article/details/gtrnaifxff.html

[S34] C++：遍历 vector
来源：http://dali.birdmap.top/Article/details/gttyifdhfo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.redwolf501.top/Article/details/gticxocyvk.html

[S35] C++：map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsrxppcw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtkmadjsmk.html

[S36] C++：unordered_map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjzedcko.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtbusxgxpg.html

[S37] C++：set
来源：http://dali.birdmap.top/Article/details/gtuoyxctau.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtueniuufx.html

[S38] C++：排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwpgcayt.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckmifhee.html

[S39] C++：自定义比较器排序
来源：http://dali.guannengcc.top/Article/details/gtyyloisaf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.vqdsnc.cn/Article/details/gtinpzdtxz.html

[S40] C++：查找元素
来源：http://dali.shzxlz.cn/Article/details/gtbpqbcxev.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.vqdsnc.cn/Article/details/gthehyjdkf.html

[S41] C++：类与构造函数
来源：http://dali.xylfe.cn/Article/details/gtscsxeefl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gtstlgydsn.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258.top/Article/details/gtqzavbjto.html

class B : public Base { public: void f() override {} };
来源：http://dali.9152youxi.cn/Article/details/gtcaonzuem.html

[S43] C++：智能指针
来源：http://dali.xziqi.cn/Article/details/gtvxvocprw.html

auto p = std::make_unique<int>(5);
来源：http://dali.9152youxi.cn/Article/details/gtiheudvoz.html

[S44] C++：引用传参
来源：http://dali.gaohongyu789.top/Article/details/gtjzgopbmg.html

void inc(int &x) { ++x; }
来源：http://dali.guowangkeji.top/Article/details/gtyzhwmian.html

[S45] C++：lambda
来源：http://dali.gotoacloud.top/Article/details/gtkhmvtzkq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jiagoushi.top/Article/details/gtjiqyooif.html

[S46] C++：函数模板
来源：http://dali.cashguo.top/Article/details/gtpegrvpee.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tanke756.top/Article/details/gtgsrzuhca.html

[S47] C++：结构化绑定遍历
来源：http://dali.yueranfly.top/Article/details/gtplfrzaqk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fengsongda.top/Article/details/gtibmpdnpd.html

[S48] C++：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtbatzpnhy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenzaomai.com/Article/details/gtxbpsuycg.html

while (std::getline(in, line)) { }
来源：http://dali.fengsongda.top/Article/details/gttgmdmqox.html

[S49] C++：写文件
来源：http://dali.yj20258.top/Article/details/gtoythjvew.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhoulong.xyz/Article/details/gtqvmlwedp.html

[S50] C++：格式化数字
来源：http://dali.smart0.xyz/Article/details/gtkgpcgbbs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtndfpoarl.html

[S51] C++：显式类型转换
来源：http://dali.aizwys.cn/Article/details/gtdfxhsynf.html

static_cast<double>(a) / b
来源：http://dali.jinqigfzy.top/Article/details/gtbewyhvlo.html

[S52] C++：const 与 noexcept
来源：http://dali.andypj.xyz/Article/details/gtmzkoenjz.html

int size() const noexcept { return n_; }
来源：http://dali.meibo888.top/Article/details/gtybivyehb.html

[S53] C++：移动语义
来源：http://dali.yj20258.top/Article/details/gtxjsnxrtd.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxinkj.top/Article/details/gttwrlqsuo.html

[S54] C++：异常处理
来源：http://dali.dashuyun.cn/Article/details/gtshojydhl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpjdcntk.html

[S55] C++：结构化绑定
来源：http://dali.nanxuanxn.top/Article/details/gtwrzqhxgx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nwbrower.top/Article/details/gtjftrailt.html

[S56] C++：optional
来源：http://dali.nwbrower.top/Article/details/gtfqrlplgp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yueranfly.top/Article/details/gttorumdnk.html

[S57] C++：编译期常量
来源：http://dali.pengpengdd.cyou/Article/details/gtiokeiqox.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gtgoosalvw.html

[S58] C++：命名空间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfocnvan.html

namespace ns { int f() { return 1; } }
来源：http://dali.gaohongyu789.top/Article/details/gtuhlkfamo.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpttwmlvf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.svipenyu.cn/Article/details/gtqxrglmjr.html

[S60] C++：遍历并删除元素
来源：http://dali.tian-w.cn/Article/details/gtidusqkrb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shuidangran.top/Article/details/gtomvkoitm.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtkjxulvpi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jlsjyb.cn/Article/details/gtgiickdzc.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtbgqeutzi.html

[T01] Kotlin：Hello World
来源：http://dali.cucudq.cn/Article/details/gtysdavlat.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsldncyt.html

[T02] Kotlin：变量
来源：http://dali.yonumen.top/Article/details/gtcmqsydgt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gzhubu.top/Article/details/gttpwyzjiu.html

[T03] Kotlin：字符串模板
来源：http://dali.yvedp.cn/Article/details/gtjinnaxwp.html

"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gtyzfrfrnp.html

[T04] Kotlin：空安全
来源：http://dali.jlsjyb.cn/Article/details/gtttzdgnsg.html

val n: String? = null;  n?.length
来源：http://dali.jinqigfzy.top/Article/details/gtugwpioyk.html

[T05] Kotlin：when 表达式
来源：http://dali.hammf.cn/Article/details/gtbzkajnah.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tanke756.top/Article/details/gtgidvpbql.html

[T06] Kotlin：集合映射
来源：http://dali.dashuyun.cn/Article/details/gtugycbvic.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj20258888.top/Article/details/gthnsfdpox.html

[T07] Kotlin：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gtmjkgdnsr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgufenzy.top/Article/details/gtzqxjdzgj.html

[T08] Kotlin：数据类
来源：http://dali.shuidangran.top/Article/details/gtlnzbvbmo.html

data class User(val name: String, val age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gtkusyalak.html

[T09] Kotlin：扩展函数
来源：http://dali.yonumen.top/Article/details/gtgpsdgtjp.html

fun String.exclaim() = this + "!"
来源：http://dali.hnqzz.top/Article/details/gtcdawiuam.html

[T10] Kotlin：默认参数
来源：http://dali.cucudq.cn/Article/details/gthboadcti.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgufenzy.top/Article/details/gtonlycwur.html

[T11] Kotlin：协程
来源：http://dali.c1oappe.top/Article/details/gttopzdipo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gogol.net.cn/Article/details/gtlxpjbysz.html

[T12] Kotlin：解构声明
来源：http://dali.zhoulong.xyz/Article/details/gtswzfrefg.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtfhtnybqs.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gtfbbgsnod.html

val m = mapOf("a" to 1)
来源：http://dali.pengpengdd.cyou/Article/details/gttqjqxkde.html

[T14] Kotlin：循环
来源：http://dali.aizwys.cn/Article/details/gtaxdkkehi.html

for (i in 1..10) println(i)
来源：http://dali.yongpay.top/Article/details/gtmnrqzcvx.html

[T15] Kotlin：接口
来源：http://dali.xziqi.cn/Article/details/gtwehatsil.html

interface Shape { fun area(): Double }
来源：http://dali.nanxinkj.top/Article/details/gtnphrdipy.html

[T16] Swift：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtmkbxqnsz.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnjcgpfh.html

[T17] Swift：变量与常量
来源：http://dali.wangdashe.top/Article/details/gtedyhbdqm.html

var a = 1;  let b = 2
来源：http://dali.nwbrower.top/Article/details/gtlajghpjx.html

[T18] Swift：字符串插值
来源：http://dali.pycfn.com/Article/details/gtatyapmam.html

"值: \(b)"
来源：http://dali.nwbrower.top/Article/details/gtwzkjjzfx.html

[T19] Swift：可选绑定
来源：http://dali.smart0.xyz/Article/details/gtarkaizks.html

if let n = opt { print(n) }
来源：http://dali.cucudq.cn/Article/details/gtxsjedpia.html

[T20] Swift：数组操作
来源：http://dali.jlsjyb.cn/Article/details/gtwvwbcdsh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.andypj.xyz/Article/details/gtzjdopwyp.html

[T21] Swift：遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtdyjrtzdv.html

for x in a { print(x) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpnigken.html

[T22] Swift：字典
来源：http://dali.shangyingyoupin.top/Article/details/gtrksyfzez.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aizwys.cn/Article/details/gtgbkjqecn.html

[T23] Swift：函数
来源：http://dali.hammf.cn/Article/details/gtpodqmywl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrocgkcw.html

[T24] Swift：闭包
来源：http://dali.chenzaomai.com/Article/details/gtxgttdrzo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtzpwuswta.html

[T25] Swift：结构体
来源：http://dali.hywenlv.cn/Article/details/gtgtizbnhv.html

struct P { var x: Int }
来源：http://dali.gogol.net.cn/Article/details/gtsrvhvgob.html

[T26] Swift：类与重写
来源：http://dali.wangdashe.top/Article/details/gtzvvdeztv.html

class A: Base { override func f() {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxeuoxyb.html

[T27] Swift：错误处理
来源：http://dali.haohaochexian.top/Article/details/gtczqppyga.html

do { try f() } catch { print(error) }
来源：http://dali.yuanzhike.top/Article/details/gtlneubjhc.html

[T28] Swift：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtvsnhnpkf.html

enum Color { case red, green }
来源：http://dali.chenlongwang.top/Article/details/gtibciztpp.html

[T29] Swift：guard 提前返回
来源：http://dali.daria6918.cn/Article/details/gtkmalkppn.html

guard let x = opt else { return }
来源：http://dali.zhixingplan.top/Article/details/gtqkvausvk.html

[T30] Swift：协议
来源：http://dali.0kj1m.cn/Article/details/gtefztonhe.html

protocol Shape { func area() -> Double }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxmcmkuq.html

[T31] Lua：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtbfdqlxej.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gtqoevxeim.html

[T32] Lua：局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gtxtvafbfh.html

local a = 1
来源：http://dali.jyoumei.cn/Article/details/gtkufoklgx.html

[T33] Lua：表（数组）
来源：http://dali.jinqigufen.top/Article/details/gtfmgqmvhd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhongyouzk.top/Article/details/gtbtanhgrx.html

[T34] Lua：遍历表
来源：http://dali.redwolf501.top/Article/details/gtnicyhhwm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xuanzx.com/Article/details/gttuqgmjmw.html

[T35] Lua：字典表
来源：http://dali.hywenlv.cn/Article/details/gtnwtbhixs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sweek.top/Article/details/gtkqunbrgp.html

[T36] Lua：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtadpyconj.html

function add(a, b) return a + b end
来源：http://dali.yuanzhike.top/Article/details/gtirweiftx.html

[T37] Lua：字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtyklyhwjm.html

"a" .. "b"
来源：http://dali.yuanzhike.top/Article/details/gtkarcofbi.html

[T38] Lua：条件
来源：http://dali.xziqi.cn/Article/details/gtxrmnfneb.html

if x > 0 then print("正") end
来源：http://dali.xuetiantiany.cn/Article/details/gtplptioyp.html

[T39] Lua：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gtigkaqoja.html

string.find(s, "%d+")
来源：http://dali.jianghu66.top/Article/details/gtlqchcmdz.html

[T40] Lua：元表
来源：http://dali.316326.xyz/Article/details/gtgoeezdvo.html

setmetatable({}, { __index = base })
来源：http://dali.zhixingplan.top/Article/details/gtkuaxbsxy.html

[T41] Perl：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtrbutwofl.html

print "Hello\n";
来源：http://dali.yonumen.top/Article/details/gtblqjccfa.html

[T42] Perl：变量类型
来源：http://dali.aibaodan.cn/Article/details/gtzhzzuads.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.daxiang520.top/Article/details/gtksgfciht.html

[T43] Perl：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtmuutqirr.html

"值: $a"
来源：http://dali.quarkkingdee.top/Article/details/gtpjqukysu.html

[T44] Perl：条件
来源：http://dali.9152youxi.cn/Article/details/gtouayadtp.html

if ($a > 0) { print "正"; }
来源：http://dali.jianghu66.top/Article/details/gtjgowfqje.html

[T45] Perl：数组遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrizrezdg.html

for my $x (@arr) { print $x; }
来源：http://dali.guowangkeji.top/Article/details/gtpapqmcep.html

[T46] Perl：哈希操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkvrnzil.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zycfv.cn/Article/details/gtntlypsih.html

[T47] Perl：正则捕获
来源：http://dali.jqgufenzy.top/Article/details/gtrurbtzic.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jyoumei.cn/Article/details/gtlsnlpoxq.html

[T48] Perl：正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtflhofidq.html

$s =~ s/old/new/g;
来源：http://dali.redwolf501.top/Article/details/gtojqyijyv.html

[T49] Perl：函数
来源：http://dali.guannengcc.top/Article/details/gtoyrlrxhz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtswlalmsr.html

[T50] Perl：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtmshikxvy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.bjfxy.top/Article/details/gtjnsmfomt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gotoacloud.top/Article/details/gtnekbmbcv.html

[T51] Scala：Hello World
来源：http://dali.andypj.xyz/Article/details/gtkgvkgnjk.html

println("Hello")
来源：http://dali.wangdashe.top/Article/details/gtdatylgzn.html

[T52] Scala：变量
来源：http://dali.sweek.top/Article/details/gtzkbanoih.html

val a = 1;  var b = 2
来源：http://dali.hnxiangtu.top/Article/details/gtmsxgfxue.html

[T53] Scala：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtrdghubic.html

s"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gtlclnkuov.html

[T54] Scala：集合映射
来源：http://dali.tanke756.top/Article/details/gtaxfduncw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtxmdfhoym.html

[T55] Scala：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gtcbnpqyjq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nwbrower.top/Article/details/gtoaeezsvu.html

[T56] Scala：样例类
来源：http://dali.daxiang520.top/Article/details/gtdabnisrz.html

case class User(name: String, age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gtijqwhflg.html

[T57] Scala：模式匹配
来源：http://dali.fzhhl.top/Article/details/gtkffcbpfh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cashguo.top/Article/details/gtfewerqna.html

[T58] Scala：函数定义
来源：http://dali.wangdashe.top/Article/details/gtdxpinqur.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.smart0.xyz/Article/details/gttcesfuub.html

[T59] Scala：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzjgwrga.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtheecxawe.html

[T60] Scala：折叠
来源：http://dali.vqdsnc.cn/Article/details/gtctzbxipr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hongshengwenyu.top/Article/details/gtkcddtqgr.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdmjxfjfc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gtgsgkbvuu.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtihcvgkof.html

[U01] Py：创建虚拟环境
来源：http://dali.xinyue.icu/Article/details/gtjdttygfd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guannengcc.top/Article/details/gtemqyyvlf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.feifeiyinyue.top/Article/details/gtsmkekqzl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgufenzy.top/Article/details/gtsizonnfr.html

[U03] Py：加载 .env 配置
来源：http://dali.jyoumei.cn/Article/details/gteikmioyr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.wangshuangyany.cn/Article/details/gtwgozblvo.html

[U04] Py：变量调试打印
来源：http://dali.haohaochexian.top/Article/details/gtzgvfhtdr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.kuanghao11.cn/Article/details/gtissqxjng.html

[U05] Py：列表去重且保序
来源：http://dali.0kj1m.cn/Article/details/gtbbpkrsfy.html

list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gtzesvsqhu.html

[U06] Py：合并两个字典
来源：http://dali.yj202588.top/Article/details/gtsjqpajaj.html

{**a, **b}
来源：http://dali.shangyingyoupin.top/Article/details/gtgipytxor.html

[U07] Py：反转字典键值
来源：http://dali.fzhhl.top/Article/details/gtptrqoweh.html

{v: k for k, v in d.items()}
来源：http://dali.yanxiufei.cn/Article/details/gtofaptydq.html

[U08] Py：展平二维列表
来源：http://dali.yj20258888.top/Article/details/gtawibdpre.html

[y for x in nested for y in x]
来源：http://dali.nanxinkj.top/Article/details/gtnlpvciua.html

[U09] Py：字典取最大值的键
来源：http://dali.tian-w.cn/Article/details/gtlmsdjhet.html

max(d, key=d.get)
来源：http://dali.sysykeji.top/Article/details/gtrgyclbme.html

[U10] Py：按值排序字典
来源：http://dali.xinyue.icu/Article/details/gtfflpmbxt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cheryme.top/Article/details/gtsvdkpjts.html

[U11] Py：生成器表达式
来源：http://dali.kuanghao11.cn/Article/details/gtetfxwdgh.html

(x * 2 for x in arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmbcvsjj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.316326.xyz/Article/details/gtvvugetbl.html

Counter(arr).most_common(3)
来源：http://dali.tian-w.cn/Article/details/gtphjmlfgl.html

[U13] Py：固定长度队列
来源：http://dali.9152youxi.cn/Article/details/gtsugctivu.html

deque(maxlen=10)
来源：http://dali.jqgfzy.top/Article/details/gtmrhckvgk.html

[U14] Py：分组收集到列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfbbmxdf.html

defaultdict(list)
来源：http://dali.jianghu66.top/Article/details/gtrsguazpi.html

[U15] Py：高精度计时
来源：http://dali.cashguo.top/Article/details/gtsaezosiz.html

t = time.perf_counter()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrdzdlqx.html

[U16] Py：命令行参数解析
来源：http://dali.xuanzx.com/Article/details/gtqzorpxfv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.quarkkingdee.top/Article/details/gtxsuotqot.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxldkffz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cucudq.cn/Article/details/gtzrregrry.html

[U18] Py：预编译正则
来源：http://dali.jlsjyb.cn/Article/details/gtcibxwfzo.html

pat = re.compile(r"\d+")
来源：http://dali.ppjwa.cn/Article/details/gtskkiogls.html

[U19] Py：正则替换带回调
来源：http://dali.xinyue.icu/Article/details/gtgzaczslt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdiuinzsx.html

[U20] Py：缓存函数结果
来源：http://dali.ppjwa.cn/Article/details/gtrjheznzu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ydzc1.top/Article/details/gtdcaixhrq.html

[U21] Py：自定义上下文管理器
来源：http://dali.yuanzhike.top/Article/details/gtwtznperq.html

@contextlib.contextmanager
来源：http://dali.nanxuanxn.top/Article/details/gtmoentokx.html

[U22] Py：矩阵转置
来源：http://dali.cheryme.top/Article/details/gtqmblcxoq.html

list(zip(*m))
来源：http://dali.quarkkingdee.top/Article/details/gtyrlkhinw.html

[U23] Py：分块读取大文件
来源：http://dali.feifeiyinyue.top/Article/details/gtcuazvnsf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sxryk.cn/Article/details/gtezcyiiqc.html

[U24] Py：路径操作
来源：http://dali.tian-w.cn/Article/details/gtizsedzut.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gtvboclccc.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gtufeqrsmy.html

csv.DictReader(f)
来源：http://dali.zhengqikj.top/Article/details/gtsrjpojhr.html

[U26] Py：并发下载
来源：http://dali.9152youxi.cn/Article/details/gtxamzoorr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hnxiangtu.top/Article/details/gtqcoqrslx.html

[U27] Py：异步 HTTP
来源：http://dali.fengsongda.top/Article/details/gtbsfyjpwu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xuetiantiany.cn/Article/details/gtpksycbpy.html

[U28] Py：类型别名
来源：http://dali.jinqigufen.top/Article/details/gtfwpivtli.html

UserId = int
来源：http://dali.chenlongwang.top/Article/details/gtqfpxjscn.html

[U29] Py：属性校验
来源：http://dali.wangshuangyany.cn/Article/details/gtgqtqrwyh.html

@property 与 @x.setter 配合
来源：http://dali.wangdashe.top/Article/details/gtlifqanyq.html

[U30] Py：数据类
来源：http://dali.jyoumei.cn/Article/details/gtyieyglfu.html

@dataclass(slots=True)
来源：http://dali.sysykeji.top/Article/details/gtabdzkwre.html

[U31] Py：单测
来源：http://dali.9152youxi.cn/Article/details/gtfucndomj.html

python -m pytest -q
来源：http://dali.yuanzhike.top/Article/details/gtsaeixpyk.html

[U32] Py：代码格式化
来源：http://dali.hnxiangtu.top/Article/details/gthvnyuydi.html

ruff format . && ruff check --fix .
来源：http://dali.wangshuangyany.cn/Article/details/gtyxfpmljx.html

[U33] Py：打包发布
来源：http://dali.kuanghao11.cn/Article/details/gteqrhodsx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shzxlz.cn/Article/details/gtxvtbgpxv.html

[U34] Py：判断编码
来源：http://dali.cucudq.cn/Article/details/gtopkyamrc.html

chardet.detect(raw)
来源：http://dali.bjfxy.top/Article/details/gtnubvzwac.html

[U35] Py：发送邮件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecbwitfj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.wangshuangyany.cn/Article/details/gtiqcroyvw.html

[U36] Py：定时任务
来源：http://dali.birdmap.top/Article/details/gtevhxxbvi.html

schedule.every(10).minutes.do(job)
来源：http://dali.tian-w.cn/Article/details/gtvwnhencb.html


<!-- 参考信息 -->