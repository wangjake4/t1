代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ferveiio.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gzhubu.top/Article/details/gt2fxopkalm.html

[S40] C++：查找元素
来源：http://dali.pycfn.com/Article/details/gt2qhfmywkc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2udgqfqhe.html

[S41] C++：类与构造函数
来源：http://dali.yj20258888.top/Article/details/gt2tioobprr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnxiangtu.top/Article/details/gt2grtpuggw.html

[S42] C++：继承与虚函数
来源：http://dali.vqdsnc.cn/Article/details/gt2gslgnebl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhongyouzk.top/Article/details/gt2kavoglxm.html

[S43] C++：智能指针
来源：http://dali.jinqigufen.top/Article/details/gt2xrukdnad.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj202588.top/Article/details/gt2bpmufiyk.html

[S44] C++：引用传参
来源：http://dali.jlsjyb.cn/Article/details/gt2ofeozzge.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gt2pycwisjo.html

[S45] C++：lambda
来源：http://dali.jqgufenzy.top/Article/details/gt2gzeegzxv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jsrnnjnf.html

[S46] C++：函数模板
来源：http://dali.vqdsnc.cn/Article/details/gt2dlgwguwt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangdashe.top/Article/details/gt2jvkrmnbt.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mdjzjkhi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ybcxt.top/Article/details/gt2degcnkph.html

[S48] C++：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gt2jcvqceac.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxinkj.top/Article/details/gt2duhdfzzj.html

while (std::getline(in, line)) { }
来源：http://dali.gzhubu.top/Article/details/gt2seavcbmu.html

[S49] C++：写文件
来源：http://dali.dashuyun.cn/Article/details/gt2ifpqfzat.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yanxiufei.cn/Article/details/gt2xtptqpzn.html

[S50] C++：格式化数字
来源：http://dali.dianchejie.cn/Article/details/gt2qwwkucxk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gt2ptwzgatq.html

[S51] C++：显式类型转换
来源：http://dali.bjfxy.top/Article/details/gt2awmavbyb.html

static_cast<double>(a) / b
来源：http://dali.cucudq.cn/Article/details/gt2ckeguucp.html

[S52] C++：const 与 noexcept
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mdmihbvj.html

int size() const noexcept { return n_; }
来源：http://dali.chenzaomai.com/Article/details/gt2pjbdiegi.html

[S53] C++：移动语义
来源：http://dali.gaohongyu789.top/Article/details/gt2ykbilikz.html

std::vector<int> w = std::move(v);
来源：http://dali.iojbl.cn/Article/details/gt2jcqabyyi.html

[S54] C++：异常处理
来源：http://dali.daxiang520.top/Article/details/gt2ywpnnyid.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ivvv.top/Article/details/gt2oqkgcvoe.html

[S55] C++：结构化绑定
来源：http://dali.hfpthk.cn/Article/details/gt2ipzletnc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2pnuycjys.html

[S56] C++：optional
来源：http://dali.ydzc1.top/Article/details/gt2merzbfse.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tian-w.cn/Article/details/gt2zylrztyf.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gt2rzrrhrwa.html

constexpr int N = 10;
来源：http://dali.chenzaomai.com/Article/details/gt2qvcvffcx.html

[S58] C++：命名空间
来源：http://dali.yuxming.cn/Article/details/gt2qomxjndz.html

namespace ns { int f() { return 1; } }
来源：http://dali.ivvv.top/Article/details/gt2ixmewncp.html

[S59] C++：静态断言
来源：http://dali.hammf.cn/Article/details/gt2pxizbypy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jyoumei.cn/Article/details/gt2nnjcrgtw.html

[S60] C++：遍历并删除元素
来源：http://dali.smart0.xyz/Article/details/gt2cqsytluw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yvedp.cn/Article/details/gt2zfudozur.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2laounblc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cashguo.top/Article/details/gt2btqbasbk.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ervxaiah.html

[T01] Kotlin：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2taiomiya.html

println("Hello")
来源：http://dali.dianchejie.cn/Article/details/gt2aokziwca.html

[T02] Kotlin：变量
来源：http://dali.c1oappe.top/Article/details/gt2ouxogpzj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxuanxn.top/Article/details/gt2goszwzgz.html

[T03] Kotlin：字符串模板
来源：http://dali.zdqjudy.top/Article/details/gt2eugtenuf.html

"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gt2surhttvw.html

[T04] Kotlin：空安全
来源：http://dali.xylfe.cn/Article/details/gt2fdccowvf.html

val n: String? = null;  n?.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2cuytcfqq.html

[T05] Kotlin：when 表达式
来源：http://dali.kuanghao11.cn/Article/details/gt2ttjshoed.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.andypj.xyz/Article/details/gt2vgychmtc.html

[T06] Kotlin：集合映射
来源：http://dali.cdnleiting.top/Article/details/gt2axgnjcbb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yvedp.cn/Article/details/gt2ppwukbwe.html

[T07] Kotlin：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gt2vdsdjywt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gt2ruidjvbi.html

[T08] Kotlin：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2edpriobu.html

data class User(val name: String, val age: Int)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kzxuuczp.html

[T09] Kotlin：扩展函数
来源：http://dali.fzhhl.top/Article/details/gt2xpxlrakj.html

fun String.exclaim() = this + "!"
来源：http://dali.jyoumei.cn/Article/details/gt2ujgmetnt.html

[T10] Kotlin：默认参数
来源：http://dali.birdmap.top/Article/details/gt2ztcqrffw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cqqwz.cn/Article/details/gt2bixgojhr.html

[T11] Kotlin：协程
来源：http://dali.yj20258.top/Article/details/gt2qenfpckb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenlongwang.top/Article/details/gt2hfbvzutn.html

[T12] Kotlin：解构声明
来源：http://dali.cashguo.top/Article/details/gt2ohrqzzcs.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2kuutmsah.html

[T13] Kotlin：只读 Map
来源：http://dali.jlsjyb.cn/Article/details/gt2ulcgzwdk.html

val m = mapOf("a" to 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bkumpsqz.html

[T14] Kotlin：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wjjxifal.html

for (i in 1..10) println(i)
来源：http://dali.fengsongda.top/Article/details/gt2zbnymbol.html

[T15] Kotlin：接口
来源：http://dali.yuxming.cn/Article/details/gt2eqdgamut.html

interface Shape { fun area(): Double }
来源：http://dali.jianghu66.top/Article/details/gt2joldoxih.html

[T16] Swift：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2xuwgrtfj.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gt2tvotwnia.html

[T17] Swift：变量与常量
来源：http://dali.hysaishi.cn/Article/details/gt2uesdblpx.html

var a = 1;  let b = 2
来源：http://dali.tianlin.xyz/Article/details/gt2ljvqhmtt.html

[T18] Swift：字符串插值
来源：http://dali.xinyue.icu/Article/details/gt2ttlwxfrv.html

"值: \(b)"
来源：http://dali.yongpay.top/Article/details/gt2upxnsvyp.html

[T19] Swift：可选绑定
来源：http://dali.zhixingplan.top/Article/details/gt2lfejqbqq.html

if let n = opt { print(n) }
来源：http://dali.chenzaomai.com/Article/details/gt2iymzfhib.html

[T20] Swift：数组操作
来源：http://dali.redwolf501.top/Article/details/gt2fjkktkqe.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258.top/Article/details/gt2xzqktwks.html

[T21] Swift：遍历
来源：http://dali.zhixingplan.top/Article/details/gt2kqosgewe.html

for x in a { print(x) }
来源：http://dali.vqdsnc.cn/Article/details/gt2okkuweqc.html

[T22] Swift：字典
来源：http://dali.cucudq.cn/Article/details/gt2xtulzdct.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.wangdashe.top/Article/details/gt2uddxorkk.html

[T23] Swift：函数
来源：http://dali.mhx1999.top/Article/details/gt2kcimnerp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hnxiangtu.top/Article/details/gt2smeogpsd.html

[T24] Swift：闭包
来源：http://dali.xuetiantiany.cn/Article/details/gt2gtnrtuyo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fengsongda.top/Article/details/gt2bdvygdml.html

[T25] Swift：结构体
来源：http://dali.birdmap.top/Article/details/gt2uaizowoo.html

struct P { var x: Int }
来源：http://dali.zdqjudy.top/Article/details/gt2phpdibsb.html

[T26] Swift：类与重写
来源：http://dali.meibo888.top/Article/details/gt2chzhynrz.html

class A: Base { override func f() {} }
来源：http://dali.zhoulong.xyz/Article/details/gt2ybibycrt.html

[T27] Swift：错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2citpvzhb.html

do { try f() } catch { print(error) }
来源：http://dali.sysykeji.top/Article/details/gt2xkfhvjbm.html

[T28] Swift：枚举
来源：http://dali.tanke756.top/Article/details/gt2uztkvztf.html

enum Color { case red, green }
来源：http://dali.fzhhl.top/Article/details/gt2gweagkns.html

[T29] Swift：guard 提前返回
来源：http://dali.chenjidiqi.icu/Article/details/gt2vdvhkcrj.html

guard let x = opt else { return }
来源：http://dali.nanxuanxn.top/Article/details/gt2kjhofmnr.html

[T30] Swift：协议
来源：http://dali.gaohongyu789.top/Article/details/gt2mmdatocb.html

protocol Shape { func area() -> Double }
来源：http://dali.shuidangran.top/Article/details/gt2eqauoogj.html

[T31] Lua：Hello World
来源：http://dali.cheryme.top/Article/details/gt2rlyhjwfr.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gt2pmwfqfbb.html

[T32] Lua：局部变量
来源：http://dali.jqgfzy.top/Article/details/gt2vyzseygi.html

local a = 1
来源：http://dali.nanxuanxn.top/Article/details/gt2gcxomuan.html

[T33] Lua：表（数组）
来源：http://dali.jianghu66.top/Article/details/gt2elmvsnzh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258.top/Article/details/gt2ueoxznbq.html

[T34] Lua：遍历表
来源：http://dali.zhoulong.xyz/Article/details/gt2oeehprkp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pycfn.com/Article/details/gt2jbppowku.html

[T35] Lua：字典表
来源：http://dali.ivvv.top/Article/details/gt2dckatkqz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sxryk.cn/Article/details/gt2dpmrezsv.html

[T36] Lua：函数
来源：http://dali.jinqigfzy.top/Article/details/gt2qjpjqsha.html

function add(a, b) return a + b end
来源：http://dali.gzhubu.top/Article/details/gt2dxfykfka.html

[T37] Lua：字符串拼接
来源：http://dali.cashguo.top/Article/details/gt2hfxellnb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2btcutfqy.html

[T38] Lua：条件
来源：http://dali.sxryk.cn/Article/details/gt2kqdfcwap.html

if x > 0 then print("正") end
来源：http://dali.jianghu66.top/Article/details/gt2gzjsajyf.html

[T39] Lua：模式匹配
来源：http://dali.pycfn.com/Article/details/gt2xiogakgb.html

string.find(s, "%d+")
来源：http://dali.yj20258.top/Article/details/gt2yfpnadao.html

[T40] Lua：元表
来源：http://dali.hongshengwenyu.top/Article/details/gt2gdmpikus.html

setmetatable({}, { __index = base })
来源：http://dali.ivvv.top/Article/details/gt2pgurlqty.html

[T41] Perl：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2lbganeri.html

print "Hello\n";
来源：http://dali.cucudq.cn/Article/details/gt2zlaxteds.html

[T42] Perl：变量类型
来源：http://dali.tanke756.top/Article/details/gt2oxjmfxjv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sysykeji.top/Article/details/gt2jezywjlo.html

[T43] Perl：字符串插值
来源：http://dali.yj20258.top/Article/details/gt2hglfqibe.html

"值: $a"
来源：http://dali.havefunace.top/Article/details/gt2gdavjkhw.html

[T44] Perl：条件
来源：http://dali.wangdashe.top/Article/details/gt2epmtrngy.html

if ($a > 0) { print "正"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2wnmrlkqc.html

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gt2nuncfxfn.html

for my $x (@arr) { print $x; }
来源：http://dali.andypj.xyz/Article/details/gt2ydiufkhx.html

[T46] Perl：哈希操作
来源：http://dali.zhoulong.xyz/Article/details/gt2uybifczq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj20258888.top/Article/details/gt2nxnjpvap.html

[T47] Perl：正则捕获
来源：http://dali.316326.xyz/Article/details/gt2cwjwgrtx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.fengsongda.top/Article/details/gt2evrxpern.html

[T48] Perl：正则替换
来源：http://dali.yj20258888.top/Article/details/gt2xvxfknam.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tcbzvsse.html

[T49] Perl：函数
来源：http://dali.ydzc1.top/Article/details/gt2iuiyvdbk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gt2gsbigsaa.html

[T50] Perl：逐行读文件
来源：http://dali.sweek.top/Article/details/gt2upzxuhnz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hongshengwenyu.top/Article/details/gt2adtdekbi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.vqdsnc.cn/Article/details/gt2hwwefsno.html

[T51] Scala：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2fpqtziys.html

println("Hello")
来源：http://dali.chenlongwang.top/Article/details/gt2wrmaqgdn.html

[T52] Scala：变量
来源：http://dali.316326.xyz/Article/details/gt2krjmijfl.html

val a = 1;  var b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2yynaipmj.html

[T53] Scala：字符串插值
来源：http://dali.sxryk.cn/Article/details/gt2ktekfmqn.html

s"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gt2tmshzgkm.html

[T54] Scala：集合映射
来源：http://dali.ivvv.top/Article/details/gt2yryivbdo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ivvv.top/Article/details/gt2hazguygl.html

[T55] Scala：集合过滤
来源：http://dali.fengsongda.top/Article/details/gt2kkkiydnd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sedrbzwr.html

[T56] Scala：样例类
来源：http://dali.dashuyun.cn/Article/details/gt2zhmidowr.html

case class User(name: String, age: Int)
来源：http://dali.kuanghao11.cn/Article/details/gt2tjlnguyv.html

[T57] Scala：模式匹配
来源：http://dali.birdmap.top/Article/details/gt2ktdyrhrn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cqqwz.cn/Article/details/gt2hlishqhx.html

[T58] Scala：函数定义
来源：http://dali.tian-w.cn/Article/details/gt2eetltvxo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cashguo.top/Article/details/gt2nvnhdasn.html

[T59] Scala：循环
来源：http://dali.jinqigfzy.top/Article/details/gt2wdtcthlm.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj20258.top/Article/details/gt2tpswrmfa.html

[T60] Scala：折叠
来源：http://dali.jqgufenzy.top/Article/details/gt2jhaomomw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxinkj.top/Article/details/gt2lnmnzxon.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2dplnvlds.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gt2ujqyqpli.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ouzmiygv.html

[U01] Py：创建虚拟环境
来源：http://dali.xylfe.cn/Article/details/gt2tpwtmpdv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenzaomai.com/Article/details/gt2tgnzvbbe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.smart0.xyz/Article/details/gt2aeqnghma.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tanke756.top/Article/details/gt2zwozncnn.html

[U03] Py：加载 .env 配置
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jirdlevl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.meibo888.top/Article/details/gt2zbbmrwwa.html

[U04] Py：变量调试打印
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rlphffco.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.birdmap.top/Article/details/gt2grsyzgle.html

[U05] Py：列表去重且保序
来源：http://dali.yangfankeji.com/Article/details/gt2qhcbtjzb.html

list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gt2sfomsuah.html

[U06] Py：合并两个字典
来源：http://dali.cucudq.cn/Article/details/gt2zajmgpep.html

{**a, **b}
来源：http://dali.yonumen.top/Article/details/gt2jguqujkb.html

[U07] Py：反转字典键值
来源：http://dali.iojbl.cn/Article/details/gt2gtycxxhu.html

{v: k for k, v in d.items()}
来源：http://dali.cqqwz.cn/Article/details/gt2jqnpzpqf.html

[U08] Py：展平二维列表
来源：http://dali.zhoulong.xyz/Article/details/gt2jffpmlwf.html

[y for x in nested for y in x]
来源：http://dali.jlsjyb.cn/Article/details/gt2bmedfibv.html

[U09] Py：字典取最大值的键
来源：http://dali.sweek.top/Article/details/gt2lqbcwzvc.html

max(d, key=d.get)
来源：http://dali.zhongyouzk.top/Article/details/gt2bvxizqfw.html

[U10] Py：按值排序字典
来源：http://dali.jinghuilouyu.cn/Article/details/gt2avnzkuwh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nanxuanxn.top/Article/details/gt2bscgbpfk.html

[U11] Py：生成器表达式
来源：http://dali.yanxiufei.cn/Article/details/gt2zwtowqwa.html

(x * 2 for x in arr)
来源：http://dali.hnqzz.top/Article/details/gt2yzjhccop.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.vqdsnc.cn/Article/details/gt2ovaxgiua.html

Counter(arr).most_common(3)
来源：http://dali.ydzc1.top/Article/details/gt2amuwtrle.html

[U13] Py：固定长度队列
来源：http://dali.aizwys.cn/Article/details/gt2grdmyvtq.html

deque(maxlen=10)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bohravai.html

[U14] Py：分组收集到列表
来源：http://dali.gogol.net.cn/Article/details/gt2lnjgznyw.html

defaultdict(list)
来源：http://dali.cqqwz.cn/Article/details/gt2onvltpix.html

[U15] Py：高精度计时
来源：http://dali.yuanzhike.top/Article/details/gt2ggtfdxud.html

t = time.perf_counter()
来源：http://dali.guannengcc.top/Article/details/gt2dywgmfxv.html

[U16] Py：命令行参数解析
来源：http://dali.daxiang520.top/Article/details/gt2ncfdlxiw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gaohongyu789.top/Article/details/gt2nolcjnuk.html

[U17] Py：初始化日志
来源：http://dali.aibaodan.cn/Article/details/gt2ffwlonlj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cdnleiting.top/Article/details/gt2bavtevya.html

[U18] Py：预编译正则
来源：http://dali.hywenlv.cn/Article/details/gt2dgoolilv.html

pat = re.compile(r"\d+")
来源：http://dali.jiagoushi.top/Article/details/gt2zmhrqdoy.html

[U19] Py：正则替换带回调
来源：http://dali.yonumen.top/Article/details/gt2tenbutwd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nwbrower.top/Article/details/gt2dltcaopu.html

[U20] Py：缓存函数结果
来源：http://dali.cqqwz.cn/Article/details/gt2hbjkaiqi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.meibo888.top/Article/details/gt2gttghpjo.html

[U21] Py：自定义上下文管理器
来源：http://dali.nanxinkj.top/Article/details/gt2lhywdbas.html

@contextlib.contextmanager
来源：http://dali.jqgufenzy.top/Article/details/gt2zgcenicu.html

[U22] Py：矩阵转置
来源：http://dali.wangshuangyany.cn/Article/details/gt2qioycwvo.html

list(zip(*m))
来源：http://dali.9152youxi.cn/Article/details/gt2bfdvkdwz.html

[U23] Py：分块读取大文件
来源：http://dali.jyoumei.cn/Article/details/gt2rjhghfso.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jyoumei.cn/Article/details/gt2lpelxfou.html

[U24] Py：路径操作
来源：http://dali.sxryk.cn/Article/details/gt2hxmumxmd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xylfe.cn/Article/details/gt2fefoqaaq.html

[U25] Py：CSV 按字典读
来源：http://dali.tanke756.top/Article/details/gt2dlkbjauh.html

csv.DictReader(f)
来源：http://dali.hammf.cn/Article/details/gt2zzoyqoyn.html

[U26] Py：并发下载
来源：http://dali.jinqigufen.top/Article/details/gt2qcwdhnsx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.mhx1999.top/Article/details/gt2kercbogn.html

[U27] Py：异步 HTTP
来源：http://dali.pycfn.com/Article/details/gt2kewgvibf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xylfe.cn/Article/details/gt2cldlfhck.html

[U28] Py：类型别名
来源：http://dali.yvedp.cn/Article/details/gt2aporxiwz.html

UserId = int
来源：http://dali.sysykeji.top/Article/details/gt2usbflyqu.html

[U29] Py：属性校验
来源：http://dali.yj20258888.top/Article/details/gt2zebspujz.html

@property 与 @x.setter 配合
来源：http://dali.redwolf501.top/Article/details/gt2gqxnowdi.html

[U30] Py：数据类
来源：http://dali.yueranfly.top/Article/details/gt2yvquknwd.html

@dataclass(slots=True)
来源：http://dali.pengpengdd.cyou/Article/details/gt2orovljsj.html

[U31] Py：单测
来源：http://dali.chenlongwang.top/Article/details/gt2ytmtplof.html

python -m pytest -q
来源：http://dali.gotoacloud.top/Article/details/gt2bgjnkgsv.html

[U32] Py：代码格式化
来源：http://dali.jqgfzy.top/Article/details/gt2ufzmncan.html

ruff format . && ruff check --fix .
来源：http://dali.feifeiyinyue.top/Article/details/gt2lyriyfzq.html

[U33] Py：打包发布
来源：http://dali.gaohongyu789.top/Article/details/gt2exbyxefx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.wangshuangyany.cn/Article/details/gt2klrgegnx.html

[U34] Py：判断编码
来源：http://dali.yanxiufei.cn/Article/details/gt2hruwpfcs.html

chardet.detect(raw)
来源：http://dali.nanxinkj.top/Article/details/gt2kjefkqlq.html

[U35] Py：发送邮件
来源：http://dali.chenlongwang.top/Article/details/gt2ttjhmbzh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xylfe.cn/Article/details/gt2hmmtqdnr.html

[U36] Py：定时任务
来源：http://dali.jinqigfzy.top/Article/details/gt2bxhwmfgz.html

schedule.every(10).minutes.do(job)
来源：http://dali.yuanzhike.top/Article/details/gt2zkpaprrp.html

[U37] Py：读写 Excel
来源：http://dali.fengsongda.top/Article/details/gt2zqkkobqm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hywenlv.cn/Article/details/gt2kbxmbgiw.html

[U38] Py：获取脚本所在目录
来源：http://dali.hywenlv.cn/Article/details/gt2omtuwjdl.html

Path(__file__).resolve().parent
来源：http://dali.sxryk.cn/Article/details/gt2jswnntiq.html

[U39] Py：判断是否在交互环境
来源：http://dali.jqgufenzy.top/Article/details/gt2osvznrca.html

sys.stdout.isatty()
来源：http://dali.tian-w.cn/Article/details/gt2lhwwcqyi.html

[U40] Py：打印到标准错误
来源：http://dali.cucudq.cn/Article/details/gt2ydvfcveq.html

print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gt2gbsibkdz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.havefunace.top/Article/details/gt2msjeghys.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yanxiufei.cn/Article/details/gt2hxpbyntn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xylfe.cn/Article/details/gt2ipwrlidr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.wangdashe.top/Article/details/gt2hiwpphsp.html

[U43] PHP：声明命名空间
来源：http://dali.hywenlv.cn/Article/details/gt2ousjmkah.html

namespace App\Http;
来源：http://dali.yangfankeji.com/Article/details/gt2zwwwcgue.html

[U44] PHP：开启严格类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nyzhwqff.html

declare(strict_types=1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ieyreuvs.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mhwggfqc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gt2hodbbntb.html

[U46] PHP：可空类型
来源：http://dali.aizwys.cn/Article/details/gt2zshjfetv.html

?string $name = null
来源：http://dali.yueranfly.top/Article/details/gt2ohisydpk.html

[U47] PHP：联合类型
来源：http://dali.yueranfly.top/Article/details/gt2ajqxridx.html

int|string $id
来源：http://dali.nanxuanxn.top/Article/details/gt2yegmkvil.html

[U48] PHP：纯枚举
来源：http://dali.chenjidiqi.icu/Article/details/gt2zdncvugs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sufxvd.cn/Article/details/gt2cvaczzot.html

[U49] PHP：只读属性
来源：http://dali.aizwys.cn/Article/details/gt2onygsycj.html

public readonly string $name
来源：http://dali.zhengqikj.top/Article/details/gt2jmaklfjw.html

[U50] PHP：构造器属性提升
来源：http://dali.zhoulong.xyz/Article/details/gt2kvyhzser.html

public function __construct(private int $id) {}
来源：http://dali.cdnleiting.top/Article/details/gt2ubuhiqlm.html

[U51] PHP：数组解构
来源：http://dali.tianlin.xyz/Article/details/gt2nougigom.html

[$a, $b] = $arr;
来源：http://dali.hongshengwenyu.top/Article/details/gt2cdcwmcbs.html

[U52] PHP：箭头函数
来源：http://dali.kuanghao11.cn/Article/details/gt2etunflhv.html

$double = fn($x) => $x * 2;
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjyvgoqc.html

[U53] PHP：空合并运算符
来源：http://dali.andypj.xyz/Article/details/gt2ctbqrhwg.html

$v = $a ?? $b ?? "default";
来源：http://dali.smart0.xyz/Article/details/gt2zkolimhk.html

[U54] PHP：空安全调用
来源：http://dali.tianlin.xyz/Article/details/gt2rqqilhwf.html

$obj?->method()
来源：http://dali.jianghu66.top/Article/details/gt2fvsemugq.html

[U55] PHP：match 表达式
来源：http://dali.zhengqikj.top/Article/details/gt2nwussxhn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2isuqbfcn.html

[U56] PHP：命名参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2unccfwzq.html

f(a: 1, b: 2)
来源：http://dali.xinyue.icu/Article/details/gt2zkkyzyri.html

[U57] PHP：字符串插值
来源：http://dali.tanke756.top/Article/details/gt2eyogzryv.html

"值: {$a}"
来源：http://dali.shuidangran.top/Article/details/gt2lvvykltp.html

[U58] PHP：数组三件套
来源：http://dali.yj202588.top/Article/details/gt2zqqkwmet.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yueranfly.top/Article/details/gt2uaqxgctt.html

[U59] PHP：自定义排序
来源：http://dali.ybcxt.top/Article/details/gt2lxizwvpf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.316326.xyz/Article/details/gt2tlyvmpgu.html

[U60] PHP：JSON 编解码
来源：http://dali.andypj.xyz/Article/details/gt2tboazbdy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.tianlin.xyz/Article/details/gt2bfykhrtp.html

[U61] PHP：正则
来源：http://dali.daria6918.cn/Article/details/gt2teiwckov.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gt2nvalpwsv.html

[U62] PHP：日期对象
来源：http://dali.cdnleiting.top/Article/details/gt2igjcbdmc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.nwbrower.top/Article/details/gt2cfaadfgr.html

[U63] PHP：文件读写
来源：http://dali.birdmap.top/Article/details/gt2bynoyvtk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhixingplan.top/Article/details/gt2aspdhsgm.html

[U64] PHP：目录遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2wdmuqhdt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cashguo.top/Article/details/gt2nnhdludi.html


<!-- 参考信息 -->