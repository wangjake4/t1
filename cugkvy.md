代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.guowangkeji.top/Article/details/gtseifronk.html

[S49] C++：写文件
来源：http://dali.hnqzz.top/Article/details/gtjbyxjbdt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yangfankeji.com/Article/details/gtykmebauy.html

[S50] C++：格式化数字
来源：http://dali.nanxinkj.top/Article/details/gthickapam.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtmnwuxvao.html

[S51] C++：显式类型转换
来源：http://dali.yvedp.cn/Article/details/gtxqjrvttc.html

static_cast<double>(a) / b
来源：http://dali.shuidangran.top/Article/details/gttukjsvrs.html

[S52] C++：const 与 noexcept
来源：http://dali.tian-w.cn/Article/details/gtigwrcegy.html

int size() const noexcept { return n_; }
来源：http://dali.yonumen.top/Article/details/gtjlugbypf.html

[S53] C++：移动语义
来源：http://dali.chenlongwang.top/Article/details/gtnprkbhxr.html

std::vector<int> w = std::move(v);
来源：http://dali.dianchejie.cn/Article/details/gtnmfmxctc.html

[S54] C++：异常处理
来源：http://dali.daria6918.cn/Article/details/gtdzsplcpl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ehwqpu.com/Article/details/gtjrtpfhbv.html

[S55] C++：结构化绑定
来源：http://dali.redwolf501.top/Article/details/gtjocscrdx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gotoacloud.top/Article/details/gtlfofjhwt.html

[S56] C++：optional
来源：http://dali.xuanzx.com/Article/details/gtshvvdqbt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gotoacloud.top/Article/details/gtghbbrlvk.html

[S57] C++：编译期常量
来源：http://dali.wangshuangyany.cn/Article/details/gtdbbylgyy.html

constexpr int N = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtnclvvvsf.html

[S58] C++：命名空间
来源：http://dali.cucudq.cn/Article/details/gtjrglmnar.html

namespace ns { int f() { return 1; } }
来源：http://dali.9152youxi.cn/Article/details/gtwyjwczpv.html

[S59] C++：静态断言
来源：http://dali.nanxinkj.top/Article/details/gtaxfrwaaq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvzhrmue.html

[S60] C++：遍历并删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhwkiirc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxinkj.top/Article/details/gtvtazkjpf.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtbzdnzsdd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hammf.cn/Article/details/gtzbzsbdne.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtbyqauviv.html

[T01] Kotlin：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtjlflaywj.html

println("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtubuaysbf.html

[T02] Kotlin：变量
来源：http://dali.feifeiyinyue.top/Article/details/gtxjgduzxf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shzxlz.cn/Article/details/gtemxsvylk.html

[T03] Kotlin：字符串模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmixtibw.html

"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gtiirwwfxq.html

[T04] Kotlin：空安全
来源：http://dali.ppjwa.cn/Article/details/gtykatwngg.html

val n: String? = null;  n?.length
来源：http://dali.quarkkingdee.top/Article/details/gtbpofgwxk.html

[T05] Kotlin：when 表达式
来源：http://dali.dashuyun.cn/Article/details/gtxmxdvjyd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenlongwang.top/Article/details/gtjorjxwaa.html

[T06] Kotlin：集合映射
来源：http://dali.fzhhl.top/Article/details/gtewjijgvg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtfayppmng.html

[T07] Kotlin：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gtkwwubdqj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhengqikj.top/Article/details/gtrawpjdeu.html

[T08] Kotlin：数据类
来源：http://dali.chenlongwang.top/Article/details/gtuvpvfqra.html

data class User(val name: String, val age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnuvoqvn.html

[T09] Kotlin：扩展函数
来源：http://dali.svipenyu.cn/Article/details/gtvgwwkbsk.html

fun String.exclaim() = this + "!"
来源：http://dali.bjfxy.top/Article/details/gtpbdeumok.html

[T10] Kotlin：默认参数
来源：http://dali.meibo888.top/Article/details/gtcwhifttu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pycfn.com/Article/details/gtdpdpdnst.html

[T11] Kotlin：协程
来源：http://dali.ybcxt.top/Article/details/gtqmszscmv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.haohaochexian.top/Article/details/gtigejqkbj.html

[T12] Kotlin：解构声明
来源：http://dali.sufxvd.cn/Article/details/gtrycdqfes.html

val (a, b) = Pair(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtisclprjd.html

[T13] Kotlin：只读 Map
来源：http://dali.yuanzhike.top/Article/details/gtogamnbbg.html

val m = mapOf("a" to 1)
来源：http://dali.nanxinkj.top/Article/details/gtqwmvopar.html

[T14] Kotlin：循环
来源：http://dali.ybcxt.top/Article/details/gthhzqqiho.html

for (i in 1..10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gthzuofabe.html

[T15] Kotlin：接口
来源：http://dali.xuanzx.com/Article/details/gtzddfpxtb.html

interface Shape { fun area(): Double }
来源：http://dali.wangshuangyany.cn/Article/details/gttonnscyl.html

[T16] Swift：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwinfylkl.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtsmstyjpx.html

[T17] Swift：变量与常量
来源：http://dali.hywenlv.cn/Article/details/gtjjmmaiaw.html

var a = 1;  let b = 2
来源：http://dali.jqgufenzy.top/Article/details/gttsbkbuaj.html

[T18] Swift：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gtqlncbdrz.html

"值: \(b)"
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjsrfcjf.html

[T19] Swift：可选绑定
来源：http://dali.yuanzhike.top/Article/details/gtacipzubf.html

if let n = opt { print(n) }
来源：http://dali.quarkkingdee.top/Article/details/gtvuqnbjel.html

[T20] Swift：数组操作
来源：http://dali.yonumen.top/Article/details/gtuetlqzep.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daxiang520.top/Article/details/gtnwnlybgq.html

[T21] Swift：遍历
来源：http://dali.nanxuanxn.top/Article/details/gtgnfpvslh.html

for x in a { print(x) }
来源：http://dali.pycfn.com/Article/details/gtfuzcksue.html

[T22] Swift：字典
来源：http://dali.zhoulong.xyz/Article/details/gtreqqtvnz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hfpthk.cn/Article/details/gtbrrogldb.html

[T23] Swift：函数
来源：http://dali.xuanzx.com/Article/details/gtwxrjdcwu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhongyouzk.top/Article/details/gtryjdpztz.html

[T24] Swift：闭包
来源：http://dali.aibaodan.cn/Article/details/gtdtqxngwv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtqfhzdsib.html

[T25] Swift：结构体
来源：http://dali.daria6918.cn/Article/details/gtrqqnlxbl.html

struct P { var x: Int }
来源：http://dali.sxryk.cn/Article/details/gtpvlfmrfd.html

[T26] Swift：类与重写
来源：http://dali.yuanzhike.top/Article/details/gtvlricmtm.html

class A: Base { override func f() {} }
来源：http://dali.jqgufenzy.top/Article/details/gtygzjgulv.html

[T27] Swift：错误处理
来源：http://dali.jqgfzy.top/Article/details/gtjxtzkbwv.html

do { try f() } catch { print(error) }
来源：http://dali.cdnleiting.top/Article/details/gtjpbxzjum.html

[T28] Swift：枚举
来源：http://dali.ppjwa.cn/Article/details/gtenhjflmb.html

enum Color { case red, green }
来源：http://dali.yj202588.top/Article/details/gtzfdddqvf.html

[T29] Swift：guard 提前返回
来源：http://dali.havefunace.top/Article/details/gtyzfhsphb.html

guard let x = opt else { return }
来源：http://dali.hywenlv.cn/Article/details/gtuhinropj.html

[T30] Swift：协议
来源：http://dali.dashuyun.cn/Article/details/gtchvipdpt.html

protocol Shape { func area() -> Double }
来源：http://dali.hfpthk.cn/Article/details/gtpniapdts.html

[T31] Lua：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlaooelca.html

print("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtboxafqxv.html

[T32] Lua：局部变量
来源：http://dali.sxryk.cn/Article/details/gtoggfphlu.html

local a = 1
来源：http://dali.hfpthk.cn/Article/details/gtizyxsswu.html

[T33] Lua：表（数组）
来源：http://dali.andypj.xyz/Article/details/gtcnbmkcdp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guowangkeji.top/Article/details/gtxwkywgno.html

[T34] Lua：遍历表
来源：http://dali.0kj1m.cn/Article/details/gtvlwfiboa.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.fengsongda.top/Article/details/gtsimnwqjw.html

[T35] Lua：字典表
来源：http://dali.nwbrower.top/Article/details/gtvkhcecml.html

local d = { a = 1 };  d.b = 2
来源：http://dali.smart0.xyz/Article/details/gtptacgxec.html

[T36] Lua：函数
来源：http://dali.daxiang520.top/Article/details/gthueujumi.html

function add(a, b) return a + b end
来源：http://dali.feifeiyinyue.top/Article/details/gticevhjlh.html

[T37] Lua：字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gtlocqzwaj.html

"a" .. "b"
来源：http://dali.jinqigfzy.top/Article/details/gtpjxmgwdf.html

[T38] Lua：条件
来源：http://dali.yj20258888.top/Article/details/gtnhfudrwx.html

if x > 0 then print("正") end
来源：http://dali.cqqwz.cn/Article/details/gtaquieeyl.html

[T39] Lua：模式匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtqiwqwrau.html

string.find(s, "%d+")
来源：http://dali.sweek.top/Article/details/gthhvzgryd.html

[T40] Lua：元表
来源：http://dali.bjfxy.top/Article/details/gtyvvnootj.html

setmetatable({}, { __index = base })
来源：http://dali.yj20258888.top/Article/details/gtidsxojxx.html

[T41] Perl：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtkikoxrls.html

print "Hello\n";
来源：http://dali.birdmap.top/Article/details/gtvmjhvgxg.html

[T42] Perl：变量类型
来源：http://dali.yuxming.cn/Article/details/gtuqnskmie.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.9152youxi.cn/Article/details/gtyiamdvcx.html

[T43] Perl：字符串插值
来源：http://dali.yonumen.top/Article/details/gtjylwiygo.html

"值: $a"
来源：http://dali.sysykeji.top/Article/details/gtqodlvrla.html

[T44] Perl：条件
来源：http://dali.zhiwuduotai.top/Article/details/gtqlctnugw.html

if ($a > 0) { print "正"; }
来源：http://dali.yonumen.top/Article/details/gtxejvgeml.html

[T45] Perl：数组遍历
来源：http://dali.yanxiufei.cn/Article/details/gtiwlllomh.html

for my $x (@arr) { print $x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtjdwrmsie.html

[T46] Perl：哈希操作
来源：http://dali.feifeiyinyue.top/Article/details/gtuwguvtxy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpxhjglje.html

[T47] Perl：正则捕获
来源：http://dali.ybcxt.top/Article/details/gthamovfgl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yanxiufei.cn/Article/details/gtndkbgvxw.html

[T48] Perl：正则替换
来源：http://dali.cdnleiting.top/Article/details/gtsrjohfjm.html

$s =~ s/old/new/g;
来源：http://dali.guowangkeji.top/Article/details/gtzgyceoej.html

[T49] Perl：函数
来源：http://dali.fengsongda.top/Article/details/gtgvmuxppi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtxcedgk.html

[T50] Perl：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtqfdumnvm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhongyouzk.top/Article/details/gtwvcpeekw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj20258888.top/Article/details/gtwfwgahki.html

[T51] Scala：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtyrinrluf.html

println("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtfkgejtae.html

[T52] Scala：变量
来源：http://dali.yangfankeji.com/Article/details/gtdnhnmgug.html

val a = 1;  var b = 2
来源：http://dali.jyoumei.cn/Article/details/gtiuefllfg.html

[T53] Scala：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtuuhcncrf.html

s"值: $b"
来源：http://dali.yongpay.top/Article/details/gtmslmegjx.html

[T54] Scala：集合映射
来源：http://dali.gotoacloud.top/Article/details/gthzpuzqve.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.guannengcc.top/Article/details/gtdsxmxyik.html

[T55] Scala：集合过滤
来源：http://dali.pycfn.com/Article/details/gtkcwsogse.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hnxiangtu.top/Article/details/gtsqgapbmp.html

[T56] Scala：样例类
来源：http://dali.yangfankeji.com/Article/details/gtqfjzzwrg.html

case class User(name: String, age: Int)
来源：http://dali.jiagoushi.top/Article/details/gtghsklirz.html

[T57] Scala：模式匹配
来源：http://dali.yongpay.top/Article/details/gtctunakbe.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnxiangtu.top/Article/details/gtmbbfnats.html

[T58] Scala：函数定义
来源：http://dali.zhixingplan.top/Article/details/gtorbwbccn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nwbrower.top/Article/details/gtrzabakct.html

[T59] Scala：循环
来源：http://dali.jianghu66.top/Article/details/gtxejbpeep.html

for (i <- 1 to 10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gtnvagmivw.html

[T60] Scala：折叠
来源：http://dali.jinqigufen.top/Article/details/gtizbfprdm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.svipenyu.cn/Article/details/gtmbrpjyjj.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgglvrcdd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhixingplan.top/Article/details/gtdhettwjj.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtvndytwql.html

[U01] Py：创建虚拟环境
来源：http://dali.feifeiyinyue.top/Article/details/gtjajkclic.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zdqjudy.top/Article/details/gtoueqcmfz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sufxvd.cn/Article/details/gtjdryicdj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jiagoushi.top/Article/details/gtzvxjhfue.html

[U03] Py：加载 .env 配置
来源：http://dali.yueranfly.top/Article/details/gtyeaarvnz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.dashuyun.cn/Article/details/gtcrmgfvnb.html

[U04] Py：变量调试打印
来源：http://dali.meibo888.top/Article/details/gtzjwxxnye.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuanzx.com/Article/details/gtulmlkmbm.html

[U05] Py：列表去重且保序
来源：http://dali.xinyue.icu/Article/details/gtzfzjfqvv.html

list(dict.fromkeys(arr))
来源：http://dali.cheryme.top/Article/details/gtgdtnzpwp.html

[U06] Py：合并两个字典
来源：http://dali.guannengcc.top/Article/details/gtvfnkocjt.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gtzxgnrasd.html

[U07] Py：反转字典键值
来源：http://dali.nanxuanxn.top/Article/details/gtibnfqlyi.html

{v: k for k, v in d.items()}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukkslfow.html

[U08] Py：展平二维列表
来源：http://dali.jyoumei.cn/Article/details/gtmoedrlcn.html

[y for x in nested for y in x]
来源：http://dali.zhiwuduotai.top/Article/details/gtaqzxsluv.html

[U09] Py：字典取最大值的键
来源：http://dali.yuanzhike.top/Article/details/gtwfwjjxdm.html

max(d, key=d.get)
来源：http://dali.aibaodan.cn/Article/details/gtoszhuddj.html

[U10] Py：按值排序字典
来源：http://dali.xuetiantiany.cn/Article/details/gtgdghhfzf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ivvv.top/Article/details/gtwcpylpdn.html

[U11] Py：生成器表达式
来源：http://dali.zycfv.cn/Article/details/gtgouluhfn.html

(x * 2 for x in arr)
来源：http://dali.nanxinkj.top/Article/details/gtevbmoesa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sufxvd.cn/Article/details/gtgmteehed.html

Counter(arr).most_common(3)
来源：http://dali.hysaishi.cn/Article/details/gtiezwozyl.html

[U13] Py：固定长度队列
来源：http://dali.jianghu66.top/Article/details/gtspdbgkmp.html

deque(maxlen=10)
来源：http://dali.zhoulong.xyz/Article/details/gtegmgxkjm.html

[U14] Py：分组收集到列表
来源：http://dali.havefunace.top/Article/details/gtojmuwkfe.html

defaultdict(list)
来源：http://dali.0kj1m.cn/Article/details/gtinuwzhmw.html

[U15] Py：高精度计时
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmkadnbt.html

t = time.perf_counter()
来源：http://dali.sxryk.cn/Article/details/gtkkxwlhbv.html

[U16] Py：命令行参数解析
来源：http://dali.jqgfzy.top/Article/details/gtnsbitqsb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yonumen.top/Article/details/gtusxcagym.html

[U17] Py：初始化日志
来源：http://dali.gzhubu.top/Article/details/gtrcletiax.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shzxlz.cn/Article/details/gtibkdvoyk.html

[U18] Py：预编译正则
来源：http://dali.hnxiangtu.top/Article/details/gtbuueaucb.html

pat = re.compile(r"\d+")
来源：http://dali.dashuyun.cn/Article/details/gtcxadruol.html

[U19] Py：正则替换带回调
来源：http://dali.shangyingyoupin.top/Article/details/gtaoegwuaz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuanzhike.top/Article/details/gttumnjhds.html

[U20] Py：缓存函数结果
来源：http://dali.cqqwz.cn/Article/details/gtxftumoki.html

@functools.lru_cache(maxsize=None)
来源：http://dali.0kj1m.cn/Article/details/gtxabrrkxg.html

[U21] Py：自定义上下文管理器
来源：http://dali.guowangkeji.top/Article/details/gtmdiupyju.html

@contextlib.contextmanager
来源：http://dali.yuxming.cn/Article/details/gtgrxldqou.html

[U22] Py：矩阵转置
来源：http://dali.hywenlv.cn/Article/details/gtuqmbaukj.html

list(zip(*m))
来源：http://dali.jqgufenzy.top/Article/details/gtyzumfmhq.html

[U23] Py：分块读取大文件
来源：http://dali.iojbl.cn/Article/details/gtqyaxduno.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.bjfxy.top/Article/details/gtakoyhzkq.html

[U24] Py：路径操作
来源：http://dali.svipenyu.cn/Article/details/gtnnuwrzpw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.0kj1m.cn/Article/details/gtlcltjyqu.html

[U25] Py：CSV 按字典读
来源：http://dali.redwolf501.top/Article/details/gtacbjnxyu.html

csv.DictReader(f)
来源：http://dali.feifeiyinyue.top/Article/details/gtjsltxjyj.html

[U26] Py：并发下载
来源：http://dali.hammf.cn/Article/details/gtsrrosovv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sxryk.cn/Article/details/gtbhxcwlaf.html

[U27] Py：异步 HTTP
来源：http://dali.jiagoushi.top/Article/details/gtcwzvchhp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuxming.cn/Article/details/gtenthzaxx.html

[U28] Py：类型别名
来源：http://dali.yvedp.cn/Article/details/gtlezhokqw.html

UserId = int
来源：http://dali.tanke756.top/Article/details/gtkmnmyawr.html

[U29] Py：属性校验
来源：http://dali.meibo888.top/Article/details/gtzixouegc.html

@property 与 @x.setter 配合
来源：http://dali.vqdsnc.cn/Article/details/gtupbjjxxc.html

[U30] Py：数据类
来源：http://dali.shangyingyoupin.top/Article/details/gtlnetpdcx.html

@dataclass(slots=True)
来源：http://dali.yuanzhike.top/Article/details/gtssbbihvi.html

[U31] Py：单测
来源：http://dali.hysaishi.cn/Article/details/gtqkretohy.html

python -m pytest -q
来源：http://dali.quarkkingdee.top/Article/details/gtprlqrbik.html

[U32] Py：代码格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtmgogquue.html

ruff format . && ruff check --fix .
来源：http://dali.quarkkingdee.top/Article/details/gtoztkwxgb.html

[U33] Py：打包发布
来源：http://dali.c1oappe.top/Article/details/gtlqvvnqev.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sxryk.cn/Article/details/gtwhrxnzlc.html

[U34] Py：判断编码
来源：http://dali.sysykeji.top/Article/details/gttphuxlyg.html

chardet.detect(raw)
来源：http://dali.yj202588.top/Article/details/gtmtolvamo.html

[U35] Py：发送邮件
来源：http://dali.hnqzz.top/Article/details/gtoesrqyts.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.316326.xyz/Article/details/gtgzlkgpuy.html

[U36] Py：定时任务
来源：http://dali.shanyushiyangtech.top/Article/details/gtegrjxavj.html

schedule.every(10).minutes.do(job)
来源：http://dali.aizwys.cn/Article/details/gtlemmtxqn.html

[U37] Py：读写 Excel
来源：http://dali.cdnleiting.top/Article/details/gtxpurywgd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.daria6918.cn/Article/details/gtbrtlkzzs.html

[U38] Py：获取脚本所在目录
来源：http://dali.cucudq.cn/Article/details/gtmsuwtkme.html

Path(__file__).resolve().parent
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyuibdmm.html

[U39] Py：判断是否在交互环境
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjclutyk.html

sys.stdout.isatty()
来源：http://dali.kuanghao11.cn/Article/details/gtjozhhfce.html

[U40] Py：打印到标准错误
来源：http://dali.meibo888.top/Article/details/gtdfgbomsn.html

print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gtytrgmlzq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cucudq.cn/Article/details/gtvbijemxa.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gogol.net.cn/Article/details/gtummmuglg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ivvv.top/Article/details/gtnqeugwap.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shzxlz.cn/Article/details/gtuzhokubu.html

[U43] PHP：声明命名空间
来源：http://dali.meibo888.top/Article/details/gtjwjkyilw.html

namespace App\Http;
来源：http://dali.yvedp.cn/Article/details/gtbhzseqwr.html

[U44] PHP：开启严格类型
来源：http://dali.zhengqikj.top/Article/details/gtiqztpfuj.html

declare(strict_types=1);
来源：http://dali.hnxiangtu.top/Article/details/gtsjrikjhg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cashguo.top/Article/details/gtinvvnwkz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtfhokubig.html

[U46] PHP：可空类型
来源：http://dali.ppjwa.cn/Article/details/gtunmajead.html

?string $name = null
来源：http://dali.smart0.xyz/Article/details/gtrebibbrl.html

[U47] PHP：联合类型
来源：http://dali.pycfn.com/Article/details/gthztkqegd.html

int|string $id
来源：http://dali.haohaochexian.top/Article/details/gtgcuarhvs.html

[U48] PHP：纯枚举
来源：http://dali.birdmap.top/Article/details/gtuztjdshr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.guowangkeji.top/Article/details/gtlmhzycyh.html

[U49] PHP：只读属性
来源：http://dali.xylfe.cn/Article/details/gtprzmfkrk.html

public readonly string $name
来源：http://dali.sysykeji.top/Article/details/gtfvhwatsx.html

[U50] PHP：构造器属性提升
来源：http://dali.guowangkeji.top/Article/details/gttvfzgzaw.html

public function __construct(private int $id) {}
来源：http://dali.dashuyun.cn/Article/details/gtckpdjogp.html

[U51] PHP：数组解构
来源：http://dali.aibaodan.cn/Article/details/gtsjzmmzem.html

[$a, $b] = $arr;
来源：http://dali.hysaishi.cn/Article/details/gtpaiqsboi.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gtfftjiavz.html

$double = fn($x) => $x * 2;
来源：http://dali.jianghu66.top/Article/details/gtgazsmdtl.html

[U53] PHP：空合并运算符
来源：http://dali.sysykeji.top/Article/details/gtolapoqjn.html

$v = $a ?? $b ?? "default";
来源：http://dali.nanxinkj.top/Article/details/gtrbwbdrmy.html

[U54] PHP：空安全调用
来源：http://dali.wangshuangyany.cn/Article/details/gtqldjpjgm.html

$obj?->method()
来源：http://dali.chenzaomai.com/Article/details/gtygnrwbmj.html

[U55] PHP：match 表达式
来源：http://dali.vqdsnc.cn/Article/details/gtlnjrmngx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xuanzx.com/Article/details/gtkdvghdup.html

[U56] PHP：命名参数
来源：http://dali.meibo888.top/Article/details/gtreosudki.html

f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gtsgiinhlj.html

[U57] PHP：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtchnphxiw.html

"值: {$a}"
来源：http://dali.zycfv.cn/Article/details/gtwoylcqoc.html

[U58] PHP：数组三件套
来源：http://dali.hfpthk.cn/Article/details/gtwgmhnyda.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.daxiang520.top/Article/details/gtdhfxxrpn.html

[U59] PHP：自定义排序
来源：http://dali.cdnleiting.top/Article/details/gtrcxcpjqr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigfzy.top/Article/details/gtwsfwyaox.html

[U60] PHP：JSON 编解码
来源：http://dali.xuetiantiany.cn/Article/details/gttbhujncj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yangfankeji.com/Article/details/gtwacslplu.html

[U61] PHP：正则
来源：http://dali.tanke756.top/Article/details/gtctcmsfda.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtsarieieb.html

[U62] PHP：日期对象
来源：http://dali.tian-w.cn/Article/details/gtnopgsxxp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cdnleiting.top/Article/details/gtbdtisdae.html

[U63] PHP：文件读写
来源：http://dali.shzxlz.cn/Article/details/gtlmlqtoan.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sweek.top/Article/details/gtjfkiekok.html

[U64] PHP：目录遍历
来源：http://dali.shuidangran.top/Article/details/gtbwzgiveu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.daxiang520.top/Article/details/gtxbkvbkvs.html

[U65] PHP：会话
来源：http://dali.hywenlv.cn/Article/details/gtrzacjpup.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtbgwpltau.html

[U66] PHP：设置 Cookie
来源：http://dali.sweek.top/Article/details/gtdhayxgxu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yanxiufei.cn/Article/details/gtrcvppxxi.html

[U67] PHP：处理文件上传
来源：http://dali.hnqzz.top/Article/details/gthwtuqbwl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.snrcjt.cn/Article/details/gtepmczzyk.html

[U68] PHP：PDO 连接
来源：http://dali.xziqi.cn/Article/details/gtnevoznzf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ivvv.top/Article/details/gtexdlrldu.html

[U69] PHP：PDO 预处理
来源：http://dali.guannengcc.top/Article/details/gtezqkygfp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hysaishi.cn/Article/details/gtixqhqiwa.html

[U70] PHP：PDO 事务
来源：http://dali.daria6918.cn/Article/details/gtuqoqunzy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jianghu66.top/Article/details/gtmvhhqkvd.html

[U71] PHP：抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtxjtwllgh.html

throw new RuntimeException("失败", 500);
来源：http://dali.sysykeji.top/Article/details/gtqlsatxkd.html

[U72] PHP：写错误日志
来源：http://dali.chenlongwang.top/Article/details/gtbouzohga.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gogol.net.cn/Article/details/gtggcpwfjp.html

[U73] PHP：读取 ini 配置
来源：http://dali.wangshuangyany.cn/Article/details/gtcjtybigf.html

parse_ini_file("config.ini", true)
来源：http://dali.quarkkingdee.top/Article/details/gtuidbvnxg.html

[U74] PHP：读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gtewjrpnoj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jlsjyb.cn/Article/details/gtjbcluxff.html


<!-- 参考信息 -->