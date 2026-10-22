代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.sweek.top/Article/details/gt2lzmteyuu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2ljhhlkyn.html

[S42] C++：继承与虚函数
来源：http://dali.andypj.xyz/Article/details/gt2ecpbrtjs.html

class B : public Base { public: void f() override {} };
来源：http://dali.svipenyu.cn/Article/details/gt2twbljrky.html

[S43] C++：智能指针
来源：http://dali.zhongyouzk.top/Article/details/gt2afqgonyh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zycfv.cn/Article/details/gt2lrghcqvm.html

[S44] C++：引用传参
来源：http://dali.shzxlz.cn/Article/details/gt2ytyklncq.html

void inc(int &x) { ++x; }
来源：http://dali.zdqjudy.top/Article/details/gt2fudppxdh.html

[S45] C++：lambda
来源：http://dali.redwolf501.top/Article/details/gt2zoisaijp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fengsongda.top/Article/details/gt2ljajpowg.html

[S46] C++：函数模板
来源：http://dali.hammf.cn/Article/details/gt2aahabuet.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guannengcc.top/Article/details/gt2xilubqlc.html

[S47] C++：结构化绑定遍历
来源：http://dali.0kj1m.cn/Article/details/gt2eagrllpw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gotoacloud.top/Article/details/gt2qjbtyfab.html

[S48] C++：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gt2mlkwelwk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eovwchdm.html

while (std::getline(in, line)) { }
来源：http://dali.guowangkeji.top/Article/details/gt2eulguily.html

[S49] C++：写文件
来源：http://dali.aizwys.cn/Article/details/gt2dbklapoc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.316326.xyz/Article/details/gt2essdajka.html

[S50] C++：格式化数字
来源：http://dali.ybcxt.top/Article/details/gt2wkgmzukx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpnlgwau.html

[S51] C++：显式类型转换
来源：http://dali.sxryk.cn/Article/details/gt2bsmgocth.html

static_cast<double>(a) / b
来源：http://dali.yj20258888.top/Article/details/gt2vtaugwjl.html

[S52] C++：const 与 noexcept
来源：http://dali.chenjidiqi.icu/Article/details/gt2kfjkeosv.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juzijbvp.html

[S53] C++：移动语义
来源：http://dali.chenzaomai.com/Article/details/gt2jyeielad.html

std::vector<int> w = std::move(v);
来源：http://dali.xziqi.cn/Article/details/gt2ofmtdgmf.html

[S54] C++：异常处理
来源：http://dali.birdmap.top/Article/details/gt2wktixkfl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fiqmtrcf.html

[S55] C++：结构化绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdphnaiq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hywenlv.cn/Article/details/gt2rubbnpxm.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gt2xdyksslu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gogol.net.cn/Article/details/gt2spsnfnaf.html

[S57] C++：编译期常量
来源：http://dali.yueranfly.top/Article/details/gt2aufydmha.html

constexpr int N = 10;
来源：http://dali.xinyue.icu/Article/details/gt2icejfthh.html

[S58] C++：命名空间
来源：http://dali.jinqigfzy.top/Article/details/gt2kbzidyrx.html

namespace ns { int f() { return 1; } }
来源：http://dali.xylfe.cn/Article/details/gt2togyhowt.html

[S59] C++：静态断言
来源：http://dali.tian-w.cn/Article/details/gt2tymomupy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhengqikj.top/Article/details/gt2zbohaaku.html

[S60] C++：遍历并删除元素
来源：http://dali.jiagoushi.top/Article/details/gt2hyrottct.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dianchejie.cn/Article/details/gt2fukvrzre.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2eugfvlot.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gt2dhaaadyg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2ejjjxijx.html

[T01] Kotlin：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2pojyfvvb.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gt2rxekuuqq.html

[T02] Kotlin：变量
来源：http://dali.yvedp.cn/Article/details/gt2louuwfai.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guowangkeji.top/Article/details/gt2mpvcunwx.html

[T03] Kotlin：字符串模板
来源：http://dali.nwbrower.top/Article/details/gt2gmtijdcd.html

"值: $b"
来源：http://dali.hammf.cn/Article/details/gt2rjayqtlp.html

[T04] Kotlin：空安全
来源：http://dali.andypj.xyz/Article/details/gt2xcintkyn.html

val n: String? = null;  n?.length
来源：http://dali.aizwys.cn/Article/details/gt2dwyzcooc.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258888.top/Article/details/gt2mbhkauhm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ejadggtt.html

[T06] Kotlin：集合映射
来源：http://dali.ydzc1.top/Article/details/gt2nbsputlo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tian-w.cn/Article/details/gt2hqphmgma.html

[T07] Kotlin：集合过滤
来源：http://dali.0kj1m.cn/Article/details/gt2zyaljydb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuanzx.com/Article/details/gt2nuwmkhvu.html

[T08] Kotlin：数据类
来源：http://dali.yueranfly.top/Article/details/gt2vlcmrlby.html

data class User(val name: String, val age: Int)
来源：http://dali.snrcjt.cn/Article/details/gt2xutkecmn.html

[T09] Kotlin：扩展函数
来源：http://dali.bjfxy.top/Article/details/gt2iutkriew.html

fun String.exclaim() = this + "!"
来源：http://dali.svipenyu.cn/Article/details/gt2hcxfvxvi.html

[T10] Kotlin：默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ebeoksms.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhengqikj.top/Article/details/gt2dyxmwaxl.html

[T11] Kotlin：协程
来源：http://dali.yongpay.top/Article/details/gt2kdinezza.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dashuyun.cn/Article/details/gt2jqozwdnj.html

[T12] Kotlin：解构声明
来源：http://dali.redwolf501.top/Article/details/gt2wrjbsmqa.html

val (a, b) = Pair(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2zogofnfw.html

[T13] Kotlin：只读 Map
来源：http://dali.guowangkeji.top/Article/details/gt2ymwciklj.html

val m = mapOf("a" to 1)
来源：http://dali.aizwys.cn/Article/details/gt2tozagxsv.html

[T14] Kotlin：循环
来源：http://dali.jlsjyb.cn/Article/details/gt2wygmuowh.html

for (i in 1..10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gt2wcqjpwpx.html

[T15] Kotlin：接口
来源：http://dali.yanxiufei.cn/Article/details/gt2zbrqqkbq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nytixinl.html

[T16] Swift：Hello World
来源：http://dali.tanke756.top/Article/details/gt2voclyqbm.html

print("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gt2vudhqopb.html

[T17] Swift：变量与常量
来源：http://dali.pycfn.com/Article/details/gt2qkyurbxs.html

var a = 1;  let b = 2
来源：http://dali.zhongyouzk.top/Article/details/gt2ydmqnatm.html

[T18] Swift：字符串插值
来源：http://dali.pycfn.com/Article/details/gt2jtkorofa.html

"值: \(b)"
来源：http://dali.dashuyun.cn/Article/details/gt2sokjntdt.html

[T19] Swift：可选绑定
来源：http://dali.snrcjt.cn/Article/details/gt2hqbzfxsl.html

if let n = opt { print(n) }
来源：http://dali.sweek.top/Article/details/gt2bljayygc.html

[T20] Swift：数组操作
来源：http://dali.zhixingplan.top/Article/details/gt2uubelehu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhoulong.xyz/Article/details/gt2ionncbss.html

[T21] Swift：遍历
来源：http://dali.cheryme.top/Article/details/gt2gijffiyk.html

for x in a { print(x) }
来源：http://dali.havefunace.top/Article/details/gt2bvttnrot.html

[T22] Swift：字典
来源：http://dali.hnxiangtu.top/Article/details/gt2srfgfegv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aibaodan.cn/Article/details/gt2kwtkznin.html

[T23] Swift：函数
来源：http://dali.jinqigfzy.top/Article/details/gt2ycpwergf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sxryk.cn/Article/details/gt2hsfqdzee.html

[T24] Swift：闭包
来源：http://dali.bjfxy.top/Article/details/gt2zhltynza.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2lxmkqxzb.html

[T25] Swift：结构体
来源：http://dali.hfpthk.cn/Article/details/gt2vvlybhxw.html

struct P { var x: Int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xqckgfpw.html

[T26] Swift：类与重写
来源：http://dali.daxiang520.top/Article/details/gt2mgboxpwq.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2olkpalnr.html

[T27] Swift：错误处理
来源：http://dali.xylfe.cn/Article/details/gt2etcoespq.html

do { try f() } catch { print(error) }
来源：http://dali.aibaodan.cn/Article/details/gt2upvosstq.html

[T28] Swift：枚举
来源：http://dali.xylfe.cn/Article/details/gt2iyswkysb.html

enum Color { case red, green }
来源：http://dali.guowangkeji.top/Article/details/gt2mtubcrns.html

[T29] Swift：guard 提前返回
来源：http://dali.zhixingplan.top/Article/details/gt2sbyvzwzs.html

guard let x = opt else { return }
来源：http://dali.shuidangran.top/Article/details/gt2xeifpdka.html

[T30] Swift：协议
来源：http://dali.zhoulong.xyz/Article/details/gt2tftmybal.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigufen.top/Article/details/gt2gfjqmdqm.html

[T31] Lua：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2ovqjopzo.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gt2fhzzavkq.html

[T32] Lua：局部变量
来源：http://dali.jianghu66.top/Article/details/gt2nupnewpf.html

local a = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ativpuml.html

[T33] Lua：表（数组）
来源：http://dali.yj20258888.top/Article/details/gt2ihzvciya.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yanxiufei.cn/Article/details/gt2jneahpdk.html

[T34] Lua：遍历表
来源：http://dali.cdnleiting.top/Article/details/gt2efjpfngf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.0kj1m.cn/Article/details/gt2lznbukur.html

[T35] Lua：字典表
来源：http://dali.cqqwz.cn/Article/details/gt2sapfnzpo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xylfe.cn/Article/details/gt2wghmkpdt.html

[T36] Lua：函数
来源：http://dali.ydzc1.top/Article/details/gt2mwcnguvl.html

function add(a, b) return a + b end
来源：http://dali.daxiang520.top/Article/details/gt2lfvtehrb.html

[T37] Lua：字符串拼接
来源：http://dali.nwbrower.top/Article/details/gt2zejdpjvi.html

"a" .. "b"
来源：http://dali.aizwys.cn/Article/details/gt2zfdpgohr.html

[T38] Lua：条件
来源：http://dali.jyoumei.cn/Article/details/gt2zuplkear.html

if x > 0 then print("正") end
来源：http://dali.jianghu66.top/Article/details/gt2ltjliipa.html

[T39] Lua：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gt2gnypsxdn.html

string.find(s, "%d+")
来源：http://dali.xuanzx.com/Article/details/gt2relttzum.html

[T40] Lua：元表
来源：http://dali.havefunace.top/Article/details/gt2qdhmaovw.html

setmetatable({}, { __index = base })
来源：http://dali.hywenlv.cn/Article/details/gt2ztbqulvu.html

[T41] Perl：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2cehohsqk.html

print "Hello\n";
来源：http://dali.vqdsnc.cn/Article/details/gt2jtmluefp.html

[T42] Perl：变量类型
来源：http://dali.cqqwz.cn/Article/details/gt2ondpjeoj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj202588.top/Article/details/gt2felkbusd.html

[T43] Perl：字符串插值
来源：http://dali.cucudq.cn/Article/details/gt2vlhmmvcd.html

"值: $a"
来源：http://dali.guannengcc.top/Article/details/gt2wtzmbvys.html

[T44] Perl：条件
来源：http://dali.jlsjyb.cn/Article/details/gt2foliitns.html

if ($a > 0) { print "正"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2llrcjzoo.html

[T45] Perl：数组遍历
来源：http://dali.svipenyu.cn/Article/details/gt2qtyrrepx.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgfzy.top/Article/details/gt2rjddjunj.html

[T46] Perl：哈希操作
来源：http://dali.yj20258888.top/Article/details/gt2vkrgbgkc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2muolowpk.html

[T47] Perl：正则捕获
来源：http://dali.wangdashe.top/Article/details/gt2ddfrfzwe.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yvedp.cn/Article/details/gt2lhfmafex.html

[T48] Perl：正则替换
来源：http://dali.yueranfly.top/Article/details/gt2webqiabo.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bkzuaftj.html

[T49] Perl：函数
来源：http://dali.jianghu66.top/Article/details/gt2enufipkd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gt2hlgxjjci.html

[T50] Perl：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2vtuzyycx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.havefunace.top/Article/details/gt2wewalwdb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hywenlv.cn/Article/details/gt2cnpscirm.html

[T51] Scala：Hello World
来源：http://dali.ivvv.top/Article/details/gt2fhfcfghw.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gt2hgnxbfsl.html

[T52] Scala：变量
来源：http://dali.yangfankeji.com/Article/details/gt2ykpuscrs.html

val a = 1;  var b = 2
来源：http://dali.wangdashe.top/Article/details/gt2plseqeyt.html

[T53] Scala：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhzcinud.html

s"值: $b"
来源：http://dali.yvedp.cn/Article/details/gt2zggwmktu.html

[T54] Scala：集合映射
来源：http://dali.fengsongda.top/Article/details/gt2gsstxcpv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hbczlshr.html

[T55] Scala：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gt2tbsujxcm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2vaqhnbuw.html

[T56] Scala：样例类
来源：http://dali.shzxlz.cn/Article/details/gt2ucfrhmru.html

case class User(name: String, age: Int)
来源：http://dali.zhixingplan.top/Article/details/gt2swuodmjk.html

[T57] Scala：模式匹配
来源：http://dali.mhx1999.top/Article/details/gt2tnjovmki.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.aizwys.cn/Article/details/gt2rdmfjfjw.html

[T58] Scala：函数定义
来源：http://dali.xuanzx.com/Article/details/gt2yzzizodc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yuanzhike.top/Article/details/gt2nionyxgj.html

[T59] Scala：循环
来源：http://dali.sweek.top/Article/details/gt2jjqtfuam.html

for (i <- 1 to 10) println(i)
来源：http://dali.xziqi.cn/Article/details/gt2sbbflddn.html

[T60] Scala：折叠
来源：http://dali.cqqwz.cn/Article/details/gt2erhljrwm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yanxiufei.cn/Article/details/gt2ujqflhvl.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2pnyaiwhj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2ircebbsp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2ojuaevno.html

[U01] Py：创建虚拟环境
来源：http://dali.ppjwa.cn/Article/details/gt2gkdmlcba.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhoulong.xyz/Article/details/gt2ircnrpgk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuanzx.com/Article/details/gt2eqcgwcvk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2usfyfrsl.html

[U03] Py：加载 .env 配置
来源：http://dali.c1oappe.top/Article/details/gt2gasopjdx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shangyingyoupin.top/Article/details/gt2duatnzwn.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangtech.top/Article/details/gt2biwikmpf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.dianchejie.cn/Article/details/gt2ktdfvtuq.html

[U05] Py：列表去重且保序
来源：http://dali.zhiwuduotai.top/Article/details/gt2oacwkrrt.html

list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gt2cmrjkhif.html

[U06] Py：合并两个字典
来源：http://dali.hywenlv.cn/Article/details/gt2recapuen.html

{**a, **b}
来源：http://dali.yongpay.top/Article/details/gt2vihkihkd.html

[U07] Py：反转字典键值
来源：http://dali.birdmap.top/Article/details/gt2blsgaofy.html

{v: k for k, v in d.items()}
来源：http://dali.pycfn.com/Article/details/gt2pjsxqtwj.html

[U08] Py：展平二维列表
来源：http://dali.jiagoushi.top/Article/details/gt2uagtftgv.html

[y for x in nested for y in x]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ajcofaqw.html

[U09] Py：字典取最大值的键
来源：http://dali.tianlin.xyz/Article/details/gt2koffrkrf.html

max(d, key=d.get)
来源：http://dali.andypj.xyz/Article/details/gt2sjjzthzs.html

[U10] Py：按值排序字典
来源：http://dali.0kj1m.cn/Article/details/gt2mioarugm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ydzc1.top/Article/details/gt2nxhudxek.html

[U11] Py：生成器表达式
来源：http://dali.guowangkeji.top/Article/details/gt2cfoxqnpg.html

(x * 2 for x in arr)
来源：http://dali.cqqwz.cn/Article/details/gt2tmzggnpt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ktulsxul.html

Counter(arr).most_common(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mtqifnyh.html

[U13] Py：固定长度队列
来源：http://dali.pycfn.com/Article/details/gt2vjekoxak.html

deque(maxlen=10)
来源：http://dali.yueranfly.top/Article/details/gt2qxmviuwf.html

[U14] Py：分组收集到列表
来源：http://dali.cucudq.cn/Article/details/gt2pgujhein.html

defaultdict(list)
来源：http://dali.pycfn.com/Article/details/gt2ftnowkdo.html

[U15] Py：高精度计时
来源：http://dali.guowangkeji.top/Article/details/gt2afqjrqqc.html

t = time.perf_counter()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2smrkfwti.html

[U16] Py：命令行参数解析
来源：http://dali.ybcxt.top/Article/details/gt2triiebtl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ppjwa.cn/Article/details/gt2yksyotha.html

[U17] Py：初始化日志
来源：http://dali.jiagoushi.top/Article/details/gt2dtzebgpu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sbyhwoqf.html

[U18] Py：预编译正则
来源：http://dali.jinqigfzy.top/Article/details/gt2iqvdrkjt.html

pat = re.compile(r"\d+")
来源：http://dali.sxryk.cn/Article/details/gt2conlrrkx.html

[U19] Py：正则替换带回调
来源：http://dali.daria6918.cn/Article/details/gt2iphuwmdi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ydzc1.top/Article/details/gt2vdkfogra.html

[U20] Py：缓存函数结果
来源：http://dali.jqgfzy.top/Article/details/gt2iebpbxqv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.haohaochexian.top/Article/details/gt2lbyuhmsz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhixingplan.top/Article/details/gt2lujurbrn.html

@contextlib.contextmanager
来源：http://dali.hysaishi.cn/Article/details/gt2kdvwxwgo.html

[U22] Py：矩阵转置
来源：http://dali.yonumen.top/Article/details/gt2xupflfty.html

list(zip(*m))
来源：http://dali.bjfxy.top/Article/details/gt2tbeigxik.html

[U23] Py：分块读取大文件
来源：http://dali.yj202588.top/Article/details/gt2ogvcluin.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cheryme.top/Article/details/gt2oxgdwscd.html

[U24] Py：路径操作
来源：http://dali.yj202588.top/Article/details/gt2fbjmwuto.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gt2hpdmqjfb.html

[U25] Py：CSV 按字典读
来源：http://dali.jiagoushi.top/Article/details/gt2mtujlknc.html

csv.DictReader(f)
来源：http://dali.iojbl.cn/Article/details/gt2zpqzzuhf.html

[U26] Py：并发下载
来源：http://dali.hammf.cn/Article/details/gt2tykgrvah.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zycfv.cn/Article/details/gt2vtflhdwd.html

[U27] Py：异步 HTTP
来源：http://dali.c1oappe.top/Article/details/gt2ybvehgdq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yangfankeji.com/Article/details/gt2taqupeje.html

[U28] Py：类型别名
来源：http://dali.hongshengwenyu.top/Article/details/gt2mknwrvmo.html

UserId = int
来源：http://dali.ybcxt.top/Article/details/gt2oaurfqkx.html

[U29] Py：属性校验
来源：http://dali.fengsongda.top/Article/details/gt2itdhxzfh.html

@property 与 @x.setter 配合
来源：http://dali.tanke756.top/Article/details/gt2xgogfbfe.html

[U30] Py：数据类
来源：http://dali.jyoumei.cn/Article/details/gt2xdsurhob.html

@dataclass(slots=True)
来源：http://dali.xuetiantiany.cn/Article/details/gt2olesfbts.html

[U31] Py：单测
来源：http://dali.ivvv.top/Article/details/gt2tuwhaqma.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2rklrrcvx.html

[U32] Py：代码格式化
来源：http://dali.xziqi.cn/Article/details/gt2hbbyrhap.html

ruff format . && ruff check --fix .
来源：http://dali.yj202588.top/Article/details/gt2mlddbeok.html

[U33] Py：打包发布
来源：http://dali.yangfankeji.com/Article/details/gt2wrcyfqdx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hywenlv.cn/Article/details/gt2armihpuj.html

[U34] Py：判断编码
来源：http://dali.wangshuangyany.cn/Article/details/gt2krccwwez.html

chardet.detect(raw)
来源：http://dali.ybcxt.top/Article/details/gt2ffapunmd.html

[U35] Py：发送邮件
来源：http://dali.gogol.net.cn/Article/details/gt2vetaqant.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.fzhhl.top/Article/details/gt2npuwbdky.html

[U36] Py：定时任务
来源：http://dali.andypj.xyz/Article/details/gt2nhbsjfax.html

schedule.every(10).minutes.do(job)
来源：http://dali.gotoacloud.top/Article/details/gt2qwobbyqv.html

[U37] Py：读写 Excel
来源：http://dali.yvedp.cn/Article/details/gt2rwfnjriz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2asvocsgp.html

[U38] Py：获取脚本所在目录
来源：http://dali.hnxiangtu.top/Article/details/gt2rtrnawxs.html

Path(__file__).resolve().parent
来源：http://dali.ydzc1.top/Article/details/gt2cgdpibuv.html

[U39] Py：判断是否在交互环境
来源：http://dali.xuetiantiany.cn/Article/details/gt2bnvgvjgp.html

sys.stdout.isatty()
来源：http://dali.hongshengwenyu.top/Article/details/gt2koriajqw.html

[U40] Py：打印到标准错误
来源：http://dali.shangyingyoupin.top/Article/details/gt2kwdpyfow.html

print("err", file=sys.stderr)
来源：http://dali.vqdsnc.cn/Article/details/gt2kwqmpiig.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hammf.cn/Article/details/gt2ecmzjkfr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhongyouzk.top/Article/details/gt2gdkysqid.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xuanzx.com/Article/details/gt2vqgjgmgp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.sweek.top/Article/details/gt2yfdtmavj.html

[U43] PHP：声明命名空间
来源：http://dali.nwbrower.top/Article/details/gt2dsregyvq.html

namespace App\Http;
来源：http://dali.ppjwa.cn/Article/details/gt2qytznlqp.html

[U44] PHP：开启严格类型
来源：http://dali.dianchejie.cn/Article/details/gt2ulduvdjb.html

declare(strict_types=1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2eaawggsg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ydzc1.top/Article/details/gt2iszhyaug.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gt2iekjjneb.html

[U46] PHP：可空类型
来源：http://dali.zhixingplan.top/Article/details/gt2njamzdng.html

?string $name = null
来源：http://dali.nanxinkj.top/Article/details/gt2nljtihvt.html

[U47] PHP：联合类型
来源：http://dali.cheryme.top/Article/details/gt2tqgwlwsb.html

int|string $id
来源：http://dali.sxryk.cn/Article/details/gt2rrspxicw.html

[U48] PHP：纯枚举
来源：http://dali.ppjwa.cn/Article/details/gt2sqpuhasl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yongpay.top/Article/details/gt2mkdmboan.html

[U49] PHP：只读属性
来源：http://dali.xylfe.cn/Article/details/gt2tfbpcxde.html

public readonly string $name
来源：http://dali.daxiang520.top/Article/details/gt2hqqlrdpq.html

[U50] PHP：构造器属性提升
来源：http://dali.dianchejie.cn/Article/details/gt2hrdvmgsf.html

public function __construct(private int $id) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2giayjcpd.html

[U51] PHP：数组解构
来源：http://dali.guowangkeji.top/Article/details/gt2hzbajozb.html

[$a, $b] = $arr;
来源：http://dali.pengpengdd.cyou/Article/details/gt2gurvswfx.html

[U52] PHP：箭头函数
来源：http://dali.haohaochexian.top/Article/details/gt2aebzlvmx.html

$double = fn($x) => $x * 2;
来源：http://dali.fengsongda.top/Article/details/gt2rxikxqbj.html

[U53] PHP：空合并运算符
来源：http://dali.zdqjudy.top/Article/details/gt2njgkevgu.html

$v = $a ?? $b ?? "default";
来源：http://dali.316326.xyz/Article/details/gt2swhutbsd.html

[U54] PHP：空安全调用
来源：http://dali.xuanzx.com/Article/details/gt2srknwszr.html

$obj?->method()
来源：http://dali.jqgufenzy.top/Article/details/gt2klaibfyi.html

[U55] PHP：match 表达式
来源：http://dali.yuxming.cn/Article/details/gt2uxhrubwh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ehwqpu.com/Article/details/gt2koquuaar.html

[U56] PHP：命名参数
来源：http://dali.shzxlz.cn/Article/details/gt2bunvtjtn.html

f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gt2apisrutb.html

[U57] PHP：字符串插值
来源：http://dali.smart0.xyz/Article/details/gt2blhxpazt.html

"值: {$a}"
来源：http://dali.tian-w.cn/Article/details/gt2jiqpkhzu.html

[U58] PHP：数组三件套
来源：http://dali.yanxiufei.cn/Article/details/gt2yzwgitbs.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhengqikj.top/Article/details/gt2prziscvy.html

[U59] PHP：自定义排序
来源：http://dali.daria6918.cn/Article/details/gt2cnxevqzj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.mhx1999.top/Article/details/gt2vogmemug.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2aujbtwbh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.haohaochexian.top/Article/details/gt2uzmeluql.html

[U61] PHP：正则
来源：http://dali.zycfv.cn/Article/details/gt2lgxkxyqq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.mhx1999.top/Article/details/gt2ktxmkefi.html

[U62] PHP：日期对象
来源：http://dali.dashuyun.cn/Article/details/gt2pkzofodg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.fengsongda.top/Article/details/gt2hcpasemp.html

[U63] PHP：文件读写
来源：http://dali.kuanghao11.cn/Article/details/gt2nmgcnzhw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hnqzz.top/Article/details/gt2pyiluubo.html

[U64] PHP：目录遍历
来源：http://dali.daria6918.cn/Article/details/gt2txlryyig.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.snrcjt.cn/Article/details/gt2efgvaday.html

[U65] PHP：会话
来源：http://dali.tanke756.top/Article/details/gt2ngscrdrl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ivvv.top/Article/details/gt2mqbmncau.html

[U66] PHP：设置 Cookie
来源：http://dali.nwbrower.top/Article/details/gt2akkinava.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cqqwz.cn/Article/details/gt2hbfknkbv.html


<!-- 参考信息 -->