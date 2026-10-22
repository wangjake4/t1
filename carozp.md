代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.fzhhl.top/Article/details/gt2jxmuyigf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jyoumei.cn/Article/details/gt2ustwlmao.html

[S48] C++：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gt2yasxsfyo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenjidiqi.icu/Article/details/gt2yzgbqvvt.html

while (std::getline(in, line)) { }
来源：http://dali.guowangkeji.top/Article/details/gt2qcskejlg.html

[S49] C++：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2rymvykkt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangshuangyany.cn/Article/details/gt2cfvwhtgx.html

[S50] C++：格式化数字
来源：http://dali.9152youxi.cn/Article/details/gt2awwxqrhk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wilzyeyj.html

[S51] C++：显式类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jwkoghyo.html

static_cast<double>(a) / b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qihfretw.html

[S52] C++：const 与 noexcept
来源：http://dali.gaohongyu789.top/Article/details/gt2dlsbwjvn.html

int size() const noexcept { return n_; }
来源：http://dali.mhx1999.top/Article/details/gt2hidwugig.html

[S53] C++：移动语义
来源：http://dali.yanxiufei.cn/Article/details/gt2arwiuavr.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258.top/Article/details/gt2ceaxgmmu.html

[S54] C++：异常处理
来源：http://dali.gotoacloud.top/Article/details/gt2dpgbqasg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.andypj.xyz/Article/details/gt2ypffdxma.html

[S55] C++：结构化绑定
来源：http://dali.ehwqpu.com/Article/details/gt2vxaspwaw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xinyue.icu/Article/details/gt2jieidsev.html

[S56] C++：optional
来源：http://dali.cashguo.top/Article/details/gt2kcqmynfj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.havefunace.top/Article/details/gt2cmoggfmo.html

[S57] C++：编译期常量
来源：http://dali.sxryk.cn/Article/details/gt2wllakuvq.html

constexpr int N = 10;
来源：http://dali.cqqwz.cn/Article/details/gt2yblhecxo.html

[S58] C++：命名空间
来源：http://dali.sweek.top/Article/details/gt2atgspcak.html

namespace ns { int f() { return 1; } }
来源：http://dali.shzxlz.cn/Article/details/gt2cpsaklht.html

[S59] C++：静态断言
来源：http://dali.yuanzhike.top/Article/details/gt2hsyfeirm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dashuyun.cn/Article/details/gt2jzdnqmdg.html

[S60] C++：遍历并删除元素
来源：http://dali.yvedp.cn/Article/details/gt2etasamne.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.bjfxy.top/Article/details/gt2trostxlh.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ftikhguz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ybcxt.top/Article/details/gt2kvweaffk.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2alfwefcm.html

[T01] Kotlin：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ebbothar.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gt2zdqmhrij.html

[T02] Kotlin：变量
来源：http://dali.mhx1999.top/Article/details/gt2exianzda.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigufen.top/Article/details/gt2htkjracx.html

[T03] Kotlin：字符串模板
来源：http://dali.yvedp.cn/Article/details/gt2exfwvicc.html

"值: $b"
来源：http://dali.daria6918.cn/Article/details/gt2exidthfj.html

[T04] Kotlin：空安全
来源：http://dali.cheryme.top/Article/details/gt2qiiqymyx.html

val n: String? = null;  n?.length
来源：http://dali.meibo888.top/Article/details/gt2zsfixtxz.html

[T05] Kotlin：when 表达式
来源：http://dali.redwolf501.top/Article/details/gt2lpsslyhk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgufenzy.top/Article/details/gt2feioygfs.html

[T06] Kotlin：集合映射
来源：http://dali.guowangkeji.top/Article/details/gt2ujrsuepl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2fsoylekg.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pvweycdk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cashguo.top/Article/details/gt2ocvaxphz.html

[T08] Kotlin：数据类
来源：http://dali.ehwqpu.com/Article/details/gt2xpqnnqgh.html

data class User(val name: String, val age: Int)
来源：http://dali.ydzc1.top/Article/details/gt2wijagavf.html

[T09] Kotlin：扩展函数
来源：http://dali.shzxlz.cn/Article/details/gt2helwhnzt.html

fun String.exclaim() = this + "!"
来源：http://dali.gogol.net.cn/Article/details/gt2yhikvooa.html

[T10] Kotlin：默认参数
来源：http://dali.ydzc1.top/Article/details/gt2auduuqql.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jyoumei.cn/Article/details/gt2bjjiuwkc.html

[T11] Kotlin：协程
来源：http://dali.yanxiufei.cn/Article/details/gt2kkazacpw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guannengcc.top/Article/details/gt2witvklyi.html

[T12] Kotlin：解构声明
来源：http://dali.daria6918.cn/Article/details/gt2jirnmqee.html

val (a, b) = Pair(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2lnaalmga.html

[T13] Kotlin：只读 Map
来源：http://dali.snrcjt.cn/Article/details/gt2dxervziy.html

val m = mapOf("a" to 1)
来源：http://dali.ppjwa.cn/Article/details/gt2mgfylxcv.html

[T14] Kotlin：循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2mrwrwdyx.html

for (i in 1..10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gt2lwanwiiv.html

[T15] Kotlin：接口
来源：http://dali.iojbl.cn/Article/details/gt2bpofjgpi.html

interface Shape { fun area(): Double }
来源：http://dali.bjfxy.top/Article/details/gt2ellpntqc.html

[T16] Swift：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2tmygygiw.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gt2iwcnyfiv.html

[T17] Swift：变量与常量
来源：http://dali.nanxuanxn.top/Article/details/gt2sayyzjpl.html

var a = 1;  let b = 2
来源：http://dali.jyoumei.cn/Article/details/gt2qgsdxsjp.html

[T18] Swift：字符串插值
来源：http://dali.gzhubu.top/Article/details/gt2lyomirlc.html

"值: \(b)"
来源：http://dali.xinyue.icu/Article/details/gt2bkzemksj.html

[T19] Swift：可选绑定
来源：http://dali.iojbl.cn/Article/details/gt2xqxukdbl.html

if let n = opt { print(n) }
来源：http://dali.fzhhl.top/Article/details/gt2fiuuwubs.html

[T20] Swift：数组操作
来源：http://dali.daxiang520.top/Article/details/gt2jfhstsov.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sweek.top/Article/details/gt2tnichsoh.html

[T21] Swift：遍历
来源：http://dali.jyoumei.cn/Article/details/gt2hmvdnjkg.html

for x in a { print(x) }
来源：http://dali.sweek.top/Article/details/gt2jrgekmzf.html

[T22] Swift：字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ohavdtei.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2becwwabs.html

[T23] Swift：函数
来源：http://dali.yj202588.top/Article/details/gt2lnclqkkp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.birdmap.top/Article/details/gt2zlshafan.html

[T24] Swift：闭包
来源：http://dali.cashguo.top/Article/details/gt2ufzqhjvt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gt2hcuovkqc.html

[T25] Swift：结构体
来源：http://dali.shzxlz.cn/Article/details/gt2gcrvczbc.html

struct P { var x: Int }
来源：http://dali.birdmap.top/Article/details/gt2xzhkucey.html

[T26] Swift：类与重写
来源：http://dali.yj202588.top/Article/details/gt2tnvrxmwd.html

class A: Base { override func f() {} }
来源：http://dali.yonumen.top/Article/details/gt2aeuegavl.html

[T27] Swift：错误处理
来源：http://dali.guowangkeji.top/Article/details/gt2unaxnzqp.html

do { try f() } catch { print(error) }
来源：http://dali.ehwqpu.com/Article/details/gt2ptrugqpo.html

[T28] Swift：枚举
来源：http://dali.tianlin.xyz/Article/details/gt2jlztzvkk.html

enum Color { case red, green }
来源：http://dali.jlsjyb.cn/Article/details/gt2wnmrvwlz.html

[T29] Swift：guard 提前返回
来源：http://dali.sweek.top/Article/details/gt2ouyqwmde.html

guard let x = opt else { return }
来源：http://dali.chenlongwang.top/Article/details/gt2ipxdntsi.html

[T30] Swift：协议
来源：http://dali.chenlongwang.top/Article/details/gt2cvvxuyqd.html

protocol Shape { func area() -> Double }
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxawoqjm.html

[T31] Lua：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2zgrfqawp.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gt2yibxhwtp.html

[T32] Lua：局部变量
来源：http://dali.xinyue.icu/Article/details/gt2hexkcvku.html

local a = 1
来源：http://dali.dashuyun.cn/Article/details/gt2cmsnhchs.html

[T33] Lua：表（数组）
来源：http://dali.snrcjt.cn/Article/details/gt2cwprtzbd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuoctid.html

[T34] Lua：遍历表
来源：http://dali.hysaishi.cn/Article/details/gt2opasoaqo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pengpengdd.cyou/Article/details/gt2yydiuxbi.html

[T35] Lua：字典表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwexcchp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.andypj.xyz/Article/details/gt2tqmzkddq.html

[T36] Lua：函数
来源：http://dali.nanxinkj.top/Article/details/gt2zttjfara.html

function add(a, b) return a + b end
来源：http://dali.xinyue.icu/Article/details/gt2qiabfygj.html

[T37] Lua：字符串拼接
来源：http://dali.cucudq.cn/Article/details/gt2owqaghwk.html

"a" .. "b"
来源：http://dali.daria6918.cn/Article/details/gt2hkllcpul.html

[T38] Lua：条件
来源：http://dali.feifeiyinyue.top/Article/details/gt2dpzpogln.html

if x > 0 then print("正") end
来源：http://dali.gotoacloud.top/Article/details/gt2ilvmhteg.html

[T39] Lua：模式匹配
来源：http://dali.sweek.top/Article/details/gt2rcxbixmj.html

string.find(s, "%d+")
来源：http://dali.gzhubu.top/Article/details/gt2xnrasfwa.html

[T40] Lua：元表
来源：http://dali.xuetiantiany.cn/Article/details/gt2qbklhken.html

setmetatable({}, { __index = base })
来源：http://dali.guannengcc.top/Article/details/gt2fhtnfuwh.html

[T41] Perl：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2pmvgtcmu.html

print "Hello\n";
来源：http://dali.xylfe.cn/Article/details/gt2aqdgzsxb.html

[T42] Perl：变量类型
来源：http://dali.ppjwa.cn/Article/details/gt2ilddluoj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gaohongyu789.top/Article/details/gt2tpvwzhqb.html

[T43] Perl：字符串插值
来源：http://dali.andypj.xyz/Article/details/gt2oqmxgukk.html

"值: $a"
来源：http://dali.jyoumei.cn/Article/details/gt2bgovianh.html

[T44] Perl：条件
来源：http://dali.pycfn.com/Article/details/gt2ixjqvsyo.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxjudez.html

[T45] Perl：数组遍历
来源：http://dali.ehwqpu.com/Article/details/gt2ymdyrcgy.html

for my $x (@arr) { print $x; }
来源：http://dali.nanxuanxn.top/Article/details/gt2wxwfhfwq.html

[T46] Perl：哈希操作
来源：http://dali.nanxuanxn.top/Article/details/gt2rsnarpqr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hywenlv.cn/Article/details/gt2goujmlwa.html

[T47] Perl：正则捕获
来源：http://dali.hongshengwenyu.top/Article/details/gt2xrwoxrjs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.quarkkingdee.top/Article/details/gt2qhmcvhbx.html

[T48] Perl：正则替换
来源：http://dali.nanxinkj.top/Article/details/gt2duvyzfdl.html

$s =~ s/old/new/g;
来源：http://dali.jlsjyb.cn/Article/details/gt2ujzalwbq.html

[T49] Perl：函数
来源：http://dali.ybcxt.top/Article/details/gt2shbqtelh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gt2jwtcnnnq.html

[T50] Perl：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gt2zggsouxw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.kuanghao11.cn/Article/details/gt2wuetbyug.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuxming.cn/Article/details/gt2xvglkvag.html

[T51] Scala：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2vsxqidwr.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gt2sujsopfb.html

[T52] Scala：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjvnujnn.html

val a = 1;  var b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2gpwhzdli.html

[T53] Scala：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gt2hbqcgszf.html

s"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gacixhwy.html

[T54] Scala：集合映射
来源：http://dali.sxryk.cn/Article/details/gt2ogjhogmj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tanke756.top/Article/details/gt2zhuwppdl.html

[T55] Scala：集合过滤
来源：http://dali.dashuyun.cn/Article/details/gt2mfbarvwo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gogol.net.cn/Article/details/gt2jwtmaquv.html

[T56] Scala：样例类
来源：http://dali.zycfv.cn/Article/details/gt2twuspizu.html

case class User(name: String, age: Int)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nwhrfakc.html

[T57] Scala：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gt2rfokbtvs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.meibo888.top/Article/details/gt2fpgbefoe.html

[T58] Scala：函数定义
来源：http://dali.vqdsnc.cn/Article/details/gt2junwhbrn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nwbrower.top/Article/details/gt2ecggbrxa.html

[T59] Scala：循环
来源：http://dali.yanxiufei.cn/Article/details/gt2girtnzqd.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gt2iwfhwlhe.html

[T60] Scala：折叠
来源：http://dali.yuxming.cn/Article/details/gt2qdttcrep.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.redwolf501.top/Article/details/gt2gyruzndv.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2nxaaqazi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nwbrower.top/Article/details/gt2skqcutji.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dxerjhhw.html

[U01] Py：创建虚拟环境
来源：http://dali.yanxiufei.cn/Article/details/gt2tcsfmwwe.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cashguo.top/Article/details/gt2wexdimnc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yvedp.cn/Article/details/gt2tvexrizs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2mdcxnkyf.html

[U03] Py：加载 .env 配置
来源：http://dali.ehwqpu.com/Article/details/gt2srezkmks.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgfzy.top/Article/details/gt2pwgvoysy.html

[U04] Py：变量调试打印
来源：http://dali.dianchejie.cn/Article/details/gt2qinzkuev.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yanxiufei.cn/Article/details/gt2ftoqepli.html

[U05] Py：列表去重且保序
来源：http://dali.zhiwuduotai.top/Article/details/gt2eymqjpuk.html

list(dict.fromkeys(arr))
来源：http://dali.cashguo.top/Article/details/gt2ctzfpkrq.html

[U06] Py：合并两个字典
来源：http://dali.aibaodan.cn/Article/details/gt2lwtsbuul.html

{**a, **b}
来源：http://dali.mhx1999.top/Article/details/gt2zlrnxtuw.html

[U07] Py：反转字典键值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jfsiywmy.html

{v: k for k, v in d.items()}
来源：http://dali.c1oappe.top/Article/details/gt2pbjdnypv.html

[U08] Py：展平二维列表
来源：http://dali.sysykeji.top/Article/details/gt2fryvjdrq.html

[y for x in nested for y in x]
来源：http://dali.sweek.top/Article/details/gt2hsxpofli.html

[U09] Py：字典取最大值的键
来源：http://dali.zhiwuduotai.top/Article/details/gt2qqaxodgc.html

max(d, key=d.get)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nzguscek.html

[U10] Py：按值排序字典
来源：http://dali.aibaodan.cn/Article/details/gt2amspnkhv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yanxiufei.cn/Article/details/gt2ohquricu.html

[U11] Py：生成器表达式
来源：http://dali.yj20258.top/Article/details/gt2kcnzmkqk.html

(x * 2 for x in arr)
来源：http://dali.zhixingplan.top/Article/details/gt2mzcesihm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zycfv.cn/Article/details/gt2cqbspirk.html

Counter(arr).most_common(3)
来源：http://dali.xylfe.cn/Article/details/gt2mrgyeyoi.html

[U13] Py：固定长度队列
来源：http://dali.yongpay.top/Article/details/gt2ydcxoxlu.html

deque(maxlen=10)
来源：http://dali.dashuyun.cn/Article/details/gt2vwlcnpqb.html

[U14] Py：分组收集到列表
来源：http://dali.hnqzz.top/Article/details/gt2xsqljigm.html

defaultdict(list)
来源：http://dali.aizwys.cn/Article/details/gt2fbwcjmvd.html

[U15] Py：高精度计时
来源：http://dali.shuidangran.top/Article/details/gt2aeocizev.html

t = time.perf_counter()
来源：http://dali.xylfe.cn/Article/details/gt2wwbzuvyl.html

[U16] Py：命令行参数解析
来源：http://dali.jlsjyb.cn/Article/details/gt2wxcpvura.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hammf.cn/Article/details/gt2uunabywh.html

[U17] Py：初始化日志
来源：http://dali.feifeiyinyue.top/Article/details/gt2jjoifbky.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gogol.net.cn/Article/details/gt2uxoqgebl.html

[U18] Py：预编译正则
来源：http://dali.haohaochexian.top/Article/details/gt2rbayxkom.html

pat = re.compile(r"\d+")
来源：http://dali.iojbl.cn/Article/details/gt2jnrwzbgz.html

[U19] Py：正则替换带回调
来源：http://dali.sxryk.cn/Article/details/gt2mgvgnbvw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hfpthk.cn/Article/details/gt2mtgjcunx.html

[U20] Py：缓存函数结果
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ijtfwbsf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xuanzx.com/Article/details/gt2yjhwugil.html

[U21] Py：自定义上下文管理器
来源：http://dali.pycfn.com/Article/details/gt2jbjauadf.html

@contextlib.contextmanager
来源：http://dali.yuanzhike.top/Article/details/gt2jjprjhqh.html

[U22] Py：矩阵转置
来源：http://dali.shuidangran.top/Article/details/gt2rvdcglop.html

list(zip(*m))
来源：http://dali.wangdashe.top/Article/details/gt2udbdrwvt.html

[U23] Py：分块读取大文件
来源：http://dali.gogol.net.cn/Article/details/gt2xkrombdi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sysykeji.top/Article/details/gt2sgcmkqaa.html

[U24] Py：路径操作
来源：http://dali.daxiang520.top/Article/details/gt2eabjufkx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2cxoaoclb.html

[U25] Py：CSV 按字典读
来源：http://dali.gaohongyu789.top/Article/details/gt2lsgejlvi.html

csv.DictReader(f)
来源：http://dali.meibo888.top/Article/details/gt2kdysemnt.html

[U26] Py：并发下载
来源：http://dali.sysykeji.top/Article/details/gt2iphtjtpm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jiagoushi.top/Article/details/gt2ucntbmeo.html

[U27] Py：异步 HTTP
来源：http://dali.pengpengdd.cyou/Article/details/gt2ljejrayf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gmcnlybn.html

[U28] Py：类型别名
来源：http://dali.fengsongda.top/Article/details/gt2jfcggzzo.html

UserId = int
来源：http://dali.hysaishi.cn/Article/details/gt2qamndwib.html

[U29] Py：属性校验
来源：http://dali.haohaochexian.top/Article/details/gt2raifkayv.html

@property 与 @x.setter 配合
来源：http://dali.sufxvd.cn/Article/details/gt2xtlyzkuv.html

[U30] Py：数据类
来源：http://dali.yongpay.top/Article/details/gt2giypoaje.html

@dataclass(slots=True)
来源：http://dali.zdqjudy.top/Article/details/gt2wniqrala.html

[U31] Py：单测
来源：http://dali.yanxiufei.cn/Article/details/gt2prtypail.html

python -m pytest -q
来源：http://dali.yj202588.top/Article/details/gt2ozkztthh.html

[U32] Py：代码格式化
来源：http://dali.cqqwz.cn/Article/details/gt2zojnbhfn.html

ruff format . && ruff check --fix .
来源：http://dali.sufxvd.cn/Article/details/gt2vrvhipzt.html

[U33] Py：打包发布
来源：http://dali.yj20258.top/Article/details/gt2crzdqcwg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.andypj.xyz/Article/details/gt2fzhuxkcb.html

[U34] Py：判断编码
来源：http://dali.9152youxi.cn/Article/details/gt2pbwiskfw.html

chardet.detect(raw)
来源：http://dali.cucudq.cn/Article/details/gt2ejpsrdno.html

[U35] Py：发送邮件
来源：http://dali.chenzaomai.com/Article/details/gt2hswucjqa.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fmmhsnjd.html

[U36] Py：定时任务
来源：http://dali.hysaishi.cn/Article/details/gt2jmairwud.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj202588.top/Article/details/gt2bidoookw.html

[U37] Py：读写 Excel
来源：http://dali.ydzc1.top/Article/details/gt2bsdmennl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.aizwys.cn/Article/details/gt2mheidxva.html

[U38] Py：获取脚本所在目录
来源：http://dali.zycfv.cn/Article/details/gt2dfigkizo.html

Path(__file__).resolve().parent
来源：http://dali.havefunace.top/Article/details/gt2tmhpypjz.html

[U39] Py：判断是否在交互环境
来源：http://dali.hnxiangtu.top/Article/details/gt2zlkkkjhj.html

sys.stdout.isatty()
来源：http://dali.ybcxt.top/Article/details/gt2btdzbdlg.html

[U40] Py：打印到标准错误
来源：http://dali.cdnleiting.top/Article/details/gt2kiwuyoyk.html

print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gt2zkiqnrvi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.guannengcc.top/Article/details/gt2vgzwtute.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.0kj1m.cn/Article/details/gt2vfvmwvel.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhixingplan.top/Article/details/gt2fioplrxb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.smart0.xyz/Article/details/gt2rreiqxrj.html

[U43] PHP：声明命名空间
来源：http://dali.hammf.cn/Article/details/gt2izpfojpn.html

namespace App\Http;
来源：http://dali.chenlongwang.top/Article/details/gt2nszpexus.html

[U44] PHP：开启严格类型
来源：http://dali.kuanghao11.cn/Article/details/gt2kbymtzgk.html

declare(strict_types=1);
来源：http://dali.zhengqikj.top/Article/details/gt2obmsndsr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.c1oappe.top/Article/details/gt2udnvorlv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qrqdnvld.html

[U46] PHP：可空类型
来源：http://dali.cqqwz.cn/Article/details/gt2xlqgxvhu.html

?string $name = null
来源：http://dali.jinghuilouyu.cn/Article/details/gt2djgucmld.html

[U47] PHP：联合类型
来源：http://dali.nanxuanxn.top/Article/details/gt2hrvzxgjl.html

int|string $id
来源：http://dali.ybcxt.top/Article/details/gt2bpgfjkec.html

[U48] PHP：纯枚举
来源：http://dali.ybcxt.top/Article/details/gt2gksuggrt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jiagoushi.top/Article/details/gt2ljrngssj.html

[U49] PHP：只读属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hdqtmkjh.html

public readonly string $name
来源：http://dali.jinqigfzy.top/Article/details/gt2shgjuwbz.html

[U50] PHP：构造器属性提升
来源：http://dali.chenlongwang.top/Article/details/gt2uzbbubnb.html

public function __construct(private int $id) {}
来源：http://dali.guowangkeji.top/Article/details/gt2xlpganli.html

[U51] PHP：数组解构
来源：http://dali.zhongyouzk.top/Article/details/gt2qwlymnca.html

[$a, $b] = $arr;
来源：http://dali.chenjidiqi.icu/Article/details/gt2unbcqwwm.html

[U52] PHP：箭头函数
来源：http://dali.meibo888.top/Article/details/gt2iwggrtfe.html

$double = fn($x) => $x * 2;
来源：http://dali.feifeiyinyue.top/Article/details/gt2lptklbwi.html

[U53] PHP：空合并运算符
来源：http://dali.ivvv.top/Article/details/gt2xfeecizf.html

$v = $a ?? $b ?? "default";
来源：http://dali.ppjwa.cn/Article/details/gt2dxddrncs.html

[U54] PHP：空安全调用
来源：http://dali.tanke756.top/Article/details/gt2kmbtyqrb.html

$obj?->method()
来源：http://dali.jinqigfzy.top/Article/details/gt2sptgmewi.html

[U55] PHP：match 表达式
来源：http://dali.fzhhl.top/Article/details/gt2avilzjok.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.bjfxy.top/Article/details/gt2dyaulcfr.html

[U56] PHP：命名参数
来源：http://dali.daria6918.cn/Article/details/gt2tghelkie.html

f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gt2bdagjcbd.html

[U57] PHP：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gt2qbwejlgo.html

"值: {$a}"
来源：http://dali.zdqjudy.top/Article/details/gt2umizznru.html

[U58] PHP：数组三件套
来源：http://dali.sufxvd.cn/Article/details/gt2jbsfjhfp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jyoumei.cn/Article/details/gt2kxgvegjd.html

[U59] PHP：自定义排序
来源：http://dali.pycfn.com/Article/details/gt2bduwncfu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zdqjudy.top/Article/details/gt2vmgnspmq.html

[U60] PHP：JSON 编解码
来源：http://dali.aibaodan.cn/Article/details/gt2cdmqlrfv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.0kj1m.cn/Article/details/gt2ssouzolm.html

[U61] PHP：正则
来源：http://dali.xinyue.icu/Article/details/gt2offmkavz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sysykeji.top/Article/details/gt2wdusnpkj.html

[U62] PHP：日期对象
来源：http://dali.yonumen.top/Article/details/gt2hmcfssac.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj20258888.top/Article/details/gt2jirqnkjh.html

[U63] PHP：文件读写
来源：http://dali.yangfankeji.com/Article/details/gt2epoedybl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.daxiang520.top/Article/details/gt2dmuxgrej.html

[U64] PHP：目录遍历
来源：http://dali.andypj.xyz/Article/details/gt2dczguteo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.dianchejie.cn/Article/details/gt2fbqvxdou.html

[U65] PHP：会话
来源：http://dali.hywenlv.cn/Article/details/gt2gzigmddc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.tanke756.top/Article/details/gt2djzlgpqy.html

[U66] PHP：设置 Cookie
来源：http://dali.jqgfzy.top/Article/details/gt2ebgbzrpo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.smart0.xyz/Article/details/gt2uqrhjnea.html

[U67] PHP：处理文件上传
来源：http://dali.ehwqpu.com/Article/details/gt2jnwlseww.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cdnleiting.top/Article/details/gt2rkmhjvmh.html

[U68] PHP：PDO 连接
来源：http://dali.mhx1999.top/Article/details/gt2ozkwyrho.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jianghu66.top/Article/details/gt2erpkmqlo.html

[U69] PHP：PDO 预处理
来源：http://dali.9152youxi.cn/Article/details/gt2qrhewhbc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jwlvruob.html

[U70] PHP：PDO 事务
来源：http://dali.tianlin.xyz/Article/details/gt2nbpqwhhd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.nwbrower.top/Article/details/gt2dfisfkzo.html

[U71] PHP：抛出异常
来源：http://dali.fengsongda.top/Article/details/gt2axjfmnwo.html

throw new RuntimeException("失败", 500);
来源：http://dali.tian-w.cn/Article/details/gt2swnoruiq.html

[U72] PHP：写错误日志
来源：http://dali.yueranfly.top/Article/details/gt2otbvmccn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.tian-w.cn/Article/details/gt2ejecigdx.html


<!-- 参考信息 -->