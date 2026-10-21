代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.zhixingplan.top/Article/details/gtyxbzijqs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.andypj.xyz/Article/details/gtjctknhox.html

[T06] Kotlin：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gtlrcusjlm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxinkj.top/Article/details/gttfdttqvu.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258.top/Article/details/gthijcdmtb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigfzy.top/Article/details/gthexdlmau.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangtech.top/Article/details/gtypssdfmd.html

data class User(val name: String, val age: Int)
来源：http://dali.sxryk.cn/Article/details/gtgssimpfx.html

[T09] Kotlin：扩展函数
来源：http://dali.zhixingplan.top/Article/details/gteunmsbii.html

fun String.exclaim() = this + "!"
来源：http://dali.wangdashe.top/Article/details/gtelsoyiiv.html

[T10] Kotlin：默认参数
来源：http://dali.9152youxi.cn/Article/details/gthhpfbtdk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxinkj.top/Article/details/gtezxfjtww.html

[T11] Kotlin：协程
来源：http://dali.0kj1m.cn/Article/details/gtkpqlmeul.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aizwys.cn/Article/details/gtxpdyvkat.html

[T12] Kotlin：解构声明
来源：http://dali.zhiwuduotai.top/Article/details/gtrqhmrcmm.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtuowrstur.html

[T13] Kotlin：只读 Map
来源：http://dali.yvedp.cn/Article/details/gtkggikyrj.html

val m = mapOf("a" to 1)
来源：http://dali.svipenyu.cn/Article/details/gtaiqksljk.html

[T14] Kotlin：循环
来源：http://dali.meibo888.top/Article/details/gtgyinbkwt.html

for (i in 1..10) println(i)
来源：http://dali.mhx1999.top/Article/details/gtmbuheqgs.html

[T15] Kotlin：接口
来源：http://dali.chenlongwang.top/Article/details/gtsiwrogwo.html

interface Shape { fun area(): Double }
来源：http://dali.yongpay.top/Article/details/gtcfxtmfob.html

[T16] Swift：Hello World
来源：http://dali.cashguo.top/Article/details/gtwhgjixxm.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtqzoglrje.html

[T17] Swift：变量与常量
来源：http://dali.dianchejie.cn/Article/details/gtymnrbefp.html

var a = 1;  let b = 2
来源：http://dali.xuanzx.com/Article/details/gtckwprazq.html

[T18] Swift：字符串插值
来源：http://dali.316326.xyz/Article/details/gtfftrgbuh.html

"值: \(b)"
来源：http://dali.snrcjt.cn/Article/details/gtzcxzbfmt.html

[T19] Swift：可选绑定
来源：http://dali.chenlongwang.top/Article/details/gtepgkobtu.html

if let n = opt { print(n) }
来源：http://dali.cdnleiting.top/Article/details/gtfxkflhxj.html

[T20] Swift：数组操作
来源：http://dali.yj20258888.top/Article/details/gtzzxltypr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sweek.top/Article/details/gtjsnrjzjt.html

[T21] Swift：遍历
来源：http://dali.jqgufenzy.top/Article/details/gtoofkvdhw.html

for x in a { print(x) }
来源：http://dali.chenlongwang.top/Article/details/gtcnjjskuv.html

[T22] Swift：字典
来源：http://dali.hywenlv.cn/Article/details/gtnuomrhrl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nwbrower.top/Article/details/gttnuwcnfm.html

[T23] Swift：函数
来源：http://dali.birdmap.top/Article/details/gtfwjxbaew.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nwbrower.top/Article/details/gtfasmzafy.html

[T24] Swift：闭包
来源：http://dali.chenzaomai.com/Article/details/gthqspepds.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fzhhl.top/Article/details/gtyaqafcpd.html

[T25] Swift：结构体
来源：http://dali.xuanzx.com/Article/details/gtaomvsmwv.html

struct P { var x: Int }
来源：http://dali.hysaishi.cn/Article/details/gtpvshuoho.html

[T26] Swift：类与重写
来源：http://dali.cucudq.cn/Article/details/gtquswxrtl.html

class A: Base { override func f() {} }
来源：http://dali.nanxinkj.top/Article/details/gtudfmimnv.html

[T27] Swift：错误处理
来源：http://dali.gzhubu.top/Article/details/gtkbzjcmkt.html

do { try f() } catch { print(error) }
来源：http://dali.zdqjudy.top/Article/details/gtygjbsfca.html

[T28] Swift：枚举
来源：http://dali.daxiang520.top/Article/details/gtzksfzpsu.html

enum Color { case red, green }
来源：http://dali.feifeiyinyue.top/Article/details/gtrgimngxq.html

[T29] Swift：guard 提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gthnnsgwyo.html

guard let x = opt else { return }
来源：http://dali.cqqwz.cn/Article/details/gtansnphfq.html

[T30] Swift：协议
来源：http://dali.jlsjyb.cn/Article/details/gteauhmfna.html

protocol Shape { func area() -> Double }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtweuwcvpk.html

[T31] Lua：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtjochhqmw.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtsuxsjenl.html

[T32] Lua：局部变量
来源：http://dali.daxiang520.top/Article/details/gtnijmrfjc.html

local a = 1
来源：http://dali.guannengcc.top/Article/details/gtojptzpdg.html

[T33] Lua：表（数组）
来源：http://dali.wangshuangyany.cn/Article/details/gtoctisrip.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xylfe.cn/Article/details/gtsxtlejui.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gtubbxymji.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gotoacloud.top/Article/details/gtribuiswu.html

[T35] Lua：字典表
来源：http://dali.haohaochexian.top/Article/details/gtpfgaaimg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jlsjyb.cn/Article/details/gtqlgpifgy.html

[T36] Lua：函数
来源：http://dali.cdnleiting.top/Article/details/gtrjotvvhj.html

function add(a, b) return a + b end
来源：http://dali.dianchejie.cn/Article/details/gttltxqqpr.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258.top/Article/details/gtpdlzucgo.html

"a" .. "b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlabukxfb.html

[T38] Lua：条件
来源：http://dali.wangshuangyany.cn/Article/details/gtwmixwxmv.html

if x > 0 then print("正") end
来源：http://dali.jinqigfzy.top/Article/details/gtzoglkvyd.html

[T39] Lua：模式匹配
来源：http://dali.tanke756.top/Article/details/gtykrwszmq.html

string.find(s, "%d+")
来源：http://dali.sufxvd.cn/Article/details/gtmckwmtwd.html

[T40] Lua：元表
来源：http://dali.tanke756.top/Article/details/gtkcmmydac.html

setmetatable({}, { __index = base })
来源：http://dali.hammf.cn/Article/details/gthltfwfee.html

[T41] Perl：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gttyoiwqtw.html

print "Hello\n";
来源：http://dali.9152youxi.cn/Article/details/gtlkpmwmst.html

[T42] Perl：变量类型
来源：http://dali.jianghu66.top/Article/details/gtiayghtlu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.daxiang520.top/Article/details/gtkhlwljsd.html

[T43] Perl：字符串插值
来源：http://dali.pycfn.com/Article/details/gtsuvknhqq.html

"值: $a"
来源：http://dali.snrcjt.cn/Article/details/gttcxsjzzr.html

[T44] Perl：条件
来源：http://dali.316326.xyz/Article/details/gtfcrdmsfk.html

if ($a > 0) { print "正"; }
来源：http://dali.cashguo.top/Article/details/gthdkftywq.html

[T45] Perl：数组遍历
来源：http://dali.haohaochexian.top/Article/details/gtevyjfqwv.html

for my $x (@arr) { print $x; }
来源：http://dali.quarkkingdee.top/Article/details/gtcxyrjtby.html

[T46] Perl：哈希操作
来源：http://dali.yongpay.top/Article/details/gtscdyhsfc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhengqikj.top/Article/details/gtmpysuqmz.html

[T47] Perl：正则捕获
来源：http://dali.ydzc1.top/Article/details/gtqwviepad.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.pycfn.com/Article/details/gtvniipljm.html

[T48] Perl：正则替换
来源：http://dali.gaohongyu789.top/Article/details/gtrxezsnob.html

$s =~ s/old/new/g;
来源：http://dali.cqqwz.cn/Article/details/gtbdroolie.html

[T49] Perl：函数
来源：http://dali.snrcjt.cn/Article/details/gtobtbdclm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtdoayomlf.html

[T50] Perl：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtiirbgrbb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj202588.top/Article/details/gtfyuanwiw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jlsjyb.cn/Article/details/gtozzpyqpn.html

[T51] Scala：Hello World
来源：http://dali.fzhhl.top/Article/details/gtkpnwplqr.html

println("Hello")
来源：http://dali.shuidangran.top/Article/details/gtqtqjpwan.html

[T52] Scala：变量
来源：http://dali.zhiwuduotai.top/Article/details/gtddjuwfob.html

val a = 1;  var b = 2
来源：http://dali.sufxvd.cn/Article/details/gtqlxfbhjc.html

[T53] Scala：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gthrmbznip.html

s"值: $b"
来源：http://dali.daria6918.cn/Article/details/gtwkbfzjmh.html

[T54] Scala：集合映射
来源：http://dali.yuxming.cn/Article/details/gtmmfjkucp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.iojbl.cn/Article/details/gtgvboeoma.html

[T55] Scala：集合过滤
来源：http://dali.havefunace.top/Article/details/gtqqmplmak.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.9152youxi.cn/Article/details/gtbzawqhdl.html

[T56] Scala：样例类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjheoavm.html

case class User(name: String, age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gtfaoooirm.html

[T57] Scala：模式匹配
来源：http://dali.yvedp.cn/Article/details/gtcpvokhnc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cashguo.top/Article/details/gtbdqidrxt.html

[T58] Scala：函数定义
来源：http://dali.shangyingyoupin.top/Article/details/gtgnxjufza.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.redwolf501.top/Article/details/gtmahzpugf.html

[T59] Scala：循环
来源：http://dali.zhixingplan.top/Article/details/gtswymkusy.html

for (i <- 1 to 10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gtaamdfaon.html

[T60] Scala：折叠
来源：http://dali.daria6918.cn/Article/details/gtrdfcnbyn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenzaomai.com/Article/details/gtqtdhhept.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtoichepby.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenlongwang.top/Article/details/gtwnacnfbc.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtxkakosfm.html

[U01] Py：创建虚拟环境
来源：http://dali.haohaochexian.top/Article/details/gtsnkgyrnj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sxryk.cn/Article/details/gtjiifqaeg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gzhubu.top/Article/details/gtggoiuppe.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gotoacloud.top/Article/details/gtnosxjlva.html

[U03] Py：加载 .env 配置
来源：http://dali.zhongyouzk.top/Article/details/gtlzygqxmi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hywenlv.cn/Article/details/gtoxsllgkz.html

[U04] Py：变量调试打印
来源：http://dali.haohaochexian.top/Article/details/gtlquwieyl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gaohongyu789.top/Article/details/gtllnyixrl.html

[U05] Py：列表去重且保序
来源：http://dali.xylfe.cn/Article/details/gtdjfscelp.html

list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gtuwlrmksc.html

[U06] Py：合并两个字典
来源：http://dali.gogol.net.cn/Article/details/gtjzxfzyqf.html

{**a, **b}
来源：http://dali.nwbrower.top/Article/details/gtmbkvqyon.html

[U07] Py：反转字典键值
来源：http://dali.chenjidiqi.icu/Article/details/gtwbrxyfud.html

{v: k for k, v in d.items()}
来源：http://dali.xuanzx.com/Article/details/gtmkaimgjr.html

[U08] Py：展平二维列表
来源：http://dali.gotoacloud.top/Article/details/gtlevhdabq.html

[y for x in nested for y in x]
来源：http://dali.gzhubu.top/Article/details/gtrckmdgxf.html

[U09] Py：字典取最大值的键
来源：http://dali.nanxuanxn.top/Article/details/gticisqztl.html

max(d, key=d.get)
来源：http://dali.yj20258.top/Article/details/gteqxkblgk.html

[U10] Py：按值排序字典
来源：http://dali.jqgfzy.top/Article/details/gtmjhfeicy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jianghu66.top/Article/details/gtvadotveq.html

[U11] Py：生成器表达式
来源：http://dali.ivvv.top/Article/details/gtthfglcgf.html

(x * 2 for x in arr)
来源：http://dali.nanxuanxn.top/Article/details/gtiivzzmww.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtudsuhmvb.html

Counter(arr).most_common(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtxeufzrpy.html

[U13] Py：固定长度队列
来源：http://dali.svipenyu.cn/Article/details/gthvqegnex.html

deque(maxlen=10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtceiweehw.html

[U14] Py：分组收集到列表
来源：http://dali.gaohongyu789.top/Article/details/gtaxqfcdnh.html

defaultdict(list)
来源：http://dali.vqdsnc.cn/Article/details/gtdjrfvhjs.html

[U15] Py：高精度计时
来源：http://dali.redwolf501.top/Article/details/gtmsxqtoat.html

t = time.perf_counter()
来源：http://dali.jinqigfzy.top/Article/details/gthrvlnmly.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxlltjdg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmjoqrts.html

[U17] Py：初始化日志
来源：http://dali.feifeiyinyue.top/Article/details/gtweqrgdem.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gogol.net.cn/Article/details/gtoselskwb.html

[U18] Py：预编译正则
来源：http://dali.yongpay.top/Article/details/gtnozkmkbp.html

pat = re.compile(r"\d+")
来源：http://dali.316326.xyz/Article/details/gtdqidupra.html

[U19] Py：正则替换带回调
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdznuwgdo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.wangdashe.top/Article/details/gtfoxhywjd.html

[U20] Py：缓存函数结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhkwzxwu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tian-w.cn/Article/details/gticjbyrdm.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhoulong.xyz/Article/details/gtiftclpjo.html

@contextlib.contextmanager
来源：http://dali.quarkkingdee.top/Article/details/gtjmmsscsn.html

[U22] Py：矩阵转置
来源：http://dali.pengpengdd.cyou/Article/details/gtpodhdduh.html

list(zip(*m))
来源：http://dali.jianghu66.top/Article/details/gtziqhkoin.html

[U23] Py：分块读取大文件
来源：http://dali.sweek.top/Article/details/gtljnlwlux.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shangyingyoupin.top/Article/details/gtooggibpj.html

[U24] Py：路径操作
来源：http://dali.pycfn.com/Article/details/gtjnzicbzi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gtcfmhwtku.html

[U25] Py：CSV 按字典读
来源：http://dali.haohaochexian.top/Article/details/gtpvylhblu.html

csv.DictReader(f)
来源：http://dali.yj202588.top/Article/details/gtjmuqrqmb.html

[U26] Py：并发下载
来源：http://dali.fzhhl.top/Article/details/gttoldybun.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhoulong.xyz/Article/details/gtkryqeyhd.html

[U27] Py：异步 HTTP
来源：http://dali.svipenyu.cn/Article/details/gtoresswlx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yonumen.top/Article/details/gtvrnpbufv.html

[U28] Py：类型别名
来源：http://dali.zhengqikj.top/Article/details/gtgwlukadl.html

UserId = int
来源：http://dali.nanxuanxn.top/Article/details/gtsifwsuvg.html

[U29] Py：属性校验
来源：http://dali.gogol.net.cn/Article/details/gttizcrwtl.html

@property 与 @x.setter 配合
来源：http://dali.nwbrower.top/Article/details/gtzrqeboqf.html

[U30] Py：数据类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcosiibmj.html

@dataclass(slots=True)
来源：http://dali.shuidangran.top/Article/details/gtuegtidgm.html

[U31] Py：单测
来源：http://dali.hnxiangtu.top/Article/details/gtennzsaof.html

python -m pytest -q
来源：http://dali.ybcxt.top/Article/details/gtoojvickr.html

[U32] Py：代码格式化
来源：http://dali.zycfv.cn/Article/details/gtcjcgxaus.html

ruff format . && ruff check --fix .
来源：http://dali.ppjwa.cn/Article/details/gtpyifjbye.html

[U33] Py：打包发布
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonikcxbl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cashguo.top/Article/details/gtxibcyxcs.html

[U34] Py：判断编码
来源：http://dali.zhongyouzk.top/Article/details/gtqwpwipov.html

chardet.detect(raw)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzlippki.html

[U35] Py：发送邮件
来源：http://dali.yj20258888.top/Article/details/gtkxkayuxb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sysykeji.top/Article/details/gtzoaxluod.html

[U36] Py：定时任务
来源：http://dali.gzhubu.top/Article/details/gtwxbnouho.html

schedule.every(10).minutes.do(job)
来源：http://dali.cheryme.top/Article/details/gtuzcprmxc.html

[U37] Py：读写 Excel
来源：http://dali.sxryk.cn/Article/details/gtqfgnnazv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tanke756.top/Article/details/gtsquidqkr.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxhsaxsw.html

Path(__file__).resolve().parent
来源：http://dali.nanxuanxn.top/Article/details/gteshzzqwe.html

[U39] Py：判断是否在交互环境
来源：http://dali.nanxuanxn.top/Article/details/gtgzyomtue.html

sys.stdout.isatty()
来源：http://dali.snrcjt.cn/Article/details/gtilprfcjj.html

[U40] Py：打印到标准错误
来源：http://dali.hfpthk.cn/Article/details/gthkkvhrul.html

print("err", file=sys.stderr)
来源：http://dali.jiagoushi.top/Article/details/gttizhrmuk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yonumen.top/Article/details/gtuyvocmco.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.fengsongda.top/Article/details/gtzznmjlij.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.wangdashe.top/Article/details/gtraqssvrd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxspkaqx.html

[U43] PHP：声明命名空间
来源：http://dali.fengsongda.top/Article/details/gtnpdbmtkd.html

namespace App\Http;
来源：http://dali.yj202588.top/Article/details/gtahzxfxoq.html

[U44] PHP：开启严格类型
来源：http://dali.zycfv.cn/Article/details/gtfjfyxswm.html

declare(strict_types=1);
来源：http://dali.aizwys.cn/Article/details/gtjnncxqoe.html

[U45] PHP：类型声明与返回类型
来源：http://dali.9152youxi.cn/Article/details/gtwawazudy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtyrgghowl.html

[U46] PHP：可空类型
来源：http://dali.shangyingyoupin.top/Article/details/gtljmukuon.html

?string $name = null
来源：http://dali.daxiang520.top/Article/details/gtnbnhphzm.html

[U47] PHP：联合类型
来源：http://dali.cqqwz.cn/Article/details/gtjskdffsp.html

int|string $id
来源：http://dali.sufxvd.cn/Article/details/gtyigavheu.html

[U48] PHP：纯枚举
来源：http://dali.jiagoushi.top/Article/details/gtaugnsngy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtiiszvufn.html

[U49] PHP：只读属性
来源：http://dali.gogol.net.cn/Article/details/gtobbrisjt.html

public readonly string $name
来源：http://dali.pengpengdd.cyou/Article/details/gtmxcnkeud.html

[U50] PHP：构造器属性提升
来源：http://dali.cashguo.top/Article/details/gtyroagrme.html

public function __construct(private int $id) {}
来源：http://dali.yj20258.top/Article/details/gtyuvebmcy.html

[U51] PHP：数组解构
来源：http://dali.ydzc1.top/Article/details/gtpwydujvg.html

[$a, $b] = $arr;
来源：http://dali.hywenlv.cn/Article/details/gtjnhyvqmh.html

[U52] PHP：箭头函数
来源：http://dali.zhiwuduotai.top/Article/details/gtsaizrqlm.html

$double = fn($x) => $x * 2;
来源：http://dali.jyoumei.cn/Article/details/gtsagauwwk.html

[U53] PHP：空合并运算符
来源：http://dali.andypj.xyz/Article/details/gtouzlrcrb.html

$v = $a ?? $b ?? "default";
来源：http://dali.hnqzz.top/Article/details/gtuxoanzht.html

[U54] PHP：空安全调用
来源：http://dali.pycfn.com/Article/details/gtlmnuxmnp.html

$obj?->method()
来源：http://dali.sweek.top/Article/details/gtdpsnpsef.html

[U55] PHP：match 表达式
来源：http://dali.shuidangran.top/Article/details/gtbvywtjdi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.pengpengdd.cyou/Article/details/gtgmgreyvq.html

[U56] PHP：命名参数
来源：http://dali.gotoacloud.top/Article/details/gtqmbmgmpe.html

f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gtlgjcdngq.html

[U57] PHP：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gttfhpvfjy.html

"值: {$a}"
来源：http://dali.xylfe.cn/Article/details/gtlimizymb.html

[U58] PHP：数组三件套
来源：http://dali.zhengqikj.top/Article/details/gtspqcwqvi.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.guowangkeji.top/Article/details/gtwycuoxzx.html

[U59] PHP：自定义排序
来源：http://dali.yuanzhike.top/Article/details/gtdgvodlwf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gtsratttmk.html

[U60] PHP：JSON 编解码
来源：http://dali.dashuyun.cn/Article/details/gtaenkxemi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gtocaektki.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gtfgsekwyv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gtkkrgntvz.html

[U62] PHP：日期对象
来源：http://dali.yuanzhike.top/Article/details/gtqrsdavlf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.redwolf501.top/Article/details/gtsfgipqbn.html

[U63] PHP：文件读写
来源：http://dali.smart0.xyz/Article/details/gtkbsmadxu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jyoumei.cn/Article/details/gtedzockql.html

[U64] PHP：目录遍历
来源：http://dali.jlsjyb.cn/Article/details/gtejxcwsdi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.iojbl.cn/Article/details/gtukfpequs.html

[U65] PHP：会话
来源：http://dali.tianlin.xyz/Article/details/gtwsbqcdat.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtwwrnkxcv.html

[U66] PHP：设置 Cookie
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwaebvss.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.dashuyun.cn/Article/details/gtkgytrwxn.html

[U67] PHP：处理文件上传
来源：http://dali.chenzaomai.com/Article/details/gtsfckdyqa.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.vqdsnc.cn/Article/details/gtsqamlxjm.html

[U68] PHP：PDO 连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqaotzqip.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.kuanghao11.cn/Article/details/gteqofscjs.html

[U69] PHP：PDO 预处理
来源：http://dali.xziqi.cn/Article/details/gtndvkdvjt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.guannengcc.top/Article/details/gtceiqxgmi.html

[U70] PHP：PDO 事务
来源：http://dali.shzxlz.cn/Article/details/gtvgfzvgyn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sxryk.cn/Article/details/gthncnxfpp.html

[U71] PHP：抛出异常
来源：http://dali.gzhubu.top/Article/details/gtqiyzvvsh.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgttguis.html

[U72] PHP：写错误日志
来源：http://dali.dianchejie.cn/Article/details/gtuemsadtm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xziqi.cn/Article/details/gtyesginbd.html

[U73] PHP：读取 ini 配置
来源：http://dali.aizwys.cn/Article/details/gtbojfindi.html

parse_ini_file("config.ini", true)
来源：http://dali.hnqzz.top/Article/details/gtnswubzcr.html

[U74] PHP：读取环境变量
来源：http://dali.daxiang520.top/Article/details/gtfxkapfdl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.svipenyu.cn/Article/details/gtuhqebqaj.html

[U75] PHP：依赖注入
来源：http://dali.cdnleiting.top/Article/details/gtfawrljix.html

composer require psr/container
来源：http://dali.yueranfly.top/Article/details/gttoggcaqu.html

[U76] PHP：简单路由
来源：http://dali.zhengqikj.top/Article/details/gtthkriuob.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cashguo.top/Article/details/gtaltashpq.html

[U77] PHP：模板渲染
来源：http://dali.xinyue.icu/Article/details/gtuzvjecpm.html

composer require twig/twig
来源：http://dali.smart0.xyz/Article/details/gtgpynpzgo.html

[U78] PHP：单元测试
来源：http://dali.havefunace.top/Article/details/gtvqsvpwmu.html

composer require --dev phpunit/phpunit
来源：http://dali.daria6918.cn/Article/details/gtzojtighz.html

[U79] PHP：静态分析
来源：http://dali.pengpengdd.cyou/Article/details/gticmlrgvp.html

composer require --dev phpstan/phpstan
来源：http://dali.hysaishi.cn/Article/details/gtgkqufvcj.html

[U80] PHP：代码规范修复
来源：http://dali.mhx1999.top/Article/details/gtsqidiyox.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.tian-w.cn/Article/details/gtsszfsbfd.html

[U81] JS：初始化项目
来源：http://dali.316326.xyz/Article/details/gtqkosaagk.html

npm init -y;  npm i express
来源：http://dali.hongshengwenyu.top/Article/details/gtyppkjfys.html

[U82] JS：package.json 脚本
来源：http://dali.wangshuangyany.cn/Article/details/gtcswxzust.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.birdmap.top/Article/details/gtdehoinep.html

[U83] JS：ES Module 导入导出
来源：http://dali.daxiang520.top/Article/details/gtfkxwwxou.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfnocbey.html

[U84] JS：CommonJS 写法
来源：http://dali.yvedp.cn/Article/details/gtnvzuzlhc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.gogol.net.cn/Article/details/gtxpgftuvj.html

[U85] JS：可选链
来源：http://dali.snrcjt.cn/Article/details/gttqpvapkd.html

a?.b?.c
来源：http://dali.fzhhl.top/Article/details/gtjzpfkyds.html

[U86] JS：空值合并
来源：http://dali.cucudq.cn/Article/details/gteyukhbsw.html

a ?? b
来源：http://dali.jianghu66.top/Article/details/gtmanmcwbt.html

[U87] JS：解构默认值
来源：http://dali.yvedp.cn/Article/details/gtoxanmniq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.daxiang520.top/Article/details/gttshtcuvk.html

[U88] JS：对象展开合并
来源：http://dali.zhongyouzk.top/Article/details/gtmsjythvx.html

{ ...a, ...b }
来源：http://dali.aibaodan.cn/Article/details/gttkjkkzbr.html

[U89] JS：数组去重
来源：http://dali.xziqi.cn/Article/details/gtwunwyidb.html

[...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gtjyjlkchl.html

[U90] JS：数字数组排序
来源：http://dali.cashguo.top/Article/details/gtybjlfgdh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtfcmpbqgj.html

[U91] JS：对象键值遍历
来源：http://dali.chenlongwang.top/Article/details/gtiajsjuqb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhengqikj.top/Article/details/gtupgahpiw.html

[U92] JS：深拷贝
来源：http://dali.iojbl.cn/Article/details/gtgrkdphci.html

structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gtvxcwqtxc.html


<!-- 参考信息 -->