代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.0kj1m.cn/Article/details/gtazbflrqm.html

[S53] C++：移动语义
来源：http://dali.xuanzx.com/Article/details/gtbldvpnxu.html

std::vector<int> w = std::move(v);
来源：http://dali.shzxlz.cn/Article/details/gtevrrhseg.html

[S54] C++：异常处理
来源：http://dali.ppjwa.cn/Article/details/gthyolmyid.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cheryme.top/Article/details/gtrbalphit.html

[S55] C++：结构化绑定
来源：http://dali.birdmap.top/Article/details/gtuopjjoqf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xziqi.cn/Article/details/gtpdtszohm.html

[S56] C++：optional
来源：http://dali.dashuyun.cn/Article/details/gtiyekpwec.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.0kj1m.cn/Article/details/gtnlaclath.html

[S57] C++：编译期常量
来源：http://dali.jqgufenzy.top/Article/details/gthtbmcivj.html

constexpr int N = 10;
来源：http://dali.yonumen.top/Article/details/gtmhsxltop.html

[S58] C++：命名空间
来源：http://dali.dianchejie.cn/Article/details/gtfswbcxqd.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgufenzy.top/Article/details/gttgtiuwqo.html

[S59] C++：静态断言
来源：http://dali.zhixingplan.top/Article/details/gtyfrrmqra.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yonumen.top/Article/details/gthocgpysh.html

[S60] C++：遍历并删除元素
来源：http://dali.sxryk.cn/Article/details/gtxboweqpj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sufxvd.cn/Article/details/gtuzsbjqdf.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtvilekgax.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guannengcc.top/Article/details/gtvoaubepx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtqaeefddk.html

[T01] Kotlin：Hello World
来源：http://dali.redwolf501.top/Article/details/gttkbtqxmg.html

println("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtswssqtan.html

[T02] Kotlin：变量
来源：http://dali.0kj1m.cn/Article/details/gtuztgeqaw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.iojbl.cn/Article/details/gtdzmtkbau.html

[T03] Kotlin：字符串模板
来源：http://dali.gogol.net.cn/Article/details/gtkkimnbty.html

"值: $b"
来源：http://dali.c1oappe.top/Article/details/gtrcyanchs.html

[T04] Kotlin：空安全
来源：http://dali.xuetiantiany.cn/Article/details/gtrbizttgw.html

val n: String? = null;  n?.length
来源：http://dali.shuidangran.top/Article/details/gtuzpdsrea.html

[T05] Kotlin：when 表达式
来源：http://dali.snrcjt.cn/Article/details/gtorcwazzw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.havefunace.top/Article/details/gttsafxfyh.html

[T06] Kotlin：集合映射
来源：http://dali.cqqwz.cn/Article/details/gtyrikcjjq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.meibo888.top/Article/details/gtktojwgqg.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gtpkbvzikq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ybcxt.top/Article/details/gtqrzfjoml.html

[T08] Kotlin：数据类
来源：http://dali.sufxvd.cn/Article/details/gtskwmssom.html

data class User(val name: String, val age: Int)
来源：http://dali.wangdashe.top/Article/details/gtogybwoxx.html

[T09] Kotlin：扩展函数
来源：http://dali.feifeiyinyue.top/Article/details/gtytevoxdk.html

fun String.exclaim() = this + "!"
来源：http://dali.haohaochexian.top/Article/details/gtzxuqghbd.html

[T10] Kotlin：默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnukhizeq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.snrcjt.cn/Article/details/gttegafnkt.html

[T11] Kotlin：协程
来源：http://dali.zhiwuduotai.top/Article/details/gtvdezhljf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjimpvsb.html

[T12] Kotlin：解构声明
来源：http://dali.pycfn.com/Article/details/gtfryvyffp.html

val (a, b) = Pair(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gtkdhnozeq.html

[T13] Kotlin：只读 Map
来源：http://dali.shangyingyoupin.top/Article/details/gtsqusekvz.html

val m = mapOf("a" to 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzyvrzevu.html

[T14] Kotlin：循环
来源：http://dali.zhixingplan.top/Article/details/gtokfglhmq.html

for (i in 1..10) println(i)
来源：http://dali.hnqzz.top/Article/details/gtycrrhekt.html

[T15] Kotlin：接口
来源：http://dali.andypj.xyz/Article/details/gtujyusezo.html

interface Shape { fun area(): Double }
来源：http://dali.0kj1m.cn/Article/details/gtoodacdsc.html

[T16] Swift：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtesqobitw.html

print("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtieiurmxn.html

[T17] Swift：变量与常量
来源：http://dali.ppjwa.cn/Article/details/gtpypjnugc.html

var a = 1;  let b = 2
来源：http://dali.cdnleiting.top/Article/details/gtlliiujwr.html

[T18] Swift：字符串插值
来源：http://dali.cashguo.top/Article/details/gtpzmnfuus.html

"值: \(b)"
来源：http://dali.quarkkingdee.top/Article/details/gtsaewvylb.html

[T19] Swift：可选绑定
来源：http://dali.zhongyouzk.top/Article/details/gtiikvfjio.html

if let n = opt { print(n) }
来源：http://dali.daria6918.cn/Article/details/gtybkifgnu.html

[T20] Swift：数组操作
来源：http://dali.ydzc1.top/Article/details/gtzosqhexh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxeqbvzjo.html

[T21] Swift：遍历
来源：http://dali.0kj1m.cn/Article/details/gtyydheomt.html

for x in a { print(x) }
来源：http://dali.zhoulong.xyz/Article/details/gtuktvetzi.html

[T22] Swift：字典
来源：http://dali.zhixingplan.top/Article/details/gtwxiwmcdw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aibaodan.cn/Article/details/gtwjhbbhnt.html

[T23] Swift：函数
来源：http://dali.gzhubu.top/Article/details/gtqblxiccp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtilpjubzl.html

[T24] Swift：闭包
来源：http://dali.cqqwz.cn/Article/details/gtpihnshwt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sxryk.cn/Article/details/gthajdwxhv.html

[T25] Swift：结构体
来源：http://dali.yvedp.cn/Article/details/gtliqnuauk.html

struct P { var x: Int }
来源：http://dali.ybcxt.top/Article/details/gtlgrnyxvq.html

[T26] Swift：类与重写
来源：http://dali.jiagoushi.top/Article/details/gtwgkwzhtb.html

class A: Base { override func f() {} }
来源：http://dali.316326.xyz/Article/details/gtrdfpckqv.html

[T27] Swift：错误处理
来源：http://dali.zdqjudy.top/Article/details/gtpfbfawrw.html

do { try f() } catch { print(error) }
来源：http://dali.ehwqpu.com/Article/details/gtzbpbgvur.html

[T28] Swift：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtzkikzvms.html

enum Color { case red, green }
来源：http://dali.jiagoushi.top/Article/details/gtjheetaod.html

[T29] Swift：guard 提前返回
来源：http://dali.sweek.top/Article/details/gtrmdmdkwy.html

guard let x = opt else { return }
来源：http://dali.fzhhl.top/Article/details/gttqlvmsey.html

[T30] Swift：协议
来源：http://dali.jqgufenzy.top/Article/details/gtbxexsbpw.html

protocol Shape { func area() -> Double }
来源：http://dali.tian-w.cn/Article/details/gteuwddgjk.html

[T31] Lua：Hello World
来源：http://dali.yj20258888.top/Article/details/gtlkgdczza.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtvfyahwnu.html

[T32] Lua：局部变量
来源：http://dali.aizwys.cn/Article/details/gtjzapvfeh.html

local a = 1
来源：http://dali.haohaochexian.top/Article/details/gthykqmqez.html

[T33] Lua：表（数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtzluskqrp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.dashuyun.cn/Article/details/gtjtggxamt.html

[T34] Lua：遍历表
来源：http://dali.hnxiangtu.top/Article/details/gtwpimslqc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shzxlz.cn/Article/details/gtveavdfve.html

[T35] Lua：字典表
来源：http://dali.yueranfly.top/Article/details/gtrqueeofw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigufen.top/Article/details/gthikduefn.html

[T36] Lua：函数
来源：http://dali.shangyingyoupin.top/Article/details/gtyznixefp.html

function add(a, b) return a + b end
来源：http://dali.jiagoushi.top/Article/details/gtdpflskvb.html

[T37] Lua：字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gtvkfnmlgj.html

"a" .. "b"
来源：http://dali.jiagoushi.top/Article/details/gtxclhcfsr.html

[T38] Lua：条件
来源：http://dali.yj20258.top/Article/details/gtunlevats.html

if x > 0 then print("正") end
来源：http://dali.sysykeji.top/Article/details/gtdkjevidv.html

[T39] Lua：模式匹配
来源：http://dali.xylfe.cn/Article/details/gtmrhjnvgp.html

string.find(s, "%d+")
来源：http://dali.xziqi.cn/Article/details/gtttwfaipu.html

[T40] Lua：元表
来源：http://dali.gaohongyu789.top/Article/details/gthhclcnnm.html

setmetatable({}, { __index = base })
来源：http://dali.mhx1999.top/Article/details/gtdpwzawoa.html

[T41] Perl：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtlptinqdm.html

print "Hello\n";
来源：http://dali.yonumen.top/Article/details/gtxwvpqbuf.html

[T42] Perl：变量类型
来源：http://dali.cucudq.cn/Article/details/gtsrxajnzj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cheryme.top/Article/details/gtjoimmojk.html

[T43] Perl：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtgwumbkxe.html

"值: $a"
来源：http://dali.jqgfzy.top/Article/details/gtmksgmlho.html

[T44] Perl：条件
来源：http://dali.nanxinkj.top/Article/details/gteanmvilt.html

if ($a > 0) { print "正"; }
来源：http://dali.0kj1m.cn/Article/details/gtcletrten.html

[T45] Perl：数组遍历
来源：http://dali.ppjwa.cn/Article/details/gtrrwoaqmv.html

for my $x (@arr) { print $x; }
来源：http://dali.yanxiufei.cn/Article/details/gtboqmfpqj.html

[T46] Perl：哈希操作
来源：http://dali.havefunace.top/Article/details/gtvueizekp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.316326.xyz/Article/details/gtbeyqwfwe.html

[T47] Perl：正则捕获
来源：http://dali.aibaodan.cn/Article/details/gtyseubfhw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlclsdjan.html

[T48] Perl：正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gtdakfqblw.html

$s =~ s/old/new/g;
来源：http://dali.guannengcc.top/Article/details/gtmlpzffft.html

[T49] Perl：函数
来源：http://dali.jiagoushi.top/Article/details/gtawqeamoq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtmtrnskmg.html

[T50] Perl：逐行读文件
来源：http://dali.sweek.top/Article/details/gtqriqarak.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xuanzx.com/Article/details/gtnmiiyime.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gtehtwdmjd.html

[T51] Scala：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtkdytekyu.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gtuimycqpx.html

[T52] Scala：变量
来源：http://dali.yangfankeji.com/Article/details/gtohhwhzbr.html

val a = 1;  var b = 2
来源：http://dali.pycfn.com/Article/details/gtlphqiyda.html

[T53] Scala：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtddbsxsag.html

s"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gtvsxxzsko.html

[T54] Scala：集合映射
来源：http://dali.xuetiantiany.cn/Article/details/gtrgiinlfz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tian-w.cn/Article/details/gtytpwthoa.html

[T55] Scala：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gtsmpniovo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sysykeji.top/Article/details/gtvkpjdgkd.html

[T56] Scala：样例类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpjexdjv.html

case class User(name: String, age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gtrezlicfd.html

[T57] Scala：模式匹配
来源：http://dali.xinyue.icu/Article/details/gtjcyepuxp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhengqikj.top/Article/details/gtvodsdlym.html

[T58] Scala：函数定义
来源：http://dali.cucudq.cn/Article/details/gthnlkkjyf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xuetiantiany.cn/Article/details/gtmqqaulwm.html

[T59] Scala：循环
来源：http://dali.hfpthk.cn/Article/details/gtnmgirtuf.html

for (i <- 1 to 10) println(i)
来源：http://dali.jianghu66.top/Article/details/gtutgjxykk.html

[T60] Scala：折叠
来源：http://dali.guowangkeji.top/Article/details/gtpxkiwzus.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xinyue.icu/Article/details/gtpgctikwk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtwtmyrafs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cucudq.cn/Article/details/gtjnzidjmf.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtfuxmspck.html

[U01] Py：创建虚拟环境
来源：http://dali.yvedp.cn/Article/details/gtsixmpphn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.316326.xyz/Article/details/gtuvfsxhsx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cdnleiting.top/Article/details/gtvkmvmeoj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jlsjyb.cn/Article/details/gtiyhdvjys.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgufenzy.top/Article/details/gthzsykiks.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sweek.top/Article/details/gtvzjrjyur.html

[U04] Py：变量调试打印
来源：http://dali.yuxming.cn/Article/details/gtsnrnhhgc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.kuanghao11.cn/Article/details/gtrihnmktt.html

[U05] Py：列表去重且保序
来源：http://dali.jinqigufen.top/Article/details/gtclfiqxzd.html

list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gtsblzmeim.html

[U06] Py：合并两个字典
来源：http://dali.sxryk.cn/Article/details/gtltkkqixq.html

{**a, **b}
来源：http://dali.shangyingyoupin.top/Article/details/gtesxcytzz.html

[U07] Py：反转字典键值
来源：http://dali.jyoumei.cn/Article/details/gtzepnlttk.html

{v: k for k, v in d.items()}
来源：http://dali.gotoacloud.top/Article/details/gttedqskos.html

[U08] Py：展平二维列表
来源：http://dali.cheryme.top/Article/details/gtpbjpwfnf.html

[y for x in nested for y in x]
来源：http://dali.yj20258888.top/Article/details/gtwhyxjnww.html

[U09] Py：字典取最大值的键
来源：http://dali.snrcjt.cn/Article/details/gtokniafuw.html

max(d, key=d.get)
来源：http://dali.cheryme.top/Article/details/gtjbextjqk.html

[U10] Py：按值排序字典
来源：http://dali.smart0.xyz/Article/details/gthglwufxs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gaohongyu789.top/Article/details/gtohxkmxer.html

[U11] Py：生成器表达式
来源：http://dali.chenzaomai.com/Article/details/gthdpcghvf.html

(x * 2 for x in arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtiqhlvdxy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.guowangkeji.top/Article/details/gtoafqaaee.html

Counter(arr).most_common(3)
来源：http://dali.fzhhl.top/Article/details/gtqfqbtcxp.html

[U13] Py：固定长度队列
来源：http://dali.shuidangran.top/Article/details/gttmmwmrbe.html

deque(maxlen=10)
来源：http://dali.pengpengdd.cyou/Article/details/gtbobfmhye.html

[U14] Py：分组收集到列表
来源：http://dali.meibo888.top/Article/details/gtkkidfhuw.html

defaultdict(list)
来源：http://dali.zdqjudy.top/Article/details/gtfragfgvn.html

[U15] Py：高精度计时
来源：http://dali.ivvv.top/Article/details/gtiaagpzio.html

t = time.perf_counter()
来源：http://dali.dianchejie.cn/Article/details/gtbtnhjrmu.html

[U16] Py：命令行参数解析
来源：http://dali.jianghu66.top/Article/details/gtbqnrgrlv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.vqdsnc.cn/Article/details/gttabjlddq.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivbnbear.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daxiang520.top/Article/details/gttzudthpt.html

[U18] Py：预编译正则
来源：http://dali.xuetiantiany.cn/Article/details/gtsvhgwjrn.html

pat = re.compile(r"\d+")
来源：http://dali.quarkkingdee.top/Article/details/gtzbjapppe.html

[U19] Py：正则替换带回调
来源：http://dali.guowangkeji.top/Article/details/gtdtawhkau.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nwbrower.top/Article/details/gtromblcor.html

[U20] Py：缓存函数结果
来源：http://dali.xylfe.cn/Article/details/gtvnbkpquj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tian-w.cn/Article/details/gtdqdkzwpo.html

[U21] Py：自定义上下文管理器
来源：http://dali.c1oappe.top/Article/details/gtrpmzwpot.html

@contextlib.contextmanager
来源：http://dali.shangyingyoupin.top/Article/details/gtenbqphhe.html

[U22] Py：矩阵转置
来源：http://dali.redwolf501.top/Article/details/gtdxmyakxu.html

list(zip(*m))
来源：http://dali.gotoacloud.top/Article/details/gtgvuvxqgk.html

[U23] Py：分块读取大文件
来源：http://dali.cashguo.top/Article/details/gtxelszuwi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.0kj1m.cn/Article/details/gtvowickxx.html

[U24] Py：路径操作
来源：http://dali.xylfe.cn/Article/details/gtcbfdnakb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gtpadcqkfe.html

[U25] Py：CSV 按字典读
来源：http://dali.c1oappe.top/Article/details/gtvemwqdcs.html

csv.DictReader(f)
来源：http://dali.jqgfzy.top/Article/details/gtwzxeqxkv.html

[U26] Py：并发下载
来源：http://dali.cheryme.top/Article/details/gttvwskgsk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pengpengdd.cyou/Article/details/gtwlniiyit.html

[U27] Py：异步 HTTP
来源：http://dali.cucudq.cn/Article/details/gtstehxnre.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.0kj1m.cn/Article/details/gtiobunfyu.html

[U28] Py：类型别名
来源：http://dali.guannengcc.top/Article/details/gtsniamjml.html

UserId = int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxpmwxny.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gtrvznzuas.html

@property 与 @x.setter 配合
来源：http://dali.shangyingyoupin.top/Article/details/gtanzkwfhl.html

[U30] Py：数据类
来源：http://dali.hongshengwenyu.top/Article/details/gtcydqqxdz.html

@dataclass(slots=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtwbonvzqp.html

[U31] Py：单测
来源：http://dali.jinghuilouyu.cn/Article/details/gtjthjxkhn.html

python -m pytest -q
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcsvneav.html

[U32] Py：代码格式化
来源：http://dali.yongpay.top/Article/details/gtgeeywqtg.html

ruff format . && ruff check --fix .
来源：http://dali.fengsongda.top/Article/details/gtazcnjnos.html

[U33] Py：打包发布
来源：http://dali.kuanghao11.cn/Article/details/gtswnbeyha.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenlongwang.top/Article/details/gtrnaqpcvr.html

[U34] Py：判断编码
来源：http://dali.jinyuanbaomall.cn/Article/details/gttndcmnkx.html

chardet.detect(raw)
来源：http://dali.zhixingplan.top/Article/details/gtffxncuby.html

[U35] Py：发送邮件
来源：http://dali.ppjwa.cn/Article/details/gtinzfnywp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.daria6918.cn/Article/details/gtkaccmeiv.html

[U36] Py：定时任务
来源：http://dali.jyoumei.cn/Article/details/gtedbunkjr.html

schedule.every(10).minutes.do(job)
来源：http://dali.sufxvd.cn/Article/details/gtbjfzpgbn.html

[U37] Py：读写 Excel
来源：http://dali.yj20258.top/Article/details/gtthxouxhb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhoulong.xyz/Article/details/gtkqgfssva.html

[U38] Py：获取脚本所在目录
来源：http://dali.fzhhl.top/Article/details/gtaduhzdmf.html

Path(__file__).resolve().parent
来源：http://dali.chenjidiqi.icu/Article/details/gtezymgson.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhongyouzk.top/Article/details/gttyoktijp.html

sys.stdout.isatty()
来源：http://dali.jqgufenzy.top/Article/details/gtpnssymfx.html

[U40] Py：打印到标准错误
来源：http://dali.aizwys.cn/Article/details/gtvqsiuthl.html

print("err", file=sys.stderr)
来源：http://dali.daxiang520.top/Article/details/gtkplhponc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.wangdashe.top/Article/details/gtbaupmeas.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yvedp.cn/Article/details/gtemtvotvm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gogol.net.cn/Article/details/gtdfkiygbj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nanxuanxn.top/Article/details/gthcryoama.html

[U43] PHP：声明命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gtfwrrjmjj.html

namespace App\Http;
来源：http://dali.xziqi.cn/Article/details/gtutxfvfcf.html

[U44] PHP：开启严格类型
来源：http://dali.mhx1999.top/Article/details/gtssceoqqm.html

declare(strict_types=1);
来源：http://dali.jianghu66.top/Article/details/gtwaaxzbyl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.9152youxi.cn/Article/details/gtvzpxmhtc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gtpnvuqudp.html

[U46] PHP：可空类型
来源：http://dali.aizwys.cn/Article/details/gtxajmlbvx.html

?string $name = null
来源：http://dali.xuanzx.com/Article/details/gthwlpzkli.html

[U47] PHP：联合类型
来源：http://dali.havefunace.top/Article/details/gtaunjivpn.html

int|string $id
来源：http://dali.kuanghao11.cn/Article/details/gtfvxarwiz.html

[U48] PHP：纯枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtedxjeffr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yvedp.cn/Article/details/gtcjagnexa.html

[U49] PHP：只读属性
来源：http://dali.yonumen.top/Article/details/gtsnirluhc.html

public readonly string $name
来源：http://dali.yangfankeji.com/Article/details/gtlrctfgdo.html

[U50] PHP：构造器属性提升
来源：http://dali.yuxming.cn/Article/details/gtvjxuyuve.html

public function __construct(private int $id) {}
来源：http://dali.hysaishi.cn/Article/details/gttqmzvmsf.html

[U51] PHP：数组解构
来源：http://dali.tian-w.cn/Article/details/gtofkrvgng.html

[$a, $b] = $arr;
来源：http://dali.jinqigfzy.top/Article/details/gtgxqeoyne.html

[U52] PHP：箭头函数
来源：http://dali.gogol.net.cn/Article/details/gtjmrtvkyb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdiehnwfq.html

[U53] PHP：空合并运算符
来源：http://dali.daxiang520.top/Article/details/gtwwersoez.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinghuilouyu.cn/Article/details/gtudfjqsrn.html

[U54] PHP：空安全调用
来源：http://dali.ppjwa.cn/Article/details/gtzdlnfgik.html

$obj?->method()
来源：http://dali.yj202588.top/Article/details/gtybhlaxbz.html

[U55] PHP：match 表达式
来源：http://dali.daxiang520.top/Article/details/gtivfkbglo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hywenlv.cn/Article/details/gtybazqmzc.html

[U56] PHP：命名参数
来源：http://dali.shuidangran.top/Article/details/gtpxkururq.html

f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtlulfxgjz.html

[U57] PHP：字符串插值
来源：http://dali.yonumen.top/Article/details/gtpdcnzfif.html

"值: {$a}"
来源：http://dali.yanxiufei.cn/Article/details/gtphktmutm.html

[U58] PHP：数组三件套
来源：http://dali.guannengcc.top/Article/details/gtbpunuqni.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.snrcjt.cn/Article/details/gtgvsaregf.html

[U59] PHP：自定义排序
来源：http://dali.sxryk.cn/Article/details/gtuyoouqbd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dianchejie.cn/Article/details/gtamqploij.html

[U60] PHP：JSON 编解码
来源：http://dali.aibaodan.cn/Article/details/gttdqnpkho.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hfpthk.cn/Article/details/gtdiwzwkxz.html

[U61] PHP：正则
来源：http://dali.zycfv.cn/Article/details/gtdjzgveck.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gtqnucsjvc.html

[U62] PHP：日期对象
来源：http://dali.jqgfzy.top/Article/details/gtrybpdjdf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.nwbrower.top/Article/details/gtjllkjejo.html

[U63] PHP：文件读写
来源：http://dali.jqgfzy.top/Article/details/gtqipqvjqp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sufxvd.cn/Article/details/gtizexwdrk.html

[U64] PHP：目录遍历
来源：http://dali.xziqi.cn/Article/details/gtofluhxly.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gzhubu.top/Article/details/gtbshzceaw.html

[U65] PHP：会话
来源：http://dali.nanxinkj.top/Article/details/gtxzaoalyj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtximzdwlg.html

[U66] PHP：设置 Cookie
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetlzitcf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yj20258.top/Article/details/gtzmvyvlbk.html

[U67] PHP：处理文件上传
来源：http://dali.zdqjudy.top/Article/details/gttwtesuji.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.fzhhl.top/Article/details/gtqleovczf.html

[U68] PHP：PDO 连接
来源：http://dali.smart0.xyz/Article/details/gtptjdwvjs.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinqigufen.top/Article/details/gtzpltwkby.html

[U69] PHP：PDO 预处理
来源：http://dali.jyoumei.cn/Article/details/gtwjcveisn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gaohongyu789.top/Article/details/gtmdftviys.html

[U70] PHP：PDO 事务
来源：http://dali.fengsongda.top/Article/details/gtruyeobfj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhoulong.xyz/Article/details/gtledtwxnm.html

[U71] PHP：抛出异常
来源：http://dali.xuanzx.com/Article/details/gtxfoymahq.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinqigfzy.top/Article/details/gtucadsooo.html

[U72] PHP：写错误日志
来源：http://dali.nanxinkj.top/Article/details/gtyfrdtpgp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenzaomai.com/Article/details/gtzembtnzk.html

[U73] PHP：读取 ini 配置
来源：http://dali.tian-w.cn/Article/details/gtfwttkjvm.html

parse_ini_file("config.ini", true)
来源：http://dali.dianchejie.cn/Article/details/gtcndhaqvl.html

[U74] PHP：读取环境变量
来源：http://dali.hnqzz.top/Article/details/gtxboagkyk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xuetiantiany.cn/Article/details/gtzyicizqc.html

[U75] PHP：依赖注入
来源：http://dali.chenlongwang.top/Article/details/gtqwrucpxk.html

composer require psr/container
来源：http://dali.chenjidiqi.icu/Article/details/gtiwiovusr.html

[U76] PHP：简单路由
来源：http://dali.hfpthk.cn/Article/details/gtcqukjtsq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yonumen.top/Article/details/gtelwurdhx.html

[U77] PHP：模板渲染
来源：http://dali.zhengqikj.top/Article/details/gtnuvkbjdq.html

composer require twig/twig
来源：http://dali.guowangkeji.top/Article/details/gtmhtiovgm.html

[U78] PHP：单元测试
来源：http://dali.nanxuanxn.top/Article/details/gtwodhwzoz.html

composer require --dev phpunit/phpunit
来源：http://dali.tanke756.top/Article/details/gttowrabbs.html


<!-- 参考信息 -->