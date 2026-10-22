代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mkmxlhef.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigufen.top/Article/details/gt2ngploqkk.html

[S48] C++：逐行读文件
来源：http://dali.sweek.top/Article/details/gt2vdaspjwj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sysykeji.top/Article/details/gt2kixtgygz.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gt2chiuihlr.html

[S49] C++：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2mwuexbzw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ybcxt.top/Article/details/gt2rxxijpui.html

[S50] C++：格式化数字
来源：http://dali.ivvv.top/Article/details/gt2mqsqvouq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ybcxt.top/Article/details/gt2jovzjptc.html

[S51] C++：显式类型转换
来源：http://dali.sufxvd.cn/Article/details/gt2tdqauwyl.html

static_cast<double>(a) / b
来源：http://dali.yueranfly.top/Article/details/gt2lpvcypjr.html

[S52] C++：const 与 noexcept
来源：http://dali.dianchejie.cn/Article/details/gt2pagnbxfk.html

int size() const noexcept { return n_; }
来源：http://dali.jiagoushi.top/Article/details/gt2vjgnylma.html

[S53] C++：移动语义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yjglmhlp.html

std::vector<int> w = std::move(v);
来源：http://dali.hysaishi.cn/Article/details/gt2zucrewnq.html

[S54] C++：异常处理
来源：http://dali.daria6918.cn/Article/details/gt2duknksvt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sweek.top/Article/details/gt2utizpalk.html

[S55] C++：结构化绑定
来源：http://dali.xuanzx.com/Article/details/gt2olavvhyh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gt2qnwjvrul.html

[S56] C++：optional
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ipuudfga.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gt2azjjkigu.html

[S57] C++：编译期常量
来源：http://dali.xuetiantiany.cn/Article/details/gt2ppdrtvqu.html

constexpr int N = 10;
来源：http://dali.yj202588.top/Article/details/gt2clbpfpzl.html

[S58] C++：命名空间
来源：http://dali.xinyue.icu/Article/details/gt2vbvigtoy.html

namespace ns { int f() { return 1; } }
来源：http://dali.jyoumei.cn/Article/details/gt2syhxuokc.html

[S59] C++：静态断言
来源：http://dali.aizwys.cn/Article/details/gt2ibzatcog.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eyskubos.html

[S60] C++：遍历并删除元素
来源：http://dali.aibaodan.cn/Article/details/gt2xvhqgriz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sufxvd.cn/Article/details/gt2vsiytqon.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2qezzppzh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigufen.top/Article/details/gt2nqnzvkvt.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2cidmzlrb.html

[T01] Kotlin：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2gsuqhdzf.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hikgvekq.html

[T02] Kotlin：变量
来源：http://dali.shzxlz.cn/Article/details/gt2rbkxnvdl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj202588.top/Article/details/gt2krtxesgz.html

[T03] Kotlin：字符串模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2veoecpei.html

"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gt2tonwvxxm.html

[T04] Kotlin：空安全
来源：http://dali.nanxuanxn.top/Article/details/gt2bknpkcpz.html

val n: String? = null;  n?.length
来源：http://dali.xziqi.cn/Article/details/gt2ggljfziu.html

[T05] Kotlin：when 表达式
来源：http://dali.daria6918.cn/Article/details/gt2elvorwxc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sufxvd.cn/Article/details/gt2dopywhcy.html

[T06] Kotlin：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gt2vnveptel.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.svipenyu.cn/Article/details/gt2zgnbzltc.html

[T07] Kotlin：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gt2gdfqdexo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tian-w.cn/Article/details/gt2uwnzqvej.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gt2blfruznw.html

data class User(val name: String, val age: Int)
来源：http://dali.ehwqpu.com/Article/details/gt2fnrxsipp.html

[T09] Kotlin：扩展函数
来源：http://dali.jlsjyb.cn/Article/details/gt2szwmnpcm.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2meyaidvu.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gisbbiow.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dianchejie.cn/Article/details/gt2gdtbvzgl.html

[T11] Kotlin：协程
来源：http://dali.daria6918.cn/Article/details/gt2ccsqmfvv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xylfe.cn/Article/details/gt2jsyhuxuo.html

[T12] Kotlin：解构声明
来源：http://dali.hammf.cn/Article/details/gt2ugvqvoor.html

val (a, b) = Pair(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2vsfaihbw.html

[T13] Kotlin：只读 Map
来源：http://dali.fzhhl.top/Article/details/gt2ylvdiakr.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gt2vomoegha.html

[T14] Kotlin：循环
来源：http://dali.ppjwa.cn/Article/details/gt2ivtavokq.html

for (i in 1..10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gt2fcsduglc.html

[T15] Kotlin：接口
来源：http://dali.iojbl.cn/Article/details/gt2rvdwfjth.html

interface Shape { fun area(): Double }
来源：http://dali.xziqi.cn/Article/details/gt2pbbvhmis.html

[T16] Swift：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2otahelmf.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gt2vuezjjrh.html

[T17] Swift：变量与常量
来源：http://dali.chenjidiqi.icu/Article/details/gt2kgvaztra.html

var a = 1;  let b = 2
来源：http://dali.aizwys.cn/Article/details/gt2xipvhaau.html

[T18] Swift：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gt2kgncmhqq.html

"值: \(b)"
来源：http://dali.aizwys.cn/Article/details/gt2rwrmmohs.html

[T19] Swift：可选绑定
来源：http://dali.jqgufenzy.top/Article/details/gt2kqgvkvce.html

if let n = opt { print(n) }
来源：http://dali.daria6918.cn/Article/details/gt2oibolpkq.html

[T20] Swift：数组操作
来源：http://dali.dianchejie.cn/Article/details/gt2lydkncrp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ldxjzprz.html

[T21] Swift：遍历
来源：http://dali.guannengcc.top/Article/details/gt2gtfhopnm.html

for x in a { print(x) }
来源：http://dali.zhoulong.xyz/Article/details/gt2gblmamcg.html

[T22] Swift：字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tqlbrfnx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnxiangtu.top/Article/details/gt2hdrbeiyp.html

[T23] Swift：函数
来源：http://dali.sxryk.cn/Article/details/gt2hkqgwrsp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gaohongyu789.top/Article/details/gt2wcykwplz.html

[T24] Swift：闭包
来源：http://dali.xylfe.cn/Article/details/gt2aapcubor.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2osohjetu.html

[T25] Swift：结构体
来源：http://dali.ehwqpu.com/Article/details/gt2irwwsgrb.html

struct P { var x: Int }
来源：http://dali.c1oappe.top/Article/details/gt2rdtklzip.html

[T26] Swift：类与重写
来源：http://dali.0kj1m.cn/Article/details/gt2gwbgghyg.html

class A: Base { override func f() {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gtbbivyl.html

[T27] Swift：错误处理
来源：http://dali.ybcxt.top/Article/details/gt2qhfffdaj.html

do { try f() } catch { print(error) }
来源：http://dali.sxryk.cn/Article/details/gt2cbbbnwxs.html

[T28] Swift：枚举
来源：http://dali.aibaodan.cn/Article/details/gt2eysinjlb.html

enum Color { case red, green }
来源：http://dali.jinqigufen.top/Article/details/gt2narnwbej.html

[T29] Swift：guard 提前返回
来源：http://dali.xylfe.cn/Article/details/gt2jiscrfzp.html

guard let x = opt else { return }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xdjndoyk.html

[T30] Swift：协议
来源：http://dali.andypj.xyz/Article/details/gt2ljctjayz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhixingplan.top/Article/details/gt2twvahcho.html

[T31] Lua：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2ebzmwgms.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gt2mqrktebo.html

[T32] Lua：局部变量
来源：http://dali.zdqjudy.top/Article/details/gt2xatylgzz.html

local a = 1
来源：http://dali.gotoacloud.top/Article/details/gt2tmkgltnr.html

[T33] Lua：表（数组）
来源：http://dali.kuanghao11.cn/Article/details/gt2oqjbhmho.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.birdmap.top/Article/details/gt2srnspnjo.html

[T34] Lua：遍历表
来源：http://dali.aizwys.cn/Article/details/gt2auhnbynu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.quarkkingdee.top/Article/details/gt2vwfwlhbc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2bljnkipc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hfpthk.cn/Article/details/gt2jgtsrsnp.html

[T36] Lua：函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2dplpugmo.html

function add(a, b) return a + b end
来源：http://dali.jyoumei.cn/Article/details/gt2ulgbmubj.html

[T37] Lua：字符串拼接
来源：http://dali.pycfn.com/Article/details/gt2wqdkenwc.html

"a" .. "b"
来源：http://dali.yvedp.cn/Article/details/gt2jjrlnwjv.html

[T38] Lua：条件
来源：http://dali.andypj.xyz/Article/details/gt2cylsdolh.html

if x > 0 then print("正") end
来源：http://dali.gogol.net.cn/Article/details/gt2cjeocxzd.html

[T39] Lua：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gt2wlyetdnc.html

string.find(s, "%d+")
来源：http://dali.nanxuanxn.top/Article/details/gt2wbyuurxs.html

[T40] Lua：元表
来源：http://dali.zhongyouzk.top/Article/details/gt2tdlyeveo.html

setmetatable({}, { __index = base })
来源：http://dali.fengsongda.top/Article/details/gt2kqsclcvw.html

[T41] Perl：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2fwfpvvoz.html

print "Hello\n";
来源：http://dali.9152youxi.cn/Article/details/gt2kgnlfmtf.html

[T42] Perl：变量类型
来源：http://dali.zhoulong.xyz/Article/details/gt2eyikaigw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.haohaochexian.top/Article/details/gt2ggkglojh.html

[T43] Perl：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gt2dqhtlack.html

"值: $a"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dvvfvbyd.html

[T44] Perl：条件
来源：http://dali.cucudq.cn/Article/details/gt2fxdvesgj.html

if ($a > 0) { print "正"; }
来源：http://dali.guowangkeji.top/Article/details/gt2fddyllam.html

[T45] Perl：数组遍历
来源：http://dali.yuxming.cn/Article/details/gt2vgfqencz.html

for my $x (@arr) { print $x; }
来源：http://dali.yj202588.top/Article/details/gt2nukicxwy.html

[T46] Perl：哈希操作
来源：http://dali.xinyue.icu/Article/details/gt2wvbadqjj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gzhubu.top/Article/details/gt2oenfjzpd.html

[T47] Perl：正则捕获
来源：http://dali.yuxming.cn/Article/details/gt2bztpatio.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zdqjudy.top/Article/details/gt2zdswgbmi.html

[T48] Perl：正则替换
来源：http://dali.zhengqikj.top/Article/details/gt2rodyyeqs.html

$s =~ s/old/new/g;
来源：http://dali.ybcxt.top/Article/details/gt2gbjikvrr.html

[T49] Perl：函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2ycpqlnnu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gt2oysxyjdz.html

[T50] Perl：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gt2xbpdfhsh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.iojbl.cn/Article/details/gt2lconlqmj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sweek.top/Article/details/gt2xfulgohb.html

[T51] Scala：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2jxjuqabl.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gt2qsqrmeqd.html

[T52] Scala：变量
来源：http://dali.redwolf501.top/Article/details/gt2tzbyinme.html

val a = 1;  var b = 2
来源：http://dali.aizwys.cn/Article/details/gt2nouaynmy.html

[T53] Scala：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gt2cicurpmk.html

s"值: $b"
来源：http://dali.cashguo.top/Article/details/gt2pdgtucyt.html

[T54] Scala：集合映射
来源：http://dali.daria6918.cn/Article/details/gt2npyctkmu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.smart0.xyz/Article/details/gt2tqfasbxf.html

[T55] Scala：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sottmtvu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.smart0.xyz/Article/details/gt2owyomxmx.html

[T56] Scala：样例类
来源：http://dali.jqgfzy.top/Article/details/gt2hgwgluza.html

case class User(name: String, age: Int)
来源：http://dali.tanke756.top/Article/details/gt2ldfarqup.html

[T57] Scala：模式匹配
来源：http://dali.tianlin.xyz/Article/details/gt2fchbqqls.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhengqikj.top/Article/details/gt2gnhsxbwg.html

[T58] Scala：函数定义
来源：http://dali.ehwqpu.com/Article/details/gt2uqiyqfkh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zycfv.cn/Article/details/gt2iahunerl.html

[T59] Scala：循环
来源：http://dali.jqgufenzy.top/Article/details/gt2rlddvuaj.html

for (i <- 1 to 10) println(i)
来源：http://dali.yonumen.top/Article/details/gt2nrtsrdxz.html

[T60] Scala：折叠
来源：http://dali.svipenyu.cn/Article/details/gt2rfjisqmz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhoulong.xyz/Article/details/gt2nvqvcxbx.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2jocjysbh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sxryk.cn/Article/details/gt2gtrimosq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2tjhrgals.html

[U01] Py：创建虚拟环境
来源：http://dali.meibo888.top/Article/details/gt2udktofqg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shuidangran.top/Article/details/gt2rqrhzgci.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cdnleiting.top/Article/details/gt2slkqnsvc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daria6918.cn/Article/details/gt2gpgdfkte.html

[U03] Py：加载 .env 配置
来源：http://dali.yj20258888.top/Article/details/gt2wzgrfurg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gotoacloud.top/Article/details/gt2wsinudkq.html

[U04] Py：变量调试打印
来源：http://dali.redwolf501.top/Article/details/gt2xyaojakq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xinyue.icu/Article/details/gt2yqhvilld.html

[U05] Py：列表去重且保序
来源：http://dali.0kj1m.cn/Article/details/gt2sogxukjc.html

list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2ctlahgod.html

[U06] Py：合并两个字典
来源：http://dali.cheryme.top/Article/details/gt2epoczkor.html

{**a, **b}
来源：http://dali.yj20258888.top/Article/details/gt2tpgckdjf.html

[U07] Py：反转字典键值
来源：http://dali.zhoulong.xyz/Article/details/gt2pxbueqkv.html

{v: k for k, v in d.items()}
来源：http://dali.chenjidiqi.icu/Article/details/gt2hlzjszeq.html

[U08] Py：展平二维列表
来源：http://dali.0kj1m.cn/Article/details/gt2qtnliqbr.html

[y for x in nested for y in x]
来源：http://dali.yj20258.top/Article/details/gt2huxxsrpt.html

[U09] Py：字典取最大值的键
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mugcdhbi.html

max(d, key=d.get)
来源：http://dali.jinqigfzy.top/Article/details/gt2elvsbqnl.html

[U10] Py：按值排序字典
来源：http://dali.pengpengdd.cyou/Article/details/gt2vqvpmhlx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj20258.top/Article/details/gt2ejpnuhpf.html

[U11] Py：生成器表达式
来源：http://dali.fzhhl.top/Article/details/gt2tcxevrwe.html

(x * 2 for x in arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2npyjlhqf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iqdcvtbq.html

Counter(arr).most_common(3)
来源：http://dali.yj202588.top/Article/details/gt2lzqqmkmx.html

[U13] Py：固定长度队列
来源：http://dali.chenlongwang.top/Article/details/gt2uiboshaj.html

deque(maxlen=10)
来源：http://dali.daxiang520.top/Article/details/gt2zfrfgzpb.html

[U14] Py：分组收集到列表
来源：http://dali.aizwys.cn/Article/details/gt2fzfisyyh.html

defaultdict(list)
来源：http://dali.yueranfly.top/Article/details/gt2exwiqryh.html

[U15] Py：高精度计时
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2erhjmncl.html

t = time.perf_counter()
来源：http://dali.ybcxt.top/Article/details/gt2olqrtavm.html

[U16] Py：命令行参数解析
来源：http://dali.chenjidiqi.icu/Article/details/gt2swzraizb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.tian-w.cn/Article/details/gt2rpsieeqb.html

[U17] Py：初始化日志
来源：http://dali.meibo888.top/Article/details/gt2uwccfrdd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziupmlsh.html

[U18] Py：预编译正则
来源：http://dali.yj202588.top/Article/details/gt2gfkhcjbj.html

pat = re.compile(r"\d+")
来源：http://dali.yj20258888.top/Article/details/gt2otfbqqbp.html

[U19] Py：正则替换带回调
来源：http://dali.zhiwuduotai.top/Article/details/gt2kinosald.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pmbdafqc.html

[U20] Py：缓存函数结果
来源：http://dali.zhixingplan.top/Article/details/gt2vuobumid.html

@functools.lru_cache(maxsize=None)
来源：http://dali.kuanghao11.cn/Article/details/gt2eutbycuo.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xceqycjd.html

@contextlib.contextmanager
来源：http://dali.birdmap.top/Article/details/gt2vjmvoxfm.html

[U22] Py：矩阵转置
来源：http://dali.ydzc1.top/Article/details/gt2fzmmctsd.html

list(zip(*m))
来源：http://dali.zycfv.cn/Article/details/gt2qchqpgjj.html

[U23] Py：分块读取大文件
来源：http://dali.dashuyun.cn/Article/details/gt2zhogqlzu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gotoacloud.top/Article/details/gt2qgvjqvnz.html

[U24] Py：路径操作
来源：http://dali.pycfn.com/Article/details/gt2mxjppafa.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uqwbmmre.html

[U25] Py：CSV 按字典读
来源：http://dali.sysykeji.top/Article/details/gt2nvxuknjt.html

csv.DictReader(f)
来源：http://dali.xylfe.cn/Article/details/gt2colcwgai.html

[U26] Py：并发下载
来源：http://dali.aibaodan.cn/Article/details/gt2kqwkgdnj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.guannengcc.top/Article/details/gt2cljqoupd.html

[U27] Py：异步 HTTP
来源：http://dali.jinqigfzy.top/Article/details/gt2ezkzbjde.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xzwwdbjs.html

[U28] Py：类型别名
来源：http://dali.jqgfzy.top/Article/details/gt2ggmweotq.html

UserId = int
来源：http://dali.fengsongda.top/Article/details/gt2sljsvguv.html

[U29] Py：属性校验
来源：http://dali.0kj1m.cn/Article/details/gt2leqkupde.html

@property 与 @x.setter 配合
来源：http://dali.sweek.top/Article/details/gt2fehfljep.html

[U30] Py：数据类
来源：http://dali.yanxiufei.cn/Article/details/gt2ojybexbc.html

@dataclass(slots=True)
来源：http://dali.ydzc1.top/Article/details/gt2kxvhpzvz.html

[U31] Py：单测
来源：http://dali.nanxinkj.top/Article/details/gt2djadbvfx.html

python -m pytest -q
来源：http://dali.yj202588.top/Article/details/gt2uqnjdkku.html

[U32] Py：代码格式化
来源：http://dali.iojbl.cn/Article/details/gt2sqrctyeq.html

ruff format . && ruff check --fix .
来源：http://dali.redwolf501.top/Article/details/gt2dylrtwse.html

[U33] Py：打包发布
来源：http://dali.nanxinkj.top/Article/details/gt2hslitpww.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.daxiang520.top/Article/details/gt2syvspaoz.html

[U34] Py：判断编码
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvokahyk.html

chardet.detect(raw)
来源：http://dali.cucudq.cn/Article/details/gt2tdyzwnah.html

[U35] Py：发送邮件
来源：http://dali.zycfv.cn/Article/details/gt2hyxfkxyb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sweek.top/Article/details/gt2ofletlmr.html

[U36] Py：定时任务
来源：http://dali.meibo888.top/Article/details/gt2kpeqyltc.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj20258888.top/Article/details/gt2mntzlyzz.html

[U37] Py：读写 Excel
来源：http://dali.mhx1999.top/Article/details/gt2dvxtyhpf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhixingplan.top/Article/details/gt2qrkrugfb.html

[U38] Py：获取脚本所在目录
来源：http://dali.jiagoushi.top/Article/details/gt2piylljdn.html

Path(__file__).resolve().parent
来源：http://dali.daxiang520.top/Article/details/gt2ffrwlmkk.html

[U39] Py：判断是否在交互环境
来源：http://dali.cheryme.top/Article/details/gt2uvwbwmff.html

sys.stdout.isatty()
来源：http://dali.shangyingyoupin.top/Article/details/gt2dzbdrewm.html

[U40] Py：打印到标准错误
来源：http://dali.shangyingyoupin.top/Article/details/gt2dhipiznz.html

print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gt2ohxcaqft.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.guannengcc.top/Article/details/gt2lxpswres.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.smart0.xyz/Article/details/gt2nezbrexd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jianghu66.top/Article/details/gt2zsbjepzu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yj20258888.top/Article/details/gt2zgndavid.html

[U43] PHP：声明命名空间
来源：http://dali.bjfxy.top/Article/details/gt2lbpbhvvh.html

namespace App\Http;
来源：http://dali.hywenlv.cn/Article/details/gt2vfwovvtr.html

[U44] PHP：开启严格类型
来源：http://dali.bjfxy.top/Article/details/gt2qnupomez.html

declare(strict_types=1);
来源：http://dali.aibaodan.cn/Article/details/gt2tubabrkd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shuidangran.top/Article/details/gt2nmprthhk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ezbvjnyd.html

[U46] PHP：可空类型
来源：http://dali.gaohongyu789.top/Article/details/gt2kaiykjmv.html

?string $name = null
来源：http://dali.tanke756.top/Article/details/gt2pnuehnyr.html

[U47] PHP：联合类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xsveykun.html

int|string $id
来源：http://dali.meibo888.top/Article/details/gt2afmbfoom.html

[U48] PHP：纯枚举
来源：http://dali.smart0.xyz/Article/details/gt2bmxwusdb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2phpkqdmj.html

[U49] PHP：只读属性
来源：http://dali.jqgufenzy.top/Article/details/gt2egnkpiyn.html

public readonly string $name
来源：http://dali.jinqigfzy.top/Article/details/gt2cxtbldfu.html

[U50] PHP：构造器属性提升
来源：http://dali.kuanghao11.cn/Article/details/gt2eeewzdww.html

public function __construct(private int $id) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2fisqlajd.html

[U51] PHP：数组解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cofhevqz.html

[$a, $b] = $arr;
来源：http://dali.xziqi.cn/Article/details/gt2gcygmlpm.html

[U52] PHP：箭头函数
来源：http://dali.jlsjyb.cn/Article/details/gt2onlvwwre.html

$double = fn($x) => $x * 2;
来源：http://dali.shuidangran.top/Article/details/gt2kxshzghn.html

[U53] PHP：空合并运算符
来源：http://dali.xziqi.cn/Article/details/gt2otmpxauw.html

$v = $a ?? $b ?? "default";
来源：http://dali.wangdashe.top/Article/details/gt2rgdlwnes.html

[U54] PHP：空安全调用
来源：http://dali.zhiwuduotai.top/Article/details/gt2pclvlnrp.html

$obj?->method()
来源：http://dali.0kj1m.cn/Article/details/gt2ufaqjyrf.html

[U55] PHP：match 表达式
来源：http://dali.nwbrower.top/Article/details/gt2wttwyaoe.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.iojbl.cn/Article/details/gt2zgmtjkpv.html

[U56] PHP：命名参数
来源：http://dali.cdnleiting.top/Article/details/gt2npdazgbw.html

f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gt2zpohjbcf.html

[U57] PHP：字符串插值
来源：http://dali.xuanzx.com/Article/details/gt2epwyxeta.html

"值: {$a}"
来源：http://dali.snrcjt.cn/Article/details/gt2mvfvotzx.html

[U58] PHP：数组三件套
来源：http://dali.nwbrower.top/Article/details/gt2ghzzibvu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2mjkytsfo.html

[U59] PHP：自定义排序
来源：http://dali.redwolf501.top/Article/details/gt2qdoppjgq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gt2acrskvmk.html

[U60] PHP：JSON 编解码
来源：http://dali.jqgufenzy.top/Article/details/gt2yqmaiofe.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjzbhnpm.html

[U61] PHP：正则
来源：http://dali.sxryk.cn/Article/details/gt2uckdhavs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2svxfuktq.html

[U62] PHP：日期对象
来源：http://dali.ivvv.top/Article/details/gt2csgxqxyj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jianghu66.top/Article/details/gt2ynbgpwbf.html

[U63] PHP：文件读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2exfpeqka.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jyoumei.cn/Article/details/gt2gsilgnrj.html

[U64] PHP：目录遍历
来源：http://dali.guannengcc.top/Article/details/gt2ovxdvhzn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cashguo.top/Article/details/gt2dfhrhasq.html

[U65] PHP：会话
来源：http://dali.hfpthk.cn/Article/details/gt2jzckfbyn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2uysvvxlp.html

[U66] PHP：设置 Cookie
来源：http://dali.fzhhl.top/Article/details/gt2ebndpvrt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gotoacloud.top/Article/details/gt2oujdijwv.html

[U67] PHP：处理文件上传
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxsutbxi.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sxryk.cn/Article/details/gt2gphptptc.html

[U68] PHP：PDO 连接
来源：http://dali.gaohongyu789.top/Article/details/gt2fynycvwx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xylfe.cn/Article/details/gt2ibijcnwq.html

[U69] PHP：PDO 预处理
来源：http://dali.daria6918.cn/Article/details/gt2mvwrmomf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hammf.cn/Article/details/gt2lyilfxjn.html

[U70] PHP：PDO 事务
来源：http://dali.sysykeji.top/Article/details/gt2zjkhmeru.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hywenlv.cn/Article/details/gt2gvawxisz.html

[U71] PHP：抛出异常
来源：http://dali.bjfxy.top/Article/details/gt2crhxmoih.html

throw new RuntimeException("失败", 500);
来源：http://dali.yueranfly.top/Article/details/gt2nmlokmux.html

[U72] PHP：写错误日志
来源：http://dali.ydzc1.top/Article/details/gt2pplpcohv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ehwqpu.com/Article/details/gt2acprcwrh.html


<!-- 参考信息 -->