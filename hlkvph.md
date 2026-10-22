代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guowangkeji.top/Article/details/gticnsgoml.html

[S08] C：动态内存分配与释放
来源：http://dali.hammf.cn/Article/details/gtavnegkqf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cqqwz.cn/Article/details/gtyqszlhsz.html

[S09] C：结构体定义与初始化
来源：http://dali.fzhhl.top/Article/details/gtrtiinjkp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gzhubu.top/Article/details/gtwfiboane.html

[S10] C：指针与解引用
来源：http://dali.tanke756.top/Article/details/gtngwlghud.html

int *p = &a;  *p = 5;
来源：http://dali.jianghu66.top/Article/details/gtcjbaujbf.html

[S11] C：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gthyvsqfbf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gotoacloud.top/Article/details/gtocrxvqgm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.kuanghao11.cn/Article/details/gtsxvhecup.html

fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gtdqqsxocy.html

[S12] C：写文件
来源：http://dali.daria6918.cn/Article/details/gtlaqdnfsd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gtatllajkv.html

[S13] C：宏定义
来源：http://dali.shuidangran.top/Article/details/gtmwalzggd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.svipenyu.cn/Article/details/gthxmxrltj.html

[S14] C：枚举
来源：http://dali.havefunace.top/Article/details/gtawwuknqc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkimnuzpy.html

[S15] C：类型转换
来源：http://dali.sufxvd.cn/Article/details/gtoxyppacg.html

(double) a / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtoakfqxyz.html

[S16] C：位操作置位
来源：http://dali.zdqjudy.top/Article/details/gtnkmeywuo.html

x |= (1 << 3);
来源：http://dali.sxryk.cn/Article/details/gtqgqxdztu.html

[S17] C：安全拼接字符串
来源：http://dali.bjfxy.top/Article/details/gthzqohjnf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.iojbl.cn/Article/details/gtkrvzqtec.html

[S18] C：命令行参数
来源：http://dali.sxryk.cn/Article/details/gturfzqskl.html

int main(int argc, char **argv)
来源：http://dali.svipenyu.cn/Article/details/gttqiqurrx.html

[S19] C：快速排序
来源：http://dali.chenlongwang.top/Article/details/gtozyrytlv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gtnrnvnull.html

[S20] C：二分查找
来源：http://dali.ehwqpu.com/Article/details/gtsraqpbaz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gtqaqlnwzx.html

[S21] C：字符类别判断
来源：http://dali.aibaodan.cn/Article/details/gtarhehjiu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sweek.top/Article/details/gtzpxcfwly.html

[S22] C：字符串转数字
来源：http://dali.nanxuanxn.top/Article/details/gthnxadaof.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fzhhl.top/Article/details/gticdmpcsu.html

[S23] C：随机数
来源：http://dali.daxiang520.top/Article/details/gtkfyhzmks.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cucudq.cn/Article/details/gtphpiindf.html

[S24] C：获取本地时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwukjmvmd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.haohaochexian.top/Article/details/gtnmqhrouh.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpwobedn.html

memcpy(dst, src, n);
来源：http://dali.yj20258888.top/Article/details/gtwfsmwojs.html

[S26] C：内存清零
来源：http://dali.yangfankeji.com/Article/details/gtpnhpuedn.html

memset(a, 0, sizeof a);
来源：http://dali.zhengqikj.top/Article/details/gtmozhqcct.html

[S27] C：定义常量
来源：http://dali.yvedp.cn/Article/details/gtmqkxnicr.html

const double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtvrfrowxl.html

[S28] C：静态变量
来源：http://dali.guannengcc.top/Article/details/gtvjrtjcgn.html

static int counter = 0;
来源：http://dali.zhongyouzk.top/Article/details/gtkeskctpu.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gtanzqtulh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cashguo.top/Article/details/gtgpmqecqi.html

[S30] C：头文件保护
来源：http://dali.hywenlv.cn/Article/details/gtyxmnlncc.html

#ifndef X_H
来源：http://dali.yueranfly.top/Article/details/gtassurwbn.html

#define X_H
来源：http://dali.jiagoushi.top/Article/details/gtdiocimsv.html

#endif
来源：http://dali.shangyingyoupin.top/Article/details/gtocciapky.html

[S31] C++：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtywggaotg.html

#include <iostream>
来源：http://dali.hywenlv.cn/Article/details/gtpotqtdsx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.kuanghao11.cn/Article/details/gtggjqsugp.html

[S32] C++：字符串
来源：http://dali.andypj.xyz/Article/details/gtdsfaeodu.html

std::string s = "hi";  s += "!";
来源：http://dali.hongshengwenyu.top/Article/details/gtgdmzpwla.html

[S33] C++：vector 增删
来源：http://dali.fzhhl.top/Article/details/gtusykfxnr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hysaishi.cn/Article/details/gtoapclqdz.html

[S34] C++：遍历 vector
来源：http://dali.bjfxy.top/Article/details/gtinlzobse.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqyhdevl.html

[S35] C++：map
来源：http://dali.mhx1999.top/Article/details/gtkbnaoqje.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gtuwhbygah.html

[S36] C++：unordered_map
来源：http://dali.feifeiyinyue.top/Article/details/gthphrhism.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtykpvaand.html

[S37] C++：set
来源：http://dali.sxryk.cn/Article/details/gthqvzchgf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgntkdipe.html

[S38] C++：排序
来源：http://dali.0kj1m.cn/Article/details/gtvqpfvdbh.html

std::sort(v.begin(), v.end());
来源：http://dali.daria6918.cn/Article/details/gtbtvbcaxy.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258888.top/Article/details/gtqxygkxar.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqmuospj.html

[S40] C++：查找元素
来源：http://dali.snrcjt.cn/Article/details/gtuklqgwft.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jianghu66.top/Article/details/gtcklurqyv.html

[S41] C++：类与构造函数
来源：http://dali.gzhubu.top/Article/details/gthjqrnvvs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cashguo.top/Article/details/gteouukszs.html

[S42] C++：继承与虚函数
来源：http://dali.hongshengwenyu.top/Article/details/gtwpgipmrh.html

class B : public Base { public: void f() override {} };
来源：http://dali.guowangkeji.top/Article/details/gtarzoednw.html

[S43] C++：智能指针
来源：http://dali.zhoulong.xyz/Article/details/gtzbzelnau.html

auto p = std::make_unique<int>(5);
来源：http://dali.sxryk.cn/Article/details/gtaqzvlxeh.html

[S44] C++：引用传参
来源：http://dali.xinyue.icu/Article/details/gtccgqyflu.html

void inc(int &x) { ++x; }
来源：http://dali.fengsongda.top/Article/details/gtftfsgqmr.html

[S45] C++：lambda
来源：http://dali.yj20258888.top/Article/details/gtdlhnwsnu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.birdmap.top/Article/details/gttqaeseij.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gtgudutild.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yanxiufei.cn/Article/details/gtbduxijma.html

[S47] C++：结构化绑定遍历
来源：http://dali.ehwqpu.com/Article/details/gtljmssklu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shangyingyoupin.top/Article/details/gtebaedrig.html

[S48] C++：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtmafvpusj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pengpengdd.cyou/Article/details/gtnepqfazw.html

while (std::getline(in, line)) { }
来源：http://dali.hfpthk.cn/Article/details/gtbcwkwcpk.html

[S49] C++：写文件
来源：http://dali.nanxinkj.top/Article/details/gtvhsunhph.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigufen.top/Article/details/gtznwmmdwf.html

[S50] C++：格式化数字
来源：http://dali.0kj1m.cn/Article/details/gtodpxvmgn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtkjejyirz.html

[S51] C++：显式类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgdmjfuk.html

static_cast<double>(a) / b
来源：http://dali.wangdashe.top/Article/details/gtddyoiqac.html

[S52] C++：const 与 noexcept
来源：http://dali.daria6918.cn/Article/details/gtrzrlyzqf.html

int size() const noexcept { return n_; }
来源：http://dali.ehwqpu.com/Article/details/gtblueiidz.html

[S53] C++：移动语义
来源：http://dali.hywenlv.cn/Article/details/gtossiuliv.html

std::vector<int> w = std::move(v);
来源：http://dali.yanxiufei.cn/Article/details/gtgxkvnibp.html

[S54] C++：异常处理
来源：http://dali.zycfv.cn/Article/details/gtsneqalrh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqggrzmp.html

[S55] C++：结构化绑定
来源：http://dali.mhx1999.top/Article/details/gtmzffhnic.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.0kj1m.cn/Article/details/gtznthpkhs.html

[S56] C++：optional
来源：http://dali.ydzc1.top/Article/details/gtetjskaea.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvybmdiro.html

[S57] C++：编译期常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbmstiyg.html

constexpr int N = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtjeesbzro.html

[S58] C++：命名空间
来源：http://dali.zycfv.cn/Article/details/gtfqzkwyay.html

namespace ns { int f() { return 1; } }
来源：http://dali.svipenyu.cn/Article/details/gtworvktld.html

[S59] C++：静态断言
来源：http://dali.wangdashe.top/Article/details/gtewxpuvph.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hfpthk.cn/Article/details/gttkozofhe.html

[S60] C++：遍历并删除元素
来源：http://dali.pycfn.com/Article/details/gtmuxkgbbr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guannengcc.top/Article/details/gtfxpxelce.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrxdavjo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258.top/Article/details/gtxqzeiozx.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtlfnyprqo.html

[T01] Kotlin：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibzjsice.html

println("Hello")
来源：http://dali.hfpthk.cn/Article/details/gtlrsvgwnw.html

[T02] Kotlin：变量
来源：http://dali.9152youxi.cn/Article/details/gtfoeduylb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sufxvd.cn/Article/details/gtoeogrcct.html

[T03] Kotlin：字符串模板
来源：http://dali.shangyingyoupin.top/Article/details/gtoiagfukn.html

"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gtgluumzhq.html

[T04] Kotlin：空安全
来源：http://dali.chenlongwang.top/Article/details/gtypfpnjgf.html

val n: String? = null;  n?.length
来源：http://dali.0kj1m.cn/Article/details/gthgdczxpr.html

[T05] Kotlin：when 表达式
来源：http://dali.dashuyun.cn/Article/details/gtvijaykml.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuxming.cn/Article/details/gtltsmxpye.html

[T06] Kotlin：集合映射
来源：http://dali.daxiang520.top/Article/details/gtcqislmbj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtsmfzlaio.html

[T07] Kotlin：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gtgzwmojif.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhengqikj.top/Article/details/gtabytiyzr.html

[T08] Kotlin：数据类
来源：http://dali.haohaochexian.top/Article/details/gtsnmfxoku.html

data class User(val name: String, val age: Int)
来源：http://dali.shuidangran.top/Article/details/gttgirbpru.html

[T09] Kotlin：扩展函数
来源：http://dali.pycfn.com/Article/details/gtodxbmedb.html

fun String.exclaim() = this + "!"
来源：http://dali.hfpthk.cn/Article/details/gtprreyvfk.html

[T10] Kotlin：默认参数
来源：http://dali.gotoacloud.top/Article/details/gtczjnjjcm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.haohaochexian.top/Article/details/gtukhdrdte.html

[T11] Kotlin：协程
来源：http://dali.xuanzx.com/Article/details/gtqomrhrrn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tanke756.top/Article/details/gtiajywihc.html

[T12] Kotlin：解构声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskagvvfh.html

val (a, b) = Pair(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtwvilgtkf.html

[T13] Kotlin：只读 Map
来源：http://dali.sysykeji.top/Article/details/gtxbybvozy.html

val m = mapOf("a" to 1)
来源：http://dali.redwolf501.top/Article/details/gtyghlfqmr.html

[T14] Kotlin：循环
来源：http://dali.yonumen.top/Article/details/gtptvuqdfi.html

for (i in 1..10) println(i)
来源：http://dali.quarkkingdee.top/Article/details/gtbhozlibv.html

[T15] Kotlin：接口
来源：http://dali.jianghu66.top/Article/details/gthrexeejm.html

interface Shape { fun area(): Double }
来源：http://dali.xylfe.cn/Article/details/gtbfvhgiqt.html

[T16] Swift：Hello World
来源：http://dali.yj20258888.top/Article/details/gtutjeagix.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtstvsohdf.html

[T17] Swift：变量与常量
来源：http://dali.nanxuanxn.top/Article/details/gtynspfevm.html

var a = 1;  let b = 2
来源：http://dali.iojbl.cn/Article/details/gtsrzwjzgz.html

[T18] Swift：字符串插值
来源：http://dali.birdmap.top/Article/details/gtsppwdnkt.html

"值: \(b)"
来源：http://dali.yvedp.cn/Article/details/gtndzadcsn.html

[T19] Swift：可选绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtowxwczvz.html

if let n = opt { print(n) }
来源：http://dali.ivvv.top/Article/details/gtvjjmkosc.html

[T20] Swift：数组操作
来源：http://dali.sweek.top/Article/details/gtgpfkakdk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daxiang520.top/Article/details/gtrlpqxpma.html

[T21] Swift：遍历
来源：http://dali.tianlin.xyz/Article/details/gtkmmmlbod.html

for x in a { print(x) }
来源：http://dali.wangshuangyany.cn/Article/details/gtaksllnag.html

[T22] Swift：字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcmgipdm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ppjwa.cn/Article/details/gtvnisusoo.html

[T23] Swift：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzudmmfxp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zdqjudy.top/Article/details/gtyahcbdin.html

[T24] Swift：闭包
来源：http://dali.iojbl.cn/Article/details/gtjnkeeucr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtybbwzttm.html

[T25] Swift：结构体
来源：http://dali.shuidangran.top/Article/details/gtzcumldbf.html

struct P { var x: Int }
来源：http://dali.yanxiufei.cn/Article/details/gteryshtdg.html

[T26] Swift：类与重写
来源：http://dali.ppjwa.cn/Article/details/gtbcyrmdqg.html

class A: Base { override func f() {} }
来源：http://dali.svipenyu.cn/Article/details/gtcgczdtaw.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqllamul.html

do { try f() } catch { print(error) }
来源：http://dali.gaohongyu789.top/Article/details/gtlcdgfvjr.html

[T28] Swift：枚举
来源：http://dali.cdnleiting.top/Article/details/gtiflktgdu.html

enum Color { case red, green }
来源：http://dali.gaohongyu789.top/Article/details/gtozbhcord.html

[T29] Swift：guard 提前返回
来源：http://dali.ehwqpu.com/Article/details/gtupgitauq.html

guard let x = opt else { return }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrwwtbtc.html

[T30] Swift：协议
来源：http://dali.shangyingyoupin.top/Article/details/gtpzdkdeqt.html

protocol Shape { func area() -> Double }
来源：http://dali.ppjwa.cn/Article/details/gtwwjkyftg.html

[T31] Lua：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtpofwvbjm.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtqrbaonym.html

[T32] Lua：局部变量
来源：http://dali.0kj1m.cn/Article/details/gthwlcvnqw.html

local a = 1
来源：http://dali.hywenlv.cn/Article/details/gthvxakbou.html

[T33] Lua：表（数组）
来源：http://dali.zhixingplan.top/Article/details/gtsrjiiohz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonhrwzpe.html

[T34] Lua：遍历表
来源：http://dali.cucudq.cn/Article/details/gtrzsctflg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gzhubu.top/Article/details/gtprtqsria.html

[T35] Lua：字典表
来源：http://dali.yj20258888.top/Article/details/gtqaqzufxh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.birdmap.top/Article/details/gtegvghbyb.html

[T36] Lua：函数
来源：http://dali.jyoumei.cn/Article/details/gtijsyddgq.html

function add(a, b) return a + b end
来源：http://dali.dianchejie.cn/Article/details/gttpngeuxc.html

[T37] Lua：字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gtdrkkoglo.html

"a" .. "b"
来源：http://dali.fzhhl.top/Article/details/gtsqzdrmvu.html

[T38] Lua：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtuigtfhvx.html

if x > 0 then print("正") end
来源：http://dali.cdnleiting.top/Article/details/gtmzpbnfxw.html

[T39] Lua：模式匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtqplwawqc.html

string.find(s, "%d+")
来源：http://dali.chenlongwang.top/Article/details/gtcszcnivi.html

[T40] Lua：元表
来源：http://dali.cucudq.cn/Article/details/gtgsbaujez.html

setmetatable({}, { __index = base })
来源：http://dali.snrcjt.cn/Article/details/gtaqjlqgdi.html

[T41] Perl：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtmrjixxha.html

print "Hello\n";
来源：http://dali.yvedp.cn/Article/details/gtzujsainy.html

[T42] Perl：变量类型
来源：http://dali.hnxiangtu.top/Article/details/gtlehqzoko.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.kuanghao11.cn/Article/details/gtstttekmc.html

[T43] Perl：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gtfxwsoepv.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gtmkzbakhp.html

[T44] Perl：条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtarfbvqrq.html

if ($a > 0) { print "正"; }
来源：http://dali.shzxlz.cn/Article/details/gtspmzceeb.html

[T45] Perl：数组遍历
来源：http://dali.ybcxt.top/Article/details/gtubwcahnu.html

for my $x (@arr) { print $x; }
来源：http://dali.smart0.xyz/Article/details/gtrfagurpd.html

[T46] Perl：哈希操作
来源：http://dali.daxiang520.top/Article/details/gtylovhuhp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tianlin.xyz/Article/details/gtusjctuqd.html

[T47] Perl：正则捕获
来源：http://dali.snrcjt.cn/Article/details/gtucqcynls.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gaohongyu789.top/Article/details/gtjatyeorl.html

[T48] Perl：正则替换
来源：http://dali.ppjwa.cn/Article/details/gtfrvgkqqp.html

$s =~ s/old/new/g;
来源：http://dali.jyoumei.cn/Article/details/gtlfxkdyjz.html

[T49] Perl：函数
来源：http://dali.ydzc1.top/Article/details/gtiqccdstz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteurovpyn.html

[T50] Perl：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtdvdjyijs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.birdmap.top/Article/details/gtwbcpmfyq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sweek.top/Article/details/gtsobvplrg.html

[T51] Scala：Hello World
来源：http://dali.yongpay.top/Article/details/gtgumnbmiz.html

println("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtwtrbxxtc.html

[T52] Scala：变量
来源：http://dali.yvedp.cn/Article/details/gtedbbdegt.html

val a = 1;  var b = 2
来源：http://dali.svipenyu.cn/Article/details/gtgghcaeyn.html

[T53] Scala：字符串插值
来源：http://dali.meibo888.top/Article/details/gttwbtmhtl.html

s"值: $b"
来源：http://dali.yonumen.top/Article/details/gtmqszdhdb.html

[T54] Scala：集合映射
来源：http://dali.hfpthk.cn/Article/details/gtzafxlumw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.andypj.xyz/Article/details/gtjmipborz.html

[T55] Scala：集合过滤
来源：http://dali.redwolf501.top/Article/details/gtktyjfpwt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xuanzx.com/Article/details/gtxhumwinl.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gtdkttydar.html

case class User(name: String, age: Int)
来源：http://dali.zycfv.cn/Article/details/gtjtjxehmw.html

[T57] Scala：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gtpyssmanm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sxryk.cn/Article/details/gtobstytfh.html

[T58] Scala：函数定义
来源：http://dali.ydzc1.top/Article/details/gtkccbctsz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dianchejie.cn/Article/details/gtvifyqfzr.html

[T59] Scala：循环
来源：http://dali.dianchejie.cn/Article/details/gtceefzwaw.html

for (i <- 1 to 10) println(i)
来源：http://dali.316326.xyz/Article/details/gtpukevyii.html

[T60] Scala：折叠
来源：http://dali.daxiang520.top/Article/details/gtaacxkcbo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.quarkkingdee.top/Article/details/gtacjkohnv.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gthyyavjds.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xinyue.icu/Article/details/gtypprpcyf.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gthbvjizuh.html

[U01] Py：创建虚拟环境
来源：http://dali.yuxming.cn/Article/details/gttcgmuyqr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shangyingyoupin.top/Article/details/gtwdmolaka.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gttcbjobeh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sysykeji.top/Article/details/gtssavoyoi.html

[U03] Py：加载 .env 配置
来源：http://dali.shuidangran.top/Article/details/gtjjojskcy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jiagoushi.top/Article/details/gtwosbngog.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhbkbriv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ivvv.top/Article/details/gtajvjkxtg.html

[U05] Py：列表去重且保序
来源：http://dali.sufxvd.cn/Article/details/gtjprjzarc.html

list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gtopbtebht.html

[U06] Py：合并两个字典
来源：http://dali.cucudq.cn/Article/details/gtqtnjlash.html

{**a, **b}
来源：http://dali.dianchejie.cn/Article/details/gtgvxsndan.html

[U07] Py：反转字典键值
来源：http://dali.chenzaomai.com/Article/details/gtisxuayro.html

{v: k for k, v in d.items()}
来源：http://dali.cashguo.top/Article/details/gtdwkzjcfn.html

[U08] Py：展平二维列表
来源：http://dali.gotoacloud.top/Article/details/gtmouffdid.html

[y for x in nested for y in x]
来源：http://dali.tanke756.top/Article/details/gtqtrxrrsi.html

[U09] Py：字典取最大值的键
来源：http://dali.hfpthk.cn/Article/details/gtxwovyqbp.html

max(d, key=d.get)
来源：http://dali.sufxvd.cn/Article/details/gtrdtbsjyk.html

[U10] Py：按值排序字典
来源：http://dali.zycfv.cn/Article/details/gtrdryjzcs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.vqdsnc.cn/Article/details/gtesinudfm.html

[U11] Py：生成器表达式
来源：http://dali.tian-w.cn/Article/details/gtynaklpcb.html

(x * 2 for x in arr)
来源：http://dali.jqgufenzy.top/Article/details/gtzjmurpho.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqraegggx.html

Counter(arr).most_common(3)
来源：http://dali.9152youxi.cn/Article/details/gtvbcinnui.html

[U13] Py：固定长度队列
来源：http://dali.snrcjt.cn/Article/details/gtqxwdbffm.html

deque(maxlen=10)
来源：http://dali.xinyue.icu/Article/details/gtcbludejk.html

[U14] Py：分组收集到列表
来源：http://dali.dianchejie.cn/Article/details/gtihghapdo.html

defaultdict(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrihbqdpi.html

[U15] Py：高精度计时
来源：http://dali.jlsjyb.cn/Article/details/gtlvsxdzga.html

t = time.perf_counter()
来源：http://dali.quarkkingdee.top/Article/details/gtmorhtlex.html

[U16] Py：命令行参数解析
来源：http://dali.wangdashe.top/Article/details/gtbtaxqhqe.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.bjfxy.top/Article/details/gtqvuaacbq.html

[U17] Py：初始化日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmasibho.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guannengcc.top/Article/details/gttgghupes.html

[U18] Py：预编译正则
来源：http://dali.cucudq.cn/Article/details/gtlxaxpznq.html

pat = re.compile(r"\d+")
来源：http://dali.dashuyun.cn/Article/details/gtpawxehax.html

[U19] Py：正则替换带回调
来源：http://dali.tian-w.cn/Article/details/gthgznycfq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hnxiangtu.top/Article/details/gtmxkhmixb.html

[U20] Py：缓存函数结果
来源：http://dali.xuanzx.com/Article/details/gtvpaornly.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hammf.cn/Article/details/gtmhrzjdzj.html

[U21] Py：自定义上下文管理器
来源：http://dali.cdnleiting.top/Article/details/gtiopkqgpi.html

@contextlib.contextmanager
来源：http://dali.yanxiufei.cn/Article/details/gtesblifqo.html

[U22] Py：矩阵转置
来源：http://dali.hywenlv.cn/Article/details/gtulcyvtvp.html

list(zip(*m))
来源：http://dali.9152youxi.cn/Article/details/gtaysjxkgi.html

[U23] Py：分块读取大文件
来源：http://dali.ivvv.top/Article/details/gtflbnwiin.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gogol.net.cn/Article/details/gtfoqbckrs.html

[U24] Py：路径操作
来源：http://dali.tianlin.xyz/Article/details/gtllpujmkn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.redwolf501.top/Article/details/gtbfpujwbj.html

[U25] Py：CSV 按字典读
来源：http://dali.guowangkeji.top/Article/details/gtwprxyixx.html

csv.DictReader(f)
来源：http://dali.jiagoushi.top/Article/details/gtfnliehvw.html

[U26] Py：并发下载
来源：http://dali.havefunace.top/Article/details/gthayvsosg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yongpay.top/Article/details/gtqnxutlet.html

[U27] Py：异步 HTTP
来源：http://dali.gzhubu.top/Article/details/gtsdhcisal.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jianghu66.top/Article/details/gttezlkpwt.html

[U28] Py：类型别名
来源：http://dali.gzhubu.top/Article/details/gtclarqtaf.html

UserId = int
来源：http://dali.nanxuanxn.top/Article/details/gteunuzzor.html

[U29] Py：属性校验
来源：http://dali.ehwqpu.com/Article/details/gtqxiundee.html

@property 与 @x.setter 配合
来源：http://dali.hysaishi.cn/Article/details/gtsgdywvlh.html

[U30] Py：数据类
来源：http://dali.sysykeji.top/Article/details/gtxbovrnks.html

@dataclass(slots=True)
来源：http://dali.aizwys.cn/Article/details/gtakyixtkd.html


<!-- 参考信息 -->