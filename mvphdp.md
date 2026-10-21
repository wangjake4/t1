代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.havefunace.top/Article/details/gtffyhangk.html

[S13] C：宏定义
来源：http://dali.wangdashe.top/Article/details/gtrzawwwyx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.316326.xyz/Article/details/gtarelmvwl.html

[S14] C：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefhxwzai.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gzhubu.top/Article/details/gtwfpirxkv.html

[S15] C：类型转换
来源：http://dali.chenzaomai.com/Article/details/gtozwovzgs.html

(double) a / b
来源：http://dali.yj20258.top/Article/details/gtgqzcrzad.html

[S16] C：位操作置位
来源：http://dali.jinqigufen.top/Article/details/gtkejzavjo.html

x |= (1 << 3);
来源：http://dali.cashguo.top/Article/details/gtyvlfushc.html

[S17] C：安全拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gtfdvaveka.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhixingplan.top/Article/details/gtwjczriep.html

[S18] C：命令行参数
来源：http://dali.zhengqikj.top/Article/details/gtnaacydxq.html

int main(int argc, char **argv)
来源：http://dali.yonumen.top/Article/details/gtvghmsacr.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gtseqtefwe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gteiydmlwe.html

[S20] C：二分查找
来源：http://dali.zdqjudy.top/Article/details/gtqdnffecf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gtdallelyx.html

[S21] C：字符类别判断
来源：http://dali.yongpay.top/Article/details/gtznxqsqzn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigfzy.top/Article/details/gtkmvnirhr.html

[S22] C：字符串转数字
来源：http://dali.snrcjt.cn/Article/details/gttxetucdk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ppjwa.cn/Article/details/gtflpgfgen.html

[S23] C：随机数
来源：http://dali.daxiang520.top/Article/details/gttjhxsdwt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yangfankeji.com/Article/details/gtrgmdjnih.html

[S24] C：获取本地时间
来源：http://dali.zhongyouzk.top/Article/details/gthofnjblm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hammf.cn/Article/details/gtgfngecto.html

[S25] C：内存拷贝
来源：http://dali.dianchejie.cn/Article/details/gtenwpwncv.html

memcpy(dst, src, n);
来源：http://dali.zhengqikj.top/Article/details/gtunoziawu.html

[S26] C：内存清零
来源：http://dali.dianchejie.cn/Article/details/gttvqpzpxi.html

memset(a, 0, sizeof a);
来源：http://dali.cheryme.top/Article/details/gtwruakdtd.html

[S27] C：定义常量
来源：http://dali.nanxuanxn.top/Article/details/gtearorigx.html

const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtrbfdfrya.html

[S28] C：静态变量
来源：http://dali.zdqjudy.top/Article/details/gtfpvxtmax.html

static int counter = 0;
来源：http://dali.ybcxt.top/Article/details/gtuhydvigy.html

[S29] C：变参函数
来源：http://dali.cqqwz.cn/Article/details/gtoxdemnzr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.meibo888.top/Article/details/gtlawnkngo.html

[S30] C：头文件保护
来源：http://dali.hysaishi.cn/Article/details/gthijpyvjc.html

#ifndef X_H
来源：http://dali.chenlongwang.top/Article/details/gtdmagruby.html

#define X_H
来源：http://dali.havefunace.top/Article/details/gtvwrvdkjv.html

#endif
来源：http://dali.cashguo.top/Article/details/gtnwfhkfzu.html

[S31] C++：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtnuycijid.html

#include <iostream>
来源：http://dali.hammf.cn/Article/details/gtphwlatud.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgouvjxhj.html

[S32] C++：字符串
来源：http://dali.aibaodan.cn/Article/details/gtuasivyvi.html

std::string s = "hi";  s += "!";
来源：http://dali.jiagoushi.top/Article/details/gtbvzhdssu.html

[S33] C++：vector 增删
来源：http://dali.gaohongyu789.top/Article/details/gtzezysbyl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shuidangran.top/Article/details/gtgotaanaq.html

[S34] C++：遍历 vector
来源：http://dali.dianchejie.cn/Article/details/gtpzepehez.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hywenlv.cn/Article/details/gtkiirufrb.html

[S35] C++：map
来源：http://dali.cheryme.top/Article/details/gtslzpdifa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtugexrigk.html

[S36] C++：unordered_map
来源：http://dali.shzxlz.cn/Article/details/gtkjthgdwj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtpogfeomp.html

[S37] C++：set
来源：http://dali.vqdsnc.cn/Article/details/gtgtfjhvvm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigfzy.top/Article/details/gtlkyacgbk.html

[S38] C++：排序
来源：http://dali.fzhhl.top/Article/details/gttgpahzkm.html

std::sort(v.begin(), v.end());
来源：http://dali.yvedp.cn/Article/details/gtfhzbfwxr.html

[S39] C++：自定义比较器排序
来源：http://dali.cheryme.top/Article/details/gtvvvjfcjw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gaohongyu789.top/Article/details/gtgllktjkl.html

[S40] C++：查找元素
来源：http://dali.hnxiangtu.top/Article/details/gtexuqhsje.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gtbbjrycsf.html

[S41] C++：类与构造函数
来源：http://dali.sweek.top/Article/details/gtmxoelnhe.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnqzz.top/Article/details/gtoahlrfid.html

[S42] C++：继承与虚函数
来源：http://dali.316326.xyz/Article/details/gtuzcnrjdj.html

class B : public Base { public: void f() override {} };
来源：http://dali.jiagoushi.top/Article/details/gtvrnbafxf.html

[S43] C++：智能指针
来源：http://dali.vqdsnc.cn/Article/details/gthjavcjrh.html

auto p = std::make_unique<int>(5);
来源：http://dali.ehwqpu.com/Article/details/gtvuuankyr.html

[S44] C++：引用传参
来源：http://dali.yj20258888.top/Article/details/gtdkhbvaqd.html

void inc(int &x) { ++x; }
来源：http://dali.shzxlz.cn/Article/details/gtmaxlurix.html

[S45] C++：lambda
来源：http://dali.pycfn.com/Article/details/gtqeeauazn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.smart0.xyz/Article/details/gttsijlddq.html

[S46] C++：函数模板
来源：http://dali.zhixingplan.top/Article/details/gtnohqaprm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.316326.xyz/Article/details/gtcxfltuhy.html

[S47] C++：结构化绑定遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtzcqgxnlw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.iojbl.cn/Article/details/gtacqhszmc.html

[S48] C++：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtadkliwgt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoollqtlv.html

while (std::getline(in, line)) { }
来源：http://dali.xuanzx.com/Article/details/gtxcnpsvgg.html

[S49] C++：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtuhogluuq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yonumen.top/Article/details/gtxbcsxcsg.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gtrceetqnn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.316326.xyz/Article/details/gtcpmboyyh.html

[S51] C++：显式类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gtonczbdtm.html

static_cast<double>(a) / b
来源：http://dali.zhengqikj.top/Article/details/gtiroapgpl.html

[S52] C++：const 与 noexcept
来源：http://dali.xinyue.icu/Article/details/gtyebxbglb.html

int size() const noexcept { return n_; }
来源：http://dali.meibo888.top/Article/details/gtedluldac.html

[S53] C++：移动语义
来源：http://dali.hammf.cn/Article/details/gtxqdttjbs.html

std::vector<int> w = std::move(v);
来源：http://dali.chenjidiqi.icu/Article/details/gtccchmdcw.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gtdfxepogn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cheryme.top/Article/details/gtwfjfcwma.html

[S55] C++：结构化绑定
来源：http://dali.hnqzz.top/Article/details/gtxwvuasma.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gtxtpaeulw.html

[S56] C++：optional
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecqyupeg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.mhx1999.top/Article/details/gtiekcmhrq.html

[S57] C++：编译期常量
来源：http://dali.gaohongyu789.top/Article/details/gtgciibhko.html

constexpr int N = 10;
来源：http://dali.hnqzz.top/Article/details/gtzcnjgakz.html

[S58] C++：命名空间
来源：http://dali.jqgfzy.top/Article/details/gtozvurlaj.html

namespace ns { int f() { return 1; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtfyfptmnx.html

[S59] C++：静态断言
来源：http://dali.chenzaomai.com/Article/details/gtelqgpjpg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sufxvd.cn/Article/details/gtnbnmzuvx.html

[S60] C++：遍历并删除元素
来源：http://dali.hammf.cn/Article/details/gtsyfjeapa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tian-w.cn/Article/details/gtnkvtsein.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtqjkftodh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnxiangtu.top/Article/details/gtirinbixi.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcldhewg.html

[T01] Kotlin：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtkjnjgfqj.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtzbztjlan.html

[T02] Kotlin：变量
来源：http://dali.ppjwa.cn/Article/details/gtjfpjnfif.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigufen.top/Article/details/gtwliqnnhh.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gtmoivjfsv.html

"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtqkxnwnfc.html

[T04] Kotlin：空安全
来源：http://dali.gzhubu.top/Article/details/gtddxnhger.html

val n: String? = null;  n?.length
来源：http://dali.birdmap.top/Article/details/gtpwtdhggy.html

[T05] Kotlin：when 表达式
来源：http://dali.aibaodan.cn/Article/details/gtjcmkgljm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.c1oappe.top/Article/details/gtvgxqucga.html

[T06] Kotlin：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gteaihouyg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlffjhbf.html

[T07] Kotlin：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gthahhscqn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gtmsyigwzy.html

[T08] Kotlin：数据类
来源：http://dali.ppjwa.cn/Article/details/gtpjpysygq.html

data class User(val name: String, val age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbizjaxk.html

[T09] Kotlin：扩展函数
来源：http://dali.c1oappe.top/Article/details/gtbccobynx.html

fun String.exclaim() = this + "!"
来源：http://dali.xylfe.cn/Article/details/gtoznlmkua.html

[T10] Kotlin：默认参数
来源：http://dali.gaohongyu789.top/Article/details/gtmfbmlyaa.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnxiangtu.top/Article/details/gtozxxffxf.html

[T11] Kotlin：协程
来源：http://dali.0kj1m.cn/Article/details/gtsyivdxbj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgfzy.top/Article/details/gtjhrryhdf.html

[T12] Kotlin：解构声明
来源：http://dali.hywenlv.cn/Article/details/gtobjwermb.html

val (a, b) = Pair(1, 2)
来源：http://dali.bjfxy.top/Article/details/gtlinshcbp.html

[T13] Kotlin：只读 Map
来源：http://dali.zycfv.cn/Article/details/gtrlxelogn.html

val m = mapOf("a" to 1)
来源：http://dali.xuanzx.com/Article/details/gthhmsoqbv.html

[T14] Kotlin：循环
来源：http://dali.yonumen.top/Article/details/gtfxzdqrrf.html

for (i in 1..10) println(i)
来源：http://dali.daria6918.cn/Article/details/gtfhcihmza.html

[T15] Kotlin：接口
来源：http://dali.nanxuanxn.top/Article/details/gtzvahamrx.html

interface Shape { fun area(): Double }
来源：http://dali.hongshengwenyu.top/Article/details/gtmrchxfdt.html

[T16] Swift：Hello World
来源：http://dali.fzhhl.top/Article/details/gtxomunrew.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gtfdbldbmg.html

[T17] Swift：变量与常量
来源：http://dali.kuanghao11.cn/Article/details/gtsispiwgt.html

var a = 1;  let b = 2
来源：http://dali.pycfn.com/Article/details/gthurruogb.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtezpvgygf.html

"值: \(b)"
来源：http://dali.fengsongda.top/Article/details/gtymfmlsop.html

[T19] Swift：可选绑定
来源：http://dali.daria6918.cn/Article/details/gtjylozppm.html

if let n = opt { print(n) }
来源：http://dali.aizwys.cn/Article/details/gtzkqdnovg.html

[T20] Swift：数组操作
来源：http://dali.hfpthk.cn/Article/details/gtcjomwgnr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yvedp.cn/Article/details/gtnciqyjqi.html

[T21] Swift：遍历
来源：http://dali.iojbl.cn/Article/details/gtmetqpegz.html

for x in a { print(x) }
来源：http://dali.jyoumei.cn/Article/details/gtvypfzxgv.html

[T22] Swift：字典
来源：http://dali.0kj1m.cn/Article/details/gttithqcsw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aibaodan.cn/Article/details/gtryzhrygo.html

[T23] Swift：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiliehqqt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cheryme.top/Article/details/gtznrvyjts.html

[T24] Swift：闭包
来源：http://dali.feifeiyinyue.top/Article/details/gtptdtpuam.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtszjxnyzd.html

[T25] Swift：结构体
来源：http://dali.bjfxy.top/Article/details/gtwbszitzt.html

struct P { var x: Int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqncvoyof.html

[T26] Swift：类与重写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkialril.html

class A: Base { override func f() {} }
来源：http://dali.xuanzx.com/Article/details/gttarrxasb.html

[T27] Swift：错误处理
来源：http://dali.chenzaomai.com/Article/details/gtkahhozzu.html

do { try f() } catch { print(error) }
来源：http://dali.gaohongyu789.top/Article/details/gtzxlfptal.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtfphuoovl.html

enum Color { case red, green }
来源：http://dali.mhx1999.top/Article/details/gtowhmizsj.html

[T29] Swift：guard 提前返回
来源：http://dali.meibo888.top/Article/details/gtvzqxshyd.html

guard let x = opt else { return }
来源：http://dali.sysykeji.top/Article/details/gtaqzjyhpx.html

[T30] Swift：协议
来源：http://dali.sufxvd.cn/Article/details/gtivcuuoxq.html

protocol Shape { func area() -> Double }
来源：http://dali.jqgufenzy.top/Article/details/gtbihamufm.html

[T31] Lua：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtqpnoqggb.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtwimotkdf.html

[T32] Lua：局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gtbucadqxs.html

local a = 1
来源：http://dali.zdqjudy.top/Article/details/gtokpsutfe.html

[T33] Lua：表（数组）
来源：http://dali.ydzc1.top/Article/details/gtdlprblup.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangdashe.top/Article/details/gtofdretff.html

[T34] Lua：遍历表
来源：http://dali.cheryme.top/Article/details/gtkyopdkch.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xinyue.icu/Article/details/gtpmtbwvac.html

[T35] Lua：字典表
来源：http://dali.wangshuangyany.cn/Article/details/gtotayiiyc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.kuanghao11.cn/Article/details/gtznllrduy.html

[T36] Lua：函数
来源：http://dali.jinqigfzy.top/Article/details/gtsjsvoqfc.html

function add(a, b) return a + b end
来源：http://dali.hnqzz.top/Article/details/gtybuyhkht.html

[T37] Lua：字符串拼接
来源：http://dali.xziqi.cn/Article/details/gtdfgztiwy.html

"a" .. "b"
来源：http://dali.9152youxi.cn/Article/details/gtbrvohzyf.html

[T38] Lua：条件
来源：http://dali.cashguo.top/Article/details/gtefqxrynb.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangkeji.top/Article/details/gthignptwt.html

[T39] Lua：模式匹配
来源：http://dali.haohaochexian.top/Article/details/gtguqanxtg.html

string.find(s, "%d+")
来源：http://dali.yuanzhike.top/Article/details/gtxtoypixh.html

[T40] Lua：元表
来源：http://dali.gzhubu.top/Article/details/gtvlfrjffk.html

setmetatable({}, { __index = base })
来源：http://dali.xuanzx.com/Article/details/gtbizuvhzq.html

[T41] Perl：Hello World
来源：http://dali.yj20258888.top/Article/details/gtnhtcgmhz.html

print "Hello\n";
来源：http://dali.jinqigufen.top/Article/details/gttduxvuld.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvstnafj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgufenzy.top/Article/details/gtowtyyhuv.html

[T43] Perl：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gtgafpbxaw.html

"值: $a"
来源：http://dali.pengpengdd.cyou/Article/details/gttwpgxjer.html

[T44] Perl：条件
来源：http://dali.yuxming.cn/Article/details/gtwfgkqlgz.html

if ($a > 0) { print "正"; }
来源：http://dali.birdmap.top/Article/details/gtdwskrjyk.html

[T45] Perl：数组遍历
来源：http://dali.sufxvd.cn/Article/details/gtaoufpxfh.html

for my $x (@arr) { print $x; }
来源：http://dali.ehwqpu.com/Article/details/gtetcnioxh.html

[T46] Perl：哈希操作
来源：http://dali.jinqigfzy.top/Article/details/gtsvhamnki.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ivvv.top/Article/details/gtvbfywviz.html

[T47] Perl：正则捕获
来源：http://dali.gzhubu.top/Article/details/gtfntceski.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.bjfxy.top/Article/details/gtgcdiwbqg.html

[T48] Perl：正则替换
来源：http://dali.gzhubu.top/Article/details/gtcrfsopkk.html

$s =~ s/old/new/g;
来源：http://dali.xylfe.cn/Article/details/gtpwxwcrxx.html

[T49] Perl：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdawxlbxk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtjrsfdeai.html

[T50] Perl：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtwwgdxkti.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tian-w.cn/Article/details/gtsednotsf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.havefunace.top/Article/details/gtzktcckvx.html

[T51] Scala：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtatlkeoxa.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gttvpiqdmd.html

[T52] Scala：变量
来源：http://dali.kuanghao11.cn/Article/details/gtkubqirzq.html

val a = 1;  var b = 2
来源：http://dali.yj20258888.top/Article/details/gtghclxjkb.html

[T53] Scala：字符串插值
来源：http://dali.mhx1999.top/Article/details/gthvktuuyi.html

s"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gtehrgtqnx.html

[T54] Scala：集合映射
来源：http://dali.pengpengdd.cyou/Article/details/gtwtpzfxvy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yongpay.top/Article/details/gtqhngsrel.html

[T55] Scala：集合过滤
来源：http://dali.smart0.xyz/Article/details/gtzfllefxt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.havefunace.top/Article/details/gtwvmfqtpl.html

[T56] Scala：样例类
来源：http://dali.xylfe.cn/Article/details/gthgybmhor.html

case class User(name: String, age: Int)
来源：http://dali.yuanzhike.top/Article/details/gtkbbhypov.html

[T57] Scala：模式匹配
来源：http://dali.hnxiangtu.top/Article/details/gtprabwqvc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nanxinkj.top/Article/details/gtcxnoodtl.html

[T58] Scala：函数定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqviwetjj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yongpay.top/Article/details/gtzbccsfxi.html

[T59] Scala：循环
来源：http://dali.sweek.top/Article/details/gtolkkiwpi.html

for (i <- 1 to 10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gtwppzbdsp.html

[T60] Scala：折叠
来源：http://dali.gaohongyu789.top/Article/details/gtwjmdermj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxuanxn.top/Article/details/gthhanyyec.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gttikhzacu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjhdodsn.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtlfumlwxu.html

[U01] Py：创建虚拟环境
来源：http://dali.redwolf501.top/Article/details/gtpjjcasbe.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cqqwz.cn/Article/details/gtnimgxdwp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinqigfzy.top/Article/details/gtcqdsvqrr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gotoacloud.top/Article/details/gtzcxanyof.html

[U03] Py：加载 .env 配置
来源：http://dali.feifeiyinyue.top/Article/details/gtoepyawqk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.fengsongda.top/Article/details/gtktrsrukn.html

[U04] Py：变量调试打印
来源：http://dali.zhongyouzk.top/Article/details/gtkcnqpklj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zycfv.cn/Article/details/gtkecbxshi.html

[U05] Py：列表去重且保序
来源：http://dali.hongshengwenyu.top/Article/details/gtcbceprcm.html

list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gtboghidpf.html

[U06] Py：合并两个字典
来源：http://dali.guowangkeji.top/Article/details/gtfxdrrafb.html

{**a, **b}
来源：http://dali.jinqigfzy.top/Article/details/gtcbdjwyxu.html

[U07] Py：反转字典键值
来源：http://dali.fengsongda.top/Article/details/gtdvpdykap.html

{v: k for k, v in d.items()}
来源：http://dali.quarkkingdee.top/Article/details/gtkslxlilj.html

[U08] Py：展平二维列表
来源：http://dali.xinyue.icu/Article/details/gtiyvucjce.html

[y for x in nested for y in x]
来源：http://dali.meibo888.top/Article/details/gtnnaxedus.html

[U09] Py：字典取最大值的键
来源：http://dali.yvedp.cn/Article/details/gtjdeqgbpd.html

max(d, key=d.get)
来源：http://dali.jinqigufen.top/Article/details/gtccgywcpw.html

[U10] Py：按值排序字典
来源：http://dali.hysaishi.cn/Article/details/gteimrqpze.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xziqi.cn/Article/details/gtncoyzxtf.html

[U11] Py：生成器表达式
来源：http://dali.smart0.xyz/Article/details/gtexozcmmb.html

(x * 2 for x in arr)
来源：http://dali.gogol.net.cn/Article/details/gtonbbroup.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gaohongyu789.top/Article/details/gtattwklxd.html

Counter(arr).most_common(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotkrpgev.html

[U13] Py：固定长度队列
来源：http://dali.zycfv.cn/Article/details/gtwqvcgsaf.html

deque(maxlen=10)
来源：http://dali.zhixingplan.top/Article/details/gthylnkpyg.html

[U14] Py：分组收集到列表
来源：http://dali.yangfankeji.com/Article/details/gtoddzqrly.html

defaultdict(list)
来源：http://dali.zdqjudy.top/Article/details/gtpuwgkfrd.html

[U15] Py：高精度计时
来源：http://dali.yvedp.cn/Article/details/gtlalkohvh.html

t = time.perf_counter()
来源：http://dali.chenjidiqi.icu/Article/details/gtrihqwtdc.html

[U16] Py：命令行参数解析
来源：http://dali.shuidangran.top/Article/details/gtfqrasykr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.feifeiyinyue.top/Article/details/gtwsyontrb.html

[U17] Py：初始化日志
来源：http://dali.shzxlz.cn/Article/details/gtwymegntn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shuidangran.top/Article/details/gtaqdvatnq.html

[U18] Py：预编译正则
来源：http://dali.yongpay.top/Article/details/gtsuzuajwt.html

pat = re.compile(r"\d+")
来源：http://dali.zhengqikj.top/Article/details/gtqmgplihf.html

[U19] Py：正则替换带回调
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikxmwakj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.dianchejie.cn/Article/details/gtfpkrscna.html

[U20] Py：缓存函数结果
来源：http://dali.ivvv.top/Article/details/gtrrclsyms.html

@functools.lru_cache(maxsize=None)
来源：http://dali.haohaochexian.top/Article/details/gtrqsgebzv.html

[U21] Py：自定义上下文管理器
来源：http://dali.tanke756.top/Article/details/gtmomndwek.html

@contextlib.contextmanager
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpswgbif.html

[U22] Py：矩阵转置
来源：http://dali.ehwqpu.com/Article/details/gtvqobwmte.html

list(zip(*m))
来源：http://dali.jinqigfzy.top/Article/details/gtegqflonv.html

[U23] Py：分块读取大文件
来源：http://dali.smart0.xyz/Article/details/gtpxwcoyvx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.pengpengdd.cyou/Article/details/gtadpqvwji.html

[U24] Py：路径操作
来源：http://dali.316326.xyz/Article/details/gtwatbpajv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.316326.xyz/Article/details/gtwbubmefz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbczvsgtz.html

csv.DictReader(f)
来源：http://dali.guowangkeji.top/Article/details/gttbmiankx.html

[U26] Py：并发下载
来源：http://dali.sufxvd.cn/Article/details/gthyumzmyv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ivvv.top/Article/details/gtaoeegpyt.html

[U27] Py：异步 HTTP
来源：http://dali.svipenyu.cn/Article/details/gtqimfyqod.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xuetiantiany.cn/Article/details/gtdczbrinm.html

[U28] Py：类型别名
来源：http://dali.cheryme.top/Article/details/gtcpaevrfh.html

UserId = int
来源：http://dali.xziqi.cn/Article/details/gteccnnnqv.html

[U29] Py：属性校验
来源：http://dali.shuidangran.top/Article/details/gtjfwjosgf.html

@property 与 @x.setter 配合
来源：http://dali.iojbl.cn/Article/details/gtdibdlwjr.html

[U30] Py：数据类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxusqcza.html

@dataclass(slots=True)
来源：http://dali.fengsongda.top/Article/details/gtasqodfoq.html

[U31] Py：单测
来源：http://dali.yongpay.top/Article/details/gtrxxutjbt.html

python -m pytest -q
来源：http://dali.gotoacloud.top/Article/details/gtkicvbzcc.html

[U32] Py：代码格式化
来源：http://dali.wangdashe.top/Article/details/gtdymkbbhp.html

ruff format . && ruff check --fix .
来源：http://dali.xinyue.icu/Article/details/gtheohmoiu.html

[U33] Py：打包发布
来源：http://dali.jianghu66.top/Article/details/gttvzxjwbx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sweek.top/Article/details/gtacewjtxd.html

[U34] Py：判断编码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvsoeriz.html

chardet.detect(raw)
来源：http://dali.xziqi.cn/Article/details/gtqcmagbjk.html

[U35] Py：发送邮件
来源：http://dali.havefunace.top/Article/details/gtczwjxovn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xinyue.icu/Article/details/gtuojhbkxe.html

[U36] Py：定时任务
来源：http://dali.jqgfzy.top/Article/details/gtirabpfaw.html

schedule.every(10).minutes.do(job)
来源：http://dali.vqdsnc.cn/Article/details/gtiayaftop.html


<!-- 参考信息 -->