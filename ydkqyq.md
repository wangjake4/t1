代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.andypj.xyz/Article/details/gtlocfifuf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sweek.top/Article/details/gtelvtlgyg.html

[T06] Kotlin：集合映射
来源：http://dali.zhoulong.xyz/Article/details/gtrnlyuyos.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhengqikj.top/Article/details/gtgokolhtr.html

[T07] Kotlin：集合过滤
来源：http://dali.guannengcc.top/Article/details/gtgffbzedc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tianlin.xyz/Article/details/gthoidkfam.html

[T08] Kotlin：数据类
来源：http://dali.daria6918.cn/Article/details/gtujcspobf.html

data class User(val name: String, val age: Int)
来源：http://dali.ybcxt.top/Article/details/gtboijptts.html

[T09] Kotlin：扩展函数
来源：http://dali.tianlin.xyz/Article/details/gtimbpqonm.html

fun String.exclaim() = this + "!"
来源：http://dali.hfpthk.cn/Article/details/gtbqktswfa.html

[T10] Kotlin：默认参数
来源：http://dali.yuxming.cn/Article/details/gtmtllkleg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.guannengcc.top/Article/details/gtnypezpcu.html

[T11] Kotlin：协程
来源：http://dali.hnxiangtu.top/Article/details/gtcvobwcbk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.svipenyu.cn/Article/details/gtfnabqhoh.html

[T12] Kotlin：解构声明
来源：http://dali.cqqwz.cn/Article/details/gtdxdoidcr.html

val (a, b) = Pair(1, 2)
来源：http://dali.birdmap.top/Article/details/gtnpztiddu.html

[T13] Kotlin：只读 Map
来源：http://dali.cdnleiting.top/Article/details/gtcprepgzg.html

val m = mapOf("a" to 1)
来源：http://dali.haohaochexian.top/Article/details/gtuueaihrr.html

[T14] Kotlin：循环
来源：http://dali.vqdsnc.cn/Article/details/gtxjzhzveg.html

for (i in 1..10) println(i)
来源：http://dali.tian-w.cn/Article/details/gtyuauagkf.html

[T15] Kotlin：接口
来源：http://dali.yueranfly.top/Article/details/gtlitybiii.html

interface Shape { fun area(): Double }
来源：http://dali.meibo888.top/Article/details/gtwgtfjdew.html

[T16] Swift：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtbjppsrfa.html

print("Hello")
来源：http://dali.yuxming.cn/Article/details/gtrjspkmvt.html

[T17] Swift：变量与常量
来源：http://dali.fzhhl.top/Article/details/gtiracpnnr.html

var a = 1;  let b = 2
来源：http://dali.jiagoushi.top/Article/details/gtenpsuexq.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtjumhkhcw.html

"值: \(b)"
来源：http://dali.cucudq.cn/Article/details/gthweqpbja.html

[T19] Swift：可选绑定
来源：http://dali.gaohongyu789.top/Article/details/gtxaojejcw.html

if let n = opt { print(n) }
来源：http://dali.dashuyun.cn/Article/details/gttwprwnar.html

[T20] Swift：数组操作
来源：http://dali.jinqigufen.top/Article/details/gtzlkjofgv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shzxlz.cn/Article/details/gtehfihqed.html

[T21] Swift：遍历
来源：http://dali.hnxiangtu.top/Article/details/gtqjqsmthb.html

for x in a { print(x) }
来源：http://dali.ivvv.top/Article/details/gtvexsrqfs.html

[T22] Swift：字典
来源：http://dali.c1oappe.top/Article/details/gteqajitrd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xziqi.cn/Article/details/gtlgtgyuup.html

[T23] Swift：函数
来源：http://dali.zhongyouzk.top/Article/details/gtfkkmkqvc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenlongwang.top/Article/details/gtvbdiyshc.html

[T24] Swift：闭包
来源：http://dali.andypj.xyz/Article/details/gthximjxzh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtddblutov.html

[T25] Swift：结构体
来源：http://dali.yangfankeji.com/Article/details/gtafwndfla.html

struct P { var x: Int }
来源：http://dali.yanxiufei.cn/Article/details/gturcrftmb.html

[T26] Swift：类与重写
来源：http://dali.fengsongda.top/Article/details/gtuaephlcx.html

class A: Base { override func f() {} }
来源：http://dali.snrcjt.cn/Article/details/gtedaifipe.html

[T27] Swift：错误处理
来源：http://dali.yj20258.top/Article/details/gtbupvhaxw.html

do { try f() } catch { print(error) }
来源：http://dali.zdqjudy.top/Article/details/gtcisjvfny.html

[T28] Swift：枚举
来源：http://dali.aizwys.cn/Article/details/gtsgdoipuw.html

enum Color { case red, green }
来源：http://dali.aibaodan.cn/Article/details/gtvridfogh.html

[T29] Swift：guard 提前返回
来源：http://dali.ppjwa.cn/Article/details/gtvqpfgnlj.html

guard let x = opt else { return }
来源：http://dali.wangshuangyany.cn/Article/details/gtoxnunvot.html

[T30] Swift：协议
来源：http://dali.chenlongwang.top/Article/details/gtbntmgipp.html

protocol Shape { func area() -> Double }
来源：http://dali.yuanzhike.top/Article/details/gtaumfuyjo.html

[T31] Lua：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtzqgtinde.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtzsjufqxp.html

[T32] Lua：局部变量
来源：http://dali.snrcjt.cn/Article/details/gtttizueba.html

local a = 1
来源：http://dali.redwolf501.top/Article/details/gtekptlynw.html

[T33] Lua：表（数组）
来源：http://dali.jianghu66.top/Article/details/gtkyklvdcl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ybcxt.top/Article/details/gtgjyxckuh.html

[T34] Lua：遍历表
来源：http://dali.snrcjt.cn/Article/details/gtdmgtlpze.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xylfe.cn/Article/details/gtnbhwnbxq.html

[T35] Lua：字典表
来源：http://dali.xziqi.cn/Article/details/gtzapkbvlr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtynsxklpj.html

[T36] Lua：函数
来源：http://dali.sufxvd.cn/Article/details/gtopxkwdpe.html

function add(a, b) return a + b end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkaxoyaky.html

[T37] Lua：字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gtzondahvn.html

"a" .. "b"
来源：http://dali.hammf.cn/Article/details/gtfkxxnhnu.html

[T38] Lua：条件
来源：http://dali.ivvv.top/Article/details/gtetehdvym.html

if x > 0 then print("正") end
来源：http://dali.hysaishi.cn/Article/details/gthrbcrich.html

[T39] Lua：模式匹配
来源：http://dali.birdmap.top/Article/details/gtojvsdezb.html

string.find(s, "%d+")
来源：http://dali.dashuyun.cn/Article/details/gtebkihqys.html

[T40] Lua：元表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssorgvnv.html

setmetatable({}, { __index = base })
来源：http://dali.gotoacloud.top/Article/details/gtmozlhriu.html

[T41] Perl：Hello World
来源：http://dali.guannengcc.top/Article/details/gtqbsuwjhg.html

print "Hello\n";
来源：http://dali.jinqigufen.top/Article/details/gtfxogsptr.html

[T42] Perl：变量类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppmonjuy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhoulong.xyz/Article/details/gtqbkdfqjf.html

[T43] Perl：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtlwskdjdu.html

"值: $a"
来源：http://dali.jinqigufen.top/Article/details/gtrplozgdn.html

[T44] Perl：条件
来源：http://dali.hongshengwenyu.top/Article/details/gtxfwxdbnv.html

if ($a > 0) { print "正"; }
来源：http://dali.ppjwa.cn/Article/details/gtbhsdskcp.html

[T45] Perl：数组遍历
来源：http://dali.zdqjudy.top/Article/details/gtsjnrgfgu.html

for my $x (@arr) { print $x; }
来源：http://dali.c1oappe.top/Article/details/gttksnodjh.html

[T46] Perl：哈希操作
来源：http://dali.cdnleiting.top/Article/details/gtcubybmcp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zycfv.cn/Article/details/gtvwcxclsz.html

[T47] Perl：正则捕获
来源：http://dali.tianlin.xyz/Article/details/gtyrycgkez.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnqzz.top/Article/details/gtdwvsxdqe.html

[T48] Perl：正则替换
来源：http://dali.zhengqikj.top/Article/details/gtuqckgewf.html

$s =~ s/old/new/g;
来源：http://dali.pengpengdd.cyou/Article/details/gtogdgapnm.html

[T49] Perl：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtkqlmhzky.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gtehxzzphp.html

[T50] Perl：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtvpgfpmwn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aibaodan.cn/Article/details/gtvnkiqsbi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.smart0.xyz/Article/details/gtoustamit.html

[T51] Scala：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtzfzpdqgp.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtbhzghliw.html

[T52] Scala：变量
来源：http://dali.tianlin.xyz/Article/details/gtpatdrdne.html

val a = 1;  var b = 2
来源：http://dali.yongpay.top/Article/details/gtxyueahug.html

[T53] Scala：字符串插值
来源：http://dali.andypj.xyz/Article/details/gtexgiijwc.html

s"值: $b"
来源：http://dali.havefunace.top/Article/details/gtkhcgqlzy.html

[T54] Scala：集合映射
来源：http://dali.gogol.net.cn/Article/details/gtploykfjp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.bjfxy.top/Article/details/gtzusfptgp.html

[T55] Scala：集合过滤
来源：http://dali.jianghu66.top/Article/details/gtemwkarpy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.kuanghao11.cn/Article/details/gtzdvbzyku.html

[T56] Scala：样例类
来源：http://dali.xylfe.cn/Article/details/gtmoustphu.html

case class User(name: String, age: Int)
来源：http://dali.zhengqikj.top/Article/details/gtwzoitmnu.html

[T57] Scala：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gtqomgmrrh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkiorilkr.html

[T58] Scala：函数定义
来源：http://dali.guannengcc.top/Article/details/gtyhyhmbzm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sxryk.cn/Article/details/gtgzuygags.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gtkepxrcmg.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgeylzpoz.html

[T60] Scala：折叠
来源：http://dali.jlsjyb.cn/Article/details/gtvelgpmze.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmyjfkght.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtzjfwglrb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.guowangkeji.top/Article/details/gtumqiqjge.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtyjnztzhq.html

[U01] Py：创建虚拟环境
来源：http://dali.cashguo.top/Article/details/gtbifkhrjp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sxryk.cn/Article/details/gtspbgyuid.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cqqwz.cn/Article/details/gtxafqaimw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yuanzhike.top/Article/details/gtzbvvbkdf.html

[U03] Py：加载 .env 配置
来源：http://dali.birdmap.top/Article/details/gtnxjjkllf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shangyingyoupin.top/Article/details/gtwyvsvqek.html

[U04] Py：变量调试打印
来源：http://dali.fzhhl.top/Article/details/gtccxmfwdn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gtqbojmlsq.html

[U05] Py：列表去重且保序
来源：http://dali.yvedp.cn/Article/details/gtgacscuvf.html

list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswuybmxb.html

[U06] Py：合并两个字典
来源：http://dali.jlsjyb.cn/Article/details/gtfmsvqfak.html

{**a, **b}
来源：http://dali.kuanghao11.cn/Article/details/gtxvmiflbr.html

[U07] Py：反转字典键值
来源：http://dali.cqqwz.cn/Article/details/gtterfuwml.html

{v: k for k, v in d.items()}
来源：http://dali.mhx1999.top/Article/details/gtmjhmnybx.html

[U08] Py：展平二维列表
来源：http://dali.shangyingyoupin.top/Article/details/gtupqcwdjz.html

[y for x in nested for y in x]
来源：http://dali.jiagoushi.top/Article/details/gtsjpvnytn.html

[U09] Py：字典取最大值的键
来源：http://dali.xuetiantiany.cn/Article/details/gtzzuxgkvr.html

max(d, key=d.get)
来源：http://dali.hywenlv.cn/Article/details/gtylzktpsu.html

[U10] Py：按值排序字典
来源：http://dali.sxryk.cn/Article/details/gtdeployzu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigfzy.top/Article/details/gtrusnrnlf.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbjelipn.html

(x * 2 for x in arr)
来源：http://dali.haohaochexian.top/Article/details/gtobxctnjf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.kuanghao11.cn/Article/details/gtkjkwwdvv.html

Counter(arr).most_common(3)
来源：http://dali.c1oappe.top/Article/details/gtibiqxkrr.html

[U13] Py：固定长度队列
来源：http://dali.jqgufenzy.top/Article/details/gtcmhmanuk.html

deque(maxlen=10)
来源：http://dali.dashuyun.cn/Article/details/gtsbmwjoed.html

[U14] Py：分组收集到列表
来源：http://dali.xuanzx.com/Article/details/gtxdiwrxwk.html

defaultdict(list)
来源：http://dali.c1oappe.top/Article/details/gtspbuoigj.html

[U15] Py：高精度计时
来源：http://dali.smart0.xyz/Article/details/gtyxbvqazx.html

t = time.perf_counter()
来源：http://dali.birdmap.top/Article/details/gtbuonjdfl.html

[U16] Py：命令行参数解析
来源：http://dali.chenlongwang.top/Article/details/gtqxqoygnm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.pycfn.com/Article/details/gtxnhqkqjr.html

[U17] Py：初始化日志
来源：http://dali.shzxlz.cn/Article/details/gtgvzpophk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yj202588.top/Article/details/gtqnerymqf.html

[U18] Py：预编译正则
来源：http://dali.sxryk.cn/Article/details/gtytkxxasc.html

pat = re.compile(r"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gtmozfromj.html

[U19] Py：正则替换带回调
来源：http://dali.daria6918.cn/Article/details/gtngplduxg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.bjfxy.top/Article/details/gttvgnjrfm.html

[U20] Py：缓存函数结果
来源：http://dali.cucudq.cn/Article/details/gtpjkhdpra.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yanxiufei.cn/Article/details/gtjttlpefc.html

[U21] Py：自定义上下文管理器
来源：http://dali.hongshengwenyu.top/Article/details/gtryttlxis.html

@contextlib.contextmanager
来源：http://dali.bjfxy.top/Article/details/gtlqaufqmb.html

[U22] Py：矩阵转置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyctvwbej.html

list(zip(*m))
来源：http://dali.bjfxy.top/Article/details/gtbgfyqfqh.html

[U23] Py：分块读取大文件
来源：http://dali.gotoacloud.top/Article/details/gtkebgznrj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.haohaochexian.top/Article/details/gtttsuftfj.html

[U24] Py：路径操作
来源：http://dali.jiagoushi.top/Article/details/gtczzjauze.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gtxjnhasuh.html

[U25] Py：CSV 按字典读
来源：http://dali.chenzaomai.com/Article/details/gtzjpkkvki.html

csv.DictReader(f)
来源：http://dali.yongpay.top/Article/details/gtmyvicihe.html

[U26] Py：并发下载
来源：http://dali.yonumen.top/Article/details/gtxaevoboe.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gzhubu.top/Article/details/gtufuwfidu.html

[U27] Py：异步 HTTP
来源：http://dali.sweek.top/Article/details/gtsxfnirlc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ybcxt.top/Article/details/gtxamumcjb.html

[U28] Py：类型别名
来源：http://dali.cdnleiting.top/Article/details/gtrsatqart.html

UserId = int
来源：http://dali.chenlongwang.top/Article/details/gtavzpwhtk.html

[U29] Py：属性校验
来源：http://dali.guowangkeji.top/Article/details/gtjotbzuam.html

@property 与 @x.setter 配合
来源：http://dali.zhiwuduotai.top/Article/details/gtvvhuytdp.html

[U30] Py：数据类
来源：http://dali.wangshuangyany.cn/Article/details/gtwwtdrhze.html

@dataclass(slots=True)
来源：http://dali.9152youxi.cn/Article/details/gtcevcsclk.html

[U31] Py：单测
来源：http://dali.nanxinkj.top/Article/details/gthojyansz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gtqstjidxk.html

[U32] Py：代码格式化
来源：http://dali.zycfv.cn/Article/details/gtpggqfpeq.html

ruff format . && ruff check --fix .
来源：http://dali.birdmap.top/Article/details/gtzjjfstxa.html

[U33] Py：打包发布
来源：http://dali.cucudq.cn/Article/details/gtgrjjfztd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nanxuanxn.top/Article/details/gthgmdsbjf.html

[U34] Py：判断编码
来源：http://dali.cucudq.cn/Article/details/gtkmqsqsbj.html

chardet.detect(raw)
来源：http://dali.gaohongyu789.top/Article/details/gtcyxhrycx.html

[U35] Py：发送邮件
来源：http://dali.tian-w.cn/Article/details/gtowuchuhq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.aibaodan.cn/Article/details/gtjmgfvipw.html

[U36] Py：定时任务
来源：http://dali.aibaodan.cn/Article/details/gtiyjoswmo.html

schedule.every(10).minutes.do(job)
来源：http://dali.xuanzx.com/Article/details/gtejnpibyk.html

[U37] Py：读写 Excel
来源：http://dali.hongshengwenyu.top/Article/details/gtijznplwm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jlsjyb.cn/Article/details/gtnxbwudxy.html

[U38] Py：获取脚本所在目录
来源：http://dali.andypj.xyz/Article/details/gtdwqpsjrt.html

Path(__file__).resolve().parent
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturczxayy.html

[U39] Py：判断是否在交互环境
来源：http://dali.tian-w.cn/Article/details/gtaftpjaon.html

sys.stdout.isatty()
来源：http://dali.gaohongyu789.top/Article/details/gtlcbhstem.html

[U40] Py：打印到标准错误
来源：http://dali.jlsjyb.cn/Article/details/gtisjufiqw.html

print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gtsohihppq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gotoacloud.top/Article/details/gtpqrgeekw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ivvv.top/Article/details/gtbdbrogzo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenzaomai.com/Article/details/gtvjpebcne.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.iojbl.cn/Article/details/gtkxwbfwkm.html

[U43] PHP：声明命名空间
来源：http://dali.zhengqikj.top/Article/details/gtaspjezmq.html

namespace App\Http;
来源：http://dali.aibaodan.cn/Article/details/gtazjuixxc.html

[U44] PHP：开启严格类型
来源：http://dali.zhongyouzk.top/Article/details/gtovzufxnb.html

declare(strict_types=1);
来源：http://dali.tian-w.cn/Article/details/gtyhzbgyjn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zycfv.cn/Article/details/gtzbdanfqd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gtpfnlhknq.html

[U46] PHP：可空类型
来源：http://dali.zhongyouzk.top/Article/details/gtkgrjkjzv.html

?string $name = null
来源：http://dali.meibo888.top/Article/details/gtlfyyaqos.html

[U47] PHP：联合类型
来源：http://dali.ivvv.top/Article/details/gtimmemqky.html

int|string $id
来源：http://dali.vqdsnc.cn/Article/details/gtyfgzbfds.html

[U48] PHP：纯枚举
来源：http://dali.yj202588.top/Article/details/gtgotoxzzl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sysykeji.top/Article/details/gttkbwnwlw.html

[U49] PHP：只读属性
来源：http://dali.yongpay.top/Article/details/gtlkjfehdb.html

public readonly string $name
来源：http://dali.hnqzz.top/Article/details/gtrdezznxm.html

[U50] PHP：构造器属性提升
来源：http://dali.guowangkeji.top/Article/details/gtymrdbfhv.html

public function __construct(private int $id) {}
来源：http://dali.daria6918.cn/Article/details/gtvytywgkj.html

[U51] PHP：数组解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccxrqsde.html

[$a, $b] = $arr;
来源：http://dali.ydzc1.top/Article/details/gtjiidqbvb.html

[U52] PHP：箭头函数
来源：http://dali.chenzaomai.com/Article/details/gtiviayhcs.html

$double = fn($x) => $x * 2;
来源：http://dali.hywenlv.cn/Article/details/gtzjgahxvj.html

[U53] PHP：空合并运算符
来源：http://dali.vqdsnc.cn/Article/details/gthoirfeik.html

$v = $a ?? $b ?? "default";
来源：http://dali.wangshuangyany.cn/Article/details/gtqeffdauv.html

[U54] PHP：空安全调用
来源：http://dali.jiagoushi.top/Article/details/gtwkknbboc.html

$obj?->method()
来源：http://dali.316326.xyz/Article/details/gtqjwipvkx.html

[U55] PHP：match 表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorsdohqx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.c1oappe.top/Article/details/gtilkssvwh.html

[U56] PHP：命名参数
来源：http://dali.tanke756.top/Article/details/gtmbsuwpyb.html

f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gteqqvqoyc.html

[U57] PHP：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gthupzrpoo.html

"值: {$a}"
来源：http://dali.aibaodan.cn/Article/details/gteuljcmgd.html

[U58] PHP：数组三件套
来源：http://dali.yj20258888.top/Article/details/gtyvtzuehh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.bjfxy.top/Article/details/gtcwuhnmfe.html

[U59] PHP：自定义排序
来源：http://dali.pycfn.com/Article/details/gtuslxtbdo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gtgraznifa.html

[U60] PHP：JSON 编解码
来源：http://dali.nwbrower.top/Article/details/gtjooefypx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yvedp.cn/Article/details/gtwkybdpnd.html

[U61] PHP：正则
来源：http://dali.haohaochexian.top/Article/details/gtpbqbryuq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.c1oappe.top/Article/details/gtdycbhsau.html

[U62] PHP：日期对象
来源：http://dali.yangfankeji.com/Article/details/gtvafjjczp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shuidangran.top/Article/details/gtjglqrajo.html

[U63] PHP：文件读写
来源：http://dali.dashuyun.cn/Article/details/gtzrdulgqz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.iojbl.cn/Article/details/gtaiamsfvb.html

[U64] PHP：目录遍历
来源：http://dali.sufxvd.cn/Article/details/gttofwapfg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkahhglu.html

[U65] PHP：会话
来源：http://dali.tian-w.cn/Article/details/gtqsrajzbs.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jianghu66.top/Article/details/gthcmfdrmj.html

[U66] PHP：设置 Cookie
来源：http://dali.tanke756.top/Article/details/gtppnhezwo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.tian-w.cn/Article/details/gtirsrxbih.html

[U67] PHP：处理文件上传
来源：http://dali.gotoacloud.top/Article/details/gtyqctmger.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yongpay.top/Article/details/gtrchmtkag.html

[U68] PHP：PDO 连接
来源：http://dali.jinqigfzy.top/Article/details/gtudnxojyl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yueranfly.top/Article/details/gtgurdnlsj.html

[U69] PHP：PDO 预处理
来源：http://dali.tian-w.cn/Article/details/gtvbpypurp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yonumen.top/Article/details/gttgyyeolc.html

[U70] PHP：PDO 事务
来源：http://dali.hongshengwenyu.top/Article/details/gticugevaa.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.fzhhl.top/Article/details/gtvrlxqqnz.html

[U71] PHP：抛出异常
来源：http://dali.tanke756.top/Article/details/gtggtwmeuf.html

throw new RuntimeException("失败", 500);
来源：http://dali.cheryme.top/Article/details/gtpxmapxwy.html

[U72] PHP：写错误日志
来源：http://dali.ppjwa.cn/Article/details/gtkpbfzpuo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hnxiangtu.top/Article/details/gtgzrztqat.html

[U73] PHP：读取 ini 配置
来源：http://dali.yvedp.cn/Article/details/gtihkdibck.html

parse_ini_file("config.ini", true)
来源：http://dali.cashguo.top/Article/details/gtnqdzbves.html

[U74] PHP：读取环境变量
来源：http://dali.dianchejie.cn/Article/details/gtvpmalohq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.pycfn.com/Article/details/gtgiwkjdtt.html

[U75] PHP：依赖注入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqgsrkyu.html

composer require psr/container
来源：http://dali.zycfv.cn/Article/details/gtcrvcbnsy.html

[U76] PHP：简单路由
来源：http://dali.hongshengwenyu.top/Article/details/gtyezraqvb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.kuanghao11.cn/Article/details/gteokkyalv.html

[U77] PHP：模板渲染
来源：http://dali.yueranfly.top/Article/details/gtibljkblc.html

composer require twig/twig
来源：http://dali.yonumen.top/Article/details/gtdslhvjhq.html

[U78] PHP：单元测试
来源：http://dali.jlsjyb.cn/Article/details/gtmufiuipn.html

composer require --dev phpunit/phpunit
来源：http://dali.yangfankeji.com/Article/details/gtlygenbdv.html

[U79] PHP：静态分析
来源：http://dali.tanke756.top/Article/details/gtwtcmhudr.html

composer require --dev phpstan/phpstan
来源：http://dali.dashuyun.cn/Article/details/gttyxeghix.html

[U80] PHP：代码规范修复
来源：http://dali.sufxvd.cn/Article/details/gtytikslte.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.dianchejie.cn/Article/details/gtirrpneby.html

[U81] JS：初始化项目
来源：http://dali.yj202588.top/Article/details/gtqkgqpius.html

npm init -y;  npm i express
来源：http://dali.cdnleiting.top/Article/details/gtltpwpclx.html

[U82] JS：package.json 脚本
来源：http://dali.c1oappe.top/Article/details/gtrjrtobkp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.havefunace.top/Article/details/gtvriidrzo.html

[U83] JS：ES Module 导入导出
来源：http://dali.xziqi.cn/Article/details/gtuhkshmxu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.vqdsnc.cn/Article/details/gtgxbilbem.html

[U84] JS：CommonJS 写法
来源：http://dali.tanke756.top/Article/details/gtcwmxsygs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinghuilouyu.cn/Article/details/gtakqldoop.html

[U85] JS：可选链
来源：http://dali.dianchejie.cn/Article/details/gtodyupqcd.html

a?.b?.c
来源：http://dali.smart0.xyz/Article/details/gtzeixgruy.html

[U86] JS：空值合并
来源：http://dali.yongpay.top/Article/details/gtwieqtpas.html

a ?? b
来源：http://dali.ydzc1.top/Article/details/gtgcbajleo.html

[U87] JS：解构默认值
来源：http://dali.feifeiyinyue.top/Article/details/gtsknqirye.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sweek.top/Article/details/gthervvdpy.html

[U88] JS：对象展开合并
来源：http://dali.yvedp.cn/Article/details/gttigcijkq.html

{ ...a, ...b }
来源：http://dali.xylfe.cn/Article/details/gtyqdweocs.html

[U89] JS：数组去重
来源：http://dali.haohaochexian.top/Article/details/gtojqhdbzw.html

[...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtttvwikyl.html

[U90] JS：数字数组排序
来源：http://dali.yvedp.cn/Article/details/gtapraijdb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gtnogspeho.html

[U91] JS：对象键值遍历
来源：http://dali.zycfv.cn/Article/details/gtueuzpkgz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.bjfxy.top/Article/details/gtdmeukghy.html

[U92] JS：深拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqzxjnox.html

structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gtpggmaeuh.html


<!-- 参考信息 -->