代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.hnqzz.top/Article/details/gt2pcmepedi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgufenzy.top/Article/details/gt2zlufibbf.html

[T06] Kotlin：集合映射
来源：http://dali.tanke756.top/Article/details/gt2uidoffqw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2jmcizoik.html

[T07] Kotlin：集合过滤
来源：http://dali.ybcxt.top/Article/details/gt2ruofszhb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yvedp.cn/Article/details/gt2tfwhlejo.html

[T08] Kotlin：数据类
来源：http://dali.guannengcc.top/Article/details/gt2lwdxcaiq.html

data class User(val name: String, val age: Int)
来源：http://dali.yuxming.cn/Article/details/gt2rsllsrbq.html

[T09] Kotlin：扩展函数
来源：http://dali.yuanzhike.top/Article/details/gt2bmyltlmn.html

fun String.exclaim() = this + "!"
来源：http://dali.xuanzx.com/Article/details/gt2pmlqcgyx.html

[T10] Kotlin：默认参数
来源：http://dali.jianghu66.top/Article/details/gt2aexfooxn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yueranfly.top/Article/details/gt2chtbdeci.html

[T11] Kotlin：协程
来源：http://dali.chenjidiqi.icu/Article/details/gt2fgykohbu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenlongwang.top/Article/details/gt2pftsutww.html

[T12] Kotlin：解构声明
来源：http://dali.meibo888.top/Article/details/gt2tnkqzbuw.html

val (a, b) = Pair(1, 2)
来源：http://dali.daria6918.cn/Article/details/gt2lvquhfcg.html

[T13] Kotlin：只读 Map
来源：http://dali.tian-w.cn/Article/details/gt2qngibbxa.html

val m = mapOf("a" to 1)
来源：http://dali.ehwqpu.com/Article/details/gt2okttariw.html

[T14] Kotlin：循环
来源：http://dali.gotoacloud.top/Article/details/gt2owiuemnp.html

for (i in 1..10) println(i)
来源：http://dali.birdmap.top/Article/details/gt2yyoxwrvu.html

[T15] Kotlin：接口
来源：http://dali.feifeiyinyue.top/Article/details/gt2mlrnemwr.html

interface Shape { fun area(): Double }
来源：http://dali.jyoumei.cn/Article/details/gt2umlnfnyf.html

[T16] Swift：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2ekafvwhx.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gt2herdgzqm.html

[T17] Swift：变量与常量
来源：http://dali.fengsongda.top/Article/details/gt2njcpqlpk.html

var a = 1;  let b = 2
来源：http://dali.vqdsnc.cn/Article/details/gt2shkxupky.html

[T18] Swift：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gt2hgpajnir.html

"值: \(b)"
来源：http://dali.kuanghao11.cn/Article/details/gt2gjscuhtz.html

[T19] Swift：可选绑定
来源：http://dali.meibo888.top/Article/details/gt2zpebwrir.html

if let n = opt { print(n) }
来源：http://dali.bjfxy.top/Article/details/gt2nbpbgakw.html

[T20] Swift：数组操作
来源：http://dali.jianghu66.top/Article/details/gt2yvrqkork.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ppjwa.cn/Article/details/gt2nigrhkfa.html

[T21] Swift：遍历
来源：http://dali.xziqi.cn/Article/details/gt2necrbasj.html

for x in a { print(x) }
来源：http://dali.mhx1999.top/Article/details/gt2ropoucqk.html

[T22] Swift：字典
来源：http://dali.nanxinkj.top/Article/details/gt2eboxaaqu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tian-w.cn/Article/details/gt2ettlmhje.html

[T23] Swift：函数
来源：http://dali.iojbl.cn/Article/details/gt2rzikdupd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jqgfzy.top/Article/details/gt2snuxjlmy.html

[T24] Swift：闭包
来源：http://dali.gaohongyu789.top/Article/details/gt2ozhcgwch.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yongpay.top/Article/details/gt2blrnefly.html

[T25] Swift：结构体
来源：http://dali.xziqi.cn/Article/details/gt2jjmjjong.html

struct P { var x: Int }
来源：http://dali.yj202588.top/Article/details/gt2qecvuzgp.html

[T26] Swift：类与重写
来源：http://dali.snrcjt.cn/Article/details/gt2whljrczq.html

class A: Base { override func f() {} }
来源：http://dali.gaohongyu789.top/Article/details/gt2cmjnfvck.html

[T27] Swift：错误处理
来源：http://dali.cheryme.top/Article/details/gt2pydufwlp.html

do { try f() } catch { print(error) }
来源：http://dali.haohaochexian.top/Article/details/gt2guisjpfd.html

[T28] Swift：枚举
来源：http://dali.yonumen.top/Article/details/gt2ljlvkdpq.html

enum Color { case red, green }
来源：http://dali.xylfe.cn/Article/details/gt2xbkbmjov.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxinkj.top/Article/details/gt2ttjbjzkl.html

guard let x = opt else { return }
来源：http://dali.haohaochexian.top/Article/details/gt2rrpgystp.html

[T30] Swift：协议
来源：http://dali.xylfe.cn/Article/details/gt2vbktaclv.html

protocol Shape { func area() -> Double }
来源：http://dali.aizwys.cn/Article/details/gt2igladtuz.html

[T31] Lua：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2lwyrumod.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gt2brbslwjb.html

[T32] Lua：局部变量
来源：http://dali.hfpthk.cn/Article/details/gt2cycnnwja.html

local a = 1
来源：http://dali.jinqigfzy.top/Article/details/gt2imadgcwp.html

[T33] Lua：表（数组）
来源：http://dali.jlsjyb.cn/Article/details/gt2rihprqeq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daxiang520.top/Article/details/gt2oktnhwju.html

[T34] Lua：遍历表
来源：http://dali.birdmap.top/Article/details/gt2jljvyawh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxuanxn.top/Article/details/gt2xghkwbwj.html

[T35] Lua：字典表
来源：http://dali.ppjwa.cn/Article/details/gt2qwdgqlcd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.bjfxy.top/Article/details/gt2tuyrojqk.html

[T36] Lua：函数
来源：http://dali.ivvv.top/Article/details/gt2gmwbbuau.html

function add(a, b) return a + b end
来源：http://dali.9152youxi.cn/Article/details/gt2xzeazrpf.html

[T37] Lua：字符串拼接
来源：http://dali.shuidangran.top/Article/details/gt2qmziwbax.html

"a" .. "b"
来源：http://dali.ybcxt.top/Article/details/gt2kvkwftwg.html

[T38] Lua：条件
来源：http://dali.hywenlv.cn/Article/details/gt2pyvamtvh.html

if x > 0 then print("正") end
来源：http://dali.pycfn.com/Article/details/gt2miyiiqki.html

[T39] Lua：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gt2hsjoefet.html

string.find(s, "%d+")
来源：http://dali.hfpthk.cn/Article/details/gt2rcsbygzo.html

[T40] Lua：元表
来源：http://dali.yuanzhike.top/Article/details/gt2rnloeieb.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbqczegh.html

[T41] Perl：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2clsykbmf.html

print "Hello\n";
来源：http://dali.zhongyouzk.top/Article/details/gt2mwgisduy.html

[T42] Perl：变量类型
来源：http://dali.smart0.xyz/Article/details/gt2lrzkmdtb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nwbrower.top/Article/details/gt2dzulcxvm.html

[T43] Perl：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gt2bkzhgjdg.html

"值: $a"
来源：http://dali.tian-w.cn/Article/details/gt2aassbpyl.html

[T44] Perl：条件
来源：http://dali.chenlongwang.top/Article/details/gt2zbpfimqn.html

if ($a > 0) { print "正"; }
来源：http://dali.jianghu66.top/Article/details/gt2iqpoxoyw.html

[T45] Perl：数组遍历
来源：http://dali.ivvv.top/Article/details/gt2milrpvnb.html

for my $x (@arr) { print $x; }
来源：http://dali.daxiang520.top/Article/details/gt2ekuzcorq.html

[T46] Perl：哈希操作
来源：http://dali.havefunace.top/Article/details/gt2rgvddqrv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jqgfzy.top/Article/details/gt2twvoznva.html

[T47] Perl：正则捕获
来源：http://dali.jqgufenzy.top/Article/details/gt2fkimjyvb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.0kj1m.cn/Article/details/gt2rtekxchg.html

[T48] Perl：正则替换
来源：http://dali.chenzaomai.com/Article/details/gt2qziuahyi.html

$s =~ s/old/new/g;
来源：http://dali.c1oappe.top/Article/details/gt2ysycfngm.html

[T49] Perl：函数
来源：http://dali.cheryme.top/Article/details/gt2sswwbdti.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gt2uocdvjrb.html

[T50] Perl：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gt2oxetnbhs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yanxiufei.cn/Article/details/gt2iqtwwfik.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.daria6918.cn/Article/details/gt2ycyqyusc.html

[T51] Scala：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2yqtqqauq.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gt2xdzocakw.html

[T52] Scala：变量
来源：http://dali.jlsjyb.cn/Article/details/gt2ywfgpvtj.html

val a = 1;  var b = 2
来源：http://dali.yueranfly.top/Article/details/gt2oslxnbto.html

[T53] Scala：字符串插值
来源：http://dali.cheryme.top/Article/details/gt2ggmjasld.html

s"值: $b"
来源：http://dali.havefunace.top/Article/details/gt2wqrfbxzi.html

[T54] Scala：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gt2vwvwyfor.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yueranfly.top/Article/details/gt2knocjymy.html

[T55] Scala：集合过滤
来源：http://dali.smart0.xyz/Article/details/gt2hmhiviwz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.c1oappe.top/Article/details/gt2uejvihhs.html

[T56] Scala：样例类
来源：http://dali.cqqwz.cn/Article/details/gt2tnjdqzds.html

case class User(name: String, age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gt2qpxncxex.html

[T57] Scala：模式匹配
来源：http://dali.cucudq.cn/Article/details/gt2xmzbevlr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gzhubu.top/Article/details/gt2wfeowrri.html

[T58] Scala：函数定义
来源：http://dali.zhoulong.xyz/Article/details/gt2ppsxfhnp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.smart0.xyz/Article/details/gt2lrjkhucz.html

[T59] Scala：循环
来源：http://dali.haohaochexian.top/Article/details/gt2jajptpoa.html

for (i <- 1 to 10) println(i)
来源：http://dali.dianchejie.cn/Article/details/gt2kddycpwm.html

[T60] Scala：折叠
来源：http://dali.ydzc1.top/Article/details/gt2etsivghx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gogol.net.cn/Article/details/gt2azwwkphc.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2gyjpnkzp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cucudq.cn/Article/details/gt2uswzoqyi.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2sfiwfurd.html

[U01] Py：创建虚拟环境
来源：http://dali.guowangkeji.top/Article/details/gt2nkiudtgp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenjidiqi.icu/Article/details/gt2cnsdjxet.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dianchejie.cn/Article/details/gt2bufpweqo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2kduzuamt.html

[U03] Py：加载 .env 配置
来源：http://dali.zycfv.cn/Article/details/gt2bjcwruog.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hammf.cn/Article/details/gt2aqrkgrcr.html

[U04] Py：变量调试打印
来源：http://dali.daxiang520.top/Article/details/gt2ohyzskgj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sufxvd.cn/Article/details/gt2zhckeniq.html

[U05] Py：列表去重且保序
来源：http://dali.dashuyun.cn/Article/details/gt2hprbvgbs.html

list(dict.fromkeys(arr))
来源：http://dali.tianlin.xyz/Article/details/gt2ajjxjgdu.html

[U06] Py：合并两个字典
来源：http://dali.xinyue.icu/Article/details/gt2zpjuzszo.html

{**a, **b}
来源：http://dali.mhx1999.top/Article/details/gt2jfbdvsek.html

[U07] Py：反转字典键值
来源：http://dali.yuanzhike.top/Article/details/gt2pruxppwz.html

{v: k for k, v in d.items()}
来源：http://dali.cheryme.top/Article/details/gt2vadwamjr.html

[U08] Py：展平二维列表
来源：http://dali.kuanghao11.cn/Article/details/gt2xfbhjdok.html

[y for x in nested for y in x]
来源：http://dali.andypj.xyz/Article/details/gt2kgwvifzs.html

[U09] Py：字典取最大值的键
来源：http://dali.ydzc1.top/Article/details/gt2jqhiujbt.html

max(d, key=d.get)
来源：http://dali.yj202588.top/Article/details/gt2tcuyoaia.html

[U10] Py：按值排序字典
来源：http://dali.ivvv.top/Article/details/gt2pguvpvij.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.andypj.xyz/Article/details/gt2vgykpzdw.html

[U11] Py：生成器表达式
来源：http://dali.ppjwa.cn/Article/details/gt2uluugwla.html

(x * 2 for x in arr)
来源：http://dali.sweek.top/Article/details/gt2yddeaovf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cqqwz.cn/Article/details/gt2gvvaydna.html

Counter(arr).most_common(3)
来源：http://dali.daria6918.cn/Article/details/gt2lzasefsq.html

[U13] Py：固定长度队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fzudomlv.html

deque(maxlen=10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gsgaguhz.html

[U14] Py：分组收集到列表
来源：http://dali.zhengqikj.top/Article/details/gt2tnpzivbk.html

defaultdict(list)
来源：http://dali.chenzaomai.com/Article/details/gt2tguaqhjj.html

[U15] Py：高精度计时
来源：http://dali.dashuyun.cn/Article/details/gt2rpoatcfj.html

t = time.perf_counter()
来源：http://dali.shuidangran.top/Article/details/gt2tcsolydg.html

[U16] Py：命令行参数解析
来源：http://dali.sweek.top/Article/details/gt2wetevlug.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.svipenyu.cn/Article/details/gt2sbwyvool.html

[U17] Py：初始化日志
来源：http://dali.havefunace.top/Article/details/gt2fdmxmzoe.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xinyue.icu/Article/details/gt2ytmwautm.html

[U18] Py：预编译正则
来源：http://dali.yuxming.cn/Article/details/gt2ejzoumda.html

pat = re.compile(r"\d+")
来源：http://dali.sxryk.cn/Article/details/gt2bohkdfvy.html

[U19] Py：正则替换带回调
来源：http://dali.cashguo.top/Article/details/gt2gaccomnk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gogol.net.cn/Article/details/gt2zjadbxkh.html

[U20] Py：缓存函数结果
来源：http://dali.haohaochexian.top/Article/details/gt2hzzlgowe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.c1oappe.top/Article/details/gt2qarncqdw.html

[U21] Py：自定义上下文管理器
来源：http://dali.9152youxi.cn/Article/details/gt2duanpcts.html

@contextlib.contextmanager
来源：http://dali.zhongyouzk.top/Article/details/gt2vcrjlkjo.html

[U22] Py：矩阵转置
来源：http://dali.dianchejie.cn/Article/details/gt2rgpxrdez.html

list(zip(*m))
来源：http://dali.mhx1999.top/Article/details/gt2crrfpfpw.html

[U23] Py：分块读取大文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2eolevnxr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shzxlz.cn/Article/details/gt2asjqxyjz.html

[U24] Py：路径操作
来源：http://dali.daria6918.cn/Article/details/gt2ywoctizq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gt2vxjdboun.html

[U25] Py：CSV 按字典读
来源：http://dali.yonumen.top/Article/details/gt2syehasod.html

csv.DictReader(f)
来源：http://dali.haohaochexian.top/Article/details/gt2aynmribm.html

[U26] Py：并发下载
来源：http://dali.guowangkeji.top/Article/details/gt2whdpcdlc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigufen.top/Article/details/gt2phuiskvy.html

[U27] Py：异步 HTTP
来源：http://dali.havefunace.top/Article/details/gt2vwxujwkm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tian-w.cn/Article/details/gt2vnabrbqb.html

[U28] Py：类型别名
来源：http://dali.nanxinkj.top/Article/details/gt2lvafrsie.html

UserId = int
来源：http://dali.jqgufenzy.top/Article/details/gt2heoloylh.html

[U29] Py：属性校验
来源：http://dali.jqgfzy.top/Article/details/gt2ieddlywq.html

@property 与 @x.setter 配合
来源：http://dali.hnqzz.top/Article/details/gt2gfuwdjys.html

[U30] Py：数据类
来源：http://dali.ppjwa.cn/Article/details/gt2aggzwcif.html

@dataclass(slots=True)
来源：http://dali.xinyue.icu/Article/details/gt2kgwlemmg.html

[U31] Py：单测
来源：http://dali.feifeiyinyue.top/Article/details/gt2zvunyzgj.html

python -m pytest -q
来源：http://dali.yonumen.top/Article/details/gt2fvtvmngk.html

[U32] Py：代码格式化
来源：http://dali.xinyue.icu/Article/details/gt2subqbzon.html

ruff format . && ruff check --fix .
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dbsqwhka.html

[U33] Py：打包发布
来源：http://dali.shangyingyoupin.top/Article/details/gt2mlbwxnwq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenzaomai.com/Article/details/gt2iqvrfhsh.html

[U34] Py：判断编码
来源：http://dali.0kj1m.cn/Article/details/gt2hlmsiszp.html

chardet.detect(raw)
来源：http://dali.aizwys.cn/Article/details/gt2mpajbbkg.html

[U35] Py：发送邮件
来源：http://dali.iojbl.cn/Article/details/gt2oumgcqib.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hnqzz.top/Article/details/gt2cltohorr.html

[U36] Py：定时任务
来源：http://dali.xziqi.cn/Article/details/gt2bhaxnawe.html

schedule.every(10).minutes.do(job)
来源：http://dali.dianchejie.cn/Article/details/gt2hxqguwgk.html

[U37] Py：读写 Excel
来源：http://dali.smart0.xyz/Article/details/gt2keqrakhr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.haohaochexian.top/Article/details/gt2qtjzimhl.html

[U38] Py：获取脚本所在目录
来源：http://dali.birdmap.top/Article/details/gt2shkbsgss.html

Path(__file__).resolve().parent
来源：http://dali.ppjwa.cn/Article/details/gt2sqrpgkkf.html

[U39] Py：判断是否在交互环境
来源：http://dali.mhx1999.top/Article/details/gt2xnxipntx.html

sys.stdout.isatty()
来源：http://dali.sufxvd.cn/Article/details/gt2qwkezliu.html

[U40] Py：打印到标准错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2veuoongr.html

print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gt2ogsoimuv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xylfe.cn/Article/details/gt2yddhztjb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yuxming.cn/Article/details/gt2lssjqrbx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gotoacloud.top/Article/details/gt2nnjenrju.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hfpthk.cn/Article/details/gt2urwykiyp.html

[U43] PHP：声明命名空间
来源：http://dali.jlsjyb.cn/Article/details/gt2groxkrvo.html

namespace App\Http;
来源：http://dali.iojbl.cn/Article/details/gt2blllcofb.html

[U44] PHP：开启严格类型
来源：http://dali.yanxiufei.cn/Article/details/gt2syhaswzy.html

declare(strict_types=1);
来源：http://dali.redwolf501.top/Article/details/gt2sqakznpt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhongyouzk.top/Article/details/gt2oparivob.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gt2sgphjdpj.html

[U46] PHP：可空类型
来源：http://dali.vqdsnc.cn/Article/details/gt2vxjxwiow.html

?string $name = null
来源：http://dali.sufxvd.cn/Article/details/gt2uszlrnif.html

[U47] PHP：联合类型
来源：http://dali.havefunace.top/Article/details/gt2honayfmy.html

int|string $id
来源：http://dali.yj20258.top/Article/details/gt2ezoqdhhm.html

[U48] PHP：纯枚举
来源：http://dali.redwolf501.top/Article/details/gt2gxlckxpw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shuidangran.top/Article/details/gt2pvnccxof.html

[U49] PHP：只读属性
来源：http://dali.yj202588.top/Article/details/gt2bwgakxli.html

public readonly string $name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2beuimsbm.html

[U50] PHP：构造器属性提升
来源：http://dali.yj20258888.top/Article/details/gt2egkihgyx.html

public function __construct(private int $id) {}
来源：http://dali.daria6918.cn/Article/details/gt2gtancdrd.html

[U51] PHP：数组解构
来源：http://dali.nwbrower.top/Article/details/gt2xmotitpe.html

[$a, $b] = $arr;
来源：http://dali.xuetiantiany.cn/Article/details/gt2hgyzftsn.html

[U52] PHP：箭头函数
来源：http://dali.nanxuanxn.top/Article/details/gt2ovljjvls.html

$double = fn($x) => $x * 2;
来源：http://dali.jinqigufen.top/Article/details/gt2lfvnisya.html

[U53] PHP：空合并运算符
来源：http://dali.cdnleiting.top/Article/details/gt2siebvovr.html

$v = $a ?? $b ?? "default";
来源：http://dali.ehwqpu.com/Article/details/gt2wvvaujbi.html

[U54] PHP：空安全调用
来源：http://dali.cucudq.cn/Article/details/gt2cexxilof.html

$obj?->method()
来源：http://dali.wangshuangyany.cn/Article/details/gt2pwujripm.html

[U55] PHP：match 表达式
来源：http://dali.dashuyun.cn/Article/details/gt2ewaejabc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.andypj.xyz/Article/details/gt2nffnikfh.html

[U56] PHP：命名参数
来源：http://dali.cucudq.cn/Article/details/gt2ebcjwomt.html

f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gt2wktwhzix.html

[U57] PHP：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gt2wasnhctw.html

"值: {$a}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2ccuxeasw.html

[U58] PHP：数组三件套
来源：http://dali.ydzc1.top/Article/details/gt2klzofnpv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.aizwys.cn/Article/details/gt2cbenxxcg.html

[U59] PHP：自定义排序
来源：http://dali.xinyue.icu/Article/details/gt2fxwvztml.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gt2ldcgkrfj.html

[U60] PHP：JSON 编解码
来源：http://dali.hammf.cn/Article/details/gt2etalcufd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.smart0.xyz/Article/details/gt2paroxzfe.html

[U61] PHP：正则
来源：http://dali.vqdsnc.cn/Article/details/gt2zjcnvqoi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2vnlkrmcs.html

[U62] PHP：日期对象
来源：http://dali.pycfn.com/Article/details/gt2rltklmdg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.feifeiyinyue.top/Article/details/gt2sdqefdxq.html

[U63] PHP：文件读写
来源：http://dali.shuidangran.top/Article/details/gt2gmbbhcrz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yvedp.cn/Article/details/gt2obipgyjr.html

[U64] PHP：目录遍历
来源：http://dali.ivvv.top/Article/details/gt2avsunrpz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.tianlin.xyz/Article/details/gt2eevdcebo.html

[U65] PHP：会话
来源：http://dali.zycfv.cn/Article/details/gt2qvpdnnky.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jkteeeoo.html

[U66] PHP：设置 Cookie
来源：http://dali.svipenyu.cn/Article/details/gt2vjangspk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gzhubu.top/Article/details/gt2hjrhzfdt.html

[U67] PHP：处理文件上传
来源：http://dali.havefunace.top/Article/details/gt2pguephdb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.vqdsnc.cn/Article/details/gt2pjufyktp.html

[U68] PHP：PDO 连接
来源：http://dali.yangfankeji.com/Article/details/gt2vltkiioh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hongshengwenyu.top/Article/details/gt2bhnktmnp.html

[U69] PHP：PDO 预处理
来源：http://dali.haohaochexian.top/Article/details/gt2vscwdicq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xuanzx.com/Article/details/gt2tjcvfgjj.html

[U70] PHP：PDO 事务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pandfzlk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.andypj.xyz/Article/details/gt2zvgdljor.html

[U71] PHP：抛出异常
来源：http://dali.yj20258888.top/Article/details/gt2bounhcwb.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhixingplan.top/Article/details/gt2lumkldhl.html

[U72] PHP：写错误日志
来源：http://dali.birdmap.top/Article/details/gt2sahxobjl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2afnnibze.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhongyouzk.top/Article/details/gt2jkzumvsj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhengqikj.top/Article/details/gt2plkawvvr.html

[U74] PHP：读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gt2frtntdtk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yuxming.cn/Article/details/gt2nmjolwxh.html

[U75] PHP：依赖注入
来源：http://dali.haohaochexian.top/Article/details/gt2jdvhflhu.html

composer require psr/container
来源：http://dali.yuanzhike.top/Article/details/gt2vsmyldfo.html

[U76] PHP：简单路由
来源：http://dali.yj20258888.top/Article/details/gt2jbbuvfde.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ivvv.top/Article/details/gt2jdeqkmra.html

[U77] PHP：模板渲染
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gevtftwz.html

composer require twig/twig
来源：http://dali.daxiang520.top/Article/details/gt2ezqzcfdq.html

[U78] PHP：单元测试
来源：http://dali.zhengqikj.top/Article/details/gt2pzbeukou.html

composer require --dev phpunit/phpunit
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2waxtcaqg.html

[U79] PHP：静态分析
来源：http://dali.haohaochexian.top/Article/details/gt2subkbcsv.html

composer require --dev phpstan/phpstan
来源：http://dali.jyoumei.cn/Article/details/gt2fsccxumb.html

[U80] PHP：代码规范修复
来源：http://dali.cqqwz.cn/Article/details/gt2neoumssz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.havefunace.top/Article/details/gt2cdounvch.html

[U81] JS：初始化项目
来源：http://dali.ppjwa.cn/Article/details/gt2tvloqgwz.html

npm init -y;  npm i express
来源：http://dali.fzhhl.top/Article/details/gt2uegeoayy.html

[U82] JS：package.json 脚本
来源：http://dali.yongpay.top/Article/details/gt2dhruujzq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.chenlongwang.top/Article/details/gt2ftbuqvvs.html

[U83] JS：ES Module 导入导出
来源：http://dali.vqdsnc.cn/Article/details/gt2tgghqfeq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.c1oappe.top/Article/details/gt2kbfjdnet.html

[U84] JS：CommonJS 写法
来源：http://dali.yangfankeji.com/Article/details/gt2pyxhggdt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ehwqpu.com/Article/details/gt2rzyytwaf.html

[U85] JS：可选链
来源：http://dali.guowangkeji.top/Article/details/gt2bijlpogl.html

a?.b?.c
来源：http://dali.yj20258.top/Article/details/gt2antrxsvl.html

[U86] JS：空值合并
来源：http://dali.gogol.net.cn/Article/details/gt2lxfqzcip.html

a ?? b
来源：http://dali.fzhhl.top/Article/details/gt2xfkfnpgt.html

[U87] JS：解构默认值
来源：http://dali.zycfv.cn/Article/details/gt2imwmpjae.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yvedp.cn/Article/details/gt2xvpezjtj.html

[U88] JS：对象展开合并
来源：http://dali.shuidangran.top/Article/details/gt2dwtckydw.html

{ ...a, ...b }
来源：http://dali.aizwys.cn/Article/details/gt2qlsugimm.html

[U89] JS：数组去重
来源：http://dali.316326.xyz/Article/details/gt2ublqwuud.html

[...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gt2dzyqbzaq.html

[U90] JS：数字数组排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jmyeonss.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gt2wwvlptyn.html

[U91] JS：对象键值遍历
来源：http://dali.tian-w.cn/Article/details/gt2sspbmasl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.aibaodan.cn/Article/details/gt2xkqetdzv.html

[U92] JS：深拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gt2tptrfzib.html

structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gt2dqdyywuo.html


<!-- 参考信息 -->