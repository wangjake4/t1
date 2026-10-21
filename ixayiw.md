代发 wailian999

int main(int argc, char **argv)
来源：http://dali.sweek.top/Article/details/gtmughgkwy.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gtqptnhvfc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtskamwjdd.html

[S20] C：二分查找
来源：http://dali.yuanzhike.top/Article/details/gtguvhisgv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gtfhfemzah.html

[S21] C：字符类别判断
来源：http://dali.nwbrower.top/Article/details/gteyrqmlnv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dianchejie.cn/Article/details/gtibfzschy.html

[S22] C：字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gtjxqhzyiu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.kuanghao11.cn/Article/details/gtlxgixfum.html

[S23] C：随机数
来源：http://dali.quarkkingdee.top/Article/details/gtrewriuwh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nanxinkj.top/Article/details/gtujlvlrdn.html

[S24] C：获取本地时间
来源：http://dali.guannengcc.top/Article/details/gtvkrhlsoo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkixljnzi.html

[S25] C：内存拷贝
来源：http://dali.dianchejie.cn/Article/details/gtplghmsph.html

memcpy(dst, src, n);
来源：http://dali.cqqwz.cn/Article/details/gtugvpflfd.html

[S26] C：内存清零
来源：http://dali.ivvv.top/Article/details/gtyayhtefl.html

memset(a, 0, sizeof a);
来源：http://dali.nwbrower.top/Article/details/gtwwpmoecl.html

[S27] C：定义常量
来源：http://dali.cashguo.top/Article/details/gtiquxhdyy.html

const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtlbzdacgj.html

[S28] C：静态变量
来源：http://dali.gotoacloud.top/Article/details/gteywbalqq.html

static int counter = 0;
来源：http://dali.ppjwa.cn/Article/details/gtdpmcynof.html

[S29] C：变参函数
来源：http://dali.wangdashe.top/Article/details/gtkqhauztj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgfzy.top/Article/details/gtysyyemkf.html

[S30] C：头文件保护
来源：http://dali.havefunace.top/Article/details/gtoclhzsch.html

#ifndef X_H
来源：http://dali.aibaodan.cn/Article/details/gtccckyrhy.html

#define X_H
来源：http://dali.yuxming.cn/Article/details/gtsacucdgg.html

#endif
来源：http://dali.vqdsnc.cn/Article/details/gtsftoxuld.html

[S31] C++：Hello World
来源：http://dali.yvedp.cn/Article/details/gtuipdzaod.html

#include <iostream>
来源：http://dali.daria6918.cn/Article/details/gttrnuqjnu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guannengcc.top/Article/details/gtyyowpwct.html

[S32] C++：字符串
来源：http://dali.aizwys.cn/Article/details/gtbrfjfaia.html

std::string s = "hi";  s += "!";
来源：http://dali.dianchejie.cn/Article/details/gtrkwxqqqq.html

[S33] C++：vector 增删
来源：http://dali.zhixingplan.top/Article/details/gtmciythqg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sufxvd.cn/Article/details/gtyvwpdmay.html

[S34] C++：遍历 vector
来源：http://dali.hnqzz.top/Article/details/gtwhsiukjv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.snrcjt.cn/Article/details/gtkoxsvube.html

[S35] C++：map
来源：http://dali.xuanzx.com/Article/details/gtlybrhaus.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtkudrjrwm.html

[S36] C++：unordered_map
来源：http://dali.yvedp.cn/Article/details/gtxkntccuo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtgglbefcu.html

[S37] C++：set
来源：http://dali.dianchejie.cn/Article/details/gtyxbwwrcm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258888.top/Article/details/gtdictpkaj.html

[S38] C++：排序
来源：http://dali.kuanghao11.cn/Article/details/gtaseyqxfe.html

std::sort(v.begin(), v.end());
来源：http://dali.cdnleiting.top/Article/details/gtcvhvbwpz.html

[S39] C++：自定义比较器排序
来源：http://dali.birdmap.top/Article/details/gtrzvhcwou.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gzhubu.top/Article/details/gtnihvhvmj.html

[S40] C++：查找元素
来源：http://dali.316326.xyz/Article/details/gtlktmhuqu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigufen.top/Article/details/gtfktkpcdk.html

[S41] C++：类与构造函数
来源：http://dali.birdmap.top/Article/details/gtwqkjecyo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xuanzx.com/Article/details/gtzmpuaxpq.html

[S42] C++：继承与虚函数
来源：http://dali.shzxlz.cn/Article/details/gthlwimwop.html

class B : public Base { public: void f() override {} };
来源：http://dali.mhx1999.top/Article/details/gtkzjpaaqp.html

[S43] C++：智能指针
来源：http://dali.daria6918.cn/Article/details/gthvpcquav.html

auto p = std::make_unique<int>(5);
来源：http://dali.jiagoushi.top/Article/details/gtmhjzkehu.html

[S44] C++：引用传参
来源：http://dali.jqgfzy.top/Article/details/gtxpiypiqf.html

void inc(int &x) { ++x; }
来源：http://dali.jyoumei.cn/Article/details/gtddevivrm.html

[S45] C++：lambda
来源：http://dali.jqgufenzy.top/Article/details/gtfjpygexi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sysykeji.top/Article/details/gteszixwhf.html

[S46] C++：函数模板
来源：http://dali.yanxiufei.cn/Article/details/gtfqmarpcl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hnxiangtu.top/Article/details/gtmlbzlhmk.html

[S47] C++：结构化绑定遍历
来源：http://dali.jiagoushi.top/Article/details/gtgqjusfyz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gtdfofontx.html

[S48] C++：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtkbuogizm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gtyiobfpgk.html

while (std::getline(in, line)) { }
来源：http://dali.mhx1999.top/Article/details/gtfeuupivk.html

[S49] C++：写文件
来源：http://dali.haohaochexian.top/Article/details/gtbrrkawtx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgufenzy.top/Article/details/gtoeeihepv.html

[S50] C++：格式化数字
来源：http://dali.dianchejie.cn/Article/details/gttoimemfw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtgbtwgyfl.html

[S51] C++：显式类型转换
来源：http://dali.haohaochexian.top/Article/details/gtdexlwlhd.html

static_cast<double>(a) / b
来源：http://dali.zhongyouzk.top/Article/details/gtwclshnve.html

[S52] C++：const 与 noexcept
来源：http://dali.iojbl.cn/Article/details/gttjyixzam.html

int size() const noexcept { return n_; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpqistpe.html

[S53] C++：移动语义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamnhrgfh.html

std::vector<int> w = std::move(v);
来源：http://dali.ydzc1.top/Article/details/gtuzdxmzcg.html

[S54] C++：异常处理
来源：http://dali.guowangkeji.top/Article/details/gtbicxutqj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.316326.xyz/Article/details/gteebrsbmn.html

[S55] C++：结构化绑定
来源：http://dali.yj202588.top/Article/details/gtpxkwplao.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.dianchejie.cn/Article/details/gthpwxlpsc.html

[S56] C++：optional
来源：http://dali.ivvv.top/Article/details/gtlvzvcyxz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xziqi.cn/Article/details/gtcblyvcfz.html

[S57] C++：编译期常量
来源：http://dali.sufxvd.cn/Article/details/gtlftmcfse.html

constexpr int N = 10;
来源：http://dali.gotoacloud.top/Article/details/gtbzjkutqk.html

[S58] C++：命名空间
来源：http://dali.shuidangran.top/Article/details/gttotddrmv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gtsamomjps.html

[S59] C++：静态断言
来源：http://dali.yueranfly.top/Article/details/gtwvzeguty.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.iojbl.cn/Article/details/gtocvxdmgw.html

[S60] C++：遍历并删除元素
来源：http://dali.havefunace.top/Article/details/gttrjnknvu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.c1oappe.top/Article/details/gtdyblyioy.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtcvhlianm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shangyingyoupin.top/Article/details/gtnbubakxm.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnxpmfuqy.html

[T01] Kotlin：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtzunsvkct.html

println("Hello")
来源：http://dali.shuidangran.top/Article/details/gttjgfrthq.html

[T02] Kotlin：变量
来源：http://dali.bjfxy.top/Article/details/gtulcvcajv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yangfankeji.com/Article/details/gtukacgwcr.html

[T03] Kotlin：字符串模板
来源：http://dali.meibo888.top/Article/details/gtidadpzov.html

"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gtnrrdyaop.html

[T04] Kotlin：空安全
来源：http://dali.jinqigfzy.top/Article/details/gtyktzeqsu.html

val n: String? = null;  n?.length
来源：http://dali.gotoacloud.top/Article/details/gtryrrktht.html

[T05] Kotlin：when 表达式
来源：http://dali.tanke756.top/Article/details/gtnetcirqb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hongshengwenyu.top/Article/details/gtmuyodtug.html

[T06] Kotlin：集合映射
来源：http://dali.yuxming.cn/Article/details/gtqercxtgi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtexybiuiq.html

[T07] Kotlin：集合过滤
来源：http://dali.yangfankeji.com/Article/details/gtxmotnyoz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxinkj.top/Article/details/gtqqbitxum.html

[T08] Kotlin：数据类
来源：http://dali.wangdashe.top/Article/details/gtjlepuemz.html

data class User(val name: String, val age: Int)
来源：http://dali.meibo888.top/Article/details/gtvnlnmcgj.html

[T09] Kotlin：扩展函数
来源：http://dali.hnxiangtu.top/Article/details/gtueoddflq.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxinkj.top/Article/details/gtgscdzxde.html

[T10] Kotlin：默认参数
来源：http://dali.aibaodan.cn/Article/details/gtjyfndudg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuxming.cn/Article/details/gtpfamlhox.html

[T11] Kotlin：协程
来源：http://dali.shzxlz.cn/Article/details/gtqqgcmgox.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqafxwyn.html

[T12] Kotlin：解构声明
来源：http://dali.feifeiyinyue.top/Article/details/gtlxanxcvw.html

val (a, b) = Pair(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtfzakikhw.html

[T13] Kotlin：只读 Map
来源：http://dali.hnqzz.top/Article/details/gtepzucpkx.html

val m = mapOf("a" to 1)
来源：http://dali.iojbl.cn/Article/details/gtwxzbfoox.html

[T14] Kotlin：循环
来源：http://dali.dianchejie.cn/Article/details/gtbnlyipzc.html

for (i in 1..10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gtxtljgznn.html

[T15] Kotlin：接口
来源：http://dali.guannengcc.top/Article/details/gtbwobvqrz.html

interface Shape { fun area(): Double }
来源：http://dali.gaohongyu789.top/Article/details/gtsmeuqeor.html

[T16] Swift：Hello World
来源：http://dali.hammf.cn/Article/details/gtlybffnrw.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gtnbuynomi.html

[T17] Swift：变量与常量
来源：http://dali.quarkkingdee.top/Article/details/gtdbeuspvi.html

var a = 1;  let b = 2
来源：http://dali.gotoacloud.top/Article/details/gteasmftew.html

[T18] Swift：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtsaywzkpj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gtoolftgzj.html

[T19] Swift：可选绑定
来源：http://dali.mhx1999.top/Article/details/gtsyybmqhn.html

if let n = opt { print(n) }
来源：http://dali.shzxlz.cn/Article/details/gtzizwjpqe.html

[T20] Swift：数组操作
来源：http://dali.yongpay.top/Article/details/gtkmbjmkqs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ybcxt.top/Article/details/gtcbficnjg.html

[T21] Swift：遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpthtkdu.html

for x in a { print(x) }
来源：http://dali.zycfv.cn/Article/details/gtfiuqeqib.html

[T22] Swift：字典
来源：http://dali.yanxiufei.cn/Article/details/gtbwprhjia.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.guowangkeji.top/Article/details/gtlzthhqew.html

[T23] Swift：函数
来源：http://dali.wangdashe.top/Article/details/gtfovbfkvo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ydzc1.top/Article/details/gtsimhppug.html

[T24] Swift：闭包
来源：http://dali.shanyushiyangtech.top/Article/details/gtanqsptld.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtxswirxjd.html

[T25] Swift：结构体
来源：http://dali.yj202588.top/Article/details/gtfyfyollo.html

struct P { var x: Int }
来源：http://dali.c1oappe.top/Article/details/gtkskwiqzc.html

[T26] Swift：类与重写
来源：http://dali.fengsongda.top/Article/details/gtcrkfnxbn.html

class A: Base { override func f() {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsqkydct.html

[T27] Swift：错误处理
来源：http://dali.ybcxt.top/Article/details/gtdcieskaq.html

do { try f() } catch { print(error) }
来源：http://dali.redwolf501.top/Article/details/gttiodyfje.html

[T28] Swift：枚举
来源：http://dali.snrcjt.cn/Article/details/gtsfexdlya.html

enum Color { case red, green }
来源：http://dali.shzxlz.cn/Article/details/gtjvzibgwv.html

[T29] Swift：guard 提前返回
来源：http://dali.hysaishi.cn/Article/details/gtnxakpdhj.html

guard let x = opt else { return }
来源：http://dali.aibaodan.cn/Article/details/gtybmtbriw.html

[T30] Swift：协议
来源：http://dali.mhx1999.top/Article/details/gtncrgfbcs.html

protocol Shape { func area() -> Double }
来源：http://dali.pycfn.com/Article/details/gtrvzkypzv.html

[T31] Lua：Hello World
来源：http://dali.birdmap.top/Article/details/gtdzxpnndk.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gtnsmmjpdk.html

[T32] Lua：局部变量
来源：http://dali.sysykeji.top/Article/details/gtocyzcqda.html

local a = 1
来源：http://dali.daxiang520.top/Article/details/gtgrkxvhbp.html

[T33] Lua：表（数组）
来源：http://dali.jiagoushi.top/Article/details/gtteqimnfd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxuanxn.top/Article/details/gtwpjzuwwb.html

[T34] Lua：遍历表
来源：http://dali.ppjwa.cn/Article/details/gtctifqkhm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hongshengwenyu.top/Article/details/gtimuzthbg.html

[T35] Lua：字典表
来源：http://dali.gogol.net.cn/Article/details/gtgxklaczy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yangfankeji.com/Article/details/gttrzqccjc.html

[T36] Lua：函数
来源：http://dali.tian-w.cn/Article/details/gtzsvillji.html

function add(a, b) return a + b end
来源：http://dali.yuxming.cn/Article/details/gtnqtuhtte.html

[T37] Lua：字符串拼接
来源：http://dali.c1oappe.top/Article/details/gtkryovluf.html

"a" .. "b"
来源：http://dali.havefunace.top/Article/details/gtmhnimdlc.html

[T38] Lua：条件
来源：http://dali.xziqi.cn/Article/details/gtmjvkjksx.html

if x > 0 then print("正") end
来源：http://dali.9152youxi.cn/Article/details/gtkjjcejku.html

[T39] Lua：模式匹配
来源：http://dali.yongpay.top/Article/details/gtjazeyowm.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gtoujujvvd.html

[T40] Lua：元表
来源：http://dali.sufxvd.cn/Article/details/gtccbewxmn.html

setmetatable({}, { __index = base })
来源：http://dali.meibo888.top/Article/details/gtkqqidvdd.html

[T41] Perl：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtcxtxetfk.html

print "Hello\n";
来源：http://dali.daria6918.cn/Article/details/gtwntzdaar.html

[T42] Perl：变量类型
来源：http://dali.yj20258888.top/Article/details/gtyeeqtmso.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gtjzxulirh.html

[T43] Perl：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtfxjwfomn.html

"值: $a"
来源：http://dali.dashuyun.cn/Article/details/gtpuipgnjw.html

[T44] Perl：条件
来源：http://dali.gzhubu.top/Article/details/gtrkwjxnmp.html

if ($a > 0) { print "正"; }
来源：http://dali.gaohongyu789.top/Article/details/gtmrshqnob.html

[T45] Perl：数组遍历
来源：http://dali.hnxiangtu.top/Article/details/gtbpnfwzot.html

for my $x (@arr) { print $x; }
来源：http://dali.yuxming.cn/Article/details/gthwykqysh.html

[T46] Perl：哈希操作
来源：http://dali.chenzaomai.com/Article/details/gtuuvsecza.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.bjfxy.top/Article/details/gtipbznylc.html

[T47] Perl：正则捕获
来源：http://dali.aizwys.cn/Article/details/gtmegsboie.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhixingplan.top/Article/details/gtlnvmtrig.html

[T48] Perl：正则替换
来源：http://dali.9152youxi.cn/Article/details/gtcenfjzxt.html

$s =~ s/old/new/g;
来源：http://dali.andypj.xyz/Article/details/gtrlnhsiue.html

[T49] Perl：函数
来源：http://dali.smart0.xyz/Article/details/gtdenxzvdk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gtcoscspoc.html

[T50] Perl：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtdsjisoud.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yonumen.top/Article/details/gtnuzwdooj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yanxiufei.cn/Article/details/gtucwxlqsu.html

[T51] Scala：Hello World
来源：http://dali.birdmap.top/Article/details/gtqnogrwjg.html

println("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtrotibwft.html

[T52] Scala：变量
来源：http://dali.xuanzx.com/Article/details/gtycpfzpjc.html

val a = 1;  var b = 2
来源：http://dali.chenlongwang.top/Article/details/gtdrxerkmn.html

[T53] Scala：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gtyiqvtefn.html

s"值: $b"
来源：http://dali.redwolf501.top/Article/details/gtobonrywz.html

[T54] Scala：集合映射
来源：http://dali.guannengcc.top/Article/details/gtdqeeoaob.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jianghu66.top/Article/details/gtlstbmfet.html

[T55] Scala：集合过滤
来源：http://dali.yanxiufei.cn/Article/details/gtqlqrwvww.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.snrcjt.cn/Article/details/gtphxfprgu.html

[T56] Scala：样例类
来源：http://dali.yuxming.cn/Article/details/gtwqlgcplw.html

case class User(name: String, age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gtfsqyfxsj.html

[T57] Scala：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gtpkerihkx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pycfn.com/Article/details/gtxceucqex.html

[T58] Scala：函数定义
来源：http://dali.hongshengwenyu.top/Article/details/gtmntvnzgj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.birdmap.top/Article/details/gteglukkhb.html

[T59] Scala：循环
来源：http://dali.sweek.top/Article/details/gtoajhsxoq.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj20258.top/Article/details/gtzfawvzan.html

[T60] Scala：折叠
来源：http://dali.chenlongwang.top/Article/details/gtvkgsheqj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxinkj.top/Article/details/gtlxfrqyob.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtzhklafiv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.fzhhl.top/Article/details/gtjkkenbgj.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtojuyhbeb.html

[U01] Py：创建虚拟环境
来源：http://dali.cheryme.top/Article/details/gtuzermzij.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinqigufen.top/Article/details/gtiomjewqp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fengsongda.top/Article/details/gthxugpkbm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shzxlz.cn/Article/details/gtvazsyycw.html

[U03] Py：加载 .env 配置
来源：http://dali.hnxiangtu.top/Article/details/gthhmdwxug.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zdqjudy.top/Article/details/gtwfuhoysi.html

[U04] Py：变量调试打印
来源：http://dali.shuidangran.top/Article/details/gtpdelicml.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cqqwz.cn/Article/details/gttuvkvyep.html

[U05] Py：列表去重且保序
来源：http://dali.jinqigfzy.top/Article/details/gtmesxawvf.html

list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gttncjoxgf.html

[U06] Py：合并两个字典
来源：http://dali.zhengqikj.top/Article/details/gtpwixacpo.html

{**a, **b}
来源：http://dali.redwolf501.top/Article/details/gtpvpwymlt.html

[U07] Py：反转字典键值
来源：http://dali.yj20258888.top/Article/details/gtmvlnbkcd.html

{v: k for k, v in d.items()}
来源：http://dali.haohaochexian.top/Article/details/gtzecsmbjg.html

[U08] Py：展平二维列表
来源：http://dali.kuanghao11.cn/Article/details/gtxtvpixxb.html

[y for x in nested for y in x]
来源：http://dali.jqgufenzy.top/Article/details/gtidoudmeu.html

[U09] Py：字典取最大值的键
来源：http://dali.tanke756.top/Article/details/gtkuywjcon.html

max(d, key=d.get)
来源：http://dali.mhx1999.top/Article/details/gtrcfogyia.html

[U10] Py：按值排序字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqtmkild.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sufxvd.cn/Article/details/gteabeheeu.html

[U11] Py：生成器表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlcnpfkp.html

(x * 2 for x in arr)
来源：http://dali.nwbrower.top/Article/details/gtwgicssvi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.0kj1m.cn/Article/details/gtymzyklsq.html

Counter(arr).most_common(3)
来源：http://dali.zdqjudy.top/Article/details/gtmyucxdbd.html

[U13] Py：固定长度队列
来源：http://dali.haohaochexian.top/Article/details/gtawjffcyl.html

deque(maxlen=10)
来源：http://dali.gzhubu.top/Article/details/gtfhesduvv.html

[U14] Py：分组收集到列表
来源：http://dali.shzxlz.cn/Article/details/gtulxzbpph.html

defaultdict(list)
来源：http://dali.jinqigfzy.top/Article/details/gtdnacqcqh.html

[U15] Py：高精度计时
来源：http://dali.jiagoushi.top/Article/details/gtvmnbbwbj.html

t = time.perf_counter()
来源：http://dali.yongpay.top/Article/details/gtmhqvlcfm.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsnnvics.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xuetiantiany.cn/Article/details/gthwtcgduw.html

[U17] Py：初始化日志
来源：http://dali.yonumen.top/Article/details/gtabhdkbkc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.kuanghao11.cn/Article/details/gtxayrjkrw.html

[U18] Py：预编译正则
来源：http://dali.pycfn.com/Article/details/gtfpcitbxx.html

pat = re.compile(r"\d+")
来源：http://dali.sysykeji.top/Article/details/gtsnzjorqq.html

[U19] Py：正则替换带回调
来源：http://dali.gotoacloud.top/Article/details/gtyukwadjn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daria6918.cn/Article/details/gtrjxivamw.html

[U20] Py：缓存函数结果
来源：http://dali.hnqzz.top/Article/details/gtiyiqmarz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyekyzrgu.html

[U21] Py：自定义上下文管理器
来源：http://dali.meibo888.top/Article/details/gtbspngwzh.html

@contextlib.contextmanager
来源：http://dali.meibo888.top/Article/details/gtwmxjsltt.html

[U22] Py：矩阵转置
来源：http://dali.wangshuangyany.cn/Article/details/gtcmozcnoc.html

list(zip(*m))
来源：http://dali.sxryk.cn/Article/details/gtsnfxrlhp.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gtawzafifn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hywenlv.cn/Article/details/gtjlhbhblk.html

[U24] Py：路径操作
来源：http://dali.kuanghao11.cn/Article/details/gtbdelbsjs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gtwejbzfsf.html

[U25] Py：CSV 按字典读
来源：http://dali.hnxiangtu.top/Article/details/gtdweftfez.html

csv.DictReader(f)
来源：http://dali.ehwqpu.com/Article/details/gtdzavkfhu.html

[U26] Py：并发下载
来源：http://dali.xylfe.cn/Article/details/gtttqxmius.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zycfv.cn/Article/details/gtpfrwkcdf.html

[U27] Py：异步 HTTP
来源：http://dali.meibo888.top/Article/details/gtewipxela.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.wangdashe.top/Article/details/gtlwuzcbjd.html

[U28] Py：类型别名
来源：http://dali.gaohongyu789.top/Article/details/gtyshavbsp.html

UserId = int
来源：http://dali.jinghuilouyu.cn/Article/details/gtajwtdkri.html

[U29] Py：属性校验
来源：http://dali.sxryk.cn/Article/details/gtacxutuff.html

@property 与 @x.setter 配合
来源：http://dali.svipenyu.cn/Article/details/gtgayaqdgn.html

[U30] Py：数据类
来源：http://dali.hongshengwenyu.top/Article/details/gtjyojehcl.html

@dataclass(slots=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoszzpcpy.html

[U31] Py：单测
来源：http://dali.havefunace.top/Article/details/gtqgtweihd.html

python -m pytest -q
来源：http://dali.zhengqikj.top/Article/details/gtzkmyxgxc.html

[U32] Py：代码格式化
来源：http://dali.shzxlz.cn/Article/details/gtugpiybrx.html

ruff format . && ruff check --fix .
来源：http://dali.jinqigfzy.top/Article/details/gtovbzxarj.html

[U33] Py：打包发布
来源：http://dali.jiagoushi.top/Article/details/gtdlueurbe.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj20258.top/Article/details/gtyeudadkk.html

[U34] Py：判断编码
来源：http://dali.chenlongwang.top/Article/details/gtyzefrqaw.html

chardet.detect(raw)
来源：http://dali.ybcxt.top/Article/details/gtuixfukmi.html

[U35] Py：发送邮件
来源：http://dali.yonumen.top/Article/details/gtmhsyoipo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.tianlin.xyz/Article/details/gtbhwebzzl.html

[U36] Py：定时任务
来源：http://dali.gogol.net.cn/Article/details/gtakvudsel.html

schedule.every(10).minutes.do(job)
来源：http://dali.pengpengdd.cyou/Article/details/gtrqddkoil.html

[U37] Py：读写 Excel
来源：http://dali.nwbrower.top/Article/details/gtqswuamqq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zdqjudy.top/Article/details/gtwfftpdbd.html

[U38] Py：获取脚本所在目录
来源：http://dali.chenzaomai.com/Article/details/gtiignrcoz.html

Path(__file__).resolve().parent
来源：http://dali.zhoulong.xyz/Article/details/gtbeloxxyd.html

[U39] Py：判断是否在交互环境
来源：http://dali.cdnleiting.top/Article/details/gtrexpjmiw.html

sys.stdout.isatty()
来源：http://dali.birdmap.top/Article/details/gtntoshfll.html

[U40] Py：打印到标准错误
来源：http://dali.aizwys.cn/Article/details/gtqclpvnks.html

print("err", file=sys.stderr)
来源：http://dali.meibo888.top/Article/details/gtkbxarldx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.snrcjt.cn/Article/details/gtuonqeskx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hywenlv.cn/Article/details/gtfwkzwqiq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ehwqpu.com/Article/details/gtlurnsobs.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hywenlv.cn/Article/details/gtrchepjeo.html


<!-- 参考信息 -->