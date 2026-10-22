代发 wailian999

[S45] C++：lambda
来源：http://dali.vqdsnc.cn/Article/details/gt2czvqtgez.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xziqi.cn/Article/details/gt2xaedvkbp.html

[S46] C++：函数模板
来源：http://dali.tanke756.top/Article/details/gt2vpjfupen.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daria6918.cn/Article/details/gt2ulhcfhdh.html

[S47] C++：结构化绑定遍历
来源：http://dali.pycfn.com/Article/details/gt2ixgmoumk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dianchejie.cn/Article/details/gt2fsyscecd.html

[S48] C++：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gt2ygrpcjst.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ybcxt.top/Article/details/gt2hggcvtwi.html

while (std::getline(in, line)) { }
来源：http://dali.chenlongwang.top/Article/details/gt2ecrveald.html

[S49] C++：写文件
来源：http://dali.zhixingplan.top/Article/details/gt2geecnxqi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ehwqpu.com/Article/details/gt2irdlehaq.html

[S50] C++：格式化数字
来源：http://dali.havefunace.top/Article/details/gt2ndhgahlx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gt2ygpsnrnu.html

[S51] C++：显式类型转换
来源：http://dali.ybcxt.top/Article/details/gt2ndzgvjyt.html

static_cast<double>(a) / b
来源：http://dali.guannengcc.top/Article/details/gt2kkfvruqk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhixingplan.top/Article/details/gt2kygpiomq.html

int size() const noexcept { return n_; }
来源：http://dali.c1oappe.top/Article/details/gt2nbvnqwoj.html

[S53] C++：移动语义
来源：http://dali.daxiang520.top/Article/details/gt2ravrcjaa.html

std::vector<int> w = std::move(v);
来源：http://dali.jlsjyb.cn/Article/details/gt2bageozsd.html

[S54] C++：异常处理
来源：http://dali.havefunace.top/Article/details/gt2brbndjpc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cqqwz.cn/Article/details/gt2urmycipm.html

[S55] C++：结构化绑定
来源：http://dali.quarkkingdee.top/Article/details/gt2ltzejdvp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qpbxxcac.html

[S56] C++：optional
来源：http://dali.nanxuanxn.top/Article/details/gt2zygmjhoy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yanxiufei.cn/Article/details/gt2hhxfbkco.html

[S57] C++：编译期常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vwpkauov.html

constexpr int N = 10;
来源：http://dali.gotoacloud.top/Article/details/gt2hvevcoys.html

[S58] C++：命名空间
来源：http://dali.sysykeji.top/Article/details/gt2hcwkeffs.html

namespace ns { int f() { return 1; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dsyscokm.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gt2kxbwsxdm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wzenpbef.html

[S60] C++：遍历并删除元素
来源：http://dali.zdqjudy.top/Article/details/gt2qmmgbdqm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yongpay.top/Article/details/gt2ilzyzptz.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2bkzrlsvc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fengsongda.top/Article/details/gt2yhwgbcky.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2kyefvsdq.html

[T01] Kotlin：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2hfuwvccj.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gt2dsizupli.html

[T02] Kotlin：变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2lioaolwt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cqqwz.cn/Article/details/gt2kerlrnpy.html

[T03] Kotlin：字符串模板
来源：http://dali.cucudq.cn/Article/details/gt2sqnprlkz.html

"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gt2twqiqvfg.html

[T04] Kotlin：空安全
来源：http://dali.cqqwz.cn/Article/details/gt2zthehrac.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tvamonpf.html

[T05] Kotlin：when 表达式
来源：http://dali.hfpthk.cn/Article/details/gt2pregkzjv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zycfv.cn/Article/details/gt2roqtomry.html

[T06] Kotlin：集合映射
来源：http://dali.daxiang520.top/Article/details/gt2wljyvcpq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.0kj1m.cn/Article/details/gt2ixtvvsea.html

[T07] Kotlin：集合过滤
来源：http://dali.yuxming.cn/Article/details/gt2lkomrpvv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxuanxn.top/Article/details/gt2hbhawalc.html

[T08] Kotlin：数据类
来源：http://dali.yj20258888.top/Article/details/gt2jtmjbccw.html

data class User(val name: String, val age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gt2tslsapnu.html

[T09] Kotlin：扩展函数
来源：http://dali.ppjwa.cn/Article/details/gt2uxleofbb.html

fun String.exclaim() = this + "!"
来源：http://dali.hammf.cn/Article/details/gt2aqzcautj.html

[T10] Kotlin：默认参数
来源：http://dali.dianchejie.cn/Article/details/gt2aeoidklw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ueuuyecx.html

[T11] Kotlin：协程
来源：http://dali.xuanzx.com/Article/details/gt2hedbblne.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenlongwang.top/Article/details/gt2rxxkgycz.html

[T12] Kotlin：解构声明
来源：http://dali.0kj1m.cn/Article/details/gt2agotujuf.html

val (a, b) = Pair(1, 2)
来源：http://dali.fengsongda.top/Article/details/gt2asxcrlax.html

[T13] Kotlin：只读 Map
来源：http://dali.gzhubu.top/Article/details/gt2gnvwzfby.html

val m = mapOf("a" to 1)
来源：http://dali.yuanzhike.top/Article/details/gt2yzjvhisi.html

[T14] Kotlin：循环
来源：http://dali.bjfxy.top/Article/details/gt2keaapxwp.html

for (i in 1..10) println(i)
来源：http://dali.jianghu66.top/Article/details/gt2dpqmwaxi.html

[T15] Kotlin：接口
来源：http://dali.zhongyouzk.top/Article/details/gt2hskdtcyg.html

interface Shape { fun area(): Double }
来源：http://dali.c1oappe.top/Article/details/gt2exvzljdg.html

[T16] Swift：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2hsmhzjwo.html

print("Hello")
来源：http://dali.zhengqikj.top/Article/details/gt2ebdzvpvj.html

[T17] Swift：变量与常量
来源：http://dali.mhx1999.top/Article/details/gt2gdthdgva.html

var a = 1;  let b = 2
来源：http://dali.yongpay.top/Article/details/gt2zrjvkjhi.html

[T18] Swift：字符串插值
来源：http://dali.jianghu66.top/Article/details/gt2vqlkzvgs.html

"值: \(b)"
来源：http://dali.hnxiangtu.top/Article/details/gt2ybdhsrlr.html

[T19] Swift：可选绑定
来源：http://dali.cashguo.top/Article/details/gt2ilufzoql.html

if let n = opt { print(n) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ngawchmy.html

[T20] Swift：数组操作
来源：http://dali.yj202588.top/Article/details/gt2ttkmozqv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.smart0.xyz/Article/details/gt2zgcntkps.html

[T21] Swift：遍历
来源：http://dali.havefunace.top/Article/details/gt2hoyqlfdh.html

for x in a { print(x) }
来源：http://dali.cucudq.cn/Article/details/gt2cbynpnmf.html

[T22] Swift：字典
来源：http://dali.316326.xyz/Article/details/gt2iyocmmeh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.haohaochexian.top/Article/details/gt2slvyfwxj.html

[T23] Swift：函数
来源：http://dali.zdqjudy.top/Article/details/gt2jnsqxnhn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.smart0.xyz/Article/details/gt2oopklrjf.html

[T24] Swift：闭包
来源：http://dali.hnqzz.top/Article/details/gt2oucwlrbv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fzhhl.top/Article/details/gt2hxmcojrg.html

[T25] Swift：结构体
来源：http://dali.meibo888.top/Article/details/gt2dlkqmtoc.html

struct P { var x: Int }
来源：http://dali.wangshuangyany.cn/Article/details/gt2lbmhbtqf.html

[T26] Swift：类与重写
来源：http://dali.ppjwa.cn/Article/details/gt2ertultiz.html

class A: Base { override func f() {} }
来源：http://dali.yongpay.top/Article/details/gt2wksfknnx.html

[T27] Swift：错误处理
来源：http://dali.hfpthk.cn/Article/details/gt2gyhthmyb.html

do { try f() } catch { print(error) }
来源：http://dali.yuxming.cn/Article/details/gt2rbmjotdh.html

[T28] Swift：枚举
来源：http://dali.andypj.xyz/Article/details/gt2dymwsdvw.html

enum Color { case red, green }
来源：http://dali.daxiang520.top/Article/details/gt2jeymjttf.html

[T29] Swift：guard 提前返回
来源：http://dali.zhoulong.xyz/Article/details/gt2ccgkiqiq.html

guard let x = opt else { return }
来源：http://dali.cheryme.top/Article/details/gt2qzrodlcb.html

[T30] Swift：协议
来源：http://dali.cqqwz.cn/Article/details/gt2vrhhubvb.html

protocol Shape { func area() -> Double }
来源：http://dali.andypj.xyz/Article/details/gt2lsclbktu.html

[T31] Lua：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2tinpxcvy.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gt2lahwlhag.html

[T32] Lua：局部变量
来源：http://dali.zhongyouzk.top/Article/details/gt2glqvajks.html

local a = 1
来源：http://dali.yonumen.top/Article/details/gt2cseibalj.html

[T33] Lua：表（数组）
来源：http://dali.zycfv.cn/Article/details/gt2spidhysp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guannengcc.top/Article/details/gt2xcnpgjkm.html

[T34] Lua：遍历表
来源：http://dali.birdmap.top/Article/details/gt2prscexfz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnqzz.top/Article/details/gt2saykigcz.html

[T35] Lua：字典表
来源：http://dali.zhengqikj.top/Article/details/gt2dsumjotk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ybcxt.top/Article/details/gt2asvxhgda.html

[T36] Lua：函数
来源：http://dali.hnxiangtu.top/Article/details/gt2ieqlbyuk.html

function add(a, b) return a + b end
来源：http://dali.zdqjudy.top/Article/details/gt2mipiioag.html

[T37] Lua：字符串拼接
来源：http://dali.ivvv.top/Article/details/gt2woyrjhxo.html

"a" .. "b"
来源：http://dali.yongpay.top/Article/details/gt2ignovkeg.html

[T38] Lua：条件
来源：http://dali.cheryme.top/Article/details/gt2uqjkujty.html

if x > 0 then print("正") end
来源：http://dali.zhiwuduotai.top/Article/details/gt2fxiasxod.html

[T39] Lua：模式匹配
来源：http://dali.sxryk.cn/Article/details/gt2qlcioyge.html

string.find(s, "%d+")
来源：http://dali.jianghu66.top/Article/details/gt2mdlseelv.html

[T40] Lua：元表
来源：http://dali.dianchejie.cn/Article/details/gt2wssiwsqb.html

setmetatable({}, { __index = base })
来源：http://dali.pycfn.com/Article/details/gt2wtpbnpqr.html

[T41] Perl：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2fxaqvlzi.html

print "Hello\n";
来源：http://dali.fengsongda.top/Article/details/gt2hwbhhupc.html

[T42] Perl：变量类型
来源：http://dali.quarkkingdee.top/Article/details/gt2igxpieju.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.wangdashe.top/Article/details/gt2vokhknju.html

[T43] Perl：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zotajdha.html

"值: $a"
来源：http://dali.yuanzhike.top/Article/details/gt2amesmwok.html

[T44] Perl：条件
来源：http://dali.gogol.net.cn/Article/details/gt2qohdtilu.html

if ($a > 0) { print "正"; }
来源：http://dali.c1oappe.top/Article/details/gt2lvinhrjt.html

[T45] Perl：数组遍历
来源：http://dali.ydzc1.top/Article/details/gt2piejgiqv.html

for my $x (@arr) { print $x; }
来源：http://dali.birdmap.top/Article/details/gt2jkubsjkc.html

[T46] Perl：哈希操作
来源：http://dali.sxryk.cn/Article/details/gt2lpjruxlt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gzhubu.top/Article/details/gt2qsffwgdl.html

[T47] Perl：正则捕获
来源：http://dali.birdmap.top/Article/details/gt2aoznwedg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xziqi.cn/Article/details/gt2pwbqjvap.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yukygxmx.html

$s =~ s/old/new/g;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yotzppaw.html

[T49] Perl：函数
来源：http://dali.haohaochexian.top/Article/details/gt2xwskdwxf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cgzefjmw.html

[T50] Perl：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gt2jqlubidg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.vqdsnc.cn/Article/details/gt2iouvewnh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xizvsezc.html

[T51] Scala：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2cjzmmkdh.html

println("Hello")
来源：http://dali.yuanzhike.top/Article/details/gt2krcmyltu.html

[T52] Scala：变量
来源：http://dali.tian-w.cn/Article/details/gt2maytuwlw.html

val a = 1;  var b = 2
来源：http://dali.jinqigfzy.top/Article/details/gt2nwfpdmqs.html

[T53] Scala：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gt2ssculawl.html

s"值: $b"
来源：http://dali.yonumen.top/Article/details/gt2yqytvkud.html

[T54] Scala：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gt2klwdligw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.aizwys.cn/Article/details/gt2guyyepps.html

[T55] Scala：集合过滤
来源：http://dali.xinyue.icu/Article/details/gt2fkcuhhyk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xuanzx.com/Article/details/gt2gedfsqye.html

[T56] Scala：样例类
来源：http://dali.meibo888.top/Article/details/gt2equrjkeq.html

case class User(name: String, age: Int)
来源：http://dali.iojbl.cn/Article/details/gt2rahjoqvx.html

[T57] Scala：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gt2vhqqhzfe.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinqigufen.top/Article/details/gt2kicshplr.html

[T58] Scala：函数定义
来源：http://dali.tian-w.cn/Article/details/gt2taybiclh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nanxuanxn.top/Article/details/gt2dnzhmqyk.html

[T59] Scala：循环
来源：http://dali.dashuyun.cn/Article/details/gt2ppfqbvta.html

for (i <- 1 to 10) println(i)
来源：http://dali.smart0.xyz/Article/details/gt2albpopzo.html

[T60] Scala：折叠
来源：http://dali.jiagoushi.top/Article/details/gt2tsmhqohm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuetiantiany.cn/Article/details/gt2krosqsff.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2odgbzsoj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.mhx1999.top/Article/details/gt2mczqqsjg.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2gqpsunud.html

[U01] Py：创建虚拟环境
来源：http://dali.kuanghao11.cn/Article/details/gt2htrfwjqc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuetiantiany.cn/Article/details/gt2kbblbhrg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tanke756.top/Article/details/gt2wkdehxhs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dianchejie.cn/Article/details/gt2jthafkrk.html

[U03] Py：加载 .env 配置
来源：http://dali.nanxuanxn.top/Article/details/gt2atsbrory.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuxming.cn/Article/details/gt2lqksvywr.html

[U04] Py：变量调试打印
来源：http://dali.yuanzhike.top/Article/details/gt2jjpggyhp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hysaishi.cn/Article/details/gt2idajtdea.html

[U05] Py：列表去重且保序
来源：http://dali.zycfv.cn/Article/details/gt2vyekrceb.html

list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gt2ippjtpim.html

[U06] Py：合并两个字典
来源：http://dali.birdmap.top/Article/details/gt2gdqrxjsj.html

{**a, **b}
来源：http://dali.snrcjt.cn/Article/details/gt2ciauxnfg.html

[U07] Py：反转字典键值
来源：http://dali.wangdashe.top/Article/details/gt2mscqpjyg.html

{v: k for k, v in d.items()}
来源：http://dali.xinyue.icu/Article/details/gt2dfdlfbmx.html

[U08] Py：展平二维列表
来源：http://dali.cashguo.top/Article/details/gt2njiwcbcm.html

[y for x in nested for y in x]
来源：http://dali.daxiang520.top/Article/details/gt2qdvuxkgk.html

[U09] Py：字典取最大值的键
来源：http://dali.gaohongyu789.top/Article/details/gt2avideykg.html

max(d, key=d.get)
来源：http://dali.aizwys.cn/Article/details/gt2ezmatdfv.html

[U10] Py：按值排序字典
来源：http://dali.yongpay.top/Article/details/gt2qsylrulp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pengpengdd.cyou/Article/details/gt2xblpthvb.html

[U11] Py：生成器表达式
来源：http://dali.wangshuangyany.cn/Article/details/gt2wpjzqpyr.html

(x * 2 for x in arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2dixvegnz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.wangdashe.top/Article/details/gt2aznosjsx.html

Counter(arr).most_common(3)
来源：http://dali.mhx1999.top/Article/details/gt2kbtwtxnb.html

[U13] Py：固定长度队列
来源：http://dali.jinqigufen.top/Article/details/gt2sqtxpznd.html

deque(maxlen=10)
来源：http://dali.dianchejie.cn/Article/details/gt2inwmlbmk.html

[U14] Py：分组收集到列表
来源：http://dali.hnqzz.top/Article/details/gt2dakloalc.html

defaultdict(list)
来源：http://dali.pengpengdd.cyou/Article/details/gt2eevnctaf.html

[U15] Py：高精度计时
来源：http://dali.aizwys.cn/Article/details/gt2liaterbx.html

t = time.perf_counter()
来源：http://dali.redwolf501.top/Article/details/gt2hewqftqq.html

[U16] Py：命令行参数解析
来源：http://dali.316326.xyz/Article/details/gt2gmkamygp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nbqqoohe.html

[U17] Py：初始化日志
来源：http://dali.ppjwa.cn/Article/details/gt2birpbvmt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.mhx1999.top/Article/details/gt2grnqpvdl.html

[U18] Py：预编译正则
来源：http://dali.tian-w.cn/Article/details/gt2ilvfmwpp.html

pat = re.compile(r"\d+")
来源：http://dali.jinqigfzy.top/Article/details/gt2xegwgzng.html

[U19] Py：正则替换带回调
来源：http://dali.havefunace.top/Article/details/gt2gqzzsjgz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jlsjyb.cn/Article/details/gt2eabfrjbj.html

[U20] Py：缓存函数结果
来源：http://dali.yangfankeji.com/Article/details/gt2sqzwpjeu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.snrcjt.cn/Article/details/gt2hpjcynsx.html

[U21] Py：自定义上下文管理器
来源：http://dali.pengpengdd.cyou/Article/details/gt2uhhnwmgu.html

@contextlib.contextmanager
来源：http://dali.hnqzz.top/Article/details/gt2gqboermt.html

[U22] Py：矩阵转置
来源：http://dali.shangyingyoupin.top/Article/details/gt2mmtzniou.html

list(zip(*m))
来源：http://dali.zhengqikj.top/Article/details/gt2cfqclcse.html

[U23] Py：分块读取大文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2dsvdpypz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.iojbl.cn/Article/details/gt2umqidljc.html

[U24] Py：路径操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kxkaraxf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wdylrpht.html

[U25] Py：CSV 按字典读
来源：http://dali.aibaodan.cn/Article/details/gt2dfvsmlbw.html

csv.DictReader(f)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zjhxgrbe.html

[U26] Py：并发下载
来源：http://dali.zhengqikj.top/Article/details/gt2aszorvbj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yanxiufei.cn/Article/details/gt2hfphlacv.html

[U27] Py：异步 HTTP
来源：http://dali.hfpthk.cn/Article/details/gt2ysbtprfr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jiagoushi.top/Article/details/gt2uhcwtvps.html

[U28] Py：类型别名
来源：http://dali.jlsjyb.cn/Article/details/gt2gdxftvfq.html

UserId = int
来源：http://dali.yueranfly.top/Article/details/gt2vggsupls.html

[U29] Py：属性校验
来源：http://dali.ehwqpu.com/Article/details/gt2neyleccc.html

@property 与 @x.setter 配合
来源：http://dali.dashuyun.cn/Article/details/gt2xostsbgq.html

[U30] Py：数据类
来源：http://dali.shzxlz.cn/Article/details/gt2vlsvwuhk.html

@dataclass(slots=True)
来源：http://dali.haohaochexian.top/Article/details/gt2xvrwyuhd.html

[U31] Py：单测
来源：http://dali.haohaochexian.top/Article/details/gt2zguycwst.html

python -m pytest -q
来源：http://dali.iojbl.cn/Article/details/gt2rqkaclvr.html

[U32] Py：代码格式化
来源：http://dali.jiagoushi.top/Article/details/gt2fquyxied.html

ruff format . && ruff check --fix .
来源：http://dali.yj20258888.top/Article/details/gt2qxuvyugl.html

[U33] Py：打包发布
来源：http://dali.jinqigfzy.top/Article/details/gt2rxihfxsb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ssufdmxt.html

[U34] Py：判断编码
来源：http://dali.shuidangran.top/Article/details/gt2kypmlxvt.html

chardet.detect(raw)
来源：http://dali.yvedp.cn/Article/details/gt2qaevvigk.html

[U35] Py：发送邮件
来源：http://dali.ehwqpu.com/Article/details/gt2peisevsn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ehwqpu.com/Article/details/gt2bgdqbwlr.html

[U36] Py：定时任务
来源：http://dali.cashguo.top/Article/details/gt2fkqbhtjt.html

schedule.every(10).minutes.do(job)
来源：http://dali.gogol.net.cn/Article/details/gt2czzpnpfb.html

[U37] Py：读写 Excel
来源：http://dali.shuidangran.top/Article/details/gt2ybnppdaz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.dashuyun.cn/Article/details/gt2etuktjin.html

[U38] Py：获取脚本所在目录
来源：http://dali.feifeiyinyue.top/Article/details/gt2vvgdxfom.html

Path(__file__).resolve().parent
来源：http://dali.guowangkeji.top/Article/details/gt2taecxpxe.html

[U39] Py：判断是否在交互环境
来源：http://dali.hongshengwenyu.top/Article/details/gt2bmyxlngp.html

sys.stdout.isatty()
来源：http://dali.0kj1m.cn/Article/details/gt2naadaidz.html

[U40] Py：打印到标准错误
来源：http://dali.dashuyun.cn/Article/details/gt2fhoqkiyu.html

print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gt2fpukayzj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.aibaodan.cn/Article/details/gt2uykaketu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tanke756.top/Article/details/gt2biqfgwtw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.guowangkeji.top/Article/details/gt2zjpixhvh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.wangdashe.top/Article/details/gt2dtuoakes.html

[U43] PHP：声明命名空间
来源：http://dali.iojbl.cn/Article/details/gt2ktqzpznf.html

namespace App\Http;
来源：http://dali.pycfn.com/Article/details/gt2njgomlbd.html

[U44] PHP：开启严格类型
来源：http://dali.quarkkingdee.top/Article/details/gt2xwezmptj.html

declare(strict_types=1);
来源：http://dali.shzxlz.cn/Article/details/gt2mtpunduu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jiagoushi.top/Article/details/gt2fbivncai.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gt2wylkpxld.html

[U46] PHP：可空类型
来源：http://dali.yuxming.cn/Article/details/gt2vmcozwvf.html

?string $name = null
来源：http://dali.feifeiyinyue.top/Article/details/gt2cfqedymr.html

[U47] PHP：联合类型
来源：http://dali.yueranfly.top/Article/details/gt2krbgpqvs.html

int|string $id
来源：http://dali.pengpengdd.cyou/Article/details/gt2ibovxzbt.html

[U48] PHP：纯枚举
来源：http://dali.zhixingplan.top/Article/details/gt2htlactdd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fzyukyed.html

[U49] PHP：只读属性
来源：http://dali.jinqigufen.top/Article/details/gt2ymqfulgq.html

public readonly string $name
来源：http://dali.yj202588.top/Article/details/gt2btmwatmh.html

[U50] PHP：构造器属性提升
来源：http://dali.nanxuanxn.top/Article/details/gt2bsuvlowu.html

public function __construct(private int $id) {}
来源：http://dali.jianghu66.top/Article/details/gt2mgwglxqn.html

[U51] PHP：数组解构
来源：http://dali.yonumen.top/Article/details/gt2vypvjhfm.html

[$a, $b] = $arr;
来源：http://dali.c1oappe.top/Article/details/gt2vprtwqmt.html

[U52] PHP：箭头函数
来源：http://dali.tanke756.top/Article/details/gt2zenfzzce.html

$double = fn($x) => $x * 2;
来源：http://dali.andypj.xyz/Article/details/gt2dwhvwhlk.html

[U53] PHP：空合并运算符
来源：http://dali.9152youxi.cn/Article/details/gt2jtgmzxzb.html

$v = $a ?? $b ?? "default";
来源：http://dali.xuetiantiany.cn/Article/details/gt2zumlbixn.html

[U54] PHP：空安全调用
来源：http://dali.jinqigufen.top/Article/details/gt2qhsgbkmf.html

$obj?->method()
来源：http://dali.hammf.cn/Article/details/gt2winidepc.html

[U55] PHP：match 表达式
来源：http://dali.yueranfly.top/Article/details/gt2eypngtxl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.pycfn.com/Article/details/gt2rmoqpcdr.html

[U56] PHP：命名参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2aamievdj.html

f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pdsosfcy.html

[U57] PHP：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gt2aoavfatw.html

"值: {$a}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2rtcvqekl.html

[U58] PHP：数组三件套
来源：http://dali.redwolf501.top/Article/details/gt2zdkumlte.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hfpthk.cn/Article/details/gt2uhnzohaj.html

[U59] PHP：自定义排序
来源：http://dali.cdnleiting.top/Article/details/gt2oenbyivs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tianlin.xyz/Article/details/gt2yeydirqq.html

[U60] PHP：JSON 编解码
来源：http://dali.aibaodan.cn/Article/details/gt2hksnvdxc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gogol.net.cn/Article/details/gt2yjnfdkjo.html

[U61] PHP：正则
来源：http://dali.sufxvd.cn/Article/details/gt2gjeltfmo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sxkkulyu.html

[U62] PHP：日期对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2mssmkrbr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yanxiufei.cn/Article/details/gt2llkinreg.html

[U63] PHP：文件读写
来源：http://dali.aibaodan.cn/Article/details/gt2lcdpchpb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cashguo.top/Article/details/gt2myfnnudy.html

[U64] PHP：目录遍历
来源：http://dali.cucudq.cn/Article/details/gt2zzrcvpen.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.wangdashe.top/Article/details/gt2notpyncd.html

[U65] PHP：会话
来源：http://dali.snrcjt.cn/Article/details/gt2swsrvsze.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xuanzx.com/Article/details/gt2ahactwzs.html

[U66] PHP：设置 Cookie
来源：http://dali.iojbl.cn/Article/details/gt2lbjqprbm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cdnleiting.top/Article/details/gt2uwmftzwv.html

[U67] PHP：处理文件上传
来源：http://dali.shzxlz.cn/Article/details/gt2kdkdzwqi.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.wangshuangyany.cn/Article/details/gt2qmbracbm.html

[U68] PHP：PDO 连接
来源：http://dali.jinqigfzy.top/Article/details/gt2ipibvxzx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hfpthk.cn/Article/details/gt2pksgtxcp.html

[U69] PHP：PDO 预处理
来源：http://dali.dianchejie.cn/Article/details/gt2ifhbvlqt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2qwamguwt.html

[U70] PHP：PDO 事务
来源：http://dali.vqdsnc.cn/Article/details/gt2frtqlofg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sweek.top/Article/details/gt2vzytffga.html


<!-- 参考信息 -->