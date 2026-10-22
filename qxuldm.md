代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.bjfxy.top/Article/details/gtsqiaujck.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fengsongda.top/Article/details/gtzsfgexzn.html

[T06] Kotlin：集合映射
来源：http://dali.aizwys.cn/Article/details/gttdogmvag.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtryxmcvnl.html

[T07] Kotlin：集合过滤
来源：http://dali.sysykeji.top/Article/details/gtokigffxn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtndlsaikw.html

[T08] Kotlin：数据类
来源：http://dali.shangyingyoupin.top/Article/details/gtfkzchkkp.html

data class User(val name: String, val age: Int)
来源：http://dali.pengpengdd.cyou/Article/details/gtgtlzxjxy.html

[T09] Kotlin：扩展函数
来源：http://dali.zdqjudy.top/Article/details/gtyrpasqxd.html

fun String.exclaim() = this + "!"
来源：http://dali.hysaishi.cn/Article/details/gtlxxeqprf.html

[T10] Kotlin：默认参数
来源：http://dali.shzxlz.cn/Article/details/gtmqdukzcp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.iojbl.cn/Article/details/gtqkfbmyvm.html

[T11] Kotlin：协程
来源：http://dali.jinqigufen.top/Article/details/gtziqimmlg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhengqikj.top/Article/details/gtzmxrwgcb.html

[T12] Kotlin：解构声明
来源：http://dali.gzhubu.top/Article/details/gttrxmlhii.html

val (a, b) = Pair(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtzfywgyys.html

[T13] Kotlin：只读 Map
来源：http://dali.shzxlz.cn/Article/details/gthmvnrniq.html

val m = mapOf("a" to 1)
来源：http://dali.birdmap.top/Article/details/gtingsxbab.html

[T14] Kotlin：循环
来源：http://dali.zhengqikj.top/Article/details/gtlrxsopkw.html

for (i in 1..10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gtyljdfafy.html

[T15] Kotlin：接口
来源：http://dali.hongshengwenyu.top/Article/details/gtanyyoesf.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvogqbqt.html

[T16] Swift：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatortiry.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gtajoizhjg.html

[T17] Swift：变量与常量
来源：http://dali.ehwqpu.com/Article/details/gtcnczmevq.html

var a = 1;  let b = 2
来源：http://dali.jinqigufen.top/Article/details/gtszbxfqgk.html

[T18] Swift：字符串插值
来源：http://dali.shuidangran.top/Article/details/gtecusdztl.html

"值: \(b)"
来源：http://dali.sweek.top/Article/details/gtsenmbqal.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwlqqwee.html

if let n = opt { print(n) }
来源：http://dali.shzxlz.cn/Article/details/gtenqdrfun.html

[T20] Swift：数组操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbibsehqx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpshdfpu.html

[T21] Swift：遍历
来源：http://dali.daxiang520.top/Article/details/gtlcboyaza.html

for x in a { print(x) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgiiuzoui.html

[T22] Swift：字典
来源：http://dali.dashuyun.cn/Article/details/gtxmwfocpz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtvkviphux.html

[T23] Swift：函数
来源：http://dali.gogol.net.cn/Article/details/gtehigfimn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tian-w.cn/Article/details/gtpyjvkqer.html

[T24] Swift：闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugguixvt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.redwolf501.top/Article/details/gtwjjpyjlr.html

[T25] Swift：结构体
来源：http://dali.nwbrower.top/Article/details/gtqtenvnbv.html

struct P { var x: Int }
来源：http://dali.yonumen.top/Article/details/gtmkfkhtxo.html

[T26] Swift：类与重写
来源：http://dali.daxiang520.top/Article/details/gtvwvfeqfy.html

class A: Base { override func f() {} }
来源：http://dali.xylfe.cn/Article/details/gthrfwzxhw.html

[T27] Swift：错误处理
来源：http://dali.gaohongyu789.top/Article/details/gtinnlxhnz.html

do { try f() } catch { print(error) }
来源：http://dali.aizwys.cn/Article/details/gtklisaovz.html

[T28] Swift：枚举
来源：http://dali.tanke756.top/Article/details/gtijlcmsiz.html

enum Color { case red, green }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuktrpgk.html

[T29] Swift：guard 提前返回
来源：http://dali.havefunace.top/Article/details/gtdtpgioti.html

guard let x = opt else { return }
来源：http://dali.xylfe.cn/Article/details/gtblitlzqh.html

[T30] Swift：协议
来源：http://dali.nwbrower.top/Article/details/gtedqkinez.html

protocol Shape { func area() -> Double }
来源：http://dali.shangyingyoupin.top/Article/details/gtquexihfa.html

[T31] Lua：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtetxtdcnf.html

print("Hello")
来源：http://dali.ydzc1.top/Article/details/gtlijgxoxx.html

[T32] Lua：局部变量
来源：http://dali.zhongyouzk.top/Article/details/gteutbexgk.html

local a = 1
来源：http://dali.xziqi.cn/Article/details/gtxnwfehxq.html

[T33] Lua：表（数组）
来源：http://dali.gotoacloud.top/Article/details/gtvnalerph.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sufxvd.cn/Article/details/gtxjxkqgbv.html

[T34] Lua：遍历表
来源：http://dali.shzxlz.cn/Article/details/gtcsduevda.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagmiosue.html

[T35] Lua：字典表
来源：http://dali.jinqigufen.top/Article/details/gtxhnemcpe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hammf.cn/Article/details/gttlwaccic.html

[T36] Lua：函数
来源：http://dali.hammf.cn/Article/details/gtiaxgdmzq.html

function add(a, b) return a + b end
来源：http://dali.meibo888.top/Article/details/gtbsiwbatt.html

[T37] Lua：字符串拼接
来源：http://dali.fzhhl.top/Article/details/gthbsiwhlb.html

"a" .. "b"
来源：http://dali.ivvv.top/Article/details/gtohrtbtgf.html

[T38] Lua：条件
来源：http://dali.xuetiantiany.cn/Article/details/gtjenozdqc.html

if x > 0 then print("正") end
来源：http://dali.gotoacloud.top/Article/details/gttycfwhce.html

[T39] Lua：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtlqjcieti.html

string.find(s, "%d+")
来源：http://dali.zhiwuduotai.top/Article/details/gtfuutizof.html

[T40] Lua：元表
来源：http://dali.hnxiangtu.top/Article/details/gtaruetlrh.html

setmetatable({}, { __index = base })
来源：http://dali.jianghu66.top/Article/details/gtvligpldw.html

[T41] Perl：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtmsrprewb.html

print "Hello\n";
来源：http://dali.jqgufenzy.top/Article/details/gtrfqkkoeb.html

[T42] Perl：变量类型
来源：http://dali.pengpengdd.cyou/Article/details/gtyuxrbcye.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yonumen.top/Article/details/gtckrxfppv.html

[T43] Perl：字符串插值
来源：http://dali.xylfe.cn/Article/details/gttvlhsozg.html

"值: $a"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqjbahbw.html

[T44] Perl：条件
来源：http://dali.jiagoushi.top/Article/details/gtwbuclrcm.html

if ($a > 0) { print "正"; }
来源：http://dali.hnqzz.top/Article/details/gtaczekmpu.html

[T45] Perl：数组遍历
来源：http://dali.pycfn.com/Article/details/gtzyrgfazz.html

for my $x (@arr) { print $x; }
来源：http://dali.haohaochexian.top/Article/details/gtjmcictgh.html

[T46] Perl：哈希操作
来源：http://dali.chenjidiqi.icu/Article/details/gtlyzbixuc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.dashuyun.cn/Article/details/gtuofbapzx.html

[T47] Perl：正则捕获
来源：http://dali.havefunace.top/Article/details/gtvkexgckc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ppjwa.cn/Article/details/gtgihyjvbq.html

[T48] Perl：正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsqagbpe.html

$s =~ s/old/new/g;
来源：http://dali.smart0.xyz/Article/details/gtaztalsaw.html

[T49] Perl：函数
来源：http://dali.yj202588.top/Article/details/gtemknsuwb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gtikyunzfh.html

[T50] Perl：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtivsuizna.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.c1oappe.top/Article/details/gtnemmtlix.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxaburzw.html

[T51] Scala：Hello World
来源：http://dali.cqqwz.cn/Article/details/gttdtsowba.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtaiarrvus.html

[T52] Scala：变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagpiaxcq.html

val a = 1;  var b = 2
来源：http://dali.nanxinkj.top/Article/details/gtvpdufvmy.html

[T53] Scala：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtwurranyy.html

s"值: $b"
来源：http://dali.sweek.top/Article/details/gtqudwrtyj.html

[T54] Scala：集合映射
来源：http://dali.yueranfly.top/Article/details/gtalmkddat.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jianghu66.top/Article/details/gtzulxbjjn.html

[T55] Scala：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gthooqbonn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.feifeiyinyue.top/Article/details/gttimdsckq.html

[T56] Scala：样例类
来源：http://dali.bjfxy.top/Article/details/gtpydxfrrf.html

case class User(name: String, age: Int)
来源：http://dali.jqgfzy.top/Article/details/gtqlhfqzpd.html

[T57] Scala：模式匹配
来源：http://dali.nanxuanxn.top/Article/details/gtythppflp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hammf.cn/Article/details/gtenmaxyuj.html

[T58] Scala：函数定义
来源：http://dali.chenjidiqi.icu/Article/details/gtckgyxaos.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.316326.xyz/Article/details/gtsggqwzng.html

[T59] Scala：循环
来源：http://dali.shangyingyoupin.top/Article/details/gtwxuuzyie.html

for (i <- 1 to 10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gtjwysfloq.html

[T60] Scala：折叠
来源：http://dali.yuxming.cn/Article/details/gtoiazsgyg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gaohongyu789.top/Article/details/gtsyktmwhx.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtzpkwehyy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258.top/Article/details/gtrwsmdbov.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtrjzadhur.html

[U01] Py：创建虚拟环境
来源：http://dali.chenjidiqi.icu/Article/details/gtncejcsru.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.andypj.xyz/Article/details/gtbuuqzpoa.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenlongwang.top/Article/details/gttpadmtfk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtnjtdauho.html

[U03] Py：加载 .env 配置
来源：http://dali.sufxvd.cn/Article/details/gtsgqpstoi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuanzx.com/Article/details/gtdqqjvchz.html

[U04] Py：变量调试打印
来源：http://dali.jqgufenzy.top/Article/details/gtcbglxzvx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhongyouzk.top/Article/details/gtfidhslfu.html

[U05] Py：列表去重且保序
来源：http://dali.cqqwz.cn/Article/details/gtculgjxyh.html

list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gtrknpksfp.html

[U06] Py：合并两个字典
来源：http://dali.zhixingplan.top/Article/details/gtoazgqlno.html

{**a, **b}
来源：http://dali.svipenyu.cn/Article/details/gtvhlvizjy.html

[U07] Py：反转字典键值
来源：http://dali.gogol.net.cn/Article/details/gtoyspwwnq.html

{v: k for k, v in d.items()}
来源：http://dali.bjfxy.top/Article/details/gtjojvlihk.html

[U08] Py：展平二维列表
来源：http://dali.yvedp.cn/Article/details/gtzbdxxjcs.html

[y for x in nested for y in x]
来源：http://dali.dashuyun.cn/Article/details/gtsezunszc.html

[U09] Py：字典取最大值的键
来源：http://dali.ybcxt.top/Article/details/gtqhvtspjs.html

max(d, key=d.get)
来源：http://dali.jqgfzy.top/Article/details/gtsgbhdhwj.html

[U10] Py：按值排序字典
来源：http://dali.ppjwa.cn/Article/details/gtrkzblwhz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.aizwys.cn/Article/details/gtkczncoqs.html

[U11] Py：生成器表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcbrrjzt.html

(x * 2 for x in arr)
来源：http://dali.smart0.xyz/Article/details/gtrbkpinkg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.snrcjt.cn/Article/details/gtodookoxo.html

Counter(arr).most_common(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtlxvfldgq.html

[U13] Py：固定长度队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhkowfoz.html

deque(maxlen=10)
来源：http://dali.hywenlv.cn/Article/details/gtlsmcqmky.html

[U14] Py：分组收集到列表
来源：http://dali.haohaochexian.top/Article/details/gthhvnsgtp.html

defaultdict(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtgtivslku.html

[U15] Py：高精度计时
来源：http://dali.aibaodan.cn/Article/details/gtcxkfcryj.html

t = time.perf_counter()
来源：http://dali.havefunace.top/Article/details/gtdqnxeoav.html

[U16] Py：命令行参数解析
来源：http://dali.gotoacloud.top/Article/details/gtsnnihlsd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yueranfly.top/Article/details/gtnnlrzqln.html

[U17] Py：初始化日志
来源：http://dali.gaohongyu789.top/Article/details/gtxgeigcvm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.haohaochexian.top/Article/details/gtmlwzuate.html

[U18] Py：预编译正则
来源：http://dali.xinyue.icu/Article/details/gtlfyercty.html

pat = re.compile(r"\d+")
来源：http://dali.mhx1999.top/Article/details/gtmnrhayld.html

[U19] Py：正则替换带回调
来源：http://dali.9152youxi.cn/Article/details/gttfdlzmim.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jqgfzy.top/Article/details/gtmuxqfqgc.html

[U20] Py：缓存函数结果
来源：http://dali.mhx1999.top/Article/details/gtjzkivitz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jqgufenzy.top/Article/details/gtoeudrdjj.html

[U21] Py：自定义上下文管理器
来源：http://dali.ybcxt.top/Article/details/gtklrgatiu.html

@contextlib.contextmanager
来源：http://dali.quarkkingdee.top/Article/details/gtnqdavqne.html

[U22] Py：矩阵转置
来源：http://dali.svipenyu.cn/Article/details/gtlykmjnhv.html

list(zip(*m))
来源：http://dali.cucudq.cn/Article/details/gtuvqcaxjj.html

[U23] Py：分块读取大文件
来源：http://dali.zycfv.cn/Article/details/gtngzvvvoc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenlongwang.top/Article/details/gtlpwkpadj.html

[U24] Py：路径操作
来源：http://dali.jiagoushi.top/Article/details/gtjfcifsvw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cucudq.cn/Article/details/gthrwpgyqt.html

[U25] Py：CSV 按字典读
来源：http://dali.birdmap.top/Article/details/gtcggmcwmq.html

csv.DictReader(f)
来源：http://dali.gzhubu.top/Article/details/gtsjuxxtrs.html

[U26] Py：并发下载
来源：http://dali.nanxinkj.top/Article/details/gtuhvhdlnz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jyoumei.cn/Article/details/gtxivkyelw.html

[U27] Py：异步 HTTP
来源：http://dali.yanxiufei.cn/Article/details/gtzrggjhtw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuxming.cn/Article/details/gtclwxnmdd.html

[U28] Py：类型别名
来源：http://dali.sufxvd.cn/Article/details/gttfzvfxns.html

UserId = int
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwatznyt.html

[U29] Py：属性校验
来源：http://dali.hongshengwenyu.top/Article/details/gtehqfjckn.html

@property 与 @x.setter 配合
来源：http://dali.yvedp.cn/Article/details/gtqfvoovlx.html

[U30] Py：数据类
来源：http://dali.jqgufenzy.top/Article/details/gtlsgyydaw.html

@dataclass(slots=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtkcnmcazx.html

[U31] Py：单测
来源：http://dali.yuxming.cn/Article/details/gtzyucmcef.html

python -m pytest -q
来源：http://dali.shzxlz.cn/Article/details/gtiaihaome.html

[U32] Py：代码格式化
来源：http://dali.smart0.xyz/Article/details/gtlfgyqqvl.html

ruff format . && ruff check --fix .
来源：http://dali.ydzc1.top/Article/details/gtwtxvynpm.html

[U33] Py：打包发布
来源：http://dali.nwbrower.top/Article/details/gtlehdmfgp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqctmhkfu.html

[U34] Py：判断编码
来源：http://dali.daxiang520.top/Article/details/gthcrqcoan.html

chardet.detect(raw)
来源：http://dali.yj20258.top/Article/details/gtilshvjsf.html

[U35] Py：发送邮件
来源：http://dali.redwolf501.top/Article/details/gtvogfjtwo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shzxlz.cn/Article/details/gtwjdazhrv.html

[U36] Py：定时任务
来源：http://dali.dianchejie.cn/Article/details/gthncfytsm.html

schedule.every(10).minutes.do(job)
来源：http://dali.cucudq.cn/Article/details/gtieqaeqiu.html

[U37] Py：读写 Excel
来源：http://dali.zhengqikj.top/Article/details/gtycoajfvi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.daria6918.cn/Article/details/gtizfcqvua.html

[U38] Py：获取脚本所在目录
来源：http://dali.sufxvd.cn/Article/details/gtklmxparv.html

Path(__file__).resolve().parent
来源：http://dali.redwolf501.top/Article/details/gtdoposeiu.html

[U39] Py：判断是否在交互环境
来源：http://dali.hnxiangtu.top/Article/details/gtebfxsakc.html

sys.stdout.isatty()
来源：http://dali.ydzc1.top/Article/details/gtxuyhgywy.html

[U40] Py：打印到标准错误
来源：http://dali.feifeiyinyue.top/Article/details/gttrolqvfn.html

print("err", file=sys.stderr)
来源：http://dali.dianchejie.cn/Article/details/gtxhjliblz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjylgqjqa.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.wangshuangyany.cn/Article/details/gtucbqvtaw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.snrcjt.cn/Article/details/gtrdzbumuo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.daria6918.cn/Article/details/gtppfdqzyz.html

[U43] PHP：声明命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gtnvgposrk.html

namespace App\Http;
来源：http://dali.chenzaomai.com/Article/details/gtyodozjft.html

[U44] PHP：开启严格类型
来源：http://dali.guowangkeji.top/Article/details/gtvwolathc.html

declare(strict_types=1);
来源：http://dali.yj20258.top/Article/details/gtfpbickvy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.guannengcc.top/Article/details/gtagqeegqi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtvofxbspy.html

[U46] PHP：可空类型
来源：http://dali.zhengqikj.top/Article/details/gtfosuvorj.html

?string $name = null
来源：http://dali.shangyingyoupin.top/Article/details/gtjznoekqi.html

[U47] PHP：联合类型
来源：http://dali.fengsongda.top/Article/details/gtpowissud.html

int|string $id
来源：http://dali.gaohongyu789.top/Article/details/gtzioluifg.html

[U48] PHP：纯枚举
来源：http://dali.pycfn.com/Article/details/gtezjdxoqe.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jyoumei.cn/Article/details/gtizpmxonr.html

[U49] PHP：只读属性
来源：http://dali.aizwys.cn/Article/details/gttvrdjjoh.html

public readonly string $name
来源：http://dali.pycfn.com/Article/details/gtykinnkaj.html

[U50] PHP：构造器属性提升
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwjhzcti.html

public function __construct(private int $id) {}
来源：http://dali.hammf.cn/Article/details/gtotcbltze.html

[U51] PHP：数组解构
来源：http://dali.9152youxi.cn/Article/details/gtdtsrxdkq.html

[$a, $b] = $arr;
来源：http://dali.ybcxt.top/Article/details/gtfirjoini.html

[U52] PHP：箭头函数
来源：http://dali.shuidangran.top/Article/details/gtmwmappbw.html

$double = fn($x) => $x * 2;
来源：http://dali.zycfv.cn/Article/details/gtgdofeepq.html

[U53] PHP：空合并运算符
来源：http://dali.cdnleiting.top/Article/details/gtfdbyrdej.html

$v = $a ?? $b ?? "default";
来源：http://dali.yonumen.top/Article/details/gtsuaqfmwg.html

[U54] PHP：空安全调用
来源：http://dali.xuetiantiany.cn/Article/details/gtlexfluai.html

$obj?->method()
来源：http://dali.gotoacloud.top/Article/details/gtcsjgkmhi.html

[U55] PHP：match 表达式
来源：http://dali.mhx1999.top/Article/details/gtobooxual.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yuxming.cn/Article/details/gtizzhtqtr.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gtamfmpmwn.html

f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenvyfstu.html

[U57] PHP：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtxykxfdij.html

"值: {$a}"
来源：http://dali.ydzc1.top/Article/details/gtopywrnqq.html

[U58] PHP：数组三件套
来源：http://dali.aibaodan.cn/Article/details/gtvqwuzban.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ppjwa.cn/Article/details/gtvwdfvigb.html

[U59] PHP：自定义排序
来源：http://dali.cucudq.cn/Article/details/gtlfwhjopz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yongpay.top/Article/details/gtatvxvlyw.html

[U60] PHP：JSON 编解码
来源：http://dali.yanxiufei.cn/Article/details/gtoifnoqcr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.316326.xyz/Article/details/gtrvtzavds.html

[U61] PHP：正则
来源：http://dali.yongpay.top/Article/details/gtsyrrzfda.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gtorfybxgd.html

[U62] PHP：日期对象
来源：http://dali.aibaodan.cn/Article/details/gtzrbsbreo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hongshengwenyu.top/Article/details/gtybxpqxos.html

[U63] PHP：文件读写
来源：http://dali.aizwys.cn/Article/details/gtrjpxqjhq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hnqzz.top/Article/details/gtwyldjbio.html

[U64] PHP：目录遍历
来源：http://dali.jinqigfzy.top/Article/details/gtusmhmopy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhengqikj.top/Article/details/gtuloakqey.html

[U65] PHP：会话
来源：http://dali.bjfxy.top/Article/details/gtyjjjqrmu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtloquziqz.html

[U66] PHP：设置 Cookie
来源：http://dali.nwbrower.top/Article/details/gtqyjmyncj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jqgfzy.top/Article/details/gtqatazdkr.html

[U67] PHP：处理文件上传
来源：http://dali.0kj1m.cn/Article/details/gtbjvscsur.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.smart0.xyz/Article/details/gtnhnwgfaj.html

[U68] PHP：PDO 连接
来源：http://dali.havefunace.top/Article/details/gtfwosiccc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.bjfxy.top/Article/details/gtjnucxzyy.html

[U69] PHP：PDO 预处理
来源：http://dali.dianchejie.cn/Article/details/gtboiilpnb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.9152youxi.cn/Article/details/gtzlizgojq.html

[U70] PHP：PDO 事务
来源：http://dali.chenjidiqi.icu/Article/details/gtrbfclkky.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yonumen.top/Article/details/gtbxusycnf.html

[U71] PHP：抛出异常
来源：http://dali.smart0.xyz/Article/details/gthkmtwpvv.html

throw new RuntimeException("失败", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gtvqyfmzjf.html

[U72] PHP：写错误日志
来源：http://dali.guowangkeji.top/Article/details/gtisakgeic.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hfpthk.cn/Article/details/gttklcyfmy.html

[U73] PHP：读取 ini 配置
来源：http://dali.nanxuanxn.top/Article/details/gtmdcltztd.html

parse_ini_file("config.ini", true)
来源：http://dali.jinqigfzy.top/Article/details/gtaniboijt.html

[U74] PHP：读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtkyvgystf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.0kj1m.cn/Article/details/gtltunyopm.html

[U75] PHP：依赖注入
来源：http://dali.mhx1999.top/Article/details/gtpwixxmcm.html

composer require psr/container
来源：http://dali.hnqzz.top/Article/details/gtahslkqgf.html

[U76] PHP：简单路由
来源：http://dali.sysykeji.top/Article/details/gtkiwnltqd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hywenlv.cn/Article/details/gtgkutkzjz.html

[U77] PHP：模板渲染
来源：http://dali.jinqigufen.top/Article/details/gtkgsdawom.html

composer require twig/twig
来源：http://dali.nwbrower.top/Article/details/gthnajfgcs.html

[U78] PHP：单元测试
来源：http://dali.zdqjudy.top/Article/details/gtjqommbsb.html

composer require --dev phpunit/phpunit
来源：http://dali.sweek.top/Article/details/gthewffzof.html

[U79] PHP：静态分析
来源：http://dali.snrcjt.cn/Article/details/gtqrlkaqls.html

composer require --dev phpstan/phpstan
来源：http://dali.yuxming.cn/Article/details/gtzjtrggla.html

[U80] PHP：代码规范修复
来源：http://dali.gogol.net.cn/Article/details/gthhyiqtqq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgufenzy.top/Article/details/gtfrbvbzrd.html

[U81] JS：初始化项目
来源：http://dali.yonumen.top/Article/details/gttqesmsxc.html

npm init -y;  npm i express
来源：http://dali.yj20258.top/Article/details/gtinxryoxz.html

[U82] JS：package.json 脚本
来源：http://dali.ivvv.top/Article/details/gtmilnnsmx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.gotoacloud.top/Article/details/gtwqhfinqi.html

[U83] JS：ES Module 导入导出
来源：http://dali.gotoacloud.top/Article/details/gtyvlcaqcn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.tian-w.cn/Article/details/gtyqvsmeum.html

[U84] JS：CommonJS 写法
来源：http://dali.gzhubu.top/Article/details/gtdlrufpwe.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.iojbl.cn/Article/details/gthwdszuwo.html

[U85] JS：可选链
来源：http://dali.hnqzz.top/Article/details/gtfghspkcz.html

a?.b?.c
来源：http://dali.fzhhl.top/Article/details/gtgtvyitpy.html

[U86] JS：空值合并
来源：http://dali.fzhhl.top/Article/details/gtxwbxkqwv.html

a ?? b
来源：http://dali.cashguo.top/Article/details/gterncqwoh.html

[U87] JS：解构默认值
来源：http://dali.aizwys.cn/Article/details/gtkuoycroa.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xinyue.icu/Article/details/gtlyylsiwi.html

[U88] JS：对象展开合并
来源：http://dali.jinqigufen.top/Article/details/gtzqgrwgwr.html

{ ...a, ...b }
来源：http://dali.aibaodan.cn/Article/details/gtqrtnioyk.html

[U89] JS：数组去重
来源：http://dali.nanxinkj.top/Article/details/gtjvlrluin.html

[...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtlhwaboql.html

[U90] JS：数字数组排序
来源：http://dali.nanxuanxn.top/Article/details/gtaeuoqwbr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtmqmedtou.html

[U91] JS：对象键值遍历
来源：http://dali.daxiang520.top/Article/details/gttwlrwelw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.tian-w.cn/Article/details/gthzuyrtag.html

[U92] JS：深拷贝
来源：http://dali.gotoacloud.top/Article/details/gtllglggak.html

structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gtctjmuwmx.html


<!-- 参考信息 -->