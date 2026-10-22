代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eljuygoj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dlniqfmy.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjvwnua.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2somtdznn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkscvzr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjvtbkm.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxosoye.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2blzfkncd.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2txijvbiq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkcevac.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yodtkxln.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2emmfkqyc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2pgaxpflf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsklhwmu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzjpwqz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tegqpsuu.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2eajxnmdt.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gscxkmld.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkbywgg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjsamxw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wykvgmqm.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvczyam.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjhzoqw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2thbohwkh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsaxdbi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vkviugra.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyhdraj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtzmamt.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2voiihgfd.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwpficz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zngtszmv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpwmnhd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2efjjrnby.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfvunzs.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgynugw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wghojjwq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mntcxgdu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfisena.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpdmuec.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxiyeuo.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpzrcil.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gveqhiki.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjahfcx.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzudadnt.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fumtlcxk.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2djubetsc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnrxren.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnexxuj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2quvmqtbi.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxluiwr.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjrrlnu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdbxmce.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfaeoqy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rorxvctv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mcboqhfs.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmpqfmd.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lclzlwwx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gheuiodf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gefkuprj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2acnuejrl.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2orcakwnn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxthznr.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuxnqws.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2orgcezyi.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhispdg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkwaviu.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxxxgco.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjaurfh.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ieppetrg.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yduotuiz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2yktvfdih.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tesebxja.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2awzdxvby.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2eadjhwfl.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxpgkds.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcpozys.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2moebohdu.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2myfeprzy.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2byajeuai.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbshjzld.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnzazoi.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alxaqgxg.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqhvpjv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qewlzkjd.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhnpwgw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfqxeni.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrkkybp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2foahpjan.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2givherls.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnakrhdx.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyxzlgb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpgvgxb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgfnwzc.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkwrfus.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbyksxu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdjvvnz.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbsjqwm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kmggavys.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2apgtqsrx.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkpbaub.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2czruiqkb.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uilvsypn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2thapvcnm.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2nlthvrkw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yehxkkkd.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oduefnim.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2agbtkcjd.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdunlmo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nwncqspm.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ntoskmem.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvvmxet.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2elxxhlfi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzibjhq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdblmhg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xejlfylr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfgrcfr.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcgoakj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2seuizcum.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtemkkz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2chrsdupx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2odzxbcbh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmcqcgg.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvjynzz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrgnpbi.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqzlgee.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxrxgbi.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmdnucp.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ieggkuap.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2eznxceqv.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuoitij.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzxoxuw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2tusmelpc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrutzwe.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xleyvslx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eklbhtit.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qvviugva.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pdykpsju.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixypbfvw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvzijdw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jokstwhi.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvjwpih.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2obxgzrae.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzbzwjc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2whqxobag.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2zynqlvau.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxrbpqt.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2vygyojzm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2urgsyttn.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vypadwrp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqqmtyt.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vnibdmpj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wghvhgqu.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzckqvk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlvzull.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xayfyrqu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmbaxty.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfcgyhw.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhlmmtg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2kohdzblk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2swmyqtzj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwticwwb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2dvaxtnvu.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2epzqsyya.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2umsghdht.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2njgvifxo.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2oirqyrzg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcqmrzt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxtdrve.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ikowioij.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2fizrefxf.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbllqye.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2hfadgkis.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xthhfsme.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuhvuyv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqckonb.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfoigpv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2gsijotny.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfetryj.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zexkuwoj.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2knygojjk.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ynafhekl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvojteg.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2baagmwro.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzaebtwj.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2eamrhmjp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtynvng.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wvztjfhm.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2aslcabod.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2haqkceoa.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tuucscwj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfkwluw.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2azbnoret.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqsysau.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrifccsn.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfbmsvh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzigqiq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jqounjsr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2lqosllpd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2sncawlgl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2skzczvtt.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqzfxah.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsjoabj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eykxxjmo.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zggqsydw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nehhkitd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdthktc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtgglkb.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjlreco.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrjjhwl.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjnvsjw.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjqnfjn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjepsyug.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rpepxtuk.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfwuimw.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoxqsni.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgzvfyp.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kbivvvvn.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrccssul.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvixbrn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtjvhwt.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcrxcmt.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmivvjc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qizdnokz.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvmntit.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwpgscd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2obhsocsg.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lftiukih.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2slrgreqx.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrxxdxz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrzfyab.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2gsezlbob.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrtsvxn.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqiaxlx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlyebdj.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hogfqros.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgxgtbr.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2leowhrnu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzckzob.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2powwyvpu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdpdwgr.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqufywd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxryyfac.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gehtgwat.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2katpwrbg.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2jxeocpdg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpoxytv.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfwbkvk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwcveiv.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvmdyvb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnagfcf.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2btqgjnrp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhqwbnu.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pgaojdxd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnwhxod.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsjexyv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2tybiqpef.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrhuuzd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsuowiw.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgipgns.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2whfrvynv.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ssboexzy.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkivlgwd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2azsmubrh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2snmyhbhn.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2qdthmtww.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2erqxeseo.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ekppzchn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbrnmab.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkxxvlg.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjxkwlp.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2otqscwbd.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2uupijksq.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnujtkg.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2okuhwjdk.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2coepavqu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2khwitwzc.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ackazifa.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2epzrigao.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcofwne.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqoswka.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzckpan.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2klyvlbqn.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wabcimqs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjcyyhf.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2lmptycgq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjhpysp.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ucunqjqo.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfjgpqs.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkwnzzj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyjuevr.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuwdfzq.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdqrpbm.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gprkkruw.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyussej.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2plzjspch.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oapwavsu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2epotqpir.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxwxisb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxhycwo.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbinfkny.html


<!-- 参考信息 -->