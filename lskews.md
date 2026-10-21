代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258888.top/Article/details/gtycwlxnel.html

[S59] C++：静态断言
来源：http://dali.sysykeji.top/Article/details/gtbpxvqtch.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xziqi.cn/Article/details/gtrwbowcdr.html

[S60] C++：遍历并删除元素
来源：http://dali.guowangkeji.top/Article/details/gtbzbybbje.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yongpay.top/Article/details/gttfzsqcqh.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtzblyyqfq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gtzpmyegzm.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgtogiwx.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvxslrhd.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnagqojdp.html

[T02] Kotlin：变量
来源：http://dali.xuetiantiany.cn/Article/details/gtdjbnsakh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hywenlv.cn/Article/details/gtcwbujaie.html

[T03] Kotlin：字符串模板
来源：http://dali.zhixingplan.top/Article/details/gtwhintcxb.html

"值: $b"
来源：http://dali.hnqzz.top/Article/details/gtkuceqnoe.html

[T04] Kotlin：空安全
来源：http://dali.daria6918.cn/Article/details/gthswcmwzm.html

val n: String? = null;  n?.length
来源：http://dali.quarkkingdee.top/Article/details/gtsttnqtoz.html

[T05] Kotlin：when 表达式
来源：http://dali.fzhhl.top/Article/details/gtslizavmu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cashguo.top/Article/details/gtljmpaons.html

[T06] Kotlin：集合映射
来源：http://dali.jianghu66.top/Article/details/gtdyxhgowr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtbiyhbgnf.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gtyjkecxmx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yanxiufei.cn/Article/details/gthuohlgwt.html

[T08] Kotlin：数据类
来源：http://dali.zhengqikj.top/Article/details/gtzcftpjab.html

data class User(val name: String, val age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gtztbjxmon.html

[T09] Kotlin：扩展函数
来源：http://dali.hnxiangtu.top/Article/details/gthfnovggo.html

fun String.exclaim() = this + "!"
来源：http://dali.snrcjt.cn/Article/details/gtdzgzqeci.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigufen.top/Article/details/gtailftzgq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pengpengdd.cyou/Article/details/gtyopaikkl.html

[T11] Kotlin：协程
来源：http://dali.gzhubu.top/Article/details/gtsljdxpto.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.9152youxi.cn/Article/details/gtmkomisxg.html

[T12] Kotlin：解构声明
来源：http://dali.sweek.top/Article/details/gtsidbknso.html

val (a, b) = Pair(1, 2)
来源：http://dali.hammf.cn/Article/details/gtsaxkyiug.html

[T13] Kotlin：只读 Map
来源：http://dali.0kj1m.cn/Article/details/gtqkrwmkkt.html

val m = mapOf("a" to 1)
来源：http://dali.fzhhl.top/Article/details/gthhrsdhkb.html

[T14] Kotlin：循环
来源：http://dali.chenjidiqi.icu/Article/details/gtnxqdmmps.html

for (i in 1..10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gtvmjuqdvu.html

[T15] Kotlin：接口
来源：http://dali.dianchejie.cn/Article/details/gtpjwhahqw.html

interface Shape { fun area(): Double }
来源：http://dali.snrcjt.cn/Article/details/gtopoctdzq.html

[T16] Swift：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtibvwsbws.html

print("Hello")
来源：http://dali.ydzc1.top/Article/details/gtyubjauue.html

[T17] Swift：变量与常量
来源：http://dali.ivvv.top/Article/details/gtpflluzst.html

var a = 1;  let b = 2
来源：http://dali.jiagoushi.top/Article/details/gtwxlstyzr.html

[T18] Swift：字符串插值
来源：http://dali.316326.xyz/Article/details/gtuqfwndzg.html

"值: \(b)"
来源：http://dali.c1oappe.top/Article/details/gtheblztoq.html

[T19] Swift：可选绑定
来源：http://dali.mhx1999.top/Article/details/gtljunkhlv.html

if let n = opt { print(n) }
来源：http://dali.tianlin.xyz/Article/details/gtjaovtjna.html

[T20] Swift：数组操作
来源：http://dali.zdqjudy.top/Article/details/gtrzqjsixc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ppjwa.cn/Article/details/gtopzvbufs.html

[T21] Swift：遍历
来源：http://dali.zhongyouzk.top/Article/details/gtdvowhblh.html

for x in a { print(x) }
来源：http://dali.zdqjudy.top/Article/details/gtrlblghuz.html

[T22] Swift：字典
来源：http://dali.ybcxt.top/Article/details/gtknvevlep.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.kuanghao11.cn/Article/details/gtxtwtbiua.html

[T23] Swift：函数
来源：http://dali.cqqwz.cn/Article/details/gtobwfffkn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.0kj1m.cn/Article/details/gthzsjjdpr.html

[T24] Swift：闭包
来源：http://dali.zhiwuduotai.top/Article/details/gtezvggqvh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sxryk.cn/Article/details/gtpdatfync.html

[T25] Swift：结构体
来源：http://dali.daxiang520.top/Article/details/gtjyajobja.html

struct P { var x: Int }
来源：http://dali.daria6918.cn/Article/details/gtxbstqtvj.html

[T26] Swift：类与重写
来源：http://dali.shzxlz.cn/Article/details/gtolkurwdy.html

class A: Base { override func f() {} }
来源：http://dali.vqdsnc.cn/Article/details/gtqkllaijb.html

[T27] Swift：错误处理
来源：http://dali.xylfe.cn/Article/details/gtuiseobyi.html

do { try f() } catch { print(error) }
来源：http://dali.sufxvd.cn/Article/details/gtefjkywsm.html

[T28] Swift：枚举
来源：http://dali.yonumen.top/Article/details/gtzjeuydwp.html

enum Color { case red, green }
来源：http://dali.meibo888.top/Article/details/gtrbxxqiww.html

[T29] Swift：guard 提前返回
来源：http://dali.redwolf501.top/Article/details/gtdfeohjzd.html

guard let x = opt else { return }
来源：http://dali.xuanzx.com/Article/details/gtgptwqhbt.html

[T30] Swift：协议
来源：http://dali.aizwys.cn/Article/details/gtrlqlicsg.html

protocol Shape { func area() -> Double }
来源：http://dali.jianghu66.top/Article/details/gtalsvxntz.html

[T31] Lua：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtvvpugkuy.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtvficdews.html

[T32] Lua：局部变量
来源：http://dali.0kj1m.cn/Article/details/gtkxhseujf.html

local a = 1
来源：http://dali.chenzaomai.com/Article/details/gtnqtfvcab.html

[T33] Lua：表（数组）
来源：http://dali.jinqigufen.top/Article/details/gtsjmunbyd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhengqikj.top/Article/details/gtwkxuryit.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangtech.top/Article/details/gtitgjrmuq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yj202588.top/Article/details/gthoetsqzi.html

[T35] Lua：字典表
来源：http://dali.iojbl.cn/Article/details/gtrgsojryt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yangfankeji.com/Article/details/gtuqhjucad.html

[T36] Lua：函数
来源：http://dali.hnqzz.top/Article/details/gtgvwgdqsi.html

function add(a, b) return a + b end
来源：http://dali.xuanzx.com/Article/details/gtezdbtptg.html

[T37] Lua：字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gthcjilngj.html

"a" .. "b"
来源：http://dali.yangfankeji.com/Article/details/gtgmdpwthx.html

[T38] Lua：条件
来源：http://dali.jinqigfzy.top/Article/details/gtqkchubkb.html

if x > 0 then print("正") end
来源：http://dali.zhixingplan.top/Article/details/gtwutnwell.html

[T39] Lua：模式匹配
来源：http://dali.daxiang520.top/Article/details/gtuxgessfg.html

string.find(s, "%d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwqmpwjl.html

[T40] Lua：元表
来源：http://dali.yuxming.cn/Article/details/gtljbtgmuo.html

setmetatable({}, { __index = base })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpavlmjk.html

[T41] Perl：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtinoebofh.html

print "Hello\n";
来源：http://dali.cheryme.top/Article/details/gtsjqcxxwv.html

[T42] Perl：变量类型
来源：http://dali.jinqigufen.top/Article/details/gttihgrdrt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xinyue.icu/Article/details/gtomfakwbm.html

[T43] Perl：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoahqalme.html

"值: $a"
来源：http://dali.guowangkeji.top/Article/details/gtlrrrgfxx.html

[T44] Perl：条件
来源：http://dali.feifeiyinyue.top/Article/details/gtejkheijv.html

if ($a > 0) { print "正"; }
来源：http://dali.xylfe.cn/Article/details/gtyumaklpf.html

[T45] Perl：数组遍历
来源：http://dali.daxiang520.top/Article/details/gttgabiuie.html

for my $x (@arr) { print $x; }
来源：http://dali.nwbrower.top/Article/details/gtjujvrmqp.html

[T46] Perl：哈希操作
来源：http://dali.chenjidiqi.icu/Article/details/gttxlxnpqy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.smart0.xyz/Article/details/gtzcdbwtng.html

[T47] Perl：正则捕获
来源：http://dali.zhixingplan.top/Article/details/gtfooefpec.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yonumen.top/Article/details/gtgqlrghhd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gtpnmygyxu.html

$s =~ s/old/new/g;
来源：http://dali.gotoacloud.top/Article/details/gtytyvpojz.html

[T49] Perl：函数
来源：http://dali.hnxiangtu.top/Article/details/gthfcfqwul.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtxqyeyteh.html

[T50] Perl：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtgpmaukcy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gogol.net.cn/Article/details/gteebjrtpq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cucudq.cn/Article/details/gtmeqetbwo.html

[T51] Scala：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtiznbueek.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gtdudyyqdg.html

[T52] Scala：变量
来源：http://dali.aizwys.cn/Article/details/gtunssufsa.html

val a = 1;  var b = 2
来源：http://dali.fzhhl.top/Article/details/gtnfinlhrb.html

[T53] Scala：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtazqcmail.html

s"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gtiwbwirny.html

[T54] Scala：集合映射
来源：http://dali.jinyuanbaomall.cn/Article/details/gtniysohvu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gotoacloud.top/Article/details/gtoelgjwvu.html

[T55] Scala：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gtreqzofxi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj202588.top/Article/details/gtopxdmblb.html

[T56] Scala：样例类
来源：http://dali.yvedp.cn/Article/details/gttiyxktnk.html

case class User(name: String, age: Int)
来源：http://dali.tianlin.xyz/Article/details/gtqzbrcvtc.html

[T57] Scala：模式匹配
来源：http://dali.nanxuanxn.top/Article/details/gtykgwsyuk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.mhx1999.top/Article/details/gtjnkenuzd.html

[T58] Scala：函数定义
来源：http://dali.hfpthk.cn/Article/details/gtbiaszfii.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zdqjudy.top/Article/details/gtvuqjvwfw.html

[T59] Scala：循环
来源：http://dali.xylfe.cn/Article/details/gtikcwsqyd.html

for (i <- 1 to 10) println(i)
来源：http://dali.sufxvd.cn/Article/details/gthanhfmkw.html

[T60] Scala：折叠
来源：http://dali.xylfe.cn/Article/details/gtvlmmquun.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj202588.top/Article/details/gtjtofyuli.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtgjfgqbtx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtbrfoenkf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtwosnygob.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigufen.top/Article/details/gtakkessdh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xziqi.cn/Article/details/gtfuhojddz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yuanzhike.top/Article/details/gtniumfqks.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinqigufen.top/Article/details/gtkninqpmd.html

[U03] Py：加载 .env 配置
来源：http://dali.yj20258.top/Article/details/gtjpqdppsk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.andypj.xyz/Article/details/gtwykowwle.html

[U04] Py：变量调试打印
来源：http://dali.aibaodan.cn/Article/details/gtasydhuwa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhoulong.xyz/Article/details/gtkvwytdhj.html

[U05] Py：列表去重且保序
来源：http://dali.ppjwa.cn/Article/details/gtlebcvnet.html

list(dict.fromkeys(arr))
来源：http://dali.0kj1m.cn/Article/details/gtfjzmbkef.html

[U06] Py：合并两个字典
来源：http://dali.gzhubu.top/Article/details/gtqczlqgmx.html

{**a, **b}
来源：http://dali.zdqjudy.top/Article/details/gtrilxzozm.html

[U07] Py：反转字典键值
来源：http://dali.sweek.top/Article/details/gtcxcjmoyo.html

{v: k for k, v in d.items()}
来源：http://dali.nanxinkj.top/Article/details/gthyyfskiq.html

[U08] Py：展平二维列表
来源：http://dali.yangfankeji.com/Article/details/gtdqdiahyp.html

[y for x in nested for y in x]
来源：http://dali.quarkkingdee.top/Article/details/gtdrlpvpas.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258888.top/Article/details/gtxrcxyylm.html

max(d, key=d.get)
来源：http://dali.jianghu66.top/Article/details/gtsxepklrq.html

[U10] Py：按值排序字典
来源：http://dali.xuanzx.com/Article/details/gtggnnoucb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.mhx1999.top/Article/details/gtrcdphzfr.html

[U11] Py：生成器表达式
来源：http://dali.ppjwa.cn/Article/details/gteixitnta.html

(x * 2 for x in arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtmhdjewvs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zycfv.cn/Article/details/gthydtrqen.html

Counter(arr).most_common(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtksudkwvz.html

[U13] Py：固定长度队列
来源：http://dali.redwolf501.top/Article/details/gtruxtqgmd.html

deque(maxlen=10)
来源：http://dali.wangdashe.top/Article/details/gtblugzjpr.html

[U14] Py：分组收集到列表
来源：http://dali.tianlin.xyz/Article/details/gtpxbulaxc.html

defaultdict(list)
来源：http://dali.sysykeji.top/Article/details/gttzxvveji.html

[U15] Py：高精度计时
来源：http://dali.ydzc1.top/Article/details/gtqrunmnlu.html

t = time.perf_counter()
来源：http://dali.xuetiantiany.cn/Article/details/gthkorblmt.html

[U16] Py：命令行参数解析
来源：http://dali.zhiwuduotai.top/Article/details/gtdszpuccb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xuanzx.com/Article/details/gtrxzswxkt.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzdtjqfh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yj20258.top/Article/details/gtjvxtenzw.html

[U18] Py：预编译正则
来源：http://dali.gotoacloud.top/Article/details/gtemcsldbe.html

pat = re.compile(r"\d+")
来源：http://dali.cucudq.cn/Article/details/gtcolstrdt.html

[U19] Py：正则替换带回调
来源：http://dali.shuidangran.top/Article/details/gtwmmklzid.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.havefunace.top/Article/details/gtrcckopmy.html

[U20] Py：缓存函数结果
来源：http://dali.mhx1999.top/Article/details/gtjnndxevv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.kuanghao11.cn/Article/details/gtxokmmzjj.html

[U21] Py：自定义上下文管理器
来源：http://dali.cucudq.cn/Article/details/gtiyficoug.html

@contextlib.contextmanager
来源：http://dali.yueranfly.top/Article/details/gtymuxvjyj.html

[U22] Py：矩阵转置
来源：http://dali.nanxuanxn.top/Article/details/gtfnrmeieg.html

list(zip(*m))
来源：http://dali.xuetiantiany.cn/Article/details/gtlhzypraq.html

[U23] Py：分块读取大文件
来源：http://dali.yanxiufei.cn/Article/details/gtrpftcwhu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.birdmap.top/Article/details/gtzjgfgllx.html

[U24] Py：路径操作
来源：http://dali.pengpengdd.cyou/Article/details/gtyxlcztrq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gtkowmksck.html

[U25] Py：CSV 按字典读
来源：http://dali.fengsongda.top/Article/details/gtnobpgsjl.html

csv.DictReader(f)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuimdzflp.html

[U26] Py：并发下载
来源：http://dali.yvedp.cn/Article/details/gtrsogokov.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.feifeiyinyue.top/Article/details/gtddxxrlvc.html

[U27] Py：异步 HTTP
来源：http://dali.vqdsnc.cn/Article/details/gtdujrxtdv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.0kj1m.cn/Article/details/gtwjuyrxjc.html

[U28] Py：类型别名
来源：http://dali.cqqwz.cn/Article/details/gtonsiusrl.html

UserId = int
来源：http://dali.svipenyu.cn/Article/details/gtvcpgkump.html

[U29] Py：属性校验
来源：http://dali.haohaochexian.top/Article/details/gtgrzwoyde.html

@property 与 @x.setter 配合
来源：http://dali.dashuyun.cn/Article/details/gtyurggdcc.html

[U30] Py：数据类
来源：http://dali.yangfankeji.com/Article/details/gtwbuoezlu.html

@dataclass(slots=True)
来源：http://dali.yanxiufei.cn/Article/details/gtlfqzzaht.html

[U31] Py：单测
来源：http://dali.nwbrower.top/Article/details/gtzwnouojf.html

python -m pytest -q
来源：http://dali.hnxiangtu.top/Article/details/gtzwucemtv.html

[U32] Py：代码格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtiavfohja.html

ruff format . && ruff check --fix .
来源：http://dali.hfpthk.cn/Article/details/gtrjkwnzjn.html

[U33] Py：打包发布
来源：http://dali.zhongyouzk.top/Article/details/gtddzacrun.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstopzzfy.html

[U34] Py：判断编码
来源：http://dali.nwbrower.top/Article/details/gtawgclxhj.html

chardet.detect(raw)
来源：http://dali.zhongyouzk.top/Article/details/gtplkggynf.html

[U35] Py：发送邮件
来源：http://dali.yj202588.top/Article/details/gtgewyfawj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.tian-w.cn/Article/details/gtavzfaopc.html

[U36] Py：定时任务
来源：http://dali.yj20258.top/Article/details/gtwdgzrtdd.html

schedule.every(10).minutes.do(job)
来源：http://dali.yangfankeji.com/Article/details/gtagnrqtjo.html

[U37] Py：读写 Excel
来源：http://dali.sysykeji.top/Article/details/gtyrhjqgcz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hnxiangtu.top/Article/details/gtttjwuwzw.html

[U38] Py：获取脚本所在目录
来源：http://dali.xuanzx.com/Article/details/gtyixrbcsh.html

Path(__file__).resolve().parent
来源：http://dali.nanxinkj.top/Article/details/gtopnlvfwi.html

[U39] Py：判断是否在交互环境
来源：http://dali.ivvv.top/Article/details/gtkafmqsla.html

sys.stdout.isatty()
来源：http://dali.cheryme.top/Article/details/gtyzkznfkf.html

[U40] Py：打印到标准错误
来源：http://dali.zhixingplan.top/Article/details/gtjsdeqqtn.html

print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gtrbyiddci.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gtcjbagztl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cqqwz.cn/Article/details/gtoallhtps.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.iojbl.cn/Article/details/gteecyqigf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhongyouzk.top/Article/details/gtwvckhicr.html

[U43] PHP：声明命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gtuzpizvtm.html

namespace App\Http;
来源：http://dali.dashuyun.cn/Article/details/gtqaezptow.html

[U44] PHP：开启严格类型
来源：http://dali.gzhubu.top/Article/details/gtekwqtvvm.html

declare(strict_types=1);
来源：http://dali.fengsongda.top/Article/details/gtikediqmb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbqkezzw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gteinngmri.html

[U46] PHP：可空类型
来源：http://dali.yanxiufei.cn/Article/details/gtsfbznmof.html

?string $name = null
来源：http://dali.xylfe.cn/Article/details/gttqpnnucu.html

[U47] PHP：联合类型
来源：http://dali.jqgfzy.top/Article/details/gttgtwtrul.html

int|string $id
来源：http://dali.xziqi.cn/Article/details/gtgzkagjgq.html

[U48] PHP：纯枚举
来源：http://dali.mhx1999.top/Article/details/gtypnyleys.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfbjvkadq.html

[U49] PHP：只读属性
来源：http://dali.tianlin.xyz/Article/details/gtgcmirrrp.html

public readonly string $name
来源：http://dali.yanxiufei.cn/Article/details/gtlmkqgsoe.html

[U50] PHP：构造器属性提升
来源：http://dali.ehwqpu.com/Article/details/gtupibhszr.html

public function __construct(private int $id) {}
来源：http://dali.jinqigfzy.top/Article/details/gtuoemfawm.html

[U51] PHP：数组解构
来源：http://dali.jqgufenzy.top/Article/details/gtvuvivecy.html

[$a, $b] = $arr;
来源：http://dali.tanke756.top/Article/details/gtfpddqsql.html

[U52] PHP：箭头函数
来源：http://dali.xinyue.icu/Article/details/gtxwxvlaqi.html

$double = fn($x) => $x * 2;
来源：http://dali.iojbl.cn/Article/details/gtfsoidzyl.html

[U53] PHP：空合并运算符
来源：http://dali.yj202588.top/Article/details/gtfrnmrnwv.html

$v = $a ?? $b ?? "default";
来源：http://dali.ppjwa.cn/Article/details/gtsvpyezge.html

[U54] PHP：空安全调用
来源：http://dali.pengpengdd.cyou/Article/details/gtbaxrvedd.html

$obj?->method()
来源：http://dali.feifeiyinyue.top/Article/details/gtfbuctksv.html

[U55] PHP：match 表达式
来源：http://dali.yueranfly.top/Article/details/gtilcuuvgx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.sufxvd.cn/Article/details/gthxthjamd.html

[U56] PHP：命名参数
来源：http://dali.hysaishi.cn/Article/details/gtzetkzdqi.html

f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gtuhwaurus.html

[U57] PHP：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtoereqbxl.html

"值: {$a}"
来源：http://dali.chenlongwang.top/Article/details/gtlgdymbiy.html

[U58] PHP：数组三件套
来源：http://dali.cqqwz.cn/Article/details/gtkjormkyg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hywenlv.cn/Article/details/gtvhsmbjca.html

[U59] PHP：自定义排序
来源：http://dali.andypj.xyz/Article/details/gtiyzornyi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhixingplan.top/Article/details/gtsaxzslyv.html

[U60] PHP：JSON 编解码
来源：http://dali.xinyue.icu/Article/details/gttnurjxjd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yj202588.top/Article/details/gtzlhtquww.html

[U61] PHP：正则
来源：http://dali.dianchejie.cn/Article/details/gtpztlzfli.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sysykeji.top/Article/details/gtkmmhzabn.html

[U62] PHP：日期对象
来源：http://dali.birdmap.top/Article/details/gtqyarxuao.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zdqjudy.top/Article/details/gtxqyvazed.html

[U63] PHP：文件读写
来源：http://dali.hnqzz.top/Article/details/gtfhocqcoi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhixingplan.top/Article/details/gtfkmtbvse.html

[U64] PHP：目录遍历
来源：http://dali.yueranfly.top/Article/details/gtymgnyjzu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.smart0.xyz/Article/details/gtxikzlmdt.html

[U65] PHP：会话
来源：http://dali.feifeiyinyue.top/Article/details/gttnkhfyyh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ybcxt.top/Article/details/gthzpyscpn.html

[U66] PHP：设置 Cookie
来源：http://dali.cheryme.top/Article/details/gtohfmsnla.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtravvhhaw.html

[U67] PHP：处理文件上传
来源：http://dali.dianchejie.cn/Article/details/gtmprdwguv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.nwbrower.top/Article/details/gtwyvygyia.html

[U68] PHP：PDO 连接
来源：http://dali.guowangkeji.top/Article/details/gtsdfakfvw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tian-w.cn/Article/details/gtxbqrnddj.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gtzmgnejln.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hnqzz.top/Article/details/gtnfxbnxbj.html

[U70] PHP：PDO 事务
来源：http://dali.chenzaomai.com/Article/details/gtowzrzvyz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.aibaodan.cn/Article/details/gtnrqkgfad.html

[U71] PHP：抛出异常
来源：http://dali.wangdashe.top/Article/details/gthktnndjg.html

throw new RuntimeException("失败", 500);
来源：http://dali.aibaodan.cn/Article/details/gtlvfltzcu.html

[U72] PHP：写错误日志
来源：http://dali.jinqigfzy.top/Article/details/gtktiixtdy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.guannengcc.top/Article/details/gtyvhjmcsu.html

[U73] PHP：读取 ini 配置
来源：http://dali.jinqigfzy.top/Article/details/gtruaczjco.html

parse_ini_file("config.ini", true)
来源：http://dali.hammf.cn/Article/details/gtnugrdiyc.html

[U74] PHP：读取环境变量
来源：http://dali.havefunace.top/Article/details/gtsxreaano.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gaohongyu789.top/Article/details/gttumgihuh.html

[U75] PHP：依赖注入
来源：http://dali.xuanzx.com/Article/details/gtewgfyour.html

composer require psr/container
来源：http://dali.yuxming.cn/Article/details/gtnwhwsyxk.html

[U76] PHP：简单路由
来源：http://dali.smart0.xyz/Article/details/gtawabksjz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cqqwz.cn/Article/details/gttgfjhgnk.html

[U77] PHP：模板渲染
来源：http://dali.yj20258.top/Article/details/gthweikgif.html

composer require twig/twig
来源：http://dali.tianlin.xyz/Article/details/gtnnbpwnpz.html

[U78] PHP：单元测试
来源：http://dali.wangdashe.top/Article/details/gtxkacwcuq.html

composer require --dev phpunit/phpunit
来源：http://dali.gogol.net.cn/Article/details/gtugtrrlte.html

[U79] PHP：静态分析
来源：http://dali.yanxiufei.cn/Article/details/gtqhnnqycw.html

composer require --dev phpstan/phpstan
来源：http://dali.yuxming.cn/Article/details/gtsoeporlc.html

[U80] PHP：代码规范修复
来源：http://dali.zycfv.cn/Article/details/gtbxectzsq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hysaishi.cn/Article/details/gtwgxtyged.html

[U81] JS：初始化项目
来源：http://dali.cucudq.cn/Article/details/gtdlospvik.html

npm init -y;  npm i express
来源：http://dali.gzhubu.top/Article/details/gtmlrsdpsk.html

[U82] JS：package.json 脚本
来源：http://dali.hnqzz.top/Article/details/gtkvhecvuq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yangfankeji.com/Article/details/gtdkrspqlw.html

[U83] JS：ES Module 导入导出
来源：http://dali.gaohongyu789.top/Article/details/gtzbsfizon.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gtxdfkxbcv.html

[U84] JS：CommonJS 写法
来源：http://dali.hfpthk.cn/Article/details/gtrgfgheun.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cdnleiting.top/Article/details/gtyovpnoxd.html


<!-- 参考信息 -->