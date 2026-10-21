代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.hongshengwenyu.top/Article/details/gtystqpwgx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhengqikj.top/Article/details/gthqndxfbf.html

[T34] Lua：遍历表
来源：http://dali.nanxinkj.top/Article/details/gttlzierfa.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guannengcc.top/Article/details/gtmybpmkmc.html

[T35] Lua：字典表
来源：http://dali.pycfn.com/Article/details/gtrrrauxpi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtnclnechl.html

[T36] Lua：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlniiekv.html

function add(a, b) return a + b end
来源：http://dali.cqqwz.cn/Article/details/gtqsyuczfd.html

[T37] Lua：字符串拼接
来源：http://dali.hnqzz.top/Article/details/gtfioiilsr.html

"a" .. "b"
来源：http://dali.feifeiyinyue.top/Article/details/gtxwfukjir.html

[T38] Lua：条件
来源：http://dali.jianghu66.top/Article/details/gtyyotdoxd.html

if x > 0 then print("正") end
来源：http://dali.jianghu66.top/Article/details/gtgdzpvsda.html

[T39] Lua：模式匹配
来源：http://dali.xuanzx.com/Article/details/gtvccqwfbl.html

string.find(s, "%d+")
来源：http://dali.vqdsnc.cn/Article/details/gtsffmbnhd.html

[T40] Lua：元表
来源：http://dali.0kj1m.cn/Article/details/gtdzoixlze.html

setmetatable({}, { __index = base })
来源：http://dali.yj20258888.top/Article/details/gthkqrjhvb.html

[T41] Perl：Hello World
来源：http://dali.tanke756.top/Article/details/gtkksykfbr.html

print "Hello\n";
来源：http://dali.tianlin.xyz/Article/details/gtdghrcejx.html

[T42] Perl：变量类型
来源：http://dali.daria6918.cn/Article/details/gtiqojomis.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hysaishi.cn/Article/details/gtknfopjrz.html

[T43] Perl：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtdnabigbd.html

"值: $a"
来源：http://dali.wangshuangyany.cn/Article/details/gtpuabtoql.html

[T44] Perl：条件
来源：http://dali.hongshengwenyu.top/Article/details/gtdzvvgijs.html

if ($a > 0) { print "正"; }
来源：http://dali.wangdashe.top/Article/details/gtckqtafik.html

[T45] Perl：数组遍历
来源：http://dali.zhoulong.xyz/Article/details/gtdndnbyof.html

for my $x (@arr) { print $x; }
来源：http://dali.shuidangran.top/Article/details/gtbfnoixhf.html

[T46] Perl：哈希操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvukcdox.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.andypj.xyz/Article/details/gtknwitxmv.html

[T47] Perl：正则捕获
来源：http://dali.yj20258.top/Article/details/gtkhvzubof.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteoonlmmr.html

[T48] Perl：正则替换
来源：http://dali.c1oappe.top/Article/details/gtpaaoqpxr.html

$s =~ s/old/new/g;
来源：http://dali.birdmap.top/Article/details/gtjitkgdkw.html

[T49] Perl：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmolpwmo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtylmrijqw.html

[T50] Perl：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtkmpeldjj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gogol.net.cn/Article/details/gtvsjdmviu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlnytcjiz.html

[T51] Scala：Hello World
来源：http://dali.iojbl.cn/Article/details/gtbncbrjds.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gtxsyiajlz.html

[T52] Scala：变量
来源：http://dali.cheryme.top/Article/details/gtovnlxedv.html

val a = 1;  var b = 2
来源：http://dali.shuidangran.top/Article/details/gtbmjprknm.html

[T53] Scala：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnggyirb.html

s"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gtejhjshgd.html

[T54] Scala：集合映射
来源：http://dali.redwolf501.top/Article/details/gtkwrdupmj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gzhubu.top/Article/details/gtxijhwczh.html

[T55] Scala：集合过滤
来源：http://dali.tian-w.cn/Article/details/gttvlygsfd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.bjfxy.top/Article/details/gtvovnrrno.html

[T56] Scala：样例类
来源：http://dali.316326.xyz/Article/details/gtnpurcdtt.html

case class User(name: String, age: Int)
来源：http://dali.xinyue.icu/Article/details/gtplpmdnnb.html

[T57] Scala：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gtqreamleh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jiagoushi.top/Article/details/gtydbbgqen.html

[T58] Scala：函数定义
来源：http://dali.gzhubu.top/Article/details/gtvorveyos.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shuidangran.top/Article/details/gtneibrnua.html

[T59] Scala：循环
来源：http://dali.zhengqikj.top/Article/details/gtmvqdnfcw.html

for (i <- 1 to 10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gtemxbdivr.html

[T60] Scala：折叠
来源：http://dali.andypj.xyz/Article/details/gtnfznyzgx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gotoacloud.top/Article/details/gtglvslkfx.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtfcrdqznf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ehwqpu.com/Article/details/gtwihweztm.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtdctpbcxn.html

[U01] Py：创建虚拟环境
来源：http://dali.tanke756.top/Article/details/gtuuqasmzy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aizwys.cn/Article/details/gtqitovcwt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nanxinkj.top/Article/details/gtbpyxasfl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.kuanghao11.cn/Article/details/gttlwsfalo.html

[U03] Py：加载 .env 配置
来源：http://dali.guannengcc.top/Article/details/gtefrgskmx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenjidiqi.icu/Article/details/gthindxfjn.html

[U04] Py：变量调试打印
来源：http://dali.hongshengwenyu.top/Article/details/gtpdspjcku.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhongyouzk.top/Article/details/gtgqpvgrts.html

[U05] Py：列表去重且保序
来源：http://dali.birdmap.top/Article/details/gtlfcxzjyt.html

list(dict.fromkeys(arr))
来源：http://dali.nanxinkj.top/Article/details/gtawomjmhb.html

[U06] Py：合并两个字典
来源：http://dali.jqgufenzy.top/Article/details/gtneeixpxi.html

{**a, **b}
来源：http://dali.gogol.net.cn/Article/details/gtpbyphqta.html

[U07] Py：反转字典键值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvrwyxxr.html

{v: k for k, v in d.items()}
来源：http://dali.tanke756.top/Article/details/gtwihjcerd.html

[U08] Py：展平二维列表
来源：http://dali.cqqwz.cn/Article/details/gtvovtrpjj.html

[y for x in nested for y in x]
来源：http://dali.aizwys.cn/Article/details/gtqeeumtnz.html

[U09] Py：字典取最大值的键
来源：http://dali.pengpengdd.cyou/Article/details/gtucisafut.html

max(d, key=d.get)
来源：http://dali.wangdashe.top/Article/details/gtlhlotxve.html

[U10] Py：按值排序字典
来源：http://dali.zhengqikj.top/Article/details/gtiiwmfaii.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xylfe.cn/Article/details/gtwhavroll.html

[U11] Py：生成器表达式
来源：http://dali.jiagoushi.top/Article/details/gtqksthrdl.html

(x * 2 for x in arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtbmitazjt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sweek.top/Article/details/gtxxxikvqx.html

Counter(arr).most_common(3)
来源：http://dali.chenzaomai.com/Article/details/gtxrqwsuqe.html

[U13] Py：固定长度队列
来源：http://dali.0kj1m.cn/Article/details/gtmshpegeg.html

deque(maxlen=10)
来源：http://dali.daxiang520.top/Article/details/gtznuvdlld.html

[U14] Py：分组收集到列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmmapran.html

defaultdict(list)
来源：http://dali.feifeiyinyue.top/Article/details/gterixzxgm.html

[U15] Py：高精度计时
来源：http://dali.snrcjt.cn/Article/details/gtmnqicmss.html

t = time.perf_counter()
来源：http://dali.iojbl.cn/Article/details/gtctqgagwy.html

[U16] Py：命令行参数解析
来源：http://dali.ydzc1.top/Article/details/gttjisiepn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuxming.cn/Article/details/gtqksuonox.html

[U17] Py：初始化日志
来源：http://dali.daria6918.cn/Article/details/gtkiymmojj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sweek.top/Article/details/gtvwcbqtcs.html

[U18] Py：预编译正则
来源：http://dali.chenzaomai.com/Article/details/gtomhqkqhp.html

pat = re.compile(r"\d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtlmuoeefw.html

[U19] Py：正则替换带回调
来源：http://dali.aizwys.cn/Article/details/gtlxrnfzbh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yvedp.cn/Article/details/gtnhxicbwr.html

[U20] Py：缓存函数结果
来源：http://dali.ivvv.top/Article/details/gtodsdbkgn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gogol.net.cn/Article/details/gtqkqvrrxc.html

[U21] Py：自定义上下文管理器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturbgszvz.html

@contextlib.contextmanager
来源：http://dali.zhongyouzk.top/Article/details/gtlxhbliqa.html

[U22] Py：矩阵转置
来源：http://dali.andypj.xyz/Article/details/gtgzzdxmvi.html

list(zip(*m))
来源：http://dali.hywenlv.cn/Article/details/gtylmnemmh.html

[U23] Py：分块读取大文件
来源：http://dali.yueranfly.top/Article/details/gtgrlndcwe.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.0kj1m.cn/Article/details/gtkjycxnhp.html

[U24] Py：路径操作
来源：http://dali.wangshuangyany.cn/Article/details/gtbeeulflu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gtwiibhibs.html

[U25] Py：CSV 按字典读
来源：http://dali.yueranfly.top/Article/details/gthdarwpei.html

csv.DictReader(f)
来源：http://dali.nwbrower.top/Article/details/gtxnkcfynh.html

[U26] Py：并发下载
来源：http://dali.andypj.xyz/Article/details/gtfaqzbgya.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shuidangran.top/Article/details/gttlobamzd.html

[U27] Py：异步 HTTP
来源：http://dali.jlsjyb.cn/Article/details/gtijnebayl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yj20258888.top/Article/details/gtxsoccukw.html

[U28] Py：类型别名
来源：http://dali.cdnleiting.top/Article/details/gtkhlawhan.html

UserId = int
来源：http://dali.yj20258.top/Article/details/gtdtbcgndb.html

[U29] Py：属性校验
来源：http://dali.chenjidiqi.icu/Article/details/gtnbllgjwl.html

@property 与 @x.setter 配合
来源：http://dali.jyoumei.cn/Article/details/gtahmgrgaz.html

[U30] Py：数据类
来源：http://dali.guowangkeji.top/Article/details/gtuzruklgv.html

@dataclass(slots=True)
来源：http://dali.ehwqpu.com/Article/details/gtetcsyzug.html

[U31] Py：单测
来源：http://dali.ybcxt.top/Article/details/gtuacwxuic.html

python -m pytest -q
来源：http://dali.chenzaomai.com/Article/details/gtvakklhfw.html

[U32] Py：代码格式化
来源：http://dali.andypj.xyz/Article/details/gtqwkobgpc.html

ruff format . && ruff check --fix .
来源：http://dali.ehwqpu.com/Article/details/gtgaagydio.html

[U33] Py：打包发布
来源：http://dali.hnxiangtu.top/Article/details/gtebreyunk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ydzc1.top/Article/details/gtvpmthcxr.html

[U34] Py：判断编码
来源：http://dali.yj202588.top/Article/details/gtroqotyuo.html

chardet.detect(raw)
来源：http://dali.xylfe.cn/Article/details/gtjcitclux.html

[U35] Py：发送邮件
来源：http://dali.gaohongyu789.top/Article/details/gtplvpheme.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.snrcjt.cn/Article/details/gtwwniabbo.html

[U36] Py：定时任务
来源：http://dali.ivvv.top/Article/details/gtlujcqahx.html

schedule.every(10).minutes.do(job)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwitjwap.html

[U37] Py：读写 Excel
来源：http://dali.jqgufenzy.top/Article/details/gtlegjhcrh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hongshengwenyu.top/Article/details/gtxilgeodt.html

[U38] Py：获取脚本所在目录
来源：http://dali.316326.xyz/Article/details/gtisftkhjg.html

Path(__file__).resolve().parent
来源：http://dali.hfpthk.cn/Article/details/gtcouplino.html

[U39] Py：判断是否在交互环境
来源：http://dali.nanxinkj.top/Article/details/gtzpjtkrnq.html

sys.stdout.isatty()
来源：http://dali.wangshuangyany.cn/Article/details/gterdypdue.html

[U40] Py：打印到标准错误
来源：http://dali.meibo888.top/Article/details/gtyvdhtdra.html

print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gtikctatmp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sysykeji.top/Article/details/gtupzgcygc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yanxiufei.cn/Article/details/gtsuqnibtu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.havefunace.top/Article/details/gtxsjjostp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.meibo888.top/Article/details/gtraxnkkai.html

[U43] PHP：声明命名空间
来源：http://dali.zdqjudy.top/Article/details/gtbbgovqim.html

namespace App\Http;
来源：http://dali.hnxiangtu.top/Article/details/gtairlgtmk.html

[U44] PHP：开启严格类型
来源：http://dali.nwbrower.top/Article/details/gtpadbltkh.html

declare(strict_types=1);
来源：http://dali.fzhhl.top/Article/details/gtktmhmnmz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gogol.net.cn/Article/details/gtkllkkoqe.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtxlfgcdut.html

[U46] PHP：可空类型
来源：http://dali.gogol.net.cn/Article/details/gtfpfrmtys.html

?string $name = null
来源：http://dali.sysykeji.top/Article/details/gtpuajpclr.html

[U47] PHP：联合类型
来源：http://dali.yangfankeji.com/Article/details/gtsqarfuyw.html

int|string $id
来源：http://dali.jqgfzy.top/Article/details/gtmnqkkgfk.html

[U48] PHP：纯枚举
来源：http://dali.yj202588.top/Article/details/gtsrefssfb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinqigfzy.top/Article/details/gtqvsrzwyz.html

[U49] PHP：只读属性
来源：http://dali.jinqigfzy.top/Article/details/gtkwemhpjl.html

public readonly string $name
来源：http://dali.yongpay.top/Article/details/gttchufzxm.html

[U50] PHP：构造器属性提升
来源：http://dali.316326.xyz/Article/details/gtblkprcpl.html

public function __construct(private int $id) {}
来源：http://dali.smart0.xyz/Article/details/gtdrwhtowe.html

[U51] PHP：数组解构
来源：http://dali.zhongyouzk.top/Article/details/gtnkqkxxzz.html

[$a, $b] = $arr;
来源：http://dali.yonumen.top/Article/details/gtyzglxnoj.html

[U52] PHP：箭头函数
来源：http://dali.aibaodan.cn/Article/details/gthkphaglm.html

$double = fn($x) => $x * 2;
来源：http://dali.pycfn.com/Article/details/gtkveyiahe.html

[U53] PHP：空合并运算符
来源：http://dali.dashuyun.cn/Article/details/gtoqdwwufp.html

$v = $a ?? $b ?? "default";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobgiqxpk.html

[U54] PHP：空安全调用
来源：http://dali.meibo888.top/Article/details/gtnxcqgjsj.html

$obj?->method()
来源：http://dali.sxryk.cn/Article/details/gtopfmyurq.html

[U55] PHP：match 表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtaicncibs.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.bjfxy.top/Article/details/gthzecrsen.html

[U56] PHP：命名参数
来源：http://dali.chenlongwang.top/Article/details/gtcjtavwms.html

f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gttadidood.html

[U57] PHP：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtzlahaaok.html

"值: {$a}"
来源：http://dali.316326.xyz/Article/details/gtekykzvhu.html

[U58] PHP：数组三件套
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqukrazhl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hysaishi.cn/Article/details/gtxwiqnkev.html

[U59] PHP：自定义排序
来源：http://dali.smart0.xyz/Article/details/gtblvmenvw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gtaqjczgti.html

[U60] PHP：JSON 编解码
来源：http://dali.gaohongyu789.top/Article/details/gtcmnbvggb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hnqzz.top/Article/details/gtikeafvjy.html

[U61] PHP：正则
来源：http://dali.mhx1999.top/Article/details/gtpxsmvwvh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gtldsoqyyn.html

[U62] PHP：日期对象
来源：http://dali.gzhubu.top/Article/details/gtndzstxnc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.chenlongwang.top/Article/details/gttvwoyqto.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gtjpxilmli.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.tianlin.xyz/Article/details/gtpgczfppv.html

[U64] PHP：目录遍历
来源：http://dali.fzhhl.top/Article/details/gtwbysmhfs.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gzhubu.top/Article/details/gtwrqmctfy.html

[U65] PHP：会话
来源：http://dali.xuetiantiany.cn/Article/details/gtqnsmlibv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtgxmspzeu.html

[U66] PHP：设置 Cookie
来源：http://dali.dianchejie.cn/Article/details/gtqxfqhnkp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.svipenyu.cn/Article/details/gtnehtunfc.html

[U67] PHP：处理文件上传
来源：http://dali.gotoacloud.top/Article/details/gtxxuivmxn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xuetiantiany.cn/Article/details/gtamacvoop.html

[U68] PHP：PDO 连接
来源：http://dali.xinyue.icu/Article/details/gtxmfwcfoj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.nanxuanxn.top/Article/details/gtjcuxzlou.html

[U69] PHP：PDO 预处理
来源：http://dali.zdqjudy.top/Article/details/gtyfjtcqqv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnykurpxo.html

[U70] PHP：PDO 事务
来源：http://dali.chenlongwang.top/Article/details/gtmemfekzq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.havefunace.top/Article/details/gtimcubswm.html

[U71] PHP：抛出异常
来源：http://dali.sweek.top/Article/details/gtfkvoyghx.html

throw new RuntimeException("失败", 500);
来源：http://dali.jianghu66.top/Article/details/gtqbtrmrbh.html

[U72] PHP：写错误日志
来源：http://dali.vqdsnc.cn/Article/details/gtdddprxgw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinqigufen.top/Article/details/gtkcfksspd.html

[U73] PHP：读取 ini 配置
来源：http://dali.jinqigufen.top/Article/details/gtjlqtedsv.html

parse_ini_file("config.ini", true)
来源：http://dali.zhongyouzk.top/Article/details/gtdmuixauf.html

[U74] PHP：读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gtxtsvqkug.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj20258888.top/Article/details/gtybqaglfc.html

[U75] PHP：依赖注入
来源：http://dali.ivvv.top/Article/details/gthwbnclup.html

composer require psr/container
来源：http://dali.xinyue.icu/Article/details/gtdcyiuxiw.html

[U76] PHP：简单路由
来源：http://dali.hnxiangtu.top/Article/details/gtrugghlfx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.birdmap.top/Article/details/gtzsouojzu.html

[U77] PHP：模板渲染
来源：http://dali.xuetiantiany.cn/Article/details/gtctwqwdvk.html

composer require twig/twig
来源：http://dali.pengpengdd.cyou/Article/details/gtcjgufuer.html

[U78] PHP：单元测试
来源：http://dali.jinqigfzy.top/Article/details/gtaojcvcca.html

composer require --dev phpunit/phpunit
来源：http://dali.guowangkeji.top/Article/details/gtlnfshtev.html

[U79] PHP：静态分析
来源：http://dali.hnqzz.top/Article/details/gtbamjmpcr.html

composer require --dev phpstan/phpstan
来源：http://dali.zhengqikj.top/Article/details/gtoatfyshn.html

[U80] PHP：代码规范修复
来源：http://dali.cucudq.cn/Article/details/gtevavdxpl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zdqjudy.top/Article/details/gtaojzunwf.html

[U81] JS：初始化项目
来源：http://dali.jianghu66.top/Article/details/gtddkqbyhe.html

npm init -y;  npm i express
来源：http://dali.jyoumei.cn/Article/details/gtetdosyrb.html

[U82] JS：package.json 脚本
来源：http://dali.smart0.xyz/Article/details/gtcxbpchiz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.svipenyu.cn/Article/details/gtyithyoob.html

[U83] JS：ES Module 导入导出
来源：http://dali.wangdashe.top/Article/details/gtcqoeljlq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gzhubu.top/Article/details/gtcwqjouhd.html

[U84] JS：CommonJS 写法
来源：http://dali.birdmap.top/Article/details/gtjozvlcos.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.gaohongyu789.top/Article/details/gtofhldncz.html

[U85] JS：可选链
来源：http://dali.meibo888.top/Article/details/gtwbitttpi.html

a?.b?.c
来源：http://dali.iojbl.cn/Article/details/gtcdksvmzn.html

[U86] JS：空值合并
来源：http://dali.havefunace.top/Article/details/gtbbikezzn.html

a ?? b
来源：http://dali.ehwqpu.com/Article/details/gtxerieker.html

[U87] JS：解构默认值
来源：http://dali.zycfv.cn/Article/details/gtpvvmerja.html

const { a = 1, b = 2 } = obj;
来源：http://dali.fengsongda.top/Article/details/gtbxyaqyqy.html

[U88] JS：对象展开合并
来源：http://dali.tian-w.cn/Article/details/gtwxzqbqzd.html

{ ...a, ...b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvalawnry.html

[U89] JS：数组去重
来源：http://dali.yueranfly.top/Article/details/gtjkufaahs.html

[...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gtrahqsaux.html

[U90] JS：数字数组排序
来源：http://dali.aizwys.cn/Article/details/gtopjuqdai.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtequumcar.html

[U91] JS：对象键值遍历
来源：http://dali.sweek.top/Article/details/gtwiekwyqr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gogol.net.cn/Article/details/gtdyimrkzd.html

[U92] JS：深拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdalirla.html

structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtlvjqsdzi.html

[U93] JS：模板字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflaxtdfj.html

`共 ${n} 条`
来源：http://dali.guowangkeji.top/Article/details/gtctjqyghg.html

[U94] JS：箭头函数
来源：http://dali.gotoacloud.top/Article/details/gtlfpofgop.html

const double = x => x * 2;
来源：http://dali.xinyue.icu/Article/details/gtzlitpugp.html

[U95] JS：Promise 包装
来源：http://dali.vqdsnc.cn/Article/details/gtxmednjmn.html

new Promise((resolve, reject) => {})
来源：http://dali.fzhhl.top/Article/details/gtgtykctut.html

[U96] JS：async/await 与异常
来源：http://dali.cucudq.cn/Article/details/gtvfiswzgy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtpuhjpuaz.html

[U97] JS：并发请求
来源：http://dali.hywenlv.cn/Article/details/gtlwuktusq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtbbuvxzmp.html

[U98] JS：fetch 带 JSON
来源：http://dali.ydzc1.top/Article/details/gtgewcqdwj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.daria6918.cn/Article/details/gtpmvhfqfn.html

[U99] JS：事件监听
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlvsxvor.html

el.addEventListener("click", e => {})
来源：http://dali.yangfankeji.com/Article/details/gtypjubdwd.html

[U100] JS：DOM 查询
来源：http://dali.zycfv.cn/Article/details/gtjposxnim.html

document.querySelector(".item")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcboqetr.html

[U101] JS：classList 操作
来源：http://dali.jqgfzy.top/Article/details/gthzepvagj.html

el.classList.toggle("active")
来源：http://dali.ydzc1.top/Article/details/gtyeitepwc.html

[U102] JS：本地存储
来源：http://dali.sweek.top/Article/details/gtdlvqgpks.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglmievtd.html

[U103] JS：定时器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqrbvhykv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhoulong.xyz/Article/details/gtjlaxdbmu.html

[U104] JS：防抖
来源：http://dali.xylfe.cn/Article/details/gtzdpogqao.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtoosfvarf.html

[U105] JS：节流
来源：http://dali.sysykeji.top/Article/details/gteasaoovt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tianlin.xyz/Article/details/gtjsrxwrfh.html

[U106] JS：日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtfkvrtiky.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ehwqpu.com/Article/details/gtugdotunz.html

[U107] JS：数字千分位
来源：http://dali.yuxming.cn/Article/details/gtoazbrbgt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gtueoxvsxy.html

[U108] JS：随机整数
来源：http://dali.cucudq.cn/Article/details/gtancyycpi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shzxlz.cn/Article/details/gtwdvupzoc.html

[U109] JS：数组分组
来源：http://dali.havefunace.top/Article/details/gtouzpcepy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gteqgpafry.html

[U110] JS：数组分块
来源：http://dali.gzhubu.top/Article/details/gtnelmpvqb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zdqjudy.top/Article/details/gtkumrawzx.html

[U111] JS：对象转 Map
来源：http://dali.redwolf501.top/Article/details/gtzkyjjsie.html

new Map(Object.entries(obj))
来源：http://dali.jqgfzy.top/Article/details/gtobrpnzqp.html

[U112] JS：字符串补位
来源：http://dali.hnxiangtu.top/Article/details/gtkmyzjsbb.html

"7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtfzaujriw.html

[U113] JS：正则替换全部
来源：http://dali.yuanzhike.top/Article/details/gtwasgmaap.html

s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtyqrqazic.html

[U114] JS：JSON 深比较
来源：http://dali.hongshengwenyu.top/Article/details/gtzvraxgbz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sxryk.cn/Article/details/gtlcgwuoqj.html

[U115] JS：生成 UUID
来源：http://dali.pengpengdd.cyou/Article/details/gtrbiadyuf.html

crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnjkwsgj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xinyue.icu/Article/details/gtylxgpqyk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.birdmap.top/Article/details/gtchskbpev.html

[U117] JS：单元测试
来源：http://dali.yangfankeji.com/Article/details/gtxxallfcf.html

npm i -D vitest;  npx vitest
来源：http://dali.andypj.xyz/Article/details/gtsrtmkfoe.html

[U118] JS：开发服务器
来源：http://dali.wangshuangyany.cn/Article/details/gtjxvavboi.html

npm i -D vite;  npx vite
来源：http://dali.daxiang520.top/Article/details/gtyuvajlqd.html

[U119] JS：生产构建
来源：http://dali.feifeiyinyue.top/Article/details/gtdbqdzxio.html

npx vite build
来源：http://dali.yuxming.cn/Article/details/gtyjstbvhj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cashguo.top/Article/details/gtcrenxapu.html

import.meta.env.VITE_API_URL
来源：http://dali.wangdashe.top/Article/details/gtvsswplyw.html


<!-- 参考信息 -->