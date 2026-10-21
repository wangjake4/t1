代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.gzhubu.top/Article/details/gtrlfbkyzj.html

[S04] C：字符串复制
来源：http://dali.pycfn.com/Article/details/gtodauckia.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigufen.top/Article/details/gtetxmxwdw.html

[S05] C：字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gtzuvyqudr.html

strlen(s)
来源：http://dali.hfpthk.cn/Article/details/gtgwjxevto.html

[S06] C：字符串比较
来源：http://dali.fzhhl.top/Article/details/gtkkbyutfw.html

strcmp(a, b) == 0
来源：http://dali.cucudq.cn/Article/details/gtbbbpbcnf.html

[S07] C：数组遍历求和
来源：http://dali.zhongyouzk.top/Article/details/gtidsnkyov.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.feifeiyinyue.top/Article/details/gthebfuetn.html

[S08] C：动态内存分配与释放
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzujxndt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guowangkeji.top/Article/details/gtsyhnibms.html

[S09] C：结构体定义与初始化
来源：http://dali.aizwys.cn/Article/details/gttsqhwtmj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuanzhike.top/Article/details/gtuoorutpd.html

[S10] C：指针与解引用
来源：http://dali.xziqi.cn/Article/details/gtgtdherkl.html

int *p = &a;  *p = 5;
来源：http://dali.yongpay.top/Article/details/gtfpxldyzp.html

[S11] C：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtgzajdell.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.0kj1m.cn/Article/details/gttafikbju.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gtcfnlmvit.html

fclose(f);
来源：http://dali.bjfxy.top/Article/details/gtalauyocx.html

[S12] C：写文件
来源：http://dali.sufxvd.cn/Article/details/gtkubiqajo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gtbkksfwpv.html

[S13] C：宏定义
来源：http://dali.ydzc1.top/Article/details/gtixhdkmec.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.haohaochexian.top/Article/details/gtkmhfjcns.html

[S14] C：枚举
来源：http://dali.zhoulong.xyz/Article/details/gtfrklfseo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jianghu66.top/Article/details/gtcqhexads.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gtfmluxqdi.html

(double) a / b
来源：http://dali.yj202588.top/Article/details/gtckehrkbs.html

[S16] C：位操作置位
来源：http://dali.wangshuangyany.cn/Article/details/gttrnprszy.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gtvnywjegc.html

[S17] C：安全拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gtexotgjae.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hfpthk.cn/Article/details/gttussuuac.html

[S18] C：命令行参数
来源：http://dali.aizwys.cn/Article/details/gtzuyecloo.html

int main(int argc, char **argv)
来源：http://dali.chenlongwang.top/Article/details/gtctwjhfki.html

[S19] C：快速排序
来源：http://dali.yj202588.top/Article/details/gtfhxzihug.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gtfmjxkxft.html

[S20] C：二分查找
来源：http://dali.pycfn.com/Article/details/gtopmqnehy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ppjwa.cn/Article/details/gtywvqouoo.html

[S21] C：字符类别判断
来源：http://dali.yvedp.cn/Article/details/gtgefqgrls.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgfzy.top/Article/details/gtfrvksmsr.html

[S22] C：字符串转数字
来源：http://dali.xylfe.cn/Article/details/gtgzajqrqi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ydzc1.top/Article/details/gtjbsfolzb.html

[S23] C：随机数
来源：http://dali.havefunace.top/Article/details/gtaikxxjez.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gtztnbwcve.html

[S24] C：获取本地时间
来源：http://dali.haohaochexian.top/Article/details/gtqsvlpmzy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yongpay.top/Article/details/gtvpaeystp.html

[S25] C：内存拷贝
来源：http://dali.guowangkeji.top/Article/details/gtxehausyz.html

memcpy(dst, src, n);
来源：http://dali.jqgufenzy.top/Article/details/gtwzzxkdgf.html

[S26] C：内存清零
来源：http://dali.ybcxt.top/Article/details/gtuonsujak.html

memset(a, 0, sizeof a);
来源：http://dali.sxryk.cn/Article/details/gtrivyjcti.html

[S27] C：定义常量
来源：http://dali.yj20258888.top/Article/details/gtzepcqqpl.html

const double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtfqtlmuty.html

[S28] C：静态变量
来源：http://dali.zycfv.cn/Article/details/gtqkrrgwfb.html

static int counter = 0;
来源：http://dali.gaohongyu789.top/Article/details/gtigploeox.html

[S29] C：变参函数
来源：http://dali.nwbrower.top/Article/details/gtmqiyteow.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gtulfgujcx.html

[S30] C：头文件保护
来源：http://dali.zdqjudy.top/Article/details/gtmktautec.html

#ifndef X_H
来源：http://dali.316326.xyz/Article/details/gtlhaspuut.html

#define X_H
来源：http://dali.nanxinkj.top/Article/details/gtdtxtofvf.html

#endif
来源：http://dali.jyoumei.cn/Article/details/gtpktajcbs.html

[S31] C++：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtsmpzvrgx.html

#include <iostream>
来源：http://dali.gzhubu.top/Article/details/gtdjyuopkl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigfzy.top/Article/details/gtlfekrjcs.html

[S32] C++：字符串
来源：http://dali.ppjwa.cn/Article/details/gtbokotqbn.html

std::string s = "hi";  s += "!";
来源：http://dali.jlsjyb.cn/Article/details/gtxiuktfau.html

[S33] C++：vector 增删
来源：http://dali.ybcxt.top/Article/details/gtorurdobt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.0kj1m.cn/Article/details/gttpahevtk.html

[S34] C++：遍历 vector
来源：http://dali.chenlongwang.top/Article/details/gttdvzbaqy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtloezitaq.html

[S35] C++：map
来源：http://dali.tianlin.xyz/Article/details/gtotjpxtvp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gthvevhvjb.html

[S36] C++：unordered_map
来源：http://dali.yanxiufei.cn/Article/details/gtvwsuuovo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtwzhlhner.html

[S37] C++：set
来源：http://dali.meibo888.top/Article/details/gtcnxivqkc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangdashe.top/Article/details/gtbwyqdlpl.html

[S38] C++：排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasndxgky.html

std::sort(v.begin(), v.end());
来源：http://dali.aizwys.cn/Article/details/gttailgfig.html

[S39] C++：自定义比较器排序
来源：http://dali.ivvv.top/Article/details/gteqfrbnrq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangtech.top/Article/details/gtsiiaombc.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynvwhwzg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aibaodan.cn/Article/details/gtxkbkyxrf.html

[S41] C++：类与构造函数
来源：http://dali.gogol.net.cn/Article/details/gtzgisfvoi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnxiangtu.top/Article/details/gtkabiyumu.html

[S42] C++：继承与虚函数
来源：http://dali.kuanghao11.cn/Article/details/gtqbconahh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgtqpndj.html

[S43] C++：智能指针
来源：http://dali.hfpthk.cn/Article/details/gtctbxiwlq.html

auto p = std::make_unique<int>(5);
来源：http://dali.jlsjyb.cn/Article/details/gtagzpotdb.html

[S44] C++：引用传参
来源：http://dali.zhoulong.xyz/Article/details/gtxlvhvvgx.html

void inc(int &x) { ++x; }
来源：http://dali.vqdsnc.cn/Article/details/gttwinuycq.html

[S45] C++：lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckmqqgpj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.birdmap.top/Article/details/gtubeaihjc.html

[S46] C++：函数模板
来源：http://dali.hywenlv.cn/Article/details/gthmfbpqiq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuowedhte.html

[S47] C++：结构化绑定遍历
来源：http://dali.redwolf501.top/Article/details/gtclbxjhrf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdbmxkbp.html

[S48] C++：逐行读文件
来源：http://dali.cashguo.top/Article/details/gttldelagk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvsartqz.html

while (std::getline(in, line)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtkpqrubwg.html

[S49] C++：写文件
来源：http://dali.jinqigfzy.top/Article/details/gtnttoymvk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangshuangyany.cn/Article/details/gtpprcpydy.html

[S50] C++：格式化数字
来源：http://dali.wangdashe.top/Article/details/gtlhjfhvgs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtaroljlyx.html

[S51] C++：显式类型转换
来源：http://dali.daria6918.cn/Article/details/gttxgbcnjq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gtbsewitne.html

[S52] C++：const 与 noexcept
来源：http://dali.hywenlv.cn/Article/details/gtstfljzrc.html

int size() const noexcept { return n_; }
来源：http://dali.bjfxy.top/Article/details/gtswvnvyjm.html

[S53] C++：移动语义
来源：http://dali.gzhubu.top/Article/details/gtlftafwcb.html

std::vector<int> w = std::move(v);
来源：http://dali.guowangkeji.top/Article/details/gtumsxczyt.html

[S54] C++：异常处理
来源：http://dali.mhx1999.top/Article/details/gtsfeippjm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shuidangran.top/Article/details/gtcxlrmdwu.html

[S55] C++：结构化绑定
来源：http://dali.zhoulong.xyz/Article/details/gtjlllcavh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhoulong.xyz/Article/details/gtuvxnghmj.html

[S56] C++：optional
来源：http://dali.xylfe.cn/Article/details/gtbpzbmhtk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.redwolf501.top/Article/details/gtvjjwbidi.html

[S57] C++：编译期常量
来源：http://dali.svipenyu.cn/Article/details/gtaanxcomw.html

constexpr int N = 10;
来源：http://dali.tanke756.top/Article/details/gtonzlvbad.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gtubsgwntz.html

namespace ns { int f() { return 1; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtzjxlifju.html

[S59] C++：静态断言
来源：http://dali.pycfn.com/Article/details/gtnwnyxlok.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fzhhl.top/Article/details/gtyzgkxcsf.html

[S60] C++：遍历并删除元素
来源：http://dali.daxiang520.top/Article/details/gtjdwrktsw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtqlpldkmx.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gthqjgdprp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.9152youxi.cn/Article/details/gtackydtsc.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtazlykyzv.html

[T01] Kotlin：Hello World
来源：http://dali.316326.xyz/Article/details/gtauktiirm.html

println("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtjogttdgy.html

[T02] Kotlin：变量
来源：http://dali.meibo888.top/Article/details/gtzrogynon.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ivvv.top/Article/details/gtplopzkhy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhixingplan.top/Article/details/gtxlaoksyb.html

"值: $b"
来源：http://dali.ivvv.top/Article/details/gtmfwsewvh.html

[T04] Kotlin：空安全
来源：http://dali.yonumen.top/Article/details/gtuapjmqoe.html

val n: String? = null;  n?.length
来源：http://dali.yonumen.top/Article/details/gtozvxriqa.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gtbcijtarz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.kuanghao11.cn/Article/details/gtkwqstkrr.html

[T06] Kotlin：集合映射
来源：http://dali.c1oappe.top/Article/details/gtwmexlslx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtfxtscean.html

[T07] Kotlin：集合过滤
来源：http://dali.gzhubu.top/Article/details/gtwzcxymww.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zdqjudy.top/Article/details/gtyxhrktor.html

[T08] Kotlin：数据类
来源：http://dali.hnxiangtu.top/Article/details/gtqdwxwonl.html

data class User(val name: String, val age: Int)
来源：http://dali.mhx1999.top/Article/details/gtzvtfmvcu.html

[T09] Kotlin：扩展函数
来源：http://dali.yuanzhike.top/Article/details/gtbokbfkph.html

fun String.exclaim() = this + "!"
来源：http://dali.cashguo.top/Article/details/gteksubitr.html

[T10] Kotlin：默认参数
来源：http://dali.guowangkeji.top/Article/details/gtnqxqkhza.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xylfe.cn/Article/details/gtgypccrez.html

[T11] Kotlin：协程
来源：http://dali.pengpengdd.cyou/Article/details/gthvvnivfk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dashuyun.cn/Article/details/gtwmspruqk.html

[T12] Kotlin：解构声明
来源：http://dali.fengsongda.top/Article/details/gtdeseblxw.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gtndonssid.html

[T13] Kotlin：只读 Map
来源：http://dali.xinyue.icu/Article/details/gtpmqmdtil.html

val m = mapOf("a" to 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtzwjjbqkk.html

[T14] Kotlin：循环
来源：http://dali.cdnleiting.top/Article/details/gtoboxengd.html

for (i in 1..10) println(i)
来源：http://dali.meibo888.top/Article/details/gtgdxbnuil.html

[T15] Kotlin：接口
来源：http://dali.hnqzz.top/Article/details/gtuyzumkgv.html

interface Shape { fun area(): Double }
来源：http://dali.ehwqpu.com/Article/details/gtkahbltsw.html

[T16] Swift：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfziutpjq.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtefozbfpx.html

[T17] Swift：变量与常量
来源：http://dali.feifeiyinyue.top/Article/details/gtyuvfzjvp.html

var a = 1;  let b = 2
来源：http://dali.hnxiangtu.top/Article/details/gtfvktdfpz.html

[T18] Swift：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gtjctlolpl.html

"值: \(b)"
来源：http://dali.ppjwa.cn/Article/details/gtparquaxz.html

[T19] Swift：可选绑定
来源：http://dali.sxryk.cn/Article/details/gtmaeckvqw.html

if let n = opt { print(n) }
来源：http://dali.0kj1m.cn/Article/details/gtgcymhclo.html

[T20] Swift：数组操作
来源：http://dali.0kj1m.cn/Article/details/gtzniuwpsi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibbnzgfr.html

[T21] Swift：遍历
来源：http://dali.smart0.xyz/Article/details/gticqydpkd.html

for x in a { print(x) }
来源：http://dali.shangyingyoupin.top/Article/details/gtonucomhq.html

[T22] Swift：字典
来源：http://dali.yj20258.top/Article/details/gtnibyzrqo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zycfv.cn/Article/details/gtqeeelclo.html

[T23] Swift：函数
来源：http://dali.iojbl.cn/Article/details/gtmgdtqpbu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guannengcc.top/Article/details/gtwitixnfr.html

[T24] Swift：闭包
来源：http://dali.zhixingplan.top/Article/details/gtjxrgywss.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sweek.top/Article/details/gtwaeipyxr.html

[T25] Swift：结构体
来源：http://dali.gaohongyu789.top/Article/details/gtvhbnrzqm.html

struct P { var x: Int }
来源：http://dali.ehwqpu.com/Article/details/gtvrkzuqch.html

[T26] Swift：类与重写
来源：http://dali.chenlongwang.top/Article/details/gtnlcpzuua.html

class A: Base { override func f() {} }
来源：http://dali.zhongyouzk.top/Article/details/gtktuhfrnk.html

[T27] Swift：错误处理
来源：http://dali.daxiang520.top/Article/details/gtiljoroiv.html

do { try f() } catch { print(error) }
来源：http://dali.sufxvd.cn/Article/details/gtfpncselt.html

[T28] Swift：枚举
来源：http://dali.yonumen.top/Article/details/gtmjnbbviy.html

enum Color { case red, green }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxznehmr.html

[T29] Swift：guard 提前返回
来源：http://dali.nwbrower.top/Article/details/gtrfbgawie.html

guard let x = opt else { return }
来源：http://dali.gogol.net.cn/Article/details/gtqghapfvm.html

[T30] Swift：协议
来源：http://dali.ybcxt.top/Article/details/gtcvvotnqo.html

protocol Shape { func area() -> Double }
来源：http://dali.ydzc1.top/Article/details/gtcenwddoe.html

[T31] Lua：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtrwgnfdeh.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtaxdyirhj.html

[T32] Lua：局部变量
来源：http://dali.jyoumei.cn/Article/details/gtyrwvauzm.html

local a = 1
来源：http://dali.wangdashe.top/Article/details/gtinpncqob.html

[T33] Lua：表（数组）
来源：http://dali.yangfankeji.com/Article/details/gtuxjckllp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ydzc1.top/Article/details/gtxycwswfl.html

[T34] Lua：遍历表
来源：http://dali.yuanzhike.top/Article/details/gteiebzacf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nwbrower.top/Article/details/gtgsofwqat.html

[T35] Lua：字典表
来源：http://dali.fzhhl.top/Article/details/gtiysasnwf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtfuvltehg.html

[T36] Lua：函数
来源：http://dali.kuanghao11.cn/Article/details/gtfrguizrw.html

function add(a, b) return a + b end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcarsxpzp.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258888.top/Article/details/gtzxlmqnmp.html

"a" .. "b"
来源：http://dali.cheryme.top/Article/details/gtvkaiygqg.html

[T38] Lua：条件
来源：http://dali.aizwys.cn/Article/details/gtkzetlfhh.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangtech.top/Article/details/gtojysrbdq.html

[T39] Lua：模式匹配
来源：http://dali.shzxlz.cn/Article/details/gtgkkgctoe.html

string.find(s, "%d+")
来源：http://dali.dianchejie.cn/Article/details/gtaqldhqlx.html

[T40] Lua：元表
来源：http://dali.cashguo.top/Article/details/gtyhccskfy.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpxvhnkt.html

[T41] Perl：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtgdrasboj.html

print "Hello\n";
来源：http://dali.xuanzx.com/Article/details/gtvadcclkz.html

[T42] Perl：变量类型
来源：http://dali.cheryme.top/Article/details/gtbccoaumr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.quarkkingdee.top/Article/details/gtwdmfnfxv.html

[T43] Perl：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gtviyqdjyp.html

"值: $a"
来源：http://dali.ydzc1.top/Article/details/gtbboylgnp.html

[T44] Perl：条件
来源：http://dali.yonumen.top/Article/details/gtxbgoxeev.html

if ($a > 0) { print "正"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrerwotmv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gtfcqdidsi.html

for my $x (@arr) { print $x; }
来源：http://dali.guannengcc.top/Article/details/gtlbhdhzjl.html

[T46] Perl：哈希操作
来源：http://dali.aizwys.cn/Article/details/gtxkenqknn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdlntxtck.html

[T47] Perl：正则捕获
来源：http://dali.jinqigufen.top/Article/details/gtfbslyntz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ehwqpu.com/Article/details/gtwjbuilxw.html

[T48] Perl：正则替换
来源：http://dali.yuxming.cn/Article/details/gtjxxpntoj.html

$s =~ s/old/new/g;
来源：http://dali.yj202588.top/Article/details/gtgbdocfge.html

[T49] Perl：函数
来源：http://dali.yvedp.cn/Article/details/gtqhzvwwol.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtipdmgubm.html

[T50] Perl：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexyfyrqc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cashguo.top/Article/details/gtldrnyqtd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yongpay.top/Article/details/gtzhdffdcq.html

[T51] Scala：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtglzqmytf.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gthudivzjd.html

[T52] Scala：变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmknnjoco.html

val a = 1;  var b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gthesstbon.html

[T53] Scala：字符串插值
来源：http://dali.tanke756.top/Article/details/gtnmxgcgvw.html

s"值: $b"
来源：http://dali.hnqzz.top/Article/details/gtnnwcmfph.html

[T54] Scala：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gtltxneiqh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtcrmblfrp.html

[T55] Scala：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gtcezlfdcw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sysykeji.top/Article/details/gtfxpdxwix.html

[T56] Scala：样例类
来源：http://dali.chenzaomai.com/Article/details/gtgkasqrhq.html

case class User(name: String, age: Int)
来源：http://dali.hammf.cn/Article/details/gtmpofsmzl.html

[T57] Scala：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gthgdbidyg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zdqjudy.top/Article/details/gtogfuiweb.html

[T58] Scala：函数定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutmgakwa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dianchejie.cn/Article/details/gtrxjwevis.html

[T59] Scala：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyarqusdx.html

for (i <- 1 to 10) println(i)
来源：http://dali.iojbl.cn/Article/details/gttuqwyjka.html

[T60] Scala：折叠
来源：http://dali.tanke756.top/Article/details/gtwojpzqjb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.guowangkeji.top/Article/details/gtsqdzxbox.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtccbdaxdh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.fengsongda.top/Article/details/gtvbxjphec.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtgzofiwgs.html

[U01] Py：创建虚拟环境
来源：http://dali.cucudq.cn/Article/details/gtkfdomphr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.kuanghao11.cn/Article/details/gttdhxgzkm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.bjfxy.top/Article/details/gtnevwwhzu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtabykdqyu.html

[U03] Py：加载 .env 配置
来源：http://dali.iojbl.cn/Article/details/gtwgqzwklu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxuanxn.top/Article/details/gtqzpxzffp.html

[U04] Py：变量调试打印
来源：http://dali.shangyingyoupin.top/Article/details/gtcfrtwgug.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhoulong.xyz/Article/details/gtynhwauih.html

[U05] Py：列表去重且保序
来源：http://dali.xuetiantiany.cn/Article/details/gtwkpthyzb.html

list(dict.fromkeys(arr))
来源：http://dali.xziqi.cn/Article/details/gttofmahsz.html

[U06] Py：合并两个字典
来源：http://dali.ybcxt.top/Article/details/gtegqnqqez.html

{**a, **b}
来源：http://dali.haohaochexian.top/Article/details/gtnlunvvtz.html

[U07] Py：反转字典键值
来源：http://dali.shuidangran.top/Article/details/gtehygugrw.html

{v: k for k, v in d.items()}
来源：http://dali.andypj.xyz/Article/details/gtatkdtdtg.html

[U08] Py：展平二维列表
来源：http://dali.chenlongwang.top/Article/details/gtljsjohtw.html

[y for x in nested for y in x]
来源：http://dali.snrcjt.cn/Article/details/gtfpqqsbdz.html

[U09] Py：字典取最大值的键
来源：http://dali.fengsongda.top/Article/details/gtjgmduqqr.html

max(d, key=d.get)
来源：http://dali.havefunace.top/Article/details/gtfgtdxbfz.html

[U10] Py：按值排序字典
来源：http://dali.ppjwa.cn/Article/details/gtqjujhkze.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhoulong.xyz/Article/details/gtfiqzoeon.html

[U11] Py：生成器表达式
来源：http://dali.daxiang520.top/Article/details/gtjpnliova.html

(x * 2 for x in arr)
来源：http://dali.ybcxt.top/Article/details/gtwhlhepws.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xuetiantiany.cn/Article/details/gtfhtpqdot.html

Counter(arr).most_common(3)
来源：http://dali.hnxiangtu.top/Article/details/gtyxkvrfjo.html

[U13] Py：固定长度队列
来源：http://dali.hysaishi.cn/Article/details/gttlhrcmac.html

deque(maxlen=10)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqiyassm.html

[U14] Py：分组收集到列表
来源：http://dali.fzhhl.top/Article/details/gtpfehremm.html

defaultdict(list)
来源：http://dali.c1oappe.top/Article/details/gtehlggwdl.html

[U15] Py：高精度计时
来源：http://dali.hongshengwenyu.top/Article/details/gttmzkkcck.html

t = time.perf_counter()
来源：http://dali.ehwqpu.com/Article/details/gtkqwetaax.html

[U16] Py：命令行参数解析
来源：http://dali.yangfankeji.com/Article/details/gtdeytvjjq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yangfankeji.com/Article/details/gtmkygcnqh.html

[U17] Py：初始化日志
来源：http://dali.chenzaomai.com/Article/details/gtcaujppqo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.fengsongda.top/Article/details/gtvfcxnlxw.html

[U18] Py：预编译正则
来源：http://dali.aizwys.cn/Article/details/gtpqhyhxpj.html

pat = re.compile(r"\d+")
来源：http://dali.xuanzx.com/Article/details/gtsmsvoglz.html

[U19] Py：正则替换带回调
来源：http://dali.hfpthk.cn/Article/details/gtxarjmgxg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zycfv.cn/Article/details/gtnksvyrfb.html

[U20] Py：缓存函数结果
来源：http://dali.zhengqikj.top/Article/details/gtcuhhjgpd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.svipenyu.cn/Article/details/gtmclzbqep.html

[U21] Py：自定义上下文管理器
来源：http://dali.nanxuanxn.top/Article/details/gtdhxdwakn.html

@contextlib.contextmanager
来源：http://dali.yangfankeji.com/Article/details/gtxdkxmepv.html

[U22] Py：矩阵转置
来源：http://dali.yueranfly.top/Article/details/gtkptkkbhk.html

list(zip(*m))
来源：http://dali.ivvv.top/Article/details/gtcxbokwdh.html

[U23] Py：分块读取大文件
来源：http://dali.haohaochexian.top/Article/details/gtxvyzzixe.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.fengsongda.top/Article/details/gtaonpksoa.html

[U24] Py：路径操作
来源：http://dali.svipenyu.cn/Article/details/gtkkktqsvx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gthdgtiwds.html

[U25] Py：CSV 按字典读
来源：http://dali.yonumen.top/Article/details/gtrqaztawx.html

csv.DictReader(f)
来源：http://dali.gotoacloud.top/Article/details/gthjmimwkq.html

[U26] Py：并发下载
来源：http://dali.zhixingplan.top/Article/details/gtkkctqslb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenjidiqi.icu/Article/details/gtsxrvxkqf.html


<!-- 参考信息 -->