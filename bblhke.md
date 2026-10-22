代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.sufxvd.cn/Article/details/gtkyurvahw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigufen.top/Article/details/gtftzhnxow.html

[T06] Kotlin：集合映射
来源：http://dali.meibo888.top/Article/details/gtimmekscv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtzjnkhwvl.html

[T07] Kotlin：集合过滤
来源：http://dali.nwbrower.top/Article/details/gtbvwdqfsa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gtqjadsytq.html

[T08] Kotlin：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gtzzwypobc.html

data class User(val name: String, val age: Int)
来源：http://dali.daria6918.cn/Article/details/gtbdzfstgv.html

[T09] Kotlin：扩展函数
来源：http://dali.ehwqpu.com/Article/details/gtxeppudrw.html

fun String.exclaim() = this + "!"
来源：http://dali.chenzaomai.com/Article/details/gtkhvedkok.html

[T10] Kotlin：默认参数
来源：http://dali.hywenlv.cn/Article/details/gtjrvqwpty.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nwbrower.top/Article/details/gtjfcoxxwb.html

[T11] Kotlin：协程
来源：http://dali.aizwys.cn/Article/details/gtzeembunj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenjidiqi.icu/Article/details/gtykcpqeis.html

[T12] Kotlin：解构声明
来源：http://dali.shzxlz.cn/Article/details/gthobnpguz.html

val (a, b) = Pair(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtxkvggkkk.html

[T13] Kotlin：只读 Map
来源：http://dali.kuanghao11.cn/Article/details/gtqperedxq.html

val m = mapOf("a" to 1)
来源：http://dali.quarkkingdee.top/Article/details/gtxgoysvyy.html

[T14] Kotlin：循环
来源：http://dali.ehwqpu.com/Article/details/gtlpyinivd.html

for (i in 1..10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gtpiigzrwm.html

[T15] Kotlin：接口
来源：http://dali.gotoacloud.top/Article/details/gttchxgaod.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gtygyyriaj.html

[T16] Swift：Hello World
来源：http://dali.wangdashe.top/Article/details/gtpbgqizej.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gtcnvobpsz.html

[T17] Swift：变量与常量
来源：http://dali.yj20258888.top/Article/details/gtddbvebic.html

var a = 1;  let b = 2
来源：http://dali.xuanzx.com/Article/details/gtfirljyef.html

[T18] Swift：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtkfyasncw.html

"值: \(b)"
来源：http://dali.svipenyu.cn/Article/details/gtkfgztpdl.html

[T19] Swift：可选绑定
来源：http://dali.haohaochexian.top/Article/details/gtpfyfgvze.html

if let n = opt { print(n) }
来源：http://dali.hywenlv.cn/Article/details/gtmnebxctc.html

[T20] Swift：数组操作
来源：http://dali.cashguo.top/Article/details/gtnozozayo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.redwolf501.top/Article/details/gtfykkbyxz.html

[T21] Swift：遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwsuuiut.html

for x in a { print(x) }
来源：http://dali.guowangkeji.top/Article/details/gthzrbckrq.html

[T22] Swift：字典
来源：http://dali.xuanzx.com/Article/details/gtbwpgcfsl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jyoumei.cn/Article/details/gttxetrtre.html

[T23] Swift：函数
来源：http://dali.gotoacloud.top/Article/details/gtdqpaurrz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtigylnmvf.html

[T24] Swift：闭包
来源：http://dali.gotoacloud.top/Article/details/gtmyhcackr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtgsxisevk.html

[T25] Swift：结构体
来源：http://dali.yuxming.cn/Article/details/gtnfyxmvht.html

struct P { var x: Int }
来源：http://dali.zycfv.cn/Article/details/gtbecungvj.html

[T26] Swift：类与重写
来源：http://dali.ehwqpu.com/Article/details/gtrajwsree.html

class A: Base { override func f() {} }
来源：http://dali.redwolf501.top/Article/details/gtjxqskyly.html

[T27] Swift：错误处理
来源：http://dali.yueranfly.top/Article/details/gtigqddriu.html

do { try f() } catch { print(error) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfglcepni.html

[T28] Swift：枚举
来源：http://dali.bjfxy.top/Article/details/gtajfcjwri.html

enum Color { case red, green }
来源：http://dali.hysaishi.cn/Article/details/gtkgbgfgud.html

[T29] Swift：guard 提前返回
来源：http://dali.yuanzhike.top/Article/details/gtztjdklan.html

guard let x = opt else { return }
来源：http://dali.nanxuanxn.top/Article/details/gtxyzpdfzh.html

[T30] Swift：协议
来源：http://dali.daria6918.cn/Article/details/gteuxarkvq.html

protocol Shape { func area() -> Double }
来源：http://dali.shangyingyoupin.top/Article/details/gtnzywaegr.html

[T31] Lua：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtyjuqbhsp.html

print("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtyiwpzyaq.html

[T32] Lua：局部变量
来源：http://dali.gaohongyu789.top/Article/details/gtwgdrbrrw.html

local a = 1
来源：http://dali.jqgufenzy.top/Article/details/gtregoyphc.html

[T33] Lua：表（数组）
来源：http://dali.fzhhl.top/Article/details/gthekcewpp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gtvvkxohdw.html

[T34] Lua：遍历表
来源：http://dali.fengsongda.top/Article/details/gtvcdvdinx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinqigfzy.top/Article/details/gtkspkipgi.html

[T35] Lua：字典表
来源：http://dali.fzhhl.top/Article/details/gtfqjxirls.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jlsjyb.cn/Article/details/gtyhcegwln.html

[T36] Lua：函数
来源：http://dali.yongpay.top/Article/details/gtkaidzrhu.html

function add(a, b) return a + b end
来源：http://dali.0kj1m.cn/Article/details/gtnjxmbizf.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gtbsudozia.html

"a" .. "b"
来源：http://dali.jianghu66.top/Article/details/gtrfthlxoo.html

[T38] Lua：条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjoplxpy.html

if x > 0 then print("正") end
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfkqlrtm.html

[T39] Lua：模式匹配
来源：http://dali.yonumen.top/Article/details/gtcstvsskn.html

string.find(s, "%d+")
来源：http://dali.hongshengwenyu.top/Article/details/gtdngeyemm.html

[T40] Lua：元表
来源：http://dali.hywenlv.cn/Article/details/gtoihgfprh.html

setmetatable({}, { __index = base })
来源：http://dali.hammf.cn/Article/details/gtyulerhxd.html

[T41] Perl：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtesxnxobl.html

print "Hello\n";
来源：http://dali.snrcjt.cn/Article/details/gtnbojqijm.html

[T42] Perl：变量类型
来源：http://dali.fzhhl.top/Article/details/gtlhjryunp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jlsjyb.cn/Article/details/gtkvlvzkpw.html

[T43] Perl：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtjycsaoum.html

"值: $a"
来源：http://dali.sysykeji.top/Article/details/gtnbbcjyfa.html

[T44] Perl：条件
来源：http://dali.yonumen.top/Article/details/gtpiznxcol.html

if ($a > 0) { print "正"; }
来源：http://dali.hnxiangtu.top/Article/details/gtfvyjgsbu.html

[T45] Perl：数组遍历
来源：http://dali.meibo888.top/Article/details/gtzmjofoun.html

for my $x (@arr) { print $x; }
来源：http://dali.ehwqpu.com/Article/details/gtnlbuqmfl.html

[T46] Perl：哈希操作
来源：http://dali.guannengcc.top/Article/details/gtaydlbqvq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tianlin.xyz/Article/details/gteqzaaeuf.html

[T47] Perl：正则捕获
来源：http://dali.gaohongyu789.top/Article/details/gtfasmueqo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jyoumei.cn/Article/details/gtftdhzdgm.html

[T48] Perl：正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtxvihzddb.html

$s =~ s/old/new/g;
来源：http://dali.jinqigfzy.top/Article/details/gtkhpfyivr.html

[T49] Perl：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtubwhpyhw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gtrfhdgsdx.html

[T50] Perl：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtjhmzgaxz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.fengsongda.top/Article/details/gtzjdcxbre.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fzhhl.top/Article/details/gtgqvvsfvi.html

[T51] Scala：Hello World
来源：http://dali.bjfxy.top/Article/details/gtnsvqhhww.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtovhkiayb.html

[T52] Scala：变量
来源：http://dali.chenjidiqi.icu/Article/details/gtdqizrnso.html

val a = 1;  var b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtzfhzdsjz.html

[T53] Scala：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtpcfoxpfn.html

s"值: $b"
来源：http://dali.dianchejie.cn/Article/details/gtzdljtalb.html

[T54] Scala：集合映射
来源：http://dali.smart0.xyz/Article/details/gtcocdbswa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jianghu66.top/Article/details/gtvkdvztic.html

[T55] Scala：集合过滤
来源：http://dali.daria6918.cn/Article/details/gtqxwznoxz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtdvqayskt.html

[T56] Scala：样例类
来源：http://dali.dianchejie.cn/Article/details/gtmqtwqvuu.html

case class User(name: String, age: Int)
来源：http://dali.yj20258.top/Article/details/gtrqovkntb.html

[T57] Scala：模式匹配
来源：http://dali.hammf.cn/Article/details/gtbvdxeclr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.andypj.xyz/Article/details/gtmhfzujhg.html

[T58] Scala：函数定义
来源：http://dali.feifeiyinyue.top/Article/details/gtweyjsujr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nanxuanxn.top/Article/details/gtdjzsqfnh.html

[T59] Scala：循环
来源：http://dali.jianghu66.top/Article/details/gtkzampugi.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj20258888.top/Article/details/gtvloscihp.html

[T60] Scala：折叠
来源：http://dali.ehwqpu.com/Article/details/gtyqaioooz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.fengsongda.top/Article/details/gtxdasejok.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtzttoiyhg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shuidangran.top/Article/details/gtmxlygiew.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtorurtrdj.html

[U01] Py：创建虚拟环境
来源：http://dali.tanke756.top/Article/details/gtexswxhds.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.316326.xyz/Article/details/gtjkweldms.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cqqwz.cn/Article/details/gtcdbnnysx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yangfankeji.com/Article/details/gtgbitwedi.html

[U03] Py：加载 .env 配置
来源：http://dali.zycfv.cn/Article/details/gtggyzketp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.svipenyu.cn/Article/details/gtwmkxmjue.html

[U04] Py：变量调试打印
来源：http://dali.ehwqpu.com/Article/details/gtldrbjver.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yongpay.top/Article/details/gttcmyyxve.html

[U05] Py：列表去重且保序
来源：http://dali.aizwys.cn/Article/details/gtnmfewrss.html

list(dict.fromkeys(arr))
来源：http://dali.kuanghao11.cn/Article/details/gtqzpkmvlk.html

[U06] Py：合并两个字典
来源：http://dali.ppjwa.cn/Article/details/gtqteogwys.html

{**a, **b}
来源：http://dali.ybcxt.top/Article/details/gtilyngics.html

[U07] Py：反转字典键值
来源：http://dali.9152youxi.cn/Article/details/gtrwibgksk.html

{v: k for k, v in d.items()}
来源：http://dali.hammf.cn/Article/details/gtoroyhdmi.html

[U08] Py：展平二维列表
来源：http://dali.zhoulong.xyz/Article/details/gtfknzxvjr.html

[y for x in nested for y in x]
来源：http://dali.yvedp.cn/Article/details/gtyzsdvvdl.html

[U09] Py：字典取最大值的键
来源：http://dali.aibaodan.cn/Article/details/gtfxtncbde.html

max(d, key=d.get)
来源：http://dali.kuanghao11.cn/Article/details/gthzxoysgo.html

[U10] Py：按值排序字典
来源：http://dali.jqgfzy.top/Article/details/gtnqmpkllz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ivvv.top/Article/details/gtofwfdikm.html

[U11] Py：生成器表达式
来源：http://dali.quarkkingdee.top/Article/details/gtweobjkvo.html

(x * 2 for x in arr)
来源：http://dali.hywenlv.cn/Article/details/gtgfnpkflm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnqzz.top/Article/details/gtzhyycoex.html

Counter(arr).most_common(3)
来源：http://dali.jianghu66.top/Article/details/gtqajwvzrj.html

[U13] Py：固定长度队列
来源：http://dali.yonumen.top/Article/details/gtgcurethc.html

deque(maxlen=10)
来源：http://dali.gzhubu.top/Article/details/gtgqteognb.html

[U14] Py：分组收集到列表
来源：http://dali.haohaochexian.top/Article/details/gtydjzwvrt.html

defaultdict(list)
来源：http://dali.dianchejie.cn/Article/details/gtpdfaczpm.html

[U15] Py：高精度计时
来源：http://dali.jinqigfzy.top/Article/details/gtinwuvryv.html

t = time.perf_counter()
来源：http://dali.shangyingyoupin.top/Article/details/gtpcmmcvbn.html

[U16] Py：命令行参数解析
来源：http://dali.zycfv.cn/Article/details/gtvzyjrdxc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sysykeji.top/Article/details/gtlsvcqdwm.html

[U17] Py：初始化日志
来源：http://dali.hywenlv.cn/Article/details/gtgvjhubcc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcpdqiqn.html

[U18] Py：预编译正则
来源：http://dali.ppjwa.cn/Article/details/gtovwqzcmp.html

pat = re.compile(r"\d+")
来源：http://dali.wangdashe.top/Article/details/gtruapgnze.html

[U19] Py：正则替换带回调
来源：http://dali.chenjidiqi.icu/Article/details/gtiilxnqfl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenlongwang.top/Article/details/gtvlgezkcl.html

[U20] Py：缓存函数结果
来源：http://dali.iojbl.cn/Article/details/gthzyhilil.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sxryk.cn/Article/details/gtkohkipme.html

[U21] Py：自定义上下文管理器
来源：http://dali.tianlin.xyz/Article/details/gtqapdovpo.html

@contextlib.contextmanager
来源：http://dali.shanyushiyangkeji.top/Article/details/gteemmiojb.html

[U22] Py：矩阵转置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmhhpsxq.html

list(zip(*m))
来源：http://dali.wangdashe.top/Article/details/gtnqkpwnxt.html

[U23] Py：分块读取大文件
来源：http://dali.yanxiufei.cn/Article/details/gtgssdqany.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xylfe.cn/Article/details/gtpljibsup.html

[U24] Py：路径操作
来源：http://dali.sxryk.cn/Article/details/gtfllgxjcf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtycdzayhb.html

[U25] Py：CSV 按字典读
来源：http://dali.hfpthk.cn/Article/details/gtxgsgwwkm.html

csv.DictReader(f)
来源：http://dali.sxryk.cn/Article/details/gtvhszkami.html

[U26] Py：并发下载
来源：http://dali.zhoulong.xyz/Article/details/gtyxcbgwzw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sweek.top/Article/details/gtzjnotwwm.html

[U27] Py：异步 HTTP
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulflkqun.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.snrcjt.cn/Article/details/gthqiqhpie.html

[U28] Py：类型别名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwycsuvg.html

UserId = int
来源：http://dali.feifeiyinyue.top/Article/details/gthgogbazw.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gtdqsadipm.html

@property 与 @x.setter 配合
来源：http://dali.shangyingyoupin.top/Article/details/gtlrrfwixx.html

[U30] Py：数据类
来源：http://dali.mhx1999.top/Article/details/gtlyhjvoyc.html

@dataclass(slots=True)
来源：http://dali.yuxming.cn/Article/details/gtqqkwfxhy.html

[U31] Py：单测
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqdjxcmw.html

python -m pytest -q
来源：http://dali.gotoacloud.top/Article/details/gtpjtwflln.html

[U32] Py：代码格式化
来源：http://dali.kuanghao11.cn/Article/details/gtrtztiwnc.html

ruff format . && ruff check --fix .
来源：http://dali.meibo888.top/Article/details/gtoqpavjll.html

[U33] Py：打包发布
来源：http://dali.zhengqikj.top/Article/details/gtbhesjydx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jlsjyb.cn/Article/details/gttrdpvhbp.html

[U34] Py：判断编码
来源：http://dali.hnxiangtu.top/Article/details/gtirlspzfe.html

chardet.detect(raw)
来源：http://dali.feifeiyinyue.top/Article/details/gtpeikkuht.html

[U35] Py：发送邮件
来源：http://dali.9152youxi.cn/Article/details/gtclcuejga.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.guannengcc.top/Article/details/gtfrkolvqb.html

[U36] Py：定时任务
来源：http://dali.chenjidiqi.icu/Article/details/gtahgzdxzd.html

schedule.every(10).minutes.do(job)
来源：http://dali.gzhubu.top/Article/details/gtvhnxrxcm.html

[U37] Py：读写 Excel
来源：http://dali.hfpthk.cn/Article/details/gtttxcphiq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzmmbwzg.html

[U38] Py：获取脚本所在目录
来源：http://dali.fengsongda.top/Article/details/gtgaweksug.html

Path(__file__).resolve().parent
来源：http://dali.xziqi.cn/Article/details/gtevnkmuek.html

[U39] Py：判断是否在交互环境
来源：http://dali.jlsjyb.cn/Article/details/gtyvppoiec.html

sys.stdout.isatty()
来源：http://dali.ydzc1.top/Article/details/gtdlinxydk.html

[U40] Py：打印到标准错误
来源：http://dali.yvedp.cn/Article/details/gtlkewoojb.html

print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gtoaglpcpw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.guannengcc.top/Article/details/gtwkavfbeu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhixingplan.top/Article/details/gtlqcwfcwg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.316326.xyz/Article/details/gtucsdpwre.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.snrcjt.cn/Article/details/gtdzlezlhh.html

[U43] PHP：声明命名空间
来源：http://dali.vqdsnc.cn/Article/details/gtyavyznjq.html

namespace App\Http;
来源：http://dali.cucudq.cn/Article/details/gteheyiygp.html

[U44] PHP：开启严格类型
来源：http://dali.yvedp.cn/Article/details/gtykthetge.html

declare(strict_types=1);
来源：http://dali.sweek.top/Article/details/gtxrpyzlxz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhixingplan.top/Article/details/gtfazpmmqo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtfxhyipvt.html

[U46] PHP：可空类型
来源：http://dali.mhx1999.top/Article/details/gtfmxkpzub.html

?string $name = null
来源：http://dali.zhongyouzk.top/Article/details/gtdisyvqmm.html

[U47] PHP：联合类型
来源：http://dali.gogol.net.cn/Article/details/gteejequio.html

int|string $id
来源：http://dali.guannengcc.top/Article/details/gtsyejlxnr.html

[U48] PHP：纯枚举
来源：http://dali.svipenyu.cn/Article/details/gtnscffkfm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yueranfly.top/Article/details/gtvckakryj.html

[U49] PHP：只读属性
来源：http://dali.gzhubu.top/Article/details/gtqpbukvop.html

public readonly string $name
来源：http://dali.wangdashe.top/Article/details/gtzrxmpsdj.html

[U50] PHP：构造器属性提升
来源：http://dali.yvedp.cn/Article/details/gttoxblqzh.html

public function __construct(private int $id) {}
来源：http://dali.daria6918.cn/Article/details/gtxdlgalkg.html

[U51] PHP：数组解构
来源：http://dali.birdmap.top/Article/details/gtujedvwzz.html

[$a, $b] = $arr;
来源：http://dali.xuetiantiany.cn/Article/details/gtkdnawdvg.html

[U52] PHP：箭头函数
来源：http://dali.nanxuanxn.top/Article/details/gtqiwnkidl.html

$double = fn($x) => $x * 2;
来源：http://dali.yuanzhike.top/Article/details/gtlbrytehq.html

[U53] PHP：空合并运算符
来源：http://dali.shuidangran.top/Article/details/gttropoosg.html

$v = $a ?? $b ?? "default";
来源：http://dali.daxiang520.top/Article/details/gtvluuwqmz.html

[U54] PHP：空安全调用
来源：http://dali.andypj.xyz/Article/details/gtbclysxal.html

$obj?->method()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkxmxbre.html

[U55] PHP：match 表达式
来源：http://dali.yj20258888.top/Article/details/gtvonehjsx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.mhx1999.top/Article/details/gttmzssgns.html

[U56] PHP：命名参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwiszxpu.html

f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gthwlmilks.html

[U57] PHP：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtwngseazv.html

"值: {$a}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwutqrkk.html

[U58] PHP：数组三件套
来源：http://dali.zhengqikj.top/Article/details/gtxbrxjjnn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdpeytgd.html

[U59] PHP：自定义排序
来源：http://dali.daxiang520.top/Article/details/gtvtxllfpi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shzxlz.cn/Article/details/gtmznuosge.html

[U60] PHP：JSON 编解码
来源：http://dali.yanxiufei.cn/Article/details/gtrpgsjnir.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gogol.net.cn/Article/details/gthuwtkfyt.html

[U61] PHP：正则
来源：http://dali.jqgfzy.top/Article/details/gthxoidexn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.tianlin.xyz/Article/details/gtuqveypvt.html

[U62] PHP：日期对象
来源：http://dali.hnxiangtu.top/Article/details/gtrxulghmg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ivvv.top/Article/details/gtlwozvwkd.html

[U63] PHP：文件读写
来源：http://dali.pycfn.com/Article/details/gtukthxdmj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.tian-w.cn/Article/details/gtmvmidejp.html

[U64] PHP：目录遍历
来源：http://dali.sweek.top/Article/details/gtlnoijxzg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zdqjudy.top/Article/details/gtpswnkztb.html

[U65] PHP：会话
来源：http://dali.jqgufenzy.top/Article/details/gtqewnuwvx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gttgzsjjvz.html

[U66] PHP：设置 Cookie
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstsylqjt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinqigufen.top/Article/details/gtrpqtargs.html

[U67] PHP：处理文件上传
来源：http://dali.yanxiufei.cn/Article/details/gtgutxsvfy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhiwuduotai.top/Article/details/gtvrokeyll.html

[U68] PHP：PDO 连接
来源：http://dali.nanxuanxn.top/Article/details/gtprybuoku.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.vqdsnc.cn/Article/details/gtdxurrmiu.html

[U69] PHP：PDO 预处理
来源：http://dali.hfpthk.cn/Article/details/gtiedogpfa.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shuidangran.top/Article/details/gtnurucqtc.html

[U70] PHP：PDO 事务
来源：http://dali.ppjwa.cn/Article/details/gtxfqijpcb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zdqjudy.top/Article/details/gtraxaxima.html

[U71] PHP：抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gtzrnuvzkk.html

throw new RuntimeException("失败", 500);
来源：http://dali.yangfankeji.com/Article/details/gtejyzhawm.html

[U72] PHP：写错误日志
来源：http://dali.snrcjt.cn/Article/details/gtyqabutdu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.daria6918.cn/Article/details/gtfxgiwufn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhixingplan.top/Article/details/gtltdyjuvd.html

parse_ini_file("config.ini", true)
来源：http://dali.mhx1999.top/Article/details/gtlylhbgdb.html

[U74] PHP：读取环境变量
来源：http://dali.jqgfzy.top/Article/details/gtcoqnwdyj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hnxiangtu.top/Article/details/gtgxppinbc.html

[U75] PHP：依赖注入
来源：http://dali.havefunace.top/Article/details/gtjvoshzwx.html

composer require psr/container
来源：http://dali.redwolf501.top/Article/details/gtcdmnhihf.html

[U76] PHP：简单路由
来源：http://dali.bjfxy.top/Article/details/gtboupajua.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.fzhhl.top/Article/details/gtbjgpxsrc.html

[U77] PHP：模板渲染
来源：http://dali.cucudq.cn/Article/details/gtyugxqftv.html

composer require twig/twig
来源：http://dali.feifeiyinyue.top/Article/details/gttkyatzln.html

[U78] PHP：单元测试
来源：http://dali.cdnleiting.top/Article/details/gtwaetzpsz.html

composer require --dev phpunit/phpunit
来源：http://dali.yj202588.top/Article/details/gtgfqbbyaj.html

[U79] PHP：静态分析
来源：http://dali.birdmap.top/Article/details/gtpntfcxbv.html

composer require --dev phpstan/phpstan
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsemqkxn.html

[U80] PHP：代码规范修复
来源：http://dali.kuanghao11.cn/Article/details/gtftddwarb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hongshengwenyu.top/Article/details/gtmpcxurru.html

[U81] JS：初始化项目
来源：http://dali.jiagoushi.top/Article/details/gtedhoeexw.html

npm init -y;  npm i express
来源：http://dali.ppjwa.cn/Article/details/gtfznsyvcx.html

[U82] JS：package.json 脚本
来源：http://dali.xylfe.cn/Article/details/gtmfafgbqe.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cashguo.top/Article/details/gtmukdkmkb.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinqigufen.top/Article/details/gtnmegdjlm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhiwuduotai.top/Article/details/gtyhqwjkmf.html

[U84] JS：CommonJS 写法
来源：http://dali.vqdsnc.cn/Article/details/gtcxmervup.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.aibaodan.cn/Article/details/gtrcvfhhyp.html

[U85] JS：可选链
来源：http://dali.ehwqpu.com/Article/details/gtttowrwsu.html

a?.b?.c
来源：http://dali.kuanghao11.cn/Article/details/gtiplwnytb.html

[U86] JS：空值合并
来源：http://dali.guowangkeji.top/Article/details/gtyfkqgzak.html

a ?? b
来源：http://dali.feifeiyinyue.top/Article/details/gtlffrpxho.html

[U87] JS：解构默认值
来源：http://dali.jqgufenzy.top/Article/details/gttlpmscyt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hammf.cn/Article/details/gtrkvgapxf.html

[U88] JS：对象展开合并
来源：http://dali.ivvv.top/Article/details/gtioqbrwyw.html

{ ...a, ...b }
来源：http://dali.yuanzhike.top/Article/details/gtrzouxdvc.html

[U89] JS：数组去重
来源：http://dali.c1oappe.top/Article/details/gtrsuwrgxc.html

[...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gttsmhuowe.html

[U90] JS：数字数组排序
来源：http://dali.hammf.cn/Article/details/gtpoijpiqc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gtkusqgehu.html

[U91] JS：对象键值遍历
来源：http://dali.hywenlv.cn/Article/details/gtiopmmkyp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sufxvd.cn/Article/details/gtuorgrblm.html

[U92] JS：深拷贝
来源：http://dali.hnqzz.top/Article/details/gteemhqfwi.html

structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gtutfrvrde.html


<!-- 参考信息 -->