代发 wailian999

S. C / C++ 专题
来源：http://dali.jqgfzy.top/Article/details/gtlrhdicqn.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gteppuhawl.html

[S01] C：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtqxltswni.html

#include <stdio.h>
来源：http://dali.haohaochexian.top/Article/details/gtedxkwtlu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.bjfxy.top/Article/details/gtxjlikmae.html

[S02] C：变量与格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtnbzrzyyx.html

int a = 10; printf("%d\n", a);
来源：http://dali.pycfn.com/Article/details/gthfucaxei.html

[S03] C：读入整数
来源：http://dali.hywenlv.cn/Article/details/gtkqwyrtgz.html

int x; scanf("%d", &x);
来源：http://dali.tian-w.cn/Article/details/gtanqqnoxc.html

[S04] C：字符串复制
来源：http://dali.0kj1m.cn/Article/details/gtonjkravl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.meibo888.top/Article/details/gtrgsqvcml.html

[S05] C：字符串长度
来源：http://dali.nanxinkj.top/Article/details/gtetckggaa.html

strlen(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtmvtnkskq.html

[S06] C：字符串比较
来源：http://dali.chenlongwang.top/Article/details/gtsqmqrely.html

strcmp(a, b) == 0
来源：http://dali.nanxinkj.top/Article/details/gtatxjvvvk.html

[S07] C：数组遍历求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqzlkkej.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cashguo.top/Article/details/gtbcubbpvv.html

[S08] C：动态内存分配与释放
来源：http://dali.ehwqpu.com/Article/details/gtfynjowke.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cashguo.top/Article/details/gtejgntqtz.html

[S09] C：结构体定义与初始化
来源：http://dali.smart0.xyz/Article/details/gtceagajzy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sweek.top/Article/details/gtwktrvmrv.html

[S10] C：指针与解引用
来源：http://dali.316326.xyz/Article/details/gtikjcglig.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcoaamwns.html

[S11] C：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtgmtvlbgo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hfpthk.cn/Article/details/gtflaukfvn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sysykeji.top/Article/details/gtqvzitpfy.html

fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gtvvedzylh.html

[S12] C：写文件
来源：http://dali.fzhhl.top/Article/details/gtocaxgzkt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hongshengwenyu.top/Article/details/gtnbeqsyav.html

[S13] C：宏定义
来源：http://dali.hysaishi.cn/Article/details/gtrxpofstw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.haohaochexian.top/Article/details/gtpsgfztcb.html

[S14] C：枚举
来源：http://dali.hywenlv.cn/Article/details/gtpgxunkxx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenlongwang.top/Article/details/gtdaswsrta.html

[S15] C：类型转换
来源：http://dali.hfpthk.cn/Article/details/gtmozqzilr.html

(double) a / b
来源：http://dali.shuidangran.top/Article/details/gtyzrzoord.html

[S16] C：位操作置位
来源：http://dali.cashguo.top/Article/details/gtsvhtfkcc.html

x |= (1 << 3);
来源：http://dali.jyoumei.cn/Article/details/gtctejhakj.html

[S17] C：安全拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtesnyxndj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daxiang520.top/Article/details/gtpxqknpcc.html

[S18] C：命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtwjjnogqm.html

int main(int argc, char **argv)
来源：http://dali.zhongyouzk.top/Article/details/gtvkadeixk.html

[S19] C：快速排序
来源：http://dali.yj20258.top/Article/details/gtfyddwrfp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gtlcfakkno.html

[S20] C：二分查找
来源：http://dali.smart0.xyz/Article/details/gtpvdecidm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gtlymcphkw.html

[S21] C：字符类别判断
来源：http://dali.redwolf501.top/Article/details/gtbsrpozbs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gotoacloud.top/Article/details/gtyjlevgdb.html

[S22] C：字符串转数字
来源：http://dali.jqgufenzy.top/Article/details/gthqsripbh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cashguo.top/Article/details/gtuowyztjo.html

[S23] C：随机数
来源：http://dali.jqgufenzy.top/Article/details/gtsbvrbocw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gotoacloud.top/Article/details/gtaldyyazo.html

[S24] C：获取本地时间
来源：http://dali.yj20258888.top/Article/details/gtckselfei.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shangyingyoupin.top/Article/details/gtvcdpadre.html

[S25] C：内存拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtbskcnvgt.html

memcpy(dst, src, n);
来源：http://dali.yongpay.top/Article/details/gtvtvegfkp.html

[S26] C：内存清零
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunlkcbko.html

memset(a, 0, sizeof a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejrtkkko.html

[S27] C：定义常量
来源：http://dali.yvedp.cn/Article/details/gtouujsmtk.html

const double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtxjbrczwf.html

[S28] C：静态变量
来源：http://dali.andypj.xyz/Article/details/gtaywqgudn.html

static int counter = 0;
来源：http://dali.wangshuangyany.cn/Article/details/gtdvdydsdz.html

[S29] C：变参函数
来源：http://dali.yanxiufei.cn/Article/details/gtfpdnqegt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfifthnft.html

[S30] C：头文件保护
来源：http://dali.yj20258888.top/Article/details/gtglybvsoz.html

#ifndef X_H
来源：http://dali.dashuyun.cn/Article/details/gtnbczzduh.html

#define X_H
来源：http://dali.0kj1m.cn/Article/details/gtkdmseglo.html

#endif
来源：http://dali.andypj.xyz/Article/details/gtzlybzvhv.html

[S31] C++：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtiyrqdahv.html

#include <iostream>
来源：http://dali.yuxming.cn/Article/details/gtjqmjauix.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cdnleiting.top/Article/details/gtdeieytjg.html

[S32] C++：字符串
来源：http://dali.quarkkingdee.top/Article/details/gtsqdfkdho.html

std::string s = "hi";  s += "!";
来源：http://dali.cheryme.top/Article/details/gtbzaaeodm.html

[S33] C++：vector 增删
来源：http://dali.ehwqpu.com/Article/details/gtjewdcinn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.0kj1m.cn/Article/details/gtzijqaebo.html

[S34] C++：遍历 vector
来源：http://dali.gaohongyu789.top/Article/details/gtolkpkayr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guowangkeji.top/Article/details/gtxnjjoyrt.html

[S35] C++：map
来源：http://dali.guowangkeji.top/Article/details/gtbuuzhnkr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkebaopo.html

[S36] C++：unordered_map
来源：http://dali.hfpthk.cn/Article/details/gtnltgaxzt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtrrqjrgvi.html

[S37] C++：set
来源：http://dali.sweek.top/Article/details/gtiysdyupc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cucudq.cn/Article/details/gtncyojmgs.html

[S38] C++：排序
来源：http://dali.vqdsnc.cn/Article/details/gtjmogwulv.html

std::sort(v.begin(), v.end());
来源：http://dali.pycfn.com/Article/details/gtzebbcmsq.html

[S39] C++：自定义比较器排序
来源：http://dali.haohaochexian.top/Article/details/gtcitoppfr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jyoumei.cn/Article/details/gtmmerrofr.html

[S40] C++：查找元素
来源：http://dali.yangfankeji.com/Article/details/gtklbgpaui.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakgtwdld.html

[S41] C++：类与构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtjmpeamsq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tianlin.xyz/Article/details/gtmmwgjawu.html

[S42] C++：继承与虚函数
来源：http://dali.snrcjt.cn/Article/details/gtdlzpxqms.html

class B : public Base { public: void f() override {} };
来源：http://dali.yonumen.top/Article/details/gtyiuormdf.html

[S43] C++：智能指针
来源：http://dali.fzhhl.top/Article/details/gthtmswpxq.html

auto p = std::make_unique<int>(5);
来源：http://dali.dianchejie.cn/Article/details/gtiypwysxq.html

[S44] C++：引用传参
来源：http://dali.kuanghao11.cn/Article/details/gtcfxgtydq.html

void inc(int &x) { ++x; }
来源：http://dali.yuxming.cn/Article/details/gtkqosmvxl.html

[S45] C++：lambda
来源：http://dali.cqqwz.cn/Article/details/gtidrbajag.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.vqdsnc.cn/Article/details/gtguxnsamh.html

[S46] C++：函数模板
来源：http://dali.mhx1999.top/Article/details/gtidynbdqc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.smart0.xyz/Article/details/gtuthrpmvv.html

[S47] C++：结构化绑定遍历
来源：http://dali.dashuyun.cn/Article/details/gtcijwcamj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutatghfu.html

[S48] C++：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtmucqtezw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhongyouzk.top/Article/details/gthterfbqe.html

while (std::getline(in, line)) { }
来源：http://dali.chenlongwang.top/Article/details/gtncaqmsnh.html

[S49] C++：写文件
来源：http://dali.sysykeji.top/Article/details/gtllxuatsl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xylfe.cn/Article/details/gtuyiubwcc.html

[S50] C++：格式化数字
来源：http://dali.birdmap.top/Article/details/gtzkklhpfo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtcxuxnkwj.html

[S51] C++：显式类型转换
来源：http://dali.jyoumei.cn/Article/details/gtbfxxlgsr.html

static_cast<double>(a) / b
来源：http://dali.hnqzz.top/Article/details/gtzqkqfaht.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gtnyhovkgu.html

int size() const noexcept { return n_; }
来源：http://dali.yuanzhike.top/Article/details/gtmpmdawar.html

[S53] C++：移动语义
来源：http://dali.guowangkeji.top/Article/details/gtsfcvgrgd.html

std::vector<int> w = std::move(v);
来源：http://dali.gaohongyu789.top/Article/details/gtubflokqa.html

[S54] C++：异常处理
来源：http://dali.fengsongda.top/Article/details/gtkkwaditq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sxryk.cn/Article/details/gtudvnmnnd.html

[S55] C++：结构化绑定
来源：http://dali.sysykeji.top/Article/details/gtpxzhzgyu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gtekuzxstl.html

[S56] C++：optional
来源：http://dali.snrcjt.cn/Article/details/gtiwsjmwod.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.9152youxi.cn/Article/details/gtqrlhwzco.html

[S57] C++：编译期常量
来源：http://dali.ydzc1.top/Article/details/gtamxcqimf.html

constexpr int N = 10;
来源：http://dali.sufxvd.cn/Article/details/gtizktmfmq.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gtvzrhqbqa.html

namespace ns { int f() { return 1; } }
来源：http://dali.c1oappe.top/Article/details/gtgmnqbvht.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtufvwdttk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jiagoushi.top/Article/details/gtimwriaky.html

[S60] C++：遍历并删除元素
来源：http://dali.daxiang520.top/Article/details/gttsksooul.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuanzx.com/Article/details/gtuuucasra.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtkwommjui.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xziqi.cn/Article/details/gtnevzfyoz.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtrgtovbqn.html

[T01] Kotlin：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtryffrsxk.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gtnnrxujyk.html

[T02] Kotlin：变量
来源：http://dali.kuanghao11.cn/Article/details/gtexyyrttb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.iojbl.cn/Article/details/gtgnesbzia.html

[T03] Kotlin：字符串模板
来源：http://dali.zhiwuduotai.top/Article/details/gthsbkoxgw.html

"值: $b"
来源：http://dali.hnxiangtu.top/Article/details/gtwlwtcpwn.html

[T04] Kotlin：空安全
来源：http://dali.jinqigufen.top/Article/details/gtupnbjulw.html

val n: String? = null;  n?.length
来源：http://dali.svipenyu.cn/Article/details/gtthluamxp.html

[T05] Kotlin：when 表达式
来源：http://dali.shzxlz.cn/Article/details/gtwblwsgmc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.andypj.xyz/Article/details/gtochotqvs.html

[T06] Kotlin：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gtucpxhdrg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guannengcc.top/Article/details/gtskutmfbo.html

[T07] Kotlin：集合过滤
来源：http://dali.0kj1m.cn/Article/details/gtuedhpjxy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yonumen.top/Article/details/gtquyvomtc.html

[T08] Kotlin：数据类
来源：http://dali.ydzc1.top/Article/details/gtkwspfppa.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gtxwskkdvw.html

[T09] Kotlin：扩展函数
来源：http://dali.gzhubu.top/Article/details/gttbpibezi.html

fun String.exclaim() = this + "!"
来源：http://dali.yongpay.top/Article/details/gtmfxeksmj.html

[T10] Kotlin：默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyicymnkd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.c1oappe.top/Article/details/gthbdsfuai.html

[T11] Kotlin：协程
来源：http://dali.guowangkeji.top/Article/details/gtwjoguhws.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hysaishi.cn/Article/details/gtyjyvevug.html

[T12] Kotlin：解构声明
来源：http://dali.c1oappe.top/Article/details/gtpjiqynoq.html

val (a, b) = Pair(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtkggbctyz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gtbzrtcqvr.html

val m = mapOf("a" to 1)
来源：http://dali.kuanghao11.cn/Article/details/gtbwiupdtf.html

[T14] Kotlin：循环
来源：http://dali.zhoulong.xyz/Article/details/gtiqbndrby.html

for (i in 1..10) println(i)
来源：http://dali.pycfn.com/Article/details/gthcoxvhje.html

[T15] Kotlin：接口
来源：http://dali.wangdashe.top/Article/details/gtfijuirld.html

interface Shape { fun area(): Double }
来源：http://dali.cashguo.top/Article/details/gtqypffiqq.html

[T16] Swift：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtyrpbklwm.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gtkcjfoxyb.html

[T17] Swift：变量与常量
来源：http://dali.0kj1m.cn/Article/details/gtxiczeorh.html

var a = 1;  let b = 2
来源：http://dali.shzxlz.cn/Article/details/gtpvgeqahe.html

[T18] Swift：字符串插值
来源：http://dali.ydzc1.top/Article/details/gtkxuqewji.html

"值: \(b)"
来源：http://dali.gogol.net.cn/Article/details/gteavhfdnl.html

[T19] Swift：可选绑定
来源：http://dali.havefunace.top/Article/details/gtvcccbooe.html

if let n = opt { print(n) }
来源：http://dali.yj20258.top/Article/details/gtqvjmzruo.html

[T20] Swift：数组操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebzmouvd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nwbrower.top/Article/details/gttluayeao.html

[T21] Swift：遍历
来源：http://dali.tian-w.cn/Article/details/gtikjfvzcz.html

for x in a { print(x) }
来源：http://dali.hnqzz.top/Article/details/gtioztuwru.html

[T22] Swift：字典
来源：http://dali.zdqjudy.top/Article/details/gtbdcypbfq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gaohongyu789.top/Article/details/gtyatykmwl.html

[T23] Swift：函数
来源：http://dali.sxryk.cn/Article/details/gtgvbjjwnf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daria6918.cn/Article/details/gtbegleean.html

[T24] Swift：闭包
来源：http://dali.mhx1999.top/Article/details/gtzssjrxsd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yonumen.top/Article/details/gtqrlwmxal.html

[T25] Swift：结构体
来源：http://dali.nanxuanxn.top/Article/details/gtmrmvurhv.html

struct P { var x: Int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmdfphkg.html

[T26] Swift：类与重写
来源：http://dali.snrcjt.cn/Article/details/gtfohvruuq.html

class A: Base { override func f() {} }
来源：http://dali.quarkkingdee.top/Article/details/gtttnxdzck.html

[T27] Swift：错误处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnqelvie.html

do { try f() } catch { print(error) }
来源：http://dali.zhixingplan.top/Article/details/gtssukkyit.html

[T28] Swift：枚举
来源：http://dali.chenzaomai.com/Article/details/gttnwawpnu.html

enum Color { case red, green }
来源：http://dali.sweek.top/Article/details/gtjmslbcik.html

[T29] Swift：guard 提前返回
来源：http://dali.wangdashe.top/Article/details/gtnqexmxcc.html

guard let x = opt else { return }
来源：http://dali.daria6918.cn/Article/details/gtheodravd.html

[T30] Swift：协议
来源：http://dali.gzhubu.top/Article/details/gtlmdajzgr.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigfzy.top/Article/details/gtpbpgxaco.html

[T31] Lua：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtdusgxizw.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqrsprjj.html

[T32] Lua：局部变量
来源：http://dali.svipenyu.cn/Article/details/gtgvarkzln.html

local a = 1
来源：http://dali.kuanghao11.cn/Article/details/gtimdiafyj.html

[T33] Lua：表（数组）
来源：http://dali.hnqzz.top/Article/details/gtcfminelb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yanxiufei.cn/Article/details/gtdieoixwn.html

[T34] Lua：遍历表
来源：http://dali.iojbl.cn/Article/details/gteuonalvs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pycfn.com/Article/details/gtezclbltu.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gtdilipsui.html

local d = { a = 1 };  d.b = 2
来源：http://dali.birdmap.top/Article/details/gtoqvisxdn.html

[T36] Lua：函数
来源：http://dali.ydzc1.top/Article/details/gtpnzdvpea.html

function add(a, b) return a + b end
来源：http://dali.chenzaomai.com/Article/details/gtakgywsts.html

[T37] Lua：字符串拼接
来源：http://dali.xylfe.cn/Article/details/gtuwygsuhl.html

"a" .. "b"
来源：http://dali.zhoulong.xyz/Article/details/gtmdrbylvr.html

[T38] Lua：条件
来源：http://dali.xziqi.cn/Article/details/gtsbxpvoie.html

if x > 0 then print("正") end
来源：http://dali.0kj1m.cn/Article/details/gtkgkaritz.html

[T39] Lua：模式匹配
来源：http://dali.xziqi.cn/Article/details/gtcjgxiggf.html

string.find(s, "%d+")
来源：http://dali.zhixingplan.top/Article/details/gtmdrrnmql.html

[T40] Lua：元表
来源：http://dali.yangfankeji.com/Article/details/gtdpsxrssb.html

setmetatable({}, { __index = base })
来源：http://dali.yueranfly.top/Article/details/gtzjlfvraa.html

[T41] Perl：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtpqffdbmk.html

print "Hello\n";
来源：http://dali.chenjidiqi.icu/Article/details/gtrzupakqy.html

[T42] Perl：变量类型
来源：http://dali.jiagoushi.top/Article/details/gtfkowzbhn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabaxmiau.html

[T43] Perl：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtobotyumt.html

"值: $a"
来源：http://dali.0kj1m.cn/Article/details/gtmbgdcjuj.html

[T44] Perl：条件
来源：http://dali.zhixingplan.top/Article/details/gtaytqsaby.html

if ($a > 0) { print "正"; }
来源：http://dali.zdqjudy.top/Article/details/gtjxvznaky.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldqqsord.html

for my $x (@arr) { print $x; }
来源：http://dali.0kj1m.cn/Article/details/gtuhzbkcgx.html

[T46] Perl：哈希操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrpozoep.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sweek.top/Article/details/gttouvqozk.html

[T47] Perl：正则捕获
来源：http://dali.feifeiyinyue.top/Article/details/gtaaodirze.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolyxgder.html

[T48] Perl：正则替换
来源：http://dali.jinqigufen.top/Article/details/gtsvrmvihf.html

$s =~ s/old/new/g;
来源：http://dali.birdmap.top/Article/details/gtxsugkeyx.html

[T49] Perl：函数
来源：http://dali.dianchejie.cn/Article/details/gtwiketenq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtgobduxka.html

[T50] Perl：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtjuqcpkmp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hfpthk.cn/Article/details/gtmlxielqi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuanzhike.top/Article/details/gtflmkdoyj.html

[T51] Scala：Hello World
来源：http://dali.birdmap.top/Article/details/gtamriacsh.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gtwkcypxoq.html

[T52] Scala：变量
来源：http://dali.yongpay.top/Article/details/gtxtgrtnta.html

val a = 1;  var b = 2
来源：http://dali.c1oappe.top/Article/details/gtstvtjjcd.html

[T53] Scala：字符串插值
来源：http://dali.ivvv.top/Article/details/gthzpdirjm.html

s"值: $b"
来源：http://dali.dianchejie.cn/Article/details/gtakpjmmkc.html

[T54] Scala：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gtyrjkrcjn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.9152youxi.cn/Article/details/gttelcadih.html

[T55] Scala：集合过滤
来源：http://dali.andypj.xyz/Article/details/gtgaptrxma.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpqogyto.html

[T56] Scala：样例类
来源：http://dali.hongshengwenyu.top/Article/details/gtkocgwrre.html

case class User(name: String, age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnnnpbnd.html

[T57] Scala：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtgejulaug.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtojroxxbr.html

[T58] Scala：函数定义
来源：http://dali.nanxuanxn.top/Article/details/gterosdahu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ehwqpu.com/Article/details/gtmfbutwjf.html

[T59] Scala：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrzmpbfv.html

for (i <- 1 to 10) println(i)
来源：http://dali.bjfxy.top/Article/details/gtagbnaizb.html

[T60] Scala：折叠
来源：http://dali.guannengcc.top/Article/details/gtherqftif.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.fzhhl.top/Article/details/gtycjisfyj.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtahmdggti.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.meibo888.top/Article/details/gtrciashbl.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtxumbkjzr.html

[U01] Py：创建虚拟环境
来源：http://dali.feifeiyinyue.top/Article/details/gtcbmmppwa.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinqigfzy.top/Article/details/gtirmylkjt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.snrcjt.cn/Article/details/gtbqbdudfe.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guannengcc.top/Article/details/gtewtlfqif.html

[U03] Py：加载 .env 配置
来源：http://dali.hnxiangtu.top/Article/details/gtkwlfsiwb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhongyouzk.top/Article/details/gtmhrgqver.html

[U04] Py：变量调试打印
来源：http://dali.ivvv.top/Article/details/gtoybebqkn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenjidiqi.icu/Article/details/gtdrotgdes.html

[U05] Py：列表去重且保序
来源：http://dali.zhiwuduotai.top/Article/details/gtnptwpgzb.html

list(dict.fromkeys(arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwsnvwxd.html

[U06] Py：合并两个字典
来源：http://dali.yonumen.top/Article/details/gtssftajqi.html

{**a, **b}
来源：http://dali.yangfankeji.com/Article/details/gtqadjskka.html

[U07] Py：反转字典键值
来源：http://dali.xylfe.cn/Article/details/gtmeksbaik.html

{v: k for k, v in d.items()}
来源：http://dali.shangyingyoupin.top/Article/details/gtggdocyxn.html

[U08] Py：展平二维列表
来源：http://dali.pengpengdd.cyou/Article/details/gtplixhngv.html

[y for x in nested for y in x]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijodvqfg.html

[U09] Py：字典取最大值的键
来源：http://dali.wangshuangyany.cn/Article/details/gtvdrfecvp.html

max(d, key=d.get)
来源：http://dali.shuidangran.top/Article/details/gtslahmkjp.html

[U10] Py：按值排序字典
来源：http://dali.zhongyouzk.top/Article/details/gthtnmjqnp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yongpay.top/Article/details/gtlipkxjyj.html

[U11] Py：生成器表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfpbvzae.html

(x * 2 for x in arr)
来源：http://dali.xuanzx.com/Article/details/gtukurachn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.quarkkingdee.top/Article/details/gtwzucdolc.html

Counter(arr).most_common(3)
来源：http://dali.c1oappe.top/Article/details/gtundjbmoj.html

[U13] Py：固定长度队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgpjtcnu.html

deque(maxlen=10)
来源：http://dali.zhoulong.xyz/Article/details/gtlygrmfel.html

[U14] Py：分组收集到列表
来源：http://dali.hammf.cn/Article/details/gtjolpxghy.html

defaultdict(list)
来源：http://dali.zhongyouzk.top/Article/details/gttabtrvpg.html

[U15] Py：高精度计时
来源：http://dali.shuidangran.top/Article/details/gtlaagzvpv.html

t = time.perf_counter()
来源：http://dali.havefunace.top/Article/details/gtvtoocpsb.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangtech.top/Article/details/gtndwomkaj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ivvv.top/Article/details/gttgikdetf.html

[U17] Py：初始化日志
来源：http://dali.svipenyu.cn/Article/details/gtnnyvecop.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.quarkkingdee.top/Article/details/gtgjnccbum.html

[U18] Py：预编译正则
来源：http://dali.jiagoushi.top/Article/details/gtbgleyocd.html

pat = re.compile(r"\d+")
来源：http://dali.yuxming.cn/Article/details/gtbazuidsb.html

[U19] Py：正则替换带回调
来源：http://dali.redwolf501.top/Article/details/gtdgrempah.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuanzhike.top/Article/details/gtacacbkul.html

[U20] Py：缓存函数结果
来源：http://dali.havefunace.top/Article/details/gtynfbbeed.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkoytfgsu.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj202588.top/Article/details/gtkifytjla.html

@contextlib.contextmanager
来源：http://dali.redwolf501.top/Article/details/gtlaluiowp.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gtcejukwap.html

list(zip(*m))
来源：http://dali.tianlin.xyz/Article/details/gtikolosuh.html


<!-- 参考信息 -->