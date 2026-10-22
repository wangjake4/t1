代发 wailian999

x |= (1 << 3);
来源：http://dali.zycfv.cn/Article/details/gt2iivkxjrc.html

[S17] C：安全拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gt2xupdepea.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ewaggcmw.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cabsjofx.html

int main(int argc, char **argv)
来源：http://dali.yj20258888.top/Article/details/gt2flwsgozw.html

[S19] C：快速排序
来源：http://dali.ydzc1.top/Article/details/gt2frnejxty.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gt2jbtokkbt.html

[S20] C：二分查找
来源：http://dali.jinqigfzy.top/Article/details/gt2hfxtiqor.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gt2zzyowklc.html

[S21] C：字符类别判断
来源：http://dali.bjfxy.top/Article/details/gt2pynnvnvj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnqzz.top/Article/details/gt2jfaczply.html

[S22] C：字符串转数字
来源：http://dali.nwbrower.top/Article/details/gt2mwlkzeiw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuanzx.com/Article/details/gt2tvvnvdam.html

[S23] C：随机数
来源：http://dali.hnqzz.top/Article/details/gt2jvdufkvl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sxryk.cn/Article/details/gt2ifjnnjhl.html

[S24] C：获取本地时间
来源：http://dali.guowangkeji.top/Article/details/gt2ujzoieou.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yangfankeji.com/Article/details/gt2odrnyurs.html

[S25] C：内存拷贝
来源：http://dali.aizwys.cn/Article/details/gt2nuxitbxa.html

memcpy(dst, src, n);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ddqsoqjf.html

[S26] C：内存清零
来源：http://dali.316326.xyz/Article/details/gt2yfawfnlm.html

memset(a, 0, sizeof a);
来源：http://dali.bjfxy.top/Article/details/gt2zflnpdrq.html

[S27] C：定义常量
来源：http://dali.xziqi.cn/Article/details/gt2cfveeaax.html

const double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kcqpbokm.html

[S28] C：静态变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mhhcdtgw.html

static int counter = 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2khpsmbre.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gt2qpoveyrt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yueranfly.top/Article/details/gt2oetpsnhi.html

[S30] C：头文件保护
来源：http://dali.sxryk.cn/Article/details/gt2pzmzvktj.html

#ifndef X_H
来源：http://dali.nanxuanxn.top/Article/details/gt2gsgvuley.html

#define X_H
来源：http://dali.yuxming.cn/Article/details/gt2ephfdzng.html

#endif
来源：http://dali.zhiwuduotai.top/Article/details/gt2ppwkyzwf.html

[S31] C++：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2ljxiwqpj.html

#include <iostream>
来源：http://dali.mhx1999.top/Article/details/gt2kngwbwfg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgfzy.top/Article/details/gt2aqskouth.html

[S32] C++：字符串
来源：http://dali.hnqzz.top/Article/details/gt2rwvdhzlg.html

std::string s = "hi";  s += "!";
来源：http://dali.xuetiantiany.cn/Article/details/gt2sqksrxnb.html

[S33] C++：vector 增删
来源：http://dali.yj20258888.top/Article/details/gt2trjmgrkt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuxming.cn/Article/details/gt2ttjhigfs.html

[S34] C++：遍历 vector
来源：http://dali.jyoumei.cn/Article/details/gt2hwdnxpnz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.snrcjt.cn/Article/details/gt2thafvcyn.html

[S35] C++：map
来源：http://dali.yueranfly.top/Article/details/gt2eghywguv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2zdnnaoau.html

[S36] C++：unordered_map
来源：http://dali.yonumen.top/Article/details/gt2zeuglzzd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fdzvahva.html

[S37] C++：set
来源：http://dali.hfpthk.cn/Article/details/gt2dspqpqyb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zdqjudy.top/Article/details/gt2abqtfikq.html

[S38] C++：排序
来源：http://dali.cucudq.cn/Article/details/gt2jeaqjitt.html

std::sort(v.begin(), v.end());
来源：http://dali.xziqi.cn/Article/details/gt2wzeibjqw.html

[S39] C++：自定义比较器排序
来源：http://dali.chenlongwang.top/Article/details/gt2omvuswur.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nwbrower.top/Article/details/gt2gwldokpr.html

[S40] C++：查找元素
来源：http://dali.dashuyun.cn/Article/details/gt2jevwswcq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sweek.top/Article/details/gt2dsqbpmml.html

[S41] C++：类与构造函数
来源：http://dali.wangdashe.top/Article/details/gt2pstzysax.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.quarkkingdee.top/Article/details/gt2pwmqniem.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2orlkbjip.html

class B : public Base { public: void f() override {} };
来源：http://dali.yangfankeji.com/Article/details/gt2sbiqjwne.html

[S43] C++：智能指针
来源：http://dali.gaohongyu789.top/Article/details/gt2vgnttjcx.html

auto p = std::make_unique<int>(5);
来源：http://dali.meibo888.top/Article/details/gt2xufqfrqd.html

[S44] C++：引用传参
来源：http://dali.guowangkeji.top/Article/details/gt2bzwchwcn.html

void inc(int &x) { ++x; }
来源：http://dali.gaohongyu789.top/Article/details/gt2mwojndxn.html

[S45] C++：lambda
来源：http://dali.yj20258888.top/Article/details/gt2vwfwkapu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guannengcc.top/Article/details/gt2tmzrxopg.html

[S46] C++：函数模板
来源：http://dali.havefunace.top/Article/details/gt2lrilosyx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zdqjudy.top/Article/details/gt2tdruwefz.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj202588.top/Article/details/gt2xccebqmz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hfpthk.cn/Article/details/gt2pvbzzout.html

[S48] C++：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gt2osmiocvw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hnqzz.top/Article/details/gt2zjhgoqws.html

while (std::getline(in, line)) { }
来源：http://dali.dashuyun.cn/Article/details/gt2xvwmkpqr.html

[S49] C++：写文件
来源：http://dali.aibaodan.cn/Article/details/gt2vmpmtedo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jlsjyb.cn/Article/details/gt2lhjrzxld.html

[S50] C++：格式化数字
来源：http://dali.shangyingyoupin.top/Article/details/gt2ahtpzoqn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2exhbjyie.html

[S51] C++：显式类型转换
来源：http://dali.ppjwa.cn/Article/details/gt2dkaedsme.html

static_cast<double>(a) / b
来源：http://dali.sxryk.cn/Article/details/gt2gvdsyhkw.html

[S52] C++：const 与 noexcept
来源：http://dali.hammf.cn/Article/details/gt2hoqgqjcm.html

int size() const noexcept { return n_; }
来源：http://dali.daria6918.cn/Article/details/gt2ycnanxfh.html

[S53] C++：移动语义
来源：http://dali.yanxiufei.cn/Article/details/gt2bwjtaqqn.html

std::vector<int> w = std::move(v);
来源：http://dali.yj202588.top/Article/details/gt2cunlgugf.html

[S54] C++：异常处理
来源：http://dali.chenlongwang.top/Article/details/gt2ynswhksq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nanxuanxn.top/Article/details/gt2hxhkkwpf.html

[S55] C++：结构化绑定
来源：http://dali.shuidangran.top/Article/details/gt2zslhcahm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sufxvd.cn/Article/details/gt2sshhojih.html

[S56] C++：optional
来源：http://dali.yueranfly.top/Article/details/gt2dozovtax.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mfhfmjae.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2srdgehbj.html

constexpr int N = 10;
来源：http://dali.xuanzx.com/Article/details/gt2mnikfkpv.html

[S58] C++：命名空间
来源：http://dali.hfpthk.cn/Article/details/gt2rkedpxet.html

namespace ns { int f() { return 1; } }
来源：http://dali.kuanghao11.cn/Article/details/gt2gfeffilp.html

[S59] C++：静态断言
来源：http://dali.aizwys.cn/Article/details/gt2vzimkwhv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shzxlz.cn/Article/details/gt2jfgcuptp.html

[S60] C++：遍历并删除元素
来源：http://dali.aibaodan.cn/Article/details/gt2jzipnzfj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yongpay.top/Article/details/gt2scsvntoz.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2mddconjg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gt2odwwwqtq.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2fibebdff.html

[T01] Kotlin：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fshneujg.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gt2tqltnnbf.html

[T02] Kotlin：变量
来源：http://dali.zhoulong.xyz/Article/details/gt2vjkkflia.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigfzy.top/Article/details/gt2emmqxkyf.html

[T03] Kotlin：字符串模板
来源：http://dali.shuidangran.top/Article/details/gt2chnahlzx.html

"值: $b"
来源：http://dali.hnqzz.top/Article/details/gt2ibccnsvi.html

[T04] Kotlin：空安全
来源：http://dali.0kj1m.cn/Article/details/gt2rxqtueqx.html

val n: String? = null;  n?.length
来源：http://dali.yj20258888.top/Article/details/gt2mqntkdnp.html

[T05] Kotlin：when 表达式
来源：http://dali.c1oappe.top/Article/details/gt2mkaimzsf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258.top/Article/details/gt2vzhbsnpo.html

[T06] Kotlin：集合映射
来源：http://dali.tanke756.top/Article/details/gt2ktplzwfw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2gxbgrqfe.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258.top/Article/details/gt2ldmxjhkq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hysaishi.cn/Article/details/gt2xwctqjmk.html

[T08] Kotlin：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qnkcniax.html

data class User(val name: String, val age: Int)
来源：http://dali.quarkkingdee.top/Article/details/gt2wmbsfuxl.html

[T09] Kotlin：扩展函数
来源：http://dali.gaohongyu789.top/Article/details/gt2fooroisu.html

fun String.exclaim() = this + "!"
来源：http://dali.tanke756.top/Article/details/gt2vrfxxdhq.html

[T10] Kotlin：默认参数
来源：http://dali.mhx1999.top/Article/details/gt2lvpjzmpu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigfzy.top/Article/details/gt2wnyeduko.html

[T11] Kotlin：协程
来源：http://dali.redwolf501.top/Article/details/gt2eqajmwci.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tianlin.xyz/Article/details/gt2ccehmppg.html

[T12] Kotlin：解构声明
来源：http://dali.havefunace.top/Article/details/gt2lhwoubpm.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gt2evlafbqu.html

[T13] Kotlin：只读 Map
来源：http://dali.snrcjt.cn/Article/details/gt2tfrznpvn.html

val m = mapOf("a" to 1)
来源：http://dali.guowangkeji.top/Article/details/gt2fbrwvnlk.html

[T14] Kotlin：循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2xbcuvjeu.html

for (i in 1..10) println(i)
来源：http://dali.tian-w.cn/Article/details/gt2strbppzj.html

[T15] Kotlin：接口
来源：http://dali.316326.xyz/Article/details/gt2jegxjnzd.html

interface Shape { fun area(): Double }
来源：http://dali.zhixingplan.top/Article/details/gt2fcsehokp.html

[T16] Swift：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxplxtmx.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gt2nmskkags.html

[T17] Swift：变量与常量
来源：http://dali.sysykeji.top/Article/details/gt2qvmzenel.html

var a = 1;  let b = 2
来源：http://dali.svipenyu.cn/Article/details/gt2apxlhfxi.html

[T18] Swift：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gt2kuvqhgim.html

"值: \(b)"
来源：http://dali.zhongyouzk.top/Article/details/gt2akgomufh.html

[T19] Swift：可选绑定
来源：http://dali.jlsjyb.cn/Article/details/gt2wmaviiei.html

if let n = opt { print(n) }
来源：http://dali.gzhubu.top/Article/details/gt2oaseczir.html

[T20] Swift：数组操作
来源：http://dali.yj20258.top/Article/details/gt2clfzmmgj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xziqi.cn/Article/details/gt2rzfhwucs.html

[T21] Swift：遍历
来源：http://dali.nanxinkj.top/Article/details/gt2engxkfev.html

for x in a { print(x) }
来源：http://dali.jianghu66.top/Article/details/gt2hsubzred.html

[T22] Swift：字典
来源：http://dali.daxiang520.top/Article/details/gt2djndewxs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hysaishi.cn/Article/details/gt2rmyvnpci.html

[T23] Swift：函数
来源：http://dali.daxiang520.top/Article/details/gt2kwppbjdx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.iojbl.cn/Article/details/gt2ryovsjwa.html

[T24] Swift：闭包
来源：http://dali.tian-w.cn/Article/details/gt2hoofqwtm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cheryme.top/Article/details/gt2qypakvfn.html

[T25] Swift：结构体
来源：http://dali.nwbrower.top/Article/details/gt2smxmydsr.html

struct P { var x: Int }
来源：http://dali.xziqi.cn/Article/details/gt2iefpokgh.html

[T26] Swift：类与重写
来源：http://dali.nanxinkj.top/Article/details/gt2wpudlkhs.html

class A: Base { override func f() {} }
来源：http://dali.hnqzz.top/Article/details/gt2uzwupaft.html

[T27] Swift：错误处理
来源：http://dali.cucudq.cn/Article/details/gt2wphnxrzn.html

do { try f() } catch { print(error) }
来源：http://dali.yuxming.cn/Article/details/gt2bulrvmap.html

[T28] Swift：枚举
来源：http://dali.smart0.xyz/Article/details/gt2iceqvgci.html

enum Color { case red, green }
来源：http://dali.ehwqpu.com/Article/details/gt2omuzugey.html

[T29] Swift：guard 提前返回
来源：http://dali.gzhubu.top/Article/details/gt2bdmewujn.html

guard let x = opt else { return }
来源：http://dali.guannengcc.top/Article/details/gt2dnmtsrnk.html

[T30] Swift：协议
来源：http://dali.mhx1999.top/Article/details/gt2lwunkgkg.html

protocol Shape { func area() -> Double }
来源：http://dali.dashuyun.cn/Article/details/gt2nkgayigs.html

[T31] Lua：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2acuylulh.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2msuklomo.html

[T32] Lua：局部变量
来源：http://dali.jinqigfzy.top/Article/details/gt2jtujzrkb.html

local a = 1
来源：http://dali.hywenlv.cn/Article/details/gt2ycxxhomp.html

[T33] Lua：表（数组）
来源：http://dali.hammf.cn/Article/details/gt2qmllouwg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xuanzx.com/Article/details/gt2japdteqo.html

[T34] Lua：遍历表
来源：http://dali.ppjwa.cn/Article/details/gt2qplcjmiw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jiagoushi.top/Article/details/gt2gxinnqxe.html

[T35] Lua：字典表
来源：http://dali.yj202588.top/Article/details/gt2uqhkgoug.html

local d = { a = 1 };  d.b = 2
来源：http://dali.haohaochexian.top/Article/details/gt2hqqouqpm.html

[T36] Lua：函数
来源：http://dali.havefunace.top/Article/details/gt2ikjodayg.html

function add(a, b) return a + b end
来源：http://dali.jinqigfzy.top/Article/details/gt2xooquliv.html

[T37] Lua：字符串拼接
来源：http://dali.cheryme.top/Article/details/gt2nffanwke.html

"a" .. "b"
来源：http://dali.yj202588.top/Article/details/gt2ooiwixcy.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yynhthtg.html

if x > 0 then print("正") end
来源：http://dali.guowangkeji.top/Article/details/gt2bnihldfm.html

[T39] Lua：模式匹配
来源：http://dali.daria6918.cn/Article/details/gt2cfwwrtlw.html

string.find(s, "%d+")
来源：http://dali.yueranfly.top/Article/details/gt2kgfehzcs.html

[T40] Lua：元表
来源：http://dali.hnxiangtu.top/Article/details/gt2wfzwhqyq.html

setmetatable({}, { __index = base })
来源：http://dali.zycfv.cn/Article/details/gt2nskcfzxa.html

[T41] Perl：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gt2ujjndkwo.html

print "Hello\n";
来源：http://dali.nanxuanxn.top/Article/details/gt2thtusdze.html

[T42] Perl：变量类型
来源：http://dali.mhx1999.top/Article/details/gt2mjwszhcx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2dcusduaj.html

[T43] Perl：字符串插值
来源：http://dali.smart0.xyz/Article/details/gt2ghlzsnsv.html

"值: $a"
来源：http://dali.9152youxi.cn/Article/details/gt2lyfkfaxs.html

[T44] Perl：条件
来源：http://dali.meibo888.top/Article/details/gt2tcllyuiz.html

if ($a > 0) { print "正"; }
来源：http://dali.tianlin.xyz/Article/details/gt2uktrixyl.html

[T45] Perl：数组遍历
来源：http://dali.jiagoushi.top/Article/details/gt2gggasrdn.html

for my $x (@arr) { print $x; }
来源：http://dali.yueranfly.top/Article/details/gt2mdswzxoc.html

[T46] Perl：哈希操作
来源：http://dali.hnqzz.top/Article/details/gt2ppbqxkgr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.pycfn.com/Article/details/gt2jevttxlu.html

[T47] Perl：正则捕获
来源：http://dali.jqgufenzy.top/Article/details/gt2ydssnsos.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.snrcjt.cn/Article/details/gt2rkhzojoc.html

[T48] Perl：正则替换
来源：http://dali.dashuyun.cn/Article/details/gt2muadojtv.html

$s =~ s/old/new/g;
来源：http://dali.hfpthk.cn/Article/details/gt2ktybfybc.html

[T49] Perl：函数
来源：http://dali.0kj1m.cn/Article/details/gt2oxbgdxnm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dabgxmrp.html

[T50] Perl：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gt2dtxkesjw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zycfv.cn/Article/details/gt2nivfdfqd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gogol.net.cn/Article/details/gt2otvjircz.html

[T51] Scala：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2ndjbawpe.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gt2ogneccrd.html

[T52] Scala：变量
来源：http://dali.guowangkeji.top/Article/details/gt2lmcnsmfo.html

val a = 1;  var b = 2
来源：http://dali.aizwys.cn/Article/details/gt2nuvrefwx.html

[T53] Scala：字符串插值
来源：http://dali.daxiang520.top/Article/details/gt2giffbtep.html

s"值: $b"
来源：http://dali.birdmap.top/Article/details/gt2khzqjlji.html

[T54] Scala：集合映射
来源：http://dali.guowangkeji.top/Article/details/gt2sjmbtjgz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.fzhhl.top/Article/details/gt2jlibpoyc.html

[T55] Scala：集合过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2arxsysft.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.dianchejie.cn/Article/details/gt2hvphyqac.html

[T56] Scala：样例类
来源：http://dali.aizwys.cn/Article/details/gt2kmbshfmz.html

case class User(name: String, age: Int)
来源：http://dali.mhx1999.top/Article/details/gt2uexurvfb.html

[T57] Scala：模式匹配
来源：http://dali.aizwys.cn/Article/details/gt2pnfvvapd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnqzz.top/Article/details/gt2xhtysfmp.html

[T58] Scala：函数定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mudyytat.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhengqikj.top/Article/details/gt2hrcjurxk.html

[T59] Scala：循环
来源：http://dali.gogol.net.cn/Article/details/gt2lmjrtydv.html

for (i <- 1 to 10) println(i)
来源：http://dali.yonumen.top/Article/details/gt2dzyxnyfn.html

[T60] Scala：折叠
来源：http://dali.havefunace.top/Article/details/gt2gtaihwej.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xziqi.cn/Article/details/gt2uxoqkpyn.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2npliiilp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenlongwang.top/Article/details/gt2lxljrqdy.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2lelmlpag.html

[U01] Py：创建虚拟环境
来源：http://dali.wangdashe.top/Article/details/gt2cpnyjvaa.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhoulong.xyz/Article/details/gt2vpdygjls.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shzxlz.cn/Article/details/gt2nmuyflxu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenlongwang.top/Article/details/gt2eigxlcar.html

[U03] Py：加载 .env 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vmmklkkc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shuidangran.top/Article/details/gt2bhpnslqq.html

[U04] Py：变量调试打印
来源：http://dali.yuanzhike.top/Article/details/gt2ytcdovht.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.snrcjt.cn/Article/details/gt2jynaioxs.html

[U05] Py：列表去重且保序
来源：http://dali.snrcjt.cn/Article/details/gt2ddqzlsnd.html

list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gt2yrbhhrvv.html

[U06] Py：合并两个字典
来源：http://dali.havefunace.top/Article/details/gt2pbgrtdwt.html

{**a, **b}
来源：http://dali.guowangkeji.top/Article/details/gt2twfqujas.html

[U07] Py：反转字典键值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2orblsumz.html

{v: k for k, v in d.items()}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kzjnltpy.html

[U08] Py：展平二维列表
来源：http://dali.sxryk.cn/Article/details/gt2cmjamurz.html

[y for x in nested for y in x]
来源：http://dali.yuxming.cn/Article/details/gt2wpcffxsi.html

[U09] Py：字典取最大值的键
来源：http://dali.daxiang520.top/Article/details/gt2cfxbjitt.html

max(d, key=d.get)
来源：http://dali.yueranfly.top/Article/details/gt2yqubysok.html

[U10] Py：按值排序字典
来源：http://dali.yueranfly.top/Article/details/gt2sxkbybrg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigfzy.top/Article/details/gt2qmqxuqkj.html

[U11] Py：生成器表达式
来源：http://dali.yj20258888.top/Article/details/gt2fxwoqafd.html

(x * 2 for x in arr)
来源：http://dali.jiagoushi.top/Article/details/gt2vbfghpsf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jyoumei.cn/Article/details/gt2npisbljn.html

Counter(arr).most_common(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rtluxlbi.html

[U13] Py：固定长度队列
来源：http://dali.nanxinkj.top/Article/details/gt2wnpmmgib.html

deque(maxlen=10)
来源：http://dali.sysykeji.top/Article/details/gt2dtmalett.html

[U14] Py：分组收集到列表
来源：http://dali.dianchejie.cn/Article/details/gt2gbriiuof.html

defaultdict(list)
来源：http://dali.fzhhl.top/Article/details/gt2itquvioy.html

[U15] Py：高精度计时
来源：http://dali.jqgufenzy.top/Article/details/gt2txjzanmu.html

t = time.perf_counter()
来源：http://dali.ppjwa.cn/Article/details/gt2fiyslkdj.html

[U16] Py：命令行参数解析
来源：http://dali.zhiwuduotai.top/Article/details/gt2yjwdzelu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhongyouzk.top/Article/details/gt2zqazaypv.html

[U17] Py：初始化日志
来源：http://dali.zdqjudy.top/Article/details/gt2okustiod.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.chenzaomai.com/Article/details/gt2doaylegg.html

[U18] Py：预编译正则
来源：http://dali.jyoumei.cn/Article/details/gt2ixnybonu.html

pat = re.compile(r"\d+")
来源：http://dali.yueranfly.top/Article/details/gt2udslmapu.html

[U19] Py：正则替换带回调
来源：http://dali.ivvv.top/Article/details/gt2ogrnsheg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jqgufenzy.top/Article/details/gt2vtyescsa.html

[U20] Py：缓存函数结果
来源：http://dali.zhixingplan.top/Article/details/gt2tijxxday.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhoulong.xyz/Article/details/gt2amemmbeg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhongyouzk.top/Article/details/gt2aqxawwoo.html

@contextlib.contextmanager
来源：http://dali.aizwys.cn/Article/details/gt2uzuykhrt.html

[U22] Py：矩阵转置
来源：http://dali.xuanzx.com/Article/details/gt2qneletze.html

list(zip(*m))
来源：http://dali.kuanghao11.cn/Article/details/gt2tmlkiscj.html

[U23] Py：分块读取大文件
来源：http://dali.sxryk.cn/Article/details/gt2sxuokugl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenzaomai.com/Article/details/gt2qspbvylu.html

[U24] Py：路径操作
来源：http://dali.jyoumei.cn/Article/details/gt2hdbxaoym.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.mhx1999.top/Article/details/gt2jclphmma.html

[U25] Py：CSV 按字典读
来源：http://dali.dashuyun.cn/Article/details/gt2rapwhjwc.html

csv.DictReader(f)
来源：http://dali.hfpthk.cn/Article/details/gt2gzvatpdw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2tjaipleo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gogol.net.cn/Article/details/gt2ukbnsyns.html

[U27] Py：异步 HTTP
来源：http://dali.cdnleiting.top/Article/details/gt2tifjcptp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hywenlv.cn/Article/details/gt2xwtqxhnk.html

[U28] Py：类型别名
来源：http://dali.sweek.top/Article/details/gt2iunrxnqt.html

UserId = int
来源：http://dali.pycfn.com/Article/details/gt2gzgrlbqd.html

[U29] Py：属性校验
来源：http://dali.svipenyu.cn/Article/details/gt2ngzqktjs.html

@property 与 @x.setter 配合
来源：http://dali.xinyue.icu/Article/details/gt2wkpbmdfx.html

[U30] Py：数据类
来源：http://dali.yonumen.top/Article/details/gt2cgdhsqnq.html

@dataclass(slots=True)
来源：http://dali.xuanzx.com/Article/details/gt2llvqmmjw.html

[U31] Py：单测
来源：http://dali.kuanghao11.cn/Article/details/gt2ghmkmuzl.html

python -m pytest -q
来源：http://dali.pycfn.com/Article/details/gt2ldoqresb.html

[U32] Py：代码格式化
来源：http://dali.nanxinkj.top/Article/details/gt2gnqwpqys.html

ruff format . && ruff check --fix .
来源：http://dali.gaohongyu789.top/Article/details/gt2tiomdpzt.html

[U33] Py：打包发布
来源：http://dali.zhongyouzk.top/Article/details/gt2guccaonx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.svipenyu.cn/Article/details/gt2jsbbkotx.html

[U34] Py：判断编码
来源：http://dali.gotoacloud.top/Article/details/gt2dymgoboz.html

chardet.detect(raw)
来源：http://dali.nwbrower.top/Article/details/gt2oltaimov.html

[U35] Py：发送邮件
来源：http://dali.nanxuanxn.top/Article/details/gt2hikzxgdu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ehwqpu.com/Article/details/gt2fdhuolvw.html

[U36] Py：定时任务
来源：http://dali.feifeiyinyue.top/Article/details/gt2jyybplmz.html

schedule.every(10).minutes.do(job)
来源：http://dali.daxiang520.top/Article/details/gt2fddftyih.html

[U37] Py：读写 Excel
来源：http://dali.kuanghao11.cn/Article/details/gt2fhqavecu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hongshengwenyu.top/Article/details/gt2dattxikx.html

[U38] Py：获取脚本所在目录
来源：http://dali.tian-w.cn/Article/details/gt2bbxiqtfw.html

Path(__file__).resolve().parent
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dnpeyily.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rqkugblr.html

sys.stdout.isatty()
来源：http://dali.chenlongwang.top/Article/details/gt2sedmsbzu.html

[U40] Py：打印到标准错误
来源：http://dali.yueranfly.top/Article/details/gt2mxeedmcs.html

print("err", file=sys.stderr)
来源：http://dali.andypj.xyz/Article/details/gt2dtkoojqn.html


<!-- 参考信息 -->