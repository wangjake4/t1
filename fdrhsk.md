代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.hywenlv.cn/Article/details/gtkmvcswqb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.snrcjt.cn/Article/details/gtjqkbrlpm.html

[T06] Kotlin：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gtbqgvripk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtpjbxrfhk.html

[T07] Kotlin：集合过滤
来源：http://dali.ybcxt.top/Article/details/gtlncgkmvp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hysaishi.cn/Article/details/gtmmlefucz.html

[T08] Kotlin：数据类
来源：http://dali.yuxming.cn/Article/details/gtnmfndido.html

data class User(val name: String, val age: Int)
来源：http://dali.zdqjudy.top/Article/details/gtycmkzgwq.html

[T09] Kotlin：扩展函数
来源：http://dali.yueranfly.top/Article/details/gttqbkijiy.html

fun String.exclaim() = this + "!"
来源：http://dali.aibaodan.cn/Article/details/gtrlkatlgj.html

[T10] Kotlin：默认参数
来源：http://dali.hywenlv.cn/Article/details/gtfnevaigx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.svipenyu.cn/Article/details/gtjtgezhfy.html

[T11] Kotlin：协程
来源：http://dali.guowangkeji.top/Article/details/gtybuvpvxk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigfzy.top/Article/details/gtxzmpjjqt.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigfzy.top/Article/details/gtedshrzoj.html

val (a, b) = Pair(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtgzkflgba.html

[T13] Kotlin：只读 Map
来源：http://dali.zhiwuduotai.top/Article/details/gtlbajhdwc.html

val m = mapOf("a" to 1)
来源：http://dali.redwolf501.top/Article/details/gtaivautwa.html

[T14] Kotlin：循环
来源：http://dali.cdnleiting.top/Article/details/gtysfsrbgr.html

for (i in 1..10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtwjniugqs.html

[T15] Kotlin：接口
来源：http://dali.yueranfly.top/Article/details/gtzqtkgbpw.html

interface Shape { fun area(): Double }
来源：http://dali.guannengcc.top/Article/details/gtsscgnskf.html

[T16] Swift：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtmceakjdg.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxclxrvz.html

[T17] Swift：变量与常量
来源：http://dali.chenzaomai.com/Article/details/gtcsglilkd.html

var a = 1;  let b = 2
来源：http://dali.redwolf501.top/Article/details/gtkrdlisqn.html

[T18] Swift：字符串插值
来源：http://dali.yuxming.cn/Article/details/gttdtdktwq.html

"值: \(b)"
来源：http://dali.cashguo.top/Article/details/gtcuejlsrw.html

[T19] Swift：可选绑定
来源：http://dali.c1oappe.top/Article/details/gthkonpfxi.html

if let n = opt { print(n) }
来源：http://dali.redwolf501.top/Article/details/gtuogfjsxt.html

[T20] Swift：数组操作
来源：http://dali.cheryme.top/Article/details/gtjjydwhte.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zycfv.cn/Article/details/gtvjwvlkfl.html

[T21] Swift：遍历
来源：http://dali.wangdashe.top/Article/details/gtbqedmsgt.html

for x in a { print(x) }
来源：http://dali.chenjidiqi.icu/Article/details/gtkywhhhok.html

[T22] Swift：字典
来源：http://dali.jinqigfzy.top/Article/details/gtycobflff.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnqzz.top/Article/details/gtlwvrclsa.html

[T23] Swift：函数
来源：http://dali.havefunace.top/Article/details/gthfzxotmd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xinyue.icu/Article/details/gtrxhbfmgk.html

[T24] Swift：闭包
来源：http://dali.yj20258888.top/Article/details/gtcyculggw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gotoacloud.top/Article/details/gtruglyvfq.html

[T25] Swift：结构体
来源：http://dali.sweek.top/Article/details/gtgfqqfohi.html

struct P { var x: Int }
来源：http://dali.yuxming.cn/Article/details/gtiaocuyml.html

[T26] Swift：类与重写
来源：http://dali.smart0.xyz/Article/details/gtsofdtrvc.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gtkeepgnnb.html

[T27] Swift：错误处理
来源：http://dali.aibaodan.cn/Article/details/gtbnxuexlk.html

do { try f() } catch { print(error) }
来源：http://dali.tianlin.xyz/Article/details/gtfzspvvrq.html

[T28] Swift：枚举
来源：http://dali.yongpay.top/Article/details/gttmozdwos.html

enum Color { case red, green }
来源：http://dali.xinyue.icu/Article/details/gtyqduoekw.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxuanxn.top/Article/details/gtauxxqlaa.html

guard let x = opt else { return }
来源：http://dali.sxryk.cn/Article/details/gthtjoehxc.html

[T30] Swift：协议
来源：http://dali.quarkkingdee.top/Article/details/gtiqexyvkz.html

protocol Shape { func area() -> Double }
来源：http://dali.hongshengwenyu.top/Article/details/gthhqrxrcg.html

[T31] Lua：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtpzslvxzx.html

print("Hello")
来源：http://dali.shuidangran.top/Article/details/gtioaelwfk.html

[T32] Lua：局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gticcyhlet.html

local a = 1
来源：http://dali.wangdashe.top/Article/details/gtdjwenikq.html

[T33] Lua：表（数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtnrlakyei.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guowangkeji.top/Article/details/gtmtmmwcoj.html

[T34] Lua：遍历表
来源：http://dali.xziqi.cn/Article/details/gtqwxajvzw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zdqjudy.top/Article/details/gtbbrrzcks.html

[T35] Lua：字典表
来源：http://dali.mhx1999.top/Article/details/gtrjusllqc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ppjwa.cn/Article/details/gtrnieyhae.html

[T36] Lua：函数
来源：http://dali.guowangkeji.top/Article/details/gtcbyxrmgj.html

function add(a, b) return a + b end
来源：http://dali.chenzaomai.com/Article/details/gtvqkdhvlk.html

[T37] Lua：字符串拼接
来源：http://dali.chenzaomai.com/Article/details/gtlnduatzp.html

"a" .. "b"
来源：http://dali.nanxinkj.top/Article/details/gtjbsmdmzy.html

[T38] Lua：条件
来源：http://dali.hnqzz.top/Article/details/gtqrwbhtxx.html

if x > 0 then print("正") end
来源：http://dali.chenjidiqi.icu/Article/details/gtvrixueec.html

[T39] Lua：模式匹配
来源：http://dali.zhengqikj.top/Article/details/gttcynkatz.html

string.find(s, "%d+")
来源：http://dali.yueranfly.top/Article/details/gtdbbfxyzy.html

[T40] Lua：元表
来源：http://dali.gogol.net.cn/Article/details/gtemretzic.html

setmetatable({}, { __index = base })
来源：http://dali.hammf.cn/Article/details/gtxvdfnlkf.html

[T41] Perl：Hello World
来源：http://dali.fzhhl.top/Article/details/gtyyimtkvr.html

print "Hello\n";
来源：http://dali.yuxming.cn/Article/details/gttsshpmbk.html

[T42] Perl：变量类型
来源：http://dali.xuanzx.com/Article/details/gtymlzwddu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.haohaochexian.top/Article/details/gtdfskpnir.html

[T43] Perl：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gtluxhlnki.html

"值: $a"
来源：http://dali.yj202588.top/Article/details/gtacgfualf.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gtpfjpbsdc.html

if ($a > 0) { print "正"; }
来源：http://dali.cheryme.top/Article/details/gtjoubgkpq.html

[T45] Perl：数组遍历
来源：http://dali.sufxvd.cn/Article/details/gtrdjmoqig.html

for my $x (@arr) { print $x; }
来源：http://dali.redwolf501.top/Article/details/gtitekvqer.html

[T46] Perl：哈希操作
来源：http://dali.sysykeji.top/Article/details/gthlqpgcfp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yangfankeji.com/Article/details/gtnacrtsov.html

[T47] Perl：正则捕获
来源：http://dali.yuxming.cn/Article/details/gtydwlbzsj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.iojbl.cn/Article/details/gteqcofudd.html

[T48] Perl：正则替换
来源：http://dali.svipenyu.cn/Article/details/gtoihbwegl.html

$s =~ s/old/new/g;
来源：http://dali.cucudq.cn/Article/details/gtrhcjrhen.html

[T49] Perl：函数
来源：http://dali.gotoacloud.top/Article/details/gtdldziskb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gtjvwnjntt.html

[T50] Perl：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtjdjjmjcp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hfpthk.cn/Article/details/gtojtbwdyz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gotoacloud.top/Article/details/gtrdcgpjkp.html

[T51] Scala：Hello World
来源：http://dali.wangdashe.top/Article/details/gtdlwhmmbb.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gttkuczafe.html

[T52] Scala：变量
来源：http://dali.pycfn.com/Article/details/gtdjzzuwad.html

val a = 1;  var b = 2
来源：http://dali.gotoacloud.top/Article/details/gtiapvpbxc.html

[T53] Scala：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtulecavfi.html

s"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gtmxruktof.html

[T54] Scala：集合映射
来源：http://dali.aibaodan.cn/Article/details/gtlkcuhtbi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtipkahbed.html

[T55] Scala：集合过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtgztryjnh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.kuanghao11.cn/Article/details/gtkfsnflzl.html

[T56] Scala：样例类
来源：http://dali.chenjidiqi.icu/Article/details/gtlpajazsp.html

case class User(name: String, age: Int)
来源：http://dali.mhx1999.top/Article/details/gtoxyvqopf.html

[T57] Scala：模式匹配
来源：http://dali.gzhubu.top/Article/details/gtyhaijxbl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.daxiang520.top/Article/details/gtalxquirm.html

[T58] Scala：函数定义
来源：http://dali.quarkkingdee.top/Article/details/gtacjxhqxu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hysaishi.cn/Article/details/gttukuesly.html

[T59] Scala：循环
来源：http://dali.tanke756.top/Article/details/gtywsgieax.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gtejrflpqv.html

[T60] Scala：折叠
来源：http://dali.ydzc1.top/Article/details/gtnpztitnw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhoulong.xyz/Article/details/gtjunzsrrp.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtehvcltks.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gtiocnopyz.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtprbhcyib.html

[U01] Py：创建虚拟环境
来源：http://dali.yongpay.top/Article/details/gtctuyjbag.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.feifeiyinyue.top/Article/details/gtrjwvwjec.html

[U02] Py：导出 / 安装依赖
来源：http://dali.smart0.xyz/Article/details/gthclyidkh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nwbrower.top/Article/details/gthznjdjuf.html

[U03] Py：加载 .env 配置
来源：http://dali.birdmap.top/Article/details/gtmspwytxn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gzhubu.top/Article/details/gtqwcpkegw.html

[U04] Py：变量调试打印
来源：http://dali.ivvv.top/Article/details/gtilnkomjm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenzaomai.com/Article/details/gtaotcckyn.html

[U05] Py：列表去重且保序
来源：http://dali.cucudq.cn/Article/details/gtuivvaobt.html

list(dict.fromkeys(arr))
来源：http://dali.xuetiantiany.cn/Article/details/gteblomkpv.html

[U06] Py：合并两个字典
来源：http://dali.andypj.xyz/Article/details/gtfbizjydb.html

{**a, **b}
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtfremdv.html

[U07] Py：反转字典键值
来源：http://dali.zhixingplan.top/Article/details/gtqkbdoktf.html

{v: k for k, v in d.items()}
来源：http://dali.ybcxt.top/Article/details/gtqermcztl.html

[U08] Py：展平二维列表
来源：http://dali.ivvv.top/Article/details/gttzonzlse.html

[y for x in nested for y in x]
来源：http://dali.hnqzz.top/Article/details/gtvydwvahi.html

[U09] Py：字典取最大值的键
来源：http://dali.sweek.top/Article/details/gtxvjmfonb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gtqqpfxstq.html

[U10] Py：按值排序字典
来源：http://dali.chenlongwang.top/Article/details/gtvgvjqqre.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jiagoushi.top/Article/details/gtdrweklrv.html

[U11] Py：生成器表达式
来源：http://dali.nwbrower.top/Article/details/gtavogtrae.html

(x * 2 for x in arr)
来源：http://dali.redwolf501.top/Article/details/gtukhwuqmi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.redwolf501.top/Article/details/gtrfagfwql.html

Counter(arr).most_common(3)
来源：http://dali.hfpthk.cn/Article/details/gtigmvtmah.html

[U13] Py：固定长度队列
来源：http://dali.feifeiyinyue.top/Article/details/gtrbypivzd.html

deque(maxlen=10)
来源：http://dali.yonumen.top/Article/details/gtjmwewxju.html

[U14] Py：分组收集到列表
来源：http://dali.iojbl.cn/Article/details/gtfsjcuyjh.html

defaultdict(list)
来源：http://dali.ivvv.top/Article/details/gtbdqjtcdo.html

[U15] Py：高精度计时
来源：http://dali.jinqigfzy.top/Article/details/gttcuxzcgq.html

t = time.perf_counter()
来源：http://dali.smart0.xyz/Article/details/gtmdtedfdg.html

[U16] Py：命令行参数解析
来源：http://dali.xziqi.cn/Article/details/gtmaojujqo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aibaodan.cn/Article/details/gtzsfkgojr.html

[U17] Py：初始化日志
来源：http://dali.fzhhl.top/Article/details/gtyewbklny.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ydzc1.top/Article/details/gtzkyucqds.html

[U18] Py：预编译正则
来源：http://dali.jinqigufen.top/Article/details/gtoqeyhwmk.html

pat = re.compile(r"\d+")
来源：http://dali.yongpay.top/Article/details/gtoojjtgce.html

[U19] Py：正则替换带回调
来源：http://dali.chenzaomai.com/Article/details/gtoslxenqq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.wangshuangyany.cn/Article/details/gtycpztvef.html

[U20] Py：缓存函数结果
来源：http://dali.ybcxt.top/Article/details/gtrxrdknml.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tianlin.xyz/Article/details/gtqaheofwf.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfoqvrxj.html

@contextlib.contextmanager
来源：http://dali.shuidangran.top/Article/details/gtkvtwkfnt.html

[U22] Py：矩阵转置
来源：http://dali.shangyingyoupin.top/Article/details/gtjokzpuww.html

list(zip(*m))
来源：http://dali.xinyue.icu/Article/details/gtvsigffmk.html

[U23] Py：分块读取大文件
来源：http://dali.cucudq.cn/Article/details/gtlxninewe.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jlsjyb.cn/Article/details/gtphxudllp.html

[U24] Py：路径操作
来源：http://dali.jlsjyb.cn/Article/details/gtwtlgxpfc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gttcobllnd.html

[U25] Py：CSV 按字典读
来源：http://dali.shangyingyoupin.top/Article/details/gthninzhae.html

csv.DictReader(f)
来源：http://dali.sysykeji.top/Article/details/gtvvrkbnvg.html

[U26] Py：并发下载
来源：http://dali.tianlin.xyz/Article/details/gtnwmhdgch.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cqqwz.cn/Article/details/gtrhakjnyq.html

[U27] Py：异步 HTTP
来源：http://dali.aizwys.cn/Article/details/gtrfxpzkjk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuylldfni.html

[U28] Py：类型别名
来源：http://dali.mhx1999.top/Article/details/gtwkumubgv.html

UserId = int
来源：http://dali.hnxiangtu.top/Article/details/gtwnfeikmj.html

[U29] Py：属性校验
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpqwtaji.html

@property 与 @x.setter 配合
来源：http://dali.zhongyouzk.top/Article/details/gtbktjetoa.html

[U30] Py：数据类
来源：http://dali.hysaishi.cn/Article/details/gtvxefwrhm.html

@dataclass(slots=True)
来源：http://dali.bjfxy.top/Article/details/gtcfsymmvz.html

[U31] Py：单测
来源：http://dali.jqgfzy.top/Article/details/gtdoxdopjc.html

python -m pytest -q
来源：http://dali.9152youxi.cn/Article/details/gtxsvjmvev.html

[U32] Py：代码格式化
来源：http://dali.chenzaomai.com/Article/details/gtlatmoatw.html

ruff format . && ruff check --fix .
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttrbvqcb.html

[U33] Py：打包发布
来源：http://dali.daxiang520.top/Article/details/gtpigydzyp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shzxlz.cn/Article/details/gtwgkwabll.html

[U34] Py：判断编码
来源：http://dali.zhoulong.xyz/Article/details/gtizdgkpjy.html

chardet.detect(raw)
来源：http://dali.xziqi.cn/Article/details/gtgnboudfi.html

[U35] Py：发送邮件
来源：http://dali.xinyue.icu/Article/details/gtcxtbxvew.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yuxming.cn/Article/details/gtbmcetndi.html

[U36] Py：定时任务
来源：http://dali.yvedp.cn/Article/details/gtgazzwhcu.html

schedule.every(10).minutes.do(job)
来源：http://dali.pengpengdd.cyou/Article/details/gtombeloqk.html

[U37] Py：读写 Excel
来源：http://dali.0kj1m.cn/Article/details/gtoznasnih.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.fzhhl.top/Article/details/gtokvdwbrp.html

[U38] Py：获取脚本所在目录
来源：http://dali.chenjidiqi.icu/Article/details/gtcgjzcsmw.html

Path(__file__).resolve().parent
来源：http://dali.fzhhl.top/Article/details/gtlhlvpmuc.html

[U39] Py：判断是否在交互环境
来源：http://dali.pycfn.com/Article/details/gtskmabiqq.html

sys.stdout.isatty()
来源：http://dali.tian-w.cn/Article/details/gtrjutytme.html

[U40] Py：打印到标准错误
来源：http://dali.aizwys.cn/Article/details/gtegsqhpqe.html

print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gtvsfgeahc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.aizwys.cn/Article/details/gtpkuczyfo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hnqzz.top/Article/details/gtbtczzosf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.andypj.xyz/Article/details/gtcrifwbas.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmsakhvw.html

[U43] PHP：声明命名空间
来源：http://dali.meibo888.top/Article/details/gtqzuwmtuu.html

namespace App\Http;
来源：http://dali.hnqzz.top/Article/details/gtewquxenl.html

[U44] PHP：开启严格类型
来源：http://dali.zhongyouzk.top/Article/details/gtlfddoppk.html

declare(strict_types=1);
来源：http://dali.yangfankeji.com/Article/details/gtwyrlifjg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.tian-w.cn/Article/details/gtogekmvix.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gttwhfibkh.html

[U46] PHP：可空类型
来源：http://dali.wangshuangyany.cn/Article/details/gtnynwvubu.html

?string $name = null
来源：http://dali.pycfn.com/Article/details/gttvqqjawg.html

[U47] PHP：联合类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqulioghv.html

int|string $id
来源：http://dali.sufxvd.cn/Article/details/gtaidrvjuz.html

[U48] PHP：纯枚举
来源：http://dali.jianghu66.top/Article/details/gtdxliscbx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nwbrower.top/Article/details/gtlhfsluln.html

[U49] PHP：只读属性
来源：http://dali.chenlongwang.top/Article/details/gtggcogsta.html

public readonly string $name
来源：http://dali.iojbl.cn/Article/details/gtsntfvyxr.html

[U50] PHP：构造器属性提升
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaswvzwyl.html

public function __construct(private int $id) {}
来源：http://dali.yanxiufei.cn/Article/details/gtktnjhvxl.html

[U51] PHP：数组解构
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcskssvs.html

[$a, $b] = $arr;
来源：http://dali.kuanghao11.cn/Article/details/gtqwutswey.html

[U52] PHP：箭头函数
来源：http://dali.hnqzz.top/Article/details/gtjolgftdf.html

$double = fn($x) => $x * 2;
来源：http://dali.c1oappe.top/Article/details/gtygrmhatm.html

[U53] PHP：空合并运算符
来源：http://dali.shangyingyoupin.top/Article/details/gtmdwbvfhx.html

$v = $a ?? $b ?? "default";
来源：http://dali.cucudq.cn/Article/details/gtxjpgkxyt.html

[U54] PHP：空安全调用
来源：http://dali.cucudq.cn/Article/details/gtlfrbpwdq.html

$obj?->method()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnujtajl.html

[U55] PHP：match 表达式
来源：http://dali.jyoumei.cn/Article/details/gtbnwmvstt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.gzhubu.top/Article/details/gtrrplxkzh.html

[U56] PHP：命名参数
来源：http://dali.ybcxt.top/Article/details/gtnrsrbmpv.html

f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gteukochgk.html

[U57] PHP：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtntgkgdvy.html

"值: {$a}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqbzdoxl.html

[U58] PHP：数组三件套
来源：http://dali.jlsjyb.cn/Article/details/gtzcsemajx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtogwhfwya.html

[U59] PHP：自定义排序
来源：http://dali.zhoulong.xyz/Article/details/gtgplczisu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ybcxt.top/Article/details/gtmoxbbguq.html

[U60] PHP：JSON 编解码
来源：http://dali.yongpay.top/Article/details/gtmkozmruj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hfpthk.cn/Article/details/gtplurynpc.html

[U61] PHP：正则
来源：http://dali.hongshengwenyu.top/Article/details/gtghbmmynm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sysykeji.top/Article/details/gtlyeccpdi.html

[U62] PHP：日期对象
来源：http://dali.guowangkeji.top/Article/details/gtnrdiumva.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hysaishi.cn/Article/details/gtazjzdins.html

[U63] PHP：文件读写
来源：http://dali.zdqjudy.top/Article/details/gtcjtvaxiw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhoulong.xyz/Article/details/gtmdpqobid.html

[U64] PHP：目录遍历
来源：http://dali.yangfankeji.com/Article/details/gtrzqyiusx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.aizwys.cn/Article/details/gtmjtujoxu.html

[U65] PHP：会话
来源：http://dali.wangshuangyany.cn/Article/details/gtorjdtxsl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtvedllqot.html

[U66] PHP：设置 Cookie
来源：http://dali.jqgfzy.top/Article/details/gtdddbxbxw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.tian-w.cn/Article/details/gtucircedo.html

[U67] PHP：处理文件上传
来源：http://dali.yuanzhike.top/Article/details/gtjxbbhtnj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gzhubu.top/Article/details/gtceajxuqf.html

[U68] PHP：PDO 连接
来源：http://dali.ppjwa.cn/Article/details/gtpljpgcuw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.fzhhl.top/Article/details/gtipwcjacp.html

[U69] PHP：PDO 预处理
来源：http://dali.birdmap.top/Article/details/gtoswyylgl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.quarkkingdee.top/Article/details/gtyxbvcdxc.html

[U70] PHP：PDO 事务
来源：http://dali.bjfxy.top/Article/details/gtmemxkyhd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.shangyingyoupin.top/Article/details/gttaamhvbh.html

[U71] PHP：抛出异常
来源：http://dali.fzhhl.top/Article/details/gthlysvugu.html

throw new RuntimeException("失败", 500);
来源：http://dali.xuetiantiany.cn/Article/details/gtgccricoa.html

[U72] PHP：写错误日志
来源：http://dali.nanxuanxn.top/Article/details/gtwcdyabek.html

error_log("失败: " . $e->getMessage());
来源：http://dali.dianchejie.cn/Article/details/gthsvczpga.html

[U73] PHP：读取 ini 配置
来源：http://dali.guowangkeji.top/Article/details/gtgphschtu.html

parse_ini_file("config.ini", true)
来源：http://dali.pengpengdd.cyou/Article/details/gtbjotkxdp.html

[U74] PHP：读取环境变量
来源：http://dali.yangfankeji.com/Article/details/gtyigazesq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqvinxyn.html

[U75] PHP：依赖注入
来源：http://dali.xuanzx.com/Article/details/gtsonhloyu.html

composer require psr/container
来源：http://dali.dashuyun.cn/Article/details/gtejrtiwbt.html

[U76] PHP：简单路由
来源：http://dali.jqgufenzy.top/Article/details/gtxmsqrrwu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jianghu66.top/Article/details/gtbjfselpb.html

[U77] PHP：模板渲染
来源：http://dali.hnqzz.top/Article/details/gtkoblakif.html

composer require twig/twig
来源：http://dali.vqdsnc.cn/Article/details/gtayqnlhjm.html

[U78] PHP：单元测试
来源：http://dali.jinqigfzy.top/Article/details/gtwpgbvtki.html

composer require --dev phpunit/phpunit
来源：http://dali.xylfe.cn/Article/details/gtnuoydcno.html

[U79] PHP：静态分析
来源：http://dali.yj20258.top/Article/details/gtyfszqoni.html

composer require --dev phpstan/phpstan
来源：http://dali.zhixingplan.top/Article/details/gtvbapxfrj.html

[U80] PHP：代码规范修复
来源：http://dali.iojbl.cn/Article/details/gtgfryjryn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xziqi.cn/Article/details/gtjfmwelvj.html

[U81] JS：初始化项目
来源：http://dali.ydzc1.top/Article/details/gtpyybdpwy.html

npm init -y;  npm i express
来源：http://dali.hammf.cn/Article/details/gtgrjfacua.html

[U82] JS：package.json 脚本
来源：http://dali.yj20258.top/Article/details/gtmkxflsvl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohlyrbtx.html

[U83] JS：ES Module 导入导出
来源：http://dali.yuanzhike.top/Article/details/gtnjxozmfn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.iojbl.cn/Article/details/gtanbsdeca.html

[U84] JS：CommonJS 写法
来源：http://dali.dianchejie.cn/Article/details/gtfizbivfm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yj202588.top/Article/details/gtujumaini.html

[U85] JS：可选链
来源：http://dali.zdqjudy.top/Article/details/gtfwaqabag.html

a?.b?.c
来源：http://dali.chenzaomai.com/Article/details/gtdmcovknw.html

[U86] JS：空值合并
来源：http://dali.hysaishi.cn/Article/details/gtkcevvdcd.html

a ?? b
来源：http://dali.yonumen.top/Article/details/gtcvnuxeey.html

[U87] JS：解构默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gtmssqpmty.html

const { a = 1, b = 2 } = obj;
来源：http://dali.chenzaomai.com/Article/details/gtdzisuube.html

[U88] JS：对象展开合并
来源：http://dali.tanke756.top/Article/details/gtelsymldp.html

{ ...a, ...b }
来源：http://dali.birdmap.top/Article/details/gtpnfirjbx.html

[U89] JS：数组去重
来源：http://dali.chenzaomai.com/Article/details/gtfapjbtgj.html

[...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gtjslcewra.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gtwgudaavx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtsbtumftx.html

[U91] JS：对象键值遍历
来源：http://dali.ivvv.top/Article/details/gtlasdwhfw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xuetiantiany.cn/Article/details/gtlzxmcbip.html

[U92] JS：深拷贝
来源：http://dali.wangdashe.top/Article/details/gtyqiscpfx.html

structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gthfybuhvs.html


<!-- 参考信息 -->