代发 wailian999

S. C / C++ 专题
来源：http://dali.daria6918.cn/Article/details/gtworhytqn.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtgffpakwr.html

[S01] C：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtuprdvfui.html

#include <stdio.h>
来源：http://dali.hnqzz.top/Article/details/gtyvthmvec.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xylfe.cn/Article/details/gtvowhpdlz.html

[S02] C：变量与格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gtamgibvps.html

int a = 10; printf("%d\n", a);
来源：http://dali.pycfn.com/Article/details/gtsazwsluo.html

[S03] C：读入整数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrtyznpe.html

int x; scanf("%d", &x);
来源：http://dali.yj202588.top/Article/details/gttwxfpfmu.html

[S04] C：字符串复制
来源：http://dali.ydzc1.top/Article/details/gtemxmrdtt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuxming.cn/Article/details/gticqbmzkd.html

[S05] C：字符串长度
来源：http://dali.chenlongwang.top/Article/details/gtnvzmsiye.html

strlen(s)
来源：http://dali.sysykeji.top/Article/details/gtldcdaush.html

[S06] C：字符串比较
来源：http://dali.aibaodan.cn/Article/details/gtgcubmflq.html

strcmp(a, b) == 0
来源：http://dali.zhongyouzk.top/Article/details/gtvoqmobrv.html

[S07] C：数组遍历求和
来源：http://dali.tanke756.top/Article/details/gtfdpxqobe.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sysykeji.top/Article/details/gtrssrfiqw.html

[S08] C：动态内存分配与释放
来源：http://dali.hfpthk.cn/Article/details/gtmuyxawoo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yanxiufei.cn/Article/details/gtccqapypc.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgufenzy.top/Article/details/gtifkliayb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhoulong.xyz/Article/details/gtwzcaiaai.html

[S10] C：指针与解引用
来源：http://dali.birdmap.top/Article/details/gtdbsbmzda.html

int *p = &a;  *p = 5;
来源：http://dali.fzhhl.top/Article/details/gtuavzxqjy.html

[S11] C：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtlqhntjjt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258.top/Article/details/gtajoagtrw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgufenzy.top/Article/details/gtwqblsorv.html

fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gtrvojtnuu.html

[S12] C：写文件
来源：http://dali.yueranfly.top/Article/details/gtxbsftlxi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gtpzuhyjou.html

[S13] C：宏定义
来源：http://dali.zhongyouzk.top/Article/details/gtszgvldps.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sysykeji.top/Article/details/gthkxdxtmc.html

[S14] C：枚举
来源：http://dali.haohaochexian.top/Article/details/gteherxitx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xinyue.icu/Article/details/gtghgizwae.html

[S15] C：类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gtxohkkgoi.html

(double) a / b
来源：http://dali.ehwqpu.com/Article/details/gtsglieboa.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gtbwopfzpb.html

x |= (1 << 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkvasviz.html

[S17] C：安全拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtpyrzlzqd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cucudq.cn/Article/details/gtzcljjuyl.html

[S18] C：命令行参数
来源：http://dali.ivvv.top/Article/details/gtegkgdxzh.html

int main(int argc, char **argv)
来源：http://dali.dianchejie.cn/Article/details/gtwxradwyq.html

[S19] C：快速排序
来源：http://dali.xuanzx.com/Article/details/gtcjugykuk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtuonmmypn.html

[S20] C：二分查找
来源：http://dali.zhiwuduotai.top/Article/details/gttgrulgkv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gtlkayfvvh.html

[S21] C：字符类别判断
来源：http://dali.daxiang520.top/Article/details/gtdpvfrepv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258.top/Article/details/gtrffuacvs.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gtixeqntnd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnqzz.top/Article/details/gtbogtrbfq.html

[S23] C：随机数
来源：http://dali.birdmap.top/Article/details/gturmdthhh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.kuanghao11.cn/Article/details/gtjfeofmrk.html

[S24] C：获取本地时间
来源：http://dali.zhixingplan.top/Article/details/gthekjejvb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhixingplan.top/Article/details/gtbdqinxpd.html

[S25] C：内存拷贝
来源：http://dali.hywenlv.cn/Article/details/gtyyltsgnp.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gtpgfawwnv.html

[S26] C：内存清零
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjfbvheh.html

memset(a, 0, sizeof a);
来源：http://dali.daxiang520.top/Article/details/gtyicsfegl.html

[S27] C：定义常量
来源：http://dali.nwbrower.top/Article/details/gtlqbpjrqw.html

const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtctomdhjl.html

[S28] C：静态变量
来源：http://dali.zdqjudy.top/Article/details/gtqjtyknmo.html

static int counter = 0;
来源：http://dali.chenlongwang.top/Article/details/gtjmwjzbyc.html

[S29] C：变参函数
来源：http://dali.yj202588.top/Article/details/gtylnjihxm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangshuangyany.cn/Article/details/gtrqwqnesu.html

[S30] C：头文件保护
来源：http://dali.chenzaomai.com/Article/details/gtjnbeowbv.html

#ifndef X_H
来源：http://dali.jinqigufen.top/Article/details/gtgsrxeuzn.html

#define X_H
来源：http://dali.hongshengwenyu.top/Article/details/gtshbdqzzl.html

#endif
来源：http://dali.jqgfzy.top/Article/details/gtavggzoam.html

[S31] C++：Hello World
来源：http://dali.cucudq.cn/Article/details/gtuynsfpyd.html

#include <iostream>
来源：http://dali.hnqzz.top/Article/details/gthhhhifwt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dashuyun.cn/Article/details/gtriihhpqx.html

[S32] C++：字符串
来源：http://dali.kuanghao11.cn/Article/details/gtcwcfarwn.html

std::string s = "hi";  s += "!";
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqaapahn.html

[S33] C++：vector 增删
来源：http://dali.quarkkingdee.top/Article/details/gtmefhshdp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gzhubu.top/Article/details/gthvhuywnb.html

[S34] C++：遍历 vector
来源：http://dali.ydzc1.top/Article/details/gthunnaklw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnmaktmr.html

[S35] C++：map
来源：http://dali.jinqigfzy.top/Article/details/gtxvtjoivg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtffpfuhep.html

[S36] C++：unordered_map
来源：http://dali.yangfankeji.com/Article/details/gtmganizqk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtjbuyktgj.html

[S37] C++：set
来源：http://dali.aizwys.cn/Article/details/gtbuqronso.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtcjrghysb.html

[S38] C++：排序
来源：http://dali.haohaochexian.top/Article/details/gtdaypvnwy.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258.top/Article/details/gtblppbxwb.html

[S39] C++：自定义比较器排序
来源：http://dali.pycfn.com/Article/details/gtuqbctmmy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258.top/Article/details/gtpxgqsrxi.html

[S40] C++：查找元素
来源：http://dali.mhx1999.top/Article/details/gtymzqpnmi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yvedp.cn/Article/details/gthidkddhe.html

[S41] C++：类与构造函数
来源：http://dali.snrcjt.cn/Article/details/gthioolchc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pengpengdd.cyou/Article/details/gtdkshqngp.html

[S42] C++：继承与虚函数
来源：http://dali.tianlin.xyz/Article/details/gtxzdmcuna.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilchzdiq.html

[S43] C++：智能指针
来源：http://dali.cdnleiting.top/Article/details/gtndxumfvb.html

auto p = std::make_unique<int>(5);
来源：http://dali.tian-w.cn/Article/details/gtcxscfimv.html

[S44] C++：引用传参
来源：http://dali.tanke756.top/Article/details/gtnyabuzhv.html

void inc(int &x) { ++x; }
来源：http://dali.jianghu66.top/Article/details/gtxespkcjb.html

[S45] C++：lambda
来源：http://dali.redwolf501.top/Article/details/gtzghsital.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.iojbl.cn/Article/details/gteoyxowzn.html

[S46] C++：函数模板
来源：http://dali.zhongyouzk.top/Article/details/gtewzgbzhi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gtbvlfwvut.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gtbygyopho.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.iojbl.cn/Article/details/gtxawfhicr.html

[S48] C++：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtkrthbjdr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yueranfly.top/Article/details/gtthiecigm.html

while (std::getline(in, line)) { }
来源：http://dali.nwbrower.top/Article/details/gtpuedeveb.html

[S49] C++：写文件
来源：http://dali.guannengcc.top/Article/details/gtysakwwhc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuxming.cn/Article/details/gttengazvb.html

[S50] C++：格式化数字
来源：http://dali.andypj.xyz/Article/details/gthmmzmska.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtotjlogig.html

[S51] C++：显式类型转换
来源：http://dali.cheryme.top/Article/details/gtkzzrulkb.html

static_cast<double>(a) / b
来源：http://dali.tianlin.xyz/Article/details/gtrseibajw.html

[S52] C++：const 与 noexcept
来源：http://dali.hfpthk.cn/Article/details/gtvorbnopy.html

int size() const noexcept { return n_; }
来源：http://dali.ydzc1.top/Article/details/gtsmwwitlo.html

[S53] C++：移动语义
来源：http://dali.chenjidiqi.icu/Article/details/gtxtjvorco.html

std::vector<int> w = std::move(v);
来源：http://dali.kuanghao11.cn/Article/details/gtaznvdmwr.html

[S54] C++：异常处理
来源：http://dali.ivvv.top/Article/details/gtrymurfxt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnqzz.top/Article/details/gtfkbbbbow.html

[S55] C++：结构化绑定
来源：http://dali.yongpay.top/Article/details/gtwpjmukkh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jyoumei.cn/Article/details/gtuwpnlsar.html

[S56] C++：optional
来源：http://dali.zhixingplan.top/Article/details/gtcdrlpoqr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daxiang520.top/Article/details/gtxphkotkz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gttvjyvtbm.html

constexpr int N = 10;
来源：http://dali.tianlin.xyz/Article/details/gtzpmhjjsf.html

[S58] C++：命名空间
来源：http://dali.wangshuangyany.cn/Article/details/gtbjjeygnl.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuanzhike.top/Article/details/gtgsjolmfx.html

[S59] C++：静态断言
来源：http://dali.cucudq.cn/Article/details/gtqrugoeor.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shuidangran.top/Article/details/gtmiafudcf.html

[S60] C++：遍历并删除元素
来源：http://dali.svipenyu.cn/Article/details/gtpgtfwppx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gtukfprwwy.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtlzjnwdsj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guowangkeji.top/Article/details/gtvnoxcazc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtsdyiteit.html

[T01] Kotlin：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtfdsidxzu.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtuhepypjn.html

[T02] Kotlin：变量
来源：http://dali.smart0.xyz/Article/details/gtpytykpwk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gaohongyu789.top/Article/details/gtjawmalvz.html

[T03] Kotlin：字符串模板
来源：http://dali.hnqzz.top/Article/details/gtkuwsvlfg.html

"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gtyonzjdow.html

[T04] Kotlin：空安全
来源：http://dali.gogol.net.cn/Article/details/gtbbvnbvzs.html

val n: String? = null;  n?.length
来源：http://dali.mhx1999.top/Article/details/gtgmdptrdv.html

[T05] Kotlin：when 表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtohngrzzq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ydzc1.top/Article/details/gtofxlfixu.html

[T06] Kotlin：集合映射
来源：http://dali.xuanzx.com/Article/details/gtugxkzkvi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sxryk.cn/Article/details/gtegtrtrhv.html

[T07] Kotlin：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gtfekonxxa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zdqjudy.top/Article/details/gthokvnujy.html

[T08] Kotlin：数据类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvxdhhpe.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gtorgbngex.html

[T09] Kotlin：扩展函数
来源：http://dali.yuanzhike.top/Article/details/gtsfhoiabn.html

fun String.exclaim() = this + "!"
来源：http://dali.ppjwa.cn/Article/details/gtnznxqywk.html

[T10] Kotlin：默认参数
来源：http://dali.sufxvd.cn/Article/details/gttbaxblum.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jyoumei.cn/Article/details/gtfsscyskp.html

[T11] Kotlin：协程
来源：http://dali.yj20258.top/Article/details/gtoadvfygu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daria6918.cn/Article/details/gtyezaazhk.html

[T12] Kotlin：解构声明
来源：http://dali.zhongyouzk.top/Article/details/gtyndpmerj.html

val (a, b) = Pair(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfmumnpa.html

[T13] Kotlin：只读 Map
来源：http://dali.ybcxt.top/Article/details/gtswimltju.html

val m = mapOf("a" to 1)
来源：http://dali.havefunace.top/Article/details/gtfpmzxrin.html

[T14] Kotlin：循环
来源：http://dali.chenlongwang.top/Article/details/gttrxhiwwz.html

for (i in 1..10) println(i)
来源：http://dali.xziqi.cn/Article/details/gtetbdbjwf.html

[T15] Kotlin：接口
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgiupcfjp.html

interface Shape { fun area(): Double }
来源：http://dali.nanxuanxn.top/Article/details/gtobhzatkt.html

[T16] Swift：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gttkfiyvpw.html

print("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtfzolxmwc.html

[T17] Swift：变量与常量
来源：http://dali.smart0.xyz/Article/details/gtmvnnmtaa.html

var a = 1;  let b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppcvakgc.html

[T18] Swift：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtunhmwdvq.html

"值: \(b)"
来源：http://dali.pengpengdd.cyou/Article/details/gtochcnsdq.html

[T19] Swift：可选绑定
来源：http://dali.sysykeji.top/Article/details/gtjphvwsyo.html

if let n = opt { print(n) }
来源：http://dali.hammf.cn/Article/details/gttmcydhjk.html

[T20] Swift：数组操作
来源：http://dali.aizwys.cn/Article/details/gtpyhvrxbo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xziqi.cn/Article/details/gtccubugtp.html

[T21] Swift：遍历
来源：http://dali.guannengcc.top/Article/details/gtwpsxbpzb.html

for x in a { print(x) }
来源：http://dali.chenlongwang.top/Article/details/gtklraypup.html

[T22] Swift：字典
来源：http://dali.hnqzz.top/Article/details/gtjecnufnf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cucudq.cn/Article/details/gtepskqdyj.html

[T23] Swift：函数
来源：http://dali.jqgfzy.top/Article/details/gttayafref.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yangfankeji.com/Article/details/gtwzpqqexb.html

[T24] Swift：闭包
来源：http://dali.mhx1999.top/Article/details/gtnanijver.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pycfn.com/Article/details/gtuuklqqaq.html

[T25] Swift：结构体
来源：http://dali.daria6918.cn/Article/details/gtavwlnhhn.html

struct P { var x: Int }
来源：http://dali.nanxinkj.top/Article/details/gtaslccdyj.html

[T26] Swift：类与重写
来源：http://dali.cheryme.top/Article/details/gtddwktpiw.html

class A: Base { override func f() {} }
来源：http://dali.ehwqpu.com/Article/details/gtcvvkmdvc.html

[T27] Swift：错误处理
来源：http://dali.jianghu66.top/Article/details/gtwmgbtper.html

do { try f() } catch { print(error) }
来源：http://dali.jlsjyb.cn/Article/details/gttbxhgbso.html

[T28] Swift：枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtbncknpma.html

enum Color { case red, green }
来源：http://dali.svipenyu.cn/Article/details/gtxiuntllx.html

[T29] Swift：guard 提前返回
来源：http://dali.cucudq.cn/Article/details/gtgnqhbujs.html

guard let x = opt else { return }
来源：http://dali.feifeiyinyue.top/Article/details/gtpzqzszhj.html

[T30] Swift：协议
来源：http://dali.xziqi.cn/Article/details/gtopwzdswx.html

protocol Shape { func area() -> Double }
来源：http://dali.hongshengwenyu.top/Article/details/gtkqayissw.html

[T31] Lua：Hello World
来源：http://dali.guannengcc.top/Article/details/gtpjmebssn.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtuojayekf.html

[T32] Lua：局部变量
来源：http://dali.iojbl.cn/Article/details/gtyqwgwwnf.html

local a = 1
来源：http://dali.haohaochexian.top/Article/details/gtegkbjebr.html

[T33] Lua：表（数组）
来源：http://dali.pengpengdd.cyou/Article/details/gtdifssxoa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.aizwys.cn/Article/details/gtdzhibgii.html

[T34] Lua：遍历表
来源：http://dali.fzhhl.top/Article/details/gtmwabkquf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.snrcjt.cn/Article/details/gtfuvowymp.html

[T35] Lua：字典表
来源：http://dali.havefunace.top/Article/details/gtjbpektgo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tianlin.xyz/Article/details/gtptkrkwfw.html

[T36] Lua：函数
来源：http://dali.sysykeji.top/Article/details/gtpvlxoyes.html

function add(a, b) return a + b end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatwenwon.html

[T37] Lua：字符串拼接
来源：http://dali.jianghu66.top/Article/details/gtlwuhkpgc.html

"a" .. "b"
来源：http://dali.hnxiangtu.top/Article/details/gtvzxwxbzg.html

[T38] Lua：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtxhaaqime.html

if x > 0 then print("正") end
来源：http://dali.hnxiangtu.top/Article/details/gtinajricg.html

[T39] Lua：模式匹配
来源：http://dali.daria6918.cn/Article/details/gtftyszlim.html

string.find(s, "%d+")
来源：http://dali.sysykeji.top/Article/details/gtlrbsnqpb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gtehwuugco.html

setmetatable({}, { __index = base })
来源：http://dali.wangshuangyany.cn/Article/details/gtxtdgqgka.html

[T41] Perl：Hello World
来源：http://dali.daria6918.cn/Article/details/gtalhavmtg.html

print "Hello\n";
来源：http://dali.hammf.cn/Article/details/gtywpqrwbk.html

[T42] Perl：变量类型
来源：http://dali.ivvv.top/Article/details/gtuvqkrwmo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yangfankeji.com/Article/details/gttdyddruo.html

[T43] Perl：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtzjxkoukx.html

"值: $a"
来源：http://dali.jinghuilouyu.cn/Article/details/gtarxkketu.html

[T44] Perl：条件
来源：http://dali.cdnleiting.top/Article/details/gtjverxedt.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigfzy.top/Article/details/gtopvwzrcy.html

[T45] Perl：数组遍历
来源：http://dali.jianghu66.top/Article/details/gteiusvaii.html

for my $x (@arr) { print $x; }
来源：http://dali.guowangkeji.top/Article/details/gtimgqxyri.html

[T46] Perl：哈希操作
来源：http://dali.redwolf501.top/Article/details/gtvyhepfmj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjvnkuwkn.html

[T47] Perl：正则捕获
来源：http://dali.jyoumei.cn/Article/details/gtbhgqmenk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj202588.top/Article/details/gtubcazakn.html

[T48] Perl：正则替换
来源：http://dali.gotoacloud.top/Article/details/gtzkwueedi.html

$s =~ s/old/new/g;
来源：http://dali.haohaochexian.top/Article/details/gtzrgrdqim.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gtwujelyex.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtsmcvobhh.html

[T50] Perl：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtceokcbpe.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvssgrwle.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.c1oappe.top/Article/details/gtqqyrbffi.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdlyalcd.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtulfirfmu.html

[T52] Scala：变量
来源：http://dali.zhixingplan.top/Article/details/gtjcbvctju.html

val a = 1;  var b = 2
来源：http://dali.fzhhl.top/Article/details/gtmfhgpqhi.html

[T53] Scala：字符串插值
来源：http://dali.yuxming.cn/Article/details/gtwjqfpedh.html

s"值: $b"
来源：http://dali.xziqi.cn/Article/details/gtpdapgdoc.html

[T54] Scala：集合映射
来源：http://dali.ybcxt.top/Article/details/gtjcbrqfzk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkkbebgf.html

[T55] Scala：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gtnztvlsng.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhoulong.xyz/Article/details/gtwyoeizem.html

[T56] Scala：样例类
来源：http://dali.kuanghao11.cn/Article/details/gtscqbqwdv.html

case class User(name: String, age: Int)
来源：http://dali.9152youxi.cn/Article/details/gtbvfuanhn.html

[T57] Scala：模式匹配
来源：http://dali.snrcjt.cn/Article/details/gtevpfqfpa.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jqgufenzy.top/Article/details/gtmzmnlzlc.html

[T58] Scala：函数定义
来源：http://dali.zhoulong.xyz/Article/details/gtdacveheq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cashguo.top/Article/details/gtvuolqjlt.html

[T59] Scala：循环
来源：http://dali.jiagoushi.top/Article/details/gtltribjxa.html

for (i <- 1 to 10) println(i)
来源：http://dali.shangyingyoupin.top/Article/details/gthvitescj.html

[T60] Scala：折叠
来源：http://dali.aibaodan.cn/Article/details/gthiinflvp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yanxiufei.cn/Article/details/gtljjaivhd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gttypqcpnv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.9152youxi.cn/Article/details/gtvcgoatyu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjowlphwl.html

[U01] Py：创建虚拟环境
来源：http://dali.yanxiufei.cn/Article/details/gtsmuejsqg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.meibo888.top/Article/details/gtnhudqyny.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fzhhl.top/Article/details/gteatbkyyq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.mhx1999.top/Article/details/gtcoxpagjg.html

[U03] Py：加载 .env 配置
来源：http://dali.iojbl.cn/Article/details/gtwstpnrwg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jianghu66.top/Article/details/gtnqgzfcfb.html

[U04] Py：变量调试打印
来源：http://dali.hfpthk.cn/Article/details/gtujyeemwp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cheryme.top/Article/details/gtzjlmomxo.html

[U05] Py：列表去重且保序
来源：http://dali.fzhhl.top/Article/details/gtrezlyvwd.html

list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvniyxiui.html

[U06] Py：合并两个字典
来源：http://dali.9152youxi.cn/Article/details/gthqsmskwf.html

{**a, **b}
来源：http://dali.ybcxt.top/Article/details/gtztzfyrcc.html

[U07] Py：反转字典键值
来源：http://dali.meibo888.top/Article/details/gtcayhaoxr.html

{v: k for k, v in d.items()}
来源：http://dali.yj202588.top/Article/details/gtnufwnsml.html

[U08] Py：展平二维列表
来源：http://dali.ehwqpu.com/Article/details/gteogtogax.html

[y for x in nested for y in x]
来源：http://dali.haohaochexian.top/Article/details/gtxdnaeray.html

[U09] Py：字典取最大值的键
来源：http://dali.nanxinkj.top/Article/details/gtfayoiebw.html

max(d, key=d.get)
来源：http://dali.yanxiufei.cn/Article/details/gtcloctbxt.html

[U10] Py：按值排序字典
来源：http://dali.daria6918.cn/Article/details/gtxrmkwwwi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.birdmap.top/Article/details/gtjjajvpws.html

[U11] Py：生成器表达式
来源：http://dali.yueranfly.top/Article/details/gtatuijsui.html

(x * 2 for x in arr)
来源：http://dali.zhongyouzk.top/Article/details/gtxjjflpsn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.birdmap.top/Article/details/gtdhlkcoro.html

Counter(arr).most_common(3)
来源：http://dali.yj20258.top/Article/details/gtdyaapsyo.html

[U13] Py：固定长度队列
来源：http://dali.xuetiantiany.cn/Article/details/gtdqgqdptj.html

deque(maxlen=10)
来源：http://dali.nanxinkj.top/Article/details/gtdorgozet.html

[U14] Py：分组收集到列表
来源：http://dali.ppjwa.cn/Article/details/gtgxzeoimt.html

defaultdict(list)
来源：http://dali.xuetiantiany.cn/Article/details/gtlnucyvnw.html

[U15] Py：高精度计时
来源：http://dali.pycfn.com/Article/details/gteoflzokg.html

t = time.perf_counter()
来源：http://dali.ybcxt.top/Article/details/gthumzaobg.html

[U16] Py：命令行参数解析
来源：http://dali.feifeiyinyue.top/Article/details/gtvkyovjsk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jianghu66.top/Article/details/gtygnfsnle.html

[U17] Py：初始化日志
来源：http://dali.zhengqikj.top/Article/details/gtdzhuziaw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xuanzx.com/Article/details/gtxllrhnyk.html

[U18] Py：预编译正则
来源：http://dali.c1oappe.top/Article/details/gtextndmlq.html

pat = re.compile(r"\d+")
来源：http://dali.andypj.xyz/Article/details/gtpwenjnbw.html

[U19] Py：正则替换带回调
来源：http://dali.ybcxt.top/Article/details/gttsiblhag.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jiagoushi.top/Article/details/gtyosqxxkc.html

[U20] Py：缓存函数结果
来源：http://dali.cashguo.top/Article/details/gtqpuzbwcp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.9152youxi.cn/Article/details/gtbdknvksr.html

[U21] Py：自定义上下文管理器
来源：http://dali.cashguo.top/Article/details/gtwrzjygpf.html

@contextlib.contextmanager
来源：http://dali.hysaishi.cn/Article/details/gtrpyfuamy.html

[U22] Py：矩阵转置
来源：http://dali.bjfxy.top/Article/details/gtgsomhect.html

list(zip(*m))
来源：http://dali.0kj1m.cn/Article/details/gtcoohdrni.html


<!-- 参考信息 -->