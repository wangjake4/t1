代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.ehwqpu.com/Article/details/gtzdjlqskz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dashuyun.cn/Article/details/gtzhveizyo.html

fclose(f);
来源：http://dali.cheryme.top/Article/details/gtfqpqspvp.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhinarai.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tanke756.top/Article/details/gtmpfuemoj.html

[S13] C：宏定义
来源：http://dali.jqgufenzy.top/Article/details/gtdgzpbdzd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fzhhl.top/Article/details/gtyxrmvgwp.html

[S14] C：枚举
来源：http://dali.zhoulong.xyz/Article/details/gtrptwizsy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hongshengwenyu.top/Article/details/gtsupaqpjp.html

[S15] C：类型转换
来源：http://dali.9152youxi.cn/Article/details/gttvwmqsms.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gtrcnklvsv.html

[S16] C：位操作置位
来源：http://dali.xuanzx.com/Article/details/gtuyuxgcwd.html

x |= (1 << 3);
来源：http://dali.bjfxy.top/Article/details/gthxefuoai.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtfffikerl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hfpthk.cn/Article/details/gtevlqrlpt.html

[S18] C：命令行参数
来源：http://dali.tanke756.top/Article/details/gtcfkhuiqc.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gtjqbdwuco.html

[S19] C：快速排序
来源：http://dali.shzxlz.cn/Article/details/gtogumtqsw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gtpjvqxuai.html

[S20] C：二分查找
来源：http://dali.jianghu66.top/Article/details/gtlyciekjb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gthhknkqgy.html

[S21] C：字符类别判断
来源：http://dali.ehwqpu.com/Article/details/gtfejgnbpk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.haohaochexian.top/Article/details/gtonjzcaii.html

[S22] C：字符串转数字
来源：http://dali.nwbrower.top/Article/details/gtzogmbatl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyrczjdo.html

[S23] C：随机数
来源：http://dali.aibaodan.cn/Article/details/gtltvhtvhk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sweek.top/Article/details/gtnkhutgoz.html

[S24] C：获取本地时间
来源：http://dali.meibo888.top/Article/details/gthozggeur.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.iojbl.cn/Article/details/gttavlpufp.html

[S25] C：内存拷贝
来源：http://dali.jianghu66.top/Article/details/gtumtkfxjk.html

memcpy(dst, src, n);
来源：http://dali.cqqwz.cn/Article/details/gtljodcqlm.html

[S26] C：内存清零
来源：http://dali.jinqigfzy.top/Article/details/gtmaaarqdf.html

memset(a, 0, sizeof a);
来源：http://dali.jianghu66.top/Article/details/gteymcobed.html

[S27] C：定义常量
来源：http://dali.xuanzx.com/Article/details/gtzzhatovg.html

const double PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtpgctgcho.html

[S28] C：静态变量
来源：http://dali.jianghu66.top/Article/details/gtajtbztxa.html

static int counter = 0;
来源：http://dali.birdmap.top/Article/details/gtksdsptzj.html

[S29] C：变参函数
来源：http://dali.hfpthk.cn/Article/details/gttehbaqrf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aibaodan.cn/Article/details/gtdfrfknxc.html

[S30] C：头文件保护
来源：http://dali.ivvv.top/Article/details/gtuhudcvdp.html

#ifndef X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmompzcm.html

#define X_H
来源：http://dali.9152youxi.cn/Article/details/gtcgsvmcbi.html

#endif
来源：http://dali.ydzc1.top/Article/details/gtqofevled.html

[S31] C++：Hello World
来源：http://dali.hammf.cn/Article/details/gtimoftqcs.html

#include <iostream>
来源：http://dali.cashguo.top/Article/details/gtlocdgwby.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuxming.cn/Article/details/gtxwaeihlr.html

[S32] C++：字符串
来源：http://dali.jqgufenzy.top/Article/details/gtjzzwifvb.html

std::string s = "hi";  s += "!";
来源：http://dali.gzhubu.top/Article/details/gtdvnbarob.html

[S33] C++：vector 增删
来源：http://dali.jlsjyb.cn/Article/details/gtyfscmvoh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhydywix.html

[S34] C++：遍历 vector
来源：http://dali.fengsongda.top/Article/details/gtpkrghdcg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hywenlv.cn/Article/details/gtuedvygik.html

[S35] C++：map
来源：http://dali.havefunace.top/Article/details/gtdxcwnooa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gthyguqimb.html

[S36] C++：unordered_map
来源：http://dali.chenjidiqi.icu/Article/details/gtworlbypq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtgkyorbji.html

[S37] C++：set
来源：http://dali.jinqigfzy.top/Article/details/gtkjwzibnb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cdnleiting.top/Article/details/gtvwbncqvs.html

[S38] C++：排序
来源：http://dali.ybcxt.top/Article/details/gtkuxaxftt.html

std::sort(v.begin(), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gtfsnofjpn.html

[S39] C++：自定义比较器排序
来源：http://dali.pycfn.com/Article/details/gtlcuxxfyl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sysykeji.top/Article/details/gtbeoojnrb.html

[S40] C++：查找元素
来源：http://dali.jiagoushi.top/Article/details/gtnlahefzu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxinkj.top/Article/details/gtcxxufggk.html

[S41] C++：类与构造函数
来源：http://dali.jianghu66.top/Article/details/gtwkroeukg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aizwys.cn/Article/details/gtdvqtrppv.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtocgsimto.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgfzy.top/Article/details/gtsicebtpt.html

[S43] C++：智能指针
来源：http://dali.wangdashe.top/Article/details/gtqpsijfhq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zdqjudy.top/Article/details/gtttykygwm.html

[S44] C++：引用传参
来源：http://dali.gaohongyu789.top/Article/details/gtduakwdbb.html

void inc(int &x) { ++x; }
来源：http://dali.gaohongyu789.top/Article/details/gtisoucvop.html

[S45] C++：lambda
来源：http://dali.ydzc1.top/Article/details/gtwdchwuoh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dianchejie.cn/Article/details/gtowwkslns.html

[S46] C++：函数模板
来源：http://dali.yueranfly.top/Article/details/gtesmssnkk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.9152youxi.cn/Article/details/gtqclzytib.html

[S47] C++：结构化绑定遍历
来源：http://dali.yueranfly.top/Article/details/gtsyzdlxac.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gogol.net.cn/Article/details/gtwqjerkpr.html

[S48] C++：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtnngkfrsw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yueranfly.top/Article/details/gtpgvgunyp.html

while (std::getline(in, line)) { }
来源：http://dali.xuanzx.com/Article/details/gtwkcuwxej.html

[S49] C++：写文件
来源：http://dali.nanxinkj.top/Article/details/gtwbivjsvr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tian-w.cn/Article/details/gtfikipzee.html

[S50] C++：格式化数字
来源：http://dali.snrcjt.cn/Article/details/gtyeqmxsyh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnqzz.top/Article/details/gthalwhptb.html

[S51] C++：显式类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtfpotbeun.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gtgwkphbxp.html

[S52] C++：const 与 noexcept
来源：http://dali.yongpay.top/Article/details/gtjwhcwhsu.html

int size() const noexcept { return n_; }
来源：http://dali.dianchejie.cn/Article/details/gtwwgeafsl.html

[S53] C++：移动语义
来源：http://dali.smart0.xyz/Article/details/gttjyivqvo.html

std::vector<int> w = std::move(v);
来源：http://dali.jyoumei.cn/Article/details/gtrfjfnylm.html

[S54] C++：异常处理
来源：http://dali.fzhhl.top/Article/details/gtbgfreyve.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.kuanghao11.cn/Article/details/gtthhboogd.html

[S55] C++：结构化绑定
来源：http://dali.havefunace.top/Article/details/gtpvmuzbqp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gtfmjpvltj.html

[S56] C++：optional
来源：http://dali.ydzc1.top/Article/details/gtysexcbmc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258888.top/Article/details/gtmhzjsmdf.html

[S57] C++：编译期常量
来源：http://dali.chenlongwang.top/Article/details/gtkeeauquw.html

constexpr int N = 10;
来源：http://dali.pycfn.com/Article/details/gtxnukpjys.html

[S58] C++：命名空间
来源：http://dali.yj20258.top/Article/details/gtfonpiqgl.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtkvqluhdt.html

[S59] C++：静态断言
来源：http://dali.ehwqpu.com/Article/details/gtaqbqisjg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fengsongda.top/Article/details/gtpomyxpdp.html

[S60] C++：遍历并删除元素
来源：http://dali.haohaochexian.top/Article/details/gtablbaszf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dianchejie.cn/Article/details/gtghzmkzsr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtckqmdmqm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jlsjyb.cn/Article/details/gtzgyzpyvt.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtobhponzh.html

[T01] Kotlin：Hello World
来源：http://dali.havefunace.top/Article/details/gtxgspzcrh.html

println("Hello")
来源：http://dali.wangdashe.top/Article/details/gtlfiqctdf.html

[T02] Kotlin：变量
来源：http://dali.fengsongda.top/Article/details/gtotnoatqy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.svipenyu.cn/Article/details/gtrbgnetya.html

[T03] Kotlin：字符串模板
来源：http://dali.wangshuangyany.cn/Article/details/gtlaesjeyq.html

"值: $b"
来源：http://dali.ivvv.top/Article/details/gtwdfbfocn.html

[T04] Kotlin：空安全
来源：http://dali.xziqi.cn/Article/details/gtwcsbifuj.html

val n: String? = null;  n?.length
来源：http://dali.jqgufenzy.top/Article/details/gtbuknocyy.html

[T05] Kotlin：when 表达式
来源：http://dali.iojbl.cn/Article/details/gtjqzbmozl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guowangkeji.top/Article/details/gtwgecngsc.html

[T06] Kotlin：集合映射
来源：http://dali.sysykeji.top/Article/details/gtioazprxa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuanzx.com/Article/details/gtjntlqgeh.html

[T07] Kotlin：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gtferelynl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.redwolf501.top/Article/details/gtskvlxpfc.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gtqjpolpgz.html

data class User(val name: String, val age: Int)
来源：http://dali.quarkkingdee.top/Article/details/gtxnwxwmai.html

[T09] Kotlin：扩展函数
来源：http://dali.wangdashe.top/Article/details/gtblyoqlkv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhiwuduotai.top/Article/details/gtdvdinhtt.html

[T10] Kotlin：默认参数
来源：http://dali.gzhubu.top/Article/details/gtpprvvzxw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuanzx.com/Article/details/gttmqbxbqx.html

[T11] Kotlin：协程
来源：http://dali.xylfe.cn/Article/details/gtwgtpioox.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tianlin.xyz/Article/details/gtotmenjyj.html

[T12] Kotlin：解构声明
来源：http://dali.ydzc1.top/Article/details/gtnohgmwku.html

val (a, b) = Pair(1, 2)
来源：http://dali.yongpay.top/Article/details/gtiomvphtm.html

[T13] Kotlin：只读 Map
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfztgoic.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258888.top/Article/details/gtggwhwkjc.html

[T14] Kotlin：循环
来源：http://dali.0kj1m.cn/Article/details/gtcvixgqov.html

for (i in 1..10) println(i)
来源：http://dali.c1oappe.top/Article/details/gtrzmvoplo.html

[T15] Kotlin：接口
来源：http://dali.hammf.cn/Article/details/gtslhfikjr.html

interface Shape { fun area(): Double }
来源：http://dali.nanxuanxn.top/Article/details/gtczumnqbz.html

[T16] Swift：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtvbceompl.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtnewxjhrd.html

[T17] Swift：变量与常量
来源：http://dali.guowangkeji.top/Article/details/gtctietszx.html

var a = 1;  let b = 2
来源：http://dali.hfpthk.cn/Article/details/gtyvhrpbdq.html

[T18] Swift：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gttliilbad.html

"值: \(b)"
来源：http://dali.sweek.top/Article/details/gtddntevdm.html

[T19] Swift：可选绑定
来源：http://dali.ydzc1.top/Article/details/gtlrbopykk.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gtmxxzoahg.html

[T20] Swift：数组操作
来源：http://dali.gaohongyu789.top/Article/details/gtgrezrnxk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuanzhike.top/Article/details/gtvtahbbha.html

[T21] Swift：遍历
来源：http://dali.hammf.cn/Article/details/gtwaosrfzh.html

for x in a { print(x) }
来源：http://dali.svipenyu.cn/Article/details/gttmerkhjs.html

[T22] Swift：字典
来源：http://dali.bjfxy.top/Article/details/gthqchfcmq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dashuyun.cn/Article/details/gtqobsnjzg.html

[T23] Swift：函数
来源：http://dali.316326.xyz/Article/details/gtpnosblfg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtjfetrisd.html

[T24] Swift：闭包
来源：http://dali.mhx1999.top/Article/details/gtjrkhgdpd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.mhx1999.top/Article/details/gtrkanpmux.html

[T25] Swift：结构体
来源：http://dali.vqdsnc.cn/Article/details/gtljclfeku.html

struct P { var x: Int }
来源：http://dali.chenlongwang.top/Article/details/gtrazfvjcl.html

[T26] Swift：类与重写
来源：http://dali.hysaishi.cn/Article/details/gtnyewvuhr.html

class A: Base { override func f() {} }
来源：http://dali.316326.xyz/Article/details/gtgospqxfj.html

[T27] Swift：错误处理
来源：http://dali.gotoacloud.top/Article/details/gthmxsnzcw.html

do { try f() } catch { print(error) }
来源：http://dali.nwbrower.top/Article/details/gthygqycty.html

[T28] Swift：枚举
来源：http://dali.kuanghao11.cn/Article/details/gtzzzffjhr.html

enum Color { case red, green }
来源：http://dali.shuidangran.top/Article/details/gtiialvcdl.html

[T29] Swift：guard 提前返回
来源：http://dali.yj202588.top/Article/details/gtqpphtmjd.html

guard let x = opt else { return }
来源：http://dali.ydzc1.top/Article/details/gtmjodbwmq.html

[T30] Swift：协议
来源：http://dali.zycfv.cn/Article/details/gtilzuoqys.html

protocol Shape { func area() -> Double }
来源：http://dali.pengpengdd.cyou/Article/details/gticvwmows.html

[T31] Lua：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtcqbjjjkm.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gtinsolnvz.html

[T32] Lua：局部变量
来源：http://dali.andypj.xyz/Article/details/gtaqwobkuh.html

local a = 1
来源：http://dali.kuanghao11.cn/Article/details/gtjnvwtayw.html

[T33] Lua：表（数组）
来源：http://dali.jlsjyb.cn/Article/details/gtmyuxgjbq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shangyingyoupin.top/Article/details/gthronvukb.html

[T34] Lua：遍历表
来源：http://dali.cashguo.top/Article/details/gtijpcgseg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxuanxn.top/Article/details/gtecygpktz.html

[T35] Lua：字典表
来源：http://dali.aibaodan.cn/Article/details/gtkykzneoi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jyoumei.cn/Article/details/gtygtujxis.html

[T36] Lua：函数
来源：http://dali.chenzaomai.com/Article/details/gtafwpkevj.html

function add(a, b) return a + b end
来源：http://dali.zycfv.cn/Article/details/gtwlfyeani.html

[T37] Lua：字符串拼接
来源：http://dali.chenzaomai.com/Article/details/gtsphxigfw.html

"a" .. "b"
来源：http://dali.zhengqikj.top/Article/details/gtwkssxpmf.html

[T38] Lua：条件
来源：http://dali.xuetiantiany.cn/Article/details/gtbairicwf.html

if x > 0 then print("正") end
来源：http://dali.9152youxi.cn/Article/details/gtlbjqtvsy.html

[T39] Lua：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gtrcvncpqf.html

string.find(s, "%d+")
来源：http://dali.birdmap.top/Article/details/gttwebapxt.html

[T40] Lua：元表
来源：http://dali.ppjwa.cn/Article/details/gtupqunytp.html

setmetatable({}, { __index = base })
来源：http://dali.birdmap.top/Article/details/gtumvmnaxq.html

[T41] Perl：Hello World
来源：http://dali.andypj.xyz/Article/details/gtoodordnv.html

print "Hello\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gthykpounq.html

[T42] Perl：变量类型
来源：http://dali.cqqwz.cn/Article/details/gtgtwmrmik.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhixingplan.top/Article/details/gtgpuxdtfr.html

[T43] Perl：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtafnbdcgu.html

"值: $a"
来源：http://dali.yanxiufei.cn/Article/details/gtmqauetzv.html

[T44] Perl：条件
来源：http://dali.hysaishi.cn/Article/details/gtjerejejo.html

if ($a > 0) { print "正"; }
来源：http://dali.iojbl.cn/Article/details/gtdzxlthyl.html

[T45] Perl：数组遍历
来源：http://dali.jinqigufen.top/Article/details/gtsxdrvnfn.html

for my $x (@arr) { print $x; }
来源：http://dali.tian-w.cn/Article/details/gtefndadev.html

[T46] Perl：哈希操作
来源：http://dali.redwolf501.top/Article/details/gtbovctpfv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.smart0.xyz/Article/details/gtjjyxhnng.html

[T47] Perl：正则捕获
来源：http://dali.yueranfly.top/Article/details/gtgvomrkpw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cucudq.cn/Article/details/gtbadgmtnz.html

[T48] Perl：正则替换
来源：http://dali.jqgfzy.top/Article/details/gtvhwtlxzy.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzsnbker.html

[T49] Perl：函数
来源：http://dali.sufxvd.cn/Article/details/gtoqtkrlko.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtwelrynfn.html

[T50] Perl：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtcpqalggn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tian-w.cn/Article/details/gtrhcetrwa.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ydzc1.top/Article/details/gtitysazhq.html

[T51] Scala：Hello World
来源：http://dali.zycfv.cn/Article/details/gtzjhrexfn.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gtcwpmollr.html

[T52] Scala：变量
来源：http://dali.jyoumei.cn/Article/details/gtswtqfaea.html

val a = 1;  var b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyraoawx.html

[T53] Scala：字符串插值
来源：http://dali.yj20258.top/Article/details/gtubzpubqn.html

s"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtaasvlsum.html

[T54] Scala：集合映射
来源：http://dali.hywenlv.cn/Article/details/gtgpwgtmyf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.havefunace.top/Article/details/gtpghuyxoh.html

[T55] Scala：集合过滤
来源：http://dali.redwolf501.top/Article/details/gtkencyuhv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sweek.top/Article/details/gtjjhqfztq.html

[T56] Scala：样例类
来源：http://dali.dashuyun.cn/Article/details/gtemwhazzk.html

case class User(name: String, age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfbhtukc.html

[T57] Scala：模式匹配
来源：http://dali.iojbl.cn/Article/details/gtaibnejoe.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.iojbl.cn/Article/details/gtcdquafmy.html

[T58] Scala：函数定义
来源：http://dali.jinqigufen.top/Article/details/gtqphybkdi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sxryk.cn/Article/details/gtisxrjtup.html

[T59] Scala：循环
来源：http://dali.jqgufenzy.top/Article/details/gttdsgdebq.html

for (i <- 1 to 10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gtsmxszmmq.html

[T60] Scala：折叠
来源：http://dali.xinyue.icu/Article/details/gtibfjkywo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgfzy.top/Article/details/gtkguwwdaz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtdhlqheyz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yvedp.cn/Article/details/gtldcrevxq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtdzgputrw.html

[U01] Py：创建虚拟环境
来源：http://dali.sufxvd.cn/Article/details/gtqktjlrka.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.quarkkingdee.top/Article/details/gtattrnfdq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.snrcjt.cn/Article/details/gtmzpyrpai.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cheryme.top/Article/details/gttvycxkji.html

[U03] Py：加载 .env 配置
来源：http://dali.daxiang520.top/Article/details/gtldwhickl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgfzy.top/Article/details/gtckvaslgx.html

[U04] Py：变量调试打印
来源：http://dali.aibaodan.cn/Article/details/gtvgmecaud.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yongpay.top/Article/details/gtlykfnwxt.html

[U05] Py：列表去重且保序
来源：http://dali.gogol.net.cn/Article/details/gtokgnpznj.html

list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gtnhveloeq.html

[U06] Py：合并两个字典
来源：http://dali.cheryme.top/Article/details/gtbpqsvgpk.html

{**a, **b}
来源：http://dali.chenlongwang.top/Article/details/gtsiovvqqd.html

[U07] Py：反转字典键值
来源：http://dali.0kj1m.cn/Article/details/gtmppoxapn.html

{v: k for k, v in d.items()}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrulukjs.html

[U08] Py：展平二维列表
来源：http://dali.cashguo.top/Article/details/gtgpwuzney.html

[y for x in nested for y in x]
来源：http://dali.wangshuangyany.cn/Article/details/gtjeqwrcro.html

[U09] Py：字典取最大值的键
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjsihlys.html

max(d, key=d.get)
来源：http://dali.yj202588.top/Article/details/gtjqrlnbzf.html

[U10] Py：按值排序字典
来源：http://dali.jinqigufen.top/Article/details/gtenughvti.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nwbrower.top/Article/details/gtoononjwn.html

[U11] Py：生成器表达式
来源：http://dali.jqgfzy.top/Article/details/gtvzjwagkm.html

(x * 2 for x in arr)
来源：http://dali.jianghu66.top/Article/details/gtsiqsiein.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykglnsmj.html

Counter(arr).most_common(3)
来源：http://dali.chenlongwang.top/Article/details/gtoiahnpys.html

[U13] Py：固定长度队列
来源：http://dali.fzhhl.top/Article/details/gtlxwallsg.html

deque(maxlen=10)
来源：http://dali.hfpthk.cn/Article/details/gtyhxqtuix.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258888.top/Article/details/gtnwkkpwzj.html

defaultdict(list)
来源：http://dali.feifeiyinyue.top/Article/details/gtnufpiqgg.html

[U15] Py：高精度计时
来源：http://dali.zhixingplan.top/Article/details/gtzjacxjmo.html

t = time.perf_counter()
来源：http://dali.ydzc1.top/Article/details/gtiujlnslj.html

[U16] Py：命令行参数解析
来源：http://dali.meibo888.top/Article/details/gtrhkgkmog.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuxming.cn/Article/details/gtgwhxnimv.html

[U17] Py：初始化日志
来源：http://dali.yj20258888.top/Article/details/gtimrgvbli.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yvedp.cn/Article/details/gtslwbxqfj.html

[U18] Py：预编译正则
来源：http://dali.nanxuanxn.top/Article/details/gtnrjyfnzm.html

pat = re.compile(r"\d+")
来源：http://dali.gogol.net.cn/Article/details/gtlczznlcs.html

[U19] Py：正则替换带回调
来源：http://dali.daxiang520.top/Article/details/gtuwdmkgmt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhoulong.xyz/Article/details/gthzvglxxw.html

[U20] Py：缓存函数结果
来源：http://dali.tian-w.cn/Article/details/gtvblkwejr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yuanzhike.top/Article/details/gtvuhzdsbp.html

[U21] Py：自定义上下文管理器
来源：http://dali.havefunace.top/Article/details/gthetbfaoo.html

@contextlib.contextmanager
来源：http://dali.yj202588.top/Article/details/gtfoaynkjn.html

[U22] Py：矩阵转置
来源：http://dali.guannengcc.top/Article/details/gtuuxujwlb.html

list(zip(*m))
来源：http://dali.yangfankeji.com/Article/details/gtemalwcea.html

[U23] Py：分块读取大文件
来源：http://dali.ivvv.top/Article/details/gtjynnevbp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jlsjyb.cn/Article/details/gtjawpjyog.html

[U24] Py：路径操作
来源：http://dali.cucudq.cn/Article/details/gtsmptglar.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gtasiuhzug.html

[U25] Py：CSV 按字典读
来源：http://dali.yj20258.top/Article/details/gtdicphnqa.html

csv.DictReader(f)
来源：http://dali.yuxming.cn/Article/details/gtzphfcapo.html

[U26] Py：并发下载
来源：http://dali.jiagoushi.top/Article/details/gtmkpsntoh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gaohongyu789.top/Article/details/gtdookiled.html

[U27] Py：异步 HTTP
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhaojxkt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shzxlz.cn/Article/details/gttomepfsv.html

[U28] Py：类型别名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjuqztoqw.html

UserId = int
来源：http://dali.haohaochexian.top/Article/details/gtlyarzlui.html

[U29] Py：属性校验
来源：http://dali.zhixingplan.top/Article/details/gtukwlhyzl.html

@property 与 @x.setter 配合
来源：http://dali.yongpay.top/Article/details/gtjytxomzh.html

[U30] Py：数据类
来源：http://dali.yj20258888.top/Article/details/gtjeuarvvc.html

@dataclass(slots=True)
来源：http://dali.birdmap.top/Article/details/gtpcefxkny.html

[U31] Py：单测
来源：http://dali.shanyushiyangtech.top/Article/details/gtaohqrizf.html

python -m pytest -q
来源：http://dali.aibaodan.cn/Article/details/gtvedqlsxc.html

[U32] Py：代码格式化
来源：http://dali.daria6918.cn/Article/details/gttgsbsuap.html

ruff format . && ruff check --fix .
来源：http://dali.c1oappe.top/Article/details/gtwathxihn.html

[U33] Py：打包发布
来源：http://dali.sxryk.cn/Article/details/gtxqsojgtx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shangyingyoupin.top/Article/details/gtykezlfvl.html

[U34] Py：判断编码
来源：http://dali.gaohongyu789.top/Article/details/gtephqhoel.html

chardet.detect(raw)
来源：http://dali.kuanghao11.cn/Article/details/gtxkueyulm.html


<!-- 参考信息 -->