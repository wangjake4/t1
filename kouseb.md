代发 wailian999

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gtxmtdwvbp.html

[S06] C：字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gtrtxfekde.html

strcmp(a, b) == 0
来源：http://dali.hywenlv.cn/Article/details/gtbvzbmjhv.html

[S07] C：数组遍历求和
来源：http://dali.yangfankeji.com/Article/details/gtmukmqqrg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.redwolf501.top/Article/details/gtwteujkne.html

[S08] C：动态内存分配与释放
来源：http://dali.feifeiyinyue.top/Article/details/gtnyhhtntw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cashguo.top/Article/details/gtnelokyll.html

[S09] C：结构体定义与初始化
来源：http://dali.chenjidiqi.icu/Article/details/gtirzbphbe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.iojbl.cn/Article/details/gtusfyccel.html

[S10] C：指针与解引用
来源：http://dali.tianlin.xyz/Article/details/gtarmwwmjz.html

int *p = &a;  *p = 5;
来源：http://dali.nanxinkj.top/Article/details/gtnawrdgmb.html

[S11] C：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtfghroroo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxinkj.top/Article/details/gtqffpmmxh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtcawpdmxs.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gtvyorhbwx.html

[S12] C：写文件
来源：http://dali.sxryk.cn/Article/details/gtlisyalot.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.iojbl.cn/Article/details/gtrcyckaqw.html

[S13] C：宏定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfbsyhye.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gtwvaqvfao.html

[S14] C：枚举
来源：http://dali.iojbl.cn/Article/details/gtifkxpwyy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sufxvd.cn/Article/details/gtuytamczk.html

[S15] C：类型转换
来源：http://dali.shzxlz.cn/Article/details/gtsvbmjomj.html

(double) a / b
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxsyaxmv.html

[S16] C：位操作置位
来源：http://dali.guannengcc.top/Article/details/gtnhxlcwum.html

x |= (1 << 3);
来源：http://dali.yuxming.cn/Article/details/gtwzfnqrlk.html

[S17] C：安全拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtgpzqvudu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cdnleiting.top/Article/details/gtzesyzvfv.html

[S18] C：命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkraoytb.html

int main(int argc, char **argv)
来源：http://dali.iojbl.cn/Article/details/gtobamyiof.html

[S19] C：快速排序
来源：http://dali.tanke756.top/Article/details/gtsdyrgykj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gtvbuwqefm.html

[S20] C：二分查找
来源：http://dali.jqgfzy.top/Article/details/gtirtgowhe.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gttbfyjxjf.html

[S21] C：字符类别判断
来源：http://dali.xinyue.icu/Article/details/gtkpldwmih.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ydzc1.top/Article/details/gtvegtflxt.html

[S22] C：字符串转数字
来源：http://dali.dashuyun.cn/Article/details/gtvjxhneio.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ydzc1.top/Article/details/gtegcgksuq.html

[S23] C：随机数
来源：http://dali.9152youxi.cn/Article/details/gtlgldxvli.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tian-w.cn/Article/details/gtwwpnlhvi.html

[S24] C：获取本地时间
来源：http://dali.gogol.net.cn/Article/details/gtnjdxkulv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sufxvd.cn/Article/details/gtfyfpexnk.html

[S25] C：内存拷贝
来源：http://dali.ivvv.top/Article/details/gttalwdqvw.html

memcpy(dst, src, n);
来源：http://dali.mhx1999.top/Article/details/gtsxqplbyt.html

[S26] C：内存清零
来源：http://dali.meibo888.top/Article/details/gtkymnkmvj.html

memset(a, 0, sizeof a);
来源：http://dali.daria6918.cn/Article/details/gtsudfysew.html

[S27] C：定义常量
来源：http://dali.xinyue.icu/Article/details/gtitruxgdj.html

const double PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gtjfxtjrlc.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gtopixzyms.html

static int counter = 0;
来源：http://dali.pengpengdd.cyou/Article/details/gtpqxmjulo.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gthmbtafwa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhixingplan.top/Article/details/gtukmayhsy.html

[S30] C：头文件保护
来源：http://dali.yj20258.top/Article/details/gtqmefexzp.html

#ifndef X_H
来源：http://dali.birdmap.top/Article/details/gtrfwpekas.html

#define X_H
来源：http://dali.zdqjudy.top/Article/details/gtatqdneig.html

#endif
来源：http://dali.sxryk.cn/Article/details/gtzswdoqqc.html

[S31] C++：Hello World
来源：http://dali.jyoumei.cn/Article/details/gttepwwuyp.html

#include <iostream>
来源：http://dali.sysykeji.top/Article/details/gtvjvuqptn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.redwolf501.top/Article/details/gtnhkylpvt.html

[S32] C++：字符串
来源：http://dali.cdnleiting.top/Article/details/gtafwhxekm.html

std::string s = "hi";  s += "!";
来源：http://dali.zycfv.cn/Article/details/gtsaqrujey.html

[S33] C++：vector 增删
来源：http://dali.316326.xyz/Article/details/gttjrzesqp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuanzx.com/Article/details/gtdobwrhsu.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gtethnpefl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xziqi.cn/Article/details/gtcerxfrpz.html

[S35] C++：map
来源：http://dali.shzxlz.cn/Article/details/gtbmksxxrh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtzgelrrvn.html

[S36] C++：unordered_map
来源：http://dali.xuanzx.com/Article/details/gtxcsregci.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtbvoxpkel.html

[S37] C++：set
来源：http://dali.yj20258888.top/Article/details/gtstlbylkf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cqqwz.cn/Article/details/gtdjkcxnko.html

[S38] C++：排序
来源：http://dali.hongshengwenyu.top/Article/details/gtdvfrmyeq.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gtncjqvcri.html

[S39] C++：自定义比较器排序
来源：http://dali.yuxming.cn/Article/details/gtqrrynwgb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258.top/Article/details/gtkstkbucy.html

[S40] C++：查找元素
来源：http://dali.yuanzhike.top/Article/details/gtvameiyzq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gaohongyu789.top/Article/details/gtjaodxidz.html

[S41] C++：类与构造函数
来源：http://dali.andypj.xyz/Article/details/gtzasxpyfi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258.top/Article/details/gthouigshl.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gtvbjxedvy.html

class B : public Base { public: void f() override {} };
来源：http://dali.gotoacloud.top/Article/details/gtmpzxemxv.html

[S43] C++：智能指针
来源：http://dali.316326.xyz/Article/details/gtnivlrwae.html

auto p = std::make_unique<int>(5);
来源：http://dali.cucudq.cn/Article/details/gtgkcdingn.html

[S44] C++：引用传参
来源：http://dali.chenzaomai.com/Article/details/gtdkltcjeq.html

void inc(int &x) { ++x; }
来源：http://dali.cqqwz.cn/Article/details/gtzrmbzibi.html

[S45] C++：lambda
来源：http://dali.redwolf501.top/Article/details/gtwyumqfdk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tian-w.cn/Article/details/gtmpwcyvnu.html

[S46] C++：函数模板
来源：http://dali.iojbl.cn/Article/details/gtapgjywux.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuanzhike.top/Article/details/gtofxevglq.html

[S47] C++：结构化绑定遍历
来源：http://dali.kuanghao11.cn/Article/details/gtkxdmlmux.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ehwqpu.com/Article/details/gtdcujloyw.html

[S48] C++：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtzjxsglye.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guowangkeji.top/Article/details/gthflhtfgf.html

while (std::getline(in, line)) { }
来源：http://dali.dianchejie.cn/Article/details/gtgwdnqhnb.html

[S49] C++：写文件
来源：http://dali.yangfankeji.com/Article/details/gttgentagz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sufxvd.cn/Article/details/gtloxzevcb.html

[S50] C++：格式化数字
来源：http://dali.nanxuanxn.top/Article/details/gtgaowphny.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj202588.top/Article/details/gtbepbborr.html

[S51] C++：显式类型转换
来源：http://dali.316326.xyz/Article/details/gtkopmlrqt.html

static_cast<double>(a) / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqiqfyjo.html

[S52] C++：const 与 noexcept
来源：http://dali.xuetiantiany.cn/Article/details/gtlytrjxxf.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258888.top/Article/details/gtulhyghkn.html

[S53] C++：移动语义
来源：http://dali.zhixingplan.top/Article/details/gtltilhopp.html

std::vector<int> w = std::move(v);
来源：http://dali.redwolf501.top/Article/details/gtolsbnngf.html

[S54] C++：异常处理
来源：http://dali.jqgfzy.top/Article/details/gtwzwcwebc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guowangkeji.top/Article/details/gtkfwodoyi.html

[S55] C++：结构化绑定
来源：http://dali.cqqwz.cn/Article/details/gtptxppett.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gtevbsbyqb.html

[S56] C++：optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoysmzvro.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.iojbl.cn/Article/details/gtdilipxse.html

[S57] C++：编译期常量
来源：http://dali.hywenlv.cn/Article/details/gttgpibdkq.html

constexpr int N = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtdlfnpnsc.html

[S58] C++：命名空间
来源：http://dali.xylfe.cn/Article/details/gthnkzfcjl.html

namespace ns { int f() { return 1; } }
来源：http://dali.ivvv.top/Article/details/gtvmlanfqj.html

[S59] C++：静态断言
来源：http://dali.jlsjyb.cn/Article/details/gtvnqjzejo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dianchejie.cn/Article/details/gtqeckkjov.html

[S60] C++：遍历并删除元素
来源：http://dali.sxryk.cn/Article/details/gttaxwbnff.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtdmsqovny.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtbhjvomqo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zdqjudy.top/Article/details/gtwomwgied.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtsrdudqzz.html

[T01] Kotlin：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtywpjbtiz.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gtqplxnqyr.html

[T02] Kotlin：变量
来源：http://dali.feifeiyinyue.top/Article/details/gttftkrniq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cqqwz.cn/Article/details/gttwdydzbm.html

[T03] Kotlin：字符串模板
来源：http://dali.hysaishi.cn/Article/details/gtjruhmcjv.html

"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gtelkteqct.html

[T04] Kotlin：空安全
来源：http://dali.zycfv.cn/Article/details/gthujxtuam.html

val n: String? = null;  n?.length
来源：http://dali.yuxming.cn/Article/details/gtcdaouzqe.html

[T05] Kotlin：when 表达式
来源：http://dali.daxiang520.top/Article/details/gtktddcdax.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shuidangran.top/Article/details/gtcvdkyvud.html

[T06] Kotlin：集合映射
来源：http://dali.0kj1m.cn/Article/details/gtucypsxlh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtiiogmhpd.html

[T07] Kotlin：集合过滤
来源：http://dali.yangfankeji.com/Article/details/gtpcrnzkow.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.c1oappe.top/Article/details/gtezrbrwfs.html

[T08] Kotlin：数据类
来源：http://dali.tian-w.cn/Article/details/gtdmpdyitk.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxuanxn.top/Article/details/gtaodzisgx.html

[T09] Kotlin：扩展函数
来源：http://dali.gotoacloud.top/Article/details/gtnxwplggk.html

fun String.exclaim() = this + "!"
来源：http://dali.ydzc1.top/Article/details/gtoavzxgzz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtaesqnzwd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ivvv.top/Article/details/gtileubhgz.html

[T11] Kotlin：协程
来源：http://dali.aibaodan.cn/Article/details/gtzwacpbfb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zycfv.cn/Article/details/gtgtktwnxy.html

[T12] Kotlin：解构声明
来源：http://dali.wangdashe.top/Article/details/gtptlpjgqc.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gtmhnibxwn.html

[T13] Kotlin：只读 Map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypfnuckq.html

val m = mapOf("a" to 1)
来源：http://dali.hnxiangtu.top/Article/details/gtvonkpblm.html

[T14] Kotlin：循环
来源：http://dali.hammf.cn/Article/details/gtdpfchpps.html

for (i in 1..10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gtqeqybnin.html

[T15] Kotlin：接口
来源：http://dali.yj202588.top/Article/details/gtrxjepqsy.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpccqqzb.html

[T16] Swift：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtrhydxlwz.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gtyeqeqfdc.html

[T17] Swift：变量与常量
来源：http://dali.cucudq.cn/Article/details/gtgnzbnsbf.html

var a = 1;  let b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtooukorrz.html

[T18] Swift：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtnsdkhidh.html

"值: \(b)"
来源：http://dali.hywenlv.cn/Article/details/gtbkudjdgf.html

[T19] Swift：可选绑定
来源：http://dali.dashuyun.cn/Article/details/gttevivnrz.html

if let n = opt { print(n) }
来源：http://dali.mhx1999.top/Article/details/gtqnwipmii.html

[T20] Swift：数组操作
来源：http://dali.iojbl.cn/Article/details/gthyelehfd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sxryk.cn/Article/details/gttcluwauj.html

[T21] Swift：遍历
来源：http://dali.yonumen.top/Article/details/gtlksiirhe.html

for x in a { print(x) }
来源：http://dali.smart0.xyz/Article/details/gtinpsnylz.html

[T22] Swift：字典
来源：http://dali.dianchejie.cn/Article/details/gtwqnbkutz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.daxiang520.top/Article/details/gtcboifvqf.html

[T23] Swift：函数
来源：http://dali.tanke756.top/Article/details/gtdfbwwnxx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cdnleiting.top/Article/details/gtlbktipdp.html

[T24] Swift：闭包
来源：http://dali.zhiwuduotai.top/Article/details/gtdrhnqvgn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtwwzaotww.html

[T25] Swift：结构体
来源：http://dali.jinqigufen.top/Article/details/gtbxmwueia.html

struct P { var x: Int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvmakjnx.html

[T26] Swift：类与重写
来源：http://dali.aibaodan.cn/Article/details/gtpmeizeql.html

class A: Base { override func f() {} }
来源：http://dali.zhoulong.xyz/Article/details/gtvapfnbza.html

[T27] Swift：错误处理
来源：http://dali.zhoulong.xyz/Article/details/gtcabzvzvx.html

do { try f() } catch { print(error) }
来源：http://dali.svipenyu.cn/Article/details/gtwigeiiit.html

[T28] Swift：枚举
来源：http://dali.havefunace.top/Article/details/gthvrvzcam.html

enum Color { case red, green }
来源：http://dali.daxiang520.top/Article/details/gtpfiqqewh.html

[T29] Swift：guard 提前返回
来源：http://dali.cqqwz.cn/Article/details/gtgiqwjfbs.html

guard let x = opt else { return }
来源：http://dali.andypj.xyz/Article/details/gtxsxvzpbz.html

[T30] Swift：协议
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhahazud.html

protocol Shape { func area() -> Double }
来源：http://dali.fzhhl.top/Article/details/gtonvbdrmd.html

[T31] Lua：Hello World
来源：http://dali.zycfv.cn/Article/details/gtbdyzqblw.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyadwcdzr.html

[T32] Lua：局部变量
来源：http://dali.aibaodan.cn/Article/details/gtxxxfqazk.html

local a = 1
来源：http://dali.smart0.xyz/Article/details/gthapcguxp.html

[T33] Lua：表（数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixyagjol.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shzxlz.cn/Article/details/gtohccbzqp.html

[T34] Lua：遍历表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfdpjzzx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hywenlv.cn/Article/details/gtflqrgtia.html

[T35] Lua：字典表
来源：http://dali.haohaochexian.top/Article/details/gtplxaadvl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenzaomai.com/Article/details/gtnxbymygt.html

[T36] Lua：函数
来源：http://dali.yanxiufei.cn/Article/details/gtxpbhvyix.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrxljtpt.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258.top/Article/details/gtsglnqqss.html

"a" .. "b"
来源：http://dali.yongpay.top/Article/details/gttpqmbzbj.html

[T38] Lua：条件
来源：http://dali.cheryme.top/Article/details/gtexvvqmue.html

if x > 0 then print("正") end
来源：http://dali.cdnleiting.top/Article/details/gtgwbvzfnx.html

[T39] Lua：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gtltasankc.html

string.find(s, "%d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhtkvtmh.html

[T40] Lua：元表
来源：http://dali.tian-w.cn/Article/details/gtayzopcgy.html

setmetatable({}, { __index = base })
来源：http://dali.sxryk.cn/Article/details/gteitwkktt.html

[T41] Perl：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtnilqcjaj.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gtxczzrvwu.html

[T42] Perl：变量类型
来源：http://dali.mhx1999.top/Article/details/gtlqcmuzzl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenlongwang.top/Article/details/gtannermgc.html

[T43] Perl：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtjkykyoem.html

"值: $a"
来源：http://dali.zhoulong.xyz/Article/details/gtzllgfgwq.html

[T44] Perl：条件
来源：http://dali.yonumen.top/Article/details/gtcuukcjts.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjhokeyx.html

[T45] Perl：数组遍历
来源：http://dali.hysaishi.cn/Article/details/gtpczbalbo.html

for my $x (@arr) { print $x; }
来源：http://dali.yuxming.cn/Article/details/gthlbimxfx.html

[T46] Perl：哈希操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqgqzlhx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cashguo.top/Article/details/gttpushmfy.html

[T47] Perl：正则捕获
来源：http://dali.zhongyouzk.top/Article/details/gtodaqodce.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ppjwa.cn/Article/details/gtsmdiwmlp.html

[T48] Perl：正则替换
来源：http://dali.jqgufenzy.top/Article/details/gtnokdvpvp.html

$s =~ s/old/new/g;
来源：http://dali.guowangkeji.top/Article/details/gtenlbnzko.html

[T49] Perl：函数
来源：http://dali.nanxinkj.top/Article/details/gtdcwvpbzw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtzaekbpbs.html

[T50] Perl：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtsppwkcco.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.fzhhl.top/Article/details/gtlqbzqkjf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pycfn.com/Article/details/gtzbfgeika.html

[T51] Scala：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtedrxcwsl.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtkccdhopo.html

[T52] Scala：变量
来源：http://dali.chenlongwang.top/Article/details/gtgagscmhn.html

val a = 1;  var b = 2
来源：http://dali.jiagoushi.top/Article/details/gtdfgbiyos.html

[T53] Scala：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtruisokjb.html

s"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gtcsyrptqn.html

[T54] Scala：集合映射
来源：http://dali.cheryme.top/Article/details/gthyfpofoz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtwihdvhce.html

[T55] Scala：集合过滤
来源：http://dali.yj20258.top/Article/details/gtjwrgfgmh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sweek.top/Article/details/gtcoblsnrq.html

[T56] Scala：样例类
来源：http://dali.andypj.xyz/Article/details/gtxekblegc.html

case class User(name: String, age: Int)
来源：http://dali.sxryk.cn/Article/details/gtviiepckc.html

[T57] Scala：模式匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzjmfrfc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dianchejie.cn/Article/details/gtktuvtdlp.html

[T58] Scala：函数定义
来源：http://dali.jqgufenzy.top/Article/details/gtyvctmgwa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtyntmmndp.html

[T59] Scala：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnlysgwz.html

for (i <- 1 to 10) println(i)
来源：http://dali.yangfankeji.com/Article/details/gtqagkqywi.html

[T60] Scala：折叠
来源：http://dali.xinyue.icu/Article/details/gtriatxjdf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yueranfly.top/Article/details/gtkekujdae.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtaubewzak.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sysykeji.top/Article/details/gtojoulyev.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gttmavmtft.html

[U01] Py：创建虚拟环境
来源：http://dali.gaohongyu789.top/Article/details/gtbjazglkz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.birdmap.top/Article/details/gthutfislf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.birdmap.top/Article/details/gtvyeimikh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgfzy.top/Article/details/gtiuyxnjax.html

[U03] Py：加载 .env 配置
来源：http://dali.yj202588.top/Article/details/gtmsajmvzt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhiwuduotai.top/Article/details/gtgpfnpjbx.html

[U04] Py：变量调试打印
来源：http://dali.yj20258.top/Article/details/gtnsudbhxf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigufen.top/Article/details/gtqmyswnta.html

[U05] Py：列表去重且保序
来源：http://dali.gogol.net.cn/Article/details/gtxgtpllbl.html

list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gthcqpklld.html

[U06] Py：合并两个字典
来源：http://dali.xuanzx.com/Article/details/gtslvuxcaq.html

{**a, **b}
来源：http://dali.yj20258.top/Article/details/gtuhixizvl.html

[U07] Py：反转字典键值
来源：http://dali.jlsjyb.cn/Article/details/gttdnloijb.html

{v: k for k, v in d.items()}
来源：http://dali.wangdashe.top/Article/details/gtnmdgdeuc.html

[U08] Py：展平二维列表
来源：http://dali.c1oappe.top/Article/details/gtvinlrtan.html

[y for x in nested for y in x]
来源：http://dali.birdmap.top/Article/details/gtirokrxws.html

[U09] Py：字典取最大值的键
来源：http://dali.shzxlz.cn/Article/details/gturwpldpe.html

max(d, key=d.get)
来源：http://dali.pycfn.com/Article/details/gtbiuthpbl.html

[U10] Py：按值排序字典
来源：http://dali.chenjidiqi.icu/Article/details/gtyegqpvvg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zycfv.cn/Article/details/gtgundmaaa.html

[U11] Py：生成器表达式
来源：http://dali.ppjwa.cn/Article/details/gtbsrhqzsl.html

(x * 2 for x in arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtilxnrlap.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.kuanghao11.cn/Article/details/gtyfmrqheq.html

Counter(arr).most_common(3)
来源：http://dali.gogol.net.cn/Article/details/gtocutctyi.html

[U13] Py：固定长度队列
来源：http://dali.nwbrower.top/Article/details/gtnsxfeplh.html

deque(maxlen=10)
来源：http://dali.jinqigufen.top/Article/details/gtitejnwli.html

[U14] Py：分组收集到列表
来源：http://dali.hongshengwenyu.top/Article/details/gtuxyagwsx.html

defaultdict(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvokxomrk.html

[U15] Py：高精度计时
来源：http://dali.guannengcc.top/Article/details/gtftiuvtxn.html

t = time.perf_counter()
来源：http://dali.cheryme.top/Article/details/gteufqdkmm.html

[U16] Py：命令行参数解析
来源：http://dali.cucudq.cn/Article/details/gtazcmroiw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.andypj.xyz/Article/details/gtgcwgaseu.html

[U17] Py：初始化日志
来源：http://dali.hongshengwenyu.top/Article/details/gtllyicgkd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.dashuyun.cn/Article/details/gtzbticada.html

[U18] Py：预编译正则
来源：http://dali.316326.xyz/Article/details/gtixfxnewd.html

pat = re.compile(r"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtktmllrob.html

[U19] Py：正则替换带回调
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwddyaace.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.meibo888.top/Article/details/gtiuinkceq.html

[U20] Py：缓存函数结果
来源：http://dali.zhixingplan.top/Article/details/gtnshwpkah.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tianlin.xyz/Article/details/gtavxqcnqv.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigfzy.top/Article/details/gtjovnelkt.html

@contextlib.contextmanager
来源：http://dali.ybcxt.top/Article/details/gtulfbzcdo.html

[U22] Py：矩阵转置
来源：http://dali.jinghuilouyu.cn/Article/details/gtogferodg.html

list(zip(*m))
来源：http://dali.quarkkingdee.top/Article/details/gthfsllahn.html

[U23] Py：分块读取大文件
来源：http://dali.mhx1999.top/Article/details/gtbjqpxbaf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gaohongyu789.top/Article/details/gthartgici.html

[U24] Py：路径操作
来源：http://dali.iojbl.cn/Article/details/gtwyvlxjdc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gtrhdpgfhb.html

[U25] Py：CSV 按字典读
来源：http://dali.sxryk.cn/Article/details/gtvbdvtpeu.html

csv.DictReader(f)
来源：http://dali.hnxiangtu.top/Article/details/gtpxxbopie.html

[U26] Py：并发下载
来源：http://dali.zhiwuduotai.top/Article/details/gtppmjufdu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ybcxt.top/Article/details/gtknqfktvh.html

[U27] Py：异步 HTTP
来源：http://dali.iojbl.cn/Article/details/gtnydywvyr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.iojbl.cn/Article/details/gttlfexyxu.html

[U28] Py：类型别名
来源：http://dali.xuanzx.com/Article/details/gtaxmftckg.html

UserId = int
来源：http://dali.316326.xyz/Article/details/gtisemnlrg.html


<!-- 参考信息 -->