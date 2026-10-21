代发 wailian999

[S43] C++：智能指针
来源：http://dali.ehwqpu.com/Article/details/gtcrmkzjtr.html

auto p = std::make_unique<int>(5);
来源：http://dali.hywenlv.cn/Article/details/gtblqyfqpf.html

[S44] C++：引用传参
来源：http://dali.ivvv.top/Article/details/gtmvqdgvcz.html

void inc(int &x) { ++x; }
来源：http://dali.chenzaomai.com/Article/details/gtydepxxzn.html

[S45] C++：lambda
来源：http://dali.iojbl.cn/Article/details/gtbpmmzmcz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangshuangyany.cn/Article/details/gtuddoccpo.html

[S46] C++：函数模板
来源：http://dali.chenjidiqi.icu/Article/details/gttqrvnrqs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.vqdsnc.cn/Article/details/gtwsarqrsy.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj202588.top/Article/details/gttontpttn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nwbrower.top/Article/details/gtqyevwcve.html

[S48] C++：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtskgropft.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinghuilouyu.cn/Article/details/gtghqkeofb.html

while (std::getline(in, line)) { }
来源：http://dali.yanxiufei.cn/Article/details/gtigdirtrq.html

[S49] C++：写文件
来源：http://dali.xuanzx.com/Article/details/gthcntiwbj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuanzx.com/Article/details/gttqkjqqwy.html

[S50] C++：格式化数字
来源：http://dali.jinqigufen.top/Article/details/gtwkvsztqe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtzirwjyll.html

[S51] C++：显式类型转换
来源：http://dali.ybcxt.top/Article/details/gtgbueiwhd.html

static_cast<double>(a) / b
来源：http://dali.cheryme.top/Article/details/gtavankhqv.html

[S52] C++：const 与 noexcept
来源：http://dali.yonumen.top/Article/details/gtfavflxbo.html

int size() const noexcept { return n_; }
来源：http://dali.feifeiyinyue.top/Article/details/gtarwchale.html

[S53] C++：移动语义
来源：http://dali.jinqigfzy.top/Article/details/gtuplqwokr.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigufen.top/Article/details/gthywinsap.html

[S54] C++：异常处理
来源：http://dali.yvedp.cn/Article/details/gtonhvuwmy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gogol.net.cn/Article/details/gtucizauet.html

[S55] C++：结构化绑定
来源：http://dali.vqdsnc.cn/Article/details/gtresfqsgv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fzhhl.top/Article/details/gtxprxhzsd.html

[S56] C++：optional
来源：http://dali.ehwqpu.com/Article/details/gtwxcltetg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.kuanghao11.cn/Article/details/gtswzuywmx.html

[S57] C++：编译期常量
来源：http://dali.guannengcc.top/Article/details/gtwivtshiz.html

constexpr int N = 10;
来源：http://dali.jqgufenzy.top/Article/details/gttnlxminf.html

[S58] C++：命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gtodnweryd.html

namespace ns { int f() { return 1; } }
来源：http://dali.hywenlv.cn/Article/details/gtmjuimhsd.html

[S59] C++：静态断言
来源：http://dali.ydzc1.top/Article/details/gtraozlnoc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pycfn.com/Article/details/gtyqlnwmsw.html

[S60] C++：遍历并删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gtszfyqshm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jianghu66.top/Article/details/gthbhctidi.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtbacbocsy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gtohdnvujc.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gthqnnvlja.html

[T01] Kotlin：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtlovwihov.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtmkjjnovi.html

[T02] Kotlin：变量
来源：http://dali.0kj1m.cn/Article/details/gtiymngiag.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.snrcjt.cn/Article/details/gttkuargcb.html

[T03] Kotlin：字符串模板
来源：http://dali.hywenlv.cn/Article/details/gtmeexxfkw.html

"值: $b"
来源：http://dali.zycfv.cn/Article/details/gtdssmvhjt.html

[T04] Kotlin：空安全
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaozgzrfi.html

val n: String? = null;  n?.length
来源：http://dali.shangyingyoupin.top/Article/details/gthhlumhzg.html

[T05] Kotlin：when 表达式
来源：http://dali.nanxinkj.top/Article/details/gtbwkttpyh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.c1oappe.top/Article/details/gtuwkcbnwz.html

[T06] Kotlin：集合映射
来源：http://dali.zhengqikj.top/Article/details/gtptjsoszx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sweek.top/Article/details/gtrflqdxzs.html

[T07] Kotlin：集合过滤
来源：http://dali.ydzc1.top/Article/details/gtsircpann.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jyoumei.cn/Article/details/gtfbvuqquj.html

[T08] Kotlin：数据类
来源：http://dali.shzxlz.cn/Article/details/gtuqacbgpd.html

data class User(val name: String, val age: Int)
来源：http://dali.ehwqpu.com/Article/details/gtaufvoxvi.html

[T09] Kotlin：扩展函数
来源：http://dali.0kj1m.cn/Article/details/gtpioynbpf.html

fun String.exclaim() = this + "!"
来源：http://dali.shuidangran.top/Article/details/gtodzbdbbq.html

[T10] Kotlin：默认参数
来源：http://dali.birdmap.top/Article/details/gtovbawczc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.guannengcc.top/Article/details/gthideqtgv.html

[T11] Kotlin：协程
来源：http://dali.yj202588.top/Article/details/gthwjshbrg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shzxlz.cn/Article/details/gtjuykbkik.html

[T12] Kotlin：解构声明
来源：http://dali.tian-w.cn/Article/details/gtopeugjla.html

val (a, b) = Pair(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtgiwkqzxt.html

[T13] Kotlin：只读 Map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpoqqulmb.html

val m = mapOf("a" to 1)
来源：http://dali.kuanghao11.cn/Article/details/gtitqbizbt.html

[T14] Kotlin：循环
来源：http://dali.vqdsnc.cn/Article/details/gtuykwfnik.html

for (i in 1..10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtluntygig.html

[T15] Kotlin：接口
来源：http://dali.xuetiantiany.cn/Article/details/gtnvijylqq.html

interface Shape { fun area(): Double }
来源：http://dali.cucudq.cn/Article/details/gtioupeypy.html

[T16] Swift：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejelpmig.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtqqkrdwnn.html

[T17] Swift：变量与常量
来源：http://dali.haohaochexian.top/Article/details/gtyzxximyx.html

var a = 1;  let b = 2
来源：http://dali.hnxiangtu.top/Article/details/gtikrgxdtl.html

[T18] Swift：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtewbkpsfs.html

"值: \(b)"
来源：http://dali.zhiwuduotai.top/Article/details/gtpdbeautr.html

[T19] Swift：可选绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtpzxjrmwc.html

if let n = opt { print(n) }
来源：http://dali.jianghu66.top/Article/details/gtdweybqkn.html

[T20] Swift：数组操作
来源：http://dali.xziqi.cn/Article/details/gtxlebcwka.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cheryme.top/Article/details/gtlqgnufne.html

[T21] Swift：遍历
来源：http://dali.shuidangran.top/Article/details/gtsrdebyjv.html

for x in a { print(x) }
来源：http://dali.cqqwz.cn/Article/details/gtexswrdzd.html

[T22] Swift：字典
来源：http://dali.jiagoushi.top/Article/details/gtezlwxjmh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.mhx1999.top/Article/details/gtpwkfhmrp.html

[T23] Swift：函数
来源：http://dali.aibaodan.cn/Article/details/gttxmjndbq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.svipenyu.cn/Article/details/gtclllhoyh.html

[T24] Swift：闭包
来源：http://dali.yongpay.top/Article/details/gtwzcxqodh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangdashe.top/Article/details/gtqvgxwaby.html

[T25] Swift：结构体
来源：http://dali.c1oappe.top/Article/details/gtazihbohb.html

struct P { var x: Int }
来源：http://dali.meibo888.top/Article/details/gtnpdgovbh.html

[T26] Swift：类与重写
来源：http://dali.gaohongyu789.top/Article/details/gtkwuqxqts.html

class A: Base { override func f() {} }
来源：http://dali.fengsongda.top/Article/details/gtlvesrqqu.html

[T27] Swift：错误处理
来源：http://dali.nwbrower.top/Article/details/gtkpffjgwq.html

do { try f() } catch { print(error) }
来源：http://dali.chenlongwang.top/Article/details/gtxjtoqnkh.html

[T28] Swift：枚举
来源：http://dali.chenlongwang.top/Article/details/gtdedrompy.html

enum Color { case red, green }
来源：http://dali.hnqzz.top/Article/details/gtsczpyesq.html

[T29] Swift：guard 提前返回
来源：http://dali.gotoacloud.top/Article/details/gtrkqzitef.html

guard let x = opt else { return }
来源：http://dali.gogol.net.cn/Article/details/gtfehrppzg.html

[T30] Swift：协议
来源：http://dali.sweek.top/Article/details/gtyoziiqdt.html

protocol Shape { func area() -> Double }
来源：http://dali.nwbrower.top/Article/details/gtcjxynlgd.html

[T31] Lua：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtusdbxnoe.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtvuyckjpl.html

[T32] Lua：局部变量
来源：http://dali.cdnleiting.top/Article/details/gtjmilqtmi.html

local a = 1
来源：http://dali.xziqi.cn/Article/details/gtkqgsmuuc.html

[T33] Lua：表（数组）
来源：http://dali.tanke756.top/Article/details/gtgmhfgmhv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigufen.top/Article/details/gtatlnzheq.html

[T34] Lua：遍历表
来源：http://dali.fengsongda.top/Article/details/gttlhvjaph.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hfpthk.cn/Article/details/gtgpqigbpk.html

[T35] Lua：字典表
来源：http://dali.chenjidiqi.icu/Article/details/gtwiajglhx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhixingplan.top/Article/details/gtqsqmwooi.html

[T36] Lua：函数
来源：http://dali.yuanzhike.top/Article/details/gtnvbjwpuj.html

function add(a, b) return a + b end
来源：http://dali.ppjwa.cn/Article/details/gtihgiveft.html

[T37] Lua：字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gtixfukues.html

"a" .. "b"
来源：http://dali.xuanzx.com/Article/details/gtczogadby.html

[T38] Lua：条件
来源：http://dali.tanke756.top/Article/details/gtnipumcdx.html

if x > 0 then print("正") end
来源：http://dali.316326.xyz/Article/details/gtwaiqskdj.html

[T39] Lua：模式匹配
来源：http://dali.sufxvd.cn/Article/details/gttvxnecyx.html

string.find(s, "%d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvchfkpyp.html

[T40] Lua：元表
来源：http://dali.quarkkingdee.top/Article/details/gtywyofqzy.html

setmetatable({}, { __index = base })
来源：http://dali.yangfankeji.com/Article/details/gtozhgumio.html

[T41] Perl：Hello World
来源：http://dali.yj20258888.top/Article/details/gtdxhvghcz.html

print "Hello\n";
来源：http://dali.316326.xyz/Article/details/gtezdfdqra.html

[T42] Perl：变量类型
来源：http://dali.sufxvd.cn/Article/details/gtssawcevq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sweek.top/Article/details/gtycpklpuj.html

[T43] Perl：字符串插值
来源：http://dali.yuxming.cn/Article/details/gtnujklcvc.html

"值: $a"
来源：http://dali.ehwqpu.com/Article/details/gtygqqjlzn.html

[T44] Perl：条件
来源：http://dali.tianlin.xyz/Article/details/gtjlebzmtm.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigfzy.top/Article/details/gteyifrdlv.html

[T45] Perl：数组遍历
来源：http://dali.sysykeji.top/Article/details/gtqffrhvni.html

for my $x (@arr) { print $x; }
来源：http://dali.zhixingplan.top/Article/details/gtuhyanjdy.html

[T46] Perl：哈希操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcrtteur.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jianghu66.top/Article/details/gtrmoccaqy.html

[T47] Perl：正则捕获
来源：http://dali.zhongyouzk.top/Article/details/gtoidfwneh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenlongwang.top/Article/details/gtqlvejrvv.html

[T48] Perl：正则替换
来源：http://dali.cashguo.top/Article/details/gtkpefpztm.html

$s =~ s/old/new/g;
来源：http://dali.jinqigufen.top/Article/details/gtvoxmwxru.html

[T49] Perl：函数
来源：http://dali.9152youxi.cn/Article/details/gtmxfurnla.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtxhxdcitl.html

[T50] Perl：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtdgcnfnzn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuanzhike.top/Article/details/gtvwgmktot.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gtcdolbldg.html

[T51] Scala：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtlbqoakgp.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gtvuyxaxdm.html

[T52] Scala：变量
来源：http://dali.jqgfzy.top/Article/details/gtzrdatxuo.html

val a = 1;  var b = 2
来源：http://dali.yongpay.top/Article/details/gtuyzpjloo.html

[T53] Scala：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtpxijbrah.html

s"值: $b"
来源：http://dali.yangfankeji.com/Article/details/gtffhpwzoz.html

[T54] Scala：集合映射
来源：http://dali.cheryme.top/Article/details/gtpudggral.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nwbrower.top/Article/details/gtgsbkzmwq.html

[T55] Scala：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gtdtulmpno.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.quarkkingdee.top/Article/details/gtynqweuwc.html

[T56] Scala：样例类
来源：http://dali.cdnleiting.top/Article/details/gtsjmvkwrj.html

case class User(name: String, age: Int)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntfjctue.html

[T57] Scala：模式匹配
来源：http://dali.yueranfly.top/Article/details/gtdyucnjyl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hfpthk.cn/Article/details/gtaskqxpqt.html

[T58] Scala：函数定义
来源：http://dali.xuetiantiany.cn/Article/details/gtggsyjojw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.wangshuangyany.cn/Article/details/gtlqhefusk.html

[T59] Scala：循环
来源：http://dali.haohaochexian.top/Article/details/gteyfgjlxh.html

for (i <- 1 to 10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gtkglbhmli.html

[T60] Scala：折叠
来源：http://dali.yj20258.top/Article/details/gtivpdztgt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalzispqt.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtgabuqkqt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hfpthk.cn/Article/details/gtxqcmtppc.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtfzqlwdrt.html

[U01] Py：创建虚拟环境
来源：http://dali.sxryk.cn/Article/details/gtqdgqfqvh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tian-w.cn/Article/details/gtwdkgawcv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hongshengwenyu.top/Article/details/gtyygisocb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gotoacloud.top/Article/details/gtmuhtlhzf.html

[U03] Py：加载 .env 配置
来源：http://dali.chenzaomai.com/Article/details/gtudmcnjbk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ivvv.top/Article/details/gtjzexjaev.html

[U04] Py：变量调试打印
来源：http://dali.316326.xyz/Article/details/gtyrdzkkgs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.meibo888.top/Article/details/gtfyquoswv.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzlnhvhk.html

list(dict.fromkeys(arr))
来源：http://dali.hnqzz.top/Article/details/gtqmwokfer.html

[U06] Py：合并两个字典
来源：http://dali.zhixingplan.top/Article/details/gtxxybwwqq.html

{**a, **b}
来源：http://dali.zhengqikj.top/Article/details/gtdzpehgiw.html

[U07] Py：反转字典键值
来源：http://dali.ydzc1.top/Article/details/gtitxlnhzk.html

{v: k for k, v in d.items()}
来源：http://dali.ivvv.top/Article/details/gtzngcebol.html

[U08] Py：展平二维列表
来源：http://dali.jinqigufen.top/Article/details/gtasoocwbx.html

[y for x in nested for y in x]
来源：http://dali.quarkkingdee.top/Article/details/gtdtkyyzfo.html

[U09] Py：字典取最大值的键
来源：http://dali.yongpay.top/Article/details/gtxhicfthf.html

max(d, key=d.get)
来源：http://dali.sweek.top/Article/details/gtbhzppubx.html

[U10] Py：按值排序字典
来源：http://dali.ehwqpu.com/Article/details/gtapiiodzu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.mhx1999.top/Article/details/gtagxypfqc.html

[U11] Py：生成器表达式
来源：http://dali.jinqigfzy.top/Article/details/gtwztngyip.html

(x * 2 for x in arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtayerzjfr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shangyingyoupin.top/Article/details/gtlicbskzp.html

Counter(arr).most_common(3)
来源：http://dali.316326.xyz/Article/details/gtjkemsrcz.html

[U13] Py：固定长度队列
来源：http://dali.jqgfzy.top/Article/details/gtenmbsehw.html

deque(maxlen=10)
来源：http://dali.hfpthk.cn/Article/details/gteovfwvid.html

[U14] Py：分组收集到列表
来源：http://dali.sweek.top/Article/details/gthhvormyo.html

defaultdict(list)
来源：http://dali.ehwqpu.com/Article/details/gtupryfxjz.html

[U15] Py：高精度计时
来源：http://dali.jyoumei.cn/Article/details/gtqgerrndn.html

t = time.perf_counter()
来源：http://dali.yuanzhike.top/Article/details/gtifthlqto.html

[U16] Py：命令行参数解析
来源：http://dali.xylfe.cn/Article/details/gtnginbosd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.andypj.xyz/Article/details/gtoxgijlfk.html

[U17] Py：初始化日志
来源：http://dali.birdmap.top/Article/details/gtuegadtnh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guowangkeji.top/Article/details/gtvsyvwvyn.html

[U18] Py：预编译正则
来源：http://dali.meibo888.top/Article/details/gtwbzhqdrq.html

pat = re.compile(r"\d+")
来源：http://dali.yanxiufei.cn/Article/details/gteolkehcx.html

[U19] Py：正则替换带回调
来源：http://dali.ppjwa.cn/Article/details/gtcdlfsddj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.snrcjt.cn/Article/details/gtkcrzetqm.html

[U20] Py：缓存函数结果
来源：http://dali.tanke756.top/Article/details/gtnnnywhkt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.mhx1999.top/Article/details/gtupgqslyd.html

[U21] Py：自定义上下文管理器
来源：http://dali.ehwqpu.com/Article/details/gtzubxklbn.html

@contextlib.contextmanager
来源：http://dali.fengsongda.top/Article/details/gtutzchvvg.html

[U22] Py：矩阵转置
来源：http://dali.xinyue.icu/Article/details/gtnkgwrmnz.html

list(zip(*m))
来源：http://dali.zhixingplan.top/Article/details/gtrrbtmfrv.html

[U23] Py：分块读取大文件
来源：http://dali.9152youxi.cn/Article/details/gtslpmtpqu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenlongwang.top/Article/details/gtombjlrnc.html

[U24] Py：路径操作
来源：http://dali.havefunace.top/Article/details/gtbwftxqho.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gtsgkvfiab.html

[U25] Py：CSV 按字典读
来源：http://dali.fzhhl.top/Article/details/gtenlyleej.html

csv.DictReader(f)
来源：http://dali.gzhubu.top/Article/details/gtswhzjwxh.html

[U26] Py：并发下载
来源：http://dali.iojbl.cn/Article/details/gtefkxkyld.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cdnleiting.top/Article/details/gttyaqxoyu.html

[U27] Py：异步 HTTP
来源：http://dali.jinqigfzy.top/Article/details/gtmmhppyox.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuxbzuwt.html

[U28] Py：类型别名
来源：http://dali.0kj1m.cn/Article/details/gtuqxumole.html

UserId = int
来源：http://dali.nanxuanxn.top/Article/details/gtujvwcwqc.html

[U29] Py：属性校验
来源：http://dali.yuxming.cn/Article/details/gtwmpooaun.html

@property 与 @x.setter 配合
来源：http://dali.yuanzhike.top/Article/details/gtvhrvuczp.html

[U30] Py：数据类
来源：http://dali.meibo888.top/Article/details/gtoulfjmhh.html

@dataclass(slots=True)
来源：http://dali.hnqzz.top/Article/details/gtagesrvqt.html

[U31] Py：单测
来源：http://dali.hfpthk.cn/Article/details/gtvyfdpdmy.html

python -m pytest -q
来源：http://dali.gzhubu.top/Article/details/gtgpttwgip.html

[U32] Py：代码格式化
来源：http://dali.iojbl.cn/Article/details/gttuctwulg.html

ruff format . && ruff check --fix .
来源：http://dali.svipenyu.cn/Article/details/gtdnfxbols.html

[U33] Py：打包发布
来源：http://dali.yj20258.top/Article/details/gtdmcdqzhg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenjidiqi.icu/Article/details/gtmtadczec.html

[U34] Py：判断编码
来源：http://dali.tianlin.xyz/Article/details/gtvvdcanag.html

chardet.detect(raw)
来源：http://dali.gogol.net.cn/Article/details/gtdnrpxfqs.html

[U35] Py：发送邮件
来源：http://dali.yuanzhike.top/Article/details/gtupieauws.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.havefunace.top/Article/details/gtxbysrurc.html

[U36] Py：定时任务
来源：http://dali.gzhubu.top/Article/details/gtjtbevmvp.html

schedule.every(10).minutes.do(job)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnuxurbuv.html

[U37] Py：读写 Excel
来源：http://dali.nanxinkj.top/Article/details/gtbvscctfj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.quarkkingdee.top/Article/details/gthvvvlezq.html

[U38] Py：获取脚本所在目录
来源：http://dali.fzhhl.top/Article/details/gtplwzguxo.html

Path(__file__).resolve().parent
来源：http://dali.zdqjudy.top/Article/details/gtybnaijog.html

[U39] Py：判断是否在交互环境
来源：http://dali.hammf.cn/Article/details/gtjkhiswow.html

sys.stdout.isatty()
来源：http://dali.dashuyun.cn/Article/details/gttffamape.html

[U40] Py：打印到标准错误
来源：http://dali.yvedp.cn/Article/details/gtpgnkfjrq.html

print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmezjvaj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ybcxt.top/Article/details/gtcpwvtvme.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.wangshuangyany.cn/Article/details/gthmnhxwne.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yanxiufei.cn/Article/details/gtubmeouco.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.gzhubu.top/Article/details/gtgqkssaoh.html

[U43] PHP：声明命名空间
来源：http://dali.nanxinkj.top/Article/details/gtplgytroe.html

namespace App\Http;
来源：http://dali.chenlongwang.top/Article/details/gtlcdddasu.html

[U44] PHP：开启严格类型
来源：http://dali.ivvv.top/Article/details/gtjumrzxls.html

declare(strict_types=1);
来源：http://dali.zhixingplan.top/Article/details/gticctnmqa.html

[U45] PHP：类型声明与返回类型
来源：http://dali.nanxuanxn.top/Article/details/gtqxfruhlt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gtbfqqlqse.html

[U46] PHP：可空类型
来源：http://dali.ybcxt.top/Article/details/gtyqgtjncs.html

?string $name = null
来源：http://dali.daxiang520.top/Article/details/gtjyzufavs.html

[U47] PHP：联合类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gteaqquzyb.html

int|string $id
来源：http://dali.cashguo.top/Article/details/gttkvwaldw.html

[U48] PHP：纯枚举
来源：http://dali.yanxiufei.cn/Article/details/gtaduusnzd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jiagoushi.top/Article/details/gtnxepazma.html

[U49] PHP：只读属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthggqshoi.html

public readonly string $name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkhsssbf.html

[U50] PHP：构造器属性提升
来源：http://dali.tian-w.cn/Article/details/gtwuzkriur.html

public function __construct(private int $id) {}
来源：http://dali.hfpthk.cn/Article/details/gtogtifwsv.html

[U51] PHP：数组解构
来源：http://dali.feifeiyinyue.top/Article/details/gtnthxxlvc.html

[$a, $b] = $arr;
来源：http://dali.shuidangran.top/Article/details/gtvqqpmezf.html

[U52] PHP：箭头函数
来源：http://dali.vqdsnc.cn/Article/details/gtgmuqkqoz.html

$double = fn($x) => $x * 2;
来源：http://dali.cashguo.top/Article/details/gtkgaxrbkt.html

[U53] PHP：空合并运算符
来源：http://dali.jinqigufen.top/Article/details/gtrfnsqazd.html

$v = $a ?? $b ?? "default";
来源：http://dali.jqgufenzy.top/Article/details/gtrpgkvgjr.html

[U54] PHP：空安全调用
来源：http://dali.cdnleiting.top/Article/details/gtnvbnmljx.html

$obj?->method()
来源：http://dali.daria6918.cn/Article/details/gtadsvptfd.html

[U55] PHP：match 表达式
来源：http://dali.sxryk.cn/Article/details/gthdyrzkwd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.guowangkeji.top/Article/details/gtpukwijwe.html

[U56] PHP：命名参数
来源：http://dali.shuidangran.top/Article/details/gtrsgxhaqb.html

f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gtcydklgko.html

[U57] PHP：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtzwazaedr.html

"值: {$a}"
来源：http://dali.wangdashe.top/Article/details/gtyvibqwno.html

[U58] PHP：数组三件套
来源：http://dali.ppjwa.cn/Article/details/gtdiyvwxqk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.chenlongwang.top/Article/details/gtoaqzsqpf.html

[U59] PHP：自定义排序
来源：http://dali.andypj.xyz/Article/details/gtpkzaqssr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zdqjudy.top/Article/details/gtosoxpczx.html

[U60] PHP：JSON 编解码
来源：http://dali.guowangkeji.top/Article/details/gtlgwtrlao.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojwbhkso.html

[U61] PHP：正则
来源：http://dali.shangyingyoupin.top/Article/details/gtlkwacalk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.smart0.xyz/Article/details/gtyaypqnlj.html

[U62] PHP：日期对象
来源：http://dali.tianlin.xyz/Article/details/gtedpbteqv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhoulong.xyz/Article/details/gtrqxnwptt.html

[U63] PHP：文件读写
来源：http://dali.gogol.net.cn/Article/details/gtwtlxbtrt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.tianlin.xyz/Article/details/gtoutmucop.html

[U64] PHP：目录遍历
来源：http://dali.gogol.net.cn/Article/details/gtixiurppy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj20258888.top/Article/details/gtpeisnedt.html

[U65] PHP：会话
来源：http://dali.xuetiantiany.cn/Article/details/gtwiipkybi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtsffpzpms.html

[U66] PHP：设置 Cookie
来源：http://dali.hnqzz.top/Article/details/gtrmsgjvpc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.iojbl.cn/Article/details/gtirylrkwq.html

[U67] PHP：处理文件上传
来源：http://dali.gogol.net.cn/Article/details/gtqzqhtijx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sweek.top/Article/details/gtxiykqvpw.html

[U68] PHP：PDO 连接
来源：http://dali.shangyingyoupin.top/Article/details/gtjekraonb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xylfe.cn/Article/details/gtgzjuunwz.html


<!-- 参考信息 -->