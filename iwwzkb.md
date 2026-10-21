代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.cashguo.top/Article/details/gtrkzujtoj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yonumen.top/Article/details/gtahrbwsbw.html

[S48] C++：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtgxusgbdt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cqqwz.cn/Article/details/gtyxbtfpro.html

while (std::getline(in, line)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtawphrkap.html

[S49] C++：写文件
来源：http://dali.jlsjyb.cn/Article/details/gtebszbpmr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ybcxt.top/Article/details/gtzwbhzazf.html

[S50] C++：格式化数字
来源：http://dali.xziqi.cn/Article/details/gtbqepdmus.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tanke756.top/Article/details/gtthifajdc.html

[S51] C++：显式类型转换
来源：http://dali.hywenlv.cn/Article/details/gtmisoxzed.html

static_cast<double>(a) / b
来源：http://dali.dashuyun.cn/Article/details/gtiqktgoqq.html

[S52] C++：const 与 noexcept
来源：http://dali.fzhhl.top/Article/details/gtdkraqoae.html

int size() const noexcept { return n_; }
来源：http://dali.snrcjt.cn/Article/details/gtzeedxnqd.html

[S53] C++：移动语义
来源：http://dali.0kj1m.cn/Article/details/gtygmggsif.html

std::vector<int> w = std::move(v);
来源：http://dali.smart0.xyz/Article/details/gtpcwqsqqz.html

[S54] C++：异常处理
来源：http://dali.gzhubu.top/Article/details/gttxyebzxi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guannengcc.top/Article/details/gtlkgueszk.html

[S55] C++：结构化绑定
来源：http://dali.jyoumei.cn/Article/details/gtfujklahj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hfpthk.cn/Article/details/gthdckctfs.html

[S56] C++：optional
来源：http://dali.yanxiufei.cn/Article/details/gtpjhviobu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258888.top/Article/details/gtqvstocsg.html

[S57] C++：编译期常量
来源：http://dali.jinqigufen.top/Article/details/gtjudgwvjr.html

constexpr int N = 10;
来源：http://dali.tianlin.xyz/Article/details/gtflxnnwya.html

[S58] C++：命名空间
来源：http://dali.hnxiangtu.top/Article/details/gtgzvmdsoa.html

namespace ns { int f() { return 1; } }
来源：http://dali.xuanzx.com/Article/details/gtayffcnjl.html

[S59] C++：静态断言
来源：http://dali.zhongyouzk.top/Article/details/gtzafnamph.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sufxvd.cn/Article/details/gtlytiffrm.html

[S60] C++：遍历并删除元素
来源：http://dali.andypj.xyz/Article/details/gtshpmbtkq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daria6918.cn/Article/details/gtimtyttgh.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtdztfpdys.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fengsongda.top/Article/details/gtaprwpiue.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwajrkzuj.html

[T01] Kotlin：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtfnmypwqm.html

println("Hello")
来源：http://dali.gzhubu.top/Article/details/gttmjnchfj.html

[T02] Kotlin：变量
来源：http://dali.xziqi.cn/Article/details/gtdyqabkaw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jlsjyb.cn/Article/details/gtvonpldqn.html

[T03] Kotlin：字符串模板
来源：http://dali.hnxiangtu.top/Article/details/gtsfzvzjsa.html

"值: $b"
来源：http://dali.yongpay.top/Article/details/gtysfxpquh.html

[T04] Kotlin：空安全
来源：http://dali.jyoumei.cn/Article/details/gtemghepcf.html

val n: String? = null;  n?.length
来源：http://dali.pycfn.com/Article/details/gtbncpvjny.html

[T05] Kotlin：when 表达式
来源：http://dali.guannengcc.top/Article/details/gtknvgpksu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangtech.top/Article/details/gtatnscqbc.html

[T06] Kotlin：集合映射
来源：http://dali.nanxinkj.top/Article/details/gtyxfcspjw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtppnpveer.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gtvftejggy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shzxlz.cn/Article/details/gtlfraawuk.html

[T08] Kotlin：数据类
来源：http://dali.yvedp.cn/Article/details/gtsxcmsqum.html

data class User(val name: String, val age: Int)
来源：http://dali.c1oappe.top/Article/details/gthtcrmzgp.html

[T09] Kotlin：扩展函数
来源：http://dali.svipenyu.cn/Article/details/gtpjsugtxs.html

fun String.exclaim() = this + "!"
来源：http://dali.shuidangran.top/Article/details/gtqskontck.html

[T10] Kotlin：默认参数
来源：http://dali.cucudq.cn/Article/details/gtmejreoxi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aizwys.cn/Article/details/gtobehxcpy.html

[T11] Kotlin：协程
来源：http://dali.tianlin.xyz/Article/details/gtgbquhzaw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuxming.cn/Article/details/gtsmqsbsdb.html

[T12] Kotlin：解构声明
来源：http://dali.jqgfzy.top/Article/details/gtellsrknl.html

val (a, b) = Pair(1, 2)
来源：http://dali.xylfe.cn/Article/details/gtyzwzholx.html

[T13] Kotlin：只读 Map
来源：http://dali.yueranfly.top/Article/details/gtfscvuzsu.html

val m = mapOf("a" to 1)
来源：http://dali.ydzc1.top/Article/details/gtndoucxax.html

[T14] Kotlin：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteiqejxqr.html

for (i in 1..10) println(i)
来源：http://dali.nwbrower.top/Article/details/gtfvckrfbv.html

[T15] Kotlin：接口
来源：http://dali.9152youxi.cn/Article/details/gtfeylgtrl.html

interface Shape { fun area(): Double }
来源：http://dali.redwolf501.top/Article/details/gtdjwixnsh.html

[T16] Swift：Hello World
来源：http://dali.xylfe.cn/Article/details/gtjayirqor.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gttfpjfnpw.html

[T17] Swift：变量与常量
来源：http://dali.meibo888.top/Article/details/gtcwdydjfg.html

var a = 1;  let b = 2
来源：http://dali.chenzaomai.com/Article/details/gtgnoaeskc.html

[T18] Swift：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gtdbxoywme.html

"值: \(b)"
来源：http://dali.xinyue.icu/Article/details/gtgghiwkoy.html

[T19] Swift：可选绑定
来源：http://dali.birdmap.top/Article/details/gtjbhvbqdd.html

if let n = opt { print(n) }
来源：http://dali.gzhubu.top/Article/details/gtzqqaryic.html

[T20] Swift：数组操作
来源：http://dali.yuanzhike.top/Article/details/gtlcckpozx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.c1oappe.top/Article/details/gtaxacdutl.html

[T21] Swift：遍历
来源：http://dali.jyoumei.cn/Article/details/gtqcffkxrd.html

for x in a { print(x) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzgluzji.html

[T22] Swift：字典
来源：http://dali.daria6918.cn/Article/details/gtnmbnvzru.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xziqi.cn/Article/details/gtocnketmi.html

[T23] Swift：函数
来源：http://dali.hysaishi.cn/Article/details/gtdqtmhqcr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cqqwz.cn/Article/details/gtzqbwvzto.html

[T24] Swift：闭包
来源：http://dali.hnxiangtu.top/Article/details/gtbyyzzzii.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.iojbl.cn/Article/details/gtkqioybpz.html

[T25] Swift：结构体
来源：http://dali.jyoumei.cn/Article/details/gtwrbnuscn.html

struct P { var x: Int }
来源：http://dali.9152youxi.cn/Article/details/gtfdytrizy.html

[T26] Swift：类与重写
来源：http://dali.yuanzhike.top/Article/details/gtgvjnmotr.html

class A: Base { override func f() {} }
来源：http://dali.yanxiufei.cn/Article/details/gttnkcxvos.html

[T27] Swift：错误处理
来源：http://dali.dianchejie.cn/Article/details/gtdvjobznu.html

do { try f() } catch { print(error) }
来源：http://dali.havefunace.top/Article/details/gtyainuoig.html

[T28] Swift：枚举
来源：http://dali.nanxinkj.top/Article/details/gtgwiwfxig.html

enum Color { case red, green }
来源：http://dali.yonumen.top/Article/details/gtccbceqad.html

[T29] Swift：guard 提前返回
来源：http://dali.yuanzhike.top/Article/details/gtujpqzfdy.html

guard let x = opt else { return }
来源：http://dali.snrcjt.cn/Article/details/gttsreuvhp.html

[T30] Swift：协议
来源：http://dali.xuanzx.com/Article/details/gtnawvfyno.html

protocol Shape { func area() -> Double }
来源：http://dali.guannengcc.top/Article/details/gtvwtybeuh.html

[T31] Lua：Hello World
来源：http://dali.mhx1999.top/Article/details/gtysyzucsq.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gtoaocrgcd.html

[T32] Lua：局部变量
来源：http://dali.jianghu66.top/Article/details/gtftnhrcsq.html

local a = 1
来源：http://dali.yuxming.cn/Article/details/gtxykoefqy.html

[T33] Lua：表（数组）
来源：http://dali.yueranfly.top/Article/details/gtdqusidmd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnqzz.top/Article/details/gtetixokjt.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngyrbiwy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daxiang520.top/Article/details/gtviumcnvs.html

[T35] Lua：字典表
来源：http://dali.jinqigufen.top/Article/details/gtpevluszc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sweek.top/Article/details/gtvlilxfpp.html

[T36] Lua：函数
来源：http://dali.bjfxy.top/Article/details/gtrjowwibn.html

function add(a, b) return a + b end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssaijsre.html

[T37] Lua：字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gtzddkyzht.html

"a" .. "b"
来源：http://dali.wangshuangyany.cn/Article/details/gtiaycltif.html

[T38] Lua：条件
来源：http://dali.chenzaomai.com/Article/details/gtpufpbvwh.html

if x > 0 then print("正") end
来源：http://dali.yj202588.top/Article/details/gtcotgzfji.html

[T39] Lua：模式匹配
来源：http://dali.quarkkingdee.top/Article/details/gtgzlsrxso.html

string.find(s, "%d+")
来源：http://dali.gaohongyu789.top/Article/details/gtewxqcnxw.html

[T40] Lua：元表
来源：http://dali.zhiwuduotai.top/Article/details/gtifxlegci.html

setmetatable({}, { __index = base })
来源：http://dali.yuxming.cn/Article/details/gtcnqjnpjf.html

[T41] Perl：Hello World
来源：http://dali.ybcxt.top/Article/details/gtdpwwtjqx.html

print "Hello\n";
来源：http://dali.daxiang520.top/Article/details/gtnvunfxec.html

[T42] Perl：变量类型
来源：http://dali.zhixingplan.top/Article/details/gtudglxcdq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yuanzhike.top/Article/details/gtjboqydep.html

[T43] Perl：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtyijeocdh.html

"值: $a"
来源：http://dali.yj202588.top/Article/details/gtbpoakqtv.html

[T44] Perl：条件
来源：http://dali.quarkkingdee.top/Article/details/gtzhyibqih.html

if ($a > 0) { print "正"; }
来源：http://dali.wangdashe.top/Article/details/gtzazsxmot.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrjymxhh.html

for my $x (@arr) { print $x; }
来源：http://dali.jinqigfzy.top/Article/details/gtmudyjckp.html

[T46] Perl：哈希操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspirimar.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tianlin.xyz/Article/details/gthpnwqmga.html

[T47] Perl：正则捕获
来源：http://dali.chenlongwang.top/Article/details/gtkmcajuns.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinqigfzy.top/Article/details/gthimsgnbl.html

[T48] Perl：正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtxouucpmq.html

$s =~ s/old/new/g;
来源：http://dali.yuanzhike.top/Article/details/gtfigfhlob.html

[T49] Perl：函数
来源：http://dali.shangyingyoupin.top/Article/details/gthtpbcidf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gtqymizccb.html

[T50] Perl：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtckizdymb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhongyouzk.top/Article/details/gthuxbgukb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yonumen.top/Article/details/gtnyuodgpo.html

[T51] Scala：Hello World
来源：http://dali.yonumen.top/Article/details/gtgpdsenia.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gtrzmfntzx.html

[T52] Scala：变量
来源：http://dali.zhengqikj.top/Article/details/gtqhfompop.html

val a = 1;  var b = 2
来源：http://dali.yj20258888.top/Article/details/gtlavjppxt.html

[T53] Scala：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtkuzzvjos.html

s"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gtlxwaewsn.html

[T54] Scala：集合映射
来源：http://dali.zhixingplan.top/Article/details/gtxtjjqpvp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yuxming.cn/Article/details/gtebmpxtex.html

[T55] Scala：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gteynfqzdy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jyoumei.cn/Article/details/gteuyvqoww.html

[T56] Scala：样例类
来源：http://dali.dashuyun.cn/Article/details/gtotbnzsma.html

case class User(name: String, age: Int)
来源：http://dali.0kj1m.cn/Article/details/gtyodnilin.html

[T57] Scala：模式匹配
来源：http://dali.shuidangran.top/Article/details/gtpntydfor.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.kuanghao11.cn/Article/details/gtecoroygy.html

[T58] Scala：函数定义
来源：http://dali.nwbrower.top/Article/details/gtosmbupoz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sysykeji.top/Article/details/gtpfiltzpu.html

[T59] Scala：循环
来源：http://dali.yonumen.top/Article/details/gtkosokkxl.html

for (i <- 1 to 10) println(i)
来源：http://dali.redwolf501.top/Article/details/gtqwcnjhkd.html

[T60] Scala：折叠
来源：http://dali.meibo888.top/Article/details/gtxuzpemkr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hfpthk.cn/Article/details/gtzrtqiqpl.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gthpkawrul.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.svipenyu.cn/Article/details/gtnloahzli.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtpvpfyoqy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhongyouzk.top/Article/details/gtnmxsulkz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gotoacloud.top/Article/details/gtpszseumo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xziqi.cn/Article/details/gtzasiveuj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.birdmap.top/Article/details/gtsgmfftli.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgfzy.top/Article/details/gtzhxggisf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sufxvd.cn/Article/details/gtlioqvkxw.html

[U04] Py：变量调试打印
来源：http://dali.dashuyun.cn/Article/details/gtcuwakvor.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sysykeji.top/Article/details/gtolpjdxqx.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzubcysc.html

list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gtpctmwmxf.html

[U06] Py：合并两个字典
来源：http://dali.kuanghao11.cn/Article/details/gtorghggjf.html

{**a, **b}
来源：http://dali.birdmap.top/Article/details/gtlxykqcdu.html

[U07] Py：反转字典键值
来源：http://dali.iojbl.cn/Article/details/gtdxbnglrd.html

{v: k for k, v in d.items()}
来源：http://dali.cqqwz.cn/Article/details/gtnfxnimom.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangtech.top/Article/details/gttpaiqyik.html

[y for x in nested for y in x]
来源：http://dali.yongpay.top/Article/details/gtgjoprbmn.html

[U09] Py：字典取最大值的键
来源：http://dali.daria6918.cn/Article/details/gtchuyaium.html

max(d, key=d.get)
来源：http://dali.quarkkingdee.top/Article/details/gtbfnjtiqt.html

[U10] Py：按值排序字典
来源：http://dali.xylfe.cn/Article/details/gtpnqojgdo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hnxiangtu.top/Article/details/gtbnxpcggq.html

[U11] Py：生成器表达式
来源：http://dali.bjfxy.top/Article/details/gthknhzekp.html

(x * 2 for x in arr)
来源：http://dali.andypj.xyz/Article/details/gtptciofnh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jqgufenzy.top/Article/details/gtwzqfpsad.html

Counter(arr).most_common(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfoocgrb.html

[U13] Py：固定长度队列
来源：http://dali.jinqigufen.top/Article/details/gtwukadlom.html

deque(maxlen=10)
来源：http://dali.mhx1999.top/Article/details/gteqijaguj.html

[U14] Py：分组收集到列表
来源：http://dali.zdqjudy.top/Article/details/gtzatcrpkz.html

defaultdict(list)
来源：http://dali.jinqigfzy.top/Article/details/gttlgdgjqb.html

[U15] Py：高精度计时
来源：http://dali.quarkkingdee.top/Article/details/gthayiixgm.html

t = time.perf_counter()
来源：http://dali.zhengqikj.top/Article/details/gtcslpsgzt.html

[U16] Py：命令行参数解析
来源：http://dali.yangfankeji.com/Article/details/gtbgwvxhjx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jiagoushi.top/Article/details/gtgdqttenh.html

[U17] Py：初始化日志
来源：http://dali.zhixingplan.top/Article/details/gtcppslkxo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.c1oappe.top/Article/details/gtkjalcdfq.html

[U18] Py：预编译正则
来源：http://dali.aizwys.cn/Article/details/gtrhbozhbp.html

pat = re.compile(r"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtklgaeaow.html

[U19] Py：正则替换带回调
来源：http://dali.xuetiantiany.cn/Article/details/gtjyjsgeok.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.pycfn.com/Article/details/gtfhnbowej.html

[U20] Py：缓存函数结果
来源：http://dali.sxryk.cn/Article/details/gtsrpofkim.html

@functools.lru_cache(maxsize=None)
来源：http://dali.daria6918.cn/Article/details/gtpednkklt.html

[U21] Py：自定义上下文管理器
来源：http://dali.quarkkingdee.top/Article/details/gtffontqov.html

@contextlib.contextmanager
来源：http://dali.xziqi.cn/Article/details/gtigdwwxem.html

[U22] Py：矩阵转置
来源：http://dali.shanyushiyangtech.top/Article/details/gtxomisdhj.html

list(zip(*m))
来源：http://dali.feifeiyinyue.top/Article/details/gthpnkhing.html

[U23] Py：分块读取大文件
来源：http://dali.ybcxt.top/Article/details/gtqygwkpca.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.mhx1999.top/Article/details/gtmhxulxga.html

[U24] Py：路径操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtygehjcic.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gtqohcrbao.html

[U25] Py：CSV 按字典读
来源：http://dali.pengpengdd.cyou/Article/details/gtqmzxphyt.html

csv.DictReader(f)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstnxaeys.html

[U26] Py：并发下载
来源：http://dali.yvedp.cn/Article/details/gtltladnat.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cdnleiting.top/Article/details/gtxjigzbgy.html

[U27] Py：异步 HTTP
来源：http://dali.zhengqikj.top/Article/details/gtjewsfevs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinqigfzy.top/Article/details/gthstykdxe.html

[U28] Py：类型别名
来源：http://dali.nanxuanxn.top/Article/details/gtqxulqces.html

UserId = int
来源：http://dali.gogol.net.cn/Article/details/gtnhrxpqbj.html

[U29] Py：属性校验
来源：http://dali.yongpay.top/Article/details/gthzqirhsx.html

@property 与 @x.setter 配合
来源：http://dali.cucudq.cn/Article/details/gteyqlvmah.html

[U30] Py：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gtevqvvynv.html

@dataclass(slots=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkracjcy.html

[U31] Py：单测
来源：http://dali.gzhubu.top/Article/details/gtykrjcdrh.html

python -m pytest -q
来源：http://dali.gzhubu.top/Article/details/gtzpgdbvgr.html

[U32] Py：代码格式化
来源：http://dali.hnxiangtu.top/Article/details/gtacxdpxve.html

ruff format . && ruff check --fix .
来源：http://dali.birdmap.top/Article/details/gthukaagdo.html

[U33] Py：打包发布
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphswjsma.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhoulong.xyz/Article/details/gttvabkwtx.html

[U34] Py：判断编码
来源：http://dali.zhiwuduotai.top/Article/details/gtqisfcznw.html

chardet.detect(raw)
来源：http://dali.cdnleiting.top/Article/details/gttuxzbfwv.html

[U35] Py：发送邮件
来源：http://dali.cheryme.top/Article/details/gtdfvotvve.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.guowangkeji.top/Article/details/gtcusdsrsq.html

[U36] Py：定时任务
来源：http://dali.yj20258.top/Article/details/gtepvsvxxp.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinqigufen.top/Article/details/gttzmswzxz.html

[U37] Py：读写 Excel
来源：http://dali.hongshengwenyu.top/Article/details/gtqmvedckv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yanxiufei.cn/Article/details/gtbukjmlac.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhongyouzk.top/Article/details/gtclmwhiov.html

Path(__file__).resolve().parent
来源：http://dali.mhx1999.top/Article/details/gtnumvfxzl.html

[U39] Py：判断是否在交互环境
来源：http://dali.redwolf501.top/Article/details/gtgommkdjz.html

sys.stdout.isatty()
来源：http://dali.sxryk.cn/Article/details/gtmjadyxsy.html

[U40] Py：打印到标准错误
来源：http://dali.ydzc1.top/Article/details/gtiwomogje.html

print("err", file=sys.stderr)
来源：http://dali.pengpengdd.cyou/Article/details/gtgmjwrvfp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.redwolf501.top/Article/details/gtkwchmtvq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zycfv.cn/Article/details/gtufmpnpuu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.wangshuangyany.cn/Article/details/gtuimblgaa.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cucudq.cn/Article/details/gtugvstfyr.html

[U43] PHP：声明命名空间
来源：http://dali.haohaochexian.top/Article/details/gthguvngrz.html

namespace App\Http;
来源：http://dali.cucudq.cn/Article/details/gtdfoumqhs.html

[U44] PHP：开启严格类型
来源：http://dali.yongpay.top/Article/details/gtuwsfxlwf.html

declare(strict_types=1);
来源：http://dali.jinghuilouyu.cn/Article/details/gthbifrvhl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yj20258888.top/Article/details/gtcaqdxgno.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtkmvewbuo.html

[U46] PHP：可空类型
来源：http://dali.svipenyu.cn/Article/details/gtqznlsliz.html

?string $name = null
来源：http://dali.dianchejie.cn/Article/details/gttznbscuu.html

[U47] PHP：联合类型
来源：http://dali.fzhhl.top/Article/details/gthnihzefx.html

int|string $id
来源：http://dali.jianghu66.top/Article/details/gtjarbjocf.html

[U48] PHP：纯枚举
来源：http://dali.hfpthk.cn/Article/details/gtzwasnbpg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.316326.xyz/Article/details/gttzucrmbf.html

[U49] PHP：只读属性
来源：http://dali.smart0.xyz/Article/details/gtluzmlapx.html

public readonly string $name
来源：http://dali.dashuyun.cn/Article/details/gtpwnqcrhw.html

[U50] PHP：构造器属性提升
来源：http://dali.cqqwz.cn/Article/details/gtkvtqgjtt.html

public function __construct(private int $id) {}
来源：http://dali.shzxlz.cn/Article/details/gtxuudtfko.html

[U51] PHP：数组解构
来源：http://dali.zhoulong.xyz/Article/details/gtlahouluh.html

[$a, $b] = $arr;
来源：http://dali.jinqigufen.top/Article/details/gtuwhxokow.html

[U52] PHP：箭头函数
来源：http://dali.0kj1m.cn/Article/details/gtofzkfvts.html

$double = fn($x) => $x * 2;
来源：http://dali.cucudq.cn/Article/details/gtgkzwqcsy.html

[U53] PHP：空合并运算符
来源：http://dali.tian-w.cn/Article/details/gtzemgprqi.html

$v = $a ?? $b ?? "default";
来源：http://dali.zycfv.cn/Article/details/gtnuirarkt.html

[U54] PHP：空安全调用
来源：http://dali.pengpengdd.cyou/Article/details/gtagjozjzo.html

$obj?->method()
来源：http://dali.shuidangran.top/Article/details/gtrsflmjzy.html

[U55] PHP：match 表达式
来源：http://dali.nwbrower.top/Article/details/gtfgtyqtpx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.fengsongda.top/Article/details/gtdxzyrgwd.html

[U56] PHP：命名参数
来源：http://dali.redwolf501.top/Article/details/gtbltrbqux.html

f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtrzkqxmvr.html

[U57] PHP：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtpigokxet.html

"值: {$a}"
来源：http://dali.shangyingyoupin.top/Article/details/gtdxqeqlgw.html

[U58] PHP：数组三件套
来源：http://dali.nanxinkj.top/Article/details/gtubeeotpd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.snrcjt.cn/Article/details/gtqowovnho.html

[U59] PHP：自定义排序
来源：http://dali.9152youxi.cn/Article/details/gtkzqqvbqa.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gtrltpnrbr.html

[U60] PHP：JSON 编解码
来源：http://dali.nanxuanxn.top/Article/details/gturgscmnz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hnxiangtu.top/Article/details/gtcshciulz.html

[U61] PHP：正则
来源：http://dali.ivvv.top/Article/details/gtqbzfnegv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.dashuyun.cn/Article/details/gtcrongpfb.html

[U62] PHP：日期对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctbvmbcz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.quarkkingdee.top/Article/details/gtjbqkyrci.html

[U63] PHP：文件读写
来源：http://dali.aizwys.cn/Article/details/gtnugatztb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jianghu66.top/Article/details/gtvakysryf.html

[U64] PHP：目录遍历
来源：http://dali.mhx1999.top/Article/details/gthaplamyb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwcnjazy.html

[U65] PHP：会话
来源：http://dali.quarkkingdee.top/Article/details/gtycgatkqu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtibqwztbm.html

[U66] PHP：设置 Cookie
来源：http://dali.jinqigufen.top/Article/details/gtgvirlntd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zdqjudy.top/Article/details/gtztjmtuoa.html

[U67] PHP：处理文件上传
来源：http://dali.sweek.top/Article/details/gtizkxuylv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shzxlz.cn/Article/details/gtjbogkmdd.html

[U68] PHP：PDO 连接
来源：http://dali.tianlin.xyz/Article/details/gtttnxpjdr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ydzc1.top/Article/details/gtyhbvjsee.html

[U69] PHP：PDO 预处理
来源：http://dali.xuanzx.com/Article/details/gtlfjpohhm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.9152youxi.cn/Article/details/gtbhrkthua.html

[U70] PHP：PDO 事务
来源：http://dali.cqqwz.cn/Article/details/gtewqhhkeh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tianlin.xyz/Article/details/gtbrsojzzx.html

[U71] PHP：抛出异常
来源：http://dali.xinyue.icu/Article/details/gtlblsblmb.html

throw new RuntimeException("失败", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gtjqkylcuc.html

[U72] PHP：写错误日志
来源：http://dali.hywenlv.cn/Article/details/gtvrnktyrr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hywenlv.cn/Article/details/gtdfcjiurb.html


<!-- 参考信息 -->