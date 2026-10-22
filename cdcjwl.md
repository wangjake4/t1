代发 wailian999

int main(int argc, char **argv)
来源：http://dali.havefunace.top/Article/details/gt2lrvpoapp.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gt2zcpedqoo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gt2xhgsmvsx.html

[S20] C：二分查找
来源：http://dali.316326.xyz/Article/details/gt2xbqqcmwn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.smart0.xyz/Article/details/gt2qxzqdmyv.html

[S21] C：字符类别判断
来源：http://dali.ydzc1.top/Article/details/gt2hmglbxzy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj202588.top/Article/details/gt2vgjvghpa.html

[S22] C：字符串转数字
来源：http://dali.tanke756.top/Article/details/gt2lbwwkxhm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuanzx.com/Article/details/gt2gnwxmjtf.html

[S23] C：随机数
来源：http://dali.bjfxy.top/Article/details/gt2dgxcpumx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuxming.cn/Article/details/gt2zvrpkkqk.html

[S24] C：获取本地时间
来源：http://dali.snrcjt.cn/Article/details/gt2adklgwzb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangdashe.top/Article/details/gt2adfhvais.html

[S25] C：内存拷贝
来源：http://dali.svipenyu.cn/Article/details/gt2ttivcnph.html

memcpy(dst, src, n);
来源：http://dali.jqgufenzy.top/Article/details/gt2movhbwro.html

[S26] C：内存清零
来源：http://dali.yonumen.top/Article/details/gt2mrzzpcbw.html

memset(a, 0, sizeof a);
来源：http://dali.quarkkingdee.top/Article/details/gt2pcmihbco.html

[S27] C：定义常量
来源：http://dali.tianlin.xyz/Article/details/gt2pgljmgyd.html

const double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gt2goiwbpql.html

[S28] C：静态变量
来源：http://dali.smart0.xyz/Article/details/gt2ffhmbhml.html

static int counter = 0;
来源：http://dali.pengpengdd.cyou/Article/details/gt2uervkyrn.html

[S29] C：变参函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2conimbca.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbewvyct.html

[S30] C：头文件保护
来源：http://dali.yueranfly.top/Article/details/gt2yxwbfveg.html

#ifndef X_H
来源：http://dali.hysaishi.cn/Article/details/gt2upgqjolo.html

#define X_H
来源：http://dali.jianghu66.top/Article/details/gt2ipdjlkou.html

#endif
来源：http://dali.tanke756.top/Article/details/gt2zwsngawr.html

[S31] C++：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2naldhjbq.html

#include <iostream>
来源：http://dali.yanxiufei.cn/Article/details/gt2kkxpzkas.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenlongwang.top/Article/details/gt2yamlxyyr.html

[S32] C++：字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2eowpmivj.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigufen.top/Article/details/gt2caxxxlkl.html

[S33] C++：vector 增删
来源：http://dali.bjfxy.top/Article/details/gt2pheqstyc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aibaodan.cn/Article/details/gt2gvghhpsh.html

[S34] C++：遍历 vector
来源：http://dali.jinqigufen.top/Article/details/gt2teftmsnk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.andypj.xyz/Article/details/gt2jwlrwqer.html

[S35] C++：map
来源：http://dali.svipenyu.cn/Article/details/gt2mwuljnem.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2jbczsvdy.html

[S36] C++：unordered_map
来源：http://dali.fengsongda.top/Article/details/gt2wtbdepna.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2gjjmbbit.html

[S37] C++：set
来源：http://dali.fzhhl.top/Article/details/gt2gcpntkor.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2chehlcbn.html

[S38] C++：排序
来源：http://dali.guowangkeji.top/Article/details/gt2mskrwkhp.html

std::sort(v.begin(), v.end());
来源：http://dali.andypj.xyz/Article/details/gt2aoffiiar.html

[S39] C++：自定义比较器排序
来源：http://dali.tian-w.cn/Article/details/gt2lodlfral.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hywenlv.cn/Article/details/gt2zcnsdbxx.html

[S40] C++：查找元素
来源：http://dali.nwbrower.top/Article/details/gt2ixyxxcom.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.iojbl.cn/Article/details/gt2myovrecz.html

[S41] C++：类与构造函数
来源：http://dali.jyoumei.cn/Article/details/gt2gikitnsz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mvufhliw.html

[S42] C++：继承与虚函数
来源：http://dali.gotoacloud.top/Article/details/gt2gxciazxv.html

class B : public Base { public: void f() override {} };
来源：http://dali.cashguo.top/Article/details/gt2nxoywoac.html

[S43] C++：智能指针
来源：http://dali.tian-w.cn/Article/details/gt2mrdxnxch.html

auto p = std::make_unique<int>(5);
来源：http://dali.zycfv.cn/Article/details/gt2znbtacsz.html

[S44] C++：引用传参
来源：http://dali.sweek.top/Article/details/gt2fltxbkee.html

void inc(int &x) { ++x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rtbczygv.html

[S45] C++：lambda
来源：http://dali.gogol.net.cn/Article/details/gt2xsdlslcm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mtynyftm.html

[S46] C++：函数模板
来源：http://dali.chenjidiqi.icu/Article/details/gt2mcmpffij.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2mogkyfez.html

[S47] C++：结构化绑定遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2edfzqpbj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zdqjudy.top/Article/details/gt2bbtgypie.html

[S48] C++：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gt2rmhpaove.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guannengcc.top/Article/details/gt2lehtmxve.html

while (std::getline(in, line)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hsccbnuu.html

[S49] C++：写文件
来源：http://dali.dianchejie.cn/Article/details/gt2avgldhad.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tian-w.cn/Article/details/gt2heblaldx.html

[S50] C++：格式化数字
来源：http://dali.xinyue.icu/Article/details/gt2hjlncrbs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2smtuakcn.html

[S51] C++：显式类型转换
来源：http://dali.gogol.net.cn/Article/details/gt2oyztoxwp.html

static_cast<double>(a) / b
来源：http://dali.yj20258888.top/Article/details/gt2ashcglze.html

[S52] C++：const 与 noexcept
来源：http://dali.chenlongwang.top/Article/details/gt2dsnvwztx.html

int size() const noexcept { return n_; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ahtrerxo.html

[S53] C++：移动语义
来源：http://dali.yuxming.cn/Article/details/gt2zhhpnofe.html

std::vector<int> w = std::move(v);
来源：http://dali.zhongyouzk.top/Article/details/gt2vpwdagjs.html

[S54] C++：异常处理
来源：http://dali.zhixingplan.top/Article/details/gt2reynjlnr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhixingplan.top/Article/details/gt2tmirgmbx.html

[S55] C++：结构化绑定
来源：http://dali.ybcxt.top/Article/details/gt2uiylkvbn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.0kj1m.cn/Article/details/gt2wdctoyzl.html

[S56] C++：optional
来源：http://dali.chenjidiqi.icu/Article/details/gt2dqbzguqz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.birdmap.top/Article/details/gt2ouvyjvhe.html

[S57] C++：编译期常量
来源：http://dali.ppjwa.cn/Article/details/gt2ippjeziy.html

constexpr int N = 10;
来源：http://dali.yueranfly.top/Article/details/gt2flqmiupp.html

[S58] C++：命名空间
来源：http://dali.gotoacloud.top/Article/details/gt2nlaapkwo.html

namespace ns { int f() { return 1; } }
来源：http://dali.yongpay.top/Article/details/gt2gvghnjau.html

[S59] C++：静态断言
来源：http://dali.guannengcc.top/Article/details/gt2yatvjlqg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenlongwang.top/Article/details/gt2fttarbww.html

[S60] C++：遍历并删除元素
来源：http://dali.shzxlz.cn/Article/details/gt2hbtvbiym.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigufen.top/Article/details/gt2tanvatom.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2naajwhfe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sysykeji.top/Article/details/gt2xfrmqlxb.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2qgovwenr.html

[T01] Kotlin：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2qhirtgfn.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gt2gvdnscri.html

[T02] Kotlin：变量
来源：http://dali.quarkkingdee.top/Article/details/gt2ffehxcgv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj202588.top/Article/details/gt2zwaykypv.html

[T03] Kotlin：字符串模板
来源：http://dali.zdqjudy.top/Article/details/gt2vcfvllee.html

"值: $b"
来源：http://dali.daria6918.cn/Article/details/gt2iitpzvlv.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gt2nnkiobiv.html

val n: String? = null;  n?.length
来源：http://dali.tanke756.top/Article/details/gt2bsaaexhj.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2npybupzk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuetiantiany.cn/Article/details/gt2abugjalo.html

[T06] Kotlin：集合映射
来源：http://dali.bjfxy.top/Article/details/gt2poggqajh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yongpay.top/Article/details/gt2tdjpmvsf.html

[T07] Kotlin：集合过滤
来源：http://dali.xziqi.cn/Article/details/gt2ajwgvirh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxinkj.top/Article/details/gt2ayuwyuot.html

[T08] Kotlin：数据类
来源：http://dali.andypj.xyz/Article/details/gt2znvusgxs.html

data class User(val name: String, val age: Int)
来源：http://dali.zycfv.cn/Article/details/gt2wxctrncr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhixingplan.top/Article/details/gt2kjcrxajq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2snddpxfe.html

[T10] Kotlin：默认参数
来源：http://dali.haohaochexian.top/Article/details/gt2ifycrwne.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhixingplan.top/Article/details/gt2ubkfuaxx.html

[T11] Kotlin：协程
来源：http://dali.hammf.cn/Article/details/gt2umlmpgtp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sysykeji.top/Article/details/gt2wiwimtzu.html

[T12] Kotlin：解构声明
来源：http://dali.zycfv.cn/Article/details/gt2flkqkkza.html

val (a, b) = Pair(1, 2)
来源：http://dali.daria6918.cn/Article/details/gt2tlyaorid.html

[T13] Kotlin：只读 Map
来源：http://dali.ydzc1.top/Article/details/gt2qggldroj.html

val m = mapOf("a" to 1)
来源：http://dali.xziqi.cn/Article/details/gt2cmrguduo.html

[T14] Kotlin：循环
来源：http://dali.redwolf501.top/Article/details/gt2gxoqhout.html

for (i in 1..10) println(i)
来源：http://dali.shuidangran.top/Article/details/gt2fzrijcpy.html

[T15] Kotlin：接口
来源：http://dali.ehwqpu.com/Article/details/gt2fxualzkj.html

interface Shape { fun area(): Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cqwnhmjp.html

[T16] Swift：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2krwtojmw.html

print("Hello")
来源：http://dali.gogol.net.cn/Article/details/gt2cizynuyg.html

[T17] Swift：变量与常量
来源：http://dali.feifeiyinyue.top/Article/details/gt2pduvbwkc.html

var a = 1;  let b = 2
来源：http://dali.hysaishi.cn/Article/details/gt2uegpakfd.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvzrann.html

"值: \(b)"
来源：http://dali.vqdsnc.cn/Article/details/gt2tegjbilv.html

[T19] Swift：可选绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ygozgtzl.html

if let n = opt { print(n) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ihtvsbeu.html

[T20] Swift：数组操作
来源：http://dali.jinqigufen.top/Article/details/gt2awyqqyal.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgufenzy.top/Article/details/gt2uiwrcawp.html

[T21] Swift：遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2oztiotui.html

for x in a { print(x) }
来源：http://dali.tanke756.top/Article/details/gt2fgkpmmop.html

[T22] Swift：字典
来源：http://dali.svipenyu.cn/Article/details/gt2adrdaxox.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sweek.top/Article/details/gt2puqnpdef.html

[T23] Swift：函数
来源：http://dali.hnqzz.top/Article/details/gt2kfntfcic.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuanzhike.top/Article/details/gt2agymrgqw.html

[T24] Swift：闭包
来源：http://dali.sufxvd.cn/Article/details/gt2bimcnvpu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258.top/Article/details/gt2niupgice.html

[T25] Swift：结构体
来源：http://dali.hywenlv.cn/Article/details/gt2scvozwxl.html

struct P { var x: Int }
来源：http://dali.gotoacloud.top/Article/details/gt2rquazcus.html

[T26] Swift：类与重写
来源：http://dali.hnqzz.top/Article/details/gt2znijoacq.html

class A: Base { override func f() {} }
来源：http://dali.guowangkeji.top/Article/details/gt2wvknpvgt.html

[T27] Swift：错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dkhdwcci.html

do { try f() } catch { print(error) }
来源：http://dali.fzhhl.top/Article/details/gt2mxvekrle.html

[T28] Swift：枚举
来源：http://dali.zhixingplan.top/Article/details/gt2ulsfidqf.html

enum Color { case red, green }
来源：http://dali.nwbrower.top/Article/details/gt2eftxqfpn.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxinkj.top/Article/details/gt2pmyazefn.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gt2bzpfzuke.html

[T30] Swift：协议
来源：http://dali.jyoumei.cn/Article/details/gt2jwitejwt.html

protocol Shape { func area() -> Double }
来源：http://dali.pengpengdd.cyou/Article/details/gt2puoakjyo.html

[T31] Lua：Hello World
来源：http://dali.birdmap.top/Article/details/gt2npganbab.html

print("Hello")
来源：http://dali.9152youxi.cn/Article/details/gt2oyrknoyv.html

[T32] Lua：局部变量
来源：http://dali.cashguo.top/Article/details/gt2lbbafpno.html

local a = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eniyykaj.html

[T33] Lua：表（数组）
来源：http://dali.cheryme.top/Article/details/gt2kgyxrwnk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangdashe.top/Article/details/gt2lozqjdyi.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zjqadqea.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qferbwyg.html

[T35] Lua：字典表
来源：http://dali.daria6918.cn/Article/details/gt2ihttgrjt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.svipenyu.cn/Article/details/gt2wyqjnfwg.html

[T36] Lua：函数
来源：http://dali.yueranfly.top/Article/details/gt2povnokrn.html

function add(a, b) return a + b end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2umkigomr.html

[T37] Lua：字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gt2gvaoillx.html

"a" .. "b"
来源：http://dali.ivvv.top/Article/details/gt2kucxazys.html

[T38] Lua：条件
来源：http://dali.yj20258888.top/Article/details/gt2zjfkceec.html

if x > 0 then print("正") end
来源：http://dali.hnqzz.top/Article/details/gt2fijqlgrq.html

[T39] Lua：模式匹配
来源：http://dali.guannengcc.top/Article/details/gt2fdlskjzv.html

string.find(s, "%d+")
来源：http://dali.jinqigfzy.top/Article/details/gt2xpiowmbn.html

[T40] Lua：元表
来源：http://dali.cucudq.cn/Article/details/gt2bsjajfvy.html

setmetatable({}, { __index = base })
来源：http://dali.snrcjt.cn/Article/details/gt2fmmnmapy.html

[T41] Perl：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2wyfvkdro.html

print "Hello\n";
来源：http://dali.tanke756.top/Article/details/gt2znddhast.html

[T42] Perl：变量类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2gswgnwmx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.haohaochexian.top/Article/details/gt2wueddnzg.html

[T43] Perl：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gt2owecffby.html

"值: $a"
来源：http://dali.pycfn.com/Article/details/gt2itkososn.html

[T44] Perl：条件
来源：http://dali.xziqi.cn/Article/details/gt2gdiqaznk.html

if ($a > 0) { print "正"; }
来源：http://dali.hnqzz.top/Article/details/gt2lbpgodhl.html

[T45] Perl：数组遍历
来源：http://dali.cashguo.top/Article/details/gt2qxqnwlds.html

for my $x (@arr) { print $x; }
来源：http://dali.cdnleiting.top/Article/details/gt2tvtpufyz.html

[T46] Perl：哈希操作
来源：http://dali.316326.xyz/Article/details/gt2ufpoinyx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jiagoushi.top/Article/details/gt2alezmcto.html

[T47] Perl：正则捕获
来源：http://dali.nwbrower.top/Article/details/gt2mvpnzeqv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sweek.top/Article/details/gt2ntaaopnn.html

[T48] Perl：正则替换
来源：http://dali.yueranfly.top/Article/details/gt2hetnzfol.html

$s =~ s/old/new/g;
来源：http://dali.gzhubu.top/Article/details/gt2zdxzzwlv.html

[T49] Perl：函数
来源：http://dali.tanke756.top/Article/details/gt2vhvwvygo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2yfeclbxw.html

[T50] Perl：逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2ygwdputs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenzaomai.com/Article/details/gt2qrnrgjre.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cucudq.cn/Article/details/gt2hepolpex.html

[T51] Scala：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2zlkkirln.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gt2lmfebhyf.html

[T52] Scala：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ekshxdgw.html

val a = 1;  var b = 2
来源：http://dali.nanxuanxn.top/Article/details/gt2mlxhrxil.html

[T53] Scala：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gt2msbeiwyw.html

s"值: $b"
来源：http://dali.yonumen.top/Article/details/gt2gksrnbnm.html

[T54] Scala：集合映射
来源：http://dali.tianlin.xyz/Article/details/gt2vkgdckbp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhengqikj.top/Article/details/gt2qtdvwmdh.html

[T55] Scala：集合过滤
来源：http://dali.cheryme.top/Article/details/gt2pgkxruxq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.haohaochexian.top/Article/details/gt2lgjywwqw.html

[T56] Scala：样例类
来源：http://dali.zhoulong.xyz/Article/details/gt2qapvwela.html

case class User(name: String, age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gt2jmujvmqe.html

[T57] Scala：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gt2jjyxeskx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yvedp.cn/Article/details/gt2lszjabut.html

[T58] Scala：函数定义
来源：http://dali.0kj1m.cn/Article/details/gt2aoiytfma.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.iojbl.cn/Article/details/gt2mzpkqvuc.html

[T59] Scala：循环
来源：http://dali.hnxiangtu.top/Article/details/gt2tcxxezpg.html

for (i <- 1 to 10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jkaavfhj.html

[T60] Scala：折叠
来源：http://dali.cashguo.top/Article/details/gt2tzhasnru.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yonumen.top/Article/details/gt2dpkagtbb.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2nowkbrcn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2awstsxaa.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dtighkvt.html

[U01] Py：创建虚拟环境
来源：http://dali.tian-w.cn/Article/details/gt2dwpqnkcu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jianghu66.top/Article/details/gt2adybfmcf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hywenlv.cn/Article/details/gt2jhxiwdmw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cucudq.cn/Article/details/gt2cjldgyjq.html

[U03] Py：加载 .env 配置
来源：http://dali.yongpay.top/Article/details/gt2leuwjnns.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hywenlv.cn/Article/details/gt2mnwzvbnu.html

[U04] Py：变量调试打印
来源：http://dali.haohaochexian.top/Article/details/gt2njvvkwut.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yongpay.top/Article/details/gt2oaqeuypx.html

[U05] Py：列表去重且保序
来源：http://dali.gotoacloud.top/Article/details/gt2scurquuz.html

list(dict.fromkeys(arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kzbqfbys.html

[U06] Py：合并两个字典
来源：http://dali.yueranfly.top/Article/details/gt2lagcgaed.html

{**a, **b}
来源：http://dali.cdnleiting.top/Article/details/gt2qhicpaul.html

[U07] Py：反转字典键值
来源：http://dali.yongpay.top/Article/details/gt2lenkqyoe.html

{v: k for k, v in d.items()}
来源：http://dali.guannengcc.top/Article/details/gt2afaieibg.html

[U08] Py：展平二维列表
来源：http://dali.bjfxy.top/Article/details/gt2rzonctvt.html

[y for x in nested for y in x]
来源：http://dali.xylfe.cn/Article/details/gt2gmnewudp.html

[U09] Py：字典取最大值的键
来源：http://dali.ehwqpu.com/Article/details/gt2oxesldao.html

max(d, key=d.get)
来源：http://dali.yj202588.top/Article/details/gt2omlfwgdj.html

[U10] Py：按值排序字典
来源：http://dali.jiagoushi.top/Article/details/gt2wowkyokd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cqqwz.cn/Article/details/gt2ykakxzoe.html

[U11] Py：生成器表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2mlyvixpc.html

(x * 2 for x in arr)
来源：http://dali.tianlin.xyz/Article/details/gt2bmmlyxlm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shuidangran.top/Article/details/gt2kksqpkdj.html

Counter(arr).most_common(3)
来源：http://dali.daxiang520.top/Article/details/gt2wlrjmpmq.html

[U13] Py：固定长度队列
来源：http://dali.daxiang520.top/Article/details/gt2aujfpnvq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnoefkh.html

[U14] Py：分组收集到列表
来源：http://dali.cdnleiting.top/Article/details/gt2wvwfbsvw.html

defaultdict(list)
来源：http://dali.svipenyu.cn/Article/details/gt2odpkryjh.html

[U15] Py：高精度计时
来源：http://dali.dianchejie.cn/Article/details/gt2olzrphtw.html

t = time.perf_counter()
来源：http://dali.nanxuanxn.top/Article/details/gt2bbtwgmic.html

[U16] Py：命令行参数解析
来源：http://dali.aizwys.cn/Article/details/gt2oznefasx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jlsjyb.cn/Article/details/gt2wsxhnawr.html

[U17] Py：初始化日志
来源：http://dali.nanxinkj.top/Article/details/gt2rxwukecc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.fengsongda.top/Article/details/gt2sjhxzuue.html

[U18] Py：预编译正则
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nyemavvz.html

pat = re.compile(r"\d+")
来源：http://dali.hfpthk.cn/Article/details/gt2tiyfuiwi.html

[U19] Py：正则替换带回调
来源：http://dali.ydzc1.top/Article/details/gt2oxzaoxin.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nanxinkj.top/Article/details/gt2reidivol.html

[U20] Py：缓存函数结果
来源：http://dali.pengpengdd.cyou/Article/details/gt2lovctlfr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.316326.xyz/Article/details/gt2muborrna.html

[U21] Py：自定义上下文管理器
来源：http://dali.xziqi.cn/Article/details/gt2elczsdku.html

@contextlib.contextmanager
来源：http://dali.cucudq.cn/Article/details/gt2avnubflj.html

[U22] Py：矩阵转置
来源：http://dali.yj202588.top/Article/details/gt2xunhqyam.html

list(zip(*m))
来源：http://dali.tanke756.top/Article/details/gt2mkkmwsen.html

[U23] Py：分块读取大文件
来源：http://dali.daria6918.cn/Article/details/gt2vkphdfng.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sxryk.cn/Article/details/gt2pvpnvcgl.html

[U24] Py：路径操作
来源：http://dali.nwbrower.top/Article/details/gt2todorizn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gt2erzyxntv.html

[U25] Py：CSV 按字典读
来源：http://dali.cdnleiting.top/Article/details/gt2bnsdhues.html

csv.DictReader(f)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qeibgfvx.html

[U26] Py：并发下载
来源：http://dali.yanxiufei.cn/Article/details/gt2ydclgrhm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vsdqihqk.html

[U27] Py：异步 HTTP
来源：http://dali.kuanghao11.cn/Article/details/gt2fndjxegv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.nanxinkj.top/Article/details/gt2foyakszt.html

[U28] Py：类型别名
来源：http://dali.sufxvd.cn/Article/details/gt2sukzmyih.html

UserId = int
来源：http://dali.bjfxy.top/Article/details/gt2xhpqsuva.html

[U29] Py：属性校验
来源：http://dali.jiagoushi.top/Article/details/gt2akirdjrk.html

@property 与 @x.setter 配合
来源：http://dali.jinqigfzy.top/Article/details/gt2ukwhlqcu.html

[U30] Py：数据类
来源：http://dali.jqgfzy.top/Article/details/gt2xmbrribx.html

@dataclass(slots=True)
来源：http://dali.zhongyouzk.top/Article/details/gt2epppzufl.html

[U31] Py：单测
来源：http://dali.jianghu66.top/Article/details/gt2qoradqkn.html

python -m pytest -q
来源：http://dali.daria6918.cn/Article/details/gt2nxbcassz.html

[U32] Py：代码格式化
来源：http://dali.haohaochexian.top/Article/details/gt2foovwxtc.html

ruff format . && ruff check --fix .
来源：http://dali.fengsongda.top/Article/details/gt2mcsfelas.html

[U33] Py：打包发布
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xphfaxcw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mrlnfrqr.html

[U34] Py：判断编码
来源：http://dali.jinqigfzy.top/Article/details/gt2arvlvpyn.html

chardet.detect(raw)
来源：http://dali.dashuyun.cn/Article/details/gt2jbhqjfqu.html

[U35] Py：发送邮件
来源：http://dali.sysykeji.top/Article/details/gt2mdmrzuhk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ngjwrwij.html

[U36] Py：定时任务
来源：http://dali.zhongyouzk.top/Article/details/gt2iankpofm.html

schedule.every(10).minutes.do(job)
来源：http://dali.jianghu66.top/Article/details/gt2nlpsqrkn.html

[U37] Py：读写 Excel
来源：http://dali.cucudq.cn/Article/details/gt2udtqwsbe.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gotoacloud.top/Article/details/gt2ovfqufmj.html

[U38] Py：获取脚本所在目录
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mltxxymn.html

Path(__file__).resolve().parent
来源：http://dali.sufxvd.cn/Article/details/gt2amtollcs.html

[U39] Py：判断是否在交互环境
来源：http://dali.tian-w.cn/Article/details/gt2ahiassos.html

sys.stdout.isatty()
来源：http://dali.shzxlz.cn/Article/details/gt2dtbpcjud.html

[U40] Py：打印到标准错误
来源：http://dali.iojbl.cn/Article/details/gt2zzllwoue.html

print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fnntfktl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.tian-w.cn/Article/details/gt2tjwqbojs.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.andypj.xyz/Article/details/gt2fayzykwr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhiwuduotai.top/Article/details/gt2syqewjss.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xinyue.icu/Article/details/gt2lpwunfvf.html


<!-- 参考信息 -->