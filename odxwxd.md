代发 wailian999

[S45] C++：lambda
来源：http://dali.dianchejie.cn/Article/details/gtyjmrogpb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuetiantiany.cn/Article/details/gtsjryitqr.html

[S46] C++：函数模板
来源：http://dali.nanxinkj.top/Article/details/gtdesaawsc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hywenlv.cn/Article/details/gtnhgtirgb.html

[S47] C++：结构化绑定遍历
来源：http://dali.yanxiufei.cn/Article/details/gtkrqnkcdb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ppjwa.cn/Article/details/gtxcfmqpbj.html

[S48] C++：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gtcxxusdrk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.daria6918.cn/Article/details/gtdfzurxal.html

while (std::getline(in, line)) { }
来源：http://dali.birdmap.top/Article/details/gtosqkvrtz.html

[S49] C++：写文件
来源：http://dali.yj20258.top/Article/details/gtpwzlhpsz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jiagoushi.top/Article/details/gtmpvvvapt.html

[S50] C++：格式化数字
来源：http://dali.jianghu66.top/Article/details/gtcxuoautc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzmpymfk.html

[S51] C++：显式类型转换
来源：http://dali.tanke756.top/Article/details/gtnmnatbdw.html

static_cast<double>(a) / b
来源：http://dali.daria6918.cn/Article/details/gtanitxosp.html

[S52] C++：const 与 noexcept
来源：http://dali.daxiang520.top/Article/details/gtihecwvpa.html

int size() const noexcept { return n_; }
来源：http://dali.zhoulong.xyz/Article/details/gtrqeeuone.html

[S53] C++：移动语义
来源：http://dali.jqgfzy.top/Article/details/gtqvsswvwf.html

std::vector<int> w = std::move(v);
来源：http://dali.hnxiangtu.top/Article/details/gtifrqakfr.html

[S54] C++：异常处理
来源：http://dali.meibo888.top/Article/details/gtumhvpetp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258888.top/Article/details/gtrgrhkovm.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gtnofwaltj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhixingplan.top/Article/details/gtpgagocss.html

[S56] C++：optional
来源：http://dali.chenzaomai.com/Article/details/gtjtefullh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenlongwang.top/Article/details/gttuoholhu.html

[S57] C++：编译期常量
来源：http://dali.zdqjudy.top/Article/details/gtqhtxkyan.html

constexpr int N = 10;
来源：http://dali.xinyue.icu/Article/details/gtlrgcdsak.html

[S58] C++：命名空间
来源：http://dali.zhoulong.xyz/Article/details/gtqzaxzron.html

namespace ns { int f() { return 1; } }
来源：http://dali.meibo888.top/Article/details/gtfqyvqdht.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtpacajepz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ybcxt.top/Article/details/gtkesoeass.html

[S60] C++：遍历并删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmmrqaoq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daxiang520.top/Article/details/gttryzoatc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtnvhuhysz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pengpengdd.cyou/Article/details/gtfpbthetr.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtisuxvsqu.html

[T01] Kotlin：Hello World
来源：http://dali.meibo888.top/Article/details/gtldvsjkkd.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtixceabji.html

[T02] Kotlin：变量
来源：http://dali.havefunace.top/Article/details/gtlbsqlwab.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhongyouzk.top/Article/details/gthjltfjfl.html

[T03] Kotlin：字符串模板
来源：http://dali.shangyingyoupin.top/Article/details/gtyjnjzsmd.html

"值: $b"
来源：http://dali.daxiang520.top/Article/details/gtvntburuy.html

[T04] Kotlin：空安全
来源：http://dali.shangyingyoupin.top/Article/details/gtouaensfo.html

val n: String? = null;  n?.length
来源：http://dali.bjfxy.top/Article/details/gtjphtcvnc.html

[T05] Kotlin：when 表达式
来源：http://dali.aibaodan.cn/Article/details/gtnebevnfo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinghuilouyu.cn/Article/details/gthhtvkvdl.html

[T06] Kotlin：集合映射
来源：http://dali.chenzaomai.com/Article/details/gtksvcfuwc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gzhubu.top/Article/details/gtzprrrmyj.html

[T07] Kotlin：集合过滤
来源：http://dali.havefunace.top/Article/details/gthfnpefhj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dianchejie.cn/Article/details/gtctazvvjf.html

[T08] Kotlin：数据类
来源：http://dali.shzxlz.cn/Article/details/gteuqfdhsp.html

data class User(val name: String, val age: Int)
来源：http://dali.haohaochexian.top/Article/details/gtxvhikvwe.html

[T09] Kotlin：扩展函数
来源：http://dali.xylfe.cn/Article/details/gtptctqrky.html

fun String.exclaim() = this + "!"
来源：http://dali.gotoacloud.top/Article/details/gttwrdqktl.html

[T10] Kotlin：默认参数
来源：http://dali.ydzc1.top/Article/details/gtuwmvaryt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuxming.cn/Article/details/gtcndkvaed.html

[T11] Kotlin：协程
来源：http://dali.pycfn.com/Article/details/gtevjpnzvs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hywenlv.cn/Article/details/gtjlkbgoke.html

[T12] Kotlin：解构声明
来源：http://dali.kuanghao11.cn/Article/details/gtmgfvztfz.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj202588.top/Article/details/gtvzjpegop.html

[T13] Kotlin：只读 Map
来源：http://dali.hnxiangtu.top/Article/details/gtlrnjnvlr.html

val m = mapOf("a" to 1)
来源：http://dali.redwolf501.top/Article/details/gtohncutfa.html

[T14] Kotlin：循环
来源：http://dali.c1oappe.top/Article/details/gtbbaukrnv.html

for (i in 1..10) println(i)
来源：http://dali.redwolf501.top/Article/details/gtviajcgih.html

[T15] Kotlin：接口
来源：http://dali.quarkkingdee.top/Article/details/gtagwxmczp.html

interface Shape { fun area(): Double }
来源：http://dali.feifeiyinyue.top/Article/details/gtswtntrax.html

[T16] Swift：Hello World
来源：http://dali.ydzc1.top/Article/details/gtvgpamhgp.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gtfmjqkfvl.html

[T17] Swift：变量与常量
来源：http://dali.svipenyu.cn/Article/details/gtinxczwtv.html

var a = 1;  let b = 2
来源：http://dali.havefunace.top/Article/details/gtiftssuvy.html

[T18] Swift：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtbvfqydtp.html

"值: \(b)"
来源：http://dali.zhiwuduotai.top/Article/details/gtgjqzuvxz.html

[T19] Swift：可选绑定
来源：http://dali.jinqigfzy.top/Article/details/gtgtciqcor.html

if let n = opt { print(n) }
来源：http://dali.cashguo.top/Article/details/gtgefixpxt.html

[T20] Swift：数组操作
来源：http://dali.jinqigufen.top/Article/details/gtqkfyuans.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daria6918.cn/Article/details/gtzgwqnchq.html

[T21] Swift：遍历
来源：http://dali.cqqwz.cn/Article/details/gtjddaoeqn.html

for x in a { print(x) }
来源：http://dali.yvedp.cn/Article/details/gtxcxhlaxn.html

[T22] Swift：字典
来源：http://dali.ppjwa.cn/Article/details/gtrktblnda.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xinyue.icu/Article/details/gtvebmqvpv.html

[T23] Swift：函数
来源：http://dali.daria6918.cn/Article/details/gtazotozyk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shzxlz.cn/Article/details/gtfbfxhlrh.html

[T24] Swift：闭包
来源：http://dali.guannengcc.top/Article/details/gtosnpwmol.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtopgyrmjo.html

[T25] Swift：结构体
来源：http://dali.xuetiantiany.cn/Article/details/gtgsabcbvb.html

struct P { var x: Int }
来源：http://dali.hfpthk.cn/Article/details/gtqaamatme.html

[T26] Swift：类与重写
来源：http://dali.jlsjyb.cn/Article/details/gtlykrkyqj.html

class A: Base { override func f() {} }
来源：http://dali.haohaochexian.top/Article/details/gtudapifhu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gtkzooagwd.html

do { try f() } catch { print(error) }
来源：http://dali.jianghu66.top/Article/details/gtmomnqjhn.html

[T28] Swift：枚举
来源：http://dali.yonumen.top/Article/details/gtsbevdlqm.html

enum Color { case red, green }
来源：http://dali.xziqi.cn/Article/details/gtezvpnfwp.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigfzy.top/Article/details/gtmutjaaqz.html

guard let x = opt else { return }
来源：http://dali.fengsongda.top/Article/details/gttkegujjn.html

[T30] Swift：协议
来源：http://dali.hongshengwenyu.top/Article/details/gtcbmbualb.html

protocol Shape { func area() -> Double }
来源：http://dali.ydzc1.top/Article/details/gtlndgydgy.html

[T31] Lua：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtbjcmoaka.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtavkoxuwx.html

[T32] Lua：局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtgbrodfcu.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gtkybqzagl.html

[T33] Lua：表（数组）
来源：http://dali.cqqwz.cn/Article/details/gtfuclbtls.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangdashe.top/Article/details/gtorneynpi.html

[T34] Lua：遍历表
来源：http://dali.jlsjyb.cn/Article/details/gtrjnxiyyz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gzhubu.top/Article/details/gthljluxdu.html

[T35] Lua：字典表
来源：http://dali.cashguo.top/Article/details/gtnloizibh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gthddneryb.html

[T36] Lua：函数
来源：http://dali.gzhubu.top/Article/details/gttqcyvoxl.html

function add(a, b) return a + b end
来源：http://dali.sweek.top/Article/details/gtlpoyemkh.html

[T37] Lua：字符串拼接
来源：http://dali.haohaochexian.top/Article/details/gtuvfnyuju.html

"a" .. "b"
来源：http://dali.jyoumei.cn/Article/details/gtsduxayex.html

[T38] Lua：条件
来源：http://dali.cucudq.cn/Article/details/gtfwfnwjqd.html

if x > 0 then print("正") end
来源：http://dali.ppjwa.cn/Article/details/gtvvnblosv.html

[T39] Lua：模式匹配
来源：http://dali.yj20258888.top/Article/details/gtdznfscvb.html

string.find(s, "%d+")
来源：http://dali.sxryk.cn/Article/details/gtxmytbrbn.html

[T40] Lua：元表
来源：http://dali.sufxvd.cn/Article/details/gtdjychxyg.html

setmetatable({}, { __index = base })
来源：http://dali.xuetiantiany.cn/Article/details/gtfrfrnxga.html

[T41] Perl：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtvwaqcrtn.html

print "Hello\n";
来源：http://dali.ehwqpu.com/Article/details/gtbyxwhdaf.html

[T42] Perl：变量类型
来源：http://dali.yangfankeji.com/Article/details/gtctixhshu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shangyingyoupin.top/Article/details/gtfrjzujvi.html

[T43] Perl：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gtmsmmbfyz.html

"值: $a"
来源：http://dali.bjfxy.top/Article/details/gtbdnwiuid.html

[T44] Perl：条件
来源：http://dali.hnqzz.top/Article/details/gtspvohhvi.html

if ($a > 0) { print "正"; }
来源：http://dali.xylfe.cn/Article/details/gtypzdthes.html

[T45] Perl：数组遍历
来源：http://dali.sweek.top/Article/details/gtyabgsvbf.html

for my $x (@arr) { print $x; }
来源：http://dali.tian-w.cn/Article/details/gtoqiyqkzg.html

[T46] Perl：哈希操作
来源：http://dali.snrcjt.cn/Article/details/gtuzhbears.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinqigfzy.top/Article/details/gthymrmgrz.html

[T47] Perl：正则捕获
来源：http://dali.pycfn.com/Article/details/gtkkyouiai.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sysykeji.top/Article/details/gtfxgrzqof.html

[T48] Perl：正则替换
来源：http://dali.daria6918.cn/Article/details/gtamzwaqlj.html

$s =~ s/old/new/g;
来源：http://dali.chenlongwang.top/Article/details/gtupyrzxec.html

[T49] Perl：函数
来源：http://dali.meibo888.top/Article/details/gtbaetbjnq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtbzoizprr.html

[T50] Perl：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtjmexmuex.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.andypj.xyz/Article/details/gtzxzcnlmc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ivvv.top/Article/details/gtqacnufqr.html

[T51] Scala：Hello World
来源：http://dali.sweek.top/Article/details/gtoimdmgxi.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtkexoxeqk.html

[T52] Scala：变量
来源：http://dali.feifeiyinyue.top/Article/details/gtqfkgjmju.html

val a = 1;  var b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtfoxomqne.html

[T53] Scala：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtvbygcdow.html

s"值: $b"
来源：http://dali.birdmap.top/Article/details/gtijmiagen.html

[T54] Scala：集合映射
来源：http://dali.cashguo.top/Article/details/gtsavsdwbv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nwbrower.top/Article/details/gtkytlooto.html

[T55] Scala：集合过滤
来源：http://dali.cashguo.top/Article/details/gtpeqlmfok.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pycfn.com/Article/details/gtiitzkacu.html

[T56] Scala：样例类
来源：http://dali.jqgufenzy.top/Article/details/gtnnqbddjh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gtmwbeqker.html

[T57] Scala：模式匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtgmwcobko.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cashguo.top/Article/details/gtwtnyyhju.html

[T58] Scala：函数定义
来源：http://dali.cdnleiting.top/Article/details/gtedbevxhz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigfzy.top/Article/details/gtrgfmmspc.html

[T59] Scala：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpvojqgn.html

for (i <- 1 to 10) println(i)
来源：http://dali.nanxinkj.top/Article/details/gtypyvgvvg.html

[T60] Scala：折叠
来源：http://dali.cashguo.top/Article/details/gttphjvbvo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenjidiqi.icu/Article/details/gtjnjbxgyg.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtapxtsisd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shzxlz.cn/Article/details/gtriaikgmu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtqlhvqmiy.html

[U01] Py：创建虚拟环境
来源：http://dali.yonumen.top/Article/details/gtrnphqmmu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ivvv.top/Article/details/gthlttzcax.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj20258888.top/Article/details/gtvtqjmmli.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sufxvd.cn/Article/details/gtedqyoylr.html

[U03] Py：加载 .env 配置
来源：http://dali.jiagoushi.top/Article/details/gtktgqxknp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xylfe.cn/Article/details/gtieycwgou.html

[U04] Py：变量调试打印
来源：http://dali.zhiwuduotai.top/Article/details/gttfbsrlxq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tian-w.cn/Article/details/gtycvnkvcr.html

[U05] Py：列表去重且保序
来源：http://dali.ppjwa.cn/Article/details/gtrpcqghgj.html

list(dict.fromkeys(arr))
来源：http://dali.cheryme.top/Article/details/gtfaiztntd.html

[U06] Py：合并两个字典
来源：http://dali.shzxlz.cn/Article/details/gtwymmfmaj.html

{**a, **b}
来源：http://dali.ivvv.top/Article/details/gtmfjwvsat.html

[U07] Py：反转字典键值
来源：http://dali.hongshengwenyu.top/Article/details/gtfqcpvbdz.html

{v: k for k, v in d.items()}
来源：http://dali.quarkkingdee.top/Article/details/gtuceocipf.html

[U08] Py：展平二维列表
来源：http://dali.meibo888.top/Article/details/gthyssbmrg.html

[y for x in nested for y in x]
来源：http://dali.zhixingplan.top/Article/details/gtaayytsiz.html

[U09] Py：字典取最大值的键
来源：http://dali.sxryk.cn/Article/details/gtxoyrgzen.html

max(d, key=d.get)
来源：http://dali.ehwqpu.com/Article/details/gtobvboawz.html

[U10] Py：按值排序字典
来源：http://dali.yueranfly.top/Article/details/gtvoddinoi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigfzy.top/Article/details/gtjziytsom.html

[U11] Py：生成器表达式
来源：http://dali.sufxvd.cn/Article/details/gttmfmrpkt.html

(x * 2 for x in arr)
来源：http://dali.sufxvd.cn/Article/details/gtnjaxuxpl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.9152youxi.cn/Article/details/gtdatcpoiq.html

Counter(arr).most_common(3)
来源：http://dali.nwbrower.top/Article/details/gtdgqlsciz.html

[U13] Py：固定长度队列
来源：http://dali.gogol.net.cn/Article/details/gtzoyehsrl.html

deque(maxlen=10)
来源：http://dali.9152youxi.cn/Article/details/gtcymforal.html

[U14] Py：分组收集到列表
来源：http://dali.yvedp.cn/Article/details/gtrmnsijax.html

defaultdict(list)
来源：http://dali.quarkkingdee.top/Article/details/gtxvezomkv.html

[U15] Py：高精度计时
来源：http://dali.shzxlz.cn/Article/details/gtmzixnypj.html

t = time.perf_counter()
来源：http://dali.bjfxy.top/Article/details/gtnbtlzlmp.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwccvcahg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.havefunace.top/Article/details/gtldyzujca.html

[U17] Py：初始化日志
来源：http://dali.chenzaomai.com/Article/details/gttzlvarae.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daxiang520.top/Article/details/gtfwxowwwz.html

[U18] Py：预编译正则
来源：http://dali.hongshengwenyu.top/Article/details/gttjwjgrbh.html

pat = re.compile(r"\d+")
来源：http://dali.yvedp.cn/Article/details/gthtmajofv.html

[U19] Py：正则替换带回调
来源：http://dali.shuidangran.top/Article/details/gtthmmmfdp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nwbrower.top/Article/details/gtknaghldy.html

[U20] Py：缓存函数结果
来源：http://dali.jinqigufen.top/Article/details/gtxzvltpvr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhengqikj.top/Article/details/gtjcoonbzf.html

[U21] Py：自定义上下文管理器
来源：http://dali.guowangkeji.top/Article/details/gtiiqzlmkj.html

@contextlib.contextmanager
来源：http://dali.c1oappe.top/Article/details/gthngubnzd.html

[U22] Py：矩阵转置
来源：http://dali.chenjidiqi.icu/Article/details/gtrwkvhpku.html

list(zip(*m))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrcunsfy.html

[U23] Py：分块读取大文件
来源：http://dali.zdqjudy.top/Article/details/gtvhlmdbni.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yonumen.top/Article/details/gtzuulqonp.html

[U24] Py：路径操作
来源：http://dali.hnxiangtu.top/Article/details/gtyiuwhbsn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gtgzhkvmhl.html

[U25] Py：CSV 按字典读
来源：http://dali.pengpengdd.cyou/Article/details/gtymapzpum.html

csv.DictReader(f)
来源：http://dali.havefunace.top/Article/details/gtwrlstccb.html

[U26] Py：并发下载
来源：http://dali.sxryk.cn/Article/details/gtubnwottn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.meibo888.top/Article/details/gtnccfucrx.html

[U27] Py：异步 HTTP
来源：http://dali.hnxiangtu.top/Article/details/gtxcfjpyhu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthseubalk.html

[U28] Py：类型别名
来源：http://dali.dianchejie.cn/Article/details/gtpimrvdst.html

UserId = int
来源：http://dali.svipenyu.cn/Article/details/gtwosdlnre.html

[U29] Py：属性校验
来源：http://dali.9152youxi.cn/Article/details/gtqtjsjjmo.html

@property 与 @x.setter 配合
来源：http://dali.hammf.cn/Article/details/gtpxhpjhtc.html

[U30] Py：数据类
来源：http://dali.ehwqpu.com/Article/details/gttbfevsyo.html

@dataclass(slots=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjcnuipl.html

[U31] Py：单测
来源：http://dali.xylfe.cn/Article/details/gtcipudqxb.html

python -m pytest -q
来源：http://dali.zdqjudy.top/Article/details/gtoujwxpxm.html

[U32] Py：代码格式化
来源：http://dali.vqdsnc.cn/Article/details/gtpiogdimr.html

ruff format . && ruff check --fix .
来源：http://dali.nanxuanxn.top/Article/details/gtvgtbtvwe.html

[U33] Py：打包发布
来源：http://dali.zhengqikj.top/Article/details/gtdjdwolbb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.fengsongda.top/Article/details/gtkjnipgrr.html

[U34] Py：判断编码
来源：http://dali.nanxinkj.top/Article/details/gtowlbdcqi.html

chardet.detect(raw)
来源：http://dali.pycfn.com/Article/details/gtofpotcns.html

[U35] Py：发送邮件
来源：http://dali.fzhhl.top/Article/details/gthldrdgcc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinyuanbaomall.cn/Article/details/gticlvzode.html

[U36] Py：定时任务
来源：http://dali.dashuyun.cn/Article/details/gttbpcmtoy.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinghuilouyu.cn/Article/details/gtonnjgatn.html

[U37] Py：读写 Excel
来源：http://dali.0kj1m.cn/Article/details/gtwhiqytbw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinqigfzy.top/Article/details/gtxgiqwboj.html

[U38] Py：获取脚本所在目录
来源：http://dali.quarkkingdee.top/Article/details/gtvxgneunp.html

Path(__file__).resolve().parent
来源：http://dali.tanke756.top/Article/details/gtpifvoinj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gtrfpceduw.html

sys.stdout.isatty()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtrplkpi.html

[U40] Py：打印到标准错误
来源：http://dali.havefunace.top/Article/details/gtwjdyzmbl.html

print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gtulrjchwi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.wangshuangyany.cn/Article/details/gttojdbplf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.pycfn.com/Article/details/gtstbtmzgm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jianghu66.top/Article/details/gtvzwpjdvo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.316326.xyz/Article/details/gtlfqznddm.html

[U43] PHP：声明命名空间
来源：http://dali.aibaodan.cn/Article/details/gtzgyqngvl.html

namespace App\Http;
来源：http://dali.zhoulong.xyz/Article/details/gtuuyaxbne.html

[U44] PHP：开启严格类型
来源：http://dali.jiagoushi.top/Article/details/gtszgwhvky.html

declare(strict_types=1);
来源：http://dali.shzxlz.cn/Article/details/gtgjxvxorh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhoulong.xyz/Article/details/gtruikmkfi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtnmmaibjr.html

[U46] PHP：可空类型
来源：http://dali.yueranfly.top/Article/details/gtybmjwzjc.html

?string $name = null
来源：http://dali.c1oappe.top/Article/details/gtvrrjgqjg.html

[U47] PHP：联合类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdjmnvfi.html

int|string $id
来源：http://dali.jinqigufen.top/Article/details/gtcnwgyxvi.html

[U48] PHP：纯枚举
来源：http://dali.redwolf501.top/Article/details/gtafuzozlq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nanxinkj.top/Article/details/gtnlprvegs.html

[U49] PHP：只读属性
来源：http://dali.ivvv.top/Article/details/gtslhtsrpq.html

public readonly string $name
来源：http://dali.nanxinkj.top/Article/details/gtpgxmnsoz.html

[U50] PHP：构造器属性提升
来源：http://dali.chenzaomai.com/Article/details/gtdhvbfyzy.html

public function __construct(private int $id) {}
来源：http://dali.ehwqpu.com/Article/details/gtbigtzpbu.html

[U51] PHP：数组解构
来源：http://dali.xuetiantiany.cn/Article/details/gtjbvenjfm.html

[$a, $b] = $arr;
来源：http://dali.chenlongwang.top/Article/details/gtmuyhifpx.html

[U52] PHP：箭头函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthysotsw.html

$double = fn($x) => $x * 2;
来源：http://dali.gaohongyu789.top/Article/details/gttorgrqsd.html

[U53] PHP：空合并运算符
来源：http://dali.nanxuanxn.top/Article/details/gtzawqewix.html

$v = $a ?? $b ?? "default";
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfsraoso.html

[U54] PHP：空安全调用
来源：http://dali.316326.xyz/Article/details/gtmrooomae.html

$obj?->method()
来源：http://dali.aibaodan.cn/Article/details/gtrdvespuk.html

[U55] PHP：match 表达式
来源：http://dali.jianghu66.top/Article/details/gtedspkixd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinghuilouyu.cn/Article/details/gtpyjarixu.html

[U56] PHP：命名参数
来源：http://dali.jqgfzy.top/Article/details/gtxfsfpcia.html

f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gtkfuebhzk.html

[U57] PHP：字符串插值
来源：http://dali.andypj.xyz/Article/details/gtgzmblpxh.html

"值: {$a}"
来源：http://dali.ppjwa.cn/Article/details/gtgbwqxvuf.html

[U58] PHP：数组三件套
来源：http://dali.zdqjudy.top/Article/details/gtgflquprn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.aizwys.cn/Article/details/gthprexutb.html

[U59] PHP：自定义排序
来源：http://dali.yonumen.top/Article/details/gtnffbswne.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gtogmssddi.html

[U60] PHP：JSON 编解码
来源：http://dali.jinqigufen.top/Article/details/gtxujcemka.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinqigfzy.top/Article/details/gtnvumjwum.html

[U61] PHP：正则
来源：http://dali.zhongyouzk.top/Article/details/gtgakqldwu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyooihuf.html

[U62] PHP：日期对象
来源：http://dali.yj202588.top/Article/details/gtoaauhhci.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tianlin.xyz/Article/details/gtumwqhaza.html

[U63] PHP：文件读写
来源：http://dali.sysykeji.top/Article/details/gtumucjrmc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.meibo888.top/Article/details/gtkxlustya.html

[U64] PHP：目录遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxcqmdgo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sxryk.cn/Article/details/gtmlmlczmy.html

[U65] PHP：会话
来源：http://dali.shangyingyoupin.top/Article/details/gtzxkicgnb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gteqwlebxr.html

[U66] PHP：设置 Cookie
来源：http://dali.yuanzhike.top/Article/details/gteiiqrkde.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hongshengwenyu.top/Article/details/gthcgktjsk.html

[U67] PHP：处理文件上传
来源：http://dali.snrcjt.cn/Article/details/gtxyrvhlnn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.guannengcc.top/Article/details/gtogxgosqv.html

[U68] PHP：PDO 连接
来源：http://dali.yuanzhike.top/Article/details/gtliulusfv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jlsjyb.cn/Article/details/gtxzresvxd.html

[U69] PHP：PDO 预处理
来源：http://dali.cucudq.cn/Article/details/gtvosrdhvt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yvedp.cn/Article/details/gthjeixzio.html

[U70] PHP：PDO 事务
来源：http://dali.jqgfzy.top/Article/details/gtlhrsvnsd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ivvv.top/Article/details/gtpeayrtyb.html


<!-- 参考信息 -->