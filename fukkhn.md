代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.daxiang520.top/Article/details/gtjaprnsgb.html

[S53] C++：移动语义
来源：http://dali.svipenyu.cn/Article/details/gtwlcicyha.html

std::vector<int> w = std::move(v);
来源：http://dali.xziqi.cn/Article/details/gtwctdrvhm.html

[S54] C++：异常处理
来源：http://dali.hywenlv.cn/Article/details/gtgrojzjri.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.quarkkingdee.top/Article/details/gtjmlsfmbp.html

[S55] C++：结构化绑定
来源：http://dali.cqqwz.cn/Article/details/gtssmfbybj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xziqi.cn/Article/details/gtebkbxfbu.html

[S56] C++：optional
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkikxaaq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gaohongyu789.top/Article/details/gttefgetqa.html

[S57] C++：编译期常量
来源：http://dali.sysykeji.top/Article/details/gtyijgfhvp.html

constexpr int N = 10;
来源：http://dali.gogol.net.cn/Article/details/gtmxnbwbmt.html

[S58] C++：命名空间
来源：http://dali.hywenlv.cn/Article/details/gtboklmddj.html

namespace ns { int f() { return 1; } }
来源：http://dali.tian-w.cn/Article/details/gtkipuvhqd.html

[S59] C++：静态断言
来源：http://dali.gotoacloud.top/Article/details/gteaeusotl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hysaishi.cn/Article/details/gtycjvrzdc.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlldkbpx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xylfe.cn/Article/details/gtqtuvkwmv.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gthqcxohzf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sxryk.cn/Article/details/gtbrunbhst.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtoixclggq.html

[T01] Kotlin：Hello World
来源：http://dali.meibo888.top/Article/details/gtidkjidcu.html

println("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtbwfpdmvm.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiezadmbo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zycfv.cn/Article/details/gtorprtvit.html

[T03] Kotlin：字符串模板
来源：http://dali.xinyue.icu/Article/details/gtfkjpddqt.html

"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gtdejzszsl.html

[T04] Kotlin：空安全
来源：http://dali.cqqwz.cn/Article/details/gttvtnfloa.html

val n: String? = null;  n?.length
来源：http://dali.yj202588.top/Article/details/gtvvixtaro.html

[T05] Kotlin：when 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtzrtwkoez.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sxryk.cn/Article/details/gteizxuech.html

[T06] Kotlin：集合映射
来源：http://dali.gzhubu.top/Article/details/gtunqafhuw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuanzx.com/Article/details/gtojjslkhi.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gtzgsyxjvl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yanxiufei.cn/Article/details/gtadwhakzn.html

[T08] Kotlin：数据类
来源：http://dali.sufxvd.cn/Article/details/gtejnsoqdu.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gtvievgrdu.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxinkj.top/Article/details/gtncxpgpan.html

fun String.exclaim() = this + "!"
来源：http://dali.yuxming.cn/Article/details/gtifngjmcc.html

[T10] Kotlin：默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gtufgmmrpu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cheryme.top/Article/details/gthxtdtoiw.html

[T11] Kotlin：协程
来源：http://dali.mhx1999.top/Article/details/gtrqwyicgx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.wangshuangyany.cn/Article/details/gtrofvnamq.html

[T12] Kotlin：解构声明
来源：http://dali.hnqzz.top/Article/details/gtfwrywxka.html

val (a, b) = Pair(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtdqnjrwyr.html

[T13] Kotlin：只读 Map
来源：http://dali.ehwqpu.com/Article/details/gtoaystwup.html

val m = mapOf("a" to 1)
来源：http://dali.cashguo.top/Article/details/gtdnwakqjx.html

[T14] Kotlin：循环
来源：http://dali.sweek.top/Article/details/gtdzbftodt.html

for (i in 1..10) println(i)
来源：http://dali.xylfe.cn/Article/details/gtecxtoexc.html

[T15] Kotlin：接口
来源：http://dali.jyoumei.cn/Article/details/gtppraehre.html

interface Shape { fun area(): Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxilievxm.html

[T16] Swift：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtvdebudub.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gttxtkjcjw.html

[T17] Swift：变量与常量
来源：http://dali.hnxiangtu.top/Article/details/gtivuxslxx.html

var a = 1;  let b = 2
来源：http://dali.guowangkeji.top/Article/details/gtappoyiga.html

[T18] Swift：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gtclocuuoe.html

"值: \(b)"
来源：http://dali.hywenlv.cn/Article/details/gtutqezuxy.html

[T19] Swift：可选绑定
来源：http://dali.cashguo.top/Article/details/gtlhacajmv.html

if let n = opt { print(n) }
来源：http://dali.316326.xyz/Article/details/gtilqaxeay.html

[T20] Swift：数组操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbpbmuwy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xuanzx.com/Article/details/gtehjgktdp.html

[T21] Swift：遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtgxrfseov.html

for x in a { print(x) }
来源：http://dali.nwbrower.top/Article/details/gtyplzcxhn.html

[T22] Swift：字典
来源：http://dali.shzxlz.cn/Article/details/gtqukcnref.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.havefunace.top/Article/details/gtkllrhlsk.html

[T23] Swift：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtupsxjwrw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cucudq.cn/Article/details/gtetyildja.html

[T24] Swift：闭包
来源：http://dali.ppjwa.cn/Article/details/gtsposziin.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuxming.cn/Article/details/gtzvcjmtzi.html

[T25] Swift：结构体
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrekxmdr.html

struct P { var x: Int }
来源：http://dali.ppjwa.cn/Article/details/gtezdvruyy.html

[T26] Swift：类与重写
来源：http://dali.yuanzhike.top/Article/details/gtlcfdrtgk.html

class A: Base { override func f() {} }
来源：http://dali.nwbrower.top/Article/details/gtptlipsib.html

[T27] Swift：错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqubpvwpy.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gtioaavpqy.html

[T28] Swift：枚举
来源：http://dali.ivvv.top/Article/details/gtzuznbtjx.html

enum Color { case red, green }
来源：http://dali.shzxlz.cn/Article/details/gtyhnxwzkt.html

[T29] Swift：guard 提前返回
来源：http://dali.yj202588.top/Article/details/gtphlqrdmq.html

guard let x = opt else { return }
来源：http://dali.zdqjudy.top/Article/details/gtenhvhxhe.html

[T30] Swift：协议
来源：http://dali.ehwqpu.com/Article/details/gtlwwbsdnt.html

protocol Shape { func area() -> Double }
来源：http://dali.cdnleiting.top/Article/details/gtmmworyyc.html

[T31] Lua：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtrikbzczk.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gtfrksgdhg.html

[T32] Lua：局部变量
来源：http://dali.0kj1m.cn/Article/details/gtbzsdbkfb.html

local a = 1
来源：http://dali.ppjwa.cn/Article/details/gtkkjrdcvq.html

[T33] Lua：表（数组）
来源：http://dali.yonumen.top/Article/details/gtewidascd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ppjwa.cn/Article/details/gtvrrbarhs.html

[T34] Lua：遍历表
来源：http://dali.yj20258.top/Article/details/gtknkrebsd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangdashe.top/Article/details/gtjhhuvave.html

[T35] Lua：字典表
来源：http://dali.jiagoushi.top/Article/details/gtksefusld.html

local d = { a = 1 };  d.b = 2
来源：http://dali.haohaochexian.top/Article/details/gtobcfjrdc.html

[T36] Lua：函数
来源：http://dali.gzhubu.top/Article/details/gtntwqpuai.html

function add(a, b) return a + b end
来源：http://dali.cucudq.cn/Article/details/gtpfkezkku.html

[T37] Lua：字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gtxkivzkov.html

"a" .. "b"
来源：http://dali.cucudq.cn/Article/details/gtwmlpgksg.html

[T38] Lua：条件
来源：http://dali.fengsongda.top/Article/details/gtiiucizdw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gtvsqtxtno.html

[T39] Lua：模式匹配
来源：http://dali.cqqwz.cn/Article/details/gtnaiqgfob.html

string.find(s, "%d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtibxcqnty.html

[T40] Lua：元表
来源：http://dali.xylfe.cn/Article/details/gtuyvmmefs.html

setmetatable({}, { __index = base })
来源：http://dali.gogol.net.cn/Article/details/gtxotfwhzm.html

[T41] Perl：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtfbcifqhh.html

print "Hello\n";
来源：http://dali.shuidangran.top/Article/details/gtwwjejntt.html

[T42] Perl：变量类型
来源：http://dali.sufxvd.cn/Article/details/gtfisrkhas.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hongshengwenyu.top/Article/details/gtfwdzfzgi.html

[T43] Perl：字符串插值
来源：http://dali.ivvv.top/Article/details/gtjutyetan.html

"值: $a"
来源：http://dali.cdnleiting.top/Article/details/gtproipmzi.html

[T44] Perl：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtogvhuyng.html

if ($a > 0) { print "正"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprohetcw.html

[T45] Perl：数组遍历
来源：http://dali.haohaochexian.top/Article/details/gttjpcvyep.html

for my $x (@arr) { print $x; }
来源：http://dali.birdmap.top/Article/details/gtcfmsbelf.html

[T46] Perl：哈希操作
来源：http://dali.zdqjudy.top/Article/details/gtndbbcauq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jqgfzy.top/Article/details/gtpzzeedpn.html

[T47] Perl：正则捕获
来源：http://dali.xinyue.icu/Article/details/gteylfnriv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvuhvdjgs.html

[T48] Perl：正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gtzabfepqb.html

$s =~ s/old/new/g;
来源：http://dali.jinqigfzy.top/Article/details/gtzsgbhoip.html

[T49] Perl：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtmfyvznyv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtszbawpmd.html

[T50] Perl：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtmtmwxxbd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.smart0.xyz/Article/details/gtuqciwvbm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fzhhl.top/Article/details/gtpldjqqrg.html

[T51] Scala：Hello World
来源：http://dali.havefunace.top/Article/details/gttojktdxn.html

println("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtiswcaxfj.html

[T52] Scala：变量
来源：http://dali.dianchejie.cn/Article/details/gtlzfgdabu.html

val a = 1;  var b = 2
来源：http://dali.redwolf501.top/Article/details/gtriuossvy.html

[T53] Scala：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gtanjwsfmm.html

s"值: $b"
来源：http://dali.guannengcc.top/Article/details/gtdemyuhxq.html

[T54] Scala：集合映射
来源：http://dali.snrcjt.cn/Article/details/gtxyoteyvj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.meibo888.top/Article/details/gticxdwodw.html

[T55] Scala：集合过滤
来源：http://dali.cheryme.top/Article/details/gtcxkfsvcz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ydzc1.top/Article/details/gtgenxazrl.html

[T56] Scala：样例类
来源：http://dali.sweek.top/Article/details/gtpenwlhqv.html

case class User(name: String, age: Int)
来源：http://dali.jianghu66.top/Article/details/gtcfjlhjwq.html

[T57] Scala：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gthmwvazjo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ybcxt.top/Article/details/gtblebgzwd.html

[T58] Scala：函数定义
来源：http://dali.316326.xyz/Article/details/gtnzycnkxw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jiagoushi.top/Article/details/gtziyamoab.html

[T59] Scala：循环
来源：http://dali.zhongyouzk.top/Article/details/gtnfvadzky.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj20258.top/Article/details/gtejujefmv.html

[T60] Scala：折叠
来源：http://dali.dashuyun.cn/Article/details/gtllcyulfx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.guowangkeji.top/Article/details/gtnjzrugcc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtswmyhebz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtnzsdpzgq.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtnvapneza.html

[U01] Py：创建虚拟环境
来源：http://dali.yangfankeji.com/Article/details/gtnwtwenfn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangdashe.top/Article/details/gtabifbcif.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhongyouzk.top/Article/details/gtumgijodt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgfzy.top/Article/details/gtlvclvzms.html

[U03] Py：加载 .env 配置
来源：http://dali.shangyingyoupin.top/Article/details/gtsrvtullh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.svipenyu.cn/Article/details/gtltbbltbm.html

[U04] Py：变量调试打印
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazuqwnyh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuetiantiany.cn/Article/details/gtafrjzbup.html

[U05] Py：列表去重且保序
来源：http://dali.tanke756.top/Article/details/gtcjhlwpwq.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gtnjjsvjlx.html

[U06] Py：合并两个字典
来源：http://dali.guannengcc.top/Article/details/gtgnvrwmbf.html

{**a, **b}
来源：http://dali.chenjidiqi.icu/Article/details/gtmhzydlpm.html

[U07] Py：反转字典键值
来源：http://dali.jiagoushi.top/Article/details/gtoncamyon.html

{v: k for k, v in d.items()}
来源：http://dali.yuxming.cn/Article/details/gthgvmnyjt.html

[U08] Py：展平二维列表
来源：http://dali.bjfxy.top/Article/details/gttlaqvwps.html

[y for x in nested for y in x]
来源：http://dali.ydzc1.top/Article/details/gtxqigdfmc.html

[U09] Py：字典取最大值的键
来源：http://dali.xziqi.cn/Article/details/gtxilbiacm.html

max(d, key=d.get)
来源：http://dali.bjfxy.top/Article/details/gtzeaaxccv.html

[U10] Py：按值排序字典
来源：http://dali.hnqzz.top/Article/details/gtovhtbcma.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj20258.top/Article/details/gtvoehfqdq.html

[U11] Py：生成器表达式
来源：http://dali.ppjwa.cn/Article/details/gthwcsyixd.html

(x * 2 for x in arr)
来源：http://dali.yj20258.top/Article/details/gtnqmplyij.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.vqdsnc.cn/Article/details/gtywltrfqp.html

Counter(arr).most_common(3)
来源：http://dali.birdmap.top/Article/details/gtmmltgoao.html

[U13] Py：固定长度队列
来源：http://dali.pycfn.com/Article/details/gtghyccfcv.html

deque(maxlen=10)
来源：http://dali.hongshengwenyu.top/Article/details/gtrfqcqtjt.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258888.top/Article/details/gtvvkclfmk.html

defaultdict(list)
来源：http://dali.yangfankeji.com/Article/details/gtmcrcqbou.html

[U15] Py：高精度计时
来源：http://dali.xinyue.icu/Article/details/gtklfixymr.html

t = time.perf_counter()
来源：http://dali.tanke756.top/Article/details/gtuhozgyhj.html

[U16] Py：命令行参数解析
来源：http://dali.xinyue.icu/Article/details/gtukyoetri.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.birdmap.top/Article/details/gttfwtjonr.html

[U17] Py：初始化日志
来源：http://dali.jqgufenzy.top/Article/details/gttijfimdd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yanxiufei.cn/Article/details/gtiatcfwlr.html

[U18] Py：预编译正则
来源：http://dali.9152youxi.cn/Article/details/gtdntwkgel.html

pat = re.compile(r"\d+")
来源：http://dali.havefunace.top/Article/details/gtichcrdzc.html

[U19] Py：正则替换带回调
来源：http://dali.zhengqikj.top/Article/details/gttcaglwwz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj20258.top/Article/details/gtdadztmnj.html

[U20] Py：缓存函数结果
来源：http://dali.hywenlv.cn/Article/details/gtdeqmosig.html

@functools.lru_cache(maxsize=None)
来源：http://dali.0kj1m.cn/Article/details/gtfozfbpdc.html

[U21] Py：自定义上下文管理器
来源：http://dali.fengsongda.top/Article/details/gtyjyxtohx.html

@contextlib.contextmanager
来源：http://dali.redwolf501.top/Article/details/gtyoxdewof.html

[U22] Py：矩阵转置
来源：http://dali.pengpengdd.cyou/Article/details/gtjeyujmlm.html

list(zip(*m))
来源：http://dali.xinyue.icu/Article/details/gtwhtckugi.html

[U23] Py：分块读取大文件
来源：http://dali.chenzaomai.com/Article/details/gtefqfiwrj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.bjfxy.top/Article/details/gtsfzqytmz.html

[U24] Py：路径操作
来源：http://dali.kuanghao11.cn/Article/details/gtfhvbxohx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gtvftcridc.html

[U25] Py：CSV 按字典读
来源：http://dali.zhongyouzk.top/Article/details/gtvmuankdz.html

csv.DictReader(f)
来源：http://dali.dashuyun.cn/Article/details/gtgvxehpnz.html

[U26] Py：并发下载
来源：http://dali.chenzaomai.com/Article/details/gtrjfyeamq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.316326.xyz/Article/details/gttltbxsup.html

[U27] Py：异步 HTTP
来源：http://dali.quarkkingdee.top/Article/details/gtecvvzfug.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenzaomai.com/Article/details/gtkocxlptm.html

[U28] Py：类型别名
来源：http://dali.yj202588.top/Article/details/gtgylhpmvx.html

UserId = int
来源：http://dali.dashuyun.cn/Article/details/gtvelekppm.html

[U29] Py：属性校验
来源：http://dali.nwbrower.top/Article/details/gtzgdglzka.html

@property 与 @x.setter 配合
来源：http://dali.tian-w.cn/Article/details/gtmywxsdwl.html

[U30] Py：数据类
来源：http://dali.kuanghao11.cn/Article/details/gtyvbpprkj.html

@dataclass(slots=True)
来源：http://dali.snrcjt.cn/Article/details/gtfzrirdtf.html

[U31] Py：单测
来源：http://dali.jianghu66.top/Article/details/gtovzvymdn.html

python -m pytest -q
来源：http://dali.pengpengdd.cyou/Article/details/gtvtfujtvs.html

[U32] Py：代码格式化
来源：http://dali.c1oappe.top/Article/details/gtwuofvtql.html

ruff format . && ruff check --fix .
来源：http://dali.wangdashe.top/Article/details/gtkucvsued.html

[U33] Py：打包发布
来源：http://dali.jinqigfzy.top/Article/details/gtxkikrtps.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yanxiufei.cn/Article/details/gtmygkqiyi.html

[U34] Py：判断编码
来源：http://dali.gaohongyu789.top/Article/details/gtetascahp.html

chardet.detect(raw)
来源：http://dali.ivvv.top/Article/details/gtoaganthg.html

[U35] Py：发送邮件
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlpnwnjr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.wangdashe.top/Article/details/gtpjtgpyat.html

[U36] Py：定时任务
来源：http://dali.birdmap.top/Article/details/gtjjffemaq.html

schedule.every(10).minutes.do(job)
来源：http://dali.chenjidiqi.icu/Article/details/gtzfgyoqbf.html

[U37] Py：读写 Excel
来源：http://dali.hnqzz.top/Article/details/gtszbetqsr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.svipenyu.cn/Article/details/gtcohhstla.html

[U38] Py：获取脚本所在目录
来源：http://dali.shangyingyoupin.top/Article/details/gtpnpxvkho.html

Path(__file__).resolve().parent
来源：http://dali.shzxlz.cn/Article/details/gtbalcezjx.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhengqikj.top/Article/details/gtrjxcodgt.html

sys.stdout.isatty()
来源：http://dali.yj20258888.top/Article/details/gtzqklnggn.html

[U40] Py：打印到标准错误
来源：http://dali.jqgfzy.top/Article/details/gthapbzucf.html

print("err", file=sys.stderr)
来源：http://dali.dianchejie.cn/Article/details/gtefnmdnxs.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.andypj.xyz/Article/details/gtxikaoyrn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.mhx1999.top/Article/details/gtxclxjgtt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yongpay.top/Article/details/gtqimylwfu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nanxinkj.top/Article/details/gtqoagemnq.html

[U43] PHP：声明命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsftkiuks.html

namespace App\Http;
来源：http://dali.xziqi.cn/Article/details/gtcuxbexpi.html

[U44] PHP：开启严格类型
来源：http://dali.feifeiyinyue.top/Article/details/gtbmtnumqx.html

declare(strict_types=1);
来源：http://dali.nanxuanxn.top/Article/details/gtdavcyuvx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.sufxvd.cn/Article/details/gtzfmpotcn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtahzomdqe.html

[U46] PHP：可空类型
来源：http://dali.hongshengwenyu.top/Article/details/gtnmogkrsj.html

?string $name = null
来源：http://dali.smart0.xyz/Article/details/gtfomgarug.html

[U47] PHP：联合类型
来源：http://dali.jinqigufen.top/Article/details/gtehudnpai.html

int|string $id
来源：http://dali.sysykeji.top/Article/details/gtyrekhrwe.html

[U48] PHP：纯枚举
来源：http://dali.gogol.net.cn/Article/details/gtdjovnbwl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhixingplan.top/Article/details/gtfgnyywwv.html

[U49] PHP：只读属性
来源：http://dali.ivvv.top/Article/details/gtvwywmtvp.html

public readonly string $name
来源：http://dali.nanxinkj.top/Article/details/gtyuagxjoz.html

[U50] PHP：构造器属性提升
来源：http://dali.sweek.top/Article/details/gtxubavafc.html

public function __construct(private int $id) {}
来源：http://dali.dianchejie.cn/Article/details/gtbnaygyin.html

[U51] PHP：数组解构
来源：http://dali.yangfankeji.com/Article/details/gtttolnzdc.html

[$a, $b] = $arr;
来源：http://dali.vqdsnc.cn/Article/details/gtbvobqwqu.html

[U52] PHP：箭头函数
来源：http://dali.chenzaomai.com/Article/details/gttpbfnriy.html

$double = fn($x) => $x * 2;
来源：http://dali.jianghu66.top/Article/details/gtosasjgoi.html

[U53] PHP：空合并运算符
来源：http://dali.cucudq.cn/Article/details/gthuchwgpe.html

$v = $a ?? $b ?? "default";
来源：http://dali.aizwys.cn/Article/details/gtvygiptff.html

[U54] PHP：空安全调用
来源：http://dali.xylfe.cn/Article/details/gtmoizrorm.html

$obj?->method()
来源：http://dali.hnqzz.top/Article/details/gtpqrmzpkd.html

[U55] PHP：match 表达式
来源：http://dali.yj20258.top/Article/details/gtzbrzxuir.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.chenjidiqi.icu/Article/details/gtbsqyhnyw.html

[U56] PHP：命名参数
来源：http://dali.cheryme.top/Article/details/gtivrxvoit.html

f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gtwhpwdpsl.html

[U57] PHP：字符串插值
来源：http://dali.smart0.xyz/Article/details/gtmgxuskgt.html

"值: {$a}"
来源：http://dali.daxiang520.top/Article/details/gtiqnqbkft.html

[U58] PHP：数组三件套
来源：http://dali.dianchejie.cn/Article/details/gtgujdyenq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtonamrgeo.html

[U59] PHP：自定义排序
来源：http://dali.xuetiantiany.cn/Article/details/gtjkazdpbv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gtxjqvnjio.html

[U60] PHP：JSON 编解码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuolndvvn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.dianchejie.cn/Article/details/gtfccqnaru.html

[U61] PHP：正则
来源：http://dali.snrcjt.cn/Article/details/gtdfrbiahg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ppjwa.cn/Article/details/gtpylkjspz.html

[U62] PHP：日期对象
来源：http://dali.gzhubu.top/Article/details/gtimgdjnne.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.quarkkingdee.top/Article/details/gtqtzuhcmj.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gtuarizoot.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.mhx1999.top/Article/details/gtrhlepsdu.html

[U64] PHP：目录遍历
来源：http://dali.fzhhl.top/Article/details/gtllgjogbg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jianghu66.top/Article/details/gtgebqebsz.html

[U65] PHP：会话
来源：http://dali.kuanghao11.cn/Article/details/gtoaxdayek.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtyjmvvduv.html

[U66] PHP：设置 Cookie
来源：http://dali.svipenyu.cn/Article/details/gtmbfmufoz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sxryk.cn/Article/details/gtotkurtyw.html

[U67] PHP：处理文件上传
来源：http://dali.meibo888.top/Article/details/gtupctjlfd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sufxvd.cn/Article/details/gtethpnawi.html

[U68] PHP：PDO 连接
来源：http://dali.andypj.xyz/Article/details/gteglegghd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.smart0.xyz/Article/details/gtvzzzivyf.html

[U69] PHP：PDO 预处理
来源：http://dali.tanke756.top/Article/details/gttugtxffk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jqgufenzy.top/Article/details/gtrdkyverf.html

[U70] PHP：PDO 事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjqoppql.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.fzhhl.top/Article/details/gtwcfbnlup.html

[U71] PHP：抛出异常
来源：http://dali.chenzaomai.com/Article/details/gtlehzvjzt.html

throw new RuntimeException("失败", 500);
来源：http://dali.fengsongda.top/Article/details/gtqegfcnjm.html

[U72] PHP：写错误日志
来源：http://dali.cdnleiting.top/Article/details/gteufkjugg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.aibaodan.cn/Article/details/gtlzbzonyn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zycfv.cn/Article/details/gtfmoskgsd.html

parse_ini_file("config.ini", true)
来源：http://dali.jyoumei.cn/Article/details/gtgzrbpung.html

[U74] PHP：读取环境变量
来源：http://dali.jqgufenzy.top/Article/details/gtntmemuoj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.svipenyu.cn/Article/details/gtolauurwo.html

[U75] PHP：依赖注入
来源：http://dali.yj20258.top/Article/details/gttlelhdom.html

composer require psr/container
来源：http://dali.cheryme.top/Article/details/gtqoyivfct.html

[U76] PHP：简单路由
来源：http://dali.tianlin.xyz/Article/details/gtmbpttxtm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xuetiantiany.cn/Article/details/gtxvvlqskl.html

[U77] PHP：模板渲染
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqvqphez.html

composer require twig/twig
来源：http://dali.svipenyu.cn/Article/details/gtgyykhsix.html

[U78] PHP：单元测试
来源：http://dali.hnxiangtu.top/Article/details/gtydcxfiyt.html

composer require --dev phpunit/phpunit
来源：http://dali.sysykeji.top/Article/details/gtixhyplsa.html


<!-- 参考信息 -->