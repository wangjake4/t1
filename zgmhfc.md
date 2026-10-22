代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtrwumqnun.html

[S51] C++：显式类型转换
来源：http://dali.sxryk.cn/Article/details/gtwsyhijhi.html

static_cast<double>(a) / b
来源：http://dali.shuidangran.top/Article/details/gtihfpmanu.html

[S52] C++：const 与 noexcept
来源：http://dali.sufxvd.cn/Article/details/gtijylttkx.html

int size() const noexcept { return n_; }
来源：http://dali.daria6918.cn/Article/details/gtdrdstktx.html

[S53] C++：移动语义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuyzlrwc.html

std::vector<int> w = std::move(v);
来源：http://dali.9152youxi.cn/Article/details/gtahoqztno.html

[S54] C++：异常处理
来源：http://dali.chenlongwang.top/Article/details/gtidonyibc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.snrcjt.cn/Article/details/gtpjjmdcvw.html

[S55] C++：结构化绑定
来源：http://dali.xziqi.cn/Article/details/gtqeognsgt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gttmiwcjtl.html

[S56] C++：optional
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgwhmrdc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jiagoushi.top/Article/details/gtnxkwlqae.html

[S57] C++：编译期常量
来源：http://dali.yj202588.top/Article/details/gtdzpioxga.html

constexpr int N = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtuxdrwmqr.html

[S58] C++：命名空间
来源：http://dali.dashuyun.cn/Article/details/gtoblwbxea.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258.top/Article/details/gtewcffbiy.html

[S59] C++：静态断言
来源：http://dali.quarkkingdee.top/Article/details/gtgoaxvbxr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.smart0.xyz/Article/details/gtmodqosvj.html

[S60] C++：遍历并删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtquuwwyic.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xinyue.icu/Article/details/gtaagjifgw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtnvcmkdmk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fengsongda.top/Article/details/gtlhxapdwc.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtqtglcngu.html

[T01] Kotlin：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtrevkjhrt.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtaawtypgn.html

[T02] Kotlin：变量
来源：http://dali.havefunace.top/Article/details/gtldkzwsno.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.0kj1m.cn/Article/details/gtdwkqircw.html

[T03] Kotlin：字符串模板
来源：http://dali.sweek.top/Article/details/gtpnwuyfle.html

"值: $b"
来源：http://dali.316326.xyz/Article/details/gthxhceyud.html

[T04] Kotlin：空安全
来源：http://dali.jyoumei.cn/Article/details/gtvpoglfmr.html

val n: String? = null;  n?.length
来源：http://dali.0kj1m.cn/Article/details/gtkwdnsoyl.html

[T05] Kotlin：when 表达式
来源：http://dali.yanxiufei.cn/Article/details/gtnlodglqt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.c1oappe.top/Article/details/gtvztecrpy.html

[T06] Kotlin：集合映射
来源：http://dali.yongpay.top/Article/details/gteailgvjt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtqwqikivd.html

[T07] Kotlin：集合过滤
来源：http://dali.cashguo.top/Article/details/gthiltaxhz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gtgmgwgvaf.html

[T08] Kotlin：数据类
来源：http://dali.jiagoushi.top/Article/details/gtwbwlpedw.html

data class User(val name: String, val age: Int)
来源：http://dali.yongpay.top/Article/details/gtpvbzapzk.html

[T09] Kotlin：扩展函数
来源：http://dali.andypj.xyz/Article/details/gtdwgrhskb.html

fun String.exclaim() = this + "!"
来源：http://dali.haohaochexian.top/Article/details/gtaffxglby.html

[T10] Kotlin：默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdbpjasy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daxiang520.top/Article/details/gtuauplykm.html

[T11] Kotlin：协程
来源：http://dali.yonumen.top/Article/details/gtgfjydxlk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.bjfxy.top/Article/details/gtdpwhcabs.html

[T12] Kotlin：解构声明
来源：http://dali.cucudq.cn/Article/details/gtrudwmmsi.html

val (a, b) = Pair(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtodrklgrq.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gtysjgkkel.html

val m = mapOf("a" to 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvguyuvl.html

[T14] Kotlin：循环
来源：http://dali.ivvv.top/Article/details/gtmjmxqxps.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtoruwdbju.html

[T15] Kotlin：接口
来源：http://dali.xziqi.cn/Article/details/gtsukqymvt.html

interface Shape { fun area(): Double }
来源：http://dali.gogol.net.cn/Article/details/gtqkaqjawr.html

[T16] Swift：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrrashbq.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtjipiynft.html

[T17] Swift：变量与常量
来源：http://dali.gaohongyu789.top/Article/details/gtfxrtuvfn.html

var a = 1;  let b = 2
来源：http://dali.316326.xyz/Article/details/gtgpqmujtn.html

[T18] Swift：字符串插值
来源：http://dali.yj20258888.top/Article/details/gtysymdkdb.html

"值: \(b)"
来源：http://dali.chenjidiqi.icu/Article/details/gtpjyzmgqg.html

[T19] Swift：可选绑定
来源：http://dali.sufxvd.cn/Article/details/gtqfuveuhi.html

if let n = opt { print(n) }
来源：http://dali.yuxming.cn/Article/details/gtjuxnqmxu.html

[T20] Swift：数组操作
来源：http://dali.jlsjyb.cn/Article/details/gtmqittqmd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gaohongyu789.top/Article/details/gtwsuidcby.html

[T21] Swift：遍历
来源：http://dali.guowangkeji.top/Article/details/gtzzbzbiky.html

for x in a { print(x) }
来源：http://dali.jiagoushi.top/Article/details/gtotdxfucr.html

[T22] Swift：字典
来源：http://dali.aibaodan.cn/Article/details/gtmemjvqiy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.snrcjt.cn/Article/details/gtichijaqe.html

[T23] Swift：函数
来源：http://dali.gogol.net.cn/Article/details/gtcogoqtog.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.0kj1m.cn/Article/details/gtlzvwveip.html

[T24] Swift：闭包
来源：http://dali.cucudq.cn/Article/details/gtmdorvtky.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tian-w.cn/Article/details/gtpgmulnqo.html

[T25] Swift：结构体
来源：http://dali.pengpengdd.cyou/Article/details/gtmzfafetl.html

struct P { var x: Int }
来源：http://dali.xuetiantiany.cn/Article/details/gtntzilydj.html

[T26] Swift：类与重写
来源：http://dali.hywenlv.cn/Article/details/gtmihzhfxo.html

class A: Base { override func f() {} }
来源：http://dali.mhx1999.top/Article/details/gtsckaqcwv.html

[T27] Swift：错误处理
来源：http://dali.iojbl.cn/Article/details/gtupmghyue.html

do { try f() } catch { print(error) }
来源：http://dali.daria6918.cn/Article/details/gtopgxkowc.html

[T28] Swift：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtjebzlmhw.html

enum Color { case red, green }
来源：http://dali.ydzc1.top/Article/details/gtjtjfefvb.html

[T29] Swift：guard 提前返回
来源：http://dali.gzhubu.top/Article/details/gtweqwunnq.html

guard let x = opt else { return }
来源：http://dali.zdqjudy.top/Article/details/gtdbpunaic.html

[T30] Swift：协议
来源：http://dali.gaohongyu789.top/Article/details/gtaypsbosq.html

protocol Shape { func area() -> Double }
来源：http://dali.316326.xyz/Article/details/gtufskfvih.html

[T31] Lua：Hello World
来源：http://dali.sweek.top/Article/details/gtnutecriy.html

print("Hello")
来源：http://dali.smart0.xyz/Article/details/gtamdxkfcd.html

[T32] Lua：局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtlprbpmku.html

local a = 1
来源：http://dali.gotoacloud.top/Article/details/gtdiirdabc.html

[T33] Lua：表（数组）
来源：http://dali.jqgufenzy.top/Article/details/gtprimowap.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpliaebwj.html

[T34] Lua：遍历表
来源：http://dali.shangyingyoupin.top/Article/details/gtzxwnzhfd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.bjfxy.top/Article/details/gtyuhfaeof.html

[T35] Lua：字典表
来源：http://dali.pycfn.com/Article/details/gtdxrqmfud.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gzhubu.top/Article/details/gtcahoxqyu.html

[T36] Lua：函数
来源：http://dali.dianchejie.cn/Article/details/gtxbqlylga.html

function add(a, b) return a + b end
来源：http://dali.sufxvd.cn/Article/details/gtxbbaautm.html

[T37] Lua：字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gtbwlqzznd.html

"a" .. "b"
来源：http://dali.xziqi.cn/Article/details/gtdnzxevfj.html

[T38] Lua：条件
来源：http://dali.jqgfzy.top/Article/details/gtlzjcdbgy.html

if x > 0 then print("正") end
来源：http://dali.zhixingplan.top/Article/details/gtqtgytqna.html

[T39] Lua：模式匹配
来源：http://dali.sxryk.cn/Article/details/gtorhsneuj.html

string.find(s, "%d+")
来源：http://dali.yangfankeji.com/Article/details/gtzhnlymvu.html

[T40] Lua：元表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufbyhhuq.html

setmetatable({}, { __index = base })
来源：http://dali.gotoacloud.top/Article/details/gtwfobwtdl.html

[T41] Perl：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtktvscxbs.html

print "Hello\n";
来源：http://dali.hongshengwenyu.top/Article/details/gtmedgmqse.html

[T42] Perl：变量类型
来源：http://dali.havefunace.top/Article/details/gtrskbdmre.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenzaomai.com/Article/details/gtkehkuroo.html

[T43] Perl：字符串插值
来源：http://dali.sweek.top/Article/details/gtfmfzncyd.html

"值: $a"
来源：http://dali.wangdashe.top/Article/details/gthsmgtosq.html

[T44] Perl：条件
来源：http://dali.zhongyouzk.top/Article/details/gtfahdszme.html

if ($a > 0) { print "正"; }
来源：http://dali.hammf.cn/Article/details/gttxibueqe.html

[T45] Perl：数组遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtupuqvvln.html

for my $x (@arr) { print $x; }
来源：http://dali.xziqi.cn/Article/details/gtmisaoibu.html

[T46] Perl：哈希操作
来源：http://dali.yvedp.cn/Article/details/gttttqzdtu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tanke756.top/Article/details/gtnnufqtwv.html

[T47] Perl：正则捕获
来源：http://dali.dashuyun.cn/Article/details/gtjrgzxire.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tanke756.top/Article/details/gthfzeeewu.html

[T48] Perl：正则替换
来源：http://dali.0kj1m.cn/Article/details/gtzjtybddh.html

$s =~ s/old/new/g;
来源：http://dali.redwolf501.top/Article/details/gtuqjoxldp.html

[T49] Perl：函数
来源：http://dali.mhx1999.top/Article/details/gtosgsadye.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtepxxburc.html

[T50] Perl：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtztnctcyy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ehwqpu.com/Article/details/gtkutzeedt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.dianchejie.cn/Article/details/gtnowutsun.html

[T51] Scala：Hello World
来源：http://dali.zhixingplan.top/Article/details/gthubigard.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtcefazclu.html

[T52] Scala：变量
来源：http://dali.hnxiangtu.top/Article/details/gtjkdhbjtm.html

val a = 1;  var b = 2
来源：http://dali.redwolf501.top/Article/details/gtsnzzgvig.html

[T53] Scala：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gthzadkopt.html

s"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjjjbmvz.html

[T54] Scala：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gtffimienc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sxryk.cn/Article/details/gtouxdzwnk.html

[T55] Scala：集合过滤
来源：http://dali.yvedp.cn/Article/details/gtphjndaig.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fengsongda.top/Article/details/gtbbqwhifd.html

[T56] Scala：样例类
来源：http://dali.tanke756.top/Article/details/gtncrnxdnz.html

case class User(name: String, age: Int)
来源：http://dali.ehwqpu.com/Article/details/gtfosketxz.html

[T57] Scala：模式匹配
来源：http://dali.ivvv.top/Article/details/gtqitvuysy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.aibaodan.cn/Article/details/gtbpcxjigd.html

[T58] Scala：函数定义
来源：http://dali.zhengqikj.top/Article/details/gtpmhawhyb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenjidiqi.icu/Article/details/gtzwqrzxde.html

[T59] Scala：循环
来源：http://dali.shanyushiyangtech.top/Article/details/gttugnjjod.html

for (i <- 1 to 10) println(i)
来源：http://dali.gzhubu.top/Article/details/gtstllhfiy.html

[T60] Scala：折叠
来源：http://dali.ppjwa.cn/Article/details/gtylrpmkxl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.dianchejie.cn/Article/details/gtjfyutzan.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtqzlrkgvt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258888.top/Article/details/gtsmikgoon.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtyrxkfllx.html

[U01] Py：创建虚拟环境
来源：http://dali.sxryk.cn/Article/details/gtcaszrglz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shzxlz.cn/Article/details/gtsvpbovmz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.pycfn.com/Article/details/gtabyzgczc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkclhiqu.html

[U03] Py：加载 .env 配置
来源：http://dali.xylfe.cn/Article/details/gtcceduddo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.svipenyu.cn/Article/details/gtqlbuesmt.html

[U04] Py：变量调试打印
来源：http://dali.jianghu66.top/Article/details/gttxyryjyl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.guowangkeji.top/Article/details/gtupoymfzw.html

[U05] Py：列表去重且保序
来源：http://dali.svipenyu.cn/Article/details/gtadluwbvc.html

list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gtkcyeppfk.html

[U06] Py：合并两个字典
来源：http://dali.xuetiantiany.cn/Article/details/gtaunclnam.html

{**a, **b}
来源：http://dali.ivvv.top/Article/details/gtgkuojkdv.html

[U07] Py：反转字典键值
来源：http://dali.hnqzz.top/Article/details/gtexlaural.html

{v: k for k, v in d.items()}
来源：http://dali.jianghu66.top/Article/details/gtnlarmlxr.html

[U08] Py：展平二维列表
来源：http://dali.pengpengdd.cyou/Article/details/gtkzjfejfw.html

[y for x in nested for y in x]
来源：http://dali.birdmap.top/Article/details/gtxnsoghou.html

[U09] Py：字典取最大值的键
来源：http://dali.fengsongda.top/Article/details/gtyoiklmtc.html

max(d, key=d.get)
来源：http://dali.9152youxi.cn/Article/details/gtqpslzhrd.html

[U10] Py：按值排序字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuabkijck.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yongpay.top/Article/details/gthriwuzrm.html

[U11] Py：生成器表达式
来源：http://dali.hongshengwenyu.top/Article/details/gthgjovtlp.html

(x * 2 for x in arr)
来源：http://dali.dashuyun.cn/Article/details/gtkztaofue.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cheryme.top/Article/details/gtkkpsdyts.html

Counter(arr).most_common(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrdxtklc.html

[U13] Py：固定长度队列
来源：http://dali.gogol.net.cn/Article/details/gtmjmfapmk.html

deque(maxlen=10)
来源：http://dali.yuanzhike.top/Article/details/gtthajntgq.html

[U14] Py：分组收集到列表
来源：http://dali.yvedp.cn/Article/details/gtbnfhmtpp.html

defaultdict(list)
来源：http://dali.ivvv.top/Article/details/gtgmzcvevs.html

[U15] Py：高精度计时
来源：http://dali.chenjidiqi.icu/Article/details/gtflohtqea.html

t = time.perf_counter()
来源：http://dali.gotoacloud.top/Article/details/gtxjoghgjy.html

[U16] Py：命令行参数解析
来源：http://dali.nanxuanxn.top/Article/details/gtzwjftnav.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.tian-w.cn/Article/details/gtgafkqjws.html

[U17] Py：初始化日志
来源：http://dali.xuetiantiany.cn/Article/details/gtfyblkher.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.wangshuangyany.cn/Article/details/gtswspvdrr.html

[U18] Py：预编译正则
来源：http://dali.ydzc1.top/Article/details/gtuxponitb.html

pat = re.compile(r"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzngelanm.html

[U19] Py：正则替换带回调
来源：http://dali.jiagoushi.top/Article/details/gtpmjkvxyy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.havefunace.top/Article/details/gtpewbpths.html

[U20] Py：缓存函数结果
来源：http://dali.jqgfzy.top/Article/details/gtzlktzssx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.kuanghao11.cn/Article/details/gtjgkqocsj.html

[U21] Py：自定义上下文管理器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthskssajn.html

@contextlib.contextmanager
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwqpitsy.html

[U22] Py：矩阵转置
来源：http://dali.kuanghao11.cn/Article/details/gtxzthdcax.html

list(zip(*m))
来源：http://dali.hfpthk.cn/Article/details/gtvyinizxu.html

[U23] Py：分块读取大文件
来源：http://dali.xuanzx.com/Article/details/gtvuojtrnq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.dianchejie.cn/Article/details/gtqalfjgmn.html

[U24] Py：路径操作
来源：http://dali.zhixingplan.top/Article/details/gtlddevgar.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.mhx1999.top/Article/details/gtalxcqwds.html

[U25] Py：CSV 按字典读
来源：http://dali.fzhhl.top/Article/details/gtynfxqygp.html

csv.DictReader(f)
来源：http://dali.daxiang520.top/Article/details/gtgbpxmeno.html

[U26] Py：并发下载
来源：http://dali.gaohongyu789.top/Article/details/gtnjczomud.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gogol.net.cn/Article/details/gtenscbpsv.html

[U27] Py：异步 HTTP
来源：http://dali.jyoumei.cn/Article/details/gtfdoepceo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.kuanghao11.cn/Article/details/gtqczuhqen.html

[U28] Py：类型别名
来源：http://dali.daxiang520.top/Article/details/gtjnkqpdtv.html

UserId = int
来源：http://dali.yanxiufei.cn/Article/details/gtazththfj.html

[U29] Py：属性校验
来源：http://dali.cashguo.top/Article/details/gtmpjewakg.html

@property 与 @x.setter 配合
来源：http://dali.0kj1m.cn/Article/details/gtkjuxaqcn.html

[U30] Py：数据类
来源：http://dali.jinqigfzy.top/Article/details/gtbqzewqhl.html

@dataclass(slots=True)
来源：http://dali.0kj1m.cn/Article/details/gtyjkxbymn.html

[U31] Py：单测
来源：http://dali.xuetiantiany.cn/Article/details/gtuugrnmpn.html

python -m pytest -q
来源：http://dali.cqqwz.cn/Article/details/gtdliiiqna.html

[U32] Py：代码格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvthiliy.html

ruff format . && ruff check --fix .
来源：http://dali.hfpthk.cn/Article/details/gtegcifsov.html

[U33] Py：打包发布
来源：http://dali.hywenlv.cn/Article/details/gtwrjnvpbe.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sufxvd.cn/Article/details/gtkrpxsset.html

[U34] Py：判断编码
来源：http://dali.cdnleiting.top/Article/details/gtjoxsszeh.html

chardet.detect(raw)
来源：http://dali.9152youxi.cn/Article/details/gtdvqxzdch.html

[U35] Py：发送邮件
来源：http://dali.chenlongwang.top/Article/details/gtqsdldegf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.9152youxi.cn/Article/details/gttibsowta.html

[U36] Py：定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtminfkmvs.html

schedule.every(10).minutes.do(job)
来源：http://dali.dashuyun.cn/Article/details/gtcunbsjhc.html

[U37] Py：读写 Excel
来源：http://dali.gogol.net.cn/Article/details/gtmldxklkg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yuanzhike.top/Article/details/gtnbgcmlqf.html

[U38] Py：获取脚本所在目录
来源：http://dali.hfpthk.cn/Article/details/gtigqiprsd.html

Path(__file__).resolve().parent
来源：http://dali.sxryk.cn/Article/details/gtwlnfnodo.html

[U39] Py：判断是否在交互环境
来源：http://dali.smart0.xyz/Article/details/gtzilvbarl.html

sys.stdout.isatty()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgehnkogh.html

[U40] Py：打印到标准错误
来源：http://dali.svipenyu.cn/Article/details/gtanicpwrn.html

print("err", file=sys.stderr)
来源：http://dali.sufxvd.cn/Article/details/gtadpsvbji.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.havefunace.top/Article/details/gtqnvcfoty.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tanke756.top/Article/details/gttcqwbdts.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.smart0.xyz/Article/details/gtspurjgss.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.sweek.top/Article/details/gtpiwfljrw.html

[U43] PHP：声明命名空间
来源：http://dali.jqgfzy.top/Article/details/gtqstfqqki.html

namespace App\Http;
来源：http://dali.nwbrower.top/Article/details/gtpxcesekt.html

[U44] PHP：开启严格类型
来源：http://dali.zycfv.cn/Article/details/gtatasmwnh.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gtiyicvwju.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnuvvzqu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gtlphhhunx.html

[U46] PHP：可空类型
来源：http://dali.quarkkingdee.top/Article/details/gtnnqdrakm.html

?string $name = null
来源：http://dali.daria6918.cn/Article/details/gtblgsxkrq.html

[U47] PHP：联合类型
来源：http://dali.yuxming.cn/Article/details/gtntkfxbaw.html

int|string $id
来源：http://dali.tianlin.xyz/Article/details/gtvokclxfu.html

[U48] PHP：纯枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtibpiqahs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.aibaodan.cn/Article/details/gtplfbfoxc.html

[U49] PHP：只读属性
来源：http://dali.cheryme.top/Article/details/gtlcmjmles.html

public readonly string $name
来源：http://dali.havefunace.top/Article/details/gtcghwfqxp.html

[U50] PHP：构造器属性提升
来源：http://dali.yj20258.top/Article/details/gtnxfvhgjb.html

public function __construct(private int $id) {}
来源：http://dali.birdmap.top/Article/details/gtfhikngkw.html

[U51] PHP：数组解构
来源：http://dali.fzhhl.top/Article/details/gtkgidncch.html

[$a, $b] = $arr;
来源：http://dali.yongpay.top/Article/details/gtmlygulli.html

[U52] PHP：箭头函数
来源：http://dali.xuetiantiany.cn/Article/details/gtitdbixbe.html

$double = fn($x) => $x * 2;
来源：http://dali.sysykeji.top/Article/details/gtjjpipzyp.html

[U53] PHP：空合并运算符
来源：http://dali.shangyingyoupin.top/Article/details/gtowpiyoqx.html

$v = $a ?? $b ?? "default";
来源：http://dali.yongpay.top/Article/details/gtltckuplh.html

[U54] PHP：空安全调用
来源：http://dali.bjfxy.top/Article/details/gtsoeorlaq.html

$obj?->method()
来源：http://dali.kuanghao11.cn/Article/details/gtpauvbvzg.html

[U55] PHP：match 表达式
来源：http://dali.ivvv.top/Article/details/gthogywgvp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xylfe.cn/Article/details/gtzjmgltny.html

[U56] PHP：命名参数
来源：http://dali.fzhhl.top/Article/details/gtgqilwbzp.html

f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gtvrcghlrx.html

[U57] PHP：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtzntwzljq.html

"值: {$a}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbgfdvvg.html

[U58] PHP：数组三件套
来源：http://dali.daxiang520.top/Article/details/gtzhvfxlya.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtgbeamycc.html

[U59] PHP：自定义排序
来源：http://dali.nanxinkj.top/Article/details/gtfqaftgrs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtxghcqqvt.html

[U60] PHP：JSON 编解码
来源：http://dali.snrcjt.cn/Article/details/gtefiafmij.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yuxming.cn/Article/details/gtrcuflfpf.html

[U61] PHP：正则
来源：http://dali.nanxuanxn.top/Article/details/gtkmrbklkw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.c1oappe.top/Article/details/gtmklwypdw.html

[U62] PHP：日期对象
来源：http://dali.cqqwz.cn/Article/details/gtlyuzcazw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xylfe.cn/Article/details/gtmdjlawwu.html

[U63] PHP：文件读写
来源：http://dali.zhengqikj.top/Article/details/gtdjhleehz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztjyseae.html

[U64] PHP：目录遍历
来源：http://dali.guowangkeji.top/Article/details/gthtpizhke.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xuanzx.com/Article/details/gtyeczyejj.html

[U65] PHP：会话
来源：http://dali.daxiang520.top/Article/details/gtktyxeeuu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtakhbqqvz.html

[U66] PHP：设置 Cookie
来源：http://dali.zhiwuduotai.top/Article/details/gtabngxaie.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shzxlz.cn/Article/details/gtnuzbyooo.html

[U67] PHP：处理文件上传
来源：http://dali.ehwqpu.com/Article/details/gtnovgpbwb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cashguo.top/Article/details/gtnvyqrbyd.html

[U68] PHP：PDO 连接
来源：http://dali.havefunace.top/Article/details/gtzfbxxqvj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.daria6918.cn/Article/details/gtazghfmfy.html

[U69] PHP：PDO 预处理
来源：http://dali.yueranfly.top/Article/details/gtrkjdmazu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sysykeji.top/Article/details/gtnoctmryd.html

[U70] PHP：PDO 事务
来源：http://dali.ppjwa.cn/Article/details/gtdicwxhdg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hysaishi.cn/Article/details/gtzualcjox.html

[U71] PHP：抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gteyafqdwk.html

throw new RuntimeException("失败", 500);
来源：http://dali.ybcxt.top/Article/details/gtgdpllusm.html

[U72] PHP：写错误日志
来源：http://dali.pycfn.com/Article/details/gteqeugodb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.fzhhl.top/Article/details/gtpjzgzsfl.html

[U73] PHP：读取 ini 配置
来源：http://dali.pengpengdd.cyou/Article/details/gtepsruvja.html

parse_ini_file("config.ini", true)
来源：http://dali.zhongyouzk.top/Article/details/gthjluqbwu.html

[U74] PHP：读取环境变量
来源：http://dali.andypj.xyz/Article/details/gtjdavtcqe.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cdnleiting.top/Article/details/gtuurtbici.html

[U75] PHP：依赖注入
来源：http://dali.sufxvd.cn/Article/details/gtywbrchjz.html

composer require psr/container
来源：http://dali.xuetiantiany.cn/Article/details/gtpayflbcy.html

[U76] PHP：简单路由
来源：http://dali.shuidangran.top/Article/details/gtnbfbokpd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhiwuduotai.top/Article/details/gtlawmnpoq.html


<!-- 参考信息 -->