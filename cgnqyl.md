代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.gogol.net.cn/Article/details/gtmkqegxog.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gotoacloud.top/Article/details/gtrrochthn.html

[T06] Kotlin：集合映射
来源：http://dali.sysykeji.top/Article/details/gtrlsdabbq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtkpdqkcqz.html

[T07] Kotlin：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gtnoahjdwt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gtxkbwoddk.html

[T08] Kotlin：数据类
来源：http://dali.zdqjudy.top/Article/details/gtarazqkjk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnfbohkl.html

[T09] Kotlin：扩展函数
来源：http://dali.hammf.cn/Article/details/gteowdcnus.html

fun String.exclaim() = this + "!"
来源：http://dali.zycfv.cn/Article/details/gtkqnkohar.html

[T10] Kotlin：默认参数
来源：http://dali.yangfankeji.com/Article/details/gtxwwjidkl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xinyue.icu/Article/details/gtnwzmfoka.html

[T11] Kotlin：协程
来源：http://dali.hammf.cn/Article/details/gtbbmgkxsg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nwbrower.top/Article/details/gtvkufvthd.html

[T12] Kotlin：解构声明
来源：http://dali.sufxvd.cn/Article/details/gtodixleyy.html

val (a, b) = Pair(1, 2)
来源：http://dali.bjfxy.top/Article/details/gtsksqwfsu.html

[T13] Kotlin：只读 Map
来源：http://dali.gotoacloud.top/Article/details/gtmlalbfbq.html

val m = mapOf("a" to 1)
来源：http://dali.yongpay.top/Article/details/gtilbevgog.html

[T14] Kotlin：循环
来源：http://dali.ydzc1.top/Article/details/gtyxooiqee.html

for (i in 1..10) println(i)
来源：http://dali.sufxvd.cn/Article/details/gtbnetkczj.html

[T15] Kotlin：接口
来源：http://dali.yanxiufei.cn/Article/details/gtcgnruktz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gtojmxxqwv.html

[T16] Swift：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtwdvygzmq.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtdaxfrcms.html

[T17] Swift：变量与常量
来源：http://dali.smart0.xyz/Article/details/gtbuhkmuem.html

var a = 1;  let b = 2
来源：http://dali.yuxming.cn/Article/details/gtqhcvmnmj.html

[T18] Swift：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtbfjzanaq.html

"值: \(b)"
来源：http://dali.pengpengdd.cyou/Article/details/gttvciehyj.html

[T19] Swift：可选绑定
来源：http://dali.gogol.net.cn/Article/details/gtmhruatdn.html

if let n = opt { print(n) }
来源：http://dali.ydzc1.top/Article/details/gtbbisdnex.html

[T20] Swift：数组操作
来源：http://dali.xinyue.icu/Article/details/gtlgvihuxt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daria6918.cn/Article/details/gtzvludbvs.html

[T21] Swift：遍历
来源：http://dali.nanxinkj.top/Article/details/gtbxhedtlc.html

for x in a { print(x) }
来源：http://dali.9152youxi.cn/Article/details/gtdpepqdlw.html

[T22] Swift：字典
来源：http://dali.hfpthk.cn/Article/details/gttylfwkff.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yanxiufei.cn/Article/details/gtmzqusjej.html

[T23] Swift：函数
来源：http://dali.shzxlz.cn/Article/details/gthyifwcof.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.meibo888.top/Article/details/gtmfanqaru.html

[T24] Swift：闭包
来源：http://dali.nwbrower.top/Article/details/gtpbcdfgkc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.meibo888.top/Article/details/gtmdqrzkus.html

[T25] Swift：结构体
来源：http://dali.c1oappe.top/Article/details/gtbodvwdea.html

struct P { var x: Int }
来源：http://dali.wangdashe.top/Article/details/gtqmnwxqdc.html

[T26] Swift：类与重写
来源：http://dali.iojbl.cn/Article/details/gtzcvvylzx.html

class A: Base { override func f() {} }
来源：http://dali.fzhhl.top/Article/details/gttacskkxj.html

[T27] Swift：错误处理
来源：http://dali.snrcjt.cn/Article/details/gtqztqbkul.html

do { try f() } catch { print(error) }
来源：http://dali.xylfe.cn/Article/details/gtwkpvtbsw.html

[T28] Swift：枚举
来源：http://dali.bjfxy.top/Article/details/gtclucjhme.html

enum Color { case red, green }
来源：http://dali.meibo888.top/Article/details/gttryzhjnf.html

[T29] Swift：guard 提前返回
来源：http://dali.jqgfzy.top/Article/details/gtmkgoclqk.html

guard let x = opt else { return }
来源：http://dali.hysaishi.cn/Article/details/gtwtjqlljm.html

[T30] Swift：协议
来源：http://dali.yj20258.top/Article/details/gtcnusqvse.html

protocol Shape { func area() -> Double }
来源：http://dali.yonumen.top/Article/details/gtgpufzkhc.html

[T31] Lua：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvjrrhtg.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gtvjxyugfw.html

[T32] Lua：局部变量
来源：http://dali.jlsjyb.cn/Article/details/gtbxhzaqke.html

local a = 1
来源：http://dali.ydzc1.top/Article/details/gtiwxluedv.html

[T33] Lua：表（数组）
来源：http://dali.jinqigfzy.top/Article/details/gtgnudgqca.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258.top/Article/details/gtzpyesfip.html

[T34] Lua：遍历表
来源：http://dali.yj20258888.top/Article/details/gtxjjrxvhp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinghuilouyu.cn/Article/details/gtzydvowqb.html

[T35] Lua：字典表
来源：http://dali.dashuyun.cn/Article/details/gtpfydosxp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yvedp.cn/Article/details/gtqdixbsbd.html

[T36] Lua：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlgwrpam.html

function add(a, b) return a + b end
来源：http://dali.yongpay.top/Article/details/gtrkhzkknv.html

[T37] Lua：字符串拼接
来源：http://dali.hywenlv.cn/Article/details/gtiurhdikg.html

"a" .. "b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzjmbyfk.html

[T38] Lua：条件
来源：http://dali.haohaochexian.top/Article/details/gtcbzaxwwl.html

if x > 0 then print("正") end
来源：http://dali.jqgufenzy.top/Article/details/gtlzeezswu.html

[T39] Lua：模式匹配
来源：http://dali.hfpthk.cn/Article/details/gtkewfnwsz.html

string.find(s, "%d+")
来源：http://dali.zdqjudy.top/Article/details/gtwjikjrpf.html

[T40] Lua：元表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrheihnr.html

setmetatable({}, { __index = base })
来源：http://dali.zhoulong.xyz/Article/details/gtfgnifgax.html

[T41] Perl：Hello World
来源：http://dali.cheryme.top/Article/details/gtcxwynzbj.html

print "Hello\n";
来源：http://dali.pengpengdd.cyou/Article/details/gtdrwuidyv.html

[T42] Perl：变量类型
来源：http://dali.zhongyouzk.top/Article/details/gtkwvfxccs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gotoacloud.top/Article/details/gtyawsstrz.html

[T43] Perl：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtfuvhzixo.html

"值: $a"
来源：http://dali.bjfxy.top/Article/details/gthngogfgr.html

[T44] Perl：条件
来源：http://dali.xuetiantiany.cn/Article/details/gtxcajbshq.html

if ($a > 0) { print "正"; }
来源：http://dali.iojbl.cn/Article/details/gtsphfdgiy.html

[T45] Perl：数组遍历
来源：http://dali.hnxiangtu.top/Article/details/gtsyfxitkz.html

for my $x (@arr) { print $x; }
来源：http://dali.zdqjudy.top/Article/details/gthaniazbk.html

[T46] Perl：哈希操作
来源：http://dali.zhongyouzk.top/Article/details/gttxcfzqbl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtszwksheu.html

[T47] Perl：正则捕获
来源：http://dali.shzxlz.cn/Article/details/gtmfbnzjwf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jyoumei.cn/Article/details/gtjsboidms.html

[T48] Perl：正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtjqefrmbx.html

$s =~ s/old/new/g;
来源：http://dali.nanxuanxn.top/Article/details/gtqbglllyq.html

[T49] Perl：函数
来源：http://dali.cqqwz.cn/Article/details/gttcwhseqq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtvfoitqbn.html

[T50] Perl：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtlkbnqeup.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gotoacloud.top/Article/details/gtflkjutwt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tian-w.cn/Article/details/gtbzyjgacx.html

[T51] Scala：Hello World
来源：http://dali.fengsongda.top/Article/details/gtkauhqyty.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gtpfkdxfjy.html

[T52] Scala：变量
来源：http://dali.jyoumei.cn/Article/details/gtevlitawm.html

val a = 1;  var b = 2
来源：http://dali.c1oappe.top/Article/details/gtwydputrw.html

[T53] Scala：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtmxkhfizn.html

s"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtulseaofk.html

[T54] Scala：集合映射
来源：http://dali.yonumen.top/Article/details/gtuqylmqug.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shuidangran.top/Article/details/gtxnmpnniv.html

[T55] Scala：集合过滤
来源：http://dali.yuxming.cn/Article/details/gtkiymczbx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sweek.top/Article/details/gtmbioiwio.html

[T56] Scala：样例类
来源：http://dali.jianghu66.top/Article/details/gtdrggevtw.html

case class User(name: String, age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrncnrbv.html

[T57] Scala：模式匹配
来源：http://dali.zhongyouzk.top/Article/details/gtzaxuaxba.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ppjwa.cn/Article/details/gtyaaaqqsv.html

[T58] Scala：函数定义
来源：http://dali.ppjwa.cn/Article/details/gthvwjgjuk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigufen.top/Article/details/gtdkhsaleo.html

[T59] Scala：循环
来源：http://dali.cdnleiting.top/Article/details/gtraybgecm.html

for (i <- 1 to 10) println(i)
来源：http://dali.cdnleiting.top/Article/details/gtflvofuac.html

[T60] Scala：折叠
来源：http://dali.ehwqpu.com/Article/details/gteyminedr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.daria6918.cn/Article/details/gtqggyozjs.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtpyhyfbwr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnqzz.top/Article/details/gtxwnkchty.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtseqcaypr.html

[U01] Py：创建虚拟环境
来源：http://dali.feifeiyinyue.top/Article/details/gtszdhjnbt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ybcxt.top/Article/details/gtudxrbgkt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.0kj1m.cn/Article/details/gtszxxndxt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shuidangran.top/Article/details/gtamzbltik.html

[U03] Py：加载 .env 配置
来源：http://dali.birdmap.top/Article/details/gttyesbhgn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gotoacloud.top/Article/details/gturfxlfda.html

[U04] Py：变量调试打印
来源：http://dali.nwbrower.top/Article/details/gtyunngwvv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xylfe.cn/Article/details/gtwsglunlw.html

[U05] Py：列表去重且保序
来源：http://dali.gaohongyu789.top/Article/details/gtkjiibdmw.html

list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtgaqslkra.html

[U06] Py：合并两个字典
来源：http://dali.zhongyouzk.top/Article/details/gtfsyvtceb.html

{**a, **b}
来源：http://dali.ehwqpu.com/Article/details/gtkphlxykc.html

[U07] Py：反转字典键值
来源：http://dali.yongpay.top/Article/details/gtecmvzlee.html

{v: k for k, v in d.items()}
来源：http://dali.dashuyun.cn/Article/details/gtssasdcmc.html

[U08] Py：展平二维列表
来源：http://dali.smart0.xyz/Article/details/gtuebncaht.html

[y for x in nested for y in x]
来源：http://dali.jinqigfzy.top/Article/details/gtrrhitagq.html

[U09] Py：字典取最大值的键
来源：http://dali.dianchejie.cn/Article/details/gtfqmxlvhp.html

max(d, key=d.get)
来源：http://dali.shangyingyoupin.top/Article/details/gtefjmwkwy.html

[U10] Py：按值排序字典
来源：http://dali.sufxvd.cn/Article/details/gtdyctnpdg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gaohongyu789.top/Article/details/gtkkqprbri.html

[U11] Py：生成器表达式
来源：http://dali.c1oappe.top/Article/details/gtvmvsgild.html

(x * 2 for x in arr)
来源：http://dali.yonumen.top/Article/details/gtovlhpedw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.chenjidiqi.icu/Article/details/gtssbxhzgm.html

Counter(arr).most_common(3)
来源：http://dali.jlsjyb.cn/Article/details/gtaxgdrhjb.html

[U13] Py：固定长度队列
来源：http://dali.wangdashe.top/Article/details/gteyvtpaof.html

deque(maxlen=10)
来源：http://dali.sxryk.cn/Article/details/gtfsgqnayg.html

[U14] Py：分组收集到列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxeiglxsn.html

defaultdict(list)
来源：http://dali.snrcjt.cn/Article/details/gtcpgllyrk.html

[U15] Py：高精度计时
来源：http://dali.birdmap.top/Article/details/gtywsgxbkj.html

t = time.perf_counter()
来源：http://dali.nanxuanxn.top/Article/details/gtpkdpvtwx.html

[U16] Py：命令行参数解析
来源：http://dali.redwolf501.top/Article/details/gtxgwdbjjl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cqqwz.cn/Article/details/gtabmhxyoe.html

[U17] Py：初始化日志
来源：http://dali.zhongyouzk.top/Article/details/gtwgnvdjpd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hammf.cn/Article/details/gtxtzywurn.html

[U18] Py：预编译正则
来源：http://dali.aibaodan.cn/Article/details/gtbvnhqbxy.html

pat = re.compile(r"\d+")
来源：http://dali.dianchejie.cn/Article/details/gtxcegmrad.html

[U19] Py：正则替换带回调
来源：http://dali.vqdsnc.cn/Article/details/gthtdlmcci.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigfzy.top/Article/details/gtcfdswtpf.html

[U20] Py：缓存函数结果
来源：http://dali.gzhubu.top/Article/details/gtdlnilsue.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbwuzskx.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhengqikj.top/Article/details/gtjctcxclu.html

@contextlib.contextmanager
来源：http://dali.yj202588.top/Article/details/gtjrhnwinc.html

[U22] Py：矩阵转置
来源：http://dali.fengsongda.top/Article/details/gtmjdaxsfw.html

list(zip(*m))
来源：http://dali.shuidangran.top/Article/details/gtfvjpnema.html

[U23] Py：分块读取大文件
来源：http://dali.zhengqikj.top/Article/details/gtqfkpwpyo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.vqdsnc.cn/Article/details/gtgwfkgalv.html

[U24] Py：路径操作
来源：http://dali.yuxming.cn/Article/details/gtxinrrgjg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gtgrlrwwit.html

[U25] Py：CSV 按字典读
来源：http://dali.nwbrower.top/Article/details/gtmyjocvzb.html

csv.DictReader(f)
来源：http://dali.aibaodan.cn/Article/details/gtvihedexr.html

[U26] Py：并发下载
来源：http://dali.jinqigfzy.top/Article/details/gtupkitird.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cucudq.cn/Article/details/gtixnivlxj.html

[U27] Py：异步 HTTP
来源：http://dali.dianchejie.cn/Article/details/gtwrdewhql.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hywenlv.cn/Article/details/gtjaqmshqx.html

[U28] Py：类型别名
来源：http://dali.yangfankeji.com/Article/details/gtcogskvyq.html

UserId = int
来源：http://dali.yonumen.top/Article/details/gtskzapgky.html

[U29] Py：属性校验
来源：http://dali.redwolf501.top/Article/details/gtrhhamqie.html

@property 与 @x.setter 配合
来源：http://dali.9152youxi.cn/Article/details/gtmabysxcw.html

[U30] Py：数据类
来源：http://dali.xinyue.icu/Article/details/gtzaoaersp.html

@dataclass(slots=True)
来源：http://dali.jianghu66.top/Article/details/gtrsyqrtbn.html

[U31] Py：单测
来源：http://dali.sxryk.cn/Article/details/gtlruauccr.html

python -m pytest -q
来源：http://dali.gotoacloud.top/Article/details/gttgaijzfi.html

[U32] Py：代码格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtiqafgafy.html

ruff format . && ruff check --fix .
来源：http://dali.xinyue.icu/Article/details/gtqvlvntbv.html

[U33] Py：打包发布
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdsrvjcc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.c1oappe.top/Article/details/gtzzpqvwax.html

[U34] Py：判断编码
来源：http://dali.gaohongyu789.top/Article/details/gtruoxyshm.html

chardet.detect(raw)
来源：http://dali.hywenlv.cn/Article/details/gtxoijrysh.html

[U35] Py：发送邮件
来源：http://dali.sufxvd.cn/Article/details/gtmvbedspc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gaohongyu789.top/Article/details/gtuxhlqrbv.html

[U36] Py：定时任务
来源：http://dali.yj202588.top/Article/details/gtqrvuazfr.html

schedule.every(10).minutes.do(job)
来源：http://dali.ybcxt.top/Article/details/gtvqhknzjf.html

[U37] Py：读写 Excel
来源：http://dali.0kj1m.cn/Article/details/gtwzwzxnva.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yueranfly.top/Article/details/gteodfifik.html

[U38] Py：获取脚本所在目录
来源：http://dali.hongshengwenyu.top/Article/details/gtjellbwug.html

Path(__file__).resolve().parent
来源：http://dali.wangshuangyany.cn/Article/details/gtldwcsxfy.html

[U39] Py：判断是否在交互环境
来源：http://dali.hysaishi.cn/Article/details/gtjhwkjtau.html

sys.stdout.isatty()
来源：http://dali.yanxiufei.cn/Article/details/gtsvmtrwmc.html

[U40] Py：打印到标准错误
来源：http://dali.nwbrower.top/Article/details/gtdaajucwr.html

print("err", file=sys.stderr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzviiamx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sysykeji.top/Article/details/gtnxhcxjgs.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hongshengwenyu.top/Article/details/gttnmigpvj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cdnleiting.top/Article/details/gtvahqaypa.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yangfankeji.com/Article/details/gtdtaojcck.html

[U43] PHP：声明命名空间
来源：http://dali.ehwqpu.com/Article/details/gtqghglcuv.html

namespace App\Http;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoohlphxn.html

[U44] PHP：开启严格类型
来源：http://dali.xuanzx.com/Article/details/gtjwzptbho.html

declare(strict_types=1);
来源：http://dali.jinqigufen.top/Article/details/gttlpusksz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinqigufen.top/Article/details/gtiizgkwmv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmpyyjni.html

[U46] PHP：可空类型
来源：http://dali.zhongyouzk.top/Article/details/gtirnsilrn.html

?string $name = null
来源：http://dali.chenzaomai.com/Article/details/gtmshnkprk.html

[U47] PHP：联合类型
来源：http://dali.zhongyouzk.top/Article/details/gtkztjnfua.html

int|string $id
来源：http://dali.ivvv.top/Article/details/gtdptgapyy.html

[U48] PHP：纯枚举
来源：http://dali.daxiang520.top/Article/details/gtgeyzgjgh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhengqikj.top/Article/details/gtcvqilnnv.html

[U49] PHP：只读属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcnzqmhm.html

public readonly string $name
来源：http://dali.jianghu66.top/Article/details/gtndzjihrx.html

[U50] PHP：构造器属性提升
来源：http://dali.yj202588.top/Article/details/gtmlzpwogp.html

public function __construct(private int $id) {}
来源：http://dali.sufxvd.cn/Article/details/gtdihmlmlk.html

[U51] PHP：数组解构
来源：http://dali.guannengcc.top/Article/details/gtrrnqmkue.html

[$a, $b] = $arr;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxymclpf.html

[U52] PHP：箭头函数
来源：http://dali.0kj1m.cn/Article/details/gtgzcpizog.html

$double = fn($x) => $x * 2;
来源：http://dali.hongshengwenyu.top/Article/details/gtmyufusxd.html

[U53] PHP：空合并运算符
来源：http://dali.wangdashe.top/Article/details/gtzheywghx.html

$v = $a ?? $b ?? "default";
来源：http://dali.xziqi.cn/Article/details/gtnhugorgi.html

[U54] PHP：空安全调用
来源：http://dali.aibaodan.cn/Article/details/gtuppjszsi.html

$obj?->method()
来源：http://dali.gotoacloud.top/Article/details/gtwljnzksv.html

[U55] PHP：match 表达式
来源：http://dali.guowangkeji.top/Article/details/gtgcvvhqpu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.tianlin.xyz/Article/details/gtmylgmlhb.html

[U56] PHP：命名参数
来源：http://dali.xuanzx.com/Article/details/gtjnbsizav.html

f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtuverohfy.html

[U57] PHP：字符串插值
来源：http://dali.yongpay.top/Article/details/gtkanjriiv.html

"值: {$a}"
来源：http://dali.haohaochexian.top/Article/details/gtqgboyimb.html

[U58] PHP：数组三件套
来源：http://dali.mhx1999.top/Article/details/gtqjmmrhcb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yj202588.top/Article/details/gtlxklizwj.html

[U59] PHP：自定义排序
来源：http://dali.gotoacloud.top/Article/details/gtuaxskmme.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gtcaipvkyu.html

[U60] PHP：JSON 编解码
来源：http://dali.daria6918.cn/Article/details/gtpcwqzntj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.guannengcc.top/Article/details/gtvkyrlviw.html

[U61] PHP：正则
来源：http://dali.ybcxt.top/Article/details/gtsozrydbc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gtuzlxzqrc.html

[U62] PHP：日期对象
来源：http://dali.wangdashe.top/Article/details/gteakppjps.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zdqjudy.top/Article/details/gtvkgmwcln.html

[U63] PHP：文件读写
来源：http://dali.hnxiangtu.top/Article/details/gtptsleaka.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jqgufenzy.top/Article/details/gtppilzpmj.html

[U64] PHP：目录遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtwliaxtfm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ppjwa.cn/Article/details/gtoyefosep.html

[U65] PHP：会话
来源：http://dali.daria6918.cn/Article/details/gtnggqupkj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtsadsmksr.html

[U66] PHP：设置 Cookie
来源：http://dali.yonumen.top/Article/details/gtlckzcrxr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.svipenyu.cn/Article/details/gtfcebmfsm.html

[U67] PHP：处理文件上传
来源：http://dali.shuidangran.top/Article/details/gtupvugqjh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.vqdsnc.cn/Article/details/gtbfmspmqx.html

[U68] PHP：PDO 连接
来源：http://dali.zycfv.cn/Article/details/gtqebgqeox.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.pengpengdd.cyou/Article/details/gtsjczbbko.html

[U69] PHP：PDO 预处理
来源：http://dali.yvedp.cn/Article/details/gtmbfbbbhn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcaxksiyv.html

[U70] PHP：PDO 事务
来源：http://dali.yj202588.top/Article/details/gtzkldgbqo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tianlin.xyz/Article/details/gtxphxncla.html

[U71] PHP：抛出异常
来源：http://dali.guannengcc.top/Article/details/gttklqgnlj.html

throw new RuntimeException("失败", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gtiywpzxrn.html

[U72] PHP：写错误日志
来源：http://dali.yj202588.top/Article/details/gtwbioilsr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hysaishi.cn/Article/details/gtblmswttj.html

[U73] PHP：读取 ini 配置
来源：http://dali.xinyue.icu/Article/details/gtcrftaurd.html

parse_ini_file("config.ini", true)
来源：http://dali.pycfn.com/Article/details/gtgqgaombt.html

[U74] PHP：读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gttrzatygj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gaohongyu789.top/Article/details/gtpjxpisqa.html

[U75] PHP：依赖注入
来源：http://dali.0kj1m.cn/Article/details/gtpqvolffe.html

composer require psr/container
来源：http://dali.guowangkeji.top/Article/details/gtjodeywdv.html

[U76] PHP：简单路由
来源：http://dali.guowangkeji.top/Article/details/gthnszlazt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.nanxinkj.top/Article/details/gttclceaqh.html

[U77] PHP：模板渲染
来源：http://dali.shzxlz.cn/Article/details/gtrywoyokr.html

composer require twig/twig
来源：http://dali.nanxuanxn.top/Article/details/gthhpcruwz.html

[U78] PHP：单元测试
来源：http://dali.hongshengwenyu.top/Article/details/gtejxgjvmr.html

composer require --dev phpunit/phpunit
来源：http://dali.9152youxi.cn/Article/details/gtfullowoh.html

[U79] PHP：静态分析
来源：http://dali.yongpay.top/Article/details/gtrayxkzdd.html

composer require --dev phpstan/phpstan
来源：http://dali.snrcjt.cn/Article/details/gtkbrpugec.html

[U80] PHP：代码规范修复
来源：http://dali.chenjidiqi.icu/Article/details/gtjpijzrnc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hysaishi.cn/Article/details/gtjjmpgqad.html

[U81] JS：初始化项目
来源：http://dali.shzxlz.cn/Article/details/gtdxsvmima.html

npm init -y;  npm i express
来源：http://dali.yueranfly.top/Article/details/gtixdrujun.html

[U82] JS：package.json 脚本
来源：http://dali.fengsongda.top/Article/details/gtcuryzmfg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hywenlv.cn/Article/details/gtcxryzniy.html

[U83] JS：ES Module 导入导出
来源：http://dali.hnxiangtu.top/Article/details/gtapnmlhtj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cheryme.top/Article/details/gtzsatumte.html

[U84] JS：CommonJS 写法
来源：http://dali.xuetiantiany.cn/Article/details/gtuhuurozx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.gogol.net.cn/Article/details/gtqogbaakf.html

[U85] JS：可选链
来源：http://dali.andypj.xyz/Article/details/gtdtyzjqwv.html

a?.b?.c
来源：http://dali.gaohongyu789.top/Article/details/gtbkpwnyrf.html

[U86] JS：空值合并
来源：http://dali.smart0.xyz/Article/details/gtxquntpiq.html

a ?? b
来源：http://dali.pycfn.com/Article/details/gthgcaqfph.html

[U87] JS：解构默认值
来源：http://dali.jinqigfzy.top/Article/details/gtdmeovkbl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhaomingkeji.xyz/Article/details/gteuvrahmm.html

[U88] JS：对象展开合并
来源：http://dali.sysykeji.top/Article/details/gtfgzqnojs.html

{ ...a, ...b }
来源：http://dali.gotoacloud.top/Article/details/gtgxoavlnr.html

[U89] JS：数组去重
来源：http://dali.tian-w.cn/Article/details/gtjiwfiqnv.html

[...new Set(arr)]
来源：http://dali.daria6918.cn/Article/details/gtyrioefxh.html

[U90] JS：数字数组排序
来源：http://dali.yongpay.top/Article/details/gtewjxipii.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtwokkucea.html

[U91] JS：对象键值遍历
来源：http://dali.shzxlz.cn/Article/details/gtewnxonli.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jianghu66.top/Article/details/gtlfupvrvt.html

[U92] JS：深拷贝
来源：http://dali.wangdashe.top/Article/details/gteuutsqgs.html

structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtovxttxtf.html


<!-- 参考信息 -->