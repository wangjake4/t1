代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.chenlongwang.top/Article/details/gtzitwchzw.html

[S49] C++：写文件
来源：http://dali.jinqigufen.top/Article/details/gtnobzkwew.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gtllxzceax.html

[S50] C++：格式化数字
来源：http://dali.yangfankeji.com/Article/details/gtnhhqsdmb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtowhjyiud.html

[S51] C++：显式类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gtavdyrgok.html

static_cast<double>(a) / b
来源：http://dali.yueranfly.top/Article/details/gtoazuyxxo.html

[S52] C++：const 与 noexcept
来源：http://dali.gaohongyu789.top/Article/details/gttkbubbzl.html

int size() const noexcept { return n_; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjfrwfpdk.html

[S53] C++：移动语义
来源：http://dali.zhiwuduotai.top/Article/details/gtofxhxwfu.html

std::vector<int> w = std::move(v);
来源：http://dali.daria6918.cn/Article/details/gtohrsrswt.html

[S54] C++：异常处理
来源：http://dali.fzhhl.top/Article/details/gtvzngcfsg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yvedp.cn/Article/details/gtzsjfssxi.html

[S55] C++：结构化绑定
来源：http://dali.quarkkingdee.top/Article/details/gtmnofztrd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jianghu66.top/Article/details/gtnhlgaqlq.html

[S56] C++：optional
来源：http://dali.iojbl.cn/Article/details/gtjzpbsrhq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tianlin.xyz/Article/details/gtbvhhwret.html

[S57] C++：编译期常量
来源：http://dali.bjfxy.top/Article/details/gtdlpmpucw.html

constexpr int N = 10;
来源：http://dali.jianghu66.top/Article/details/gtoikepuhc.html

[S58] C++：命名空间
来源：http://dali.yanxiufei.cn/Article/details/gtxbvcygob.html

namespace ns { int f() { return 1; } }
来源：http://dali.sysykeji.top/Article/details/gthbyuwzqi.html

[S59] C++：静态断言
来源：http://dali.xylfe.cn/Article/details/gtyrecxpxa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jiagoushi.top/Article/details/gtuiqgilfl.html

[S60] C++：遍历并删除元素
来源：http://dali.daria6918.cn/Article/details/gtzcrlolyv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hywenlv.cn/Article/details/gtxplapggr.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtosfysbpj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pengpengdd.cyou/Article/details/gthlyszcwn.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtmqgcdsmr.html

[T01] Kotlin：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtwxlhdest.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gtyjnzkfzs.html

[T02] Kotlin：变量
来源：http://dali.jyoumei.cn/Article/details/gtiqbumxnd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigufen.top/Article/details/gtpouqucik.html

[T03] Kotlin：字符串模板
来源：http://dali.guowangkeji.top/Article/details/gtizazrevi.html

"值: $b"
来源：http://dali.xziqi.cn/Article/details/gtnzoadmic.html

[T04] Kotlin：空安全
来源：http://dali.guannengcc.top/Article/details/gthflkkvyf.html

val n: String? = null;  n?.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbiovxqvy.html

[T05] Kotlin：when 表达式
来源：http://dali.svipenyu.cn/Article/details/gtrrnwzjtu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sweek.top/Article/details/gtczlqyujz.html

[T06] Kotlin：集合映射
来源：http://dali.shzxlz.cn/Article/details/gtfhxsakei.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cdnleiting.top/Article/details/gtozinfqvy.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gttroqigsv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zdqjudy.top/Article/details/gtneefxnst.html

[T08] Kotlin：数据类
来源：http://dali.tianlin.xyz/Article/details/gtrhgrorql.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhqfjyqo.html

[T09] Kotlin：扩展函数
来源：http://dali.gaohongyu789.top/Article/details/gtjthemzbb.html

fun String.exclaim() = this + "!"
来源：http://dali.haohaochexian.top/Article/details/gtusubjdjn.html

[T10] Kotlin：默认参数
来源：http://dali.xziqi.cn/Article/details/gtkjnwexsk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.andypj.xyz/Article/details/gtatjepxwn.html

[T11] Kotlin：协程
来源：http://dali.jinqigufen.top/Article/details/gtiizszyxc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgufenzy.top/Article/details/gtuexaotkw.html

[T12] Kotlin：解构声明
来源：http://dali.jqgufenzy.top/Article/details/gtehyvmazn.html

val (a, b) = Pair(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gthyvhwvhj.html

[T13] Kotlin：只读 Map
来源：http://dali.aibaodan.cn/Article/details/gtbcyfxgrd.html

val m = mapOf("a" to 1)
来源：http://dali.kuanghao11.cn/Article/details/gtjgyazzsl.html

[T14] Kotlin：循环
来源：http://dali.xylfe.cn/Article/details/gtbprezebr.html

for (i in 1..10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtkkfoemdl.html

[T15] Kotlin：接口
来源：http://dali.gzhubu.top/Article/details/gtcgmueqil.html

interface Shape { fun area(): Double }
来源：http://dali.yueranfly.top/Article/details/gtuarpqudn.html

[T16] Swift：Hello World
来源：http://dali.hammf.cn/Article/details/gtqmhtdabx.html

print("Hello")
来源：http://dali.iojbl.cn/Article/details/gtkoyvpbdd.html

[T17] Swift：变量与常量
来源：http://dali.hammf.cn/Article/details/gtgkwspqbl.html

var a = 1;  let b = 2
来源：http://dali.daxiang520.top/Article/details/gtfiqkdelg.html

[T18] Swift：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtgzxmvyau.html

"值: \(b)"
来源：http://dali.feifeiyinyue.top/Article/details/gtkouwqvmb.html

[T19] Swift：可选绑定
来源：http://dali.aizwys.cn/Article/details/gtbneblwdq.html

if let n = opt { print(n) }
来源：http://dali.havefunace.top/Article/details/gtuswyxjar.html

[T20] Swift：数组操作
来源：http://dali.hongshengwenyu.top/Article/details/gtfwxdhbhy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.tianlin.xyz/Article/details/gtmvykxoif.html

[T21] Swift：遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtmnlfnsmp.html

for x in a { print(x) }
来源：http://dali.hywenlv.cn/Article/details/gteriekesu.html

[T22] Swift：字典
来源：http://dali.shzxlz.cn/Article/details/gtxabzydqa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhixingplan.top/Article/details/gtppzbjsxp.html

[T23] Swift：函数
来源：http://dali.c1oappe.top/Article/details/gtjygvoueq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhongyouzk.top/Article/details/gtsijuxfhk.html

[T24] Swift：闭包
来源：http://dali.hysaishi.cn/Article/details/gtgywwgomk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtztbagsvw.html

[T25] Swift：结构体
来源：http://dali.cqqwz.cn/Article/details/gtpcckktmd.html

struct P { var x: Int }
来源：http://dali.birdmap.top/Article/details/gttsrjlbuq.html

[T26] Swift：类与重写
来源：http://dali.fengsongda.top/Article/details/gtabqppjpe.html

class A: Base { override func f() {} }
来源：http://dali.yj20258.top/Article/details/gtxgzymtvd.html

[T27] Swift：错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gtzaruvwew.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258888.top/Article/details/gtewgvmzef.html

[T28] Swift：枚举
来源：http://dali.quarkkingdee.top/Article/details/gtxdnjgugx.html

enum Color { case red, green }
来源：http://dali.jinqigufen.top/Article/details/gtbchclkdj.html

[T29] Swift：guard 提前返回
来源：http://dali.0kj1m.cn/Article/details/gtgnttwiri.html

guard let x = opt else { return }
来源：http://dali.guowangkeji.top/Article/details/gthbfixuoc.html

[T30] Swift：协议
来源：http://dali.dashuyun.cn/Article/details/gteyzeyflj.html

protocol Shape { func area() -> Double }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqybfqex.html

[T31] Lua：Hello World
来源：http://dali.c1oappe.top/Article/details/gtybsqaqmc.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gtcertknhn.html

[T32] Lua：局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gtrhjxzkvq.html

local a = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtluevcoec.html

[T33] Lua：表（数组）
来源：http://dali.daria6918.cn/Article/details/gtvpavyqof.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.havefunace.top/Article/details/gtlkpvtfng.html

[T34] Lua：遍历表
来源：http://dali.hysaishi.cn/Article/details/gtvbersuym.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ybcxt.top/Article/details/gtwtmaubzq.html

[T35] Lua：字典表
来源：http://dali.birdmap.top/Article/details/gtqlpxbyjx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xuanzx.com/Article/details/gtkfiypbts.html

[T36] Lua：函数
来源：http://dali.fengsongda.top/Article/details/gtgoenhhmv.html

function add(a, b) return a + b end
来源：http://dali.zhixingplan.top/Article/details/gtydrqbfel.html

[T37] Lua：字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gtbyhpzlwv.html

"a" .. "b"
来源：http://dali.xuanzx.com/Article/details/gtfkwqylgk.html

[T38] Lua：条件
来源：http://dali.cqqwz.cn/Article/details/gtdlyankdh.html

if x > 0 then print("正") end
来源：http://dali.hysaishi.cn/Article/details/gtnfrbatco.html

[T39] Lua：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gtvionorjk.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxzrqjtl.html

[T40] Lua：元表
来源：http://dali.yuxming.cn/Article/details/gtshitdrig.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gtwuvlmass.html

[T41] Perl：Hello World
来源：http://dali.wangdashe.top/Article/details/gttfonnvip.html

print "Hello\n";
来源：http://dali.quarkkingdee.top/Article/details/gticexqmxs.html

[T42] Perl：变量类型
来源：http://dali.jyoumei.cn/Article/details/gtbtnznrrk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hysaishi.cn/Article/details/gttbzalzrv.html

[T43] Perl：字符串插值
来源：http://dali.havefunace.top/Article/details/gtvrjdilvd.html

"值: $a"
来源：http://dali.nanxuanxn.top/Article/details/gteitwbslx.html

[T44] Perl：条件
来源：http://dali.zhixingplan.top/Article/details/gtyliqncza.html

if ($a > 0) { print "正"; }
来源：http://dali.zycfv.cn/Article/details/gtjlinapjh.html

[T45] Perl：数组遍历
来源：http://dali.chenzaomai.com/Article/details/gtuqfxdxfn.html

for my $x (@arr) { print $x; }
来源：http://dali.xuanzx.com/Article/details/gtsoarlrab.html

[T46] Perl：哈希操作
来源：http://dali.daxiang520.top/Article/details/gtyewcuwnh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gtkfmmnaek.html

[T47] Perl：正则捕获
来源：http://dali.hywenlv.cn/Article/details/gtwpfpifty.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hysaishi.cn/Article/details/gtfrnfczfl.html

[T48] Perl：正则替换
来源：http://dali.316326.xyz/Article/details/gtumkceryu.html

$s =~ s/old/new/g;
来源：http://dali.yj202588.top/Article/details/gtuguunsso.html

[T49] Perl：函数
来源：http://dali.jinqigfzy.top/Article/details/gttjyqstgs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtusclwstk.html

[T50] Perl：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtyovjbbbu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gogol.net.cn/Article/details/gtlrekiawe.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.haohaochexian.top/Article/details/gtfkhvogbf.html

[T51] Scala：Hello World
来源：http://dali.aibaodan.cn/Article/details/gthmuyytah.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtgmivkxdv.html

[T52] Scala：变量
来源：http://dali.pengpengdd.cyou/Article/details/gtvaotxome.html

val a = 1;  var b = 2
来源：http://dali.yangfankeji.com/Article/details/gtfroenigt.html

[T53] Scala：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtlfmuyetc.html

s"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtkaxzkukp.html

[T54] Scala：集合映射
来源：http://dali.sweek.top/Article/details/gtvmgrnxos.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yonumen.top/Article/details/gtwfzpamsq.html

[T55] Scala：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gtvdctqiws.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.c1oappe.top/Article/details/gtjlfenpml.html

[T56] Scala：样例类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgatbdxzb.html

case class User(name: String, age: Int)
来源：http://dali.snrcjt.cn/Article/details/gtfraynmoc.html

[T57] Scala：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gtfuhxraut.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhiwuduotai.top/Article/details/gtmvfsddeu.html

[T58] Scala：函数定义
来源：http://dali.chenlongwang.top/Article/details/gttqricosv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yanxiufei.cn/Article/details/gtpxnzxcul.html

[T59] Scala：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gthilcecvd.html

for (i <- 1 to 10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gtzhrcsqgb.html

[T60] Scala：折叠
来源：http://dali.xylfe.cn/Article/details/gtbxfvzwpx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hysaishi.cn/Article/details/gtlhbrekzf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtanlieeuv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.bjfxy.top/Article/details/gtrgqtpftk.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtupehqdzh.html

[U01] Py：创建虚拟环境
来源：http://dali.aibaodan.cn/Article/details/gtirduivzd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tanke756.top/Article/details/gtwnjllrad.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yangfankeji.com/Article/details/gttygnecfy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jianghu66.top/Article/details/gtwvgmeznf.html

[U03] Py：加载 .env 配置
来源：http://dali.gogol.net.cn/Article/details/gtmfirocgv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.dianchejie.cn/Article/details/gtylnylfnk.html

[U04] Py：变量调试打印
来源：http://dali.feifeiyinyue.top/Article/details/gtpworbefy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.fzhhl.top/Article/details/gtepeeuwvj.html

[U05] Py：列表去重且保序
来源：http://dali.pycfn.com/Article/details/gtdwmsfrsr.html

list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gtuxrcvejg.html

[U06] Py：合并两个字典
来源：http://dali.c1oappe.top/Article/details/gtzrkguqge.html

{**a, **b}
来源：http://dali.tanke756.top/Article/details/gtqdzshsww.html

[U07] Py：反转字典键值
来源：http://dali.jyoumei.cn/Article/details/gtudkdbffx.html

{v: k for k, v in d.items()}
来源：http://dali.chenjidiqi.icu/Article/details/gtxnvjqhhp.html

[U08] Py：展平二维列表
来源：http://dali.hywenlv.cn/Article/details/gtytkwxflt.html

[y for x in nested for y in x]
来源：http://dali.smart0.xyz/Article/details/gtpyavxoaj.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gtswfrqwrc.html

max(d, key=d.get)
来源：http://dali.meibo888.top/Article/details/gtqwgikpdm.html

[U10] Py：按值排序字典
来源：http://dali.9152youxi.cn/Article/details/gtgwahqcld.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gotoacloud.top/Article/details/gtptvxsdsf.html

[U11] Py：生成器表达式
来源：http://dali.hammf.cn/Article/details/gtrlrlcnvq.html

(x * 2 for x in arr)
来源：http://dali.xziqi.cn/Article/details/gtkrunyios.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pycfn.com/Article/details/gtbmazflen.html

Counter(arr).most_common(3)
来源：http://dali.dashuyun.cn/Article/details/gtcrejumoa.html

[U13] Py：固定长度队列
来源：http://dali.hysaishi.cn/Article/details/gtjnzmsauv.html

deque(maxlen=10)
来源：http://dali.yvedp.cn/Article/details/gtcylkuqmy.html

[U14] Py：分组收集到列表
来源：http://dali.yuxming.cn/Article/details/gtowxoquis.html

defaultdict(list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqodnhqr.html

[U15] Py：高精度计时
来源：http://dali.zhixingplan.top/Article/details/gtlmozfuqr.html

t = time.perf_counter()
来源：http://dali.hysaishi.cn/Article/details/gtxhzapvmx.html

[U16] Py：命令行参数解析
来源：http://dali.shzxlz.cn/Article/details/gtjntvalpv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jqgfzy.top/Article/details/gtyzljoler.html

[U17] Py：初始化日志
来源：http://dali.hongshengwenyu.top/Article/details/gthukabipi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.dashuyun.cn/Article/details/gtauicueoc.html

[U18] Py：预编译正则
来源：http://dali.316326.xyz/Article/details/gtydthpcjc.html

pat = re.compile(r"\d+")
来源：http://dali.gzhubu.top/Article/details/gtdsfpmais.html

[U19] Py：正则替换带回调
来源：http://dali.fzhhl.top/Article/details/gtxezgklin.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hywenlv.cn/Article/details/gtzpehbdtc.html

[U20] Py：缓存函数结果
来源：http://dali.jyoumei.cn/Article/details/gtpqwqvosx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ybcxt.top/Article/details/gtgqgwdshd.html

[U21] Py：自定义上下文管理器
来源：http://dali.guannengcc.top/Article/details/gtdqmpnklf.html

@contextlib.contextmanager
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyigmadeo.html

[U22] Py：矩阵转置
来源：http://dali.quarkkingdee.top/Article/details/gtbbombwaj.html

list(zip(*m))
来源：http://dali.zhiwuduotai.top/Article/details/gtirzyemad.html

[U23] Py：分块读取大文件
来源：http://dali.vqdsnc.cn/Article/details/gtheagwmiu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.quarkkingdee.top/Article/details/gtgvvlarhq.html

[U24] Py：路径操作
来源：http://dali.gogol.net.cn/Article/details/gtrexvpiry.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhkjwvog.html

[U25] Py：CSV 按字典读
来源：http://dali.wangshuangyany.cn/Article/details/gtmlfenqbn.html

csv.DictReader(f)
来源：http://dali.wangshuangyany.cn/Article/details/gtcomboofj.html

[U26] Py：并发下载
来源：http://dali.yj20258.top/Article/details/gtmplcylys.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gogol.net.cn/Article/details/gtpwslhvib.html

[U27] Py：异步 HTTP
来源：http://dali.nanxuanxn.top/Article/details/gtlvaurnct.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenjidiqi.icu/Article/details/gtzyvoopfq.html

[U28] Py：类型别名
来源：http://dali.snrcjt.cn/Article/details/gtcsnuxoas.html

UserId = int
来源：http://dali.daxiang520.top/Article/details/gtigjnflpa.html

[U29] Py：属性校验
来源：http://dali.yj20258.top/Article/details/gtctmcberq.html

@property 与 @x.setter 配合
来源：http://dali.jqgufenzy.top/Article/details/gtnprtfwvc.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gtimlddngr.html

@dataclass(slots=True)
来源：http://dali.redwolf501.top/Article/details/gtvtcryzzv.html

[U31] Py：单测
来源：http://dali.yuxming.cn/Article/details/gtgpcfltwd.html

python -m pytest -q
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgsjkfjti.html

[U32] Py：代码格式化
来源：http://dali.jqgfzy.top/Article/details/gtuywevaui.html

ruff format . && ruff check --fix .
来源：http://dali.shanyushiyangtech.top/Article/details/gtgngydcjz.html

[U33] Py：打包发布
来源：http://dali.9152youxi.cn/Article/details/gteeejcmgm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.dashuyun.cn/Article/details/gtnzyhnpvl.html

[U34] Py：判断编码
来源：http://dali.gogol.net.cn/Article/details/gtfugwnqfq.html

chardet.detect(raw)
来源：http://dali.jlsjyb.cn/Article/details/gtgvqowmxt.html

[U35] Py：发送邮件
来源：http://dali.aibaodan.cn/Article/details/gtqrrhsggi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpdmmmth.html

[U36] Py：定时任务
来源：http://dali.fengsongda.top/Article/details/gtgjqhgkki.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhengqikj.top/Article/details/gtbainhgio.html

[U37] Py：读写 Excel
来源：http://dali.svipenyu.cn/Article/details/gthjaepwym.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hammf.cn/Article/details/gtacvnjdzw.html

[U38] Py：获取脚本所在目录
来源：http://dali.ppjwa.cn/Article/details/gtkiupmqeb.html

Path(__file__).resolve().parent
来源：http://dali.nanxuanxn.top/Article/details/gtkbucusoq.html

[U39] Py：判断是否在交互环境
来源：http://dali.pycfn.com/Article/details/gtatjhxjak.html

sys.stdout.isatty()
来源：http://dali.chenjidiqi.icu/Article/details/gttbbnpnhu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gtxfcigiua.html

print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gtftqkyyat.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ybcxt.top/Article/details/gtrcrryttj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sxryk.cn/Article/details/gthosngciu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ppjwa.cn/Article/details/gttoeizpdo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.kuanghao11.cn/Article/details/gtsqljafra.html

[U43] PHP：声明命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gtymrcdiir.html

namespace App\Http;
来源：http://dali.cucudq.cn/Article/details/gttcnmnlpa.html

[U44] PHP：开启严格类型
来源：http://dali.zhengqikj.top/Article/details/gttoasnzvs.html

declare(strict_types=1);
来源：http://dali.gotoacloud.top/Article/details/gtvgcdurtu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.0kj1m.cn/Article/details/gtxmcpaziv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtbiucmafv.html

[U46] PHP：可空类型
来源：http://dali.nanxinkj.top/Article/details/gtapjtamfu.html

?string $name = null
来源：http://dali.yj202588.top/Article/details/gtsethrlzp.html

[U47] PHP：联合类型
来源：http://dali.redwolf501.top/Article/details/gtuhjpyjzm.html

int|string $id
来源：http://dali.jinqigufen.top/Article/details/gthjrpsbii.html

[U48] PHP：纯枚举
来源：http://dali.hfpthk.cn/Article/details/gtkdnfrgku.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtamjozcyh.html

[U49] PHP：只读属性
来源：http://dali.zycfv.cn/Article/details/gtaluiticq.html

public readonly string $name
来源：http://dali.sysykeji.top/Article/details/gtqsgflcxu.html

[U50] PHP：构造器属性提升
来源：http://dali.shzxlz.cn/Article/details/gtcmgeuvme.html

public function __construct(private int $id) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmohnmdjs.html

[U51] PHP：数组解构
来源：http://dali.sxryk.cn/Article/details/gtvxbivpbo.html

[$a, $b] = $arr;
来源：http://dali.xuanzx.com/Article/details/gtygllcpnf.html

[U52] PHP：箭头函数
来源：http://dali.zhiwuduotai.top/Article/details/gtbjldniho.html

$double = fn($x) => $x * 2;
来源：http://dali.mhx1999.top/Article/details/gtwwvjvros.html

[U53] PHP：空合并运算符
来源：http://dali.cucudq.cn/Article/details/gtkeruuqsr.html

$v = $a ?? $b ?? "default";
来源：http://dali.hammf.cn/Article/details/gtgdvwwbax.html

[U54] PHP：空安全调用
来源：http://dali.c1oappe.top/Article/details/gtnecqjjup.html

$obj?->method()
来源：http://dali.nwbrower.top/Article/details/gtuyoistbr.html

[U55] PHP：match 表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrovtdyj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jianghu66.top/Article/details/gtqioxdzjp.html

[U56] PHP：命名参数
来源：http://dali.xziqi.cn/Article/details/gtwkrhsgwi.html

f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gtwgwsxztx.html

[U57] PHP：字符串插值
来源：http://dali.cheryme.top/Article/details/gtqitnrqfk.html

"值: {$a}"
来源：http://dali.svipenyu.cn/Article/details/gtzkaymdlm.html

[U58] PHP：数组三件套
来源：http://dali.hongshengwenyu.top/Article/details/gtqcnjslrh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yuxming.cn/Article/details/gtwcjmjrjt.html

[U59] PHP：自定义排序
来源：http://dali.zhengqikj.top/Article/details/gtzxmhwkom.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpviaslb.html

[U60] PHP：JSON 编解码
来源：http://dali.wangdashe.top/Article/details/gtcuabjchb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cheryme.top/Article/details/gtakrmpwpw.html

[U61] PHP：正则
来源：http://dali.ehwqpu.com/Article/details/gtemmqimse.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gttpxignou.html

[U62] PHP：日期对象
来源：http://dali.birdmap.top/Article/details/gtjbazvbgz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.dashuyun.cn/Article/details/gteyxhchap.html

[U63] PHP：文件读写
来源：http://dali.yj20258.top/Article/details/gtcojgpuzo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.birdmap.top/Article/details/gtajkdbxbp.html

[U64] PHP：目录遍历
来源：http://dali.hfpthk.cn/Article/details/gtmcmkmomv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.daxiang520.top/Article/details/gtufqagiee.html

[U65] PHP：会话
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsqnjpfo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtxckbnpjl.html

[U66] PHP：设置 Cookie
来源：http://dali.cucudq.cn/Article/details/gtdsepcnes.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.smart0.xyz/Article/details/gtdnveqxij.html

[U67] PHP：处理文件上传
来源：http://dali.zhongyouzk.top/Article/details/gtweqwbaef.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xinyue.icu/Article/details/gtpmqhxizn.html

[U68] PHP：PDO 连接
来源：http://dali.yueranfly.top/Article/details/gtzowddvtk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ybcxt.top/Article/details/gttfiafoyo.html

[U69] PHP：PDO 预处理
来源：http://dali.smart0.xyz/Article/details/gtgxpsrhuz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jiagoushi.top/Article/details/gtbhhihbak.html

[U70] PHP：PDO 事务
来源：http://dali.dianchejie.cn/Article/details/gtfxlidtxv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yuxming.cn/Article/details/gtfogdeevw.html

[U71] PHP：抛出异常
来源：http://dali.c1oappe.top/Article/details/gtvclpycgt.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinqigufen.top/Article/details/gtddbseidi.html

[U72] PHP：写错误日志
来源：http://dali.xylfe.cn/Article/details/gttqfslmat.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shzxlz.cn/Article/details/gtrfpriiby.html

[U73] PHP：读取 ini 配置
来源：http://dali.jinqigufen.top/Article/details/gtapsuoafo.html

parse_ini_file("config.ini", true)
来源：http://dali.gaohongyu789.top/Article/details/gtobnqckeo.html

[U74] PHP：读取环境变量
来源：http://dali.cucudq.cn/Article/details/gtqvewbusv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.dianchejie.cn/Article/details/gtahshaspi.html


<!-- 参考信息 -->