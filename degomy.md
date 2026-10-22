代发 wailian999

[S33] C++：vector 增删
来源：http://dali.feifeiyinyue.top/Article/details/gt2ywqainnm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.0kj1m.cn/Article/details/gt2gupmelvu.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gt2jehjeuzd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tvcffarv.html

[S35] C++：map
来源：http://dali.xuetiantiany.cn/Article/details/gt2mgrwenir.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2jbqhgdgq.html

[S36] C++：unordered_map
来源：http://dali.tianlin.xyz/Article/details/gt2bsgnrwrq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2nshjqvlm.html

[S37] C++：set
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxzbymti.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xylfe.cn/Article/details/gt2fsfhckbe.html

[S38] C++：排序
来源：http://dali.yanxiufei.cn/Article/details/gt2izwbzfvv.html

std::sort(v.begin(), v.end());
来源：http://dali.cqqwz.cn/Article/details/gt2hbjzbneg.html

[S39] C++：自定义比较器排序
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqeokxlb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gt2ecfggfmg.html

[S40] C++：查找元素
来源：http://dali.jianghu66.top/Article/details/gt2vnuikhct.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2zwfzkqid.html

[S41] C++：类与构造函数
来源：http://dali.tian-w.cn/Article/details/gt2deswneby.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.redwolf501.top/Article/details/gt2vkamuwkm.html

[S42] C++：继承与虚函数
来源：http://dali.jiagoushi.top/Article/details/gt2ojolbwvx.html

class B : public Base { public: void f() override {} };
来源：http://dali.tianlin.xyz/Article/details/gt2esxgnogo.html

[S43] C++：智能指针
来源：http://dali.svipenyu.cn/Article/details/gt2juzhwvrb.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgufenzy.top/Article/details/gt2casuqphp.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gt2cpjblaty.html

void inc(int &x) { ++x; }
来源：http://dali.hysaishi.cn/Article/details/gt2dobshhtv.html

[S45] C++：lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2somfcull.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yanxiufei.cn/Article/details/gt2hdyzairi.html

[S46] C++：函数模板
来源：http://dali.aibaodan.cn/Article/details/gt2cmxhjzks.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuxming.cn/Article/details/gt2bzynhbch.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fpwxdjrd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fengsongda.top/Article/details/gt2skldoksj.html

[S48] C++：逐行读文件
来源：http://dali.yj202588.top/Article/details/gt2wqqxwbke.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.vqdsnc.cn/Article/details/gt2bjrrwlfs.html

while (std::getline(in, line)) { }
来源：http://dali.ehwqpu.com/Article/details/gt2nhrcswqp.html

[S49] C++：写文件
来源：http://dali.0kj1m.cn/Article/details/gt2lvbnqgjl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yangfankeji.com/Article/details/gt2zmttazkq.html

[S50] C++：格式化数字
来源：http://dali.jinqigufen.top/Article/details/gt2ggyoitea.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnqzz.top/Article/details/gt2bqusqrjr.html

[S51] C++：显式类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dmpvwkok.html

static_cast<double>(a) / b
来源：http://dali.pengpengdd.cyou/Article/details/gt2kfnvicbh.html

[S52] C++：const 与 noexcept
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iipayvuy.html

int size() const noexcept { return n_; }
来源：http://dali.smart0.xyz/Article/details/gt2swknpkea.html

[S53] C++：移动语义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ndxbmdbe.html

std::vector<int> w = std::move(v);
来源：http://dali.snrcjt.cn/Article/details/gt2dvyxdfhs.html

[S54] C++：异常处理
来源：http://dali.jqgfzy.top/Article/details/gt2pwvjbfoa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.mhx1999.top/Article/details/gt2fbgfdgck.html

[S55] C++：结构化绑定
来源：http://dali.daxiang520.top/Article/details/gt2frquxhyw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.c1oappe.top/Article/details/gt2vdcxezjm.html

[S56] C++：optional
来源：http://dali.jianghu66.top/Article/details/gt2wdsrvnzf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.c1oappe.top/Article/details/gt2vnyomwbm.html

[S57] C++：编译期常量
来源：http://dali.ybcxt.top/Article/details/gt2dmjdlahc.html

constexpr int N = 10;
来源：http://dali.nanxuanxn.top/Article/details/gt2cmwormqa.html

[S58] C++：命名空间
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvxwdsjx.html

namespace ns { int f() { return 1; } }
来源：http://dali.jiagoushi.top/Article/details/gt2nxzvomci.html

[S59] C++：静态断言
来源：http://dali.0kj1m.cn/Article/details/gt2ixltwjla.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guannengcc.top/Article/details/gt2dmymwodz.html

[S60] C++：遍历并删除元素
来源：http://dali.9152youxi.cn/Article/details/gt2likhlaxh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dzylpdni.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ptissbia.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zycfv.cn/Article/details/gt2cvgknlbo.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2utgljrgw.html

[T01] Kotlin：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2qhqjgolc.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gt2rntlxsxk.html

[T02] Kotlin：变量
来源：http://dali.ybcxt.top/Article/details/gt2ecvfzgjt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fzhhl.top/Article/details/gt2jqkmxscg.html

[T03] Kotlin：字符串模板
来源：http://dali.yangfankeji.com/Article/details/gt2tvczgdht.html

"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gt2feqzzzcd.html

[T04] Kotlin：空安全
来源：http://dali.cucudq.cn/Article/details/gt2nfipztng.html

val n: String? = null;  n?.length
来源：http://dali.aizwys.cn/Article/details/gt2lhmutjow.html

[T05] Kotlin：when 表达式
来源：http://dali.tanke756.top/Article/details/gt2kyxtjqgs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258888.top/Article/details/gt2rluszpan.html

[T06] Kotlin：集合映射
来源：http://dali.ivvv.top/Article/details/gt2ijdchves.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2obxmtjjr.html

[T07] Kotlin：集合过滤
来源：http://dali.yongpay.top/Article/details/gt2dqvugqpf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258.top/Article/details/gt2lorrcxea.html

[T08] Kotlin：数据类
来源：http://dali.0kj1m.cn/Article/details/gt2xvkbpcpy.html

data class User(val name: String, val age: Int)
来源：http://dali.hfpthk.cn/Article/details/gt2vnnpudry.html

[T09] Kotlin：扩展函数
来源：http://dali.dashuyun.cn/Article/details/gt2dzfmmxmy.html

fun String.exclaim() = this + "!"
来源：http://dali.chenzaomai.com/Article/details/gt2ekoomqsy.html

[T10] Kotlin：默认参数
来源：http://dali.cashguo.top/Article/details/gt2dpuxuafd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zycfv.cn/Article/details/gt2prgknykp.html

[T11] Kotlin：协程
来源：http://dali.jqgfzy.top/Article/details/gt2zsrdcedo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhengqikj.top/Article/details/gt2xrvkqnvg.html

[T12] Kotlin：解构声明
来源：http://dali.gotoacloud.top/Article/details/gt2vfdagjss.html

val (a, b) = Pair(1, 2)
来源：http://dali.hammf.cn/Article/details/gt2jdhavsrd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2oudbnjkz.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lugvzdta.html

[T14] Kotlin：循环
来源：http://dali.hnxiangtu.top/Article/details/gt2isarkbnp.html

for (i in 1..10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gt2yvbanbkx.html

[T15] Kotlin：接口
来源：http://dali.meibo888.top/Article/details/gt2rseomqej.html

interface Shape { fun area(): Double }
来源：http://dali.wangdashe.top/Article/details/gt2bwvyspzw.html

[T16] Swift：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2nvctmnro.html

print("Hello")
来源：http://dali.zycfv.cn/Article/details/gt2qphwgtvn.html

[T17] Swift：变量与常量
来源：http://dali.gaohongyu789.top/Article/details/gt2fyxbjjiw.html

var a = 1;  let b = 2
来源：http://dali.vqdsnc.cn/Article/details/gt2futcgkzb.html

[T18] Swift：字符串插值
来源：http://dali.gzhubu.top/Article/details/gt2mtldpgem.html

"值: \(b)"
来源：http://dali.havefunace.top/Article/details/gt2eaborrsa.html

[T19] Swift：可选绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yguidhfy.html

if let n = opt { print(n) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tcjgtcqu.html

[T20] Swift：数组操作
来源：http://dali.feifeiyinyue.top/Article/details/gt2dzvxejfy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.guannengcc.top/Article/details/gt2stkykhvl.html

[T21] Swift：遍历
来源：http://dali.yj202588.top/Article/details/gt2gudetjdf.html

for x in a { print(x) }
来源：http://dali.pycfn.com/Article/details/gt2akezbbyv.html

[T22] Swift：字典
来源：http://dali.zhixingplan.top/Article/details/gt2apxphsgz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.quarkkingdee.top/Article/details/gt2pabfefst.html

[T23] Swift：函数
来源：http://dali.jiagoushi.top/Article/details/gt2siiricgx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.bjfxy.top/Article/details/gt2naphegww.html

[T24] Swift：闭包
来源：http://dali.xuetiantiany.cn/Article/details/gt2bapwkxyk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258888.top/Article/details/gt2dupgyzva.html

[T25] Swift：结构体
来源：http://dali.zhengqikj.top/Article/details/gt2iqfgdcdf.html

struct P { var x: Int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zurrkhoh.html

[T26] Swift：类与重写
来源：http://dali.havefunace.top/Article/details/gt2kzrwxivs.html

class A: Base { override func f() {} }
来源：http://dali.jinqigufen.top/Article/details/gt2zkwtpasn.html

[T27] Swift：错误处理
来源：http://dali.smart0.xyz/Article/details/gt2sdhhbfam.html

do { try f() } catch { print(error) }
来源：http://dali.xylfe.cn/Article/details/gt2bzuwmkgu.html

[T28] Swift：枚举
来源：http://dali.yvedp.cn/Article/details/gt2xlrmgqoc.html

enum Color { case red, green }
来源：http://dali.guowangkeji.top/Article/details/gt2cymhnway.html

[T29] Swift：guard 提前返回
来源：http://dali.dashuyun.cn/Article/details/gt2onggohzt.html

guard let x = opt else { return }
来源：http://dali.hysaishi.cn/Article/details/gt2jctpxlbn.html

[T30] Swift：协议
来源：http://dali.jinqigfzy.top/Article/details/gt2jyasyfvr.html

protocol Shape { func area() -> Double }
来源：http://dali.andypj.xyz/Article/details/gt2lxonajvh.html

[T31] Lua：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2mqlmxnsw.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gt2yeoivkzp.html

[T32] Lua：局部变量
来源：http://dali.tanke756.top/Article/details/gt2eeqpachh.html

local a = 1
来源：http://dali.yangfankeji.com/Article/details/gt2dmdvzhyd.html

[T33] Lua：表（数组）
来源：http://dali.pengpengdd.cyou/Article/details/gt2nlfbjlrf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mnywacbi.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qwnuheny.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gotoacloud.top/Article/details/gt2kdtnmkcx.html

[T35] Lua：字典表
来源：http://dali.tian-w.cn/Article/details/gt2xfotgepy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhongyouzk.top/Article/details/gt2eclrpdyx.html

[T36] Lua：函数
来源：http://dali.iojbl.cn/Article/details/gt2kcjsfpev.html

function add(a, b) return a + b end
来源：http://dali.hongshengwenyu.top/Article/details/gt2hzbkiwdi.html

[T37] Lua：字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gt2rihclmis.html

"a" .. "b"
来源：http://dali.fzhhl.top/Article/details/gt2qlzbzdgv.html

[T38] Lua：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tatweshx.html

if x > 0 then print("正") end
来源：http://dali.9152youxi.cn/Article/details/gt2jlvbevqe.html

[T39] Lua：模式匹配
来源：http://dali.yuxming.cn/Article/details/gt2egxyeetn.html

string.find(s, "%d+")
来源：http://dali.ybcxt.top/Article/details/gt2lvdxsoxj.html

[T40] Lua：元表
来源：http://dali.meibo888.top/Article/details/gt2unmwfsus.html

setmetatable({}, { __index = base })
来源：http://dali.hysaishi.cn/Article/details/gt2phejpxnk.html

[T41] Perl：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2xupuxaoz.html

print "Hello\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2przxrrng.html

[T42] Perl：变量类型
来源：http://dali.kuanghao11.cn/Article/details/gt2dznrfoqi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.andypj.xyz/Article/details/gt2dvxabwec.html

[T43] Perl：字符串插值
来源：http://dali.iojbl.cn/Article/details/gt2rqmgkwgb.html

"值: $a"
来源：http://dali.wangdashe.top/Article/details/gt2hxhrafjl.html

[T44] Perl：条件
来源：http://dali.haohaochexian.top/Article/details/gt2iltmyvxc.html

if ($a > 0) { print "正"; }
来源：http://dali.gzhubu.top/Article/details/gt2dxpubcip.html

[T45] Perl：数组遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2udhpuijx.html

for my $x (@arr) { print $x; }
来源：http://dali.chenlongwang.top/Article/details/gt2hmflahml.html

[T46] Perl：哈希操作
来源：http://dali.xziqi.cn/Article/details/gt2oifvwgje.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.meibo888.top/Article/details/gt2rytvvpcw.html

[T47] Perl：正则捕获
来源：http://dali.jinqigufen.top/Article/details/gt2cauiditr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yangfankeji.com/Article/details/gt2uzeniken.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwdajcmr.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sggauorl.html

[T49] Perl：函数
来源：http://dali.jiagoushi.top/Article/details/gt2hhbongad.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gt2iyokbwia.html

[T50] Perl：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2wtgmvdfz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gotoacloud.top/Article/details/gt2eydoqntv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.haohaochexian.top/Article/details/gt2neyemiuj.html

[T51] Scala：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2gvppcize.html

println("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2abhozmth.html

[T52] Scala：变量
来源：http://dali.hfpthk.cn/Article/details/gt2zlptdjpc.html

val a = 1;  var b = 2
来源：http://dali.mhx1999.top/Article/details/gt2nzywmufv.html

[T53] Scala：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gt2mbjagdwy.html

s"值: $b"
来源：http://dali.yongpay.top/Article/details/gt2qnkybnvx.html

[T54] Scala：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gt2brinbpxd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sweek.top/Article/details/gt2ftrxioxa.html

[T55] Scala：集合过滤
来源：http://dali.redwolf501.top/Article/details/gt2wyunzfer.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yangfankeji.com/Article/details/gt2vuyexmof.html

[T56] Scala：样例类
来源：http://dali.jqgfzy.top/Article/details/gt2peprbzms.html

case class User(name: String, age: Int)
来源：http://dali.xinyue.icu/Article/details/gt2ugoablxo.html

[T57] Scala：模式匹配
来源：http://dali.xziqi.cn/Article/details/gt2qfksswmc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fpgfyeuv.html

[T58] Scala：函数定义
来源：http://dali.cashguo.top/Article/details/gt2jtxlbirr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sufxvd.cn/Article/details/gt2acgtowhi.html

[T59] Scala：循环
来源：http://dali.sysykeji.top/Article/details/gt2jgdyjtly.html

for (i <- 1 to 10) println(i)
来源：http://dali.316326.xyz/Article/details/gt2vemnthnc.html

[T60] Scala：折叠
来源：http://dali.nanxuanxn.top/Article/details/gt2monhxglh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qpctarbc.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2wqkyppbi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gzhubu.top/Article/details/gt2fhzuxxic.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2nsocgkyp.html

[U01] Py：创建虚拟环境
来源：http://dali.tianlin.xyz/Article/details/gt2boqnoqfl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangtech.top/Article/details/gt2otokyznf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.havefunace.top/Article/details/gt2aolwzohb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2owowjapi.html

[U03] Py：加载 .env 配置
来源：http://dali.zdqjudy.top/Article/details/gt2abmagzfe.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuanzhike.top/Article/details/gt2syjeywew.html

[U04] Py：变量调试打印
来源：http://dali.yuxming.cn/Article/details/gt2qoinlzao.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.dashuyun.cn/Article/details/gt2rpptnjmh.html

[U05] Py：列表去重且保序
来源：http://dali.aibaodan.cn/Article/details/gt2utbiusyl.html

list(dict.fromkeys(arr))
来源：http://dali.9152youxi.cn/Article/details/gt2iomyvcal.html

[U06] Py：合并两个字典
来源：http://dali.aizwys.cn/Article/details/gt2jltirbkh.html

{**a, **b}
来源：http://dali.cashguo.top/Article/details/gt2loobupdu.html

[U07] Py：反转字典键值
来源：http://dali.jinqigfzy.top/Article/details/gt2ojqlrbzr.html

{v: k for k, v in d.items()}
来源：http://dali.zycfv.cn/Article/details/gt2ntelfkxg.html

[U08] Py：展平二维列表
来源：http://dali.ppjwa.cn/Article/details/gt2hwuvjxbw.html

[y for x in nested for y in x]
来源：http://dali.yvedp.cn/Article/details/gt2lofhjlns.html

[U09] Py：字典取最大值的键
来源：http://dali.havefunace.top/Article/details/gt2wnawbkdd.html

max(d, key=d.get)
来源：http://dali.tianlin.xyz/Article/details/gt2fcamuldm.html

[U10] Py：按值排序字典
来源：http://dali.ivvv.top/Article/details/gt2hchzhmvf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gaohongyu789.top/Article/details/gt2qtkafoey.html

[U11] Py：生成器表达式
来源：http://dali.cashguo.top/Article/details/gt2xudrfkbd.html

(x * 2 for x in arr)
来源：http://dali.jqgfzy.top/Article/details/gt2ljibwmfg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shzxlz.cn/Article/details/gt2wmdejnfn.html

Counter(arr).most_common(3)
来源：http://dali.andypj.xyz/Article/details/gt2cdlzgaqk.html

[U13] Py：固定长度队列
来源：http://dali.yongpay.top/Article/details/gt2ijqjujpn.html

deque(maxlen=10)
来源：http://dali.wangdashe.top/Article/details/gt2ghzuosnf.html

[U14] Py：分组收集到列表
来源：http://dali.zycfv.cn/Article/details/gt2yaubttad.html

defaultdict(list)
来源：http://dali.gogol.net.cn/Article/details/gt2akfaetsl.html

[U15] Py：高精度计时
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjjjyake.html

t = time.perf_counter()
来源：http://dali.shangyingyoupin.top/Article/details/gt2bnvjiosq.html

[U16] Py：命令行参数解析
来源：http://dali.yvedp.cn/Article/details/gt2eczxmqpr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.0kj1m.cn/Article/details/gt2soprairw.html

[U17] Py：初始化日志
来源：http://dali.daria6918.cn/Article/details/gt2dnropxlv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eowqfckm.html

[U18] Py：预编译正则
来源：http://dali.iojbl.cn/Article/details/gt2btiumckw.html

pat = re.compile(r"\d+")
来源：http://dali.yj20258888.top/Article/details/gt2ybvpwurn.html

[U19] Py：正则替换带回调
来源：http://dali.chenlongwang.top/Article/details/gt2pzauiorr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.guowangkeji.top/Article/details/gt2vhcdfrdd.html

[U20] Py：缓存函数结果
来源：http://dali.jiagoushi.top/Article/details/gt2oyiskuzq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhengqikj.top/Article/details/gt2fwhgkhot.html

[U21] Py：自定义上下文管理器
来源：http://dali.jqgufenzy.top/Article/details/gt2woarsjud.html

@contextlib.contextmanager
来源：http://dali.guowangkeji.top/Article/details/gt2cmolejtq.html

[U22] Py：矩阵转置
来源：http://dali.shangyingyoupin.top/Article/details/gt2wlbcwygb.html

list(zip(*m))
来源：http://dali.ybcxt.top/Article/details/gt2kovzrhwg.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2piypysfg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.iojbl.cn/Article/details/gt2cwjpmync.html

[U24] Py：路径操作
来源：http://dali.gotoacloud.top/Article/details/gt2sbmivtdn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.0kj1m.cn/Article/details/gt2noycljwv.html

[U25] Py：CSV 按字典读
来源：http://dali.vqdsnc.cn/Article/details/gt2qimraakw.html

csv.DictReader(f)
来源：http://dali.ydzc1.top/Article/details/gt2uctulopp.html

[U26] Py：并发下载
来源：http://dali.iojbl.cn/Article/details/gt2yftetptx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.birdmap.top/Article/details/gt2crrpqbnu.html

[U27] Py：异步 HTTP
来源：http://dali.cashguo.top/Article/details/gt2mdmiuoph.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hysaishi.cn/Article/details/gt2nyoepwcc.html

[U28] Py：类型别名
来源：http://dali.zhoulong.xyz/Article/details/gt2wfqcqqgh.html

UserId = int
来源：http://dali.ehwqpu.com/Article/details/gt2kwunqcwn.html

[U29] Py：属性校验
来源：http://dali.redwolf501.top/Article/details/gt2rwgsphhn.html

@property 与 @x.setter 配合
来源：http://dali.xuetiantiany.cn/Article/details/gt2xablieqz.html

[U30] Py：数据类
来源：http://dali.nwbrower.top/Article/details/gt2lrhrckeu.html

@dataclass(slots=True)
来源：http://dali.snrcjt.cn/Article/details/gt2tfpxqgjy.html

[U31] Py：单测
来源：http://dali.dianchejie.cn/Article/details/gt2yrfdreor.html

python -m pytest -q
来源：http://dali.chenjidiqi.icu/Article/details/gt2xvosbufs.html

[U32] Py：代码格式化
来源：http://dali.xinyue.icu/Article/details/gt2dmxtgszb.html

ruff format . && ruff check --fix .
来源：http://dali.hammf.cn/Article/details/gt2stzzpuvc.html

[U33] Py：打包发布
来源：http://dali.zhixingplan.top/Article/details/gt2yqpjkfuw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sysykeji.top/Article/details/gt2boifwqml.html

[U34] Py：判断编码
来源：http://dali.chenlongwang.top/Article/details/gt2yylwisnk.html

chardet.detect(raw)
来源：http://dali.chenzaomai.com/Article/details/gt2bmnfqokk.html

[U35] Py：发送邮件
来源：http://dali.hammf.cn/Article/details/gt2kwfjkhuf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.aibaodan.cn/Article/details/gt2oyrvmabv.html

[U36] Py：定时任务
来源：http://dali.zhoulong.xyz/Article/details/gt2ibeobcoa.html

schedule.every(10).minutes.do(job)
来源：http://dali.iojbl.cn/Article/details/gt2jcblyihg.html

[U37] Py：读写 Excel
来源：http://dali.ppjwa.cn/Article/details/gt2fmtpzskh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yongpay.top/Article/details/gt2mgqrkvxd.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhixingplan.top/Article/details/gt2pdpqofnq.html

Path(__file__).resolve().parent
来源：http://dali.ybcxt.top/Article/details/gt2iscyryjt.html

[U39] Py：判断是否在交互环境
来源：http://dali.gotoacloud.top/Article/details/gt2osmibbqv.html

sys.stdout.isatty()
来源：http://dali.gzhubu.top/Article/details/gt2ynymkjvl.html

[U40] Py：打印到标准错误
来源：http://dali.wangshuangyany.cn/Article/details/gt2cloazvcq.html

print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gt2mplhtgge.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.mhx1999.top/Article/details/gt2ddhqktxh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xziqi.cn/Article/details/gt2egftlgag.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.svipenyu.cn/Article/details/gt2oqweesgd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2filcsnda.html

[U43] PHP：声明命名空间
来源：http://dali.gaohongyu789.top/Article/details/gt2cxvzqqcx.html

namespace App\Http;
来源：http://dali.gogol.net.cn/Article/details/gt2nzoswugh.html

[U44] PHP：开启严格类型
来源：http://dali.tanke756.top/Article/details/gt2vstqbkjo.html

declare(strict_types=1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hlebadiv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ehwqpu.com/Article/details/gt2rxzgasdg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gt2bymgjbyu.html

[U46] PHP：可空类型
来源：http://dali.aibaodan.cn/Article/details/gt2myzvcszr.html

?string $name = null
来源：http://dali.xylfe.cn/Article/details/gt2wstnrlhe.html

[U47] PHP：联合类型
来源：http://dali.zycfv.cn/Article/details/gt2nctuaarn.html

int|string $id
来源：http://dali.smart0.xyz/Article/details/gt2dljmpelw.html

[U48] PHP：纯枚举
来源：http://dali.jianghu66.top/Article/details/gt2qgmpxbuv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sweek.top/Article/details/gt2hpwhxmlj.html

[U49] PHP：只读属性
来源：http://dali.bjfxy.top/Article/details/gt2xcscjyps.html

public readonly string $name
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxbdtnxn.html

[U50] PHP：构造器属性提升
来源：http://dali.sxryk.cn/Article/details/gt2btrmnwdu.html

public function __construct(private int $id) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2btkqqqkn.html

[U51] PHP：数组解构
来源：http://dali.tianlin.xyz/Article/details/gt2iqntfcdk.html

[$a, $b] = $arr;
来源：http://dali.havefunace.top/Article/details/gt2bgmskrnu.html

[U52] PHP：箭头函数
来源：http://dali.nwbrower.top/Article/details/gt2fuykgxlt.html

$double = fn($x) => $x * 2;
来源：http://dali.andypj.xyz/Article/details/gt2xkqrwoqu.html

[U53] PHP：空合并运算符
来源：http://dali.zhoulong.xyz/Article/details/gt2quhfxjjt.html

$v = $a ?? $b ?? "default";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aomatooz.html

[U54] PHP：空安全调用
来源：http://dali.ybcxt.top/Article/details/gt2uvglqwaq.html

$obj?->method()
来源：http://dali.quarkkingdee.top/Article/details/gt2fhrqvyyx.html

[U55] PHP：match 表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2sdhbvkru.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ivvv.top/Article/details/gt2zwpryynj.html

[U56] PHP：命名参数
来源：http://dali.jyoumei.cn/Article/details/gt2dlxrmwek.html

f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2vyqnrjli.html

[U57] PHP：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gt2lwzxljtz.html

"值: {$a}"
来源：http://dali.jiagoushi.top/Article/details/gt2gpcyjcsp.html

[U58] PHP：数组三件套
来源：http://dali.smart0.xyz/Article/details/gt2vatfsxtp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yvedp.cn/Article/details/gt2nhqxlprq.html


<!-- 参考信息 -->