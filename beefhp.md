代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqhbtkmm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gtxyaoapin.html

[S48] C++：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtnccwwgzc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunavxemh.html

while (std::getline(in, line)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gthnnndmue.html

[S49] C++：写文件
来源：http://dali.iojbl.cn/Article/details/gtfftbniyt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.316326.xyz/Article/details/gtuxraqyda.html

[S50] C++：格式化数字
来源：http://dali.yuanzhike.top/Article/details/gtsoajgiyg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtvmhrxrno.html

[S51] C++：显式类型转换
来源：http://dali.hnxiangtu.top/Article/details/gtzqvjkbfv.html

static_cast<double>(a) / b
来源：http://dali.chenzaomai.com/Article/details/gtweqqjjvf.html

[S52] C++：const 与 noexcept
来源：http://dali.hongshengwenyu.top/Article/details/gtmvrjczer.html

int size() const noexcept { return n_; }
来源：http://dali.xuanzx.com/Article/details/gtiomubdwg.html

[S53] C++：移动语义
来源：http://dali.shzxlz.cn/Article/details/gtmpvnqksy.html

std::vector<int> w = std::move(v);
来源：http://dali.cucudq.cn/Article/details/gtgykizcpv.html

[S54] C++：异常处理
来源：http://dali.mhx1999.top/Article/details/gtqhcoivzn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvpviyqg.html

[S55] C++：结构化绑定
来源：http://dali.aibaodan.cn/Article/details/gtfyvukfkb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.c1oappe.top/Article/details/gtbotyjmqi.html

[S56] C++：optional
来源：http://dali.cqqwz.cn/Article/details/gtrbpcxupc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hongshengwenyu.top/Article/details/gteaktdyvm.html

[S57] C++：编译期常量
来源：http://dali.smart0.xyz/Article/details/gtmzdrjqde.html

constexpr int N = 10;
来源：http://dali.havefunace.top/Article/details/gtqjuwyiqc.html

[S58] C++：命名空间
来源：http://dali.sufxvd.cn/Article/details/gtvduenxzm.html

namespace ns { int f() { return 1; } }
来源：http://dali.c1oappe.top/Article/details/gtvylyirrw.html

[S59] C++：静态断言
来源：http://dali.cdnleiting.top/Article/details/gtyxtuzdku.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yangfankeji.com/Article/details/gtkwkunnbx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvryayoum.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gtbogwbxzp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtjganmoqk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cucudq.cn/Article/details/gtmdoitnpw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtrqvhhsgc.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gtegmvfoti.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtqiayfwto.html

[T02] Kotlin：变量
来源：http://dali.hfpthk.cn/Article/details/gtbxklbzet.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangshuangyany.cn/Article/details/gtsrwcpadn.html

[T03] Kotlin：字符串模板
来源：http://dali.chenzaomai.com/Article/details/gtwhkjbxtl.html

"值: $b"
来源：http://dali.sysykeji.top/Article/details/gtqboomvqt.html

[T04] Kotlin：空安全
来源：http://dali.xziqi.cn/Article/details/gtapygjgqv.html

val n: String? = null;  n?.length
来源：http://dali.hammf.cn/Article/details/gtswahzfhc.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gtjclwqbgb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigfzy.top/Article/details/gtkmrxnhhu.html

[T06] Kotlin：集合映射
来源：http://dali.shuidangran.top/Article/details/gtjikcekbp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daria6918.cn/Article/details/gtvzzrputz.html

[T07] Kotlin：集合过滤
来源：http://dali.xziqi.cn/Article/details/gtvsxfdgjb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gogol.net.cn/Article/details/gtdzzzbnpi.html

[T08] Kotlin：数据类
来源：http://dali.sxryk.cn/Article/details/gtpwbvirzv.html

data class User(val name: String, val age: Int)
来源：http://dali.gzhubu.top/Article/details/gtzfeiqncy.html

[T09] Kotlin：扩展函数
来源：http://dali.zycfv.cn/Article/details/gtspggahbb.html

fun String.exclaim() = this + "!"
来源：http://dali.quarkkingdee.top/Article/details/gtrwcrtpjt.html

[T10] Kotlin：默认参数
来源：http://dali.hfpthk.cn/Article/details/gtgidxncnu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cheryme.top/Article/details/gtxhuwbmiy.html

[T11] Kotlin：协程
来源：http://dali.tanke756.top/Article/details/gtqvknpbhw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.kuanghao11.cn/Article/details/gtuexhkocn.html

[T12] Kotlin：解构声明
来源：http://dali.sweek.top/Article/details/gtmzndwmfu.html

val (a, b) = Pair(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtqyfklfoe.html

[T13] Kotlin：只读 Map
来源：http://dali.smart0.xyz/Article/details/gtxlkuothc.html

val m = mapOf("a" to 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmplyutmd.html

[T14] Kotlin：循环
来源：http://dali.jlsjyb.cn/Article/details/gtlymnmsxq.html

for (i in 1..10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gtpimtfaan.html

[T15] Kotlin：接口
来源：http://dali.gotoacloud.top/Article/details/gtownvakpz.html

interface Shape { fun area(): Double }
来源：http://dali.smart0.xyz/Article/details/gtqqjcyshk.html

[T16] Swift：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtjvghclec.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtftugsrep.html

[T17] Swift：变量与常量
来源：http://dali.jlsjyb.cn/Article/details/gtggocbzdy.html

var a = 1;  let b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtymhrwxmr.html

[T18] Swift：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gtsdlfgkcw.html

"值: \(b)"
来源：http://dali.tianlin.xyz/Article/details/gtfttickhs.html

[T19] Swift：可选绑定
来源：http://dali.yangfankeji.com/Article/details/gtkxrboqhr.html

if let n = opt { print(n) }
来源：http://dali.jianghu66.top/Article/details/gtwfqjbjlj.html

[T20] Swift：数组操作
来源：http://dali.zhiwuduotai.top/Article/details/gtsuvfcatq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zycfv.cn/Article/details/gtfffswtib.html

[T21] Swift：遍历
来源：http://dali.yanxiufei.cn/Article/details/gtuxwkhmfu.html

for x in a { print(x) }
来源：http://dali.hongshengwenyu.top/Article/details/gtrzxjwbnp.html

[T22] Swift：字典
来源：http://dali.guannengcc.top/Article/details/gtfrzdklqh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhoulong.xyz/Article/details/gtnuerdeol.html

[T23] Swift：函数
来源：http://dali.daria6918.cn/Article/details/gtztbyxkek.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtkftoxjcx.html

[T24] Swift：闭包
来源：http://dali.guowangkeji.top/Article/details/gtclsjfbqn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtvfjwsyyl.html

[T25] Swift：结构体
来源：http://dali.aizwys.cn/Article/details/gtrxkutmat.html

struct P { var x: Int }
来源：http://dali.redwolf501.top/Article/details/gtbavbvalh.html

[T26] Swift：类与重写
来源：http://dali.dianchejie.cn/Article/details/gtzvqoxdty.html

class A: Base { override func f() {} }
来源：http://dali.guannengcc.top/Article/details/gtxjyecmuw.html

[T27] Swift：错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gtmcebuhhy.html

do { try f() } catch { print(error) }
来源：http://dali.ydzc1.top/Article/details/gtplnuiwbf.html

[T28] Swift：枚举
来源：http://dali.fengsongda.top/Article/details/gtbsvdyjhn.html

enum Color { case red, green }
来源：http://dali.fengsongda.top/Article/details/gtipuumeet.html

[T29] Swift：guard 提前返回
来源：http://dali.cucudq.cn/Article/details/gtipednlbi.html

guard let x = opt else { return }
来源：http://dali.birdmap.top/Article/details/gtuvzbsamw.html

[T30] Swift：协议
来源：http://dali.tanke756.top/Article/details/gthocbpfoi.html

protocol Shape { func area() -> Double }
来源：http://dali.fengsongda.top/Article/details/gtmsfkyplb.html

[T31] Lua：Hello World
来源：http://dali.bjfxy.top/Article/details/gtqbsqggkq.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtlpcrczrk.html

[T32] Lua：局部变量
来源：http://dali.9152youxi.cn/Article/details/gtqyletxah.html

local a = 1
来源：http://dali.gaohongyu789.top/Article/details/gtyfyxwsmv.html

[T33] Lua：表（数组）
来源：http://dali.shuidangran.top/Article/details/gtijflfdum.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yvedp.cn/Article/details/gtgsoyzxyt.html

[T34] Lua：遍历表
来源：http://dali.cqqwz.cn/Article/details/gtnvrhsxqg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhengqikj.top/Article/details/gtwguduxlw.html

[T35] Lua：字典表
来源：http://dali.daria6918.cn/Article/details/gtioesqmfi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dashuyun.cn/Article/details/gtgbbzwfmv.html

[T36] Lua：函数
来源：http://dali.cashguo.top/Article/details/gtooofrbuk.html

function add(a, b) return a + b end
来源：http://dali.ehwqpu.com/Article/details/gthjcmqrus.html

[T37] Lua：字符串拼接
来源：http://dali.daria6918.cn/Article/details/gtoouycrcq.html

"a" .. "b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizposlap.html

[T38] Lua：条件
来源：http://dali.jqgufenzy.top/Article/details/gtnlhowgfu.html

if x > 0 then print("正") end
来源：http://dali.quarkkingdee.top/Article/details/gtlzjlrsbt.html

[T39] Lua：模式匹配
来源：http://dali.xylfe.cn/Article/details/gtfcmbfgrn.html

string.find(s, "%d+")
来源：http://dali.daria6918.cn/Article/details/gtffkylqfc.html

[T40] Lua：元表
来源：http://dali.cqqwz.cn/Article/details/gtgxrwbmcd.html

setmetatable({}, { __index = base })
来源：http://dali.zhoulong.xyz/Article/details/gtfatealoa.html

[T41] Perl：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtzakvtxcp.html

print "Hello\n";
来源：http://dali.xinyue.icu/Article/details/gtlbfkxstl.html

[T42] Perl：变量类型
来源：http://dali.cqqwz.cn/Article/details/gtwjqqolbn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinqigufen.top/Article/details/gtkyttjwtb.html

[T43] Perl：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtulkthfre.html

"值: $a"
来源：http://dali.shzxlz.cn/Article/details/gtmzqtuxal.html

[T44] Perl：条件
来源：http://dali.snrcjt.cn/Article/details/gtoahikqkv.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gtolmnodfl.html

[T45] Perl：数组遍历
来源：http://dali.zhixingplan.top/Article/details/gtcmrzgfqi.html

for my $x (@arr) { print $x; }
来源：http://dali.xziqi.cn/Article/details/gtmtokcbmk.html

[T46] Perl：哈希操作
来源：http://dali.316326.xyz/Article/details/gtspemwvyl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtsymrnent.html

[T47] Perl：正则捕获
来源：http://dali.yvedp.cn/Article/details/gtfnbrzwwj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.haohaochexian.top/Article/details/gtvqzfygzc.html

[T48] Perl：正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztrwuhdp.html

$s =~ s/old/new/g;
来源：http://dali.nanxinkj.top/Article/details/gtnbngnekn.html

[T49] Perl：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqzuzxxr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gthimubeuu.html

[T50] Perl：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtciclxfsr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yangfankeji.com/Article/details/gtfibtlpmg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pycfn.com/Article/details/gtgshdueyr.html

[T51] Scala：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtejusbpnn.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gtvkithqly.html

[T52] Scala：变量
来源：http://dali.yj20258.top/Article/details/gttfcrxbey.html

val a = 1;  var b = 2
来源：http://dali.svipenyu.cn/Article/details/gtefvsuuwp.html

[T53] Scala：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtzccwqqsm.html

s"值: $b"
来源：http://dali.mhx1999.top/Article/details/gtrixxxcjz.html

[T54] Scala：集合映射
来源：http://dali.daria6918.cn/Article/details/gtdhejcnok.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tianlin.xyz/Article/details/gthgqrlpfu.html

[T55] Scala：集合过滤
来源：http://dali.cheryme.top/Article/details/gtbjogcwyb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdffrtkre.html

[T56] Scala：样例类
来源：http://dali.aibaodan.cn/Article/details/gtijfyzcdu.html

case class User(name: String, age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gtgqhbphsd.html

[T57] Scala：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gtyklogsgw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.quarkkingdee.top/Article/details/gtsebiuikq.html

[T58] Scala：函数定义
来源：http://dali.yangfankeji.com/Article/details/gtbssaaagk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrzszxrw.html

[T59] Scala：循环
来源：http://dali.ppjwa.cn/Article/details/gtizmzjroy.html

for (i <- 1 to 10) println(i)
来源：http://dali.fengsongda.top/Article/details/gtcsjzahim.html

[T60] Scala：折叠
来源：http://dali.hammf.cn/Article/details/gtruhgioui.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmszxqdhl.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtfeagmfzm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xinyue.icu/Article/details/gtiaoqkfes.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtajsbljok.html

[U01] Py：创建虚拟环境
来源：http://dali.tianlin.xyz/Article/details/gtzdcaopbh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenzaomai.com/Article/details/gtxekbjqgu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ehwqpu.com/Article/details/gtdiwtbuqt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.aizwys.cn/Article/details/gtfxnkjaeh.html

[U03] Py：加载 .env 配置
来源：http://dali.hywenlv.cn/Article/details/gtmwziwwbq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.redwolf501.top/Article/details/gtfsvailib.html

[U04] Py：变量调试打印
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhgqqeko.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jqgufenzy.top/Article/details/gthwauvxzr.html

[U05] Py：列表去重且保序
来源：http://dali.cqqwz.cn/Article/details/gtgcfngwso.html

list(dict.fromkeys(arr))
来源：http://dali.sufxvd.cn/Article/details/gtsepbtkzi.html

[U06] Py：合并两个字典
来源：http://dali.fengsongda.top/Article/details/gtbmddrmsv.html

{**a, **b}
来源：http://dali.iojbl.cn/Article/details/gthqkfdqjk.html

[U07] Py：反转字典键值
来源：http://dali.redwolf501.top/Article/details/gtlhexvqwr.html

{v: k for k, v in d.items()}
来源：http://dali.zdqjudy.top/Article/details/gtifmiptdd.html

[U08] Py：展平二维列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvoracxrs.html

[y for x in nested for y in x]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzuvmpko.html

[U09] Py：字典取最大值的键
来源：http://dali.316326.xyz/Article/details/gtfvjonynq.html

max(d, key=d.get)
来源：http://dali.ybcxt.top/Article/details/gtdfwqjcvg.html

[U10] Py：按值排序字典
来源：http://dali.zdqjudy.top/Article/details/gtydujbhey.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.birdmap.top/Article/details/gtsdphgytf.html

[U11] Py：生成器表达式
来源：http://dali.jianghu66.top/Article/details/gtmahykvfb.html

(x * 2 for x in arr)
来源：http://dali.jiagoushi.top/Article/details/gtbgrumktj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.svipenyu.cn/Article/details/gtthprprsy.html

Counter(arr).most_common(3)
来源：http://dali.jianghu66.top/Article/details/gtqjfezhur.html

[U13] Py：固定长度队列
来源：http://dali.ppjwa.cn/Article/details/gtnpvkooal.html

deque(maxlen=10)
来源：http://dali.shuidangran.top/Article/details/gtbolfvzlg.html

[U14] Py：分组收集到列表
来源：http://dali.snrcjt.cn/Article/details/gtwiubgyqp.html

defaultdict(list)
来源：http://dali.fzhhl.top/Article/details/gtiinxqubj.html

[U15] Py：高精度计时
来源：http://dali.yanxiufei.cn/Article/details/gtgxmqtntd.html

t = time.perf_counter()
来源：http://dali.sweek.top/Article/details/gtdyzrjdox.html

[U16] Py：命令行参数解析
来源：http://dali.316326.xyz/Article/details/gtcqezracv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.c1oappe.top/Article/details/gteytjbevi.html

[U17] Py：初始化日志
来源：http://dali.quarkkingdee.top/Article/details/gtrwaxxudn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yvedp.cn/Article/details/gtjjghuxcs.html

[U18] Py：预编译正则
来源：http://dali.cdnleiting.top/Article/details/gtnnyrukzj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gtwezhawlb.html

[U19] Py：正则替换带回调
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqdxoiey.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigufen.top/Article/details/gtxjsgwrcl.html

[U20] Py：缓存函数结果
来源：http://dali.xinyue.icu/Article/details/gtijfmjlxe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhongyouzk.top/Article/details/gtcqtelenl.html

[U21] Py：自定义上下文管理器
来源：http://dali.xuetiantiany.cn/Article/details/gtwjluvvfq.html

@contextlib.contextmanager
来源：http://dali.yj20258.top/Article/details/gtvrxdoncr.html

[U22] Py：矩阵转置
来源：http://dali.pengpengdd.cyou/Article/details/gtmpoxxqmd.html

list(zip(*m))
来源：http://dali.hnxiangtu.top/Article/details/gtibiidwtx.html

[U23] Py：分块读取大文件
来源：http://dali.xuetiantiany.cn/Article/details/gtokkbsojf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ppjwa.cn/Article/details/gtirlswuky.html

[U24] Py：路径操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiekvqesd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gtuyihnivf.html

[U25] Py：CSV 按字典读
来源：http://dali.hongshengwenyu.top/Article/details/gtnxxncsxi.html

csv.DictReader(f)
来源：http://dali.yj202588.top/Article/details/gtfsqbadjb.html

[U26] Py：并发下载
来源：http://dali.daria6918.cn/Article/details/gtvtfcxyeb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.haohaochexian.top/Article/details/gtohwafaay.html

[U27] Py：异步 HTTP
来源：http://dali.gotoacloud.top/Article/details/gtvxpwoguc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yj20258.top/Article/details/gtvwbiedyl.html

[U28] Py：类型别名
来源：http://dali.yj20258.top/Article/details/gtktwqxxio.html

UserId = int
来源：http://dali.svipenyu.cn/Article/details/gtzbdpyovb.html

[U29] Py：属性校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwoqojjhl.html

@property 与 @x.setter 配合
来源：http://dali.chenlongwang.top/Article/details/gtbvmivagq.html

[U30] Py：数据类
来源：http://dali.yuxming.cn/Article/details/gtsjhzstrk.html

@dataclass(slots=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtazjniqfk.html

[U31] Py：单测
来源：http://dali.hfpthk.cn/Article/details/gtcdifnsep.html

python -m pytest -q
来源：http://dali.hammf.cn/Article/details/gtyqiglnwh.html

[U32] Py：代码格式化
来源：http://dali.redwolf501.top/Article/details/gtbhqsjntq.html

ruff format . && ruff check --fix .
来源：http://dali.jinqigufen.top/Article/details/gtwezevghp.html

[U33] Py：打包发布
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpsifkwlc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hammf.cn/Article/details/gtkxbjuxbp.html

[U34] Py：判断编码
来源：http://dali.0kj1m.cn/Article/details/gtoospgwhn.html

chardet.detect(raw)
来源：http://dali.xylfe.cn/Article/details/gtvgigvwct.html

[U35] Py：发送邮件
来源：http://dali.shangyingyoupin.top/Article/details/gtndecsrip.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinqigufen.top/Article/details/gtrymhmvxy.html

[U36] Py：定时任务
来源：http://dali.pengpengdd.cyou/Article/details/gtwqorbsum.html

schedule.every(10).minutes.do(job)
来源：http://dali.wangdashe.top/Article/details/gtkdgnasxp.html

[U37] Py：读写 Excel
来源：http://dali.jiagoushi.top/Article/details/gtkanhgobt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.pycfn.com/Article/details/gtvwozzqti.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtdoiceuwp.html

Path(__file__).resolve().parent
来源：http://dali.hnqzz.top/Article/details/gtymapzbdz.html

[U39] Py：判断是否在交互环境
来源：http://dali.xuetiantiany.cn/Article/details/gtawxacefj.html

sys.stdout.isatty()
来源：http://dali.yangfankeji.com/Article/details/gtzgkbdtcj.html

[U40] Py：打印到标准错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodqotmxs.html

print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gtlmvxeabi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkqyeqjj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gogol.net.cn/Article/details/gtgiinifkb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hysaishi.cn/Article/details/gtmqnvyokc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ehwqpu.com/Article/details/gtlkrdmshp.html

[U43] PHP：声明命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gtpohwgjsw.html

namespace App\Http;
来源：http://dali.zhongyouzk.top/Article/details/gtazorelbc.html

[U44] PHP：开启严格类型
来源：http://dali.shzxlz.cn/Article/details/gthjpcmavs.html

declare(strict_types=1);
来源：http://dali.redwolf501.top/Article/details/gtyilinvdc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cdnleiting.top/Article/details/gtegrdpqrj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtdabbjbqt.html

[U46] PHP：可空类型
来源：http://dali.ehwqpu.com/Article/details/gtppwaexlf.html

?string $name = null
来源：http://dali.wangshuangyany.cn/Article/details/gtgjkvmipv.html

[U47] PHP：联合类型
来源：http://dali.meibo888.top/Article/details/gtfdrvogro.html

int|string $id
来源：http://dali.gzhubu.top/Article/details/gtcubupdpf.html

[U48] PHP：纯枚举
来源：http://dali.zdqjudy.top/Article/details/gtqinukxwy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gzhubu.top/Article/details/gtylhwkdhi.html

[U49] PHP：只读属性
来源：http://dali.ivvv.top/Article/details/gtuqxikajf.html

public readonly string $name
来源：http://dali.chenlongwang.top/Article/details/gtfjuqjvvf.html

[U50] PHP：构造器属性提升
来源：http://dali.pycfn.com/Article/details/gtmougxiqt.html

public function __construct(private int $id) {}
来源：http://dali.jinqigfzy.top/Article/details/gtvoymwlsl.html

[U51] PHP：数组解构
来源：http://dali.jqgfzy.top/Article/details/gtfmvqnrwy.html

[$a, $b] = $arr;
来源：http://dali.jqgufenzy.top/Article/details/gtevxctymr.html

[U52] PHP：箭头函数
来源：http://dali.hongshengwenyu.top/Article/details/gtokspgpgf.html

$double = fn($x) => $x * 2;
来源：http://dali.shzxlz.cn/Article/details/gtlkzbtflo.html

[U53] PHP：空合并运算符
来源：http://dali.jianghu66.top/Article/details/gtruwuevyd.html

$v = $a ?? $b ?? "default";
来源：http://dali.vqdsnc.cn/Article/details/gtzwsmofot.html

[U54] PHP：空安全调用
来源：http://dali.haohaochexian.top/Article/details/gttitztvno.html

$obj?->method()
来源：http://dali.svipenyu.cn/Article/details/gtntyyltkw.html

[U55] PHP：match 表达式
来源：http://dali.aibaodan.cn/Article/details/gttuztjmjx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shuidangran.top/Article/details/gtekegtkhl.html

[U56] PHP：命名参数
来源：http://dali.cucudq.cn/Article/details/gtvcptycch.html

f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gtrljjnvct.html

[U57] PHP：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtwhbwubew.html

"值: {$a}"
来源：http://dali.snrcjt.cn/Article/details/gticsyoaio.html

[U58] PHP：数组三件套
来源：http://dali.bjfxy.top/Article/details/gtlnolynhb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtukmqwgzw.html

[U59] PHP：自定义排序
来源：http://dali.daxiang520.top/Article/details/gtdzzenruc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yongpay.top/Article/details/gtwtbjkowe.html

[U60] PHP：JSON 编解码
来源：http://dali.nanxinkj.top/Article/details/gtvkoxwjff.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.pycfn.com/Article/details/gtnsphphjq.html

[U61] PHP：正则
来源：http://dali.shuidangran.top/Article/details/gtouvipzun.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gtezjxzbwa.html

[U62] PHP：日期对象
来源：http://dali.jiagoushi.top/Article/details/gtmamuluwy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhongyouzk.top/Article/details/gtrejrcgak.html

[U63] PHP：文件读写
来源：http://dali.zhoulong.xyz/Article/details/gthuzjiwyj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yj20258.top/Article/details/gtvleputlo.html

[U64] PHP：目录遍历
来源：http://dali.ehwqpu.com/Article/details/gtqyubyuzf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj20258.top/Article/details/gtcwvolljt.html

[U65] PHP：会话
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvfrrtfl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ivvv.top/Article/details/gtlbzkwyag.html

[U66] PHP：设置 Cookie
来源：http://dali.pycfn.com/Article/details/gtozdhenxh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.snrcjt.cn/Article/details/gtyjkwkcdp.html

[U67] PHP：处理文件上传
来源：http://dali.316326.xyz/Article/details/gtklbpdyza.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.svipenyu.cn/Article/details/gtkyaqvezf.html

[U68] PHP：PDO 连接
来源：http://dali.yueranfly.top/Article/details/gtdqunjdpz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yj202588.top/Article/details/gtcdoqznhj.html

[U69] PHP：PDO 预处理
来源：http://dali.jqgufenzy.top/Article/details/gtdvmuhzzc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.pycfn.com/Article/details/gtjwbwasbr.html

[U70] PHP：PDO 事务
来源：http://dali.feifeiyinyue.top/Article/details/gttcpqhdbx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gaohongyu789.top/Article/details/gtxgqqrdcs.html

[U71] PHP：抛出异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqytvyvq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhiwuduotai.top/Article/details/gtfyjflkoh.html

[U72] PHP：写错误日志
来源：http://dali.dashuyun.cn/Article/details/gtnkizorgj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sweek.top/Article/details/gtomuwdevw.html


<!-- 参考信息 -->