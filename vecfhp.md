代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.316326.xyz/Article/details/gtywtwmxnd.html

[S49] C++：写文件
来源：http://dali.ivvv.top/Article/details/gtgpgzovnu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhiwuduotai.top/Article/details/gthrettqca.html

[S50] C++：格式化数字
来源：http://dali.zhongyouzk.top/Article/details/gtqpdpornj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtsrkkxcot.html

[S51] C++：显式类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gtdzpekuiz.html

static_cast<double>(a) / b
来源：http://dali.tian-w.cn/Article/details/gtyiqjxkbe.html

[S52] C++：const 与 noexcept
来源：http://dali.jiagoushi.top/Article/details/gtbnwgcwoq.html

int size() const noexcept { return n_; }
来源：http://dali.jiagoushi.top/Article/details/gtlacuumco.html

[S53] C++：移动语义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayuvmxwv.html

std::vector<int> w = std::move(v);
来源：http://dali.yanxiufei.cn/Article/details/gtctoqaqdm.html

[S54] C++：异常处理
来源：http://dali.zhongyouzk.top/Article/details/gtoomgkygk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sufxvd.cn/Article/details/gtvgkkkbhs.html

[S55] C++：结构化绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdzszoxm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfysfidrj.html

[S56] C++：optional
来源：http://dali.wangshuangyany.cn/Article/details/gtkyuxuajj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pycfn.com/Article/details/gtxnorjunz.html

[S57] C++：编译期常量
来源：http://dali.birdmap.top/Article/details/gttyngxplx.html

constexpr int N = 10;
来源：http://dali.yuxming.cn/Article/details/gtcstxdgwr.html

[S58] C++：命名空间
来源：http://dali.ivvv.top/Article/details/gtpuvulear.html

namespace ns { int f() { return 1; } }
来源：http://dali.bjfxy.top/Article/details/gtioxomcjs.html

[S59] C++：静态断言
来源：http://dali.jiagoushi.top/Article/details/gtvxawqukk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenzaomai.com/Article/details/gtvwpatlya.html

[S60] C++：遍历并删除元素
来源：http://dali.yuanzhike.top/Article/details/gtqctamxwd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.9152youxi.cn/Article/details/gtcnwpiexp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtyjrvazny.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.vqdsnc.cn/Article/details/gtlplubvls.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtcyoapcsg.html

[T01] Kotlin：Hello World
来源：http://dali.yuxming.cn/Article/details/gtlfreqczq.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gtmxqxamdi.html

[T02] Kotlin：变量
来源：http://dali.xziqi.cn/Article/details/gtlbrgfusc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zdqjudy.top/Article/details/gtmkotpnfv.html

[T03] Kotlin：字符串模板
来源：http://dali.dianchejie.cn/Article/details/gtgudcjzco.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gtmprfeasy.html

[T04] Kotlin：空安全
来源：http://dali.ywan-chungtsiang.top/Article/details/gtblcfdxgf.html

val n: String? = null;  n?.length
来源：http://dali.cheryme.top/Article/details/gtgbfeboib.html

[T05] Kotlin：when 表达式
来源：http://dali.guannengcc.top/Article/details/gttpytfine.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzwbfcnr.html

[T06] Kotlin：集合映射
来源：http://dali.havefunace.top/Article/details/gthybjmmas.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pycfn.com/Article/details/gtolacaect.html

[T07] Kotlin：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gtqkaokkct.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuanzx.com/Article/details/gttelusyvn.html

[T08] Kotlin：数据类
来源：http://dali.zhongyouzk.top/Article/details/gtwopcufrf.html

data class User(val name: String, val age: Int)
来源：http://dali.sxryk.cn/Article/details/gtswwpbvdj.html

[T09] Kotlin：扩展函数
来源：http://dali.dianchejie.cn/Article/details/gtwwrsnkux.html

fun String.exclaim() = this + "!"
来源：http://dali.316326.xyz/Article/details/gtjnrmgmmn.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvmhteah.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dashuyun.cn/Article/details/gtesfkqpfw.html

[T11] Kotlin：协程
来源：http://dali.zhoulong.xyz/Article/details/gtwologzvs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhongyouzk.top/Article/details/gtxgohgjoj.html

[T12] Kotlin：解构声明
来源：http://dali.smart0.xyz/Article/details/gtwflpdaks.html

val (a, b) = Pair(1, 2)
来源：http://dali.yvedp.cn/Article/details/gtpvxrrjjt.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmnqmywb.html

val m = mapOf("a" to 1)
来源：http://dali.svipenyu.cn/Article/details/gtwevvzxiw.html

[T14] Kotlin：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobivdrtc.html

for (i in 1..10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gtehzfcwsw.html

[T15] Kotlin：接口
来源：http://dali.quarkkingdee.top/Article/details/gtxhlvubqf.html

interface Shape { fun area(): Double }
来源：http://dali.jqgfzy.top/Article/details/gtdssfyxgd.html

[T16] Swift：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtagnlbjew.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtzlqbszio.html

[T17] Swift：变量与常量
来源：http://dali.shangyingyoupin.top/Article/details/gtgisvsvuf.html

var a = 1;  let b = 2
来源：http://dali.kuanghao11.cn/Article/details/gtgflwdejc.html

[T18] Swift：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtjuqemfpn.html

"值: \(b)"
来源：http://dali.zhiwuduotai.top/Article/details/gtpqqogpqi.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gtffmiofnp.html

if let n = opt { print(n) }
来源：http://dali.dashuyun.cn/Article/details/gtgoqgkfbl.html

[T20] Swift：数组操作
来源：http://dali.havefunace.top/Article/details/gtwbjtnold.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenjidiqi.icu/Article/details/gtnpjufuxm.html

[T21] Swift：遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmnptrmm.html

for x in a { print(x) }
来源：http://dali.yj20258888.top/Article/details/gtklowuitz.html

[T22] Swift：字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkahqrix.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ppjwa.cn/Article/details/gtbrkowinw.html

[T23] Swift：函数
来源：http://dali.sufxvd.cn/Article/details/gtsonfcvnz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuxming.cn/Article/details/gtuajljsox.html

[T24] Swift：闭包
来源：http://dali.yvedp.cn/Article/details/gthatlbhcw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shuidangran.top/Article/details/gtsqovozzk.html

[T25] Swift：结构体
来源：http://dali.quarkkingdee.top/Article/details/gtutnfdlwg.html

struct P { var x: Int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwckykjh.html

[T26] Swift：类与重写
来源：http://dali.fzhhl.top/Article/details/gttvqprrwn.html

class A: Base { override func f() {} }
来源：http://dali.c1oappe.top/Article/details/gtlwzgwiod.html

[T27] Swift：错误处理
来源：http://dali.mhx1999.top/Article/details/gtjabchkja.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdinjwkcj.html

[T28] Swift：枚举
来源：http://dali.yuxming.cn/Article/details/gtwisteizp.html

enum Color { case red, green }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdkoakxds.html

[T29] Swift：guard 提前返回
来源：http://dali.chenlongwang.top/Article/details/gtutwjtwuc.html

guard let x = opt else { return }
来源：http://dali.xuetiantiany.cn/Article/details/gtrxsabwoa.html

[T30] Swift：协议
来源：http://dali.dashuyun.cn/Article/details/gtirnapamd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhoulong.xyz/Article/details/gtckievnyo.html

[T31] Lua：Hello World
来源：http://dali.gogol.net.cn/Article/details/gttlkltngs.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtujmahgom.html

[T32] Lua：局部变量
来源：http://dali.daxiang520.top/Article/details/gtxehklkmw.html

local a = 1
来源：http://dali.yanxiufei.cn/Article/details/gtbuteywzu.html

[T33] Lua：表（数组）
来源：http://dali.svipenyu.cn/Article/details/gttjkfaowo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrbeqpqv.html

[T34] Lua：遍历表
来源：http://dali.nwbrower.top/Article/details/gtrqqxeomv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.9152youxi.cn/Article/details/gtisliltxn.html

[T35] Lua：字典表
来源：http://dali.aizwys.cn/Article/details/gtbqinvqfg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.316326.xyz/Article/details/gtchrwdjof.html

[T36] Lua：函数
来源：http://dali.tian-w.cn/Article/details/gtaoggpmdu.html

function add(a, b) return a + b end
来源：http://dali.pengpengdd.cyou/Article/details/gtpfqnraht.html

[T37] Lua：字符串拼接
来源：http://dali.jlsjyb.cn/Article/details/gtzqnqvsun.html

"a" .. "b"
来源：http://dali.iojbl.cn/Article/details/gtbeccvfkx.html

[T38] Lua：条件
来源：http://dali.feifeiyinyue.top/Article/details/gtacavntth.html

if x > 0 then print("正") end
来源：http://dali.xuetiantiany.cn/Article/details/gtkjytwhyk.html

[T39] Lua：模式匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmqghrii.html

string.find(s, "%d+")
来源：http://dali.zdqjudy.top/Article/details/gtimxumqbj.html

[T40] Lua：元表
来源：http://dali.chenlongwang.top/Article/details/gtkbrucpbd.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigfzy.top/Article/details/gtlunagxog.html

[T41] Perl：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtvrjhpwsu.html

print "Hello\n";
来源：http://dali.kuanghao11.cn/Article/details/gtvosyhnyd.html

[T42] Perl：变量类型
来源：http://dali.xziqi.cn/Article/details/gtjhulrupk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sufxvd.cn/Article/details/gtwgxzwexz.html

[T43] Perl：字符串插值
来源：http://dali.yuxming.cn/Article/details/gtajdsuaua.html

"值: $a"
来源：http://dali.tianlin.xyz/Article/details/gtgcvrnowb.html

[T44] Perl：条件
来源：http://dali.ivvv.top/Article/details/gthvesxvih.html

if ($a > 0) { print "正"; }
来源：http://dali.yonumen.top/Article/details/gtfhxpaygu.html

[T45] Perl：数组遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtsdokeagz.html

for my $x (@arr) { print $x; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjoaguqbj.html

[T46] Perl：哈希操作
来源：http://dali.ehwqpu.com/Article/details/gtsriglucb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxinkj.top/Article/details/gttbrvyryg.html

[T47] Perl：正则捕获
来源：http://dali.bjfxy.top/Article/details/gtxevpbcry.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yuxming.cn/Article/details/gtajtmscpu.html

[T48] Perl：正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtinkroqur.html

$s =~ s/old/new/g;
来源：http://dali.cucudq.cn/Article/details/gtubcnogoq.html

[T49] Perl：函数
来源：http://dali.cqqwz.cn/Article/details/gtshcrpcat.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtgkzydhai.html

[T50] Perl：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtbgdjsdft.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hywenlv.cn/Article/details/gtajcnzdje.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jianghu66.top/Article/details/gtsxejpxzh.html

[T51] Scala：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtybitjhnr.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gtunjcxeof.html

[T52] Scala：变量
来源：http://dali.ivvv.top/Article/details/gtjgomxbeg.html

val a = 1;  var b = 2
来源：http://dali.mhx1999.top/Article/details/gtjsabkgyi.html

[T53] Scala：字符串插值
来源：http://dali.andypj.xyz/Article/details/gtufmrskpt.html

s"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gttowyrhyp.html

[T54] Scala：集合映射
来源：http://dali.meibo888.top/Article/details/gtgpzliwfn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhongyouzk.top/Article/details/gtmjyxzvju.html

[T55] Scala：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gtlwcqehvn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fzhhl.top/Article/details/gtwdbafsov.html

[T56] Scala：样例类
来源：http://dali.gzhubu.top/Article/details/gtkncprrmi.html

case class User(name: String, age: Int)
来源：http://dali.hfpthk.cn/Article/details/gtrzswchxd.html

[T57] Scala：模式匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gttawaxeeu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tianlin.xyz/Article/details/gtzsuxvybk.html

[T58] Scala：函数定义
来源：http://dali.jinqigufen.top/Article/details/gtcvjmtdpn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hammf.cn/Article/details/gtsmpjgugl.html

[T59] Scala：循环
来源：http://dali.xuanzx.com/Article/details/gtefkdjrds.html

for (i <- 1 to 10) println(i)
来源：http://dali.haohaochexian.top/Article/details/gturqzgfnn.html

[T60] Scala：折叠
来源：http://dali.guannengcc.top/Article/details/gtixtlrhie.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hongshengwenyu.top/Article/details/gtndlshyiv.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtadtqljyh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtleamfrhf.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtakxstoog.html

[U01] Py：创建虚拟环境
来源：http://dali.0kj1m.cn/Article/details/gtsoramstg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gtzichmtrl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hysaishi.cn/Article/details/gtfswxktql.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtvzmjkyry.html

[U03] Py：加载 .env 配置
来源：http://dali.nanxuanxn.top/Article/details/gtpdupfxui.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gaohongyu789.top/Article/details/gtoybencca.html

[U04] Py：变量调试打印
来源：http://dali.yuanzhike.top/Article/details/gtznlhmktn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ppjwa.cn/Article/details/gtpqzjymkl.html

[U05] Py：列表去重且保序
来源：http://dali.chenlongwang.top/Article/details/gtpeigsmdp.html

list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gthurdixvu.html

[U06] Py：合并两个字典
来源：http://dali.jyoumei.cn/Article/details/gtfaektyyu.html

{**a, **b}
来源：http://dali.snrcjt.cn/Article/details/gtpoldjhsz.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvkkgogn.html

{v: k for k, v in d.items()}
来源：http://dali.fzhhl.top/Article/details/gtuxtanzpm.html

[U08] Py：展平二维列表
来源：http://dali.wangshuangyany.cn/Article/details/gthmxchdfs.html

[y for x in nested for y in x]
来源：http://dali.yvedp.cn/Article/details/gtzrxcnhnh.html

[U09] Py：字典取最大值的键
来源：http://dali.daxiang520.top/Article/details/gttbvhbsre.html

max(d, key=d.get)
来源：http://dali.cqqwz.cn/Article/details/gtgannitlf.html

[U10] Py：按值排序字典
来源：http://dali.cdnleiting.top/Article/details/gtpisnwvjv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pengpengdd.cyou/Article/details/gtytawqikd.html

[U11] Py：生成器表达式
来源：http://dali.daxiang520.top/Article/details/gtykltgnmd.html

(x * 2 for x in arr)
来源：http://dali.daria6918.cn/Article/details/gtxpvqazrw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinqigufen.top/Article/details/gtnhtafrun.html

Counter(arr).most_common(3)
来源：http://dali.nanxuanxn.top/Article/details/gtzzcgndzt.html

[U13] Py：固定长度队列
来源：http://dali.nwbrower.top/Article/details/gtrrvaceql.html

deque(maxlen=10)
来源：http://dali.hfpthk.cn/Article/details/gteaxvkesi.html

[U14] Py：分组收集到列表
来源：http://dali.tian-w.cn/Article/details/gtltjurlqs.html

defaultdict(list)
来源：http://dali.0kj1m.cn/Article/details/gtqkfesjpo.html

[U15] Py：高精度计时
来源：http://dali.snrcjt.cn/Article/details/gtbwqkomqn.html

t = time.perf_counter()
来源：http://dali.yongpay.top/Article/details/gtkgzhvuln.html

[U16] Py：命令行参数解析
来源：http://dali.jinghuilouyu.cn/Article/details/gtjquhgmhq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnhmpigy.html

[U17] Py：初始化日志
来源：http://dali.cucudq.cn/Article/details/gtsakiunel.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.wangdashe.top/Article/details/gtsoigeskq.html

[U18] Py：预编译正则
来源：http://dali.gotoacloud.top/Article/details/gtttdqrlhc.html

pat = re.compile(r"\d+")
来源：http://dali.yueranfly.top/Article/details/gtvknirouz.html

[U19] Py：正则替换带回调
来源：http://dali.sufxvd.cn/Article/details/gtcojhwlhr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jlsjyb.cn/Article/details/gtumjljzwa.html

[U20] Py：缓存函数结果
来源：http://dali.pengpengdd.cyou/Article/details/gtmpbehhlc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.kuanghao11.cn/Article/details/gtavkdcrsd.html

[U21] Py：自定义上下文管理器
来源：http://dali.yanxiufei.cn/Article/details/gticlxryau.html

@contextlib.contextmanager
来源：http://dali.jqgufenzy.top/Article/details/gtosvagzej.html

[U22] Py：矩阵转置
来源：http://dali.zhongyouzk.top/Article/details/gtzhbwkpdq.html

list(zip(*m))
来源：http://dali.hnxiangtu.top/Article/details/gtrpyzoskd.html

[U23] Py：分块读取大文件
来源：http://dali.aibaodan.cn/Article/details/gtmesqysum.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryuwehtg.html

[U24] Py：路径操作
来源：http://dali.xylfe.cn/Article/details/gtrkrtvhgr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sweek.top/Article/details/gtencshuyy.html

[U25] Py：CSV 按字典读
来源：http://dali.zdqjudy.top/Article/details/gtryldsijy.html

csv.DictReader(f)
来源：http://dali.yuanzhike.top/Article/details/gtmatgmkgr.html

[U26] Py：并发下载
来源：http://dali.tianlin.xyz/Article/details/gtundzhmvk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.guannengcc.top/Article/details/gtbltllhde.html

[U27] Py：异步 HTTP
来源：http://dali.cucudq.cn/Article/details/gturrdtdet.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jqgufenzy.top/Article/details/gtnhyjygbu.html

[U28] Py：类型别名
来源：http://dali.hongshengwenyu.top/Article/details/gtcdzcpcbj.html

UserId = int
来源：http://dali.haohaochexian.top/Article/details/gtqxjyxdjx.html

[U29] Py：属性校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteybpzron.html

@property 与 @x.setter 配合
来源：http://dali.jqgufenzy.top/Article/details/gtassnohym.html

[U30] Py：数据类
来源：http://dali.ppjwa.cn/Article/details/gtglmdtest.html

@dataclass(slots=True)
来源：http://dali.nanxuanxn.top/Article/details/gtzlzydfbv.html

[U31] Py：单测
来源：http://dali.316326.xyz/Article/details/gtamnugask.html

python -m pytest -q
来源：http://dali.redwolf501.top/Article/details/gtmjhdfbga.html

[U32] Py：代码格式化
来源：http://dali.yj20258.top/Article/details/gtwqqcyknr.html

ruff format . && ruff check --fix .
来源：http://dali.hysaishi.cn/Article/details/gtcmfdlinb.html

[U33] Py：打包发布
来源：http://dali.xuetiantiany.cn/Article/details/gtrrvvktwt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nanxuanxn.top/Article/details/gtkcymxfxb.html

[U34] Py：判断编码
来源：http://dali.hnqzz.top/Article/details/gtdkqafqec.html

chardet.detect(raw)
来源：http://dali.gzhubu.top/Article/details/gtszdoidju.html

[U35] Py：发送邮件
来源：http://dali.nanxuanxn.top/Article/details/gtzmjetliz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.aizwys.cn/Article/details/gtorpshmbg.html

[U36] Py：定时任务
来源：http://dali.jinqigfzy.top/Article/details/gtfpzhmzkx.html

schedule.every(10).minutes.do(job)
来源：http://dali.ehwqpu.com/Article/details/gtbudkjrzp.html

[U37] Py：读写 Excel
来源：http://dali.hysaishi.cn/Article/details/gtneurzrzt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zdqjudy.top/Article/details/gtxunmcgoq.html

[U38] Py：获取脚本所在目录
来源：http://dali.meibo888.top/Article/details/gtyikzpadl.html

Path(__file__).resolve().parent
来源：http://dali.nwbrower.top/Article/details/gtpzaaqkxm.html

[U39] Py：判断是否在交互环境
来源：http://dali.havefunace.top/Article/details/gtohredlit.html

sys.stdout.isatty()
来源：http://dali.svipenyu.cn/Article/details/gtunqriryc.html

[U40] Py：打印到标准错误
来源：http://dali.sysykeji.top/Article/details/gtbaovhtyc.html

print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gtdovhjxje.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sufxvd.cn/Article/details/gtpptyzcvh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ppjwa.cn/Article/details/gtpslfnexq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shangyingyoupin.top/Article/details/gtcytgwwgv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yuanzhike.top/Article/details/gtsaybyagt.html

[U43] PHP：声明命名空间
来源：http://dali.cashguo.top/Article/details/gtbenvicrw.html

namespace App\Http;
来源：http://dali.jinqigufen.top/Article/details/gtetildvni.html

[U44] PHP：开启严格类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjibbjbv.html

declare(strict_types=1);
来源：http://dali.316326.xyz/Article/details/gtmpkwyxqr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yuxming.cn/Article/details/gthmsmhtgw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtnblytkik.html

[U46] PHP：可空类型
来源：http://dali.pycfn.com/Article/details/gtmkfynapj.html

?string $name = null
来源：http://dali.yvedp.cn/Article/details/gttdqoqizv.html

[U47] PHP：联合类型
来源：http://dali.cheryme.top/Article/details/gtlxvpbmtf.html

int|string $id
来源：http://dali.jiagoushi.top/Article/details/gtsriarsbo.html

[U48] PHP：纯枚举
来源：http://dali.tian-w.cn/Article/details/gtrfczaluv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ydzc1.top/Article/details/gtfierinzp.html

[U49] PHP：只读属性
来源：http://dali.cheryme.top/Article/details/gtucxpjupm.html

public readonly string $name
来源：http://dali.jqgfzy.top/Article/details/gtnhmuifns.html

[U50] PHP：构造器属性提升
来源：http://dali.jlsjyb.cn/Article/details/gttwlrewff.html

public function __construct(private int $id) {}
来源：http://dali.hysaishi.cn/Article/details/gtykdipmsj.html

[U51] PHP：数组解构
来源：http://dali.wangshuangyany.cn/Article/details/gtflkcljxx.html

[$a, $b] = $arr;
来源：http://dali.sufxvd.cn/Article/details/gtmrcetkyw.html

[U52] PHP：箭头函数
来源：http://dali.hysaishi.cn/Article/details/gtxhpdyyuw.html

$double = fn($x) => $x * 2;
来源：http://dali.aizwys.cn/Article/details/gtqfwydwlo.html

[U53] PHP：空合并运算符
来源：http://dali.daxiang520.top/Article/details/gtqktgwvck.html

$v = $a ?? $b ?? "default";
来源：http://dali.sweek.top/Article/details/gtxzhvgbgz.html

[U54] PHP：空安全调用
来源：http://dali.pycfn.com/Article/details/gttnffzpui.html

$obj?->method()
来源：http://dali.sweek.top/Article/details/gtuktlcebb.html

[U55] PHP：match 表达式
来源：http://dali.0kj1m.cn/Article/details/gtmraljful.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.haohaochexian.top/Article/details/gtzylgyrnf.html

[U56] PHP：命名参数
来源：http://dali.kuanghao11.cn/Article/details/gtfsvawefq.html

f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gtqmilfogb.html

[U57] PHP：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtqewbavle.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gtwylnnbzq.html

[U58] PHP：数组三件套
来源：http://dali.c1oappe.top/Article/details/gtucnqxlug.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yj20258.top/Article/details/gtiyysrckn.html

[U59] PHP：自定义排序
来源：http://dali.zdqjudy.top/Article/details/gtoucuqxtn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwvvzbln.html

[U60] PHP：JSON 编解码
来源：http://dali.gzhubu.top/Article/details/gtstzlqyhf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yongpay.top/Article/details/gtwiganuwh.html

[U61] PHP：正则
来源：http://dali.svipenyu.cn/Article/details/gtyelywkfo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfdtsulp.html

[U62] PHP：日期对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtuorgkinj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yonumen.top/Article/details/gthzujfemr.html

[U63] PHP：文件读写
来源：http://dali.yj202588.top/Article/details/gtonelhuwx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hongshengwenyu.top/Article/details/gtzxvizyks.html

[U64] PHP：目录遍历
来源：http://dali.smart0.xyz/Article/details/gtjvegrfyj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xuetiantiany.cn/Article/details/gtekvyxfis.html

[U65] PHP：会话
来源：http://dali.tianlin.xyz/Article/details/gtbswvoryg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtiytoylkp.html

[U66] PHP：设置 Cookie
来源：http://dali.redwolf501.top/Article/details/gtjzrjglhi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gtlgemauvx.html

[U67] PHP：处理文件上传
来源：http://dali.hnxiangtu.top/Article/details/gtwpbbcmaw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yj202588.top/Article/details/gtinamdmko.html

[U68] PHP：PDO 连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftkwkcnr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.andypj.xyz/Article/details/gthjrhhpvm.html

[U69] PHP：PDO 预处理
来源：http://dali.sxryk.cn/Article/details/gtoyncmnna.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.tanke756.top/Article/details/gtuoogeglq.html

[U70] PHP：PDO 事务
来源：http://dali.haohaochexian.top/Article/details/gtqgawfaxp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.haohaochexian.top/Article/details/gtmlcwejiv.html

[U71] PHP：抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtmrsbouhf.html

throw new RuntimeException("失败", 500);
来源：http://dali.tianlin.xyz/Article/details/gturhdxcth.html

[U72] PHP：写错误日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxznbaypv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ydzc1.top/Article/details/gtzxsqocak.html

[U73] PHP：读取 ini 配置
来源：http://dali.kuanghao11.cn/Article/details/gtzsvoehle.html

parse_ini_file("config.ini", true)
来源：http://dali.jianghu66.top/Article/details/gteisfhrwd.html

[U74] PHP：读取环境变量
来源：http://dali.tanke756.top/Article/details/gtqpqjuauu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.pengpengdd.cyou/Article/details/gthcdompoc.html


<!-- 参考信息 -->