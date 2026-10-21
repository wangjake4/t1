代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gtpxlsvwev.html

[S13] C：宏定义
来源：http://dali.xuanzx.com/Article/details/gtgrtltlij.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxuanxn.top/Article/details/gtyocmvpft.html

[S14] C：枚举
来源：http://dali.jqgfzy.top/Article/details/gtyvqbqnqh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shuidangran.top/Article/details/gtfngpwwwx.html

[S15] C：类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyarhvdkj.html

(double) a / b
来源：http://dali.xinyue.icu/Article/details/gtivugjvtu.html

[S16] C：位操作置位
来源：http://dali.yueranfly.top/Article/details/gtvcfsauxq.html

x |= (1 << 3);
来源：http://dali.zhengqikj.top/Article/details/gtaqioamkc.html

[S17] C：安全拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtrxocnknn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gogol.net.cn/Article/details/gtmbkiqdfu.html

[S18] C：命令行参数
来源：http://dali.yanxiufei.cn/Article/details/gtiduavzma.html

int main(int argc, char **argv)
来源：http://dali.c1oappe.top/Article/details/gtbwtzfjiq.html

[S19] C：快速排序
来源：http://dali.jinqigufen.top/Article/details/gtsmzbrwad.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gtmojpluwq.html

[S20] C：二分查找
来源：http://dali.tanke756.top/Article/details/gtyvmvausy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtoxpiyknb.html

[S21] C：字符类别判断
来源：http://dali.tanke756.top/Article/details/gtlacwhqeo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.kuanghao11.cn/Article/details/gtozhzlnhr.html

[S22] C：字符串转数字
来源：http://dali.sxryk.cn/Article/details/gtsrrexwki.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.svipenyu.cn/Article/details/gtieklqajh.html

[S23] C：随机数
来源：http://dali.jianghu66.top/Article/details/gtrlyqlmyn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dashuyun.cn/Article/details/gtxwgdvavh.html

[S24] C：获取本地时间
来源：http://dali.hfpthk.cn/Article/details/gtizmfpewz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ehwqpu.com/Article/details/gtlzqkiawy.html

[S25] C：内存拷贝
来源：http://dali.ybcxt.top/Article/details/gttcolbmkw.html

memcpy(dst, src, n);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteggtirqn.html

[S26] C：内存清零
来源：http://dali.guannengcc.top/Article/details/gtgwyjsxqw.html

memset(a, 0, sizeof a);
来源：http://dali.zhengqikj.top/Article/details/gtzskllpev.html

[S27] C：定义常量
来源：http://dali.nanxinkj.top/Article/details/gtmnvvhsfn.html

const double PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtlxivobpr.html

[S28] C：静态变量
来源：http://dali.haohaochexian.top/Article/details/gthucppwhh.html

static int counter = 0;
来源：http://dali.yj20258.top/Article/details/gthdoxxapb.html

[S29] C：变参函数
来源：http://dali.aizwys.cn/Article/details/gtweygsnwf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sweek.top/Article/details/gtsyijqpfj.html

[S30] C：头文件保护
来源：http://dali.zhiwuduotai.top/Article/details/gtsvbzxzoy.html

#ifndef X_H
来源：http://dali.cqqwz.cn/Article/details/gtmvvnqfdb.html

#define X_H
来源：http://dali.cdnleiting.top/Article/details/gtdksqdtph.html

#endif
来源：http://dali.cashguo.top/Article/details/gtwwypghfj.html

[S31] C++：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gttvlhuioo.html

#include <iostream>
来源：http://dali.yvedp.cn/Article/details/gtsalgpavr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxuanxn.top/Article/details/gtcclfskwv.html

[S32] C++：字符串
来源：http://dali.bjfxy.top/Article/details/gtlpwnowqo.html

std::string s = "hi";  s += "!";
来源：http://dali.hfpthk.cn/Article/details/gtftytpenf.html

[S33] C++：vector 增删
来源：http://dali.sysykeji.top/Article/details/gtodzyegcs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gtmuqlqgrd.html

[S34] C++：遍历 vector
来源：http://dali.yvedp.cn/Article/details/gtsddopany.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.birdmap.top/Article/details/gtvxfrwzoy.html

[S35] C++：map
来源：http://dali.tian-w.cn/Article/details/gtyxevswdl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtyzaelyiw.html

[S36] C++：unordered_map
来源：http://dali.bjfxy.top/Article/details/gtzmqnombl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtarhofrgi.html

[S37] C++：set
来源：http://dali.feifeiyinyue.top/Article/details/gtlyzkvbrr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.redwolf501.top/Article/details/gtnzppopos.html

[S38] C++：排序
来源：http://dali.ivvv.top/Article/details/gtgcxpabgb.html

std::sort(v.begin(), v.end());
来源：http://dali.tanke756.top/Article/details/gtluhkopqx.html

[S39] C++：自定义比较器排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcsjtnra.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hywenlv.cn/Article/details/gtglepuake.html

[S40] C++：查找元素
来源：http://dali.zhongyouzk.top/Article/details/gtzejvdszh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gzhubu.top/Article/details/gtjaeszonl.html

[S41] C++：类与构造函数
来源：http://dali.tianlin.xyz/Article/details/gtfsphpobi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ivvv.top/Article/details/gtmctqdstg.html

[S42] C++：继承与虚函数
来源：http://dali.nwbrower.top/Article/details/gtkvracwwv.html

class B : public Base { public: void f() override {} };
来源：http://dali.guannengcc.top/Article/details/gtgiieafok.html

[S43] C++：智能指针
来源：http://dali.fengsongda.top/Article/details/gtrescsftt.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenzaomai.com/Article/details/gtmxjbirot.html

[S44] C++：引用传参
来源：http://dali.ydzc1.top/Article/details/gtoxkeyxol.html

void inc(int &x) { ++x; }
来源：http://dali.xuanzx.com/Article/details/gtqwifboos.html

[S45] C++：lambda
来源：http://dali.sweek.top/Article/details/gtlziaiwfe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.9152youxi.cn/Article/details/gtkbugzpdf.html

[S46] C++：函数模板
来源：http://dali.yuanzhike.top/Article/details/gtcrjeljaw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tianlin.xyz/Article/details/gtlafkejvb.html

[S47] C++：结构化绑定遍历
来源：http://dali.cqqwz.cn/Article/details/gtzetlfgby.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.havefunace.top/Article/details/gtkhzcvcqu.html

[S48] C++：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtlqhbhfmm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhoulong.xyz/Article/details/gtakrvfeoq.html

while (std::getline(in, line)) { }
来源：http://dali.tanke756.top/Article/details/gteewffadn.html

[S49] C++：写文件
来源：http://dali.yuxming.cn/Article/details/gtucuvkffa.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gotoacloud.top/Article/details/gtuivbdftn.html

[S50] C++：格式化数字
来源：http://dali.yongpay.top/Article/details/gthlbngxfn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtbfvmmkjr.html

[S51] C++：显式类型转换
来源：http://dali.aizwys.cn/Article/details/gtygzmqdrz.html

static_cast<double>(a) / b
来源：http://dali.yvedp.cn/Article/details/gtbkqdurqp.html

[S52] C++：const 与 noexcept
来源：http://dali.daria6918.cn/Article/details/gtgutuafev.html

int size() const noexcept { return n_; }
来源：http://dali.yj202588.top/Article/details/gtbghpaxje.html

[S53] C++：移动语义
来源：http://dali.shangyingyoupin.top/Article/details/gtrzykgfqw.html

std::vector<int> w = std::move(v);
来源：http://dali.pengpengdd.cyou/Article/details/gtnbzyybus.html

[S54] C++：异常处理
来源：http://dali.316326.xyz/Article/details/gtknebrhaf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhengqikj.top/Article/details/gtzuwclztb.html

[S55] C++：结构化绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyhyhbkl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ehwqpu.com/Article/details/gtjjoihqhy.html

[S56] C++：optional
来源：http://dali.316326.xyz/Article/details/gtqacgfwsw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sweek.top/Article/details/gtgdqgsuyz.html

[S57] C++：编译期常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsezpsfsi.html

constexpr int N = 10;
来源：http://dali.zdqjudy.top/Article/details/gtfyabyibl.html

[S58] C++：命名空间
来源：http://dali.ydzc1.top/Article/details/gtitijvprb.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnxiangtu.top/Article/details/gtwofgfdli.html

[S59] C++：静态断言
来源：http://dali.hongshengwenyu.top/Article/details/gtsrqziwyq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jianghu66.top/Article/details/gtrdayhuls.html

[S60] C++：遍历并删除元素
来源：http://dali.hysaishi.cn/Article/details/gtrxdvgowz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cashguo.top/Article/details/gtemwmasic.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtjlmpovoh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.c1oappe.top/Article/details/gtiklrxqoh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtwitvumyp.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtimhwtsbx.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gtfvfsrzhp.html

[T02] Kotlin：变量
来源：http://dali.9152youxi.cn/Article/details/gtymcovypp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnxiangtu.top/Article/details/gteijjjldt.html

[T03] Kotlin：字符串模板
来源：http://dali.shangyingyoupin.top/Article/details/gtluvkrhkm.html

"值: $b"
来源：http://dali.pycfn.com/Article/details/gtppsensqv.html

[T04] Kotlin：空安全
来源：http://dali.pycfn.com/Article/details/gtjlwfefzs.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gtbilcdkgx.html

[T05] Kotlin：when 表达式
来源：http://dali.smart0.xyz/Article/details/gtevjsasgr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zycfv.cn/Article/details/gtjfnmaxyp.html

[T06] Kotlin：集合映射
来源：http://dali.fzhhl.top/Article/details/gtvtbwdqhw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yonumen.top/Article/details/gtckjkjutt.html

[T07] Kotlin：集合过滤
来源：http://dali.smart0.xyz/Article/details/gttjtbihuz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tian-w.cn/Article/details/gtlrhjjmml.html

[T08] Kotlin：数据类
来源：http://dali.dianchejie.cn/Article/details/gtrpqwvvfn.html

data class User(val name: String, val age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gtovvxqiwk.html

[T09] Kotlin：扩展函数
来源：http://dali.fengsongda.top/Article/details/gtrzjvcxle.html

fun String.exclaim() = this + "!"
来源：http://dali.hywenlv.cn/Article/details/gtjxysqkyn.html

[T10] Kotlin：默认参数
来源：http://dali.quarkkingdee.top/Article/details/gtrunulkki.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gogol.net.cn/Article/details/gtywwkvofw.html

[T11] Kotlin：协程
来源：http://dali.jianghu66.top/Article/details/gttouflxji.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuxming.cn/Article/details/gttnhtmeqi.html

[T12] Kotlin：解构声明
来源：http://dali.yuanzhike.top/Article/details/gtimhkdxna.html

val (a, b) = Pair(1, 2)
来源：http://dali.ivvv.top/Article/details/gtqzrapkul.html

[T13] Kotlin：只读 Map
来源：http://dali.cdnleiting.top/Article/details/gtzdkpgbwl.html

val m = mapOf("a" to 1)
来源：http://dali.gogol.net.cn/Article/details/gteqwybdff.html

[T14] Kotlin：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjzevfkg.html

for (i in 1..10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gtkrjgcodz.html

[T15] Kotlin：接口
来源：http://dali.9152youxi.cn/Article/details/gtwnanfhnb.html

interface Shape { fun area(): Double }
来源：http://dali.guowangkeji.top/Article/details/gtqtgbitey.html

[T16] Swift：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtlpvmewle.html

print("Hello")
来源：http://dali.hysaishi.cn/Article/details/gtiijccpbf.html

[T17] Swift：变量与常量
来源：http://dali.yvedp.cn/Article/details/gtaxgjmhud.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtiqrszbyq.html

[T18] Swift：字符串插值
来源：http://dali.birdmap.top/Article/details/gtonoueinh.html

"值: \(b)"
来源：http://dali.shzxlz.cn/Article/details/gtihkhcvtu.html

[T19] Swift：可选绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbmxbqrf.html

if let n = opt { print(n) }
来源：http://dali.jqgfzy.top/Article/details/gtbcgjdefr.html

[T20] Swift：数组操作
来源：http://dali.zycfv.cn/Article/details/gtfazjcnmx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.smart0.xyz/Article/details/gtybkgwzah.html

[T21] Swift：遍历
来源：http://dali.zhoulong.xyz/Article/details/gtxnylyguc.html

for x in a { print(x) }
来源：http://dali.fzhhl.top/Article/details/gttocdnlxa.html

[T22] Swift：字典
来源：http://dali.cashguo.top/Article/details/gtphyqvsfx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sxryk.cn/Article/details/gtxeccyjvi.html

[T23] Swift：函数
来源：http://dali.hnqzz.top/Article/details/gtcrtwidau.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tanke756.top/Article/details/gtmxavpuak.html

[T24] Swift：闭包
来源：http://dali.0kj1m.cn/Article/details/gtpcfqbqhh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xziqi.cn/Article/details/gtcfyxlyux.html

[T25] Swift：结构体
来源：http://dali.smart0.xyz/Article/details/gtcbsvjqkn.html

struct P { var x: Int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmodzphrh.html

[T26] Swift：类与重写
来源：http://dali.yj20258888.top/Article/details/gtdyopzzdi.html

class A: Base { override func f() {} }
来源：http://dali.xylfe.cn/Article/details/gtinwqdlyn.html

[T27] Swift：错误处理
来源：http://dali.redwolf501.top/Article/details/gtueanncad.html

do { try f() } catch { print(error) }
来源：http://dali.aibaodan.cn/Article/details/gtsemaehap.html

[T28] Swift：枚举
来源：http://dali.chenlongwang.top/Article/details/gtohusnwed.html

enum Color { case red, green }
来源：http://dali.hnxiangtu.top/Article/details/gtvqvxtlcy.html

[T29] Swift：guard 提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gtclrlluhd.html

guard let x = opt else { return }
来源：http://dali.yj202588.top/Article/details/gtdvgndqhy.html

[T30] Swift：协议
来源：http://dali.dianchejie.cn/Article/details/gtwjyniwwj.html

protocol Shape { func area() -> Double }
来源：http://dali.c1oappe.top/Article/details/gthpnkcxha.html

[T31] Lua：Hello World
来源：http://dali.bjfxy.top/Article/details/gtuyfglfqc.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtujhsboeu.html

[T32] Lua：局部变量
来源：http://dali.kuanghao11.cn/Article/details/gtozibhbwv.html

local a = 1
来源：http://dali.bjfxy.top/Article/details/gtigedpyoe.html

[T33] Lua：表（数组）
来源：http://dali.quarkkingdee.top/Article/details/gtafmkrmfb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.havefunace.top/Article/details/gtgljhiutv.html

[T34] Lua：遍历表
来源：http://dali.aizwys.cn/Article/details/gtzyciayro.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.meibo888.top/Article/details/gtgwfxfwcj.html

[T35] Lua：字典表
来源：http://dali.jianghu66.top/Article/details/gtcicemiuq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jqgufenzy.top/Article/details/gtwfvdnvgo.html

[T36] Lua：函数
来源：http://dali.yj20258888.top/Article/details/gtneumcypk.html

function add(a, b) return a + b end
来源：http://dali.quarkkingdee.top/Article/details/gtvhaprihk.html

[T37] Lua：字符串拼接
来源：http://dali.yongpay.top/Article/details/gtitmiuukz.html

"a" .. "b"
来源：http://dali.chenzaomai.com/Article/details/gtcotbobkz.html

[T38] Lua：条件
来源：http://dali.fengsongda.top/Article/details/gtefwuhywa.html

if x > 0 then print("正") end
来源：http://dali.xuetiantiany.cn/Article/details/gtrjwckuga.html

[T39] Lua：模式匹配
来源：http://dali.jiagoushi.top/Article/details/gttnetviyt.html

string.find(s, "%d+")
来源：http://dali.xuanzx.com/Article/details/gtpvzkwtcb.html

[T40] Lua：元表
来源：http://dali.zhixingplan.top/Article/details/gtktqjboup.html

setmetatable({}, { __index = base })
来源：http://dali.andypj.xyz/Article/details/gtvrspkpdn.html

[T41] Perl：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrsgnkzw.html

print "Hello\n";
来源：http://dali.shuidangran.top/Article/details/gtdqaxpmif.html

[T42] Perl：变量类型
来源：http://dali.c1oappe.top/Article/details/gtjyqwuqbp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.fengsongda.top/Article/details/gtfhwnkeon.html

[T43] Perl：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtaynigvws.html

"值: $a"
来源：http://dali.0kj1m.cn/Article/details/gtjgeqegpd.html

[T44] Perl：条件
来源：http://dali.nanxinkj.top/Article/details/gtuhdjzcbn.html

if ($a > 0) { print "正"; }
来源：http://dali.hfpthk.cn/Article/details/gtxoqxtdou.html

[T45] Perl：数组遍历
来源：http://dali.guannengcc.top/Article/details/gtjatldvvv.html

for my $x (@arr) { print $x; }
来源：http://dali.feifeiyinyue.top/Article/details/gtevqjmksa.html

[T46] Perl：哈希操作
来源：http://dali.wangshuangyany.cn/Article/details/gthuzookuz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hywenlv.cn/Article/details/gtobwyefbr.html

[T47] Perl：正则捕获
来源：http://dali.zycfv.cn/Article/details/gtxnfhyjes.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj202588.top/Article/details/gtbgtytzhp.html

[T48] Perl：正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gthefnetkr.html

$s =~ s/old/new/g;
来源：http://dali.zdqjudy.top/Article/details/gtdgsysqkc.html

[T49] Perl：函数
来源：http://dali.chenzaomai.com/Article/details/gtvpmekssb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtesexmpvg.html

[T50] Perl：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtrwlmfciq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sufxvd.cn/Article/details/gtfbehlrqh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sysykeji.top/Article/details/gtecaotyis.html

[T51] Scala：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtmwxosdct.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtizinffgr.html

[T52] Scala：变量
来源：http://dali.yj202588.top/Article/details/gtvkcswnxq.html

val a = 1;  var b = 2
来源：http://dali.sufxvd.cn/Article/details/gtdyebsvak.html

[T53] Scala：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtdflanpou.html

s"值: $b"
来源：http://dali.pengpengdd.cyou/Article/details/gthygjwvlw.html

[T54] Scala：集合映射
来源：http://dali.ppjwa.cn/Article/details/gtqpxjetyr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.9152youxi.cn/Article/details/gtqxmzabso.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjftbgax.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenlongwang.top/Article/details/gtmxnaxfxf.html

[T56] Scala：样例类
来源：http://dali.xylfe.cn/Article/details/gtaalzctsv.html

case class User(name: String, age: Int)
来源：http://dali.yueranfly.top/Article/details/gtrfzzwpjv.html

[T57] Scala：模式匹配
来源：http://dali.cqqwz.cn/Article/details/gtciexsbxd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.bjfxy.top/Article/details/gtbshknwvm.html

[T58] Scala：函数定义
来源：http://dali.yanxiufei.cn/Article/details/gtdveyfutv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ppjwa.cn/Article/details/gtrhrqahfk.html

[T59] Scala：循环
来源：http://dali.fengsongda.top/Article/details/gttlbirrhv.html

for (i <- 1 to 10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gtcfhiphzi.html

[T60] Scala：折叠
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntbotwqf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tianlin.xyz/Article/details/gtinjmrtnf.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtumkfwwir.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.birdmap.top/Article/details/gtzkxeuoql.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtbdfnshwr.html

[U01] Py：创建虚拟环境
来源：http://dali.jianghu66.top/Article/details/gtkouzdvar.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nanxinkj.top/Article/details/gtxgtbiacb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nwbrower.top/Article/details/gtozyumjdk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpinixzk.html

[U03] Py：加载 .env 配置
来源：http://dali.jyoumei.cn/Article/details/gtoticsnhw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxuanxn.top/Article/details/gtfejfyuop.html

[U04] Py：变量调试打印
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkhoscrn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.bjfxy.top/Article/details/gtmxlgclga.html

[U05] Py：列表去重且保序
来源：http://dali.hammf.cn/Article/details/gthflcyvoo.html

list(dict.fromkeys(arr))
来源：http://dali.yuanzhike.top/Article/details/gtasgpsjnj.html

[U06] Py：合并两个字典
来源：http://dali.xziqi.cn/Article/details/gtjmzbtlom.html

{**a, **b}
来源：http://dali.vqdsnc.cn/Article/details/gtwxvuyoyf.html

[U07] Py：反转字典键值
来源：http://dali.aizwys.cn/Article/details/gtxgnpluhh.html

{v: k for k, v in d.items()}
来源：http://dali.c1oappe.top/Article/details/gtuwlwyoqx.html

[U08] Py：展平二维列表
来源：http://dali.yj202588.top/Article/details/gtvufzswnr.html

[y for x in nested for y in x]
来源：http://dali.tian-w.cn/Article/details/gtzpvhlmok.html

[U09] Py：字典取最大值的键
来源：http://dali.sufxvd.cn/Article/details/gtrvifekyc.html

max(d, key=d.get)
来源：http://dali.meibo888.top/Article/details/gtfplxomev.html

[U10] Py：按值排序字典
来源：http://dali.jlsjyb.cn/Article/details/gtlsyatfsb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jyoumei.cn/Article/details/gtizdzpfzw.html

[U11] Py：生成器表达式
来源：http://dali.yongpay.top/Article/details/gtmczcbght.html

(x * 2 for x in arr)
来源：http://dali.tian-w.cn/Article/details/gtrpkofeaf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258888.top/Article/details/gtdgvduisw.html

Counter(arr).most_common(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtqfibxjjv.html

[U13] Py：固定长度队列
来源：http://dali.tanke756.top/Article/details/gtofkqobke.html

deque(maxlen=10)
来源：http://dali.yvedp.cn/Article/details/gtztjumsbq.html

[U14] Py：分组收集到列表
来源：http://dali.chenzaomai.com/Article/details/gtqwsnvbmr.html

defaultdict(list)
来源：http://dali.zycfv.cn/Article/details/gtdtwsskqp.html

[U15] Py：高精度计时
来源：http://dali.jinqigfzy.top/Article/details/gtpqzhovqz.html

t = time.perf_counter()
来源：http://dali.shuidangran.top/Article/details/gtsosmfsqt.html

[U16] Py：命令行参数解析
来源：http://dali.hywenlv.cn/Article/details/gtgyjoqfab.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.smart0.xyz/Article/details/gtussfmlbf.html

[U17] Py：初始化日志
来源：http://dali.ybcxt.top/Article/details/gtshruydxj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.birdmap.top/Article/details/gtsqvxmnue.html

[U18] Py：预编译正则
来源：http://dali.jiagoushi.top/Article/details/gtyyaeokjs.html

pat = re.compile(r"\d+")
来源：http://dali.ivvv.top/Article/details/gtdfnbdjhm.html

[U19] Py：正则替换带回调
来源：http://dali.kuanghao11.cn/Article/details/gtfwlqmzpi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gotoacloud.top/Article/details/gtgzlvnflq.html

[U20] Py：缓存函数结果
来源：http://dali.yvedp.cn/Article/details/gteghomguz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.kuanghao11.cn/Article/details/gtrmvvjgkt.html

[U21] Py：自定义上下文管理器
来源：http://dali.hongshengwenyu.top/Article/details/gtbqcpyaon.html

@contextlib.contextmanager
来源：http://dali.dianchejie.cn/Article/details/gtrdryqsij.html

[U22] Py：矩阵转置
来源：http://dali.gaohongyu789.top/Article/details/gtuqynbnja.html

list(zip(*m))
来源：http://dali.zhoulong.xyz/Article/details/gtgosmjtcx.html

[U23] Py：分块读取大文件
来源：http://dali.hysaishi.cn/Article/details/gtjdurhsyp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yueranfly.top/Article/details/gtewenybce.html

[U24] Py：路径操作
来源：http://dali.hfpthk.cn/Article/details/gtageuvvvq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtwbnkujxq.html

[U25] Py：CSV 按字典读
来源：http://dali.cucudq.cn/Article/details/gtumovdayl.html

csv.DictReader(f)
来源：http://dali.yuxming.cn/Article/details/gtycwovcbw.html

[U26] Py：并发下载
来源：http://dali.aizwys.cn/Article/details/gtfklostpi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sweek.top/Article/details/gtoyuefsgx.html

[U27] Py：异步 HTTP
来源：http://dali.fzhhl.top/Article/details/gtzdyeotgh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hammf.cn/Article/details/gtlxsoyogz.html

[U28] Py：类型别名
来源：http://dali.zdqjudy.top/Article/details/gtpoffqcdv.html

UserId = int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffchqwhg.html

[U29] Py：属性校验
来源：http://dali.gogol.net.cn/Article/details/gtmonrvaoy.html

@property 与 @x.setter 配合
来源：http://dali.zhoulong.xyz/Article/details/gtbkukrdds.html

[U30] Py：数据类
来源：http://dali.meibo888.top/Article/details/gtgdqoxkra.html

@dataclass(slots=True)
来源：http://dali.gogol.net.cn/Article/details/gtwhzzhbxo.html

[U31] Py：单测
来源：http://dali.dashuyun.cn/Article/details/gtgbxquvem.html

python -m pytest -q
来源：http://dali.9152youxi.cn/Article/details/gtyhmuqpki.html

[U32] Py：代码格式化
来源：http://dali.svipenyu.cn/Article/details/gtqzjiwgzp.html

ruff format . && ruff check --fix .
来源：http://dali.zhixingplan.top/Article/details/gtnxncshfz.html

[U33] Py：打包发布
来源：http://dali.zhixingplan.top/Article/details/gtjbijoomt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jlsjyb.cn/Article/details/gtoqjsrdco.html

[U34] Py：判断编码
来源：http://dali.yangfankeji.com/Article/details/gtravypkoc.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gtaalsiuga.html

[U35] Py：发送邮件
来源：http://dali.xinyue.icu/Article/details/gtdtiwljad.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinqigfzy.top/Article/details/gtpdcnbfvk.html

[U36] Py：定时任务
来源：http://dali.jqgfzy.top/Article/details/gtqapqhacs.html

schedule.every(10).minutes.do(job)
来源：http://dali.smart0.xyz/Article/details/gtcfrlwntp.html


<!-- 参考信息 -->