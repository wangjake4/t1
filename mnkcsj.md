代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gtbwrsctwo.html

[S55] C++：结构化绑定
来源：http://dali.aizwys.cn/Article/details/gtuizqofjt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgufenzy.top/Article/details/gtlztsefoi.html

[S56] C++：optional
来源：http://dali.yvedp.cn/Article/details/gtvvtmihpg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfgkfgsx.html

[S57] C++：编译期常量
来源：http://dali.shzxlz.cn/Article/details/gttrbmtokq.html

constexpr int N = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtzpkgvccd.html

[S58] C++：命名空间
来源：http://dali.gaohongyu789.top/Article/details/gtlilijslz.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuanzhike.top/Article/details/gtjyrewwcg.html

[S59] C++：静态断言
来源：http://dali.shuidangran.top/Article/details/gtevrevktv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.kuanghao11.cn/Article/details/gtiklkdcji.html

[S60] C++：遍历并删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gtzkzdekdy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.svipenyu.cn/Article/details/gtxogrruax.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtaagjtgcr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gtouptrxfh.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gttciwucrm.html

[T01] Kotlin：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtpygmxnsw.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gtqsmzwpoy.html

[T02] Kotlin：变量
来源：http://dali.haohaochexian.top/Article/details/gtgtzpfkvt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hongshengwenyu.top/Article/details/gtbzlrcegl.html

[T03] Kotlin：字符串模板
来源：http://dali.cheryme.top/Article/details/gtzoumvbxb.html

"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gtvesgabkf.html

[T04] Kotlin：空安全
来源：http://dali.haohaochexian.top/Article/details/gtbpwoafft.html

val n: String? = null;  n?.length
来源：http://dali.snrcjt.cn/Article/details/gtxzlyeovu.html

[T05] Kotlin：when 表达式
来源：http://dali.haohaochexian.top/Article/details/gtaudlfvxh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.smart0.xyz/Article/details/gtkcgukfkw.html

[T06] Kotlin：集合映射
来源：http://dali.guowangkeji.top/Article/details/gtbwbftwgw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtcxashwjl.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gtiadkdbxg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ivvv.top/Article/details/gthwhnmqoh.html

[T08] Kotlin：数据类
来源：http://dali.hfpthk.cn/Article/details/gtyipyglyx.html

data class User(val name: String, val age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gtzpdrzeby.html

[T09] Kotlin：扩展函数
来源：http://dali.hywenlv.cn/Article/details/gthtbhdtac.html

fun String.exclaim() = this + "!"
来源：http://dali.bjfxy.top/Article/details/gtgmkuoqix.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gtpynnpksp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ppjwa.cn/Article/details/gtliozexie.html

[T11] Kotlin：协程
来源：http://dali.tian-w.cn/Article/details/gtjifxjvgi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jyoumei.cn/Article/details/gtumysvspo.html

[T12] Kotlin：解构声明
来源：http://dali.vqdsnc.cn/Article/details/gtqicotcfe.html

val (a, b) = Pair(1, 2)
来源：http://dali.tanke756.top/Article/details/gtiziyetyb.html

[T13] Kotlin：只读 Map
来源：http://dali.yangfankeji.com/Article/details/gtmjyncgzh.html

val m = mapOf("a" to 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfonqoie.html

[T14] Kotlin：循环
来源：http://dali.sxryk.cn/Article/details/gttzqhvpdw.html

for (i in 1..10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gtnoprwgex.html

[T15] Kotlin：接口
来源：http://dali.gogol.net.cn/Article/details/gtwhaplgyc.html

interface Shape { fun area(): Double }
来源：http://dali.jianghu66.top/Article/details/gtuwygmdzp.html

[T16] Swift：Hello World
来源：http://dali.bjfxy.top/Article/details/gtiakxnelf.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtvzcdezgp.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtthrailtf.html

var a = 1;  let b = 2
来源：http://dali.sysykeji.top/Article/details/gtwuhdhnwr.html

[T18] Swift：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gtfrhopezm.html

"值: \(b)"
来源：http://dali.xziqi.cn/Article/details/gtpkldpdki.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqsgbvcu.html

if let n = opt { print(n) }
来源：http://dali.c1oappe.top/Article/details/gtvqolofqf.html

[T20] Swift：数组操作
来源：http://dali.xuetiantiany.cn/Article/details/gtefbmknyj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuxming.cn/Article/details/gtbwtgzswf.html

[T21] Swift：遍历
来源：http://dali.zycfv.cn/Article/details/gtvaergyew.html

for x in a { print(x) }
来源：http://dali.hongshengwenyu.top/Article/details/gtzrdsvvfo.html

[T22] Swift：字典
来源：http://dali.tian-w.cn/Article/details/gttgtvkioc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ivvv.top/Article/details/gtmgvukwte.html

[T23] Swift：函数
来源：http://dali.zhengqikj.top/Article/details/gteqmfvidd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtjkhxzphy.html

[T24] Swift：闭包
来源：http://dali.hnxiangtu.top/Article/details/gteymzzrjb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtabjvomzo.html

[T25] Swift：结构体
来源：http://dali.snrcjt.cn/Article/details/gtpvnqafmh.html

struct P { var x: Int }
来源：http://dali.guowangkeji.top/Article/details/gtmsqtuqor.html

[T26] Swift：类与重写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewawumrq.html

class A: Base { override func f() {} }
来源：http://dali.havefunace.top/Article/details/gtzzimeisv.html

[T27] Swift：错误处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokjlfdwc.html

do { try f() } catch { print(error) }
来源：http://dali.daria6918.cn/Article/details/gtitgfnmfx.html

[T28] Swift：枚举
来源：http://dali.aibaodan.cn/Article/details/gttdaaccfw.html

enum Color { case red, green }
来源：http://dali.pengpengdd.cyou/Article/details/gtdkjlnjqz.html

[T29] Swift：guard 提前返回
来源：http://dali.quarkkingdee.top/Article/details/gtxufiftnt.html

guard let x = opt else { return }
来源：http://dali.zhoulong.xyz/Article/details/gtxmifwuml.html

[T30] Swift：协议
来源：http://dali.redwolf501.top/Article/details/gtcwhaplxh.html

protocol Shape { func area() -> Double }
来源：http://dali.daria6918.cn/Article/details/gtbryqqhhe.html

[T31] Lua：Hello World
来源：http://dali.xuanzx.com/Article/details/gtflcetbqu.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtzuuyqrtt.html

[T32] Lua：局部变量
来源：http://dali.zhengqikj.top/Article/details/gtynggqnkb.html

local a = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtavznnctg.html

[T33] Lua：表（数组）
来源：http://dali.yvedp.cn/Article/details/gtpnjibcby.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.fengsongda.top/Article/details/gtvkjgogmb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gtdijzuaii.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxuanxn.top/Article/details/gtxyonmytu.html

[T35] Lua：字典表
来源：http://dali.ydzc1.top/Article/details/gthvozfkvq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtfykseajy.html

[T36] Lua：函数
来源：http://dali.ppjwa.cn/Article/details/gtudifbnjp.html

function add(a, b) return a + b end
来源：http://dali.jinqigufen.top/Article/details/gtflubtqfu.html

[T37] Lua：字符串拼接
来源：http://dali.yj202588.top/Article/details/gtcmtisvxp.html

"a" .. "b"
来源：http://dali.aibaodan.cn/Article/details/gtnyhibksu.html

[T38] Lua：条件
来源：http://dali.316326.xyz/Article/details/gtcbkqrtvt.html

if x > 0 then print("正") end
来源：http://dali.yangfankeji.com/Article/details/gtloextzqy.html

[T39] Lua：模式匹配
来源：http://dali.smart0.xyz/Article/details/gtfpeirvth.html

string.find(s, "%d+")
来源：http://dali.yuxming.cn/Article/details/gtffqvukcx.html

[T40] Lua：元表
来源：http://dali.gaohongyu789.top/Article/details/gtauiwybdu.html

setmetatable({}, { __index = base })
来源：http://dali.sxryk.cn/Article/details/gtggyzwxgo.html

[T41] Perl：Hello World
来源：http://dali.fzhhl.top/Article/details/gtvboauvfa.html

print "Hello\n";
来源：http://dali.0kj1m.cn/Article/details/gtjsgoskpy.html

[T42] Perl：变量类型
来源：http://dali.jlsjyb.cn/Article/details/gtomnqyxts.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.9152youxi.cn/Article/details/gtfqjfrjjh.html

[T43] Perl：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtnkmdcoyd.html

"值: $a"
来源：http://dali.ppjwa.cn/Article/details/gtfzwyeuvb.html

[T44] Perl：条件
来源：http://dali.sysykeji.top/Article/details/gtnzvakaor.html

if ($a > 0) { print "正"; }
来源：http://dali.daxiang520.top/Article/details/gtdzykhyat.html

[T45] Perl：数组遍历
来源：http://dali.smart0.xyz/Article/details/gtrrkhbctn.html

for my $x (@arr) { print $x; }
来源：http://dali.jiagoushi.top/Article/details/gtalkxqxto.html

[T46] Perl：哈希操作
来源：http://dali.guowangkeji.top/Article/details/gtplcsdcpo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.daxiang520.top/Article/details/gtuxgztfsj.html

[T47] Perl：正则捕获
来源：http://dali.pengpengdd.cyou/Article/details/gtucjnrxnq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ppjwa.cn/Article/details/gtxtqaqott.html

[T48] Perl：正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtioqthhbw.html

$s =~ s/old/new/g;
来源：http://dali.jlsjyb.cn/Article/details/gtnrebhspq.html

[T49] Perl：函数
来源：http://dali.zhixingplan.top/Article/details/gtztvcdbrd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtnftxcnyy.html

[T50] Perl：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtuwxbokur.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cqqwz.cn/Article/details/gtqpswawaw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ppjwa.cn/Article/details/gtchsrklpx.html

[T51] Scala：Hello World
来源：http://dali.ydzc1.top/Article/details/gtkpukwfyl.html

println("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtcuxzuzrg.html

[T52] Scala：变量
来源：http://dali.0kj1m.cn/Article/details/gttnstqgoc.html

val a = 1;  var b = 2
来源：http://dali.meibo888.top/Article/details/gtrcxnvzsh.html

[T53] Scala：字符串插值
来源：http://dali.sweek.top/Article/details/gtoplglqry.html

s"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gtojiyzdvq.html

[T54] Scala：集合映射
来源：http://dali.shuidangran.top/Article/details/gtnekchkky.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtanpbelqf.html

[T55] Scala：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gtjydsznbo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtvcfoxlls.html

[T56] Scala：样例类
来源：http://dali.gogol.net.cn/Article/details/gthfhcvbma.html

case class User(name: String, age: Int)
来源：http://dali.jinqigfzy.top/Article/details/gtinparroz.html

[T57] Scala：模式匹配
来源：http://dali.jqgfzy.top/Article/details/gtbljoztxz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tian-w.cn/Article/details/gtztshpsbh.html

[T58] Scala：函数定义
来源：http://dali.yueranfly.top/Article/details/gtjdvnuolh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gotoacloud.top/Article/details/gtsxypzhor.html

[T59] Scala：循环
来源：http://dali.fengsongda.top/Article/details/gtvmptllap.html

for (i <- 1 to 10) println(i)
来源：http://dali.quarkkingdee.top/Article/details/gtqkrnyedn.html

[T60] Scala：折叠
来源：http://dali.birdmap.top/Article/details/gtsnkfnvhe.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tian-w.cn/Article/details/gtabqvekqv.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtyowfrbiu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yueranfly.top/Article/details/gtyeeddhqt.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gthwqhpwhp.html

[U01] Py：创建虚拟环境
来源：http://dali.pengpengdd.cyou/Article/details/gtgkfqqint.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sufxvd.cn/Article/details/gtjwrgurob.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cashguo.top/Article/details/gtzjbztiox.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj20258888.top/Article/details/gtgsrfarwu.html

[U03] Py：加载 .env 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhizpuhn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.havefunace.top/Article/details/gtjyobxjes.html

[U04] Py：变量调试打印
来源：http://dali.redwolf501.top/Article/details/gtkagjxkzj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hysaishi.cn/Article/details/gtykdrjpzm.html

[U05] Py：列表去重且保序
来源：http://dali.guowangkeji.top/Article/details/gtxlgyaxal.html

list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gtrohxkjuu.html

[U06] Py：合并两个字典
来源：http://dali.ybcxt.top/Article/details/gteqzlaltu.html

{**a, **b}
来源：http://dali.daria6918.cn/Article/details/gtsjdxagqw.html

[U07] Py：反转字典键值
来源：http://dali.cdnleiting.top/Article/details/gtvnadehiu.html

{v: k for k, v in d.items()}
来源：http://dali.aibaodan.cn/Article/details/gtkfjgjuut.html

[U08] Py：展平二维列表
来源：http://dali.yuanzhike.top/Article/details/gtgnmmxdek.html

[y for x in nested for y in x]
来源：http://dali.hysaishi.cn/Article/details/gtsrcovigl.html

[U09] Py：字典取最大值的键
来源：http://dali.tianlin.xyz/Article/details/gtuwtyirju.html

max(d, key=d.get)
来源：http://dali.guowangkeji.top/Article/details/gtngkadomy.html

[U10] Py：按值排序字典
来源：http://dali.daria6918.cn/Article/details/gtrublpwcv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cdnleiting.top/Article/details/gtxdnlxlgu.html

[U11] Py：生成器表达式
来源：http://dali.xinyue.icu/Article/details/gthlapoysn.html

(x * 2 for x in arr)
来源：http://dali.smart0.xyz/Article/details/gttyqbyurr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhoulong.xyz/Article/details/gtatrdixuh.html

Counter(arr).most_common(3)
来源：http://dali.tanke756.top/Article/details/gtoawjbnar.html

[U13] Py：固定长度队列
来源：http://dali.feifeiyinyue.top/Article/details/gtrsaxckjw.html

deque(maxlen=10)
来源：http://dali.shanyushiyangtech.top/Article/details/gtalansgqq.html

[U14] Py：分组收集到列表
来源：http://dali.quarkkingdee.top/Article/details/gtrmllnhzo.html

defaultdict(list)
来源：http://dali.yuxming.cn/Article/details/gtnzqijqwy.html

[U15] Py：高精度计时
来源：http://dali.guannengcc.top/Article/details/gtrfkmmhol.html

t = time.perf_counter()
来源：http://dali.xinyue.icu/Article/details/gteemfxpdl.html

[U16] Py：命令行参数解析
来源：http://dali.shzxlz.cn/Article/details/gtfnfdfgzo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sxryk.cn/Article/details/gtafifwqjk.html

[U17] Py：初始化日志
来源：http://dali.kuanghao11.cn/Article/details/gthvnmyaqw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hysaishi.cn/Article/details/gtcelaftgo.html

[U18] Py：预编译正则
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavhnzuol.html

pat = re.compile(r"\d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtjwjksoui.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gtzzuitist.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpropwdzg.html

[U20] Py：缓存函数结果
来源：http://dali.meibo888.top/Article/details/gttbqywrof.html

@functools.lru_cache(maxsize=None)
来源：http://dali.daxiang520.top/Article/details/gtpoflvhxf.html

[U21] Py：自定义上下文管理器
来源：http://dali.fzhhl.top/Article/details/gtwjbktyho.html

@contextlib.contextmanager
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcscvfiyw.html

[U22] Py：矩阵转置
来源：http://dali.nanxuanxn.top/Article/details/gthfcttvqu.html

list(zip(*m))
来源：http://dali.chenjidiqi.icu/Article/details/gtdukckdsi.html

[U23] Py：分块读取大文件
来源：http://dali.hnqzz.top/Article/details/gtoouovxvv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.316326.xyz/Article/details/gtfdsqdpkv.html

[U24] Py：路径操作
来源：http://dali.jianghu66.top/Article/details/gtblmhzyxm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzchfleq.html

[U25] Py：CSV 按字典读
来源：http://dali.gaohongyu789.top/Article/details/gttymadczx.html

csv.DictReader(f)
来源：http://dali.fengsongda.top/Article/details/gtijucukxr.html

[U26] Py：并发下载
来源：http://dali.wangdashe.top/Article/details/gtndcpfnwn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yj20258.top/Article/details/gttfzifmwo.html

[U27] Py：异步 HTTP
来源：http://dali.pycfn.com/Article/details/gtrgqnlkdf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuxming.cn/Article/details/gterofedjd.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gtbfutafxn.html

UserId = int
来源：http://dali.jianghu66.top/Article/details/gtkuxfzorn.html

[U29] Py：属性校验
来源：http://dali.yj20258888.top/Article/details/gtsgazoqrr.html

@property 与 @x.setter 配合
来源：http://dali.ivvv.top/Article/details/gtdmokkxzw.html

[U30] Py：数据类
来源：http://dali.nanxuanxn.top/Article/details/gtzfltsnht.html

@dataclass(slots=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqngjavke.html

[U31] Py：单测
来源：http://dali.nanxuanxn.top/Article/details/gtnnuabxuh.html

python -m pytest -q
来源：http://dali.yuanzhike.top/Article/details/gtrlpdqdna.html

[U32] Py：代码格式化
来源：http://dali.redwolf501.top/Article/details/gtssshbake.html

ruff format . && ruff check --fix .
来源：http://dali.shzxlz.cn/Article/details/gtdzjxpcic.html

[U33] Py：打包发布
来源：http://dali.meibo888.top/Article/details/gtezrcdprq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jiagoushi.top/Article/details/gtooasucrd.html

[U34] Py：判断编码
来源：http://dali.hnqzz.top/Article/details/gtjctlpzoc.html

chardet.detect(raw)
来源：http://dali.hfpthk.cn/Article/details/gtdammjtsu.html

[U35] Py：发送邮件
来源：http://dali.zhongyouzk.top/Article/details/gtlnxwsxlu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yueranfly.top/Article/details/gtnlskbmuw.html

[U36] Py：定时任务
来源：http://dali.hongshengwenyu.top/Article/details/gtwoozdqqv.html

schedule.every(10).minutes.do(job)
来源：http://dali.xinyue.icu/Article/details/gtqesqxtri.html

[U37] Py：读写 Excel
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbrqitsh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tianlin.xyz/Article/details/gtlnfyiycg.html

[U38] Py：获取脚本所在目录
来源：http://dali.gotoacloud.top/Article/details/gtnardwdnn.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gtglalccnf.html

[U39] Py：判断是否在交互环境
来源：http://dali.sweek.top/Article/details/gtcitabeyi.html

sys.stdout.isatty()
来源：http://dali.jqgfzy.top/Article/details/gtzjugngnt.html

[U40] Py：打印到标准错误
来源：http://dali.kuanghao11.cn/Article/details/gtivwiqqam.html

print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gtacxhncaz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.havefunace.top/Article/details/gtckejpbox.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shuidangran.top/Article/details/gtwuyzyjpf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yvedp.cn/Article/details/gticrxsxeh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttoapmnpv.html

[U43] PHP：声明命名空间
来源：http://dali.xylfe.cn/Article/details/gtslortchz.html

namespace App\Http;
来源：http://dali.guowangkeji.top/Article/details/gtjsptcbzk.html

[U44] PHP：开启严格类型
来源：http://dali.xziqi.cn/Article/details/gtladphehv.html

declare(strict_types=1);
来源：http://dali.jlsjyb.cn/Article/details/gtmxwrlevc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.dashuyun.cn/Article/details/gtbvepgzwa.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gtojdeheoi.html

[U46] PHP：可空类型
来源：http://dali.sxryk.cn/Article/details/gtmuqmjjbw.html

?string $name = null
来源：http://dali.hammf.cn/Article/details/gtlhpxvicf.html

[U47] PHP：联合类型
来源：http://dali.birdmap.top/Article/details/gtvdlrsfap.html

int|string $id
来源：http://dali.daxiang520.top/Article/details/gtxsrnlral.html

[U48] PHP：纯枚举
来源：http://dali.hnqzz.top/Article/details/gtqbaabxsh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ybcxt.top/Article/details/gtzgputcee.html

[U49] PHP：只读属性
来源：http://dali.wangdashe.top/Article/details/gtpytzkdpm.html

public readonly string $name
来源：http://dali.birdmap.top/Article/details/gtbojbcvqr.html

[U50] PHP：构造器属性提升
来源：http://dali.hysaishi.cn/Article/details/gtjphtiuxw.html

public function __construct(private int $id) {}
来源：http://dali.quarkkingdee.top/Article/details/gtskibmqbr.html

[U51] PHP：数组解构
来源：http://dali.daria6918.cn/Article/details/gtuzwasuoh.html

[$a, $b] = $arr;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllfdleyn.html

[U52] PHP：箭头函数
来源：http://dali.zycfv.cn/Article/details/gtdekpbgto.html

$double = fn($x) => $x * 2;
来源：http://dali.xylfe.cn/Article/details/gtzwiufmae.html

[U53] PHP：空合并运算符
来源：http://dali.jyoumei.cn/Article/details/gtrkextixl.html

$v = $a ?? $b ?? "default";
来源：http://dali.fzhhl.top/Article/details/gtatmxmvyp.html

[U54] PHP：空安全调用
来源：http://dali.jlsjyb.cn/Article/details/gtpqulgvme.html

$obj?->method()
来源：http://dali.shuidangran.top/Article/details/gtqcmljznv.html

[U55] PHP：match 表达式
来源：http://dali.fzhhl.top/Article/details/gtamiujuox.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cashguo.top/Article/details/gtqumexvib.html

[U56] PHP：命名参数
来源：http://dali.316326.xyz/Article/details/gtwuhinxck.html

f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtbpeakucy.html

[U57] PHP：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtzrnbzrur.html

"值: {$a}"
来源：http://dali.shangyingyoupin.top/Article/details/gtjbnittka.html

[U58] PHP：数组三件套
来源：http://dali.jinqigfzy.top/Article/details/gtlcobqgym.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.chenlongwang.top/Article/details/gtopcyjuha.html

[U59] PHP：自定义排序
来源：http://dali.mhx1999.top/Article/details/gtswczawbs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.smart0.xyz/Article/details/gtvcnlzjka.html

[U60] PHP：JSON 编解码
来源：http://dali.sweek.top/Article/details/gtlphkcrme.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfuraswt.html

[U61] PHP：正则
来源：http://dali.gzhubu.top/Article/details/gteexlgulo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.aizwys.cn/Article/details/gtorlikxxi.html

[U62] PHP：日期对象
来源：http://dali.ybcxt.top/Article/details/gtlswvirox.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hnxiangtu.top/Article/details/gtoosqjupg.html

[U63] PHP：文件读写
来源：http://dali.xuanzx.com/Article/details/gtdrsmmusa.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zycfv.cn/Article/details/gtiyycyjan.html

[U64] PHP：目录遍历
来源：http://dali.pycfn.com/Article/details/gteolsyuww.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shangyingyoupin.top/Article/details/gtwulhqzyc.html

[U65] PHP：会话
来源：http://dali.feifeiyinyue.top/Article/details/gtkomlvxfy.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtkdysizfc.html

[U66] PHP：设置 Cookie
来源：http://dali.pengpengdd.cyou/Article/details/gtrpngcqwf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hnqzz.top/Article/details/gtcvbtfpws.html

[U67] PHP：处理文件上传
来源：http://dali.jqgufenzy.top/Article/details/gtgxjsbvqe.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.vqdsnc.cn/Article/details/gtrtvuuxas.html

[U68] PHP：PDO 连接
来源：http://dali.zhoulong.xyz/Article/details/gtevdzywri.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gtbthhqmuz.html

[U69] PHP：PDO 预处理
来源：http://dali.dianchejie.cn/Article/details/gtoragrgfo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shuidangran.top/Article/details/gtotlyhrof.html

[U70] PHP：PDO 事务
来源：http://dali.feifeiyinyue.top/Article/details/gtxxoaihnf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sysykeji.top/Article/details/gtecoyhlnr.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gtbblvpyus.html

throw new RuntimeException("失败", 500);
来源：http://dali.316326.xyz/Article/details/gtuljjpmcp.html

[U72] PHP：写错误日志
来源：http://dali.tian-w.cn/Article/details/gtggvsgvwa.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shuidangran.top/Article/details/gtgvemtqzn.html

[U73] PHP：读取 ini 配置
来源：http://dali.shzxlz.cn/Article/details/gtkvijsawi.html

parse_ini_file("config.ini", true)
来源：http://dali.tanke756.top/Article/details/gtqgbcpidj.html

[U74] PHP：读取环境变量
来源：http://dali.daxiang520.top/Article/details/gtliqtxcii.html

getenv("APP_ENV") ?: "production"
来源：http://dali.aibaodan.cn/Article/details/gttrfkwuoy.html

[U75] PHP：依赖注入
来源：http://dali.hywenlv.cn/Article/details/gtuoiwymcr.html

composer require psr/container
来源：http://dali.sxryk.cn/Article/details/gtzsnfvcpm.html

[U76] PHP：简单路由
来源：http://dali.quarkkingdee.top/Article/details/gtaoruokqe.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jyoumei.cn/Article/details/gtlxlkzcnx.html

[U77] PHP：模板渲染
来源：http://dali.9152youxi.cn/Article/details/gtpkvbsagn.html

composer require twig/twig
来源：http://dali.chenlongwang.top/Article/details/gtnuxcbigu.html

[U78] PHP：单元测试
来源：http://dali.birdmap.top/Article/details/gtnuwdshej.html

composer require --dev phpunit/phpunit
来源：http://dali.gogol.net.cn/Article/details/gtqlkmqwdk.html

[U79] PHP：静态分析
来源：http://dali.iojbl.cn/Article/details/gtuvuyorqt.html

composer require --dev phpstan/phpstan
来源：http://dali.daxiang520.top/Article/details/gtrlquival.html

[U80] PHP：代码规范修复
来源：http://dali.xziqi.cn/Article/details/gtmetzlvxd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.fengsongda.top/Article/details/gtmhwxxwsf.html


<!-- 参考信息 -->