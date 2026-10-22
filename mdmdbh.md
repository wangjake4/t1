代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2cglmoujn.html

[S51] C++：显式类型转换
来源：http://dali.snrcjt.cn/Article/details/gt2besbjafm.html

static_cast<double>(a) / b
来源：http://dali.jqgufenzy.top/Article/details/gt2mdpdvzbj.html

[S52] C++：const 与 noexcept
来源：http://dali.nwbrower.top/Article/details/gt2kybvrxhk.html

int size() const noexcept { return n_; }
来源：http://dali.jlsjyb.cn/Article/details/gt2eqopushe.html

[S53] C++：移动语义
来源：http://dali.cqqwz.cn/Article/details/gt2jurseljp.html

std::vector<int> w = std::move(v);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jbyzlwlx.html

[S54] C++：异常处理
来源：http://dali.yuxming.cn/Article/details/gt2elntdcrl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuanzhike.top/Article/details/gt2ebrevkfn.html

[S55] C++：结构化绑定
来源：http://dali.zhoulong.xyz/Article/details/gt2froypyeb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lursacnv.html

[S56] C++：optional
来源：http://dali.sweek.top/Article/details/gt2reaaeowq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gt2eydopjut.html

[S57] C++：编译期常量
来源：http://dali.gotoacloud.top/Article/details/gt2zlbbwsps.html

constexpr int N = 10;
来源：http://dali.cheryme.top/Article/details/gt2ntrwjpvy.html

[S58] C++：命名空间
来源：http://dali.nanxuanxn.top/Article/details/gt2fglqnlhs.html

namespace ns { int f() { return 1; } }
来源：http://dali.bjfxy.top/Article/details/gt2jgakaztq.html

[S59] C++：静态断言
来源：http://dali.redwolf501.top/Article/details/gt2ugnmduem.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tian-w.cn/Article/details/gt2vbtjfmir.html

[S60] C++：遍历并删除元素
来源：http://dali.shzxlz.cn/Article/details/gt2vkutbfcb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sihxcauo.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2xsocmmhk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2robvvxzj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qluskikz.html

[T01] Kotlin：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2soqapqje.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gt2iprgwzbp.html

[T02] Kotlin：变量
来源：http://dali.xinyue.icu/Article/details/gt2sfprwtjt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shzxlz.cn/Article/details/gt2lgqcpinz.html

[T03] Kotlin：字符串模板
来源：http://dali.iojbl.cn/Article/details/gt2cwlzvfrx.html

"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gt2lpuqcsbf.html

[T04] Kotlin：空安全
来源：http://dali.ppjwa.cn/Article/details/gt2pcyuenrd.html

val n: String? = null;  n?.length
来源：http://dali.gogol.net.cn/Article/details/gt2tdmyyxcx.html

[T05] Kotlin：when 表达式
来源：http://dali.pycfn.com/Article/details/gt2zdzymwej.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.svipenyu.cn/Article/details/gt2ecmpgyud.html

[T06] Kotlin：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yhutxojp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sysykeji.top/Article/details/gt2erusznhd.html

[T07] Kotlin：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gt2winzocox.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sxryk.cn/Article/details/gt2ywafxjxe.html

[T08] Kotlin：数据类
来源：http://dali.chenzaomai.com/Article/details/gt2mdjufbis.html

data class User(val name: String, val age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gt2knrthcsv.html

[T09] Kotlin：扩展函数
来源：http://dali.0kj1m.cn/Article/details/gt2vrwslwwg.html

fun String.exclaim() = this + "!"
来源：http://dali.cashguo.top/Article/details/gt2uasjrkax.html

[T10] Kotlin：默认参数
来源：http://dali.9152youxi.cn/Article/details/gt2oxskzotl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cfcqcazy.html

[T11] Kotlin：协程
来源：http://dali.yj202588.top/Article/details/gt2xddtpzrl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.0kj1m.cn/Article/details/gt2jpwiollq.html

[T12] Kotlin：解构声明
来源：http://dali.jqgfzy.top/Article/details/gt2ohbzsgnc.html

val (a, b) = Pair(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2evtonliw.html

[T13] Kotlin：只读 Map
来源：http://dali.wangshuangyany.cn/Article/details/gt2dizavsnn.html

val m = mapOf("a" to 1)
来源：http://dali.xziqi.cn/Article/details/gt2oaxzyrck.html

[T14] Kotlin：循环
来源：http://dali.xylfe.cn/Article/details/gt2xrmfzbql.html

for (i in 1..10) println(i)
来源：http://dali.chenzaomai.com/Article/details/gt2ivihstvf.html

[T15] Kotlin：接口
来源：http://dali.daxiang520.top/Article/details/gt2sxhggtos.html

interface Shape { fun area(): Double }
来源：http://dali.yanxiufei.cn/Article/details/gt2zaffnxfh.html

[T16] Swift：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2tbalcumn.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gt2qrnmtrao.html

[T17] Swift：变量与常量
来源：http://dali.zhongyouzk.top/Article/details/gt2qslksani.html

var a = 1;  let b = 2
来源：http://dali.nanxuanxn.top/Article/details/gt2wltzjjxm.html

[T18] Swift：字符串插值
来源：http://dali.zycfv.cn/Article/details/gt2rutnvumx.html

"值: \(b)"
来源：http://dali.haohaochexian.top/Article/details/gt2fxijzhuh.html

[T19] Swift：可选绑定
来源：http://dali.yuanzhike.top/Article/details/gt2soetumdg.html

if let n = opt { print(n) }
来源：http://dali.316326.xyz/Article/details/gt2crtvdmxq.html

[T20] Swift：数组操作
来源：http://dali.cucudq.cn/Article/details/gt2bjpxwcuk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.havefunace.top/Article/details/gt2ruihmfdn.html

[T21] Swift：遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2czvryfcf.html

for x in a { print(x) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zykvpaju.html

[T22] Swift：字典
来源：http://dali.zdqjudy.top/Article/details/gt2drabebfy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.birdmap.top/Article/details/gt2sjwrlzpz.html

[T23] Swift：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zuxkhtet.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.pycfn.com/Article/details/gt2eyyzlvis.html

[T24] Swift：闭包
来源：http://dali.hywenlv.cn/Article/details/gt2zjbzxdba.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sxryk.cn/Article/details/gt2qfcvxsfu.html

[T25] Swift：结构体
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2genqhuze.html

struct P { var x: Int }
来源：http://dali.tian-w.cn/Article/details/gt2juuptbku.html

[T26] Swift：类与重写
来源：http://dali.smart0.xyz/Article/details/gt2ecxzvgzq.html

class A: Base { override func f() {} }
来源：http://dali.jyoumei.cn/Article/details/gt2hwonwnxf.html

[T27] Swift：错误处理
来源：http://dali.smart0.xyz/Article/details/gt2yvelvekq.html

do { try f() } catch { print(error) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xhlcncky.html

[T28] Swift：枚举
来源：http://dali.xuanzx.com/Article/details/gt2lwsvncil.html

enum Color { case red, green }
来源：http://dali.xziqi.cn/Article/details/gt2eqfufefg.html

[T29] Swift：guard 提前返回
来源：http://dali.cqqwz.cn/Article/details/gt2jaiulhwd.html

guard let x = opt else { return }
来源：http://dali.bjfxy.top/Article/details/gt2fhgdzdiq.html

[T30] Swift：协议
来源：http://dali.gaohongyu789.top/Article/details/gt2betunoas.html

protocol Shape { func area() -> Double }
来源：http://dali.chenzaomai.com/Article/details/gt2iimkpcgh.html

[T31] Lua：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2whzedlkh.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jwjjjelz.html

[T32] Lua：局部变量
来源：http://dali.ppjwa.cn/Article/details/gt2nekkzvzb.html

local a = 1
来源：http://dali.zhoulong.xyz/Article/details/gt2zhcxlcbe.html

[T33] Lua：表（数组）
来源：http://dali.zhiwuduotai.top/Article/details/gt2uvnhmiiz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gogol.net.cn/Article/details/gt2kfcjbgic.html

[T34] Lua：遍历表
来源：http://dali.gotoacloud.top/Article/details/gt2xjtuulih.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cheryme.top/Article/details/gt2oirugfvk.html

[T35] Lua：字典表
来源：http://dali.snrcjt.cn/Article/details/gt2efcdkhzx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigfzy.top/Article/details/gt2uuwgjhbx.html

[T36] Lua：函数
来源：http://dali.dianchejie.cn/Article/details/gt2xxfypiri.html

function add(a, b) return a + b end
来源：http://dali.pycfn.com/Article/details/gt2wdebkwkd.html

[T37] Lua：字符串拼接
来源：http://dali.vqdsnc.cn/Article/details/gt2ceqcyyze.html

"a" .. "b"
来源：http://dali.hongshengwenyu.top/Article/details/gt2dsfqwpzp.html

[T38] Lua：条件
来源：http://dali.sxryk.cn/Article/details/gt2mmlscdhy.html

if x > 0 then print("正") end
来源：http://dali.yueranfly.top/Article/details/gt2dhzdgswp.html

[T39] Lua：模式匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2eownchzo.html

string.find(s, "%d+")
来源：http://dali.jqgufenzy.top/Article/details/gt2wzxnjzvy.html

[T40] Lua：元表
来源：http://dali.jlsjyb.cn/Article/details/gt2spefpiqe.html

setmetatable({}, { __index = base })
来源：http://dali.jqgufenzy.top/Article/details/gt2neobtbyq.html

[T41] Perl：Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2bowipgxl.html

print "Hello\n";
来源：http://dali.redwolf501.top/Article/details/gt2ngcguseq.html

[T42] Perl：变量类型
来源：http://dali.zhoulong.xyz/Article/details/gt2ocinzlkg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gogol.net.cn/Article/details/gt2wvjzufdj.html

[T43] Perl：字符串插值
来源：http://dali.sweek.top/Article/details/gt2adhbvgmn.html

"值: $a"
来源：http://dali.guannengcc.top/Article/details/gt2rkzxloch.html

[T44] Perl：条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dfpuwwav.html

if ($a > 0) { print "正"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2anwvdywa.html

[T45] Perl：数组遍历
来源：http://dali.cucudq.cn/Article/details/gt2znpquirg.html

for my $x (@arr) { print $x; }
来源：http://dali.xziqi.cn/Article/details/gt2sjknpxvx.html

[T46] Perl：哈希操作
来源：http://dali.nwbrower.top/Article/details/gt2eoqqzqmt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nanjqkot.html

[T47] Perl：正则捕获
来源：http://dali.cheryme.top/Article/details/gt2zcgzfoay.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pbymaihm.html

[T48] Perl：正则替换
来源：http://dali.cdnleiting.top/Article/details/gt2ptfoehgp.html

$s =~ s/old/new/g;
来源：http://dali.zdqjudy.top/Article/details/gt2ujcipcqk.html

[T49] Perl：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yrkuqkcv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gt2auoeouer.html

[T50] Perl：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2walmjqjl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.mhx1999.top/Article/details/gt2yweqwzlv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.havefunace.top/Article/details/gt2oecgysvw.html

[T51] Scala：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2figyrbsc.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gt2usatpgxf.html

[T52] Scala：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bbwhzsgo.html

val a = 1;  var b = 2
来源：http://dali.nanxuanxn.top/Article/details/gt2gpzonfzi.html

[T53] Scala：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gt2wzyhkxjv.html

s"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gt2wykmywkx.html

[T54] Scala：集合映射
来源：http://dali.xziqi.cn/Article/details/gt2nxhwowmb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.redwolf501.top/Article/details/gt2anritlnz.html

[T55] Scala：集合过滤
来源：http://dali.jianghu66.top/Article/details/gt2ixuvdrej.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tanke756.top/Article/details/gt2gepchkuw.html

[T56] Scala：样例类
来源：http://dali.havefunace.top/Article/details/gt2ikaeilhs.html

case class User(name: String, age: Int)
来源：http://dali.hywenlv.cn/Article/details/gt2aqjdyzhq.html

[T57] Scala：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gt2zwufbwpf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.fzhhl.top/Article/details/gt2yoctfevh.html

[T58] Scala：函数定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dgtbozwc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dianchejie.cn/Article/details/gt2bzajwqcy.html

[T59] Scala：循环
来源：http://dali.svipenyu.cn/Article/details/gt2bzbufusn.html

for (i <- 1 to 10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2efabdxtt.html

[T60] Scala：折叠
来源：http://dali.cqqwz.cn/Article/details/gt2gzpuswgr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwpsidbb.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2fbfkmagf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sufxvd.cn/Article/details/gt2flyehvse.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2tveuymse.html

[U01] Py：创建虚拟环境
来源：http://dali.vqdsnc.cn/Article/details/gt2diuzyjuk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jqgufenzy.top/Article/details/gt2infyrzdk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.meibo888.top/Article/details/gt2zolpoafe.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jiagoushi.top/Article/details/gt2uzepnlfo.html

[U03] Py：加载 .env 配置
来源：http://dali.jinqigufen.top/Article/details/gt2fmfiqxtq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jiagoushi.top/Article/details/gt2gjipfocw.html

[U04] Py：变量调试打印
来源：http://dali.guowangkeji.top/Article/details/gt2plnplvjm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.bjfxy.top/Article/details/gt2oqbrsiqw.html

[U05] Py：列表去重且保序
来源：http://dali.zhongyouzk.top/Article/details/gt2muzcjexv.html

list(dict.fromkeys(arr))
来源：http://dali.hongshengwenyu.top/Article/details/gt2nztnfvwa.html

[U06] Py：合并两个字典
来源：http://dali.wangshuangyany.cn/Article/details/gt2htmcvhji.html

{**a, **b}
来源：http://dali.yj202588.top/Article/details/gt2cukzwstv.html

[U07] Py：反转字典键值
来源：http://dali.vqdsnc.cn/Article/details/gt2faohvolb.html

{v: k for k, v in d.items()}
来源：http://dali.zhiwuduotai.top/Article/details/gt2alknnzep.html

[U08] Py：展平二维列表
来源：http://dali.sweek.top/Article/details/gt2yvarzlam.html

[y for x in nested for y in x]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qgvyrsfm.html

[U09] Py：字典取最大值的键
来源：http://dali.gotoacloud.top/Article/details/gt2pexrunwm.html

max(d, key=d.get)
来源：http://dali.nwbrower.top/Article/details/gt2betrkphj.html

[U10] Py：按值排序字典
来源：http://dali.fengsongda.top/Article/details/gt2gvuyzdgp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhongyouzk.top/Article/details/gt2hpjuadfd.html

[U11] Py：生成器表达式
来源：http://dali.cheryme.top/Article/details/gt2wqueimyd.html

(x * 2 for x in arr)
来源：http://dali.yueranfly.top/Article/details/gt2tjvwpgyk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tian-w.cn/Article/details/gt2lfjkcqfq.html

Counter(arr).most_common(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ychtpzgx.html

[U13] Py：固定长度队列
来源：http://dali.tanke756.top/Article/details/gt2guautriu.html

deque(maxlen=10)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xixmcqao.html

[U14] Py：分组收集到列表
来源：http://dali.aizwys.cn/Article/details/gt2pjvddsqp.html

defaultdict(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ofecpuut.html

[U15] Py：高精度计时
来源：http://dali.ivvv.top/Article/details/gt2ohffavvl.html

t = time.perf_counter()
来源：http://dali.kuanghao11.cn/Article/details/gt2plyugqdk.html

[U16] Py：命令行参数解析
来源：http://dali.zhoulong.xyz/Article/details/gt2lrqvvamw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xylfe.cn/Article/details/gt2aqbqfrum.html

[U17] Py：初始化日志
来源：http://dali.tianlin.xyz/Article/details/gt2uydewhit.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gotoacloud.top/Article/details/gt2axkcnauh.html

[U18] Py：预编译正则
来源：http://dali.zhongyouzk.top/Article/details/gt2csxfirsm.html

pat = re.compile(r"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gt2fyjzjaid.html

[U19] Py：正则替换带回调
来源：http://dali.zhixingplan.top/Article/details/gt2rxrctgin.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigufen.top/Article/details/gt2ulyntnbz.html

[U20] Py：缓存函数结果
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xnostvgj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ivvv.top/Article/details/gt2zotrmbvr.html

[U21] Py：自定义上下文管理器
来源：http://dali.hywenlv.cn/Article/details/gt2dlunqxbd.html

@contextlib.contextmanager
来源：http://dali.chenlongwang.top/Article/details/gt2razzgxwc.html

[U22] Py：矩阵转置
来源：http://dali.chenjidiqi.icu/Article/details/gt2xylsawkf.html

list(zip(*m))
来源：http://dali.xuetiantiany.cn/Article/details/gt2gaepnkcy.html

[U23] Py：分块读取大文件
来源：http://dali.yonumen.top/Article/details/gt2ieqopvrj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.pycfn.com/Article/details/gt2tawxlkih.html

[U24] Py：路径操作
来源：http://dali.zhengqikj.top/Article/details/gt2wvnsbujz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gt2bupdhqhc.html

[U25] Py：CSV 按字典读
来源：http://dali.jianghu66.top/Article/details/gt2cgoghvvu.html

csv.DictReader(f)
来源：http://dali.ydzc1.top/Article/details/gt2oleqjrfu.html

[U26] Py：并发下载
来源：http://dali.zycfv.cn/Article/details/gt2tezueexn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zdqjudy.top/Article/details/gt2xaewhhhv.html

[U27] Py：异步 HTTP
来源：http://dali.xuetiantiany.cn/Article/details/gt2njexnguj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.fzhhl.top/Article/details/gt2ehvtqdtp.html

[U28] Py：类型别名
来源：http://dali.tanke756.top/Article/details/gt2ynupiojz.html

UserId = int
来源：http://dali.cashguo.top/Article/details/gt2gnmlnuxt.html

[U29] Py：属性校验
来源：http://dali.yvedp.cn/Article/details/gt2tzjljhuj.html

@property 与 @x.setter 配合
来源：http://dali.sufxvd.cn/Article/details/gt2fygdkzyd.html

[U30] Py：数据类
来源：http://dali.kuanghao11.cn/Article/details/gt2gdugbhxs.html

@dataclass(slots=True)
来源：http://dali.dianchejie.cn/Article/details/gt2osabnbhh.html

[U31] Py：单测
来源：http://dali.tanke756.top/Article/details/gt2zitxfwfa.html

python -m pytest -q
来源：http://dali.yangfankeji.com/Article/details/gt2vsznbbgc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjznsxh.html

ruff format . && ruff check --fix .
来源：http://dali.cheryme.top/Article/details/gt2fcyaznvn.html

[U33] Py：打包发布
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bevwhyth.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.bjfxy.top/Article/details/gt2gfxkpcsg.html

[U34] Py：判断编码
来源：http://dali.jinqigufen.top/Article/details/gt2zotvkflm.html

chardet.detect(raw)
来源：http://dali.xylfe.cn/Article/details/gt2efdddggp.html

[U35] Py：发送邮件
来源：http://dali.havefunace.top/Article/details/gt2oqmdifkh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hnxiangtu.top/Article/details/gt2qbexgxbg.html

[U36] Py：定时任务
来源：http://dali.kuanghao11.cn/Article/details/gt2noaychbj.html

schedule.every(10).minutes.do(job)
来源：http://dali.fengsongda.top/Article/details/gt2matmpvca.html

[U37] Py：读写 Excel
来源：http://dali.sweek.top/Article/details/gt2yfncnokc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ehwqpu.com/Article/details/gt2cduqazkq.html

[U38] Py：获取脚本所在目录
来源：http://dali.kuanghao11.cn/Article/details/gt2dqbghvsy.html

Path(__file__).resolve().parent
来源：http://dali.zdqjudy.top/Article/details/gt2tuutokhy.html

[U39] Py：判断是否在交互环境
来源：http://dali.daxiang520.top/Article/details/gt2ofgstbzp.html

sys.stdout.isatty()
来源：http://dali.kuanghao11.cn/Article/details/gt2wejldsxa.html

[U40] Py：打印到标准错误
来源：http://dali.birdmap.top/Article/details/gt2gmynbqdz.html

print("err", file=sys.stderr)
来源：http://dali.jiagoushi.top/Article/details/gt2fnbzkrlg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.kuanghao11.cn/Article/details/gt2ohtxiakm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.daria6918.cn/Article/details/gt2ottxdewq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.havefunace.top/Article/details/gt2lhhwwfwj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tian-w.cn/Article/details/gt2oudkeylp.html

[U43] PHP：声明命名空间
来源：http://dali.cqqwz.cn/Article/details/gt2hqbldmey.html

namespace App\Http;
来源：http://dali.meibo888.top/Article/details/gt2ukhfgzno.html

[U44] PHP：开启严格类型
来源：http://dali.9152youxi.cn/Article/details/gt2azzpdzdk.html

declare(strict_types=1);
来源：http://dali.ybcxt.top/Article/details/gt2rqjqpjcx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gzhubu.top/Article/details/gt2fqntgxgm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gt2qjskpdnb.html

[U46] PHP：可空类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ipbrifpv.html

?string $name = null
来源：http://dali.daxiang520.top/Article/details/gt2lbvqiyxg.html

[U47] PHP：联合类型
来源：http://dali.guannengcc.top/Article/details/gt2kqwvyqzn.html

int|string $id
来源：http://dali.snrcjt.cn/Article/details/gt2nccjdjrv.html

[U48] PHP：纯枚举
来源：http://dali.yj202588.top/Article/details/gt2snhrckki.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yuanzhike.top/Article/details/gt2yrjlfila.html

[U49] PHP：只读属性
来源：http://dali.jinqigufen.top/Article/details/gt2fptiozof.html

public readonly string $name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wfukwkjs.html

[U50] PHP：构造器属性提升
来源：http://dali.fzhhl.top/Article/details/gt2vyjcrawl.html

public function __construct(private int $id) {}
来源：http://dali.daria6918.cn/Article/details/gt2uvrsizzd.html

[U51] PHP：数组解构
来源：http://dali.vqdsnc.cn/Article/details/gt2wktbulwy.html

[$a, $b] = $arr;
来源：http://dali.xuanzx.com/Article/details/gt2uhnwddrv.html

[U52] PHP：箭头函数
来源：http://dali.gotoacloud.top/Article/details/gt2jnuzliot.html

$double = fn($x) => $x * 2;
来源：http://dali.fengsongda.top/Article/details/gt2kyyqlcrj.html

[U53] PHP：空合并运算符
来源：http://dali.tian-w.cn/Article/details/gt2krelkwru.html

$v = $a ?? $b ?? "default";
来源：http://dali.ybcxt.top/Article/details/gt2mholmpku.html

[U54] PHP：空安全调用
来源：http://dali.meibo888.top/Article/details/gt2vqsdcuft.html

$obj?->method()
来源：http://dali.quarkkingdee.top/Article/details/gt2nsmpvfef.html

[U55] PHP：match 表达式
来源：http://dali.cheryme.top/Article/details/gt2osgqnyes.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.quarkkingdee.top/Article/details/gt2mxohmbsj.html

[U56] PHP：命名参数
来源：http://dali.ydzc1.top/Article/details/gt2hxyvgwvd.html

f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gt2rioivjli.html

[U57] PHP：字符串插值
来源：http://dali.fengsongda.top/Article/details/gt2zdmczccr.html

"值: {$a}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fygbwvqv.html

[U58] PHP：数组三件套
来源：http://dali.yj202588.top/Article/details/gt2jlejydjm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.daria6918.cn/Article/details/gt2sldmpsrk.html

[U59] PHP：自定义排序
来源：http://dali.jqgfzy.top/Article/details/gt2lqinkmex.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenzaomai.com/Article/details/gt2zysrnqjg.html

[U60] PHP：JSON 编解码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2agoorhzk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jlsjyb.cn/Article/details/gt2gnszkpip.html

[U61] PHP：正则
来源：http://dali.jiagoushi.top/Article/details/gt2jenfstqu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2ycksidyo.html

[U62] PHP：日期对象
来源：http://dali.wangdashe.top/Article/details/gt2naqeneos.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shuidangran.top/Article/details/gt2hlpzaezt.html

[U63] PHP：文件读写
来源：http://dali.daxiang520.top/Article/details/gt2opvypsce.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.snrcjt.cn/Article/details/gt2fvawmgab.html

[U64] PHP：目录遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2hvseidtx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj20258.top/Article/details/gt2ybzqrbaa.html

[U65] PHP：会话
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzhuuhxu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zcnsxhol.html

[U66] PHP：设置 Cookie
来源：http://dali.zycfv.cn/Article/details/gt2laajvdpc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2itdcsyzu.html

[U67] PHP：处理文件上传
来源：http://dali.aizwys.cn/Article/details/gt2wpzhoaky.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yvedp.cn/Article/details/gt2bmcvgurs.html

[U68] PHP：PDO 连接
来源：http://dali.dianchejie.cn/Article/details/gt2splgzjdf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jqgufenzy.top/Article/details/gt2wokslnbs.html

[U69] PHP：PDO 预处理
来源：http://dali.yueranfly.top/Article/details/gt2mkienlbx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.meibo888.top/Article/details/gt2pwyvykmm.html

[U70] PHP：PDO 事务
来源：http://dali.zhixingplan.top/Article/details/gt2vkuynrmj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zycfv.cn/Article/details/gt2mfhbipnm.html

[U71] PHP：抛出异常
来源：http://dali.yj20258.top/Article/details/gt2wmcevgel.html

throw new RuntimeException("失败", 500);
来源：http://dali.ybcxt.top/Article/details/gt2pruhzyuo.html

[U72] PHP：写错误日志
来源：http://dali.hysaishi.cn/Article/details/gt2sbobrkns.html

error_log("失败: " . $e->getMessage());
来源：http://dali.fzhhl.top/Article/details/gt2xkefnfvn.html

[U73] PHP：读取 ini 配置
来源：http://dali.yueranfly.top/Article/details/gt2omzfklcm.html

parse_ini_file("config.ini", true)
来源：http://dali.gzhubu.top/Article/details/gt2dbqofjed.html

[U74] PHP：读取环境变量
来源：http://dali.ivvv.top/Article/details/gt2cpdkzvbv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.dashuyun.cn/Article/details/gt2jtbbxerh.html

[U75] PHP：依赖注入
来源：http://dali.shangyingyoupin.top/Article/details/gt2isccizcx.html

composer require psr/container
来源：http://dali.gogol.net.cn/Article/details/gt2cfqjlcpi.html

[U76] PHP：简单路由
来源：http://dali.yj20258.top/Article/details/gt2wegzduvz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ybcxt.top/Article/details/gt2axszlgym.html


<!-- 参考信息 -->