代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.sxryk.cn/Article/details/gt2bmjdfhsr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hongshengwenyu.top/Article/details/gt2fehhvlon.html

[T06] Kotlin：集合映射
来源：http://dali.yuanzhike.top/Article/details/gt2thisbvbn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhszfkgp.html

[T07] Kotlin：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gt2jfrvkfuu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.haohaochexian.top/Article/details/gt2rkoedfbs.html

[T08] Kotlin：数据类
来源：http://dali.sufxvd.cn/Article/details/gt2rgugykga.html

data class User(val name: String, val age: Int)
来源：http://dali.fengsongda.top/Article/details/gt2ghvpwgmx.html

[T09] Kotlin：扩展函数
来源：http://dali.ydzc1.top/Article/details/gt2nhurjgpp.html

fun String.exclaim() = this + "!"
来源：http://dali.hywenlv.cn/Article/details/gt2sjwzlhbk.html

[T10] Kotlin：默认参数
来源：http://dali.tian-w.cn/Article/details/gt2wwbjuolv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.feifeiyinyue.top/Article/details/gt2dpqvkwon.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rffpyrgk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daria6918.cn/Article/details/gt2pztswaxv.html

[T12] Kotlin：解构声明
来源：http://dali.gotoacloud.top/Article/details/gt2fzxxjkfo.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jcmqkayw.html

[T13] Kotlin：只读 Map
来源：http://dali.birdmap.top/Article/details/gt2epukagfw.html

val m = mapOf("a" to 1)
来源：http://dali.yangfankeji.com/Article/details/gt2whspuuyj.html

[T14] Kotlin：循环
来源：http://dali.hammf.cn/Article/details/gt2kqzrtndb.html

for (i in 1..10) println(i)
来源：http://dali.daria6918.cn/Article/details/gt2ugtszein.html

[T15] Kotlin：接口
来源：http://dali.feifeiyinyue.top/Article/details/gt2lmfzpdbg.html

interface Shape { fun area(): Double }
来源：http://dali.vqdsnc.cn/Article/details/gt2jkwvtfeq.html

[T16] Swift：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2ktqzvdvb.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gt2fyjqrfnq.html

[T17] Swift：变量与常量
来源：http://dali.hfpthk.cn/Article/details/gt2yujtzkml.html

var a = 1;  let b = 2
来源：http://dali.svipenyu.cn/Article/details/gt2jdtjpwtx.html

[T18] Swift：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gt2bfrgjrin.html

"值: \(b)"
来源：http://dali.kuanghao11.cn/Article/details/gt2zkwtkvfz.html

[T19] Swift：可选绑定
来源：http://dali.ppjwa.cn/Article/details/gt2pygdfmtg.html

if let n = opt { print(n) }
来源：http://dali.hysaishi.cn/Article/details/gt2hblsezwm.html

[T20] Swift：数组操作
来源：http://dali.kuanghao11.cn/Article/details/gt2awqkmbmc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xylfe.cn/Article/details/gt2yhodwmzt.html

[T21] Swift：遍历
来源：http://dali.fengsongda.top/Article/details/gt2shmsigru.html

for x in a { print(x) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2shddearf.html

[T22] Swift：字典
来源：http://dali.zhoulong.xyz/Article/details/gt2itslgtic.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fengsongda.top/Article/details/gt2oxbkessj.html

[T23] Swift：函数
来源：http://dali.redwolf501.top/Article/details/gt2vadapkhl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xuanzx.com/Article/details/gt2lgaoscaz.html

[T24] Swift：闭包
来源：http://dali.jinghuilouyu.cn/Article/details/gt2adjmdvvx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ydzaqhve.html

[T25] Swift：结构体
来源：http://dali.sxryk.cn/Article/details/gt2zenvzxru.html

struct P { var x: Int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lgyjfkrw.html

[T26] Swift：类与重写
来源：http://dali.snrcjt.cn/Article/details/gt2oshvvexr.html

class A: Base { override func f() {} }
来源：http://dali.yj20258888.top/Article/details/gt2hgjpminv.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nxuavspg.html

do { try f() } catch { print(error) }
来源：http://dali.guannengcc.top/Article/details/gt2rhxcwhpf.html

[T28] Swift：枚举
来源：http://dali.ydzc1.top/Article/details/gt2mqqcyxdr.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmmnwck.html

[T29] Swift：guard 提前返回
来源：http://dali.dianchejie.cn/Article/details/gt2plzmqpso.html

guard let x = opt else { return }
来源：http://dali.wangdashe.top/Article/details/gt2pwwuygtd.html

[T30] Swift：协议
来源：http://dali.zhongyouzk.top/Article/details/gt2bpoucadz.html

protocol Shape { func area() -> Double }
来源：http://dali.pycfn.com/Article/details/gt2njeotopq.html

[T31] Lua：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2uahgfqkx.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gt2yuenapww.html

[T32] Lua：局部变量
来源：http://dali.ehwqpu.com/Article/details/gt2xciffmjg.html

local a = 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2frmafhma.html

[T33] Lua：表（数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2olyibtpy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jyoumei.cn/Article/details/gt2oxqljhhr.html

[T34] Lua：遍历表
来源：http://dali.aibaodan.cn/Article/details/gt2rpptreyv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenjidiqi.icu/Article/details/gt2vljqexwu.html

[T35] Lua：字典表
来源：http://dali.gzhubu.top/Article/details/gt2zdhuvwqh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yvedp.cn/Article/details/gt2cnzhfadn.html

[T36] Lua：函数
来源：http://dali.hnqzz.top/Article/details/gt2kudwqstk.html

function add(a, b) return a + b end
来源：http://dali.smart0.xyz/Article/details/gt2wnnerizt.html

[T37] Lua：字符串拼接
来源：http://dali.shuidangran.top/Article/details/gt2fnppuywu.html

"a" .. "b"
来源：http://dali.dianchejie.cn/Article/details/gt2rpiqxjqc.html

[T38] Lua：条件
来源：http://dali.zdqjudy.top/Article/details/gt2oogvqymq.html

if x > 0 then print("正") end
来源：http://dali.cucudq.cn/Article/details/gt2byfiaxoc.html

[T39] Lua：模式匹配
来源：http://dali.bjfxy.top/Article/details/gt2umgkgnwd.html

string.find(s, "%d+")
来源：http://dali.gotoacloud.top/Article/details/gt2uuydutny.html

[T40] Lua：元表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vddzvlve.html

setmetatable({}, { __index = base })
来源：http://dali.chenzaomai.com/Article/details/gt2plrduqgk.html

[T41] Perl：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2fgkxkebl.html

print "Hello\n";
来源：http://dali.0kj1m.cn/Article/details/gt2douqucgl.html

[T42] Perl：变量类型
来源：http://dali.quarkkingdee.top/Article/details/gt2hyjgkkeq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.daxiang520.top/Article/details/gt2tkxciokm.html

[T43] Perl：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gt2pixdlsbg.html

"值: $a"
来源：http://dali.fzhhl.top/Article/details/gt2llnzkwfh.html

[T44] Perl：条件
来源：http://dali.yangfankeji.com/Article/details/gt2zskmmsma.html

if ($a > 0) { print "正"; }
来源：http://dali.gzhubu.top/Article/details/gt2ftfgpoqr.html

[T45] Perl：数组遍历
来源：http://dali.hnqzz.top/Article/details/gt2fjuhccjh.html

for my $x (@arr) { print $x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2syqhewex.html

[T46] Perl：哈希操作
来源：http://dali.chenzaomai.com/Article/details/gt2cripwzzd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cucudq.cn/Article/details/gt2lvrotybc.html

[T47] Perl：正则捕获
来源：http://dali.zhixingplan.top/Article/details/gt2hgrpzfma.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.c1oappe.top/Article/details/gt2lusncabn.html

[T48] Perl：正则替换
来源：http://dali.ehwqpu.com/Article/details/gt2huxarzop.html

$s =~ s/old/new/g;
来源：http://dali.redwolf501.top/Article/details/gt2gtwawsag.html

[T49] Perl：函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2usgyxryw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gt2opdqprbi.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzrnvjd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.haohaochexian.top/Article/details/gt2kiihshki.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.9152youxi.cn/Article/details/gt2vjpdidmq.html

[T51] Scala：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2cgajmscv.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gt2humyucuq.html

[T52] Scala：变量
来源：http://dali.hammf.cn/Article/details/gt2toturdbk.html

val a = 1;  var b = 2
来源：http://dali.yuxming.cn/Article/details/gt2ipioxpch.html

[T53] Scala：字符串插值
来源：http://dali.guannengcc.top/Article/details/gt2huhgsywu.html

s"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gt2subsbxmp.html

[T54] Scala：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gt2xyvkqcpc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yangfankeji.com/Article/details/gt2xhiacxvr.html

[T55] Scala：集合过滤
来源：http://dali.yj202588.top/Article/details/gt2jbpqayxi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.9152youxi.cn/Article/details/gt2brxwzqat.html

[T56] Scala：样例类
来源：http://dali.hammf.cn/Article/details/gt2pzbxkncb.html

case class User(name: String, age: Int)
来源：http://dali.cqqwz.cn/Article/details/gt2wmsupuez.html

[T57] Scala：模式匹配
来源：http://dali.jqgfzy.top/Article/details/gt2oppkkmve.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yuanzhike.top/Article/details/gt2imspqikj.html

[T58] Scala：函数定义
来源：http://dali.guannengcc.top/Article/details/gt2jdthabkz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shzxlz.cn/Article/details/gt2xugrvmic.html

[T59] Scala：循环
来源：http://dali.0kj1m.cn/Article/details/gt2swlxlypl.html

for (i <- 1 to 10) println(i)
来源：http://dali.guannengcc.top/Article/details/gt2mtlmegcx.html

[T60] Scala：折叠
来源：http://dali.zdqjudy.top/Article/details/gt2bpeufjle.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nwbrower.top/Article/details/gt2tpqgcoel.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2ufxtfmgk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ehwqpu.com/Article/details/gt2bkgkozbx.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2deouoobn.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxuanxn.top/Article/details/gt2ahkyaiqi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.kuanghao11.cn/Article/details/gt2zswbegdv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.guannengcc.top/Article/details/gt2wkbnzrgg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sweek.top/Article/details/gt2atvzkmul.html

[U03] Py：加载 .env 配置
来源：http://dali.daria6918.cn/Article/details/gt2eyjcdpxq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xylfe.cn/Article/details/gt2usldmevx.html

[U04] Py：变量调试打印
来源：http://dali.yj20258888.top/Article/details/gt2hjwpeggz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nanxuanxn.top/Article/details/gt2lomacavn.html

[U05] Py：列表去重且保序
来源：http://dali.jianghu66.top/Article/details/gt2ryncddfm.html

list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gt2juldgeyr.html

[U06] Py：合并两个字典
来源：http://dali.yuanzhike.top/Article/details/gt2vefpgtoo.html

{**a, **b}
来源：http://dali.guannengcc.top/Article/details/gt2wajzyvbi.html

[U07] Py：反转字典键值
来源：http://dali.yuanzhike.top/Article/details/gt2cvlfqfht.html

{v: k for k, v in d.items()}
来源：http://dali.tian-w.cn/Article/details/gt2kyakfazw.html

[U08] Py：展平二维列表
来源：http://dali.zdqjudy.top/Article/details/gt2afvzojot.html

[y for x in nested for y in x]
来源：http://dali.c1oappe.top/Article/details/gt2ydaefeyp.html

[U09] Py：字典取最大值的键
来源：http://dali.meibo888.top/Article/details/gt2ieamyvvl.html

max(d, key=d.get)
来源：http://dali.cucudq.cn/Article/details/gt2bdatxrnd.html

[U10] Py：按值排序字典
来源：http://dali.yonumen.top/Article/details/gt2sisbdohi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixkoilwl.html

[U11] Py：生成器表达式
来源：http://dali.jiagoushi.top/Article/details/gt2yxatsjrz.html

(x * 2 for x in arr)
来源：http://dali.yongpay.top/Article/details/gt2pelpyzbs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czjtvqiy.html

Counter(arr).most_common(3)
来源：http://dali.ivvv.top/Article/details/gt2hfwddzkq.html

[U13] Py：固定长度队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqramrdq.html

deque(maxlen=10)
来源：http://dali.iojbl.cn/Article/details/gt2peveelgl.html

[U14] Py：分组收集到列表
来源：http://dali.fengsongda.top/Article/details/gt2qnehlqyy.html

defaultdict(list)
来源：http://dali.ivvv.top/Article/details/gt2utnhjmpa.html

[U15] Py：高精度计时
来源：http://dali.jianghu66.top/Article/details/gt2dnoqhvsi.html

t = time.perf_counter()
来源：http://dali.jinqigufen.top/Article/details/gt2fskxthgp.html

[U16] Py：命令行参数解析
来源：http://dali.ppjwa.cn/Article/details/gt2uggpnkwb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuxming.cn/Article/details/gt2oecrsjxw.html

[U17] Py：初始化日志
来源：http://dali.svipenyu.cn/Article/details/gt2jeqplcus.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xinyue.icu/Article/details/gt2zrxoirpr.html

[U18] Py：预编译正则
来源：http://dali.sysykeji.top/Article/details/gt2wlpgqqam.html

pat = re.compile(r"\d+")
来源：http://dali.tian-w.cn/Article/details/gt2mgvzwmtf.html

[U19] Py：正则替换带回调
来源：http://dali.bjfxy.top/Article/details/gt2gveejtcy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nbccpgpk.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ssntbflk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.meibo888.top/Article/details/gt2onlpctop.html

[U21] Py：自定义上下文管理器
来源：http://dali.birdmap.top/Article/details/gt2ualrjtbz.html

@contextlib.contextmanager
来源：http://dali.yuxming.cn/Article/details/gt2vzpiyyir.html

[U22] Py：矩阵转置
来源：http://dali.jiagoushi.top/Article/details/gt2aerypwgm.html

list(zip(*m))
来源：http://dali.zycfv.cn/Article/details/gt2eimwkaad.html

[U23] Py：分块读取大文件
来源：http://dali.quarkkingdee.top/Article/details/gt2jspwgdou.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yuxming.cn/Article/details/gt2tbavhffz.html

[U24] Py：路径操作
来源：http://dali.ehwqpu.com/Article/details/gt2oramtldb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gt2ltnmgwos.html

[U25] Py：CSV 按字典读
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wotkzpdm.html

csv.DictReader(f)
来源：http://dali.fzhhl.top/Article/details/gt2udtbuhqw.html

[U26] Py：并发下载
来源：http://dali.cucudq.cn/Article/details/gt2vsyliehl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hysaishi.cn/Article/details/gt2qvwojvgq.html

[U27] Py：异步 HTTP
来源：http://dali.daria6918.cn/Article/details/gt2ttayzpgj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zdqjudy.top/Article/details/gt2zymeygxo.html

[U28] Py：类型别名
来源：http://dali.zhixingplan.top/Article/details/gt2wrnkrtnu.html

UserId = int
来源：http://dali.chenzaomai.com/Article/details/gt2xqdesrya.html

[U29] Py：属性校验
来源：http://dali.cheryme.top/Article/details/gt2itchxsoo.html

@property 与 @x.setter 配合
来源：http://dali.andypj.xyz/Article/details/gt2hahxvjxl.html

[U30] Py：数据类
来源：http://dali.cqqwz.cn/Article/details/gt2veqghonh.html

@dataclass(slots=True)
来源：http://dali.hywenlv.cn/Article/details/gt2ivlmomch.html

[U31] Py：单测
来源：http://dali.iojbl.cn/Article/details/gt2dspwutlw.html

python -m pytest -q
来源：http://dali.xuanzx.com/Article/details/gt2pedobczg.html

[U32] Py：代码格式化
来源：http://dali.guowangkeji.top/Article/details/gt2cikgqqdd.html

ruff format . && ruff check --fix .
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mgvcgfee.html

[U33] Py：打包发布
来源：http://dali.chenlongwang.top/Article/details/gt2bovamfbt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenlongwang.top/Article/details/gt2zblnwtkq.html

[U34] Py：判断编码
来源：http://dali.sxryk.cn/Article/details/gt2nridlhpb.html

chardet.detect(raw)
来源：http://dali.aibaodan.cn/Article/details/gt2ifthgbew.html

[U35] Py：发送邮件
来源：http://dali.zhongyouzk.top/Article/details/gt2ngddalso.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zycfv.cn/Article/details/gt2ihxwrwjx.html

[U36] Py：定时任务
来源：http://dali.cdnleiting.top/Article/details/gt2yzsxxabb.html

schedule.every(10).minutes.do(job)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kqiegpxk.html

[U37] Py：读写 Excel
来源：http://dali.cheryme.top/Article/details/gt2nzjyctvj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shuidangran.top/Article/details/gt2piixyeyh.html

[U38] Py：获取脚本所在目录
来源：http://dali.shzxlz.cn/Article/details/gt2ojwfzkqe.html

Path(__file__).resolve().parent
来源：http://dali.haohaochexian.top/Article/details/gt2riiwycae.html

[U39] Py：判断是否在交互环境
来源：http://dali.shzxlz.cn/Article/details/gt2kmkpgbzy.html

sys.stdout.isatty()
来源：http://dali.jqgufenzy.top/Article/details/gt2ujmnxgkg.html

[U40] Py：打印到标准错误
来源：http://dali.chenlongwang.top/Article/details/gt2rhkphykx.html

print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gt2gjgtlfji.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fckghrbp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhixingplan.top/Article/details/gt2qpbtpyux.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.meibo888.top/Article/details/gt2gjmosucb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dlsttgdb.html

[U43] PHP：声明命名空间
来源：http://dali.hongshengwenyu.top/Article/details/gt2ukmmrbzo.html

namespace App\Http;
来源：http://dali.c1oappe.top/Article/details/gt2uiavcxfs.html

[U44] PHP：开启严格类型
来源：http://dali.yanxiufei.cn/Article/details/gt2zeqkirks.html

declare(strict_types=1);
来源：http://dali.fzhhl.top/Article/details/gt2wnjzswoi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.c1oappe.top/Article/details/gt2vbfevbbl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2abpfmmnn.html

[U46] PHP：可空类型
来源：http://dali.gotoacloud.top/Article/details/gt2enzluifz.html

?string $name = null
来源：http://dali.shuidangran.top/Article/details/gt2aubirjyr.html

[U47] PHP：联合类型
来源：http://dali.quarkkingdee.top/Article/details/gt2xzbgumpr.html

int|string $id
来源：http://dali.jiagoushi.top/Article/details/gt2assqzddu.html

[U48] PHP：纯枚举
来源：http://dali.xziqi.cn/Article/details/gt2bbkopixr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.birdmap.top/Article/details/gt2rhhyrfjp.html

[U49] PHP：只读属性
来源：http://dali.redwolf501.top/Article/details/gt2mryuwtoi.html

public readonly string $name
来源：http://dali.chenlongwang.top/Article/details/gt2oftjivut.html

[U50] PHP：构造器属性提升
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gsciodbc.html

public function __construct(private int $id) {}
来源：http://dali.aizwys.cn/Article/details/gt2dioedpnj.html

[U51] PHP：数组解构
来源：http://dali.zhoulong.xyz/Article/details/gt2lpczvpld.html

[$a, $b] = $arr;
来源：http://dali.wangdashe.top/Article/details/gt2fuecmrtd.html

[U52] PHP：箭头函数
来源：http://dali.zhengqikj.top/Article/details/gt2ahbyzxwo.html

$double = fn($x) => $x * 2;
来源：http://dali.wangdashe.top/Article/details/gt2bvhkbove.html

[U53] PHP：空合并运算符
来源：http://dali.wangshuangyany.cn/Article/details/gt2fwpgbqkk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhengqikj.top/Article/details/gt2rtunihmb.html

[U54] PHP：空安全调用
来源：http://dali.shangyingyoupin.top/Article/details/gt2wonxekdd.html

$obj?->method()
来源：http://dali.jinqigfzy.top/Article/details/gt2ctcluuid.html

[U55] PHP：match 表达式
来源：http://dali.gogol.net.cn/Article/details/gt2hftvszqu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.dianchejie.cn/Article/details/gt2canexetk.html

[U56] PHP：命名参数
来源：http://dali.cheryme.top/Article/details/gt2qdeqslpp.html

f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjrysbkr.html

[U57] PHP：字符串插值
来源：http://dali.xuanzx.com/Article/details/gt2qubrqtoq.html

"值: {$a}"
来源：http://dali.xylfe.cn/Article/details/gt2shmijaht.html

[U58] PHP：数组三件套
来源：http://dali.gaohongyu789.top/Article/details/gt2ypzeefpo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtocsnuk.html

[U59] PHP：自定义排序
来源：http://dali.sweek.top/Article/details/gt2jwdbomgy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gt2mdkbfrvk.html

[U60] PHP：JSON 编解码
来源：http://dali.hywenlv.cn/Article/details/gt2rppxocie.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shuidangran.top/Article/details/gt2gtlosrsr.html

[U61] PHP：正则
来源：http://dali.tianlin.xyz/Article/details/gt2xbiwrwen.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.daxiang520.top/Article/details/gt2zbpauufl.html

[U62] PHP：日期对象
来源：http://dali.yuanzhike.top/Article/details/gt2ureobgzr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hnxiangtu.top/Article/details/gt2opnuosit.html

[U63] PHP：文件读写
来源：http://dali.hnqzz.top/Article/details/gt2ubmvfqip.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.birdmap.top/Article/details/gt2bctoscdp.html

[U64] PHP：目录遍历
来源：http://dali.hysaishi.cn/Article/details/gt2hhwqugsq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cucudq.cn/Article/details/gt2aqezdqhk.html

[U65] PHP：会话
来源：http://dali.chenlongwang.top/Article/details/gt2cejjzkqj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2izznrybl.html

[U66] PHP：设置 Cookie
来源：http://dali.birdmap.top/Article/details/gt2llhjbquj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cqqwz.cn/Article/details/gt2huagazhf.html

[U67] PHP：处理文件上传
来源：http://dali.vqdsnc.cn/Article/details/gt2idhbonft.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yj202588.top/Article/details/gt2qqyysnby.html

[U68] PHP：PDO 连接
来源：http://dali.yj20258888.top/Article/details/gt2sjcpykkf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.smart0.xyz/Article/details/gt2jrlohblg.html

[U69] PHP：PDO 预处理
来源：http://dali.nanxinkj.top/Article/details/gt2sqnmaypa.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.svipenyu.cn/Article/details/gt2ktlkdlos.html

[U70] PHP：PDO 事务
来源：http://dali.hfpthk.cn/Article/details/gt2kkdnoikz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yonumen.top/Article/details/gt2yourvztr.html

[U71] PHP：抛出异常
来源：http://dali.yj20258888.top/Article/details/gt2rgynpukz.html

throw new RuntimeException("失败", 500);
来源：http://dali.nanxuanxn.top/Article/details/gt2mgsdciue.html

[U72] PHP：写错误日志
来源：http://dali.xziqi.cn/Article/details/gt2yyouhpoq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jqgufenzy.top/Article/details/gt2zdbyxzcm.html

[U73] PHP：读取 ini 配置
来源：http://dali.cashguo.top/Article/details/gt2fnvotfge.html

parse_ini_file("config.ini", true)
来源：http://dali.gaohongyu789.top/Article/details/gt2tnbjwdqm.html

[U74] PHP：读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2umvbtaul.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xziqi.cn/Article/details/gt2oooipuiw.html

[U75] PHP：依赖注入
来源：http://dali.c1oappe.top/Article/details/gt2evmqqahi.html

composer require psr/container
来源：http://dali.yangfankeji.com/Article/details/gt2ovvzutby.html

[U76] PHP：简单路由
来源：http://dali.yvedp.cn/Article/details/gt2favhemiy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.guannengcc.top/Article/details/gt2oadejwgc.html

[U77] PHP：模板渲染
来源：http://dali.jyoumei.cn/Article/details/gt2ysuugpxu.html

composer require twig/twig
来源：http://dali.sweek.top/Article/details/gt2iecrbcfi.html

[U78] PHP：单元测试
来源：http://dali.hnqzz.top/Article/details/gt2bvlgfrya.html

composer require --dev phpunit/phpunit
来源：http://dali.zhiwuduotai.top/Article/details/gt2qwmrqunn.html

[U79] PHP：静态分析
来源：http://dali.daria6918.cn/Article/details/gt2tpdfeefi.html

composer require --dev phpstan/phpstan
来源：http://dali.andypj.xyz/Article/details/gt2jxaexwbq.html

[U80] PHP：代码规范修复
来源：http://dali.jyoumei.cn/Article/details/gt2jlzksasv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yj20258888.top/Article/details/gt2btsavgvp.html

[U81] JS：初始化项目
来源：http://dali.smart0.xyz/Article/details/gt2whtvyiqt.html

npm init -y;  npm i express
来源：http://dali.chenzaomai.com/Article/details/gt2owdtbkjj.html

[U82] JS：package.json 脚本
来源：http://dali.fengsongda.top/Article/details/gt2gvjnekea.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hnxiangtu.top/Article/details/gt2jggcbjod.html

[U83] JS：ES Module 导入导出
来源：http://dali.hammf.cn/Article/details/gt2tvxxiyyq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.nanxuanxn.top/Article/details/gt2uyhqskef.html

[U84] JS：CommonJS 写法
来源：http://dali.zhiwuduotai.top/Article/details/gt2ihkzzwgt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinqigfzy.top/Article/details/gt2ciowtajz.html

[U85] JS：可选链
来源：http://dali.fzhhl.top/Article/details/gt2wfgbuyqz.html

a?.b?.c
来源：http://dali.gaohongyu789.top/Article/details/gt2wnmehvlj.html

[U86] JS：空值合并
来源：http://dali.hongshengwenyu.top/Article/details/gt2mgwnssyf.html

a ?? b
来源：http://dali.cucudq.cn/Article/details/gt2bjyhjuam.html

[U87] JS：解构默认值
来源：http://dali.gzhubu.top/Article/details/gt2eopgxubx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.aizwys.cn/Article/details/gt2rsfrnueu.html

[U88] JS：对象展开合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vipddohh.html

{ ...a, ...b }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lnpeebtz.html

[U89] JS：数组去重
来源：http://dali.jinqigufen.top/Article/details/gt2bzpccewh.html

[...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gt2ajhhbrzt.html

[U90] JS：数字数组排序
来源：http://dali.guowangkeji.top/Article/details/gt2nmebttma.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gt2twezvujw.html

[U91] JS：对象键值遍历
来源：http://dali.hammf.cn/Article/details/gt2ocxfnyxo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.daria6918.cn/Article/details/gt2sgyebhfy.html

[U92] JS：深拷贝
来源：http://dali.guowangkeji.top/Article/details/gt2nychlrvq.html

structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hvvwrcca.html


<!-- 参考信息 -->