代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vmyzlpck.html

[S23] C：随机数
来源：http://dali.xuanzx.com/Article/details/gt2grqzxpck.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cdnleiting.top/Article/details/gt2qfcspcec.html

[S24] C：获取本地时间
来源：http://dali.hfpthk.cn/Article/details/gt2khsiemga.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pycfn.com/Article/details/gt2xtnsnsov.html

[S25] C：内存拷贝
来源：http://dali.cdnleiting.top/Article/details/gt2nnenhzsy.html

memcpy(dst, src, n);
来源：http://dali.daria6918.cn/Article/details/gt2hbptwmmq.html

[S26] C：内存清零
来源：http://dali.yueranfly.top/Article/details/gt2vvpjibtx.html

memset(a, 0, sizeof a);
来源：http://dali.yongpay.top/Article/details/gt2ojfcgnol.html

[S27] C：定义常量
来源：http://dali.xuanzx.com/Article/details/gt2mkxhdxbo.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gt2kwjdikkd.html

[S28] C：静态变量
来源：http://dali.sufxvd.cn/Article/details/gt2cfdfvnty.html

static int counter = 0;
来源：http://dali.yangfankeji.com/Article/details/gt2edwhlydf.html

[S29] C：变参函数
来源：http://dali.0kj1m.cn/Article/details/gt2izgjfweo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cdnleiting.top/Article/details/gt2mshbfxzq.html

[S30] C：头文件保护
来源：http://dali.gzhubu.top/Article/details/gt2hzmsgach.html

#ifndef X_H
来源：http://dali.gaohongyu789.top/Article/details/gt2qttrakkh.html

#define X_H
来源：http://dali.snrcjt.cn/Article/details/gt2txeltcnu.html

#endif
来源：http://dali.chenlongwang.top/Article/details/gt2fywivotm.html

[S31] C++：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2lolbpalt.html

#include <iostream>
来源：http://dali.yonumen.top/Article/details/gt2wzguwxvh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fengsongda.top/Article/details/gt2djvlirde.html

[S32] C++：字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2lsvbkaoo.html

std::string s = "hi";  s += "!";
来源：http://dali.aizwys.cn/Article/details/gt2clnczybi.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gt2ldqoqwfu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuxming.cn/Article/details/gt2joxtjcvb.html

[S34] C++：遍历 vector
来源：http://dali.cucudq.cn/Article/details/gt2ixwodvub.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yueranfly.top/Article/details/gt2gopbxmcu.html

[S35] C++：map
来源：http://dali.yj202588.top/Article/details/gt2nqvtbzrt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ljdtxfdu.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiyktbe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gt2ymnmmocr.html

[S37] C++：set
来源：http://dali.hongshengwenyu.top/Article/details/gt2eaukkvpu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2oxkkoogo.html

[S38] C++：排序
来源：http://dali.xziqi.cn/Article/details/gt2zavyyoci.html

std::sort(v.begin(), v.end());
来源：http://dali.tanke756.top/Article/details/gt2oolnrwaf.html

[S39] C++：自定义比较器排序
来源：http://dali.quarkkingdee.top/Article/details/gt2gajvzsjk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cheryme.top/Article/details/gt2zhbrhbhj.html

[S40] C++：查找元素
来源：http://dali.nanxinkj.top/Article/details/gt2oxfzutpw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.birdmap.top/Article/details/gt2mmlajwub.html

[S41] C++：类与构造函数
来源：http://dali.jianghu66.top/Article/details/gt2ttrorawo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangdashe.top/Article/details/gt2vqegdfxm.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gt2saitjohv.html

class B : public Base { public: void f() override {} };
来源：http://dali.ppjwa.cn/Article/details/gt2vjewtwut.html

[S43] C++：智能指针
来源：http://dali.snrcjt.cn/Article/details/gt2acrcohjq.html

auto p = std::make_unique<int>(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2usqodxun.html

[S44] C++：引用传参
来源：http://dali.xylfe.cn/Article/details/gt2xxqofajq.html

void inc(int &x) { ++x; }
来源：http://dali.tian-w.cn/Article/details/gt2mkcwbkox.html

[S45] C++：lambda
来源：http://dali.ppjwa.cn/Article/details/gt2cjahllqk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tian-w.cn/Article/details/gt2rmftssce.html

[S46] C++：函数模板
来源：http://dali.mhx1999.top/Article/details/gt2gmnxonwc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.redwolf501.top/Article/details/gt2bwxqclit.html

[S47] C++：结构化绑定遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uozzsryd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ykyrzqva.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2drdgkuei.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.meibo888.top/Article/details/gt2mxqoqdil.html

while (std::getline(in, line)) { }
来源：http://dali.wangdashe.top/Article/details/gt2jtesbzps.html

[S49] C++：写文件
来源：http://dali.zycfv.cn/Article/details/gt2hxtltmes.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.havefunace.top/Article/details/gt2nggsqgmd.html

[S50] C++：格式化数字
来源：http://dali.dashuyun.cn/Article/details/gt2qjcxwpwv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sysykeji.top/Article/details/gt2hjmfmdbh.html

[S51] C++：显式类型转换
来源：http://dali.xziqi.cn/Article/details/gt2caeberor.html

static_cast<double>(a) / b
来源：http://dali.snrcjt.cn/Article/details/gt2zepkzict.html

[S52] C++：const 与 noexcept
来源：http://dali.hfpthk.cn/Article/details/gt2yzljqrbs.html

int size() const noexcept { return n_; }
来源：http://dali.shzxlz.cn/Article/details/gt2ewakvhwh.html

[S53] C++：移动语义
来源：http://dali.chenzaomai.com/Article/details/gt2etpqaklu.html

std::vector<int> w = std::move(v);
来源：http://dali.svipenyu.cn/Article/details/gt2poiysdyp.html

[S54] C++：异常处理
来源：http://dali.birdmap.top/Article/details/gt2xhsdloic.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhiwuduotai.top/Article/details/gt2gyqqrxkq.html

[S55] C++：结构化绑定
来源：http://dali.chenzaomai.com/Article/details/gt2adhqmppd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jianghu66.top/Article/details/gt2mhicvrsy.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gt2yidkuhol.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cashguo.top/Article/details/gt2fxjygsjg.html

[S57] C++：编译期常量
来源：http://dali.haohaochexian.top/Article/details/gt2arugsvhm.html

constexpr int N = 10;
来源：http://dali.guannengcc.top/Article/details/gt2mwrcnubw.html

[S58] C++：命名空间
来源：http://dali.ydzc1.top/Article/details/gt2rtxvxkuu.html

namespace ns { int f() { return 1; } }
来源：http://dali.dashuyun.cn/Article/details/gt2hjggedkm.html

[S59] C++：静态断言
来源：http://dali.ydzc1.top/Article/details/gt2ccodfjtc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ybcxt.top/Article/details/gt2hrzgoxkl.html

[S60] C++：遍历并删除元素
来源：http://dali.birdmap.top/Article/details/gt2xslzemad.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jyoumei.cn/Article/details/gt2tvkmgplq.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2agkrfhzd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykwjqiqh.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2pmtiaoxu.html

[T01] Kotlin：Hello World
来源：http://dali.havefunace.top/Article/details/gt2ceyislwp.html

println("Hello")
来源：http://dali.jinqigufen.top/Article/details/gt2xvwbwfne.html

[T02] Kotlin：变量
来源：http://dali.yonumen.top/Article/details/gt2vvaqfjho.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jiagoushi.top/Article/details/gt2bxvdeqgh.html

[T03] Kotlin：字符串模板
来源：http://dali.yj202588.top/Article/details/gt2rkujoywl.html

"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gt2zwpzvooq.html

[T04] Kotlin：空安全
来源：http://dali.zhoulong.xyz/Article/details/gt2ixygoyfd.html

val n: String? = null;  n?.length
来源：http://dali.zhoulong.xyz/Article/details/gt2qxjgtwmi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhoulong.xyz/Article/details/gt2tutthczj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangdashe.top/Article/details/gt2fsozqpec.html

[T06] Kotlin：集合映射
来源：http://dali.andypj.xyz/Article/details/gt2vfjmowwp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tanke756.top/Article/details/gt2sphgyshe.html

[T07] Kotlin：集合过滤
来源：http://dali.feifeiyinyue.top/Article/details/gt2cubmmhht.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ybcxt.top/Article/details/gt2zoolizaz.html

[T08] Kotlin：数据类
来源：http://dali.daria6918.cn/Article/details/gt2kvooedui.html

data class User(val name: String, val age: Int)
来源：http://dali.zdqjudy.top/Article/details/gt2tblxoeso.html

[T09] Kotlin：扩展函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2yhaipoia.html

fun String.exclaim() = this + "!"
来源：http://dali.jlsjyb.cn/Article/details/gt2hlrsckgq.html

[T10] Kotlin：默认参数
来源：http://dali.jlsjyb.cn/Article/details/gt2xmagvpny.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wmnecfhj.html

[T11] Kotlin：协程
来源：http://dali.zhengqikj.top/Article/details/gt2hmawpsdp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yongpay.top/Article/details/gt2wcnavryd.html

[T12] Kotlin：解构声明
来源：http://dali.zhixingplan.top/Article/details/gt2kpyeiazt.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2ohemupiu.html

[T13] Kotlin：只读 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mcjgamrz.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gt2gevlwvbn.html

[T14] Kotlin：循环
来源：http://dali.hnqzz.top/Article/details/gt2cpiyqshs.html

for (i in 1..10) println(i)
来源：http://dali.quarkkingdee.top/Article/details/gt2wpvlfnao.html

[T15] Kotlin：接口
来源：http://dali.havefunace.top/Article/details/gt2ajxvnefh.html

interface Shape { fun area(): Double }
来源：http://dali.fzhhl.top/Article/details/gt2ivkgutbv.html

[T16] Swift：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2zkdnlqvq.html

print("Hello")
来源：http://dali.zdqjudy.top/Article/details/gt2iqmjddmy.html

[T17] Swift：变量与常量
来源：http://dali.daria6918.cn/Article/details/gt2kwfefule.html

var a = 1;  let b = 2
来源：http://dali.yvedp.cn/Article/details/gt2ourrkhch.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2wckmqomn.html

"值: \(b)"
来源：http://dali.hywenlv.cn/Article/details/gt2yfcxpzag.html

[T19] Swift：可选绑定
来源：http://dali.bjfxy.top/Article/details/gt2balsnxvq.html

if let n = opt { print(n) }
来源：http://dali.yuxming.cn/Article/details/gt2pvlempbv.html

[T20] Swift：数组操作
来源：http://dali.andypj.xyz/Article/details/gt2usazewxg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jyoumei.cn/Article/details/gt2sdrzznbm.html

[T21] Swift：遍历
来源：http://dali.guannengcc.top/Article/details/gt2deqosvzm.html

for x in a { print(x) }
来源：http://dali.cucudq.cn/Article/details/gt2htiosanw.html

[T22] Swift：字典
来源：http://dali.hfpthk.cn/Article/details/gt2agszjuji.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dianchejie.cn/Article/details/gt2fabyyulq.html

[T23] Swift：函数
来源：http://dali.9152youxi.cn/Article/details/gt2gdxcinqz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinqigufen.top/Article/details/gt2vyfmcpcu.html

[T24] Swift：闭包
来源：http://dali.nanxinkj.top/Article/details/gt2hwyihwox.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2patcqbty.html

[T25] Swift：结构体
来源：http://dali.jinqigfzy.top/Article/details/gt2wodaztle.html

struct P { var x: Int }
来源：http://dali.sweek.top/Article/details/gt2ymxeyowj.html

[T26] Swift：类与重写
来源：http://dali.pengpengdd.cyou/Article/details/gt2mhxpjzna.html

class A: Base { override func f() {} }
来源：http://dali.cashguo.top/Article/details/gt2ezhyizti.html

[T27] Swift：错误处理
来源：http://dali.sufxvd.cn/Article/details/gt2emwcsxea.html

do { try f() } catch { print(error) }
来源：http://dali.cqqwz.cn/Article/details/gt2lljwieks.html

[T28] Swift：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gt2rngmgwdn.html

enum Color { case red, green }
来源：http://dali.sysykeji.top/Article/details/gt2uqgnrxio.html

[T29] Swift：guard 提前返回
来源：http://dali.meibo888.top/Article/details/gt2ltlzoypv.html

guard let x = opt else { return }
来源：http://dali.zhengqikj.top/Article/details/gt2cosswyjv.html

[T30] Swift：协议
来源：http://dali.sweek.top/Article/details/gt2vxlisedn.html

protocol Shape { func area() -> Double }
来源：http://dali.hongshengwenyu.top/Article/details/gt2clvcanpm.html

[T31] Lua：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2zvwqibwk.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gt2axckxukm.html

[T32] Lua：局部变量
来源：http://dali.yvedp.cn/Article/details/gt2zyjjhdtd.html

local a = 1
来源：http://dali.svipenyu.cn/Article/details/gt2osgtydjy.html

[T33] Lua：表（数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jxudnbuc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxinkj.top/Article/details/gt2odjrbkpy.html

[T34] Lua：遍历表
来源：http://dali.nanxinkj.top/Article/details/gt2wukuodmu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.fzhhl.top/Article/details/gt2ykmyacpw.html

[T35] Lua：字典表
来源：http://dali.haohaochexian.top/Article/details/gt2kybmjwyn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.andypj.xyz/Article/details/gt2pkfgiyqx.html

[T36] Lua：函数
来源：http://dali.sysykeji.top/Article/details/gt2hpwmefxs.html

function add(a, b) return a + b end
来源：http://dali.xuetiantiany.cn/Article/details/gt2wrurtqyo.html

[T37] Lua：字符串拼接
来源：http://dali.yuxming.cn/Article/details/gt2wgsspulp.html

"a" .. "b"
来源：http://dali.zycfv.cn/Article/details/gt2uzughukb.html

[T38] Lua：条件
来源：http://dali.shuidangran.top/Article/details/gt2adsbyeuc.html

if x > 0 then print("正") end
来源：http://dali.aizwys.cn/Article/details/gt2tzeifwla.html

[T39] Lua：模式匹配
来源：http://dali.bjfxy.top/Article/details/gt2remnjdqq.html

string.find(s, "%d+")
来源：http://dali.yuanzhike.top/Article/details/gt2limphqqp.html

[T40] Lua：元表
来源：http://dali.havefunace.top/Article/details/gt2wwtkozww.html

setmetatable({}, { __index = base })
来源：http://dali.svipenyu.cn/Article/details/gt2hwsskanh.html

[T41] Perl：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2enbbxstd.html

print "Hello\n";
来源：http://dali.hammf.cn/Article/details/gt2frplqyvu.html

[T42] Perl：变量类型
来源：http://dali.vqdsnc.cn/Article/details/gt2neggldpz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tian-w.cn/Article/details/gt2atzeaekj.html

[T43] Perl：字符串插值
来源：http://dali.tian-w.cn/Article/details/gt2gaiwyvno.html

"值: $a"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ttpocird.html

[T44] Perl：条件
来源：http://dali.dianchejie.cn/Article/details/gt2ypsutspk.html

if ($a > 0) { print "正"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2bklzwfzt.html

[T45] Perl：数组遍历
来源：http://dali.xylfe.cn/Article/details/gt2xlwnxhuj.html

for my $x (@arr) { print $x; }
来源：http://dali.yj20258.top/Article/details/gt2jcoscvkf.html

[T46] Perl：哈希操作
来源：http://dali.haohaochexian.top/Article/details/gt2ijrpsahr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zycfv.cn/Article/details/gt2wnbnwnge.html

[T47] Perl：正则捕获
来源：http://dali.jianghu66.top/Article/details/gt2oazzbafl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnxiangtu.top/Article/details/gt2qrmjkolj.html

[T48] Perl：正则替换
来源：http://dali.yvedp.cn/Article/details/gt2ghpavich.html

$s =~ s/old/new/g;
来源：http://dali.jlsjyb.cn/Article/details/gt2qqtovrfn.html

[T49] Perl：函数
来源：http://dali.jianghu66.top/Article/details/gt2vcgfjwve.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gt2wbooowbv.html

[T50] Perl：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gt2pysgenie.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.birdmap.top/Article/details/gt2kagjbevl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2trwjswas.html

[T51] Scala：Hello World
来源：http://dali.yj20258.top/Article/details/gt2mjfzwzlf.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gt2srouiujf.html

[T52] Scala：变量
来源：http://dali.hfpthk.cn/Article/details/gt2mozmhmmo.html

val a = 1;  var b = 2
来源：http://dali.gogol.net.cn/Article/details/gt2qpwpwhzu.html

[T53] Scala：字符串插值
来源：http://dali.iojbl.cn/Article/details/gt2zxcjkjbr.html

s"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gt2umkwwqqt.html

[T54] Scala：集合映射
来源：http://dali.zycfv.cn/Article/details/gt2lxvsedzt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2gqzglxft.html

[T55] Scala：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gt2aaireugb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sweek.top/Article/details/gt2rbpzchds.html

[T56] Scala：样例类
来源：http://dali.snrcjt.cn/Article/details/gt2qyvjfuzq.html

case class User(name: String, age: Int)
来源：http://dali.xuanzx.com/Article/details/gt2qkjtmtfw.html

[T57] Scala：模式匹配
来源：http://dali.yongpay.top/Article/details/gt2vvkloepe.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jqgufenzy.top/Article/details/gt2xzhpahpv.html

[T58] Scala：函数定义
来源：http://dali.ybcxt.top/Article/details/gt2zuqukobg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.smart0.xyz/Article/details/gt2xbofaysc.html

[T59] Scala：循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2hxdugcba.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kxrhhypk.html

[T60] Scala：折叠
来源：http://dali.hammf.cn/Article/details/gt2wmtaoskm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuanzhike.top/Article/details/gt2peohnqjq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2njxeftfx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gogol.net.cn/Article/details/gt2risgiuwa.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2pybnciep.html

[U01] Py：创建虚拟环境
来源：http://dali.hnxiangtu.top/Article/details/gt2inyxctwh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuetiantiany.cn/Article/details/gt2avlosnqm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gogol.net.cn/Article/details/gt2ixyctecp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2gspuftvj.html

[U03] Py：加载 .env 配置
来源：http://dali.redwolf501.top/Article/details/gt2rtmmdsll.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hnxiangtu.top/Article/details/gt2kqzzixcv.html

[U04] Py：变量调试打印
来源：http://dali.havefunace.top/Article/details/gt2lflfwboi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nwbrower.top/Article/details/gt2tkdaztug.html

[U05] Py：列表去重且保序
来源：http://dali.tianlin.xyz/Article/details/gt2twkcwklg.html

list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gt2fibskuzb.html

[U06] Py：合并两个字典
来源：http://dali.wangshuangyany.cn/Article/details/gt2egtihznb.html

{**a, **b}
来源：http://dali.guowangkeji.top/Article/details/gt2senikvcw.html

[U07] Py：反转字典键值
来源：http://dali.gogol.net.cn/Article/details/gt2vrugdudt.html

{v: k for k, v in d.items()}
来源：http://dali.hongshengwenyu.top/Article/details/gt2cyxngosn.html

[U08] Py：展平二维列表
来源：http://dali.ivvv.top/Article/details/gt2fledoibf.html

[y for x in nested for y in x]
来源：http://dali.guowangkeji.top/Article/details/gt2kisqiytd.html

[U09] Py：字典取最大值的键
来源：http://dali.jyoumei.cn/Article/details/gt2gzpsonpz.html

max(d, key=d.get)
来源：http://dali.yanxiufei.cn/Article/details/gt2cxqlkxtr.html

[U10] Py：按值排序字典
来源：http://dali.cheryme.top/Article/details/gt2npgobgfi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.0kj1m.cn/Article/details/gt2vlvkbyrn.html

[U11] Py：生成器表达式
来源：http://dali.xylfe.cn/Article/details/gt2kuiztwir.html

(x * 2 for x in arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rdtyhmah.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gzhubu.top/Article/details/gt2uydlmupb.html

Counter(arr).most_common(3)
来源：http://dali.svipenyu.cn/Article/details/gt2vqmjjqei.html

[U13] Py：固定长度队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqfwufqn.html

deque(maxlen=10)
来源：http://dali.zhoulong.xyz/Article/details/gt2vikvsmyt.html

[U14] Py：分组收集到列表
来源：http://dali.cdnleiting.top/Article/details/gt2mpedolbt.html

defaultdict(list)
来源：http://dali.quarkkingdee.top/Article/details/gt2owtydasi.html

[U15] Py：高精度计时
来源：http://dali.birdmap.top/Article/details/gt2kgqffwir.html

t = time.perf_counter()
来源：http://dali.xinyue.icu/Article/details/gt2wmhodacw.html

[U16] Py：命令行参数解析
来源：http://dali.cqqwz.cn/Article/details/gt2ehkdbuhb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.tianlin.xyz/Article/details/gt2dhasodgu.html

[U17] Py：初始化日志
来源：http://dali.jiagoushi.top/Article/details/gt2cysnpial.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zdqjudy.top/Article/details/gt2itskedkt.html

[U18] Py：预编译正则
来源：http://dali.chenzaomai.com/Article/details/gt2mtkulgdz.html

pat = re.compile(r"\d+")
来源：http://dali.haohaochexian.top/Article/details/gt2jphdvnus.html

[U19] Py：正则替换带回调
来源：http://dali.xziqi.cn/Article/details/gt2ehocrvey.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ybcxt.top/Article/details/gt2fcocmsqj.html

[U20] Py：缓存函数结果
来源：http://dali.jiagoushi.top/Article/details/gt2gihnsjyn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.iojbl.cn/Article/details/gt2clvallln.html

[U21] Py：自定义上下文管理器
来源：http://dali.0kj1m.cn/Article/details/gt2zekfemtf.html

@contextlib.contextmanager
来源：http://dali.ybcxt.top/Article/details/gt2nnshyvqr.html

[U22] Py：矩阵转置
来源：http://dali.shzxlz.cn/Article/details/gt2kbxdtnan.html

list(zip(*m))
来源：http://dali.gzhubu.top/Article/details/gt2mlglhplh.html

[U23] Py：分块读取大文件
来源：http://dali.daria6918.cn/Article/details/gt2nsaekxjv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shanyushiyangtech.top/Article/details/gt2peobsczy.html

[U24] Py：路径操作
来源：http://dali.nanxuanxn.top/Article/details/gt2cqlfneeo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gt2oifdhtig.html

[U25] Py：CSV 按字典读
来源：http://dali.hywenlv.cn/Article/details/gt2uphzdqyr.html

csv.DictReader(f)
来源：http://dali.havefunace.top/Article/details/gt2dxfxaajz.html

[U26] Py：并发下载
来源：http://dali.fengsongda.top/Article/details/gt2jrhvtckm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.vqdsnc.cn/Article/details/gt2nykdjwyf.html

[U27] Py：异步 HTTP
来源：http://dali.snrcjt.cn/Article/details/gt2fxlttxtk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yvedp.cn/Article/details/gt2hkktnzeh.html

[U28] Py：类型别名
来源：http://dali.havefunace.top/Article/details/gt2xvvjyewf.html

UserId = int
来源：http://dali.cqqwz.cn/Article/details/gt2whyawnmn.html

[U29] Py：属性校验
来源：http://dali.yvedp.cn/Article/details/gt2ymhpjfco.html

@property 与 @x.setter 配合
来源：http://dali.andypj.xyz/Article/details/gt2wlymbujh.html

[U30] Py：数据类
来源：http://dali.zdqjudy.top/Article/details/gt2udsknwnk.html

@dataclass(slots=True)
来源：http://dali.wangdashe.top/Article/details/gt2ajkdlcih.html

[U31] Py：单测
来源：http://dali.haohaochexian.top/Article/details/gt2zvefylog.html

python -m pytest -q
来源：http://dali.jinqigufen.top/Article/details/gt2unhphgdb.html

[U32] Py：代码格式化
来源：http://dali.chenzaomai.com/Article/details/gt2yaaexdpg.html

ruff format . && ruff check --fix .
来源：http://dali.c1oappe.top/Article/details/gt2rtclwdhb.html

[U33] Py：打包发布
来源：http://dali.chenlongwang.top/Article/details/gt2itptvjkz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.guannengcc.top/Article/details/gt2odxuzsgf.html

[U34] Py：判断编码
来源：http://dali.9152youxi.cn/Article/details/gt2joaeajqf.html

chardet.detect(raw)
来源：http://dali.yj202588.top/Article/details/gt2zoietyqu.html

[U35] Py：发送邮件
来源：http://dali.hywenlv.cn/Article/details/gt2rleetkwn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dyjvlbvr.html

[U36] Py：定时任务
来源：http://dali.0kj1m.cn/Article/details/gt2exhvrqhm.html

schedule.every(10).minutes.do(job)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vyivbnmk.html

[U37] Py：读写 Excel
来源：http://dali.jianghu66.top/Article/details/gt2ifquukgf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj20258.top/Article/details/gt2hispqrwt.html

[U38] Py：获取脚本所在目录
来源：http://dali.nanxinkj.top/Article/details/gt2ngbdpyeh.html

Path(__file__).resolve().parent
来源：http://dali.yueranfly.top/Article/details/gt2cvtdbruh.html

[U39] Py：判断是否在交互环境
来源：http://dali.fzhhl.top/Article/details/gt2sgyjrzkb.html

sys.stdout.isatty()
来源：http://dali.chenlongwang.top/Article/details/gt2tijbkwkm.html

[U40] Py：打印到标准错误
来源：http://dali.zhengqikj.top/Article/details/gt2aidkccna.html

print("err", file=sys.stderr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fkwimmkh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xuanzx.com/Article/details/gt2vxetfzuu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jqgfzy.top/Article/details/gt2cxtbjbxx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ppjwa.cn/Article/details/gt2qpmjavrz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.chenlongwang.top/Article/details/gt2nywjwgjq.html

[U43] PHP：声明命名空间
来源：http://dali.jiagoushi.top/Article/details/gt2efyantbe.html

namespace App\Http;
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkatkmnq.html

[U44] PHP：开启严格类型
来源：http://dali.sufxvd.cn/Article/details/gt2hokqeyjf.html

declare(strict_types=1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zlqkjdpy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.guowangkeji.top/Article/details/gt2csfslcek.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gt2drxdmatt.html

[U46] PHP：可空类型
来源：http://dali.0kj1m.cn/Article/details/gt2eqoweclf.html

?string $name = null
来源：http://dali.sufxvd.cn/Article/details/gt2spyvaetn.html


<!-- 参考信息 -->