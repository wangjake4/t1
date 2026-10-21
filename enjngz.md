代发 wailian999

strlen(s)
来源：http://dali.ybcxt.top/Article/details/gtdeflqqvs.html

[S06] C：字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtlnwfgfhi.html

strcmp(a, b) == 0
来源：http://dali.shangyingyoupin.top/Article/details/gtmigwhveu.html

[S07] C：数组遍历求和
来源：http://dali.cheryme.top/Article/details/gtmfpnkmwa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hywenlv.cn/Article/details/gtrpgktlhl.html

[S08] C：动态内存分配与释放
来源：http://dali.fzhhl.top/Article/details/gtmiysbwcs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.mhx1999.top/Article/details/gtkgwffvds.html

[S09] C：结构体定义与初始化
来源：http://dali.daria6918.cn/Article/details/gtvquuapyg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhengqikj.top/Article/details/gtxiwgjxen.html

[S10] C：指针与解引用
来源：http://dali.haohaochexian.top/Article/details/gtzaaeosxz.html

int *p = &a;  *p = 5;
来源：http://dali.mhx1999.top/Article/details/gticuajzjq.html

[S11] C：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtwutyonri.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuanzx.com/Article/details/gthaqwslzf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuanzhike.top/Article/details/gtgpuxfgel.html

fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gtaqgtwadw.html

[S12] C：写文件
来源：http://dali.ppjwa.cn/Article/details/gtfsxakgan.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pycfn.com/Article/details/gtndcdupbb.html

[S13] C：宏定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwgybduy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxuanxn.top/Article/details/gtgdedfmhn.html

[S14] C：枚举
来源：http://dali.meibo888.top/Article/details/gthytlvelh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangdashe.top/Article/details/gtlbsdeibk.html

[S15] C：类型转换
来源：http://dali.ivvv.top/Article/details/gtybrqxybs.html

(double) a / b
来源：http://dali.ppjwa.cn/Article/details/gtexecivgh.html

[S16] C：位操作置位
来源：http://dali.aizwys.cn/Article/details/gtbkihlovy.html

x |= (1 << 3);
来源：http://dali.yvedp.cn/Article/details/gtboopeccp.html

[S17] C：安全拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtwglgrlzd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xylfe.cn/Article/details/gtmdifsqwb.html

[S18] C：命令行参数
来源：http://dali.xuanzx.com/Article/details/gtjhvpckew.html

int main(int argc, char **argv)
来源：http://dali.zycfv.cn/Article/details/gtyyrfegqs.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gtimkfcjmn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gtepiydlkx.html

[S20] C：二分查找
来源：http://dali.dashuyun.cn/Article/details/gtxnqpmwqz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gtzapddaax.html

[S21] C：字符类别判断
来源：http://dali.xinyue.icu/Article/details/gtgzjjhowk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.redwolf501.top/Article/details/gttcybmnsp.html

[S22] C：字符串转数字
来源：http://dali.zhongyouzk.top/Article/details/gtekoukmse.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ivvv.top/Article/details/gtsfywyqfn.html

[S23] C：随机数
来源：http://dali.zhoulong.xyz/Article/details/gtgviwltxf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenjidiqi.icu/Article/details/gtzvooazch.html

[S24] C：获取本地时间
来源：http://dali.xziqi.cn/Article/details/gttnyadzke.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.andypj.xyz/Article/details/gtbopedaqn.html

[S25] C：内存拷贝
来源：http://dali.jqgufenzy.top/Article/details/gtuyqatahx.html

memcpy(dst, src, n);
来源：http://dali.xinyue.icu/Article/details/gtpjzpamvx.html

[S26] C：内存清零
来源：http://dali.dianchejie.cn/Article/details/gtuhfpince.html

memset(a, 0, sizeof a);
来源：http://dali.vqdsnc.cn/Article/details/gtkpckqkpa.html

[S27] C：定义常量
来源：http://dali.dianchejie.cn/Article/details/gtmfentdca.html

const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtofgcixli.html

[S28] C：静态变量
来源：http://dali.aibaodan.cn/Article/details/gtprhfcvbc.html

static int counter = 0;
来源：http://dali.sweek.top/Article/details/gtkmqfvyfb.html

[S29] C：变参函数
来源：http://dali.birdmap.top/Article/details/gtjmdosseo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xziqi.cn/Article/details/gtexncilqs.html

[S30] C：头文件保护
来源：http://dali.jqgufenzy.top/Article/details/gtnbqgdcdb.html

#ifndef X_H
来源：http://dali.shuidangran.top/Article/details/gtkdzclahv.html

#define X_H
来源：http://dali.xylfe.cn/Article/details/gttfivfmhc.html

#endif
来源：http://dali.yangfankeji.com/Article/details/gtegblmnso.html

[S31] C++：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtzmynqjvw.html

#include <iostream>
来源：http://dali.yj20258.top/Article/details/gtfzuaedhl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yueranfly.top/Article/details/gtapdeesch.html

[S32] C++：字符串
来源：http://dali.snrcjt.cn/Article/details/gtjknvxcho.html

std::string s = "hi";  s += "!";
来源：http://dali.zycfv.cn/Article/details/gteeiulfrm.html

[S33] C++：vector 增删
来源：http://dali.dianchejie.cn/Article/details/gtyjyhjwgv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.iojbl.cn/Article/details/gtvxzsdxzr.html

[S34] C++：遍历 vector
来源：http://dali.ehwqpu.com/Article/details/gtvpdysivt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.smart0.xyz/Article/details/gtbpbjqyit.html

[S35] C++：map
来源：http://dali.dashuyun.cn/Article/details/gtvtjodgea.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtgqrfdgbt.html

[S36] C++：unordered_map
来源：http://dali.yuxming.cn/Article/details/gtydkjidme.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtjckedkfs.html

[S37] C++：set
来源：http://dali.ybcxt.top/Article/details/gtxmngemly.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxinkj.top/Article/details/gtukkuqink.html

[S38] C++：排序
来源：http://dali.iojbl.cn/Article/details/gtuuftxqar.html

std::sort(v.begin(), v.end());
来源：http://dali.jiagoushi.top/Article/details/gtmwswrurl.html

[S39] C++：自定义比较器排序
来源：http://dali.sufxvd.cn/Article/details/gtfugjybpn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.havefunace.top/Article/details/gtfkzuukuz.html

[S40] C++：查找元素
来源：http://dali.andypj.xyz/Article/details/gtgjyflucp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpoavpzw.html

[S41] C++：类与构造函数
来源：http://dali.yj20258888.top/Article/details/gtzugidtwf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tian-w.cn/Article/details/gtcwxhkdst.html

[S42] C++：继承与虚函数
来源：http://dali.shzxlz.cn/Article/details/gtbhymaoqf.html

class B : public Base { public: void f() override {} };
来源：http://dali.redwolf501.top/Article/details/gtubmycdnp.html

[S43] C++：智能指针
来源：http://dali.nanxuanxn.top/Article/details/gtmporwkod.html

auto p = std::make_unique<int>(5);
来源：http://dali.guowangkeji.top/Article/details/gtwmavnahc.html

[S44] C++：引用传参
来源：http://dali.gaohongyu789.top/Article/details/gtznevpdtq.html

void inc(int &x) { ++x; }
来源：http://dali.c1oappe.top/Article/details/gtzifwhpny.html

[S45] C++：lambda
来源：http://dali.havefunace.top/Article/details/gtvktwqwcb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.svipenyu.cn/Article/details/gtexpzxeag.html

[S46] C++：函数模板
来源：http://dali.aizwys.cn/Article/details/gtfontbpve.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xziqi.cn/Article/details/gtuzrmyuon.html

[S47] C++：结构化绑定遍历
来源：http://dali.0kj1m.cn/Article/details/gtwgcbwnpd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxuanxn.top/Article/details/gtcremhzrm.html

[S48] C++：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtuabdbanm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.9152youxi.cn/Article/details/gtftnvqmjo.html

while (std::getline(in, line)) { }
来源：http://dali.ppjwa.cn/Article/details/gtbhargnem.html

[S49] C++：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gtimtnmjjz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shuidangran.top/Article/details/gtkaioujpn.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gtjpuobwei.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtxvuwyhai.html

[S51] C++：显式类型转换
来源：http://dali.shuidangran.top/Article/details/gtzhepnlxc.html

static_cast<double>(a) / b
来源：http://dali.yuanzhike.top/Article/details/gtoifepjki.html

[S52] C++：const 与 noexcept
来源：http://dali.wangshuangyany.cn/Article/details/gtskkrqhzb.html

int size() const noexcept { return n_; }
来源：http://dali.kuanghao11.cn/Article/details/gtzknqnyri.html

[S53] C++：移动语义
来源：http://dali.pycfn.com/Article/details/gtwepgczig.html

std::vector<int> w = std::move(v);
来源：http://dali.shzxlz.cn/Article/details/gtrbvfqbyn.html

[S54] C++：异常处理
来源：http://dali.cheryme.top/Article/details/gtbrsgnxmv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ydzc1.top/Article/details/gtuoshqrix.html

[S55] C++：结构化绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhiqevvs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xziqi.cn/Article/details/gtwydmalrk.html

[S56] C++：optional
来源：http://dali.hongshengwenyu.top/Article/details/gthmcjelsa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zdqjudy.top/Article/details/gtoqncwuni.html

[S57] C++：编译期常量
来源：http://dali.gzhubu.top/Article/details/gtwtavmgin.html

constexpr int N = 10;
来源：http://dali.chenlongwang.top/Article/details/gtnzthsufb.html

[S58] C++：命名空间
来源：http://dali.redwolf501.top/Article/details/gtdtptvemj.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbslnxww.html

[S59] C++：静态断言
来源：http://dali.xuanzx.com/Article/details/gtvalbxkwg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangshuangyany.cn/Article/details/gtdpcrvzrs.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhnisyes.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pycfn.com/Article/details/gtnkypdmkg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtshkiogpj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhengqikj.top/Article/details/gtojqvhsfe.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtblsnwtmq.html

[T01] Kotlin：Hello World
来源：http://dali.xinyue.icu/Article/details/gtzjelfjnf.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtmqptimot.html

[T02] Kotlin：变量
来源：http://dali.bjfxy.top/Article/details/gteguwozlf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenlongwang.top/Article/details/gtejrokkni.html

[T03] Kotlin：字符串模板
来源：http://dali.yangfankeji.com/Article/details/gtegyhmufp.html

"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gthzauxtie.html

[T04] Kotlin：空安全
来源：http://dali.andypj.xyz/Article/details/gtfnhaxftx.html

val n: String? = null;  n?.length
来源：http://dali.gogol.net.cn/Article/details/gthfyksgmy.html

[T05] Kotlin：when 表达式
来源：http://dali.fzhhl.top/Article/details/gtlndielsp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yvedp.cn/Article/details/gthbfpwsnj.html

[T06] Kotlin：集合映射
来源：http://dali.xuanzx.com/Article/details/gtwslxycdt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhengqikj.top/Article/details/gtfdmezarm.html

[T07] Kotlin：集合过滤
来源：http://dali.c1oappe.top/Article/details/gtxotumaho.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hammf.cn/Article/details/gtjrbxfhip.html

[T08] Kotlin：数据类
来源：http://dali.jlsjyb.cn/Article/details/gtlsfmnknt.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkulonaxj.html

[T09] Kotlin：扩展函数
来源：http://dali.yvedp.cn/Article/details/gtcvetvvok.html

fun String.exclaim() = this + "!"
来源：http://dali.wangshuangyany.cn/Article/details/gtemkbykon.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gtozzdefaq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.bjfxy.top/Article/details/gtnziywnbc.html

[T11] Kotlin：协程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoezncxdx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cqqwz.cn/Article/details/gtswjjoowl.html

[T12] Kotlin：解构声明
来源：http://dali.zhengqikj.top/Article/details/gtiqtttjft.html

val (a, b) = Pair(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gtwvgdbcpa.html

[T13] Kotlin：只读 Map
来源：http://dali.chenlongwang.top/Article/details/gtefatggmp.html

val m = mapOf("a" to 1)
来源：http://dali.zycfv.cn/Article/details/gtmxonqngt.html

[T14] Kotlin：循环
来源：http://dali.yonumen.top/Article/details/gtouwprams.html

for (i in 1..10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqoucgqr.html

[T15] Kotlin：接口
来源：http://dali.c1oappe.top/Article/details/gtnjrmlzyc.html

interface Shape { fun area(): Double }
来源：http://dali.smart0.xyz/Article/details/gtlapraesn.html

[T16] Swift：Hello World
来源：http://dali.smart0.xyz/Article/details/gtddvbkijq.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtugsliwtw.html

[T17] Swift：变量与常量
来源：http://dali.nanxinkj.top/Article/details/gtunodlsov.html

var a = 1;  let b = 2
来源：http://dali.guannengcc.top/Article/details/gtipgllddm.html

[T18] Swift：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtarszdtsg.html

"值: \(b)"
来源：http://dali.yongpay.top/Article/details/gtfojvezpz.html

[T19] Swift：可选绑定
来源：http://dali.hammf.cn/Article/details/gtrqkggbkx.html

if let n = opt { print(n) }
来源：http://dali.iojbl.cn/Article/details/gthqqclklh.html

[T20] Swift：数组操作
来源：http://dali.cheryme.top/Article/details/gttnooroyl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ppjwa.cn/Article/details/gthsgirrmf.html

[T21] Swift：遍历
来源：http://dali.zdqjudy.top/Article/details/gtjmwvjtds.html

for x in a { print(x) }
来源：http://dali.yangfankeji.com/Article/details/gtgcuvrkfk.html

[T22] Swift：字典
来源：http://dali.jqgfzy.top/Article/details/gtkvmjwhza.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cdnleiting.top/Article/details/gtywhiqlao.html

[T23] Swift：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtzboxeddv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hywenlv.cn/Article/details/gttcpjdypi.html

[T24] Swift：闭包
来源：http://dali.yuxming.cn/Article/details/gtibprkcok.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfuzxngh.html

[T25] Swift：结构体
来源：http://dali.ivvv.top/Article/details/gtlqefcdkk.html

struct P { var x: Int }
来源：http://dali.chenlongwang.top/Article/details/gtltrsqeon.html

[T26] Swift：类与重写
来源：http://dali.chenjidiqi.icu/Article/details/gtlrrbmvts.html

class A: Base { override func f() {} }
来源：http://dali.yvedp.cn/Article/details/gtjwsdxczn.html

[T27] Swift：错误处理
来源：http://dali.sweek.top/Article/details/gtpavqcmgk.html

do { try f() } catch { print(error) }
来源：http://dali.jqgufenzy.top/Article/details/gtqezvnzxw.html

[T28] Swift：枚举
来源：http://dali.hnqzz.top/Article/details/gtqgbmksfy.html

enum Color { case red, green }
来源：http://dali.zhongyouzk.top/Article/details/gtrjzrldka.html

[T29] Swift：guard 提前返回
来源：http://dali.tanke756.top/Article/details/gtmassieck.html

guard let x = opt else { return }
来源：http://dali.mhx1999.top/Article/details/gtrcafknpu.html

[T30] Swift：协议
来源：http://dali.xylfe.cn/Article/details/gtjyhlmyfj.html

protocol Shape { func area() -> Double }
来源：http://dali.feifeiyinyue.top/Article/details/gtrdfzclwg.html

[T31] Lua：Hello World
来源：http://dali.yonumen.top/Article/details/gtumzyxhrh.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gtmscujdfw.html

[T32] Lua：局部变量
来源：http://dali.smart0.xyz/Article/details/gtziwafxrq.html

local a = 1
来源：http://dali.tian-w.cn/Article/details/gtwmfjkwcm.html

[T33] Lua：表（数组）
来源：http://dali.haohaochexian.top/Article/details/gtjoshujad.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhixingplan.top/Article/details/gtgkpdfnym.html

[T34] Lua：遍历表
来源：http://dali.xinyue.icu/Article/details/gtyzkmxeks.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zdqjudy.top/Article/details/gtahinxeao.html

[T35] Lua：字典表
来源：http://dali.wangshuangyany.cn/Article/details/gtgjzstari.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cashguo.top/Article/details/gtwpnucgxs.html

[T36] Lua：函数
来源：http://dali.pycfn.com/Article/details/gtfxovnnds.html

function add(a, b) return a + b end
来源：http://dali.cucudq.cn/Article/details/gtekenvjyg.html

[T37] Lua：字符串拼接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehkwsxpr.html

"a" .. "b"
来源：http://dali.zhixingplan.top/Article/details/gtjacawfcf.html

[T38] Lua：条件
来源：http://dali.zhongyouzk.top/Article/details/gtjxzlmmyh.html

if x > 0 then print("正") end
来源：http://dali.hfpthk.cn/Article/details/gtworjdgdx.html

[T39] Lua：模式匹配
来源：http://dali.quarkkingdee.top/Article/details/gtnzxfxkmd.html

string.find(s, "%d+")
来源：http://dali.shuidangran.top/Article/details/gtogazlyhh.html

[T40] Lua：元表
来源：http://dali.redwolf501.top/Article/details/gtiyemuxzv.html

setmetatable({}, { __index = base })
来源：http://dali.andypj.xyz/Article/details/gtswhvjphp.html

[T41] Perl：Hello World
来源：http://dali.yj202588.top/Article/details/gthbkorbmr.html

print "Hello\n";
来源：http://dali.feifeiyinyue.top/Article/details/gtfzogfakf.html

[T42] Perl：变量类型
来源：http://dali.jinqigfzy.top/Article/details/gtpzoriqgw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xinyue.icu/Article/details/gtuvchznpy.html

[T43] Perl：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gthdyjyoxo.html

"值: $a"
来源：http://dali.hammf.cn/Article/details/gtpjwokbwv.html

[T44] Perl：条件
来源：http://dali.hfpthk.cn/Article/details/gtobqrmzts.html

if ($a > 0) { print "正"; }
来源：http://dali.ybcxt.top/Article/details/gtlfsatdpr.html

[T45] Perl：数组遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyznortj.html

for my $x (@arr) { print $x; }
来源：http://dali.ydzc1.top/Article/details/gtvruwkmrp.html

[T46] Perl：哈希操作
来源：http://dali.bjfxy.top/Article/details/gtyuwmgfrc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhubmykt.html

[T47] Perl：正则捕获
来源：http://dali.hnxiangtu.top/Article/details/gtmzhnfkgw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hysaishi.cn/Article/details/gtnhlelaap.html

[T48] Perl：正则替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmcuxgvc.html

$s =~ s/old/new/g;
来源：http://dali.xziqi.cn/Article/details/gtfohsciud.html

[T49] Perl：函数
来源：http://dali.yanxiufei.cn/Article/details/gthhcmsmzy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtqmvdpwbz.html

[T50] Perl：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtuzhgzked.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hnqzz.top/Article/details/gtkdlhxzaw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.aibaodan.cn/Article/details/gthqltibkj.html

[T51] Scala：Hello World
来源：http://dali.sxryk.cn/Article/details/gtyaganbzi.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gtqqrsnllz.html

[T52] Scala：变量
来源：http://dali.aizwys.cn/Article/details/gtzfcipffg.html

val a = 1;  var b = 2
来源：http://dali.dianchejie.cn/Article/details/gtkohutego.html

[T53] Scala：字符串插值
来源：http://dali.fzhhl.top/Article/details/gtbmcmuclo.html

s"值: $b"
来源：http://dali.andypj.xyz/Article/details/gtdhrijkce.html

[T54] Scala：集合映射
来源：http://dali.daria6918.cn/Article/details/gtevwuontk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtenkfsvzy.html

[T55] Scala：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gtzvaekmsr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fengsongda.top/Article/details/gtgwcbikur.html

[T56] Scala：样例类
来源：http://dali.yonumen.top/Article/details/gtgtfyxyvs.html

case class User(name: String, age: Int)
来源：http://dali.hfpthk.cn/Article/details/gtxppgprxp.html

[T57] Scala：模式匹配
来源：http://dali.shzxlz.cn/Article/details/gtppegaxxn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.fzhhl.top/Article/details/gtmdgnxrcu.html

[T58] Scala：函数定义
来源：http://dali.aizwys.cn/Article/details/gtzwikceaa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtpohvfkbq.html

[T59] Scala：循环
来源：http://dali.tanke756.top/Article/details/gtiogkufiy.html

for (i <- 1 to 10) println(i)
来源：http://dali.c1oappe.top/Article/details/gtyopmflwp.html

[T60] Scala：折叠
来源：http://dali.meibo888.top/Article/details/gtwjxsfuev.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgufenzy.top/Article/details/gtyyxkwxoh.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtiqwkhkba.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfaizujjj.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtpyxiakwx.html

[U01] Py：创建虚拟环境
来源：http://dali.zycfv.cn/Article/details/gttlicrdqc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.vqdsnc.cn/Article/details/gtqiisjauf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.birdmap.top/Article/details/gtasrxtvfp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gzhubu.top/Article/details/gttlgglcwx.html

[U03] Py：加载 .env 配置
来源：http://dali.jinqigufen.top/Article/details/gtlbqclwlt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlmkjjgx.html

[U04] Py：变量调试打印
来源：http://dali.fzhhl.top/Article/details/gtijycytaw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj20258888.top/Article/details/gtfxubtkpu.html

[U05] Py：列表去重且保序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvikjcyvx.html

list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gtcuyjjozc.html

[U06] Py：合并两个字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdyxbaoat.html

{**a, **b}
来源：http://dali.hnxiangtu.top/Article/details/gtwgtldwbc.html

[U07] Py：反转字典键值
来源：http://dali.0kj1m.cn/Article/details/gtcahodtjx.html

{v: k for k, v in d.items()}
来源：http://dali.cheryme.top/Article/details/gtypvepalg.html

[U08] Py：展平二维列表
来源：http://dali.chenlongwang.top/Article/details/gtdinqnmji.html

[y for x in nested for y in x]
来源：http://dali.aizwys.cn/Article/details/gtfzotxjaz.html

[U09] Py：字典取最大值的键
来源：http://dali.fengsongda.top/Article/details/gtpnpwbxdb.html

max(d, key=d.get)
来源：http://dali.ybcxt.top/Article/details/gtbauyvasu.html

[U10] Py：按值排序字典
来源：http://dali.vqdsnc.cn/Article/details/gtbvvogixp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fengsongda.top/Article/details/gtfubqhgtb.html

[U11] Py：生成器表达式
来源：http://dali.jinqigfzy.top/Article/details/gthsqtucfj.html

(x * 2 for x in arr)
来源：http://dali.cdnleiting.top/Article/details/gtwlrndfux.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sysykeji.top/Article/details/gtxbidttux.html

Counter(arr).most_common(3)
来源：http://dali.shzxlz.cn/Article/details/gtffhakwvs.html

[U13] Py：固定长度队列
来源：http://dali.redwolf501.top/Article/details/gtrhbbgoxy.html

deque(maxlen=10)
来源：http://dali.jianghu66.top/Article/details/gtieenhzko.html

[U14] Py：分组收集到列表
来源：http://dali.zycfv.cn/Article/details/gtsmipshli.html

defaultdict(list)
来源：http://dali.feifeiyinyue.top/Article/details/gtsxwvsgmx.html

[U15] Py：高精度计时
来源：http://dali.xuetiantiany.cn/Article/details/gtzrauuios.html

t = time.perf_counter()
来源：http://dali.feifeiyinyue.top/Article/details/gtgsdwbjbg.html

[U16] Py：命令行参数解析
来源：http://dali.chenlongwang.top/Article/details/gtowizqruk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sufxvd.cn/Article/details/gtjxudgast.html

[U17] Py：初始化日志
来源：http://dali.yueranfly.top/Article/details/gtcdiabatn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfidrqbs.html

[U18] Py：预编译正则
来源：http://dali.yj20258888.top/Article/details/gttzuhrynm.html

pat = re.compile(r"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqfqmqgy.html

[U19] Py：正则替换带回调
来源：http://dali.yvedp.cn/Article/details/gtbrkianrv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenlongwang.top/Article/details/gtgctezudx.html

[U20] Py：缓存函数结果
来源：http://dali.haohaochexian.top/Article/details/gtsvizmasg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxuanxn.top/Article/details/gtirahbocd.html

[U21] Py：自定义上下文管理器
来源：http://dali.shzxlz.cn/Article/details/gtdbmejkyn.html

@contextlib.contextmanager
来源：http://dali.hongshengwenyu.top/Article/details/gtmfatkjsp.html

[U22] Py：矩阵转置
来源：http://dali.andypj.xyz/Article/details/gtakgvhuie.html

list(zip(*m))
来源：http://dali.yongpay.top/Article/details/gtvbpwboxz.html

[U23] Py：分块读取大文件
来源：http://dali.zhoulong.xyz/Article/details/gtxaskmema.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hongshengwenyu.top/Article/details/gtviarbevd.html

[U24] Py：路径操作
来源：http://dali.mhx1999.top/Article/details/gtyhwdswbx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gtpiruyzhz.html

[U25] Py：CSV 按字典读
来源：http://dali.zdqjudy.top/Article/details/gtbjcmauqw.html

csv.DictReader(f)
来源：http://dali.hysaishi.cn/Article/details/gtjrxgkwlt.html

[U26] Py：并发下载
来源：http://dali.9152youxi.cn/Article/details/gtygzmllig.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.aibaodan.cn/Article/details/gtgwdksiob.html

[U27] Py：异步 HTTP
来源：http://dali.dianchejie.cn/Article/details/gtqsnurcdn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hnqzz.top/Article/details/gttjmurnaj.html

[U28] Py：类型别名
来源：http://dali.dianchejie.cn/Article/details/gtgwdlymsd.html

UserId = int
来源：http://dali.birdmap.top/Article/details/gtezwiolqr.html


<!-- 参考信息 -->