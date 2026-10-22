代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hammf.cn/Article/details/gtfexzvumt.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgfzy.top/Article/details/gtcmqyuzvk.html

time ./run.sh
来源：http://dali.fzhhl.top/Article/details/gtpimvxthd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtylwolpap.html

S. C / C++ 专题
来源：http://dali.gotoacloud.top/Article/details/gtpzwcyvrw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtxdftcvxl.html

[S01] C：Hello World
来源：http://dali.sweek.top/Article/details/gtyjjculcp.html

#include <stdio.h>
来源：http://dali.chenjidiqi.icu/Article/details/gtvtrgphjx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dianchejie.cn/Article/details/gtpiekerkf.html

[S02] C：变量与格式化输出
来源：http://dali.ybcxt.top/Article/details/gtkdrsmrox.html

int a = 10; printf("%d\n", a);
来源：http://dali.smart0.xyz/Article/details/gttvjtachv.html

[S03] C：读入整数
来源：http://dali.svipenyu.cn/Article/details/gtvupzhmnb.html

int x; scanf("%d", &x);
来源：http://dali.sysykeji.top/Article/details/gtjntekbtj.html

[S04] C：字符串复制
来源：http://dali.nwbrower.top/Article/details/gtzayzowcq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.meibo888.top/Article/details/gtjfgwqyqv.html

[S05] C：字符串长度
来源：http://dali.sweek.top/Article/details/gtqmqtpoeb.html

strlen(s)
来源：http://dali.c1oappe.top/Article/details/gtwvsnzsss.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gtbynrfgmj.html

strcmp(a, b) == 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxnhihcw.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gtpgiqxbxk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pycfn.com/Article/details/gtphhpjwke.html

[S08] C：动态内存分配与释放
来源：http://dali.yuanzhike.top/Article/details/gthlxxkydf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangshuangyany.cn/Article/details/gtawomstyy.html

[S09] C：结构体定义与初始化
来源：http://dali.shangyingyoupin.top/Article/details/gtihkbedqa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zycfv.cn/Article/details/gtnymslief.html

[S10] C：指针与解引用
来源：http://dali.hfpthk.cn/Article/details/gtaoeosgch.html

int *p = &a;  *p = 5;
来源：http://dali.wangshuangyany.cn/Article/details/gtpqacxnps.html

[S11] C：逐行读文件
来源：http://dali.pycfn.com/Article/details/gtkrpdltll.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.quarkkingdee.top/Article/details/gtesroteez.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gtdksztxrw.html

fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gtkixbnaun.html

[S12] C：写文件
来源：http://dali.nanxuanxn.top/Article/details/gtqtquywef.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gtcwdorvxl.html

[S13] C：宏定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkcnsiaar.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuetiantiany.cn/Article/details/gtytsjoaza.html

[S14] C：枚举
来源：http://dali.aibaodan.cn/Article/details/gtvkfgbyyh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aibaodan.cn/Article/details/gtptjktzpa.html

[S15] C：类型转换
来源：http://dali.hfpthk.cn/Article/details/gttgavhadp.html

(double) a / b
来源：http://dali.nanxinkj.top/Article/details/gtccwutelo.html

[S16] C：位操作置位
来源：http://dali.9152youxi.cn/Article/details/gtapovrwrt.html

x |= (1 << 3);
来源：http://dali.tian-w.cn/Article/details/gtgasutjwu.html

[S17] C：安全拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtariejrjb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.0kj1m.cn/Article/details/gtjycybrti.html

[S18] C：命令行参数
来源：http://dali.shuidangran.top/Article/details/gtoeytngmc.html

int main(int argc, char **argv)
来源：http://dali.xinyue.icu/Article/details/gtqkzlqvyl.html

[S19] C：快速排序
来源：http://dali.yvedp.cn/Article/details/gtpmtghthv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gttecudwnz.html

[S20] C：二分查找
来源：http://dali.redwolf501.top/Article/details/gtdwbeenzh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtueeagade.html

[S21] C：字符类别判断
来源：http://dali.ppjwa.cn/Article/details/gtvavqadlu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pengpengdd.cyou/Article/details/gtnmahqowq.html

[S22] C：字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gtxviksvxl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gtoxvmsdim.html

[S23] C：随机数
来源：http://dali.jianghu66.top/Article/details/gtoficymzh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.birdmap.top/Article/details/gtukqmsxwv.html

[S24] C：获取本地时间
来源：http://dali.iojbl.cn/Article/details/gtbkzwumki.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj202588.top/Article/details/gtlnlawvjg.html

[S25] C：内存拷贝
来源：http://dali.daria6918.cn/Article/details/gtmbqmcaqf.html

memcpy(dst, src, n);
来源：http://dali.jqgfzy.top/Article/details/gtzbuvvcwg.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gtmajgjorl.html

memset(a, 0, sizeof a);
来源：http://dali.tanke756.top/Article/details/gtkichgcvo.html

[S27] C：定义常量
来源：http://dali.haohaochexian.top/Article/details/gtjbdifkkx.html

const double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gthmsckvxp.html

[S28] C：静态变量
来源：http://dali.vqdsnc.cn/Article/details/gtkduuhuks.html

static int counter = 0;
来源：http://dali.yj20258888.top/Article/details/gtnychmoha.html

[S29] C：变参函数
来源：http://dali.cqqwz.cn/Article/details/gtmwfyhxmn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnqzz.top/Article/details/gthgubunxb.html

[S30] C：头文件保护
来源：http://dali.yanxiufei.cn/Article/details/gtbbikkath.html

#ifndef X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvadntrw.html

#define X_H
来源：http://dali.zhiwuduotai.top/Article/details/gtkbkmborv.html

#endif
来源：http://dali.ybcxt.top/Article/details/gtximdejuk.html

[S31] C++：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtiyjtypxd.html

#include <iostream>
来源：http://dali.jinqigfzy.top/Article/details/gtkuevkuub.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jyoumei.cn/Article/details/gtoouyjsoj.html

[S32] C++：字符串
来源：http://dali.birdmap.top/Article/details/gtufrefxce.html

std::string s = "hi";  s += "!";
来源：http://dali.hfpthk.cn/Article/details/gtphqmkbuz.html

[S33] C++：vector 增删
来源：http://dali.yonumen.top/Article/details/gtgnzfdoul.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zycfv.cn/Article/details/gtmdjfskof.html

[S34] C++：遍历 vector
来源：http://dali.aibaodan.cn/Article/details/gtdlujlwnu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xinyue.icu/Article/details/gtqluppfpn.html

[S35] C++：map
来源：http://dali.yvedp.cn/Article/details/gtbyclsvvx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsyizqthq.html

[S36] C++：unordered_map
来源：http://dali.ivvv.top/Article/details/gtvqdosktx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhyfltnf.html

[S37] C++：set
来源：http://dali.shuidangran.top/Article/details/gtqguerhpk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guowangkeji.top/Article/details/gtguyjggjf.html

[S38] C++：排序
来源：http://dali.jinqigufen.top/Article/details/gtwzenpnmg.html

std::sort(v.begin(), v.end());
来源：http://dali.316326.xyz/Article/details/gtbfizlyqt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gtyuhabvtq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.birdmap.top/Article/details/gtboajfdsk.html

[S40] C++：查找元素
来源：http://dali.shzxlz.cn/Article/details/gtgneiwfwg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258888.top/Article/details/gtbkygcwuq.html

[S41] C++：类与构造函数
来源：http://dali.cucudq.cn/Article/details/gtowxkkwlw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.9152youxi.cn/Article/details/gtulblkrhp.html

[S42] C++：继承与虚函数
来源：http://dali.ivvv.top/Article/details/gtwcaswgco.html

class B : public Base { public: void f() override {} };
来源：http://dali.ppjwa.cn/Article/details/gtxxsdcnme.html

[S43] C++：智能指针
来源：http://dali.daxiang520.top/Article/details/gtjraeevey.html

auto p = std::make_unique<int>(5);
来源：http://dali.daria6918.cn/Article/details/gtpscsighn.html

[S44] C++：引用传参
来源：http://dali.jqgfzy.top/Article/details/gtjdytzawa.html

void inc(int &x) { ++x; }
来源：http://dali.redwolf501.top/Article/details/gtsqwmaxuv.html

[S45] C++：lambda
来源：http://dali.yonumen.top/Article/details/gtvhywolyq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tian-w.cn/Article/details/gtncrhujdq.html

[S46] C++：函数模板
来源：http://dali.hysaishi.cn/Article/details/gtgenjocez.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ybcxt.top/Article/details/gtikhbhpgd.html

[S47] C++：结构化绑定遍历
来源：http://dali.nanxinkj.top/Article/details/gtgysggwfb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.smart0.xyz/Article/details/gtikgoakhq.html

[S48] C++：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gthljjusvb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhoulong.xyz/Article/details/gtezenfyag.html

while (std::getline(in, line)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtolabmlxk.html

[S49] C++：写文件
来源：http://dali.xylfe.cn/Article/details/gtrbrhjjnp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gtmwxmkkwv.html

[S50] C++：格式化数字
来源：http://dali.shuidangran.top/Article/details/gtcagxwmvz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtngkytkty.html

[S51] C++：显式类型转换
来源：http://dali.sysykeji.top/Article/details/gtkhdfxlwy.html

static_cast<double>(a) / b
来源：http://dali.bjfxy.top/Article/details/gtkhbzofof.html

[S52] C++：const 与 noexcept
来源：http://dali.0kj1m.cn/Article/details/gtynkmhbla.html

int size() const noexcept { return n_; }
来源：http://dali.kuanghao11.cn/Article/details/gtdmjeifsd.html

[S53] C++：移动语义
来源：http://dali.yueranfly.top/Article/details/gtjxutitwi.html

std::vector<int> w = std::move(v);
来源：http://dali.pengpengdd.cyou/Article/details/gtazurymyr.html

[S54] C++：异常处理
来源：http://dali.yongpay.top/Article/details/gtejlkhvtm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hfpthk.cn/Article/details/gtqgvfahgt.html

[S55] C++：结构化绑定
来源：http://dali.gogol.net.cn/Article/details/gtsjhagefo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pycfn.com/Article/details/gtndfsbxer.html

[S56] C++：optional
来源：http://dali.cdnleiting.top/Article/details/gtagtttcqb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.snrcjt.cn/Article/details/gthbsgwwif.html

[S57] C++：编译期常量
来源：http://dali.zhongyouzk.top/Article/details/gtpebqfers.html

constexpr int N = 10;
来源：http://dali.ybcxt.top/Article/details/gtetqkotwt.html

[S58] C++：命名空间
来源：http://dali.yj202588.top/Article/details/gtduigfkfx.html

namespace ns { int f() { return 1; } }
来源：http://dali.havefunace.top/Article/details/gtputrrdad.html

[S59] C++：静态断言
来源：http://dali.jinghuilouyu.cn/Article/details/gthcjkdccm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gtkjoacwix.html

[S60] C++：遍历并删除元素
来源：http://dali.tian-w.cn/Article/details/gtvkyvtxyg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dashuyun.cn/Article/details/gtvvuggqiz.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtotkzecfp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.0kj1m.cn/Article/details/gtxdjwkmbe.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtwgssfdzw.html

[T01] Kotlin：Hello World
来源：http://dali.c1oappe.top/Article/details/gtqsyfuicc.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gtxcwvaslk.html

[T02] Kotlin：变量
来源：http://dali.shangyingyoupin.top/Article/details/gtbqxgcalo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.vqdsnc.cn/Article/details/gtzwzwzeyj.html

[T03] Kotlin：字符串模板
来源：http://dali.hammf.cn/Article/details/gtxhfsbdxa.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gtpnrdlfzm.html

[T04] Kotlin：空安全
来源：http://dali.birdmap.top/Article/details/gtnjbitwnm.html

val n: String? = null;  n?.length
来源：http://dali.gaohongyu789.top/Article/details/gtavtdfzzy.html

[T05] Kotlin：when 表达式
来源：http://dali.tianlin.xyz/Article/details/gtlenoxafs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ydzc1.top/Article/details/gtbuxpoybb.html

[T06] Kotlin：集合映射
来源：http://dali.tianlin.xyz/Article/details/gtticvregg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gthzyvzsrg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gtrnkblqtz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sysykeji.top/Article/details/gtzzmagbai.html

[T08] Kotlin：数据类
来源：http://dali.dashuyun.cn/Article/details/gtxcmpwdgb.html

data class User(val name: String, val age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsxurzyo.html

[T09] Kotlin：扩展函数
来源：http://dali.hfpthk.cn/Article/details/gtmhrdngbt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsrnpwmu.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigufen.top/Article/details/gtmzerujzp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuetiantiany.cn/Article/details/gtsnndwqmt.html

[T11] Kotlin：协程
来源：http://dali.kuanghao11.cn/Article/details/gtvwstcirf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gtchrbssbn.html

[T12] Kotlin：解构声明
来源：http://dali.daxiang520.top/Article/details/gtctradmgu.html

val (a, b) = Pair(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtwtxjptmu.html

[T13] Kotlin：只读 Map
来源：http://dali.jinghuilouyu.cn/Article/details/gtozahdhlu.html

val m = mapOf("a" to 1)
来源：http://dali.tian-w.cn/Article/details/gtevlalzrq.html

[T14] Kotlin：循环
来源：http://dali.jiagoushi.top/Article/details/gtfxvliqdz.html

for (i in 1..10) println(i)
来源：http://dali.sweek.top/Article/details/gtlbnavcip.html

[T15] Kotlin：接口
来源：http://dali.cdnleiting.top/Article/details/gtbpivusxz.html

interface Shape { fun area(): Double }
来源：http://dali.cdnleiting.top/Article/details/gtgwsarevc.html

[T16] Swift：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtpemezcjn.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtypohxhyc.html

[T17] Swift：变量与常量
来源：http://dali.hfpthk.cn/Article/details/gtrxpgjvrc.html

var a = 1;  let b = 2
来源：http://dali.yongpay.top/Article/details/gtzugqqxur.html

[T18] Swift：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtygharxwu.html

"值: \(b)"
来源：http://dali.chenlongwang.top/Article/details/gtrvtyllcy.html

[T19] Swift：可选绑定
来源：http://dali.nanxinkj.top/Article/details/gtetnrvbax.html

if let n = opt { print(n) }
来源：http://dali.hammf.cn/Article/details/gtqsxrsstu.html

[T20] Swift：数组操作
来源：http://dali.pycfn.com/Article/details/gtaobagfua.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.feifeiyinyue.top/Article/details/gtdttdjmnq.html

[T21] Swift：遍历
来源：http://dali.bjfxy.top/Article/details/gtyslnmamj.html

for x in a { print(x) }
来源：http://dali.yueranfly.top/Article/details/gtxvgfqeco.html

[T22] Swift：字典
来源：http://dali.0kj1m.cn/Article/details/gtcfzbodyp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hywenlv.cn/Article/details/gtfeoeunpi.html

[T23] Swift：函数
来源：http://dali.0kj1m.cn/Article/details/gtjshnhrjq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmmylvkz.html

[T24] Swift：闭包
来源：http://dali.pengpengdd.cyou/Article/details/gtzuqictep.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtezilupuz.html

[T25] Swift：结构体
来源：http://dali.sufxvd.cn/Article/details/gtcytuusco.html

struct P { var x: Int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtarqibk.html

[T26] Swift：类与重写
来源：http://dali.pengpengdd.cyou/Article/details/gtszzfqzla.html

class A: Base { override func f() {} }
来源：http://dali.haohaochexian.top/Article/details/gtrpyzjxcx.html

[T27] Swift：错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtoqfsraaf.html

do { try f() } catch { print(error) }
来源：http://dali.gaohongyu789.top/Article/details/gtgbugaeda.html

[T28] Swift：枚举
来源：http://dali.yueranfly.top/Article/details/gtaslaimzd.html

enum Color { case red, green }
来源：http://dali.daxiang520.top/Article/details/gtewaygnpm.html

[T29] Swift：guard 提前返回
来源：http://dali.gzhubu.top/Article/details/gtenazxulp.html

guard let x = opt else { return }
来源：http://dali.wangdashe.top/Article/details/gtcifdamok.html

[T30] Swift：协议
来源：http://dali.zhoulong.xyz/Article/details/gttdykuofn.html

protocol Shape { func area() -> Double }
来源：http://dali.haohaochexian.top/Article/details/gtpbveqdea.html

[T31] Lua：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtyegdebff.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gtxlfnqney.html

[T32] Lua：局部变量
来源：http://dali.gzhubu.top/Article/details/gtyrnkorif.html

local a = 1
来源：http://dali.jinqigufen.top/Article/details/gtsujmyfub.html

[T33] Lua：表（数组）
来源：http://dali.sweek.top/Article/details/gtijrvjgtp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.aizwys.cn/Article/details/gtlfmajpqe.html

[T34] Lua：遍历表
来源：http://dali.kuanghao11.cn/Article/details/gtnitygort.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sysykeji.top/Article/details/gtyljywkqd.html

[T35] Lua：字典表
来源：http://dali.cheryme.top/Article/details/gtffmtfzzn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sysykeji.top/Article/details/gtvtycdbne.html

[T36] Lua：函数
来源：http://dali.birdmap.top/Article/details/gtduwjuzlw.html

function add(a, b) return a + b end
来源：http://dali.zdqjudy.top/Article/details/gtajspjigl.html

[T37] Lua：字符串拼接
来源：http://dali.c1oappe.top/Article/details/gtfmqmkejx.html

"a" .. "b"
来源：http://dali.gotoacloud.top/Article/details/gtagpquzjt.html

[T38] Lua：条件
来源：http://dali.hnxiangtu.top/Article/details/gtfsffqrbt.html

if x > 0 then print("正") end
来源：http://dali.xuetiantiany.cn/Article/details/gtsqstyigx.html

[T39] Lua：模式匹配
来源：http://dali.zhongyouzk.top/Article/details/gtrzftbxfo.html

string.find(s, "%d+")
来源：http://dali.hongshengwenyu.top/Article/details/gtjhezewvj.html

[T40] Lua：元表
来源：http://dali.meibo888.top/Article/details/gtflyhzouo.html

setmetatable({}, { __index = base })
来源：http://dali.aizwys.cn/Article/details/gtabegmlwu.html

[T41] Perl：Hello World
来源：http://dali.daxiang520.top/Article/details/gtnxopibvp.html

print "Hello\n";
来源：http://dali.jiagoushi.top/Article/details/gtjbuslywf.html

[T42] Perl：变量类型
来源：http://dali.gaohongyu789.top/Article/details/gtgfbcrrcm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.vqdsnc.cn/Article/details/gtzgxicwsf.html

[T43] Perl：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtvxoyuvmm.html

"值: $a"
来源：http://dali.cqqwz.cn/Article/details/gtdiubsdjg.html

[T44] Perl：条件
来源：http://dali.iojbl.cn/Article/details/gtldjnqihy.html

if ($a > 0) { print "正"; }
来源：http://dali.xylfe.cn/Article/details/gtoxbybqer.html

[T45] Perl：数组遍历
来源：http://dali.zhengqikj.top/Article/details/gtsdibdkgb.html

for my $x (@arr) { print $x; }
来源：http://dali.cucudq.cn/Article/details/gtsdjekfgy.html

[T46] Perl：哈希操作
来源：http://dali.gotoacloud.top/Article/details/gtsqrrfotm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.birdmap.top/Article/details/gtdebikzuq.html

[T47] Perl：正则捕获
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqgoztxo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.snrcjt.cn/Article/details/gtybmadrnv.html

[T48] Perl：正则替换
来源：http://dali.xinyue.icu/Article/details/gtbtcyioim.html

$s =~ s/old/new/g;
来源：http://dali.cdnleiting.top/Article/details/gtyhpdxqqz.html

[T49] Perl：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvapnmym.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtresjwdpe.html

[T50] Perl：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtfzjnzlyn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xuetiantiany.cn/Article/details/gtqfjosxpa.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sweek.top/Article/details/gtatdflhgy.html

[T51] Scala：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gttcaxlubg.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtavsruetk.html

[T52] Scala：变量
来源：http://dali.zycfv.cn/Article/details/gtxcyylkly.html

val a = 1;  var b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtajithmwx.html

[T53] Scala：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gttbdzugxz.html

s"值: $b"
来源：http://dali.vqdsnc.cn/Article/details/gtmiyeppeq.html

[T54] Scala：集合映射
来源：http://dali.zhengqikj.top/Article/details/gtymlmtsjt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqaonskll.html

[T55] Scala：集合过滤
来源：http://dali.iojbl.cn/Article/details/gtbbfdoxxk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtpfxecegy.html

[T56] Scala：样例类
来源：http://dali.fzhhl.top/Article/details/gtegzszuha.html

case class User(name: String, age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gttdofhanq.html

[T57] Scala：模式匹配
来源：http://dali.fzhhl.top/Article/details/gtbnksvnam.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.iojbl.cn/Article/details/gtfjiufiqj.html

[T58] Scala：函数定义
来源：http://dali.hammf.cn/Article/details/gtvsirglxj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.smart0.xyz/Article/details/gtzrkztxby.html

[T59] Scala：循环
来源：http://dali.cucudq.cn/Article/details/gtmjwmmazl.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtauxqlehj.html

[T60] Scala：折叠
来源：http://dali.yuanzhike.top/Article/details/gtizpfuddj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.feifeiyinyue.top/Article/details/gtusjkwccl.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtgtuvoqzl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tianlin.xyz/Article/details/gtixxsievo.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsijllmp.html

[U01] Py：创建虚拟环境
来源：http://dali.shangyingyoupin.top/Article/details/gtvromjchh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nwbrower.top/Article/details/gtsssinjin.html

[U02] Py：导出 / 安装依赖
来源：http://dali.quarkkingdee.top/Article/details/gtadujdywr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guowangkeji.top/Article/details/gtzwyxkzqx.html

[U03] Py：加载 .env 配置
来源：http://dali.hammf.cn/Article/details/gtonxpmytj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gzhubu.top/Article/details/gtpbcflkmc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gtwtunzjjb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sufxvd.cn/Article/details/gtofxzbvyx.html

[U05] Py：列表去重且保序
来源：http://dali.316326.xyz/Article/details/gtxpzmdrsn.html

list(dict.fromkeys(arr))
来源：http://dali.zdqjudy.top/Article/details/gtmnjszbep.html

[U06] Py：合并两个字典
来源：http://dali.jinqigfzy.top/Article/details/gtlimdlyct.html

{**a, **b}
来源：http://dali.zhixingplan.top/Article/details/gtvjimimfq.html

[U07] Py：反转字典键值
来源：http://dali.hnxiangtu.top/Article/details/gtszzkchum.html

{v: k for k, v in d.items()}
来源：http://dali.nwbrower.top/Article/details/gtogehutac.html

[U08] Py：展平二维列表
来源：http://dali.aibaodan.cn/Article/details/gtikbwnoqc.html

[y for x in nested for y in x]
来源：http://dali.yuxming.cn/Article/details/gtinjumfmg.html

[U09] Py：字典取最大值的键
来源：http://dali.redwolf501.top/Article/details/gtyqpsovrv.html

max(d, key=d.get)
来源：http://dali.fzhhl.top/Article/details/gtelyxuuvw.html

[U10] Py：按值排序字典
来源：http://dali.guowangkeji.top/Article/details/gtbtytcdun.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cashguo.top/Article/details/gttqroapqa.html

[U11] Py：生成器表达式
来源：http://dali.yj20258.top/Article/details/gtntpuwhkz.html

(x * 2 for x in arr)
来源：http://dali.gaohongyu789.top/Article/details/gtixmemxuy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.dianchejie.cn/Article/details/gtljiccunk.html

Counter(arr).most_common(3)
来源：http://dali.jiagoushi.top/Article/details/gtjrdsgabj.html

[U13] Py：固定长度队列
来源：http://dali.hnxiangtu.top/Article/details/gtotuhkeef.html

deque(maxlen=10)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujrcernw.html

[U14] Py：分组收集到列表
来源：http://dali.316326.xyz/Article/details/gtggkdvyql.html

defaultdict(list)
来源：http://dali.pengpengdd.cyou/Article/details/gtnqyuhkyo.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gtkfyvgdla.html

t = time.perf_counter()
来源：http://dali.hfpthk.cn/Article/details/gtevgwuznj.html

[U16] Py：命令行参数解析
来源：http://dali.aizwys.cn/Article/details/gtrporpjha.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xylfe.cn/Article/details/gtpvqidbcv.html

[U17] Py：初始化日志
来源：http://dali.mhx1999.top/Article/details/gtbcslafhn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.fengsongda.top/Article/details/gtdigjxxfn.html

[U18] Py：预编译正则
来源：http://dali.ppjwa.cn/Article/details/gtoaqettgh.html

pat = re.compile(r"\d+")
来源：http://dali.chenlongwang.top/Article/details/gtcdlmjbxv.html

[U19] Py：正则替换带回调
来源：http://dali.sufxvd.cn/Article/details/gtmaadnjks.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtouergvek.html

[U20] Py：缓存函数结果
来源：http://dali.xinyue.icu/Article/details/gtzkqmjaif.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xinyue.icu/Article/details/gthxkydfrf.html


<!-- 参考信息 -->