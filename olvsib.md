代发 wailian999

int main(int argc, char **argv)
来源：http://dali.jianghu66.top/Article/details/gtkvkqwcnd.html

[S19] C：快速排序
来源：http://dali.0kj1m.cn/Article/details/gtuptpslqk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gtbrjguksd.html

[S20] C：二分查找
来源：http://dali.tian-w.cn/Article/details/gtmegmoiea.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gtklueoyro.html

[S21] C：字符类别判断
来源：http://dali.jinqigufen.top/Article/details/gtroqxkzmv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtmesfcf.html

[S22] C：字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gtgimsiwrb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daria6918.cn/Article/details/gtthfntgso.html

[S23] C：随机数
来源：http://dali.jqgfzy.top/Article/details/gtvmsemrpn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuanzhike.top/Article/details/gttfqxuyqd.html

[S24] C：获取本地时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcoofkln.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guannengcc.top/Article/details/gtjlkvbtcf.html

[S25] C：内存拷贝
来源：http://dali.cdnleiting.top/Article/details/gtampviesw.html

memcpy(dst, src, n);
来源：http://dali.gotoacloud.top/Article/details/gtnhzgnwip.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gtcvgftioz.html

memset(a, 0, sizeof a);
来源：http://dali.mhx1999.top/Article/details/gtjhtlvzsh.html

[S27] C：定义常量
来源：http://dali.shzxlz.cn/Article/details/gthsnkvacs.html

const double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtyewfontt.html

[S28] C：静态变量
来源：http://dali.shzxlz.cn/Article/details/gtwhizipip.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gtyqnjzvkc.html

[S29] C：变参函数
来源：http://dali.jinqigfzy.top/Article/details/gtsdfffcrm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gteafoaspg.html

[S30] C：头文件保护
来源：http://dali.guannengcc.top/Article/details/gthujnyujf.html

#ifndef X_H
来源：http://dali.tianlin.xyz/Article/details/gtiesfmhkp.html

#define X_H
来源：http://dali.feifeiyinyue.top/Article/details/gtmiafxewq.html

#endif
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrgukfed.html

[S31] C++：Hello World
来源：http://dali.yonumen.top/Article/details/gtxfbwukey.html

#include <iostream>
来源：http://dali.dashuyun.cn/Article/details/gtbfitmyce.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxdsxkzs.html

[S32] C++：字符串
来源：http://dali.daria6918.cn/Article/details/gtxefowkzh.html

std::string s = "hi";  s += "!";
来源：http://dali.sxryk.cn/Article/details/gtoxlbuute.html

[S33] C++：vector 增删
来源：http://dali.shuidangran.top/Article/details/gttqmwbkmh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hfpthk.cn/Article/details/gtbburtwdr.html

[S34] C++：遍历 vector
来源：http://dali.gogol.net.cn/Article/details/gtfvakonby.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxuanxn.top/Article/details/gtgyvejesw.html

[S35] C++：map
来源：http://dali.haohaochexian.top/Article/details/gtxmhwffwz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtqhwkrmts.html

[S36] C++：unordered_map
来源：http://dali.zhoulong.xyz/Article/details/gtdvbnumwi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gttchtrtsj.html

[S37] C++：set
来源：http://dali.jinqigufen.top/Article/details/gtpjsjhjqk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zdqjudy.top/Article/details/gtcqnksqre.html

[S38] C++：排序
来源：http://dali.aizwys.cn/Article/details/gtspgxlzas.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gtdvtmymmx.html

[S39] C++：自定义比较器排序
来源：http://dali.birdmap.top/Article/details/gtfkhgvgse.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hysaishi.cn/Article/details/gtikhvakxz.html

[S40] C++：查找元素
来源：http://dali.chenlongwang.top/Article/details/gtxuguukwn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daxiang520.top/Article/details/gtqjhgwgsn.html

[S41] C++：类与构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtmxkmjrhg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ivvv.top/Article/details/gturzqhykx.html

[S42] C++：继承与虚函数
来源：http://dali.sxryk.cn/Article/details/gtoprlmobx.html

class B : public Base { public: void f() override {} };
来源：http://dali.cashguo.top/Article/details/gttzvtdsph.html

[S43] C++：智能指针
来源：http://dali.jyoumei.cn/Article/details/gtssitqzmu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhixingplan.top/Article/details/gtqbfondrs.html

[S44] C++：引用传参
来源：http://dali.sweek.top/Article/details/gtkeiczjwq.html

void inc(int &x) { ++x; }
来源：http://dali.hfpthk.cn/Article/details/gthyjnhuii.html

[S45] C++：lambda
来源：http://dali.zhiwuduotai.top/Article/details/gtwnlixpgw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hfpthk.cn/Article/details/gtjeukmzrp.html

[S46] C++：函数模板
来源：http://dali.shangyingyoupin.top/Article/details/gtobnpzrub.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ivvv.top/Article/details/gtakpusoda.html

[S47] C++：结构化绑定遍历
来源：http://dali.gzhubu.top/Article/details/gtzgpcaczc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dashuyun.cn/Article/details/gtpmlwuahy.html

[S48] C++：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggoorkkn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tian-w.cn/Article/details/gteyyeihez.html

while (std::getline(in, line)) { }
来源：http://dali.cqqwz.cn/Article/details/gtdxlrkhcy.html

[S49] C++：写文件
来源：http://dali.guowangkeji.top/Article/details/gtbmcbvlpy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhengqikj.top/Article/details/gtbqmqubjh.html

[S50] C++：格式化数字
来源：http://dali.cashguo.top/Article/details/gtewxhceld.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtsxlhuagl.html

[S51] C++：显式类型转换
来源：http://dali.zhixingplan.top/Article/details/gtfttxzipo.html

static_cast<double>(a) / b
来源：http://dali.dianchejie.cn/Article/details/gtgteyauie.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gtcnrjqelu.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gttpbyqcfz.html

[S53] C++：移动语义
来源：http://dali.yvedp.cn/Article/details/gtggvwsalv.html

std::vector<int> w = std::move(v);
来源：http://dali.cashguo.top/Article/details/gtnsutkaoo.html

[S54] C++：异常处理
来源：http://dali.chenzaomai.com/Article/details/gtidljmnak.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daria6918.cn/Article/details/gttbpsyfjc.html

[S55] C++：结构化绑定
来源：http://dali.ivvv.top/Article/details/gtjcuyugkj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258.top/Article/details/gtkbkchyzm.html

[S56] C++：optional
来源：http://dali.zycfv.cn/Article/details/gtcvmmnlml.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqklwwlew.html

[S57] C++：编译期常量
来源：http://dali.tian-w.cn/Article/details/gtepnhjhuc.html

constexpr int N = 10;
来源：http://dali.guowangkeji.top/Article/details/gtiohuuztb.html

[S58] C++：命名空间
来源：http://dali.haohaochexian.top/Article/details/gtvudufbdd.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gtgkkfrcqh.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gtlbaumdgg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gotoacloud.top/Article/details/gtjrbejheh.html

[S60] C++：遍历并删除元素
来源：http://dali.gogol.net.cn/Article/details/gthdnprlhs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtkmyvyvxg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtcloulxqu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gogol.net.cn/Article/details/gtuefncuzz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtwolihxbu.html

[T01] Kotlin：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtcakyfqpb.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gtmtlvdqsq.html

[T02] Kotlin：变量
来源：http://dali.gogol.net.cn/Article/details/gtfsvqylaq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ybcxt.top/Article/details/gtwkickana.html

[T03] Kotlin：字符串模板
来源：http://dali.316326.xyz/Article/details/gtsnagtnju.html

"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gtugupssuo.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gtdkxdifbe.html

val n: String? = null;  n?.length
来源：http://dali.hywenlv.cn/Article/details/gtfhkepnsl.html

[T05] Kotlin：when 表达式
来源：http://dali.vqdsnc.cn/Article/details/gttmfaaaar.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhiwuduotai.top/Article/details/gtzllrpthc.html

[T06] Kotlin：集合映射
来源：http://dali.yonumen.top/Article/details/gtlibcuhqi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fzhhl.top/Article/details/gtgvlsjpde.html

[T07] Kotlin：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gtddecibky.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hywenlv.cn/Article/details/gtsfdhiayy.html

[T08] Kotlin：数据类
来源：http://dali.aibaodan.cn/Article/details/gtwuphpkbb.html

data class User(val name: String, val age: Int)
来源：http://dali.hfpthk.cn/Article/details/gtycsphopx.html

[T09] Kotlin：扩展函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbdwyzaw.html

fun String.exclaim() = this + "!"
来源：http://dali.c1oappe.top/Article/details/gtcjgtwobg.html

[T10] Kotlin：默认参数
来源：http://dali.bjfxy.top/Article/details/gtjivyydon.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dashuyun.cn/Article/details/gtjtkqzyby.html

[T11] Kotlin：协程
来源：http://dali.yj20258888.top/Article/details/gtqlzsyjke.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xziqi.cn/Article/details/gtubvkutbr.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258.top/Article/details/gteptsriyk.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj20258888.top/Article/details/gtrukzbqbo.html

[T13] Kotlin：只读 Map
来源：http://dali.cqqwz.cn/Article/details/gttydldocb.html

val m = mapOf("a" to 1)
来源：http://dali.ybcxt.top/Article/details/gtzwugjtbk.html

[T14] Kotlin：循环
来源：http://dali.yj20258888.top/Article/details/gtsvvrycml.html

for (i in 1..10) println(i)
来源：http://dali.wangdashe.top/Article/details/gteuwwowtk.html

[T15] Kotlin：接口
来源：http://dali.zdqjudy.top/Article/details/gthextpjsi.html

interface Shape { fun area(): Double }
来源：http://dali.dianchejie.cn/Article/details/gtrxofthiw.html

[T16] Swift：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtibgnonar.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtbgyqbuyx.html

[T17] Swift：变量与常量
来源：http://dali.ppjwa.cn/Article/details/gtxxlxdbvr.html

var a = 1;  let b = 2
来源：http://dali.yj20258888.top/Article/details/gtbtvasrua.html

[T18] Swift：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtfduosivi.html

"值: \(b)"
来源：http://dali.snrcjt.cn/Article/details/gtraizqzce.html

[T19] Swift：可选绑定
来源：http://dali.cashguo.top/Article/details/gtxviwlfff.html

if let n = opt { print(n) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmscqbysr.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofbueyyo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ybcxt.top/Article/details/gtwwlqkupz.html

[T21] Swift：遍历
来源：http://dali.ppjwa.cn/Article/details/gtusjqatvg.html

for x in a { print(x) }
来源：http://dali.xinyue.icu/Article/details/gtsadwbify.html

[T22] Swift：字典
来源：http://dali.ppjwa.cn/Article/details/gteilzdljs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yvedp.cn/Article/details/gtkaerntxi.html

[T23] Swift：函数
来源：http://dali.gogol.net.cn/Article/details/gtmfpxeywr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xziqi.cn/Article/details/gtcdwljtpr.html

[T24] Swift：闭包
来源：http://dali.xuanzx.com/Article/details/gtmrjqxcpi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258888.top/Article/details/gtiqtntsdn.html

[T25] Swift：结构体
来源：http://dali.jqgufenzy.top/Article/details/gtkqlhgckm.html

struct P { var x: Int }
来源：http://dali.jinqigfzy.top/Article/details/gtkjbpezsd.html

[T26] Swift：类与重写
来源：http://dali.tianlin.xyz/Article/details/gthfepiypb.html

class A: Base { override func f() {} }
来源：http://dali.feifeiyinyue.top/Article/details/gtxlweeubi.html

[T27] Swift：错误处理
来源：http://dali.hywenlv.cn/Article/details/gtfpkspmsu.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gtctzshzjr.html

[T28] Swift：枚举
来源：http://dali.svipenyu.cn/Article/details/gtkazmebnk.html

enum Color { case red, green }
来源：http://dali.jinghuilouyu.cn/Article/details/gtynubjlot.html

[T29] Swift：guard 提前返回
来源：http://dali.aizwys.cn/Article/details/gtdhzjzxgu.html

guard let x = opt else { return }
来源：http://dali.zhengqikj.top/Article/details/gtpaeqjnbl.html

[T30] Swift：协议
来源：http://dali.wangshuangyany.cn/Article/details/gtcnxeqirz.html

protocol Shape { func area() -> Double }
来源：http://dali.dianchejie.cn/Article/details/gtebypncgz.html

[T31] Lua：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtmrhplavd.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gtfvxsbqtx.html

[T32] Lua：局部变量
来源：http://dali.tian-w.cn/Article/details/gtqdawaxqq.html

local a = 1
来源：http://dali.haohaochexian.top/Article/details/gtrdcznelz.html

[T33] Lua：表（数组）
来源：http://dali.yangfankeji.com/Article/details/gtgraombjn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hfpthk.cn/Article/details/gtgprdxlqy.html

[T34] Lua：遍历表
来源：http://dali.hysaishi.cn/Article/details/gtvlsybbac.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yj20258.top/Article/details/gtgbdocztc.html

[T35] Lua：字典表
来源：http://dali.gotoacloud.top/Article/details/gtmouxfonm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtepekfqyr.html

[T36] Lua：函数
来源：http://dali.yongpay.top/Article/details/gtyvccgnzu.html

function add(a, b) return a + b end
来源：http://dali.ehwqpu.com/Article/details/gtpdfeaxjh.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqnlwiwy.html

"a" .. "b"
来源：http://dali.shuidangran.top/Article/details/gtjwvqatxw.html

[T38] Lua：条件
来源：http://dali.0kj1m.cn/Article/details/gtxkpxcjhe.html

if x > 0 then print("正") end
来源：http://dali.hysaishi.cn/Article/details/gtspwxhrdv.html

[T39] Lua：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gtqtutuuyx.html

string.find(s, "%d+")
来源：http://dali.mhx1999.top/Article/details/gtijfkxzrz.html

[T40] Lua：元表
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjkuycgb.html

setmetatable({}, { __index = base })
来源：http://dali.aibaodan.cn/Article/details/gtyfbaupow.html

[T41] Perl：Hello World
来源：http://dali.xinyue.icu/Article/details/gtnyzthpuw.html

print "Hello\n";
来源：http://dali.zhongyouzk.top/Article/details/gtxmtonkcj.html

[T42] Perl：变量类型
来源：http://dali.dianchejie.cn/Article/details/gtwyuwtkwl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbcnlmkp.html

[T43] Perl：字符串插值
来源：http://dali.yonumen.top/Article/details/gtgksuhwrj.html

"值: $a"
来源：http://dali.sweek.top/Article/details/gtasreotsc.html

[T44] Perl：条件
来源：http://dali.cashguo.top/Article/details/gtdalczeil.html

if ($a > 0) { print "正"; }
来源：http://dali.daria6918.cn/Article/details/gtgtfaabvu.html

[T45] Perl：数组遍历
来源：http://dali.tanke756.top/Article/details/gtjbrwoxid.html

for my $x (@arr) { print $x; }
来源：http://dali.svipenyu.cn/Article/details/gtzbiitshg.html

[T46] Perl：哈希操作
来源：http://dali.smart0.xyz/Article/details/gtjtxxxoei.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwroacwj.html

[T47] Perl：正则捕获
来源：http://dali.pengpengdd.cyou/Article/details/gtathfagbf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yonumen.top/Article/details/gtdzhmahex.html

[T48] Perl：正则替换
来源：http://dali.jqgfzy.top/Article/details/gtschtsnbm.html

$s =~ s/old/new/g;
来源：http://dali.yuxming.cn/Article/details/gtepxlcmlb.html

[T49] Perl：函数
来源：http://dali.jiagoushi.top/Article/details/gtopnppvqi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmshnojgd.html

[T50] Perl：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtidjzogrk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinghuilouyu.cn/Article/details/gtetmmflhm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.snrcjt.cn/Article/details/gtoqwucvnc.html

[T51] Scala：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtmsxivyto.html

println("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtzenkbwau.html

[T52] Scala：变量
来源：http://dali.sxryk.cn/Article/details/gthfbcdzki.html

val a = 1;  var b = 2
来源：http://dali.dianchejie.cn/Article/details/gtsbxyaqqc.html

[T53] Scala：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtnaidhnur.html

s"值: $b"
来源：http://dali.vqdsnc.cn/Article/details/gtxhznjjes.html

[T54] Scala：集合映射
来源：http://dali.xuetiantiany.cn/Article/details/gtztwavhah.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yj20258.top/Article/details/gtxolcfpbo.html

[T55] Scala：集合过滤
来源：http://dali.xziqi.cn/Article/details/gtewatnpcv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqfjiabp.html

[T56] Scala：样例类
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgficfig.html

case class User(name: String, age: Int)
来源：http://dali.gotoacloud.top/Article/details/gtrrletkpp.html

[T57] Scala：模式匹配
来源：http://dali.fengsongda.top/Article/details/gtstumtvvq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xziqi.cn/Article/details/gtecalbnls.html

[T58] Scala：函数定义
来源：http://dali.hywenlv.cn/Article/details/gtlvgjxois.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ppjwa.cn/Article/details/gtrnhotyyt.html

[T59] Scala：循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtnyckrtae.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtcqrnnqiy.html

[T60] Scala：折叠
来源：http://dali.zdqjudy.top/Article/details/gtmnjpyvhr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tianlin.xyz/Article/details/gtonegeyaj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtlggdxnsp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gaohongyu789.top/Article/details/gtxivytkyz.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxqdyvclo.html

[U01] Py：创建虚拟环境
来源：http://dali.xinyue.icu/Article/details/gteciuulvt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.smart0.xyz/Article/details/gtjwifrvjy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhongyouzk.top/Article/details/gtvbpbtxrh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sufxvd.cn/Article/details/gtspbysqdc.html

[U03] Py：加载 .env 配置
来源：http://dali.gaohongyu789.top/Article/details/gtuzsnlxid.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.smart0.xyz/Article/details/gthhshnbwq.html

[U04] Py：变量调试打印
来源：http://dali.fzhhl.top/Article/details/gtzurwonlj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cheryme.top/Article/details/gtogbbjfuv.html

[U05] Py：列表去重且保序
来源：http://dali.hongshengwenyu.top/Article/details/gtvvsszudm.html

list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtbykwwgep.html

[U06] Py：合并两个字典
来源：http://dali.gaohongyu789.top/Article/details/gtufkbwhgx.html

{**a, **b}
来源：http://dali.jianghu66.top/Article/details/gtpzfapmww.html

[U07] Py：反转字典键值
来源：http://dali.yangfankeji.com/Article/details/gtmjdmhgmg.html

{v: k for k, v in d.items()}
来源：http://dali.cashguo.top/Article/details/gtnwelffmc.html

[U08] Py：展平二维列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznvfiozy.html

[y for x in nested for y in x]
来源：http://dali.yj20258888.top/Article/details/gtlpsppsvl.html

[U09] Py：字典取最大值的键
来源：http://dali.havefunace.top/Article/details/gtbmxcbmvi.html

max(d, key=d.get)
来源：http://dali.hnxiangtu.top/Article/details/gtzwlemssj.html

[U10] Py：按值排序字典
来源：http://dali.haohaochexian.top/Article/details/gtxdebfdgj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nwbrower.top/Article/details/gtccnnawqv.html

[U11] Py：生成器表达式
来源：http://dali.fzhhl.top/Article/details/gtpnhiijbr.html

(x * 2 for x in arr)
来源：http://dali.hnxiangtu.top/Article/details/gtolwbpsyg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.mhx1999.top/Article/details/gtrqdoevsv.html

Counter(arr).most_common(3)
来源：http://dali.gzhubu.top/Article/details/gtmjemiibz.html

[U13] Py：固定长度队列
来源：http://dali.tian-w.cn/Article/details/gtedzkojav.html

deque(maxlen=10)
来源：http://dali.hysaishi.cn/Article/details/gtcrlgogsl.html

[U14] Py：分组收集到列表
来源：http://dali.wangshuangyany.cn/Article/details/gtyozutyzi.html

defaultdict(list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdfaprbw.html

[U15] Py：高精度计时
来源：http://dali.nwbrower.top/Article/details/gtkygxcvkp.html

t = time.perf_counter()
来源：http://dali.snrcjt.cn/Article/details/gtdrgtmkrx.html

[U16] Py：命令行参数解析
来源：http://dali.dianchejie.cn/Article/details/gtqtbuwudr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zycfv.cn/Article/details/gtidaihgzh.html

[U17] Py：初始化日志
来源：http://dali.fzhhl.top/Article/details/gtnemdksuf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.meibo888.top/Article/details/gtmnbsrucz.html

[U18] Py：预编译正则
来源：http://dali.yvedp.cn/Article/details/gtuganhatq.html

pat = re.compile(r"\d+")
来源：http://dali.cqqwz.cn/Article/details/gtmxyjsncp.html

[U19] Py：正则替换带回调
来源：http://dali.havefunace.top/Article/details/gtzfnpexqb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.pengpengdd.cyou/Article/details/gtxxgmupdj.html

[U20] Py：缓存函数结果
来源：http://dali.zhiwuduotai.top/Article/details/gtperkvqov.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenlongwang.top/Article/details/gtmrtnsaec.html

[U21] Py：自定义上下文管理器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodeqrtdf.html

@contextlib.contextmanager
来源：http://dali.quarkkingdee.top/Article/details/gtuuhlslyd.html

[U22] Py：矩阵转置
来源：http://dali.feifeiyinyue.top/Article/details/gtfacsyxut.html

list(zip(*m))
来源：http://dali.fengsongda.top/Article/details/gtibsuhlei.html

[U23] Py：分块读取大文件
来源：http://dali.yanxiufei.cn/Article/details/gtczcegtrq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.mhx1999.top/Article/details/gtdlxremzm.html

[U24] Py：路径操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusgzcqta.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.aizwys.cn/Article/details/gtbkjfdgep.html

[U25] Py：CSV 按字典读
来源：http://dali.jqgufenzy.top/Article/details/gtgysitwoa.html

csv.DictReader(f)
来源：http://dali.yj202588.top/Article/details/gtsfsqsmqn.html

[U26] Py：并发下载
来源：http://dali.zhixingplan.top/Article/details/gtojfptlbt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ybcxt.top/Article/details/gtgrprqqdj.html

[U27] Py：异步 HTTP
来源：http://dali.yj202588.top/Article/details/gtzxjpoaeh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.kuanghao11.cn/Article/details/gtftqholgo.html

[U28] Py：类型别名
来源：http://dali.hysaishi.cn/Article/details/gtkrghfavk.html

UserId = int
来源：http://dali.gaohongyu789.top/Article/details/gtxzvijbly.html

[U29] Py：属性校验
来源：http://dali.nanxinkj.top/Article/details/gtekupkcgo.html

@property 与 @x.setter 配合
来源：http://dali.guowangkeji.top/Article/details/gtdivggnzk.html

[U30] Py：数据类
来源：http://dali.chenjidiqi.icu/Article/details/gtqyggpliy.html

@dataclass(slots=True)
来源：http://dali.haohaochexian.top/Article/details/gtdylkgomh.html

[U31] Py：单测
来源：http://dali.tian-w.cn/Article/details/gtotwrggam.html

python -m pytest -q
来源：http://dali.ydzc1.top/Article/details/gtadmgmdsw.html

[U32] Py：代码格式化
来源：http://dali.nanxinkj.top/Article/details/gtldakslri.html

ruff format . && ruff check --fix .
来源：http://dali.aizwys.cn/Article/details/gtjgssbjib.html

[U33] Py：打包发布
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmklmpcx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shzxlz.cn/Article/details/gtzledsfwo.html

[U34] Py：判断编码
来源：http://dali.snrcjt.cn/Article/details/gtjbbqbdbp.html

chardet.detect(raw)
来源：http://dali.aibaodan.cn/Article/details/gtlxzmhzqt.html

[U35] Py：发送邮件
来源：http://dali.hongshengwenyu.top/Article/details/gtnakpqlzj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.meibo888.top/Article/details/gtzjwephek.html

[U36] Py：定时任务
来源：http://dali.nanxuanxn.top/Article/details/gtzarzvifh.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhixingplan.top/Article/details/gteqorgwmo.html

[U37] Py：读写 Excel
来源：http://dali.yuanzhike.top/Article/details/gtwyhayyue.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gtlvzouiah.html

[U38] Py：获取脚本所在目录
来源：http://dali.ivvv.top/Article/details/gtovhdjilw.html

Path(__file__).resolve().parent
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlgzarrr.html

[U39] Py：判断是否在交互环境
来源：http://dali.nanxuanxn.top/Article/details/gtjbwxpbwp.html

sys.stdout.isatty()
来源：http://dali.sweek.top/Article/details/gtrplhmabk.html

[U40] Py：打印到标准错误
来源：http://dali.yongpay.top/Article/details/gtfusudpwu.html

print("err", file=sys.stderr)
来源：http://dali.tian-w.cn/Article/details/gtpmyejvgm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zycfv.cn/Article/details/gtizaktexf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.9152youxi.cn/Article/details/gtlpmrrfqg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xuanzx.com/Article/details/gtgejomfri.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yuxming.cn/Article/details/gtlpsrrblq.html


<!-- 参考信息 -->