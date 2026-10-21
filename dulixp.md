代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.iojbl.cn/Article/details/gtaiowikxh.html

[S02] C：变量与格式化输出
来源：http://dali.gzhubu.top/Article/details/gtfnewvyrr.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj202588.top/Article/details/gtzfgbedrw.html

[S03] C：读入整数
来源：http://dali.yanxiufei.cn/Article/details/gtklmtvobn.html

int x; scanf("%d", &x);
来源：http://dali.guowangkeji.top/Article/details/gtolfxouya.html

[S04] C：字符串复制
来源：http://dali.0kj1m.cn/Article/details/gtuswrrrfe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtcvwgggjx.html

[S05] C：字符串长度
来源：http://dali.gzhubu.top/Article/details/gtrunfrnam.html

strlen(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvrrjdmb.html

[S06] C：字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gttziaqrpz.html

strcmp(a, b) == 0
来源：http://dali.nanxuanxn.top/Article/details/gtfefhhihr.html

[S07] C：数组遍历求和
来源：http://dali.jqgfzy.top/Article/details/gtkvbokdje.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhongyouzk.top/Article/details/gteafmmtmq.html

[S08] C：动态内存分配与释放
来源：http://dali.pengpengdd.cyou/Article/details/gtpileqbsn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gogol.net.cn/Article/details/gtlovotrpb.html

[S09] C：结构体定义与初始化
来源：http://dali.hongshengwenyu.top/Article/details/gtntzuonzi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gzhubu.top/Article/details/gtumaewqqb.html

[S10] C：指针与解引用
来源：http://dali.birdmap.top/Article/details/gtdfcyrtod.html

int *p = &a;  *p = 5;
来源：http://dali.nanxinkj.top/Article/details/gtwfulvfbh.html

[S11] C：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtrmfkpdwx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.smart0.xyz/Article/details/gtpkoiazww.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhnodcbl.html

fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtccegweov.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gtqhbydtgm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzmcwqmt.html

[S13] C：宏定义
来源：http://dali.nanxinkj.top/Article/details/gtyhxwetwe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gtqhxccjlk.html

[S14] C：枚举
来源：http://dali.tianlin.xyz/Article/details/gtknklvyzu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbpgldcd.html

[S15] C：类型转换
来源：http://dali.0kj1m.cn/Article/details/gtohqqgnfi.html

(double) a / b
来源：http://dali.nanxinkj.top/Article/details/gthlhvcngl.html

[S16] C：位操作置位
来源：http://dali.0kj1m.cn/Article/details/gtvfnxyuuc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gtrohleehg.html

[S17] C：安全拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtyfsbylaf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gtqrqmblvu.html

[S18] C：命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gttdssegfj.html

int main(int argc, char **argv)
来源：http://dali.shuidangran.top/Article/details/gtebhrvfda.html

[S19] C：快速排序
来源：http://dali.guannengcc.top/Article/details/gtpekxjuuo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gtafsylaqy.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gtyuoddjhc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtppiejhhn.html

[S21] C：字符类别判断
来源：http://dali.nanxuanxn.top/Article/details/gtrivcmhkx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hysaishi.cn/Article/details/gtefnhlioj.html

[S22] C：字符串转数字
来源：http://dali.quarkkingdee.top/Article/details/gtttlxxrpv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gtasgdfair.html

[S23] C：随机数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemtqbyrh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.0kj1m.cn/Article/details/gtorzwxktn.html

[S24] C：获取本地时间
来源：http://dali.jlsjyb.cn/Article/details/gtsztwnpqs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuxming.cn/Article/details/gtapnrhqgq.html

[S25] C：内存拷贝
来源：http://dali.hammf.cn/Article/details/gtokzelcrb.html

memcpy(dst, src, n);
来源：http://dali.vqdsnc.cn/Article/details/gtnngltmrt.html

[S26] C：内存清零
来源：http://dali.zycfv.cn/Article/details/gtroujxjbq.html

memset(a, 0, sizeof a);
来源：http://dali.yj202588.top/Article/details/gtimlprvsp.html

[S27] C：定义常量
来源：http://dali.feifeiyinyue.top/Article/details/gtnnogudha.html

const double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtfjrwntxr.html

[S28] C：静态变量
来源：http://dali.ppjwa.cn/Article/details/gtxciopfwz.html

static int counter = 0;
来源：http://dali.ppjwa.cn/Article/details/gtrbyqghzr.html

[S29] C：变参函数
来源：http://dali.nwbrower.top/Article/details/gtesqmlnnm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnqzz.top/Article/details/gtraxlqhch.html

[S30] C：头文件保护
来源：http://dali.ydzc1.top/Article/details/gtigvpikxf.html

#ifndef X_H
来源：http://dali.svipenyu.cn/Article/details/gtlfiswdse.html

#define X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovvslvcf.html

#endif
来源：http://dali.mhx1999.top/Article/details/gtskqeyzyj.html

[S31] C++：Hello World
来源：http://dali.meibo888.top/Article/details/gtyuusplaj.html

#include <iostream>
来源：http://dali.jinqigufen.top/Article/details/gttwyjgeql.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cdnleiting.top/Article/details/gtdcdhltgo.html

[S32] C++：字符串
来源：http://dali.zycfv.cn/Article/details/gtkjczohik.html

std::string s = "hi";  s += "!";
来源：http://dali.meibo888.top/Article/details/gttxupplkp.html

[S33] C++：vector 增删
来源：http://dali.vqdsnc.cn/Article/details/gtyaxxjxkc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhoulong.xyz/Article/details/gtihnbqfvq.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gtkpeltklu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.meibo888.top/Article/details/gtogsjdpde.html

[S35] C++：map
来源：http://dali.jlsjyb.cn/Article/details/gtjquybgrj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtskcnxykj.html

[S36] C++：unordered_map
来源：http://dali.smart0.xyz/Article/details/gtiwblxpzg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtigrpcojk.html

[S37] C++：set
来源：http://dali.pengpengdd.cyou/Article/details/gtyhhmogje.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gtsunoksbx.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gtmloiorex.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gtaygbomep.html

[S39] C++：自定义比较器排序
来源：http://dali.c1oappe.top/Article/details/gtgxaavxik.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.kuanghao11.cn/Article/details/gtelezrjjd.html

[S40] C++：查找元素
来源：http://dali.aibaodan.cn/Article/details/gtsmehzrfg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.birdmap.top/Article/details/gtmkynntli.html

[S41] C++：类与构造函数
来源：http://dali.aizwys.cn/Article/details/gtisqfgfhn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cdnleiting.top/Article/details/gtogkjdbxf.html

[S42] C++：继承与虚函数
来源：http://dali.vqdsnc.cn/Article/details/gttvwirpuv.html

class B : public Base { public: void f() override {} };
来源：http://dali.jyoumei.cn/Article/details/gtetyvcwgr.html

[S43] C++：智能指针
来源：http://dali.smart0.xyz/Article/details/gtaginobvl.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangdashe.top/Article/details/gtkoaqhxid.html

[S44] C++：引用传参
来源：http://dali.yanxiufei.cn/Article/details/gtdqbeorco.html

void inc(int &x) { ++x; }
来源：http://dali.yueranfly.top/Article/details/gtbazvnkab.html

[S45] C++：lambda
来源：http://dali.pycfn.com/Article/details/gtpggrmvfh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ehwqpu.com/Article/details/gtawbqebxs.html

[S46] C++：函数模板
来源：http://dali.hongshengwenyu.top/Article/details/gtuaqejsil.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jiagoushi.top/Article/details/gtwwcipvsa.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacisdrvg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.bjfxy.top/Article/details/gtrnbftrto.html

[S48] C++：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtolcyqcri.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangshuangyany.cn/Article/details/gttavycclk.html

while (std::getline(in, line)) { }
来源：http://dali.andypj.xyz/Article/details/gthkainmca.html

[S49] C++：写文件
来源：http://dali.quarkkingdee.top/Article/details/gtcbakhgix.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nwbrower.top/Article/details/gtrpftbegl.html

[S50] C++：格式化数字
来源：http://dali.aizwys.cn/Article/details/gtjigwqodx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtyvdlhjal.html

[S51] C++：显式类型转换
来源：http://dali.daria6918.cn/Article/details/gtfmtgwnrq.html

static_cast<double>(a) / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphpfzczm.html

[S52] C++：const 与 noexcept
来源：http://dali.yonumen.top/Article/details/gtukykerlz.html

int size() const noexcept { return n_; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgivokbjj.html

[S53] C++：移动语义
来源：http://dali.ehwqpu.com/Article/details/gtvaftzpuk.html

std::vector<int> w = std::move(v);
来源：http://dali.zdqjudy.top/Article/details/gtkhbjgudo.html

[S54] C++：异常处理
来源：http://dali.9152youxi.cn/Article/details/gtvxmekofy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.9152youxi.cn/Article/details/gtebggqerj.html

[S55] C++：结构化绑定
来源：http://dali.pengpengdd.cyou/Article/details/gttceafmcx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shzxlz.cn/Article/details/gtcqfwpcan.html

[S56] C++：optional
来源：http://dali.316326.xyz/Article/details/gtvrzvuqxa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtllddbemb.html

[S57] C++：编译期常量
来源：http://dali.cdnleiting.top/Article/details/gtepwwbpyz.html

constexpr int N = 10;
来源：http://dali.haohaochexian.top/Article/details/gtkrqejudd.html

[S58] C++：命名空间
来源：http://dali.nanxuanxn.top/Article/details/gtnvpgwuef.html

namespace ns { int f() { return 1; } }
来源：http://dali.yongpay.top/Article/details/gtvzbjuaoi.html

[S59] C++：静态断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlrpmeoe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gogol.net.cn/Article/details/gtbqnefzah.html

[S60] C++：遍历并删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gtsiphgrmd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hammf.cn/Article/details/gtqrdjlrhq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtwifbxueq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gtbomearmc.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtembscokv.html

[T01] Kotlin：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtfwhzhhin.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtwqulxlnn.html

[T02] Kotlin：变量
来源：http://dali.guannengcc.top/Article/details/gtzcubdllg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxuanxn.top/Article/details/gtnbduuiiq.html

[T03] Kotlin：字符串模板
来源：http://dali.xuetiantiany.cn/Article/details/gthzgyfchi.html

"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuaxpjmtg.html

[T04] Kotlin：空安全
来源：http://dali.smart0.xyz/Article/details/gtqsjutjfs.html

val n: String? = null;  n?.length
来源：http://dali.cashguo.top/Article/details/gtbjxrhhpz.html

[T05] Kotlin：when 表达式
来源：http://dali.haohaochexian.top/Article/details/gtsgwirqvm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258888.top/Article/details/gtqysevdev.html

[T06] Kotlin：集合映射
来源：http://dali.fzhhl.top/Article/details/gtyyhgsxtm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszqafatg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gtbaudjrrw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ivvv.top/Article/details/gtyvctvkaa.html

[T08] Kotlin：数据类
来源：http://dali.ppjwa.cn/Article/details/gtdbkzogdd.html

data class User(val name: String, val age: Int)
来源：http://dali.jyoumei.cn/Article/details/gtmeaxesjt.html

[T09] Kotlin：扩展函数
来源：http://dali.ydzc1.top/Article/details/gtljmatxdp.html

fun String.exclaim() = this + "!"
来源：http://dali.haohaochexian.top/Article/details/gthtvmquvb.html

[T10] Kotlin：默认参数
来源：http://dali.guowangkeji.top/Article/details/gtdbhnelkh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yongpay.top/Article/details/gtwkxcwiqc.html

[T11] Kotlin：协程
来源：http://dali.guannengcc.top/Article/details/gtncsnaogv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.pycfn.com/Article/details/gtrwgmjmjr.html

[T12] Kotlin：解构声明
来源：http://dali.cheryme.top/Article/details/gtzhjuldcl.html

val (a, b) = Pair(1, 2)
来源：http://dali.birdmap.top/Article/details/gtjldoyssv.html

[T13] Kotlin：只读 Map
来源：http://dali.jiagoushi.top/Article/details/gtmkmbhyfk.html

val m = mapOf("a" to 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtoysmetdk.html

[T14] Kotlin：循环
来源：http://dali.cdnleiting.top/Article/details/gtosqgnqws.html

for (i in 1..10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gtghxvqzou.html

[T15] Kotlin：接口
来源：http://dali.ydzc1.top/Article/details/gtklhhwula.html

interface Shape { fun area(): Double }
来源：http://dali.hongshengwenyu.top/Article/details/gtfafyzvbe.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gttamlvtfp.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtlledcjho.html

[T17] Swift：变量与常量
来源：http://dali.redwolf501.top/Article/details/gtfbszcibp.html

var a = 1;  let b = 2
来源：http://dali.yj20258.top/Article/details/gtvtwobxyx.html

[T18] Swift：字符串插值
来源：http://dali.jianghu66.top/Article/details/gtornltfwk.html

"值: \(b)"
来源：http://dali.cucudq.cn/Article/details/gtxvgkotdn.html

[T19] Swift：可选绑定
来源：http://dali.iojbl.cn/Article/details/gtxnnefwgi.html

if let n = opt { print(n) }
来源：http://dali.hywenlv.cn/Article/details/gtgrhnidob.html

[T20] Swift：数组操作
来源：http://dali.dashuyun.cn/Article/details/gtumdvnonq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.bjfxy.top/Article/details/gtcmzewoer.html

[T21] Swift：遍历
来源：http://dali.jinqigufen.top/Article/details/gtfripffbo.html

for x in a { print(x) }
来源：http://dali.jqgfzy.top/Article/details/gtffrngcwz.html

[T22] Swift：字典
来源：http://dali.jyoumei.cn/Article/details/gtaqogncgs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nanxinkj.top/Article/details/gtdbsxmffl.html

[T23] Swift：函数
来源：http://dali.ivvv.top/Article/details/gtjupcqrek.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sxryk.cn/Article/details/gtjlczhnnq.html

[T24] Swift：闭包
来源：http://dali.zhiwuduotai.top/Article/details/gtpcgkqdjt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtiaaaevbq.html

[T25] Swift：结构体
来源：http://dali.hnqzz.top/Article/details/gtsdpuedqw.html

struct P { var x: Int }
来源：http://dali.yuanzhike.top/Article/details/gtmvqdspln.html

[T26] Swift：类与重写
来源：http://dali.zhongyouzk.top/Article/details/gtdqelttuk.html

class A: Base { override func f() {} }
来源：http://dali.andypj.xyz/Article/details/gttqxobtbo.html

[T27] Swift：错误处理
来源：http://dali.haohaochexian.top/Article/details/gtxzgqwcwd.html

do { try f() } catch { print(error) }
来源：http://dali.gogol.net.cn/Article/details/gtwznlczvx.html

[T28] Swift：枚举
来源：http://dali.sweek.top/Article/details/gtupjcakyk.html

enum Color { case red, green }
来源：http://dali.daxiang520.top/Article/details/gtlnjprpyq.html

[T29] Swift：guard 提前返回
来源：http://dali.yuxming.cn/Article/details/gtdkmbjyuf.html

guard let x = opt else { return }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqesfcyd.html

[T30] Swift：协议
来源：http://dali.feifeiyinyue.top/Article/details/gtfrfefgvq.html

protocol Shape { func area() -> Double }
来源：http://dali.daxiang520.top/Article/details/gtbkytenvz.html

[T31] Lua：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtrshzodgv.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gtbjrxakwr.html

[T32] Lua：局部变量
来源：http://dali.yj202588.top/Article/details/gtoiqzswnu.html

local a = 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtevdotjin.html

[T33] Lua：表（数组）
来源：http://dali.vqdsnc.cn/Article/details/gtfnryulvp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.smart0.xyz/Article/details/gtuztmehfq.html

[T34] Lua：遍历表
来源：http://dali.dashuyun.cn/Article/details/gtwqjvvbvi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnxiangtu.top/Article/details/gtyxvuuisy.html

[T35] Lua：字典表
来源：http://dali.pycfn.com/Article/details/gtwcdtwjij.html

local d = { a = 1 };  d.b = 2
来源：http://dali.daria6918.cn/Article/details/gtxytkttws.html

[T36] Lua：函数
来源：http://dali.ivvv.top/Article/details/gtdkyptean.html

function add(a, b) return a + b end
来源：http://dali.sysykeji.top/Article/details/gttaaoojsv.html

[T37] Lua：字符串拼接
来源：http://dali.316326.xyz/Article/details/gtqxxmqtha.html

"a" .. "b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqcyorey.html

[T38] Lua：条件
来源：http://dali.jinghuilouyu.cn/Article/details/gttcdfudwo.html

if x > 0 then print("正") end
来源：http://dali.cashguo.top/Article/details/gthbtvucxg.html

[T39] Lua：模式匹配
来源：http://dali.meibo888.top/Article/details/gtffxvbhol.html

string.find(s, "%d+")
来源：http://dali.xinyue.icu/Article/details/gtxptmhyrd.html

[T40] Lua：元表
来源：http://dali.wangshuangyany.cn/Article/details/gtkpqhqyww.html

setmetatable({}, { __index = base })
来源：http://dali.gaohongyu789.top/Article/details/gtdgoktcrc.html

[T41] Perl：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtquczsawl.html

print "Hello\n";
来源：http://dali.feifeiyinyue.top/Article/details/gtlavtduys.html

[T42] Perl：变量类型
来源：http://dali.shangyingyoupin.top/Article/details/gtlhlzbnft.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sufxvd.cn/Article/details/gteandpeyf.html

[T43] Perl：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtcrtxbnkl.html

"值: $a"
来源：http://dali.iojbl.cn/Article/details/gtmywcwwzl.html

[T44] Perl：条件
来源：http://dali.cdnleiting.top/Article/details/gtmytvyfrb.html

if ($a > 0) { print "正"; }
来源：http://dali.guowangkeji.top/Article/details/gtrfzfxngc.html

[T45] Perl：数组遍历
来源：http://dali.tanke756.top/Article/details/gtxoumcjsp.html

for my $x (@arr) { print $x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzmnyveu.html

[T46] Perl：哈希操作
来源：http://dali.cucudq.cn/Article/details/gttimkvikv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.kuanghao11.cn/Article/details/gttjgujtpa.html

[T47] Perl：正则捕获
来源：http://dali.bjfxy.top/Article/details/gtiwtssmls.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cqqwz.cn/Article/details/gtdlpcjswu.html

[T48] Perl：正则替换
来源：http://dali.nanxuanxn.top/Article/details/gtsmxyewoa.html

$s =~ s/old/new/g;
来源：http://dali.daria6918.cn/Article/details/gtibtjrrai.html

[T49] Perl：函数
来源：http://dali.chenjidiqi.icu/Article/details/gtpgklqeva.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtdiwqqewk.html

[T50] Perl：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtomeoovow.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sysykeji.top/Article/details/gthneawnal.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxuanxn.top/Article/details/gtbclpjwyc.html

[T51] Scala：Hello World
来源：http://dali.yueranfly.top/Article/details/gtmhnewwof.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gteisoapqx.html

[T52] Scala：变量
来源：http://dali.yanxiufei.cn/Article/details/gtujblhktb.html

val a = 1;  var b = 2
来源：http://dali.ppjwa.cn/Article/details/gtltwbzpxb.html

[T53] Scala：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gttxxhrbgg.html

s"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtqyskzkly.html

[T54] Scala：集合映射
来源：http://dali.meibo888.top/Article/details/gtfmgipmee.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmpefiek.html

[T55] Scala：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gtxlxqeblr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtabeuveyn.html

[T56] Scala：样例类
来源：http://dali.dashuyun.cn/Article/details/gtuucvmpux.html

case class User(name: String, age: Int)
来源：http://dali.haohaochexian.top/Article/details/gtteoraatj.html

[T57] Scala：模式匹配
来源：http://dali.yongpay.top/Article/details/gthybyifaa.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.daxiang520.top/Article/details/gtcqrzljtb.html

[T58] Scala：函数定义
来源：http://dali.jlsjyb.cn/Article/details/gtjuimihnh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guowangkeji.top/Article/details/gtffkezunm.html

[T59] Scala：循环
来源：http://dali.iojbl.cn/Article/details/gtakqpaxoj.html

for (i <- 1 to 10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gtltpdqdfo.html

[T60] Scala：折叠
来源：http://dali.0kj1m.cn/Article/details/gtndrqxnqw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hywenlv.cn/Article/details/gtzmxqdvle.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtugemjhmi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.guowangkeji.top/Article/details/gtwakmmhdm.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtvocoupux.html

[U01] Py：创建虚拟环境
来源：http://dali.jqgfzy.top/Article/details/gtsstdhfnd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinqigufen.top/Article/details/gtusmnslrn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.316326.xyz/Article/details/gtgdaalthv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj20258888.top/Article/details/gtmwobartz.html

[U03] Py：加载 .env 配置
来源：http://dali.chenzaomai.com/Article/details/gtmfjdtgof.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.havefunace.top/Article/details/gtputlqotd.html

[U04] Py：变量调试打印
来源：http://dali.sxryk.cn/Article/details/gtnmhrcnqa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pycfn.com/Article/details/gtmzokwvjy.html

[U05] Py：列表去重且保序
来源：http://dali.xuanzx.com/Article/details/gtrmjmbmur.html

list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gtpdkbwvlu.html

[U06] Py：合并两个字典
来源：http://dali.dashuyun.cn/Article/details/gthaikacis.html

{**a, **b}
来源：http://dali.nanxuanxn.top/Article/details/gtxsaoavrk.html

[U07] Py：反转字典键值
来源：http://dali.yongpay.top/Article/details/gtukxnwufl.html

{v: k for k, v in d.items()}
来源：http://dali.svipenyu.cn/Article/details/gtghchxizg.html

[U08] Py：展平二维列表
来源：http://dali.xziqi.cn/Article/details/gtbkeihqpc.html

[y for x in nested for y in x]
来源：http://dali.fengsongda.top/Article/details/gtffywcdoo.html

[U09] Py：字典取最大值的键
来源：http://dali.cashguo.top/Article/details/gtlilzyckf.html

max(d, key=d.get)
来源：http://dali.cdnleiting.top/Article/details/gtubrgdool.html

[U10] Py：按值排序字典
来源：http://dali.mhx1999.top/Article/details/gtozlkmwye.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.svipenyu.cn/Article/details/gtlyxnvkqe.html

[U11] Py：生成器表达式
来源：http://dali.c1oappe.top/Article/details/gtindfomho.html

(x * 2 for x in arr)
来源：http://dali.havefunace.top/Article/details/gtvvkpndbr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xinyue.icu/Article/details/gtvjvhnorh.html

Counter(arr).most_common(3)
来源：http://dali.guowangkeji.top/Article/details/gtstxopyls.html

[U13] Py：固定长度队列
来源：http://dali.hongshengwenyu.top/Article/details/gtjlwsrmqf.html

deque(maxlen=10)
来源：http://dali.ppjwa.cn/Article/details/gtbxlibxwe.html

[U14] Py：分组收集到列表
来源：http://dali.xuanzx.com/Article/details/gtsqgwrdjo.html

defaultdict(list)
来源：http://dali.yueranfly.top/Article/details/gtskoibhwn.html

[U15] Py：高精度计时
来源：http://dali.9152youxi.cn/Article/details/gtvoojvgvf.html

t = time.perf_counter()
来源：http://dali.dashuyun.cn/Article/details/gtnxmyfycu.html

[U16] Py：命令行参数解析
来源：http://dali.c1oappe.top/Article/details/gtgwgafpfd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hywenlv.cn/Article/details/gtbaktaxhk.html

[U17] Py：初始化日志
来源：http://dali.sweek.top/Article/details/gtvovbhffo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.havefunace.top/Article/details/gtmpcaxvob.html

[U18] Py：预编译正则
来源：http://dali.bjfxy.top/Article/details/gtpbrnbtol.html

pat = re.compile(r"\d+")
来源：http://dali.xuanzx.com/Article/details/gtbmpyaphu.html

[U19] Py：正则替换带回调
来源：http://dali.gogol.net.cn/Article/details/gtehrqlcmq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigfzy.top/Article/details/gtwmbgndrz.html

[U20] Py：缓存函数结果
来源：http://dali.zdqjudy.top/Article/details/gtiuydnaqr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yonumen.top/Article/details/gttzjfyjdi.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj20258888.top/Article/details/gtzmgqyohi.html

@contextlib.contextmanager
来源：http://dali.feifeiyinyue.top/Article/details/gtnjfidljg.html

[U22] Py：矩阵转置
来源：http://dali.hnqzz.top/Article/details/gtrlnsbkpr.html

list(zip(*m))
来源：http://dali.xuetiantiany.cn/Article/details/gthvmjsrdd.html

[U23] Py：分块读取大文件
来源：http://dali.yanxiufei.cn/Article/details/gtquhkmfmr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zycfv.cn/Article/details/gtsnlywsgr.html

[U24] Py：路径操作
来源：http://dali.bjfxy.top/Article/details/gtdhklphfh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gtdwgjpezy.html


<!-- 参考信息 -->