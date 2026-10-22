代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2gblsludu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yanxiufei.cn/Article/details/gt2clusergj.html

[S48] C++：逐行读文件
来源：http://dali.cheryme.top/Article/details/gt2mbrjjyxx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hnqzz.top/Article/details/gt2abjdtees.html

while (std::getline(in, line)) { }
来源：http://dali.yongpay.top/Article/details/gt2hbrwxzib.html

[S49] C++：写文件
来源：http://dali.dianchejie.cn/Article/details/gt2vxbiddep.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhoulong.xyz/Article/details/gt2fidipsnz.html

[S50] C++：格式化数字
来源：http://dali.yanxiufei.cn/Article/details/gt2axxpgnqo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yueranfly.top/Article/details/gt2rbgsjegn.html

[S51] C++：显式类型转换
来源：http://dali.gogol.net.cn/Article/details/gt2ecqkejls.html

static_cast<double>(a) / b
来源：http://dali.wangshuangyany.cn/Article/details/gt2jnciddmp.html

[S52] C++：const 与 noexcept
来源：http://dali.c1oappe.top/Article/details/gt2utyyaqeb.html

int size() const noexcept { return n_; }
来源：http://dali.xziqi.cn/Article/details/gt2rdbczffw.html

[S53] C++：移动语义
来源：http://dali.sxryk.cn/Article/details/gt2ypaepwqg.html

std::vector<int> w = std::move(v);
来源：http://dali.jqgfzy.top/Article/details/gt2dphbvqze.html

[S54] C++：异常处理
来源：http://dali.kuanghao11.cn/Article/details/gt2svrieviz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenlongwang.top/Article/details/gt2fisqhtvk.html

[S55] C++：结构化绑定
来源：http://dali.yonumen.top/Article/details/gt2tlhskgto.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hunavcch.html

[S56] C++：optional
来源：http://dali.nanxinkj.top/Article/details/gt2mmbzpgdv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenlongwang.top/Article/details/gt2zldbalby.html

[S57] C++：编译期常量
来源：http://dali.jinqigufen.top/Article/details/gt2wcrycnlk.html

constexpr int N = 10;
来源：http://dali.yvedp.cn/Article/details/gt2sovekgsq.html

[S58] C++：命名空间
来源：http://dali.pycfn.com/Article/details/gt2ovbuxwjv.html

namespace ns { int f() { return 1; } }
来源：http://dali.shzxlz.cn/Article/details/gt2dyuuaikv.html

[S59] C++：静态断言
来源：http://dali.tianlin.xyz/Article/details/gt2enjalrcy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.andypj.xyz/Article/details/gt2fqutcnht.html

[S60] C++：遍历并删除元素
来源：http://dali.iojbl.cn/Article/details/gt2onesrrtj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuanzx.com/Article/details/gt2vvwrezoc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxvbxhjv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gt2wwcajslb.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2lnkljokn.html

[T01] Kotlin：Hello World
来源：http://dali.pycfn.com/Article/details/gt2qudauymu.html

println("Hello")
来源：http://dali.316326.xyz/Article/details/gt2ejqcvxua.html

[T02] Kotlin：变量
来源：http://dali.sweek.top/Article/details/gt2riykclab.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gotoacloud.top/Article/details/gt2vmltwegx.html

[T03] Kotlin：字符串模板
来源：http://dali.guowangkeji.top/Article/details/gt2ziuytuks.html

"值: $b"
来源：http://dali.cucudq.cn/Article/details/gt2jqrjqjka.html

[T04] Kotlin：空安全
来源：http://dali.daxiang520.top/Article/details/gt2ykhqcgap.html

val n: String? = null;  n?.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2srvtvdgu.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gt2uksqcqrk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuxming.cn/Article/details/gt2rpybutxf.html

[T06] Kotlin：集合映射
来源：http://dali.yonumen.top/Article/details/gt2ygpogvli.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ybcxt.top/Article/details/gt2gekdwkyy.html

[T07] Kotlin：集合过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2xcprtbuu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yueranfly.top/Article/details/gt2wcreuqed.html

[T08] Kotlin：数据类
来源：http://dali.zhengqikj.top/Article/details/gt2xwaqtblb.html

data class User(val name: String, val age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gt2gaybmlne.html

[T09] Kotlin：扩展函数
来源：http://dali.gotoacloud.top/Article/details/gt2eqoihvzv.html

fun String.exclaim() = this + "!"
来源：http://dali.chenzaomai.com/Article/details/gt2oamwzvvo.html

[T10] Kotlin：默认参数
来源：http://dali.zhongyouzk.top/Article/details/gt2shggigzh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fengsongda.top/Article/details/gt2uqnlblyp.html

[T11] Kotlin：协程
来源：http://dali.yongpay.top/Article/details/gt2meoypisy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.feifeiyinyue.top/Article/details/gt2uifpwfnr.html

[T12] Kotlin：解构声明
来源：http://dali.sweek.top/Article/details/gt2cqhycibm.html

val (a, b) = Pair(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2ygxgddrs.html

[T13] Kotlin：只读 Map
来源：http://dali.wangdashe.top/Article/details/gt2mwznwkid.html

val m = mapOf("a" to 1)
来源：http://dali.tanke756.top/Article/details/gt2xnqhfkhx.html

[T14] Kotlin：循环
来源：http://dali.gaohongyu789.top/Article/details/gt2iksoavaj.html

for (i in 1..10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gt2veliydig.html

[T15] Kotlin：接口
来源：http://dali.ybcxt.top/Article/details/gt2umenndxe.html

interface Shape { fun area(): Double }
来源：http://dali.yj20258.top/Article/details/gt2fvmywfuo.html

[T16] Swift：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2rqnjpqys.html

print("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqjkdunb.html

[T17] Swift：变量与常量
来源：http://dali.yuanzhike.top/Article/details/gt2kqovhjeq.html

var a = 1;  let b = 2
来源：http://dali.yanxiufei.cn/Article/details/gt2yicgrroh.html

[T18] Swift：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gt2eenrmvkt.html

"值: \(b)"
来源：http://dali.zhoulong.xyz/Article/details/gt2pboiztyk.html

[T19] Swift：可选绑定
来源：http://dali.havefunace.top/Article/details/gt2lsdmbejj.html

if let n = opt { print(n) }
来源：http://dali.mhx1999.top/Article/details/gt2szspgdlx.html

[T20] Swift：数组操作
来源：http://dali.tian-w.cn/Article/details/gt2ddpopodr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xziqi.cn/Article/details/gt2ubssivno.html

[T21] Swift：遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2qashekan.html

for x in a { print(x) }
来源：http://dali.jqgfzy.top/Article/details/gt2hckcrxwj.html

[T22] Swift：字典
来源：http://dali.0kj1m.cn/Article/details/gt2hoxwiiuq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2yidybjvw.html

[T23] Swift：函数
来源：http://dali.cdnleiting.top/Article/details/gt2jahsebas.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jyoumei.cn/Article/details/gt2yscfzyaq.html

[T24] Swift：闭包
来源：http://dali.iojbl.cn/Article/details/gt2pdhiywke.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yueranfly.top/Article/details/gt2oqnngxrz.html

[T25] Swift：结构体
来源：http://dali.fengsongda.top/Article/details/gt2rklsqpxy.html

struct P { var x: Int }
来源：http://dali.tianlin.xyz/Article/details/gt2rrlfbwam.html

[T26] Swift：类与重写
来源：http://dali.nanxinkj.top/Article/details/gt2ricnasec.html

class A: Base { override func f() {} }
来源：http://dali.tianlin.xyz/Article/details/gt2xxbpduzf.html

[T27] Swift：错误处理
来源：http://dali.yongpay.top/Article/details/gt2bcefdgio.html

do { try f() } catch { print(error) }
来源：http://dali.fzhhl.top/Article/details/gt2ulaguora.html

[T28] Swift：枚举
来源：http://dali.9152youxi.cn/Article/details/gt2orvokiwh.html

enum Color { case red, green }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ukclepkr.html

[T29] Swift：guard 提前返回
来源：http://dali.yj20258888.top/Article/details/gt2dyglbkhn.html

guard let x = opt else { return }
来源：http://dali.sxryk.cn/Article/details/gt2jscwnmvt.html

[T30] Swift：协议
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovfxwjhr.html

protocol Shape { func area() -> Double }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rrkcmlwk.html

[T31] Lua：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2slqpqzmr.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gt2vopocylb.html

[T32] Lua：局部变量
来源：http://dali.sufxvd.cn/Article/details/gt2ndltpobh.html

local a = 1
来源：http://dali.chenlongwang.top/Article/details/gt2rmddzilt.html

[T33] Lua：表（数组）
来源：http://dali.iojbl.cn/Article/details/gt2iuqxlwqn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jlsjyb.cn/Article/details/gt2qxvaqwqu.html

[T34] Lua：遍历表
来源：http://dali.jqgufenzy.top/Article/details/gt2kznqsnxs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.mhx1999.top/Article/details/gt2xbjpqmyl.html

[T35] Lua：字典表
来源：http://dali.cqqwz.cn/Article/details/gt2xlefzjfj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iwjlnhjn.html

[T36] Lua：函数
来源：http://dali.xinyue.icu/Article/details/gt2wipdmxym.html

function add(a, b) return a + b end
来源：http://dali.zhengqikj.top/Article/details/gt2njkomwir.html

[T37] Lua：字符串拼接
来源：http://dali.meibo888.top/Article/details/gt2vgqzlhsz.html

"a" .. "b"
来源：http://dali.havefunace.top/Article/details/gt2nbonoqoo.html

[T38] Lua：条件
来源：http://dali.tian-w.cn/Article/details/gt2xugmlqiu.html

if x > 0 then print("正") end
来源：http://dali.yanxiufei.cn/Article/details/gt2uhqusskc.html

[T39] Lua：模式匹配
来源：http://dali.cashguo.top/Article/details/gt2ajyshefs.html

string.find(s, "%d+")
来源：http://dali.sysykeji.top/Article/details/gt2ofpeixes.html

[T40] Lua：元表
来源：http://dali.316326.xyz/Article/details/gt2uuyrqjns.html

setmetatable({}, { __index = base })
来源：http://dali.fengsongda.top/Article/details/gt2peweezvd.html

[T41] Perl：Hello World
来源：http://dali.316326.xyz/Article/details/gt2gwatzjip.html

print "Hello\n";
来源：http://dali.chenlongwang.top/Article/details/gt2wjgrnbtw.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qkqshfpm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.havefunace.top/Article/details/gt2yuhxbwew.html

[T43] Perl：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gt2mifyzhiv.html

"值: $a"
来源：http://dali.birdmap.top/Article/details/gt2trxhfhsf.html

[T44] Perl：条件
来源：http://dali.jinqigfzy.top/Article/details/gt2tydxpkoz.html

if ($a > 0) { print "正"; }
来源：http://dali.yuanzhike.top/Article/details/gt2dmpuijst.html

[T45] Perl：数组遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2aotyrwoy.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dblhzrvs.html

[T46] Perl：哈希操作
来源：http://dali.shangyingyoupin.top/Article/details/gt2pivdbgge.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cucudq.cn/Article/details/gt2azeqnusn.html

[T47] Perl：正则捕获
来源：http://dali.ivvv.top/Article/details/gt2gzsbuyos.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jyoumei.cn/Article/details/gt2qtwkeqsg.html

[T48] Perl：正则替换
来源：http://dali.chenzaomai.com/Article/details/gt2zroomhli.html

$s =~ s/old/new/g;
来源：http://dali.cqqwz.cn/Article/details/gt2zsrhehxw.html

[T49] Perl：函数
来源：http://dali.quarkkingdee.top/Article/details/gt2twtcnttq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gt2vlrbllbj.html

[T50] Perl：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gt2slxzhfrb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.daria6918.cn/Article/details/gt2kgfnilcb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fzhhl.top/Article/details/gt2pmxmgxbn.html

[T51] Scala：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2kpwwokyl.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gt2iybjympl.html

[T52] Scala：变量
来源：http://dali.chenzaomai.com/Article/details/gt2hzhnlywc.html

val a = 1;  var b = 2
来源：http://dali.cheryme.top/Article/details/gt2baaeober.html

[T53] Scala：字符串插值
来源：http://dali.cheryme.top/Article/details/gt2zjmxyceh.html

s"值: $b"
来源：http://dali.meibo888.top/Article/details/gt2rrapdzwm.html

[T54] Scala：集合映射
来源：http://dali.nanxuanxn.top/Article/details/gt2emvubqqn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.c1oappe.top/Article/details/gt2noxinutl.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2twarwoco.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vdfgimzz.html

[T56] Scala：样例类
来源：http://dali.tianlin.xyz/Article/details/gt2hrlmphna.html

case class User(name: String, age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gt2lbnvcvvt.html

[T57] Scala：模式匹配
来源：http://dali.shzxlz.cn/Article/details/gt2nnjwwtky.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gaohongyu789.top/Article/details/gt2yayozayr.html

[T58] Scala：函数定义
来源：http://dali.ydzc1.top/Article/details/gt2wbemeyem.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigufen.top/Article/details/gt2ukrmhrjk.html

[T59] Scala：循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2xoypsqqg.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnqzz.top/Article/details/gt2vuwsbrym.html

[T60] Scala：折叠
来源：http://dali.daxiang520.top/Article/details/gt2doncrynk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sufxvd.cn/Article/details/gt2kfqlxtcf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2yydokpoq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2hhtequsq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2mbztkdvx.html

[U01] Py：创建虚拟环境
来源：http://dali.yj20258888.top/Article/details/gt2kkndtpkr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shzxlz.cn/Article/details/gt2umitplhr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.quarkkingdee.top/Article/details/gt2qxcabcmg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.andypj.xyz/Article/details/gt2qdurbeot.html

[U03] Py：加载 .env 配置
来源：http://dali.yj20258888.top/Article/details/gt2hnjomudn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cqqwz.cn/Article/details/gt2enczapki.html

[U04] Py：变量调试打印
来源：http://dali.dianchejie.cn/Article/details/gt2fzvdojrl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hongshengwenyu.top/Article/details/gt2nljrqebt.html

[U05] Py：列表去重且保序
来源：http://dali.nanxuanxn.top/Article/details/gt2igrdbzpa.html

list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gt2jzbpytig.html

[U06] Py：合并两个字典
来源：http://dali.xuanzx.com/Article/details/gt2ezogqywr.html

{**a, **b}
来源：http://dali.tianlin.xyz/Article/details/gt2hyhlkhjr.html

[U07] Py：反转字典键值
来源：http://dali.zhongyouzk.top/Article/details/gt2buprumfx.html

{v: k for k, v in d.items()}
来源：http://dali.pycfn.com/Article/details/gt2gookwqcu.html

[U08] Py：展平二维列表
来源：http://dali.nanxinkj.top/Article/details/gt2nkwxzdft.html

[y for x in nested for y in x]
来源：http://dali.jinqigfzy.top/Article/details/gt2dzgfeiph.html

[U09] Py：字典取最大值的键
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vqrsuzlg.html

max(d, key=d.get)
来源：http://dali.bjfxy.top/Article/details/gt2vtxwlkba.html

[U10] Py：按值排序字典
来源：http://dali.nanxuanxn.top/Article/details/gt2iihnyikx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj20258.top/Article/details/gt2lzfgvfhh.html

[U11] Py：生成器表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2rnjmqesy.html

(x * 2 for x in arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2zmpclwyn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nanxuanxn.top/Article/details/gt2cnmiljgs.html

Counter(arr).most_common(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sddefmfm.html

[U13] Py：固定长度队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2jwattgad.html

deque(maxlen=10)
来源：http://dali.gogol.net.cn/Article/details/gt2bkafxbal.html

[U14] Py：分组收集到列表
来源：http://dali.ehwqpu.com/Article/details/gt2nfudjffl.html

defaultdict(list)
来源：http://dali.redwolf501.top/Article/details/gt2nlgebhtm.html

[U15] Py：高精度计时
来源：http://dali.yj202588.top/Article/details/gt2wlgtyhwf.html

t = time.perf_counter()
来源：http://dali.yangfankeji.com/Article/details/gt2cmolwrne.html

[U16] Py：命令行参数解析
来源：http://dali.svipenyu.cn/Article/details/gt2jzrkfwlu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhoulong.xyz/Article/details/gt2hfvjpfbs.html

[U17] Py：初始化日志
来源：http://dali.c1oappe.top/Article/details/gt2apiwfqki.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ybcxt.top/Article/details/gt2btwyloos.html

[U18] Py：预编译正则
来源：http://dali.hfpthk.cn/Article/details/gt2yuvompxh.html

pat = re.compile(r"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2deznmwsp.html

[U19] Py：正则替换带回调
来源：http://dali.jyoumei.cn/Article/details/gt2zddjahmh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.haohaochexian.top/Article/details/gt2pgpqbmiv.html

[U20] Py：缓存函数结果
来源：http://dali.havefunace.top/Article/details/gt2vvreaqux.html

@functools.lru_cache(maxsize=None)
来源：http://dali.guannengcc.top/Article/details/gt2yozpyoyu.html

[U21] Py：自定义上下文管理器
来源：http://dali.vqdsnc.cn/Article/details/gt2duhgrcfo.html

@contextlib.contextmanager
来源：http://dali.ehwqpu.com/Article/details/gt2zpvwnwpa.html

[U22] Py：矩阵转置
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eumnlpne.html

list(zip(*m))
来源：http://dali.gaohongyu789.top/Article/details/gt2gtbbuppr.html

[U23] Py：分块读取大文件
来源：http://dali.pycfn.com/Article/details/gt2hyztbrco.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tianlin.xyz/Article/details/gt2iahrzljo.html

[U24] Py：路径操作
来源：http://dali.yonumen.top/Article/details/gt2kqwrctqa.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gt2bqzulrcm.html

[U25] Py：CSV 按字典读
来源：http://dali.xuanzx.com/Article/details/gt2uostogpu.html

csv.DictReader(f)
来源：http://dali.zycfv.cn/Article/details/gt2remqiqds.html

[U26] Py：并发下载
来源：http://dali.yuxming.cn/Article/details/gt2lbrntypi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhengqikj.top/Article/details/gt2wvnugyke.html

[U27] Py：异步 HTTP
来源：http://dali.guowangkeji.top/Article/details/gt2trdtphry.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jiagoushi.top/Article/details/gt2sencgmsp.html

[U28] Py：类型别名
来源：http://dali.cdnleiting.top/Article/details/gt2ejaydwgi.html

UserId = int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ryuduibb.html

[U29] Py：属性校验
来源：http://dali.jyoumei.cn/Article/details/gt2zooqclfg.html

@property 与 @x.setter 配合
来源：http://dali.smart0.xyz/Article/details/gt2lhqzinje.html

[U30] Py：数据类
来源：http://dali.hywenlv.cn/Article/details/gt2dmggjnby.html

@dataclass(slots=True)
来源：http://dali.nanxinkj.top/Article/details/gt2rfjybzlc.html

[U31] Py：单测
来源：http://dali.ybcxt.top/Article/details/gt2jjvnppff.html

python -m pytest -q
来源：http://dali.yuxming.cn/Article/details/gt2uhgznply.html

[U32] Py：代码格式化
来源：http://dali.jqgufenzy.top/Article/details/gt2xpdvddes.html

ruff format . && ruff check --fix .
来源：http://dali.0kj1m.cn/Article/details/gt2rtaxuvua.html

[U33] Py：打包发布
来源：http://dali.c1oappe.top/Article/details/gt2qmdrcosl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.dianchejie.cn/Article/details/gt2zpcywafc.html

[U34] Py：判断编码
来源：http://dali.yanxiufei.cn/Article/details/gt2mdcqjdit.html

chardet.detect(raw)
来源：http://dali.yanxiufei.cn/Article/details/gt2qewgvxic.html

[U35] Py：发送邮件
来源：http://dali.sufxvd.cn/Article/details/gt2tfhikopr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hammf.cn/Article/details/gt2iswtwcow.html

[U36] Py：定时任务
来源：http://dali.jinqigufen.top/Article/details/gt2thwerajm.html

schedule.every(10).minutes.do(job)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vrdwiwnn.html

[U37] Py：读写 Excel
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdawytre.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gaohongyu789.top/Article/details/gt2wwkfphsg.html

[U38] Py：获取脚本所在目录
来源：http://dali.ybcxt.top/Article/details/gt2iirgyoiy.html

Path(__file__).resolve().parent
来源：http://dali.ehwqpu.com/Article/details/gt2qyhewreh.html

[U39] Py：判断是否在交互环境
来源：http://dali.gzhubu.top/Article/details/gt2ihlknzhc.html

sys.stdout.isatty()
来源：http://dali.hysaishi.cn/Article/details/gt2rakbsobe.html

[U40] Py：打印到标准错误
来源：http://dali.svipenyu.cn/Article/details/gt2ptuwlvwo.html

print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ilinyisl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbrxucjm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jiagoushi.top/Article/details/gt2xnpmmkfw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gotoacloud.top/Article/details/gt2jjthboga.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.sxryk.cn/Article/details/gt2camvtejg.html

[U43] PHP：声明命名空间
来源：http://dali.jinqigufen.top/Article/details/gt2nuqreibv.html

namespace App\Http;
来源：http://dali.tianlin.xyz/Article/details/gt2mpmlbszq.html

[U44] PHP：开启严格类型
来源：http://dali.xuanzx.com/Article/details/gt2hzmxypvh.html

declare(strict_types=1);
来源：http://dali.yueranfly.top/Article/details/gt2vxvegcwv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qzmqhaym.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gt2ptrprbhm.html

[U46] PHP：可空类型
来源：http://dali.hnqzz.top/Article/details/gt2rlpuxoqd.html

?string $name = null
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qrveknst.html

[U47] PHP：联合类型
来源：http://dali.yueranfly.top/Article/details/gt2kpyazqno.html

int|string $id
来源：http://dali.yongpay.top/Article/details/gt2swlpkrff.html

[U48] PHP：纯枚举
来源：http://dali.jinqigufen.top/Article/details/gt2byqufxkj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shuidangran.top/Article/details/gt2waqcebhy.html

[U49] PHP：只读属性
来源：http://dali.tianlin.xyz/Article/details/gt2qcqfvgzv.html

public readonly string $name
来源：http://dali.0kj1m.cn/Article/details/gt2hvfcfuvx.html

[U50] PHP：构造器属性提升
来源：http://dali.ivvv.top/Article/details/gt2wmxgcysp.html

public function __construct(private int $id) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2pnuyrzox.html

[U51] PHP：数组解构
来源：http://dali.snrcjt.cn/Article/details/gt2sucdjdaw.html

[$a, $b] = $arr;
来源：http://dali.birdmap.top/Article/details/gt2mxszooah.html

[U52] PHP：箭头函数
来源：http://dali.haohaochexian.top/Article/details/gt2zgrnzrzz.html

$double = fn($x) => $x * 2;
来源：http://dali.gogol.net.cn/Article/details/gt2gijwtsih.html

[U53] PHP：空合并运算符
来源：http://dali.xinyue.icu/Article/details/gt2rxejhqul.html

$v = $a ?? $b ?? "default";
来源：http://dali.yanxiufei.cn/Article/details/gt2tqywydce.html

[U54] PHP：空安全调用
来源：http://dali.yueranfly.top/Article/details/gt2huhmhrbo.html

$obj?->method()
来源：http://dali.hysaishi.cn/Article/details/gt2nbnzrnns.html

[U55] PHP：match 表达式
来源：http://dali.svipenyu.cn/Article/details/gt2ooborggk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.guowangkeji.top/Article/details/gt2hqnpmkjd.html

[U56] PHP：命名参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eqlbwksv.html

f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gt2yafkvnxt.html

[U57] PHP：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gt2wubhqxcx.html

"值: {$a}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2tgeiapuv.html

[U58] PHP：数组三件套
来源：http://dali.gzhubu.top/Article/details/gt2vzosrhnf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.daxiang520.top/Article/details/gt2efakerxq.html

[U59] PHP：自定义排序
来源：http://dali.jinqigfzy.top/Article/details/gt2edxnxsdh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zdqjudy.top/Article/details/gt2uavpehfa.html

[U60] PHP：JSON 编解码
来源：http://dali.hfpthk.cn/Article/details/gt2ntcvgxou.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cdnleiting.top/Article/details/gt2ilrzmlnu.html

[U61] PHP：正则
来源：http://dali.xylfe.cn/Article/details/gt2mjyikisj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2nvptcnlf.html

[U62] PHP：日期对象
来源：http://dali.hnxiangtu.top/Article/details/gt2sogmpway.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ogklgpqz.html

[U63] PHP：文件读写
来源：http://dali.c1oappe.top/Article/details/gt2blcnxhjf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.aibaodan.cn/Article/details/gt2ricbglrg.html

[U64] PHP：目录遍历
来源：http://dali.zdqjudy.top/Article/details/gt2iuvhaqdk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ppjwa.cn/Article/details/gt2fmfqaotp.html

[U65] PHP：会话
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ybpqsrni.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfaitzrt.html

[U66] PHP：设置 Cookie
来源：http://dali.fzhhl.top/Article/details/gt2pemivllx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hckntzku.html

[U67] PHP：处理文件上传
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ilthtezk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.bjfxy.top/Article/details/gt2edsruymc.html

[U68] PHP：PDO 连接
来源：http://dali.cucudq.cn/Article/details/gt2agqcqljv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tianlin.xyz/Article/details/gt2xsyqzrfu.html

[U69] PHP：PDO 预处理
来源：http://dali.yuanzhike.top/Article/details/gt2uaakfocy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhongyouzk.top/Article/details/gt2szdksiac.html

[U70] PHP：PDO 事务
来源：http://dali.sxryk.cn/Article/details/gt2pfzfapjy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cdnleiting.top/Article/details/gt2azwlhiaz.html

[U71] PHP：抛出异常
来源：http://dali.dianchejie.cn/Article/details/gt2nmpesjjy.html

throw new RuntimeException("失败", 500);
来源：http://dali.xylfe.cn/Article/details/gt2cgefbuxw.html

[U72] PHP：写错误日志
来源：http://dali.ybcxt.top/Article/details/gt2ohwnqjvb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jlsjyb.cn/Article/details/gt2xtqxoutg.html


<!-- 参考信息 -->