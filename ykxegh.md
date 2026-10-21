代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.pengpengdd.cyou/Article/details/gtfyjbfgmn.html

[S23] C：随机数
来源：http://dali.nanxuanxn.top/Article/details/gteqechelg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.haohaochexian.top/Article/details/gtkunqsmoo.html

[S24] C：获取本地时间
来源：http://dali.hammf.cn/Article/details/gtazfpevjd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuxming.cn/Article/details/gtagwxwbnc.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmcwetbe.html

memcpy(dst, src, n);
来源：http://dali.zhixingplan.top/Article/details/gtpgougale.html

[S26] C：内存清零
来源：http://dali.guannengcc.top/Article/details/gtcslxoguj.html

memset(a, 0, sizeof a);
来源：http://dali.jqgfzy.top/Article/details/gtwdqwhglp.html

[S27] C：定义常量
来源：http://dali.yonumen.top/Article/details/gtksbguxkr.html

const double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtvjtnomvj.html

[S28] C：静态变量
来源：http://dali.vqdsnc.cn/Article/details/gtsvvsgtec.html

static int counter = 0;
来源：http://dali.havefunace.top/Article/details/gtpxtkwzgp.html

[S29] C：变参函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqcnsrfvj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.bjfxy.top/Article/details/gthkfjegqd.html

[S30] C：头文件保护
来源：http://dali.yangfankeji.com/Article/details/gtqdehsmky.html

#ifndef X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttualtnwy.html

#define X_H
来源：http://dali.jiagoushi.top/Article/details/gtcgbxlbzt.html

#endif
来源：http://dali.kuanghao11.cn/Article/details/gtlqbpxhiz.html

[S31] C++：Hello World
来源：http://dali.mhx1999.top/Article/details/gtqmqmvhly.html

#include <iostream>
来源：http://dali.vqdsnc.cn/Article/details/gtnnuuedbm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.quarkkingdee.top/Article/details/gtxfleidpz.html

[S32] C++：字符串
来源：http://dali.jiagoushi.top/Article/details/gtfumchfax.html

std::string s = "hi";  s += "!";
来源：http://dali.yuanzhike.top/Article/details/gtcbqpccme.html

[S33] C++：vector 增删
来源：http://dali.shuidangran.top/Article/details/gtbyqfpqnh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ppjwa.cn/Article/details/gtglhuciha.html

[S34] C++：遍历 vector
来源：http://dali.gotoacloud.top/Article/details/gttklfutgd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jianghu66.top/Article/details/gtvvywcrgq.html

[S35] C++：map
来源：http://dali.hongshengwenyu.top/Article/details/gtyvyrxwqs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtybkbeshc.html

[S36] C++：unordered_map
来源：http://dali.yanxiufei.cn/Article/details/gtiotqmkio.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdcozbjn.html

[S37] C++：set
来源：http://dali.andypj.xyz/Article/details/gtqrqmlvjz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuanzhike.top/Article/details/gtwarrnqdq.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gtofmesrta.html

std::sort(v.begin(), v.end());
来源：http://dali.0kj1m.cn/Article/details/gtvixynztn.html

[S39] C++：自定义比较器排序
来源：http://dali.ydzc1.top/Article/details/gtcfkwriux.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinghuilouyu.cn/Article/details/gthabtymzy.html

[S40] C++：查找元素
来源：http://dali.yonumen.top/Article/details/gtgoiffyhg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ydzc1.top/Article/details/gtdanyfanj.html

[S41] C++：类与构造函数
来源：http://dali.cashguo.top/Article/details/gtlqsiwzoq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daria6918.cn/Article/details/gtncxwovwp.html

[S42] C++：继承与虚函数
来源：http://dali.yueranfly.top/Article/details/gtzqgepxhp.html

class B : public Base { public: void f() override {} };
来源：http://dali.daria6918.cn/Article/details/gtycgkhala.html

[S43] C++：智能指针
来源：http://dali.gzhubu.top/Article/details/gtlbysdtlw.html

auto p = std::make_unique<int>(5);
来源：http://dali.tianlin.xyz/Article/details/gtbkwqicfx.html

[S44] C++：引用传参
来源：http://dali.smart0.xyz/Article/details/gteeapemev.html

void inc(int &x) { ++x; }
来源：http://dali.jyoumei.cn/Article/details/gtnicqwzkh.html

[S45] C++：lambda
来源：http://dali.yangfankeji.com/Article/details/gtgtfczmvw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tian-w.cn/Article/details/gtfjwjclab.html

[S46] C++：函数模板
来源：http://dali.vqdsnc.cn/Article/details/gtffcnkhms.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.snrcjt.cn/Article/details/gtzqrvtpzw.html

[S47] C++：结构化绑定遍历
来源：http://dali.iojbl.cn/Article/details/gtiljqmhse.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hammf.cn/Article/details/gtxisiecoa.html

[S48] C++：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtaaklcfvf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shuidangran.top/Article/details/gtwenlyluf.html

while (std::getline(in, line)) { }
来源：http://dali.sweek.top/Article/details/gtweixwgsk.html

[S49] C++：写文件
来源：http://dali.jyoumei.cn/Article/details/gtvtuanjvu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxinkj.top/Article/details/gtznvcughv.html

[S50] C++：格式化数字
来源：http://dali.tanke756.top/Article/details/gtjchjrufb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtubydfser.html

[S51] C++：显式类型转换
来源：http://dali.yueranfly.top/Article/details/gtrvluleae.html

static_cast<double>(a) / b
来源：http://dali.sufxvd.cn/Article/details/gtxxhajkhm.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxuanxn.top/Article/details/gtnfdhllur.html

int size() const noexcept { return n_; }
来源：http://dali.yonumen.top/Article/details/gtldekqohn.html

[S53] C++：移动语义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqrwzrhq.html

std::vector<int> w = std::move(v);
来源：http://dali.xziqi.cn/Article/details/gtqmlyvkgx.html

[S54] C++：异常处理
来源：http://dali.svipenyu.cn/Article/details/gttnyupgne.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xziqi.cn/Article/details/gtpeffpkxp.html

[S55] C++：结构化绑定
来源：http://dali.yuxming.cn/Article/details/gtzqtsspea.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtuoyyjihb.html

[S56] C++：optional
来源：http://dali.zhixingplan.top/Article/details/gtlluxitcw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.haohaochexian.top/Article/details/gtftyfdzqj.html

[S57] C++：编译期常量
来源：http://dali.yvedp.cn/Article/details/gthspfndnd.html

constexpr int N = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtzcjuzxvy.html

[S58] C++：命名空间
来源：http://dali.shuidangran.top/Article/details/gtzynlcclm.html

namespace ns { int f() { return 1; } }
来源：http://dali.meibo888.top/Article/details/gtsouyajbc.html

[S59] C++：静态断言
来源：http://dali.hnxiangtu.top/Article/details/gtfmzxinun.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhixingplan.top/Article/details/gtvloqhspe.html

[S60] C++：遍历并删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtyjhwyhfn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tian-w.cn/Article/details/gthxxilqzr.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtwjoxxquk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuxming.cn/Article/details/gtcjhxkgwr.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtnzjpgjmx.html

[T01] Kotlin：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtryehnslo.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtzkdfhrdu.html

[T02] Kotlin：变量
来源：http://dali.guannengcc.top/Article/details/gtgdulwioe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.feifeiyinyue.top/Article/details/gtvntymonq.html

[T03] Kotlin：字符串模板
来源：http://dali.havefunace.top/Article/details/gtzaatwvbq.html

"值: $b"
来源：http://dali.xylfe.cn/Article/details/gtaeygcfam.html

[T04] Kotlin：空安全
来源：http://dali.hnqzz.top/Article/details/gtrpystbgo.html

val n: String? = null;  n?.length
来源：http://dali.guannengcc.top/Article/details/gtwfxwmmno.html

[T05] Kotlin：when 表达式
来源：http://dali.xinyue.icu/Article/details/gtzvdmzcsl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gthxjksyqm.html

[T06] Kotlin：集合映射
来源：http://dali.gaohongyu789.top/Article/details/gtqbgygwsj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtssdrtvzv.html

[T07] Kotlin：集合过滤
来源：http://dali.redwolf501.top/Article/details/gtitjhvaqt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.quarkkingdee.top/Article/details/gtortumorg.html

[T08] Kotlin：数据类
来源：http://dali.snrcjt.cn/Article/details/gttbqkobmn.html

data class User(val name: String, val age: Int)
来源：http://dali.ivvv.top/Article/details/gtqqahjhuq.html

[T09] Kotlin：扩展函数
来源：http://dali.yonumen.top/Article/details/gtxnvquqbs.html

fun String.exclaim() = this + "!"
来源：http://dali.fzhhl.top/Article/details/gtnjpjpbua.html

[T10] Kotlin：默认参数
来源：http://dali.chenjidiqi.icu/Article/details/gtkxmaxnzz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigufen.top/Article/details/gtohjgeqys.html

[T11] Kotlin：协程
来源：http://dali.sweek.top/Article/details/gtcrfszddp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwiurrigd.html

[T12] Kotlin：解构声明
来源：http://dali.yanxiufei.cn/Article/details/gtzlvkmykw.html

val (a, b) = Pair(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtrmuweaht.html

[T13] Kotlin：只读 Map
来源：http://dali.aibaodan.cn/Article/details/gtdxgppkxg.html

val m = mapOf("a" to 1)
来源：http://dali.sweek.top/Article/details/gtbcwnovnk.html

[T14] Kotlin：循环
来源：http://dali.haohaochexian.top/Article/details/gtjymdjjrg.html

for (i in 1..10) println(i)
来源：http://dali.xinyue.icu/Article/details/gtostwmjmk.html

[T15] Kotlin：接口
来源：http://dali.cucudq.cn/Article/details/gtzkfzyztj.html

interface Shape { fun area(): Double }
来源：http://dali.shuidangran.top/Article/details/gtlaiiubqq.html

[T16] Swift：Hello World
来源：http://dali.yj20258888.top/Article/details/gtljbdgtsk.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gticphdktc.html

[T17] Swift：变量与常量
来源：http://dali.yangfankeji.com/Article/details/gtnziqmukl.html

var a = 1;  let b = 2
来源：http://dali.gogol.net.cn/Article/details/gtoyihmtfd.html

[T18] Swift：字符串插值
来源：http://dali.ivvv.top/Article/details/gtdyfryozv.html

"值: \(b)"
来源：http://dali.jianghu66.top/Article/details/gtmahaptpm.html

[T19] Swift：可选绑定
来源：http://dali.zhongyouzk.top/Article/details/gtplkvalqu.html

if let n = opt { print(n) }
来源：http://dali.shzxlz.cn/Article/details/gtxbmwivgf.html

[T20] Swift：数组操作
来源：http://dali.hammf.cn/Article/details/gtmtrvvouo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.kuanghao11.cn/Article/details/gtlkjepuwc.html

[T21] Swift：遍历
来源：http://dali.mhx1999.top/Article/details/gtwkuwljbz.html

for x in a { print(x) }
来源：http://dali.sufxvd.cn/Article/details/gtyktraydr.html

[T22] Swift：字典
来源：http://dali.xuanzx.com/Article/details/gtsougeidi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.kuanghao11.cn/Article/details/gtcpneagja.html

[T23] Swift：函数
来源：http://dali.zdqjudy.top/Article/details/gtnennlggy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sysykeji.top/Article/details/gtawktwiqt.html

[T24] Swift：闭包
来源：http://dali.jqgufenzy.top/Article/details/gtxqgatfiu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ydzc1.top/Article/details/gtmnzvryjs.html

[T25] Swift：结构体
来源：http://dali.dianchejie.cn/Article/details/gtnjmfbotm.html

struct P { var x: Int }
来源：http://dali.pycfn.com/Article/details/gtlejsbvgo.html

[T26] Swift：类与重写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfotuhvl.html

class A: Base { override func f() {} }
来源：http://dali.pengpengdd.cyou/Article/details/gtdqbjtdku.html

[T27] Swift：错误处理
来源：http://dali.redwolf501.top/Article/details/gtcftlgdyh.html

do { try f() } catch { print(error) }
来源：http://dali.feifeiyinyue.top/Article/details/gtwqghszhg.html

[T28] Swift：枚举
来源：http://dali.yj20258.top/Article/details/gtlenurxij.html

enum Color { case red, green }
来源：http://dali.yj20258888.top/Article/details/gtwxbdkjqh.html

[T29] Swift：guard 提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gtcnbzfcyd.html

guard let x = opt else { return }
来源：http://dali.wangshuangyany.cn/Article/details/gtumqybdwl.html

[T30] Swift：协议
来源：http://dali.jinqigfzy.top/Article/details/gtffmfofcy.html

protocol Shape { func area() -> Double }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxyrhstr.html

[T31] Lua：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtxknusjii.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxppvvuxv.html

[T32] Lua：局部变量
来源：http://dali.yonumen.top/Article/details/gtfmkwpesr.html

local a = 1
来源：http://dali.chenzaomai.com/Article/details/gtsewqkxkl.html

[T33] Lua：表（数组）
来源：http://dali.ivvv.top/Article/details/gtmanabmnb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gzhubu.top/Article/details/gtsykihqns.html

[T34] Lua：遍历表
来源：http://dali.haohaochexian.top/Article/details/gtrdicnenx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yvedp.cn/Article/details/gtpdwnkklq.html

[T35] Lua：字典表
来源：http://dali.birdmap.top/Article/details/gtuvkkdmfu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jqgfzy.top/Article/details/gtgruscpnk.html

[T36] Lua：函数
来源：http://dali.316326.xyz/Article/details/gtezaucgtx.html

function add(a, b) return a + b end
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvphuaxw.html

[T37] Lua：字符串拼接
来源：http://dali.haohaochexian.top/Article/details/gtgwnicxho.html

"a" .. "b"
来源：http://dali.vqdsnc.cn/Article/details/gtogsycget.html

[T38] Lua：条件
来源：http://dali.zhongyouzk.top/Article/details/gtjmzqnlpf.html

if x > 0 then print("正") end
来源：http://dali.gogol.net.cn/Article/details/gtazkvwblx.html

[T39] Lua：模式匹配
来源：http://dali.redwolf501.top/Article/details/gtvhfkdrpj.html

string.find(s, "%d+")
来源：http://dali.aibaodan.cn/Article/details/gtmdcfvnrw.html

[T40] Lua：元表
来源：http://dali.xuanzx.com/Article/details/gtzkunmtkh.html

setmetatable({}, { __index = base })
来源：http://dali.quarkkingdee.top/Article/details/gtdszhmhbz.html

[T41] Perl：Hello World
来源：http://dali.yueranfly.top/Article/details/gtfvrrunhp.html

print "Hello\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczysvkal.html

[T42] Perl：变量类型
来源：http://dali.hnxiangtu.top/Article/details/gtiratfuqs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zdqjudy.top/Article/details/gtefogysux.html

[T43] Perl：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gtsvkxghln.html

"值: $a"
来源：http://dali.xylfe.cn/Article/details/gtdbolyyhv.html

[T44] Perl：条件
来源：http://dali.zhongyouzk.top/Article/details/gtvkjdlngk.html

if ($a > 0) { print "正"; }
来源：http://dali.yvedp.cn/Article/details/gtqtuoifpl.html

[T45] Perl：数组遍历
来源：http://dali.9152youxi.cn/Article/details/gtdpywdxhq.html

for my $x (@arr) { print $x; }
来源：http://dali.cashguo.top/Article/details/gtiryebemw.html

[T46] Perl：哈希操作
来源：http://dali.gaohongyu789.top/Article/details/gtnuhrweij.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj202588.top/Article/details/gteahuzbbx.html

[T47] Perl：正则捕获
来源：http://dali.gzhubu.top/Article/details/gttdaiipta.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.9152youxi.cn/Article/details/gtqxnynmze.html

[T48] Perl：正则替换
来源：http://dali.shzxlz.cn/Article/details/gtymqygpvf.html

$s =~ s/old/new/g;
来源：http://dali.yangfankeji.com/Article/details/gtqzwfdchc.html

[T49] Perl：函数
来源：http://dali.zhixingplan.top/Article/details/gtxqtjtwqi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtxxhkdebz.html

[T50] Perl：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtlvukpkuo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hywenlv.cn/Article/details/gtufpdewvt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yanxiufei.cn/Article/details/gthmmyiqpl.html

[T51] Scala：Hello World
来源：http://dali.yuxming.cn/Article/details/gttldwmesf.html

println("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtifibqvjn.html

[T52] Scala：变量
来源：http://dali.ehwqpu.com/Article/details/gtilmukjqj.html

val a = 1;  var b = 2
来源：http://dali.sxryk.cn/Article/details/gtouyvakkx.html

[T53] Scala：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gthlzzvmjh.html

s"值: $b"
来源：http://dali.c1oappe.top/Article/details/gtbbvgtvdj.html

[T54] Scala：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gtncsanhyq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hnqzz.top/Article/details/gtutbpbhci.html

[T55] Scala：集合过滤
来源：http://dali.c1oappe.top/Article/details/gtvmextakp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxinkj.top/Article/details/gtuiutmjyk.html

[T56] Scala：样例类
来源：http://dali.svipenyu.cn/Article/details/gtffybmlwn.html

case class User(name: String, age: Int)
来源：http://dali.tianlin.xyz/Article/details/gtmurelszf.html

[T57] Scala：模式匹配
来源：http://dali.yanxiufei.cn/Article/details/gtqshzfeop.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtmmtrgw.html

[T58] Scala：函数定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvpehgkk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.9152youxi.cn/Article/details/gtmzfffwfz.html

[T59] Scala：循环
来源：http://dali.jinqigufen.top/Article/details/gtwjnlkmmc.html

for (i <- 1 to 10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gtugbvkmwo.html

[T60] Scala：折叠
来源：http://dali.cqqwz.cn/Article/details/gthyeomeis.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hywenlv.cn/Article/details/gtgwvubigf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtobbevpbn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigfzy.top/Article/details/gtbsfhpldj.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtxbcgmwpw.html

[U01] Py：创建虚拟环境
来源：http://dali.gzhubu.top/Article/details/gtuthkcbuy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.iojbl.cn/Article/details/gtzzjopvro.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhongyouzk.top/Article/details/gtkzikehfy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jyoumei.cn/Article/details/gtltsubmbp.html

[U03] Py：加载 .env 配置
来源：http://dali.hongshengwenyu.top/Article/details/gtvgistncz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhongyouzk.top/Article/details/gtzywnsdrn.html

[U04] Py：变量调试打印
来源：http://dali.sysykeji.top/Article/details/gtjyiqxpcm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuanzx.com/Article/details/gtuonijxav.html

[U05] Py：列表去重且保序
来源：http://dali.zhengqikj.top/Article/details/gttbsyacto.html

list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtwzhrkhyk.html

[U06] Py：合并两个字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtweziblsl.html

{**a, **b}
来源：http://dali.pycfn.com/Article/details/gtninwzijs.html

[U07] Py：反转字典键值
来源：http://dali.zhoulong.xyz/Article/details/gtqouvrvtd.html

{v: k for k, v in d.items()}
来源：http://dali.zycfv.cn/Article/details/gtmijfswib.html

[U08] Py：展平二维列表
来源：http://dali.zhiwuduotai.top/Article/details/gtkssbvpbg.html

[y for x in nested for y in x]
来源：http://dali.zycfv.cn/Article/details/gtmkgdeowm.html

[U09] Py：字典取最大值的键
来源：http://dali.yangfankeji.com/Article/details/gtupfhswka.html

max(d, key=d.get)
来源：http://dali.cdnleiting.top/Article/details/gtlgudsxyg.html

[U10] Py：按值排序字典
来源：http://dali.zdqjudy.top/Article/details/gtdntjorpx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jyoumei.cn/Article/details/gtxuxmqakq.html

[U11] Py：生成器表达式
来源：http://dali.9152youxi.cn/Article/details/gtmeufzzsr.html

(x * 2 for x in arr)
来源：http://dali.snrcjt.cn/Article/details/gtqwttxtud.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.guannengcc.top/Article/details/gtjwhkgdqt.html

Counter(arr).most_common(3)
来源：http://dali.shzxlz.cn/Article/details/gtjtugrkwc.html

[U13] Py：固定长度队列
来源：http://dali.jyoumei.cn/Article/details/gtweyqenuz.html

deque(maxlen=10)
来源：http://dali.guowangkeji.top/Article/details/gtotyjxnit.html

[U14] Py：分组收集到列表
来源：http://dali.gaohongyu789.top/Article/details/gtuxscgkfx.html

defaultdict(list)
来源：http://dali.zhixingplan.top/Article/details/gtwlkyfbes.html

[U15] Py：高精度计时
来源：http://dali.dianchejie.cn/Article/details/gtstsniaqm.html

t = time.perf_counter()
来源：http://dali.jinqigufen.top/Article/details/gtvifpfuwe.html

[U16] Py：命令行参数解析
来源：http://dali.cdnleiting.top/Article/details/gtdilzcbdz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jyoumei.cn/Article/details/gthfvqqjpe.html

[U17] Py：初始化日志
来源：http://dali.cqqwz.cn/Article/details/gtuesvnwhk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daria6918.cn/Article/details/gtpczjqhzx.html

[U18] Py：预编译正则
来源：http://dali.gogol.net.cn/Article/details/gtsqfbawvl.html

pat = re.compile(r"\d+")
来源：http://dali.ybcxt.top/Article/details/gtrkfvljot.html

[U19] Py：正则替换带回调
来源：http://dali.daria6918.cn/Article/details/gtsunvayqh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.meibo888.top/Article/details/gtwxqpggnd.html

[U20] Py：缓存函数结果
来源：http://dali.svipenyu.cn/Article/details/gtegszgplz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.daria6918.cn/Article/details/gtjcrtsxla.html

[U21] Py：自定义上下文管理器
来源：http://dali.guannengcc.top/Article/details/gtkccrlrxy.html

@contextlib.contextmanager
来源：http://dali.iojbl.cn/Article/details/gtkyktwsjz.html

[U22] Py：矩阵转置
来源：http://dali.svipenyu.cn/Article/details/gtkwmvdmji.html

list(zip(*m))
来源：http://dali.bjfxy.top/Article/details/gttdwricaz.html

[U23] Py：分块读取大文件
来源：http://dali.guannengcc.top/Article/details/gtsazaraps.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhoulong.xyz/Article/details/gtqlgpxbjm.html

[U24] Py：路径操作
来源：http://dali.andypj.xyz/Article/details/gtlltzxeqk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gtfivjvipn.html

[U25] Py：CSV 按字典读
来源：http://dali.sxryk.cn/Article/details/gtxrtnyigu.html

csv.DictReader(f)
来源：http://dali.yonumen.top/Article/details/gtvguajqib.html

[U26] Py：并发下载
来源：http://dali.ydzc1.top/Article/details/gtulrjcmvy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shzxlz.cn/Article/details/gtkwuvsnxh.html

[U27] Py：异步 HTTP
来源：http://dali.tian-w.cn/Article/details/gteqykvwkw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.aizwys.cn/Article/details/gtoufttyzp.html

[U28] Py：类型别名
来源：http://dali.dianchejie.cn/Article/details/gteniwipvx.html

UserId = int
来源：http://dali.nanxuanxn.top/Article/details/gtpgeoczed.html

[U29] Py：属性校验
来源：http://dali.shangyingyoupin.top/Article/details/gteihamqsa.html

@property 与 @x.setter 配合
来源：http://dali.daria6918.cn/Article/details/gtgcumncyw.html

[U30] Py：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gtxomvfqmh.html

@dataclass(slots=True)
来源：http://dali.yanxiufei.cn/Article/details/gtotcenyqr.html

[U31] Py：单测
来源：http://dali.yj20258888.top/Article/details/gtqazalxpf.html

python -m pytest -q
来源：http://dali.jianghu66.top/Article/details/gtuvetfzpe.html

[U32] Py：代码格式化
来源：http://dali.aizwys.cn/Article/details/gteoblgpky.html

ruff format . && ruff check --fix .
来源：http://dali.quarkkingdee.top/Article/details/gtogamifff.html

[U33] Py：打包发布
来源：http://dali.dashuyun.cn/Article/details/gtogywmwsm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jqgufenzy.top/Article/details/gtjtknbuwj.html

[U34] Py：判断编码
来源：http://dali.ivvv.top/Article/details/gtumwtydas.html

chardet.detect(raw)
来源：http://dali.nwbrower.top/Article/details/gterdzvnko.html

[U35] Py：发送邮件
来源：http://dali.sysykeji.top/Article/details/gtfgsvuqtr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.wangdashe.top/Article/details/gtqzgavnuy.html

[U36] Py：定时任务
来源：http://dali.sufxvd.cn/Article/details/gthgtgjjfw.html

schedule.every(10).minutes.do(job)
来源：http://dali.bjfxy.top/Article/details/gttlfvgsel.html

[U37] Py：读写 Excel
来源：http://dali.tanke756.top/Article/details/gtxioqyjeu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinqigfzy.top/Article/details/gtaoheougn.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhiwuduotai.top/Article/details/gteauzzzvc.html

Path(__file__).resolve().parent
来源：http://dali.hnqzz.top/Article/details/gtvzamvavl.html

[U39] Py：判断是否在交互环境
来源：http://dali.havefunace.top/Article/details/gtbakoqcfo.html

sys.stdout.isatty()
来源：http://dali.hysaishi.cn/Article/details/gtwawycxgv.html

[U40] Py：打印到标准错误
来源：http://dali.wangdashe.top/Article/details/gtggddgtpy.html

print("err", file=sys.stderr)
来源：http://dali.tanke756.top/Article/details/gtdfumgdko.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj202588.top/Article/details/gtnsciyhpo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.iojbl.cn/Article/details/gtyrfhowyu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhongyouzk.top/Article/details/gtykuqtibx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yanxiufei.cn/Article/details/gtezsudmxk.html

[U43] PHP：声明命名空间
来源：http://dali.yj202588.top/Article/details/gtsgftgljm.html

namespace App\Http;
来源：http://dali.ehwqpu.com/Article/details/gtmzqkugcy.html

[U44] PHP：开启严格类型
来源：http://dali.sxryk.cn/Article/details/gtmmivjxcr.html

declare(strict_types=1);
来源：http://dali.cheryme.top/Article/details/gtffcdtved.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shzxlz.cn/Article/details/gtofwximvq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtbhedzyzo.html

[U46] PHP：可空类型
来源：http://dali.tianlin.xyz/Article/details/gtaxjdhelp.html

?string $name = null
来源：http://dali.havefunace.top/Article/details/gtghxfisha.html


<!-- 参考信息 -->