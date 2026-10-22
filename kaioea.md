代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.ppjwa.cn/Article/details/gtgefykabc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnxiangtu.top/Article/details/gtlhuqzhtj.html

[T34] Lua：遍历表
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjcujlgj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.bjfxy.top/Article/details/gtzsazdkmz.html

[T35] Lua：字典表
来源：http://dali.shangyingyoupin.top/Article/details/gtsxtqpmtm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.aizwys.cn/Article/details/gtkoshlfnb.html

[T36] Lua：函数
来源：http://dali.shzxlz.cn/Article/details/gtvbkffhqe.html

function add(a, b) return a + b end
来源：http://dali.nanxinkj.top/Article/details/gthbricyet.html

[T37] Lua：字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtxhjfneur.html

"a" .. "b"
来源：http://dali.aizwys.cn/Article/details/gtlxagocnc.html

[T38] Lua：条件
来源：http://dali.aibaodan.cn/Article/details/gtoqhgrfiv.html

if x > 0 then print("正") end
来源：http://dali.jqgfzy.top/Article/details/gtyeevnajj.html

[T39] Lua：模式匹配
来源：http://dali.quarkkingdee.top/Article/details/gtjpvfpowr.html

string.find(s, "%d+")
来源：http://dali.smart0.xyz/Article/details/gtuhxunhvp.html

[T40] Lua：元表
来源：http://dali.zhongyouzk.top/Article/details/gtzuacmgys.html

setmetatable({}, { __index = base })
来源：http://dali.smart0.xyz/Article/details/gtewgpdbmz.html

[T41] Perl：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtjgdqvzto.html

print "Hello\n";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxymywho.html

[T42] Perl：变量类型
来源：http://dali.zhiwuduotai.top/Article/details/gtsvcifyzw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xziqi.cn/Article/details/gtlmmgjnok.html

[T43] Perl：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtjggkuhtd.html

"值: $a"
来源：http://dali.ydzc1.top/Article/details/gtlotluluh.html

[T44] Perl：条件
来源：http://dali.zhoulong.xyz/Article/details/gtopkwriak.html

if ($a > 0) { print "正"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqjjkjsl.html

[T45] Perl：数组遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtqkwjfvsi.html

for my $x (@arr) { print $x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdchydqux.html

[T46] Perl：哈希操作
来源：http://dali.chenjidiqi.icu/Article/details/gtglrmeyaa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.kuanghao11.cn/Article/details/gtxjbbjtjz.html

[T47] Perl：正则捕获
来源：http://dali.guowangkeji.top/Article/details/gtnyqtxzlq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guannengcc.top/Article/details/gtexmunsxt.html

[T48] Perl：正则替换
来源：http://dali.pycfn.com/Article/details/gtujmbiayy.html

$s =~ s/old/new/g;
来源：http://dali.0kj1m.cn/Article/details/gtlkbpxwvq.html

[T49] Perl：函数
来源：http://dali.guowangkeji.top/Article/details/gtrxifeech.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtnqyrajcd.html

[T50] Perl：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtlikmcrqz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.wangdashe.top/Article/details/gtelfiamct.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj20258.top/Article/details/gtmrutnkua.html

[T51] Scala：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtfreanyax.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gtohevwqrw.html

[T52] Scala：变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnyorpqi.html

val a = 1;  var b = 2
来源：http://dali.tianlin.xyz/Article/details/gtocgbjeip.html

[T53] Scala：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtqoplicwv.html

s"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gttrixotkf.html

[T54] Scala：集合映射
来源：http://dali.ppjwa.cn/Article/details/gtpjlxpaor.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ppjwa.cn/Article/details/gtcrcamcmf.html

[T55] Scala：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gtbhyursaa.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hywenlv.cn/Article/details/gtorfsxthn.html

[T56] Scala：样例类
来源：http://dali.yuxming.cn/Article/details/gtedlypnkd.html

case class User(name: String, age: Int)
来源：http://dali.sweek.top/Article/details/gtxsbjpiyi.html

[T57] Scala：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtpykzdkzq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhoulong.xyz/Article/details/gtmltcncfb.html

[T58] Scala：函数定义
来源：http://dali.jqgfzy.top/Article/details/gtssenoejc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daria6918.cn/Article/details/gtttmmvxck.html

[T59] Scala：循环
来源：http://dali.feifeiyinyue.top/Article/details/gtjdscdxua.html

for (i <- 1 to 10) println(i)
来源：http://dali.cucudq.cn/Article/details/gtczsdnjbn.html

[T60] Scala：折叠
来源：http://dali.yj20258888.top/Article/details/gtbvgpcmrm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.guowangkeji.top/Article/details/gtcdfxtjcq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gttrmsoaig.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xinyue.icu/Article/details/gteastngqk.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtlmctpbti.html

[U01] Py：创建虚拟环境
来源：http://dali.birdmap.top/Article/details/gtviwaeicv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xziqi.cn/Article/details/gtkcmluvaq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tianlin.xyz/Article/details/gtfpbgjiob.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hnxiangtu.top/Article/details/gtrraunkca.html

[U03] Py：加载 .env 配置
来源：http://dali.ydzc1.top/Article/details/gtgxlnhkmc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenzaomai.com/Article/details/gtzbhmzccz.html

[U04] Py：变量调试打印
来源：http://dali.c1oappe.top/Article/details/gtgzlthtce.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gaohongyu789.top/Article/details/gtgfeoidrb.html

[U05] Py：列表去重且保序
来源：http://dali.zdqjudy.top/Article/details/gtvshwcttb.html

list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gtsoolypju.html

[U06] Py：合并两个字典
来源：http://dali.cheryme.top/Article/details/gtqxirothh.html

{**a, **b}
来源：http://dali.zhongyouzk.top/Article/details/gtpgtswsyk.html

[U07] Py：反转字典键值
来源：http://dali.snrcjt.cn/Article/details/gtdiplnsie.html

{v: k for k, v in d.items()}
来源：http://dali.ivvv.top/Article/details/gtqouggcba.html

[U08] Py：展平二维列表
来源：http://dali.pengpengdd.cyou/Article/details/gtleknowob.html

[y for x in nested for y in x]
来源：http://dali.quarkkingdee.top/Article/details/gtzoxgdign.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigufen.top/Article/details/gtnteztrmf.html

max(d, key=d.get)
来源：http://dali.guowangkeji.top/Article/details/gtniyuuwes.html

[U10] Py：按值排序字典
来源：http://dali.hywenlv.cn/Article/details/gtkgnaelep.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigfzy.top/Article/details/gteudznrml.html

[U11] Py：生成器表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgartdcad.html

(x * 2 for x in arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxitrcwwi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ppjwa.cn/Article/details/gtwmxqaygg.html

Counter(arr).most_common(3)
来源：http://dali.yonumen.top/Article/details/gtffkrntel.html

[U13] Py：固定长度队列
来源：http://dali.nanxuanxn.top/Article/details/gtrtatoveq.html

deque(maxlen=10)
来源：http://dali.sxryk.cn/Article/details/gtalozuhoo.html

[U14] Py：分组收集到列表
来源：http://dali.316326.xyz/Article/details/gtvrmwigid.html

defaultdict(list)
来源：http://dali.0kj1m.cn/Article/details/gtwfhumvza.html

[U15] Py：高精度计时
来源：http://dali.xylfe.cn/Article/details/gtstzzihpc.html

t = time.perf_counter()
来源：http://dali.birdmap.top/Article/details/gtmqpvdvtt.html

[U16] Py：命令行参数解析
来源：http://dali.iojbl.cn/Article/details/gtahssuyon.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zdqjudy.top/Article/details/gtjkhustdq.html

[U17] Py：初始化日志
来源：http://dali.sysykeji.top/Article/details/gtozksxphk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.9152youxi.cn/Article/details/gtxshvppvi.html

[U18] Py：预编译正则
来源：http://dali.zhiwuduotai.top/Article/details/gtfznipwaz.html

pat = re.compile(r"\d+")
来源：http://dali.andypj.xyz/Article/details/gtmhmtjmzd.html

[U19] Py：正则替换带回调
来源：http://dali.snrcjt.cn/Article/details/gtwfdqkbur.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sufxvd.cn/Article/details/gtjiasrxrk.html

[U20] Py：缓存函数结果
来源：http://dali.gaohongyu789.top/Article/details/gtazfupcch.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shzxlz.cn/Article/details/gtdfjxhxvx.html

[U21] Py：自定义上下文管理器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvwygbxx.html

@contextlib.contextmanager
来源：http://dali.vqdsnc.cn/Article/details/gtejdtzwnr.html

[U22] Py：矩阵转置
来源：http://dali.yangfankeji.com/Article/details/gtnqiysnkg.html

list(zip(*m))
来源：http://dali.gotoacloud.top/Article/details/gtxfosviuq.html

[U23] Py：分块读取大文件
来源：http://dali.hfpthk.cn/Article/details/gthnwlgrdp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jianghu66.top/Article/details/gthuqoslnx.html

[U24] Py：路径操作
来源：http://dali.gzhubu.top/Article/details/gtwazyjlce.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gtzbwdccdn.html

[U25] Py：CSV 按字典读
来源：http://dali.meibo888.top/Article/details/gthmoqalbk.html

csv.DictReader(f)
来源：http://dali.wangshuangyany.cn/Article/details/gtqoyprpld.html

[U26] Py：并发下载
来源：http://dali.aizwys.cn/Article/details/gtvxcjipyf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pycfn.com/Article/details/gtwwvgxznq.html

[U27] Py：异步 HTTP
来源：http://dali.tianlin.xyz/Article/details/gtmckdisde.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.svipenyu.cn/Article/details/gtphhjdtsp.html

[U28] Py：类型别名
来源：http://dali.zycfv.cn/Article/details/gtoyomkwur.html

UserId = int
来源：http://dali.guannengcc.top/Article/details/gtilmfjvxz.html

[U29] Py：属性校验
来源：http://dali.chenlongwang.top/Article/details/gtkikoyvhy.html

@property 与 @x.setter 配合
来源：http://dali.jqgufenzy.top/Article/details/gtlbtlimlj.html

[U30] Py：数据类
来源：http://dali.yj20258.top/Article/details/gtoaffoxeh.html

@dataclass(slots=True)
来源：http://dali.tanke756.top/Article/details/gtzqqgvuah.html

[U31] Py：单测
来源：http://dali.ehwqpu.com/Article/details/gtsjauqjzj.html

python -m pytest -q
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwldvykdc.html

[U32] Py：代码格式化
来源：http://dali.guowangkeji.top/Article/details/gtplhxhwwx.html

ruff format . && ruff check --fix .
来源：http://dali.nanxuanxn.top/Article/details/gtagowckbs.html

[U33] Py：打包发布
来源：http://dali.ehwqpu.com/Article/details/gtfnugszeh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ybcxt.top/Article/details/gtvytfjldh.html

[U34] Py：判断编码
来源：http://dali.vqdsnc.cn/Article/details/gtbvfqjvqt.html

chardet.detect(raw)
来源：http://dali.gotoacloud.top/Article/details/gtxlmgbset.html

[U35] Py：发送邮件
来源：http://dali.vqdsnc.cn/Article/details/gtxvtdbxso.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.vqdsnc.cn/Article/details/gtsegpdcri.html

[U36] Py：定时任务
来源：http://dali.xuetiantiany.cn/Article/details/gtgegjfaol.html

schedule.every(10).minutes.do(job)
来源：http://dali.shanyushiyangtech.top/Article/details/gtutktbbkp.html

[U37] Py：读写 Excel
来源：http://dali.meibo888.top/Article/details/gtweudgcqx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ehwqpu.com/Article/details/gtvzwyhoot.html

[U38] Py：获取脚本所在目录
来源：http://dali.vqdsnc.cn/Article/details/gtsxzafpez.html

Path(__file__).resolve().parent
来源：http://dali.yuxming.cn/Article/details/gtcgrortax.html

[U39] Py：判断是否在交互环境
来源：http://dali.dashuyun.cn/Article/details/gteejjpxsh.html

sys.stdout.isatty()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddmctymu.html

[U40] Py：打印到标准错误
来源：http://dali.316326.xyz/Article/details/gteqceyohe.html

print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gtqtyyinnp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shuidangran.top/Article/details/gtzsfuxqlf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tian-w.cn/Article/details/gtfftwbrmm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.fzhhl.top/Article/details/gtflltfyur.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ppjwa.cn/Article/details/gtjlzjgjfr.html

[U43] PHP：声明命名空间
来源：http://dali.hnxiangtu.top/Article/details/gtcjkoimuu.html

namespace App\Http;
来源：http://dali.birdmap.top/Article/details/gtijhuwsms.html

[U44] PHP：开启严格类型
来源：http://dali.ppjwa.cn/Article/details/gtnrfdgqyt.html

declare(strict_types=1);
来源：http://dali.yj202588.top/Article/details/gtkapeufgj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.svipenyu.cn/Article/details/gtdyfvxqcs.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzxqhgcj.html

[U46] PHP：可空类型
来源：http://dali.xuanzx.com/Article/details/gtidmizasi.html

?string $name = null
来源：http://dali.jqgufenzy.top/Article/details/gtocuimxio.html

[U47] PHP：联合类型
来源：http://dali.zycfv.cn/Article/details/gtepytnmzm.html

int|string $id
来源：http://dali.zhixingplan.top/Article/details/gtrasnqzhh.html

[U48] PHP：纯枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtajnrjdja.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zdqjudy.top/Article/details/gtijezncli.html

[U49] PHP：只读属性
来源：http://dali.mhx1999.top/Article/details/gtpunwtbuj.html

public readonly string $name
来源：http://dali.ybcxt.top/Article/details/gtxbtcatcl.html

[U50] PHP：构造器属性提升
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnueflprr.html

public function __construct(private int $id) {}
来源：http://dali.nanxuanxn.top/Article/details/gtqsbchjad.html

[U51] PHP：数组解构
来源：http://dali.wangdashe.top/Article/details/gtsfqvnxib.html

[$a, $b] = $arr;
来源：http://dali.nanxinkj.top/Article/details/gtretqddad.html

[U52] PHP：箭头函数
来源：http://dali.kuanghao11.cn/Article/details/gtfyukiiit.html

$double = fn($x) => $x * 2;
来源：http://dali.wangdashe.top/Article/details/gtrodwczhf.html

[U53] PHP：空合并运算符
来源：http://dali.fengsongda.top/Article/details/gtfxjyeaim.html

$v = $a ?? $b ?? "default";
来源：http://dali.ivvv.top/Article/details/gtklwfjzbt.html

[U54] PHP：空安全调用
来源：http://dali.cashguo.top/Article/details/gtlbirwoba.html

$obj?->method()
来源：http://dali.cqqwz.cn/Article/details/gtycbntrde.html

[U55] PHP：match 表达式
来源：http://dali.jlsjyb.cn/Article/details/gthubsvxgz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hysaishi.cn/Article/details/gtxosyanub.html

[U56] PHP：命名参数
来源：http://dali.tanke756.top/Article/details/gtcrofduyz.html

f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gtvxhtzwam.html

[U57] PHP：字符串插值
来源：http://dali.sweek.top/Article/details/gtadoimegx.html

"值: {$a}"
来源：http://dali.tianlin.xyz/Article/details/gtcemgjzqz.html

[U58] PHP：数组三件套
来源：http://dali.guannengcc.top/Article/details/gtjbwwharg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtcjawsmog.html

[U59] PHP：自定义排序
来源：http://dali.aizwys.cn/Article/details/gtxdczbyjq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifvoxipx.html

[U60] PHP：JSON 编解码
来源：http://dali.hammf.cn/Article/details/gtzrlsknxz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.quarkkingdee.top/Article/details/gtdxpfdjoj.html

[U61] PHP：正则
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxgugqrg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gtfsevnzap.html

[U62] PHP：日期对象
来源：http://dali.fzhhl.top/Article/details/gtgegsgzwq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.pengpengdd.cyou/Article/details/gtyxrxxoss.html

[U63] PHP：文件读写
来源：http://dali.aizwys.cn/Article/details/gtloeezdyh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hongshengwenyu.top/Article/details/gtqbvppuqz.html

[U64] PHP：目录遍历
来源：http://dali.fzhhl.top/Article/details/gtkdqcfqgo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jqgfzy.top/Article/details/gtevyjxcto.html

[U65] PHP：会话
来源：http://dali.jinghuilouyu.cn/Article/details/gtcorryocy.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtuaxksbtx.html

[U66] PHP：设置 Cookie
来源：http://dali.sysykeji.top/Article/details/gtitnypdmm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.haohaochexian.top/Article/details/gttboudthn.html

[U67] PHP：处理文件上传
来源：http://dali.haohaochexian.top/Article/details/gthrypkqhi.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yongpay.top/Article/details/gtqvltgvqv.html

[U68] PHP：PDO 连接
来源：http://dali.tanke756.top/Article/details/gteelweput.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.daxiang520.top/Article/details/gtnsybghua.html

[U69] PHP：PDO 预处理
来源：http://dali.dashuyun.cn/Article/details/gtugxkueis.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yongpay.top/Article/details/gthvfkyiyz.html

[U70] PHP：PDO 事务
来源：http://dali.cqqwz.cn/Article/details/gtpgjshgjp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.daria6918.cn/Article/details/gtxizdqtcu.html

[U71] PHP：抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbudwqwl.html

throw new RuntimeException("失败", 500);
来源：http://dali.xuetiantiany.cn/Article/details/gtoulsvmtm.html

[U72] PHP：写错误日志
来源：http://dali.wangdashe.top/Article/details/gtlugysgdx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zdqjudy.top/Article/details/gtxpmtkqdm.html

[U73] PHP：读取 ini 配置
来源：http://dali.hnxiangtu.top/Article/details/gtjdmqplvl.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gtahymexjv.html

[U74] PHP：读取环境变量
来源：http://dali.tianlin.xyz/Article/details/gttmdktdja.html

getenv("APP_ENV") ?: "production"
来源：http://dali.quarkkingdee.top/Article/details/gtkntebhsd.html

[U75] PHP：依赖注入
来源：http://dali.yanxiufei.cn/Article/details/gtvtpxkujt.html

composer require psr/container
来源：http://dali.hnxiangtu.top/Article/details/gtvozzzdal.html

[U76] PHP：简单路由
来源：http://dali.shzxlz.cn/Article/details/gtegnkmnps.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yj20258.top/Article/details/gtreehicse.html

[U77] PHP：模板渲染
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgrcxgwm.html

composer require twig/twig
来源：http://dali.wangdashe.top/Article/details/gtzszvrcey.html

[U78] PHP：单元测试
来源：http://dali.gaohongyu789.top/Article/details/gttirreypm.html

composer require --dev phpunit/phpunit
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqtmqlwm.html

[U79] PHP：静态分析
来源：http://dali.mhx1999.top/Article/details/gtcuqeghsb.html

composer require --dev phpstan/phpstan
来源：http://dali.xuetiantiany.cn/Article/details/gtcjazgpjm.html

[U80] PHP：代码规范修复
来源：http://dali.yongpay.top/Article/details/gtyxbuboqj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yj20258.top/Article/details/gtxfpuuntt.html

[U81] JS：初始化项目
来源：http://dali.yj20258.top/Article/details/gtdksexwyo.html

npm init -y;  npm i express
来源：http://dali.hammf.cn/Article/details/gtljpnqkyl.html

[U82] JS：package.json 脚本
来源：http://dali.jianghu66.top/Article/details/gtvnafeyzk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sweek.top/Article/details/gtypnbecgv.html

[U83] JS：ES Module 导入导出
来源：http://dali.hywenlv.cn/Article/details/gtseuervbj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yj20258888.top/Article/details/gtveskgwqb.html

[U84] JS：CommonJS 写法
来源：http://dali.tian-w.cn/Article/details/gtyhcreogg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.iojbl.cn/Article/details/gtgyztnnpi.html

[U85] JS：可选链
来源：http://dali.wangshuangyany.cn/Article/details/gtewsigdyb.html

a?.b?.c
来源：http://dali.hongshengwenyu.top/Article/details/gtoxyxqabq.html

[U86] JS：空值合并
来源：http://dali.jqgfzy.top/Article/details/gtssalzzah.html

a ?? b
来源：http://dali.jyoumei.cn/Article/details/gtrmoppnib.html

[U87] JS：解构默认值
来源：http://dali.tianlin.xyz/Article/details/gtmmcmkluh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hysaishi.cn/Article/details/gthakncmeu.html

[U88] JS：对象展开合并
来源：http://dali.ybcxt.top/Article/details/gtkxufnhqs.html

{ ...a, ...b }
来源：http://dali.daria6918.cn/Article/details/gtwauetqtg.html

[U89] JS：数组去重
来源：http://dali.jiagoushi.top/Article/details/gtpidtaqsd.html

[...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gthnwutccf.html

[U90] JS：数字数组排序
来源：http://dali.tian-w.cn/Article/details/gtbllaiyfs.html

[...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gtebrycdsg.html

[U91] JS：对象键值遍历
来源：http://dali.ehwqpu.com/Article/details/gthowrtsaw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cheryme.top/Article/details/gtaiiohbqz.html

[U92] JS：深拷贝
来源：http://dali.jiagoushi.top/Article/details/gtqgapokxk.html

structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtkmjtcufx.html

[U93] JS：模板字符串
来源：http://dali.guowangkeji.top/Article/details/gttqhentbx.html

`共 ${n} 条`
来源：http://dali.dianchejie.cn/Article/details/gtfxibncgu.html

[U94] JS：箭头函数
来源：http://dali.jyoumei.cn/Article/details/gtviqwujae.html

const double = x => x * 2;
来源：http://dali.gotoacloud.top/Article/details/gtilpsqrjk.html

[U95] JS：Promise 包装
来源：http://dali.hammf.cn/Article/details/gtsbqzsqyn.html

new Promise((resolve, reject) => {})
来源：http://dali.nwbrower.top/Article/details/gtolqllilz.html

[U96] JS：async/await 与异常
来源：http://dali.c1oappe.top/Article/details/gtvpjzzabm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtdcqtvhtv.html

[U97] JS：并发请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnboxmmp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtpetdkday.html

[U98] JS：fetch 带 JSON
来源：http://dali.ydzc1.top/Article/details/gtgolttoqe.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.pycfn.com/Article/details/gtwvmjmxot.html

[U99] JS：事件监听
来源：http://dali.gogol.net.cn/Article/details/gtdrehouao.html

el.addEventListener("click", e => {})
来源：http://dali.mhx1999.top/Article/details/gtnjmoouiu.html

[U100] JS：DOM 查询
来源：http://dali.pengpengdd.cyou/Article/details/gtpisnuzrl.html

document.querySelector(".item")
来源：http://dali.hywenlv.cn/Article/details/gtqizajsnh.html

[U101] JS：classList 操作
来源：http://dali.yvedp.cn/Article/details/gtizuzadbb.html

el.classList.toggle("active")
来源：http://dali.zhengqikj.top/Article/details/gtpdzsmhxu.html

[U102] JS：本地存储
来源：http://dali.andypj.xyz/Article/details/gtakxqmuxe.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.smart0.xyz/Article/details/gteulydnpv.html

[U103] JS：定时器
来源：http://dali.gotoacloud.top/Article/details/gtdvjuudku.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.daria6918.cn/Article/details/gtcoqofsoz.html

[U104] JS：防抖
来源：http://dali.yueranfly.top/Article/details/gtnilmttod.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gtqlxrzzxu.html

[U105] JS：节流
来源：http://dali.gotoacloud.top/Article/details/gtvuuiybwx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgaecoau.html

[U106] JS：日期格式化
来源：http://dali.sweek.top/Article/details/gtxezfhznq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.aizwys.cn/Article/details/gtkynjvqbf.html

[U107] JS：数字千分位
来源：http://dali.jyoumei.cn/Article/details/gttiwpecsn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenlongwang.top/Article/details/gtfazbazfq.html

[U108] JS：随机整数
来源：http://dali.quarkkingdee.top/Article/details/gtcpcotxxm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinqigufen.top/Article/details/gtejvfznqy.html

[U109] JS：数组分组
来源：http://dali.sufxvd.cn/Article/details/gtxdeyhdbc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmeswrhzw.html

[U110] JS：数组分块
来源：http://dali.zhengqikj.top/Article/details/gtitorkwga.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hywenlv.cn/Article/details/gtdfwcfizv.html

[U111] JS：对象转 Map
来源：http://dali.cdnleiting.top/Article/details/gtnfdbresr.html

new Map(Object.entries(obj))
来源：http://dali.hywenlv.cn/Article/details/gtjpxxoxaj.html

[U112] JS：字符串补位
来源：http://dali.ppjwa.cn/Article/details/gtdauiladj.html

"7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gtweuthwrv.html

[U113] JS：正则替换全部
来源：http://dali.zhiwuduotai.top/Article/details/gtuzekrjhs.html

s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtljraywgr.html

[U114] JS：JSON 深比较
来源：http://dali.zhoulong.xyz/Article/details/gtcdgkemsh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gtocjcteqy.html

[U115] JS：生成 UUID
来源：http://dali.vqdsnc.cn/Article/details/gtkwjudkrf.html

crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gtbatzbjed.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.snrcjt.cn/Article/details/gtinwlbowv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzyxbjnad.html

[U117] JS：单元测试
来源：http://dali.dashuyun.cn/Article/details/gttedvuybq.html

npm i -D vitest;  npx vitest
来源：http://dali.xziqi.cn/Article/details/gtokvhukvl.html

[U118] JS：开发服务器
来源：http://dali.nwbrower.top/Article/details/gtuidsyrkd.html

npm i -D vite;  npx vite
来源：http://dali.jinghuilouyu.cn/Article/details/gtzanrvmmj.html

[U119] JS：生产构建
来源：http://dali.fengsongda.top/Article/details/gtraxqhpjg.html

npx vite build
来源：http://dali.jiagoushi.top/Article/details/gtbejwtqht.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhiwuduotai.top/Article/details/gtfpnuajor.html

import.meta.env.VITE_API_URL
来源：http://dali.yj20258.top/Article/details/gtkionhbjl.html


<!-- 参考信息 -->