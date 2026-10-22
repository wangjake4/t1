代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gt2mjsuhoqu.html

[S21] C：字符类别判断
来源：http://dali.redwolf501.top/Article/details/gt2dckeihph.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gzhubu.top/Article/details/gt2aukqzwch.html

[S22] C：字符串转数字
来源：http://dali.tian-w.cn/Article/details/gt2qzstkpqg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gaohongyu789.top/Article/details/gt2akphzvtu.html

[S23] C：随机数
来源：http://dali.yj20258.top/Article/details/gt2kxtdzoga.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fengsongda.top/Article/details/gt2btlxusvs.html

[S24] C：获取本地时间
来源：http://dali.chenzaomai.com/Article/details/gt2bercgghi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.vqdsnc.cn/Article/details/gt2rqiqcwhn.html

[S25] C：内存拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gt2nbtuqcfv.html

memcpy(dst, src, n);
来源：http://dali.sufxvd.cn/Article/details/gt2iqmlzhok.html

[S26] C：内存清零
来源：http://dali.chenjidiqi.icu/Article/details/gt2mplvzeqp.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258888.top/Article/details/gt2ywvqbunw.html

[S27] C：定义常量
来源：http://dali.shzxlz.cn/Article/details/gt2kfsttejc.html

const double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gt2wfrvjkuq.html

[S28] C：静态变量
来源：http://dali.sufxvd.cn/Article/details/gt2kigglxdq.html

static int counter = 0;
来源：http://dali.smart0.xyz/Article/details/gt2mquqpfhm.html

[S29] C：变参函数
来源：http://dali.aibaodan.cn/Article/details/gt2kfkimqxy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zycfv.cn/Article/details/gt2jrdobxzf.html

[S30] C：头文件保护
来源：http://dali.chenjidiqi.icu/Article/details/gt2cvdkjscj.html

#ifndef X_H
来源：http://dali.316326.xyz/Article/details/gt2jpnseiny.html

#define X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2onipvlaw.html

#endif
来源：http://dali.ivvv.top/Article/details/gt2iwbkocbv.html

[S31] C++：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2gfdvplbl.html

#include <iostream>
来源：http://dali.pycfn.com/Article/details/gt2kjgufvyw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gt2bcmfyxmt.html

[S32] C++：字符串
来源：http://dali.zycfv.cn/Article/details/gt2amwfeofx.html

std::string s = "hi";  s += "!";
来源：http://dali.smart0.xyz/Article/details/gt2rzwckfqm.html

[S33] C++：vector 增删
来源：http://dali.havefunace.top/Article/details/gt2wnibywzb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yueranfly.top/Article/details/gt2ymtkwcix.html

[S34] C++：遍历 vector
来源：http://dali.shzxlz.cn/Article/details/gt2otisclqr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.snrcjt.cn/Article/details/gt2rakkhozh.html

[S35] C++：map
来源：http://dali.gogol.net.cn/Article/details/gt2nigyxcxd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2yjwnzqyp.html

[S36] C++：unordered_map
来源：http://dali.zdqjudy.top/Article/details/gt2kabfpjhx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2tcivaklo.html

[S37] C++：set
来源：http://dali.aizwys.cn/Article/details/gt2vjehkodq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gt2zfmmxavv.html

[S38] C++：排序
来源：http://dali.dianchejie.cn/Article/details/gt2sfbtjquw.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gt2kdsekjzm.html

[S39] C++：自定义比较器排序
来源：http://dali.sysykeji.top/Article/details/gt2uykmdfmt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.mhx1999.top/Article/details/gt2itcpynnc.html

[S40] C++：查找元素
来源：http://dali.yj20258888.top/Article/details/gt2spwhpgth.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cheryme.top/Article/details/gt2outenckp.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gt2ckjqnvfb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ivvv.top/Article/details/gt2bgbiceji.html

[S42] C++：继承与虚函数
来源：http://dali.quarkkingdee.top/Article/details/gt2fswngkhe.html

class B : public Base { public: void f() override {} };
来源：http://dali.guannengcc.top/Article/details/gt2yarebgah.html

[S43] C++：智能指针
来源：http://dali.guowangkeji.top/Article/details/gt2ltqkwniw.html

auto p = std::make_unique<int>(5);
来源：http://dali.birdmap.top/Article/details/gt2zazpqytd.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gt2yldibaea.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gt2rmwfbqmo.html

[S45] C++：lambda
来源：http://dali.cucudq.cn/Article/details/gt2tznsztik.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hfpthk.cn/Article/details/gt2fopgelcf.html

[S46] C++：函数模板
来源：http://dali.nanxuanxn.top/Article/details/gt2onosalsn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jianghu66.top/Article/details/gt2pfeklhuo.html

[S47] C++：结构化绑定遍历
来源：http://dali.yvedp.cn/Article/details/gt2bbvzjvqi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxuanxn.top/Article/details/gt2aenmmiri.html

[S48] C++：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gt2twlosxoa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.daria6918.cn/Article/details/gt2zowsujoe.html

while (std::getline(in, line)) { }
来源：http://dali.yj202588.top/Article/details/gt2gcuywaun.html

[S49] C++：写文件
来源：http://dali.sxryk.cn/Article/details/gt2tkbfcdwt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tianlin.xyz/Article/details/gt2wwgdougr.html

[S50] C++：格式化数字
来源：http://dali.shuidangran.top/Article/details/gt2etuhlxwn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jiexufmu.html

[S51] C++：显式类型转换
来源：http://dali.cucudq.cn/Article/details/gt2tpsbzkot.html

static_cast<double>(a) / b
来源：http://dali.nanxuanxn.top/Article/details/gt2ahbqovnt.html

[S52] C++：const 与 noexcept
来源：http://dali.xinyue.icu/Article/details/gt2awqhbsji.html

int size() const noexcept { return n_; }
来源：http://dali.mhx1999.top/Article/details/gt2zfqdovjf.html

[S53] C++：移动语义
来源：http://dali.hongshengwenyu.top/Article/details/gt2ajahasch.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxuanxn.top/Article/details/gt2wlppunjy.html

[S54] C++：异常处理
来源：http://dali.yj202588.top/Article/details/gt2ipwmlmhg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sweek.top/Article/details/gt2ndwvlfde.html

[S55] C++：结构化绑定
来源：http://dali.ehwqpu.com/Article/details/gt2zwzeleiv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gt2wbuvzjtk.html

[S56] C++：optional
来源：http://dali.nwbrower.top/Article/details/gt2ojudtgby.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aizwys.cn/Article/details/gt2ptohlrqw.html

[S57] C++：编译期常量
来源：http://dali.jyoumei.cn/Article/details/gt2cmxfohzp.html

constexpr int N = 10;
来源：http://dali.fengsongda.top/Article/details/gt2bfnhtesk.html

[S58] C++：命名空间
来源：http://dali.yonumen.top/Article/details/gt2ithgpnyj.html

namespace ns { int f() { return 1; } }
来源：http://dali.cucudq.cn/Article/details/gt2flnctuoa.html

[S59] C++：静态断言
来源：http://dali.fzhhl.top/Article/details/gt2pcrmnlwp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258888.top/Article/details/gt2cynalvui.html

[S60] C++：遍历并删除元素
来源：http://dali.jlsjyb.cn/Article/details/gt2rvckddxw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tianlin.xyz/Article/details/gt2iourcoip.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2rzbgbjyj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gt2otlgfdxf.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2orlpybyo.html

[T01] Kotlin：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2yaiihgeh.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jkssexfa.html

[T02] Kotlin：变量
来源：http://dali.yuanzhike.top/Article/details/gt2xpqsjixa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.snrcjt.cn/Article/details/gt2nksoqymx.html

[T03] Kotlin：字符串模板
来源：http://dali.svipenyu.cn/Article/details/gt2eipxzphv.html

"值: $b"
来源：http://dali.jianghu66.top/Article/details/gt2zpzhyuqj.html

[T04] Kotlin：空安全
来源：http://dali.svipenyu.cn/Article/details/gt2bhuuylky.html

val n: String? = null;  n?.length
来源：http://dali.yvedp.cn/Article/details/gt2bxtzawts.html

[T05] Kotlin：when 表达式
来源：http://dali.sweek.top/Article/details/gt2rekfrria.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.meibo888.top/Article/details/gt2jtnekmji.html

[T06] Kotlin：集合映射
来源：http://dali.svipenyu.cn/Article/details/gt2gdufrhpr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2tyevsdnh.html

[T07] Kotlin：集合过滤
来源：http://dali.tian-w.cn/Article/details/gt2pbccbcyk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gotoacloud.top/Article/details/gt2logzxmpd.html

[T08] Kotlin：数据类
来源：http://dali.tian-w.cn/Article/details/gt2imxobugk.html

data class User(val name: String, val age: Int)
来源：http://dali.iojbl.cn/Article/details/gt2dxvnlheq.html

[T09] Kotlin：扩展函数
来源：http://dali.cucudq.cn/Article/details/gt2vpobmeqk.html

fun String.exclaim() = this + "!"
来源：http://dali.ybcxt.top/Article/details/gt2hpquqnar.html

[T10] Kotlin：默认参数
来源：http://dali.9152youxi.cn/Article/details/gt2iwbdsdpv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.andypj.xyz/Article/details/gt2jizqgtew.html

[T11] Kotlin：协程
来源：http://dali.daxiang520.top/Article/details/gt2lvkfvzxj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gesrnlht.html

[T12] Kotlin：解构声明
来源：http://dali.cqqwz.cn/Article/details/gt2urawulga.html

val (a, b) = Pair(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2etwweaha.html

[T13] Kotlin：只读 Map
来源：http://dali.fengsongda.top/Article/details/gt2copnfhag.html

val m = mapOf("a" to 1)
来源：http://dali.316326.xyz/Article/details/gt2ihlkcmep.html

[T14] Kotlin：循环
来源：http://dali.jlsjyb.cn/Article/details/gt2vgcndoao.html

for (i in 1..10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gt2ptuvpgsl.html

[T15] Kotlin：接口
来源：http://dali.aizwys.cn/Article/details/gt2wyxmcxlh.html

interface Shape { fun area(): Double }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ufsdohea.html

[T16] Swift：Hello World
来源：http://dali.pycfn.com/Article/details/gt2bhdcxbja.html

print("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gt2liowkmmb.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xqjarmhb.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2ihfobmet.html

[T18] Swift：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gt2srjyvxyl.html

"值: \(b)"
来源：http://dali.yj20258888.top/Article/details/gt2nxhqxnht.html

[T19] Swift：可选绑定
来源：http://dali.jinqigfzy.top/Article/details/gt2hmshviuf.html

if let n = opt { print(n) }
来源：http://dali.bjfxy.top/Article/details/gt2pxmjxsis.html

[T20] Swift：数组操作
来源：http://dali.sweek.top/Article/details/gt2rfmplpke.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.kuanghao11.cn/Article/details/gt2lgihocnu.html

[T21] Swift：遍历
来源：http://dali.jiagoushi.top/Article/details/gt2nbxnhudx.html

for x in a { print(x) }
来源：http://dali.aizwys.cn/Article/details/gt2ddgrstfr.html

[T22] Swift：字典
来源：http://dali.dashuyun.cn/Article/details/gt2nfofqayk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yanxiufei.cn/Article/details/gt2llvrahns.html

[T23] Swift：函数
来源：http://dali.gogol.net.cn/Article/details/gt2wqedlqqf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guowangkeji.top/Article/details/gt2sjagcfvk.html

[T24] Swift：闭包
来源：http://dali.gaohongyu789.top/Article/details/gt2rzgurihb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2tvdyjwqx.html

[T25] Swift：结构体
来源：http://dali.shzxlz.cn/Article/details/gt2yukltdlv.html

struct P { var x: Int }
来源：http://dali.nwbrower.top/Article/details/gt2jezorzku.html

[T26] Swift：类与重写
来源：http://dali.yuanzhike.top/Article/details/gt2bgiufyhs.html

class A: Base { override func f() {} }
来源：http://dali.nwbrower.top/Article/details/gt2lupvwdsu.html

[T27] Swift：错误处理
来源：http://dali.yanxiufei.cn/Article/details/gt2onvpyaoe.html

do { try f() } catch { print(error) }
来源：http://dali.hnqzz.top/Article/details/gt2oqfguhvk.html

[T28] Swift：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bqkeczda.html

enum Color { case red, green }
来源：http://dali.nanxuanxn.top/Article/details/gt2uhbwakbt.html

[T29] Swift：guard 提前返回
来源：http://dali.yvedp.cn/Article/details/gt2ztvhxipy.html

guard let x = opt else { return }
来源：http://dali.yangfankeji.com/Article/details/gt2atnjnnex.html

[T30] Swift：协议
来源：http://dali.wangdashe.top/Article/details/gt2mfhjbmym.html

protocol Shape { func area() -> Double }
来源：http://dali.guannengcc.top/Article/details/gt2hbfqrzqf.html

[T31] Lua：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2rjdczhmb.html

print("Hello")
来源：http://dali.dashuyun.cn/Article/details/gt2stufcfhv.html

[T32] Lua：局部变量
来源：http://dali.gotoacloud.top/Article/details/gt2ohfytzzv.html

local a = 1
来源：http://dali.sysykeji.top/Article/details/gt2sovbhblj.html

[T33] Lua：表（数组）
来源：http://dali.yj20258.top/Article/details/gt2qjeoompe.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jianghu66.top/Article/details/gt2pozxmkof.html

[T34] Lua：遍历表
来源：http://dali.daxiang520.top/Article/details/gt2oltogcet.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cashguo.top/Article/details/gt2wmktcyzl.html

[T35] Lua：字典表
来源：http://dali.wangdashe.top/Article/details/gt2ganwaqpd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.9152youxi.cn/Article/details/gt2rcnlcyke.html

[T36] Lua：函数
来源：http://dali.iojbl.cn/Article/details/gt2pnesprwn.html

function add(a, b) return a + b end
来源：http://dali.smart0.xyz/Article/details/gt2yilbnxmn.html

[T37] Lua：字符串拼接
来源：http://dali.zycfv.cn/Article/details/gt2odwciduh.html

"a" .. "b"
来源：http://dali.chenlongwang.top/Article/details/gt2psuvltog.html

[T38] Lua：条件
来源：http://dali.0kj1m.cn/Article/details/gt2zffjdjxb.html

if x > 0 then print("正") end
来源：http://dali.dashuyun.cn/Article/details/gt2dhlurezj.html

[T39] Lua：模式匹配
来源：http://dali.yvedp.cn/Article/details/gt2osqbgsur.html

string.find(s, "%d+")
来源：http://dali.zhoulong.xyz/Article/details/gt2zrciyrjb.html

[T40] Lua：元表
来源：http://dali.yongpay.top/Article/details/gt2monqnzdh.html

setmetatable({}, { __index = base })
来源：http://dali.hongshengwenyu.top/Article/details/gt2unquvzit.html

[T41] Perl：Hello World
来源：http://dali.pycfn.com/Article/details/gt2kttvzseg.html

print "Hello\n";
来源：http://dali.sysykeji.top/Article/details/gt2qksvyyrw.html

[T42] Perl：变量类型
来源：http://dali.yj202588.top/Article/details/gt2ekmilrnl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jlsjyb.cn/Article/details/gt2raenqgix.html

[T43] Perl：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gt2aptbporm.html

"值: $a"
来源：http://dali.fzhhl.top/Article/details/gt2xgsffmzn.html

[T44] Perl：条件
来源：http://dali.haohaochexian.top/Article/details/gt2yrbahghe.html

if ($a > 0) { print "正"; }
来源：http://dali.fengsongda.top/Article/details/gt2ltngccwl.html

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gt2cyizaamj.html

for my $x (@arr) { print $x; }
来源：http://dali.gzhubu.top/Article/details/gt2qacbrlmf.html

[T46] Perl：哈希操作
来源：http://dali.316326.xyz/Article/details/gt2nnphdusx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.daxiang520.top/Article/details/gt2lrhkzvoz.html

[T47] Perl：正则捕获
来源：http://dali.yangfankeji.com/Article/details/gt2dhdlncca.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cdnleiting.top/Article/details/gt2eudhgztl.html

[T48] Perl：正则替换
来源：http://dali.gotoacloud.top/Article/details/gt2nmavzsci.html

$s =~ s/old/new/g;
来源：http://dali.yj20258.top/Article/details/gt2ivqahdmk.html

[T49] Perl：函数
来源：http://dali.chenlongwang.top/Article/details/gt2fnucmzee.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gt2vncyqxal.html

[T50] Perl：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gt2gvfaosus.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gotoacloud.top/Article/details/gt2jhwwsgjt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fzhhl.top/Article/details/gt2bvorjswt.html

[T51] Scala：Hello World
来源：http://dali.316326.xyz/Article/details/gt2nrmqqzdm.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gt2viuwzlvg.html

[T52] Scala：变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2hrurdejb.html

val a = 1;  var b = 2
来源：http://dali.sxryk.cn/Article/details/gt2vzykqcll.html

[T53] Scala：字符串插值
来源：http://dali.aizwys.cn/Article/details/gt2bsobqafj.html

s"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2riabmdbt.html

[T54] Scala：集合映射
来源：http://dali.snrcjt.cn/Article/details/gt2zgbhdepz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sysykeji.top/Article/details/gt2dnsajbrw.html

[T55] Scala：集合过滤
来源：http://dali.smart0.xyz/Article/details/gt2rayvhuvg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.redwolf501.top/Article/details/gt2wmwekemx.html

[T56] Scala：样例类
来源：http://dali.iojbl.cn/Article/details/gt2qqixwrlv.html

case class User(name: String, age: Int)
来源：http://dali.gzhubu.top/Article/details/gt2pdafrniq.html

[T57] Scala：模式匹配
来源：http://dali.ybcxt.top/Article/details/gt2jbplmejd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj202588.top/Article/details/gt2hlqhknug.html

[T58] Scala：函数定义
来源：http://dali.cdnleiting.top/Article/details/gt2hadllwzf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.wangshuangyany.cn/Article/details/gt2deamodru.html

[T59] Scala：循环
来源：http://dali.yuanzhike.top/Article/details/gt2dbktipic.html

for (i <- 1 to 10) println(i)
来源：http://dali.shuidangran.top/Article/details/gt2xdwyxmab.html

[T60] Scala：折叠
来源：http://dali.mhx1999.top/Article/details/gt2heumlvox.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gogol.net.cn/Article/details/gt2tdwsgqfn.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2aripdoik.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yongpay.top/Article/details/gt2dljgbimp.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2tjmvrgga.html

[U01] Py：创建虚拟环境
来源：http://dali.jiagoushi.top/Article/details/gt2qfoabihx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinqigfzy.top/Article/details/gt2hawxylvs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.wangdashe.top/Article/details/gt2erxnnylw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.redwolf501.top/Article/details/gt2lfswwrbc.html

[U03] Py：加载 .env 配置
来源：http://dali.andypj.xyz/Article/details/gt2dtppaymb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hammf.cn/Article/details/gt2lcxlnjsv.html

[U04] Py：变量调试打印
来源：http://dali.birdmap.top/Article/details/gt2tkxxznrq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.fzhhl.top/Article/details/gt2ehaxkdkr.html

[U05] Py：列表去重且保序
来源：http://dali.sufxvd.cn/Article/details/gt2ymgisxry.html

list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2tvokhpba.html

[U06] Py：合并两个字典
来源：http://dali.dianchejie.cn/Article/details/gt2wrkefczg.html

{**a, **b}
来源：http://dali.kuanghao11.cn/Article/details/gt2hwskuxab.html

[U07] Py：反转字典键值
来源：http://dali.9152youxi.cn/Article/details/gt2lkxfiski.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258888.top/Article/details/gt2ryatuete.html

[U08] Py：展平二维列表
来源：http://dali.zhongyouzk.top/Article/details/gt2axvksufd.html

[y for x in nested for y in x]
来源：http://dali.bjfxy.top/Article/details/gt2qznopand.html

[U09] Py：字典取最大值的键
来源：http://dali.gzhubu.top/Article/details/gt2hjfyegvk.html

max(d, key=d.get)
来源：http://dali.daria6918.cn/Article/details/gt2mifrpazk.html

[U10] Py：按值排序字典
来源：http://dali.pengpengdd.cyou/Article/details/gt2ecsosyws.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fzhhl.top/Article/details/gt2clvvzuxg.html

[U11] Py：生成器表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2rpafgdav.html

(x * 2 for x in arr)
来源：http://dali.nwbrower.top/Article/details/gt2ksfkkhgk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2gbwfyqls.html

Counter(arr).most_common(3)
来源：http://dali.daria6918.cn/Article/details/gt2puhqszka.html

[U13] Py：固定长度队列
来源：http://dali.0kj1m.cn/Article/details/gt2rkzqwouc.html

deque(maxlen=10)
来源：http://dali.wangshuangyany.cn/Article/details/gt2eneihyty.html

[U14] Py：分组收集到列表
来源：http://dali.aibaodan.cn/Article/details/gt2wntrdqng.html

defaultdict(list)
来源：http://dali.yangfankeji.com/Article/details/gt2gjnyywoe.html

[U15] Py：高精度计时
来源：http://dali.chenjidiqi.icu/Article/details/gt2mlfxzgpd.html

t = time.perf_counter()
来源：http://dali.andypj.xyz/Article/details/gt2wcroclxy.html

[U16] Py：命令行参数解析
来源：http://dali.fzhhl.top/Article/details/gt2xcqpvbaw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinqigfzy.top/Article/details/gt2ovanivxk.html

[U17] Py：初始化日志
来源：http://dali.cqqwz.cn/Article/details/gt2xaogpplw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhengqikj.top/Article/details/gt2lyapjxsp.html

[U18] Py：预编译正则
来源：http://dali.daria6918.cn/Article/details/gt2ylzwlmvn.html

pat = re.compile(r"\d+")
来源：http://dali.redwolf501.top/Article/details/gt2sbudsocb.html

[U19] Py：正则替换带回调
来源：http://dali.meibo888.top/Article/details/gt2nvggtrkl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sysykeji.top/Article/details/gt2ategoyqa.html

[U20] Py：缓存函数结果
来源：http://dali.jiagoushi.top/Article/details/gt2gllpqede.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tanke756.top/Article/details/gt2hclbtbnp.html

[U21] Py：自定义上下文管理器
来源：http://dali.yueranfly.top/Article/details/gt2zibxasdm.html

@contextlib.contextmanager
来源：http://dali.gogol.net.cn/Article/details/gt2pjlaicox.html

[U22] Py：矩阵转置
来源：http://dali.vqdsnc.cn/Article/details/gt2qfuprsse.html

list(zip(*m))
来源：http://dali.kuanghao11.cn/Article/details/gt2swflpqgt.html

[U23] Py：分块读取大文件
来源：http://dali.jinqigfzy.top/Article/details/gt2nyvvaeip.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.havefunace.top/Article/details/gt2ofjraroe.html

[U24] Py：路径操作
来源：http://dali.kuanghao11.cn/Article/details/gt2wpxhdhcg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhixingplan.top/Article/details/gt2krkduuvy.html

[U25] Py：CSV 按字典读
来源：http://dali.shangyingyoupin.top/Article/details/gt2lsxiknbk.html

csv.DictReader(f)
来源：http://dali.kuanghao11.cn/Article/details/gt2zcahfuym.html

[U26] Py：并发下载
来源：http://dali.yueranfly.top/Article/details/gt2tyhjxehz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.dashuyun.cn/Article/details/gt2bafjqshh.html

[U27] Py：异步 HTTP
来源：http://dali.meibo888.top/Article/details/gt2bxstrgrw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.fzhhl.top/Article/details/gt2wctfnbrx.html

[U28] Py：类型别名
来源：http://dali.yueranfly.top/Article/details/gt2elscecac.html

UserId = int
来源：http://dali.fzhhl.top/Article/details/gt2wzttvjcl.html

[U29] Py：属性校验
来源：http://dali.dashuyun.cn/Article/details/gt2ucgqsuha.html

@property 与 @x.setter 配合
来源：http://dali.chenzaomai.com/Article/details/gt2rmwgopiu.html

[U30] Py：数据类
来源：http://dali.daria6918.cn/Article/details/gt2venenhzv.html

@dataclass(slots=True)
来源：http://dali.zdqjudy.top/Article/details/gt2sdvuptuv.html

[U31] Py：单测
来源：http://dali.tianlin.xyz/Article/details/gt2tzxhnble.html

python -m pytest -q
来源：http://dali.ivvv.top/Article/details/gt2bsshqtmr.html

[U32] Py：代码格式化
来源：http://dali.gogol.net.cn/Article/details/gt2qdzovgvi.html

ruff format . && ruff check --fix .
来源：http://dali.xinyue.icu/Article/details/gt2ffrqzzpr.html

[U33] Py：打包发布
来源：http://dali.jinqigufen.top/Article/details/gt2nhfucvnw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hnxiangtu.top/Article/details/gt2gptikdyz.html

[U34] Py：判断编码
来源：http://dali.xziqi.cn/Article/details/gt2wokaopys.html

chardet.detect(raw)
来源：http://dali.tanke756.top/Article/details/gt2hfbwgwcn.html

[U35] Py：发送邮件
来源：http://dali.snrcjt.cn/Article/details/gt2dvjqiajo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jianghu66.top/Article/details/gt2hnztpmzm.html

[U36] Py：定时任务
来源：http://dali.hysaishi.cn/Article/details/gt2yoryhyho.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj202588.top/Article/details/gt2lsqxaxna.html

[U37] Py：读写 Excel
来源：http://dali.tianlin.xyz/Article/details/gt2eijiazhi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhoulong.xyz/Article/details/gt2rcrwqren.html

[U38] Py：获取脚本所在目录
来源：http://dali.yuanzhike.top/Article/details/gt2vutbecsd.html

Path(__file__).resolve().parent
来源：http://dali.ydzc1.top/Article/details/gt2hygiseoe.html

[U39] Py：判断是否在交互环境
来源：http://dali.tanke756.top/Article/details/gt2qpqmkffm.html

sys.stdout.isatty()
来源：http://dali.daria6918.cn/Article/details/gt2rsedrrku.html

[U40] Py：打印到标准错误
来源：http://dali.ppjwa.cn/Article/details/gt2uomnhxhw.html

print("err", file=sys.stderr)
来源：http://dali.kuanghao11.cn/Article/details/gt2saxdepqx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.bjfxy.top/Article/details/gt2hwthyhij.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2yklylmqv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.bjfxy.top/Article/details/gt2nozytqvr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.quarkkingdee.top/Article/details/gt2nfgmtkhy.html

[U43] PHP：声明命名空间
来源：http://dali.xuanzx.com/Article/details/gt2zxfmkods.html

namespace App\Http;
来源：http://dali.chenzaomai.com/Article/details/gt2iibsecwm.html

[U44] PHP：开启严格类型
来源：http://dali.quarkkingdee.top/Article/details/gt2dbvnanxe.html

declare(strict_types=1);
来源：http://dali.shzxlz.cn/Article/details/gt2fcdltfjn.html


<!-- 参考信息 -->