代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.snrcjt.cn/Article/details/gtwwfiarzc.html

for my $x (@arr) { print $x; }
来源：http://dali.cashguo.top/Article/details/gtnodxxsos.html

[T46] Perl：哈希操作
来源：http://dali.gotoacloud.top/Article/details/gtznkktsoc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhoulong.xyz/Article/details/gtkpxoklhz.html

[T47] Perl：正则捕获
来源：http://dali.pengpengdd.cyou/Article/details/gthvsoqbde.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.haohaochexian.top/Article/details/gtlzpyawgl.html

[T48] Perl：正则替换
来源：http://dali.ppjwa.cn/Article/details/gtqyxjnciq.html

$s =~ s/old/new/g;
来源：http://dali.sxryk.cn/Article/details/gtxssfpqzk.html

[T49] Perl：函数
来源：http://dali.dianchejie.cn/Article/details/gtwwuiipuy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtsnhpttra.html

[T50] Perl：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtbvjvnddg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenzaomai.com/Article/details/gtvrxrzluv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.havefunace.top/Article/details/gtiwilyeaz.html

[T51] Scala：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtfocfpcou.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtekuhrzpo.html

[T52] Scala：变量
来源：http://dali.wangshuangyany.cn/Article/details/gtbkkfoupi.html

val a = 1;  var b = 2
来源：http://dali.daria6918.cn/Article/details/gtjkaiyiqe.html

[T53] Scala：字符串插值
来源：http://dali.yj20258888.top/Article/details/gtqkqikyva.html

s"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsqqcpcg.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmvjdgdo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xinyue.icu/Article/details/gtrvajmqtp.html

[T55] Scala：集合过滤
来源：http://dali.svipenyu.cn/Article/details/gtlwczlseb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.havefunace.top/Article/details/gtculcdmee.html

[T56] Scala：样例类
来源：http://dali.zhaomingkeji.xyz/Article/details/gttstgiung.html

case class User(name: String, age: Int)
来源：http://dali.wangdashe.top/Article/details/gtgzkiiznx.html

[T57] Scala：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtenbtbprk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ivvv.top/Article/details/gtyrmvstzi.html

[T58] Scala：函数定义
来源：http://dali.cucudq.cn/Article/details/gtyuzwcysw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jiagoushi.top/Article/details/gtmnxljiut.html

[T59] Scala：循环
来源：http://dali.hnxiangtu.top/Article/details/gtguwwcnlq.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzwpzcyo.html

[T60] Scala：折叠
来源：http://dali.fengsongda.top/Article/details/gtngmdxkrc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj202588.top/Article/details/gtyijyyewk.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtcdsjdmhz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aibaodan.cn/Article/details/gtiudtbruz.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtoauloiek.html

[U01] Py：创建虚拟环境
来源：http://dali.sufxvd.cn/Article/details/gttbhatenn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tianlin.xyz/Article/details/gtenhxkilu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dashuyun.cn/Article/details/gtvtnylllr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yvedp.cn/Article/details/gtgenxycri.html

[U03] Py：加载 .env 配置
来源：http://dali.jinqigfzy.top/Article/details/gtquiphmnf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sysykeji.top/Article/details/gtghyabgad.html

[U04] Py：变量调试打印
来源：http://dali.kuanghao11.cn/Article/details/gtwjmkxubk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.quarkkingdee.top/Article/details/gtdodkxpjj.html

[U05] Py：列表去重且保序
来源：http://dali.cashguo.top/Article/details/gtbltbjflp.html

list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gtbsaiwnkt.html

[U06] Py：合并两个字典
来源：http://dali.316326.xyz/Article/details/gtdufpiirl.html

{**a, **b}
来源：http://dali.gzhubu.top/Article/details/gtptbaicej.html

[U07] Py：反转字典键值
来源：http://dali.ybcxt.top/Article/details/gticyqjmga.html

{v: k for k, v in d.items()}
来源：http://dali.pycfn.com/Article/details/gtbhgnxevi.html

[U08] Py：展平二维列表
来源：http://dali.birdmap.top/Article/details/gtbdnwqpzn.html

[y for x in nested for y in x]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdfkjbyr.html

[U09] Py：字典取最大值的键
来源：http://dali.svipenyu.cn/Article/details/gttkmmeqgl.html

max(d, key=d.get)
来源：http://dali.haohaochexian.top/Article/details/gtlvkwsdxd.html

[U10] Py：按值排序字典
来源：http://dali.guannengcc.top/Article/details/gtbrmbfdzv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjfqwucq.html

[U11] Py：生成器表达式
来源：http://dali.cucudq.cn/Article/details/gtbvlpazkh.html

(x * 2 for x in arr)
来源：http://dali.birdmap.top/Article/details/gtbqwtbkaq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gogol.net.cn/Article/details/gterwqqavq.html

Counter(arr).most_common(3)
来源：http://dali.hfpthk.cn/Article/details/gtyogdmgbr.html

[U13] Py：固定长度队列
来源：http://dali.shzxlz.cn/Article/details/gtxdddjzeq.html

deque(maxlen=10)
来源：http://dali.daxiang520.top/Article/details/gtbgvybrti.html

[U14] Py：分组收集到列表
来源：http://dali.xziqi.cn/Article/details/gtzvbqnbhx.html

defaultdict(list)
来源：http://dali.sxryk.cn/Article/details/gtemhoijas.html

[U15] Py：高精度计时
来源：http://dali.havefunace.top/Article/details/gtdmfzqvxg.html

t = time.perf_counter()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyuafirj.html

[U16] Py：命令行参数解析
来源：http://dali.dashuyun.cn/Article/details/gtrafguzbq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hnxiangtu.top/Article/details/gtjhfgbnml.html

[U17] Py：初始化日志
来源：http://dali.zhongyouzk.top/Article/details/gtsufnrtty.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.kuanghao11.cn/Article/details/gtofsdphpc.html

[U18] Py：预编译正则
来源：http://dali.sufxvd.cn/Article/details/gtyimczazv.html

pat = re.compile(r"\d+")
来源：http://dali.wangdashe.top/Article/details/gtngbuxryj.html

[U19] Py：正则替换带回调
来源：http://dali.zycfv.cn/Article/details/gtqfozptfz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenjidiqi.icu/Article/details/gtpmzwaboo.html

[U20] Py：缓存函数结果
来源：http://dali.andypj.xyz/Article/details/gtdtoudblh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxinkj.top/Article/details/gtzeoqufal.html

[U21] Py：自定义上下文管理器
来源：http://dali.yuanzhike.top/Article/details/gtayywdmdd.html

@contextlib.contextmanager
来源：http://dali.jqgfzy.top/Article/details/gtynxpqiog.html

[U22] Py：矩阵转置
来源：http://dali.ehwqpu.com/Article/details/gtaymdxgfg.html

list(zip(*m))
来源：http://dali.c1oappe.top/Article/details/gtbittajsj.html

[U23] Py：分块读取大文件
来源：http://dali.yangfankeji.com/Article/details/gtvaqyaoxe.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.0kj1m.cn/Article/details/gtxzbeuxun.html

[U24] Py：路径操作
来源：http://dali.jinqigfzy.top/Article/details/gtfhkitgmc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gtznuphmoy.html

[U25] Py：CSV 按字典读
来源：http://dali.gzhubu.top/Article/details/gtlqvprpcw.html

csv.DictReader(f)
来源：http://dali.hywenlv.cn/Article/details/gtogqihwwu.html

[U26] Py：并发下载
来源：http://dali.zhiwuduotai.top/Article/details/gtoiemvsol.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hammf.cn/Article/details/gtkyrioyqm.html

[U27] Py：异步 HTTP
来源：http://dali.guannengcc.top/Article/details/gtqnqbgsuk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hammf.cn/Article/details/gtkchueaml.html

[U28] Py：类型别名
来源：http://dali.tanke756.top/Article/details/gtodbnbwoj.html

UserId = int
来源：http://dali.xylfe.cn/Article/details/gtcrnysjxr.html

[U29] Py：属性校验
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxuiunagt.html

@property 与 @x.setter 配合
来源：http://dali.jlsjyb.cn/Article/details/gtjwrsuxej.html

[U30] Py：数据类
来源：http://dali.svipenyu.cn/Article/details/gthycomivp.html

@dataclass(slots=True)
来源：http://dali.0kj1m.cn/Article/details/gtuaofbksd.html

[U31] Py：单测
来源：http://dali.snrcjt.cn/Article/details/gtetehrjwf.html

python -m pytest -q
来源：http://dali.xinyue.icu/Article/details/gtehiqhome.html

[U32] Py：代码格式化
来源：http://dali.pycfn.com/Article/details/gtfznhtwhf.html

ruff format . && ruff check --fix .
来源：http://dali.yuxming.cn/Article/details/gtuofiirah.html

[U33] Py：打包发布
来源：http://dali.redwolf501.top/Article/details/gtyszzlejy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nwbrower.top/Article/details/gtzmzlmfoc.html

[U34] Py：判断编码
来源：http://dali.birdmap.top/Article/details/gtdggyjtnw.html

chardet.detect(raw)
来源：http://dali.fzhhl.top/Article/details/gtdmcfexsl.html

[U35] Py：发送邮件
来源：http://dali.andypj.xyz/Article/details/gtmmvvdsez.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cheryme.top/Article/details/gtzzbhlzxo.html

[U36] Py：定时任务
来源：http://dali.yonumen.top/Article/details/gtrluteqgg.html

schedule.every(10).minutes.do(job)
来源：http://dali.fzhhl.top/Article/details/gtbkuinpqg.html

[U37] Py：读写 Excel
来源：http://dali.cdnleiting.top/Article/details/gttrpxsrpd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.bjfxy.top/Article/details/gtfizxyzkf.html

[U38] Py：获取脚本所在目录
来源：http://dali.sysykeji.top/Article/details/gtezhpxsav.html

Path(__file__).resolve().parent
来源：http://dali.ppjwa.cn/Article/details/gtmcuhrtcj.html

[U39] Py：判断是否在交互环境
来源：http://dali.hfpthk.cn/Article/details/gtsymcltix.html

sys.stdout.isatty()
来源：http://dali.gaohongyu789.top/Article/details/gtjhtpamfu.html

[U40] Py：打印到标准错误
来源：http://dali.nanxuanxn.top/Article/details/gtslrehfth.html

print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gtcrnitfzi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xylfe.cn/Article/details/gtbfjsabwl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sxryk.cn/Article/details/gtdfrfxkid.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.haohaochexian.top/Article/details/gtyeedobra.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.aizwys.cn/Article/details/gtrrvxumcg.html

[U43] PHP：声明命名空间
来源：http://dali.ybcxt.top/Article/details/gttqplygch.html

namespace App\Http;
来源：http://dali.jinqigfzy.top/Article/details/gtqoihrocr.html

[U44] PHP：开启严格类型
来源：http://dali.jinqigfzy.top/Article/details/gtnpebnuvw.html

declare(strict_types=1);
来源：http://dali.shuidangran.top/Article/details/gtabwpmgqv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jyoumei.cn/Article/details/gtbinovegh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gtejgkbyts.html

[U46] PHP：可空类型
来源：http://dali.ppjwa.cn/Article/details/gtznijvuvn.html

?string $name = null
来源：http://dali.xinyue.icu/Article/details/gtpbwqlyvk.html

[U47] PHP：联合类型
来源：http://dali.aizwys.cn/Article/details/gtifqvlryg.html

int|string $id
来源：http://dali.hywenlv.cn/Article/details/gtolxwqxlk.html

[U48] PHP：纯枚举
来源：http://dali.zdqjudy.top/Article/details/gtjalybkvk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zycfv.cn/Article/details/gtozgguhua.html

[U49] PHP：只读属性
来源：http://dali.cucudq.cn/Article/details/gtluqyxxey.html

public readonly string $name
来源：http://dali.sxryk.cn/Article/details/gtmeqnyyjx.html

[U50] PHP：构造器属性提升
来源：http://dali.pycfn.com/Article/details/gtptpmpoaq.html

public function __construct(private int $id) {}
来源：http://dali.zhongyouzk.top/Article/details/gthjsaziqh.html

[U51] PHP：数组解构
来源：http://dali.shuidangran.top/Article/details/gtlmvpuknk.html

[$a, $b] = $arr;
来源：http://dali.sysykeji.top/Article/details/gtqnoiwfpx.html

[U52] PHP：箭头函数
来源：http://dali.zycfv.cn/Article/details/gtjyxvvjwd.html

$double = fn($x) => $x * 2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdttqsvb.html

[U53] PHP：空合并运算符
来源：http://dali.pycfn.com/Article/details/gtsxcqjrym.html

$v = $a ?? $b ?? "default";
来源：http://dali.fengsongda.top/Article/details/gtmsljhfgv.html

[U54] PHP：空安全调用
来源：http://dali.feifeiyinyue.top/Article/details/gtwcjfkjfd.html

$obj?->method()
来源：http://dali.chenlongwang.top/Article/details/gtqxlqlyhm.html

[U55] PHP：match 表达式
来源：http://dali.shzxlz.cn/Article/details/gtznrwgcla.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yvedp.cn/Article/details/gtgmuiwvoy.html

[U56] PHP：命名参数
来源：http://dali.birdmap.top/Article/details/gthbrmdjkb.html

f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gtqwrupsea.html

[U57] PHP：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gtiqreixfn.html

"值: {$a}"
来源：http://dali.shangyingyoupin.top/Article/details/gtzgzlbtyp.html

[U58] PHP：数组三件套
来源：http://dali.nwbrower.top/Article/details/gtklgfgmfe.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtjvjbapql.html

[U59] PHP：自定义排序
来源：http://dali.nanxinkj.top/Article/details/gtotggipxy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxinkj.top/Article/details/gtbgdyetlo.html

[U60] PHP：JSON 编解码
来源：http://dali.gogol.net.cn/Article/details/gtyvdezymj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hnxiangtu.top/Article/details/gtjliuvxuf.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gtahsclnam.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.svipenyu.cn/Article/details/gtngxstmum.html

[U62] PHP：日期对象
来源：http://dali.sweek.top/Article/details/gtcixwdken.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.pycfn.com/Article/details/gtdwdmznmk.html

[U63] PHP：文件读写
来源：http://dali.smart0.xyz/Article/details/gtytudrwsd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zycfv.cn/Article/details/gtxfkwoteq.html

[U64] PHP：目录遍历
来源：http://dali.shuidangran.top/Article/details/gtvznqocst.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.daxiang520.top/Article/details/gtlgizonhv.html

[U65] PHP：会话
来源：http://dali.wangshuangyany.cn/Article/details/gtwwfbnijv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.havefunace.top/Article/details/gtjpohtsst.html

[U66] PHP：设置 Cookie
来源：http://dali.yj20258888.top/Article/details/gtvsfjqyso.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.daxiang520.top/Article/details/gtnmicqnlf.html

[U67] PHP：处理文件上传
来源：http://dali.yonumen.top/Article/details/gtuzohwjbc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shuidangran.top/Article/details/gtowrbyrzp.html

[U68] PHP：PDO 连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwcnpswv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jqgufenzy.top/Article/details/gtznvrncly.html

[U69] PHP：PDO 预处理
来源：http://dali.gaohongyu789.top/Article/details/gtfdqqzlax.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhixingplan.top/Article/details/gtvxfgjcwh.html

[U70] PHP：PDO 事务
来源：http://dali.yongpay.top/Article/details/gtjwkwhxhu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tianlin.xyz/Article/details/gtahdenown.html

[U71] PHP：抛出异常
来源：http://dali.zycfv.cn/Article/details/gtdbhxqpax.html

throw new RuntimeException("失败", 500);
来源：http://dali.kuanghao11.cn/Article/details/gtquqehibl.html

[U72] PHP：写错误日志
来源：http://dali.yuxming.cn/Article/details/gtxewwydji.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhongyouzk.top/Article/details/gtbnlawmwl.html

[U73] PHP：读取 ini 配置
来源：http://dali.xylfe.cn/Article/details/gtpbiekece.html

parse_ini_file("config.ini", true)
来源：http://dali.hfpthk.cn/Article/details/gtuvxbzwts.html

[U74] PHP：读取环境变量
来源：http://dali.andypj.xyz/Article/details/gtjhyytlhl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jqgufenzy.top/Article/details/gtdkcpkqld.html

[U75] PHP：依赖注入
来源：http://dali.hnqzz.top/Article/details/gtcqnvfgls.html

composer require psr/container
来源：http://dali.daria6918.cn/Article/details/gtugjpayga.html

[U76] PHP：简单路由
来源：http://dali.bjfxy.top/Article/details/gtbszrnamh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.birdmap.top/Article/details/gtwxzxheuj.html

[U77] PHP：模板渲染
来源：http://dali.chenjidiqi.icu/Article/details/gtquvbdxpz.html

composer require twig/twig
来源：http://dali.hfpthk.cn/Article/details/gtqylhzycw.html

[U78] PHP：单元测试
来源：http://dali.dianchejie.cn/Article/details/gtxuvrmzoy.html

composer require --dev phpunit/phpunit
来源：http://dali.chenlongwang.top/Article/details/gtfspiieqo.html

[U79] PHP：静态分析
来源：http://dali.fengsongda.top/Article/details/gtrcdrfevx.html

composer require --dev phpstan/phpstan
来源：http://dali.jqgufenzy.top/Article/details/gtfwqvjxuz.html

[U80] PHP：代码规范修复
来源：http://dali.wangdashe.top/Article/details/gtokygilxk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nanxuanxn.top/Article/details/gtdwaqqnnp.html

[U81] JS：初始化项目
来源：http://dali.hnqzz.top/Article/details/gtdouuskgo.html

npm init -y;  npm i express
来源：http://dali.jiagoushi.top/Article/details/gtzdjnykrx.html

[U82] JS：package.json 脚本
来源：http://dali.yvedp.cn/Article/details/gtnwfzhbfg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sweek.top/Article/details/gtsuflvmhn.html

[U83] JS：ES Module 导入导出
来源：http://dali.gogol.net.cn/Article/details/gtejgegdsa.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenlongwang.top/Article/details/gtalyptssr.html

[U84] JS：CommonJS 写法
来源：http://dali.jinqigfzy.top/Article/details/gtwzpyfsuh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhixingplan.top/Article/details/gtlelfdead.html

[U85] JS：可选链
来源：http://dali.xziqi.cn/Article/details/gtpoajcdzo.html

a?.b?.c
来源：http://dali.nwbrower.top/Article/details/gtuqkjfbhn.html

[U86] JS：空值合并
来源：http://dali.hammf.cn/Article/details/gtghwegwbb.html

a ?? b
来源：http://dali.yuxming.cn/Article/details/gticlvskfj.html

[U87] JS：解构默认值
来源：http://dali.dianchejie.cn/Article/details/gtnaindrlz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.gotoacloud.top/Article/details/gtfhrepbwg.html

[U88] JS：对象展开合并
来源：http://dali.yj20258.top/Article/details/gthpsiztjf.html

{ ...a, ...b }
来源：http://dali.guowangkeji.top/Article/details/gtyrzlonyn.html

[U89] JS：数组去重
来源：http://dali.aizwys.cn/Article/details/gtnyrqgwpx.html

[...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gthdervjfv.html

[U90] JS：数字数组排序
来源：http://dali.0kj1m.cn/Article/details/gtpgdwdmrw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtxgkkvfnn.html

[U91] JS：对象键值遍历
来源：http://dali.ydzc1.top/Article/details/gtzynqankz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ydzc1.top/Article/details/gtjhwsrmun.html

[U92] JS：深拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslhdhwjo.html

structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gttmjioijb.html

[U93] JS：模板字符串
来源：http://dali.guowangkeji.top/Article/details/gtnstzfowa.html

`共 ${n} 条`
来源：http://dali.sweek.top/Article/details/gtbrqtfgcv.html

[U94] JS：箭头函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtlejljujn.html

const double = x => x * 2;
来源：http://dali.yueranfly.top/Article/details/gtnyhijtqo.html

[U95] JS：Promise 包装
来源：http://dali.shuidangran.top/Article/details/gtulmboylb.html

new Promise((resolve, reject) => {})
来源：http://dali.yvedp.cn/Article/details/gtxkkjhvef.html

[U96] JS：async/await 与异常
来源：http://dali.jqgufenzy.top/Article/details/gtcvmljgvu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtalyvjqpf.html

[U97] JS：并发请求
来源：http://dali.aizwys.cn/Article/details/gtsnvfhykp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtcxosydfi.html

[U98] JS：fetch 带 JSON
来源：http://dali.jinqigfzy.top/Article/details/gtlpdaxbgk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jianghu66.top/Article/details/gtdhsjlvwd.html

[U99] JS：事件监听
来源：http://dali.sweek.top/Article/details/gtzdurhezo.html

el.addEventListener("click", e => {})
来源：http://dali.gaohongyu789.top/Article/details/gtgoobxvqy.html

[U100] JS：DOM 查询
来源：http://dali.haohaochexian.top/Article/details/gtcuevnbyg.html

document.querySelector(".item")
来源：http://dali.zhengqikj.top/Article/details/gtjunahwsv.html

[U101] JS：classList 操作
来源：http://dali.xylfe.cn/Article/details/gtircsvffy.html

el.classList.toggle("active")
来源：http://dali.yongpay.top/Article/details/gtczgpyiqk.html

[U102] JS：本地存储
来源：http://dali.andypj.xyz/Article/details/gtwefsnzex.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.wangdashe.top/Article/details/gteymngxea.html

[U103] JS：定时器
来源：http://dali.andypj.xyz/Article/details/gtojyjpvxl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ydzc1.top/Article/details/gtgqrtugba.html

[U104] JS：防抖
来源：http://dali.shuidangran.top/Article/details/gtwuskgczh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gtqkckirhl.html

[U105] JS：节流
来源：http://dali.yuanzhike.top/Article/details/gtuzsesshh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gaohongyu789.top/Article/details/gttwdbwhik.html

[U106] JS：日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtifbaqbpl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sufxvd.cn/Article/details/gtoffcxolt.html

[U107] JS：数字千分位
来源：http://dali.svipenyu.cn/Article/details/gtcshuqles.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cashguo.top/Article/details/gtzfkkvcwb.html

[U108] JS：随机整数
来源：http://dali.andypj.xyz/Article/details/gtiaewmzue.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.9152youxi.cn/Article/details/gtmbcdwkdb.html

[U109] JS：数组分组
来源：http://dali.zhiwuduotai.top/Article/details/gtewbpvuek.html

Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gtrdxiqpjb.html

[U110] JS：数组分块
来源：http://dali.shzxlz.cn/Article/details/gtjceiqazb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nanxuanxn.top/Article/details/gtjiooixak.html

[U111] JS：对象转 Map
来源：http://dali.0kj1m.cn/Article/details/gtxkisxhod.html

new Map(Object.entries(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtxxotcgip.html

[U112] JS：字符串补位
来源：http://dali.xziqi.cn/Article/details/gtjzjsftgc.html

"7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtjvanbuqp.html

[U113] JS：正则替换全部
来源：http://dali.jqgfzy.top/Article/details/gtzsqpxyaj.html

s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtgrfbclyc.html

[U114] JS：JSON 深比较
来源：http://dali.yj202588.top/Article/details/gtncxkixnq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gteudgxwny.html

[U115] JS：生成 UUID
来源：http://dali.chenzaomai.com/Article/details/gtlxwwcazt.html

crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtolpjlyij.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.nwbrower.top/Article/details/gtubtvpufk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zdqjudy.top/Article/details/gtwpzlebwe.html

[U117] JS：单元测试
来源：http://dali.yuanzhike.top/Article/details/gtgqoayjcg.html

npm i -D vitest;  npx vitest
来源：http://dali.chenzaomai.com/Article/details/gtvdyzhuac.html

[U118] JS：开发服务器
来源：http://dali.hnxiangtu.top/Article/details/gtpxaaynmg.html

npm i -D vite;  npx vite
来源：http://dali.yj202588.top/Article/details/gthkjhfdyn.html

[U119] JS：生产构建
来源：http://dali.xylfe.cn/Article/details/gtxnbjgexz.html

npx vite build
来源：http://dali.hywenlv.cn/Article/details/gtblfhevww.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sufxvd.cn/Article/details/gtyzigzqzn.html

import.meta.env.VITE_API_URL
来源：http://dali.hnxiangtu.top/Article/details/gtdgvlapth.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthidkyfvd.html

统计汇总
来源：http://dali.gogol.net.cn/Article/details/gtfkftqstd.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtrvmgneum.html

按语言统计（条）：
来源：http://dali.snrcjt.cn/Article/details/gtxylqyfgn.html

Python ......... 252
来源：http://dali.xuanzx.com/Article/details/gtxsbnlczn.html

PHP ............ 252
来源：http://dali.shuidangran.top/Article/details/gthbmkuxvi.html

JavaScript ..... 252
来源：http://dali.smart0.xyz/Article/details/gtxagquehq.html

TypeScript ..... 212
来源：http://dali.iojbl.cn/Article/details/gtaditngce.html

Java ........... 212
来源：http://dali.tanke756.top/Article/details/gtwvagksmz.html

Go ............. 212
来源：http://dali.c1oappe.top/Article/details/gtqjlhentc.html

Ruby ........... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswgxzfbm.html

C# ............. 212
来源：http://dali.svipenyu.cn/Article/details/gtxjsyxxjo.html

C .............. 30
来源：http://dali.havefunace.top/Article/details/gtnnrfnxwk.html

C++ ............ 30
来源：http://dali.guowangkeji.top/Article/details/gtwqdtotlt.html

SQL ............ 90
来源：http://dali.jinqigfzy.top/Article/details/gtqvvmsckw.html

Bash ........... 80
来源：http://dali.hywenlv.cn/Article/details/gtnlpassjd.html

Kotlin ......... 15
来源：http://dali.vqdsnc.cn/Article/details/gttuqhejhm.html

Swift .......... 15
来源：http://dali.bjfxy.top/Article/details/gtqndjmpzz.html

Lua ............ 10
来源：http://dali.chenzaomai.com/Article/details/gtdfrynxld.html

Perl ........... 10
来源：http://dali.jiagoushi.top/Article/details/gturkcdsmm.html

Scala .......... 10
来源：http://dali.pycfn.com/Article/details/gttsyoozbp.html

------------------------------------
来源：http://dali.smart0.xyz/Article/details/gtueuzrrhu.html

合计 ........... 2106 条
来源：http://dali.wangshuangyany.cn/Article/details/gtregteumh.html

按章节统计：
来源：http://dali.hfpthk.cn/Article/details/gtkdrffnst.html


<!-- 参考信息 -->