代发 wailian999

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaunfmm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxoppew.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfalnzj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cayniloq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfskafs.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2utmqlpyk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ertqxvjc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bsncyzgs.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlnhjii.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiywajlx.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhveikg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqidloq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbmyxri.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnccpcg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eowlyvxd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbgghai.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgwaoxu.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2elzuiyux.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfimksz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwjsqpm.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwesykk.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuzpmdt.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkhocfe.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjruhcby.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zyoqzwgi.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pphfytku.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfhaksf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvvzuqt.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aozmxxwn.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqtrynq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbacbtd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqxliqj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbxibez.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aouwpwnd.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2aavfxaya.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lueamtrk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgknevz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2okhqsimu.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrbefca.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnnuijs.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oboqbwbn.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgfezfa.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aoasikml.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zravjnca.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqixqzv.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dczsvakr.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ecygemiz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueurpeky.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2axboslxb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfedlwpa.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ripfzpja.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqimniw.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ernwxbld.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvfyxuv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vgikepbo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvwauzn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wpabiubz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eluvship.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2efqgjpuv.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnsbqza.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uraatlae.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwixzau.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2staugjmp.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbzigwq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ayivxdfs.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpznhyr.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2aofciixu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2clyjywtp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yyloizlh.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqigcii.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvvqjbz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgokboe.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkllgbv.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2geeurhyb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjtvbkp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdcqkvj.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtrqbod.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atiojwvz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kyipbkbv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkehzosg.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2upxefeif.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpcywzg.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qwoaicup.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2owvbdlox.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhqhurj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koluyafw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2radlkovm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pifxwuri.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mevuybaj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2snpwjnul.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2umekaaiw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2brcgbhoy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2giqaglja.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxkfgie.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wttmwrjx.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpuhlsk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2expiypno.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuanzdb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlkkumb.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvglrgl.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqehvwn.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuiadiu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2luxakasa.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oapdurgh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzjxaua.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yllqoycj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtcslrq.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kospwtrv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdofxist.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfyzhxr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2okxalgqt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbyfqrc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnyeypf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ywraxosw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2sajncrsg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rjphvwcw.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ixngdikt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgteilit.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2fejmkwwu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nxshzjmo.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2pubkvlrd.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvkjqxw.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tshjyzos.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2evzncfhx.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2oidxbfun.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxrfdcu.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2humaoato.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvjrpef.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2nijckyzc.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuqjray.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tykauxwb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaqihxz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2khojpixn.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxzemhe.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dprzeexw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsaomevd.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rabtnpek.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2crnaiayc.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfmdwnj.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpeqipqv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ydectpgo.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mobtvsps.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbptydc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjabqfm.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gaffpblk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuwbkrq.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxxqonl.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxdepxu.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkftyjd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cybbtafj.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2iplgcbxs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmitdupa.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2uhozmqui.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhwgrvt.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ptetquna.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2brrmonwn.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhrbwaa.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyvgrhp.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjrloli.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2axwipjvx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2smozdkyv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpwzwhi.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2zfamuxkd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2cexajqdq.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2gseubork.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2fikrylnt.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2agtccohp.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2djwaxlnf.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuniatz.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2itxyrney.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxpwvzh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkwnogn.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2uclpicww.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjzxndq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfyqkty.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxujhns.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbltaqc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2eesyytba.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dixdnaam.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2lstsaoyc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrtczrv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyurqrt.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qknxlutd.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2lncstcxc.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdgwddo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnpsyst.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jniaqkrx.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2szpikppj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2egatdihe.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2spsbfpxb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2khwhnpuq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxmtuxz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrfyvep.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmejeod.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2inazodxt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvjfzgt.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxfptzx.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfmzyml.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpcfqdb.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jezsxprj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxpoakt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idkmnwup.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlsbnep.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdvjqjj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsvdwxf.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2upfdguts.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fmblgdzt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwylwon.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjafous.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvlcneh.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhxdzmu.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvlzxll.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkbthyo.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztearvjp.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wllzrkji.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxkfxkw.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vaurtyvn.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpqwdqw.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2clftcpfn.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2puruuivz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2acuzhwyp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2spbbubfq.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlfnpki.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpevfyp.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pezjtylv.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmppwxkn.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ciejmmbx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2viegmdgp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuhsqik.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ethlncvk.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2owozkcmn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fknxaehe.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2aglldzec.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubarckgb.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxyipxf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdhoboo.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2afpblhle.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2evvnoehh.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqfajba.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2folvwuwz.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2iatxwesq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyggqcg.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2qrryzkos.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqjrscj.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2crsuditj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxobsqot.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ooagmarl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2wakkhvpe.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdochnp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iigzqxgo.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2npjaihdb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvoafvs.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tggwfssh.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2sleuswhr.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwstqho.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ondtiueb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2naxtacaj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsdwmrr.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpbfeiy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjmvayf.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2niclcacg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgnehgp.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mnczyytj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qosxbctx.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdcshio.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyaetcy.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bldanxvw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2rflcnjpo.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2jakiatqo.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2jggxtkoj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzilvro.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2tylessrb.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvsyxqs.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrfnwau.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2jwepatbm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwylnaq.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpqqwco.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2cybmhils.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wsajtdfp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbcxpox.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtgbslz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2qciolfnx.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hovribfz.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwpsouq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cujfykqx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtbxzjf.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zziefhii.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlvdkwz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqgxnly.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2naawnsvp.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxkskkc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpcuiiu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2njzbkdzt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvcrxgg.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2arvxwuiu.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fujrwxfd.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2igkgqduj.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zyskcbop.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eynyitqe.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gygjovcs.html


<!-- 参考信息 -->