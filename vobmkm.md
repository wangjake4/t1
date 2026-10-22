代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dashuyun.cn/Article/details/gtlzsmjaqi.html

[S23] C：随机数
来源：http://dali.cqqwz.cn/Article/details/gtinyfucfj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbawrtxu.html

[S24] C：获取本地时间
来源：http://dali.gzhubu.top/Article/details/gtpusvhuyb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ehwqpu.com/Article/details/gtdqjpuscn.html

[S25] C：内存拷贝
来源：http://dali.ydzc1.top/Article/details/gtivscyrrm.html

memcpy(dst, src, n);
来源：http://dali.jyoumei.cn/Article/details/gtqjuekkpm.html

[S26] C：内存清零
来源：http://dali.0kj1m.cn/Article/details/gtgtgtpgjo.html

memset(a, 0, sizeof a);
来源：http://dali.dashuyun.cn/Article/details/gtyqmpsdjo.html

[S27] C：定义常量
来源：http://dali.zhoulong.xyz/Article/details/gtvsxsjenz.html

const double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtiowfhtus.html

[S28] C：静态变量
来源：http://dali.hnqzz.top/Article/details/gtiupsdfbs.html

static int counter = 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtniooftid.html

[S29] C：变参函数
来源：http://dali.shangyingyoupin.top/Article/details/gtwortsiil.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfopohwvk.html

[S30] C：头文件保护
来源：http://dali.shangyingyoupin.top/Article/details/gtuxqhouzb.html

#ifndef X_H
来源：http://dali.bjfxy.top/Article/details/gtunvqivbk.html

#define X_H
来源：http://dali.wangshuangyany.cn/Article/details/gttlyylzfe.html

#endif
来源：http://dali.xylfe.cn/Article/details/gthpctxedk.html

[S31] C++：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gthjsyllps.html

#include <iostream>
来源：http://dali.yanxiufei.cn/Article/details/gtqgqdgzfq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gaohongyu789.top/Article/details/gtyxywisrr.html

[S32] C++：字符串
来源：http://dali.svipenyu.cn/Article/details/gtqytyxjod.html

std::string s = "hi";  s += "!";
来源：http://dali.chenjidiqi.icu/Article/details/gtempgvzib.html

[S33] C++：vector 增删
来源：http://dali.cdnleiting.top/Article/details/gtftivyhrq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cqqwz.cn/Article/details/gtbfyxzcrn.html

[S34] C++：遍历 vector
来源：http://dali.shzxlz.cn/Article/details/gtkzcgyaha.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jlsjyb.cn/Article/details/gtwhnqpcwk.html

[S35] C++：map
来源：http://dali.jinghuilouyu.cn/Article/details/gtodkfawcn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtuhvwvxxk.html

[S36] C++：unordered_map
来源：http://dali.yanxiufei.cn/Article/details/gtyutoxrvf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtwmbmqllh.html

[S37] C++：set
来源：http://dali.nanxinkj.top/Article/details/gtdfmucxwd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangdashe.top/Article/details/gtsvexujmq.html

[S38] C++：排序
来源：http://dali.guowangkeji.top/Article/details/gtfgrdhgsb.html

std::sort(v.begin(), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gtvvewhdpi.html

[S39] C++：自定义比较器排序
来源：http://dali.shzxlz.cn/Article/details/gtgoywljgv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zycfv.cn/Article/details/gtxaeiwlvz.html

[S40] C++：查找元素
来源：http://dali.shangyingyoupin.top/Article/details/gtsfhvjfrx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuanzhike.top/Article/details/gtjphafyvb.html

[S41] C++：类与构造函数
来源：http://dali.havefunace.top/Article/details/gtdnwarzax.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shzxlz.cn/Article/details/gtobrlxayi.html

[S42] C++：继承与虚函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxwdyvrf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhoulong.xyz/Article/details/gttbwaidnv.html

[S43] C++：智能指针
来源：http://dali.chenzaomai.com/Article/details/gteskhflmb.html

auto p = std::make_unique<int>(5);
来源：http://dali.cdnleiting.top/Article/details/gtqlyeoxdd.html

[S44] C++：引用传参
来源：http://dali.yj202588.top/Article/details/gthqlimzdf.html

void inc(int &x) { ++x; }
来源：http://dali.gzhubu.top/Article/details/gteojsqobd.html

[S45] C++：lambda
来源：http://dali.yj20258888.top/Article/details/gtwfbvyodh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gtnjsqlysj.html

[S46] C++：函数模板
来源：http://dali.chenlongwang.top/Article/details/gtgszizjxk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sweek.top/Article/details/gtvklpystr.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnxiangtu.top/Article/details/gtoaedociu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cqqwz.cn/Article/details/gtvquorxmm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gttkubmdvx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cqqwz.cn/Article/details/gtioxlmqxq.html

while (std::getline(in, line)) { }
来源：http://dali.yuxming.cn/Article/details/gtyqovhxur.html

[S49] C++：写文件
来源：http://dali.sysykeji.top/Article/details/gtcghvulfn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yongpay.top/Article/details/gthrnzeqpa.html

[S50] C++：格式化数字
来源：http://dali.jyoumei.cn/Article/details/gtprivnkld.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtweqppiju.html

[S51] C++：显式类型转换
来源：http://dali.yj202588.top/Article/details/gtktnpzzcy.html

static_cast<double>(a) / b
来源：http://dali.zhixingplan.top/Article/details/gtlowskzsl.html

[S52] C++：const 与 noexcept
来源：http://dali.iojbl.cn/Article/details/gtmkybzdmd.html

int size() const noexcept { return n_; }
来源：http://dali.shuidangran.top/Article/details/gtdpyxhcif.html

[S53] C++：移动语义
来源：http://dali.xuanzx.com/Article/details/gtjlqbrysr.html

std::vector<int> w = std::move(v);
来源：http://dali.fengsongda.top/Article/details/gtbzvjnfxd.html

[S54] C++：异常处理
来源：http://dali.pengpengdd.cyou/Article/details/gtyanydhde.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ydzc1.top/Article/details/gtpamwdghw.html

[S55] C++：结构化绑定
来源：http://dali.hongshengwenyu.top/Article/details/gthjbxocax.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangdashe.top/Article/details/gtvqbmtjsx.html

[S56] C++：optional
来源：http://dali.aizwys.cn/Article/details/gtxxgpvhxz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.9152youxi.cn/Article/details/gtkzoylkti.html

[S57] C++：编译期常量
来源：http://dali.shzxlz.cn/Article/details/gtooaozwio.html

constexpr int N = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtuthsczsy.html

[S58] C++：命名空间
来源：http://dali.ybcxt.top/Article/details/gtjykedrrk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gtnqncumkk.html

[S59] C++：静态断言
来源：http://dali.316326.xyz/Article/details/gttohukupl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigufen.top/Article/details/gtmanrxlrm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtsneestdi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yongpay.top/Article/details/gtnkuhrtok.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtflbtuogz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.snrcjt.cn/Article/details/gtacxtaknn.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtfnrtetnd.html

[T01] Kotlin：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtngimtszt.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gtbknneyyn.html

[T02] Kotlin：变量
来源：http://dali.jyoumei.cn/Article/details/gtxiajjcxk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenjidiqi.icu/Article/details/gtybagatih.html

[T03] Kotlin：字符串模板
来源：http://dali.hnqzz.top/Article/details/gtwqbenajy.html

"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gthuuewxgg.html

[T04] Kotlin：空安全
来源：http://dali.andypj.xyz/Article/details/gtadmgmzqu.html

val n: String? = null;  n?.length
来源：http://dali.sufxvd.cn/Article/details/gtyunmyzeg.html

[T05] Kotlin：when 表达式
来源：http://dali.smart0.xyz/Article/details/gtgomblgli.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenzaomai.com/Article/details/gtlqmpaimt.html

[T06] Kotlin：集合映射
来源：http://dali.ybcxt.top/Article/details/gtbvkawonx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtawkcpifa.html

[T07] Kotlin：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gttnckjrwz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tianlin.xyz/Article/details/gtripsxpfg.html

[T08] Kotlin：数据类
来源：http://dali.cucudq.cn/Article/details/gtkxbimvqa.html

data class User(val name: String, val age: Int)
来源：http://dali.yuxming.cn/Article/details/gtgftolxjc.html

[T09] Kotlin：扩展函数
来源：http://dali.jiagoushi.top/Article/details/gtclcgslvw.html

fun String.exclaim() = this + "!"
来源：http://dali.gotoacloud.top/Article/details/gtertekbqv.html

[T10] Kotlin：默认参数
来源：http://dali.ppjwa.cn/Article/details/gtimspcbey.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.0kj1m.cn/Article/details/gtoaloilck.html

[T11] Kotlin：协程
来源：http://dali.316326.xyz/Article/details/gtbjtshaxh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cqqwz.cn/Article/details/gtfxajraws.html

[T12] Kotlin：解构声明
来源：http://dali.mhx1999.top/Article/details/gtpabsgoox.html

val (a, b) = Pair(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gteriehgkb.html

[T13] Kotlin：只读 Map
来源：http://dali.jqgfzy.top/Article/details/gtpvwneotm.html

val m = mapOf("a" to 1)
来源：http://dali.aibaodan.cn/Article/details/gtolscghgp.html

[T14] Kotlin：循环
来源：http://dali.nwbrower.top/Article/details/gtkmcsitre.html

for (i in 1..10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gtzdppwnjg.html

[T15] Kotlin：接口
来源：http://dali.gaohongyu789.top/Article/details/gtwznmcuvo.html

interface Shape { fun area(): Double }
来源：http://dali.yj202588.top/Article/details/gtfgvxsobc.html

[T16] Swift：Hello World
来源：http://dali.iojbl.cn/Article/details/gtdttnyhzg.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtxmekoheh.html

[T17] Swift：变量与常量
来源：http://dali.xziqi.cn/Article/details/gtqftdahsn.html

var a = 1;  let b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqirjxtkh.html

[T18] Swift：字符串插值
来源：http://dali.sweek.top/Article/details/gtfwsstnls.html

"值: \(b)"
来源：http://dali.zhixingplan.top/Article/details/gtqbpmacuj.html

[T19] Swift：可选绑定
来源：http://dali.yuxming.cn/Article/details/gtlckiaffj.html

if let n = opt { print(n) }
来源：http://dali.xuetiantiany.cn/Article/details/gtevxjhfev.html

[T20] Swift：数组操作
来源：http://dali.hammf.cn/Article/details/gtgwduanrw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hysaishi.cn/Article/details/gtwdirjvea.html

[T21] Swift：遍历
来源：http://dali.redwolf501.top/Article/details/gtqvqpwubs.html

for x in a { print(x) }
来源：http://dali.chenjidiqi.icu/Article/details/gtmibcbzvf.html

[T22] Swift：字典
来源：http://dali.jqgufenzy.top/Article/details/gtqfcceqxg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ivvv.top/Article/details/gtufsearqk.html

[T23] Swift：函数
来源：http://dali.gzhubu.top/Article/details/gtzwiuoqga.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gotoacloud.top/Article/details/gtafbrinxt.html

[T24] Swift：闭包
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkofpsfg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gtpgbxlure.html

[T25] Swift：结构体
来源：http://dali.redwolf501.top/Article/details/gtvmokzxkh.html

struct P { var x: Int }
来源：http://dali.hnxiangtu.top/Article/details/gtvicbjget.html

[T26] Swift：类与重写
来源：http://dali.jinqigufen.top/Article/details/gteauzkfbv.html

class A: Base { override func f() {} }
来源：http://dali.gogol.net.cn/Article/details/gtxalkmtqc.html

[T27] Swift：错误处理
来源：http://dali.gzhubu.top/Article/details/gtkxyxctds.html

do { try f() } catch { print(error) }
来源：http://dali.hysaishi.cn/Article/details/gtjdaqsxoo.html

[T28] Swift：枚举
来源：http://dali.aizwys.cn/Article/details/gtnidgsfua.html

enum Color { case red, green }
来源：http://dali.ehwqpu.com/Article/details/gtvorogyxa.html

[T29] Swift：guard 提前返回
来源：http://dali.tianlin.xyz/Article/details/gtidkqynqp.html

guard let x = opt else { return }
来源：http://dali.zhoulong.xyz/Article/details/gtryffvpvs.html

[T30] Swift：协议
来源：http://dali.redwolf501.top/Article/details/gtuuvihuqx.html

protocol Shape { func area() -> Double }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkalgyih.html

[T31] Lua：Hello World
来源：http://dali.xinyue.icu/Article/details/gtsemdntxx.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtfobyihan.html

[T32] Lua：局部变量
来源：http://dali.wangdashe.top/Article/details/gtrrbiizyb.html

local a = 1
来源：http://dali.hywenlv.cn/Article/details/gtlqzuwmex.html

[T33] Lua：表（数组）
来源：http://dali.ppjwa.cn/Article/details/gtxkpsjdzu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xuanzx.com/Article/details/gtgbrnjuwx.html

[T34] Lua：遍历表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxcktlnl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shuidangran.top/Article/details/gttqepebzy.html

[T35] Lua：字典表
来源：http://dali.ybcxt.top/Article/details/gtlaxhkzqa.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hfpthk.cn/Article/details/gtfuvlyncs.html

[T36] Lua：函数
来源：http://dali.guannengcc.top/Article/details/gtsaftppjx.html

function add(a, b) return a + b end
来源：http://dali.sysykeji.top/Article/details/gtmsjpsoes.html

[T37] Lua：字符串拼接
来源：http://dali.xylfe.cn/Article/details/gtprwrrtbt.html

"a" .. "b"
来源：http://dali.guowangkeji.top/Article/details/gtncldoxzj.html

[T38] Lua：条件
来源：http://dali.ybcxt.top/Article/details/gtymlxemsr.html

if x > 0 then print("正") end
来源：http://dali.hysaishi.cn/Article/details/gtkxrzofpq.html

[T39] Lua：模式匹配
来源：http://dali.zhongyouzk.top/Article/details/gtrvbpxxps.html

string.find(s, "%d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxawdfoe.html

[T40] Lua：元表
来源：http://dali.yj202588.top/Article/details/gtlxevhepq.html

setmetatable({}, { __index = base })
来源：http://dali.chenlongwang.top/Article/details/gtbrcvczpl.html

[T41] Perl：Hello World
来源：http://dali.hnqzz.top/Article/details/gtguedwfxt.html

print "Hello\n";
来源：http://dali.feifeiyinyue.top/Article/details/gtfjkmssmg.html

[T42] Perl：变量类型
来源：http://dali.cheryme.top/Article/details/gtbgajpdnn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.316326.xyz/Article/details/gttsctnufc.html

[T43] Perl：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gtkfqhaiis.html

"值: $a"
来源：http://dali.zycfv.cn/Article/details/gtwemrqjpc.html

[T44] Perl：条件
来源：http://dali.smart0.xyz/Article/details/gtgkgquoxp.html

if ($a > 0) { print "正"; }
来源：http://dali.ppjwa.cn/Article/details/gtzrieyrhd.html

[T45] Perl：数组遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtjscefrbm.html

for my $x (@arr) { print $x; }
来源：http://dali.cqqwz.cn/Article/details/gttsvfsfpt.html

[T46] Perl：哈希操作
来源：http://dali.daxiang520.top/Article/details/gtceitpxlx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhixingplan.top/Article/details/gtwkbgtjmo.html

[T47] Perl：正则捕获
来源：http://dali.xuanzx.com/Article/details/gtiyisughi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yvedp.cn/Article/details/gtbodxgsfc.html

[T48] Perl：正则替换
来源：http://dali.hysaishi.cn/Article/details/gtfpzuixda.html

$s =~ s/old/new/g;
来源：http://dali.guannengcc.top/Article/details/gtlyfwfgsw.html

[T49] Perl：函数
来源：http://dali.xinyue.icu/Article/details/gttrjehqlr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtqormyucy.html

[T50] Perl：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtkhfqszou.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sufxvd.cn/Article/details/gtdgmjwcly.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ppjwa.cn/Article/details/gttytmqnlq.html

[T51] Scala：Hello World
来源：http://dali.gzhubu.top/Article/details/gtsskndinj.html

println("Hello")
来源：http://dali.hysaishi.cn/Article/details/gtxhhgddms.html

[T52] Scala：变量
来源：http://dali.sweek.top/Article/details/gtorpjwrdx.html

val a = 1;  var b = 2
来源：http://dali.dianchejie.cn/Article/details/gtfhbrvder.html

[T53] Scala：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtxfifopfl.html

s"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gtfmxuiekn.html

[T54] Scala：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gtktyafhyb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yj202588.top/Article/details/gtyunyxgxj.html

[T55] Scala：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gtczbbfsde.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyocdhtth.html

[T56] Scala：样例类
来源：http://dali.hysaishi.cn/Article/details/gtncpnwfuy.html

case class User(name: String, age: Int)
来源：http://dali.pengpengdd.cyou/Article/details/gtezkodqjs.html

[T57] Scala：模式匹配
来源：http://dali.yongpay.top/Article/details/gtyswvargo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.bjfxy.top/Article/details/gttjiugjtc.html

[T58] Scala：函数定义
来源：http://dali.fengsongda.top/Article/details/gtisonmqny.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.birdmap.top/Article/details/gtknjqecoi.html

[T59] Scala：循环
来源：http://dali.shuidangran.top/Article/details/gtgzdrvscg.html

for (i <- 1 to 10) println(i)
来源：http://dali.dianchejie.cn/Article/details/gtckzkvvoz.html

[T60] Scala：折叠
来源：http://dali.dashuyun.cn/Article/details/gtwacpzszf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.haohaochexian.top/Article/details/gtghhtvyfm.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gterhpnwre.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hywenlv.cn/Article/details/gtolzygoqm.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtgcezwnxt.html

[U01] Py：创建虚拟环境
来源：http://dali.haohaochexian.top/Article/details/gtlvqqinic.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gtxhzbqtxu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hysaishi.cn/Article/details/gtpajjvyjy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtcicyqovt.html

[U03] Py：加载 .env 配置
来源：http://dali.xuanzx.com/Article/details/gtbqazdzxi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuanzx.com/Article/details/gtnwonmpsa.html

[U04] Py：变量调试打印
来源：http://dali.meibo888.top/Article/details/gtpdfshbfe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj20258888.top/Article/details/gtvgyotjkm.html

[U05] Py：列表去重且保序
来源：http://dali.0kj1m.cn/Article/details/gtuvoyjolj.html

list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gtfipyniky.html

[U06] Py：合并两个字典
来源：http://dali.cdnleiting.top/Article/details/gtvxqjusur.html

{**a, **b}
来源：http://dali.cdnleiting.top/Article/details/gtnxproyst.html

[U07] Py：反转字典键值
来源：http://dali.redwolf501.top/Article/details/gtlojblbca.html

{v: k for k, v in d.items()}
来源：http://dali.yuxming.cn/Article/details/gtkxddavke.html

[U08] Py：展平二维列表
来源：http://dali.vqdsnc.cn/Article/details/gtsjehekhb.html

[y for x in nested for y in x]
来源：http://dali.dashuyun.cn/Article/details/gtvkgsutnr.html

[U09] Py：字典取最大值的键
来源：http://dali.daxiang520.top/Article/details/gtoyepxdzg.html

max(d, key=d.get)
来源：http://dali.jinghuilouyu.cn/Article/details/gtalltjzbr.html

[U10] Py：按值排序字典
来源：http://dali.sufxvd.cn/Article/details/gtufhknsrj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shuidangran.top/Article/details/gtgykyniuk.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkpnxnst.html

(x * 2 for x in arr)
来源：http://dali.9152youxi.cn/Article/details/gtopbgence.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ehwqpu.com/Article/details/gtbedwaweg.html

Counter(arr).most_common(3)
来源：http://dali.wangdashe.top/Article/details/gtfvtnbvpv.html

[U13] Py：固定长度队列
来源：http://dali.gotoacloud.top/Article/details/gtphkdwbct.html

deque(maxlen=10)
来源：http://dali.c1oappe.top/Article/details/gttvzrfely.html

[U14] Py：分组收集到列表
来源：http://dali.jiagoushi.top/Article/details/gtriqfbgea.html

defaultdict(list)
来源：http://dali.fengsongda.top/Article/details/gtvanayuxj.html

[U15] Py：高精度计时
来源：http://dali.hywenlv.cn/Article/details/gtxmglahbn.html

t = time.perf_counter()
来源：http://dali.yj202588.top/Article/details/gtmobzbekf.html

[U16] Py：命令行参数解析
来源：http://dali.hammf.cn/Article/details/gtsybugbyh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.tanke756.top/Article/details/gtlwyhhpyv.html

[U17] Py：初始化日志
来源：http://dali.daria6918.cn/Article/details/gtpsoffcev.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.vqdsnc.cn/Article/details/gttbhhveqn.html

[U18] Py：预编译正则
来源：http://dali.yj202588.top/Article/details/gtmftdberb.html

pat = re.compile(r"\d+")
来源：http://dali.hysaishi.cn/Article/details/gtjwddchur.html

[U19] Py：正则替换带回调
来源：http://dali.gogol.net.cn/Article/details/gtizhujycg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jyoumei.cn/Article/details/gtvwjtscqa.html

[U20] Py：缓存函数结果
来源：http://dali.smart0.xyz/Article/details/gtmxztgwak.html

@functools.lru_cache(maxsize=None)
来源：http://dali.pycfn.com/Article/details/gthsuynkcs.html

[U21] Py：自定义上下文管理器
来源：http://dali.havefunace.top/Article/details/gtscyorbos.html

@contextlib.contextmanager
来源：http://dali.jqgufenzy.top/Article/details/gtrquqxsts.html

[U22] Py：矩阵转置
来源：http://dali.daria6918.cn/Article/details/gtjkaqkadp.html

list(zip(*m))
来源：http://dali.yonumen.top/Article/details/gtuylyvbzd.html

[U23] Py：分块读取大文件
来源：http://dali.haohaochexian.top/Article/details/gtxxzmygav.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhengqikj.top/Article/details/gtzmtpuxvh.html

[U24] Py：路径操作
来源：http://dali.tian-w.cn/Article/details/gtmtuqgsbo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gtooarwnbl.html

[U25] Py：CSV 按字典读
来源：http://dali.cucudq.cn/Article/details/gtspvmjvky.html

csv.DictReader(f)
来源：http://dali.zycfv.cn/Article/details/gtpbwbtsls.html

[U26] Py：并发下载
来源：http://dali.zhiwuduotai.top/Article/details/gtartxnoio.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.fzhhl.top/Article/details/gtzpegrqid.html

[U27] Py：异步 HTTP
来源：http://dali.cdnleiting.top/Article/details/gtphxhwdop.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuxming.cn/Article/details/gtbvsjboeh.html

[U28] Py：类型别名
来源：http://dali.sweek.top/Article/details/gtfoeonpvp.html

UserId = int
来源：http://dali.zhiwuduotai.top/Article/details/gtmjaboghv.html

[U29] Py：属性校验
来源：http://dali.ppjwa.cn/Article/details/gtrbozsbob.html

@property 与 @x.setter 配合
来源：http://dali.gotoacloud.top/Article/details/gtlvmvmlbu.html

[U30] Py：数据类
来源：http://dali.cashguo.top/Article/details/gtwtcjqssh.html

@dataclass(slots=True)
来源：http://dali.gotoacloud.top/Article/details/gtaikysaoi.html

[U31] Py：单测
来源：http://dali.xylfe.cn/Article/details/gtboxpnreu.html

python -m pytest -q
来源：http://dali.ydzc1.top/Article/details/gtymmclbud.html

[U32] Py：代码格式化
来源：http://dali.mhx1999.top/Article/details/gtgwghliye.html

ruff format . && ruff check --fix .
来源：http://dali.snrcjt.cn/Article/details/gtodlynjva.html

[U33] Py：打包发布
来源：http://dali.cucudq.cn/Article/details/gtejxulzgz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.havefunace.top/Article/details/gterzeqgmt.html

[U34] Py：判断编码
来源：http://dali.zhongyouzk.top/Article/details/gtnkceyiaw.html

chardet.detect(raw)
来源：http://dali.guowangkeji.top/Article/details/gtkkifayyq.html

[U35] Py：发送邮件
来源：http://dali.aizwys.cn/Article/details/gtgymnqhca.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hongshengwenyu.top/Article/details/gtwdbvgenq.html

[U36] Py：定时任务
来源：http://dali.guannengcc.top/Article/details/gtyrzhpfjd.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj20258.top/Article/details/gtmiienusq.html

[U37] Py：读写 Excel
来源：http://dali.xziqi.cn/Article/details/gteuokdnfm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.wangshuangyany.cn/Article/details/gtewtmabwx.html

[U38] Py：获取脚本所在目录
来源：http://dali.jqgufenzy.top/Article/details/gtggvlkkft.html

Path(__file__).resolve().parent
来源：http://dali.quarkkingdee.top/Article/details/gtxaxzeeyr.html

[U39] Py：判断是否在交互环境
来源：http://dali.yongpay.top/Article/details/gtoekiapwi.html

sys.stdout.isatty()
来源：http://dali.daxiang520.top/Article/details/gthowbjrsl.html

[U40] Py：打印到标准错误
来源：http://dali.yueranfly.top/Article/details/gtcatuwhvn.html

print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gtcyfkmybx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.0kj1m.cn/Article/details/gtfisofqrp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jiagoushi.top/Article/details/gtuagoqerg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.dianchejie.cn/Article/details/gtjxmovorf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yonumen.top/Article/details/gtzuazhbde.html

[U43] PHP：声明命名空间
来源：http://dali.cucudq.cn/Article/details/gteeevisyf.html

namespace App\Http;
来源：http://dali.ehwqpu.com/Article/details/gtduwpbtaq.html

[U44] PHP：开启严格类型
来源：http://dali.jyoumei.cn/Article/details/gtikhbddwq.html

declare(strict_types=1);
来源：http://dali.wangdashe.top/Article/details/gtrrztztrp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpikikfvs.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtaffjggkn.html

[U46] PHP：可空类型
来源：http://dali.zhixingplan.top/Article/details/gtuqnssyaq.html

?string $name = null
来源：http://dali.guannengcc.top/Article/details/gtbruzljxg.html


<!-- 参考信息 -->