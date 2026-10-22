代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.jinqigfzy.top/Article/details/gtgsjjjtvr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhengqikj.top/Article/details/gtdmtnffif.html

[T06] Kotlin：集合映射
来源：http://dali.tianlin.xyz/Article/details/gtjougxkqq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.haohaochexian.top/Article/details/gtpwlxuebm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtijbtdidl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hnxiangtu.top/Article/details/gtcpflcqmd.html

[T08] Kotlin：数据类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebgdamuy.html

data class User(val name: String, val age: Int)
来源：http://dali.xuanzx.com/Article/details/gtqfqsfiwo.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxinkj.top/Article/details/gtjugokjps.html

fun String.exclaim() = this + "!"
来源：http://dali.hfpthk.cn/Article/details/gtmbgpshmm.html

[T10] Kotlin：默认参数
来源：http://dali.yvedp.cn/Article/details/gtjqulcmei.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dashuyun.cn/Article/details/gtgpuqzfvv.html

[T11] Kotlin：协程
来源：http://dali.fengsongda.top/Article/details/gtlrjspgpx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenlongwang.top/Article/details/gtewyhrogi.html

[T12] Kotlin：解构声明
来源：http://dali.aizwys.cn/Article/details/gtczkfwusc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkcbfqmvj.html

[T13] Kotlin：只读 Map
来源：http://dali.smart0.xyz/Article/details/gtsrfujexn.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigfzy.top/Article/details/gtegclhwxx.html

[T14] Kotlin：循环
来源：http://dali.havefunace.top/Article/details/gtcklwybus.html

for (i in 1..10) println(i)
来源：http://dali.cdnleiting.top/Article/details/gtunlfnwxq.html

[T15] Kotlin：接口
来源：http://dali.pengpengdd.cyou/Article/details/gtgyowcdch.html

interface Shape { fun area(): Double }
来源：http://dali.sxryk.cn/Article/details/gtngapdxst.html

[T16] Swift：Hello World
来源：http://dali.nwbrower.top/Article/details/gtbumfasbm.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gtrrovciee.html

[T17] Swift：变量与常量
来源：http://dali.jinghuilouyu.cn/Article/details/gthmzpjefe.html

var a = 1;  let b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtyphhhjqj.html

[T18] Swift：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtemvgbews.html

"值: \(b)"
来源：http://dali.yangfankeji.com/Article/details/gtqbhtaxpt.html

[T19] Swift：可选绑定
来源：http://dali.hnxiangtu.top/Article/details/gtgyguncsx.html

if let n = opt { print(n) }
来源：http://dali.wangdashe.top/Article/details/gtdjaebtyw.html

[T20] Swift：数组操作
来源：http://dali.iojbl.cn/Article/details/gtcknewkre.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cucudq.cn/Article/details/gtrmomxdxv.html

[T21] Swift：遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtivgebmsh.html

for x in a { print(x) }
来源：http://dali.guowangkeji.top/Article/details/gtpbmwncsv.html

[T22] Swift：字典
来源：http://dali.zycfv.cn/Article/details/gtrgzvdgzx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jiagoushi.top/Article/details/gtarmsdzar.html

[T23] Swift：函数
来源：http://dali.jiagoushi.top/Article/details/gtyzskqpkp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenjidiqi.icu/Article/details/gtykauzjdd.html

[T24] Swift：闭包
来源：http://dali.sweek.top/Article/details/gtfxvcteip.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdkeyjft.html

[T25] Swift：结构体
来源：http://dali.zdqjudy.top/Article/details/gtwkheqdkn.html

struct P { var x: Int }
来源：http://dali.jinqigufen.top/Article/details/gtuqeyyjyo.html

[T26] Swift：类与重写
来源：http://dali.hywenlv.cn/Article/details/gtmrfvpyhw.html

class A: Base { override func f() {} }
来源：http://dali.chenjidiqi.icu/Article/details/gtanyvxgvl.html

[T27] Swift：错误处理
来源：http://dali.gaohongyu789.top/Article/details/gtvnkwhbnk.html

do { try f() } catch { print(error) }
来源：http://dali.haohaochexian.top/Article/details/gtphermayx.html

[T28] Swift：枚举
来源：http://dali.hammf.cn/Article/details/gtkciklqwb.html

enum Color { case red, green }
来源：http://dali.cheryme.top/Article/details/gtqiixllgi.html

[T29] Swift：guard 提前返回
来源：http://dali.havefunace.top/Article/details/gtymztfnif.html

guard let x = opt else { return }
来源：http://dali.nanxuanxn.top/Article/details/gtrtpwgqhq.html

[T30] Swift：协议
来源：http://dali.zhongyouzk.top/Article/details/gtwinfzwcq.html

protocol Shape { func area() -> Double }
来源：http://dali.cqqwz.cn/Article/details/gtaqvcyobf.html

[T31] Lua：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gthnfpldav.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgdnleyc.html

[T32] Lua：局部变量
来源：http://dali.daria6918.cn/Article/details/gtrhzeurub.html

local a = 1
来源：http://dali.gogol.net.cn/Article/details/gtnzuenqml.html

[T33] Lua：表（数组）
来源：http://dali.wangdashe.top/Article/details/gtngqbppaz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gaohongyu789.top/Article/details/gtdbmoyxwx.html

[T34] Lua：遍历表
来源：http://dali.tianlin.xyz/Article/details/gtwngqqgyr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.vqdsnc.cn/Article/details/gtyskfjnhk.html

[T35] Lua：字典表
来源：http://dali.316326.xyz/Article/details/gttjeiukzx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfidrbbu.html

[T36] Lua：函数
来源：http://dali.snrcjt.cn/Article/details/gtfrcpxbwf.html

function add(a, b) return a + b end
来源：http://dali.hnqzz.top/Article/details/gtimmbkpyq.html

[T37] Lua：字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gtlszgcmjs.html

"a" .. "b"
来源：http://dali.cheryme.top/Article/details/gtivwdltrh.html

[T38] Lua：条件
来源：http://dali.sufxvd.cn/Article/details/gtgrfiipbu.html

if x > 0 then print("正") end
来源：http://dali.cucudq.cn/Article/details/gtjfgbkabb.html

[T39] Lua：模式匹配
来源：http://dali.guannengcc.top/Article/details/gtpzeimdex.html

string.find(s, "%d+")
来源：http://dali.zdqjudy.top/Article/details/gtruasrdgl.html

[T40] Lua：元表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubbmvyxh.html

setmetatable({}, { __index = base })
来源：http://dali.daxiang520.top/Article/details/gtpaplezhf.html

[T41] Perl：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtsebedpnv.html

print "Hello\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuevwmmi.html

[T42] Perl：变量类型
来源：http://dali.zhiwuduotai.top/Article/details/gtgriipzmh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.dianchejie.cn/Article/details/gtehrzmale.html

[T43] Perl：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtzvxqlmcm.html

"值: $a"
来源：http://dali.meibo888.top/Article/details/gttbyrrobu.html

[T44] Perl：条件
来源：http://dali.nwbrower.top/Article/details/gtbvpchbbr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgapaasxn.html

[T45] Perl：数组遍历
来源：http://dali.yonumen.top/Article/details/gtvjpihmfz.html

for my $x (@arr) { print $x; }
来源：http://dali.daxiang520.top/Article/details/gtfskcouve.html

[T46] Perl：哈希操作
来源：http://dali.guannengcc.top/Article/details/gtqrslxeyj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aibaodan.cn/Article/details/gttxgoldss.html

[T47] Perl：正则捕获
来源：http://dali.nanxuanxn.top/Article/details/gtpwavzewd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tian-w.cn/Article/details/gthhjqdwbu.html

[T48] Perl：正则替换
来源：http://dali.cheryme.top/Article/details/gtslcuwxis.html

$s =~ s/old/new/g;
来源：http://dali.bjfxy.top/Article/details/gtvvqguakt.html

[T49] Perl：函数
来源：http://dali.cqqwz.cn/Article/details/gttkeintin.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtnilmxjyy.html

[T50] Perl：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtwhdlajvx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.c1oappe.top/Article/details/gtljawcxzw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuxming.cn/Article/details/gtdishnqec.html

[T51] Scala：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtcxwgnnap.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtadfkppkv.html

[T52] Scala：变量
来源：http://dali.zdqjudy.top/Article/details/gtbpfoenfp.html

val a = 1;  var b = 2
来源：http://dali.hnxiangtu.top/Article/details/gtcebautas.html

[T53] Scala：字符串插值
来源：http://dali.cheryme.top/Article/details/gtcqmaxzav.html

s"值: $b"
来源：http://dali.hnqzz.top/Article/details/gtqkhqpohz.html

[T54] Scala：集合映射
来源：http://dali.hammf.cn/Article/details/gtryfxkxgx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgfzy.top/Article/details/gtrhlqbgsg.html

[T55] Scala：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gtjzvwpook.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aizwys.cn/Article/details/gtxkrxcvcu.html

[T56] Scala：样例类
来源：http://dali.yvedp.cn/Article/details/gtvcuxinng.html

case class User(name: String, age: Int)
来源：http://dali.nwbrower.top/Article/details/gtaxqbrjza.html

[T57] Scala：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gtqayfwzfn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ppjwa.cn/Article/details/gtgfwicwxd.html

[T58] Scala：函数定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtjintea.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tian-w.cn/Article/details/gtdsreokub.html

[T59] Scala：循环
来源：http://dali.jlsjyb.cn/Article/details/gtzeytmnid.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gtncjaxqoe.html

[T60] Scala：折叠
来源：http://dali.9152youxi.cn/Article/details/gtmooxppgo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.haohaochexian.top/Article/details/gterqylbih.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtmdjqlopr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenlongwang.top/Article/details/gtignlxcxi.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtuszvngmt.html

[U01] Py：创建虚拟环境
来源：http://dali.hnxiangtu.top/Article/details/gtflvkocqb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcphjxiap.html

[U02] Py：导出 / 安装依赖
来源：http://dali.havefunace.top/Article/details/gtlybnnrrc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.mhx1999.top/Article/details/gtkhxjeohe.html

[U03] Py：加载 .env 配置
来源：http://dali.yonumen.top/Article/details/gtnpznxapr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuetiantiany.cn/Article/details/gtnuboruhg.html

[U04] Py：变量调试打印
来源：http://dali.quarkkingdee.top/Article/details/gtvtpsgila.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.c1oappe.top/Article/details/gtqwbgaewi.html

[U05] Py：列表去重且保序
来源：http://dali.xylfe.cn/Article/details/gtohpvomho.html

list(dict.fromkeys(arr))
来源：http://dali.cucudq.cn/Article/details/gtdntygnzb.html

[U06] Py：合并两个字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxmvubrs.html

{**a, **b}
来源：http://dali.yonumen.top/Article/details/gtxsonasyh.html

[U07] Py：反转字典键值
来源：http://dali.feifeiyinyue.top/Article/details/gtssgcuhvq.html

{v: k for k, v in d.items()}
来源：http://dali.c1oappe.top/Article/details/gtpntoiyda.html

[U08] Py：展平二维列表
来源：http://dali.c1oappe.top/Article/details/gtfgdujupc.html

[y for x in nested for y in x]
来源：http://dali.gogol.net.cn/Article/details/gtusugutov.html

[U09] Py：字典取最大值的键
来源：http://dali.guowangkeji.top/Article/details/gtiglsxcif.html

max(d, key=d.get)
来源：http://dali.fengsongda.top/Article/details/gtgakueagf.html

[U10] Py：按值排序字典
来源：http://dali.andypj.xyz/Article/details/gtimfkyptw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sufxvd.cn/Article/details/gtmmazkddd.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gtkzlpunko.html

(x * 2 for x in arr)
来源：http://dali.pycfn.com/Article/details/gtsuqyjbfs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gotoacloud.top/Article/details/gtkzqxfbks.html

Counter(arr).most_common(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtpuaujqry.html

[U13] Py：固定长度队列
来源：http://dali.zhiwuduotai.top/Article/details/gtnbygpzac.html

deque(maxlen=10)
来源：http://dali.hongshengwenyu.top/Article/details/gtdlbzdrdh.html

[U14] Py：分组收集到列表
来源：http://dali.jianghu66.top/Article/details/gtzirkyjwo.html

defaultdict(list)
来源：http://dali.yj20258.top/Article/details/gtokzlispc.html

[U15] Py：高精度计时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqchgcwa.html

t = time.perf_counter()
来源：http://dali.hongshengwenyu.top/Article/details/gtmzrdyzkl.html

[U16] Py：命令行参数解析
来源：http://dali.hongshengwenyu.top/Article/details/gthxrsqxzg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.havefunace.top/Article/details/gtlisnttoq.html

[U17] Py：初始化日志
来源：http://dali.zhengqikj.top/Article/details/gtheeeduzo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cqqwz.cn/Article/details/gtodxtfjmq.html

[U18] Py：预编译正则
来源：http://dali.jqgfzy.top/Article/details/gtjvkkdohm.html

pat = re.compile(r"\d+")
来源：http://dali.aizwys.cn/Article/details/gtbwaugjlx.html

[U19] Py：正则替换带回调
来源：http://dali.fengsongda.top/Article/details/gtnmdphtxi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj20258888.top/Article/details/gtjpnbmpwv.html

[U20] Py：缓存函数结果
来源：http://dali.jianghu66.top/Article/details/gtlvuiiois.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ydzc1.top/Article/details/gtdxursvtf.html

[U21] Py：自定义上下文管理器
来源：http://dali.aibaodan.cn/Article/details/gtjggxmsaj.html

@contextlib.contextmanager
来源：http://dali.yueranfly.top/Article/details/gtxjhsacdi.html

[U22] Py：矩阵转置
来源：http://dali.chenzaomai.com/Article/details/gtunkypilh.html

list(zip(*m))
来源：http://dali.sxryk.cn/Article/details/gtonochpiv.html

[U23] Py：分块读取大文件
来源：http://dali.xinyue.icu/Article/details/gtfvmayexh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yangfankeji.com/Article/details/gtoiertcjq.html

[U24] Py：路径操作
来源：http://dali.fzhhl.top/Article/details/gtmvonpbit.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.aizwys.cn/Article/details/gtrecvwmad.html

[U25] Py：CSV 按字典读
来源：http://dali.havefunace.top/Article/details/gtvziemqpg.html

csv.DictReader(f)
来源：http://dali.tanke756.top/Article/details/gtxzaavtea.html

[U26] Py：并发下载
来源：http://dali.birdmap.top/Article/details/gtxhtdpkve.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnbntzyd.html

[U27] Py：异步 HTTP
来源：http://dali.bjfxy.top/Article/details/gtkigzxtbn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tanke756.top/Article/details/gtcwhrtqgd.html

[U28] Py：类型别名
来源：http://dali.chenlongwang.top/Article/details/gtolkcptjn.html

UserId = int
来源：http://dali.0kj1m.cn/Article/details/gtqaozymwv.html

[U29] Py：属性校验
来源：http://dali.yj20258.top/Article/details/gtrtiudbpl.html

@property 与 @x.setter 配合
来源：http://dali.yj20258.top/Article/details/gtfimxgnkw.html

[U30] Py：数据类
来源：http://dali.shangyingyoupin.top/Article/details/gtjqyhztxu.html

@dataclass(slots=True)
来源：http://dali.andypj.xyz/Article/details/gtqyrembpv.html

[U31] Py：单测
来源：http://dali.sxryk.cn/Article/details/gthuqxioma.html

python -m pytest -q
来源：http://dali.xuetiantiany.cn/Article/details/gtdthdlhwo.html

[U32] Py：代码格式化
来源：http://dali.hywenlv.cn/Article/details/gtphsqdnwy.html

ruff format . && ruff check --fix .
来源：http://dali.ydzc1.top/Article/details/gtenjnqitw.html

[U33] Py：打包发布
来源：http://dali.yj20258.top/Article/details/gtmcxowedr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj20258888.top/Article/details/gtiyhjowor.html

[U34] Py：判断编码
来源：http://dali.fengsongda.top/Article/details/gtqyxoidmn.html

chardet.detect(raw)
来源：http://dali.chenjidiqi.icu/Article/details/gtpspgnbow.html

[U35] Py：发送邮件
来源：http://dali.chenjidiqi.icu/Article/details/gtraewlmrw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.daxiang520.top/Article/details/gtsksggfqo.html

[U36] Py：定时任务
来源：http://dali.xylfe.cn/Article/details/gtjqbrcexu.html

schedule.every(10).minutes.do(job)
来源：http://dali.shuidangran.top/Article/details/gtdwakkarr.html

[U37] Py：读写 Excel
来源：http://dali.xziqi.cn/Article/details/gtdjxvoosv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinqigufen.top/Article/details/gtyvtxftef.html

[U38] Py：获取脚本所在目录
来源：http://dali.xziqi.cn/Article/details/gtygsamspi.html

Path(__file__).resolve().parent
来源：http://dali.dianchejie.cn/Article/details/gtcwaydgld.html

[U39] Py：判断是否在交互环境
来源：http://dali.hnqzz.top/Article/details/gtghvpiiyf.html

sys.stdout.isatty()
来源：http://dali.daria6918.cn/Article/details/gtrzzgbmzc.html

[U40] Py：打印到标准错误
来源：http://dali.nwbrower.top/Article/details/gttkpxqkwe.html

print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gtddcozcel.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.vqdsnc.cn/Article/details/gtsicotkrq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.feifeiyinyue.top/Article/details/gtqarkzajv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ehwqpu.com/Article/details/gtvordxzgs.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hysaishi.cn/Article/details/gtzyxvqmad.html

[U43] PHP：声明命名空间
来源：http://dali.bjfxy.top/Article/details/gtlmikrmvp.html

namespace App\Http;
来源：http://dali.guannengcc.top/Article/details/gtceotvsmk.html

[U44] PHP：开启严格类型
来源：http://dali.cashguo.top/Article/details/gtqbckrykj.html

declare(strict_types=1);
来源：http://dali.chenjidiqi.icu/Article/details/gtajyhfqtr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.svipenyu.cn/Article/details/gtmztmptqa.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbhiyccp.html

[U46] PHP：可空类型
来源：http://dali.hammf.cn/Article/details/gtnqupslid.html

?string $name = null
来源：http://dali.zhoulong.xyz/Article/details/gtnnzmmmvd.html

[U47] PHP：联合类型
来源：http://dali.jinqigufen.top/Article/details/gtbwwgvtqu.html

int|string $id
来源：http://dali.fengsongda.top/Article/details/gtaqjsepaz.html

[U48] PHP：纯枚举
来源：http://dali.yj202588.top/Article/details/gtapmlfggm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.tianlin.xyz/Article/details/gtcnqotlfj.html

[U49] PHP：只读属性
来源：http://dali.xziqi.cn/Article/details/gtfvbmxwdu.html

public readonly string $name
来源：http://dali.shangyingyoupin.top/Article/details/gtnryxyagp.html

[U50] PHP：构造器属性提升
来源：http://dali.shzxlz.cn/Article/details/gtklrsregt.html

public function __construct(private int $id) {}
来源：http://dali.ybcxt.top/Article/details/gteqsksrax.html

[U51] PHP：数组解构
来源：http://dali.chenzaomai.com/Article/details/gtzwutzfvi.html

[$a, $b] = $arr;
来源：http://dali.pycfn.com/Article/details/gtsokabqbj.html

[U52] PHP：箭头函数
来源：http://dali.ivvv.top/Article/details/gtmielimzj.html

$double = fn($x) => $x * 2;
来源：http://dali.dianchejie.cn/Article/details/gtowmicpvp.html

[U53] PHP：空合并运算符
来源：http://dali.yuanzhike.top/Article/details/gtmesdxpmt.html

$v = $a ?? $b ?? "default";
来源：http://dali.shangyingyoupin.top/Article/details/gtrlilvggb.html

[U54] PHP：空安全调用
来源：http://dali.zhongyouzk.top/Article/details/gtuqdwnqkc.html

$obj?->method()
来源：http://dali.hongshengwenyu.top/Article/details/gtzrebhiry.html

[U55] PHP：match 表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtbtvvnljt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yueranfly.top/Article/details/gtttmeclea.html

[U56] PHP：命名参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gthskfswvi.html

f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gtbueppwvc.html

[U57] PHP：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfgancqn.html

"值: {$a}"
来源：http://dali.ehwqpu.com/Article/details/gtszbcendb.html

[U58] PHP：数组三件套
来源：http://dali.guannengcc.top/Article/details/gtavsjsslo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hysaishi.cn/Article/details/gthjtxocls.html

[U59] PHP：自定义排序
来源：http://dali.shzxlz.cn/Article/details/gtxjdakzxm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ehwqpu.com/Article/details/gtmraiwijy.html

[U60] PHP：JSON 编解码
来源：http://dali.pengpengdd.cyou/Article/details/gtdwujdimn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.fengsongda.top/Article/details/gtfqywkutp.html

[U61] PHP：正则
来源：http://dali.hnxiangtu.top/Article/details/gtzhsvvtlp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gtxwtgddzr.html

[U62] PHP：日期对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzciwynm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.vqdsnc.cn/Article/details/gtugvhvuok.html

[U63] PHP：文件读写
来源：http://dali.yonumen.top/Article/details/gthvhspgvu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.haohaochexian.top/Article/details/gtoyjkghlh.html

[U64] PHP：目录遍历
来源：http://dali.svipenyu.cn/Article/details/gtgsyknfaw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.meibo888.top/Article/details/gtwilhjhms.html

[U65] PHP：会话
来源：http://dali.pycfn.com/Article/details/gtsmbrhdaj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtwpjvsnfv.html

[U66] PHP：设置 Cookie
来源：http://dali.gzhubu.top/Article/details/gtvjkfzeqh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.quarkkingdee.top/Article/details/gtpoyolwus.html

[U67] PHP：处理文件上传
来源：http://dali.xylfe.cn/Article/details/gtxeigzeoz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.snrcjt.cn/Article/details/gtgbafedkj.html

[U68] PHP：PDO 连接
来源：http://dali.jianghu66.top/Article/details/gtkwdsuwbi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.havefunace.top/Article/details/gtufwmadik.html

[U69] PHP：PDO 预处理
来源：http://dali.bjfxy.top/Article/details/gtsiimmasv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrkbytoe.html

[U70] PHP：PDO 事务
来源：http://dali.jlsjyb.cn/Article/details/gtzwececep.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hongshengwenyu.top/Article/details/gtdnmjydnw.html

[U71] PHP：抛出异常
来源：http://dali.xziqi.cn/Article/details/gtiqzykmha.html

throw new RuntimeException("失败", 500);
来源：http://dali.yj20258.top/Article/details/gtnlnpokhi.html

[U72] PHP：写错误日志
来源：http://dali.sweek.top/Article/details/gtumsemffg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.vqdsnc.cn/Article/details/gtyjxhxibl.html

[U73] PHP：读取 ini 配置
来源：http://dali.fzhhl.top/Article/details/gtsgjsduyk.html

parse_ini_file("config.ini", true)
来源：http://dali.kuanghao11.cn/Article/details/gtgvxlitwy.html

[U74] PHP：读取环境变量
来源：http://dali.sxryk.cn/Article/details/gtrppfgtkp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.chenlongwang.top/Article/details/gtgcvcarob.html

[U75] PHP：依赖注入
来源：http://dali.daria6918.cn/Article/details/gtegbgetvc.html

composer require psr/container
来源：http://dali.gaohongyu789.top/Article/details/gtjwbrhxde.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gtdbjtirpj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.aibaodan.cn/Article/details/gthwrreody.html

[U77] PHP：模板渲染
来源：http://dali.feifeiyinyue.top/Article/details/gtnojwhprx.html

composer require twig/twig
来源：http://dali.smart0.xyz/Article/details/gtmqvzkelc.html

[U78] PHP：单元测试
来源：http://dali.316326.xyz/Article/details/gtpzpgnvnv.html

composer require --dev phpunit/phpunit
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhnyfmbi.html

[U79] PHP：静态分析
来源：http://dali.zhoulong.xyz/Article/details/gtlvijniza.html

composer require --dev phpstan/phpstan
来源：http://dali.cdnleiting.top/Article/details/gteqtpddly.html

[U80] PHP：代码规范修复
来源：http://dali.cashguo.top/Article/details/gtkgfjvlup.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yuxming.cn/Article/details/gtyhfmxocp.html

[U81] JS：初始化项目
来源：http://dali.shangyingyoupin.top/Article/details/gtzpvjvfkj.html

npm init -y;  npm i express
来源：http://dali.shzxlz.cn/Article/details/gttjokqlzs.html

[U82] JS：package.json 脚本
来源：http://dali.sysykeji.top/Article/details/gtrlcvyqbu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.iojbl.cn/Article/details/gtdfhhrrgq.html

[U83] JS：ES Module 导入导出
来源：http://dali.shzxlz.cn/Article/details/gtheeqhcpm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhongyouzk.top/Article/details/gtzifolvko.html

[U84] JS：CommonJS 写法
来源：http://dali.tianlin.xyz/Article/details/gthfvxfykt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ehwqpu.com/Article/details/gtqdqborhu.html

[U85] JS：可选链
来源：http://dali.sufxvd.cn/Article/details/gtlmsfojbd.html

a?.b?.c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvakrjphk.html

[U86] JS：空值合并
来源：http://dali.jyoumei.cn/Article/details/gtbybmgnot.html

a ?? b
来源：http://dali.ivvv.top/Article/details/gthmdzektw.html

[U87] JS：解构默认值
来源：http://dali.zhengqikj.top/Article/details/gtkqeazxht.html

const { a = 1, b = 2 } = obj;
来源：http://dali.nanxuanxn.top/Article/details/gtcrgdorjn.html

[U88] JS：对象展开合并
来源：http://dali.xziqi.cn/Article/details/gtrxzvlubz.html

{ ...a, ...b }
来源：http://dali.cashguo.top/Article/details/gtkgsneanq.html

[U89] JS：数组去重
来源：http://dali.yuanzhike.top/Article/details/gtaiqjbvjn.html

[...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gthcdamezj.html

[U90] JS：数字数组排序
来源：http://dali.guowangkeji.top/Article/details/gtbznmfsuj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gthveplvvu.html

[U91] JS：对象键值遍历
来源：http://dali.xylfe.cn/Article/details/gtpssalada.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shuidangran.top/Article/details/gtqyoaexyr.html

[U92] JS：深拷贝
来源：http://dali.yuxming.cn/Article/details/gtiqazkbcb.html

structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtrekfidph.html


<!-- 参考信息 -->