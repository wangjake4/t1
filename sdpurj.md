代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xziqi.cn/Article/details/gtlvzonrik.html

[S55] C++：结构化绑定
来源：http://dali.guannengcc.top/Article/details/gtthveszhr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjaoguul.html

[S56] C++：optional
来源：http://dali.redwolf501.top/Article/details/gtfihmpmfg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hongshengwenyu.top/Article/details/gtnblxmvwq.html

[S57] C++：编译期常量
来源：http://dali.shuidangran.top/Article/details/gtawzexyjv.html

constexpr int N = 10;
来源：http://dali.aizwys.cn/Article/details/gtogzunbkt.html

[S58] C++：命名空间
来源：http://dali.yonumen.top/Article/details/gtuxrpjrud.html

namespace ns { int f() { return 1; } }
来源：http://dali.daria6918.cn/Article/details/gtzskrosvb.html

[S59] C++：静态断言
来源：http://dali.yongpay.top/Article/details/gtqjuuxecr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.feifeiyinyue.top/Article/details/gtioguhpci.html

[S60] C++：遍历并删除元素
来源：http://dali.sysykeji.top/Article/details/gtpuxfktvy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gotoacloud.top/Article/details/gtkkvcvnbu.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtyoepnivl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cdnleiting.top/Article/details/gtgzszejgp.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtyelceppw.html

[T01] Kotlin：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtpqxokpcd.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtdcbqklmq.html

[T02] Kotlin：变量
来源：http://dali.kuanghao11.cn/Article/details/gtktaddpti.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258.top/Article/details/gtxutnwlqt.html

[T03] Kotlin：字符串模板
来源：http://dali.0kj1m.cn/Article/details/gtibrlinbe.html

"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gtquxobtax.html

[T04] Kotlin：空安全
来源：http://dali.mhx1999.top/Article/details/gtybzghzmj.html

val n: String? = null;  n?.length
来源：http://dali.gaohongyu789.top/Article/details/gtdihvfpcn.html

[T05] Kotlin：when 表达式
来源：http://dali.andypj.xyz/Article/details/gtwsrqlmns.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shangyingyoupin.top/Article/details/gtgkgkvowh.html

[T06] Kotlin：集合映射
来源：http://dali.aizwys.cn/Article/details/gtzpnglxmu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guannengcc.top/Article/details/gtrxwltccf.html

[T07] Kotlin：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gtqoankqrr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.9152youxi.cn/Article/details/gtgyhlroqn.html

[T08] Kotlin：数据类
来源：http://dali.cheryme.top/Article/details/gtdmwiwhyj.html

data class User(val name: String, val age: Int)
来源：http://dali.smart0.xyz/Article/details/gtyadonusu.html

[T09] Kotlin：扩展函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrglcvzgf.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgfzy.top/Article/details/gtnuwnyrph.html

[T10] Kotlin：默认参数
来源：http://dali.gaohongyu789.top/Article/details/gtwtgzwosr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cashguo.top/Article/details/gtutxvboqw.html

[T11] Kotlin：协程
来源：http://dali.jiagoushi.top/Article/details/gtchnilzwn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhiwuduotai.top/Article/details/gtpwcytdji.html

[T12] Kotlin：解构声明
来源：http://dali.daxiang520.top/Article/details/gtxeecnmew.html

val (a, b) = Pair(1, 2)
来源：http://dali.sweek.top/Article/details/gttkqesdvr.html

[T13] Kotlin：只读 Map
来源：http://dali.cheryme.top/Article/details/gtyqdojtit.html

val m = mapOf("a" to 1)
来源：http://dali.hammf.cn/Article/details/gtzxqocqrn.html

[T14] Kotlin：循环
来源：http://dali.kuanghao11.cn/Article/details/gtmyzogalm.html

for (i in 1..10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtlljkvnxw.html

[T15] Kotlin：接口
来源：http://dali.zycfv.cn/Article/details/gtdnrrjzex.html

interface Shape { fun area(): Double }
来源：http://dali.hnqzz.top/Article/details/gtiqkuuvcn.html

[T16] Swift：Hello World
来源：http://dali.nwbrower.top/Article/details/gtarvfcaar.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtmdnsaoxe.html

[T17] Swift：变量与常量
来源：http://dali.hfpthk.cn/Article/details/gtiefsqtdm.html

var a = 1;  let b = 2
来源：http://dali.yueranfly.top/Article/details/gtihoyyvih.html

[T18] Swift：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtngnjhjux.html

"值: \(b)"
来源：http://dali.snrcjt.cn/Article/details/gtrxrrtmtv.html

[T19] Swift：可选绑定
来源：http://dali.havefunace.top/Article/details/gtoojzvbqo.html

if let n = opt { print(n) }
来源：http://dali.ppjwa.cn/Article/details/gtlalpqcke.html

[T20] Swift：数组操作
来源：http://dali.tanke756.top/Article/details/gtfudyegog.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hysaishi.cn/Article/details/gtvwyrmpnw.html

[T21] Swift：遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtidzspoqr.html

for x in a { print(x) }
来源：http://dali.yj20258888.top/Article/details/gtzwmpqoru.html

[T22] Swift：字典
来源：http://dali.gaohongyu789.top/Article/details/gtuvckxxdd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jianghu66.top/Article/details/gtbndtfpud.html

[T23] Swift：函数
来源：http://dali.yj202588.top/Article/details/gtgomvwutq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtaylgrfib.html

[T24] Swift：闭包
来源：http://dali.dianchejie.cn/Article/details/gtinpvuvsz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gtvkvcsnds.html

[T25] Swift：结构体
来源：http://dali.chenzaomai.com/Article/details/gtjiiqykqb.html

struct P { var x: Int }
来源：http://dali.jqgufenzy.top/Article/details/gtydwilxzz.html

[T26] Swift：类与重写
来源：http://dali.shzxlz.cn/Article/details/gtpmytonjg.html

class A: Base { override func f() {} }
来源：http://dali.ydzc1.top/Article/details/gtryfmffuj.html

[T27] Swift：错误处理
来源：http://dali.shzxlz.cn/Article/details/gtzldvelda.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258.top/Article/details/gtqkycztvv.html

[T28] Swift：枚举
来源：http://dali.fengsongda.top/Article/details/gthrypwswy.html

enum Color { case red, green }
来源：http://dali.ehwqpu.com/Article/details/gtrclwlbfj.html

[T29] Swift：guard 提前返回
来源：http://dali.ivvv.top/Article/details/gtvqkbkmxl.html

guard let x = opt else { return }
来源：http://dali.haohaochexian.top/Article/details/gttzuwberf.html

[T30] Swift：协议
来源：http://dali.zhiwuduotai.top/Article/details/gtfpfgtitj.html

protocol Shape { func area() -> Double }
来源：http://dali.yuanzhike.top/Article/details/gtxjlvfusc.html

[T31] Lua：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtlqcykbxi.html

print("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtwtyqoana.html

[T32] Lua：局部变量
来源：http://dali.nwbrower.top/Article/details/gttnpmhmgz.html

local a = 1
来源：http://dali.zhongyouzk.top/Article/details/gtqnuzblgq.html

[T33] Lua：表（数组）
来源：http://dali.mhx1999.top/Article/details/gtjpnyupjn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.9152youxi.cn/Article/details/gtjlvyahqc.html

[T34] Lua：遍历表
来源：http://dali.guowangkeji.top/Article/details/gtvulfzkwi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xuanzx.com/Article/details/gtmklnfqsk.html

[T35] Lua：字典表
来源：http://dali.yuanzhike.top/Article/details/gtypyjfxuj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ivvv.top/Article/details/gtxhztmbih.html

[T36] Lua：函数
来源：http://dali.zhixingplan.top/Article/details/gtnynfkzad.html

function add(a, b) return a + b end
来源：http://dali.ppjwa.cn/Article/details/gtrtjggoax.html

[T37] Lua：字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gtzbxfkjbm.html

"a" .. "b"
来源：http://dali.zhiwuduotai.top/Article/details/gthmoexxei.html

[T38] Lua：条件
来源：http://dali.yuxming.cn/Article/details/gtpdrrctjs.html

if x > 0 then print("正") end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgqruawt.html

[T39] Lua：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtpzxeazlg.html

string.find(s, "%d+")
来源：http://dali.yj202588.top/Article/details/gtdvploqsj.html

[T40] Lua：元表
来源：http://dali.aizwys.cn/Article/details/gtelgmjtdf.html

setmetatable({}, { __index = base })
来源：http://dali.dianchejie.cn/Article/details/gtxrgbwqvo.html

[T41] Perl：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtlooznazg.html

print "Hello\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gthuetrcbr.html

[T42] Perl：变量类型
来源：http://dali.smart0.xyz/Article/details/gtlzlcttvv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tanke756.top/Article/details/gtnvkxczek.html

[T43] Perl：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtrdkdmjlm.html

"值: $a"
来源：http://dali.gaohongyu789.top/Article/details/gtlzvefhvq.html

[T44] Perl：条件
来源：http://dali.iojbl.cn/Article/details/gtzajbkfea.html

if ($a > 0) { print "正"; }
来源：http://dali.gogol.net.cn/Article/details/gtfengaqgi.html

[T45] Perl：数组遍历
来源：http://dali.vqdsnc.cn/Article/details/gteamqxqhc.html

for my $x (@arr) { print $x; }
来源：http://dali.aibaodan.cn/Article/details/gtfxfuoaim.html

[T46] Perl：哈希操作
来源：http://dali.havefunace.top/Article/details/gtraiaiork.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ybcxt.top/Article/details/gtonevfnas.html

[T47] Perl：正则捕获
来源：http://dali.chenjidiqi.icu/Article/details/gtbcbjwdps.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkseqhbgn.html

[T48] Perl：正则替换
来源：http://dali.cdnleiting.top/Article/details/gtsbgdpvbh.html

$s =~ s/old/new/g;
来源：http://dali.nanxinkj.top/Article/details/gtprxawifa.html

[T49] Perl：函数
来源：http://dali.aibaodan.cn/Article/details/gtfzctjkvu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtpkecfsgj.html

[T50] Perl：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtyeyifwsm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.bjfxy.top/Article/details/gtaercejqg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.c1oappe.top/Article/details/gtihqdzgkc.html

[T51] Scala：Hello World
来源：http://dali.guannengcc.top/Article/details/gtjckeqrxg.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtfqghxkwf.html

[T52] Scala：变量
来源：http://dali.feifeiyinyue.top/Article/details/gtlhmktagp.html

val a = 1;  var b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoeoookvc.html

[T53] Scala：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gtftwbhjqo.html

s"值: $b"
来源：http://dali.mhx1999.top/Article/details/gtmokiycrb.html

[T54] Scala：集合映射
来源：http://dali.mhx1999.top/Article/details/gtazymmzpm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yj20258.top/Article/details/gtvnrfnste.html

[T55] Scala：集合过滤
来源：http://dali.vqdsnc.cn/Article/details/gtrunzhhgy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fengsongda.top/Article/details/gtezhjsxuq.html

[T56] Scala：样例类
来源：http://dali.jianghu66.top/Article/details/gtkwjtlkxl.html

case class User(name: String, age: Int)
来源：http://dali.hnqzz.top/Article/details/gtqhvluhzq.html

[T57] Scala：模式匹配
来源：http://dali.yangfankeji.com/Article/details/gthhzaktmd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhengqikj.top/Article/details/gtnxhsrvii.html

[T58] Scala：函数定义
来源：http://dali.cheryme.top/Article/details/gthbtvmzss.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj20258.top/Article/details/gtiexflsqy.html

[T59] Scala：循环
来源：http://dali.bjfxy.top/Article/details/gtpcypoplo.html

for (i <- 1 to 10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gtmeldcvwm.html

[T60] Scala：折叠
来源：http://dali.sweek.top/Article/details/gtaglyafiy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258888.top/Article/details/gtntsfbvcs.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtbjfbtffc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sufxvd.cn/Article/details/gttlwwvxyd.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasafnssa.html

[U01] Py：创建虚拟环境
来源：http://dali.wangdashe.top/Article/details/gtfembgart.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.quarkkingdee.top/Article/details/gtgcacufja.html

[U02] Py：导出 / 安装依赖
来源：http://dali.0kj1m.cn/Article/details/gtltivsewu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgfzy.top/Article/details/gtpbkxwhmy.html

[U03] Py：加载 .env 配置
来源：http://dali.hywenlv.cn/Article/details/gtmyedvorh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.dashuyun.cn/Article/details/gtocqsdrcj.html

[U04] Py：变量调试打印
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnjtvght.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xinyue.icu/Article/details/gtqzweexvk.html

[U05] Py：列表去重且保序
来源：http://dali.daria6918.cn/Article/details/gtuzwqbzgh.html

list(dict.fromkeys(arr))
来源：http://dali.daria6918.cn/Article/details/gtmtyxdxxt.html

[U06] Py：合并两个字典
来源：http://dali.yangfankeji.com/Article/details/gtnnbukrxl.html

{**a, **b}
来源：http://dali.feifeiyinyue.top/Article/details/gtykflinag.html

[U07] Py：反转字典键值
来源：http://dali.zdqjudy.top/Article/details/gthbvryjfr.html

{v: k for k, v in d.items()}
来源：http://dali.yuanzhike.top/Article/details/gtxgaqykih.html

[U08] Py：展平二维列表
来源：http://dali.pengpengdd.cyou/Article/details/gtvyojufbm.html

[y for x in nested for y in x]
来源：http://dali.zhongyouzk.top/Article/details/gtlnmyzhfo.html

[U09] Py：字典取最大值的键
来源：http://dali.birdmap.top/Article/details/gtdskmkmfs.html

max(d, key=d.get)
来源：http://dali.havefunace.top/Article/details/gtmbrdnjri.html

[U10] Py：按值排序字典
来源：http://dali.haohaochexian.top/Article/details/gtyhznenqa.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj20258.top/Article/details/gthfezsqhf.html

[U11] Py：生成器表达式
来源：http://dali.ppjwa.cn/Article/details/gtmwjhwbpc.html

(x * 2 for x in arr)
来源：http://dali.zycfv.cn/Article/details/gtkdimvoie.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtlingoogh.html

Counter(arr).most_common(3)
来源：http://dali.gogol.net.cn/Article/details/gtfluauudj.html

[U13] Py：固定长度队列
来源：http://dali.ivvv.top/Article/details/gtirksiudr.html

deque(maxlen=10)
来源：http://dali.dianchejie.cn/Article/details/gtffwwlhpn.html

[U14] Py：分组收集到列表
来源：http://dali.hfpthk.cn/Article/details/gtuogjqcau.html

defaultdict(list)
来源：http://dali.yvedp.cn/Article/details/gtqrajdgzt.html

[U15] Py：高精度计时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfnukkwf.html

t = time.perf_counter()
来源：http://dali.jiagoushi.top/Article/details/gtswxjszpu.html

[U16] Py：命令行参数解析
来源：http://dali.zhixingplan.top/Article/details/gtrulodlap.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hnqzz.top/Article/details/gtrzoyywgc.html

[U17] Py：初始化日志
来源：http://dali.vqdsnc.cn/Article/details/gtmenzdebq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xuanzx.com/Article/details/gtziuguerw.html

[U18] Py：预编译正则
来源：http://dali.ivvv.top/Article/details/gtgikovhqu.html

pat = re.compile(r"\d+")
来源：http://dali.dianchejie.cn/Article/details/gtanrtsosx.html

[U19] Py：正则替换带回调
来源：http://dali.cdnleiting.top/Article/details/gtewnihbvr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daxiang520.top/Article/details/gtqulhnmot.html

[U20] Py：缓存函数结果
来源：http://dali.zycfv.cn/Article/details/gtdvshkoqb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zdqjudy.top/Article/details/gtdzzuwcli.html

[U21] Py：自定义上下文管理器
来源：http://dali.jqgufenzy.top/Article/details/gtcukfwnvp.html

@contextlib.contextmanager
来源：http://dali.jyoumei.cn/Article/details/gtmjriijqv.html

[U22] Py：矩阵转置
来源：http://dali.zhongyouzk.top/Article/details/gtgilzahtw.html

list(zip(*m))
来源：http://dali.fengsongda.top/Article/details/gtpxkrcgkv.html

[U23] Py：分块读取大文件
来源：http://dali.cqqwz.cn/Article/details/gtrszxqavx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cqqwz.cn/Article/details/gtcrfhvcau.html

[U24] Py：路径操作
来源：http://dali.yonumen.top/Article/details/gtrewtfdhs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gtgairtkiy.html

[U25] Py：CSV 按字典读
来源：http://dali.redwolf501.top/Article/details/gtazouxzsy.html

csv.DictReader(f)
来源：http://dali.pengpengdd.cyou/Article/details/gtpsjugofp.html

[U26] Py：并发下载
来源：http://dali.yj20258.top/Article/details/gtqdjqapwf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.meibo888.top/Article/details/gtxjxpqnyh.html

[U27] Py：异步 HTTP
来源：http://dali.wangshuangyany.cn/Article/details/gtllehtprw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yj20258888.top/Article/details/gtlbwynhuy.html

[U28] Py：类型别名
来源：http://dali.jinqigfzy.top/Article/details/gtwpzambhh.html

UserId = int
来源：http://dali.cashguo.top/Article/details/gtsfqssuvo.html

[U29] Py：属性校验
来源：http://dali.xuetiantiany.cn/Article/details/gtzksfigsr.html

@property 与 @x.setter 配合
来源：http://dali.jqgfzy.top/Article/details/gtazhefiso.html

[U30] Py：数据类
来源：http://dali.jqgufenzy.top/Article/details/gtnnzcjagk.html

@dataclass(slots=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtjjkfbpze.html

[U31] Py：单测
来源：http://dali.tian-w.cn/Article/details/gttzikeucl.html

python -m pytest -q
来源：http://dali.ivvv.top/Article/details/gtsfvqvopw.html

[U32] Py：代码格式化
来源：http://dali.smart0.xyz/Article/details/gtxpiwnydo.html

ruff format . && ruff check --fix .
来源：http://dali.haohaochexian.top/Article/details/gtdydmdzks.html

[U33] Py：打包发布
来源：http://dali.gaohongyu789.top/Article/details/gtjfvljtel.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.haohaochexian.top/Article/details/gtaqtdnerd.html

[U34] Py：判断编码
来源：http://dali.tanke756.top/Article/details/gtjbpqpqpd.html

chardet.detect(raw)
来源：http://dali.ybcxt.top/Article/details/gtbtrgzdrb.html

[U35] Py：发送邮件
来源：http://dali.guowangkeji.top/Article/details/gtakbxtxqm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cqqwz.cn/Article/details/gtxxjamsfh.html

[U36] Py：定时任务
来源：http://dali.tianlin.xyz/Article/details/gtsolaerob.html

schedule.every(10).minutes.do(job)
来源：http://dali.sufxvd.cn/Article/details/gtzwfjqqoi.html

[U37] Py：读写 Excel
来源：http://dali.hammf.cn/Article/details/gtruzdywji.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.pengpengdd.cyou/Article/details/gtpecvrefp.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj20258888.top/Article/details/gtlxteujkr.html

Path(__file__).resolve().parent
来源：http://dali.sufxvd.cn/Article/details/gtvvkjyfky.html

[U39] Py：判断是否在交互环境
来源：http://dali.jyoumei.cn/Article/details/gtnlhiperi.html

sys.stdout.isatty()
来源：http://dali.hnqzz.top/Article/details/gtxgpakjtw.html

[U40] Py：打印到标准错误
来源：http://dali.hnqzz.top/Article/details/gtkjwhxhqh.html

print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gtwabsqnty.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hongshengwenyu.top/Article/details/gtspspsbgq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.snrcjt.cn/Article/details/gtizxcmxys.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zdqjudy.top/Article/details/gtdlxejlrz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jqgfzy.top/Article/details/gtxcngldpi.html

[U43] PHP：声明命名空间
来源：http://dali.jinqigufen.top/Article/details/gttzulobug.html

namespace App\Http;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbtgggjo.html

[U44] PHP：开启严格类型
来源：http://dali.xylfe.cn/Article/details/gtlckodqrb.html

declare(strict_types=1);
来源：http://dali.yangfankeji.com/Article/details/gtdnvvtzak.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ivvv.top/Article/details/gtacpoerre.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtgbmxnrul.html

[U46] PHP：可空类型
来源：http://dali.guannengcc.top/Article/details/gtrjgntybx.html

?string $name = null
来源：http://dali.hysaishi.cn/Article/details/gtjmkxkdio.html

[U47] PHP：联合类型
来源：http://dali.wangshuangyany.cn/Article/details/gtmdrvbigw.html

int|string $id
来源：http://dali.zycfv.cn/Article/details/gtxnnasxzb.html

[U48] PHP：纯枚举
来源：http://dali.cucudq.cn/Article/details/gtgzweloei.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.fzhhl.top/Article/details/gtwqtaijop.html

[U49] PHP：只读属性
来源：http://dali.zhongyouzk.top/Article/details/gtqyjsuqhl.html

public readonly string $name
来源：http://dali.daxiang520.top/Article/details/gtdzpysdqm.html

[U50] PHP：构造器属性提升
来源：http://dali.zhengqikj.top/Article/details/gtvdixxfrn.html

public function __construct(private int $id) {}
来源：http://dali.yj202588.top/Article/details/gteqwxksym.html

[U51] PHP：数组解构
来源：http://dali.zhoulong.xyz/Article/details/gtydhlpric.html

[$a, $b] = $arr;
来源：http://dali.snrcjt.cn/Article/details/gtalueeeon.html

[U52] PHP：箭头函数
来源：http://dali.cdnleiting.top/Article/details/gtdspylfwg.html

$double = fn($x) => $x * 2;
来源：http://dali.jinqigfzy.top/Article/details/gtmboxkahl.html

[U53] PHP：空合并运算符
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdfgdelw.html

$v = $a ?? $b ?? "default";
来源：http://dali.9152youxi.cn/Article/details/gtkyxiyxfn.html

[U54] PHP：空安全调用
来源：http://dali.xylfe.cn/Article/details/gtffbcnrud.html

$obj?->method()
来源：http://dali.wangdashe.top/Article/details/gtjfndufor.html

[U55] PHP：match 表达式
来源：http://dali.zhixingplan.top/Article/details/gtmvdgxiyb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhengqikj.top/Article/details/gtunbnltns.html

[U56] PHP：命名参数
来源：http://dali.jqgufenzy.top/Article/details/gtkyxydedl.html

f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gtgofsbxhi.html

[U57] PHP：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gtkpxedvpr.html

"值: {$a}"
来源：http://dali.xinyue.icu/Article/details/gtvsunpeyp.html

[U58] PHP：数组三件套
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgvsejef.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xziqi.cn/Article/details/gtxwlfxvnz.html

[U59] PHP：自定义排序
来源：http://dali.wangdashe.top/Article/details/gtmbccjxye.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigfzy.top/Article/details/gtqzrnwvma.html

[U60] PHP：JSON 编解码
来源：http://dali.zhengqikj.top/Article/details/gtlrkuvtjg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtspibjscj.html

[U61] PHP：正则
来源：http://dali.xuanzx.com/Article/details/gtnjitatij.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtdzfksqyg.html

[U62] PHP：日期对象
来源：http://dali.ehwqpu.com/Article/details/gtyxegnzrk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.daria6918.cn/Article/details/gtomxadgxc.html

[U63] PHP：文件读写
来源：http://dali.yonumen.top/Article/details/gtkptefphb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhengqikj.top/Article/details/gtqtmmycsg.html

[U64] PHP：目录遍历
来源：http://dali.hnxiangtu.top/Article/details/gtxkwmyosc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cheryme.top/Article/details/gtlcjaznrn.html

[U65] PHP：会话
来源：http://dali.zycfv.cn/Article/details/gteondfkul.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtjtlufvvc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gtpxjlepgf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xinyue.icu/Article/details/gtxgwspwvi.html

[U67] PHP：处理文件上传
来源：http://dali.tianlin.xyz/Article/details/gtjwrhlblq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhongyouzk.top/Article/details/gtyxsfxqcs.html

[U68] PHP：PDO 连接
来源：http://dali.vqdsnc.cn/Article/details/gtcaaegxpl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jqgufenzy.top/Article/details/gtovncwqgi.html

[U69] PHP：PDO 预处理
来源：http://dali.hnxiangtu.top/Article/details/gtmerbmqfh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hammf.cn/Article/details/gtuizoxitd.html

[U70] PHP：PDO 事务
来源：http://dali.pengpengdd.cyou/Article/details/gtaxnifown.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hywenlv.cn/Article/details/gtwcracmjq.html

[U71] PHP：抛出异常
来源：http://dali.bjfxy.top/Article/details/gtmqsprgbd.html

throw new RuntimeException("失败", 500);
来源：http://dali.nanxinkj.top/Article/details/gtdfcmiwou.html

[U72] PHP：写错误日志
来源：http://dali.nanxinkj.top/Article/details/gtijglautd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gaohongyu789.top/Article/details/gtyjsxlcvg.html

[U73] PHP：读取 ini 配置
来源：http://dali.aibaodan.cn/Article/details/gtpqvnrehn.html

parse_ini_file("config.ini", true)
来源：http://dali.xinyue.icu/Article/details/gtqcctmalu.html

[U74] PHP：读取环境变量
来源：http://dali.mhx1999.top/Article/details/gtgllfhnwf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xuetiantiany.cn/Article/details/gtcozxveeu.html

[U75] PHP：依赖注入
来源：http://dali.sxryk.cn/Article/details/gtgrktgcgm.html

composer require psr/container
来源：http://dali.chenlongwang.top/Article/details/gthhoskfsb.html

[U76] PHP：简单路由
来源：http://dali.gzhubu.top/Article/details/gtcffmenvw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shzxlz.cn/Article/details/gtiahulpsl.html

[U77] PHP：模板渲染
来源：http://dali.havefunace.top/Article/details/gttygwlvxt.html

composer require twig/twig
来源：http://dali.nanxinkj.top/Article/details/gtzwkpkepb.html

[U78] PHP：单元测试
来源：http://dali.jinqigfzy.top/Article/details/gtupzaxjfm.html

composer require --dev phpunit/phpunit
来源：http://dali.fengsongda.top/Article/details/gtqhkguuuq.html

[U79] PHP：静态分析
来源：http://dali.cashguo.top/Article/details/gtaawryjkx.html

composer require --dev phpstan/phpstan
来源：http://dali.gzhubu.top/Article/details/gthipazako.html

[U80] PHP：代码规范修复
来源：http://dali.hongshengwenyu.top/Article/details/gtwhodztyy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shzxlz.cn/Article/details/gttmriactn.html


<!-- 参考信息 -->