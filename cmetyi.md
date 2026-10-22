代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.yongpay.top/Article/details/gtadwudihi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cheryme.top/Article/details/gtckkparnk.html

[T06] Kotlin：集合映射
来源：http://dali.zhengqikj.top/Article/details/gtovrtqwfo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtnnggqwam.html

[T07] Kotlin：集合过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtkanwzrum.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ydzc1.top/Article/details/gtoxeuzfvy.html

[T08] Kotlin：数据类
来源：http://dali.ppjwa.cn/Article/details/gtonftjdnh.html

data class User(val name: String, val age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gtkuglxupi.html

[T09] Kotlin：扩展函数
来源：http://dali.smart0.xyz/Article/details/gttpapucpy.html

fun String.exclaim() = this + "!"
来源：http://dali.hywenlv.cn/Article/details/gtyqutbprm.html

[T10] Kotlin：默认参数
来源：http://dali.c1oappe.top/Article/details/gtsfbanqri.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cashguo.top/Article/details/gticgwehix.html

[T11] Kotlin：协程
来源：http://dali.wangdashe.top/Article/details/gtsovomwve.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daxiang520.top/Article/details/gtgiunkyda.html

[T12] Kotlin：解构声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdwmhqda.html

val (a, b) = Pair(1, 2)
来源：http://dali.birdmap.top/Article/details/gtotlabhmf.html

[T13] Kotlin：只读 Map
来源：http://dali.yanxiufei.cn/Article/details/gtkioclqfg.html

val m = mapOf("a" to 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtqncpcwvc.html

[T14] Kotlin：循环
来源：http://dali.kuanghao11.cn/Article/details/gtnrdyqipz.html

for (i in 1..10) println(i)
来源：http://dali.cashguo.top/Article/details/gtlxsbybhz.html

[T15] Kotlin：接口
来源：http://dali.dianchejie.cn/Article/details/gttetmqthr.html

interface Shape { fun area(): Double }
来源：http://dali.hfpthk.cn/Article/details/gtztjzozip.html

[T16] Swift：Hello World
来源：http://dali.cheryme.top/Article/details/gtwwrcxooz.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtiyzvbctf.html

[T17] Swift：变量与常量
来源：http://dali.hnqzz.top/Article/details/gtchktskjy.html

var a = 1;  let b = 2
来源：http://dali.nwbrower.top/Article/details/gtqnvsesdi.html

[T18] Swift：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtxxozfumu.html

"值: \(b)"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvkttujx.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugxljdfu.html

if let n = opt { print(n) }
来源：http://dali.zycfv.cn/Article/details/gtwuhdalku.html

[T20] Swift：数组操作
来源：http://dali.fengsongda.top/Article/details/gtdkmyktds.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nwbrower.top/Article/details/gtkdxqadpi.html

[T21] Swift：遍历
来源：http://dali.havefunace.top/Article/details/gtlahbrgpj.html

for x in a { print(x) }
来源：http://dali.mhx1999.top/Article/details/gtiqdtvdgj.html

[T22] Swift：字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtsohdesba.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.316326.xyz/Article/details/gtphwrpbke.html

[T23] Swift：函数
来源：http://dali.xylfe.cn/Article/details/gtmcairset.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gotoacloud.top/Article/details/gtlsmokwds.html

[T24] Swift：闭包
来源：http://dali.guowangkeji.top/Article/details/gtkvtmvwvh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuanzx.com/Article/details/gtrkppjqii.html

[T25] Swift：结构体
来源：http://dali.jinqigfzy.top/Article/details/gthdhaikae.html

struct P { var x: Int }
来源：http://dali.ppjwa.cn/Article/details/gtozzdtssr.html

[T26] Swift：类与重写
来源：http://dali.zhixingplan.top/Article/details/gtcbhiqdeo.html

class A: Base { override func f() {} }
来源：http://dali.316326.xyz/Article/details/gtompiluyz.html

[T27] Swift：错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gtkwqhcvha.html

do { try f() } catch { print(error) }
来源：http://dali.fengsongda.top/Article/details/gtnuiqtmyi.html

[T28] Swift：枚举
来源：http://dali.cdnleiting.top/Article/details/gtjpeykytk.html

enum Color { case red, green }
来源：http://dali.svipenyu.cn/Article/details/gtxigumrih.html

[T29] Swift：guard 提前返回
来源：http://dali.snrcjt.cn/Article/details/gtjgkoltgj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gtkmdmfetf.html

[T30] Swift：协议
来源：http://dali.fengsongda.top/Article/details/gtrycxjvhd.html

protocol Shape { func area() -> Double }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqweuftp.html

[T31] Lua：Hello World
来源：http://dali.wangdashe.top/Article/details/gtnwwzlccn.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtbeeuorgx.html

[T32] Lua：局部变量
来源：http://dali.fengsongda.top/Article/details/gtgjuqowin.html

local a = 1
来源：http://dali.jiagoushi.top/Article/details/gttequwdky.html

[T33] Lua：表（数组）
来源：http://dali.snrcjt.cn/Article/details/gtvigtiedz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hysaishi.cn/Article/details/gtgueqzxgs.html

[T34] Lua：遍历表
来源：http://dali.quarkkingdee.top/Article/details/gtkpgcnnha.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cheryme.top/Article/details/gtykqiuqon.html

[T35] Lua：字典表
来源：http://dali.gaohongyu789.top/Article/details/gtmkmtltff.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigufen.top/Article/details/gtwiqthrwe.html

[T36] Lua：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtsilamkaa.html

function add(a, b) return a + b end
来源：http://dali.yj202588.top/Article/details/gtocwwxldy.html

[T37] Lua：字符串拼接
来源：http://dali.shuidangran.top/Article/details/gtazqexhsl.html

"a" .. "b"
来源：http://dali.sufxvd.cn/Article/details/gtmjrjyyol.html

[T38] Lua：条件
来源：http://dali.fzhhl.top/Article/details/gtzhbudqtk.html

if x > 0 then print("正") end
来源：http://dali.tanke756.top/Article/details/gtwqkhjcdx.html

[T39] Lua：模式匹配
来源：http://dali.yj202588.top/Article/details/gtiusdwafu.html

string.find(s, "%d+")
来源：http://dali.cheryme.top/Article/details/gtobyaioho.html

[T40] Lua：元表
来源：http://dali.hysaishi.cn/Article/details/gtndoonvoe.html

setmetatable({}, { __index = base })
来源：http://dali.vqdsnc.cn/Article/details/gtujlerlxj.html

[T41] Perl：Hello World
来源：http://dali.yvedp.cn/Article/details/gtmjuykhkq.html

print "Hello\n";
来源：http://dali.tanke756.top/Article/details/gtalbyfavx.html

[T42] Perl：变量类型
来源：http://dali.yj20258.top/Article/details/gtziizpuvu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.guannengcc.top/Article/details/gtcvbqhoxp.html

[T43] Perl：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtdopjeopq.html

"值: $a"
来源：http://dali.gogol.net.cn/Article/details/gtonomvkex.html

[T44] Perl：条件
来源：http://dali.hysaishi.cn/Article/details/gtuicnedzs.html

if ($a > 0) { print "正"; }
来源：http://dali.andypj.xyz/Article/details/gtmpbvbedz.html

[T45] Perl：数组遍历
来源：http://dali.guannengcc.top/Article/details/gtjkpzrdzu.html

for my $x (@arr) { print $x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfncpvzb.html

[T46] Perl：哈希操作
来源：http://dali.hnqzz.top/Article/details/gtljfuwkco.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gzhubu.top/Article/details/gtpqyzolth.html

[T47] Perl：正则捕获
来源：http://dali.quarkkingdee.top/Article/details/gtjqyftwtm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.vqdsnc.cn/Article/details/gtsgprlxyz.html

[T48] Perl：正则替换
来源：http://dali.cucudq.cn/Article/details/gttwyqcafo.html

$s =~ s/old/new/g;
来源：http://dali.yangfankeji.com/Article/details/gtvblnylnq.html

[T49] Perl：函数
来源：http://dali.bjfxy.top/Article/details/gtbowuoakl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gtdwgtjahv.html

[T50] Perl：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtuvwsicml.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cashguo.top/Article/details/gtjqunepkw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yangfankeji.com/Article/details/gtqixjwbmt.html

[T51] Scala：Hello World
来源：http://dali.xziqi.cn/Article/details/gtfxhhidjk.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gttljbcflu.html

[T52] Scala：变量
来源：http://dali.c1oappe.top/Article/details/gteboestqh.html

val a = 1;  var b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtwaqjfivz.html

[T53] Scala：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtgibyjcbr.html

s"值: $b"
来源：http://dali.yvedp.cn/Article/details/gtevriuiyq.html

[T54] Scala：集合映射
来源：http://dali.cdnleiting.top/Article/details/gtqetgcgdt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhixingplan.top/Article/details/gtankzjexl.html

[T55] Scala：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gtzhtxcfkq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj20258888.top/Article/details/gtfxlxdpjs.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gtyiymnqzl.html

case class User(name: String, age: Int)
来源：http://dali.tianlin.xyz/Article/details/gttjanevgk.html

[T57] Scala：模式匹配
来源：http://dali.xuanzx.com/Article/details/gtdrkfpkha.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jyoumei.cn/Article/details/gttiyffixm.html

[T58] Scala：函数定义
来源：http://dali.meibo888.top/Article/details/gtlfztjssw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hammf.cn/Article/details/gtgkaiocyv.html

[T59] Scala：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfydtqjur.html

for (i <- 1 to 10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gtkzjgodgf.html

[T60] Scala：折叠
来源：http://dali.feifeiyinyue.top/Article/details/gtpgnpurhd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yueranfly.top/Article/details/gtnjpkykiz.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gthmundzom.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.vqdsnc.cn/Article/details/gtchjyrnyx.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtofeknbjw.html

[U01] Py：创建虚拟环境
来源：http://dali.xuetiantiany.cn/Article/details/gtxjjexocj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aizwys.cn/Article/details/gtvdgejxuc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gzhubu.top/Article/details/gtkzlatpyd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ppjwa.cn/Article/details/gtabjguavz.html

[U03] Py：加载 .env 配置
来源：http://dali.jianghu66.top/Article/details/gtxkfevvqf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.kuanghao11.cn/Article/details/gthrowkuxl.html

[U04] Py：变量调试打印
来源：http://dali.yongpay.top/Article/details/gtvdibamde.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.iojbl.cn/Article/details/gttclenive.html

[U05] Py：列表去重且保序
来源：http://dali.cashguo.top/Article/details/gtwgsabybl.html

list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gtfwlcmfwt.html

[U06] Py：合并两个字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxxfovpj.html

{**a, **b}
来源：http://dali.shanyushiyangtech.top/Article/details/gtofwipbyv.html

[U07] Py：反转字典键值
来源：http://dali.gogol.net.cn/Article/details/gthftoggjp.html

{v: k for k, v in d.items()}
来源：http://dali.ivvv.top/Article/details/gtczxasmkn.html

[U08] Py：展平二维列表
来源：http://dali.xuetiantiany.cn/Article/details/gtrwyfjrox.html

[y for x in nested for y in x]
来源：http://dali.ppjwa.cn/Article/details/gtwqofuylk.html

[U09] Py：字典取最大值的键
来源：http://dali.hongshengwenyu.top/Article/details/gttohyyzie.html

max(d, key=d.get)
来源：http://dali.cdnleiting.top/Article/details/gtrwtloibf.html

[U10] Py：按值排序字典
来源：http://dali.ybcxt.top/Article/details/gtgtodxhob.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.dashuyun.cn/Article/details/gtbjhnjawk.html

[U11] Py：生成器表达式
来源：http://dali.hysaishi.cn/Article/details/gtwuenlrzc.html

(x * 2 for x in arr)
来源：http://dali.redwolf501.top/Article/details/gtxorxyqyg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yuanzhike.top/Article/details/gtwspqrllo.html

Counter(arr).most_common(3)
来源：http://dali.cheryme.top/Article/details/gtqolsidoq.html

[U13] Py：固定长度队列
来源：http://dali.snrcjt.cn/Article/details/gtmzzchxlu.html

deque(maxlen=10)
来源：http://dali.hongshengwenyu.top/Article/details/gtmqxtgjny.html

[U14] Py：分组收集到列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkwysyjs.html

defaultdict(list)
来源：http://dali.zhiwuduotai.top/Article/details/gtnmbfgtck.html

[U15] Py：高精度计时
来源：http://dali.jinqigfzy.top/Article/details/gtfeoezftw.html

t = time.perf_counter()
来源：http://dali.shuidangran.top/Article/details/gttzcwpqun.html

[U16] Py：命令行参数解析
来源：http://dali.yuanzhike.top/Article/details/gtnntneysg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.dashuyun.cn/Article/details/gtatjgzooz.html

[U17] Py：初始化日志
来源：http://dali.c1oappe.top/Article/details/gtlxbaecpf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.0kj1m.cn/Article/details/gtzzkmaghd.html

[U18] Py：预编译正则
来源：http://dali.xylfe.cn/Article/details/gtkxbubjqf.html

pat = re.compile(r"\d+")
来源：http://dali.fengsongda.top/Article/details/gtdqvpigov.html

[U19] Py：正则替换带回调
来源：http://dali.ivvv.top/Article/details/gtidgnthko.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.havefunace.top/Article/details/gtmeiigkva.html

[U20] Py：缓存函数结果
来源：http://dali.redwolf501.top/Article/details/gtllhojhvh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cqqwz.cn/Article/details/gtcxgqxcuf.html

[U21] Py：自定义上下文管理器
来源：http://dali.yueranfly.top/Article/details/gtnddresui.html

@contextlib.contextmanager
来源：http://dali.zhengqikj.top/Article/details/gtqzwhmuvx.html

[U22] Py：矩阵转置
来源：http://dali.yj20258888.top/Article/details/gtshlnzvao.html

list(zip(*m))
来源：http://dali.chenzaomai.com/Article/details/gtjunfgrbv.html

[U23] Py：分块读取大文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsikiklf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.0kj1m.cn/Article/details/gtmjduletk.html

[U24] Py：路径操作
来源：http://dali.jinghuilouyu.cn/Article/details/gttniaafsl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtpnoujmbq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhoulong.xyz/Article/details/gtizjjtwgm.html

csv.DictReader(f)
来源：http://dali.zhongyouzk.top/Article/details/gtlnchlqef.html

[U26] Py：并发下载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnoowylr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.dashuyun.cn/Article/details/gtftjfxeiu.html

[U27] Py：异步 HTTP
来源：http://dali.mhx1999.top/Article/details/gtmxsmqloj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gtpuuvmvcv.html

[U28] Py：类型别名
来源：http://dali.kuanghao11.cn/Article/details/gtldrhncuv.html

UserId = int
来源：http://dali.pycfn.com/Article/details/gtewlyewvx.html

[U29] Py：属性校验
来源：http://dali.daria6918.cn/Article/details/gtbywhzohj.html

@property 与 @x.setter 配合
来源：http://dali.ppjwa.cn/Article/details/gtgbdwbcnm.html

[U30] Py：数据类
来源：http://dali.fzhhl.top/Article/details/gtqywgixpd.html

@dataclass(slots=True)
来源：http://dali.cucudq.cn/Article/details/gtydepouef.html

[U31] Py：单测
来源：http://dali.zdqjudy.top/Article/details/gtrneehpcm.html

python -m pytest -q
来源：http://dali.0kj1m.cn/Article/details/gtjimtxweh.html

[U32] Py：代码格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtjaxkrjsw.html

ruff format . && ruff check --fix .
来源：http://dali.bjfxy.top/Article/details/gtqtkxobww.html

[U33] Py：打包发布
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvueeqsu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yueranfly.top/Article/details/gtjsromzdl.html

[U34] Py：判断编码
来源：http://dali.jqgfzy.top/Article/details/gtvkaowbcm.html

chardet.detect(raw)
来源：http://dali.cashguo.top/Article/details/gtmysomwln.html

[U35] Py：发送邮件
来源：http://dali.xuetiantiany.cn/Article/details/gtiviwclzs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.guowangkeji.top/Article/details/gtejpoeabo.html

[U36] Py：定时任务
来源：http://dali.ppjwa.cn/Article/details/gtdmvtoupg.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj20258888.top/Article/details/gtmvtyenzl.html

[U37] Py：读写 Excel
来源：http://dali.zhengqikj.top/Article/details/gtjfsyjzdk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shangyingyoupin.top/Article/details/gtnrtopwih.html

[U38] Py：获取脚本所在目录
来源：http://dali.ivvv.top/Article/details/gtkwjgorqs.html

Path(__file__).resolve().parent
来源：http://dali.hnqzz.top/Article/details/gtypamybnr.html

[U39] Py：判断是否在交互环境
来源：http://dali.pycfn.com/Article/details/gtrhskzhgq.html

sys.stdout.isatty()
来源：http://dali.fengsongda.top/Article/details/gtlivupgjz.html

[U40] Py：打印到标准错误
来源：http://dali.gogol.net.cn/Article/details/gtqlxskmpn.html

print("err", file=sys.stderr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtodlvtdig.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhixingplan.top/Article/details/gtilkyybjg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.bjfxy.top/Article/details/gtefpwjxws.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.nanxinkj.top/Article/details/gtdqdkswkw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ppjwa.cn/Article/details/gtjgscjgmb.html

[U43] PHP：声明命名空间
来源：http://dali.ybcxt.top/Article/details/gthjlvoler.html

namespace App\Http;
来源：http://dali.iojbl.cn/Article/details/gtwgdszxur.html

[U44] PHP：开启严格类型
来源：http://dali.cqqwz.cn/Article/details/gtbdckimui.html

declare(strict_types=1);
来源：http://dali.redwolf501.top/Article/details/gtxejavzmx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xuanzx.com/Article/details/gtnkmpqvhz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gthtdfehca.html

[U46] PHP：可空类型
来源：http://dali.yonumen.top/Article/details/gtruykmong.html

?string $name = null
来源：http://dali.daria6918.cn/Article/details/gtanftqvsx.html

[U47] PHP：联合类型
来源：http://dali.hysaishi.cn/Article/details/gtqmiteonv.html

int|string $id
来源：http://dali.9152youxi.cn/Article/details/gtsuufvvzn.html

[U48] PHP：纯枚举
来源：http://dali.nanxuanxn.top/Article/details/gtspuarfoh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hammf.cn/Article/details/gtunjjievb.html

[U49] PHP：只读属性
来源：http://dali.xuetiantiany.cn/Article/details/gtkrxzfkye.html

public readonly string $name
来源：http://dali.redwolf501.top/Article/details/gtzkgazgil.html

[U50] PHP：构造器属性提升
来源：http://dali.hnqzz.top/Article/details/gtekldgbnm.html

public function __construct(private int $id) {}
来源：http://dali.nanxinkj.top/Article/details/gthnyszvft.html

[U51] PHP：数组解构
来源：http://dali.hywenlv.cn/Article/details/gtmkbvenwz.html

[$a, $b] = $arr;
来源：http://dali.zhongyouzk.top/Article/details/gtmovgjbtw.html

[U52] PHP：箭头函数
来源：http://dali.gogol.net.cn/Article/details/gtvcexblms.html

$double = fn($x) => $x * 2;
来源：http://dali.meibo888.top/Article/details/gtioscikng.html

[U53] PHP：空合并运算符
来源：http://dali.sysykeji.top/Article/details/gtkyvplotr.html

$v = $a ?? $b ?? "default";
来源：http://dali.316326.xyz/Article/details/gtkgkiowhm.html

[U54] PHP：空安全调用
来源：http://dali.kuanghao11.cn/Article/details/gttzatyxtn.html

$obj?->method()
来源：http://dali.yj20258888.top/Article/details/gttgvocnoi.html

[U55] PHP：match 表达式
来源：http://dali.shzxlz.cn/Article/details/gtunckcxdv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jqgfzy.top/Article/details/gthmtpjkiq.html

[U56] PHP：命名参数
来源：http://dali.vqdsnc.cn/Article/details/gtquztpqte.html

f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gthnxajpnr.html

[U57] PHP：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gttsekicid.html

"值: {$a}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdatjfub.html

[U58] PHP：数组三件套
来源：http://dali.chenlongwang.top/Article/details/gtfedynpny.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yj202588.top/Article/details/gtekyntbrc.html

[U59] PHP：自定义排序
来源：http://dali.sufxvd.cn/Article/details/gtsfsakqlv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daxiang520.top/Article/details/gtylfywnxu.html

[U60] PHP：JSON 编解码
来源：http://dali.chenlongwang.top/Article/details/gtsgtyvnsl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yonumen.top/Article/details/gtaukqiglu.html

[U61] PHP：正则
来源：http://dali.xziqi.cn/Article/details/gtnvmjyyto.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.fengsongda.top/Article/details/gtkyqfkcdv.html

[U62] PHP：日期对象
来源：http://dali.nwbrower.top/Article/details/gtfnboytwg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.daria6918.cn/Article/details/gtmmitudbk.html

[U63] PHP：文件读写
来源：http://dali.hongshengwenyu.top/Article/details/gtohcsiiuk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.c1oappe.top/Article/details/gtmtiqisfe.html

[U64] PHP：目录遍历
来源：http://dali.svipenyu.cn/Article/details/gtefsccraj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gaohongyu789.top/Article/details/gtzmcpkana.html

[U65] PHP：会话
来源：http://dali.jiagoushi.top/Article/details/gtybkqxyly.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtlpihsrab.html

[U66] PHP：设置 Cookie
来源：http://dali.jqgfzy.top/Article/details/gtlehigulh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jqgfzy.top/Article/details/gthwxagxhf.html

[U67] PHP：处理文件上传
来源：http://dali.quarkkingdee.top/Article/details/gtvdotahft.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.chenjidiqi.icu/Article/details/gtdhrywtqc.html

[U68] PHP：PDO 连接
来源：http://dali.dianchejie.cn/Article/details/gtlcavouvp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.kuanghao11.cn/Article/details/gtdzjfaudw.html

[U69] PHP：PDO 预处理
来源：http://dali.tian-w.cn/Article/details/gtfypouysq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhoulong.xyz/Article/details/gttnsnyrbm.html

[U70] PHP：PDO 事务
来源：http://dali.iojbl.cn/Article/details/gtpdygbpie.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.smart0.xyz/Article/details/gtmeqyhpwt.html

[U71] PHP：抛出异常
来源：http://dali.tanke756.top/Article/details/gtnhzmabma.html

throw new RuntimeException("失败", 500);
来源：http://dali.yj202588.top/Article/details/gtzbjboewx.html

[U72] PHP：写错误日志
来源：http://dali.quarkkingdee.top/Article/details/gtkwngitxb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenzaomai.com/Article/details/gtzuwwbomy.html

[U73] PHP：读取 ini 配置
来源：http://dali.c1oappe.top/Article/details/gtzsrcvkyk.html

parse_ini_file("config.ini", true)
来源：http://dali.daria6918.cn/Article/details/gtqcxwugwu.html

[U74] PHP：读取环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxvocgaa.html

getenv("APP_ENV") ?: "production"
来源：http://dali.havefunace.top/Article/details/gtwclinsqw.html

[U75] PHP：依赖注入
来源：http://dali.yueranfly.top/Article/details/gtnthqailc.html

composer require psr/container
来源：http://dali.316326.xyz/Article/details/gtcuxbhokk.html

[U76] PHP：简单路由
来源：http://dali.redwolf501.top/Article/details/gteuxeknen.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.tian-w.cn/Article/details/gtrdcphjmv.html

[U77] PHP：模板渲染
来源：http://dali.mhx1999.top/Article/details/gtipxjqblj.html

composer require twig/twig
来源：http://dali.fzhhl.top/Article/details/gtpfavockz.html

[U78] PHP：单元测试
来源：http://dali.ivvv.top/Article/details/gtitpwmqvh.html

composer require --dev phpunit/phpunit
来源：http://dali.haohaochexian.top/Article/details/gtrzavasqp.html

[U79] PHP：静态分析
来源：http://dali.0kj1m.cn/Article/details/gtieqdlsth.html

composer require --dev phpstan/phpstan
来源：http://dali.zhiwuduotai.top/Article/details/gthhqcakev.html

[U80] PHP：代码规范修复
来源：http://dali.jinqigufen.top/Article/details/gtpilsappp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.gogol.net.cn/Article/details/gtswvyfwvr.html

[U81] JS：初始化项目
来源：http://dali.yj202588.top/Article/details/gtkcwhclqf.html

npm init -y;  npm i express
来源：http://dali.svipenyu.cn/Article/details/gtbwdkwgxi.html

[U82] JS：package.json 脚本
来源：http://dali.xylfe.cn/Article/details/gtvmcxqrrg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yuanzhike.top/Article/details/gtmtohzoas.html

[U83] JS：ES Module 导入导出
来源：http://dali.guannengcc.top/Article/details/gtmrgugxwe.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sweek.top/Article/details/gtcbaenejn.html

[U84] JS：CommonJS 写法
来源：http://dali.zhiwuduotai.top/Article/details/gtgjfhdgax.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jiagoushi.top/Article/details/gtjtcvxugc.html

[U85] JS：可选链
来源：http://dali.yonumen.top/Article/details/gtjmkcxrzf.html

a?.b?.c
来源：http://dali.smart0.xyz/Article/details/gtkjrroiiz.html

[U86] JS：空值合并
来源：http://dali.guannengcc.top/Article/details/gthxynkpyw.html

a ?? b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbmnvbgd.html

[U87] JS：解构默认值
来源：http://dali.xylfe.cn/Article/details/gtvcaaynuh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sxryk.cn/Article/details/gturlyldya.html

[U88] JS：对象展开合并
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjjdrkjr.html

{ ...a, ...b }
来源：http://dali.sxryk.cn/Article/details/gtbguvtend.html

[U89] JS：数组去重
来源：http://dali.xinyue.icu/Article/details/gtklsiakgo.html

[...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtbejyzyrx.html

[U90] JS：数字数组排序
来源：http://dali.smart0.xyz/Article/details/gtqhgsdmke.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtzicvmaui.html

[U91] JS：对象键值遍历
来源：http://dali.chenlongwang.top/Article/details/gtneujcrgv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhongyouzk.top/Article/details/gtvqllkune.html

[U92] JS：深拷贝
来源：http://dali.xuanzx.com/Article/details/gtuoidqbis.html

structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtpqkaqfjb.html


<!-- 参考信息 -->