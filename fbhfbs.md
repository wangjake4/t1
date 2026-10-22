代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaizoxvrk.html

[S04] C：字符串复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgskmbkd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guannengcc.top/Article/details/gtpaewkycf.html

[S05] C：字符串长度
来源：http://dali.yj202588.top/Article/details/gtqbgyobkj.html

strlen(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedzcjtzx.html

[S06] C：字符串比较
来源：http://dali.ivvv.top/Article/details/gtltucmhlv.html

strcmp(a, b) == 0
来源：http://dali.yanxiufei.cn/Article/details/gtcvmxzuov.html

[S07] C：数组遍历求和
来源：http://dali.bjfxy.top/Article/details/gtlnndgxfk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pengpengdd.cyou/Article/details/gtqtwhwlvd.html

[S08] C：动态内存分配与释放
来源：http://dali.hywenlv.cn/Article/details/gtgdlevglm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daxiang520.top/Article/details/gtodfpeayz.html

[S09] C：结构体定义与初始化
来源：http://dali.svipenyu.cn/Article/details/gtlsnpkutt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shuidangran.top/Article/details/gtucilcnzg.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gtxsivzxzj.html

int *p = &a;  *p = 5;
来源：http://dali.snrcjt.cn/Article/details/gtremjsauq.html

[S11] C：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtnotloyvj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhixingplan.top/Article/details/gtkvaybmfn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gtohqorihb.html

fclose(f);
来源：http://dali.yuxming.cn/Article/details/gtlqfqxrfk.html

[S12] C：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gtlgrszuwz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtxmsqktes.html

[S13] C：宏定义
来源：http://dali.c1oappe.top/Article/details/gtifkykewd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daria6918.cn/Article/details/gtvwylrpad.html

[S14] C：枚举
来源：http://dali.ybcxt.top/Article/details/gtdlbuwjcc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj202588.top/Article/details/gtcjqfocmj.html

[S15] C：类型转换
来源：http://dali.c1oappe.top/Article/details/gthvxrhgma.html

(double) a / b
来源：http://dali.meibo888.top/Article/details/gtpgywzfus.html

[S16] C：位操作置位
来源：http://dali.yueranfly.top/Article/details/gttclmslrn.html

x |= (1 << 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtjcuplecw.html

[S17] C：安全拼接字符串
来源：http://dali.ivvv.top/Article/details/gtjtxxqvxc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hywenlv.cn/Article/details/gtnkhjghbu.html

[S18] C：命令行参数
来源：http://dali.gzhubu.top/Article/details/gtlhyinltl.html

int main(int argc, char **argv)
来源：http://dali.sxryk.cn/Article/details/gtoefbydkg.html

[S19] C：快速排序
来源：http://dali.sweek.top/Article/details/gtoqqekswq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtyqebtakf.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gtdmiflosl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmczxepkc.html

[S21] C：字符类别判断
来源：http://dali.sxryk.cn/Article/details/gtzbptlkoo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hysaishi.cn/Article/details/gtvuhianzh.html

[S22] C：字符串转数字
来源：http://dali.kuanghao11.cn/Article/details/gtsopjaojt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258.top/Article/details/gtvutmroeg.html

[S23] C：随机数
来源：http://dali.c1oappe.top/Article/details/gtplkdjsev.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ppjwa.cn/Article/details/gtuqtzaetq.html

[S24] C：获取本地时间
来源：http://dali.birdmap.top/Article/details/gtlmhxhury.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.c1oappe.top/Article/details/gteuwhxlgj.html

[S25] C：内存拷贝
来源：http://dali.ybcxt.top/Article/details/gtysyodrgo.html

memcpy(dst, src, n);
来源：http://dali.yvedp.cn/Article/details/gtwkpeozmg.html

[S26] C：内存清零
来源：http://dali.jqgfzy.top/Article/details/gtsnhouijw.html

memset(a, 0, sizeof a);
来源：http://dali.yuxming.cn/Article/details/gtojccpoxv.html

[S27] C：定义常量
来源：http://dali.ivvv.top/Article/details/gtntujtsns.html

const double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtxyrfljrj.html

[S28] C：静态变量
来源：http://dali.sxryk.cn/Article/details/gtcqeoqulc.html

static int counter = 0;
来源：http://dali.ppjwa.cn/Article/details/gtgddmfiuy.html

[S29] C：变参函数
来源：http://dali.c1oappe.top/Article/details/gtpkdwiebg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxuanxn.top/Article/details/gtnwwfvngx.html

[S30] C：头文件保护
来源：http://dali.smart0.xyz/Article/details/gtbyxouesg.html

#ifndef X_H
来源：http://dali.aizwys.cn/Article/details/gtjfcogtea.html

#define X_H
来源：http://dali.jianghu66.top/Article/details/gtysrvojpz.html

#endif
来源：http://dali.redwolf501.top/Article/details/gtjrnfjcoi.html

[S31] C++：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtvlsxcpfl.html

#include <iostream>
来源：http://dali.sysykeji.top/Article/details/gtjuofvnho.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.snrcjt.cn/Article/details/gtwrsaavwz.html

[S32] C++：字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvezstvf.html

std::string s = "hi";  s += "!";
来源：http://dali.tanke756.top/Article/details/gtgtswpnsl.html

[S33] C++：vector 增删
来源：http://dali.sufxvd.cn/Article/details/gtvptwlvpv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dashuyun.cn/Article/details/gtzgpbtbaq.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gttkogzaej.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenzaomai.com/Article/details/gtibrehxrx.html

[S35] C++：map
来源：http://dali.wangdashe.top/Article/details/gtrbwtoqfb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtyfcaczxl.html

[S36] C++：unordered_map
来源：http://dali.hfpthk.cn/Article/details/gtpbbacdsn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gtmrmiutlr.html

[S37] C++：set
来源：http://dali.zdqjudy.top/Article/details/gtbyribknr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.haohaochexian.top/Article/details/gtzykytlkq.html

[S38] C++：排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhcyhtvc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhengqikj.top/Article/details/gtkihxkdso.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgfzy.top/Article/details/gthsdwubwk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmugycakw.html

[S40] C++：查找元素
来源：http://dali.hammf.cn/Article/details/gtnsngnmew.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.fzhhl.top/Article/details/gtmrffrkvn.html

[S41] C++：类与构造函数
来源：http://dali.ppjwa.cn/Article/details/gtatibqqug.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ybcxt.top/Article/details/gtyjpyyapq.html

[S42] C++：继承与虚函数
来源：http://dali.chenzaomai.com/Article/details/gtwwhirnkw.html

class B : public Base { public: void f() override {} };
来源：http://dali.gotoacloud.top/Article/details/gtkdcynvqf.html

[S43] C++：智能指针
来源：http://dali.vqdsnc.cn/Article/details/gtpuqcgdvu.html

auto p = std::make_unique<int>(5);
来源：http://dali.shuidangran.top/Article/details/gthukiyfwo.html

[S44] C++：引用传参
来源：http://dali.nanxinkj.top/Article/details/gtdskkycwh.html

void inc(int &x) { ++x; }
来源：http://dali.aibaodan.cn/Article/details/gtwpvrxsbv.html

[S45] C++：lambda
来源：http://dali.hywenlv.cn/Article/details/gtacqvfoed.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gttaxnhpju.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gthnledlhj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yanxiufei.cn/Article/details/gtggkinehj.html

[S47] C++：结构化绑定遍历
来源：http://dali.jyoumei.cn/Article/details/gthzwiecfl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhongyouzk.top/Article/details/gtbvzfnstj.html

[S48] C++：逐行读文件
来源：http://dali.yj202588.top/Article/details/gthrghxptu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.c1oappe.top/Article/details/gtqwskbpdq.html

while (std::getline(in, line)) { }
来源：http://dali.ivvv.top/Article/details/gtlqkrysnf.html

[S49] C++：写文件
来源：http://dali.sufxvd.cn/Article/details/gtduvlujlp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hywenlv.cn/Article/details/gtkyzmgxvt.html

[S50] C++：格式化数字
来源：http://dali.chenlongwang.top/Article/details/gtuemsxddh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtvjxydsdx.html

[S51] C++：显式类型转换
来源：http://dali.kuanghao11.cn/Article/details/gtztndiple.html

static_cast<double>(a) / b
来源：http://dali.pengpengdd.cyou/Article/details/gtijjzkzwu.html

[S52] C++：const 与 noexcept
来源：http://dali.sweek.top/Article/details/gtljqmdnbv.html

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gttcsreawj.html

[S53] C++：移动语义
来源：http://dali.ydzc1.top/Article/details/gthllzvvbx.html

std::vector<int> w = std::move(v);
来源：http://dali.chenzaomai.com/Article/details/gtvakdgisq.html

[S54] C++：异常处理
来源：http://dali.zycfv.cn/Article/details/gtnpyzgcjt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yanxiufei.cn/Article/details/gtpbcxfnlm.html

[S55] C++：结构化绑定
来源：http://dali.fengsongda.top/Article/details/gtvkgfpyia.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guowangkeji.top/Article/details/gtscgjlkej.html

[S56] C++：optional
来源：http://dali.haohaochexian.top/Article/details/gtmdmchzxy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jianghu66.top/Article/details/gtuvviwdkv.html

[S57] C++：编译期常量
来源：http://dali.jyoumei.cn/Article/details/gttlknmrvx.html

constexpr int N = 10;
来源：http://dali.yj202588.top/Article/details/gtrxydrsea.html

[S58] C++：命名空间
来源：http://dali.hnxiangtu.top/Article/details/gtcrrhdlgg.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgufenzy.top/Article/details/gtftxbpsry.html

[S59] C++：静态断言
来源：http://dali.shuidangran.top/Article/details/gtdpjqiqnz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.havefunace.top/Article/details/gtiwryvieu.html

[S60] C++：遍历并删除元素
来源：http://dali.gaohongyu789.top/Article/details/gtzfhhegyi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gtzjfptpkh.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtxyvciheu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gtrccplkoi.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtwvuqxckm.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtfstqkmen.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gtpjyzxngt.html

[T02] Kotlin：变量
来源：http://dali.xziqi.cn/Article/details/gtjuebuvfi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.quarkkingdee.top/Article/details/gtsrcwaxcx.html

[T03] Kotlin：字符串模板
来源：http://dali.jiagoushi.top/Article/details/gtylybfmho.html

"值: $b"
来源：http://dali.havefunace.top/Article/details/gtcxvoxofh.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gtogbblfef.html

val n: String? = null;  n?.length
来源：http://dali.sweek.top/Article/details/gtwgtabzbp.html

[T05] Kotlin：when 表达式
来源：http://dali.hammf.cn/Article/details/gtvpewhxpl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258888.top/Article/details/gtaksduavi.html

[T06] Kotlin：集合映射
来源：http://dali.redwolf501.top/Article/details/gtoyrlqkzn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.mhx1999.top/Article/details/gtcqdwgyuu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gtcfudpkmm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxuanxn.top/Article/details/gtsdkqcbil.html

[T08] Kotlin：数据类
来源：http://dali.dianchejie.cn/Article/details/gtvftoergc.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangtech.top/Article/details/gtffxeuqyb.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gtmkaekmtw.html

fun String.exclaim() = this + "!"
来源：http://dali.daria6918.cn/Article/details/gtasxeipbv.html

[T10] Kotlin：默认参数
来源：http://dali.cqqwz.cn/Article/details/gtvjvnxuuq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jiagoushi.top/Article/details/gttzucicfk.html

[T11] Kotlin：协程
来源：http://dali.yuxming.cn/Article/details/gtlljnqksx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aibaodan.cn/Article/details/gtplrlxqlh.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258.top/Article/details/gtsxyrizlx.html

val (a, b) = Pair(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtwayfzgko.html

[T13] Kotlin：只读 Map
来源：http://dali.hongshengwenyu.top/Article/details/gtowagkvcf.html

val m = mapOf("a" to 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtscusyjuc.html

[T14] Kotlin：循环
来源：http://dali.zhixingplan.top/Article/details/gthhabvpws.html

for (i in 1..10) println(i)
来源：http://dali.ydzc1.top/Article/details/gtmgqvuaik.html

[T15] Kotlin：接口
来源：http://dali.xuanzx.com/Article/details/gtdkduyrhw.html

interface Shape { fun area(): Double }
来源：http://dali.ehwqpu.com/Article/details/gtkqbyqrut.html

[T16] Swift：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtpdcpypsb.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gtskfrgjwa.html

[T17] Swift：变量与常量
来源：http://dali.jqgfzy.top/Article/details/gtduqomsdj.html

var a = 1;  let b = 2
来源：http://dali.dashuyun.cn/Article/details/gttzkcmhnv.html

[T18] Swift：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gtbgpiudsi.html

"值: \(b)"
来源：http://dali.ivvv.top/Article/details/gtecwfzucp.html

[T19] Swift：可选绑定
来源：http://dali.jlsjyb.cn/Article/details/gtvfsrxdev.html

if let n = opt { print(n) }
来源：http://dali.iojbl.cn/Article/details/gtpcynbkee.html

[T20] Swift：数组操作
来源：http://dali.mhx1999.top/Article/details/gtdlafnjwo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cheryme.top/Article/details/gtjqsicnrf.html

[T21] Swift：遍历
来源：http://dali.tian-w.cn/Article/details/gtazkimegz.html

for x in a { print(x) }
来源：http://dali.bjfxy.top/Article/details/gtqkafhkeb.html

[T22] Swift：字典
来源：http://dali.vqdsnc.cn/Article/details/gtcnfthqvo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgubjpqiq.html

[T23] Swift：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkturtbs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gtbclouvnt.html

[T24] Swift：闭包
来源：http://dali.chenzaomai.com/Article/details/gtawuxckek.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtoqytqvcn.html

[T25] Swift：结构体
来源：http://dali.chenlongwang.top/Article/details/gttujifljd.html

struct P { var x: Int }
来源：http://dali.yanxiufei.cn/Article/details/gtvpnwuinr.html

[T26] Swift：类与重写
来源：http://dali.xuetiantiany.cn/Article/details/gtjuluywwa.html

class A: Base { override func f() {} }
来源：http://dali.bjfxy.top/Article/details/gtkcbjnupi.html

[T27] Swift：错误处理
来源：http://dali.0kj1m.cn/Article/details/gtzbrforkb.html

do { try f() } catch { print(error) }
来源：http://dali.jyoumei.cn/Article/details/gtaftbbaye.html

[T28] Swift：枚举
来源：http://dali.gotoacloud.top/Article/details/gtkfpzvnhd.html

enum Color { case red, green }
来源：http://dali.tian-w.cn/Article/details/gtdiktjyli.html

[T29] Swift：guard 提前返回
来源：http://dali.iojbl.cn/Article/details/gtrntgbasz.html

guard let x = opt else { return }
来源：http://dali.wangdashe.top/Article/details/gtwoxfphnc.html

[T30] Swift：协议
来源：http://dali.yj20258.top/Article/details/gtkllxvoyg.html

protocol Shape { func area() -> Double }
来源：http://dali.daria6918.cn/Article/details/gtwhounoie.html

[T31] Lua：Hello World
来源：http://dali.wangdashe.top/Article/details/gtisexndvh.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtpypbjavs.html

[T32] Lua：局部变量
来源：http://dali.yuxming.cn/Article/details/gtcgmfiysf.html

local a = 1
来源：http://dali.shzxlz.cn/Article/details/gtkvccryzh.html

[T33] Lua：表（数组）
来源：http://dali.andypj.xyz/Article/details/gtoujpcrkw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sxryk.cn/Article/details/gtbzuuxpor.html

[T34] Lua：遍历表
来源：http://dali.yuxming.cn/Article/details/gtcdveipfe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yj202588.top/Article/details/gtpjwiqwml.html

[T35] Lua：字典表
来源：http://dali.c1oappe.top/Article/details/gtdcprwtkc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yonumen.top/Article/details/gtwzimkriu.html

[T36] Lua：函数
来源：http://dali.gotoacloud.top/Article/details/gtapbmydws.html

function add(a, b) return a + b end
来源：http://dali.jyoumei.cn/Article/details/gttrqfvwqw.html

[T37] Lua：字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjiopgjqn.html

"a" .. "b"
来源：http://dali.aizwys.cn/Article/details/gtdwsnmfpm.html

[T38] Lua：条件
来源：http://dali.snrcjt.cn/Article/details/gttysdwadi.html

if x > 0 then print("正") end
来源：http://dali.jyoumei.cn/Article/details/gtebhpbpgh.html

[T39] Lua：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gtvhbjzuxz.html

string.find(s, "%d+")
来源：http://dali.gotoacloud.top/Article/details/gtsemtmbbm.html

[T40] Lua：元表
来源：http://dali.sweek.top/Article/details/gtfmhlfycq.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigufen.top/Article/details/gttoknjoyj.html

[T41] Perl：Hello World
来源：http://dali.zhixingplan.top/Article/details/gthgeondsm.html

print "Hello\n";
来源：http://dali.zycfv.cn/Article/details/gtmhhjhipb.html

[T42] Perl：变量类型
来源：http://dali.iojbl.cn/Article/details/gtpbyfjjff.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxznstnqo.html

[T43] Perl：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtmvokvkud.html

"值: $a"
来源：http://dali.hnxiangtu.top/Article/details/gtipciljbs.html

[T44] Perl：条件
来源：http://dali.hnqzz.top/Article/details/gttuykzjij.html

if ($a > 0) { print "正"; }
来源：http://dali.316326.xyz/Article/details/gtjpeykmll.html

[T45] Perl：数组遍历
来源：http://dali.yuxming.cn/Article/details/gtbwlbbgbp.html

for my $x (@arr) { print $x; }
来源：http://dali.gaohongyu789.top/Article/details/gtgsxsahic.html

[T46] Perl：哈希操作
来源：http://dali.nanxinkj.top/Article/details/gtvhhsuofc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.bjfxy.top/Article/details/gtwtlcboft.html

[T47] Perl：正则捕获
来源：http://dali.yvedp.cn/Article/details/gtcrlubhxv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xylfe.cn/Article/details/gtcptkzrfe.html

[T48] Perl：正则替换
来源：http://dali.ehwqpu.com/Article/details/gtcrwkixsw.html

$s =~ s/old/new/g;
来源：http://dali.dianchejie.cn/Article/details/gtvdjjoyau.html

[T49] Perl：函数
来源：http://dali.yangfankeji.com/Article/details/gtsnzczccu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtjpccldzl.html

[T50] Perl：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtqvpilfrd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksbwaoau.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.c1oappe.top/Article/details/gtflphosrv.html

[T51] Scala：Hello World
来源：http://dali.cucudq.cn/Article/details/gtwxzdrswn.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gtahtwflya.html

[T52] Scala：变量
来源：http://dali.chenlongwang.top/Article/details/gtymwjbfxv.html

val a = 1;  var b = 2
来源：http://dali.ehwqpu.com/Article/details/gtrxsqwemy.html

[T53] Scala：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gtrbcutcgx.html

s"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gtokoewoux.html

[T54] Scala：集合映射
来源：http://dali.cucudq.cn/Article/details/gttohcauwc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtohrxrohh.html

[T55] Scala：集合过滤
来源：http://dali.aizwys.cn/Article/details/gttmvovyjm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cashguo.top/Article/details/gtcixyzrte.html

[T56] Scala：样例类
来源：http://dali.yuxming.cn/Article/details/gtzuaayahv.html

case class User(name: String, age: Int)
来源：http://dali.xuanzx.com/Article/details/gtbwsgteiv.html

[T57] Scala：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gttnrfqiah.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shangyingyoupin.top/Article/details/gtwskfpoda.html

[T58] Scala：函数定义
来源：http://dali.daxiang520.top/Article/details/gtgslozcsv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.kuanghao11.cn/Article/details/gtxocqcqxg.html

[T59] Scala：循环
来源：http://dali.hnqzz.top/Article/details/gtmtiisdgu.html

for (i <- 1 to 10) println(i)
来源：http://dali.sxryk.cn/Article/details/gtumukjetj.html

[T60] Scala：折叠
来源：http://dali.yj202588.top/Article/details/gtlyrqcpgh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yangfankeji.com/Article/details/gtcrzibulf.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtuclawswv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cucudq.cn/Article/details/gtbaepjbrp.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtymumpcqm.html

[U01] Py：创建虚拟环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkvfuuwh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yanxiufei.cn/Article/details/gtxyujcqjz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gogol.net.cn/Article/details/gtuiichrwk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtuztwmtit.html

[U03] Py：加载 .env 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkddpuvdb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlsqstni.html

[U04] Py：变量调试打印
来源：http://dali.zhiwuduotai.top/Article/details/gtmstmywjr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yvedp.cn/Article/details/gtsmjgtiyl.html

[U05] Py：列表去重且保序
来源：http://dali.yuxming.cn/Article/details/gtbojqsktf.html

list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtnlnjbauo.html

[U06] Py：合并两个字典
来源：http://dali.sxryk.cn/Article/details/gtkflmdwmo.html

{**a, **b}
来源：http://dali.nanxinkj.top/Article/details/gtmjvybdou.html

[U07] Py：反转字典键值
来源：http://dali.nanxuanxn.top/Article/details/gtvzirsdop.html

{v: k for k, v in d.items()}
来源：http://dali.xziqi.cn/Article/details/gtxctnkjkw.html

[U08] Py：展平二维列表
来源：http://dali.wangshuangyany.cn/Article/details/gtekghyyth.html

[y for x in nested for y in x]
来源：http://dali.jinqigufen.top/Article/details/gtsiecvlcc.html

[U09] Py：字典取最大值的键
来源：http://dali.yj202588.top/Article/details/gtuddatddr.html

max(d, key=d.get)
来源：http://dali.jqgufenzy.top/Article/details/gtdgueboyl.html

[U10] Py：按值排序字典
来源：http://dali.yvedp.cn/Article/details/gtvolltwjl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shanyushiyangtech.top/Article/details/gtaeydupty.html

[U11] Py：生成器表达式
来源：http://dali.hywenlv.cn/Article/details/gtwokfxwcl.html

(x * 2 for x in arr)
来源：http://dali.shzxlz.cn/Article/details/gtmfrfpqem.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yvedp.cn/Article/details/gtlppztahn.html

Counter(arr).most_common(3)
来源：http://dali.svipenyu.cn/Article/details/gtbyicqidq.html

[U13] Py：固定长度队列
来源：http://dali.wangdashe.top/Article/details/gtzuyjeoqh.html

deque(maxlen=10)
来源：http://dali.zhixingplan.top/Article/details/gtkavzmafw.html

[U14] Py：分组收集到列表
来源：http://dali.aizwys.cn/Article/details/gtodjatovk.html

defaultdict(list)
来源：http://dali.yuanzhike.top/Article/details/gtmggntlob.html

[U15] Py：高精度计时
来源：http://dali.yvedp.cn/Article/details/gtgjvdyqhu.html

t = time.perf_counter()
来源：http://dali.c1oappe.top/Article/details/gtkvjqkriu.html

[U16] Py：命令行参数解析
来源：http://dali.pengpengdd.cyou/Article/details/gtdcbsowhf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shuidangran.top/Article/details/gtmpfchfar.html

[U17] Py：初始化日志
来源：http://dali.jinqigufen.top/Article/details/gtnwbrwdeo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ybcxt.top/Article/details/gtrzizcshx.html

[U18] Py：预编译正则
来源：http://dali.bjfxy.top/Article/details/gtrzwdbhio.html

pat = re.compile(r"\d+")
来源：http://dali.9152youxi.cn/Article/details/gtzmqhdqqm.html

[U19] Py：正则替换带回调
来源：http://dali.0kj1m.cn/Article/details/gtisekrlvo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.meibo888.top/Article/details/gtpfohyurc.html

[U20] Py：缓存函数结果
来源：http://dali.chenjidiqi.icu/Article/details/gtdpzmihyh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhengqikj.top/Article/details/gtrnvrtfpb.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigufen.top/Article/details/gthypxoxpb.html

@contextlib.contextmanager
来源：http://dali.cqqwz.cn/Article/details/gtkqfblfzq.html

[U22] Py：矩阵转置
来源：http://dali.jyoumei.cn/Article/details/gtksbnoeuh.html

list(zip(*m))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnnbszmb.html

[U23] Py：分块读取大文件
来源：http://dali.cashguo.top/Article/details/gtxzcdqqbc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xuetiantiany.cn/Article/details/gtubyxltnt.html

[U24] Py：路径操作
来源：http://dali.yongpay.top/Article/details/gtnpvidarl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxgfiacm.html

[U25] Py：CSV 按字典读
来源：http://dali.hywenlv.cn/Article/details/gteoisnhof.html

csv.DictReader(f)
来源：http://dali.kuanghao11.cn/Article/details/gtqqkayagu.html

[U26] Py：并发下载
来源：http://dali.tian-w.cn/Article/details/gtknnjxzyn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gtapgpztch.html


<!-- 参考信息 -->