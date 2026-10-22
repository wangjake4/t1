代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.guannengcc.top/Article/details/gtfumonkvr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hammf.cn/Article/details/gtvumalvft.html

[T34] Lua：遍历表
来源：http://dali.vqdsnc.cn/Article/details/gtbmhwqjtz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xinyue.icu/Article/details/gtrobibzez.html

[T35] Lua：字典表
来源：http://dali.zycfv.cn/Article/details/gttfhyjezi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cashguo.top/Article/details/gtlvmsygng.html

[T36] Lua：函数
来源：http://dali.zhixingplan.top/Article/details/gtxvwjenoq.html

function add(a, b) return a + b end
来源：http://dali.guowangkeji.top/Article/details/gtmqfruykz.html

[T37] Lua：字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gtzydptrjb.html

"a" .. "b"
来源：http://dali.jianghu66.top/Article/details/gtpunfdwoy.html

[T38] Lua：条件
来源：http://dali.sysykeji.top/Article/details/gteqbqnojq.html

if x > 0 then print("正") end
来源：http://dali.tian-w.cn/Article/details/gtugwzslsz.html

[T39] Lua：模式匹配
来源：http://dali.tanke756.top/Article/details/gtfxpdfpnj.html

string.find(s, "%d+")
来源：http://dali.hammf.cn/Article/details/gtclwzrmbh.html

[T40] Lua：元表
来源：http://dali.sufxvd.cn/Article/details/gtxahlhrzm.html

setmetatable({}, { __index = base })
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxgfehza.html

[T41] Perl：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukuoiodt.html

print "Hello\n";
来源：http://dali.chenzaomai.com/Article/details/gtlojypcpt.html

[T42] Perl：变量类型
来源：http://dali.gotoacloud.top/Article/details/gtqqwhmuuk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhengqikj.top/Article/details/gtzwsgpugg.html

[T43] Perl：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxevbjypn.html

"值: $a"
来源：http://dali.shanyushiyangtech.top/Article/details/gtwiefylgq.html

[T44] Perl：条件
来源：http://dali.ppjwa.cn/Article/details/gtulcqqxji.html

if ($a > 0) { print "正"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtveghdhqq.html

[T45] Perl：数组遍历
来源：http://dali.tian-w.cn/Article/details/gtsprqrtfx.html

for my $x (@arr) { print $x; }
来源：http://dali.yj20258.top/Article/details/gtfwjbaitd.html

[T46] Perl：哈希操作
来源：http://dali.shuidangran.top/Article/details/gtjlzmitcm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.dashuyun.cn/Article/details/gtjpmdychq.html

[T47] Perl：正则捕获
来源：http://dali.yvedp.cn/Article/details/gtvytkhcgx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.andypj.xyz/Article/details/gtrhltmkyp.html

[T48] Perl：正则替换
来源：http://dali.xuanzx.com/Article/details/gtnlrnjsgx.html

$s =~ s/old/new/g;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhruglyz.html

[T49] Perl：函数
来源：http://dali.meibo888.top/Article/details/gtnhedimqu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtbxdcaiyd.html

[T50] Perl：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtfmrltrdm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.iojbl.cn/Article/details/gtuanmdrms.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xinyue.icu/Article/details/gtpjaisvrp.html

[T51] Scala：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbeuicprr.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtxueqgcer.html

[T52] Scala：变量
来源：http://dali.nwbrower.top/Article/details/gtrgksazjf.html

val a = 1;  var b = 2
来源：http://dali.zdqjudy.top/Article/details/gtsiqgfnxl.html

[T53] Scala：字符串插值
来源：http://dali.pycfn.com/Article/details/gtjgbceqis.html

s"值: $b"
来源：http://dali.fengsongda.top/Article/details/gtfvyuehcs.html

[T54] Scala：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzmepbib.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.pycfn.com/Article/details/gtkassoxij.html

[T55] Scala：集合过滤
来源：http://dali.cucudq.cn/Article/details/gtnxcgvybl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fengsongda.top/Article/details/gtvpapgibt.html

[T56] Scala：样例类
来源：http://dali.yvedp.cn/Article/details/gtnvohnqjd.html

case class User(name: String, age: Int)
来源：http://dali.nanxinkj.top/Article/details/gteitxquit.html

[T57] Scala：模式匹配
来源：http://dali.jyoumei.cn/Article/details/gtnhxhblte.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sysykeji.top/Article/details/gtskhrghcf.html

[T58] Scala：函数定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbontkoxc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xinyue.icu/Article/details/gtmvnbkwiy.html

[T59] Scala：循环
来源：http://dali.jlsjyb.cn/Article/details/gtkxyxylgv.html

for (i <- 1 to 10) println(i)
来源：http://dali.c1oappe.top/Article/details/gtuywrygzs.html

[T60] Scala：折叠
来源：http://dali.kuanghao11.cn/Article/details/gtwvzxokuz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hnxiangtu.top/Article/details/gtrjsgmiaj.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtoihrknvg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sweek.top/Article/details/gtgmbbgbdo.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtszhbxxjt.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigfzy.top/Article/details/gtfxuypatx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xinyue.icu/Article/details/gtpoelmunv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.snrcjt.cn/Article/details/gtjngsdres.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nanxuanxn.top/Article/details/gtidbtlsda.html

[U03] Py：加载 .env 配置
来源：http://dali.cqqwz.cn/Article/details/gtenbrazvw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hnxiangtu.top/Article/details/gtdoriryxj.html

[U04] Py：变量调试打印
来源：http://dali.tanke756.top/Article/details/gtnmnrmwlm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigufen.top/Article/details/gtbymsptqj.html

[U05] Py：列表去重且保序
来源：http://dali.redwolf501.top/Article/details/gtjntjebxt.html

list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gthwdhqrxi.html

[U06] Py：合并两个字典
来源：http://dali.sxryk.cn/Article/details/gtgqmaakak.html

{**a, **b}
来源：http://dali.yanxiufei.cn/Article/details/gtbxdmmlpp.html

[U07] Py：反转字典键值
来源：http://dali.gaohongyu789.top/Article/details/gttkahrdut.html

{v: k for k, v in d.items()}
来源：http://dali.jinghuilouyu.cn/Article/details/gtldzoaqib.html

[U08] Py：展平二维列表
来源：http://dali.zhengqikj.top/Article/details/gtskjfowha.html

[y for x in nested for y in x]
来源：http://dali.snrcjt.cn/Article/details/gtmktqlxnw.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258.top/Article/details/gtejkkfmzq.html

max(d, key=d.get)
来源：http://dali.tanke756.top/Article/details/gtiavznytc.html

[U10] Py：按值排序字典
来源：http://dali.chenlongwang.top/Article/details/gtlxscpvrj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xziqi.cn/Article/details/gtwtqxhzpm.html

[U11] Py：生成器表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtvkapimxh.html

(x * 2 for x in arr)
来源：http://dali.iojbl.cn/Article/details/gthrksqaat.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.aibaodan.cn/Article/details/gteqisckwl.html

Counter(arr).most_common(3)
来源：http://dali.316326.xyz/Article/details/gteggnpfjr.html

[U13] Py：固定长度队列
来源：http://dali.yj202588.top/Article/details/gtszfuhswi.html

deque(maxlen=10)
来源：http://dali.tian-w.cn/Article/details/gtzqgjomce.html

[U14] Py：分组收集到列表
来源：http://dali.chenzaomai.com/Article/details/gtgogsbmho.html

defaultdict(list)
来源：http://dali.yangfankeji.com/Article/details/gtxsmwtbdd.html

[U15] Py：高精度计时
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmscyohb.html

t = time.perf_counter()
来源：http://dali.jinghuilouyu.cn/Article/details/gtllwwqype.html

[U16] Py：命令行参数解析
来源：http://dali.chenjidiqi.icu/Article/details/gtjrkwflsf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.dashuyun.cn/Article/details/gtysbedwsk.html

[U17] Py：初始化日志
来源：http://dali.jinqigufen.top/Article/details/gtyrmcsmwt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xziqi.cn/Article/details/gthuisqryy.html

[U18] Py：预编译正则
来源：http://dali.pengpengdd.cyou/Article/details/gtaqvntboh.html

pat = re.compile(r"\d+")
来源：http://dali.yueranfly.top/Article/details/gtpwleihmp.html

[U19] Py：正则替换带回调
来源：http://dali.yonumen.top/Article/details/gthxpociym.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jiagoushi.top/Article/details/gtxoffoger.html

[U20] Py：缓存函数结果
来源：http://dali.ybcxt.top/Article/details/gtnchmtttd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shangyingyoupin.top/Article/details/gtlshnxjwm.html

[U21] Py：自定义上下文管理器
来源：http://dali.dianchejie.cn/Article/details/gtffkdqwuq.html

@contextlib.contextmanager
来源：http://dali.chenlongwang.top/Article/details/gtcmpuukrq.html

[U22] Py：矩阵转置
来源：http://dali.hfpthk.cn/Article/details/gtukprufns.html

list(zip(*m))
来源：http://dali.gogol.net.cn/Article/details/gtcbbzfdiv.html

[U23] Py：分块读取大文件
来源：http://dali.hysaishi.cn/Article/details/gtgcuzxkjg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zycfv.cn/Article/details/gtymeeefak.html

[U24] Py：路径操作
来源：http://dali.zycfv.cn/Article/details/gtankaibvi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gtgmecughk.html

[U25] Py：CSV 按字典读
来源：http://dali.316326.xyz/Article/details/gtzrxnulnn.html

csv.DictReader(f)
来源：http://dali.shzxlz.cn/Article/details/gtxggvpigd.html

[U26] Py：并发下载
来源：http://dali.hywenlv.cn/Article/details/gthiebfczj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.daria6918.cn/Article/details/gtebgxdqjm.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gtaissddko.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xuanzx.com/Article/details/gtaqaenljp.html

[U28] Py：类型别名
来源：http://dali.quarkkingdee.top/Article/details/gtdmuiooux.html

UserId = int
来源：http://dali.zdqjudy.top/Article/details/gtzbquziya.html

[U29] Py：属性校验
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlntkaljh.html

@property 与 @x.setter 配合
来源：http://dali.ehwqpu.com/Article/details/gtinzatvcr.html

[U30] Py：数据类
来源：http://dali.kuanghao11.cn/Article/details/gtffufpwxi.html

@dataclass(slots=True)
来源：http://dali.yanxiufei.cn/Article/details/gtrvzwwtny.html

[U31] Py：单测
来源：http://dali.fzhhl.top/Article/details/gtjrtzlkcy.html

python -m pytest -q
来源：http://dali.iojbl.cn/Article/details/gtqrbkdvlx.html

[U32] Py：代码格式化
来源：http://dali.yueranfly.top/Article/details/gtsalibihn.html

ruff format . && ruff check --fix .
来源：http://dali.jianghu66.top/Article/details/gttoqjvvwx.html

[U33] Py：打包发布
来源：http://dali.yj20258.top/Article/details/gtwgqpbdwb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.andypj.xyz/Article/details/gtoimpjeun.html

[U34] Py：判断编码
来源：http://dali.zhoulong.xyz/Article/details/gtigsffdfd.html

chardet.detect(raw)
来源：http://dali.hywenlv.cn/Article/details/gtlsxrmstb.html

[U35] Py：发送邮件
来源：http://dali.zhongyouzk.top/Article/details/gtntjrhntl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.daria6918.cn/Article/details/gtfokysyxv.html

[U36] Py：定时任务
来源：http://dali.smart0.xyz/Article/details/gtxzjkxnhc.html

schedule.every(10).minutes.do(job)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppllmoyc.html

[U37] Py：读写 Excel
来源：http://dali.gotoacloud.top/Article/details/gthgknswaw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.nwbrower.top/Article/details/gtazpkkvwq.html

[U38] Py：获取脚本所在目录
来源：http://dali.yonumen.top/Article/details/gtjuecdmgb.html

Path(__file__).resolve().parent
来源：http://dali.daria6918.cn/Article/details/gthyzxsbkv.html

[U39] Py：判断是否在交互环境
来源：http://dali.birdmap.top/Article/details/gtfzdihrnx.html

sys.stdout.isatty()
来源：http://dali.yj20258888.top/Article/details/gtgkmcbszc.html

[U40] Py：打印到标准错误
来源：http://dali.jinqigfzy.top/Article/details/gtgtxnonqd.html

print("err", file=sys.stderr)
来源：http://dali.ppjwa.cn/Article/details/gtrvxzmplr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.aibaodan.cn/Article/details/gthqhvsqkr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.nanxuanxn.top/Article/details/gtchqbbcnp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gzhubu.top/Article/details/gtrmtlczvs.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jyoumei.cn/Article/details/gtpllgkwcd.html

[U43] PHP：声明命名空间
来源：http://dali.sufxvd.cn/Article/details/gttsvtkbio.html

namespace App\Http;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsoewmtjc.html

[U44] PHP：开启严格类型
来源：http://dali.andypj.xyz/Article/details/gtpqdljhhx.html

declare(strict_types=1);
来源：http://dali.pengpengdd.cyou/Article/details/gtnlctwodd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhengqikj.top/Article/details/gtsfznuejo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtauyfonup.html

[U46] PHP：可空类型
来源：http://dali.zhixingplan.top/Article/details/gtfycpjtir.html

?string $name = null
来源：http://dali.aibaodan.cn/Article/details/gtcaakggmu.html

[U47] PHP：联合类型
来源：http://dali.guowangkeji.top/Article/details/gtbppwfafp.html

int|string $id
来源：http://dali.dashuyun.cn/Article/details/gtxhcbcmij.html

[U48] PHP：纯枚举
来源：http://dali.zdqjudy.top/Article/details/gtcjumjnaz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sysykeji.top/Article/details/gtungiyxjk.html

[U49] PHP：只读属性
来源：http://dali.hnxiangtu.top/Article/details/gtgskihhwb.html

public readonly string $name
来源：http://dali.shzxlz.cn/Article/details/gtbwrkgknf.html

[U50] PHP：构造器属性提升
来源：http://dali.9152youxi.cn/Article/details/gtbcoybpnb.html

public function __construct(private int $id) {}
来源：http://dali.yuanzhike.top/Article/details/gtdhenqowx.html

[U51] PHP：数组解构
来源：http://dali.birdmap.top/Article/details/gtabqasjlj.html

[$a, $b] = $arr;
来源：http://dali.yvedp.cn/Article/details/gtsdmjqqxa.html

[U52] PHP：箭头函数
来源：http://dali.yongpay.top/Article/details/gtmoqbfxoh.html

$double = fn($x) => $x * 2;
来源：http://dali.tian-w.cn/Article/details/gtrizswjjp.html

[U53] PHP：空合并运算符
来源：http://dali.316326.xyz/Article/details/gtywcyvhcd.html

$v = $a ?? $b ?? "default";
来源：http://dali.yj202588.top/Article/details/gtpxymfrkf.html

[U54] PHP：空安全调用
来源：http://dali.hongshengwenyu.top/Article/details/gtnpzzmdju.html

$obj?->method()
来源：http://dali.mhx1999.top/Article/details/gtldfilpng.html

[U55] PHP：match 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtjqwfsjtx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gtlzxrgucw.html

[U56] PHP：命名参数
来源：http://dali.ydzc1.top/Article/details/gtrwnenzqr.html

f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gtnwpluaxd.html

[U57] PHP：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtpztewssd.html

"值: {$a}"
来源：http://dali.9152youxi.cn/Article/details/gtlmglrxdn.html

[U58] PHP：数组三件套
来源：http://dali.iojbl.cn/Article/details/gtagcighlq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zycfv.cn/Article/details/gtcssycjfm.html

[U59] PHP：自定义排序
来源：http://dali.dianchejie.cn/Article/details/gtboqbngae.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sysykeji.top/Article/details/gtvxetqwce.html

[U60] PHP：JSON 编解码
来源：http://dali.dianchejie.cn/Article/details/gtywmahwwa.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.c1oappe.top/Article/details/gthmeiinib.html

[U61] PHP：正则
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimecmrpm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gtntyperah.html

[U62] PHP：日期对象
来源：http://dali.bjfxy.top/Article/details/gtmkcoirfk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.feifeiyinyue.top/Article/details/gtscbvsjek.html

[U63] PHP：文件读写
来源：http://dali.jiagoushi.top/Article/details/gtherszagc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.chenlongwang.top/Article/details/gtsetpwmoe.html

[U64] PHP：目录遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtgsqadack.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.aibaodan.cn/Article/details/gtqzffonzj.html

[U65] PHP：会话
来源：http://dali.yj20258888.top/Article/details/gtqjdxmuek.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtxqgkussf.html

[U66] PHP：设置 Cookie
来源：http://dali.tanke756.top/Article/details/gtutuvdjjt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zdqjudy.top/Article/details/gtqmurafkj.html

[U67] PHP：处理文件上传
来源：http://dali.zhiwuduotai.top/Article/details/gtuertccmb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.nwbrower.top/Article/details/gtsumjoqmc.html

[U68] PHP：PDO 连接
来源：http://dali.bjfxy.top/Article/details/gtgbcnvdjk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.fengsongda.top/Article/details/gtylsbiqwm.html

[U69] PHP：PDO 预处理
来源：http://dali.guowangkeji.top/Article/details/gtocxmysbx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiiqmcybf.html

[U70] PHP：PDO 事务
来源：http://dali.hongshengwenyu.top/Article/details/gtyskuzpba.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xuanzx.com/Article/details/gtmeytxges.html

[U71] PHP：抛出异常
来源：http://dali.gaohongyu789.top/Article/details/gtuirjrfou.html

throw new RuntimeException("失败", 500);
来源：http://dali.jlsjyb.cn/Article/details/gtkhhgjugb.html

[U72] PHP：写错误日志
来源：http://dali.svipenyu.cn/Article/details/gtdhuxwxvm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.9152youxi.cn/Article/details/gtsrwrvnme.html

[U73] PHP：读取 ini 配置
来源：http://dali.cashguo.top/Article/details/gtdubnybdh.html

parse_ini_file("config.ini", true)
来源：http://dali.nanxinkj.top/Article/details/gtnrwpcphd.html

[U74] PHP：读取环境变量
来源：http://dali.aizwys.cn/Article/details/gtpqqcrrmp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.dianchejie.cn/Article/details/gtsaijryxm.html

[U75] PHP：依赖注入
来源：http://dali.shzxlz.cn/Article/details/gtiubupdlu.html

composer require psr/container
来源：http://dali.hnqzz.top/Article/details/gtvphmiebs.html

[U76] PHP：简单路由
来源：http://dali.guowangkeji.top/Article/details/gtjradtiyc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.chenlongwang.top/Article/details/gtxxebjzad.html

[U77] PHP：模板渲染
来源：http://dali.fzhhl.top/Article/details/gtpdojwgbu.html

composer require twig/twig
来源：http://dali.yuxming.cn/Article/details/gtqoaxovjk.html

[U78] PHP：单元测试
来源：http://dali.smart0.xyz/Article/details/gtwjvgjroy.html

composer require --dev phpunit/phpunit
来源：http://dali.pengpengdd.cyou/Article/details/gtofvpyulm.html

[U79] PHP：静态分析
来源：http://dali.aibaodan.cn/Article/details/gtlneadwlf.html

composer require --dev phpstan/phpstan
来源：http://dali.fengsongda.top/Article/details/gtzyocfyvp.html

[U80] PHP：代码规范修复
来源：http://dali.tianlin.xyz/Article/details/gtpbhcmnhp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sweek.top/Article/details/gtavubvevc.html

[U81] JS：初始化项目
来源：http://dali.zhixingplan.top/Article/details/gtlsasptmo.html

npm init -y;  npm i express
来源：http://dali.xziqi.cn/Article/details/gtmgfeyhnb.html

[U82] JS：package.json 脚本
来源：http://dali.yuanzhike.top/Article/details/gtupimbmef.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zycfv.cn/Article/details/gtniyqzofw.html

[U83] JS：ES Module 导入导出
来源：http://dali.snrcjt.cn/Article/details/gtnlwiuqyc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.daxiang520.top/Article/details/gtmiwdrlnq.html

[U84] JS：CommonJS 写法
来源：http://dali.jinqigfzy.top/Article/details/gtfhakouyz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjimpwkl.html

[U85] JS：可选链
来源：http://dali.sweek.top/Article/details/gtgacgyivg.html

a?.b?.c
来源：http://dali.ppjwa.cn/Article/details/gteasptdpy.html

[U86] JS：空值合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecjksohx.html

a ?? b
来源：http://dali.chenjidiqi.icu/Article/details/gtsxyukyoc.html

[U87] JS：解构默认值
来源：http://dali.xuanzx.com/Article/details/gtcbdmjdjc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jqgufenzy.top/Article/details/gtcxqjqgcd.html

[U88] JS：对象展开合并
来源：http://dali.quarkkingdee.top/Article/details/gtwgbjuubj.html

{ ...a, ...b }
来源：http://dali.hywenlv.cn/Article/details/gtpcioefeu.html

[U89] JS：数组去重
来源：http://dali.ppjwa.cn/Article/details/gtfbvhkebw.html

[...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gtplfubxyl.html

[U90] JS：数字数组排序
来源：http://dali.mhx1999.top/Article/details/gtawvqyvan.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmxwwqkf.html

[U91] JS：对象键值遍历
来源：http://dali.hammf.cn/Article/details/gtnrawyzsm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gttojlnxth.html

[U92] JS：深拷贝
来源：http://dali.xziqi.cn/Article/details/gtulbnvxtd.html

structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtihpmxvkp.html

[U93] JS：模板字符串
来源：http://dali.9152youxi.cn/Article/details/gtdghgiopx.html

`共 ${n} 条`
来源：http://dali.nwbrower.top/Article/details/gtpugdhdkr.html

[U94] JS：箭头函数
来源：http://dali.wangshuangyany.cn/Article/details/gtsppzjtsz.html

const double = x => x * 2;
来源：http://dali.snrcjt.cn/Article/details/gtikjhfdgq.html

[U95] JS：Promise 包装
来源：http://dali.yueranfly.top/Article/details/gthpfvnynf.html

new Promise((resolve, reject) => {})
来源：http://dali.jqgfzy.top/Article/details/gtzotgcijr.html

[U96] JS：async/await 与异常
来源：http://dali.svipenyu.cn/Article/details/gtbiyvbysx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtilwmbjou.html

[U97] JS：并发请求
来源：http://dali.sweek.top/Article/details/gthpgauawh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmxwqtky.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gtkimypypq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.redwolf501.top/Article/details/gtcwczttsq.html

[U99] JS：事件监听
来源：http://dali.dashuyun.cn/Article/details/gtjxjhzwnv.html

el.addEventListener("click", e => {})
来源：http://dali.dashuyun.cn/Article/details/gtmxrnouer.html

[U100] JS：DOM 查询
来源：http://dali.meibo888.top/Article/details/gtazgcncoh.html

document.querySelector(".item")
来源：http://dali.zdqjudy.top/Article/details/gtcvyhuvii.html

[U101] JS：classList 操作
来源：http://dali.hammf.cn/Article/details/gtndtcvhpc.html

el.classList.toggle("active")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzghuuvy.html

[U102] JS：本地存储
来源：http://dali.zdqjudy.top/Article/details/gtkfvhuwgs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xinyue.icu/Article/details/gturjmpevz.html

[U103] JS：定时器
来源：http://dali.chenlongwang.top/Article/details/gtqxisuzef.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yonumen.top/Article/details/gtanwkcara.html

[U104] JS：防抖
来源：http://dali.pengpengdd.cyou/Article/details/gtsoomimjc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gtgcmpkzfx.html

[U105] JS：节流
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfdmhacu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtwiprqygn.html

[U106] JS：日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqntkdgv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cqqwz.cn/Article/details/gtzjiccgcq.html

[U107] JS：数字千分位
来源：http://dali.gogol.net.cn/Article/details/gtumwgroli.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gtkwnpduao.html

[U108] JS：随机整数
来源：http://dali.yuxming.cn/Article/details/gtacqkufft.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.aizwys.cn/Article/details/gtfuuolzxd.html

[U109] JS：数组分组
来源：http://dali.guannengcc.top/Article/details/gttylswooc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gtuwkzfshe.html

[U110] JS：数组分块
来源：http://dali.yangfankeji.com/Article/details/gtsrwkvlga.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shuidangran.top/Article/details/gtqdwoazvb.html

[U111] JS：对象转 Map
来源：http://dali.yongpay.top/Article/details/gtpjnebqms.html

new Map(Object.entries(obj))
来源：http://dali.cashguo.top/Article/details/gtsbzwxiyl.html

[U112] JS：字符串补位
来源：http://dali.yvedp.cn/Article/details/gtvmbwywbj.html

"7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gttkvcdxto.html

[U113] JS：正则替换全部
来源：http://dali.nanxinkj.top/Article/details/gtqdlencyr.html

s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtguiahqbv.html

[U114] JS：JSON 深比较
来源：http://dali.xuetiantiany.cn/Article/details/gtosyfpszi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigufen.top/Article/details/gtzlrognkh.html

[U115] JS：生成 UUID
来源：http://dali.snrcjt.cn/Article/details/gtsablnogb.html

crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gthfoiymcs.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xuanzx.com/Article/details/gtcgrvywlg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj20258.top/Article/details/gtdchywlxd.html

[U117] JS：单元测试
来源：http://dali.zdqjudy.top/Article/details/gtrhbobhoj.html

npm i -D vitest;  npx vitest
来源：http://dali.jqgfzy.top/Article/details/gtlojljjff.html

[U118] JS：开发服务器
来源：http://dali.yonumen.top/Article/details/gtcuxykjmn.html

npm i -D vite;  npx vite
来源：http://dali.shzxlz.cn/Article/details/gtdobtrgnz.html

[U119] JS：生产构建
来源：http://dali.zhixingplan.top/Article/details/gtyuuwvpuf.html

npx vite build
来源：http://dali.chenjidiqi.icu/Article/details/gtvsbcgetv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhoulong.xyz/Article/details/gtpgxskxye.html

import.meta.env.VITE_API_URL
来源：http://dali.wangshuangyany.cn/Article/details/gtmizaniay.html


<!-- 参考信息 -->