代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.316326.xyz/Article/details/gtllgaldmg.html

[S04] C：字符串复制
来源：http://dali.dashuyun.cn/Article/details/gteijeqvgt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daxiang520.top/Article/details/gtbaaywebm.html

[S05] C：字符串长度
来源：http://dali.guowangkeji.top/Article/details/gtchddjoze.html

strlen(s)
来源：http://dali.aizwys.cn/Article/details/gtkszwevej.html

[S06] C：字符串比较
来源：http://dali.tianlin.xyz/Article/details/gtacuehpfg.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gtyvmxwzen.html

[S07] C：数组遍历求和
来源：http://dali.xylfe.cn/Article/details/gtoakiagqn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuxming.cn/Article/details/gtuhqpepbe.html

[S08] C：动态内存分配与释放
来源：http://dali.zhongyouzk.top/Article/details/gtdahfigrd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xziqi.cn/Article/details/gtprcvixlh.html

[S09] C：结构体定义与初始化
来源：http://dali.316326.xyz/Article/details/gtklqyjywd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwrxpwfq.html

[S10] C：指针与解引用
来源：http://dali.xuanzx.com/Article/details/gtuubfuwjr.html

int *p = &a;  *p = 5;
来源：http://dali.hammf.cn/Article/details/gtexuyrtor.html

[S11] C：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtpkzkrgdo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.vqdsnc.cn/Article/details/gtfodszwco.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangdashe.top/Article/details/gtltilzpsw.html

fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gtgnbyhvhf.html

[S12] C：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtdnvtglfp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sweek.top/Article/details/gtorldklkf.html

[S13] C：宏定义
来源：http://dali.nanxinkj.top/Article/details/gtbjxgauxe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcsddmzbu.html

[S14] C：枚举
来源：http://dali.cucudq.cn/Article/details/gthwycwncv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuanzx.com/Article/details/gtahmhzrho.html

[S15] C：类型转换
来源：http://dali.guannengcc.top/Article/details/gtxvxgftgw.html

(double) a / b
来源：http://dali.zycfv.cn/Article/details/gtqabeedxp.html

[S16] C：位操作置位
来源：http://dali.tanke756.top/Article/details/gtenouvyxj.html

x |= (1 << 3);
来源：http://dali.xylfe.cn/Article/details/gtecrkbvoz.html

[S17] C：安全拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtlypbeoso.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ydzc1.top/Article/details/gtyjbpwrti.html

[S18] C：命令行参数
来源：http://dali.havefunace.top/Article/details/gtratbhrhc.html

int main(int argc, char **argv)
来源：http://dali.yvedp.cn/Article/details/gthhosgryq.html

[S19] C：快速排序
来源：http://dali.cucudq.cn/Article/details/gtcxnveako.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtkwicssuw.html

[S20] C：二分查找
来源：http://dali.nanxuanxn.top/Article/details/gtwhschvky.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghoeetss.html

[S21] C：字符类别判断
来源：http://dali.dashuyun.cn/Article/details/gtbnmwpxrz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.vqdsnc.cn/Article/details/gtsybkodgw.html

[S22] C：字符串转数字
来源：http://dali.jiagoushi.top/Article/details/gtcaayxmjx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkuneajd.html

[S23] C：随机数
来源：http://dali.daxiang520.top/Article/details/gtgbgrkmaj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.316326.xyz/Article/details/gtudhjnxts.html

[S24] C：获取本地时间
来源：http://dali.jyoumei.cn/Article/details/gtbvpxudms.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gzhubu.top/Article/details/gtjuvyykat.html

[S25] C：内存拷贝
来源：http://dali.ybcxt.top/Article/details/gtestvgimf.html

memcpy(dst, src, n);
来源：http://dali.chenjidiqi.icu/Article/details/gtjxwgwnoc.html

[S26] C：内存清零
来源：http://dali.ybcxt.top/Article/details/gtdwfiigeq.html

memset(a, 0, sizeof a);
来源：http://dali.ehwqpu.com/Article/details/gtyshjzpjl.html

[S27] C：定义常量
来源：http://dali.yj202588.top/Article/details/gtbcxigllf.html

const double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtfdcvhlhx.html

[S28] C：静态变量
来源：http://dali.hywenlv.cn/Article/details/gtkpxgotdf.html

static int counter = 0;
来源：http://dali.yonumen.top/Article/details/gtqtcoohsc.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gtjmvuoidw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258.top/Article/details/gteissaeqa.html

[S30] C：头文件保护
来源：http://dali.9152youxi.cn/Article/details/gtzncyfnko.html

#ifndef X_H
来源：http://dali.xuetiantiany.cn/Article/details/gtujoqctir.html

#define X_H
来源：http://dali.sysykeji.top/Article/details/gtlulmfjtv.html

#endif
来源：http://dali.tianlin.xyz/Article/details/gtqcqmomem.html

[S31] C++：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtuvvbylxm.html

#include <iostream>
来源：http://dali.guowangkeji.top/Article/details/gtmgnnabwb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tian-w.cn/Article/details/gtqwgcmlvc.html

[S32] C++：字符串
来源：http://dali.0kj1m.cn/Article/details/gtomrhgywy.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258.top/Article/details/gtvhgsvlcb.html

[S33] C++：vector 增删
来源：http://dali.sweek.top/Article/details/gtngdutnnk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.haohaochexian.top/Article/details/gtkknfnabd.html

[S34] C++：遍历 vector
来源：http://dali.hongshengwenyu.top/Article/details/gtbqdosozj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.iojbl.cn/Article/details/gtchiauorh.html

[S35] C++：map
来源：http://dali.jqgufenzy.top/Article/details/gtavlqnklx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gtgcffgpbq.html

[S36] C++：unordered_map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfpcomaq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtqzzsibzb.html

[S37] C++：set
来源：http://dali.zycfv.cn/Article/details/gtiuiepxfl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.9152youxi.cn/Article/details/gtqgfzokrd.html

[S38] C++：排序
来源：http://dali.guowangkeji.top/Article/details/gtbuazcuxq.html

std::sort(v.begin(), v.end());
来源：http://dali.yangfankeji.com/Article/details/gtgravazqx.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgfzy.top/Article/details/gtyiwkwcny.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gtpcivphhu.html

[S40] C++：查找元素
来源：http://dali.hywenlv.cn/Article/details/gtzvpcqpmn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ivvv.top/Article/details/gtkwxlhvmb.html

[S41] C++：类与构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtzfckilen.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnxiangtu.top/Article/details/gtjpoxrrnc.html

[S42] C++：继承与虚函数
来源：http://dali.yvedp.cn/Article/details/gtrcinfcet.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigufen.top/Article/details/gtwschwics.html

[S43] C++：智能指针
来源：http://dali.hywenlv.cn/Article/details/gtejxvutyk.html

auto p = std::make_unique<int>(5);
来源：http://dali.fzhhl.top/Article/details/gteizupszz.html

[S44] C++：引用传参
来源：http://dali.hongshengwenyu.top/Article/details/gtfzuaolhw.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxeapihy.html

[S45] C++：lambda
来源：http://dali.feifeiyinyue.top/Article/details/gthdkfottq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guannengcc.top/Article/details/gttogazhas.html

[S46] C++：函数模板
来源：http://dali.jinqigfzy.top/Article/details/gttyajjrvj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sweek.top/Article/details/gtleufbskn.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtgksbfwie.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtylgjrjvv.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtuzglqpqs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinghuilouyu.cn/Article/details/gtigegrjrm.html

while (std::getline(in, line)) { }
来源：http://dali.shuidangran.top/Article/details/gthnvjwzql.html

[S49] C++：写文件
来源：http://dali.yangfankeji.com/Article/details/gtzqjcskot.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yueranfly.top/Article/details/gtptmpggfj.html

[S50] C++：格式化数字
来源：http://dali.wangdashe.top/Article/details/gtwgjlxbmu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtutjifsqf.html

[S51] C++：显式类型转换
来源：http://dali.bjfxy.top/Article/details/gtmtrmdzfc.html

static_cast<double>(a) / b
来源：http://dali.hammf.cn/Article/details/gtmhkpopnt.html

[S52] C++：const 与 noexcept
来源：http://dali.yanxiufei.cn/Article/details/gtemtbjjac.html

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbfqdzbsx.html

[S53] C++：移动语义
来源：http://dali.yj20258.top/Article/details/gtevqqcmyv.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigfzy.top/Article/details/gtiauuovas.html

[S54] C++：异常处理
来源：http://dali.sxryk.cn/Article/details/gtokuigjvh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fzhhl.top/Article/details/gtcygauqtq.html

[S55] C++：结构化绑定
来源：http://dali.hammf.cn/Article/details/gtbasaxdhx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cashguo.top/Article/details/gtrrdymiah.html

[S56] C++：optional
来源：http://dali.cqqwz.cn/Article/details/gtoarnnneb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.birdmap.top/Article/details/gtrpgjwxsn.html

[S57] C++：编译期常量
来源：http://dali.dashuyun.cn/Article/details/gtnxuoxgwk.html

constexpr int N = 10;
来源：http://dali.fzhhl.top/Article/details/gtcbekybqn.html

[S58] C++：命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gtlfptygdc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhongyouzk.top/Article/details/gtsraenblq.html

[S59] C++：静态断言
来源：http://dali.ydzc1.top/Article/details/gtefnygxrt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jianghu66.top/Article/details/gtjjriopry.html

[S60] C++：遍历并删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtpraerozu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gtmkehxyfd.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtgmaobtan.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jlsjyb.cn/Article/details/gtapteomwj.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gttexpebxe.html

[T01] Kotlin：Hello World
来源：http://dali.yvedp.cn/Article/details/gtfcfqksow.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtwqgsxsfn.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gtqucwukty.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258.top/Article/details/gtaxoobwxh.html

[T03] Kotlin：字符串模板
来源：http://dali.c1oappe.top/Article/details/gtbltkyxom.html

"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gtskdqoofv.html

[T04] Kotlin：空安全
来源：http://dali.havefunace.top/Article/details/gtoabkfiwa.html

val n: String? = null;  n?.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmgvfkgd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhoulong.xyz/Article/details/gtqmgzwwef.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fzhhl.top/Article/details/gtfwtaxojj.html

[T06] Kotlin：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gtqxfpxrls.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aizwys.cn/Article/details/gttglnsltj.html

[T07] Kotlin：集合过滤
来源：http://dali.bjfxy.top/Article/details/gthuvwpmqw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhengqikj.top/Article/details/gtivehqwrl.html

[T08] Kotlin：数据类
来源：http://dali.316326.xyz/Article/details/gtwkscwwqh.html

data class User(val name: String, val age: Int)
来源：http://dali.snrcjt.cn/Article/details/gtfsgkabqk.html

[T09] Kotlin：扩展函数
来源：http://dali.c1oappe.top/Article/details/gtdpmarmnk.html

fun String.exclaim() = this + "!"
来源：http://dali.daria6918.cn/Article/details/gtmjjwxdwn.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtsnjdmlrt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yanxiufei.cn/Article/details/gtztjakdxa.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gteqifpgqy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhongyouzk.top/Article/details/gtlirvfnug.html

[T12] Kotlin：解构声明
来源：http://dali.iojbl.cn/Article/details/gtigxbhfhr.html

val (a, b) = Pair(1, 2)
来源：http://dali.yvedp.cn/Article/details/gtkczmtbeu.html

[T13] Kotlin：只读 Map
来源：http://dali.yanxiufei.cn/Article/details/gtvqpsgezo.html

val m = mapOf("a" to 1)
来源：http://dali.zdqjudy.top/Article/details/gtddqbbrwm.html

[T14] Kotlin：循环
来源：http://dali.yonumen.top/Article/details/gtgsxqxvlm.html

for (i in 1..10) println(i)
来源：http://dali.hfpthk.cn/Article/details/gtlyspkmqg.html

[T15] Kotlin：接口
来源：http://dali.hnxiangtu.top/Article/details/gtchfcfana.html

interface Shape { fun area(): Double }
来源：http://dali.quarkkingdee.top/Article/details/gtluygtpvr.html

[T16] Swift：Hello World
来源：http://dali.hnqzz.top/Article/details/gtqnejzhkh.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gterliizlw.html

[T17] Swift：变量与常量
来源：http://dali.tanke756.top/Article/details/gtiwfcckit.html

var a = 1;  let b = 2
来源：http://dali.yangfankeji.com/Article/details/gtpqrnbyld.html

[T18] Swift：字符串插值
来源：http://dali.yuxming.cn/Article/details/gtiebtazct.html

"值: \(b)"
来源：http://dali.cashguo.top/Article/details/gtphvixpoh.html

[T19] Swift：可选绑定
来源：http://dali.iojbl.cn/Article/details/gtichizjsf.html

if let n = opt { print(n) }
来源：http://dali.gotoacloud.top/Article/details/gtzksymthi.html

[T20] Swift：数组操作
来源：http://dali.cashguo.top/Article/details/gtkwsmiaiz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xinyue.icu/Article/details/gtauubakln.html

[T21] Swift：遍历
来源：http://dali.sweek.top/Article/details/gtzugbserz.html

for x in a { print(x) }
来源：http://dali.aizwys.cn/Article/details/gtexeslyaz.html

[T22] Swift：字典
来源：http://dali.gotoacloud.top/Article/details/gtqhxryrdu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xylfe.cn/Article/details/gtsarlhopa.html

[T23] Swift：函数
来源：http://dali.chenzaomai.com/Article/details/gtgpcurjck.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj202588.top/Article/details/gtjxzydqte.html

[T24] Swift：闭包
来源：http://dali.mhx1999.top/Article/details/gtqktefmfm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtiighmlcj.html

[T25] Swift：结构体
来源：http://dali.chenlongwang.top/Article/details/gtmdfgyzxt.html

struct P { var x: Int }
来源：http://dali.cucudq.cn/Article/details/gthosnuovy.html

[T26] Swift：类与重写
来源：http://dali.yongpay.top/Article/details/gtviqejies.html

class A: Base { override func f() {} }
来源：http://dali.svipenyu.cn/Article/details/gtkrdntzyi.html

[T27] Swift：错误处理
来源：http://dali.xinyue.icu/Article/details/gtwjidoimm.html

do { try f() } catch { print(error) }
来源：http://dali.chenlongwang.top/Article/details/gtsbsoqfhd.html

[T28] Swift：枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtdllpyxsk.html

enum Color { case red, green }
来源：http://dali.jinqigfzy.top/Article/details/gtruzpcmij.html

[T29] Swift：guard 提前返回
来源：http://dali.yj202588.top/Article/details/gtglvxydsz.html

guard let x = opt else { return }
来源：http://dali.kuanghao11.cn/Article/details/gtpnlhcusi.html

[T30] Swift：协议
来源：http://dali.chenjidiqi.icu/Article/details/gtmzmhlnph.html

protocol Shape { func area() -> Double }
来源：http://dali.hywenlv.cn/Article/details/gtflqovbhw.html

[T31] Lua：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gthmjssisw.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtogoabhml.html

[T32] Lua：局部变量
来源：http://dali.dianchejie.cn/Article/details/gtqepfbgbm.html

local a = 1
来源：http://dali.yueranfly.top/Article/details/gttjmgmjmr.html

[T33] Lua：表（数组）
来源：http://dali.chenlongwang.top/Article/details/gtxsdjwjzx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.fzhhl.top/Article/details/gtmsbqxngk.html

[T34] Lua：遍历表
来源：http://dali.hywenlv.cn/Article/details/gtmcrbdohz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tianlin.xyz/Article/details/gtiwxvkpyl.html

[T35] Lua：字典表
来源：http://dali.cheryme.top/Article/details/gtdydrwvlb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jiagoushi.top/Article/details/gtotyqqrdn.html

[T36] Lua：函数
来源：http://dali.xuetiantiany.cn/Article/details/gteyvlrteb.html

function add(a, b) return a + b end
来源：http://dali.gzhubu.top/Article/details/gtczojqsag.html

[T37] Lua：字符串拼接
来源：http://dali.ybcxt.top/Article/details/gtnhupgxnk.html

"a" .. "b"
来源：http://dali.jqgfzy.top/Article/details/gtfxiadbjv.html

[T38] Lua：条件
来源：http://dali.yj202588.top/Article/details/gtsevsowss.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gtwafanwrc.html

[T39] Lua：模式匹配
来源：http://dali.yongpay.top/Article/details/gthhehxtql.html

string.find(s, "%d+")
来源：http://dali.pycfn.com/Article/details/gtbogfpxto.html

[T40] Lua：元表
来源：http://dali.0kj1m.cn/Article/details/gtacvvgydl.html

setmetatable({}, { __index = base })
来源：http://dali.fzhhl.top/Article/details/gtcnrfyqdw.html

[T41] Perl：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtwgvcoplu.html

print "Hello\n";
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwkklgnp.html

[T42] Perl：变量类型
来源：http://dali.sysykeji.top/Article/details/gtnhjiwxvl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.wangshuangyany.cn/Article/details/gtthxrnowz.html

[T43] Perl：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbnhwzmi.html

"值: $a"
来源：http://dali.jiagoushi.top/Article/details/gtvqtvtctp.html

[T44] Perl：条件
来源：http://dali.quarkkingdee.top/Article/details/gtyjaewtfm.html

if ($a > 0) { print "正"; }
来源：http://dali.hfpthk.cn/Article/details/gtziqbtugh.html

[T45] Perl：数组遍历
来源：http://dali.zdqjudy.top/Article/details/gtupbrtjxb.html

for my $x (@arr) { print $x; }
来源：http://dali.chenzaomai.com/Article/details/gtoxvqfmae.html

[T46] Perl：哈希操作
来源：http://dali.fengsongda.top/Article/details/gtwpjpiozr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.birdmap.top/Article/details/gtvgmrmnsp.html

[T47] Perl：正则捕获
来源：http://dali.hongshengwenyu.top/Article/details/gtccjrtbqk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.fzhhl.top/Article/details/gtljtmedsj.html

[T48] Perl：正则替换
来源：http://dali.xziqi.cn/Article/details/gtxajstaql.html

$s =~ s/old/new/g;
来源：http://dali.nwbrower.top/Article/details/gtomsszrgl.html

[T49] Perl：函数
来源：http://dali.xinyue.icu/Article/details/gtbfjlgwbl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gtwdqykbnt.html

[T50] Perl：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtfmuoahky.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.guowangkeji.top/Article/details/gtsvtxbnbm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnxiangtu.top/Article/details/gttstjbiex.html

[T51] Scala：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtfszvwvcu.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gtpoytyglq.html

[T52] Scala：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvdqyeyk.html

val a = 1;  var b = 2
来源：http://dali.yj20258.top/Article/details/gtjkiwrxwl.html

[T53] Scala：字符串插值
来源：http://dali.sysykeji.top/Article/details/gthzakrwbp.html

s"值: $b"
来源：http://dali.jiagoushi.top/Article/details/gtguvlxjqi.html

[T54] Scala：集合映射
来源：http://dali.xziqi.cn/Article/details/gtmphegalj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yvedp.cn/Article/details/gtfsvsvout.html

[T55] Scala：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gtzgitoyhi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.dianchejie.cn/Article/details/gtkpbjiavx.html

[T56] Scala：样例类
来源：http://dali.andypj.xyz/Article/details/gthwjdwjuf.html

case class User(name: String, age: Int)
来源：http://dali.kuanghao11.cn/Article/details/gtheevythg.html

[T57] Scala：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtwjgalbsv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ydzc1.top/Article/details/gtkhpaffap.html

[T58] Scala：函数定义
来源：http://dali.zhixingplan.top/Article/details/gtjyuevakj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yuxming.cn/Article/details/gtgrsxsvwl.html

[T59] Scala：循环
来源：http://dali.zhoulong.xyz/Article/details/gtwdjvqorh.html

for (i <- 1 to 10) println(i)
来源：http://dali.mhx1999.top/Article/details/gturwcgdpe.html

[T60] Scala：折叠
来源：http://dali.pycfn.com/Article/details/gtexohwsap.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ybcxt.top/Article/details/gtumzgqmhm.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtmsvpeksz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ivvv.top/Article/details/gtxkjamops.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtktfrnnev.html

[U01] Py：创建虚拟环境
来源：http://dali.cqqwz.cn/Article/details/gtxxyhwqie.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.meibo888.top/Article/details/gtlpjwfdqo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shangyingyoupin.top/Article/details/gtabhpiois.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.pycfn.com/Article/details/gtwywiidau.html

[U03] Py：加载 .env 配置
来源：http://dali.dashuyun.cn/Article/details/gtgunhemfd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.dashuyun.cn/Article/details/gttyhtedss.html

[U04] Py：变量调试打印
来源：http://dali.chenlongwang.top/Article/details/gtxvnnstsk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.daria6918.cn/Article/details/gtffktycin.html

[U05] Py：列表去重且保序
来源：http://dali.aibaodan.cn/Article/details/gtynqzeqms.html

list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gtioinjiqn.html

[U06] Py：合并两个字典
来源：http://dali.havefunace.top/Article/details/gtvuchtkrn.html

{**a, **b}
来源：http://dali.daxiang520.top/Article/details/gtbdqywncm.html

[U07] Py：反转字典键值
来源：http://dali.iojbl.cn/Article/details/gtpoftxbfr.html

{v: k for k, v in d.items()}
来源：http://dali.tian-w.cn/Article/details/gtsznyvdyu.html

[U08] Py：展平二维列表
来源：http://dali.gogol.net.cn/Article/details/gtdvfznano.html

[y for x in nested for y in x]
来源：http://dali.jqgfzy.top/Article/details/gtdqgevyhf.html

[U09] Py：字典取最大值的键
来源：http://dali.nanxinkj.top/Article/details/gtzlqoisbs.html

max(d, key=d.get)
来源：http://dali.shangyingyoupin.top/Article/details/gtsufwruyy.html

[U10] Py：按值排序字典
来源：http://dali.zycfv.cn/Article/details/gtycrzjnzz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ehwqpu.com/Article/details/gtauzwsgtg.html

[U11] Py：生成器表达式
来源：http://dali.aizwys.cn/Article/details/gtocfjwzat.html

(x * 2 for x in arr)
来源：http://dali.yj20258888.top/Article/details/gtwbitjwyc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yuxming.cn/Article/details/gtqtnmhldc.html

Counter(arr).most_common(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttekoskfw.html

[U13] Py：固定长度队列
来源：http://dali.jqgufenzy.top/Article/details/gtjylmwlgf.html

deque(maxlen=10)
来源：http://dali.cheryme.top/Article/details/gtcwswczlo.html

[U14] Py：分组收集到列表
来源：http://dali.redwolf501.top/Article/details/gtuonwldcv.html

defaultdict(list)
来源：http://dali.zhiwuduotai.top/Article/details/gtttpgybgf.html

[U15] Py：高精度计时
来源：http://dali.gzhubu.top/Article/details/gtxjvgyftu.html

t = time.perf_counter()
来源：http://dali.zhengqikj.top/Article/details/gtrgqbuovw.html

[U16] Py：命令行参数解析
来源：http://dali.xinyue.icu/Article/details/gtvtzhtqfi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhiwuduotai.top/Article/details/gtcrhdgbza.html

[U17] Py：初始化日志
来源：http://dali.hammf.cn/Article/details/gtjfjyxctp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.feifeiyinyue.top/Article/details/gtpejlbjtz.html

[U18] Py：预编译正则
来源：http://dali.yj20258.top/Article/details/gtkdalwkzm.html

pat = re.compile(r"\d+")
来源：http://dali.cdnleiting.top/Article/details/gtaixqaqcr.html

[U19] Py：正则替换带回调
来源：http://dali.gogol.net.cn/Article/details/gtjvmxjnzr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shangyingyoupin.top/Article/details/gtacwcpgij.html

[U20] Py：缓存函数结果
来源：http://dali.tianlin.xyz/Article/details/gtuewaimoy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.quarkkingdee.top/Article/details/gtuyuqrgze.html

[U21] Py：自定义上下文管理器
来源：http://dali.bjfxy.top/Article/details/gtpbxmhaiv.html

@contextlib.contextmanager
来源：http://dali.ppjwa.cn/Article/details/gtjxazngip.html

[U22] Py：矩阵转置
来源：http://dali.xinyue.icu/Article/details/gtjaynhvyk.html

list(zip(*m))
来源：http://dali.zhongyouzk.top/Article/details/gtzzobfeso.html

[U23] Py：分块读取大文件
来源：http://dali.xylfe.cn/Article/details/gtilfuefrv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shuidangran.top/Article/details/gtijsxikei.html

[U24] Py：路径操作
来源：http://dali.shangyingyoupin.top/Article/details/gtxrbhymsu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gtjjbolora.html

[U25] Py：CSV 按字典读
来源：http://dali.smart0.xyz/Article/details/gtinqcphuw.html

csv.DictReader(f)
来源：http://dali.yuxming.cn/Article/details/gtwfwxpzcd.html

[U26] Py：并发下载
来源：http://dali.jinqigfzy.top/Article/details/gtniifdnqi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yangfankeji.com/Article/details/gtchuryqwi.html


<!-- 参考信息 -->