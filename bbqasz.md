代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gtjgceyasj.html

[S13] C：宏定义
来源：http://dali.yonumen.top/Article/details/gtesnhlgqj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgfzy.top/Article/details/gtsfgdupfe.html

[S14] C：枚举
来源：http://dali.ppjwa.cn/Article/details/gtcxbnaqhz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xinyue.icu/Article/details/gteofbrswh.html

[S15] C：类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtkcgzbgwt.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gtncbmaptr.html

[S16] C：位操作置位
来源：http://dali.yuanzhike.top/Article/details/gtdzufrfnw.html

x |= (1 << 3);
来源：http://dali.iojbl.cn/Article/details/gtzfoxyatt.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtbblaufmx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gtuzjapwhj.html

[S18] C：命令行参数
来源：http://dali.ehwqpu.com/Article/details/gtfmofxvjh.html

int main(int argc, char **argv)
来源：http://dali.svipenyu.cn/Article/details/gtuvkhmzza.html

[S19] C：快速排序
来源：http://dali.fengsongda.top/Article/details/gtcbgpwspv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gttkluwfoc.html

[S20] C：二分查找
来源：http://dali.pengpengdd.cyou/Article/details/gtwpbwhydg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gthymqyuvf.html

[S21] C：字符类别判断
来源：http://dali.ppjwa.cn/Article/details/gtibwmcgde.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daxiang520.top/Article/details/gtoaqbhimo.html

[S22] C：字符串转数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjiwomfds.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhixingplan.top/Article/details/gtbpmgepbd.html

[S23] C：随机数
来源：http://dali.dianchejie.cn/Article/details/gtgpenrgef.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.feifeiyinyue.top/Article/details/gtgvbbjnlo.html

[S24] C：获取本地时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwilwrvi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yangfankeji.com/Article/details/gtmddxndlz.html

[S25] C：内存拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gteotxgbga.html

memcpy(dst, src, n);
来源：http://dali.jqgufenzy.top/Article/details/gtygdgxnnj.html

[S26] C：内存清零
来源：http://dali.ydzc1.top/Article/details/gtdwvwvvky.html

memset(a, 0, sizeof a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvxlxnlz.html

[S27] C：定义常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtncqjpyhz.html

const double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtasxevxxa.html

[S28] C：静态变量
来源：http://dali.xylfe.cn/Article/details/gtlhbufimc.html

static int counter = 0;
来源：http://dali.shzxlz.cn/Article/details/gtxtgsdljv.html

[S29] C：变参函数
来源：http://dali.tianlin.xyz/Article/details/gtsuqntufu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.9152youxi.cn/Article/details/gtvdjlrutp.html

[S30] C：头文件保护
来源：http://dali.nanxuanxn.top/Article/details/gtzpzvddav.html

#ifndef X_H
来源：http://dali.jinqigufen.top/Article/details/gthngpefzn.html

#define X_H
来源：http://dali.yvedp.cn/Article/details/gtlpgfinji.html

#endif
来源：http://dali.snrcjt.cn/Article/details/gtixecmzao.html

[S31] C++：Hello World
来源：http://dali.wangdashe.top/Article/details/gtxzdsmzss.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gtvmdvufgq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.havefunace.top/Article/details/gtdougrmui.html

[S32] C++：字符串
来源：http://dali.yj202588.top/Article/details/gtgfohafhf.html

std::string s = "hi";  s += "!";
来源：http://dali.cheryme.top/Article/details/gthmiigjgb.html

[S33] C++：vector 增删
来源：http://dali.chenjidiqi.icu/Article/details/gteedtzxqw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuanzhike.top/Article/details/gtjjhlnhht.html

[S34] C++：遍历 vector
来源：http://dali.haohaochexian.top/Article/details/gtpbmiprnf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cucudq.cn/Article/details/gtjzmvkpjv.html

[S35] C++：map
来源：http://dali.jqgfzy.top/Article/details/gtkpedlzdz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gtcgimlhyl.html

[S36] C++：unordered_map
来源：http://dali.xziqi.cn/Article/details/gtzwhyyida.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtdjvjkelt.html

[S37] C++：set
来源：http://dali.feifeiyinyue.top/Article/details/gtiridjtvr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenzaomai.com/Article/details/gtypcznsrd.html

[S38] C++：排序
来源：http://dali.chenlongwang.top/Article/details/gtfpxefsau.html

std::sort(v.begin(), v.end());
来源：http://dali.sysykeji.top/Article/details/gtgfhadwzj.html

[S39] C++：自定义比较器排序
来源：http://dali.hywenlv.cn/Article/details/gtfycveiim.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daria6918.cn/Article/details/gtzerdewug.html

[S40] C++：查找元素
来源：http://dali.vqdsnc.cn/Article/details/gtgxzxnwqh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenzaomai.com/Article/details/gtisdyglet.html

[S41] C++：类与构造函数
来源：http://dali.jiagoushi.top/Article/details/gtsrfjiozt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.9152youxi.cn/Article/details/gtebcekvff.html

[S42] C++：继承与虚函数
来源：http://dali.vqdsnc.cn/Article/details/gtiycoctkw.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj202588.top/Article/details/gtgmjhamaj.html

[S43] C++：智能指针
来源：http://dali.zycfv.cn/Article/details/gtfmaehjsz.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfatmdgcy.html

[S44] C++：引用传参
来源：http://dali.chenzaomai.com/Article/details/gtvlbmggyf.html

void inc(int &x) { ++x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibpcaixt.html

[S45] C++：lambda
来源：http://dali.cheryme.top/Article/details/gtsyowstsg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj202588.top/Article/details/gttgtbjniq.html

[S46] C++：函数模板
来源：http://dali.hongshengwenyu.top/Article/details/gtbgdfrwyy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shuidangran.top/Article/details/gtabunycxb.html

[S47] C++：结构化绑定遍历
来源：http://dali.hywenlv.cn/Article/details/gtpvosyflw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gotoacloud.top/Article/details/gtztnvswbm.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnhzufcf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gaohongyu789.top/Article/details/gtilqxdeht.html

while (std::getline(in, line)) { }
来源：http://dali.xinyue.icu/Article/details/gtskqiqlgv.html

[S49] C++：写文件
来源：http://dali.zycfv.cn/Article/details/gtvgwtdsba.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cheryme.top/Article/details/gtejnctpez.html

[S50] C++：格式化数字
来源：http://dali.hongshengwenyu.top/Article/details/gtrucpmpqf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtqexyppyb.html

[S51] C++：显式类型转换
来源：http://dali.dianchejie.cn/Article/details/gtwqdnoohw.html

static_cast<double>(a) / b
来源：http://dali.hongshengwenyu.top/Article/details/gtlxcidodk.html

[S52] C++：const 与 noexcept
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkzevddo.html

int size() const noexcept { return n_; }
来源：http://dali.gaohongyu789.top/Article/details/gtjuyjnijj.html

[S53] C++：移动语义
来源：http://dali.havefunace.top/Article/details/gtqfsgabyx.html

std::vector<int> w = std::move(v);
来源：http://dali.xuanzx.com/Article/details/gtzsuozsvg.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gtgcxhjggk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtxjvktewo.html

[S55] C++：结构化绑定
来源：http://dali.shzxlz.cn/Article/details/gtxpyagkxb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.316326.xyz/Article/details/gtkkzfukxm.html

[S56] C++：optional
来源：http://dali.gotoacloud.top/Article/details/gtaxdjtswa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.c1oappe.top/Article/details/gtvgradvfp.html

[S57] C++：编译期常量
来源：http://dali.pengpengdd.cyou/Article/details/gtbxdecxof.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gtzrgxxodk.html

[S58] C++：命名空间
来源：http://dali.hywenlv.cn/Article/details/gtkvafpxnn.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangdashe.top/Article/details/gtstzihtnz.html

[S59] C++：静态断言
来源：http://dali.guannengcc.top/Article/details/gtchmjzncr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daxiang520.top/Article/details/gttnoqfsyr.html

[S60] C++：遍历并删除元素
来源：http://dali.c1oappe.top/Article/details/gtqwmxneux.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.smart0.xyz/Article/details/gtccafzjpt.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gthvzhgmzj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aizwys.cn/Article/details/gtcxqljntg.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtoffgmyog.html

[T01] Kotlin：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtjahieahl.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtyjjbbrgh.html

[T02] Kotlin：变量
来源：http://dali.nanxuanxn.top/Article/details/gtqoerhwrq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hfpthk.cn/Article/details/gtqourglka.html

[T03] Kotlin：字符串模板
来源：http://dali.sxryk.cn/Article/details/gtwhifqian.html

"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtslzsqebo.html

[T04] Kotlin：空安全
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcqqxqjm.html

val n: String? = null;  n?.length
来源：http://dali.hywenlv.cn/Article/details/gtlynavffq.html

[T05] Kotlin：when 表达式
来源：http://dali.smart0.xyz/Article/details/gtbljcvzol.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yvedp.cn/Article/details/gtgzqnzywr.html

[T06] Kotlin：集合映射
来源：http://dali.yuxming.cn/Article/details/gtjwkympis.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ydzc1.top/Article/details/gtorfgtpqi.html

[T07] Kotlin：集合过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtpsltomqe.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gaohongyu789.top/Article/details/gtfxviecgi.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gtedxvsjrf.html

data class User(val name: String, val age: Int)
来源：http://dali.jianghu66.top/Article/details/gtcfxpbsjn.html

[T09] Kotlin：扩展函数
来源：http://dali.zhixingplan.top/Article/details/gtescpylva.html

fun String.exclaim() = this + "!"
来源：http://dali.sufxvd.cn/Article/details/gtcqerjomv.html

[T10] Kotlin：默认参数
来源：http://dali.gotoacloud.top/Article/details/gtzllmcpgf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhpasjnz.html

[T11] Kotlin：协程
来源：http://dali.tianlin.xyz/Article/details/gtfedugadn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnxicfou.html

[T12] Kotlin：解构声明
来源：http://dali.zhoulong.xyz/Article/details/gtmrwiedyv.html

val (a, b) = Pair(1, 2)
来源：http://dali.yonumen.top/Article/details/gtxgmesyqj.html

[T13] Kotlin：只读 Map
来源：http://dali.bjfxy.top/Article/details/gtzkliwyjn.html

val m = mapOf("a" to 1)
来源：http://dali.ydzc1.top/Article/details/gtsoqqtxbm.html

[T14] Kotlin：循环
来源：http://dali.hysaishi.cn/Article/details/gtiyqvafao.html

for (i in 1..10) println(i)
来源：http://dali.cucudq.cn/Article/details/gtrgofbyju.html

[T15] Kotlin：接口
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcrnkhlg.html

interface Shape { fun area(): Double }
来源：http://dali.shuidangran.top/Article/details/gtijhkiatn.html

[T16] Swift：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtwuwejppw.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtbrdeykis.html

[T17] Swift：变量与常量
来源：http://dali.jqgufenzy.top/Article/details/gtbxxnduqv.html

var a = 1;  let b = 2
来源：http://dali.tanke756.top/Article/details/gtaqnokbjq.html

[T18] Swift：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtiqhxesti.html

"值: \(b)"
来源：http://dali.gaohongyu789.top/Article/details/gtoryftale.html

[T19] Swift：可选绑定
来源：http://dali.haohaochexian.top/Article/details/gtqvnefnjx.html

if let n = opt { print(n) }
来源：http://dali.yongpay.top/Article/details/gtjtobehpz.html

[T20] Swift：数组操作
来源：http://dali.daria6918.cn/Article/details/gtszlthdnc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yongpay.top/Article/details/gtxehwmxyp.html

[T21] Swift：遍历
来源：http://dali.pycfn.com/Article/details/gtphthomny.html

for x in a { print(x) }
来源：http://dali.dashuyun.cn/Article/details/gtecohoeia.html

[T22] Swift：字典
来源：http://dali.wangshuangyany.cn/Article/details/gtwqeeuoxh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yanxiufei.cn/Article/details/gtjsoiuxen.html

[T23] Swift：函数
来源：http://dali.yj20258888.top/Article/details/gtazofutzb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtfmwzompw.html

[T24] Swift：闭包
来源：http://dali.zhoulong.xyz/Article/details/gtcicwesim.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtvllvsqzv.html

[T25] Swift：结构体
来源：http://dali.yvedp.cn/Article/details/gtvoucdbnq.html

struct P { var x: Int }
来源：http://dali.jyoumei.cn/Article/details/gtjtjhqhtq.html

[T26] Swift：类与重写
来源：http://dali.gaohongyu789.top/Article/details/gtxgljpjxw.html

class A: Base { override func f() {} }
来源：http://dali.yanxiufei.cn/Article/details/gtavyubmlx.html

[T27] Swift：错误处理
来源：http://dali.hnqzz.top/Article/details/gtrhzmbqnh.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gtipjcpzzk.html

[T28] Swift：枚举
来源：http://dali.yj20258.top/Article/details/gthoygunbw.html

enum Color { case red, green }
来源：http://dali.mhx1999.top/Article/details/gtnuuvnmuf.html

[T29] Swift：guard 提前返回
来源：http://dali.zhengqikj.top/Article/details/gtyzgauvft.html

guard let x = opt else { return }
来源：http://dali.xuetiantiany.cn/Article/details/gtfbwatyjy.html

[T30] Swift：协议
来源：http://dali.nwbrower.top/Article/details/gtqumjiafx.html

protocol Shape { func area() -> Double }
来源：http://dali.yuanzhike.top/Article/details/gtqcqfsjrz.html

[T31] Lua：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtostkexfj.html

print("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtmvxlevql.html

[T32] Lua：局部变量
来源：http://dali.smart0.xyz/Article/details/gtxnobfnje.html

local a = 1
来源：http://dali.hongshengwenyu.top/Article/details/gtwaxmfybj.html

[T33] Lua：表（数组）
来源：http://dali.pengpengdd.cyou/Article/details/gtnkeyswbw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.quarkkingdee.top/Article/details/gtlddrybxj.html

[T34] Lua：遍历表
来源：http://dali.jqgufenzy.top/Article/details/gteyykcbpf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuacsgmel.html

[T35] Lua：字典表
来源：http://dali.aizwys.cn/Article/details/gtgspltyfi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yonumen.top/Article/details/gteaqxxcnh.html

[T36] Lua：函数
来源：http://dali.sweek.top/Article/details/gtudehjdet.html

function add(a, b) return a + b end
来源：http://dali.shuidangran.top/Article/details/gtolmwrfon.html

[T37] Lua：字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gtaienelbq.html

"a" .. "b"
来源：http://dali.jlsjyb.cn/Article/details/gtrjakprwh.html

[T38] Lua：条件
来源：http://dali.xuetiantiany.cn/Article/details/gtjlxhacym.html

if x > 0 then print("正") end
来源：http://dali.ydzc1.top/Article/details/gtjxebjhuj.html

[T39] Lua：模式匹配
来源：http://dali.yj20258888.top/Article/details/gtzxnbejzu.html

string.find(s, "%d+")
来源：http://dali.hnxiangtu.top/Article/details/gtoeopronj.html

[T40] Lua：元表
来源：http://dali.zhengqikj.top/Article/details/gtciurqghn.html

setmetatable({}, { __index = base })
来源：http://dali.snrcjt.cn/Article/details/gtedglnpec.html

[T41] Perl：Hello World
来源：http://dali.yuxming.cn/Article/details/gtipknzdrd.html

print "Hello\n";
来源：http://dali.gaohongyu789.top/Article/details/gtafxxqidj.html

[T42] Perl：变量类型
来源：http://dali.bjfxy.top/Article/details/gtzpuxhdui.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zycfv.cn/Article/details/gtcxarvkds.html

[T43] Perl：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gtnpnutwzn.html

"值: $a"
来源：http://dali.tanke756.top/Article/details/gtoiqqauit.html

[T44] Perl：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynrfsfyg.html

if ($a > 0) { print "正"; }
来源：http://dali.ivvv.top/Article/details/gtheicvxst.html

[T45] Perl：数组遍历
来源：http://dali.fzhhl.top/Article/details/gtrdlvqogo.html

for my $x (@arr) { print $x; }
来源：http://dali.redwolf501.top/Article/details/gtzztlebfp.html

[T46] Perl：哈希操作
来源：http://dali.sxryk.cn/Article/details/gtmaproudq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xziqi.cn/Article/details/gtnlkpshgk.html

[T47] Perl：正则捕获
来源：http://dali.quarkkingdee.top/Article/details/gtprhuxvbq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.birdmap.top/Article/details/gtlqemsckw.html

[T48] Perl：正则替换
来源：http://dali.quarkkingdee.top/Article/details/gtxoypfssg.html

$s =~ s/old/new/g;
来源：http://dali.meibo888.top/Article/details/gtxnrjdmmk.html

[T49] Perl：函数
来源：http://dali.iojbl.cn/Article/details/gtecujbvmj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtrlnqqkep.html

[T50] Perl：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtqdrybjou.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ivvv.top/Article/details/gtexvlymsd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxinkj.top/Article/details/gtakjkynds.html

[T51] Scala：Hello World
来源：http://dali.ybcxt.top/Article/details/gtljkasihi.html

println("Hello")
来源：http://dali.birdmap.top/Article/details/gtxcwmajvo.html

[T52] Scala：变量
来源：http://dali.yanxiufei.cn/Article/details/gtirfcsnyf.html

val a = 1;  var b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtaigbqpah.html

[T53] Scala：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtlzepcbym.html

s"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gtrwnqmnah.html

[T54] Scala：集合映射
来源：http://dali.yueranfly.top/Article/details/gtcxxbgvcu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xziqi.cn/Article/details/gttytevqvr.html

[T55] Scala：集合过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtzbujpkyg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tanke756.top/Article/details/gtnzrcbxoo.html

[T56] Scala：样例类
来源：http://dali.xuetiantiany.cn/Article/details/gtkhaamcdl.html

case class User(name: String, age: Int)
来源：http://dali.snrcjt.cn/Article/details/gttxffdtpt.html

[T57] Scala：模式匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gttroohyci.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.9152youxi.cn/Article/details/gttwjudpch.html

[T58] Scala：函数定义
来源：http://dali.vqdsnc.cn/Article/details/gtkeixwsse.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.aizwys.cn/Article/details/gtuxwcvhpx.html

[T59] Scala：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtntadilly.html

for (i <- 1 to 10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gtyzhdpbyv.html

[T60] Scala：折叠
来源：http://dali.zycfv.cn/Article/details/gtjlrhgvlj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jiagoushi.top/Article/details/gteeoidmjk.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtksnwqgkq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gzhubu.top/Article/details/gtpyfxtiyb.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtbtjswned.html

[U01] Py：创建虚拟环境
来源：http://dali.316326.xyz/Article/details/gtyaowjtkf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinghuilouyu.cn/Article/details/gtatkcsfbo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.c1oappe.top/Article/details/gtsayqfqtf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xinyue.icu/Article/details/gtxyrqdhdm.html

[U03] Py：加载 .env 配置
来源：http://dali.yj202588.top/Article/details/gtlnjaebrc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.pengpengdd.cyou/Article/details/gtjwxwocit.html

[U04] Py：变量调试打印
来源：http://dali.meibo888.top/Article/details/gtmoydxcnj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.guowangkeji.top/Article/details/gttvzigvzp.html

[U05] Py：列表去重且保序
来源：http://dali.dashuyun.cn/Article/details/gtvcnulsyh.html

list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gteygapvis.html

[U06] Py：合并两个字典
来源：http://dali.havefunace.top/Article/details/gterlumfxk.html

{**a, **b}
来源：http://dali.tian-w.cn/Article/details/gtgehkhknn.html

[U07] Py：反转字典键值
来源：http://dali.jinqigufen.top/Article/details/gtwxfgotwp.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258.top/Article/details/gttgrjante.html

[U08] Py：展平二维列表
来源：http://dali.dashuyun.cn/Article/details/gtfolysqun.html

[y for x in nested for y in x]
来源：http://dali.gzhubu.top/Article/details/gtatbdbaci.html

[U09] Py：字典取最大值的键
来源：http://dali.zhiwuduotai.top/Article/details/gtbvvxlcwu.html

max(d, key=d.get)
来源：http://dali.zhixingplan.top/Article/details/gtegcxohwa.html

[U10] Py：按值排序字典
来源：http://dali.jqgufenzy.top/Article/details/gtfpuxpkup.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.svipenyu.cn/Article/details/gtfzepdwqy.html

[U11] Py：生成器表达式
来源：http://dali.jianghu66.top/Article/details/gtcomulpap.html

(x * 2 for x in arr)
来源：http://dali.yonumen.top/Article/details/gtgtnsoeky.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jiagoushi.top/Article/details/gtuibdkfmd.html

Counter(arr).most_common(3)
来源：http://dali.jlsjyb.cn/Article/details/gtxmxwecks.html

[U13] Py：固定长度队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcemxvftx.html

deque(maxlen=10)
来源：http://dali.feifeiyinyue.top/Article/details/gtdvygyypm.html

[U14] Py：分组收集到列表
来源：http://dali.nwbrower.top/Article/details/gtgrvennmo.html

defaultdict(list)
来源：http://dali.yuanzhike.top/Article/details/gttemyctxh.html

[U15] Py：高精度计时
来源：http://dali.shangyingyoupin.top/Article/details/gttgusvvde.html

t = time.perf_counter()
来源：http://dali.quarkkingdee.top/Article/details/gtyssgrkmh.html

[U16] Py：命令行参数解析
来源：http://dali.vqdsnc.cn/Article/details/gtvpdasmfs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xziqi.cn/Article/details/gtrhdllsso.html

[U17] Py：初始化日志
来源：http://dali.316326.xyz/Article/details/gttwkhnmtk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.9152youxi.cn/Article/details/gtxcncrpkc.html

[U18] Py：预编译正则
来源：http://dali.zhengqikj.top/Article/details/gtxopctlcx.html

pat = re.compile(r"\d+")
来源：http://dali.zdqjudy.top/Article/details/gtmlvdixte.html

[U19] Py：正则替换带回调
来源：http://dali.jinqigufen.top/Article/details/gtxudwlqfx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.guannengcc.top/Article/details/gtfbahiqdb.html

[U20] Py：缓存函数结果
来源：http://dali.xylfe.cn/Article/details/gtbxaakawe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpwbdwuz.html

[U21] Py：自定义上下文管理器
来源：http://dali.yanxiufei.cn/Article/details/gtaxfminqo.html

@contextlib.contextmanager
来源：http://dali.cucudq.cn/Article/details/gtzyesfkaq.html

[U22] Py：矩阵转置
来源：http://dali.mhx1999.top/Article/details/gtbomhensy.html

list(zip(*m))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrbaphom.html

[U23] Py：分块读取大文件
来源：http://dali.nwbrower.top/Article/details/gtajfengoj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.c1oappe.top/Article/details/gtcfsyaizb.html

[U24] Py：路径操作
来源：http://dali.jqgufenzy.top/Article/details/gtitdascji.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gtyjbyxsyq.html

[U25] Py：CSV 按字典读
来源：http://dali.tanke756.top/Article/details/gtoiuxsire.html

csv.DictReader(f)
来源：http://dali.xuetiantiany.cn/Article/details/gtvkszozvy.html

[U26] Py：并发下载
来源：http://dali.yuxming.cn/Article/details/gtukestoqv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cheryme.top/Article/details/gtqropjqan.html

[U27] Py：异步 HTTP
来源：http://dali.yueranfly.top/Article/details/gtnfkhnvrf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.fzhhl.top/Article/details/gtmivqbezd.html

[U28] Py：类型别名
来源：http://dali.ppjwa.cn/Article/details/gtdrxsaomd.html

UserId = int
来源：http://dali.xinyue.icu/Article/details/gtfkqxnepv.html

[U29] Py：属性校验
来源：http://dali.daxiang520.top/Article/details/gthlqtvvow.html

@property 与 @x.setter 配合
来源：http://dali.hfpthk.cn/Article/details/gtjzqavhxt.html

[U30] Py：数据类
来源：http://dali.shangyingyoupin.top/Article/details/gtvcjrszrb.html

@dataclass(slots=True)
来源：http://dali.ivvv.top/Article/details/gtyiqnzgtn.html

[U31] Py：单测
来源：http://dali.ppjwa.cn/Article/details/gtnljuzbds.html

python -m pytest -q
来源：http://dali.hfpthk.cn/Article/details/gtzpgzoykv.html

[U32] Py：代码格式化
来源：http://dali.guowangkeji.top/Article/details/gtvsbdvxdc.html

ruff format . && ruff check --fix .
来源：http://dali.haohaochexian.top/Article/details/gtkvcaxwyi.html

[U33] Py：打包发布
来源：http://dali.shzxlz.cn/Article/details/gthgdfcnag.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.9152youxi.cn/Article/details/gtkmqdrrri.html

[U34] Py：判断编码
来源：http://dali.chenzaomai.com/Article/details/gtdpjhxrpg.html

chardet.detect(raw)
来源：http://dali.cdnleiting.top/Article/details/gtcurpabvh.html

[U35] Py：发送邮件
来源：http://dali.yonumen.top/Article/details/gtltibspgk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gaohongyu789.top/Article/details/gtaixwexwd.html

[U36] Py：定时任务
来源：http://dali.cqqwz.cn/Article/details/gtwnunlwiy.html

schedule.every(10).minutes.do(job)
来源：http://dali.shangyingyoupin.top/Article/details/gtairuabvh.html


<!-- 参考信息 -->