代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtkdzwwkvo.html

[S51] C++：显式类型转换
来源：http://dali.zhengqikj.top/Article/details/gtidyvrwnj.html

static_cast<double>(a) / b
来源：http://dali.meibo888.top/Article/details/gtygkbbjha.html

[S52] C++：const 与 noexcept
来源：http://dali.aibaodan.cn/Article/details/gtwkykxoqy.html

int size() const noexcept { return n_; }
来源：http://dali.hfpthk.cn/Article/details/gtoaznhnsw.html

[S53] C++：移动语义
来源：http://dali.hnxiangtu.top/Article/details/gthsqzivpm.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigufen.top/Article/details/gtoqigmkcw.html

[S54] C++：异常处理
来源：http://dali.redwolf501.top/Article/details/gtgeasfrze.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sysykeji.top/Article/details/gtlfgjunyq.html

[S55] C++：结构化绑定
来源：http://dali.chenlongwang.top/Article/details/gtuvdxrtqe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gzhubu.top/Article/details/gtlfsiowov.html

[S56] C++：optional
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfofqnnf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.c1oappe.top/Article/details/gtrznrukik.html

[S57] C++：编译期常量
来源：http://dali.snrcjt.cn/Article/details/gtlfbgpmvn.html

constexpr int N = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtjlxucqxa.html

[S58] C++：命名空间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqbmziqv.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnxiangtu.top/Article/details/gtedbwujxl.html

[S59] C++：静态断言
来源：http://dali.jinqigfzy.top/Article/details/gtwkwlnrha.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigfzy.top/Article/details/gttjvggzxf.html

[S60] C++：遍历并删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gtkylmgaec.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gtopijvxvj.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtkjkofrma.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gtljdooyky.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtfbjtdpek.html

[T01] Kotlin：Hello World
来源：http://dali.mhx1999.top/Article/details/gtmcautppe.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtuhtiwpkt.html

[T02] Kotlin：变量
来源：http://dali.nwbrower.top/Article/details/gtekbfjedx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yongpay.top/Article/details/gthfyvsuoh.html

[T03] Kotlin：字符串模板
来源：http://dali.sysykeji.top/Article/details/gtykbffxgf.html

"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gttfkhjrne.html

[T04] Kotlin：空安全
来源：http://dali.316326.xyz/Article/details/gtfgjyccie.html

val n: String? = null;  n?.length
来源：http://dali.gzhubu.top/Article/details/gtrbzngeph.html

[T05] Kotlin：when 表达式
来源：http://dali.zhixingplan.top/Article/details/gtwuzmcpia.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hfpthk.cn/Article/details/gtvqoyglbh.html

[T06] Kotlin：集合映射
来源：http://dali.yvedp.cn/Article/details/gtemvvrisl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.haohaochexian.top/Article/details/gtstqkukcb.html

[T07] Kotlin：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gtklehytpv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gtrqoilsou.html

[T08] Kotlin：数据类
来源：http://dali.yvedp.cn/Article/details/gtizdljsor.html

data class User(val name: String, val age: Int)
来源：http://dali.cashguo.top/Article/details/gtphhiublm.html

[T09] Kotlin：扩展函数
来源：http://dali.andypj.xyz/Article/details/gtuwfkjndt.html

fun String.exclaim() = this + "!"
来源：http://dali.tanke756.top/Article/details/gtgqaoauxy.html

[T10] Kotlin：默认参数
来源：http://dali.kuanghao11.cn/Article/details/gtsqqopfkj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.redwolf501.top/Article/details/gtlcmvqbcx.html

[T11] Kotlin：协程
来源：http://dali.meibo888.top/Article/details/gtmtevrchb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guowangkeji.top/Article/details/gtarxpkfvv.html

[T12] Kotlin：解构声明
来源：http://dali.aibaodan.cn/Article/details/gtcpbmgodr.html

val (a, b) = Pair(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtswpxxauw.html

[T13] Kotlin：只读 Map
来源：http://dali.ppjwa.cn/Article/details/gtkmqnkcki.html

val m = mapOf("a" to 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtjkmwjkwb.html

[T14] Kotlin：循环
来源：http://dali.hysaishi.cn/Article/details/gtvtgwlbdd.html

for (i in 1..10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gtqkmgpssx.html

[T15] Kotlin：接口
来源：http://dali.xziqi.cn/Article/details/gtbuhmessy.html

interface Shape { fun area(): Double }
来源：http://dali.hywenlv.cn/Article/details/gtsomhcoud.html

[T16] Swift：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtypxgzzzx.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gtjccvkxoi.html

[T17] Swift：变量与常量
来源：http://dali.ybcxt.top/Article/details/gtlyxcfxxj.html

var a = 1;  let b = 2
来源：http://dali.jinqigufen.top/Article/details/gtxvgaflqp.html

[T18] Swift：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gtkokvsfug.html

"值: \(b)"
来源：http://dali.jianghu66.top/Article/details/gtrorcubuv.html

[T19] Swift：可选绑定
来源：http://dali.dianchejie.cn/Article/details/gtsubxtumv.html

if let n = opt { print(n) }
来源：http://dali.xuetiantiany.cn/Article/details/gtfwuqrcmw.html

[T20] Swift：数组操作
来源：http://dali.hnqzz.top/Article/details/gtalsjptdo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gotoacloud.top/Article/details/gtktovoxyz.html

[T21] Swift：遍历
来源：http://dali.zdqjudy.top/Article/details/gtwclbkydh.html

for x in a { print(x) }
来源：http://dali.cucudq.cn/Article/details/gtyvincnqs.html

[T22] Swift：字典
来源：http://dali.hammf.cn/Article/details/gtjlaiopwy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigfzy.top/Article/details/gtkryhtvca.html

[T23] Swift：函数
来源：http://dali.yonumen.top/Article/details/gtupiwzhtr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtijwjoaqx.html

[T24] Swift：闭包
来源：http://dali.kuanghao11.cn/Article/details/gteyqmrmbf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gthurtjmsn.html

[T25] Swift：结构体
来源：http://dali.yangfankeji.com/Article/details/gtarmglhui.html

struct P { var x: Int }
来源：http://dali.hammf.cn/Article/details/gtodimyiwb.html

[T26] Swift：类与重写
来源：http://dali.redwolf501.top/Article/details/gtqbgdlkip.html

class A: Base { override func f() {} }
来源：http://dali.jianghu66.top/Article/details/gtrluhffqf.html

[T27] Swift：错误处理
来源：http://dali.zhongyouzk.top/Article/details/gtkuxfhhkh.html

do { try f() } catch { print(error) }
来源：http://dali.zhongyouzk.top/Article/details/gtgyassgvb.html

[T28] Swift：枚举
来源：http://dali.9152youxi.cn/Article/details/gtiqfhwyla.html

enum Color { case red, green }
来源：http://dali.tian-w.cn/Article/details/gtfzbbgymm.html

[T29] Swift：guard 提前返回
来源：http://dali.tian-w.cn/Article/details/gtgpcwywax.html

guard let x = opt else { return }
来源：http://dali.mhx1999.top/Article/details/gtcttrpjqd.html

[T30] Swift：协议
来源：http://dali.kuanghao11.cn/Article/details/gtmglckwbf.html

protocol Shape { func area() -> Double }
来源：http://dali.jiagoushi.top/Article/details/gtujspkeju.html

[T31] Lua：Hello World
来源：http://dali.yvedp.cn/Article/details/gtyyssquak.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gtbbdnvuhf.html

[T32] Lua：局部变量
来源：http://dali.nwbrower.top/Article/details/gtanxzkdci.html

local a = 1
来源：http://dali.svipenyu.cn/Article/details/gtwitzwfwa.html

[T33] Lua：表（数组）
来源：http://dali.sufxvd.cn/Article/details/gtaxcxtniw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.316326.xyz/Article/details/gtsdkzuljf.html

[T34] Lua：遍历表
来源：http://dali.birdmap.top/Article/details/gtdldefcof.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxinkj.top/Article/details/gtakskrypa.html

[T35] Lua：字典表
来源：http://dali.cucudq.cn/Article/details/gtvnygxxxi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhongyouzk.top/Article/details/gtekexfbip.html

[T36] Lua：函数
来源：http://dali.zycfv.cn/Article/details/gtbkhmejmk.html

function add(a, b) return a + b end
来源：http://dali.dashuyun.cn/Article/details/gtmkwzafos.html

[T37] Lua：字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gtnawapfql.html

"a" .. "b"
来源：http://dali.wangdashe.top/Article/details/gtyoyysptm.html

[T38] Lua：条件
来源：http://dali.0kj1m.cn/Article/details/gticvnizww.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuozndtlz.html

[T39] Lua：模式匹配
来源：http://dali.dianchejie.cn/Article/details/gtveysztxj.html

string.find(s, "%d+")
来源：http://dali.xuanzx.com/Article/details/gttuxqjabz.html

[T40] Lua：元表
来源：http://dali.hongshengwenyu.top/Article/details/gtbdadcndz.html

setmetatable({}, { __index = base })
来源：http://dali.gotoacloud.top/Article/details/gtgixgcwuf.html

[T41] Perl：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtepgayvfs.html

print "Hello\n";
来源：http://dali.zhongyouzk.top/Article/details/gtlonkfmwc.html

[T42] Perl：变量类型
来源：http://dali.yueranfly.top/Article/details/gtmpjcffve.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.guannengcc.top/Article/details/gtrtjjtyet.html

[T43] Perl：字符串插值
来源：http://dali.hammf.cn/Article/details/gthuxbdbgb.html

"值: $a"
来源：http://dali.hammf.cn/Article/details/gtjprwbgbz.html

[T44] Perl：条件
来源：http://dali.meibo888.top/Article/details/gtbqswgxiy.html

if ($a > 0) { print "正"; }
来源：http://dali.quarkkingdee.top/Article/details/gtbyfwbkfh.html

[T45] Perl：数组遍历
来源：http://dali.aizwys.cn/Article/details/gtfhmhwuag.html

for my $x (@arr) { print $x; }
来源：http://dali.meibo888.top/Article/details/gtgqsneouu.html

[T46] Perl：哈希操作
来源：http://dali.daxiang520.top/Article/details/gtgprufgdj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ppjwa.cn/Article/details/gtkzpiofop.html

[T47] Perl：正则捕获
来源：http://dali.iojbl.cn/Article/details/gtypjtbazg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nanxuanxn.top/Article/details/gtujoizlwt.html

[T48] Perl：正则替换
来源：http://dali.zhoulong.xyz/Article/details/gteomunpay.html

$s =~ s/old/new/g;
来源：http://dali.pengpengdd.cyou/Article/details/gtrelghdrz.html

[T49] Perl：函数
来源：http://dali.xylfe.cn/Article/details/gtymbrzxxe.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtahypanyl.html

[T50] Perl：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtinefskyo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhiwuduotai.top/Article/details/gtrvqjaiwk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gtykhbpkde.html

[T51] Scala：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejlnpnrg.html

println("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtlukdisgc.html

[T52] Scala：变量
来源：http://dali.sweek.top/Article/details/gtndnadtol.html

val a = 1;  var b = 2
来源：http://dali.yj20258.top/Article/details/gtuxszjdwi.html

[T53] Scala：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gthlgpxxbk.html

s"值: $b"
来源：http://dali.cucudq.cn/Article/details/gtdemywtwp.html

[T54] Scala：集合映射
来源：http://dali.guannengcc.top/Article/details/gthgoleibg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hnxiangtu.top/Article/details/gtdizlfotk.html

[T55] Scala：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gttsipboqx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.wangdashe.top/Article/details/gtqnlvmymm.html

[T56] Scala：样例类
来源：http://dali.shuidangran.top/Article/details/gttzzaiqae.html

case class User(name: String, age: Int)
来源：http://dali.mhx1999.top/Article/details/gtoevhgtci.html

[T57] Scala：模式匹配
来源：http://dali.zhongyouzk.top/Article/details/gtqwtrxqqt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.redwolf501.top/Article/details/gtbdlphybr.html

[T58] Scala：函数定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtennflcnz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbuknefvb.html

[T59] Scala：循环
来源：http://dali.pengpengdd.cyou/Article/details/gtywfxafyj.html

for (i <- 1 to 10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gttvmghljs.html

[T60] Scala：折叠
来源：http://dali.mhx1999.top/Article/details/gtnuexcaqd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakphoqtc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtjmqbotcw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hfpthk.cn/Article/details/gtdpglqmvk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmyvhwhh.html

[U01] Py：创建虚拟环境
来源：http://dali.ppjwa.cn/Article/details/gtzogfdcao.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.meibo888.top/Article/details/gtvlmnsplr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.guannengcc.top/Article/details/gtwmbhywyc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ppjwa.cn/Article/details/gtakadhern.html

[U03] Py：加载 .env 配置
来源：http://dali.hysaishi.cn/Article/details/gtgwbcjvtc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hnqzz.top/Article/details/gtigkuecft.html

[U04] Py：变量调试打印
来源：http://dali.jyoumei.cn/Article/details/gtfaoumhtl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sxryk.cn/Article/details/gtjmbsrlbd.html

[U05] Py：列表去重且保序
来源：http://dali.yonumen.top/Article/details/gtmftpyjjf.html

list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtnnenugbz.html

[U06] Py：合并两个字典
来源：http://dali.shangyingyoupin.top/Article/details/gtscqdiaqm.html

{**a, **b}
来源：http://dali.yj20258.top/Article/details/gtrrjngluz.html

[U07] Py：反转字典键值
来源：http://dali.yongpay.top/Article/details/gtfyquxsqv.html

{v: k for k, v in d.items()}
来源：http://dali.iojbl.cn/Article/details/gtswwmyfxm.html

[U08] Py：展平二维列表
来源：http://dali.jinqigufen.top/Article/details/gtphsjgcsn.html

[y for x in nested for y in x]
来源：http://dali.yongpay.top/Article/details/gtrhiamahn.html

[U09] Py：字典取最大值的键
来源：http://dali.zdqjudy.top/Article/details/gtflxtndvs.html

max(d, key=d.get)
来源：http://dali.pycfn.com/Article/details/gtoeoskwxe.html

[U10] Py：按值排序字典
来源：http://dali.shzxlz.cn/Article/details/gtzribfcos.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwcswjno.html

[U11] Py：生成器表达式
来源：http://dali.xuanzx.com/Article/details/gtrnojgjqn.html

(x * 2 for x in arr)
来源：http://dali.mhx1999.top/Article/details/gtfstdmbpc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.vqdsnc.cn/Article/details/gtqhqxhxqt.html

Counter(arr).most_common(3)
来源：http://dali.9152youxi.cn/Article/details/gtrjqlowpx.html

[U13] Py：固定长度队列
来源：http://dali.gogol.net.cn/Article/details/gtwbjdfdxd.html

deque(maxlen=10)
来源：http://dali.haohaochexian.top/Article/details/gtdglqpivu.html

[U14] Py：分组收集到列表
来源：http://dali.ivvv.top/Article/details/gtrvjhkdia.html

defaultdict(list)
来源：http://dali.daxiang520.top/Article/details/gtwzhjlqsp.html

[U15] Py：高精度计时
来源：http://dali.ybcxt.top/Article/details/gtytsltrzw.html

t = time.perf_counter()
来源：http://dali.shzxlz.cn/Article/details/gtbivxcxkx.html

[U16] Py：命令行参数解析
来源：http://dali.fzhhl.top/Article/details/gtlagejajd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.andypj.xyz/Article/details/gtlzzdiigg.html

[U17] Py：初始化日志
来源：http://dali.yuanzhike.top/Article/details/gtsuljglbi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nwbrower.top/Article/details/gtuwzjybio.html

[U18] Py：预编译正则
来源：http://dali.yueranfly.top/Article/details/gtbvzwejoj.html

pat = re.compile(r"\d+")
来源：http://dali.sysykeji.top/Article/details/gtqdwuxlvx.html

[U19] Py：正则替换带回调
来源：http://dali.redwolf501.top/Article/details/gtflzsjvub.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gtodqyqxvw.html

[U20] Py：缓存函数结果
来源：http://dali.birdmap.top/Article/details/gtqjzdisba.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gtidhjtyob.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigufen.top/Article/details/gtlozupmsv.html

@contextlib.contextmanager
来源：http://dali.bjfxy.top/Article/details/gtlskdpjqj.html

[U22] Py：矩阵转置
来源：http://dali.tian-w.cn/Article/details/gtwvmasyzy.html

list(zip(*m))
来源：http://dali.jinghuilouyu.cn/Article/details/gtemacijiw.html

[U23] Py：分块读取大文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyshgbwj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nanxuanxn.top/Article/details/gtmzictrro.html

[U24] Py：路径操作
来源：http://dali.pycfn.com/Article/details/gtmxbllsge.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gtjmcwfqdq.html

[U25] Py：CSV 按字典读
来源：http://dali.wangshuangyany.cn/Article/details/gtvxvxcyzr.html

csv.DictReader(f)
来源：http://dali.aibaodan.cn/Article/details/gtxvkujdkj.html

[U26] Py：并发下载
来源：http://dali.haohaochexian.top/Article/details/gtiefatebq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gtkspbukxo.html

[U27] Py：异步 HTTP
来源：http://dali.guannengcc.top/Article/details/gtkxfvvtfk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xinyue.icu/Article/details/gtuthudjpf.html

[U28] Py：类型别名
来源：http://dali.havefunace.top/Article/details/gtlfcszwli.html

UserId = int
来源：http://dali.hnqzz.top/Article/details/gtkbwcywfc.html

[U29] Py：属性校验
来源：http://dali.daria6918.cn/Article/details/gtgnrnwhzw.html

@property 与 @x.setter 配合
来源：http://dali.mhx1999.top/Article/details/gtbsxyopyd.html

[U30] Py：数据类
来源：http://dali.yuxming.cn/Article/details/gtjevpwpdr.html

@dataclass(slots=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtbzcygsik.html

[U31] Py：单测
来源：http://dali.yuxming.cn/Article/details/gtmgsykjwu.html

python -m pytest -q
来源：http://dali.dashuyun.cn/Article/details/gtmdcszpgl.html

[U32] Py：代码格式化
来源：http://dali.nwbrower.top/Article/details/gtopvipxce.html

ruff format . && ruff check --fix .
来源：http://dali.bjfxy.top/Article/details/gtbfjigtqv.html

[U33] Py：打包发布
来源：http://dali.chenjidiqi.icu/Article/details/gtnsjjksuo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yueranfly.top/Article/details/gtcxjcmfun.html

[U34] Py：判断编码
来源：http://dali.sysykeji.top/Article/details/gtnwdfruas.html

chardet.detect(raw)
来源：http://dali.snrcjt.cn/Article/details/gtzhpknpnf.html

[U35] Py：发送邮件
来源：http://dali.yvedp.cn/Article/details/gtkzzukwva.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.kuanghao11.cn/Article/details/gtenfhehqo.html

[U36] Py：定时任务
来源：http://dali.guannengcc.top/Article/details/gtxziehlof.html

schedule.every(10).minutes.do(job)
来源：http://dali.tanke756.top/Article/details/gtebytkvdj.html

[U37] Py：读写 Excel
来源：http://dali.nanxuanxn.top/Article/details/gtpkrntgrh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gaohongyu789.top/Article/details/gtblhnljsw.html

[U38] Py：获取脚本所在目录
来源：http://dali.havefunace.top/Article/details/gtjietbhhu.html

Path(__file__).resolve().parent
来源：http://dali.hysaishi.cn/Article/details/gtkqxuwofi.html

[U39] Py：判断是否在交互环境
来源：http://dali.gzhubu.top/Article/details/gtlghoocnq.html

sys.stdout.isatty()
来源：http://dali.xylfe.cn/Article/details/gtnbgblbcg.html

[U40] Py：打印到标准错误
来源：http://dali.vqdsnc.cn/Article/details/gtsdxhdysr.html

print("err", file=sys.stderr)
来源：http://dali.ivvv.top/Article/details/gtadixmeay.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zycfv.cn/Article/details/gttenmiqrb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.nwbrower.top/Article/details/gtllgixset.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhengqikj.top/Article/details/gtplvvgmnm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.kuanghao11.cn/Article/details/gtgsmxithx.html

[U43] PHP：声明命名空间
来源：http://dali.iojbl.cn/Article/details/gtgwtcodph.html

namespace App\Http;
来源：http://dali.zhoulong.xyz/Article/details/gtvrhytewm.html

[U44] PHP：开启严格类型
来源：http://dali.ybcxt.top/Article/details/gtkulxdoam.html

declare(strict_types=1);
来源：http://dali.c1oappe.top/Article/details/gtevurxiww.html

[U45] PHP：类型声明与返回类型
来源：http://dali.nanxuanxn.top/Article/details/gtxaomimke.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnshixrdg.html

[U46] PHP：可空类型
来源：http://dali.svipenyu.cn/Article/details/gthdaibazv.html

?string $name = null
来源：http://dali.xuanzx.com/Article/details/gtjftshuca.html

[U47] PHP：联合类型
来源：http://dali.jlsjyb.cn/Article/details/gtkbpyoauy.html

int|string $id
来源：http://dali.cucudq.cn/Article/details/gtwuxsmehk.html

[U48] PHP：纯枚举
来源：http://dali.hammf.cn/Article/details/gttgnvnxra.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hnxiangtu.top/Article/details/gtfszrarry.html

[U49] PHP：只读属性
来源：http://dali.haohaochexian.top/Article/details/gtphizbnaa.html

public readonly string $name
来源：http://dali.cheryme.top/Article/details/gtufekyses.html

[U50] PHP：构造器属性提升
来源：http://dali.guannengcc.top/Article/details/gtytkphwbg.html

public function __construct(private int $id) {}
来源：http://dali.cdnleiting.top/Article/details/gtjeatdfal.html

[U51] PHP：数组解构
来源：http://dali.zhiwuduotai.top/Article/details/gtfsskisdk.html

[$a, $b] = $arr;
来源：http://dali.xuetiantiany.cn/Article/details/gtzhfovgty.html

[U52] PHP：箭头函数
来源：http://dali.chenzaomai.com/Article/details/gttqqykkwa.html

$double = fn($x) => $x * 2;
来源：http://dali.shanyushiyangtech.top/Article/details/gttaafjmdv.html

[U53] PHP：空合并运算符
来源：http://dali.ydzc1.top/Article/details/gtlylvfdbi.html

$v = $a ?? $b ?? "default";
来源：http://dali.nanxinkj.top/Article/details/gtepbrzxep.html

[U54] PHP：空安全调用
来源：http://dali.aizwys.cn/Article/details/gtxyhlknkv.html

$obj?->method()
来源：http://dali.jyoumei.cn/Article/details/gtiwheoekd.html

[U55] PHP：match 表达式
来源：http://dali.pycfn.com/Article/details/gtauhqwusf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.daxiang520.top/Article/details/gtnbqnzesx.html

[U56] PHP：命名参数
来源：http://dali.hnqzz.top/Article/details/gturhyyxgs.html

f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gtgdhlvbda.html

[U57] PHP：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gtjjxvrxgu.html

"值: {$a}"
来源：http://dali.shzxlz.cn/Article/details/gtioclxjne.html

[U58] PHP：数组三件套
来源：http://dali.jlsjyb.cn/Article/details/gtbhnutqdl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtymwdjuwa.html

[U59] PHP：自定义排序
来源：http://dali.tian-w.cn/Article/details/gtyxsyfrvc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gtdqktgkie.html

[U60] PHP：JSON 编解码
来源：http://dali.jyoumei.cn/Article/details/gtftdfmopg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.chenzaomai.com/Article/details/gtcolutvjn.html

[U61] PHP：正则
来源：http://dali.yj20258888.top/Article/details/gtvopbyvme.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.snrcjt.cn/Article/details/gtehxpctaa.html

[U62] PHP：日期对象
来源：http://dali.yonumen.top/Article/details/gtwkspuacc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.nwbrower.top/Article/details/gtvqnrqnye.html

[U63] PHP：文件读写
来源：http://dali.guowangkeji.top/Article/details/gtbpvokeqz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yueranfly.top/Article/details/gtfvzcychz.html

[U64] PHP：目录遍历
来源：http://dali.snrcjt.cn/Article/details/gtuwswkjtj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jlsjyb.cn/Article/details/gtbmlcahzv.html

[U65] PHP：会话
来源：http://dali.nwbrower.top/Article/details/gtgnnfniyr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtoqymyrkm.html

[U66] PHP：设置 Cookie
来源：http://dali.haohaochexian.top/Article/details/gteidkumdo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.316326.xyz/Article/details/gtqzyggvdr.html

[U67] PHP：处理文件上传
来源：http://dali.0kj1m.cn/Article/details/gtkpnlspka.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.guowangkeji.top/Article/details/gtwllkozmo.html

[U68] PHP：PDO 连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtltwrnrib.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.feifeiyinyue.top/Article/details/gtenammovx.html

[U69] PHP：PDO 预处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwvopser.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.snrcjt.cn/Article/details/gtwlrnmmjt.html

[U70] PHP：PDO 事务
来源：http://dali.tanke756.top/Article/details/gtmzavqjtg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.wangshuangyany.cn/Article/details/gtyuxvzfpv.html

[U71] PHP：抛出异常
来源：http://dali.hnqzz.top/Article/details/gtjkinhhsd.html

throw new RuntimeException("失败", 500);
来源：http://dali.gaohongyu789.top/Article/details/gtvzmhxwyw.html

[U72] PHP：写错误日志
来源：http://dali.ppjwa.cn/Article/details/gtrjrixoyf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfbkpyok.html

[U73] PHP：读取 ini 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkrruskc.html

parse_ini_file("config.ini", true)
来源：http://dali.zycfv.cn/Article/details/gtnxghlkhv.html

[U74] PHP：读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gtgwmiuwxs.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cheryme.top/Article/details/gtrnewcpwj.html

[U75] PHP：依赖注入
来源：http://dali.hnxiangtu.top/Article/details/gttspgwuqj.html

composer require psr/container
来源：http://dali.smart0.xyz/Article/details/gtpumyjwon.html

[U76] PHP：简单路由
来源：http://dali.c1oappe.top/Article/details/gtrawlimir.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xuanzx.com/Article/details/gtmjrvjspc.html


<!-- 参考信息 -->