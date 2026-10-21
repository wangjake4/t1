代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gtgdwtfctg.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtveowevlk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258.top/Article/details/gticdwcbzf.html

[S22] C：字符串转数字
来源：http://dali.yonumen.top/Article/details/gtaxsujkty.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.316326.xyz/Article/details/gtqwcnqnaa.html

[S23] C：随机数
来源：http://dali.haohaochexian.top/Article/details/gtcasxuodt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.vqdsnc.cn/Article/details/gtzmnxdmqv.html

[S24] C：获取本地时间
来源：http://dali.gaohongyu789.top/Article/details/gtdiqsimcq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hongshengwenyu.top/Article/details/gtcjodcdek.html

[S25] C：内存拷贝
来源：http://dali.0kj1m.cn/Article/details/gtouhzbqst.html

memcpy(dst, src, n);
来源：http://dali.quarkkingdee.top/Article/details/gtywrgfzim.html

[S26] C：内存清零
来源：http://dali.yj202588.top/Article/details/gtwnhnglmz.html

memset(a, 0, sizeof a);
来源：http://dali.hysaishi.cn/Article/details/gtauxpdkyk.html

[S27] C：定义常量
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnumkboz.html

const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtgahpfgvj.html

[S28] C：静态变量
来源：http://dali.shzxlz.cn/Article/details/gtoiparpts.html

static int counter = 0;
来源：http://dali.ybcxt.top/Article/details/gtfwdgkgqh.html

[S29] C：变参函数
来源：http://dali.vqdsnc.cn/Article/details/gtottxbbaw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hfpthk.cn/Article/details/gtnhqdeyxz.html

[S30] C：头文件保护
来源：http://dali.cheryme.top/Article/details/gtzuaewadu.html

#ifndef X_H
来源：http://dali.xuanzx.com/Article/details/gtgpoqmfjc.html

#define X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfaoskmg.html

#endif
来源：http://dali.shanyushiyangtech.top/Article/details/gttlcpvnnp.html

[S31] C++：Hello World
来源：http://dali.yonumen.top/Article/details/gtkjtomdxt.html

#include <iostream>
来源：http://dali.quarkkingdee.top/Article/details/gtoxeugskp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yangfankeji.com/Article/details/gthmpiocxb.html

[S32] C++：字符串
来源：http://dali.snrcjt.cn/Article/details/gtjstykbvn.html

std::string s = "hi";  s += "!";
来源：http://dali.xziqi.cn/Article/details/gtsikriyof.html

[S33] C++：vector 增删
来源：http://dali.chenzaomai.com/Article/details/gtuzrfgaps.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.iojbl.cn/Article/details/gtohxewpqi.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnoboodo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258888.top/Article/details/gtefjqtcmh.html

[S35] C++：map
来源：http://dali.snrcjt.cn/Article/details/gtdzglwqog.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtqkjkvleb.html

[S36] C++：unordered_map
来源：http://dali.daria6918.cn/Article/details/gthupgehol.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtdvkqcteh.html

[S37] C++：set
来源：http://dali.yonumen.top/Article/details/gterzusbaa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.meibo888.top/Article/details/gttqgcmbcw.html

[S38] C++：排序
来源：http://dali.nanxinkj.top/Article/details/gtsowwsski.html

std::sort(v.begin(), v.end());
来源：http://dali.aizwys.cn/Article/details/gtrfjuyudt.html

[S39] C++：自定义比较器排序
来源：http://dali.ybcxt.top/Article/details/gtqnqgmqnn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gotoacloud.top/Article/details/gtzrbyctws.html

[S40] C++：查找元素
来源：http://dali.andypj.xyz/Article/details/gtrjmtrslf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cucudq.cn/Article/details/gtnhesmelv.html

[S41] C++：类与构造函数
来源：http://dali.c1oappe.top/Article/details/gtzogtfvib.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dianchejie.cn/Article/details/gteotnvhvy.html

[S42] C++：继承与虚函数
来源：http://dali.yuanzhike.top/Article/details/gtpbrqlpar.html

class B : public Base { public: void f() override {} };
来源：http://dali.snrcjt.cn/Article/details/gtlbfozbnm.html

[S43] C++：智能指针
来源：http://dali.zdqjudy.top/Article/details/gtbaszctuj.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj202588.top/Article/details/gtngbgocxj.html

[S44] C++：引用传参
来源：http://dali.chenlongwang.top/Article/details/gtulkdkshn.html

void inc(int &x) { ++x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbksenaoe.html

[S45] C++：lambda
来源：http://dali.birdmap.top/Article/details/gtmvluofye.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xinyue.icu/Article/details/gticxeswwa.html

[S46] C++：函数模板
来源：http://dali.wangdashe.top/Article/details/gthdhxisqz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jiagoushi.top/Article/details/gtibiqiwtg.html

[S47] C++：结构化绑定遍历
来源：http://dali.guowangkeji.top/Article/details/gtbxvvqkop.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgufenzy.top/Article/details/gtikrrjicz.html

[S48] C++：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtcgrofygt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigufen.top/Article/details/gtizwitvrq.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258.top/Article/details/gtvnufquqe.html

[S49] C++：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gtvbxfqmul.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangshuangyany.cn/Article/details/gtiatyrcrn.html

[S50] C++：格式化数字
来源：http://dali.jyoumei.cn/Article/details/gtbzqmzvtt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzptwylw.html

[S51] C++：显式类型转换
来源：http://dali.tianlin.xyz/Article/details/gtprkhicwo.html

static_cast<double>(a) / b
来源：http://dali.wangshuangyany.cn/Article/details/gtbfxyzdxs.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnxazmga.html

int size() const noexcept { return n_; }
来源：http://dali.chenzaomai.com/Article/details/gtsabxykfb.html

[S53] C++：移动语义
来源：http://dali.jiagoushi.top/Article/details/gtwkndewqw.html

std::vector<int> w = std::move(v);
来源：http://dali.hammf.cn/Article/details/gtxhctkixl.html

[S54] C++：异常处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsbxiuvg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhongyouzk.top/Article/details/gtiapcofwb.html

[S55] C++：结构化绑定
来源：http://dali.fzhhl.top/Article/details/gtvegiidrk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jiagoushi.top/Article/details/gtmtbmkqft.html

[S56] C++：optional
来源：http://dali.jqgufenzy.top/Article/details/gtahvovtdz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tanke756.top/Article/details/gtbhpuoehi.html

[S57] C++：编译期常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmnbcoxbm.html

constexpr int N = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtgruculyf.html

[S58] C++：命名空间
来源：http://dali.hnxiangtu.top/Article/details/gttrspxpkq.html

namespace ns { int f() { return 1; } }
来源：http://dali.yangfankeji.com/Article/details/gtlsvaycvv.html

[S59] C++：静态断言
来源：http://dali.cheryme.top/Article/details/gtqffyjvlg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pengpengdd.cyou/Article/details/gthkywwjxm.html

[S60] C++：遍历并删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gtwxbepqco.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtyrrkvdkp.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtshwvjats.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gtddhurdwn.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlysoqfrq.html

[T01] Kotlin：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtmqdoxyxi.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gtxbohfqcu.html

[T02] Kotlin：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyqsewdf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aizwys.cn/Article/details/gtgvfhrhal.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gtkqsljixa.html

"值: $b"
来源：http://dali.yj202588.top/Article/details/gtgqskzktm.html

[T04] Kotlin：空安全
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywrntopt.html

val n: String? = null;  n?.length
来源：http://dali.yueranfly.top/Article/details/gtsnggefzm.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigfzy.top/Article/details/gtuyyuywtw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shangyingyoupin.top/Article/details/gtcooxeqma.html

[T06] Kotlin：集合映射
来源：http://dali.nwbrower.top/Article/details/gticznpykq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gotoacloud.top/Article/details/gtubwtvasz.html

[T07] Kotlin：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gtmxthizyu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tian-w.cn/Article/details/gtrvqutnux.html

[T08] Kotlin：数据类
来源：http://dali.yonumen.top/Article/details/gtwmszqvvd.html

data class User(val name: String, val age: Int)
来源：http://dali.quarkkingdee.top/Article/details/gtfcjkmmos.html

[T09] Kotlin：扩展函数
来源：http://dali.aibaodan.cn/Article/details/gtiotwxank.html

fun String.exclaim() = this + "!"
来源：http://dali.aibaodan.cn/Article/details/gtuvqrunqb.html

[T10] Kotlin：默认参数
来源：http://dali.daxiang520.top/Article/details/gtaglrpkxv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhongyouzk.top/Article/details/gtkrlfyewh.html

[T11] Kotlin：协程
来源：http://dali.gotoacloud.top/Article/details/gttendhhhj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258888.top/Article/details/gtkoorpzqt.html

[T12] Kotlin：解构声明
来源：http://dali.nwbrower.top/Article/details/gtjlfltaot.html

val (a, b) = Pair(1, 2)
来源：http://dali.guannengcc.top/Article/details/gthirkjhvv.html

[T13] Kotlin：只读 Map
来源：http://dali.kuanghao11.cn/Article/details/gtweohqpfa.html

val m = mapOf("a" to 1)
来源：http://dali.0kj1m.cn/Article/details/gtnsbswblj.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqcdgyacb.html

for (i in 1..10) println(i)
来源：http://dali.daria6918.cn/Article/details/gtdvnghdsz.html

[T15] Kotlin：接口
来源：http://dali.nwbrower.top/Article/details/gtkgszopdy.html

interface Shape { fun area(): Double }
来源：http://dali.sysykeji.top/Article/details/gtxuurxngw.html

[T16] Swift：Hello World
来源：http://dali.cucudq.cn/Article/details/gtxmfmhokd.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtcsbusxsk.html

[T17] Swift：变量与常量
来源：http://dali.nwbrower.top/Article/details/gtrrshjxay.html

var a = 1;  let b = 2
来源：http://dali.yuanzhike.top/Article/details/gtmqoqthur.html

[T18] Swift：字符串插值
来源：http://dali.hammf.cn/Article/details/gthxzkhpas.html

"值: \(b)"
来源：http://dali.gogol.net.cn/Article/details/gtqfzpevwo.html

[T19] Swift：可选绑定
来源：http://dali.ehwqpu.com/Article/details/gtfgrgcsvo.html

if let n = opt { print(n) }
来源：http://dali.xuanzx.com/Article/details/gtofpanviv.html

[T20] Swift：数组操作
来源：http://dali.316326.xyz/Article/details/gtjagrhwzr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aibaodan.cn/Article/details/gttuagdlyk.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlkowajp.html

for x in a { print(x) }
来源：http://dali.aibaodan.cn/Article/details/gtrlselzxv.html

[T22] Swift：字典
来源：http://dali.andypj.xyz/Article/details/gtmikcwfaf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnxiangtu.top/Article/details/gtfcwjzaza.html

[T23] Swift：函数
来源：http://dali.yanxiufei.cn/Article/details/gtsvccspxe.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.birdmap.top/Article/details/gtiipjccdh.html

[T24] Swift：闭包
来源：http://dali.snrcjt.cn/Article/details/gtetkvfjvk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cheryme.top/Article/details/gtnwzyszkp.html

[T25] Swift：结构体
来源：http://dali.yj20258888.top/Article/details/gtbvlutgqv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gtltdvkbiy.html

[T26] Swift：类与重写
来源：http://dali.shzxlz.cn/Article/details/gtkfzblbyz.html

class A: Base { override func f() {} }
来源：http://dali.xuetiantiany.cn/Article/details/gtllykfazx.html

[T27] Swift：错误处理
来源：http://dali.xylfe.cn/Article/details/gtygjfddia.html

do { try f() } catch { print(error) }
来源：http://dali.wangshuangyany.cn/Article/details/gtfnyxdgoj.html

[T28] Swift：枚举
来源：http://dali.yonumen.top/Article/details/gtspvootvi.html

enum Color { case red, green }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaowcfhed.html

[T29] Swift：guard 提前返回
来源：http://dali.yj20258888.top/Article/details/gtxjytpfkj.html

guard let x = opt else { return }
来源：http://dali.zycfv.cn/Article/details/gtsqofteyz.html

[T30] Swift：协议
来源：http://dali.vqdsnc.cn/Article/details/gtwpklgsor.html

protocol Shape { func area() -> Double }
来源：http://dali.hammf.cn/Article/details/gtailvmvxx.html

[T31] Lua：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtsauguzju.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gtegbldidm.html

[T32] Lua：局部变量
来源：http://dali.cqqwz.cn/Article/details/gthcqcflin.html

local a = 1
来源：http://dali.daria6918.cn/Article/details/gtsyhfeljl.html

[T33] Lua：表（数组）
来源：http://dali.cucudq.cn/Article/details/gthcelidnf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zdqjudy.top/Article/details/gtrbuxdien.html

[T34] Lua：遍历表
来源：http://dali.cqqwz.cn/Article/details/gtqriyqjaz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cucudq.cn/Article/details/gtktycgulv.html

[T35] Lua：字典表
来源：http://dali.meibo888.top/Article/details/gtrwdgrsms.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jyoumei.cn/Article/details/gtksjsdkga.html

[T36] Lua：函数
来源：http://dali.smart0.xyz/Article/details/gtxepcoknb.html

function add(a, b) return a + b end
来源：http://dali.jqgufenzy.top/Article/details/gtqjuufelu.html

[T37] Lua：字符串拼接
来源：http://dali.xylfe.cn/Article/details/gtctxihmvi.html

"a" .. "b"
来源：http://dali.sweek.top/Article/details/gtleoyuoxf.html

[T38] Lua：条件
来源：http://dali.c1oappe.top/Article/details/gtedidayjr.html

if x > 0 then print("正") end
来源：http://dali.yvedp.cn/Article/details/gtrvudlkdv.html

[T39] Lua：模式匹配
来源：http://dali.mhx1999.top/Article/details/gtbobetmpx.html

string.find(s, "%d+")
来源：http://dali.nanxuanxn.top/Article/details/gtxhroypoi.html

[T40] Lua：元表
来源：http://dali.9152youxi.cn/Article/details/gttcydftgn.html

setmetatable({}, { __index = base })
来源：http://dali.jiagoushi.top/Article/details/gtpxbnonrh.html

[T41] Perl：Hello World
来源：http://dali.meibo888.top/Article/details/gtwriyulsf.html

print "Hello\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqsqymln.html

[T42] Perl：变量类型
来源：http://dali.sysykeji.top/Article/details/gtuwusgrhb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj20258888.top/Article/details/gtpxfyjbzo.html

[T43] Perl：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtrbtbtdck.html

"值: $a"
来源：http://dali.shzxlz.cn/Article/details/gtshvvcrcf.html

[T44] Perl：条件
来源：http://dali.vqdsnc.cn/Article/details/gtxrfdmuia.html

if ($a > 0) { print "正"; }
来源：http://dali.yvedp.cn/Article/details/gtrhypkbnu.html

[T45] Perl：数组遍历
来源：http://dali.sufxvd.cn/Article/details/gtbhubycbr.html

for my $x (@arr) { print $x; }
来源：http://dali.yuxming.cn/Article/details/gtoyevdnpb.html

[T46] Perl：哈希操作
来源：http://dali.xziqi.cn/Article/details/gturedmssu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tianlin.xyz/Article/details/gtroruovjb.html

[T47] Perl：正则捕获
来源：http://dali.jlsjyb.cn/Article/details/gtyghiiqsr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtlfmunqie.html

[T48] Perl：正则替换
来源：http://dali.jyoumei.cn/Article/details/gtddynfwzi.html

$s =~ s/old/new/g;
来源：http://dali.vqdsnc.cn/Article/details/gtvwocsezo.html

[T49] Perl：函数
来源：http://dali.svipenyu.cn/Article/details/gtvipghcce.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtgxlbqtrs.html

[T50] Perl：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtgxdzxnjw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgufenzy.top/Article/details/gtysdabxtj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfubzyann.html

[T51] Scala：Hello World
来源：http://dali.mhx1999.top/Article/details/gtmizflghw.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gtxbfcfxar.html

[T52] Scala：变量
来源：http://dali.shangyingyoupin.top/Article/details/gtcgihkztj.html

val a = 1;  var b = 2
来源：http://dali.sufxvd.cn/Article/details/gtxkvmrlav.html

[T53] Scala：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtktvehswg.html

s"值: $b"
来源：http://dali.sxryk.cn/Article/details/gtnrfmpzyz.html

[T54] Scala：集合映射
来源：http://dali.yj20258.top/Article/details/gtpgmfehqm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtdwqhcjab.html

[T55] Scala：集合过滤
来源：http://dali.0kj1m.cn/Article/details/gtantsqnpk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zycfv.cn/Article/details/gtdoqxzfjk.html

[T56] Scala：样例类
来源：http://dali.cucudq.cn/Article/details/gtwxylucrh.html

case class User(name: String, age: Int)
来源：http://dali.tian-w.cn/Article/details/gtojmlitwy.html

[T57] Scala：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gtbphmewqo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pengpengdd.cyou/Article/details/gtdkjuuoza.html

[T58] Scala：函数定义
来源：http://dali.meibo888.top/Article/details/gtsgmuhhab.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cucudq.cn/Article/details/gtcgmnykco.html

[T59] Scala：循环
来源：http://dali.feifeiyinyue.top/Article/details/gtpwmifyja.html

for (i <- 1 to 10) println(i)
来源：http://dali.xinyue.icu/Article/details/gtbrmnpxpg.html

[T60] Scala：折叠
来源：http://dali.ppjwa.cn/Article/details/gtkfolijlx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gogol.net.cn/Article/details/gtoykxpjej.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtdcijsawq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gtlubfvlyt.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtfwmxqtbr.html

[U01] Py：创建虚拟环境
来源：http://dali.hysaishi.cn/Article/details/gtqzsrcjio.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yvedp.cn/Article/details/gtptidlwlh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gtbkwgtvin.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jyoumei.cn/Article/details/gtrisjjwuy.html

[U03] Py：加载 .env 配置
来源：http://dali.xylfe.cn/Article/details/gtpejjaran.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxinkj.top/Article/details/gtdgvndpts.html

[U04] Py：变量调试打印
来源：http://dali.jinqigufen.top/Article/details/gtzaammaaa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.guannengcc.top/Article/details/gtyoueugka.html

[U05] Py：列表去重且保序
来源：http://dali.xuanzx.com/Article/details/gtafqtkkny.html

list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gtztujdqhl.html

[U06] Py：合并两个字典
来源：http://dali.cashguo.top/Article/details/gtqovqaxwd.html

{**a, **b}
来源：http://dali.daria6918.cn/Article/details/gtsjfggsui.html

[U07] Py：反转字典键值
来源：http://dali.xuanzx.com/Article/details/gtiylqjkqg.html

{v: k for k, v in d.items()}
来源：http://dali.nanxuanxn.top/Article/details/gtmlklpbuy.html

[U08] Py：展平二维列表
来源：http://dali.nwbrower.top/Article/details/gtqrpchrxa.html

[y for x in nested for y in x]
来源：http://dali.9152youxi.cn/Article/details/gtqbevcprj.html

[U09] Py：字典取最大值的键
来源：http://dali.yuanzhike.top/Article/details/gticqncsiv.html

max(d, key=d.get)
来源：http://dali.hysaishi.cn/Article/details/gtqloknicn.html

[U10] Py：按值排序字典
来源：http://dali.xuanzx.com/Article/details/gtyarcjhnh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yonumen.top/Article/details/gtfkairdsp.html

[U11] Py：生成器表达式
来源：http://dali.cdnleiting.top/Article/details/gtxuehkbuv.html

(x * 2 for x in arr)
来源：http://dali.cashguo.top/Article/details/gtstyxjhbz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yonumen.top/Article/details/gtelxxyxux.html

Counter(arr).most_common(3)
来源：http://dali.daria6918.cn/Article/details/gtehkbxhll.html

[U13] Py：固定长度队列
来源：http://dali.yj20258.top/Article/details/gtmhlegeqx.html

deque(maxlen=10)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmwyapni.html

[U14] Py：分组收集到列表
来源：http://dali.ybcxt.top/Article/details/gtfuubinjy.html

defaultdict(list)
来源：http://dali.chenlongwang.top/Article/details/gtdauolslr.html

[U15] Py：高精度计时
来源：http://dali.chenlongwang.top/Article/details/gtrmjbottu.html

t = time.perf_counter()
来源：http://dali.ydzc1.top/Article/details/gtsduftmgd.html

[U16] Py：命令行参数解析
来源：http://dali.pycfn.com/Article/details/gtjcssyxwg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkldzdrp.html

[U17] Py：初始化日志
来源：http://dali.bjfxy.top/Article/details/gttpwglzwq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.quarkkingdee.top/Article/details/gtrezakzzy.html

[U18] Py：预编译正则
来源：http://dali.gzhubu.top/Article/details/gtthzuylmu.html

pat = re.compile(r"\d+")
来源：http://dali.sweek.top/Article/details/gtyzaxayha.html

[U19] Py：正则替换带回调
来源：http://dali.yuxming.cn/Article/details/gtydtkusdn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.dashuyun.cn/Article/details/gtliecwjmh.html

[U20] Py：缓存函数结果
来源：http://dali.jinqigufen.top/Article/details/gtppfzysnq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hfpthk.cn/Article/details/gtwnoeezhk.html

[U21] Py：自定义上下文管理器
来源：http://dali.gzhubu.top/Article/details/gtnmkcgihs.html

@contextlib.contextmanager
来源：http://dali.tianlin.xyz/Article/details/gtppnlowhx.html

[U22] Py：矩阵转置
来源：http://dali.xuanzx.com/Article/details/gtkrtraoha.html

list(zip(*m))
来源：http://dali.ehwqpu.com/Article/details/gtiuhgtbbj.html

[U23] Py：分块读取大文件
来源：http://dali.chenzaomai.com/Article/details/gtoqxlkpio.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.havefunace.top/Article/details/gtikubzgwk.html

[U24] Py：路径操作
来源：http://dali.nwbrower.top/Article/details/gttkuvofui.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gtpsokkoaq.html

[U25] Py：CSV 按字典读
来源：http://dali.aibaodan.cn/Article/details/gtutcyplvd.html

csv.DictReader(f)
来源：http://dali.aizwys.cn/Article/details/gtrajsnqpp.html

[U26] Py：并发下载
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdvsbjdn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cqqwz.cn/Article/details/gtaikjlqtr.html

[U27] Py：异步 HTTP
来源：http://dali.guannengcc.top/Article/details/gtfmxfpxyb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.nwbrower.top/Article/details/gtqvrszdov.html

[U28] Py：类型别名
来源：http://dali.sxryk.cn/Article/details/gtwarzktkq.html

UserId = int
来源：http://dali.bjfxy.top/Article/details/gtkrcypeli.html

[U29] Py：属性校验
来源：http://dali.nwbrower.top/Article/details/gtgkwzykvy.html

@property 与 @x.setter 配合
来源：http://dali.jinghuilouyu.cn/Article/details/gtsyftmjfd.html

[U30] Py：数据类
来源：http://dali.daxiang520.top/Article/details/gtajjsazlh.html

@dataclass(slots=True)
来源：http://dali.hnxiangtu.top/Article/details/gtakfhyfyd.html

[U31] Py：单测
来源：http://dali.hnxiangtu.top/Article/details/gteishukbv.html

python -m pytest -q
来源：http://dali.fengsongda.top/Article/details/gteznpxdkl.html

[U32] Py：代码格式化
来源：http://dali.gzhubu.top/Article/details/gtotweulnz.html

ruff format . && ruff check --fix .
来源：http://dali.gaohongyu789.top/Article/details/gtgoqjhzgf.html

[U33] Py：打包发布
来源：http://dali.yueranfly.top/Article/details/gthdaethof.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwexucvld.html

[U34] Py：判断编码
来源：http://dali.sysykeji.top/Article/details/gtrtrrbvjl.html

chardet.detect(raw)
来源：http://dali.ppjwa.cn/Article/details/gtntdnjtki.html

[U35] Py：发送邮件
来源：http://dali.haohaochexian.top/Article/details/gtyamaebwd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jqgfzy.top/Article/details/gtiwknlnbh.html

[U36] Py：定时任务
来源：http://dali.snrcjt.cn/Article/details/gtsqguvabl.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjdoczrl.html

[U37] Py：读写 Excel
来源：http://dali.dashuyun.cn/Article/details/gtnrobtvdx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jiagoushi.top/Article/details/gtiffyfitc.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhoulong.xyz/Article/details/gtxvyiojrb.html

Path(__file__).resolve().parent
来源：http://dali.iojbl.cn/Article/details/gtaxaxuoxb.html

[U39] Py：判断是否在交互环境
来源：http://dali.daxiang520.top/Article/details/gtjrjqxgxi.html

sys.stdout.isatty()
来源：http://dali.wangdashe.top/Article/details/gtbrolicqd.html

[U40] Py：打印到标准错误
来源：http://dali.zhongyouzk.top/Article/details/gtlcgqwefe.html

print("err", file=sys.stderr)
来源：http://dali.gogol.net.cn/Article/details/gtetfcwabt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.c1oappe.top/Article/details/gtvssmjotr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinqigufen.top/Article/details/gtyehththe.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cheryme.top/Article/details/gtfisrerkj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jqgufenzy.top/Article/details/gtybcchkgr.html

[U43] PHP：声明命名空间
来源：http://dali.zhongyouzk.top/Article/details/gtqonhelnm.html

namespace App\Http;
来源：http://dali.jqgufenzy.top/Article/details/gtxxscvapw.html

[U44] PHP：开启严格类型
来源：http://dali.jinqigfzy.top/Article/details/gtoqkqhvso.html

declare(strict_types=1);
来源：http://dali.zycfv.cn/Article/details/gttwuyjisy.html


<!-- 参考信息 -->