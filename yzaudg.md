代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.wangdashe.top/Article/details/gt2tbnamgzu.html

[S49] C++：写文件
来源：http://dali.jlsjyb.cn/Article/details/gt2ogdwmeqh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxagufyx.html

[S50] C++：格式化数字
来源：http://dali.zhoulong.xyz/Article/details/gt2swyacrms.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gt2ccaupvlv.html

[S51] C++：显式类型转换
来源：http://dali.chenlongwang.top/Article/details/gt2mejhjbgd.html

static_cast<double>(a) / b
来源：http://dali.zhoulong.xyz/Article/details/gt2mzixrlmo.html

[S52] C++：const 与 noexcept
来源：http://dali.daria6918.cn/Article/details/gt2prlhysua.html

int size() const noexcept { return n_; }
来源：http://dali.jqgfzy.top/Article/details/gt2avshrevc.html

[S53] C++：移动语义
来源：http://dali.wangdashe.top/Article/details/gt2zecuaeux.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigufen.top/Article/details/gt2fdrqrrgh.html

[S54] C++：异常处理
来源：http://dali.gaohongyu789.top/Article/details/gt2hwpsjxbf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gt2jkeeujtk.html

[S55] C++：结构化绑定
来源：http://dali.yanxiufei.cn/Article/details/gt2ggiqleqf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangdashe.top/Article/details/gt2bzfwljcd.html

[S56] C++：optional
来源：http://dali.zdqjudy.top/Article/details/gt2eafsnrjv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.dianchejie.cn/Article/details/gt2eoniwbyt.html

[S57] C++：编译期常量
来源：http://dali.yj20258888.top/Article/details/gt2fhahewyj.html

constexpr int N = 10;
来源：http://dali.jiagoushi.top/Article/details/gt2rtecyryx.html

[S58] C++：命名空间
来源：http://dali.jinqigufen.top/Article/details/gt2duwohmws.html

namespace ns { int f() { return 1; } }
来源：http://dali.svipenyu.cn/Article/details/gt2iqpmwmgc.html

[S59] C++：静态断言
来源：http://dali.yanxiufei.cn/Article/details/gt2ybrnqyht.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xylfe.cn/Article/details/gt2ktuprund.html

[S60] C++：遍历并删除元素
来源：http://dali.9152youxi.cn/Article/details/gt2qmizrsgs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gt2ycgyhayt.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2fyxjvvka.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258.top/Article/details/gt2tvkjamlr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cefxyvax.html

[T01] Kotlin：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2jaoqumjn.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gt2vqyhaocb.html

[T02] Kotlin：变量
来源：http://dali.gzhubu.top/Article/details/gt2jltweeeb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yvedp.cn/Article/details/gt2clcqeklz.html

[T03] Kotlin：字符串模板
来源：http://dali.tian-w.cn/Article/details/gt2bypovphq.html

"值: $b"
来源：http://dali.jiagoushi.top/Article/details/gt2dmsdnged.html

[T04] Kotlin：空安全
来源：http://dali.pycfn.com/Article/details/gt2xokvrvcn.html

val n: String? = null;  n?.length
来源：http://dali.jyoumei.cn/Article/details/gt2gqcuqfsa.html

[T05] Kotlin：when 表达式
来源：http://dali.ppjwa.cn/Article/details/gt2coomhndf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2leacuvwo.html

[T06] Kotlin：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gt2piwgqiam.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.c1oappe.top/Article/details/gt2hlfwsvte.html

[T07] Kotlin：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gt2nzogamzl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guowangkeji.top/Article/details/gt2bxhmfprb.html

[T08] Kotlin：数据类
来源：http://dali.gogol.net.cn/Article/details/gt2muzwdxlg.html

data class User(val name: String, val age: Int)
来源：http://dali.xylfe.cn/Article/details/gt2znvhzjvt.html

[T09] Kotlin：扩展函数
来源：http://dali.jinqigfzy.top/Article/details/gt2glmbendg.html

fun String.exclaim() = this + "!"
来源：http://dali.jianghu66.top/Article/details/gt2aokvfxjt.html

[T10] Kotlin：默认参数
来源：http://dali.hammf.cn/Article/details/gt2ilqajfyp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pycfn.com/Article/details/gt2mhzfymnl.html

[T11] Kotlin：协程
来源：http://dali.zycfv.cn/Article/details/gt2bfqdowao.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sysykeji.top/Article/details/gt2kaupttdm.html

[T12] Kotlin：解构声明
来源：http://dali.nanxinkj.top/Article/details/gt2oojqqohi.html

val (a, b) = Pair(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gt2zqriozvg.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258.top/Article/details/gt2gmzgrtxu.html

val m = mapOf("a" to 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2emoyqkuo.html

[T14] Kotlin：循环
来源：http://dali.yj202588.top/Article/details/gt2zugtuief.html

for (i in 1..10) println(i)
来源：http://dali.ivvv.top/Article/details/gt2wetjsbqi.html

[T15] Kotlin：接口
来源：http://dali.316326.xyz/Article/details/gt2jjlzxbxc.html

interface Shape { fun area(): Double }
来源：http://dali.zhiwuduotai.top/Article/details/gt2odncifct.html

[T16] Swift：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2ozwqzliq.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gt2kaxcskwq.html

[T17] Swift：变量与常量
来源：http://dali.jyoumei.cn/Article/details/gt2tyfaljje.html

var a = 1;  let b = 2
来源：http://dali.gogol.net.cn/Article/details/gt2zekhhnkn.html

[T18] Swift：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gt2drxyurds.html

"值: \(b)"
来源：http://dali.hnqzz.top/Article/details/gt2fdkhzakz.html

[T19] Swift：可选绑定
来源：http://dali.pengpengdd.cyou/Article/details/gt2thckfbsu.html

if let n = opt { print(n) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ltxbwraw.html

[T20] Swift：数组操作
来源：http://dali.hongshengwenyu.top/Article/details/gt2woetyrqb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yongpay.top/Article/details/gt2ymqtxkun.html

[T21] Swift：遍历
来源：http://dali.iojbl.cn/Article/details/gt2ytpkbziy.html

for x in a { print(x) }
来源：http://dali.yongpay.top/Article/details/gt2whbggvyd.html

[T22] Swift：字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lcatmmzi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258888.top/Article/details/gt2sdklvamk.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqbwyvj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhixingplan.top/Article/details/gt2bvwgbnry.html

[T24] Swift：闭包
来源：http://dali.vqdsnc.cn/Article/details/gt2fbgaqdnr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cdnleiting.top/Article/details/gt2ljholrdf.html

[T25] Swift：结构体
来源：http://dali.iojbl.cn/Article/details/gt2tgdecpro.html

struct P { var x: Int }
来源：http://dali.tanke756.top/Article/details/gt2tomruwai.html

[T26] Swift：类与重写
来源：http://dali.cashguo.top/Article/details/gt2hodmlwia.html

class A: Base { override func f() {} }
来源：http://dali.dianchejie.cn/Article/details/gt2htpfodoz.html

[T27] Swift：错误处理
来源：http://dali.quarkkingdee.top/Article/details/gt2ourksjgy.html

do { try f() } catch { print(error) }
来源：http://dali.fzhhl.top/Article/details/gt2hnogftkq.html

[T28] Swift：枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2cgmlfjvj.html

enum Color { case red, green }
来源：http://dali.hongshengwenyu.top/Article/details/gt2iyjuqipr.html

[T29] Swift：guard 提前返回
来源：http://dali.wangshuangyany.cn/Article/details/gt2vkitbfmo.html

guard let x = opt else { return }
来源：http://dali.hnqzz.top/Article/details/gt2zkuolmjw.html

[T30] Swift：协议
来源：http://dali.xylfe.cn/Article/details/gt2rjsjynum.html

protocol Shape { func area() -> Double }
来源：http://dali.ybcxt.top/Article/details/gt2cujycsbv.html

[T31] Lua：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2zoayheji.html

print("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gt2umubhkbw.html

[T32] Lua：局部变量
来源：http://dali.haohaochexian.top/Article/details/gt2pqsmvgoi.html

local a = 1
来源：http://dali.sysykeji.top/Article/details/gt2wnupewgi.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cpuwzlen.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hywenlv.cn/Article/details/gt2drwbhgvd.html

[T34] Lua：遍历表
来源：http://dali.0kj1m.cn/Article/details/gt2sptwiwuo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xylfe.cn/Article/details/gt2uoxmrlpq.html

[T35] Lua：字典表
来源：http://dali.chenjidiqi.icu/Article/details/gt2uskvhkjg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.kuanghao11.cn/Article/details/gt2hmynlvvd.html

[T36] Lua：函数
来源：http://dali.birdmap.top/Article/details/gt2ktsqglsn.html

function add(a, b) return a + b end
来源：http://dali.quarkkingdee.top/Article/details/gt2uvrteysr.html

[T37] Lua：字符串拼接
来源：http://dali.pycfn.com/Article/details/gt2zjapovds.html

"a" .. "b"
来源：http://dali.0kj1m.cn/Article/details/gt2fngcgqje.html

[T38] Lua：条件
来源：http://dali.shangyingyoupin.top/Article/details/gt2ojthpvjt.html

if x > 0 then print("正") end
来源：http://dali.xinyue.icu/Article/details/gt2fqwqoojq.html

[T39] Lua：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2gjizkaqc.html

string.find(s, "%d+")
来源：http://dali.zhengqikj.top/Article/details/gt2xpoffoaj.html

[T40] Lua：元表
来源：http://dali.birdmap.top/Article/details/gt2vqqosufr.html

setmetatable({}, { __index = base })
来源：http://dali.hysaishi.cn/Article/details/gt2eaxxndnm.html

[T41] Perl：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2twsdmcvd.html

print "Hello\n";
来源：http://dali.mhx1999.top/Article/details/gt2cuhrcnwb.html

[T42] Perl：变量类型
来源：http://dali.fengsongda.top/Article/details/gt2imjkozhn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hfpthk.cn/Article/details/gt2klyejrtm.html

[T43] Perl：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gt2erfkjkmt.html

"值: $a"
来源：http://dali.jinqigufen.top/Article/details/gt2glrkwaed.html

[T44] Perl：条件
来源：http://dali.xylfe.cn/Article/details/gt2ykntlyoi.html

if ($a > 0) { print "正"; }
来源：http://dali.mhx1999.top/Article/details/gt2phojnnvz.html

[T45] Perl：数组遍历
来源：http://dali.yuanzhike.top/Article/details/gt2fzdigvtb.html

for my $x (@arr) { print $x; }
来源：http://dali.jianghu66.top/Article/details/gt2etkmaytw.html

[T46] Perl：哈希操作
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kdptwirs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.mhx1999.top/Article/details/gt2neyxcibf.html

[T47] Perl：正则捕获
来源：http://dali.aibaodan.cn/Article/details/gt2enahpsot.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zycfv.cn/Article/details/gt2akrwloox.html

[T48] Perl：正则替换
来源：http://dali.gaohongyu789.top/Article/details/gt2sbpbfhin.html

$s =~ s/old/new/g;
来源：http://dali.c1oappe.top/Article/details/gt2xkiturkh.html

[T49] Perl：函数
来源：http://dali.cqqwz.cn/Article/details/gt2rhqswkhf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gt2xiycaatp.html

[T50] Perl：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gt2bnkxsqlw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhengqikj.top/Article/details/gt2tgyzldxd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.bjfxy.top/Article/details/gt2xhjsawlh.html

[T51] Scala：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2hcjydfnc.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gt2gowaedlt.html

[T52] Scala：变量
来源：http://dali.sysykeji.top/Article/details/gt2bpwgoeaz.html

val a = 1;  var b = 2
来源：http://dali.zhixingplan.top/Article/details/gt2zxmxttod.html

[T53] Scala：字符串插值
来源：http://dali.316326.xyz/Article/details/gt2knllyobm.html

s"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gt2luvvgloi.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uocnbwrv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daria6918.cn/Article/details/gt2oniaqlio.html

[T55] Scala：集合过滤
来源：http://dali.xuanzx.com/Article/details/gt2tgjbyggq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.c1oappe.top/Article/details/gt2dwloonlg.html

[T56] Scala：样例类
来源：http://dali.xinyue.icu/Article/details/gt2lwvmvakb.html

case class User(name: String, age: Int)
来源：http://dali.yueranfly.top/Article/details/gt2rxbzoppu.html

[T57] Scala：模式匹配
来源：http://dali.yj20258888.top/Article/details/gt2tkzuxmxz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wqansnqp.html

[T58] Scala：函数定义
来源：http://dali.gogol.net.cn/Article/details/gt2mohtfhlz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.316326.xyz/Article/details/gt2fmegvcug.html

[T59] Scala：循环
来源：http://dali.tanke756.top/Article/details/gt2onpbuuet.html

for (i <- 1 to 10) println(i)
来源：http://dali.yonumen.top/Article/details/gt2hcvcymzv.html

[T60] Scala：折叠
来源：http://dali.nanxinkj.top/Article/details/gt2sifswgjn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jdauokma.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2sosejdoh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlvuvha.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2hruynxna.html

[U01] Py：创建虚拟环境
来源：http://dali.bjfxy.top/Article/details/gt2qdevqqqz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xinyue.icu/Article/details/gt2owkxkhje.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sufxvd.cn/Article/details/gt2yyfousdr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hywenlv.cn/Article/details/gt2ewaoxdnx.html

[U03] Py：加载 .env 配置
来源：http://dali.cashguo.top/Article/details/gt2klrbrrjb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hammf.cn/Article/details/gt2txquhsfl.html

[U04] Py：变量调试打印
来源：http://dali.ybcxt.top/Article/details/gt2pzzkpclg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.0kj1m.cn/Article/details/gt2mpodbzpg.html

[U05] Py：列表去重且保序
来源：http://dali.shzxlz.cn/Article/details/gt2upjaqwqu.html

list(dict.fromkeys(arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cwjeryde.html

[U06] Py：合并两个字典
来源：http://dali.haohaochexian.top/Article/details/gt2vofujjoe.html

{**a, **b}
来源：http://dali.wangshuangyany.cn/Article/details/gt2sywxamwh.html

[U07] Py：反转字典键值
来源：http://dali.jiagoushi.top/Article/details/gt2rzxnwvfd.html

{v: k for k, v in d.items()}
来源：http://dali.hammf.cn/Article/details/gt2sulftiss.html

[U08] Py：展平二维列表
来源：http://dali.cqqwz.cn/Article/details/gt2mreokymb.html

[y for x in nested for y in x]
来源：http://dali.xziqi.cn/Article/details/gt2xiiindus.html

[U09] Py：字典取最大值的键
来源：http://dali.gzhubu.top/Article/details/gt2vrcvncjy.html

max(d, key=d.get)
来源：http://dali.hnxiangtu.top/Article/details/gt2hbfhlpfa.html

[U10] Py：按值排序字典
来源：http://dali.hongshengwenyu.top/Article/details/gt2gtatpuuc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigufen.top/Article/details/gt2lllgggpv.html

[U11] Py：生成器表达式
来源：http://dali.pengpengdd.cyou/Article/details/gt2amxydqjs.html

(x * 2 for x in arr)
来源：http://dali.hysaishi.cn/Article/details/gt2ehmmpklo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yvedp.cn/Article/details/gt2spbtfkkg.html

Counter(arr).most_common(3)
来源：http://dali.fzhhl.top/Article/details/gt2fzodtcrf.html

[U13] Py：固定长度队列
来源：http://dali.hysaishi.cn/Article/details/gt2xhjathzt.html

deque(maxlen=10)
来源：http://dali.tianlin.xyz/Article/details/gt2qagswxtn.html

[U14] Py：分组收集到列表
来源：http://dali.vqdsnc.cn/Article/details/gt2ykjzhwma.html

defaultdict(list)
来源：http://dali.yueranfly.top/Article/details/gt2aushbfdy.html

[U15] Py：高精度计时
来源：http://dali.ppjwa.cn/Article/details/gt2tuxqwnkg.html

t = time.perf_counter()
来源：http://dali.yuxming.cn/Article/details/gt2zuhkpqoc.html

[U16] Py：命令行参数解析
来源：http://dali.hnqzz.top/Article/details/gt2qtrtjvmq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.andypj.xyz/Article/details/gt2nxuuxocd.html

[U17] Py：初始化日志
来源：http://dali.jqgufenzy.top/Article/details/gt2cdlunfzy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.dianchejie.cn/Article/details/gt2wmfccylo.html

[U18] Py：预编译正则
来源：http://dali.hnxiangtu.top/Article/details/gt2mplhkdbr.html

pat = re.compile(r"\d+")
来源：http://dali.gaohongyu789.top/Article/details/gt2vvaxwmgi.html

[U19] Py：正则替换带回调
来源：http://dali.zycfv.cn/Article/details/gt2lmyicuso.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cheryme.top/Article/details/gt2bvkpkcfs.html

[U20] Py：缓存函数结果
来源：http://dali.pycfn.com/Article/details/gt2ogglkyok.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gogol.net.cn/Article/details/gt2gsffeslk.html

[U21] Py：自定义上下文管理器
来源：http://dali.gaohongyu789.top/Article/details/gt2tmatvick.html

@contextlib.contextmanager
来源：http://dali.nanxinkj.top/Article/details/gt2wsahtrwo.html

[U22] Py：矩阵转置
来源：http://dali.hnqzz.top/Article/details/gt2euymncus.html

list(zip(*m))
来源：http://dali.jinqigfzy.top/Article/details/gt2oukaucax.html

[U23] Py：分块读取大文件
来源：http://dali.jinqigfzy.top/Article/details/gt2klqjehna.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ybcxt.top/Article/details/gt2gqqvkvmo.html

[U24] Py：路径操作
来源：http://dali.hongshengwenyu.top/Article/details/gt2ddbloglj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shzxlz.cn/Article/details/gt2iamcvbui.html

[U25] Py：CSV 按字典读
来源：http://dali.havefunace.top/Article/details/gt2mybmqtdc.html

csv.DictReader(f)
来源：http://dali.yj20258.top/Article/details/gt2sdrcpahz.html

[U26] Py：并发下载
来源：http://dali.bjfxy.top/Article/details/gt2rzmsphou.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yanxiufei.cn/Article/details/gt2ftblecvb.html

[U27] Py：异步 HTTP
来源：http://dali.nwbrower.top/Article/details/gt2dywqpjff.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shzxlz.cn/Article/details/gt2fgimmuzo.html

[U28] Py：类型别名
来源：http://dali.hongshengwenyu.top/Article/details/gt2axvdmmqw.html

UserId = int
来源：http://dali.sweek.top/Article/details/gt2mqnzafsn.html

[U29] Py：属性校验
来源：http://dali.nanxinkj.top/Article/details/gt2pxhsfglj.html

@property 与 @x.setter 配合
来源：http://dali.cheryme.top/Article/details/gt2fdnahqbp.html

[U30] Py：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gt2igcrbado.html

@dataclass(slots=True)
来源：http://dali.xinyue.icu/Article/details/gt2ajnqlauw.html

[U31] Py：单测
来源：http://dali.yj20258.top/Article/details/gt2cvkrezzs.html

python -m pytest -q
来源：http://dali.haohaochexian.top/Article/details/gt2ufyxixmk.html

[U32] Py：代码格式化
来源：http://dali.chenjidiqi.icu/Article/details/gt2srkmqnpr.html

ruff format . && ruff check --fix .
来源：http://dali.hnqzz.top/Article/details/gt2fcuuqnaw.html

[U33] Py：打包发布
来源：http://dali.svipenyu.cn/Article/details/gt2hfblpktg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.wangshuangyany.cn/Article/details/gt2asfsvgxn.html

[U34] Py：判断编码
来源：http://dali.yj202588.top/Article/details/gt2wzbiogkv.html

chardet.detect(raw)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tcjnhruo.html

[U35] Py：发送邮件
来源：http://dali.gotoacloud.top/Article/details/gt2aoldvueb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmynsykr.html

[U36] Py：定时任务
来源：http://dali.gogol.net.cn/Article/details/gt2pojprvyk.html

schedule.every(10).minutes.do(job)
来源：http://dali.svipenyu.cn/Article/details/gt2imxefbud.html

[U37] Py：读写 Excel
来源：http://dali.meibo888.top/Article/details/gt2ywchmlpe.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.nanxinkj.top/Article/details/gt2bvhbgwiq.html

[U38] Py：获取脚本所在目录
来源：http://dali.ppjwa.cn/Article/details/gt2uwxpdwcp.html

Path(__file__).resolve().parent
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kbghhidu.html

[U39] Py：判断是否在交互环境
来源：http://dali.guowangkeji.top/Article/details/gt2bmmkkvcg.html

sys.stdout.isatty()
来源：http://dali.xziqi.cn/Article/details/gt2dwhawpku.html

[U40] Py：打印到标准错误
来源：http://dali.jqgufenzy.top/Article/details/gt2frvmwisi.html

print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gt2cglcoihw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj20258888.top/Article/details/gt2sbjosbhw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhengqikj.top/Article/details/gt2vnyjbknu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zgkxtqqf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hnqzz.top/Article/details/gt2ejtekoov.html

[U43] PHP：声明命名空间
来源：http://dali.dashuyun.cn/Article/details/gt2dkirjgdk.html

namespace App\Http;
来源：http://dali.chenlongwang.top/Article/details/gt2trmstqmi.html

[U44] PHP：开启严格类型
来源：http://dali.zhongyouzk.top/Article/details/gt2xysmvfzo.html

declare(strict_types=1);
来源：http://dali.0kj1m.cn/Article/details/gt2rymjkwkm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yonumen.top/Article/details/gt2tporwsfd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ybdjrsrq.html

[U46] PHP：可空类型
来源：http://dali.zdqjudy.top/Article/details/gt2zshdupjw.html

?string $name = null
来源：http://dali.snrcjt.cn/Article/details/gt2qvjncdtj.html

[U47] PHP：联合类型
来源：http://dali.9152youxi.cn/Article/details/gt2peyfdzmj.html

int|string $id
来源：http://dali.0kj1m.cn/Article/details/gt2hxxcypzs.html

[U48] PHP：纯枚举
来源：http://dali.hammf.cn/Article/details/gt2pqjgaodl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.meibo888.top/Article/details/gt2ywzfprdh.html

[U49] PHP：只读属性
来源：http://dali.gotoacloud.top/Article/details/gt2ijdwipcm.html

public readonly string $name
来源：http://dali.316326.xyz/Article/details/gt2dzeilfif.html

[U50] PHP：构造器属性提升
来源：http://dali.zhixingplan.top/Article/details/gt2airudofm.html

public function __construct(private int $id) {}
来源：http://dali.xinyue.icu/Article/details/gt2rbepwapo.html

[U51] PHP：数组解构
来源：http://dali.tanke756.top/Article/details/gt2vaabujzc.html

[$a, $b] = $arr;
来源：http://dali.yueranfly.top/Article/details/gt2odgpnkgl.html

[U52] PHP：箭头函数
来源：http://dali.shzxlz.cn/Article/details/gt2jclppqka.html

$double = fn($x) => $x * 2;
来源：http://dali.hnxiangtu.top/Article/details/gt2tiszlnwl.html

[U53] PHP：空合并运算符
来源：http://dali.sysykeji.top/Article/details/gt2icuxtjfc.html

$v = $a ?? $b ?? "default";
来源：http://dali.tian-w.cn/Article/details/gt2clupfwaj.html

[U54] PHP：空安全调用
来源：http://dali.xziqi.cn/Article/details/gt2geycogxc.html

$obj?->method()
来源：http://dali.mhx1999.top/Article/details/gt2ukdntgyb.html

[U55] PHP：match 表达式
来源：http://dali.tanke756.top/Article/details/gt2rxsyabwy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj202588.top/Article/details/gt2tuoxfkow.html

[U56] PHP：命名参数
来源：http://dali.aibaodan.cn/Article/details/gt2vgvvsosk.html

f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gt2pssqxswe.html

[U57] PHP：字符串插值
来源：http://dali.redwolf501.top/Article/details/gt2chhmlrcp.html

"值: {$a}"
来源：http://dali.tian-w.cn/Article/details/gt2aimczrni.html

[U58] PHP：数组三件套
来源：http://dali.meibo888.top/Article/details/gt2nyrinysv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.guowangkeji.top/Article/details/gt2ubvetugo.html

[U59] PHP：自定义排序
来源：http://dali.ivvv.top/Article/details/gt2gwcuiumr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hammf.cn/Article/details/gt2ypbkfzqt.html

[U60] PHP：JSON 编解码
来源：http://dali.birdmap.top/Article/details/gt2zauprukl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yanxiufei.cn/Article/details/gt2zgltycit.html

[U61] PHP：正则
来源：http://dali.ehwqpu.com/Article/details/gt2wmulkgrb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2wgfzmppa.html

[U62] PHP：日期对象
来源：http://dali.xinyue.icu/Article/details/gt2xmpgdlju.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hnqzz.top/Article/details/gt2kticshnv.html

[U63] PHP：文件读写
来源：http://dali.yueranfly.top/Article/details/gt2pgzvtcgq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.chenjidiqi.icu/Article/details/gt2jrsulkxk.html

[U64] PHP：目录遍历
来源：http://dali.daxiang520.top/Article/details/gt2lhrfselv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.dashuyun.cn/Article/details/gt2zzkywmob.html

[U65] PHP：会话
来源：http://dali.nanxinkj.top/Article/details/gt2umlzyudn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2pbauugfe.html

[U66] PHP：设置 Cookie
来源：http://dali.sxryk.cn/Article/details/gt2vurrgmds.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2scucwwlg.html

[U67] PHP：处理文件上传
来源：http://dali.chenzaomai.com/Article/details/gt2qhdgjozm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yuanzhike.top/Article/details/gt2dqgxycnp.html

[U68] PHP：PDO 连接
来源：http://dali.gaohongyu789.top/Article/details/gt2ikzrhphf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cdnleiting.top/Article/details/gt2rvcibsxy.html

[U69] PHP：PDO 预处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bgazyehs.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hnxiangtu.top/Article/details/gt2cyfpxsua.html

[U70] PHP：PDO 事务
来源：http://dali.haohaochexian.top/Article/details/gt2msrxsgml.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zdqjudy.top/Article/details/gt2wklvgpax.html

[U71] PHP：抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gt2hvuqlwwq.html

throw new RuntimeException("失败", 500);
来源：http://dali.jqgufenzy.top/Article/details/gt2xxwzeytm.html

[U72] PHP：写错误日志
来源：http://dali.xuetiantiany.cn/Article/details/gt2cikjbqcp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jqgufenzy.top/Article/details/gt2ksqmieni.html

[U73] PHP：读取 ini 配置
来源：http://dali.smart0.xyz/Article/details/gt2fjzpwqwr.html

parse_ini_file("config.ini", true)
来源：http://dali.dianchejie.cn/Article/details/gt2ncfnhien.html

[U74] PHP：读取环境变量
来源：http://dali.c1oappe.top/Article/details/gt2fsenwgsj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gzhubu.top/Article/details/gt2gkxedxai.html


<!-- 参考信息 -->