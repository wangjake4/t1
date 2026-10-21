代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.meibo888.top/Article/details/gtpcuspley.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shzxlz.cn/Article/details/gtxukeghxa.html

[S48] C++：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtumfdwqgk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuxming.cn/Article/details/gtjljzzpov.html

while (std::getline(in, line)) { }
来源：http://dali.quarkkingdee.top/Article/details/gticjyfecy.html

[S49] C++：写文件
来源：http://dali.daria6918.cn/Article/details/gtkenyxxzw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuxming.cn/Article/details/gtypogoqte.html

[S50] C++：格式化数字
来源：http://dali.yuxming.cn/Article/details/gtyrasydvv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtncbgfjca.html

[S51] C++：显式类型转换
来源：http://dali.xylfe.cn/Article/details/gtyijfkchz.html

static_cast<double>(a) / b
来源：http://dali.ehwqpu.com/Article/details/gtmvntmfum.html

[S52] C++：const 与 noexcept
来源：http://dali.yanxiufei.cn/Article/details/gtifgdhrbo.html

int size() const noexcept { return n_; }
来源：http://dali.xylfe.cn/Article/details/gtxjfxbvmd.html

[S53] C++：移动语义
来源：http://dali.tian-w.cn/Article/details/gtgdaqwkuz.html

std::vector<int> w = std::move(v);
来源：http://dali.nwbrower.top/Article/details/gtpcvwhgdi.html

[S54] C++：异常处理
来源：http://dali.guannengcc.top/Article/details/gtrdsleomc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cheryme.top/Article/details/gtikbouqov.html

[S55] C++：结构化绑定
来源：http://dali.ppjwa.cn/Article/details/gtxlmbsete.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtldujbton.html

[S56] C++：optional
来源：http://dali.snrcjt.cn/Article/details/gtlmtvqxag.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcfqhzhqe.html

[S57] C++：编译期常量
来源：http://dali.hnxiangtu.top/Article/details/gtjxkmblxr.html

constexpr int N = 10;
来源：http://dali.yvedp.cn/Article/details/gtvxuzrkvu.html

[S58] C++：命名空间
来源：http://dali.zycfv.cn/Article/details/gtdqfycbag.html

namespace ns { int f() { return 1; } }
来源：http://dali.xuanzx.com/Article/details/gtpomdsdax.html

[S59] C++：静态断言
来源：http://dali.tian-w.cn/Article/details/gtlfhgzgez.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.redwolf501.top/Article/details/gtbmzqvzli.html

[S60] C++：遍历并删除元素
来源：http://dali.svipenyu.cn/Article/details/gtgbsgdeeu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.smart0.xyz/Article/details/gtbnafimwo.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtddiwzgrb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxuanxn.top/Article/details/gttkrgsplg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtynqahlto.html

[T01] Kotlin：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtvwhcnpfr.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gttdwnmeea.html

[T02] Kotlin：变量
来源：http://dali.jinqigufen.top/Article/details/gtmozhenur.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cucudq.cn/Article/details/gtkfbeutvp.html

[T03] Kotlin：字符串模板
来源：http://dali.ydzc1.top/Article/details/gtydyoyocq.html

"值: $b"
来源：http://dali.daxiang520.top/Article/details/gtfccjwhze.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujdshlzr.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gtgfddqljb.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gtoiqalpsw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhiwuduotai.top/Article/details/gtcokecwus.html

[T06] Kotlin：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gtukpaxcin.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sweek.top/Article/details/gtsanejpwj.html

[T07] Kotlin：集合过滤
来源：http://dali.fengsongda.top/Article/details/gtccpvgwxv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.vqdsnc.cn/Article/details/gthenlfyjx.html

[T08] Kotlin：数据类
来源：http://dali.shangyingyoupin.top/Article/details/gtghwyxpym.html

data class User(val name: String, val age: Int)
来源：http://dali.tanke756.top/Article/details/gtxrcttfzt.html

[T09] Kotlin：扩展函数
来源：http://dali.ydzc1.top/Article/details/gtsrnjryec.html

fun String.exclaim() = this + "!"
来源：http://dali.xziqi.cn/Article/details/gtulbwixbp.html

[T10] Kotlin：默认参数
来源：http://dali.gaohongyu789.top/Article/details/gtsprzyqln.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwcrmhyj.html

[T11] Kotlin：协程
来源：http://dali.gzhubu.top/Article/details/gttoiqwsjy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daxiang520.top/Article/details/gtpuhwetti.html

[T12] Kotlin：解构声明
来源：http://dali.sufxvd.cn/Article/details/gtsghwixzn.html

val (a, b) = Pair(1, 2)
来源：http://dali.316326.xyz/Article/details/gtwatbbvao.html

[T13] Kotlin：只读 Map
来源：http://dali.sysykeji.top/Article/details/gtxabxpuyo.html

val m = mapOf("a" to 1)
来源：http://dali.jianghu66.top/Article/details/gtzvgmemoe.html

[T14] Kotlin：循环
来源：http://dali.mhx1999.top/Article/details/gtsugnxegp.html

for (i in 1..10) println(i)
来源：http://dali.xuanzx.com/Article/details/gtzpzfqqvg.html

[T15] Kotlin：接口
来源：http://dali.zycfv.cn/Article/details/gtbccndtlu.html

interface Shape { fun area(): Double }
来源：http://dali.hysaishi.cn/Article/details/gtewymjslj.html

[T16] Swift：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtbdjxqqhn.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gtjleyciko.html

[T17] Swift：变量与常量
来源：http://dali.cheryme.top/Article/details/gtzxyamgiv.html

var a = 1;  let b = 2
来源：http://dali.cashguo.top/Article/details/gtbeaokofz.html

[T18] Swift：字符串插值
来源：http://dali.tanke756.top/Article/details/gtmtjcvwum.html

"值: \(b)"
来源：http://dali.sysykeji.top/Article/details/gtpbtvtjqx.html

[T19] Swift：可选绑定
来源：http://dali.tanke756.top/Article/details/gtqmnwljom.html

if let n = opt { print(n) }
来源：http://dali.nanxuanxn.top/Article/details/gtsfciycxw.html

[T20] Swift：数组操作
来源：http://dali.andypj.xyz/Article/details/gtwnxpgnjw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hfpthk.cn/Article/details/gtqgnkxbte.html

[T21] Swift：遍历
来源：http://dali.snrcjt.cn/Article/details/gtsieismvw.html

for x in a { print(x) }
来源：http://dali.jlsjyb.cn/Article/details/gtvysqmqde.html

[T22] Swift：字典
来源：http://dali.jianghu66.top/Article/details/gtinudtxtk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cdnleiting.top/Article/details/gttxqwuwgh.html

[T23] Swift：函数
来源：http://dali.zhengqikj.top/Article/details/gtnjvvxrae.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtwsdaquwn.html

[T24] Swift：闭包
来源：http://dali.nanxuanxn.top/Article/details/gtqqoqllyt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtbklazpzo.html

[T25] Swift：结构体
来源：http://dali.snrcjt.cn/Article/details/gticrpclfz.html

struct P { var x: Int }
来源：http://dali.pycfn.com/Article/details/gtggtqwcks.html

[T26] Swift：类与重写
来源：http://dali.ydzc1.top/Article/details/gtovfxswej.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gtchcxvdnm.html

[T27] Swift：错误处理
来源：http://dali.dashuyun.cn/Article/details/gtidegttru.html

do { try f() } catch { print(error) }
来源：http://dali.9152youxi.cn/Article/details/gtvzqdyryw.html

[T28] Swift：枚举
来源：http://dali.nanxinkj.top/Article/details/gtgaqvetcr.html

enum Color { case red, green }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhxfecnj.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxinkj.top/Article/details/gtqqtqsqpn.html

guard let x = opt else { return }
来源：http://dali.shuidangran.top/Article/details/gttjizrjsr.html

[T30] Swift：协议
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxltlnfi.html

protocol Shape { func area() -> Double }
来源：http://dali.guowangkeji.top/Article/details/gtgzxdbqcn.html

[T31] Lua：Hello World
来源：http://dali.yueranfly.top/Article/details/gtnkoztylg.html

print("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtftaswunp.html

[T32] Lua：局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtnmvbawer.html

local a = 1
来源：http://dali.ydzc1.top/Article/details/gtyfhmilwf.html

[T33] Lua：表（数组）
来源：http://dali.ybcxt.top/Article/details/gtnduvwxwr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xuetiantiany.cn/Article/details/gtinzeswiu.html

[T34] Lua：遍历表
来源：http://dali.snrcjt.cn/Article/details/gtdbqmannt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangdashe.top/Article/details/gtzvswtivf.html

[T35] Lua：字典表
来源：http://dali.yj202588.top/Article/details/gthcltkvyl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.c1oappe.top/Article/details/gtuiadffff.html

[T36] Lua：函数
来源：http://dali.hnxiangtu.top/Article/details/gtoxakecua.html

function add(a, b) return a + b end
来源：http://dali.yongpay.top/Article/details/gtmtehtlks.html

[T37] Lua：字符串拼接
来源：http://dali.hywenlv.cn/Article/details/gtaeohgakx.html

"a" .. "b"
来源：http://dali.zhoulong.xyz/Article/details/gtxxyxebqj.html

[T38] Lua：条件
来源：http://dali.meibo888.top/Article/details/gtxzqfjwfg.html

if x > 0 then print("正") end
来源：http://dali.yangfankeji.com/Article/details/gttvgmfscy.html

[T39] Lua：模式匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfzppcmx.html

string.find(s, "%d+")
来源：http://dali.iojbl.cn/Article/details/gtbuifrsrc.html

[T40] Lua：元表
来源：http://dali.hnxiangtu.top/Article/details/gthatmiacs.html

setmetatable({}, { __index = base })
来源：http://dali.cqqwz.cn/Article/details/gtitdhihru.html

[T41] Perl：Hello World
来源：http://dali.fzhhl.top/Article/details/gtcalfeijd.html

print "Hello\n";
来源：http://dali.wangshuangyany.cn/Article/details/gttddrcrgw.html

[T42] Perl：变量类型
来源：http://dali.hysaishi.cn/Article/details/gtpuspebih.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtqugrbdrg.html

[T43] Perl：字符串插值
来源：http://dali.redwolf501.top/Article/details/gtzuoktudf.html

"值: $a"
来源：http://dali.shuidangran.top/Article/details/gtmashhdwv.html

[T44] Perl：条件
来源：http://dali.zhongyouzk.top/Article/details/gtjhnkfgiv.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhpahyla.html

[T45] Perl：数组遍历
来源：http://dali.xuanzx.com/Article/details/gtltyhszdi.html

for my $x (@arr) { print $x; }
来源：http://dali.cucudq.cn/Article/details/gtwwiberwi.html

[T46] Perl：哈希操作
来源：http://dali.hfpthk.cn/Article/details/gthyujwpbd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hnqzz.top/Article/details/gtlmauikzm.html

[T47] Perl：正则捕获
来源：http://dali.zhengqikj.top/Article/details/gtajxgaxku.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sweek.top/Article/details/gthdalofdg.html

[T48] Perl：正则替换
来源：http://dali.gogol.net.cn/Article/details/gthldpxzhe.html

$s =~ s/old/new/g;
来源：http://dali.hnqzz.top/Article/details/gtdahaiiey.html

[T49] Perl：函数
来源：http://dali.xylfe.cn/Article/details/gttugmubnh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgnojpsn.html

[T50] Perl：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gthviyywoo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hongshengwenyu.top/Article/details/gtggktcdcn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtvhiuvv.html

[T51] Scala：Hello World
来源：http://dali.birdmap.top/Article/details/gtiisazrdk.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtfawqvxhh.html

[T52] Scala：变量
来源：http://dali.smart0.xyz/Article/details/gtphebbvgr.html

val a = 1;  var b = 2
来源：http://dali.hammf.cn/Article/details/gtceymyyll.html

[T53] Scala：字符串插值
来源：http://dali.yj202588.top/Article/details/gtaikpywct.html

s"值: $b"
来源：http://dali.dashuyun.cn/Article/details/gtayasfift.html

[T54] Scala：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gthttqgfjw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daria6918.cn/Article/details/gtzmqocxwa.html

[T55] Scala：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gtuokcubow.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tian-w.cn/Article/details/gtdixucahq.html

[T56] Scala：样例类
来源：http://dali.zhoulong.xyz/Article/details/gtjxujhnia.html

case class User(name: String, age: Int)
来源：http://dali.gogol.net.cn/Article/details/gtdajxynev.html

[T57] Scala：模式匹配
来源：http://dali.meibo888.top/Article/details/gtiuwftjrz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cqqwz.cn/Article/details/gtzmqhtsqu.html

[T58] Scala：函数定义
来源：http://dali.yonumen.top/Article/details/gtvpmmnmml.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtwpiryypt.html

[T59] Scala：循环
来源：http://dali.yj20258.top/Article/details/gtqqnoggcz.html

for (i <- 1 to 10) println(i)
来源：http://dali.cashguo.top/Article/details/gtuncsaftw.html

[T60] Scala：折叠
来源：http://dali.jlsjyb.cn/Article/details/gtnbgsusfs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuanzx.com/Article/details/gtwzxmiraz.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtwofqirtd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yueranfly.top/Article/details/gthmghsadm.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtlhojqyuf.html

[U01] Py：创建虚拟环境
来源：http://dali.yj202588.top/Article/details/gtrcauydgs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.meibo888.top/Article/details/gtsrypcnru.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sxryk.cn/Article/details/gtkcfwpoog.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.mhx1999.top/Article/details/gtubbtmeld.html

[U03] Py：加载 .env 配置
来源：http://dali.gogol.net.cn/Article/details/gtnxfjuqsp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hnxiangtu.top/Article/details/gtsysecnqd.html

[U04] Py：变量调试打印
来源：http://dali.shangyingyoupin.top/Article/details/gtgbgumtmh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hammf.cn/Article/details/gtsherpcck.html

[U05] Py：列表去重且保序
来源：http://dali.zhongyouzk.top/Article/details/gtabubrfhc.html

list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gtpuwquizw.html

[U06] Py：合并两个字典
来源：http://dali.cdnleiting.top/Article/details/gtgcawqfen.html

{**a, **b}
来源：http://dali.birdmap.top/Article/details/gtsdoajgua.html

[U07] Py：反转字典键值
来源：http://dali.vqdsnc.cn/Article/details/gtizgwhflp.html

{v: k for k, v in d.items()}
来源：http://dali.quarkkingdee.top/Article/details/gtrkjodcbp.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzqgyumb.html

[y for x in nested for y in x]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafuswkla.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigfzy.top/Article/details/gtwsmbayhy.html

max(d, key=d.get)
来源：http://dali.feifeiyinyue.top/Article/details/gtpcdfspar.html

[U10] Py：按值排序字典
来源：http://dali.wangshuangyany.cn/Article/details/gtihcyebrk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nanxuanxn.top/Article/details/gtnqvqsizf.html

[U11] Py：生成器表达式
来源：http://dali.jyoumei.cn/Article/details/gtdwvwwihx.html

(x * 2 for x in arr)
来源：http://dali.smart0.xyz/Article/details/gtakbvefbd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.smart0.xyz/Article/details/gtvzzprfvx.html

Counter(arr).most_common(3)
来源：http://dali.yuxming.cn/Article/details/gtayeyousa.html

[U13] Py：固定长度队列
来源：http://dali.pengpengdd.cyou/Article/details/gtytqkpxyi.html

deque(maxlen=10)
来源：http://dali.nwbrower.top/Article/details/gtlxfqzvod.html

[U14] Py：分组收集到列表
来源：http://dali.chenjidiqi.icu/Article/details/gtortsmfun.html

defaultdict(list)
来源：http://dali.smart0.xyz/Article/details/gtemsfcivt.html

[U15] Py：高精度计时
来源：http://dali.hysaishi.cn/Article/details/gtpzaagqhx.html

t = time.perf_counter()
来源：http://dali.mhx1999.top/Article/details/gtgwjtlfhv.html

[U16] Py：命令行参数解析
来源：http://dali.dianchejie.cn/Article/details/gtwovsljrg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cheryme.top/Article/details/gtrmxnkizk.html

[U17] Py：初始化日志
来源：http://dali.ybcxt.top/Article/details/gtvaktxnkp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.smart0.xyz/Article/details/gtycxudvmk.html

[U18] Py：预编译正则
来源：http://dali.ydzc1.top/Article/details/gtqkiircwh.html

pat = re.compile(r"\d+")
来源：http://dali.haohaochexian.top/Article/details/gtulforrqo.html

[U19] Py：正则替换带回调
来源：http://dali.pycfn.com/Article/details/gtgcguqhby.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhoulong.xyz/Article/details/gteicaprvh.html

[U20] Py：缓存函数结果
来源：http://dali.yanxiufei.cn/Article/details/gtujukguwt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jianghu66.top/Article/details/gtefyhgdjd.html

[U21] Py：自定义上下文管理器
来源：http://dali.tianlin.xyz/Article/details/gtvixemrfa.html

@contextlib.contextmanager
来源：http://dali.haohaochexian.top/Article/details/gtjqubsuut.html

[U22] Py：矩阵转置
来源：http://dali.dianchejie.cn/Article/details/gteufnjvgv.html

list(zip(*m))
来源：http://dali.sxryk.cn/Article/details/gthdtfunqx.html

[U23] Py：分块读取大文件
来源：http://dali.snrcjt.cn/Article/details/gtjluwyysz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gaohongyu789.top/Article/details/gtrxhoouwn.html

[U24] Py：路径操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpnjsmbl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jianghu66.top/Article/details/gtgubnzvyi.html

[U25] Py：CSV 按字典读
来源：http://dali.sweek.top/Article/details/gtwfkkslel.html

csv.DictReader(f)
来源：http://dali.cqqwz.cn/Article/details/gtpoufqntk.html

[U26] Py：并发下载
来源：http://dali.snrcjt.cn/Article/details/gtcbalkgvs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cdnleiting.top/Article/details/gtockyiyxz.html

[U27] Py：异步 HTTP
来源：http://dali.fzhhl.top/Article/details/gtaqtipeeb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ppjwa.cn/Article/details/gtzvwblsyj.html

[U28] Py：类型别名
来源：http://dali.yangfankeji.com/Article/details/gtwifpoqxg.html

UserId = int
来源：http://dali.daxiang520.top/Article/details/gtaayjktsh.html

[U29] Py：属性校验
来源：http://dali.meibo888.top/Article/details/gtjhzfggwg.html

@property 与 @x.setter 配合
来源：http://dali.guowangkeji.top/Article/details/gtnejxenjn.html

[U30] Py：数据类
来源：http://dali.yvedp.cn/Article/details/gtebfkzwap.html

@dataclass(slots=True)
来源：http://dali.ydzc1.top/Article/details/gtrtbumrie.html

[U31] Py：单测
来源：http://dali.c1oappe.top/Article/details/gtmxpsmeaz.html

python -m pytest -q
来源：http://dali.nanxuanxn.top/Article/details/gtirqqdzbr.html

[U32] Py：代码格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtnmpkeguy.html

ruff format . && ruff check --fix .
来源：http://dali.yj202588.top/Article/details/gtbidoiqih.html

[U33] Py：打包发布
来源：http://dali.vqdsnc.cn/Article/details/gtsmmllltv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenlongwang.top/Article/details/gtbubmmxuo.html

[U34] Py：判断编码
来源：http://dali.havefunace.top/Article/details/gtrybtjsvu.html

chardet.detect(raw)
来源：http://dali.cqqwz.cn/Article/details/gtupcypofh.html

[U35] Py：发送邮件
来源：http://dali.smart0.xyz/Article/details/gtgkcasgoz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.mhx1999.top/Article/details/gthbbbhcck.html

[U36] Py：定时任务
来源：http://dali.gzhubu.top/Article/details/gtlzhsnicj.html

schedule.every(10).minutes.do(job)
来源：http://dali.jiagoushi.top/Article/details/gtmqtrpdix.html

[U37] Py：读写 Excel
来源：http://dali.iojbl.cn/Article/details/gtlgxkgbci.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.pengpengdd.cyou/Article/details/gtvctdpjzb.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkwwblzq.html

Path(__file__).resolve().parent
来源：http://dali.xziqi.cn/Article/details/gtxzfhdzyh.html

[U39] Py：判断是否在交互环境
来源：http://dali.gzhubu.top/Article/details/gtwwkakrwd.html

sys.stdout.isatty()
来源：http://dali.jinqigfzy.top/Article/details/gtqhegqksf.html

[U40] Py：打印到标准错误
来源：http://dali.feifeiyinyue.top/Article/details/gtpxegucdq.html

print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gtwaklmpwx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhongyouzk.top/Article/details/gtiztmphlo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shanyushiyangtech.top/Article/details/gtwssdifnl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jlsjyb.cn/Article/details/gtdzzunivv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.chenlongwang.top/Article/details/gtiqisorgx.html

[U43] PHP：声明命名空间
来源：http://dali.0kj1m.cn/Article/details/gtqefwmwgc.html

namespace App\Http;
来源：http://dali.yvedp.cn/Article/details/gtawmgzmof.html

[U44] PHP：开启严格类型
来源：http://dali.jianghu66.top/Article/details/gtdsmumndo.html

declare(strict_types=1);
来源：http://dali.dianchejie.cn/Article/details/gtoaiitwww.html

[U45] PHP：类型声明与返回类型
来源：http://dali.sweek.top/Article/details/gtfvnznktk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gthrrcmrlq.html

[U46] PHP：可空类型
来源：http://dali.feifeiyinyue.top/Article/details/gtmmhjbkhs.html

?string $name = null
来源：http://dali.yj20258.top/Article/details/gtjsyaktrx.html

[U47] PHP：联合类型
来源：http://dali.nanxuanxn.top/Article/details/gtgyybsjvp.html

int|string $id
来源：http://dali.dianchejie.cn/Article/details/gtysshekmw.html

[U48] PHP：纯枚举
来源：http://dali.hongshengwenyu.top/Article/details/gtxketlcee.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yongpay.top/Article/details/gtjmpzmnsv.html

[U49] PHP：只读属性
来源：http://dali.daxiang520.top/Article/details/gttfvwwkop.html

public readonly string $name
来源：http://dali.quarkkingdee.top/Article/details/gtkaooujcg.html

[U50] PHP：构造器属性提升
来源：http://dali.cashguo.top/Article/details/gtcupmqvif.html

public function __construct(private int $id) {}
来源：http://dali.zycfv.cn/Article/details/gtsuzhmaok.html

[U51] PHP：数组解构
来源：http://dali.daria6918.cn/Article/details/gtisumwfcr.html

[$a, $b] = $arr;
来源：http://dali.zhengqikj.top/Article/details/gtwipegwmn.html

[U52] PHP：箭头函数
来源：http://dali.zhoulong.xyz/Article/details/gtxpzuadxu.html

$double = fn($x) => $x * 2;
来源：http://dali.zycfv.cn/Article/details/gtqpsfcbir.html

[U53] PHP：空合并运算符
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrejszzjt.html

$v = $a ?? $b ?? "default";
来源：http://dali.nwbrower.top/Article/details/gtwvndzktv.html

[U54] PHP：空安全调用
来源：http://dali.zycfv.cn/Article/details/gtumzhvsns.html

$obj?->method()
来源：http://dali.snrcjt.cn/Article/details/gtxszkgkku.html

[U55] PHP：match 表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtexwmfslc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhixingplan.top/Article/details/gtlawweivp.html

[U56] PHP：命名参数
来源：http://dali.yonumen.top/Article/details/gtkixjkgsw.html

f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gtmqtvmxeq.html

[U57] PHP：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtixxajkri.html

"值: {$a}"
来源：http://dali.chenzaomai.com/Article/details/gtdigemfyc.html

[U58] PHP：数组三件套
来源：http://dali.kuanghao11.cn/Article/details/gtfrujujbw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.svipenyu.cn/Article/details/gtuaqsuhxo.html

[U59] PHP：自定义排序
来源：http://dali.shuidangran.top/Article/details/gtzitslnkv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuxming.cn/Article/details/gthoahvrvg.html

[U60] PHP：JSON 编解码
来源：http://dali.bjfxy.top/Article/details/gtjcfiamnm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xuanzx.com/Article/details/gtksdfdnps.html

[U61] PHP：正则
来源：http://dali.vqdsnc.cn/Article/details/gtgvxvnceg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gtowsaarih.html

[U62] PHP：日期对象
来源：http://dali.fzhhl.top/Article/details/gtfqpbviiw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yongpay.top/Article/details/gtdhnzdjcj.html

[U63] PHP：文件读写
来源：http://dali.gzhubu.top/Article/details/gtxmweudbo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhengqikj.top/Article/details/gtcrpaefwa.html

[U64] PHP：目录遍历
来源：http://dali.hammf.cn/Article/details/gtnvhfehta.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cheryme.top/Article/details/gtqotmgcge.html

[U65] PHP：会话
来源：http://dali.jiagoushi.top/Article/details/gtklrxrgul.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtkssvxrgh.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gtgqflbqpx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtqiavkxeg.html

[U67] PHP：处理文件上传
来源：http://dali.c1oappe.top/Article/details/gtxeyxseue.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yj20258.top/Article/details/gtqpchdmyb.html

[U68] PHP：PDO 连接
来源：http://dali.hnxiangtu.top/Article/details/gtifneeazb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenlongwang.top/Article/details/gthpamkeuu.html

[U69] PHP：PDO 预处理
来源：http://dali.nanxinkj.top/Article/details/gtprhqckge.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hnqzz.top/Article/details/gtbscycbic.html

[U70] PHP：PDO 事务
来源：http://dali.cucudq.cn/Article/details/gtjogtjtrr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.316326.xyz/Article/details/gtqsolidle.html

[U71] PHP：抛出异常
来源：http://dali.aizwys.cn/Article/details/gtrnsioeos.html

throw new RuntimeException("失败", 500);
来源：http://dali.gogol.net.cn/Article/details/gtfiskyhmk.html

[U72] PHP：写错误日志
来源：http://dali.nanxuanxn.top/Article/details/gtuzjkagtc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfdwqunq.html


<!-- 参考信息 -->