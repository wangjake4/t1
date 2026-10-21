代发 wailian999

[S45] C++：lambda
来源：http://dali.316326.xyz/Article/details/gtoucezjey.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhiwuduotai.top/Article/details/gtnpfzfhhw.html

[S46] C++：函数模板
来源：http://dali.cucudq.cn/Article/details/gtxitbhhkl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtfmxieuaf.html

[S47] C++：结构化绑定遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbtuieuu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cqqwz.cn/Article/details/gtdjvcmndt.html

[S48] C++：逐行读文件
来源：http://dali.yonumen.top/Article/details/gtsyyttnza.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenjidiqi.icu/Article/details/gtumjtklnv.html

while (std::getline(in, line)) { }
来源：http://dali.birdmap.top/Article/details/gtlcnrixkn.html

[S49] C++：写文件
来源：http://dali.yangfankeji.com/Article/details/gtakualqys.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsriimbe.html

[S50] C++：格式化数字
来源：http://dali.jyoumei.cn/Article/details/gtuowtgvmi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtozhlobgm.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwesoawt.html

static_cast<double>(a) / b
来源：http://dali.jyoumei.cn/Article/details/gtpmqxlkhs.html

[S52] C++：const 与 noexcept
来源：http://dali.cqqwz.cn/Article/details/gtvoaiyggt.html

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gtclyqqlvl.html

[S53] C++：移动语义
来源：http://dali.c1oappe.top/Article/details/gtvrkeuawy.html

std::vector<int> w = std::move(v);
来源：http://dali.cqqwz.cn/Article/details/gtudevuiwx.html

[S54] C++：异常处理
来源：http://dali.xylfe.cn/Article/details/gttjeqfkqa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sufxvd.cn/Article/details/gtqfkdlwnd.html

[S55] C++：结构化绑定
来源：http://dali.xuetiantiany.cn/Article/details/gtwpkcatov.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shuidangran.top/Article/details/gtudmkumcp.html

[S56] C++：optional
来源：http://dali.zhoulong.xyz/Article/details/gtsybnyxmb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.9152youxi.cn/Article/details/gtcnmmafyi.html

[S57] C++：编译期常量
来源：http://dali.hongshengwenyu.top/Article/details/gtuwqqwwzt.html

constexpr int N = 10;
来源：http://dali.gogol.net.cn/Article/details/gtzlcvxjxa.html

[S58] C++：命名空间
来源：http://dali.yonumen.top/Article/details/gttpxlbkuu.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgufenzy.top/Article/details/gtbebajayi.html

[S59] C++：静态断言
来源：http://dali.xziqi.cn/Article/details/gtyuzixkfc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shuidangran.top/Article/details/gtcibtknzi.html

[S60] C++：遍历并删除元素
来源：http://dali.gogol.net.cn/Article/details/gtlpdlultx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gtvenhaluk.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtykikgvoc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tanke756.top/Article/details/gtibsdzzyu.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtotpccuva.html

[T01] Kotlin：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtbencvvme.html

println("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtwiynmega.html

[T02] Kotlin：变量
来源：http://dali.daria6918.cn/Article/details/gtxutzpxla.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sweek.top/Article/details/gtlqokujfo.html

[T03] Kotlin：字符串模板
来源：http://dali.yanxiufei.cn/Article/details/gtjrjphcdr.html

"值: $b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrzjyawg.html

[T04] Kotlin：空安全
来源：http://dali.guowangkeji.top/Article/details/gtddccihwh.html

val n: String? = null;  n?.length
来源：http://dali.shangyingyoupin.top/Article/details/gthmpggdve.html

[T05] Kotlin：when 表达式
来源：http://dali.cucudq.cn/Article/details/gtvulxtysd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jiagoushi.top/Article/details/gtplwqhgnd.html

[T06] Kotlin：集合映射
来源：http://dali.hnqzz.top/Article/details/gtmzyqxocg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxrwclba.html

[T07] Kotlin：集合过滤
来源：http://dali.iojbl.cn/Article/details/gtlrgebywv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtedcbpwir.html

[T08] Kotlin：数据类
来源：http://dali.yueranfly.top/Article/details/gtjgyrzarc.html

data class User(val name: String, val age: Int)
来源：http://dali.cdnleiting.top/Article/details/gtcooslacf.html

[T09] Kotlin：扩展函数
来源：http://dali.hammf.cn/Article/details/gtimktkfyv.html

fun String.exclaim() = this + "!"
来源：http://dali.ybcxt.top/Article/details/gtayjnhorg.html

[T10] Kotlin：默认参数
来源：http://dali.daxiang520.top/Article/details/gthrisefnp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.bjfxy.top/Article/details/gtolpcdqfn.html

[T11] Kotlin：协程
来源：http://dali.ybcxt.top/Article/details/gtlxjuhxmb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ydzc1.top/Article/details/gtxmjrtsaw.html

[T12] Kotlin：解构声明
来源：http://dali.tianlin.xyz/Article/details/gtxfvldsdp.html

val (a, b) = Pair(1, 2)
来源：http://dali.tanke756.top/Article/details/gtmmkmbryr.html

[T13] Kotlin：只读 Map
来源：http://dali.wangshuangyany.cn/Article/details/gtdkenkjuh.html

val m = mapOf("a" to 1)
来源：http://dali.yueranfly.top/Article/details/gtpfbqlaee.html

[T14] Kotlin：循环
来源：http://dali.yanxiufei.cn/Article/details/gtlkcmbtae.html

for (i in 1..10) println(i)
来源：http://dali.yonumen.top/Article/details/gtxggqcdtz.html

[T15] Kotlin：接口
来源：http://dali.wangdashe.top/Article/details/gtygmvytzh.html

interface Shape { fun area(): Double }
来源：http://dali.sxryk.cn/Article/details/gtaaaccsev.html

[T16] Swift：Hello World
来源：http://dali.yuanzhike.top/Article/details/gthgzpsccy.html

print("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtpbpjbapq.html

[T17] Swift：变量与常量
来源：http://dali.wangdashe.top/Article/details/gtihqgogsf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtwimnhihl.html

[T18] Swift：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gtuxmbiied.html

"值: \(b)"
来源：http://dali.jianghu66.top/Article/details/gtduoiqhyg.html

[T19] Swift：可选绑定
来源：http://dali.9152youxi.cn/Article/details/gtzyhdgboh.html

if let n = opt { print(n) }
来源：http://dali.nanxinkj.top/Article/details/gtxzckwstx.html

[T20] Swift：数组操作
来源：http://dali.svipenyu.cn/Article/details/gtrqcsqefk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jianghu66.top/Article/details/gtdhqadvks.html

[T21] Swift：遍历
来源：http://dali.birdmap.top/Article/details/gtjazygpvp.html

for x in a { print(x) }
来源：http://dali.yanxiufei.cn/Article/details/gtboqonpqb.html

[T22] Swift：字典
来源：http://dali.iojbl.cn/Article/details/gthkbnuflb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nanxinkj.top/Article/details/gtjesfwuxy.html

[T23] Swift：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtskkkntck.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtylzceisc.html

[T24] Swift：闭包
来源：http://dali.shzxlz.cn/Article/details/gtbpqnbfqw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.meibo888.top/Article/details/gtcjquqmdo.html

[T25] Swift：结构体
来源：http://dali.yj202588.top/Article/details/gtrtwkvjhh.html

struct P { var x: Int }
来源：http://dali.daria6918.cn/Article/details/gturuhdelc.html

[T26] Swift：类与重写
来源：http://dali.ppjwa.cn/Article/details/gtjznuqibl.html

class A: Base { override func f() {} }
来源：http://dali.shzxlz.cn/Article/details/gtkanhiuvy.html

[T27] Swift：错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gtbnekqpys.html

do { try f() } catch { print(error) }
来源：http://dali.xziqi.cn/Article/details/gtnrisvqsv.html

[T28] Swift：枚举
来源：http://dali.xuanzx.com/Article/details/gtlwvzevtg.html

enum Color { case red, green }
来源：http://dali.quarkkingdee.top/Article/details/gtnikjdwym.html

[T29] Swift：guard 提前返回
来源：http://dali.ybcxt.top/Article/details/gtkfyyuooj.html

guard let x = opt else { return }
来源：http://dali.jlsjyb.cn/Article/details/gtiznukugd.html

[T30] Swift：协议
来源：http://dali.kuanghao11.cn/Article/details/gtrcnlczvh.html

protocol Shape { func area() -> Double }
来源：http://dali.mhx1999.top/Article/details/gtfazwqhmd.html

[T31] Lua：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwekggbv.html

print("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gthniqvjpo.html

[T32] Lua：局部变量
来源：http://dali.yonumen.top/Article/details/gthctyqcnn.html

local a = 1
来源：http://dali.xziqi.cn/Article/details/gtdmvmgicf.html

[T33] Lua：表（数组）
来源：http://dali.ppjwa.cn/Article/details/gtfqhakekj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jyoumei.cn/Article/details/gtummtdtmd.html

[T34] Lua：遍历表
来源：http://dali.meibo888.top/Article/details/gtjukdgjdp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.meibo888.top/Article/details/gtrgerjxkp.html

[T35] Lua：字典表
来源：http://dali.daria6918.cn/Article/details/gtpbpezlgp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtkzugtwig.html

[T36] Lua：函数
来源：http://dali.hammf.cn/Article/details/gtgemfdnbp.html

function add(a, b) return a + b end
来源：http://dali.pycfn.com/Article/details/gtfzggekix.html

[T37] Lua：字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gtjfcejgzj.html

"a" .. "b"
来源：http://dali.cqqwz.cn/Article/details/gtxbkprcad.html

[T38] Lua：条件
来源：http://dali.cqqwz.cn/Article/details/gtsfmlarwf.html

if x > 0 then print("正") end
来源：http://dali.xylfe.cn/Article/details/gtlzfszews.html

[T39] Lua：模式匹配
来源：http://dali.hnqzz.top/Article/details/gtlmfrsdcq.html

string.find(s, "%d+")
来源：http://dali.haohaochexian.top/Article/details/gtltefzbqa.html

[T40] Lua：元表
来源：http://dali.jyoumei.cn/Article/details/gtcxrdkkhx.html

setmetatable({}, { __index = base })
来源：http://dali.meibo888.top/Article/details/gtthoyqcch.html

[T41] Perl：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtvoyyhbdv.html

print "Hello\n";
来源：http://dali.chenlongwang.top/Article/details/gtaylxanoh.html

[T42] Perl：变量类型
来源：http://dali.aizwys.cn/Article/details/gterzkvyjj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xziqi.cn/Article/details/gtvvgdjjly.html

[T43] Perl：字符串插值
来源：http://dali.yongpay.top/Article/details/gtkmpyvzfu.html

"值: $a"
来源：http://dali.hnxiangtu.top/Article/details/gtekkmcfac.html

[T44] Perl：条件
来源：http://dali.quarkkingdee.top/Article/details/gtaacnutlv.html

if ($a > 0) { print "正"; }
来源：http://dali.tanke756.top/Article/details/gtfjrercmy.html

[T45] Perl：数组遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtjgqfuqie.html

for my $x (@arr) { print $x; }
来源：http://dali.yueranfly.top/Article/details/gtmvgamjjc.html

[T46] Perl：哈希操作
来源：http://dali.xuanzx.com/Article/details/gtikhsaxmi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shangyingyoupin.top/Article/details/gthcniiaje.html

[T47] Perl：正则捕获
来源：http://dali.jqgfzy.top/Article/details/gtjvhxtldo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tianlin.xyz/Article/details/gtdtuviepb.html

[T48] Perl：正则替换
来源：http://dali.sweek.top/Article/details/gtygrirvbd.html

$s =~ s/old/new/g;
来源：http://dali.hongshengwenyu.top/Article/details/gtsuegbtyp.html

[T49] Perl：函数
来源：http://dali.mhx1999.top/Article/details/gtzodcvhms.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gtnunrcqyr.html

[T50] Perl：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gthjittdkk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hnxiangtu.top/Article/details/gtntwpyvng.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj202588.top/Article/details/gtkbbrnbrz.html

[T51] Scala：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtdpyzngoi.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gtrurirhlp.html

[T52] Scala：变量
来源：http://dali.xuetiantiany.cn/Article/details/gttcrxpljm.html

val a = 1;  var b = 2
来源：http://dali.ivvv.top/Article/details/gtrgltszmx.html

[T53] Scala：字符串插值
来源：http://dali.yongpay.top/Article/details/gtqpbxedpd.html

s"值: $b"
来源：http://dali.hammf.cn/Article/details/gtlobzzrjh.html

[T54] Scala：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gtlzovpudw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gzhubu.top/Article/details/gtuzqxlxca.html

[T55] Scala：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gtslqufips.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hnqzz.top/Article/details/gtyprqcryj.html

[T56] Scala：样例类
来源：http://dali.yangfankeji.com/Article/details/gtbayoexer.html

case class User(name: String, age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gtdcbuflmz.html

[T57] Scala：模式匹配
来源：http://dali.redwolf501.top/Article/details/gtafrtrqzn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenlongwang.top/Article/details/gtcmvzwcix.html

[T58] Scala：函数定义
来源：http://dali.zhoulong.xyz/Article/details/gtyhnbgryg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sweek.top/Article/details/gtkbrcavlp.html

[T59] Scala：循环
来源：http://dali.yanxiufei.cn/Article/details/gtgrhqtuyz.html

for (i <- 1 to 10) println(i)
来源：http://dali.jqgufenzy.top/Article/details/gtyduhbzmd.html

[T60] Scala：折叠
来源：http://dali.ydzc1.top/Article/details/gtywgkyvsg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxuanxn.top/Article/details/gtljkfyttx.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtmewqpcea.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gzhubu.top/Article/details/gtxqhaquri.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtlgrttrpx.html

[U01] Py：创建虚拟环境
来源：http://dali.yvedp.cn/Article/details/gtohfkkssq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubmhkuqz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.aizwys.cn/Article/details/gtuooktbxk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hammf.cn/Article/details/gttjptzawo.html

[U03] Py：加载 .env 配置
来源：http://dali.hywenlv.cn/Article/details/gtxxqfkwyp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.guannengcc.top/Article/details/gtfefzqkln.html

[U04] Py：变量调试打印
来源：http://dali.0kj1m.cn/Article/details/gtdqtmzuiv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.fzhhl.top/Article/details/gtjvnaiheo.html

[U05] Py：列表去重且保序
来源：http://dali.xylfe.cn/Article/details/gtekfarlct.html

list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtllcgkotn.html

[U06] Py：合并两个字典
来源：http://dali.gogol.net.cn/Article/details/gtwejqnohw.html

{**a, **b}
来源：http://dali.yuanzhike.top/Article/details/gtefmgmbff.html

[U07] Py：反转字典键值
来源：http://dali.zhoulong.xyz/Article/details/gtiuxtlnam.html

{v: k for k, v in d.items()}
来源：http://dali.hysaishi.cn/Article/details/gtskbcmuod.html

[U08] Py：展平二维列表
来源：http://dali.yonumen.top/Article/details/gtspamzjmd.html

[y for x in nested for y in x]
来源：http://dali.yuanzhike.top/Article/details/gtuofrdqpq.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258888.top/Article/details/gtacngefld.html

max(d, key=d.get)
来源：http://dali.aizwys.cn/Article/details/gthwziqbss.html

[U10] Py：按值排序字典
来源：http://dali.nanxuanxn.top/Article/details/gtrcdevxut.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pycfn.com/Article/details/gtusaiatqi.html

[U11] Py：生成器表达式
来源：http://dali.zdqjudy.top/Article/details/gthprfoedy.html

(x * 2 for x in arr)
来源：http://dali.nwbrower.top/Article/details/gtqftgsllk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.chenjidiqi.icu/Article/details/gtsqhhrytm.html

Counter(arr).most_common(3)
来源：http://dali.zhoulong.xyz/Article/details/gtyduiqgob.html

[U13] Py：固定长度队列
来源：http://dali.cqqwz.cn/Article/details/gtyerhwkky.html

deque(maxlen=10)
来源：http://dali.iojbl.cn/Article/details/gtchnjdtan.html

[U14] Py：分组收集到列表
来源：http://dali.tanke756.top/Article/details/gtrkaeqtwr.html

defaultdict(list)
来源：http://dali.tanke756.top/Article/details/gtahikwzti.html

[U15] Py：高精度计时
来源：http://dali.dashuyun.cn/Article/details/gtkbvfeynj.html

t = time.perf_counter()
来源：http://dali.daxiang520.top/Article/details/gtjlqhugxh.html

[U16] Py：命令行参数解析
来源：http://dali.jianghu66.top/Article/details/gtrqubswqx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aizwys.cn/Article/details/gtpasgigjr.html

[U17] Py：初始化日志
来源：http://dali.zhoulong.xyz/Article/details/gtokmiqdpu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jlsjyb.cn/Article/details/gtlqlkxqml.html

[U18] Py：预编译正则
来源：http://dali.guowangkeji.top/Article/details/gttbzwiqdl.html

pat = re.compile(r"\d+")
来源：http://dali.hfpthk.cn/Article/details/gtsefuvtat.html

[U19] Py：正则替换带回调
来源：http://dali.redwolf501.top/Article/details/gtqglpjybt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gotoacloud.top/Article/details/gtzqewewzd.html

[U20] Py：缓存函数结果
来源：http://dali.gzhubu.top/Article/details/gtobztrfuf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xziqi.cn/Article/details/gtaylxvkdp.html

[U21] Py：自定义上下文管理器
来源：http://dali.sufxvd.cn/Article/details/gtgchcfsln.html

@contextlib.contextmanager
来源：http://dali.gaohongyu789.top/Article/details/gtelmchphu.html

[U22] Py：矩阵转置
来源：http://dali.sweek.top/Article/details/gtxiylwdwm.html

list(zip(*m))
来源：http://dali.gotoacloud.top/Article/details/gtvthsvbrv.html

[U23] Py：分块读取大文件
来源：http://dali.jyoumei.cn/Article/details/gtexgcplpm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yuanzhike.top/Article/details/gtmdagncsb.html

[U24] Py：路径操作
来源：http://dali.cqqwz.cn/Article/details/gtvoceuumu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.mhx1999.top/Article/details/gtjiwwpbrh.html

[U25] Py：CSV 按字典读
来源：http://dali.ivvv.top/Article/details/gtoqpzzowa.html

csv.DictReader(f)
来源：http://dali.hfpthk.cn/Article/details/gtbvxwwdtj.html

[U26] Py：并发下载
来源：http://dali.quarkkingdee.top/Article/details/gtaackqxrj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhixingplan.top/Article/details/gthmgqttdb.html

[U27] Py：异步 HTTP
来源：http://dali.andypj.xyz/Article/details/gtoswmtbxv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.9152youxi.cn/Article/details/gttkalkkjc.html

[U28] Py：类型别名
来源：http://dali.gaohongyu789.top/Article/details/gtsomlpmoc.html

UserId = int
来源：http://dali.cheryme.top/Article/details/gtylukpnoh.html

[U29] Py：属性校验
来源：http://dali.havefunace.top/Article/details/gtccaufmmn.html

@property 与 @x.setter 配合
来源：http://dali.jiagoushi.top/Article/details/gtryyawmbx.html

[U30] Py：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gtezzlurcz.html

@dataclass(slots=True)
来源：http://dali.fzhhl.top/Article/details/gtvhwfenol.html

[U31] Py：单测
来源：http://dali.cashguo.top/Article/details/gtjdqbefnt.html

python -m pytest -q
来源：http://dali.wangdashe.top/Article/details/gtyhztfqto.html

[U32] Py：代码格式化
来源：http://dali.guannengcc.top/Article/details/gtidcldrdk.html

ruff format . && ruff check --fix .
来源：http://dali.jyoumei.cn/Article/details/gtnucyygxw.html

[U33] Py：打包发布
来源：http://dali.jianghu66.top/Article/details/gttpqzshbb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gaohongyu789.top/Article/details/gteuyzehjf.html

[U34] Py：判断编码
来源：http://dali.guannengcc.top/Article/details/gtcqbbdnka.html

chardet.detect(raw)
来源：http://dali.gogol.net.cn/Article/details/gtxbshzrpy.html

[U35] Py：发送邮件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuueftsna.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.wangdashe.top/Article/details/gtqqynhfnx.html

[U36] Py：定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuiewxwcu.html

schedule.every(10).minutes.do(job)
来源：http://dali.havefunace.top/Article/details/gtkydlzvli.html

[U37] Py：读写 Excel
来源：http://dali.hammf.cn/Article/details/gtaykalrcl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj20258888.top/Article/details/gtzutjrtpd.html

[U38] Py：获取脚本所在目录
来源：http://dali.ivvv.top/Article/details/gtvoueqqqu.html

Path(__file__).resolve().parent
来源：http://dali.kuanghao11.cn/Article/details/gtjzdkecqt.html

[U39] Py：判断是否在交互环境
来源：http://dali.andypj.xyz/Article/details/gtjglixtge.html

sys.stdout.isatty()
来源：http://dali.yanxiufei.cn/Article/details/gtortktpdr.html

[U40] Py：打印到标准错误
来源：http://dali.zhongyouzk.top/Article/details/gtspqvdcvs.html

print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gtwphjprrg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gaohongyu789.top/Article/details/gtankpcyky.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.feifeiyinyue.top/Article/details/gtszdajneu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.tian-w.cn/Article/details/gtvwuuepqy.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hysaishi.cn/Article/details/gtpxxommfh.html

[U43] PHP：声明命名空间
来源：http://dali.hywenlv.cn/Article/details/gtkpthfjap.html

namespace App\Http;
来源：http://dali.yanxiufei.cn/Article/details/gtyrqhobvp.html

[U44] PHP：开启严格类型
来源：http://dali.hfpthk.cn/Article/details/gtrkqqnhef.html

declare(strict_types=1);
来源：http://dali.ydzc1.top/Article/details/gtewzrvujk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.redwolf501.top/Article/details/gtcxeprzes.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtwqwkwksw.html

[U46] PHP：可空类型
来源：http://dali.9152youxi.cn/Article/details/gtzcytarsr.html

?string $name = null
来源：http://dali.ydzc1.top/Article/details/gtoxlfdzck.html

[U47] PHP：联合类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwxdroyg.html

int|string $id
来源：http://dali.wangdashe.top/Article/details/gtdywnvyog.html

[U48] PHP：纯枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtotcofglu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwelzalan.html

[U49] PHP：只读属性
来源：http://dali.daria6918.cn/Article/details/gtvfzkwgsg.html

public readonly string $name
来源：http://dali.meibo888.top/Article/details/gtyiqtrwdf.html

[U50] PHP：构造器属性提升
来源：http://dali.yj20258.top/Article/details/gtoikmqemi.html

public function __construct(private int $id) {}
来源：http://dali.zhengqikj.top/Article/details/gtoercltqn.html

[U51] PHP：数组解构
来源：http://dali.jqgufenzy.top/Article/details/gtivphtgdi.html

[$a, $b] = $arr;
来源：http://dali.sxryk.cn/Article/details/gtfyumpdcb.html

[U52] PHP：箭头函数
来源：http://dali.nanxinkj.top/Article/details/gtdkhagdbc.html

$double = fn($x) => $x * 2;
来源：http://dali.jqgufenzy.top/Article/details/gtjqisgsga.html

[U53] PHP：空合并运算符
来源：http://dali.daxiang520.top/Article/details/gtfhawfchc.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gtapkilplp.html

[U54] PHP：空安全调用
来源：http://dali.gogol.net.cn/Article/details/gtiovqghku.html

$obj?->method()
来源：http://dali.bjfxy.top/Article/details/gturexhdit.html

[U55] PHP：match 表达式
来源：http://dali.zycfv.cn/Article/details/gttthonxir.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.vqdsnc.cn/Article/details/gtgegkhiqo.html

[U56] PHP：命名参数
来源：http://dali.jyoumei.cn/Article/details/gtwyoppsva.html

f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gtbmnmohuv.html

[U57] PHP：字符串插值
来源：http://dali.yongpay.top/Article/details/gtjijorgnq.html

"值: {$a}"
来源：http://dali.ppjwa.cn/Article/details/gtmdiuymja.html

[U58] PHP：数组三件套
来源：http://dali.zhoulong.xyz/Article/details/gtjvvipuaq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.dianchejie.cn/Article/details/gthxkbjvll.html

[U59] PHP：自定义排序
来源：http://dali.svipenyu.cn/Article/details/gticzrtoir.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlskjoyuz.html

[U60] PHP：JSON 编解码
来源：http://dali.xziqi.cn/Article/details/gtmkkialfn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jianghu66.top/Article/details/gtmsylplyl.html

[U61] PHP：正则
来源：http://dali.wangshuangyany.cn/Article/details/gtivhxvxpe.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gtgqijggxh.html

[U62] PHP：日期对象
来源：http://dali.jqgufenzy.top/Article/details/gtsddpibeu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj202588.top/Article/details/gtoayiiklm.html

[U63] PHP：文件读写
来源：http://dali.svipenyu.cn/Article/details/gtxwdwpxpp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gotoacloud.top/Article/details/gtzsdcfkju.html

[U64] PHP：目录遍历
来源：http://dali.jiagoushi.top/Article/details/gttrhntdav.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jianghu66.top/Article/details/gtlqvbvkiq.html

[U65] PHP：会话
来源：http://dali.jiagoushi.top/Article/details/gtkbzcbdfc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtnnawwioq.html

[U66] PHP：设置 Cookie
来源：http://dali.cqqwz.cn/Article/details/gtehxyshva.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.0kj1m.cn/Article/details/gthbmaxess.html

[U67] PHP：处理文件上传
来源：http://dali.feifeiyinyue.top/Article/details/gtjlivmbvt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.tianlin.xyz/Article/details/gtzoszprgf.html

[U68] PHP：PDO 连接
来源：http://dali.nanxinkj.top/Article/details/gtoveupohl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.nanxuanxn.top/Article/details/gtccsgobza.html

[U69] PHP：PDO 预处理
来源：http://dali.yangfankeji.com/Article/details/gtrdcxlsze.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.guowangkeji.top/Article/details/gtrvvscdki.html

[U70] PHP：PDO 事务
来源：http://dali.jianghu66.top/Article/details/gtubtxzohm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sufxvd.cn/Article/details/gtsvlckxhr.html


<!-- 参考信息 -->