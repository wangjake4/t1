代发 wailian999

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjbgwwxk.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtxhqffkzz.html

[S01] C：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtqsekqtle.html

#include <stdio.h>
来源：http://dali.jqgufenzy.top/Article/details/gtiktmrmfj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cdnleiting.top/Article/details/gtscjsylki.html

[S02] C：变量与格式化输出
来源：http://dali.yueranfly.top/Article/details/gthjkabbde.html

int a = 10; printf("%d\n", a);
来源：http://dali.aibaodan.cn/Article/details/gttnwrkudp.html

[S03] C：读入整数
来源：http://dali.9152youxi.cn/Article/details/gtrbbmqgdf.html

int x; scanf("%d", &x);
来源：http://dali.cdnleiting.top/Article/details/gtyqimldfa.html

[S04] C：字符串复制
来源：http://dali.zdqjudy.top/Article/details/gtqetbozjg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fengsongda.top/Article/details/gthbrgksxt.html

[S05] C：字符串长度
来源：http://dali.andypj.xyz/Article/details/gtfycldkon.html

strlen(s)
来源：http://dali.aibaodan.cn/Article/details/gtjsxurnvg.html

[S06] C：字符串比较
来源：http://dali.yj202588.top/Article/details/gthsftjplm.html

strcmp(a, b) == 0
来源：http://dali.chenzaomai.com/Article/details/gtfgdzdmlc.html

[S07] C：数组遍历求和
来源：http://dali.yuxming.cn/Article/details/gtxqttcmol.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gtnoipstmv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxwhufac.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigufen.top/Article/details/gtramxdiwk.html

[S09] C：结构体定义与初始化
来源：http://dali.meibo888.top/Article/details/gtdzgbtnqu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhixingplan.top/Article/details/gtxnbmtphe.html

[S10] C：指针与解引用
来源：http://dali.jiagoushi.top/Article/details/gtkecwkqur.html

int *p = &a;  *p = 5;
来源：http://dali.cucudq.cn/Article/details/gtygtecbmw.html

[S11] C：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtwjodyzfr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.meibo888.top/Article/details/gteavabxvl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gtovzhnadn.html

fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtrnftkdol.html

[S12] C：写文件
来源：http://dali.yueranfly.top/Article/details/gtiyuuerty.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gtryowdqjf.html

[S13] C：宏定义
来源：http://dali.yueranfly.top/Article/details/gtrikuuzzy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yangfankeji.com/Article/details/gtipysverp.html

[S14] C：枚举
来源：http://dali.0kj1m.cn/Article/details/gtzsgkmjyl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.svipenyu.cn/Article/details/gtgubatmwt.html

[S15] C：类型转换
来源：http://dali.zhixingplan.top/Article/details/gtbmjpqlye.html

(double) a / b
来源：http://dali.meibo888.top/Article/details/gtnljslfwj.html

[S16] C：位操作置位
来源：http://dali.yj202588.top/Article/details/gtosuuvxcv.html

x |= (1 << 3);
来源：http://dali.yonumen.top/Article/details/gtrdpimyzu.html

[S17] C：安全拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gtkpfqrexd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jiagoushi.top/Article/details/gtqydayuub.html

[S18] C：命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gtxwnlfhix.html

int main(int argc, char **argv)
来源：http://dali.yj20258.top/Article/details/gtzgeyxnyc.html

[S19] C：快速排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlonekixh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gtklaqfifz.html

[S20] C：二分查找
来源：http://dali.zhongyouzk.top/Article/details/gtqwnuctfy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gtqbqjoqzh.html

[S21] C：字符类别判断
来源：http://dali.yangfankeji.com/Article/details/gtomzzpkhi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hysaishi.cn/Article/details/gthybbkhpo.html

[S22] C：字符串转数字
来源：http://dali.sxryk.cn/Article/details/gtlecrdpyb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnqzz.top/Article/details/gtjbskzagy.html

[S23] C：随机数
来源：http://dali.wangdashe.top/Article/details/gtlrprhwkm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinghuilouyu.cn/Article/details/gtaljwnzvy.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gtsrbwphsy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.havefunace.top/Article/details/gtrmysuzvs.html

[S25] C：内存拷贝
来源：http://dali.ppjwa.cn/Article/details/gtxbdyetvt.html

memcpy(dst, src, n);
来源：http://dali.zdqjudy.top/Article/details/gtwgtchwfn.html

[S26] C：内存清零
来源：http://dali.tian-w.cn/Article/details/gtlnvaopzq.html

memset(a, 0, sizeof a);
来源：http://dali.snrcjt.cn/Article/details/gtnzwgmiop.html

[S27] C：定义常量
来源：http://dali.zycfv.cn/Article/details/gtfrdsmrjs.html

const double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghbjpxna.html

[S28] C：静态变量
来源：http://dali.ydzc1.top/Article/details/gtyhuxqjun.html

static int counter = 0;
来源：http://dali.birdmap.top/Article/details/gtybbxlonn.html

[S29] C：变参函数
来源：http://dali.nanxinkj.top/Article/details/gtksxrorsh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ivvv.top/Article/details/gtzkvkzxyq.html

[S30] C：头文件保护
来源：http://dali.aibaodan.cn/Article/details/gtemahaqqc.html

#ifndef X_H
来源：http://dali.hfpthk.cn/Article/details/gtygpgtdnj.html

#define X_H
来源：http://dali.guowangkeji.top/Article/details/gtqbscywcc.html

#endif
来源：http://dali.redwolf501.top/Article/details/gtwweqhvvw.html

[S31] C++：Hello World
来源：http://dali.yvedp.cn/Article/details/gtpuujfgow.html

#include <iostream>
来源：http://dali.meibo888.top/Article/details/gteggbptpf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gtrzkmktwe.html

[S32] C++：字符串
来源：http://dali.gotoacloud.top/Article/details/gtuctbisfs.html

std::string s = "hi";  s += "!";
来源：http://dali.shzxlz.cn/Article/details/gtbckfzgkr.html

[S33] C++：vector 增删
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsceqrwqn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yanxiufei.cn/Article/details/gtiqepwvxb.html

[S34] C++：遍历 vector
来源：http://dali.tanke756.top/Article/details/gthkpqzyyx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nwbrower.top/Article/details/gtbhruanbb.html

[S35] C++：map
来源：http://dali.guannengcc.top/Article/details/gtlsnbaein.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtralkpadj.html

[S36] C++：unordered_map
来源：http://dali.smart0.xyz/Article/details/gtbyzbgktl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gthbvkjndr.html

[S37] C++：set
来源：http://dali.vqdsnc.cn/Article/details/gtcggcrbzn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tian-w.cn/Article/details/gtqfmdivby.html

[S38] C++：排序
来源：http://dali.yueranfly.top/Article/details/gtzbugyvsr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gtwueqljym.html

[S39] C++：自定义比较器排序
来源：http://dali.yonumen.top/Article/details/gtzoffprub.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigfzy.top/Article/details/gtgbshtzxk.html

[S40] C++：查找元素
来源：http://dali.xziqi.cn/Article/details/gtdvkkxhhh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258.top/Article/details/gtodvjpwbs.html

[S41] C++：类与构造函数
来源：http://dali.yuxming.cn/Article/details/gtqpywnuhu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgufenzy.top/Article/details/gtoveecgev.html

[S42] C++：继承与虚函数
来源：http://dali.yanxiufei.cn/Article/details/gtvejukrzt.html

class B : public Base { public: void f() override {} };
来源：http://dali.andypj.xyz/Article/details/gtsvdnyztm.html

[S43] C++：智能指针
来源：http://dali.zdqjudy.top/Article/details/gtyptcoewv.html

auto p = std::make_unique<int>(5);
来源：http://dali.vqdsnc.cn/Article/details/gtvcmlsjyj.html

[S44] C++：引用传参
来源：http://dali.316326.xyz/Article/details/gttyqvclru.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigfzy.top/Article/details/gtnjsmcbrt.html

[S45] C++：lambda
来源：http://dali.jianghu66.top/Article/details/gtbjujdiln.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cdnleiting.top/Article/details/gtnhqngifz.html

[S46] C++：函数模板
来源：http://dali.aizwys.cn/Article/details/gtuhibmdyh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yanxiufei.cn/Article/details/gtttppgspt.html

[S47] C++：结构化绑定遍历
来源：http://dali.hammf.cn/Article/details/gtdllqxhnq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sweek.top/Article/details/gthplmtmkw.html

[S48] C++：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtshrjxngu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dashuyun.cn/Article/details/gtbfegrmzp.html

while (std::getline(in, line)) { }
来源：http://dali.yueranfly.top/Article/details/gtvelxktlc.html

[S49] C++：写文件
来源：http://dali.gotoacloud.top/Article/details/gtescdmtol.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xylfe.cn/Article/details/gtbnqilkap.html

[S50] C++：格式化数字
来源：http://dali.yonumen.top/Article/details/gtummfknan.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtaieojvgv.html

[S51] C++：显式类型转换
来源：http://dali.chenzaomai.com/Article/details/gtjwrvltur.html

static_cast<double>(a) / b
来源：http://dali.wangshuangyany.cn/Article/details/gtzgjzfcvn.html

[S52] C++：const 与 noexcept
来源：http://dali.yuanzhike.top/Article/details/gtredewnnf.html

int size() const noexcept { return n_; }
来源：http://dali.yanxiufei.cn/Article/details/gtqrieaoua.html

[S53] C++：移动语义
来源：http://dali.yanxiufei.cn/Article/details/gtdoqdiqhw.html

std::vector<int> w = std::move(v);
来源：http://dali.havefunace.top/Article/details/gtbsnzcqgm.html

[S54] C++：异常处理
来源：http://dali.iojbl.cn/Article/details/gtjfleekgp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fengsongda.top/Article/details/gtgbdshkgd.html

[S55] C++：结构化绑定
来源：http://dali.ybcxt.top/Article/details/gtixidamav.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sxryk.cn/Article/details/gtguiwmboe.html

[S56] C++：optional
来源：http://dali.zhongyouzk.top/Article/details/gtytfitcsx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.smart0.xyz/Article/details/gtrchricmn.html

[S57] C++：编译期常量
来源：http://dali.pengpengdd.cyou/Article/details/gtqkwgkxby.html

constexpr int N = 10;
来源：http://dali.aizwys.cn/Article/details/gtauvctqgi.html

[S58] C++：命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gtgljtogiq.html

namespace ns { int f() { return 1; } }
来源：http://dali.mhx1999.top/Article/details/gtiapjkmik.html

[S59] C++：静态断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvfwbbxi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guowangkeji.top/Article/details/gtgrapgeba.html

[S60] C++：遍历并删除元素
来源：http://dali.ivvv.top/Article/details/gtjtqznmgq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.iojbl.cn/Article/details/gtzfkqnapk.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtqjfmimhp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gtdvqvdrbu.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtmdduntmq.html

[T01] Kotlin：Hello World
来源：http://dali.shuidangran.top/Article/details/gtwkcxklgt.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gtempfwlbf.html

[T02] Kotlin：变量
来源：http://dali.snrcjt.cn/Article/details/gtulyfwqro.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigufen.top/Article/details/gtyxnupfup.html

[T03] Kotlin：字符串模板
来源：http://dali.iojbl.cn/Article/details/gtzkhshsmd.html

"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gtbxmwssxr.html

[T04] Kotlin：空安全
来源：http://dali.guannengcc.top/Article/details/gtrvwlfcgm.html

val n: String? = null;  n?.length
来源：http://dali.smart0.xyz/Article/details/gtpgvpmqwn.html

[T05] Kotlin：when 表达式
来源：http://dali.guannengcc.top/Article/details/gtvvdjekys.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.c1oappe.top/Article/details/gtcavwgqie.html

[T06] Kotlin：集合映射
来源：http://dali.xuetiantiany.cn/Article/details/gthbplsobn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtroegiyuk.html

[T07] Kotlin：集合过滤
来源：http://dali.yangfankeji.com/Article/details/gtobcrnnep.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jyoumei.cn/Article/details/gtrfnfvdsx.html

[T08] Kotlin：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gtifbdhfma.html

data class User(val name: String, val age: Int)
来源：http://dali.zhixingplan.top/Article/details/gthgpcfvso.html

[T09] Kotlin：扩展函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbacgmbi.html

fun String.exclaim() = this + "!"
来源：http://dali.svipenyu.cn/Article/details/gtoevkmkyb.html

[T10] Kotlin：默认参数
来源：http://dali.birdmap.top/Article/details/gtvcvpbpas.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ydzc1.top/Article/details/gtuwydkmuc.html

[T11] Kotlin：协程
来源：http://dali.zhengqikj.top/Article/details/gtkvghkhkh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.redwolf501.top/Article/details/gtbnrhreir.html

[T12] Kotlin：解构声明
来源：http://dali.snrcjt.cn/Article/details/gtqgwrsfqb.html

val (a, b) = Pair(1, 2)
来源：http://dali.sweek.top/Article/details/gtzdoqveba.html

[T13] Kotlin：只读 Map
来源：http://dali.xziqi.cn/Article/details/gtmsyrpkju.html

val m = mapOf("a" to 1)
来源：http://dali.snrcjt.cn/Article/details/gtluqeicup.html

[T14] Kotlin：循环
来源：http://dali.yueranfly.top/Article/details/gtqvbfqcvg.html

for (i in 1..10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtfiradaog.html

[T15] Kotlin：接口
来源：http://dali.jianghu66.top/Article/details/gtglcbredf.html

interface Shape { fun area(): Double }
来源：http://dali.cdnleiting.top/Article/details/gttmbfzwzx.html

[T16] Swift：Hello World
来源：http://dali.c1oappe.top/Article/details/gtjqvgezeu.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gtwhvuxymu.html

[T17] Swift：变量与常量
来源：http://dali.yonumen.top/Article/details/gtrxflhwac.html

var a = 1;  let b = 2
来源：http://dali.gogol.net.cn/Article/details/gtdyjscxvs.html

[T18] Swift：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtquvhmsog.html

"值: \(b)"
来源：http://dali.gotoacloud.top/Article/details/gtcxnlecax.html

[T19] Swift：可选绑定
来源：http://dali.yj202588.top/Article/details/gtoluskjpw.html

if let n = opt { print(n) }
来源：http://dali.haohaochexian.top/Article/details/gtnvkzwbho.html

[T20] Swift：数组操作
来源：http://dali.hammf.cn/Article/details/gtzibhhcff.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.316326.xyz/Article/details/gtksyvzmyu.html

[T21] Swift：遍历
来源：http://dali.xylfe.cn/Article/details/gtjbhgmtgt.html

for x in a { print(x) }
来源：http://dali.fengsongda.top/Article/details/gthvuvxezg.html

[T22] Swift：字典
来源：http://dali.dashuyun.cn/Article/details/gtqnxbkkmt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yvedp.cn/Article/details/gtookhxpsp.html

[T23] Swift：函数
来源：http://dali.nwbrower.top/Article/details/gteqylktrw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guowangkeji.top/Article/details/gtidbulyaf.html

[T24] Swift：闭包
来源：http://dali.haohaochexian.top/Article/details/gtjzpvlqxy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gtqyrqzzxa.html

[T25] Swift：结构体
来源：http://dali.sweek.top/Article/details/gtbrejsywn.html

struct P { var x: Int }
来源：http://dali.iojbl.cn/Article/details/gtacfvlqkv.html

[T26] Swift：类与重写
来源：http://dali.dianchejie.cn/Article/details/gtujcyqntr.html

class A: Base { override func f() {} }
来源：http://dali.smart0.xyz/Article/details/gtebrifgfs.html

[T27] Swift：错误处理
来源：http://dali.iojbl.cn/Article/details/gtamvdkuau.html

do { try f() } catch { print(error) }
来源：http://dali.sweek.top/Article/details/gtqbizaymm.html

[T28] Swift：枚举
来源：http://dali.havefunace.top/Article/details/gtqzqicvqe.html

enum Color { case red, green }
来源：http://dali.cucudq.cn/Article/details/gtkfogvgls.html

[T29] Swift：guard 提前返回
来源：http://dali.snrcjt.cn/Article/details/gtivbfoqjj.html

guard let x = opt else { return }
来源：http://dali.jinqigufen.top/Article/details/gtogperbcj.html

[T30] Swift：协议
来源：http://dali.ydzc1.top/Article/details/gtsjubjxky.html

protocol Shape { func area() -> Double }
来源：http://dali.hnxiangtu.top/Article/details/gtfhgysdwe.html

[T31] Lua：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtzozfmbjc.html

print("Hello")
来源：http://dali.sxryk.cn/Article/details/gtuwppzewt.html

[T32] Lua：局部变量
来源：http://dali.fengsongda.top/Article/details/gtciymtycb.html

local a = 1
来源：http://dali.zycfv.cn/Article/details/gturbvpnef.html

[T33] Lua：表（数组）
来源：http://dali.gaohongyu789.top/Article/details/gtmldkowyi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sysykeji.top/Article/details/gtqxydpsnz.html

[T34] Lua：遍历表
来源：http://dali.aibaodan.cn/Article/details/gtenffhozy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xinyue.icu/Article/details/gtocoegwga.html

[T35] Lua：字典表
来源：http://dali.shangyingyoupin.top/Article/details/gtqpmdydjx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhengqikj.top/Article/details/gtpbwmiwpx.html

[T36] Lua：函数
来源：http://dali.vqdsnc.cn/Article/details/gtbgxtyljs.html

function add(a, b) return a + b end
来源：http://dali.aizwys.cn/Article/details/gtfobimntd.html

[T37] Lua：字符串拼接
来源：http://dali.hammf.cn/Article/details/gtkmfembwc.html

"a" .. "b"
来源：http://dali.xuanzx.com/Article/details/gtbtzuscoi.html

[T38] Lua：条件
来源：http://dali.chenjidiqi.icu/Article/details/gtygcsaayi.html

if x > 0 then print("正") end
来源：http://dali.zhengqikj.top/Article/details/gtjkmfnodv.html

[T39] Lua：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gtuazmfpzw.html

string.find(s, "%d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtxpyzafna.html

[T40] Lua：元表
来源：http://dali.316326.xyz/Article/details/gtydqqukbm.html

setmetatable({}, { __index = base })
来源：http://dali.zhongyouzk.top/Article/details/gtskyyzlti.html

[T41] Perl：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtwxurgxqk.html

print "Hello\n";
来源：http://dali.jinqigfzy.top/Article/details/gtmmegidom.html

[T42] Perl：变量类型
来源：http://dali.zycfv.cn/Article/details/gtzxctzfvh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hnxiangtu.top/Article/details/gtjdmyemiy.html

[T43] Perl：字符串插值
来源：http://dali.316326.xyz/Article/details/gtatbrfbbx.html

"值: $a"
来源：http://dali.ivvv.top/Article/details/gthjszbkfc.html

[T44] Perl：条件
来源：http://dali.c1oappe.top/Article/details/gthxeuzxih.html

if ($a > 0) { print "正"; }
来源：http://dali.svipenyu.cn/Article/details/gtnubjpdht.html

[T45] Perl：数组遍历
来源：http://dali.jiagoushi.top/Article/details/gteutcsnva.html

for my $x (@arr) { print $x; }
来源：http://dali.nanxinkj.top/Article/details/gtemhahrmh.html

[T46] Perl：哈希操作
来源：http://dali.jyoumei.cn/Article/details/gtycfiytzm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.birdmap.top/Article/details/gtzkgfbvas.html

[T47] Perl：正则捕获
来源：http://dali.cheryme.top/Article/details/gtgozhlosg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.c1oappe.top/Article/details/gtwxjmxbhn.html

[T48] Perl：正则替换
来源：http://dali.jianghu66.top/Article/details/gtbosaplly.html

$s =~ s/old/new/g;
来源：http://dali.fzhhl.top/Article/details/gtnndwobeb.html

[T49] Perl：函数
来源：http://dali.yj20258888.top/Article/details/gtysasyeib.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtqetfjnus.html

[T50] Perl：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtmnzrimns.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hysaishi.cn/Article/details/gtwriidgua.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gtonrxqnjo.html

[T51] Scala：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtqcibryni.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtgervbbnr.html

[T52] Scala：变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgrnfsjx.html

val a = 1;  var b = 2
来源：http://dali.iojbl.cn/Article/details/gtxaubmecl.html

[T53] Scala：字符串插值
来源：http://dali.cheryme.top/Article/details/gtjonhlgbh.html

s"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gtgeqoaqep.html

[T54] Scala：集合映射
来源：http://dali.ehwqpu.com/Article/details/gtfknpdssx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinqigfzy.top/Article/details/gtyfjiqyll.html

[T55] Scala：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gtebafgswu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.snrcjt.cn/Article/details/gtdwtpliew.html

[T56] Scala：样例类
来源：http://dali.sysykeji.top/Article/details/gthyddrhuu.html

case class User(name: String, age: Int)
来源：http://dali.gzhubu.top/Article/details/gtwcqrzjbi.html

[T57] Scala：模式匹配
来源：http://dali.vqdsnc.cn/Article/details/gtwvzvdjqv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jlsjyb.cn/Article/details/gtyzvmxmme.html

[T58] Scala：函数定义
来源：http://dali.xuanzx.com/Article/details/gtybihfbpt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hysaishi.cn/Article/details/gtcdbjuqnw.html

[T59] Scala：循环
来源：http://dali.cheryme.top/Article/details/gtrymckbbf.html

for (i <- 1 to 10) println(i)
来源：http://dali.gzhubu.top/Article/details/gtqjcgofop.html

[T60] Scala：折叠
来源：http://dali.aizwys.cn/Article/details/gtoiuaaxyb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ppjwa.cn/Article/details/gtpbxdwptn.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtxhiffqrn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aibaodan.cn/Article/details/gtzxhygpqu.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtixdgztnp.html

[U01] Py：创建虚拟环境
来源：http://dali.jqgufenzy.top/Article/details/gtbcalvcaf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinghuilouyu.cn/Article/details/gthayngcba.html

[U02] Py：导出 / 安装依赖
来源：http://dali.birdmap.top/Article/details/gtuqevtata.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sufxvd.cn/Article/details/gtdcfpdtpe.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gtqyeedmne.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sxryk.cn/Article/details/gtnnozqmxh.html

[U04] Py：变量调试打印
来源：http://dali.hnqzz.top/Article/details/gtczxrozil.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cheryme.top/Article/details/gtyofsulmz.html

[U05] Py：列表去重且保序
来源：http://dali.vqdsnc.cn/Article/details/gtyhycbzgb.html

list(dict.fromkeys(arr))
来源：http://dali.yj202588.top/Article/details/gtrkhzugvz.html

[U06] Py：合并两个字典
来源：http://dali.daria6918.cn/Article/details/gtpnxpnsiy.html

{**a, **b}
来源：http://dali.shangyingyoupin.top/Article/details/gtdtrzvsrn.html

[U07] Py：反转字典键值
来源：http://dali.cheryme.top/Article/details/gtswpzoajz.html

{v: k for k, v in d.items()}
来源：http://dali.jinqigfzy.top/Article/details/gtpshnxxsz.html

[U08] Py：展平二维列表
来源：http://dali.yueranfly.top/Article/details/gtdzvhpesn.html

[y for x in nested for y in x]
来源：http://dali.316326.xyz/Article/details/gtarfyplqr.html

[U09] Py：字典取最大值的键
来源：http://dali.yangfankeji.com/Article/details/gtujryojch.html

max(d, key=d.get)
来源：http://dali.hongshengwenyu.top/Article/details/gtpzkamlwz.html

[U10] Py：按值排序字典
来源：http://dali.guannengcc.top/Article/details/gtsswilirp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pycfn.com/Article/details/gtmasxseul.html

[U11] Py：生成器表达式
来源：http://dali.jqgufenzy.top/Article/details/gtyapwltzj.html

(x * 2 for x in arr)
来源：http://dali.zhongyouzk.top/Article/details/gtlrecvebk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sysykeji.top/Article/details/gtqjzpbupc.html

Counter(arr).most_common(3)
来源：http://dali.snrcjt.cn/Article/details/gtpduyelal.html

[U13] Py：固定长度队列
来源：http://dali.cdnleiting.top/Article/details/gtgovaslrd.html

deque(maxlen=10)
来源：http://dali.xuetiantiany.cn/Article/details/gteaavatrt.html

[U14] Py：分组收集到列表
来源：http://dali.pycfn.com/Article/details/gtqrqfuvdb.html

defaultdict(list)
来源：http://dali.nwbrower.top/Article/details/gttyggpbhb.html

[U15] Py：高精度计时
来源：http://dali.mhx1999.top/Article/details/gtoucvquqe.html

t = time.perf_counter()
来源：http://dali.birdmap.top/Article/details/gtnqpabhyn.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvwstxrs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cdnleiting.top/Article/details/gtwnmxwcao.html

[U17] Py：初始化日志
来源：http://dali.gaohongyu789.top/Article/details/gtxwgnvoum.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ydzc1.top/Article/details/gtxfeopcul.html

[U18] Py：预编译正则
来源：http://dali.jlsjyb.cn/Article/details/gtxfaxmcvz.html

pat = re.compile(r"\d+")
来源：http://dali.zdqjudy.top/Article/details/gtncfgblhb.html

[U19] Py：正则替换带回调
来源：http://dali.gaohongyu789.top/Article/details/gtewdectkc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.svipenyu.cn/Article/details/gtixdhamev.html

[U20] Py：缓存函数结果
来源：http://dali.yj202588.top/Article/details/gtvhsthbik.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmttwfvm.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolpjjjcs.html

@contextlib.contextmanager
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzoilkpe.html

[U22] Py：矩阵转置
来源：http://dali.chenjidiqi.icu/Article/details/gtgxooybte.html

list(zip(*m))
来源：http://dali.cashguo.top/Article/details/gtdalachqa.html


<!-- 参考信息 -->