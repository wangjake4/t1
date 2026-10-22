代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gturlmhxom.html

[S53] C++：移动语义
来源：http://dali.tian-w.cn/Article/details/gtdsebhxll.html

std::vector<int> w = std::move(v);
来源：http://dali.wangshuangyany.cn/Article/details/gtfnlxmjde.html

[S54] C++：异常处理
来源：http://dali.tian-w.cn/Article/details/gtwwoybzwm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtpdzekfyo.html

[S55] C++：结构化绑定
来源：http://dali.fzhhl.top/Article/details/gtjtwtskpl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gteoymtnnw.html

[S56] C++：optional
来源：http://dali.wangshuangyany.cn/Article/details/gthmupvsac.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tanke756.top/Article/details/gtjmluryvv.html

[S57] C++：编译期常量
来源：http://dali.shangyingyoupin.top/Article/details/gtftuxqcff.html

constexpr int N = 10;
来源：http://dali.wangdashe.top/Article/details/gtnxvdmfvy.html

[S58] C++：命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gtaijepjeh.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxinkj.top/Article/details/gtuqgpyyby.html

[S59] C++：静态断言
来源：http://dali.yangfankeji.com/Article/details/gtvkahppjz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pycfn.com/Article/details/gthldrpibz.html

[S60] C++：遍历并删除元素
来源：http://dali.yongpay.top/Article/details/gtkvjaohfp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gtkbbnhsyz.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyhwulqy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tian-w.cn/Article/details/gthktysxme.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtudmrqkrk.html

[T01] Kotlin：Hello World
来源：http://dali.gzhubu.top/Article/details/gtmokqzbeu.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtckflvjzl.html

[T02] Kotlin：变量
来源：http://dali.yuanzhike.top/Article/details/gthoawyfdy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangtech.top/Article/details/gtbikokuhj.html

[T03] Kotlin：字符串模板
来源：http://dali.zdqjudy.top/Article/details/gtwzfxppmi.html

"值: $b"
来源：http://dali.bjfxy.top/Article/details/gtzquzhrsn.html

[T04] Kotlin：空安全
来源：http://dali.sufxvd.cn/Article/details/gtrbyzykqs.html

val n: String? = null;  n?.length
来源：http://dali.jlsjyb.cn/Article/details/gtxdwjwoei.html

[T05] Kotlin：when 表达式
来源：http://dali.shzxlz.cn/Article/details/gtlyposirf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.meibo888.top/Article/details/gtrqczuvue.html

[T06] Kotlin：集合映射
来源：http://dali.ivvv.top/Article/details/gtohdaldhh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.wangdashe.top/Article/details/gtiqdbnpur.html

[T07] Kotlin：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gtexkbjhlv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.bjfxy.top/Article/details/gtkehlixez.html

[T08] Kotlin：数据类
来源：http://dali.yueranfly.top/Article/details/gtvzhmajtf.html

data class User(val name: String, val age: Int)
来源：http://dali.guannengcc.top/Article/details/gtipgfxspb.html

[T09] Kotlin：扩展函数
来源：http://dali.hongshengwenyu.top/Article/details/gtmleskqsy.html

fun String.exclaim() = this + "!"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdnayqwo.html

[T10] Kotlin：默认参数
来源：http://dali.hysaishi.cn/Article/details/gtbpzhhjlv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daxiang520.top/Article/details/gtrqwuhrxh.html

[T11] Kotlin：协程
来源：http://dali.xuanzx.com/Article/details/gtatvyhyoa.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fengsongda.top/Article/details/gtisfnqwko.html

[T12] Kotlin：解构声明
来源：http://dali.cucudq.cn/Article/details/gtfbfzndkk.html

val (a, b) = Pair(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulzazycv.html

[T13] Kotlin：只读 Map
来源：http://dali.sweek.top/Article/details/gtjxuazscr.html

val m = mapOf("a" to 1)
来源：http://dali.smart0.xyz/Article/details/gtglxpwrpv.html

[T14] Kotlin：循环
来源：http://dali.hongshengwenyu.top/Article/details/gtsmspzdmy.html

for (i in 1..10) println(i)
来源：http://dali.iojbl.cn/Article/details/gtdzcyffpo.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcsnjgaf.html

interface Shape { fun area(): Double }
来源：http://dali.smart0.xyz/Article/details/gtdsyhnydu.html

[T16] Swift：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtesnwwnzn.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtsgtfufih.html

[T17] Swift：变量与常量
来源：http://dali.9152youxi.cn/Article/details/gtyliexcxu.html

var a = 1;  let b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabzfthpm.html

[T18] Swift：字符串插值
来源：http://dali.birdmap.top/Article/details/gttbdikuas.html

"值: \(b)"
来源：http://dali.hnxiangtu.top/Article/details/gtorcvaczu.html

[T19] Swift：可选绑定
来源：http://dali.guannengcc.top/Article/details/gtalrdlaos.html

if let n = opt { print(n) }
来源：http://dali.haohaochexian.top/Article/details/gtskashjio.html

[T20] Swift：数组操作
来源：http://dali.haohaochexian.top/Article/details/gtbbeiitat.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.redwolf501.top/Article/details/gthdqopvnh.html

[T21] Swift：遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtciliqhxd.html

for x in a { print(x) }
来源：http://dali.zdqjudy.top/Article/details/gtregwpgbn.html

[T22] Swift：字典
来源：http://dali.jinqigfzy.top/Article/details/gtnmfjmjok.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.mhx1999.top/Article/details/gtbexdhdee.html

[T23] Swift：函数
来源：http://dali.ydzc1.top/Article/details/gtshwjzvsx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.dashuyun.cn/Article/details/gtrqlwhpne.html

[T24] Swift：闭包
来源：http://dali.quarkkingdee.top/Article/details/gtxpqpyztc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj202588.top/Article/details/gtrktwzvku.html

[T25] Swift：结构体
来源：http://dali.mhx1999.top/Article/details/gtzagadnnw.html

struct P { var x: Int }
来源：http://dali.shuidangran.top/Article/details/gtltdualmv.html

[T26] Swift：类与重写
来源：http://dali.tianlin.xyz/Article/details/gtrvogsupt.html

class A: Base { override func f() {} }
来源：http://dali.redwolf501.top/Article/details/gtcongcdlw.html

[T27] Swift：错误处理
来源：http://dali.chenlongwang.top/Article/details/gthefogdrz.html

do { try f() } catch { print(error) }
来源：http://dali.zhiwuduotai.top/Article/details/gtlwhoqzwh.html

[T28] Swift：枚举
来源：http://dali.fzhhl.top/Article/details/gtwoifwabi.html

enum Color { case red, green }
来源：http://dali.yonumen.top/Article/details/gttoaxyhlk.html

[T29] Swift：guard 提前返回
来源：http://dali.ydzc1.top/Article/details/gtlzjlxqli.html

guard let x = opt else { return }
来源：http://dali.havefunace.top/Article/details/gtkagcwqep.html

[T30] Swift：协议
来源：http://dali.aizwys.cn/Article/details/gtwsbrpnsw.html

protocol Shape { func area() -> Double }
来源：http://dali.sysykeji.top/Article/details/gtykyvcrmm.html

[T31] Lua：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtjiupcntz.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtvcdqzkox.html

[T32] Lua：局部变量
来源：http://dali.xziqi.cn/Article/details/gtmlqtcznk.html

local a = 1
来源：http://dali.chenlongwang.top/Article/details/gtrnvbebcz.html

[T33] Lua：表（数组）
来源：http://dali.iojbl.cn/Article/details/gtkspuiwoj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenjidiqi.icu/Article/details/gtqfaqfmcj.html

[T34] Lua：遍历表
来源：http://dali.snrcjt.cn/Article/details/gtzddzajjl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cucudq.cn/Article/details/gtvuriaheg.html

[T35] Lua：字典表
来源：http://dali.cqqwz.cn/Article/details/gtehbjanin.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zdqjudy.top/Article/details/gtgkudtffm.html

[T36] Lua：函数
来源：http://dali.shuidangran.top/Article/details/gtqbnncglb.html

function add(a, b) return a + b end
来源：http://dali.xylfe.cn/Article/details/gtruplnstt.html

[T37] Lua：字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gtvrfchjky.html

"a" .. "b"
来源：http://dali.yonumen.top/Article/details/gtjlykczdr.html

[T38] Lua：条件
来源：http://dali.jinqigufen.top/Article/details/gtbtgswzlf.html

if x > 0 then print("正") end
来源：http://dali.jyoumei.cn/Article/details/gtwfclcyly.html

[T39] Lua：模式匹配
来源：http://dali.cheryme.top/Article/details/gtmwtrsbwe.html

string.find(s, "%d+")
来源：http://dali.yongpay.top/Article/details/gtnxvxhbay.html

[T40] Lua：元表
来源：http://dali.jqgfzy.top/Article/details/gtcngmpkww.html

setmetatable({}, { __index = base })
来源：http://dali.yuanzhike.top/Article/details/gtoykyrprl.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpkzmrva.html

print "Hello\n";
来源：http://dali.cheryme.top/Article/details/gttbvgfxfe.html

[T42] Perl：变量类型
来源：http://dali.fzhhl.top/Article/details/gthvycpcbw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gzhubu.top/Article/details/gtkyljeegy.html

[T43] Perl：字符串插值
来源：http://dali.ydzc1.top/Article/details/gtnnikugvc.html

"值: $a"
来源：http://dali.zhiwuduotai.top/Article/details/gtsnerupkt.html

[T44] Perl：条件
来源：http://dali.ehwqpu.com/Article/details/gttwnglywt.html

if ($a > 0) { print "正"; }
来源：http://dali.yvedp.cn/Article/details/gttmbtpdtf.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhlygdro.html

for my $x (@arr) { print $x; }
来源：http://dali.chenzaomai.com/Article/details/gtuphiziyx.html

[T46] Perl：哈希操作
来源：http://dali.sysykeji.top/Article/details/gtgndacmrv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hammf.cn/Article/details/gtjjjpkakp.html

[T47] Perl：正则捕获
来源：http://dali.gogol.net.cn/Article/details/gtnsurtapt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj202588.top/Article/details/gtjevjpsgy.html

[T48] Perl：正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqlzeugj.html

$s =~ s/old/new/g;
来源：http://dali.andypj.xyz/Article/details/gtciujrcko.html

[T49] Perl：函数
来源：http://dali.zycfv.cn/Article/details/gtwqnbtzfg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtnaczerhg.html

[T50] Perl：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwknjouwm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuanzhike.top/Article/details/gtcxjdmbnh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.c1oappe.top/Article/details/gtmuchsygw.html

[T51] Scala：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtdnhyvftg.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gthpjkqpuj.html

[T52] Scala：变量
来源：http://dali.ivvv.top/Article/details/gtehneawwk.html

val a = 1;  var b = 2
来源：http://dali.jqgufenzy.top/Article/details/gtatyyabgx.html

[T53] Scala：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvdydqog.html

s"值: $b"
来源：http://dali.jqgfzy.top/Article/details/gtrgkmgtfy.html

[T54] Scala：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gtvsmfpntm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hnxiangtu.top/Article/details/gtitmwlvng.html

[T55] Scala：集合过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtdycfieem.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ybcxt.top/Article/details/gtdgjpgywp.html

[T56] Scala：样例类
来源：http://dali.yvedp.cn/Article/details/gthkivfrov.html

case class User(name: String, age: Int)
来源：http://dali.cashguo.top/Article/details/gtugrfkthu.html

[T57] Scala：模式匹配
来源：http://dali.sxryk.cn/Article/details/gtauomjqnp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cheryme.top/Article/details/gtlnckruyf.html

[T58] Scala：函数定义
来源：http://dali.tianlin.xyz/Article/details/gtlaiybagc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.9152youxi.cn/Article/details/gtvjdbbagn.html

[T59] Scala：循环
来源：http://dali.ehwqpu.com/Article/details/gtanhfizcr.html

for (i <- 1 to 10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtorlmnhra.html

[T60] Scala：折叠
来源：http://dali.sysykeji.top/Article/details/gtnzmnmyic.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xziqi.cn/Article/details/gtmxuvndao.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtmbliplii.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sufxvd.cn/Article/details/gtdkupzchk.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtlbepvuys.html

[U01] Py：创建虚拟环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfkxgjtr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yueranfly.top/Article/details/gtzzgpcejw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.pycfn.com/Article/details/gtqahjppum.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.aibaodan.cn/Article/details/gtchynespv.html

[U03] Py：加载 .env 配置
来源：http://dali.cheryme.top/Article/details/gtnqteggpl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gotoacloud.top/Article/details/gtsuveslcx.html

[U04] Py：变量调试打印
来源：http://dali.bjfxy.top/Article/details/gtmpviknbr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xylfe.cn/Article/details/gtncebiyxx.html

[U05] Py：列表去重且保序
来源：http://dali.redwolf501.top/Article/details/gtpfmixtzm.html

list(dict.fromkeys(arr))
来源：http://dali.hywenlv.cn/Article/details/gtbhnkbxib.html

[U06] Py：合并两个字典
来源：http://dali.chenzaomai.com/Article/details/gtvoqzuuyx.html

{**a, **b}
来源：http://dali.gaohongyu789.top/Article/details/gtoamcwnjt.html

[U07] Py：反转字典键值
来源：http://dali.nanxinkj.top/Article/details/gtnibmgfov.html

{v: k for k, v in d.items()}
来源：http://dali.wangshuangyany.cn/Article/details/gtmwpembma.html

[U08] Py：展平二维列表
来源：http://dali.guannengcc.top/Article/details/gtjtpiistv.html

[y for x in nested for y in x]
来源：http://dali.nanxuanxn.top/Article/details/gtjhlmatys.html

[U09] Py：字典取最大值的键
来源：http://dali.hywenlv.cn/Article/details/gtayltaeru.html

max(d, key=d.get)
来源：http://dali.yvedp.cn/Article/details/gtqdtyknha.html

[U10] Py：按值排序字典
来源：http://dali.wangdashe.top/Article/details/gtztgvlkis.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jiagoushi.top/Article/details/gthjhsoiax.html

[U11] Py：生成器表达式
来源：http://dali.cdnleiting.top/Article/details/gtcslaixkb.html

(x * 2 for x in arr)
来源：http://dali.chenzaomai.com/Article/details/gtwystzcmd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.bjfxy.top/Article/details/gtwqgtqsgy.html

Counter(arr).most_common(3)
来源：http://dali.mhx1999.top/Article/details/gtdrkeihsu.html

[U13] Py：固定长度队列
来源：http://dali.sufxvd.cn/Article/details/gtxecsfbiz.html

deque(maxlen=10)
来源：http://dali.wangshuangyany.cn/Article/details/gtzbqeavcs.html

[U14] Py：分组收集到列表
来源：http://dali.snrcjt.cn/Article/details/gtroghaofs.html

defaultdict(list)
来源：http://dali.yj20258888.top/Article/details/gtvsagrnox.html

[U15] Py：高精度计时
来源：http://dali.kuanghao11.cn/Article/details/gtrdlwmdpg.html

t = time.perf_counter()
来源：http://dali.cheryme.top/Article/details/gtvvzxmazt.html

[U16] Py：命令行参数解析
来源：http://dali.cucudq.cn/Article/details/gtmcmnenes.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jiagoushi.top/Article/details/gtrarztcti.html

[U17] Py：初始化日志
来源：http://dali.cdnleiting.top/Article/details/gtazigsvix.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jianghu66.top/Article/details/gtzixakahi.html

[U18] Py：预编译正则
来源：http://dali.hnqzz.top/Article/details/gteekuxgit.html

pat = re.compile(r"\d+")
来源：http://dali.jlsjyb.cn/Article/details/gtkduabnyn.html

[U19] Py：正则替换带回调
来源：http://dali.hysaishi.cn/Article/details/gtgsvnqzsw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yanxiufei.cn/Article/details/gtludebkmn.html

[U20] Py：缓存函数结果
来源：http://dali.hfpthk.cn/Article/details/gtwwsibiba.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hnqzz.top/Article/details/gtvnerdkhd.html

[U21] Py：自定义上下文管理器
来源：http://dali.xziqi.cn/Article/details/gttzmxzaat.html

@contextlib.contextmanager
来源：http://dali.ppjwa.cn/Article/details/gtbuozlpug.html

[U22] Py：矩阵转置
来源：http://dali.gotoacloud.top/Article/details/gtwxqeqxtt.html

list(zip(*m))
来源：http://dali.sweek.top/Article/details/gthlheibvu.html

[U23] Py：分块读取大文件
来源：http://dali.daria6918.cn/Article/details/gtkvqumnzl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.andypj.xyz/Article/details/gtzztasdxi.html

[U24] Py：路径操作
来源：http://dali.shangyingyoupin.top/Article/details/gtpcsevbji.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yanxiufei.cn/Article/details/gtwcliudbu.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gtzdojjcns.html

csv.DictReader(f)
来源：http://dali.hongshengwenyu.top/Article/details/gtwntrzuyh.html

[U26] Py：并发下载
来源：http://dali.feifeiyinyue.top/Article/details/gtloancfac.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.daxiang520.top/Article/details/gterfbtdyo.html

[U27] Py：异步 HTTP
来源：http://dali.hnqzz.top/Article/details/gtdwdklwse.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.dianchejie.cn/Article/details/gtqgpjxbzj.html

[U28] Py：类型别名
来源：http://dali.jinghuilouyu.cn/Article/details/gtvoowpacr.html

UserId = int
来源：http://dali.tanke756.top/Article/details/gtgrnulbzo.html

[U29] Py：属性校验
来源：http://dali.ybcxt.top/Article/details/gtfanfpzkn.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gtymakmzxr.html

[U30] Py：数据类
来源：http://dali.yj202588.top/Article/details/gtdjigztmm.html

@dataclass(slots=True)
来源：http://dali.zhoulong.xyz/Article/details/gttpmfupop.html

[U31] Py：单测
来源：http://dali.yangfankeji.com/Article/details/gtvvezkhwl.html

python -m pytest -q
来源：http://dali.ydzc1.top/Article/details/gtkvjihyof.html

[U32] Py：代码格式化
来源：http://dali.hnqzz.top/Article/details/gtfrraifdn.html

ruff format . && ruff check --fix .
来源：http://dali.ehwqpu.com/Article/details/gtzzmweqez.html

[U33] Py：打包发布
来源：http://dali.gzhubu.top/Article/details/gtpqukuphc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauephwtw.html

[U34] Py：判断编码
来源：http://dali.jlsjyb.cn/Article/details/gtdjzifkpa.html

chardet.detect(raw)
来源：http://dali.hnqzz.top/Article/details/gtabarjrxf.html

[U35] Py：发送邮件
来源：http://dali.hongshengwenyu.top/Article/details/gthytpxrxw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jiagoushi.top/Article/details/gtdhwwbact.html

[U36] Py：定时任务
来源：http://dali.cqqwz.cn/Article/details/gtqfgywdgk.html

schedule.every(10).minutes.do(job)
来源：http://dali.svipenyu.cn/Article/details/gtwbahnskv.html

[U37] Py：读写 Excel
来源：http://dali.nwbrower.top/Article/details/gttomnuzhs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hnqzz.top/Article/details/gtiyymoudk.html

[U38] Py：获取脚本所在目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbxbsene.html

Path(__file__).resolve().parent
来源：http://dali.316326.xyz/Article/details/gtiwfifkbj.html

[U39] Py：判断是否在交互环境
来源：http://dali.sufxvd.cn/Article/details/gtraiaskpb.html

sys.stdout.isatty()
来源：http://dali.zhoulong.xyz/Article/details/gtnxfjzxdi.html

[U40] Py：打印到标准错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtairoikam.html

print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gtcmlzweux.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdxzegra.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhongyouzk.top/Article/details/gtfueulmhu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zycfv.cn/Article/details/gtgucaibou.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ehwqpu.com/Article/details/gtspwllyly.html

[U43] PHP：声明命名空间
来源：http://dali.316326.xyz/Article/details/gtwvhxazfa.html

namespace App\Http;
来源：http://dali.cashguo.top/Article/details/gtppdiueni.html

[U44] PHP：开启严格类型
来源：http://dali.quarkkingdee.top/Article/details/gtsytuhtdc.html

declare(strict_types=1);
来源：http://dali.andypj.xyz/Article/details/gthvcxpowu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgenpyxq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtxerlesjx.html

[U46] PHP：可空类型
来源：http://dali.316326.xyz/Article/details/gtlvsnynyz.html

?string $name = null
来源：http://dali.gotoacloud.top/Article/details/gtdbcqiubz.html

[U47] PHP：联合类型
来源：http://dali.zycfv.cn/Article/details/gtatqsanxl.html

int|string $id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvlkphmx.html

[U48] PHP：纯枚举
来源：http://dali.pycfn.com/Article/details/gturdwawla.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sufxvd.cn/Article/details/gtackxqmom.html

[U49] PHP：只读属性
来源：http://dali.ybcxt.top/Article/details/gtgefoopyi.html

public readonly string $name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbocdrhwo.html

[U50] PHP：构造器属性提升
来源：http://dali.cucudq.cn/Article/details/gthsxcmpum.html

public function __construct(private int $id) {}
来源：http://dali.sufxvd.cn/Article/details/gtljhxrton.html

[U51] PHP：数组解构
来源：http://dali.wangdashe.top/Article/details/gtwbdxrunb.html

[$a, $b] = $arr;
来源：http://dali.sysykeji.top/Article/details/gtrhdyjois.html

[U52] PHP：箭头函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtliimzemc.html

$double = fn($x) => $x * 2;
来源：http://dali.iojbl.cn/Article/details/gtvdfrqccg.html

[U53] PHP：空合并运算符
来源：http://dali.9152youxi.cn/Article/details/gtglxyldva.html

$v = $a ?? $b ?? "default";
来源：http://dali.birdmap.top/Article/details/gtxnbrmheh.html

[U54] PHP：空安全调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazcqlnpg.html

$obj?->method()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgiiczyo.html

[U55] PHP：match 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtafhmrenv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj20258888.top/Article/details/gtayxflrds.html

[U56] PHP：命名参数
来源：http://dali.hfpthk.cn/Article/details/gtokdlntsj.html

f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gtawlkhret.html

[U57] PHP：字符串插值
来源：http://dali.pycfn.com/Article/details/gtuqewcqio.html

"值: {$a}"
来源：http://dali.wangdashe.top/Article/details/gtocxrzhiq.html

[U58] PHP：数组三件套
来源：http://dali.yongpay.top/Article/details/gtwxawbuhi.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.havefunace.top/Article/details/gtdxtmhkxd.html

[U59] PHP：自定义排序
来源：http://dali.jianghu66.top/Article/details/gtugztwqsr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gtifxgocmw.html

[U60] PHP：JSON 编解码
来源：http://dali.chenjidiqi.icu/Article/details/gtuwvwuvqt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtkvvnpqdu.html

[U61] PHP：正则
来源：http://dali.yvedp.cn/Article/details/gtfzgnovjo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gtfgjasvkm.html

[U62] PHP：日期对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuewvuqni.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.nwbrower.top/Article/details/gtoonpsiek.html

[U63] PHP：文件读写
来源：http://dali.c1oappe.top/Article/details/gtbjbynmdi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xuetiantiany.cn/Article/details/gteifoznce.html

[U64] PHP：目录遍历
来源：http://dali.gogol.net.cn/Article/details/gtsmhomqvm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.andypj.xyz/Article/details/gtrebmmusg.html

[U65] PHP：会话
来源：http://dali.316326.xyz/Article/details/gtdiggxtzo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.daxiang520.top/Article/details/gtjbhksrrx.html

[U66] PHP：设置 Cookie
来源：http://dali.jqgfzy.top/Article/details/gtkqfnbyuy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sufxvd.cn/Article/details/gtpxqjpsyy.html

[U67] PHP：处理文件上传
来源：http://dali.cucudq.cn/Article/details/gtxhsvyjvk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hywenlv.cn/Article/details/gtzoxmjcqk.html

[U68] PHP：PDO 连接
来源：http://dali.chenzaomai.com/Article/details/gtsfxxuesa.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.haohaochexian.top/Article/details/gtqqnbjnqi.html

[U69] PHP：PDO 预处理
来源：http://dali.gotoacloud.top/Article/details/gtajfchtmu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sxryk.cn/Article/details/gtlguxijjq.html

[U70] PHP：PDO 事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmtppaaj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hnxiangtu.top/Article/details/gtvhumupbq.html

[U71] PHP：抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gtoglxdcwp.html

throw new RuntimeException("失败", 500);
来源：http://dali.yuanzhike.top/Article/details/gtpsszzdmp.html

[U72] PHP：写错误日志
来源：http://dali.svipenyu.cn/Article/details/gtoscrzxjj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnyqkfbhv.html

[U73] PHP：读取 ini 配置
来源：http://dali.yj202588.top/Article/details/gttrkxbczk.html

parse_ini_file("config.ini", true)
来源：http://dali.ivvv.top/Article/details/gtfbqfrqau.html

[U74] PHP：读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gtqywioleh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.0kj1m.cn/Article/details/gtwkzavrqf.html

[U75] PHP：依赖注入
来源：http://dali.zycfv.cn/Article/details/gtdzmkcuzp.html

composer require psr/container
来源：http://dali.c1oappe.top/Article/details/gtbnsciznd.html

[U76] PHP：简单路由
来源：http://dali.cucudq.cn/Article/details/gtrbbcmlsg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.316326.xyz/Article/details/gtwosfdcbb.html

[U77] PHP：模板渲染
来源：http://dali.hywenlv.cn/Article/details/gtzqtcxeye.html

composer require twig/twig
来源：http://dali.ybcxt.top/Article/details/gtmfegsvpi.html

[U78] PHP：单元测试
来源：http://dali.zhongyouzk.top/Article/details/gtscijowjj.html

composer require --dev phpunit/phpunit
来源：http://dali.aizwys.cn/Article/details/gtcrsrgerz.html


<!-- 参考信息 -->