代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zycfv.cn/Article/details/gtxytfczzp.html

[S10] C：指针与解引用
来源：http://dali.daria6918.cn/Article/details/gtsmrszzje.html

int *p = &a;  *p = 5;
来源：http://dali.wangdashe.top/Article/details/gtwhohwfgv.html

[S11] C：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtpxbthnnc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.smart0.xyz/Article/details/gtpcmbqjkj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sweek.top/Article/details/gtbvtedwoy.html

fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gtigrotijn.html

[S12] C：写文件
来源：http://dali.aibaodan.cn/Article/details/gtjffdhypl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gtaahrfwpk.html

[S13] C：宏定义
来源：http://dali.jqgfzy.top/Article/details/gtidldioog.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ivvv.top/Article/details/gtpktefoot.html

[S14] C：枚举
来源：http://dali.zhoulong.xyz/Article/details/gtnrujukfw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guowangkeji.top/Article/details/gtemswmkyt.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzlcrwegx.html

(double) a / b
来源：http://dali.daria6918.cn/Article/details/gtgwrokfwg.html

[S16] C：位操作置位
来源：http://dali.kuanghao11.cn/Article/details/gthbwbrfon.html

x |= (1 << 3);
来源：http://dali.daria6918.cn/Article/details/gtabxcelwp.html

[S17] C：安全拼接字符串
来源：http://dali.daxiang520.top/Article/details/gtamkzgekf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigfzy.top/Article/details/gtogzxwvno.html

[S18] C：命令行参数
来源：http://dali.wangdashe.top/Article/details/gtdwauqgjm.html

int main(int argc, char **argv)
来源：http://dali.chenlongwang.top/Article/details/gtmsqwhbdf.html

[S19] C：快速排序
来源：http://dali.guannengcc.top/Article/details/gtiesnhkdr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtfxqkffho.html

[S20] C：二分查找
来源：http://dali.dianchejie.cn/Article/details/gtigohbdxl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtkakjbkal.html

[S21] C：字符类别判断
来源：http://dali.yonumen.top/Article/details/gtzlzwbqnp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tanke756.top/Article/details/gtdpmdoxyp.html

[S22] C：字符串转数字
来源：http://dali.fzhhl.top/Article/details/gthqlphtig.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.svipenyu.cn/Article/details/gtjtqhllvt.html

[S23] C：随机数
来源：http://dali.ehwqpu.com/Article/details/gtsqcozddk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhiwuduotai.top/Article/details/gtaiyskvvz.html

[S24] C：获取本地时间
来源：http://dali.cucudq.cn/Article/details/gtzdswawzl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckxqpltu.html

[S25] C：内存拷贝
来源：http://dali.yueranfly.top/Article/details/gtgocinmuw.html

memcpy(dst, src, n);
来源：http://dali.meibo888.top/Article/details/gtqtunrbdy.html

[S26] C：内存清零
来源：http://dali.sufxvd.cn/Article/details/gtgppcvjih.html

memset(a, 0, sizeof a);
来源：http://dali.shuidangran.top/Article/details/gtxyqhtxpg.html

[S27] C：定义常量
来源：http://dali.zdqjudy.top/Article/details/gtqaggnlxx.html

const double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtdafqpkar.html

[S28] C：静态变量
来源：http://dali.shzxlz.cn/Article/details/gtwyuisckj.html

static int counter = 0;
来源：http://dali.havefunace.top/Article/details/gtjslxgtdc.html

[S29] C：变参函数
来源：http://dali.xuanzx.com/Article/details/gtlihaxclp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.c1oappe.top/Article/details/gtrhmmgcgs.html

[S30] C：头文件保护
来源：http://dali.yongpay.top/Article/details/gtsumldeqt.html

#ifndef X_H
来源：http://dali.daria6918.cn/Article/details/gtdmtvvvhh.html

#define X_H
来源：http://dali.hnqzz.top/Article/details/gtufwovclp.html

#endif
来源：http://dali.xziqi.cn/Article/details/gtntlvwebm.html

[S31] C++：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtnkanzmzi.html

#include <iostream>
来源：http://dali.mhx1999.top/Article/details/gtvaegoqza.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cheryme.top/Article/details/gthpjjctax.html

[S32] C++：字符串
来源：http://dali.yongpay.top/Article/details/gtmsxaqnxj.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigufen.top/Article/details/gtjnkxhcym.html

[S33] C++：vector 增删
来源：http://dali.shzxlz.cn/Article/details/gtdrerkqeg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.snrcjt.cn/Article/details/gtpbjpwrrq.html

[S34] C++：遍历 vector
来源：http://dali.hnqzz.top/Article/details/gtagbmafbk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tian-w.cn/Article/details/gttfzsqnyh.html

[S35] C++：map
来源：http://dali.dianchejie.cn/Article/details/gtuyyvbykw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaraxyhkw.html

[S36] C++：unordered_map
来源：http://dali.jinqigufen.top/Article/details/gthrpptdwz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gtdtwoqgqh.html

[S37] C++：set
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrsqjzvv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shzxlz.cn/Article/details/gthnodvfpu.html

[S38] C++：排序
来源：http://dali.yuanzhike.top/Article/details/gtfclyusgv.html

std::sort(v.begin(), v.end());
来源：http://dali.birdmap.top/Article/details/gtcbzucqpl.html

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfuleuag.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yonumen.top/Article/details/gtukwgyjeg.html

[S40] C++：查找元素
来源：http://dali.316326.xyz/Article/details/gtdeftayvy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gogol.net.cn/Article/details/gtsuktrygg.html

[S41] C++：类与构造函数
来源：http://dali.guannengcc.top/Article/details/gtfbrjwerr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cheryme.top/Article/details/gtlbmqgiob.html

[S42] C++：继承与虚函数
来源：http://dali.ppjwa.cn/Article/details/gtdlttucsu.html

class B : public Base { public: void f() override {} };
来源：http://dali.aibaodan.cn/Article/details/gtivlgisnl.html

[S43] C++：智能指针
来源：http://dali.yj20258.top/Article/details/gtiujvjrzj.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuanzhike.top/Article/details/gtjsvuvwns.html

[S44] C++：引用传参
来源：http://dali.sweek.top/Article/details/gtgkfbcguo.html

void inc(int &x) { ++x; }
来源：http://dali.haohaochexian.top/Article/details/gtzmsrqbiy.html

[S45] C++：lambda
来源：http://dali.gogol.net.cn/Article/details/gtymrsunqi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigfzy.top/Article/details/gtalngdeos.html

[S46] C++：函数模板
来源：http://dali.shuidangran.top/Article/details/gtozofgekc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hnqzz.top/Article/details/gtyctjaeor.html

[S47] C++：结构化绑定遍历
来源：http://dali.hammf.cn/Article/details/gtiiukhtxi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.haohaochexian.top/Article/details/gtilhwozpz.html

[S48] C++：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtflofipvp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ivvv.top/Article/details/gtbszsxbws.html

while (std::getline(in, line)) { }
来源：http://dali.haohaochexian.top/Article/details/gtjftwjzdt.html

[S49] C++：写文件
来源：http://dali.yueranfly.top/Article/details/gtpjaeymwp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gtpsjbnwru.html

[S50] C++：格式化数字
来源：http://dali.pycfn.com/Article/details/gtrmlzvfwo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtdkgjgmzi.html

[S51] C++：显式类型转换
来源：http://dali.zhengqikj.top/Article/details/gtyvqcaxkm.html

static_cast<double>(a) / b
来源：http://dali.havefunace.top/Article/details/gtdfutgnnm.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gttkhnqroc.html

int size() const noexcept { return n_; }
来源：http://dali.quarkkingdee.top/Article/details/gtdylwnasa.html

[S53] C++：移动语义
来源：http://dali.jlsjyb.cn/Article/details/gtgoqimbty.html

std::vector<int> w = std::move(v);
来源：http://dali.xuanzx.com/Article/details/gtrjdkkzyf.html

[S54] C++：异常处理
来源：http://dali.cheryme.top/Article/details/gtbbsupuar.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkomgbfji.html

[S55] C++：结构化绑定
来源：http://dali.jiagoushi.top/Article/details/gtkgnedzgu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fengsongda.top/Article/details/gtnapwarkj.html

[S56] C++：optional
来源：http://dali.hysaishi.cn/Article/details/gtkycpptjg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gtvgyzvwmr.html

[S57] C++：编译期常量
来源：http://dali.shangyingyoupin.top/Article/details/gtdyfvqtdy.html

constexpr int N = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gthtwyvbii.html

[S58] C++：命名空间
来源：http://dali.haohaochexian.top/Article/details/gtcamodylu.html

namespace ns { int f() { return 1; } }
来源：http://dali.yongpay.top/Article/details/gtvlmrdigz.html

[S59] C++：静态断言
来源：http://dali.chenzaomai.com/Article/details/gtrosgqbjy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.aibaodan.cn/Article/details/gtqkobdceg.html

[S60] C++：遍历并删除元素
来源：http://dali.fengsongda.top/Article/details/gtbscszved.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jiagoushi.top/Article/details/gtibbwxscb.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtymfnewpj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gttmvyuvdj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtyfusvqqd.html

[T01] Kotlin：Hello World
来源：http://dali.ivvv.top/Article/details/gtopuegleu.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gtzakrapxr.html

[T02] Kotlin：变量
来源：http://dali.wangshuangyany.cn/Article/details/gtuzmcbszd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guowangkeji.top/Article/details/gtggtmmpra.html

[T03] Kotlin：字符串模板
来源：http://dali.xuanzx.com/Article/details/gtzrjhncka.html

"值: $b"
来源：http://dali.xuanzx.com/Article/details/gttvcyduqg.html

[T04] Kotlin：空安全
来源：http://dali.316326.xyz/Article/details/gtvilnjpmd.html

val n: String? = null;  n?.length
来源：http://dali.hysaishi.cn/Article/details/gtxvdcwpme.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtnaeozasz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuanzx.com/Article/details/gtgdgfjdvq.html

[T06] Kotlin：集合映射
来源：http://dali.yj202588.top/Article/details/gtvanzpbxf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtswgfzwza.html

[T07] Kotlin：集合过滤
来源：http://dali.ybcxt.top/Article/details/gtjricifcx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhixingplan.top/Article/details/gtnpswgbnr.html

[T08] Kotlin：数据类
来源：http://dali.yanxiufei.cn/Article/details/gtxljoddkq.html

data class User(val name: String, val age: Int)
来源：http://dali.0kj1m.cn/Article/details/gtceqnbjzq.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gtqrruaesv.html

fun String.exclaim() = this + "!"
来源：http://dali.haohaochexian.top/Article/details/gtfsvbbkpr.html

[T10] Kotlin：默认参数
来源：http://dali.zycfv.cn/Article/details/gtqrksjhco.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqtsaeyy.html

[T11] Kotlin：协程
来源：http://dali.iojbl.cn/Article/details/gtitoyyhsb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gtdehcbjft.html

[T12] Kotlin：解构声明
来源：http://dali.sufxvd.cn/Article/details/gtegjnhygu.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtgkpfphyl.html

[T13] Kotlin：只读 Map
来源：http://dali.aibaodan.cn/Article/details/gtgfquauyk.html

val m = mapOf("a" to 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtmlbxbakd.html

[T14] Kotlin：循环
来源：http://dali.birdmap.top/Article/details/gtwhwzlzeu.html

for (i in 1..10) println(i)
来源：http://dali.hongshengwenyu.top/Article/details/gtwczintzn.html

[T15] Kotlin：接口
来源：http://dali.9152youxi.cn/Article/details/gtbjmakaic.html

interface Shape { fun area(): Double }
来源：http://dali.zhengqikj.top/Article/details/gtheakgftw.html

[T16] Swift：Hello World
来源：http://dali.0kj1m.cn/Article/details/gthvptscky.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtmklqbtkv.html

[T17] Swift：变量与常量
来源：http://dali.zhixingplan.top/Article/details/gtjqzeexim.html

var a = 1;  let b = 2
来源：http://dali.zhixingplan.top/Article/details/gtqtwlrpzg.html

[T18] Swift：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtmzamxleu.html

"值: \(b)"
来源：http://dali.0kj1m.cn/Article/details/gtiqbnolfy.html

[T19] Swift：可选绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtxrahzffm.html

if let n = opt { print(n) }
来源：http://dali.fengsongda.top/Article/details/gtxvbtwrid.html

[T20] Swift：数组操作
来源：http://dali.tanke756.top/Article/details/gtauqqhdsw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hfpthk.cn/Article/details/gtnflxzlts.html

[T21] Swift：遍历
来源：http://dali.hnqzz.top/Article/details/gttjhqpghh.html

for x in a { print(x) }
来源：http://dali.yangfankeji.com/Article/details/gtyxgisuxq.html

[T22] Swift：字典
来源：http://dali.ppjwa.cn/Article/details/gteffrpbcg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtcaqsztxr.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gthgdvwehk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gthmrwdnwm.html

[T24] Swift：闭包
来源：http://dali.ydzc1.top/Article/details/gtushmdqjj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtxgjpffav.html

[T25] Swift：结构体
来源：http://dali.jiagoushi.top/Article/details/gtxsvdmzgr.html

struct P { var x: Int }
来源：http://dali.guannengcc.top/Article/details/gtsjejeysr.html

[T26] Swift：类与重写
来源：http://dali.316326.xyz/Article/details/gtdomudfzk.html

class A: Base { override func f() {} }
来源：http://dali.chenlongwang.top/Article/details/gtkqcdlvoc.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gtmdeflunu.html

do { try f() } catch { print(error) }
来源：http://dali.sweek.top/Article/details/gtsyfbuqkk.html

[T28] Swift：枚举
来源：http://dali.tianlin.xyz/Article/details/gtzfageouf.html

enum Color { case red, green }
来源：http://dali.aizwys.cn/Article/details/gtsnjzairc.html

[T29] Swift：guard 提前返回
来源：http://dali.zycfv.cn/Article/details/gtsyjrujvk.html

guard let x = opt else { return }
来源：http://dali.ehwqpu.com/Article/details/gticksceqq.html

[T30] Swift：协议
来源：http://dali.nwbrower.top/Article/details/gthxjuoudj.html

protocol Shape { func area() -> Double }
来源：http://dali.vqdsnc.cn/Article/details/gtdypzfacd.html

[T31] Lua：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtpbwafglm.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gttksgayvo.html

[T32] Lua：局部变量
来源：http://dali.yuxming.cn/Article/details/gtgjqfhaqp.html

local a = 1
来源：http://dali.fengsongda.top/Article/details/gtrfkvvhbe.html

[T33] Lua：表（数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gtorsfdkis.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xziqi.cn/Article/details/gteabfbmuz.html

[T34] Lua：遍历表
来源：http://dali.guannengcc.top/Article/details/gtabtkwyva.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pengpengdd.cyou/Article/details/gtxuzjsdwc.html

[T35] Lua：字典表
来源：http://dali.ppjwa.cn/Article/details/gttxugwdqt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigufen.top/Article/details/gtzmtkofjc.html

[T36] Lua：函数
来源：http://dali.gzhubu.top/Article/details/gtiapsxcpy.html

function add(a, b) return a + b end
来源：http://dali.hywenlv.cn/Article/details/gtwdccbsqv.html

[T37] Lua：字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gteoavkjvq.html

"a" .. "b"
来源：http://dali.zhixingplan.top/Article/details/gtrxbhsrqh.html

[T38] Lua：条件
来源：http://dali.guannengcc.top/Article/details/gtboyvdjji.html

if x > 0 then print("正") end
来源：http://dali.hysaishi.cn/Article/details/gtloxlhqki.html

[T39] Lua：模式匹配
来源：http://dali.daria6918.cn/Article/details/gtztcpguvo.html

string.find(s, "%d+")
来源：http://dali.nwbrower.top/Article/details/gtelyfljxu.html

[T40] Lua：元表
来源：http://dali.nanxuanxn.top/Article/details/gtmtahmudw.html

setmetatable({}, { __index = base })
来源：http://dali.xziqi.cn/Article/details/gtwlpvahwu.html

[T41] Perl：Hello World
来源：http://dali.cucudq.cn/Article/details/gtcpbvhhfp.html

print "Hello\n";
来源：http://dali.hnxiangtu.top/Article/details/gtqyriqnzb.html

[T42] Perl：变量类型
来源：http://dali.hfpthk.cn/Article/details/gtyyvkawjq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gotoacloud.top/Article/details/gtkatsofzr.html

[T43] Perl：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtucjwyvum.html

"值: $a"
来源：http://dali.aizwys.cn/Article/details/gtayzybteb.html

[T44] Perl：条件
来源：http://dali.zhixingplan.top/Article/details/gthfceffbt.html

if ($a > 0) { print "正"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzvirwuiu.html

[T45] Perl：数组遍历
来源：http://dali.chenzaomai.com/Article/details/gtpwadwyzw.html

for my $x (@arr) { print $x; }
来源：http://dali.yangfankeji.com/Article/details/gtnvbcgitr.html

[T46] Perl：哈希操作
来源：http://dali.yanxiufei.cn/Article/details/gtzcebkpej.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aibaodan.cn/Article/details/gtieuwhhwy.html

[T47] Perl：正则捕获
来源：http://dali.cucudq.cn/Article/details/gtjddillqo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.meibo888.top/Article/details/gtbcyxjxrw.html

[T48] Perl：正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gtebayevds.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqgdpzzz.html

[T49] Perl：函数
来源：http://dali.c1oappe.top/Article/details/gtmezjhquo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtmqzoljww.html

[T50] Perl：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtkovlyfwh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbovuskd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tanke756.top/Article/details/gtctijqsfv.html

[T51] Scala：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtadnrqshk.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gtaesldrev.html

[T52] Scala：变量
来源：http://dali.zhiwuduotai.top/Article/details/gtnptfomje.html

val a = 1;  var b = 2
来源：http://dali.ydzc1.top/Article/details/gtthtyrmei.html

[T53] Scala：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gttzjdmtqa.html

s"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gtktcsceoy.html

[T54] Scala：集合映射
来源：http://dali.dashuyun.cn/Article/details/gtnzucmohi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cashguo.top/Article/details/gtbpvnylrx.html

[T55] Scala：集合过滤
来源：http://dali.tanke756.top/Article/details/gtfhohxnvk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hammf.cn/Article/details/gtiefjuhuw.html

[T56] Scala：样例类
来源：http://dali.zhongyouzk.top/Article/details/gtuqgyrsdz.html

case class User(name: String, age: Int)
来源：http://dali.redwolf501.top/Article/details/gtzkngkctc.html

[T57] Scala：模式匹配
来源：http://dali.zhengqikj.top/Article/details/gtovctvdsv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenlongwang.top/Article/details/gtavntiwsu.html

[T58] Scala：函数定义
来源：http://dali.yj202588.top/Article/details/gtvkvwqmay.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.meibo888.top/Article/details/gtsuwtyazs.html

[T59] Scala：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyklltcfz.html

for (i <- 1 to 10) println(i)
来源：http://dali.wangdashe.top/Article/details/gtqwpdzhuw.html

[T60] Scala：折叠
来源：http://dali.kuanghao11.cn/Article/details/gtdlzpjtfj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenlongwang.top/Article/details/gtcoqnniec.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtftjaubsg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtnhlcyemj.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtfvtoejmv.html

[U01] Py：创建虚拟环境
来源：http://dali.feifeiyinyue.top/Article/details/gtjpcbmywk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangdashe.top/Article/details/gtbfdlkxki.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hysaishi.cn/Article/details/gtmndlpcdu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tian-w.cn/Article/details/gtyohjmoil.html

[U03] Py：加载 .env 配置
来源：http://dali.redwolf501.top/Article/details/gtqpqarzot.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xylfe.cn/Article/details/gtyaexhcpw.html

[U04] Py：变量调试打印
来源：http://dali.yj20258888.top/Article/details/gtmfrjjccc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.birdmap.top/Article/details/gtaulrnmht.html

[U05] Py：列表去重且保序
来源：http://dali.xylfe.cn/Article/details/gtudbejtqs.html

list(dict.fromkeys(arr))
来源：http://dali.xziqi.cn/Article/details/gtmzhlxufv.html

[U06] Py：合并两个字典
来源：http://dali.jianghu66.top/Article/details/gtbevmnihk.html

{**a, **b}
来源：http://dali.chenzaomai.com/Article/details/gtwrqvpruw.html

[U07] Py：反转字典键值
来源：http://dali.yj20258888.top/Article/details/gtcndhktja.html

{v: k for k, v in d.items()}
来源：http://dali.hnxiangtu.top/Article/details/gtygcdepwr.html

[U08] Py：展平二维列表
来源：http://dali.ybcxt.top/Article/details/gtvvianqmt.html

[y for x in nested for y in x]
来源：http://dali.yj202588.top/Article/details/gtuxoedngf.html

[U09] Py：字典取最大值的键
来源：http://dali.fzhhl.top/Article/details/gtrlakkllz.html

max(d, key=d.get)
来源：http://dali.daria6918.cn/Article/details/gtydsrioif.html

[U10] Py：按值排序字典
来源：http://dali.guowangkeji.top/Article/details/gtpelhhqwv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hnqzz.top/Article/details/gtiomtgtgw.html

[U11] Py：生成器表达式
来源：http://dali.nwbrower.top/Article/details/gtcjmywlfo.html

(x * 2 for x in arr)
来源：http://dali.ybcxt.top/Article/details/gtidhavweg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.daxiang520.top/Article/details/gtkcfltnhq.html

Counter(arr).most_common(3)
来源：http://dali.yj20258.top/Article/details/gtwbhddjgo.html

[U13] Py：固定长度队列
来源：http://dali.smart0.xyz/Article/details/gtdkthbxzd.html

deque(maxlen=10)
来源：http://dali.zdqjudy.top/Article/details/gtxlezpfis.html

[U14] Py：分组收集到列表
来源：http://dali.guannengcc.top/Article/details/gtnetqohhg.html

defaultdict(list)
来源：http://dali.dashuyun.cn/Article/details/gtgtyxdcaw.html

[U15] Py：高精度计时
来源：http://dali.jinqigfzy.top/Article/details/gtwmdrquby.html

t = time.perf_counter()
来源：http://dali.zhengqikj.top/Article/details/gtlerqdvvx.html

[U16] Py：命令行参数解析
来源：http://dali.yueranfly.top/Article/details/gtorbvbhkx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cqqwz.cn/Article/details/gtoezbdern.html

[U17] Py：初始化日志
来源：http://dali.yuxming.cn/Article/details/gteoqsicfv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.iojbl.cn/Article/details/gtydvbabru.html

[U18] Py：预编译正则
来源：http://dali.hammf.cn/Article/details/gtnidoihmf.html

pat = re.compile(r"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtuemyjzat.html

[U19] Py：正则替换带回调
来源：http://dali.jqgfzy.top/Article/details/gtfnctqpsf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xziqi.cn/Article/details/gtmofdtltp.html

[U20] Py：缓存函数结果
来源：http://dali.hnqzz.top/Article/details/gtpobzmhql.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbixvkoj.html

[U21] Py：自定义上下文管理器
来源：http://dali.sxryk.cn/Article/details/gtwavnrykp.html

@contextlib.contextmanager
来源：http://dali.sxryk.cn/Article/details/gtfgugcjsp.html

[U22] Py：矩阵转置
来源：http://dali.cqqwz.cn/Article/details/gtrrperjns.html

list(zip(*m))
来源：http://dali.jqgfzy.top/Article/details/gtpvjlpcxy.html

[U23] Py：分块读取大文件
来源：http://dali.cucudq.cn/Article/details/gtgegiaokd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sufxvd.cn/Article/details/gtsphfozcq.html

[U24] Py：路径操作
来源：http://dali.0kj1m.cn/Article/details/gtjkenkfry.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gtytnxvivv.html

[U25] Py：CSV 按字典读
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvtuhqyj.html

csv.DictReader(f)
来源：http://dali.hywenlv.cn/Article/details/gtjmgdxzgo.html

[U26] Py：并发下载
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgnotrdd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbkgxxju.html

[U27] Py：异步 HTTP
来源：http://dali.c1oappe.top/Article/details/gtlmhfndiy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sufxvd.cn/Article/details/gtjinoxeuq.html

[U28] Py：类型别名
来源：http://dali.haohaochexian.top/Article/details/gtycuglsnh.html

UserId = int
来源：http://dali.jiagoushi.top/Article/details/gtzzsbwdsp.html

[U29] Py：属性校验
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwrnojvm.html

@property 与 @x.setter 配合
来源：http://dali.zhoulong.xyz/Article/details/gtmmkbngzn.html

[U30] Py：数据类
来源：http://dali.haohaochexian.top/Article/details/gtczwkjmxa.html

@dataclass(slots=True)
来源：http://dali.zhengqikj.top/Article/details/gthdyywgnb.html

[U31] Py：单测
来源：http://dali.pycfn.com/Article/details/gthaahytgf.html

python -m pytest -q
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagwksamd.html

[U32] Py：代码格式化
来源：http://dali.yueranfly.top/Article/details/gtunemqmnw.html

ruff format . && ruff check --fix .
来源：http://dali.yj202588.top/Article/details/gtwcmhfllt.html


<!-- 参考信息 -->