代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.dashuyun.cn/Article/details/gt2zpkchvxq.html

for my $x (@arr) { print $x; }
来源：http://dali.fzhhl.top/Article/details/gt2crafglml.html

[T46] Perl：哈希操作
来源：http://dali.daxiang520.top/Article/details/gt2jgkilibx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztbcpuis.html

[T47] Perl：正则捕获
来源：http://dali.jianghu66.top/Article/details/gt2zcjavvpi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdthbvnz.html

[T48] Perl：正则替换
来源：http://dali.gotoacloud.top/Article/details/gt2fsyreyga.html

$s =~ s/old/new/g;
来源：http://dali.aibaodan.cn/Article/details/gt2yxdarbcs.html

[T49] Perl：函数
来源：http://dali.tanke756.top/Article/details/gt2ilrkzecp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rywjjfub.html

[T50] Perl：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gt2pdtqmghn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.quarkkingdee.top/Article/details/gt2pbnzqkbd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hammf.cn/Article/details/gt2avfdshdc.html

[T51] Scala：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2ttiuunqr.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gt2wmgbrasp.html

[T52] Scala：变量
来源：http://dali.c1oappe.top/Article/details/gt2eftoykcc.html

val a = 1;  var b = 2
来源：http://dali.jinqigufen.top/Article/details/gt2zflnlmjm.html

[T53] Scala：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gt2keddikhe.html

s"值: $b"
来源：http://dali.cheryme.top/Article/details/gt2qqnznuqm.html

[T54] Scala：集合映射
来源：http://dali.sufxvd.cn/Article/details/gt2iglrzdtu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yueranfly.top/Article/details/gt2gtsiriyo.html

[T55] Scala：集合过滤
来源：http://dali.0kj1m.cn/Article/details/gt2rhhljstg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yonumen.top/Article/details/gt2ikymuiil.html

[T56] Scala：样例类
来源：http://dali.gogol.net.cn/Article/details/gt2jyktdqmd.html

case class User(name: String, age: Int)
来源：http://dali.dianchejie.cn/Article/details/gt2kvmmnrle.html

[T57] Scala：模式匹配
来源：http://dali.sysykeji.top/Article/details/gt2nfmkprht.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yanxiufei.cn/Article/details/gt2lebzpwpm.html

[T58] Scala：函数定义
来源：http://dali.cqqwz.cn/Article/details/gt2pcelkstr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cashguo.top/Article/details/gt2uwwoowww.html

[T59] Scala：循环
来源：http://dali.nwbrower.top/Article/details/gt2aiybielk.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2czndprsj.html

[T60] Scala：折叠
来源：http://dali.havefunace.top/Article/details/gt2pxljujpj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sufxvd.cn/Article/details/gt2moblybwl.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2mrffauxy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.dianchejie.cn/Article/details/gt2vuedspxf.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2ybtrjptf.html

[U01] Py：创建虚拟环境
来源：http://dali.havefunace.top/Article/details/gt2rtxkwrcv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fengsongda.top/Article/details/gt2ciruzlpd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zycfv.cn/Article/details/gt2ftormyyn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yvedp.cn/Article/details/gt2rpkprcmy.html

[U03] Py：加载 .env 配置
来源：http://dali.pengpengdd.cyou/Article/details/gt2rmvdorya.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.guowangkeji.top/Article/details/gt2liowhvhg.html

[U04] Py：变量调试打印
来源：http://dali.nwbrower.top/Article/details/gt2ebchsikk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shzxlz.cn/Article/details/gt2cxolgdbe.html

[U05] Py：列表去重且保序
来源：http://dali.shangyingyoupin.top/Article/details/gt2hsqwyxrb.html

list(dict.fromkeys(arr))
来源：http://dali.redwolf501.top/Article/details/gt2dlqqnakz.html

[U06] Py：合并两个字典
来源：http://dali.cdnleiting.top/Article/details/gt2xxmgowgt.html

{**a, **b}
来源：http://dali.gotoacloud.top/Article/details/gt2fenvdxoc.html

[U07] Py：反转字典键值
来源：http://dali.nwbrower.top/Article/details/gt2snrtjrlq.html

{v: k for k, v in d.items()}
来源：http://dali.tianlin.xyz/Article/details/gt2meupxuct.html

[U08] Py：展平二维列表
来源：http://dali.jiagoushi.top/Article/details/gt2bihbtrai.html

[y for x in nested for y in x]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezblhckn.html

[U09] Py：字典取最大值的键
来源：http://dali.jiagoushi.top/Article/details/gt2kwsahyzq.html

max(d, key=d.get)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ilyurknc.html

[U10] Py：按值排序字典
来源：http://dali.quarkkingdee.top/Article/details/gt2usjasems.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.0kj1m.cn/Article/details/gt2nvvgtcty.html

[U11] Py：生成器表达式
来源：http://dali.jlsjyb.cn/Article/details/gt2xysenugu.html

(x * 2 for x in arr)
来源：http://dali.pycfn.com/Article/details/gt2dzsavboo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shzxlz.cn/Article/details/gt2nqvmemvv.html

Counter(arr).most_common(3)
来源：http://dali.hnqzz.top/Article/details/gt2nldekxnh.html

[U13] Py：固定长度队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2bickhttd.html

deque(maxlen=10)
来源：http://dali.shzxlz.cn/Article/details/gt2kaixzrgp.html

[U14] Py：分组收集到列表
来源：http://dali.cheryme.top/Article/details/gt2nzopuuvz.html

defaultdict(list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zfjvbajp.html

[U15] Py：高精度计时
来源：http://dali.pycfn.com/Article/details/gt2ftvvzwzd.html

t = time.perf_counter()
来源：http://dali.birdmap.top/Article/details/gt2aanzytad.html

[U16] Py：命令行参数解析
来源：http://dali.ppjwa.cn/Article/details/gt2qqzbsreb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xziqi.cn/Article/details/gt2ubpklbmn.html

[U17] Py：初始化日志
来源：http://dali.sysykeji.top/Article/details/gt2wnuqzjel.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.chenjidiqi.icu/Article/details/gt2onwlvyhl.html

[U18] Py：预编译正则
来源：http://dali.ybcxt.top/Article/details/gt2rkxffmys.html

pat = re.compile(r"\d+")
来源：http://dali.yj202588.top/Article/details/gt2cwywpsse.html

[U19] Py：正则替换带回调
来源：http://dali.yangfankeji.com/Article/details/gt2zcrzkonv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ojnzudjv.html

[U20] Py：缓存函数结果
来源：http://dali.shzxlz.cn/Article/details/gt2ozlrvcaz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.snrcjt.cn/Article/details/gt2rtfquyzv.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj202588.top/Article/details/gt2twqjugqr.html

@contextlib.contextmanager
来源：http://dali.hnqzz.top/Article/details/gt2bzclzvxy.html

[U22] Py：矩阵转置
来源：http://dali.nwbrower.top/Article/details/gt2dutawjve.html

list(zip(*m))
来源：http://dali.316326.xyz/Article/details/gt2kvydzxtc.html

[U23] Py：分块读取大文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dahescim.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.c1oappe.top/Article/details/gt2abwtqynb.html

[U24] Py：路径操作
来源：http://dali.cucudq.cn/Article/details/gt2sinkhnqw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gt2ydazqodu.html

[U25] Py：CSV 按字典读
来源：http://dali.jiagoushi.top/Article/details/gt2trbefhnu.html

csv.DictReader(f)
来源：http://dali.svipenyu.cn/Article/details/gt2bwwoiumz.html

[U26] Py：并发下载
来源：http://dali.xuetiantiany.cn/Article/details/gt2ekdpckij.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jqgufenzy.top/Article/details/gt2kjqprnov.html

[U27] Py：异步 HTTP
来源：http://dali.yangfankeji.com/Article/details/gt2raabkjan.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.haohaochexian.top/Article/details/gt2jvjfwlsj.html

[U28] Py：类型别名
来源：http://dali.haohaochexian.top/Article/details/gt2xdehivti.html

UserId = int
来源：http://dali.kuanghao11.cn/Article/details/gt2lsrzuyfl.html

[U29] Py：属性校验
来源：http://dali.c1oappe.top/Article/details/gt2wqhsedfn.html

@property 与 @x.setter 配合
来源：http://dali.zhengqikj.top/Article/details/gt2lcgfliko.html

[U30] Py：数据类
来源：http://dali.zhoulong.xyz/Article/details/gt2dtkquyat.html

@dataclass(slots=True)
来源：http://dali.ehwqpu.com/Article/details/gt2gkzqgzmz.html

[U31] Py：单测
来源：http://dali.yangfankeji.com/Article/details/gt2dbfzssfp.html

python -m pytest -q
来源：http://dali.dashuyun.cn/Article/details/gt2reewfadv.html

[U32] Py：代码格式化
来源：http://dali.jinqigufen.top/Article/details/gt2pvlfppzp.html

ruff format . && ruff check --fix .
来源：http://dali.gaohongyu789.top/Article/details/gt2ykdzguak.html

[U33] Py：打包发布
来源：http://dali.yuanzhike.top/Article/details/gt2mxesbvhp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ppjwa.cn/Article/details/gt2azbvqbna.html

[U34] Py：判断编码
来源：http://dali.gaohongyu789.top/Article/details/gt2umfxhjen.html

chardet.detect(raw)
来源：http://dali.jqgufenzy.top/Article/details/gt2efbxojrq.html

[U35] Py：发送邮件
来源：http://dali.fengsongda.top/Article/details/gt2tvzrazog.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj202588.top/Article/details/gt2gdbcymnt.html

[U36] Py：定时任务
来源：http://dali.dashuyun.cn/Article/details/gt2lfsuntgj.html

schedule.every(10).minutes.do(job)
来源：http://dali.fzhhl.top/Article/details/gt2qrzbufke.html

[U37] Py：读写 Excel
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2knugesyr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tianlin.xyz/Article/details/gt2ikkmigvi.html

[U38] Py：获取脚本所在目录
来源：http://dali.nanxuanxn.top/Article/details/gt2toadstzr.html

Path(__file__).resolve().parent
来源：http://dali.0kj1m.cn/Article/details/gt2rsldmldb.html

[U39] Py：判断是否在交互环境
来源：http://dali.pengpengdd.cyou/Article/details/gt2gwpneevr.html

sys.stdout.isatty()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vtjjsbbn.html

[U40] Py：打印到标准错误
来源：http://dali.fengsongda.top/Article/details/gt2kcyqzkty.html

print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gt2qyxqijpz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhengqikj.top/Article/details/gt2oikktkys.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yangfankeji.com/Article/details/gt2msolqsxe.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.vqdsnc.cn/Article/details/gt2ruxgfrif.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kmjcihoj.html

[U43] PHP：声明命名空间
来源：http://dali.fengsongda.top/Article/details/gt2divhrujq.html

namespace App\Http;
来源：http://dali.snrcjt.cn/Article/details/gt2dkrwudde.html

[U44] PHP：开启严格类型
来源：http://dali.daria6918.cn/Article/details/gt2ttsltzjk.html

declare(strict_types=1);
来源：http://dali.yj20258.top/Article/details/gt2yklfqrtr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hfpthk.cn/Article/details/gt2czrsxvhj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gt2zjuffefy.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfiwnsx.html

?string $name = null
来源：http://dali.xinyue.icu/Article/details/gt2tzidpnxm.html

[U47] PHP：联合类型
来源：http://dali.jqgfzy.top/Article/details/gt2ltpauhtm.html

int|string $id
来源：http://dali.cashguo.top/Article/details/gt2ltozclei.html

[U48] PHP：纯枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tgdnocvl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yuxming.cn/Article/details/gt2xzigzeku.html

[U49] PHP：只读属性
来源：http://dali.yj20258.top/Article/details/gt2dplpdlid.html

public readonly string $name
来源：http://dali.zhiwuduotai.top/Article/details/gt2rtmfbtyj.html

[U50] PHP：构造器属性提升
来源：http://dali.c1oappe.top/Article/details/gt2chaktnal.html

public function __construct(private int $id) {}
来源：http://dali.yvedp.cn/Article/details/gt2moboqebe.html

[U51] PHP：数组解构
来源：http://dali.zhoulong.xyz/Article/details/gt2nokwwqkm.html

[$a, $b] = $arr;
来源：http://dali.jinqigfzy.top/Article/details/gt2mlzkzfdz.html

[U52] PHP：箭头函数
来源：http://dali.tanke756.top/Article/details/gt2qkosmfzj.html

$double = fn($x) => $x * 2;
来源：http://dali.cucudq.cn/Article/details/gt2eprppetj.html

[U53] PHP：空合并运算符
来源：http://dali.vqdsnc.cn/Article/details/gt2teatqlhk.html

$v = $a ?? $b ?? "default";
来源：http://dali.ehwqpu.com/Article/details/gt2ixetehvw.html

[U54] PHP：空安全调用
来源：http://dali.nwbrower.top/Article/details/gt2dkwzdsak.html

$obj?->method()
来源：http://dali.cdnleiting.top/Article/details/gt2xjaocydx.html

[U55] PHP：match 表达式
来源：http://dali.cdnleiting.top/Article/details/gt2eiljosgk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.316326.xyz/Article/details/gt2iwfokahq.html

[U56] PHP：命名参数
来源：http://dali.9152youxi.cn/Article/details/gt2sbfogfpy.html

f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gt2kyltstjx.html

[U57] PHP：字符串插值
来源：http://dali.jianghu66.top/Article/details/gt2afbyppgc.html

"值: {$a}"
来源：http://dali.yanxiufei.cn/Article/details/gt2umunrtdm.html

[U58] PHP：数组三件套
来源：http://dali.yuxming.cn/Article/details/gt2ggsjspme.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.svipenyu.cn/Article/details/gt2ctgqyxud.html

[U59] PHP：自定义排序
来源：http://dali.nanxinkj.top/Article/details/gt2teiilpnf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gt2jfwufwqz.html

[U60] PHP：JSON 编解码
来源：http://dali.tanke756.top/Article/details/gt2pwuwoftt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.kuanghao11.cn/Article/details/gt2gnqiutst.html

[U61] PHP：正则
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbqsxghm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.birdmap.top/Article/details/gt2yapejqkw.html

[U62] PHP：日期对象
来源：http://dali.cashguo.top/Article/details/gt2wajavsem.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xuanzx.com/Article/details/gt2phdybich.html

[U63] PHP：文件读写
来源：http://dali.yuanzhike.top/Article/details/gt2friklroq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jlsjyb.cn/Article/details/gt2mthgowuq.html

[U64] PHP：目录遍历
来源：http://dali.andypj.xyz/Article/details/gt2qvlxbsyo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.andypj.xyz/Article/details/gt2icorrozz.html

[U65] PHP：会话
来源：http://dali.yuanzhike.top/Article/details/gt2uiwaqejd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj202588.top/Article/details/gt2maqshclc.html

[U66] PHP：设置 Cookie
来源：http://dali.pycfn.com/Article/details/gt2jpgptdbu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yuanzhike.top/Article/details/gt2kwvpnqvp.html

[U67] PHP：处理文件上传
来源：http://dali.yj202588.top/Article/details/gt2tnoxlqzp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ivvv.top/Article/details/gt2jknffulj.html

[U68] PHP：PDO 连接
来源：http://dali.hongshengwenyu.top/Article/details/gt2eeiwacof.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yj202588.top/Article/details/gt2lttlspol.html

[U69] PHP：PDO 预处理
来源：http://dali.nwbrower.top/Article/details/gt2xotocedr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj202588.top/Article/details/gt2hgdzxanu.html

[U70] PHP：PDO 事务
来源：http://dali.hnqzz.top/Article/details/gt2sfpnwupf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.aibaodan.cn/Article/details/gt2wcmixtkd.html

[U71] PHP：抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2kyxxjdwh.html

throw new RuntimeException("失败", 500);
来源：http://dali.pycfn.com/Article/details/gt2geiqiadc.html

[U72] PHP：写错误日志
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bkyciucl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenjidiqi.icu/Article/details/gt2spybfeez.html

[U73] PHP：读取 ini 配置
来源：http://dali.fengsongda.top/Article/details/gt2llxxnabu.html

parse_ini_file("config.ini", true)
来源：http://dali.jyoumei.cn/Article/details/gt2hifwsevi.html

[U74] PHP：读取环境变量
来源：http://dali.jqgfzy.top/Article/details/gt2jofxpqsx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jyoumei.cn/Article/details/gt2gwttuqnz.html

[U75] PHP：依赖注入
来源：http://dali.zhongyouzk.top/Article/details/gt2vhfvjshm.html

composer require psr/container
来源：http://dali.9152youxi.cn/Article/details/gt2mwvzfawd.html

[U76] PHP：简单路由
来源：http://dali.shuidangran.top/Article/details/gt2ftvxlkhg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yj20258888.top/Article/details/gt2wssiizko.html

[U77] PHP：模板渲染
来源：http://dali.shangyingyoupin.top/Article/details/gt2cyfbwerb.html

composer require twig/twig
来源：http://dali.meibo888.top/Article/details/gt2wsivyzcx.html

[U78] PHP：单元测试
来源：http://dali.bjfxy.top/Article/details/gt2crhefbjl.html

composer require --dev phpunit/phpunit
来源：http://dali.tianlin.xyz/Article/details/gt2yxakfqiw.html

[U79] PHP：静态分析
来源：http://dali.cucudq.cn/Article/details/gt2nwaziofy.html

composer require --dev phpstan/phpstan
来源：http://dali.hysaishi.cn/Article/details/gt2aqmkecsk.html

[U80] PHP：代码规范修复
来源：http://dali.bjfxy.top/Article/details/gt2urrhlmyi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhoulong.xyz/Article/details/gt2kgldliyy.html

[U81] JS：初始化项目
来源：http://dali.dianchejie.cn/Article/details/gt2dbxjorkd.html

npm init -y;  npm i express
来源：http://dali.gogol.net.cn/Article/details/gt2tagfrmen.html

[U82] JS：package.json 脚本
来源：http://dali.gzhubu.top/Article/details/gt2egcjuhpv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhongyouzk.top/Article/details/gt2jqkeluyb.html

[U83] JS：ES Module 导入导出
来源：http://dali.0kj1m.cn/Article/details/gt2gglmlzmr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.daxiang520.top/Article/details/gt2czhscehx.html

[U84] JS：CommonJS 写法
来源：http://dali.shangyingyoupin.top/Article/details/gt2dctsqmoi.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wilxsdij.html

[U85] JS：可选链
来源：http://dali.tanke756.top/Article/details/gt2wusxezbq.html

a?.b?.c
来源：http://dali.tian-w.cn/Article/details/gt2ggkomlhq.html

[U86] JS：空值合并
来源：http://dali.bjfxy.top/Article/details/gt2cbxkrbjx.html

a ?? b
来源：http://dali.jqgufenzy.top/Article/details/gt2kbeilybv.html

[U87] JS：解构默认值
来源：http://dali.xziqi.cn/Article/details/gt2tsmpsgos.html

const { a = 1, b = 2 } = obj;
来源：http://dali.guowangkeji.top/Article/details/gt2tgyqrohh.html

[U88] JS：对象展开合并
来源：http://dali.nwbrower.top/Article/details/gt2jufrpjgm.html

{ ...a, ...b }
来源：http://dali.316326.xyz/Article/details/gt2teaqieij.html

[U89] JS：数组去重
来源：http://dali.nwbrower.top/Article/details/gt2bxylsvuf.html

[...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gt2yhlxjfup.html

[U90] JS：数字数组排序
来源：http://dali.smart0.xyz/Article/details/gt2eyesidca.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gt2fotrwwlv.html

[U91] JS：对象键值遍历
来源：http://dali.ehwqpu.com/Article/details/gt2wchnpsda.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.dianchejie.cn/Article/details/gt2eetyqjqf.html

[U92] JS：深拷贝
来源：http://dali.mhx1999.top/Article/details/gt2widaibha.html

structuredClone(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eooxtkal.html

[U93] JS：模板字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2heddonpj.html

`共 ${n} 条`
来源：http://dali.zdqjudy.top/Article/details/gt2yrqndyua.html

[U94] JS：箭头函数
来源：http://dali.sysykeji.top/Article/details/gt2ubbkbizo.html

const double = x => x * 2;
来源：http://dali.shuidangran.top/Article/details/gt2qawkxpni.html

[U95] JS：Promise 包装
来源：http://dali.jqgufenzy.top/Article/details/gt2xrugofqu.html

new Promise((resolve, reject) => {})
来源：http://dali.dianchejie.cn/Article/details/gt2zoreuzyy.html

[U96] JS：async/await 与异常
来源：http://dali.xuetiantiany.cn/Article/details/gt2gpjxsypi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gt2liwzlfni.html

[U97] JS：并发请求
来源：http://dali.guannengcc.top/Article/details/gt2ftmkyrvc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gt2koqjktfm.html

[U98] JS：fetch 带 JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2evushnsu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jiagoushi.top/Article/details/gt2qnjgntrj.html

[U99] JS：事件监听
来源：http://dali.jqgufenzy.top/Article/details/gt2miwqapgb.html

el.addEventListener("click", e => {})
来源：http://dali.xziqi.cn/Article/details/gt2hncgmcrr.html

[U100] JS：DOM 查询
来源：http://dali.dianchejie.cn/Article/details/gt2fulyozmp.html

document.querySelector(".item")
来源：http://dali.shuidangran.top/Article/details/gt2jmbbvgth.html

[U101] JS：classList 操作
来源：http://dali.yongpay.top/Article/details/gt2mvgitxmv.html

el.classList.toggle("active")
来源：http://dali.chenzaomai.com/Article/details/gt2xxsiidry.html

[U102] JS：本地存储
来源：http://dali.wangdashe.top/Article/details/gt2lxynxeou.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xkicatzc.html

[U103] JS：定时器
来源：http://dali.wangdashe.top/Article/details/gt2bepdaudo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ivvv.top/Article/details/gt2jppuobtg.html

[U104] JS：防抖
来源：http://dali.ehwqpu.com/Article/details/gt2pvltusxz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gt2dqxedgnp.html

[U105] JS：节流
来源：http://dali.dianchejie.cn/Article/details/gt2rsjvsmxa.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhiwuduotai.top/Article/details/gt2pvokpbil.html

[U106] JS：日期格式化
来源：http://dali.jinqigufen.top/Article/details/gt2lubbfmpw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hfpthk.cn/Article/details/gt2wjahmgps.html

[U107] JS：数字千分位
来源：http://dali.xziqi.cn/Article/details/gt2vvopawue.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jvxdfucx.html

[U108] JS：随机整数
来源：http://dali.xuetiantiany.cn/Article/details/gt2uepwmnps.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xylfe.cn/Article/details/gt2wawvdvus.html

[U109] JS：数组分组
来源：http://dali.gogol.net.cn/Article/details/gt2gosmtwns.html

Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gt2ubmwhnkm.html

[U110] JS：数组分块
来源：http://dali.pycfn.com/Article/details/gt2ngwrunka.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.0kj1m.cn/Article/details/gt2zerolffv.html

[U111] JS：对象转 Map
来源：http://dali.iojbl.cn/Article/details/gt2usgjelay.html

new Map(Object.entries(obj))
来源：http://dali.wangdashe.top/Article/details/gt2hplktaun.html

[U112] JS：字符串补位
来源：http://dali.zhiwuduotai.top/Article/details/gt2shrytfzi.html

"7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gt2hfulhxvh.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ixalthob.html

s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2hkpuqrmt.html

[U114] JS：JSON 深比较
来源：http://dali.bjfxy.top/Article/details/gt2zsudmavs.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gt2kslktklz.html

[U115] JS：生成 UUID
来源：http://dali.daria6918.cn/Article/details/gt2rtoglamy.html

crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gt2yuwlekdv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ppjwa.cn/Article/details/gt2sjbzwjcg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzxoghnr.html

[U117] JS：单元测试
来源：http://dali.shangyingyoupin.top/Article/details/gt2fdutlwde.html

npm i -D vitest;  npx vitest
来源：http://dali.pengpengdd.cyou/Article/details/gt2siebjjtp.html

[U118] JS：开发服务器
来源：http://dali.meibo888.top/Article/details/gt2szbsvaed.html

npm i -D vite;  npx vite
来源：http://dali.c1oappe.top/Article/details/gt2fmpaaxwq.html

[U119] JS：生产构建
来源：http://dali.ybcxt.top/Article/details/gt2vzrvzlwr.html

npx vite build
来源：http://dali.xylfe.cn/Article/details/gt2bnmqpupf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.vqdsnc.cn/Article/details/gt2xyfjizgn.html

import.meta.env.VITE_API_URL
来源：http://dali.sufxvd.cn/Article/details/gt2oktymrnx.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2xjisyroo.html

统计汇总
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2adpqktpo.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2joqwqxqz.html

按语言统计（条）：
来源：http://dali.smart0.xyz/Article/details/gt2yrevpcoe.html

Python ......... 252
来源：http://dali.hysaishi.cn/Article/details/gt2hlxxcskr.html

PHP ............ 252
来源：http://dali.iojbl.cn/Article/details/gt2bsqycngp.html

JavaScript ..... 252
来源：http://dali.dashuyun.cn/Article/details/gt2crxljpub.html

TypeScript ..... 212
来源：http://dali.cdnleiting.top/Article/details/gt2ipejevxg.html

Java ........... 212
来源：http://dali.gotoacloud.top/Article/details/gt2yqlzpdik.html

Go ............. 212
来源：http://dali.mhx1999.top/Article/details/gt2wjkuclmt.html

Ruby ........... 212
来源：http://dali.yuxming.cn/Article/details/gt2yfgkudco.html

C# ............. 212
来源：http://dali.wangdashe.top/Article/details/gt2yynbiwne.html

C .............. 30
来源：http://dali.cheryme.top/Article/details/gt2ifhdnliq.html

C++ ............ 30
来源：http://dali.sysykeji.top/Article/details/gt2cynpoxku.html

SQL ............ 90
来源：http://dali.hysaishi.cn/Article/details/gt2mqcyenfj.html

Bash ........... 80
来源：http://dali.yongpay.top/Article/details/gt2ojxenbky.html

Kotlin ......... 15
来源：http://dali.gogol.net.cn/Article/details/gt2etobspkj.html

Swift .......... 15
来源：http://dali.zhoulong.xyz/Article/details/gt2rogwleme.html

Lua ............ 10
来源：http://dali.hfpthk.cn/Article/details/gt2fxgufsjg.html

Perl ........... 10
来源：http://dali.yueranfly.top/Article/details/gt2mbhalnre.html

Scala .......... 10
来源：http://dali.9152youxi.cn/Article/details/gt2qlajwtmg.html

------------------------------------
来源：http://dali.tian-w.cn/Article/details/gt2vxilnvrd.html

合计 ........... 2106 条
来源：http://dali.shzxlz.cn/Article/details/gt2hqcrsgeh.html

按章节统计：
来源：http://dali.hammf.cn/Article/details/gt2qrgrwimt.html


<!-- 参考信息 -->