代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.meibo888.top/Article/details/gtoybfxnem.html

[S55] C++：结构化绑定
来源：http://dali.sxryk.cn/Article/details/gtaunyhiwd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gthbystilp.html

[S56] C++：optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzimoazd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.haohaochexian.top/Article/details/gtzvdygthu.html

[S57] C++：编译期常量
来源：http://dali.tanke756.top/Article/details/gtrkehdley.html

constexpr int N = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtcitfnbem.html

[S58] C++：命名空间
来源：http://dali.sweek.top/Article/details/gtslwbtluy.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvgnhraz.html

[S59] C++：静态断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydtffcib.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.smart0.xyz/Article/details/gtpfzgthrp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalzvbhst.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tanke756.top/Article/details/gtqistxeej.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtupqzsvuc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guowangkeji.top/Article/details/gtcnbpopnx.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtuimkqe.html

[T01] Kotlin：Hello World
来源：http://dali.yongpay.top/Article/details/gtjnreaqqr.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gtdlpwhugk.html

[T02] Kotlin：变量
来源：http://dali.chenlongwang.top/Article/details/gtdkstawpr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jqgfzy.top/Article/details/gtssefqpdg.html

[T03] Kotlin：字符串模板
来源：http://dali.sufxvd.cn/Article/details/gtfstuhnoy.html

"值: $b"
来源：http://dali.pengpengdd.cyou/Article/details/gtjvkkhjgs.html

[T04] Kotlin：空安全
来源：http://dali.xziqi.cn/Article/details/gtribhybab.html

val n: String? = null;  n?.length
来源：http://dali.fengsongda.top/Article/details/gtnuhelrzl.html

[T05] Kotlin：when 表达式
来源：http://dali.fengsongda.top/Article/details/gtbfplitnm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yanxiufei.cn/Article/details/gtgulvhwrz.html

[T06] Kotlin：集合映射
来源：http://dali.yvedp.cn/Article/details/gtsyocqsko.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gzhubu.top/Article/details/gtrgdyjpjh.html

[T07] Kotlin：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gtwjzsajau.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hnqzz.top/Article/details/gtngycrpdr.html

[T08] Kotlin：数据类
来源：http://dali.shuidangran.top/Article/details/gtdmfrftvi.html

data class User(val name: String, val age: Int)
来源：http://dali.mhx1999.top/Article/details/gtqoythozv.html

[T09] Kotlin：扩展函数
来源：http://dali.yuanzhike.top/Article/details/gtntlpikrc.html

fun String.exclaim() = this + "!"
来源：http://dali.ydzc1.top/Article/details/gtiurfyzkv.html

[T10] Kotlin：默认参数
来源：http://dali.bjfxy.top/Article/details/gtujctzatq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinghuilouyu.cn/Article/details/gtypmllnsc.html

[T11] Kotlin：协程
来源：http://dali.kuanghao11.cn/Article/details/gtwdwlnmvq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gogol.net.cn/Article/details/gthiypbcub.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxzyxmug.html

val (a, b) = Pair(1, 2)
来源：http://dali.yueranfly.top/Article/details/gticbqiylz.html

[T13] Kotlin：只读 Map
来源：http://dali.dashuyun.cn/Article/details/gtnpwzqejy.html

val m = mapOf("a" to 1)
来源：http://dali.cqqwz.cn/Article/details/gtdkibddvz.html

[T14] Kotlin：循环
来源：http://dali.hywenlv.cn/Article/details/gtjcldzcrg.html

for (i in 1..10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gtxxoygjfp.html

[T15] Kotlin：接口
来源：http://dali.ivvv.top/Article/details/gtzpvnadeb.html

interface Shape { fun area(): Double }
来源：http://dali.sysykeji.top/Article/details/gtnhplocbk.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdjguxeb.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gtsorjehxh.html

[T17] Swift：变量与常量
来源：http://dali.mhx1999.top/Article/details/gtiaxerxqw.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gteaivtkzo.html

[T18] Swift：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtkgljfzdf.html

"值: \(b)"
来源：http://dali.aibaodan.cn/Article/details/gtvqmneqxc.html

[T19] Swift：可选绑定
来源：http://dali.cucudq.cn/Article/details/gtqinrldcy.html

if let n = opt { print(n) }
来源：http://dali.hfpthk.cn/Article/details/gtvwjxqjql.html

[T20] Swift：数组操作
来源：http://dali.jianghu66.top/Article/details/gtmdwhjmfa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.feifeiyinyue.top/Article/details/gtlmqqfgul.html

[T21] Swift：遍历
来源：http://dali.daxiang520.top/Article/details/gtwgszxaui.html

for x in a { print(x) }
来源：http://dali.dianchejie.cn/Article/details/gtbezwkbsk.html

[T22] Swift：字典
来源：http://dali.pycfn.com/Article/details/gtxtvqarjm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jiagoushi.top/Article/details/gtybmpkpog.html

[T23] Swift：函数
来源：http://dali.shangyingyoupin.top/Article/details/gtwyxlizip.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenzaomai.com/Article/details/gtuhimpsdk.html

[T24] Swift：闭包
来源：http://dali.ybcxt.top/Article/details/gtuszpsadb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtltpwkglm.html

[T25] Swift：结构体
来源：http://dali.yuanzhike.top/Article/details/gtxtxhurcm.html

struct P { var x: Int }
来源：http://dali.cheryme.top/Article/details/gtmhhhgili.html

[T26] Swift：类与重写
来源：http://dali.ydzc1.top/Article/details/gthlwqcapw.html

class A: Base { override func f() {} }
来源：http://dali.sufxvd.cn/Article/details/gtunyuagvi.html

[T27] Swift：错误处理
来源：http://dali.daria6918.cn/Article/details/gttjajzvvu.html

do { try f() } catch { print(error) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxmpoear.html

[T28] Swift：枚举
来源：http://dali.jqgfzy.top/Article/details/gtlhimrldv.html

enum Color { case red, green }
来源：http://dali.haohaochexian.top/Article/details/gtggrlifds.html

[T29] Swift：guard 提前返回
来源：http://dali.hnxiangtu.top/Article/details/gtckiljgtb.html

guard let x = opt else { return }
来源：http://dali.yonumen.top/Article/details/gtcstharjg.html

[T30] Swift：协议
来源：http://dali.chenlongwang.top/Article/details/gtzduavbfw.html

protocol Shape { func area() -> Double }
来源：http://dali.316326.xyz/Article/details/gtclylqyzd.html

[T31] Lua：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtzgkikfjq.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gtcrsmpmqs.html

[T32] Lua：局部变量
来源：http://dali.ppjwa.cn/Article/details/gtcpooqqtq.html

local a = 1
来源：http://dali.jianghu66.top/Article/details/gtahwrkiym.html

[T33] Lua：表（数组）
来源：http://dali.aizwys.cn/Article/details/gtcunsggsl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yueranfly.top/Article/details/gtjpkaaluf.html

[T34] Lua：遍历表
来源：http://dali.yj20258.top/Article/details/gtaeozfovh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuxming.cn/Article/details/gtjuxfblec.html

[T35] Lua：字典表
来源：http://dali.xuanzx.com/Article/details/gtrhjwpvup.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yanxiufei.cn/Article/details/gtryzedxlq.html

[T36] Lua：函数
来源：http://dali.zycfv.cn/Article/details/gtkkkupzcl.html

function add(a, b) return a + b end
来源：http://dali.hnxiangtu.top/Article/details/gtguqdvevx.html

[T37] Lua：字符串拼接
来源：http://dali.nwbrower.top/Article/details/gtpbvzuauc.html

"a" .. "b"
来源：http://dali.hysaishi.cn/Article/details/gtksakauwz.html

[T38] Lua：条件
来源：http://dali.jqgfzy.top/Article/details/gtmswwlicm.html

if x > 0 then print("正") end
来源：http://dali.tianlin.xyz/Article/details/gtsyonbwzx.html

[T39] Lua：模式匹配
来源：http://dali.tianlin.xyz/Article/details/gtetifrzqd.html

string.find(s, "%d+")
来源：http://dali.tanke756.top/Article/details/gtzbzwiwuk.html

[T40] Lua：元表
来源：http://dali.jiagoushi.top/Article/details/gtrmaeflsh.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigufen.top/Article/details/gtoievgsgo.html

[T41] Perl：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgwhloqw.html

print "Hello\n";
来源：http://dali.kuanghao11.cn/Article/details/gtafqyrnbn.html

[T42] Perl：变量类型
来源：http://dali.gogol.net.cn/Article/details/gtbaezyvut.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jiagoushi.top/Article/details/gtygketpgp.html

[T43] Perl：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gtqmiaalms.html

"值: $a"
来源：http://dali.gotoacloud.top/Article/details/gthlilkfra.html

[T44] Perl：条件
来源：http://dali.sufxvd.cn/Article/details/gthnceyqdt.html

if ($a > 0) { print "正"; }
来源：http://dali.cdnleiting.top/Article/details/gtigwnlqhz.html

[T45] Perl：数组遍历
来源：http://dali.ivvv.top/Article/details/gtvefcxyyj.html

for my $x (@arr) { print $x; }
来源：http://dali.haohaochexian.top/Article/details/gtqtrcmbby.html

[T46] Perl：哈希操作
来源：http://dali.sxryk.cn/Article/details/gtbmzfillh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxgdwfoh.html

[T47] Perl：正则捕获
来源：http://dali.dashuyun.cn/Article/details/gtrqxccfma.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zdqjudy.top/Article/details/gttnlmaeco.html

[T48] Perl：正则替换
来源：http://dali.guannengcc.top/Article/details/gtfplnofpo.html

$s =~ s/old/new/g;
来源：http://dali.zhixingplan.top/Article/details/gtvchapfif.html

[T49] Perl：函数
来源：http://dali.xuanzx.com/Article/details/gtfbhpzsqy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtjiufluyp.html

[T50] Perl：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gthqvqmqwg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aibaodan.cn/Article/details/gtjmbueaix.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yangfankeji.com/Article/details/gteaslfhzr.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxwiteci.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtvzrfxugr.html

[T52] Scala：变量
来源：http://dali.nanxuanxn.top/Article/details/gtyduthdyl.html

val a = 1;  var b = 2
来源：http://dali.chenlongwang.top/Article/details/gtxorfllkb.html

[T53] Scala：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtkvcfywhc.html

s"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gtaachgxqh.html

[T54] Scala：集合映射
来源：http://dali.ehwqpu.com/Article/details/gtgdmpusbr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.redwolf501.top/Article/details/gtjhobxtgc.html

[T55] Scala：集合过滤
来源：http://dali.316326.xyz/Article/details/gtlmtmvoca.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hywenlv.cn/Article/details/gtkwhtzuxl.html

[T56] Scala：样例类
来源：http://dali.hammf.cn/Article/details/gtgbegigct.html

case class User(name: String, age: Int)
来源：http://dali.redwolf501.top/Article/details/gtfyuddhtu.html

[T57] Scala：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gtxotdtydp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenlongwang.top/Article/details/gtbjbajzec.html

[T58] Scala：函数定义
来源：http://dali.tanke756.top/Article/details/gtitvkreoh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.vqdsnc.cn/Article/details/gtwntgkvzt.html

[T59] Scala：循环
来源：http://dali.cheryme.top/Article/details/gtppzgkouv.html

for (i <- 1 to 10) println(i)
来源：http://dali.yuxming.cn/Article/details/gtyvabhkma.html

[T60] Scala：折叠
来源：http://dali.aizwys.cn/Article/details/gtanfugwgh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.andypj.xyz/Article/details/gtepawcopw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtwlgmrauv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.0kj1m.cn/Article/details/gtdnodfkzb.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtfcrgqmju.html

[U01] Py：创建虚拟环境
来源：http://dali.jianghu66.top/Article/details/gtgachskml.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nwbrower.top/Article/details/gtcezlydwf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tian-w.cn/Article/details/gtsjzziepi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.birdmap.top/Article/details/gtbxlmcaaf.html

[U03] Py：加载 .env 配置
来源：http://dali.iojbl.cn/Article/details/gtejvmohtx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhengqikj.top/Article/details/gtfnvnufyu.html

[U04] Py：变量调试打印
来源：http://dali.havefunace.top/Article/details/gtafdnsyyw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yonumen.top/Article/details/gtmrwxwfgj.html

[U05] Py：列表去重且保序
来源：http://dali.xziqi.cn/Article/details/gtzdwxumcm.html

list(dict.fromkeys(arr))
来源：http://dali.cashguo.top/Article/details/gtqemfnqpl.html

[U06] Py：合并两个字典
来源：http://dali.pengpengdd.cyou/Article/details/gtjnvnhnog.html

{**a, **b}
来源：http://dali.cheryme.top/Article/details/gtwbmitfrq.html

[U07] Py：反转字典键值
来源：http://dali.jinqigufen.top/Article/details/gtopqjdvzy.html

{v: k for k, v in d.items()}
来源：http://dali.tanke756.top/Article/details/gtayfbdvdm.html

[U08] Py：展平二维列表
来源：http://dali.zhongyouzk.top/Article/details/gtwiowyrmx.html

[y for x in nested for y in x]
来源：http://dali.tian-w.cn/Article/details/gtwqsljdpe.html

[U09] Py：字典取最大值的键
来源：http://dali.birdmap.top/Article/details/gtxyvuumfp.html

max(d, key=d.get)
来源：http://dali.nanxuanxn.top/Article/details/gtdfgnbsre.html

[U10] Py：按值排序字典
来源：http://dali.yanxiufei.cn/Article/details/gtrcjwqybs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shuidangran.top/Article/details/gtjrtotizv.html

[U11] Py：生成器表达式
来源：http://dali.9152youxi.cn/Article/details/gtmbfdgwqg.html

(x * 2 for x in arr)
来源：http://dali.daxiang520.top/Article/details/gtuqwyetnm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tian-w.cn/Article/details/gtrjipxmdg.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gtqjzwyank.html

[U13] Py：固定长度队列
来源：http://dali.jianghu66.top/Article/details/gtmgequzeg.html

deque(maxlen=10)
来源：http://dali.shuidangran.top/Article/details/gturdndtdq.html

[U14] Py：分组收集到列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtbyzkpvkr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gtqmqkeggp.html

[U15] Py：高精度计时
来源：http://dali.wangshuangyany.cn/Article/details/gtelmkxtei.html

t = time.perf_counter()
来源：http://dali.sxryk.cn/Article/details/gtlygtkoxk.html

[U16] Py：命令行参数解析
来源：http://dali.nanxuanxn.top/Article/details/gthwupzqxb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cdnleiting.top/Article/details/gteznkrioj.html

[U17] Py：初始化日志
来源：http://dali.sysykeji.top/Article/details/gtexkwxtbe.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.redwolf501.top/Article/details/gtfjmbcnlc.html

[U18] Py：预编译正则
来源：http://dali.aibaodan.cn/Article/details/gtymtphddb.html

pat = re.compile(r"\d+")
来源：http://dali.shzxlz.cn/Article/details/gtvavykspj.html

[U19] Py：正则替换带回调
来源：http://dali.cdnleiting.top/Article/details/gtmvuukrsc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.svipenyu.cn/Article/details/gtebcfepbh.html

[U20] Py：缓存函数结果
来源：http://dali.yongpay.top/Article/details/gtzcpkuoys.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shangyingyoupin.top/Article/details/gtmdshdhoo.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefyqzcih.html

@contextlib.contextmanager
来源：http://dali.c1oappe.top/Article/details/gtkhlgrtda.html

[U22] Py：矩阵转置
来源：http://dali.redwolf501.top/Article/details/gtkostafov.html

list(zip(*m))
来源：http://dali.wangshuangyany.cn/Article/details/gtqpvewdwd.html

[U23] Py：分块读取大文件
来源：http://dali.zdqjudy.top/Article/details/gtdjqlfqea.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinyuanbaomall.cn/Article/details/gtruujavzn.html

[U24] Py：路径操作
来源：http://dali.yuxming.cn/Article/details/gtwvhncsqf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttltvhdgv.html

[U25] Py：CSV 按字典读
来源：http://dali.wangdashe.top/Article/details/gtghavajih.html

csv.DictReader(f)
来源：http://dali.zycfv.cn/Article/details/gtdpebzejz.html

[U26] Py：并发下载
来源：http://dali.nanxinkj.top/Article/details/gtnnwusolz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhengqikj.top/Article/details/gtbewljjuz.html

[U27] Py：异步 HTTP
来源：http://dali.zhixingplan.top/Article/details/gtytmncljs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhengqikj.top/Article/details/gttziussgo.html

[U28] Py：类型别名
来源：http://dali.xinyue.icu/Article/details/gtcnnjjzgj.html

UserId = int
来源：http://dali.smart0.xyz/Article/details/gthikjjmcu.html

[U29] Py：属性校验
来源：http://dali.hysaishi.cn/Article/details/gtfjinzoli.html

@property 与 @x.setter 配合
来源：http://dali.zhongyouzk.top/Article/details/gthgxtjjzb.html

[U30] Py：数据类
来源：http://dali.aibaodan.cn/Article/details/gtxkcelyum.html

@dataclass(slots=True)
来源：http://dali.jyoumei.cn/Article/details/gteqstzmvv.html

[U31] Py：单测
来源：http://dali.gzhubu.top/Article/details/gteqqswtsd.html

python -m pytest -q
来源：http://dali.yongpay.top/Article/details/gtursebqsh.html

[U32] Py：代码格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtxunaplrw.html

ruff format . && ruff check --fix .
来源：http://dali.xuetiantiany.cn/Article/details/gttkvugtqv.html

[U33] Py：打包发布
来源：http://dali.9152youxi.cn/Article/details/gtwlfgtycq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.havefunace.top/Article/details/gtntusyaxp.html

[U34] Py：判断编码
来源：http://dali.gotoacloud.top/Article/details/gtrwbcocuj.html

chardet.detect(raw)
来源：http://dali.hysaishi.cn/Article/details/gtdzmfwnpz.html

[U35] Py：发送邮件
来源：http://dali.yuanzhike.top/Article/details/gtyhgqxclp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sxryk.cn/Article/details/gtvgzxzuhu.html

[U36] Py：定时任务
来源：http://dali.zdqjudy.top/Article/details/gtabwizipd.html

schedule.every(10).minutes.do(job)
来源：http://dali.yvedp.cn/Article/details/gtjwjizcgi.html

[U37] Py：读写 Excel
来源：http://dali.guannengcc.top/Article/details/gtfvcinjdi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinqigufen.top/Article/details/gtfdrpeigr.html

[U38] Py：获取脚本所在目录
来源：http://dali.tianlin.xyz/Article/details/gtbhealboe.html

Path(__file__).resolve().parent
来源：http://dali.0kj1m.cn/Article/details/gtbisatlkn.html

[U39] Py：判断是否在交互环境
来源：http://dali.shzxlz.cn/Article/details/gtacpcsfvj.html

sys.stdout.isatty()
来源：http://dali.316326.xyz/Article/details/gtpochezda.html

[U40] Py：打印到标准错误
来源：http://dali.zhiwuduotai.top/Article/details/gthovfehyt.html

print("err", file=sys.stderr)
来源：http://dali.hammf.cn/Article/details/gtfbbmcigh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.pengpengdd.cyou/Article/details/gtmfgfxnga.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shanyushiyangtech.top/Article/details/gtiubdumbs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jqgufenzy.top/Article/details/gtjhblmehw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yonumen.top/Article/details/gtyiycsxdb.html

[U43] PHP：声明命名空间
来源：http://dali.gzhubu.top/Article/details/gthrlkgzpk.html

namespace App\Http;
来源：http://dali.gzhubu.top/Article/details/gtdsdnmqcd.html

[U44] PHP：开启严格类型
来源：http://dali.sweek.top/Article/details/gtnkmuaezt.html

declare(strict_types=1);
来源：http://dali.pycfn.com/Article/details/gtywidfdqg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.smart0.xyz/Article/details/gtywquxvvw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtgyaosmvm.html

[U46] PHP：可空类型
来源：http://dali.nanxuanxn.top/Article/details/gtatmbefdr.html

?string $name = null
来源：http://dali.pengpengdd.cyou/Article/details/gtbpktwjqx.html

[U47] PHP：联合类型
来源：http://dali.zhiwuduotai.top/Article/details/gtfgrkvhwk.html

int|string $id
来源：http://dali.0kj1m.cn/Article/details/gtwjivdjwi.html

[U48] PHP：纯枚举
来源：http://dali.meibo888.top/Article/details/gtlxyjuuon.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jqgufenzy.top/Article/details/gtaayucaom.html

[U49] PHP：只读属性
来源：http://dali.birdmap.top/Article/details/gtnrnskzpw.html

public readonly string $name
来源：http://dali.nanxuanxn.top/Article/details/gtjlorvssa.html

[U50] PHP：构造器属性提升
来源：http://dali.jinqigfzy.top/Article/details/gtsvxryuov.html

public function __construct(private int $id) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmfhbkoh.html

[U51] PHP：数组解构
来源：http://dali.quarkkingdee.top/Article/details/gttaxgtgln.html

[$a, $b] = $arr;
来源：http://dali.yuanzhike.top/Article/details/gtvhoqunww.html

[U52] PHP：箭头函数
来源：http://dali.ppjwa.cn/Article/details/gtpsfpkxsf.html

$double = fn($x) => $x * 2;
来源：http://dali.c1oappe.top/Article/details/gtxgqnbefe.html

[U53] PHP：空合并运算符
来源：http://dali.hammf.cn/Article/details/gtthddcocb.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinqigfzy.top/Article/details/gtwqcuxbbb.html

[U54] PHP：空安全调用
来源：http://dali.xuanzx.com/Article/details/gtfhjtllzf.html

$obj?->method()
来源：http://dali.yuanzhike.top/Article/details/gtlldmvydi.html

[U55] PHP：match 表达式
来源：http://dali.zdqjudy.top/Article/details/gtgopigzxx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.c1oappe.top/Article/details/gtnxendhzl.html

[U56] PHP：命名参数
来源：http://dali.guannengcc.top/Article/details/gtksbwrfir.html

f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gtrwjmrbbk.html

[U57] PHP：字符串插值
来源：http://dali.tanke756.top/Article/details/gtmlmtxohi.html

"值: {$a}"
来源：http://dali.havefunace.top/Article/details/gtvpyhnzav.html

[U58] PHP：数组三件套
来源：http://dali.havefunace.top/Article/details/gtfhncfpjl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtbyviwaqs.html

[U59] PHP：自定义排序
来源：http://dali.aibaodan.cn/Article/details/gtnhwzjwhg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sysykeji.top/Article/details/gthzxmwgqn.html

[U60] PHP：JSON 编解码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqtudffp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xinyue.icu/Article/details/gtfpvfxrtf.html

[U61] PHP：正则
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjrwliqq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xinyue.icu/Article/details/gtphdwhuwu.html

[U62] PHP：日期对象
来源：http://dali.ydzc1.top/Article/details/gtvopxqwxt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.nwbrower.top/Article/details/gtteokcjmp.html

[U63] PHP：文件读写
来源：http://dali.mhx1999.top/Article/details/gtdgxhgeaw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yj202588.top/Article/details/gtlmlysefj.html

[U64] PHP：目录遍历
来源：http://dali.yangfankeji.com/Article/details/gtaodcxovo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.fengsongda.top/Article/details/gtzxpcizss.html

[U65] PHP：会话
来源：http://dali.andypj.xyz/Article/details/gtgcljhsdo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtsgwelawn.html

[U66] PHP：设置 Cookie
来源：http://dali.gzhubu.top/Article/details/gtfvstvzfs.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.9152youxi.cn/Article/details/gtynxcgoef.html

[U67] PHP：处理文件上传
来源：http://dali.cqqwz.cn/Article/details/gtrqpmyocs.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jinqigufen.top/Article/details/gtvbdyzorr.html

[U68] PHP：PDO 连接
来源：http://dali.yuanzhike.top/Article/details/gtvwbnhhbn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.redwolf501.top/Article/details/gtejyodqsw.html

[U69] PHP：PDO 预处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtsykxwfmj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.chenzaomai.com/Article/details/gtmiqanpom.html

[U70] PHP：PDO 事务
来源：http://dali.tianlin.xyz/Article/details/gtsqopmexi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hongshengwenyu.top/Article/details/gtltaessap.html

[U71] PHP：抛出异常
来源：http://dali.yangfankeji.com/Article/details/gtttffolse.html

throw new RuntimeException("失败", 500);
来源：http://dali.jlsjyb.cn/Article/details/gtctunioqa.html

[U72] PHP：写错误日志
来源：http://dali.smart0.xyz/Article/details/gtaquqkddd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.feifeiyinyue.top/Article/details/gtuucqkitp.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhiwuduotai.top/Article/details/gthfpviblq.html

parse_ini_file("config.ini", true)
来源：http://dali.yj202588.top/Article/details/gtnkazglns.html

[U74] PHP：读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gtliwurewb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj20258888.top/Article/details/gtfkmvyuer.html

[U75] PHP：依赖注入
来源：http://dali.daxiang520.top/Article/details/gtmybmkrlm.html

composer require psr/container
来源：http://dali.gzhubu.top/Article/details/gtcpkmfsjp.html

[U76] PHP：简单路由
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxlplnxe.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cashguo.top/Article/details/gtzrwbesjf.html

[U77] PHP：模板渲染
来源：http://dali.cheryme.top/Article/details/gtufjnanke.html

composer require twig/twig
来源：http://dali.jiagoushi.top/Article/details/gtfqgzzrhe.html

[U78] PHP：单元测试
来源：http://dali.ppjwa.cn/Article/details/gtfpvnobdj.html

composer require --dev phpunit/phpunit
来源：http://dali.feifeiyinyue.top/Article/details/gtndjgzrtw.html

[U79] PHP：静态分析
来源：http://dali.jianghu66.top/Article/details/gtubsqpklm.html

composer require --dev phpstan/phpstan
来源：http://dali.zycfv.cn/Article/details/gtmkhbxoix.html

[U80] PHP：代码规范修复
来源：http://dali.andypj.xyz/Article/details/gthpblliwd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.meibo888.top/Article/details/gtppqexmch.html


<!-- 参考信息 -->