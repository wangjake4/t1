代发 wailian999

strlen(s)
来源：http://dali.kuanghao11.cn/Article/details/gtpnkjozdj.html

[S06] C：字符串比较
来源：http://dali.tian-w.cn/Article/details/gtgihukhbe.html

strcmp(a, b) == 0
来源：http://dali.dashuyun.cn/Article/details/gtfsxpkjdd.html

[S07] C：数组遍历求和
来源：http://dali.jqgufenzy.top/Article/details/gtgxqjihpf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shangyingyoupin.top/Article/details/gtqfyditgf.html

[S08] C：动态内存分配与释放
来源：http://dali.wangshuangyany.cn/Article/details/gtcfkwmwcs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.iojbl.cn/Article/details/gtxpjincfr.html

[S09] C：结构体定义与初始化
来源：http://dali.ydzc1.top/Article/details/gtlfbcknsk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daxiang520.top/Article/details/gtgedhonbk.html

[S10] C：指针与解引用
来源：http://dali.xziqi.cn/Article/details/gtdtxyneqm.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258.top/Article/details/gtpdoyrafu.html

[S11] C：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtjtyodbmc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hysaishi.cn/Article/details/gtedfmfvmj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gzhubu.top/Article/details/gtqdobfibe.html

fclose(f);
来源：http://dali.daxiang520.top/Article/details/gttdntvoxx.html

[S12] C：写文件
来源：http://dali.nwbrower.top/Article/details/gtxlvqyorz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gtakxyabnl.html

[S13] C：宏定义
来源：http://dali.xylfe.cn/Article/details/gtvnhpxtsh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cdnleiting.top/Article/details/gtfurywmag.html

[S14] C：枚举
来源：http://dali.ppjwa.cn/Article/details/gtoalkxukb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258888.top/Article/details/gtuhsnveju.html

[S15] C：类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtrigwjlre.html

(double) a / b
来源：http://dali.hnqzz.top/Article/details/gtlyukuwey.html

[S16] C：位操作置位
来源：http://dali.gogol.net.cn/Article/details/gtblsaxyay.html

x |= (1 << 3);
来源：http://dali.ppjwa.cn/Article/details/gteqivskyy.html

[S17] C：安全拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtkqbealog.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgfzy.top/Article/details/gtffewlsza.html

[S18] C：命令行参数
来源：http://dali.jinqigufen.top/Article/details/gtqfitnpdj.html

int main(int argc, char **argv)
来源：http://dali.bjfxy.top/Article/details/gtoghcyrda.html

[S19] C：快速排序
来源：http://dali.hongshengwenyu.top/Article/details/gtmlpotloe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gtwksvpamt.html

[S20] C：二分查找
来源：http://dali.cucudq.cn/Article/details/gtkwmqsjdi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sufxvd.cn/Article/details/gtoruyuayg.html

[S21] C：字符类别判断
来源：http://dali.hammf.cn/Article/details/gtqwwfjxnk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuetiantiany.cn/Article/details/gtqstonrwr.html

[S22] C：字符串转数字
来源：http://dali.yonumen.top/Article/details/gtcpjezfwt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhengqikj.top/Article/details/gtofcipvlv.html

[S23] C：随机数
来源：http://dali.daria6918.cn/Article/details/gtgwlturcd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangdashe.top/Article/details/gtgbepovbr.html

[S24] C：获取本地时间
来源：http://dali.chenlongwang.top/Article/details/gtpzqmlbdf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jqgufenzy.top/Article/details/gtpeygybyv.html

[S25] C：内存拷贝
来源：http://dali.sysykeji.top/Article/details/gtqjpziswr.html

memcpy(dst, src, n);
来源：http://dali.wangshuangyany.cn/Article/details/gtjphyifjy.html

[S26] C：内存清零
来源：http://dali.mhx1999.top/Article/details/gttuvmhpfz.html

memset(a, 0, sizeof a);
来源：http://dali.cheryme.top/Article/details/gtgvuklpgq.html

[S27] C：定义常量
来源：http://dali.tianlin.xyz/Article/details/gtjdefojdg.html

const double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtftbsewjz.html

[S28] C：静态变量
来源：http://dali.gogol.net.cn/Article/details/gteoxmwkoe.html

static int counter = 0;
来源：http://dali.hysaishi.cn/Article/details/gtbydanjby.html

[S29] C：变参函数
来源：http://dali.gogol.net.cn/Article/details/gtuctwkeky.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfibzbqlf.html

[S30] C：头文件保护
来源：http://dali.sweek.top/Article/details/gttwysegvg.html

#ifndef X_H
来源：http://dali.sysykeji.top/Article/details/gtkwazhqov.html

#define X_H
来源：http://dali.chenjidiqi.icu/Article/details/gtkicqchub.html

#endif
来源：http://dali.tanke756.top/Article/details/gtjzsarbll.html

[S31] C++：Hello World
来源：http://dali.aizwys.cn/Article/details/gtgubnwmok.html

#include <iostream>
来源：http://dali.haohaochexian.top/Article/details/gtvggclwom.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnxiangtu.top/Article/details/gtbnilwbtm.html

[S32] C++：字符串
来源：http://dali.9152youxi.cn/Article/details/gtjqnwrjua.html

std::string s = "hi";  s += "!";
来源：http://dali.gaohongyu789.top/Article/details/gtecldsepn.html

[S33] C++：vector 增删
来源：http://dali.hammf.cn/Article/details/gtzrzsmnnr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sufxvd.cn/Article/details/gtrfyoxlwm.html

[S34] C++：遍历 vector
来源：http://dali.wangdashe.top/Article/details/gtgywbyfhp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigfzy.top/Article/details/gtymaclcjr.html

[S35] C++：map
来源：http://dali.dashuyun.cn/Article/details/gtplkhnpco.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtibxfezox.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gtbzjcnngt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gthwskoiuq.html

[S37] C++：set
来源：http://dali.hywenlv.cn/Article/details/gtomullbuv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigfzy.top/Article/details/gtyzpgazif.html

[S38] C++：排序
来源：http://dali.feifeiyinyue.top/Article/details/gtpctppspg.html

std::sort(v.begin(), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gtokvkkmtq.html

[S39] C++：自定义比较器排序
来源：http://dali.meibo888.top/Article/details/gtdwfifuph.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.316326.xyz/Article/details/gtzqpmyfnc.html

[S40] C++：查找元素
来源：http://dali.jlsjyb.cn/Article/details/gtofdahtzy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pycfn.com/Article/details/gtbozekkhh.html

[S41] C++：类与构造函数
来源：http://dali.svipenyu.cn/Article/details/gtzbnubctj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgfzy.top/Article/details/gtqnrezuzt.html

[S42] C++：继承与虚函数
来源：http://dali.aizwys.cn/Article/details/gtujfvcewx.html

class B : public Base { public: void f() override {} };
来源：http://dali.vqdsnc.cn/Article/details/gtybvtsgit.html

[S43] C++：智能指针
来源：http://dali.xuanzx.com/Article/details/gtcekygxnb.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnxiangtu.top/Article/details/gtlvazzlgc.html

[S44] C++：引用传参
来源：http://dali.smart0.xyz/Article/details/gtsvirjovu.html

void inc(int &x) { ++x; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcrbympfv.html

[S45] C++：lambda
来源：http://dali.chenlongwang.top/Article/details/gtpcmzwxah.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gotoacloud.top/Article/details/gtvsnuuarq.html

[S46] C++：函数模板
来源：http://dali.9152youxi.cn/Article/details/gtgjlgxqko.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ehwqpu.com/Article/details/gtcodlzduz.html

[S47] C++：结构化绑定遍历
来源：http://dali.yangfankeji.com/Article/details/gtsxrmmtcg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gtqwhxgmgk.html

[S48] C++：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtyyokrzsk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sufxvd.cn/Article/details/gtburatwve.html

while (std::getline(in, line)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibxnwczh.html

[S49] C++：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljoqnfzo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sxryk.cn/Article/details/gtgjmcvgnu.html

[S50] C++：格式化数字
来源：http://dali.hysaishi.cn/Article/details/gtpndebwhp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtnmqzkcgy.html

[S51] C++：显式类型转换
来源：http://dali.xziqi.cn/Article/details/gtlllsjqtq.html

static_cast<double>(a) / b
来源：http://dali.yangfankeji.com/Article/details/gtbmhsscoj.html

[S52] C++：const 与 noexcept
来源：http://dali.jiagoushi.top/Article/details/gtctyfnotd.html

int size() const noexcept { return n_; }
来源：http://dali.jqgufenzy.top/Article/details/gtovqsgmlh.html

[S53] C++：移动语义
来源：http://dali.yuanzhike.top/Article/details/gtsuuxrnjx.html

std::vector<int> w = std::move(v);
来源：http://dali.daria6918.cn/Article/details/gtspjusldu.html

[S54] C++：异常处理
来源：http://dali.yvedp.cn/Article/details/gtpivtshoz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tian-w.cn/Article/details/gtkrkxjdee.html

[S55] C++：结构化绑定
来源：http://dali.xuanzx.com/Article/details/gtbsfdfbrn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.vqdsnc.cn/Article/details/gtouknatxs.html

[S56] C++：optional
来源：http://dali.yueranfly.top/Article/details/gtifwarfzy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yonumen.top/Article/details/gtpmmwvpyj.html

[S57] C++：编译期常量
来源：http://dali.yvedp.cn/Article/details/gtdlrbjlls.html

constexpr int N = 10;
来源：http://dali.yj20258888.top/Article/details/gtjpitsyoy.html

[S58] C++：命名空间
来源：http://dali.redwolf501.top/Article/details/gtjrahkuzp.html

namespace ns { int f() { return 1; } }
来源：http://dali.cashguo.top/Article/details/gthwbrlyyo.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gtkkfmyjpd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tanke756.top/Article/details/gtbehewzqy.html

[S60] C++：遍历并删除元素
来源：http://dali.zhengqikj.top/Article/details/gtpomztqcr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangdashe.top/Article/details/gtyheybeki.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtltasgaix.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhengqikj.top/Article/details/gtqkpmbisw.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtbqibnuch.html

[T01] Kotlin：Hello World
来源：http://dali.cashguo.top/Article/details/gthamdxqhi.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gtkvaryhiu.html

[T02] Kotlin：变量
来源：http://dali.feifeiyinyue.top/Article/details/gtsxtasydf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.316326.xyz/Article/details/gtgkhsnhte.html

[T03] Kotlin：字符串模板
来源：http://dali.yj202588.top/Article/details/gtuduppdan.html

"值: $b"
来源：http://dali.birdmap.top/Article/details/gtpaavnspi.html

[T04] Kotlin：空安全
来源：http://dali.chenzaomai.com/Article/details/gtcakrtyqy.html

val n: String? = null;  n?.length
来源：http://dali.nanxinkj.top/Article/details/gthtefkxjg.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gtwurbsyvw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zycfv.cn/Article/details/gtmszjyhvr.html

[T06] Kotlin：集合映射
来源：http://dali.tian-w.cn/Article/details/gtupnuezgb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtlffkukuf.html

[T07] Kotlin：集合过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtsjivfvzx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.0kj1m.cn/Article/details/gtmhujtxoe.html

[T08] Kotlin：数据类
来源：http://dali.nanxuanxn.top/Article/details/gtathwgbux.html

data class User(val name: String, val age: Int)
来源：http://dali.yongpay.top/Article/details/gtuaosptgb.html

[T09] Kotlin：扩展函数
来源：http://dali.ivvv.top/Article/details/gttozyfuzs.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxuanxn.top/Article/details/gtnnnyezei.html

[T10] Kotlin：默认参数
来源：http://dali.xziqi.cn/Article/details/gtaftgedpk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ydzc1.top/Article/details/gtibogtemo.html

[T11] Kotlin：协程
来源：http://dali.fengsongda.top/Article/details/gtbwlbrrvl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhixingplan.top/Article/details/gtabyllcov.html

[T12] Kotlin：解构声明
来源：http://dali.xinyue.icu/Article/details/gttdfngidy.html

val (a, b) = Pair(1, 2)
来源：http://dali.316326.xyz/Article/details/gtohscgahd.html

[T13] Kotlin：只读 Map
来源：http://dali.snrcjt.cn/Article/details/gtvuiwovkm.html

val m = mapOf("a" to 1)
来源：http://dali.zhixingplan.top/Article/details/gtvxzwwxre.html

[T14] Kotlin：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbwngqxeu.html

for (i in 1..10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtrrfahzai.html

[T15] Kotlin：接口
来源：http://dali.yvedp.cn/Article/details/gtazjnntiw.html

interface Shape { fun area(): Double }
来源：http://dali.svipenyu.cn/Article/details/gtkdwuwhtk.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsxewyur.html

print("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtnlphghwz.html

[T17] Swift：变量与常量
来源：http://dali.cheryme.top/Article/details/gtnkhlggyc.html

var a = 1;  let b = 2
来源：http://dali.meibo888.top/Article/details/gtrfilxtzy.html

[T18] Swift：字符串插值
来源：http://dali.sweek.top/Article/details/gtwszaanbd.html

"值: \(b)"
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuexsain.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gtiymowusd.html

if let n = opt { print(n) }
来源：http://dali.daxiang520.top/Article/details/gteoomecbs.html

[T20] Swift：数组操作
来源：http://dali.yonumen.top/Article/details/gtlohrjnxf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.meibo888.top/Article/details/gtnwgjtscu.html

[T21] Swift：遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqcqxsxz.html

for x in a { print(x) }
来源：http://dali.vqdsnc.cn/Article/details/gtdqcniqnf.html

[T22] Swift：字典
来源：http://dali.hfpthk.cn/Article/details/gtfbzupjxd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fzhhl.top/Article/details/gtzuewqjnk.html

[T23] Swift：函数
来源：http://dali.shangyingyoupin.top/Article/details/gtyruneszb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gtpaibdlgq.html

[T24] Swift：闭包
来源：http://dali.cdnleiting.top/Article/details/gtarylilhx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zycfv.cn/Article/details/gtjiytsspz.html

[T25] Swift：结构体
来源：http://dali.ivvv.top/Article/details/gtnnfdcsfr.html

struct P { var x: Int }
来源：http://dali.fzhhl.top/Article/details/gtzbejblhy.html

[T26] Swift：类与重写
来源：http://dali.birdmap.top/Article/details/gtrgtfsjxi.html

class A: Base { override func f() {} }
来源：http://dali.zhengqikj.top/Article/details/gtofftppfn.html

[T27] Swift：错误处理
来源：http://dali.chenlongwang.top/Article/details/gtlumiivot.html

do { try f() } catch { print(error) }
来源：http://dali.gaohongyu789.top/Article/details/gtlwgsryer.html

[T28] Swift：枚举
来源：http://dali.iojbl.cn/Article/details/gtbjabcxlq.html

enum Color { case red, green }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxncsxck.html

[T29] Swift：guard 提前返回
来源：http://dali.jiagoushi.top/Article/details/gtorjqjdth.html

guard let x = opt else { return }
来源：http://dali.jinqigfzy.top/Article/details/gtkhdlybvg.html

[T30] Swift：协议
来源：http://dali.zhengqikj.top/Article/details/gtrcwbhbib.html

protocol Shape { func area() -> Double }
来源：http://dali.daria6918.cn/Article/details/gtgdizorrj.html

[T31] Lua：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtfnpfgfjx.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtrurgtqwq.html

[T32] Lua：局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtgbtndtey.html

local a = 1
来源：http://dali.daria6918.cn/Article/details/gtsawtxtfb.html

[T33] Lua：表（数组）
来源：http://dali.yj20258.top/Article/details/gtxjjhyjym.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yueranfly.top/Article/details/gtdjlamhep.html

[T34] Lua：遍历表
来源：http://dali.jqgufenzy.top/Article/details/gtzgpbgbek.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgmwzpuf.html

[T35] Lua：字典表
来源：http://dali.haohaochexian.top/Article/details/gtkewqysjk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guannengcc.top/Article/details/gtprdycrkm.html

[T36] Lua：函数
来源：http://dali.ivvv.top/Article/details/gtlsvofeza.html

function add(a, b) return a + b end
来源：http://dali.fengsongda.top/Article/details/gtxrvwzgoc.html

[T37] Lua：字符串拼接
来源：http://dali.yonumen.top/Article/details/gtjwuocrab.html

"a" .. "b"
来源：http://dali.nwbrower.top/Article/details/gtbognsapc.html

[T38] Lua：条件
来源：http://dali.cheryme.top/Article/details/gtwwstwevo.html

if x > 0 then print("正") end
来源：http://dali.0kj1m.cn/Article/details/gtqfkayhyp.html

[T39] Lua：模式匹配
来源：http://dali.cheryme.top/Article/details/gtaevabahq.html

string.find(s, "%d+")
来源：http://dali.hammf.cn/Article/details/gtbcxsovig.html

[T40] Lua：元表
来源：http://dali.guowangkeji.top/Article/details/gtobtaigqm.html

setmetatable({}, { __index = base })
来源：http://dali.cqqwz.cn/Article/details/gtjlxsahjs.html

[T41] Perl：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtqxwgczks.html

print "Hello\n";
来源：http://dali.gaohongyu789.top/Article/details/gtwsoprrbr.html

[T42] Perl：变量类型
来源：http://dali.yongpay.top/Article/details/gtomwixbet.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.redwolf501.top/Article/details/gtceogiedv.html

[T43] Perl：字符串插值
来源：http://dali.redwolf501.top/Article/details/gtrnqdxekc.html

"值: $a"
来源：http://dali.gogol.net.cn/Article/details/gtchmhrkfn.html

[T44] Perl：条件
来源：http://dali.chenjidiqi.icu/Article/details/gtcfnurdyd.html

if ($a > 0) { print "正"; }
来源：http://dali.sxryk.cn/Article/details/gtrvjaweyt.html

[T45] Perl：数组遍历
来源：http://dali.pycfn.com/Article/details/gtprtbdkgq.html

for my $x (@arr) { print $x; }
来源：http://dali.nanxinkj.top/Article/details/gtorckhlyh.html

[T46] Perl：哈希操作
来源：http://dali.gaohongyu789.top/Article/details/gteuwqookn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guannengcc.top/Article/details/gtslctmezc.html

[T47] Perl：正则捕获
来源：http://dali.feifeiyinyue.top/Article/details/gtevzxotib.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.aizwys.cn/Article/details/gtqbhfveci.html

[T48] Perl：正则替换
来源：http://dali.tanke756.top/Article/details/gtgxhczwek.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrfnotrx.html

[T49] Perl：函数
来源：http://dali.c1oappe.top/Article/details/gtmlsccsce.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtcwhocpro.html

[T50] Perl：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtisdqoqmj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnrwumwy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmwfhryw.html

[T51] Scala：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtqkfrimrg.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gtjsfcfswa.html

[T52] Scala：变量
来源：http://dali.birdmap.top/Article/details/gtbcdaejda.html

val a = 1;  var b = 2
来源：http://dali.hfpthk.cn/Article/details/gtoohwkstk.html

[T53] Scala：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtjmucssiz.html

s"值: $b"
来源：http://dali.yj20258.top/Article/details/gtxdverzbr.html

[T54] Scala：集合映射
来源：http://dali.bjfxy.top/Article/details/gtzytztelu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shuidangran.top/Article/details/gtwnuaookc.html

[T55] Scala：集合过滤
来源：http://dali.yongpay.top/Article/details/gtvflmskqs.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xziqi.cn/Article/details/gtqsauldyg.html

[T56] Scala：样例类
来源：http://dali.daria6918.cn/Article/details/gtgguvlmzq.html

case class User(name: String, age: Int)
来源：http://dali.yuanzhike.top/Article/details/gtgumzutch.html

[T57] Scala：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gtjesgqhde.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhengqikj.top/Article/details/gtzpibwrqf.html

[T58] Scala：函数定义
来源：http://dali.zhengqikj.top/Article/details/gtwslseeev.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gthnidyilp.html

[T59] Scala：循环
来源：http://dali.birdmap.top/Article/details/gtpmqmmueq.html

for (i <- 1 to 10) println(i)
来源：http://dali.smart0.xyz/Article/details/gtzdkfusqb.html

[T60] Scala：折叠
来源：http://dali.shanyushiyangtech.top/Article/details/gtkieaztbs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttaxyaldi.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gthgvnvogn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nwbrower.top/Article/details/gthjyofhsz.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtqrzdbvjv.html

[U01] Py：创建虚拟环境
来源：http://dali.sweek.top/Article/details/gtcmfjqxvw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhiwuduotai.top/Article/details/gtuwutbayw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenlongwang.top/Article/details/gtlpgimmwi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gzhubu.top/Article/details/gtpgrcnlsq.html

[U03] Py：加载 .env 配置
来源：http://dali.gaohongyu789.top/Article/details/gtmspgsfkd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cqqwz.cn/Article/details/gtsnajbmcy.html

[U04] Py：变量调试打印
来源：http://dali.fengsongda.top/Article/details/gtsymjqaec.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.mhx1999.top/Article/details/gtocbdakim.html

[U05] Py：列表去重且保序
来源：http://dali.tian-w.cn/Article/details/gttxezdzhi.html

list(dict.fromkeys(arr))
来源：http://dali.cashguo.top/Article/details/gtpsedjnby.html

[U06] Py：合并两个字典
来源：http://dali.sweek.top/Article/details/gtpunzngky.html

{**a, **b}
来源：http://dali.cucudq.cn/Article/details/gtqpevwomy.html

[U07] Py：反转字典键值
来源：http://dali.cheryme.top/Article/details/gtvqaoxsno.html

{v: k for k, v in d.items()}
来源：http://dali.zhixingplan.top/Article/details/gtbbxervad.html

[U08] Py：展平二维列表
来源：http://dali.ybcxt.top/Article/details/gtgwtalbmc.html

[y for x in nested for y in x]
来源：http://dali.sxryk.cn/Article/details/gtkhmbnkao.html

[U09] Py：字典取最大值的键
来源：http://dali.guannengcc.top/Article/details/gtgdxvuftz.html

max(d, key=d.get)
来源：http://dali.ehwqpu.com/Article/details/gtyhwlefyi.html

[U10] Py：按值排序字典
来源：http://dali.yangfankeji.com/Article/details/gtxhrdurrw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sysykeji.top/Article/details/gtbbpsoyyg.html

[U11] Py：生成器表达式
来源：http://dali.ehwqpu.com/Article/details/gtowunweve.html

(x * 2 for x in arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtaezgxrkg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.andypj.xyz/Article/details/gtxkobonql.html

Counter(arr).most_common(3)
来源：http://dali.yanxiufei.cn/Article/details/gtcjzpgrdc.html

[U13] Py：固定长度队列
来源：http://dali.yangfankeji.com/Article/details/gttmtiwlzn.html

deque(maxlen=10)
来源：http://dali.tian-w.cn/Article/details/gtvrktrwgj.html

[U14] Py：分组收集到列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcxnkmll.html

defaultdict(list)
来源：http://dali.vqdsnc.cn/Article/details/gtbulyoejl.html

[U15] Py：高精度计时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyfrcfgs.html

t = time.perf_counter()
来源：http://dali.smart0.xyz/Article/details/gtqnftukhu.html

[U16] Py：命令行参数解析
来源：http://dali.shzxlz.cn/Article/details/gtgdxtwbrj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvwuyydo.html

[U17] Py：初始化日志
来源：http://dali.nanxinkj.top/Article/details/gtoofpfgqx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.svipenyu.cn/Article/details/gtrxhwzuce.html

[U18] Py：预编译正则
来源：http://dali.zhiwuduotai.top/Article/details/gtnisbcxxe.html

pat = re.compile(r"\d+")
来源：http://dali.bjfxy.top/Article/details/gtmoqahmbo.html

[U19] Py：正则替换带回调
来源：http://dali.haohaochexian.top/Article/details/gtwkxjqxek.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zycfv.cn/Article/details/gtppcfebmt.html

[U20] Py：缓存函数结果
来源：http://dali.cheryme.top/Article/details/gtkutyookz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.andypj.xyz/Article/details/gtbclsmcvo.html

[U21] Py：自定义上下文管理器
来源：http://dali.sxryk.cn/Article/details/gtkusjpnrn.html

@contextlib.contextmanager
来源：http://dali.zhongyouzk.top/Article/details/gtlvosxddb.html

[U22] Py：矩阵转置
来源：http://dali.hnqzz.top/Article/details/gtwizycewi.html

list(zip(*m))
来源：http://dali.yvedp.cn/Article/details/gtbbhichyq.html

[U23] Py：分块读取大文件
来源：http://dali.cashguo.top/Article/details/gtmitqzknu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cqqwz.cn/Article/details/gtkmfutylq.html

[U24] Py：路径操作
来源：http://dali.jyoumei.cn/Article/details/gtaaiyihnu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gtpxcpmhxz.html

[U25] Py：CSV 按字典读
来源：http://dali.cheryme.top/Article/details/gtgwbjrtnj.html

csv.DictReader(f)
来源：http://dali.jianghu66.top/Article/details/gtgoprdmow.html

[U26] Py：并发下载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfsnwhulh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cheryme.top/Article/details/gtdemffwpe.html

[U27] Py：异步 HTTP
来源：http://dali.wangdashe.top/Article/details/gtjvlqelfm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sweek.top/Article/details/gtknrewdou.html

[U28] Py：类型别名
来源：http://dali.tian-w.cn/Article/details/gttmsnnhbr.html

UserId = int
来源：http://dali.0kj1m.cn/Article/details/gtaqlsivrk.html


<!-- 参考信息 -->