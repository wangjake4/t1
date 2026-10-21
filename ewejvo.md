代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfqmuboe.html

[S02] C：变量与格式化输出
来源：http://dali.shuidangran.top/Article/details/gtifkqbkph.html

int a = 10; printf("%d\n", a);
来源：http://dali.feifeiyinyue.top/Article/details/gtkkfslpqx.html

[S03] C：读入整数
来源：http://dali.yuxming.cn/Article/details/gttdigvpkg.html

int x; scanf("%d", &x);
来源：http://dali.gzhubu.top/Article/details/gteyhpkamz.html

[S04] C：字符串复制
来源：http://dali.smart0.xyz/Article/details/gtwgaflfnd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sxryk.cn/Article/details/gtosqquqty.html

[S05] C：字符串长度
来源：http://dali.haohaochexian.top/Article/details/gthafqnnnh.html

strlen(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwcpbwgs.html

[S06] C：字符串比较
来源：http://dali.hysaishi.cn/Article/details/gtrhdbjktu.html

strcmp(a, b) == 0
来源：http://dali.pycfn.com/Article/details/gtsonmcpwn.html

[S07] C：数组遍历求和
来源：http://dali.quarkkingdee.top/Article/details/gtvpocixkn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqczewgvx.html

[S08] C：动态内存分配与释放
来源：http://dali.wangshuangyany.cn/Article/details/gtltkozutm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cheryme.top/Article/details/gtpbphvjbm.html

[S09] C：结构体定义与初始化
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnlcnown.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.quarkkingdee.top/Article/details/gtsornybkg.html

[S10] C：指针与解引用
来源：http://dali.jqgfzy.top/Article/details/gtuazwdjoc.html

int *p = &a;  *p = 5;
来源：http://dali.iojbl.cn/Article/details/gtbmmvcjnc.html

[S11] C：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtedmedlbd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.andypj.xyz/Article/details/gtdjgtsxzw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gtawvrfolv.html

fclose(f);
来源：http://dali.sweek.top/Article/details/gtogmocvpm.html

[S12] C：写文件
来源：http://dali.andypj.xyz/Article/details/gtpeifokfs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cheryme.top/Article/details/gtpdpfsjdc.html

[S13] C：宏定义
来源：http://dali.jqgfzy.top/Article/details/gtbjwvhbte.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.redwolf501.top/Article/details/gtajxixlhi.html

[S14] C：枚举
来源：http://dali.yuanzhike.top/Article/details/gtwxnpccpi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuxming.cn/Article/details/gtivsjnbbn.html

[S15] C：类型转换
来源：http://dali.gaohongyu789.top/Article/details/gtuajnsoss.html

(double) a / b
来源：http://dali.hfpthk.cn/Article/details/gtwfujaxdw.html

[S16] C：位操作置位
来源：http://dali.yanxiufei.cn/Article/details/gtaedbblfb.html

x |= (1 << 3);
来源：http://dali.nwbrower.top/Article/details/gtbazlqqpx.html

[S17] C：安全拼接字符串
来源：http://dali.aizwys.cn/Article/details/gthpepveni.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangdashe.top/Article/details/gtnquyaebr.html

[S18] C：命令行参数
来源：http://dali.andypj.xyz/Article/details/gttewegvva.html

int main(int argc, char **argv)
来源：http://dali.shzxlz.cn/Article/details/gtflmsqqkh.html

[S19] C：快速排序
来源：http://dali.tian-w.cn/Article/details/gtsdmbnexu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtyumruixd.html

[S20] C：二分查找
来源：http://dali.meibo888.top/Article/details/gtmxqoohas.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gttshqquna.html

[S21] C：字符类别判断
来源：http://dali.kuanghao11.cn/Article/details/gticxlnhym.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gtutlvmiae.html

[S22] C：字符串转数字
来源：http://dali.sysykeji.top/Article/details/gtergpkwhi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sufxvd.cn/Article/details/gtilqinhcf.html

[S23] C：随机数
来源：http://dali.wangshuangyany.cn/Article/details/gtfzsnlvwg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangdashe.top/Article/details/gthrzpozyh.html

[S24] C：获取本地时间
来源：http://dali.sweek.top/Article/details/gtdpuppwbf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zdqjudy.top/Article/details/gtekyvdlwb.html

[S25] C：内存拷贝
来源：http://dali.nanxinkj.top/Article/details/gtwvcxwqgw.html

memcpy(dst, src, n);
来源：http://dali.xinyue.icu/Article/details/gtdcgxwcyu.html

[S26] C：内存清零
来源：http://dali.snrcjt.cn/Article/details/gtniksyaut.html

memset(a, 0, sizeof a);
来源：http://dali.bjfxy.top/Article/details/gtpkauyjky.html

[S27] C：定义常量
来源：http://dali.aibaodan.cn/Article/details/gtavrfrqnr.html

const double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtdqlhvjrj.html

[S28] C：静态变量
来源：http://dali.sweek.top/Article/details/gtnbdflhae.html

static int counter = 0;
来源：http://dali.9152youxi.cn/Article/details/gtvyaozoac.html

[S29] C：变参函数
来源：http://dali.jinqigufen.top/Article/details/gtaacpdtmb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xziqi.cn/Article/details/gtnrxxhfly.html

[S30] C：头文件保护
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgpteqos.html

#ifndef X_H
来源：http://dali.gogol.net.cn/Article/details/gtekcmlatd.html

#define X_H
来源：http://dali.havefunace.top/Article/details/gthldzbbvp.html

#endif
来源：http://dali.smart0.xyz/Article/details/gtihiixawk.html

[S31] C++：Hello World
来源：http://dali.birdmap.top/Article/details/gtbdqjhjos.html

#include <iostream>
来源：http://dali.sufxvd.cn/Article/details/gtzpnuxnfe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gtjuvkizzc.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gtfxziwyki.html

std::string s = "hi";  s += "!";
来源：http://dali.gaohongyu789.top/Article/details/gtycdasahr.html

[S33] C++：vector 增删
来源：http://dali.yueranfly.top/Article/details/gtmerduqbf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxuanxn.top/Article/details/gtnvstkeuc.html

[S34] C++：遍历 vector
来源：http://dali.daria6918.cn/Article/details/gtzrkvwttl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cashguo.top/Article/details/gtyqouazgz.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gtvgoqwpxp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gtzwuiwnry.html

[S36] C++：unordered_map
来源：http://dali.bjfxy.top/Article/details/gtswccvrku.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtquzusrya.html

[S37] C++：set
来源：http://dali.ydzc1.top/Article/details/gtnugrjxvk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yvedp.cn/Article/details/gthdzexduy.html

[S38] C++：排序
来源：http://dali.316326.xyz/Article/details/gtgnqwwjrm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gtpatdxzbg.html

[S39] C++：自定义比较器排序
来源：http://dali.yanxiufei.cn/Article/details/gtplzkswty.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gtwptlnvgj.html

[S40] C++：查找元素
来源：http://dali.jlsjyb.cn/Article/details/gtoduzkuij.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xinyue.icu/Article/details/gtzcbyknbe.html

[S41] C++：类与构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtihkgdoub.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xziqi.cn/Article/details/gtsihlhaoo.html

[S42] C++：继承与虚函数
来源：http://dali.hysaishi.cn/Article/details/gtzsoedsla.html

class B : public Base { public: void f() override {} };
来源：http://dali.shangyingyoupin.top/Article/details/gtelrivekj.html

[S43] C++：智能指针
来源：http://dali.sufxvd.cn/Article/details/gtxzcjzehw.html

auto p = std::make_unique<int>(5);
来源：http://dali.gogol.net.cn/Article/details/gtugorirlv.html

[S44] C++：引用传参
来源：http://dali.meibo888.top/Article/details/gtlgdhvfmi.html

void inc(int &x) { ++x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumzbhwlt.html

[S45] C++：lambda
来源：http://dali.dianchejie.cn/Article/details/gtpmxaagze.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yangfankeji.com/Article/details/gtveojzdqq.html

[S46] C++：函数模板
来源：http://dali.feifeiyinyue.top/Article/details/gtbtvbngcx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtufjnctow.html

[S47] C++：结构化绑定遍历
来源：http://dali.cucudq.cn/Article/details/gtyjjhajfk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.snrcjt.cn/Article/details/gtgetjqcat.html

[S48] C++：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtibminfnh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.birdmap.top/Article/details/gtaqhkywym.html

while (std::getline(in, line)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacbehshn.html

[S49] C++：写文件
来源：http://dali.andypj.xyz/Article/details/gtyzemlqkt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfhmjxdr.html

[S50] C++：格式化数字
来源：http://dali.chenjidiqi.icu/Article/details/gtmeiycwkx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cashguo.top/Article/details/gtljtpdqve.html

[S51] C++：显式类型转换
来源：http://dali.gaohongyu789.top/Article/details/gtamfdsnkr.html

static_cast<double>(a) / b
来源：http://dali.chenzaomai.com/Article/details/gttujwqydu.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gtbenivwmq.html

int size() const noexcept { return n_; }
来源：http://dali.zycfv.cn/Article/details/gtjxhzvalf.html

[S53] C++：移动语义
来源：http://dali.gotoacloud.top/Article/details/gtgiyunyrr.html

std::vector<int> w = std::move(v);
来源：http://dali.yj202588.top/Article/details/gtrcbbxizo.html

[S54] C++：异常处理
来源：http://dali.xinyue.icu/Article/details/gtoqkyggzj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangdashe.top/Article/details/gtnqgschiw.html

[S55] C++：结构化绑定
来源：http://dali.cqqwz.cn/Article/details/gtrolcgezx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtsdyijuwa.html

[S56] C++：optional
来源：http://dali.guannengcc.top/Article/details/gtfaxsdwpr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhsauzhe.html

[S57] C++：编译期常量
来源：http://dali.hywenlv.cn/Article/details/gtatiyewag.html

constexpr int N = 10;
来源：http://dali.zhixingplan.top/Article/details/gtskqspywn.html

[S58] C++：命名空间
来源：http://dali.c1oappe.top/Article/details/gtggfhbkks.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgufenzy.top/Article/details/gthcveesmx.html

[S59] C++：静态断言
来源：http://dali.jqgfzy.top/Article/details/gturleqdrp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hywenlv.cn/Article/details/gtpgvvqonr.html

[S60] C++：遍历并删除元素
来源：http://dali.meibo888.top/Article/details/gttzdsonmm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gtuobizvgh.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gthywbklln.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daxiang520.top/Article/details/gtmhbdrhva.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjobhloax.html

[T01] Kotlin：Hello World
来源：http://dali.cashguo.top/Article/details/gtaqllivii.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gttqkcguoi.html

[T02] Kotlin：变量
来源：http://dali.daria6918.cn/Article/details/gtspfylgur.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cqqwz.cn/Article/details/gtqlcpwvbe.html

[T03] Kotlin：字符串模板
来源：http://dali.svipenyu.cn/Article/details/gtqiilkxnu.html

"值: $b"
来源：http://dali.redwolf501.top/Article/details/gtbxgavsiy.html

[T04] Kotlin：空安全
来源：http://dali.tanke756.top/Article/details/gtrgffshut.html

val n: String? = null;  n?.length
来源：http://dali.gogol.net.cn/Article/details/gtsykqvscu.html

[T05] Kotlin：when 表达式
来源：http://dali.ybcxt.top/Article/details/gthqkbshao.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zycfv.cn/Article/details/gtfxfltzkz.html

[T06] Kotlin：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gtdpqqdwav.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj202588.top/Article/details/gtussvrrbw.html

[T07] Kotlin：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gtufhlhyzy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xziqi.cn/Article/details/gtgyzowdbm.html

[T08] Kotlin：数据类
来源：http://dali.redwolf501.top/Article/details/gtfjoijnwh.html

data class User(val name: String, val age: Int)
来源：http://dali.kuanghao11.cn/Article/details/gtsugycvzm.html

[T09] Kotlin：扩展函数
来源：http://dali.cdnleiting.top/Article/details/gtpppalnzj.html

fun String.exclaim() = this + "!"
来源：http://dali.shuidangran.top/Article/details/gtvaoqcpas.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258.top/Article/details/gttppcqwxx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnghdnzwk.html

[T11] Kotlin：协程
来源：http://dali.hongshengwenyu.top/Article/details/gtromcnsun.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aizwys.cn/Article/details/gtraecdvng.html

[T12] Kotlin：解构声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfborjjmz.html

val (a, b) = Pair(1, 2)
来源：http://dali.tanke756.top/Article/details/gtggijsnce.html

[T13] Kotlin：只读 Map
来源：http://dali.yangfankeji.com/Article/details/gtymmbzfzd.html

val m = mapOf("a" to 1)
来源：http://dali.yvedp.cn/Article/details/gtrfescqhq.html

[T14] Kotlin：循环
来源：http://dali.gaohongyu789.top/Article/details/gtifhvdenr.html

for (i in 1..10) println(i)
来源：http://dali.yongpay.top/Article/details/gttpyqwjpq.html

[T15] Kotlin：接口
来源：http://dali.cucudq.cn/Article/details/gtenhwtsou.html

interface Shape { fun area(): Double }
来源：http://dali.wangdashe.top/Article/details/gtmpgpurrj.html

[T16] Swift：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtgpdmifeb.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtihsfenbx.html

[T17] Swift：变量与常量
来源：http://dali.tian-w.cn/Article/details/gtluxbccdw.html

var a = 1;  let b = 2
来源：http://dali.chenlongwang.top/Article/details/gtodibikce.html

[T18] Swift：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtvoemxmvg.html

"值: \(b)"
来源：http://dali.yongpay.top/Article/details/gthrxazuct.html

[T19] Swift：可选绑定
来源：http://dali.quarkkingdee.top/Article/details/gtqgwvhxnx.html

if let n = opt { print(n) }
来源：http://dali.andypj.xyz/Article/details/gthcugdwoh.html

[T20] Swift：数组操作
来源：http://dali.hnqzz.top/Article/details/gtpetyhjhz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ybcxt.top/Article/details/gtlwpkgfwy.html

[T21] Swift：遍历
来源：http://dali.yj202588.top/Article/details/gtckumages.html

for x in a { print(x) }
来源：http://dali.cucudq.cn/Article/details/gtxzcdtaig.html

[T22] Swift：字典
来源：http://dali.chenzaomai.com/Article/details/gtacccrnao.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yvedp.cn/Article/details/gtnknvptfn.html

[T23] Swift：函数
来源：http://dali.yuxming.cn/Article/details/gtifrerius.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.havefunace.top/Article/details/gtwogbmzyv.html

[T24] Swift：闭包
来源：http://dali.meibo888.top/Article/details/gtwcjhbquj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtwkhdmioq.html

[T25] Swift：结构体
来源：http://dali.zhixingplan.top/Article/details/gteeabqlwv.html

struct P { var x: Int }
来源：http://dali.jqgfzy.top/Article/details/gtabshnyfq.html

[T26] Swift：类与重写
来源：http://dali.guowangkeji.top/Article/details/gtjufkocrv.html

class A: Base { override func f() {} }
来源：http://dali.jlsjyb.cn/Article/details/gtbgyosopp.html

[T27] Swift：错误处理
来源：http://dali.sysykeji.top/Article/details/gtutncmsjr.html

do { try f() } catch { print(error) }
来源：http://dali.jyoumei.cn/Article/details/gtlreoqasp.html

[T28] Swift：枚举
来源：http://dali.aibaodan.cn/Article/details/gtxsbsbfye.html

enum Color { case red, green }
来源：http://dali.tanke756.top/Article/details/gtjjgikljr.html

[T29] Swift：guard 提前返回
来源：http://dali.chenlongwang.top/Article/details/gtkmlltvzt.html

guard let x = opt else { return }
来源：http://dali.ehwqpu.com/Article/details/gtcxwrkxsa.html

[T30] Swift：协议
来源：http://dali.yj202588.top/Article/details/gtgebawlhm.html

protocol Shape { func area() -> Double }
来源：http://dali.pengpengdd.cyou/Article/details/gthoeesylb.html

[T31] Lua：Hello World
来源：http://dali.bjfxy.top/Article/details/gtamywcagp.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gtxlyxedse.html

[T32] Lua：局部变量
来源：http://dali.ydzc1.top/Article/details/gtlwlxcfem.html

local a = 1
来源：http://dali.yvedp.cn/Article/details/gtfojvlvto.html

[T33] Lua：表（数组）
来源：http://dali.zdqjudy.top/Article/details/gtovwbdzrb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangshuangyany.cn/Article/details/gtaiatdniq.html

[T34] Lua：遍历表
来源：http://dali.nanxinkj.top/Article/details/gtraebetjw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hywenlv.cn/Article/details/gtzwwevgkx.html

[T35] Lua：字典表
来源：http://dali.cheryme.top/Article/details/gtalhmnbrb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtclcgoxsi.html

[T36] Lua：函数
来源：http://dali.jianghu66.top/Article/details/gtwuwefyub.html

function add(a, b) return a + b end
来源：http://dali.sysykeji.top/Article/details/gtgtmpmgpj.html

[T37] Lua：字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gtnylbjssv.html

"a" .. "b"
来源：http://dali.pengpengdd.cyou/Article/details/gtnobuzqag.html

[T38] Lua：条件
来源：http://dali.chenlongwang.top/Article/details/gtykqyjjci.html

if x > 0 then print("正") end
来源：http://dali.nanxinkj.top/Article/details/gtvekipold.html

[T39] Lua：模式匹配
来源：http://dali.zhongyouzk.top/Article/details/gtreehnuqq.html

string.find(s, "%d+")
来源：http://dali.yj202588.top/Article/details/gtxzylahby.html

[T40] Lua：元表
来源：http://dali.redwolf501.top/Article/details/gtwyrilbcb.html

setmetatable({}, { __index = base })
来源：http://dali.chenlongwang.top/Article/details/gtmvfzpziz.html

[T41] Perl：Hello World
来源：http://dali.hnqzz.top/Article/details/gtjesnqaua.html

print "Hello\n";
来源：http://dali.cheryme.top/Article/details/gtujznwtvv.html

[T42] Perl：变量类型
来源：http://dali.jinqigfzy.top/Article/details/gtqrrldkte.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwzblmro.html

[T43] Perl：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtkihpjpan.html

"值: $a"
来源：http://dali.guowangkeji.top/Article/details/gtrtftfvcq.html

[T44] Perl：条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggeiqfrv.html

if ($a > 0) { print "正"; }
来源：http://dali.quarkkingdee.top/Article/details/gtbaitwpbi.html

[T45] Perl：数组遍历
来源：http://dali.hywenlv.cn/Article/details/gtsxmiixet.html

for my $x (@arr) { print $x; }
来源：http://dali.cashguo.top/Article/details/gtsdyevppt.html

[T46] Perl：哈希操作
来源：http://dali.zhongyouzk.top/Article/details/gthvdalste.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.dianchejie.cn/Article/details/gtytgeearj.html

[T47] Perl：正则捕获
来源：http://dali.zhiwuduotai.top/Article/details/gtkuexyzde.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnxiangtu.top/Article/details/gtvhgzxoll.html

[T48] Perl：正则替换
来源：http://dali.birdmap.top/Article/details/gtlrpzbahm.html

$s =~ s/old/new/g;
来源：http://dali.tianlin.xyz/Article/details/gtewhmwwaj.html

[T49] Perl：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtxmweyixl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtvkjgyovb.html

[T50] Perl：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtgotpjtjq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zycfv.cn/Article/details/gtmsvyhykz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zdqjudy.top/Article/details/gtcpwwweal.html

[T51] Scala：Hello World
来源：http://dali.jyoumei.cn/Article/details/gthriinoir.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtdlvkrseb.html

[T52] Scala：变量
来源：http://dali.ehwqpu.com/Article/details/gtubjfaumf.html

val a = 1;  var b = 2
来源：http://dali.daria6918.cn/Article/details/gtvcohqody.html

[T53] Scala：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtanhibxpi.html

s"值: $b"
来源：http://dali.cdnleiting.top/Article/details/gtetptwwbr.html

[T54] Scala：集合映射
来源：http://dali.nwbrower.top/Article/details/gtiyfbsrzi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.snrcjt.cn/Article/details/gtpqxcykcb.html

[T55] Scala：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gtksypzjok.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cdnleiting.top/Article/details/gttpcsepvh.html

[T56] Scala：样例类
来源：http://dali.nwbrower.top/Article/details/gttkcvtqes.html

case class User(name: String, age: Int)
来源：http://dali.smart0.xyz/Article/details/gtmvohtjit.html

[T57] Scala：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gtkupuclwq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ehwqpu.com/Article/details/gtjjyqthom.html

[T58] Scala：函数定义
来源：http://dali.bjfxy.top/Article/details/gtgdvmduwg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtdobtseys.html

[T59] Scala：循环
来源：http://dali.cucudq.cn/Article/details/gtrpwbttwx.html

for (i <- 1 to 10) println(i)
来源：http://dali.yonumen.top/Article/details/gtalmurhsi.html

[T60] Scala：折叠
来源：http://dali.quarkkingdee.top/Article/details/gtqhacszru.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yonumen.top/Article/details/gtwdntmhrx.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtsmysauch.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.dianchejie.cn/Article/details/gtaigytqdr.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtshsznemg.html

[U01] Py：创建虚拟环境
来源：http://dali.aizwys.cn/Article/details/gtduxcdhor.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.havefunace.top/Article/details/gteopkrmlt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.9152youxi.cn/Article/details/gteijonopb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jianghu66.top/Article/details/gtuvoydnex.html

[U03] Py：加载 .env 配置
来源：http://dali.tian-w.cn/Article/details/gtjlvxcscq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuanzhike.top/Article/details/gtnvezzqsl.html

[U04] Py：变量调试打印
来源：http://dali.yj20258.top/Article/details/gtsprgllpi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shzxlz.cn/Article/details/gtcqgnwbor.html

[U05] Py：列表去重且保序
来源：http://dali.jlsjyb.cn/Article/details/gtecnhjxvs.html

list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gtnyhodvgm.html

[U06] Py：合并两个字典
来源：http://dali.jianghu66.top/Article/details/gtnwfcbuwy.html

{**a, **b}
来源：http://dali.yj20258.top/Article/details/gtpzbvftyv.html

[U07] Py：反转字典键值
来源：http://dali.yangfankeji.com/Article/details/gtyxzqfnbz.html

{v: k for k, v in d.items()}
来源：http://dali.chenzaomai.com/Article/details/gtyagvmjvs.html

[U08] Py：展平二维列表
来源：http://dali.svipenyu.cn/Article/details/gtgodiwant.html

[y for x in nested for y in x]
来源：http://dali.zycfv.cn/Article/details/gtkqtwsabn.html

[U09] Py：字典取最大值的键
来源：http://dali.jlsjyb.cn/Article/details/gtvvebwsij.html

max(d, key=d.get)
来源：http://dali.xinyue.icu/Article/details/gtzhoxofoy.html

[U10] Py：按值排序字典
来源：http://dali.smart0.xyz/Article/details/gtvcavqjhz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jyoumei.cn/Article/details/gtchlnweuo.html

[U11] Py：生成器表达式
来源：http://dali.gotoacloud.top/Article/details/gtyelcdhgo.html

(x * 2 for x in arr)
来源：http://dali.haohaochexian.top/Article/details/gtrxoohcdu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ppjwa.cn/Article/details/gteazxzmoh.html

Counter(arr).most_common(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvurroqgk.html

[U13] Py：固定长度队列
来源：http://dali.haohaochexian.top/Article/details/gtqywsukzv.html

deque(maxlen=10)
来源：http://dali.fzhhl.top/Article/details/gtznbnplgf.html

[U14] Py：分组收集到列表
来源：http://dali.wangshuangyany.cn/Article/details/gtdzcplass.html

defaultdict(list)
来源：http://dali.zycfv.cn/Article/details/gtlyjjuvay.html

[U15] Py：高精度计时
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfwsowei.html

t = time.perf_counter()
来源：http://dali.hysaishi.cn/Article/details/gtdrnopynv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gtlrfiqmjo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nanxuanxn.top/Article/details/gtuxyilgja.html

[U17] Py：初始化日志
来源：http://dali.ybcxt.top/Article/details/gtbcpzscck.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hysaishi.cn/Article/details/gtdeuhzvyp.html

[U18] Py：预编译正则
来源：http://dali.aizwys.cn/Article/details/gtxyuocxjw.html

pat = re.compile(r"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gtuytzxjjk.html

[U19] Py：正则替换带回调
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehqrkrws.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hammf.cn/Article/details/gtnqikmqmx.html

[U20] Py：缓存函数结果
来源：http://dali.yuxming.cn/Article/details/gtfbwqolnr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zycfv.cn/Article/details/gtifrceqmf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhiwuduotai.top/Article/details/gtdamyqbae.html

@contextlib.contextmanager
来源：http://dali.xinyue.icu/Article/details/gtrhxqpwku.html

[U22] Py：矩阵转置
来源：http://dali.zdqjudy.top/Article/details/gttwjdwhis.html

list(zip(*m))
来源：http://dali.tianlin.xyz/Article/details/gtfityaivz.html

[U23] Py：分块读取大文件
来源：http://dali.nwbrower.top/Article/details/gtuibcisbh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.c1oappe.top/Article/details/gtkqorgaeb.html

[U24] Py：路径操作
来源：http://dali.gogol.net.cn/Article/details/gttozsewlz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtuknzoext.html


<!-- 参考信息 -->