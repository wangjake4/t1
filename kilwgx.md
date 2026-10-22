代发 wailian999

[S43] C++：智能指针
来源：http://dali.birdmap.top/Article/details/gtcguojdid.html

auto p = std::make_unique<int>(5);
来源：http://dali.nwbrower.top/Article/details/gtwwvergjg.html

[S44] C++：引用传参
来源：http://dali.ydzc1.top/Article/details/gtwvfgdnhy.html

void inc(int &x) { ++x; }
来源：http://dali.zhengqikj.top/Article/details/gtugohrvgf.html

[S45] C++：lambda
来源：http://dali.xuanzx.com/Article/details/gtpuhpffmf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zycfv.cn/Article/details/gtdaqwjkgh.html

[S46] C++：函数模板
来源：http://dali.kuanghao11.cn/Article/details/gtmrgortpx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangdashe.top/Article/details/gtzanfjxsz.html

[S47] C++：结构化绑定遍历
来源：http://dali.0kj1m.cn/Article/details/gtxekbkftn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hysaishi.cn/Article/details/gteyixxoci.html

[S48] C++：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtbfsqbhkj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tianlin.xyz/Article/details/gteyfqoqrb.html

while (std::getline(in, line)) { }
来源：http://dali.ivvv.top/Article/details/gtcvchuzwx.html

[S49] C++：写文件
来源：http://dali.cashguo.top/Article/details/gtkdkyvzon.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yongpay.top/Article/details/gtwjwfhmpf.html

[S50] C++：格式化数字
来源：http://dali.chenlongwang.top/Article/details/gtbdqenqyp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtqjttywbk.html

[S51] C++：显式类型转换
来源：http://dali.gaohongyu789.top/Article/details/gtwnpmeivx.html

static_cast<double>(a) / b
来源：http://dali.havefunace.top/Article/details/gtzomyeijb.html

[S52] C++：const 与 noexcept
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfrujtzb.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gtgubbvsiw.html

[S53] C++：移动语义
来源：http://dali.yueranfly.top/Article/details/gtjfbfhwqz.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gtsxtxliti.html

[S54] C++：异常处理
来源：http://dali.xziqi.cn/Article/details/gtsedskxmt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fengsongda.top/Article/details/gtasfcojrp.html

[S55] C++：结构化绑定
来源：http://dali.316326.xyz/Article/details/gtbuhymckh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangdashe.top/Article/details/gtjyuzhigw.html

[S56] C++：optional
来源：http://dali.cashguo.top/Article/details/gtjeczfpzh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cdnleiting.top/Article/details/gtflfobmsm.html

[S57] C++：编译期常量
来源：http://dali.haohaochexian.top/Article/details/gtuuzcdqbb.html

constexpr int N = 10;
来源：http://dali.c1oappe.top/Article/details/gtmbjafqvq.html

[S58] C++：命名空间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllkphyhd.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigfzy.top/Article/details/gtzkrqfddd.html

[S59] C++：静态断言
来源：http://dali.zhongyouzk.top/Article/details/gtlkizegsz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgfzy.top/Article/details/gttqjsamrg.html

[S60] C++：遍历并删除元素
来源：http://dali.daria6918.cn/Article/details/gtcluxhbta.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gtfuzrderb.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtwoetnlkt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.svipenyu.cn/Article/details/gtwumawynq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtueszjzll.html

[T01] Kotlin：Hello World
来源：http://dali.cheryme.top/Article/details/gtnyftwhnx.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gtlwlbaxfd.html

[T02] Kotlin：变量
来源：http://dali.aizwys.cn/Article/details/gthwawnqeq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sweek.top/Article/details/gthxepdufx.html

[T03] Kotlin：字符串模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbugvfdj.html

"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gtlizlnroh.html

[T04] Kotlin：空安全
来源：http://dali.birdmap.top/Article/details/gtizrfjxyn.html

val n: String? = null;  n?.length
来源：http://dali.haohaochexian.top/Article/details/gtwifjpyxu.html

[T05] Kotlin：when 表达式
来源：http://dali.zhoulong.xyz/Article/details/gtznzyilvl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.vqdsnc.cn/Article/details/gthwdifccb.html

[T06] Kotlin：集合映射
来源：http://dali.tianlin.xyz/Article/details/gtucobnxyx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnqzz.top/Article/details/gtvoczfxss.html

[T07] Kotlin：集合过滤
来源：http://dali.yangfankeji.com/Article/details/gtbluiftan.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuxming.cn/Article/details/gtvvwwmlck.html

[T08] Kotlin：数据类
来源：http://dali.tanke756.top/Article/details/gtglekijrs.html

data class User(val name: String, val age: Int)
来源：http://dali.zhixingplan.top/Article/details/gtjwbbxutj.html

[T09] Kotlin：扩展函数
来源：http://dali.birdmap.top/Article/details/gtikmeswwk.html

fun String.exclaim() = this + "!"
来源：http://dali.tian-w.cn/Article/details/gtwtbrvqpz.html

[T10] Kotlin：默认参数
来源：http://dali.kuanghao11.cn/Article/details/gtsdmbthjn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258.top/Article/details/gtpskkculo.html

[T11] Kotlin：协程
来源：http://dali.yj20258888.top/Article/details/gtolbsdwni.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sufxvd.cn/Article/details/gtadgasuwd.html

[T12] Kotlin：解构声明
来源：http://dali.zhixingplan.top/Article/details/gtxvkmbrky.html

val (a, b) = Pair(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtmexiahhz.html

[T13] Kotlin：只读 Map
来源：http://dali.pengpengdd.cyou/Article/details/gttedqtmzz.html

val m = mapOf("a" to 1)
来源：http://dali.tanke756.top/Article/details/gtkpiwkgnr.html

[T14] Kotlin：循环
来源：http://dali.cashguo.top/Article/details/gtqkqgyysq.html

for (i in 1..10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gtohkxfzpn.html

[T15] Kotlin：接口
来源：http://dali.bjfxy.top/Article/details/gtrjinmigt.html

interface Shape { fun area(): Double }
来源：http://dali.zycfv.cn/Article/details/gtpaqufulh.html

[T16] Swift：Hello World
来源：http://dali.yj202588.top/Article/details/gtxsauygcc.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtlgpepfxo.html

[T17] Swift：变量与常量
来源：http://dali.sweek.top/Article/details/gtdyzqqnwx.html

var a = 1;  let b = 2
来源：http://dali.cqqwz.cn/Article/details/gtkhosyufv.html

[T18] Swift：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtkafjtrve.html

"值: \(b)"
来源：http://dali.sxryk.cn/Article/details/gtgpetbola.html

[T19] Swift：可选绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmncncjst.html

if let n = opt { print(n) }
来源：http://dali.316326.xyz/Article/details/gtdcqitsuv.html

[T20] Swift：数组操作
来源：http://dali.dashuyun.cn/Article/details/gtaetuynqv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinqigfzy.top/Article/details/gtqcanofhv.html

[T21] Swift：遍历
来源：http://dali.zhengqikj.top/Article/details/gtaxmaxatl.html

for x in a { print(x) }
来源：http://dali.hnxiangtu.top/Article/details/gtrfmfplei.html

[T22] Swift：字典
来源：http://dali.jinqigufen.top/Article/details/gtlfbzrxih.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenlongwang.top/Article/details/gteixuttdp.html

[T23] Swift：函数
来源：http://dali.nanxinkj.top/Article/details/gtdufsimex.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sxryk.cn/Article/details/gteqslrgiv.html

[T24] Swift：闭包
来源：http://dali.zhengqikj.top/Article/details/gtekywiedf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtorohxeyv.html

[T25] Swift：结构体
来源：http://dali.sufxvd.cn/Article/details/gtdjfokjwe.html

struct P { var x: Int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoeneivvt.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gtlexmrqph.html

class A: Base { override func f() {} }
来源：http://dali.tanke756.top/Article/details/gtfkznrvxv.html

[T27] Swift：错误处理
来源：http://dali.yj20258.top/Article/details/gtbmrywlml.html

do { try f() } catch { print(error) }
来源：http://dali.ybcxt.top/Article/details/gtamhuheew.html

[T28] Swift：枚举
来源：http://dali.hfpthk.cn/Article/details/gtqopiyarn.html

enum Color { case red, green }
来源：http://dali.ehwqpu.com/Article/details/gtmogcelsg.html

[T29] Swift：guard 提前返回
来源：http://dali.c1oappe.top/Article/details/gtqxmsdeew.html

guard let x = opt else { return }
来源：http://dali.havefunace.top/Article/details/gtmdjtppkn.html

[T30] Swift：协议
来源：http://dali.zhongyouzk.top/Article/details/gtcsycydjw.html

protocol Shape { func area() -> Double }
来源：http://dali.gaohongyu789.top/Article/details/gtzvrbibnk.html

[T31] Lua：Hello World
来源：http://dali.xuanzx.com/Article/details/gtmeutsgfj.html

print("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtrivdypdc.html

[T32] Lua：局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gtrtmkvfbx.html

local a = 1
来源：http://dali.gotoacloud.top/Article/details/gtklzhoteb.html

[T33] Lua：表（数组）
来源：http://dali.gotoacloud.top/Article/details/gthrfywwsq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258.top/Article/details/gtkfvzifrp.html

[T34] Lua：遍历表
来源：http://dali.cdnleiting.top/Article/details/gtzyximpkv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jyoumei.cn/Article/details/gtprjjgork.html

[T35] Lua：字典表
来源：http://dali.ydzc1.top/Article/details/gtiqkkguwm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtazpchlyr.html

[T36] Lua：函数
来源：http://dali.jianghu66.top/Article/details/gtihbprbxi.html

function add(a, b) return a + b end
来源：http://dali.shangyingyoupin.top/Article/details/gtfsdjlhmn.html

[T37] Lua：字符串拼接
来源：http://dali.tanke756.top/Article/details/gtuxskxjzc.html

"a" .. "b"
来源：http://dali.jianghu66.top/Article/details/gtrrwdaork.html

[T38] Lua：条件
来源：http://dali.cucudq.cn/Article/details/gthkjuouyr.html

if x > 0 then print("正") end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzeytzbt.html

[T39] Lua：模式匹配
来源：http://dali.zycfv.cn/Article/details/gttcxkuqtn.html

string.find(s, "%d+")
来源：http://dali.wangdashe.top/Article/details/gtluemiupa.html

[T40] Lua：元表
来源：http://dali.sufxvd.cn/Article/details/gtxlbimknz.html

setmetatable({}, { __index = base })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfidxctvj.html

[T41] Perl：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtmallyzku.html

print "Hello\n";
来源：http://dali.hongshengwenyu.top/Article/details/gtfendtmwz.html

[T42] Perl：变量类型
来源：http://dali.xuetiantiany.cn/Article/details/gtjjtbjfhh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sxryk.cn/Article/details/gtxcqruhzx.html

[T43] Perl：字符串插值
来源：http://dali.316326.xyz/Article/details/gtmzjkweqf.html

"值: $a"
来源：http://dali.jiagoushi.top/Article/details/gtymvngixn.html

[T44] Perl：条件
来源：http://dali.shuidangran.top/Article/details/gtjvrzpyhk.html

if ($a > 0) { print "正"; }
来源：http://dali.ybcxt.top/Article/details/gtvqrjmvvt.html

[T45] Perl：数组遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuyfsdes.html

for my $x (@arr) { print $x; }
来源：http://dali.cdnleiting.top/Article/details/gtesdjwfcj.html

[T46] Perl：哈希操作
来源：http://dali.hammf.cn/Article/details/gtlkliqblj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gogol.net.cn/Article/details/gtsygtinnd.html

[T47] Perl：正则捕获
来源：http://dali.aizwys.cn/Article/details/gtcktayqug.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtyolqvgkx.html

[T48] Perl：正则替换
来源：http://dali.gogol.net.cn/Article/details/gtrlndqjgu.html

$s =~ s/old/new/g;
来源：http://dali.chenjidiqi.icu/Article/details/gtiffgjnwe.html

[T49] Perl：函数
来源：http://dali.yangfankeji.com/Article/details/gtcbtpeysy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtqobpqffz.html

[T50] Perl：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtrsctogow.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nanxinkj.top/Article/details/gtmpmapbxz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.andypj.xyz/Article/details/gtjnlqwnpu.html

[T51] Scala：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtewjyvvoi.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gthezswrmw.html

[T52] Scala：变量
来源：http://dali.yj202588.top/Article/details/gtldymtrcl.html

val a = 1;  var b = 2
来源：http://dali.meibo888.top/Article/details/gtskluetga.html

[T53] Scala：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtksmifqhm.html

s"值: $b"
来源：http://dali.havefunace.top/Article/details/gtvbqctgtb.html

[T54] Scala：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gtcuybwdza.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xinyue.icu/Article/details/gtwfnddwqa.html

[T55] Scala：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gtjbhothzh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yongpay.top/Article/details/gtmalmrirb.html

[T56] Scala：样例类
来源：http://dali.iojbl.cn/Article/details/gtzrepwnjv.html

case class User(name: String, age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtlkysjgfk.html

[T57] Scala：模式匹配
来源：http://dali.havefunace.top/Article/details/gtrvhxxiih.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cqqwz.cn/Article/details/gtzwpdhwax.html

[T58] Scala：函数定义
来源：http://dali.nwbrower.top/Article/details/gttmabxdel.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzqytlnw.html

[T59] Scala：循环
来源：http://dali.sweek.top/Article/details/gthkonlhej.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj20258888.top/Article/details/gtuqxocpuo.html

[T60] Scala：折叠
来源：http://dali.9152youxi.cn/Article/details/gtgulzfque.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gtsjejqvxc.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtcjemzssa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hywenlv.cn/Article/details/gtozzilkfu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtighsydel.html

[U01] Py：创建虚拟环境
来源：http://dali.feifeiyinyue.top/Article/details/gtizclokvr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pengpengdd.cyou/Article/details/gtpsgicwdz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tian-w.cn/Article/details/gtqljfgjnn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtmxacyxra.html

[U03] Py：加载 .env 配置
来源：http://dali.yanxiufei.cn/Article/details/gtehtaevyc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gotoacloud.top/Article/details/gtarflgrvu.html

[U04] Py：变量调试打印
来源：http://dali.chenjidiqi.icu/Article/details/gtuxjofevn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jlsjyb.cn/Article/details/gtvwxuaexz.html

[U05] Py：列表去重且保序
来源：http://dali.shangyingyoupin.top/Article/details/gtsyvdmqfl.html

list(dict.fromkeys(arr))
来源：http://dali.shzxlz.cn/Article/details/gtsavqmgfb.html

[U06] Py：合并两个字典
来源：http://dali.andypj.xyz/Article/details/gtvntkpybf.html

{**a, **b}
来源：http://dali.hnxiangtu.top/Article/details/gtfprmftql.html

[U07] Py：反转字典键值
来源：http://dali.yongpay.top/Article/details/gtbfnmhzhj.html

{v: k for k, v in d.items()}
来源：http://dali.feifeiyinyue.top/Article/details/gtvyfpeduy.html

[U08] Py：展平二维列表
来源：http://dali.zhixingplan.top/Article/details/gtwtldpiou.html

[y for x in nested for y in x]
来源：http://dali.jqgfzy.top/Article/details/gtalkxqcie.html

[U09] Py：字典取最大值的键
来源：http://dali.nanxuanxn.top/Article/details/gtjhgjdigk.html

max(d, key=d.get)
来源：http://dali.gaohongyu789.top/Article/details/gtdgstmhad.html

[U10] Py：按值排序字典
来源：http://dali.dianchejie.cn/Article/details/gtzbvvxxxp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cdnleiting.top/Article/details/gtkpxlfzja.html

[U11] Py：生成器表达式
来源：http://dali.meibo888.top/Article/details/gtducmkwqd.html

(x * 2 for x in arr)
来源：http://dali.hfpthk.cn/Article/details/gtaxpfbcns.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.guowangkeji.top/Article/details/gtsjwrhrmu.html

Counter(arr).most_common(3)
来源：http://dali.wangdashe.top/Article/details/gtnsqxecox.html

[U13] Py：固定长度队列
来源：http://dali.yj20258.top/Article/details/gtlvwnftkz.html

deque(maxlen=10)
来源：http://dali.hywenlv.cn/Article/details/gtwicwcsfh.html

[U14] Py：分组收集到列表
来源：http://dali.zhiwuduotai.top/Article/details/gtabdykzdi.html

defaultdict(list)
来源：http://dali.daria6918.cn/Article/details/gtedciuoab.html

[U15] Py：高精度计时
来源：http://dali.yj20258888.top/Article/details/gtwyexmwwb.html

t = time.perf_counter()
来源：http://dali.shangyingyoupin.top/Article/details/gtwhnzlfbv.html

[U16] Py：命令行参数解析
来源：http://dali.shzxlz.cn/Article/details/gtxamzgkhs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuxming.cn/Article/details/gtsvrouwan.html

[U17] Py：初始化日志
来源：http://dali.jianghu66.top/Article/details/gtfbrskdxp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.birdmap.top/Article/details/gtmcncplop.html

[U18] Py：预编译正则
来源：http://dali.jqgufenzy.top/Article/details/gtzgisvbrc.html

pat = re.compile(r"\d+")
来源：http://dali.hfpthk.cn/Article/details/gtsbeegcbo.html

[U19] Py：正则替换带回调
来源：http://dali.ehwqpu.com/Article/details/gtdqsofign.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nanxinkj.top/Article/details/gtbmqjvygp.html

[U20] Py：缓存函数结果
来源：http://dali.jinqigfzy.top/Article/details/gtfpspbccw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hysaishi.cn/Article/details/gtmshmthtk.html

[U21] Py：自定义上下文管理器
来源：http://dali.mhx1999.top/Article/details/gtkiufaxxe.html

@contextlib.contextmanager
来源：http://dali.yueranfly.top/Article/details/gtmytzchvn.html

[U22] Py：矩阵转置
来源：http://dali.wangshuangyany.cn/Article/details/gtoeslizsd.html

list(zip(*m))
来源：http://dali.pycfn.com/Article/details/gteyumlfdi.html

[U23] Py：分块读取大文件
来源：http://dali.andypj.xyz/Article/details/gtawhtdhhc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.smart0.xyz/Article/details/gtykkunbpd.html

[U24] Py：路径操作
来源：http://dali.nwbrower.top/Article/details/gttlfqwnqc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gtaoepaftm.html

[U25] Py：CSV 按字典读
来源：http://dali.cdnleiting.top/Article/details/gtbjejuczl.html

csv.DictReader(f)
来源：http://dali.yanxiufei.cn/Article/details/gtkohazkye.html

[U26] Py：并发下载
来源：http://dali.svipenyu.cn/Article/details/gtdiucbhff.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.redwolf501.top/Article/details/gtgtmhhnob.html

[U27] Py：异步 HTTP
来源：http://dali.kuanghao11.cn/Article/details/gtmzgcqacc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gzhubu.top/Article/details/gtuzrdamkc.html

[U28] Py：类型别名
来源：http://dali.gotoacloud.top/Article/details/gtldgblnuf.html

UserId = int
来源：http://dali.chenjidiqi.icu/Article/details/gtblhhtlau.html

[U29] Py：属性校验
来源：http://dali.nanxuanxn.top/Article/details/gtfyxuprmo.html

@property 与 @x.setter 配合
来源：http://dali.xuetiantiany.cn/Article/details/gtziowoxzy.html

[U30] Py：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvtwtuam.html

@dataclass(slots=True)
来源：http://dali.c1oappe.top/Article/details/gtvaslomui.html

[U31] Py：单测
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppowqxsk.html

python -m pytest -q
来源：http://dali.zdqjudy.top/Article/details/gtfsexrxym.html

[U32] Py：代码格式化
来源：http://dali.nanxuanxn.top/Article/details/gtbcajhzbu.html

ruff format . && ruff check --fix .
来源：http://dali.cucudq.cn/Article/details/gtjjsrfkkw.html

[U33] Py：打包发布
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkjcljxl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sysykeji.top/Article/details/gtihfistnb.html

[U34] Py：判断编码
来源：http://dali.pengpengdd.cyou/Article/details/gtamjdtzae.html

chardet.detect(raw)
来源：http://dali.gzhubu.top/Article/details/gtbkfiqgem.html

[U35] Py：发送邮件
来源：http://dali.zhoulong.xyz/Article/details/gtriedyvwq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sysykeji.top/Article/details/gtjvseddna.html

[U36] Py：定时任务
来源：http://dali.0kj1m.cn/Article/details/gtaqanqtqu.html

schedule.every(10).minutes.do(job)
来源：http://dali.daxiang520.top/Article/details/gtoupjftwa.html

[U37] Py：读写 Excel
来源：http://dali.aizwys.cn/Article/details/gtlsykmbhb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.feifeiyinyue.top/Article/details/gtviwmvrwn.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gthbrctfej.html

Path(__file__).resolve().parent
来源：http://dali.hammf.cn/Article/details/gtpobfpzbh.html

[U39] Py：判断是否在交互环境
来源：http://dali.sufxvd.cn/Article/details/gtqvrgdzli.html

sys.stdout.isatty()
来源：http://dali.hywenlv.cn/Article/details/gtamswwwju.html

[U40] Py：打印到标准错误
来源：http://dali.chenzaomai.com/Article/details/gtjsbqgnpj.html

print("err", file=sys.stderr)
来源：http://dali.fzhhl.top/Article/details/gtlxqwwpfd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sweek.top/Article/details/gtrhteqdpz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hysaishi.cn/Article/details/gtxizmsnqj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.snrcjt.cn/Article/details/gtannxuuul.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.chenjidiqi.icu/Article/details/gtwrtccavr.html

[U43] PHP：声明命名空间
来源：http://dali.zhengqikj.top/Article/details/gtioxnyuib.html

namespace App\Http;
来源：http://dali.jlsjyb.cn/Article/details/gtpppbcbbp.html

[U44] PHP：开启严格类型
来源：http://dali.bjfxy.top/Article/details/gtjnmydcpd.html

declare(strict_types=1);
来源：http://dali.hnxiangtu.top/Article/details/gtqczcdqui.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shangyingyoupin.top/Article/details/gtqpbnexco.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtzfxinchc.html

[U46] PHP：可空类型
来源：http://dali.guannengcc.top/Article/details/gthludenpl.html

?string $name = null
来源：http://dali.cucudq.cn/Article/details/gtmokuzvtk.html

[U47] PHP：联合类型
来源：http://dali.pengpengdd.cyou/Article/details/gttixiwagq.html

int|string $id
来源：http://dali.jianghu66.top/Article/details/gteiqsjgbu.html

[U48] PHP：纯枚举
来源：http://dali.hfpthk.cn/Article/details/gtexjklmfc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtclhnprgw.html

[U49] PHP：只读属性
来源：http://dali.nanxuanxn.top/Article/details/gtwccardqq.html

public readonly string $name
来源：http://dali.aizwys.cn/Article/details/gtxrfaqpqm.html

[U50] PHP：构造器属性提升
来源：http://dali.hnqzz.top/Article/details/gtiqvxtmxr.html

public function __construct(private int $id) {}
来源：http://dali.chenzaomai.com/Article/details/gtvvppwjfq.html

[U51] PHP：数组解构
来源：http://dali.ivvv.top/Article/details/gtrylibgjd.html

[$a, $b] = $arr;
来源：http://dali.wangdashe.top/Article/details/gtubdvjuwv.html

[U52] PHP：箭头函数
来源：http://dali.gaohongyu789.top/Article/details/gtobasqihy.html

$double = fn($x) => $x * 2;
来源：http://dali.hysaishi.cn/Article/details/gtelsrirgy.html

[U53] PHP：空合并运算符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwjmdkcz.html

$v = $a ?? $b ?? "default";
来源：http://dali.wangshuangyany.cn/Article/details/gtqirfobqb.html

[U54] PHP：空安全调用
来源：http://dali.snrcjt.cn/Article/details/gtthtkhdlk.html

$obj?->method()
来源：http://dali.smart0.xyz/Article/details/gtryoptgsn.html

[U55] PHP：match 表达式
来源：http://dali.quarkkingdee.top/Article/details/gtucmiwzxk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhixingplan.top/Article/details/gtcwujvuux.html

[U56] PHP：命名参数
来源：http://dali.yj20258888.top/Article/details/gthjsuydzo.html

f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtasurvkje.html

[U57] PHP：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtjdnmfvur.html

"值: {$a}"
来源：http://dali.zdqjudy.top/Article/details/gtnsvwccpn.html

[U58] PHP：数组三件套
来源：http://dali.jqgfzy.top/Article/details/gtjtuzejlq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.0kj1m.cn/Article/details/gtliihulrc.html

[U59] PHP：自定义排序
来源：http://dali.snrcjt.cn/Article/details/gtxoghtarz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gtlwbbyfbr.html

[U60] PHP：JSON 编解码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrlbqpcg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.dashuyun.cn/Article/details/gtmroxqlpc.html

[U61] PHP：正则
来源：http://dali.hnqzz.top/Article/details/gtgmdbxfga.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtjtcqahwl.html

[U62] PHP：日期对象
来源：http://dali.gogol.net.cn/Article/details/gtjiyrbexo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.feifeiyinyue.top/Article/details/gtduxfolql.html

[U63] PHP：文件读写
来源：http://dali.pengpengdd.cyou/Article/details/gtpsctpuff.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ppjwa.cn/Article/details/gtqizojgwu.html

[U64] PHP：目录遍历
来源：http://dali.zhoulong.xyz/Article/details/gtaofeycyd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jlsjyb.cn/Article/details/gtmrqbjyob.html

[U65] PHP：会话
来源：http://dali.yuanzhike.top/Article/details/gttwpviocg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtoqyrltrs.html

[U66] PHP：设置 Cookie
来源：http://dali.hammf.cn/Article/details/gtnbibplqk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.wangdashe.top/Article/details/gtiximlqso.html

[U67] PHP：处理文件上传
来源：http://dali.yonumen.top/Article/details/gtwiemspca.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.daria6918.cn/Article/details/gtuornpkjx.html

[U68] PHP：PDO 连接
来源：http://dali.zdqjudy.top/Article/details/gtgjdsbuqs.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sxryk.cn/Article/details/gtitivagpw.html


<!-- 参考信息 -->