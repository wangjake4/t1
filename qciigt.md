代发 wailian999

[T27] Swift：错误处理
来源：http://dali.hammf.cn/Article/details/gt2ltwihgzt.html

do { try f() } catch { print(error) }
来源：http://dali.yuxming.cn/Article/details/gt2ckyzwhmo.html

[T28] Swift：枚举
来源：http://dali.jiagoushi.top/Article/details/gt2kgdaajjy.html

enum Color { case red, green }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vzvsmtbd.html

[T29] Swift：guard 提前返回
来源：http://dali.hongshengwenyu.top/Article/details/gt2mizsmjzm.html

guard let x = opt else { return }
来源：http://dali.cucudq.cn/Article/details/gt2ibcoziku.html

[T30] Swift：协议
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aahynboa.html

protocol Shape { func area() -> Double }
来源：http://dali.hnqzz.top/Article/details/gt2fpxgjmyy.html

[T31] Lua：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2dmuzzpxm.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gt2nltdghfk.html

[T32] Lua：局部变量
来源：http://dali.yangfankeji.com/Article/details/gt2vwpabzjq.html

local a = 1
来源：http://dali.dianchejie.cn/Article/details/gt2ubqeboao.html

[T33] Lua：表（数组）
来源：http://dali.xuanzx.com/Article/details/gt2stcbstgt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.kuanghao11.cn/Article/details/gt2yvnpkwwb.html

[T34] Lua：遍历表
来源：http://dali.yangfankeji.com/Article/details/gt2jcgyuene.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.snrcjt.cn/Article/details/gt2gmicdrdw.html

[T35] Lua：字典表
来源：http://dali.cucudq.cn/Article/details/gt2wjgjooxn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guowangkeji.top/Article/details/gt2hfcdsldq.html

[T36] Lua：函数
来源：http://dali.jiagoushi.top/Article/details/gt2hwjeqilm.html

function add(a, b) return a + b end
来源：http://dali.guannengcc.top/Article/details/gt2ieaiadql.html

[T37] Lua：字符串拼接
来源：http://dali.tanke756.top/Article/details/gt2qxairgvl.html

"a" .. "b"
来源：http://dali.shzxlz.cn/Article/details/gt2jbcmpfun.html

[T38] Lua：条件
来源：http://dali.yuanzhike.top/Article/details/gt2kyrzyjae.html

if x > 0 then print("正") end
来源：http://dali.hongshengwenyu.top/Article/details/gt2fugoxwqg.html

[T39] Lua：模式匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2cpqjwxib.html

string.find(s, "%d+")
来源：http://dali.fengsongda.top/Article/details/gt2jgwknfco.html

[T40] Lua：元表
来源：http://dali.aibaodan.cn/Article/details/gt2ryzhkept.html

setmetatable({}, { __index = base })
来源：http://dali.ydzc1.top/Article/details/gt2sxfmbwdw.html

[T41] Perl：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2owxmxbvg.html

print "Hello\n";
来源：http://dali.yongpay.top/Article/details/gt2kshjeuzo.html

[T42] Perl：变量类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sfbprkfx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhixingplan.top/Article/details/gt2vsluvbfj.html

[T43] Perl：字符串插值
来源：http://dali.nwbrower.top/Article/details/gt2dtxlfunb.html

"值: $a"
来源：http://dali.dianchejie.cn/Article/details/gt2lohtergm.html

[T44] Perl：条件
来源：http://dali.cheryme.top/Article/details/gt2tgbqytjb.html

if ($a > 0) { print "正"; }
来源：http://dali.andypj.xyz/Article/details/gt2lfdzszqs.html

[T45] Perl：数组遍历
来源：http://dali.chenzaomai.com/Article/details/gt2jgnpuqts.html

for my $x (@arr) { print $x; }
来源：http://dali.hysaishi.cn/Article/details/gt2ortgifqv.html

[T46] Perl：哈希操作
来源：http://dali.0kj1m.cn/Article/details/gt2ledydlju.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tpwkwrwd.html

[T47] Perl：正则捕获
来源：http://dali.cashguo.top/Article/details/gt2pogbgjcz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gzhubu.top/Article/details/gt2hhwlxxvp.html

[T48] Perl：正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2dgxjccuj.html

$s =~ s/old/new/g;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vrjgqnrr.html

[T49] Perl：函数
来源：http://dali.shuidangran.top/Article/details/gt2xfmozjcw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nepiobtp.html

[T50] Perl：逐行读文件
来源：http://dali.sweek.top/Article/details/gt2vekkztct.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.c1oappe.top/Article/details/gt2mohrjnml.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sufxvd.cn/Article/details/gt2xtmhjfhv.html

[T51] Scala：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2wntuvthq.html

println("Hello")
来源：http://dali.shuidangran.top/Article/details/gt2rtddpgwa.html

[T52] Scala：变量
来源：http://dali.sweek.top/Article/details/gt2ckzlgwph.html

val a = 1;  var b = 2
来源：http://dali.tian-w.cn/Article/details/gt2izscdvhs.html

[T53] Scala：字符串插值
来源：http://dali.zycfv.cn/Article/details/gt2ghwvyuwn.html

s"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gt2oeiiybue.html

[T54] Scala：集合映射
来源：http://dali.yuanzhike.top/Article/details/gt2loltpowr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ivvv.top/Article/details/gt2matdclhn.html

[T55] Scala：集合过滤
来源：http://dali.tian-w.cn/Article/details/gt2ayeelsil.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2axkwmbwt.html

[T56] Scala：样例类
来源：http://dali.yanxiufei.cn/Article/details/gt2dpcksftg.html

case class User(name: String, age: Int)
来源：http://dali.yj20258888.top/Article/details/gt2zxekicws.html

[T57] Scala：模式匹配
来源：http://dali.c1oappe.top/Article/details/gt2uxxfesgn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.svipenyu.cn/Article/details/gt2czhxrodh.html

[T58] Scala：函数定义
来源：http://dali.aizwys.cn/Article/details/gt2soulggdt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tanke756.top/Article/details/gt2cgmfwmyp.html

[T59] Scala：循环
来源：http://dali.zycfv.cn/Article/details/gt2uzawosie.html

for (i <- 1 to 10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gt2kwwdocwx.html

[T60] Scala：折叠
来源：http://dali.zhongyouzk.top/Article/details/gt2acipsrpc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ehwqpu.com/Article/details/gt2ujwsfpxz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2aqusvrhs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2dukanvmm.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ofzmbfhq.html

[U01] Py：创建虚拟环境
来源：http://dali.zdqjudy.top/Article/details/gt2oqlrudkz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yvedp.cn/Article/details/gt2rvflrliz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.mhx1999.top/Article/details/gt2zqunqcbz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nwbrower.top/Article/details/gt2qllkodor.html

[U03] Py：加载 .env 配置
来源：http://dali.pengpengdd.cyou/Article/details/gt2aggqagmi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tianlin.xyz/Article/details/gt2qpmtqxcc.html

[U04] Py：变量调试打印
来源：http://dali.ivvv.top/Article/details/gt2mltdzluk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cucudq.cn/Article/details/gt2tkfrovix.html

[U05] Py：列表去重且保序
来源：http://dali.ehwqpu.com/Article/details/gt2jeuxbeek.html

list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gt2kezgrlvm.html

[U06] Py：合并两个字典
来源：http://dali.zdqjudy.top/Article/details/gt2ujsdupjr.html

{**a, **b}
来源：http://dali.tianlin.xyz/Article/details/gt2suxasiqe.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hbkvnvdb.html

{v: k for k, v in d.items()}
来源：http://dali.xinyue.icu/Article/details/gt2vasisfvw.html

[U08] Py：展平二维列表
来源：http://dali.zdqjudy.top/Article/details/gt2tysjptsg.html

[y for x in nested for y in x]
来源：http://dali.feifeiyinyue.top/Article/details/gt2xcyewysj.html

[U09] Py：字典取最大值的键
来源：http://dali.gogol.net.cn/Article/details/gt2esdunajw.html

max(d, key=d.get)
来源：http://dali.tanke756.top/Article/details/gt2actladvp.html

[U10] Py：按值排序字典
来源：http://dali.hnxiangtu.top/Article/details/gt2wrpuwnjf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sweek.top/Article/details/gt2sgnzudny.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zsjclvdo.html

(x * 2 for x in arr)
来源：http://dali.c1oappe.top/Article/details/gt2yydvcsna.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xuanzx.com/Article/details/gt2cfcrerkb.html

Counter(arr).most_common(3)
来源：http://dali.yj20258.top/Article/details/gt2aoqjavmh.html

[U13] Py：固定长度队列
来源：http://dali.wangdashe.top/Article/details/gt2qvtknjqh.html

deque(maxlen=10)
来源：http://dali.jyoumei.cn/Article/details/gt2lqaerziv.html

[U14] Py：分组收集到列表
来源：http://dali.dashuyun.cn/Article/details/gt2bywyypih.html

defaultdict(list)
来源：http://dali.yvedp.cn/Article/details/gt2dxeoxljb.html

[U15] Py：高精度计时
来源：http://dali.jlsjyb.cn/Article/details/gt2feitmsey.html

t = time.perf_counter()
来源：http://dali.jinqigufen.top/Article/details/gt2rdiistbr.html

[U16] Py：命令行参数解析
来源：http://dali.guannengcc.top/Article/details/gt2kmmgncja.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hfpthk.cn/Article/details/gt2rqktqzks.html

[U17] Py：初始化日志
来源：http://dali.hnqzz.top/Article/details/gt2qwxbqdgp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.316326.xyz/Article/details/gt2iaqbisjp.html

[U18] Py：预编译正则
来源：http://dali.jiagoushi.top/Article/details/gt2bhikahas.html

pat = re.compile(r"\d+")
来源：http://dali.hfpthk.cn/Article/details/gt2xnosvulh.html

[U19] Py：正则替换带回调
来源：http://dali.tanke756.top/Article/details/gt2nfjdnghq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.bjfxy.top/Article/details/gt2mtphcaqu.html

[U20] Py：缓存函数结果
来源：http://dali.jiagoushi.top/Article/details/gt2yenjfnys.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jgmtuwth.html

[U21] Py：自定义上下文管理器
来源：http://dali.nanxuanxn.top/Article/details/gt2phrqfgoz.html

@contextlib.contextmanager
来源：http://dali.shuidangran.top/Article/details/gt2scttwfvy.html

[U22] Py：矩阵转置
来源：http://dali.sweek.top/Article/details/gt2tmubglko.html

list(zip(*m))
来源：http://dali.c1oappe.top/Article/details/gt2pqzpsqoz.html

[U23] Py：分块读取大文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2moespzcv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj202588.top/Article/details/gt2aiquzqpi.html

[U24] Py：路径操作
来源：http://dali.hnqzz.top/Article/details/gt2rwmgijqw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gt2yneehmtr.html

[U25] Py：CSV 按字典读
来源：http://dali.316326.xyz/Article/details/gt2eclefhsd.html

csv.DictReader(f)
来源：http://dali.daria6918.cn/Article/details/gt2huaedszf.html

[U26] Py：并发下载
来源：http://dali.yuxming.cn/Article/details/gt2vtlmgfse.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lxotwtvg.html

[U27] Py：异步 HTTP
来源：http://dali.sweek.top/Article/details/gt2ocahlvtx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cashguo.top/Article/details/gt2gxqabzfk.html

[U28] Py：类型别名
来源：http://dali.tianlin.xyz/Article/details/gt2kkxjovhj.html

UserId = int
来源：http://dali.fengsongda.top/Article/details/gt2yccgxhmg.html

[U29] Py：属性校验
来源：http://dali.yuanzhike.top/Article/details/gt2gpzlescb.html

@property 与 @x.setter 配合
来源：http://dali.hywenlv.cn/Article/details/gt2knwplteq.html

[U30] Py：数据类
来源：http://dali.redwolf501.top/Article/details/gt2doyqnmvm.html

@dataclass(slots=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qajggebt.html

[U31] Py：单测
来源：http://dali.hywenlv.cn/Article/details/gt2aqbknlqh.html

python -m pytest -q
来源：http://dali.wangshuangyany.cn/Article/details/gt2rcfecpzx.html

[U32] Py：代码格式化
来源：http://dali.sweek.top/Article/details/gt2qnjjgpvx.html

ruff format . && ruff check --fix .
来源：http://dali.tian-w.cn/Article/details/gt2dnesbwdo.html

[U33] Py：打包发布
来源：http://dali.yangfankeji.com/Article/details/gt2apfysias.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yueranfly.top/Article/details/gt2wybusvao.html

[U34] Py：判断编码
来源：http://dali.nwbrower.top/Article/details/gt2syygqndc.html

chardet.detect(raw)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ficanokn.html

[U35] Py：发送邮件
来源：http://dali.jlsjyb.cn/Article/details/gt2mnylgpug.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.snrcjt.cn/Article/details/gt2npddbeyj.html

[U36] Py：定时任务
来源：http://dali.xziqi.cn/Article/details/gt2meghfbkv.html

schedule.every(10).minutes.do(job)
来源：http://dali.chenzaomai.com/Article/details/gt2vdskzkir.html

[U37] Py：读写 Excel
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmpesofu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.redwolf501.top/Article/details/gt2glwtowga.html

[U38] Py：获取脚本所在目录
来源：http://dali.yonumen.top/Article/details/gt2xmfrucdd.html

Path(__file__).resolve().parent
来源：http://dali.yuanzhike.top/Article/details/gt2pibohaen.html

[U39] Py：判断是否在交互环境
来源：http://dali.tianlin.xyz/Article/details/gt2rvmizmmo.html

sys.stdout.isatty()
来源：http://dali.ehwqpu.com/Article/details/gt2aosbykwx.html

[U40] Py：打印到标准错误
来源：http://dali.yonumen.top/Article/details/gt2dzgwuwag.html

print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gt2buwunzsl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fcxsdbek.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.316326.xyz/Article/details/gt2dcuqmmhc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.pycfn.com/Article/details/gt2ymceiuvo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2exhkegzm.html

[U43] PHP：声明命名空间
来源：http://dali.c1oappe.top/Article/details/gt2uibxmkje.html

namespace App\Http;
来源：http://dali.gotoacloud.top/Article/details/gt2hrrpaowm.html

[U44] PHP：开启严格类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xakpzzic.html

declare(strict_types=1);
来源：http://dali.jinqigfzy.top/Article/details/gt2gkadwvcl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.fengsongda.top/Article/details/gt2ymrzeetn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gt2nnqcrbul.html

[U46] PHP：可空类型
来源：http://dali.jqgfzy.top/Article/details/gt2kxqsqcje.html

?string $name = null
来源：http://dali.cheryme.top/Article/details/gt2isphoiln.html

[U47] PHP：联合类型
来源：http://dali.zhoulong.xyz/Article/details/gt2lauemryd.html

int|string $id
来源：http://dali.9152youxi.cn/Article/details/gt2ybbkyzwn.html

[U48] PHP：纯枚举
来源：http://dali.guannengcc.top/Article/details/gt2lwbejfgo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.fzhhl.top/Article/details/gt2plucgzdc.html

[U49] PHP：只读属性
来源：http://dali.ydzc1.top/Article/details/gt2gsydjzwu.html

public readonly string $name
来源：http://dali.aibaodan.cn/Article/details/gt2dwykucqc.html

[U50] PHP：构造器属性提升
来源：http://dali.gaohongyu789.top/Article/details/gt2uifzycyk.html

public function __construct(private int $id) {}
来源：http://dali.fzhhl.top/Article/details/gt2rmzxetns.html

[U51] PHP：数组解构
来源：http://dali.wangdashe.top/Article/details/gt2diqvuimj.html

[$a, $b] = $arr;
来源：http://dali.haohaochexian.top/Article/details/gt2zaogofya.html

[U52] PHP：箭头函数
来源：http://dali.hysaishi.cn/Article/details/gt2tpjvfhgn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhiwuduotai.top/Article/details/gt2kzqlbqop.html

[U53] PHP：空合并运算符
来源：http://dali.yongpay.top/Article/details/gt2jjaunhkg.html

$v = $a ?? $b ?? "default";
来源：http://dali.xylfe.cn/Article/details/gt2lwpgpifh.html

[U54] PHP：空安全调用
来源：http://dali.nanxuanxn.top/Article/details/gt2yqbsbszq.html

$obj?->method()
来源：http://dali.fengsongda.top/Article/details/gt2hrlrwbeh.html

[U55] PHP：match 表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2feihavpq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.fengsongda.top/Article/details/gt2ptcjujar.html

[U56] PHP：命名参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kegycvpu.html

f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2ichxaoot.html

[U57] PHP：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gt2igczfqwi.html

"值: {$a}"
来源：http://dali.yanxiufei.cn/Article/details/gt2khebkjse.html

[U58] PHP：数组三件套
来源：http://dali.fengsongda.top/Article/details/gt2rtjlgyfu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xinyue.icu/Article/details/gt2kmxpywjz.html

[U59] PHP：自定义排序
来源：http://dali.hnxiangtu.top/Article/details/gt2zjqjhrja.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2fbvxjdsp.html

[U60] PHP：JSON 编解码
来源：http://dali.cucudq.cn/Article/details/gt2lzajrdwc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ydzc1.top/Article/details/gt2upcswyvl.html

[U61] PHP：正则
来源：http://dali.c1oappe.top/Article/details/gt2zkqahvum.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2olvqthzh.html

[U62] PHP：日期对象
来源：http://dali.meibo888.top/Article/details/gt2chorrlxh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yueranfly.top/Article/details/gt2gjxtckgn.html

[U63] PHP：文件读写
来源：http://dali.9152youxi.cn/Article/details/gt2lxrtxuqq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.bjfxy.top/Article/details/gt2bbyejrnr.html

[U64] PHP：目录遍历
来源：http://dali.ppjwa.cn/Article/details/gt2lakcigbz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sysykeji.top/Article/details/gt2fkjzvgyu.html

[U65] PHP：会话
来源：http://dali.yj20258888.top/Article/details/gt2trluzojw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2icgyoqwd.html

[U66] PHP：设置 Cookie
来源：http://dali.jyoumei.cn/Article/details/gt2hghovrwt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jyoumei.cn/Article/details/gt2ooozgewq.html

[U67] PHP：处理文件上传
来源：http://dali.hysaishi.cn/Article/details/gt2tgnjlyob.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hnqzz.top/Article/details/gt2hurzjvgb.html

[U68] PHP：PDO 连接
来源：http://dali.aibaodan.cn/Article/details/gt2mhjziahx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yonumen.top/Article/details/gt2ptoqlqmu.html

[U69] PHP：PDO 预处理
来源：http://dali.jqgufenzy.top/Article/details/gt2gvotzqad.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.0kj1m.cn/Article/details/gt2ufpxgsmf.html

[U70] PHP：PDO 事务
来源：http://dali.shangyingyoupin.top/Article/details/gt2dsqsoyjo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sxryk.cn/Article/details/gt2atpchzoy.html

[U71] PHP：抛出异常
来源：http://dali.andypj.xyz/Article/details/gt2bjgudind.html

throw new RuntimeException("失败", 500);
来源：http://dali.ivvv.top/Article/details/gt2tdredpqz.html

[U72] PHP：写错误日志
来源：http://dali.c1oappe.top/Article/details/gt2wugbucbm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cqqwz.cn/Article/details/gt2kyggdvaz.html

[U73] PHP：读取 ini 配置
来源：http://dali.cucudq.cn/Article/details/gt2zrqedymf.html

parse_ini_file("config.ini", true)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rptwlkdu.html

[U74] PHP：读取环境变量
来源：http://dali.yj20258.top/Article/details/gt2xseosvqw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yuxming.cn/Article/details/gt2cncmawsj.html

[U75] PHP：依赖注入
来源：http://dali.wangdashe.top/Article/details/gt2hkurjsdz.html

composer require psr/container
来源：http://dali.havefunace.top/Article/details/gt2cgnzanii.html

[U76] PHP：简单路由
来源：http://dali.xziqi.cn/Article/details/gt2buawrhps.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.guowangkeji.top/Article/details/gt2deberamb.html

[U77] PHP：模板渲染
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wcaclhkt.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2taalhscm.html

[U78] PHP：单元测试
来源：http://dali.vqdsnc.cn/Article/details/gt2rvmjlghb.html

composer require --dev phpunit/phpunit
来源：http://dali.wangdashe.top/Article/details/gt2riwjubml.html

[U79] PHP：静态分析
来源：http://dali.yvedp.cn/Article/details/gt2irwuicar.html

composer require --dev phpstan/phpstan
来源：http://dali.hfpthk.cn/Article/details/gt2ptchrpwx.html

[U80] PHP：代码规范修复
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vqswsflq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.feifeiyinyue.top/Article/details/gt2wxyusfvu.html

[U81] JS：初始化项目
来源：http://dali.snrcjt.cn/Article/details/gt2bdhzaqti.html

npm init -y;  npm i express
来源：http://dali.316326.xyz/Article/details/gt2vmciandg.html

[U82] JS：package.json 脚本
来源：http://dali.yuanzhike.top/Article/details/gt2qvxaxiss.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.gzhubu.top/Article/details/gt2aazsbogr.html

[U83] JS：ES Module 导入导出
来源：http://dali.wangshuangyany.cn/Article/details/gt2gwscknco.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gt2gaqmapkr.html

[U84] JS：CommonJS 写法
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hybevfyk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bzkvuxhi.html

[U85] JS：可选链
来源：http://dali.yj20258888.top/Article/details/gt2feehkzac.html

a?.b?.c
来源：http://dali.kuanghao11.cn/Article/details/gt2wjtgtjzx.html

[U86] JS：空值合并
来源：http://dali.fzhhl.top/Article/details/gt2fdjopfsd.html

a ?? b
来源：http://dali.gaohongyu789.top/Article/details/gt2phimuqqf.html

[U87] JS：解构默认值
来源：http://dali.ivvv.top/Article/details/gt2fegjqafe.html

const { a = 1, b = 2 } = obj;
来源：http://dali.316326.xyz/Article/details/gt2haednsch.html

[U88] JS：对象展开合并
来源：http://dali.ybcxt.top/Article/details/gt2qprhltla.html

{ ...a, ...b }
来源：http://dali.yonumen.top/Article/details/gt2axppbunw.html

[U89] JS：数组去重
来源：http://dali.zhixingplan.top/Article/details/gt2jpjlpxge.html

[...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gt2aymoxuld.html

[U90] JS：数字数组排序
来源：http://dali.xuanzx.com/Article/details/gt2mowoasul.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gt2jthcgbej.html

[U91] JS：对象键值遍历
来源：http://dali.nanxinkj.top/Article/details/gt2vwaxvdgr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yvedp.cn/Article/details/gt2ecjjmybe.html

[U92] JS：深拷贝
来源：http://dali.jqgfzy.top/Article/details/gt2vfxnvquf.html

structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2zonanblb.html

[U93] JS：模板字符串
来源：http://dali.xuanzx.com/Article/details/gt2evphhsvq.html

`共 ${n} 条`
来源：http://dali.jyoumei.cn/Article/details/gt2mlhssmfd.html

[U94] JS：箭头函数
来源：http://dali.yongpay.top/Article/details/gt2iwfwtqdn.html

const double = x => x * 2;
来源：http://dali.xylfe.cn/Article/details/gt2uosmrbia.html

[U95] JS：Promise 包装
来源：http://dali.gogol.net.cn/Article/details/gt2zlhgmkey.html

new Promise((resolve, reject) => {})
来源：http://dali.sufxvd.cn/Article/details/gt2xtwtxmsf.html

[U96] JS：async/await 与异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2okzuhrjy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gt2juqfqoxn.html

[U97] JS：并发请求
来源：http://dali.nanxuanxn.top/Article/details/gt2cbdzotxo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gt2xnzsyavh.html

[U98] JS：fetch 带 JSON
来源：http://dali.hfpthk.cn/Article/details/gt2uyrbbkgd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.tianlin.xyz/Article/details/gt2pxsfbfnb.html

[U99] JS：事件监听
来源：http://dali.pengpengdd.cyou/Article/details/gt2psynpeqv.html

el.addEventListener("click", e => {})
来源：http://dali.fzhhl.top/Article/details/gt2kefqyhrm.html

[U100] JS：DOM 查询
来源：http://dali.mhx1999.top/Article/details/gt2hiivrvzo.html

document.querySelector(".item")
来源：http://dali.9152youxi.cn/Article/details/gt2wiauujsy.html

[U101] JS：classList 操作
来源：http://dali.meibo888.top/Article/details/gt2imtgnyfn.html

el.classList.toggle("active")
来源：http://dali.sxryk.cn/Article/details/gt2upqiwvsn.html

[U102] JS：本地存储
来源：http://dali.xinyue.icu/Article/details/gt2dszfafht.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yuxming.cn/Article/details/gt2pgpucllv.html

[U103] JS：定时器
来源：http://dali.pengpengdd.cyou/Article/details/gt2gncikkgv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.smart0.xyz/Article/details/gt2pzthrkbb.html

[U104] JS：防抖
来源：http://dali.nwbrower.top/Article/details/gt2dtnzayht.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gt2gophknno.html

[U105] JS：节流
来源：http://dali.hongshengwenyu.top/Article/details/gt2ijtunlmc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sxryk.cn/Article/details/gt2tkrerqrh.html

[U106] JS：日期格式化
来源：http://dali.zdqjudy.top/Article/details/gt2ktnsrhur.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ppjwa.cn/Article/details/gt2lkwmatxs.html

[U107] JS：数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gt2einpqqhz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.c1oappe.top/Article/details/gt2jkeulyvj.html

[U108] JS：随机整数
来源：http://dali.kuanghao11.cn/Article/details/gt2afntuswk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yj202588.top/Article/details/gt2volvfgtp.html

[U109] JS：数组分组
来源：http://dali.9152youxi.cn/Article/details/gt2lslzcbij.html

Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fpqyhkve.html

[U110] JS：数组分块
来源：http://dali.vqdsnc.cn/Article/details/gt2matmljlg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ydzc1.top/Article/details/gt2ckpfkwgl.html

[U111] JS：对象转 Map
来源：http://dali.yj20258888.top/Article/details/gt2kmuvvpay.html

new Map(Object.entries(obj))
来源：http://dali.jinqigfzy.top/Article/details/gt2svzkzsoh.html

[U112] JS：字符串补位
来源：http://dali.jqgufenzy.top/Article/details/gt2vmgzqszx.html

"7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2gsevwhfi.html

[U113] JS：正则替换全部
来源：http://dali.hammf.cn/Article/details/gt2jobtgxyv.html

s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2lrjqoqoe.html

[U114] JS：JSON 深比较
来源：http://dali.xziqi.cn/Article/details/gt2foaigjsi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gt2szksrbbo.html


<!-- 参考信息 -->