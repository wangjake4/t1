代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.yuanzhike.top/Article/details/gtamwucjyl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shangyingyoupin.top/Article/details/gtkscltfhj.html

[S48] C++：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtgqcjfozt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangshuangyany.cn/Article/details/gtdeddfaca.html

while (std::getline(in, line)) { }
来源：http://dali.zhoulong.xyz/Article/details/gtmwwrwtoa.html

[S49] C++：写文件
来源：http://dali.redwolf501.top/Article/details/gtseayswti.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dashuyun.cn/Article/details/gtpbhnfdix.html

[S50] C++：格式化数字
来源：http://dali.guowangkeji.top/Article/details/gtualbwscx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgtqyqnf.html

[S51] C++：显式类型转换
来源：http://dali.yonumen.top/Article/details/gtuqkppgxu.html

static_cast<double>(a) / b
来源：http://dali.mhx1999.top/Article/details/gtxprlqqey.html

[S52] C++：const 与 noexcept
来源：http://dali.yuxming.cn/Article/details/gtylwduorm.html

int size() const noexcept { return n_; }
来源：http://dali.yuxming.cn/Article/details/gtsituftam.html

[S53] C++：移动语义
来源：http://dali.guannengcc.top/Article/details/gteobslwpw.html

std::vector<int> w = std::move(v);
来源：http://dali.chenlongwang.top/Article/details/gtmrasubhr.html

[S54] C++：异常处理
来源：http://dali.shzxlz.cn/Article/details/gtwcotttui.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.svipenyu.cn/Article/details/gtmvudznly.html

[S55] C++：结构化绑定
来源：http://dali.daria6918.cn/Article/details/gtjsjujvgb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nwbrower.top/Article/details/gtyielulqv.html

[S56] C++：optional
来源：http://dali.hongshengwenyu.top/Article/details/gtdtvekiad.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hywenlv.cn/Article/details/gtjrqfxuei.html

[S57] C++：编译期常量
来源：http://dali.xylfe.cn/Article/details/gtqsjqawoz.html

constexpr int N = 10;
来源：http://dali.yj20258888.top/Article/details/gtokayswsf.html

[S58] C++：命名空间
来源：http://dali.yj202588.top/Article/details/gtrtuczsbt.html

namespace ns { int f() { return 1; } }
来源：http://dali.fengsongda.top/Article/details/gtvinrmdks.html

[S59] C++：静态断言
来源：http://dali.chenzaomai.com/Article/details/gtgyfzikfl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hongshengwenyu.top/Article/details/gtctwdawnt.html

[S60] C++：遍历并删除元素
来源：http://dali.ydzc1.top/Article/details/gtfmvnqrul.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ydzc1.top/Article/details/gtxqptwyvm.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtlrbogryv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yueranfly.top/Article/details/gtpjwrdwoh.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtgjhckeyy.html

[T01] Kotlin：Hello World
来源：http://dali.fengsongda.top/Article/details/gtosyxiqmh.html

println("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtsfoaenrj.html

[T02] Kotlin：变量
来源：http://dali.hammf.cn/Article/details/gtfomgaovd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxuanxn.top/Article/details/gtavnmlggr.html

[T03] Kotlin：字符串模板
来源：http://dali.xinyue.icu/Article/details/gtignvgyan.html

"值: $b"
来源：http://dali.yuxming.cn/Article/details/gtxbfwuepo.html

[T04] Kotlin：空安全
来源：http://dali.zhongyouzk.top/Article/details/gttchnkyjk.html

val n: String? = null;  n?.length
来源：http://dali.aibaodan.cn/Article/details/gtoklpvwht.html

[T05] Kotlin：when 表达式
来源：http://dali.tanke756.top/Article/details/gtdvzjqaeh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.0kj1m.cn/Article/details/gtrchirrvp.html

[T06] Kotlin：集合映射
来源：http://dali.xziqi.cn/Article/details/gtnkqzgvot.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvrfsyjg.html

[T07] Kotlin：集合过滤
来源：http://dali.zycfv.cn/Article/details/gtonrlrfwc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sweek.top/Article/details/gtkxhgdtfv.html

[T08] Kotlin：数据类
来源：http://dali.hywenlv.cn/Article/details/gtxqjbarat.html

data class User(val name: String, val age: Int)
来源：http://dali.zhixingplan.top/Article/details/gtzgvvfgnj.html

[T09] Kotlin：扩展函数
来源：http://dali.sufxvd.cn/Article/details/gtryatczac.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbphgtblz.html

[T10] Kotlin：默认参数
来源：http://dali.chenzaomai.com/Article/details/gtrqcsynqc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gaohongyu789.top/Article/details/gthfniqfvy.html

[T11] Kotlin：协程
来源：http://dali.mhx1999.top/Article/details/gtcvicscvs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xinyue.icu/Article/details/gtdbhsjoqf.html

[T12] Kotlin：解构声明
来源：http://dali.xuetiantiany.cn/Article/details/gtrmsovbns.html

val (a, b) = Pair(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gtmjszakdw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhengqikj.top/Article/details/gtkbtwejur.html

val m = mapOf("a" to 1)
来源：http://dali.zhoulong.xyz/Article/details/gtixjxxkqe.html

[T14] Kotlin：循环
来源：http://dali.chenlongwang.top/Article/details/gtzrqkfzpj.html

for (i in 1..10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gtpndfjwoe.html

[T15] Kotlin：接口
来源：http://dali.jyoumei.cn/Article/details/gtoqzekfpu.html

interface Shape { fun area(): Double }
来源：http://dali.pengpengdd.cyou/Article/details/gtpizqeozs.html

[T16] Swift：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gttjabuhti.html

print("Hello")
来源：http://dali.hysaishi.cn/Article/details/gtfncidcft.html

[T17] Swift：变量与常量
来源：http://dali.andypj.xyz/Article/details/gtmrrepmpj.html

var a = 1;  let b = 2
来源：http://dali.ppjwa.cn/Article/details/gtljqijkga.html

[T18] Swift：字符串插值
来源：http://dali.ivvv.top/Article/details/gtxovhtflm.html

"值: \(b)"
来源：http://dali.cdnleiting.top/Article/details/gtohothamw.html

[T19] Swift：可选绑定
来源：http://dali.chenzaomai.com/Article/details/gtwwbugoyg.html

if let n = opt { print(n) }
来源：http://dali.tianlin.xyz/Article/details/gtmjefxhml.html

[T20] Swift：数组操作
来源：http://dali.snrcjt.cn/Article/details/gteazhzgqu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aizwys.cn/Article/details/gtvtdhhvzd.html

[T21] Swift：遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtpqoawpok.html

for x in a { print(x) }
来源：http://dali.jyoumei.cn/Article/details/gtwzzlxnju.html

[T22] Swift：字典
来源：http://dali.shangyingyoupin.top/Article/details/gtrcfgcpoo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.0kj1m.cn/Article/details/gtztofknse.html

[T23] Swift：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtklmqjtme.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuanzhike.top/Article/details/gtamxbfphs.html

[T24] Swift：闭包
来源：http://dali.xuetiantiany.cn/Article/details/gtlvrbfavr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.andypj.xyz/Article/details/gtvnabkgqs.html

[T25] Swift：结构体
来源：http://dali.smart0.xyz/Article/details/gtmfggeyal.html

struct P { var x: Int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlfkuopn.html

[T26] Swift：类与重写
来源：http://dali.316326.xyz/Article/details/gtuwwvewpc.html

class A: Base { override func f() {} }
来源：http://dali.mhx1999.top/Article/details/gtecphlnpr.html

[T27] Swift：错误处理
来源：http://dali.yuxming.cn/Article/details/gtxtmatyzh.html

do { try f() } catch { print(error) }
来源：http://dali.hongshengwenyu.top/Article/details/gtgwaamnib.html

[T28] Swift：枚举
来源：http://dali.fengsongda.top/Article/details/gtzfqywvhn.html

enum Color { case red, green }
来源：http://dali.jiagoushi.top/Article/details/gtxamfobcr.html

[T29] Swift：guard 提前返回
来源：http://dali.yueranfly.top/Article/details/gtwcecevlz.html

guard let x = opt else { return }
来源：http://dali.zhoulong.xyz/Article/details/gtzypodiux.html

[T30] Swift：协议
来源：http://dali.cucudq.cn/Article/details/gtbyooygld.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigufen.top/Article/details/gthxrvijht.html

[T31] Lua：Hello World
来源：http://dali.sysykeji.top/Article/details/gtsgooylde.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtvnaabfvd.html

[T32] Lua：局部变量
来源：http://dali.mhx1999.top/Article/details/gtbumqmkwi.html

local a = 1
来源：http://dali.ppjwa.cn/Article/details/gtvgtpiezd.html

[T33] Lua：表（数组）
来源：http://dali.zhoulong.xyz/Article/details/gtdfhaomwg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.pycfn.com/Article/details/gtphbpvmhj.html

[T34] Lua：遍历表
来源：http://dali.jlsjyb.cn/Article/details/gtmocmfmwx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yonumen.top/Article/details/gtlemzdbpc.html

[T35] Lua：字典表
来源：http://dali.c1oappe.top/Article/details/gtoyhjudwc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuxming.cn/Article/details/gtkkeybfqr.html

[T36] Lua：函数
来源：http://dali.zdqjudy.top/Article/details/gtkmubesty.html

function add(a, b) return a + b end
来源：http://dali.svipenyu.cn/Article/details/gtjmvjifog.html

[T37] Lua：字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gthkvirmwa.html

"a" .. "b"
来源：http://dali.chenzaomai.com/Article/details/gtpwtgiwsc.html

[T38] Lua：条件
来源：http://dali.hongshengwenyu.top/Article/details/gttwkbnqvk.html

if x > 0 then print("正") end
来源：http://dali.jiagoushi.top/Article/details/gtsxnmjdpo.html

[T39] Lua：模式匹配
来源：http://dali.sxryk.cn/Article/details/gtgqqamrow.html

string.find(s, "%d+")
来源：http://dali.gaohongyu789.top/Article/details/gtjbpfrtlo.html

[T40] Lua：元表
来源：http://dali.9152youxi.cn/Article/details/gtudoopvcs.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gtqfskbkis.html

[T41] Perl：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtiafbcpgi.html

print "Hello\n";
来源：http://dali.cdnleiting.top/Article/details/gtfffhpznv.html

[T42] Perl：变量类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbbxrsii.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.wangshuangyany.cn/Article/details/gtirmrkwhj.html

[T43] Perl：字符串插值
来源：http://dali.yj20258888.top/Article/details/gtunbhdsry.html

"值: $a"
来源：http://dali.sufxvd.cn/Article/details/gtoinaghic.html

[T44] Perl：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgrummbk.html

if ($a > 0) { print "正"; }
来源：http://dali.vqdsnc.cn/Article/details/gthrylvjms.html

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gtxwkypwcw.html

for my $x (@arr) { print $x; }
来源：http://dali.jiagoushi.top/Article/details/gtdesmmsyn.html

[T46] Perl：哈希操作
来源：http://dali.yonumen.top/Article/details/gtwgajyufx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.svipenyu.cn/Article/details/gtxfbaqerc.html

[T47] Perl：正则捕获
来源：http://dali.nanxinkj.top/Article/details/gthbvtuhyq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.kuanghao11.cn/Article/details/gtnmjjaqtr.html

[T48] Perl：正则替换
来源：http://dali.cheryme.top/Article/details/gtebygoesh.html

$s =~ s/old/new/g;
来源：http://dali.hnqzz.top/Article/details/gtjpmjnauk.html

[T49] Perl：函数
来源：http://dali.pycfn.com/Article/details/gtrlbgivjc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhpunqoh.html

[T50] Perl：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtxxxvhbgv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.mhx1999.top/Article/details/gtdopzjjti.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hywenlv.cn/Article/details/gtklzkoozm.html

[T51] Scala：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtinxrizrl.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtxixfneaj.html

[T52] Scala：变量
来源：http://dali.shuidangran.top/Article/details/gtxttaakpq.html

val a = 1;  var b = 2
来源：http://dali.tanke756.top/Article/details/gthpyfvhgs.html

[T53] Scala：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtvaelhmac.html

s"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gtowbefocb.html

[T54] Scala：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gtywoqpmfe.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gteecqwlox.html

[T55] Scala：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gtykekobzg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtczfcpzjz.html

[T56] Scala：样例类
来源：http://dali.yonumen.top/Article/details/gtqiloglwx.html

case class User(name: String, age: Int)
来源：http://dali.yangfankeji.com/Article/details/gtercfsktc.html

[T57] Scala：模式匹配
来源：http://dali.yj20258.top/Article/details/gtlgsyiwki.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.snrcjt.cn/Article/details/gtelciqptt.html

[T58] Scala：函数定义
来源：http://dali.iojbl.cn/Article/details/gtzgriglvo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sweek.top/Article/details/gtacbxqisn.html

[T59] Scala：循环
来源：http://dali.jiagoushi.top/Article/details/gtckltwhgt.html

for (i <- 1 to 10) println(i)
来源：http://dali.quarkkingdee.top/Article/details/gtfnuyfozd.html

[T60] Scala：折叠
来源：http://dali.gogol.net.cn/Article/details/gtliviofpp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tianlin.xyz/Article/details/gtoyexrgni.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gttruxpavp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.redwolf501.top/Article/details/gtmfhwtopq.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtqewrgbcl.html

[U01] Py：创建虚拟环境
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgxcbpgf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zycfv.cn/Article/details/gtumuyfwch.html

[U02] Py：导出 / 安装依赖
来源：http://dali.c1oappe.top/Article/details/gtnikaevfj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqozuxmg.html

[U03] Py：加载 .env 配置
来源：http://dali.sysykeji.top/Article/details/gtlmwpsvsd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nwbrower.top/Article/details/gtdwnivlmq.html

[U04] Py：变量调试打印
来源：http://dali.yonumen.top/Article/details/gtoghykzce.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hfpthk.cn/Article/details/gtvmsyctnt.html

[U05] Py：列表去重且保序
来源：http://dali.yvedp.cn/Article/details/gtlivettbd.html

list(dict.fromkeys(arr))
来源：http://dali.redwolf501.top/Article/details/gtykggtujq.html

[U06] Py：合并两个字典
来源：http://dali.ehwqpu.com/Article/details/gtcwbotyln.html

{**a, **b}
来源：http://dali.0kj1m.cn/Article/details/gtylfqowlt.html

[U07] Py：反转字典键值
来源：http://dali.gotoacloud.top/Article/details/gtytgdviwr.html

{v: k for k, v in d.items()}
来源：http://dali.guannengcc.top/Article/details/gtiubfnlca.html

[U08] Py：展平二维列表
来源：http://dali.vqdsnc.cn/Article/details/gtewxlbxjo.html

[y for x in nested for y in x]
来源：http://dali.cheryme.top/Article/details/gtmdbtnqzu.html

[U09] Py：字典取最大值的键
来源：http://dali.yvedp.cn/Article/details/gtcmqikgad.html

max(d, key=d.get)
来源：http://dali.hammf.cn/Article/details/gtblosyxhi.html

[U10] Py：按值排序字典
来源：http://dali.yj20258888.top/Article/details/gttjynikku.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.snrcjt.cn/Article/details/gtjzgbnzhn.html

[U11] Py：生成器表达式
来源：http://dali.hfpthk.cn/Article/details/gtnbdwjjkk.html

(x * 2 for x in arr)
来源：http://dali.hysaishi.cn/Article/details/gtvdzelkgo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.birdmap.top/Article/details/gtkxmoufcy.html

Counter(arr).most_common(3)
来源：http://dali.nanxuanxn.top/Article/details/gtwynjxohm.html

[U13] Py：固定长度队列
来源：http://dali.haohaochexian.top/Article/details/gtkjmktrjk.html

deque(maxlen=10)
来源：http://dali.zhiwuduotai.top/Article/details/gtxyfysjwl.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258888.top/Article/details/gteogjzmzf.html

defaultdict(list)
来源：http://dali.guowangkeji.top/Article/details/gtkdxxyevq.html

[U15] Py：高精度计时
来源：http://dali.yj202588.top/Article/details/gtcicwqnvl.html

t = time.perf_counter()
来源：http://dali.vqdsnc.cn/Article/details/gtasbocjkb.html

[U16] Py：命令行参数解析
来源：http://dali.gotoacloud.top/Article/details/gtelrrcckn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhiwuduotai.top/Article/details/gtpoijsqjz.html

[U17] Py：初始化日志
来源：http://dali.hammf.cn/Article/details/gtnuyxemqa.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.svipenyu.cn/Article/details/gtaactzpxs.html

[U18] Py：预编译正则
来源：http://dali.tanke756.top/Article/details/gtjogaqrir.html

pat = re.compile(r"\d+")
来源：http://dali.ehwqpu.com/Article/details/gtyzaftlns.html

[U19] Py：正则替换带回调
来源：http://dali.pengpengdd.cyou/Article/details/gtfkiflnzs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhiwuduotai.top/Article/details/gtfvuspdsp.html

[U20] Py：缓存函数结果
来源：http://dali.snrcjt.cn/Article/details/gtgbaswtqf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nwbrower.top/Article/details/gtxwbosdzg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zdqjudy.top/Article/details/gtbtxijmjg.html

@contextlib.contextmanager
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsvptdht.html

[U22] Py：矩阵转置
来源：http://dali.hongshengwenyu.top/Article/details/gtsjtszdbc.html

list(zip(*m))
来源：http://dali.shuidangran.top/Article/details/gtpewtdwwi.html

[U23] Py：分块读取大文件
来源：http://dali.birdmap.top/Article/details/gtzdwplpaq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.havefunace.top/Article/details/gtlqdttzsm.html

[U24] Py：路径操作
来源：http://dali.ybcxt.top/Article/details/gtbuazgggi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxujwaps.html

[U25] Py：CSV 按字典读
来源：http://dali.zhongyouzk.top/Article/details/gtkzfgkbqq.html

csv.DictReader(f)
来源：http://dali.haohaochexian.top/Article/details/gtjwqnlvnk.html

[U26] Py：并发下载
来源：http://dali.sxryk.cn/Article/details/gtngudneno.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jqgfzy.top/Article/details/gtdgcxylsa.html

[U27] Py：异步 HTTP
来源：http://dali.chenjidiqi.icu/Article/details/gtugozxmtu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.svipenyu.cn/Article/details/gtzccshcot.html

[U28] Py：类型别名
来源：http://dali.316326.xyz/Article/details/gtheicfkzf.html

UserId = int
来源：http://dali.yuxming.cn/Article/details/gtcykacjah.html

[U29] Py：属性校验
来源：http://dali.guowangkeji.top/Article/details/gtajtnbumk.html

@property 与 @x.setter 配合
来源：http://dali.quarkkingdee.top/Article/details/gthiajysvs.html

[U30] Py：数据类
来源：http://dali.mhx1999.top/Article/details/gtxdkmxbsn.html

@dataclass(slots=True)
来源：http://dali.yuanzhike.top/Article/details/gtzamzeqkr.html

[U31] Py：单测
来源：http://dali.ydzc1.top/Article/details/gtnlsevamr.html

python -m pytest -q
来源：http://dali.kuanghao11.cn/Article/details/gtkmjhxojk.html

[U32] Py：代码格式化
来源：http://dali.yj20258.top/Article/details/gtfpcdqygs.html

ruff format . && ruff check --fix .
来源：http://dali.gaohongyu789.top/Article/details/gtsqsdagah.html

[U33] Py：打包发布
来源：http://dali.sysykeji.top/Article/details/gtcityjuva.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cqqwz.cn/Article/details/gtcsgxunrq.html

[U34] Py：判断编码
来源：http://dali.jinqigfzy.top/Article/details/gtpjvnsvns.html

chardet.detect(raw)
来源：http://dali.gaohongyu789.top/Article/details/gtxqxzslvp.html

[U35] Py：发送邮件
来源：http://dali.jiagoushi.top/Article/details/gtczsskcjw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj202588.top/Article/details/gtetpiennc.html

[U36] Py：定时任务
来源：http://dali.gotoacloud.top/Article/details/gtlrgbvhot.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzkyltev.html

[U37] Py：读写 Excel
来源：http://dali.guannengcc.top/Article/details/gtkxlzfxgj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jianghu66.top/Article/details/gttigefzhx.html

[U38] Py：获取脚本所在目录
来源：http://dali.tanke756.top/Article/details/gtohgwgskm.html

Path(__file__).resolve().parent
来源：http://dali.sysykeji.top/Article/details/gtobnmdmlh.html

[U39] Py：判断是否在交互环境
来源：http://dali.hammf.cn/Article/details/gtqqltvirq.html

sys.stdout.isatty()
来源：http://dali.xuanzx.com/Article/details/gtumjazrld.html

[U40] Py：打印到标准错误
来源：http://dali.cqqwz.cn/Article/details/gtvmdyynmr.html

print("err", file=sys.stderr)
来源：http://dali.jiagoushi.top/Article/details/gtzdjhfcga.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.meibo888.top/Article/details/gthkzstzsg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.nanxuanxn.top/Article/details/gttyalxhmf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenlongwang.top/Article/details/gtxyzpafcb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yj20258888.top/Article/details/gtmyhcypty.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gtvbtiueti.html

namespace App\Http;
来源：http://dali.xuanzx.com/Article/details/gtxqvttxjs.html

[U44] PHP：开启严格类型
来源：http://dali.0kj1m.cn/Article/details/gtdmciljsc.html

declare(strict_types=1);
来源：http://dali.yangfankeji.com/Article/details/gtmoymqknm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hywenlv.cn/Article/details/gtasvejmns.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gttqnvpsen.html

[U46] PHP：可空类型
来源：http://dali.xuanzx.com/Article/details/gtajywnjqz.html

?string $name = null
来源：http://dali.yj20258888.top/Article/details/gtohhoxdbm.html

[U47] PHP：联合类型
来源：http://dali.xuanzx.com/Article/details/gtfsftasbf.html

int|string $id
来源：http://dali.fzhhl.top/Article/details/gtfotacvgh.html

[U48] PHP：纯枚举
来源：http://dali.ydzc1.top/Article/details/gtqtfytvoy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shzxlz.cn/Article/details/gtzxthcvgw.html

[U49] PHP：只读属性
来源：http://dali.chenzaomai.com/Article/details/gtzxswrnyv.html

public readonly string $name
来源：http://dali.snrcjt.cn/Article/details/gtovzyvbpc.html

[U50] PHP：构造器属性提升
来源：http://dali.smart0.xyz/Article/details/gtvjudwped.html

public function __construct(private int $id) {}
来源：http://dali.cheryme.top/Article/details/gtypqsarar.html

[U51] PHP：数组解构
来源：http://dali.zhongyouzk.top/Article/details/gtdnjqkuel.html

[$a, $b] = $arr;
来源：http://dali.wangshuangyany.cn/Article/details/gtnlzwzjzv.html

[U52] PHP：箭头函数
来源：http://dali.ydzc1.top/Article/details/gteagzuava.html

$double = fn($x) => $x * 2;
来源：http://dali.daxiang520.top/Article/details/gtkmdhmfwp.html

[U53] PHP：空合并运算符
来源：http://dali.shanyushiyangtech.top/Article/details/gthswrrxqa.html

$v = $a ?? $b ?? "default";
来源：http://dali.hysaishi.cn/Article/details/gthfulvrpy.html

[U54] PHP：空安全调用
来源：http://dali.316326.xyz/Article/details/gtspwgrjfd.html

$obj?->method()
来源：http://dali.jiagoushi.top/Article/details/gtxuiufcvz.html

[U55] PHP：match 表达式
来源：http://dali.hnxiangtu.top/Article/details/gtgtqvuztu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.birdmap.top/Article/details/gticmwkelv.html

[U56] PHP：命名参数
来源：http://dali.hnxiangtu.top/Article/details/gtqbhdoouk.html

f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gtwcjnfexz.html

[U57] PHP：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gtielznath.html

"值: {$a}"
来源：http://dali.0kj1m.cn/Article/details/gthvafawfg.html

[U58] PHP：数组三件套
来源：http://dali.pengpengdd.cyou/Article/details/gtzvijnkxu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtkijgbasn.html

[U59] PHP：自定义排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkcgioxlh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtpsqlavmn.html

[U60] PHP：JSON 编解码
来源：http://dali.chenjidiqi.icu/Article/details/gtcciabqrk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hnxiangtu.top/Article/details/gttscjwxqy.html

[U61] PHP：正则
来源：http://dali.yongpay.top/Article/details/gtaxtsuefw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtszuylwey.html

[U62] PHP：日期对象
来源：http://dali.zdqjudy.top/Article/details/gtggrtlmtp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tianlin.xyz/Article/details/gtaujtcwgx.html

[U63] PHP：文件读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnezwpqw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.haohaochexian.top/Article/details/gtuhsbspvh.html

[U64] PHP：目录遍历
来源：http://dali.9152youxi.cn/Article/details/gtgikhxkxn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sxryk.cn/Article/details/gtcndakebt.html

[U65] PHP：会话
来源：http://dali.kuanghao11.cn/Article/details/gteknbmdsv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gteujvhnsf.html

[U66] PHP：设置 Cookie
来源：http://dali.jlsjyb.cn/Article/details/gtbsvnfmqy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xylfe.cn/Article/details/gtbrbngyew.html

[U67] PHP：处理文件上传
来源：http://dali.mhx1999.top/Article/details/gtiwllzzdm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jqgfzy.top/Article/details/gtuddndigj.html

[U68] PHP：PDO 连接
来源：http://dali.yj20258888.top/Article/details/gtnmgnlxmn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.0kj1m.cn/Article/details/gtjeqwvbfy.html

[U69] PHP：PDO 预处理
来源：http://dali.aizwys.cn/Article/details/gtuklhcyzr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zdqjudy.top/Article/details/gtsbctslfu.html

[U70] PHP：PDO 事务
来源：http://dali.andypj.xyz/Article/details/gtagyopkev.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.shzxlz.cn/Article/details/gtxwbsqsxg.html

[U71] PHP：抛出异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbuegkqhp.html

throw new RuntimeException("失败", 500);
来源：http://dali.sufxvd.cn/Article/details/gttoviepit.html

[U72] PHP：写错误日志
来源：http://dali.zycfv.cn/Article/details/gtzaitytuw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenlongwang.top/Article/details/gtnyukshqq.html


<!-- 参考信息 -->