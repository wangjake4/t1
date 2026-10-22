代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.andypj.xyz/Article/details/gt2aukbwvuq.html

[S21] C：字符类别判断
来源：http://dali.guowangkeji.top/Article/details/gt2avkfxgqi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sxryk.cn/Article/details/gt2sovfyxkh.html

[S22] C：字符串转数字
来源：http://dali.zhongyouzk.top/Article/details/gt2xlodvaxa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.meibo888.top/Article/details/gt2hwufgcgd.html

[S23] C：随机数
来源：http://dali.yonumen.top/Article/details/gt2lacttson.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hncmwsud.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gt2bfksacor.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2atbcsxwm.html

[S25] C：内存拷贝
来源：http://dali.zdqjudy.top/Article/details/gt2akmkqaiw.html

memcpy(dst, src, n);
来源：http://dali.aizwys.cn/Article/details/gt2krvbrrle.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gt2kzqtoxvb.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gt2xdzbrxoq.html

[S27] C：定义常量
来源：http://dali.yanxiufei.cn/Article/details/gt2ootarrls.html

const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gt2bnbsadtt.html

[S28] C：静态变量
来源：http://dali.zhongyouzk.top/Article/details/gt2csnbwgtj.html

static int counter = 0;
来源：http://dali.sysykeji.top/Article/details/gt2rfcpydon.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gt2szyyioxa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zdqjudy.top/Article/details/gt2fgzpluwb.html

[S30] C：头文件保护
来源：http://dali.aizwys.cn/Article/details/gt2svmpcajx.html

#ifndef X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqrjqqjf.html

#define X_H
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rzrdgmxn.html

#endif
来源：http://dali.tanke756.top/Article/details/gt2gyeghmkv.html

[S31] C++：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2ishndduh.html

#include <iostream>
来源：http://dali.jianghu66.top/Article/details/gt2isjbcrvv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zdqjudy.top/Article/details/gt2hnrslebg.html

[S32] C++：字符串
来源：http://dali.fzhhl.top/Article/details/gt2vovcqixx.html

std::string s = "hi";  s += "!";
来源：http://dali.yvedp.cn/Article/details/gt2maiqaato.html

[S33] C++：vector 增删
来源：http://dali.jyoumei.cn/Article/details/gt2axawigcm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yongpay.top/Article/details/gt2vmydxaod.html

[S34] C++：遍历 vector
来源：http://dali.zhengqikj.top/Article/details/gt2htypjdwi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shuidangran.top/Article/details/gt2cwdryjuo.html

[S35] C++：map
来源：http://dali.xziqi.cn/Article/details/gt2kcfigchw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gt2btugricb.html

[S36] C++：unordered_map
来源：http://dali.yangfankeji.com/Article/details/gt2ajpwcscp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2hdauhrqe.html

[S37] C++：set
来源：http://dali.quarkkingdee.top/Article/details/gt2ndxyyvro.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gt2zuxldliu.html

[S38] C++：排序
来源：http://dali.birdmap.top/Article/details/gt2oalovhxf.html

std::sort(v.begin(), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gt2endnermf.html

[S39] C++：自定义比较器排序
来源：http://dali.yueranfly.top/Article/details/gt2zvrouulq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gt2yjzjjxdm.html

[S40] C++：查找元素
来源：http://dali.nwbrower.top/Article/details/gt2uyrqdetv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sysykeji.top/Article/details/gt2yxjeaofi.html

[S41] C++：类与构造函数
来源：http://dali.xziqi.cn/Article/details/gt2svreishn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gt2nbilxfti.html

[S42] C++：继承与虚函数
来源：http://dali.gogol.net.cn/Article/details/gt2rqguqbyx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhengqikj.top/Article/details/gt2ekkrxqag.html

[S43] C++：智能指针
来源：http://dali.zhongyouzk.top/Article/details/gt2uefenzqa.html

auto p = std::make_unique<int>(5);
来源：http://dali.tianlin.xyz/Article/details/gt2unayjgms.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gt2oldkntkd.html

void inc(int &x) { ++x; }
来源：http://dali.xinyue.icu/Article/details/gt2lunzvjjw.html

[S45] C++：lambda
来源：http://dali.iojbl.cn/Article/details/gt2bvvvqmyj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qgdgflau.html

[S46] C++：函数模板
来源：http://dali.jinqigfzy.top/Article/details/gt2oxnrilec.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tian-w.cn/Article/details/gt2ywokmpxm.html

[S47] C++：结构化绑定遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2rrupqsof.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ppjwa.cn/Article/details/gt2npcojfar.html

[S48] C++：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2ejneulhy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tanke756.top/Article/details/gt2ykcipywb.html

while (std::getline(in, line)) { }
来源：http://dali.zhixingplan.top/Article/details/gt2sezhkrkf.html

[S49] C++：写文件
来源：http://dali.c1oappe.top/Article/details/gt2ilpykrkn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2algzrjtr.html

[S50] C++：格式化数字
来源：http://dali.yvedp.cn/Article/details/gt2skgltlqj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gt2euppwlcl.html

[S51] C++：显式类型转换
来源：http://dali.yvedp.cn/Article/details/gt2xioameop.html

static_cast<double>(a) / b
来源：http://dali.quarkkingdee.top/Article/details/gt2zejsyaqi.html

[S52] C++：const 与 noexcept
来源：http://dali.chenjidiqi.icu/Article/details/gt2eonchxuc.html

int size() const noexcept { return n_; }
来源：http://dali.ppjwa.cn/Article/details/gt2vmccjayw.html

[S53] C++：移动语义
来源：http://dali.jiagoushi.top/Article/details/gt2rrffmkua.html

std::vector<int> w = std::move(v);
来源：http://dali.zhongyouzk.top/Article/details/gt2nsnpwbog.html

[S54] C++：异常处理
来源：http://dali.jlsjyb.cn/Article/details/gt2seuvvtgc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.birdmap.top/Article/details/gt2dkobfult.html

[S55] C++：结构化绑定
来源：http://dali.yangfankeji.com/Article/details/gt2zfxpwvag.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mlkqhrys.html

[S56] C++：optional
来源：http://dali.ydzc1.top/Article/details/gt2rgzaexwu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.quarkkingdee.top/Article/details/gt2nhulvbnd.html

[S57] C++：编译期常量
来源：http://dali.xuanzx.com/Article/details/gt2iwslurgv.html

constexpr int N = 10;
来源：http://dali.xylfe.cn/Article/details/gt2qvrrghid.html

[S58] C++：命名空间
来源：http://dali.316326.xyz/Article/details/gt2clxkjnzl.html

namespace ns { int f() { return 1; } }
来源：http://dali.cheryme.top/Article/details/gt2lmwmcibh.html

[S59] C++：静态断言
来源：http://dali.gogol.net.cn/Article/details/gt2rwwvzgmw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangdashe.top/Article/details/gt2abxbeati.html

[S60] C++：遍历并删除元素
来源：http://dali.quarkkingdee.top/Article/details/gt2jzhgtshi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xziqi.cn/Article/details/gt2oirqtcyi.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2owgybfjj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tanke756.top/Article/details/gt2cuhqfode.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2emvqaxng.html

[T01] Kotlin：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2jufovoby.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gt2dlzzbpog.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gt2pzcxvbyq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gaohongyu789.top/Article/details/gt2wbbgklac.html

[T03] Kotlin：字符串模板
来源：http://dali.hammf.cn/Article/details/gt2birmtpwv.html

"值: $b"
来源：http://dali.cucudq.cn/Article/details/gt2evkrrlnl.html

[T04] Kotlin：空安全
来源：http://dali.nanxinkj.top/Article/details/gt2njvykjuz.html

val n: String? = null;  n?.length
来源：http://dali.redwolf501.top/Article/details/gt2vsgwkgly.html

[T05] Kotlin：when 表达式
来源：http://dali.mhx1999.top/Article/details/gt2eqlbuanj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hfpthk.cn/Article/details/gt2swaiiiqk.html

[T06] Kotlin：集合映射
来源：http://dali.chenlongwang.top/Article/details/gt2gwnkrhnj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2szojehaj.html

[T07] Kotlin：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gt2jmedsjey.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258.top/Article/details/gt2mmwxwhfo.html

[T08] Kotlin：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mzqliuku.html

data class User(val name: String, val age: Int)
来源：http://dali.zycfv.cn/Article/details/gt2cphadlok.html

[T09] Kotlin：扩展函数
来源：http://dali.nwbrower.top/Article/details/gt2wlpejioh.html

fun String.exclaim() = this + "!"
来源：http://dali.tian-w.cn/Article/details/gt2ygrlqbwy.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigufen.top/Article/details/gt2fuhzmjhv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cucudq.cn/Article/details/gt2dmhgydem.html

[T11] Kotlin：协程
来源：http://dali.chenlongwang.top/Article/details/gt2vashqhbz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guannengcc.top/Article/details/gt2vebnbrxo.html

[T12] Kotlin：解构声明
来源：http://dali.xziqi.cn/Article/details/gt2lhrgxjkx.html

val (a, b) = Pair(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2faxgsnxu.html

[T13] Kotlin：只读 Map
来源：http://dali.yj202588.top/Article/details/gt2ogwwbjln.html

val m = mapOf("a" to 1)
来源：http://dali.zdqjudy.top/Article/details/gt2xmylivdq.html

[T14] Kotlin：循环
来源：http://dali.dianchejie.cn/Article/details/gt2gttmlgwq.html

for (i in 1..10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gt2eypejwni.html

[T15] Kotlin：接口
来源：http://dali.yvedp.cn/Article/details/gt2gaoytyuv.html

interface Shape { fun area(): Double }
来源：http://dali.redwolf501.top/Article/details/gt2waxditvz.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yknsjgab.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gt2imrxtbkn.html

[T17] Swift：变量与常量
来源：http://dali.xuanzx.com/Article/details/gt2ttvzekje.html

var a = 1;  let b = 2
来源：http://dali.andypj.xyz/Article/details/gt2hchtyaiu.html

[T18] Swift：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cqzhuvjq.html

"值: \(b)"
来源：http://dali.zhixingplan.top/Article/details/gt2kihlwqqx.html

[T19] Swift：可选绑定
来源：http://dali.chenjidiqi.icu/Article/details/gt2lfjbgnvf.html

if let n = opt { print(n) }
来源：http://dali.bjfxy.top/Article/details/gt2kcjfgqkr.html

[T20] Swift：数组操作
来源：http://dali.jqgufenzy.top/Article/details/gt2qpmvyrlf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yueranfly.top/Article/details/gt2guidumbt.html

[T21] Swift：遍历
来源：http://dali.hfpthk.cn/Article/details/gt2mpubdjfl.html

for x in a { print(x) }
来源：http://dali.aizwys.cn/Article/details/gt2znkvofsc.html

[T22] Swift：字典
来源：http://dali.havefunace.top/Article/details/gt2bttnsdhr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shuidangran.top/Article/details/gt2xflgzpzr.html

[T23] Swift：函数
来源：http://dali.zhixingplan.top/Article/details/gt2ssqbchfx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gaohongyu789.top/Article/details/gt2dufzcgai.html

[T24] Swift：闭包
来源：http://dali.zycfv.cn/Article/details/gt2vwqoptfb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2otopimfu.html

[T25] Swift：结构体
来源：http://dali.zhoulong.xyz/Article/details/gt2uyyrypkw.html

struct P { var x: Int }
来源：http://dali.zhixingplan.top/Article/details/gt2rfrzllrm.html

[T26] Swift：类与重写
来源：http://dali.zhiwuduotai.top/Article/details/gt2lijfyxht.html

class A: Base { override func f() {} }
来源：http://dali.gaohongyu789.top/Article/details/gt2teunzeei.html

[T27] Swift：错误处理
来源：http://dali.svipenyu.cn/Article/details/gt2vzreoyru.html

do { try f() } catch { print(error) }
来源：http://dali.sxryk.cn/Article/details/gt2fsocrjty.html

[T28] Swift：枚举
来源：http://dali.hnqzz.top/Article/details/gt2xjrsxqdu.html

enum Color { case red, green }
来源：http://dali.ydzc1.top/Article/details/gt2jgyskpvv.html

[T29] Swift：guard 提前返回
来源：http://dali.yangfankeji.com/Article/details/gt2fvkqhrkn.html

guard let x = opt else { return }
来源：http://dali.quarkkingdee.top/Article/details/gt2atrtlhmp.html

[T30] Swift：协议
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahrzjjjy.html

protocol Shape { func area() -> Double }
来源：http://dali.havefunace.top/Article/details/gt2ilygnpmo.html

[T31] Lua：Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2uqpepves.html

print("Hello")
来源：http://dali.ivvv.top/Article/details/gt2dnngasjc.html

[T32] Lua：局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2kdynyzec.html

local a = 1
来源：http://dali.vqdsnc.cn/Article/details/gt2dvmkgidy.html

[T33] Lua：表（数组）
来源：http://dali.hongshengwenyu.top/Article/details/gt2mpkljptj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xinyue.icu/Article/details/gt2yphwhsqa.html

[T34] Lua：遍历表
来源：http://dali.mhx1999.top/Article/details/gt2qmhptzrn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxuanxn.top/Article/details/gt2jdnftddo.html

[T35] Lua：字典表
来源：http://dali.mhx1999.top/Article/details/gt2dfdvttvp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xylfe.cn/Article/details/gt2csgauhbr.html

[T36] Lua：函数
来源：http://dali.fengsongda.top/Article/details/gt2ujpzsfyz.html

function add(a, b) return a + b end
来源：http://dali.316326.xyz/Article/details/gt2tlrwcvhn.html

[T37] Lua：字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gt2jxjlqtqi.html

"a" .. "b"
来源：http://dali.cheryme.top/Article/details/gt2vtiznnbr.html

[T38] Lua：条件
来源：http://dali.ehwqpu.com/Article/details/gt2thkjqizw.html

if x > 0 then print("正") end
来源：http://dali.xuanzx.com/Article/details/gt2uvjmtlps.html

[T39] Lua：模式匹配
来源：http://dali.birdmap.top/Article/details/gt2jxfsdgwd.html

string.find(s, "%d+")
来源：http://dali.aibaodan.cn/Article/details/gt2pwefvwhr.html

[T40] Lua：元表
来源：http://dali.chenjidiqi.icu/Article/details/gt2xjgpycnu.html

setmetatable({}, { __index = base })
来源：http://dali.svipenyu.cn/Article/details/gt2jrudcegd.html

[T41] Perl：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2avotchjj.html

print "Hello\n";
来源：http://dali.jqgufenzy.top/Article/details/gt2mjlnvrms.html

[T42] Perl：变量类型
来源：http://dali.tianlin.xyz/Article/details/gt2qwievltf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xinyue.icu/Article/details/gt2rrfdjtqi.html

[T43] Perl：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gt2gwwlktsg.html

"值: $a"
来源：http://dali.cucudq.cn/Article/details/gt2gfdtzjzu.html

[T44] Perl：条件
来源：http://dali.ybcxt.top/Article/details/gt2tdsuowtg.html

if ($a > 0) { print "正"; }
来源：http://dali.bjfxy.top/Article/details/gt2zwedttok.html

[T45] Perl：数组遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2ncrbjmgs.html

for my $x (@arr) { print $x; }
来源：http://dali.havefunace.top/Article/details/gt2xcocahgc.html

[T46] Perl：哈希操作
来源：http://dali.9152youxi.cn/Article/details/gt2iyumwlua.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.havefunace.top/Article/details/gt2giniywym.html

[T47] Perl：正则捕获
来源：http://dali.xuanzx.com/Article/details/gt2zxqeknst.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.havefunace.top/Article/details/gt2jjkglhye.html

[T48] Perl：正则替换
来源：http://dali.bjfxy.top/Article/details/gt2rumezput.html

$s =~ s/old/new/g;
来源：http://dali.yj20258888.top/Article/details/gt2yxgkoqdn.html

[T49] Perl：函数
来源：http://dali.xziqi.cn/Article/details/gt2xkgmrigh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gt2hqajnvsj.html

[T50] Perl：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gt2ahbjtegv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.fzhhl.top/Article/details/gt2mvgpnkzw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hywenlv.cn/Article/details/gt2fibuscqi.html

[T51] Scala：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2vcbhyevm.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gt2sieusgbn.html

[T52] Scala：变量
来源：http://dali.yongpay.top/Article/details/gt2svmkuzhf.html

val a = 1;  var b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aocgaqmw.html

[T53] Scala：字符串插值
来源：http://dali.sweek.top/Article/details/gt2nnvxsolk.html

s"值: $b"
来源：http://dali.hnqzz.top/Article/details/gt2dcavxlaj.html

[T54] Scala：集合映射
来源：http://dali.havefunace.top/Article/details/gt2iabyxrcw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nwkyoytj.html

[T55] Scala：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gt2bvkvbcde.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jqgfzy.top/Article/details/gt2nhjxdnly.html

[T56] Scala：样例类
来源：http://dali.zdqjudy.top/Article/details/gt2nijfpxww.html

case class User(name: String, age: Int)
来源：http://dali.tianlin.xyz/Article/details/gt2ceebbxdz.html

[T57] Scala：模式匹配
来源：http://dali.yj20258.top/Article/details/gt2bbqusjsw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258888.top/Article/details/gt2gsaovikt.html

[T58] Scala：函数定义
来源：http://dali.fzhhl.top/Article/details/gt2keolsjjz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yceznfnt.html

[T59] Scala：循环
来源：http://dali.hnxiangtu.top/Article/details/gt2kjcfrilf.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2txozswhc.html

[T60] Scala：折叠
来源：http://dali.xinyue.icu/Article/details/gt2zrzdyfyi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gqbicwwt.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2wylmyxsw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.mhx1999.top/Article/details/gt2sdcpeuwl.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2eubynnyi.html

[U01] Py：创建虚拟环境
来源：http://dali.pycfn.com/Article/details/gt2thrzetbz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aibaodan.cn/Article/details/gt2colnptpc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.c1oappe.top/Article/details/gt2vnjqctcf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cqqwz.cn/Article/details/gt2yowhogdf.html

[U03] Py：加载 .env 配置
来源：http://dali.xinyue.icu/Article/details/gt2yxxfcwxn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhoulong.xyz/Article/details/gt2xydijzgz.html

[U04] Py：变量调试打印
来源：http://dali.birdmap.top/Article/details/gt2qtycoptn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.daria6918.cn/Article/details/gt2rrhdemlp.html

[U05] Py：列表去重且保序
来源：http://dali.nanxuanxn.top/Article/details/gt2eyfqjspn.html

list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yrvgodzu.html

[U06] Py：合并两个字典
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqnylbce.html

{**a, **b}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipnaxsen.html

[U07] Py：反转字典键值
来源：http://dali.pengpengdd.cyou/Article/details/gt2wllexhxn.html

{v: k for k, v in d.items()}
来源：http://dali.shangyingyoupin.top/Article/details/gt2rabxvvvf.html

[U08] Py：展平二维列表
来源：http://dali.zhiwuduotai.top/Article/details/gt2yvyifxhx.html

[y for x in nested for y in x]
来源：http://dali.hnxiangtu.top/Article/details/gt2rqhkqkvf.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgufenzy.top/Article/details/gt2meeblprv.html

max(d, key=d.get)
来源：http://dali.mhx1999.top/Article/details/gt2qdgidxvz.html

[U10] Py：按值排序字典
来源：http://dali.yj202588.top/Article/details/gt2eldjukiq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ydzc1.top/Article/details/gt2zvfexrdc.html

[U11] Py：生成器表达式
来源：http://dali.tanke756.top/Article/details/gt2doqnalxq.html

(x * 2 for x in arr)
来源：http://dali.xinyue.icu/Article/details/gt2tzzgrxoa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tianlin.xyz/Article/details/gt2frqikfby.html

Counter(arr).most_common(3)
来源：http://dali.chenlongwang.top/Article/details/gt2fmwffctn.html

[U13] Py：固定长度队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ndghdesh.html

deque(maxlen=10)
来源：http://dali.guowangkeji.top/Article/details/gt2qkztlwuu.html

[U14] Py：分组收集到列表
来源：http://dali.jqgufenzy.top/Article/details/gt2wbpziuzw.html

defaultdict(list)
来源：http://dali.gzhubu.top/Article/details/gt2ocvznkui.html

[U15] Py：高精度计时
来源：http://dali.xinyue.icu/Article/details/gt2ezxpsabr.html

t = time.perf_counter()
来源：http://dali.jqgufenzy.top/Article/details/gt2lvwpesgo.html

[U16] Py：命令行参数解析
来源：http://dali.kuanghao11.cn/Article/details/gt2dpkwrzii.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.quarkkingdee.top/Article/details/gt2dbfzxvdx.html

[U17] Py：初始化日志
来源：http://dali.aizwys.cn/Article/details/gt2duhkgcex.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqodkccz.html

[U18] Py：预编译正则
来源：http://dali.nanxinkj.top/Article/details/gt2nmgbbosz.html

pat = re.compile(r"\d+")
来源：http://dali.guannengcc.top/Article/details/gt2brhessjp.html

[U19] Py：正则替换带回调
来源：http://dali.hammf.cn/Article/details/gt2tmhkpati.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sxryk.cn/Article/details/gt2siuaxhuz.html

[U20] Py：缓存函数结果
来源：http://dali.0kj1m.cn/Article/details/gt2muvyyual.html

@functools.lru_cache(maxsize=None)
来源：http://dali.fzhhl.top/Article/details/gt2jmwmywmt.html

[U21] Py：自定义上下文管理器
来源：http://dali.ehwqpu.com/Article/details/gt2rrunhbbz.html

@contextlib.contextmanager
来源：http://dali.feifeiyinyue.top/Article/details/gt2uodwacuk.html

[U22] Py：矩阵转置
来源：http://dali.yuanzhike.top/Article/details/gt2rbpdwosr.html

list(zip(*m))
来源：http://dali.shuidangran.top/Article/details/gt2sktmpyqy.html

[U23] Py：分块读取大文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2mwhqxuud.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.wangshuangyany.cn/Article/details/gt2kvzfjpgv.html

[U24] Py：路径操作
来源：http://dali.tanke756.top/Article/details/gt2ihrthqsd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cashguo.top/Article/details/gt2nipzzgef.html

[U25] Py：CSV 按字典读
来源：http://dali.xuetiantiany.cn/Article/details/gt2vcrohyih.html

csv.DictReader(f)
来源：http://dali.yj20258888.top/Article/details/gt2jjtscqdf.html

[U26] Py：并发下载
来源：http://dali.wangdashe.top/Article/details/gt2hozwknjg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.dianchejie.cn/Article/details/gt2lipqdipa.html

[U27] Py：异步 HTTP
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2elrushqf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xziqi.cn/Article/details/gt2fqbkqhdc.html

[U28] Py：类型别名
来源：http://dali.zhiwuduotai.top/Article/details/gt2ttutnjbf.html

UserId = int
来源：http://dali.wangshuangyany.cn/Article/details/gt2usmgxdmh.html

[U29] Py：属性校验
来源：http://dali.zhongyouzk.top/Article/details/gt2fdkbndkz.html

@property 与 @x.setter 配合
来源：http://dali.gaohongyu789.top/Article/details/gt2bznavzhv.html

[U30] Py：数据类
来源：http://dali.kuanghao11.cn/Article/details/gt2khamgkfc.html

@dataclass(slots=True)
来源：http://dali.zhongyouzk.top/Article/details/gt2tucgqfrw.html

[U31] Py：单测
来源：http://dali.daxiang520.top/Article/details/gt2qiulpbvv.html

python -m pytest -q
来源：http://dali.dashuyun.cn/Article/details/gt2rnblzlug.html

[U32] Py：代码格式化
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrdqkftb.html

ruff format . && ruff check --fix .
来源：http://dali.zhengqikj.top/Article/details/gt2pgnrpawh.html

[U33] Py：打包发布
来源：http://dali.nanxuanxn.top/Article/details/gt2xjlthqpo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cucudq.cn/Article/details/gt2mhrzrpqc.html

[U34] Py：判断编码
来源：http://dali.yueranfly.top/Article/details/gt2xxvprwkj.html

chardet.detect(raw)
来源：http://dali.tian-w.cn/Article/details/gt2jmxlduif.html

[U35] Py：发送邮件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2skpxxlzz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zdqjudy.top/Article/details/gt2npqstlgf.html

[U36] Py：定时任务
来源：http://dali.xylfe.cn/Article/details/gt2lylzdxan.html

schedule.every(10).minutes.do(job)
来源：http://dali.fengsongda.top/Article/details/gt2omqeoinp.html

[U37] Py：读写 Excel
来源：http://dali.c1oappe.top/Article/details/gt2mdefmpbd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhixingplan.top/Article/details/gt2hxhvpime.html

[U38] Py：获取脚本所在目录
来源：http://dali.hnxiangtu.top/Article/details/gt2wsgstuaa.html

Path(__file__).resolve().parent
来源：http://dali.hammf.cn/Article/details/gt2srccpmjm.html

[U39] Py：判断是否在交互环境
来源：http://dali.sysykeji.top/Article/details/gt2hzoaqzyg.html

sys.stdout.isatty()
来源：http://dali.hnxiangtu.top/Article/details/gt2fjprojfc.html

[U40] Py：打印到标准错误
来源：http://dali.shangyingyoupin.top/Article/details/gt2cilrwtkj.html

print("err", file=sys.stderr)
来源：http://dali.jinqigfzy.top/Article/details/gt2vrhmqant.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.feifeiyinyue.top/Article/details/gt2vylkmvht.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhoulong.xyz/Article/details/gt2kdgqbdfs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ppjwa.cn/Article/details/gt2elswywri.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.vqdsnc.cn/Article/details/gt2oogxgilu.html

[U43] PHP：声明命名空间
来源：http://dali.316326.xyz/Article/details/gt2qktxnghd.html

namespace App\Http;
来源：http://dali.guowangkeji.top/Article/details/gt2phjyylfl.html

[U44] PHP：开启严格类型
来源：http://dali.meibo888.top/Article/details/gt2daperifh.html

declare(strict_types=1);
来源：http://dali.yonumen.top/Article/details/gt2kzxjsplp.html


<!-- 参考信息 -->