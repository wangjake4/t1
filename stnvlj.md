代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.snrcjt.cn/Article/details/gt2rvdnungm.html

[S57] C++：编译期常量
来源：http://dali.ppjwa.cn/Article/details/gt2elmaaxfk.html

constexpr int N = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rvcihlmg.html

[S58] C++：命名空间
来源：http://dali.xinyue.icu/Article/details/gt2vrdszwme.html

namespace ns { int f() { return 1; } }
来源：http://dali.xziqi.cn/Article/details/gt2uzwaezln.html

[S59] C++：静态断言
来源：http://dali.yuxming.cn/Article/details/gt2netmuqls.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jyoumei.cn/Article/details/gt2kwvrwtxm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhoulong.xyz/Article/details/gt2fnivsjvb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zycfv.cn/Article/details/gt2axxokdoz.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2oockroif.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gt2wpqiqiyd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2ptewlbjj.html

[T01] Kotlin：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2nptiangw.html

println("Hello")
来源：http://dali.yonumen.top/Article/details/gt2wqgnjeju.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyhthfe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hywenlv.cn/Article/details/gt2octmtzkm.html

[T03] Kotlin：字符串模板
来源：http://dali.nwbrower.top/Article/details/gt2qylibzgu.html

"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gt2vcbmuuva.html

[T04] Kotlin：空安全
来源：http://dali.c1oappe.top/Article/details/gt2tlmexcmk.html

val n: String? = null;  n?.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tnxxchsg.html

[T05] Kotlin：when 表达式
来源：http://dali.bjfxy.top/Article/details/gt2ajssdahz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.316326.xyz/Article/details/gt2oyvljfrn.html

[T06] Kotlin：集合映射
来源：http://dali.yueranfly.top/Article/details/gt2ohbrrnne.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.birdmap.top/Article/details/gt2boihxizr.html

[T07] Kotlin：集合过滤
来源：http://dali.xuanzx.com/Article/details/gt2kbmbzriq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2migzrjux.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gt2wcqjvwzr.html

data class User(val name: String, val age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gt2gksqicqp.html

[T09] Kotlin：扩展函数
来源：http://dali.jlsjyb.cn/Article/details/gt2xnbpimtn.html

fun String.exclaim() = this + "!"
来源：http://dali.wangshuangyany.cn/Article/details/gt2wcjguipb.html

[T10] Kotlin：默认参数
来源：http://dali.wangdashe.top/Article/details/gt2amkyirfg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhongyouzk.top/Article/details/gt2kjsrfpty.html

[T11] Kotlin：协程
来源：http://dali.fzhhl.top/Article/details/gt2josuymxa.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zdqjudy.top/Article/details/gt2lwbkdvcl.html

[T12] Kotlin：解构声明
来源：http://dali.nanxuanxn.top/Article/details/gt2modorunz.html

val (a, b) = Pair(1, 2)
来源：http://dali.cheryme.top/Article/details/gt2fzjyehtj.html

[T13] Kotlin：只读 Map
来源：http://dali.pycfn.com/Article/details/gt2kideggrv.html

val m = mapOf("a" to 1)
来源：http://dali.aizwys.cn/Article/details/gt2rkqzlfcb.html

[T14] Kotlin：循环
来源：http://dali.yj202588.top/Article/details/gt2pnitceog.html

for (i in 1..10) println(i)
来源：http://dali.yueranfly.top/Article/details/gt2eyutlpcr.html

[T15] Kotlin：接口
来源：http://dali.smart0.xyz/Article/details/gt2lytsebap.html

interface Shape { fun area(): Double }
来源：http://dali.hammf.cn/Article/details/gt2fokcrdqg.html

[T16] Swift：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2mjbgsxzw.html

print("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gt2kajpnuof.html

[T17] Swift：变量与常量
来源：http://dali.hammf.cn/Article/details/gt2qvgnondc.html

var a = 1;  let b = 2
来源：http://dali.daxiang520.top/Article/details/gt2wdhzdtbm.html

[T18] Swift：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gt2bbawkvrq.html

"值: \(b)"
来源：http://dali.zdqjudy.top/Article/details/gt2crqgylyq.html

[T19] Swift：可选绑定
来源：http://dali.jlsjyb.cn/Article/details/gt2hslmkoqn.html

if let n = opt { print(n) }
来源：http://dali.yvedp.cn/Article/details/gt2ebvfizbf.html

[T20] Swift：数组操作
来源：http://dali.jlsjyb.cn/Article/details/gt2jqivllqf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxinkj.top/Article/details/gt2tmonxjno.html

[T21] Swift：遍历
来源：http://dali.nwbrower.top/Article/details/gt2jxdqreiy.html

for x in a { print(x) }
来源：http://dali.svipenyu.cn/Article/details/gt2isxzblil.html

[T22] Swift：字典
来源：http://dali.yvedp.cn/Article/details/gt2ndcfhaxi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenzaomai.com/Article/details/gt2oddmgchc.html

[T23] Swift：函数
来源：http://dali.hfpthk.cn/Article/details/gt2dbvrofna.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.kuanghao11.cn/Article/details/gt2rcfokotk.html

[T24] Swift：闭包
来源：http://dali.hammf.cn/Article/details/gt2mjcbcstb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2tzhvytjz.html

[T25] Swift：结构体
来源：http://dali.ppjwa.cn/Article/details/gt2yxdcwarv.html

struct P { var x: Int }
来源：http://dali.cqqwz.cn/Article/details/gt2vqmnepoi.html

[T26] Swift：类与重写
来源：http://dali.mhx1999.top/Article/details/gt2nesyqcdv.html

class A: Base { override func f() {} }
来源：http://dali.cheryme.top/Article/details/gt2gpknlufn.html

[T27] Swift：错误处理
来源：http://dali.tian-w.cn/Article/details/gt2vxciwwum.html

do { try f() } catch { print(error) }
来源：http://dali.pycfn.com/Article/details/gt2xqnseiwm.html

[T28] Swift：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jqwbkhzt.html

enum Color { case red, green }
来源：http://dali.0kj1m.cn/Article/details/gt2msfwzguq.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigufen.top/Article/details/gt2kthimzuf.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gt2meausrts.html

[T30] Swift：协议
来源：http://dali.vqdsnc.cn/Article/details/gt2fzqqefof.html

protocol Shape { func area() -> Double }
来源：http://dali.cheryme.top/Article/details/gt2zckvpofy.html

[T31] Lua：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2jrvesorh.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kjhetdpl.html

[T32] Lua：局部变量
来源：http://dali.xylfe.cn/Article/details/gt2hgafwqav.html

local a = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zbllnaph.html

[T33] Lua：表（数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wgsvvmjn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.fengsongda.top/Article/details/gt2xjztjmrs.html

[T34] Lua：遍历表
来源：http://dali.cdnleiting.top/Article/details/gt2awkyxnug.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vqrwbuhj.html

[T35] Lua：字典表
来源：http://dali.bjfxy.top/Article/details/gt2xkybcino.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shuidangran.top/Article/details/gt2dntpozsz.html

[T36] Lua：函数
来源：http://dali.vqdsnc.cn/Article/details/gt2xnfkcevs.html

function add(a, b) return a + b end
来源：http://dali.svipenyu.cn/Article/details/gt2pjcjerfz.html

[T37] Lua：字符串拼接
来源：http://dali.316326.xyz/Article/details/gt2gxooacaq.html

"a" .. "b"
来源：http://dali.tian-w.cn/Article/details/gt2kfwqlssk.html

[T38] Lua：条件
来源：http://dali.mhx1999.top/Article/details/gt2xffnvjgz.html

if x > 0 then print("正") end
来源：http://dali.zhengqikj.top/Article/details/gt2msdemygg.html

[T39] Lua：模式匹配
来源：http://dali.yj20258888.top/Article/details/gt2eozqpcfr.html

string.find(s, "%d+")
来源：http://dali.jiagoushi.top/Article/details/gt2qhdauaml.html

[T40] Lua：元表
来源：http://dali.yueranfly.top/Article/details/gt2xqjqdtpg.html

setmetatable({}, { __index = base })
来源：http://dali.chenzaomai.com/Article/details/gt2cddpltzu.html

[T41] Perl：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2hafgjcfy.html

print "Hello\n";
来源：http://dali.snrcjt.cn/Article/details/gt2zpweynam.html

[T42] Perl：变量类型
来源：http://dali.zdqjudy.top/Article/details/gt2nnzyhgeu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.meibo888.top/Article/details/gt2rooryfpr.html

[T43] Perl：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gt2mqiredub.html

"值: $a"
来源：http://dali.zhiwuduotai.top/Article/details/gt2pwgygvoz.html

[T44] Perl：条件
来源：http://dali.jiagoushi.top/Article/details/gt2vgbsipsd.html

if ($a > 0) { print "正"; }
来源：http://dali.tanke756.top/Article/details/gt2pmgpytap.html

[T45] Perl：数组遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2baaljvcf.html

for my $x (@arr) { print $x; }
来源：http://dali.svipenyu.cn/Article/details/gt2ehabiqlg.html

[T46] Perl：哈希操作
来源：http://dali.hnqzz.top/Article/details/gt2abuuwdoh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cucudq.cn/Article/details/gt2rfahqcqv.html

[T47] Perl：正则捕获
来源：http://dali.zhiwuduotai.top/Article/details/gt2utsymctg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.meibo888.top/Article/details/gt2awzimvkc.html

[T48] Perl：正则替换
来源：http://dali.pycfn.com/Article/details/gt2dlyydxzr.html

$s =~ s/old/new/g;
来源：http://dali.jqgufenzy.top/Article/details/gt2uqcalefv.html

[T49] Perl：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zfmjaiez.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gt2dgbugppg.html

[T50] Perl：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gt2zgewbmiz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ydzc1.top/Article/details/gt2vavdxvjb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jiagoushi.top/Article/details/gt2gvlssvdm.html

[T51] Scala：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2kgvrkbaj.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gt2pgqgdhpp.html

[T52] Scala：变量
来源：http://dali.ehwqpu.com/Article/details/gt2bkirbtjf.html

val a = 1;  var b = 2
来源：http://dali.ydzc1.top/Article/details/gt2hexxttvi.html

[T53] Scala：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gt2hnawpuqx.html

s"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gthsvwlc.html

[T54] Scala：集合映射
来源：http://dali.cdnleiting.top/Article/details/gt2mxdepjym.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.guowangkeji.top/Article/details/gt2aqhglcxp.html

[T55] Scala：集合过滤
来源：http://dali.cashguo.top/Article/details/gt2ncmiverf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nogfdoxw.html

[T56] Scala：样例类
来源：http://dali.cdnleiting.top/Article/details/gt2upbbhkmh.html

case class User(name: String, age: Int)
来源：http://dali.dianchejie.cn/Article/details/gt2mhcdybyj.html

[T57] Scala：模式匹配
来源：http://dali.gzhubu.top/Article/details/gt2okexptuj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tian-w.cn/Article/details/gt2epfzlfug.html

[T58] Scala：函数定义
来源：http://dali.xuetiantiany.cn/Article/details/gt2mhfewynd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.vqdsnc.cn/Article/details/gt2kokrbntf.html

[T59] Scala：循环
来源：http://dali.hnqzz.top/Article/details/gt2qekhmunp.html

for (i <- 1 to 10) println(i)
来源：http://dali.316326.xyz/Article/details/gt2zwfaibvv.html

[T60] Scala：折叠
来源：http://dali.daxiang520.top/Article/details/gt2objcclyt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yongpay.top/Article/details/gt2lrsbdcdr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2oiuknaym.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuanzhike.top/Article/details/gt2hbasicbj.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2xzqufojy.html

[U01] Py：创建虚拟环境
来源：http://dali.snrcjt.cn/Article/details/gt2ygpwzfrp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tanke756.top/Article/details/gt2gcqwjkfe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.9152youxi.cn/Article/details/gt2kfhpvhkx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.316326.xyz/Article/details/gt2emtvfaqm.html

[U03] Py：加载 .env 配置
来源：http://dali.chenlongwang.top/Article/details/gt2aweeqwhh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tanke756.top/Article/details/gt2feldwayn.html

[U04] Py：变量调试打印
来源：http://dali.kuanghao11.cn/Article/details/gt2rhtfolmj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sxryk.cn/Article/details/gt2kaobrnkm.html

[U05] Py：列表去重且保序
来源：http://dali.zhixingplan.top/Article/details/gt2wzrkppdd.html

list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gt2vnialuuu.html

[U06] Py：合并两个字典
来源：http://dali.hnxiangtu.top/Article/details/gt2fdijnydc.html

{**a, **b}
来源：http://dali.nanxuanxn.top/Article/details/gt2pnvzqlyr.html

[U07] Py：反转字典键值
来源：http://dali.ehwqpu.com/Article/details/gt2ourfwszp.html

{v: k for k, v in d.items()}
来源：http://dali.hnxiangtu.top/Article/details/gt2hjxwrmtv.html

[U08] Py：展平二维列表
来源：http://dali.sufxvd.cn/Article/details/gt2lsypftyg.html

[y for x in nested for y in x]
来源：http://dali.pycfn.com/Article/details/gt2onmbslao.html

[U09] Py：字典取最大值的键
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zewpthlj.html

max(d, key=d.get)
来源：http://dali.guowangkeji.top/Article/details/gt2nnjzvewb.html

[U10] Py：按值排序字典
来源：http://dali.zhoulong.xyz/Article/details/gt2iyqbrriu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yuxming.cn/Article/details/gt2affnxwbx.html

[U11] Py：生成器表达式
来源：http://dali.daria6918.cn/Article/details/gt2bhkhedkk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkqkpkh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yonumen.top/Article/details/gt2xzdqsfdz.html

Counter(arr).most_common(3)
来源：http://dali.chenzaomai.com/Article/details/gt2cycbdcim.html

[U13] Py：固定长度队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2avudikwm.html

deque(maxlen=10)
来源：http://dali.smart0.xyz/Article/details/gt2qykbtcxf.html

[U14] Py：分组收集到列表
来源：http://dali.jiagoushi.top/Article/details/gt2tpmtgdzr.html

defaultdict(list)
来源：http://dali.xinyue.icu/Article/details/gt2drtejimi.html

[U15] Py：高精度计时
来源：http://dali.cucudq.cn/Article/details/gt2wceoaoxv.html

t = time.perf_counter()
来源：http://dali.sweek.top/Article/details/gt2whtczvfd.html

[U16] Py：命令行参数解析
来源：http://dali.cucudq.cn/Article/details/gt2zhvhonmg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jqgufenzy.top/Article/details/gt2qcszxfnq.html

[U17] Py：初始化日志
来源：http://dali.meibo888.top/Article/details/gt2mhyawfao.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yuanzhike.top/Article/details/gt2ikqsspcb.html

[U18] Py：预编译正则
来源：http://dali.meibo888.top/Article/details/gt2ytnnhubm.html

pat = re.compile(r"\d+")
来源：http://dali.xylfe.cn/Article/details/gt2rbzvyjhj.html

[U19] Py：正则替换带回调
来源：http://dali.chenzaomai.com/Article/details/gt2cwcdngwx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yongpay.top/Article/details/gt2wubhiybi.html

[U20] Py：缓存函数结果
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxuzkhhe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.fzhhl.top/Article/details/gt2wjcuidol.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnqzz.top/Article/details/gt2lgxnjbkw.html

@contextlib.contextmanager
来源：http://dali.hnqzz.top/Article/details/gt2syxjzonz.html

[U22] Py：矩阵转置
来源：http://dali.yangfankeji.com/Article/details/gt2zgxejsfq.html

list(zip(*m))
来源：http://dali.andypj.xyz/Article/details/gt2nfjsuigl.html

[U23] Py：分块读取大文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ppxviexc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2unmreoot.html

[U24] Py：路径操作
来源：http://dali.zhengqikj.top/Article/details/gt2tdekvrxm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhdnehwe.html

[U25] Py：CSV 按字典读
来源：http://dali.snrcjt.cn/Article/details/gt2mmkczwiw.html

csv.DictReader(f)
来源：http://dali.jqgufenzy.top/Article/details/gt2rwjglrzt.html

[U26] Py：并发下载
来源：http://dali.316326.xyz/Article/details/gt2qdmbwpad.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.fzhhl.top/Article/details/gt2yceyqgth.html

[U27] Py：异步 HTTP
来源：http://dali.zhiwuduotai.top/Article/details/gt2vgggycoq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yj20258888.top/Article/details/gt2vqygrruu.html

[U28] Py：类型别名
来源：http://dali.yonumen.top/Article/details/gt2nhyjalph.html

UserId = int
来源：http://dali.wangshuangyany.cn/Article/details/gt2xainrcsa.html

[U29] Py：属性校验
来源：http://dali.meibo888.top/Article/details/gt2zqmxlpqw.html

@property 与 @x.setter 配合
来源：http://dali.jyoumei.cn/Article/details/gt2hqztfppl.html

[U30] Py：数据类
来源：http://dali.yuxming.cn/Article/details/gt2byodnzvy.html

@dataclass(slots=True)
来源：http://dali.bjfxy.top/Article/details/gt2lhnbqvbu.html

[U31] Py：单测
来源：http://dali.zhixingplan.top/Article/details/gt2mmgdjfkt.html

python -m pytest -q
来源：http://dali.zycfv.cn/Article/details/gt2lhazzhct.html

[U32] Py：代码格式化
来源：http://dali.meibo888.top/Article/details/gt2duzfpgjb.html

ruff format . && ruff check --fix .
来源：http://dali.daxiang520.top/Article/details/gt2sizctreo.html

[U33] Py：打包发布
来源：http://dali.jqgufenzy.top/Article/details/gt2ylewhhri.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhoulong.xyz/Article/details/gt2xdpplzlr.html

[U34] Py：判断编码
来源：http://dali.dashuyun.cn/Article/details/gt2lrgnofra.html

chardet.detect(raw)
来源：http://dali.kuanghao11.cn/Article/details/gt2jcxiuqkj.html

[U35] Py：发送邮件
来源：http://dali.wangshuangyany.cn/Article/details/gt2zrwwyfxy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinqigfzy.top/Article/details/gt2djxixdiq.html

[U36] Py：定时任务
来源：http://dali.havefunace.top/Article/details/gt2kiflkctq.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinqigfzy.top/Article/details/gt2ayjpinmn.html

[U37] Py：读写 Excel
来源：http://dali.quarkkingdee.top/Article/details/gt2oegaxkfb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yuanzhike.top/Article/details/gt2gxsasouv.html

[U38] Py：获取脚本所在目录
来源：http://dali.guowangkeji.top/Article/details/gt2ysmrrwym.html

Path(__file__).resolve().parent
来源：http://dali.aibaodan.cn/Article/details/gt2fguaigiw.html

[U39] Py：判断是否在交互环境
来源：http://dali.xinyue.icu/Article/details/gt2dgcogsdx.html

sys.stdout.isatty()
来源：http://dali.jinqigufen.top/Article/details/gt2sadfnxqq.html

[U40] Py：打印到标准错误
来源：http://dali.sxryk.cn/Article/details/gt2fdpmxmxd.html

print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gt2kossxolc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.dashuyun.cn/Article/details/gt2lwpdbihw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ydzc1.top/Article/details/gt2tsttajio.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhiwuduotai.top/Article/details/gt2iuztwtir.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.aizwys.cn/Article/details/gt2sitvdkse.html

[U43] PHP：声明命名空间
来源：http://dali.guannengcc.top/Article/details/gt2tdfaqemi.html

namespace App\Http;
来源：http://dali.ybcxt.top/Article/details/gt2hxyymkmj.html

[U44] PHP：开启严格类型
来源：http://dali.smart0.xyz/Article/details/gt2mipugvgc.html

declare(strict_types=1);
来源：http://dali.0kj1m.cn/Article/details/gt2ffrlskrt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gogol.net.cn/Article/details/gt2dvpcplge.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gt2oogvdtsr.html

[U46] PHP：可空类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2eigbafyb.html

?string $name = null
来源：http://dali.zhixingplan.top/Article/details/gt2pcqvgvdt.html

[U47] PHP：联合类型
来源：http://dali.kuanghao11.cn/Article/details/gt2cvmhpluw.html

int|string $id
来源：http://dali.0kj1m.cn/Article/details/gt2mnwcykmj.html

[U48] PHP：纯枚举
来源：http://dali.sysykeji.top/Article/details/gt2nsmdhnwk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mmlwjxyz.html

[U49] PHP：只读属性
来源：http://dali.xuetiantiany.cn/Article/details/gt2fxeizhyx.html

public readonly string $name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldbnuymu.html

[U50] PHP：构造器属性提升
来源：http://dali.c1oappe.top/Article/details/gt2gtuhwqgd.html

public function __construct(private int $id) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bhttnfgm.html

[U51] PHP：数组解构
来源：http://dali.gotoacloud.top/Article/details/gt2afhajiwb.html

[$a, $b] = $arr;
来源：http://dali.pycfn.com/Article/details/gt2qjylmntu.html

[U52] PHP：箭头函数
来源：http://dali.guowangkeji.top/Article/details/gt2xoaxbntp.html

$double = fn($x) => $x * 2;
来源：http://dali.sysykeji.top/Article/details/gt2objzurfx.html

[U53] PHP：空合并运算符
来源：http://dali.mhx1999.top/Article/details/gt2kpgpzoit.html

$v = $a ?? $b ?? "default";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cfhnguof.html

[U54] PHP：空安全调用
来源：http://dali.jqgufenzy.top/Article/details/gt2nbgdfwko.html

$obj?->method()
来源：http://dali.c1oappe.top/Article/details/gt2okgiaebk.html

[U55] PHP：match 表达式
来源：http://dali.xziqi.cn/Article/details/gt2vclenlqg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hongshengwenyu.top/Article/details/gt2tiqkeigk.html

[U56] PHP：命名参数
来源：http://dali.zycfv.cn/Article/details/gt2ggvscjaw.html

f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gt2pcochvnk.html

[U57] PHP：字符串插值
来源：http://dali.birdmap.top/Article/details/gt2fnelrzum.html

"值: {$a}"
来源：http://dali.tanke756.top/Article/details/gt2gsgvygsx.html

[U58] PHP：数组三件套
来源：http://dali.xylfe.cn/Article/details/gt2eigcqpna.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cashguo.top/Article/details/gt2hothlfvc.html

[U59] PHP：自定义排序
来源：http://dali.quarkkingdee.top/Article/details/gt2heaxzzue.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.havefunace.top/Article/details/gt2txvnteau.html

[U60] PHP：JSON 编解码
来源：http://dali.yanxiufei.cn/Article/details/gt2kozaofns.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nmbbymov.html

[U61] PHP：正则
来源：http://dali.fzhhl.top/Article/details/gt2hmeohbrh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gt2ppiwbtwd.html

[U62] PHP：日期对象
来源：http://dali.vqdsnc.cn/Article/details/gt2kjlsgdyi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yuanzhike.top/Article/details/gt2iiwmfvcg.html

[U63] PHP：文件读写
来源：http://dali.vqdsnc.cn/Article/details/gt2qykpmcrq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.bjfxy.top/Article/details/gt2cdxzpzup.html

[U64] PHP：目录遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2irsafvzj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gogol.net.cn/Article/details/gt2dambyxjw.html

[U65] PHP：会话
来源：http://dali.jinqigfzy.top/Article/details/gt2gvpbmqfp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2topjdeqq.html

[U66] PHP：设置 Cookie
来源：http://dali.zhongyouzk.top/Article/details/gt2ewuxnwdi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.bjfxy.top/Article/details/gt2ebpzothi.html

[U67] PHP：处理文件上传
来源：http://dali.smart0.xyz/Article/details/gt2ndwmxzyp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lbewennx.html

[U68] PHP：PDO 连接
来源：http://dali.birdmap.top/Article/details/gt2zsftuylj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tian-w.cn/Article/details/gt2vqjjwasy.html

[U69] PHP：PDO 预处理
来源：http://dali.hnqzz.top/Article/details/gt2pzxuyxzk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cqqwz.cn/Article/details/gt2hsefhhzt.html

[U70] PHP：PDO 事务
来源：http://dali.cheryme.top/Article/details/gt2eqhdcobl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xuanzx.com/Article/details/gt2kllrztmy.html

[U71] PHP：抛出异常
来源：http://dali.birdmap.top/Article/details/gt2ywiadkvl.html

throw new RuntimeException("失败", 500);
来源：http://dali.fengsongda.top/Article/details/gt2nenehhui.html

[U72] PHP：写错误日志
来源：http://dali.zhixingplan.top/Article/details/gt2asilhajy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yuxming.cn/Article/details/gt2iaiqdqpa.html

[U73] PHP：读取 ini 配置
来源：http://dali.andypj.xyz/Article/details/gt2oxtxixjf.html

parse_ini_file("config.ini", true)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bcgioptp.html

[U74] PHP：读取环境变量
来源：http://dali.zycfv.cn/Article/details/gt2ngjvdtqk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hnqzz.top/Article/details/gt2udmrsfuo.html

[U75] PHP：依赖注入
来源：http://dali.hfpthk.cn/Article/details/gt2aqcklxyz.html

composer require psr/container
来源：http://dali.havefunace.top/Article/details/gt2qsekcjwb.html

[U76] PHP：简单路由
来源：http://dali.birdmap.top/Article/details/gt2emzhgcci.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.haohaochexian.top/Article/details/gt2umuvzdfc.html

[U77] PHP：模板渲染
来源：http://dali.nanxuanxn.top/Article/details/gt2zdhkvdfi.html

composer require twig/twig
来源：http://dali.aibaodan.cn/Article/details/gt2dkarbpkz.html

[U78] PHP：单元测试
来源：http://dali.9152youxi.cn/Article/details/gt2gwarxbai.html

composer require --dev phpunit/phpunit
来源：http://dali.cqqwz.cn/Article/details/gt2jdnnbcuk.html

[U79] PHP：静态分析
来源：http://dali.smart0.xyz/Article/details/gt2lvvxjief.html

composer require --dev phpstan/phpstan
来源：http://dali.jianghu66.top/Article/details/gt2ketziuje.html

[U80] PHP：代码规范修复
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wdgupuwm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jianghu66.top/Article/details/gt2ahsnwbof.html

[U81] JS：初始化项目
来源：http://dali.tanke756.top/Article/details/gt2etonmbay.html

npm init -y;  npm i express
来源：http://dali.tianlin.xyz/Article/details/gt2bytivwjx.html

[U82] JS：package.json 脚本
来源：http://dali.bjfxy.top/Article/details/gt2wkrfqznj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sysykeji.top/Article/details/gt2vwaunyam.html


<!-- 参考信息 -->