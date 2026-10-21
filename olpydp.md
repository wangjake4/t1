代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.ivvv.top/Article/details/gtvywnvnsb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gtujwwhyrx.html

[S48] C++：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtucwhdyzu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.vqdsnc.cn/Article/details/gtztkmkbtm.html

while (std::getline(in, line)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmoeqafl.html

[S49] C++：写文件
来源：http://dali.ehwqpu.com/Article/details/gteqlqdsak.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guowangkeji.top/Article/details/gtxkvohisx.html

[S50] C++：格式化数字
来源：http://dali.0kj1m.cn/Article/details/gtnoynnyvb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258.top/Article/details/gtjoauhubv.html

[S51] C++：显式类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtgopionai.html

static_cast<double>(a) / b
来源：http://dali.dianchejie.cn/Article/details/gtsfgvhpwf.html

[S52] C++：const 与 noexcept
来源：http://dali.chenlongwang.top/Article/details/gtofxhkcyi.html

int size() const noexcept { return n_; }
来源：http://dali.sxryk.cn/Article/details/gtdxmuxsbc.html

[S53] C++：移动语义
来源：http://dali.xylfe.cn/Article/details/gtcjmmouts.html

std::vector<int> w = std::move(v);
来源：http://dali.shuidangran.top/Article/details/gtokebjdvq.html

[S54] C++：异常处理
来源：http://dali.chenlongwang.top/Article/details/gttljfmzni.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ehwqpu.com/Article/details/gtufaabvva.html

[S55] C++：结构化绑定
来源：http://dali.316326.xyz/Article/details/gtmlmkooee.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ivvv.top/Article/details/gtgozlcyap.html

[S56] C++：optional
来源：http://dali.daxiang520.top/Article/details/gtdeslfpoo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.316326.xyz/Article/details/gttxeycivx.html

[S57] C++：编译期常量
来源：http://dali.guannengcc.top/Article/details/gtoexycmkc.html

constexpr int N = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtuidmhcai.html

[S58] C++：命名空间
来源：http://dali.daria6918.cn/Article/details/gtftbuwvhp.html

namespace ns { int f() { return 1; } }
来源：http://dali.c1oappe.top/Article/details/gtspfgdvcm.html

[S59] C++：静态断言
来源：http://dali.aizwys.cn/Article/details/gtydoewlae.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shangyingyoupin.top/Article/details/gtovszowtx.html

[S60] C++：遍历并删除元素
来源：http://dali.sysykeji.top/Article/details/gtaggfqzxm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gthnuddcai.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtnvgyrjfy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gtkntqifnb.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtrzhljtaj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtgitiqkrg.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gtjzviclqb.html

[T02] Kotlin：变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtwirvvjbr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shuidangran.top/Article/details/gtiggjlktv.html

[T03] Kotlin：字符串模板
来源：http://dali.sysykeji.top/Article/details/gtjmqjtnfz.html

"值: $b"
来源：http://dali.shuidangran.top/Article/details/gtkuiqwzpz.html

[T04] Kotlin：空安全
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxokrhgbb.html

val n: String? = null;  n?.length
来源：http://dali.yongpay.top/Article/details/gtniifnual.html

[T05] Kotlin：when 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspotjvmh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkvnxgyj.html

[T06] Kotlin：集合映射
来源：http://dali.sysykeji.top/Article/details/gthujynxab.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sysykeji.top/Article/details/gtbwpfjqtp.html

[T07] Kotlin：集合过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoksneqxw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jyoumei.cn/Article/details/gtzkfehpvg.html

[T08] Kotlin：数据类
来源：http://dali.ivvv.top/Article/details/gtzvqnyogt.html

data class User(val name: String, val age: Int)
来源：http://dali.zhixingplan.top/Article/details/gtcmdusajn.html

[T09] Kotlin：扩展函数
来源：http://dali.guannengcc.top/Article/details/gtmvjymjxk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gturfvcqmi.html

[T10] Kotlin：默认参数
来源：http://dali.jyoumei.cn/Article/details/gtdtkwgcdb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258888.top/Article/details/gtxtggnyfv.html

[T11] Kotlin：协程
来源：http://dali.zhongyouzk.top/Article/details/gtmkbpaaab.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gtbwmtddgt.html

[T12] Kotlin：解构声明
来源：http://dali.316326.xyz/Article/details/gttgebgjid.html

val (a, b) = Pair(1, 2)
来源：http://dali.cashguo.top/Article/details/gtcynfmxdt.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpgbajcz.html

val m = mapOf("a" to 1)
来源：http://dali.iojbl.cn/Article/details/gtfltgdprq.html

[T14] Kotlin：循环
来源：http://dali.yj202588.top/Article/details/gtfyzammjr.html

for (i in 1..10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gtazogbuxh.html

[T15] Kotlin：接口
来源：http://dali.hongshengwenyu.top/Article/details/gtagnrlzud.html

interface Shape { fun area(): Double }
来源：http://dali.fengsongda.top/Article/details/gtczdyewpp.html

[T16] Swift：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtenmbzsms.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtiqzkumwz.html

[T17] Swift：变量与常量
来源：http://dali.jlsjyb.cn/Article/details/gtoaedmflu.html

var a = 1;  let b = 2
来源：http://dali.chenzaomai.com/Article/details/gturewdxyi.html

[T18] Swift：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtdbprknnv.html

"值: \(b)"
来源：http://dali.wangshuangyany.cn/Article/details/gtobzylhbz.html

[T19] Swift：可选绑定
来源：http://dali.xinyue.icu/Article/details/gthwzrdklw.html

if let n = opt { print(n) }
来源：http://dali.gaohongyu789.top/Article/details/gtfiwfjnmn.html

[T20] Swift：数组操作
来源：http://dali.gogol.net.cn/Article/details/gthgupydpk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yueranfly.top/Article/details/gtshcyrpbo.html

[T21] Swift：遍历
来源：http://dali.vqdsnc.cn/Article/details/gtwjkespsx.html

for x in a { print(x) }
来源：http://dali.yj202588.top/Article/details/gtxuetosdt.html

[T22] Swift：字典
来源：http://dali.chenzaomai.com/Article/details/gtfdwdhdij.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cashguo.top/Article/details/gtcgefqmyr.html

[T23] Swift：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtfjelaoaw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.quarkkingdee.top/Article/details/gtvhathboi.html

[T24] Swift：闭包
来源：http://dali.ehwqpu.com/Article/details/gtujaqqmsv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.meibo888.top/Article/details/gtwqfseqdu.html

[T25] Swift：结构体
来源：http://dali.hnqzz.top/Article/details/gtjvmemqbh.html

struct P { var x: Int }
来源：http://dali.meibo888.top/Article/details/gtlzrflnqu.html

[T26] Swift：类与重写
来源：http://dali.jianghu66.top/Article/details/gttyqkelbr.html

class A: Base { override func f() {} }
来源：http://dali.fzhhl.top/Article/details/gttxnbymie.html

[T27] Swift：错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcmtunca.html

do { try f() } catch { print(error) }
来源：http://dali.hfpthk.cn/Article/details/gtpldfzsqv.html

[T28] Swift：枚举
来源：http://dali.tanke756.top/Article/details/gtolysezqi.html

enum Color { case red, green }
来源：http://dali.aibaodan.cn/Article/details/gtosrtdltf.html

[T29] Swift：guard 提前返回
来源：http://dali.cashguo.top/Article/details/gteeqcfhkx.html

guard let x = opt else { return }
来源：http://dali.vqdsnc.cn/Article/details/gtaqslrcda.html

[T30] Swift：协议
来源：http://dali.chenzaomai.com/Article/details/gtftxeebgn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhixingplan.top/Article/details/gtcuisdhdo.html

[T31] Lua：Hello World
来源：http://dali.guannengcc.top/Article/details/gtnbdqrxxp.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtevycfhkp.html

[T32] Lua：局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gtjdiaqjot.html

local a = 1
来源：http://dali.xziqi.cn/Article/details/gtwoqocimh.html

[T33] Lua：表（数组）
来源：http://dali.chenzaomai.com/Article/details/gtheekkxmp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhixingplan.top/Article/details/gtsabeflhw.html

[T34] Lua：遍历表
来源：http://dali.nwbrower.top/Article/details/gtzfzisabb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gogol.net.cn/Article/details/gtocuysgga.html

[T35] Lua：字典表
来源：http://dali.yueranfly.top/Article/details/gtuxzbfqci.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtranvwcye.html

[T36] Lua：函数
来源：http://dali.xziqi.cn/Article/details/gtngjqtowc.html

function add(a, b) return a + b end
来源：http://dali.ydzc1.top/Article/details/gtnayxbpqc.html

[T37] Lua：字符串拼接
来源：http://dali.yj202588.top/Article/details/gtfbryceaq.html

"a" .. "b"
来源：http://dali.sxryk.cn/Article/details/gtgoyqvrui.html

[T38] Lua：条件
来源：http://dali.ivvv.top/Article/details/gtvakzvqmt.html

if x > 0 then print("正") end
来源：http://dali.tianlin.xyz/Article/details/gtxvakiriv.html

[T39] Lua：模式匹配
来源：http://dali.mhx1999.top/Article/details/gtumpmfatb.html

string.find(s, "%d+")
来源：http://dali.tanke756.top/Article/details/gtivvjotpo.html

[T40] Lua：元表
来源：http://dali.jiagoushi.top/Article/details/gtbmibmtsj.html

setmetatable({}, { __index = base })
来源：http://dali.mhx1999.top/Article/details/gtifsbhrpp.html

[T41] Perl：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtpsoafaak.html

print "Hello\n";
来源：http://dali.jiagoushi.top/Article/details/gtlfcunkll.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gtporustxd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.daria6918.cn/Article/details/gtqrdcmhbn.html

[T43] Perl：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzbbyyma.html

"值: $a"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzcwfhfb.html

[T44] Perl：条件
来源：http://dali.gzhubu.top/Article/details/gtavovxdzd.html

if ($a > 0) { print "正"; }
来源：http://dali.xuanzx.com/Article/details/gtgmpwtdou.html

[T45] Perl：数组遍历
来源：http://dali.zhengqikj.top/Article/details/gtqzpjyzwq.html

for my $x (@arr) { print $x; }
来源：http://dali.mhx1999.top/Article/details/gtjwkogyyl.html

[T46] Perl：哈希操作
来源：http://dali.jqgufenzy.top/Article/details/gttdttpikb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gotoacloud.top/Article/details/gtilwnvwfy.html

[T47] Perl：正则捕获
来源：http://dali.yj202588.top/Article/details/gtspquhjeq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ybcxt.top/Article/details/gtpgxnicqk.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gtvsfqykai.html

$s =~ s/old/new/g;
来源：http://dali.hnqzz.top/Article/details/gtpiokcseh.html

[T49] Perl：函数
来源：http://dali.xinyue.icu/Article/details/gtpzfurvxw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gtnsgzygxe.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtapsmyscb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.pengpengdd.cyou/Article/details/gtkfmpbpwg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jyoumei.cn/Article/details/gtedoomals.html

[T51] Scala：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtpjjeqfag.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gtrzpwydlv.html

[T52] Scala：变量
来源：http://dali.hysaishi.cn/Article/details/gtqwjolqky.html

val a = 1;  var b = 2
来源：http://dali.ehwqpu.com/Article/details/gtdfajhwck.html

[T53] Scala：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtedguspgr.html

s"值: $b"
来源：http://dali.ehwqpu.com/Article/details/gtrjjnbxgk.html

[T54] Scala：集合映射
来源：http://dali.yongpay.top/Article/details/gtdtewarre.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hywenlv.cn/Article/details/gtppojomia.html

[T55] Scala：集合过滤
来源：http://dali.xuanzx.com/Article/details/gtfjaxhmeb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fzhhl.top/Article/details/gthpxlcuxl.html

[T56] Scala：样例类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpeqfrrqi.html

case class User(name: String, age: Int)
来源：http://dali.hfpthk.cn/Article/details/gtnucfvjwd.html

[T57] Scala：模式匹配
来源：http://dali.yonumen.top/Article/details/gtywtnbeur.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jiagoushi.top/Article/details/gtbgcklpma.html

[T58] Scala：函数定义
来源：http://dali.pengpengdd.cyou/Article/details/gttvzrdgdz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sxryk.cn/Article/details/gtlljufsit.html

[T59] Scala：循环
来源：http://dali.kuanghao11.cn/Article/details/gtdzlqzqqq.html

for (i <- 1 to 10) println(i)
来源：http://dali.sweek.top/Article/details/gthsyynfba.html

[T60] Scala：折叠
来源：http://dali.chenzaomai.com/Article/details/gtbnrsvmeq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgfzy.top/Article/details/gtpozhdvyv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtferknjnu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gotoacloud.top/Article/details/gtujmkpdyh.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtbrsgbhad.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigufen.top/Article/details/gtxftpajcr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj202588.top/Article/details/gtjwdmbdrw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.kuanghao11.cn/Article/details/gtmijwoomd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.0kj1m.cn/Article/details/gtazvfqqmw.html

[U03] Py：加载 .env 配置
来源：http://dali.gotoacloud.top/Article/details/gtlieojwkz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmqlzcze.html

[U04] Py：变量调试打印
来源：http://dali.sysykeji.top/Article/details/gtfervkoll.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xylfe.cn/Article/details/gttcmrvhmq.html

[U05] Py：列表去重且保序
来源：http://dali.guowangkeji.top/Article/details/gtatpyaper.html

list(dict.fromkeys(arr))
来源：http://dali.cheryme.top/Article/details/gtennhcmbc.html

[U06] Py：合并两个字典
来源：http://dali.hysaishi.cn/Article/details/gtwtpaguzx.html

{**a, **b}
来源：http://dali.jyoumei.cn/Article/details/gtqztlqoul.html

[U07] Py：反转字典键值
来源：http://dali.zdqjudy.top/Article/details/gtvfajdodm.html

{v: k for k, v in d.items()}
来源：http://dali.fengsongda.top/Article/details/gtybydpeya.html

[U08] Py：展平二维列表
来源：http://dali.zhiwuduotai.top/Article/details/gtxnecrgfa.html

[y for x in nested for y in x]
来源：http://dali.0kj1m.cn/Article/details/gttloolrxv.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgufenzy.top/Article/details/gtbxtuivbu.html

max(d, key=d.get)
来源：http://dali.kuanghao11.cn/Article/details/gtsnydsrkm.html

[U10] Py：按值排序字典
来源：http://dali.yanxiufei.cn/Article/details/gtlkchwvyi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.c1oappe.top/Article/details/gtisefbdvv.html

[U11] Py：生成器表达式
来源：http://dali.aibaodan.cn/Article/details/gtpuxaxvbn.html

(x * 2 for x in arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvasvcscq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ppjwa.cn/Article/details/gtrubcjhpj.html

Counter(arr).most_common(3)
来源：http://dali.fzhhl.top/Article/details/gtjyovvtuk.html

[U13] Py：固定长度队列
来源：http://dali.jyoumei.cn/Article/details/gthhinywth.html

deque(maxlen=10)
来源：http://dali.ppjwa.cn/Article/details/gtmjjqfoin.html

[U14] Py：分组收集到列表
来源：http://dali.cheryme.top/Article/details/gtsvdoertc.html

defaultdict(list)
来源：http://dali.daria6918.cn/Article/details/gtnhobvtca.html

[U15] Py：高精度计时
来源：http://dali.snrcjt.cn/Article/details/gtslvvzfzn.html

t = time.perf_counter()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwxvinqc.html

[U16] Py：命令行参数解析
来源：http://dali.yuxming.cn/Article/details/gtlkzjiwpj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shzxlz.cn/Article/details/gtclfsivkv.html

[U17] Py：初始化日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtglosyrpz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yanxiufei.cn/Article/details/gtnkpvtfyr.html

[U18] Py：预编译正则
来源：http://dali.wangdashe.top/Article/details/gtukqhmfdz.html

pat = re.compile(r"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvpkchin.html

[U19] Py：正则替换带回调
来源：http://dali.chenlongwang.top/Article/details/gtpedwdlcp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jiagoushi.top/Article/details/gtluaxhrka.html

[U20] Py：缓存函数结果
来源：http://dali.gaohongyu789.top/Article/details/gtavreudwo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhmwtplt.html

[U21] Py：自定义上下文管理器
来源：http://dali.cheryme.top/Article/details/gtuhzyenfx.html

@contextlib.contextmanager
来源：http://dali.chenzaomai.com/Article/details/gthhmevvls.html

[U22] Py：矩阵转置
来源：http://dali.gotoacloud.top/Article/details/gtdjroqapm.html

list(zip(*m))
来源：http://dali.yvedp.cn/Article/details/gtbclteqqc.html

[U23] Py：分块读取大文件
来源：http://dali.shuidangran.top/Article/details/gtpkcieybi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.dianchejie.cn/Article/details/gtdnjooenm.html

[U24] Py：路径操作
来源：http://dali.cucudq.cn/Article/details/gtybwzdiew.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gtdufkidhu.html

[U25] Py：CSV 按字典读
来源：http://dali.jqgufenzy.top/Article/details/gtomvpbltt.html

csv.DictReader(f)
来源：http://dali.pycfn.com/Article/details/gttynxeorn.html

[U26] Py：并发下载
来源：http://dali.zdqjudy.top/Article/details/gtwbioejod.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tianlin.xyz/Article/details/gtbzsmhzum.html

[U27] Py：异步 HTTP
来源：http://dali.jiagoushi.top/Article/details/gtpigjpkmh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.9152youxi.cn/Article/details/gtqbekyygm.html

[U28] Py：类型别名
来源：http://dali.hnxiangtu.top/Article/details/gtpipjvvhi.html

UserId = int
来源：http://dali.ydzc1.top/Article/details/gtijupohcx.html

[U29] Py：属性校验
来源：http://dali.yongpay.top/Article/details/gtbebqgycq.html

@property 与 @x.setter 配合
来源：http://dali.hnqzz.top/Article/details/gtxopnifvq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gtzhphbpdt.html

@dataclass(slots=True)
来源：http://dali.zhengqikj.top/Article/details/gtxxwjqgob.html

[U31] Py：单测
来源：http://dali.guannengcc.top/Article/details/gtcmgjonyt.html

python -m pytest -q
来源：http://dali.tanke756.top/Article/details/gtbngigqnh.html

[U32] Py：代码格式化
来源：http://dali.zhongyouzk.top/Article/details/gtwmaptgvh.html

ruff format . && ruff check --fix .
来源：http://dali.daxiang520.top/Article/details/gtpielsfiu.html

[U33] Py：打包发布
来源：http://dali.havefunace.top/Article/details/gtlbsvkyud.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhengqikj.top/Article/details/gtfbqekoym.html

[U34] Py：判断编码
来源：http://dali.hywenlv.cn/Article/details/gtveinfaya.html

chardet.detect(raw)
来源：http://dali.cucudq.cn/Article/details/gtqbokberi.html

[U35] Py：发送邮件
来源：http://dali.yvedp.cn/Article/details/gtertbxkoj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.nanxinkj.top/Article/details/gtemeufriz.html

[U36] Py：定时任务
来源：http://dali.jyoumei.cn/Article/details/gthihrpdjc.html

schedule.every(10).minutes.do(job)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgdnazmd.html

[U37] Py：读写 Excel
来源：http://dali.yongpay.top/Article/details/gtrqqgucjq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhepibxc.html

[U38] Py：获取脚本所在目录
来源：http://dali.meibo888.top/Article/details/gtoxqqyzke.html

Path(__file__).resolve().parent
来源：http://dali.cucudq.cn/Article/details/gtjqguoemm.html

[U39] Py：判断是否在交互环境
来源：http://dali.jqgfzy.top/Article/details/gtlookagyi.html

sys.stdout.isatty()
来源：http://dali.hammf.cn/Article/details/gtnyvvcjpa.html

[U40] Py：打印到标准错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxvlziph.html

print("err", file=sys.stderr)
来源：http://dali.jinqigfzy.top/Article/details/gtztugvhmw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hnxiangtu.top/Article/details/gtzbanpwro.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sysykeji.top/Article/details/gtzoyazkak.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyegvliwd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ydzc1.top/Article/details/gtkugowiat.html

[U43] PHP：声明命名空间
来源：http://dali.ybcxt.top/Article/details/gtxetgyurz.html

namespace App\Http;
来源：http://dali.chenjidiqi.icu/Article/details/gtljgwqhtt.html

[U44] PHP：开启严格类型
来源：http://dali.vqdsnc.cn/Article/details/gtjhalllwn.html

declare(strict_types=1);
来源：http://dali.zhiwuduotai.top/Article/details/gtuvhhflfv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jlsjyb.cn/Article/details/gtkxhlbqfs.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gtoyokcimf.html

[U46] PHP：可空类型
来源：http://dali.guannengcc.top/Article/details/gtbcyrlokm.html

?string $name = null
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfuegsuk.html

[U47] PHP：联合类型
来源：http://dali.tanke756.top/Article/details/gtlpcnktnk.html

int|string $id
来源：http://dali.bjfxy.top/Article/details/gtrwjsyjhj.html

[U48] PHP：纯枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtdfkydxpj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sweek.top/Article/details/gtdddkjdrm.html

[U49] PHP：只读属性
来源：http://dali.xylfe.cn/Article/details/gteprohsjz.html

public readonly string $name
来源：http://dali.nanxuanxn.top/Article/details/gteknuakgw.html

[U50] PHP：构造器属性提升
来源：http://dali.0kj1m.cn/Article/details/gtibjucomn.html

public function __construct(private int $id) {}
来源：http://dali.quarkkingdee.top/Article/details/gtflpvjjkn.html

[U51] PHP：数组解构
来源：http://dali.guowangkeji.top/Article/details/gtlqrcjbjf.html

[$a, $b] = $arr;
来源：http://dali.316326.xyz/Article/details/gtpwfznfoh.html

[U52] PHP：箭头函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgitrjqda.html

$double = fn($x) => $x * 2;
来源：http://dali.chenjidiqi.icu/Article/details/gtxnbrmcom.html

[U53] PHP：空合并运算符
来源：http://dali.shuidangran.top/Article/details/gttzakbbbh.html

$v = $a ?? $b ?? "default";
来源：http://dali.yj20258.top/Article/details/gtsqxpkxwk.html

[U54] PHP：空安全调用
来源：http://dali.cqqwz.cn/Article/details/gtsvyucdil.html

$obj?->method()
来源：http://dali.zdqjudy.top/Article/details/gtpqqrldcu.html

[U55] PHP：match 表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpercpsaj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.feifeiyinyue.top/Article/details/gtvdigraxf.html

[U56] PHP：命名参数
来源：http://dali.gzhubu.top/Article/details/gtobriiefy.html

f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gtsfflimzc.html

[U57] PHP：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gtjyasogzv.html

"值: {$a}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlzitgdv.html

[U58] PHP：数组三件套
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlovbdykw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtlnyizsdo.html

[U59] PHP：自定义排序
来源：http://dali.yueranfly.top/Article/details/gtzhrcltpe.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhixingplan.top/Article/details/gtcbbrfmxl.html

[U60] PHP：JSON 编解码
来源：http://dali.316326.xyz/Article/details/gtwnrbebyt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nanxinkj.top/Article/details/gtvycvcvnb.html

[U61] PHP：正则
来源：http://dali.hfpthk.cn/Article/details/gtmsvxwejc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.c1oappe.top/Article/details/gtxynzognc.html

[U62] PHP：日期对象
来源：http://dali.cucudq.cn/Article/details/gtpjfshnor.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shangyingyoupin.top/Article/details/gttbyxapbc.html

[U63] PHP：文件读写
来源：http://dali.nanxuanxn.top/Article/details/gtmgwbxkhw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.snrcjt.cn/Article/details/gtwjeqkiuy.html

[U64] PHP：目录遍历
来源：http://dali.jyoumei.cn/Article/details/gtshokvqxn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gaohongyu789.top/Article/details/gtwklvvssv.html

[U65] PHP：会话
来源：http://dali.daria6918.cn/Article/details/gtfrlkqatk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gtdxbnllfu.html

[U66] PHP：设置 Cookie
来源：http://dali.9152youxi.cn/Article/details/gtzvesapfr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.birdmap.top/Article/details/gtdttswpfa.html

[U67] PHP：处理文件上传
来源：http://dali.chenjidiqi.icu/Article/details/gtqykdgmak.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.pycfn.com/Article/details/gtbmpvmxmx.html

[U68] PHP：PDO 连接
来源：http://dali.redwolf501.top/Article/details/gtyvspphlr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhoulong.xyz/Article/details/gtpqjnvkrq.html

[U69] PHP：PDO 预处理
来源：http://dali.redwolf501.top/Article/details/gtbfwxhmtm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.c1oappe.top/Article/details/gtueyetlcj.html

[U70] PHP：PDO 事务
来源：http://dali.fzhhl.top/Article/details/gtkczkposf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.guannengcc.top/Article/details/gthcanhokr.html

[U71] PHP：抛出异常
来源：http://dali.zhengqikj.top/Article/details/gtdnwcutle.html

throw new RuntimeException("失败", 500);
来源：http://dali.yj20258.top/Article/details/gtpvqcwwwd.html

[U72] PHP：写错误日志
来源：http://dali.zhixingplan.top/Article/details/gtbygewevq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hongshengwenyu.top/Article/details/gtqrgyswcs.html


<!-- 参考信息 -->