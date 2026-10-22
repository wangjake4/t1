代发 wailian999

[S43] C++：智能指针
来源：http://dali.havefunace.top/Article/details/gt2vdvujsyc.html

auto p = std::make_unique<int>(5);
来源：http://dali.shuidangran.top/Article/details/gt2bqufoqbi.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zawxvtdu.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258.top/Article/details/gt2vvefozfb.html

[S45] C++：lambda
来源：http://dali.sxryk.cn/Article/details/gt2uxkrdchm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.9152youxi.cn/Article/details/gt2mmexesjb.html

[S46] C++：函数模板
来源：http://dali.yangfankeji.com/Article/details/gt2qnlxnugr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cqqwz.cn/Article/details/gt2gmepxwkn.html

[S47] C++：结构化绑定遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2backerpw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kxdiybxp.html

[S48] C++：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2tucjljio.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dqkeygdw.html

while (std::getline(in, line)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ktyaqohj.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gt2ddkxywnw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sysykeji.top/Article/details/gt2yoqfkxyq.html

[S50] C++：格式化数字
来源：http://dali.pycfn.com/Article/details/gt2elwwlkfb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fzhhl.top/Article/details/gt2gaerlrzo.html

[S51] C++：显式类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubpgxvgl.html

static_cast<double>(a) / b
来源：http://dali.ydzc1.top/Article/details/gt2rjricblg.html

[S52] C++：const 与 noexcept
来源：http://dali.c1oappe.top/Article/details/gt2ekhawukb.html

int size() const noexcept { return n_; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xfknqtto.html

[S53] C++：移动语义
来源：http://dali.c1oappe.top/Article/details/gt2zgehreby.html

std::vector<int> w = std::move(v);
来源：http://dali.tanke756.top/Article/details/gt2lejbnqzn.html

[S54] C++：异常处理
来源：http://dali.xylfe.cn/Article/details/gt2wpncboxh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.bjfxy.top/Article/details/gt2nykianev.html

[S55] C++：结构化绑定
来源：http://dali.shangyingyoupin.top/Article/details/gt2khldyuft.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guannengcc.top/Article/details/gt2utppiqan.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gt2grgcsqvs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2huzkakgx.html

[S57] C++：编译期常量
来源：http://dali.gotoacloud.top/Article/details/gt2wcelwhue.html

constexpr int N = 10;
来源：http://dali.andypj.xyz/Article/details/gt2kbcragrk.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gt2dhqoqetj.html

namespace ns { int f() { return 1; } }
来源：http://dali.kuanghao11.cn/Article/details/gt2dlsjhklh.html

[S59] C++：静态断言
来源：http://dali.mhx1999.top/Article/details/gt2bihzzwyc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fzhhl.top/Article/details/gt2pwtofmcl.html

[S60] C++：遍历并删除元素
来源：http://dali.birdmap.top/Article/details/gt2vbrstgal.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cashguo.top/Article/details/gt2zrtynduo.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2esmbinpb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yangfankeji.com/Article/details/gt2xumlnbzs.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2zddxvoxj.html

[T01] Kotlin：Hello World
来源：http://dali.yonumen.top/Article/details/gt2bogtttdo.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gt2noudsuus.html

[T02] Kotlin：变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2heqxgsqg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tanke756.top/Article/details/gt2xqmferop.html

[T03] Kotlin：字符串模板
来源：http://dali.c1oappe.top/Article/details/gt2ipqdzhsn.html

"值: $b"
来源：http://dali.birdmap.top/Article/details/gt2ruvfhtgy.html

[T04] Kotlin：空安全
来源：http://dali.hnxiangtu.top/Article/details/gt2awenyofo.html

val n: String? = null;  n?.length
来源：http://dali.jqgfzy.top/Article/details/gt2ffzohenk.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gt2juaxezjc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daria6918.cn/Article/details/gt2hflpxjub.html

[T06] Kotlin：集合映射
来源：http://dali.zycfv.cn/Article/details/gt2fgklvpav.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2jxtvuiol.html

[T07] Kotlin：集合过滤
来源：http://dali.nwbrower.top/Article/details/gt2hetvoryx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yvedp.cn/Article/details/gt2ffglxrrx.html

[T08] Kotlin：数据类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vppxqkbx.html

data class User(val name: String, val age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gt2pmythgio.html

[T09] Kotlin：扩展函数
来源：http://dali.chenzaomai.com/Article/details/gt2yacszpvx.html

fun String.exclaim() = this + "!"
来源：http://dali.chenzaomai.com/Article/details/gt2vdhswzgj.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dqsfqwoq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xlvbswrx.html

[T11] Kotlin：协程
来源：http://dali.zdqjudy.top/Article/details/gt2jjzoqjsq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yangfankeji.com/Article/details/gt2tpzysguj.html

[T12] Kotlin：解构声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhszqjmr.html

val (a, b) = Pair(1, 2)
来源：http://dali.hnqzz.top/Article/details/gt2xnfraqep.html

[T13] Kotlin：只读 Map
来源：http://dali.zhengqikj.top/Article/details/gt2qndoxsum.html

val m = mapOf("a" to 1)
来源：http://dali.aibaodan.cn/Article/details/gt2eafzoqtc.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2igjcpumw.html

for (i in 1..10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gt2ovlkiexj.html

[T15] Kotlin：接口
来源：http://dali.yj20258.top/Article/details/gt2uorhqnnf.html

interface Shape { fun area(): Double }
来源：http://dali.fzhhl.top/Article/details/gt2vrnktjlu.html

[T16] Swift：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2acobaiur.html

print("Hello")
来源：http://dali.zycfv.cn/Article/details/gt2oxauzwvu.html

[T17] Swift：变量与常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xirfprsm.html

var a = 1;  let b = 2
来源：http://dali.dianchejie.cn/Article/details/gt2adjmgpjg.html

[T18] Swift：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gt2jwnnihcz.html

"值: \(b)"
来源：http://dali.gotoacloud.top/Article/details/gt2uptgcvfc.html

[T19] Swift：可选绑定
来源：http://dali.nanxuanxn.top/Article/details/gt2himinuaq.html

if let n = opt { print(n) }
来源：http://dali.xuanzx.com/Article/details/gt2lwlwmzom.html

[T20] Swift：数组操作
来源：http://dali.jyoumei.cn/Article/details/gt2pcdcmjig.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwzbdpy.html

[T21] Swift：遍历
来源：http://dali.zycfv.cn/Article/details/gt2wzunwfgy.html

for x in a { print(x) }
来源：http://dali.jinqigufen.top/Article/details/gt2chebnfxu.html

[T22] Swift：字典
来源：http://dali.dianchejie.cn/Article/details/gt2azkagfbj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2bsxwwycp.html

[T23] Swift：函数
来源：http://dali.sxryk.cn/Article/details/gt2iuktuvrf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zdqjudy.top/Article/details/gt2evswioya.html

[T24] Swift：闭包
来源：http://dali.kuanghao11.cn/Article/details/gt2jttblauz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gt2hswlajit.html

[T25] Swift：结构体
来源：http://dali.xuetiantiany.cn/Article/details/gt2dcjdbfpt.html

struct P { var x: Int }
来源：http://dali.kuanghao11.cn/Article/details/gt2hythpjhq.html

[T26] Swift：类与重写
来源：http://dali.bjfxy.top/Article/details/gt2shitlyox.html

class A: Base { override func f() {} }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vmkosvtu.html

[T27] Swift：错误处理
来源：http://dali.shzxlz.cn/Article/details/gt2cbmaeutw.html

do { try f() } catch { print(error) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bmuooeex.html

[T28] Swift：枚举
来源：http://dali.zhengqikj.top/Article/details/gt2dshxdwoy.html

enum Color { case red, green }
来源：http://dali.bjfxy.top/Article/details/gt2jyohaybl.html

[T29] Swift：guard 提前返回
来源：http://dali.cdnleiting.top/Article/details/gt2hcajzhbn.html

guard let x = opt else { return }
来源：http://dali.ybcxt.top/Article/details/gt2ppwpvkbl.html

[T30] Swift：协议
来源：http://dali.shuidangran.top/Article/details/gt2soyuahty.html

protocol Shape { func area() -> Double }
来源：http://dali.haohaochexian.top/Article/details/gt2mhwjfmub.html

[T31] Lua：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2mdjefisf.html

print("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zdmwtslf.html

[T32] Lua：局部变量
来源：http://dali.zhengqikj.top/Article/details/gt2ndsmfbcy.html

local a = 1
来源：http://dali.dashuyun.cn/Article/details/gt2hohcezqd.html

[T33] Lua：表（数组）
来源：http://dali.fengsongda.top/Article/details/gt2ljonrqxf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ivvv.top/Article/details/gt2xbdjwrvl.html

[T34] Lua：遍历表
来源：http://dali.yangfankeji.com/Article/details/gt2jqfszbjg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shangyingyoupin.top/Article/details/gt2lauykemj.html

[T35] Lua：字典表
来源：http://dali.yanxiufei.cn/Article/details/gt2auailkcy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tanke756.top/Article/details/gt2fuiomjbb.html

[T36] Lua：函数
来源：http://dali.hysaishi.cn/Article/details/gt2jyyozzlb.html

function add(a, b) return a + b end
来源：http://dali.gzhubu.top/Article/details/gt2ernjskrs.html

[T37] Lua：字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zlrgkszh.html

"a" .. "b"
来源：http://dali.cashguo.top/Article/details/gt2qcuufvsg.html

[T38] Lua：条件
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptwmnbho.html

if x > 0 then print("正") end
来源：http://dali.gogol.net.cn/Article/details/gt2ndfslyhy.html

[T39] Lua：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gt2bkhaypdr.html

string.find(s, "%d+")
来源：http://dali.xuanzx.com/Article/details/gt2zxulavra.html

[T40] Lua：元表
来源：http://dali.xuanzx.com/Article/details/gt2vflhzbgk.html

setmetatable({}, { __index = base })
来源：http://dali.cheryme.top/Article/details/gt2lrpmuokc.html

[T41] Perl：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2quccnffs.html

print "Hello\n";
来源：http://dali.meibo888.top/Article/details/gt2phcieqiy.html

[T42] Perl：变量类型
来源：http://dali.yanxiufei.cn/Article/details/gt2bekeghzg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2wgurglqt.html

[T43] Perl：字符串插值
来源：http://dali.yj202588.top/Article/details/gt2jafqaydw.html

"值: $a"
来源：http://dali.hysaishi.cn/Article/details/gt2tecnrlcr.html

[T44] Perl：条件
来源：http://dali.vqdsnc.cn/Article/details/gt2jsfsdnto.html

if ($a > 0) { print "正"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2eeprhndq.html

[T45] Perl：数组遍历
来源：http://dali.hammf.cn/Article/details/gt2kqlwuhzb.html

for my $x (@arr) { print $x; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lfisdrvq.html

[T46] Perl：哈希操作
来源：http://dali.wangshuangyany.cn/Article/details/gt2nhisiiep.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uujrslaz.html

[T47] Perl：正则捕获
来源：http://dali.fzhhl.top/Article/details/gt2bvcexgsm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dashuyun.cn/Article/details/gt2bsabsjet.html

[T48] Perl：正则替换
来源：http://dali.yangfankeji.com/Article/details/gt2yoyktkci.html

$s =~ s/old/new/g;
来源：http://dali.ybcxt.top/Article/details/gt2vhjvmbed.html

[T49] Perl：函数
来源：http://dali.jqgufenzy.top/Article/details/gt2sluvbejy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gt2icduzhxr.html

[T50] Perl：逐行读文件
来源：http://dali.yongpay.top/Article/details/gt2uieqavbh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.kuanghao11.cn/Article/details/gt2lufposaf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2futsebgk.html

[T51] Scala：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2betzcorw.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gt2cwlvqwdc.html

[T52] Scala：变量
来源：http://dali.ehwqpu.com/Article/details/gt2tmnjjipy.html

val a = 1;  var b = 2
来源：http://dali.iojbl.cn/Article/details/gt2hwzhecvx.html

[T53] Scala：字符串插值
来源：http://dali.daxiang520.top/Article/details/gt2ohikmkrb.html

s"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gt2wdkedmar.html

[T54] Scala：集合映射
来源：http://dali.fengsongda.top/Article/details/gt2gnoebgkg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rmcczndb.html

[T55] Scala：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gt2kifsfhad.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guannengcc.top/Article/details/gt2jdzkntqn.html

[T56] Scala：样例类
来源：http://dali.yonumen.top/Article/details/gt2vojzigav.html

case class User(name: String, age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hfafhlqz.html

[T57] Scala：模式匹配
来源：http://dali.havefunace.top/Article/details/gt2todqdpob.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.redwolf501.top/Article/details/gt2hxwwsmhy.html

[T58] Scala：函数定义
来源：http://dali.gogol.net.cn/Article/details/gt2vvbbjufp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sufxvd.cn/Article/details/gt2tlynfgmv.html

[T59] Scala：循环
来源：http://dali.zhengqikj.top/Article/details/gt2bmlfxznd.html

for (i <- 1 to 10) println(i)
来源：http://dali.xinyue.icu/Article/details/gt2vkkttfhl.html

[T60] Scala：折叠
来源：http://dali.hnqzz.top/Article/details/gt2narzjikx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ehwqpu.com/Article/details/gt2hxyebfqi.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2vhrgpoyb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenlongwang.top/Article/details/gt2yobeyugq.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2bdnnxzqf.html

[U01] Py：创建虚拟环境
来源：http://dali.chenjidiqi.icu/Article/details/gt2rszfotra.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tanke756.top/Article/details/gt2ujxfbunw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.birdmap.top/Article/details/gt2hftumnnn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dianchejie.cn/Article/details/gt2kwwfszrv.html

[U03] Py：加载 .env 配置
来源：http://dali.0kj1m.cn/Article/details/gt2piylokbh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yongpay.top/Article/details/gt2kwtktqki.html

[U04] Py：变量调试打印
来源：http://dali.zhiwuduotai.top/Article/details/gt2dxnudenm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cheryme.top/Article/details/gt2ajtgsraw.html

[U05] Py：列表去重且保序
来源：http://dali.vqdsnc.cn/Article/details/gt2nrdzuurp.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gt2vthkwcxr.html

[U06] Py：合并两个字典
来源：http://dali.hysaishi.cn/Article/details/gt2cyjgqsef.html

{**a, **b}
来源：http://dali.shzxlz.cn/Article/details/gt2zkjbizon.html

[U07] Py：反转字典键值
来源：http://dali.cashguo.top/Article/details/gt2ysybnukq.html

{v: k for k, v in d.items()}
来源：http://dali.kuanghao11.cn/Article/details/gt2snftjzck.html

[U08] Py：展平二维列表
来源：http://dali.yangfankeji.com/Article/details/gt2kmpyfgpn.html

[y for x in nested for y in x]
来源：http://dali.hnxiangtu.top/Article/details/gt2droodbnh.html

[U09] Py：字典取最大值的键
来源：http://dali.fzhhl.top/Article/details/gt2lhdqqrms.html

max(d, key=d.get)
来源：http://dali.tianlin.xyz/Article/details/gt2yrbhqsqm.html

[U10] Py：按值排序字典
来源：http://dali.zycfv.cn/Article/details/gt2cimweacq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yongpay.top/Article/details/gt2kdxuhhsf.html

[U11] Py：生成器表达式
来源：http://dali.yonumen.top/Article/details/gt2pskaxcey.html

(x * 2 for x in arr)
来源：http://dali.fzhhl.top/Article/details/gt2aknuaxaf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khehbifg.html

Counter(arr).most_common(3)
来源：http://dali.ivvv.top/Article/details/gt2pswtzqzj.html

[U13] Py：固定长度队列
来源：http://dali.haohaochexian.top/Article/details/gt2ibkquwbh.html

deque(maxlen=10)
来源：http://dali.chenzaomai.com/Article/details/gt2kavpvqvm.html

[U14] Py：分组收集到列表
来源：http://dali.zhengqikj.top/Article/details/gt2piqugecj.html

defaultdict(list)
来源：http://dali.yj20258.top/Article/details/gt2densnehv.html

[U15] Py：高精度计时
来源：http://dali.havefunace.top/Article/details/gt2wxvlmypl.html

t = time.perf_counter()
来源：http://dali.nanxinkj.top/Article/details/gt2gbcpqtcf.html

[U16] Py：命令行参数解析
来源：http://dali.zycfv.cn/Article/details/gt2yfpwvato.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.vqdsnc.cn/Article/details/gt2zdpkyaok.html

[U17] Py：初始化日志
来源：http://dali.gzhubu.top/Article/details/gt2qlwwifqc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.316326.xyz/Article/details/gt2gqwwefyr.html

[U18] Py：预编译正则
来源：http://dali.tianlin.xyz/Article/details/gt2wspdguxf.html

pat = re.compile(r"\d+")
来源：http://dali.zhoulong.xyz/Article/details/gt2vhbhkrvl.html

[U19] Py：正则替换带回调
来源：http://dali.yonumen.top/Article/details/gt2ijqizkle.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.birdmap.top/Article/details/gt2shtcctlv.html

[U20] Py：缓存函数结果
来源：http://dali.haohaochexian.top/Article/details/gt2kainvmic.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xziqi.cn/Article/details/gt2gtcpppzw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zdqjudy.top/Article/details/gt2kwzxhzpn.html

@contextlib.contextmanager
来源：http://dali.quarkkingdee.top/Article/details/gt2vekqufzu.html

[U22] Py：矩阵转置
来源：http://dali.hnqzz.top/Article/details/gt2fdevgojj.html

list(zip(*m))
来源：http://dali.sxryk.cn/Article/details/gt2afcahyzz.html

[U23] Py：分块读取大文件
来源：http://dali.jinqigufen.top/Article/details/gt2okzdssgb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.andypj.xyz/Article/details/gt2ngxfxfct.html

[U24] Py：路径操作
来源：http://dali.haohaochexian.top/Article/details/gt2alricpwi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sweek.top/Article/details/gt2nazlraxq.html

[U25] Py：CSV 按字典读
来源：http://dali.jlsjyb.cn/Article/details/gt2vmftuqrs.html

csv.DictReader(f)
来源：http://dali.ehwqpu.com/Article/details/gt2wetnfbas.html

[U26] Py：并发下载
来源：http://dali.shuidangran.top/Article/details/gt2oxghvvfz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.bjfxy.top/Article/details/gt2rfurjkmy.html

[U27] Py：异步 HTTP
来源：http://dali.zhoulong.xyz/Article/details/gt2phinrxuh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.vqdsnc.cn/Article/details/gt2jymbehqe.html

[U28] Py：类型别名
来源：http://dali.vqdsnc.cn/Article/details/gt2jnrkbevz.html

UserId = int
来源：http://dali.svipenyu.cn/Article/details/gt2lakxfeps.html

[U29] Py：属性校验
来源：http://dali.nwbrower.top/Article/details/gt2rysqbmgj.html

@property 与 @x.setter 配合
来源：http://dali.hfpthk.cn/Article/details/gt2qvtbkkvc.html

[U30] Py：数据类
来源：http://dali.hnqzz.top/Article/details/gt2iopxkmzj.html

@dataclass(slots=True)
来源：http://dali.aibaodan.cn/Article/details/gt2zqhubaqq.html

[U31] Py：单测
来源：http://dali.chenlongwang.top/Article/details/gt2irfdoyrb.html

python -m pytest -q
来源：http://dali.sufxvd.cn/Article/details/gt2eexgelge.html

[U32] Py：代码格式化
来源：http://dali.xuetiantiany.cn/Article/details/gt2crlmswvk.html

ruff format . && ruff check --fix .
来源：http://dali.xziqi.cn/Article/details/gt2dmzlcmbq.html

[U33] Py：打包发布
来源：http://dali.feifeiyinyue.top/Article/details/gt2aqhfqkni.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.haohaochexian.top/Article/details/gt2vkbvzxze.html

[U34] Py：判断编码
来源：http://dali.hnxiangtu.top/Article/details/gt2cuoloney.html

chardet.detect(raw)
来源：http://dali.yvedp.cn/Article/details/gt2uymckpwr.html

[U35] Py：发送邮件
来源：http://dali.hysaishi.cn/Article/details/gt2zzxjshwg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ifypqyjy.html

[U36] Py：定时任务
来源：http://dali.havefunace.top/Article/details/gt2kovqtovf.html

schedule.every(10).minutes.do(job)
来源：http://dali.jiagoushi.top/Article/details/gt2xpwfyldr.html

[U37] Py：读写 Excel
来源：http://dali.sysykeji.top/Article/details/gt2qzrfqjit.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ivvv.top/Article/details/gt2npyheqco.html

[U38] Py：获取脚本所在目录
来源：http://dali.kuanghao11.cn/Article/details/gt2zvyoxasi.html

Path(__file__).resolve().parent
来源：http://dali.tian-w.cn/Article/details/gt2hcbynozs.html

[U39] Py：判断是否在交互环境
来源：http://dali.redwolf501.top/Article/details/gt2brejagvr.html

sys.stdout.isatty()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tdbddugx.html

[U40] Py：打印到标准错误
来源：http://dali.jqgufenzy.top/Article/details/gt2sdwpqziu.html

print("err", file=sys.stderr)
来源：http://dali.ivvv.top/Article/details/gt2ppfophhw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wlptaehl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2cswqhlaa.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.0kj1m.cn/Article/details/gt2rsfvaylo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gnfynrbh.html

[U43] PHP：声明命名空间
来源：http://dali.zdqjudy.top/Article/details/gt2swcfkmmh.html

namespace App\Http;
来源：http://dali.gzhubu.top/Article/details/gt2awqvychd.html

[U44] PHP：开启严格类型
来源：http://dali.zhengqikj.top/Article/details/gt2ezhzplyn.html

declare(strict_types=1);
来源：http://dali.mhx1999.top/Article/details/gt2tlaixchn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.aibaodan.cn/Article/details/gt2amrelaje.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gt2dymdhvbw.html

[U46] PHP：可空类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2vhocwkfr.html

?string $name = null
来源：http://dali.guannengcc.top/Article/details/gt2stbqdshc.html

[U47] PHP：联合类型
来源：http://dali.xziqi.cn/Article/details/gt2xcpxleyl.html

int|string $id
来源：http://dali.gotoacloud.top/Article/details/gt2yurdclov.html

[U48] PHP：纯枚举
来源：http://dali.guowangkeji.top/Article/details/gt2nhdmzojy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.wangdashe.top/Article/details/gt2etddtyon.html

[U49] PHP：只读属性
来源：http://dali.yvedp.cn/Article/details/gt2txnuwjbv.html

public readonly string $name
来源：http://dali.feifeiyinyue.top/Article/details/gt2qizhduas.html

[U50] PHP：构造器属性提升
来源：http://dali.snrcjt.cn/Article/details/gt2eutxhhsu.html

public function __construct(private int $id) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2oorjdohi.html

[U51] PHP：数组解构
来源：http://dali.ybcxt.top/Article/details/gt2yvfooatf.html

[$a, $b] = $arr;
来源：http://dali.cheryme.top/Article/details/gt2ucjtgrls.html

[U52] PHP：箭头函数
来源：http://dali.jianghu66.top/Article/details/gt2xypxfbij.html

$double = fn($x) => $x * 2;
来源：http://dali.svipenyu.cn/Article/details/gt2xrgutuuk.html

[U53] PHP：空合并运算符
来源：http://dali.yueranfly.top/Article/details/gt2iabuaker.html

$v = $a ?? $b ?? "default";
来源：http://dali.gotoacloud.top/Article/details/gt2rfntlwkk.html

[U54] PHP：空安全调用
来源：http://dali.shuidangran.top/Article/details/gt2rcmknbdj.html

$obj?->method()
来源：http://dali.nanxinkj.top/Article/details/gt2sxqzvszc.html

[U55] PHP：match 表达式
来源：http://dali.nanxinkj.top/Article/details/gt2tgblrhya.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.guannengcc.top/Article/details/gt2revlcjuq.html

[U56] PHP：命名参数
来源：http://dali.xuanzx.com/Article/details/gt2svofqfqv.html

f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2uqacnkpw.html

[U57] PHP：字符串插值
来源：http://dali.ivvv.top/Article/details/gt2vcstifft.html

"值: {$a}"
来源：http://dali.ydzc1.top/Article/details/gt2pmeolgge.html

[U58] PHP：数组三件套
来源：http://dali.aibaodan.cn/Article/details/gt2bwkyvsve.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.havefunace.top/Article/details/gt2qoymkjpd.html

[U59] PHP：自定义排序
来源：http://dali.dianchejie.cn/Article/details/gt2ttoweojs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xmilwgdv.html

[U60] PHP：JSON 编解码
来源：http://dali.sxryk.cn/Article/details/gt2gyqfvddl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cashguo.top/Article/details/gt2hepaxbhg.html

[U61] PHP：正则
来源：http://dali.xuetiantiany.cn/Article/details/gt2kibszsph.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2smrebruh.html

[U62] PHP：日期对象
来源：http://dali.wangdashe.top/Article/details/gt2xlyuheqk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hammf.cn/Article/details/gt2cyvdsijy.html

[U63] PHP：文件读写
来源：http://dali.cheryme.top/Article/details/gt2tvpqbgmv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinqigfzy.top/Article/details/gt2oclbdmqx.html

[U64] PHP：目录遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2czgbghbt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwntpnjp.html

[U65] PHP：会话
来源：http://dali.316326.xyz/Article/details/gt2exvenrvs.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2gnkfmrnx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhixingplan.top/Article/details/gt2tgtsfclc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ydzc1.top/Article/details/gt2lakjsqlm.html

[U67] PHP：处理文件上传
来源：http://dali.chenjidiqi.icu/Article/details/gt2dtwralzz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.birdmap.top/Article/details/gt2oiqcqtlh.html

[U68] PHP：PDO 连接
来源：http://dali.zdqjudy.top/Article/details/gt2rlycrsmp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jqgufenzy.top/Article/details/gt2hrmghset.html


<!-- 参考信息 -->