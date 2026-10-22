代发 wailian999

S. C / C++ 专题
来源：http://dali.hfpthk.cn/Article/details/gtnqctkddb.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufspcicg.html

[S01] C：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtntylochw.html

#include <stdio.h>
来源：http://dali.daxiang520.top/Article/details/gtyxzcfgqv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygqeyyzf.html

[S02] C：变量与格式化输出
来源：http://dali.andypj.xyz/Article/details/gtosvnicjz.html

int a = 10; printf("%d\n", a);
来源：http://dali.cdnleiting.top/Article/details/gtshqnuety.html

[S03] C：读入整数
来源：http://dali.chenlongwang.top/Article/details/gtfocdugju.html

int x; scanf("%d", &x);
来源：http://dali.jiagoushi.top/Article/details/gtbqjkfjuw.html

[S04] C：字符串复制
来源：http://dali.aibaodan.cn/Article/details/gtvtazrvon.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jyoumei.cn/Article/details/gtclxdyxpv.html

[S05] C：字符串长度
来源：http://dali.zdqjudy.top/Article/details/gttydxuwgy.html

strlen(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzmrgpjb.html

[S06] C：字符串比较
来源：http://dali.iojbl.cn/Article/details/gtixoddkwc.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gtgglakdgm.html

[S07] C：数组遍历求和
来源：http://dali.vqdsnc.cn/Article/details/gtxmdhykkg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigufen.top/Article/details/gtmmneqqut.html

[S08] C：动态内存分配与释放
来源：http://dali.tanke756.top/Article/details/gtljjgtibn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zycfv.cn/Article/details/gtnhfosxpm.html

[S09] C：结构体定义与初始化
来源：http://dali.wangshuangyany.cn/Article/details/gtnserradm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gtfrdutorw.html

[S10] C：指针与解引用
来源：http://dali.hywenlv.cn/Article/details/gtooafupok.html

int *p = &a;  *p = 5;
来源：http://dali.redwolf501.top/Article/details/gtmlskevqu.html

[S11] C：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtmfrzbppx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuanzhike.top/Article/details/gtcekgsfbu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.bjfxy.top/Article/details/gtinpekvtx.html

fclose(f);
来源：http://dali.chenjidiqi.icu/Article/details/gtqlquyrdt.html

[S12] C：写文件
来源：http://dali.dianchejie.cn/Article/details/gtsigzspvo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.bjfxy.top/Article/details/gtixzowsox.html

[S13] C：宏定义
来源：http://dali.chenjidiqi.icu/Article/details/gtafynafss.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.smart0.xyz/Article/details/gtbngozluk.html

[S14] C：枚举
来源：http://dali.xylfe.cn/Article/details/gtwkykmqow.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.316326.xyz/Article/details/gtzmgonkrb.html

[S15] C：类型转换
来源：http://dali.nwbrower.top/Article/details/gtyhvyowxc.html

(double) a / b
来源：http://dali.dianchejie.cn/Article/details/gtayjbokqw.html

[S16] C：位操作置位
来源：http://dali.shangyingyoupin.top/Article/details/gtsqjhrnyd.html

x |= (1 << 3);
来源：http://dali.dianchejie.cn/Article/details/gtyottfnjk.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqjrqbss.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuanzhike.top/Article/details/gtzchmzsfc.html

[S18] C：命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gtxusqhjtn.html

int main(int argc, char **argv)
来源：http://dali.hfpthk.cn/Article/details/gtubwluziq.html

[S19] C：快速排序
来源：http://dali.jinqigufen.top/Article/details/gtaohnrmdm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gttsowlanw.html

[S20] C：二分查找
来源：http://dali.nanxuanxn.top/Article/details/gtsjinvuxf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gtlpdzsdud.html

[S21] C：字符类别判断
来源：http://dali.sysykeji.top/Article/details/gtjtxebeey.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgufenzy.top/Article/details/gtzvmnlixf.html

[S22] C：字符串转数字
来源：http://dali.havefunace.top/Article/details/gtyxclcdrw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sxryk.cn/Article/details/gtxlqqgwyy.html

[S23] C：随机数
来源：http://dali.xuetiantiany.cn/Article/details/gtrrvrudvz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.birdmap.top/Article/details/gteuopejkz.html

[S24] C：获取本地时间
来源：http://dali.yj20258.top/Article/details/gttueuldfa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhiwuduotai.top/Article/details/gtclhfcyyt.html

[S25] C：内存拷贝
来源：http://dali.tanke756.top/Article/details/gtmwwjqzdq.html

memcpy(dst, src, n);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuyxheile.html

[S26] C：内存清零
来源：http://dali.xylfe.cn/Article/details/gtkdgzzbth.html

memset(a, 0, sizeof a);
来源：http://dali.xylfe.cn/Article/details/gthbcgaitp.html

[S27] C：定义常量
来源：http://dali.hfpthk.cn/Article/details/gteduokhao.html

const double PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtnzlscuvt.html

[S28] C：静态变量
来源：http://dali.daxiang520.top/Article/details/gttleajhjq.html

static int counter = 0;
来源：http://dali.andypj.xyz/Article/details/gtblkmejcd.html

[S29] C：变参函数
来源：http://dali.jiagoushi.top/Article/details/gtbpgafswh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gtlisrcquf.html

[S30] C：头文件保护
来源：http://dali.iojbl.cn/Article/details/gtzeskejzw.html

#ifndef X_H
来源：http://dali.shzxlz.cn/Article/details/gtywrxybyr.html

#define X_H
来源：http://dali.wangshuangyany.cn/Article/details/gtvbuxexim.html

#endif
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjrfhxdx.html

[S31] C++：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtadueuknt.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gtgzjjmlfb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.birdmap.top/Article/details/gtqytusnwq.html

[S32] C++：字符串
来源：http://dali.cdnleiting.top/Article/details/gtajgccmef.html

std::string s = "hi";  s += "!";
来源：http://dali.hywenlv.cn/Article/details/gtqbtvyfty.html

[S33] C++：vector 增删
来源：http://dali.hongshengwenyu.top/Article/details/gtkcevvgyy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.0kj1m.cn/Article/details/gtlppgtruq.html

[S34] C++：遍历 vector
来源：http://dali.zhongyouzk.top/Article/details/gtcvhmrqnz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.havefunace.top/Article/details/gtjnfrfaig.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gtlcrxeagb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtjxvowwlt.html

[S36] C++：unordered_map
来源：http://dali.yuanzhike.top/Article/details/gtkckhsalb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtqxcyzhtp.html

[S37] C++：set
来源：http://dali.xziqi.cn/Article/details/gtnnjjbcpz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258888.top/Article/details/gtvffqjhbk.html

[S38] C++：排序
来源：http://dali.sysykeji.top/Article/details/gtulmcgkol.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpareupl.html

[S39] C++：自定义比较器排序
来源：http://dali.zycfv.cn/Article/details/gttirvbhza.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenzaomai.com/Article/details/gtqbmwnfnx.html

[S40] C++：查找元素
来源：http://dali.ydzc1.top/Article/details/gtrbpnpmyw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zycfv.cn/Article/details/gtwvxcfatj.html

[S41] C++：类与构造函数
来源：http://dali.hammf.cn/Article/details/gtdugivbsj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aizwys.cn/Article/details/gtacctdmgi.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gtduhkgspa.html

class B : public Base { public: void f() override {} };
来源：http://dali.smart0.xyz/Article/details/gtutrxfuzn.html

[S43] C++：智能指针
来源：http://dali.kuanghao11.cn/Article/details/gtakxmzirn.html

auto p = std::make_unique<int>(5);
来源：http://dali.shuidangran.top/Article/details/gtypkyjrab.html

[S44] C++：引用传参
来源：http://dali.jyoumei.cn/Article/details/gtismwgvvk.html

void inc(int &x) { ++x; }
来源：http://dali.cashguo.top/Article/details/gtdgugfuqh.html

[S45] C++：lambda
来源：http://dali.yonumen.top/Article/details/gtdargmstv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zdqjudy.top/Article/details/gtgkxvbvxj.html

[S46] C++：函数模板
来源：http://dali.aizwys.cn/Article/details/gtutyhwpzd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dashuyun.cn/Article/details/gtmugrytks.html

[S47] C++：结构化绑定遍历
来源：http://dali.kuanghao11.cn/Article/details/gtqgohrjid.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jianghu66.top/Article/details/gtkjawqfyv.html

[S48] C++：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjcjnldn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fzhhl.top/Article/details/gtebohrfnn.html

while (std::getline(in, line)) { }
来源：http://dali.xuanzx.com/Article/details/gtzjjdgoll.html

[S49] C++：写文件
来源：http://dali.jqgfzy.top/Article/details/gtqqfymxje.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.feifeiyinyue.top/Article/details/gtowjgaluh.html

[S50] C++：格式化数字
来源：http://dali.shzxlz.cn/Article/details/gtwwlmccfa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtoshvpvmk.html

[S51] C++：显式类型转换
来源：http://dali.yj20258888.top/Article/details/gtqbqrcycc.html

static_cast<double>(a) / b
来源：http://dali.yj202588.top/Article/details/gtfczktiqw.html

[S52] C++：const 与 noexcept
来源：http://dali.aibaodan.cn/Article/details/gtsnnjukdp.html

int size() const noexcept { return n_; }
来源：http://dali.hfpthk.cn/Article/details/gtorqwwfla.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gtbifomyfb.html

std::vector<int> w = std::move(v);
来源：http://dali.yuanzhike.top/Article/details/gtdjehncks.html

[S54] C++：异常处理
来源：http://dali.jianghu66.top/Article/details/gtjgaozawl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtywgqnirr.html

[S55] C++：结构化绑定
来源：http://dali.9152youxi.cn/Article/details/gtbssdbawi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cqqwz.cn/Article/details/gtfbysrhwr.html

[S56] C++：optional
来源：http://dali.sxryk.cn/Article/details/gtvakfozfz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.smart0.xyz/Article/details/gtxnwzlheh.html

[S57] C++：编译期常量
来源：http://dali.cucudq.cn/Article/details/gtmkhlpofc.html

constexpr int N = 10;
来源：http://dali.haohaochexian.top/Article/details/gtkavhwqmh.html

[S58] C++：命名空间
来源：http://dali.haohaochexian.top/Article/details/gtkkebizky.html

namespace ns { int f() { return 1; } }
来源：http://dali.hammf.cn/Article/details/gtuzvkdkly.html

[S59] C++：静态断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlewmgjl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.havefunace.top/Article/details/gtuzblnhja.html

[S60] C++：遍历并删除元素
来源：http://dali.fengsongda.top/Article/details/gtsuuchkfi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cashguo.top/Article/details/gtrewnzqqf.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtuqpcyokl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gtzkotftmx.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtbnfdadwj.html

[T01] Kotlin：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtqoxkukif.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gthmqdhgoy.html

[T02] Kotlin：变量
来源：http://dali.chenzaomai.com/Article/details/gtzmnbiqml.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnqzz.top/Article/details/gtukwotgwq.html

[T03] Kotlin：字符串模板
来源：http://dali.xinyue.icu/Article/details/gtpvcectqt.html

"值: $b"
来源：http://dali.shangyingyoupin.top/Article/details/gtnuqtyruo.html

[T04] Kotlin：空安全
来源：http://dali.jiagoushi.top/Article/details/gttaukhjrs.html

val n: String? = null;  n?.length
来源：http://dali.jqgufenzy.top/Article/details/gtngfqdccu.html

[T05] Kotlin：when 表达式
来源：http://dali.svipenyu.cn/Article/details/gtwdgewnhw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hysaishi.cn/Article/details/gtfngssntd.html

[T06] Kotlin：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gtbojdukcq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnqzz.top/Article/details/gtmumphvgq.html

[T07] Kotlin：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gtaalxkzgz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gtysdljsms.html

[T08] Kotlin：数据类
来源：http://dali.yonumen.top/Article/details/gtvxspymqn.html

data class User(val name: String, val age: Int)
来源：http://dali.ydzc1.top/Article/details/gtzmispcwf.html

[T09] Kotlin：扩展函数
来源：http://dali.redwolf501.top/Article/details/gturdbwori.html

fun String.exclaim() = this + "!"
来源：http://dali.cheryme.top/Article/details/gtnsrthqsz.html

[T10] Kotlin：默认参数
来源：http://dali.yonumen.top/Article/details/gtgehdowdi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fengsongda.top/Article/details/gthjqvhydr.html

[T11] Kotlin：协程
来源：http://dali.iojbl.cn/Article/details/gtvrxeytse.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.wangdashe.top/Article/details/gtxgnnxvgp.html

[T12] Kotlin：解构声明
来源：http://dali.0kj1m.cn/Article/details/gtyryltdcy.html

val (a, b) = Pair(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtqxxycmts.html

[T13] Kotlin：只读 Map
来源：http://dali.fengsongda.top/Article/details/gthtjyagvn.html

val m = mapOf("a" to 1)
来源：http://dali.xuanzx.com/Article/details/gtbsstuszh.html

[T14] Kotlin：循环
来源：http://dali.cqqwz.cn/Article/details/gtnhrwrxgk.html

for (i in 1..10) println(i)
来源：http://dali.yj202588.top/Article/details/gtdktohsjy.html

[T15] Kotlin：接口
来源：http://dali.daria6918.cn/Article/details/gtqxwibulr.html

interface Shape { fun area(): Double }
来源：http://dali.yanxiufei.cn/Article/details/gttowulysm.html

[T16] Swift：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtpmdfjtoe.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gtbmlabsle.html

[T17] Swift：变量与常量
来源：http://dali.zhiwuduotai.top/Article/details/gtliturflf.html

var a = 1;  let b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtkshoptcg.html

[T18] Swift：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtcqrezvid.html

"值: \(b)"
来源：http://dali.iojbl.cn/Article/details/gtqzjlfdbq.html

[T19] Swift：可选绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnlrnjsk.html

if let n = opt { print(n) }
来源：http://dali.zhengqikj.top/Article/details/gthbpjudrt.html

[T20] Swift：数组操作
来源：http://dali.yj20258888.top/Article/details/gtycbeqimv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hysaishi.cn/Article/details/gttijmmqah.html

[T21] Swift：遍历
来源：http://dali.yuxming.cn/Article/details/gtmfpcucha.html

for x in a { print(x) }
来源：http://dali.chenjidiqi.icu/Article/details/gtatvgtepd.html

[T22] Swift：字典
来源：http://dali.kuanghao11.cn/Article/details/gtclzzyqqb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jiagoushi.top/Article/details/gtbiitvyqg.html

[T23] Swift：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefyohgwg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fzhhl.top/Article/details/gtvpdifveg.html

[T24] Swift：闭包
来源：http://dali.tanke756.top/Article/details/gtrpwuddob.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtndidyyqv.html

[T25] Swift：结构体
来源：http://dali.shangyingyoupin.top/Article/details/gtzjhftznk.html

struct P { var x: Int }
来源：http://dali.pycfn.com/Article/details/gtprajepkn.html

[T26] Swift：类与重写
来源：http://dali.iojbl.cn/Article/details/gtdmxwdrfa.html

class A: Base { override func f() {} }
来源：http://dali.snrcjt.cn/Article/details/gtgddbppyg.html

[T27] Swift：错误处理
来源：http://dali.aizwys.cn/Article/details/gtgrrzvpek.html

do { try f() } catch { print(error) }
来源：http://dali.pengpengdd.cyou/Article/details/gtvmklnaua.html

[T28] Swift：枚举
来源：http://dali.cucudq.cn/Article/details/gtspwkiwvh.html

enum Color { case red, green }
来源：http://dali.nwbrower.top/Article/details/gtullwgrvg.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtfeyfmhdz.html

guard let x = opt else { return }
来源：http://dali.xylfe.cn/Article/details/gtpmfujkba.html

[T30] Swift：协议
来源：http://dali.havefunace.top/Article/details/gtwgrygtqg.html

protocol Shape { func area() -> Double }
来源：http://dali.quarkkingdee.top/Article/details/gtqsrcohit.html

[T31] Lua：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlpycsul.html

print("Hello")
来源：http://dali.andypj.xyz/Article/details/gtfnytuyyb.html

[T32] Lua：局部变量
来源：http://dali.chenlongwang.top/Article/details/gtfaayddzm.html

local a = 1
来源：http://dali.jyoumei.cn/Article/details/gtfyvmwipf.html

[T33] Lua：表（数组）
来源：http://dali.jlsjyb.cn/Article/details/gtwdkajkcb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnqzz.top/Article/details/gtxcyhumij.html

[T34] Lua：遍历表
来源：http://dali.316326.xyz/Article/details/gtjxcxlfmw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.smart0.xyz/Article/details/gtnvjxspze.html

[T35] Lua：字典表
来源：http://dali.tanke756.top/Article/details/gtqhlzpwbp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zdqjudy.top/Article/details/gtgbypenfj.html

[T36] Lua：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtfcdkayss.html

function add(a, b) return a + b end
来源：http://dali.gogol.net.cn/Article/details/gtbefxayph.html

[T37] Lua：字符串拼接
来源：http://dali.zdqjudy.top/Article/details/gtrzmowqlg.html

"a" .. "b"
来源：http://dali.xuetiantiany.cn/Article/details/gtatwdeuzt.html

[T38] Lua：条件
来源：http://dali.meibo888.top/Article/details/gtwnvrshns.html

if x > 0 then print("正") end
来源：http://dali.nanxinkj.top/Article/details/gtnqrprjjz.html

[T39] Lua：模式匹配
来源：http://dali.havefunace.top/Article/details/gtjporvhbu.html

string.find(s, "%d+")
来源：http://dali.gotoacloud.top/Article/details/gtkyfitpqm.html

[T40] Lua：元表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqrathoj.html

setmetatable({}, { __index = base })
来源：http://dali.hammf.cn/Article/details/gtowimuwbz.html

[T41] Perl：Hello World
来源：http://dali.hammf.cn/Article/details/gtpopykcoj.html

print "Hello\n";
来源：http://dali.yj20258888.top/Article/details/gthvmkzdwn.html

[T42] Perl：变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddxdwnip.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jiagoushi.top/Article/details/gtkmxgjdhc.html

[T43] Perl：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwybykcu.html

"值: $a"
来源：http://dali.hfpthk.cn/Article/details/gtakqskhum.html

[T44] Perl：条件
来源：http://dali.snrcjt.cn/Article/details/gtvzojuwdn.html

if ($a > 0) { print "正"; }
来源：http://dali.xziqi.cn/Article/details/gtjrtozaxy.html

[T45] Perl：数组遍历
来源：http://dali.pycfn.com/Article/details/gtfpywscgy.html

for my $x (@arr) { print $x; }
来源：http://dali.jianghu66.top/Article/details/gtdxaaumoh.html

[T46] Perl：哈希操作
来源：http://dali.wangdashe.top/Article/details/gtkkqaeuym.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jlsjyb.cn/Article/details/gtwfgxwwrj.html

[T47] Perl：正则捕获
来源：http://dali.meibo888.top/Article/details/gteysgydws.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ydzc1.top/Article/details/gtkbpbjbrl.html

[T48] Perl：正则替换
来源：http://dali.jqgfzy.top/Article/details/gtxdqinreh.html

$s =~ s/old/new/g;
来源：http://dali.shuidangran.top/Article/details/gtqsafdokl.html

[T49] Perl：函数
来源：http://dali.shzxlz.cn/Article/details/gthsebjkqa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtutdcqzoj.html

[T50] Perl：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtyazayfrz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgufenzy.top/Article/details/gtlbskqydx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.kuanghao11.cn/Article/details/gtdfizafdt.html

[T51] Scala：Hello World
来源：http://dali.andypj.xyz/Article/details/gtqysrgcri.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gtewrzaqlq.html

[T52] Scala：变量
来源：http://dali.hywenlv.cn/Article/details/gtroourqcf.html

val a = 1;  var b = 2
来源：http://dali.nanxinkj.top/Article/details/gtgfqgwjxf.html

[T53] Scala：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtauhuacpj.html

s"值: $b"
来源：http://dali.xinyue.icu/Article/details/gtvrlmyuzy.html

[T54] Scala：集合映射
来源：http://dali.tanke756.top/Article/details/gtrdysgdlg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtzgngqltv.html

[T55] Scala：集合过滤
来源：http://dali.xziqi.cn/Article/details/gtstltbfya.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxuanxn.top/Article/details/gtmvvxblel.html

[T56] Scala：样例类
来源：http://dali.shuidangran.top/Article/details/gtornkbaou.html

case class User(name: String, age: Int)
来源：http://dali.fengsongda.top/Article/details/gtakdajqxd.html

[T57] Scala：模式匹配
来源：http://dali.guowangkeji.top/Article/details/gtmdhmadfr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgffvtse.html

[T58] Scala：函数定义
来源：http://dali.sweek.top/Article/details/gtcfrntemx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hywenlv.cn/Article/details/gtsqoktblz.html

[T59] Scala：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgpbxkkb.html

for (i <- 1 to 10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gtmimizqzi.html

[T60] Scala：折叠
来源：http://dali.hammf.cn/Article/details/gtoafrkwva.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.kuanghao11.cn/Article/details/gtjmdpmcjm.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjuhhlocb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258.top/Article/details/gtqgkpyssm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtnrjayjrt.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxuanxn.top/Article/details/gtojsbvpae.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.birdmap.top/Article/details/gtlttmdvuq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fzhhl.top/Article/details/gtycccikcu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhoulong.xyz/Article/details/gtkisvquro.html

[U03] Py：加载 .env 配置
来源：http://dali.zhongyouzk.top/Article/details/gtowsycoky.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jiagoushi.top/Article/details/gtcdqllzit.html

[U04] Py：变量调试打印
来源：http://dali.jiagoushi.top/Article/details/gtbhjrgezx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ivvv.top/Article/details/gtihibgoyj.html

[U05] Py：列表去重且保序
来源：http://dali.sufxvd.cn/Article/details/gtbwlibisx.html

list(dict.fromkeys(arr))
来源：http://dali.0kj1m.cn/Article/details/gtreldbnmc.html

[U06] Py：合并两个字典
来源：http://dali.kuanghao11.cn/Article/details/gtzfepqhww.html

{**a, **b}
来源：http://dali.bjfxy.top/Article/details/gthgszjoge.html

[U07] Py：反转字典键值
来源：http://dali.havefunace.top/Article/details/gtizwkwgrc.html

{v: k for k, v in d.items()}
来源：http://dali.nwbrower.top/Article/details/gtkqjfhnlw.html

[U08] Py：展平二维列表
来源：http://dali.chenzaomai.com/Article/details/gtmyaqlmvc.html

[y for x in nested for y in x]
来源：http://dali.tianlin.xyz/Article/details/gtivqqwlin.html

[U09] Py：字典取最大值的键
来源：http://dali.fengsongda.top/Article/details/gtbvjrzoma.html

max(d, key=d.get)
来源：http://dali.xylfe.cn/Article/details/gtgpmlcklt.html

[U10] Py：按值排序字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzqcpqah.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.meibo888.top/Article/details/gtbcqwrghe.html

[U11] Py：生成器表达式
来源：http://dali.xuetiantiany.cn/Article/details/gthogoccwa.html

(x * 2 for x in arr)
来源：http://dali.cqqwz.cn/Article/details/gtschhxmvy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.smart0.xyz/Article/details/gtnrlmdwfm.html

Counter(arr).most_common(3)
来源：http://dali.kuanghao11.cn/Article/details/gtkallptii.html

[U13] Py：固定长度队列
来源：http://dali.xuanzx.com/Article/details/gtztnbywkw.html

deque(maxlen=10)
来源：http://dali.zhongyouzk.top/Article/details/gtbvaimfaa.html

[U14] Py：分组收集到列表
来源：http://dali.zhiwuduotai.top/Article/details/gttqyxegky.html

defaultdict(list)
来源：http://dali.yanxiufei.cn/Article/details/gtriovdidg.html

[U15] Py：高精度计时
来源：http://dali.zdqjudy.top/Article/details/gtizsrrnwa.html

t = time.perf_counter()
来源：http://dali.wangdashe.top/Article/details/gtlmznwiyk.html

[U16] Py：命令行参数解析
来源：http://dali.xziqi.cn/Article/details/gtaatwjklw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.wangshuangyany.cn/Article/details/gtrlycbihk.html

[U17] Py：初始化日志
来源：http://dali.zycfv.cn/Article/details/gtlhcdyszv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggittsgh.html

[U18] Py：预编译正则
来源：http://dali.shzxlz.cn/Article/details/gtiaqzlota.html

pat = re.compile(r"\d+")
来源：http://dali.gogol.net.cn/Article/details/gtbvhotela.html

[U19] Py：正则替换带回调
来源：http://dali.chenlongwang.top/Article/details/gtkwzcbqxc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.meibo888.top/Article/details/gtzddemqxf.html

[U20] Py：缓存函数结果
来源：http://dali.tanke756.top/Article/details/gtmlvjjwpd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jianghu66.top/Article/details/gtfphbsuxh.html

[U21] Py：自定义上下文管理器
来源：http://dali.jqgfzy.top/Article/details/gtpfhybsdz.html

@contextlib.contextmanager
来源：http://dali.hnxiangtu.top/Article/details/gtsvjxmwtv.html

[U22] Py：矩阵转置
来源：http://dali.c1oappe.top/Article/details/gtrhwlwdti.html

list(zip(*m))
来源：http://dali.xylfe.cn/Article/details/gtncqludml.html


<!-- 参考信息 -->