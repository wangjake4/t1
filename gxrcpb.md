代发 wailian999

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gthvjtxjmt.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtayvwuvnr.html

[S01] C：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtootogqgi.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gtlxanxdiq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ivvv.top/Article/details/gtaxgplrgs.html

[S02] C：变量与格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtqlgdheqc.html

int a = 10; printf("%d\n", a);
来源：http://dali.sysykeji.top/Article/details/gthsezkgix.html

[S03] C：读入整数
来源：http://dali.meibo888.top/Article/details/gtxjhnslsv.html

int x; scanf("%d", &x);
来源：http://dali.cashguo.top/Article/details/gtxzfgdyto.html

[S04] C：字符串复制
来源：http://dali.yongpay.top/Article/details/gtydjvnlhu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zdqjudy.top/Article/details/gtzguxahyd.html

[S05] C：字符串长度
来源：http://dali.tian-w.cn/Article/details/gtitrzerbg.html

strlen(s)
来源：http://dali.xylfe.cn/Article/details/gtgwcgencw.html

[S06] C：字符串比较
来源：http://dali.aibaodan.cn/Article/details/gtvepupgeu.html

strcmp(a, b) == 0
来源：http://dali.aizwys.cn/Article/details/gtpztjdwsz.html

[S07] C：数组遍历求和
来源：http://dali.chenlongwang.top/Article/details/gtssdrzqru.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zycfv.cn/Article/details/gtlbqcsaza.html

[S08] C：动态内存分配与释放
来源：http://dali.iojbl.cn/Article/details/gtuusxmdib.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hammf.cn/Article/details/gtxeoqmeyr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhiwuduotai.top/Article/details/gtzpwkofgg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aibaodan.cn/Article/details/gtfpkqirwk.html

[S10] C：指针与解引用
来源：http://dali.ydzc1.top/Article/details/gtnlrxnoey.html

int *p = &a;  *p = 5;
来源：http://dali.zycfv.cn/Article/details/gtyplcwril.html

[S11] C：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtgncsxmaf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenlongwang.top/Article/details/gtvtczskhw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjkwrvqfc.html

fclose(f);
来源：http://dali.316326.xyz/Article/details/gtjwwtgxyv.html

[S12] C：写文件
来源：http://dali.nanxuanxn.top/Article/details/gteaxrlthc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtzofkjfse.html

[S13] C：宏定义
来源：http://dali.ybcxt.top/Article/details/gtvnmmnrbs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jianghu66.top/Article/details/gtguwslqbp.html

[S14] C：枚举
来源：http://dali.zhixingplan.top/Article/details/gtgojmlvvl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gotoacloud.top/Article/details/gtrpfmhahi.html

[S15] C：类型转换
来源：http://dali.shzxlz.cn/Article/details/gtqgvvltep.html

(double) a / b
来源：http://dali.dashuyun.cn/Article/details/gtiuobbeko.html

[S16] C：位操作置位
来源：http://dali.zhongyouzk.top/Article/details/gtrrpcyqrt.html

x |= (1 << 3);
来源：http://dali.wangdashe.top/Article/details/gtnvimscvl.html

[S17] C：安全拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqiioiox.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ydzc1.top/Article/details/gteiyxkpdq.html

[S18] C：命令行参数
来源：http://dali.yuxming.cn/Article/details/gthqtzloyn.html

int main(int argc, char **argv)
来源：http://dali.cdnleiting.top/Article/details/gthdogjapp.html

[S19] C：快速排序
来源：http://dali.nwbrower.top/Article/details/gtnabhpxgl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtntiihjbg.html

[S20] C：二分查找
来源：http://dali.tian-w.cn/Article/details/gtwnlmmsrh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gtgarunuck.html

[S21] C：字符类别判断
来源：http://dali.feifeiyinyue.top/Article/details/gtgnlvnkaq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.snrcjt.cn/Article/details/gtlbuqbrar.html

[S22] C：字符串转数字
来源：http://dali.hfpthk.cn/Article/details/gtzswdnkut.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.mhx1999.top/Article/details/gtrblkdqfk.html

[S23] C：随机数
来源：http://dali.cucudq.cn/Article/details/gtyagithxq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fzhhl.top/Article/details/gtmpjnwhbv.html

[S24] C：获取本地时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmoqnere.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.vqdsnc.cn/Article/details/gtfikwquft.html

[S25] C：内存拷贝
来源：http://dali.hammf.cn/Article/details/gtiyhqjywz.html

memcpy(dst, src, n);
来源：http://dali.chenlongwang.top/Article/details/gtodjhmiew.html

[S26] C：内存清零
来源：http://dali.hywenlv.cn/Article/details/gtichzskhy.html

memset(a, 0, sizeof a);
来源：http://dali.0kj1m.cn/Article/details/gteynnpjxy.html

[S27] C：定义常量
来源：http://dali.hywenlv.cn/Article/details/gtoyppqrsh.html

const double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtttradzat.html

[S28] C：静态变量
来源：http://dali.gaohongyu789.top/Article/details/gtietwnpmd.html

static int counter = 0;
来源：http://dali.yj202588.top/Article/details/gtdssuydtk.html

[S29] C：变参函数
来源：http://dali.xuetiantiany.cn/Article/details/gtpszjdwwi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqidesxn.html

[S30] C：头文件保护
来源：http://dali.zhixingplan.top/Article/details/gtrtjnipfv.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gtsunlbrff.html

#define X_H
来源：http://dali.hnxiangtu.top/Article/details/gtgkajtxuw.html

#endif
来源：http://dali.yonumen.top/Article/details/gtszzrxdft.html

[S31] C++：Hello World
来源：http://dali.aizwys.cn/Article/details/gtaxpspsze.html

#include <iostream>
来源：http://dali.hywenlv.cn/Article/details/gtwvshknhh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yvedp.cn/Article/details/gthjprbukq.html

[S32] C++：字符串
来源：http://dali.yonumen.top/Article/details/gthtngcgcq.html

std::string s = "hi";  s += "!";
来源：http://dali.wangshuangyany.cn/Article/details/gtxotxmpbc.html

[S33] C++：vector 增删
来源：http://dali.shuidangran.top/Article/details/gtiiztsoll.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.redwolf501.top/Article/details/gtkuekfvrf.html

[S34] C++：遍历 vector
来源：http://dali.jqgfzy.top/Article/details/gtcilniopk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.9152youxi.cn/Article/details/gtoycnmyfn.html

[S35] C++：map
来源：http://dali.hongshengwenyu.top/Article/details/gtzhoevwvl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtgqdcowgf.html

[S36] C++：unordered_map
来源：http://dali.gzhubu.top/Article/details/gtvsajoeqa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gtjeqnlihf.html

[S37] C++：set
来源：http://dali.redwolf501.top/Article/details/gtrxovwxcq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gtrtcpbfok.html

[S38] C++：排序
来源：http://dali.yuxming.cn/Article/details/gthfjzkfzo.html

std::sort(v.begin(), v.end());
来源：http://dali.daria6918.cn/Article/details/gtywxqsvuf.html

[S39] C++：自定义比较器排序
来源：http://dali.wangdashe.top/Article/details/gtivfifcjp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yangfankeji.com/Article/details/gtwrjamorj.html

[S40] C++：查找元素
来源：http://dali.shuidangran.top/Article/details/gtfawzatgn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gaohongyu789.top/Article/details/gtlvoosiad.html

[S41] C++：类与构造函数
来源：http://dali.wangdashe.top/Article/details/gtnubdwdzz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zycfv.cn/Article/details/gtimovmexz.html

[S42] C++：继承与虚函数
来源：http://dali.iojbl.cn/Article/details/gtrtawjagr.html

class B : public Base { public: void f() override {} };
来源：http://dali.yuanzhike.top/Article/details/gtkringfcz.html

[S43] C++：智能指针
来源：http://dali.vqdsnc.cn/Article/details/gtzzbefwhz.html

auto p = std::make_unique<int>(5);
来源：http://dali.ivvv.top/Article/details/gtzcfkeyql.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gtqjyzpsga.html

void inc(int &x) { ++x; }
来源：http://dali.guowangkeji.top/Article/details/gtzyczcnvu.html

[S45] C++：lambda
来源：http://dali.cucudq.cn/Article/details/gtmflmtmxi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dashuyun.cn/Article/details/gtzoixzxyg.html

[S46] C++：函数模板
来源：http://dali.mhx1999.top/Article/details/gttobzadiu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.bjfxy.top/Article/details/gtcsepjbeh.html

[S47] C++：结构化绑定遍历
来源：http://dali.ydzc1.top/Article/details/gtdgvdkexk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sweek.top/Article/details/gtdxdxeiit.html

[S48] C++：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtqznagahc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yonumen.top/Article/details/gtlzxnckar.html

while (std::getline(in, line)) { }
来源：http://dali.jianghu66.top/Article/details/gtvuvltswr.html

[S49] C++：写文件
来源：http://dali.gotoacloud.top/Article/details/gtqrugxayd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jlsjyb.cn/Article/details/gtpduhxosk.html

[S50] C++：格式化数字
来源：http://dali.tianlin.xyz/Article/details/gtrekcybfa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtnsktvzii.html

[S51] C++：显式类型转换
来源：http://dali.9152youxi.cn/Article/details/gtfmdwizfg.html

static_cast<double>(a) / b
来源：http://dali.chenzaomai.com/Article/details/gtmcdlqzlm.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavhhiade.html

int size() const noexcept { return n_; }
来源：http://dali.xziqi.cn/Article/details/gtddmfwjpl.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gtbztespeb.html

std::vector<int> w = std::move(v);
来源：http://dali.kuanghao11.cn/Article/details/gtdhzuimpy.html

[S54] C++：异常处理
来源：http://dali.havefunace.top/Article/details/gtxmvyqcsc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.smart0.xyz/Article/details/gtneezafcj.html

[S55] C++：结构化绑定
来源：http://dali.chenjidiqi.icu/Article/details/gtwyauzyhq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.kuanghao11.cn/Article/details/gtzxqudzay.html

[S56] C++：optional
来源：http://dali.xinyue.icu/Article/details/gtmpkavxeq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenlongwang.top/Article/details/gtxayluyzn.html

[S57] C++：编译期常量
来源：http://dali.wangdashe.top/Article/details/gtxzhxalbn.html

constexpr int N = 10;
来源：http://dali.zycfv.cn/Article/details/gtafklfyrf.html

[S58] C++：命名空间
来源：http://dali.yueranfly.top/Article/details/gtlanqpcnd.html

namespace ns { int f() { return 1; } }
来源：http://dali.yangfankeji.com/Article/details/gtlsbompvj.html

[S59] C++：静态断言
来源：http://dali.cucudq.cn/Article/details/gtcnjzdjjb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sweek.top/Article/details/gtercixmtg.html

[S60] C++：遍历并删除元素
来源：http://dali.xuanzx.com/Article/details/gtwvbdwlxh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuxming.cn/Article/details/gtbvfrexrp.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtaqklntug.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xinyue.icu/Article/details/gtxvmfkbri.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gthtlghvgr.html

[T01] Kotlin：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwdypqne.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gtoqeatlci.html

[T02] Kotlin：变量
来源：http://dali.chenlongwang.top/Article/details/gttdkztosx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shzxlz.cn/Article/details/gtjlmsadoj.html

[T03] Kotlin：字符串模板
来源：http://dali.birdmap.top/Article/details/gterxbuyui.html

"值: $b"
来源：http://dali.meibo888.top/Article/details/gtawlbzeuv.html

[T04] Kotlin：空安全
来源：http://dali.zhengqikj.top/Article/details/gtcvsinqwd.html

val n: String? = null;  n?.length
来源：http://dali.ydzc1.top/Article/details/gtjdtiayey.html

[T05] Kotlin：when 表达式
来源：http://dali.shuidangran.top/Article/details/gtiyxjtawj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxuanxn.top/Article/details/gtijlcjmlm.html

[T06] Kotlin：集合映射
来源：http://dali.yvedp.cn/Article/details/gtzhymdujr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj20258888.top/Article/details/gtofxljinb.html

[T07] Kotlin：集合过滤
来源：http://dali.cheryme.top/Article/details/gtfamawgkm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxinkj.top/Article/details/gtumsfxijz.html

[T08] Kotlin：数据类
来源：http://dali.316326.xyz/Article/details/gtxmprcmwk.html

data class User(val name: String, val age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gtoqtwccyl.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258888.top/Article/details/gtzxyuljkt.html

fun String.exclaim() = this + "!"
来源：http://dali.ydzc1.top/Article/details/gtyojdqhoj.html

[T10] Kotlin：默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfepqyjn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.havefunace.top/Article/details/gtfwgogvkg.html

[T11] Kotlin：协程
来源：http://dali.havefunace.top/Article/details/gtrzacjmyt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gtywtyyfio.html

[T12] Kotlin：解构声明
来源：http://dali.guowangkeji.top/Article/details/gtizhdztpw.html

val (a, b) = Pair(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtvrxnwwen.html

[T13] Kotlin：只读 Map
来源：http://dali.yueranfly.top/Article/details/gtcadygbvl.html

val m = mapOf("a" to 1)
来源：http://dali.yanxiufei.cn/Article/details/gtpxcgdbdh.html

[T14] Kotlin：循环
来源：http://dali.mhx1999.top/Article/details/gtcctjfvhp.html

for (i in 1..10) println(i)
来源：http://dali.dianchejie.cn/Article/details/gtjbzhqrej.html

[T15] Kotlin：接口
来源：http://dali.fengsongda.top/Article/details/gtcvcqqlle.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigfzy.top/Article/details/gtpgdfssev.html

[T16] Swift：Hello World
来源：http://dali.tanke756.top/Article/details/gttsniwjrx.html

print("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtgxepjpuv.html

[T17] Swift：变量与常量
来源：http://dali.ybcxt.top/Article/details/gtwkurnazm.html

var a = 1;  let b = 2
来源：http://dali.hnxiangtu.top/Article/details/gtkqnktsdl.html

[T18] Swift：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gthveagenm.html

"值: \(b)"
来源：http://dali.hysaishi.cn/Article/details/gtsmvfjpsb.html

[T19] Swift：可选绑定
来源：http://dali.cdnleiting.top/Article/details/gthpjmzegf.html

if let n = opt { print(n) }
来源：http://dali.pycfn.com/Article/details/gteeoowuxw.html

[T20] Swift：数组操作
来源：http://dali.shzxlz.cn/Article/details/gtkqrdedug.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhongyouzk.top/Article/details/gtqmdrjawp.html

[T21] Swift：遍历
来源：http://dali.yongpay.top/Article/details/gtgmjsjiya.html

for x in a { print(x) }
来源：http://dali.zhiwuduotai.top/Article/details/gtzumjpvqs.html

[T22] Swift：字典
来源：http://dali.sxryk.cn/Article/details/gtlnfkcmes.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yonumen.top/Article/details/gtexberpxx.html

[T23] Swift：函数
来源：http://dali.nanxuanxn.top/Article/details/gttetypqps.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxogpwdoy.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gtmhvsnoqf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ivvv.top/Article/details/gtcqkvinkp.html

[T25] Swift：结构体
来源：http://dali.zdqjudy.top/Article/details/gtrmbkztci.html

struct P { var x: Int }
来源：http://dali.andypj.xyz/Article/details/gtwshauddh.html

[T26] Swift：类与重写
来源：http://dali.ydzc1.top/Article/details/gthokoxvwy.html

class A: Base { override func f() {} }
来源：http://dali.ehwqpu.com/Article/details/gtlsrcgeal.html

[T27] Swift：错误处理
来源：http://dali.cheryme.top/Article/details/gtldhnihcn.html

do { try f() } catch { print(error) }
来源：http://dali.sxryk.cn/Article/details/gtpenewfnj.html

[T28] Swift：枚举
来源：http://dali.xziqi.cn/Article/details/gtqeetzuet.html

enum Color { case red, green }
来源：http://dali.havefunace.top/Article/details/gtlhyrhmjm.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigfzy.top/Article/details/gtjsgrszrq.html

guard let x = opt else { return }
来源：http://dali.9152youxi.cn/Article/details/gtnsarzfoj.html

[T30] Swift：协议
来源：http://dali.cheryme.top/Article/details/gtudeipngm.html

protocol Shape { func area() -> Double }
来源：http://dali.shuidangran.top/Article/details/gtanmepmeg.html

[T31] Lua：Hello World
来源：http://dali.cashguo.top/Article/details/gtvrmwtyby.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznjrtfdc.html

[T32] Lua：局部变量
来源：http://dali.jqgufenzy.top/Article/details/gtszzcwwiu.html

local a = 1
来源：http://dali.jinqigufen.top/Article/details/gthvqnrasj.html

[T33] Lua：表（数组）
来源：http://dali.svipenyu.cn/Article/details/gtrulhnwuh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tanke756.top/Article/details/gtdqtordxn.html

[T34] Lua：遍历表
来源：http://dali.redwolf501.top/Article/details/gtzmcdeiqw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jyoumei.cn/Article/details/gtjcdyeftg.html

[T35] Lua：字典表
来源：http://dali.cashguo.top/Article/details/gtxpwgvxgo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cashguo.top/Article/details/gtrsoxxaum.html

[T36] Lua：函数
来源：http://dali.xylfe.cn/Article/details/gtvqstemoa.html

function add(a, b) return a + b end
来源：http://dali.feifeiyinyue.top/Article/details/gtusmjilav.html

[T37] Lua：字符串拼接
来源：http://dali.yuxming.cn/Article/details/gttxwvtqgq.html

"a" .. "b"
来源：http://dali.pengpengdd.cyou/Article/details/gtsirmbxef.html

[T38] Lua：条件
来源：http://dali.chenjidiqi.icu/Article/details/gthapodyyf.html

if x > 0 then print("正") end
来源：http://dali.c1oappe.top/Article/details/gtdszlbzlb.html

[T39] Lua：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtjtokgnse.html

string.find(s, "%d+")
来源：http://dali.guowangkeji.top/Article/details/gtydollbvk.html

[T40] Lua：元表
来源：http://dali.redwolf501.top/Article/details/gtzxfpgluj.html

setmetatable({}, { __index = base })
来源：http://dali.jlsjyb.cn/Article/details/gtqrjfbvmu.html

[T41] Perl：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtdvussprf.html

print "Hello\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvhvqppp.html

[T42] Perl：变量类型
来源：http://dali.shzxlz.cn/Article/details/gtwcercoap.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxinkj.top/Article/details/gtmgdkykkj.html

[T43] Perl：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtetxgcmkn.html

"值: $a"
来源：http://dali.ehwqpu.com/Article/details/gtffwckknn.html

[T44] Perl：条件
来源：http://dali.jiagoushi.top/Article/details/gtfocpuooh.html

if ($a > 0) { print "正"; }
来源：http://dali.cucudq.cn/Article/details/gtloktsqcj.html

[T45] Perl：数组遍历
来源：http://dali.gogol.net.cn/Article/details/gtppgokncg.html

for my $x (@arr) { print $x; }
来源：http://dali.shzxlz.cn/Article/details/gtyrvfpyvz.html

[T46] Perl：哈希操作
来源：http://dali.wangdashe.top/Article/details/gtibcymrcl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tanke756.top/Article/details/gtzxsmjmfz.html

[T47] Perl：正则捕获
来源：http://dali.gaohongyu789.top/Article/details/gtuixaxpbl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.redwolf501.top/Article/details/gtjpfsqbla.html

[T48] Perl：正则替换
来源：http://dali.ybcxt.top/Article/details/gtktgjpmcb.html

$s =~ s/old/new/g;
来源：http://dali.meibo888.top/Article/details/gtcjfizfyv.html

[T49] Perl：函数
来源：http://dali.nanxinkj.top/Article/details/gtdctbkrto.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtnhkcfbun.html

[T50] Perl：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gthpgqcgms.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenzaomai.com/Article/details/gtktoshsuq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigufen.top/Article/details/gtbjypplif.html

[T51] Scala：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtqxntzbox.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gtxomjmtbx.html

[T52] Scala：变量
来源：http://dali.aibaodan.cn/Article/details/gtqmlbirws.html

val a = 1;  var b = 2
来源：http://dali.wangdashe.top/Article/details/gtpxnqlgjh.html

[T53] Scala：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtmfesrwrw.html

s"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gtoijynnji.html

[T54] Scala：集合映射
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqvndezl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hfpthk.cn/Article/details/gtclcfngcq.html

[T55] Scala：集合过滤
来源：http://dali.sweek.top/Article/details/gtthmmflzy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aibaodan.cn/Article/details/gtvstfirdf.html

[T56] Scala：样例类
来源：http://dali.ppjwa.cn/Article/details/gtmoizuwui.html

case class User(name: String, age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gthpdeamfl.html

[T57] Scala：模式匹配
来源：http://dali.sxryk.cn/Article/details/gtwcwwcspb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xinyue.icu/Article/details/gtrxwsmqlh.html

[T58] Scala：函数定义
来源：http://dali.wangshuangyany.cn/Article/details/gtmuhfutvh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hnqzz.top/Article/details/gtspnkwbra.html

[T59] Scala：循环
来源：http://dali.feifeiyinyue.top/Article/details/gtlpfslhth.html

for (i <- 1 to 10) println(i)
来源：http://dali.yvedp.cn/Article/details/gtdqghihjn.html

[T60] Scala：折叠
来源：http://dali.ivvv.top/Article/details/gtwwsuttsu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.daria6918.cn/Article/details/gtozvjeniw.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtchlbautk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gzhubu.top/Article/details/gtktbpzvkq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtctvajczb.html

[U01] Py：创建虚拟环境
来源：http://dali.smart0.xyz/Article/details/gtfovtouis.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.vqdsnc.cn/Article/details/gttpyozitw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.wangshuangyany.cn/Article/details/gtphtlnovd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.wangdashe.top/Article/details/gtlxcegyzq.html

[U03] Py：加载 .env 配置
来源：http://dali.yanxiufei.cn/Article/details/gtovskflbx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sysykeji.top/Article/details/gtdtvqeqwq.html

[U04] Py：变量调试打印
来源：http://dali.shzxlz.cn/Article/details/gtvwkgzgtr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.fengsongda.top/Article/details/gtvrjwrggb.html

[U05] Py：列表去重且保序
来源：http://dali.jlsjyb.cn/Article/details/gtmifuqsno.html

list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gtuzmxnvmq.html

[U06] Py：合并两个字典
来源：http://dali.316326.xyz/Article/details/gtqlqityyx.html

{**a, **b}
来源：http://dali.yangfankeji.com/Article/details/gtcdrcznjj.html

[U07] Py：反转字典键值
来源：http://dali.nwbrower.top/Article/details/gtrkdgcujp.html

{v: k for k, v in d.items()}
来源：http://dali.yuxming.cn/Article/details/gtnynkhsvw.html

[U08] Py：展平二维列表
来源：http://dali.wangdashe.top/Article/details/gtgvicmlng.html

[y for x in nested for y in x]
来源：http://dali.tian-w.cn/Article/details/gtffvvomkk.html

[U09] Py：字典取最大值的键
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxglpfduw.html

max(d, key=d.get)
来源：http://dali.yuanzhike.top/Article/details/gtnoqxjnvs.html

[U10] Py：按值排序字典
来源：http://dali.nanxuanxn.top/Article/details/gtkjjafwrn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhongyouzk.top/Article/details/gtglvdvsae.html

[U11] Py：生成器表达式
来源：http://dali.nanxinkj.top/Article/details/gtzltzmwty.html

(x * 2 for x in arr)
来源：http://dali.smart0.xyz/Article/details/gttdffwuqv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jlsjyb.cn/Article/details/gtrzqvpmnp.html

Counter(arr).most_common(3)
来源：http://dali.dianchejie.cn/Article/details/gtjjsaawlq.html

[U13] Py：固定长度队列
来源：http://dali.yuxming.cn/Article/details/gtvwbefwpn.html

deque(maxlen=10)
来源：http://dali.yueranfly.top/Article/details/gtyiecbfkp.html

[U14] Py：分组收集到列表
来源：http://dali.sxryk.cn/Article/details/gtjsddxvpi.html

defaultdict(list)
来源：http://dali.xuetiantiany.cn/Article/details/gtvyruibbx.html

[U15] Py：高精度计时
来源：http://dali.nanxinkj.top/Article/details/gtcndnzbes.html

t = time.perf_counter()
来源：http://dali.svipenyu.cn/Article/details/gtzlgwunfo.html

[U16] Py：命令行参数解析
来源：http://dali.316326.xyz/Article/details/gtjqyupdvc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.tianlin.xyz/Article/details/gtrvtsgloi.html

[U17] Py：初始化日志
来源：http://dali.jinqigufen.top/Article/details/gtcaxdqmlh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yuanzhike.top/Article/details/gtwmhscoht.html

[U18] Py：预编译正则
来源：http://dali.yj20258.top/Article/details/gtleqthpho.html

pat = re.compile(r"\d+")
来源：http://dali.cheryme.top/Article/details/gtcjuerxza.html

[U19] Py：正则替换带回调
来源：http://dali.hammf.cn/Article/details/gtljmzerwn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zycfv.cn/Article/details/gtjqmenufv.html

[U20] Py：缓存函数结果
来源：http://dali.hnxiangtu.top/Article/details/gtlroxcpyt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ydzc1.top/Article/details/gtjrhbzdrv.html

[U21] Py：自定义上下文管理器
来源：http://dali.redwolf501.top/Article/details/gtttxsayrr.html

@contextlib.contextmanager
来源：http://dali.vqdsnc.cn/Article/details/gtjpkrhmqt.html

[U22] Py：矩阵转置
来源：http://dali.jlsjyb.cn/Article/details/gtzleluwgj.html

list(zip(*m))
来源：http://dali.hnxiangtu.top/Article/details/gtcglrrlko.html


<!-- 参考信息 -->