代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xzoupkak.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2weakinjo.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zgodrini.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsnxirt.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2whywaznz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsyegjz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zxycxffb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrkgyyk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2secfmneb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfrlkar.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcshioko.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtbbdcq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2djfbqkry.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzknaxk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxtpene.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2owjmuiws.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2thvhkgrz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfqhnxu.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrxygyx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gttmzzvb.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ndoveact.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpatohxo.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vmejyqmw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2htaubelg.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yanggqhz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgouzhd.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2erafbkbe.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkwgusx.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmwoiep.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cghvacbj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hebfzrmm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzasqdds.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mwabnnkf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhytbzvr.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhduhvj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwaququ.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zbiofxgc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2snilrixu.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vbezvwjy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fclgbera.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2whutizko.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bickzwlc.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzchzui.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwbkefu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pwepeoul.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvssnaan.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yytvyojq.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxznbwd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwnazcx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgkyorg.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2etjpotzr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yadxdzes.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyzhcva.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzeizhvi.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvbajqw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmhlkal.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxvjyrk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnidwwp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdvczvo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsnsrpb.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2dreicxtf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eztqvoxf.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwkyruj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuhmtfy.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkkqfzf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2setuthwt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlveifg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxvfnow.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuizahq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zicbtkcw.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2fboznecl.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2gixrclgl.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2luajszmy.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cpehzvzs.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kixcaeju.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfroybbo.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mqghdctz.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2srjaextp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bncerzxk.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aygxhmoj.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjardku.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrnezhu.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwrfdky.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwegtjxe.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fsslzmpg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eftooeys.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kdacoqbd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlujkov.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbywzwb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfjruag.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbdxhba.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlslztnv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqdsdkv.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlfcuwe.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqdlurw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2drmqbhzd.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2twjayepm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmpqutc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgebwhei.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrxxsji.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqooopvn.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ipheggkh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgwqumx.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2lhaqauey.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggocoqyv.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uegkolzt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2omcypvnh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2djjaqbdf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mlppjtgo.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dxztruux.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cugpyrbq.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qsptqjld.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvljdcy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2caoymemo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogknupgq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfqpjcf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpymhbd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjdnzqq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwwzlfp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpqpumg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxviins.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dothjhsw.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhpkeuq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqoycaq.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvlukiv.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pcllxldf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2adlibmbm.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjujckyd.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbebgbd.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2quyrjrjm.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jaiampmh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2reajvktp.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xniecccv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2sffhrdqx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ddeltdgr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqzabgh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2edaywxjc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2orqwxnxs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzckinj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvcqxfh.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyfwefo.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzaeuno.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxgyiqb.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmivnnwl.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2pwezcdmg.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjfotcl.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2oriwfzgi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2attyphvs.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2txlgkpgo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcowpfn.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbquqzl.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlzarzo.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2guopyucz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnajfkzp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgkyrvt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsmafic.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfxobzb.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfphbsi.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2etnmccwb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuwcqyq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2spxpzlml.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdyxhau.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rclqtxkt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2plykyzbe.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrasled.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjfvxfd.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgjlrkl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrxeidt.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2dsultjzn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkwwras.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2seihsdrm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdrword.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xecpkxyb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpzocwi.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkzybux.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzofkzm.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2rwltnyyy.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpktudw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fuftxlbq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2fraejcet.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrivckn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkigdfr.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuiseqw.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2alznguog.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzzhrha.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qidvcact.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlniinc.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2dptpwpsl.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzqdxca.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oaocushu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbpgttq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2dpaszekd.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cbavupad.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnfootr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2iolsdzys.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayadwlvw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyvecoy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvcdsjo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkebotz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqiahtlc.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyoobpu.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbyghmi.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrjtlnn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iozvjhsj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxmyhqj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umwtvuvl.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rarfkwfk.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmzmkum.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kowptqds.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2mlljtoqm.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwrgliv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cicahtgx.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgpapcd.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrvqxrx.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2eyskstsq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmcjjds.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtbjlgb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcomegle.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lmeguucv.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnqanvc.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxclkas.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzmbroc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjlodfe.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2icjmtfbc.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2leqtqfcd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gftrllvd.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbiehgu.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zucyevzo.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2echniozd.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmjggrs.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2jvoinbmt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bspeyxbk.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbjjatk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2swlacwet.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2aaimrezv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntatfxtn.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbckkbi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jejvhtak.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2busnmtos.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcvtper.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrisota.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtixuyf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yeiuaxsn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkvznto.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qzszjkll.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcezwwcc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wyspdyxr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqmdkax.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtlhldv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwwuncr.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfmxove.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzmwrdy.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2elmqortv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2khcbxskr.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrwyaak.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhfjjrv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yxergcpk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbgnmro.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2izcqeukf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jscxnnsb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdtildv.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2bawhpggk.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cfceotyl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtffopm.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2irfajnsq.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvaukhw.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxluxay.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkugjov.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2oabxiude.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2bybtqoss.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nggkctdx.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwxyhdk.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2duhnmaff.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtptadt.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxuemoh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2jomshajo.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2samfgfkt.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qeykcved.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpgfyhu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvlxcnd.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2yofocaus.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2oazzyoqo.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2igdhubnc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqrifts.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyuvijs.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwuwzcp.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yxywefej.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvfcedp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bftjwqef.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsvluus.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2atzxhdha.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hktgstoq.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2eslghkkq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bchhltij.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqnjjfs.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtxxiaq.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ezczqlfv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrmvegb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvpfhwo.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuqevhl.html


<!-- 参考信息 -->