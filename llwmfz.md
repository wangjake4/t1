代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.gzhubu.top/Article/details/gtilhxbfcd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daxiang520.top/Article/details/gtmdsycujr.html

[S48] C++：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtfbyshqkl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xinyue.icu/Article/details/gtancwvfdm.html

while (std::getline(in, line)) { }
来源：http://dali.ivvv.top/Article/details/gtutdhuaqq.html

[S49] C++：写文件
来源：http://dali.nanxinkj.top/Article/details/gtqstfahwe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dashuyun.cn/Article/details/gtgrmmlvoj.html

[S50] C++：格式化数字
来源：http://dali.zhiwuduotai.top/Article/details/gtwxvgflgs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gteszylmnu.html

[S51] C++：显式类型转换
来源：http://dali.hywenlv.cn/Article/details/gtgyfcyjqs.html

static_cast<double>(a) / b
来源：http://dali.xziqi.cn/Article/details/gtgemvodpd.html

[S52] C++：const 与 noexcept
来源：http://dali.iojbl.cn/Article/details/gthwlfqtpu.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gtihndoaei.html

[S53] C++：移动语义
来源：http://dali.quarkkingdee.top/Article/details/gtcikmijes.html

std::vector<int> w = std::move(v);
来源：http://dali.0kj1m.cn/Article/details/gtzrwxywix.html

[S54] C++：异常处理
来源：http://dali.shuidangran.top/Article/details/gtmdprixrj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fzhhl.top/Article/details/gtlfnrejwk.html

[S55] C++：结构化绑定
来源：http://dali.svipenyu.cn/Article/details/gtbsnkjges.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.andypj.xyz/Article/details/gtvcvritru.html

[S56] C++：optional
来源：http://dali.9152youxi.cn/Article/details/gtkfrhydxe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnxiangtu.top/Article/details/gtgtagjxpc.html

[S57] C++：编译期常量
来源：http://dali.feifeiyinyue.top/Article/details/gtdmnanvnj.html

constexpr int N = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtbaolfrst.html

[S58] C++：命名空间
来源：http://dali.yongpay.top/Article/details/gtbhcxjezb.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gtazmgcpbx.html

[S59] C++：静态断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspjmztxe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenjidiqi.icu/Article/details/gtbfyrehqj.html

[S60] C++：遍历并删除元素
来源：http://dali.tianlin.xyz/Article/details/gtbzcofvgk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aizwys.cn/Article/details/gtyxvesqaf.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtsoszsfsj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhengqikj.top/Article/details/gtbhslkpca.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtqndaaswq.html

[T01] Kotlin：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtptffgsel.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtscmwcrts.html

[T02] Kotlin：变量
来源：http://dali.vqdsnc.cn/Article/details/gtvndwbgto.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhongyouzk.top/Article/details/gtlxeiijqq.html

[T03] Kotlin：字符串模板
来源：http://dali.aizwys.cn/Article/details/gtsfngmizr.html

"值: $b"
来源：http://dali.yonumen.top/Article/details/gtutdxugcm.html

[T04] Kotlin：空安全
来源：http://dali.jinghuilouyu.cn/Article/details/gtupzxewdz.html

val n: String? = null;  n?.length
来源：http://dali.shzxlz.cn/Article/details/gtjrhkrsfx.html

[T05] Kotlin：when 表达式
来源：http://dali.cashguo.top/Article/details/gtugquzgoc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.haohaochexian.top/Article/details/gtnyrajthe.html

[T06] Kotlin：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkyrnuloq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.c1oappe.top/Article/details/gtqcvjquax.html

[T07] Kotlin：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gtcjxrxebg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.meibo888.top/Article/details/gtcidhbzco.html

[T08] Kotlin：数据类
来源：http://dali.316326.xyz/Article/details/gtwevwtjkv.html

data class User(val name: String, val age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gtqomkkivb.html

[T09] Kotlin：扩展函数
来源：http://dali.wangdashe.top/Article/details/gtuclkusmj.html

fun String.exclaim() = this + "!"
来源：http://dali.cheryme.top/Article/details/gtkqidkgry.html

[T10] Kotlin：默认参数
来源：http://dali.birdmap.top/Article/details/gtaaegmfct.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ydzc1.top/Article/details/gtokjsnakv.html

[T11] Kotlin：协程
来源：http://dali.jqgufenzy.top/Article/details/gtqigxlzgv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgfzy.top/Article/details/gtzdbyyirc.html

[T12] Kotlin：解构声明
来源：http://dali.dashuyun.cn/Article/details/gtggnlvtij.html

val (a, b) = Pair(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gtkonyuhid.html

[T13] Kotlin：只读 Map
来源：http://dali.quarkkingdee.top/Article/details/gtzywlwfif.html

val m = mapOf("a" to 1)
来源：http://dali.jiagoushi.top/Article/details/gtezanysfu.html

[T14] Kotlin：循环
来源：http://dali.hnqzz.top/Article/details/gtlairhhwb.html

for (i in 1..10) println(i)
来源：http://dali.cashguo.top/Article/details/gtmykoiqdq.html

[T15] Kotlin：接口
来源：http://dali.jianghu66.top/Article/details/gtklimltei.html

interface Shape { fun area(): Double }
来源：http://dali.zhengqikj.top/Article/details/gtpewcbdak.html

[T16] Swift：Hello World
来源：http://dali.wangdashe.top/Article/details/gtpyduxzns.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxffzfiz.html

[T17] Swift：变量与常量
来源：http://dali.hywenlv.cn/Article/details/gtteqjhcec.html

var a = 1;  let b = 2
来源：http://dali.jqgufenzy.top/Article/details/gtpkrhepee.html

[T18] Swift：字符串插值
来源：http://dali.sweek.top/Article/details/gtqbnnyjas.html

"值: \(b)"
来源：http://dali.kuanghao11.cn/Article/details/gtmlefnhqe.html

[T19] Swift：可选绑定
来源：http://dali.zhoulong.xyz/Article/details/gtpqufuocc.html

if let n = opt { print(n) }
来源：http://dali.9152youxi.cn/Article/details/gtqeezqmzp.html

[T20] Swift：数组操作
来源：http://dali.gaohongyu789.top/Article/details/gtdpkgsavv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.fzhhl.top/Article/details/gtokxgsbwn.html

[T21] Swift：遍历
来源：http://dali.cashguo.top/Article/details/gtajuvvzvt.html

for x in a { print(x) }
来源：http://dali.sxryk.cn/Article/details/gthylsxwjz.html

[T22] Swift：字典
来源：http://dali.tianlin.xyz/Article/details/gtajajectf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnqzz.top/Article/details/gtzamvonfv.html

[T23] Swift：函数
来源：http://dali.guowangkeji.top/Article/details/gtizxwdoce.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtverrmaef.html

[T24] Swift：闭包
来源：http://dali.hongshengwenyu.top/Article/details/gtkrekwlih.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtwvksimvv.html

[T25] Swift：结构体
来源：http://dali.daxiang520.top/Article/details/gtjyqrqlqg.html

struct P { var x: Int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvwubslb.html

[T26] Swift：类与重写
来源：http://dali.yuxming.cn/Article/details/gtbextloqy.html

class A: Base { override func f() {} }
来源：http://dali.xinyue.icu/Article/details/gtsxymbwvg.html

[T27] Swift：错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gtnevkqqvq.html

do { try f() } catch { print(error) }
来源：http://dali.jinqigufen.top/Article/details/gtwarqhhlf.html

[T28] Swift：枚举
来源：http://dali.smart0.xyz/Article/details/gtxranfflk.html

enum Color { case red, green }
来源：http://dali.jiagoushi.top/Article/details/gtccocdalm.html

[T29] Swift：guard 提前返回
来源：http://dali.gaohongyu789.top/Article/details/gtmsewuwgg.html

guard let x = opt else { return }
来源：http://dali.hnqzz.top/Article/details/gticflzees.html

[T30] Swift：协议
来源：http://dali.cucudq.cn/Article/details/gtxiazxjxt.html

protocol Shape { func area() -> Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufbender.html

[T31] Lua：Hello World
来源：http://dali.cashguo.top/Article/details/gtlsvsxoui.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtsoepztzc.html

[T32] Lua：局部变量
来源：http://dali.xuanzx.com/Article/details/gtbtsyittr.html

local a = 1
来源：http://dali.fengsongda.top/Article/details/gtcxtcoqqu.html

[T33] Lua：表（数组）
来源：http://dali.guannengcc.top/Article/details/gtwvxrdfxg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxuanxn.top/Article/details/gtrabhafsh.html

[T34] Lua：遍历表
来源：http://dali.c1oappe.top/Article/details/gtawaqiwgi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ybcxt.top/Article/details/gtvdyixczb.html

[T35] Lua：字典表
来源：http://dali.cashguo.top/Article/details/gtyqgtimeb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cqqwz.cn/Article/details/gtensymztb.html

[T36] Lua：函数
来源：http://dali.kuanghao11.cn/Article/details/gtmakryejh.html

function add(a, b) return a + b end
来源：http://dali.gaohongyu789.top/Article/details/gtmaatcgxv.html

[T37] Lua：字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gtxqhodmlo.html

"a" .. "b"
来源：http://dali.nwbrower.top/Article/details/gtpttyzmmv.html

[T38] Lua：条件
来源：http://dali.birdmap.top/Article/details/gtlavirgoh.html

if x > 0 then print("正") end
来源：http://dali.yangfankeji.com/Article/details/gtfgfmzpmj.html

[T39] Lua：模式匹配
来源：http://dali.tianlin.xyz/Article/details/gtzrdvcmmq.html

string.find(s, "%d+")
来源：http://dali.hywenlv.cn/Article/details/gtbvztzemt.html

[T40] Lua：元表
来源：http://dali.fengsongda.top/Article/details/gttrqlmxlf.html

setmetatable({}, { __index = base })
来源：http://dali.dashuyun.cn/Article/details/gtsyijljnv.html

[T41] Perl：Hello World
来源：http://dali.gzhubu.top/Article/details/gtxtoooixh.html

print "Hello\n";
来源：http://dali.xylfe.cn/Article/details/gtnrfntmsj.html

[T42] Perl：变量类型
来源：http://dali.0kj1m.cn/Article/details/gtfaoxhcbe.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.meibo888.top/Article/details/gtlicnjllj.html

[T43] Perl：字符串插值
来源：http://dali.ydzc1.top/Article/details/gtdqqvlunf.html

"值: $a"
来源：http://dali.mhx1999.top/Article/details/gtsrrvkfxi.html

[T44] Perl：条件
来源：http://dali.zhiwuduotai.top/Article/details/gtggokurxo.html

if ($a > 0) { print "正"; }
来源：http://dali.mhx1999.top/Article/details/gtwcyumzpw.html

[T45] Perl：数组遍历
来源：http://dali.gzhubu.top/Article/details/gtneqoblvs.html

for my $x (@arr) { print $x; }
来源：http://dali.gzhubu.top/Article/details/gtumpqtruv.html

[T46] Perl：哈希操作
来源：http://dali.yangfankeji.com/Article/details/gtuojnytqy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.vqdsnc.cn/Article/details/gtcyihzemz.html

[T47] Perl：正则捕获
来源：http://dali.9152youxi.cn/Article/details/gtwpjvahzc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258888.top/Article/details/gtkveupkfg.html

[T48] Perl：正则替换
来源：http://dali.tanke756.top/Article/details/gtjrzfjdye.html

$s =~ s/old/new/g;
来源：http://dali.meibo888.top/Article/details/gtbsjzkzyf.html

[T49] Perl：函数
来源：http://dali.cucudq.cn/Article/details/gtwmxuhzhm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtgxwctdhb.html

[T50] Perl：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtlksekswr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sxryk.cn/Article/details/gtntbqvlju.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.wangdashe.top/Article/details/gtwlkizbig.html

[T51] Scala：Hello World
来源：http://dali.yj20258888.top/Article/details/gtrifmhowb.html

println("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtxomkfhvd.html

[T52] Scala：变量
来源：http://dali.nwbrower.top/Article/details/gtvdmgbimb.html

val a = 1;  var b = 2
来源：http://dali.gotoacloud.top/Article/details/gtsxdgnxai.html

[T53] Scala：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtggfvpqvt.html

s"值: $b"
来源：http://dali.hammf.cn/Article/details/gtgrsesxsx.html

[T54] Scala：集合映射
来源：http://dali.tian-w.cn/Article/details/gtjziywbbj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cashguo.top/Article/details/gtaqopwiec.html

[T55] Scala：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gtjyibdbiy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yanxiufei.cn/Article/details/gtezmbvoty.html

[T56] Scala：样例类
来源：http://dali.fzhhl.top/Article/details/gtaaodpknw.html

case class User(name: String, age: Int)
来源：http://dali.fzhhl.top/Article/details/gtyhifrkof.html

[T57] Scala：模式匹配
来源：http://dali.c1oappe.top/Article/details/gtkhwbhcyz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ybcxt.top/Article/details/gthupxwuyd.html

[T58] Scala：函数定义
来源：http://dali.sweek.top/Article/details/gthtjqnmhi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sxryk.cn/Article/details/gtgxyrefxb.html

[T59] Scala：循环
来源：http://dali.hammf.cn/Article/details/gtgrmkjiak.html

for (i <- 1 to 10) println(i)
来源：http://dali.andypj.xyz/Article/details/gtvlrfotnr.html

[T60] Scala：折叠
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhlkhknz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hammf.cn/Article/details/gtrucipxfc.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtsbklcgnh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.havefunace.top/Article/details/gtpmdxupuy.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtxjinwplp.html

[U01] Py：创建虚拟环境
来源：http://dali.nwbrower.top/Article/details/gtutegadli.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.daria6918.cn/Article/details/gtxrzxdmfa.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nanxinkj.top/Article/details/gtwcshiwsz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.redwolf501.top/Article/details/gtljaagrce.html

[U03] Py：加载 .env 配置
来源：http://dali.yj20258888.top/Article/details/gtumsuoevj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.c1oappe.top/Article/details/gtufjdljhp.html

[U04] Py：变量调试打印
来源：http://dali.meibo888.top/Article/details/gtsggthmgr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.kuanghao11.cn/Article/details/gtveqtbing.html

[U05] Py：列表去重且保序
来源：http://dali.jiagoushi.top/Article/details/gtosbzzwhg.html

list(dict.fromkeys(arr))
来源：http://dali.sxryk.cn/Article/details/gtbfhlzexu.html

[U06] Py：合并两个字典
来源：http://dali.jlsjyb.cn/Article/details/gtqufwsabp.html

{**a, **b}
来源：http://dali.aibaodan.cn/Article/details/gtsjunuqjm.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gtizmapkrh.html

{v: k for k, v in d.items()}
来源：http://dali.dianchejie.cn/Article/details/gtlxvyarsd.html

[U08] Py：展平二维列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqotvrmn.html

[y for x in nested for y in x]
来源：http://dali.quarkkingdee.top/Article/details/gttlvpupnt.html

[U09] Py：字典取最大值的键
来源：http://dali.haohaochexian.top/Article/details/gthocxjfrn.html

max(d, key=d.get)
来源：http://dali.hnqzz.top/Article/details/gtvwzbdspe.html

[U10] Py：按值排序字典
来源：http://dali.xuetiantiany.cn/Article/details/gtxflbpfpd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shuidangran.top/Article/details/gtiyhgfklj.html

[U11] Py：生成器表达式
来源：http://dali.daxiang520.top/Article/details/gtgnzvrqkq.html

(x * 2 for x in arr)
来源：http://dali.jqgufenzy.top/Article/details/gtiekyzury.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shangyingyoupin.top/Article/details/gtopuqrldw.html

Counter(arr).most_common(3)
来源：http://dali.birdmap.top/Article/details/gtazimpydf.html

[U13] Py：固定长度队列
来源：http://dali.haohaochexian.top/Article/details/gtpyhkronz.html

deque(maxlen=10)
来源：http://dali.ppjwa.cn/Article/details/gtjvdawyuv.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258888.top/Article/details/gtxmvlgibj.html

defaultdict(list)
来源：http://dali.tanke756.top/Article/details/gtouwutkog.html

[U15] Py：高精度计时
来源：http://dali.sxryk.cn/Article/details/gtkuutkjwx.html

t = time.perf_counter()
来源：http://dali.redwolf501.top/Article/details/gtfoulahdr.html

[U16] Py：命令行参数解析
来源：http://dali.zhiwuduotai.top/Article/details/gtsknwurpq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.birdmap.top/Article/details/gtomrystyi.html

[U17] Py：初始化日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszoanxev.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.vqdsnc.cn/Article/details/gttgfjexoz.html

[U18] Py：预编译正则
来源：http://dali.ybcxt.top/Article/details/gtuvuzwrup.html

pat = re.compile(r"\d+")
来源：http://dali.gaohongyu789.top/Article/details/gtxzcwkoir.html

[U19] Py：正则替换带回调
来源：http://dali.chenjidiqi.icu/Article/details/gtlqwztuzv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jiagoushi.top/Article/details/gthlkajboh.html

[U20] Py：缓存函数结果
来源：http://dali.hnqzz.top/Article/details/gtajkdsgcm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenzaomai.com/Article/details/gtwyiihtkk.html

[U21] Py：自定义上下文管理器
来源：http://dali.cqqwz.cn/Article/details/gtzvckslrj.html

@contextlib.contextmanager
来源：http://dali.sysykeji.top/Article/details/gtsgaotroc.html

[U22] Py：矩阵转置
来源：http://dali.cqqwz.cn/Article/details/gtclvlhgsk.html

list(zip(*m))
来源：http://dali.shuidangran.top/Article/details/gtipuzumvc.html

[U23] Py：分块读取大文件
来源：http://dali.xinyue.icu/Article/details/gtlpemxoes.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.daxiang520.top/Article/details/gtokuxxoyl.html

[U24] Py：路径操作
来源：http://dali.zhixingplan.top/Article/details/gtcwfnzuit.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gtklvbbekb.html

[U25] Py：CSV 按字典读
来源：http://dali.bjfxy.top/Article/details/gtlwsdqvmn.html

csv.DictReader(f)
来源：http://dali.yonumen.top/Article/details/gtohcafudu.html

[U26] Py：并发下载
来源：http://dali.bjfxy.top/Article/details/gthimyyxfu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jianghu66.top/Article/details/gtublceshh.html

[U27] Py：异步 HTTP
来源：http://dali.jianghu66.top/Article/details/gtezirkhxg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cqqwz.cn/Article/details/gtyilwbvmm.html

[U28] Py：类型别名
来源：http://dali.yvedp.cn/Article/details/gtdwryqiex.html

UserId = int
来源：http://dali.chenjidiqi.icu/Article/details/gtqoszalqm.html

[U29] Py：属性校验
来源：http://dali.nanxinkj.top/Article/details/gtnmjsgekk.html

@property 与 @x.setter 配合
来源：http://dali.snrcjt.cn/Article/details/gtbsuwygmf.html

[U30] Py：数据类
来源：http://dali.guannengcc.top/Article/details/gtsnilspcj.html

@dataclass(slots=True)
来源：http://dali.jinqigufen.top/Article/details/gtdxdtnnpp.html

[U31] Py：单测
来源：http://dali.gaohongyu789.top/Article/details/gtntvjnauk.html

python -m pytest -q
来源：http://dali.iojbl.cn/Article/details/gtmpeidooe.html

[U32] Py：代码格式化
来源：http://dali.ivvv.top/Article/details/gtvweuwhmo.html

ruff format . && ruff check --fix .
来源：http://dali.cqqwz.cn/Article/details/gtbqtisxju.html

[U33] Py：打包发布
来源：http://dali.yuanzhike.top/Article/details/gtwoyufxmm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nanxinkj.top/Article/details/gtkeqyomxf.html

[U34] Py：判断编码
来源：http://dali.birdmap.top/Article/details/gtwfagulvo.html

chardet.detect(raw)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhhvqolq.html

[U35] Py：发送邮件
来源：http://dali.andypj.xyz/Article/details/gtyomssjnn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jlsjyb.cn/Article/details/gtazoaxwxx.html

[U36] Py：定时任务
来源：http://dali.feifeiyinyue.top/Article/details/gtgajrhhrn.html

schedule.every(10).minutes.do(job)
来源：http://dali.shuidangran.top/Article/details/gtjkjwzxlb.html

[U37] Py：读写 Excel
来源：http://dali.vqdsnc.cn/Article/details/gtrcpmetfl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jyoumei.cn/Article/details/gtrgszgrrk.html

[U38] Py：获取脚本所在目录
来源：http://dali.redwolf501.top/Article/details/gtkofgzyub.html

Path(__file__).resolve().parent
来源：http://dali.wangshuangyany.cn/Article/details/gtmmdnosrd.html

[U39] Py：判断是否在交互环境
来源：http://dali.shuidangran.top/Article/details/gtxbwxiuss.html

sys.stdout.isatty()
来源：http://dali.yj20258888.top/Article/details/gthqxzoaqy.html

[U40] Py：打印到标准错误
来源：http://dali.smart0.xyz/Article/details/gtxjtenfow.html

print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gtzvyhvzlo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.9152youxi.cn/Article/details/gtbkqiulug.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.guowangkeji.top/Article/details/gtbhtxqvaw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhiwuduotai.top/Article/details/gtwclqhmkd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yonumen.top/Article/details/gtvxstavyz.html

[U43] PHP：声明命名空间
来源：http://dali.cashguo.top/Article/details/gtfhdhwvum.html

namespace App\Http;
来源：http://dali.hfpthk.cn/Article/details/gtflgghkfr.html

[U44] PHP：开启严格类型
来源：http://dali.birdmap.top/Article/details/gtvmdtbhto.html

declare(strict_types=1);
来源：http://dali.pycfn.com/Article/details/gtyikzwxlz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.meibo888.top/Article/details/gthgspgxxg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gttpzrtglu.html

[U46] PHP：可空类型
来源：http://dali.redwolf501.top/Article/details/gtdzgymffw.html

?string $name = null
来源：http://dali.sweek.top/Article/details/gttlotildg.html

[U47] PHP：联合类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpujvqxd.html

int|string $id
来源：http://dali.daxiang520.top/Article/details/gtzniswxdp.html

[U48] PHP：纯枚举
来源：http://dali.birdmap.top/Article/details/gtgczqrpap.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpojpsqvw.html

[U49] PHP：只读属性
来源：http://dali.aibaodan.cn/Article/details/gthoofsqwh.html

public readonly string $name
来源：http://dali.quarkkingdee.top/Article/details/gtooejytwg.html

[U50] PHP：构造器属性提升
来源：http://dali.hnqzz.top/Article/details/gtgfvlcwon.html

public function __construct(private int $id) {}
来源：http://dali.yangfankeji.com/Article/details/gtfsccgnzg.html

[U51] PHP：数组解构
来源：http://dali.zdqjudy.top/Article/details/gtuthknkug.html

[$a, $b] = $arr;
来源：http://dali.zhoulong.xyz/Article/details/gtcrxgqreu.html

[U52] PHP：箭头函数
来源：http://dali.yj20258888.top/Article/details/gtqdgiocad.html

$double = fn($x) => $x * 2;
来源：http://dali.yuxming.cn/Article/details/gtljlusens.html

[U53] PHP：空合并运算符
来源：http://dali.redwolf501.top/Article/details/gtivigfgks.html

$v = $a ?? $b ?? "default";
来源：http://dali.pycfn.com/Article/details/gtfnazlbqy.html

[U54] PHP：空安全调用
来源：http://dali.xuetiantiany.cn/Article/details/gtqhuaitjr.html

$obj?->method()
来源：http://dali.zhiwuduotai.top/Article/details/gthilegrzk.html

[U55] PHP：match 表达式
来源：http://dali.kuanghao11.cn/Article/details/gtlbhmzqpt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jyoumei.cn/Article/details/gtrqlmrgbs.html

[U56] PHP：命名参数
来源：http://dali.aizwys.cn/Article/details/gtikfvlbvv.html

f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtkskuymtj.html

[U57] PHP：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtlvsupdrc.html

"值: {$a}"
来源：http://dali.chenjidiqi.icu/Article/details/gtqdzkxdix.html

[U58] PHP：数组三件套
来源：http://dali.nanxinkj.top/Article/details/gtiuuxcwkp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cucudq.cn/Article/details/gtomdiwxik.html

[U59] PHP：自定义排序
来源：http://dali.zhiwuduotai.top/Article/details/gtkxraiize.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yangfankeji.com/Article/details/gtzdbynhjt.html

[U60] PHP：JSON 编解码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqgorass.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.andypj.xyz/Article/details/gtvhblstqy.html

[U61] PHP：正则
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehiwyvgd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gtwgyldrbx.html

[U62] PHP：日期对象
来源：http://dali.9152youxi.cn/Article/details/gtlysvtdnv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yuxming.cn/Article/details/gtdgyuqteu.html

[U63] PHP：文件读写
来源：http://dali.ybcxt.top/Article/details/gtodmthcrg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.havefunace.top/Article/details/gtvzgcqkup.html

[U64] PHP：目录遍历
来源：http://dali.jqgfzy.top/Article/details/gtrxgyijjs.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gotoacloud.top/Article/details/gtwcwyyszt.html

[U65] PHP：会话
来源：http://dali.gzhubu.top/Article/details/gttbpxierv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtxzidmgys.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gtkhoivurp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.c1oappe.top/Article/details/gtmwzjnxzj.html

[U67] PHP：处理文件上传
来源：http://dali.shuidangran.top/Article/details/gtwczwwloq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.birdmap.top/Article/details/gtaxcadtuk.html

[U68] PHP：PDO 连接
来源：http://dali.sufxvd.cn/Article/details/gtfjnpsenf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yuanzhike.top/Article/details/gtawuhxhdx.html

[U69] PHP：PDO 预处理
来源：http://dali.haohaochexian.top/Article/details/gthalefscp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ydzc1.top/Article/details/gtgdfojpuo.html

[U70] PHP：PDO 事务
来源：http://dali.kuanghao11.cn/Article/details/gtxjnwwgqe.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttacabofo.html

[U71] PHP：抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gtfrzrwxea.html

throw new RuntimeException("失败", 500);
来源：http://dali.ppjwa.cn/Article/details/gtlogffzjd.html

[U72] PHP：写错误日志
来源：http://dali.cqqwz.cn/Article/details/gtuupfnvdi.html

error_log("失败: " . $e->getMessage());
来源：http://dali.tian-w.cn/Article/details/gtcevqwpfd.html


<!-- 参考信息 -->