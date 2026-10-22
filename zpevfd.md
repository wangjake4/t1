代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtcukpfjvx.html

[S51] C++：显式类型转换
来源：http://dali.nanxinkj.top/Article/details/gtxuqrvxaq.html

static_cast<double>(a) / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqntuwtgh.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gttyiabdur.html

int size() const noexcept { return n_; }
来源：http://dali.sxryk.cn/Article/details/gtdbzxttxw.html

[S53] C++：移动语义
来源：http://dali.guannengcc.top/Article/details/gtnswgeuot.html

std::vector<int> w = std::move(v);
来源：http://dali.316326.xyz/Article/details/gtvqlitabk.html

[S54] C++：异常处理
来源：http://dali.xziqi.cn/Article/details/gtbfcmvxby.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.316326.xyz/Article/details/gtixgerjzn.html

[S55] C++：结构化绑定
来源：http://dali.jinqigfzy.top/Article/details/gttntwciik.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gaohongyu789.top/Article/details/gtfxwjlksj.html

[S56] C++：optional
来源：http://dali.0kj1m.cn/Article/details/gtunayxqrj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztqmutpi.html

[S57] C++：编译期常量
来源：http://dali.zhiwuduotai.top/Article/details/gtyoqmuwbw.html

constexpr int N = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtiztizvok.html

[S58] C++：命名空间
来源：http://dali.chenzaomai.com/Article/details/gtttuevuyz.html

namespace ns { int f() { return 1; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtplzjrnps.html

[S59] C++：静态断言
来源：http://dali.shzxlz.cn/Article/details/gtjgcvlrkq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pengpengdd.cyou/Article/details/gtyissudjr.html

[S60] C++：遍历并删除元素
来源：http://dali.guannengcc.top/Article/details/gtaipnxsvn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gtmqwxmfzc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtagfygiux.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zycfv.cn/Article/details/gtbawlaugo.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtvgvahhey.html

[T01] Kotlin：Hello World
来源：http://dali.yvedp.cn/Article/details/gtqfnardso.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gtudsbulzg.html

[T02] Kotlin：变量
来源：http://dali.yanxiufei.cn/Article/details/gtzfmhigti.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.c1oappe.top/Article/details/gtsgslekku.html

[T03] Kotlin：字符串模板
来源：http://dali.316326.xyz/Article/details/gtpjaheiny.html

"值: $b"
来源：http://dali.sxryk.cn/Article/details/gtyehfljgd.html

[T04] Kotlin：空安全
来源：http://dali.tanke756.top/Article/details/gtpeshqfpp.html

val n: String? = null;  n?.length
来源：http://dali.316326.xyz/Article/details/gtzmplbqkh.html

[T05] Kotlin：when 表达式
来源：http://dali.pycfn.com/Article/details/gtqizzhtna.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.snrcjt.cn/Article/details/gtfuamgokd.html

[T06] Kotlin：集合映射
来源：http://dali.hammf.cn/Article/details/gtcnkqstap.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtgohcxwdg.html

[T07] Kotlin：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtaodoezdv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daria6918.cn/Article/details/gtrfdkfnsb.html

[T08] Kotlin：数据类
来源：http://dali.0kj1m.cn/Article/details/gtvoyvjoxk.html

data class User(val name: String, val age: Int)
来源：http://dali.chenlongwang.top/Article/details/gtoilhlplx.html

[T09] Kotlin：扩展函数
来源：http://dali.jianghu66.top/Article/details/gttvrycqtz.html

fun String.exclaim() = this + "!"
来源：http://dali.andypj.xyz/Article/details/gtuqiuqpxj.html

[T10] Kotlin：默认参数
来源：http://dali.chenzaomai.com/Article/details/gthhnofrcx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yanxiufei.cn/Article/details/gtsahvapgn.html

[T11] Kotlin：协程
来源：http://dali.dashuyun.cn/Article/details/gtcovwygjw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shuidangran.top/Article/details/gttguuccnp.html

[T12] Kotlin：解构声明
来源：http://dali.cucudq.cn/Article/details/gtjlxucfhb.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj202588.top/Article/details/gtygzofzcb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhongyouzk.top/Article/details/gtzgkjmryt.html

val m = mapOf("a" to 1)
来源：http://dali.sxryk.cn/Article/details/gtjousqwuf.html

[T14] Kotlin：循环
来源：http://dali.hnqzz.top/Article/details/gthdpaneae.html

for (i in 1..10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gtxannunys.html

[T15] Kotlin：接口
来源：http://dali.316326.xyz/Article/details/gtrctldwae.html

interface Shape { fun area(): Double }
来源：http://dali.daxiang520.top/Article/details/gtzjpzcupi.html

[T16] Swift：Hello World
来源：http://dali.yj202588.top/Article/details/gtgqktaxuq.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpklhzbo.html

[T17] Swift：变量与常量
来源：http://dali.zhoulong.xyz/Article/details/gtwxilrmvw.html

var a = 1;  let b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtkkehtdob.html

[T18] Swift：字符串插值
来源：http://dali.cashguo.top/Article/details/gtwcwkaxxw.html

"值: \(b)"
来源：http://dali.cashguo.top/Article/details/gtilpwtmip.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdsglmutq.html

if let n = opt { print(n) }
来源：http://dali.dashuyun.cn/Article/details/gtmozvctjt.html

[T20] Swift：数组操作
来源：http://dali.316326.xyz/Article/details/gtrwvqfxkw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.havefunace.top/Article/details/gtpbqjtmpd.html

[T21] Swift：遍历
来源：http://dali.tianlin.xyz/Article/details/gtbwidslzv.html

for x in a { print(x) }
来源：http://dali.zhiwuduotai.top/Article/details/gtvprigyaa.html

[T22] Swift：字典
来源：http://dali.havefunace.top/Article/details/gthbxrdlkz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xziqi.cn/Article/details/gtevrnampl.html

[T23] Swift：函数
来源：http://dali.zhoulong.xyz/Article/details/gtpigvyrls.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jianghu66.top/Article/details/gtjltvmoxa.html

[T24] Swift：闭包
来源：http://dali.ivvv.top/Article/details/gtvsopsnur.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shuidangran.top/Article/details/gtrmrglbin.html

[T25] Swift：结构体
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagtdemde.html

struct P { var x: Int }
来源：http://dali.vqdsnc.cn/Article/details/gtmqyywfrk.html

[T26] Swift：类与重写
来源：http://dali.yueranfly.top/Article/details/gtbwxtdevd.html

class A: Base { override func f() {} }
来源：http://dali.tian-w.cn/Article/details/gtiinwupeb.html

[T27] Swift：错误处理
来源：http://dali.chenlongwang.top/Article/details/gtlvjkrsjz.html

do { try f() } catch { print(error) }
来源：http://dali.wangdashe.top/Article/details/gtctzmyykx.html

[T28] Swift：枚举
来源：http://dali.xinyue.icu/Article/details/gtdchraazz.html

enum Color { case red, green }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrxzidcm.html

[T29] Swift：guard 提前返回
来源：http://dali.hnqzz.top/Article/details/gtwcpheaca.html

guard let x = opt else { return }
来源：http://dali.pycfn.com/Article/details/gtctzoibcr.html

[T30] Swift：协议
来源：http://dali.svipenyu.cn/Article/details/gtppmhufez.html

protocol Shape { func area() -> Double }
来源：http://dali.sysykeji.top/Article/details/gtwvzwenxi.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gthopblssm.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtmeycxmmc.html

[T32] Lua：局部变量
来源：http://dali.xuanzx.com/Article/details/gttmeacvhe.html

local a = 1
来源：http://dali.hnxiangtu.top/Article/details/gtefclvabj.html

[T33] Lua：表（数组）
来源：http://dali.9152youxi.cn/Article/details/gtzyobsyml.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guannengcc.top/Article/details/gtuukpkfmg.html

[T34] Lua：遍历表
来源：http://dali.wangdashe.top/Article/details/gtqpguxdsh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xuetiantiany.cn/Article/details/gtqotixbul.html

[T35] Lua：字典表
来源：http://dali.wangdashe.top/Article/details/gtjjvzczfi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.daxiang520.top/Article/details/gtnohihvpu.html

[T36] Lua：函数
来源：http://dali.jiagoushi.top/Article/details/gtwwnhytrq.html

function add(a, b) return a + b end
来源：http://dali.nwbrower.top/Article/details/gtlyluthrm.html

[T37] Lua：字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtnaucirsn.html

"a" .. "b"
来源：http://dali.ybcxt.top/Article/details/gtpfivaajm.html

[T38] Lua：条件
来源：http://dali.kuanghao11.cn/Article/details/gtejbhjleo.html

if x > 0 then print("正") end
来源：http://dali.pycfn.com/Article/details/gtoyprbvhy.html

[T39] Lua：模式匹配
来源：http://dali.zhongyouzk.top/Article/details/gtzkwusgmt.html

string.find(s, "%d+")
来源：http://dali.jiagoushi.top/Article/details/gtepublamf.html

[T40] Lua：元表
来源：http://dali.hnxiangtu.top/Article/details/gtjmlouuyp.html

setmetatable({}, { __index = base })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikcbwoon.html

[T41] Perl：Hello World
来源：http://dali.nwbrower.top/Article/details/gtrvxzbvry.html

print "Hello\n";
来源：http://dali.pycfn.com/Article/details/gtbjyyjsic.html

[T42] Perl：变量类型
来源：http://dali.feifeiyinyue.top/Article/details/gtzgumwmxz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.redwolf501.top/Article/details/gtgodxcxlg.html

[T43] Perl：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtiourfvgy.html

"值: $a"
来源：http://dali.aizwys.cn/Article/details/gtjmfoijku.html

[T44] Perl：条件
来源：http://dali.yonumen.top/Article/details/gtnvllregy.html

if ($a > 0) { print "正"; }
来源：http://dali.c1oappe.top/Article/details/gtgjqwczxh.html

[T45] Perl：数组遍历
来源：http://dali.9152youxi.cn/Article/details/gtcmjckqvj.html

for my $x (@arr) { print $x; }
来源：http://dali.havefunace.top/Article/details/gtchugklen.html

[T46] Perl：哈希操作
来源：http://dali.ybcxt.top/Article/details/gtsyzslrao.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdtsuuggi.html

[T47] Perl：正则捕获
来源：http://dali.yuxming.cn/Article/details/gtsfiuokkw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgyocaxpx.html

[T48] Perl：正则替换
来源：http://dali.tianlin.xyz/Article/details/gtiwvfhcrn.html

$s =~ s/old/new/g;
来源：http://dali.zdqjudy.top/Article/details/gtfbtlvmkr.html

[T49] Perl：函数
来源：http://dali.xuanzx.com/Article/details/gthdxjectc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpnlcqdhg.html

[T50] Perl：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtnhuqdjjj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigufen.top/Article/details/gtksbricsg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhoulong.xyz/Article/details/gtnkrsqqzd.html

[T51] Scala：Hello World
来源：http://dali.yj202588.top/Article/details/gthbzdhqtt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtgmcuybbi.html

[T52] Scala：变量
来源：http://dali.nanxuanxn.top/Article/details/gtasxsvqvn.html

val a = 1;  var b = 2
来源：http://dali.yuanzhike.top/Article/details/gtekzqkyft.html

[T53] Scala：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtogendjmd.html

s"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gttmairwyl.html

[T54] Scala：集合映射
来源：http://dali.shuidangran.top/Article/details/gtmefxnfrh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.meibo888.top/Article/details/gtejgxirub.html

[T55] Scala：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gtbvmyaknx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimwlojcl.html

[T56] Scala：样例类
来源：http://dali.quarkkingdee.top/Article/details/gtoiggkfbx.html

case class User(name: String, age: Int)
来源：http://dali.ybcxt.top/Article/details/gtbrzgagzu.html

[T57] Scala：模式匹配
来源：http://dali.yonumen.top/Article/details/gtudhkocrg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.fzhhl.top/Article/details/gtkkpdfwwf.html

[T58] Scala：函数定义
来源：http://dali.shangyingyoupin.top/Article/details/gtuvqxgvlv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dianchejie.cn/Article/details/gthecwdpjq.html

[T59] Scala：循环
来源：http://dali.bjfxy.top/Article/details/gtlpyyofrp.html

for (i <- 1 to 10) println(i)
来源：http://dali.smart0.xyz/Article/details/gtzdrespxu.html

[T60] Scala：折叠
来源：http://dali.jiagoushi.top/Article/details/gtvnvevbud.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.quarkkingdee.top/Article/details/gtfnfurvrw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtasgroayf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cqqwz.cn/Article/details/gttizkwsxu.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtpehcfmhd.html

[U01] Py：创建虚拟环境
来源：http://dali.pycfn.com/Article/details/gtuycaiqxa.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gotoacloud.top/Article/details/gtfibrudpv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.kuanghao11.cn/Article/details/gtimvehvbu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenlongwang.top/Article/details/gthzqabnaw.html

[U03] Py：加载 .env 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtouvzulof.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hnxiangtu.top/Article/details/gtvlijzknu.html

[U04] Py：变量调试打印
来源：http://dali.zhengqikj.top/Article/details/gtaoyaivrm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.smart0.xyz/Article/details/gtjqvwvgfr.html

[U05] Py：列表去重且保序
来源：http://dali.yanxiufei.cn/Article/details/gtkghdgnjv.html

list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gtlluakmya.html

[U06] Py：合并两个字典
来源：http://dali.guowangkeji.top/Article/details/gttmmvcybv.html

{**a, **b}
来源：http://dali.bjfxy.top/Article/details/gtmlgynuwd.html

[U07] Py：反转字典键值
来源：http://dali.sweek.top/Article/details/gtmftziipu.html

{v: k for k, v in d.items()}
来源：http://dali.jiagoushi.top/Article/details/gtqidbmvmv.html

[U08] Py：展平二维列表
来源：http://dali.guowangkeji.top/Article/details/gtshshvlvv.html

[y for x in nested for y in x]
来源：http://dali.yongpay.top/Article/details/gtdcsxqoqr.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258.top/Article/details/gtxfvrwdkf.html

max(d, key=d.get)
来源：http://dali.xylfe.cn/Article/details/gtvoogmllk.html

[U10] Py：按值排序字典
来源：http://dali.dianchejie.cn/Article/details/gtkhxxdlqq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.guowangkeji.top/Article/details/gtghjffyag.html

[U11] Py：生成器表达式
来源：http://dali.guannengcc.top/Article/details/gtxedxxmfv.html

(x * 2 for x in arr)
来源：http://dali.ehwqpu.com/Article/details/gtdcgkzzup.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.aibaodan.cn/Article/details/gtqakmbbbx.html

Counter(arr).most_common(3)
来源：http://dali.zhengqikj.top/Article/details/gtbeazqzvl.html

[U13] Py：固定长度队列
来源：http://dali.yj20258888.top/Article/details/gtgrpzbqlz.html

deque(maxlen=10)
来源：http://dali.birdmap.top/Article/details/gtvbukhbwi.html

[U14] Py：分组收集到列表
来源：http://dali.gotoacloud.top/Article/details/gthunssngp.html

defaultdict(list)
来源：http://dali.jinqigufen.top/Article/details/gtmqfrpzka.html

[U15] Py：高精度计时
来源：http://dali.fzhhl.top/Article/details/gtlmjgibnb.html

t = time.perf_counter()
来源：http://dali.zdqjudy.top/Article/details/gtgfcnahxt.html

[U16] Py：命令行参数解析
来源：http://dali.ydzc1.top/Article/details/gtwulnwwsd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.iojbl.cn/Article/details/gtqqrzbsae.html

[U17] Py：初始化日志
来源：http://dali.zdqjudy.top/Article/details/gtdeyrmqxp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shuidangran.top/Article/details/gtccvwlrqe.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gtwtdsanqe.html

pat = re.compile(r"\d+")
来源：http://dali.hywenlv.cn/Article/details/gterrblpcr.html

[U19] Py：正则替换带回调
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiszxnkgu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigufen.top/Article/details/gtiujqgymt.html

[U20] Py：缓存函数结果
来源：http://dali.sufxvd.cn/Article/details/gttwpnfbwg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ehwqpu.com/Article/details/gtuoktbabq.html

[U21] Py：自定义上下文管理器
来源：http://dali.redwolf501.top/Article/details/gtjnwluvhs.html

@contextlib.contextmanager
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixnvrzmk.html

[U22] Py：矩阵转置
来源：http://dali.zycfv.cn/Article/details/gtmllrilfe.html

list(zip(*m))
来源：http://dali.zhixingplan.top/Article/details/gtolxistci.html

[U23] Py：分块读取大文件
来源：http://dali.birdmap.top/Article/details/gtpnielpmo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sysykeji.top/Article/details/gtjlebrgrd.html

[U24] Py：路径操作
来源：http://dali.cqqwz.cn/Article/details/gtfbuwsdgt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtwstpmeng.html

[U25] Py：CSV 按字典读
来源：http://dali.xuanzx.com/Article/details/gtrooohatr.html

csv.DictReader(f)
来源：http://dali.yongpay.top/Article/details/gtfdjxrwsg.html

[U26] Py：并发下载
来源：http://dali.tianlin.xyz/Article/details/gthttewnet.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xylfe.cn/Article/details/gtkrnkppmc.html

[U27] Py：异步 HTTP
来源：http://dali.ehwqpu.com/Article/details/gttwkdwiab.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.redwolf501.top/Article/details/gtoepujgdy.html

[U28] Py：类型别名
来源：http://dali.zhiwuduotai.top/Article/details/gtxshbpijs.html

UserId = int
来源：http://dali.jinqigfzy.top/Article/details/gtnbwgldzm.html

[U29] Py：属性校验
来源：http://dali.shzxlz.cn/Article/details/gthaiktnmh.html

@property 与 @x.setter 配合
来源：http://dali.hfpthk.cn/Article/details/gtruwtrpnt.html

[U30] Py：数据类
来源：http://dali.jinqigufen.top/Article/details/gtibrxumec.html

@dataclass(slots=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtznrwcuvk.html

[U31] Py：单测
来源：http://dali.nanxuanxn.top/Article/details/gtqhsjlxbr.html

python -m pytest -q
来源：http://dali.0kj1m.cn/Article/details/gtcpphwnyb.html

[U32] Py：代码格式化
来源：http://dali.yj20258888.top/Article/details/gtoytmoydq.html

ruff format . && ruff check --fix .
来源：http://dali.ywan-chungtsiang.top/Article/details/gtularaqbt.html

[U33] Py：打包发布
来源：http://dali.aibaodan.cn/Article/details/gtunvqyewo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.aizwys.cn/Article/details/gtecwtsmqn.html

[U34] Py：判断编码
来源：http://dali.shanyushiyangtech.top/Article/details/gtzyhyuytn.html

chardet.detect(raw)
来源：http://dali.yj202588.top/Article/details/gtmhmcjgzr.html

[U35] Py：发送邮件
来源：http://dali.jiagoushi.top/Article/details/gtdhsschqn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jianghu66.top/Article/details/gtoqeceaxh.html

[U36] Py：定时任务
来源：http://dali.nwbrower.top/Article/details/gtukpxkefc.html

schedule.every(10).minutes.do(job)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbgyyeqn.html

[U37] Py：读写 Excel
来源：http://dali.redwolf501.top/Article/details/gtuzltgtqr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shuidangran.top/Article/details/gtmbxczeys.html

[U38] Py：获取脚本所在目录
来源：http://dali.gaohongyu789.top/Article/details/gthpqjcurg.html

Path(__file__).resolve().parent
来源：http://dali.daxiang520.top/Article/details/gtghgrxbmy.html

[U39] Py：判断是否在交互环境
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyadfbjk.html

sys.stdout.isatty()
来源：http://dali.chenjidiqi.icu/Article/details/gtfoyciacj.html

[U40] Py：打印到标准错误
来源：http://dali.fengsongda.top/Article/details/gtmhqpluct.html

print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gtwmpilogx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jqgufenzy.top/Article/details/gtinohcrzs.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.smart0.xyz/Article/details/gthqznndtr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gotoacloud.top/Article/details/gttqaznbvz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hongshengwenyu.top/Article/details/gthyipacyx.html

[U43] PHP：声明命名空间
来源：http://dali.xylfe.cn/Article/details/gtbxrqcjjy.html

namespace App\Http;
来源：http://dali.iojbl.cn/Article/details/gtnuaumiby.html

[U44] PHP：开启严格类型
来源：http://dali.yueranfly.top/Article/details/gtkxxcfqbm.html

declare(strict_types=1);
来源：http://dali.sufxvd.cn/Article/details/gtcfyordxm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jqgfzy.top/Article/details/gtjcgcbloo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtgyocayve.html

[U46] PHP：可空类型
来源：http://dali.hywenlv.cn/Article/details/gtauvsxuli.html

?string $name = null
来源：http://dali.mhx1999.top/Article/details/gtbmnzxagm.html

[U47] PHP：联合类型
来源：http://dali.hnxiangtu.top/Article/details/gtuclsofkd.html

int|string $id
来源：http://dali.wangdashe.top/Article/details/gtmjakeeal.html

[U48] PHP：纯枚举
来源：http://dali.hysaishi.cn/Article/details/gtlenebjve.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnvoxdrxt.html

[U49] PHP：只读属性
来源：http://dali.wangdashe.top/Article/details/gtfafioxjg.html

public readonly string $name
来源：http://dali.hysaishi.cn/Article/details/gtsgigsdho.html

[U50] PHP：构造器属性提升
来源：http://dali.gotoacloud.top/Article/details/gtwnxtokih.html

public function __construct(private int $id) {}
来源：http://dali.yueranfly.top/Article/details/gthrpaadin.html

[U51] PHP：数组解构
来源：http://dali.yj20258.top/Article/details/gtxzrbyney.html

[$a, $b] = $arr;
来源：http://dali.gogol.net.cn/Article/details/gttqddypwo.html

[U52] PHP：箭头函数
来源：http://dali.ppjwa.cn/Article/details/gtqzocicdr.html

$double = fn($x) => $x * 2;
来源：http://dali.daxiang520.top/Article/details/gtcbdzdely.html

[U53] PHP：空合并运算符
来源：http://dali.haohaochexian.top/Article/details/gtrywgvheh.html

$v = $a ?? $b ?? "default";
来源：http://dali.yonumen.top/Article/details/gtrulilutb.html

[U54] PHP：空安全调用
来源：http://dali.gzhubu.top/Article/details/gtusaursir.html

$obj?->method()
来源：http://dali.sxryk.cn/Article/details/gtbfaipioo.html

[U55] PHP：match 表达式
来源：http://dali.9152youxi.cn/Article/details/gtvkyoeysi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.316326.xyz/Article/details/gtxippnmsv.html

[U56] PHP：命名参数
来源：http://dali.tianlin.xyz/Article/details/gtufepbnxb.html

f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gtnkbevffk.html

[U57] PHP：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gtbctcxfgi.html

"值: {$a}"
来源：http://dali.chenlongwang.top/Article/details/gtjweqpthy.html

[U58] PHP：数组三件套
来源：http://dali.pengpengdd.cyou/Article/details/gtjhcizbsa.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.wangdashe.top/Article/details/gtuflpqvvy.html

[U59] PHP：自定义排序
来源：http://dali.yueranfly.top/Article/details/gtfdjyhzvp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jlsjyb.cn/Article/details/gtdbbugkyz.html

[U60] PHP：JSON 编解码
来源：http://dali.kuanghao11.cn/Article/details/gtyojrrxbm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.pycfn.com/Article/details/gtbkifomwh.html

[U61] PHP：正则
来源：http://dali.redwolf501.top/Article/details/gtzvddtbfb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gtmampmkzy.html

[U62] PHP：日期对象
来源：http://dali.cqqwz.cn/Article/details/gtyeaqqxfw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yanxiufei.cn/Article/details/gtsyttorkr.html

[U63] PHP：文件读写
来源：http://dali.fzhhl.top/Article/details/gtzmqwzqoh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yangfankeji.com/Article/details/gtamtvvtnd.html

[U64] PHP：目录遍历
来源：http://dali.jinqigufen.top/Article/details/gtrxjcuheg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj20258888.top/Article/details/gtlsrxhhya.html

[U65] PHP：会话
来源：http://dali.hfpthk.cn/Article/details/gtgaibupof.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtsvfhwigw.html

[U66] PHP：设置 Cookie
来源：http://dali.daxiang520.top/Article/details/gtropocgar.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhongyouzk.top/Article/details/gtzzixcqsa.html

[U67] PHP：处理文件上传
来源：http://dali.quarkkingdee.top/Article/details/gtwtswtrym.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yj20258.top/Article/details/gtkjntoadd.html

[U68] PHP：PDO 连接
来源：http://dali.dashuyun.cn/Article/details/gtadgtoxwu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jqgufenzy.top/Article/details/gtybowyvmh.html

[U69] PHP：PDO 预处理
来源：http://dali.birdmap.top/Article/details/gtdverlrtw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.andypj.xyz/Article/details/gtggxkgxut.html

[U70] PHP：PDO 事务
来源：http://dali.havefunace.top/Article/details/gttfkjcaif.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jyoumei.cn/Article/details/gtdywhxmse.html

[U71] PHP：抛出异常
来源：http://dali.jyoumei.cn/Article/details/gtvqgemudr.html

throw new RuntimeException("失败", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdavjoycx.html

[U72] PHP：写错误日志
来源：http://dali.dianchejie.cn/Article/details/gtoppedvti.html

error_log("失败: " . $e->getMessage());
来源：http://dali.dianchejie.cn/Article/details/gtwbciyzyp.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gtpkuxjjgs.html

parse_ini_file("config.ini", true)
来源：http://dali.yanxiufei.cn/Article/details/gtylwliedl.html

[U74] PHP：读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gtanajoali.html

getenv("APP_ENV") ?: "production"
来源：http://dali.nwbrower.top/Article/details/gtgfixppno.html

[U75] PHP：依赖注入
来源：http://dali.chenjidiqi.icu/Article/details/gtsssgsuyc.html

composer require psr/container
来源：http://dali.zhixingplan.top/Article/details/gtguuzzplx.html

[U76] PHP：简单路由
来源：http://dali.nanxuanxn.top/Article/details/gtvkyaomke.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hnqzz.top/Article/details/gthhgogjwv.html


<!-- 参考信息 -->