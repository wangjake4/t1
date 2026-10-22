代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.andypj.xyz/Article/details/gt2ciotfgzw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yvedp.cn/Article/details/gt2lwpqciis.html

[S48] C++：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2zzthtczs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuxming.cn/Article/details/gt2lilvvxdd.html

while (std::getline(in, line)) { }
来源：http://dali.sufxvd.cn/Article/details/gt2sjgbccvu.html

[S49] C++：写文件
来源：http://dali.wangdashe.top/Article/details/gt2ynizpfqq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cqqwz.cn/Article/details/gt2cwdmkwuo.html

[S50] C++：格式化数字
来源：http://dali.hfpthk.cn/Article/details/gt2wwuiekck.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sweek.top/Article/details/gt2xmuxzxbi.html

[S51] C++：显式类型转换
来源：http://dali.hywenlv.cn/Article/details/gt2sauerijd.html

static_cast<double>(a) / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oolzkdaj.html

[S52] C++：const 与 noexcept
来源：http://dali.ybcxt.top/Article/details/gt2qsmmzjug.html

int size() const noexcept { return n_; }
来源：http://dali.andypj.xyz/Article/details/gt2rbvtwtso.html

[S53] C++：移动语义
来源：http://dali.kuanghao11.cn/Article/details/gt2hgetrvol.html

std::vector<int> w = std::move(v);
来源：http://dali.yangfankeji.com/Article/details/gt2rapevhno.html

[S54] C++：异常处理
来源：http://dali.quarkkingdee.top/Article/details/gt2aqgqohzm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangdashe.top/Article/details/gt2apgweefm.html

[S55] C++：结构化绑定
来源：http://dali.zdqjudy.top/Article/details/gt2parrgmpr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xinyue.icu/Article/details/gt2lxslxppg.html

[S56] C++：optional
来源：http://dali.jianghu66.top/Article/details/gt2jknurhnn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yangfankeji.com/Article/details/gt2uojjiszc.html

[S57] C++：编译期常量
来源：http://dali.hongshengwenyu.top/Article/details/gt2judhbxfq.html

constexpr int N = 10;
来源：http://dali.hysaishi.cn/Article/details/gt2diadfcwh.html

[S58] C++：命名空间
来源：http://dali.9152youxi.cn/Article/details/gt2acuasqfz.html

namespace ns { int f() { return 1; } }
来源：http://dali.9152youxi.cn/Article/details/gt2edcftkmq.html

[S59] C++：静态断言
来源：http://dali.yueranfly.top/Article/details/gt2ftxwecby.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yongpay.top/Article/details/gt2dxcumxvt.html

[S60] C++：遍历并删除元素
来源：http://dali.aibaodan.cn/Article/details/gt2klmmklul.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gt2scwmsgua.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2luzpifgw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tzvzmglh.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2pqhwfsdp.html

[T01] Kotlin：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2zsrbpdeb.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gt2mutttmsd.html

[T02] Kotlin：变量
来源：http://dali.yongpay.top/Article/details/gt2kevjocgv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.svipenyu.cn/Article/details/gt2hqbtuzns.html

[T03] Kotlin：字符串模板
来源：http://dali.xuanzx.com/Article/details/gt2mlusjemh.html

"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jmctymls.html

[T04] Kotlin：空安全
来源：http://dali.aizwys.cn/Article/details/gt2kbiebkba.html

val n: String? = null;  n?.length
来源：http://dali.zycfv.cn/Article/details/gt2pkujmnzo.html

[T05] Kotlin：when 表达式
来源：http://dali.hysaishi.cn/Article/details/gt2npijhfvz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.smart0.xyz/Article/details/gt2eqttdmdq.html

[T06] Kotlin：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gt2ldvmcern.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dxmsgiwb.html

[T07] Kotlin：集合过滤
来源：http://dali.0kj1m.cn/Article/details/gt2aoiouris.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tianlin.xyz/Article/details/gt2dxxzcels.html

[T08] Kotlin：数据类
来源：http://dali.yuxming.cn/Article/details/gt2vgqsdhmf.html

data class User(val name: String, val age: Int)
来源：http://dali.yj202588.top/Article/details/gt2phkgtvdx.html

[T09] Kotlin：扩展函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jtyworha.html

fun String.exclaim() = this + "!"
来源：http://dali.0kj1m.cn/Article/details/gt2dzrkfrdj.html

[T10] Kotlin：默认参数
来源：http://dali.nwbrower.top/Article/details/gt2xrgjmwqg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigfzy.top/Article/details/gt2eeyejdvc.html

[T11] Kotlin：协程
来源：http://dali.dianchejie.cn/Article/details/gt2tetuostb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ybcxt.top/Article/details/gt2iamfrney.html

[T12] Kotlin：解构声明
来源：http://dali.pengpengdd.cyou/Article/details/gt2zoxojors.html

val (a, b) = Pair(1, 2)
来源：http://dali.havefunace.top/Article/details/gt2loqgrsej.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258.top/Article/details/gt2gtditidj.html

val m = mapOf("a" to 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mkzdsthf.html

[T14] Kotlin：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pyjysgjp.html

for (i in 1..10) println(i)
来源：http://dali.smart0.xyz/Article/details/gt2zbdlxzxq.html

[T15] Kotlin：接口
来源：http://dali.yangfankeji.com/Article/details/gt2oobrvyoa.html

interface Shape { fun area(): Double }
来源：http://dali.yj20258888.top/Article/details/gt2oxtojajd.html

[T16] Swift：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2uzfrzhnh.html

print("Hello")
来源：http://dali.yueranfly.top/Article/details/gt2kzjiyomu.html

[T17] Swift：变量与常量
来源：http://dali.pengpengdd.cyou/Article/details/gt2pmpasari.html

var a = 1;  let b = 2
来源：http://dali.tianlin.xyz/Article/details/gt2wdmahoph.html

[T18] Swift：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqkomgtg.html

"值: \(b)"
来源：http://dali.vqdsnc.cn/Article/details/gt2orcfpfdl.html

[T19] Swift：可选绑定
来源：http://dali.9152youxi.cn/Article/details/gt2slzqqvyn.html

if let n = opt { print(n) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pkqgstle.html

[T20] Swift：数组操作
来源：http://dali.bjfxy.top/Article/details/gt2dlbzpydh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dashuyun.cn/Article/details/gt2tifskefc.html

[T21] Swift：遍历
来源：http://dali.jyoumei.cn/Article/details/gt2dlxmyrib.html

for x in a { print(x) }
来源：http://dali.cdnleiting.top/Article/details/gt2wqywufuz.html

[T22] Swift：字典
来源：http://dali.nwbrower.top/Article/details/gt2bqlyvfoo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fengsongda.top/Article/details/gt2wvgswued.html

[T23] Swift：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cnrgdwfh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hfpthk.cn/Article/details/gt2naljqpbl.html

[T24] Swift：闭包
来源：http://dali.meibo888.top/Article/details/gt2dwqhklyj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2wzyzgmmi.html

[T25] Swift：结构体
来源：http://dali.birdmap.top/Article/details/gt2udtdhddk.html

struct P { var x: Int }
来源：http://dali.0kj1m.cn/Article/details/gt2hogjnyre.html

[T26] Swift：类与重写
来源：http://dali.feifeiyinyue.top/Article/details/gt2idstkfrx.html

class A: Base { override func f() {} }
来源：http://dali.sysykeji.top/Article/details/gt2kwauhily.html

[T27] Swift：错误处理
来源：http://dali.wangdashe.top/Article/details/gt2ehbildqt.html

do { try f() } catch { print(error) }
来源：http://dali.dashuyun.cn/Article/details/gt2wfznxovh.html

[T28] Swift：枚举
来源：http://dali.sysykeji.top/Article/details/gt2ndxozmzr.html

enum Color { case red, green }
来源：http://dali.daria6918.cn/Article/details/gt2slvhqtom.html

[T29] Swift：guard 提前返回
来源：http://dali.hnqzz.top/Article/details/gt2jilnnbiv.html

guard let x = opt else { return }
来源：http://dali.zhoulong.xyz/Article/details/gt2gqoedgfe.html

[T30] Swift：协议
来源：http://dali.svipenyu.cn/Article/details/gt2yqhrsbos.html

protocol Shape { func area() -> Double }
来源：http://dali.xinyue.icu/Article/details/gt2xzdmigei.html

[T31] Lua：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2bpmjbmre.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gt2frlrsutr.html

[T32] Lua：局部变量
来源：http://dali.shuidangran.top/Article/details/gt2xqjfyogq.html

local a = 1
来源：http://dali.gotoacloud.top/Article/details/gt2orbwbtpp.html

[T33] Lua：表（数组）
来源：http://dali.yongpay.top/Article/details/gt2pydbobgd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ppjwa.cn/Article/details/gt2atjylwva.html

[T34] Lua：遍历表
来源：http://dali.zhengqikj.top/Article/details/gt2rdjhcqsb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhengqikj.top/Article/details/gt2dashrucf.html

[T35] Lua：字典表
来源：http://dali.quarkkingdee.top/Article/details/gt2kjsgvqav.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tianlin.xyz/Article/details/gt2xvhurrwx.html

[T36] Lua：函数
来源：http://dali.jinqigfzy.top/Article/details/gt2hlkzojkv.html

function add(a, b) return a + b end
来源：http://dali.redwolf501.top/Article/details/gt2tvrenhbq.html

[T37] Lua：字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gt2ceksrvtv.html

"a" .. "b"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ifbebtgg.html

[T38] Lua：条件
来源：http://dali.yj20258888.top/Article/details/gt2ldhqkjbi.html

if x > 0 then print("正") end
来源：http://dali.snrcjt.cn/Article/details/gt2emejxenb.html

[T39] Lua：模式匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2hrhvqzps.html

string.find(s, "%d+")
来源：http://dali.zhoulong.xyz/Article/details/gt2odhrqnno.html

[T40] Lua：元表
来源：http://dali.redwolf501.top/Article/details/gt2guckytag.html

setmetatable({}, { __index = base })
来源：http://dali.havefunace.top/Article/details/gt2csitxxxo.html

[T41] Perl：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gt2tkhuxokg.html

print "Hello\n";
来源：http://dali.hnqzz.top/Article/details/gt2cvyzixao.html

[T42] Perl：变量类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jpfmpxuk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xiboycnh.html

[T43] Perl：字符串插值
来源：http://dali.tian-w.cn/Article/details/gt2gohnqybq.html

"值: $a"
来源：http://dali.zhengqikj.top/Article/details/gt2ejursxfg.html

[T44] Perl：条件
来源：http://dali.jqgufenzy.top/Article/details/gt2tkbpmoqy.html

if ($a > 0) { print "正"; }
来源：http://dali.xuanzx.com/Article/details/gt2jotvjzmq.html

[T45] Perl：数组遍历
来源：http://dali.shuidangran.top/Article/details/gt2gwpfkzyx.html

for my $x (@arr) { print $x; }
来源：http://dali.fengsongda.top/Article/details/gt2nfkpttlx.html

[T46] Perl：哈希操作
来源：http://dali.zhixingplan.top/Article/details/gt2tsgqtuak.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gogol.net.cn/Article/details/gt2ihprkmaw.html

[T47] Perl：正则捕获
来源：http://dali.xylfe.cn/Article/details/gt2uytxbmil.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2doacjnoq.html

[T48] Perl：正则替换
来源：http://dali.kuanghao11.cn/Article/details/gt2tbzndvju.html

$s =~ s/old/new/g;
来源：http://dali.zhixingplan.top/Article/details/gt2rwkynjnp.html

[T49] Perl：函数
来源：http://dali.quarkkingdee.top/Article/details/gt2nkntirrt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mzaicjki.html

[T50] Perl：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gt2rxnswyhh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.svipenyu.cn/Article/details/gt2pesxdulk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ewlzctpn.html

[T51] Scala：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2qbhukmkp.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kglqiukq.html

[T52] Scala：变量
来源：http://dali.hammf.cn/Article/details/gt2erbgzoto.html

val a = 1;  var b = 2
来源：http://dali.hnqzz.top/Article/details/gt2yjutgxme.html

[T53] Scala：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2zgbwkirh.html

s"值: $b"
来源：http://dali.gotoacloud.top/Article/details/gt2rxqchoov.html

[T54] Scala：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tkbgerzy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cdnleiting.top/Article/details/gt2qfccdfsi.html

[T55] Scala：集合过滤
来源：http://dali.c1oappe.top/Article/details/gt2nxkmdggt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2tkctisvl.html

[T56] Scala：样例类
来源：http://dali.yuanzhike.top/Article/details/gt2zoyiolic.html

case class User(name: String, age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gt2rqjljzip.html

[T57] Scala：模式匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jexgqoeo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hywenlv.cn/Article/details/gt2xxatvsdz.html

[T58] Scala：函数定义
来源：http://dali.yuanzhike.top/Article/details/gt2lrbyuhoe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shzxlz.cn/Article/details/gt2nrcpunyh.html

[T59] Scala：循环
来源：http://dali.mhx1999.top/Article/details/gt2hydtuqqu.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gt2sqchzzsp.html

[T60] Scala：折叠
来源：http://dali.yuanzhike.top/Article/details/gt2blbgimdm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ivvv.top/Article/details/gt2bggurqmf.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2uvtzzofh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gogol.net.cn/Article/details/gt2xfcudnwy.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2nqiydqbp.html

[U01] Py：创建虚拟环境
来源：http://dali.jiagoushi.top/Article/details/gt2kdzvxslr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jyoumei.cn/Article/details/gt2bnfjjsqz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.daria6918.cn/Article/details/gt2zlhpwlsy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tian-w.cn/Article/details/gt2plmfcger.html

[U03] Py：加载 .env 配置
来源：http://dali.dashuyun.cn/Article/details/gt2vvlymszf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yongpay.top/Article/details/gt2schtewjl.html

[U04] Py：变量调试打印
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wtjrihvl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xylfe.cn/Article/details/gt2maefngta.html

[U05] Py：列表去重且保序
来源：http://dali.bjfxy.top/Article/details/gt2jlucpmms.html

list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gt2oatzobgw.html

[U06] Py：合并两个字典
来源：http://dali.kuanghao11.cn/Article/details/gt2velelhgh.html

{**a, **b}
来源：http://dali.zhongyouzk.top/Article/details/gt2ztdqrlwu.html

[U07] Py：反转字典键值
来源：http://dali.haohaochexian.top/Article/details/gt2yhscysdl.html

{v: k for k, v in d.items()}
来源：http://dali.jqgufenzy.top/Article/details/gt2dujmglwh.html

[U08] Py：展平二维列表
来源：http://dali.zycfv.cn/Article/details/gt2ftrvduyn.html

[y for x in nested for y in x]
来源：http://dali.xinyue.icu/Article/details/gt2rzgdjexs.html

[U09] Py：字典取最大值的键
来源：http://dali.yvedp.cn/Article/details/gt2ujrthjzn.html

max(d, key=d.get)
来源：http://dali.hywenlv.cn/Article/details/gt2nhledeat.html

[U10] Py：按值排序字典
来源：http://dali.gogol.net.cn/Article/details/gt2dexahcfh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uecvlwuq.html

[U11] Py：生成器表达式
来源：http://dali.redwolf501.top/Article/details/gt2pjixsofc.html

(x * 2 for x in arr)
来源：http://dali.hnqzz.top/Article/details/gt2nmdrxonh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.316326.xyz/Article/details/gt2cttjrikd.html

Counter(arr).most_common(3)
来源：http://dali.jqgufenzy.top/Article/details/gt2ijddlkmg.html

[U13] Py：固定长度队列
来源：http://dali.9152youxi.cn/Article/details/gt2zmmslvmh.html

deque(maxlen=10)
来源：http://dali.sysykeji.top/Article/details/gt2jrnxilvh.html

[U14] Py：分组收集到列表
来源：http://dali.jianghu66.top/Article/details/gt2pdsjhqus.html

defaultdict(list)
来源：http://dali.fzhhl.top/Article/details/gt2pxdzybno.html

[U15] Py：高精度计时
来源：http://dali.sxryk.cn/Article/details/gt2yrimwydt.html

t = time.perf_counter()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ikvdzkza.html

[U16] Py：命令行参数解析
来源：http://dali.tian-w.cn/Article/details/gt2udqdsfks.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hnqzz.top/Article/details/gt2jytsodop.html

[U17] Py：初始化日志
来源：http://dali.jqgufenzy.top/Article/details/gt2iqgmqgtt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shuidangran.top/Article/details/gt2hjvbqqzl.html

[U18] Py：预编译正则
来源：http://dali.hfpthk.cn/Article/details/gt2fxaaoghm.html

pat = re.compile(r"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vptvcuqz.html

[U19] Py：正则替换带回调
来源：http://dali.shzxlz.cn/Article/details/gt2urgzuxso.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cashguo.top/Article/details/gt2hrsbvjxi.html

[U20] Py：缓存函数结果
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vnypcukw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.haohaochexian.top/Article/details/gt2ibyoqddx.html

[U21] Py：自定义上下文管理器
来源：http://dali.shzxlz.cn/Article/details/gt2ohpkcogo.html

@contextlib.contextmanager
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pghtvmhm.html

[U22] Py：矩阵转置
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bdvyevml.html

list(zip(*m))
来源：http://dali.jinqigfzy.top/Article/details/gt2zxrswejp.html

[U23] Py：分块读取大文件
来源：http://dali.xinyue.icu/Article/details/gt2fxxzlqzb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shanyushiyangtech.top/Article/details/gt2awnptufq.html

[U24] Py：路径操作
来源：http://dali.gotoacloud.top/Article/details/gt2vtnrhfyn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jianghu66.top/Article/details/gt2cdzhgwoj.html

[U25] Py：CSV 按字典读
来源：http://dali.ybcxt.top/Article/details/gt2unhzzhkx.html

csv.DictReader(f)
来源：http://dali.xinyue.icu/Article/details/gt2rtwmyzuy.html

[U26] Py：并发下载
来源：http://dali.tanke756.top/Article/details/gt2mnwxzvaw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pycfn.com/Article/details/gt2rhghkwzr.html

[U27] Py：异步 HTTP
来源：http://dali.ybcxt.top/Article/details/gt2hauszsoa.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ydzc1.top/Article/details/gt2qghzwlfm.html

[U28] Py：类型别名
来源：http://dali.jinqigufen.top/Article/details/gt2ubbeohwi.html

UserId = int
来源：http://dali.chenjidiqi.icu/Article/details/gt2akhneizo.html

[U29] Py：属性校验
来源：http://dali.birdmap.top/Article/details/gt2txpskdkp.html

@property 与 @x.setter 配合
来源：http://dali.cashguo.top/Article/details/gt2jmgoghpa.html

[U30] Py：数据类
来源：http://dali.wangshuangyany.cn/Article/details/gt2gipanpfw.html

@dataclass(slots=True)
来源：http://dali.jianghu66.top/Article/details/gt2qkpsdxxg.html

[U31] Py：单测
来源：http://dali.xuanzx.com/Article/details/gt2wivajbtd.html

python -m pytest -q
来源：http://dali.shuidangran.top/Article/details/gt2rctqdzsb.html

[U32] Py：代码格式化
来源：http://dali.yanxiufei.cn/Article/details/gt2stbmdfjo.html

ruff format . && ruff check --fix .
来源：http://dali.chenjidiqi.icu/Article/details/gt2bqvnrwae.html

[U33] Py：打包发布
来源：http://dali.jinqigufen.top/Article/details/gt2znckqluk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xylfe.cn/Article/details/gt2orqgxzyu.html

[U34] Py：判断编码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ehmtpjhr.html

chardet.detect(raw)
来源：http://dali.shangyingyoupin.top/Article/details/gt2eqpxatdx.html

[U35] Py：发送邮件
来源：http://dali.xziqi.cn/Article/details/gt2fmzsbnmc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sysykeji.top/Article/details/gt2rjtafcwg.html

[U36] Py：定时任务
来源：http://dali.xinyue.icu/Article/details/gt2knzdasuz.html

schedule.every(10).minutes.do(job)
来源：http://dali.hnxiangtu.top/Article/details/gt2wjzbecck.html

[U37] Py：读写 Excel
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mehqsckt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jiagoushi.top/Article/details/gt2ewinochk.html

[U38] Py：获取脚本所在目录
来源：http://dali.havefunace.top/Article/details/gt2obzyznqn.html

Path(__file__).resolve().parent
来源：http://dali.snrcjt.cn/Article/details/gt2iyhccdos.html

[U39] Py：判断是否在交互环境
来源：http://dali.pengpengdd.cyou/Article/details/gt2wqmcyxvy.html

sys.stdout.isatty()
来源：http://dali.yongpay.top/Article/details/gt2scvwkqwc.html

[U40] Py：打印到标准错误
来源：http://dali.sweek.top/Article/details/gt2cznxxcgs.html

print("err", file=sys.stderr)
来源：http://dali.dianchejie.cn/Article/details/gt2apfnmtnh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhixingplan.top/Article/details/gt2lecbjhnn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.9152youxi.cn/Article/details/gt2ogetccop.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hnqzz.top/Article/details/gt2vecbedir.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2khzxdjth.html

[U43] PHP：声明命名空间
来源：http://dali.c1oappe.top/Article/details/gt2xcexuftu.html

namespace App\Http;
来源：http://dali.meibo888.top/Article/details/gt2fxfchzws.html

[U44] PHP：开启严格类型
来源：http://dali.ehwqpu.com/Article/details/gt2jnekamxt.html

declare(strict_types=1);
来源：http://dali.ybcxt.top/Article/details/gt2kywuefbx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xinyue.icu/Article/details/gt2lmtdhjse.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2btzqyrhs.html

[U46] PHP：可空类型
来源：http://dali.guowangkeji.top/Article/details/gt2jowjhdlw.html

?string $name = null
来源：http://dali.yuanzhike.top/Article/details/gt2yeoccbnp.html

[U47] PHP：联合类型
来源：http://dali.yuanzhike.top/Article/details/gt2cwtqqslv.html

int|string $id
来源：http://dali.dashuyun.cn/Article/details/gt2rbgtwtpr.html

[U48] PHP：纯枚举
来源：http://dali.jiagoushi.top/Article/details/gt2sbstqxbn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ybcxt.top/Article/details/gt2mbhhubri.html

[U49] PHP：只读属性
来源：http://dali.guannengcc.top/Article/details/gt2ddunktpa.html

public readonly string $name
来源：http://dali.havefunace.top/Article/details/gt2zcrsulcs.html

[U50] PHP：构造器属性提升
来源：http://dali.zhongyouzk.top/Article/details/gt2tsgzmynz.html

public function __construct(private int $id) {}
来源：http://dali.birdmap.top/Article/details/gt2swpvgesd.html

[U51] PHP：数组解构
来源：http://dali.sysykeji.top/Article/details/gt2pqteoinl.html

[$a, $b] = $arr;
来源：http://dali.dianchejie.cn/Article/details/gt2qklaaatf.html

[U52] PHP：箭头函数
来源：http://dali.sxryk.cn/Article/details/gt2zzklvsfh.html

$double = fn($x) => $x * 2;
来源：http://dali.aibaodan.cn/Article/details/gt2rpqmqfne.html

[U53] PHP：空合并运算符
来源：http://dali.wangdashe.top/Article/details/gt2qfqykzys.html

$v = $a ?? $b ?? "default";
来源：http://dali.yuanzhike.top/Article/details/gt2hjxvdwov.html

[U54] PHP：空安全调用
来源：http://dali.yj20258888.top/Article/details/gt2ebjtrljb.html

$obj?->method()
来源：http://dali.hysaishi.cn/Article/details/gt2tdnzdqll.html

[U55] PHP：match 表达式
来源：http://dali.sufxvd.cn/Article/details/gt2ndjftgki.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.daria6918.cn/Article/details/gt2wkssnvzn.html

[U56] PHP：命名参数
来源：http://dali.shzxlz.cn/Article/details/gt2hzoztgef.html

f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gt2okvjhcxd.html

[U57] PHP：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gt2diceiabd.html

"值: {$a}"
来源：http://dali.guowangkeji.top/Article/details/gt2ngzmzbbw.html

[U58] PHP：数组三件套
来源：http://dali.yj20258888.top/Article/details/gt2qlhvzjry.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hysaishi.cn/Article/details/gt2hmvfaflr.html

[U59] PHP：自定义排序
来源：http://dali.ivvv.top/Article/details/gt2ugpwfisf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2dkykwxsy.html

[U60] PHP：JSON 编解码
来源：http://dali.smart0.xyz/Article/details/gt2myrhfzmi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nanxinkj.top/Article/details/gt2vcgynpna.html

[U61] PHP：正则
来源：http://dali.ehwqpu.com/Article/details/gt2qofcrftp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gt2ctalaydh.html

[U62] PHP：日期对象
来源：http://dali.wangdashe.top/Article/details/gt2fvqkiove.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cashguo.top/Article/details/gt2inbcaltq.html

[U63] PHP：文件读写
来源：http://dali.kuanghao11.cn/Article/details/gt2ldwuowah.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.feifeiyinyue.top/Article/details/gt2aznxufeq.html

[U64] PHP：目录遍历
来源：http://dali.sysykeji.top/Article/details/gt2ghbajtsu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nwbrower.top/Article/details/gt2hhtmbbxz.html

[U65] PHP：会话
来源：http://dali.meibo888.top/Article/details/gt2qnvatjez.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2piluaqep.html

[U66] PHP：设置 Cookie
来源：http://dali.yueranfly.top/Article/details/gt2jffznlye.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yongpay.top/Article/details/gt2jajxhsfs.html

[U67] PHP：处理文件上传
来源：http://dali.yj20258888.top/Article/details/gt2wgmxljdk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.haohaochexian.top/Article/details/gt2gykbhrji.html

[U68] PHP：PDO 连接
来源：http://dali.zhiwuduotai.top/Article/details/gt2pngqlqkx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2farfiawv.html

[U69] PHP：PDO 预处理
来源：http://dali.nanxuanxn.top/Article/details/gt2hcxoezoz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2haftnfng.html

[U70] PHP：PDO 事务
来源：http://dali.yangfankeji.com/Article/details/gt2gamrvrkq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.316326.xyz/Article/details/gt2zyapswhc.html

[U71] PHP：抛出异常
来源：http://dali.aizwys.cn/Article/details/gt2zivttvqf.html

throw new RuntimeException("失败", 500);
来源：http://dali.bjfxy.top/Article/details/gt2phfjmiux.html

[U72] PHP：写错误日志
来源：http://dali.pycfn.com/Article/details/gt2plgjekfg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.daria6918.cn/Article/details/gt2ajsjastp.html


<!-- 参考信息 -->