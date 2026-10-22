代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fzhhl.top/Article/details/gt2kdligwtq.html

[S55] C++：结构化绑定
来源：http://dali.zdqjudy.top/Article/details/gt2oprgxivd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xlsyvelp.html

[S56] C++：optional
来源：http://dali.hammf.cn/Article/details/gt2icorkuea.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pycfn.com/Article/details/gt2ycxyhkzg.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gt2wotlypnk.html

constexpr int N = 10;
来源：http://dali.redwolf501.top/Article/details/gt2zgvjfcoi.html

[S58] C++：命名空间
来源：http://dali.zhixingplan.top/Article/details/gt2pmleboxn.html

namespace ns { int f() { return 1; } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rlawwban.html

[S59] C++：静态断言
来源：http://dali.sysykeji.top/Article/details/gt2mxhsxnog.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abxzsman.html

[S60] C++：遍历并删除元素
来源：http://dali.guannengcc.top/Article/details/gt2gszhjkvy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenlongwang.top/Article/details/gt2lkcesslq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gdlmhtft.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenlongwang.top/Article/details/gt2pvgucubq.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2rfiwwqnp.html

[T01] Kotlin：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2ormiyygv.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gt2kdkotler.html

[T02] Kotlin：变量
来源：http://dali.cucudq.cn/Article/details/gt2lcvzyzoq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhbkihkh.html

[T03] Kotlin：字符串模板
来源：http://dali.gzhubu.top/Article/details/gt2cakdlkzd.html

"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jedhoirh.html

[T04] Kotlin：空安全
来源：http://dali.jlsjyb.cn/Article/details/gt2qkvfnvzh.html

val n: String? = null;  n?.length
来源：http://dali.xziqi.cn/Article/details/gt2yzmvgkxb.html

[T05] Kotlin：when 表达式
来源：http://dali.svipenyu.cn/Article/details/gt2ftqrvokp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.316326.xyz/Article/details/gt2wjdmtqrk.html

[T06] Kotlin：集合映射
来源：http://dali.hammf.cn/Article/details/gt2ilwmtxbu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2koyiuufx.html

[T07] Kotlin：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2ywfxoeqg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgfzy.top/Article/details/gt2cweufnxa.html

[T08] Kotlin：数据类
来源：http://dali.zdqjudy.top/Article/details/gt2qorciygd.html

data class User(val name: String, val age: Int)
来源：http://dali.cqqwz.cn/Article/details/gt2bzbojssn.html

[T09] Kotlin：扩展函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2flmffswn.html

fun String.exclaim() = this + "!"
来源：http://dali.sxryk.cn/Article/details/gt2sorvfrfl.html

[T10] Kotlin：默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2hhxzmljb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yueranfly.top/Article/details/gt2vlzhclgx.html

[T11] Kotlin：协程
来源：http://dali.zhiwuduotai.top/Article/details/gt2ktfqdjfc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xinyue.icu/Article/details/gt2ktaobhre.html

[T12] Kotlin：解构声明
来源：http://dali.redwolf501.top/Article/details/gt2owifoxme.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2ktmnxwll.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigufen.top/Article/details/gt2fimcwqjm.html

val m = mapOf("a" to 1)
来源：http://dali.cucudq.cn/Article/details/gt2cklnsacu.html

[T14] Kotlin：循环
来源：http://dali.nanxuanxn.top/Article/details/gt2lzvcudag.html

for (i in 1..10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gt2zplykqmh.html

[T15] Kotlin：接口
来源：http://dali.cqqwz.cn/Article/details/gt2ybszipkb.html

interface Shape { fun area(): Double }
来源：http://dali.wangshuangyany.cn/Article/details/gt2leavigtc.html

[T16] Swift：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2aypkvspq.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gt2zhxkdnnw.html

[T17] Swift：变量与常量
来源：http://dali.mhx1999.top/Article/details/gt2swyqemdv.html

var a = 1;  let b = 2
来源：http://dali.0kj1m.cn/Article/details/gt2pycquysf.html

[T18] Swift：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gt2qgidqpla.html

"值: \(b)"
来源：http://dali.dianchejie.cn/Article/details/gt2tgxhesor.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zyzjtuhy.html

if let n = opt { print(n) }
来源：http://dali.cdnleiting.top/Article/details/gt2wrcuagmy.html

[T20] Swift：数组操作
来源：http://dali.svipenyu.cn/Article/details/gt2ixpzprwz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hysaishi.cn/Article/details/gt2vcaodgvk.html

[T21] Swift：遍历
来源：http://dali.daxiang520.top/Article/details/gt2htswrrwf.html

for x in a { print(x) }
来源：http://dali.hfpthk.cn/Article/details/gt2xottwiqp.html

[T22] Swift：字典
来源：http://dali.sufxvd.cn/Article/details/gt2iumwlcof.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fengsongda.top/Article/details/gt2smneebvf.html

[T23] Swift：函数
来源：http://dali.meibo888.top/Article/details/gt2eothsudi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jqgufenzy.top/Article/details/gt2igtrkyrk.html

[T24] Swift：闭包
来源：http://dali.shuidangran.top/Article/details/gt2mfarafug.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.redwolf501.top/Article/details/gt2eqmfwwcj.html

[T25] Swift：结构体
来源：http://dali.chenlongwang.top/Article/details/gt2ggzwdfaf.html

struct P { var x: Int }
来源：http://dali.shzxlz.cn/Article/details/gt2ptdnpebo.html

[T26] Swift：类与重写
来源：http://dali.gotoacloud.top/Article/details/gt2vgdnwzjv.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ipauvidk.html

[T27] Swift：错误处理
来源：http://dali.bjfxy.top/Article/details/gt2decnyumo.html

do { try f() } catch { print(error) }
来源：http://dali.wangdashe.top/Article/details/gt2xqyorlhi.html

[T28] Swift：枚举
来源：http://dali.daria6918.cn/Article/details/gt2sepjrxiw.html

enum Color { case red, green }
来源：http://dali.sweek.top/Article/details/gt2lueeojjf.html

[T29] Swift：guard 提前返回
来源：http://dali.hongshengwenyu.top/Article/details/gt2tawkjhue.html

guard let x = opt else { return }
来源：http://dali.jlsjyb.cn/Article/details/gt2wqrgkium.html

[T30] Swift：协议
来源：http://dali.hnqzz.top/Article/details/gt2hrherrlh.html

protocol Shape { func area() -> Double }
来源：http://dali.cheryme.top/Article/details/gt2kbsaekmz.html

[T31] Lua：Hello World
来源：http://dali.yonumen.top/Article/details/gt2lyfebhkt.html

print("Hello")
来源：http://dali.hammf.cn/Article/details/gt2ivpzxoaj.html

[T32] Lua：局部变量
来源：http://dali.jqgufenzy.top/Article/details/gt2qhoazrhn.html

local a = 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2wgqsgxqx.html

[T33] Lua：表（数组）
来源：http://dali.meibo888.top/Article/details/gt2ynkmvktf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zycfv.cn/Article/details/gt2nwcsqqfw.html

[T34] Lua：遍历表
来源：http://dali.pycfn.com/Article/details/gt2xlzdhaxh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xuanzx.com/Article/details/gt2ngygvmqq.html

[T35] Lua：字典表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gcgrkzlf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2xxekusla.html

[T36] Lua：函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2idyxhhzh.html

function add(a, b) return a + b end
来源：http://dali.yanxiufei.cn/Article/details/gt2rwvzgqmu.html

[T37] Lua：字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gt2pxidkwad.html

"a" .. "b"
来源：http://dali.mhx1999.top/Article/details/gt2yybzvhnc.html

[T38] Lua：条件
来源：http://dali.svipenyu.cn/Article/details/gt2hvfkpmbd.html

if x > 0 then print("正") end
来源：http://dali.tianlin.xyz/Article/details/gt2ijlykljk.html

[T39] Lua：模式匹配
来源：http://dali.andypj.xyz/Article/details/gt2tcejtdxf.html

string.find(s, "%d+")
来源：http://dali.nanxinkj.top/Article/details/gt2rghzzpxj.html

[T40] Lua：元表
来源：http://dali.yueranfly.top/Article/details/gt2lodpdibm.html

setmetatable({}, { __index = base })
来源：http://dali.havefunace.top/Article/details/gt2wxbdfkfh.html

[T41] Perl：Hello World
来源：http://dali.tanke756.top/Article/details/gt2lqoelchv.html

print "Hello\n";
来源：http://dali.tian-w.cn/Article/details/gt2tygnmlxm.html

[T42] Perl：变量类型
来源：http://dali.c1oappe.top/Article/details/gt2xbqkexkj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gotoacloud.top/Article/details/gt2izauqsge.html

[T43] Perl：字符串插值
来源：http://dali.yj20258888.top/Article/details/gt2kkmgyhcf.html

"值: $a"
来源：http://dali.jinqigfzy.top/Article/details/gt2szauhhhx.html

[T44] Perl：条件
来源：http://dali.smart0.xyz/Article/details/gt2dcbptood.html

if ($a > 0) { print "正"; }
来源：http://dali.hnqzz.top/Article/details/gt2vxcmbkdq.html

[T45] Perl：数组遍历
来源：http://dali.hfpthk.cn/Article/details/gt2yylvnseb.html

for my $x (@arr) { print $x; }
来源：http://dali.yj20258.top/Article/details/gt2ioapcwak.html

[T46] Perl：哈希操作
来源：http://dali.haohaochexian.top/Article/details/gt2vlwcwbdd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.andypj.xyz/Article/details/gt2kqnzhkwn.html

[T47] Perl：正则捕获
来源：http://dali.316326.xyz/Article/details/gt2odrpznjt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ckstudoz.html

[T48] Perl：正则替换
来源：http://dali.yuanzhike.top/Article/details/gt2vtxyqqzv.html

$s =~ s/old/new/g;
来源：http://dali.andypj.xyz/Article/details/gt2hifsjbrv.html

[T49] Perl：函数
来源：http://dali.mhx1999.top/Article/details/gt2kdcmkhon.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gt2ltmwjxqj.html

[T50] Perl：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gt2rvnjuypf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.dianchejie.cn/Article/details/gt2zziskezt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ydzc1.top/Article/details/gt2semvowlh.html

[T51] Scala：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2nicezqom.html

println("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gt2bbnumgun.html

[T52] Scala：变量
来源：http://dali.redwolf501.top/Article/details/gt2tisssuxo.html

val a = 1;  var b = 2
来源：http://dali.ydzc1.top/Article/details/gt2zwdddfhx.html

[T53] Scala：字符串插值
来源：http://dali.316326.xyz/Article/details/gt2btwcnjvr.html

s"值: $b"
来源：http://dali.hnxiangtu.top/Article/details/gt2ermaxipt.html

[T54] Scala：集合映射
来源：http://dali.nanxuanxn.top/Article/details/gt2nwpkjkhp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xziqi.cn/Article/details/gt2bwxhigpe.html

[T55] Scala：集合过滤
来源：http://dali.fzhhl.top/Article/details/gt2dztlfxpf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fxuggvkz.html

[T56] Scala：样例类
来源：http://dali.smart0.xyz/Article/details/gt2oinpplgd.html

case class User(name: String, age: Int)
来源：http://dali.hywenlv.cn/Article/details/gt2zwkmsirj.html

[T57] Scala：模式匹配
来源：http://dali.sweek.top/Article/details/gt2rxtedcsy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shuidangran.top/Article/details/gt2lxgasunx.html

[T58] Scala：函数定义
来源：http://dali.daxiang520.top/Article/details/gt2zlmjgkqi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yanxiufei.cn/Article/details/gt2kzmthcvo.html

[T59] Scala：循环
来源：http://dali.hnxiangtu.top/Article/details/gt2stvsiowm.html

for (i <- 1 to 10) println(i)
来源：http://dali.haohaochexian.top/Article/details/gt2ebkuhpam.html

[T60] Scala：折叠
来源：http://dali.hywenlv.cn/Article/details/gt2xgtgqvox.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenlongwang.top/Article/details/gt2ptsxjqdu.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ecpqqkxl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zdqjudy.top/Article/details/gt2ohgrhwzc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2wgjwbzxx.html

[U01] Py：创建虚拟环境
来源：http://dali.chenzaomai.com/Article/details/gt2igzmdrba.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guannengcc.top/Article/details/gt2ocjmtqid.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gzhubu.top/Article/details/gt2lcuaylmf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2lppdhsxc.html

[U03] Py：加载 .env 配置
来源：http://dali.cdnleiting.top/Article/details/gt2jbhdyvad.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.daria6918.cn/Article/details/gt2ejvsozek.html

[U04] Py：变量调试打印
来源：http://dali.nwbrower.top/Article/details/gt2jrqqolpj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cqqwz.cn/Article/details/gt2wfjajbyi.html

[U05] Py：列表去重且保序
来源：http://dali.cdnleiting.top/Article/details/gt2kqajrusg.html

list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gt2pbtplbrj.html

[U06] Py：合并两个字典
来源：http://dali.zhiwuduotai.top/Article/details/gt2uvejxcvr.html

{**a, **b}
来源：http://dali.gotoacloud.top/Article/details/gt2aarzbhha.html

[U07] Py：反转字典键值
来源：http://dali.yj20258888.top/Article/details/gt2nzplcoue.html

{v: k for k, v in d.items()}
来源：http://dali.shzxlz.cn/Article/details/gt2sndoqwlp.html

[U08] Py：展平二维列表
来源：http://dali.ybcxt.top/Article/details/gt2jbfsevnb.html

[y for x in nested for y in x]
来源：http://dali.ybcxt.top/Article/details/gt2peoeuruq.html

[U09] Py：字典取最大值的键
来源：http://dali.vqdsnc.cn/Article/details/gt2uzqxiayg.html

max(d, key=d.get)
来源：http://dali.mhx1999.top/Article/details/gt2mkslwysw.html

[U10] Py：按值排序字典
来源：http://dali.tanke756.top/Article/details/gt2ftuniwnq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hnqzz.top/Article/details/gt2tetfdvxi.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vgztwijf.html

(x * 2 for x in arr)
来源：http://dali.birdmap.top/Article/details/gt2ifyiaqgr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cdnleiting.top/Article/details/gt2sciyyvbp.html

Counter(arr).most_common(3)
来源：http://dali.jiagoushi.top/Article/details/gt2ipsotrre.html

[U13] Py：固定长度队列
来源：http://dali.pycfn.com/Article/details/gt2omxrkdjr.html

deque(maxlen=10)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xdryjeas.html

[U14] Py：分组收集到列表
来源：http://dali.jianghu66.top/Article/details/gt2zypikgdw.html

defaultdict(list)
来源：http://dali.shzxlz.cn/Article/details/gt2tailneao.html

[U15] Py：高精度计时
来源：http://dali.daxiang520.top/Article/details/gt2odlywtdj.html

t = time.perf_counter()
来源：http://dali.dianchejie.cn/Article/details/gt2siqyavrc.html

[U16] Py：命令行参数解析
来源：http://dali.daria6918.cn/Article/details/gt2uadhxojr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2doicsvxd.html

[U17] Py：初始化日志
来源：http://dali.zhoulong.xyz/Article/details/gt2giablsdw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yangfankeji.com/Article/details/gt2lcpgbwcn.html

[U18] Py：预编译正则
来源：http://dali.zhoulong.xyz/Article/details/gt2egpuhytl.html

pat = re.compile(r"\d+")
来源：http://dali.sysykeji.top/Article/details/gt2kozhwcgt.html

[U19] Py：正则替换带回调
来源：http://dali.316326.xyz/Article/details/gt2bzzoptla.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xuanzx.com/Article/details/gt2tvldbbtg.html

[U20] Py：缓存函数结果
来源：http://dali.gzhubu.top/Article/details/gt2lduppshz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aibaodan.cn/Article/details/gt2zuycerqq.html

[U21] Py：自定义上下文管理器
来源：http://dali.jqgufenzy.top/Article/details/gt2dzyokwks.html

@contextlib.contextmanager
来源：http://dali.ydzc1.top/Article/details/gt2cscsgvcg.html

[U22] Py：矩阵转置
来源：http://dali.jyoumei.cn/Article/details/gt2pezxmajy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zxubnxky.html

[U23] Py：分块读取大文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kxrwqwoj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shzxlz.cn/Article/details/gt2ikyolgmv.html

[U24] Py：路径操作
来源：http://dali.tianlin.xyz/Article/details/gt2usfihvxf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gt2qykrddom.html

[U25] Py：CSV 按字典读
来源：http://dali.smart0.xyz/Article/details/gt2jjwixmcv.html

csv.DictReader(f)
来源：http://dali.hysaishi.cn/Article/details/gt2qjozuzdo.html

[U26] Py：并发下载
来源：http://dali.dianchejie.cn/Article/details/gt2uostefam.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yongpay.top/Article/details/gt2kgzqibse.html

[U27] Py：异步 HTTP
来源：http://dali.jianghu66.top/Article/details/gt2kcsvqdfo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.svipenyu.cn/Article/details/gt2arsnvfgd.html

[U28] Py：类型别名
来源：http://dali.yongpay.top/Article/details/gt2fbbgkirl.html

UserId = int
来源：http://dali.meibo888.top/Article/details/gt2hnrdetrk.html

[U29] Py：属性校验
来源：http://dali.dashuyun.cn/Article/details/gt2ukaxhtuo.html

@property 与 @x.setter 配合
来源：http://dali.xziqi.cn/Article/details/gt2pohhiwet.html

[U30] Py：数据类
来源：http://dali.ivvv.top/Article/details/gt2nwpnbzdc.html

@dataclass(slots=True)
来源：http://dali.316326.xyz/Article/details/gt2zizcezto.html

[U31] Py：单测
来源：http://dali.yj20258.top/Article/details/gt2yrloqevj.html

python -m pytest -q
来源：http://dali.meibo888.top/Article/details/gt2lzprqvsk.html

[U32] Py：代码格式化
来源：http://dali.daxiang520.top/Article/details/gt2hoasggtg.html

ruff format . && ruff check --fix .
来源：http://dali.ydzc1.top/Article/details/gt2zvruzeut.html

[U33] Py：打包发布
来源：http://dali.jianghu66.top/Article/details/gt2cyjpneut.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cashguo.top/Article/details/gt2laajggdo.html

[U34] Py：判断编码
来源：http://dali.shzxlz.cn/Article/details/gt2niajutts.html

chardet.detect(raw)
来源：http://dali.cqqwz.cn/Article/details/gt2sbxwqzgm.html

[U35] Py：发送邮件
来源：http://dali.316326.xyz/Article/details/gt2ptswxmxt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xziqi.cn/Article/details/gt2zhtffbof.html

[U36] Py：定时任务
来源：http://dali.xylfe.cn/Article/details/gt2uvtosudl.html

schedule.every(10).minutes.do(job)
来源：http://dali.jianghu66.top/Article/details/gt2giaaftia.html

[U37] Py：读写 Excel
来源：http://dali.zhixingplan.top/Article/details/gt2xzelfgjh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.iojbl.cn/Article/details/gt2bbulqolw.html

[U38] Py：获取脚本所在目录
来源：http://dali.ivvv.top/Article/details/gt2zzojstxq.html

Path(__file__).resolve().parent
来源：http://dali.gotoacloud.top/Article/details/gt2yqqtoudf.html

[U39] Py：判断是否在交互环境
来源：http://dali.ivvv.top/Article/details/gt2nbfkbhfd.html

sys.stdout.isatty()
来源：http://dali.guannengcc.top/Article/details/gt2dqvshkoa.html

[U40] Py：打印到标准错误
来源：http://dali.c1oappe.top/Article/details/gt2txumuvzu.html

print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2crtbcnzo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gaohongyu789.top/Article/details/gt2zszadtwr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yanxiufei.cn/Article/details/gt2qvojelrl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ehwqpu.com/Article/details/gt2kpqdffid.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shzxlz.cn/Article/details/gt2bvtqersv.html

[U43] PHP：声明命名空间
来源：http://dali.0kj1m.cn/Article/details/gt2llnqvqrk.html

namespace App\Http;
来源：http://dali.shzxlz.cn/Article/details/gt2gkgjdhyd.html

[U44] PHP：开启严格类型
来源：http://dali.pycfn.com/Article/details/gt2gfkycrtw.html

declare(strict_types=1);
来源：http://dali.zhongyouzk.top/Article/details/gt2kinvdbii.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cdnleiting.top/Article/details/gt2ktappviv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gt2kymcqgwz.html

[U46] PHP：可空类型
来源：http://dali.jianghu66.top/Article/details/gt2rnjxcevo.html

?string $name = null
来源：http://dali.zycfv.cn/Article/details/gt2wpmpjjfu.html

[U47] PHP：联合类型
来源：http://dali.cdnleiting.top/Article/details/gt2ddvwfhai.html

int|string $id
来源：http://dali.cdnleiting.top/Article/details/gt2mehlxxup.html

[U48] PHP：纯枚举
来源：http://dali.ehwqpu.com/Article/details/gt2dgnaxdbf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.dashuyun.cn/Article/details/gt2ltiqxdyo.html

[U49] PHP：只读属性
来源：http://dali.yangfankeji.com/Article/details/gt2hphtebtq.html

public readonly string $name
来源：http://dali.birdmap.top/Article/details/gt2ofcsnfro.html

[U50] PHP：构造器属性提升
来源：http://dali.fzhhl.top/Article/details/gt2bljrzlbf.html

public function __construct(private int $id) {}
来源：http://dali.zhixingplan.top/Article/details/gt2pxuqhayp.html

[U51] PHP：数组解构
来源：http://dali.birdmap.top/Article/details/gt2bbyqunrr.html

[$a, $b] = $arr;
来源：http://dali.iojbl.cn/Article/details/gt2jgxfvask.html

[U52] PHP：箭头函数
来源：http://dali.gogol.net.cn/Article/details/gt2lirxdgtu.html

$double = fn($x) => $x * 2;
来源：http://dali.nanxuanxn.top/Article/details/gt2ntpznzsq.html

[U53] PHP：空合并运算符
来源：http://dali.zycfv.cn/Article/details/gt2ijjgaxoc.html

$v = $a ?? $b ?? "default";
来源：http://dali.guowangkeji.top/Article/details/gt2doetribs.html

[U54] PHP：空安全调用
来源：http://dali.havefunace.top/Article/details/gt2wjxuqsxi.html

$obj?->method()
来源：http://dali.tanke756.top/Article/details/gt2fckclyaz.html

[U55] PHP：match 表达式
来源：http://dali.aibaodan.cn/Article/details/gt2nxokpkrb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.feifeiyinyue.top/Article/details/gt2qvojhwmi.html

[U56] PHP：命名参数
来源：http://dali.cheryme.top/Article/details/gt2bmegkwsh.html

f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2uuwjvtvm.html

[U57] PHP：字符串插值
来源：http://dali.xuanzx.com/Article/details/gt2mqqlcwge.html

"值: {$a}"
来源：http://dali.aizwys.cn/Article/details/gt2qiauadmk.html

[U58] PHP：数组三件套
来源：http://dali.yj20258.top/Article/details/gt2pinxbpnv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.daxiang520.top/Article/details/gt2lkhimppl.html

[U59] PHP：自定义排序
来源：http://dali.yuanzhike.top/Article/details/gt2qedlxfnb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangdashe.top/Article/details/gt2ydluvijb.html

[U60] PHP：JSON 编解码
来源：http://dali.jyoumei.cn/Article/details/gt2hsumqwtf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2reatvgjy.html

[U61] PHP：正则
来源：http://dali.cqqwz.cn/Article/details/gt2mbnhjckn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.bjfxy.top/Article/details/gt2mdhbcldt.html

[U62] PHP：日期对象
来源：http://dali.9152youxi.cn/Article/details/gt2ovvxwkhy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.pycfn.com/Article/details/gt2vjuutgsa.html

[U63] PHP：文件读写
来源：http://dali.shangyingyoupin.top/Article/details/gt2qkapdivd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hnxiangtu.top/Article/details/gt2rjveksaf.html

[U64] PHP：目录遍历
来源：http://dali.cashguo.top/Article/details/gt2usdubovb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ydzc1.top/Article/details/gt2dtqjvuwz.html

[U65] PHP：会话
来源：http://dali.birdmap.top/Article/details/gt2jujnkjcg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.pycfn.com/Article/details/gt2ohrgsjmo.html

[U66] PHP：设置 Cookie
来源：http://dali.svipenyu.cn/Article/details/gt2mduuzgmq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.9152youxi.cn/Article/details/gt2ntlmwynm.html

[U67] PHP：处理文件上传
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ietqrqiv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhoulong.xyz/Article/details/gt2wukatdqj.html

[U68] PHP：PDO 连接
来源：http://dali.daria6918.cn/Article/details/gt2lppmhcxi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.vqdsnc.cn/Article/details/gt2jrdmbsin.html

[U69] PHP：PDO 预处理
来源：http://dali.chenlongwang.top/Article/details/gt2mcteomld.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.bjfxy.top/Article/details/gt2rlndpquf.html

[U70] PHP：PDO 事务
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffbymjln.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.svipenyu.cn/Article/details/gt2atyjsegu.html

[U71] PHP：抛出异常
来源：http://dali.cqqwz.cn/Article/details/gt2cojmhmys.html

throw new RuntimeException("失败", 500);
来源：http://dali.fengsongda.top/Article/details/gt2bxuedqgi.html

[U72] PHP：写错误日志
来源：http://dali.zdqjudy.top/Article/details/gt2udgxyoje.html

error_log("失败: " . $e->getMessage());
来源：http://dali.wangdashe.top/Article/details/gt2ndcqsecn.html

[U73] PHP：读取 ini 配置
来源：http://dali.cdnleiting.top/Article/details/gt2kgnbguee.html

parse_ini_file("config.ini", true)
来源：http://dali.redwolf501.top/Article/details/gt2ubngscll.html

[U74] PHP：读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gt2dlcrpmpp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ydzc1.top/Article/details/gt2otqfaacn.html

[U75] PHP：依赖注入
来源：http://dali.aizwys.cn/Article/details/gt2fvybhkrc.html

composer require psr/container
来源：http://dali.gaohongyu789.top/Article/details/gt2nkzduuve.html

[U76] PHP：简单路由
来源：http://dali.redwolf501.top/Article/details/gt2suwslgsq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.wangdashe.top/Article/details/gt2syhiecoc.html

[U77] PHP：模板渲染
来源：http://dali.nanxuanxn.top/Article/details/gt2frwanwov.html

composer require twig/twig
来源：http://dali.guannengcc.top/Article/details/gt2dpowgesw.html

[U78] PHP：单元测试
来源：http://dali.sweek.top/Article/details/gt2uxlppduh.html

composer require --dev phpunit/phpunit
来源：http://dali.pengpengdd.cyou/Article/details/gt2rkhwsipr.html

[U79] PHP：静态分析
来源：http://dali.316326.xyz/Article/details/gt2jwjwtghf.html

composer require --dev phpstan/phpstan
来源：http://dali.gogol.net.cn/Article/details/gt2agkdgekt.html

[U80] PHP：代码规范修复
来源：http://dali.hammf.cn/Article/details/gt2uyxloecp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mknrdjfb.html


<!-- 参考信息 -->