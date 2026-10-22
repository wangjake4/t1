代发 wailian999

int main(int argc, char **argv)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2prwyytpg.html

[S19] C：快速排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybkpcjrc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gt2poywrsnv.html

[S20] C：二分查找
来源：http://dali.yonumen.top/Article/details/gt2ffplfecd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gt2pojnsovx.html

[S21] C：字符类别判断
来源：http://dali.fengsongda.top/Article/details/gt2gyxdcsnb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gt2zyfivtej.html

[S22] C：字符串转数字
来源：http://dali.pycfn.com/Article/details/gt2svlouunr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gzhubu.top/Article/details/gt2pmhcpbdi.html

[S23] C：随机数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wohowlyp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ivvv.top/Article/details/gt2iinpehbb.html

[S24] C：获取本地时间
来源：http://dali.yuxming.cn/Article/details/gt2eovibzcz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sufxvd.cn/Article/details/gt2twfjzimx.html

[S25] C：内存拷贝
来源：http://dali.fengsongda.top/Article/details/gt2ddmihomx.html

memcpy(dst, src, n);
来源：http://dali.yongpay.top/Article/details/gt2guakwdgv.html

[S26] C：内存清零
来源：http://dali.jinqigufen.top/Article/details/gt2tbowhoui.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfcqmeo.html

[S27] C：定义常量
来源：http://dali.shuidangran.top/Article/details/gt2wheykpcb.html

const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gt2vtjruwxy.html

[S28] C：静态变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qcaieuxu.html

static int counter = 0;
来源：http://dali.hysaishi.cn/Article/details/gt2gwsxpyzc.html

[S29] C：变参函数
来源：http://dali.zhongyouzk.top/Article/details/gt2vvpdahql.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnxiangtu.top/Article/details/gt2laewoppp.html

[S30] C：头文件保护
来源：http://dali.gotoacloud.top/Article/details/gt2jxixzwtm.html

#ifndef X_H
来源：http://dali.svipenyu.cn/Article/details/gt2cziefenh.html

#define X_H
来源：http://dali.gzhubu.top/Article/details/gt2algmqcgh.html

#endif
来源：http://dali.dashuyun.cn/Article/details/gt2rhdmxxof.html

[S31] C++：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2xaapofda.html

#include <iostream>
来源：http://dali.yj20258888.top/Article/details/gt2enjxzpkc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ehwqpu.com/Article/details/gt2bdgrazyg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfecwqu.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgfzy.top/Article/details/gt2zxvzqsjl.html

[S33] C++：vector 增删
来源：http://dali.yuxming.cn/Article/details/gt2kkemklkc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.havefunace.top/Article/details/gt2bcsyfebi.html

[S34] C++：遍历 vector
来源：http://dali.chenlongwang.top/Article/details/gt2rtbnunfp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigufen.top/Article/details/gt2zwtnvhtg.html

[S35] C++：map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2atjgykmc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2ahnaevzd.html

[S36] C++：unordered_map
来源：http://dali.ybcxt.top/Article/details/gt2lqhtbwro.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2jcoxible.html

[S37] C++：set
来源：http://dali.quarkkingdee.top/Article/details/gt2pqgydqfy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcshvdsp.html

[S38] C++：排序
来源：http://dali.smart0.xyz/Article/details/gt2tjvhacom.html

std::sort(v.begin(), v.end());
来源：http://dali.dianchejie.cn/Article/details/gt2vtzyavdi.html

[S39] C++：自定义比较器排序
来源：http://dali.xinyue.icu/Article/details/gt2qqpasrxn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daria6918.cn/Article/details/gt2twjuowpj.html

[S40] C++：查找元素
来源：http://dali.cheryme.top/Article/details/gt2tyfxdugi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xylfe.cn/Article/details/gt2jibstfmh.html

[S41] C++：类与构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2giyydavz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aibaodan.cn/Article/details/gt2xijouxsh.html

[S42] C++：继承与虚函数
来源：http://dali.cucudq.cn/Article/details/gt2vehznjih.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgufenzy.top/Article/details/gt2lhnpsulb.html

[S43] C++：智能指针
来源：http://dali.nwbrower.top/Article/details/gt2hjglkvcf.html

auto p = std::make_unique<int>(5);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahfqfceu.html

[S44] C++：引用传参
来源：http://dali.sweek.top/Article/details/gt2mcetkfed.html

void inc(int &x) { ++x; }
来源：http://dali.pycfn.com/Article/details/gt2rucylrei.html

[S45] C++：lambda
来源：http://dali.hysaishi.cn/Article/details/gt2njokxkqf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.snrcjt.cn/Article/details/gt2fznzkfuv.html

[S46] C++：函数模板
来源：http://dali.jyoumei.cn/Article/details/gt2jiouswpg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zdqjudy.top/Article/details/gt2pkmdkrid.html

[S47] C++：结构化绑定遍历
来源：http://dali.cqqwz.cn/Article/details/gt2aqvwaszi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tianlin.xyz/Article/details/gt2lfuwgqvw.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvkbuahe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sysykeji.top/Article/details/gt2htrvvydw.html

while (std::getline(in, line)) { }
来源：http://dali.fzhhl.top/Article/details/gt2xrffmnwc.html

[S49] C++：写文件
来源：http://dali.yongpay.top/Article/details/gt2gvsdqqao.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bymwkodr.html

[S50] C++：格式化数字
来源：http://dali.ydzc1.top/Article/details/gt2owqsoeir.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gt2fgsmupgx.html

[S51] C++：显式类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2axqytkgd.html

static_cast<double>(a) / b
来源：http://dali.hnxiangtu.top/Article/details/gt2nfqofrda.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxinkj.top/Article/details/gt2mtbjnmru.html

int size() const noexcept { return n_; }
来源：http://dali.yonumen.top/Article/details/gt2fskaqvcf.html

[S53] C++：移动语义
来源：http://dali.pycfn.com/Article/details/gt2qttnmfnk.html

std::vector<int> w = std::move(v);
来源：http://dali.hysaishi.cn/Article/details/gt2yvqwwykd.html

[S54] C++：异常处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2yifurpbc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gt2nsiiwuev.html

[S55] C++：结构化绑定
来源：http://dali.aizwys.cn/Article/details/gt2pokpspfy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2eyehzgei.html

[S56] C++：optional
来源：http://dali.gotoacloud.top/Article/details/gt2thzbfppj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daxiang520.top/Article/details/gt2wecbeqvh.html

[S57] C++：编译期常量
来源：http://dali.cheryme.top/Article/details/gt2oivxhcrm.html

constexpr int N = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vgwtwlrv.html

[S58] C++：命名空间
来源：http://dali.gogol.net.cn/Article/details/gt2wtospocd.html

namespace ns { int f() { return 1; } }
来源：http://dali.gogol.net.cn/Article/details/gt2aqktgvnx.html

[S59] C++：静态断言
来源：http://dali.redwolf501.top/Article/details/gt2cosqzfuk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ehwqpu.com/Article/details/gt2wmzbuyze.html

[S60] C++：遍历并删除元素
来源：http://dali.cucudq.cn/Article/details/gt2sfrchuyz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xinyue.icu/Article/details/gt2ootvbqnc.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2yfoghxve.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gt2svvbxrix.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2tmfznokv.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mxrzegdz.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gt2gnrijwud.html

[T02] Kotlin：变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2lfhbbhnq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ehwqpu.com/Article/details/gt2dfqacdtc.html

[T03] Kotlin：字符串模板
来源：http://dali.hysaishi.cn/Article/details/gt2dimuknyx.html

"值: $b"
来源：http://dali.wangdashe.top/Article/details/gt2nciabchx.html

[T04] Kotlin：空安全
来源：http://dali.xziqi.cn/Article/details/gt2ykmsmqeb.html

val n: String? = null;  n?.length
来源：http://dali.jinqigfzy.top/Article/details/gt2icpevtrx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhengqikj.top/Article/details/gt2hlvvmfuc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yanxiufei.cn/Article/details/gt2takqfoag.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pusekrlc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fzhhl.top/Article/details/gt2gtwrfgja.html

[T07] Kotlin：集合过滤
来源：http://dali.xinyue.icu/Article/details/gt2ijkacgxo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuanzx.com/Article/details/gt2ffwmbael.html

[T08] Kotlin：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oeirzgql.html

data class User(val name: String, val age: Int)
来源：http://dali.zhengqikj.top/Article/details/gt2cqsmjcke.html

[T09] Kotlin：扩展函数
来源：http://dali.hnxiangtu.top/Article/details/gt2ituqehfb.html

fun String.exclaim() = this + "!"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bligtbll.html

[T10] Kotlin：默认参数
来源：http://dali.zhoulong.xyz/Article/details/gt2vaxmdxrb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ybcxt.top/Article/details/gt2dwsmmutq.html

[T11] Kotlin：协程
来源：http://dali.c1oappe.top/Article/details/gt2lvbqogwy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yueranfly.top/Article/details/gt2qhqvjept.html

[T12] Kotlin：解构声明
来源：http://dali.chenjidiqi.icu/Article/details/gt2howmeazo.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gt2jalmjiip.html

[T13] Kotlin：只读 Map
来源：http://dali.c1oappe.top/Article/details/gt2aqulckry.html

val m = mapOf("a" to 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mnwlzqap.html

[T14] Kotlin：循环
来源：http://dali.kuanghao11.cn/Article/details/gt2sxgilrhx.html

for (i in 1..10) println(i)
来源：http://dali.0kj1m.cn/Article/details/gt2noiqzxfn.html

[T15] Kotlin：接口
来源：http://dali.nwbrower.top/Article/details/gt2jsrwcpjm.html

interface Shape { fun area(): Double }
来源：http://dali.hnqzz.top/Article/details/gt2zdwgxbuj.html

[T16] Swift：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2qdccehlf.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gt2gtbowpqd.html

[T17] Swift：变量与常量
来源：http://dali.wangshuangyany.cn/Article/details/gt2tbkfixik.html

var a = 1;  let b = 2
来源：http://dali.dashuyun.cn/Article/details/gt2ijzwrglw.html

[T18] Swift：字符串插值
来源：http://dali.andypj.xyz/Article/details/gt2ygmdjxdm.html

"值: \(b)"
来源：http://dali.xuanzx.com/Article/details/gt2pkeyggwz.html

[T19] Swift：可选绑定
来源：http://dali.fengsongda.top/Article/details/gt2ujbuuena.html

if let n = opt { print(n) }
来源：http://dali.mhx1999.top/Article/details/gt2thbmnnlf.html

[T20] Swift：数组操作
来源：http://dali.redwolf501.top/Article/details/gt2vgfmhsra.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgfzy.top/Article/details/gt2ukrfhbtx.html

[T21] Swift：遍历
来源：http://dali.chenlongwang.top/Article/details/gt2yxdakqcc.html

for x in a { print(x) }
来源：http://dali.tian-w.cn/Article/details/gt2mhiwljut.html

[T22] Swift：字典
来源：http://dali.gogol.net.cn/Article/details/gt2crtkxadt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigufen.top/Article/details/gt2vhivclsr.html

[T23] Swift：函数
来源：http://dali.aibaodan.cn/Article/details/gt2xctezseu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nwbrower.top/Article/details/gt2amktnzmz.html

[T24] Swift：闭包
来源：http://dali.cdnleiting.top/Article/details/gt2ctqlvkwg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2rsldudel.html

[T25] Swift：结构体
来源：http://dali.nanxuanxn.top/Article/details/gt2gbgcaolx.html

struct P { var x: Int }
来源：http://dali.xuanzx.com/Article/details/gt2hqxrepwb.html

[T26] Swift：类与重写
来源：http://dali.hywenlv.cn/Article/details/gt2rkpznpcr.html

class A: Base { override func f() {} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xwzvymae.html

[T27] Swift：错误处理
来源：http://dali.nwbrower.top/Article/details/gt2fbqpyvcs.html

do { try f() } catch { print(error) }
来源：http://dali.ybcxt.top/Article/details/gt2pohgnbwq.html

[T28] Swift：枚举
来源：http://dali.yj20258.top/Article/details/gt2clsifoqm.html

enum Color { case red, green }
来源：http://dali.ivvv.top/Article/details/gt2mglrfros.html

[T29] Swift：guard 提前返回
来源：http://dali.redwolf501.top/Article/details/gt2cwxjxzpt.html

guard let x = opt else { return }
来源：http://dali.yongpay.top/Article/details/gt2bwnxhibi.html

[T30] Swift：协议
来源：http://dali.zhongyouzk.top/Article/details/gt2vzpdnilz.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxinkj.top/Article/details/gt2jlnpbshp.html

[T31] Lua：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2ikeecyxm.html

print("Hello")
来源：http://dali.zhengqikj.top/Article/details/gt2rlzyjfxf.html

[T32] Lua：局部变量
来源：http://dali.yj202588.top/Article/details/gt2wvmkjouj.html

local a = 1
来源：http://dali.chenlongwang.top/Article/details/gt2zqyozbwn.html

[T33] Lua：表（数组）
来源：http://dali.yuxming.cn/Article/details/gt2hcjgdqgy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cqqwz.cn/Article/details/gt2iwjbrtwh.html

[T34] Lua：遍历表
来源：http://dali.jyoumei.cn/Article/details/gt2csdmqeir.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yongpay.top/Article/details/gt2eoridiup.html

[T35] Lua：字典表
来源：http://dali.guannengcc.top/Article/details/gt2prfvfxqe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tianlin.xyz/Article/details/gt2jerdibqw.html

[T36] Lua：函数
来源：http://dali.wangdashe.top/Article/details/gt2zqdlpvrn.html

function add(a, b) return a + b end
来源：http://dali.ydzc1.top/Article/details/gt2kpnxacwo.html

[T37] Lua：字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gt2vhemvzmx.html

"a" .. "b"
来源：http://dali.hysaishi.cn/Article/details/gt2hxgcmzut.html

[T38] Lua：条件
来源：http://dali.jinqigfzy.top/Article/details/gt2otlplfle.html

if x > 0 then print("正") end
来源：http://dali.zhixingplan.top/Article/details/gt2qxmhwafi.html

[T39] Lua：模式匹配
来源：http://dali.aibaodan.cn/Article/details/gt2ejhjwmwr.html

string.find(s, "%d+")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zzqoazha.html

[T40] Lua：元表
来源：http://dali.kuanghao11.cn/Article/details/gt2ccewenax.html

setmetatable({}, { __index = base })
来源：http://dali.jqgufenzy.top/Article/details/gt2srzfezce.html

[T41] Perl：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shwaexcy.html

print "Hello\n";
来源：http://dali.cucudq.cn/Article/details/gt2yrkeiwoa.html

[T42] Perl：变量类型
来源：http://dali.mhx1999.top/Article/details/gt2biblhdjl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yubyphft.html

[T43] Perl：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gt2njfamubp.html

"值: $a"
来源：http://dali.zhiwuduotai.top/Article/details/gt2jltqngul.html

[T44] Perl：条件
来源：http://dali.hnxiangtu.top/Article/details/gt2eoosqklf.html

if ($a > 0) { print "正"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhauexny.html

[T45] Perl：数组遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2vofwelxv.html

for my $x (@arr) { print $x; }
来源：http://dali.zycfv.cn/Article/details/gt2enmfixlt.html

[T46] Perl：哈希操作
来源：http://dali.ppjwa.cn/Article/details/gt2hfuancas.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.9152youxi.cn/Article/details/gt2cfmlbipp.html

[T47] Perl：正则捕获
来源：http://dali.gaohongyu789.top/Article/details/gt2cxgzwznu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zycfv.cn/Article/details/gt2lowwwisr.html

[T48] Perl：正则替换
来源：http://dali.hnqzz.top/Article/details/gt2fyxswdwv.html

$s =~ s/old/new/g;
来源：http://dali.yongpay.top/Article/details/gt2yqygeutb.html

[T49] Perl：函数
来源：http://dali.daria6918.cn/Article/details/gt2mcbxwoxb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gt2lsrxdnbt.html

[T50] Perl：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gt2jyfzyqmk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cqqwz.cn/Article/details/gt2yiadatac.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yvedp.cn/Article/details/gt2kocrablb.html

[T51] Scala：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2rdljqvsa.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gt2vwpwlnka.html

[T52] Scala：变量
来源：http://dali.vqdsnc.cn/Article/details/gt2pwmpeedy.html

val a = 1;  var b = 2
来源：http://dali.yongpay.top/Article/details/gt2xqjgkksa.html

[T53] Scala：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gt2lhrwoxlx.html

s"值: $b"
来源：http://dali.cashguo.top/Article/details/gt2czsftiqb.html

[T54] Scala：集合映射
来源：http://dali.nanxinkj.top/Article/details/gt2nehmepwo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.redwolf501.top/Article/details/gt2fwbuqpoi.html

[T55] Scala：集合过滤
来源：http://dali.iojbl.cn/Article/details/gt2vzqfdbon.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aibaodan.cn/Article/details/gt2ywgxwtwa.html

[T56] Scala：样例类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zahdnvnh.html

case class User(name: String, age: Int)
来源：http://dali.daxiang520.top/Article/details/gt2gosihwqy.html

[T57] Scala：模式匹配
来源：http://dali.smart0.xyz/Article/details/gt2cvigadmg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhengqikj.top/Article/details/gt2kkjfkote.html

[T58] Scala：函数定义
来源：http://dali.yangfankeji.com/Article/details/gt2tqpymomb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhongyouzk.top/Article/details/gt2qwhfxcoa.html

[T59] Scala：循环
来源：http://dali.yuxming.cn/Article/details/gt2ypvalpmm.html

for (i <- 1 to 10) println(i)
来源：http://dali.ivvv.top/Article/details/gt2qonamekn.html

[T60] Scala：折叠
来源：http://dali.zhixingplan.top/Article/details/gt2yjdjovpn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.0kj1m.cn/Article/details/gt2alqkkyxx.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2wtzagmhw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gt2xipssiob.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2udwvnjmp.html

[U01] Py：创建虚拟环境
来源：http://dali.0kj1m.cn/Article/details/gt2moqyjcjq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.birdmap.top/Article/details/gt2awdljoue.html

[U02] Py：导出 / 安装依赖
来源：http://dali.c1oappe.top/Article/details/gt2ylyrddpg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yvedp.cn/Article/details/gt2venmdrhc.html

[U03] Py：加载 .env 配置
来源：http://dali.xylfe.cn/Article/details/gt2obibbvwd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.0kj1m.cn/Article/details/gt2wfimlnje.html

[U04] Py：变量调试打印
来源：http://dali.yj20258.top/Article/details/gt2ywtdfaaj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.quarkkingdee.top/Article/details/gt2uxjovlsw.html

[U05] Py：列表去重且保序
来源：http://dali.jiagoushi.top/Article/details/gt2gwfdktsm.html

list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gt2mjxpxhsm.html

[U06] Py：合并两个字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2styezqlm.html

{**a, **b}
来源：http://dali.hongshengwenyu.top/Article/details/gt2vusytmmn.html

[U07] Py：反转字典键值
来源：http://dali.cdnleiting.top/Article/details/gt2bvxttjij.html

{v: k for k, v in d.items()}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ngjlolnd.html

[U08] Py：展平二维列表
来源：http://dali.tanke756.top/Article/details/gt2ufcscabt.html

[y for x in nested for y in x]
来源：http://dali.cucudq.cn/Article/details/gt2slxbvgmf.html

[U09] Py：字典取最大值的键
来源：http://dali.xuetiantiany.cn/Article/details/gt2yfbbprds.html

max(d, key=d.get)
来源：http://dali.havefunace.top/Article/details/gt2tqlotphk.html

[U10] Py：按值排序字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imgmieew.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.snrcjt.cn/Article/details/gt2ogkonhuq.html

[U11] Py：生成器表达式
来源：http://dali.yongpay.top/Article/details/gt2kvlxjsbg.html

(x * 2 for x in arr)
来源：http://dali.tianlin.xyz/Article/details/gt2aikzojpe.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ehwqpu.com/Article/details/gt2jmbgqbhy.html

Counter(arr).most_common(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fzuixjua.html

[U13] Py：固定长度队列
来源：http://dali.xuanzx.com/Article/details/gt2nfwbjwvb.html

deque(maxlen=10)
来源：http://dali.jinqigfzy.top/Article/details/gt2dcatcdmr.html

[U14] Py：分组收集到列表
来源：http://dali.yongpay.top/Article/details/gt2yalgjzqj.html

defaultdict(list)
来源：http://dali.hnxiangtu.top/Article/details/gt2bkohgmpu.html

[U15] Py：高精度计时
来源：http://dali.zdqjudy.top/Article/details/gt2qemsodsn.html

t = time.perf_counter()
来源：http://dali.hfpthk.cn/Article/details/gt2ivuaswjc.html

[U16] Py：命令行参数解析
来源：http://dali.sufxvd.cn/Article/details/gt2lhnurlok.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gotoacloud.top/Article/details/gt2meuaxnaw.html

[U17] Py：初始化日志
来源：http://dali.hfpthk.cn/Article/details/gt2qmgesbch.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhixingplan.top/Article/details/gt2sjaejowm.html

[U18] Py：预编译正则
来源：http://dali.havefunace.top/Article/details/gt2bvxbgkvn.html

pat = re.compile(r"\d+")
来源：http://dali.daxiang520.top/Article/details/gt2pnkenaps.html

[U19] Py：正则替换带回调
来源：http://dali.zhiwuduotai.top/Article/details/gt2joezppvg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.birdmap.top/Article/details/gt2zomqcoie.html

[U20] Py：缓存函数结果
来源：http://dali.yj202588.top/Article/details/gt2dqlsjcfs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hammf.cn/Article/details/gt2valbrbqu.html

[U21] Py：自定义上下文管理器
来源：http://dali.dianchejie.cn/Article/details/gt2tlrcgcbm.html

@contextlib.contextmanager
来源：http://dali.tian-w.cn/Article/details/gt2jkzxypuf.html

[U22] Py：矩阵转置
来源：http://dali.yueranfly.top/Article/details/gt2oghrnhji.html

list(zip(*m))
来源：http://dali.yongpay.top/Article/details/gt2awrsrwhx.html

[U23] Py：分块读取大文件
来源：http://dali.ivvv.top/Article/details/gt2cabonovw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yongpay.top/Article/details/gt2gdbebbde.html

[U24] Py：路径操作
来源：http://dali.jinqigufen.top/Article/details/gt2feaayrdf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gt2vxiugcbu.html

[U25] Py：CSV 按字典读
来源：http://dali.gogol.net.cn/Article/details/gt2xjtfdxgn.html

csv.DictReader(f)
来源：http://dali.ivvv.top/Article/details/gt2kkozetmm.html

[U26] Py：并发下载
来源：http://dali.fengsongda.top/Article/details/gt2kjgyjdye.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ivvv.top/Article/details/gt2zrbfhrbi.html

[U27] Py：异步 HTTP
来源：http://dali.yonumen.top/Article/details/gt2khtwartn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zogquiay.html

[U28] Py：类型别名
来源：http://dali.zhengqikj.top/Article/details/gt2hwljeksv.html

UserId = int
来源：http://dali.yuanzhike.top/Article/details/gt2gaxilxjr.html

[U29] Py：属性校验
来源：http://dali.sxryk.cn/Article/details/gt2onkwbahi.html

@property 与 @x.setter 配合
来源：http://dali.hywenlv.cn/Article/details/gt2qtakngmt.html

[U30] Py：数据类
来源：http://dali.xinyue.icu/Article/details/gt2smesmdke.html

@dataclass(slots=True)
来源：http://dali.cheryme.top/Article/details/gt2gpangwvq.html

[U31] Py：单测
来源：http://dali.hnqzz.top/Article/details/gt2lztzowej.html

python -m pytest -q
来源：http://dali.yueranfly.top/Article/details/gt2abnhijwn.html

[U32] Py：代码格式化
来源：http://dali.sysykeji.top/Article/details/gt2lrlaeptv.html

ruff format . && ruff check --fix .
来源：http://dali.iojbl.cn/Article/details/gt2pztcgdaa.html

[U33] Py：打包发布
来源：http://dali.yuxming.cn/Article/details/gt2npggpiam.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yueranfly.top/Article/details/gt2bwrtcbeb.html

[U34] Py：判断编码
来源：http://dali.zdqjudy.top/Article/details/gt2dejoochx.html

chardet.detect(raw)
来源：http://dali.xuanzx.com/Article/details/gt2fbetktct.html

[U35] Py：发送邮件
来源：http://dali.birdmap.top/Article/details/gt2ylhwqhtd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sxryk.cn/Article/details/gt2hrfwjqnb.html

[U36] Py：定时任务
来源：http://dali.haohaochexian.top/Article/details/gt2cmpwbggg.html

schedule.every(10).minutes.do(job)
来源：http://dali.ehwqpu.com/Article/details/gt2lmtzufgu.html

[U37] Py：读写 Excel
来源：http://dali.guowangkeji.top/Article/details/gt2tppuxeam.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jlsjyb.cn/Article/details/gt2lyfzaopz.html

[U38] Py：获取脚本所在目录
来源：http://dali.redwolf501.top/Article/details/gt2vutsxnzg.html

Path(__file__).resolve().parent
来源：http://dali.yuanzhike.top/Article/details/gt2wophpdwq.html

[U39] Py：判断是否在交互环境
来源：http://dali.quarkkingdee.top/Article/details/gt2bjtnndzl.html

sys.stdout.isatty()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ccgxhxhw.html

[U40] Py：打印到标准错误
来源：http://dali.fzhhl.top/Article/details/gt2iespbhma.html

print("err", file=sys.stderr)
来源：http://dali.iojbl.cn/Article/details/gt2nhajmovy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xuetiantiany.cn/Article/details/gt2udzppjmj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yj20258888.top/Article/details/gt2usplzxbf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hleexsle.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tianlin.xyz/Article/details/gt2doiegmqc.html


<!-- 参考信息 -->