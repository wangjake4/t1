代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.cucudq.cn/Article/details/gt2qqdloayt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aizwys.cn/Article/details/gt2wxbaiyms.html

[S48] C++：逐行读文件
来源：http://dali.yj20258.top/Article/details/gt2qdidyhjo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hxbcfvsz.html

while (std::getline(in, line)) { }
来源：http://dali.sysykeji.top/Article/details/gt2ysouwdtb.html

[S49] C++：写文件
来源：http://dali.jqgfzy.top/Article/details/gt2riayuryv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxinkj.top/Article/details/gt2lfiancay.html

[S50] C++：格式化数字
来源：http://dali.ybcxt.top/Article/details/gt2lppyqyxz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ydzc1.top/Article/details/gt2yltjpgjl.html

[S51] C++：显式类型转换
来源：http://dali.meibo888.top/Article/details/gt2arnkywau.html

static_cast<double>(a) / b
来源：http://dali.yvedp.cn/Article/details/gt2bvbluepp.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxinkj.top/Article/details/gt2sqljlkhz.html

int size() const noexcept { return n_; }
来源：http://dali.0kj1m.cn/Article/details/gt2tgpbuqnu.html

[S53] C++：移动语义
来源：http://dali.redwolf501.top/Article/details/gt2lokhjepc.html

std::vector<int> w = std::move(v);
来源：http://dali.yangfankeji.com/Article/details/gt2exydmpwt.html

[S54] C++：异常处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2oxrdplbc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenlongwang.top/Article/details/gt2mbocwudz.html

[S55] C++：结构化绑定
来源：http://dali.andypj.xyz/Article/details/gt2kcjfziwu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gt2lnpgchtj.html

[S56] C++：optional
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lwhgkiri.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.0kj1m.cn/Article/details/gt2nezddvbl.html

[S57] C++：编译期常量
来源：http://dali.redwolf501.top/Article/details/gt2xlswmusu.html

constexpr int N = 10;
来源：http://dali.tian-w.cn/Article/details/gt2znuraivt.html

[S58] C++：命名空间
来源：http://dali.jlsjyb.cn/Article/details/gt2kkijeynb.html

namespace ns { int f() { return 1; } }
来源：http://dali.haohaochexian.top/Article/details/gt2galpafya.html

[S59] C++：静态断言
来源：http://dali.iojbl.cn/Article/details/gt2ugdkcgsh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuetiantiany.cn/Article/details/gt2wwsffsod.html

[S60] C++：遍历并删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vdckoade.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2smshpdui.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2daoshugp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenlongwang.top/Article/details/gt2fgrmlzpi.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2tzwqfkej.html

[T01] Kotlin：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2kzfgqsjv.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gt2bkcsmgom.html

[T02] Kotlin：变量
来源：http://dali.aizwys.cn/Article/details/gt2xkulhyvk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangshuangyany.cn/Article/details/gt2wvwqhayi.html

[T03] Kotlin：字符串模板
来源：http://dali.haohaochexian.top/Article/details/gt2bhvcvfwd.html

"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gt2eopgzlfj.html

[T04] Kotlin：空安全
来源：http://dali.xylfe.cn/Article/details/gt2qdzudotg.html

val n: String? = null;  n?.length
来源：http://dali.0kj1m.cn/Article/details/gt2qhgvcvdj.html

[T05] Kotlin：when 表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jcscbzgf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.meibo888.top/Article/details/gt2hhykuhls.html

[T06] Kotlin：集合映射
来源：http://dali.ehwqpu.com/Article/details/gt2jmhcozxa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ehwqpu.com/Article/details/gt2ewuwndik.html

[T07] Kotlin：集合过滤
来源：http://dali.iojbl.cn/Article/details/gt2ngjjnblp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jyoumei.cn/Article/details/gt2xyafhmlp.html

[T08] Kotlin：数据类
来源：http://dali.dashuyun.cn/Article/details/gt2rhvzxqrr.html

data class User(val name: String, val age: Int)
来源：http://dali.hnqzz.top/Article/details/gt2akokyzmn.html

[T09] Kotlin：扩展函数
来源：http://dali.hfpthk.cn/Article/details/gt2clmkbzkf.html

fun String.exclaim() = this + "!"
来源：http://dali.xinyue.icu/Article/details/gt2xflekfcd.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bliqvcag.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.mhx1999.top/Article/details/gt2yxjcgbvt.html

[T11] Kotlin：协程
来源：http://dali.tian-w.cn/Article/details/gt2biwqcqkr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenzaomai.com/Article/details/gt2mrukyuxq.html

[T12] Kotlin：解构声明
来源：http://dali.cheryme.top/Article/details/gt2bzmmxzjz.html

val (a, b) = Pair(1, 2)
来源：http://dali.bjfxy.top/Article/details/gt2xvbsnnil.html

[T13] Kotlin：只读 Map
来源：http://dali.zhiwuduotai.top/Article/details/gt2lnmwkjlw.html

val m = mapOf("a" to 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2gtdotdei.html

[T14] Kotlin：循环
来源：http://dali.jiagoushi.top/Article/details/gt2ytmbbykm.html

for (i in 1..10) println(i)
来源：http://dali.yuanzhike.top/Article/details/gt2hdgqmsvw.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangtech.top/Article/details/gt2awmremdt.html

interface Shape { fun area(): Double }
来源：http://dali.c1oappe.top/Article/details/gt2lbjgqypw.html

[T16] Swift：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2kfhpcvuy.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gt2pthkqmne.html

[T17] Swift：变量与常量
来源：http://dali.tian-w.cn/Article/details/gt2isfckssu.html

var a = 1;  let b = 2
来源：http://dali.birdmap.top/Article/details/gt2glrhpgzu.html

[T18] Swift：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gt2vebttook.html

"值: \(b)"
来源：http://dali.sufxvd.cn/Article/details/gt2btyesqei.html

[T19] Swift：可选绑定
来源：http://dali.sufxvd.cn/Article/details/gt2encusbai.html

if let n = opt { print(n) }
来源：http://dali.jqgufenzy.top/Article/details/gt2ajwfgsvt.html

[T20] Swift：数组操作
来源：http://dali.gaohongyu789.top/Article/details/gt2dvelzvkr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258.top/Article/details/gt2ngkbbkzp.html

[T21] Swift：遍历
来源：http://dali.yueranfly.top/Article/details/gt2umqrtpfj.html

for x in a { print(x) }
来源：http://dali.jinqigfzy.top/Article/details/gt2zedftxmi.html

[T22] Swift：字典
来源：http://dali.jiagoushi.top/Article/details/gt2imawpttd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pycfn.com/Article/details/gt2vplkanec.html

[T23] Swift：函数
来源：http://dali.shuidangran.top/Article/details/gt2yeknggwh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenzaomai.com/Article/details/gt2tyuflxkq.html

[T24] Swift：闭包
来源：http://dali.9152youxi.cn/Article/details/gt2tvtuxlyl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qdoxqwvn.html

[T25] Swift：结构体
来源：http://dali.hnxiangtu.top/Article/details/gt2hkjwsnrw.html

struct P { var x: Int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lnmoifio.html

[T26] Swift：类与重写
来源：http://dali.xziqi.cn/Article/details/gt2egbjlqxq.html

class A: Base { override func f() {} }
来源：http://dali.sxryk.cn/Article/details/gt2fkmsfwjt.html

[T27] Swift：错误处理
来源：http://dali.kuanghao11.cn/Article/details/gt2zdvtzpjb.html

do { try f() } catch { print(error) }
来源：http://dali.jlsjyb.cn/Article/details/gt2sdvosrry.html

[T28] Swift：枚举
来源：http://dali.daxiang520.top/Article/details/gt2wzyyleyn.html

enum Color { case red, green }
来源：http://dali.jiagoushi.top/Article/details/gt2rdgoodtp.html

[T29] Swift：guard 提前返回
来源：http://dali.hfpthk.cn/Article/details/gt2zxzabphi.html

guard let x = opt else { return }
来源：http://dali.fengsongda.top/Article/details/gt2uvkrcrce.html

[T30] Swift：协议
来源：http://dali.yj20258.top/Article/details/gt2onbharjn.html

protocol Shape { func area() -> Double }
来源：http://dali.ivvv.top/Article/details/gt2ufyqywhn.html

[T31] Lua：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2hhzwgihu.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gt2wksryetp.html

[T32] Lua：局部变量
来源：http://dali.hfpthk.cn/Article/details/gt2yxpncmqx.html

local a = 1
来源：http://dali.havefunace.top/Article/details/gt2brhngfot.html

[T33] Lua：表（数组）
来源：http://dali.yueranfly.top/Article/details/gt2iihfsgfj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tianlin.xyz/Article/details/gt2aeflsqgy.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imbpayqt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2nylcmmbp.html

[T35] Lua：字典表
来源：http://dali.quarkkingdee.top/Article/details/gt2jerlqwrc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.0kj1m.cn/Article/details/gt2yzkdmsgd.html

[T36] Lua：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wqgluwtc.html

function add(a, b) return a + b end
来源：http://dali.ppjwa.cn/Article/details/gt2mzjiaexf.html

[T37] Lua：字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aidphoof.html

"a" .. "b"
来源：http://dali.smart0.xyz/Article/details/gt2qaaqghxo.html

[T38] Lua：条件
来源：http://dali.andypj.xyz/Article/details/gt2xvfuauvp.html

if x > 0 then print("正") end
来源：http://dali.zhengqikj.top/Article/details/gt2aljiysmt.html

[T39] Lua：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gt2vpjmzucn.html

string.find(s, "%d+")
来源：http://dali.0kj1m.cn/Article/details/gt2kncdykwd.html

[T40] Lua：元表
来源：http://dali.sysykeji.top/Article/details/gt2okcwmraj.html

setmetatable({}, { __index = base })
来源：http://dali.9152youxi.cn/Article/details/gt2uuwdrkpr.html

[T41] Perl：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2uwgcerbq.html

print "Hello\n";
来源：http://dali.kuanghao11.cn/Article/details/gt2imrtaihh.html

[T42] Perl：变量类型
来源：http://dali.havefunace.top/Article/details/gt2blndwdhn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sxryk.cn/Article/details/gt2oudbrnua.html

[T43] Perl：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gt2hxqsltea.html

"值: $a"
来源：http://dali.yuxming.cn/Article/details/gt2fnyszwxw.html

[T44] Perl：条件
来源：http://dali.jiagoushi.top/Article/details/gt2soorqtan.html

if ($a > 0) { print "正"; }
来源：http://dali.yvedp.cn/Article/details/gt2tzerpvfb.html

[T45] Perl：数组遍历
来源：http://dali.cashguo.top/Article/details/gt2pwqumgkj.html

for my $x (@arr) { print $x; }
来源：http://dali.tanke756.top/Article/details/gt2itcjltxo.html

[T46] Perl：哈希操作
来源：http://dali.hongshengwenyu.top/Article/details/gt2axqgzcvo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ydzc1.top/Article/details/gt2xuirozkr.html

[T47] Perl：正则捕获
来源：http://dali.hongshengwenyu.top/Article/details/gt2uylfmcqx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.9152youxi.cn/Article/details/gt2grfeslwm.html

[T48] Perl：正则替换
来源：http://dali.guowangkeji.top/Article/details/gt2dtcssfyz.html

$s =~ s/old/new/g;
来源：http://dali.jinqigufen.top/Article/details/gt2iflhineq.html

[T49] Perl：函数
来源：http://dali.wangdashe.top/Article/details/gt2zctyqxdd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gt2szrijbit.html

[T50] Perl：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gt2kiehpiov.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hnqzz.top/Article/details/gt2jqswdtme.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnqzz.top/Article/details/gt2nteslxzw.html

[T51] Scala：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2ordkouul.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gt2pnoykuvt.html

[T52] Scala：变量
来源：http://dali.birdmap.top/Article/details/gt2gzsayqbg.html

val a = 1;  var b = 2
来源：http://dali.jianghu66.top/Article/details/gt2mtrskqyh.html

[T53] Scala：字符串插值
来源：http://dali.iojbl.cn/Article/details/gt2wbyokqyj.html

s"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gt2pqmjsfzf.html

[T54] Scala：集合映射
来源：http://dali.aibaodan.cn/Article/details/gt2tuvudezk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.smart0.xyz/Article/details/gt2hnylatkn.html

[T55] Scala：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gt2gogsjged.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhixingplan.top/Article/details/gt2ymhuhnul.html

[T56] Scala：样例类
来源：http://dali.xziqi.cn/Article/details/gt2gqxawlrq.html

case class User(name: String, age: Int)
来源：http://dali.yonumen.top/Article/details/gt2dyctwdnr.html

[T57] Scala：模式匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2bysdknmc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pycfn.com/Article/details/gt2jcwifeyg.html

[T58] Scala：函数定义
来源：http://dali.daxiang520.top/Article/details/gt2wroyaskn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.haohaochexian.top/Article/details/gt2jqhjyhvl.html

[T59] Scala：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2niboriov.html

for (i <- 1 to 10) println(i)
来源：http://dali.cashguo.top/Article/details/gt2emzpgkpe.html

[T60] Scala：折叠
来源：http://dali.daria6918.cn/Article/details/gt2onkhsmvl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.vqdsnc.cn/Article/details/gt2oymevnwg.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mlnsnjhy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2loohaxvb.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ijwvzgaa.html

[U01] Py：创建虚拟环境
来源：http://dali.aizwys.cn/Article/details/gt2slaygqrp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhiwuduotai.top/Article/details/gt2zmtlgowx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenzaomai.com/Article/details/gt2gcvofjco.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhengqikj.top/Article/details/gt2mqszwxgu.html

[U03] Py：加载 .env 配置
来源：http://dali.hnqzz.top/Article/details/gt2fvepdqrb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.fzhhl.top/Article/details/gt2ronqwsso.html

[U04] Py：变量调试打印
来源：http://dali.yangfankeji.com/Article/details/gt2bxidraua.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.feifeiyinyue.top/Article/details/gt2wmzdgcby.html

[U05] Py：列表去重且保序
来源：http://dali.zhoulong.xyz/Article/details/gt2qzfcjwih.html

list(dict.fromkeys(arr))
来源：http://dali.hywenlv.cn/Article/details/gt2pensrzlk.html

[U06] Py：合并两个字典
来源：http://dali.hysaishi.cn/Article/details/gt2jyiwgbmg.html

{**a, **b}
来源：http://dali.ybcxt.top/Article/details/gt2bnhrfvft.html

[U07] Py：反转字典键值
来源：http://dali.tanke756.top/Article/details/gt2pnzrpqsu.html

{v: k for k, v in d.items()}
来源：http://dali.zhoulong.xyz/Article/details/gt2vsjcystc.html

[U08] Py：展平二维列表
来源：http://dali.jianghu66.top/Article/details/gt2vkzroqmb.html

[y for x in nested for y in x]
来源：http://dali.nanxuanxn.top/Article/details/gt2apnuejwu.html

[U09] Py：字典取最大值的键
来源：http://dali.jiagoushi.top/Article/details/gt2hdtkfetx.html

max(d, key=d.get)
来源：http://dali.daria6918.cn/Article/details/gt2pjywzhid.html

[U10] Py：按值排序字典
来源：http://dali.nwbrower.top/Article/details/gt2jdkmepbc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jianghu66.top/Article/details/gt2jsnpylbr.html

[U11] Py：生成器表达式
来源：http://dali.shzxlz.cn/Article/details/gt2vlqyzjxc.html

(x * 2 for x in arr)
来源：http://dali.haohaochexian.top/Article/details/gt2heonjrql.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.9152youxi.cn/Article/details/gt2zthlnlbs.html

Counter(arr).most_common(3)
来源：http://dali.tianlin.xyz/Article/details/gt2dqhfadzx.html

[U13] Py：固定长度队列
来源：http://dali.guowangkeji.top/Article/details/gt2jrmnpgxv.html

deque(maxlen=10)
来源：http://dali.guannengcc.top/Article/details/gt2cjemydyt.html

[U14] Py：分组收集到列表
来源：http://dali.zycfv.cn/Article/details/gt2czglsbct.html

defaultdict(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tfmcsklw.html

[U15] Py：高精度计时
来源：http://dali.yuanzhike.top/Article/details/gt2ybqlbttq.html

t = time.perf_counter()
来源：http://dali.xuetiantiany.cn/Article/details/gt2dzpjhsab.html

[U16] Py：命令行参数解析
来源：http://dali.sweek.top/Article/details/gt2htjqcgvl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinqigufen.top/Article/details/gt2vbeqqtyo.html

[U17] Py：初始化日志
来源：http://dali.hammf.cn/Article/details/gt2dpgmubkw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhongyouzk.top/Article/details/gt2taxucxpp.html

[U18] Py：预编译正则
来源：http://dali.xylfe.cn/Article/details/gt2ubzedydk.html

pat = re.compile(r"\d+")
来源：http://dali.wangdashe.top/Article/details/gt2okpbyiww.html

[U19] Py：正则替换带回调
来源：http://dali.smart0.xyz/Article/details/gt2cwqamtdq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jlsjyb.cn/Article/details/gt2oewxdotx.html

[U20] Py：缓存函数结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fiivhqno.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sufxvd.cn/Article/details/gt2zvehcgjv.html

[U21] Py：自定义上下文管理器
来源：http://dali.sufxvd.cn/Article/details/gt2nnrgpoyt.html

@contextlib.contextmanager
来源：http://dali.tianlin.xyz/Article/details/gt2uytuahpz.html

[U22] Py：矩阵转置
来源：http://dali.hnxiangtu.top/Article/details/gt2evtcbnyb.html

list(zip(*m))
来源：http://dali.jianghu66.top/Article/details/gt2djaauorw.html

[U23] Py：分块读取大文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2tqfzmbqs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xuanzx.com/Article/details/gt2wftzbehm.html

[U24] Py：路径操作
来源：http://dali.zycfv.cn/Article/details/gt2adzkpfqs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.kuanghao11.cn/Article/details/gt2oovtovgt.html

[U25] Py：CSV 按字典读
来源：http://dali.guowangkeji.top/Article/details/gt2gvazwlan.html

csv.DictReader(f)
来源：http://dali.guannengcc.top/Article/details/gt2daskpokk.html

[U26] Py：并发下载
来源：http://dali.dashuyun.cn/Article/details/gt2nsscdlge.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigfzy.top/Article/details/gt2yztapugc.html

[U27] Py：异步 HTTP
来源：http://dali.dashuyun.cn/Article/details/gt2qkjpaygr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.0kj1m.cn/Article/details/gt2cuhiuwua.html

[U28] Py：类型别名
来源：http://dali.jinqigfzy.top/Article/details/gt2wbeelzxc.html

UserId = int
来源：http://dali.zhengqikj.top/Article/details/gt2gekvlacx.html

[U29] Py：属性校验
来源：http://dali.yangfankeji.com/Article/details/gt2peidxyxv.html

@property 与 @x.setter 配合
来源：http://dali.xziqi.cn/Article/details/gt2qyttyuob.html

[U30] Py：数据类
来源：http://dali.quarkkingdee.top/Article/details/gt2kmmtcjbx.html

@dataclass(slots=True)
来源：http://dali.aibaodan.cn/Article/details/gt2gpsngtux.html

[U31] Py：单测
来源：http://dali.jqgfzy.top/Article/details/gt2frygubso.html

python -m pytest -q
来源：http://dali.jinqigufen.top/Article/details/gt2mozzapfj.html

[U32] Py：代码格式化
来源：http://dali.iojbl.cn/Article/details/gt2knunawsm.html

ruff format . && ruff check --fix .
来源：http://dali.jinqigufen.top/Article/details/gt2xknqybop.html

[U33] Py：打包发布
来源：http://dali.andypj.xyz/Article/details/gt2yhlereqs.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jlsjyb.cn/Article/details/gt2kextiknz.html

[U34] Py：判断编码
来源：http://dali.sxryk.cn/Article/details/gt2qqjmbtdb.html

chardet.detect(raw)
来源：http://dali.aibaodan.cn/Article/details/gt2mkurfviz.html

[U35] Py：发送邮件
来源：http://dali.yvedp.cn/Article/details/gt2zaegldzm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.birdmap.top/Article/details/gt2krlmiarq.html

[U36] Py：定时任务
来源：http://dali.ppjwa.cn/Article/details/gt2tknoiafr.html

schedule.every(10).minutes.do(job)
来源：http://dali.hysaishi.cn/Article/details/gt2kfogxuhu.html

[U37] Py：读写 Excel
来源：http://dali.xylfe.cn/Article/details/gt2mkdisawl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hnxiangtu.top/Article/details/gt2epvrrilg.html

[U38] Py：获取脚本所在目录
来源：http://dali.haohaochexian.top/Article/details/gt2tmbowems.html

Path(__file__).resolve().parent
来源：http://dali.hammf.cn/Article/details/gt2afpqldui.html

[U39] Py：判断是否在交互环境
来源：http://dali.chenzaomai.com/Article/details/gt2nvxnpocj.html

sys.stdout.isatty()
来源：http://dali.hnxiangtu.top/Article/details/gt2igeejihp.html

[U40] Py：打印到标准错误
来源：http://dali.redwolf501.top/Article/details/gt2vxektnvn.html

print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qbqgnuta.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.nwbrower.top/Article/details/gt2zbbqnqzt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.dashuyun.cn/Article/details/gt2sgsxpnrl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhiwuduotai.top/Article/details/gt2gmjrsqqx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cashguo.top/Article/details/gt2fjxesgys.html

[U43] PHP：声明命名空间
来源：http://dali.gotoacloud.top/Article/details/gt2evitygbt.html

namespace App\Http;
来源：http://dali.nanxuanxn.top/Article/details/gt2gdqhgnoj.html

[U44] PHP：开启严格类型
来源：http://dali.smart0.xyz/Article/details/gt2hmwzjrsa.html

declare(strict_types=1);
来源：http://dali.guowangkeji.top/Article/details/gt2ffffkhoe.html

[U45] PHP：类型声明与返回类型
来源：http://dali.redwolf501.top/Article/details/gt2blkmaqkx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2rgkhcrdu.html

[U46] PHP：可空类型
来源：http://dali.yangfankeji.com/Article/details/gt2gzkxwfxz.html

?string $name = null
来源：http://dali.hongshengwenyu.top/Article/details/gt2eewnloko.html

[U47] PHP：联合类型
来源：http://dali.tian-w.cn/Article/details/gt2jddxqemj.html

int|string $id
来源：http://dali.zhongyouzk.top/Article/details/gt2bjkqacgz.html

[U48] PHP：纯枚举
来源：http://dali.cucudq.cn/Article/details/gt2blunfyhw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xinyue.icu/Article/details/gt2ipynaenp.html

[U49] PHP：只读属性
来源：http://dali.jinqigufen.top/Article/details/gt2khlhbkvy.html

public readonly string $name
来源：http://dali.hammf.cn/Article/details/gt2fhlpqnve.html

[U50] PHP：构造器属性提升
来源：http://dali.zhiwuduotai.top/Article/details/gt2euyfuyms.html

public function __construct(private int $id) {}
来源：http://dali.yuxming.cn/Article/details/gt2ntsryovi.html

[U51] PHP：数组解构
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yhxikwcb.html

[$a, $b] = $arr;
来源：http://dali.jinqigfzy.top/Article/details/gt2svcxtvow.html

[U52] PHP：箭头函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2groxtipy.html

$double = fn($x) => $x * 2;
来源：http://dali.jyoumei.cn/Article/details/gt2wylpmvfa.html

[U53] PHP：空合并运算符
来源：http://dali.ybcxt.top/Article/details/gt2qfsffxlr.html

$v = $a ?? $b ?? "default";
来源：http://dali.guowangkeji.top/Article/details/gt2jcsswhcn.html

[U54] PHP：空安全调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rzkrshps.html

$obj?->method()
来源：http://dali.yangfankeji.com/Article/details/gt2fofdwjge.html

[U55] PHP：match 表达式
来源：http://dali.cucudq.cn/Article/details/gt2dpystaol.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.daxiang520.top/Article/details/gt2zpupkbvk.html

[U56] PHP：命名参数
来源：http://dali.jiagoushi.top/Article/details/gt2gqlulwpx.html

f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gt2ismujghd.html

[U57] PHP：字符串插值
来源：http://dali.jianghu66.top/Article/details/gt2vwlfktay.html

"值: {$a}"
来源：http://dali.yangfankeji.com/Article/details/gt2tfkiaojy.html

[U58] PHP：数组三件套
来源：http://dali.jlsjyb.cn/Article/details/gt2jcqtkkox.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.aibaodan.cn/Article/details/gt2asqlabao.html

[U59] PHP：自定义排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2haoaytez.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yueranfly.top/Article/details/gt2wseyfcik.html

[U60] PHP：JSON 编解码
来源：http://dali.jqgufenzy.top/Article/details/gt2jbmlvcsm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xuanzx.com/Article/details/gt2ganczhjb.html

[U61] PHP：正则
来源：http://dali.vqdsnc.cn/Article/details/gt2kukkjjai.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ivvv.top/Article/details/gt2ukcycdvi.html

[U62] PHP：日期对象
来源：http://dali.kuanghao11.cn/Article/details/gt2winlokwg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jiagoushi.top/Article/details/gt2kqtwvaoq.html

[U63] PHP：文件读写
来源：http://dali.zhiwuduotai.top/Article/details/gt2edpjygvn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.feifeiyinyue.top/Article/details/gt2euxikpug.html

[U64] PHP：目录遍历
来源：http://dali.nwbrower.top/Article/details/gt2glfjwjnf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yanxiufei.cn/Article/details/gt2ilermcvv.html

[U65] PHP：会话
来源：http://dali.yj20258888.top/Article/details/gt2kmuhymzj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.iojbl.cn/Article/details/gt2jmceswqm.html

[U66] PHP：设置 Cookie
来源：http://dali.zdqjudy.top/Article/details/gt2kojgrczb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinqigufen.top/Article/details/gt2uizbwchd.html

[U67] PHP：处理文件上传
来源：http://dali.fzhhl.top/Article/details/gt2oxxnfyxf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jlsjyb.cn/Article/details/gt2lqdvrult.html

[U68] PHP：PDO 连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eouacolx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.redwolf501.top/Article/details/gt2nvbdqqjp.html

[U69] PHP：PDO 预处理
来源：http://dali.yonumen.top/Article/details/gt2ppghlpcf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj202588.top/Article/details/gt2vdxuatcx.html

[U70] PHP：PDO 事务
来源：http://dali.zdqjudy.top/Article/details/gt2jbcbbzre.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tianlin.xyz/Article/details/gt2bjobozxc.html

[U71] PHP：抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gt2lhudsijs.html

throw new RuntimeException("失败", 500);
来源：http://dali.jqgufenzy.top/Article/details/gt2pmphthxl.html

[U72] PHP：写错误日志
来源：http://dali.nwbrower.top/Article/details/gt2hwuhcnhx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yueranfly.top/Article/details/gt2qkwznsqm.html


<!-- 参考信息 -->