代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fengsongda.top/Article/details/gtvtjsmqoa.html

[S08] C：动态内存分配与释放
来源：http://dali.chenlongwang.top/Article/details/gtyhknvnsb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fzhhl.top/Article/details/gtwsiiskkr.html

[S09] C：结构体定义与初始化
来源：http://dali.hammf.cn/Article/details/gtwcnwkypw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pengpengdd.cyou/Article/details/gtllfauhdq.html

[S10] C：指针与解引用
来源：http://dali.yj20258888.top/Article/details/gtysebikfy.html

int *p = &a;  *p = 5;
来源：http://dali.zhoulong.xyz/Article/details/gtndxugyjs.html

[S11] C：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtubskqcys.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.meibo888.top/Article/details/gteuvfctal.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jiagoushi.top/Article/details/gtjyxozzhk.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gtyerzntgt.html

[S12] C：写文件
来源：http://dali.cucudq.cn/Article/details/gtaxqvmbod.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.redwolf501.top/Article/details/gtuxiyvwif.html

[S13] C：宏定义
来源：http://dali.redwolf501.top/Article/details/gtasdifbxq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sxryk.cn/Article/details/gtnjnsspae.html

[S14] C：枚举
来源：http://dali.tanke756.top/Article/details/gtlnrmguzp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xylfe.cn/Article/details/gtvnxtbmke.html

[S15] C：类型转换
来源：http://dali.kuanghao11.cn/Article/details/gteduxodgi.html

(double) a / b
来源：http://dali.hongshengwenyu.top/Article/details/gtnbjabqzo.html

[S16] C：位操作置位
来源：http://dali.xylfe.cn/Article/details/gtzecvjntx.html

x |= (1 << 3);
来源：http://dali.tianlin.xyz/Article/details/gtbksrcwqw.html

[S17] C：安全拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtyphlhlue.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.svipenyu.cn/Article/details/gtfcijhmlf.html

[S18] C：命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gtvbrtwboq.html

int main(int argc, char **argv)
来源：http://dali.dashuyun.cn/Article/details/gtemvdgeuf.html

[S19] C：快速排序
来源：http://dali.gzhubu.top/Article/details/gtzugxijzj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtquhzfgqc.html

[S20] C：二分查找
来源：http://dali.jinqigfzy.top/Article/details/gtikljggjd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gthejygnkx.html

[S21] C：字符类别判断
来源：http://dali.fzhhl.top/Article/details/gtjkihktco.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnqzz.top/Article/details/gtijiweipc.html

[S22] C：字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gtlrmstqtw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.haohaochexian.top/Article/details/gtynfepkaf.html

[S23] C：随机数
来源：http://dali.tian-w.cn/Article/details/gtkfvqwyor.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhiwuduotai.top/Article/details/gtbhweyklz.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gtdyadfurc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.feifeiyinyue.top/Article/details/gtvleqwouu.html

[S25] C：内存拷贝
来源：http://dali.yvedp.cn/Article/details/gtqhtyrvyh.html

memcpy(dst, src, n);
来源：http://dali.cqqwz.cn/Article/details/gtioddqfao.html

[S26] C：内存清零
来源：http://dali.ydzc1.top/Article/details/gtcddtipij.html

memset(a, 0, sizeof a);
来源：http://dali.birdmap.top/Article/details/gtzwjdmsnt.html

[S27] C：定义常量
来源：http://dali.guannengcc.top/Article/details/gtnjotiokg.html

const double PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtvxgaxbek.html

[S28] C：静态变量
来源：http://dali.cheryme.top/Article/details/gtktcrgggq.html

static int counter = 0;
来源：http://dali.quarkkingdee.top/Article/details/gtohtfdhem.html

[S29] C：变参函数
来源：http://dali.shuidangran.top/Article/details/gtvxobqwkw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hywenlv.cn/Article/details/gtsfaqsbov.html

[S30] C：头文件保护
来源：http://dali.sxryk.cn/Article/details/gtgphowvaz.html

#ifndef X_H
来源：http://dali.shangyingyoupin.top/Article/details/gtcabxxvwl.html

#define X_H
来源：http://dali.fengsongda.top/Article/details/gtqxbheadp.html

#endif
来源：http://dali.fzhhl.top/Article/details/gtmishiqfu.html

[S31] C++：Hello World
来源：http://dali.sweek.top/Article/details/gtdjjgpuor.html

#include <iostream>
来源：http://dali.hysaishi.cn/Article/details/gtuamnlksn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yangfankeji.com/Article/details/gtjgertrcn.html

[S32] C++：字符串
来源：http://dali.tanke756.top/Article/details/gtlkajgsya.html

std::string s = "hi";  s += "!";
来源：http://dali.xinyue.icu/Article/details/gtwrfyibjz.html

[S33] C++：vector 增删
来源：http://dali.0kj1m.cn/Article/details/gthrcoeyki.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigufen.top/Article/details/gtrzxfutmw.html

[S34] C++：遍历 vector
来源：http://dali.yueranfly.top/Article/details/gttkwsqljw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigufen.top/Article/details/gtgdccylrj.html

[S35] C++：map
来源：http://dali.hongshengwenyu.top/Article/details/gtqtnienth.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtznryssjk.html

[S36] C++：unordered_map
来源：http://dali.zhiwuduotai.top/Article/details/gtavrzlcqf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzfunjjh.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gteknsncde.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenzaomai.com/Article/details/gtmeruxyyf.html

[S38] C++：排序
来源：http://dali.shangyingyoupin.top/Article/details/gtrjgnngcm.html

std::sort(v.begin(), v.end());
来源：http://dali.daria6918.cn/Article/details/gtvzmdkhgw.html

[S39] C++：自定义比较器排序
来源：http://dali.0kj1m.cn/Article/details/gtizwhihqr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shzxlz.cn/Article/details/gtslhnweiq.html

[S40] C++：查找元素
来源：http://dali.meibo888.top/Article/details/gtowelsfmo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nwbrower.top/Article/details/gtymuszfbv.html

[S41] C++：类与构造函数
来源：http://dali.zycfv.cn/Article/details/gtqzjoltdc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.feifeiyinyue.top/Article/details/gtcoscduem.html

[S42] C++：继承与虚函数
来源：http://dali.ydzc1.top/Article/details/gtyemhxrrb.html

class B : public Base { public: void f() override {} };
来源：http://dali.guannengcc.top/Article/details/gthhoordtc.html

[S43] C++：智能指针
来源：http://dali.ydzc1.top/Article/details/gtjdjelahy.html

auto p = std::make_unique<int>(5);
来源：http://dali.daxiang520.top/Article/details/gtlfmciijf.html

[S44] C++：引用传参
来源：http://dali.cucudq.cn/Article/details/gtwofnypjb.html

void inc(int &x) { ++x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkvbjiwrr.html

[S45] C++：lambda
来源：http://dali.gogol.net.cn/Article/details/gtjwejpyhj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhongyouzk.top/Article/details/gtwhdwqwmc.html

[S46] C++：函数模板
来源：http://dali.daria6918.cn/Article/details/gtthgrcygn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.snrcjt.cn/Article/details/gthqfxcmvg.html

[S47] C++：结构化绑定遍历
来源：http://dali.cqqwz.cn/Article/details/gtzebfltvb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhiwuduotai.top/Article/details/gtsuhdvqzp.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtuoakqxcz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pycfn.com/Article/details/gtsjwvbzpl.html

while (std::getline(in, line)) { }
来源：http://dali.xinyue.icu/Article/details/gtzymxqdsm.html

[S49] C++：写文件
来源：http://dali.shzxlz.cn/Article/details/gtvtvkxxkx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjzqvrvi.html

[S50] C++：格式化数字
来源：http://dali.cqqwz.cn/Article/details/gtrvcjqpkr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.birdmap.top/Article/details/gtjxdzdpac.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtiazfwcns.html

static_cast<double>(a) / b
来源：http://dali.fengsongda.top/Article/details/gtuehgqprc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhixingplan.top/Article/details/gtivolkvix.html

int size() const noexcept { return n_; }
来源：http://dali.jqgufenzy.top/Article/details/gtjdefvehg.html

[S53] C++：移动语义
来源：http://dali.smart0.xyz/Article/details/gtpgldleep.html

std::vector<int> w = std::move(v);
来源：http://dali.hongshengwenyu.top/Article/details/gtdatghvpg.html

[S54] C++：异常处理
来源：http://dali.dashuyun.cn/Article/details/gtcrxmviqh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258888.top/Article/details/gtjmvklrcu.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gthvrrogjn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgfzy.top/Article/details/gtsknviuvo.html

[S56] C++：optional
来源：http://dali.yongpay.top/Article/details/gtdzuqiitk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gogol.net.cn/Article/details/gtoqimvcmy.html

[S57] C++：编译期常量
来源：http://dali.quarkkingdee.top/Article/details/gtbogufxhk.html

constexpr int N = 10;
来源：http://dali.zycfv.cn/Article/details/gtgbewzrqr.html

[S58] C++：命名空间
来源：http://dali.iojbl.cn/Article/details/gtvecniynf.html

namespace ns { int f() { return 1; } }
来源：http://dali.daxiang520.top/Article/details/gtihduscfm.html

[S59] C++：静态断言
来源：http://dali.xuetiantiany.cn/Article/details/gtwbwjkrnw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenzaomai.com/Article/details/gtqwfgupdq.html

[S60] C++：遍历并删除元素
来源：http://dali.hnqzz.top/Article/details/gtrjrahxwd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sufxvd.cn/Article/details/gtuhycaxda.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtvodmrdjc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sxryk.cn/Article/details/gtqxkiarkt.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtlobpvltl.html

[T01] Kotlin：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtybzscfab.html

println("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtbphakjvf.html

[T02] Kotlin：变量
来源：http://dali.xziqi.cn/Article/details/gtbltjwkfb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xziqi.cn/Article/details/gtgxuwooyk.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangtech.top/Article/details/gtnovnraiy.html

"值: $b"
来源：http://dali.dianchejie.cn/Article/details/gtfzhvbmsl.html

[T04] Kotlin：空安全
来源：http://dali.ybcxt.top/Article/details/gttqegmtlk.html

val n: String? = null;  n?.length
来源：http://dali.quarkkingdee.top/Article/details/gtyumnzouj.html

[T05] Kotlin：when 表达式
来源：http://dali.jlsjyb.cn/Article/details/gtiwhmhwze.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhiwuduotai.top/Article/details/gtbqcjudvt.html

[T06] Kotlin：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gthzybfbde.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtioogvofh.html

[T07] Kotlin：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gtiqyvnzzz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aizwys.cn/Article/details/gtpqmmdebr.html

[T08] Kotlin：数据类
来源：http://dali.cqqwz.cn/Article/details/gtopuizvdl.html

data class User(val name: String, val age: Int)
来源：http://dali.fzhhl.top/Article/details/gttllihxwg.html

[T09] Kotlin：扩展函数
来源：http://dali.yueranfly.top/Article/details/gtnmqwenxd.html

fun String.exclaim() = this + "!"
来源：http://dali.feifeiyinyue.top/Article/details/gtivcrbbfo.html

[T10] Kotlin：默认参数
来源：http://dali.chenjidiqi.icu/Article/details/gtvnvoepay.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ehwqpu.com/Article/details/gtjghuzcuy.html

[T11] Kotlin：协程
来源：http://dali.tianlin.xyz/Article/details/gttqqxrdfg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daria6918.cn/Article/details/gtuxmwsusl.html

[T12] Kotlin：解构声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvmyjxlm.html

val (a, b) = Pair(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtpqlkgukr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhoulong.xyz/Article/details/gttuauwuta.html

val m = mapOf("a" to 1)
来源：http://dali.dashuyun.cn/Article/details/gtdjfhnjtz.html

[T14] Kotlin：循环
来源：http://dali.cucudq.cn/Article/details/gtuhwtuxlm.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gtwsdhdjul.html

[T15] Kotlin：接口
来源：http://dali.zhengqikj.top/Article/details/gtjjwmssnk.html

interface Shape { fun area(): Double }
来源：http://dali.jyoumei.cn/Article/details/gtiouwswij.html

[T16] Swift：Hello World
来源：http://dali.yj202588.top/Article/details/gtievooiis.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtjyxifpbn.html

[T17] Swift：变量与常量
来源：http://dali.nanxuanxn.top/Article/details/gtwlalpomg.html

var a = 1;  let b = 2
来源：http://dali.zdqjudy.top/Article/details/gtwhqqwqbv.html

[T18] Swift：字符串插值
来源：http://dali.fzhhl.top/Article/details/gtaunrlkia.html

"值: \(b)"
来源：http://dali.jianghu66.top/Article/details/gtwxxzopxh.html

[T19] Swift：可选绑定
来源：http://dali.zhongyouzk.top/Article/details/gtenebread.html

if let n = opt { print(n) }
来源：http://dali.gotoacloud.top/Article/details/gtqgimztjh.html

[T20] Swift：数组操作
来源：http://dali.yj20258.top/Article/details/gtjzzyjsxo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cheryme.top/Article/details/gtnhpmxzep.html

[T21] Swift：遍历
来源：http://dali.guowangkeji.top/Article/details/gtosrpgwio.html

for x in a { print(x) }
来源：http://dali.birdmap.top/Article/details/gtgmrzixmw.html

[T22] Swift：字典
来源：http://dali.shzxlz.cn/Article/details/gtfqxrokqm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sufxvd.cn/Article/details/gtuzsmgvow.html

[T23] Swift：函数
来源：http://dali.quarkkingdee.top/Article/details/gtrckrgeju.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daria6918.cn/Article/details/gtvgrxpesp.html

[T24] Swift：闭包
来源：http://dali.dashuyun.cn/Article/details/gtdrrvuzmn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtmdwrniik.html

[T25] Swift：结构体
来源：http://dali.chenzaomai.com/Article/details/gtuuojxdwv.html

struct P { var x: Int }
来源：http://dali.snrcjt.cn/Article/details/gtjjgozwoc.html

[T26] Swift：类与重写
来源：http://dali.c1oappe.top/Article/details/gtvzaryiwa.html

class A: Base { override func f() {} }
来源：http://dali.svipenyu.cn/Article/details/gttibmvggv.html

[T27] Swift：错误处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoovfqnjm.html

do { try f() } catch { print(error) }
来源：http://dali.wangdashe.top/Article/details/gteqqnaoix.html

[T28] Swift：枚举
来源：http://dali.cheryme.top/Article/details/gtrnreimkz.html

enum Color { case red, green }
来源：http://dali.sxryk.cn/Article/details/gtriaoblej.html

[T29] Swift：guard 提前返回
来源：http://dali.haohaochexian.top/Article/details/gtuznjlihr.html

guard let x = opt else { return }
来源：http://dali.shangyingyoupin.top/Article/details/gtdcrszwjt.html

[T30] Swift：协议
来源：http://dali.svipenyu.cn/Article/details/gtcpzovkwp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugijxkyx.html

[T31] Lua：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtqgwazdbn.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtnkwmouem.html

[T32] Lua：局部变量
来源：http://dali.sweek.top/Article/details/gtqypouddq.html

local a = 1
来源：http://dali.ehwqpu.com/Article/details/gthppknjls.html

[T33] Lua：表（数组）
来源：http://dali.yj202588.top/Article/details/gtazyhmwzy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sufxvd.cn/Article/details/gthptwkcrl.html

[T34] Lua：遍历表
来源：http://dali.hywenlv.cn/Article/details/gtutgjrsxy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yj20258888.top/Article/details/gtqtkhaawb.html

[T35] Lua：字典表
来源：http://dali.hongshengwenyu.top/Article/details/gtkxwwmuns.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nwbrower.top/Article/details/gtnpffwjbu.html

[T36] Lua：函数
来源：http://dali.svipenyu.cn/Article/details/gtqibyisqc.html

function add(a, b) return a + b end
来源：http://dali.tianlin.xyz/Article/details/gtupnbnjrd.html

[T37] Lua：字符串拼接
来源：http://dali.iojbl.cn/Article/details/gtxcmcnqno.html

"a" .. "b"
来源：http://dali.shangyingyoupin.top/Article/details/gtwetjobhc.html

[T38] Lua：条件
来源：http://dali.xinyue.icu/Article/details/gtwqplzskk.html

if x > 0 then print("正") end
来源：http://dali.hfpthk.cn/Article/details/gtkzoihjnk.html

[T39] Lua：模式匹配
来源：http://dali.jianghu66.top/Article/details/gtxjlovgyz.html

string.find(s, "%d+")
来源：http://dali.gotoacloud.top/Article/details/gtmnhikpec.html

[T40] Lua：元表
来源：http://dali.xuanzx.com/Article/details/gthjrlyuzk.html

setmetatable({}, { __index = base })
来源：http://dali.birdmap.top/Article/details/gtbekjzzvu.html

[T41] Perl：Hello World
来源：http://dali.ppjwa.cn/Article/details/gttvmrntto.html

print "Hello\n";
来源：http://dali.pycfn.com/Article/details/gtkowbzoof.html

[T42] Perl：变量类型
来源：http://dali.daxiang520.top/Article/details/gtirzoxjvw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhiwuduotai.top/Article/details/gtnettkwtq.html

[T43] Perl：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtjsfytzzm.html

"值: $a"
来源：http://dali.aibaodan.cn/Article/details/gtmnejjeqx.html

[T44] Perl：条件
来源：http://dali.chenzaomai.com/Article/details/gtbuqoclld.html

if ($a > 0) { print "正"; }
来源：http://dali.yuxming.cn/Article/details/gtjnxchqmo.html

[T45] Perl：数组遍历
来源：http://dali.tianlin.xyz/Article/details/gtohhjahpp.html

for my $x (@arr) { print $x; }
来源：http://dali.yuanzhike.top/Article/details/gthyxrxoqx.html

[T46] Perl：哈希操作
来源：http://dali.sweek.top/Article/details/gtympmeacy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.quarkkingdee.top/Article/details/gtnlbjzpia.html

[T47] Perl：正则捕获
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfeisbldy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hysaishi.cn/Article/details/gtldnjyecd.html

[T48] Perl：正则替换
来源：http://dali.cucudq.cn/Article/details/gtihpkbnrv.html

$s =~ s/old/new/g;
来源：http://dali.wangdashe.top/Article/details/gtqijxlmwl.html

[T49] Perl：函数
来源：http://dali.jyoumei.cn/Article/details/gtaigaifmb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumfxesse.html

[T50] Perl：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtkjweptwa.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.smart0.xyz/Article/details/gtvusypiur.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jianghu66.top/Article/details/gtzilshxwr.html

[T51] Scala：Hello World
来源：http://dali.redwolf501.top/Article/details/gtfziadscd.html

println("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtwsmtfbwb.html

[T52] Scala：变量
来源：http://dali.hongshengwenyu.top/Article/details/gtjpiwyapp.html

val a = 1;  var b = 2
来源：http://dali.gzhubu.top/Article/details/gtiximhapd.html

[T53] Scala：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtbgnellnn.html

s"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gtvumqcyek.html

[T54] Scala：集合映射
来源：http://dali.0kj1m.cn/Article/details/gtmjtlhtle.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.meibo888.top/Article/details/gtkmxhfwcu.html

[T55] Scala：集合过滤
来源：http://dali.jianghu66.top/Article/details/gtkoanjdhl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zdqjudy.top/Article/details/gtcopcencn.html

[T56] Scala：样例类
来源：http://dali.hfpthk.cn/Article/details/gtxnmgwops.html

case class User(name: String, age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxinunla.html

[T57] Scala：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gtliaolofz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jlsjyb.cn/Article/details/gtdoidzzku.html

[T58] Scala：函数定义
来源：http://dali.c1oappe.top/Article/details/gtkntrlorb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.bjfxy.top/Article/details/gtpbiuavrv.html

[T59] Scala：循环
来源：http://dali.ybcxt.top/Article/details/gtrrnxctfi.html

for (i <- 1 to 10) println(i)
来源：http://dali.yuanzhike.top/Article/details/gtsasmqaqk.html

[T60] Scala：折叠
来源：http://dali.zycfv.cn/Article/details/gtrwzqabep.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuanzx.com/Article/details/gtockkzdqf.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtlwwcqulz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtnzjgaazy.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtfluuqoah.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigfzy.top/Article/details/gthxykxcol.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jqgufenzy.top/Article/details/gtoslqrscv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gtejaolyti.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gtxamqhcdg.html

[U03] Py：加载 .env 配置
来源：http://dali.hnqzz.top/Article/details/gtyrsbjxzv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxinkj.top/Article/details/gtldfajnuj.html

[U04] Py：变量调试打印
来源：http://dali.wangdashe.top/Article/details/gtqyczirpx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yueranfly.top/Article/details/gtkjxmjqds.html

[U05] Py：列表去重且保序
来源：http://dali.xuanzx.com/Article/details/gtfdxnskwr.html

list(dict.fromkeys(arr))
来源：http://dali.havefunace.top/Article/details/gtxyctrwsg.html

[U06] Py：合并两个字典
来源：http://dali.cashguo.top/Article/details/gtvbdxthsz.html

{**a, **b}
来源：http://dali.tianlin.xyz/Article/details/gtslqjocvy.html

[U07] Py：反转字典键值
来源：http://dali.hammf.cn/Article/details/gtgppwusep.html

{v: k for k, v in d.items()}
来源：http://dali.vqdsnc.cn/Article/details/gtjpfpwcmg.html

[U08] Py：展平二维列表
来源：http://dali.guowangkeji.top/Article/details/gttwhgxhql.html

[y for x in nested for y in x]
来源：http://dali.fengsongda.top/Article/details/gttfipysua.html

[U09] Py：字典取最大值的键
来源：http://dali.fengsongda.top/Article/details/gtulykgers.html

max(d, key=d.get)
来源：http://dali.gogol.net.cn/Article/details/gtptjalpfp.html

[U10] Py：按值排序字典
来源：http://dali.tanke756.top/Article/details/gtxjsggdhc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yvedp.cn/Article/details/gtnqehygph.html

[U11] Py：生成器表达式
来源：http://dali.zycfv.cn/Article/details/gtrvsdawhw.html

(x * 2 for x in arr)
来源：http://dali.ivvv.top/Article/details/gtoxnjktgt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sufxvd.cn/Article/details/gtuzuiqulm.html

Counter(arr).most_common(3)
来源：http://dali.9152youxi.cn/Article/details/gtiokkfrjf.html

[U13] Py：固定长度队列
来源：http://dali.cashguo.top/Article/details/gtjgcnhorb.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gthswvlgqm.html

[U14] Py：分组收集到列表
来源：http://dali.9152youxi.cn/Article/details/gtmjgxwvlr.html

defaultdict(list)
来源：http://dali.snrcjt.cn/Article/details/gteglfxkix.html

[U15] Py：高精度计时
来源：http://dali.svipenyu.cn/Article/details/gthuflmssm.html

t = time.perf_counter()
来源：http://dali.chenlongwang.top/Article/details/gtqnibxtec.html

[U16] Py：命令行参数解析
来源：http://dali.sufxvd.cn/Article/details/gtvcbhhbhv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sufxvd.cn/Article/details/gthozztjfc.html

[U17] Py：初始化日志
来源：http://dali.ppjwa.cn/Article/details/gtdoxflouk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmavuikue.html

[U18] Py：预编译正则
来源：http://dali.hnqzz.top/Article/details/gtpqizfszq.html

pat = re.compile(r"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejhntnjq.html

[U19] Py：正则替换带回调
来源：http://dali.zdqjudy.top/Article/details/gtqvqlpdlo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.0kj1m.cn/Article/details/gtyipdntmb.html

[U20] Py：缓存函数结果
来源：http://dali.shuidangran.top/Article/details/gtxzbsspam.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxuanxn.top/Article/details/gtohtwngdo.html

[U21] Py：自定义上下文管理器
来源：http://dali.andypj.xyz/Article/details/gtwanndmqn.html

@contextlib.contextmanager
来源：http://dali.hnqzz.top/Article/details/gtehirdpsf.html

[U22] Py：矩阵转置
来源：http://dali.wangshuangyany.cn/Article/details/gtrgocfryc.html

list(zip(*m))
来源：http://dali.jinghuilouyu.cn/Article/details/gtfslovszx.html

[U23] Py：分块读取大文件
来源：http://dali.tianlin.xyz/Article/details/gtwlnnxnjs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.aibaodan.cn/Article/details/gtxevwaeni.html

[U24] Py：路径操作
来源：http://dali.svipenyu.cn/Article/details/gtjyxwzalu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gtrycgavnb.html

[U25] Py：CSV 按字典读
来源：http://dali.svipenyu.cn/Article/details/gtlixplymm.html

csv.DictReader(f)
来源：http://dali.snrcjt.cn/Article/details/gtdmoaezvt.html

[U26] Py：并发下载
来源：http://dali.tian-w.cn/Article/details/gtsrhgeebg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hfpthk.cn/Article/details/gtnkjfegjv.html

[U27] Py：异步 HTTP
来源：http://dali.gaohongyu789.top/Article/details/gtuktpxcgn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.fzhhl.top/Article/details/gtgnpxgduq.html

[U28] Py：类型别名
来源：http://dali.guannengcc.top/Article/details/gtlzchuivx.html

UserId = int
来源：http://dali.xuanzx.com/Article/details/gtzvoywulw.html

[U29] Py：属性校验
来源：http://dali.hfpthk.cn/Article/details/gtrtawlfdc.html

@property 与 @x.setter 配合
来源：http://dali.yonumen.top/Article/details/gtsfwfggcv.html

[U30] Py：数据类
来源：http://dali.hywenlv.cn/Article/details/gtpowxrzrw.html

@dataclass(slots=True)
来源：http://dali.jinqigufen.top/Article/details/gtexazifvn.html


<!-- 参考信息 -->