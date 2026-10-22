代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gtknkrqjiz.html

[S21] C：字符类别判断
来源：http://dali.cdnleiting.top/Article/details/gtyknzqjsu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jlsjyb.cn/Article/details/gtqgibssjw.html

[S22] C：字符串转数字
来源：http://dali.mhx1999.top/Article/details/gtfekjmozm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yanxiufei.cn/Article/details/gtbljwlxyw.html

[S23] C：随机数
来源：http://dali.jqgfzy.top/Article/details/gtcolvaosr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daxiang520.top/Article/details/gtpsxvvves.html

[S24] C：获取本地时间
来源：http://dali.daxiang520.top/Article/details/gtbawgwfvp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hysaishi.cn/Article/details/gtkzxumqln.html

[S25] C：内存拷贝
来源：http://dali.daxiang520.top/Article/details/gtkonbmjxe.html

memcpy(dst, src, n);
来源：http://dali.hnxiangtu.top/Article/details/gtthauiaqq.html

[S26] C：内存清零
来源：http://dali.zhiwuduotai.top/Article/details/gttdmgkqzd.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxmppkmx.html

[S27] C：定义常量
来源：http://dali.sweek.top/Article/details/gtrmritzcq.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtyyvomkgq.html

[S28] C：静态变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgruwfyp.html

static int counter = 0;
来源：http://dali.guowangkeji.top/Article/details/gtnzdreukw.html

[S29] C：变参函数
来源：http://dali.mhx1999.top/Article/details/gtruhgvaib.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fzhhl.top/Article/details/gtotndwguh.html

[S30] C：头文件保护
来源：http://dali.snrcjt.cn/Article/details/gtsreaiisk.html

#ifndef X_H
来源：http://dali.tian-w.cn/Article/details/gtnvnrycjz.html

#define X_H
来源：http://dali.guannengcc.top/Article/details/gttlsykovc.html

#endif
来源：http://dali.zycfv.cn/Article/details/gtwyljzhpp.html

[S31] C++：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtsopfivxx.html

#include <iostream>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskjvdket.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcthlpcpz.html

[S32] C++：字符串
来源：http://dali.0kj1m.cn/Article/details/gtzijzqzrx.html

std::string s = "hi";  s += "!";
来源：http://dali.xuetiantiany.cn/Article/details/gttkkixrys.html

[S33] C++：vector 增删
来源：http://dali.gotoacloud.top/Article/details/gtkrgigqqx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hywenlv.cn/Article/details/gthximufiq.html

[S34] C++：遍历 vector
来源：http://dali.zhixingplan.top/Article/details/gtfysdxail.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sweek.top/Article/details/gtjagquzzv.html

[S35] C++：map
来源：http://dali.nanxinkj.top/Article/details/gtzciudgpd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gtiinwmtra.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqwrevqi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtyljprbob.html

[S37] C++：set
来源：http://dali.gzhubu.top/Article/details/gtuifgstug.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtsahwmykx.html

[S38] C++：排序
来源：http://dali.xuetiantiany.cn/Article/details/gteyqwhyel.html

std::sort(v.begin(), v.end());
来源：http://dali.gotoacloud.top/Article/details/gteavmlurf.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gtdpmycacr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cdnleiting.top/Article/details/gtrueepfza.html

[S40] C++：查找元素
来源：http://dali.tianlin.xyz/Article/details/gtfkgfuidh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aizwys.cn/Article/details/gtxjfsrmzv.html

[S41] C++：类与构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiupchelj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.fzhhl.top/Article/details/gtlmquwbtc.html

[S42] C++：继承与虚函数
来源：http://dali.redwolf501.top/Article/details/gtjprmiqow.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigfzy.top/Article/details/gtyaimpjah.html

[S43] C++：智能指针
来源：http://dali.wangshuangyany.cn/Article/details/gtnecjfztq.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuetiantiany.cn/Article/details/gtppzovixr.html

[S44] C++：引用传参
来源：http://dali.hfpthk.cn/Article/details/gtyqfddejz.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gtsfkrrcxi.html

[S45] C++：lambda
来源：http://dali.yonumen.top/Article/details/gtxkldribc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yvedp.cn/Article/details/gtrgjzaxnb.html

[S46] C++：函数模板
来源：http://dali.cheryme.top/Article/details/gtenthfpku.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yvedp.cn/Article/details/gttzoxereb.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gtnvdolrrd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sweek.top/Article/details/gtgviubbaf.html

[S48] C++：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtukrnzbtn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.9152youxi.cn/Article/details/gtktyxuxrl.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258.top/Article/details/gtdshvezwu.html

[S49] C++：写文件
来源：http://dali.havefunace.top/Article/details/gtrglpnjdj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258888.top/Article/details/gtgmxmztqm.html

[S50] C++：格式化数字
来源：http://dali.tianlin.xyz/Article/details/gtjvywmevi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtglxrturc.html

[S51] C++：显式类型转换
来源：http://dali.daxiang520.top/Article/details/gtfazftzok.html

static_cast<double>(a) / b
来源：http://dali.guannengcc.top/Article/details/gtjhjetyat.html

[S52] C++：const 与 noexcept
来源：http://dali.sysykeji.top/Article/details/gtssytossh.html

int size() const noexcept { return n_; }
来源：http://dali.smart0.xyz/Article/details/gtodoclekh.html

[S53] C++：移动语义
来源：http://dali.tanke756.top/Article/details/gtlmdqgfsz.html

std::vector<int> w = std::move(v);
来源：http://dali.tanke756.top/Article/details/gtspbgtvyv.html

[S54] C++：异常处理
来源：http://dali.yj20258888.top/Article/details/gtdcgeslhz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwrwhbjl.html

[S55] C++：结构化绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmgwbdgf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daxiang520.top/Article/details/gtszacxyzu.html

[S56] C++：optional
来源：http://dali.0kj1m.cn/Article/details/gtgprmpthm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yueranfly.top/Article/details/gtlkrlrwsg.html

[S57] C++：编译期常量
来源：http://dali.tanke756.top/Article/details/gtuxrlvmmt.html

constexpr int N = 10;
来源：http://dali.yuxming.cn/Article/details/gtgfhiqnbz.html

[S58] C++：命名空间
来源：http://dali.ivvv.top/Article/details/gtgkinkdgr.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfeykeawk.html

[S59] C++：静态断言
来源：http://dali.yueranfly.top/Article/details/gtsljcshjv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigufen.top/Article/details/gttytphunh.html

[S60] C++：遍历并删除元素
来源：http://dali.xziqi.cn/Article/details/gttfmofxul.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhengqikj.top/Article/details/gtzdsssxfm.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtboiuavwm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shuidangran.top/Article/details/gtchnwlodq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtvcqylkuc.html

[T01] Kotlin：Hello World
来源：http://dali.c1oappe.top/Article/details/gttusuzftc.html

println("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvqgimxq.html

[T02] Kotlin：变量
来源：http://dali.9152youxi.cn/Article/details/gtfumvxlwh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dianchejie.cn/Article/details/gtyeqxhmgh.html

[T03] Kotlin：字符串模板
来源：http://dali.yonumen.top/Article/details/gtuxwmuwzn.html

"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnuyvvyvx.html

[T04] Kotlin：空安全
来源：http://dali.yvedp.cn/Article/details/gtjazokkbm.html

val n: String? = null;  n?.length
来源：http://dali.shangyingyoupin.top/Article/details/gtqqdctyaw.html

[T05] Kotlin：when 表达式
来源：http://dali.daxiang520.top/Article/details/gtivpfauxy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.mhx1999.top/Article/details/gtulqpktpq.html

[T06] Kotlin：集合映射
来源：http://dali.nanxinkj.top/Article/details/gtmvblwqot.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gogol.net.cn/Article/details/gtdwxmrskh.html

[T07] Kotlin：集合过滤
来源：http://dali.yongpay.top/Article/details/gtkvglneww.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gogol.net.cn/Article/details/gtcjyispwv.html

[T08] Kotlin：数据类
来源：http://dali.316326.xyz/Article/details/gtzexvrumm.html

data class User(val name: String, val age: Int)
来源：http://dali.gogol.net.cn/Article/details/gtkvxcvvcl.html

[T09] Kotlin：扩展函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrbfweve.html

fun String.exclaim() = this + "!"
来源：http://dali.hnxiangtu.top/Article/details/gtdiqglhnz.html

[T10] Kotlin：默认参数
来源：http://dali.xuanzx.com/Article/details/gtuinpfznv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhixingplan.top/Article/details/gtukjrsiej.html

[T11] Kotlin：协程
来源：http://dali.smart0.xyz/Article/details/gtipibygvt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yongpay.top/Article/details/gtvornwbwh.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258.top/Article/details/gtjbsrhjrf.html

val (a, b) = Pair(1, 2)
来源：http://dali.cashguo.top/Article/details/gtynmftieo.html

[T13] Kotlin：只读 Map
来源：http://dali.xinyue.icu/Article/details/gtbfbblerx.html

val m = mapOf("a" to 1)
来源：http://dali.zdqjudy.top/Article/details/gtpogljwco.html

[T14] Kotlin：循环
来源：http://dali.jyoumei.cn/Article/details/gtziwftblp.html

for (i in 1..10) println(i)
来源：http://dali.smart0.xyz/Article/details/gtlhecbayv.html

[T15] Kotlin：接口
来源：http://dali.0kj1m.cn/Article/details/gtqjkuarvr.html

interface Shape { fun area(): Double }
来源：http://dali.tian-w.cn/Article/details/gtxvcbwqpd.html

[T16] Swift：Hello World
来源：http://dali.daria6918.cn/Article/details/gtgpwjdude.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gtcpmcvdgg.html

[T17] Swift：变量与常量
来源：http://dali.aibaodan.cn/Article/details/gteoclmpvl.html

var a = 1;  let b = 2
来源：http://dali.yvedp.cn/Article/details/gtmppstcer.html

[T18] Swift：字符串插值
来源：http://dali.meibo888.top/Article/details/gthmgawfxn.html

"值: \(b)"
来源：http://dali.zhixingplan.top/Article/details/gthznwgagh.html

[T19] Swift：可选绑定
来源：http://dali.hnxiangtu.top/Article/details/gtfhjgdmxm.html

if let n = opt { print(n) }
来源：http://dali.daxiang520.top/Article/details/gtgwpqptlh.html

[T20] Swift：数组操作
来源：http://dali.havefunace.top/Article/details/gttmzhghgg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.316326.xyz/Article/details/gtlhavdzpv.html

[T21] Swift：遍历
来源：http://dali.tianlin.xyz/Article/details/gtqdfvfksd.html

for x in a { print(x) }
来源：http://dali.mhx1999.top/Article/details/gtnfeamcnb.html

[T22] Swift：字典
来源：http://dali.zhixingplan.top/Article/details/gtjhkgwgfa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hfpthk.cn/Article/details/gthpcbhhnv.html

[T23] Swift：函数
来源：http://dali.zdqjudy.top/Article/details/gtuxkhvfna.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinqigfzy.top/Article/details/gtcjqwzlgp.html

[T24] Swift：闭包
来源：http://dali.chenlongwang.top/Article/details/gtqdeeddcb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tian-w.cn/Article/details/gtlyqwhuax.html

[T25] Swift：结构体
来源：http://dali.jqgfzy.top/Article/details/gtmoalyzdo.html

struct P { var x: Int }
来源：http://dali.xziqi.cn/Article/details/gtoxophzyy.html

[T26] Swift：类与重写
来源：http://dali.tianlin.xyz/Article/details/gtlelnhrdk.html

class A: Base { override func f() {} }
来源：http://dali.redwolf501.top/Article/details/gtjezwgyyl.html

[T27] Swift：错误处理
来源：http://dali.hnqzz.top/Article/details/gtuqwuxpld.html

do { try f() } catch { print(error) }
来源：http://dali.kuanghao11.cn/Article/details/gthsntvrac.html

[T28] Swift：枚举
来源：http://dali.ivvv.top/Article/details/gtsiavphao.html

enum Color { case red, green }
来源：http://dali.yangfankeji.com/Article/details/gtuxrmqhzy.html

[T29] Swift：guard 提前返回
来源：http://dali.andypj.xyz/Article/details/gtgobyeibb.html

guard let x = opt else { return }
来源：http://dali.ppjwa.cn/Article/details/gtxjcokwrg.html

[T30] Swift：协议
来源：http://dali.yj20258.top/Article/details/gtcteikngo.html

protocol Shape { func area() -> Double }
来源：http://dali.jiagoushi.top/Article/details/gtzcibltmg.html

[T31] Lua：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtpzqpwpzl.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gtxdldfdof.html

[T32] Lua：局部变量
来源：http://dali.cashguo.top/Article/details/gtjwylpkko.html

local a = 1
来源：http://dali.dashuyun.cn/Article/details/gtisbchbbi.html

[T33] Lua：表（数组）
来源：http://dali.smart0.xyz/Article/details/gtbrdzasji.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.birdmap.top/Article/details/gtzzsuyomk.html

[T34] Lua：遍历表
来源：http://dali.cqqwz.cn/Article/details/gtdxadjpbw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hongshengwenyu.top/Article/details/gtubhaahav.html

[T35] Lua：字典表
来源：http://dali.jinqigufen.top/Article/details/gtrfmtwdau.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gttzeqsudm.html

[T36] Lua：函数
来源：http://dali.gotoacloud.top/Article/details/gtnxfxroii.html

function add(a, b) return a + b end
来源：http://dali.guowangkeji.top/Article/details/gtyjugpfad.html

[T37] Lua：字符串拼接
来源：http://dali.316326.xyz/Article/details/gtufpgcemh.html

"a" .. "b"
来源：http://dali.jiagoushi.top/Article/details/gtrxejverp.html

[T38] Lua：条件
来源：http://dali.nanxuanxn.top/Article/details/gtpmtnuzkr.html

if x > 0 then print("正") end
来源：http://dali.chenjidiqi.icu/Article/details/gttldxtwwk.html

[T39] Lua：模式匹配
来源：http://dali.daxiang520.top/Article/details/gtxfijhdxe.html

string.find(s, "%d+")
来源：http://dali.mhx1999.top/Article/details/gtrkchhckh.html

[T40] Lua：元表
来源：http://dali.nwbrower.top/Article/details/gtpynungml.html

setmetatable({}, { __index = base })
来源：http://dali.hammf.cn/Article/details/gtdgvjfhiu.html

[T41] Perl：Hello World
来源：http://dali.hysaishi.cn/Article/details/gteuxcxpnw.html

print "Hello\n";
来源：http://dali.vqdsnc.cn/Article/details/gtcumevvpi.html

[T42] Perl：变量类型
来源：http://dali.gzhubu.top/Article/details/gtmryopurx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.havefunace.top/Article/details/gtjrsprtms.html

[T43] Perl：字符串插值
来源：http://dali.ivvv.top/Article/details/gtcehdijso.html

"值: $a"
来源：http://dali.jianghu66.top/Article/details/gtvnuutmep.html

[T44] Perl：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtuahulvyr.html

if ($a > 0) { print "正"; }
来源：http://dali.jyoumei.cn/Article/details/gtpvpkechy.html

[T45] Perl：数组遍历
来源：http://dali.yueranfly.top/Article/details/gtbuzvanyh.html

for my $x (@arr) { print $x; }
来源：http://dali.yonumen.top/Article/details/gtpjogphaa.html

[T46] Perl：哈希操作
来源：http://dali.zycfv.cn/Article/details/gtrzcaksed.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xylfe.cn/Article/details/gtnflkljla.html

[T47] Perl：正则捕获
来源：http://dali.cashguo.top/Article/details/gtrxfkajfp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jlsjyb.cn/Article/details/gtpygwhpzd.html

[T48] Perl：正则替换
来源：http://dali.nanxinkj.top/Article/details/gttifxgkkg.html

$s =~ s/old/new/g;
来源：http://dali.aizwys.cn/Article/details/gthzehzwyt.html

[T49] Perl：函数
来源：http://dali.cdnleiting.top/Article/details/gtrfrxeziz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtnuiugsiq.html

[T50] Perl：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtcwjcpwfx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yvedp.cn/Article/details/gtzbfnkkqw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jqgufenzy.top/Article/details/gtuhkbsrdh.html

[T51] Scala：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtbsjmathw.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gtfpdcbfhq.html

[T52] Scala：变量
来源：http://dali.316326.xyz/Article/details/gtntelscyp.html

val a = 1;  var b = 2
来源：http://dali.aibaodan.cn/Article/details/gtlxqfagad.html

[T53] Scala：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtsdsfjlxv.html

s"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtgekepftx.html

[T54] Scala：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gtkelpsyxg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cashguo.top/Article/details/gtxtpqrrld.html

[T55] Scala：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gtkqldfiyo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.dashuyun.cn/Article/details/gtklerekpb.html

[T56] Scala：样例类
来源：http://dali.zhengqikj.top/Article/details/gtgahduskc.html

case class User(name: String, age: Int)
来源：http://dali.cqqwz.cn/Article/details/gtvrfrjdir.html

[T57] Scala：模式匹配
来源：http://dali.havefunace.top/Article/details/gthazbrtyv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cheryme.top/Article/details/gtwbijbwkr.html

[T58] Scala：函数定义
来源：http://dali.ydzc1.top/Article/details/gtgovjrcoh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhengqikj.top/Article/details/gtgiwkxsuu.html

[T59] Scala：循环
来源：http://dali.kuanghao11.cn/Article/details/gttskvkylb.html

for (i <- 1 to 10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtlynzurze.html

[T60] Scala：折叠
来源：http://dali.fzhhl.top/Article/details/gtfsdqoxrj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sysykeji.top/Article/details/gtdlpkjcym.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtomlrbsqf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cheryme.top/Article/details/gthdqlumgk.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gthukjpfse.html

[U01] Py：创建虚拟环境
来源：http://dali.zycfv.cn/Article/details/gthddmurbm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jianghu66.top/Article/details/gtcfvxyxlw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dashuyun.cn/Article/details/gtihldojtl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.bjfxy.top/Article/details/gtfilwwfbp.html

[U03] Py：加载 .env 配置
来源：http://dali.hnxiangtu.top/Article/details/gtlhbzncsm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.haohaochexian.top/Article/details/gtecqywbjp.html

[U04] Py：变量调试打印
来源：http://dali.shuidangran.top/Article/details/gtfxzuowoc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.vqdsnc.cn/Article/details/gtwoadpxjf.html

[U05] Py：列表去重且保序
来源：http://dali.fzhhl.top/Article/details/gtclplufax.html

list(dict.fromkeys(arr))
来源：http://dali.havefunace.top/Article/details/gtiopfbfgd.html

[U06] Py：合并两个字典
来源：http://dali.jinqigfzy.top/Article/details/gttnciremr.html

{**a, **b}
来源：http://dali.wangdashe.top/Article/details/gtvlenkzzq.html

[U07] Py：反转字典键值
来源：http://dali.yvedp.cn/Article/details/gtbvobzcgs.html

{v: k for k, v in d.items()}
来源：http://dali.zhixingplan.top/Article/details/gtqgternch.html

[U08] Py：展平二维列表
来源：http://dali.cashguo.top/Article/details/gtjkbxsavw.html

[y for x in nested for y in x]
来源：http://dali.ppjwa.cn/Article/details/gtkdddbjms.html

[U09] Py：字典取最大值的键
来源：http://dali.xylfe.cn/Article/details/gtomhptpcv.html

max(d, key=d.get)
来源：http://dali.jqgfzy.top/Article/details/gtnplaguwk.html

[U10] Py：按值排序字典
来源：http://dali.tanke756.top/Article/details/gtaxgacnfo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gaohongyu789.top/Article/details/gtlfqikuae.html

[U11] Py：生成器表达式
来源：http://dali.xziqi.cn/Article/details/gtzmfgfoaf.html

(x * 2 for x in arr)
来源：http://dali.hysaishi.cn/Article/details/gttiixryhh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhoulong.xyz/Article/details/gtguklghhs.html

Counter(arr).most_common(3)
来源：http://dali.tian-w.cn/Article/details/gtgsfnkvdl.html

[U13] Py：固定长度队列
来源：http://dali.316326.xyz/Article/details/gtvmwrozdz.html

deque(maxlen=10)
来源：http://dali.jiagoushi.top/Article/details/gtqlzhrvaz.html

[U14] Py：分组收集到列表
来源：http://dali.chenjidiqi.icu/Article/details/gtdnxnxyqs.html

defaultdict(list)
来源：http://dali.jlsjyb.cn/Article/details/gtkueddmac.html

[U15] Py：高精度计时
来源：http://dali.zhixingplan.top/Article/details/gtudlmgbqu.html

t = time.perf_counter()
来源：http://dali.kuanghao11.cn/Article/details/gtvrnqandp.html

[U16] Py：命令行参数解析
来源：http://dali.hfpthk.cn/Article/details/gtvgwvpuwg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.redwolf501.top/Article/details/gtumlmbxej.html

[U17] Py：初始化日志
来源：http://dali.dianchejie.cn/Article/details/gtemwtxetp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.redwolf501.top/Article/details/gtewkfkpvr.html

[U18] Py：预编译正则
来源：http://dali.mhx1999.top/Article/details/gtxghsntiq.html

pat = re.compile(r"\d+")
来源：http://dali.chenzaomai.com/Article/details/gtymrebmva.html

[U19] Py：正则替换带回调
来源：http://dali.yuanzhike.top/Article/details/gtjebighza.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttivscth.html

[U20] Py：缓存函数结果
来源：http://dali.shzxlz.cn/Article/details/gtehcwivxk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxuanxn.top/Article/details/gtjsubiskj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhengqikj.top/Article/details/gtgejjrttw.html

@contextlib.contextmanager
来源：http://dali.hysaishi.cn/Article/details/gtdjxaedxq.html

[U22] Py：矩阵转置
来源：http://dali.guowangkeji.top/Article/details/gtuvikraon.html

list(zip(*m))
来源：http://dali.ydzc1.top/Article/details/gtftlphsku.html

[U23] Py：分块读取大文件
来源：http://dali.daria6918.cn/Article/details/gtqqkzjkjt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yonumen.top/Article/details/gtegharkjp.html

[U24] Py：路径操作
来源：http://dali.smart0.xyz/Article/details/gtlcaptwna.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gtpydiwnoa.html

[U25] Py：CSV 按字典读
来源：http://dali.birdmap.top/Article/details/gtxdkuehnk.html

csv.DictReader(f)
来源：http://dali.shzxlz.cn/Article/details/gtuzzjuazt.html

[U26] Py：并发下载
来源：http://dali.xylfe.cn/Article/details/gtaybxqjcn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.nwbrower.top/Article/details/gtcjcoyfrc.html

[U27] Py：异步 HTTP
来源：http://dali.jlsjyb.cn/Article/details/gtukxeozpl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.pycfn.com/Article/details/gtioxkpofu.html

[U28] Py：类型别名
来源：http://dali.tian-w.cn/Article/details/gtljdvvwkv.html

UserId = int
来源：http://dali.cashguo.top/Article/details/gtyugsrzoy.html

[U29] Py：属性校验
来源：http://dali.hywenlv.cn/Article/details/gtmarjkikf.html

@property 与 @x.setter 配合
来源：http://dali.cqqwz.cn/Article/details/gtxvmwiyhq.html

[U30] Py：数据类
来源：http://dali.cheryme.top/Article/details/gtbawlzadk.html

@dataclass(slots=True)
来源：http://dali.haohaochexian.top/Article/details/gtfchjegoy.html

[U31] Py：单测
来源：http://dali.tianlin.xyz/Article/details/gtcrtriywa.html

python -m pytest -q
来源：http://dali.zhixingplan.top/Article/details/gtbjwfepuw.html

[U32] Py：代码格式化
来源：http://dali.yj20258888.top/Article/details/gtukuexnqr.html

ruff format . && ruff check --fix .
来源：http://dali.aizwys.cn/Article/details/gtjudhqpfs.html

[U33] Py：打包发布
来源：http://dali.ybcxt.top/Article/details/gtsnqfweej.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hysaishi.cn/Article/details/gtuxiplabl.html

[U34] Py：判断编码
来源：http://dali.zdqjudy.top/Article/details/gtcrfuexfb.html

chardet.detect(raw)
来源：http://dali.guannengcc.top/Article/details/gtyuwgvoxe.html

[U35] Py：发送邮件
来源：http://dali.shuidangran.top/Article/details/gtsfhbfzum.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.snrcjt.cn/Article/details/gtulytmggn.html

[U36] Py：定时任务
来源：http://dali.sufxvd.cn/Article/details/gtslvbxlez.html

schedule.every(10).minutes.do(job)
来源：http://dali.fengsongda.top/Article/details/gtdczvtbqw.html

[U37] Py：读写 Excel
来源：http://dali.wangdashe.top/Article/details/gtiufiagdf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.sxryk.cn/Article/details/gtgpmqoxqk.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhiwuduotai.top/Article/details/gtqhafgeat.html

Path(__file__).resolve().parent
来源：http://dali.havefunace.top/Article/details/gtmjyffthn.html

[U39] Py：判断是否在交互环境
来源：http://dali.yuxming.cn/Article/details/gtqwylrehy.html

sys.stdout.isatty()
来源：http://dali.xziqi.cn/Article/details/gtgizlukro.html

[U40] Py：打印到标准错误
来源：http://dali.yj20258.top/Article/details/gtjoygtzbe.html

print("err", file=sys.stderr)
来源：http://dali.birdmap.top/Article/details/gtqerikgll.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenzaomai.com/Article/details/gtihrytjbu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xinyue.icu/Article/details/gtytswygdr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jqgfzy.top/Article/details/gtxnitbhfz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzqqlesi.html

[U43] PHP：声明命名空间
来源：http://dali.hfpthk.cn/Article/details/gtbpkyjdyo.html

namespace App\Http;
来源：http://dali.fengsongda.top/Article/details/gtpuirllue.html

[U44] PHP：开启严格类型
来源：http://dali.quarkkingdee.top/Article/details/gtumrsclaf.html

declare(strict_types=1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwavrzypz.html


<!-- 参考信息 -->