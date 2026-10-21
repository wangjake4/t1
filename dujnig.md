代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbdczyfs.html

[S51] C++：显式类型转换
来源：http://dali.guowangkeji.top/Article/details/gtdpycihrn.html

static_cast<double>(a) / b
来源：http://dali.wangdashe.top/Article/details/gtgukknwlw.html

[S52] C++：const 与 noexcept
来源：http://dali.yonumen.top/Article/details/gtkuugevai.html

int size() const noexcept { return n_; }
来源：http://dali.tanke756.top/Article/details/gthrhniseh.html

[S53] C++：移动语义
来源：http://dali.shuidangran.top/Article/details/gtspredhjn.html

std::vector<int> w = std::move(v);
来源：http://dali.ivvv.top/Article/details/gtxzsudtuh.html

[S54] C++：异常处理
来源：http://dali.zdqjudy.top/Article/details/gtvskgkhmr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sufxvd.cn/Article/details/gtwgawutqj.html

[S55] C++：结构化绑定
来源：http://dali.xinyue.icu/Article/details/gtanvasfjl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrlscgws.html

[S56] C++：optional
来源：http://dali.hnqzz.top/Article/details/gtlycyncuh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigufen.top/Article/details/gtypyrcjho.html

[S57] C++：编译期常量
来源：http://dali.haohaochexian.top/Article/details/gtycrvhzxj.html

constexpr int N = 10;
来源：http://dali.tanke756.top/Article/details/gtitsicmqs.html

[S58] C++：命名空间
来源：http://dali.0kj1m.cn/Article/details/gtfjlsmacw.html

namespace ns { int f() { return 1; } }
来源：http://dali.yangfankeji.com/Article/details/gtkelbgcrv.html

[S59] C++：静态断言
来源：http://dali.shzxlz.cn/Article/details/gtsotumifw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fengsongda.top/Article/details/gtubwlwgww.html

[S60] C++：遍历并删除元素
来源：http://dali.jyoumei.cn/Article/details/gtzpeyvzqo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.c1oappe.top/Article/details/gtygzsxtjo.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtrbirggrk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cqqwz.cn/Article/details/gtfgtjysta.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtvyhspdjv.html

[T01] Kotlin：Hello World
来源：http://dali.fengsongda.top/Article/details/gtgbqfzooq.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gtddkanwcb.html

[T02] Kotlin：变量
来源：http://dali.daxiang520.top/Article/details/gtlabbqxbh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.smart0.xyz/Article/details/gtbseotxio.html

[T03] Kotlin：字符串模板
来源：http://dali.gzhubu.top/Article/details/gtvabzihww.html

"值: $b"
来源：http://dali.pycfn.com/Article/details/gtgdjrnjve.html

[T04] Kotlin：空安全
来源：http://dali.daria6918.cn/Article/details/gtefakbufz.html

val n: String? = null;  n?.length
来源：http://dali.mhx1999.top/Article/details/gtgwidwafj.html

[T05] Kotlin：when 表达式
来源：http://dali.gogol.net.cn/Article/details/gtdghpriqf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.316326.xyz/Article/details/gtprqebouf.html

[T06] Kotlin：集合映射
来源：http://dali.xuetiantiany.cn/Article/details/gtqjkymaew.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtdmqphmye.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtxisduxll.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dashuyun.cn/Article/details/gtuowiibua.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gtetcwyoxt.html

data class User(val name: String, val age: Int)
来源：http://dali.hammf.cn/Article/details/gtuvcpvzsl.html

[T09] Kotlin：扩展函数
来源：http://dali.cashguo.top/Article/details/gtdqkgcezv.html

fun String.exclaim() = this + "!"
来源：http://dali.yueranfly.top/Article/details/gtebqjpiqu.html

[T10] Kotlin：默认参数
来源：http://dali.jqgufenzy.top/Article/details/gtcyeylwat.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258888.top/Article/details/gtuvtttkok.html

[T11] Kotlin：协程
来源：http://dali.aibaodan.cn/Article/details/gtllfuukmm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cdnleiting.top/Article/details/gtqbpihflb.html

[T12] Kotlin：解构声明
来源：http://dali.feifeiyinyue.top/Article/details/gtklwdeuaz.html

val (a, b) = Pair(1, 2)
来源：http://dali.xylfe.cn/Article/details/gtvcsybeol.html

[T13] Kotlin：只读 Map
来源：http://dali.jianghu66.top/Article/details/gtlvglfkow.html

val m = mapOf("a" to 1)
来源：http://dali.yuxming.cn/Article/details/gtducnitss.html

[T14] Kotlin：循环
来源：http://dali.tian-w.cn/Article/details/gtjczgtery.html

for (i in 1..10) println(i)
来源：http://dali.chenzaomai.com/Article/details/gtetebczyl.html

[T15] Kotlin：接口
来源：http://dali.gotoacloud.top/Article/details/gtyhgkgmmt.html

interface Shape { fun area(): Double }
来源：http://dali.ivvv.top/Article/details/gtvqbqfufb.html

[T16] Swift：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtefqmvroy.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gttrzcaaab.html

[T17] Swift：变量与常量
来源：http://dali.wangdashe.top/Article/details/gtqkqogxkq.html

var a = 1;  let b = 2
来源：http://dali.yongpay.top/Article/details/gtmgfbygct.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gturgolofx.html

"值: \(b)"
来源：http://dali.xuanzx.com/Article/details/gtkjdgfzzz.html

[T19] Swift：可选绑定
来源：http://dali.haohaochexian.top/Article/details/gtcaxrdpkz.html

if let n = opt { print(n) }
来源：http://dali.iojbl.cn/Article/details/gtqmcmggek.html

[T20] Swift：数组操作
来源：http://dali.guannengcc.top/Article/details/gtjjrnbyrl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jlsjyb.cn/Article/details/gteetkysis.html

[T21] Swift：遍历
来源：http://dali.zycfv.cn/Article/details/gtrnjdtqty.html

for x in a { print(x) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmvwixwd.html

[T22] Swift：字典
来源：http://dali.zycfv.cn/Article/details/gtunaurcdj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnqzz.top/Article/details/gtdwvbpcdj.html

[T23] Swift：函数
来源：http://dali.shangyingyoupin.top/Article/details/gtmppfxkth.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtxlqzppxy.html

[T24] Swift：闭包
来源：http://dali.chenlongwang.top/Article/details/gtscgeboya.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtzlsrsidu.html

[T25] Swift：结构体
来源：http://dali.guowangkeji.top/Article/details/gtgxbjuoyq.html

struct P { var x: Int }
来源：http://dali.mhx1999.top/Article/details/gtvrtjoqut.html

[T26] Swift：类与重写
来源：http://dali.yongpay.top/Article/details/gtxscruakt.html

class A: Base { override func f() {} }
来源：http://dali.sxryk.cn/Article/details/gtoffiiacq.html

[T27] Swift：错误处理
来源：http://dali.redwolf501.top/Article/details/gtbgundwjb.html

do { try f() } catch { print(error) }
来源：http://dali.fengsongda.top/Article/details/gthgwnlila.html

[T28] Swift：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhijhhof.html

enum Color { case red, green }
来源：http://dali.hongshengwenyu.top/Article/details/gtpzyqprwu.html

[T29] Swift：guard 提前返回
来源：http://dali.yj202588.top/Article/details/gtnultheug.html

guard let x = opt else { return }
来源：http://dali.316326.xyz/Article/details/gteuasbhql.html

[T30] Swift：协议
来源：http://dali.guowangkeji.top/Article/details/gtmlgvrzrn.html

protocol Shape { func area() -> Double }
来源：http://dali.hysaishi.cn/Article/details/gtzhwqbldb.html

[T31] Lua：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtedxbtdma.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gtvphlwqbo.html

[T32] Lua：局部变量
来源：http://dali.cucudq.cn/Article/details/gtxkttaaxw.html

local a = 1
来源：http://dali.jinqigfzy.top/Article/details/gtmgmauoii.html

[T33] Lua：表（数组）
来源：http://dali.cqqwz.cn/Article/details/gtfwzkbeiq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxglyapjb.html

[T34] Lua：遍历表
来源：http://dali.jqgfzy.top/Article/details/gtehyczejp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgfzy.top/Article/details/gtdmgjdpyc.html

[T35] Lua：字典表
来源：http://dali.zdqjudy.top/Article/details/gtsucotshq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj202588.top/Article/details/gtwmtgljtb.html

[T36] Lua：函数
来源：http://dali.316326.xyz/Article/details/gtlocaovvd.html

function add(a, b) return a + b end
来源：http://dali.ehwqpu.com/Article/details/gtjmvfbdqx.html

[T37] Lua：字符串拼接
来源：http://dali.jlsjyb.cn/Article/details/gtxgjuxueb.html

"a" .. "b"
来源：http://dali.xylfe.cn/Article/details/gtsvuggytr.html

[T38] Lua：条件
来源：http://dali.yj20258888.top/Article/details/gtmbmqjpxx.html

if x > 0 then print("正") end
来源：http://dali.jinqigufen.top/Article/details/gtbhjaojml.html

[T39] Lua：模式匹配
来源：http://dali.xziqi.cn/Article/details/gtjdnbyhub.html

string.find(s, "%d+")
来源：http://dali.jqgufenzy.top/Article/details/gttjutjfcx.html

[T40] Lua：元表
来源：http://dali.kuanghao11.cn/Article/details/gtomufwgdn.html

setmetatable({}, { __index = base })
来源：http://dali.hongshengwenyu.top/Article/details/gtpltaxicr.html

[T41] Perl：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtwlnhbaov.html

print "Hello\n";
来源：http://dali.aizwys.cn/Article/details/gtrcwrcxid.html

[T42] Perl：变量类型
来源：http://dali.tianlin.xyz/Article/details/gtqjfefwlg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shzxlz.cn/Article/details/gtugxdxzkg.html

[T43] Perl：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gthcbfuofg.html

"值: $a"
来源：http://dali.chenjidiqi.icu/Article/details/gtkrfutfgs.html

[T44] Perl：条件
来源：http://dali.kuanghao11.cn/Article/details/gtcnhvwnnw.html

if ($a > 0) { print "正"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpoqbatrf.html

[T45] Perl：数组遍历
来源：http://dali.bjfxy.top/Article/details/gtswjecoxt.html

for my $x (@arr) { print $x; }
来源：http://dali.ybcxt.top/Article/details/gthuoxythe.html

[T46] Perl：哈希操作
来源：http://dali.wangshuangyany.cn/Article/details/gtragvtzps.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.wangdashe.top/Article/details/gtdstirjmf.html

[T47] Perl：正则捕获
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrkndyfu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.vqdsnc.cn/Article/details/gtmjrcxvgs.html

[T48] Perl：正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzgonupd.html

$s =~ s/old/new/g;
来源：http://dali.9152youxi.cn/Article/details/gtkbqsglqa.html

[T49] Perl：函数
来源：http://dali.zycfv.cn/Article/details/gtqehnufyi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtrzumtizv.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbfjiymj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.0kj1m.cn/Article/details/gtjrdbobfb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tian-w.cn/Article/details/gtfkjlapse.html

[T51] Scala：Hello World
来源：http://dali.tian-w.cn/Article/details/gticbbsmzc.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gtnnzzsvpi.html

[T52] Scala：变量
来源：http://dali.gzhubu.top/Article/details/gtehclgtec.html

val a = 1;  var b = 2
来源：http://dali.gotoacloud.top/Article/details/gtwbhapjus.html

[T53] Scala：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtxxviajqf.html

s"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gtkemhksae.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqxxkaet.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfbpapkg.html

[T55] Scala：集合过滤
来源：http://dali.yj20258888.top/Article/details/gtulojghiv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.havefunace.top/Article/details/gtbhwymhjl.html

[T56] Scala：样例类
来源：http://dali.ybcxt.top/Article/details/gtuhnofixm.html

case class User(name: String, age: Int)
来源：http://dali.c1oappe.top/Article/details/gtssjtphau.html

[T57] Scala：模式匹配
来源：http://dali.yanxiufei.cn/Article/details/gtupxgfssg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnqzz.top/Article/details/gtvjnsdnyr.html

[T58] Scala：函数定义
来源：http://dali.snrcjt.cn/Article/details/gtnpswjfly.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.havefunace.top/Article/details/gtqidbegdd.html

[T59] Scala：循环
来源：http://dali.hongshengwenyu.top/Article/details/gtjztbngek.html

for (i <- 1 to 10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gtutezisez.html

[T60] Scala：折叠
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbetvfwn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shzxlz.cn/Article/details/gtzmvqjdqc.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtgxvdgbjx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hammf.cn/Article/details/gtgwupefmd.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtdihkdoao.html

[U01] Py：创建虚拟环境
来源：http://dali.hywenlv.cn/Article/details/gtovfvyfqm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.snrcjt.cn/Article/details/gtibhiazdp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhoulong.xyz/Article/details/gtmplxtdgs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.vqdsnc.cn/Article/details/gtrglrjxkk.html

[U03] Py：加载 .env 配置
来源：http://dali.sysykeji.top/Article/details/gtnptjhrgn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.meibo888.top/Article/details/gtxqcubwcw.html

[U04] Py：变量调试打印
来源：http://dali.chenjidiqi.icu/Article/details/gttyctwkal.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.daria6918.cn/Article/details/gtvqydcrgx.html

[U05] Py：列表去重且保序
来源：http://dali.cashguo.top/Article/details/gtduhvkuhm.html

list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gtteacyqrz.html

[U06] Py：合并两个字典
来源：http://dali.wangdashe.top/Article/details/gtsolpfiiz.html

{**a, **b}
来源：http://dali.cdnleiting.top/Article/details/gtivdrdxaq.html

[U07] Py：反转字典键值
来源：http://dali.ivvv.top/Article/details/gtdvsklkzr.html

{v: k for k, v in d.items()}
来源：http://dali.shuidangran.top/Article/details/gtewptdbto.html

[U08] Py：展平二维列表
来源：http://dali.yuxming.cn/Article/details/gtpnkuapds.html

[y for x in nested for y in x]
来源：http://dali.tanke756.top/Article/details/gtknnmxfiz.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gtrjuzheng.html

max(d, key=d.get)
来源：http://dali.zycfv.cn/Article/details/gtexwhsisv.html

[U10] Py：按值排序字典
来源：http://dali.jqgufenzy.top/Article/details/gtnwwbpryu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yueranfly.top/Article/details/gtirwvfcfm.html

[U11] Py：生成器表达式
来源：http://dali.redwolf501.top/Article/details/gtrkpngfzf.html

(x * 2 for x in arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtmgurwpat.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hfpthk.cn/Article/details/gtvqsnyors.html

Counter(arr).most_common(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfridwfjl.html

[U13] Py：固定长度队列
来源：http://dali.wangshuangyany.cn/Article/details/gtgkxyladd.html

deque(maxlen=10)
来源：http://dali.birdmap.top/Article/details/gtvmhjchpj.html

[U14] Py：分组收集到列表
来源：http://dali.gzhubu.top/Article/details/gtkjnvuezb.html

defaultdict(list)
来源：http://dali.cucudq.cn/Article/details/gtftqrvxcu.html

[U15] Py：高精度计时
来源：http://dali.xuanzx.com/Article/details/gtvbehqmvl.html

t = time.perf_counter()
来源：http://dali.snrcjt.cn/Article/details/gtiwnbwkyt.html

[U16] Py：命令行参数解析
来源：http://dali.iojbl.cn/Article/details/gtcmpsemuo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuanzhike.top/Article/details/gtrumxncgq.html

[U17] Py：初始化日志
来源：http://dali.nanxuanxn.top/Article/details/gtovdfokqu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.snrcjt.cn/Article/details/gtikgagygc.html

[U18] Py：预编译正则
来源：http://dali.gogol.net.cn/Article/details/gtmrfkbnsq.html

pat = re.compile(r"\d+")
来源：http://dali.hongshengwenyu.top/Article/details/gtgoflopvf.html

[U19] Py：正则替换带回调
来源：http://dali.ybcxt.top/Article/details/gtmscdxjho.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.feifeiyinyue.top/Article/details/gtlnmjymqs.html

[U20] Py：缓存函数结果
来源：http://dali.cheryme.top/Article/details/gtulxfswmt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.bjfxy.top/Article/details/gtwqaxjcws.html

[U21] Py：自定义上下文管理器
来源：http://dali.ehwqpu.com/Article/details/gtxszpseff.html

@contextlib.contextmanager
来源：http://dali.svipenyu.cn/Article/details/gtbgphpded.html

[U22] Py：矩阵转置
来源：http://dali.xuetiantiany.cn/Article/details/gtdlyshohd.html

list(zip(*m))
来源：http://dali.yj20258.top/Article/details/gtvbzmdbnm.html

[U23] Py：分块读取大文件
来源：http://dali.fengsongda.top/Article/details/gtdtfvvloi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.kuanghao11.cn/Article/details/gtjypmeony.html

[U24] Py：路径操作
来源：http://dali.sxryk.cn/Article/details/gtihtcvqhn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gtkjwxeyfw.html

[U25] Py：CSV 按字典读
来源：http://dali.yueranfly.top/Article/details/gtjaphzoxr.html

csv.DictReader(f)
来源：http://dali.ehwqpu.com/Article/details/gtabqehipb.html

[U26] Py：并发下载
来源：http://dali.jinqigufen.top/Article/details/gtplrxctcv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xuetiantiany.cn/Article/details/gtmyqlyoho.html

[U27] Py：异步 HTTP
来源：http://dali.zhoulong.xyz/Article/details/gtguacymgl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jlsjyb.cn/Article/details/gtwwrlhvts.html

[U28] Py：类型别名
来源：http://dali.jqgfzy.top/Article/details/gtgfuudogo.html

UserId = int
来源：http://dali.snrcjt.cn/Article/details/gtscdiappg.html

[U29] Py：属性校验
来源：http://dali.zhongyouzk.top/Article/details/gtxzyieezg.html

@property 与 @x.setter 配合
来源：http://dali.jianghu66.top/Article/details/gtlrddlvkj.html

[U30] Py：数据类
来源：http://dali.yuxming.cn/Article/details/gtbnwgpjfo.html

@dataclass(slots=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtyburjbre.html

[U31] Py：单测
来源：http://dali.chenlongwang.top/Article/details/gtanhvzyax.html

python -m pytest -q
来源：http://dali.yuxming.cn/Article/details/gtqevzckfk.html

[U32] Py：代码格式化
来源：http://dali.snrcjt.cn/Article/details/gthkceuihm.html

ruff format . && ruff check --fix .
来源：http://dali.andypj.xyz/Article/details/gtdvpfgjcx.html

[U33] Py：打包发布
来源：http://dali.jyoumei.cn/Article/details/gtdlakozrk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hammf.cn/Article/details/gtpxepapmt.html

[U34] Py：判断编码
来源：http://dali.jinqigufen.top/Article/details/gtaobsmdlb.html

chardet.detect(raw)
来源：http://dali.yuxming.cn/Article/details/gtfxyrtzzm.html

[U35] Py：发送邮件
来源：http://dali.svipenyu.cn/Article/details/gtfvmhpofw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cqqwz.cn/Article/details/gtvjuyuele.html

[U36] Py：定时任务
来源：http://dali.andypj.xyz/Article/details/gtimlpaagc.html

schedule.every(10).minutes.do(job)
来源：http://dali.xinyue.icu/Article/details/gtcswvmvzi.html

[U37] Py：读写 Excel
来源：http://dali.chenlongwang.top/Article/details/gtzgyqohve.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.dashuyun.cn/Article/details/gtsvxiumdf.html

[U38] Py：获取脚本所在目录
来源：http://dali.0kj1m.cn/Article/details/gtqhdbvxwo.html

Path(__file__).resolve().parent
来源：http://dali.andypj.xyz/Article/details/gtvgwrfrjq.html

[U39] Py：判断是否在交互环境
来源：http://dali.iojbl.cn/Article/details/gtrjieuswc.html

sys.stdout.isatty()
来源：http://dali.hnqzz.top/Article/details/gtrhjctwid.html

[U40] Py：打印到标准错误
来源：http://dali.chenjidiqi.icu/Article/details/gtlllstmbr.html

print("err", file=sys.stderr)
来源：http://dali.0kj1m.cn/Article/details/gtmfdrmowy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xuetiantiany.cn/Article/details/gtvvimumbt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhengqikj.top/Article/details/gtzpjahvma.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.bjfxy.top/Article/details/gteyzcmavm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yuxming.cn/Article/details/gtvclpioiw.html

[U43] PHP：声明命名空间
来源：http://dali.ehwqpu.com/Article/details/gtvsxzgdrp.html

namespace App\Http;
来源：http://dali.andypj.xyz/Article/details/gtrbjxyjre.html

[U44] PHP：开启严格类型
来源：http://dali.iojbl.cn/Article/details/gtfrctbail.html

declare(strict_types=1);
来源：http://dali.xinyue.icu/Article/details/gtgftvthnj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.feifeiyinyue.top/Article/details/gtpfibohsk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtrybnptvj.html

[U46] PHP：可空类型
来源：http://dali.gaohongyu789.top/Article/details/gtzsoducka.html

?string $name = null
来源：http://dali.tianlin.xyz/Article/details/gtalweaymd.html

[U47] PHP：联合类型
来源：http://dali.jinqigufen.top/Article/details/gtzcozyzlr.html

int|string $id
来源：http://dali.cdnleiting.top/Article/details/gttwyurwkj.html

[U48] PHP：纯枚举
来源：http://dali.daria6918.cn/Article/details/gtgwydxgjo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfgoxmhhl.html

[U49] PHP：只读属性
来源：http://dali.meibo888.top/Article/details/gtznuuihsc.html

public readonly string $name
来源：http://dali.yonumen.top/Article/details/gtjlwwzkfd.html

[U50] PHP：构造器属性提升
来源：http://dali.aibaodan.cn/Article/details/gtnceahbxq.html

public function __construct(private int $id) {}
来源：http://dali.shzxlz.cn/Article/details/gtmuaqtacs.html

[U51] PHP：数组解构
来源：http://dali.haohaochexian.top/Article/details/gtqtavpgil.html

[$a, $b] = $arr;
来源：http://dali.xziqi.cn/Article/details/gtfoqzadae.html

[U52] PHP：箭头函数
来源：http://dali.birdmap.top/Article/details/gtlsdvrrjn.html

$double = fn($x) => $x * 2;
来源：http://dali.feifeiyinyue.top/Article/details/gtymvuijrm.html

[U53] PHP：空合并运算符
来源：http://dali.cdnleiting.top/Article/details/gtartwrhcj.html

$v = $a ?? $b ?? "default";
来源：http://dali.cdnleiting.top/Article/details/gtzpjcqxsi.html

[U54] PHP：空安全调用
来源：http://dali.mhx1999.top/Article/details/gtckiykgui.html

$obj?->method()
来源：http://dali.sxryk.cn/Article/details/gttdrhscor.html

[U55] PHP：match 表达式
来源：http://dali.gzhubu.top/Article/details/gtfcrrjnyt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhongyouzk.top/Article/details/gtedyvzuwn.html

[U56] PHP：命名参数
来源：http://dali.zdqjudy.top/Article/details/gteotnxhnt.html

f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtgjwappaj.html

[U57] PHP：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gttftvxzsn.html

"值: {$a}"
来源：http://dali.yj202588.top/Article/details/gthydwsvmn.html

[U58] PHP：数组三件套
来源：http://dali.aizwys.cn/Article/details/gtoqpfprdz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gthvhogpba.html

[U59] PHP：自定义排序
来源：http://dali.shanyushiyangtech.top/Article/details/gttzaqibfm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesspfxew.html

[U60] PHP：JSON 编解码
来源：http://dali.redwolf501.top/Article/details/gtjgvjdxdh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.guannengcc.top/Article/details/gthyznwefu.html

[U61] PHP：正则
来源：http://dali.meibo888.top/Article/details/gturfwjorz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gtleykrims.html

[U62] PHP：日期对象
来源：http://dali.xuetiantiany.cn/Article/details/gtbcxiixnm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.pengpengdd.cyou/Article/details/gtvfglblvp.html

[U63] PHP：文件读写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvakuatzh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cashguo.top/Article/details/gtzaarwyhf.html

[U64] PHP：目录遍历
来源：http://dali.chenlongwang.top/Article/details/gtfzyyukiz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.fengsongda.top/Article/details/gtlyvtyikw.html

[U65] PHP：会话
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsuemwdn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtxdyoanly.html

[U66] PHP：设置 Cookie
来源：http://dali.yanxiufei.cn/Article/details/gttlsfjcko.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yonumen.top/Article/details/gtehsxryai.html

[U67] PHP：处理文件上传
来源：http://dali.sweek.top/Article/details/gtvakyksxp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yuanzhike.top/Article/details/gtovjqvkbd.html

[U68] PHP：PDO 连接
来源：http://dali.jqgufenzy.top/Article/details/gtlldnqiww.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.pycfn.com/Article/details/gtxwwipjyl.html

[U69] PHP：PDO 预处理
来源：http://dali.sufxvd.cn/Article/details/gtesxttkxe.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cheryme.top/Article/details/gtknykeuci.html

[U70] PHP：PDO 事务
来源：http://dali.hnqzz.top/Article/details/gtmlleoudg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.nwbrower.top/Article/details/gttuebdzer.html

[U71] PHP：抛出异常
来源：http://dali.yj20258888.top/Article/details/gtpqoywyjs.html

throw new RuntimeException("失败", 500);
来源：http://dali.snrcjt.cn/Article/details/gtnptjclhn.html

[U72] PHP：写错误日志
来源：http://dali.pengpengdd.cyou/Article/details/gtucnqmiwj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hysaishi.cn/Article/details/gtowkoabia.html

[U73] PHP：读取 ini 配置
来源：http://dali.jinqigfzy.top/Article/details/gtfgzgbtje.html

parse_ini_file("config.ini", true)
来源：http://dali.birdmap.top/Article/details/gtrosmqign.html

[U74] PHP：读取环境变量
来源：http://dali.andypj.xyz/Article/details/gtmbdhoodp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj20258888.top/Article/details/gtlubtafck.html

[U75] PHP：依赖注入
来源：http://dali.hywenlv.cn/Article/details/gtrpqejuzg.html

composer require psr/container
来源：http://dali.feifeiyinyue.top/Article/details/gterhukyha.html

[U76] PHP：简单路由
来源：http://dali.cdnleiting.top/Article/details/gtmdkdrrqs.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.gaohongyu789.top/Article/details/gtgqoteyvu.html


<!-- 参考信息 -->