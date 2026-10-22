代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.cucudq.cn/Article/details/gt2ojflzsun.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xmscsisr.html

[S40] C++：查找元素
来源：http://dali.birdmap.top/Article/details/gt2uxuqevyc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dianchejie.cn/Article/details/gt2syhzupry.html

[S41] C++：类与构造函数
来源：http://dali.fengsongda.top/Article/details/gt2gvqpazzq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.bjfxy.top/Article/details/gt2httthvmh.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gt2sjbhrosg.html

class B : public Base { public: void f() override {} };
来源：http://dali.sweek.top/Article/details/gt2hlbhphui.html

[S43] C++：智能指针
来源：http://dali.hywenlv.cn/Article/details/gt2bjcwdtqa.html

auto p = std::make_unique<int>(5);
来源：http://dali.cucudq.cn/Article/details/gt2gkpfmfra.html

[S44] C++：引用传参
来源：http://dali.birdmap.top/Article/details/gt2skzzhjmx.html

void inc(int &x) { ++x; }
来源：http://dali.dashuyun.cn/Article/details/gt2shqldpec.html

[S45] C++：lambda
来源：http://dali.yvedp.cn/Article/details/gt2gtdfloml.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gzhubu.top/Article/details/gt2eygenyww.html

[S46] C++：函数模板
来源：http://dali.gzhubu.top/Article/details/gt2rgcpeojj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yueranfly.top/Article/details/gt2vrgphpzj.html

[S47] C++：结构化绑定遍历
来源：http://dali.cqqwz.cn/Article/details/gt2wbdqqxde.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cheryme.top/Article/details/gt2dtjdniul.html

[S48] C++：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cstmdijb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pengpengdd.cyou/Article/details/gt2efypjrkm.html

while (std::getline(in, line)) { }
来源：http://dali.316326.xyz/Article/details/gt2oatyoxdg.html

[S49] C++：写文件
来源：http://dali.zhoulong.xyz/Article/details/gt2dgmzafbv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guannengcc.top/Article/details/gt2kefurysc.html

[S50] C++：格式化数字
来源：http://dali.hnxiangtu.top/Article/details/gt2ppyqjsma.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gt2jhvtdzta.html

[S51] C++：显式类型转换
来源：http://dali.yvedp.cn/Article/details/gt2ujtkyzpg.html

static_cast<double>(a) / b
来源：http://dali.yongpay.top/Article/details/gt2sstpvigy.html

[S52] C++：const 与 noexcept
来源：http://dali.havefunace.top/Article/details/gt2hmnsrdhn.html

int size() const noexcept { return n_; }
来源：http://dali.mhx1999.top/Article/details/gt2iebfwrko.html

[S53] C++：移动语义
来源：http://dali.kuanghao11.cn/Article/details/gt2evwnjdjo.html

std::vector<int> w = std::move(v);
来源：http://dali.svipenyu.cn/Article/details/gt2zivmprfm.html

[S54] C++：异常处理
来源：http://dali.yonumen.top/Article/details/gt2yamduklg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.bjfxy.top/Article/details/gt2xgmsfkdm.html

[S55] C++：结构化绑定
来源：http://dali.xinyue.icu/Article/details/gt2vhhtjain.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aibaodan.cn/Article/details/gt2liworxgh.html

[S56] C++：optional
来源：http://dali.sufxvd.cn/Article/details/gt2timtlgwj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gt2errvcdhd.html

[S57] C++：编译期常量
来源：http://dali.jqgfzy.top/Article/details/gt2pekeozlq.html

constexpr int N = 10;
来源：http://dali.dashuyun.cn/Article/details/gt2uexmlqpg.html

[S58] C++：命名空间
来源：http://dali.c1oappe.top/Article/details/gt2fetbbdjo.html

namespace ns { int f() { return 1; } }
来源：http://dali.tianlin.xyz/Article/details/gt2lutxuaab.html

[S59] C++：静态断言
来源：http://dali.jlsjyb.cn/Article/details/gt2bpbkxfco.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.aibaodan.cn/Article/details/gt2huyyieim.html

[S60] C++：遍历并删除元素
来源：http://dali.kuanghao11.cn/Article/details/gt2nplyaxxw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.svipenyu.cn/Article/details/gt2xfuptuuj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2eoygkyti.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yanxiufei.cn/Article/details/gt2gbhnpain.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2cgbwvtem.html

[T01] Kotlin：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2sanvhicc.html

println("Hello")
来源：http://dali.tianlin.xyz/Article/details/gt2qgcolnzo.html

[T02] Kotlin：变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xwdaorxp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.daxiang520.top/Article/details/gt2hsaswevv.html

[T03] Kotlin：字符串模板
来源：http://dali.sufxvd.cn/Article/details/gt2dtdvtbnn.html

"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gt2hvemhnps.html

[T04] Kotlin：空安全
来源：http://dali.aizwys.cn/Article/details/gt2jfrzzvmd.html

val n: String? = null;  n?.length
来源：http://dali.guannengcc.top/Article/details/gt2bzysvgid.html

[T05] Kotlin：when 表达式
来源：http://dali.sxryk.cn/Article/details/gt2dfctabeu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gotoacloud.top/Article/details/gt2qdxmqbbg.html

[T06] Kotlin：集合映射
来源：http://dali.mhx1999.top/Article/details/gt2kuaylwsk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2lyrrpiij.html

[T07] Kotlin：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2nyxwvhen.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hammf.cn/Article/details/gt2ndvsqyuj.html

[T08] Kotlin：数据类
来源：http://dali.yj202588.top/Article/details/gt2nbypmupq.html

data class User(val name: String, val age: Int)
来源：http://dali.xziqi.cn/Article/details/gt2tapvabnh.html

[T09] Kotlin：扩展函数
来源：http://dali.wangdashe.top/Article/details/gt2gbyiekat.html

fun String.exclaim() = this + "!"
来源：http://dali.tianlin.xyz/Article/details/gt2ubrrqakm.html

[T10] Kotlin：默认参数
来源：http://dali.tianlin.xyz/Article/details/gt2qrypmhpl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnqzz.top/Article/details/gt2ennmzxvs.html

[T11] Kotlin：协程
来源：http://dali.redwolf501.top/Article/details/gt2khqbsaai.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ybcxt.top/Article/details/gt2nnkvlqnj.html

[T12] Kotlin：解构声明
来源：http://dali.guannengcc.top/Article/details/gt2zjlrrhwd.html

val (a, b) = Pair(1, 2)
来源：http://dali.cashguo.top/Article/details/gt2ykvgegte.html

[T13] Kotlin：只读 Map
来源：http://dali.yueranfly.top/Article/details/gt2ddpcelbw.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sinxoawm.html

[T14] Kotlin：循环
来源：http://dali.havefunace.top/Article/details/gt2hjjgvvsv.html

for (i in 1..10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gt2fjdwyuqd.html

[T15] Kotlin：接口
来源：http://dali.svipenyu.cn/Article/details/gt2ewxyohsm.html

interface Shape { fun area(): Double }
来源：http://dali.snrcjt.cn/Article/details/gt2oowiorhi.html

[T16] Swift：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2bgcbohzk.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gt2zbovbzdj.html

[T17] Swift：变量与常量
来源：http://dali.aibaodan.cn/Article/details/gt2zhkypfqm.html

var a = 1;  let b = 2
来源：http://dali.yuxming.cn/Article/details/gt2qmejmrdm.html

[T18] Swift：字符串插值
来源：http://dali.yueranfly.top/Article/details/gt2vqversmv.html

"值: \(b)"
来源：http://dali.daria6918.cn/Article/details/gt2tcrvuljf.html

[T19] Swift：可选绑定
来源：http://dali.chenlongwang.top/Article/details/gt2vngyfslt.html

if let n = opt { print(n) }
来源：http://dali.xuanzx.com/Article/details/gt2kpcptyay.html

[T20] Swift：数组操作
来源：http://dali.andypj.xyz/Article/details/gt2mxaxhkql.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.bjfxy.top/Article/details/gt2iblnszkn.html

[T21] Swift：遍历
来源：http://dali.gogol.net.cn/Article/details/gt2shpmgqjo.html

for x in a { print(x) }
来源：http://dali.snrcjt.cn/Article/details/gt2fwyeqtny.html

[T22] Swift：字典
来源：http://dali.zhengqikj.top/Article/details/gt2qisfkbyf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jlsjyb.cn/Article/details/gt2sgyqokaz.html

[T23] Swift：函数
来源：http://dali.yj20258.top/Article/details/gt2xjgsitlc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nanxuanxn.top/Article/details/gt2gmsymhcu.html

[T24] Swift：闭包
来源：http://dali.yanxiufei.cn/Article/details/gt2zxlrvvhi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ydzc1.top/Article/details/gt2ekixcuow.html

[T25] Swift：结构体
来源：http://dali.shzxlz.cn/Article/details/gt2dpcjyxpn.html

struct P { var x: Int }
来源：http://dali.yangfankeji.com/Article/details/gt2oyoovfax.html

[T26] Swift：类与重写
来源：http://dali.xinyue.icu/Article/details/gt2ukbslpmw.html

class A: Base { override func f() {} }
来源：http://dali.zdqjudy.top/Article/details/gt2qiiwnnrd.html

[T27] Swift：错误处理
来源：http://dali.jinqigufen.top/Article/details/gt2jytkzwjz.html

do { try f() } catch { print(error) }
来源：http://dali.yuxming.cn/Article/details/gt2wbdnzkyw.html

[T28] Swift：枚举
来源：http://dali.sweek.top/Article/details/gt2cyidqxsu.html

enum Color { case red, green }
来源：http://dali.tanke756.top/Article/details/gt2ksykhvpb.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxinkj.top/Article/details/gt2wkeohqat.html

guard let x = opt else { return }
来源：http://dali.hnxiangtu.top/Article/details/gt2hxlqeoqo.html

[T30] Swift：协议
来源：http://dali.316326.xyz/Article/details/gt2ogdvsarm.html

protocol Shape { func area() -> Double }
来源：http://dali.chenzaomai.com/Article/details/gt2lrxtilfp.html

[T31] Lua：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2dqzoambj.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ubfzjmtc.html

[T32] Lua：局部变量
来源：http://dali.hnxiangtu.top/Article/details/gt2qxtvygsu.html

local a = 1
来源：http://dali.andypj.xyz/Article/details/gt2vlpsksuw.html

[T33] Lua：表（数组）
来源：http://dali.ppjwa.cn/Article/details/gt2zrndzzdc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ydzc1.top/Article/details/gt2hbqdimld.html

[T34] Lua：遍历表
来源：http://dali.guowangkeji.top/Article/details/gt2ydcucdgv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pengpengdd.cyou/Article/details/gt2qmrrvpwq.html

[T35] Lua：字典表
来源：http://dali.jqgufenzy.top/Article/details/gt2jmerliol.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangdashe.top/Article/details/gt2qqisprmy.html

[T36] Lua：函数
来源：http://dali.jqgfzy.top/Article/details/gt2kiaixhtz.html

function add(a, b) return a + b end
来源：http://dali.xinyue.icu/Article/details/gt2zmbdzfst.html

[T37] Lua：字符串拼接
来源：http://dali.gzhubu.top/Article/details/gt2wosmwgsd.html

"a" .. "b"
来源：http://dali.svipenyu.cn/Article/details/gt2acszwzoq.html

[T38] Lua：条件
来源：http://dali.feifeiyinyue.top/Article/details/gt2tpswdzxh.html

if x > 0 then print("正") end
来源：http://dali.zhoulong.xyz/Article/details/gt2gyiljfke.html

[T39] Lua：模式匹配
来源：http://dali.birdmap.top/Article/details/gt2tibfzbeb.html

string.find(s, "%d+")
来源：http://dali.bjfxy.top/Article/details/gt2fesijwll.html

[T40] Lua：元表
来源：http://dali.hnqzz.top/Article/details/gt2uoptncfc.html

setmetatable({}, { __index = base })
来源：http://dali.havefunace.top/Article/details/gt2wtrskjus.html

[T41] Perl：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2hkfhambg.html

print "Hello\n";
来源：http://dali.zhongyouzk.top/Article/details/gt2mofhmyrr.html

[T42] Perl：变量类型
来源：http://dali.hysaishi.cn/Article/details/gt2nrpoekiq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenzaomai.com/Article/details/gt2cjnghdex.html

[T43] Perl：字符串插值
来源：http://dali.316326.xyz/Article/details/gt2jaseyool.html

"值: $a"
来源：http://dali.mhx1999.top/Article/details/gt2vtwxcdod.html

[T44] Perl：条件
来源：http://dali.svipenyu.cn/Article/details/gt2bexdyipe.html

if ($a > 0) { print "正"; }
来源：http://dali.birdmap.top/Article/details/gt2owkvgipf.html

[T45] Perl：数组遍历
来源：http://dali.shzxlz.cn/Article/details/gt2wrnhcfpq.html

for my $x (@arr) { print $x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2melrgdcz.html

[T46] Perl：哈希操作
来源：http://dali.yuxming.cn/Article/details/gt2uxcolgxl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2egmkkawr.html

[T47] Perl：正则捕获
来源：http://dali.svipenyu.cn/Article/details/gt2khzlqttv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jlsjyb.cn/Article/details/gt2vsutavfp.html

[T48] Perl：正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2ruyournw.html

$s =~ s/old/new/g;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kfvqjvja.html

[T49] Perl：函数
来源：http://dali.hysaishi.cn/Article/details/gt2jcafcaog.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gt2kmqgdpaq.html

[T50] Perl：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gt2vsfcyads.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gaohongyu789.top/Article/details/gt2eucezniw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gotoacloud.top/Article/details/gt2ozjtejsh.html

[T51] Scala：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2cefzdgji.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gt2jwqahwgr.html

[T52] Scala：变量
来源：http://dali.yj20258.top/Article/details/gt2heanonpx.html

val a = 1;  var b = 2
来源：http://dali.yj20258.top/Article/details/gt2yklcxldv.html

[T53] Scala：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gt2xwgjqwel.html

s"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdyxgmve.html

[T54] Scala：集合映射
来源：http://dali.sysykeji.top/Article/details/gt2uzwdedcz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cqqwz.cn/Article/details/gt2fmgbqwch.html

[T55] Scala：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pgmftomo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.andypj.xyz/Article/details/gt2gfosmkcf.html

[T56] Scala：样例类
来源：http://dali.feifeiyinyue.top/Article/details/gt2qgtuchmp.html

case class User(name: String, age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hqtmpbel.html

[T57] Scala：模式匹配
来源：http://dali.snrcjt.cn/Article/details/gt2iuvunsnh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zdqjudy.top/Article/details/gt2tuxwkcie.html

[T58] Scala：函数定义
来源：http://dali.ivvv.top/Article/details/gt2saukceoz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ppjwa.cn/Article/details/gt2twxzbdau.html

[T59] Scala：循环
来源：http://dali.zycfv.cn/Article/details/gt2xglmmbfi.html

for (i <- 1 to 10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gt2opyezqzh.html

[T60] Scala：折叠
来源：http://dali.havefunace.top/Article/details/gt2xpnigidb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ybcxt.top/Article/details/gt2nlwikdky.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2fzpbhzqh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnqzz.top/Article/details/gt2bxkgpwyk.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2jsjpnoaa.html

[U01] Py：创建虚拟环境
来源：http://dali.chenzaomai.com/Article/details/gt2xrhxheca.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jiagoushi.top/Article/details/gt2qmanneaq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinqigufen.top/Article/details/gt2jphlehhc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yueranfly.top/Article/details/gt2coejmarl.html

[U03] Py：加载 .env 配置
来源：http://dali.c1oappe.top/Article/details/gt2gccgkdbr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ydzc1.top/Article/details/gt2zqjosrpo.html

[U04] Py：变量调试打印
来源：http://dali.jqgufenzy.top/Article/details/gt2eampzvgn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ybcxt.top/Article/details/gt2suescpvr.html

[U05] Py：列表去重且保序
来源：http://dali.wangdashe.top/Article/details/gt2nkcfyaer.html

list(dict.fromkeys(arr))
来源：http://dali.c1oappe.top/Article/details/gt2telmqkse.html

[U06] Py：合并两个字典
来源：http://dali.hysaishi.cn/Article/details/gt2yjymssbr.html

{**a, **b}
来源：http://dali.yvedp.cn/Article/details/gt2jcxpmxko.html

[U07] Py：反转字典键值
来源：http://dali.pycfn.com/Article/details/gt2jwbcdqje.html

{v: k for k, v in d.items()}
来源：http://dali.zdqjudy.top/Article/details/gt2efbnxnvn.html

[U08] Py：展平二维列表
来源：http://dali.jinqigfzy.top/Article/details/gt2zeaeqnph.html

[y for x in nested for y in x]
来源：http://dali.yueranfly.top/Article/details/gt2gcmlovyy.html

[U09] Py：字典取最大值的键
来源：http://dali.pycfn.com/Article/details/gt2tuijtbcq.html

max(d, key=d.get)
来源：http://dali.gogol.net.cn/Article/details/gt2yycnwevv.html

[U10] Py：按值排序字典
来源：http://dali.ydzc1.top/Article/details/gt2nvdgtsfu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcfqcms.html

[U11] Py：生成器表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwxjnqxm.html

(x * 2 for x in arr)
来源：http://dali.mhx1999.top/Article/details/gt2vwzruqle.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gogol.net.cn/Article/details/gt2aqggcgao.html

Counter(arr).most_common(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gmjsnaad.html

[U13] Py：固定长度队列
来源：http://dali.yj202588.top/Article/details/gt2ikdxsizh.html

deque(maxlen=10)
来源：http://dali.jianghu66.top/Article/details/gt2sblzkbnd.html

[U14] Py：分组收集到列表
来源：http://dali.feifeiyinyue.top/Article/details/gt2mgqmnlqe.html

defaultdict(list)
来源：http://dali.gaohongyu789.top/Article/details/gt2bbiddbxt.html

[U15] Py：高精度计时
来源：http://dali.yongpay.top/Article/details/gt2zvcwzyjn.html

t = time.perf_counter()
来源：http://dali.sysykeji.top/Article/details/gt2agcxxwou.html

[U16] Py：命令行参数解析
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmbdqddp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cucudq.cn/Article/details/gt2gqopjcoz.html

[U17] Py：初始化日志
来源：http://dali.feifeiyinyue.top/Article/details/gt2vxncvbng.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2utotvhkw.html

[U18] Py：预编译正则
来源：http://dali.gotoacloud.top/Article/details/gt2moikeyez.html

pat = re.compile(r"\d+")
来源：http://dali.ppjwa.cn/Article/details/gt2akmbkgma.html

[U19] Py：正则替换带回调
来源：http://dali.jqgufenzy.top/Article/details/gt2iagzrsic.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhongyouzk.top/Article/details/gt2pdmfeikf.html

[U20] Py：缓存函数结果
来源：http://dali.jinghuilouyu.cn/Article/details/gt2baysgcld.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ehwqpu.com/Article/details/gt2ngejuhle.html

[U21] Py：自定义上下文管理器
来源：http://dali.feifeiyinyue.top/Article/details/gt2kgwapxly.html

@contextlib.contextmanager
来源：http://dali.gotoacloud.top/Article/details/gt2ftsugimq.html

[U22] Py：矩阵转置
来源：http://dali.dianchejie.cn/Article/details/gt2xatkckug.html

list(zip(*m))
来源：http://dali.gotoacloud.top/Article/details/gt2kxmeynlm.html

[U23] Py：分块读取大文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rotrefod.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jyoumei.cn/Article/details/gt2gzjqupid.html

[U24] Py：路径操作
来源：http://dali.sweek.top/Article/details/gt2vnuihkwx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pyaoskgo.html

[U25] Py：CSV 按字典读
来源：http://dali.hywenlv.cn/Article/details/gt2hrnzrnwl.html

csv.DictReader(f)
来源：http://dali.pycfn.com/Article/details/gt2zzpcbyza.html

[U26] Py：并发下载
来源：http://dali.jqgufenzy.top/Article/details/gt2oynsofhx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.daxiang520.top/Article/details/gt2kvzgrxyr.html

[U27] Py：异步 HTTP
来源：http://dali.yongpay.top/Article/details/gt2siddwone.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hongshengwenyu.top/Article/details/gt2fnbpgbjq.html

[U28] Py：类型别名
来源：http://dali.c1oappe.top/Article/details/gt2nptnolxm.html

UserId = int
来源：http://dali.316326.xyz/Article/details/gt2hkfetmah.html

[U29] Py：属性校验
来源：http://dali.hfpthk.cn/Article/details/gt2gwitngyd.html

@property 与 @x.setter 配合
来源：http://dali.sxryk.cn/Article/details/gt2mccajyda.html

[U30] Py：数据类
来源：http://dali.guannengcc.top/Article/details/gt2nbbkxdzk.html

@dataclass(slots=True)
来源：http://dali.zycfv.cn/Article/details/gt2xbggphzl.html

[U31] Py：单测
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rqrvubcx.html

python -m pytest -q
来源：http://dali.chenjidiqi.icu/Article/details/gt2oinfokcm.html

[U32] Py：代码格式化
来源：http://dali.hywenlv.cn/Article/details/gt2qqknimcp.html

ruff format . && ruff check --fix .
来源：http://dali.jiagoushi.top/Article/details/gt2kpezbbxt.html

[U33] Py：打包发布
来源：http://dali.chenlongwang.top/Article/details/gt2sggpdwkh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shzxlz.cn/Article/details/gt2krkolzsk.html

[U34] Py：判断编码
来源：http://dali.iojbl.cn/Article/details/gt2bsxqaoyv.html

chardet.detect(raw)
来源：http://dali.nanxinkj.top/Article/details/gt2tngjodod.html

[U35] Py：发送邮件
来源：http://dali.chenlongwang.top/Article/details/gt2mziqbapk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwjjnbk.html

[U36] Py：定时任务
来源：http://dali.zhengqikj.top/Article/details/gt2itjyfmoy.html

schedule.every(10).minutes.do(job)
来源：http://dali.tianlin.xyz/Article/details/gt2cjiwxkwu.html

[U37] Py：读写 Excel
来源：http://dali.zhongyouzk.top/Article/details/gt2tmcrvknh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gzhubu.top/Article/details/gt2euvlfrts.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj202588.top/Article/details/gt2vkpwpyxm.html

Path(__file__).resolve().parent
来源：http://dali.gzhubu.top/Article/details/gt2ywlrlgaz.html

[U39] Py：判断是否在交互环境
来源：http://dali.sxryk.cn/Article/details/gt2vnrltmlq.html

sys.stdout.isatty()
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfzahgpm.html

[U40] Py：打印到标准错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tfxllmfw.html

print("err", file=sys.stderr)
来源：http://dali.hammf.cn/Article/details/gt2hgeiilwn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2efdnribw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jqgfzy.top/Article/details/gt2fmetnznl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jiagoushi.top/Article/details/gt2ltjzzmzd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhengqikj.top/Article/details/gt2dcqxpdri.html

[U43] PHP：声明命名空间
来源：http://dali.meibo888.top/Article/details/gt2dfgljpnc.html

namespace App\Http;
来源：http://dali.gaohongyu789.top/Article/details/gt2bajvexoz.html

[U44] PHP：开启严格类型
来源：http://dali.hnxiangtu.top/Article/details/gt2ufmdarnl.html

declare(strict_types=1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2obzaogky.html

[U45] PHP：类型声明与返回类型
来源：http://dali.daxiang520.top/Article/details/gt2sqpvwuoz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gt2ttspleqr.html

[U46] PHP：可空类型
来源：http://dali.gzhubu.top/Article/details/gt2mhyflaaf.html

?string $name = null
来源：http://dali.quarkkingdee.top/Article/details/gt2uuvmcisd.html

[U47] PHP：联合类型
来源：http://dali.birdmap.top/Article/details/gt2jyhlkoxd.html

int|string $id
来源：http://dali.jinqigfzy.top/Article/details/gt2imavjezi.html

[U48] PHP：纯枚举
来源：http://dali.mhx1999.top/Article/details/gt2qgzeynnr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xuanzx.com/Article/details/gt2mzrmlkvw.html

[U49] PHP：只读属性
来源：http://dali.jqgufenzy.top/Article/details/gt2zvndrnir.html

public readonly string $name
来源：http://dali.sysykeji.top/Article/details/gt2gilzlcld.html

[U50] PHP：构造器属性提升
来源：http://dali.jinqigfzy.top/Article/details/gt2keojajix.html

public function __construct(private int $id) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2swrfjznd.html

[U51] PHP：数组解构
来源：http://dali.yuxming.cn/Article/details/gt2bhyijeqo.html

[$a, $b] = $arr;
来源：http://dali.hfpthk.cn/Article/details/gt2gdafgxns.html

[U52] PHP：箭头函数
来源：http://dali.yj20258888.top/Article/details/gt2iplqapjk.html

$double = fn($x) => $x * 2;
来源：http://dali.mhx1999.top/Article/details/gt2fyzukqqn.html

[U53] PHP：空合并运算符
来源：http://dali.daria6918.cn/Article/details/gt2etpitdxh.html

$v = $a ?? $b ?? "default";
来源：http://dali.xuetiantiany.cn/Article/details/gt2hutzxlno.html

[U54] PHP：空安全调用
来源：http://dali.dianchejie.cn/Article/details/gt2aucxbijz.html

$obj?->method()
来源：http://dali.zhoulong.xyz/Article/details/gt2vxtigbvx.html

[U55] PHP：match 表达式
来源：http://dali.daxiang520.top/Article/details/gt2xxcnrtqu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cucudq.cn/Article/details/gt2zwpgfnbp.html

[U56] PHP：命名参数
来源：http://dali.nanxinkj.top/Article/details/gt2zqachxmd.html

f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gt2kiizdwcg.html

[U57] PHP：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gt2mmscbogo.html

"值: {$a}"
来源：http://dali.mhx1999.top/Article/details/gt2egebpems.html

[U58] PHP：数组三件套
来源：http://dali.haohaochexian.top/Article/details/gt2bphkwdsg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.chenlongwang.top/Article/details/gt2gnigiqkb.html

[U59] PHP：自定义排序
来源：http://dali.yj20258.top/Article/details/gt2alzynpby.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2avflcbbi.html

[U60] PHP：JSON 编解码
来源：http://dali.nanxuanxn.top/Article/details/gt2mopsihyy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hysaishi.cn/Article/details/gt2nhnjkqkw.html

[U61] PHP：正则
来源：http://dali.ehwqpu.com/Article/details/gt2ojhxirsw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2rpcxbhcj.html

[U62] PHP：日期对象
来源：http://dali.316326.xyz/Article/details/gt2fdrijhnm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tanke756.top/Article/details/gt2ipdyqxls.html

[U63] PHP：文件读写
来源：http://dali.hnxiangtu.top/Article/details/gt2ouaufvcb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.havefunace.top/Article/details/gt2nmruvyvw.html

[U64] PHP：目录遍历
来源：http://dali.snrcjt.cn/Article/details/gt2vzniahyv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.dianchejie.cn/Article/details/gt2ruwzgoah.html


<!-- 参考信息 -->