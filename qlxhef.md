代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xinyue.icu/Article/details/gtjigweizx.html

[R80] 查看脚本执行耗时
来源：http://dali.0kj1m.cn/Article/details/gtuvnzncav.html

time ./run.sh
来源：http://dali.dashuyun.cn/Article/details/gthiigjlmx.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtthkucrxs.html

S. C / C++ 专题
来源：http://dali.yj20258888.top/Article/details/gtirbzuvgp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtxpbrclet.html

[S01] C：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtnwxlqurl.html

#include <stdio.h>
来源：http://dali.cqqwz.cn/Article/details/gtdjswuyrp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jlsjyb.cn/Article/details/gtdznxvpji.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqavrtjs.html

int a = 10; printf("%d\n", a);
来源：http://dali.guowangkeji.top/Article/details/gtqvhhkxkq.html

[S03] C：读入整数
来源：http://dali.shzxlz.cn/Article/details/gtnxmhkerl.html

int x; scanf("%d", &x);
来源：http://dali.sxryk.cn/Article/details/gtgjvuypro.html

[S04] C：字符串复制
来源：http://dali.shzxlz.cn/Article/details/gtolcnyjnm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cdnleiting.top/Article/details/gtpdftghzy.html

[S05] C：字符串长度
来源：http://dali.cashguo.top/Article/details/gtutyihqmq.html

strlen(s)
来源：http://dali.tian-w.cn/Article/details/gtdaaekrwa.html

[S06] C：字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gtjugjfosf.html

strcmp(a, b) == 0
来源：http://dali.zhixingplan.top/Article/details/gtwvepibcx.html

[S07] C：数组遍历求和
来源：http://dali.cqqwz.cn/Article/details/gtppjmcfcg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnqzz.top/Article/details/gtsndxgtvn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhiwuduotai.top/Article/details/gtrkhzyzln.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xylfe.cn/Article/details/gtbhrlgbae.html

[S09] C：结构体定义与初始化
来源：http://dali.ybcxt.top/Article/details/gtcqgktdlr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guowangkeji.top/Article/details/gtmdoernll.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gtbergmlqv.html

int *p = &a;  *p = 5;
来源：http://dali.jlsjyb.cn/Article/details/gtnwobkixs.html

[S11] C：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gttfdsethh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gtqfjkjiri.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xinyue.icu/Article/details/gtylfwtaus.html

fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtugaprahl.html

[S12] C：写文件
来源：http://dali.bjfxy.top/Article/details/gtltpamvzl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cheryme.top/Article/details/gtbhhmnxcj.html

[S13] C：宏定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gteiujofkc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gzhubu.top/Article/details/gttmepvuwy.html

[S14] C：枚举
来源：http://dali.cashguo.top/Article/details/gtngsbzdzi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hysaishi.cn/Article/details/gtsruqgcou.html

[S15] C：类型转换
来源：http://dali.zycfv.cn/Article/details/gtwlrbhbok.html

(double) a / b
来源：http://dali.chenzaomai.com/Article/details/gtgnpcipfn.html

[S16] C：位操作置位
来源：http://dali.yj20258.top/Article/details/gtqqahqfgb.html

x |= (1 << 3);
来源：http://dali.yuanzhike.top/Article/details/gtpvcvbgxz.html

[S17] C：安全拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gthmjurand.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.havefunace.top/Article/details/gthyhtbvfi.html

[S18] C：命令行参数
来源：http://dali.tanke756.top/Article/details/gtnxszsgmd.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkeoisjy.html

[S19] C：快速排序
来源：http://dali.yonumen.top/Article/details/gtobhvbigs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtcsprxuio.html

[S20] C：二分查找
来源：http://dali.gotoacloud.top/Article/details/gtcpxxuuzw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gtnsocbrbb.html

[S21] C：字符类别判断
来源：http://dali.xuanzx.com/Article/details/gtxgrrytqn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hammf.cn/Article/details/gtayeaczsi.html

[S22] C：字符串转数字
来源：http://dali.bjfxy.top/Article/details/gttthwbycy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gtqwxpszjb.html

[S23] C：随机数
来源：http://dali.nanxinkj.top/Article/details/gtwpqqmjoo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hammf.cn/Article/details/gtadwzaktr.html

[S24] C：获取本地时间
来源：http://dali.cdnleiting.top/Article/details/gtgsbddsng.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cucudq.cn/Article/details/gtllomtfvr.html

[S25] C：内存拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtghfdmjnu.html

memcpy(dst, src, n);
来源：http://dali.cheryme.top/Article/details/gtoqcfsytz.html

[S26] C：内存清零
来源：http://dali.sweek.top/Article/details/gtkyzrzgsd.html

memset(a, 0, sizeof a);
来源：http://dali.snrcjt.cn/Article/details/gtmiaawtqv.html

[S27] C：定义常量
来源：http://dali.cdnleiting.top/Article/details/gtiwjelyxt.html

const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtndfnhesl.html

[S28] C：静态变量
来源：http://dali.shuidangran.top/Article/details/gticpmedtp.html

static int counter = 0;
来源：http://dali.sufxvd.cn/Article/details/gteogrunzi.html

[S29] C：变参函数
来源：http://dali.shzxlz.cn/Article/details/gtdmmgtthu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shuidangran.top/Article/details/gtkyfljikz.html

[S30] C：头文件保护
来源：http://dali.dashuyun.cn/Article/details/gtelpvsgyt.html

#ifndef X_H
来源：http://dali.chenjidiqi.icu/Article/details/gtnsdofovt.html

#define X_H
来源：http://dali.zhixingplan.top/Article/details/gtfsgemeom.html

#endif
来源：http://dali.tian-w.cn/Article/details/gtlrsdnlex.html

[S31] C++：Hello World
来源：http://dali.yj20258.top/Article/details/gtxqfddvzx.html

#include <iostream>
来源：http://dali.jyoumei.cn/Article/details/gtiloohzdk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hammf.cn/Article/details/gtsmaysclz.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjfxiega.html

std::string s = "hi";  s += "!";
来源：http://dali.aibaodan.cn/Article/details/gtihwxuddx.html

[S33] C++：vector 增删
来源：http://dali.cdnleiting.top/Article/details/gtudwhrkqu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gtlmkqnoac.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangtech.top/Article/details/gtjczuqcbo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tian-w.cn/Article/details/gtfbgyfmqy.html

[S35] C++：map
来源：http://dali.guowangkeji.top/Article/details/gtzfhdcsbb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtpxehhxzn.html

[S36] C++：unordered_map
来源：http://dali.hnqzz.top/Article/details/gtkjlwrjlj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtpuvzbzdo.html

[S37] C++：set
来源：http://dali.jinqigfzy.top/Article/details/gtxpkuahyy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.0kj1m.cn/Article/details/gtpwhyfzlb.html

[S38] C++：排序
来源：http://dali.ehwqpu.com/Article/details/gtifujmegc.html

std::sort(v.begin(), v.end());
来源：http://dali.shuidangran.top/Article/details/gtnlvoimga.html

[S39] C++：自定义比较器排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsvpoztd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxinkj.top/Article/details/gtuvplhqxa.html

[S40] C++：查找元素
来源：http://dali.jyoumei.cn/Article/details/gtxvfbovrp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gogol.net.cn/Article/details/gteijncuoh.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gtjwtrckch.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tanke756.top/Article/details/gtigqwgutr.html

[S42] C++：继承与虚函数
来源：http://dali.shangyingyoupin.top/Article/details/gtoinpoyap.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgufenzy.top/Article/details/gtdsqmthtj.html

[S43] C++：智能指针
来源：http://dali.hywenlv.cn/Article/details/gtbdsrcfvd.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfnimdqo.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gttdqfzbyq.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gtyyxxffks.html

[S45] C++：lambda
来源：http://dali.yongpay.top/Article/details/gtfatvwnxh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tian-w.cn/Article/details/gtcayzuaqr.html

[S46] C++：函数模板
来源：http://dali.zhengqikj.top/Article/details/gtxypslnnx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tianlin.xyz/Article/details/gtjzejjcpz.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigufen.top/Article/details/gtxpgzfrno.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yvedp.cn/Article/details/gtopasrrzz.html

[S48] C++：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtrwownpqd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnydrztji.html

while (std::getline(in, line)) { }
来源：http://dali.yuxming.cn/Article/details/gtotejhqsk.html

[S49] C++：写文件
来源：http://dali.hammf.cn/Article/details/gtnxxmwmvk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yueranfly.top/Article/details/gtysgbmlao.html

[S50] C++：格式化数字
来源：http://dali.yvedp.cn/Article/details/gtjoqklwvc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtjbeldxpt.html

[S51] C++：显式类型转换
来源：http://dali.dianchejie.cn/Article/details/gtnksxhssz.html

static_cast<double>(a) / b
来源：http://dali.jlsjyb.cn/Article/details/gtgprsogmc.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gtndqxorbl.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gtriugtvjz.html

[S53] C++：移动语义
来源：http://dali.gzhubu.top/Article/details/gtwjdoioxd.html

std::vector<int> w = std::move(v);
来源：http://dali.jlsjyb.cn/Article/details/gtnvedejux.html

[S54] C++：异常处理
来源：http://dali.gzhubu.top/Article/details/gtsznabzwn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxirtbrmp.html

[S55] C++：结构化绑定
来源：http://dali.svipenyu.cn/Article/details/gttikmbqup.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yongpay.top/Article/details/gtzjygmcnj.html

[S56] C++：optional
来源：http://dali.kuanghao11.cn/Article/details/gtuetpiujv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.meibo888.top/Article/details/gtuikaqgix.html

[S57] C++：编译期常量
来源：http://dali.aibaodan.cn/Article/details/gtpowukqvv.html

constexpr int N = 10;
来源：http://dali.cdnleiting.top/Article/details/gtfrryxklm.html

[S58] C++：命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gtayrbjvhy.html

namespace ns { int f() { return 1; } }
来源：http://dali.hysaishi.cn/Article/details/gtmvvfvnqz.html

[S59] C++：静态断言
来源：http://dali.xuanzx.com/Article/details/gtbjjtjtrq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gtpqojgans.html

[S60] C++：遍历并删除元素
来源：http://dali.ybcxt.top/Article/details/gtmtlttdrm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jianghu66.top/Article/details/gtvtbpqvpr.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtmnfwbmir.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sxryk.cn/Article/details/gtrujiqlua.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtrdntujfc.html

[T01] Kotlin：Hello World
来源：http://dali.daria6918.cn/Article/details/gtcgqhmgoy.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtphpcrapw.html

[T02] Kotlin：变量
来源：http://dali.redwolf501.top/Article/details/gtqbebagvu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhixingplan.top/Article/details/gtdpkdmhfo.html

[T03] Kotlin：字符串模板
来源：http://dali.hnxiangtu.top/Article/details/gtugfxpbnf.html

"值: $b"
来源：http://dali.nwbrower.top/Article/details/gtvjvanpvm.html

[T04] Kotlin：空安全
来源：http://dali.vqdsnc.cn/Article/details/gthgbzzatc.html

val n: String? = null;  n?.length
来源：http://dali.hnqzz.top/Article/details/gthwvqruht.html

[T05] Kotlin：when 表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gteutzyyny.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ivvv.top/Article/details/gtfrhnzvtv.html

[T06] Kotlin：集合映射
来源：http://dali.tian-w.cn/Article/details/gtwhyklcrt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj20258888.top/Article/details/gtpnppdmzj.html

[T07] Kotlin：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gtgicmoyib.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.bjfxy.top/Article/details/gtvyzbxwdg.html

[T08] Kotlin：数据类
来源：http://dali.meibo888.top/Article/details/gtldbmgssa.html

data class User(val name: String, val age: Int)
来源：http://dali.daxiang520.top/Article/details/gtuyhiyaxj.html

[T09] Kotlin：扩展函数
来源：http://dali.haohaochexian.top/Article/details/gtktxatpqq.html

fun String.exclaim() = this + "!"
来源：http://dali.yj20258.top/Article/details/gtinminhhq.html

[T10] Kotlin：默认参数
来源：http://dali.bjfxy.top/Article/details/gtgvdovfct.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.birdmap.top/Article/details/gtoomdeaiq.html

[T11] Kotlin：协程
来源：http://dali.guowangkeji.top/Article/details/gthznobimz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hnqzz.top/Article/details/gtraomeluq.html

[T12] Kotlin：解构声明
来源：http://dali.yonumen.top/Article/details/gtjdtixlrz.html

val (a, b) = Pair(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtaiwlrebk.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxuanxn.top/Article/details/gtulbgyosw.html

val m = mapOf("a" to 1)
来源：http://dali.guannengcc.top/Article/details/gtglhqpceu.html

[T14] Kotlin：循环
来源：http://dali.andypj.xyz/Article/details/gtjgmotxss.html

for (i in 1..10) println(i)
来源：http://dali.zhixingplan.top/Article/details/gthhtypklp.html

[T15] Kotlin：接口
来源：http://dali.ppjwa.cn/Article/details/gthcgzdplj.html

interface Shape { fun area(): Double }
来源：http://dali.fengsongda.top/Article/details/gtseiavojr.html

[T16] Swift：Hello World
来源：http://dali.ybcxt.top/Article/details/gtchwvkjfk.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtonvassgh.html

[T17] Swift：变量与常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfuqasua.html

var a = 1;  let b = 2
来源：http://dali.sysykeji.top/Article/details/gtetmukcwg.html

[T18] Swift：字符串插值
来源：http://dali.316326.xyz/Article/details/gtkkxoyoub.html

"值: \(b)"
来源：http://dali.316326.xyz/Article/details/gtncfoehwn.html

[T19] Swift：可选绑定
来源：http://dali.tianlin.xyz/Article/details/gttavprhoh.html

if let n = opt { print(n) }
来源：http://dali.gotoacloud.top/Article/details/gtfoupntmd.html

[T20] Swift：数组操作
来源：http://dali.fengsongda.top/Article/details/gtbkwqhbgd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangshuangyany.cn/Article/details/gtdpckynbr.html

[T21] Swift：遍历
来源：http://dali.xylfe.cn/Article/details/gtlfyfxlvx.html

for x in a { print(x) }
来源：http://dali.chenjidiqi.icu/Article/details/gtjjmtnkrl.html

[T22] Swift：字典
来源：http://dali.birdmap.top/Article/details/gtnafdmdnt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gogol.net.cn/Article/details/gtvrviitbi.html

[T23] Swift：函数
来源：http://dali.havefunace.top/Article/details/gtnbcuevym.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hnqzz.top/Article/details/gtaqrunlrz.html

[T24] Swift：闭包
来源：http://dali.316326.xyz/Article/details/gtdrcbffbw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtrfcskzao.html

[T25] Swift：结构体
来源：http://dali.cheryme.top/Article/details/gtdqynmxze.html

struct P { var x: Int }
来源：http://dali.sweek.top/Article/details/gtcofpzphv.html

[T26] Swift：类与重写
来源：http://dali.jinghuilouyu.cn/Article/details/gtebzjxhzp.html

class A: Base { override func f() {} }
来源：http://dali.snrcjt.cn/Article/details/gtkeilqeqp.html

[T27] Swift：错误处理
来源：http://dali.cheryme.top/Article/details/gtsytjaydv.html

do { try f() } catch { print(error) }
来源：http://dali.iojbl.cn/Article/details/gtezyeltyt.html

[T28] Swift：枚举
来源：http://dali.cheryme.top/Article/details/gtgtyotvxl.html

enum Color { case red, green }
来源：http://dali.0kj1m.cn/Article/details/gtbpvwzkfg.html

[T29] Swift：guard 提前返回
来源：http://dali.sysykeji.top/Article/details/gtctarrxow.html

guard let x = opt else { return }
来源：http://dali.yongpay.top/Article/details/gttqqzdfkp.html

[T30] Swift：协议
来源：http://dali.yonumen.top/Article/details/gtrfipszlv.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxuanxn.top/Article/details/gtpxzidkdc.html

[T31] Lua：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtgwbddruw.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtteklyywq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gttgzzydbv.html

local a = 1
来源：http://dali.xuetiantiany.cn/Article/details/gtyzwjbvgo.html

[T33] Lua：表（数组）
来源：http://dali.redwolf501.top/Article/details/gtfcnvutlu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefktuuxi.html

[T34] Lua：遍历表
来源：http://dali.ybcxt.top/Article/details/gtxaohftvj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hammf.cn/Article/details/gtecuchete.html

[T35] Lua：字典表
来源：http://dali.fengsongda.top/Article/details/gtjtawjbwq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxinkj.top/Article/details/gtzcxhoihx.html

[T36] Lua：函数
来源：http://dali.zhixingplan.top/Article/details/gtvkllriau.html

function add(a, b) return a + b end
来源：http://dali.xuetiantiany.cn/Article/details/gtdnrzrymg.html

[T37] Lua：字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gtliifadqh.html

"a" .. "b"
来源：http://dali.tanke756.top/Article/details/gtgvsuiatg.html

[T38] Lua：条件
来源：http://dali.birdmap.top/Article/details/gtpzpmdlwj.html

if x > 0 then print("正") end
来源：http://dali.zhoulong.xyz/Article/details/gtcqgjecio.html

[T39] Lua：模式匹配
来源：http://dali.cheryme.top/Article/details/gthwwjchyg.html

string.find(s, "%d+")
来源：http://dali.ybcxt.top/Article/details/gtipiuonyt.html

[T40] Lua：元表
来源：http://dali.cdnleiting.top/Article/details/gtfusaybsf.html

setmetatable({}, { __index = base })
来源：http://dali.xuanzx.com/Article/details/gtzwfovznu.html

[T41] Perl：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtuddprwwf.html

print "Hello\n";
来源：http://dali.jinqigufen.top/Article/details/gtsimfaogb.html

[T42] Perl：变量类型
来源：http://dali.zhoulong.xyz/Article/details/gtkgvubdsw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cheryme.top/Article/details/gtwtctqqwt.html

[T43] Perl：字符串插值
来源：http://dali.smart0.xyz/Article/details/gtcwjxxfcj.html

"值: $a"
来源：http://dali.yuanzhike.top/Article/details/gtncuesnqm.html

[T44] Perl：条件
来源：http://dali.yonumen.top/Article/details/gtadjtdgkw.html

if ($a > 0) { print "正"; }
来源：http://dali.cucudq.cn/Article/details/gtzjfztibb.html

[T45] Perl：数组遍历
来源：http://dali.birdmap.top/Article/details/gtckpedwre.html

for my $x (@arr) { print $x; }
来源：http://dali.jinqigfzy.top/Article/details/gtbyfqwrxj.html

[T46] Perl：哈希操作
来源：http://dali.sysykeji.top/Article/details/gtllqmrfca.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ivvv.top/Article/details/gtytkrqelx.html

[T47] Perl：正则捕获
来源：http://dali.gotoacloud.top/Article/details/gtmazqnkka.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gogol.net.cn/Article/details/gtmuvscnqu.html

[T48] Perl：正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcbpygtf.html

$s =~ s/old/new/g;
来源：http://dali.haohaochexian.top/Article/details/gthztcflga.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gtqfvoovnb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtcoevxlqq.html

[T50] Perl：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtolnyoocn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.pengpengdd.cyou/Article/details/gtalupifbx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yueranfly.top/Article/details/gtxiwrgpyz.html

[T51] Scala：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gthrwvnged.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gteopygbkf.html

[T52] Scala：变量
来源：http://dali.0kj1m.cn/Article/details/gtdoknvcvy.html

val a = 1;  var b = 2
来源：http://dali.zdqjudy.top/Article/details/gtspygmnfq.html

[T53] Scala：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gtvrdolbmn.html

s"值: $b"
来源：http://dali.jiagoushi.top/Article/details/gttklrpzon.html

[T54] Scala：集合映射
来源：http://dali.yj20258888.top/Article/details/gtrrholkmz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtuxakjbvf.html

[T55] Scala：集合过滤
来源：http://dali.yanxiufei.cn/Article/details/gtdvriffhe.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gtcjeliamv.html

[T56] Scala：样例类
来源：http://dali.zycfv.cn/Article/details/gtqxbfihex.html

case class User(name: String, age: Int)
来源：http://dali.hysaishi.cn/Article/details/gtpfocheqg.html

[T57] Scala：模式匹配
来源：http://dali.haohaochexian.top/Article/details/gtxmxnygut.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ivvv.top/Article/details/gtzcydqdiu.html

[T58] Scala：函数定义
来源：http://dali.zhiwuduotai.top/Article/details/gtsfdrtdkc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gtqvhvndeg.html

[T59] Scala：循环
来源：http://dali.sufxvd.cn/Article/details/gtgkvnxbue.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gtkbdspmri.html

[T60] Scala：折叠
来源：http://dali.zhongyouzk.top/Article/details/gthjwclefz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.vqdsnc.cn/Article/details/gthfnqtwsr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtckgjuyks.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.feifeiyinyue.top/Article/details/gthxcjxqsa.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtloesswwx.html

[U01] Py：创建虚拟环境
来源：http://dali.shuidangran.top/Article/details/gtndjggyka.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tianlin.xyz/Article/details/gtqzeuejih.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yongpay.top/Article/details/gtdlowcwek.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgfzy.top/Article/details/gtrepyjnfk.html

[U03] Py：加载 .env 配置
来源：http://dali.9152youxi.cn/Article/details/gtvslimprd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.c1oappe.top/Article/details/gtjgtigmly.html

[U04] Py：变量调试打印
来源：http://dali.cqqwz.cn/Article/details/gtewrirock.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hongshengwenyu.top/Article/details/gthnwzbuhf.html

[U05] Py：列表去重且保序
来源：http://dali.jinghuilouyu.cn/Article/details/gttdlplqyu.html

list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqupuwed.html

[U06] Py：合并两个字典
来源：http://dali.dashuyun.cn/Article/details/gtbmfwjnbi.html

{**a, **b}
来源：http://dali.zhoulong.xyz/Article/details/gtlidrtrtw.html

[U07] Py：反转字典键值
来源：http://dali.feifeiyinyue.top/Article/details/gthelmhplo.html

{v: k for k, v in d.items()}
来源：http://dali.shangyingyoupin.top/Article/details/gtkfrvmexx.html

[U08] Py：展平二维列表
来源：http://dali.dianchejie.cn/Article/details/gtrcsgmmmv.html

[y for x in nested for y in x]
来源：http://dali.gaohongyu789.top/Article/details/gtjhhlyfpy.html

[U09] Py：字典取最大值的键
来源：http://dali.hnqzz.top/Article/details/gtwplxhtfn.html

max(d, key=d.get)
来源：http://dali.meibo888.top/Article/details/gtsglhvvju.html

[U10] Py：按值排序字典
来源：http://dali.shuidangran.top/Article/details/gtfiggtuop.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fzhhl.top/Article/details/gtfpgfarxj.html

[U11] Py：生成器表达式
来源：http://dali.gogol.net.cn/Article/details/gthnjnmrxd.html

(x * 2 for x in arr)
来源：http://dali.ppjwa.cn/Article/details/gtphkpdcdi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nanxuanxn.top/Article/details/gtwjwaugjl.html

Counter(arr).most_common(3)
来源：http://dali.gogol.net.cn/Article/details/gtqjluzfkp.html

[U13] Py：固定长度队列
来源：http://dali.yj20258.top/Article/details/gtboycngeg.html

deque(maxlen=10)
来源：http://dali.shzxlz.cn/Article/details/gtjkwpslmi.html

[U14] Py：分组收集到列表
来源：http://dali.sufxvd.cn/Article/details/gtcsuksagf.html

defaultdict(list)
来源：http://dali.daria6918.cn/Article/details/gtdmsohpit.html

[U15] Py：高精度计时
来源：http://dali.zhiwuduotai.top/Article/details/gtenfmbtpq.html

t = time.perf_counter()
来源：http://dali.tian-w.cn/Article/details/gtlpiizgtg.html

[U16] Py：命令行参数解析
来源：http://dali.jinqigfzy.top/Article/details/gtpcdgnvjn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ppjwa.cn/Article/details/gtcexjfgke.html

[U17] Py：初始化日志
来源：http://dali.yvedp.cn/Article/details/gtcibvpkuq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xziqi.cn/Article/details/gtimylwdaw.html

[U18] Py：预编译正则
来源：http://dali.havefunace.top/Article/details/gtzyiisjxj.html

pat = re.compile(r"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gtthppllco.html

[U19] Py：正则替换带回调
来源：http://dali.dianchejie.cn/Article/details/gtgegfibys.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigfzy.top/Article/details/gtntlzlfzw.html

[U20] Py：缓存函数结果
来源：http://dali.hywenlv.cn/Article/details/gtzbnyvyvk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.quarkkingdee.top/Article/details/gtzxeujylm.html


<!-- 参考信息 -->