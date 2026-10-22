代发 wailian999

[S43] C++：智能指针
来源：http://dali.sxryk.cn/Article/details/gt2zvzehgfo.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuanzhike.top/Article/details/gt2kzmphwtm.html

[S44] C++：引用传参
来源：http://dali.meibo888.top/Article/details/gt2amtcqtkb.html

void inc(int &x) { ++x; }
来源：http://dali.svipenyu.cn/Article/details/gt2lztzydcr.html

[S45] C++：lambda
来源：http://dali.gotoacloud.top/Article/details/gt2raolkyng.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aibaodan.cn/Article/details/gt2pwskcrnt.html

[S46] C++：函数模板
来源：http://dali.nanxuanxn.top/Article/details/gt2xvzkykno.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yongpay.top/Article/details/gt2qhnejogb.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2xmmwpdco.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.havefunace.top/Article/details/gt2quyaadcs.html

[S48] C++：逐行读文件
来源：http://dali.tanke756.top/Article/details/gt2epgfobjx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.mhx1999.top/Article/details/gt2ivreeogq.html

while (std::getline(in, line)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cssebgwu.html

[S49] C++：写文件
来源：http://dali.meibo888.top/Article/details/gt2jmtjzcei.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tianlin.xyz/Article/details/gt2ipnkzrag.html

[S50] C++：格式化数字
来源：http://dali.zdqjudy.top/Article/details/gt2thliczce.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gt2pbiouywo.html

[S51] C++：显式类型转换
来源：http://dali.tanke756.top/Article/details/gt2yqinlssz.html

static_cast<double>(a) / b
来源：http://dali.wangshuangyany.cn/Article/details/gt2fksrnbkn.html

[S52] C++：const 与 noexcept
来源：http://dali.guannengcc.top/Article/details/gt2zwnkcons.html

int size() const noexcept { return n_; }
来源：http://dali.hysaishi.cn/Article/details/gt2bjngetjc.html

[S53] C++：移动语义
来源：http://dali.kuanghao11.cn/Article/details/gt2mvivfabz.html

std::vector<int> w = std::move(v);
来源：http://dali.zycfv.cn/Article/details/gt2ltjijppz.html

[S54] C++：异常处理
来源：http://dali.iojbl.cn/Article/details/gt2auqonclt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xjkjnbds.html

[S55] C++：结构化绑定
来源：http://dali.sxryk.cn/Article/details/gt2sfbsztgm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqbgeey.html

[S56] C++：optional
来源：http://dali.jyoumei.cn/Article/details/gt2vukckyil.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zycfv.cn/Article/details/gt2aegiayrd.html

[S57] C++：编译期常量
来源：http://dali.wangdashe.top/Article/details/gt2tfwagajt.html

constexpr int N = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xgchtnxn.html

[S58] C++：命名空间
来源：http://dali.yuxming.cn/Article/details/gt2fzbegojk.html

namespace ns { int f() { return 1; } }
来源：http://dali.ehwqpu.com/Article/details/gt2rdsdspwv.html

[S59] C++：静态断言
来源：http://dali.gotoacloud.top/Article/details/gt2kzhykdpf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zdqjudy.top/Article/details/gt2scuxsubf.html

[S60] C++：遍历并删除元素
来源：http://dali.meibo888.top/Article/details/gt2fzsatkkc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hnxiangtu.top/Article/details/gt2kbfqzpjc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2tdjnewmu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gt2otzhenio.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2lfdpydic.html

[T01] Kotlin：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2eiwfypsn.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gt2moxbmtdb.html

[T02] Kotlin：变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kbniljoi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigfzy.top/Article/details/gt2rpixqcfc.html

[T03] Kotlin：字符串模板
来源：http://dali.zycfv.cn/Article/details/gt2wigwrffp.html

"值: $b"
来源：http://dali.shuidangran.top/Article/details/gt2ldwanmzh.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gt2psqbtqas.html

val n: String? = null;  n?.length
来源：http://dali.aibaodan.cn/Article/details/gt2hdurdhkd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxhfjmb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuanzhike.top/Article/details/gt2syxhxgee.html

[T06] Kotlin：集合映射
来源：http://dali.chenlongwang.top/Article/details/gt2takdemmv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gt2eqaaniaq.html

[T07] Kotlin：集合过滤
来源：http://dali.sweek.top/Article/details/gt2ynhuhjgs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sxryk.cn/Article/details/gt2unjkdiqm.html

[T08] Kotlin：数据类
来源：http://dali.zhoulong.xyz/Article/details/gt2qgaqqast.html

data class User(val name: String, val age: Int)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ewzzpabu.html

[T09] Kotlin：扩展函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2glajxozv.html

fun String.exclaim() = this + "!"
来源：http://dali.hongshengwenyu.top/Article/details/gt2zrgsfdgn.html

[T10] Kotlin：默认参数
来源：http://dali.wangdashe.top/Article/details/gt2rtbtodyf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pengpengdd.cyou/Article/details/gt2yrpkxzbb.html

[T11] Kotlin：协程
来源：http://dali.sysykeji.top/Article/details/gt2gqxbzoly.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.snrcjt.cn/Article/details/gt2fexduzsf.html

[T12] Kotlin：解构声明
来源：http://dali.wangshuangyany.cn/Article/details/gt2gwvetahc.html

val (a, b) = Pair(1, 2)
来源：http://dali.yongpay.top/Article/details/gt2ymjdcwlq.html

[T13] Kotlin：只读 Map
来源：http://dali.hysaishi.cn/Article/details/gt2ogygtuuo.html

val m = mapOf("a" to 1)
来源：http://dali.yongpay.top/Article/details/gt2vijuuqkn.html

[T14] Kotlin：循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2dbxdffmo.html

for (i in 1..10) println(i)
来源：http://dali.mhx1999.top/Article/details/gt2joudglrn.html

[T15] Kotlin：接口
来源：http://dali.jiagoushi.top/Article/details/gt2zexyvago.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigufen.top/Article/details/gt2jteahzsi.html

[T16] Swift：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2lziahxtz.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gt2rysnyibg.html

[T17] Swift：变量与常量
来源：http://dali.zhongyouzk.top/Article/details/gt2cjqnaonf.html

var a = 1;  let b = 2
来源：http://dali.tianlin.xyz/Article/details/gt2szxhdusg.html

[T18] Swift：字符串插值
来源：http://dali.meibo888.top/Article/details/gt2uulanxub.html

"值: \(b)"
来源：http://dali.zhiwuduotai.top/Article/details/gt2vbcrtrui.html

[T19] Swift：可选绑定
来源：http://dali.xuetiantiany.cn/Article/details/gt2igcdsapg.html

if let n = opt { print(n) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2oxswcnnv.html

[T20] Swift：数组操作
来源：http://dali.zycfv.cn/Article/details/gt2bvhhynso.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.kuanghao11.cn/Article/details/gt2qrfodhne.html

[T21] Swift：遍历
来源：http://dali.dashuyun.cn/Article/details/gt2acgpyzls.html

for x in a { print(x) }
来源：http://dali.jianghu66.top/Article/details/gt2fjqoazng.html

[T22] Swift：字典
来源：http://dali.xuanzx.com/Article/details/gt2nekwtkzg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nwbrower.top/Article/details/gt2ytvmkzdp.html

[T23] Swift：函数
来源：http://dali.jinqigfzy.top/Article/details/gt2ylbgmvxl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gaohongyu789.top/Article/details/gt2dyjtlzdq.html

[T24] Swift：闭包
来源：http://dali.ppjwa.cn/Article/details/gt2qpqgnxee.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yueranfly.top/Article/details/gt2yrpjvsno.html

[T25] Swift：结构体
来源：http://dali.yongpay.top/Article/details/gt2orqnygxd.html

struct P { var x: Int }
来源：http://dali.cucudq.cn/Article/details/gt2pqdtlubd.html

[T26] Swift：类与重写
来源：http://dali.bjfxy.top/Article/details/gt2uajphcpj.html

class A: Base { override func f() {} }
来源：http://dali.aibaodan.cn/Article/details/gt2gqvcxemk.html

[T27] Swift：错误处理
来源：http://dali.jinqigfzy.top/Article/details/gt2guwdfqqa.html

do { try f() } catch { print(error) }
来源：http://dali.316326.xyz/Article/details/gt2ywbpvfod.html

[T28] Swift：枚举
来源：http://dali.sufxvd.cn/Article/details/gt2pceovywp.html

enum Color { case red, green }
来源：http://dali.iojbl.cn/Article/details/gt2vdhlwvxl.html

[T29] Swift：guard 提前返回
来源：http://dali.ybcxt.top/Article/details/gt2evjgcqaf.html

guard let x = opt else { return }
来源：http://dali.ivvv.top/Article/details/gt2itqcjsjf.html

[T30] Swift：协议
来源：http://dali.jqgufenzy.top/Article/details/gt2frgupdhs.html

protocol Shape { func area() -> Double }
来源：http://dali.cqqwz.cn/Article/details/gt2kixexdiu.html

[T31] Lua：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2jkxiphez.html

print("Hello")
来源：http://dali.smart0.xyz/Article/details/gt2mygcotzc.html

[T32] Lua：局部变量
来源：http://dali.cdnleiting.top/Article/details/gt2kboumede.html

local a = 1
来源：http://dali.nwbrower.top/Article/details/gt2soeedsry.html

[T33] Lua：表（数组）
来源：http://dali.hammf.cn/Article/details/gt2xfedcpea.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gzhubu.top/Article/details/gt2awldnhln.html

[T34] Lua：遍历表
来源：http://dali.jinqigufen.top/Article/details/gt2hkqriqre.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ybcxt.top/Article/details/gt2snahmyuf.html

[T35] Lua：字典表
来源：http://dali.zdqjudy.top/Article/details/gt2jopezand.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cashguo.top/Article/details/gt2zgfrtzcn.html

[T36] Lua：函数
来源：http://dali.jyoumei.cn/Article/details/gt2mnvrxsab.html

function add(a, b) return a + b end
来源：http://dali.hongshengwenyu.top/Article/details/gt2wqizfigf.html

[T37] Lua：字符串拼接
来源：http://dali.smart0.xyz/Article/details/gt2dyyyjjkq.html

"a" .. "b"
来源：http://dali.gotoacloud.top/Article/details/gt2ndaqfvap.html

[T38] Lua：条件
来源：http://dali.xuanzx.com/Article/details/gt2sutssaii.html

if x > 0 then print("正") end
来源：http://dali.hfpthk.cn/Article/details/gt2lxkyevli.html

[T39] Lua：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2jpkzpkts.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvwmuqn.html

[T40] Lua：元表
来源：http://dali.nanxinkj.top/Article/details/gt2tzhjplws.html

setmetatable({}, { __index = base })
来源：http://dali.xuanzx.com/Article/details/gt2wapgawqu.html

[T41] Perl：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ytnqiila.html

print "Hello\n";
来源：http://dali.dashuyun.cn/Article/details/gt2bnpnergl.html

[T42] Perl：变量类型
来源：http://dali.pycfn.com/Article/details/gt2obcigjoe.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.0kj1m.cn/Article/details/gt2geblowac.html

[T43] Perl：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gt2yitrnbbm.html

"值: $a"
来源：http://dali.sweek.top/Article/details/gt2bizvbkqg.html

[T44] Perl：条件
来源：http://dali.9152youxi.cn/Article/details/gt2bfpagwqp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2aqalzlfn.html

[T45] Perl：数组遍历
来源：http://dali.yongpay.top/Article/details/gt2ygrzkbyn.html

for my $x (@arr) { print $x; }
来源：http://dali.guannengcc.top/Article/details/gt2hqoeswkh.html

[T46] Perl：哈希操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cilmbxum.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ehwqpu.com/Article/details/gt2aptafjfx.html

[T47] Perl：正则捕获
来源：http://dali.yj20258888.top/Article/details/gt2chiaofli.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.quarkkingdee.top/Article/details/gt2yruybtzw.html

[T48] Perl：正则替换
来源：http://dali.jinqigufen.top/Article/details/gt2ahzmqilb.html

$s =~ s/old/new/g;
来源：http://dali.quarkkingdee.top/Article/details/gt2nnhculob.html

[T49] Perl：函数
来源：http://dali.jqgfzy.top/Article/details/gt2rcmzwkii.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gt2xnnvjgko.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xntcdkce.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgfzy.top/Article/details/gt2zdffmfub.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hammf.cn/Article/details/gt2tnilffjd.html

[T51] Scala：Hello World
来源：http://dali.ydzc1.top/Article/details/gt2mcmqhohp.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gt2sfropsjk.html

[T52] Scala：变量
来源：http://dali.316326.xyz/Article/details/gt2ulqmfzbi.html

val a = 1;  var b = 2
来源：http://dali.cdnleiting.top/Article/details/gt2ixjuvfdq.html

[T53] Scala：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gt2stnquxmb.html

s"值: $b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sqrrmiey.html

[T54] Scala：集合映射
来源：http://dali.redwolf501.top/Article/details/gt2qvlpqlcf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tian-w.cn/Article/details/gt2jqqynwxt.html

[T55] Scala：集合过滤
来源：http://dali.yj20258888.top/Article/details/gt2iedwcxmr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hfpthk.cn/Article/details/gt2ixzrifgf.html

[T56] Scala：样例类
来源：http://dali.sysykeji.top/Article/details/gt2tqcpairz.html

case class User(name: String, age: Int)
来源：http://dali.jqgufenzy.top/Article/details/gt2nxdhqstf.html

[T57] Scala：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gt2euplhlno.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.iojbl.cn/Article/details/gt2ftmxwxfx.html

[T58] Scala：函数定义
来源：http://dali.zhiwuduotai.top/Article/details/gt2idjjllkn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj20258888.top/Article/details/gt2jaxnczmd.html

[T59] Scala：循环
来源：http://dali.9152youxi.cn/Article/details/gt2nyzlcagw.html

for (i <- 1 to 10) println(i)
来源：http://dali.jqgufenzy.top/Article/details/gt2svjycdcn.html

[T60] Scala：折叠
来源：http://dali.shuidangran.top/Article/details/gt2zfaoqytr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuxming.cn/Article/details/gt2wifdmwbw.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2hevbkmfa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxinkj.top/Article/details/gt2xuzondmy.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2terewvju.html

[U01] Py：创建虚拟环境
来源：http://dali.cqqwz.cn/Article/details/gt2plmsuicr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2glkoivfg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zycfv.cn/Article/details/gt2wostjqda.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenlongwang.top/Article/details/gt2itjeiugo.html

[U03] Py：加载 .env 配置
来源：http://dali.ydzc1.top/Article/details/gt2acgelwtb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gzhubu.top/Article/details/gt2avwwusrq.html

[U04] Py：变量调试打印
来源：http://dali.wangshuangyany.cn/Article/details/gt2wuvwvpxs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.kuanghao11.cn/Article/details/gt2dmnwingx.html

[U05] Py：列表去重且保序
来源：http://dali.xuetiantiany.cn/Article/details/gt2ctqufphz.html

list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2eorkzvyy.html

[U06] Py：合并两个字典
来源：http://dali.yueranfly.top/Article/details/gt2pjejxydd.html

{**a, **b}
来源：http://dali.quarkkingdee.top/Article/details/gt2jwhlpwzr.html

[U07] Py：反转字典键值
来源：http://dali.redwolf501.top/Article/details/gt2ltgvdvqv.html

{v: k for k, v in d.items()}
来源：http://dali.guannengcc.top/Article/details/gt2qdgcqefl.html

[U08] Py：展平二维列表
来源：http://dali.gaohongyu789.top/Article/details/gt2cufqweoi.html

[y for x in nested for y in x]
来源：http://dali.hysaishi.cn/Article/details/gt2sebzcumq.html

[U09] Py：字典取最大值的键
来源：http://dali.c1oappe.top/Article/details/gt2rokqhepc.html

max(d, key=d.get)
来源：http://dali.shzxlz.cn/Article/details/gt2opkbzdok.html

[U10] Py：按值排序字典
来源：http://dali.316326.xyz/Article/details/gt2izbhywij.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.aibaodan.cn/Article/details/gt2yxwogzoy.html

[U11] Py：生成器表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2otmrlnjn.html

(x * 2 for x in arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwryklpf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gzhubu.top/Article/details/gt2iuoctjrh.html

Counter(arr).most_common(3)
来源：http://dali.zycfv.cn/Article/details/gt2piqoebbv.html

[U13] Py：固定长度队列
来源：http://dali.wangdashe.top/Article/details/gt2hehibsxl.html

deque(maxlen=10)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vemrhgwa.html

[U14] Py：分组收集到列表
来源：http://dali.cheryme.top/Article/details/gt2fmxymekb.html

defaultdict(list)
来源：http://dali.0kj1m.cn/Article/details/gt2ehygxgmt.html

[U15] Py：高精度计时
来源：http://dali.yvedp.cn/Article/details/gt2nmjxbygt.html

t = time.perf_counter()
来源：http://dali.chenzaomai.com/Article/details/gt2bipzgyqv.html

[U16] Py：命令行参数解析
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sijliled.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vxbsuhak.html

[U17] Py：初始化日志
来源：http://dali.kuanghao11.cn/Article/details/gt2rjueylfi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gzhubu.top/Article/details/gt2gxgivfcn.html

[U18] Py：预编译正则
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yeqycarf.html

pat = re.compile(r"\d+")
来源：http://dali.daria6918.cn/Article/details/gt2kfpgleej.html

[U19] Py：正则替换带回调
来源：http://dali.quarkkingdee.top/Article/details/gt2gogbmyii.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zdqjudy.top/Article/details/gt2utvpuram.html

[U20] Py：缓存函数结果
来源：http://dali.birdmap.top/Article/details/gt2blwyrazu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yueranfly.top/Article/details/gt2ilnkehyj.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenzaomai.com/Article/details/gt2abcuakfb.html

@contextlib.contextmanager
来源：http://dali.shzxlz.cn/Article/details/gt2plwvolwk.html

[U22] Py：矩阵转置
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eartland.html

list(zip(*m))
来源：http://dali.zhiwuduotai.top/Article/details/gt2nkypehrs.html

[U23] Py：分块读取大文件
来源：http://dali.yonumen.top/Article/details/gt2tdimrjwt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shuidangran.top/Article/details/gt2dybhzybr.html

[U24] Py：路径操作
来源：http://dali.ybcxt.top/Article/details/gt2sqnykodv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gt2xokqzhav.html

[U25] Py：CSV 按字典读
来源：http://dali.jinqigfzy.top/Article/details/gt2iiqxpiwj.html

csv.DictReader(f)
来源：http://dali.hnxiangtu.top/Article/details/gt2rofoicxz.html

[U26] Py：并发下载
来源：http://dali.jianghu66.top/Article/details/gt2kxkxmtbw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jjhaxsnv.html

[U27] Py：异步 HTTP
来源：http://dali.nanxinkj.top/Article/details/gt2akvfeilf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hfpthk.cn/Article/details/gt2mhqmdnpx.html

[U28] Py：类型别名
来源：http://dali.daxiang520.top/Article/details/gt2yvuhivxv.html

UserId = int
来源：http://dali.zhongyouzk.top/Article/details/gt2vxzukmbq.html

[U29] Py：属性校验
来源：http://dali.gogol.net.cn/Article/details/gt2gwrjupzt.html

@property 与 @x.setter 配合
来源：http://dali.tanke756.top/Article/details/gt2vcervvyl.html

[U30] Py：数据类
来源：http://dali.sufxvd.cn/Article/details/gt2leujwbbq.html

@dataclass(slots=True)
来源：http://dali.ydzc1.top/Article/details/gt2igljgyyo.html

[U31] Py：单测
来源：http://dali.zhongyouzk.top/Article/details/gt2shtairox.html

python -m pytest -q
来源：http://dali.havefunace.top/Article/details/gt2huqqbbwu.html

[U32] Py：代码格式化
来源：http://dali.meibo888.top/Article/details/gt2iumcobxz.html

ruff format . && ruff check --fix .
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2enghkpvw.html

[U33] Py：打包发布
来源：http://dali.yj20258888.top/Article/details/gt2ytexzodl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj202588.top/Article/details/gt2dignhwtp.html

[U34] Py：判断编码
来源：http://dali.birdmap.top/Article/details/gt2oxylhqkw.html

chardet.detect(raw)
来源：http://dali.sweek.top/Article/details/gt2hknlkzst.html

[U35] Py：发送邮件
来源：http://dali.shzxlz.cn/Article/details/gt2hbzograd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj20258888.top/Article/details/gt2vcnevbyk.html

[U36] Py：定时任务
来源：http://dali.xinyue.icu/Article/details/gt2evqawbcl.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhoulong.xyz/Article/details/gt2mcbxdjfc.html

[U37] Py：读写 Excel
来源：http://dali.andypj.xyz/Article/details/gt2cxnppkgr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.haohaochexian.top/Article/details/gt2tzidombc.html

[U38] Py：获取脚本所在目录
来源：http://dali.gzhubu.top/Article/details/gt2lttyfkxj.html

Path(__file__).resolve().parent
来源：http://dali.hywenlv.cn/Article/details/gt2dnjtgsak.html

[U39] Py：判断是否在交互环境
来源：http://dali.dashuyun.cn/Article/details/gt2zhlnhhzn.html

sys.stdout.isatty()
来源：http://dali.yonumen.top/Article/details/gt2rcprkoaa.html

[U40] Py：打印到标准错误
来源：http://dali.yj20258.top/Article/details/gt2xbvovjes.html

print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gt2unneurap.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xuanzx.com/Article/details/gt2efnqrxzu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hongshengwenyu.top/Article/details/gt2ujmildwu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.svipenyu.cn/Article/details/gt2uilkdnbe.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.mhx1999.top/Article/details/gt2tnumeuhw.html

[U43] PHP：声明命名空间
来源：http://dali.smart0.xyz/Article/details/gt2rlytsxuj.html

namespace App\Http;
来源：http://dali.pengpengdd.cyou/Article/details/gt2wqsfviqs.html

[U44] PHP：开启严格类型
来源：http://dali.gaohongyu789.top/Article/details/gt2rarqetls.html

declare(strict_types=1);
来源：http://dali.cqqwz.cn/Article/details/gt2ondmfclv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jiagoushi.top/Article/details/gt2prqhalzy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmolxtwq.html

[U46] PHP：可空类型
来源：http://dali.zhengqikj.top/Article/details/gt2hbvdiwge.html

?string $name = null
来源：http://dali.ehwqpu.com/Article/details/gt2opzlgjqx.html

[U47] PHP：联合类型
来源：http://dali.nwbrower.top/Article/details/gt2talpolox.html

int|string $id
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yfcrzxri.html

[U48] PHP：纯枚举
来源：http://dali.daria6918.cn/Article/details/gt2fdhxepzi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.smart0.xyz/Article/details/gt2dqhxjmlg.html

[U49] PHP：只读属性
来源：http://dali.yvedp.cn/Article/details/gt2bbqrrfay.html

public readonly string $name
来源：http://dali.sxryk.cn/Article/details/gt2zequcxym.html

[U50] PHP：构造器属性提升
来源：http://dali.zhoulong.xyz/Article/details/gt2ttjlbiob.html

public function __construct(private int $id) {}
来源：http://dali.ppjwa.cn/Article/details/gt2roijoxoc.html

[U51] PHP：数组解构
来源：http://dali.dashuyun.cn/Article/details/gt2ukhsrbrk.html

[$a, $b] = $arr;
来源：http://dali.bjfxy.top/Article/details/gt2kqkxfpcb.html

[U52] PHP：箭头函数
来源：http://dali.gzhubu.top/Article/details/gt2fuzuheel.html

$double = fn($x) => $x * 2;
来源：http://dali.ehwqpu.com/Article/details/gt2nozbfyhc.html

[U53] PHP：空合并运算符
来源：http://dali.iojbl.cn/Article/details/gt2pvbzpjdr.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinqigufen.top/Article/details/gt2ufyprokm.html

[U54] PHP：空安全调用
来源：http://dali.jiagoushi.top/Article/details/gt2evvntquh.html

$obj?->method()
来源：http://dali.hnxiangtu.top/Article/details/gt2sssmmhvj.html

[U55] PHP：match 表达式
来源：http://dali.cheryme.top/Article/details/gt2vmaqwqhp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xziqi.cn/Article/details/gt2orirdoov.html

[U56] PHP：命名参数
来源：http://dali.yj202588.top/Article/details/gt2ersbeewd.html

f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gt2ltcuxmow.html

[U57] PHP：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gt2whyetzdg.html

"值: {$a}"
来源：http://dali.ehwqpu.com/Article/details/gt2splchrah.html

[U58] PHP：数组三件套
来源：http://dali.zycfv.cn/Article/details/gt2dgxbmokv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yangfankeji.com/Article/details/gt2bqplivor.html

[U59] PHP：自定义排序
来源：http://dali.zhoulong.xyz/Article/details/gt2tnffytyj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hammf.cn/Article/details/gt2bhwklbub.html

[U60] PHP：JSON 编解码
来源：http://dali.xinyue.icu/Article/details/gt2aolloxac.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yuxming.cn/Article/details/gt2itqecaih.html

[U61] PHP：正则
来源：http://dali.cheryme.top/Article/details/gt2rqjgmder.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wghvidal.html

[U62] PHP：日期对象
来源：http://dali.jqgfzy.top/Article/details/gt2dqltxqcx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.316326.xyz/Article/details/gt2otjantkw.html

[U63] PHP：文件读写
来源：http://dali.xylfe.cn/Article/details/gt2xhsnccum.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.0kj1m.cn/Article/details/gt2ccifodri.html

[U64] PHP：目录遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2pawbavvt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zycfv.cn/Article/details/gt2sivijlvs.html

[U65] PHP：会话
来源：http://dali.redwolf501.top/Article/details/gt2sviivsff.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hwaygdkn.html

[U66] PHP：设置 Cookie
来源：http://dali.cucudq.cn/Article/details/gt2wbprmfsa.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2psqcfddd.html

[U67] PHP：处理文件上传
来源：http://dali.nanxuanxn.top/Article/details/gt2uygtklzj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.chenjidiqi.icu/Article/details/gt2usjwlqkp.html

[U68] PHP：PDO 连接
来源：http://dali.kuanghao11.cn/Article/details/gt2bopyyvxw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ehwqpu.com/Article/details/gt2fjpbsfpi.html


<!-- 参考信息 -->