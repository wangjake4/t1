代发 wailian999

[S35] C++：map
来源：http://dali.ybcxt.top/Article/details/gt2qvnjvddb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2hhynlnam.html

[S36] C++：unordered_map
来源：http://dali.pengpengdd.cyou/Article/details/gt2jvgxqash.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yayczalf.html

[S37] C++：set
来源：http://dali.sysykeji.top/Article/details/gt2iylmwgeg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.c1oappe.top/Article/details/gt2wbknipqc.html

[S38] C++：排序
来源：http://dali.hfpthk.cn/Article/details/gt2jufxwkdy.html

std::sort(v.begin(), v.end());
来源：http://dali.nwbrower.top/Article/details/gt2vzwxenbu.html

[S39] C++：自定义比较器排序
来源：http://dali.redwolf501.top/Article/details/gt2fziiinnt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jiagoushi.top/Article/details/gt2buqftcvc.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gt2ncktzsia.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hywenlv.cn/Article/details/gt2gpyxvtwp.html

[S41] C++：类与构造函数
来源：http://dali.andypj.xyz/Article/details/gt2bxeypzep.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yonumen.top/Article/details/gt2xaplbtub.html

[S42] C++：继承与虚函数
来源：http://dali.xziqi.cn/Article/details/gt2frpzagam.html

class B : public Base { public: void f() override {} };
来源：http://dali.ppjwa.cn/Article/details/gt2ckwwqaxy.html

[S43] C++：智能指针
来源：http://dali.cashguo.top/Article/details/gt2svjumfys.html

auto p = std::make_unique<int>(5);
来源：http://dali.9152youxi.cn/Article/details/gt2papezhpu.html

[S44] C++：引用传参
来源：http://dali.hnqzz.top/Article/details/gt2lunaqcsv.html

void inc(int &x) { ++x; }
来源：http://dali.yuxming.cn/Article/details/gt2afowgega.html

[S45] C++：lambda
来源：http://dali.haohaochexian.top/Article/details/gt2lpixgmsz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangshuangyany.cn/Article/details/gt2rmxdmuyf.html

[S46] C++：函数模板
来源：http://dali.0kj1m.cn/Article/details/gt2hsqitugq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yvedp.cn/Article/details/gt2kizledbd.html

[S47] C++：结构化绑定遍历
来源：http://dali.xylfe.cn/Article/details/gt2zosiaibv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zycfv.cn/Article/details/gt2eqmiwpmp.html

[S48] C++：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gt2gaujkgvo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhixingplan.top/Article/details/gt2nouixgpl.html

while (std::getline(in, line)) { }
来源：http://dali.jianghu66.top/Article/details/gt2kxssfxbo.html

[S49] C++：写文件
来源：http://dali.kuanghao11.cn/Article/details/gt2tccdndzs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shuidangran.top/Article/details/gt2vqwaijbe.html

[S50] C++：格式化数字
来源：http://dali.jinqigufen.top/Article/details/gt2ffrjysaa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2ewmooutj.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gt2epcbrozd.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rglypmmv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhengqikj.top/Article/details/gt2itxcngoi.html

int size() const noexcept { return n_; }
来源：http://dali.zycfv.cn/Article/details/gt2oswhbnxd.html

[S53] C++：移动语义
来源：http://dali.sweek.top/Article/details/gt2wduzfbmu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhoulong.xyz/Article/details/gt2gkcrxrtk.html

[S54] C++：异常处理
来源：http://dali.aibaodan.cn/Article/details/gt2zsfzkels.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aizwys.cn/Article/details/gt2nnqbevts.html

[S55] C++：结构化绑定
来源：http://dali.jinqigufen.top/Article/details/gt2iuyfqvwk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.havefunace.top/Article/details/gt2xflcvxop.html

[S56] C++：optional
来源：http://dali.chenzaomai.com/Article/details/gt2kfnsoofy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuanzhike.top/Article/details/gt2vkoiklum.html

[S57] C++：编译期常量
来源：http://dali.xylfe.cn/Article/details/gt2wtscyyeq.html

constexpr int N = 10;
来源：http://dali.yueranfly.top/Article/details/gt2xetawboz.html

[S58] C++：命名空间
来源：http://dali.ppjwa.cn/Article/details/gt2qhhzdjxr.html

namespace ns { int f() { return 1; } }
来源：http://dali.c1oappe.top/Article/details/gt2vjbfozal.html

[S59] C++：静态断言
来源：http://dali.xziqi.cn/Article/details/gt2aszccuoe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ybcxt.top/Article/details/gt2lujtvjky.html

[S60] C++：遍历并删除元素
来源：http://dali.meibo888.top/Article/details/gt2tosrwebo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gotoacloud.top/Article/details/gt2hiwovqik.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2duiinqwf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gt2fbkrtkzs.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2jiehybuj.html

[T01] Kotlin：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2wsdrjhco.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gt2ztcabbvq.html

[T02] Kotlin：变量
来源：http://dali.gzhubu.top/Article/details/gt2kkkxwxzq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gaohongyu789.top/Article/details/gt2ddrqvffa.html

[T03] Kotlin：字符串模板
来源：http://dali.tian-w.cn/Article/details/gt2ldtxbjmj.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gt2lqggwiwc.html

[T04] Kotlin：空安全
来源：http://dali.snrcjt.cn/Article/details/gt2graloyqq.html

val n: String? = null;  n?.length
来源：http://dali.yj202588.top/Article/details/gt2gtoqeepo.html

[T05] Kotlin：when 表达式
来源：http://dali.yongpay.top/Article/details/gt2tacvehwq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ppjwa.cn/Article/details/gt2oweeejqn.html

[T06] Kotlin：集合映射
来源：http://dali.svipenyu.cn/Article/details/gt2zufreftm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hfpthk.cn/Article/details/gt2hxrvrgbu.html

[T07] Kotlin：集合过滤
来源：http://dali.fzhhl.top/Article/details/gt2owgdbvwk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guowangkeji.top/Article/details/gt2pnxfkbeu.html

[T08] Kotlin：数据类
来源：http://dali.ivvv.top/Article/details/gt2rmrucggn.html

data class User(val name: String, val age: Int)
来源：http://dali.pycfn.com/Article/details/gt2zogowkbs.html

[T09] Kotlin：扩展函数
来源：http://dali.ydzc1.top/Article/details/gt2midevtnf.html

fun String.exclaim() = this + "!"
来源：http://dali.sysykeji.top/Article/details/gt2tqyilosc.html

[T10] Kotlin：默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2izgyvofr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hywenlv.cn/Article/details/gt2vqtqnoxr.html

[T11] Kotlin：协程
来源：http://dali.tianlin.xyz/Article/details/gt2kwsmmvlc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dianchejie.cn/Article/details/gt2htifdojp.html

[T12] Kotlin：解构声明
来源：http://dali.tian-w.cn/Article/details/gt2wjbszhki.html

val (a, b) = Pair(1, 2)
来源：http://dali.hnqzz.top/Article/details/gt2lfppbhmj.html

[T13] Kotlin：只读 Map
来源：http://dali.yonumen.top/Article/details/gt2jsxlfpzn.html

val m = mapOf("a" to 1)
来源：http://dali.yangfankeji.com/Article/details/gt2vxlzcrtz.html

[T14] Kotlin：循环
来源：http://dali.gzhubu.top/Article/details/gt2wjpnrfwa.html

for (i in 1..10) println(i)
来源：http://dali.nanxinkj.top/Article/details/gt2exszftwn.html

[T15] Kotlin：接口
来源：http://dali.yongpay.top/Article/details/gt2zdyzpyuc.html

interface Shape { fun area(): Double }
来源：http://dali.nwbrower.top/Article/details/gt2znyxzrpi.html

[T16] Swift：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2toxiyypz.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gt2quxdezfi.html

[T17] Swift：变量与常量
来源：http://dali.redwolf501.top/Article/details/gt2jexvefwo.html

var a = 1;  let b = 2
来源：http://dali.gzhubu.top/Article/details/gt2ukzjbsle.html

[T18] Swift：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gt2ostuarrn.html

"值: \(b)"
来源：http://dali.hammf.cn/Article/details/gt2fsfihqyc.html

[T19] Swift：可选绑定
来源：http://dali.bjfxy.top/Article/details/gt2jidnlklt.html

if let n = opt { print(n) }
来源：http://dali.kuanghao11.cn/Article/details/gt2lsgkxtws.html

[T20] Swift：数组操作
来源：http://dali.haohaochexian.top/Article/details/gt2wsjdlwwi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ydzc1.top/Article/details/gt2rzygvcba.html

[T21] Swift：遍历
来源：http://dali.jyoumei.cn/Article/details/gt2jcgvqnkl.html

for x in a { print(x) }
来源：http://dali.havefunace.top/Article/details/gt2nqbezekd.html

[T22] Swift：字典
来源：http://dali.feifeiyinyue.top/Article/details/gt2sudfromn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gaohongyu789.top/Article/details/gt2ofzovbod.html

[T23] Swift：函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2qtfxovbq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tanke756.top/Article/details/gt2gjjowlyr.html

[T24] Swift：闭包
来源：http://dali.9152youxi.cn/Article/details/gt2xadlruxj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2nvvjybtb.html

[T25] Swift：结构体
来源：http://dali.jlsjyb.cn/Article/details/gt2yklrdyfe.html

struct P { var x: Int }
来源：http://dali.xinyue.icu/Article/details/gt2hnntdgen.html

[T26] Swift：类与重写
来源：http://dali.xinyue.icu/Article/details/gt2fywdadin.html

class A: Base { override func f() {} }
来源：http://dali.yj202588.top/Article/details/gt2xrolcbai.html

[T27] Swift：错误处理
来源：http://dali.ehwqpu.com/Article/details/gt2albdeood.html

do { try f() } catch { print(error) }
来源：http://dali.yueranfly.top/Article/details/gt2ovyecriv.html

[T28] Swift：枚举
来源：http://dali.sxryk.cn/Article/details/gt2oejxxkfu.html

enum Color { case red, green }
来源：http://dali.dianchejie.cn/Article/details/gt2jfxtqeaz.html

[T29] Swift：guard 提前返回
来源：http://dali.ydzc1.top/Article/details/gt2ezmgfksg.html

guard let x = opt else { return }
来源：http://dali.tianlin.xyz/Article/details/gt2neqqeztp.html

[T30] Swift：协议
来源：http://dali.andypj.xyz/Article/details/gt2fvljmqmq.html

protocol Shape { func area() -> Double }
来源：http://dali.gzhubu.top/Article/details/gt2jokcmtzm.html

[T31] Lua：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2dvzhhhfx.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gt2brgfcebu.html

[T32] Lua：局部变量
来源：http://dali.guowangkeji.top/Article/details/gt2blkplosn.html

local a = 1
来源：http://dali.zhixingplan.top/Article/details/gt2qvmbnfbv.html

[T33] Lua：表（数组）
来源：http://dali.jinqigufen.top/Article/details/gt2bzniuhwt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jlsjyb.cn/Article/details/gt2anaftrnj.html

[T34] Lua：遍历表
来源：http://dali.hnqzz.top/Article/details/gt2jtwcxvun.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jianghu66.top/Article/details/gt2kzpjdyqm.html

[T35] Lua：字典表
来源：http://dali.feifeiyinyue.top/Article/details/gt2hchslirw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guowangkeji.top/Article/details/gt2migexfuz.html

[T36] Lua：函数
来源：http://dali.tanke756.top/Article/details/gt2ixammvgv.html

function add(a, b) return a + b end
来源：http://dali.tianlin.xyz/Article/details/gt2upfadcje.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsgqwqs.html

"a" .. "b"
来源：http://dali.yuxming.cn/Article/details/gt2ktufupbf.html

[T38] Lua：条件
来源：http://dali.zhoulong.xyz/Article/details/gt2outdlvyh.html

if x > 0 then print("正") end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vcjboqmf.html

[T39] Lua：模式匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2saotnjzz.html

string.find(s, "%d+")
来源：http://dali.ivvv.top/Article/details/gt2kzwkdinf.html

[T40] Lua：元表
来源：http://dali.meibo888.top/Article/details/gt2fpbzzhgt.html

setmetatable({}, { __index = base })
来源：http://dali.shuidangran.top/Article/details/gt2kojrthne.html

[T41] Perl：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2wwxkduoi.html

print "Hello\n";
来源：http://dali.wangdashe.top/Article/details/gt2piwplxso.html

[T42] Perl：变量类型
来源：http://dali.c1oappe.top/Article/details/gt2vsyklohg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj20258888.top/Article/details/gt2lcorrdpl.html

[T43] Perl：字符串插值
来源：http://dali.gzhubu.top/Article/details/gt2jwqvnfsh.html

"值: $a"
来源：http://dali.yj202588.top/Article/details/gt2rsnskbee.html

[T44] Perl：条件
来源：http://dali.shuidangran.top/Article/details/gt2eytmnjxl.html

if ($a > 0) { print "正"; }
来源：http://dali.tanke756.top/Article/details/gt2hxdnhwss.html

[T45] Perl：数组遍历
来源：http://dali.nanxinkj.top/Article/details/gt2sneiuiks.html

for my $x (@arr) { print $x; }
来源：http://dali.yj202588.top/Article/details/gt2pphfpbsb.html

[T46] Perl：哈希操作
来源：http://dali.nwbrower.top/Article/details/gt2aumougov.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.birdmap.top/Article/details/gt2fhpfmgtv.html

[T47] Perl：正则捕获
来源：http://dali.zhiwuduotai.top/Article/details/gt2xsmyajdz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xuanzx.com/Article/details/gt2frfigvdr.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eqthlodh.html

$s =~ s/old/new/g;
来源：http://dali.ybcxt.top/Article/details/gt2yutfxntu.html

[T49] Perl：函数
来源：http://dali.xziqi.cn/Article/details/gt2dwbfrjqo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2mrcarihd.html

[T50] Perl：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gt2msgtmftg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cdnleiting.top/Article/details/gt2bcoameky.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.andypj.xyz/Article/details/gt2rodcetjg.html

[T51] Scala：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2vdruencr.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ohvelqcg.html

[T52] Scala：变量
来源：http://dali.smart0.xyz/Article/details/gt2qfozfhkj.html

val a = 1;  var b = 2
来源：http://dali.zhengqikj.top/Article/details/gt2eniyyrjg.html

[T53] Scala：字符串插值
来源：http://dali.fzhhl.top/Article/details/gt2qhybynej.html

s"值: $b"
来源：http://dali.yj202588.top/Article/details/gt2otxnynre.html

[T54] Scala：集合映射
来源：http://dali.tian-w.cn/Article/details/gt2sogcmvdw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yangfankeji.com/Article/details/gt2slexmveu.html

[T55] Scala：集合过滤
来源：http://dali.hnqzz.top/Article/details/gt2bnunnalg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ydzc1.top/Article/details/gt2gkwcuhhy.html

[T56] Scala：样例类
来源：http://dali.xuetiantiany.cn/Article/details/gt2bklxrmql.html

case class User(name: String, age: Int)
来源：http://dali.redwolf501.top/Article/details/gt2vpctjivq.html

[T57] Scala：模式匹配
来源：http://dali.meibo888.top/Article/details/gt2vpkdkfgd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pmvnpelq.html

[T58] Scala：函数定义
来源：http://dali.andypj.xyz/Article/details/gt2zrforlwq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daria6918.cn/Article/details/gt2hfvpgdnb.html

[T59] Scala：循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2yhkpjpix.html

for (i <- 1 to 10) println(i)
来源：http://dali.yvedp.cn/Article/details/gt2xsnopbzb.html

[T60] Scala：折叠
来源：http://dali.jqgfzy.top/Article/details/gt2hxrzdijy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.snrcjt.cn/Article/details/gt2wrwlotul.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2xvoqphtt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.redwolf501.top/Article/details/gt2orrpbzrp.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2phjmrblj.html

[U01] Py：创建虚拟环境
来源：http://dali.yj20258888.top/Article/details/gt2dqcnqlcp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dashuyun.cn/Article/details/gt2ooruzvxu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.c1oappe.top/Article/details/gt2zpzrplot.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daria6918.cn/Article/details/gt2zhmotasu.html

[U03] Py：加载 .env 配置
来源：http://dali.dianchejie.cn/Article/details/gt2ctbxpvdf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ieejhcom.html

[U04] Py：变量调试打印
来源：http://dali.ivvv.top/Article/details/gt2wkeuzpyh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cashguo.top/Article/details/gt2vwkqjxjd.html

[U05] Py：列表去重且保序
来源：http://dali.zdqjudy.top/Article/details/gt2jyifoxla.html

list(dict.fromkeys(arr))
来源：http://dali.redwolf501.top/Article/details/gt2lbqbtluh.html

[U06] Py：合并两个字典
来源：http://dali.gotoacloud.top/Article/details/gt2ckoebzwo.html

{**a, **b}
来源：http://dali.aibaodan.cn/Article/details/gt2kgudipdm.html

[U07] Py：反转字典键值
来源：http://dali.jqgfzy.top/Article/details/gt2ohjojlfr.html

{v: k for k, v in d.items()}
来源：http://dali.ybcxt.top/Article/details/gt2jzqtspba.html

[U08] Py：展平二维列表
来源：http://dali.shuidangran.top/Article/details/gt2woiyqgbw.html

[y for x in nested for y in x]
来源：http://dali.guannengcc.top/Article/details/gt2okxabjwc.html

[U09] Py：字典取最大值的键
来源：http://dali.yonumen.top/Article/details/gt2urkbohky.html

max(d, key=d.get)
来源：http://dali.xinyue.icu/Article/details/gt2pavsaznp.html

[U10] Py：按值排序字典
来源：http://dali.svipenyu.cn/Article/details/gt2bmcohphd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenjidiqi.icu/Article/details/gt2xlbojcmk.html

[U11] Py：生成器表达式
来源：http://dali.zhixingplan.top/Article/details/gt2fxravaem.html

(x * 2 for x in arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2wmwblcxu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.redwolf501.top/Article/details/gt2qhmlepdi.html

Counter(arr).most_common(3)
来源：http://dali.yangfankeji.com/Article/details/gt2opvnfhdn.html

[U13] Py：固定长度队列
来源：http://dali.ppjwa.cn/Article/details/gt2mtsoejhe.html

deque(maxlen=10)
来源：http://dali.zhoulong.xyz/Article/details/gt2sdryatfw.html

[U14] Py：分组收集到列表
来源：http://dali.nwbrower.top/Article/details/gt2lceoyuvr.html

defaultdict(list)
来源：http://dali.dashuyun.cn/Article/details/gt2tcocyjgr.html

[U15] Py：高精度计时
来源：http://dali.jinqigfzy.top/Article/details/gt2ozadjwtb.html

t = time.perf_counter()
来源：http://dali.xziqi.cn/Article/details/gt2jehhrlxb.html

[U16] Py：命令行参数解析
来源：http://dali.zhongyouzk.top/Article/details/gt2hngidxwl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ydzc1.top/Article/details/gt2zzhweraz.html

[U17] Py：初始化日志
来源：http://dali.jqgfzy.top/Article/details/gt2phesfczd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.snrcjt.cn/Article/details/gt2umqjifdc.html

[U18] Py：预编译正则
来源：http://dali.cdnleiting.top/Article/details/gt2stxyyotj.html

pat = re.compile(r"\d+")
来源：http://dali.bjfxy.top/Article/details/gt2sqrzdqyk.html

[U19] Py：正则替换带回调
来源：http://dali.hysaishi.cn/Article/details/gt2gorjufwc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuanzhike.top/Article/details/gt2ojbbthuz.html

[U20] Py：缓存函数结果
来源：http://dali.snrcjt.cn/Article/details/gt2iwybseta.html

@functools.lru_cache(maxsize=None)
来源：http://dali.iojbl.cn/Article/details/gt2ijydekbh.html

[U21] Py：自定义上下文管理器
来源：http://dali.ydzc1.top/Article/details/gt2sqvunmvc.html

@contextlib.contextmanager
来源：http://dali.316326.xyz/Article/details/gt2xyjhpdzs.html

[U22] Py：矩阵转置
来源：http://dali.dianchejie.cn/Article/details/gt2xpbyfvom.html

list(zip(*m))
来源：http://dali.tanke756.top/Article/details/gt2szqcwlts.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vpprteso.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ivvv.top/Article/details/gt2fvddilax.html

[U24] Py：路径操作
来源：http://dali.vqdsnc.cn/Article/details/gt2nlvgqbni.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.havefunace.top/Article/details/gt2elldumdk.html

[U25] Py：CSV 按字典读
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvxzpopu.html

csv.DictReader(f)
来源：http://dali.hnqzz.top/Article/details/gt2otgzwjtj.html

[U26] Py：并发下载
来源：http://dali.yongpay.top/Article/details/gt2qfbkrihz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shuidangran.top/Article/details/gt2kejbufox.html

[U27] Py：异步 HTTP
来源：http://dali.xylfe.cn/Article/details/gt2fplrcpcy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hnxiangtu.top/Article/details/gt2zxbfribq.html

[U28] Py：类型别名
来源：http://dali.sufxvd.cn/Article/details/gt2edzylruj.html

UserId = int
来源：http://dali.ppjwa.cn/Article/details/gt2qpziabsf.html

[U29] Py：属性校验
来源：http://dali.jqgufenzy.top/Article/details/gt2wromgken.html

@property 与 @x.setter 配合
来源：http://dali.hysaishi.cn/Article/details/gt2jrkqgocb.html

[U30] Py：数据类
来源：http://dali.hfpthk.cn/Article/details/gt2uaxixpfq.html

@dataclass(slots=True)
来源：http://dali.ybcxt.top/Article/details/gt2rlimsvtt.html

[U31] Py：单测
来源：http://dali.ydzc1.top/Article/details/gt2jmyvpyws.html

python -m pytest -q
来源：http://dali.shzxlz.cn/Article/details/gt2gllchexf.html

[U32] Py：代码格式化
来源：http://dali.guannengcc.top/Article/details/gt2cwelvuoy.html

ruff format . && ruff check --fix .
来源：http://dali.zhoulong.xyz/Article/details/gt2xisicccw.html

[U33] Py：打包发布
来源：http://dali.kuanghao11.cn/Article/details/gt2azblskyd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cheryme.top/Article/details/gt2kbwkbtjj.html

[U34] Py：判断编码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ixksyfpr.html

chardet.detect(raw)
来源：http://dali.dashuyun.cn/Article/details/gt2hrqtrvuq.html

[U35] Py：发送邮件
来源：http://dali.yvedp.cn/Article/details/gt2ggooinlv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hywenlv.cn/Article/details/gt2gdviioqt.html

[U36] Py：定时任务
来源：http://dali.fengsongda.top/Article/details/gt2baguqiaq.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qngefkil.html

[U37] Py：读写 Excel
来源：http://dali.wangdashe.top/Article/details/gt2gvbtxuko.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.iojbl.cn/Article/details/gt2rydwqpan.html

[U38] Py：获取脚本所在目录
来源：http://dali.shzxlz.cn/Article/details/gt2rjdwxaev.html

Path(__file__).resolve().parent
来源：http://dali.chenzaomai.com/Article/details/gt2ocsumzdn.html

[U39] Py：判断是否在交互环境
来源：http://dali.xuanzx.com/Article/details/gt2xfxntttf.html

sys.stdout.isatty()
来源：http://dali.gaohongyu789.top/Article/details/gt2qznnfrec.html

[U40] Py：打印到标准错误
来源：http://dali.smart0.xyz/Article/details/gt2cnuepqce.html

print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gt2xcfvhgpa.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jlsjyb.cn/Article/details/gt2hasbdrvh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jianghu66.top/Article/details/gt2psluwywo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhiwuduotai.top/Article/details/gt2umeoznpw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nwbrower.top/Article/details/gt2fmchndut.html

[U43] PHP：声明命名空间
来源：http://dali.dianchejie.cn/Article/details/gt2vfepswqh.html

namespace App\Http;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gfrpvjwb.html

[U44] PHP：开启严格类型
来源：http://dali.hysaishi.cn/Article/details/gt2wcauksug.html

declare(strict_types=1);
来源：http://dali.cashguo.top/Article/details/gt2kxbdsfqu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cashguo.top/Article/details/gt2vitsdeyx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gt2ezskslzp.html

[U46] PHP：可空类型
来源：http://dali.tanke756.top/Article/details/gt2caxmphmw.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2gofbpmgb.html

[U47] PHP：联合类型
来源：http://dali.yj20258.top/Article/details/gt2vlqtphqa.html

int|string $id
来源：http://dali.hfpthk.cn/Article/details/gt2abegqfmb.html

[U48] PHP：纯枚举
来源：http://dali.jiagoushi.top/Article/details/gt2wgrvfplz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sxryk.cn/Article/details/gt2fmsfxrqt.html

[U49] PHP：只读属性
来源：http://dali.zhongyouzk.top/Article/details/gt2ddqetkwt.html

public readonly string $name
来源：http://dali.xuanzx.com/Article/details/gt2xnsdflzg.html

[U50] PHP：构造器属性提升
来源：http://dali.cashguo.top/Article/details/gt2yfasygmk.html

public function __construct(private int $id) {}
来源：http://dali.sxryk.cn/Article/details/gt2gpdoleds.html

[U51] PHP：数组解构
来源：http://dali.316326.xyz/Article/details/gt2ipeylwyu.html

[$a, $b] = $arr;
来源：http://dali.cheryme.top/Article/details/gt2gsukksmk.html

[U52] PHP：箭头函数
来源：http://dali.daxiang520.top/Article/details/gt2swrfrgpg.html

$double = fn($x) => $x * 2;
来源：http://dali.iojbl.cn/Article/details/gt2jlstsmwo.html

[U53] PHP：空合并运算符
来源：http://dali.aibaodan.cn/Article/details/gt2ftqmblsi.html

$v = $a ?? $b ?? "default";
来源：http://dali.daria6918.cn/Article/details/gt2qayfxwgj.html

[U54] PHP：空安全调用
来源：http://dali.ivvv.top/Article/details/gt2dnrvlyte.html

$obj?->method()
来源：http://dali.zhengqikj.top/Article/details/gt2shvupuce.html

[U55] PHP：match 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2mghzjapd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gt2uwdomwev.html

[U56] PHP：命名参数
来源：http://dali.aibaodan.cn/Article/details/gt2aydcoxzt.html

f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2recvbpvw.html

[U57] PHP：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gt2tsaoznhh.html

"值: {$a}"
来源：http://dali.haohaochexian.top/Article/details/gt2oigcltym.html

[U58] PHP：数组三件套
来源：http://dali.haohaochexian.top/Article/details/gt2xufwzhoq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2lwjbokwl.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkgidqh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daria6918.cn/Article/details/gt2annbamgn.html

[U60] PHP：JSON 编解码
来源：http://dali.zhiwuduotai.top/Article/details/gt2xnfscbvg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.haohaochexian.top/Article/details/gt2uqzahuwz.html


<!-- 参考信息 -->