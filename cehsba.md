代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gotoacloud.top/Article/details/gt2mpefcruq.html

[S25] C：内存拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rmbujxts.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gt2dxfnuuus.html

[S26] C：内存清零
来源：http://dali.andypj.xyz/Article/details/gt2haunakxo.html

memset(a, 0, sizeof a);
来源：http://dali.9152youxi.cn/Article/details/gt2kncbhpml.html

[S27] C：定义常量
来源：http://dali.andypj.xyz/Article/details/gt2bbcxemuo.html

const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2wzklllpr.html

[S28] C：静态变量
来源：http://dali.jqgfzy.top/Article/details/gt2admqmgdh.html

static int counter = 0;
来源：http://dali.dashuyun.cn/Article/details/gt2cqqektse.html

[S29] C：变参函数
来源：http://dali.shuidangran.top/Article/details/gt2ahrszhug.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yongpay.top/Article/details/gt2gbjzhaje.html

[S30] C：头文件保护
来源：http://dali.tianlin.xyz/Article/details/gt2qjtunyhm.html

#ifndef X_H
来源：http://dali.sysykeji.top/Article/details/gt2rezadalb.html

#define X_H
来源：http://dali.zdqjudy.top/Article/details/gt2iusjgzxc.html

#endif
来源：http://dali.iojbl.cn/Article/details/gt2bjzubwnj.html

[S31] C++：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2sdituofq.html

#include <iostream>
来源：http://dali.ybcxt.top/Article/details/gt2jtvibgia.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.mhx1999.top/Article/details/gt2hctxtegd.html

[S32] C++：字符串
来源：http://dali.nwbrower.top/Article/details/gt2beietdrp.html

std::string s = "hi";  s += "!";
来源：http://dali.cucudq.cn/Article/details/gt2khohxmjg.html

[S33] C++：vector 增删
来源：http://dali.yj202588.top/Article/details/gt2zxlvxsbl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xinyue.icu/Article/details/gt2ahnopydx.html

[S34] C++：遍历 vector
来源：http://dali.zhiwuduotai.top/Article/details/gt2tcfyooao.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ydzc1.top/Article/details/gt2byinofze.html

[S35] C++：map
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zgleqaoa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gt2fkzejqgh.html

[S36] C++：unordered_map
来源：http://dali.xylfe.cn/Article/details/gt2oxsizgyy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gt2apzgrsko.html

[S37] C++：set
来源：http://dali.ydzc1.top/Article/details/gt2gkwsrbmr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigfzy.top/Article/details/gt2hxggucef.html

[S38] C++：排序
来源：http://dali.hongshengwenyu.top/Article/details/gt2tughuuho.html

std::sort(v.begin(), v.end());
来源：http://dali.dianchejie.cn/Article/details/gt2coiidnwr.html

[S39] C++：自定义比较器排序
来源：http://dali.tian-w.cn/Article/details/gt2jzxzhgke.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangdashe.top/Article/details/gt2ufrfaqei.html

[S40] C++：查找元素
来源：http://dali.wangdashe.top/Article/details/gt2lutzjdch.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tanke756.top/Article/details/gt2ydgeztip.html

[S41] C++：类与构造函数
来源：http://dali.fengsongda.top/Article/details/gt2ybjxwbhd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.316326.xyz/Article/details/gt2ctdecqjv.html

[S42] C++：继承与虚函数
来源：http://dali.tian-w.cn/Article/details/gt2eorkczga.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangshuangyany.cn/Article/details/gt2ammdovuh.html

[S43] C++：智能指针
来源：http://dali.chenjidiqi.icu/Article/details/gt2gtdwmfbq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjaehwmh.html

[S44] C++：引用传参
来源：http://dali.zhiwuduotai.top/Article/details/gt2kihttwer.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkabvuy.html

[S45] C++：lambda
来源：http://dali.dianchejie.cn/Article/details/gt2tnbebubt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gzhubu.top/Article/details/gt2jjddahdk.html

[S46] C++：函数模板
来源：http://dali.iojbl.cn/Article/details/gt2qikslcfb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ipamdeng.html

[S47] C++：结构化绑定遍历
来源：http://dali.yonumen.top/Article/details/gt2dlkqhyev.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhengqikj.top/Article/details/gt2slmnchic.html

[S48] C++：逐行读文件
来源：http://dali.316326.xyz/Article/details/gt2arujtezv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zdqjudy.top/Article/details/gt2toorltzg.html

while (std::getline(in, line)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vshxquzc.html

[S49] C++：写文件
来源：http://dali.ppjwa.cn/Article/details/gt2qumhcqjh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dashuyun.cn/Article/details/gt2fqyucgfu.html

[S50] C++：格式化数字
来源：http://dali.cqqwz.cn/Article/details/gt2xuwqyqwy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gt2pfxirpnn.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gt2ibulvpdz.html

static_cast<double>(a) / b
来源：http://dali.chenzaomai.com/Article/details/gt2fcdlxcrb.html

[S52] C++：const 与 noexcept
来源：http://dali.haohaochexian.top/Article/details/gt2aadvfvwf.html

int size() const noexcept { return n_; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2pcbbacyi.html

[S53] C++：移动语义
来源：http://dali.yj20258888.top/Article/details/gt2swwjntik.html

std::vector<int> w = std::move(v);
来源：http://dali.gotoacloud.top/Article/details/gt2azksgpyt.html

[S54] C++：异常处理
来源：http://dali.9152youxi.cn/Article/details/gt2xolkyaip.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tanke756.top/Article/details/gt2qfiigotz.html

[S55] C++：结构化绑定
来源：http://dali.chenjidiqi.icu/Article/details/gt2okvrydeq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gotoacloud.top/Article/details/gt2ymzfvbok.html

[S56] C++：optional
来源：http://dali.yongpay.top/Article/details/gt2gmmizjhl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2sqyylwys.html

[S57] C++：编译期常量
来源：http://dali.yueranfly.top/Article/details/gt2dqnrwlpc.html

constexpr int N = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bzhutlbw.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlwkadh.html

namespace ns { int f() { return 1; } }
来源：http://dali.meibo888.top/Article/details/gt2pzkphcvs.html

[S59] C++：静态断言
来源：http://dali.zhoulong.xyz/Article/details/gt2xqcmnozg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gt2jemdfkvy.html

[S60] C++：遍历并删除元素
来源：http://dali.yuxming.cn/Article/details/gt2oxvdpsvi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gt2xonnitbc.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hlstlqri.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xinyue.icu/Article/details/gt2bmhzbabm.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2tcqjjixm.html

[T01] Kotlin：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2ugwuvbwi.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gt2qvlweoqj.html

[T02] Kotlin：变量
来源：http://dali.zhoulong.xyz/Article/details/gt2fhyeadub.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhengqikj.top/Article/details/gt2xvehewdi.html

[T03] Kotlin：字符串模板
来源：http://dali.hysaishi.cn/Article/details/gt2btenedlj.html

"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bmzdbhuq.html

[T04] Kotlin：空安全
来源：http://dali.jqgufenzy.top/Article/details/gt2wcbzctqt.html

val n: String? = null;  n?.length
来源：http://dali.dashuyun.cn/Article/details/gt2fzuqprxm.html

[T05] Kotlin：when 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gt2wxienrxf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shangyingyoupin.top/Article/details/gt2naveuxnv.html

[T06] Kotlin：集合映射
来源：http://dali.316326.xyz/Article/details/gt2fgcltcfg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ymqklybg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2zyisjrdk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yvedp.cn/Article/details/gt2ecerhwoi.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hsaqdtvh.html

data class User(val name: String, val age: Int)
来源：http://dali.jqgufenzy.top/Article/details/gt2kjcngzsi.html

[T09] Kotlin：扩展函数
来源：http://dali.ydzc1.top/Article/details/gt2sxvpruxk.html

fun String.exclaim() = this + "!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mtcoyhet.html

[T10] Kotlin：默认参数
来源：http://dali.zhengqikj.top/Article/details/gt2kmhqihlm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj202588.top/Article/details/gt2cvpexjht.html

[T11] Kotlin：协程
来源：http://dali.aizwys.cn/Article/details/gt2slhwgubt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.9152youxi.cn/Article/details/gt2kxhyczeo.html

[T12] Kotlin：解构声明
来源：http://dali.ehwqpu.com/Article/details/gt2izctdcpf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2lyurirzc.html

[T13] Kotlin：只读 Map
来源：http://dali.yongpay.top/Article/details/gt2phzajaii.html

val m = mapOf("a" to 1)
来源：http://dali.ehwqpu.com/Article/details/gt2bxxopoel.html

[T14] Kotlin：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vqizcbtf.html

for (i in 1..10) println(i)
来源：http://dali.jianghu66.top/Article/details/gt2rsrutywq.html

[T15] Kotlin：接口
来源：http://dali.cashguo.top/Article/details/gt2uexlvgbb.html

interface Shape { fun area(): Double }
来源：http://dali.dianchejie.cn/Article/details/gt2xspkwzsj.html

[T16] Swift：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2pbmfrzeh.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2evhxczbs.html

[T17] Swift：变量与常量
来源：http://dali.zhixingplan.top/Article/details/gt2agguvmtc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aurtzbmr.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gt2oqtvspvc.html

"值: \(b)"
来源：http://dali.zhiwuduotai.top/Article/details/gt2jwiqrwct.html

[T19] Swift：可选绑定
来源：http://dali.tianlin.xyz/Article/details/gt2dcygrkzf.html

if let n = opt { print(n) }
来源：http://dali.iojbl.cn/Article/details/gt2gygtyaam.html

[T20] Swift：数组操作
来源：http://dali.mhx1999.top/Article/details/gt2xzladfdc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xylfe.cn/Article/details/gt2kgbaavgl.html

[T21] Swift：遍历
来源：http://dali.sweek.top/Article/details/gt2sryjoild.html

for x in a { print(x) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjoaophi.html

[T22] Swift：字典
来源：http://dali.quarkkingdee.top/Article/details/gt2adonnkyv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj202588.top/Article/details/gt2lhukover.html

[T23] Swift：函数
来源：http://dali.xylfe.cn/Article/details/gt2afrxapxc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj202588.top/Article/details/gt2ziqswuhz.html

[T24] Swift：闭包
来源：http://dali.shuidangran.top/Article/details/gt2wgufqoli.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.iojbl.cn/Article/details/gt2zdiqhetx.html

[T25] Swift：结构体
来源：http://dali.dianchejie.cn/Article/details/gt2pqngxbay.html

struct P { var x: Int }
来源：http://dali.c1oappe.top/Article/details/gt2suzbnoit.html

[T26] Swift：类与重写
来源：http://dali.haohaochexian.top/Article/details/gt2rzycdrxw.html

class A: Base { override func f() {} }
来源：http://dali.guannengcc.top/Article/details/gt2cjohrgad.html

[T27] Swift：错误处理
来源：http://dali.fzhhl.top/Article/details/gt2kkplrozb.html

do { try f() } catch { print(error) }
来源：http://dali.mhx1999.top/Article/details/gt2vbjmaqat.html

[T28] Swift：枚举
来源：http://dali.yj202588.top/Article/details/gt2wqiphxmv.html

enum Color { case red, green }
来源：http://dali.cqqwz.cn/Article/details/gt2cfwlnpiu.html

[T29] Swift：guard 提前返回
来源：http://dali.xylfe.cn/Article/details/gt2vuxawtpo.html

guard let x = opt else { return }
来源：http://dali.daxiang520.top/Article/details/gt2cnphtyhu.html

[T30] Swift：协议
来源：http://dali.jqgfzy.top/Article/details/gt2dwzxdpjc.html

protocol Shape { func area() -> Double }
来源：http://dali.birdmap.top/Article/details/gt2kqurmrwi.html

[T31] Lua：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2zdfszgmj.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gt2iezuvnlc.html

[T32] Lua：局部变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aemccymm.html

local a = 1
来源：http://dali.wangdashe.top/Article/details/gt2xamfxizq.html

[T33] Lua：表（数组）
来源：http://dali.zhoulong.xyz/Article/details/gt2roewkkee.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hfpthk.cn/Article/details/gt2qezjdrdp.html

[T34] Lua：遍历表
来源：http://dali.nanxuanxn.top/Article/details/gt2qtzjldyx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.mhx1999.top/Article/details/gt2iupjedah.html

[T35] Lua：字典表
来源：http://dali.xylfe.cn/Article/details/gt2wkgfdycx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ydzc1.top/Article/details/gt2vkfxmfil.html

[T36] Lua：函数
来源：http://dali.birdmap.top/Article/details/gt2mwoijdlf.html

function add(a, b) return a + b end
来源：http://dali.pengpengdd.cyou/Article/details/gt2fnklqqpp.html

[T37] Lua：字符串拼接
来源：http://dali.cucudq.cn/Article/details/gt2spnyrfcy.html

"a" .. "b"
来源：http://dali.wangdashe.top/Article/details/gt2bdfymbhm.html

[T38] Lua：条件
来源：http://dali.yj20258.top/Article/details/gt2udapevqo.html

if x > 0 then print("正") end
来源：http://dali.gotoacloud.top/Article/details/gt2bpworeiu.html

[T39] Lua：模式匹配
来源：http://dali.daxiang520.top/Article/details/gt2tuqxbgtm.html

string.find(s, "%d+")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qyrjvaoc.html

[T40] Lua：元表
来源：http://dali.redwolf501.top/Article/details/gt2nvjhhlgo.html

setmetatable({}, { __index = base })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sjimurnq.html

[T41] Perl：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2mqzvexam.html

print "Hello\n";
来源：http://dali.yueranfly.top/Article/details/gt2afuxjsur.html

[T42] Perl：变量类型
来源：http://dali.zhongyouzk.top/Article/details/gt2yuvmranq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jianghu66.top/Article/details/gt2hrcmozyd.html

[T43] Perl：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2oeeuizoy.html

"值: $a"
来源：http://dali.wangshuangyany.cn/Article/details/gt2cssbtdmw.html

[T44] Perl：条件
来源：http://dali.sysykeji.top/Article/details/gt2llaxygii.html

if ($a > 0) { print "正"; }
来源：http://dali.tian-w.cn/Article/details/gt2sfaorjlz.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eytpsbhp.html

for my $x (@arr) { print $x; }
来源：http://dali.yangfankeji.com/Article/details/gt2vfipnimj.html

[T46] Perl：哈希操作
来源：http://dali.quarkkingdee.top/Article/details/gt2dspbfyps.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.pycfn.com/Article/details/gt2tvjpkvia.html

[T47] Perl：正则捕获
来源：http://dali.daxiang520.top/Article/details/gt2yqyhahoe.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.meibo888.top/Article/details/gt2fopnwxln.html

[T48] Perl：正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ifatpygl.html

$s =~ s/old/new/g;
来源：http://dali.mhx1999.top/Article/details/gt2bdmhkwvm.html

[T49] Perl：函数
来源：http://dali.yangfankeji.com/Article/details/gt2egyjaftg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gt2qomlzpsf.html

[T50] Perl：逐行读文件
来源：http://dali.yj202588.top/Article/details/gt2pmrmjapo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgufenzy.top/Article/details/gt2qbgdiaxw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shuidangran.top/Article/details/gt2oeirskrl.html

[T51] Scala：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2rialdwre.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gt2snfhlhrf.html

[T52] Scala：变量
来源：http://dali.dianchejie.cn/Article/details/gt2kalxxspw.html

val a = 1;  var b = 2
来源：http://dali.daria6918.cn/Article/details/gt2gklyumjv.html

[T53] Scala：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gt2xrssyobq.html

s"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gt2kmxmgkhn.html

[T54] Scala：集合映射
来源：http://dali.ydzc1.top/Article/details/gt2kyjmuxkl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhkbwxx.html

[T55] Scala：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2uvrbiewm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guowangkeji.top/Article/details/gt2nnuqdlol.html

[T56] Scala：样例类
来源：http://dali.meibo888.top/Article/details/gt2dgomvmnn.html

case class User(name: String, age: Int)
来源：http://dali.9152youxi.cn/Article/details/gt2lcsbrxgd.html

[T57] Scala：模式匹配
来源：http://dali.cqqwz.cn/Article/details/gt2irecefso.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nhxadyvq.html

[T58] Scala：函数定义
来源：http://dali.daxiang520.top/Article/details/gt2lhowuxcg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sxryk.cn/Article/details/gt2jvconwmz.html

[T59] Scala：循环
来源：http://dali.xziqi.cn/Article/details/gt2xrqsaihu.html

for (i <- 1 to 10) println(i)
来源：http://dali.yuxming.cn/Article/details/gt2ldhipinb.html

[T60] Scala：折叠
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fntdlmlw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hysaishi.cn/Article/details/gt2mhjkfrit.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2bcuntqtu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2uvrqelib.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2tdrsgxae.html

[U01] Py：创建虚拟环境
来源：http://dali.sxryk.cn/Article/details/gt2wzefliqu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pjcrgwli.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cheryme.top/Article/details/gt2jtowvgih.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.316326.xyz/Article/details/gt2xsfmrwrc.html

[U03] Py：加载 .env 配置
来源：http://dali.smart0.xyz/Article/details/gt2ekxqxzbj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tckbpven.html

[U04] Py：变量调试打印
来源：http://dali.hongshengwenyu.top/Article/details/gt2rbtprlwf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shangyingyoupin.top/Article/details/gt2rszishrf.html

[U05] Py：列表去重且保序
来源：http://dali.yueranfly.top/Article/details/gt2uskklwxo.html

list(dict.fromkeys(arr))
来源：http://dali.jqgfzy.top/Article/details/gt2hnzmuobq.html

[U06] Py：合并两个字典
来源：http://dali.yj202588.top/Article/details/gt2jdafykjl.html

{**a, **b}
来源：http://dali.yonumen.top/Article/details/gt2gjfhlkgc.html

[U07] Py：反转字典键值
来源：http://dali.haohaochexian.top/Article/details/gt2sfovdcpc.html

{v: k for k, v in d.items()}
来源：http://dali.yj202588.top/Article/details/gt2gdqqifxl.html

[U08] Py：展平二维列表
来源：http://dali.hnqzz.top/Article/details/gt2rkpnohul.html

[y for x in nested for y in x]
来源：http://dali.kuanghao11.cn/Article/details/gt2oszzvwva.html

[U09] Py：字典取最大值的键
来源：http://dali.redwolf501.top/Article/details/gt2nzbxcokm.html

max(d, key=d.get)
来源：http://dali.sxryk.cn/Article/details/gt2vldzbxdt.html

[U10] Py：按值排序字典
来源：http://dali.wangdashe.top/Article/details/gt2xjvilxdt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gaohongyu789.top/Article/details/gt2egfwjeko.html

[U11] Py：生成器表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2jtfkgmbh.html

(x * 2 for x in arr)
来源：http://dali.bjfxy.top/Article/details/gt2isohhltf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.dashuyun.cn/Article/details/gt2dbctazva.html

Counter(arr).most_common(3)
来源：http://dali.aibaodan.cn/Article/details/gt2boilqhzh.html

[U13] Py：固定长度队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ndawcbky.html

deque(maxlen=10)
来源：http://dali.hnxiangtu.top/Article/details/gt2gymhznqc.html

[U14] Py：分组收集到列表
来源：http://dali.xuetiantiany.cn/Article/details/gt2nyygbnxk.html

defaultdict(list)
来源：http://dali.aizwys.cn/Article/details/gt2izijwsaz.html

[U15] Py：高精度计时
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pikstspp.html

t = time.perf_counter()
来源：http://dali.nanxinkj.top/Article/details/gt2aikygify.html

[U16] Py：命令行参数解析
来源：http://dali.tian-w.cn/Article/details/gt2aixqrnxm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cashguo.top/Article/details/gt2fdaheine.html

[U17] Py：初始化日志
来源：http://dali.sxryk.cn/Article/details/gt2urjnblyi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pphfzsal.html

[U18] Py：预编译正则
来源：http://dali.yangfankeji.com/Article/details/gt2iqcqlzgk.html

pat = re.compile(r"\d+")
来源：http://dali.ydzc1.top/Article/details/gt2dfpwdkhc.html

[U19] Py：正则替换带回调
来源：http://dali.sufxvd.cn/Article/details/gt2rakvrvmv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zdqjudy.top/Article/details/gt2trexonhm.html

[U20] Py：缓存函数结果
来源：http://dali.hongshengwenyu.top/Article/details/gt2biudywva.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ybcxt.top/Article/details/gt2ycumsrax.html

[U21] Py：自定义上下文管理器
来源：http://dali.jianghu66.top/Article/details/gt2hxjzkucq.html

@contextlib.contextmanager
来源：http://dali.xuetiantiany.cn/Article/details/gt2fnyorueq.html

[U22] Py：矩阵转置
来源：http://dali.ybcxt.top/Article/details/gt2yovscsnp.html

list(zip(*m))
来源：http://dali.wangshuangyany.cn/Article/details/gt2rrmfqilb.html

[U23] Py：分块读取大文件
来源：http://dali.aibaodan.cn/Article/details/gt2enxhrtsi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.svipenyu.cn/Article/details/gt2tmqnxlar.html

[U24] Py：路径操作
来源：http://dali.daxiang520.top/Article/details/gt2buhjyxjs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gt2rqjftcif.html

[U25] Py：CSV 按字典读
来源：http://dali.yongpay.top/Article/details/gt2nrkoyhup.html

csv.DictReader(f)
来源：http://dali.gaohongyu789.top/Article/details/gt2tbcvuvvs.html

[U26] Py：并发下载
来源：http://dali.hfpthk.cn/Article/details/gt2jxsjanrj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lvhqphqr.html

[U27] Py：异步 HTTP
来源：http://dali.xylfe.cn/Article/details/gt2shkhufyd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgwloopu.html

[U28] Py：类型别名
来源：http://dali.sxryk.cn/Article/details/gt2hgnkfapv.html

UserId = int
来源：http://dali.feifeiyinyue.top/Article/details/gt2usrlehxj.html

[U29] Py：属性校验
来源：http://dali.zhixingplan.top/Article/details/gt2vpqavgso.html

@property 与 @x.setter 配合
来源：http://dali.jqgufenzy.top/Article/details/gt2vrvpaovl.html

[U30] Py：数据类
来源：http://dali.hnxiangtu.top/Article/details/gt2btwddrgd.html

@dataclass(slots=True)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mcoqowma.html

[U31] Py：单测
来源：http://dali.tanke756.top/Article/details/gt2fedihwfp.html

python -m pytest -q
来源：http://dali.sysykeji.top/Article/details/gt2fdrvyrfs.html

[U32] Py：代码格式化
来源：http://dali.wangdashe.top/Article/details/gt2gbynufal.html

ruff format . && ruff check --fix .
来源：http://dali.jlsjyb.cn/Article/details/gt2zsoguccm.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfbgvlr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.mhx1999.top/Article/details/gt2uxyfsugo.html

[U34] Py：判断编码
来源：http://dali.ehwqpu.com/Article/details/gt2nvehwafu.html

chardet.detect(raw)
来源：http://dali.daria6918.cn/Article/details/gt2gyoizfrh.html

[U35] Py：发送邮件
来源：http://dali.wangdashe.top/Article/details/gt2ldwrdivk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jqgufenzy.top/Article/details/gt2xsphgaya.html

[U36] Py：定时任务
来源：http://dali.zhixingplan.top/Article/details/gt2ntkimctn.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhixingplan.top/Article/details/gt2yaoohxpi.html

[U37] Py：读写 Excel
来源：http://dali.jinqigfzy.top/Article/details/gt2qaoyfrag.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.kuanghao11.cn/Article/details/gt2ajdjdajg.html

[U38] Py：获取脚本所在目录
来源：http://dali.hnqzz.top/Article/details/gt2phcrjzaz.html

Path(__file__).resolve().parent
来源：http://dali.ydzc1.top/Article/details/gt2aogqkitg.html

[U39] Py：判断是否在交互环境
来源：http://dali.yuxming.cn/Article/details/gt2ijkgltty.html

sys.stdout.isatty()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vanswzgs.html

[U40] Py：打印到标准错误
来源：http://dali.ydzc1.top/Article/details/gt2drlprtao.html

print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gt2hrsrsvtn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zycfv.cn/Article/details/gt2cddjrjze.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yuxming.cn/Article/details/gt2oxlgusxb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xuanzx.com/Article/details/gt2egnfgczl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.meibo888.top/Article/details/gt2vngfqnmt.html

[U43] PHP：声明命名空间
来源：http://dali.jqgufenzy.top/Article/details/gt2ryzocugt.html

namespace App\Http;
来源：http://dali.nanxuanxn.top/Article/details/gt2ygmfqjdo.html

[U44] PHP：开启严格类型
来源：http://dali.ppjwa.cn/Article/details/gt2rreebnmx.html

declare(strict_types=1);
来源：http://dali.shuidangran.top/Article/details/gt2srikvmmy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.sxryk.cn/Article/details/gt2obxnqiys.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2nuxcytcl.html

[U46] PHP：可空类型
来源：http://dali.pycfn.com/Article/details/gt2ehimlydh.html

?string $name = null
来源：http://dali.wangshuangyany.cn/Article/details/gt2vfpktiys.html

[U47] PHP：联合类型
来源：http://dali.tian-w.cn/Article/details/gt2nppwyawx.html

int|string $id
来源：http://dali.daxiang520.top/Article/details/gt2ltoilshf.html

[U48] PHP：纯枚举
来源：http://dali.cqqwz.cn/Article/details/gt2cxepcdki.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jmxjcrev.html


<!-- 参考信息 -->