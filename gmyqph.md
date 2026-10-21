代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxqwvyzcj.html

[S53] C++：移动语义
来源：http://dali.cqqwz.cn/Article/details/gtvhzignlf.html

std::vector<int> w = std::move(v);
来源：http://dali.sufxvd.cn/Article/details/gtpeybaklc.html

[S54] C++：异常处理
来源：http://dali.sxryk.cn/Article/details/gtvabuuoyq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yvedp.cn/Article/details/gttpvwyokr.html

[S55] C++：结构化绑定
来源：http://dali.xziqi.cn/Article/details/gtsrdyxhdp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjqbdfvs.html

[S56] C++：optional
来源：http://dali.zhoulong.xyz/Article/details/gtvalywfvt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xylfe.cn/Article/details/gtmunwbfoz.html

[S57] C++：编译期常量
来源：http://dali.jianghu66.top/Article/details/gtwzfaxynx.html

constexpr int N = 10;
来源：http://dali.gzhubu.top/Article/details/gtziivcphl.html

[S58] C++：命名空间
来源：http://dali.cheryme.top/Article/details/gtzccycdmm.html

namespace ns { int f() { return 1; } }
来源：http://dali.aibaodan.cn/Article/details/gtehsoxwkz.html

[S59] C++：静态断言
来源：http://dali.fzhhl.top/Article/details/gtfmkozvzl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fzhhl.top/Article/details/gtlmxmfrnh.html

[S60] C++：遍历并删除元素
来源：http://dali.ehwqpu.com/Article/details/gtzedfftff.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.iojbl.cn/Article/details/gtnotjzyhl.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtcpzqmkoj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gtbyhsmniq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgycpfep.html

[T01] Kotlin：Hello World
来源：http://dali.sxryk.cn/Article/details/gtacfhowrp.html

println("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtluoogheo.html

[T02] Kotlin：变量
来源：http://dali.feifeiyinyue.top/Article/details/gtuxmsfalu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shzxlz.cn/Article/details/gtkxcuajwv.html

[T03] Kotlin：字符串模板
来源：http://dali.tian-w.cn/Article/details/gtunszrgll.html

"值: $b"
来源：http://dali.shangyingyoupin.top/Article/details/gtheusysyn.html

[T04] Kotlin：空安全
来源：http://dali.quarkkingdee.top/Article/details/gtfxooxmhp.html

val n: String? = null;  n?.length
来源：http://dali.sxryk.cn/Article/details/gtwbkokhvw.html

[T05] Kotlin：when 表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtsuirkzmy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezerosue.html

[T06] Kotlin：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwbeuluk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtccbpcdua.html

[T07] Kotlin：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gtlmtizvif.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sysykeji.top/Article/details/gtqvbypczc.html

[T08] Kotlin：数据类
来源：http://dali.jyoumei.cn/Article/details/gtoyaujmhm.html

data class User(val name: String, val age: Int)
来源：http://dali.cdnleiting.top/Article/details/gtdlhqlwtf.html

[T09] Kotlin：扩展函数
来源：http://dali.shangyingyoupin.top/Article/details/gtwlkzqeyn.html

fun String.exclaim() = this + "!"
来源：http://dali.yueranfly.top/Article/details/gtotabnoil.html

[T10] Kotlin：默认参数
来源：http://dali.jqgfzy.top/Article/details/gtogivzanm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.iojbl.cn/Article/details/gttmojfkgz.html

[T11] Kotlin：协程
来源：http://dali.hammf.cn/Article/details/gthqdkanqy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuanzhike.top/Article/details/gtopqovfct.html

[T12] Kotlin：解构声明
来源：http://dali.gzhubu.top/Article/details/gtbbkfcepd.html

val (a, b) = Pair(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtltbmfloe.html

[T13] Kotlin：只读 Map
来源：http://dali.jiagoushi.top/Article/details/gtocjflimy.html

val m = mapOf("a" to 1)
来源：http://dali.xinyue.icu/Article/details/gtcllsfbxp.html

[T14] Kotlin：循环
来源：http://dali.jyoumei.cn/Article/details/gtcxdaafkz.html

for (i in 1..10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gtgcreogya.html

[T15] Kotlin：接口
来源：http://dali.sysykeji.top/Article/details/gtvslmutac.html

interface Shape { fun area(): Double }
来源：http://dali.sufxvd.cn/Article/details/gtlqevkqhh.html

[T16] Swift：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtaucunuaa.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gtcksdgvjz.html

[T17] Swift：变量与常量
来源：http://dali.cdnleiting.top/Article/details/gtplbzogkp.html

var a = 1;  let b = 2
来源：http://dali.svipenyu.cn/Article/details/gtadvvgorj.html

[T18] Swift：字符串插值
来源：http://dali.316326.xyz/Article/details/gtyfkwauyo.html

"值: \(b)"
来源：http://dali.shzxlz.cn/Article/details/gtmgjadymq.html

[T19] Swift：可选绑定
来源：http://dali.sxryk.cn/Article/details/gtfzoivxln.html

if let n = opt { print(n) }
来源：http://dali.havefunace.top/Article/details/gtyzlbszdb.html

[T20] Swift：数组操作
来源：http://dali.shzxlz.cn/Article/details/gtoubipbgq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.birdmap.top/Article/details/gteeratgoy.html

[T21] Swift：遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtqqegeeld.html

for x in a { print(x) }
来源：http://dali.pycfn.com/Article/details/gtckutfjnt.html

[T22] Swift：字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmyjxoihe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.vqdsnc.cn/Article/details/gtphyibdwx.html

[T23] Swift：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtfimufayk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtjqvnalgo.html

[T24] Swift：闭包
来源：http://dali.sysykeji.top/Article/details/gtjhrzpehs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xziqi.cn/Article/details/gtldtzbywi.html

[T25] Swift：结构体
来源：http://dali.jinqigufen.top/Article/details/gtpxiwadzg.html

struct P { var x: Int }
来源：http://dali.cheryme.top/Article/details/gthmuzyoho.html

[T26] Swift：类与重写
来源：http://dali.gotoacloud.top/Article/details/gtwoeurzha.html

class A: Base { override func f() {} }
来源：http://dali.hnxiangtu.top/Article/details/gtmwlhsaag.html

[T27] Swift：错误处理
来源：http://dali.iojbl.cn/Article/details/gtxrikrtrk.html

do { try f() } catch { print(error) }
来源：http://dali.xinyue.icu/Article/details/gthmlxrohs.html

[T28] Swift：枚举
来源：http://dali.aibaodan.cn/Article/details/gtejmpbgit.html

enum Color { case red, green }
来源：http://dali.xuetiantiany.cn/Article/details/gtjjczmida.html

[T29] Swift：guard 提前返回
来源：http://dali.andypj.xyz/Article/details/gtqtlilpso.html

guard let x = opt else { return }
来源：http://dali.nanxinkj.top/Article/details/gtivsxsstu.html

[T30] Swift：协议
来源：http://dali.xylfe.cn/Article/details/gtntkviiyg.html

protocol Shape { func area() -> Double }
来源：http://dali.guannengcc.top/Article/details/gtaiyfrlse.html

[T31] Lua：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtdrelatmi.html

print("Hello")
来源：http://dali.tanke756.top/Article/details/gtludmbdac.html

[T32] Lua：局部变量
来源：http://dali.wangdashe.top/Article/details/gtswqvdeeh.html

local a = 1
来源：http://dali.wangdashe.top/Article/details/gtajalbhhk.html

[T33] Lua：表（数组）
来源：http://dali.tian-w.cn/Article/details/gtfgomovps.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gogol.net.cn/Article/details/gtwokoeerz.html

[T34] Lua：遍历表
来源：http://dali.jyoumei.cn/Article/details/gtteowkrtx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgfzy.top/Article/details/gtvavlzwyc.html

[T35] Lua：字典表
来源：http://dali.yvedp.cn/Article/details/gtnhtnvdzh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sweek.top/Article/details/gtchpqnozd.html

[T36] Lua：函数
来源：http://dali.guannengcc.top/Article/details/gtjpgzpjzo.html

function add(a, b) return a + b end
来源：http://dali.xuanzx.com/Article/details/gtcmxfzeaq.html

[T37] Lua：字符串拼接
来源：http://dali.meibo888.top/Article/details/gtudqkihwp.html

"a" .. "b"
来源：http://dali.andypj.xyz/Article/details/gtavpfatou.html

[T38] Lua：条件
来源：http://dali.ydzc1.top/Article/details/gttitjicyf.html

if x > 0 then print("正") end
来源：http://dali.smart0.xyz/Article/details/gtlbghgxcb.html

[T39] Lua：模式匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtnswpxngd.html

string.find(s, "%d+")
来源：http://dali.hfpthk.cn/Article/details/gttehavlwx.html

[T40] Lua：元表
来源：http://dali.chenjidiqi.icu/Article/details/gtnwfzezmh.html

setmetatable({}, { __index = base })
来源：http://dali.ivvv.top/Article/details/gtwezlyxcn.html

[T41] Perl：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtsrcjiuvc.html

print "Hello\n";
来源：http://dali.nanxuanxn.top/Article/details/gtocofsoky.html

[T42] Perl：变量类型
来源：http://dali.meibo888.top/Article/details/gtmszufhaj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hfpthk.cn/Article/details/gtqlvfzdsg.html

[T43] Perl：字符串插值
来源：http://dali.pycfn.com/Article/details/gtlhidiofu.html

"值: $a"
来源：http://dali.chenjidiqi.icu/Article/details/gtdswzhifm.html

[T44] Perl：条件
来源：http://dali.birdmap.top/Article/details/gtdvbtksuk.html

if ($a > 0) { print "正"; }
来源：http://dali.birdmap.top/Article/details/gtpibmeows.html

[T45] Perl：数组遍历
来源：http://dali.shuidangran.top/Article/details/gtqakromai.html

for my $x (@arr) { print $x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrrddlikg.html

[T46] Perl：哈希操作
来源：http://dali.yonumen.top/Article/details/gtjcplgvqj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yvedp.cn/Article/details/gtpskpbooh.html

[T47] Perl：正则捕获
来源：http://dali.shangyingyoupin.top/Article/details/gtxeumourd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dashuyun.cn/Article/details/gtxszgalna.html

[T48] Perl：正则替换
来源：http://dali.nanxuanxn.top/Article/details/gtfckziwdb.html

$s =~ s/old/new/g;
来源：http://dali.daria6918.cn/Article/details/gtunjskdpy.html

[T49] Perl：函数
来源：http://dali.yonumen.top/Article/details/gtrorhmstl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtcandbnxo.html

[T50] Perl：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtvpukyrmo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.mhx1999.top/Article/details/gtaavdjlsi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tanke756.top/Article/details/gtduwyvnyb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gthkskmzjv.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtxqztexwf.html

[T52] Scala：变量
来源：http://dali.yj20258888.top/Article/details/gtbakobzxm.html

val a = 1;  var b = 2
来源：http://dali.hnxiangtu.top/Article/details/gtngvghrqa.html

[T53] Scala：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtmasnjzlr.html

s"值: $b"
来源：http://dali.kuanghao11.cn/Article/details/gtxmabpiyu.html

[T54] Scala：集合映射
来源：http://dali.cashguo.top/Article/details/gtjbdxzjpj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgfzy.top/Article/details/gtrifkyjhl.html

[T55] Scala：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gtoyifwcgz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jqgfzy.top/Article/details/gtamvyqnme.html

[T56] Scala：样例类
来源：http://dali.yongpay.top/Article/details/gttlmlkmoa.html

case class User(name: String, age: Int)
来源：http://dali.jqgfzy.top/Article/details/gtmxlmjtav.html

[T57] Scala：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtdfvchwmm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yonumen.top/Article/details/gtarteodua.html

[T58] Scala：函数定义
来源：http://dali.pycfn.com/Article/details/gtdryhaccf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guowangkeji.top/Article/details/gtlddndsnx.html

[T59] Scala：循环
来源：http://dali.xuanzx.com/Article/details/gtjilnimve.html

for (i <- 1 to 10) println(i)
来源：http://dali.cashguo.top/Article/details/gtctfgwndn.html

[T60] Scala：折叠
来源：http://dali.ivvv.top/Article/details/gtfcsscdiv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jlsjyb.cn/Article/details/gtyzkyozrq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtdesfbogx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtfyjjcqcm.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtqeezxtfn.html

[U01] Py：创建虚拟环境
来源：http://dali.hammf.cn/Article/details/gtmpgyxdfj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ehwqpu.com/Article/details/gtkfouavkj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fzhhl.top/Article/details/gtqtgabqeg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guannengcc.top/Article/details/gtmvmrsptr.html

[U03] Py：加载 .env 配置
来源：http://dali.haohaochexian.top/Article/details/gtdyjzhxzl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.dashuyun.cn/Article/details/gtpvkkyktj.html

[U04] Py：变量调试打印
来源：http://dali.hywenlv.cn/Article/details/gtgvymkxqi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xinyue.icu/Article/details/gtrludhvkl.html

[U05] Py：列表去重且保序
来源：http://dali.zhongyouzk.top/Article/details/gthbwqeqxt.html

list(dict.fromkeys(arr))
来源：http://dali.cucudq.cn/Article/details/gtoehcmtst.html

[U06] Py：合并两个字典
来源：http://dali.smart0.xyz/Article/details/gthmjnqovw.html

{**a, **b}
来源：http://dali.zycfv.cn/Article/details/gtxpiiasqz.html

[U07] Py：反转字典键值
来源：http://dali.gogol.net.cn/Article/details/gtbzafyxnp.html

{v: k for k, v in d.items()}
来源：http://dali.aibaodan.cn/Article/details/gtfnslocdk.html

[U08] Py：展平二维列表
来源：http://dali.gaohongyu789.top/Article/details/gtolqgswqr.html

[y for x in nested for y in x]
来源：http://dali.wangdashe.top/Article/details/gtbdfpgtkn.html

[U09] Py：字典取最大值的键
来源：http://dali.mhx1999.top/Article/details/gtodnlwlqd.html

max(d, key=d.get)
来源：http://dali.ppjwa.cn/Article/details/gtghwtrevn.html

[U10] Py：按值排序字典
来源：http://dali.jianghu66.top/Article/details/gtrvuldmsj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xuanzx.com/Article/details/gtrqcgermu.html

[U11] Py：生成器表达式
来源：http://dali.fengsongda.top/Article/details/gtjzixgzjs.html

(x * 2 for x in arr)
来源：http://dali.hammf.cn/Article/details/gtzgjvspxu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.kuanghao11.cn/Article/details/gtyefzreqq.html

Counter(arr).most_common(3)
来源：http://dali.tian-w.cn/Article/details/gtltsnwekt.html

[U13] Py：固定长度队列
来源：http://dali.yj20258888.top/Article/details/gtupchodwn.html

deque(maxlen=10)
来源：http://dali.ehwqpu.com/Article/details/gtbjmpxtbm.html

[U14] Py：分组收集到列表
来源：http://dali.yongpay.top/Article/details/gtedngytkn.html

defaultdict(list)
来源：http://dali.shuidangran.top/Article/details/gtgewqssmi.html

[U15] Py：高精度计时
来源：http://dali.ywan-chungtsiang.top/Article/details/gteamprcdl.html

t = time.perf_counter()
来源：http://dali.zhoulong.xyz/Article/details/gtuomjfmqc.html

[U16] Py：命令行参数解析
来源：http://dali.yongpay.top/Article/details/gtjdyvrhis.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xuetiantiany.cn/Article/details/gtfwxkpjnz.html

[U17] Py：初始化日志
来源：http://dali.xuanzx.com/Article/details/gtnuezfavt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.andypj.xyz/Article/details/gtnnuiqmfe.html

[U18] Py：预编译正则
来源：http://dali.yuxming.cn/Article/details/gtcnkswprr.html

pat = re.compile(r"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gtrynuwlrc.html

[U19] Py：正则替换带回调
来源：http://dali.xziqi.cn/Article/details/gtomfnmpok.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sxryk.cn/Article/details/gtfxdqfpbt.html

[U20] Py：缓存函数结果
来源：http://dali.guowangkeji.top/Article/details/gtwnjkpzno.html

@functools.lru_cache(maxsize=None)
来源：http://dali.vqdsnc.cn/Article/details/gtgwxrbnkm.html

[U21] Py：自定义上下文管理器
来源：http://dali.hongshengwenyu.top/Article/details/gtlroquimt.html

@contextlib.contextmanager
来源：http://dali.sxryk.cn/Article/details/gtigluodzb.html

[U22] Py：矩阵转置
来源：http://dali.hnqzz.top/Article/details/gtdwokzzkj.html

list(zip(*m))
来源：http://dali.hnxiangtu.top/Article/details/gtrgypelei.html

[U23] Py：分块读取大文件
来源：http://dali.yj202588.top/Article/details/gtxosixaeu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xuetiantiany.cn/Article/details/gthsclstkt.html

[U24] Py：路径操作
来源：http://dali.yvedp.cn/Article/details/gtzdclklld.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gtwxwjydbr.html

[U25] Py：CSV 按字典读
来源：http://dali.cashguo.top/Article/details/gtjnvkyntt.html

csv.DictReader(f)
来源：http://dali.hfpthk.cn/Article/details/gtpytvcfca.html

[U26] Py：并发下载
来源：http://dali.gzhubu.top/Article/details/gtatguxjlh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.quarkkingdee.top/Article/details/gtiasobcim.html

[U27] Py：异步 HTTP
来源：http://dali.yanxiufei.cn/Article/details/gtwxvryblg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jyoumei.cn/Article/details/gteqwjjfwq.html

[U28] Py：类型别名
来源：http://dali.bjfxy.top/Article/details/gtbtikwalr.html

UserId = int
来源：http://dali.xinyue.icu/Article/details/gtovzinxwz.html

[U29] Py：属性校验
来源：http://dali.9152youxi.cn/Article/details/gtrejzphuq.html

@property 与 @x.setter 配合
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkztbsze.html

[U30] Py：数据类
来源：http://dali.zhongyouzk.top/Article/details/gtipkojsdw.html

@dataclass(slots=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjpekzak.html

[U31] Py：单测
来源：http://dali.xuanzx.com/Article/details/gtbpzugfhc.html

python -m pytest -q
来源：http://dali.hfpthk.cn/Article/details/gtqtnyrzap.html

[U32] Py：代码格式化
来源：http://dali.zhixingplan.top/Article/details/gtufkyoqra.html

ruff format . && ruff check --fix .
来源：http://dali.feifeiyinyue.top/Article/details/gteihsmdzk.html

[U33] Py：打包发布
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlywsukwh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.daxiang520.top/Article/details/gtqihtimzp.html

[U34] Py：判断编码
来源：http://dali.chenjidiqi.icu/Article/details/gtrrzswfgm.html

chardet.detect(raw)
来源：http://dali.chenzaomai.com/Article/details/gtybgteuhc.html

[U35] Py：发送邮件
来源：http://dali.xylfe.cn/Article/details/gtthyhlmuh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcybupwxw.html

[U36] Py：定时任务
来源：http://dali.yvedp.cn/Article/details/gtdltlhihz.html

schedule.every(10).minutes.do(job)
来源：http://dali.jiagoushi.top/Article/details/gthwyrbdpa.html

[U37] Py：读写 Excel
来源：http://dali.hnxiangtu.top/Article/details/gtzvsnlkpb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hfpthk.cn/Article/details/gtbppwlrwe.html

[U38] Py：获取脚本所在目录
来源：http://dali.haohaochexian.top/Article/details/gtpbqdyacy.html

Path(__file__).resolve().parent
来源：http://dali.cheryme.top/Article/details/gtcfcokeyh.html

[U39] Py：判断是否在交互环境
来源：http://dali.bjfxy.top/Article/details/gtwukptrff.html

sys.stdout.isatty()
来源：http://dali.cheryme.top/Article/details/gtldmgfjnp.html

[U40] Py：打印到标准错误
来源：http://dali.zhiwuduotai.top/Article/details/gtzjbjmuuk.html

print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gtgbgxswok.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.guannengcc.top/Article/details/gtnndevxdt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.fengsongda.top/Article/details/gtueealpcy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenlongwang.top/Article/details/gtprippjql.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.meibo888.top/Article/details/gtuwjbmpga.html

[U43] PHP：声明命名空间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuugktnwu.html

namespace App\Http;
来源：http://dali.chenzaomai.com/Article/details/gtzlzbvyhh.html

[U44] PHP：开启严格类型
来源：http://dali.nwbrower.top/Article/details/gtbnydlqen.html

declare(strict_types=1);
来源：http://dali.jianghu66.top/Article/details/gtzpluajif.html

[U45] PHP：类型声明与返回类型
来源：http://dali.feifeiyinyue.top/Article/details/gtrfukeuht.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtcdhlqjjd.html

[U46] PHP：可空类型
来源：http://dali.cucudq.cn/Article/details/gtrebqnhbb.html

?string $name = null
来源：http://dali.jianghu66.top/Article/details/gtcnanpssu.html

[U47] PHP：联合类型
来源：http://dali.wangshuangyany.cn/Article/details/gtdtrsdydx.html

int|string $id
来源：http://dali.chenlongwang.top/Article/details/gtypukvidn.html

[U48] PHP：纯枚举
来源：http://dali.cheryme.top/Article/details/gtwiluiogb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ydzc1.top/Article/details/gtozhrogxc.html

[U49] PHP：只读属性
来源：http://dali.yj20258888.top/Article/details/gtdznbuwha.html

public readonly string $name
来源：http://dali.nanxinkj.top/Article/details/gtyjdsjuxb.html

[U50] PHP：构造器属性提升
来源：http://dali.jinqigufen.top/Article/details/gtushhpdqs.html

public function __construct(private int $id) {}
来源：http://dali.316326.xyz/Article/details/gtwjqowavo.html

[U51] PHP：数组解构
来源：http://dali.hfpthk.cn/Article/details/gtqypdfgfj.html

[$a, $b] = $arr;
来源：http://dali.svipenyu.cn/Article/details/gtiaesdydz.html

[U52] PHP：箭头函数
来源：http://dali.havefunace.top/Article/details/gtbzzpmkap.html

$double = fn($x) => $x * 2;
来源：http://dali.jlsjyb.cn/Article/details/gteotdcwxr.html

[U53] PHP：空合并运算符
来源：http://dali.havefunace.top/Article/details/gtlzgpqcpl.html

$v = $a ?? $b ?? "default";
来源：http://dali.shangyingyoupin.top/Article/details/gtufktnaun.html

[U54] PHP：空安全调用
来源：http://dali.jianghu66.top/Article/details/gtmmyuyfue.html

$obj?->method()
来源：http://dali.ppjwa.cn/Article/details/gtkjwzulqf.html

[U55] PHP：match 表达式
来源：http://dali.yvedp.cn/Article/details/gtnhibmlnr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpqnoips.html

[U56] PHP：命名参数
来源：http://dali.yj20258.top/Article/details/gtzbrmsvjx.html

f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gtcfwydmlf.html

[U57] PHP：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtekvmecoi.html

"值: {$a}"
来源：http://dali.cucudq.cn/Article/details/gtbpnzoqhy.html

[U58] PHP：数组三件套
来源：http://dali.daria6918.cn/Article/details/gtjxzekiwc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.mhx1999.top/Article/details/gtajyyjqir.html

[U59] PHP：自定义排序
来源：http://dali.zycfv.cn/Article/details/gtouyktntt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ybcxt.top/Article/details/gtkkfkjslg.html

[U60] PHP：JSON 编解码
来源：http://dali.chenzaomai.com/Article/details/gtavvvohtc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.tianlin.xyz/Article/details/gtrpqtbicx.html

[U61] PHP：正则
来源：http://dali.wangdashe.top/Article/details/gtlgasuoka.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtiqfffwci.html

[U62] PHP：日期对象
来源：http://dali.gaohongyu789.top/Article/details/gtfxyxgsbr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xuanzx.com/Article/details/gtjqkijrvc.html

[U63] PHP：文件读写
来源：http://dali.svipenyu.cn/Article/details/gtgrjbfxxx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.nanxuanxn.top/Article/details/gtsyhkuabb.html

[U64] PHP：目录遍历
来源：http://dali.andypj.xyz/Article/details/gtbkbnebcg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gzhubu.top/Article/details/gttskphrae.html

[U65] PHP：会话
来源：http://dali.aibaodan.cn/Article/details/gtydtttyvz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gttzkjzyyi.html

[U66] PHP：设置 Cookie
来源：http://dali.quarkkingdee.top/Article/details/gttqmcqkcj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinqigufen.top/Article/details/gtnozwooae.html

[U67] PHP：处理文件上传
来源：http://dali.haohaochexian.top/Article/details/gtbzpemkcg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cdnleiting.top/Article/details/gtxqhvraav.html

[U68] PHP：PDO 连接
来源：http://dali.ydzc1.top/Article/details/gtmfdodhsz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezengyka.html

[U69] PHP：PDO 预处理
来源：http://dali.yj20258888.top/Article/details/gtuhsozvxh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gotoacloud.top/Article/details/gtqdkssmdp.html

[U70] PHP：PDO 事务
来源：http://dali.guannengcc.top/Article/details/gtoffbzqfi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yongpay.top/Article/details/gtzorsiiyy.html

[U71] PHP：抛出异常
来源：http://dali.gzhubu.top/Article/details/gtmqzolpzi.html

throw new RuntimeException("失败", 500);
来源：http://dali.xuanzx.com/Article/details/gtqvfyechl.html

[U72] PHP：写错误日志
来源：http://dali.yj20258.top/Article/details/gtwcwlzgqu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhoulong.xyz/Article/details/gtorbnkdfx.html

[U73] PHP：读取 ini 配置
来源：http://dali.sxryk.cn/Article/details/gtbopjzovd.html

parse_ini_file("config.ini", true)
来源：http://dali.wangdashe.top/Article/details/gttoebuhja.html

[U74] PHP：读取环境变量
来源：http://dali.daria6918.cn/Article/details/gtkfpkvraw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj202588.top/Article/details/gtvnebgfjl.html

[U75] PHP：依赖注入
来源：http://dali.mhx1999.top/Article/details/gtqytzfsnv.html

composer require psr/container
来源：http://dali.hongshengwenyu.top/Article/details/gtdeelqwis.html

[U76] PHP：简单路由
来源：http://dali.ppjwa.cn/Article/details/gtufdqchbm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jianghu66.top/Article/details/gtiaveqnxs.html

[U77] PHP：模板渲染
来源：http://dali.xuetiantiany.cn/Article/details/gtamucmurb.html

composer require twig/twig
来源：http://dali.tian-w.cn/Article/details/gtafpyxxgu.html

[U78] PHP：单元测试
来源：http://dali.jqgfzy.top/Article/details/gtcnntrrqj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhoulong.xyz/Article/details/gtlgcbbnlu.html


<!-- 参考信息 -->