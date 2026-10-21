代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtublvdmso.html

[S49] C++：写文件
来源：http://dali.daxiang520.top/Article/details/gtballmuln.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nwbrower.top/Article/details/gtqsraigts.html

[S50] C++：格式化数字
来源：http://dali.andypj.xyz/Article/details/gtpwynsdad.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtwsjcjzca.html

[S51] C++：显式类型转换
来源：http://dali.gzhubu.top/Article/details/gtasvndlhv.html

static_cast<double>(a) / b
来源：http://dali.ybcxt.top/Article/details/gtivwvhgzt.html

[S52] C++：const 与 noexcept
来源：http://dali.sweek.top/Article/details/gtuhikqxdc.html

int size() const noexcept { return n_; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcwjjmmny.html

[S53] C++：移动语义
来源：http://dali.jinqigufen.top/Article/details/gtrxzqetsp.html

std::vector<int> w = std::move(v);
来源：http://dali.cqqwz.cn/Article/details/gtlcfywbyf.html

[S54] C++：异常处理
来源：http://dali.jqgfzy.top/Article/details/gtalxssohi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.iojbl.cn/Article/details/gtsqewhgnt.html

[S55] C++：结构化绑定
来源：http://dali.yj20258888.top/Article/details/gtzxhgcpwq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigfzy.top/Article/details/gtoodkiyob.html

[S56] C++：optional
来源：http://dali.smart0.xyz/Article/details/gtjqhnzcfk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sysykeji.top/Article/details/gtnbwcxbvk.html

[S57] C++：编译期常量
来源：http://dali.chenjidiqi.icu/Article/details/gtirnapjbn.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtqwfinaia.html

[S58] C++：命名空间
来源：http://dali.0kj1m.cn/Article/details/gteahrikwk.html

namespace ns { int f() { return 1; } }
来源：http://dali.daxiang520.top/Article/details/gtczzmwbjg.html

[S59] C++：静态断言
来源：http://dali.ehwqpu.com/Article/details/gtbqwbchoz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhengqikj.top/Article/details/gtvwkglgnw.html

[S60] C++：遍历并删除元素
来源：http://dali.jianghu66.top/Article/details/gttssqeyjp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gtnvuyhgoa.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtomhrmzwv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.svipenyu.cn/Article/details/gtilprgkud.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtsgrvbjjk.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258.top/Article/details/gtoroxhnhr.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtegzfjppy.html

[T02] Kotlin：变量
来源：http://dali.nanxuanxn.top/Article/details/gthlegadps.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenjidiqi.icu/Article/details/gtuutagpdy.html

[T03] Kotlin：字符串模板
来源：http://dali.haohaochexian.top/Article/details/gtvganljfk.html

"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gtpackgahb.html

[T04] Kotlin：空安全
来源：http://dali.fengsongda.top/Article/details/gthzxgjhkm.html

val n: String? = null;  n?.length
来源：http://dali.jinqigufen.top/Article/details/gtxsxbqdjc.html

[T05] Kotlin：when 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtboxaebyz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jlsjyb.cn/Article/details/gtpnwroojh.html

[T06] Kotlin：集合映射
来源：http://dali.aizwys.cn/Article/details/gteqvirwzr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gotoacloud.top/Article/details/gtztmvtyho.html

[T07] Kotlin：集合过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyebyman.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258.top/Article/details/gtuaqszvsn.html

[T08] Kotlin：数据类
来源：http://dali.hnqzz.top/Article/details/gtxgngoyoq.html

data class User(val name: String, val age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gtdlhkwjas.html

[T09] Kotlin：扩展函数
来源：http://dali.havefunace.top/Article/details/gtmeuvbcuv.html

fun String.exclaim() = this + "!"
来源：http://dali.yuanzhike.top/Article/details/gtmnemjtrb.html

[T10] Kotlin：默认参数
来源：http://dali.cqqwz.cn/Article/details/gtlntnmbgo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cqqwz.cn/Article/details/gtybrcstkc.html

[T11] Kotlin：协程
来源：http://dali.sxryk.cn/Article/details/gtnedhvsec.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hongshengwenyu.top/Article/details/gtgynznrvm.html

[T12] Kotlin：解构声明
来源：http://dali.shangyingyoupin.top/Article/details/gtfqxxslgd.html

val (a, b) = Pair(1, 2)
来源：http://dali.mhx1999.top/Article/details/gtvaqsjajf.html

[T13] Kotlin：只读 Map
来源：http://dali.0kj1m.cn/Article/details/gtxfmdnhdo.html

val m = mapOf("a" to 1)
来源：http://dali.sweek.top/Article/details/gtcwtzngja.html

[T14] Kotlin：循环
来源：http://dali.hammf.cn/Article/details/gtvevthjnj.html

for (i in 1..10) println(i)
来源：http://dali.xziqi.cn/Article/details/gtxefgydha.html

[T15] Kotlin：接口
来源：http://dali.ivvv.top/Article/details/gtuemnrgsk.html

interface Shape { fun area(): Double }
来源：http://dali.cucudq.cn/Article/details/gtczfjfsdm.html

[T16] Swift：Hello World
来源：http://dali.svipenyu.cn/Article/details/gttkszwqsb.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gtvrsqqxxi.html

[T17] Swift：变量与常量
来源：http://dali.nanxuanxn.top/Article/details/gtpxlvtjeo.html

var a = 1;  let b = 2
来源：http://dali.nwbrower.top/Article/details/gtgtojlxss.html

[T18] Swift：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbrqgmoy.html

"值: \(b)"
来源：http://dali.redwolf501.top/Article/details/gtgdigzaoj.html

[T19] Swift：可选绑定
来源：http://dali.bjfxy.top/Article/details/gtavupvfbh.html

if let n = opt { print(n) }
来源：http://dali.guowangkeji.top/Article/details/gtzefanvag.html

[T20] Swift：数组操作
来源：http://dali.ydzc1.top/Article/details/gtmrtyjwwn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhoulong.xyz/Article/details/gtrrajqnck.html

[T21] Swift：遍历
来源：http://dali.vqdsnc.cn/Article/details/gtpayguvdx.html

for x in a { print(x) }
来源：http://dali.jiagoushi.top/Article/details/gtnepoyqje.html

[T22] Swift：字典
来源：http://dali.9152youxi.cn/Article/details/gtwzzgedno.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cqqwz.cn/Article/details/gtjllmgrtx.html

[T23] Swift：函数
来源：http://dali.chenjidiqi.icu/Article/details/gtozqrceom.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtropmbjnp.html

[T24] Swift：闭包
来源：http://dali.hysaishi.cn/Article/details/gtvanadufk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guannengcc.top/Article/details/gtbepwdkpl.html

[T25] Swift：结构体
来源：http://dali.shangyingyoupin.top/Article/details/gtzewbqzbg.html

struct P { var x: Int }
来源：http://dali.vqdsnc.cn/Article/details/gtjnxgpexe.html

[T26] Swift：类与重写
来源：http://dali.9152youxi.cn/Article/details/gtjpesspmr.html

class A: Base { override func f() {} }
来源：http://dali.gaohongyu789.top/Article/details/gtqtyhgyhz.html

[T27] Swift：错误处理
来源：http://dali.zycfv.cn/Article/details/gtqkjvlzal.html

do { try f() } catch { print(error) }
来源：http://dali.fzhhl.top/Article/details/gtcbhtnapr.html

[T28] Swift：枚举
来源：http://dali.ybcxt.top/Article/details/gtdnhqwkrv.html

enum Color { case red, green }
来源：http://dali.zhengqikj.top/Article/details/gtpwbtvrrl.html

[T29] Swift：guard 提前返回
来源：http://dali.jiagoushi.top/Article/details/gtpeqzynao.html

guard let x = opt else { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrozelhoi.html

[T30] Swift：协议
来源：http://dali.fzhhl.top/Article/details/gtisbajkvf.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxinkj.top/Article/details/gtqvysibia.html

[T31] Lua：Hello World
来源：http://dali.smart0.xyz/Article/details/gtopstiibo.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gtamcwjckp.html

[T32] Lua：局部变量
来源：http://dali.yuanzhike.top/Article/details/gtedeotktz.html

local a = 1
来源：http://dali.cucudq.cn/Article/details/gtfcosbalx.html

[T33] Lua：表（数组）
来源：http://dali.cashguo.top/Article/details/gtsgfyrrjj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbpuiuhb.html

[T34] Lua：遍历表
来源：http://dali.havefunace.top/Article/details/gtwehtnhea.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangshuangyany.cn/Article/details/gtasbvikyl.html

[T35] Lua：字典表
来源：http://dali.gzhubu.top/Article/details/gtpiezsnuu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuanzhike.top/Article/details/gtpqzxujtv.html

[T36] Lua：函数
来源：http://dali.jiagoushi.top/Article/details/gtlstwhzwm.html

function add(a, b) return a + b end
来源：http://dali.gaohongyu789.top/Article/details/gtqrcdiufe.html

[T37] Lua：字符串拼接
来源：http://dali.cucudq.cn/Article/details/gtneguwqrr.html

"a" .. "b"
来源：http://dali.jiagoushi.top/Article/details/gtecnehyrc.html

[T38] Lua：条件
来源：http://dali.hfpthk.cn/Article/details/gthdthkajv.html

if x > 0 then print("正") end
来源：http://dali.xuanzx.com/Article/details/gtbmpbynup.html

[T39] Lua：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtdmfwbxzk.html

string.find(s, "%d+")
来源：http://dali.yongpay.top/Article/details/gtnkkgteby.html

[T40] Lua：元表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvoukdiiv.html

setmetatable({}, { __index = base })
来源：http://dali.bjfxy.top/Article/details/gtjffcncyj.html

[T41] Perl：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtbaregeob.html

print "Hello\n";
来源：http://dali.yj20258.top/Article/details/gtlucdgdtl.html

[T42] Perl：变量类型
来源：http://dali.xylfe.cn/Article/details/gtjhywcron.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.havefunace.top/Article/details/gtzicfwdhn.html

[T43] Perl：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtslidcimr.html

"值: $a"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsjpavme.html

[T44] Perl：条件
来源：http://dali.hfpthk.cn/Article/details/gtqnjctquq.html

if ($a > 0) { print "正"; }
来源：http://dali.nanxinkj.top/Article/details/gtruznuetv.html

[T45] Perl：数组遍历
来源：http://dali.hywenlv.cn/Article/details/gthiavsnsv.html

for my $x (@arr) { print $x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxbhrxwh.html

[T46] Perl：哈希操作
来源：http://dali.aizwys.cn/Article/details/gtfzgbivdr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.feifeiyinyue.top/Article/details/gthgfhdtbv.html

[T47] Perl：正则捕获
来源：http://dali.chenzaomai.com/Article/details/gtpuyfzske.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nanxinkj.top/Article/details/gtfdlejvbd.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gttlndhvzy.html

$s =~ s/old/new/g;
来源：http://dali.daxiang520.top/Article/details/gtjabeiool.html

[T49] Perl：函数
来源：http://dali.yangfankeji.com/Article/details/gtmyeoxzex.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gtcykzeorp.html

[T50] Perl：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtbedwhder.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aibaodan.cn/Article/details/gtucsynacf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gzhubu.top/Article/details/gtwnmmzvep.html

[T51] Scala：Hello World
来源：http://dali.nwbrower.top/Article/details/gtlufharng.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtnynosfns.html

[T52] Scala：变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqilhbnxz.html

val a = 1;  var b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtdmuditlu.html

[T53] Scala：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtyomaxaoh.html

s"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gtwropntuw.html

[T54] Scala：集合映射
来源：http://dali.yj202588.top/Article/details/gtgpywgzlw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.pycfn.com/Article/details/gtedyzkgql.html

[T55] Scala：集合过滤
来源：http://dali.yongpay.top/Article/details/gtdstpthhc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinqigufen.top/Article/details/gtwdzfsimm.html

[T56] Scala：样例类
来源：http://dali.sxryk.cn/Article/details/gtpcvcqyfu.html

case class User(name: String, age: Int)
来源：http://dali.tian-w.cn/Article/details/gtcmqywjfj.html

[T57] Scala：模式匹配
来源：http://dali.zhengqikj.top/Article/details/gtvqdbpmws.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shzxlz.cn/Article/details/gtjufktdve.html

[T58] Scala：函数定义
来源：http://dali.xylfe.cn/Article/details/gtpzpkmdfr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sxryk.cn/Article/details/gtjjbtbnep.html

[T59] Scala：循环
来源：http://dali.ppjwa.cn/Article/details/gtszbtkbdr.html

for (i <- 1 to 10) println(i)
来源：http://dali.aizwys.cn/Article/details/gtkagtpfcs.html

[T60] Scala：折叠
来源：http://dali.ppjwa.cn/Article/details/gthaopcpuj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhengqikj.top/Article/details/gtrgkyrsyn.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtwgouxscl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.bjfxy.top/Article/details/gtmvqtfhvk.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtbczvqoia.html

[U01] Py：创建虚拟环境
来源：http://dali.wangdashe.top/Article/details/gtzbeeqhrb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hongshengwenyu.top/Article/details/gtuztmjtxq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ppjwa.cn/Article/details/gtqqbjydrq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zdqjudy.top/Article/details/gtizknzwjn.html

[U03] Py：加载 .env 配置
来源：http://dali.tanke756.top/Article/details/gtebasblch.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuanzx.com/Article/details/gtslhvsuob.html

[U04] Py：变量调试打印
来源：http://dali.gotoacloud.top/Article/details/gtuvlczjid.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj202588.top/Article/details/gteyvarmbf.html

[U05] Py：列表去重且保序
来源：http://dali.ppjwa.cn/Article/details/gtegugurqa.html

list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gtvkfdgher.html

[U06] Py：合并两个字典
来源：http://dali.redwolf501.top/Article/details/gtnwbysmny.html

{**a, **b}
来源：http://dali.tian-w.cn/Article/details/gthwmzdsxy.html

[U07] Py：反转字典键值
来源：http://dali.chenjidiqi.icu/Article/details/gtdlrqzsjl.html

{v: k for k, v in d.items()}
来源：http://dali.andypj.xyz/Article/details/gtubqxazqh.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjxxvrug.html

[y for x in nested for y in x]
来源：http://dali.birdmap.top/Article/details/gtjuwnvcrp.html

[U09] Py：字典取最大值的键
来源：http://dali.daxiang520.top/Article/details/gtonfecrfi.html

max(d, key=d.get)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqrarcgz.html

[U10] Py：按值排序字典
来源：http://dali.xylfe.cn/Article/details/gtpvusazyy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yueranfly.top/Article/details/gtwshprmks.html

[U11] Py：生成器表达式
来源：http://dali.0kj1m.cn/Article/details/gtheumhtpd.html

(x * 2 for x in arr)
来源：http://dali.316326.xyz/Article/details/gtqokeeabu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pycfn.com/Article/details/gtydhxruuu.html

Counter(arr).most_common(3)
来源：http://dali.nanxuanxn.top/Article/details/gtcbdphfpd.html

[U13] Py：固定长度队列
来源：http://dali.xuanzx.com/Article/details/gtvotdpavc.html

deque(maxlen=10)
来源：http://dali.sweek.top/Article/details/gteoyywpip.html

[U14] Py：分组收集到列表
来源：http://dali.cucudq.cn/Article/details/gtrednkogz.html

defaultdict(list)
来源：http://dali.feifeiyinyue.top/Article/details/gtdtamzxnw.html

[U15] Py：高精度计时
来源：http://dali.dashuyun.cn/Article/details/gtnkhftlhu.html

t = time.perf_counter()
来源：http://dali.redwolf501.top/Article/details/gtuywpwdps.html

[U16] Py：命令行参数解析
来源：http://dali.chenzaomai.com/Article/details/gtmmiibzwp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cucudq.cn/Article/details/gttpqeqqui.html

[U17] Py：初始化日志
来源：http://dali.sweek.top/Article/details/gthdmutnjx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ybcxt.top/Article/details/gtzstynmuz.html

[U18] Py：预编译正则
来源：http://dali.jyoumei.cn/Article/details/gtjccipcqa.html

pat = re.compile(r"\d+")
来源：http://dali.xuanzx.com/Article/details/gtoxybkexw.html

[U19] Py：正则替换带回调
来源：http://dali.svipenyu.cn/Article/details/gtklqozdqb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.quarkkingdee.top/Article/details/gtoygooelu.html

[U20] Py：缓存函数结果
来源：http://dali.jqgfzy.top/Article/details/gtonchoqdt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ydzc1.top/Article/details/gtddgfarhs.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenjidiqi.icu/Article/details/gtgsitguxs.html

@contextlib.contextmanager
来源：http://dali.yuxming.cn/Article/details/gtsfexzviu.html

[U22] Py：矩阵转置
来源：http://dali.jlsjyb.cn/Article/details/gtkvnofwsl.html

list(zip(*m))
来源：http://dali.chenjidiqi.icu/Article/details/gtmtkpbnri.html

[U23] Py：分块读取大文件
来源：http://dali.sxryk.cn/Article/details/gtrcrpuhmm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinqigufen.top/Article/details/gttluirsgc.html

[U24] Py：路径操作
来源：http://dali.jiagoushi.top/Article/details/gtsusqbnlh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gtskofnsvv.html

[U25] Py：CSV 按字典读
来源：http://dali.chenlongwang.top/Article/details/gtrkyrgtqw.html

csv.DictReader(f)
来源：http://dali.jiagoushi.top/Article/details/gtzefiiftz.html

[U26] Py：并发下载
来源：http://dali.quarkkingdee.top/Article/details/gthdkbvgot.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hnqzz.top/Article/details/gtbmmekctd.html

[U27] Py：异步 HTTP
来源：http://dali.hfpthk.cn/Article/details/gtmozoetkr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhongyouzk.top/Article/details/gtuilchofq.html

[U28] Py：类型别名
来源：http://dali.nwbrower.top/Article/details/gtbeqcdgjn.html

UserId = int
来源：http://dali.yonumen.top/Article/details/gtrgjhvqba.html

[U29] Py：属性校验
来源：http://dali.hysaishi.cn/Article/details/gtjoyomvxw.html

@property 与 @x.setter 配合
来源：http://dali.sufxvd.cn/Article/details/gtxcrbehlj.html

[U30] Py：数据类
来源：http://dali.zhongyouzk.top/Article/details/gtphypkxil.html

@dataclass(slots=True)
来源：http://dali.sysykeji.top/Article/details/gtutktivkv.html

[U31] Py：单测
来源：http://dali.zhixingplan.top/Article/details/gtlugocqbm.html

python -m pytest -q
来源：http://dali.zhixingplan.top/Article/details/gtktccofmc.html

[U32] Py：代码格式化
来源：http://dali.kuanghao11.cn/Article/details/gtjpqjmswb.html

ruff format . && ruff check --fix .
来源：http://dali.yj20258888.top/Article/details/gtrbthogxh.html

[U33] Py：打包发布
来源：http://dali.nanxinkj.top/Article/details/gtdsrkxegb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.wangdashe.top/Article/details/gtklgrwxmo.html

[U34] Py：判断编码
来源：http://dali.xylfe.cn/Article/details/gtsyrmyshd.html

chardet.detect(raw)
来源：http://dali.daxiang520.top/Article/details/gthvvbyfwq.html

[U35] Py：发送邮件
来源：http://dali.hysaishi.cn/Article/details/gtpiimfhkv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yueranfly.top/Article/details/gtcqtmjhqt.html

[U36] Py：定时任务
来源：http://dali.sysykeji.top/Article/details/gtjtndohfx.html

schedule.every(10).minutes.do(job)
来源：http://dali.shuidangran.top/Article/details/gtdwwbbsfg.html

[U37] Py：读写 Excel
来源：http://dali.aibaodan.cn/Article/details/gtvrsttysl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.aibaodan.cn/Article/details/gtvesmdvkx.html

[U38] Py：获取脚本所在目录
来源：http://dali.xuetiantiany.cn/Article/details/gtnnsvqfmh.html

Path(__file__).resolve().parent
来源：http://dali.yj20258888.top/Article/details/gtzkdbspkl.html

[U39] Py：判断是否在交互环境
来源：http://dali.jyoumei.cn/Article/details/gttyvgdati.html

sys.stdout.isatty()
来源：http://dali.sysykeji.top/Article/details/gtlrzqsynu.html

[U40] Py：打印到标准错误
来源：http://dali.birdmap.top/Article/details/gtzgscqrae.html

print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gtpchjijtr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hnqzz.top/Article/details/gtzzhsdbfl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yuanzhike.top/Article/details/gtpqzqxcxs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gogol.net.cn/Article/details/gtusuimozm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cucudq.cn/Article/details/gtpdchabmq.html

[U43] PHP：声明命名空间
来源：http://dali.0kj1m.cn/Article/details/gtnmqlesxx.html

namespace App\Http;
来源：http://dali.hongshengwenyu.top/Article/details/gtbztvfeii.html

[U44] PHP：开启严格类型
来源：http://dali.zhoulong.xyz/Article/details/gtlbscikik.html

declare(strict_types=1);
来源：http://dali.cheryme.top/Article/details/gtlffrpois.html

[U45] PHP：类型声明与返回类型
来源：http://dali.wangshuangyany.cn/Article/details/gtuigltsek.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtdcxngcai.html

[U46] PHP：可空类型
来源：http://dali.hywenlv.cn/Article/details/gtmqregijw.html

?string $name = null
来源：http://dali.zhongyouzk.top/Article/details/gtkhuyckgu.html

[U47] PHP：联合类型
来源：http://dali.jqgfzy.top/Article/details/gtkdnrzrxp.html

int|string $id
来源：http://dali.jinghuilouyu.cn/Article/details/gtristdgrw.html

[U48] PHP：纯枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttocuorzo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zycfv.cn/Article/details/gtssxykkno.html

[U49] PHP：只读属性
来源：http://dali.fengsongda.top/Article/details/gtuokovggj.html

public readonly string $name
来源：http://dali.kuanghao11.cn/Article/details/gtmiuvkncy.html

[U50] PHP：构造器属性提升
来源：http://dali.ybcxt.top/Article/details/gtsfjzmcvm.html

public function __construct(private int $id) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtgyspditx.html

[U51] PHP：数组解构
来源：http://dali.yanxiufei.cn/Article/details/gtxozaxfyk.html

[$a, $b] = $arr;
来源：http://dali.tianlin.xyz/Article/details/gtfbaixvkp.html

[U52] PHP：箭头函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvohsyxk.html

$double = fn($x) => $x * 2;
来源：http://dali.svipenyu.cn/Article/details/gthrblruef.html

[U53] PHP：空合并运算符
来源：http://dali.shuidangran.top/Article/details/gtqhffqeox.html

$v = $a ?? $b ?? "default";
来源：http://dali.quarkkingdee.top/Article/details/gtzoxiehsh.html

[U54] PHP：空安全调用
来源：http://dali.aizwys.cn/Article/details/gtskqbkunu.html

$obj?->method()
来源：http://dali.redwolf501.top/Article/details/gtfnugkkwr.html

[U55] PHP：match 表达式
来源：http://dali.daxiang520.top/Article/details/gtxotyjldq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ivvv.top/Article/details/gtklufjxdv.html

[U56] PHP：命名参数
来源：http://dali.zhixingplan.top/Article/details/gtcqnvvdpa.html

f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtybzallzl.html

[U57] PHP：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavlldrac.html

"值: {$a}"
来源：http://dali.ivvv.top/Article/details/gtrecztdvb.html

[U58] PHP：数组三件套
来源：http://dali.0kj1m.cn/Article/details/gtgiuklwra.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.dashuyun.cn/Article/details/gtnmlnhwff.html

[U59] PHP：自定义排序
来源：http://dali.xylfe.cn/Article/details/gtphqwfihx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gtcbdelgwf.html

[U60] PHP：JSON 编解码
来源：http://dali.yj202588.top/Article/details/gtsuudxgpp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ivvv.top/Article/details/gtvrgfaxsk.html

[U61] PHP：正则
来源：http://dali.yongpay.top/Article/details/gtnxtyaebq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gtpifpynyq.html

[U62] PHP：日期对象
来源：http://dali.yj20258888.top/Article/details/gtqmcmyozd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yanxiufei.cn/Article/details/gtfoerchkb.html

[U63] PHP：文件读写
来源：http://dali.yj20258888.top/Article/details/gtcmwkqqpo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepekipnm.html

[U64] PHP：目录遍历
来源：http://dali.ivvv.top/Article/details/gtywqyyeqp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.mhx1999.top/Article/details/gtaqpbwhlj.html

[U65] PHP：会话
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzishgpnf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtjlgiaqpw.html

[U66] PHP：设置 Cookie
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzuuvsjp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtglnznstf.html

[U67] PHP：处理文件上传
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbszessrq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gaohongyu789.top/Article/details/gtklbcbyrk.html

[U68] PHP：PDO 连接
来源：http://dali.dashuyun.cn/Article/details/gtgdjpfzze.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hongshengwenyu.top/Article/details/gtvmlkgwbn.html

[U69] PHP：PDO 预处理
来源：http://dali.gotoacloud.top/Article/details/gtankatpge.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sufxvd.cn/Article/details/gttrzuoggy.html

[U70] PHP：PDO 事务
来源：http://dali.smart0.xyz/Article/details/gthbfkatud.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hongshengwenyu.top/Article/details/gtadllswof.html

[U71] PHP：抛出异常
来源：http://dali.xuanzx.com/Article/details/gtulsjbulh.html

throw new RuntimeException("失败", 500);
来源：http://dali.hywenlv.cn/Article/details/gtgfjhxjvg.html

[U72] PHP：写错误日志
来源：http://dali.jinqigufen.top/Article/details/gtkaxyytcq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenlongwang.top/Article/details/gttiaywmex.html

[U73] PHP：读取 ini 配置
来源：http://dali.gzhubu.top/Article/details/gtfrwdrkxk.html

parse_ini_file("config.ini", true)
来源：http://dali.nanxuanxn.top/Article/details/gtzxeablgf.html

[U74] PHP：读取环境变量
来源：http://dali.nwbrower.top/Article/details/gtvpitzygi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.snrcjt.cn/Article/details/gtdlxoksos.html


<!-- 参考信息 -->