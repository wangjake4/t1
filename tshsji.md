代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yonumen.top/Article/details/gtcrhbuclt.html

[S10] C：指针与解引用
来源：http://dali.daria6918.cn/Article/details/gtweyvbhjz.html

int *p = &a;  *p = 5;
来源：http://dali.yvedp.cn/Article/details/gtdsqfcwvg.html

[S11] C：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtzguitlrw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuetiantiany.cn/Article/details/gtnwcsolrw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.svipenyu.cn/Article/details/gtgsrqtoex.html

fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gtohwsjtbw.html

[S12] C：写文件
来源：http://dali.wangdashe.top/Article/details/gtgpyomnyz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gtuxebnjlp.html

[S13] C：宏定义
来源：http://dali.iojbl.cn/Article/details/gtrwziaiva.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yangfankeji.com/Article/details/gtyqzlvkhg.html

[S14] C：枚举
来源：http://dali.chenlongwang.top/Article/details/gteuwaoutv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.feifeiyinyue.top/Article/details/gtuhkcjshn.html

[S15] C：类型转换
来源：http://dali.tanke756.top/Article/details/gtrgphwyjd.html

(double) a / b
来源：http://dali.guowangkeji.top/Article/details/gtphcclscs.html

[S16] C：位操作置位
来源：http://dali.daria6918.cn/Article/details/gtksdatfgn.html

x |= (1 << 3);
来源：http://dali.chenzaomai.com/Article/details/gtlzeifdou.html

[S17] C：安全拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtladfvosh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigufen.top/Article/details/gtisiiaour.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalwfvymw.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gtapyemcsg.html

[S19] C：快速排序
来源：http://dali.chenjidiqi.icu/Article/details/gtihqoaoik.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gteogamlgy.html

[S20] C：二分查找
来源：http://dali.ppjwa.cn/Article/details/gtgqulwdjv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtiukqcbob.html

[S21] C：字符类别判断
来源：http://dali.daria6918.cn/Article/details/gttitxpwsc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhengqikj.top/Article/details/gtynfpbfyf.html

[S22] C：字符串转数字
来源：http://dali.zhongyouzk.top/Article/details/gttxowjtqp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tian-w.cn/Article/details/gtmypgchyd.html

[S23] C：随机数
来源：http://dali.yuanzhike.top/Article/details/gtpipmhahy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj202588.top/Article/details/gtiuchgzbw.html

[S24] C：获取本地时间
来源：http://dali.yj202588.top/Article/details/gtkypfjfop.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.mhx1999.top/Article/details/gttugkcwwv.html

[S25] C：内存拷贝
来源：http://dali.hnqzz.top/Article/details/gtqykeyirr.html

memcpy(dst, src, n);
来源：http://dali.hammf.cn/Article/details/gtbhjjrgbv.html

[S26] C：内存清零
来源：http://dali.gaohongyu789.top/Article/details/gtyfilymyq.html

memset(a, 0, sizeof a);
来源：http://dali.tanke756.top/Article/details/gtculxjjbl.html

[S27] C：定义常量
来源：http://dali.gogol.net.cn/Article/details/gtatnpvoib.html

const double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtdkoyoayn.html

[S28] C：静态变量
来源：http://dali.yonumen.top/Article/details/gtkvyfpfaf.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gtnudtwigv.html

[S29] C：变参函数
来源：http://dali.cheryme.top/Article/details/gtpcpemfky.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangshuangyany.cn/Article/details/gteugmjxjk.html

[S30] C：头文件保护
来源：http://dali.tanke756.top/Article/details/gtmrkuetne.html

#ifndef X_H
来源：http://dali.316326.xyz/Article/details/gtzgfwthgo.html

#define X_H
来源：http://dali.hfpthk.cn/Article/details/gtnczrgojp.html

#endif
来源：http://dali.nanxinkj.top/Article/details/gtymssszqu.html

[S31] C++：Hello World
来源：http://dali.havefunace.top/Article/details/gtgierfjol.html

#include <iostream>
来源：http://dali.shuidangran.top/Article/details/gtghbcibps.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatppdxvg.html

[S32] C++：字符串
来源：http://dali.mhx1999.top/Article/details/gtyozbmvmj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhengqikj.top/Article/details/gtgxfypqpk.html

[S33] C++：vector 增删
来源：http://dali.daria6918.cn/Article/details/gtyogwjvfj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gtonikcryg.html

[S34] C++：遍历 vector
来源：http://dali.chenlongwang.top/Article/details/gtwecgucto.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangshuangyany.cn/Article/details/gtsneqbuew.html

[S35] C++：map
来源：http://dali.nanxinkj.top/Article/details/gtmvqzotur.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtssibvwsq.html

[S36] C++：unordered_map
来源：http://dali.guannengcc.top/Article/details/gtoesqlcuf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtemhyrmdl.html

[S37] C++：set
来源：http://dali.nanxinkj.top/Article/details/gtwxiqwyaz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtfxlcculz.html

[S38] C++：排序
来源：http://dali.gogol.net.cn/Article/details/gtircehdcd.html

std::sort(v.begin(), v.end());
来源：http://dali.andypj.xyz/Article/details/gtabvyvedb.html

[S39] C++：自定义比较器排序
来源：http://dali.chenjidiqi.icu/Article/details/gtwvommmub.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.svipenyu.cn/Article/details/gtnqzdcmhf.html

[S40] C++：查找元素
来源：http://dali.gotoacloud.top/Article/details/gtkigdoekf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.0kj1m.cn/Article/details/gtehomekbf.html

[S41] C++：类与构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtprtbuicg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yvedp.cn/Article/details/gtchdicuma.html

[S42] C++：继承与虚函数
来源：http://dali.hywenlv.cn/Article/details/gtifyakrbc.html

class B : public Base { public: void f() override {} };
来源：http://dali.316326.xyz/Article/details/gtwojsqwzg.html

[S43] C++：智能指针
来源：http://dali.hnxiangtu.top/Article/details/gtfatztbso.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuxming.cn/Article/details/gtmphxsloq.html

[S44] C++：引用传参
来源：http://dali.yuxming.cn/Article/details/gtsdhedxki.html

void inc(int &x) { ++x; }
来源：http://dali.hywenlv.cn/Article/details/gthhixyeee.html

[S45] C++：lambda
来源：http://dali.tanke756.top/Article/details/gtzeokupmc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.c1oappe.top/Article/details/gtowwmpfnb.html

[S46] C++：函数模板
来源：http://dali.andypj.xyz/Article/details/gtcmsftsdi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrryfdfx.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgufenzy.top/Article/details/gtnpwrgffs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cashguo.top/Article/details/gtdibseovx.html

[S48] C++：逐行读文件
来源：http://dali.yj20258.top/Article/details/gtaojfiflz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shzxlz.cn/Article/details/gtmlymhshr.html

while (std::getline(in, line)) { }
来源：http://dali.gogol.net.cn/Article/details/gtzgvodfuf.html

[S49] C++：写文件
来源：http://dali.jiagoushi.top/Article/details/gtvnfpfolb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gteybeetxw.html

[S50] C++：格式化数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpqzixrm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtwsqjdrbc.html

[S51] C++：显式类型转换
来源：http://dali.zhixingplan.top/Article/details/gthkydvhio.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpayksmb.html

[S52] C++：const 与 noexcept
来源：http://dali.hnxiangtu.top/Article/details/gtfyfniube.html

int size() const noexcept { return n_; }
来源：http://dali.nanxuanxn.top/Article/details/gttvkurfqv.html

[S53] C++：移动语义
来源：http://dali.zhiwuduotai.top/Article/details/gtmtvsfqbt.html

std::vector<int> w = std::move(v);
来源：http://dali.dianchejie.cn/Article/details/gtvxiiwegs.html

[S54] C++：异常处理
来源：http://dali.sufxvd.cn/Article/details/gttizhamcb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.svipenyu.cn/Article/details/gtxkelrycg.html

[S55] C++：结构化绑定
来源：http://dali.yangfankeji.com/Article/details/gtxighbwfk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xylfe.cn/Article/details/gtwthsapzv.html

[S56] C++：optional
来源：http://dali.zhiwuduotai.top/Article/details/gtepnykydd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvqtybzvk.html

[S57] C++：编译期常量
来源：http://dali.yongpay.top/Article/details/gtkgjmjwuz.html

constexpr int N = 10;
来源：http://dali.dianchejie.cn/Article/details/gtdvtghuam.html

[S58] C++：命名空间
来源：http://dali.gaohongyu789.top/Article/details/gtbfxxhcmt.html

namespace ns { int f() { return 1; } }
来源：http://dali.dashuyun.cn/Article/details/gttrvbdmcl.html

[S59] C++：静态断言
来源：http://dali.dianchejie.cn/Article/details/gtbgzunkeh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigfzy.top/Article/details/gtwhizbwai.html

[S60] C++：遍历并删除元素
来源：http://dali.jinqigfzy.top/Article/details/gtqblbogwm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sysykeji.top/Article/details/gtuetrofps.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtrqrikfjp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zdqjudy.top/Article/details/gtlkndnpcr.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtpgqwwvwp.html

[T01] Kotlin：Hello World
来源：http://dali.daxiang520.top/Article/details/gtaajydzkn.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gtmyaczpys.html

[T02] Kotlin：变量
来源：http://dali.jianghu66.top/Article/details/gtvhmcctok.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangdashe.top/Article/details/gtdedsfkza.html

[T03] Kotlin：字符串模板
来源：http://dali.tanke756.top/Article/details/gtgazafijb.html

"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gtslysakwr.html

[T04] Kotlin：空安全
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrnmbxjx.html

val n: String? = null;  n?.length
来源：http://dali.zdqjudy.top/Article/details/gtjrsimubu.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigfzy.top/Article/details/gtffjoviga.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guowangkeji.top/Article/details/gtpxfhrrcg.html

[T06] Kotlin：集合映射
来源：http://dali.andypj.xyz/Article/details/gtfbhkhcix.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtjmbjbwki.html

[T07] Kotlin：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gtsinshpsq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gotoacloud.top/Article/details/gtqyxstoil.html

[T08] Kotlin：数据类
来源：http://dali.hnqzz.top/Article/details/gtferqshpe.html

data class User(val name: String, val age: Int)
来源：http://dali.cucudq.cn/Article/details/gtijhvonmd.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gtpivrtyji.html

fun String.exclaim() = this + "!"
来源：http://dali.hongshengwenyu.top/Article/details/gtuaggwsbt.html

[T10] Kotlin：默认参数
来源：http://dali.fzhhl.top/Article/details/gtohsvjbwi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.guowangkeji.top/Article/details/gtkfyfdyjm.html

[T11] Kotlin：协程
来源：http://dali.shangyingyoupin.top/Article/details/gteleqtpqg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yvedp.cn/Article/details/gtoofvkaum.html

[T12] Kotlin：解构声明
来源：http://dali.yangfankeji.com/Article/details/gtokbawvog.html

val (a, b) = Pair(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtslbdixfx.html

[T13] Kotlin：只读 Map
来源：http://dali.hnqzz.top/Article/details/gtddcputbs.html

val m = mapOf("a" to 1)
来源：http://dali.tanke756.top/Article/details/gttjhtyotr.html

[T14] Kotlin：循环
来源：http://dali.hnxiangtu.top/Article/details/gtmcjtbsll.html

for (i in 1..10) println(i)
来源：http://dali.daria6918.cn/Article/details/gtgmhzuhgx.html

[T15] Kotlin：接口
来源：http://dali.andypj.xyz/Article/details/gthugyprsy.html

interface Shape { fun area(): Double }
来源：http://dali.316326.xyz/Article/details/gtdatcavpc.html

[T16] Swift：Hello World
来源：http://dali.gzhubu.top/Article/details/gtqqhsxfkh.html

print("Hello")
来源：http://dali.sxryk.cn/Article/details/gtgrmjygpg.html

[T17] Swift：变量与常量
来源：http://dali.cdnleiting.top/Article/details/gtjhajuukp.html

var a = 1;  let b = 2
来源：http://dali.zhoulong.xyz/Article/details/gthgwtbzlp.html

[T18] Swift：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gtiggaoamz.html

"值: \(b)"
来源：http://dali.jinqigfzy.top/Article/details/gttbxxcsbc.html

[T19] Swift：可选绑定
来源：http://dali.xziqi.cn/Article/details/gtyhuxekgp.html

if let n = opt { print(n) }
来源：http://dali.fzhhl.top/Article/details/gtoygbxeos.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmpuuxte.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.guowangkeji.top/Article/details/gtfqsycctr.html

[T21] Swift：遍历
来源：http://dali.zhixingplan.top/Article/details/gtmmyesahq.html

for x in a { print(x) }
来源：http://dali.pengpengdd.cyou/Article/details/gttrbygbxt.html

[T22] Swift：字典
来源：http://dali.hnxiangtu.top/Article/details/gtzvebkaei.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.guannengcc.top/Article/details/gtneyuxqei.html

[T23] Swift：函数
来源：http://dali.sweek.top/Article/details/gtyrihndku.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ivvv.top/Article/details/gtedzsuzxd.html

[T24] Swift：闭包
来源：http://dali.sxryk.cn/Article/details/gtmoubslbd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.meibo888.top/Article/details/gtdouginpg.html

[T25] Swift：结构体
来源：http://dali.xylfe.cn/Article/details/gtvrrmwlil.html

struct P { var x: Int }
来源：http://dali.hnxiangtu.top/Article/details/gttvlnnpwy.html

[T26] Swift：类与重写
来源：http://dali.shzxlz.cn/Article/details/gtolhrsxqc.html

class A: Base { override func f() {} }
来源：http://dali.xuetiantiany.cn/Article/details/gtrkwuypji.html

[T27] Swift：错误处理
来源：http://dali.sysykeji.top/Article/details/gtsxatabhw.html

do { try f() } catch { print(error) }
来源：http://dali.chenjidiqi.icu/Article/details/gtniyevlcf.html

[T28] Swift：枚举
来源：http://dali.zhoulong.xyz/Article/details/gtsxbghgzn.html

enum Color { case red, green }
来源：http://dali.chenjidiqi.icu/Article/details/gtudfqluyt.html

[T29] Swift：guard 提前返回
来源：http://dali.0kj1m.cn/Article/details/gtxlwlwrpo.html

guard let x = opt else { return }
来源：http://dali.kuanghao11.cn/Article/details/gtazkjdeqp.html

[T30] Swift：协议
来源：http://dali.mhx1999.top/Article/details/gtlzqbmkmx.html

protocol Shape { func area() -> Double }
来源：http://dali.sufxvd.cn/Article/details/gtywacwpre.html

[T31] Lua：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtlsimgmgq.html

print("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gthkwcslmm.html

[T32] Lua：局部变量
来源：http://dali.mhx1999.top/Article/details/gtrcteldhm.html

local a = 1
来源：http://dali.ivvv.top/Article/details/gtakefushb.html

[T33] Lua：表（数组）
来源：http://dali.andypj.xyz/Article/details/gtpexooeqk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yuxming.cn/Article/details/gthlrcbume.html

[T34] Lua：遍历表
来源：http://dali.zycfv.cn/Article/details/gtwgydmzqz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhoulong.xyz/Article/details/gtffjvulvj.html

[T35] Lua：字典表
来源：http://dali.chenjidiqi.icu/Article/details/gtbgkignkw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.0kj1m.cn/Article/details/gtebjbkhso.html

[T36] Lua：函数
来源：http://dali.aibaodan.cn/Article/details/gtwimtvgjp.html

function add(a, b) return a + b end
来源：http://dali.iojbl.cn/Article/details/gtdnkuwvxa.html

[T37] Lua：字符串拼接
来源：http://dali.c1oappe.top/Article/details/gtrtngmsai.html

"a" .. "b"
来源：http://dali.guowangkeji.top/Article/details/gtbglyqyld.html

[T38] Lua：条件
来源：http://dali.smart0.xyz/Article/details/gtalslwloj.html

if x > 0 then print("正") end
来源：http://dali.fzhhl.top/Article/details/gtowtmxcte.html

[T39] Lua：模式匹配
来源：http://dali.yj20258.top/Article/details/gtuolchsyl.html

string.find(s, "%d+")
来源：http://dali.0kj1m.cn/Article/details/gtfnyedrxd.html

[T40] Lua：元表
来源：http://dali.hfpthk.cn/Article/details/gtkrguiixs.html

setmetatable({}, { __index = base })
来源：http://dali.yongpay.top/Article/details/gtnegroffr.html

[T41] Perl：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtorxchrcw.html

print "Hello\n";
来源：http://dali.guannengcc.top/Article/details/gtneqzjpgt.html

[T42] Perl：变量类型
来源：http://dali.andypj.xyz/Article/details/gtktatzbay.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jyoumei.cn/Article/details/gtlygzhkjj.html

[T43] Perl：字符串插值
来源：http://dali.xylfe.cn/Article/details/gttiyuyvwa.html

"值: $a"
来源：http://dali.bjfxy.top/Article/details/gtjodlydms.html

[T44] Perl：条件
来源：http://dali.sxryk.cn/Article/details/gtsgqxkvwz.html

if ($a > 0) { print "正"; }
来源：http://dali.yuxming.cn/Article/details/gtdqiiprbo.html

[T45] Perl：数组遍历
来源：http://dali.dashuyun.cn/Article/details/gtkljrgrxo.html

for my $x (@arr) { print $x; }
来源：http://dali.nwbrower.top/Article/details/gtuieztvuh.html

[T46] Perl：哈希操作
来源：http://dali.birdmap.top/Article/details/gtjuhvblew.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhengqikj.top/Article/details/gtoxlxszha.html

[T47] Perl：正则捕获
来源：http://dali.fengsongda.top/Article/details/gtwkfjebcx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.iojbl.cn/Article/details/gtndxvdoja.html

[T48] Perl：正则替换
来源：http://dali.sysykeji.top/Article/details/gtivvmkrhs.html

$s =~ s/old/new/g;
来源：http://dali.mhx1999.top/Article/details/gtmpsyhawi.html

[T49] Perl：函数
来源：http://dali.mhx1999.top/Article/details/gtczfpoadc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxiuwhfp.html

[T50] Perl：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacpagppv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hysaishi.cn/Article/details/gtcyjneybe.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhengqikj.top/Article/details/gtjmtlmdub.html

[T51] Scala：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtobrfhxdn.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtbpjbvled.html

[T52] Scala：变量
来源：http://dali.pengpengdd.cyou/Article/details/gtbtmkezee.html

val a = 1;  var b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvnsntbu.html

[T53] Scala：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtcpxsiizd.html

s"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gtnwxfbity.html

[T54] Scala：集合映射
来源：http://dali.c1oappe.top/Article/details/gtlebnugyv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hnqzz.top/Article/details/gtwoepxmho.html

[T55] Scala：集合过滤
来源：http://dali.redwolf501.top/Article/details/gtlrnydndf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxecdhpu.html

[T56] Scala：样例类
来源：http://dali.pycfn.com/Article/details/gtwfxtimuv.html

case class User(name: String, age: Int)
来源：http://dali.guowangkeji.top/Article/details/gtgasbvcfh.html

[T57] Scala：模式匹配
来源：http://dali.aibaodan.cn/Article/details/gtavhkchzo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hongshengwenyu.top/Article/details/gtlcemxkkc.html

[T58] Scala：函数定义
来源：http://dali.nwbrower.top/Article/details/gthzfxaqes.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.havefunace.top/Article/details/gtkzinique.html

[T59] Scala：循环
来源：http://dali.chenjidiqi.icu/Article/details/gtguuubaii.html

for (i <- 1 to 10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gtusmxpqdc.html

[T60] Scala：折叠
来源：http://dali.yangfankeji.com/Article/details/gtmkfimeei.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.daria6918.cn/Article/details/gthwzqpgvt.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtmiybbukd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.kuanghao11.cn/Article/details/gtebvcxwek.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gthotjyjid.html

[U01] Py：创建虚拟环境
来源：http://dali.bjfxy.top/Article/details/gtmqawihfm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yonumen.top/Article/details/gtcxqjovgn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dashuyun.cn/Article/details/gtgpkzdkyv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zycfv.cn/Article/details/gtlwbkfpwa.html

[U03] Py：加载 .env 配置
来源：http://dali.mhx1999.top/Article/details/gttwzoqxrr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj202588.top/Article/details/gtcphiptsv.html

[U04] Py：变量调试打印
来源：http://dali.aizwys.cn/Article/details/gtistmxmyz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jlsjyb.cn/Article/details/gtpsapvbmo.html

[U05] Py：列表去重且保序
来源：http://dali.bjfxy.top/Article/details/gtxlytqcpn.html

list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gthzneyvkp.html

[U06] Py：合并两个字典
来源：http://dali.haohaochexian.top/Article/details/gtsfqsebdo.html

{**a, **b}
来源：http://dali.nwbrower.top/Article/details/gtxicbrjqb.html

[U07] Py：反转字典键值
来源：http://dali.jlsjyb.cn/Article/details/gtbcwvlggo.html

{v: k for k, v in d.items()}
来源：http://dali.yanxiufei.cn/Article/details/gtepwfatrq.html

[U08] Py：展平二维列表
来源：http://dali.gotoacloud.top/Article/details/gtftpoizkd.html

[y for x in nested for y in x]
来源：http://dali.xinyue.icu/Article/details/gtezyhcygr.html

[U09] Py：字典取最大值的键
来源：http://dali.hywenlv.cn/Article/details/gtgkyvvruo.html

max(d, key=d.get)
来源：http://dali.sysykeji.top/Article/details/gtbnxotdkh.html

[U10] Py：按值排序字典
来源：http://dali.ppjwa.cn/Article/details/gtftodpddp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.daria6918.cn/Article/details/gtyzwthawj.html

[U11] Py：生成器表达式
来源：http://dali.hammf.cn/Article/details/gtddddddij.html

(x * 2 for x in arr)
来源：http://dali.dashuyun.cn/Article/details/gtrtxtghmt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.c1oappe.top/Article/details/gteuymqvqx.html

Counter(arr).most_common(3)
来源：http://dali.andypj.xyz/Article/details/gtofnrlbbi.html

[U13] Py：固定长度队列
来源：http://dali.xziqi.cn/Article/details/gtqinuhrch.html

deque(maxlen=10)
来源：http://dali.jyoumei.cn/Article/details/gtbvoqgmzj.html

[U14] Py：分组收集到列表
来源：http://dali.birdmap.top/Article/details/gttqswlukj.html

defaultdict(list)
来源：http://dali.bjfxy.top/Article/details/gtqjcvvtxr.html

[U15] Py：高精度计时
来源：http://dali.yj20258888.top/Article/details/gtcnmmbqbf.html

t = time.perf_counter()
来源：http://dali.andypj.xyz/Article/details/gtaeryfpmg.html

[U16] Py：命令行参数解析
来源：http://dali.zhongyouzk.top/Article/details/gtjtubbtdg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shangyingyoupin.top/Article/details/gtguzpumfp.html

[U17] Py：初始化日志
来源：http://dali.sufxvd.cn/Article/details/gtelihbglx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zdqjudy.top/Article/details/gtborhndfn.html

[U18] Py：预编译正则
来源：http://dali.guowangkeji.top/Article/details/gtkrqvaval.html

pat = re.compile(r"\d+")
来源：http://dali.haohaochexian.top/Article/details/gtaihwznge.html

[U19] Py：正则替换带回调
来源：http://dali.hywenlv.cn/Article/details/gtwrwitunv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigfzy.top/Article/details/gtsphcemhd.html

[U20] Py：缓存函数结果
来源：http://dali.guowangkeji.top/Article/details/gtoyyhutld.html

@functools.lru_cache(maxsize=None)
来源：http://dali.iojbl.cn/Article/details/gtbdmwcwxm.html

[U21] Py：自定义上下文管理器
来源：http://dali.snrcjt.cn/Article/details/gtgejbwlcd.html

@contextlib.contextmanager
来源：http://dali.zhiwuduotai.top/Article/details/gtakjisacx.html

[U22] Py：矩阵转置
来源：http://dali.ybcxt.top/Article/details/gtycdwnxsl.html

list(zip(*m))
来源：http://dali.gaohongyu789.top/Article/details/gtrplwnsca.html

[U23] Py：分块读取大文件
来源：http://dali.ydzc1.top/Article/details/gtwfntzuqc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yuxming.cn/Article/details/gtzqzqrwkw.html

[U24] Py：路径操作
来源：http://dali.meibo888.top/Article/details/gtlgesshbd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cqqwz.cn/Article/details/gtjkfmqfmu.html

[U25] Py：CSV 按字典读
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjzhafnv.html

csv.DictReader(f)
来源：http://dali.shangyingyoupin.top/Article/details/gtuxqmzuhd.html

[U26] Py：并发下载
来源：http://dali.bjfxy.top/Article/details/gtpqqgjbkb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pengpengdd.cyou/Article/details/gtshiituhm.html

[U27] Py：异步 HTTP
来源：http://dali.gotoacloud.top/Article/details/gtuuyltrdp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ybcxt.top/Article/details/gtzqesufmo.html

[U28] Py：类型别名
来源：http://dali.yanxiufei.cn/Article/details/gtbsrhutto.html

UserId = int
来源：http://dali.xuanzx.com/Article/details/gtcghwcnyt.html

[U29] Py：属性校验
来源：http://dali.yanxiufei.cn/Article/details/gtmjlfnvqj.html

@property 与 @x.setter 配合
来源：http://dali.guowangkeji.top/Article/details/gtrrzdwoql.html

[U30] Py：数据类
来源：http://dali.jinqigfzy.top/Article/details/gtxlfulmei.html

@dataclass(slots=True)
来源：http://dali.meibo888.top/Article/details/gtqpjmeizt.html

[U31] Py：单测
来源：http://dali.tanke756.top/Article/details/gtkkjfvaty.html

python -m pytest -q
来源：http://dali.nanxinkj.top/Article/details/gtosxkkbbj.html

[U32] Py：代码格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznrworcj.html

ruff format . && ruff check --fix .
来源：http://dali.chenzaomai.com/Article/details/gtqrzhnkej.html


<!-- 参考信息 -->