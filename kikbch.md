代发 wailian999

S. C / C++ 专题
来源：http://dali.cucudq.cn/Article/details/gtbhjbccit.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtbejraqxr.html

[S01] C：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtliouxjyx.html

#include <stdio.h>
来源：http://dali.yuxming.cn/Article/details/gteilwwrka.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuxming.cn/Article/details/gttuwefshr.html

[S02] C：变量与格式化输出
来源：http://dali.xziqi.cn/Article/details/gtpepuawtz.html

int a = 10; printf("%d\n", a);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlitsjgpu.html

[S03] C：读入整数
来源：http://dali.pycfn.com/Article/details/gtfzuqdnbh.html

int x; scanf("%d", &x);
来源：http://dali.jqgufenzy.top/Article/details/gtctaxiktp.html

[S04] C：字符串复制
来源：http://dali.mhx1999.top/Article/details/gtufjhczij.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gogol.net.cn/Article/details/gtldgfyvyy.html

[S05] C：字符串长度
来源：http://dali.shuidangran.top/Article/details/gtxmydiftt.html

strlen(s)
来源：http://dali.jinqigufen.top/Article/details/gtuulnmlxj.html

[S06] C：字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gtvhvzebns.html

strcmp(a, b) == 0
来源：http://dali.chenzaomai.com/Article/details/gtjzvomjeu.html

[S07] C：数组遍历求和
来源：http://dali.pengpengdd.cyou/Article/details/gtxhqrfsgi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangdashe.top/Article/details/gtihuqkdkm.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgfzy.top/Article/details/gtuyugygnj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xinyue.icu/Article/details/gtjukfgohr.html

[S09] C：结构体定义与初始化
来源：http://dali.nanxinkj.top/Article/details/gtyjgelhjq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.fzhhl.top/Article/details/gtwjgiovvn.html

[S10] C：指针与解引用
来源：http://dali.gzhubu.top/Article/details/gtcgxopnln.html

int *p = &a;  *p = 5;
来源：http://dali.daxiang520.top/Article/details/gtamybpmic.html

[S11] C：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtsaphvbqw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.redwolf501.top/Article/details/gtggzmealj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tian-w.cn/Article/details/gtexwxmixb.html

fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gtnzmvfgtb.html

[S12] C：写文件
来源：http://dali.jlsjyb.cn/Article/details/gtvtrztlwx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gtergbksxu.html

[S13] C：宏定义
来源：http://dali.yj20258888.top/Article/details/gtdyhlecnt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cheryme.top/Article/details/gtfmuspsak.html

[S14] C：枚举
来源：http://dali.hongshengwenyu.top/Article/details/gtbilmbfqk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.svipenyu.cn/Article/details/gtxqejaawp.html

[S15] C：类型转换
来源：http://dali.dianchejie.cn/Article/details/gthhqmogfs.html

(double) a / b
来源：http://dali.cheryme.top/Article/details/gtgjvsxfzo.html

[S16] C：位操作置位
来源：http://dali.cashguo.top/Article/details/gtpiihppoa.html

x |= (1 << 3);
来源：http://dali.hnxiangtu.top/Article/details/gtttkaxiki.html

[S17] C：安全拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtyaefoswl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shuidangran.top/Article/details/gtgsnvkkdu.html

[S18] C：命令行参数
来源：http://dali.wangdashe.top/Article/details/gthkoasqfl.html

int main(int argc, char **argv)
来源：http://dali.yuanzhike.top/Article/details/gtxudqhdvp.html

[S19] C：快速排序
来源：http://dali.chenjidiqi.icu/Article/details/gtltfrjrok.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddckaatd.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gttyhqbnvb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gtzapllhjp.html

[S21] C：字符类别判断
来源：http://dali.redwolf501.top/Article/details/gtszvplrjr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jyoumei.cn/Article/details/gtdrffsexy.html

[S22] C：字符串转数字
来源：http://dali.xinyue.icu/Article/details/gtzofhgmwp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxuanxn.top/Article/details/gtyvujsedo.html

[S23] C：随机数
来源：http://dali.redwolf501.top/Article/details/gtiaesontq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yonumen.top/Article/details/gtywgiaoxu.html

[S24] C：获取本地时间
来源：http://dali.hammf.cn/Article/details/gtqsuxdzdg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.0kj1m.cn/Article/details/gtuukvudzy.html

[S25] C：内存拷贝
来源：http://dali.wangdashe.top/Article/details/gtoqlytbfx.html

memcpy(dst, src, n);
来源：http://dali.bjfxy.top/Article/details/gtugfcotyc.html

[S26] C：内存清零
来源：http://dali.aibaodan.cn/Article/details/gtvjfxfxej.html

memset(a, 0, sizeof a);
来源：http://dali.jiagoushi.top/Article/details/gtulaacldr.html

[S27] C：定义常量
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbxfjdqu.html

const double PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtgwukggbz.html

[S28] C：静态变量
来源：http://dali.ehwqpu.com/Article/details/gtlasxdmzf.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gtfrshufws.html

[S29] C：变参函数
来源：http://dali.sxryk.cn/Article/details/gtgderysjp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhgsvzio.html

[S30] C：头文件保护
来源：http://dali.0kj1m.cn/Article/details/gtnrcvbiqg.html

#ifndef X_H
来源：http://dali.aibaodan.cn/Article/details/gtoqdwpbbi.html

#define X_H
来源：http://dali.yj202588.top/Article/details/gtemvjffcr.html

#endif
来源：http://dali.daxiang520.top/Article/details/gtqswhtfpj.html

[S31] C++：Hello World
来源：http://dali.aizwys.cn/Article/details/gtobschajz.html

#include <iostream>
来源：http://dali.shuidangran.top/Article/details/gtluvhhwmh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ppjwa.cn/Article/details/gteaxsdhes.html

[S32] C++：字符串
来源：http://dali.yongpay.top/Article/details/gtkoumsgay.html

std::string s = "hi";  s += "!";
来源：http://dali.xuanzx.com/Article/details/gtertxvwjz.html

[S33] C++：vector 增删
来源：http://dali.guannengcc.top/Article/details/gtjuuqspln.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dashuyun.cn/Article/details/gtneevrakn.html

[S34] C++：遍历 vector
来源：http://dali.gotoacloud.top/Article/details/gtvvhgqobs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gzhubu.top/Article/details/gtobngnptl.html

[S35] C++：map
来源：http://dali.sweek.top/Article/details/gtlblxnuyq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gtbvzrcmzn.html

[S36] C++：unordered_map
来源：http://dali.sxryk.cn/Article/details/gtmdhhxgcn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gttbqqcbtd.html

[S37] C++：set
来源：http://dali.sufxvd.cn/Article/details/gtqlisxpdc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gtxkjglrfy.html

[S38] C++：排序
来源：http://dali.yj20258.top/Article/details/gtjmcxhtfs.html

std::sort(v.begin(), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gtkavmexla.html

[S39] C++：自定义比较器排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtqigepwvk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ppjwa.cn/Article/details/gtprteqnvc.html

[S40] C++：查找元素
来源：http://dali.pengpengdd.cyou/Article/details/gtgpayzltp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.meibo888.top/Article/details/gttujahwwz.html

[S41] C++：类与构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtlitekmpe.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hysaishi.cn/Article/details/gtalqmebah.html

[S42] C++：继承与虚函数
来源：http://dali.yuanzhike.top/Article/details/gtazlvcqsv.html

class B : public Base { public: void f() override {} };
来源：http://dali.tian-w.cn/Article/details/gtyblehphj.html

[S43] C++：智能指针
来源：http://dali.bjfxy.top/Article/details/gtvvzndjcb.html

auto p = std::make_unique<int>(5);
来源：http://dali.meibo888.top/Article/details/gtcmmetcsj.html

[S44] C++：引用传参
来源：http://dali.fzhhl.top/Article/details/gtebiylqad.html

void inc(int &x) { ++x; }
来源：http://dali.tian-w.cn/Article/details/gtqkbwnsdp.html

[S45] C++：lambda
来源：http://dali.gaohongyu789.top/Article/details/gtthgrhvyu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sysykeji.top/Article/details/gtwujmlsrs.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gthjpdqlsa.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepmvexqv.html

[S47] C++：结构化绑定遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlgzsjoi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ydzc1.top/Article/details/gtfexcqqal.html

[S48] C++：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtaeqhixyi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtisomzotm.html

while (std::getline(in, line)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gthvdkxcom.html

[S49] C++：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gtabcyceqy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.iojbl.cn/Article/details/gtrbhcadsf.html

[S50] C++：格式化数字
来源：http://dali.yuanzhike.top/Article/details/gtitljnmxm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtujbaddod.html

[S51] C++：显式类型转换
来源：http://dali.pycfn.com/Article/details/gtlkciqjju.html

static_cast<double>(a) / b
来源：http://dali.jqgfzy.top/Article/details/gtkscnfqfb.html

[S52] C++：const 与 noexcept
来源：http://dali.yuxming.cn/Article/details/gtmctdglph.html

int size() const noexcept { return n_; }
来源：http://dali.zhixingplan.top/Article/details/gtwfwkapaz.html

[S53] C++：移动语义
来源：http://dali.dashuyun.cn/Article/details/gtqbqtjigi.html

std::vector<int> w = std::move(v);
来源：http://dali.aizwys.cn/Article/details/gtisxnebed.html

[S54] C++：异常处理
来源：http://dali.kuanghao11.cn/Article/details/gtgbfkrhrm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtlwoxzixo.html

[S55] C++：结构化绑定
来源：http://dali.gaohongyu789.top/Article/details/gtkisvfnsu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sxryk.cn/Article/details/gtivwepaho.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gtmhvdojuj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.c1oappe.top/Article/details/gtnyyfoqmr.html

[S57] C++：编译期常量
来源：http://dali.gogol.net.cn/Article/details/gtepxuyhcq.html

constexpr int N = 10;
来源：http://dali.jinqigufen.top/Article/details/gtuyhbmrpr.html

[S58] C++：命名空间
来源：http://dali.aibaodan.cn/Article/details/gtmvkhdhln.html

namespace ns { int f() { return 1; } }
来源：http://dali.vqdsnc.cn/Article/details/gtjekidaen.html

[S59] C++：静态断言
来源：http://dali.yongpay.top/Article/details/gtdpleglrv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangshuangyany.cn/Article/details/gtzyamsexi.html

[S60] C++：遍历并删除元素
来源：http://dali.cqqwz.cn/Article/details/gtwgmguxpv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guowangkeji.top/Article/details/gtkdyaikpj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtqugpfcmv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gtagchecah.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtycxhsjzn.html

[T01] Kotlin：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtvtdwrqfq.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtjjnwrhjg.html

[T02] Kotlin：变量
来源：http://dali.fengsongda.top/Article/details/gtcpzukyzi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shzxlz.cn/Article/details/gtkkrypxvg.html

[T03] Kotlin：字符串模板
来源：http://dali.svipenyu.cn/Article/details/gtzontymys.html

"值: $b"
来源：http://dali.fengsongda.top/Article/details/gtngssidhw.html

[T04] Kotlin：空安全
来源：http://dali.yangfankeji.com/Article/details/gtsgdoobwc.html

val n: String? = null;  n?.length
来源：http://dali.shzxlz.cn/Article/details/gtmnvblbgk.html

[T05] Kotlin：when 表达式
来源：http://dali.yanxiufei.cn/Article/details/gthevsuufb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hfpthk.cn/Article/details/gtqfaophnw.html

[T06] Kotlin：集合映射
来源：http://dali.c1oappe.top/Article/details/gtuncqqxfk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.svipenyu.cn/Article/details/gthnzdclix.html

[T07] Kotlin：集合过滤
来源：http://dali.jianghu66.top/Article/details/gtfrgingpm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daxiang520.top/Article/details/gtkabhrwtb.html

[T08] Kotlin：数据类
来源：http://dali.shuidangran.top/Article/details/gtdocxzejb.html

data class User(val name: String, val age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gtzlskippk.html

[T09] Kotlin：扩展函数
来源：http://dali.nwbrower.top/Article/details/gtejowjbfl.html

fun String.exclaim() = this + "!"
来源：http://dali.yangfankeji.com/Article/details/gtzzyupuhy.html

[T10] Kotlin：默认参数
来源：http://dali.hammf.cn/Article/details/gtogrtqkwp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jiagoushi.top/Article/details/gtutxtcbiq.html

[T11] Kotlin：协程
来源：http://dali.jinqigfzy.top/Article/details/gtilijibps.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cqqwz.cn/Article/details/gtjrfryngu.html

[T12] Kotlin：解构声明
来源：http://dali.sweek.top/Article/details/gtubdjxfhb.html

val (a, b) = Pair(1, 2)
来源：http://dali.yongpay.top/Article/details/gttyufagcx.html

[T13] Kotlin：只读 Map
来源：http://dali.hnqzz.top/Article/details/gtjbugdvtr.html

val m = mapOf("a" to 1)
来源：http://dali.guowangkeji.top/Article/details/gtpqglgiuo.html

[T14] Kotlin：循环
来源：http://dali.xuetiantiany.cn/Article/details/gtfelvsiur.html

for (i in 1..10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gtsgogmlzu.html

[T15] Kotlin：接口
来源：http://dali.hnxiangtu.top/Article/details/gtvcrcmebc.html

interface Shape { fun area(): Double }
来源：http://dali.hfpthk.cn/Article/details/gtabwjenbc.html

[T16] Swift：Hello World
来源：http://dali.gzhubu.top/Article/details/gtwnsvmczw.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtlcgssxun.html

[T17] Swift：变量与常量
来源：http://dali.haohaochexian.top/Article/details/gterbspcch.html

var a = 1;  let b = 2
来源：http://dali.xinyue.icu/Article/details/gtzqktjoha.html

[T18] Swift：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtulvlynuz.html

"值: \(b)"
来源：http://dali.gotoacloud.top/Article/details/gtkjuybtxi.html

[T19] Swift：可选绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscwifqhq.html

if let n = opt { print(n) }
来源：http://dali.c1oappe.top/Article/details/gtctlnsrjc.html

[T20] Swift：数组操作
来源：http://dali.svipenyu.cn/Article/details/gtglljcsem.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.pycfn.com/Article/details/gttkfmjogk.html

[T21] Swift：遍历
来源：http://dali.yj20258.top/Article/details/gtthxrptpq.html

for x in a { print(x) }
来源：http://dali.tanke756.top/Article/details/gtjoseszwm.html

[T22] Swift：字典
来源：http://dali.gaohongyu789.top/Article/details/gtdyvjiimi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yuxming.cn/Article/details/gtbmwugtbe.html

[T23] Swift：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtijxuqosz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daxiang520.top/Article/details/gtafdiltzq.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gtoihdiarg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtjyrshllh.html

[T25] Swift：结构体
来源：http://dali.hnxiangtu.top/Article/details/gtmawbynpo.html

struct P { var x: Int }
来源：http://dali.tianlin.xyz/Article/details/gtnzlwtnhy.html

[T26] Swift：类与重写
来源：http://dali.ehwqpu.com/Article/details/gtukfekcts.html

class A: Base { override func f() {} }
来源：http://dali.fengsongda.top/Article/details/gtpggsqbch.html

[T27] Swift：错误处理
来源：http://dali.xuanzx.com/Article/details/gtoxsfnqyo.html

do { try f() } catch { print(error) }
来源：http://dali.gotoacloud.top/Article/details/gtqepwpclh.html

[T28] Swift：枚举
来源：http://dali.meibo888.top/Article/details/gtwteqkizf.html

enum Color { case red, green }
来源：http://dali.nanxuanxn.top/Article/details/gtmjkwvrlz.html

[T29] Swift：guard 提前返回
来源：http://dali.yuanzhike.top/Article/details/gtosshljhu.html

guard let x = opt else { return }
来源：http://dali.jyoumei.cn/Article/details/gtfzprxiag.html

[T30] Swift：协议
来源：http://dali.ybcxt.top/Article/details/gtiwpobuei.html

protocol Shape { func area() -> Double }
来源：http://dali.9152youxi.cn/Article/details/gtjzmsnyzu.html

[T31] Lua：Hello World
来源：http://dali.shuidangran.top/Article/details/gtxsaomake.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gtxigzeutf.html

[T32] Lua：局部变量
来源：http://dali.zhixingplan.top/Article/details/gtqutxpxgr.html

local a = 1
来源：http://dali.yuxming.cn/Article/details/gtapwiwcok.html

[T33] Lua：表（数组）
来源：http://dali.yanxiufei.cn/Article/details/gtsziqvxhe.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yuanzhike.top/Article/details/gtlefrpjrg.html

[T34] Lua：遍历表
来源：http://dali.hnqzz.top/Article/details/gtpgnkddot.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hongshengwenyu.top/Article/details/gtxekscmlg.html

[T35] Lua：字典表
来源：http://dali.chenlongwang.top/Article/details/gtdpytrqta.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guannengcc.top/Article/details/gtymfnfbrv.html

[T36] Lua：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvdvxrhx.html

function add(a, b) return a + b end
来源：http://dali.hfpthk.cn/Article/details/gtntpxxiue.html

[T37] Lua：字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gtecrknbor.html

"a" .. "b"
来源：http://dali.iojbl.cn/Article/details/gtmfxnvwrp.html

[T38] Lua：条件
来源：http://dali.ydzc1.top/Article/details/gthykihfjw.html

if x > 0 then print("正") end
来源：http://dali.jqgufenzy.top/Article/details/gthruhgsmw.html

[T39] Lua：模式匹配
来源：http://dali.tanke756.top/Article/details/gtjktzvkqx.html

string.find(s, "%d+")
来源：http://dali.shuidangran.top/Article/details/gtrqjyktuy.html

[T40] Lua：元表
来源：http://dali.hywenlv.cn/Article/details/gtenfnasov.html

setmetatable({}, { __index = base })
来源：http://dali.ehwqpu.com/Article/details/gtbumolwku.html

[T41] Perl：Hello World
来源：http://dali.bjfxy.top/Article/details/gtocxpbkwq.html

print "Hello\n";
来源：http://dali.gotoacloud.top/Article/details/gtgywnijjf.html

[T42] Perl：变量类型
来源：http://dali.redwolf501.top/Article/details/gtqropsgus.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sufxvd.cn/Article/details/gtlecrhoqz.html

[T43] Perl：字符串插值
来源：http://dali.havefunace.top/Article/details/gtdkbwgmju.html

"值: $a"
来源：http://dali.pengpengdd.cyou/Article/details/gtivbpjruk.html

[T44] Perl：条件
来源：http://dali.chenjidiqi.icu/Article/details/gtzszffnwd.html

if ($a > 0) { print "正"; }
来源：http://dali.yj20258.top/Article/details/gtzjaavrrh.html

[T45] Perl：数组遍历
来源：http://dali.nanxinkj.top/Article/details/gtccmufham.html

for my $x (@arr) { print $x; }
来源：http://dali.zhoulong.xyz/Article/details/gtllmkvrbi.html

[T46] Perl：哈希操作
来源：http://dali.quarkkingdee.top/Article/details/gtqjpzfkhu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aibaodan.cn/Article/details/gtbransahm.html

[T47] Perl：正则捕获
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjayrmoi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daria6918.cn/Article/details/gtdgbevskk.html

[T48] Perl：正则替换
来源：http://dali.jiagoushi.top/Article/details/gtulfkhorb.html

$s =~ s/old/new/g;
来源：http://dali.zhiwuduotai.top/Article/details/gtzmmrjfeu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gttcxpkhsg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtihzpmgzv.html

[T50] Perl：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnrjgpzc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigufen.top/Article/details/gtgfqrnaom.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gotoacloud.top/Article/details/gtommwntzl.html

[T51] Scala：Hello World
来源：http://dali.gzhubu.top/Article/details/gttbumagpb.html

println("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtgczohlft.html

[T52] Scala：变量
来源：http://dali.xinyue.icu/Article/details/gtuqmopomd.html

val a = 1;  var b = 2
来源：http://dali.ydzc1.top/Article/details/gtwfxtwlyj.html

[T53] Scala：字符串插值
来源：http://dali.cashguo.top/Article/details/gtzozzwdbh.html

s"值: $b"
来源：http://dali.yonumen.top/Article/details/gtldxdlrpb.html

[T54] Scala：集合映射
来源：http://dali.fengsongda.top/Article/details/gtchctzsnl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tanke756.top/Article/details/gtcegpfnhi.html

[T55] Scala：集合过滤
来源：http://dali.yangfankeji.com/Article/details/gtxypilfif.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhongyouzk.top/Article/details/gtjknqoopa.html

[T56] Scala：样例类
来源：http://dali.ehwqpu.com/Article/details/gtjmsdfyhs.html

case class User(name: String, age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthybbjjhj.html

[T57] Scala：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gtutrbkxlm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhongyouzk.top/Article/details/gtrggznjsc.html

[T58] Scala：函数定义
来源：http://dali.c1oappe.top/Article/details/gtopdfwgjc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.havefunace.top/Article/details/gtvuvtppyf.html

[T59] Scala：循环
来源：http://dali.ppjwa.cn/Article/details/gtmeayzsnl.html

for (i <- 1 to 10) println(i)
来源：http://dali.xinyue.icu/Article/details/gtnlsywlqp.html

[T60] Scala：折叠
来源：http://dali.nwbrower.top/Article/details/gtzzadreqo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tanke756.top/Article/details/gthtkhnlhl.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtsrtxtamu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.guowangkeji.top/Article/details/gtlbymzvga.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtbiwxnyim.html

[U01] Py：创建虚拟环境
来源：http://dali.ivvv.top/Article/details/gtqhbponyc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jqgfzy.top/Article/details/gtejffzbjn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbfptlqw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.redwolf501.top/Article/details/gtcvjsaoty.html

[U03] Py：加载 .env 配置
来源：http://dali.yvedp.cn/Article/details/gtxhitdzco.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj20258888.top/Article/details/gtcbwojfli.html

[U04] Py：变量调试打印
来源：http://dali.zhongyouzk.top/Article/details/gtokrjijpn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhixingplan.top/Article/details/gtzpqsaiuz.html

[U05] Py：列表去重且保序
来源：http://dali.bjfxy.top/Article/details/gtbhludbtm.html

list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gtgkxtrxvt.html

[U06] Py：合并两个字典
来源：http://dali.shuidangran.top/Article/details/gtvxyocdjv.html

{**a, **b}
来源：http://dali.iojbl.cn/Article/details/gtwlrllyai.html

[U07] Py：反转字典键值
来源：http://dali.cqqwz.cn/Article/details/gtjwatxxie.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbeeigesz.html

[U08] Py：展平二维列表
来源：http://dali.hywenlv.cn/Article/details/gtxjubctop.html

[y for x in nested for y in x]
来源：http://dali.guowangkeji.top/Article/details/gtygaepfbp.html

[U09] Py：字典取最大值的键
来源：http://dali.guannengcc.top/Article/details/gtavloanbq.html

max(d, key=d.get)
来源：http://dali.fengsongda.top/Article/details/gtdjudfnyw.html

[U10] Py：按值排序字典
来源：http://dali.yj20258888.top/Article/details/gtydqgtwci.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sxryk.cn/Article/details/gttipsxypg.html

[U11] Py：生成器表达式
来源：http://dali.andypj.xyz/Article/details/gtrtbztuan.html

(x * 2 for x in arr)
来源：http://dali.sysykeji.top/Article/details/gtvclbvlcu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xuetiantiany.cn/Article/details/gtylsnvnrf.html

Counter(arr).most_common(3)
来源：http://dali.birdmap.top/Article/details/gtpwcyzsub.html

[U13] Py：固定长度队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdjnnbxr.html

deque(maxlen=10)
来源：http://dali.aizwys.cn/Article/details/gtrojwwtbk.html

[U14] Py：分组收集到列表
来源：http://dali.yueranfly.top/Article/details/gtnfkjqtyc.html

defaultdict(list)
来源：http://dali.yonumen.top/Article/details/gtrsejxatb.html

[U15] Py：高精度计时
来源：http://dali.guannengcc.top/Article/details/gtntpuiust.html

t = time.perf_counter()
来源：http://dali.snrcjt.cn/Article/details/gtfzhjunic.html

[U16] Py：命令行参数解析
来源：http://dali.zycfv.cn/Article/details/gtivjjoqvz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.iojbl.cn/Article/details/gteotxvsmx.html

[U17] Py：初始化日志
来源：http://dali.316326.xyz/Article/details/gtsoygdnhj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.tianlin.xyz/Article/details/gtustslazr.html

[U18] Py：预编译正则
来源：http://dali.feifeiyinyue.top/Article/details/gthgpqwymy.html

pat = re.compile(r"\d+")
来源：http://dali.guowangkeji.top/Article/details/gtiryrxhmx.html

[U19] Py：正则替换带回调
来源：http://dali.yvedp.cn/Article/details/gtilxnkgaa.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.feifeiyinyue.top/Article/details/gtnvjgjbmx.html

[U20] Py：缓存函数结果
来源：http://dali.iojbl.cn/Article/details/gtbwbkjetp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.snrcjt.cn/Article/details/gtadohpjil.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenjidiqi.icu/Article/details/gtbdtqohft.html

@contextlib.contextmanager
来源：http://dali.0kj1m.cn/Article/details/gtidribckv.html

[U22] Py：矩阵转置
来源：http://dali.hywenlv.cn/Article/details/gtdcemwxsr.html

list(zip(*m))
来源：http://dali.zhoulong.xyz/Article/details/gtfovbjujw.html


<!-- 参考信息 -->