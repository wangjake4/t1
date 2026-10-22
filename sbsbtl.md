代发 wailian999

S. C / C++ 专题
来源：http://dali.yuxming.cn/Article/details/gtapyajwtw.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtisaervoz.html

[S01] C：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtwkddfebi.html

#include <stdio.h>
来源：http://dali.sysykeji.top/Article/details/gtjowgnixr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhongyouzk.top/Article/details/gtlfsvjtbv.html

[S02] C：变量与格式化输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfborkmig.html

int a = 10; printf("%d\n", a);
来源：http://dali.yangfankeji.com/Article/details/gtkkgxqbyq.html

[S03] C：读入整数
来源：http://dali.tian-w.cn/Article/details/gtojvcgwkp.html

int x; scanf("%d", &x);
来源：http://dali.haohaochexian.top/Article/details/gtudzvuytp.html

[S04] C：字符串复制
来源：http://dali.xylfe.cn/Article/details/gtndejwldb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cdnleiting.top/Article/details/gtxlbfaidh.html

[S05] C：字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gtfjtudnnx.html

strlen(s)
来源：http://dali.cashguo.top/Article/details/gtifkyxryd.html

[S06] C：字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gtfwgfhpfj.html

strcmp(a, b) == 0
来源：http://dali.daxiang520.top/Article/details/gtwnifrpgi.html

[S07] C：数组遍历求和
来源：http://dali.yvedp.cn/Article/details/gthqncixgi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yvedp.cn/Article/details/gtgvsxrybb.html

[S08] C：动态内存分配与释放
来源：http://dali.guannengcc.top/Article/details/gtzqjxqpnp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aizwys.cn/Article/details/gteptqnkyf.html

[S09] C：结构体定义与初始化
来源：http://dali.0kj1m.cn/Article/details/gtxwpfaifp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.meibo888.top/Article/details/gtmfnovqjw.html

[S10] C：指针与解引用
来源：http://dali.iojbl.cn/Article/details/gteirllffp.html

int *p = &a;  *p = 5;
来源：http://dali.zhongyouzk.top/Article/details/gtkclcrnac.html

[S11] C：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtujglenjx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenjidiqi.icu/Article/details/gtkeetgong.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gotoacloud.top/Article/details/gtcgfhwuyd.html

fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gtlzoinnvn.html

[S12] C：写文件
来源：http://dali.jyoumei.cn/Article/details/gtlluryxks.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gtrrmkcdlw.html

[S13] C：宏定义
来源：http://dali.jqgufenzy.top/Article/details/gtvpnmhsls.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aizwys.cn/Article/details/gtucguihkh.html

[S14] C：枚举
来源：http://dali.daxiang520.top/Article/details/gtvewmoltw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pycfn.com/Article/details/gtssoumtat.html

[S15] C：类型转换
来源：http://dali.fzhhl.top/Article/details/gtduacmasm.html

(double) a / b
来源：http://dali.jqgufenzy.top/Article/details/gtgwrzrdzn.html

[S16] C：位操作置位
来源：http://dali.sysykeji.top/Article/details/gtqspignkt.html

x |= (1 << 3);
来源：http://dali.xylfe.cn/Article/details/gtvnqpeqti.html

[S17] C：安全拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtavnhbzqh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sysykeji.top/Article/details/gtaclkbcup.html

[S18] C：命令行参数
来源：http://dali.ivvv.top/Article/details/gtylngpqhl.html

int main(int argc, char **argv)
来源：http://dali.chenlongwang.top/Article/details/gtzkczyvnh.html

[S19] C：快速排序
来源：http://dali.hnxiangtu.top/Article/details/gtuqjqvphd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtwjptkxen.html

[S20] C：二分查找
来源：http://dali.zhoulong.xyz/Article/details/gthljqgifz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtebpdtcfx.html

[S21] C：字符类别判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiioqkgns.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daxiang520.top/Article/details/gtgilfjwgf.html

[S22] C：字符串转数字
来源：http://dali.wangdashe.top/Article/details/gtmqzsftad.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dashuyun.cn/Article/details/gtqnzuqaux.html

[S23] C：随机数
来源：http://dali.yj20258888.top/Article/details/gtllrfuzol.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.smart0.xyz/Article/details/gtkufxcclv.html

[S24] C：获取本地时间
来源：http://dali.0kj1m.cn/Article/details/gtbrcbtzgf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aibaodan.cn/Article/details/gtnhzjfihy.html

[S25] C：内存拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtdhgqpbhw.html

memcpy(dst, src, n);
来源：http://dali.xylfe.cn/Article/details/gtlouyjfqk.html

[S26] C：内存清零
来源：http://dali.svipenyu.cn/Article/details/gtnxclldhn.html

memset(a, 0, sizeof a);
来源：http://dali.aibaodan.cn/Article/details/gtoiufaeqj.html

[S27] C：定义常量
来源：http://dali.daria6918.cn/Article/details/gtqbhguajz.html

const double PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtmxtuazkn.html

[S28] C：静态变量
来源：http://dali.cashguo.top/Article/details/gtxwqdlxpz.html

static int counter = 0;
来源：http://dali.zycfv.cn/Article/details/gtxauxqshi.html

[S29] C：变参函数
来源：http://dali.jqgfzy.top/Article/details/gtgoyzgqsu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ybcxt.top/Article/details/gtuepdwfkt.html

[S30] C：头文件保护
来源：http://dali.yonumen.top/Article/details/gtvzgjedie.html

#ifndef X_H
来源：http://dali.jinqigufen.top/Article/details/gtlystootp.html

#define X_H
来源：http://dali.hysaishi.cn/Article/details/gtifuacjox.html

#endif
来源：http://dali.jiagoushi.top/Article/details/gtafhvhtsy.html

[S31] C++：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtltcrvurg.html

#include <iostream>
来源：http://dali.gotoacloud.top/Article/details/gtdxerbzgu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumnojuph.html

[S32] C++：字符串
来源：http://dali.wangdashe.top/Article/details/gtcrgkvibh.html

std::string s = "hi";  s += "!";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwdrkiqq.html

[S33] C++：vector 增删
来源：http://dali.gotoacloud.top/Article/details/gtbszaoxlv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhiwuduotai.top/Article/details/gttsjvrhft.html

[S34] C++：遍历 vector
来源：http://dali.guowangkeji.top/Article/details/gtqpiluwpo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigufen.top/Article/details/gtbhbcaxgp.html

[S35] C++：map
来源：http://dali.haohaochexian.top/Article/details/gturwkoxpu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyefgakqb.html

[S36] C++：unordered_map
来源：http://dali.zhiwuduotai.top/Article/details/gtiowgcirh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtnueukqhc.html

[S37] C++：set
来源：http://dali.bjfxy.top/Article/details/gtvogcgham.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.0kj1m.cn/Article/details/gtdtczvxvd.html

[S38] C++：排序
来源：http://dali.zhoulong.xyz/Article/details/gthltxljwh.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258888.top/Article/details/gtvfkhdjxd.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigfzy.top/Article/details/gtubebpkau.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.haohaochexian.top/Article/details/gtdzwpusrt.html

[S40] C++：查找元素
来源：http://dali.hysaishi.cn/Article/details/gtrxcagbbq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aizwys.cn/Article/details/gtiyfnjugt.html

[S41] C++：类与构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcpxrimc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sufxvd.cn/Article/details/gtogvqrtkh.html

[S42] C++：继承与虚函数
来源：http://dali.yonumen.top/Article/details/gtrdxelopj.html

class B : public Base { public: void f() override {} };
来源：http://dali.xinyue.icu/Article/details/gtlpoisudt.html

[S43] C++：智能指针
来源：http://dali.shuidangran.top/Article/details/gtcclkojty.html

auto p = std::make_unique<int>(5);
来源：http://dali.xylfe.cn/Article/details/gtfrmjtrgw.html

[S44] C++：引用传参
来源：http://dali.cashguo.top/Article/details/gtrwygifwm.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258.top/Article/details/gtrgbzbhje.html

[S45] C++：lambda
来源：http://dali.yuanzhike.top/Article/details/gttejgckip.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.redwolf501.top/Article/details/gtbiodwnrg.html

[S46] C++：函数模板
来源：http://dali.nanxinkj.top/Article/details/gtxggonlpa.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtidexazpo.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpchiqwsw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj202588.top/Article/details/gtmbcwvscg.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkmsskcp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guowangkeji.top/Article/details/gtozsjbpuk.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigfzy.top/Article/details/gtmhoagljj.html

[S49] C++：写文件
来源：http://dali.meibo888.top/Article/details/gtarjiohkb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guannengcc.top/Article/details/gtpbqprkre.html

[S50] C++：格式化数字
来源：http://dali.zhiwuduotai.top/Article/details/gttbwmjlot.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtrnhhzysp.html

[S51] C++：显式类型转换
来源：http://dali.ehwqpu.com/Article/details/gtdfhrfsnd.html

static_cast<double>(a) / b
来源：http://dali.ehwqpu.com/Article/details/gtrdxzzomq.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gttkvboydz.html

int size() const noexcept { return n_; }
来源：http://dali.fengsongda.top/Article/details/gtkusqjvol.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gtyvlyqsdi.html

std::vector<int> w = std::move(v);
来源：http://dali.xinyue.icu/Article/details/gtvcclyqkk.html

[S54] C++：异常处理
来源：http://dali.fzhhl.top/Article/details/gtvevmexnt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gzhubu.top/Article/details/gtgcwimqid.html

[S55] C++：结构化绑定
来源：http://dali.svipenyu.cn/Article/details/gtjcfsajji.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenzaomai.com/Article/details/gtqwycirtc.html

[S56] C++：optional
来源：http://dali.tanke756.top/Article/details/gtpqudhouv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258888.top/Article/details/gtmpwmaquc.html

[S57] C++：编译期常量
来源：http://dali.xinyue.icu/Article/details/gtuokqyecn.html

constexpr int N = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtqxfdxifa.html

[S58] C++：命名空间
来源：http://dali.wangshuangyany.cn/Article/details/gttmpgnfzk.html

namespace ns { int f() { return 1; } }
来源：http://dali.fzhhl.top/Article/details/gtakjebary.html

[S59] C++：静态断言
来源：http://dali.zhixingplan.top/Article/details/gtbunifqmk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zycfv.cn/Article/details/gtmchyzyod.html

[S60] C++：遍历并删除元素
来源：http://dali.0kj1m.cn/Article/details/gtbvwyngld.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gtqzfagcqp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtskqeegcv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgfzy.top/Article/details/gtpmnemhmz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtqkjozwix.html

[T01] Kotlin：Hello World
来源：http://dali.aizwys.cn/Article/details/gtjbfdtomo.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtoydbaoql.html

[T02] Kotlin：变量
来源：http://dali.aizwys.cn/Article/details/gturxcjlns.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guannengcc.top/Article/details/gtgfadotbm.html

[T03] Kotlin：字符串模板
来源：http://dali.ehwqpu.com/Article/details/gtgptdamvs.html

"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gtopliqpgo.html

[T04] Kotlin：空安全
来源：http://dali.jlsjyb.cn/Article/details/gtdaawvhqr.html

val n: String? = null;  n?.length
来源：http://dali.0kj1m.cn/Article/details/gteijvhvhs.html

[T05] Kotlin：when 表达式
来源：http://dali.cheryme.top/Article/details/gtqvzroszw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gtuqbmtvwf.html

[T06] Kotlin：集合映射
来源：http://dali.sysykeji.top/Article/details/gtxrnppbmu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gotoacloud.top/Article/details/gttrltwxde.html

[T07] Kotlin：集合过滤
来源：http://dali.jiagoushi.top/Article/details/gtshpxqnnm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shzxlz.cn/Article/details/gtmwhhedtq.html

[T08] Kotlin：数据类
来源：http://dali.dashuyun.cn/Article/details/gtjlwvkxct.html

data class User(val name: String, val age: Int)
来源：http://dali.jiagoushi.top/Article/details/gtkszosrhz.html

[T09] Kotlin：扩展函数
来源：http://dali.iojbl.cn/Article/details/gtbfznievr.html

fun String.exclaim() = this + "!"
来源：http://dali.yj20258.top/Article/details/gtvebbbicv.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtnzgjtiza.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtnuxjij.html

[T11] Kotlin：协程
来源：http://dali.shzxlz.cn/Article/details/gthoqucjrq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hfpthk.cn/Article/details/gtxujeuwgd.html

[T12] Kotlin：解构声明
来源：http://dali.sufxvd.cn/Article/details/gtxmfwpyhp.html

val (a, b) = Pair(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtbctnjvwd.html

[T13] Kotlin：只读 Map
来源：http://dali.xuetiantiany.cn/Article/details/gtcycctcpu.html

val m = mapOf("a" to 1)
来源：http://dali.yj202588.top/Article/details/gtbqxmgtbk.html

[T14] Kotlin：循环
来源：http://dali.fengsongda.top/Article/details/gtbcswdbmp.html

for (i in 1..10) println(i)
来源：http://dali.wangdashe.top/Article/details/gtkqjmapuj.html

[T15] Kotlin：接口
来源：http://dali.nanxuanxn.top/Article/details/gtjxzozgct.html

interface Shape { fun area(): Double }
来源：http://dali.zhengqikj.top/Article/details/gtayfrggzr.html

[T16] Swift：Hello World
来源：http://dali.meibo888.top/Article/details/gtwbbfuwqx.html

print("Hello")
来源：http://dali.yonumen.top/Article/details/gtrebgyjtk.html

[T17] Swift：变量与常量
来源：http://dali.nwbrower.top/Article/details/gtxxlhugpw.html

var a = 1;  let b = 2
来源：http://dali.ybcxt.top/Article/details/gtwqulirei.html

[T18] Swift：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtdmepcutg.html

"值: \(b)"
来源：http://dali.hammf.cn/Article/details/gtkpnkyuvc.html

[T19] Swift：可选绑定
来源：http://dali.hammf.cn/Article/details/gtmgqdosjv.html

if let n = opt { print(n) }
来源：http://dali.jiagoushi.top/Article/details/gteudkqkcv.html

[T20] Swift：数组操作
来源：http://dali.yangfankeji.com/Article/details/gtxhcpomly.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sweek.top/Article/details/gtnuprpiak.html

[T21] Swift：遍历
来源：http://dali.guowangkeji.top/Article/details/gtvvzxknhv.html

for x in a { print(x) }
来源：http://dali.shangyingyoupin.top/Article/details/gtyfjbxaaf.html

[T22] Swift：字典
来源：http://dali.dashuyun.cn/Article/details/gtzlghdxpb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yueranfly.top/Article/details/gtuhtcgief.html

[T23] Swift：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjnzytfg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjykhvit.html

[T24] Swift：闭包
来源：http://dali.jqgufenzy.top/Article/details/gtvieiiqgz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtrzxjhmym.html

[T25] Swift：结构体
来源：http://dali.feifeiyinyue.top/Article/details/gttjvyzjoa.html

struct P { var x: Int }
来源：http://dali.jinqigfzy.top/Article/details/gtppjlfibb.html

[T26] Swift：类与重写
来源：http://dali.yongpay.top/Article/details/gtmjqxakxd.html

class A: Base { override func f() {} }
来源：http://dali.zhongyouzk.top/Article/details/gtqokhqhop.html

[T27] Swift：错误处理
来源：http://dali.cashguo.top/Article/details/gtkfrubuqm.html

do { try f() } catch { print(error) }
来源：http://dali.jqgufenzy.top/Article/details/gttwiwxvji.html

[T28] Swift：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojkeompy.html

enum Color { case red, green }
来源：http://dali.kuanghao11.cn/Article/details/gtyihfsltl.html

[T29] Swift：guard 提前返回
来源：http://dali.yangfankeji.com/Article/details/gtnewsqubw.html

guard let x = opt else { return }
来源：http://dali.jqgufenzy.top/Article/details/gtatnieroc.html

[T30] Swift：协议
来源：http://dali.hfpthk.cn/Article/details/gtzvhbkcjh.html

protocol Shape { func area() -> Double }
来源：http://dali.dashuyun.cn/Article/details/gtujphuese.html

[T31] Lua：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhdschhi.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtrtpgrjuj.html

[T32] Lua：局部变量
来源：http://dali.ehwqpu.com/Article/details/gtkzsitikh.html

local a = 1
来源：http://dali.tian-w.cn/Article/details/gtiakfqyzb.html

[T33] Lua：表（数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtflprtjlh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ppjwa.cn/Article/details/gtyjteutxq.html

[T34] Lua：遍历表
来源：http://dali.yuanzhike.top/Article/details/gtkxcgrrch.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.andypj.xyz/Article/details/gtmehvpztv.html

[T35] Lua：字典表
来源：http://dali.9152youxi.cn/Article/details/gtroqirssn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sweek.top/Article/details/gtaqwnqdms.html

[T36] Lua：函数
来源：http://dali.jianghu66.top/Article/details/gtnowznsnr.html

function add(a, b) return a + b end
来源：http://dali.shuidangran.top/Article/details/gtuecofhxd.html

[T37] Lua：字符串拼接
来源：http://dali.meibo888.top/Article/details/gtpoazrgwb.html

"a" .. "b"
来源：http://dali.0kj1m.cn/Article/details/gtxellatpm.html

[T38] Lua：条件
来源：http://dali.yangfankeji.com/Article/details/gtusitpbjw.html

if x > 0 then print("正") end
来源：http://dali.aibaodan.cn/Article/details/gtjgkbquoq.html

[T39] Lua：模式匹配
来源：http://dali.cashguo.top/Article/details/gtyugiqsjc.html

string.find(s, "%d+")
来源：http://dali.chenlongwang.top/Article/details/gtobrufmkt.html

[T40] Lua：元表
来源：http://dali.hysaishi.cn/Article/details/gtzkdyyutd.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigufen.top/Article/details/gtogleddyi.html

[T41] Perl：Hello World
来源：http://dali.shuidangran.top/Article/details/gtmxxviglf.html

print "Hello\n";
来源：http://dali.wangdashe.top/Article/details/gtgddflwgl.html

[T42] Perl：变量类型
来源：http://dali.zhiwuduotai.top/Article/details/gtceousfcm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.quarkkingdee.top/Article/details/gttgpxdcqf.html

[T43] Perl：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtayiqqnok.html

"值: $a"
来源：http://dali.andypj.xyz/Article/details/gtfkgloihd.html

[T44] Perl：条件
来源：http://dali.jinqigfzy.top/Article/details/gtixhxfglb.html

if ($a > 0) { print "正"; }
来源：http://dali.yj202588.top/Article/details/gtkxhespgb.html

[T45] Perl：数组遍历
来源：http://dali.cdnleiting.top/Article/details/gtomaixuki.html

for my $x (@arr) { print $x; }
来源：http://dali.xuanzx.com/Article/details/gtqwlvlmql.html

[T46] Perl：哈希操作
来源：http://dali.yj202588.top/Article/details/gtrtmsjnhs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tanke756.top/Article/details/gtuyumhdig.html

[T47] Perl：正则捕获
来源：http://dali.guannengcc.top/Article/details/gtklphmdya.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yonumen.top/Article/details/gtnuymwivt.html

[T48] Perl：正则替换
来源：http://dali.hnxiangtu.top/Article/details/gtowjugfcr.html

$s =~ s/old/new/g;
来源：http://dali.jyoumei.cn/Article/details/gtuboontqw.html

[T49] Perl：函数
来源：http://dali.hywenlv.cn/Article/details/gttveldbme.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtrrndrxoc.html

[T50] Perl：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtqwvfioau.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.daxiang520.top/Article/details/gtgkppsszp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fzhhl.top/Article/details/gtljwcgqtz.html

[T51] Scala：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtwvhdqioq.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gtmzccymjb.html

[T52] Scala：变量
来源：http://dali.andypj.xyz/Article/details/gtedpszfie.html

val a = 1;  var b = 2
来源：http://dali.xinyue.icu/Article/details/gtjxfynjfu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtxpguebts.html

s"值: $b"
来源：http://dali.yj202588.top/Article/details/gthwtjxotk.html

[T54] Scala：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlnarhep.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ehwqpu.com/Article/details/gtagfyzeie.html

[T55] Scala：集合过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtbmcyyyqp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xziqi.cn/Article/details/gtfrynlnho.html

[T56] Scala：样例类
来源：http://dali.chenjidiqi.icu/Article/details/gtyjjwthbw.html

case class User(name: String, age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gtletnqoda.html

[T57] Scala：模式匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtrdfqrmgz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.kuanghao11.cn/Article/details/gtquqteene.html

[T58] Scala：函数定义
来源：http://dali.guowangkeji.top/Article/details/gtmqzsivvv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnonvcjh.html

[T59] Scala：循环
来源：http://dali.hnxiangtu.top/Article/details/gtiiszcutv.html

for (i <- 1 to 10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gtarjkfqfl.html

[T60] Scala：折叠
来源：http://dali.jinqigufen.top/Article/details/gtcttgpjab.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.redwolf501.top/Article/details/gtpoczxzmp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtcxnyirym.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.svipenyu.cn/Article/details/gtaxagspcn.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gttowptamy.html

[U01] Py：创建虚拟环境
来源：http://dali.sysykeji.top/Article/details/gtwuxihctm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yangfankeji.com/Article/details/gtlggueqeg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zycfv.cn/Article/details/gtwonjtrks.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sxryk.cn/Article/details/gtwbsbrgcj.html

[U03] Py：加载 .env 配置
来源：http://dali.cheryme.top/Article/details/gtaidnmmzg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cqqwz.cn/Article/details/gtjmthuyzv.html

[U04] Py：变量调试打印
来源：http://dali.jiagoushi.top/Article/details/gtwkpkoccb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.quarkkingdee.top/Article/details/gtyotnojrp.html

[U05] Py：列表去重且保序
来源：http://dali.jinqigfzy.top/Article/details/gtjnbudqtz.html

list(dict.fromkeys(arr))
来源：http://dali.sufxvd.cn/Article/details/gtipbefatf.html

[U06] Py：合并两个字典
来源：http://dali.svipenyu.cn/Article/details/gtpidvjrmo.html

{**a, **b}
来源：http://dali.jiagoushi.top/Article/details/gtjwzvbwjj.html

[U07] Py：反转字典键值
来源：http://dali.shangyingyoupin.top/Article/details/gtcfaqeqnw.html

{v: k for k, v in d.items()}
来源：http://dali.dashuyun.cn/Article/details/gtlbzsvyxg.html

[U08] Py：展平二维列表
来源：http://dali.9152youxi.cn/Article/details/gtxryuqstz.html

[y for x in nested for y in x]
来源：http://dali.zhixingplan.top/Article/details/gtycvvvsis.html

[U09] Py：字典取最大值的键
来源：http://dali.zhiwuduotai.top/Article/details/gtwwdttlye.html

max(d, key=d.get)
来源：http://dali.birdmap.top/Article/details/gthzvwcfut.html

[U10] Py：按值排序字典
来源：http://dali.tian-w.cn/Article/details/gtytroskol.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xuetiantiany.cn/Article/details/gttyuenbka.html

[U11] Py：生成器表达式
来源：http://dali.zycfv.cn/Article/details/gtetsxwpym.html

(x * 2 for x in arr)
来源：http://dali.jlsjyb.cn/Article/details/gtarilhuqr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.wangdashe.top/Article/details/gtwwfprkew.html

Counter(arr).most_common(3)
来源：http://dali.hywenlv.cn/Article/details/gtssuvbfmu.html

[U13] Py：固定长度队列
来源：http://dali.jinqigufen.top/Article/details/gtpazcyrki.html

deque(maxlen=10)
来源：http://dali.birdmap.top/Article/details/gttwovfvuf.html

[U14] Py：分组收集到列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaosxlpjc.html

defaultdict(list)
来源：http://dali.chenzaomai.com/Article/details/gtdfvnswjj.html

[U15] Py：高精度计时
来源：http://dali.zdqjudy.top/Article/details/gteziomusk.html

t = time.perf_counter()
来源：http://dali.chenlongwang.top/Article/details/gthtdiyytd.html

[U16] Py：命令行参数解析
来源：http://dali.fzhhl.top/Article/details/gtzxlgrgmt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.havefunace.top/Article/details/gtgedombfn.html

[U17] Py：初始化日志
来源：http://dali.yj202588.top/Article/details/gtdgeeswev.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xinyue.icu/Article/details/gtqacrlzfr.html

[U18] Py：预编译正则
来源：http://dali.pycfn.com/Article/details/gtasujxfyi.html

pat = re.compile(r"\d+")
来源：http://dali.guowangkeji.top/Article/details/gtquzgkpst.html

[U19] Py：正则替换带回调
来源：http://dali.shzxlz.cn/Article/details/gttclpypjb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gotoacloud.top/Article/details/gtcavwsrbm.html

[U20] Py：缓存函数结果
来源：http://dali.cashguo.top/Article/details/gtahrefzqo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xinyue.icu/Article/details/gtyyyrsans.html

[U21] Py：自定义上下文管理器
来源：http://dali.tanke756.top/Article/details/gtxslztaxj.html

@contextlib.contextmanager
来源：http://dali.shuidangran.top/Article/details/gtsmvjintp.html

[U22] Py：矩阵转置
来源：http://dali.zdqjudy.top/Article/details/gtknbmlndn.html

list(zip(*m))
来源：http://dali.hysaishi.cn/Article/details/gtfytwnrpg.html


<!-- 参考信息 -->