代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gt2gytzpmvt.html

[S21] C：字符类别判断
来源：http://dali.hammf.cn/Article/details/gt2isvkhtqk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ydzc1.top/Article/details/gt2ebujjrko.html

[S22] C：字符串转数字
来源：http://dali.redwolf501.top/Article/details/gt2gpdavnqk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgfzy.top/Article/details/gt2kciktgbf.html

[S23] C：随机数
来源：http://dali.9152youxi.cn/Article/details/gt2ucgwjvlw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yktdemcf.html

[S24] C：获取本地时间
来源：http://dali.snrcjt.cn/Article/details/gt2jbhklsah.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangshuangyany.cn/Article/details/gt2whrwpeqh.html

[S25] C：内存拷贝
来源：http://dali.jinqigufen.top/Article/details/gt2qqtbpfmq.html

memcpy(dst, src, n);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vtvywnoe.html

[S26] C：内存清零
来源：http://dali.ydzc1.top/Article/details/gt2shidarax.html

memset(a, 0, sizeof a);
来源：http://dali.yj202588.top/Article/details/gt2anhcotml.html

[S27] C：定义常量
来源：http://dali.guowangkeji.top/Article/details/gt2jsytgzwj.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gt2bijmfuvo.html

[S28] C：静态变量
来源：http://dali.jinqigfzy.top/Article/details/gt2bgdqnhgz.html

static int counter = 0;
来源：http://dali.cdnleiting.top/Article/details/gt2mlfhrqyo.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2eythsjhe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yvedp.cn/Article/details/gt2oxstaudc.html

[S30] C：头文件保护
来源：http://dali.aizwys.cn/Article/details/gt2sybullqo.html

#ifndef X_H
来源：http://dali.c1oappe.top/Article/details/gt2kgsqsbax.html

#define X_H
来源：http://dali.chenjidiqi.icu/Article/details/gt2ytgcsxhn.html

#endif
来源：http://dali.chenjidiqi.icu/Article/details/gt2yysfufxi.html

[S31] C++：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2lttlxwue.html

#include <iostream>
来源：http://dali.hywenlv.cn/Article/details/gt2jmobixfj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2zzxuhfzr.html

[S32] C++：字符串
来源：http://dali.zycfv.cn/Article/details/gt2vchyyayf.html

std::string s = "hi";  s += "!";
来源：http://dali.pengpengdd.cyou/Article/details/gt2pmmcklai.html

[S33] C++：vector 增删
来源：http://dali.tian-w.cn/Article/details/gt2cdysylqc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2gsyjgayu.html

[S34] C++：遍历 vector
来源：http://dali.andypj.xyz/Article/details/gt2diljmvdg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jianghu66.top/Article/details/gt2qyyogyvj.html

[S35] C++：map
来源：http://dali.hywenlv.cn/Article/details/gt2zizoayfy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gt2vzyxaufv.html

[S36] C++：unordered_map
来源：http://dali.jyoumei.cn/Article/details/gt2kybnirgv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2hugehtpe.html

[S37] C++：set
来源：http://dali.hysaishi.cn/Article/details/gt2jxlmkplr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2inzsbnhv.html

[S38] C++：排序
来源：http://dali.shuidangran.top/Article/details/gt2pqhycciw.html

std::sort(v.begin(), v.end());
来源：http://dali.yangfankeji.com/Article/details/gt2wqafoyst.html

[S39] C++：自定义比较器排序
来源：http://dali.smart0.xyz/Article/details/gt2euwzmutg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yueranfly.top/Article/details/gt2wyhihcdw.html

[S40] C++：查找元素
来源：http://dali.dianchejie.cn/Article/details/gt2wyozfxxm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2xaurobrn.html

[S41] C++：类与构造函数
来源：http://dali.tanke756.top/Article/details/gt2taiatyvz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.316326.xyz/Article/details/gt2dotekquw.html

[S42] C++：继承与虚函数
来源：http://dali.kuanghao11.cn/Article/details/gt2rsagyudj.html

class B : public Base { public: void f() override {} };
来源：http://dali.gzhubu.top/Article/details/gt2jvqnpgas.html

[S43] C++：智能指针
来源：http://dali.hfpthk.cn/Article/details/gt2hbawingl.html

auto p = std::make_unique<int>(5);
来源：http://dali.mhx1999.top/Article/details/gt2dwsklhfh.html

[S44] C++：引用传参
来源：http://dali.yj202588.top/Article/details/gt2ortqavgd.html

void inc(int &x) { ++x; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tzeisawc.html

[S45] C++：lambda
来源：http://dali.ivvv.top/Article/details/gt2mqctqwhq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zdqjudy.top/Article/details/gt2xdkbfwkm.html

[S46] C++：函数模板
来源：http://dali.daria6918.cn/Article/details/gt2eakutlfr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.snrcjt.cn/Article/details/gt2gxaxeibd.html

[S47] C++：结构化绑定遍历
来源：http://dali.tianlin.xyz/Article/details/gt2iltqipia.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.smart0.xyz/Article/details/gt2eshnnkea.html

[S48] C++：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gt2mvqizutc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.mhx1999.top/Article/details/gt2livwjmep.html

while (std::getline(in, line)) { }
来源：http://dali.fzhhl.top/Article/details/gt2deaqadvf.html

[S49] C++：写文件
来源：http://dali.gaohongyu789.top/Article/details/gt2wyyploxv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kijtxerb.html

[S50] C++：格式化数字
来源：http://dali.gotoacloud.top/Article/details/gt2hfucntye.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gt2sbedblki.html

[S51] C++：显式类型转换
来源：http://dali.chenlongwang.top/Article/details/gt2riuoueoe.html

static_cast<double>(a) / b
来源：http://dali.nwbrower.top/Article/details/gt2ospwfcfk.html

[S52] C++：const 与 noexcept
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fnecqdxp.html

int size() const noexcept { return n_; }
来源：http://dali.xylfe.cn/Article/details/gt2anmdzynk.html

[S53] C++：移动语义
来源：http://dali.jinqigfzy.top/Article/details/gt2bjwnwjal.html

std::vector<int> w = std::move(v);
来源：http://dali.hysaishi.cn/Article/details/gt2bjjniqjx.html

[S54] C++：异常处理
来源：http://dali.xylfe.cn/Article/details/gt2pzslqhip.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258.top/Article/details/gt2lvaydqnw.html

[S55] C++：结构化绑定
来源：http://dali.zhixingplan.top/Article/details/gt2qpnnwjxm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ppjwa.cn/Article/details/gt2aqztfcjc.html

[S56] C++：optional
来源：http://dali.jqgfzy.top/Article/details/gt2paabgzrw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sufxvd.cn/Article/details/gt2btrvadlq.html

[S57] C++：编译期常量
来源：http://dali.9152youxi.cn/Article/details/gt2jhhfeevm.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gt2xuwmqiko.html

[S58] C++：命名空间
来源：http://dali.shzxlz.cn/Article/details/gt2yyzqdqhd.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxinkj.top/Article/details/gt2jdxyecfh.html

[S59] C++：静态断言
来源：http://dali.gotoacloud.top/Article/details/gt2smotvnse.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yueranfly.top/Article/details/gt2cajrchcz.html

[S60] C++：遍历并删除元素
来源：http://dali.shuidangran.top/Article/details/gt2trqtjgcm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gt2yxwtpltq.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2rviefitn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gt2ldudewup.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2qfddzvul.html

[T01] Kotlin：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2isdmqura.html

println("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gt2rsgrbrdv.html

[T02] Kotlin：变量
来源：http://dali.aibaodan.cn/Article/details/gt2soquuaaq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.quarkkingdee.top/Article/details/gt2dvyletcv.html

[T03] Kotlin：字符串模板
来源：http://dali.yueranfly.top/Article/details/gt2geymzdvw.html

"值: $b"
来源：http://dali.yuxming.cn/Article/details/gt2puhyibrk.html

[T04] Kotlin：空安全
来源：http://dali.svipenyu.cn/Article/details/gt2szpzjmyl.html

val n: String? = null;  n?.length
来源：http://dali.nanxinkj.top/Article/details/gt2qxuyjjye.html

[T05] Kotlin：when 表达式
来源：http://dali.sufxvd.cn/Article/details/gt2hzoppgxp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ydzc1.top/Article/details/gt2eqbgzlat.html

[T06] Kotlin：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gt2csstvbue.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuxming.cn/Article/details/gt2pqdvpcii.html

[T07] Kotlin：集合过滤
来源：http://dali.xziqi.cn/Article/details/gt2orthdnkt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.iojbl.cn/Article/details/gt2sdqedyyf.html

[T08] Kotlin：数据类
来源：http://dali.cqqwz.cn/Article/details/gt2ihkgqaqo.html

data class User(val name: String, val age: Int)
来源：http://dali.yangfankeji.com/Article/details/gt2lezjkhej.html

[T09] Kotlin：扩展函数
来源：http://dali.dianchejie.cn/Article/details/gt2klmezoxc.html

fun String.exclaim() = this + "!"
来源：http://dali.cqqwz.cn/Article/details/gt2sprawrve.html

[T10] Kotlin：默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2saodyxyf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shuidangran.top/Article/details/gt2tlztlmxd.html

[T11] Kotlin：协程
来源：http://dali.yangfankeji.com/Article/details/gt2udwrotqa.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jyoumei.cn/Article/details/gt2auwknxnz.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258888.top/Article/details/gt2vhuhxidd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2grdmijgj.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gt2qzovyylk.html

val m = mapOf("a" to 1)
来源：http://dali.ydzc1.top/Article/details/gt2ntkmdwhy.html

[T14] Kotlin：循环
来源：http://dali.yangfankeji.com/Article/details/gt2kcavfmff.html

for (i in 1..10) println(i)
来源：http://dali.redwolf501.top/Article/details/gt2ieljeyet.html

[T15] Kotlin：接口
来源：http://dali.316326.xyz/Article/details/gt2jmosyzzt.html

interface Shape { fun area(): Double }
来源：http://dali.shzxlz.cn/Article/details/gt2vwvduaah.html

[T16] Swift：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2awxgyfic.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gt2tmrignlx.html

[T17] Swift：变量与常量
来源：http://dali.yj20258.top/Article/details/gt2zuvbbknn.html

var a = 1;  let b = 2
来源：http://dali.sysykeji.top/Article/details/gt2jxvjlchm.html

[T18] Swift：字符串插值
来源：http://dali.yj20258888.top/Article/details/gt2wqvooeek.html

"值: \(b)"
来源：http://dali.yj20258888.top/Article/details/gt2njbxkrug.html

[T19] Swift：可选绑定
来源：http://dali.pycfn.com/Article/details/gt2ixhbnufw.html

if let n = opt { print(n) }
来源：http://dali.iojbl.cn/Article/details/gt2lruldcxg.html

[T20] Swift：数组操作
来源：http://dali.xylfe.cn/Article/details/gt2coyprwxf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.guowangkeji.top/Article/details/gt2knilbmhw.html

[T21] Swift：遍历
来源：http://dali.hfpthk.cn/Article/details/gt2mncbfcxn.html

for x in a { print(x) }
来源：http://dali.jianghu66.top/Article/details/gt2ejvgzafm.html

[T22] Swift：字典
来源：http://dali.dianchejie.cn/Article/details/gt2hhkpteol.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.c1oappe.top/Article/details/gt2zkabixfq.html

[T23] Swift：函数
来源：http://dali.zhixingplan.top/Article/details/gt2dedlbzvl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yongpay.top/Article/details/gt2jbngkwoe.html

[T24] Swift：闭包
来源：http://dali.sysykeji.top/Article/details/gt2yblifkle.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yvedp.cn/Article/details/gt2aiozfffp.html

[T25] Swift：结构体
来源：http://dali.ivvv.top/Article/details/gt2gwxndrvt.html

struct P { var x: Int }
来源：http://dali.nanxuanxn.top/Article/details/gt2ykvyucya.html

[T26] Swift：类与重写
来源：http://dali.haohaochexian.top/Article/details/gt2qvponyup.html

class A: Base { override func f() {} }
来源：http://dali.yj20258888.top/Article/details/gt2rxbfxabz.html

[T27] Swift：错误处理
来源：http://dali.jiagoushi.top/Article/details/gt2fdrdhmbj.html

do { try f() } catch { print(error) }
来源：http://dali.chenzaomai.com/Article/details/gt2kvsnjmto.html

[T28] Swift：枚举
来源：http://dali.cashguo.top/Article/details/gt2rttqxwqr.html

enum Color { case red, green }
来源：http://dali.wangdashe.top/Article/details/gt2dunbchxl.html

[T29] Swift：guard 提前返回
来源：http://dali.shuidangran.top/Article/details/gt2mysjnxov.html

guard let x = opt else { return }
来源：http://dali.mhx1999.top/Article/details/gt2gdastaip.html

[T30] Swift：协议
来源：http://dali.jinqigfzy.top/Article/details/gt2ffmugzib.html

protocol Shape { func area() -> Double }
来源：http://dali.mhx1999.top/Article/details/gt2mijdqzpl.html

[T31] Lua：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2fezvmtom.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rgavantu.html

[T32] Lua：局部变量
来源：http://dali.cdnleiting.top/Article/details/gt2durgdaii.html

local a = 1
来源：http://dali.jianghu66.top/Article/details/gt2zgzceizw.html

[T33] Lua：表（数组）
来源：http://dali.yonumen.top/Article/details/gt2yljfvtys.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sysykeji.top/Article/details/gt2tcygwwja.html

[T34] Lua：遍历表
来源：http://dali.nanxinkj.top/Article/details/gt2efmwsbgg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ngwyylwt.html

[T35] Lua：字典表
来源：http://dali.aibaodan.cn/Article/details/gt2lkxiuhax.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hfpthk.cn/Article/details/gt2jvjsidpa.html

[T36] Lua：函数
来源：http://dali.zhengqikj.top/Article/details/gt2lzmamvjj.html

function add(a, b) return a + b end
来源：http://dali.nanxinkj.top/Article/details/gt2cnmentan.html

[T37] Lua：字符串拼接
来源：http://dali.316326.xyz/Article/details/gt2sxawybfq.html

"a" .. "b"
来源：http://dali.gogol.net.cn/Article/details/gt2xxujjjqw.html

[T38] Lua：条件
来源：http://dali.gaohongyu789.top/Article/details/gt2udqgunla.html

if x > 0 then print("正") end
来源：http://dali.jiagoushi.top/Article/details/gt2mybjgscn.html

[T39] Lua：模式匹配
来源：http://dali.jinqigufen.top/Article/details/gt2yoskratf.html

string.find(s, "%d+")
来源：http://dali.birdmap.top/Article/details/gt2iwkdljqh.html

[T40] Lua：元表
来源：http://dali.nanxuanxn.top/Article/details/gt2ccgoaouh.html

setmetatable({}, { __index = base })
来源：http://dali.pengpengdd.cyou/Article/details/gt2xusdnxzv.html

[T41] Perl：Hello World
来源：http://dali.yongpay.top/Article/details/gt2tucsuyzp.html

print "Hello\n";
来源：http://dali.yonumen.top/Article/details/gt2vcgzdnia.html

[T42] Perl：变量类型
来源：http://dali.nanxinkj.top/Article/details/gt2ehftskdj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.smart0.xyz/Article/details/gt2trszmmvr.html

[T43] Perl：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gt2bfddaqjk.html

"值: $a"
来源：http://dali.jqgfzy.top/Article/details/gt2uswwktll.html

[T44] Perl：条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2rsxzgdzo.html

if ($a > 0) { print "正"; }
来源：http://dali.ydzc1.top/Article/details/gt2cffqjijw.html

[T45] Perl：数组遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2wopejpuy.html

for my $x (@arr) { print $x; }
来源：http://dali.cucudq.cn/Article/details/gt2ckjfygzw.html

[T46] Perl：哈希操作
来源：http://dali.316326.xyz/Article/details/gt2qxmcjmbl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ivvv.top/Article/details/gt2xlixqggd.html

[T47] Perl：正则捕获
来源：http://dali.haohaochexian.top/Article/details/gt2zwlqdgax.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rheibrou.html

[T48] Perl：正则替换
来源：http://dali.chenzaomai.com/Article/details/gt2mwjehfys.html

$s =~ s/old/new/g;
来源：http://dali.hnxiangtu.top/Article/details/gt2ueijvdgb.html

[T49] Perl：函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2uxpmadpn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uzhqddhb.html

[T50] Perl：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gt2knhldjax.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenlongwang.top/Article/details/gt2jbvaziwq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fengsongda.top/Article/details/gt2jphlxfrs.html

[T51] Scala：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nqyezine.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gt2spdjszoc.html

[T52] Scala：变量
来源：http://dali.cdnleiting.top/Article/details/gt2oupvfxez.html

val a = 1;  var b = 2
来源：http://dali.vqdsnc.cn/Article/details/gt2xfcdjizj.html

[T53] Scala：字符串插值
来源：http://dali.daxiang520.top/Article/details/gt2widiygyu.html

s"值: $b"
来源：http://dali.havefunace.top/Article/details/gt2ccjtvhik.html

[T54] Scala：集合映射
来源：http://dali.hywenlv.cn/Article/details/gt2vuowjvxq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.pycfn.com/Article/details/gt2ycjrubfk.html

[T55] Scala：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gt2vqiznqcn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.iojbl.cn/Article/details/gt2kjepfzsq.html

[T56] Scala：样例类
来源：http://dali.andypj.xyz/Article/details/gt2ugqzudcc.html

case class User(name: String, age: Int)
来源：http://dali.pycfn.com/Article/details/gt2oyoqyhwj.html

[T57] Scala：模式匹配
来源：http://dali.bjfxy.top/Article/details/gt2alhghuht.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.fengsongda.top/Article/details/gt2wcterbri.html

[T58] Scala：函数定义
来源：http://dali.kuanghao11.cn/Article/details/gt2navqhxpa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ehwqpu.com/Article/details/gt2rxxpbfbz.html

[T59] Scala：循环
来源：http://dali.zdqjudy.top/Article/details/gt2uxepvibz.html

for (i <- 1 to 10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2niygltsr.html

[T60] Scala：折叠
来源：http://dali.andypj.xyz/Article/details/gt2vbebaaty.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yvedp.cn/Article/details/gt2vaptnaeg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2encougau.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhengqikj.top/Article/details/gt2ehtqbatu.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2xmeqrfoz.html

[U01] Py：创建虚拟环境
来源：http://dali.sweek.top/Article/details/gt2lnrqyefy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.vqdsnc.cn/Article/details/gt2qzryvasq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.daria6918.cn/Article/details/gt2tbjdfuws.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.316326.xyz/Article/details/gt2gqhezitk.html

[U03] Py：加载 .env 配置
来源：http://dali.havefunace.top/Article/details/gt2chvwklti.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.meibo888.top/Article/details/gt2aqsyajnc.html

[U04] Py：变量调试打印
来源：http://dali.snrcjt.cn/Article/details/gt2becbsvzy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jqgfzy.top/Article/details/gt2bshuixmf.html

[U05] Py：列表去重且保序
来源：http://dali.nanxuanxn.top/Article/details/gt2bzcukfvb.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gt2zlczteuk.html

[U06] Py：合并两个字典
来源：http://dali.wangshuangyany.cn/Article/details/gt2cwodjpni.html

{**a, **b}
来源：http://dali.jinqigfzy.top/Article/details/gt2hltzqlgn.html

[U07] Py：反转字典键值
来源：http://dali.jyoumei.cn/Article/details/gt2awqjthlx.html

{v: k for k, v in d.items()}
来源：http://dali.aizwys.cn/Article/details/gt2cetdhsev.html

[U08] Py：展平二维列表
来源：http://dali.zhiwuduotai.top/Article/details/gt2vqnfabqt.html

[y for x in nested for y in x]
来源：http://dali.svipenyu.cn/Article/details/gt2yygrlfbv.html

[U09] Py：字典取最大值的键
来源：http://dali.xinyue.icu/Article/details/gt2huyghsid.html

max(d, key=d.get)
来源：http://dali.meibo888.top/Article/details/gt2wddqjnjw.html

[U10] Py：按值排序字典
来源：http://dali.mhx1999.top/Article/details/gt2prpasaok.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hysaishi.cn/Article/details/gt2fcvmiptx.html

[U11] Py：生成器表达式
来源：http://dali.zhoulong.xyz/Article/details/gt2cxvajorh.html

(x * 2 for x in arr)
来源：http://dali.mhx1999.top/Article/details/gt2txvbspmg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tian-w.cn/Article/details/gt2cdxgnuhc.html

Counter(arr).most_common(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2edrrnnmt.html

[U13] Py：固定长度队列
来源：http://dali.nanxinkj.top/Article/details/gt2eyaezgfr.html

deque(maxlen=10)
来源：http://dali.cheryme.top/Article/details/gt2aramxfab.html

[U14] Py：分组收集到列表
来源：http://dali.gzhubu.top/Article/details/gt2emdomiec.html

defaultdict(list)
来源：http://dali.dianchejie.cn/Article/details/gt2nrcnxaeo.html

[U15] Py：高精度计时
来源：http://dali.zycfv.cn/Article/details/gt2govibxdi.html

t = time.perf_counter()
来源：http://dali.havefunace.top/Article/details/gt2qgkdoeng.html

[U16] Py：命令行参数解析
来源：http://dali.cucudq.cn/Article/details/gt2olwposhk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shangyingyoupin.top/Article/details/gt2wuidfeei.html

[U17] Py：初始化日志
来源：http://dali.hfpthk.cn/Article/details/gt2fjyuqmfp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ybcxt.top/Article/details/gt2urjbwwpo.html

[U18] Py：预编译正则
来源：http://dali.daria6918.cn/Article/details/gt2ecizwsms.html

pat = re.compile(r"\d+")
来源：http://dali.hysaishi.cn/Article/details/gt2wefcbljd.html

[U19] Py：正则替换带回调
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wgwxhurg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.0kj1m.cn/Article/details/gt2hmtgpenr.html

[U20] Py：缓存函数结果
来源：http://dali.pycfn.com/Article/details/gt2rwmbenqo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ppjwa.cn/Article/details/gt2qzwmdlpj.html

[U21] Py：自定义上下文管理器
来源：http://dali.aizwys.cn/Article/details/gt2rvvbaalw.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrsiwfu.html

[U22] Py：矩阵转置
来源：http://dali.hfpthk.cn/Article/details/gt2erzjrbys.html

list(zip(*m))
来源：http://dali.guannengcc.top/Article/details/gt2iamqxegy.html

[U23] Py：分块读取大文件
来源：http://dali.hnqzz.top/Article/details/gt2ldovdrcy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tian-w.cn/Article/details/gt2bjgbugqx.html

[U24] Py：路径操作
来源：http://dali.cheryme.top/Article/details/gt2dgfdmmln.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gt2jitmzjgv.html

[U25] Py：CSV 按字典读
来源：http://dali.dashuyun.cn/Article/details/gt2lvjstydq.html

csv.DictReader(f)
来源：http://dali.jinqigufen.top/Article/details/gt2yrdnsgex.html

[U26] Py：并发下载
来源：http://dali.316326.xyz/Article/details/gt2ewaopgqn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gogol.net.cn/Article/details/gt2ebsemsdy.html

[U27] Py：异步 HTTP
来源：http://dali.jlsjyb.cn/Article/details/gt2lvbazlln.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.daxiang520.top/Article/details/gt2mrgtaixs.html

[U28] Py：类型别名
来源：http://dali.nanxinkj.top/Article/details/gt2qlbvitgp.html

UserId = int
来源：http://dali.gzhubu.top/Article/details/gt2abinlrnd.html

[U29] Py：属性校验
来源：http://dali.kuanghao11.cn/Article/details/gt2timuwioa.html

@property 与 @x.setter 配合
来源：http://dali.fengsongda.top/Article/details/gt2eazevcsd.html

[U30] Py：数据类
来源：http://dali.wangdashe.top/Article/details/gt2dxuxlomz.html

@dataclass(slots=True)
来源：http://dali.cashguo.top/Article/details/gt2lwpigosa.html

[U31] Py：单测
来源：http://dali.cqqwz.cn/Article/details/gt2skgefkvi.html

python -m pytest -q
来源：http://dali.sufxvd.cn/Article/details/gt2xgwhxnga.html

[U32] Py：代码格式化
来源：http://dali.guannengcc.top/Article/details/gt2uxuejtlw.html

ruff format . && ruff check --fix .
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kuytzimj.html

[U33] Py：打包发布
来源：http://dali.hywenlv.cn/Article/details/gt2nclkkrwm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gzhubu.top/Article/details/gt2mzszxtdl.html

[U34] Py：判断编码
来源：http://dali.sweek.top/Article/details/gt2cnlcndzi.html

chardet.detect(raw)
来源：http://dali.jiagoushi.top/Article/details/gt2dkhamvza.html

[U35] Py：发送邮件
来源：http://dali.zhoulong.xyz/Article/details/gt2yxxguhrv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.daria6918.cn/Article/details/gt2elzzkrrc.html

[U36] Py：定时任务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gbjvqlwu.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgfzy.top/Article/details/gt2ogmdrcxc.html

[U37] Py：读写 Excel
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pkfclmpb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcmgikp.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwfqiico.html

Path(__file__).resolve().parent
来源：http://dali.xuetiantiany.cn/Article/details/gt2lydwlwkp.html

[U39] Py：判断是否在交互环境
来源：http://dali.nanxuanxn.top/Article/details/gt2pgvbhhdi.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruadiyys.html

[U40] Py：打印到标准错误
来源：http://dali.xuetiantiany.cn/Article/details/gt2zwynmzyb.html

print("err", file=sys.stderr)
来源：http://dali.fzhhl.top/Article/details/gt2oljtgmxo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj20258888.top/Article/details/gt2hnckeitl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.vqdsnc.cn/Article/details/gt2htlseakp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yongpay.top/Article/details/gt2wrpnprei.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zdqjudy.top/Article/details/gt2nirjzucp.html

[U43] PHP：声明命名空间
来源：http://dali.jianghu66.top/Article/details/gt2aprlqbgk.html

namespace App\Http;
来源：http://dali.cqqwz.cn/Article/details/gt2rhjtkvtq.html

[U44] PHP：开启严格类型
来源：http://dali.ehwqpu.com/Article/details/gt2ieazkeki.html

declare(strict_types=1);
来源：http://dali.dashuyun.cn/Article/details/gt2bxfufwjb.html


<!-- 参考信息 -->