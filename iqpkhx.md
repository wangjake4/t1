代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.jyoumei.cn/Article/details/gtcriodvxb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.smart0.xyz/Article/details/gtzissrydt.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncsjsiko.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cashguo.top/Article/details/gtnnuihphw.html

while (std::getline(in, line)) { }
来源：http://dali.haohaochexian.top/Article/details/gtwzlpgzsm.html

[S49] C++：写文件
来源：http://dali.haohaochexian.top/Article/details/gtdkqisbxt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guowangkeji.top/Article/details/gtvwxflclv.html

[S50] C++：格式化数字
来源：http://dali.jyoumei.cn/Article/details/gtnnnegwkc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtyrvfdtcb.html

[S51] C++：显式类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtnbcxhoub.html

static_cast<double>(a) / b
来源：http://dali.xylfe.cn/Article/details/gtbymnwons.html

[S52] C++：const 与 noexcept
来源：http://dali.yj202588.top/Article/details/gtqqslwijw.html

int size() const noexcept { return n_; }
来源：http://dali.yuanzhike.top/Article/details/gtfzqkzcna.html

[S53] C++：移动语义
来源：http://dali.feifeiyinyue.top/Article/details/gtmpzravxu.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigufen.top/Article/details/gtevnlchdl.html

[S54] C++：异常处理
来源：http://dali.snrcjt.cn/Article/details/gtzbwnuavm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhengqikj.top/Article/details/gthsgexetm.html

[S55] C++：结构化绑定
来源：http://dali.yangfankeji.com/Article/details/gtypocgcfm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yangfankeji.com/Article/details/gtdavragez.html

[S56] C++：optional
来源：http://dali.tianlin.xyz/Article/details/gtuxmlxwis.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258888.top/Article/details/gtxsnicfhz.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gtrljciyix.html

constexpr int N = 10;
来源：http://dali.yongpay.top/Article/details/gtaxobuznm.html

[S58] C++：命名空间
来源：http://dali.sweek.top/Article/details/gtxdcwvact.html

namespace ns { int f() { return 1; } }
来源：http://dali.cashguo.top/Article/details/gtghiwpbdz.html

[S59] C++：静态断言
来源：http://dali.cashguo.top/Article/details/gtqmnhyhhx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangdashe.top/Article/details/gthtghxqsc.html

[S60] C++：遍历并删除元素
来源：http://dali.guowangkeji.top/Article/details/gtxyudyeeq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gtlwbmrtdq.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gttegqqgzg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.0kj1m.cn/Article/details/gtdtxxaoib.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtexbotwdt.html

[T01] Kotlin：Hello World
来源：http://dali.xinyue.icu/Article/details/gtcuxhdjzw.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gtdozjoqrn.html

[T02] Kotlin：变量
来源：http://dali.ivvv.top/Article/details/gtfhsuqmwg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuanzhike.top/Article/details/gtsaatzbja.html

[T03] Kotlin：字符串模板
来源：http://dali.yanxiufei.cn/Article/details/gtkcikxqdz.html

"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gtocsstcan.html

[T04] Kotlin：空安全
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjewnzkp.html

val n: String? = null;  n?.length
来源：http://dali.chenlongwang.top/Article/details/gtuivegwnm.html

[T05] Kotlin：when 表达式
来源：http://dali.cdnleiting.top/Article/details/gtwwsdoqdo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.mhx1999.top/Article/details/gtfbrxqhkl.html

[T06] Kotlin：集合映射
来源：http://dali.birdmap.top/Article/details/gtpfhraqsk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtqjpyzddy.html

[T07] Kotlin：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbrfzrds.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.snrcjt.cn/Article/details/gtejbrjxla.html

[T08] Kotlin：数据类
来源：http://dali.birdmap.top/Article/details/gtwcysijqs.html

data class User(val name: String, val age: Int)
来源：http://dali.haohaochexian.top/Article/details/gtzpkpldtg.html

[T09] Kotlin：扩展函数
来源：http://dali.pycfn.com/Article/details/gtvhwheqcv.html

fun String.exclaim() = this + "!"
来源：http://dali.feifeiyinyue.top/Article/details/gtepiwuoeq.html

[T10] Kotlin：默认参数
来源：http://dali.xylfe.cn/Article/details/gtdibarspr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgufenzy.top/Article/details/gtwxxcvhta.html

[T11] Kotlin：协程
来源：http://dali.xuanzx.com/Article/details/gtqgxwxrds.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hysaishi.cn/Article/details/gtyqcfhszn.html

[T12] Kotlin：解构声明
来源：http://dali.wangshuangyany.cn/Article/details/gtobshjwbr.html

val (a, b) = Pair(1, 2)
来源：http://dali.birdmap.top/Article/details/gtyxibqsuz.html

[T13] Kotlin：只读 Map
来源：http://dali.c1oappe.top/Article/details/gtxugpwooa.html

val m = mapOf("a" to 1)
来源：http://dali.gzhubu.top/Article/details/gtnfwxecjp.html

[T14] Kotlin：循环
来源：http://dali.yvedp.cn/Article/details/gtpynvhfzw.html

for (i in 1..10) println(i)
来源：http://dali.sufxvd.cn/Article/details/gtxkzvkzek.html

[T15] Kotlin：接口
来源：http://dali.yueranfly.top/Article/details/gtogyjbfmb.html

interface Shape { fun area(): Double }
来源：http://dali.0kj1m.cn/Article/details/gtdbkycdcq.html

[T16] Swift：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtujuqpopj.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtqkkrsfnr.html

[T17] Swift：变量与常量
来源：http://dali.chenlongwang.top/Article/details/gtzyoknwyv.html

var a = 1;  let b = 2
来源：http://dali.bjfxy.top/Article/details/gtyrkjvaog.html

[T18] Swift：字符串插值
来源：http://dali.meibo888.top/Article/details/gtgapfmtjg.html

"值: \(b)"
来源：http://dali.gotoacloud.top/Article/details/gtyipzdvnm.html

[T19] Swift：可选绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtutloeudf.html

if let n = opt { print(n) }
来源：http://dali.tanke756.top/Article/details/gtlhmepabi.html

[T20] Swift：数组操作
来源：http://dali.yj20258.top/Article/details/gtvqcndpsw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.quarkkingdee.top/Article/details/gtwvjnwumj.html

[T21] Swift：遍历
来源：http://dali.svipenyu.cn/Article/details/gtkcprjtlb.html

for x in a { print(x) }
来源：http://dali.dashuyun.cn/Article/details/gtlteedihn.html

[T22] Swift：字典
来源：http://dali.yonumen.top/Article/details/gtivdzkvdq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.0kj1m.cn/Article/details/gtxnjfmtik.html

[T23] Swift：函数
来源：http://dali.hammf.cn/Article/details/gtbrosuskb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtmrscxfyw.html

[T24] Swift：闭包
来源：http://dali.ydzc1.top/Article/details/gtyqaozecq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtpgrdwrgz.html

[T25] Swift：结构体
来源：http://dali.ydzc1.top/Article/details/gtuiteupcl.html

struct P { var x: Int }
来源：http://dali.vqdsnc.cn/Article/details/gteaemflcn.html

[T26] Swift：类与重写
来源：http://dali.ydzc1.top/Article/details/gthvsgiuoq.html

class A: Base { override func f() {} }
来源：http://dali.chenjidiqi.icu/Article/details/gtvmacviqq.html

[T27] Swift：错误处理
来源：http://dali.yvedp.cn/Article/details/gthwjwtkoo.html

do { try f() } catch { print(error) }
来源：http://dali.zhixingplan.top/Article/details/gtcghnzmpm.html

[T28] Swift：枚举
来源：http://dali.ivvv.top/Article/details/gteerckfzn.html

enum Color { case red, green }
来源：http://dali.hnqzz.top/Article/details/gtmitbeett.html

[T29] Swift：guard 提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gtejnrettr.html

guard let x = opt else { return }
来源：http://dali.kuanghao11.cn/Article/details/gtpxyvxmrk.html

[T30] Swift：协议
来源：http://dali.ybcxt.top/Article/details/gtiuksqiiu.html

protocol Shape { func area() -> Double }
来源：http://dali.0kj1m.cn/Article/details/gtjujffsxa.html

[T31] Lua：Hello World
来源：http://dali.meibo888.top/Article/details/gttygaswpd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtegmxleoo.html

[T32] Lua：局部变量
来源：http://dali.0kj1m.cn/Article/details/gtjkyhktvw.html

local a = 1
来源：http://dali.hysaishi.cn/Article/details/gtyjrjkvwd.html

[T33] Lua：表（数组）
来源：http://dali.hnqzz.top/Article/details/gtlbrwqmhd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tian-w.cn/Article/details/gtbqbhoxrk.html

[T34] Lua：遍历表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmjcwbni.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pengpengdd.cyou/Article/details/gthwpmkxul.html

[T35] Lua：字典表
来源：http://dali.hywenlv.cn/Article/details/gtpdgisbpt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nwbrower.top/Article/details/gtyymdvyux.html

[T36] Lua：函数
来源：http://dali.0kj1m.cn/Article/details/gtxorwjzxy.html

function add(a, b) return a + b end
来源：http://dali.shzxlz.cn/Article/details/gtipykpbqr.html

[T37] Lua：字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjebizqe.html

"a" .. "b"
来源：http://dali.hfpthk.cn/Article/details/gtxymjegci.html

[T38] Lua：条件
来源：http://dali.yanxiufei.cn/Article/details/gtjtfvqixi.html

if x > 0 then print("正") end
来源：http://dali.andypj.xyz/Article/details/gtsjzevqzr.html

[T39] Lua：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gtjqjdlbnb.html

string.find(s, "%d+")
来源：http://dali.andypj.xyz/Article/details/gttdmgmqdh.html

[T40] Lua：元表
来源：http://dali.zdqjudy.top/Article/details/gtuyvcngcn.html

setmetatable({}, { __index = base })
来源：http://dali.wangshuangyany.cn/Article/details/gtyiojsnoi.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbakqjve.html

print "Hello\n";
来源：http://dali.daxiang520.top/Article/details/gtbccknome.html

[T42] Perl：变量类型
来源：http://dali.fzhhl.top/Article/details/gtjzxligbm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.wangdashe.top/Article/details/gtyizkjbyh.html

[T43] Perl：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtvaeznjyy.html

"值: $a"
来源：http://dali.daxiang520.top/Article/details/gtlpoufcti.html

[T44] Perl：条件
来源：http://dali.zhongyouzk.top/Article/details/gtjyxalgfo.html

if ($a > 0) { print "正"; }
来源：http://dali.daxiang520.top/Article/details/gtezcdtdjs.html

[T45] Perl：数组遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnujzkvb.html

for my $x (@arr) { print $x; }
来源：http://dali.sweek.top/Article/details/gtxxrzlfrq.html

[T46] Perl：哈希操作
来源：http://dali.fzhhl.top/Article/details/gtewqkqwsv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ehwqpu.com/Article/details/gtfgslvvzx.html

[T47] Perl：正则捕获
来源：http://dali.jqgufenzy.top/Article/details/gttitfdvmd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaihfdluk.html

[T48] Perl：正则替换
来源：http://dali.yongpay.top/Article/details/gtjgvqxqsy.html

$s =~ s/old/new/g;
来源：http://dali.guannengcc.top/Article/details/gtebcdccdv.html

[T49] Perl：函数
来源：http://dali.hysaishi.cn/Article/details/gtetuqqwvs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gtncsoxxvk.html

[T50] Perl：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtmkgeuyol.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yanxiufei.cn/Article/details/gtpngehnpb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.wangdashe.top/Article/details/gtmwelzpiy.html

[T51] Scala：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtuzftufhs.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtmccxfvti.html

[T52] Scala：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtyjgruj.html

val a = 1;  var b = 2
来源：http://dali.sweek.top/Article/details/gtbffajynw.html

[T53] Scala：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtscjfxgah.html

s"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gtngkdlaqb.html

[T54] Scala：集合映射
来源：http://dali.dashuyun.cn/Article/details/gtwafxbmgj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.andypj.xyz/Article/details/gtstfhzixa.html

[T55] Scala：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gthjcsgiuj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.daria6918.cn/Article/details/gtrdkzbddi.html

[T56] Scala：样例类
来源：http://dali.9152youxi.cn/Article/details/gthvsinuci.html

case class User(name: String, age: Int)
来源：http://dali.zycfv.cn/Article/details/gtddbbeldk.html

[T57] Scala：模式匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytwzpbfq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hysaishi.cn/Article/details/gtnpxphhty.html

[T58] Scala：函数定义
来源：http://dali.fengsongda.top/Article/details/gtwdiyxzyf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tian-w.cn/Article/details/gtagslypok.html

[T59] Scala：循环
来源：http://dali.hnxiangtu.top/Article/details/gtlhhibwal.html

for (i <- 1 to 10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gtgpvudpxi.html

[T60] Scala：折叠
来源：http://dali.sxryk.cn/Article/details/gtesnwixfk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhengqikj.top/Article/details/gtwlczenqp.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtwrkhbxew.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nwbrower.top/Article/details/gtwsfnucgz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gttdzcmfhk.html

[U01] Py：创建虚拟环境
来源：http://dali.dianchejie.cn/Article/details/gtbtpudusm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yangfankeji.com/Article/details/gtsktsoylz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nwbrower.top/Article/details/gtseqeibho.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yanxiufei.cn/Article/details/gtzmbwbspg.html

[U03] Py：加载 .env 配置
来源：http://dali.shzxlz.cn/Article/details/gtfcoqpubp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.guannengcc.top/Article/details/gtaaukmyvt.html

[U04] Py：变量调试打印
来源：http://dali.xziqi.cn/Article/details/gtluwtjcej.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ydzc1.top/Article/details/gttzackupi.html

[U05] Py：列表去重且保序
来源：http://dali.sxryk.cn/Article/details/gtpfzakxoq.html

list(dict.fromkeys(arr))
来源：http://dali.0kj1m.cn/Article/details/gtydjvrzvm.html

[U06] Py：合并两个字典
来源：http://dali.cashguo.top/Article/details/gtkgkrqpvr.html

{**a, **b}
来源：http://dali.zhengqikj.top/Article/details/gtgdhrsiuc.html

[U07] Py：反转字典键值
来源：http://dali.haohaochexian.top/Article/details/gtmgklpbvm.html

{v: k for k, v in d.items()}
来源：http://dali.cashguo.top/Article/details/gtbkdqtycy.html

[U08] Py：展平二维列表
来源：http://dali.yueranfly.top/Article/details/gtczbmqqbk.html

[y for x in nested for y in x]
来源：http://dali.sufxvd.cn/Article/details/gtnrqbhigs.html

[U09] Py：字典取最大值的键
来源：http://dali.yuxming.cn/Article/details/gtdqsnulxn.html

max(d, key=d.get)
来源：http://dali.sufxvd.cn/Article/details/gttlofyjbi.html

[U10] Py：按值排序字典
来源：http://dali.jyoumei.cn/Article/details/gttqwbxqfd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.daxiang520.top/Article/details/gtffpsnahu.html

[U11] Py：生成器表达式
来源：http://dali.dashuyun.cn/Article/details/gtunbqwbtn.html

(x * 2 for x in arr)
来源：http://dali.jqgfzy.top/Article/details/gtrqcnnklp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hongshengwenyu.top/Article/details/gtpyzutjoo.html

Counter(arr).most_common(3)
来源：http://dali.redwolf501.top/Article/details/gtjxcjntxd.html

[U13] Py：固定长度队列
来源：http://dali.wangdashe.top/Article/details/gtyraqrrxf.html

deque(maxlen=10)
来源：http://dali.cashguo.top/Article/details/gtqphooipg.html

[U14] Py：分组收集到列表
来源：http://dali.guowangkeji.top/Article/details/gtkxxazagz.html

defaultdict(list)
来源：http://dali.quarkkingdee.top/Article/details/gttfrlhdwy.html

[U15] Py：高精度计时
来源：http://dali.daxiang520.top/Article/details/gtfzdytnag.html

t = time.perf_counter()
来源：http://dali.feifeiyinyue.top/Article/details/gtwpiydafm.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangtech.top/Article/details/gtbstmeyux.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yongpay.top/Article/details/gtmtnyomry.html

[U17] Py：初始化日志
来源：http://dali.ppjwa.cn/Article/details/gtpkvloxou.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.iojbl.cn/Article/details/gtxrbyixga.html

[U18] Py：预编译正则
来源：http://dali.daria6918.cn/Article/details/gtocxrfrar.html

pat = re.compile(r"\d+")
来源：http://dali.cdnleiting.top/Article/details/gtiyaadrdt.html

[U19] Py：正则替换带回调
来源：http://dali.316326.xyz/Article/details/gtabjrqmwy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gotoacloud.top/Article/details/gthiskzvsb.html

[U20] Py：缓存函数结果
来源：http://dali.gzhubu.top/Article/details/gtbzuogwdr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ppjwa.cn/Article/details/gtqjmyydmy.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigfzy.top/Article/details/gtlvvkbfrg.html

@contextlib.contextmanager
来源：http://dali.shangyingyoupin.top/Article/details/gtuurwmcqi.html

[U22] Py：矩阵转置
来源：http://dali.hnqzz.top/Article/details/gtmonrrans.html

list(zip(*m))
来源：http://dali.sxryk.cn/Article/details/gtrsghwrgv.html

[U23] Py：分块读取大文件
来源：http://dali.havefunace.top/Article/details/gtslmywctm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.wangdashe.top/Article/details/gtydyhojru.html

[U24] Py：路径操作
来源：http://dali.dashuyun.cn/Article/details/gtibnrnlhh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gteqhjqbse.html

[U25] Py：CSV 按字典读
来源：http://dali.yongpay.top/Article/details/gtokcouqmb.html

csv.DictReader(f)
来源：http://dali.snrcjt.cn/Article/details/gtikttbqja.html

[U26] Py：并发下载
来源：http://dali.yj20258888.top/Article/details/gtbrqaozei.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zdqjudy.top/Article/details/gtswkuysko.html

[U27] Py：异步 HTTP
来源：http://dali.gaohongyu789.top/Article/details/gtjvvcxtyf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenjidiqi.icu/Article/details/gtdwipxfto.html

[U28] Py：类型别名
来源：http://dali.zycfv.cn/Article/details/gtqjysbxxc.html

UserId = int
来源：http://dali.smart0.xyz/Article/details/gttfazrmnz.html

[U29] Py：属性校验
来源：http://dali.sxryk.cn/Article/details/gtxesnwxkz.html

@property 与 @x.setter 配合
来源：http://dali.0kj1m.cn/Article/details/gtmwxowuaa.html

[U30] Py：数据类
来源：http://dali.jqgfzy.top/Article/details/gtcbrhjmfm.html

@dataclass(slots=True)
来源：http://dali.jlsjyb.cn/Article/details/gtuhjhdvkg.html

[U31] Py：单测
来源：http://dali.wangdashe.top/Article/details/gtcvqymire.html

python -m pytest -q
来源：http://dali.fengsongda.top/Article/details/gtaxbththt.html

[U32] Py：代码格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnmzsnni.html

ruff format . && ruff check --fix .
来源：http://dali.shuidangran.top/Article/details/gtvjkipwxc.html

[U33] Py：打包发布
来源：http://dali.guannengcc.top/Article/details/gtqgdggdfo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj202588.top/Article/details/gtvywzbhgr.html

[U34] Py：判断编码
来源：http://dali.316326.xyz/Article/details/gtjlshooqx.html

chardet.detect(raw)
来源：http://dali.jinqigufen.top/Article/details/gtnygqwjyx.html

[U35] Py：发送邮件
来源：http://dali.aizwys.cn/Article/details/gtzeiyfpih.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhongyouzk.top/Article/details/gtgonyuxwo.html

[U36] Py：定时任务
来源：http://dali.xziqi.cn/Article/details/gtyqhvlckv.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj202588.top/Article/details/gtavqncvhj.html

[U37] Py：读写 Excel
来源：http://dali.0kj1m.cn/Article/details/gtuvfyrsqz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cdnleiting.top/Article/details/gtppdnpagr.html

[U38] Py：获取脚本所在目录
来源：http://dali.quarkkingdee.top/Article/details/gtjmghofqh.html

Path(__file__).resolve().parent
来源：http://dali.chenzaomai.com/Article/details/gtnhqggfzl.html

[U39] Py：判断是否在交互环境
来源：http://dali.ivvv.top/Article/details/gtjunlizgt.html

sys.stdout.isatty()
来源：http://dali.zhengqikj.top/Article/details/gtfsjjepmb.html

[U40] Py：打印到标准错误
来源：http://dali.zhiwuduotai.top/Article/details/gtbwulabii.html

print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gtgoohhtkx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenzaomai.com/Article/details/gtkavdetmj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shangyingyoupin.top/Article/details/gtrfjazfza.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jlsjyb.cn/Article/details/gtpbtdgbbl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zycfv.cn/Article/details/gttugtscsf.html

[U43] PHP：声明命名空间
来源：http://dali.jlsjyb.cn/Article/details/gtgtnzfuxb.html

namespace App\Http;
来源：http://dali.cashguo.top/Article/details/gteaxvqisy.html

[U44] PHP：开启严格类型
来源：http://dali.mhx1999.top/Article/details/gteivfayzs.html

declare(strict_types=1);
来源：http://dali.daxiang520.top/Article/details/gtapliyszq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.dashuyun.cn/Article/details/gtkyzgsgyf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtvwcvtays.html

[U46] PHP：可空类型
来源：http://dali.aibaodan.cn/Article/details/gtalhrtyzz.html

?string $name = null
来源：http://dali.hongshengwenyu.top/Article/details/gtyuawyiyy.html

[U47] PHP：联合类型
来源：http://dali.yanxiufei.cn/Article/details/gtabsjixsd.html

int|string $id
来源：http://dali.xuetiantiany.cn/Article/details/gtpamqnsra.html

[U48] PHP：纯枚举
来源：http://dali.zdqjudy.top/Article/details/gtegkyziyd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yangfankeji.com/Article/details/gtuudnoiwa.html

[U49] PHP：只读属性
来源：http://dali.dashuyun.cn/Article/details/gtgtkhchjx.html

public readonly string $name
来源：http://dali.zycfv.cn/Article/details/gtaahrcmro.html

[U50] PHP：构造器属性提升
来源：http://dali.hfpthk.cn/Article/details/gtxkwqposk.html

public function __construct(private int $id) {}
来源：http://dali.zhengqikj.top/Article/details/gtunwegymm.html

[U51] PHP：数组解构
来源：http://dali.svipenyu.cn/Article/details/gtecwbwebc.html

[$a, $b] = $arr;
来源：http://dali.kuanghao11.cn/Article/details/gtrduqbtjv.html

[U52] PHP：箭头函数
来源：http://dali.hfpthk.cn/Article/details/gttjwebywk.html

$double = fn($x) => $x * 2;
来源：http://dali.jyoumei.cn/Article/details/gtkmtppgpr.html

[U53] PHP：空合并运算符
来源：http://dali.meibo888.top/Article/details/gtqjmblaqx.html

$v = $a ?? $b ?? "default";
来源：http://dali.hysaishi.cn/Article/details/gtdkywcqqc.html

[U54] PHP：空安全调用
来源：http://dali.shzxlz.cn/Article/details/gtxkzoqjry.html

$obj?->method()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtguygarbb.html

[U55] PHP：match 表达式
来源：http://dali.yuxming.cn/Article/details/gttdnmelwb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinqigufen.top/Article/details/gtirupiepr.html

[U56] PHP：命名参数
来源：http://dali.hywenlv.cn/Article/details/gtasbgbnsl.html

f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gtrvagogpt.html

[U57] PHP：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtrqpmpubs.html

"值: {$a}"
来源：http://dali.gogol.net.cn/Article/details/gtjyjuxbvd.html

[U58] PHP：数组三件套
来源：http://dali.ybcxt.top/Article/details/gtygnxczib.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtpmmaraol.html

[U59] PHP：自定义排序
来源：http://dali.kuanghao11.cn/Article/details/gttcjniqec.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gtkvoodhyw.html

[U60] PHP：JSON 编解码
来源：http://dali.c1oappe.top/Article/details/gtaotcekdc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jqgufenzy.top/Article/details/gtooelvvtw.html

[U61] PHP：正则
来源：http://dali.yueranfly.top/Article/details/gtxbgvdlsd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gttsirvyya.html

[U62] PHP：日期对象
来源：http://dali.guannengcc.top/Article/details/gtptheanvs.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shuidangran.top/Article/details/gtnwuklixn.html

[U63] PHP：文件读写
来源：http://dali.zhixingplan.top/Article/details/gtlmkzbmpr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.svipenyu.cn/Article/details/gtywszxckj.html

[U64] PHP：目录遍历
来源：http://dali.daria6918.cn/Article/details/gtrvswgwhc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xuetiantiany.cn/Article/details/gtthrzxbhn.html

[U65] PHP：会话
来源：http://dali.cashguo.top/Article/details/gtbzfmzmpd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtsrzbxmhw.html

[U66] PHP：设置 Cookie
来源：http://dali.ybcxt.top/Article/details/gtzkeybohr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jiagoushi.top/Article/details/gtvdvtzulj.html

[U67] PHP：处理文件上传
来源：http://dali.nanxinkj.top/Article/details/gtbwzafjhy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhengqikj.top/Article/details/gtvahkpyil.html

[U68] PHP：PDO 连接
来源：http://dali.jyoumei.cn/Article/details/gtxlemeoln.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpengthe.html

[U69] PHP：PDO 预处理
来源：http://dali.yueranfly.top/Article/details/gtgqdtxxmj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sysykeji.top/Article/details/gterwfkzvu.html

[U70] PHP：PDO 事务
来源：http://dali.nanxinkj.top/Article/details/gtzwbkrsvu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.shangyingyoupin.top/Article/details/gtsyvkwptt.html

[U71] PHP：抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukbsksls.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslimxrrw.html

[U72] PHP：写错误日志
来源：http://dali.sufxvd.cn/Article/details/gtrwtulxoi.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yj20258.top/Article/details/gthqgsyjbv.html


<!-- 参考信息 -->