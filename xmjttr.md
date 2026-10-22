代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gt2nvmlijah.html

[S21] C：字符类别判断
来源：http://dali.smart0.xyz/Article/details/gt2woqevnzf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gt2xuqszvjo.html

[S22] C：字符串转数字
来源：http://dali.haohaochexian.top/Article/details/gt2msotuwkp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yidyqvgw.html

[S23] C：随机数
来源：http://dali.snrcjt.cn/Article/details/gt2ptbvnfbw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.smart0.xyz/Article/details/gt2yqkwojqy.html

[S24] C：获取本地时间
来源：http://dali.yangfankeji.com/Article/details/gt2sacfjxsd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shuidangran.top/Article/details/gt2ksrixtrs.html

[S25] C：内存拷贝
来源：http://dali.yueranfly.top/Article/details/gt2qenjozny.html

memcpy(dst, src, n);
来源：http://dali.yj202588.top/Article/details/gt2ucaaogmv.html

[S26] C：内存清零
来源：http://dali.hywenlv.cn/Article/details/gt2qrcogntm.html

memset(a, 0, sizeof a);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dgjrtogc.html

[S27] C：定义常量
来源：http://dali.zhixingplan.top/Article/details/gt2fhxgwugb.html

const double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gt2oqdbrzlf.html

[S28] C：静态变量
来源：http://dali.xziqi.cn/Article/details/gt2msjdbdfr.html

static int counter = 0;
来源：http://dali.sweek.top/Article/details/gt2vkflnrpc.html

[S29] C：变参函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ygfrsyec.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258888.top/Article/details/gt2yftboccb.html

[S30] C：头文件保护
来源：http://dali.sysykeji.top/Article/details/gt2nfpjfgck.html

#ifndef X_H
来源：http://dali.316326.xyz/Article/details/gt2dritrnez.html

#define X_H
来源：http://dali.ybcxt.top/Article/details/gt2yspgetfs.html

#endif
来源：http://dali.snrcjt.cn/Article/details/gt2igaeqjsn.html

[S31] C++：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2kptgmify.html

#include <iostream>
来源：http://dali.aibaodan.cn/Article/details/gt2oiunycak.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258.top/Article/details/gt2bzpoyesx.html

[S32] C++：字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2yvcohqql.html

std::string s = "hi";  s += "!";
来源：http://dali.shzxlz.cn/Article/details/gt2dicaveiy.html

[S33] C++：vector 增删
来源：http://dali.nanxinkj.top/Article/details/gt2rstecqxk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hfpthk.cn/Article/details/gt2fjoljisu.html

[S34] C++：遍历 vector
来源：http://dali.nanxuanxn.top/Article/details/gt2dpurzvod.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hywenlv.cn/Article/details/gt2buwovgsp.html

[S35] C++：map
来源：http://dali.daxiang520.top/Article/details/gt2beaolluu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rrxwdrgh.html

[S36] C++：unordered_map
来源：http://dali.jqgfzy.top/Article/details/gt2lyqlogrh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2ktsoqkua.html

[S37] C++：set
来源：http://dali.ydzc1.top/Article/details/gt2qjcuindk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sweek.top/Article/details/gt2eesanjzs.html

[S38] C++：排序
来源：http://dali.jianghu66.top/Article/details/gt2dmtdlnio.html

std::sort(v.begin(), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cwsujjua.html

[S39] C++：自定义比较器排序
来源：http://dali.vqdsnc.cn/Article/details/gt2odpjgcnq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xkrrexdm.html

[S40] C++：查找元素
来源：http://dali.0kj1m.cn/Article/details/gt2mpjjgmuh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sysykeji.top/Article/details/gt2bidtlbxi.html

[S41] C++：类与构造函数
来源：http://dali.iojbl.cn/Article/details/gt2lsxqqslp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ybcxt.top/Article/details/gt2jocjggfg.html

[S42] C++：继承与虚函数
来源：http://dali.xuanzx.com/Article/details/gt2yahjrwwa.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258.top/Article/details/gt2ahuivrco.html

[S43] C++：智能指针
来源：http://dali.cashguo.top/Article/details/gt2esdufllw.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rlcmqate.html

[S44] C++：引用传参
来源：http://dali.yj20258.top/Article/details/gt2upqiejub.html

void inc(int &x) { ++x; }
来源：http://dali.yueranfly.top/Article/details/gt2eqsebmyz.html

[S45] C++：lambda
来源：http://dali.hywenlv.cn/Article/details/gt2edrwudag.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yonumen.top/Article/details/gt2kqibjaxs.html

[S46] C++：函数模板
来源：http://dali.jyoumei.cn/Article/details/gt2gyigeohe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gt2ibkmywyn.html

[S47] C++：结构化绑定遍历
来源：http://dali.jiagoushi.top/Article/details/gt2fpdjozrq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tian-w.cn/Article/details/gt2qucabrre.html

[S48] C++：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gt2crohsuiw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shangyingyoupin.top/Article/details/gt2puhfbntf.html

while (std::getline(in, line)) { }
来源：http://dali.yueranfly.top/Article/details/gt2ejdeezca.html

[S49] C++：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kukfqhzz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daxiang520.top/Article/details/gt2yydgnfhg.html

[S50] C++：格式化数字
来源：http://dali.ydzc1.top/Article/details/gt2lspmcmqi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnqzz.top/Article/details/gt2xqrldfjd.html

[S51] C++：显式类型转换
来源：http://dali.jyoumei.cn/Article/details/gt2yqekkfkv.html

static_cast<double>(a) / b
来源：http://dali.bjfxy.top/Article/details/gt2yqseasnr.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gt2jmszlcpy.html

int size() const noexcept { return n_; }
来源：http://dali.gaohongyu789.top/Article/details/gt2nalceqed.html

[S53] C++：移动语义
来源：http://dali.gotoacloud.top/Article/details/gt2fvuoyekb.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxinkj.top/Article/details/gt2jdifixgc.html

[S54] C++：异常处理
来源：http://dali.redwolf501.top/Article/details/gt2lknbdgub.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ldqqsqab.html

[S55] C++：结构化绑定
来源：http://dali.jinqigufen.top/Article/details/gt2yuskqigb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hywenlv.cn/Article/details/gt2ouowurlf.html

[S56] C++：optional
来源：http://dali.0kj1m.cn/Article/details/gt2nkxykcqj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yueranfly.top/Article/details/gt2wivkllyt.html

[S57] C++：编译期常量
来源：http://dali.0kj1m.cn/Article/details/gt2cyszfosy.html

constexpr int N = 10;
来源：http://dali.dashuyun.cn/Article/details/gt2mtqokoga.html

[S58] C++：命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gt2ogebiacb.html

namespace ns { int f() { return 1; } }
来源：http://dali.sweek.top/Article/details/gt2ykqtkzgo.html

[S59] C++：静态断言
来源：http://dali.zdqjudy.top/Article/details/gt2creqqaco.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.c1oappe.top/Article/details/gt2hxqdqrzw.html

[S60] C++：遍历并删除元素
来源：http://dali.hywenlv.cn/Article/details/gt2fnsvairj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daria6918.cn/Article/details/gt2pzladrqr.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2biglvuti.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ueyywpfq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2egwcdvnm.html

[T01] Kotlin：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2bzfycyfi.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gt2akjimatd.html

[T02] Kotlin：变量
来源：http://dali.zdqjudy.top/Article/details/gt2iqzbgtmx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aibaodan.cn/Article/details/gt2rzkjcxum.html

[T03] Kotlin：字符串模板
来源：http://dali.ehwqpu.com/Article/details/gt2hluezcld.html

"值: $b"
来源：http://dali.bjfxy.top/Article/details/gt2defocrnu.html

[T04] Kotlin：空安全
来源：http://dali.guannengcc.top/Article/details/gt2kmybfvdh.html

val n: String? = null;  n?.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2afylcyhy.html

[T05] Kotlin：when 表达式
来源：http://dali.ybcxt.top/Article/details/gt2ziecqlao.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258.top/Article/details/gt2cuydrvhs.html

[T06] Kotlin：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gt2mxbkzapy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cdnleiting.top/Article/details/gt2wozuekry.html

[T07] Kotlin：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mjpdiksn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fwfleugo.html

[T08] Kotlin：数据类
来源：http://dali.sxryk.cn/Article/details/gt2fepnvrap.html

data class User(val name: String, val age: Int)
来源：http://dali.smart0.xyz/Article/details/gt2fovbfoyu.html

[T09] Kotlin：扩展函数
来源：http://dali.guowangkeji.top/Article/details/gt2jvritell.html

fun String.exclaim() = this + "!"
来源：http://dali.sufxvd.cn/Article/details/gt2yhrovyol.html

[T10] Kotlin：默认参数
来源：http://dali.yongpay.top/Article/details/gt2kndtaanq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxinkj.top/Article/details/gt2ohtqpexz.html

[T11] Kotlin：协程
来源：http://dali.yueranfly.top/Article/details/gt2nnikagub.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jiagoushi.top/Article/details/gt2qghlzvby.html

[T12] Kotlin：解构声明
来源：http://dali.dianchejie.cn/Article/details/gt2icsylbgn.html

val (a, b) = Pair(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gt2urpwpdqk.html

[T13] Kotlin：只读 Map
来源：http://dali.chenlongwang.top/Article/details/gt2tbixadxw.html

val m = mapOf("a" to 1)
来源：http://dali.zycfv.cn/Article/details/gt2ggqcgfhy.html

[T14] Kotlin：循环
来源：http://dali.smart0.xyz/Article/details/gt2khhwdewm.html

for (i in 1..10) println(i)
来源：http://dali.fzhhl.top/Article/details/gt2hmzoqqtf.html

[T15] Kotlin：接口
来源：http://dali.hnqzz.top/Article/details/gt2kyunpfrg.html

interface Shape { fun area(): Double }
来源：http://dali.fzhhl.top/Article/details/gt2hvrbmlsb.html

[T16] Swift：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2nvalquwg.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tyijohbj.html

[T17] Swift：变量与常量
来源：http://dali.316326.xyz/Article/details/gt2cvrkbzbo.html

var a = 1;  let b = 2
来源：http://dali.jqgfzy.top/Article/details/gt2hniwzniu.html

[T18] Swift：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gt2evjgocna.html

"值: \(b)"
来源：http://dali.wangshuangyany.cn/Article/details/gt2pygstjbj.html

[T19] Swift：可选绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hivadsid.html

if let n = opt { print(n) }
来源：http://dali.haohaochexian.top/Article/details/gt2hewjmgzg.html

[T20] Swift：数组操作
来源：http://dali.zhongyouzk.top/Article/details/gt2vhxijzym.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jianghu66.top/Article/details/gt2kxfjgcjp.html

[T21] Swift：遍历
来源：http://dali.hammf.cn/Article/details/gt2fmgslpyk.html

for x in a { print(x) }
来源：http://dali.chenzaomai.com/Article/details/gt2ytywvcxp.html

[T22] Swift：字典
来源：http://dali.havefunace.top/Article/details/gt2gmrvvupx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.c1oappe.top/Article/details/gt2thuldgky.html

[T23] Swift：函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2vlrvadqf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ydzc1.top/Article/details/gt2nuygmfki.html

[T24] Swift：闭包
来源：http://dali.dianchejie.cn/Article/details/gt2hlhrcuvo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.redwolf501.top/Article/details/gt2qighzvjl.html

[T25] Swift：结构体
来源：http://dali.sysykeji.top/Article/details/gt2abexvirs.html

struct P { var x: Int }
来源：http://dali.9152youxi.cn/Article/details/gt2xypkbtib.html

[T26] Swift：类与重写
来源：http://dali.ybcxt.top/Article/details/gt2uvknjjsc.html

class A: Base { override func f() {} }
来源：http://dali.nanxuanxn.top/Article/details/gt2mrmylocy.html

[T27] Swift：错误处理
来源：http://dali.dianchejie.cn/Article/details/gt2txjbaldr.html

do { try f() } catch { print(error) }
来源：http://dali.mhx1999.top/Article/details/gt2jlqspwfr.html

[T28] Swift：枚举
来源：http://dali.gaohongyu789.top/Article/details/gt2whfqivlr.html

enum Color { case red, green }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qjvrfiud.html

[T29] Swift：guard 提前返回
来源：http://dali.gaohongyu789.top/Article/details/gt2ruxtigbo.html

guard let x = opt else { return }
来源：http://dali.gaohongyu789.top/Article/details/gt2vwujgwls.html

[T30] Swift：协议
来源：http://dali.dashuyun.cn/Article/details/gt2cpgylxki.html

protocol Shape { func area() -> Double }
来源：http://dali.zhengqikj.top/Article/details/gt2rosnemxu.html

[T31] Lua：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2jnkzupyf.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gt2vtleaywm.html

[T32] Lua：局部变量
来源：http://dali.cdnleiting.top/Article/details/gt2uyyhcfrh.html

local a = 1
来源：http://dali.9152youxi.cn/Article/details/gt2esmhvykk.html

[T33] Lua：表（数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bnyhbskc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.aibaodan.cn/Article/details/gt2kqkgmgmo.html

[T34] Lua：遍历表
来源：http://dali.cqqwz.cn/Article/details/gt2wclccygx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xuanzx.com/Article/details/gt2lypdjjaf.html

[T35] Lua：字典表
来源：http://dali.sysykeji.top/Article/details/gt2vjzesgxr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tian-w.cn/Article/details/gt2plwomhix.html

[T36] Lua：函数
来源：http://dali.gogol.net.cn/Article/details/gt2gelsdxqf.html

function add(a, b) return a + b end
来源：http://dali.xziqi.cn/Article/details/gt2cirtonuz.html

[T37] Lua：字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gt2zvduchxm.html

"a" .. "b"
来源：http://dali.sweek.top/Article/details/gt2twrumodz.html

[T38] Lua：条件
来源：http://dali.jinqigufen.top/Article/details/gt2shxrnxjg.html

if x > 0 then print("正") end
来源：http://dali.chenjidiqi.icu/Article/details/gt2qywrpqbn.html

[T39] Lua：模式匹配
来源：http://dali.xuanzx.com/Article/details/gt2klhvhcsh.html

string.find(s, "%d+")
来源：http://dali.xziqi.cn/Article/details/gt2hbchkzed.html

[T40] Lua：元表
来源：http://dali.ybcxt.top/Article/details/gt2utxmhivj.html

setmetatable({}, { __index = base })
来源：http://dali.jqgfzy.top/Article/details/gt2ykpzswbw.html

[T41] Perl：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2fencmnxo.html

print "Hello\n";
来源：http://dali.nanxinkj.top/Article/details/gt2lolhmnvx.html

[T42] Perl：变量类型
来源：http://dali.zycfv.cn/Article/details/gt2gqhlgcyj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ikydqvyk.html

[T43] Perl：字符串插值
来源：http://dali.mhx1999.top/Article/details/gt2bpdosxnw.html

"值: $a"
来源：http://dali.jinqigufen.top/Article/details/gt2cfuquikh.html

[T44] Perl：条件
来源：http://dali.yonumen.top/Article/details/gt2rmqkliwp.html

if ($a > 0) { print "正"; }
来源：http://dali.haohaochexian.top/Article/details/gt2hojjpjut.html

[T45] Perl：数组遍历
来源：http://dali.cqqwz.cn/Article/details/gt2ufeophxz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhengqikj.top/Article/details/gt2xfcecqkf.html

[T46] Perl：哈希操作
来源：http://dali.shangyingyoupin.top/Article/details/gt2wphibzha.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2agvzqeaw.html

[T47] Perl：正则捕获
来源：http://dali.yj202588.top/Article/details/gt2bwflbqfb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ydzc1.top/Article/details/gt2rnhiqkuf.html

[T48] Perl：正则替换
来源：http://dali.yuanzhike.top/Article/details/gt2pkdwymvd.html

$s =~ s/old/new/g;
来源：http://dali.zhoulong.xyz/Article/details/gt2ziklharn.html

[T49] Perl：函数
来源：http://dali.yvedp.cn/Article/details/gt2olxrtntn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gt2tnqsosos.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tnekjyzr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.birdmap.top/Article/details/gt2cnhwlzaw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sxryk.cn/Article/details/gt2svqbmofv.html

[T51] Scala：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2ppozblxk.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gt2nclfhwms.html

[T52] Scala：变量
来源：http://dali.yuxming.cn/Article/details/gt2rqnqqdwy.html

val a = 1;  var b = 2
来源：http://dali.cashguo.top/Article/details/gt2frergdww.html

[T53] Scala：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gt2mvcgktxi.html

s"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gt2zsawzvke.html

[T54] Scala：集合映射
来源：http://dali.dashuyun.cn/Article/details/gt2lesfejga.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2cgzfaoyc.html

[T55] Scala：集合过滤
来源：http://dali.yueranfly.top/Article/details/gt2neldxxhg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2akawrkbk.html

[T56] Scala：样例类
来源：http://dali.yueranfly.top/Article/details/gt2zqpuaiyi.html

case class User(name: String, age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gt2scxzpsbv.html

[T57] Scala：模式匹配
来源：http://dali.yj20258.top/Article/details/gt2chpcwmux.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tian-w.cn/Article/details/gt2pbgtxefb.html

[T58] Scala：函数定义
来源：http://dali.ehwqpu.com/Article/details/gt2egggbhbd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ppjwa.cn/Article/details/gt2bdkniwtx.html

[T59] Scala：循环
来源：http://dali.aibaodan.cn/Article/details/gt2tlzimmft.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2maeiibrj.html

[T60] Scala：折叠
来源：http://dali.hfpthk.cn/Article/details/gt2fenofqtt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.dashuyun.cn/Article/details/gt2zlbbimod.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2fmfrublf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2semaejqh.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ukkjhqix.html

[U01] Py：创建虚拟环境
来源：http://dali.sufxvd.cn/Article/details/gt2vzywbmoy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shzxlz.cn/Article/details/gt2uremrlhx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dashuyun.cn/Article/details/gt2btsatwxj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daxiang520.top/Article/details/gt2mwxqpnko.html

[U03] Py：加载 .env 配置
来源：http://dali.chenlongwang.top/Article/details/gt2mftafbcy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jyoumei.cn/Article/details/gt2mxdpthwm.html

[U04] Py：变量调试打印
来源：http://dali.jlsjyb.cn/Article/details/gt2hrgkifkn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.316326.xyz/Article/details/gt2gfzhisdm.html

[U05] Py：列表去重且保序
来源：http://dali.yueranfly.top/Article/details/gt2zirplodf.html

list(dict.fromkeys(arr))
来源：http://dali.daria6918.cn/Article/details/gt2orpmwxdr.html

[U06] Py：合并两个字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2shqtmhwg.html

{**a, **b}
来源：http://dali.hnxiangtu.top/Article/details/gt2pxkodane.html

[U07] Py：反转字典键值
来源：http://dali.dashuyun.cn/Article/details/gt2iahpgcjx.html

{v: k for k, v in d.items()}
来源：http://dali.nanxinkj.top/Article/details/gt2feoxfbsy.html

[U08] Py：展平二维列表
来源：http://dali.sysykeji.top/Article/details/gt2fneovmll.html

[y for x in nested for y in x]
来源：http://dali.hywenlv.cn/Article/details/gt2rfolizyz.html

[U09] Py：字典取最大值的键
来源：http://dali.dianchejie.cn/Article/details/gt2sittyszu.html

max(d, key=d.get)
来源：http://dali.yongpay.top/Article/details/gt2ceyqrvkl.html

[U10] Py：按值排序字典
来源：http://dali.snrcjt.cn/Article/details/gt2joxmwqfw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hnqzz.top/Article/details/gt2iwuxxxrd.html

[U11] Py：生成器表达式
来源：http://dali.cashguo.top/Article/details/gt2wbbupydb.html

(x * 2 for x in arr)
来源：http://dali.xuanzx.com/Article/details/gt2nsvxbeqg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sysykeji.top/Article/details/gt2knfoypfh.html

Counter(arr).most_common(3)
来源：http://dali.daria6918.cn/Article/details/gt2cgnkyhfp.html

[U13] Py：固定长度队列
来源：http://dali.cashguo.top/Article/details/gt2onrrnhbn.html

deque(maxlen=10)
来源：http://dali.fzhhl.top/Article/details/gt2cpwvhpiw.html

[U14] Py：分组收集到列表
来源：http://dali.vqdsnc.cn/Article/details/gt2mlqnbvmt.html

defaultdict(list)
来源：http://dali.zhoulong.xyz/Article/details/gt2ivrierxg.html

[U15] Py：高精度计时
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lnkbexog.html

t = time.perf_counter()
来源：http://dali.shzxlz.cn/Article/details/gt2arypqbpc.html

[U16] Py：命令行参数解析
来源：http://dali.feifeiyinyue.top/Article/details/gt2ztksyptd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ybcxt.top/Article/details/gt2rrtuwelr.html

[U17] Py：初始化日志
来源：http://dali.dianchejie.cn/Article/details/gt2rnhwcfim.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinqigfzy.top/Article/details/gt2gxmgtjug.html

[U18] Py：预编译正则
来源：http://dali.chenzaomai.com/Article/details/gt2ovkiukde.html

pat = re.compile(r"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gt2rvyqwumf.html

[U19] Py：正则替换带回调
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qkipidco.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.birdmap.top/Article/details/gt2epimiumh.html

[U20] Py：缓存函数结果
来源：http://dali.aizwys.cn/Article/details/gt2ipmwmuhp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhiwuduotai.top/Article/details/gt2svffrvfw.html

[U21] Py：自定义上下文管理器
来源：http://dali.gotoacloud.top/Article/details/gt2wecoeqpt.html

@contextlib.contextmanager
来源：http://dali.ydzc1.top/Article/details/gt2gsranxiv.html

[U22] Py：矩阵转置
来源：http://dali.shangyingyoupin.top/Article/details/gt2hpzdsvhy.html

list(zip(*m))
来源：http://dali.ydzc1.top/Article/details/gt2wfjefmfz.html

[U23] Py：分块读取大文件
来源：http://dali.gaohongyu789.top/Article/details/gt2phgrwxjl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rzjqtqen.html

[U24] Py：路径操作
来源：http://dali.yanxiufei.cn/Article/details/gt2lsabzqll.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gt2ynhmdymz.html

[U25] Py：CSV 按字典读
来源：http://dali.sufxvd.cn/Article/details/gt2oxlzhkwr.html

csv.DictReader(f)
来源：http://dali.cqqwz.cn/Article/details/gt2hdmlrfil.html

[U26] Py：并发下载
来源：http://dali.zycfv.cn/Article/details/gt2usprhuvn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hnqzz.top/Article/details/gt2zdxphugl.html

[U27] Py：异步 HTTP
来源：http://dali.gaohongyu789.top/Article/details/gt2elifuptt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jyoumei.cn/Article/details/gt2kpwmqypt.html

[U28] Py：类型别名
来源：http://dali.feifeiyinyue.top/Article/details/gt2xrowdglh.html

UserId = int
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqtntvwu.html

[U29] Py：属性校验
来源：http://dali.nwbrower.top/Article/details/gt2pyxwpynd.html

@property 与 @x.setter 配合
来源：http://dali.fengsongda.top/Article/details/gt2bgcjkghq.html

[U30] Py：数据类
来源：http://dali.mhx1999.top/Article/details/gt2ftlowijn.html

@dataclass(slots=True)
来源：http://dali.hywenlv.cn/Article/details/gt2gbywtvec.html

[U31] Py：单测
来源：http://dali.chenlongwang.top/Article/details/gt2iiffuaxi.html

python -m pytest -q
来源：http://dali.9152youxi.cn/Article/details/gt2kbyzojbs.html

[U32] Py：代码格式化
来源：http://dali.jlsjyb.cn/Article/details/gt2atgxeqkl.html

ruff format . && ruff check --fix .
来源：http://dali.c1oappe.top/Article/details/gt2pasehvfx.html

[U33] Py：打包发布
来源：http://dali.dashuyun.cn/Article/details/gt2jdugcvwx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.smart0.xyz/Article/details/gt2daeufmkv.html

[U34] Py：判断编码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sblosabh.html

chardet.detect(raw)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ffdfxens.html

[U35] Py：发送邮件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bwsuqdbz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cqqwz.cn/Article/details/gt2xhxoacht.html

[U36] Py：定时任务
来源：http://dali.nanxinkj.top/Article/details/gt2qhgmaqmj.html

schedule.every(10).minutes.do(job)
来源：http://dali.c1oappe.top/Article/details/gt2uxbuthgv.html

[U37] Py：读写 Excel
来源：http://dali.cdnleiting.top/Article/details/gt2gindemsi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zxpmgtrr.html

[U38] Py：获取脚本所在目录
来源：http://dali.quarkkingdee.top/Article/details/gt2bjtktvsk.html

Path(__file__).resolve().parent
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qteylyvr.html

[U39] Py：判断是否在交互环境
来源：http://dali.xinyue.icu/Article/details/gt2yarvvqrg.html

sys.stdout.isatty()
来源：http://dali.cucudq.cn/Article/details/gt2qxgiipip.html

[U40] Py：打印到标准错误
来源：http://dali.chenlongwang.top/Article/details/gt2mpmhfzem.html

print("err", file=sys.stderr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emlmqhyc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ybcxt.top/Article/details/gt2lxabfenf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sysykeji.top/Article/details/gt2aqwsazfo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xziqi.cn/Article/details/gt2hkcygfmg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmetgrb.html

[U43] PHP：声明命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gt2igtwgymr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2aafkqvpt.html

[U44] PHP：开启严格类型
来源：http://dali.ppjwa.cn/Article/details/gt2aokytzxk.html

declare(strict_types=1);
来源：http://dali.fzhhl.top/Article/details/gt2ktyjynkt.html


<!-- 参考信息 -->