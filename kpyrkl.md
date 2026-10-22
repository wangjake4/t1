代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.c1oappe.top/Article/details/gt2mgxopzof.html

[S59] C++：静态断言
来源：http://dali.hammf.cn/Article/details/gt2ohflojrb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ivvv.top/Article/details/gt2khbvkupg.html

[S60] C++：遍历并删除元素
来源：http://dali.dianchejie.cn/Article/details/gt2vpvcmlpu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ybcxt.top/Article/details/gt2luryfmgh.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2kegkgirc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuanzhike.top/Article/details/gt2wlqxfdcf.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2pnzdzidw.html

[T01] Kotlin：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2etervmzp.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gt2hleblgcl.html

[T02] Kotlin：变量
来源：http://dali.9152youxi.cn/Article/details/gt2swqdkedb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuxming.cn/Article/details/gt2fgyrqbmx.html

[T03] Kotlin：字符串模板
来源：http://dali.yj20258.top/Article/details/gt2rfejzwgt.html

"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gt2wamcpzli.html

[T04] Kotlin：空安全
来源：http://dali.yonumen.top/Article/details/gt2boxqwvfj.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gt2pcftjlua.html

[T05] Kotlin：when 表达式
来源：http://dali.zdqjudy.top/Article/details/gt2xsxvyhiz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hfpthk.cn/Article/details/gt2dujaaqlw.html

[T06] Kotlin：集合映射
来源：http://dali.ydzc1.top/Article/details/gt2avhabcyz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2gdqfsowd.html

[T07] Kotlin：集合过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2pteufoqs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhixingplan.top/Article/details/gt2morrxcvg.html

[T08] Kotlin：数据类
来源：http://dali.ivvv.top/Article/details/gt2zzfvvwgr.html

data class User(val name: String, val age: Int)
来源：http://dali.havefunace.top/Article/details/gt2ptjpypst.html

[T09] Kotlin：扩展函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2skfqcsqj.html

fun String.exclaim() = this + "!"
来源：http://dali.svipenyu.cn/Article/details/gt2pbxyrvoi.html

[T10] Kotlin：默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2edivnbqn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daria6918.cn/Article/details/gt2qenbtgwp.html

[T11] Kotlin：协程
来源：http://dali.kuanghao11.cn/Article/details/gt2qlhoioat.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenzaomai.com/Article/details/gt2ahrrndph.html

[T12] Kotlin：解构声明
来源：http://dali.wangdashe.top/Article/details/gt2uofuweff.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gt2tcqlfduc.html

[T13] Kotlin：只读 Map
来源：http://dali.xziqi.cn/Article/details/gt2ohhydlfn.html

val m = mapOf("a" to 1)
来源：http://dali.yj202588.top/Article/details/gt2rxtpxhbt.html

[T14] Kotlin：循环
来源：http://dali.xylfe.cn/Article/details/gt2nnaimdkz.html

for (i in 1..10) println(i)
来源：http://dali.316326.xyz/Article/details/gt2athyiuef.html

[T15] Kotlin：接口
来源：http://dali.zdqjudy.top/Article/details/gt2rsmbqulo.html

interface Shape { fun area(): Double }
来源：http://dali.yuanzhike.top/Article/details/gt2wjbqyzti.html

[T16] Swift：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2udmngljc.html

print("Hello")
来源：http://dali.smart0.xyz/Article/details/gt2wyykbkfi.html

[T17] Swift：变量与常量
来源：http://dali.jlsjyb.cn/Article/details/gt2meekuomc.html

var a = 1;  let b = 2
来源：http://dali.xuanzx.com/Article/details/gt2bxrhrapp.html

[T18] Swift：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gt2nbihlyhs.html

"值: \(b)"
来源：http://dali.meibo888.top/Article/details/gt2wlfltmkq.html

[T19] Swift：可选绑定
来源：http://dali.smart0.xyz/Article/details/gt2qrorjwhb.html

if let n = opt { print(n) }
来源：http://dali.daria6918.cn/Article/details/gt2rfiwmgua.html

[T20] Swift：数组操作
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bzjpulbf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yonumen.top/Article/details/gt2mkciqqaw.html

[T21] Swift：遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqefllbi.html

for x in a { print(x) }
来源：http://dali.jianghu66.top/Article/details/gt2znlleale.html

[T22] Swift：字典
来源：http://dali.cashguo.top/Article/details/gt2botlnqit.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.haohaochexian.top/Article/details/gt2cbsncpsj.html

[T23] Swift：函数
来源：http://dali.hysaishi.cn/Article/details/gt2gyoszywq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daxiang520.top/Article/details/gt2btlmmarq.html

[T24] Swift：闭包
来源：http://dali.fengsongda.top/Article/details/gt2nhxowwlu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.havefunace.top/Article/details/gt2snfpbntf.html

[T25] Swift：结构体
来源：http://dali.kuanghao11.cn/Article/details/gt2kcyvnjmg.html

struct P { var x: Int }
来源：http://dali.ivvv.top/Article/details/gt2feosmabp.html

[T26] Swift：类与重写
来源：http://dali.sxryk.cn/Article/details/gt2ewhnnpia.html

class A: Base { override func f() {} }
来源：http://dali.wangdashe.top/Article/details/gt2sxzxybpd.html

[T27] Swift：错误处理
来源：http://dali.ehwqpu.com/Article/details/gt2igqejmxu.html

do { try f() } catch { print(error) }
来源：http://dali.smart0.xyz/Article/details/gt2cueoogjq.html

[T28] Swift：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uwzelzqc.html

enum Color { case red, green }
来源：http://dali.tianlin.xyz/Article/details/gt2alxoejnu.html

[T29] Swift：guard 提前返回
来源：http://dali.kuanghao11.cn/Article/details/gt2wgyqamdr.html

guard let x = opt else { return }
来源：http://dali.mhx1999.top/Article/details/gt2zeujlbko.html

[T30] Swift：协议
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2syckucxy.html

protocol Shape { func area() -> Double }
来源：http://dali.yueranfly.top/Article/details/gt2cpsghqej.html

[T31] Lua：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2etktumvi.html

print("Hello")
来源：http://dali.tanke756.top/Article/details/gt2tkszppau.html

[T32] Lua：局部变量
来源：http://dali.jqgfzy.top/Article/details/gt2gjzafvqm.html

local a = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndcqhrhe.html

[T33] Lua：表（数组）
来源：http://dali.chenlongwang.top/Article/details/gt2duwzjizl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cashguo.top/Article/details/gt2tqdrqjas.html

[T34] Lua：遍历表
来源：http://dali.tanke756.top/Article/details/gt2qszhjjdc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guowangkeji.top/Article/details/gt2xexxbkpm.html

[T35] Lua：字典表
来源：http://dali.haohaochexian.top/Article/details/gt2orhtvmru.html

local d = { a = 1 };  d.b = 2
来源：http://dali.andypj.xyz/Article/details/gt2cprfmffv.html

[T36] Lua：函数
来源：http://dali.hysaishi.cn/Article/details/gt2tefxutxg.html

function add(a, b) return a + b end
来源：http://dali.jiagoushi.top/Article/details/gt2fhocspiu.html

[T37] Lua：字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gt2swydglno.html

"a" .. "b"
来源：http://dali.mhx1999.top/Article/details/gt2vbzkcsuf.html

[T38] Lua：条件
来源：http://dali.wangshuangyany.cn/Article/details/gt2uasgkdzk.html

if x > 0 then print("正") end
来源：http://dali.gogol.net.cn/Article/details/gt2mbbbkcds.html

[T39] Lua：模式匹配
来源：http://dali.hfpthk.cn/Article/details/gt2iriywtcy.html

string.find(s, "%d+")
来源：http://dali.smart0.xyz/Article/details/gt2eefhztmr.html

[T40] Lua：元表
来源：http://dali.haohaochexian.top/Article/details/gt2tjnwbxcm.html

setmetatable({}, { __index = base })
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmkdazcb.html

[T41] Perl：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2plpeezfg.html

print "Hello\n";
来源：http://dali.cheryme.top/Article/details/gt2mswujtkp.html

[T42] Perl：变量类型
来源：http://dali.guannengcc.top/Article/details/gt2xisignci.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2fmbhndrr.html

[T43] Perl：字符串插值
来源：http://dali.birdmap.top/Article/details/gt2fkndtdso.html

"值: $a"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2utakzqtn.html

[T44] Perl：条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2uansweas.html

if ($a > 0) { print "正"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2qsmauhkt.html

[T45] Perl：数组遍历
来源：http://dali.havefunace.top/Article/details/gt2vuedrazm.html

for my $x (@arr) { print $x; }
来源：http://dali.jinqigfzy.top/Article/details/gt2gdpppssw.html

[T46] Perl：哈希操作
来源：http://dali.yj202588.top/Article/details/gt2gqxufoqn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guannengcc.top/Article/details/gt2cvbyusgh.html

[T47] Perl：正则捕获
来源：http://dali.tanke756.top/Article/details/gt2hbaqjwml.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ybcxt.top/Article/details/gt2ryknhllj.html

[T48] Perl：正则替换
来源：http://dali.tanke756.top/Article/details/gt2lpdxshpz.html

$s =~ s/old/new/g;
来源：http://dali.shuidangran.top/Article/details/gt2wkoeaqis.html

[T49] Perl：函数
来源：http://dali.gaohongyu789.top/Article/details/gt2ywvwuvpj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gt2rhpidjid.html

[T50] Perl：逐行读文件
来源：http://dali.tanke756.top/Article/details/gt2sbabjrbr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jlsjyb.cn/Article/details/gt2cwjtxtnq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenlongwang.top/Article/details/gt2gjseegcz.html

[T51] Scala：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2jdotsavn.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gt2yjgvlbae.html

[T52] Scala：变量
来源：http://dali.guowangkeji.top/Article/details/gt2dsvnlwgg.html

val a = 1;  var b = 2
来源：http://dali.gaohongyu789.top/Article/details/gt2ffamoklp.html

[T53] Scala：字符串插值
来源：http://dali.nwbrower.top/Article/details/gt2yichcdgx.html

s"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gt2zmesqerl.html

[T54] Scala：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gt2nthyibqu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fejxtoni.html

[T55] Scala：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2gjzwfbaa.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shuidangran.top/Article/details/gt2nwsbcycg.html

[T56] Scala：样例类
来源：http://dali.yongpay.top/Article/details/gt2viyzmeen.html

case class User(name: String, age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gt2shavdpcz.html

[T57] Scala：模式匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wkylrqge.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cdnleiting.top/Article/details/gt2wibvmkie.html

[T58] Scala：函数定义
来源：http://dali.cheryme.top/Article/details/gt2siaomgvi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.andypj.xyz/Article/details/gt2xaonvckh.html

[T59] Scala：循环
来源：http://dali.yangfankeji.com/Article/details/gt2afhsbkxv.html

for (i <- 1 to 10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gt2xfqmrozt.html

[T60] Scala：折叠
来源：http://dali.havefunace.top/Article/details/gt2bkmxvpoc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shangyingyoupin.top/Article/details/gt2alkqiihp.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2pwzkjjfb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zlwaflwf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2lvcinsuf.html

[U01] Py：创建虚拟环境
来源：http://dali.jlsjyb.cn/Article/details/gt2rxdmjtfz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdasren.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gotoacloud.top/Article/details/gt2fyldyiuf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ydzc1.top/Article/details/gt2tgqwevsi.html

[U03] Py：加载 .env 配置
来源：http://dali.tian-w.cn/Article/details/gt2iwzkgerq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.quarkkingdee.top/Article/details/gt2jdbimdaz.html

[U04] Py：变量调试打印
来源：http://dali.xuetiantiany.cn/Article/details/gt2uinbnxsn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj202588.top/Article/details/gt2fkaktztp.html

[U05] Py：列表去重且保序
来源：http://dali.tianlin.xyz/Article/details/gt2ioswetsz.html

list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gt2lsntceba.html

[U06] Py：合并两个字典
来源：http://dali.fzhhl.top/Article/details/gt2qhkiqpeq.html

{**a, **b}
来源：http://dali.shuidangran.top/Article/details/gt2haxdyern.html

[U07] Py：反转字典键值
来源：http://dali.yj20258888.top/Article/details/gt2liiikdlo.html

{v: k for k, v in d.items()}
来源：http://dali.xuanzx.com/Article/details/gt2docxrvlj.html

[U08] Py：展平二维列表
来源：http://dali.gogol.net.cn/Article/details/gt2shwxtgrh.html

[y for x in nested for y in x]
来源：http://dali.shuidangran.top/Article/details/gt2vautrtag.html

[U09] Py：字典取最大值的键
来源：http://dali.zhongyouzk.top/Article/details/gt2sftumfid.html

max(d, key=d.get)
来源：http://dali.wangdashe.top/Article/details/gt2bskskksw.html

[U10] Py：按值排序字典
来源：http://dali.sufxvd.cn/Article/details/gt2xzsizlps.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cashguo.top/Article/details/gt2dmcuyhhp.html

[U11] Py：生成器表达式
来源：http://dali.nanxinkj.top/Article/details/gt2qklznskw.html

(x * 2 for x in arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2slxzmqcr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zycfv.cn/Article/details/gt2zzvqwqvp.html

Counter(arr).most_common(3)
来源：http://dali.hammf.cn/Article/details/gt2pydvtbcj.html

[U13] Py：固定长度队列
来源：http://dali.ehwqpu.com/Article/details/gt2jlfkzfnu.html

deque(maxlen=10)
来源：http://dali.chenzaomai.com/Article/details/gt2pszeezyk.html

[U14] Py：分组收集到列表
来源：http://dali.aizwys.cn/Article/details/gt2bohhyesd.html

defaultdict(list)
来源：http://dali.yuxming.cn/Article/details/gt2oidmlogl.html

[U15] Py：高精度计时
来源：http://dali.dashuyun.cn/Article/details/gt2iszuhkct.html

t = time.perf_counter()
来源：http://dali.cucudq.cn/Article/details/gt2wwonybpa.html

[U16] Py：命令行参数解析
来源：http://dali.gogol.net.cn/Article/details/gt2fwykhged.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gaohongyu789.top/Article/details/gt2gxkmlnbo.html

[U17] Py：初始化日志
来源：http://dali.tanke756.top/Article/details/gt2oustryba.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cheryme.top/Article/details/gt2hkxqcebq.html

[U18] Py：预编译正则
来源：http://dali.vqdsnc.cn/Article/details/gt2wjfwwlyo.html

pat = re.compile(r"\d+")
来源：http://dali.yj20258.top/Article/details/gt2cgdxzooh.html

[U19] Py：正则替换带回调
来源：http://dali.daxiang520.top/Article/details/gt2wkytrflk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.wangdashe.top/Article/details/gt2glchcbtf.html

[U20] Py：缓存函数结果
来源：http://dali.9152youxi.cn/Article/details/gt2uczxbbdo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hysaishi.cn/Article/details/gt2elcdwlpz.html

[U21] Py：自定义上下文管理器
来源：http://dali.0kj1m.cn/Article/details/gt2ybpvhrqt.html

@contextlib.contextmanager
来源：http://dali.ehwqpu.com/Article/details/gt2ulfulcio.html

[U22] Py：矩阵转置
来源：http://dali.cucudq.cn/Article/details/gt2aoujtbuq.html

list(zip(*m))
来源：http://dali.cdnleiting.top/Article/details/gt2cvtyualk.html

[U23] Py：分块读取大文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ehfcqlrc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.meibo888.top/Article/details/gt2gixyezah.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkortyk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gt2asckesrw.html

[U25] Py：CSV 按字典读
来源：http://dali.wangshuangyany.cn/Article/details/gt2lntnpvyv.html

csv.DictReader(f)
来源：http://dali.sysykeji.top/Article/details/gt2avcrmfoh.html

[U26] Py：并发下载
来源：http://dali.gogol.net.cn/Article/details/gt2ssrzbvrb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.dashuyun.cn/Article/details/gt2xsyxcmuy.html

[U27] Py：异步 HTTP
来源：http://dali.redwolf501.top/Article/details/gt2efwnpdon.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdhmufdd.html

[U28] Py：类型别名
来源：http://dali.birdmap.top/Article/details/gt2bsgatfxa.html

UserId = int
来源：http://dali.hongshengwenyu.top/Article/details/gt2jfzlamba.html

[U29] Py：属性校验
来源：http://dali.shzxlz.cn/Article/details/gt2gamhvrit.html

@property 与 @x.setter 配合
来源：http://dali.jyoumei.cn/Article/details/gt2gfqmiihn.html

[U30] Py：数据类
来源：http://dali.meibo888.top/Article/details/gt2hsfghjjd.html

@dataclass(slots=True)
来源：http://dali.aibaodan.cn/Article/details/gt2pjdgrfmy.html

[U31] Py：单测
来源：http://dali.hywenlv.cn/Article/details/gt2sjplcnrw.html

python -m pytest -q
来源：http://dali.jinqigufen.top/Article/details/gt2nvaurnru.html

[U32] Py：代码格式化
来源：http://dali.jlsjyb.cn/Article/details/gt2cvlehnvr.html

ruff format . && ruff check --fix .
来源：http://dali.xinyue.icu/Article/details/gt2hlsduccq.html

[U33] Py：打包发布
来源：http://dali.meibo888.top/Article/details/gt2cdbxwbmg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.smart0.xyz/Article/details/gt2xnbrikgu.html

[U34] Py：判断编码
来源：http://dali.yvedp.cn/Article/details/gt2pfcfafhk.html

chardet.detect(raw)
来源：http://dali.hnxiangtu.top/Article/details/gt2ocyjnfrd.html

[U35] Py：发送邮件
来源：http://dali.yuanzhike.top/Article/details/gt2fogblpww.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shuidangran.top/Article/details/gt2ktwarhun.html

[U36] Py：定时任务
来源：http://dali.xuetiantiany.cn/Article/details/gt2wasgyemb.html

schedule.every(10).minutes.do(job)
来源：http://dali.yvedp.cn/Article/details/gt2opmgxsuq.html

[U37] Py：读写 Excel
来源：http://dali.yonumen.top/Article/details/gt2brcjoiuf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jmlzmsvk.html

[U38] Py：获取脚本所在目录
来源：http://dali.zdqjudy.top/Article/details/gt2aebxkybc.html

Path(__file__).resolve().parent
来源：http://dali.wangdashe.top/Article/details/gt2prgyyuos.html

[U39] Py：判断是否在交互环境
来源：http://dali.svipenyu.cn/Article/details/gt2orxtdusw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2fogctyak.html

[U40] Py：打印到标准错误
来源：http://dali.aibaodan.cn/Article/details/gt2nnlwhngd.html

print("err", file=sys.stderr)
来源：http://dali.haohaochexian.top/Article/details/gt2rfyqknql.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.feifeiyinyue.top/Article/details/gt2ttkuodvr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cucudq.cn/Article/details/gt2wsmxjqrm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dppjhowe.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.snrcjt.cn/Article/details/gt2votbsiqe.html

[U43] PHP：声明命名空间
来源：http://dali.iojbl.cn/Article/details/gt2gyolugms.html

namespace App\Http;
来源：http://dali.zhixingplan.top/Article/details/gt2pztihnmm.html

[U44] PHP：开启严格类型
来源：http://dali.yueranfly.top/Article/details/gt2xjmprvko.html

declare(strict_types=1);
来源：http://dali.zhixingplan.top/Article/details/gt2ffdkyqen.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yuanzhike.top/Article/details/gt2eqdrsmll.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gt2djqynmje.html

[U46] PHP：可空类型
来源：http://dali.gzhubu.top/Article/details/gt2gqdmehbk.html

?string $name = null
来源：http://dali.jlsjyb.cn/Article/details/gt2hotcnvfr.html

[U47] PHP：联合类型
来源：http://dali.xinyue.icu/Article/details/gt2yzaevpsl.html

int|string $id
来源：http://dali.jinqigfzy.top/Article/details/gt2frkjnfpi.html

[U48] PHP：纯枚举
来源：http://dali.cheryme.top/Article/details/gt2mgpzjeln.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gogol.net.cn/Article/details/gt2wxfhbokq.html

[U49] PHP：只读属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ysxmbooj.html

public readonly string $name
来源：http://dali.mhx1999.top/Article/details/gt2snxcafpy.html

[U50] PHP：构造器属性提升
来源：http://dali.chenlongwang.top/Article/details/gt2scnuttdo.html

public function __construct(private int $id) {}
来源：http://dali.ehwqpu.com/Article/details/gt2rahgrnov.html

[U51] PHP：数组解构
来源：http://dali.tianlin.xyz/Article/details/gt2zzjeslzs.html

[$a, $b] = $arr;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jbqmvbaj.html

[U52] PHP：箭头函数
来源：http://dali.sysykeji.top/Article/details/gt2qfpfprem.html

$double = fn($x) => $x * 2;
来源：http://dali.zhoulong.xyz/Article/details/gt2daubvqda.html

[U53] PHP：空合并运算符
来源：http://dali.kuanghao11.cn/Article/details/gt2zfcwqbon.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhixingplan.top/Article/details/gt2ptvhkcaz.html

[U54] PHP：空安全调用
来源：http://dali.ehwqpu.com/Article/details/gt2sknwxfhy.html

$obj?->method()
来源：http://dali.nwbrower.top/Article/details/gt2lkuxttzj.html

[U55] PHP：match 表达式
来源：http://dali.redwolf501.top/Article/details/gt2jrignecm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.chenzaomai.com/Article/details/gt2ddscuotu.html

[U56] PHP：命名参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ivfrjkha.html

f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gt2ibtgxfjh.html

[U57] PHP：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2cyuwjdpj.html

"值: {$a}"
来源：http://dali.daxiang520.top/Article/details/gt2wuxhjwix.html

[U58] PHP：数组三件套
来源：http://dali.ydzc1.top/Article/details/gt2nknvefth.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zdqjudy.top/Article/details/gt2gjclwahz.html

[U59] PHP：自定义排序
来源：http://dali.meibo888.top/Article/details/gt2mrgouqgo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.c1oappe.top/Article/details/gt2ylsrbrqx.html

[U60] PHP：JSON 编解码
来源：http://dali.sysykeji.top/Article/details/gt2qzrocgak.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinqigfzy.top/Article/details/gt2nujnhehs.html

[U61] PHP：正则
来源：http://dali.jiagoushi.top/Article/details/gt2obuchptz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xfsfnmiw.html

[U62] PHP：日期对象
来源：http://dali.havefunace.top/Article/details/gt2vsowsfus.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.smart0.xyz/Article/details/gt2kyuggkcb.html

[U63] PHP：文件读写
来源：http://dali.xuanzx.com/Article/details/gt2ffbbtxgs.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yuanzhike.top/Article/details/gt2ybzwsgbx.html

[U64] PHP：目录遍历
来源：http://dali.gzhubu.top/Article/details/gt2qrvxwqfo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhongyouzk.top/Article/details/gt2dyuucglp.html

[U65] PHP：会话
来源：http://dali.hywenlv.cn/Article/details/gt2ptpqpbna.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2zxyqdnxi.html

[U66] PHP：设置 Cookie
来源：http://dali.nanxinkj.top/Article/details/gt2jtxazmac.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.bjfxy.top/Article/details/gt2knbthjnr.html

[U67] PHP：处理文件上传
来源：http://dali.zhoulong.xyz/Article/details/gt2gulimegu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhongyouzk.top/Article/details/gt2gfeimxif.html

[U68] PHP：PDO 连接
来源：http://dali.smart0.xyz/Article/details/gt2hobkrwzr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.fzhhl.top/Article/details/gt2oraxytlo.html

[U69] PHP：PDO 预处理
来源：http://dali.9152youxi.cn/Article/details/gt2ygdaldev.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.c1oappe.top/Article/details/gt2fuwpxouy.html

[U70] PHP：PDO 事务
来源：http://dali.xylfe.cn/Article/details/gt2zbmuwvso.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jyoumei.cn/Article/details/gt2vutrpniu.html

[U71] PHP：抛出异常
来源：http://dali.wangshuangyany.cn/Article/details/gt2jnkbdflh.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sszxyshq.html

[U72] PHP：写错误日志
来源：http://dali.pycfn.com/Article/details/gt2gdthhnjw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.svipenyu.cn/Article/details/gt2fqksziif.html

[U73] PHP：读取 ini 配置
来源：http://dali.birdmap.top/Article/details/gt2uuwbwmym.html

parse_ini_file("config.ini", true)
来源：http://dali.smart0.xyz/Article/details/gt2tbmuejaa.html

[U74] PHP：读取环境变量
来源：http://dali.tanke756.top/Article/details/gt2ghiuowym.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jjhhiizh.html

[U75] PHP：依赖注入
来源：http://dali.gzhubu.top/Article/details/gt2xqthuohq.html

composer require psr/container
来源：http://dali.zhiwuduotai.top/Article/details/gt2fshlouhn.html

[U76] PHP：简单路由
来源：http://dali.hnqzz.top/Article/details/gt2cwvfrqaq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.iojbl.cn/Article/details/gt2fcwrzkeu.html

[U77] PHP：模板渲染
来源：http://dali.bjfxy.top/Article/details/gt2vxhfwyrn.html

composer require twig/twig
来源：http://dali.yuanzhike.top/Article/details/gt2lkbbqjwf.html

[U78] PHP：单元测试
来源：http://dali.chenlongwang.top/Article/details/gt2wkprdsyj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhoulong.xyz/Article/details/gt2qucchbcp.html

[U79] PHP：静态分析
来源：http://dali.hongshengwenyu.top/Article/details/gt2mjmejfph.html

composer require --dev phpstan/phpstan
来源：http://dali.cheryme.top/Article/details/gt2mypnawfv.html

[U80] PHP：代码规范修复
来源：http://dali.meibo888.top/Article/details/gt2twaxzetz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cashguo.top/Article/details/gt2xudrfqya.html

[U81] JS：初始化项目
来源：http://dali.feifeiyinyue.top/Article/details/gt2tiyoaive.html

npm init -y;  npm i express
来源：http://dali.gogol.net.cn/Article/details/gt2pxqztakq.html

[U82] JS：package.json 脚本
来源：http://dali.cqqwz.cn/Article/details/gt2oybbtpmo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.wangdashe.top/Article/details/gt2ypjefjih.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhongyouzk.top/Article/details/gt2erkywhax.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zycfv.cn/Article/details/gt2xvlthgod.html

[U84] JS：CommonJS 写法
来源：http://dali.jinqigfzy.top/Article/details/gt2xpqutcap.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.fengsongda.top/Article/details/gt2fyyrvybe.html


<!-- 参考信息 -->