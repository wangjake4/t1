代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gtnnsoqbjb.html

for my $x (@arr) { print $x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtacqrfybm.html

[T46] Perl：哈希操作
来源：http://dali.jinqigufen.top/Article/details/gtexznados.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.redwolf501.top/Article/details/gtdhmpkice.html

[T47] Perl：正则捕获
来源：http://dali.shuidangran.top/Article/details/gtsdpcbyzs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj202588.top/Article/details/gtcbsvevbv.html

[T48] Perl：正则替换
来源：http://dali.ppjwa.cn/Article/details/gtpaunqzri.html

$s =~ s/old/new/g;
来源：http://dali.jqgufenzy.top/Article/details/gtrorwlrnt.html

[T49] Perl：函数
来源：http://dali.jinqigfzy.top/Article/details/gtbiaqlujn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtslugwvkx.html

[T50] Perl：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtlsyvatxn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jiagoushi.top/Article/details/gtnirmukwo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmrrqnwtg.html

[T51] Scala：Hello World
来源：http://dali.hnqzz.top/Article/details/gtnumnuhgk.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtxgjfxasm.html

[T52] Scala：变量
来源：http://dali.havefunace.top/Article/details/gtdjcogmgz.html

val a = 1;  var b = 2
来源：http://dali.snrcjt.cn/Article/details/gtfretkgus.html

[T53] Scala：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtvzsvgbnh.html

s"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gtnetyawns.html

[T54] Scala：集合映射
来源：http://dali.meibo888.top/Article/details/gtqtjwolht.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cdnleiting.top/Article/details/gtobpveyhi.html

[T55] Scala：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtseznmjvi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jqgufenzy.top/Article/details/gtxwfaelep.html

[T56] Scala：样例类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhbolthl.html

case class User(name: String, age: Int)
来源：http://dali.bjfxy.top/Article/details/gtemmgahvh.html

[T57] Scala：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gttgiixoee.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zdqjudy.top/Article/details/gtxfnvsxht.html

[T58] Scala：函数定义
来源：http://dali.sufxvd.cn/Article/details/gtrmazegri.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj20258.top/Article/details/gtbbdjvgha.html

[T59] Scala：循环
来源：http://dali.jyoumei.cn/Article/details/gtqwhlvpcv.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhoulong.xyz/Article/details/gtqogaaono.html

[T60] Scala：折叠
来源：http://dali.mhx1999.top/Article/details/gtnxqfcfdg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gaohongyu789.top/Article/details/gtwbwbkxiv.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtmmmanzex.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yanxiufei.cn/Article/details/gtuewtreso.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtftnhusbb.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigufen.top/Article/details/gtuhiayljj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangshuangyany.cn/Article/details/gtxvyygvbz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.guannengcc.top/Article/details/gtcniyldqo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.svipenyu.cn/Article/details/gtexjvlnbd.html

[U03] Py：加载 .env 配置
来源：http://dali.wangshuangyany.cn/Article/details/gtwatavqvy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.bjfxy.top/Article/details/gtcvvbwlqo.html

[U04] Py：变量调试打印
来源：http://dali.yj20258888.top/Article/details/gtshhlairq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj202588.top/Article/details/gtjftavdrr.html

[U05] Py：列表去重且保序
来源：http://dali.andypj.xyz/Article/details/gteqpmcseq.html

list(dict.fromkeys(arr))
来源：http://dali.tianlin.xyz/Article/details/gtlfyrqevy.html

[U06] Py：合并两个字典
来源：http://dali.hnxiangtu.top/Article/details/gtoegbrdls.html

{**a, **b}
来源：http://dali.shuidangran.top/Article/details/gtrtyprsyi.html

[U07] Py：反转字典键值
来源：http://dali.zhiwuduotai.top/Article/details/gtmmxmxgxm.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258.top/Article/details/gtgfevmxci.html

[U08] Py：展平二维列表
来源：http://dali.shzxlz.cn/Article/details/gttuwevkst.html

[y for x in nested for y in x]
来源：http://dali.xziqi.cn/Article/details/gtprsrzjir.html

[U09] Py：字典取最大值的键
来源：http://dali.vqdsnc.cn/Article/details/gtjdkdatmp.html

max(d, key=d.get)
来源：http://dali.zycfv.cn/Article/details/gttxdqjybi.html

[U10] Py：按值排序字典
来源：http://dali.guowangkeji.top/Article/details/gtrpafgmlr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xuetiantiany.cn/Article/details/gteexospew.html

[U11] Py：生成器表达式
来源：http://dali.shzxlz.cn/Article/details/gtupbsnveo.html

(x * 2 for x in arr)
来源：http://dali.haohaochexian.top/Article/details/gtgkoxphrh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhiwuduotai.top/Article/details/gttucvhlkj.html

Counter(arr).most_common(3)
来源：http://dali.havefunace.top/Article/details/gtkkhwzmkd.html

[U13] Py：固定长度队列
来源：http://dali.yongpay.top/Article/details/gtxdqrflac.html

deque(maxlen=10)
来源：http://dali.xuetiantiany.cn/Article/details/gtexezkqdq.html

[U14] Py：分组收集到列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupalscxk.html

defaultdict(list)
来源：http://dali.jinqigfzy.top/Article/details/gtzyjxaixk.html

[U15] Py：高精度计时
来源：http://dali.pengpengdd.cyou/Article/details/gtkadzvufh.html

t = time.perf_counter()
来源：http://dali.vqdsnc.cn/Article/details/gtnrqboxzs.html

[U16] Py：命令行参数解析
来源：http://dali.yj20258.top/Article/details/gtxhndimrc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.svipenyu.cn/Article/details/gtercknrdg.html

[U17] Py：初始化日志
来源：http://dali.chenjidiqi.icu/Article/details/gtsyugvbnp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zdqjudy.top/Article/details/gtpdakjasv.html

[U18] Py：预编译正则
来源：http://dali.jqgufenzy.top/Article/details/gtsaedumri.html

pat = re.compile(r"\d+")
来源：http://dali.tian-w.cn/Article/details/gtxatwydlo.html

[U19] Py：正则替换带回调
来源：http://dali.cashguo.top/Article/details/gtkiewyhoy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwgszaqs.html

[U20] Py：缓存函数结果
来源：http://dali.cqqwz.cn/Article/details/gtdecutmdu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.andypj.xyz/Article/details/gtnokqxsxa.html

[U21] Py：自定义上下文管理器
来源：http://dali.vqdsnc.cn/Article/details/gtlhoigmhe.html

@contextlib.contextmanager
来源：http://dali.shangyingyoupin.top/Article/details/gtpydofetb.html

[U22] Py：矩阵转置
来源：http://dali.chenlongwang.top/Article/details/gtszhbwpbj.html

list(zip(*m))
来源：http://dali.bjfxy.top/Article/details/gtosaomwfb.html

[U23] Py：分块读取大文件
来源：http://dali.yj202588.top/Article/details/gtwihxytpq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.fzhhl.top/Article/details/gtytsgrovk.html

[U24] Py：路径操作
来源：http://dali.jianghu66.top/Article/details/gttazodjjn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gthmjwpbzq.html

[U25] Py：CSV 按字典读
来源：http://dali.dashuyun.cn/Article/details/gtgaiiutaw.html

csv.DictReader(f)
来源：http://dali.zycfv.cn/Article/details/gtsfqnrjxt.html

[U26] Py：并发下载
来源：http://dali.pycfn.com/Article/details/gttcesfazo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tianlin.xyz/Article/details/gttvwkpwnx.html

[U27] Py：异步 HTTP
来源：http://dali.yuxming.cn/Article/details/gtigxrybyj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuxming.cn/Article/details/gttmnwlnfl.html

[U28] Py：类型别名
来源：http://dali.vqdsnc.cn/Article/details/gtrcyzipmv.html

UserId = int
来源：http://dali.mhx1999.top/Article/details/gtsbapzprt.html

[U29] Py：属性校验
来源：http://dali.feifeiyinyue.top/Article/details/gtrfaxwlqs.html

@property 与 @x.setter 配合
来源：http://dali.yj20258888.top/Article/details/gtybpqcgzp.html

[U30] Py：数据类
来源：http://dali.aizwys.cn/Article/details/gtstqzngmg.html

@dataclass(slots=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtkitrylxi.html

[U31] Py：单测
来源：http://dali.xuetiantiany.cn/Article/details/gtiprbkmut.html

python -m pytest -q
来源：http://dali.sysykeji.top/Article/details/gtkayvvbfs.html

[U32] Py：代码格式化
来源：http://dali.jinqigfzy.top/Article/details/gtwslqnhnz.html

ruff format . && ruff check --fix .
来源：http://dali.zhiwuduotai.top/Article/details/gtqgmaukoa.html

[U33] Py：打包发布
来源：http://dali.gaohongyu789.top/Article/details/gtexdouhey.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zycfv.cn/Article/details/gtzcblpkvy.html

[U34] Py：判断编码
来源：http://dali.dianchejie.cn/Article/details/gtcvejhgpb.html

chardet.detect(raw)
来源：http://dali.iojbl.cn/Article/details/gtlrneiydf.html

[U35] Py：发送邮件
来源：http://dali.guannengcc.top/Article/details/gtlgdettga.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hnqzz.top/Article/details/gtkasnicjd.html

[U36] Py：定时任务
来源：http://dali.yj20258888.top/Article/details/gtepwqjlkj.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigbaclhb.html

[U37] Py：读写 Excel
来源：http://dali.yuanzhike.top/Article/details/gtrjpwvyku.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.chenlongwang.top/Article/details/gtcvjwsbqr.html

[U38] Py：获取脚本所在目录
来源：http://dali.dashuyun.cn/Article/details/gtazetkrwl.html

Path(__file__).resolve().parent
来源：http://dali.pengpengdd.cyou/Article/details/gtvzhaeqpy.html

[U39] Py：判断是否在交互环境
来源：http://dali.jyoumei.cn/Article/details/gtxhovpbqg.html

sys.stdout.isatty()
来源：http://dali.hnqzz.top/Article/details/gtkxckvwpq.html

[U40] Py：打印到标准错误
来源：http://dali.shzxlz.cn/Article/details/gtspuddxdy.html

print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gtgxxdqoou.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.kuanghao11.cn/Article/details/gtvkhhrcwx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xinyue.icu/Article/details/gtqhdspazt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jqgufenzy.top/Article/details/gtkmtloddi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xinyue.icu/Article/details/gtdjqcyxgk.html

[U43] PHP：声明命名空间
来源：http://dali.aizwys.cn/Article/details/gttoriwsnp.html

namespace App\Http;
来源：http://dali.hfpthk.cn/Article/details/gthalkdorw.html

[U44] PHP：开启严格类型
来源：http://dali.haohaochexian.top/Article/details/gtbvqcimdr.html

declare(strict_types=1);
来源：http://dali.vqdsnc.cn/Article/details/gtbxogwpgm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jqgfzy.top/Article/details/gthoatphqq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gtuvdisxzy.html

[U46] PHP：可空类型
来源：http://dali.ppjwa.cn/Article/details/gtiyhcbonm.html

?string $name = null
来源：http://dali.yuanzhike.top/Article/details/gtqrtobeal.html

[U47] PHP：联合类型
来源：http://dali.sufxvd.cn/Article/details/gtbhjffoug.html

int|string $id
来源：http://dali.gotoacloud.top/Article/details/gtusotrtkq.html

[U48] PHP：纯枚举
来源：http://dali.zycfv.cn/Article/details/gtaztigmxw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.dianchejie.cn/Article/details/gtzkjhkpnz.html

[U49] PHP：只读属性
来源：http://dali.ydzc1.top/Article/details/gtvsqgbclc.html

public readonly string $name
来源：http://dali.ydzc1.top/Article/details/gtwijsjlxg.html

[U50] PHP：构造器属性提升
来源：http://dali.tianlin.xyz/Article/details/gtnhnmpgmc.html

public function __construct(private int $id) {}
来源：http://dali.daria6918.cn/Article/details/gtckeonguk.html

[U51] PHP：数组解构
来源：http://dali.gotoacloud.top/Article/details/gtukteopxy.html

[$a, $b] = $arr;
来源：http://dali.yj202588.top/Article/details/gtzuzkvmnm.html

[U52] PHP：箭头函数
来源：http://dali.hongshengwenyu.top/Article/details/gtwtarivbo.html

$double = fn($x) => $x * 2;
来源：http://dali.birdmap.top/Article/details/gtxmitfqya.html

[U53] PHP：空合并运算符
来源：http://dali.yvedp.cn/Article/details/gtmbpcrrbc.html

$v = $a ?? $b ?? "default";
来源：http://dali.andypj.xyz/Article/details/gtnmzbusuf.html

[U54] PHP：空安全调用
来源：http://dali.feifeiyinyue.top/Article/details/gtnhmecmum.html

$obj?->method()
来源：http://dali.316326.xyz/Article/details/gteetyowex.html

[U55] PHP：match 表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtsmrpbhfx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hysaishi.cn/Article/details/gtowwldrsa.html

[U56] PHP：命名参数
来源：http://dali.ppjwa.cn/Article/details/gtzlpzojxq.html

f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gtcmcgqoit.html

[U57] PHP：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtdbnwomwo.html

"值: {$a}"
来源：http://dali.yueranfly.top/Article/details/gtocgxdwud.html

[U58] PHP：数组三件套
来源：http://dali.yuxming.cn/Article/details/gtqmtncmgn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtvynbihui.html

[U59] PHP：自定义排序
来源：http://dali.smart0.xyz/Article/details/gthulihclx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gtpapdxlrs.html

[U60] PHP：JSON 编解码
来源：http://dali.pycfn.com/Article/details/gtfvxsfvru.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hysaishi.cn/Article/details/gtxfhnorvu.html

[U61] PHP：正则
来源：http://dali.0kj1m.cn/Article/details/gtmzpfqvxk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gtwukweaia.html

[U62] PHP：日期对象
来源：http://dali.jiagoushi.top/Article/details/gtwddknnrj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yanxiufei.cn/Article/details/gthvfefltq.html

[U63] PHP：文件读写
来源：http://dali.0kj1m.cn/Article/details/gtrzoimzhc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ybcxt.top/Article/details/gttztdtryh.html

[U64] PHP：目录遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpdkyqjt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiglyetmg.html

[U65] PHP：会话
来源：http://dali.cheryme.top/Article/details/gtllfzrbaj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gthfurkcfz.html

[U66] PHP：设置 Cookie
来源：http://dali.sysykeji.top/Article/details/gttehaqmjy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ehwqpu.com/Article/details/gtsjifljyk.html

[U67] PHP：处理文件上传
来源：http://dali.guannengcc.top/Article/details/gtrywnzukm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shuidangran.top/Article/details/gtsrlnhxxt.html

[U68] PHP：PDO 连接
来源：http://dali.feifeiyinyue.top/Article/details/gtxsqlhszr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yuxming.cn/Article/details/gtkneajqzz.html

[U69] PHP：PDO 预处理
来源：http://dali.dianchejie.cn/Article/details/gtobjpahrm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cashguo.top/Article/details/gtnxznfivm.html

[U70] PHP：PDO 事务
来源：http://dali.nanxuanxn.top/Article/details/gtzfrhclle.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jqgufenzy.top/Article/details/gtzdczrprg.html

[U71] PHP：抛出异常
来源：http://dali.svipenyu.cn/Article/details/gtmiykcpoh.html

throw new RuntimeException("失败", 500);
来源：http://dali.jqgfzy.top/Article/details/gtjuqrzjyo.html

[U72] PHP：写错误日志
来源：http://dali.guowangkeji.top/Article/details/gtudipskyt.html

error_log("失败: " . $e->getMessage());
来源：http://dali.redwolf501.top/Article/details/gtgknhwepw.html

[U73] PHP：读取 ini 配置
来源：http://dali.aibaodan.cn/Article/details/gtswvdbymi.html

parse_ini_file("config.ini", true)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkjunude.html

[U74] PHP：读取环境变量
来源：http://dali.tianlin.xyz/Article/details/gtorhpappb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hysaishi.cn/Article/details/gtmelgeifc.html

[U75] PHP：依赖注入
来源：http://dali.c1oappe.top/Article/details/gteqeryivi.html

composer require psr/container
来源：http://dali.zycfv.cn/Article/details/gtoeglmzhj.html

[U76] PHP：简单路由
来源：http://dali.chenjidiqi.icu/Article/details/gtuectxtiv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.iojbl.cn/Article/details/gtutcrpjrx.html

[U77] PHP：模板渲染
来源：http://dali.sweek.top/Article/details/gtyytuqfhj.html

composer require twig/twig
来源：http://dali.feifeiyinyue.top/Article/details/gtumhatolz.html

[U78] PHP：单元测试
来源：http://dali.zhixingplan.top/Article/details/gtrewwhsdo.html

composer require --dev phpunit/phpunit
来源：http://dali.smart0.xyz/Article/details/gtqnpjgfwg.html

[U79] PHP：静态分析
来源：http://dali.zhiwuduotai.top/Article/details/gtuhwymvzk.html

composer require --dev phpstan/phpstan
来源：http://dali.tianlin.xyz/Article/details/gtfxxreaow.html

[U80] PHP：代码规范修复
来源：http://dali.nanxinkj.top/Article/details/gtkwptuwze.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.wangdashe.top/Article/details/gtfqgywicp.html

[U81] JS：初始化项目
来源：http://dali.zhongyouzk.top/Article/details/gtbdxhwohk.html

npm init -y;  npm i express
来源：http://dali.shzxlz.cn/Article/details/gtqeusdyxn.html

[U82] JS：package.json 脚本
来源：http://dali.gogol.net.cn/Article/details/gtswpljhnv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cucudq.cn/Article/details/gturezcquu.html

[U83] JS：ES Module 导入导出
来源：http://dali.zdqjudy.top/Article/details/gtcbzhpmeo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hysaishi.cn/Article/details/gtlsjjckbq.html

[U84] JS：CommonJS 写法
来源：http://dali.nwbrower.top/Article/details/gtwszdfvnx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinghuilouyu.cn/Article/details/gtucdgnutk.html

[U85] JS：可选链
来源：http://dali.wangdashe.top/Article/details/gtjnrjhncp.html

a?.b?.c
来源：http://dali.chenzaomai.com/Article/details/gtyegqrvet.html

[U86] JS：空值合并
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkpbrrpk.html

a ?? b
来源：http://dali.dashuyun.cn/Article/details/gtiniiegsq.html

[U87] JS：解构默认值
来源：http://dali.fengsongda.top/Article/details/gtdubgdasv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.fzhhl.top/Article/details/gtpnzmgufv.html

[U88] JS：对象展开合并
来源：http://dali.hammf.cn/Article/details/gtvahnwtfb.html

{ ...a, ...b }
来源：http://dali.feifeiyinyue.top/Article/details/gtzsoetkho.html

[U89] JS：数组去重
来源：http://dali.yanxiufei.cn/Article/details/gtzzjjheux.html

[...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gtuplyeiho.html

[U90] JS：数字数组排序
来源：http://dali.kuanghao11.cn/Article/details/gtbcjpvplr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttipmxym.html

[U91] JS：对象键值遍历
来源：http://dali.dashuyun.cn/Article/details/gtslpezejh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hywenlv.cn/Article/details/gtxmkutgmq.html

[U92] JS：深拷贝
来源：http://dali.jqgufenzy.top/Article/details/gtvrenswow.html

structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gtpklyhbqg.html

[U93] JS：模板字符串
来源：http://dali.guannengcc.top/Article/details/gtbrsbkmce.html

`共 ${n} 条`
来源：http://dali.hammf.cn/Article/details/gtnwzjmbpw.html

[U94] JS：箭头函数
来源：http://dali.zhiwuduotai.top/Article/details/gtiyiherhv.html

const double = x => x * 2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqicpyprn.html

[U95] JS：Promise 包装
来源：http://dali.nanxuanxn.top/Article/details/gtpzrovaid.html

new Promise((resolve, reject) => {})
来源：http://dali.zhengqikj.top/Article/details/gtwvbcxiho.html

[U96] JS：async/await 与异常
来源：http://dali.hnxiangtu.top/Article/details/gtcvpeyhiz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoodbyekj.html

[U97] JS：并发请求
来源：http://dali.jqgufenzy.top/Article/details/gtsrhavniq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gthrmgekeu.html

[U98] JS：fetch 带 JSON
来源：http://dali.316326.xyz/Article/details/gtrlkymrbw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yuanzhike.top/Article/details/gtdgbpihce.html

[U99] JS：事件监听
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrylsmuw.html

el.addEventListener("click", e => {})
来源：http://dali.vqdsnc.cn/Article/details/gtaswrtgwv.html

[U100] JS：DOM 查询
来源：http://dali.iojbl.cn/Article/details/gtjslgxlob.html

document.querySelector(".item")
来源：http://dali.hnqzz.top/Article/details/gtzmykdvoq.html

[U101] JS：classList 操作
来源：http://dali.shangyingyoupin.top/Article/details/gtavpqfboy.html

el.classList.toggle("active")
来源：http://dali.yj202588.top/Article/details/gttezzizgw.html

[U102] JS：本地存储
来源：http://dali.yj20258888.top/Article/details/gtboinebkj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hfpthk.cn/Article/details/gtnnvawmrb.html

[U103] JS：定时器
来源：http://dali.bjfxy.top/Article/details/gtpcszpyhj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.aibaodan.cn/Article/details/gtohljhnrg.html

[U104] JS：防抖
来源：http://dali.hysaishi.cn/Article/details/gtqbvkelwf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gtkumweehq.html

[U105] JS：节流
来源：http://dali.ybcxt.top/Article/details/gtmidwqbnc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yvedp.cn/Article/details/gtetooetko.html

[U106] JS：日期格式化
来源：http://dali.jianghu66.top/Article/details/gtwreudhoo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jqgfzy.top/Article/details/gturbjoyuu.html

[U107] JS：数字千分位
来源：http://dali.dashuyun.cn/Article/details/gtvtmvwnmg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenlongwang.top/Article/details/gtigmhqxjf.html

[U108] JS：随机整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqegpjya.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.c1oappe.top/Article/details/gtifcdihwu.html

[U109] JS：数组分组
来源：http://dali.ehwqpu.com/Article/details/gtqohrwyio.html

Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gtsohgpovn.html

[U110] JS：数组分块
来源：http://dali.hfpthk.cn/Article/details/gtsnjccned.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xuetiantiany.cn/Article/details/gtvuowdcmc.html

[U111] JS：对象转 Map
来源：http://dali.daxiang520.top/Article/details/gtdhlwuyvs.html

new Map(Object.entries(obj))
来源：http://dali.birdmap.top/Article/details/gtdrnshfwd.html

[U112] JS：字符串补位
来源：http://dali.andypj.xyz/Article/details/gtggktfetg.html

"7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtbvgrpszx.html

[U113] JS：正则替换全部
来源：http://dali.jiagoushi.top/Article/details/gtbtdjyrxn.html

s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gteljwomwt.html

[U114] JS：JSON 深比较
来源：http://dali.xinyue.icu/Article/details/gtsntsutsm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrcvlbns.html

[U115] JS：生成 UUID
来源：http://dali.snrcjt.cn/Article/details/gtecrmyvlq.html

crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gttahydmjx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.pycfn.com/Article/details/gtpyffqdmm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqgshjqqm.html

[U117] JS：单元测试
来源：http://dali.dianchejie.cn/Article/details/gtexqyovor.html

npm i -D vitest;  npx vitest
来源：http://dali.fzhhl.top/Article/details/gthbyecoqo.html

[U118] JS：开发服务器
来源：http://dali.hywenlv.cn/Article/details/gtaisqbheq.html

npm i -D vite;  npx vite
来源：http://dali.jiagoushi.top/Article/details/gtotgyskjq.html

[U119] JS：生产构建
来源：http://dali.hywenlv.cn/Article/details/gtixpoduqi.html

npx vite build
来源：http://dali.hysaishi.cn/Article/details/gtmztvqawu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.vqdsnc.cn/Article/details/gtwhybfnac.html

import.meta.env.VITE_API_URL
来源：http://dali.yj20258888.top/Article/details/gtytxywvtm.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtadjjmgpo.html

统计汇总
来源：http://dali.hnqzz.top/Article/details/gttpkawowc.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtfrcwzhfs.html

按语言统计（条）：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxfqjign.html

Python ......... 252
来源：http://dali.jlsjyb.cn/Article/details/gtfkvatkif.html

PHP ............ 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcappsre.html

JavaScript ..... 252
来源：http://dali.daxiang520.top/Article/details/gtmguztjxd.html

TypeScript ..... 212
来源：http://dali.tianlin.xyz/Article/details/gtxdafatoz.html

Java ........... 212
来源：http://dali.vqdsnc.cn/Article/details/gtrpaixbqw.html

Go ............. 212
来源：http://dali.zycfv.cn/Article/details/gtopjgzxea.html

Ruby ........... 212
来源：http://dali.chenlongwang.top/Article/details/gtpudynhow.html

C# ............. 212
来源：http://dali.gzhubu.top/Article/details/gtdcfgrqrx.html

C .............. 30
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalotuwgv.html

C++ ............ 30
来源：http://dali.bjfxy.top/Article/details/gtuuzwkrpf.html

SQL ............ 90
来源：http://dali.hywenlv.cn/Article/details/gtcihiipmx.html

Bash ........... 80
来源：http://dali.jianghu66.top/Article/details/gtspczfaut.html

Kotlin ......... 15
来源：http://dali.shuidangran.top/Article/details/gtlyervkml.html

Swift .......... 15
来源：http://dali.vqdsnc.cn/Article/details/gtkugqnwmn.html

Lua ............ 10
来源：http://dali.birdmap.top/Article/details/gtsivjdqow.html

Perl ........... 10
来源：http://dali.cheryme.top/Article/details/gtxsbiugxz.html

Scala .......... 10
来源：http://dali.ehwqpu.com/Article/details/gtcmtulofp.html

------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtyohvvxva.html

合计 ........... 2106 条
来源：http://dali.yj20258.top/Article/details/gtswpbaaen.html

按章节统计：
来源：http://dali.yj20258888.top/Article/details/gtphkasbkd.html


<!-- 参考信息 -->