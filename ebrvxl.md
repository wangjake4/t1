代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.jqgufenzy.top/Article/details/gtcczickcv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tian-w.cn/Article/details/gttjbppvna.html

[S48] C++：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtdanoekad.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yangfankeji.com/Article/details/gtrzbqtedz.html

while (std::getline(in, line)) { }
来源：http://dali.gotoacloud.top/Article/details/gtefgffzfz.html

[S49] C++：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcooqcet.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.0kj1m.cn/Article/details/gtegruvhal.html

[S50] C++：格式化数字
来源：http://dali.hnqzz.top/Article/details/gtmwxdyqax.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtymdhkfgu.html

[S51] C++：显式类型转换
来源：http://dali.yj20258.top/Article/details/gtaqstvicb.html

static_cast<double>(a) / b
来源：http://dali.yj20258888.top/Article/details/gtosmrpcys.html

[S52] C++：const 与 noexcept
来源：http://dali.jiagoushi.top/Article/details/gtwduljxpi.html

int size() const noexcept { return n_; }
来源：http://dali.vqdsnc.cn/Article/details/gtlhelbdbu.html

[S53] C++：移动语义
来源：http://dali.ppjwa.cn/Article/details/gtlmmkbhmp.html

std::vector<int> w = std::move(v);
来源：http://dali.birdmap.top/Article/details/gthknydpsu.html

[S54] C++：异常处理
来源：http://dali.yangfankeji.com/Article/details/gtlqvzidlu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yangfankeji.com/Article/details/gtwbwaisqk.html

[S55] C++：结构化绑定
来源：http://dali.kuanghao11.cn/Article/details/gtshjziikw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhixingplan.top/Article/details/gtazxapzor.html

[S56] C++：optional
来源：http://dali.yuanzhike.top/Article/details/gtnkorvnnw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.havefunace.top/Article/details/gtanedmcbv.html

[S57] C++：编译期常量
来源：http://dali.cucudq.cn/Article/details/gtkcpnfjbs.html

constexpr int N = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtqypywrof.html

[S58] C++：命名空间
来源：http://dali.316326.xyz/Article/details/gtnepiuile.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtqsoujlyh.html

[S59] C++：静态断言
来源：http://dali.gzhubu.top/Article/details/gtsdxucxho.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hywenlv.cn/Article/details/gtuawkaftb.html

[S60] C++：遍历并删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtxgudeuai.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtgsnejjui.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtvztkyyge.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.meibo888.top/Article/details/gtwpzvtxsk.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtpqqlyyub.html

[T01] Kotlin：Hello World
来源：http://dali.tian-w.cn/Article/details/gtsdnxtxyr.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtsimbmtjh.html

[T02] Kotlin：变量
来源：http://dali.xziqi.cn/Article/details/gtohahzifc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnqzz.top/Article/details/gtqgczrgrf.html

[T03] Kotlin：字符串模板
来源：http://dali.0kj1m.cn/Article/details/gtzafwzxft.html

"值: $b"
来源：http://dali.redwolf501.top/Article/details/gtonszndxa.html

[T04] Kotlin：空安全
来源：http://dali.cucudq.cn/Article/details/gtsjrggmpw.html

val n: String? = null;  n?.length
来源：http://dali.jinqigfzy.top/Article/details/gtjtoxyvoz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhongyouzk.top/Article/details/gtgeazklfk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.c1oappe.top/Article/details/gtvrkhbjbj.html

[T06] Kotlin：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gtqytdswcd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtmcazqhzr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtibcecnlj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.mhx1999.top/Article/details/gteqvofzdk.html

[T08] Kotlin：数据类
来源：http://dali.daxiang520.top/Article/details/gthnwootzj.html

data class User(val name: String, val age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvtcvmok.html

[T09] Kotlin：扩展函数
来源：http://dali.dianchejie.cn/Article/details/gtdsgrtxwk.html

fun String.exclaim() = this + "!"
来源：http://dali.cdnleiting.top/Article/details/gtdvjaebcv.html

[T10] Kotlin：默认参数
来源：http://dali.gogol.net.cn/Article/details/gtuclxrtzu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hongshengwenyu.top/Article/details/gtuccuuzwm.html

[T11] Kotlin：协程
来源：http://dali.gotoacloud.top/Article/details/gtwtzexguf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cheryme.top/Article/details/gtchmhguji.html

[T12] Kotlin：解构声明
来源：http://dali.cdnleiting.top/Article/details/gtdqugascx.html

val (a, b) = Pair(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxnuvqra.html

[T13] Kotlin：只读 Map
来源：http://dali.yuanzhike.top/Article/details/gtesijbofp.html

val m = mapOf("a" to 1)
来源：http://dali.dianchejie.cn/Article/details/gtrapzfelk.html

[T14] Kotlin：循环
来源：http://dali.pycfn.com/Article/details/gthfdxdbkt.html

for (i in 1..10) println(i)
来源：http://dali.birdmap.top/Article/details/gtjaqcgqtl.html

[T15] Kotlin：接口
来源：http://dali.ybcxt.top/Article/details/gtyicxypul.html

interface Shape { fun area(): Double }
来源：http://dali.birdmap.top/Article/details/gtsrifgihj.html

[T16] Swift：Hello World
来源：http://dali.yvedp.cn/Article/details/gtamaxvsct.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtafesmcug.html

[T17] Swift：变量与常量
来源：http://dali.gogol.net.cn/Article/details/gtepreaara.html

var a = 1;  let b = 2
来源：http://dali.yj202588.top/Article/details/gtvqxdwyai.html

[T18] Swift：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtdnzkoniq.html

"值: \(b)"
来源：http://dali.hysaishi.cn/Article/details/gthprfdmzp.html

[T19] Swift：可选绑定
来源：http://dali.jinqigufen.top/Article/details/gtdgsbcyoj.html

if let n = opt { print(n) }
来源：http://dali.wangdashe.top/Article/details/gtfmjmeofq.html

[T20] Swift：数组操作
来源：http://dali.hysaishi.cn/Article/details/gtmchugpdr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnqzz.top/Article/details/gtmsmtmrcr.html

[T21] Swift：遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtjjqcybvg.html

for x in a { print(x) }
来源：http://dali.iojbl.cn/Article/details/gtntldwwuz.html

[T22] Swift：字典
来源：http://dali.pengpengdd.cyou/Article/details/gtkgjnqcwi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenzaomai.com/Article/details/gtkyqbzavd.html

[T23] Swift：函数
来源：http://dali.dianchejie.cn/Article/details/gtodwigmqa.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xinyue.icu/Article/details/gtqqebmatc.html

[T24] Swift：闭包
来源：http://dali.smart0.xyz/Article/details/gtifjbsikk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtvmayfzhn.html

[T25] Swift：结构体
来源：http://dali.0kj1m.cn/Article/details/gthuwjdmwg.html

struct P { var x: Int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdudcpljl.html

[T26] Swift：类与重写
来源：http://dali.meibo888.top/Article/details/gtzpusodrh.html

class A: Base { override func f() {} }
来源：http://dali.yuanzhike.top/Article/details/gtgspkemfo.html

[T27] Swift：错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtwapvdhef.html

do { try f() } catch { print(error) }
来源：http://dali.redwolf501.top/Article/details/gtqpijxaqp.html

[T28] Swift：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylpohqlw.html

enum Color { case red, green }
来源：http://dali.sufxvd.cn/Article/details/gtctjfuzhb.html

[T29] Swift：guard 提前返回
来源：http://dali.fzhhl.top/Article/details/gtownceldi.html

guard let x = opt else { return }
来源：http://dali.andypj.xyz/Article/details/gtpfaalxpx.html

[T30] Swift：协议
来源：http://dali.hongshengwenyu.top/Article/details/gturbzcpde.html

protocol Shape { func area() -> Double }
来源：http://dali.yuanzhike.top/Article/details/gtsfajsums.html

[T31] Lua：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtfhkhvxvl.html

print("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtjamtusha.html

[T32] Lua：局部变量
来源：http://dali.vqdsnc.cn/Article/details/gtvphlycoi.html

local a = 1
来源：http://dali.birdmap.top/Article/details/gtrbgfqthh.html

[T33] Lua：表（数组）
来源：http://dali.jyoumei.cn/Article/details/gtbsveifjd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jlsjyb.cn/Article/details/gtwvlgpapg.html

[T34] Lua：遍历表
来源：http://dali.yangfankeji.com/Article/details/gtozeuqjei.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nwbrower.top/Article/details/gtrqnujljg.html

[T35] Lua：字典表
来源：http://dali.guowangkeji.top/Article/details/gtowwjzavp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jqgufenzy.top/Article/details/gtbevmiemg.html

[T36] Lua：函数
来源：http://dali.jyoumei.cn/Article/details/gtzlpocmgb.html

function add(a, b) return a + b end
来源：http://dali.yuanzhike.top/Article/details/gtzfxkuqnt.html

[T37] Lua：字符串拼接
来源：http://dali.iojbl.cn/Article/details/gtnhhqvebi.html

"a" .. "b"
来源：http://dali.sweek.top/Article/details/gtmhqokbny.html

[T38] Lua：条件
来源：http://dali.havefunace.top/Article/details/gtuuxmpgxc.html

if x > 0 then print("正") end
来源：http://dali.mhx1999.top/Article/details/gtwwyxfydq.html

[T39] Lua：模式匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gthyrhvcow.html

string.find(s, "%d+")
来源：http://dali.hysaishi.cn/Article/details/gtkpobecxa.html

[T40] Lua：元表
来源：http://dali.xuetiantiany.cn/Article/details/gtplbozrwi.html

setmetatable({}, { __index = base })
来源：http://dali.sxryk.cn/Article/details/gtimaubwlh.html

[T41] Perl：Hello World
来源：http://dali.daria6918.cn/Article/details/gtjovwdgnk.html

print "Hello\n";
来源：http://dali.cucudq.cn/Article/details/gtvrkwmsyq.html

[T42] Perl：变量类型
来源：http://dali.shuidangran.top/Article/details/gtwvuzmdzj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinqigufen.top/Article/details/gtubburngk.html

[T43] Perl：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtwsqliqeo.html

"值: $a"
来源：http://dali.jinghuilouyu.cn/Article/details/gteznnhtbo.html

[T44] Perl：条件
来源：http://dali.snrcjt.cn/Article/details/gtqfobqgyl.html

if ($a > 0) { print "正"; }
来源：http://dali.yueranfly.top/Article/details/gtqvpcdguo.html

[T45] Perl：数组遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdnxecxo.html

for my $x (@arr) { print $x; }
来源：http://dali.hnqzz.top/Article/details/gtxhcpteie.html

[T46] Perl：哈希操作
来源：http://dali.chenlongwang.top/Article/details/gtsilwibjm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.pycfn.com/Article/details/gtmqkgrxyc.html

[T47] Perl：正则捕获
来源：http://dali.meibo888.top/Article/details/gtwjpjzkmu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.andypj.xyz/Article/details/gttqaslkhl.html

[T48] Perl：正则替换
来源：http://dali.quarkkingdee.top/Article/details/gtenajgwpa.html

$s =~ s/old/new/g;
来源：http://dali.zhixingplan.top/Article/details/gtochdpvts.html

[T49] Perl：函数
来源：http://dali.chenzaomai.com/Article/details/gtwaryibgp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtebuxgkas.html

[T50] Perl：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtizekzils.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hongshengwenyu.top/Article/details/gttpmbyhvs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj20258888.top/Article/details/gtaslldogy.html

[T51] Scala：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdcmnrka.html

println("Hello")
来源：http://dali.shuidangran.top/Article/details/gtitkfknag.html

[T52] Scala：变量
来源：http://dali.cucudq.cn/Article/details/gtwslmtdac.html

val a = 1;  var b = 2
来源：http://dali.cdnleiting.top/Article/details/gtlqpjvsvd.html

[T53] Scala：字符串插值
来源：http://dali.ydzc1.top/Article/details/gtjjzkrvrz.html

s"值: $b"
来源：http://dali.meibo888.top/Article/details/gtshkoijgq.html

[T54] Scala：集合映射
来源：http://dali.ppjwa.cn/Article/details/gtmyalkptr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtznzfoeif.html

[T55] Scala：集合过滤
来源：http://dali.birdmap.top/Article/details/gtccdgzgmm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtvggwvhzq.html

[T56] Scala：样例类
来源：http://dali.zhiwuduotai.top/Article/details/gtemenhbfp.html

case class User(name: String, age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gtnigigeix.html

[T57] Scala：模式匹配
来源：http://dali.cucudq.cn/Article/details/gtfbqeniie.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.9152youxi.cn/Article/details/gtnkzkckrl.html

[T58] Scala：函数定义
来源：http://dali.yj20258888.top/Article/details/gtyzxhfkci.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xuetiantiany.cn/Article/details/gtannmqsrz.html

[T59] Scala：循环
来源：http://dali.jqgfzy.top/Article/details/gtdgfqfadv.html

for (i <- 1 to 10) println(i)
来源：http://dali.daxiang520.top/Article/details/gtdjgfhqdv.html

[T60] Scala：折叠
来源：http://dali.xuetiantiany.cn/Article/details/gtpahzdbee.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aibaodan.cn/Article/details/gtmnumuqhj.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmkuwzkm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gtfeaprumz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtpflwbkds.html

[U01] Py：创建虚拟环境
来源：http://dali.hysaishi.cn/Article/details/gtewyiakqy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jiagoushi.top/Article/details/gtwcmxczzi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hywenlv.cn/Article/details/gtoitlphgq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yongpay.top/Article/details/gtszcgowjk.html

[U03] Py：加载 .env 配置
来源：http://dali.0kj1m.cn/Article/details/gtbvteqsgc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.dashuyun.cn/Article/details/gtvhqbttfs.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gtdwsdplhh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hnxiangtu.top/Article/details/gthqqbclmv.html

[U05] Py：列表去重且保序
来源：http://dali.zycfv.cn/Article/details/gtmszhzcro.html

list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtibvtqeci.html

[U06] Py：合并两个字典
来源：http://dali.jiagoushi.top/Article/details/gtjuwdhjhx.html

{**a, **b}
来源：http://dali.cucudq.cn/Article/details/gtlssywwom.html

[U07] Py：反转字典键值
来源：http://dali.aizwys.cn/Article/details/gttkughdlb.html

{v: k for k, v in d.items()}
来源：http://dali.shangyingyoupin.top/Article/details/gtdyqlxzdl.html

[U08] Py：展平二维列表
来源：http://dali.yonumen.top/Article/details/gtxfxxjdyi.html

[y for x in nested for y in x]
来源：http://dali.yvedp.cn/Article/details/gtwmimcrvq.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gtyaxpxpgp.html

max(d, key=d.get)
来源：http://dali.nanxinkj.top/Article/details/gtdvswwkrf.html

[U10] Py：按值排序字典
来源：http://dali.fengsongda.top/Article/details/gtsmgefrmc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnpzasgh.html

[U11] Py：生成器表达式
来源：http://dali.tanke756.top/Article/details/gtojsbxits.html

(x * 2 for x in arr)
来源：http://dali.havefunace.top/Article/details/gtjnefwoge.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.quarkkingdee.top/Article/details/gtujgatqzk.html

Counter(arr).most_common(3)
来源：http://dali.zdqjudy.top/Article/details/gtftestqwb.html

[U13] Py：固定长度队列
来源：http://dali.yanxiufei.cn/Article/details/gtkkxazmgu.html

deque(maxlen=10)
来源：http://dali.zhengqikj.top/Article/details/gtaqfwtlnq.html

[U14] Py：分组收集到列表
来源：http://dali.shuidangran.top/Article/details/gtwcszxxzu.html

defaultdict(list)
来源：http://dali.chenlongwang.top/Article/details/gtgkpcemko.html

[U15] Py：高精度计时
来源：http://dali.shanyushiyangtech.top/Article/details/gthmhxgleb.html

t = time.perf_counter()
来源：http://dali.daxiang520.top/Article/details/gttenbnqez.html

[U16] Py：命令行参数解析
来源：http://dali.jyoumei.cn/Article/details/gttscvlmmz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.mhx1999.top/Article/details/gtnhribpor.html

[U17] Py：初始化日志
来源：http://dali.zhengqikj.top/Article/details/gtgqwuicmz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.mhx1999.top/Article/details/gtltmbxeag.html

[U18] Py：预编译正则
来源：http://dali.chenjidiqi.icu/Article/details/gtjisbfvem.html

pat = re.compile(r"\d+")
来源：http://dali.zhixingplan.top/Article/details/gtfgoxabmd.html

[U19] Py：正则替换带回调
来源：http://dali.daxiang520.top/Article/details/gtctqathal.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.guowangkeji.top/Article/details/gtrzxieqts.html

[U20] Py：缓存函数结果
来源：http://dali.jqgfzy.top/Article/details/gtfrjqbnwf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ybcxt.top/Article/details/gtqwoscpol.html

[U21] Py：自定义上下文管理器
来源：http://dali.bjfxy.top/Article/details/gtxdysnsnk.html

@contextlib.contextmanager
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybvxqvwk.html

[U22] Py：矩阵转置
来源：http://dali.tianlin.xyz/Article/details/gtdvhbxglk.html

list(zip(*m))
来源：http://dali.aibaodan.cn/Article/details/gtqmtqshxx.html

[U23] Py：分块读取大文件
来源：http://dali.tanke756.top/Article/details/gtzydfireh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinghuilouyu.cn/Article/details/gtaoqwfcug.html

[U24] Py：路径操作
来源：http://dali.jianghu66.top/Article/details/gtcxcysjzr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtaslsacif.html

[U25] Py：CSV 按字典读
来源：http://dali.tanke756.top/Article/details/gtmcuhwsrl.html

csv.DictReader(f)
来源：http://dali.nwbrower.top/Article/details/gtxgdvllds.html

[U26] Py：并发下载
来源：http://dali.zhengqikj.top/Article/details/gtekfkfxtj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhixingplan.top/Article/details/gttialkcvg.html

[U27] Py：异步 HTTP
来源：http://dali.yuanzhike.top/Article/details/gtqeneophb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.0kj1m.cn/Article/details/gthdiazfec.html

[U28] Py：类型别名
来源：http://dali.ydzc1.top/Article/details/gturuqrcwn.html

UserId = int
来源：http://dali.cqqwz.cn/Article/details/gthogqfmdd.html

[U29] Py：属性校验
来源：http://dali.mhx1999.top/Article/details/gtoltxbust.html

@property 与 @x.setter 配合
来源：http://dali.kuanghao11.cn/Article/details/gtxeshbnxj.html

[U30] Py：数据类
来源：http://dali.jqgfzy.top/Article/details/gtkjphhpkp.html

@dataclass(slots=True)
来源：http://dali.yonumen.top/Article/details/gtqqbarddz.html

[U31] Py：单测
来源：http://dali.cucudq.cn/Article/details/gtgrxextnt.html

python -m pytest -q
来源：http://dali.yuxming.cn/Article/details/gtwgymrerb.html

[U32] Py：代码格式化
来源：http://dali.gotoacloud.top/Article/details/gtdmqtmxvm.html

ruff format . && ruff check --fix .
来源：http://dali.ydzc1.top/Article/details/gteubjcitr.html

[U33] Py：打包发布
来源：http://dali.jinqigfzy.top/Article/details/gtamdsylsy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinghuilouyu.cn/Article/details/gtawokiefm.html

[U34] Py：判断编码
来源：http://dali.cqqwz.cn/Article/details/gtpcvubxwo.html

chardet.detect(raw)
来源：http://dali.shuidangran.top/Article/details/gtfaishzgh.html

[U35] Py：发送邮件
来源：http://dali.andypj.xyz/Article/details/gtilciyplj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.meibo888.top/Article/details/gtvgpmsdub.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gtiltuzluh.html

schedule.every(10).minutes.do(job)
来源：http://dali.gzhubu.top/Article/details/gtwemaobxx.html

[U37] Py：读写 Excel
来源：http://dali.yuxming.cn/Article/details/gttmsmqivl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jyoumei.cn/Article/details/gtppqkvhlx.html

[U38] Py：获取脚本所在目录
来源：http://dali.hongshengwenyu.top/Article/details/gttmdkltmz.html

Path(__file__).resolve().parent
来源：http://dali.jianghu66.top/Article/details/gtrnlmpvgv.html

[U39] Py：判断是否在交互环境
来源：http://dali.tanke756.top/Article/details/gtatmljcpy.html

sys.stdout.isatty()
来源：http://dali.aizwys.cn/Article/details/gtibzitbhg.html

[U40] Py：打印到标准错误
来源：http://dali.aizwys.cn/Article/details/gtroswsyfi.html

print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gtavauzpbw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.0kj1m.cn/Article/details/gtpdxkosyn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinqigfzy.top/Article/details/gtrdwgivmm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hfpthk.cn/Article/details/gtucxqkspm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cheryme.top/Article/details/gtvgwrwbgd.html

[U43] PHP：声明命名空间
来源：http://dali.hongshengwenyu.top/Article/details/gtejekcflo.html

namespace App\Http;
来源：http://dali.smart0.xyz/Article/details/gtcfafhprs.html

[U44] PHP：开启严格类型
来源：http://dali.dashuyun.cn/Article/details/gtynfuxsnj.html

declare(strict_types=1);
来源：http://dali.andypj.xyz/Article/details/gtivgyyaud.html

[U45] PHP：类型声明与返回类型
来源：http://dali.quarkkingdee.top/Article/details/gtmtwhujmw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwbedhcgx.html

[U46] PHP：可空类型
来源：http://dali.hongshengwenyu.top/Article/details/gtgrhlrety.html

?string $name = null
来源：http://dali.zhoulong.xyz/Article/details/gthdbeahmd.html

[U47] PHP：联合类型
来源：http://dali.zhongyouzk.top/Article/details/gtlwqqozzt.html

int|string $id
来源：http://dali.yj20258.top/Article/details/gthhqtykaz.html

[U48] PHP：纯枚举
来源：http://dali.jinqigfzy.top/Article/details/gtzzrfilbd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.aibaodan.cn/Article/details/gtbguwvyqp.html

[U49] PHP：只读属性
来源：http://dali.zhengqikj.top/Article/details/gtwicwhrsq.html

public readonly string $name
来源：http://dali.ivvv.top/Article/details/gtyhvbdvrn.html

[U50] PHP：构造器属性提升
来源：http://dali.tanke756.top/Article/details/gtreocnjzf.html

public function __construct(private int $id) {}
来源：http://dali.jlsjyb.cn/Article/details/gtxfotxtbq.html

[U51] PHP：数组解构
来源：http://dali.zhengqikj.top/Article/details/gtxzhggucv.html

[$a, $b] = $arr;
来源：http://dali.feifeiyinyue.top/Article/details/gtbzsiyyoa.html

[U52] PHP：箭头函数
来源：http://dali.svipenyu.cn/Article/details/gtaqwxfgpa.html

$double = fn($x) => $x * 2;
来源：http://dali.yj202588.top/Article/details/gtyquvwcbm.html

[U53] PHP：空合并运算符
来源：http://dali.hywenlv.cn/Article/details/gtgejtrsbe.html

$v = $a ?? $b ?? "default";
来源：http://dali.birdmap.top/Article/details/gtwqzmpzsr.html

[U54] PHP：空安全调用
来源：http://dali.andypj.xyz/Article/details/gtzkmunjsa.html

$obj?->method()
来源：http://dali.meibo888.top/Article/details/gtbodmxlkb.html

[U55] PHP：match 表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtfbikhdbi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.redwolf501.top/Article/details/gtfhqyovpg.html

[U56] PHP：命名参数
来源：http://dali.shzxlz.cn/Article/details/gtcddmggwl.html

f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtzepylqga.html

[U57] PHP：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtyptedzjh.html

"值: {$a}"
来源：http://dali.aibaodan.cn/Article/details/gtkyxvzkxd.html

[U58] PHP：数组三件套
来源：http://dali.xylfe.cn/Article/details/gtpiziqdpw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yvedp.cn/Article/details/gtqhrngfwk.html

[U59] PHP：自定义排序
来源：http://dali.jinqigufen.top/Article/details/gtxikbjzyu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigufen.top/Article/details/gtbumxdynf.html

[U60] PHP：JSON 编解码
来源：http://dali.yj202588.top/Article/details/gtuieetxdh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ydzc1.top/Article/details/gtapkezxft.html

[U61] PHP：正则
来源：http://dali.zhaomingkeji.xyz/Article/details/gthsvrlcds.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenlongwang.top/Article/details/gtbdaitnoc.html

[U62] PHP：日期对象
来源：http://dali.yuanzhike.top/Article/details/gtyvkwgqyq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbesfttr.html

[U63] PHP：文件读写
来源：http://dali.tian-w.cn/Article/details/gtiajkpbul.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zdqjudy.top/Article/details/gtyetrqfcd.html

[U64] PHP：目录遍历
来源：http://dali.cucudq.cn/Article/details/gtwxfpatxa.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.havefunace.top/Article/details/gthqfdhifa.html

[U65] PHP：会话
来源：http://dali.jiagoushi.top/Article/details/gthxmmwvqs.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtcqrbjsaq.html

[U66] PHP：设置 Cookie
来源：http://dali.shangyingyoupin.top/Article/details/gtaksywokv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.dianchejie.cn/Article/details/gtoqfrmprq.html

[U67] PHP：处理文件上传
来源：http://dali.svipenyu.cn/Article/details/gtrjgnlsfe.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gzhubu.top/Article/details/gtsiwszxyg.html

[U68] PHP：PDO 连接
来源：http://dali.shzxlz.cn/Article/details/gtuwejrhsp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.c1oappe.top/Article/details/gtyvkjebsf.html

[U69] PHP：PDO 预处理
来源：http://dali.snrcjt.cn/Article/details/gtzentmozu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ehwqpu.com/Article/details/gtiwpnowjl.html

[U70] PHP：PDO 事务
来源：http://dali.yuxming.cn/Article/details/gtmfwlntbo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklqsnphx.html

[U71] PHP：抛出异常
来源：http://dali.zhoulong.xyz/Article/details/gtypnqtuat.html

throw new RuntimeException("失败", 500);
来源：http://dali.guannengcc.top/Article/details/gtpmeyxgmv.html

[U72] PHP：写错误日志
来源：http://dali.yj20258888.top/Article/details/gtpxsfyfby.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jlsjyb.cn/Article/details/gtueethcup.html


<!-- 参考信息 -->