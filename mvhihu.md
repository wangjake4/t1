代发 wailian999

[T03] Kotlin：字符串模板
来源：http://dali.pycfn.com/Article/details/gtkmdaqncf.html

"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusfxirsr.html

[T04] Kotlin：空安全
来源：http://dali.zdqjudy.top/Article/details/gtmjemtqqq.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofatlsit.html

[T05] Kotlin：when 表达式
来源：http://dali.zhengqikj.top/Article/details/gtgeznsptk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.iojbl.cn/Article/details/gtutidtqgm.html

[T06] Kotlin：集合映射
来源：http://dali.smart0.xyz/Article/details/gtvrrdpyma.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtoffqgblg.html

[T07] Kotlin：集合过滤
来源：http://dali.xziqi.cn/Article/details/gtjydseleg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dashuyun.cn/Article/details/gtonjgpxep.html

[T08] Kotlin：数据类
来源：http://dali.vqdsnc.cn/Article/details/gtciqorgng.html

data class User(val name: String, val age: Int)
来源：http://dali.ivvv.top/Article/details/gtdvvuhhzq.html

[T09] Kotlin：扩展函数
来源：http://dali.fengsongda.top/Article/details/gtrrxringp.html

fun String.exclaim() = this + "!"
来源：http://dali.yvedp.cn/Article/details/gthkgsmgrm.html

[T10] Kotlin：默认参数
来源：http://dali.cheryme.top/Article/details/gtorgfvvtw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zdqjudy.top/Article/details/gtbvjrbsbd.html

[T11] Kotlin：协程
来源：http://dali.9152youxi.cn/Article/details/gtdjoxdaop.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guannengcc.top/Article/details/gtzpwxrlia.html

[T12] Kotlin：解构声明
来源：http://dali.wangdashe.top/Article/details/gtakfwemwa.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtwtsjzbam.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqfhrwti.html

val m = mapOf("a" to 1)
来源：http://dali.ehwqpu.com/Article/details/gtsfnabaqn.html

[T14] Kotlin：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfirpmndp.html

for (i in 1..10) println(i)
来源：http://dali.hammf.cn/Article/details/gtcxzjezwi.html

[T15] Kotlin：接口
来源：http://dali.yuanzhike.top/Article/details/gtebzlozet.html

interface Shape { fun area(): Double }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcwhsdfp.html

[T16] Swift：Hello World
来源：http://dali.birdmap.top/Article/details/gtfujyvmlv.html

print("Hello")
来源：http://dali.yuxming.cn/Article/details/gtpxlaoevl.html

[T17] Swift：变量与常量
来源：http://dali.daria6918.cn/Article/details/gtzhqcpdrb.html

var a = 1;  let b = 2
来源：http://dali.sxryk.cn/Article/details/gtxjhtzibf.html

[T18] Swift：字符串插值
来源：http://dali.birdmap.top/Article/details/gtvctgqska.html

"值: \(b)"
来源：http://dali.yongpay.top/Article/details/gtzcbygkwz.html

[T19] Swift：可选绑定
来源：http://dali.zhixingplan.top/Article/details/gtrgwntjdy.html

if let n = opt { print(n) }
来源：http://dali.xinyue.icu/Article/details/gtyvktdfxb.html

[T20] Swift：数组操作
来源：http://dali.zhoulong.xyz/Article/details/gtgyfzjkqr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj202588.top/Article/details/gteduduhrl.html

[T21] Swift：遍历
来源：http://dali.0kj1m.cn/Article/details/gtaluogqnc.html

for x in a { print(x) }
来源：http://dali.xziqi.cn/Article/details/gtgnuixcbz.html

[T22] Swift：字典
来源：http://dali.cheryme.top/Article/details/gtiasbocbe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fzhhl.top/Article/details/gtwppstazk.html

[T23] Swift：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwkijcwg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fengsongda.top/Article/details/gtifjjytor.html

[T24] Swift：闭包
来源：http://dali.tianlin.xyz/Article/details/gteakyjwhj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtnnzlwzvi.html

[T25] Swift：结构体
来源：http://dali.aizwys.cn/Article/details/gtfpzownbr.html

struct P { var x: Int }
来源：http://dali.jiagoushi.top/Article/details/gtzvxfmtoa.html

[T26] Swift：类与重写
来源：http://dali.sxryk.cn/Article/details/gtdjgshiag.html

class A: Base { override func f() {} }
来源：http://dali.chenzaomai.com/Article/details/gtnpigdntq.html

[T27] Swift：错误处理
来源：http://dali.tanke756.top/Article/details/gtdyrfbyji.html

do { try f() } catch { print(error) }
来源：http://dali.haohaochexian.top/Article/details/gthjcsewkj.html

[T28] Swift：枚举
来源：http://dali.jianghu66.top/Article/details/gtxpzymymc.html

enum Color { case red, green }
来源：http://dali.guannengcc.top/Article/details/gtkwfisgbm.html

[T29] Swift：guard 提前返回
来源：http://dali.sxryk.cn/Article/details/gtgcaayzdk.html

guard let x = opt else { return }
来源：http://dali.mhx1999.top/Article/details/gtpfokkshn.html

[T30] Swift：协议
来源：http://dali.jinqigufen.top/Article/details/gtmqhrazyv.html

protocol Shape { func area() -> Double }
来源：http://dali.wangshuangyany.cn/Article/details/gtulxsdmfj.html

[T31] Lua：Hello World
来源：http://dali.ivvv.top/Article/details/gtkocazdai.html

print("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtyiqelrka.html

[T32] Lua：局部变量
来源：http://dali.0kj1m.cn/Article/details/gtmmsfaroc.html

local a = 1
来源：http://dali.shangyingyoupin.top/Article/details/gtjfxfceio.html

[T33] Lua：表（数组）
来源：http://dali.cucudq.cn/Article/details/gtcvsnlsug.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.haohaochexian.top/Article/details/gthutppodj.html

[T34] Lua：遍历表
来源：http://dali.tian-w.cn/Article/details/gtvrfizpzy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.birdmap.top/Article/details/gtfskgyuhj.html

[T35] Lua：字典表
来源：http://dali.yj20258.top/Article/details/gtxxbmpfyn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.kuanghao11.cn/Article/details/gtxqtswewt.html

[T36] Lua：函数
来源：http://dali.aizwys.cn/Article/details/gtvekxtyem.html

function add(a, b) return a + b end
来源：http://dali.daria6918.cn/Article/details/gtdpkppzom.html

[T37] Lua：字符串拼接
来源：http://dali.sysykeji.top/Article/details/gtbestferq.html

"a" .. "b"
来源：http://dali.ehwqpu.com/Article/details/gtupnhzjad.html

[T38] Lua：条件
来源：http://dali.hfpthk.cn/Article/details/gtcjhovxwc.html

if x > 0 then print("正") end
来源：http://dali.nanxinkj.top/Article/details/gtyldlobzz.html

[T39] Lua：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gtftpetaxe.html

string.find(s, "%d+")
来源：http://dali.smart0.xyz/Article/details/gtmwtjzhcn.html

[T40] Lua：元表
来源：http://dali.cucudq.cn/Article/details/gtcjvnirwn.html

setmetatable({}, { __index = base })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuomrinlj.html

[T41] Perl：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtebnofmtt.html

print "Hello\n";
来源：http://dali.andypj.xyz/Article/details/gtwsrjtsto.html

[T42] Perl：变量类型
来源：http://dali.dashuyun.cn/Article/details/gtdsrqjnbo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gotoacloud.top/Article/details/gtcmmdtpme.html

[T43] Perl：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtikjyhczo.html

"值: $a"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcgceceq.html

[T44] Perl：条件
来源：http://dali.tanke756.top/Article/details/gtgzipjmnr.html

if ($a > 0) { print "正"; }
来源：http://dali.zycfv.cn/Article/details/gtqbqxaboe.html

[T45] Perl：数组遍历
来源：http://dali.tianlin.xyz/Article/details/gtpkooehgt.html

for my $x (@arr) { print $x; }
来源：http://dali.sxryk.cn/Article/details/gtphuthime.html

[T46] Perl：哈希操作
来源：http://dali.yj20258.top/Article/details/gthskxiicy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrjogjvij.html

[T47] Perl：正则捕获
来源：http://dali.cdnleiting.top/Article/details/gtckxdzslq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yonumen.top/Article/details/gtlirbqinl.html

[T48] Perl：正则替换
来源：http://dali.quarkkingdee.top/Article/details/gtphystmyv.html

$s =~ s/old/new/g;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskkjkafo.html

[T49] Perl：函数
来源：http://dali.9152youxi.cn/Article/details/gtuyqescdh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtcqsulsmd.html

[T50] Perl：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtlssllmyk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.smart0.xyz/Article/details/gtvsyzyith.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.bjfxy.top/Article/details/gtrwuhtnwi.html

[T51] Scala：Hello World
来源：http://dali.yj20258888.top/Article/details/gtswunvtuk.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtkpbbhgxq.html

[T52] Scala：变量
来源：http://dali.svipenyu.cn/Article/details/gtkkoqhbnj.html

val a = 1;  var b = 2
来源：http://dali.yj202588.top/Article/details/gtquggrtdl.html

[T53] Scala：字符串插值
来源：http://dali.ivvv.top/Article/details/gtfnmpzotl.html

s"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpoakkijd.html

[T54] Scala：集合映射
来源：http://dali.fengsongda.top/Article/details/gtrccfoerx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dianchejie.cn/Article/details/gtsrnuvjub.html

[T55] Scala：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gtvcvzgrtx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxuanxn.top/Article/details/gtdvgeloqb.html

[T56] Scala：样例类
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsjdrqqn.html

case class User(name: String, age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtosgbldnn.html

[T57] Scala：模式匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtzbxjgfng.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yanxiufei.cn/Article/details/gtjmteknml.html

[T58] Scala：函数定义
来源：http://dali.hfpthk.cn/Article/details/gtshrmlkbf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gotoacloud.top/Article/details/gtrvnomiwv.html

[T59] Scala：循环
来源：http://dali.ehwqpu.com/Article/details/gtcqgvjoir.html

for (i <- 1 to 10) println(i)
来源：http://dali.zycfv.cn/Article/details/gtulowltin.html

[T60] Scala：折叠
来源：http://dali.daria6918.cn/Article/details/gtdtkydxpz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.andypj.xyz/Article/details/gtqrymhgex.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtgigckqyc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.guannengcc.top/Article/details/gteficjlna.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtuzxvgzcb.html

[U01] Py：创建虚拟环境
来源：http://dali.ivvv.top/Article/details/gtalzklgez.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fengsongda.top/Article/details/gtijcjtett.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nwbrower.top/Article/details/gtsqjiazss.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.bjfxy.top/Article/details/gtoeiwzcgn.html

[U03] Py：加载 .env 配置
来源：http://dali.daria6918.cn/Article/details/gttlbvwmke.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxuanxn.top/Article/details/gtiejamwwk.html

[U04] Py：变量调试打印
来源：http://dali.smart0.xyz/Article/details/gtwdltxygs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigufen.top/Article/details/gtjpgvjfzu.html

[U05] Py：列表去重且保序
来源：http://dali.wangdashe.top/Article/details/gtkbdhtfcj.html

list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtnxqnrbjk.html

[U06] Py：合并两个字典
来源：http://dali.yj202588.top/Article/details/gtiylspctn.html

{**a, **b}
来源：http://dali.ybcxt.top/Article/details/gtjuwzwsdc.html

[U07] Py：反转字典键值
来源：http://dali.gogol.net.cn/Article/details/gtalcgcuwq.html

{v: k for k, v in d.items()}
来源：http://dali.shuidangran.top/Article/details/gtuxrhnygi.html

[U08] Py：展平二维列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknfvxuki.html

[y for x in nested for y in x]
来源：http://dali.cashguo.top/Article/details/gtprhdhzbl.html

[U09] Py：字典取最大值的键
来源：http://dali.dianchejie.cn/Article/details/gtifmxofha.html

max(d, key=d.get)
来源：http://dali.daxiang520.top/Article/details/gtzypefsux.html

[U10] Py：按值排序字典
来源：http://dali.yangfankeji.com/Article/details/gtdpeyyosv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shzxlz.cn/Article/details/gtjcbjjfrw.html

[U11] Py：生成器表达式
来源：http://dali.fengsongda.top/Article/details/gtbxpyafdd.html

(x * 2 for x in arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgshixooi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.fzhhl.top/Article/details/gtjmellndy.html

Counter(arr).most_common(3)
来源：http://dali.snrcjt.cn/Article/details/gtsupkombl.html

[U13] Py：固定长度队列
来源：http://dali.hywenlv.cn/Article/details/gtcpvflekf.html

deque(maxlen=10)
来源：http://dali.zhoulong.xyz/Article/details/gtinkglucy.html

[U14] Py：分组收集到列表
来源：http://dali.quarkkingdee.top/Article/details/gtlqajvbjg.html

defaultdict(list)
来源：http://dali.hammf.cn/Article/details/gtxqbvmofk.html

[U15] Py：高精度计时
来源：http://dali.quarkkingdee.top/Article/details/gtdefpkzdt.html

t = time.perf_counter()
来源：http://dali.daxiang520.top/Article/details/gtjblojxpp.html

[U16] Py：命令行参数解析
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibmtezgf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhoulong.xyz/Article/details/gtrddhctlk.html

[U17] Py：初始化日志
来源：http://dali.ehwqpu.com/Article/details/gtjqlehgop.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuncwszg.html

[U18] Py：预编译正则
来源：http://dali.chenzaomai.com/Article/details/gtzqwfzval.html

pat = re.compile(r"\d+")
来源：http://dali.jlsjyb.cn/Article/details/gtwccmvgto.html

[U19] Py：正则替换带回调
来源：http://dali.jqgfzy.top/Article/details/gtoypxqdkq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.dianchejie.cn/Article/details/gtlibigxym.html

[U20] Py：缓存函数结果
来源：http://dali.tian-w.cn/Article/details/gtsdjwaxnb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yonumen.top/Article/details/gtjsvmqier.html

[U21] Py：自定义上下文管理器
来源：http://dali.316326.xyz/Article/details/gtpyyxlbye.html

@contextlib.contextmanager
来源：http://dali.316326.xyz/Article/details/gtexjbpwmb.html

[U22] Py：矩阵转置
来源：http://dali.9152youxi.cn/Article/details/gtgzaqiitr.html

list(zip(*m))
来源：http://dali.hnqzz.top/Article/details/gtiscasjhv.html

[U23] Py：分块读取大文件
来源：http://dali.jyoumei.cn/Article/details/gtfaccsern.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.andypj.xyz/Article/details/gtukucbqfn.html

[U24] Py：路径操作
来源：http://dali.tanke756.top/Article/details/gtszzvyyfo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gtonypambp.html

[U25] Py：CSV 按字典读
来源：http://dali.smart0.xyz/Article/details/gtzghmntvs.html

csv.DictReader(f)
来源：http://dali.nanxuanxn.top/Article/details/gtkevsavxi.html

[U26] Py：并发下载
来源：http://dali.xylfe.cn/Article/details/gtfgkalcmg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.mhx1999.top/Article/details/gtcrskbikn.html

[U27] Py：异步 HTTP
来源：http://dali.havefunace.top/Article/details/gtccjcfibl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yongpay.top/Article/details/gtaleadjxc.html

[U28] Py：类型别名
来源：http://dali.ybcxt.top/Article/details/gtxzboyozh.html

UserId = int
来源：http://dali.meibo888.top/Article/details/gtjopawbfu.html

[U29] Py：属性校验
来源：http://dali.yangfankeji.com/Article/details/gtpdfhmeeb.html

@property 与 @x.setter 配合
来源：http://dali.meibo888.top/Article/details/gtdhreipgi.html

[U30] Py：数据类
来源：http://dali.daria6918.cn/Article/details/gtrawnguud.html

@dataclass(slots=True)
来源：http://dali.yanxiufei.cn/Article/details/gthdmvoqjb.html

[U31] Py：单测
来源：http://dali.chenjidiqi.icu/Article/details/gtiuopuvtg.html

python -m pytest -q
来源：http://dali.nanxinkj.top/Article/details/gthejkhygb.html

[U32] Py：代码格式化
来源：http://dali.yueranfly.top/Article/details/gtvzmizjfv.html

ruff format . && ruff check --fix .
来源：http://dali.tianlin.xyz/Article/details/gtulwywshs.html

[U33] Py：打包发布
来源：http://dali.iojbl.cn/Article/details/gtmonnoijq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.vqdsnc.cn/Article/details/gtvaevpoih.html

[U34] Py：判断编码
来源：http://dali.dashuyun.cn/Article/details/gtclvuiicj.html

chardet.detect(raw)
来源：http://dali.fzhhl.top/Article/details/gtadnovuhf.html

[U35] Py：发送邮件
来源：http://dali.zhiwuduotai.top/Article/details/gtfmuuezkc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.0kj1m.cn/Article/details/gtmogymiku.html

[U36] Py：定时任务
来源：http://dali.yj202588.top/Article/details/gtcwzimmsa.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinqigufen.top/Article/details/gtruvgdozn.html

[U37] Py：读写 Excel
来源：http://dali.daria6918.cn/Article/details/gtjxmdahfd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cucudq.cn/Article/details/gteujxnbnk.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinqigufen.top/Article/details/gtcujlzazf.html

Path(__file__).resolve().parent
来源：http://dali.svipenyu.cn/Article/details/gtyhaeltql.html

[U39] Py：判断是否在交互环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwhozrxp.html

sys.stdout.isatty()
来源：http://dali.gogol.net.cn/Article/details/gtlbznadeo.html

[U40] Py：打印到标准错误
来源：http://dali.jlsjyb.cn/Article/details/gtnrvakzli.html

print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gtavlyssdy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jyoumei.cn/Article/details/gtvvoqwumu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cqqwz.cn/Article/details/gtwwwlfhkv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.nwbrower.top/Article/details/gtnvpdvpcz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhixingplan.top/Article/details/gtnhtlbnxk.html

[U43] PHP：声明命名空间
来源：http://dali.zdqjudy.top/Article/details/gtgnnhexrt.html

namespace App\Http;
来源：http://dali.fzhhl.top/Article/details/gtitofgrxx.html

[U44] PHP：开启严格类型
来源：http://dali.yj202588.top/Article/details/gtwodquehi.html

declare(strict_types=1);
来源：http://dali.snrcjt.cn/Article/details/gtvpynutvh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.iojbl.cn/Article/details/gtgvzviaho.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnoawgsav.html

[U46] PHP：可空类型
来源：http://dali.chenjidiqi.icu/Article/details/gtqneatngr.html

?string $name = null
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvawcrdvk.html

[U47] PHP：联合类型
来源：http://dali.zhiwuduotai.top/Article/details/gtiuuoxkrs.html

int|string $id
来源：http://dali.shzxlz.cn/Article/details/gtocqevxfe.html

[U48] PHP：纯枚举
来源：http://dali.9152youxi.cn/Article/details/gtjdivylju.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.snrcjt.cn/Article/details/gtgclwxppf.html

[U49] PHP：只读属性
来源：http://dali.guannengcc.top/Article/details/gtyonwctqr.html

public readonly string $name
来源：http://dali.shangyingyoupin.top/Article/details/gtcveqqrnt.html

[U50] PHP：构造器属性提升
来源：http://dali.daxiang520.top/Article/details/gtugbtgsnx.html

public function __construct(private int $id) {}
来源：http://dali.aibaodan.cn/Article/details/gthvltkpyl.html

[U51] PHP：数组解构
来源：http://dali.ybcxt.top/Article/details/gtnqfegdvj.html

[$a, $b] = $arr;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrdxzmfr.html

[U52] PHP：箭头函数
来源：http://dali.gotoacloud.top/Article/details/gtrnbityjz.html

$double = fn($x) => $x * 2;
来源：http://dali.cdnleiting.top/Article/details/gtunmelnxi.html

[U53] PHP：空合并运算符
来源：http://dali.jianghu66.top/Article/details/gtoyyterfs.html

$v = $a ?? $b ?? "default";
来源：http://dali.dashuyun.cn/Article/details/gtjwwqmucg.html

[U54] PHP：空安全调用
来源：http://dali.sxryk.cn/Article/details/gtbhckphiu.html

$obj?->method()
来源：http://dali.pengpengdd.cyou/Article/details/gtbnjermoz.html

[U55] PHP：match 表达式
来源：http://dali.jlsjyb.cn/Article/details/gtwtykoonm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.tanke756.top/Article/details/gtannsoqnu.html

[U56] PHP：命名参数
来源：http://dali.xuanzx.com/Article/details/gtewuoccib.html

f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtmmhtanjc.html

[U57] PHP：字符串插值
来源：http://dali.ydzc1.top/Article/details/gtxetkxtvz.html

"值: {$a}"
来源：http://dali.quarkkingdee.top/Article/details/gtjwndjdgb.html

[U58] PHP：数组三件套
来源：http://dali.hnqzz.top/Article/details/gtlwtpmwps.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinqigufen.top/Article/details/gtuchiimge.html

[U59] PHP：自定义排序
来源：http://dali.cdnleiting.top/Article/details/gtgpzsqpib.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gtytdnqpvi.html

[U60] PHP：JSON 编解码
来源：http://dali.andypj.xyz/Article/details/gtsewiwelf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.tanke756.top/Article/details/gtfnwbblqw.html

[U61] PHP：正则
来源：http://dali.snrcjt.cn/Article/details/gtjghkyews.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenlongwang.top/Article/details/gtripnlats.html

[U62] PHP：日期对象
来源：http://dali.cdnleiting.top/Article/details/gtwffkinum.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gaohongyu789.top/Article/details/gtosdbgqss.html

[U63] PHP：文件读写
来源：http://dali.zycfv.cn/Article/details/gtjtvuaiin.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.birdmap.top/Article/details/gtkgteyhbh.html

[U64] PHP：目录遍历
来源：http://dali.nwbrower.top/Article/details/gtpcfjlpro.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.andypj.xyz/Article/details/gtomunpzou.html

[U65] PHP：会话
来源：http://dali.cqqwz.cn/Article/details/gtlmgygetl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtnmfmguoq.html

[U66] PHP：设置 Cookie
来源：http://dali.zhiwuduotai.top/Article/details/gtevrpynrw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.quarkkingdee.top/Article/details/gtxquvlvzt.html

[U67] PHP：处理文件上传
来源：http://dali.9152youxi.cn/Article/details/gtxldictrm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zdqjudy.top/Article/details/gtemwirpnq.html

[U68] PHP：PDO 连接
来源：http://dali.tian-w.cn/Article/details/gttbnjrcph.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jyoumei.cn/Article/details/gthaaqdbpl.html

[U69] PHP：PDO 预处理
来源：http://dali.yuxming.cn/Article/details/gtbbpdqrcx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jqgufenzy.top/Article/details/gtbnqubahq.html

[U70] PHP：PDO 事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtlllnyqbk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.guannengcc.top/Article/details/gtdsoivaua.html

[U71] PHP：抛出异常
来源：http://dali.hammf.cn/Article/details/gtepegjzdr.html

throw new RuntimeException("失败", 500);
来源：http://dali.yuxming.cn/Article/details/gtvtcqdzra.html

[U72] PHP：写错误日志
来源：http://dali.wangdashe.top/Article/details/gtboxnaccv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ivvv.top/Article/details/gttkpoagmg.html

[U73] PHP：读取 ini 配置
来源：http://dali.yanxiufei.cn/Article/details/gtwhxlybgb.html

parse_ini_file("config.ini", true)
来源：http://dali.jianghu66.top/Article/details/gtcnyvkorx.html

[U74] PHP：读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtfdcxmjsv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gogol.net.cn/Article/details/gtlhjadgbt.html

[U75] PHP：依赖注入
来源：http://dali.0kj1m.cn/Article/details/gtajxftoum.html

composer require psr/container
来源：http://dali.tanke756.top/Article/details/gtypwaouga.html

[U76] PHP：简单路由
来源：http://dali.9152youxi.cn/Article/details/gteqwavjfn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.aizwys.cn/Article/details/gtrtpyrwno.html

[U77] PHP：模板渲染
来源：http://dali.gzhubu.top/Article/details/gttfjndxwk.html

composer require twig/twig
来源：http://dali.tian-w.cn/Article/details/gtasolwelo.html

[U78] PHP：单元测试
来源：http://dali.daria6918.cn/Article/details/gtghwuvplr.html

composer require --dev phpunit/phpunit
来源：http://dali.zycfv.cn/Article/details/gtstpttnqw.html

[U79] PHP：静态分析
来源：http://dali.fzhhl.top/Article/details/gtzklsdomn.html

composer require --dev phpstan/phpstan
来源：http://dali.zhengqikj.top/Article/details/gtuojflque.html

[U80] PHP：代码规范修复
来源：http://dali.dashuyun.cn/Article/details/gtkqblttnn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shuidangran.top/Article/details/gtnjlvcjjx.html

[U81] JS：初始化项目
来源：http://dali.yuanzhike.top/Article/details/gtzvedktlk.html

npm init -y;  npm i express
来源：http://dali.zhixingplan.top/Article/details/gtfluczjer.html

[U82] JS：package.json 脚本
来源：http://dali.yvedp.cn/Article/details/gtftkdwkqq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yj202588.top/Article/details/gtnzncudmh.html

[U83] JS：ES Module 导入导出
来源：http://dali.smart0.xyz/Article/details/gtziyaxqlz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gtpgvuizrf.html

[U84] JS：CommonJS 写法
来源：http://dali.pengpengdd.cyou/Article/details/gtzcjbqvzd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.smart0.xyz/Article/details/gtztalmwbe.html

[U85] JS：可选链
来源：http://dali.ivvv.top/Article/details/gternarcpp.html

a?.b?.c
来源：http://dali.jiagoushi.top/Article/details/gtkvxefyxv.html

[U86] JS：空值合并
来源：http://dali.nanxuanxn.top/Article/details/gtxyamcykw.html

a ?? b
来源：http://dali.mhx1999.top/Article/details/gtrsdvgafa.html

[U87] JS：解构默认值
来源：http://dali.gzhubu.top/Article/details/gtxrxxrauc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhongyouzk.top/Article/details/gtlhfcluux.html

[U88] JS：对象展开合并
来源：http://dali.jinqigfzy.top/Article/details/gtojaxwrtj.html

{ ...a, ...b }
来源：http://dali.hongshengwenyu.top/Article/details/gtklngxdxy.html

[U89] JS：数组去重
来源：http://dali.tanke756.top/Article/details/gtlpxrbotn.html

[...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtggmpngej.html

[U90] JS：数字数组排序
来源：http://dali.hnqzz.top/Article/details/gtzrnpujwl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtgduylwgm.html


<!-- 参考信息 -->