代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xziqi.cn/Article/details/gt2bugvoydb.html

[S51] C++：显式类型转换
来源：http://dali.jinqigufen.top/Article/details/gt2mkqwygoy.html

static_cast<double>(a) / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oqhofybh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhixingplan.top/Article/details/gt2ivmlefdu.html

int size() const noexcept { return n_; }
来源：http://dali.cheryme.top/Article/details/gt2ewgpkitc.html

[S53] C++：移动语义
来源：http://dali.zdqjudy.top/Article/details/gt2mbrhxawc.html

std::vector<int> w = std::move(v);
来源：http://dali.gotoacloud.top/Article/details/gt2yxrekuyw.html

[S54] C++：异常处理
来源：http://dali.jqgfzy.top/Article/details/gt2ohwsaeyg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jlsjyb.cn/Article/details/gt2gcmtzfjp.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqthuqs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pycfn.com/Article/details/gt2diiyxycn.html

[S56] C++：optional
来源：http://dali.zhoulong.xyz/Article/details/gt2grvvkwil.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhixingplan.top/Article/details/gt2ngeilhxj.html

[S57] C++：编译期常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qyzzxscw.html

constexpr int N = 10;
来源：http://dali.sxryk.cn/Article/details/gt2vetoxqoa.html

[S58] C++：命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gt2ochrqlal.html

namespace ns { int f() { return 1; } }
来源：http://dali.ehwqpu.com/Article/details/gt2zgupefgi.html

[S59] C++：静态断言
来源：http://dali.kuanghao11.cn/Article/details/gt2zxzkfylz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuanzx.com/Article/details/gt2puzcdbtd.html

[S60] C++：遍历并删除元素
来源：http://dali.pycfn.com/Article/details/gt2oyqybplw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tian-w.cn/Article/details/gt2xgzijred.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2wbkcqjcl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gt2quauagjo.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2ryboqigx.html

[T01] Kotlin：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oipyeysf.html

println("Hello")
来源：http://dali.jqgfzy.top/Article/details/gt2xpdemhjc.html

[T02] Kotlin：变量
来源：http://dali.svipenyu.cn/Article/details/gt2znbslgfh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hongshengwenyu.top/Article/details/gt2uwrzidfl.html

[T03] Kotlin：字符串模板
来源：http://dali.meibo888.top/Article/details/gt2uzzmqgds.html

"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gt2hpegdcho.html

[T04] Kotlin：空安全
来源：http://dali.yj202588.top/Article/details/gt2alhoaieg.html

val n: String? = null;  n?.length
来源：http://dali.redwolf501.top/Article/details/gt2bsggekea.html

[T05] Kotlin：when 表达式
来源：http://dali.cucudq.cn/Article/details/gt2ookaumrl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hnxiangtu.top/Article/details/gt2gptxpqrl.html

[T06] Kotlin：集合映射
来源：http://dali.nanxinkj.top/Article/details/gt2dpltxkxp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gt2lgcuyndr.html

[T07] Kotlin：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gt2mqmimspa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.quarkkingdee.top/Article/details/gt2clwvckmi.html

[T08] Kotlin：数据类
来源：http://dali.mhx1999.top/Article/details/gt2bwaxpopm.html

data class User(val name: String, val age: Int)
来源：http://dali.9152youxi.cn/Article/details/gt2fkfrgzey.html

[T09] Kotlin：扩展函数
来源：http://dali.ehwqpu.com/Article/details/gt2zxrnsgiz.html

fun String.exclaim() = this + "!"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ughrzjxt.html

[T10] Kotlin：默认参数
来源：http://dali.dashuyun.cn/Article/details/gt2puhiqpuq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgufenzy.top/Article/details/gt2sgwwlewy.html

[T11] Kotlin：协程
来源：http://dali.guowangkeji.top/Article/details/gt2gdoodzje.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jianghu66.top/Article/details/gt2qvvficbo.html

[T12] Kotlin：解构声明
来源：http://dali.jlsjyb.cn/Article/details/gt2kmfpakzl.html

val (a, b) = Pair(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2jgnfnavh.html

[T13] Kotlin：只读 Map
来源：http://dali.zdqjudy.top/Article/details/gt2hgsglbkz.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tzvtigpq.html

[T14] Kotlin：循环
来源：http://dali.hammf.cn/Article/details/gt2llukavqe.html

for (i in 1..10) println(i)
来源：http://dali.yueranfly.top/Article/details/gt2ijuzuwpk.html

[T15] Kotlin：接口
来源：http://dali.haohaochexian.top/Article/details/gt2anjpbmcn.html

interface Shape { fun area(): Double }
来源：http://dali.aibaodan.cn/Article/details/gt2ikpmklzl.html

[T16] Swift：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2lpiovxev.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gt2teukdedb.html

[T17] Swift：变量与常量
来源：http://dali.iojbl.cn/Article/details/gt2ghgfgzqd.html

var a = 1;  let b = 2
来源：http://dali.zycfv.cn/Article/details/gt2mqfbhtwd.html

[T18] Swift：字符串插值
来源：http://dali.daxiang520.top/Article/details/gt2vfyhghsx.html

"值: \(b)"
来源：http://dali.haohaochexian.top/Article/details/gt2uwvnxdtd.html

[T19] Swift：可选绑定
来源：http://dali.zhiwuduotai.top/Article/details/gt2tdcrauji.html

if let n = opt { print(n) }
来源：http://dali.cheryme.top/Article/details/gt2orkfyezr.html

[T20] Swift：数组操作
来源：http://dali.feifeiyinyue.top/Article/details/gt2fenaowlw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xuanzx.com/Article/details/gt2lbutydfq.html

[T21] Swift：遍历
来源：http://dali.xziqi.cn/Article/details/gt2dqlxddpv.html

for x in a { print(x) }
来源：http://dali.316326.xyz/Article/details/gt2zxznazqz.html

[T22] Swift：字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2wgfdqorl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhongyouzk.top/Article/details/gt2ighmxjrx.html

[T23] Swift：函数
来源：http://dali.yj20258.top/Article/details/gt2vubeeovy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.kuanghao11.cn/Article/details/gt2tailznge.html

[T24] Swift：闭包
来源：http://dali.quarkkingdee.top/Article/details/gt2apwjismm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2rrnpidkj.html

[T25] Swift：结构体
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2istcxssn.html

struct P { var x: Int }
来源：http://dali.nanxuanxn.top/Article/details/gt2svnmofnu.html

[T26] Swift：类与重写
来源：http://dali.gotoacloud.top/Article/details/gt2tjhidwog.html

class A: Base { override func f() {} }
来源：http://dali.quarkkingdee.top/Article/details/gt2qopwuubm.html

[T27] Swift：错误处理
来源：http://dali.yueranfly.top/Article/details/gt2ropesmsc.html

do { try f() } catch { print(error) }
来源：http://dali.iojbl.cn/Article/details/gt2lienxiqg.html

[T28] Swift：枚举
来源：http://dali.xuanzx.com/Article/details/gt2myevpxxp.html

enum Color { case red, green }
来源：http://dali.wangdashe.top/Article/details/gt2fhlqaxda.html

[T29] Swift：guard 提前返回
来源：http://dali.jyoumei.cn/Article/details/gt2babmahev.html

guard let x = opt else { return }
来源：http://dali.andypj.xyz/Article/details/gt2glsdwwtt.html

[T30] Swift：协议
来源：http://dali.ybcxt.top/Article/details/gt2tvdfjtyj.html

protocol Shape { func area() -> Double }
来源：http://dali.jianghu66.top/Article/details/gt2edqwqabq.html

[T31] Lua：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2necwycbc.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gt2jgcvpqhw.html

[T32] Lua：局部变量
来源：http://dali.ydzc1.top/Article/details/gt2vlegceew.html

local a = 1
来源：http://dali.ivvv.top/Article/details/gt2agmqqciw.html

[T33] Lua：表（数组）
来源：http://dali.xziqi.cn/Article/details/gt2ocmzgiov.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gogol.net.cn/Article/details/gt2xllteyam.html

[T34] Lua：遍历表
来源：http://dali.redwolf501.top/Article/details/gt2avnbmgrl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.meibo888.top/Article/details/gt2qqbrzvae.html

[T35] Lua：字典表
来源：http://dali.sufxvd.cn/Article/details/gt2qrzsdgzv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.aibaodan.cn/Article/details/gt2wrcminga.html

[T36] Lua：函数
来源：http://dali.guowangkeji.top/Article/details/gt2pylrefyg.html

function add(a, b) return a + b end
来源：http://dali.yonumen.top/Article/details/gt2rbktmkkn.html

[T37] Lua：字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gt2nymipsxl.html

"a" .. "b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ljbswiic.html

[T38] Lua：条件
来源：http://dali.andypj.xyz/Article/details/gt2seqvazmq.html

if x > 0 then print("正") end
来源：http://dali.xylfe.cn/Article/details/gt2bmpcwbrn.html

[T39] Lua：模式匹配
来源：http://dali.tianlin.xyz/Article/details/gt2aeruhwoe.html

string.find(s, "%d+")
来源：http://dali.xuanzx.com/Article/details/gt2ejapprjm.html

[T40] Lua：元表
来源：http://dali.tanke756.top/Article/details/gt2mlxyrjmf.html

setmetatable({}, { __index = base })
来源：http://dali.aibaodan.cn/Article/details/gt2bmxyrkuq.html

[T41] Perl：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2hzwbasgg.html

print "Hello\n";
来源：http://dali.hongshengwenyu.top/Article/details/gt2lxqqmfiv.html

[T42] Perl：变量类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2hglosrsc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj202588.top/Article/details/gt2vdggccln.html

[T43] Perl：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gt2bzlgrdzp.html

"值: $a"
来源：http://dali.gaohongyu789.top/Article/details/gt2dxmyxhqd.html

[T44] Perl：条件
来源：http://dali.jinqigfzy.top/Article/details/gt2rxrxnitq.html

if ($a > 0) { print "正"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dknwocpf.html

[T45] Perl：数组遍历
来源：http://dali.ybcxt.top/Article/details/gt2hvcqwwty.html

for my $x (@arr) { print $x; }
来源：http://dali.jlsjyb.cn/Article/details/gt2lmcrvawb.html

[T46] Perl：哈希操作
来源：http://dali.andypj.xyz/Article/details/gt2ivprnjdx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2jtwgtegh.html

[T47] Perl：正则捕获
来源：http://dali.hnxiangtu.top/Article/details/gt2lfqwxzvu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xinyue.icu/Article/details/gt2bfstrtrc.html

[T48] Perl：正则替换
来源：http://dali.jqgfzy.top/Article/details/gt2kuitvksy.html

$s =~ s/old/new/g;
来源：http://dali.yvedp.cn/Article/details/gt2rshuzgrp.html

[T49] Perl：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2goqaiauw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gt2emgabdpq.html

[T50] Perl：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gt2ykkbaofh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cashguo.top/Article/details/gt2vgzghbxs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.guannengcc.top/Article/details/gt2asjwjofy.html

[T51] Scala：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ignyqsxo.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gt2nxmqlurh.html

[T52] Scala：变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2pdjxsahh.html

val a = 1;  var b = 2
来源：http://dali.andypj.xyz/Article/details/gt2xgdakdvk.html

[T53] Scala：字符串插值
来源：http://dali.zycfv.cn/Article/details/gt2etanjima.html

s"值: $b"
来源：http://dali.yj20258.top/Article/details/gt2ypovykzx.html

[T54] Scala：集合映射
来源：http://dali.gogol.net.cn/Article/details/gt2tmqdwgkq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rinlzzkf.html

[T55] Scala：集合过滤
来源：http://dali.dashuyun.cn/Article/details/gt2lbhzgknk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jyoumei.cn/Article/details/gt2qwpvvbcs.html

[T56] Scala：样例类
来源：http://dali.jqgfzy.top/Article/details/gt2mcfjaljm.html

case class User(name: String, age: Int)
来源：http://dali.mhx1999.top/Article/details/gt2auabumdr.html

[T57] Scala：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gt2gcgincyp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yonumen.top/Article/details/gt2ljeseojk.html

[T58] Scala：函数定义
来源：http://dali.jyoumei.cn/Article/details/gt2hlecjksn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sysykeji.top/Article/details/gt2msgeymtz.html

[T59] Scala：循环
来源：http://dali.zdqjudy.top/Article/details/gt2tpifewek.html

for (i <- 1 to 10) println(i)
来源：http://dali.wangdashe.top/Article/details/gt2yjpsilhs.html

[T60] Scala：折叠
来源：http://dali.guannengcc.top/Article/details/gt2kzrlxsdt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cashguo.top/Article/details/gt2ixbvdogo.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2cmokfcji.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sysykeji.top/Article/details/gt2xmyzhdsy.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2vdkiqeia.html

[U01] Py：创建虚拟环境
来源：http://dali.0kj1m.cn/Article/details/gt2pwkjalrb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fzhhl.top/Article/details/gt2pjahehoz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nanxuanxn.top/Article/details/gt2puoyvrgk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.smart0.xyz/Article/details/gt2zecubhmu.html

[U03] Py：加载 .env 配置
来源：http://dali.pengpengdd.cyou/Article/details/gt2iyslckqi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhengqikj.top/Article/details/gt2hqtehnfu.html

[U04] Py：变量调试打印
来源：http://dali.yuanzhike.top/Article/details/gt2fpzpfppp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jyoumei.cn/Article/details/gt2cksrlpxj.html

[U05] Py：列表去重且保序
来源：http://dali.yanxiufei.cn/Article/details/gt2derveipv.html

list(dict.fromkeys(arr))
来源：http://dali.sysykeji.top/Article/details/gt2qoqhbcov.html

[U06] Py：合并两个字典
来源：http://dali.jiagoushi.top/Article/details/gt2ejhcgsda.html

{**a, **b}
来源：http://dali.kuanghao11.cn/Article/details/gt2izjdzgee.html

[U07] Py：反转字典键值
来源：http://dali.zhengqikj.top/Article/details/gt2kkiqpoca.html

{v: k for k, v in d.items()}
来源：http://dali.yueranfly.top/Article/details/gt2kmyjikcx.html

[U08] Py：展平二维列表
来源：http://dali.cashguo.top/Article/details/gt2yiujdsuc.html

[y for x in nested for y in x]
来源：http://dali.aibaodan.cn/Article/details/gt2dkmkzqgx.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgfzy.top/Article/details/gt2tbitgefz.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nafjgyoo.html

[U10] Py：按值排序字典
来源：http://dali.hnxiangtu.top/Article/details/gt2pxvknuho.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.daria6918.cn/Article/details/gt2isgjvkua.html

[U11] Py：生成器表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2zmvpqovq.html

(x * 2 for x in arr)
来源：http://dali.chenzaomai.com/Article/details/gt2bbsmykjr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mjascvnc.html

Counter(arr).most_common(3)
来源：http://dali.zycfv.cn/Article/details/gt2qgbwvidl.html

[U13] Py：固定长度队列
来源：http://dali.jinqigufen.top/Article/details/gt2frinasru.html

deque(maxlen=10)
来源：http://dali.316326.xyz/Article/details/gt2rvymqgla.html

[U14] Py：分组收集到列表
来源：http://dali.chenjidiqi.icu/Article/details/gt2mshdpxfy.html

defaultdict(list)
来源：http://dali.jinqigufen.top/Article/details/gt2ztuxykbn.html

[U15] Py：高精度计时
来源：http://dali.svipenyu.cn/Article/details/gt2tbairmbc.html

t = time.perf_counter()
来源：http://dali.9152youxi.cn/Article/details/gt2lkunujao.html

[U16] Py：命令行参数解析
来源：http://dali.ehwqpu.com/Article/details/gt2wzaodozp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhoulong.xyz/Article/details/gt2bawtmden.html

[U17] Py：初始化日志
来源：http://dali.nwbrower.top/Article/details/gt2tgiaywvp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.iojbl.cn/Article/details/gt2rmxhvehb.html

[U18] Py：预编译正则
来源：http://dali.yueranfly.top/Article/details/gt2xqdxrcjt.html

pat = re.compile(r"\d+")
来源：http://dali.jlsjyb.cn/Article/details/gt2bmqjztcv.html

[U19] Py：正则替换带回调
来源：http://dali.yj20258.top/Article/details/gt2xhokilta.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hysaishi.cn/Article/details/gt2sqkaogol.html

[U20] Py：缓存函数结果
来源：http://dali.cucudq.cn/Article/details/gt2hlgiigfa.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aibaodan.cn/Article/details/gt2ptjyqgfr.html

[U21] Py：自定义上下文管理器
来源：http://dali.kuanghao11.cn/Article/details/gt2ucliltby.html

@contextlib.contextmanager
来源：http://dali.0kj1m.cn/Article/details/gt2qhzxswdz.html

[U22] Py：矩阵转置
来源：http://dali.ppjwa.cn/Article/details/gt2uokkdigo.html

list(zip(*m))
来源：http://dali.yueranfly.top/Article/details/gt2dzxlcvpt.html

[U23] Py：分块读取大文件
来源：http://dali.fengsongda.top/Article/details/gt2fsosiiuv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.wangshuangyany.cn/Article/details/gt2qcumcakd.html

[U24] Py：路径操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tjqtkgyz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xinyue.icu/Article/details/gt2jlbkkska.html

[U25] Py：CSV 按字典读
来源：http://dali.yongpay.top/Article/details/gt2eneblkqj.html

csv.DictReader(f)
来源：http://dali.yj202588.top/Article/details/gt2lxgneuap.html

[U26] Py：并发下载
来源：http://dali.shuidangran.top/Article/details/gt2cmrjgido.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hfpthk.cn/Article/details/gt2mvzzrfef.html

[U27] Py：异步 HTTP
来源：http://dali.yonumen.top/Article/details/gt2ljmxvbqx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shzxlz.cn/Article/details/gt2vuunygho.html

[U28] Py：类型别名
来源：http://dali.birdmap.top/Article/details/gt2gxjozomq.html

UserId = int
来源：http://dali.dashuyun.cn/Article/details/gt2nfahpnih.html

[U29] Py：属性校验
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2elnbgdnm.html

@property 与 @x.setter 配合
来源：http://dali.ydzc1.top/Article/details/gt2vrapxsap.html

[U30] Py：数据类
来源：http://dali.c1oappe.top/Article/details/gt2wrfnayxv.html

@dataclass(slots=True)
来源：http://dali.sysykeji.top/Article/details/gt2mbxupdel.html

[U31] Py：单测
来源：http://dali.316326.xyz/Article/details/gt2mmqqwjsr.html

python -m pytest -q
来源：http://dali.jianghu66.top/Article/details/gt2hooidgtp.html

[U32] Py：代码格式化
来源：http://dali.dashuyun.cn/Article/details/gt2vfackqpt.html

ruff format . && ruff check --fix .
来源：http://dali.yj20258888.top/Article/details/gt2ltzlrnzh.html

[U33] Py：打包发布
来源：http://dali.zdqjudy.top/Article/details/gt2myiusufd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ydzc1.top/Article/details/gt2bvkbnlrl.html

[U34] Py：判断编码
来源：http://dali.smart0.xyz/Article/details/gt2iutirrov.html

chardet.detect(raw)
来源：http://dali.nanxuanxn.top/Article/details/gt2wuygbvum.html

[U35] Py：发送邮件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tvjxhudg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.daxiang520.top/Article/details/gt2mkacqsls.html

[U36] Py：定时任务
来源：http://dali.aizwys.cn/Article/details/gt2befhpfme.html

schedule.every(10).minutes.do(job)
来源：http://dali.jyoumei.cn/Article/details/gt2xrxdipyh.html

[U37] Py：读写 Excel
来源：http://dali.xuanzx.com/Article/details/gt2hdfutotq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.316326.xyz/Article/details/gt2nbokfzyv.html

[U38] Py：获取脚本所在目录
来源：http://dali.haohaochexian.top/Article/details/gt2eekdcxgo.html

Path(__file__).resolve().parent
来源：http://dali.mhx1999.top/Article/details/gt2kaqyjknu.html

[U39] Py：判断是否在交互环境
来源：http://dali.yangfankeji.com/Article/details/gt2cvuciehq.html

sys.stdout.isatty()
来源：http://dali.xuanzx.com/Article/details/gt2vvnpllir.html

[U40] Py：打印到标准错误
来源：http://dali.feifeiyinyue.top/Article/details/gt2cemjqxan.html

print("err", file=sys.stderr)
来源：http://dali.gzhubu.top/Article/details/gt2ceywarwd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.dashuyun.cn/Article/details/gt2qojycbqb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xinyue.icu/Article/details/gt2sbwoftxy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yj20258888.top/Article/details/gt2agsjvmcv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.meibo888.top/Article/details/gt2xgrtlxrh.html

[U43] PHP：声明命名空间
来源：http://dali.quarkkingdee.top/Article/details/gt2uzdngpwt.html

namespace App\Http;
来源：http://dali.gzhubu.top/Article/details/gt2evvmdzrs.html

[U44] PHP：开启严格类型
来源：http://dali.ydzc1.top/Article/details/gt2pgpkobhy.html

declare(strict_types=1);
来源：http://dali.daria6918.cn/Article/details/gt2klkoemtz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhixingplan.top/Article/details/gt2yugnrhjh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gt2nevbgyuv.html

[U46] PHP：可空类型
来源：http://dali.ppjwa.cn/Article/details/gt2xdyqepjf.html

?string $name = null
来源：http://dali.nanxuanxn.top/Article/details/gt2zunleunv.html

[U47] PHP：联合类型
来源：http://dali.andypj.xyz/Article/details/gt2hcytnvom.html

int|string $id
来源：http://dali.jyoumei.cn/Article/details/gt2qnkyzbew.html

[U48] PHP：纯枚举
来源：http://dali.nwbrower.top/Article/details/gt2qwzhpgnv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.mhx1999.top/Article/details/gt2jlqearxo.html

[U49] PHP：只读属性
来源：http://dali.wangdashe.top/Article/details/gt2gxyimczk.html

public readonly string $name
来源：http://dali.gotoacloud.top/Article/details/gt2kavteuce.html

[U50] PHP：构造器属性提升
来源：http://dali.hfpthk.cn/Article/details/gt2ojrnyaqc.html

public function __construct(private int $id) {}
来源：http://dali.dianchejie.cn/Article/details/gt2xwgeskzc.html

[U51] PHP：数组解构
来源：http://dali.hfpthk.cn/Article/details/gt2wlvtlqjk.html

[$a, $b] = $arr;
来源：http://dali.cdnleiting.top/Article/details/gt2mfiwtsla.html

[U52] PHP：箭头函数
来源：http://dali.nwbrower.top/Article/details/gt2nzbidvld.html

$double = fn($x) => $x * 2;
来源：http://dali.shzxlz.cn/Article/details/gt2xyztoufc.html

[U53] PHP：空合并运算符
来源：http://dali.zycfv.cn/Article/details/gt2pzrmcezk.html

$v = $a ?? $b ?? "default";
来源：http://dali.yongpay.top/Article/details/gt2lolgabdy.html

[U54] PHP：空安全调用
来源：http://dali.mhx1999.top/Article/details/gt2vbjzqnph.html

$obj?->method()
来源：http://dali.quarkkingdee.top/Article/details/gt2zzqmoqdx.html

[U55] PHP：match 表达式
来源：http://dali.gzhubu.top/Article/details/gt2tgnaybdc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ehwqpu.com/Article/details/gt2gkhcljye.html

[U56] PHP：命名参数
来源：http://dali.shuidangran.top/Article/details/gt2llmwprpf.html

f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2zkmpqqnx.html

[U57] PHP：字符串插值
来源：http://dali.meibo888.top/Article/details/gt2ohlfoihi.html

"值: {$a}"
来源：http://dali.wangdashe.top/Article/details/gt2kcmzkitu.html

[U58] PHP：数组三件套
来源：http://dali.zdqjudy.top/Article/details/gt2vfmftene.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yuxming.cn/Article/details/gt2ylokakom.html

[U59] PHP：自定义排序
来源：http://dali.wangdashe.top/Article/details/gt2ezogoszx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gt2wlyikfmm.html

[U60] PHP：JSON 编解码
来源：http://dali.fengsongda.top/Article/details/gt2kxihhrix.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.chenlongwang.top/Article/details/gt2cpwdevmf.html

[U61] PHP：正则
来源：http://dali.cqqwz.cn/Article/details/gt2cnlvtqzs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gt2wgwroetm.html

[U62] PHP：日期对象
来源：http://dali.zhoulong.xyz/Article/details/gt2stndqkab.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hnxiangtu.top/Article/details/gt2dvvodcnv.html

[U63] PHP：文件读写
来源：http://dali.zhoulong.xyz/Article/details/gt2jpjrznpw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.daxiang520.top/Article/details/gt2gtnclnte.html

[U64] PHP：目录遍历
来源：http://dali.yj20258.top/Article/details/gt2ajyahnrj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cajokdtj.html

[U65] PHP：会话
来源：http://dali.gogol.net.cn/Article/details/gt2xtszpyho.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.fzhhl.top/Article/details/gt2dilnxpzy.html

[U66] PHP：设置 Cookie
来源：http://dali.jyoumei.cn/Article/details/gt2udhppbjc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2eoeolqzk.html

[U67] PHP：处理文件上传
来源：http://dali.feifeiyinyue.top/Article/details/gt2dptmqocw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hnqzz.top/Article/details/gt2gvtkmdwb.html

[U68] PHP：PDO 连接
来源：http://dali.zhiwuduotai.top/Article/details/gt2craefyci.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yvedp.cn/Article/details/gt2mbecygmc.html

[U69] PHP：PDO 预处理
来源：http://dali.cdnleiting.top/Article/details/gt2nygzirvp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jqgfzy.top/Article/details/gt2oecgzvhl.html

[U70] PHP：PDO 事务
来源：http://dali.nwbrower.top/Article/details/gt2uuvimvmn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2rcanabyp.html

[U71] PHP：抛出异常
来源：http://dali.sweek.top/Article/details/gt2omqgsunk.html

throw new RuntimeException("失败", 500);
来源：http://dali.yongpay.top/Article/details/gt2gwqcluwf.html

[U72] PHP：写错误日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qththqol.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gotoacloud.top/Article/details/gt2ohdqlioa.html

[U73] PHP：读取 ini 配置
来源：http://dali.sysykeji.top/Article/details/gt2robunjkx.html

parse_ini_file("config.ini", true)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ytpausmk.html

[U74] PHP：读取环境变量
来源：http://dali.birdmap.top/Article/details/gt2kygdhgcb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hfpthk.cn/Article/details/gt2mfnxrdrl.html

[U75] PHP：依赖注入
来源：http://dali.xinyue.icu/Article/details/gt2chkjtajc.html

composer require psr/container
来源：http://dali.guowangkeji.top/Article/details/gt2qtcwukif.html

[U76] PHP：简单路由
来源：http://dali.jinqigufen.top/Article/details/gt2brpdnnwe.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yanxiufei.cn/Article/details/gt2xnflmusv.html


<!-- 参考信息 -->