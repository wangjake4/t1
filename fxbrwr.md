代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtwxidzuyx.html

[S59] C++：静态断言
来源：http://dali.bjfxy.top/Article/details/gtgpwpfifb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.andypj.xyz/Article/details/gtkvoanmdv.html

[S60] C++：遍历并删除元素
来源：http://dali.yonumen.top/Article/details/gtuejrtnso.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hnqzz.top/Article/details/gtaxgvieup.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtnvrlvsyq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhongyouzk.top/Article/details/gtwynnronc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtwffzoeta.html

[T01] Kotlin：Hello World
来源：http://dali.aibaodan.cn/Article/details/gttefdwssu.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gteirrkjsu.html

[T02] Kotlin：变量
来源：http://dali.0kj1m.cn/Article/details/gtsjtqfcbt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yangfankeji.com/Article/details/gtseinemfd.html

[T03] Kotlin：字符串模板
来源：http://dali.mhx1999.top/Article/details/gtzkfhxnhj.html

"值: $b"
来源：http://dali.hammf.cn/Article/details/gtmxkrbyfa.html

[T04] Kotlin：空安全
来源：http://dali.xinyue.icu/Article/details/gtdimoguvr.html

val n: String? = null;  n?.length
来源：http://dali.gzhubu.top/Article/details/gtpmeuntjl.html

[T05] Kotlin：when 表达式
来源：http://dali.sufxvd.cn/Article/details/gtuodhsyqk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yonumen.top/Article/details/gtjhibekxs.html

[T06] Kotlin：集合映射
来源：http://dali.xziqi.cn/Article/details/gttjjikvvk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtulbuwchw.html

[T07] Kotlin：集合过滤
来源：http://dali.zycfv.cn/Article/details/gtilvdeblp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gtibvuakch.html

[T08] Kotlin：数据类
来源：http://dali.xziqi.cn/Article/details/gtwyotwbhh.html

data class User(val name: String, val age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gtjrjwnbjk.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgufenzy.top/Article/details/gtclcqfnym.html

fun String.exclaim() = this + "!"
来源：http://dali.zhongyouzk.top/Article/details/gtumipzahf.html

[T10] Kotlin：默认参数
来源：http://dali.guannengcc.top/Article/details/gtxenfjtfk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yonumen.top/Article/details/gtopqanggs.html

[T11] Kotlin：协程
来源：http://dali.snrcjt.cn/Article/details/gtpirkhblx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgufenzy.top/Article/details/gtebrqkbqf.html

[T12] Kotlin：解构声明
来源：http://dali.dianchejie.cn/Article/details/gtpfkbmsbv.html

val (a, b) = Pair(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtipnozfsv.html

[T13] Kotlin：只读 Map
来源：http://dali.yongpay.top/Article/details/gtgesceelo.html

val m = mapOf("a" to 1)
来源：http://dali.316326.xyz/Article/details/gtgtcydnft.html

[T14] Kotlin：循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajsljrmr.html

for (i in 1..10) println(i)
来源：http://dali.yuxming.cn/Article/details/gtmssjyrrf.html

[T15] Kotlin：接口
来源：http://dali.dianchejie.cn/Article/details/gtjbixlsmb.html

interface Shape { fun area(): Double }
来源：http://dali.yuanzhike.top/Article/details/gtarmwykjg.html

[T16] Swift：Hello World
来源：http://dali.wangdashe.top/Article/details/gtxiqqsnyu.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gtuzsgcemp.html

[T17] Swift：变量与常量
来源：http://dali.andypj.xyz/Article/details/gtunytqtsm.html

var a = 1;  let b = 2
来源：http://dali.jqgufenzy.top/Article/details/gtemomiasi.html

[T18] Swift：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtysmclytd.html

"值: \(b)"
来源：http://dali.yanxiufei.cn/Article/details/gtzpzkthhm.html

[T19] Swift：可选绑定
来源：http://dali.birdmap.top/Article/details/gtpmnnybtm.html

if let n = opt { print(n) }
来源：http://dali.jinqigfzy.top/Article/details/gtignzsvkc.html

[T20] Swift：数组操作
来源：http://dali.yangfankeji.com/Article/details/gtmfxclfcy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hfpthk.cn/Article/details/gteledyuog.html

[T21] Swift：遍历
来源：http://dali.zhixingplan.top/Article/details/gtqymjfobf.html

for x in a { print(x) }
来源：http://dali.pycfn.com/Article/details/gtvsmzbtkr.html

[T22] Swift：字典
来源：http://dali.dashuyun.cn/Article/details/gtpovbxwql.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.bjfxy.top/Article/details/gtejaznues.html

[T23] Swift：函数
来源：http://dali.cdnleiting.top/Article/details/gtkqrrbqib.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhongyouzk.top/Article/details/gtlgenjxuz.html

[T24] Swift：闭包
来源：http://dali.jqgufenzy.top/Article/details/gtfpiruyvs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtrodinxki.html

[T25] Swift：结构体
来源：http://dali.sysykeji.top/Article/details/gtfghtikfx.html

struct P { var x: Int }
来源：http://dali.gogol.net.cn/Article/details/gtkzxovuww.html

[T26] Swift：类与重写
来源：http://dali.sweek.top/Article/details/gtvqbuljhp.html

class A: Base { override func f() {} }
来源：http://dali.redwolf501.top/Article/details/gtzjunttxe.html

[T27] Swift：错误处理
来源：http://dali.tian-w.cn/Article/details/gtcetmvhuj.html

do { try f() } catch { print(error) }
来源：http://dali.xuetiantiany.cn/Article/details/gtjkvmamgk.html

[T28] Swift：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtwjreyabl.html

enum Color { case red, green }
来源：http://dali.birdmap.top/Article/details/gtafsvntth.html

[T29] Swift：guard 提前返回
来源：http://dali.haohaochexian.top/Article/details/gtbagnaqmq.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gtkiuvhfcd.html

[T30] Swift：协议
来源：http://dali.jlsjyb.cn/Article/details/gteeagnrod.html

protocol Shape { func area() -> Double }
来源：http://dali.hongshengwenyu.top/Article/details/gtlkgywjye.html

[T31] Lua：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtckkfkefq.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdstaydk.html

[T32] Lua：局部变量
来源：http://dali.chenzaomai.com/Article/details/gtplmtgpwx.html

local a = 1
来源：http://dali.cashguo.top/Article/details/gtrtjqzxmq.html

[T33] Lua：表（数组）
来源：http://dali.tian-w.cn/Article/details/gthqfqdgjb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.c1oappe.top/Article/details/gtofxtyavb.html

[T34] Lua：遍历表
来源：http://dali.cdnleiting.top/Article/details/gtbxmmrlls.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guannengcc.top/Article/details/gtigfsbmya.html

[T35] Lua：字典表
来源：http://dali.zycfv.cn/Article/details/gtjympwdps.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpgdwpry.html

[T36] Lua：函数
来源：http://dali.zdqjudy.top/Article/details/gtodkjvlox.html

function add(a, b) return a + b end
来源：http://dali.xylfe.cn/Article/details/gtjlsnkofc.html

[T37] Lua：字符串拼接
来源：http://dali.c1oappe.top/Article/details/gtdoowddyo.html

"a" .. "b"
来源：http://dali.smart0.xyz/Article/details/gtdnyzkbee.html

[T38] Lua：条件
来源：http://dali.cdnleiting.top/Article/details/gtrevkgoav.html

if x > 0 then print("正") end
来源：http://dali.tanke756.top/Article/details/gtghayybss.html

[T39] Lua：模式匹配
来源：http://dali.jyoumei.cn/Article/details/gtknpuqxxv.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwszsbyhx.html

[T40] Lua：元表
来源：http://dali.havefunace.top/Article/details/gtrldxoikc.html

setmetatable({}, { __index = base })
来源：http://dali.nanxinkj.top/Article/details/gtedasqfyv.html

[T41] Perl：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtgbcnssly.html

print "Hello\n";
来源：http://dali.guannengcc.top/Article/details/gtulooeiwo.html

[T42] Perl：变量类型
来源：http://dali.tian-w.cn/Article/details/gtqzolhzye.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.haohaochexian.top/Article/details/gtwutrzvgq.html

[T43] Perl：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtjllrqxmd.html

"值: $a"
来源：http://dali.jqgfzy.top/Article/details/gtbvnnldqz.html

[T44] Perl：条件
来源：http://dali.bjfxy.top/Article/details/gtbqhmgxob.html

if ($a > 0) { print "正"; }
来源：http://dali.jqgfzy.top/Article/details/gtswgjgipf.html

[T45] Perl：数组遍历
来源：http://dali.xylfe.cn/Article/details/gtoqihpnbz.html

for my $x (@arr) { print $x; }
来源：http://dali.iojbl.cn/Article/details/gtrinabbrl.html

[T46] Perl：哈希操作
来源：http://dali.tianlin.xyz/Article/details/gtwtstnicy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.birdmap.top/Article/details/gtoqvljxrb.html

[T47] Perl：正则捕获
来源：http://dali.cqqwz.cn/Article/details/gtkzoozscd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daxiang520.top/Article/details/gtgoonszrl.html

[T48] Perl：正则替换
来源：http://dali.xuanzx.com/Article/details/gtvfrkgelp.html

$s =~ s/old/new/g;
来源：http://dali.ivvv.top/Article/details/gtvaqfpdrr.html

[T49] Perl：函数
来源：http://dali.hysaishi.cn/Article/details/gtkwxdfxpa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtiaiwhlga.html

[T50] Perl：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtufozenle.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jianghu66.top/Article/details/gtqibgupiz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhixingplan.top/Article/details/gttcodfqya.html

[T51] Scala：Hello World
来源：http://dali.xziqi.cn/Article/details/gtxxtpkefi.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gtrbqreksc.html

[T52] Scala：变量
来源：http://dali.haohaochexian.top/Article/details/gtngmlsltg.html

val a = 1;  var b = 2
来源：http://dali.cucudq.cn/Article/details/gteimusons.html

[T53] Scala：字符串插值
来源：http://dali.ydzc1.top/Article/details/gttpyzzlcm.html

s"值: $b"
来源：http://dali.redwolf501.top/Article/details/gtgesyvapz.html

[T54] Scala：集合映射
来源：http://dali.nanxuanxn.top/Article/details/gtpcamiwck.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnthqewtu.html

[T55] Scala：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtsdovrtvh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gogol.net.cn/Article/details/gtispwznbn.html

[T56] Scala：样例类
来源：http://dali.xylfe.cn/Article/details/gtethqeino.html

case class User(name: String, age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcihslepf.html

[T57] Scala：模式匹配
来源：http://dali.ybcxt.top/Article/details/gtuzojvpvf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.redwolf501.top/Article/details/gtahqkipsl.html

[T58] Scala：函数定义
来源：http://dali.chenzaomai.com/Article/details/gtrcrfivwz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jyoumei.cn/Article/details/gtudyrtrdp.html

[T59] Scala：循环
来源：http://dali.shuidangran.top/Article/details/gttbjqiegs.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsejwsar.html

[T60] Scala：折叠
来源：http://dali.quarkkingdee.top/Article/details/gtoatubmqh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ybcxt.top/Article/details/gtlzkgpazz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtqjnbpcol.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cqqwz.cn/Article/details/gtwivgildi.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtkyjhhojq.html

[U01] Py：创建虚拟环境
来源：http://dali.jlsjyb.cn/Article/details/gtwtauocws.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zdqjudy.top/Article/details/gtiobualai.html

[U02] Py：导出 / 安装依赖
来源：http://dali.wangshuangyany.cn/Article/details/gtvhjpjqqk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sufxvd.cn/Article/details/gtlffkfuoo.html

[U03] Py：加载 .env 配置
来源：http://dali.zycfv.cn/Article/details/gtkkiwtapu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ivvv.top/Article/details/gtccyowdzm.html

[U04] Py：变量调试打印
来源：http://dali.snrcjt.cn/Article/details/gtgrsrmgbo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.meibo888.top/Article/details/gtjsyqjvsp.html

[U05] Py：列表去重且保序
来源：http://dali.sufxvd.cn/Article/details/gtaqwxfugz.html

list(dict.fromkeys(arr))
来源：http://dali.redwolf501.top/Article/details/gtcnkvemgs.html

[U06] Py：合并两个字典
来源：http://dali.gogol.net.cn/Article/details/gtlteuisah.html

{**a, **b}
来源：http://dali.c1oappe.top/Article/details/gtwlthwogl.html

[U07] Py：反转字典键值
来源：http://dali.hongshengwenyu.top/Article/details/gtudhxuslh.html

{v: k for k, v in d.items()}
来源：http://dali.0kj1m.cn/Article/details/gtxpyixwzp.html

[U08] Py：展平二维列表
来源：http://dali.jinqigfzy.top/Article/details/gttyhupvyg.html

[y for x in nested for y in x]
来源：http://dali.xuanzx.com/Article/details/gtajjiffwt.html

[U09] Py：字典取最大值的键
来源：http://dali.hywenlv.cn/Article/details/gthzwzphyu.html

max(d, key=d.get)
来源：http://dali.kuanghao11.cn/Article/details/gtlrmgvcvj.html

[U10] Py：按值排序字典
来源：http://dali.dashuyun.cn/Article/details/gtxkioswbc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ehwqpu.com/Article/details/gtsaolxfae.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcmlcbts.html

(x * 2 for x in arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpjkqszs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.dianchejie.cn/Article/details/gtirpitkgx.html

Counter(arr).most_common(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtmbanujjq.html

[U13] Py：固定长度队列
来源：http://dali.redwolf501.top/Article/details/gtoefwmgsj.html

deque(maxlen=10)
来源：http://dali.zycfv.cn/Article/details/gtlfqlbnxp.html

[U14] Py：分组收集到列表
来源：http://dali.hnqzz.top/Article/details/gtuzhjfben.html

defaultdict(list)
来源：http://dali.quarkkingdee.top/Article/details/gtultqdahf.html

[U15] Py：高精度计时
来源：http://dali.aizwys.cn/Article/details/gtmayjpply.html

t = time.perf_counter()
来源：http://dali.jqgufenzy.top/Article/details/gtbmkjfosh.html

[U16] Py：命令行参数解析
来源：http://dali.fengsongda.top/Article/details/gtqbmtvove.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.snrcjt.cn/Article/details/gtorlaogez.html

[U17] Py：初始化日志
来源：http://dali.cucudq.cn/Article/details/gtfoclmcgg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hysaishi.cn/Article/details/gtpfgteqfo.html

[U18] Py：预编译正则
来源：http://dali.hfpthk.cn/Article/details/gtjsgefmps.html

pat = re.compile(r"\d+")
来源：http://dali.hywenlv.cn/Article/details/gtizckdeav.html

[U19] Py：正则替换带回调
来源：http://dali.sysykeji.top/Article/details/gtrgadooci.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.9152youxi.cn/Article/details/gtwsfwdwhq.html

[U20] Py：缓存函数结果
来源：http://dali.zhiwuduotai.top/Article/details/gtzkyvroyp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jianghu66.top/Article/details/gtfjpdvrau.html

[U21] Py：自定义上下文管理器
来源：http://dali.aibaodan.cn/Article/details/gtwrpmddrt.html

@contextlib.contextmanager
来源：http://dali.sweek.top/Article/details/gtexgnzprw.html

[U22] Py：矩阵转置
来源：http://dali.jqgfzy.top/Article/details/gtmxvqwpum.html

list(zip(*m))
来源：http://dali.sweek.top/Article/details/gtxszzwcfh.html

[U23] Py：分块读取大文件
来源：http://dali.sysykeji.top/Article/details/gtpktumqvt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tian-w.cn/Article/details/gthoxbaydy.html

[U24] Py：路径操作
来源：http://dali.yongpay.top/Article/details/gtycarckvv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gtcspyaggq.html

[U25] Py：CSV 按字典读
来源：http://dali.zdqjudy.top/Article/details/gtjfwvpsic.html

csv.DictReader(f)
来源：http://dali.yvedp.cn/Article/details/gtdcmfmxwg.html

[U26] Py：并发下载
来源：http://dali.zhiwuduotai.top/Article/details/gtyatlgqcy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.kuanghao11.cn/Article/details/gtgfutljxg.html

[U27] Py：异步 HTTP
来源：http://dali.yanxiufei.cn/Article/details/gtzuiqqwjo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.svipenyu.cn/Article/details/gtcorkcvbx.html

[U28] Py：类型别名
来源：http://dali.sweek.top/Article/details/gtraissfoa.html

UserId = int
来源：http://dali.jiagoushi.top/Article/details/gtrlgpvbly.html

[U29] Py：属性校验
来源：http://dali.ybcxt.top/Article/details/gtrvbsbbng.html

@property 与 @x.setter 配合
来源：http://dali.pengpengdd.cyou/Article/details/gtzobbgtrb.html

[U30] Py：数据类
来源：http://dali.jlsjyb.cn/Article/details/gtpogwfxit.html

@dataclass(slots=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtwhfkqxwt.html

[U31] Py：单测
来源：http://dali.yj20258888.top/Article/details/gtnqambann.html

python -m pytest -q
来源：http://dali.aizwys.cn/Article/details/gtqbrajbnb.html

[U32] Py：代码格式化
来源：http://dali.jqgufenzy.top/Article/details/gtsreglgcl.html

ruff format . && ruff check --fix .
来源：http://dali.jinghuilouyu.cn/Article/details/gtuuziltmd.html

[U33] Py：打包发布
来源：http://dali.smart0.xyz/Article/details/gtfihciwgq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwilyxud.html

[U34] Py：判断编码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayhavzct.html

chardet.detect(raw)
来源：http://dali.zdqjudy.top/Article/details/gtxxcmzboa.html

[U35] Py：发送邮件
来源：http://dali.kuanghao11.cn/Article/details/gtjfrayptk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ppjwa.cn/Article/details/gtexwgiefu.html

[U36] Py：定时任务
来源：http://dali.daxiang520.top/Article/details/gtmixynwga.html

schedule.every(10).minutes.do(job)
来源：http://dali.sweek.top/Article/details/gtmnrovmdk.html

[U37] Py：读写 Excel
来源：http://dali.jlsjyb.cn/Article/details/gtsirvmgva.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yongpay.top/Article/details/gtwfdhswif.html

[U38] Py：获取脚本所在目录
来源：http://dali.gogol.net.cn/Article/details/gthslhbncf.html

Path(__file__).resolve().parent
来源：http://dali.cqqwz.cn/Article/details/gtvlustdmg.html

[U39] Py：判断是否在交互环境
来源：http://dali.fzhhl.top/Article/details/gtvyxnypdb.html

sys.stdout.isatty()
来源：http://dali.chenlongwang.top/Article/details/gtmuoposlg.html

[U40] Py：打印到标准错误
来源：http://dali.yonumen.top/Article/details/gtrldazbiv.html

print("err", file=sys.stderr)
来源：http://dali.yonumen.top/Article/details/gttaanixps.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.aizwys.cn/Article/details/gtgakrkwzl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hammf.cn/Article/details/gtfgrozcdg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jyoumei.cn/Article/details/gtpvvhdedv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtshxxuddn.html

[U43] PHP：声明命名空间
来源：http://dali.316326.xyz/Article/details/gtlphyylwd.html

namespace App\Http;
来源：http://dali.hammf.cn/Article/details/gtfgtzmctp.html

[U44] PHP：开启严格类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtnubddowb.html

declare(strict_types=1);
来源：http://dali.dianchejie.cn/Article/details/gtqhulhatc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhongyouzk.top/Article/details/gtvtkjuynr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtpxjwrope.html

[U46] PHP：可空类型
来源：http://dali.xuetiantiany.cn/Article/details/gtyjwwabpm.html

?string $name = null
来源：http://dali.shuidangran.top/Article/details/gtnbzwaegt.html

[U47] PHP：联合类型
来源：http://dali.kuanghao11.cn/Article/details/gtxcyoagtb.html

int|string $id
来源：http://dali.xziqi.cn/Article/details/gtvsipuvuq.html

[U48] PHP：纯枚举
来源：http://dali.quarkkingdee.top/Article/details/gtqdenmcre.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.andypj.xyz/Article/details/gtknrhjrug.html

[U49] PHP：只读属性
来源：http://dali.0kj1m.cn/Article/details/gtszsejnsr.html

public readonly string $name
来源：http://dali.sysykeji.top/Article/details/gtrwjbliqb.html

[U50] PHP：构造器属性提升
来源：http://dali.snrcjt.cn/Article/details/gtpmxcnegv.html

public function __construct(private int $id) {}
来源：http://dali.fzhhl.top/Article/details/gtjkftsptv.html

[U51] PHP：数组解构
来源：http://dali.ppjwa.cn/Article/details/gtzhslmiuz.html

[$a, $b] = $arr;
来源：http://dali.jianghu66.top/Article/details/gtzlmnojpf.html

[U52] PHP：箭头函数
来源：http://dali.xylfe.cn/Article/details/gtnhsahsso.html

$double = fn($x) => $x * 2;
来源：http://dali.kuanghao11.cn/Article/details/gtjpywjdok.html

[U53] PHP：空合并运算符
来源：http://dali.cqqwz.cn/Article/details/gtwulfecbd.html

$v = $a ?? $b ?? "default";
来源：http://dali.wangshuangyany.cn/Article/details/gtoeevynbd.html

[U54] PHP：空安全调用
来源：http://dali.zhengqikj.top/Article/details/gtteamenue.html

$obj?->method()
来源：http://dali.c1oappe.top/Article/details/gtlkoncigf.html

[U55] PHP：match 表达式
来源：http://dali.guannengcc.top/Article/details/gttsfdptkj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jqgufenzy.top/Article/details/gtqhuqmclo.html

[U56] PHP：命名参数
来源：http://dali.cdnleiting.top/Article/details/gtmoghcbwz.html

f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtkrjosioz.html

[U57] PHP：字符串插值
来源：http://dali.meibo888.top/Article/details/gteksibjkj.html

"值: {$a}"
来源：http://dali.meibo888.top/Article/details/gtunfizfkj.html

[U58] PHP：数组三件套
来源：http://dali.ivvv.top/Article/details/gtwwlukkep.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtjmliifxp.html

[U59] PHP：自定义排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrroacctd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daria6918.cn/Article/details/gtkjccqcvf.html

[U60] PHP：JSON 编解码
来源：http://dali.yj20258.top/Article/details/gtjubgnmpr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hammf.cn/Article/details/gtsjqkzitv.html

[U61] PHP：正则
来源：http://dali.smart0.xyz/Article/details/gtnpggdjup.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtgbreljgj.html

[U62] PHP：日期对象
来源：http://dali.jianghu66.top/Article/details/gtnppoddyg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hysaishi.cn/Article/details/gtxdwzebai.html

[U63] PHP：文件读写
来源：http://dali.hongshengwenyu.top/Article/details/gtaxxrwqey.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cheryme.top/Article/details/gtyhdzesyq.html

[U64] PHP：目录遍历
来源：http://dali.0kj1m.cn/Article/details/gtolceyxcp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jlsjyb.cn/Article/details/gtpbkfhuky.html

[U65] PHP：会话
来源：http://dali.pycfn.com/Article/details/gtivljpctc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtqunklpja.html

[U66] PHP：设置 Cookie
来源：http://dali.svipenyu.cn/Article/details/gtxkatkjyx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hywenlv.cn/Article/details/gtiblptnjk.html

[U67] PHP：处理文件上传
来源：http://dali.yuxming.cn/Article/details/gtttxwuaki.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yonumen.top/Article/details/gtqidftyqr.html

[U68] PHP：PDO 连接
来源：http://dali.0kj1m.cn/Article/details/gtyrrfhyek.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xuetiantiany.cn/Article/details/gtyirurqyz.html

[U69] PHP：PDO 预处理
来源：http://dali.hammf.cn/Article/details/gtjavwdfpv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yuanzhike.top/Article/details/gtsplhxbvo.html

[U70] PHP：PDO 事务
来源：http://dali.hnqzz.top/Article/details/gtqqcnaqga.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvuelehv.html

[U71] PHP：抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzcjapjh.html

throw new RuntimeException("失败", 500);
来源：http://dali.jqgfzy.top/Article/details/gtaafkkmew.html

[U72] PHP：写错误日志
来源：http://dali.hongshengwenyu.top/Article/details/gtkuyogwme.html

error_log("失败: " . $e->getMessage());
来源：http://dali.quarkkingdee.top/Article/details/gtlzyrizqw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhiwuduotai.top/Article/details/gtitxoknck.html

parse_ini_file("config.ini", true)
来源：http://dali.cashguo.top/Article/details/gtdqizyewo.html

[U74] PHP：读取环境变量
来源：http://dali.yonumen.top/Article/details/gtlsgeptmd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinghuilouyu.cn/Article/details/gtubbgydml.html

[U75] PHP：依赖注入
来源：http://dali.ppjwa.cn/Article/details/gtkxfrwkvb.html

composer require psr/container
来源：http://dali.chenzaomai.com/Article/details/gtylcslrpn.html

[U76] PHP：简单路由
来源：http://dali.xziqi.cn/Article/details/gtolpxhvaa.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shuidangran.top/Article/details/gtzusnhxkp.html

[U77] PHP：模板渲染
来源：http://dali.gotoacloud.top/Article/details/gtjgazlsaz.html

composer require twig/twig
来源：http://dali.iojbl.cn/Article/details/gttwmyxwsi.html

[U78] PHP：单元测试
来源：http://dali.dianchejie.cn/Article/details/gtywfqdmmu.html

composer require --dev phpunit/phpunit
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwgcbioi.html

[U79] PHP：静态分析
来源：http://dali.gaohongyu789.top/Article/details/gtfnvnrlbm.html

composer require --dev phpstan/phpstan
来源：http://dali.316326.xyz/Article/details/gtjlawfcwx.html

[U80] PHP：代码规范修复
来源：http://dali.tanke756.top/Article/details/gtgofyvear.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yj202588.top/Article/details/gtmfgdoxnl.html

[U81] JS：初始化项目
来源：http://dali.c1oappe.top/Article/details/gtoqhwiysg.html

npm init -y;  npm i express
来源：http://dali.yj202588.top/Article/details/gtcsngezio.html

[U82] JS：package.json 脚本
来源：http://dali.mhx1999.top/Article/details/gtrrzkercq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.guannengcc.top/Article/details/gtmtyfgsrs.html

[U83] JS：ES Module 导入导出
来源：http://dali.gaohongyu789.top/Article/details/gtigiimdbi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwcxbvlw.html

[U84] JS：CommonJS 写法
来源：http://dali.pengpengdd.cyou/Article/details/gtcmpkxaug.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.0kj1m.cn/Article/details/gtudgypwuy.html


<!-- 参考信息 -->