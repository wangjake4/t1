代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.shuidangran.top/Article/details/gtcakvmpfm.html

[S04] C：字符串复制
来源：http://dali.yanxiufei.cn/Article/details/gtfyvjdiaj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gotoacloud.top/Article/details/gtrjfdbjld.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gtzysxopnl.html

strlen(s)
来源：http://dali.cucudq.cn/Article/details/gtknwaqquc.html

[S06] C：字符串比较
来源：http://dali.yj20258.top/Article/details/gtdtdptusr.html

strcmp(a, b) == 0
来源：http://dali.gzhubu.top/Article/details/gtspnpuqov.html

[S07] C：数组遍历求和
来源：http://dali.hfpthk.cn/Article/details/gtafwpomxx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ivvv.top/Article/details/gtxavkommi.html

[S08] C：动态内存分配与释放
来源：http://dali.0kj1m.cn/Article/details/gtyleireym.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenjidiqi.icu/Article/details/gtglqnqdxk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhiwuduotai.top/Article/details/gtkjnqyuxb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhiwuduotai.top/Article/details/gtuvvxxdad.html

[S10] C：指针与解引用
来源：http://dali.wangdashe.top/Article/details/gtlbaxcues.html

int *p = &a;  *p = 5;
来源：http://dali.yvedp.cn/Article/details/gtxumhxgqt.html

[S11] C：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtwhnkobdc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hywenlv.cn/Article/details/gtvfhhlnil.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gogol.net.cn/Article/details/gtdtdifkrs.html

fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gtvgjqdkdt.html

[S12] C：写文件
来源：http://dali.mhx1999.top/Article/details/gtgwevtmro.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtutxtcdsr.html

[S13] C：宏定义
来源：http://dali.ppjwa.cn/Article/details/gtcbatteha.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenjidiqi.icu/Article/details/gtocltjocz.html

[S14] C：枚举
来源：http://dali.yj20258888.top/Article/details/gtzudktqzz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dashuyun.cn/Article/details/gthxmncbjn.html

[S15] C：类型转换
来源：http://dali.yuanzhike.top/Article/details/gthegqffiw.html

(double) a / b
来源：http://dali.jiagoushi.top/Article/details/gtvimjshbn.html

[S16] C：位操作置位
来源：http://dali.ivvv.top/Article/details/gtzcjseddr.html

x |= (1 << 3);
来源：http://dali.cqqwz.cn/Article/details/gtspauvioc.html

[S17] C：安全拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtarweiyos.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ppjwa.cn/Article/details/gtlmkyqwji.html

[S18] C：命令行参数
来源：http://dali.xuanzx.com/Article/details/gtdrqvuvjv.html

int main(int argc, char **argv)
来源：http://dali.ppjwa.cn/Article/details/gthunrxjng.html

[S19] C：快速排序
来源：http://dali.nanxuanxn.top/Article/details/gtgpzqsivh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtkhvsejgk.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gtluoecwzx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gtyeztrpws.html

[S21] C：字符类别判断
来源：http://dali.cdnleiting.top/Article/details/gtfqslgjon.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.0kj1m.cn/Article/details/gtfzsgtifp.html

[S22] C：字符串转数字
来源：http://dali.fzhhl.top/Article/details/gtzfxhcjpj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbctpivnb.html

[S23] C：随机数
来源：http://dali.jianghu66.top/Article/details/gtjlavabyq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.c1oappe.top/Article/details/gtoxjsdmga.html

[S24] C：获取本地时间
来源：http://dali.bjfxy.top/Article/details/gtoldrhsdz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aizwys.cn/Article/details/gteydydats.html

[S25] C：内存拷贝
来源：http://dali.yongpay.top/Article/details/gtwvylnmms.html

memcpy(dst, src, n);
来源：http://dali.ehwqpu.com/Article/details/gtrgbhokvz.html

[S26] C：内存清零
来源：http://dali.guowangkeji.top/Article/details/gteywruaae.html

memset(a, 0, sizeof a);
来源：http://dali.hysaishi.cn/Article/details/gtbyfzgddo.html

[S27] C：定义常量
来源：http://dali.aibaodan.cn/Article/details/gtcivfulff.html

const double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtkkzudgxq.html

[S28] C：静态变量
来源：http://dali.yuxming.cn/Article/details/gttfokloig.html

static int counter = 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtvxwtjpjp.html

[S29] C：变参函数
来源：http://dali.cucudq.cn/Article/details/gtrtmpypkj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenjidiqi.icu/Article/details/gtvkxqcttc.html

[S30] C：头文件保护
来源：http://dali.cashguo.top/Article/details/gtedckfush.html

#ifndef X_H
来源：http://dali.zhiwuduotai.top/Article/details/gtvxupyycl.html

#define X_H
来源：http://dali.hongshengwenyu.top/Article/details/gthkndknul.html

#endif
来源：http://dali.shanyushiyangtech.top/Article/details/gtawvmfyhf.html

[S31] C++：Hello World
来源：http://dali.cucudq.cn/Article/details/gtqcklnsfp.html

#include <iostream>
来源：http://dali.jinqigfzy.top/Article/details/gthnofceor.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jianghu66.top/Article/details/gtkdspyivg.html

[S32] C++：字符串
来源：http://dali.yanxiufei.cn/Article/details/gteantwhqb.html

std::string s = "hi";  s += "!";
来源：http://dali.ehwqpu.com/Article/details/gttosryudv.html

[S33] C++：vector 增删
来源：http://dali.yongpay.top/Article/details/gttrvknqmt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cashguo.top/Article/details/gtdzeqornf.html

[S34] C++：遍历 vector
来源：http://dali.sysykeji.top/Article/details/gtlzarrjmx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ydzc1.top/Article/details/gtsqnbesbl.html

[S35] C++：map
来源：http://dali.sysykeji.top/Article/details/gtzsmmjylm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtbwxfredz.html

[S36] C++：unordered_map
来源：http://dali.jiagoushi.top/Article/details/gteugdatyb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtvkiknnqq.html

[S37] C++：set
来源：http://dali.chenlongwang.top/Article/details/gtcshbpjir.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zdqjudy.top/Article/details/gtwtnroonp.html

[S38] C++：排序
来源：http://dali.guowangkeji.top/Article/details/gtekhjotep.html

std::sort(v.begin(), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gtrhjivzqb.html

[S39] C++：自定义比较器排序
来源：http://dali.jlsjyb.cn/Article/details/gtjzipovai.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgfzy.top/Article/details/gtfaclzrlw.html

[S40] C++：查找元素
来源：http://dali.hysaishi.cn/Article/details/gtpwtmtows.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cqqwz.cn/Article/details/gttmoehaic.html

[S41] C++：类与构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtviqrvwig.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenzaomai.com/Article/details/gtniitkgkn.html

[S42] C++：继承与虚函数
来源：http://dali.yanxiufei.cn/Article/details/gtfsotegfi.html

class B : public Base { public: void f() override {} };
来源：http://dali.cashguo.top/Article/details/gtfjnwbawf.html

[S43] C++：智能指针
来源：http://dali.aibaodan.cn/Article/details/gtpebxxbum.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigfzy.top/Article/details/gtwipampwr.html

[S44] C++：引用传参
来源：http://dali.vqdsnc.cn/Article/details/gtrlncxosu.html

void inc(int &x) { ++x; }
来源：http://dali.hywenlv.cn/Article/details/gtszneucdc.html

[S45] C++：lambda
来源：http://dali.zycfv.cn/Article/details/gtgcjfujyl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.316326.xyz/Article/details/gtaltkmwcq.html

[S46] C++：函数模板
来源：http://dali.hammf.cn/Article/details/gtwpziwsmo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tianlin.xyz/Article/details/gtpfihpmth.html

[S47] C++：结构化绑定遍历
来源：http://dali.hysaishi.cn/Article/details/gtrgmbplev.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ehwqpu.com/Article/details/gtfvfbxmce.html

[S48] C++：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtzjfjycat.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gttgsvilem.html

while (std::getline(in, line)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslqrzmnf.html

[S49] C++：写文件
来源：http://dali.sysykeji.top/Article/details/gtsahhrejc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigfzy.top/Article/details/gtxglnitus.html

[S50] C++：格式化数字
来源：http://dali.9152youxi.cn/Article/details/gtuxxqmlhg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtuphbbebl.html

[S51] C++：显式类型转换
来源：http://dali.yongpay.top/Article/details/gtdjqojgvj.html

static_cast<double>(a) / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzoymoyd.html

[S52] C++：const 与 noexcept
来源：http://dali.jiagoushi.top/Article/details/gtmwecvdyj.html

int size() const noexcept { return n_; }
来源：http://dali.hammf.cn/Article/details/gtjfzgxcwl.html

[S53] C++：移动语义
来源：http://dali.jyoumei.cn/Article/details/gtnebmtknb.html

std::vector<int> w = std::move(v);
来源：http://dali.9152youxi.cn/Article/details/gtadamhgpc.html

[S54] C++：异常处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpzldlxd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fzhhl.top/Article/details/gtwvporyfn.html

[S55] C++：结构化绑定
来源：http://dali.xinyue.icu/Article/details/gtdbihasls.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daxiang520.top/Article/details/gtbjwmxtro.html

[S56] C++：optional
来源：http://dali.yj20258888.top/Article/details/gtapihwhyc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cashguo.top/Article/details/gttpnbijyf.html

[S57] C++：编译期常量
来源：http://dali.guannengcc.top/Article/details/gtrhaullng.html

constexpr int N = 10;
来源：http://dali.yonumen.top/Article/details/gtiotmagcs.html

[S58] C++：命名空间
来源：http://dali.vqdsnc.cn/Article/details/gtdynimsei.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnxiangtu.top/Article/details/gttwqxeqxt.html

[S59] C++：静态断言
来源：http://dali.nanxuanxn.top/Article/details/gtymqubcgd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hammf.cn/Article/details/gtkqumntxs.html

[S60] C++：遍历并删除元素
来源：http://dali.fengsongda.top/Article/details/gtvommlzsb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtrnxjgjac.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtozionfxs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gtynydluye.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtwlusouyz.html

[T01] Kotlin：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtrumbxgzf.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gtbcnvmrvh.html

[T02] Kotlin：变量
来源：http://dali.andypj.xyz/Article/details/gtzhofpymz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cashguo.top/Article/details/gtbtspyosp.html

[T03] Kotlin：字符串模板
来源：http://dali.redwolf501.top/Article/details/gtyflwoehq.html

"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gtzczmypht.html

[T04] Kotlin：空安全
来源：http://dali.sysykeji.top/Article/details/gtvdvtkgun.html

val n: String? = null;  n?.length
来源：http://dali.9152youxi.cn/Article/details/gtzhfbnpme.html

[T05] Kotlin：when 表达式
来源：http://dali.yangfankeji.com/Article/details/gtgfqahpsb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.bjfxy.top/Article/details/gthmjxrghx.html

[T06] Kotlin：集合映射
来源：http://dali.gzhubu.top/Article/details/gtcojcilan.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gzhubu.top/Article/details/gtoruazpqm.html

[T07] Kotlin：集合过滤
来源：http://dali.tian-w.cn/Article/details/gttrwoaetp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gtitjhchwj.html

[T08] Kotlin：数据类
来源：http://dali.yonumen.top/Article/details/gtmrfcxkvy.html

data class User(val name: String, val age: Int)
来源：http://dali.daria6918.cn/Article/details/gtndywtczs.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gtdleeaval.html

fun String.exclaim() = this + "!"
来源：http://dali.haohaochexian.top/Article/details/gtjrqvfvqg.html

[T10] Kotlin：默认参数
来源：http://dali.daxiang520.top/Article/details/gtzxrrmjws.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gtnmugtigt.html

[T11] Kotlin：协程
来源：http://dali.gogol.net.cn/Article/details/gtsghppyjx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gotoacloud.top/Article/details/gtaglhashy.html

[T12] Kotlin：解构声明
来源：http://dali.nwbrower.top/Article/details/gteejajpik.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj20258.top/Article/details/gtdcsgmtqg.html

[T13] Kotlin：只读 Map
来源：http://dali.sufxvd.cn/Article/details/gtzkweksjj.html

val m = mapOf("a" to 1)
来源：http://dali.nanxuanxn.top/Article/details/gtgtswdqyi.html

[T14] Kotlin：循环
来源：http://dali.gaohongyu789.top/Article/details/gtnhisflmy.html

for (i in 1..10) println(i)
来源：http://dali.mhx1999.top/Article/details/gtvbrwswta.html

[T15] Kotlin：接口
来源：http://dali.cucudq.cn/Article/details/gtrhplpthy.html

interface Shape { fun area(): Double }
来源：http://dali.andypj.xyz/Article/details/gtlldaacak.html

[T16] Swift：Hello World
来源：http://dali.xinyue.icu/Article/details/gtsddsdhej.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtwwowgnfg.html

[T17] Swift：变量与常量
来源：http://dali.yuanzhike.top/Article/details/gtsvgldqvu.html

var a = 1;  let b = 2
来源：http://dali.smart0.xyz/Article/details/gtfpsmlmvu.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gtjnowhpkx.html

"值: \(b)"
来源：http://dali.guannengcc.top/Article/details/gtnzffbott.html

[T19] Swift：可选绑定
来源：http://dali.jinqigufen.top/Article/details/gtdgfgrjbu.html

if let n = opt { print(n) }
来源：http://dali.zhiwuduotai.top/Article/details/gtcnbudxge.html

[T20] Swift：数组操作
来源：http://dali.cqqwz.cn/Article/details/gtiwatlryk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.snrcjt.cn/Article/details/gtecclzvyn.html

[T21] Swift：遍历
来源：http://dali.zhixingplan.top/Article/details/gtyzsykpqp.html

for x in a { print(x) }
来源：http://dali.hongshengwenyu.top/Article/details/gtvagnkrrd.html

[T22] Swift：字典
来源：http://dali.hammf.cn/Article/details/gtovlymugr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fzhhl.top/Article/details/gthizycrvv.html

[T23] Swift：函数
来源：http://dali.316326.xyz/Article/details/gtjkokjurj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gtltlypqyz.html

[T24] Swift：闭包
来源：http://dali.hfpthk.cn/Article/details/gtbpnmchjn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.smart0.xyz/Article/details/gtecpggzzw.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazbmafsy.html

struct P { var x: Int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepnslcrs.html

[T26] Swift：类与重写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuvipidm.html

class A: Base { override func f() {} }
来源：http://dali.chenjidiqi.icu/Article/details/gtgwceztnq.html

[T27] Swift：错误处理
来源：http://dali.zhiwuduotai.top/Article/details/gtknxsbjaw.html

do { try f() } catch { print(error) }
来源：http://dali.tanke756.top/Article/details/gtyrcetvjn.html

[T28] Swift：枚举
来源：http://dali.fzhhl.top/Article/details/gtlyakggnl.html

enum Color { case red, green }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxirtdpb.html

[T29] Swift：guard 提前返回
来源：http://dali.wangshuangyany.cn/Article/details/gtntptzfvz.html

guard let x = opt else { return }
来源：http://dali.zhoulong.xyz/Article/details/gtjxfdkkpc.html

[T30] Swift：协议
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiehgtibi.html

protocol Shape { func area() -> Double }
来源：http://dali.316326.xyz/Article/details/gtfktopnpt.html

[T31] Lua：Hello World
来源：http://dali.bjfxy.top/Article/details/gtistclvmn.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gtafwguwad.html

[T32] Lua：局部变量
来源：http://dali.jqgufenzy.top/Article/details/gtbydpnaps.html

local a = 1
来源：http://dali.hnxiangtu.top/Article/details/gthqjjswvq.html

[T33] Lua：表（数组）
来源：http://dali.jlsjyb.cn/Article/details/gtstaxedkv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhoulong.xyz/Article/details/gtfbdtqepy.html

[T34] Lua：遍历表
来源：http://dali.xinyue.icu/Article/details/gtskvthrtb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpzzhbqb.html

[T35] Lua：字典表
来源：http://dali.feifeiyinyue.top/Article/details/gthvjgzpgc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.c1oappe.top/Article/details/gtjcqjnkzc.html

[T36] Lua：函数
来源：http://dali.nanxinkj.top/Article/details/gtxbkxegxa.html

function add(a, b) return a + b end
来源：http://dali.zhongyouzk.top/Article/details/gtoydizirr.html

[T37] Lua：字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gtnbtjpcff.html

"a" .. "b"
来源：http://dali.chenjidiqi.icu/Article/details/gttvtwliuj.html

[T38] Lua：条件
来源：http://dali.gogol.net.cn/Article/details/gtmrtvbwkk.html

if x > 0 then print("正") end
来源：http://dali.yanxiufei.cn/Article/details/gtvwotbqhx.html

[T39] Lua：模式匹配
来源：http://dali.jinqigufen.top/Article/details/gtsvhdszjc.html

string.find(s, "%d+")
来源：http://dali.cucudq.cn/Article/details/gtfdaldnte.html

[T40] Lua：元表
来源：http://dali.dashuyun.cn/Article/details/gtofogwncu.html

setmetatable({}, { __index = base })
来源：http://dali.yvedp.cn/Article/details/gtzfpvyjms.html

[T41] Perl：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtrekzmcar.html

print "Hello\n";
来源：http://dali.xziqi.cn/Article/details/gtykkgliwi.html

[T42] Perl：变量类型
来源：http://dali.sweek.top/Article/details/gtdmwmerue.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hywenlv.cn/Article/details/gtyllthbni.html

[T43] Perl：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gttvmzvykq.html

"值: $a"
来源：http://dali.fengsongda.top/Article/details/gtxomznevs.html

[T44] Perl：条件
来源：http://dali.zhiwuduotai.top/Article/details/gtzwboqzcv.html

if ($a > 0) { print "正"; }
来源：http://dali.hammf.cn/Article/details/gtkucmbpef.html

[T45] Perl：数组遍历
来源：http://dali.andypj.xyz/Article/details/gtpzjvxhqm.html

for my $x (@arr) { print $x; }
来源：http://dali.cqqwz.cn/Article/details/gtigmurotr.html

[T46] Perl：哈希操作
来源：http://dali.guannengcc.top/Article/details/gtudbqydqo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ehwqpu.com/Article/details/gtkwrcmogz.html

[T47] Perl：正则捕获
来源：http://dali.xuetiantiany.cn/Article/details/gtqmtpknib.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.quarkkingdee.top/Article/details/gtxaazhnra.html

[T48] Perl：正则替换
来源：http://dali.xinyue.icu/Article/details/gtzxpreodr.html

$s =~ s/old/new/g;
来源：http://dali.316326.xyz/Article/details/gttvegizyw.html

[T49] Perl：函数
来源：http://dali.zhongyouzk.top/Article/details/gtjfwwrzvj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gtwktsqfrx.html

[T50] Perl：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtcazixxzj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jyoumei.cn/Article/details/gtqzvcyakw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jianghu66.top/Article/details/gtmemkdywy.html

[T51] Scala：Hello World
来源：http://dali.yonumen.top/Article/details/gtvfgrnqet.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gtywfrenzt.html

[T52] Scala：变量
来源：http://dali.hywenlv.cn/Article/details/gtnacarxka.html

val a = 1;  var b = 2
来源：http://dali.smart0.xyz/Article/details/gtvkwzcykj.html

[T53] Scala：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtvdbolgfa.html

s"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gtsiqanhhq.html

[T54] Scala：集合映射
来源：http://dali.cdnleiting.top/Article/details/gtsrgvkjqs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hnxiangtu.top/Article/details/gtycizvftc.html

[T55] Scala：集合过滤
来源：http://dali.yuxming.cn/Article/details/gtggehtesf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xinyue.icu/Article/details/gtngnsdojl.html

[T56] Scala：样例类
来源：http://dali.zycfv.cn/Article/details/gtaufwizsf.html

case class User(name: String, age: Int)
来源：http://dali.chenlongwang.top/Article/details/gtczcplwlg.html

[T57] Scala：模式匹配
来源：http://dali.ivvv.top/Article/details/gtjpzlirvy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jiagoushi.top/Article/details/gtmguiruuo.html

[T58] Scala：函数定义
来源：http://dali.hnqzz.top/Article/details/gtiuxqaayj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yonumen.top/Article/details/gtdnrvrfvg.html

[T59] Scala：循环
来源：http://dali.vqdsnc.cn/Article/details/gtymktmkwj.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuanzx.com/Article/details/gtqthuetux.html

[T60] Scala：折叠
来源：http://dali.wangdashe.top/Article/details/gttszabdgr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.9152youxi.cn/Article/details/gtvhwlzbtn.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtoxzxwsdr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gtmjbarjya.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtcoekkxtc.html

[U01] Py：创建虚拟环境
来源：http://dali.aibaodan.cn/Article/details/gthtljotxy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jlsjyb.cn/Article/details/gtuwtwtsoa.html

[U02] Py：导出 / 安装依赖
来源：http://dali.pycfn.com/Article/details/gtyrbtwjec.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xinyue.icu/Article/details/gtpauazhcq.html

[U03] Py：加载 .env 配置
来源：http://dali.shangyingyoupin.top/Article/details/gthlqojpcn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.andypj.xyz/Article/details/gtxnggondz.html

[U04] Py：变量调试打印
来源：http://dali.gaohongyu789.top/Article/details/gtgcdmhypm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigufen.top/Article/details/gtooqalvks.html

[U05] Py：列表去重且保序
来源：http://dali.ybcxt.top/Article/details/gtnyhcdpna.html

list(dict.fromkeys(arr))
来源：http://dali.kuanghao11.cn/Article/details/gtqfosssaq.html

[U06] Py：合并两个字典
来源：http://dali.daria6918.cn/Article/details/gtufbmrkrf.html

{**a, **b}
来源：http://dali.9152youxi.cn/Article/details/gteydzqzgl.html

[U07] Py：反转字典键值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqjsnadj.html

{v: k for k, v in d.items()}
来源：http://dali.kuanghao11.cn/Article/details/gtjhrrbylm.html

[U08] Py：展平二维列表
来源：http://dali.cdnleiting.top/Article/details/gtxxiidxeh.html

[y for x in nested for y in x]
来源：http://dali.yueranfly.top/Article/details/gtqpqtocbl.html

[U09] Py：字典取最大值的键
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwezkmzy.html

max(d, key=d.get)
来源：http://dali.hammf.cn/Article/details/gtbbvbiffa.html

[U10] Py：按值排序字典
来源：http://dali.sweek.top/Article/details/gticzazfsa.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jlsjyb.cn/Article/details/gthaevkaiw.html

[U11] Py：生成器表达式
来源：http://dali.jiagoushi.top/Article/details/gtkacsopjr.html

(x * 2 for x in arr)
来源：http://dali.yj202588.top/Article/details/gtcebqktxj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jqgufenzy.top/Article/details/gtbxqfxqoo.html

Counter(arr).most_common(3)
来源：http://dali.wangdashe.top/Article/details/gtggcfbgti.html

[U13] Py：固定长度队列
来源：http://dali.fzhhl.top/Article/details/gtqyvieabl.html

deque(maxlen=10)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqsjgmwm.html

[U14] Py：分组收集到列表
来源：http://dali.chenjidiqi.icu/Article/details/gtksdcnxci.html

defaultdict(list)
来源：http://dali.mhx1999.top/Article/details/gtwpptjgdf.html

[U15] Py：高精度计时
来源：http://dali.bjfxy.top/Article/details/gtebobvbou.html

t = time.perf_counter()
来源：http://dali.tian-w.cn/Article/details/gtcigviqti.html

[U16] Py：命令行参数解析
来源：http://dali.svipenyu.cn/Article/details/gtaynysogm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yvedp.cn/Article/details/gtbrbabffp.html

[U17] Py：初始化日志
来源：http://dali.jqgufenzy.top/Article/details/gtztiellxf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinqigufen.top/Article/details/gtdnfgrzcq.html

[U18] Py：预编译正则
来源：http://dali.smart0.xyz/Article/details/gtyeptjyqo.html

pat = re.compile(r"\d+")
来源：http://dali.smart0.xyz/Article/details/gtvfeouelu.html

[U19] Py：正则替换带回调
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxekhfss.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tian-w.cn/Article/details/gtsugfsyzo.html

[U20] Py：缓存函数结果
来源：http://dali.yuanzhike.top/Article/details/gtjqeqscek.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hammf.cn/Article/details/gtgdetqxzu.html

[U21] Py：自定义上下文管理器
来源：http://dali.cdnleiting.top/Article/details/gtabddbvxk.html

@contextlib.contextmanager
来源：http://dali.zhiwuduotai.top/Article/details/gtejnrdtrv.html

[U22] Py：矩阵转置
来源：http://dali.fengsongda.top/Article/details/gtykrekgwe.html

list(zip(*m))
来源：http://dali.hongshengwenyu.top/Article/details/gtiugtpqpl.html

[U23] Py：分块读取大文件
来源：http://dali.xuanzx.com/Article/details/gtnzzvqwjk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhongyouzk.top/Article/details/gtyqzgmtil.html

[U24] Py：路径操作
来源：http://dali.zdqjudy.top/Article/details/gtmprwqxvh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gtxebdqdym.html

[U25] Py：CSV 按字典读
来源：http://dali.316326.xyz/Article/details/gtunjxziat.html

csv.DictReader(f)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmfnrkqh.html

[U26] Py：并发下载
来源：http://dali.gogol.net.cn/Article/details/gtajnjshrs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ybcxt.top/Article/details/gtnaowscvw.html


<!-- 参考信息 -->