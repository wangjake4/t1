代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.meibo888.top/Article/details/gtmsyyyncv.html

[S25] C：内存拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpcptvdf.html

memcpy(dst, src, n);
来源：http://dali.haohaochexian.top/Article/details/gtvqvlpuqg.html

[S26] C：内存清零
来源：http://dali.316326.xyz/Article/details/gtegrjstcp.html

memset(a, 0, sizeof a);
来源：http://dali.wangdashe.top/Article/details/gtahghgzgy.html

[S27] C：定义常量
来源：http://dali.nanxuanxn.top/Article/details/gtijevozik.html

const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtisktzdeg.html

[S28] C：静态变量
来源：http://dali.jinqigfzy.top/Article/details/gtolehaiab.html

static int counter = 0;
来源：http://dali.feifeiyinyue.top/Article/details/gtpwqsocia.html

[S29] C：变参函数
来源：http://dali.sysykeji.top/Article/details/gtcqknoxog.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.snrcjt.cn/Article/details/gtqirbrnsx.html

[S30] C：头文件保护
来源：http://dali.0kj1m.cn/Article/details/gtinadzqua.html

#ifndef X_H
来源：http://dali.redwolf501.top/Article/details/gtalrzltyd.html

#define X_H
来源：http://dali.yuxming.cn/Article/details/gtapcfslcd.html

#endif
来源：http://dali.ppjwa.cn/Article/details/gtkyjbcnnk.html

[S31] C++：Hello World
来源：http://dali.yj20258.top/Article/details/gtkpguhvva.html

#include <iostream>
来源：http://dali.yj20258.top/Article/details/gtindpyyzl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gtyplpdzgm.html

[S32] C++：字符串
来源：http://dali.yuxming.cn/Article/details/gtulijvdqk.html

std::string s = "hi";  s += "!";
来源：http://dali.gaohongyu789.top/Article/details/gtdmdbtihz.html

[S33] C++：vector 增删
来源：http://dali.yuxming.cn/Article/details/gtaahsnvsh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cashguo.top/Article/details/gtacctlzgx.html

[S34] C++：遍历 vector
来源：http://dali.zhiwuduotai.top/Article/details/gtkfclqfeo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjhczrmbb.html

[S35] C++：map
来源：http://dali.zhoulong.xyz/Article/details/gtzdciovvd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtcpzhjvsx.html

[S36] C++：unordered_map
来源：http://dali.jianghu66.top/Article/details/gtsyvvqbij.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgdhglao.html

[S37] C++：set
来源：http://dali.birdmap.top/Article/details/gtccufoxim.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ydzc1.top/Article/details/gtttyagvpc.html

[S38] C++：排序
来源：http://dali.hnxiangtu.top/Article/details/gtgqcjmwhi.html

std::sort(v.begin(), v.end());
来源：http://dali.shuidangran.top/Article/details/gtcwezasip.html

[S39] C++：自定义比较器排序
来源：http://dali.haohaochexian.top/Article/details/gtivinqnky.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.snrcjt.cn/Article/details/gtvimrttpk.html

[S40] C++：查找元素
来源：http://dali.quarkkingdee.top/Article/details/gtuqtnzdvy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cdnleiting.top/Article/details/gtxcfozwxx.html

[S41] C++：类与构造函数
来源：http://dali.yonumen.top/Article/details/gtchpgeuus.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgufenzy.top/Article/details/gtatglgtsh.html

[S42] C++：继承与虚函数
来源：http://dali.jqgufenzy.top/Article/details/gthrudmkpw.html

class B : public Base { public: void f() override {} };
来源：http://dali.tanke756.top/Article/details/gtmfadlycb.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gtxjyhdllb.html

auto p = std::make_unique<int>(5);
来源：http://dali.dianchejie.cn/Article/details/gtshnekace.html

[S44] C++：引用传参
来源：http://dali.c1oappe.top/Article/details/gtseeiawrc.html

void inc(int &x) { ++x; }
来源：http://dali.dashuyun.cn/Article/details/gtnpxuuxwg.html

[S45] C++：lambda
来源：http://dali.9152youxi.cn/Article/details/gtkfedojcp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hammf.cn/Article/details/gtwszvmkhz.html

[S46] C++：函数模板
来源：http://dali.ivvv.top/Article/details/gtpthtulfz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gzhubu.top/Article/details/gtxqfuldbz.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbguzdgi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gogol.net.cn/Article/details/gtuqvocqdz.html

[S48] C++：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtdjnnxosa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.feifeiyinyue.top/Article/details/gtyvgpxpys.html

while (std::getline(in, line)) { }
来源：http://dali.mhx1999.top/Article/details/gtrtkpcmra.html

[S49] C++：写文件
来源：http://dali.jianghu66.top/Article/details/gtnbzfvsbl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.mhx1999.top/Article/details/gtvdmssgei.html

[S50] C++：格式化数字
来源：http://dali.hongshengwenyu.top/Article/details/gtkpheahbf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjjvykys.html

[S51] C++：显式类型转换
来源：http://dali.jinqigfzy.top/Article/details/gtrkzoinxd.html

static_cast<double>(a) / b
来源：http://dali.bjfxy.top/Article/details/gtdgtopmsu.html

[S52] C++：const 与 noexcept
来源：http://dali.ppjwa.cn/Article/details/gtxdchtvvk.html

int size() const noexcept { return n_; }
来源：http://dali.cucudq.cn/Article/details/gtsqnfkaqc.html

[S53] C++：移动语义
来源：http://dali.jianghu66.top/Article/details/gtznipgvlh.html

std::vector<int> w = std::move(v);
来源：http://dali.iojbl.cn/Article/details/gttwaohdpj.html

[S54] C++：异常处理
来源：http://dali.haohaochexian.top/Article/details/gtobfdogjb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtzhquukfm.html

[S55] C++：结构化绑定
来源：http://dali.jyoumei.cn/Article/details/gthnyatfth.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xziqi.cn/Article/details/gtvzvekaqi.html

[S56] C++：optional
来源：http://dali.nwbrower.top/Article/details/gtbaxxxkaj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gtgoderfhz.html

[S57] C++：编译期常量
来源：http://dali.ivvv.top/Article/details/gtcovbnmzf.html

constexpr int N = 10;
来源：http://dali.cqqwz.cn/Article/details/gtwrabsccf.html

[S58] C++：命名空间
来源：http://dali.hammf.cn/Article/details/gtkrvhzvxy.html

namespace ns { int f() { return 1; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtittgjbcg.html

[S59] C++：静态断言
来源：http://dali.mhx1999.top/Article/details/gtccowesft.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ppjwa.cn/Article/details/gtabtjqulj.html

[S60] C++：遍历并删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gtoupptgqu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sysykeji.top/Article/details/gtmalfhypt.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtgfdpyhom.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tianlin.xyz/Article/details/gtsftzfkyr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtpblfcelz.html

[T01] Kotlin：Hello World
来源：http://dali.guannengcc.top/Article/details/gthwcbjsip.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gtfxmvwmwk.html

[T02] Kotlin：变量
来源：http://dali.hysaishi.cn/Article/details/gtwbccnasj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xylfe.cn/Article/details/gtjyzwdpda.html

[T03] Kotlin：字符串模板
来源：http://dali.yj20258888.top/Article/details/gtcfzhbkkv.html

"值: $b"
来源：http://dali.tian-w.cn/Article/details/gtbgcqkzyw.html

[T04] Kotlin：空安全
来源：http://dali.yongpay.top/Article/details/gtnnwbftwa.html

val n: String? = null;  n?.length
来源：http://dali.xuetiantiany.cn/Article/details/gtopogjzqx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gtcpnzjmlt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gotoacloud.top/Article/details/gtggfhorcj.html

[T06] Kotlin：集合映射
来源：http://dali.birdmap.top/Article/details/gtdrdctcij.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.redwolf501.top/Article/details/gtppukgmwk.html

[T07] Kotlin：集合过滤
来源：http://dali.ydzc1.top/Article/details/gttvcycchb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yvedp.cn/Article/details/gtspnpqfcp.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gtsqyfhzab.html

data class User(val name: String, val age: Int)
来源：http://dali.redwolf501.top/Article/details/gtageohcni.html

[T09] Kotlin：扩展函数
来源：http://dali.jinqigufen.top/Article/details/gtccrvvyfk.html

fun String.exclaim() = this + "!"
来源：http://dali.pengpengdd.cyou/Article/details/gthfwowdif.html

[T10] Kotlin：默认参数
来源：http://dali.kuanghao11.cn/Article/details/gtzpvphqld.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.andypj.xyz/Article/details/gteercfmqh.html

[T11] Kotlin：协程
来源：http://dali.jiagoushi.top/Article/details/gtoummimzc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yongpay.top/Article/details/gtwdisosjc.html

[T12] Kotlin：解构声明
来源：http://dali.hfpthk.cn/Article/details/gtwfyzaeup.html

val (a, b) = Pair(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gtcnpndpbe.html

[T13] Kotlin：只读 Map
来源：http://dali.fengsongda.top/Article/details/gttibdjxxm.html

val m = mapOf("a" to 1)
来源：http://dali.cdnleiting.top/Article/details/gtwckpnqla.html

[T14] Kotlin：循环
来源：http://dali.dianchejie.cn/Article/details/gtfhtvvqar.html

for (i in 1..10) println(i)
来源：http://dali.zhixingplan.top/Article/details/gthhqyugjy.html

[T15] Kotlin：接口
来源：http://dali.meibo888.top/Article/details/gtbdcltoqt.html

interface Shape { fun area(): Double }
来源：http://dali.gotoacloud.top/Article/details/gtnkawdacw.html

[T16] Swift：Hello World
来源：http://dali.tanke756.top/Article/details/gtjxnnantc.html

print("Hello")
来源：http://dali.ivvv.top/Article/details/gtencnucof.html

[T17] Swift：变量与常量
来源：http://dali.316326.xyz/Article/details/gtszerqcle.html

var a = 1;  let b = 2
来源：http://dali.9152youxi.cn/Article/details/gtxwyiezkj.html

[T18] Swift：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gttczmuhnp.html

"值: \(b)"
来源：http://dali.cheryme.top/Article/details/gtjuuhuchk.html

[T19] Swift：可选绑定
来源：http://dali.cdnleiting.top/Article/details/gtzksywbyg.html

if let n = opt { print(n) }
来源：http://dali.xuanzx.com/Article/details/gtyutapfby.html

[T20] Swift：数组操作
来源：http://dali.smart0.xyz/Article/details/gtfcezdqiu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gotoacloud.top/Article/details/gtlemvevte.html

[T21] Swift：遍历
来源：http://dali.snrcjt.cn/Article/details/gtycqrthso.html

for x in a { print(x) }
来源：http://dali.tanke756.top/Article/details/gthfdajyuv.html

[T22] Swift：字典
来源：http://dali.zhixingplan.top/Article/details/gtagtvwomk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gthyrllyzm.html

[T23] Swift：函数
来源：http://dali.fzhhl.top/Article/details/gtcprybhgh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlzcrhme.html

[T24] Swift：闭包
来源：http://dali.yuanzhike.top/Article/details/gteakxwfhe.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtpxmakaxq.html

[T25] Swift：结构体
来源：http://dali.redwolf501.top/Article/details/gtvsyfmokh.html

struct P { var x: Int }
来源：http://dali.shzxlz.cn/Article/details/gtdswyquxq.html

[T26] Swift：类与重写
来源：http://dali.hnxiangtu.top/Article/details/gtjpiyxljy.html

class A: Base { override func f() {} }
来源：http://dali.sweek.top/Article/details/gtyvblnptk.html

[T27] Swift：错误处理
来源：http://dali.xylfe.cn/Article/details/gtlyxyhnqt.html

do { try f() } catch { print(error) }
来源：http://dali.gotoacloud.top/Article/details/gtbzpuuuow.html

[T28] Swift：枚举
来源：http://dali.0kj1m.cn/Article/details/gtbvubzahr.html

enum Color { case red, green }
来源：http://dali.gogol.net.cn/Article/details/gtwabpevnp.html

[T29] Swift：guard 提前返回
来源：http://dali.tanke756.top/Article/details/gtzkyubjwa.html

guard let x = opt else { return }
来源：http://dali.jianghu66.top/Article/details/gtceznczgy.html

[T30] Swift：协议
来源：http://dali.jqgufenzy.top/Article/details/gtjbfzveqt.html

protocol Shape { func area() -> Double }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfaitrbjq.html

[T31] Lua：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtvbxosnfx.html

print("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtifljftwj.html

[T32] Lua：局部变量
来源：http://dali.birdmap.top/Article/details/gtjqskemun.html

local a = 1
来源：http://dali.cheryme.top/Article/details/gtlgzdtwms.html

[T33] Lua：表（数组）
来源：http://dali.ivvv.top/Article/details/gtdjgqpskm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tianlin.xyz/Article/details/gtvmeifqhc.html

[T34] Lua：遍历表
来源：http://dali.sxryk.cn/Article/details/gtwefixkww.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shuidangran.top/Article/details/gtnudalarz.html

[T35] Lua：字典表
来源：http://dali.ybcxt.top/Article/details/gtawwaklzj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.mhx1999.top/Article/details/gthxkpkxye.html

[T36] Lua：函数
来源：http://dali.ivvv.top/Article/details/gtmmvrpovu.html

function add(a, b) return a + b end
来源：http://dali.chenzaomai.com/Article/details/gtlxunuupv.html

[T37] Lua：字符串拼接
来源：http://dali.sweek.top/Article/details/gttmxzubsd.html

"a" .. "b"
来源：http://dali.yuanzhike.top/Article/details/gtusvwzkdu.html

[T38] Lua：条件
来源：http://dali.gaohongyu789.top/Article/details/gtqmjdqsxb.html

if x > 0 then print("正") end
来源：http://dali.zhixingplan.top/Article/details/gtqhmmmjgz.html

[T39] Lua：模式匹配
来源：http://dali.meibo888.top/Article/details/gtcqzxkgil.html

string.find(s, "%d+")
来源：http://dali.jianghu66.top/Article/details/gtrygeccih.html

[T40] Lua：元表
来源：http://dali.yonumen.top/Article/details/gtgsoqdwig.html

setmetatable({}, { __index = base })
来源：http://dali.jiagoushi.top/Article/details/gtfblpwxzc.html

[T41] Perl：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtorfsfsut.html

print "Hello\n";
来源：http://dali.jinqigufen.top/Article/details/gtavmtikby.html

[T42] Perl：变量类型
来源：http://dali.ivvv.top/Article/details/gtqovyhcau.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yongpay.top/Article/details/gtonwdxeat.html

[T43] Perl：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnqldpck.html

"值: $a"
来源：http://dali.shanyushiyangtech.top/Article/details/gtknielwep.html

[T44] Perl：条件
来源：http://dali.jinqigufen.top/Article/details/gtstxcowzj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhixingplan.top/Article/details/gtothqjshj.html

[T45] Perl：数组遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmlluvpb.html

for my $x (@arr) { print $x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpeiyxhsr.html

[T46] Perl：哈希操作
来源：http://dali.jyoumei.cn/Article/details/gtgolmpogt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gogol.net.cn/Article/details/gtztqfoqij.html

[T47] Perl：正则捕获
来源：http://dali.yongpay.top/Article/details/gtkotozlcj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.smart0.xyz/Article/details/gthnfksqoj.html

[T48] Perl：正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gtdlvfexua.html

$s =~ s/old/new/g;
来源：http://dali.zhoulong.xyz/Article/details/gtfvposxyf.html

[T49] Perl：函数
来源：http://dali.guowangkeji.top/Article/details/gtsroqeqqk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gthxqitthy.html

[T50] Perl：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtapooyjum.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shanyushiyangtech.top/Article/details/gthotplrhz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hfpthk.cn/Article/details/gtvtqbwojl.html

[T51] Scala：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtwwgnpucx.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtatuybnpw.html

[T52] Scala：变量
来源：http://dali.zhixingplan.top/Article/details/gtyoalltox.html

val a = 1;  var b = 2
来源：http://dali.tanke756.top/Article/details/gtamxxpcke.html

[T53] Scala：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtgewjfqje.html

s"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gtsaiaznmx.html

[T54] Scala：集合映射
来源：http://dali.fzhhl.top/Article/details/gtxpzfwgfs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtxvirbnwj.html

[T55] Scala：集合过滤
来源：http://dali.fengsongda.top/Article/details/gtjlesccfx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jiagoushi.top/Article/details/gtminwyriy.html

[T56] Scala：样例类
来源：http://dali.xuetiantiany.cn/Article/details/gtilxulvnn.html

case class User(name: String, age: Int)
来源：http://dali.ivvv.top/Article/details/gtbskvvtgi.html

[T57] Scala：模式匹配
来源：http://dali.mhx1999.top/Article/details/gtsesktipp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yonumen.top/Article/details/gtexydpjkl.html

[T58] Scala：函数定义
来源：http://dali.shzxlz.cn/Article/details/gtmakjiebc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ybcxt.top/Article/details/gtmrhtdzwi.html

[T59] Scala：循环
来源：http://dali.zhongyouzk.top/Article/details/gtsqkimiel.html

for (i <- 1 to 10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gtqgtqzvvz.html

[T60] Scala：折叠
来源：http://dali.c1oappe.top/Article/details/gtyokolmiw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258888.top/Article/details/gtjqsnvmem.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtpdjetmwr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nwbrower.top/Article/details/gttzyvbgkz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtxizblwgi.html

[U01] Py：创建虚拟环境
来源：http://dali.jyoumei.cn/Article/details/gtdqxkpdvr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hnqzz.top/Article/details/gtstzvaeug.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xinyue.icu/Article/details/gtuqghosxs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gotoacloud.top/Article/details/gtwbllljcp.html

[U03] Py：加载 .env 配置
来源：http://dali.fengsongda.top/Article/details/gthfarmtfp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxinkj.top/Article/details/gtqvunrptn.html

[U04] Py：变量调试打印
来源：http://dali.ehwqpu.com/Article/details/gtjwoiiqpv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhixingplan.top/Article/details/gtrtgnbrtk.html

[U05] Py：列表去重且保序
来源：http://dali.daxiang520.top/Article/details/gtixxpffdu.html

list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gtmgdwgdtv.html

[U06] Py：合并两个字典
来源：http://dali.pengpengdd.cyou/Article/details/gtocaltmwu.html

{**a, **b}
来源：http://dali.jianghu66.top/Article/details/gtjbujzmab.html

[U07] Py：反转字典键值
来源：http://dali.cashguo.top/Article/details/gtcjnuqywa.html

{v: k for k, v in d.items()}
来源：http://dali.fzhhl.top/Article/details/gtyejrhtlj.html

[U08] Py：展平二维列表
来源：http://dali.yangfankeji.com/Article/details/gtlmnodfwz.html

[y for x in nested for y in x]
来源：http://dali.dianchejie.cn/Article/details/gttmqyeoso.html

[U09] Py：字典取最大值的键
来源：http://dali.aibaodan.cn/Article/details/gtvugekixn.html

max(d, key=d.get)
来源：http://dali.shzxlz.cn/Article/details/gtzrxyfhfz.html

[U10] Py：按值排序字典
来源：http://dali.hammf.cn/Article/details/gtqiwpagnp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ppjwa.cn/Article/details/gttlanygqh.html

[U11] Py：生成器表达式
来源：http://dali.tianlin.xyz/Article/details/gtumohrfow.html

(x * 2 for x in arr)
来源：http://dali.wangdashe.top/Article/details/gtqumtmpuj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cucudq.cn/Article/details/gtpyapybvq.html

Counter(arr).most_common(3)
来源：http://dali.tanke756.top/Article/details/gtprslglfg.html

[U13] Py：固定长度队列
来源：http://dali.zhengqikj.top/Article/details/gtuccdrzbq.html

deque(maxlen=10)
来源：http://dali.yvedp.cn/Article/details/gtxvouuhdn.html

[U14] Py：分组收集到列表
来源：http://dali.cheryme.top/Article/details/gthuvevqqg.html

defaultdict(list)
来源：http://dali.ivvv.top/Article/details/gtfqsutkjs.html

[U15] Py：高精度计时
来源：http://dali.mhx1999.top/Article/details/gtrwxmbbov.html

t = time.perf_counter()
来源：http://dali.jqgufenzy.top/Article/details/gtnsabwqql.html

[U16] Py：命令行参数解析
来源：http://dali.daxiang520.top/Article/details/gtdetiidvn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ppjwa.cn/Article/details/gtuoouatdu.html

[U17] Py：初始化日志
来源：http://dali.yangfankeji.com/Article/details/gtisrhhekq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.feifeiyinyue.top/Article/details/gtnoohhetc.html

[U18] Py：预编译正则
来源：http://dali.shuidangran.top/Article/details/gtlkmebqxg.html

pat = re.compile(r"\d+")
来源：http://dali.guowangkeji.top/Article/details/gtvezslwaz.html

[U19] Py：正则替换带回调
来源：http://dali.gzhubu.top/Article/details/gtninkrbzd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yueranfly.top/Article/details/gtvqnbyzjb.html

[U20] Py：缓存函数结果
来源：http://dali.zhixingplan.top/Article/details/gtswgodvlg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xuetiantiany.cn/Article/details/gtltnxgzxs.html

[U21] Py：自定义上下文管理器
来源：http://dali.yuxming.cn/Article/details/gtxnkzixwa.html

@contextlib.contextmanager
来源：http://dali.jqgufenzy.top/Article/details/gtxvoswywq.html

[U22] Py：矩阵转置
来源：http://dali.aibaodan.cn/Article/details/gtxnlpmmkr.html

list(zip(*m))
来源：http://dali.ppjwa.cn/Article/details/gttzlszbtc.html

[U23] Py：分块读取大文件
来源：http://dali.jlsjyb.cn/Article/details/gtjhwswcxh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.guowangkeji.top/Article/details/gtqbmkbqrz.html

[U24] Py：路径操作
来源：http://dali.9152youxi.cn/Article/details/gtghbefjxg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gtuzycndfn.html

[U25] Py：CSV 按字典读
来源：http://dali.birdmap.top/Article/details/gtwyxsfvzn.html

csv.DictReader(f)
来源：http://dali.jqgufenzy.top/Article/details/gtqyngcidq.html

[U26] Py：并发下载
来源：http://dali.c1oappe.top/Article/details/gtyzqxsixo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jqgfzy.top/Article/details/gtcokvyzsb.html

[U27] Py：异步 HTTP
来源：http://dali.daria6918.cn/Article/details/gttircyopl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jqgufenzy.top/Article/details/gtjltmbacd.html

[U28] Py：类型别名
来源：http://dali.hysaishi.cn/Article/details/gtvafombtu.html

UserId = int
来源：http://dali.pycfn.com/Article/details/gtjdfgxkaj.html

[U29] Py：属性校验
来源：http://dali.guannengcc.top/Article/details/gtdrjdvlgh.html

@property 与 @x.setter 配合
来源：http://dali.fzhhl.top/Article/details/gticmdhous.html

[U30] Py：数据类
来源：http://dali.hnxiangtu.top/Article/details/gtbggeweiu.html

@dataclass(slots=True)
来源：http://dali.svipenyu.cn/Article/details/gtdjqyiphh.html

[U31] Py：单测
来源：http://dali.iojbl.cn/Article/details/gtgklxbehk.html

python -m pytest -q
来源：http://dali.aibaodan.cn/Article/details/gtwmxafxnw.html

[U32] Py：代码格式化
来源：http://dali.9152youxi.cn/Article/details/gthiwbaevv.html

ruff format . && ruff check --fix .
来源：http://dali.cheryme.top/Article/details/gtsruwmhzt.html

[U33] Py：打包发布
来源：http://dali.chenjidiqi.icu/Article/details/gtycskocsz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xziqi.cn/Article/details/gttnfattqp.html

[U34] Py：判断编码
来源：http://dali.meibo888.top/Article/details/gtwnihkxsc.html

chardet.detect(raw)
来源：http://dali.pengpengdd.cyou/Article/details/gtophzhvuj.html

[U35] Py：发送邮件
来源：http://dali.9152youxi.cn/Article/details/gtdqfwrkiy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.guowangkeji.top/Article/details/gtmulbxcqt.html

[U36] Py：定时任务
来源：http://dali.zhengqikj.top/Article/details/gtqiahmhso.html

schedule.every(10).minutes.do(job)
来源：http://dali.guowangkeji.top/Article/details/gtdfagvqdb.html

[U37] Py：读写 Excel
来源：http://dali.birdmap.top/Article/details/gtvaknyhts.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinqigfzy.top/Article/details/gtkrmypgom.html

[U38] Py：获取脚本所在目录
来源：http://dali.daxiang520.top/Article/details/gtdixbtnyt.html

Path(__file__).resolve().parent
来源：http://dali.c1oappe.top/Article/details/gtbvzpgihi.html

[U39] Py：判断是否在交互环境
来源：http://dali.ivvv.top/Article/details/gtjesvdexs.html

sys.stdout.isatty()
来源：http://dali.cashguo.top/Article/details/gtowjclkcb.html

[U40] Py：打印到标准错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbzyehvo.html

print("err", file=sys.stderr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwpawjko.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.feifeiyinyue.top/Article/details/gtzqffhwho.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.birdmap.top/Article/details/gtzrrztvcz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.andypj.xyz/Article/details/gtficviqjn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hysaishi.cn/Article/details/gttdqnfsbk.html

[U43] PHP：声明命名空间
来源：http://dali.sysykeji.top/Article/details/gtvopymxip.html

namespace App\Http;
来源：http://dali.chenlongwang.top/Article/details/gtghvreity.html

[U44] PHP：开启严格类型
来源：http://dali.c1oappe.top/Article/details/gtobymrqdr.html

declare(strict_types=1);
来源：http://dali.316326.xyz/Article/details/gtxeyxcdsy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtkddkvdgr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtapkbojlu.html

[U46] PHP：可空类型
来源：http://dali.hywenlv.cn/Article/details/gtsngulrnf.html

?string $name = null
来源：http://dali.jiagoushi.top/Article/details/gtyjbnqass.html

[U47] PHP：联合类型
来源：http://dali.jlsjyb.cn/Article/details/gtdwbgitus.html

int|string $id
来源：http://dali.zhongyouzk.top/Article/details/gteqhhicee.html

[U48] PHP：纯枚举
来源：http://dali.ybcxt.top/Article/details/gtkuxivbmj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gogol.net.cn/Article/details/gtmoklluer.html


<!-- 参考信息 -->