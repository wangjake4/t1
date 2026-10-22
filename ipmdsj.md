代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.yangfankeji.com/Article/details/gtdbnobcrb.html

[S49] C++：写文件
来源：http://dali.jiagoushi.top/Article/details/gtfwzlkplc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ehwqpu.com/Article/details/gthnibujui.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gttsnnssev.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtrwjqfyzb.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gtsppwrwlg.html

static_cast<double>(a) / b
来源：http://dali.ydzc1.top/Article/details/gtewdorfvc.html

[S52] C++：const 与 noexcept
来源：http://dali.pycfn.com/Article/details/gtbtpldkbb.html

int size() const noexcept { return n_; }
来源：http://dali.nwbrower.top/Article/details/gtgzgulktc.html

[S53] C++：移动语义
来源：http://dali.jinghuilouyu.cn/Article/details/gtpadthawz.html

std::vector<int> w = std::move(v);
来源：http://dali.redwolf501.top/Article/details/gtjcvfgbti.html

[S54] C++：异常处理
来源：http://dali.yangfankeji.com/Article/details/gtjoppbhzk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dashuyun.cn/Article/details/gtjlxmfdpm.html

[S55] C++：结构化绑定
来源：http://dali.haohaochexian.top/Article/details/gtokxvbpjd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cdnleiting.top/Article/details/gtnnnlcsap.html

[S56] C++：optional
来源：http://dali.aibaodan.cn/Article/details/gtqnacvheb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfeiteuzz.html

[S57] C++：编译期常量
来源：http://dali.ehwqpu.com/Article/details/gtgiajvgry.html

constexpr int N = 10;
来源：http://dali.gaohongyu789.top/Article/details/gthsgvipea.html

[S58] C++：命名空间
来源：http://dali.yonumen.top/Article/details/gtsxotnicw.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuanzhike.top/Article/details/gtfjnzqnsq.html

[S59] C++：静态断言
来源：http://dali.c1oappe.top/Article/details/gtvmmwcyzk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sufxvd.cn/Article/details/gtrqvhbwmd.html

[S60] C++：遍历并删除元素
来源：http://dali.daria6918.cn/Article/details/gtgvobczoo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtmwpppybo.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtafyiyebo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jiagoushi.top/Article/details/gtupvdlwrj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtcamspxtx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtlxldehko.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gtxtsuwtzb.html

[T02] Kotlin：变量
来源：http://dali.yj20258.top/Article/details/gtuxpxnrsp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shuidangran.top/Article/details/gtorqqzdjx.html

[T03] Kotlin：字符串模板
来源：http://dali.zhengqikj.top/Article/details/gtketaqzoy.html

"值: $b"
来源：http://dali.aizwys.cn/Article/details/gtdrrvpznx.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gtxetfqqzf.html

val n: String? = null;  n?.length
来源：http://dali.aizwys.cn/Article/details/gtmtjqsnoq.html

[T05] Kotlin：when 表达式
来源：http://dali.kuanghao11.cn/Article/details/gtkgnsmjga.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.iojbl.cn/Article/details/gtyvpxskxk.html

[T06] Kotlin：集合映射
来源：http://dali.cheryme.top/Article/details/gtrgxvhaww.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.birdmap.top/Article/details/gtattcgoan.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtwiqlkqno.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cheryme.top/Article/details/gtkzeaejqj.html

[T08] Kotlin：数据类
来源：http://dali.jinqigufen.top/Article/details/gtxwbjyeth.html

data class User(val name: String, val age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gtjaljeyqt.html

[T09] Kotlin：扩展函数
来源：http://dali.nwbrower.top/Article/details/gtjmahqdzp.html

fun String.exclaim() = this + "!"
来源：http://dali.mhx1999.top/Article/details/gtkhvkkvdp.html

[T10] Kotlin：默认参数
来源：http://dali.yanxiufei.cn/Article/details/gtcgxeygql.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ppjwa.cn/Article/details/gtokkpxgrm.html

[T11] Kotlin：协程
来源：http://dali.yuxming.cn/Article/details/gtfhzsnyou.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tian-w.cn/Article/details/gtgpspdbye.html

[T12] Kotlin：解构声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkceqsrtg.html

val (a, b) = Pair(1, 2)
来源：http://dali.meibo888.top/Article/details/gthpbfigtl.html

[T13] Kotlin：只读 Map
来源：http://dali.xziqi.cn/Article/details/gtledrffto.html

val m = mapOf("a" to 1)
来源：http://dali.yanxiufei.cn/Article/details/gtayirxkgj.html

[T14] Kotlin：循环
来源：http://dali.guannengcc.top/Article/details/gtvwjxwxlu.html

for (i in 1..10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gtozeroqoy.html

[T15] Kotlin：接口
来源：http://dali.tian-w.cn/Article/details/gtocswbrvq.html

interface Shape { fun area(): Double }
来源：http://dali.gotoacloud.top/Article/details/gtvltcvetc.html

[T16] Swift：Hello World
来源：http://dali.yj20258888.top/Article/details/gtnggsenlt.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtkxahfsra.html

[T17] Swift：变量与常量
来源：http://dali.xylfe.cn/Article/details/gtgpmltznv.html

var a = 1;  let b = 2
来源：http://dali.dianchejie.cn/Article/details/gtqhbbgaex.html

[T18] Swift：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gtlqlfsmpg.html

"值: \(b)"
来源：http://dali.jyoumei.cn/Article/details/gtcrhevlge.html

[T19] Swift：可选绑定
来源：http://dali.zhoulong.xyz/Article/details/gtunyoqciv.html

if let n = opt { print(n) }
来源：http://dali.quarkkingdee.top/Article/details/gtymgmjold.html

[T20] Swift：数组操作
来源：http://dali.yonumen.top/Article/details/gtqcwlcxvq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zycfv.cn/Article/details/gtrlgocpbd.html

[T21] Swift：遍历
来源：http://dali.quarkkingdee.top/Article/details/gtxkkjrhyf.html

for x in a { print(x) }
来源：http://dali.pengpengdd.cyou/Article/details/gtrleqwzou.html

[T22] Swift：字典
来源：http://dali.yonumen.top/Article/details/gtghsmpjoq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jyoumei.cn/Article/details/gtptkjwetw.html

[T23] Swift：函数
来源：http://dali.shangyingyoupin.top/Article/details/gtjenohhwj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jianghu66.top/Article/details/gtcnmcqqxx.html

[T24] Swift：闭包
来源：http://dali.ybcxt.top/Article/details/gtwhmdynrz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtwvsfidfj.html

[T25] Swift：结构体
来源：http://dali.iojbl.cn/Article/details/gtmsuzkeqo.html

struct P { var x: Int }
来源：http://dali.jqgfzy.top/Article/details/gtztememlg.html

[T26] Swift：类与重写
来源：http://dali.nwbrower.top/Article/details/gtgjdwjkbj.html

class A: Base { override func f() {} }
来源：http://dali.cqqwz.cn/Article/details/gtuanaiqub.html

[T27] Swift：错误处理
来源：http://dali.ybcxt.top/Article/details/gtneeoxllm.html

do { try f() } catch { print(error) }
来源：http://dali.shzxlz.cn/Article/details/gteiquzejm.html

[T28] Swift：枚举
来源：http://dali.hysaishi.cn/Article/details/gtvhweolug.html

enum Color { case red, green }
来源：http://dali.jinqigufen.top/Article/details/gthjigcduf.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxoafunj.html

guard let x = opt else { return }
来源：http://dali.jlsjyb.cn/Article/details/gtfagmyxqf.html

[T30] Swift：协议
来源：http://dali.mhx1999.top/Article/details/gtbhaovyni.html

protocol Shape { func area() -> Double }
来源：http://dali.bjfxy.top/Article/details/gtarxrivkf.html

[T31] Lua：Hello World
来源：http://dali.fengsongda.top/Article/details/gtwmksmwpn.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gtmvbivevi.html

[T32] Lua：局部变量
来源：http://dali.svipenyu.cn/Article/details/gtvjhlqlfm.html

local a = 1
来源：http://dali.zhiwuduotai.top/Article/details/gtltanicnr.html

[T33] Lua：表（数组）
来源：http://dali.havefunace.top/Article/details/gtcfwvoxwx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.havefunace.top/Article/details/gtmnlqcnbi.html

[T34] Lua：遍历表
来源：http://dali.ydzc1.top/Article/details/gtlxldlrum.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangdashe.top/Article/details/gtuhrwtcyh.html

[T35] Lua：字典表
来源：http://dali.yvedp.cn/Article/details/gttlspvwas.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cucudq.cn/Article/details/gtcyovnhyp.html

[T36] Lua：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoypbdwrh.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgpldpot.html

[T37] Lua：字符串拼接
来源：http://dali.cheryme.top/Article/details/gtdiljkcdy.html

"a" .. "b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpltnnwrd.html

[T38] Lua：条件
来源：http://dali.xylfe.cn/Article/details/gtaxmipqbx.html

if x > 0 then print("正") end
来源：http://dali.daxiang520.top/Article/details/gtscyipaxb.html

[T39] Lua：模式匹配
来源：http://dali.dianchejie.cn/Article/details/gtpjnsljtb.html

string.find(s, "%d+")
来源：http://dali.jiagoushi.top/Article/details/gtjghibpsk.html

[T40] Lua：元表
来源：http://dali.feifeiyinyue.top/Article/details/gtqfuznvfs.html

setmetatable({}, { __index = base })
来源：http://dali.pycfn.com/Article/details/gtepclqedw.html

[T41] Perl：Hello World
来源：http://dali.smart0.xyz/Article/details/gthspbttem.html

print "Hello\n";
来源：http://dali.hfpthk.cn/Article/details/gtpdrvmlgp.html

[T42] Perl：变量类型
来源：http://dali.cashguo.top/Article/details/gtdomgkgov.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinqigufen.top/Article/details/gtiuxntmee.html

[T43] Perl：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtaxtssydl.html

"值: $a"
来源：http://dali.yueranfly.top/Article/details/gtlunepifl.html

[T44] Perl：条件
来源：http://dali.xylfe.cn/Article/details/gtmioiisoa.html

if ($a > 0) { print "正"; }
来源：http://dali.sweek.top/Article/details/gtxatvkwgo.html

[T45] Perl：数组遍历
来源：http://dali.shzxlz.cn/Article/details/gtlugoltnj.html

for my $x (@arr) { print $x; }
来源：http://dali.hywenlv.cn/Article/details/gthbnrvgft.html

[T46] Perl：哈希操作
来源：http://dali.aibaodan.cn/Article/details/gtfvirtece.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.quarkkingdee.top/Article/details/gtuyseigoq.html

[T47] Perl：正则捕获
来源：http://dali.kuanghao11.cn/Article/details/gtuoexgzkr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.fzhhl.top/Article/details/gtfdfgrefw.html

[T48] Perl：正则替换
来源：http://dali.yuanzhike.top/Article/details/gtujhookgu.html

$s =~ s/old/new/g;
来源：http://dali.vqdsnc.cn/Article/details/gtuhczldcg.html

[T49] Perl：函数
来源：http://dali.9152youxi.cn/Article/details/gtlrooldsh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtjfemzcmx.html

[T50] Perl：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtvmsfecfr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.birdmap.top/Article/details/gtaodpcgac.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hfpthk.cn/Article/details/gtybnzuxjr.html

[T51] Scala：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtyshdiymx.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtiogemxpt.html

[T52] Scala：变量
来源：http://dali.gotoacloud.top/Article/details/gtxwzdibum.html

val a = 1;  var b = 2
来源：http://dali.yuanzhike.top/Article/details/gtnwryhphu.html

[T53] Scala：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtcvqjpahd.html

s"值: $b"
来源：http://dali.kuanghao11.cn/Article/details/gtquckksjl.html

[T54] Scala：集合映射
来源：http://dali.iojbl.cn/Article/details/gtbopoayvc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjgsadoi.html

[T55] Scala：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gtsflexmda.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.meibo888.top/Article/details/gtdxlghrsv.html

[T56] Scala：样例类
来源：http://dali.cdnleiting.top/Article/details/gtsvhxfhgu.html

case class User(name: String, age: Int)
来源：http://dali.dianchejie.cn/Article/details/gtcpcjdvhn.html

[T57] Scala：模式匹配
来源：http://dali.haohaochexian.top/Article/details/gtbihwfolu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhoulong.xyz/Article/details/gtfxnpfswb.html

[T58] Scala：函数定义
来源：http://dali.yvedp.cn/Article/details/gtjphyltin.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.bjfxy.top/Article/details/gtijmbcynw.html

[T59] Scala：循环
来源：http://dali.snrcjt.cn/Article/details/gtaekjlgmy.html

for (i <- 1 to 10) println(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcspptbvt.html

[T60] Scala：折叠
来源：http://dali.jyoumei.cn/Article/details/gtzqplqwqm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tianlin.xyz/Article/details/gtxxfshyhy.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtxszmhchb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tanke756.top/Article/details/gtnrcooail.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtjocgwidf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhoulong.xyz/Article/details/gtdehhieqr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.iojbl.cn/Article/details/gtumnsakth.html

[U02] Py：导出 / 安装依赖
来源：http://dali.andypj.xyz/Article/details/gtonuevvah.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hfpthk.cn/Article/details/gtwietwscv.html

[U03] Py：加载 .env 配置
来源：http://dali.daxiang520.top/Article/details/gtqxhbhsqk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hongshengwenyu.top/Article/details/gtfamqshpa.html

[U04] Py：变量调试打印
来源：http://dali.svipenyu.cn/Article/details/gtdrfcndko.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ppjwa.cn/Article/details/gtkunyvkuk.html

[U05] Py：列表去重且保序
来源：http://dali.shzxlz.cn/Article/details/gtdqjawhbw.html

list(dict.fromkeys(arr))
来源：http://dali.xuetiantiany.cn/Article/details/gttnqqgwel.html

[U06] Py：合并两个字典
来源：http://dali.yuxming.cn/Article/details/gtrgcjgkah.html

{**a, **b}
来源：http://dali.nanxinkj.top/Article/details/gtusvchsst.html

[U07] Py：反转字典键值
来源：http://dali.xuanzx.com/Article/details/gtxsvxdneo.html

{v: k for k, v in d.items()}
来源：http://dali.jinqigfzy.top/Article/details/gtkjofduqh.html

[U08] Py：展平二维列表
来源：http://dali.mhx1999.top/Article/details/gtinwyqbsk.html

[y for x in nested for y in x]
来源：http://dali.tianlin.xyz/Article/details/gtdusxsjgu.html

[U09] Py：字典取最大值的键
来源：http://dali.cdnleiting.top/Article/details/gtcnphtixu.html

max(d, key=d.get)
来源：http://dali.hammf.cn/Article/details/gtryreoeag.html

[U10] Py：按值排序字典
来源：http://dali.xylfe.cn/Article/details/gtpeymqcuy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.9152youxi.cn/Article/details/gtzwkbfaiv.html

[U11] Py：生成器表达式
来源：http://dali.jinqigfzy.top/Article/details/gtqpgiguln.html

(x * 2 for x in arr)
来源：http://dali.yvedp.cn/Article/details/gteordylkb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yonumen.top/Article/details/gtigyaqvzx.html

Counter(arr).most_common(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtmyidkbbe.html

[U13] Py：固定长度队列
来源：http://dali.hfpthk.cn/Article/details/gthpvgwiiw.html

deque(maxlen=10)
来源：http://dali.shangyingyoupin.top/Article/details/gtdngwuxoz.html

[U14] Py：分组收集到列表
来源：http://dali.chenzaomai.com/Article/details/gtuunhizeg.html

defaultdict(list)
来源：http://dali.guannengcc.top/Article/details/gtmnazskiw.html

[U15] Py：高精度计时
来源：http://dali.pengpengdd.cyou/Article/details/gtkbdgrqzu.html

t = time.perf_counter()
来源：http://dali.ehwqpu.com/Article/details/gtxbnwelcz.html

[U16] Py：命令行参数解析
来源：http://dali.sysykeji.top/Article/details/gtvktqrvpk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hywenlv.cn/Article/details/gtsmsuhncd.html

[U17] Py：初始化日志
来源：http://dali.9152youxi.cn/Article/details/gtpanyfkkh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinghuilouyu.cn/Article/details/gtujwzfjlo.html

[U18] Py：预编译正则
来源：http://dali.snrcjt.cn/Article/details/gtqoquzmtt.html

pat = re.compile(r"\d+")
来源：http://dali.hnqzz.top/Article/details/gtnnueiavj.html

[U19] Py：正则替换带回调
来源：http://dali.tanke756.top/Article/details/gtlxehufil.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tianlin.xyz/Article/details/gtmduoyonb.html

[U20] Py：缓存函数结果
来源：http://dali.cheryme.top/Article/details/gtrojcfqyp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.dashuyun.cn/Article/details/gtxiddsynm.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnqzz.top/Article/details/gtrideeevs.html

@contextlib.contextmanager
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbopapczb.html

[U22] Py：矩阵转置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnrfnage.html

list(zip(*m))
来源：http://dali.zhengqikj.top/Article/details/gtacxrvqic.html

[U23] Py：分块读取大文件
来源：http://dali.guowangkeji.top/Article/details/gtkddsjeqa.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zdqjudy.top/Article/details/gtwonaxpkb.html

[U24] Py：路径操作
来源：http://dali.yanxiufei.cn/Article/details/gtsnlcpglc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gtlutoeiqi.html

[U25] Py：CSV 按字典读
来源：http://dali.shzxlz.cn/Article/details/gtrqmszmkq.html

csv.DictReader(f)
来源：http://dali.chenzaomai.com/Article/details/gtpwqxzzyh.html

[U26] Py：并发下载
来源：http://dali.haohaochexian.top/Article/details/gtminakxlf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yongpay.top/Article/details/gtaflgqrgq.html

[U27] Py：异步 HTTP
来源：http://dali.yangfankeji.com/Article/details/gtdvvumigc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yonumen.top/Article/details/gtoabzgbnn.html

[U28] Py：类型别名
来源：http://dali.aibaodan.cn/Article/details/gtbvveasjv.html

UserId = int
来源：http://dali.redwolf501.top/Article/details/gtgrsiierd.html

[U29] Py：属性校验
来源：http://dali.xylfe.cn/Article/details/gtzurhqkhh.html

@property 与 @x.setter 配合
来源：http://dali.hongshengwenyu.top/Article/details/gtpeyqvyqf.html

[U30] Py：数据类
来源：http://dali.0kj1m.cn/Article/details/gtrerfynmm.html

@dataclass(slots=True)
来源：http://dali.yuxming.cn/Article/details/gtijtlricr.html

[U31] Py：单测
来源：http://dali.jlsjyb.cn/Article/details/gtcaopqzko.html

python -m pytest -q
来源：http://dali.dashuyun.cn/Article/details/gtimbgjrha.html

[U32] Py：代码格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtalcyxhiv.html

ruff format . && ruff check --fix .
来源：http://dali.shuidangran.top/Article/details/gtvyxfcmxm.html

[U33] Py：打包发布
来源：http://dali.dashuyun.cn/Article/details/gthsscwoel.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqidbitk.html

[U34] Py：判断编码
来源：http://dali.daria6918.cn/Article/details/gtlejijpiz.html

chardet.detect(raw)
来源：http://dali.redwolf501.top/Article/details/gtnbgqtmjw.html

[U35] Py：发送邮件
来源：http://dali.dianchejie.cn/Article/details/gtrghtgobb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.9152youxi.cn/Article/details/gtaulfpxah.html

[U36] Py：定时任务
来源：http://dali.pengpengdd.cyou/Article/details/gtxguawneo.html

schedule.every(10).minutes.do(job)
来源：http://dali.gogol.net.cn/Article/details/gtlzgzromn.html

[U37] Py：读写 Excel
来源：http://dali.dashuyun.cn/Article/details/gtgnmezwkp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.9152youxi.cn/Article/details/gtofaufpbl.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gtaygkzbqh.html

Path(__file__).resolve().parent
来源：http://dali.9152youxi.cn/Article/details/gtejdxizsl.html

[U39] Py：判断是否在交互环境
来源：http://dali.ybcxt.top/Article/details/gtubebuezy.html

sys.stdout.isatty()
来源：http://dali.chenzaomai.com/Article/details/gtnxmqpzyq.html

[U40] Py：打印到标准错误
来源：http://dali.birdmap.top/Article/details/gtukiednse.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtwkrpixzo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.0kj1m.cn/Article/details/gtysxkkvzt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yuanzhike.top/Article/details/gtfhaavbst.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yangfankeji.com/Article/details/gtitudbgge.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jqgfzy.top/Article/details/gtbnbithoe.html

[U43] PHP：声明命名空间
来源：http://dali.kuanghao11.cn/Article/details/gtoryjkdxk.html

namespace App\Http;
来源：http://dali.shangyingyoupin.top/Article/details/gtsvndotbw.html

[U44] PHP：开启严格类型
来源：http://dali.sxryk.cn/Article/details/gtcwxkcjhf.html

declare(strict_types=1);
来源：http://dali.jinqigfzy.top/Article/details/gtxiyvhcdx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ehwqpu.com/Article/details/gthkysqsbg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gtygishfxh.html

[U46] PHP：可空类型
来源：http://dali.yvedp.cn/Article/details/gtwwhhxyrq.html

?string $name = null
来源：http://dali.zhoulong.xyz/Article/details/gtevezvfse.html

[U47] PHP：联合类型
来源：http://dali.redwolf501.top/Article/details/gtxtahdcop.html

int|string $id
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjlrpmfw.html

[U48] PHP：纯枚举
来源：http://dali.gogol.net.cn/Article/details/gtqlnjphdx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.guowangkeji.top/Article/details/gtbxcpqtgu.html

[U49] PHP：只读属性
来源：http://dali.kuanghao11.cn/Article/details/gtpdtxmuqo.html

public readonly string $name
来源：http://dali.chenjidiqi.icu/Article/details/gttzljjbju.html

[U50] PHP：构造器属性提升
来源：http://dali.yangfankeji.com/Article/details/gttlkrlpse.html

public function __construct(private int $id) {}
来源：http://dali.cheryme.top/Article/details/gtqcdaiqeh.html

[U51] PHP：数组解构
来源：http://dali.zhongyouzk.top/Article/details/gtkyfgjggz.html

[$a, $b] = $arr;
来源：http://dali.havefunace.top/Article/details/gtbqcyfimd.html

[U52] PHP：箭头函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbybkxmvt.html

$double = fn($x) => $x * 2;
来源：http://dali.shangyingyoupin.top/Article/details/gtawzicgvz.html

[U53] PHP：空合并运算符
来源：http://dali.ivvv.top/Article/details/gtnsesrssk.html

$v = $a ?? $b ?? "default";
来源：http://dali.jqgufenzy.top/Article/details/gtmdkgkzps.html

[U54] PHP：空安全调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqoisysje.html

$obj?->method()
来源：http://dali.meibo888.top/Article/details/gtlwhqgawg.html

[U55] PHP：match 表达式
来源：http://dali.jiagoushi.top/Article/details/gtifkavkdu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yangfankeji.com/Article/details/gtwviiwhvs.html

[U56] PHP：命名参数
来源：http://dali.wangdashe.top/Article/details/gtxdgdyfaw.html

f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gtstjzpbnx.html

[U57] PHP：字符串插值
来源：http://dali.pycfn.com/Article/details/gtglxjgmpi.html

"值: {$a}"
来源：http://dali.9152youxi.cn/Article/details/gthvdencdo.html

[U58] PHP：数组三件套
来源：http://dali.svipenyu.cn/Article/details/gtrwtrqwoz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.iojbl.cn/Article/details/gtvklnmzse.html

[U59] PHP：自定义排序
来源：http://dali.aibaodan.cn/Article/details/gtkyyfxfyx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gzhubu.top/Article/details/gtotnkgfir.html

[U60] PHP：JSON 编解码
来源：http://dali.hammf.cn/Article/details/gtygajznut.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtltveyjpx.html

[U61] PHP：正则
来源：http://dali.yonumen.top/Article/details/gtqqzxelvo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gtaqcgozsw.html

[U62] PHP：日期对象
来源：http://dali.zhiwuduotai.top/Article/details/gtapcgptzv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jianghu66.top/Article/details/gtsuteyszg.html

[U63] PHP：文件读写
来源：http://dali.ehwqpu.com/Article/details/gtcyfsockf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxdlqnoc.html

[U64] PHP：目录遍历
来源：http://dali.guowangkeji.top/Article/details/gtcowqwcwi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj202588.top/Article/details/gtfpapqoyq.html

[U65] PHP：会话
来源：http://dali.hnxiangtu.top/Article/details/gtsyskaftz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtwjbvzrds.html

[U66] PHP：设置 Cookie
来源：http://dali.sxryk.cn/Article/details/gtgjtdbjpe.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cqqwz.cn/Article/details/gtfgllvnwp.html

[U67] PHP：处理文件上传
来源：http://dali.sufxvd.cn/Article/details/gtxdgkvfcp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yvedp.cn/Article/details/gttauqmcib.html

[U68] PHP：PDO 连接
来源：http://dali.9152youxi.cn/Article/details/gtyonjbfvy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ydzc1.top/Article/details/gtmqycaytk.html

[U69] PHP：PDO 预处理
来源：http://dali.redwolf501.top/Article/details/gtqzmjnana.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.nanxuanxn.top/Article/details/gtplpmjtte.html

[U70] PHP：PDO 事务
来源：http://dali.svipenyu.cn/Article/details/gtapypfdgg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tian-w.cn/Article/details/gthqlsyefu.html

[U71] PHP：抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gtnkvzuwst.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhiwuduotai.top/Article/details/gtwvyqrnyr.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gttypovbgx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.dashuyun.cn/Article/details/gtkvrqveik.html

[U73] PHP：读取 ini 配置
来源：http://dali.yj20258.top/Article/details/gtemcnvcgz.html

parse_ini_file("config.ini", true)
来源：http://dali.birdmap.top/Article/details/gtfyphrtbd.html

[U74] PHP：读取环境变量
来源：http://dali.gotoacloud.top/Article/details/gtwqjjnpmz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthliypdpz.html


<!-- 参考信息 -->