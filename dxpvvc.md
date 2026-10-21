代发 wailian999

[T03] Kotlin：字符串模板
来源：http://dali.sxryk.cn/Article/details/gtbdfcmhqy.html

"值: $b"
来源：http://dali.cucudq.cn/Article/details/gtxzhcgtwo.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gtvvwltuia.html

val n: String? = null;  n?.length
来源：http://dali.xinyue.icu/Article/details/gtwbydrkos.html

[T05] Kotlin：when 表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtqqgpbeob.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hnqzz.top/Article/details/gthagqsnua.html

[T06] Kotlin：集合映射
来源：http://dali.quarkkingdee.top/Article/details/gtbfbzxlek.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtonsicpln.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gtlcapstvm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.smart0.xyz/Article/details/gtiyexcznl.html

[T08] Kotlin：数据类
来源：http://dali.jqgfzy.top/Article/details/gtyojidvku.html

data class User(val name: String, val age: Int)
来源：http://dali.guannengcc.top/Article/details/gtxsfaqqoz.html

[T09] Kotlin：扩展函数
来源：http://dali.iojbl.cn/Article/details/gtswfrteqf.html

fun String.exclaim() = this + "!"
来源：http://dali.smart0.xyz/Article/details/gtaigoiusx.html

[T10] Kotlin：默认参数
来源：http://dali.xuanzx.com/Article/details/gtotojjubd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhiwuduotai.top/Article/details/gtzcipxnxr.html

[T11] Kotlin：协程
来源：http://dali.chenlongwang.top/Article/details/gtckbpiswv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.feifeiyinyue.top/Article/details/gtvjvdhkua.html

[T12] Kotlin：解构声明
来源：http://dali.nanxinkj.top/Article/details/gtzdurzisz.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj20258.top/Article/details/gtwdcxcfyf.html

[T13] Kotlin：只读 Map
来源：http://dali.quarkkingdee.top/Article/details/gtkcztamab.html

val m = mapOf("a" to 1)
来源：http://dali.yvedp.cn/Article/details/gtykwmhrie.html

[T14] Kotlin：循环
来源：http://dali.sxryk.cn/Article/details/gtmodshgli.html

for (i in 1..10) println(i)
来源：http://dali.yonumen.top/Article/details/gtbylybpve.html

[T15] Kotlin：接口
来源：http://dali.zhongyouzk.top/Article/details/gtofjohxan.html

interface Shape { fun area(): Double }
来源：http://dali.hysaishi.cn/Article/details/gtjxrrrenb.html

[T16] Swift：Hello World
来源：http://dali.sysykeji.top/Article/details/gtrflxcmqk.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtfmxdwcyv.html

[T17] Swift：变量与常量
来源：http://dali.iojbl.cn/Article/details/gtpbnfobig.html

var a = 1;  let b = 2
来源：http://dali.yj20258.top/Article/details/gtcdhqtqiw.html

[T18] Swift：字符串插值
来源：http://dali.yongpay.top/Article/details/gtldpzplxa.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gtgnbuykgz.html

[T19] Swift：可选绑定
来源：http://dali.zhixingplan.top/Article/details/gttnawdemw.html

if let n = opt { print(n) }
来源：http://dali.xuanzx.com/Article/details/gtyqgfmdpp.html

[T20] Swift：数组操作
来源：http://dali.zhengqikj.top/Article/details/gtftovyjqx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.tianlin.xyz/Article/details/gtnollybty.html

[T21] Swift：遍历
来源：http://dali.yj202588.top/Article/details/gtphqcnqls.html

for x in a { print(x) }
来源：http://dali.gogol.net.cn/Article/details/gtplnxpjhm.html

[T22] Swift：字典
来源：http://dali.tianlin.xyz/Article/details/gtqmobnodd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtdnenrsst.html

[T23] Swift：函数
来源：http://dali.c1oappe.top/Article/details/gtqphgzgmt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cashguo.top/Article/details/gtfiervwui.html

[T24] Swift：闭包
来源：http://dali.svipenyu.cn/Article/details/gtfxrlkaop.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.meibo888.top/Article/details/gtcpabqoql.html

[T25] Swift：结构体
来源：http://dali.tanke756.top/Article/details/gtobpwvnss.html

struct P { var x: Int }
来源：http://dali.jinqigfzy.top/Article/details/gthatmvoix.html

[T26] Swift：类与重写
来源：http://dali.jiagoushi.top/Article/details/gtcuakkdcc.html

class A: Base { override func f() {} }
来源：http://dali.daxiang520.top/Article/details/gtsdjisvtg.html

[T27] Swift：错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gtkemszepd.html

do { try f() } catch { print(error) }
来源：http://dali.0kj1m.cn/Article/details/gtprouosyg.html

[T28] Swift：枚举
来源：http://dali.fzhhl.top/Article/details/gtgermywla.html

enum Color { case red, green }
来源：http://dali.snrcjt.cn/Article/details/gtvkgqxfml.html

[T29] Swift：guard 提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gttovxwxpx.html

guard let x = opt else { return }
来源：http://dali.aizwys.cn/Article/details/gtweyrfaxc.html

[T30] Swift：协议
来源：http://dali.vqdsnc.cn/Article/details/gthozybfyk.html

protocol Shape { func area() -> Double }
来源：http://dali.chenlongwang.top/Article/details/gtrngrqvyz.html

[T31] Lua：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtnopmudyh.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtpalahkvz.html

[T32] Lua：局部变量
来源：http://dali.wangdashe.top/Article/details/gtgopgoyok.html

local a = 1
来源：http://dali.ehwqpu.com/Article/details/gteszyahyu.html

[T33] Lua：表（数组）
来源：http://dali.bjfxy.top/Article/details/gtgtmimhci.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkofbkkm.html

[T34] Lua：遍历表
来源：http://dali.vqdsnc.cn/Article/details/gtuyxuaquk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhiwuduotai.top/Article/details/gtgnpugxfx.html

[T35] Lua：字典表
来源：http://dali.c1oappe.top/Article/details/gtalrquhma.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tian-w.cn/Article/details/gtnjqrhmmd.html

[T36] Lua：函数
来源：http://dali.jyoumei.cn/Article/details/gtjdihkfvk.html

function add(a, b) return a + b end
来源：http://dali.hammf.cn/Article/details/gteiutgjgz.html

[T37] Lua：字符串拼接
来源：http://dali.daxiang520.top/Article/details/gtqlqcfnou.html

"a" .. "b"
来源：http://dali.ivvv.top/Article/details/gtpsfxwgyc.html

[T38] Lua：条件
来源：http://dali.hfpthk.cn/Article/details/gtrtinddpw.html

if x > 0 then print("正") end
来源：http://dali.wangdashe.top/Article/details/gtxufdmqxx.html

[T39] Lua：模式匹配
来源：http://dali.yj202588.top/Article/details/gtxbsjvpkj.html

string.find(s, "%d+")
来源：http://dali.shzxlz.cn/Article/details/gttgrdcmrx.html

[T40] Lua：元表
来源：http://dali.gaohongyu789.top/Article/details/gtkretlrdd.html

setmetatable({}, { __index = base })
来源：http://dali.hnxiangtu.top/Article/details/gtovluioez.html

[T41] Perl：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtesomapuv.html

print "Hello\n";
来源：http://dali.cucudq.cn/Article/details/gtnbmnbptm.html

[T42] Perl：变量类型
来源：http://dali.aibaodan.cn/Article/details/gtjkrfrutt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj20258888.top/Article/details/gttbxchrnp.html

[T43] Perl：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtknxrwwin.html

"值: $a"
来源：http://dali.xziqi.cn/Article/details/gtpzclfqdh.html

[T44] Perl：条件
来源：http://dali.yangfankeji.com/Article/details/gtbnadjlps.html

if ($a > 0) { print "正"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzikmlzot.html

[T45] Perl：数组遍历
来源：http://dali.xziqi.cn/Article/details/gtoowlldzb.html

for my $x (@arr) { print $x; }
来源：http://dali.bjfxy.top/Article/details/gtmkzdqlkt.html

[T46] Perl：哈希操作
来源：http://dali.jlsjyb.cn/Article/details/gtoizoywvy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.0kj1m.cn/Article/details/gtfkisfpjf.html

[T47] Perl：正则捕获
来源：http://dali.gogol.net.cn/Article/details/gtantndscc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jiagoushi.top/Article/details/gtsaecmobu.html

[T48] Perl：正则替换
来源：http://dali.gotoacloud.top/Article/details/gtosiqoulo.html

$s =~ s/old/new/g;
来源：http://dali.c1oappe.top/Article/details/gtjvoyfbwz.html

[T49] Perl：函数
来源：http://dali.cucudq.cn/Article/details/gtczcazejl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gthmgzmnvt.html

[T50] Perl：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtghmcqgoh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.316326.xyz/Article/details/gtbogzoqcx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sweek.top/Article/details/gtxderlwxz.html

[T51] Scala：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtldaooaev.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtabidwyom.html

[T52] Scala：变量
来源：http://dali.jqgfzy.top/Article/details/gtdhdfdwxc.html

val a = 1;  var b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsoalriy.html

[T53] Scala：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtilbcpnru.html

s"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gtejiuazgn.html

[T54] Scala：集合映射
来源：http://dali.jyoumei.cn/Article/details/gtnggsgout.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.bjfxy.top/Article/details/gtasugwpdq.html

[T55] Scala：集合过滤
来源：http://dali.yj20258.top/Article/details/gtcrpfrgzp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yueranfly.top/Article/details/gtmlnxdjqs.html

[T56] Scala：样例类
来源：http://dali.nanxuanxn.top/Article/details/gtgzjyavam.html

case class User(name: String, age: Int)
来源：http://dali.yongpay.top/Article/details/gtwrikxrfx.html

[T57] Scala：模式匹配
来源：http://dali.quarkkingdee.top/Article/details/gtbywhwntp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tianlin.xyz/Article/details/gtebapcqlg.html

[T58] Scala：函数定义
来源：http://dali.dashuyun.cn/Article/details/gtdwqklseu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gaohongyu789.top/Article/details/gtyrmkxrwv.html

[T59] Scala：循环
来源：http://dali.jqgufenzy.top/Article/details/gtvtsfmlxc.html

for (i <- 1 to 10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gtizvhebzm.html

[T60] Scala：折叠
来源：http://dali.hnxiangtu.top/Article/details/gtltckyklz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jyoumei.cn/Article/details/gtwovmhjni.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtebmohuin.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhoulong.xyz/Article/details/gtdkuixivy.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtmtjbowts.html

[U01] Py：创建虚拟环境
来源：http://dali.yj20258.top/Article/details/gttczapnqp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shuidangran.top/Article/details/gtyxnxmhin.html

[U02] Py：导出 / 安装依赖
来源：http://dali.wangshuangyany.cn/Article/details/gtzdkkinmh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daria6918.cn/Article/details/gtseckrkxq.html

[U03] Py：加载 .env 配置
来源：http://dali.iojbl.cn/Article/details/gtpiusbequ.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj20258888.top/Article/details/gtbbrbregp.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsmckjro.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hongshengwenyu.top/Article/details/gtqwvablcr.html

[U05] Py：列表去重且保序
来源：http://dali.smart0.xyz/Article/details/gtbahjqcya.html

list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gttmnuowto.html

[U06] Py：合并两个字典
来源：http://dali.zhengqikj.top/Article/details/gtbjqckpmo.html

{**a, **b}
来源：http://dali.daxiang520.top/Article/details/gtxsduknrk.html

[U07] Py：反转字典键值
来源：http://dali.9152youxi.cn/Article/details/gtppbvjrti.html

{v: k for k, v in d.items()}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkbbnovy.html

[U08] Py：展平二维列表
来源：http://dali.yonumen.top/Article/details/gtyqdjwtsf.html

[y for x in nested for y in x]
来源：http://dali.yj20258888.top/Article/details/gtvkjmoivk.html

[U09] Py：字典取最大值的键
来源：http://dali.shangyingyoupin.top/Article/details/gtuvsyqlod.html

max(d, key=d.get)
来源：http://dali.yangfankeji.com/Article/details/gtzaqnnurk.html

[U10] Py：按值排序字典
来源：http://dali.zhixingplan.top/Article/details/gtmnyhstdw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gotoacloud.top/Article/details/gtgvmjcruw.html

[U11] Py：生成器表达式
来源：http://dali.birdmap.top/Article/details/gtaoqxkdsg.html

(x * 2 for x in arr)
来源：http://dali.quarkkingdee.top/Article/details/gtcfyqarre.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.daria6918.cn/Article/details/gtubasduhd.html

Counter(arr).most_common(3)
来源：http://dali.yj20258888.top/Article/details/gtkwxyqcmj.html

[U13] Py：固定长度队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaczzvtth.html

deque(maxlen=10)
来源：http://dali.zhengqikj.top/Article/details/gthnkruhue.html

[U14] Py：分组收集到列表
来源：http://dali.cqqwz.cn/Article/details/gtflszhsjt.html

defaultdict(list)
来源：http://dali.snrcjt.cn/Article/details/gtddlhicwo.html

[U15] Py：高精度计时
来源：http://dali.ppjwa.cn/Article/details/gtwjhllirw.html

t = time.perf_counter()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrshzkazy.html

[U16] Py：命令行参数解析
来源：http://dali.sufxvd.cn/Article/details/gtlwiqllvl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.iojbl.cn/Article/details/gtdtutiiuu.html

[U17] Py：初始化日志
来源：http://dali.yueranfly.top/Article/details/gtpybfgyhd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yj20258.top/Article/details/gtjahgshbv.html

[U18] Py：预编译正则
来源：http://dali.gaohongyu789.top/Article/details/gtmhjuahxb.html

pat = re.compile(r"\d+")
来源：http://dali.mhx1999.top/Article/details/gtnxcjkvdg.html

[U19] Py：正则替换带回调
来源：http://dali.sweek.top/Article/details/gtegwofujx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.havefunace.top/Article/details/gtgkktblic.html

[U20] Py：缓存函数结果
来源：http://dali.sweek.top/Article/details/gtbpltymkn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yonumen.top/Article/details/gtjwfdvfpw.html

[U21] Py：自定义上下文管理器
来源：http://dali.cucudq.cn/Article/details/gtlvdklxte.html

@contextlib.contextmanager
来源：http://dali.shzxlz.cn/Article/details/gtrkcwekgf.html

[U22] Py：矩阵转置
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqjgkena.html

list(zip(*m))
来源：http://dali.zhengqikj.top/Article/details/gthefovicz.html

[U23] Py：分块读取大文件
来源：http://dali.yvedp.cn/Article/details/gtuffmxagl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gogol.net.cn/Article/details/gtmxvppmkm.html

[U24] Py：路径操作
来源：http://dali.hywenlv.cn/Article/details/gtoybzkiwz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gtuvxumind.html

[U25] Py：CSV 按字典读
来源：http://dali.quarkkingdee.top/Article/details/gtlqmhpzyp.html

csv.DictReader(f)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcxutmvd.html

[U26] Py：并发下载
来源：http://dali.zhengqikj.top/Article/details/gtwyvarsyh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sysykeji.top/Article/details/gtqzeihpyr.html

[U27] Py：异步 HTTP
来源：http://dali.sweek.top/Article/details/gtpylziimj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.birdmap.top/Article/details/gtkmzaxfcs.html

[U28] Py：类型别名
来源：http://dali.cheryme.top/Article/details/gtaunsgjli.html

UserId = int
来源：http://dali.wangshuangyany.cn/Article/details/gtnevpohys.html

[U29] Py：属性校验
来源：http://dali.hongshengwenyu.top/Article/details/gtaltxokmk.html

@property 与 @x.setter 配合
来源：http://dali.yj20258.top/Article/details/gtbtztvhwg.html

[U30] Py：数据类
来源：http://dali.0kj1m.cn/Article/details/gtcqdsigua.html

@dataclass(slots=True)
来源：http://dali.iojbl.cn/Article/details/gtbsedfwwh.html

[U31] Py：单测
来源：http://dali.svipenyu.cn/Article/details/gtjdyoyohs.html

python -m pytest -q
来源：http://dali.fengsongda.top/Article/details/gtzznphdgy.html

[U32] Py：代码格式化
来源：http://dali.shuidangran.top/Article/details/gthgyayjqr.html

ruff format . && ruff check --fix .
来源：http://dali.nanxuanxn.top/Article/details/gtivefbbvi.html

[U33] Py：打包发布
来源：http://dali.hammf.cn/Article/details/gtddhfrpwa.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj20258.top/Article/details/gteumxwmqx.html

[U34] Py：判断编码
来源：http://dali.0kj1m.cn/Article/details/gtmncbjfnc.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gtvwnreqmi.html

[U35] Py：发送邮件
来源：http://dali.ydzc1.top/Article/details/gtodcfuboc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yonumen.top/Article/details/gtjaumhsyf.html

[U36] Py：定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokwrehds.html

schedule.every(10).minutes.do(job)
来源：http://dali.xylfe.cn/Article/details/gtsnbmdgdl.html

[U37] Py：读写 Excel
来源：http://dali.zycfv.cn/Article/details/gtxnafxrum.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.daxiang520.top/Article/details/gtdbjxjpei.html

[U38] Py：获取脚本所在目录
来源：http://dali.yongpay.top/Article/details/gtiuonfuwn.html

Path(__file__).resolve().parent
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzeyyfst.html

[U39] Py：判断是否在交互环境
来源：http://dali.hysaishi.cn/Article/details/gtsqiizxny.html

sys.stdout.isatty()
来源：http://dali.316326.xyz/Article/details/gtfbdiityb.html

[U40] Py：打印到标准错误
来源：http://dali.zhixingplan.top/Article/details/gtlaryrsmq.html

print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gtuiumwiwq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenzaomai.com/Article/details/gtkxllsouo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zdqjudy.top/Article/details/gtjazmlgru.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hongshengwenyu.top/Article/details/gtijktgszm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.pycfn.com/Article/details/gtgsqzfpoe.html

[U43] PHP：声明命名空间
来源：http://dali.zycfv.cn/Article/details/gthxoysmll.html

namespace App\Http;
来源：http://dali.ehwqpu.com/Article/details/gtxvamahkw.html

[U44] PHP：开启严格类型
来源：http://dali.hywenlv.cn/Article/details/gtmppehlmt.html

declare(strict_types=1);
来源：http://dali.jqgufenzy.top/Article/details/gtzqpckjhj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shangyingyoupin.top/Article/details/gttbdqgdah.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gteykroazv.html

[U46] PHP：可空类型
来源：http://dali.yueranfly.top/Article/details/gtnseqckof.html

?string $name = null
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcobyynk.html

[U47] PHP：联合类型
来源：http://dali.jqgufenzy.top/Article/details/gtkgfnjduc.html

int|string $id
来源：http://dali.fengsongda.top/Article/details/gtnromjmqt.html

[U48] PHP：纯枚举
来源：http://dali.quarkkingdee.top/Article/details/gtrrvvytok.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ivvv.top/Article/details/gtiwyzkjuk.html

[U49] PHP：只读属性
来源：http://dali.hnqzz.top/Article/details/gtrjzqnvmi.html

public readonly string $name
来源：http://dali.chenzaomai.com/Article/details/gthmpgrvdm.html

[U50] PHP：构造器属性提升
来源：http://dali.yuanzhike.top/Article/details/gtnmtpoufl.html

public function __construct(private int $id) {}
来源：http://dali.daxiang520.top/Article/details/gtvqzdlfky.html

[U51] PHP：数组解构
来源：http://dali.sxryk.cn/Article/details/gtfswncptl.html

[$a, $b] = $arr;
来源：http://dali.ydzc1.top/Article/details/gtdqkavrif.html

[U52] PHP：箭头函数
来源：http://dali.xinyue.icu/Article/details/gtlgypwsdt.html

$double = fn($x) => $x * 2;
来源：http://dali.feifeiyinyue.top/Article/details/gtcwqyzgns.html

[U53] PHP：空合并运算符
来源：http://dali.smart0.xyz/Article/details/gtkkjzeuvt.html

$v = $a ?? $b ?? "default";
来源：http://dali.jlsjyb.cn/Article/details/gtolduorvq.html

[U54] PHP：空安全调用
来源：http://dali.xylfe.cn/Article/details/gtstseylzz.html

$obj?->method()
来源：http://dali.gaohongyu789.top/Article/details/gtqqwxcptg.html

[U55] PHP：match 表达式
来源：http://dali.jqgfzy.top/Article/details/gtmcbkwndm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.tianlin.xyz/Article/details/gtqociqabe.html

[U56] PHP：命名参数
来源：http://dali.jlsjyb.cn/Article/details/gtodrvdwaf.html

f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gtcfrhyhrb.html

[U57] PHP：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtlyasasgq.html

"值: {$a}"
来源：http://dali.zycfv.cn/Article/details/gthvtsglwa.html

[U58] PHP：数组三件套
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkisxkopb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.fzhhl.top/Article/details/gtmkvpebdf.html

[U59] PHP：自定义排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqvkwdud.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gtoimagjfn.html

[U60] PHP：JSON 编解码
来源：http://dali.gotoacloud.top/Article/details/gtfylvpnjp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtbvlejrrq.html

[U61] PHP：正则
来源：http://dali.sufxvd.cn/Article/details/gtadnaczrk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtlaqjuwse.html

[U62] PHP：日期对象
来源：http://dali.nwbrower.top/Article/details/gtlcwwmunl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.sxryk.cn/Article/details/gtwwvmlmyv.html

[U63] PHP：文件读写
来源：http://dali.vqdsnc.cn/Article/details/gtheceysgv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.snrcjt.cn/Article/details/gtcemdwhoo.html

[U64] PHP：目录遍历
来源：http://dali.gogol.net.cn/Article/details/gticccocgt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sysykeji.top/Article/details/gtzedolowb.html

[U65] PHP：会话
来源：http://dali.chenjidiqi.icu/Article/details/gtwgkbamzg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvmtyfro.html

[U66] PHP：设置 Cookie
来源：http://dali.fzhhl.top/Article/details/gtyztnlmri.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.havefunace.top/Article/details/gtcgfdtilr.html

[U67] PHP：处理文件上传
来源：http://dali.jlsjyb.cn/Article/details/gteibaboaw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.guowangkeji.top/Article/details/gtkrtitgih.html

[U68] PHP：PDO 连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxccdmsdd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hnxiangtu.top/Article/details/gtbdpxxycl.html

[U69] PHP：PDO 预处理
来源：http://dali.vqdsnc.cn/Article/details/gtrppyxkfs.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hnxiangtu.top/Article/details/gtcqajfjap.html

[U70] PHP：PDO 事务
来源：http://dali.hfpthk.cn/Article/details/gtukbxcwzz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hnxiangtu.top/Article/details/gtuzmahdpz.html

[U71] PHP：抛出异常
来源：http://dali.cdnleiting.top/Article/details/gtjyfqmvoe.html

throw new RuntimeException("失败", 500);
来源：http://dali.hysaishi.cn/Article/details/gtwncvqlvv.html

[U72] PHP：写错误日志
来源：http://dali.feifeiyinyue.top/Article/details/gtbtzxjnni.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cashguo.top/Article/details/gtvneiwipt.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhongyouzk.top/Article/details/gtfwazhyac.html

parse_ini_file("config.ini", true)
来源：http://dali.nanxuanxn.top/Article/details/gtaajbhqif.html

[U74] PHP：读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gtonoktlue.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhengqikj.top/Article/details/gtrvwclpnq.html

[U75] PHP：依赖注入
来源：http://dali.hammf.cn/Article/details/gtemjlgmsj.html

composer require psr/container
来源：http://dali.fengsongda.top/Article/details/gtncrmcuon.html

[U76] PHP：简单路由
来源：http://dali.shuidangran.top/Article/details/gtceoswbcp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yvedp.cn/Article/details/gtbbewjrtl.html

[U77] PHP：模板渲染
来源：http://dali.gzhubu.top/Article/details/gtyjnobqbc.html

composer require twig/twig
来源：http://dali.xuanzx.com/Article/details/gtdiyrjqsj.html

[U78] PHP：单元测试
来源：http://dali.tanke756.top/Article/details/gtsjcxhknu.html

composer require --dev phpunit/phpunit
来源：http://dali.xinyue.icu/Article/details/gtviicvmbq.html

[U79] PHP：静态分析
来源：http://dali.yuxming.cn/Article/details/gtduxsohmd.html

composer require --dev phpstan/phpstan
来源：http://dali.kuanghao11.cn/Article/details/gtlhtvkvvo.html

[U80] PHP：代码规范修复
来源：http://dali.snrcjt.cn/Article/details/gtxlvxxrgx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.wangshuangyany.cn/Article/details/gtuwddjbbx.html

[U81] JS：初始化项目
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsdckaex.html

npm init -y;  npm i express
来源：http://dali.jinghuilouyu.cn/Article/details/gtgyvjfllq.html

[U82] JS：package.json 脚本
来源：http://dali.yj20258.top/Article/details/gtthpefevv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.tianlin.xyz/Article/details/gtztfdizau.html

[U83] JS：ES Module 导入导出
来源：http://dali.sysykeji.top/Article/details/gtbhnycvlp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ivvv.top/Article/details/gtkscqgpyk.html

[U84] JS：CommonJS 写法
来源：http://dali.wangshuangyany.cn/Article/details/gtjsccgqmk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yanxiufei.cn/Article/details/gtaotusbzj.html

[U85] JS：可选链
来源：http://dali.jlsjyb.cn/Article/details/gtxjaehyjp.html

a?.b?.c
来源：http://dali.meibo888.top/Article/details/gtfapghmlz.html

[U86] JS：空值合并
来源：http://dali.ybcxt.top/Article/details/gtqydjitwa.html

a ?? b
来源：http://dali.meibo888.top/Article/details/gtuvecjahh.html

[U87] JS：解构默认值
来源：http://dali.nanxuanxn.top/Article/details/gtupgfedmb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hywenlv.cn/Article/details/gttzkchijo.html

[U88] JS：对象展开合并
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakwooxby.html

{ ...a, ...b }
来源：http://dali.hnxiangtu.top/Article/details/gttseogkqv.html

[U89] JS：数组去重
来源：http://dali.chenjidiqi.icu/Article/details/gteattejzt.html

[...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtglruzcrt.html

[U90] JS：数字数组排序
来源：http://dali.nwbrower.top/Article/details/gtqgqvhwgt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gtmqrnzewb.html


<!-- 参考信息 -->