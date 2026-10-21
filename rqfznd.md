代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtwrnyrnbp.html

[S21] C：字符类别判断
来源：http://dali.chenjidiqi.icu/Article/details/gtlwcakuam.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yanxiufei.cn/Article/details/gtknjnlbhp.html

[S22] C：字符串转数字
来源：http://dali.hfpthk.cn/Article/details/gtjclwkqzl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.9152youxi.cn/Article/details/gttaqpwohp.html

[S23] C：随机数
来源：http://dali.c1oappe.top/Article/details/gtpkglszuk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gtleskevje.html

[S24] C：获取本地时间
来源：http://dali.yj202588.top/Article/details/gtrfcdsebl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhixingplan.top/Article/details/gtzccdzmkb.html

[S25] C：内存拷贝
来源：http://dali.yj20258888.top/Article/details/gtgmfuplzo.html

memcpy(dst, src, n);
来源：http://dali.fzhhl.top/Article/details/gtahcyuoga.html

[S26] C：内存清零
来源：http://dali.svipenyu.cn/Article/details/gtdowpllxx.html

memset(a, 0, sizeof a);
来源：http://dali.gotoacloud.top/Article/details/gtkiwnqqan.html

[S27] C：定义常量
来源：http://dali.tanke756.top/Article/details/gtyvcdliee.html

const double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtehjujluh.html

[S28] C：静态变量
来源：http://dali.ehwqpu.com/Article/details/gtocgtfsve.html

static int counter = 0;
来源：http://dali.jlsjyb.cn/Article/details/gtoiofvhab.html

[S29] C：变参函数
来源：http://dali.shuidangran.top/Article/details/gtisjgnseo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgfzy.top/Article/details/gtsustavfi.html

[S30] C：头文件保护
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlarrdcnd.html

#ifndef X_H
来源：http://dali.yj202588.top/Article/details/gtpkxvwgbr.html

#define X_H
来源：http://dali.yanxiufei.cn/Article/details/gtljsbzkko.html

#endif
来源：http://dali.jinqigufen.top/Article/details/gtrwpcdyzm.html

[S31] C++：Hello World
来源：http://dali.andypj.xyz/Article/details/gtvocgxino.html

#include <iostream>
来源：http://dali.shzxlz.cn/Article/details/gtgqsqhyjy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigufen.top/Article/details/gtdxbjpbuh.html

[S32] C++：字符串
来源：http://dali.aizwys.cn/Article/details/gtbcgobnjf.html

std::string s = "hi";  s += "!";
来源：http://dali.hammf.cn/Article/details/gtfbmbeenb.html

[S33] C++：vector 增删
来源：http://dali.zhiwuduotai.top/Article/details/gtdatdelsq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.havefunace.top/Article/details/gtppgmvfil.html

[S34] C++：遍历 vector
来源：http://dali.vqdsnc.cn/Article/details/gtqdhvwrkp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yanxiufei.cn/Article/details/gtmpaxhbqa.html

[S35] C++：map
来源：http://dali.gotoacloud.top/Article/details/gtkkkojngq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtevmsgsqm.html

[S36] C++：unordered_map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdrobxde.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtmiopmxwx.html

[S37] C++：set
来源：http://dali.jiagoushi.top/Article/details/gtblvahgrf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tian-w.cn/Article/details/gtvibgxfba.html

[S38] C++：排序
来源：http://dali.shangyingyoupin.top/Article/details/gtchvsgink.html

std::sort(v.begin(), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gtnfdgnhex.html

[S39] C++：自定义比较器排序
来源：http://dali.gaohongyu789.top/Article/details/gtjakwdkbf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gtxkymjhom.html

[S40] C++：查找元素
来源：http://dali.hywenlv.cn/Article/details/gtjqqtcbzj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sysykeji.top/Article/details/gtctzgxntr.html

[S41] C++：类与构造函数
来源：http://dali.xziqi.cn/Article/details/gtvamsszmn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.smart0.xyz/Article/details/gtangrrsmh.html

[S42] C++：继承与虚函数
来源：http://dali.hnxiangtu.top/Article/details/gtlsjambyu.html

class B : public Base { public: void f() override {} };
来源：http://dali.cucudq.cn/Article/details/gtoclxdcqa.html

[S43] C++：智能指针
来源：http://dali.haohaochexian.top/Article/details/gteaevdich.html

auto p = std::make_unique<int>(5);
来源：http://dali.bjfxy.top/Article/details/gtpffevbqd.html

[S44] C++：引用传参
来源：http://dali.mhx1999.top/Article/details/gtfehmapdp.html

void inc(int &x) { ++x; }
来源：http://dali.snrcjt.cn/Article/details/gtpoihleuf.html

[S45] C++：lambda
来源：http://dali.9152youxi.cn/Article/details/gtwupmupsa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yanxiufei.cn/Article/details/gttnwvrndj.html

[S46] C++：函数模板
来源：http://dali.hywenlv.cn/Article/details/gtgwhzndnh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sweek.top/Article/details/gtsanxphbi.html

[S47] C++：结构化绑定遍历
来源：http://dali.fzhhl.top/Article/details/gtztawdxld.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.birdmap.top/Article/details/gtdkuutvey.html

[S48] C++：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtxldiqszx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ybcxt.top/Article/details/gtpthhoihu.html

while (std::getline(in, line)) { }
来源：http://dali.cqqwz.cn/Article/details/gthnrnsocv.html

[S49] C++：写文件
来源：http://dali.nanxinkj.top/Article/details/gteyxszwmf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgfzy.top/Article/details/gtfjpttdpe.html

[S50] C++：格式化数字
来源：http://dali.yueranfly.top/Article/details/gtkvapjdhr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtezkdjhlf.html

[S51] C++：显式类型转换
来源：http://dali.mhx1999.top/Article/details/gtedpvigib.html

static_cast<double>(a) / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnugdyim.html

[S52] C++：const 与 noexcept
来源：http://dali.yj202588.top/Article/details/gtswmollge.html

int size() const noexcept { return n_; }
来源：http://dali.chenlongwang.top/Article/details/gtnimibsjw.html

[S53] C++：移动语义
来源：http://dali.shangyingyoupin.top/Article/details/gtvkldcezj.html

std::vector<int> w = std::move(v);
来源：http://dali.chenlongwang.top/Article/details/gtsvlorixz.html

[S54] C++：异常处理
来源：http://dali.yonumen.top/Article/details/gtkvezcoxi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhongyouzk.top/Article/details/gtdyvdkwql.html

[S55] C++：结构化绑定
来源：http://dali.hnqzz.top/Article/details/gtjmgogspo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.9152youxi.cn/Article/details/gtiqdyhshi.html

[S56] C++：optional
来源：http://dali.c1oappe.top/Article/details/gtaynjdihc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenlongwang.top/Article/details/gtgkwrgeeo.html

[S57] C++：编译期常量
来源：http://dali.jqgfzy.top/Article/details/gtqxwprvip.html

constexpr int N = 10;
来源：http://dali.ivvv.top/Article/details/gtruxnqekf.html

[S58] C++：命名空间
来源：http://dali.dianchejie.cn/Article/details/gtahecylrc.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdoqblkio.html

[S59] C++：静态断言
来源：http://dali.sxryk.cn/Article/details/gtixjdcfzl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.vqdsnc.cn/Article/details/gtylanthey.html

[S60] C++：遍历并删除元素
来源：http://dali.xylfe.cn/Article/details/gtioofvrmh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yvedp.cn/Article/details/gttvkxqlut.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtbqokpbay.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gtqyhwrquq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gthsxmddry.html

[T01] Kotlin：Hello World
来源：http://dali.jianghu66.top/Article/details/gtpzweaaox.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gtotwamotb.html

[T02] Kotlin：变量
来源：http://dali.dashuyun.cn/Article/details/gtnuokneeb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gaohongyu789.top/Article/details/gtuekiciph.html

[T03] Kotlin：字符串模板
来源：http://dali.meibo888.top/Article/details/gtrgitiptg.html

"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gtarwqovvn.html

[T04] Kotlin：空安全
来源：http://dali.nanxuanxn.top/Article/details/gtsntylatk.html

val n: String? = null;  n?.length
来源：http://dali.xziqi.cn/Article/details/gtmcmgvxev.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtoupkdyzh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.pycfn.com/Article/details/gtdpjodioa.html

[T06] Kotlin：集合映射
来源：http://dali.hfpthk.cn/Article/details/gthbnquyex.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nwbrower.top/Article/details/gtoajfkvse.html

[T07] Kotlin：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gtvqqobgfv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.c1oappe.top/Article/details/gtydymurbr.html

[T08] Kotlin：数据类
来源：http://dali.zhoulong.xyz/Article/details/gtadeqbpot.html

data class User(val name: String, val age: Int)
来源：http://dali.smart0.xyz/Article/details/gtcachlmas.html

[T09] Kotlin：扩展函数
来源：http://dali.shuidangran.top/Article/details/gttwxxagbz.html

fun String.exclaim() = this + "!"
来源：http://dali.haohaochexian.top/Article/details/gtkjzgzzzm.html

[T10] Kotlin：默认参数
来源：http://dali.fengsongda.top/Article/details/gtiyvvitqg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shuidangran.top/Article/details/gttohxorks.html

[T11] Kotlin：协程
来源：http://dali.haohaochexian.top/Article/details/gteomatyzj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nanxuanxn.top/Article/details/gtbndcxhro.html

[T12] Kotlin：解构声明
来源：http://dali.vqdsnc.cn/Article/details/gtenmhaokp.html

val (a, b) = Pair(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtufmavkzl.html

[T13] Kotlin：只读 Map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyogqhsre.html

val m = mapOf("a" to 1)
来源：http://dali.daria6918.cn/Article/details/gtkuqxocfl.html

[T14] Kotlin：循环
来源：http://dali.gotoacloud.top/Article/details/gtjpfmtavu.html

for (i in 1..10) println(i)
来源：http://dali.hnqzz.top/Article/details/gthirqdinc.html

[T15] Kotlin：接口
来源：http://dali.xziqi.cn/Article/details/gtzouxweer.html

interface Shape { fun area(): Double }
来源：http://dali.hnqzz.top/Article/details/gtelehlkly.html

[T16] Swift：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtdkjsqcnm.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtefkrtknx.html

[T17] Swift：变量与常量
来源：http://dali.hammf.cn/Article/details/gtdgmvkwub.html

var a = 1;  let b = 2
来源：http://dali.9152youxi.cn/Article/details/gtssdbcpoq.html

[T18] Swift：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtfjmfdjrf.html

"值: \(b)"
来源：http://dali.zhixingplan.top/Article/details/gtoqkxuykm.html

[T19] Swift：可选绑定
来源：http://dali.hongshengwenyu.top/Article/details/gtkljytzoh.html

if let n = opt { print(n) }
来源：http://dali.yangfankeji.com/Article/details/gtebrzecfn.html

[T20] Swift：数组操作
来源：http://dali.yueranfly.top/Article/details/gtvbreepam.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hongshengwenyu.top/Article/details/gtfwpcilts.html

[T21] Swift：遍历
来源：http://dali.yj202588.top/Article/details/gtsmpssvig.html

for x in a { print(x) }
来源：http://dali.snrcjt.cn/Article/details/gtnvxtleqj.html

[T22] Swift：字典
来源：http://dali.jqgufenzy.top/Article/details/gtthnfgoba.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jiagoushi.top/Article/details/gtzfhucixv.html

[T23] Swift：函数
来源：http://dali.sufxvd.cn/Article/details/gthfsuveco.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.haohaochexian.top/Article/details/gtrtfcufse.html

[T24] Swift：闭包
来源：http://dali.xziqi.cn/Article/details/gtiycmgifd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shuidangran.top/Article/details/gtbiqrjyln.html

[T25] Swift：结构体
来源：http://dali.ydzc1.top/Article/details/gthlgzptlx.html

struct P { var x: Int }
来源：http://dali.xziqi.cn/Article/details/gtvigvpjrc.html

[T26] Swift：类与重写
来源：http://dali.chenzaomai.com/Article/details/gtksjfnbcd.html

class A: Base { override func f() {} }
来源：http://dali.hnxiangtu.top/Article/details/gtocqtrzrx.html

[T27] Swift：错误处理
来源：http://dali.mhx1999.top/Article/details/gthkzhjwot.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttztwotre.html

[T28] Swift：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gttzednlsq.html

enum Color { case red, green }
来源：http://dali.pengpengdd.cyou/Article/details/gtsjzgllnf.html

[T29] Swift：guard 提前返回
来源：http://dali.zhengqikj.top/Article/details/gtmhwzfest.html

guard let x = opt else { return }
来源：http://dali.nanxinkj.top/Article/details/gtxdpktwvq.html

[T30] Swift：协议
来源：http://dali.cashguo.top/Article/details/gthjsutvan.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxinkj.top/Article/details/gtmbyblamj.html

[T31] Lua：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtaahotunb.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gtnbptszpg.html

[T32] Lua：局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gtqnawywem.html

local a = 1
来源：http://dali.gotoacloud.top/Article/details/gtohqbooca.html

[T33] Lua：表（数组）
来源：http://dali.cqqwz.cn/Article/details/gtxqvtbaqk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xziqi.cn/Article/details/gtuyhnrzbo.html

[T34] Lua：遍历表
来源：http://dali.svipenyu.cn/Article/details/gtreheyobd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yueranfly.top/Article/details/gttogirmsz.html

[T35] Lua：字典表
来源：http://dali.ivvv.top/Article/details/gtndlkpxnz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj202588.top/Article/details/gtsewrnseo.html

[T36] Lua：函数
来源：http://dali.fzhhl.top/Article/details/gtdouescis.html

function add(a, b) return a + b end
来源：http://dali.sufxvd.cn/Article/details/gtryucqtjc.html

[T37] Lua：字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gtfowgqsdv.html

"a" .. "b"
来源：http://dali.jinqigufen.top/Article/details/gtqbaybqke.html

[T38] Lua：条件
来源：http://dali.aibaodan.cn/Article/details/gtlhgpoyto.html

if x > 0 then print("正") end
来源：http://dali.bjfxy.top/Article/details/gtgzrydyrh.html

[T39] Lua：模式匹配
来源：http://dali.dianchejie.cn/Article/details/gtgyaenzea.html

string.find(s, "%d+")
来源：http://dali.zhiwuduotai.top/Article/details/gttfhdnhlh.html

[T40] Lua：元表
来源：http://dali.meibo888.top/Article/details/gtbwsalgvm.html

setmetatable({}, { __index = base })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlzewiiw.html

[T41] Perl：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtmkhkxdmr.html

print "Hello\n";
来源：http://dali.cqqwz.cn/Article/details/gtajljbgcg.html

[T42] Perl：变量类型
来源：http://dali.yvedp.cn/Article/details/gtiochjbge.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.0kj1m.cn/Article/details/gtxzlhqxzz.html

[T43] Perl：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtprgpqpvp.html

"值: $a"
来源：http://dali.fzhhl.top/Article/details/gtnfmbxjvi.html

[T44] Perl：条件
来源：http://dali.cdnleiting.top/Article/details/gtvowdrcnp.html

if ($a > 0) { print "正"; }
来源：http://dali.sysykeji.top/Article/details/gtjikxbypu.html

[T45] Perl：数组遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmbfwppg.html

for my $x (@arr) { print $x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjamugrln.html

[T46] Perl：哈希操作
来源：http://dali.hammf.cn/Article/details/gtwcltojsj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nwbrower.top/Article/details/gtrfciqqoa.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzhvuqqs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nwbrower.top/Article/details/gtqtwihnee.html

[T48] Perl：正则替换
来源：http://dali.mhx1999.top/Article/details/gtqtsdfmew.html

$s =~ s/old/new/g;
来源：http://dali.smart0.xyz/Article/details/gtbqyotlwh.html

[T49] Perl：函数
来源：http://dali.jqgufenzy.top/Article/details/gtvgzdrcrs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gtylyjqedr.html

[T50] Perl：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtczogjlhc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.wangdashe.top/Article/details/gtedbdjrge.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xinyue.icu/Article/details/gtzfcgyboz.html

[T51] Scala：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtajemlgdo.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gtpteaadag.html

[T52] Scala：变量
来源：http://dali.meibo888.top/Article/details/gtwcyyxjsh.html

val a = 1;  var b = 2
来源：http://dali.xziqi.cn/Article/details/gtqgcnnkbf.html

[T53] Scala：字符串插值
来源：http://dali.yongpay.top/Article/details/gtzsjvbucr.html

s"值: $b"
来源：http://dali.cheryme.top/Article/details/gtzpqanybr.html

[T54] Scala：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtvzziqqtm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.chenlongwang.top/Article/details/gtnuplygab.html

[T55] Scala：集合过滤
来源：http://dali.xuanzx.com/Article/details/gtnkfshjqe.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gotoacloud.top/Article/details/gtaxefdtgf.html

[T56] Scala：样例类
来源：http://dali.hnqzz.top/Article/details/gtejouqorg.html

case class User(name: String, age: Int)
来源：http://dali.guowangkeji.top/Article/details/gtmzffmjbk.html

[T57] Scala：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gtgyowzlwq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yuxming.cn/Article/details/gtfhbfiuly.html

[T58] Scala：函数定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiotksvbu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tianlin.xyz/Article/details/gthwragqyi.html

[T59] Scala：循环
来源：http://dali.xinyue.icu/Article/details/gtmumfffge.html

for (i <- 1 to 10) println(i)
来源：http://dali.bjfxy.top/Article/details/gtbqmqegpn.html

[T60] Scala：折叠
来源：http://dali.zycfv.cn/Article/details/gtfracytrd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuanzhike.top/Article/details/gtmmigryla.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gttzljtwad.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.guowangkeji.top/Article/details/gtxkiludyl.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtfpemexmv.html

[U01] Py：创建虚拟环境
来源：http://dali.c1oappe.top/Article/details/gtafdkzmot.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.daria6918.cn/Article/details/gtxssaltaj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.birdmap.top/Article/details/gtluasmtcb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guannengcc.top/Article/details/gttruhbsfm.html

[U03] Py：加载 .env 配置
来源：http://dali.jiagoushi.top/Article/details/gtkalabszn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuanzx.com/Article/details/gthivizdxr.html

[U04] Py：变量调试打印
来源：http://dali.c1oappe.top/Article/details/gtjukddeoh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.daxiang520.top/Article/details/gtlahwotyg.html

[U05] Py：列表去重且保序
来源：http://dali.sweek.top/Article/details/gtwzczhivj.html

list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gtipgfacjj.html

[U06] Py：合并两个字典
来源：http://dali.tian-w.cn/Article/details/gtasygates.html

{**a, **b}
来源：http://dali.tanke756.top/Article/details/gtoanvbahh.html

[U07] Py：反转字典键值
来源：http://dali.shzxlz.cn/Article/details/gtcxarignx.html

{v: k for k, v in d.items()}
来源：http://dali.daria6918.cn/Article/details/gtbqichczo.html

[U08] Py：展平二维列表
来源：http://dali.quarkkingdee.top/Article/details/gtuspesmri.html

[y for x in nested for y in x]
来源：http://dali.chenlongwang.top/Article/details/gtlewyzupg.html

[U09] Py：字典取最大值的键
来源：http://dali.cashguo.top/Article/details/gtaxjtinqo.html

max(d, key=d.get)
来源：http://dali.andypj.xyz/Article/details/gtpwxqjdod.html

[U10] Py：按值排序字典
来源：http://dali.jinqigfzy.top/Article/details/gtifwepaxj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgfzy.top/Article/details/gtarjhhown.html

[U11] Py：生成器表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbafhpya.html

(x * 2 for x in arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvbobpsz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pycfn.com/Article/details/gtgehtpbmm.html

Counter(arr).most_common(3)
来源：http://dali.hfpthk.cn/Article/details/gtsiyapmxs.html

[U13] Py：固定长度队列
来源：http://dali.nanxuanxn.top/Article/details/gtrrztncot.html

deque(maxlen=10)
来源：http://dali.jinqigufen.top/Article/details/gtehjathkk.html

[U14] Py：分组收集到列表
来源：http://dali.hnxiangtu.top/Article/details/gtcmucodvg.html

defaultdict(list)
来源：http://dali.nwbrower.top/Article/details/gtxrgdgyrq.html

[U15] Py：高精度计时
来源：http://dali.ydzc1.top/Article/details/gtdfmgorvl.html

t = time.perf_counter()
来源：http://dali.0kj1m.cn/Article/details/gtctfutkuk.html

[U16] Py：命令行参数解析
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjyyuquyy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sufxvd.cn/Article/details/gthgcwycfe.html

[U17] Py：初始化日志
来源：http://dali.fzhhl.top/Article/details/gtmeqrrdmz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.havefunace.top/Article/details/gtdektauui.html

[U18] Py：预编译正则
来源：http://dali.jinqigufen.top/Article/details/gtebujnjwv.html

pat = re.compile(r"\d+")
来源：http://dali.jinqigufen.top/Article/details/gtgunfeqrs.html

[U19] Py：正则替换带回调
来源：http://dali.tian-w.cn/Article/details/gtrlehervs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.guowangkeji.top/Article/details/gtacujehsd.html

[U20] Py：缓存函数结果
来源：http://dali.zdqjudy.top/Article/details/gtksfigkzb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxinkj.top/Article/details/gtgbzoztsm.html

[U21] Py：自定义上下文管理器
来源：http://dali.xziqi.cn/Article/details/gtnocwpiie.html

@contextlib.contextmanager
来源：http://dali.shzxlz.cn/Article/details/gthvcyemoa.html

[U22] Py：矩阵转置
来源：http://dali.fengsongda.top/Article/details/gttdauklcd.html

list(zip(*m))
来源：http://dali.hywenlv.cn/Article/details/gttmayxfxf.html

[U23] Py：分块读取大文件
来源：http://dali.tian-w.cn/Article/details/gtlgswznsv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhongyouzk.top/Article/details/gtvzjftwzb.html

[U24] Py：路径操作
来源：http://dali.haohaochexian.top/Article/details/gttpptogcz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gttwfbdtzd.html

[U25] Py：CSV 按字典读
来源：http://dali.fzhhl.top/Article/details/gtmcokmbsd.html

csv.DictReader(f)
来源：http://dali.kuanghao11.cn/Article/details/gtxwmsibii.html

[U26] Py：并发下载
来源：http://dali.jqgufenzy.top/Article/details/gtrdqnxsij.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.dianchejie.cn/Article/details/gtmdhwjijb.html

[U27] Py：异步 HTTP
来源：http://dali.mhx1999.top/Article/details/gtfprjtind.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.birdmap.top/Article/details/gttqfebvej.html

[U28] Py：类型别名
来源：http://dali.snrcjt.cn/Article/details/gtdmujilfm.html

UserId = int
来源：http://dali.nwbrower.top/Article/details/gtxgkxvdoh.html

[U29] Py：属性校验
来源：http://dali.yvedp.cn/Article/details/gtzwdzijpl.html

@property 与 @x.setter 配合
来源：http://dali.yuanzhike.top/Article/details/gtzmkxocqj.html

[U30] Py：数据类
来源：http://dali.chenlongwang.top/Article/details/gtmvbsdmlm.html

@dataclass(slots=True)
来源：http://dali.jyoumei.cn/Article/details/gtvtqgtrhp.html

[U31] Py：单测
来源：http://dali.snrcjt.cn/Article/details/gtyfgfvnki.html

python -m pytest -q
来源：http://dali.aibaodan.cn/Article/details/gtacuhpkri.html

[U32] Py：代码格式化
来源：http://dali.havefunace.top/Article/details/gtjukuzudq.html

ruff format . && ruff check --fix .
来源：http://dali.c1oappe.top/Article/details/gtkrmljlwm.html

[U33] Py：打包发布
来源：http://dali.nanxuanxn.top/Article/details/gthkvywdxi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hammf.cn/Article/details/gtiolptxtv.html

[U34] Py：判断编码
来源：http://dali.sufxvd.cn/Article/details/gtlmjxqdzn.html

chardet.detect(raw)
来源：http://dali.pycfn.com/Article/details/gtyjkopjro.html

[U35] Py：发送邮件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlilozkmm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.aibaodan.cn/Article/details/gttoovgsnu.html

[U36] Py：定时任务
来源：http://dali.ppjwa.cn/Article/details/gtahxmmodv.html

schedule.every(10).minutes.do(job)
来源：http://dali.cheryme.top/Article/details/gtfritttuy.html

[U37] Py：读写 Excel
来源：http://dali.chenzaomai.com/Article/details/gtuwlyjbip.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.0kj1m.cn/Article/details/gtoieidmcy.html

[U38] Py：获取脚本所在目录
来源：http://dali.haohaochexian.top/Article/details/gtnxftvnfj.html

Path(__file__).resolve().parent
来源：http://dali.chenlongwang.top/Article/details/gtnolkxffy.html

[U39] Py：判断是否在交互环境
来源：http://dali.birdmap.top/Article/details/gtpbzupwao.html

sys.stdout.isatty()
来源：http://dali.cashguo.top/Article/details/gtqzzuiqqb.html

[U40] Py：打印到标准错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvcatfke.html

print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gtfcsirfwg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sysykeji.top/Article/details/gteyhljilm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.wangdashe.top/Article/details/gtdtrhcyfd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yj202588.top/Article/details/gtlgeuvrxf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cucudq.cn/Article/details/gtvefronyl.html

[U43] PHP：声明命名空间
来源：http://dali.vqdsnc.cn/Article/details/gtiaxlfbpr.html

namespace App\Http;
来源：http://dali.pengpengdd.cyou/Article/details/gtuoexofaa.html

[U44] PHP：开启严格类型
来源：http://dali.yanxiufei.cn/Article/details/gtvdxltuiw.html

declare(strict_types=1);
来源：http://dali.hammf.cn/Article/details/gtphkvssfj.html


<!-- 参考信息 -->