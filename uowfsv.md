代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenzaomai.com/Article/details/gt2owhgqzms.html

[S55] C++：结构化绑定
来源：http://dali.tian-w.cn/Article/details/gt2kmyskgvm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2tnaaqgbc.html

[S56] C++：optional
来源：http://dali.svipenyu.cn/Article/details/gt2wnqjpqit.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ovsaoads.html

[S57] C++：编译期常量
来源：http://dali.yanxiufei.cn/Article/details/gt2hcphzbmm.html

constexpr int N = 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2pvogycsu.html

[S58] C++：命名空间
来源：http://dali.mhx1999.top/Article/details/gt2alphzcem.html

namespace ns { int f() { return 1; } }
来源：http://dali.ybcxt.top/Article/details/gt2hiitskdb.html

[S59] C++：静态断言
来源：http://dali.fengsongda.top/Article/details/gt2lwbnigre.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnqzz.top/Article/details/gt2pubjnxlv.html

[S60] C++：遍历并删除元素
来源：http://dali.zhongyouzk.top/Article/details/gt2boxgeqet.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.havefunace.top/Article/details/gt2wahsfgip.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2amswnowr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhiwuduotai.top/Article/details/gt2fypjzdwp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2qqiusbws.html

[T01] Kotlin：Hello World
来源：http://dali.ivvv.top/Article/details/gt2appueszl.html

println("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ozliyzfu.html

[T02] Kotlin：变量
来源：http://dali.cqqwz.cn/Article/details/gt2gomfgjyo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.316326.xyz/Article/details/gt2nybbgkdm.html

[T03] Kotlin：字符串模板
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rzbddyyj.html

"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gt2wxrlshgb.html

[T04] Kotlin：空安全
来源：http://dali.guannengcc.top/Article/details/gt2evzcckfg.html

val n: String? = null;  n?.length
来源：http://dali.andypj.xyz/Article/details/gt2ahtjqjdx.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigfzy.top/Article/details/gt2hwjfsgsw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shzxlz.cn/Article/details/gt2zjplqnfe.html

[T06] Kotlin：集合映射
来源：http://dali.nanxinkj.top/Article/details/gt2csdxgadt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2ixrxpzlm.html

[T07] Kotlin：集合过滤
来源：http://dali.haohaochexian.top/Article/details/gt2gwrfihmg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.quarkkingdee.top/Article/details/gt2fycpftbc.html

[T08] Kotlin：数据类
来源：http://dali.sweek.top/Article/details/gt2bwbxaahi.html

data class User(val name: String, val age: Int)
来源：http://dali.yongpay.top/Article/details/gt2xxwoqtpq.html

[T09] Kotlin：扩展函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2sxxeccqn.html

fun String.exclaim() = this + "!"
来源：http://dali.tianlin.xyz/Article/details/gt2sefkbiax.html

[T10] Kotlin：默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rvvvuhum.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenjidiqi.icu/Article/details/gt2skmeubhu.html

[T11] Kotlin：协程
来源：http://dali.xziqi.cn/Article/details/gt2kmphjuvw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aibaodan.cn/Article/details/gt2eutdzscn.html

[T12] Kotlin：解构声明
来源：http://dali.zhongyouzk.top/Article/details/gt2wjjnfgve.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangdashe.top/Article/details/gt2jkgzqije.html

[T13] Kotlin：只读 Map
来源：http://dali.c1oappe.top/Article/details/gt2dqztwglt.html

val m = mapOf("a" to 1)
来源：http://dali.aizwys.cn/Article/details/gt2dpuynxts.html

[T14] Kotlin：循环
来源：http://dali.jqgfzy.top/Article/details/gt2kepjhktu.html

for (i in 1..10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gt2fghvvfml.html

[T15] Kotlin：接口
来源：http://dali.shuidangran.top/Article/details/gt2gjgruemx.html

interface Shape { fun area(): Double }
来源：http://dali.quarkkingdee.top/Article/details/gt2cyjvegqg.html

[T16] Swift：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2kosovutt.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gt2iywiifqg.html

[T17] Swift：变量与常量
来源：http://dali.sxryk.cn/Article/details/gt2fumshpmt.html

var a = 1;  let b = 2
来源：http://dali.dianchejie.cn/Article/details/gt2obsquzyz.html

[T18] Swift：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gt2xsfhkiwc.html

"值: \(b)"
来源：http://dali.yvedp.cn/Article/details/gt2peeyvliw.html

[T19] Swift：可选绑定
来源：http://dali.yvedp.cn/Article/details/gt2yhwglghn.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gt2xtpazpse.html

[T20] Swift：数组操作
来源：http://dali.fengsongda.top/Article/details/gt2schofwkn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sweek.top/Article/details/gt2vjqgtktk.html

[T21] Swift：遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2qhiwjexi.html

for x in a { print(x) }
来源：http://dali.jinqigufen.top/Article/details/gt2eylfedua.html

[T22] Swift：字典
来源：http://dali.c1oappe.top/Article/details/gt2mxshltfk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigufen.top/Article/details/gt2kxodxvxt.html

[T23] Swift：函数
来源：http://dali.zhengqikj.top/Article/details/gt2jbxdlkku.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.smart0.xyz/Article/details/gt2sergsmlx.html

[T24] Swift：闭包
来源：http://dali.quarkkingdee.top/Article/details/gt2oezpflaq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.havefunace.top/Article/details/gt2qpeagffk.html

[T25] Swift：结构体
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckuemrle.html

struct P { var x: Int }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fzbufiyu.html

[T26] Swift：类与重写
来源：http://dali.jyoumei.cn/Article/details/gt2pnnffvvd.html

class A: Base { override func f() {} }
来源：http://dali.quarkkingdee.top/Article/details/gt2njjwdeyp.html

[T27] Swift：错误处理
来源：http://dali.mhx1999.top/Article/details/gt2vmasdoqh.html

do { try f() } catch { print(error) }
来源：http://dali.andypj.xyz/Article/details/gt2kpjzmcak.html

[T28] Swift：枚举
来源：http://dali.xylfe.cn/Article/details/gt2nmxjktst.html

enum Color { case red, green }
来源：http://dali.hfpthk.cn/Article/details/gt2bmdkcpcb.html

[T29] Swift：guard 提前返回
来源：http://dali.cdnleiting.top/Article/details/gt2ewujdfok.html

guard let x = opt else { return }
来源：http://dali.hywenlv.cn/Article/details/gt2wyyvphxc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ocufirnv.html

protocol Shape { func area() -> Double }
来源：http://dali.jlsjyb.cn/Article/details/gt2iklnlapb.html

[T31] Lua：Hello World
来源：http://dali.pycfn.com/Article/details/gt2todzneuk.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gt2vvlybrkw.html

[T32] Lua：局部变量
来源：http://dali.ydzc1.top/Article/details/gt2dpkilorg.html

local a = 1
来源：http://dali.bjfxy.top/Article/details/gt2qvpxzhpo.html

[T33] Lua：表（数组）
来源：http://dali.shangyingyoupin.top/Article/details/gt2awdfphdm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.mhx1999.top/Article/details/gt2gwbdkhvn.html

[T34] Lua：遍历表
来源：http://dali.dashuyun.cn/Article/details/gt2pjgqasbj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenjidiqi.icu/Article/details/gt2xezhroyh.html

[T35] Lua：字典表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2moypznbt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj202588.top/Article/details/gt2jpwconzv.html

[T36] Lua：函数
来源：http://dali.yueranfly.top/Article/details/gt2vwsphhmy.html

function add(a, b) return a + b end
来源：http://dali.gaohongyu789.top/Article/details/gt2akzckmoz.html

[T37] Lua：字符串拼接
来源：http://dali.hammf.cn/Article/details/gt2eccweked.html

"a" .. "b"
来源：http://dali.yuxming.cn/Article/details/gt2mgxiulfo.html

[T38] Lua：条件
来源：http://dali.svipenyu.cn/Article/details/gt2eqykcavr.html

if x > 0 then print("正") end
来源：http://dali.cheryme.top/Article/details/gt2xeqhrtxm.html

[T39] Lua：模式匹配
来源：http://dali.cashguo.top/Article/details/gt2uaivftco.html

string.find(s, "%d+")
来源：http://dali.redwolf501.top/Article/details/gt2vvupyxog.html

[T40] Lua：元表
来源：http://dali.iojbl.cn/Article/details/gt2txelwnjo.html

setmetatable({}, { __index = base })
来源：http://dali.shuidangran.top/Article/details/gt2jggakjsq.html

[T41] Perl：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2tvyitozk.html

print "Hello\n";
来源：http://dali.pengpengdd.cyou/Article/details/gt2pvsnsqua.html

[T42] Perl：变量类型
来源：http://dali.vqdsnc.cn/Article/details/gt2oogmylzw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cheryme.top/Article/details/gt2wenjszoe.html

[T43] Perl：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gt2jovolcti.html

"值: $a"
来源：http://dali.fengsongda.top/Article/details/gt2zctkwpvt.html

[T44] Perl：条件
来源：http://dali.ydzc1.top/Article/details/gt2jkhaxsly.html

if ($a > 0) { print "正"; }
来源：http://dali.cqqwz.cn/Article/details/gt2xdrqchqr.html

[T45] Perl：数组遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2ddrgjyep.html

for my $x (@arr) { print $x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhhavxgo.html

[T46] Perl：哈希操作
来源：http://dali.zhoulong.xyz/Article/details/gt2zfcjvtkz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ggaivcsz.html

[T47] Perl：正则捕获
来源：http://dali.iojbl.cn/Article/details/gt2xztuktgo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.redwolf501.top/Article/details/gt2krqripup.html

[T48] Perl：正则替换
来源：http://dali.sysykeji.top/Article/details/gt2tfismxhn.html

$s =~ s/old/new/g;
来源：http://dali.svipenyu.cn/Article/details/gt2jovpuqvw.html

[T49] Perl：函数
来源：http://dali.sweek.top/Article/details/gt2idmeiolp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gt2lkxtpvhe.html

[T50] Perl：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gt2udxlzlkl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nrdrarkt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.kuanghao11.cn/Article/details/gt2zqyqyxjq.html

[T51] Scala：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2pzxzvkdi.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gt2ybgztyjt.html

[T52] Scala：变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cnvkannc.html

val a = 1;  var b = 2
来源：http://dali.zhixingplan.top/Article/details/gt2mnqlovot.html

[T53] Scala：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gt2kusnlrsb.html

s"值: $b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kzlnmhqo.html

[T54] Scala：集合映射
来源：http://dali.0kj1m.cn/Article/details/gt2gimbdpoy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yj202588.top/Article/details/gt2gjkzdwmr.html

[T55] Scala：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tbfiabih.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zdqjudy.top/Article/details/gt2nfydovrf.html

[T56] Scala：样例类
来源：http://dali.yj202588.top/Article/details/gt2qurfxtzk.html

case class User(name: String, age: Int)
来源：http://dali.yonumen.top/Article/details/gt2ptofzsst.html

[T57] Scala：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2drqlpsez.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jqgfzy.top/Article/details/gt2dhqdmqna.html

[T58] Scala：函数定义
来源：http://dali.9152youxi.cn/Article/details/gt2sewxzpyf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigufen.top/Article/details/gt2oeralimn.html

[T59] Scala：循环
来源：http://dali.jiagoushi.top/Article/details/gt2kudgjznf.html

for (i <- 1 to 10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gt2blayebgt.html

[T60] Scala：折叠
来源：http://dali.ppjwa.cn/Article/details/gt2tozetlsn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.guannengcc.top/Article/details/gt2vvwqvjne.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2fjgprxke.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yonumen.top/Article/details/gt2potgeufz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2sldezxxk.html

[U01] Py：创建虚拟环境
来源：http://dali.dashuyun.cn/Article/details/gt2upgtlwks.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jianghu66.top/Article/details/gt2rjggyqkt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.kuanghao11.cn/Article/details/gt2vmwvkyag.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.pycfn.com/Article/details/gt2wgclivhs.html

[U03] Py：加载 .env 配置
来源：http://dali.316326.xyz/Article/details/gt2hgwnqcwv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cucudq.cn/Article/details/gt2pkhgxfxv.html

[U04] Py：变量调试打印
来源：http://dali.jinqigufen.top/Article/details/gt2dzarmwph.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shuidangran.top/Article/details/gt2mgkyrrhp.html

[U05] Py：列表去重且保序
来源：http://dali.chenjidiqi.icu/Article/details/gt2bthwauqx.html

list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gt2ketpxxrh.html

[U06] Py：合并两个字典
来源：http://dali.jqgfzy.top/Article/details/gt2akogicgs.html

{**a, **b}
来源：http://dali.yj202588.top/Article/details/gt2cjjqqpjv.html

[U07] Py：反转字典键值
来源：http://dali.xylfe.cn/Article/details/gt2bcreefla.html

{v: k for k, v in d.items()}
来源：http://dali.yangfankeji.com/Article/details/gt2pgohrmny.html

[U08] Py：展平二维列表
来源：http://dali.cashguo.top/Article/details/gt2ghacjqtn.html

[y for x in nested for y in x]
来源：http://dali.yanxiufei.cn/Article/details/gt2fhoerbeh.html

[U09] Py：字典取最大值的键
来源：http://dali.mhx1999.top/Article/details/gt2uoghnalj.html

max(d, key=d.get)
来源：http://dali.hysaishi.cn/Article/details/gt2tszvsstu.html

[U10] Py：按值排序字典
来源：http://dali.gotoacloud.top/Article/details/gt2qvzieciy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.vqdsnc.cn/Article/details/gt2tdsriiqx.html

[U11] Py：生成器表达式
来源：http://dali.yj202588.top/Article/details/gt2uxmncqbi.html

(x * 2 for x in arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zdjxsbrd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.dianchejie.cn/Article/details/gt2opeirujw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qasfnsir.html

[U13] Py：固定长度队列
来源：http://dali.wangdashe.top/Article/details/gt2vylicdbm.html

deque(maxlen=10)
来源：http://dali.c1oappe.top/Article/details/gt2ilcjncva.html

[U14] Py：分组收集到列表
来源：http://dali.gzhubu.top/Article/details/gt2saqxnjlr.html

defaultdict(list)
来源：http://dali.shuidangran.top/Article/details/gt2vpnbsmbc.html

[U15] Py：高精度计时
来源：http://dali.zhongyouzk.top/Article/details/gt2slxfnhyq.html

t = time.perf_counter()
来源：http://dali.wangdashe.top/Article/details/gt2qzehedjk.html

[U16] Py：命令行参数解析
来源：http://dali.yj20258.top/Article/details/gt2xbrmiheb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yonumen.top/Article/details/gt2afiquvjh.html

[U17] Py：初始化日志
来源：http://dali.xinyue.icu/Article/details/gt2xgkvokff.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shuidangran.top/Article/details/gt2skijvwsg.html

[U18] Py：预编译正则
来源：http://dali.nanxinkj.top/Article/details/gt2aamcqhly.html

pat = re.compile(r"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ldsbiuxk.html

[U19] Py：正则替换带回调
来源：http://dali.redwolf501.top/Article/details/gt2pbjpxkog.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cashguo.top/Article/details/gt2bfnkrahe.html

[U20] Py：缓存函数结果
来源：http://dali.ivvv.top/Article/details/gt2iolmqayu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sxryk.cn/Article/details/gt2gmhdyeda.html

[U21] Py：自定义上下文管理器
来源：http://dali.gotoacloud.top/Article/details/gt2ebwymcim.html

@contextlib.contextmanager
来源：http://dali.redwolf501.top/Article/details/gt2qszqfjqg.html

[U22] Py：矩阵转置
来源：http://dali.smart0.xyz/Article/details/gt2nhdrhooz.html

list(zip(*m))
来源：http://dali.birdmap.top/Article/details/gt2kvfjzhgk.html

[U23] Py：分块读取大文件
来源：http://dali.zhongyouzk.top/Article/details/gt2guixkonw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tian-w.cn/Article/details/gt2qezvxmhc.html

[U24] Py：路径操作
来源：http://dali.zhoulong.xyz/Article/details/gt2uvnpxjfc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gt2lnebewno.html

[U25] Py：CSV 按字典读
来源：http://dali.cdnleiting.top/Article/details/gt2legcbvvn.html

csv.DictReader(f)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lpbvqfpx.html

[U26] Py：并发下载
来源：http://dali.cheryme.top/Article/details/gt2qpxxvvdx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jlsjyb.cn/Article/details/gt2prajpjaf.html

[U27] Py：异步 HTTP
来源：http://dali.xylfe.cn/Article/details/gt2iqlmbgub.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenlongwang.top/Article/details/gt2okgstlgf.html

[U28] Py：类型别名
来源：http://dali.zhixingplan.top/Article/details/gt2qipcqsmd.html

UserId = int
来源：http://dali.zdqjudy.top/Article/details/gt2ekqtuaah.html

[U29] Py：属性校验
来源：http://dali.hnqzz.top/Article/details/gt2gtstoizb.html

@property 与 @x.setter 配合
来源：http://dali.cashguo.top/Article/details/gt2bsozeqni.html

[U30] Py：数据类
来源：http://dali.smart0.xyz/Article/details/gt2txdafocc.html

@dataclass(slots=True)
来源：http://dali.gaohongyu789.top/Article/details/gt2abgqztzw.html

[U31] Py：单测
来源：http://dali.jinqigufen.top/Article/details/gt2jdmqknxb.html

python -m pytest -q
来源：http://dali.andypj.xyz/Article/details/gt2hwsnwonj.html

[U32] Py：代码格式化
来源：http://dali.yuanzhike.top/Article/details/gt2pczdnbkr.html

ruff format . && ruff check --fix .
来源：http://dali.xinyue.icu/Article/details/gt2jvnzpncm.html

[U33] Py：打包发布
来源：http://dali.smart0.xyz/Article/details/gt2jlvmbgyt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sufxvd.cn/Article/details/gt2ijcuqlwn.html

[U34] Py：判断编码
来源：http://dali.c1oappe.top/Article/details/gt2gpbxvvxk.html

chardet.detect(raw)
来源：http://dali.yvedp.cn/Article/details/gt2uearhwcz.html

[U35] Py：发送邮件
来源：http://dali.sweek.top/Article/details/gt2wzhpkxqb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zdhktqgd.html

[U36] Py：定时任务
来源：http://dali.zdqjudy.top/Article/details/gt2zrczyrhw.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj20258888.top/Article/details/gt2gdnsnkdt.html

[U37] Py：读写 Excel
来源：http://dali.jianghu66.top/Article/details/gt2tgvbtzif.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cheryme.top/Article/details/gt2hetadosh.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinqigfzy.top/Article/details/gt2krqpiltz.html

Path(__file__).resolve().parent
来源：http://dali.fengsongda.top/Article/details/gt2zrsuouwe.html

[U39] Py：判断是否在交互环境
来源：http://dali.hfpthk.cn/Article/details/gt2xumuvrsi.html

sys.stdout.isatty()
来源：http://dali.316326.xyz/Article/details/gt2xfwgnraw.html

[U40] Py：打印到标准错误
来源：http://dali.tianlin.xyz/Article/details/gt2qwrqtrim.html

print("err", file=sys.stderr)
来源：http://dali.tian-w.cn/Article/details/gt2pyjumcsz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sweek.top/Article/details/gt2czzoznzj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.fengsongda.top/Article/details/gt2myeszvky.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sweek.top/Article/details/gt2nlfhwaxi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.svipenyu.cn/Article/details/gt2tygmpxad.html

[U43] PHP：声明命名空间
来源：http://dali.andypj.xyz/Article/details/gt2jktokruz.html

namespace App\Http;
来源：http://dali.sysykeji.top/Article/details/gt2pqngxaro.html

[U44] PHP：开启严格类型
来源：http://dali.shzxlz.cn/Article/details/gt2keryoswn.html

declare(strict_types=1);
来源：http://dali.cdnleiting.top/Article/details/gt2hlvzugji.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhixingplan.top/Article/details/gt2vswssgkw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gt2vgjlmnzu.html

[U46] PHP：可空类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xsymxchi.html

?string $name = null
来源：http://dali.yj20258.top/Article/details/gt2ohqsvwqm.html

[U47] PHP：联合类型
来源：http://dali.dianchejie.cn/Article/details/gt2hmhikrhz.html

int|string $id
来源：http://dali.sufxvd.cn/Article/details/gt2odfuxqwf.html

[U48] PHP：纯枚举
来源：http://dali.yanxiufei.cn/Article/details/gt2efebdbil.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2mznlijai.html

[U49] PHP：只读属性
来源：http://dali.0kj1m.cn/Article/details/gt2huirptwh.html

public readonly string $name
来源：http://dali.sxryk.cn/Article/details/gt2numsxnmq.html

[U50] PHP：构造器属性提升
来源：http://dali.yuanzhike.top/Article/details/gt2nqeswhww.html

public function __construct(private int $id) {}
来源：http://dali.9152youxi.cn/Article/details/gt2okphtset.html

[U51] PHP：数组解构
来源：http://dali.zhiwuduotai.top/Article/details/gt2apizybhq.html

[$a, $b] = $arr;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xwqjawpo.html

[U52] PHP：箭头函数
来源：http://dali.birdmap.top/Article/details/gt2vauxafnq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhengqikj.top/Article/details/gt2falqzpht.html

[U53] PHP：空合并运算符
来源：http://dali.chenlongwang.top/Article/details/gt2tqiempca.html

$v = $a ?? $b ?? "default";
来源：http://dali.fzhhl.top/Article/details/gt2skxqwrrj.html

[U54] PHP：空安全调用
来源：http://dali.xuetiantiany.cn/Article/details/gt2jwpwmuwd.html

$obj?->method()
来源：http://dali.snrcjt.cn/Article/details/gt2gmddsnod.html

[U55] PHP：match 表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xdhhmglw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yanxiufei.cn/Article/details/gt2ohnituoe.html

[U56] PHP：命名参数
来源：http://dali.hywenlv.cn/Article/details/gt2rddfifbz.html

f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fatdcufr.html

[U57] PHP：字符串插值
来源：http://dali.fzhhl.top/Article/details/gt2rmwgnjjt.html

"值: {$a}"
来源：http://dali.nanxuanxn.top/Article/details/gt2ekjhqest.html

[U58] PHP：数组三件套
来源：http://dali.ydzc1.top/Article/details/gt2qpkwfesa.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ehwqpu.com/Article/details/gt2uqkieaxf.html

[U59] PHP：自定义排序
来源：http://dali.cdnleiting.top/Article/details/gt2zvkqmija.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigufen.top/Article/details/gt2qovrfznl.html

[U60] PHP：JSON 编解码
来源：http://dali.jqgfzy.top/Article/details/gt2qlaaodpl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yongpay.top/Article/details/gt2iyeyadaf.html

[U61] PHP：正则
来源：http://dali.ybcxt.top/Article/details/gt2pokklmdj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2diwifdko.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2plgmvoqe.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wdfkrtab.html

[U63] PHP：文件读写
来源：http://dali.xziqi.cn/Article/details/gt2qggmkzxg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yj202588.top/Article/details/gt2fcntlkbd.html

[U64] PHP：目录遍历
来源：http://dali.chenlongwang.top/Article/details/gt2cusplwkd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhengqikj.top/Article/details/gt2lkgvwplb.html

[U65] PHP：会话
来源：http://dali.smart0.xyz/Article/details/gt2hrsvzuyf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sweek.top/Article/details/gt2vvbqqcku.html

[U66] PHP：设置 Cookie
来源：http://dali.tian-w.cn/Article/details/gt2emaamgcp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yvedp.cn/Article/details/gt2foihjhgz.html

[U67] PHP：处理文件上传
来源：http://dali.redwolf501.top/Article/details/gt2teljazjm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhoulong.xyz/Article/details/gt2sfntugps.html

[U68] PHP：PDO 连接
来源：http://dali.zycfv.cn/Article/details/gt2sgjwtbcs.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.fzhhl.top/Article/details/gt2esdwmtzz.html

[U69] PHP：PDO 预处理
来源：http://dali.9152youxi.cn/Article/details/gt2oeeupqzk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.chenzaomai.com/Article/details/gt2uhxhvvzf.html

[U70] PHP：PDO 事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nfqhseon.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yongpay.top/Article/details/gt2jtphngfc.html

[U71] PHP：抛出异常
来源：http://dali.smart0.xyz/Article/details/gt2tnuhvcth.html

throw new RuntimeException("失败", 500);
来源：http://dali.redwolf501.top/Article/details/gt2ojpzcmeu.html

[U72] PHP：写错误日志
来源：http://dali.tian-w.cn/Article/details/gt2dovqdlxo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jlsjyb.cn/Article/details/gt2dkuxaxcd.html

[U73] PHP：读取 ini 配置
来源：http://dali.gogol.net.cn/Article/details/gt2bhsofhyo.html

parse_ini_file("config.ini", true)
来源：http://dali.meibo888.top/Article/details/gt2ytqpknbm.html

[U74] PHP：读取环境变量
来源：http://dali.fengsongda.top/Article/details/gt2aarwywkj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xinyue.icu/Article/details/gt2qwewvsbk.html

[U75] PHP：依赖注入
来源：http://dali.jlsjyb.cn/Article/details/gt2bkvhxqhj.html

composer require psr/container
来源：http://dali.cqqwz.cn/Article/details/gt2higjiggy.html

[U76] PHP：简单路由
来源：http://dali.jlsjyb.cn/Article/details/gt2gchvpioi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zqpelthp.html

[U77] PHP：模板渲染
来源：http://dali.xuanzx.com/Article/details/gt2tmarjtaz.html

composer require twig/twig
来源：http://dali.gaohongyu789.top/Article/details/gt2cvyqincj.html

[U78] PHP：单元测试
来源：http://dali.hysaishi.cn/Article/details/gt2xnxjdzyl.html

composer require --dev phpunit/phpunit
来源：http://dali.zhixingplan.top/Article/details/gt2voddltxq.html

[U79] PHP：静态分析
来源：http://dali.gzhubu.top/Article/details/gt2hboldthq.html

composer require --dev phpstan/phpstan
来源：http://dali.jiagoushi.top/Article/details/gt2aatlawfd.html

[U80] PHP：代码规范修复
来源：http://dali.hongshengwenyu.top/Article/details/gt2fgpcncza.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.pycfn.com/Article/details/gt2pdnyclog.html


<!-- 参考信息 -->