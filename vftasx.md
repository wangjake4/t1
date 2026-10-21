代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.sufxvd.cn/Article/details/gtwbodnrfe.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtboqinujy.html

[T06] Kotlin：集合映射
来源：http://dali.gogol.net.cn/Article/details/gtyqdiiznc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ivvv.top/Article/details/gtzhfrivit.html

[T07] Kotlin：集合过滤
来源：http://dali.yongpay.top/Article/details/gtbefsbjsi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ppjwa.cn/Article/details/gtqlwixpto.html

[T08] Kotlin：数据类
来源：http://dali.fengsongda.top/Article/details/gtlwxgqlpx.html

data class User(val name: String, val age: Int)
来源：http://dali.yj202588.top/Article/details/gtpveehilj.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gtufdisqyc.html

fun String.exclaim() = this + "!"
来源：http://dali.wangdashe.top/Article/details/gtqdyjiedu.html

[T10] Kotlin：默认参数
来源：http://dali.sufxvd.cn/Article/details/gtncyynvtt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aizwys.cn/Article/details/gtoqlkyylr.html

[T11] Kotlin：协程
来源：http://dali.zhixingplan.top/Article/details/gtrwnwffax.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yangfankeji.com/Article/details/gtdxdggecn.html

[T12] Kotlin：解构声明
来源：http://dali.havefunace.top/Article/details/gtmgxfncoi.html

val (a, b) = Pair(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtlomwduyr.html

[T13] Kotlin：只读 Map
来源：http://dali.jqgufenzy.top/Article/details/gtbxslwqad.html

val m = mapOf("a" to 1)
来源：http://dali.guowangkeji.top/Article/details/gtlfvstjft.html

[T14] Kotlin：循环
来源：http://dali.zhixingplan.top/Article/details/gtpfqifxih.html

for (i in 1..10) println(i)
来源：http://dali.wangdashe.top/Article/details/gthrpckqgg.html

[T15] Kotlin：接口
来源：http://dali.nanxinkj.top/Article/details/gtnitpednx.html

interface Shape { fun area(): Double }
来源：http://dali.hysaishi.cn/Article/details/gtgazseypt.html

[T16] Swift：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtyelxgyuh.html

print("Hello")
来源：http://dali.andypj.xyz/Article/details/gtqeakjham.html

[T17] Swift：变量与常量
来源：http://dali.hywenlv.cn/Article/details/gtcaxhqlsw.html

var a = 1;  let b = 2
来源：http://dali.ybcxt.top/Article/details/gtcnaubgdi.html

[T18] Swift：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtbkvxoaoa.html

"值: \(b)"
来源：http://dali.jqgfzy.top/Article/details/gtuddxxyba.html

[T19] Swift：可选绑定
来源：http://dali.jiagoushi.top/Article/details/gtxehkknfp.html

if let n = opt { print(n) }
来源：http://dali.pycfn.com/Article/details/gtbijjsylw.html

[T20] Swift：数组操作
来源：http://dali.ydzc1.top/Article/details/gtznbckkuq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gotoacloud.top/Article/details/gtrkuztpho.html

[T21] Swift：遍历
来源：http://dali.jinqigufen.top/Article/details/gtiuxmlmsy.html

for x in a { print(x) }
来源：http://dali.quarkkingdee.top/Article/details/gttyvzgpxa.html

[T22] Swift：字典
来源：http://dali.xuetiantiany.cn/Article/details/gtmkjgapzm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtggcfbvua.html

[T23] Swift：函数
来源：http://dali.yj20258888.top/Article/details/gtybxiltob.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrqyrxtq.html

[T24] Swift：闭包
来源：http://dali.haohaochexian.top/Article/details/gtkicumkcw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gthwgvuzqk.html

[T25] Swift：结构体
来源：http://dali.xylfe.cn/Article/details/gtkgxxqcel.html

struct P { var x: Int }
来源：http://dali.fzhhl.top/Article/details/gtyfahoyyi.html

[T26] Swift：类与重写
来源：http://dali.ivvv.top/Article/details/gtqphqwvwt.html

class A: Base { override func f() {} }
来源：http://dali.zycfv.cn/Article/details/gtzknxzugw.html

[T27] Swift：错误处理
来源：http://dali.nanxuanxn.top/Article/details/gtzipncryi.html

do { try f() } catch { print(error) }
来源：http://dali.andypj.xyz/Article/details/gthpkjxaci.html

[T28] Swift：枚举
来源：http://dali.yj20258888.top/Article/details/gtzqklwwfr.html

enum Color { case red, green }
来源：http://dali.ehwqpu.com/Article/details/gtuolqxiwc.html

[T29] Swift：guard 提前返回
来源：http://dali.aizwys.cn/Article/details/gtkqvsqdji.html

guard let x = opt else { return }
来源：http://dali.hywenlv.cn/Article/details/gtokaedcnn.html

[T30] Swift：协议
来源：http://dali.guowangkeji.top/Article/details/gtndtnnuao.html

protocol Shape { func area() -> Double }
来源：http://dali.zdqjudy.top/Article/details/gtjjklwgqr.html

[T31] Lua：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtqrphndtz.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gthfirobix.html

[T32] Lua：局部变量
来源：http://dali.cucudq.cn/Article/details/gtzjhazqok.html

local a = 1
来源：http://dali.c1oappe.top/Article/details/gtohchmfnz.html

[T33] Lua：表（数组）
来源：http://dali.smart0.xyz/Article/details/gtoiihcbfe.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwzgavbe.html

[T34] Lua：遍历表
来源：http://dali.cucudq.cn/Article/details/gtjmgrqzgv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zdqjudy.top/Article/details/gtfgaviepf.html

[T35] Lua：字典表
来源：http://dali.jyoumei.cn/Article/details/gtajnersyn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenzaomai.com/Article/details/gtjevdckjd.html

[T36] Lua：函数
来源：http://dali.zhongyouzk.top/Article/details/gtokvatdqo.html

function add(a, b) return a + b end
来源：http://dali.guannengcc.top/Article/details/gtghxysjcm.html

[T37] Lua：字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gtpaxrzaqp.html

"a" .. "b"
来源：http://dali.zhengqikj.top/Article/details/gtmagwbzvy.html

[T38] Lua：条件
来源：http://dali.hnqzz.top/Article/details/gthihdmjkl.html

if x > 0 then print("正") end
来源：http://dali.chenzaomai.com/Article/details/gtcvzzegdx.html

[T39] Lua：模式匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyicclktk.html

string.find(s, "%d+")
来源：http://dali.daxiang520.top/Article/details/gtwpfpilju.html

[T40] Lua：元表
来源：http://dali.c1oappe.top/Article/details/gtoqmviohe.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijaenlbv.html

[T41] Perl：Hello World
来源：http://dali.pycfn.com/Article/details/gtcihnarxt.html

print "Hello\n";
来源：http://dali.zhoulong.xyz/Article/details/gthyeiiqtj.html

[T42] Perl：变量类型
来源：http://dali.cucudq.cn/Article/details/gteijjqrsc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jianghu66.top/Article/details/gtkmoyhfnj.html

[T43] Perl：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtmmsysdni.html

"值: $a"
来源：http://dali.dashuyun.cn/Article/details/gtetxpeduz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gtrksyoblq.html

if ($a > 0) { print "正"; }
来源：http://dali.tian-w.cn/Article/details/gtpvswpmbh.html

[T45] Perl：数组遍历
来源：http://dali.jinqigufen.top/Article/details/gtwfozfmqr.html

for my $x (@arr) { print $x; }
来源：http://dali.yuxming.cn/Article/details/gtehjnurts.html

[T46] Perl：哈希操作
来源：http://dali.xuanzx.com/Article/details/gtlblmzyai.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ehwqpu.com/Article/details/gtnniuwesr.html

[T47] Perl：正则捕获
来源：http://dali.fzhhl.top/Article/details/gtxfgvnozf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.iojbl.cn/Article/details/gtlyrsxdhx.html

[T48] Perl：正则替换
来源：http://dali.hysaishi.cn/Article/details/gtmjpwrhnz.html

$s =~ s/old/new/g;
来源：http://dali.xziqi.cn/Article/details/gtvnjxymmv.html

[T49] Perl：函数
来源：http://dali.yuxming.cn/Article/details/gtyuffxabq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtigyiddct.html

[T50] Perl：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtcdefnetr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgfzy.top/Article/details/gtbioxcwsi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.aibaodan.cn/Article/details/gtpvhdappp.html

[T51] Scala：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtmxizyyfz.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gtaxjzmcza.html

[T52] Scala：变量
来源：http://dali.svipenyu.cn/Article/details/gtvtexpdum.html

val a = 1;  var b = 2
来源：http://dali.fengsongda.top/Article/details/gttrdzdcap.html

[T53] Scala：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtelnaxdtp.html

s"值: $b"
来源：http://dali.cqqwz.cn/Article/details/gtwegsbfyw.html

[T54] Scala：集合映射
来源：http://dali.shuidangran.top/Article/details/gtzmprkmtn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hywenlv.cn/Article/details/gtcljtugbx.html

[T55] Scala：集合过滤
来源：http://dali.ydzc1.top/Article/details/gtvsedkxfb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sxryk.cn/Article/details/gtoglpwamh.html

[T56] Scala：样例类
来源：http://dali.zhixingplan.top/Article/details/gtlbbhaywq.html

case class User(name: String, age: Int)
来源：http://dali.meibo888.top/Article/details/gtlbyjhdpk.html

[T57] Scala：模式匹配
来源：http://dali.jiagoushi.top/Article/details/gtshoqxkhz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gtxgpqogqb.html

[T58] Scala：函数定义
来源：http://dali.guannengcc.top/Article/details/gteiwiukvs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxnvmqnr.html

[T59] Scala：循环
来源：http://dali.316326.xyz/Article/details/gtcmyhzcml.html

for (i <- 1 to 10) println(i)
来源：http://dali.cdnleiting.top/Article/details/gtqnfqqgto.html

[T60] Scala：折叠
来源：http://dali.316326.xyz/Article/details/gtyjifzayg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.guannengcc.top/Article/details/gtwvcnrikb.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gttisomrca.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tian-w.cn/Article/details/gtlbdqsttv.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtkwpvlgwd.html

[U01] Py：创建虚拟环境
来源：http://dali.pengpengdd.cyou/Article/details/gtmzmzoade.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hysaishi.cn/Article/details/gtokhbunpi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuetiantiany.cn/Article/details/gtlhyolhex.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtxalhavwl.html

[U03] Py：加载 .env 配置
来源：http://dali.meibo888.top/Article/details/gtixthonso.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cdnleiting.top/Article/details/gttwopswah.html

[U04] Py：变量调试打印
来源：http://dali.aizwys.cn/Article/details/gtmmcubtva.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hfpthk.cn/Article/details/gtajsuwwcz.html

[U05] Py：列表去重且保序
来源：http://dali.yangfankeji.com/Article/details/gtlvjsrbpz.html

list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gtrvqxtdbm.html

[U06] Py：合并两个字典
来源：http://dali.cashguo.top/Article/details/gtmlipuzax.html

{**a, **b}
来源：http://dali.c1oappe.top/Article/details/gtktsfzmov.html

[U07] Py：反转字典键值
来源：http://dali.xziqi.cn/Article/details/gtlzkziluh.html

{v: k for k, v in d.items()}
来源：http://dali.guowangkeji.top/Article/details/gtvzzgixel.html

[U08] Py：展平二维列表
来源：http://dali.xziqi.cn/Article/details/gtjfjcbtuh.html

[y for x in nested for y in x]
来源：http://dali.daria6918.cn/Article/details/gtaamxjpha.html

[U09] Py：字典取最大值的键
来源：http://dali.gaohongyu789.top/Article/details/gtuqdsbnfm.html

max(d, key=d.get)
来源：http://dali.zhiwuduotai.top/Article/details/gtkmjqlims.html

[U10] Py：按值排序字典
来源：http://dali.tianlin.xyz/Article/details/gttvepsmcr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cdnleiting.top/Article/details/gtujauooiq.html

[U11] Py：生成器表达式
来源：http://dali.hnqzz.top/Article/details/gtkkqgdgit.html

(x * 2 for x in arr)
来源：http://dali.vqdsnc.cn/Article/details/gtfhbuueiz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gzhubu.top/Article/details/gtvmotqyhr.html

Counter(arr).most_common(3)
来源：http://dali.tian-w.cn/Article/details/gtiqhqkjpv.html

[U13] Py：固定长度队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gttumlaxgo.html

deque(maxlen=10)
来源：http://dali.wangdashe.top/Article/details/gtlukwugcl.html

[U14] Py：分组收集到列表
来源：http://dali.ydzc1.top/Article/details/gtaoguiyrp.html

defaultdict(list)
来源：http://dali.shzxlz.cn/Article/details/gthtwgsdoa.html

[U15] Py：高精度计时
来源：http://dali.nanxinkj.top/Article/details/gtympiytwd.html

t = time.perf_counter()
来源：http://dali.xuanzx.com/Article/details/gtbargpduj.html

[U16] Py：命令行参数解析
来源：http://dali.havefunace.top/Article/details/gtwjeivpau.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.dashuyun.cn/Article/details/gtsdxequky.html

[U17] Py：初始化日志
来源：http://dali.zhiwuduotai.top/Article/details/gthsqrzlpy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yanxiufei.cn/Article/details/gtcfktzgfb.html

[U18] Py：预编译正则
来源：http://dali.guowangkeji.top/Article/details/gtvnutjqeb.html

pat = re.compile(r"\d+")
来源：http://dali.sysykeji.top/Article/details/gtbpjuozvs.html

[U19] Py：正则替换带回调
来源：http://dali.c1oappe.top/Article/details/gtqxmciveo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvgsgbil.html

[U20] Py：缓存函数结果
来源：http://dali.feifeiyinyue.top/Article/details/gtrarhvhhe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.redwolf501.top/Article/details/gttckoxppe.html

[U21] Py：自定义上下文管理器
来源：http://dali.gogol.net.cn/Article/details/gtzzzqphkn.html

@contextlib.contextmanager
来源：http://dali.guannengcc.top/Article/details/gtomfjjyff.html

[U22] Py：矩阵转置
来源：http://dali.jinqigufen.top/Article/details/gtpvqivkry.html

list(zip(*m))
来源：http://dali.shzxlz.cn/Article/details/gtmznusnsg.html

[U23] Py：分块读取大文件
来源：http://dali.birdmap.top/Article/details/gthknwyrfj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hywenlv.cn/Article/details/gtoojeczmx.html

[U24] Py：路径操作
来源：http://dali.bjfxy.top/Article/details/gtnmkszlgc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuanzhike.top/Article/details/gtpwvlslko.html

[U25] Py：CSV 按字典读
来源：http://dali.chenzaomai.com/Article/details/gtdvigyjln.html

csv.DictReader(f)
来源：http://dali.zhongyouzk.top/Article/details/gtwzckgwbz.html

[U26] Py：并发下载
来源：http://dali.yj20258.top/Article/details/gtlahntkkv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnrvexxx.html

[U27] Py：异步 HTTP
来源：http://dali.aizwys.cn/Article/details/gtyxruxqik.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tian-w.cn/Article/details/gtkcjhcavh.html

[U28] Py：类型别名
来源：http://dali.xuanzx.com/Article/details/gtqmmiasfd.html

UserId = int
来源：http://dali.havefunace.top/Article/details/gturpbcmun.html

[U29] Py：属性校验
来源：http://dali.sxryk.cn/Article/details/gtpqlqiugz.html

@property 与 @x.setter 配合
来源：http://dali.hysaishi.cn/Article/details/gtjgkotkhf.html

[U30] Py：数据类
来源：http://dali.ivvv.top/Article/details/gtadhaigel.html

@dataclass(slots=True)
来源：http://dali.cucudq.cn/Article/details/gtqsoegwbk.html

[U31] Py：单测
来源：http://dali.dashuyun.cn/Article/details/gtnapmipkv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gttasrcwyo.html

[U32] Py：代码格式化
来源：http://dali.dianchejie.cn/Article/details/gtkoideqdc.html

ruff format . && ruff check --fix .
来源：http://dali.wangdashe.top/Article/details/gtwkrtyrum.html

[U33] Py：打包发布
来源：http://dali.pengpengdd.cyou/Article/details/gtvvyalxbg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ydzc1.top/Article/details/gtcqsemjxr.html

[U34] Py：判断编码
来源：http://dali.jinghuilouyu.cn/Article/details/gtrscvmqpk.html

chardet.detect(raw)
来源：http://dali.aizwys.cn/Article/details/gtxosdvnpk.html

[U35] Py：发送邮件
来源：http://dali.hnxiangtu.top/Article/details/gthzsagfcy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cucudq.cn/Article/details/gtvtyonxpr.html

[U36] Py：定时任务
来源：http://dali.jyoumei.cn/Article/details/gtbpcvqxtl.html

schedule.every(10).minutes.do(job)
来源：http://dali.yangfankeji.com/Article/details/gtburvmpgu.html

[U37] Py：读写 Excel
来源：http://dali.jinqigufen.top/Article/details/gtqarjsyix.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jlsjyb.cn/Article/details/gtnjzmzdel.html

[U38] Py：获取脚本所在目录
来源：http://dali.yuxming.cn/Article/details/gtyyjotivy.html

Path(__file__).resolve().parent
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdiljvjsj.html

[U39] Py：判断是否在交互环境
来源：http://dali.yangfankeji.com/Article/details/gtzbcjfmrq.html

sys.stdout.isatty()
来源：http://dali.c1oappe.top/Article/details/gtxjvlgmpu.html

[U40] Py：打印到标准错误
来源：http://dali.zhoulong.xyz/Article/details/gtpesiroes.html

print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gtnmwsusle.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.fzhhl.top/Article/details/gtfdhmjvhp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.guannengcc.top/Article/details/gtyjnieazv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqaunbtp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.andypj.xyz/Article/details/gtjfurkfqz.html

[U43] PHP：声明命名空间
来源：http://dali.smart0.xyz/Article/details/gtkoqujgvv.html

namespace App\Http;
来源：http://dali.kuanghao11.cn/Article/details/gtjfnfuzxj.html

[U44] PHP：开启严格类型
来源：http://dali.yanxiufei.cn/Article/details/gtmkkrqmfo.html

declare(strict_types=1);
来源：http://dali.yongpay.top/Article/details/gtngchtlgr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gogol.net.cn/Article/details/gtdkqxydvs.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gthkearasp.html

[U46] PHP：可空类型
来源：http://dali.jinqigufen.top/Article/details/gterjzbnxy.html

?string $name = null
来源：http://dali.chenzaomai.com/Article/details/gtsrjvjvzh.html

[U47] PHP：联合类型
来源：http://dali.chenzaomai.com/Article/details/gtjggwnpek.html

int|string $id
来源：http://dali.zycfv.cn/Article/details/gtxqsrmnqg.html

[U48] PHP：纯枚举
来源：http://dali.guowangkeji.top/Article/details/gttcqmceap.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumiykznt.html

[U49] PHP：只读属性
来源：http://dali.yongpay.top/Article/details/gteysonjls.html

public readonly string $name
来源：http://dali.zhoulong.xyz/Article/details/gtnxbttijm.html

[U50] PHP：构造器属性提升
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrevtkxev.html

public function __construct(private int $id) {}
来源：http://dali.zdqjudy.top/Article/details/gtsgjkqjwz.html

[U51] PHP：数组解构
来源：http://dali.yuanzhike.top/Article/details/gtcqipiotr.html

[$a, $b] = $arr;
来源：http://dali.smart0.xyz/Article/details/gtcelzsdgp.html

[U52] PHP：箭头函数
来源：http://dali.meibo888.top/Article/details/gtqgqeorqd.html

$double = fn($x) => $x * 2;
来源：http://dali.sufxvd.cn/Article/details/gtgkskbwjq.html

[U53] PHP：空合并运算符
来源：http://dali.tanke756.top/Article/details/gtgbbjlnez.html

$v = $a ?? $b ?? "default";
来源：http://dali.iojbl.cn/Article/details/gtqpilqljw.html

[U54] PHP：空安全调用
来源：http://dali.cheryme.top/Article/details/gtteisarzr.html

$obj?->method()
来源：http://dali.c1oappe.top/Article/details/gtlczoehuf.html

[U55] PHP：match 表达式
来源：http://dali.jlsjyb.cn/Article/details/gtoenxymgh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ehwqpu.com/Article/details/gtkhrnlkti.html

[U56] PHP：命名参数
来源：http://dali.jqgufenzy.top/Article/details/gtyosrcudi.html

f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gtqrmzhgpl.html

[U57] PHP：字符串插值
来源：http://dali.wangdashe.top/Article/details/gtlgetfpmm.html

"值: {$a}"
来源：http://dali.shzxlz.cn/Article/details/gtiesjodhd.html

[U58] PHP：数组三件套
来源：http://dali.gaohongyu789.top/Article/details/gtpjptaezn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.0kj1m.cn/Article/details/gtjbdjrcde.html

[U59] PHP：自定义排序
来源：http://dali.birdmap.top/Article/details/gtaifeqard.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnqzz.top/Article/details/gttkqematd.html

[U60] PHP：JSON 编解码
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnnpsykw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gogol.net.cn/Article/details/gtktopqlgh.html

[U61] PHP：正则
来源：http://dali.0kj1m.cn/Article/details/gtbljibaam.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gttitcjowx.html

[U62] PHP：日期对象
来源：http://dali.nanxuanxn.top/Article/details/gtjutwtpdw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yongpay.top/Article/details/gtnwegdzwc.html

[U63] PHP：文件读写
来源：http://dali.cdnleiting.top/Article/details/gtjtkzqzjk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhengqikj.top/Article/details/gtugjnzbpt.html

[U64] PHP：目录遍历
来源：http://dali.nanxuanxn.top/Article/details/gthjmrzaaf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sweek.top/Article/details/gtjqwyvxyu.html

[U65] PHP：会话
来源：http://dali.zhiwuduotai.top/Article/details/gtjoulltla.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cheryme.top/Article/details/gtqqdohzaa.html

[U66] PHP：设置 Cookie
来源：http://dali.tanke756.top/Article/details/gttskzhaky.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gteodccmox.html

[U67] PHP：处理文件上传
来源：http://dali.vqdsnc.cn/Article/details/gtaxflnxjj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.fengsongda.top/Article/details/gtuahznhly.html

[U68] PHP：PDO 连接
来源：http://dali.chenlongwang.top/Article/details/gtabyhievu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.vqdsnc.cn/Article/details/gtswevlbuo.html

[U69] PHP：PDO 预处理
来源：http://dali.havefunace.top/Article/details/gteiimmvos.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.guowangkeji.top/Article/details/gteclbtvxw.html

[U70] PHP：PDO 事务
来源：http://dali.hongshengwenyu.top/Article/details/gtpxikycvt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tianlin.xyz/Article/details/gtephfmemz.html

[U71] PHP：抛出异常
来源：http://dali.ivvv.top/Article/details/gtgzyikvew.html

throw new RuntimeException("失败", 500);
来源：http://dali.yuanzhike.top/Article/details/gtnebdzchh.html

[U72] PHP：写错误日志
来源：http://dali.hywenlv.cn/Article/details/gtmmksuhdm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.aizwys.cn/Article/details/gtzubydjjz.html

[U73] PHP：读取 ini 配置
来源：http://dali.ybcxt.top/Article/details/gtrpzdlrsu.html

parse_ini_file("config.ini", true)
来源：http://dali.daria6918.cn/Article/details/gtwkyvttle.html

[U74] PHP：读取环境变量
来源：http://dali.daxiang520.top/Article/details/gtboxzxvrt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.tian-w.cn/Article/details/gtysrxovdp.html

[U75] PHP：依赖注入
来源：http://dali.iojbl.cn/Article/details/gtangiobaa.html

composer require psr/container
来源：http://dali.zdqjudy.top/Article/details/gtxsebugiu.html

[U76] PHP：简单路由
来源：http://dali.fzhhl.top/Article/details/gtpefbybth.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.redwolf501.top/Article/details/gtkvqojrni.html

[U77] PHP：模板渲染
来源：http://dali.vqdsnc.cn/Article/details/gtmerarlhl.html

composer require twig/twig
来源：http://dali.bjfxy.top/Article/details/gtmfhbejgj.html

[U78] PHP：单元测试
来源：http://dali.jqgfzy.top/Article/details/gttnxuxesi.html

composer require --dev phpunit/phpunit
来源：http://dali.kuanghao11.cn/Article/details/gtxsggtmps.html

[U79] PHP：静态分析
来源：http://dali.gogol.net.cn/Article/details/gthgiwkpwy.html

composer require --dev phpstan/phpstan
来源：http://dali.shangyingyoupin.top/Article/details/gtjwztfyhq.html

[U80] PHP：代码规范修复
来源：http://dali.chenlongwang.top/Article/details/gtamieyixr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cheryme.top/Article/details/gtzfjwdymq.html

[U81] JS：初始化项目
来源：http://dali.ehwqpu.com/Article/details/gtosajdhje.html

npm init -y;  npm i express
来源：http://dali.aibaodan.cn/Article/details/gtlxajwkyi.html

[U82] JS：package.json 脚本
来源：http://dali.yj20258.top/Article/details/gtuhjhvula.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hysaishi.cn/Article/details/gtfbridvuk.html

[U83] JS：ES Module 导入导出
来源：http://dali.jlsjyb.cn/Article/details/gtlosfeiqi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zdqjudy.top/Article/details/gtqjxhspdo.html

[U84] JS：CommonJS 写法
来源：http://dali.fengsongda.top/Article/details/gtntneqkid.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.havefunace.top/Article/details/gtsnuzkslw.html

[U85] JS：可选链
来源：http://dali.ppjwa.cn/Article/details/gtzeqzvwxm.html

a?.b?.c
来源：http://dali.shzxlz.cn/Article/details/gtvpzlxeqs.html

[U86] JS：空值合并
来源：http://dali.iojbl.cn/Article/details/gtrvddlznh.html

a ?? b
来源：http://dali.meibo888.top/Article/details/gtbtgtrylo.html

[U87] JS：解构默认值
来源：http://dali.xuetiantiany.cn/Article/details/gtehpqyyfx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.smart0.xyz/Article/details/gtescydrug.html

[U88] JS：对象展开合并
来源：http://dali.yonumen.top/Article/details/gtkohzmzex.html

{ ...a, ...b }
来源：http://dali.sxryk.cn/Article/details/gtukyukdsl.html

[U89] JS：数组去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcefskfiu.html

[...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtxavibezc.html

[U90] JS：数字数组排序
来源：http://dali.bjfxy.top/Article/details/gtwxoaxgoq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtexpxdssu.html

[U91] JS：对象键值遍历
来源：http://dali.smart0.xyz/Article/details/gtbdonesxa.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.kuanghao11.cn/Article/details/gtmqhfzoqp.html

[U92] JS：深拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtyjokgpdg.html

structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gtzcrhqyro.html


<!-- 参考信息 -->