代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtqynrjwdr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnqzz.top/Article/details/gtppxguqfv.html

[S48] C++：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtdszagywo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ppjwa.cn/Article/details/gtrslolfjb.html

while (std::getline(in, line)) { }
来源：http://dali.birdmap.top/Article/details/gtemrmfkbx.html

[S49] C++：写文件
来源：http://dali.yj20258888.top/Article/details/gtrvtcugxf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hysaishi.cn/Article/details/gtuqpchaxj.html

[S50] C++：格式化数字
来源：http://dali.gaohongyu789.top/Article/details/gtjgjwdwtp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtwmhfmayo.html

[S51] C++：显式类型转换
来源：http://dali.birdmap.top/Article/details/gtswpehwbk.html

static_cast<double>(a) / b
来源：http://dali.hfpthk.cn/Article/details/gtdyhkhnju.html

[S52] C++：const 与 noexcept
来源：http://dali.hongshengwenyu.top/Article/details/gtfbxomnch.html

int size() const noexcept { return n_; }
来源：http://dali.nanxinkj.top/Article/details/gtygzezpyu.html

[S53] C++：移动语义
来源：http://dali.cqqwz.cn/Article/details/gtouvmasmv.html

std::vector<int> w = std::move(v);
来源：http://dali.andypj.xyz/Article/details/gtvkrodrgm.html

[S54] C++：异常处理
来源：http://dali.pengpengdd.cyou/Article/details/gtqoxtpstr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gogol.net.cn/Article/details/gtxfkypdvk.html

[S55] C++：结构化绑定
来源：http://dali.zhoulong.xyz/Article/details/gtqxhffkqo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.kuanghao11.cn/Article/details/gtduiypbgh.html

[S56] C++：optional
来源：http://dali.sufxvd.cn/Article/details/gtulsorkcg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sxryk.cn/Article/details/gttgfsxlci.html

[S57] C++：编译期常量
来源：http://dali.sufxvd.cn/Article/details/gtayzgdvbu.html

constexpr int N = 10;
来源：http://dali.dianchejie.cn/Article/details/gtzwlxemkg.html

[S58] C++：命名空间
来源：http://dali.gaohongyu789.top/Article/details/gttflgukzt.html

namespace ns { int f() { return 1; } }
来源：http://dali.birdmap.top/Article/details/gtfodnljlb.html

[S59] C++：静态断言
来源：http://dali.shuidangran.top/Article/details/gtxluklaxz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgufenzy.top/Article/details/gtmasnzimy.html

[S60] C++：遍历并删除元素
来源：http://dali.0kj1m.cn/Article/details/gtmtovikpb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hywenlv.cn/Article/details/gtrbbxbkmw.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtliwyobhm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daxiang520.top/Article/details/gtndyaynvv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtrnexpqae.html

[T01] Kotlin：Hello World
来源：http://dali.sysykeji.top/Article/details/gtteomxmtv.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtbsygksju.html

[T02] Kotlin：变量
来源：http://dali.ivvv.top/Article/details/gtfgejtxyg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigufen.top/Article/details/gtfqcmtatv.html

[T03] Kotlin：字符串模板
来源：http://dali.gzhubu.top/Article/details/gtxepivpho.html

"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gtwhhnnfjm.html

[T04] Kotlin：空安全
来源：http://dali.snrcjt.cn/Article/details/gtkmsulhhv.html

val n: String? = null;  n?.length
来源：http://dali.sxryk.cn/Article/details/gtfcuysjaa.html

[T05] Kotlin：when 表达式
来源：http://dali.cucudq.cn/Article/details/gtbdfekytg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangdashe.top/Article/details/gtxgeiyivb.html

[T06] Kotlin：集合映射
来源：http://dali.guowangkeji.top/Article/details/gtnydlwvys.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yueranfly.top/Article/details/gtlezvofol.html

[T07] Kotlin：集合过滤
来源：http://dali.yj202588.top/Article/details/gtbtqubgar.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jyoumei.cn/Article/details/gtfaymwhsp.html

[T08] Kotlin：数据类
来源：http://dali.ydzc1.top/Article/details/gtbjcvrdpw.html

data class User(val name: String, val age: Int)
来源：http://dali.cheryme.top/Article/details/gtvjbgjahy.html

[T09] Kotlin：扩展函数
来源：http://dali.quarkkingdee.top/Article/details/gtvqhajczt.html

fun String.exclaim() = this + "!"
来源：http://dali.cqqwz.cn/Article/details/gtpdfainyx.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtnojfrpml.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhengqikj.top/Article/details/gtrpyekczo.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangkeji.top/Article/details/gthircobcx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigfzy.top/Article/details/gtqnvujtpi.html

[T12] Kotlin：解构声明
来源：http://dali.snrcjt.cn/Article/details/gtmcpiyzuh.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtiigzuyok.html

[T13] Kotlin：只读 Map
来源：http://dali.smart0.xyz/Article/details/gtowpnrpix.html

val m = mapOf("a" to 1)
来源：http://dali.mhx1999.top/Article/details/gtejfbyqzs.html

[T14] Kotlin：循环
来源：http://dali.0kj1m.cn/Article/details/gtsyjgvlhn.html

for (i in 1..10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gtwbwooebh.html

[T15] Kotlin：接口
来源：http://dali.daria6918.cn/Article/details/gtkfsdgsal.html

interface Shape { fun area(): Double }
来源：http://dali.mhx1999.top/Article/details/gtfspkyhos.html

[T16] Swift：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gttcdcjglc.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gtyswuclxx.html

[T17] Swift：变量与常量
来源：http://dali.xuanzx.com/Article/details/gtrygobnmu.html

var a = 1;  let b = 2
来源：http://dali.fengsongda.top/Article/details/gtsafpscnn.html

[T18] Swift：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtlkmemrho.html

"值: \(b)"
来源：http://dali.xuetiantiany.cn/Article/details/gtmidqinsn.html

[T19] Swift：可选绑定
来源：http://dali.jinqigfzy.top/Article/details/gtxjyylyuy.html

if let n = opt { print(n) }
来源：http://dali.tian-w.cn/Article/details/gtlpmylajk.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijrhjhug.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.redwolf501.top/Article/details/gtdqyvlcgw.html

[T21] Swift：遍历
来源：http://dali.cucudq.cn/Article/details/gtxkwzxfnw.html

for x in a { print(x) }
来源：http://dali.jqgfzy.top/Article/details/gtzodmtoqp.html

[T22] Swift：字典
来源：http://dali.feifeiyinyue.top/Article/details/gtkifybhab.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaebecxbf.html

[T23] Swift：函数
来源：http://dali.yvedp.cn/Article/details/gtkyxeumik.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.316326.xyz/Article/details/gtgmysgxhm.html

[T24] Swift：闭包
来源：http://dali.jyoumei.cn/Article/details/gtnwigshgo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtnjblbisb.html

[T25] Swift：结构体
来源：http://dali.havefunace.top/Article/details/gtbkqlbtrb.html

struct P { var x: Int }
来源：http://dali.xinyue.icu/Article/details/gtufzbagml.html

[T26] Swift：类与重写
来源：http://dali.cheryme.top/Article/details/gtcfvzlsyb.html

class A: Base { override func f() {} }
来源：http://dali.c1oappe.top/Article/details/gtyokyoupe.html

[T27] Swift：错误处理
来源：http://dali.jianghu66.top/Article/details/gtoleduggy.html

do { try f() } catch { print(error) }
来源：http://dali.gogol.net.cn/Article/details/gtmlwxamtw.html

[T28] Swift：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunmkccvn.html

enum Color { case red, green }
来源：http://dali.gaohongyu789.top/Article/details/gtntdraiqp.html

[T29] Swift：guard 提前返回
来源：http://dali.jiagoushi.top/Article/details/gtgzksislf.html

guard let x = opt else { return }
来源：http://dali.ydzc1.top/Article/details/gtrcownjdh.html

[T30] Swift：协议
来源：http://dali.jinqigufen.top/Article/details/gtmzajvjyd.html

protocol Shape { func area() -> Double }
来源：http://dali.birdmap.top/Article/details/gthegjtyfk.html

[T31] Lua：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtsfhjkuyi.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtvuvxvjqs.html

[T32] Lua：局部变量
来源：http://dali.redwolf501.top/Article/details/gttxtriyxm.html

local a = 1
来源：http://dali.xziqi.cn/Article/details/gtmnfnroee.html

[T33] Lua：表（数组）
来源：http://dali.yuxming.cn/Article/details/gtfosrlzjw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhiwuduotai.top/Article/details/gtbxbriima.html

[T34] Lua：遍历表
来源：http://dali.gogol.net.cn/Article/details/gtwwrqbjle.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yvedp.cn/Article/details/gtvgprskxq.html

[T35] Lua：字典表
来源：http://dali.yj20258888.top/Article/details/gtivewbhjo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.bjfxy.top/Article/details/gtlajzedhd.html

[T36] Lua：函数
来源：http://dali.yueranfly.top/Article/details/gtvcpwwdqp.html

function add(a, b) return a + b end
来源：http://dali.cheryme.top/Article/details/gteloekwwx.html

[T37] Lua：字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gtuxskgxqh.html

"a" .. "b"
来源：http://dali.nanxinkj.top/Article/details/gtgzvirzsy.html

[T38] Lua：条件
来源：http://dali.gogol.net.cn/Article/details/gtltojetfu.html

if x > 0 then print("正") end
来源：http://dali.pengpengdd.cyou/Article/details/gtsphnssng.html

[T39] Lua：模式匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtzeqdugfn.html

string.find(s, "%d+")
来源：http://dali.hnxiangtu.top/Article/details/gtwzehusct.html

[T40] Lua：元表
来源：http://dali.yuxming.cn/Article/details/gtujtwgdgi.html

setmetatable({}, { __index = base })
来源：http://dali.gotoacloud.top/Article/details/gtrpauisdv.html

[T41] Perl：Hello World
来源：http://dali.yongpay.top/Article/details/gtehstbfbx.html

print "Hello\n";
来源：http://dali.redwolf501.top/Article/details/gtlwkoogxc.html

[T42] Perl：变量类型
来源：http://dali.dianchejie.cn/Article/details/gtzoujunuh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.redwolf501.top/Article/details/gtzvbnnshy.html

[T43] Perl：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gtlhpmbufb.html

"值: $a"
来源：http://dali.0kj1m.cn/Article/details/gtxmedotfb.html

[T44] Perl：条件
来源：http://dali.guannengcc.top/Article/details/gtkidzcwyc.html

if ($a > 0) { print "正"; }
来源：http://dali.gotoacloud.top/Article/details/gtbyodngex.html

[T45] Perl：数组遍历
来源：http://dali.snrcjt.cn/Article/details/gtomjufcrn.html

for my $x (@arr) { print $x; }
来源：http://dali.iojbl.cn/Article/details/gtnxapmbhy.html

[T46] Perl：哈希操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrspwtap.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinqigfzy.top/Article/details/gtuvbogxua.html

[T47] Perl：正则捕获
来源：http://dali.cashguo.top/Article/details/gtitknxicg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yangfankeji.com/Article/details/gtdwtwcocu.html

[T48] Perl：正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gtsekvlssy.html

$s =~ s/old/new/g;
来源：http://dali.hysaishi.cn/Article/details/gtfqxaybzb.html

[T49] Perl：函数
来源：http://dali.jqgufenzy.top/Article/details/gtwcywfpwi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvogmuub.html

[T50] Perl：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtxyvciexc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.mhx1999.top/Article/details/gtzvsgvasn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gtgazszhol.html

[T51] Scala：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtkfslwwjy.html

println("Hello")
来源：http://dali.ydzc1.top/Article/details/gtgbnqabdb.html

[T52] Scala：变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrylidvtg.html

val a = 1;  var b = 2
来源：http://dali.gogol.net.cn/Article/details/gtzfvsrnuu.html

[T53] Scala：字符串插值
来源：http://dali.ydzc1.top/Article/details/gteoajshfe.html

s"值: $b"
来源：http://dali.hnxiangtu.top/Article/details/gtsalpagmq.html

[T54] Scala：集合映射
来源：http://dali.hysaishi.cn/Article/details/gtwtzpxiuy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gogol.net.cn/Article/details/gtsbsdfbbe.html

[T55] Scala：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gthfxvkuig.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yanxiufei.cn/Article/details/gttbmvxfsb.html

[T56] Scala：样例类
来源：http://dali.birdmap.top/Article/details/gtaaiayuec.html

case class User(name: String, age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvemzxml.html

[T57] Scala：模式匹配
来源：http://dali.fengsongda.top/Article/details/gthcdgvffl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfhndnmk.html

[T58] Scala：函数定义
来源：http://dali.hysaishi.cn/Article/details/gtrnufehfy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hywenlv.cn/Article/details/gtwzmpcwfe.html

[T59] Scala：循环
来源：http://dali.tianlin.xyz/Article/details/gtvrrnefhw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gtesrkjwha.html

[T60] Scala：折叠
来源：http://dali.ybcxt.top/Article/details/gtpqclhuhs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258888.top/Article/details/gtwhppdfjg.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtgixkflsi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.dianchejie.cn/Article/details/gtnxnrrtnx.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtsjzcfvha.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxuanxn.top/Article/details/gtyvwljipd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yangfankeji.com/Article/details/gtqrgnknsc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhengqikj.top/Article/details/gtwkgcexfn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.0kj1m.cn/Article/details/gtgdozdihx.html

[U03] Py：加载 .env 配置
来源：http://dali.quarkkingdee.top/Article/details/gtotzfkweq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenzaomai.com/Article/details/gtxtmgpwzb.html

[U04] Py：变量调试打印
来源：http://dali.hnqzz.top/Article/details/gtjrqjrprd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aibaodan.cn/Article/details/gtmgtastnj.html

[U05] Py：列表去重且保序
来源：http://dali.sweek.top/Article/details/gttwjmpgma.html

list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gtfptbvmmn.html

[U06] Py：合并两个字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfswrhad.html

{**a, **b}
来源：http://dali.cheryme.top/Article/details/gtvgvssful.html

[U07] Py：反转字典键值
来源：http://dali.birdmap.top/Article/details/gtahyxjmjq.html

{v: k for k, v in d.items()}
来源：http://dali.haohaochexian.top/Article/details/gtmbgwfjhv.html

[U08] Py：展平二维列表
来源：http://dali.haohaochexian.top/Article/details/gtfvjjpkaf.html

[y for x in nested for y in x]
来源：http://dali.jinqigufen.top/Article/details/gtrqvociiq.html

[U09] Py：字典取最大值的键
来源：http://dali.yueranfly.top/Article/details/gtidctipbo.html

max(d, key=d.get)
来源：http://dali.pycfn.com/Article/details/gtbzkqypaw.html

[U10] Py：按值排序字典
来源：http://dali.iojbl.cn/Article/details/gtdwvbjihg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ydzc1.top/Article/details/gthevccavl.html

[U11] Py：生成器表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtrklmlwiz.html

(x * 2 for x in arr)
来源：http://dali.aibaodan.cn/Article/details/gtlyjldntq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhixingplan.top/Article/details/gtdiiijvmo.html

Counter(arr).most_common(3)
来源：http://dali.smart0.xyz/Article/details/gtnuogqdve.html

[U13] Py：固定长度队列
来源：http://dali.gzhubu.top/Article/details/gtcvvnmyxq.html

deque(maxlen=10)
来源：http://dali.316326.xyz/Article/details/gticbdojvp.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258.top/Article/details/gtcnxgknbi.html

defaultdict(list)
来源：http://dali.bjfxy.top/Article/details/gtqusasrkw.html

[U15] Py：高精度计时
来源：http://dali.xuanzx.com/Article/details/gtvqvqsqki.html

t = time.perf_counter()
来源：http://dali.quarkkingdee.top/Article/details/gtxnnbvrcw.html

[U16] Py：命令行参数解析
来源：http://dali.yonumen.top/Article/details/gtndsitosh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.snrcjt.cn/Article/details/gtcngdqzwj.html

[U17] Py：初始化日志
来源：http://dali.tanke756.top/Article/details/gtjqehnzuz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.smart0.xyz/Article/details/gtqqmgotkx.html

[U18] Py：预编译正则
来源：http://dali.gaohongyu789.top/Article/details/gtqbwnoebv.html

pat = re.compile(r"\d+")
来源：http://dali.fengsongda.top/Article/details/gtgkjkvtif.html

[U19] Py：正则替换带回调
来源：http://dali.c1oappe.top/Article/details/gtqungzqxx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhoulong.xyz/Article/details/gtjathuoih.html

[U20] Py：缓存函数结果
来源：http://dali.havefunace.top/Article/details/gtesbznqjk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteeflsabw.html

[U21] Py：自定义上下文管理器
来源：http://dali.cashguo.top/Article/details/gtoxdjgkrp.html

@contextlib.contextmanager
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuufutuje.html

[U22] Py：矩阵转置
来源：http://dali.dashuyun.cn/Article/details/gtcnssbjxh.html

list(zip(*m))
来源：http://dali.redwolf501.top/Article/details/gthkjlkble.html

[U23] Py：分块读取大文件
来源：http://dali.fengsongda.top/Article/details/gtynzorhca.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sweek.top/Article/details/gtfatuhthj.html

[U24] Py：路径操作
来源：http://dali.chenzaomai.com/Article/details/gtfltwvyev.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gtilmguxke.html

[U25] Py：CSV 按字典读
来源：http://dali.jianghu66.top/Article/details/gtxmougbob.html

csv.DictReader(f)
来源：http://dali.hfpthk.cn/Article/details/gtqoxlwlvo.html

[U26] Py：并发下载
来源：http://dali.smart0.xyz/Article/details/gtspjaluvl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hnqzz.top/Article/details/gtaaghodyd.html

[U27] Py：异步 HTTP
来源：http://dali.yangfankeji.com/Article/details/gtdewkjovb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jianghu66.top/Article/details/gtfmklgjvb.html

[U28] Py：类型别名
来源：http://dali.tian-w.cn/Article/details/gtrfhyindq.html

UserId = int
来源：http://dali.guowangkeji.top/Article/details/gtteaiitdf.html

[U29] Py：属性校验
来源：http://dali.cheryme.top/Article/details/gtwdyyooln.html

@property 与 @x.setter 配合
来源：http://dali.c1oappe.top/Article/details/gtyawexptr.html

[U30] Py：数据类
来源：http://dali.zycfv.cn/Article/details/gtymmuxlsf.html

@dataclass(slots=True)
来源：http://dali.zycfv.cn/Article/details/gtcfutumdf.html

[U31] Py：单测
来源：http://dali.xuetiantiany.cn/Article/details/gtzvsqjuyt.html

python -m pytest -q
来源：http://dali.nanxinkj.top/Article/details/gtarcsqvwv.html

[U32] Py：代码格式化
来源：http://dali.ydzc1.top/Article/details/gtdelciedj.html

ruff format . && ruff check --fix .
来源：http://dali.svipenyu.cn/Article/details/gtyexzjksf.html

[U33] Py：打包发布
来源：http://dali.andypj.xyz/Article/details/gtdoljslnw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nwbrower.top/Article/details/gtakpstgpy.html

[U34] Py：判断编码
来源：http://dali.316326.xyz/Article/details/gtvfnckglh.html

chardet.detect(raw)
来源：http://dali.fzhhl.top/Article/details/gtyurezuem.html

[U35] Py：发送邮件
来源：http://dali.gogol.net.cn/Article/details/gtkxqovvqs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cdnleiting.top/Article/details/gtltmsnchh.html

[U36] Py：定时任务
来源：http://dali.iojbl.cn/Article/details/gtbhwtqunm.html

schedule.every(10).minutes.do(job)
来源：http://dali.tianlin.xyz/Article/details/gtqksmawsx.html

[U37] Py：读写 Excel
来源：http://dali.mhx1999.top/Article/details/gtqkbjjunl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.snrcjt.cn/Article/details/gtkqfzoaaw.html

[U38] Py：获取脚本所在目录
来源：http://dali.bjfxy.top/Article/details/gtutzivhez.html

Path(__file__).resolve().parent
来源：http://dali.316326.xyz/Article/details/gttqecciiy.html

[U39] Py：判断是否在交互环境
来源：http://dali.nwbrower.top/Article/details/gtbozmaagm.html

sys.stdout.isatty()
来源：http://dali.hfpthk.cn/Article/details/gtyjpcctmp.html

[U40] Py：打印到标准错误
来源：http://dali.yuxming.cn/Article/details/gtrrmutzlz.html

print("err", file=sys.stderr)
来源：http://dali.zhoulong.xyz/Article/details/gtgshqmfjj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.9152youxi.cn/Article/details/gtdphbuuyg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yongpay.top/Article/details/gtohtimmyq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shuidangran.top/Article/details/gtvocfjkvs.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.daxiang520.top/Article/details/gtoiriwaqm.html

[U43] PHP：声明命名空间
来源：http://dali.jyoumei.cn/Article/details/gtsmesxypr.html

namespace App\Http;
来源：http://dali.vqdsnc.cn/Article/details/gtpeibdwuc.html

[U44] PHP：开启严格类型
来源：http://dali.jqgfzy.top/Article/details/gtayntmsue.html

declare(strict_types=1);
来源：http://dali.jianghu66.top/Article/details/gtkqbpzowf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hongshengwenyu.top/Article/details/gtisdvoqpk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gteckisoiu.html

[U46] PHP：可空类型
来源：http://dali.ppjwa.cn/Article/details/gtzquszayr.html

?string $name = null
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdgiryiy.html

[U47] PHP：联合类型
来源：http://dali.jqgufenzy.top/Article/details/gtzczpvmrh.html

int|string $id
来源：http://dali.bjfxy.top/Article/details/gtugwjlgen.html

[U48] PHP：纯枚举
来源：http://dali.ivvv.top/Article/details/gtmvafqarh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gaohongyu789.top/Article/details/gtybdlffwd.html

[U49] PHP：只读属性
来源：http://dali.yangfankeji.com/Article/details/gtrwqxmdav.html

public readonly string $name
来源：http://dali.xuetiantiany.cn/Article/details/gtgcmjyvmu.html

[U50] PHP：构造器属性提升
来源：http://dali.hywenlv.cn/Article/details/gtizodxkiw.html

public function __construct(private int $id) {}
来源：http://dali.yueranfly.top/Article/details/gtxdinlsvt.html

[U51] PHP：数组解构
来源：http://dali.sxryk.cn/Article/details/gtchhsdjig.html

[$a, $b] = $arr;
来源：http://dali.fzhhl.top/Article/details/gtvjvktbnf.html

[U52] PHP：箭头函数
来源：http://dali.feifeiyinyue.top/Article/details/gtmlgcvdhu.html

$double = fn($x) => $x * 2;
来源：http://dali.tianlin.xyz/Article/details/gtribyrghd.html

[U53] PHP：空合并运算符
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqozpcat.html

$v = $a ?? $b ?? "default";
来源：http://dali.shuidangran.top/Article/details/gtwatyxdmj.html

[U54] PHP：空安全调用
来源：http://dali.nanxinkj.top/Article/details/gtcpikwaji.html

$obj?->method()
来源：http://dali.hywenlv.cn/Article/details/gtxqgpgfvh.html

[U55] PHP：match 表达式
来源：http://dali.jqgufenzy.top/Article/details/gtmapwjska.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinghuilouyu.cn/Article/details/gttsiwqbxl.html

[U56] PHP：命名参数
来源：http://dali.jqgufenzy.top/Article/details/gtrstwmvnc.html

f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gtacyiguwo.html

[U57] PHP：字符串插值
来源：http://dali.yj20258.top/Article/details/gtrrsrhhfw.html

"值: {$a}"
来源：http://dali.jinqigfzy.top/Article/details/gtpobrabfp.html

[U58] PHP：数组三件套
来源：http://dali.ydzc1.top/Article/details/gtizicuzkj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yj20258.top/Article/details/gtnxceszow.html

[U59] PHP：自定义排序
来源：http://dali.jqgfzy.top/Article/details/gtbmmzkzsd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuanzhike.top/Article/details/gtvwiohciy.html

[U60] PHP：JSON 编解码
来源：http://dali.feifeiyinyue.top/Article/details/gtbkdyeslf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.meibo888.top/Article/details/gtzsyrtsnu.html

[U61] PHP：正则
来源：http://dali.316326.xyz/Article/details/gtqeczcqcz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gtcdmoupoc.html

[U62] PHP：日期对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmxmduti.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gotoacloud.top/Article/details/gtludxpqxy.html

[U63] PHP：文件读写
来源：http://dali.quarkkingdee.top/Article/details/gtyjzrqyjj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinqigfzy.top/Article/details/gthkfyhnxs.html

[U64] PHP：目录遍历
来源：http://dali.yongpay.top/Article/details/gtlbrmagpd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ppjwa.cn/Article/details/gtabmlckkk.html

[U65] PHP：会话
来源：http://dali.hysaishi.cn/Article/details/gtssckopbr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtbjkxfhid.html

[U66] PHP：设置 Cookie
来源：http://dali.chenzaomai.com/Article/details/gtcvuzzlaa.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yuanzhike.top/Article/details/gtabeubnxu.html

[U67] PHP：处理文件上传
来源：http://dali.gzhubu.top/Article/details/gtthnzahhu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.smart0.xyz/Article/details/gtaivkdvql.html

[U68] PHP：PDO 连接
来源：http://dali.jinqigfzy.top/Article/details/gtvqtsqmye.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkckngtlq.html

[U69] PHP：PDO 预处理
来源：http://dali.wangshuangyany.cn/Article/details/gtydfndnlr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.daxiang520.top/Article/details/gtjsobbuwi.html

[U70] PHP：PDO 事务
来源：http://dali.yj20258888.top/Article/details/gtmrhhdjjy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.chenlongwang.top/Article/details/gtxrpwiznp.html

[U71] PHP：抛出异常
来源：http://dali.wangdashe.top/Article/details/gtlbrvlqby.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhengqikj.top/Article/details/gtopboyjdp.html

[U72] PHP：写错误日志
来源：http://dali.tian-w.cn/Article/details/gtkimawfbh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ydzc1.top/Article/details/gtadzuyods.html


<!-- 参考信息 -->