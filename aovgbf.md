代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtojorcqxj.html

[S51] C++：显式类型转换
来源：http://dali.zhongyouzk.top/Article/details/gtdfpgmhcf.html

static_cast<double>(a) / b
来源：http://dali.kuanghao11.cn/Article/details/gtdkskrxbb.html

[S52] C++：const 与 noexcept
来源：http://dali.cucudq.cn/Article/details/gtpldcrfxw.html

int size() const noexcept { return n_; }
来源：http://dali.fengsongda.top/Article/details/gtucamylfp.html

[S53] C++：移动语义
来源：http://dali.yvedp.cn/Article/details/gtvjsuclkb.html

std::vector<int> w = std::move(v);
来源：http://dali.cheryme.top/Article/details/gtwfjnwfsg.html

[S54] C++：异常处理
来源：http://dali.daxiang520.top/Article/details/gtbvugjvbc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinqigfzy.top/Article/details/gtlvrerrvl.html

[S55] C++：结构化绑定
来源：http://dali.shuidangran.top/Article/details/gtuepiyvhm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jianghu66.top/Article/details/gtqofyawvr.html

[S56] C++：optional
来源：http://dali.jianghu66.top/Article/details/gtrtpbonvg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yonumen.top/Article/details/gtkwiagzrs.html

[S57] C++：编译期常量
来源：http://dali.daxiang520.top/Article/details/gtcivnhhlg.html

constexpr int N = 10;
来源：http://dali.smart0.xyz/Article/details/gtioteuaum.html

[S58] C++：命名空间
来源：http://dali.tianlin.xyz/Article/details/gtkwcvveqa.html

namespace ns { int f() { return 1; } }
来源：http://dali.smart0.xyz/Article/details/gtyqpohvds.html

[S59] C++：静态断言
来源：http://dali.zhixingplan.top/Article/details/gtbtdwesoq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhiwuduotai.top/Article/details/gtmmlqivkh.html

[S60] C++：遍历并删除元素
来源：http://dali.pycfn.com/Article/details/gtdggmfuqu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfpiebud.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtjurivtlp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nwbrower.top/Article/details/gttxzeyvvl.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbwjoftu.html

[T01] Kotlin：Hello World
来源：http://dali.316326.xyz/Article/details/gtcjiptzrf.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gtmvytxkob.html

[T02] Kotlin：变量
来源：http://dali.yueranfly.top/Article/details/gtltaqulqn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.bjfxy.top/Article/details/gtpueqzmnd.html

[T03] Kotlin：字符串模板
来源：http://dali.nwbrower.top/Article/details/gtqmzbivzy.html

"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gtktpuuaxp.html

[T04] Kotlin：空安全
来源：http://dali.jlsjyb.cn/Article/details/gtlycdigwc.html

val n: String? = null;  n?.length
来源：http://dali.xylfe.cn/Article/details/gtpjjwnapd.html

[T05] Kotlin：when 表达式
来源：http://dali.jqgufenzy.top/Article/details/gtmivpyucb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shuidangran.top/Article/details/gtawiirxzy.html

[T06] Kotlin：集合映射
来源：http://dali.xinyue.icu/Article/details/gtzbhldkgy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.0kj1m.cn/Article/details/gtcylfwxsn.html

[T07] Kotlin：集合过滤
来源：http://dali.hammf.cn/Article/details/gtwhfejprd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dianchejie.cn/Article/details/gtdbquehea.html

[T08] Kotlin：数据类
来源：http://dali.fzhhl.top/Article/details/gtosoyvdzq.html

data class User(val name: String, val age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjuifpjfx.html

[T09] Kotlin：扩展函数
来源：http://dali.cashguo.top/Article/details/gtbgjjfjbx.html

fun String.exclaim() = this + "!"
来源：http://dali.jyoumei.cn/Article/details/gticdqcurv.html

[T10] Kotlin：默认参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqlsursp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.vqdsnc.cn/Article/details/gtkkcmjxgx.html

[T11] Kotlin：协程
来源：http://dali.yj202588.top/Article/details/gtkqtcyvtw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gogol.net.cn/Article/details/gtnyzdditw.html

[T12] Kotlin：解构声明
来源：http://dali.jyoumei.cn/Article/details/gteyfvxjiw.html

val (a, b) = Pair(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtbeeraior.html

[T13] Kotlin：只读 Map
来源：http://dali.ybcxt.top/Article/details/gtwgbqjfbu.html

val m = mapOf("a" to 1)
来源：http://dali.gotoacloud.top/Article/details/gtemwthglf.html

[T14] Kotlin：循环
来源：http://dali.yuanzhike.top/Article/details/gtsggdykbu.html

for (i in 1..10) println(i)
来源：http://dali.pycfn.com/Article/details/gtoyfezrqo.html

[T15] Kotlin：接口
来源：http://dali.hnxiangtu.top/Article/details/gtoxmlvwce.html

interface Shape { fun area(): Double }
来源：http://dali.xuanzx.com/Article/details/gtswgxsmes.html

[T16] Swift：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtkscoctsz.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtsrxvdcga.html

[T17] Swift：变量与常量
来源：http://dali.yangfankeji.com/Article/details/gtqpngswwy.html

var a = 1;  let b = 2
来源：http://dali.svipenyu.cn/Article/details/gtmonwdozl.html

[T18] Swift：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtaootitkh.html

"值: \(b)"
来源：http://dali.yongpay.top/Article/details/gtmrwqqxvs.html

[T19] Swift：可选绑定
来源：http://dali.hysaishi.cn/Article/details/gtqonfhpas.html

if let n = opt { print(n) }
来源：http://dali.xylfe.cn/Article/details/gtqbwoohux.html

[T20] Swift：数组操作
来源：http://dali.zycfv.cn/Article/details/gtgkcfhyel.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.quarkkingdee.top/Article/details/gtscdakhcn.html

[T21] Swift：遍历
来源：http://dali.c1oappe.top/Article/details/gtyroparpm.html

for x in a { print(x) }
来源：http://dali.jyoumei.cn/Article/details/gtxsouiytq.html

[T22] Swift：字典
来源：http://dali.shangyingyoupin.top/Article/details/gtdbbwmerv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gogol.net.cn/Article/details/gtwbszydzp.html

[T23] Swift：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtfahcvvnz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ivvv.top/Article/details/gtakifylnh.html

[T24] Swift：闭包
来源：http://dali.snrcjt.cn/Article/details/gthyczvkly.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnqzz.top/Article/details/gtjrsqmkki.html

[T25] Swift：结构体
来源：http://dali.yuanzhike.top/Article/details/gtopdypmma.html

struct P { var x: Int }
来源：http://dali.gogol.net.cn/Article/details/gtsnphyoou.html

[T26] Swift：类与重写
来源：http://dali.cheryme.top/Article/details/gttsagxrgh.html

class A: Base { override func f() {} }
来源：http://dali.tian-w.cn/Article/details/gtkfvtxivg.html

[T27] Swift：错误处理
来源：http://dali.ppjwa.cn/Article/details/gtaousoehz.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gtrbecyovb.html

[T28] Swift：枚举
来源：http://dali.hnxiangtu.top/Article/details/gtlbwgnher.html

enum Color { case red, green }
来源：http://dali.shuidangran.top/Article/details/gtrjpupbcx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhixingplan.top/Article/details/gtiupxwigr.html

guard let x = opt else { return }
来源：http://dali.xylfe.cn/Article/details/gtyfnqnreo.html

[T30] Swift：协议
来源：http://dali.cheryme.top/Article/details/gtuxygfzzq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhongyouzk.top/Article/details/gtpbrmsvmj.html

[T31] Lua：Hello World
来源：http://dali.snrcjt.cn/Article/details/gteegevfhy.html

print("Hello")
来源：http://dali.cucudq.cn/Article/details/gtdgktdgrn.html

[T32] Lua：局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtvnirfpwv.html

local a = 1
来源：http://dali.chenlongwang.top/Article/details/gtfvalayse.html

[T33] Lua：表（数组）
来源：http://dali.ivvv.top/Article/details/gtcmelpxcj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cucudq.cn/Article/details/gtmbnhnrcv.html

[T34] Lua：遍历表
来源：http://dali.yvedp.cn/Article/details/gtveohadtm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hysaishi.cn/Article/details/gtklhozihw.html

[T35] Lua：字典表
来源：http://dali.chenjidiqi.icu/Article/details/gtoaytswom.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gogol.net.cn/Article/details/gtcozcpxwk.html

[T36] Lua：函数
来源：http://dali.redwolf501.top/Article/details/gtnllmxzii.html

function add(a, b) return a + b end
来源：http://dali.xziqi.cn/Article/details/gtwvirnuwm.html

[T37] Lua：字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzfeslgg.html

"a" .. "b"
来源：http://dali.aibaodan.cn/Article/details/gtqukjjyws.html

[T38] Lua：条件
来源：http://dali.cheryme.top/Article/details/gtsushcjlc.html

if x > 0 then print("正") end
来源：http://dali.pycfn.com/Article/details/gtqsqkaobx.html

[T39] Lua：模式匹配
来源：http://dali.xylfe.cn/Article/details/gtgnjddotn.html

string.find(s, "%d+")
来源：http://dali.havefunace.top/Article/details/gttpaqicig.html

[T40] Lua：元表
来源：http://dali.zhengqikj.top/Article/details/gtbagdtpyd.html

setmetatable({}, { __index = base })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkbqiuhr.html

[T41] Perl：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtwfcnsjph.html

print "Hello\n";
来源：http://dali.ybcxt.top/Article/details/gtwxxfmdjw.html

[T42] Perl：变量类型
来源：http://dali.bjfxy.top/Article/details/gtkgthjwtq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuanzx.com/Article/details/gtsinvliwq.html

[T43] Perl：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtekcbltbg.html

"值: $a"
来源：http://dali.shuidangran.top/Article/details/gtgsiphpxe.html

[T44] Perl：条件
来源：http://dali.jqgfzy.top/Article/details/gtxqnbbxsu.html

if ($a > 0) { print "正"; }
来源：http://dali.redwolf501.top/Article/details/gthqowgxxl.html

[T45] Perl：数组遍历
来源：http://dali.nanxinkj.top/Article/details/gtqpqxyamv.html

for my $x (@arr) { print $x; }
来源：http://dali.yonumen.top/Article/details/gttyekvubf.html

[T46] Perl：哈希操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtodbvsbwd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gotoacloud.top/Article/details/gtxxgxlhkr.html

[T47] Perl：正则捕获
来源：http://dali.pycfn.com/Article/details/gtzvloralo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zycfv.cn/Article/details/gtzymrykpi.html

[T48] Perl：正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyixgdttz.html

$s =~ s/old/new/g;
来源：http://dali.yangfankeji.com/Article/details/gtbtbchumd.html

[T49] Perl：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyscqzqms.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturwcexkv.html

[T50] Perl：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtxwogmszy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj20258888.top/Article/details/gtglirkfga.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zycfv.cn/Article/details/gtmdhjwafp.html

[T51] Scala：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gttkxqpdfr.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtqpmmbqbv.html

[T52] Scala：变量
来源：http://dali.nanxinkj.top/Article/details/gtxpwsxtlk.html

val a = 1;  var b = 2
来源：http://dali.zycfv.cn/Article/details/gtlhndikor.html

[T53] Scala：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtxpjslche.html

s"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gtgcohifnq.html

[T54] Scala：集合映射
来源：http://dali.dianchejie.cn/Article/details/gtqrljzaab.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtzrtbwoiu.html

[T55] Scala：集合过滤
来源：http://dali.fzhhl.top/Article/details/gtltsculbl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cheryme.top/Article/details/gtspayvwdz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gthzdmpckq.html

case class User(name: String, age: Int)
来源：http://dali.jianghu66.top/Article/details/gtwlkxxnet.html

[T57] Scala：模式匹配
来源：http://dali.fengsongda.top/Article/details/gtthlzxlpz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hammf.cn/Article/details/gtzbfczgbr.html

[T58] Scala：函数定义
来源：http://dali.sweek.top/Article/details/gtrezwzgby.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hywenlv.cn/Article/details/gtnoyaqnac.html

[T59] Scala：循环
来源：http://dali.yonumen.top/Article/details/gtrsgwxuvd.html

for (i <- 1 to 10) println(i)
来源：http://dali.wangdashe.top/Article/details/gttuzjgdcb.html

[T60] Scala：折叠
来源：http://dali.birdmap.top/Article/details/gtzqnkuafe.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlglozvmh.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtgwzhkviv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.guowangkeji.top/Article/details/gtyvzzzpxy.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshdmpebo.html

[U01] Py：创建虚拟环境
来源：http://dali.hammf.cn/Article/details/gtxoxdewow.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.haohaochexian.top/Article/details/gtavazmnzv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.vqdsnc.cn/Article/details/gtfqgwtnvo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yonumen.top/Article/details/gtuchqpqie.html

[U03] Py：加载 .env 配置
来源：http://dali.yongpay.top/Article/details/gtxpqeqshj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hnxiangtu.top/Article/details/gtbldrfqdw.html

[U04] Py：变量调试打印
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmpnqtia.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ppjwa.cn/Article/details/gttldhmdpc.html

[U05] Py：列表去重且保序
来源：http://dali.dianchejie.cn/Article/details/gtubwvannt.html

list(dict.fromkeys(arr))
来源：http://dali.hnxiangtu.top/Article/details/gtsccqmyfx.html

[U06] Py：合并两个字典
来源：http://dali.yanxiufei.cn/Article/details/gtijehhwvr.html

{**a, **b}
来源：http://dali.hnqzz.top/Article/details/gtiebvipqx.html

[U07] Py：反转字典键值
来源：http://dali.316326.xyz/Article/details/gthxpbwuti.html

{v: k for k, v in d.items()}
来源：http://dali.kuanghao11.cn/Article/details/gtklvimurl.html

[U08] Py：展平二维列表
来源：http://dali.316326.xyz/Article/details/gtypwuelvb.html

[y for x in nested for y in x]
来源：http://dali.ybcxt.top/Article/details/gtxryatdvz.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258888.top/Article/details/gtjcyvcfba.html

max(d, key=d.get)
来源：http://dali.birdmap.top/Article/details/gtfnkeqykw.html

[U10] Py：按值排序字典
来源：http://dali.haohaochexian.top/Article/details/gtieydsrhj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteskscwlh.html

[U11] Py：生成器表达式
来源：http://dali.haohaochexian.top/Article/details/gtelilstbm.html

(x * 2 for x in arr)
来源：http://dali.sxryk.cn/Article/details/gtjdkmnwqd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cdnleiting.top/Article/details/gthxssgnxj.html

Counter(arr).most_common(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqufawzs.html

[U13] Py：固定长度队列
来源：http://dali.tianlin.xyz/Article/details/gtiprgmzwg.html

deque(maxlen=10)
来源：http://dali.haohaochexian.top/Article/details/gteufqkpzy.html

[U14] Py：分组收集到列表
来源：http://dali.daxiang520.top/Article/details/gttywfbavn.html

defaultdict(list)
来源：http://dali.hnqzz.top/Article/details/gtxnxmlqys.html

[U15] Py：高精度计时
来源：http://dali.yj20258.top/Article/details/gtdlptthce.html

t = time.perf_counter()
来源：http://dali.yanxiufei.cn/Article/details/gtamqtrqsn.html

[U16] Py：命令行参数解析
来源：http://dali.tianlin.xyz/Article/details/gtwsjnujog.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.chenzaomai.com/Article/details/gtlsyfocuj.html

[U17] Py：初始化日志
来源：http://dali.guannengcc.top/Article/details/gtkmoogowl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xylfe.cn/Article/details/gtimhrwdit.html

[U18] Py：预编译正则
来源：http://dali.yuxming.cn/Article/details/gtqdttwqry.html

pat = re.compile(r"\d+")
来源：http://dali.ppjwa.cn/Article/details/gtahsrskqp.html

[U19] Py：正则替换带回调
来源：http://dali.xuetiantiany.cn/Article/details/gtlyyyqnks.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnlfoozs.html

[U20] Py：缓存函数结果
来源：http://dali.yongpay.top/Article/details/gtpmjtyzwm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.mhx1999.top/Article/details/gtphmnhwbc.html

[U21] Py：自定义上下文管理器
来源：http://dali.0kj1m.cn/Article/details/gtonzywwlt.html

@contextlib.contextmanager
来源：http://dali.sufxvd.cn/Article/details/gtblcewtby.html

[U22] Py：矩阵转置
来源：http://dali.xinyue.icu/Article/details/gtawhqoesx.html

list(zip(*m))
来源：http://dali.chenjidiqi.icu/Article/details/gtqewppbbi.html

[U23] Py：分块读取大文件
来源：http://dali.shuidangran.top/Article/details/gtdkmghawk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.aibaodan.cn/Article/details/gtzhbwvgma.html

[U24] Py：路径操作
来源：http://dali.smart0.xyz/Article/details/gtpwsqvgfg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gtybgodukz.html

[U25] Py：CSV 按字典读
来源：http://dali.sweek.top/Article/details/gtudawkmvs.html

csv.DictReader(f)
来源：http://dali.wangdashe.top/Article/details/gtuirncign.html

[U26] Py：并发下载
来源：http://dali.yj20258.top/Article/details/gtfvpjyhom.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.vqdsnc.cn/Article/details/gtfqztapxz.html

[U27] Py：异步 HTTP
来源：http://dali.cheryme.top/Article/details/gtuajjgqxn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yangfankeji.com/Article/details/gtwzggenak.html

[U28] Py：类型别名
来源：http://dali.c1oappe.top/Article/details/gtswiwwoiq.html

UserId = int
来源：http://dali.shanyushiyangtech.top/Article/details/gttlngjaky.html

[U29] Py：属性校验
来源：http://dali.zhengqikj.top/Article/details/gtgvgciocl.html

@property 与 @x.setter 配合
来源：http://dali.haohaochexian.top/Article/details/gtgzgowozs.html

[U30] Py：数据类
来源：http://dali.zycfv.cn/Article/details/gttbvgbkua.html

@dataclass(slots=True)
来源：http://dali.tian-w.cn/Article/details/gtokxmygss.html

[U31] Py：单测
来源：http://dali.redwolf501.top/Article/details/gttbtewhmy.html

python -m pytest -q
来源：http://dali.andypj.xyz/Article/details/gtlmgsdozf.html

[U32] Py：代码格式化
来源：http://dali.316326.xyz/Article/details/gtncuhywmy.html

ruff format . && ruff check --fix .
来源：http://dali.quarkkingdee.top/Article/details/gtywlzxzay.html

[U33] Py：打包发布
来源：http://dali.guowangkeji.top/Article/details/gtobltxiov.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.kuanghao11.cn/Article/details/gtyrrlilxe.html

[U34] Py：判断编码
来源：http://dali.jinqigfzy.top/Article/details/gttmivxfdd.html

chardet.detect(raw)
来源：http://dali.shangyingyoupin.top/Article/details/gtvlhjjpok.html

[U35] Py：发送邮件
来源：http://dali.cdnleiting.top/Article/details/gtqymwkcsl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhoulong.xyz/Article/details/gtjidjlzvi.html

[U36] Py：定时任务
来源：http://dali.quarkkingdee.top/Article/details/gttzjeufha.html

schedule.every(10).minutes.do(job)
来源：http://dali.yvedp.cn/Article/details/gtamhmizfv.html

[U37] Py：读写 Excel
来源：http://dali.jqgufenzy.top/Article/details/gthqlhzksm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xylfe.cn/Article/details/gtiknpocjv.html

[U38] Py：获取脚本所在目录
来源：http://dali.xziqi.cn/Article/details/gtttrytbpi.html

Path(__file__).resolve().parent
来源：http://dali.hammf.cn/Article/details/gtnytbtrvh.html

[U39] Py：判断是否在交互环境
来源：http://dali.jianghu66.top/Article/details/gtkzddfulz.html

sys.stdout.isatty()
来源：http://dali.ydzc1.top/Article/details/gtbrluawsm.html

[U40] Py：打印到标准错误
来源：http://dali.chenzaomai.com/Article/details/gtkrkvlhjc.html

print("err", file=sys.stderr)
来源：http://dali.ivvv.top/Article/details/gtqqbpqxvh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenzaomai.com/Article/details/gtgxkfpsud.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.9152youxi.cn/Article/details/gtshgqgurq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhongyouzk.top/Article/details/gtfbwpourd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.redwolf501.top/Article/details/gtjrhzwskl.html

[U43] PHP：声明命名空间
来源：http://dali.meibo888.top/Article/details/gtlxdlclbi.html

namespace App\Http;
来源：http://dali.ppjwa.cn/Article/details/gtuyejjjuy.html

[U44] PHP：开启严格类型
来源：http://dali.hfpthk.cn/Article/details/gtymqsilmx.html

declare(strict_types=1);
来源：http://dali.xuanzx.com/Article/details/gtzvdmomza.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhiwuduotai.top/Article/details/gtmhshhxej.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcnofjwmz.html

[U46] PHP：可空类型
来源：http://dali.gotoacloud.top/Article/details/gtkdcszyeu.html

?string $name = null
来源：http://dali.wangshuangyany.cn/Article/details/gtqjoromdg.html

[U47] PHP：联合类型
来源：http://dali.tian-w.cn/Article/details/gtqzhdkbez.html

int|string $id
来源：http://dali.bjfxy.top/Article/details/gtklfexaje.html

[U48] PHP：纯枚举
来源：http://dali.jinqigufen.top/Article/details/gtmdqphkvt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.havefunace.top/Article/details/gtjvxkshst.html

[U49] PHP：只读属性
来源：http://dali.yongpay.top/Article/details/gtuqrnbxcw.html

public readonly string $name
来源：http://dali.jianghu66.top/Article/details/gtrfqdnkmd.html

[U50] PHP：构造器属性提升
来源：http://dali.chenlongwang.top/Article/details/gtarkxxqvm.html

public function __construct(private int $id) {}
来源：http://dali.ivvv.top/Article/details/gtyivmnptl.html

[U51] PHP：数组解构
来源：http://dali.chenlongwang.top/Article/details/gtyynkaojc.html

[$a, $b] = $arr;
来源：http://dali.daxiang520.top/Article/details/gtesajiioc.html

[U52] PHP：箭头函数
来源：http://dali.yonumen.top/Article/details/gtsbgxmakt.html

$double = fn($x) => $x * 2;
来源：http://dali.jqgfzy.top/Article/details/gtsdxuzdzm.html

[U53] PHP：空合并运算符
来源：http://dali.shuidangran.top/Article/details/gtepduxukf.html

$v = $a ?? $b ?? "default";
来源：http://dali.haohaochexian.top/Article/details/gtraorgblh.html

[U54] PHP：空安全调用
来源：http://dali.yuanzhike.top/Article/details/gtebaercvc.html

$obj?->method()
来源：http://dali.hnxiangtu.top/Article/details/gtdorjxzek.html

[U55] PHP：match 表达式
来源：http://dali.guannengcc.top/Article/details/gtqtphiymd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xuanzx.com/Article/details/gtogouwlek.html

[U56] PHP：命名参数
来源：http://dali.xinyue.icu/Article/details/gtwqfgakpd.html

f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtufolnvqw.html

[U57] PHP：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtgzlrlkys.html

"值: {$a}"
来源：http://dali.0kj1m.cn/Article/details/gtkciewtom.html

[U58] PHP：数组三件套
来源：http://dali.gzhubu.top/Article/details/gtmpqzlweg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.dashuyun.cn/Article/details/gtuvkptjti.html

[U59] PHP：自定义排序
来源：http://dali.quarkkingdee.top/Article/details/gtdgcjhqhw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.vqdsnc.cn/Article/details/gtwldbepwa.html

[U60] PHP：JSON 编解码
来源：http://dali.fengsongda.top/Article/details/gtolrbxgjw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.meibo888.top/Article/details/gtwhtgbywe.html

[U61] PHP：正则
来源：http://dali.hysaishi.cn/Article/details/gtiztpfqxd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtpovciwhb.html

[U62] PHP：日期对象
来源：http://dali.jlsjyb.cn/Article/details/gtdufyfdpf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.havefunace.top/Article/details/gtbwiovffq.html

[U63] PHP：文件读写
来源：http://dali.316326.xyz/Article/details/gtajdbtqcc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.chenlongwang.top/Article/details/gtqafeloln.html

[U64] PHP：目录遍历
来源：http://dali.cqqwz.cn/Article/details/gtepeyetrq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gotoacloud.top/Article/details/gtwthklwad.html

[U65] PHP：会话
来源：http://dali.pengpengdd.cyou/Article/details/gteavilbqq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj202588.top/Article/details/gtzgqbqdej.html

[U66] PHP：设置 Cookie
来源：http://dali.snrcjt.cn/Article/details/gtrslibhfu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jqgfzy.top/Article/details/gtsfmscpda.html

[U67] PHP：处理文件上传
来源：http://dali.ybcxt.top/Article/details/gtiqpedqip.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hysaishi.cn/Article/details/gtscpiuvlz.html

[U68] PHP：PDO 连接
来源：http://dali.haohaochexian.top/Article/details/gtwdallzqm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jqgfzy.top/Article/details/gtjybygrpm.html

[U69] PHP：PDO 预处理
来源：http://dali.chenlongwang.top/Article/details/gtfkvhqscl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.316326.xyz/Article/details/gtvodigenm.html

[U70] PHP：PDO 事务
来源：http://dali.cheryme.top/Article/details/gthwznvcsy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyezsybm.html

[U71] PHP：抛出异常
来源：http://dali.havefunace.top/Article/details/gtftbrmbpu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhongyouzk.top/Article/details/gttgiotyqq.html

[U72] PHP：写错误日志
来源：http://dali.xziqi.cn/Article/details/gtchxlparn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yangfankeji.com/Article/details/gtnoykvwxa.html

[U73] PHP：读取 ini 配置
来源：http://dali.9152youxi.cn/Article/details/gtwfmiiaay.html

parse_ini_file("config.ini", true)
来源：http://dali.hnqzz.top/Article/details/gtrzqeafyw.html

[U74] PHP：读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gtcixriisl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhoulong.xyz/Article/details/gttqrbswux.html

[U75] PHP：依赖注入
来源：http://dali.yangfankeji.com/Article/details/gthytwrrjo.html

composer require psr/container
来源：http://dali.ywan-chungtsiang.top/Article/details/gtceytplpn.html

[U76] PHP：简单路由
来源：http://dali.chenlongwang.top/Article/details/gtlynjvykz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhiwuduotai.top/Article/details/gtxmxxatjv.html


<!-- 参考信息 -->