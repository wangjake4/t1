代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.yangfankeji.com/Article/details/gt2lachbajm.html

[S49] C++：写文件
来源：http://dali.c1oappe.top/Article/details/gt2jyaanfix.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cqqwz.cn/Article/details/gt2ixjpduvp.html

[S50] C++：格式化数字
来源：http://dali.gzhubu.top/Article/details/gt2zmdiuytc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.andypj.xyz/Article/details/gt2gywoddmn.html

[S51] C++：显式类型转换
来源：http://dali.iojbl.cn/Article/details/gt2yhvwwxah.html

static_cast<double>(a) / b
来源：http://dali.hongshengwenyu.top/Article/details/gt2fwbkwykf.html

[S52] C++：const 与 noexcept
来源：http://dali.0kj1m.cn/Article/details/gt2igcomflh.html

int size() const noexcept { return n_; }
来源：http://dali.yj202588.top/Article/details/gt2dxobxkzm.html

[S53] C++：移动语义
来源：http://dali.jinqigfzy.top/Article/details/gt2nhgtgqbi.html

std::vector<int> w = std::move(v);
来源：http://dali.316326.xyz/Article/details/gt2jtnzymra.html

[S54] C++：异常处理
来源：http://dali.iojbl.cn/Article/details/gt2xklcbxsx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.meibo888.top/Article/details/gt2yjxfjhoh.html

[S55] C++：结构化绑定
来源：http://dali.jqgufenzy.top/Article/details/gt2hqnqkfua.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gt2bttunqxg.html

[S56] C++：optional
来源：http://dali.hammf.cn/Article/details/gt2fbqrkddn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.316326.xyz/Article/details/gt2naxqfxgn.html

[S57] C++：编译期常量
来源：http://dali.pengpengdd.cyou/Article/details/gt2wrnvkffw.html

constexpr int N = 10;
来源：http://dali.gogol.net.cn/Article/details/gt2vbxeusxv.html

[S58] C++：命名空间
来源：http://dali.jinqigufen.top/Article/details/gt2dfhazzld.html

namespace ns { int f() { return 1; } }
来源：http://dali.bjfxy.top/Article/details/gt2gytfqqre.html

[S59] C++：静态断言
来源：http://dali.birdmap.top/Article/details/gt2rqmztyzu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jianghu66.top/Article/details/gt2gkcaqapy.html

[S60] C++：遍历并删除元素
来源：http://dali.shzxlz.cn/Article/details/gt2mnzhgkbs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.redwolf501.top/Article/details/gt2zqehponp.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2tartjrxw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shangyingyoupin.top/Article/details/gt2wqeelazg.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2uqbcgkro.html

[T01] Kotlin：Hello World
来源：http://dali.sweek.top/Article/details/gt2krjancqt.html

println("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gt2pghmqkde.html

[T02] Kotlin：变量
来源：http://dali.quarkkingdee.top/Article/details/gt2ojyaifpm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ybcxt.top/Article/details/gt2bjbrxsyk.html

[T03] Kotlin：字符串模板
来源：http://dali.tanke756.top/Article/details/gt2rmeioksn.html

"值: $b"
来源：http://dali.xziqi.cn/Article/details/gt2yrfzhgwr.html

[T04] Kotlin：空安全
来源：http://dali.xinyue.icu/Article/details/gt2yscktarm.html

val n: String? = null;  n?.length
来源：http://dali.jyoumei.cn/Article/details/gt2kwelbqyz.html

[T05] Kotlin：when 表达式
来源：http://dali.cqqwz.cn/Article/details/gt2eghedihy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fzhhl.top/Article/details/gt2epodxdht.html

[T06] Kotlin：集合映射
来源：http://dali.gotoacloud.top/Article/details/gt2ngyhpgxb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.bjfxy.top/Article/details/gt2fqixcgll.html

[T07] Kotlin：集合过滤
来源：http://dali.yuxming.cn/Article/details/gt2rnodjitq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hywenlv.cn/Article/details/gt2iresrmqk.html

[T08] Kotlin：数据类
来源：http://dali.zhengqikj.top/Article/details/gt2illcynns.html

data class User(val name: String, val age: Int)
来源：http://dali.meibo888.top/Article/details/gt2rwsbeuui.html

[T09] Kotlin：扩展函数
来源：http://dali.guowangkeji.top/Article/details/gt2fjfcittg.html

fun String.exclaim() = this + "!"
来源：http://dali.gotoacloud.top/Article/details/gt2pceahygg.html

[T10] Kotlin：默认参数
来源：http://dali.aizwys.cn/Article/details/gt2tzsuyldh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aibaodan.cn/Article/details/gt2dwhnjjwj.html

[T11] Kotlin：协程
来源：http://dali.dashuyun.cn/Article/details/gt2hufbmden.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gotoacloud.top/Article/details/gt2fxylmjxz.html

[T12] Kotlin：解构声明
来源：http://dali.fzhhl.top/Article/details/gt2oesznowa.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swxreqtc.html

[T13] Kotlin：只读 Map
来源：http://dali.feifeiyinyue.top/Article/details/gt2ybuqoxpt.html

val m = mapOf("a" to 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2tayaxfgq.html

[T14] Kotlin：循环
来源：http://dali.chenlongwang.top/Article/details/gt2lkecsmcm.html

for (i in 1..10) println(i)
来源：http://dali.ydzc1.top/Article/details/gt2cvqppcrj.html

[T15] Kotlin：接口
来源：http://dali.hnqzz.top/Article/details/gt2rsqiqtxv.html

interface Shape { fun area(): Double }
来源：http://dali.xziqi.cn/Article/details/gt2jelxmckb.html

[T16] Swift：Hello World
来源：http://dali.pycfn.com/Article/details/gt2wwkpqnrw.html

print("Hello")
来源：http://dali.ydzc1.top/Article/details/gt2cqoelhjr.html

[T17] Swift：变量与常量
来源：http://dali.guannengcc.top/Article/details/gt2wijsarbs.html

var a = 1;  let b = 2
来源：http://dali.snrcjt.cn/Article/details/gt2nhjkcnju.html

[T18] Swift：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gt2kqrtgzcc.html

"值: \(b)"
来源：http://dali.quarkkingdee.top/Article/details/gt2ydjiygwo.html

[T19] Swift：可选绑定
来源：http://dali.nanxuanxn.top/Article/details/gt2asgqvcow.html

if let n = opt { print(n) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2miazxhmv.html

[T20] Swift：数组操作
来源：http://dali.ehwqpu.com/Article/details/gt2cogbfkdu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj202588.top/Article/details/gt2zezwxsnd.html

[T21] Swift：遍历
来源：http://dali.hammf.cn/Article/details/gt2qropycao.html

for x in a { print(x) }
来源：http://dali.wangdashe.top/Article/details/gt2ddsyfshy.html

[T22] Swift：字典
来源：http://dali.shzxlz.cn/Article/details/gt2bnskodtp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2euqhkuax.html

[T23] Swift：函数
来源：http://dali.tian-w.cn/Article/details/gt2flitabjg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yongpay.top/Article/details/gt2kpspmwun.html

[T24] Swift：闭包
来源：http://dali.sxryk.cn/Article/details/gt2sapurwaw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gt2xuselhaq.html

[T25] Swift：结构体
来源：http://dali.smart0.xyz/Article/details/gt2mswvlwkw.html

struct P { var x: Int }
来源：http://dali.ivvv.top/Article/details/gt2jlgmwqoe.html

[T26] Swift：类与重写
来源：http://dali.daxiang520.top/Article/details/gt2jjyhyyfe.html

class A: Base { override func f() {} }
来源：http://dali.xuanzx.com/Article/details/gt2xxhrhdwq.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybsjrwrj.html

do { try f() } catch { print(error) }
来源：http://dali.daria6918.cn/Article/details/gt2bmdqhzvk.html

[T28] Swift：枚举
来源：http://dali.jlsjyb.cn/Article/details/gt2bnwgxahu.html

enum Color { case red, green }
来源：http://dali.sysykeji.top/Article/details/gt2inszlsws.html

[T29] Swift：guard 提前返回
来源：http://dali.guowangkeji.top/Article/details/gt2zekiylyg.html

guard let x = opt else { return }
来源：http://dali.mhx1999.top/Article/details/gt2qrdvcbhj.html

[T30] Swift：协议
来源：http://dali.ybcxt.top/Article/details/gt2mecnhqme.html

protocol Shape { func area() -> Double }
来源：http://dali.chenlongwang.top/Article/details/gt2rjmkxhfk.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aufdfcvv.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gt2tsfbgoog.html

[T32] Lua：局部变量
来源：http://dali.vqdsnc.cn/Article/details/gt2mlbguyrl.html

local a = 1
来源：http://dali.nwbrower.top/Article/details/gt2dfppgttx.html

[T33] Lua：表（数组）
来源：http://dali.hongshengwenyu.top/Article/details/gt2gyqlhjsa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.fzhhl.top/Article/details/gt2xntpbiai.html

[T34] Lua：遍历表
来源：http://dali.zhoulong.xyz/Article/details/gt2fuiufydr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.meibo888.top/Article/details/gt2orsmuxlk.html

[T35] Lua：字典表
来源：http://dali.nanxinkj.top/Article/details/gt2eaftertd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhengqikj.top/Article/details/gt2ybxbvoyr.html

[T36] Lua：函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2fvgwxarf.html

function add(a, b) return a + b end
来源：http://dali.haohaochexian.top/Article/details/gt2dqqywtzd.html

[T37] Lua：字符串拼接
来源：http://dali.sweek.top/Article/details/gt2epykelww.html

"a" .. "b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfazfhlu.html

[T38] Lua：条件
来源：http://dali.nanxuanxn.top/Article/details/gt2mjftrqaf.html

if x > 0 then print("正") end
来源：http://dali.shuidangran.top/Article/details/gt2epnisuxd.html

[T39] Lua：模式匹配
来源：http://dali.daria6918.cn/Article/details/gt2rvowklii.html

string.find(s, "%d+")
来源：http://dali.zhixingplan.top/Article/details/gt2umlkytmv.html

[T40] Lua：元表
来源：http://dali.gaohongyu789.top/Article/details/gt2oymptsxl.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rhoobfku.html

[T41] Perl：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2ksrczprz.html

print "Hello\n";
来源：http://dali.snrcjt.cn/Article/details/gt2rqfxaocm.html

[T42] Perl：变量类型
来源：http://dali.hnxiangtu.top/Article/details/gt2klzabzkz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.daria6918.cn/Article/details/gt2qnenahly.html

[T43] Perl：字符串插值
来源：http://dali.yuxming.cn/Article/details/gt2gwbmzlpc.html

"值: $a"
来源：http://dali.snrcjt.cn/Article/details/gt2jwticvcr.html

[T44] Perl：条件
来源：http://dali.yuxming.cn/Article/details/gt2srfhblna.html

if ($a > 0) { print "正"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zlkunkyd.html

[T45] Perl：数组遍历
来源：http://dali.aizwys.cn/Article/details/gt2iceggtbm.html

for my $x (@arr) { print $x; }
来源：http://dali.zycfv.cn/Article/details/gt2hcgyrzig.html

[T46] Perl：哈希操作
来源：http://dali.smart0.xyz/Article/details/gt2rlnnztgy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.smart0.xyz/Article/details/gt2zcxniqal.html

[T47] Perl：正则捕获
来源：http://dali.tian-w.cn/Article/details/gt2cmxbkkcd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jianghu66.top/Article/details/gt2lmvkcxqk.html

[T48] Perl：正则替换
来源：http://dali.chenzaomai.com/Article/details/gt2bdmgpsmc.html

$s =~ s/old/new/g;
来源：http://dali.zdqjudy.top/Article/details/gt2uuefcwca.html

[T49] Perl：函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2owygjmkg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2uisxbcaf.html

[T50] Perl：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gt2sitsmdrh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hnqzz.top/Article/details/gt2znhsjdxg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.0kj1m.cn/Article/details/gt2hravtzss.html

[T51] Scala：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2hykhibqe.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gt2ltxsumtd.html

[T52] Scala：变量
来源：http://dali.yangfankeji.com/Article/details/gt2huhzlhsp.html

val a = 1;  var b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2fdyxsqej.html

[T53] Scala：字符串插值
来源：http://dali.gzhubu.top/Article/details/gt2ogbsnkqw.html

s"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gt2nlfjshqo.html

[T54] Scala：集合映射
来源：http://dali.meibo888.top/Article/details/gt2gobbhejv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ozzyrgzu.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tbkmwcmu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj20258888.top/Article/details/gt2ptawhemw.html

[T56] Scala：样例类
来源：http://dali.pycfn.com/Article/details/gt2ktdvuugz.html

case class User(name: String, age: Int)
来源：http://dali.fzhhl.top/Article/details/gt2kyijwdwi.html

[T57] Scala：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gt2wrchjobr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shuidangran.top/Article/details/gt2yfpjdoxr.html

[T58] Scala：函数定义
来源：http://dali.nanxuanxn.top/Article/details/gt2gbvffmmn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qtsodwzn.html

[T59] Scala：循环
来源：http://dali.xziqi.cn/Article/details/gt2vnrxbffy.html

for (i <- 1 to 10) println(i)
来源：http://dali.fengsongda.top/Article/details/gt2plciboal.html

[T60] Scala：折叠
来源：http://dali.wangshuangyany.cn/Article/details/gt2cruhhneo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ydzc1.top/Article/details/gt2pqmsvslw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2muooheiu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2qdlyfvvz.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2mznwqiuh.html

[U01] Py：创建虚拟环境
来源：http://dali.snrcjt.cn/Article/details/gt2effrubww.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ppjwa.cn/Article/details/gt2egyhhtyh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj20258.top/Article/details/gt2woojjgxm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.aibaodan.cn/Article/details/gt2sofepfsw.html

[U03] Py：加载 .env 配置
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dobgghuc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shzxlz.cn/Article/details/gt2seuvnlsq.html

[U04] Py：变量调试打印
来源：http://dali.yongpay.top/Article/details/gt2ymhkvzco.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cdnleiting.top/Article/details/gt2nrxrvbth.html

[U05] Py：列表去重且保序
来源：http://dali.gogol.net.cn/Article/details/gt2abnwzpwx.html

list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lmipqrvl.html

[U06] Py：合并两个字典
来源：http://dali.hywenlv.cn/Article/details/gt2lkvzoryg.html

{**a, **b}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hgbewlxt.html

[U07] Py：反转字典键值
来源：http://dali.snrcjt.cn/Article/details/gt2pmuepvhz.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxhefnzu.html

[U08] Py：展平二维列表
来源：http://dali.jqgufenzy.top/Article/details/gt2tclamzaj.html

[y for x in nested for y in x]
来源：http://dali.jlsjyb.cn/Article/details/gt2tsdazoey.html

[U09] Py：字典取最大值的键
来源：http://dali.chenzaomai.com/Article/details/gt2wewsahev.html

max(d, key=d.get)
来源：http://dali.smart0.xyz/Article/details/gt2cogpahfm.html

[U10] Py：按值排序字典
来源：http://dali.andypj.xyz/Article/details/gt2qotuojzg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.feifeiyinyue.top/Article/details/gt2zheocdsu.html

[U11] Py：生成器表达式
来源：http://dali.cucudq.cn/Article/details/gt2hrbsajsi.html

(x * 2 for x in arr)
来源：http://dali.xylfe.cn/Article/details/gt2oomzdkkf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jqgfzy.top/Article/details/gt2xpyhdxtv.html

Counter(arr).most_common(3)
来源：http://dali.jyoumei.cn/Article/details/gt2yrhgvnjl.html

[U13] Py：固定长度队列
来源：http://dali.tanke756.top/Article/details/gt2msxkjqro.html

deque(maxlen=10)
来源：http://dali.jianghu66.top/Article/details/gt2vjvbhbpu.html

[U14] Py：分组收集到列表
来源：http://dali.zdqjudy.top/Article/details/gt2guribeps.html

defaultdict(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2upjamhhu.html

[U15] Py：高精度计时
来源：http://dali.gaohongyu789.top/Article/details/gt2qtmwwjjs.html

t = time.perf_counter()
来源：http://dali.haohaochexian.top/Article/details/gt2gtfnwbgm.html

[U16] Py：命令行参数解析
来源：http://dali.quarkkingdee.top/Article/details/gt2cvoazljz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jiagoushi.top/Article/details/gt2btkitnvh.html

[U17] Py：初始化日志
来源：http://dali.guowangkeji.top/Article/details/gt2llyykwok.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jqgfzy.top/Article/details/gt2bfiuhqod.html

[U18] Py：预编译正则
来源：http://dali.tian-w.cn/Article/details/gt2hxgrbypx.html

pat = re.compile(r"\d+")
来源：http://dali.iojbl.cn/Article/details/gt2ajushtry.html

[U19] Py：正则替换带回调
来源：http://dali.hammf.cn/Article/details/gt2wpguzmmj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nxmsmlvr.html

[U20] Py：缓存函数结果
来源：http://dali.quarkkingdee.top/Article/details/gt2dsftmmoh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yanxiufei.cn/Article/details/gt2viqwaxin.html

[U21] Py：自定义上下文管理器
来源：http://dali.yuanzhike.top/Article/details/gt2lcnwfyzz.html

@contextlib.contextmanager
来源：http://dali.cucudq.cn/Article/details/gt2gwdmdeuu.html

[U22] Py：矩阵转置
来源：http://dali.nwbrower.top/Article/details/gt2ronlqpzr.html

list(zip(*m))
来源：http://dali.gogol.net.cn/Article/details/gt2hzjmbexy.html

[U23] Py：分块读取大文件
来源：http://dali.nanxuanxn.top/Article/details/gt2rnublqxp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhixingplan.top/Article/details/gt2uwpmnrsv.html

[U24] Py：路径操作
来源：http://dali.wangshuangyany.cn/Article/details/gt2upawyxha.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gt2ttoyinfi.html

[U25] Py：CSV 按字典读
来源：http://dali.tanke756.top/Article/details/gt2vpqqznyl.html

csv.DictReader(f)
来源：http://dali.aibaodan.cn/Article/details/gt2pkapilhg.html

[U26] Py：并发下载
来源：http://dali.cucudq.cn/Article/details/gt2atmsflda.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.daria6918.cn/Article/details/gt2kgegaxne.html

[U27] Py：异步 HTTP
来源：http://dali.cqqwz.cn/Article/details/gt2ahtycjzh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gogol.net.cn/Article/details/gt2aipuxypc.html

[U28] Py：类型别名
来源：http://dali.gzhubu.top/Article/details/gt2offrkywr.html

UserId = int
来源：http://dali.fzhhl.top/Article/details/gt2aybckofv.html

[U29] Py：属性校验
来源：http://dali.hnqzz.top/Article/details/gt2hgoauevh.html

@property 与 @x.setter 配合
来源：http://dali.jinqigfzy.top/Article/details/gt2ltrjqcph.html

[U30] Py：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ochhjlcv.html

@dataclass(slots=True)
来源：http://dali.hnxiangtu.top/Article/details/gt2aifguucy.html

[U31] Py：单测
来源：http://dali.iojbl.cn/Article/details/gt2biksfqbb.html

python -m pytest -q
来源：http://dali.shzxlz.cn/Article/details/gt2tgsiqumr.html

[U32] Py：代码格式化
来源：http://dali.tanke756.top/Article/details/gt2wmmpnibi.html

ruff format . && ruff check --fix .
来源：http://dali.jqgufenzy.top/Article/details/gt2ibdbhlyh.html

[U33] Py：打包发布
来源：http://dali.sufxvd.cn/Article/details/gt2clftjzpv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sgwleayy.html

[U34] Py：判断编码
来源：http://dali.jqgfzy.top/Article/details/gt2elbqnevc.html

chardet.detect(raw)
来源：http://dali.316326.xyz/Article/details/gt2lomzsmii.html

[U35] Py：发送邮件
来源：http://dali.bjfxy.top/Article/details/gt2maoisngm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.guannengcc.top/Article/details/gt2afyywsbx.html

[U36] Py：定时任务
来源：http://dali.shuidangran.top/Article/details/gt2niqakrem.html

schedule.every(10).minutes.do(job)
来源：http://dali.quarkkingdee.top/Article/details/gt2szdxbqro.html

[U37] Py：读写 Excel
来源：http://dali.ppjwa.cn/Article/details/gt2abnqfdpk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.chenzaomai.com/Article/details/gt2eroswrpm.html

[U38] Py：获取脚本所在目录
来源：http://dali.sxryk.cn/Article/details/gt2ifjgxcfr.html

Path(__file__).resolve().parent
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pkgcxdpu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zycfv.cn/Article/details/gt2alncwgdn.html

sys.stdout.isatty()
来源：http://dali.yonumen.top/Article/details/gt2amrpslbn.html

[U40] Py：打印到标准错误
来源：http://dali.smart0.xyz/Article/details/gt2pwmizpus.html

print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gt2domhagzb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gaohongyu789.top/Article/details/gt2fzjjwrpk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yueranfly.top/Article/details/gt2rnkwihuy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yanxiufei.cn/Article/details/gt2qvbakqsl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xinyue.icu/Article/details/gt2etxsthvo.html

[U43] PHP：声明命名空间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fhybjwxl.html

namespace App\Http;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wfjevuvf.html

[U44] PHP：开启严格类型
来源：http://dali.redwolf501.top/Article/details/gt2cutuhumo.html

declare(strict_types=1);
来源：http://dali.ydzc1.top/Article/details/gt2elkezrcj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.fzhhl.top/Article/details/gt2oynainhz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2aoanpehn.html

[U46] PHP：可空类型
来源：http://dali.xinyue.icu/Article/details/gt2kctfyfuk.html

?string $name = null
来源：http://dali.iojbl.cn/Article/details/gt2uhxvukrn.html

[U47] PHP：联合类型
来源：http://dali.gogol.net.cn/Article/details/gt2ozvwpbkj.html

int|string $id
来源：http://dali.yonumen.top/Article/details/gt2faaozfmp.html

[U48] PHP：纯枚举
来源：http://dali.birdmap.top/Article/details/gt2otwepfyb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.tanke756.top/Article/details/gt2xqgyprvn.html

[U49] PHP：只读属性
来源：http://dali.jianghu66.top/Article/details/gt2vhujklcp.html

public readonly string $name
来源：http://dali.chenlongwang.top/Article/details/gt2nqmrzyvi.html

[U50] PHP：构造器属性提升
来源：http://dali.chenlongwang.top/Article/details/gt2fzolnhop.html

public function __construct(private int $id) {}
来源：http://dali.tanke756.top/Article/details/gt2ddelrein.html

[U51] PHP：数组解构
来源：http://dali.sufxvd.cn/Article/details/gt2ackcqwdz.html

[$a, $b] = $arr;
来源：http://dali.ehwqpu.com/Article/details/gt2mveuonrh.html

[U52] PHP：箭头函数
来源：http://dali.yuxming.cn/Article/details/gt2zmndsqhn.html

$double = fn($x) => $x * 2;
来源：http://dali.daria6918.cn/Article/details/gt2ehjanill.html

[U53] PHP：空合并运算符
来源：http://dali.zdqjudy.top/Article/details/gt2vqilbrnp.html

$v = $a ?? $b ?? "default";
来源：http://dali.cucudq.cn/Article/details/gt2ybkoymdz.html

[U54] PHP：空安全调用
来源：http://dali.xuetiantiany.cn/Article/details/gt2yyffceug.html

$obj?->method()
来源：http://dali.chenjidiqi.icu/Article/details/gt2soaceeup.html

[U55] PHP：match 表达式
来源：http://dali.ybcxt.top/Article/details/gt2zuhyumme.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.gaohongyu789.top/Article/details/gt2xosyoaax.html

[U56] PHP：命名参数
来源：http://dali.wangdashe.top/Article/details/gt2kbzidszy.html

f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jkquwfuq.html

[U57] PHP：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2unrdizpu.html

"值: {$a}"
来源：http://dali.daria6918.cn/Article/details/gt2yhnaxeqd.html

[U58] PHP：数组三件套
来源：http://dali.yongpay.top/Article/details/gt2mkhrinkx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yj20258.top/Article/details/gt2dfxzyryl.html

[U59] PHP：自定义排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2uijuwbah.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2scwwwmzv.html

[U60] PHP：JSON 编解码
来源：http://dali.xinyue.icu/Article/details/gt2npofcqvj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhongyouzk.top/Article/details/gt2aaarynfr.html

[U61] PHP：正则
来源：http://dali.yj20258888.top/Article/details/gt2fuzbhrwm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2kdwvotcy.html

[U62] PHP：日期对象
来源：http://dali.jianghu66.top/Article/details/gt2klfirccn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.dianchejie.cn/Article/details/gt2eznmklwu.html

[U63] PHP：文件读写
来源：http://dali.sufxvd.cn/Article/details/gt2tvfmltem.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yvedp.cn/Article/details/gt2wobijyjn.html

[U64] PHP：目录遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zfkmotue.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.c1oappe.top/Article/details/gt2tqekkjml.html

[U65] PHP：会话
来源：http://dali.cdnleiting.top/Article/details/gt2nipbvjol.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.andypj.xyz/Article/details/gt2gyrkxrca.html

[U66] PHP：设置 Cookie
来源：http://dali.aibaodan.cn/Article/details/gt2xkwklmuj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ybcxt.top/Article/details/gt2kkphzzgl.html

[U67] PHP：处理文件上传
来源：http://dali.hfpthk.cn/Article/details/gt2yxopkeqy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sysykeji.top/Article/details/gt2naievtjb.html

[U68] PHP：PDO 连接
来源：http://dali.jqgfzy.top/Article/details/gt2wokzsmbk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.kuanghao11.cn/Article/details/gt2gijexmcp.html

[U69] PHP：PDO 预处理
来源：http://dali.cqqwz.cn/Article/details/gt2mkhpjmpn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jqgfzy.top/Article/details/gt2vkzkegdm.html

[U70] PHP：PDO 事务
来源：http://dali.cashguo.top/Article/details/gt2ifebdwgy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.meibo888.top/Article/details/gt2fobfgvog.html

[U71] PHP：抛出异常
来源：http://dali.hammf.cn/Article/details/gt2yxwybaab.html

throw new RuntimeException("失败", 500);
来源：http://dali.fengsongda.top/Article/details/gt2dhmqeufq.html

[U72] PHP：写错误日志
来源：http://dali.pengpengdd.cyou/Article/details/gt2ubswwgmf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shzxlz.cn/Article/details/gt2nvtzfrpo.html

[U73] PHP：读取 ini 配置
来源：http://dali.xylfe.cn/Article/details/gt2gazlvfuf.html

parse_ini_file("config.ini", true)
来源：http://dali.yvedp.cn/Article/details/gt2dklunnad.html

[U74] PHP：读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gt2vpukubwu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sxryk.cn/Article/details/gt2fmivdnve.html


<!-- 参考信息 -->