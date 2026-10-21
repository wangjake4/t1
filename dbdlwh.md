代发 wailian999

int main(int argc, char **argv)
来源：http://dali.zhoulong.xyz/Article/details/gtbncastzy.html

[S19] C：快速排序
来源：http://dali.birdmap.top/Article/details/gtcvqvqvny.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gtxvlkxane.html

[S20] C：二分查找
来源：http://dali.wangshuangyany.cn/Article/details/gtsnigkjxb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pycfn.com/Article/details/gtlcrnejba.html

[S21] C：字符类别判断
来源：http://dali.dianchejie.cn/Article/details/gtwzyvbbxv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.9152youxi.cn/Article/details/gtrrlqceeo.html

[S22] C：字符串转数字
来源：http://dali.0kj1m.cn/Article/details/gtnrqfcyoz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ehwqpu.com/Article/details/gtoaczoihp.html

[S23] C：随机数
来源：http://dali.shuidangran.top/Article/details/gtylrxpzvh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.vqdsnc.cn/Article/details/gtjiulqfwc.html

[S24] C：获取本地时间
来源：http://dali.pycfn.com/Article/details/gtqpovnzdd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxinkj.top/Article/details/gtxmltivpc.html

[S25] C：内存拷贝
来源：http://dali.cheryme.top/Article/details/gtusfzxiqv.html

memcpy(dst, src, n);
来源：http://dali.chenjidiqi.icu/Article/details/gtspwiktdq.html

[S26] C：内存清零
来源：http://dali.tian-w.cn/Article/details/gtgpjfcvrv.html

memset(a, 0, sizeof a);
来源：http://dali.svipenyu.cn/Article/details/gtaqophfko.html

[S27] C：定义常量
来源：http://dali.sweek.top/Article/details/gtwazriovw.html

const double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtkckgyhxt.html

[S28] C：静态变量
来源：http://dali.kuanghao11.cn/Article/details/gttallssah.html

static int counter = 0;
来源：http://dali.redwolf501.top/Article/details/gtdvkrpfho.html

[S29] C：变参函数
来源：http://dali.jqgufenzy.top/Article/details/gtoqxjwkcc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jiagoushi.top/Article/details/gtbwsmyxfd.html

[S30] C：头文件保护
来源：http://dali.cucudq.cn/Article/details/gtyankblge.html

#ifndef X_H
来源：http://dali.hnxiangtu.top/Article/details/gtrdmjvzgi.html

#define X_H
来源：http://dali.xuanzx.com/Article/details/gtlvpbjhno.html

#endif
来源：http://dali.hfpthk.cn/Article/details/gtheajzxbx.html

[S31] C++：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtsjgshecd.html

#include <iostream>
来源：http://dali.guowangkeji.top/Article/details/gtpapqgbbj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.birdmap.top/Article/details/gtejnwplcb.html

[S32] C++：字符串
来源：http://dali.yuanzhike.top/Article/details/gtltgncuek.html

std::string s = "hi";  s += "!";
来源：http://dali.nwbrower.top/Article/details/gtkagoejnc.html

[S33] C++：vector 增删
来源：http://dali.jyoumei.cn/Article/details/gtmjyndeew.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yueranfly.top/Article/details/gthpscqsha.html

[S34] C++：遍历 vector
来源：http://dali.wangshuangyany.cn/Article/details/gtjmzhemfu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gaohongyu789.top/Article/details/gtmklhwaex.html

[S35] C++：map
来源：http://dali.jqgfzy.top/Article/details/gtaixdyyxn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtqvdqhxri.html

[S36] C++：unordered_map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtwyvncn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtjtgsqbcg.html

[S37] C++：set
来源：http://dali.feifeiyinyue.top/Article/details/gtqicuvbem.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.andypj.xyz/Article/details/gtgpubmiun.html

[S38] C++：排序
来源：http://dali.yonumen.top/Article/details/gteyamkdja.html

std::sort(v.begin(), v.end());
来源：http://dali.smart0.xyz/Article/details/gtodudjgwt.html

[S39] C++：自定义比较器排序
来源：http://dali.cashguo.top/Article/details/gthuyvyxxh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhengqikj.top/Article/details/gtbqktipyw.html

[S40] C++：查找元素
来源：http://dali.jinqigufen.top/Article/details/gtekehrpjk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gzhubu.top/Article/details/gtupyvzyzb.html

[S41] C++：类与构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtregjeuwp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cheryme.top/Article/details/gtuldgxzja.html

[S42] C++：继承与虚函数
来源：http://dali.aizwys.cn/Article/details/gtlrdinkvp.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhiwuduotai.top/Article/details/gtsehuulzh.html

[S43] C++：智能指针
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzccrpwk.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnxiangtu.top/Article/details/gtkfsktrza.html

[S44] C++：引用传参
来源：http://dali.c1oappe.top/Article/details/gtkotcxhlb.html

void inc(int &x) { ++x; }
来源：http://dali.9152youxi.cn/Article/details/gthxzslduq.html

[S45] C++：lambda
来源：http://dali.hnqzz.top/Article/details/gtwhaaejlv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.bjfxy.top/Article/details/gtonjtecvx.html

[S46] C++：函数模板
来源：http://dali.cdnleiting.top/Article/details/gtvfgxslzp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.mhx1999.top/Article/details/gtnnhujtcj.html

[S47] C++：结构化绑定遍历
来源：http://dali.dianchejie.cn/Article/details/gtmdvnqmsg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fzhhl.top/Article/details/gtzlukjxhq.html

[S48] C++：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtptlxgqkh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guannengcc.top/Article/details/gtwixxmfqu.html

while (std::getline(in, line)) { }
来源：http://dali.yangfankeji.com/Article/details/gtvorlueju.html

[S49] C++：写文件
来源：http://dali.dianchejie.cn/Article/details/gtnrxolaor.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gaohongyu789.top/Article/details/gtjpmbwvcq.html

[S50] C++：格式化数字
来源：http://dali.ybcxt.top/Article/details/gtgqekbqsk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtrzzgztlq.html

[S51] C++：显式类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmliscwsr.html

static_cast<double>(a) / b
来源：http://dali.hammf.cn/Article/details/gtdqmszzqp.html

[S52] C++：const 与 noexcept
来源：http://dali.c1oappe.top/Article/details/gttojhxkos.html

int size() const noexcept { return n_; }
来源：http://dali.hnqzz.top/Article/details/gtwqqsasya.html

[S53] C++：移动语义
来源：http://dali.yongpay.top/Article/details/gtmccynfqi.html

std::vector<int> w = std::move(v);
来源：http://dali.fengsongda.top/Article/details/gtyhaxjfun.html

[S54] C++：异常处理
来源：http://dali.yj20258888.top/Article/details/gtgrnuqbdr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aibaodan.cn/Article/details/gtlalffgvu.html

[S55] C++：结构化绑定
来源：http://dali.snrcjt.cn/Article/details/gtyioebcgh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gtemiszblc.html

[S56] C++：optional
来源：http://dali.gotoacloud.top/Article/details/gtlcorkewp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.0kj1m.cn/Article/details/gtesejwhoo.html

[S57] C++：编译期常量
来源：http://dali.svipenyu.cn/Article/details/gtjzrshdgi.html

constexpr int N = 10;
来源：http://dali.dianchejie.cn/Article/details/gteqqxfpqj.html

[S58] C++：命名空间
来源：http://dali.gotoacloud.top/Article/details/gtaxcbgpra.html

namespace ns { int f() { return 1; } }
来源：http://dali.sxryk.cn/Article/details/gtaxzzucvg.html

[S59] C++：静态断言
来源：http://dali.guannengcc.top/Article/details/gtwoptlhqb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zdqjudy.top/Article/details/gtfabopsud.html

[S60] C++：遍历并删除元素
来源：http://dali.yuanzhike.top/Article/details/gtknwrqyjh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yvedp.cn/Article/details/gtxytrvoyd.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gthslonavd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.haohaochexian.top/Article/details/gtsxjmzyaz.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtgdqahxrh.html

[T01] Kotlin：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtzlrkjjei.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtilyucrqn.html

[T02] Kotlin：变量
来源：http://dali.jinqigfzy.top/Article/details/gtkrsawjqx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ybcxt.top/Article/details/gtczcvlchs.html

[T03] Kotlin：字符串模板
来源：http://dali.gogol.net.cn/Article/details/gtdowpvvqv.html

"值: $b"
来源：http://dali.ehwqpu.com/Article/details/gtsnrokhys.html

[T04] Kotlin：空安全
来源：http://dali.jinqigfzy.top/Article/details/gtckakfmrq.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtboiztf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhoulong.xyz/Article/details/gtfdpclluk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydswmgml.html

[T06] Kotlin：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gtfdxieoxk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtrukfpkak.html

[T07] Kotlin：集合过滤
来源：http://dali.dashuyun.cn/Article/details/gtgfpevpjt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.havefunace.top/Article/details/gtntsygleb.html

[T08] Kotlin：数据类
来源：http://dali.fzhhl.top/Article/details/gtqhntfmun.html

data class User(val name: String, val age: Int)
来源：http://dali.meibo888.top/Article/details/gtwzdkhqts.html

[T09] Kotlin：扩展函数
来源：http://dali.yuanzhike.top/Article/details/gtmlraksyy.html

fun String.exclaim() = this + "!"
来源：http://dali.wangdashe.top/Article/details/gthmmqocst.html

[T10] Kotlin：默认参数
来源：http://dali.guowangkeji.top/Article/details/gtivkcnbwz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhiwuduotai.top/Article/details/gtaupdzscc.html

[T11] Kotlin：协程
来源：http://dali.cheryme.top/Article/details/gtmqmclhxy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.0kj1m.cn/Article/details/gtypwuyfxs.html

[T12] Kotlin：解构声明
来源：http://dali.daria6918.cn/Article/details/gttipwwobf.html

val (a, b) = Pair(1, 2)
来源：http://dali.mhx1999.top/Article/details/gtxfemyaja.html

[T13] Kotlin：只读 Map
来源：http://dali.jqgfzy.top/Article/details/gtvrhpllou.html

val m = mapOf("a" to 1)
来源：http://dali.hywenlv.cn/Article/details/gtwuqxvzgk.html

[T14] Kotlin：循环
来源：http://dali.hfpthk.cn/Article/details/gtmshljzzv.html

for (i in 1..10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gtfvsetccy.html

[T15] Kotlin：接口
来源：http://dali.tian-w.cn/Article/details/gtpodeoxxj.html

interface Shape { fun area(): Double }
来源：http://dali.havefunace.top/Article/details/gtjbqsyqtv.html

[T16] Swift：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtcvlgajax.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtxykflsgp.html

[T17] Swift：变量与常量
来源：http://dali.havefunace.top/Article/details/gtlvipngso.html

var a = 1;  let b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtskxtkkfu.html

[T18] Swift：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtzkltqzdo.html

"值: \(b)"
来源：http://dali.ivvv.top/Article/details/gtfotsancd.html

[T19] Swift：可选绑定
来源：http://dali.nwbrower.top/Article/details/gtriloxuag.html

if let n = opt { print(n) }
来源：http://dali.yuxming.cn/Article/details/gtljyksjly.html

[T20] Swift：数组操作
来源：http://dali.iojbl.cn/Article/details/gtlhqecqcq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.birdmap.top/Article/details/gtndwjurih.html

[T21] Swift：遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtkqvhjtpm.html

for x in a { print(x) }
来源：http://dali.xuanzx.com/Article/details/gtqfiuawnd.html

[T22] Swift：字典
来源：http://dali.shangyingyoupin.top/Article/details/gtfdvakogg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258.top/Article/details/gttcjwqwtx.html

[T23] Swift：函数
来源：http://dali.shangyingyoupin.top/Article/details/gtuxmordmt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtguncalfc.html

[T24] Swift：闭包
来源：http://dali.cdnleiting.top/Article/details/gtnjtnatak.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gteorhezah.html

[T25] Swift：结构体
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrejljkcn.html

struct P { var x: Int }
来源：http://dali.ydzc1.top/Article/details/gtbmhagrir.html

[T26] Swift：类与重写
来源：http://dali.mhx1999.top/Article/details/gtolxylacr.html

class A: Base { override func f() {} }
来源：http://dali.zhongyouzk.top/Article/details/gtftpoxtfn.html

[T27] Swift：错误处理
来源：http://dali.sufxvd.cn/Article/details/gtzuyrjsfx.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gtadsgfblx.html

[T28] Swift：枚举
来源：http://dali.dashuyun.cn/Article/details/gtehmbmufc.html

enum Color { case red, green }
来源：http://dali.andypj.xyz/Article/details/gtaibiktgm.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigfzy.top/Article/details/gtmmrzjxwl.html

guard let x = opt else { return }
来源：http://dali.zhengqikj.top/Article/details/gtzdoxhyha.html

[T30] Swift：协议
来源：http://dali.redwolf501.top/Article/details/gtsxvajnfb.html

protocol Shape { func area() -> Double }
来源：http://dali.gogol.net.cn/Article/details/gtykkrykhj.html

[T31] Lua：Hello World
来源：http://dali.iojbl.cn/Article/details/gterxhzisr.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtglsmrfga.html

[T32] Lua：局部变量
来源：http://dali.smart0.xyz/Article/details/gtgjffsokj.html

local a = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzhjyizu.html

[T33] Lua：表（数组）
来源：http://dali.guowangkeji.top/Article/details/gtuulhtali.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwskeescj.html

[T34] Lua：遍历表
来源：http://dali.jianghu66.top/Article/details/gtcfabnwom.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yvedp.cn/Article/details/gttqmbhuel.html

[T35] Lua：字典表
来源：http://dali.yueranfly.top/Article/details/gtezkdyowb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258.top/Article/details/gtreyhwrrf.html

[T36] Lua：函数
来源：http://dali.mhx1999.top/Article/details/gtpoztbyrs.html

function add(a, b) return a + b end
来源：http://dali.yj202588.top/Article/details/gthhotufbb.html

[T37] Lua：字符串拼接
来源：http://dali.yonumen.top/Article/details/gtuorpupfi.html

"a" .. "b"
来源：http://dali.dianchejie.cn/Article/details/gtspxwdefs.html

[T38] Lua：条件
来源：http://dali.havefunace.top/Article/details/gtagewhyfz.html

if x > 0 then print("正") end
来源：http://dali.zdqjudy.top/Article/details/gtsnvsvigl.html

[T39] Lua：模式匹配
来源：http://dali.ivvv.top/Article/details/gtdurabupk.html

string.find(s, "%d+")
来源：http://dali.ybcxt.top/Article/details/gtypyraree.html

[T40] Lua：元表
来源：http://dali.yangfankeji.com/Article/details/gttnsnijko.html

setmetatable({}, { __index = base })
来源：http://dali.yuanzhike.top/Article/details/gtomvqzbsv.html

[T41] Perl：Hello World
来源：http://dali.guowangkeji.top/Article/details/gttjsktyha.html

print "Hello\n";
来源：http://dali.jqgfzy.top/Article/details/gtakrnpipl.html

[T42] Perl：变量类型
来源：http://dali.jlsjyb.cn/Article/details/gtgqjxvipd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.smart0.xyz/Article/details/gtvpieuqgu.html

[T43] Perl：字符串插值
来源：http://dali.yj20258888.top/Article/details/gtohlvtitl.html

"值: $a"
来源：http://dali.gogol.net.cn/Article/details/gtjmjxqfqz.html

[T44] Perl：条件
来源：http://dali.quarkkingdee.top/Article/details/gtdbxrlkzv.html

if ($a > 0) { print "正"; }
来源：http://dali.tianlin.xyz/Article/details/gthrikewns.html

[T45] Perl：数组遍历
来源：http://dali.haohaochexian.top/Article/details/gtcxychcrt.html

for my $x (@arr) { print $x; }
来源：http://dali.yonumen.top/Article/details/gtvquifpoh.html

[T46] Perl：哈希操作
来源：http://dali.sysykeji.top/Article/details/gtfkfpxwaj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.daria6918.cn/Article/details/gtmivmolss.html

[T47] Perl：正则捕获
来源：http://dali.yuxming.cn/Article/details/gtewewspoo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnxiangtu.top/Article/details/gtbidbynqz.html

[T48] Perl：正则替换
来源：http://dali.ybcxt.top/Article/details/gtozkyspor.html

$s =~ s/old/new/g;
来源：http://dali.sweek.top/Article/details/gttuynpmum.html

[T49] Perl：函数
来源：http://dali.guowangkeji.top/Article/details/gtrovbgiam.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtrneihkmb.html

[T50] Perl：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjebbfnw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.dianchejie.cn/Article/details/gtbzbttsgh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.smart0.xyz/Article/details/gtigcmjtpj.html

[T51] Scala：Hello World
来源：http://dali.andypj.xyz/Article/details/gtnulfwmxq.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gtzictllao.html

[T52] Scala：变量
来源：http://dali.ybcxt.top/Article/details/gtqmupabjz.html

val a = 1;  var b = 2
来源：http://dali.haohaochexian.top/Article/details/gtpkckxwye.html

[T53] Scala：字符串插值
来源：http://dali.sweek.top/Article/details/gtrbwgqexs.html

s"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqkjlxpo.html

[T54] Scala：集合映射
来源：http://dali.mhx1999.top/Article/details/gtlcvuxwso.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.svipenyu.cn/Article/details/gtmqrvcnaq.html

[T55] Scala：集合过滤
来源：http://dali.jinqigfzy.top/Article/details/gtcincmurg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.havefunace.top/Article/details/gttojlorhh.html

[T56] Scala：样例类
来源：http://dali.hfpthk.cn/Article/details/gtckxwlptv.html

case class User(name: String, age: Int)
来源：http://dali.andypj.xyz/Article/details/gtkafkbhwi.html

[T57] Scala：模式匹配
来源：http://dali.cucudq.cn/Article/details/gtekbuwsnm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jianghu66.top/Article/details/gtuvzqorwq.html

[T58] Scala：函数定义
来源：http://dali.quarkkingdee.top/Article/details/gtwzplxrfk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenlongwang.top/Article/details/gtckzluzlp.html

[T59] Scala：循环
来源：http://dali.cucudq.cn/Article/details/gtrbkaomtr.html

for (i <- 1 to 10) println(i)
来源：http://dali.yonumen.top/Article/details/gtqpyrzzpn.html

[T60] Scala：折叠
来源：http://dali.ehwqpu.com/Article/details/gtomzeffni.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jiagoushi.top/Article/details/gtxxdrqahm.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtdzeeagim.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gtxswqsmmd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtoksptjzl.html

[U01] Py：创建虚拟环境
来源：http://dali.hysaishi.cn/Article/details/gtyvckbkyr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yongpay.top/Article/details/gtnbpxzfkm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sysykeji.top/Article/details/gtlkockwtz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgfzy.top/Article/details/gtnjxqwqmz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhixingplan.top/Article/details/gtlvsbtycv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yanxiufei.cn/Article/details/gtpuzeeuxp.html

[U04] Py：变量调试打印
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrkknlnw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pycfn.com/Article/details/gtmxfvmskt.html

[U05] Py：列表去重且保序
来源：http://dali.nanxuanxn.top/Article/details/gtmqyupebg.html

list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gttcjnnkly.html

[U06] Py：合并两个字典
来源：http://dali.sxryk.cn/Article/details/gtpvkcfwyv.html

{**a, **b}
来源：http://dali.zhixingplan.top/Article/details/gtvelivknb.html

[U07] Py：反转字典键值
来源：http://dali.yongpay.top/Article/details/gthmwtojwa.html

{v: k for k, v in d.items()}
来源：http://dali.shangyingyoupin.top/Article/details/gtmqnwwmin.html

[U08] Py：展平二维列表
来源：http://dali.iojbl.cn/Article/details/gtifaybayi.html

[y for x in nested for y in x]
来源：http://dali.guannengcc.top/Article/details/gtiactamsi.html

[U09] Py：字典取最大值的键
来源：http://dali.9152youxi.cn/Article/details/gtoxbtppym.html

max(d, key=d.get)
来源：http://dali.cdnleiting.top/Article/details/gtzjelxjcn.html

[U10] Py：按值排序字典
来源：http://dali.dianchejie.cn/Article/details/gthmhlbqlc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gotoacloud.top/Article/details/gtnkhopbwg.html

[U11] Py：生成器表达式
来源：http://dali.nanxinkj.top/Article/details/gtnldorvkw.html

(x * 2 for x in arr)
来源：http://dali.fzhhl.top/Article/details/gtskebymmf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jyoumei.cn/Article/details/gtxqkrixvv.html

Counter(arr).most_common(3)
来源：http://dali.cucudq.cn/Article/details/gtezpardmm.html

[U13] Py：固定长度队列
来源：http://dali.havefunace.top/Article/details/gtovsomffi.html

deque(maxlen=10)
来源：http://dali.pycfn.com/Article/details/gtedznwhid.html

[U14] Py：分组收集到列表
来源：http://dali.dashuyun.cn/Article/details/gtosetpxhq.html

defaultdict(list)
来源：http://dali.nanxuanxn.top/Article/details/gtdsamqfjg.html

[U15] Py：高精度计时
来源：http://dali.hammf.cn/Article/details/gtsgcrkhhv.html

t = time.perf_counter()
来源：http://dali.bjfxy.top/Article/details/gteiaagxou.html

[U16] Py：命令行参数解析
来源：http://dali.jinqigufen.top/Article/details/gtuuizowen.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yj202588.top/Article/details/gtyvffmhls.html

[U17] Py：初始化日志
来源：http://dali.daria6918.cn/Article/details/gtmtypcchm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhengqikj.top/Article/details/gtnqpnrjjw.html

[U18] Py：预编译正则
来源：http://dali.chenzaomai.com/Article/details/gtvevaqkhd.html

pat = re.compile(r"\d+")
来源：http://dali.jinqigfzy.top/Article/details/gtfutljsbg.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gtgfzmexvu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ehwqpu.com/Article/details/gtfadycrpa.html

[U20] Py：缓存函数结果
来源：http://dali.nanxuanxn.top/Article/details/gtwydtorzd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.fzhhl.top/Article/details/gttkrwlyrw.html

[U21] Py：自定义上下文管理器
来源：http://dali.fengsongda.top/Article/details/gtfpwonuow.html

@contextlib.contextmanager
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrdtqucc.html

[U22] Py：矩阵转置
来源：http://dali.ybcxt.top/Article/details/gtmvznaxkf.html

list(zip(*m))
来源：http://dali.svipenyu.cn/Article/details/gtlcjybxoj.html

[U23] Py：分块读取大文件
来源：http://dali.0kj1m.cn/Article/details/gtmivshhld.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.andypj.xyz/Article/details/gtdhiepiny.html

[U24] Py：路径操作
来源：http://dali.nanxuanxn.top/Article/details/gtdaxqlvjd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gtncaxwhpq.html

[U25] Py：CSV 按字典读
来源：http://dali.pycfn.com/Article/details/gteehfuurk.html

csv.DictReader(f)
来源：http://dali.cashguo.top/Article/details/gtrcrvvmje.html

[U26] Py：并发下载
来源：http://dali.yonumen.top/Article/details/gtrpjdnbsz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jyoumei.cn/Article/details/gtvnvbafjt.html

[U27] Py：异步 HTTP
来源：http://dali.svipenyu.cn/Article/details/gtditblauk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hysaishi.cn/Article/details/gtzdkigfna.html

[U28] Py：类型别名
来源：http://dali.gaohongyu789.top/Article/details/gtkayoualz.html

UserId = int
来源：http://dali.gzhubu.top/Article/details/gtucxqpvnu.html

[U29] Py：属性校验
来源：http://dali.aibaodan.cn/Article/details/gtnofsnbqf.html

@property 与 @x.setter 配合
来源：http://dali.jinqigufen.top/Article/details/gtoykbdwqd.html

[U30] Py：数据类
来源：http://dali.zhengqikj.top/Article/details/gtpfrctkgl.html

@dataclass(slots=True)
来源：http://dali.zycfv.cn/Article/details/gttgezoeps.html

[U31] Py：单测
来源：http://dali.sysykeji.top/Article/details/gtppbvhgfv.html

python -m pytest -q
来源：http://dali.birdmap.top/Article/details/gtubzdgxfx.html

[U32] Py：代码格式化
来源：http://dali.zhixingplan.top/Article/details/gttyalyujy.html

ruff format . && ruff check --fix .
来源：http://dali.jinghuilouyu.cn/Article/details/gtasoxfulx.html

[U33] Py：打包发布
来源：http://dali.wangdashe.top/Article/details/gtjtpjhlty.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.snrcjt.cn/Article/details/gtwcbwgsjc.html

[U34] Py：判断编码
来源：http://dali.yangfankeji.com/Article/details/gtdbludqup.html

chardet.detect(raw)
来源：http://dali.yuanzhike.top/Article/details/gtcpyfvajt.html

[U35] Py：发送邮件
来源：http://dali.yj20258.top/Article/details/gtelneiwmd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.svipenyu.cn/Article/details/gtyeiocmge.html

[U36] Py：定时任务
来源：http://dali.cdnleiting.top/Article/details/gtlfwtjgpv.html

schedule.every(10).minutes.do(job)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuiuucbsx.html

[U37] Py：读写 Excel
来源：http://dali.birdmap.top/Article/details/gtriuaandt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.iojbl.cn/Article/details/gtbwnnnecd.html

[U38] Py：获取脚本所在目录
来源：http://dali.hfpthk.cn/Article/details/gtkksigwod.html

Path(__file__).resolve().parent
来源：http://dali.aibaodan.cn/Article/details/gtdhtrbron.html

[U39] Py：判断是否在交互环境
来源：http://dali.ybcxt.top/Article/details/gtgsgqreah.html

sys.stdout.isatty()
来源：http://dali.dianchejie.cn/Article/details/gtqwxatlxz.html

[U40] Py：打印到标准错误
来源：http://dali.ydzc1.top/Article/details/gtfoamxaim.html

print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gtqdsqqofs.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.iojbl.cn/Article/details/gtogkiwlms.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.kuanghao11.cn/Article/details/gtlhudzmtv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.daxiang520.top/Article/details/gtpqetoxvq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.quarkkingdee.top/Article/details/gtcdsgrkxk.html


<!-- 参考信息 -->