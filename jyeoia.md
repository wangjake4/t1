代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gt2yuclyqyl.html

[S21] C：字符类别判断
来源：http://dali.cheryme.top/Article/details/gt2wjkyybyn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cheryme.top/Article/details/gt2dxtxclel.html

[S22] C：字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gt2ipvfxhsy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ybcxt.top/Article/details/gt2woypwixk.html

[S23] C：随机数
来源：http://dali.yueranfly.top/Article/details/gt2yneawpgk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj202588.top/Article/details/gt2omavzxzp.html

[S24] C：获取本地时间
来源：http://dali.hysaishi.cn/Article/details/gt2miqrrmpk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuanzhike.top/Article/details/gt2jqmjtyft.html

[S25] C：内存拷贝
来源：http://dali.bjfxy.top/Article/details/gt2zyiskukj.html

memcpy(dst, src, n);
来源：http://dali.jiagoushi.top/Article/details/gt2cjnifrbd.html

[S26] C：内存清零
来源：http://dali.mhx1999.top/Article/details/gt2niywmkvs.html

memset(a, 0, sizeof a);
来源：http://dali.xziqi.cn/Article/details/gt2qydtweia.html

[S27] C：定义常量
来源：http://dali.sweek.top/Article/details/gt2klzhbxtm.html

const double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gt2odjhjbdc.html

[S28] C：静态变量
来源：http://dali.ehwqpu.com/Article/details/gt2zznginus.html

static int counter = 0;
来源：http://dali.tanke756.top/Article/details/gt2qulwgoei.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gt2hppfkmxv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigufen.top/Article/details/gt2hjyujxut.html

[S30] C：头文件保护
来源：http://dali.smart0.xyz/Article/details/gt2slolcmlw.html

#ifndef X_H
来源：http://dali.cheryme.top/Article/details/gt2azdywwks.html

#define X_H
来源：http://dali.hnxiangtu.top/Article/details/gt2ibgqxodz.html

#endif
来源：http://dali.sxryk.cn/Article/details/gt2rfxyjfxe.html

[S31] C++：Hello World
来源：http://dali.yj20258.top/Article/details/gt2dwxmwejj.html

#include <iostream>
来源：http://dali.xinyue.icu/Article/details/gt2xfwllwre.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhixingplan.top/Article/details/gt2xjdzkcoi.html

[S32] C++：字符串
来源：http://dali.ivvv.top/Article/details/gt2pjoxjuhb.html

std::string s = "hi";  s += "!";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yscifhtj.html

[S33] C++：vector 增删
来源：http://dali.daxiang520.top/Article/details/gt2khngszam.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guowangkeji.top/Article/details/gt2ecywdzhp.html

[S34] C++：遍历 vector
来源：http://dali.xuanzx.com/Article/details/gt2bdyrrrnh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.mhx1999.top/Article/details/gt2nvbvtezm.html

[S35] C++：map
来源：http://dali.shangyingyoupin.top/Article/details/gt2kvipurpv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gt2zoyxprai.html

[S36] C++：unordered_map
来源：http://dali.zycfv.cn/Article/details/gt2axfflval.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gt2qrwwmbjn.html

[S37] C++：set
来源：http://dali.gaohongyu789.top/Article/details/gt2oovnuzpp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmkltgsj.html

[S38] C++：排序
来源：http://dali.jinqigufen.top/Article/details/gt2xkyjpqna.html

std::sort(v.begin(), v.end());
来源：http://dali.gotoacloud.top/Article/details/gt2nxhnmuhl.html

[S39] C++：自定义比较器排序
来源：http://dali.sxryk.cn/Article/details/gt2dvzvoqhx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.havefunace.top/Article/details/gt2clomxssf.html

[S40] C++：查找元素
来源：http://dali.yuanzhike.top/Article/details/gt2sxxropjv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigufen.top/Article/details/gt2aulcpaoh.html

[S41] C++：类与构造函数
来源：http://dali.jinqigufen.top/Article/details/gt2adoioclo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aibaodan.cn/Article/details/gt2aqiwkapq.html

[S42] C++：继承与虚函数
来源：http://dali.ivvv.top/Article/details/gt2izpysaxu.html

class B : public Base { public: void f() override {} };
来源：http://dali.sxryk.cn/Article/details/gt2mfuuyclb.html

[S43] C++：智能指针
来源：http://dali.c1oappe.top/Article/details/gt2dhhngtud.html

auto p = std::make_unique<int>(5);
来源：http://dali.9152youxi.cn/Article/details/gt2tuzowlbn.html

[S44] C++：引用传参
来源：http://dali.dashuyun.cn/Article/details/gt2bedpiqip.html

void inc(int &x) { ++x; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ntdotuyb.html

[S45] C++：lambda
来源：http://dali.pengpengdd.cyou/Article/details/gt2gcyniryo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yueranfly.top/Article/details/gt2yvouhaji.html

[S46] C++：函数模板
来源：http://dali.jlsjyb.cn/Article/details/gt2zdhxzdkv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tanke756.top/Article/details/gt2tqeijtgd.html

[S47] C++：结构化绑定遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2mzsmdsqi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guannengcc.top/Article/details/gt2txawlfpu.html

[S48] C++：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gt2qcneyqfw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2agefaxup.html

while (std::getline(in, line)) { }
来源：http://dali.iojbl.cn/Article/details/gt2xyhkgfwj.html

[S49] C++：写文件
来源：http://dali.zycfv.cn/Article/details/gt2ackjrxah.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jianghu66.top/Article/details/gt2prtpjwkf.html

[S50] C++：格式化数字
来源：http://dali.zhengqikj.top/Article/details/gt2qxhpkdja.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sxryk.cn/Article/details/gt2fdgxcpyo.html

[S51] C++：显式类型转换
来源：http://dali.wangdashe.top/Article/details/gt2ohgbqqvm.html

static_cast<double>(a) / b
来源：http://dali.316326.xyz/Article/details/gt2pymqvjqz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhengqikj.top/Article/details/gt2gxefhzoe.html

int size() const noexcept { return n_; }
来源：http://dali.tian-w.cn/Article/details/gt2nzosxofl.html

[S53] C++：移动语义
来源：http://dali.yj20258.top/Article/details/gt2sjytpgje.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gt2elsprivx.html

[S54] C++：异常处理
来源：http://dali.yueranfly.top/Article/details/gt2mnzsrskr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dashuyun.cn/Article/details/gt2vecwaswz.html

[S55] C++：结构化绑定
来源：http://dali.redwolf501.top/Article/details/gt2ctabayhk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shuidangran.top/Article/details/gt2uxyuufpb.html

[S56] C++：optional
来源：http://dali.xuetiantiany.cn/Article/details/gt2lxlhquqr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tian-w.cn/Article/details/gt2xmuxdpzx.html

[S57] C++：编译期常量
来源：http://dali.bjfxy.top/Article/details/gt2izqwdira.html

constexpr int N = 10;
来源：http://dali.jinqigfzy.top/Article/details/gt2rkotqpya.html

[S58] C++：命名空间
来源：http://dali.c1oappe.top/Article/details/gt2vgjuqlnk.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigufen.top/Article/details/gt2thixtuoa.html

[S59] C++：静态断言
来源：http://dali.xziqi.cn/Article/details/gt2nvynmncz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.c1oappe.top/Article/details/gt2avuosuiz.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgfzy.top/Article/details/gt2aixtdzww.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.svipenyu.cn/Article/details/gt2thalioxg.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yrjdmghu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nrizwtgp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ohtfxxcm.html

[T01] Kotlin：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2kvgqrbas.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gt2nkfafebz.html

[T02] Kotlin：变量
来源：http://dali.tanke756.top/Article/details/gt2wimqquwq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aibaodan.cn/Article/details/gt2yjotughh.html

[T03] Kotlin：字符串模板
来源：http://dali.smart0.xyz/Article/details/gt2mygwmqxq.html

"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gt2wrmpiwmq.html

[T04] Kotlin：空安全
来源：http://dali.jianghu66.top/Article/details/gt2svgytbdy.html

val n: String? = null;  n?.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebgfrtte.html

[T05] Kotlin：when 表达式
来源：http://dali.birdmap.top/Article/details/gt2tpozczep.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.smart0.xyz/Article/details/gt2rgyqqgoj.html

[T06] Kotlin：集合映射
来源：http://dali.zhixingplan.top/Article/details/gt2dzrnjkyz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2lhwltdvl.html

[T07] Kotlin：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2jdmujwdp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yonumen.top/Article/details/gt2jjrqsbym.html

[T08] Kotlin：数据类
来源：http://dali.nanxuanxn.top/Article/details/gt2ewempgpj.html

data class User(val name: String, val age: Int)
来源：http://dali.guowangkeji.top/Article/details/gt2pqjlvhxu.html

[T09] Kotlin：扩展函数
来源：http://dali.birdmap.top/Article/details/gt2pboddneu.html

fun String.exclaim() = this + "!"
来源：http://dali.yj202588.top/Article/details/gt2blkynljx.html

[T10] Kotlin：默认参数
来源：http://dali.snrcjt.cn/Article/details/gt2wlotzsdx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuanzx.com/Article/details/gt2kdwkaeuc.html

[T11] Kotlin：协程
来源：http://dali.wangdashe.top/Article/details/gt2fxmpxkze.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2zccxmjfi.html

[T12] Kotlin：解构声明
来源：http://dali.sweek.top/Article/details/gt2hglgaexh.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangdashe.top/Article/details/gt2ttssbvka.html

[T13] Kotlin：只读 Map
来源：http://dali.gaohongyu789.top/Article/details/gt2lbjbiynj.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gt2stymffgc.html

[T14] Kotlin：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qfwxqbuq.html

for (i in 1..10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gt2jxnykbmv.html

[T15] Kotlin：接口
来源：http://dali.aibaodan.cn/Article/details/gt2wuiewlgs.html

interface Shape { fun area(): Double }
来源：http://dali.andypj.xyz/Article/details/gt2nbgpoeej.html

[T16] Swift：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2fgrzersv.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gt2xhaftqdt.html

[T17] Swift：变量与常量
来源：http://dali.sysykeji.top/Article/details/gt2uwoptdqd.html

var a = 1;  let b = 2
来源：http://dali.gotoacloud.top/Article/details/gt2lpjxdvkm.html

[T18] Swift：字符串插值
来源：http://dali.cucudq.cn/Article/details/gt2dcnzetxc.html

"值: \(b)"
来源：http://dali.guowangkeji.top/Article/details/gt2nucaurmm.html

[T19] Swift：可选绑定
来源：http://dali.nanxinkj.top/Article/details/gt2zvnrrikb.html

if let n = opt { print(n) }
来源：http://dali.xinyue.icu/Article/details/gt2seurxvxw.html

[T20] Swift：数组操作
来源：http://dali.zhengqikj.top/Article/details/gt2yjshspnf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.quarkkingdee.top/Article/details/gt2lolbrwlu.html

[T21] Swift：遍历
来源：http://dali.jyoumei.cn/Article/details/gt2cjjnluuz.html

for x in a { print(x) }
来源：http://dali.chenzaomai.com/Article/details/gt2elorcllr.html

[T22] Swift：字典
来源：http://dali.fzhhl.top/Article/details/gt2krkrwzqy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2hmhzioog.html

[T23] Swift：函数
来源：http://dali.gzhubu.top/Article/details/gt2qkvtcvcv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gt2kzacirti.html

[T24] Swift：闭包
来源：http://dali.sufxvd.cn/Article/details/gt2zwtqyyeo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fwrmffra.html

[T25] Swift：结构体
来源：http://dali.chenzaomai.com/Article/details/gt2hrszofnd.html

struct P { var x: Int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wzrkejrr.html

[T26] Swift：类与重写
来源：http://dali.chenlongwang.top/Article/details/gt2dflkgejj.html

class A: Base { override func f() {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wzlxqfpq.html

[T27] Swift：错误处理
来源：http://dali.hfpthk.cn/Article/details/gt2rvbjkzfq.html

do { try f() } catch { print(error) }
来源：http://dali.redwolf501.top/Article/details/gt2rjzecfzs.html

[T28] Swift：枚举
来源：http://dali.ydzc1.top/Article/details/gt2hypgllud.html

enum Color { case red, green }
来源：http://dali.haohaochexian.top/Article/details/gt2afsvllsb.html

[T29] Swift：guard 提前返回
来源：http://dali.pycfn.com/Article/details/gt2iirtgwna.html

guard let x = opt else { return }
来源：http://dali.cheryme.top/Article/details/gt2cqztsrur.html

[T30] Swift：协议
来源：http://dali.yuanzhike.top/Article/details/gt2zmururzy.html

protocol Shape { func area() -> Double }
来源：http://dali.havefunace.top/Article/details/gt2mshbzcju.html

[T31] Lua：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2lnejvbev.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gt2xdwcjtli.html

[T32] Lua：局部变量
来源：http://dali.ybcxt.top/Article/details/gt2szpnjegn.html

local a = 1
来源：http://dali.ehwqpu.com/Article/details/gt2zxbuktjt.html

[T33] Lua：表（数组）
来源：http://dali.cucudq.cn/Article/details/gt2mfvkexhk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yueranfly.top/Article/details/gt2cvtlodsc.html

[T34] Lua：遍历表
来源：http://dali.havefunace.top/Article/details/gt2awwjxfne.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.fzhhl.top/Article/details/gt2xcxuvvom.html

[T35] Lua：字典表
来源：http://dali.tian-w.cn/Article/details/gt2iwiwchhe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.birdmap.top/Article/details/gt2tmnbzdzd.html

[T36] Lua：函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2oqulhfuw.html

function add(a, b) return a + b end
来源：http://dali.yj20258.top/Article/details/gt2qtcbcgch.html

[T37] Lua：字符串拼接
来源：http://dali.tian-w.cn/Article/details/gt2qnabpgjt.html

"a" .. "b"
来源：http://dali.cashguo.top/Article/details/gt2gcwbzjac.html

[T38] Lua：条件
来源：http://dali.cashguo.top/Article/details/gt2vqiblndp.html

if x > 0 then print("正") end
来源：http://dali.svipenyu.cn/Article/details/gt2odxodfbg.html

[T39] Lua：模式匹配
来源：http://dali.yj20258888.top/Article/details/gt2wehtghne.html

string.find(s, "%d+")
来源：http://dali.zycfv.cn/Article/details/gt2hghdfcck.html

[T40] Lua：元表
来源：http://dali.tian-w.cn/Article/details/gt2jprklbrn.html

setmetatable({}, { __index = base })
来源：http://dali.havefunace.top/Article/details/gt2cfenpwyf.html

[T41] Perl：Hello World
来源：http://dali.ivvv.top/Article/details/gt2aniqzgdl.html

print "Hello\n";
来源：http://dali.haohaochexian.top/Article/details/gt2uynplezr.html

[T42] Perl：变量类型
来源：http://dali.yvedp.cn/Article/details/gt2iffykmab.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2jabnxrwb.html

[T43] Perl：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gt2ewlieozd.html

"值: $a"
来源：http://dali.zhixingplan.top/Article/details/gt2nrsdkfdq.html

[T44] Perl：条件
来源：http://dali.ppjwa.cn/Article/details/gt2xnqbswry.html

if ($a > 0) { print "正"; }
来源：http://dali.dashuyun.cn/Article/details/gt2bicepuoo.html

[T45] Perl：数组遍历
来源：http://dali.shzxlz.cn/Article/details/gt2urrnrjvo.html

for my $x (@arr) { print $x; }
来源：http://dali.gaohongyu789.top/Article/details/gt2qwxpzibt.html

[T46] Perl：哈希操作
来源：http://dali.feifeiyinyue.top/Article/details/gt2atoxfczu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.wangdashe.top/Article/details/gt2idntgcch.html

[T47] Perl：正则捕获
来源：http://dali.smart0.xyz/Article/details/gt2itcayrus.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tian-w.cn/Article/details/gt2ouitzwvx.html

[T48] Perl：正则替换
来源：http://dali.gotoacloud.top/Article/details/gt2qjgzwixf.html

$s =~ s/old/new/g;
来源：http://dali.kuanghao11.cn/Article/details/gt2jagskayc.html

[T49] Perl：函数
来源：http://dali.yvedp.cn/Article/details/gt2vvuianpt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gt2llgfnbns.html

[T50] Perl：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gt2bvtfgftg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigfzy.top/Article/details/gt2gxjvyiyk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.aibaodan.cn/Article/details/gt2nbtzkvgk.html

[T51] Scala：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2galtvpwx.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gt2pxuvxxpa.html

[T52] Scala：变量
来源：http://dali.yangfankeji.com/Article/details/gt2vhtfkruc.html

val a = 1;  var b = 2
来源：http://dali.havefunace.top/Article/details/gt2gnozeyxw.html

[T53] Scala：字符串插值
来源：http://dali.tian-w.cn/Article/details/gt2sbjugvrr.html

s"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gt2oecqzusq.html

[T54] Scala：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gt2xffqzios.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dashuyun.cn/Article/details/gt2fecoqcmd.html

[T55] Scala：集合过滤
来源：http://dali.bjfxy.top/Article/details/gt2lgknjzsc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hywenlv.cn/Article/details/gt2aglqhqyx.html

[T56] Scala：样例类
来源：http://dali.jiagoushi.top/Article/details/gt2acfbchby.html

case class User(name: String, age: Int)
来源：http://dali.svipenyu.cn/Article/details/gt2lkcdnpyq.html

[T57] Scala：模式匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2qgxfmnce.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.birdmap.top/Article/details/gt2ivxqvfir.html

[T58] Scala：函数定义
来源：http://dali.dianchejie.cn/Article/details/gt2pzcsoqpb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cdnleiting.top/Article/details/gt2ivamdmlb.html

[T59] Scala：循环
来源：http://dali.birdmap.top/Article/details/gt2yyzldufv.html

for (i <- 1 to 10) println(i)
来源：http://dali.sufxvd.cn/Article/details/gt2dlbsuyqo.html

[T60] Scala：折叠
来源：http://dali.yonumen.top/Article/details/gt2qeqajaui.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.snrcjt.cn/Article/details/gt2tumjzkve.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2xcyrmqyh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhengqikj.top/Article/details/gt2yjdxkqjt.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2sapcsaud.html

[U01] Py：创建虚拟环境
来源：http://dali.aizwys.cn/Article/details/gt2ltkfwyzm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cashguo.top/Article/details/gt2bhzvggbz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yuxming.cn/Article/details/gt2zygovtzo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gsnunies.html

[U03] Py：加载 .env 配置
来源：http://dali.yuanzhike.top/Article/details/gt2tzjwdgmp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj202588.top/Article/details/gt2opaqpfgc.html

[U04] Py：变量调试打印
来源：http://dali.hnqzz.top/Article/details/gt2wnwkvcvn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yuanzhike.top/Article/details/gt2gsqumyqk.html

[U05] Py：列表去重且保序
来源：http://dali.dianchejie.cn/Article/details/gt2xcsyfuoj.html

list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2scrsvstj.html

[U06] Py：合并两个字典
来源：http://dali.gaohongyu789.top/Article/details/gt2ewwmtsey.html

{**a, **b}
来源：http://dali.dashuyun.cn/Article/details/gt2iscjlbsr.html

[U07] Py：反转字典键值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qvtgdcdn.html

{v: k for k, v in d.items()}
来源：http://dali.jinqigufen.top/Article/details/gt2ylhdponz.html

[U08] Py：展平二维列表
来源：http://dali.gzhubu.top/Article/details/gt2qnntinrp.html

[y for x in nested for y in x]
来源：http://dali.chenlongwang.top/Article/details/gt2ombzsjcs.html

[U09] Py：字典取最大值的键
来源：http://dali.birdmap.top/Article/details/gt2vznmwwkb.html

max(d, key=d.get)
来源：http://dali.zhoulong.xyz/Article/details/gt2dmxqzxax.html

[U10] Py：按值排序字典
来源：http://dali.zhoulong.xyz/Article/details/gt2svzibcbb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ivvv.top/Article/details/gt2qifplvop.html

[U11] Py：生成器表达式
来源：http://dali.ehwqpu.com/Article/details/gt2anqctsud.html

(x * 2 for x in arr)
来源：http://dali.nwbrower.top/Article/details/gt2luykqwtq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nanxuanxn.top/Article/details/gt2ueiloacs.html

Counter(arr).most_common(3)
来源：http://dali.aibaodan.cn/Article/details/gt2eoabjuwp.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ncuvjymb.html

deque(maxlen=10)
来源：http://dali.andypj.xyz/Article/details/gt2oplmtdyl.html

[U14] Py：分组收集到列表
来源：http://dali.haohaochexian.top/Article/details/gt2qnzviaou.html

defaultdict(list)
来源：http://dali.zhixingplan.top/Article/details/gt2pmuytxex.html

[U15] Py：高精度计时
来源：http://dali.cucudq.cn/Article/details/gt2thobdpbv.html

t = time.perf_counter()
来源：http://dali.yongpay.top/Article/details/gt2monabokm.html

[U16] Py：命令行参数解析
来源：http://dali.zhoulong.xyz/Article/details/gt2cvnuwjvo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.iojbl.cn/Article/details/gt2nvbxvnok.html

[U17] Py：初始化日志
来源：http://dali.zhongyouzk.top/Article/details/gt2qybcmxun.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.vqdsnc.cn/Article/details/gt2tjdwhwxb.html

[U18] Py：预编译正则
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jltenxpj.html

pat = re.compile(r"\d+")
来源：http://dali.redwolf501.top/Article/details/gt2pkogrvse.html

[U19] Py：正则替换带回调
来源：http://dali.nwbrower.top/Article/details/gt2rtroeppc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.fzhhl.top/Article/details/gt2oxeowqly.html

[U20] Py：缓存函数结果
来源：http://dali.shzxlz.cn/Article/details/gt2tqjyiaba.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhoulong.xyz/Article/details/gt2ppczdzfo.html

[U21] Py：自定义上下文管理器
来源：http://dali.aibaodan.cn/Article/details/gt2kddbvojo.html

@contextlib.contextmanager
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezylcitl.html

[U22] Py：矩阵转置
来源：http://dali.snrcjt.cn/Article/details/gt2axxipqku.html

list(zip(*m))
来源：http://dali.guowangkeji.top/Article/details/gt2osqulaea.html

[U23] Py：分块读取大文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjfuibyv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hnxiangtu.top/Article/details/gt2fnzblcap.html

[U24] Py：路径操作
来源：http://dali.havefunace.top/Article/details/gt2blpllrdi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.haohaochexian.top/Article/details/gt2vntiqofz.html

[U25] Py：CSV 按字典读
来源：http://dali.sweek.top/Article/details/gt2jkfaonag.html

csv.DictReader(f)
来源：http://dali.fengsongda.top/Article/details/gt2jyjamoph.html

[U26] Py：并发下载
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fyeegvwh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kncxgpbz.html

[U27] Py：异步 HTTP
来源：http://dali.jinqigufen.top/Article/details/gt2yfgburci.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.dianchejie.cn/Article/details/gt2wkstdpcw.html

[U28] Py：类型别名
来源：http://dali.shangyingyoupin.top/Article/details/gt2cqrfrlxv.html

UserId = int
来源：http://dali.yongpay.top/Article/details/gt2rkolmksi.html

[U29] Py：属性校验
来源：http://dali.yangfankeji.com/Article/details/gt2biasqcny.html

@property 与 @x.setter 配合
来源：http://dali.sysykeji.top/Article/details/gt2qaearcxi.html

[U30] Py：数据类
来源：http://dali.yj202588.top/Article/details/gt2wmbnhptv.html

@dataclass(slots=True)
来源：http://dali.iojbl.cn/Article/details/gt2hfsbclhw.html

[U31] Py：单测
来源：http://dali.tian-w.cn/Article/details/gt2vzvdixim.html

python -m pytest -q
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tqpwlkxt.html

[U32] Py：代码格式化
来源：http://dali.jlsjyb.cn/Article/details/gt2jiwvtefq.html

ruff format . && ruff check --fix .
来源：http://dali.dianchejie.cn/Article/details/gt2xnvbbyci.html

[U33] Py：打包发布
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2agggimap.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xuanzx.com/Article/details/gt2yqamxhpc.html

[U34] Py：判断编码
来源：http://dali.fengsongda.top/Article/details/gt2oohamtjd.html

chardet.detect(raw)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ltlgbtkf.html

[U35] Py：发送邮件
来源：http://dali.yj20258888.top/Article/details/gt2khcepfum.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sufxvd.cn/Article/details/gt2sqockcam.html

[U36] Py：定时任务
来源：http://dali.316326.xyz/Article/details/gt2cvukgpyt.html

schedule.every(10).minutes.do(job)
来源：http://dali.hysaishi.cn/Article/details/gt2zttjmuzy.html

[U37] Py：读写 Excel
来源：http://dali.hnxiangtu.top/Article/details/gt2dcvufdup.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhixingplan.top/Article/details/gt2wdxvlopf.html

[U38] Py：获取脚本所在目录
来源：http://dali.birdmap.top/Article/details/gt2kablcfng.html

Path(__file__).resolve().parent
来源：http://dali.shuidangran.top/Article/details/gt2uucqcmms.html

[U39] Py：判断是否在交互环境
来源：http://dali.0kj1m.cn/Article/details/gt2hyfhoyvw.html

sys.stdout.isatty()
来源：http://dali.dianchejie.cn/Article/details/gt2akxmasxq.html

[U40] Py：打印到标准错误
来源：http://dali.jyoumei.cn/Article/details/gt2byhdhgjb.html

print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gt2gzslrcdo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.bjfxy.top/Article/details/gt2bhfffssa.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cheryme.top/Article/details/gt2wplukarp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xuetiantiany.cn/Article/details/gt2jlolhkfe.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yangfankeji.com/Article/details/gt2nlztkzwx.html

[U43] PHP：声明命名空间
来源：http://dali.zdqjudy.top/Article/details/gt2sgnkdfdk.html

namespace App\Http;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ykovyluk.html

[U44] PHP：开启严格类型
来源：http://dali.andypj.xyz/Article/details/gt2gymxvpkt.html

declare(strict_types=1);
来源：http://dali.hnqzz.top/Article/details/gt2vwallizc.html


<!-- 参考信息 -->