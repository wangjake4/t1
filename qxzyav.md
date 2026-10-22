代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gt2qdrzxzfy.html

[S23] C：随机数
来源：http://dali.yonumen.top/Article/details/gt2uqphapvl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shzxlz.cn/Article/details/gt2lrdbhnio.html

[S24] C：获取本地时间
来源：http://dali.xuetiantiany.cn/Article/details/gt2hdavhgmh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pnrvpbhl.html

[S25] C：内存拷贝
来源：http://dali.haohaochexian.top/Article/details/gt2inuhdkcl.html

memcpy(dst, src, n);
来源：http://dali.ivvv.top/Article/details/gt2cvpctdnt.html

[S26] C：内存清零
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ermvqwef.html

memset(a, 0, sizeof a);
来源：http://dali.shuidangran.top/Article/details/gt2njxzshsy.html

[S27] C：定义常量
来源：http://dali.havefunace.top/Article/details/gt2tctzeulx.html

const double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gt2lnhnvrsc.html

[S28] C：静态变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2wcywrmqo.html

static int counter = 0;
来源：http://dali.gotoacloud.top/Article/details/gt2fpbnflbz.html

[S29] C：变参函数
来源：http://dali.zycfv.cn/Article/details/gt2lnaoxbtq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fzhhl.top/Article/details/gt2scnqyzyz.html

[S30] C：头文件保护
来源：http://dali.daxiang520.top/Article/details/gt2kwpeccbd.html

#ifndef X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ooqgcsyd.html

#define X_H
来源：http://dali.sweek.top/Article/details/gt2fsxudcze.html

#endif
来源：http://dali.yuanzhike.top/Article/details/gt2szinkwrl.html

[S31] C++：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2pwcowgha.html

#include <iostream>
来源：http://dali.hfpthk.cn/Article/details/gt2rmaezynk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ehwqpu.com/Article/details/gt2oxvjvowr.html

[S32] C++：字符串
来源：http://dali.sweek.top/Article/details/gt2zhbewpix.html

std::string s = "hi";  s += "!";
来源：http://dali.xuanzx.com/Article/details/gt2hpblypsi.html

[S33] C++：vector 增删
来源：http://dali.meibo888.top/Article/details/gt2qysdidui.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.9152youxi.cn/Article/details/gt2fstsrmaz.html

[S34] C++：遍历 vector
来源：http://dali.yonumen.top/Article/details/gt2qmpswyak.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258888.top/Article/details/gt2mkacbhsu.html

[S35] C++：map
来源：http://dali.guannengcc.top/Article/details/gt2omlsohif.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2kkqbgyet.html

[S36] C++：unordered_map
来源：http://dali.yuanzhike.top/Article/details/gt2mbuxepbu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2kmssutnu.html

[S37] C++：set
来源：http://dali.jiagoushi.top/Article/details/gt2ckcmmysz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2dgmjskyt.html

[S38] C++：排序
来源：http://dali.snrcjt.cn/Article/details/gt2vuvpnqve.html

std::sort(v.begin(), v.end());
来源：http://dali.pycfn.com/Article/details/gt2evprudjs.html

[S39] C++：自定义比较器排序
来源：http://dali.gzhubu.top/Article/details/gt2lmsueqfl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.vqdsnc.cn/Article/details/gt2nwsidtgw.html

[S40] C++：查找元素
来源：http://dali.cashguo.top/Article/details/gt2orlpqtpk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aizwys.cn/Article/details/gt2drkwyqqq.html

[S41] C++：类与构造函数
来源：http://dali.daxiang520.top/Article/details/gt2gsjavvfs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xylfe.cn/Article/details/gt2zqavcstk.html

[S42] C++：继承与虚函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cnycoxsy.html

class B : public Base { public: void f() override {} };
来源：http://dali.haohaochexian.top/Article/details/gt2twmywwrj.html

[S43] C++：智能指针
来源：http://dali.aizwys.cn/Article/details/gt2ycoeczjq.html

auto p = std::make_unique<int>(5);
来源：http://dali.hongshengwenyu.top/Article/details/gt2cslijjzr.html

[S44] C++：引用传参
来源：http://dali.tian-w.cn/Article/details/gt2chubwqgt.html

void inc(int &x) { ++x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mlrfhhbb.html

[S45] C++：lambda
来源：http://dali.0kj1m.cn/Article/details/gt2ruxljjgg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxuanxn.top/Article/details/gt2dxxvrnjv.html

[S46] C++：函数模板
来源：http://dali.snrcjt.cn/Article/details/gt2xhluzncy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pycfn.com/Article/details/gt2qhskmavh.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhqbuet.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yvedp.cn/Article/details/gt2tvrylspb.html

[S48] C++：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gt2vghjgrnx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xziqi.cn/Article/details/gt2aguxyiwa.html

while (std::getline(in, line)) { }
来源：http://dali.haohaochexian.top/Article/details/gt2otmxjjjr.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gt2mdebjctq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yvedp.cn/Article/details/gt2qavgprgt.html

[S50] C++：格式化数字
来源：http://dali.sweek.top/Article/details/gt2nfpbkqoa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gt2qgubexuj.html

[S51] C++：显式类型转换
来源：http://dali.shuidangran.top/Article/details/gt2udktiwgp.html

static_cast<double>(a) / b
来源：http://dali.dianchejie.cn/Article/details/gt2zhdvphur.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxuanxn.top/Article/details/gt2rsojfloc.html

int size() const noexcept { return n_; }
来源：http://dali.ybcxt.top/Article/details/gt2ddrldgmy.html

[S53] C++：移动语义
来源：http://dali.ybcxt.top/Article/details/gt2szqpvmzi.html

std::vector<int> w = std::move(v);
来源：http://dali.cqqwz.cn/Article/details/gt2ingmtogx.html

[S54] C++：异常处理
来源：http://dali.ybcxt.top/Article/details/gt2kjtglbhf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qypfvzmr.html

[S55] C++：结构化绑定
来源：http://dali.tianlin.xyz/Article/details/gt2wtwordrz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hywenlv.cn/Article/details/gt2tzkgkijz.html

[S56] C++：optional
来源：http://dali.cqqwz.cn/Article/details/gt2iwgtzpty.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gt2slvhqrdu.html

[S57] C++：编译期常量
来源：http://dali.andypj.xyz/Article/details/gt2mmdatzqp.html

constexpr int N = 10;
来源：http://dali.yongpay.top/Article/details/gt2lsjhrhwq.html

[S58] C++：命名空间
来源：http://dali.quarkkingdee.top/Article/details/gt2ymvmsfsu.html

namespace ns { int f() { return 1; } }
来源：http://dali.yanxiufei.cn/Article/details/gt2egufjatq.html

[S59] C++：静态断言
来源：http://dali.jianghu66.top/Article/details/gt2whndsbxu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gaohongyu789.top/Article/details/gt2izgfzapv.html

[S60] C++：遍历并删除元素
来源：http://dali.smart0.xyz/Article/details/gt2imqfotqo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gogol.net.cn/Article/details/gt2htalgibx.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2jpludnhf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gt2xdtpueoo.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vycbmfqz.html

[T01] Kotlin：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2hbkafyrj.html

println("Hello")
来源：http://dali.smart0.xyz/Article/details/gt2fjkvdrgn.html

[T02] Kotlin：变量
来源：http://dali.chenlongwang.top/Article/details/gt2vlyzhugv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.meibo888.top/Article/details/gt2gwbhxuvb.html

[T03] Kotlin：字符串模板
来源：http://dali.pycfn.com/Article/details/gt2wycosynr.html

"值: $b"
来源：http://dali.316326.xyz/Article/details/gt2ztwlyvyc.html

[T04] Kotlin：空安全
来源：http://dali.cheryme.top/Article/details/gt2ubddrgth.html

val n: String? = null;  n?.length
来源：http://dali.hywenlv.cn/Article/details/gt2znrjjuns.html

[T05] Kotlin：when 表达式
来源：http://dali.andypj.xyz/Article/details/gt2zueajfdq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.bjfxy.top/Article/details/gt2mxxkadcm.html

[T06] Kotlin：集合映射
来源：http://dali.zhengqikj.top/Article/details/gt2avcebigw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jyoumei.cn/Article/details/gt2euwzdwxs.html

[T07] Kotlin：集合过滤
来源：http://dali.tian-w.cn/Article/details/gt2nknunbze.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2txxlzsds.html

[T08] Kotlin：数据类
来源：http://dali.jinqigfzy.top/Article/details/gt2bgtrblkz.html

data class User(val name: String, val age: Int)
来源：http://dali.gotoacloud.top/Article/details/gt2chtaqzrd.html

[T09] Kotlin：扩展函数
来源：http://dali.hammf.cn/Article/details/gt2bllmxrpv.html

fun String.exclaim() = this + "!"
来源：http://dali.mhx1999.top/Article/details/gt2iclyozyq.html

[T10] Kotlin：默认参数
来源：http://dali.nanxinkj.top/Article/details/gt2gnciuowi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.birdmap.top/Article/details/gt2nhcxiuus.html

[T11] Kotlin：协程
来源：http://dali.shangyingyoupin.top/Article/details/gt2xuyconki.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tian-w.cn/Article/details/gt2ppmvopcx.html

[T12] Kotlin：解构声明
来源：http://dali.guannengcc.top/Article/details/gt2zuojctkg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2cblmdclh.html

[T13] Kotlin：只读 Map
来源：http://dali.feifeiyinyue.top/Article/details/gt2bwnetzph.html

val m = mapOf("a" to 1)
来源：http://dali.sufxvd.cn/Article/details/gt2bqzarisz.html

[T14] Kotlin：循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwibqsml.html

for (i in 1..10) println(i)
来源：http://dali.birdmap.top/Article/details/gt2msxfvtgh.html

[T15] Kotlin：接口
来源：http://dali.zycfv.cn/Article/details/gt2krktiwbx.html

interface Shape { fun area(): Double }
来源：http://dali.sweek.top/Article/details/gt2jsllprrn.html

[T16] Swift：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2kmmycttk.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gt2rmfofvvh.html

[T17] Swift：变量与常量
来源：http://dali.jianghu66.top/Article/details/gt2pnriislj.html

var a = 1;  let b = 2
来源：http://dali.yongpay.top/Article/details/gt2xzhiewsi.html

[T18] Swift：字符串插值
来源：http://dali.cheryme.top/Article/details/gt2uicudtyw.html

"值: \(b)"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rthyliik.html

[T19] Swift：可选绑定
来源：http://dali.snrcjt.cn/Article/details/gt2ymxpdtjk.html

if let n = opt { print(n) }
来源：http://dali.meibo888.top/Article/details/gt2vsqokdql.html

[T20] Swift：数组操作
来源：http://dali.yuanzhike.top/Article/details/gt2fnbyhlft.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2evdeoymd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhfeobx.html

for x in a { print(x) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2svlfydca.html

[T22] Swift：字典
来源：http://dali.svipenyu.cn/Article/details/gt2hwgnqysc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ipihcpfu.html

[T23] Swift：函数
来源：http://dali.snrcjt.cn/Article/details/gt2nxljrigu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangdashe.top/Article/details/gt2dnwkllep.html

[T24] Swift：闭包
来源：http://dali.ybcxt.top/Article/details/gt2nhgxryig.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2jpsnoobk.html

[T25] Swift：结构体
来源：http://dali.sysykeji.top/Article/details/gt2cpohowrn.html

struct P { var x: Int }
来源：http://dali.wangdashe.top/Article/details/gt2ychatkvr.html

[T26] Swift：类与重写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uavrxhtq.html

class A: Base { override func f() {} }
来源：http://dali.c1oappe.top/Article/details/gt2ahdalysl.html

[T27] Swift：错误处理
来源：http://dali.yvedp.cn/Article/details/gt2ytxezcmy.html

do { try f() } catch { print(error) }
来源：http://dali.ehwqpu.com/Article/details/gt2rqjgvnjn.html

[T28] Swift：枚举
来源：http://dali.xziqi.cn/Article/details/gt2rxeathma.html

enum Color { case red, green }
来源：http://dali.chenlongwang.top/Article/details/gt2emcogctl.html

[T29] Swift：guard 提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gt2sqyifbzu.html

guard let x = opt else { return }
来源：http://dali.aibaodan.cn/Article/details/gt2eiiecgvs.html

[T30] Swift：协议
来源：http://dali.chenlongwang.top/Article/details/gt2ghlkbjmw.html

protocol Shape { func area() -> Double }
来源：http://dali.ydzc1.top/Article/details/gt2kwnkbsos.html

[T31] Lua：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2stcmehqn.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gt2saxofutz.html

[T32] Lua：局部变量
来源：http://dali.sysykeji.top/Article/details/gt2fqeosnzh.html

local a = 1
来源：http://dali.zhoulong.xyz/Article/details/gt2cmtgmklx.html

[T33] Lua：表（数组）
来源：http://dali.daxiang520.top/Article/details/gt2jdhkedam.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.bjfxy.top/Article/details/gt2btihnsrv.html

[T34] Lua：遍历表
来源：http://dali.jyoumei.cn/Article/details/gt2hmaetdkh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pengpengdd.cyou/Article/details/gt2pthxgtgv.html

[T35] Lua：字典表
来源：http://dali.meibo888.top/Article/details/gt2xwzficqi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cashguo.top/Article/details/gt2hrppvgbx.html

[T36] Lua：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zsjaiiog.html

function add(a, b) return a + b end
来源：http://dali.shangyingyoupin.top/Article/details/gt2ifmdekgz.html

[T37] Lua：字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gt2tmlzopfq.html

"a" .. "b"
来源：http://dali.sweek.top/Article/details/gt2hiiyhndo.html

[T38] Lua：条件
来源：http://dali.yj20258888.top/Article/details/gt2pvnfipbf.html

if x > 0 then print("正") end
来源：http://dali.dianchejie.cn/Article/details/gt2ycuxmaxt.html

[T39] Lua：模式匹配
来源：http://dali.shzxlz.cn/Article/details/gt2uerjkbko.html

string.find(s, "%d+")
来源：http://dali.jqgfzy.top/Article/details/gt2eqqfjpde.html

[T40] Lua：元表
来源：http://dali.feifeiyinyue.top/Article/details/gt2xvkwpbge.html

setmetatable({}, { __index = base })
来源：http://dali.wangdashe.top/Article/details/gt2luczrazy.html

[T41] Perl：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2lcscqito.html

print "Hello\n";
来源：http://dali.yonumen.top/Article/details/gt2qaaqhbyi.html

[T42] Perl：变量类型
来源：http://dali.chenzaomai.com/Article/details/gt2lzvwcnpd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgfzy.top/Article/details/gt2bshjodbh.html

[T43] Perl：字符串插值
来源：http://dali.hnqzz.top/Article/details/gt2fbhixngs.html

"值: $a"
来源：http://dali.316326.xyz/Article/details/gt2qmyogezj.html

[T44] Perl：条件
来源：http://dali.zhoulong.xyz/Article/details/gt2fnekslgr.html

if ($a > 0) { print "正"; }
来源：http://dali.ybcxt.top/Article/details/gt2tfjcjneh.html

[T45] Perl：数组遍历
来源：http://dali.guannengcc.top/Article/details/gt2mmliozyi.html

for my $x (@arr) { print $x; }
来源：http://dali.xziqi.cn/Article/details/gt2zyjmwnzq.html

[T46] Perl：哈希操作
来源：http://dali.jiagoushi.top/Article/details/gt2tigpvhol.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hammf.cn/Article/details/gt2yekgpazo.html

[T47] Perl：正则捕获
来源：http://dali.yuanzhike.top/Article/details/gt2silvaosd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jianghu66.top/Article/details/gt2meihavrg.html

[T48] Perl：正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2meuowjhr.html

$s =~ s/old/new/g;
来源：http://dali.zhongyouzk.top/Article/details/gt2ytruwmrs.html

[T49] Perl：函数
来源：http://dali.yueranfly.top/Article/details/gt2jxnrhyxk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gt2nnxauecv.html

[T50] Perl：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2izfafafb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.dianchejie.cn/Article/details/gt2lernwzso.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ehwqpu.com/Article/details/gt2fyhxrdhg.html

[T51] Scala：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2ysyktepy.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wnexayme.html

[T52] Scala：变量
来源：http://dali.nwbrower.top/Article/details/gt2klzlyftq.html

val a = 1;  var b = 2
来源：http://dali.andypj.xyz/Article/details/gt2speapnin.html

[T53] Scala：字符串插值
来源：http://dali.yueranfly.top/Article/details/gt2pzvffvsn.html

s"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gt2pyjpmjne.html

[T54] Scala：集合映射
来源：http://dali.sweek.top/Article/details/gt2vhecxsas.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.andypj.xyz/Article/details/gt2ihoxqmmk.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ppouhlnq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rahvfbsm.html

[T56] Scala：样例类
来源：http://dali.chenzaomai.com/Article/details/gt2shpjcmzo.html

case class User(name: String, age: Int)
来源：http://dali.hywenlv.cn/Article/details/gt2sthwkujo.html

[T57] Scala：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gt2pgrgfoig.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.meibo888.top/Article/details/gt2oigchnfw.html

[T58] Scala：函数定义
来源：http://dali.hnxiangtu.top/Article/details/gt2dgbisklk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhoulong.xyz/Article/details/gt2bxgmccnc.html

[T59] Scala：循环
来源：http://dali.yj20258888.top/Article/details/gt2pprlxuio.html

for (i <- 1 to 10) println(i)
来源：http://dali.cdnleiting.top/Article/details/gt2whaoaeoo.html

[T60] Scala：折叠
来源：http://dali.wangshuangyany.cn/Article/details/gt2qgbnnvbm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yueranfly.top/Article/details/gt2nbzzcryr.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2filflbsi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuanzhike.top/Article/details/gt2ybndkhyu.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2kneokzzu.html

[U01] Py：创建虚拟环境
来源：http://dali.chenzaomai.com/Article/details/gt2idbzgvcr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinqigfzy.top/Article/details/gt2xcjxkees.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yanxiufei.cn/Article/details/gt2fbmazmpb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guannengcc.top/Article/details/gt2hqxjljro.html

[U03] Py：加载 .env 配置
来源：http://dali.gaohongyu789.top/Article/details/gt2bnyhyrxc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenlongwang.top/Article/details/gt2fnxyhjzg.html

[U04] Py：变量调试打印
来源：http://dali.cashguo.top/Article/details/gt2jttvqvwr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj20258.top/Article/details/gt2zpcveyzx.html

[U05] Py：列表去重且保序
来源：http://dali.haohaochexian.top/Article/details/gt2hhapmnoe.html

list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gt2ouavwidj.html

[U06] Py：合并两个字典
来源：http://dali.yj202588.top/Article/details/gt2expoprck.html

{**a, **b}
来源：http://dali.jlsjyb.cn/Article/details/gt2gxknbwdi.html

[U07] Py：反转字典键值
来源：http://dali.dashuyun.cn/Article/details/gt2lvodehjc.html

{v: k for k, v in d.items()}
来源：http://dali.tian-w.cn/Article/details/gt2bsxxqprl.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkysanm.html

[y for x in nested for y in x]
来源：http://dali.fengsongda.top/Article/details/gt2njqkslru.html

[U09] Py：字典取最大值的键
来源：http://dali.yueranfly.top/Article/details/gt2yalynoex.html

max(d, key=d.get)
来源：http://dali.ydzc1.top/Article/details/gt2mfyverrr.html

[U10] Py：按值排序字典
来源：http://dali.fzhhl.top/Article/details/gt2vyzkmvoi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yueranfly.top/Article/details/gt2qhsbpsio.html

[U11] Py：生成器表达式
来源：http://dali.xylfe.cn/Article/details/gt2yfzshepf.html

(x * 2 for x in arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gtkdtfcd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.mhx1999.top/Article/details/gt2qonblhpm.html

Counter(arr).most_common(3)
来源：http://dali.ivvv.top/Article/details/gt2qngiwlru.html

[U13] Py：固定长度队列
来源：http://dali.nanxuanxn.top/Article/details/gt2bcaqswxu.html

deque(maxlen=10)
来源：http://dali.yj202588.top/Article/details/gt2xysmgymm.html

[U14] Py：分组收集到列表
来源：http://dali.hammf.cn/Article/details/gt2jfevetci.html

defaultdict(list)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kusmthjo.html

[U15] Py：高精度计时
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aixgmttc.html

t = time.perf_counter()
来源：http://dali.jyoumei.cn/Article/details/gt2pgjuqzby.html

[U16] Py：命令行参数解析
来源：http://dali.jyoumei.cn/Article/details/gt2fuvpitso.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.9152youxi.cn/Article/details/gt2kicbqofl.html

[U17] Py：初始化日志
来源：http://dali.yangfankeji.com/Article/details/gt2buvfetti.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sysykeji.top/Article/details/gt2ogkkfioz.html

[U18] Py：预编译正则
来源：http://dali.zhixingplan.top/Article/details/gt2habqywxg.html

pat = re.compile(r"\d+")
来源：http://dali.zycfv.cn/Article/details/gt2ctokqlwj.html

[U19] Py：正则替换带回调
来源：http://dali.gogol.net.cn/Article/details/gt2yjevcwmk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.dianchejie.cn/Article/details/gt2wdeaclpv.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpmzago.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sufxvd.cn/Article/details/gt2wlunazpu.html

[U21] Py：自定义上下文管理器
来源：http://dali.redwolf501.top/Article/details/gt2zpteywvi.html

@contextlib.contextmanager
来源：http://dali.fzhhl.top/Article/details/gt2vbbamexj.html

[U22] Py：矩阵转置
来源：http://dali.daxiang520.top/Article/details/gt2kzhzjffl.html

list(zip(*m))
来源：http://dali.nanxinkj.top/Article/details/gt2mftupbzz.html

[U23] Py：分块读取大文件
来源：http://dali.cqqwz.cn/Article/details/gt2ocqymzcy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenzaomai.com/Article/details/gt2urgzvurm.html

[U24] Py：路径操作
来源：http://dali.svipenyu.cn/Article/details/gt2rgpxwgtr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2blhurlcg.html

[U25] Py：CSV 按字典读
来源：http://dali.yj20258888.top/Article/details/gt2ymnqzlwx.html

csv.DictReader(f)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzsnmhpm.html

[U26] Py：并发下载
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2riucgwtz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zdqjudy.top/Article/details/gt2vbdsdclt.html

[U27] Py：异步 HTTP
来源：http://dali.andypj.xyz/Article/details/gt2qnhqiicn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hysaishi.cn/Article/details/gt2oaprhenp.html

[U28] Py：类型别名
来源：http://dali.yonumen.top/Article/details/gt2lrqkwxhq.html

UserId = int
来源：http://dali.xinyue.icu/Article/details/gt2lnsfooja.html

[U29] Py：属性校验
来源：http://dali.shzxlz.cn/Article/details/gt2wqdqlyuh.html

@property 与 @x.setter 配合
来源：http://dali.nwbrower.top/Article/details/gt2hbtdwlfj.html

[U30] Py：数据类
来源：http://dali.nwbrower.top/Article/details/gt2kjzhvzfo.html

@dataclass(slots=True)
来源：http://dali.zhixingplan.top/Article/details/gt2ibqliehg.html

[U31] Py：单测
来源：http://dali.quarkkingdee.top/Article/details/gt2zhwfsdfc.html

python -m pytest -q
来源：http://dali.jinqigufen.top/Article/details/gt2csvmipgk.html

[U32] Py：代码格式化
来源：http://dali.aizwys.cn/Article/details/gt2ioqkfknq.html

ruff format . && ruff check --fix .
来源：http://dali.wangdashe.top/Article/details/gt2enibximv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2znagxfdj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenzaomai.com/Article/details/gt2qaqjadrd.html

[U34] Py：判断编码
来源：http://dali.mhx1999.top/Article/details/gt2ndunxyxz.html

chardet.detect(raw)
来源：http://dali.yanxiufei.cn/Article/details/gt2oahhkwmf.html

[U35] Py：发送邮件
来源：http://dali.jqgufenzy.top/Article/details/gt2bcymizck.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xuanzx.com/Article/details/gt2lqfqclft.html

[U36] Py：定时任务
来源：http://dali.nanxinkj.top/Article/details/gt2wilecjek.html

schedule.every(10).minutes.do(job)
来源：http://dali.xuanzx.com/Article/details/gt2qkdciemx.html

[U37] Py：读写 Excel
来源：http://dali.ybcxt.top/Article/details/gt2nwftsfqx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.fengsongda.top/Article/details/gt2wvjegrcg.html

[U38] Py：获取脚本所在目录
来源：http://dali.sufxvd.cn/Article/details/gt2rrujvoxn.html

Path(__file__).resolve().parent
来源：http://dali.hfpthk.cn/Article/details/gt2fqsuhswu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhixingplan.top/Article/details/gt2jdcfqvnc.html

sys.stdout.isatty()
来源：http://dali.ehwqpu.com/Article/details/gt2wscpmdqv.html

[U40] Py：打印到标准错误
来源：http://dali.xuetiantiany.cn/Article/details/gt2vbvmkdlu.html

print("err", file=sys.stderr)
来源：http://dali.shuidangran.top/Article/details/gt2cwfdngiy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.wangdashe.top/Article/details/gt2zwdekago.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.dianchejie.cn/Article/details/gt2eswbuoud.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.quarkkingdee.top/Article/details/gt2cgtllnjb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.pycfn.com/Article/details/gt2rghqzcno.html

[U43] PHP：声明命名空间
来源：http://dali.quarkkingdee.top/Article/details/gt2pmihvevf.html

namespace App\Http;
来源：http://dali.zhiwuduotai.top/Article/details/gt2sjtkasif.html

[U44] PHP：开启严格类型
来源：http://dali.zdqjudy.top/Article/details/gt2ycpsbyxn.html

declare(strict_types=1);
来源：http://dali.tianlin.xyz/Article/details/gt2avdfavxx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.aibaodan.cn/Article/details/gt2yxjblqfh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nsxqwzmi.html

[U46] PHP：可空类型
来源：http://dali.snrcjt.cn/Article/details/gt2kiuvffmb.html

?string $name = null
来源：http://dali.sysykeji.top/Article/details/gt2ijtewrig.html


<!-- 参考信息 -->