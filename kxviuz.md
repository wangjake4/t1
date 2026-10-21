代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.birdmap.top/Article/details/gtkbsdickc.html

[S23] C：随机数
来源：http://dali.hammf.cn/Article/details/gtlxntvaxq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hysaishi.cn/Article/details/gtzpnmyill.html

[S24] C：获取本地时间
来源：http://dali.meibo888.top/Article/details/gtefnzutnm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxinkj.top/Article/details/gtzeognlyc.html

[S25] C：内存拷贝
来源：http://dali.meibo888.top/Article/details/gtcvvdfapc.html

memcpy(dst, src, n);
来源：http://dali.redwolf501.top/Article/details/gtxnzauhwf.html

[S26] C：内存清零
来源：http://dali.snrcjt.cn/Article/details/gtxyzxvinp.html

memset(a, 0, sizeof a);
来源：http://dali.0kj1m.cn/Article/details/gtcjwwmpjt.html

[S27] C：定义常量
来源：http://dali.aibaodan.cn/Article/details/gtsaumdctg.html

const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtkksemdpn.html

[S28] C：静态变量
来源：http://dali.jinqigufen.top/Article/details/gtijtbmnun.html

static int counter = 0;
来源：http://dali.ivvv.top/Article/details/gtvjnqofhs.html

[S29] C：变参函数
来源：http://dali.xuetiantiany.cn/Article/details/gtpbkzkals.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aizwys.cn/Article/details/gtnodnamfn.html

[S30] C：头文件保护
来源：http://dali.yuanzhike.top/Article/details/gtcupionin.html

#ifndef X_H
来源：http://dali.zhengqikj.top/Article/details/gtylaehydl.html

#define X_H
来源：http://dali.tian-w.cn/Article/details/gtivooylvr.html

#endif
来源：http://dali.iojbl.cn/Article/details/gtsilnnphn.html

[S31] C++：Hello World
来源：http://dali.316326.xyz/Article/details/gtxrkpbglv.html

#include <iostream>
来源：http://dali.yj20258.top/Article/details/gtducsnylu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ivvv.top/Article/details/gtspzuodjk.html

[S32] C++：字符串
来源：http://dali.ybcxt.top/Article/details/gtqiomabfp.html

std::string s = "hi";  s += "!";
来源：http://dali.xziqi.cn/Article/details/gtpxnvyquc.html

[S33] C++：vector 增删
来源：http://dali.jinqigfzy.top/Article/details/gtigbulubd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gtjspykjmf.html

[S34] C++：遍历 vector
来源：http://dali.tanke756.top/Article/details/gtgmqranoj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shzxlz.cn/Article/details/gtoyfgtati.html

[S35] C++：map
来源：http://dali.gogol.net.cn/Article/details/gtrzaarflc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtwzzmxekw.html

[S36] C++：unordered_map
来源：http://dali.aibaodan.cn/Article/details/gtbaoscfwk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gteykfionw.html

[S37] C++：set
来源：http://dali.cheryme.top/Article/details/gtzdfftwhi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yvedp.cn/Article/details/gtzrjuaofw.html

[S38] C++：排序
来源：http://dali.gogol.net.cn/Article/details/gtxsiexwsh.html

std::sort(v.begin(), v.end());
来源：http://dali.shuidangran.top/Article/details/gttmeeqorg.html

[S39] C++：自定义比较器排序
来源：http://dali.wangshuangyany.cn/Article/details/gtvhfrgcpv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhongyouzk.top/Article/details/gtkkelwrxu.html

[S40] C++：查找元素
来源：http://dali.yonumen.top/Article/details/gtphulymad.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.havefunace.top/Article/details/gtdxkegtdv.html

[S41] C++：类与构造函数
来源：http://dali.yuxming.cn/Article/details/gtbthkejln.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhongyouzk.top/Article/details/gtofpcuwyt.html

[S42] C++：继承与虚函数
来源：http://dali.gaohongyu789.top/Article/details/gtcflqhjvh.html

class B : public Base { public: void f() override {} };
来源：http://dali.c1oappe.top/Article/details/gtykhtsuyv.html

[S43] C++：智能指针
来源：http://dali.yongpay.top/Article/details/gtnpweligq.html

auto p = std::make_unique<int>(5);
来源：http://dali.haohaochexian.top/Article/details/gtwopkolzq.html

[S44] C++：引用传参
来源：http://dali.jianghu66.top/Article/details/gtsspfolri.html

void inc(int &x) { ++x; }
来源：http://dali.dashuyun.cn/Article/details/gtdsvqqnrb.html

[S45] C++：lambda
来源：http://dali.shzxlz.cn/Article/details/gtdwmzzsnt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fengsongda.top/Article/details/gtsledioxj.html

[S46] C++：函数模板
来源：http://dali.kuanghao11.cn/Article/details/gtcrmmqvdf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gogol.net.cn/Article/details/gtfqystpya.html

[S47] C++：结构化绑定遍历
来源：http://dali.tianlin.xyz/Article/details/gtoyvlphbd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cashguo.top/Article/details/gtemprnpmt.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtsljkxhay.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuanzhike.top/Article/details/gtdgqvfqrr.html

while (std::getline(in, line)) { }
来源：http://dali.jyoumei.cn/Article/details/gtcxkwudfj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gtqsikghqn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aibaodan.cn/Article/details/gthpjmymjp.html

[S50] C++：格式化数字
来源：http://dali.chenzaomai.com/Article/details/gtxlwloqex.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtaqshaawx.html

[S51] C++：显式类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtvzkrpv.html

static_cast<double>(a) / b
来源：http://dali.aizwys.cn/Article/details/gtdibkwnkp.html

[S52] C++：const 与 noexcept
来源：http://dali.meibo888.top/Article/details/gtwtiscwcg.html

int size() const noexcept { return n_; }
来源：http://dali.iojbl.cn/Article/details/gtcmeprktf.html

[S53] C++：移动语义
来源：http://dali.xylfe.cn/Article/details/gtndaakpjm.html

std::vector<int> w = std::move(v);
来源：http://dali.hnxiangtu.top/Article/details/gtyaximssf.html

[S54] C++：异常处理
来源：http://dali.nwbrower.top/Article/details/gtiinzaujg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dianchejie.cn/Article/details/gttewezgej.html

[S55] C++：结构化绑定
来源：http://dali.havefunace.top/Article/details/gtylzyztdg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtsmryclln.html

[S56] C++：optional
来源：http://dali.zdqjudy.top/Article/details/gtkrphuain.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yanxiufei.cn/Article/details/gtgpbeaeoi.html

[S57] C++：编译期常量
来源：http://dali.nwbrower.top/Article/details/gtmddjgtce.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gtydhrliox.html

[S58] C++：命名空间
来源：http://dali.daxiang520.top/Article/details/gtbhvzaelb.html

namespace ns { int f() { return 1; } }
来源：http://dali.yongpay.top/Article/details/gtsawpnlhx.html

[S59] C++：静态断言
来源：http://dali.zhengqikj.top/Article/details/gtzvctsnus.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ivvv.top/Article/details/gtrobrodns.html

[S60] C++：遍历并删除元素
来源：http://dali.gzhubu.top/Article/details/gtlydbvikq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yongpay.top/Article/details/gtsgostazu.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtxvtsucel.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gtorwhkglo.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtlswvsnvd.html

[T01] Kotlin：Hello World
来源：http://dali.guannengcc.top/Article/details/gtlsfcoonv.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfadzsna.html

[T02] Kotlin：变量
来源：http://dali.yuanzhike.top/Article/details/gtjnfblvof.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.0kj1m.cn/Article/details/gtcaddhxig.html

[T03] Kotlin：字符串模板
来源：http://dali.wangshuangyany.cn/Article/details/gtaanyezmg.html

"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gtvgcdhhhp.html

[T04] Kotlin：空安全
来源：http://dali.zycfv.cn/Article/details/gtvngbchir.html

val n: String? = null;  n?.length
来源：http://dali.yj20258888.top/Article/details/gtciqwaxxz.html

[T05] Kotlin：when 表达式
来源：http://dali.pycfn.com/Article/details/gtnisanmpd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jiagoushi.top/Article/details/gttyesuzwh.html

[T06] Kotlin：集合映射
来源：http://dali.quarkkingdee.top/Article/details/gtadgooqaj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtqmtxyzgo.html

[T07] Kotlin：集合过滤
来源：http://dali.daxiang520.top/Article/details/gtmeuhpkgl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zycfv.cn/Article/details/gtikvohkjx.html

[T08] Kotlin：数据类
来源：http://dali.zdqjudy.top/Article/details/gtktshuxrt.html

data class User(val name: String, val age: Int)
来源：http://dali.c1oappe.top/Article/details/gtqqlzgqug.html

[T09] Kotlin：扩展函数
来源：http://dali.jianghu66.top/Article/details/gtvutqikss.html

fun String.exclaim() = this + "!"
来源：http://dali.smart0.xyz/Article/details/gtbhfenwrd.html

[T10] Kotlin：默认参数
来源：http://dali.jyoumei.cn/Article/details/gtcdzyxyvw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sysykeji.top/Article/details/gtfytavmdj.html

[T11] Kotlin：协程
来源：http://dali.birdmap.top/Article/details/gtgqwwhful.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yongpay.top/Article/details/gtaibpflyj.html

[T12] Kotlin：解构声明
来源：http://dali.yj202588.top/Article/details/gtcryespgi.html

val (a, b) = Pair(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtyogkdqzl.html

[T13] Kotlin：只读 Map
来源：http://dali.xinyue.icu/Article/details/gtrzqhznsm.html

val m = mapOf("a" to 1)
来源：http://dali.cqqwz.cn/Article/details/gtujrpqovc.html

[T14] Kotlin：循环
来源：http://dali.zhiwuduotai.top/Article/details/gtiuwflclv.html

for (i in 1..10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gtonuqwmtt.html

[T15] Kotlin：接口
来源：http://dali.fengsongda.top/Article/details/gtcdrvqxcs.html

interface Shape { fun area(): Double }
来源：http://dali.feifeiyinyue.top/Article/details/gtpzzxqkfh.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxtwimvy.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtdytrspyc.html

[T17] Swift：变量与常量
来源：http://dali.yanxiufei.cn/Article/details/gtfsvrwkqm.html

var a = 1;  let b = 2
来源：http://dali.daxiang520.top/Article/details/gtpkvpzucf.html

[T18] Swift：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtxxzsunko.html

"值: \(b)"
来源：http://dali.ydzc1.top/Article/details/gtkksmidao.html

[T19] Swift：可选绑定
来源：http://dali.dianchejie.cn/Article/details/gtpbdxciso.html

if let n = opt { print(n) }
来源：http://dali.quarkkingdee.top/Article/details/gtohklmqbo.html

[T20] Swift：数组操作
来源：http://dali.ybcxt.top/Article/details/gtlrgrhlof.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenzaomai.com/Article/details/gtdfaiwcci.html

[T21] Swift：遍历
来源：http://dali.sysykeji.top/Article/details/gtslouyuco.html

for x in a { print(x) }
来源：http://dali.dianchejie.cn/Article/details/gtgobuuekb.html

[T22] Swift：字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsxnpehi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.mhx1999.top/Article/details/gtiozksrcr.html

[T23] Swift：函数
来源：http://dali.tian-w.cn/Article/details/gtsdztrvse.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ydzc1.top/Article/details/gtgwsbvuth.html

[T24] Swift：闭包
来源：http://dali.aibaodan.cn/Article/details/gtimwujyqi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jianghu66.top/Article/details/gtinvjlbdp.html

[T25] Swift：结构体
来源：http://dali.feifeiyinyue.top/Article/details/gtoddtucls.html

struct P { var x: Int }
来源：http://dali.cashguo.top/Article/details/gtbandxfsz.html

[T26] Swift：类与重写
来源：http://dali.quarkkingdee.top/Article/details/gtdllxtmaf.html

class A: Base { override func f() {} }
来源：http://dali.jinqigfzy.top/Article/details/gthhsjwrjk.html

[T27] Swift：错误处理
来源：http://dali.dashuyun.cn/Article/details/gtlorauywz.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gttdliedrn.html

[T28] Swift：枚举
来源：http://dali.ydzc1.top/Article/details/gtvwlgdfol.html

enum Color { case red, green }
来源：http://dali.cdnleiting.top/Article/details/gtqjphjeic.html

[T29] Swift：guard 提前返回
来源：http://dali.jiagoushi.top/Article/details/gtsgsyvyir.html

guard let x = opt else { return }
来源：http://dali.pengpengdd.cyou/Article/details/gtjdbzffbg.html

[T30] Swift：协议
来源：http://dali.0kj1m.cn/Article/details/gtqypsjmkn.html

protocol Shape { func area() -> Double }
来源：http://dali.guannengcc.top/Article/details/gtyxpbmwjk.html

[T31] Lua：Hello World
来源：http://dali.fengsongda.top/Article/details/gtldxewwvb.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtilivpzgz.html

[T32] Lua：局部变量
来源：http://dali.dashuyun.cn/Article/details/gtwefskqhz.html

local a = 1
来源：http://dali.nanxuanxn.top/Article/details/gtcvwuffti.html

[T33] Lua：表（数组）
来源：http://dali.zdqjudy.top/Article/details/gtpcvnvfco.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqtgklkk.html

[T34] Lua：遍历表
来源：http://dali.guannengcc.top/Article/details/gtgnlfrgll.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.havefunace.top/Article/details/gtssevvtyg.html

[T35] Lua：字典表
来源：http://dali.yuxming.cn/Article/details/gtppfgpryq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258888.top/Article/details/gtxxdfsjzl.html

[T36] Lua：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxpvinps.html

function add(a, b) return a + b end
来源：http://dali.jlsjyb.cn/Article/details/gtzarzvsro.html

[T37] Lua：字符串拼接
来源：http://dali.andypj.xyz/Article/details/gtwkxgiusn.html

"a" .. "b"
来源：http://dali.ivvv.top/Article/details/gthlxjusto.html

[T38] Lua：条件
来源：http://dali.cucudq.cn/Article/details/gtrutrawdb.html

if x > 0 then print("正") end
来源：http://dali.shangyingyoupin.top/Article/details/gtvvcycnds.html

[T39] Lua：模式匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtqnhbywwa.html

string.find(s, "%d+")
来源：http://dali.haohaochexian.top/Article/details/gtifkmhnuq.html

[T40] Lua：元表
来源：http://dali.shangyingyoupin.top/Article/details/gtdfoyflsw.html

setmetatable({}, { __index = base })
来源：http://dali.smart0.xyz/Article/details/gtrtvldmdf.html

[T41] Perl：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtifudmxeo.html

print "Hello\n";
来源：http://dali.316326.xyz/Article/details/gtgbpdfefd.html

[T42] Perl：变量类型
来源：http://dali.andypj.xyz/Article/details/gtgyibypfe.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shzxlz.cn/Article/details/gtqxwvjeko.html

[T43] Perl：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtmobcdmdf.html

"值: $a"
来源：http://dali.meibo888.top/Article/details/gtzchplzdq.html

[T44] Perl：条件
来源：http://dali.yonumen.top/Article/details/gtvvhncmyl.html

if ($a > 0) { print "正"; }
来源：http://dali.gotoacloud.top/Article/details/gtamditavq.html

[T45] Perl：数组遍历
来源：http://dali.yongpay.top/Article/details/gtiuoscabd.html

for my $x (@arr) { print $x; }
来源：http://dali.gzhubu.top/Article/details/gtjewafryl.html

[T46] Perl：哈希操作
来源：http://dali.hammf.cn/Article/details/gtztaxbzdj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuanzx.com/Article/details/gtydequoju.html

[T47] Perl：正则捕获
来源：http://dali.yj20258.top/Article/details/gtyblleewv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hywenlv.cn/Article/details/gtkfbbxpfj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gtgzvmjkqu.html

$s =~ s/old/new/g;
来源：http://dali.jqgfzy.top/Article/details/gtrhntbbag.html

[T49] Perl：函数
来源：http://dali.gogol.net.cn/Article/details/gtctaokmwr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtrgrsrxpu.html

[T50] Perl：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtlxrvqndh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.quarkkingdee.top/Article/details/gtffzdwvst.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntgtlxid.html

[T51] Scala：Hello World
来源：http://dali.smart0.xyz/Article/details/gtwhwwznjv.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyuhluchd.html

[T52] Scala：变量
来源：http://dali.hammf.cn/Article/details/gtpymirkcs.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtqjnfragt.html

[T53] Scala：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtknbtmgzs.html

s"值: $b"
来源：http://dali.mhx1999.top/Article/details/gtrzjlhney.html

[T54] Scala：集合映射
来源：http://dali.tian-w.cn/Article/details/gtzozbdfad.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gogol.net.cn/Article/details/gtuogcyssq.html

[T55] Scala：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gtwtrntkkn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yuanzhike.top/Article/details/gtgmqsvijz.html

[T56] Scala：样例类
来源：http://dali.andypj.xyz/Article/details/gtdjnqjpjz.html

case class User(name: String, age: Int)
来源：http://dali.nwbrower.top/Article/details/gtojtwyebm.html

[T57] Scala：模式匹配
来源：http://dali.birdmap.top/Article/details/gtyxyrjwmp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258888.top/Article/details/gtukiylaxq.html

[T58] Scala：函数定义
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmplfhdk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.redwolf501.top/Article/details/gttumpnmqu.html

[T59] Scala：循环
来源：http://dali.hnqzz.top/Article/details/gtifeqkqai.html

for (i <- 1 to 10) println(i)
来源：http://dali.ivvv.top/Article/details/gtbkesszhd.html

[T60] Scala：折叠
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzlsswth.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xinyue.icu/Article/details/gtbghzggbv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtdkxrdkmp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.9152youxi.cn/Article/details/gtbvqaeivx.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtaozsbvpm.html

[U01] Py：创建虚拟环境
来源：http://dali.yuxming.cn/Article/details/gteyhvddii.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fzhhl.top/Article/details/gtskcqeaut.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jlsjyb.cn/Article/details/gtkyvdtteb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ybcxt.top/Article/details/gtjrvrmiti.html

[U03] Py：加载 .env 配置
来源：http://dali.fzhhl.top/Article/details/gtaxcuwgpz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hysaishi.cn/Article/details/gtiekdrjtg.html

[U04] Py：变量调试打印
来源：http://dali.birdmap.top/Article/details/gtsyuwmllb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenjidiqi.icu/Article/details/gtxkwbeenu.html

[U05] Py：列表去重且保序
来源：http://dali.zhoulong.xyz/Article/details/gtikepgilq.html

list(dict.fromkeys(arr))
来源：http://dali.hnqzz.top/Article/details/gtdabahkbt.html

[U06] Py：合并两个字典
来源：http://dali.shzxlz.cn/Article/details/gteenrpeaf.html

{**a, **b}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrwupkqa.html

[U07] Py：反转字典键值
来源：http://dali.cheryme.top/Article/details/gtxzqnnbyv.html

{v: k for k, v in d.items()}
来源：http://dali.hammf.cn/Article/details/gtakbnsuwd.html

[U08] Py：展平二维列表
来源：http://dali.yuanzhike.top/Article/details/gtrtijgssm.html

[y for x in nested for y in x]
来源：http://dali.pengpengdd.cyou/Article/details/gtuvkaehwv.html

[U09] Py：字典取最大值的键
来源：http://dali.hongshengwenyu.top/Article/details/gtiyevosra.html

max(d, key=d.get)
来源：http://dali.hysaishi.cn/Article/details/gtpxqceslm.html

[U10] Py：按值排序字典
来源：http://dali.yueranfly.top/Article/details/gticdkvvwd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.andypj.xyz/Article/details/gtsubcmiir.html

[U11] Py：生成器表达式
来源：http://dali.yuanzhike.top/Article/details/gtzdfvipyx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gtywkepldg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.chenlongwang.top/Article/details/gtocbsandy.html

Counter(arr).most_common(3)
来源：http://dali.kuanghao11.cn/Article/details/gtqzodnflg.html

[U13] Py：固定长度队列
来源：http://dali.zycfv.cn/Article/details/gtpgwmueed.html

deque(maxlen=10)
来源：http://dali.birdmap.top/Article/details/gtgjgglels.html

[U14] Py：分组收集到列表
来源：http://dali.yanxiufei.cn/Article/details/gtygswtuzr.html

defaultdict(list)
来源：http://dali.andypj.xyz/Article/details/gtsjxtibnj.html

[U15] Py：高精度计时
来源：http://dali.hywenlv.cn/Article/details/gtjnizfjug.html

t = time.perf_counter()
来源：http://dali.ppjwa.cn/Article/details/gtbswedehy.html

[U16] Py：命令行参数解析
来源：http://dali.fzhhl.top/Article/details/gtxopeuqrz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nwbrower.top/Article/details/gtcgjsnifm.html

[U17] Py：初始化日志
来源：http://dali.zhiwuduotai.top/Article/details/gtmwlznjdi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhengqikj.top/Article/details/gtuejaggkg.html

[U18] Py：预编译正则
来源：http://dali.snrcjt.cn/Article/details/gtnttlihss.html

pat = re.compile(r"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtowxkrtma.html

[U19] Py：正则替换带回调
来源：http://dali.kuanghao11.cn/Article/details/gtzalytgwh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.feifeiyinyue.top/Article/details/gtnuqkctxp.html

[U20] Py：缓存函数结果
来源：http://dali.jlsjyb.cn/Article/details/gtenoqolky.html

@functools.lru_cache(maxsize=None)
来源：http://dali.daria6918.cn/Article/details/gtpzamafzq.html

[U21] Py：自定义上下文管理器
来源：http://dali.tanke756.top/Article/details/gtbfzjzxfi.html

@contextlib.contextmanager
来源：http://dali.pengpengdd.cyou/Article/details/gtoqyyypip.html

[U22] Py：矩阵转置
来源：http://dali.hfpthk.cn/Article/details/gtqwqqinfa.html

list(zip(*m))
来源：http://dali.c1oappe.top/Article/details/gtsiphulsv.html

[U23] Py：分块读取大文件
来源：http://dali.jinqigfzy.top/Article/details/gtasiepdfa.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xziqi.cn/Article/details/gttcmjnkvq.html

[U24] Py：路径操作
来源：http://dali.zhongyouzk.top/Article/details/gtvqwifvpz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gtenvbzfey.html

[U25] Py：CSV 按字典读
来源：http://dali.xziqi.cn/Article/details/gthtgfqsak.html

csv.DictReader(f)
来源：http://dali.bjfxy.top/Article/details/gtfbvwavzc.html

[U26] Py：并发下载
来源：http://dali.tianlin.xyz/Article/details/gtlrznyuky.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hnxiangtu.top/Article/details/gtsxveagdl.html

[U27] Py：异步 HTTP
来源：http://dali.birdmap.top/Article/details/gtzvrttfda.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hnqzz.top/Article/details/gtldxptgwg.html

[U28] Py：类型别名
来源：http://dali.shangyingyoupin.top/Article/details/gtzjvmzmkk.html

UserId = int
来源：http://dali.tian-w.cn/Article/details/gtdmersfdz.html

[U29] Py：属性校验
来源：http://dali.dashuyun.cn/Article/details/gtffccynbt.html

@property 与 @x.setter 配合
来源：http://dali.hammf.cn/Article/details/gtwhfyjtou.html

[U30] Py：数据类
来源：http://dali.cqqwz.cn/Article/details/gthllinjzu.html

@dataclass(slots=True)
来源：http://dali.sweek.top/Article/details/gtveiatlic.html

[U31] Py：单测
来源：http://dali.jianghu66.top/Article/details/gtgopihidt.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gtlcquudvy.html

[U32] Py：代码格式化
来源：http://dali.guannengcc.top/Article/details/gtskxdatmy.html

ruff format . && ruff check --fix .
来源：http://dali.svipenyu.cn/Article/details/gtgsyzzeoz.html

[U33] Py：打包发布
来源：http://dali.fzhhl.top/Article/details/gtrqqrsjom.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jqgfzy.top/Article/details/gttmodmbhc.html

[U34] Py：判断编码
来源：http://dali.jinqigufen.top/Article/details/gtysmarrpx.html

chardet.detect(raw)
来源：http://dali.jiagoushi.top/Article/details/gtlosuqogy.html

[U35] Py：发送邮件
来源：http://dali.9152youxi.cn/Article/details/gtiaqgnfgg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yuanzhike.top/Article/details/gtiuuswxyq.html

[U36] Py：定时任务
来源：http://dali.nanxuanxn.top/Article/details/gtromcrqcx.html

schedule.every(10).minutes.do(job)
来源：http://dali.xuetiantiany.cn/Article/details/gtpcpetqdp.html

[U37] Py：读写 Excel
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknjebqmw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.havefunace.top/Article/details/gtqxuhbfmc.html

[U38] Py：获取脚本所在目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxyugshmz.html

Path(__file__).resolve().parent
来源：http://dali.c1oappe.top/Article/details/gthgriekkp.html

[U39] Py：判断是否在交互环境
来源：http://dali.guowangkeji.top/Article/details/gtcwbpcmxn.html

sys.stdout.isatty()
来源：http://dali.guowangkeji.top/Article/details/gtxhtinjtw.html

[U40] Py：打印到标准错误
来源：http://dali.c1oappe.top/Article/details/gtkjxemqxq.html

print("err", file=sys.stderr)
来源：http://dali.hammf.cn/Article/details/gtmwxveocg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.feifeiyinyue.top/Article/details/gtlpyocyab.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cqqwz.cn/Article/details/gteeoaatxz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hnqzz.top/Article/details/gtlakjznks.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.feifeiyinyue.top/Article/details/gtwqqpsswp.html

[U43] PHP：声明命名空间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkuyzufh.html

namespace App\Http;
来源：http://dali.ehwqpu.com/Article/details/gtrorvhhwb.html

[U44] PHP：开启严格类型
来源：http://dali.ydzc1.top/Article/details/gtknmzzgvz.html

declare(strict_types=1);
来源：http://dali.yanxiufei.cn/Article/details/gtgaabyomd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jianghu66.top/Article/details/gtcrtpqsuy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtayaifhxd.html

[U46] PHP：可空类型
来源：http://dali.ehwqpu.com/Article/details/gtoqifhgpy.html

?string $name = null
来源：http://dali.hongshengwenyu.top/Article/details/gthlkxqigf.html


<!-- 参考信息 -->