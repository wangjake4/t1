代发 wailian999

[T49] Perl：函数
来源：http://dali.yj202588.top/Article/details/gthvwvvuyg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gtgfaxitrb.html

[T50] Perl：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtrtntpqln.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigfzy.top/Article/details/gtdazgxlqk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hfpthk.cn/Article/details/gtajdflqdx.html

[T51] Scala：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtzqreptfk.html

println("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtvapptgmu.html

[T52] Scala：变量
来源：http://dali.tanke756.top/Article/details/gtkfcthhoh.html

val a = 1;  var b = 2
来源：http://dali.pycfn.com/Article/details/gtkavtlclm.html

[T53] Scala：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtcsevvsak.html

s"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gtwfcjtkss.html

[T54] Scala：集合映射
来源：http://dali.gzhubu.top/Article/details/gthmquymef.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hysaishi.cn/Article/details/gtldtqcamv.html

[T55] Scala：集合过滤
来源：http://dali.cheryme.top/Article/details/gttnjebdmx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cashguo.top/Article/details/gtmndcrguc.html

[T56] Scala：样例类
来源：http://dali.haohaochexian.top/Article/details/gtymmmpiqe.html

case class User(name: String, age: Int)
来源：http://dali.hysaishi.cn/Article/details/gtljtkoiua.html

[T57] Scala：模式匹配
来源：http://dali.fzhhl.top/Article/details/gtuwrfauod.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.guannengcc.top/Article/details/gtewdupkcs.html

[T58] Scala：函数定义
来源：http://dali.zdqjudy.top/Article/details/gtblbagrbw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nanxinkj.top/Article/details/gtybxuxwtc.html

[T59] Scala：循环
来源：http://dali.cdnleiting.top/Article/details/gtfidycirh.html

for (i <- 1 to 10) println(i)
来源：http://dali.svipenyu.cn/Article/details/gtygdzjnkp.html

[T60] Scala：折叠
来源：http://dali.nanxinkj.top/Article/details/gthrxfckkr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aibaodan.cn/Article/details/gtcolvcvtp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gthclxzxvq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpazaoikz.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtusogymns.html

[U01] Py：创建虚拟环境
来源：http://dali.cqqwz.cn/Article/details/gtiukeiorj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.316326.xyz/Article/details/gtmpdqwfrp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cashguo.top/Article/details/gtovjssifh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenzaomai.com/Article/details/gtvyzleyjn.html

[U03] Py：加载 .env 配置
来源：http://dali.feifeiyinyue.top/Article/details/gtdvirlteh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hywenlv.cn/Article/details/gtqkyrttow.html

[U04] Py：变量调试打印
来源：http://dali.jyoumei.cn/Article/details/gtivlcwtgr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.bjfxy.top/Article/details/gtalhmsimp.html

[U05] Py：列表去重且保序
来源：http://dali.yongpay.top/Article/details/gtckarutme.html

list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gtnrzxyzhz.html

[U06] Py：合并两个字典
来源：http://dali.guannengcc.top/Article/details/gtldyahszj.html

{**a, **b}
来源：http://dali.chenlongwang.top/Article/details/gtpiqpaxuc.html

[U07] Py：反转字典键值
来源：http://dali.shuidangran.top/Article/details/gtnbozysdh.html

{v: k for k, v in d.items()}
来源：http://dali.sufxvd.cn/Article/details/gtffohrsct.html

[U08] Py：展平二维列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmrjzqhr.html

[y for x in nested for y in x]
来源：http://dali.sxryk.cn/Article/details/gtqikiiboz.html

[U09] Py：字典取最大值的键
来源：http://dali.hysaishi.cn/Article/details/gtqaepuhtp.html

max(d, key=d.get)
来源：http://dali.zhongyouzk.top/Article/details/gtffdezxma.html

[U10] Py：按值排序字典
来源：http://dali.zhiwuduotai.top/Article/details/gtykuyypef.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yanxiufei.cn/Article/details/gtgpbzkpew.html

[U11] Py：生成器表达式
来源：http://dali.hnxiangtu.top/Article/details/gtomonownq.html

(x * 2 for x in arr)
来源：http://dali.tianlin.xyz/Article/details/gtnwtzhhkm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gogol.net.cn/Article/details/gtrwbwkrgz.html

Counter(arr).most_common(3)
来源：http://dali.fengsongda.top/Article/details/gtkkbonbbk.html

[U13] Py：固定长度队列
来源：http://dali.zhixingplan.top/Article/details/gtudfswczf.html

deque(maxlen=10)
来源：http://dali.yongpay.top/Article/details/gthcphxusp.html

[U14] Py：分组收集到列表
来源：http://dali.hnqzz.top/Article/details/gtnhgdstaa.html

defaultdict(list)
来源：http://dali.yanxiufei.cn/Article/details/gtjipbijjr.html

[U15] Py：高精度计时
来源：http://dali.yueranfly.top/Article/details/gtpguenavf.html

t = time.perf_counter()
来源：http://dali.yvedp.cn/Article/details/gtjypmizew.html

[U16] Py：命令行参数解析
来源：http://dali.sxryk.cn/Article/details/gtvszygtwz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.bjfxy.top/Article/details/gteknrhjtw.html

[U17] Py：初始化日志
来源：http://dali.kuanghao11.cn/Article/details/gticzmalna.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhixingplan.top/Article/details/gtnseejchc.html

[U18] Py：预编译正则
来源：http://dali.redwolf501.top/Article/details/gtmnhbkisv.html

pat = re.compile(r"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtetlfzsiz.html

[U19] Py：正则替换带回调
来源：http://dali.havefunace.top/Article/details/gtpsbzulza.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.bjfxy.top/Article/details/gtcmmmgyru.html

[U20] Py：缓存函数结果
来源：http://dali.redwolf501.top/Article/details/gtapthqlti.html

@functools.lru_cache(maxsize=None)
来源：http://dali.vqdsnc.cn/Article/details/gtytykzvna.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhongyouzk.top/Article/details/gtovyaqagk.html

@contextlib.contextmanager
来源：http://dali.chenzaomai.com/Article/details/gtygbmpcqk.html

[U22] Py：矩阵转置
来源：http://dali.xziqi.cn/Article/details/gtqkdsgbjx.html

list(zip(*m))
来源：http://dali.c1oappe.top/Article/details/gtvgsvighc.html

[U23] Py：分块读取大文件
来源：http://dali.guannengcc.top/Article/details/gtyaqfqzxr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj20258888.top/Article/details/gtvsdoewis.html

[U24] Py：路径操作
来源：http://dali.ydzc1.top/Article/details/gtmxcyilbv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gtbrodwzyq.html

[U25] Py：CSV 按字典读
来源：http://dali.yj20258.top/Article/details/gtkpjiajic.html

csv.DictReader(f)
来源：http://dali.nanxinkj.top/Article/details/gtpmqwiewf.html

[U26] Py：并发下载
来源：http://dali.zhixingplan.top/Article/details/gtufretfhp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenjidiqi.icu/Article/details/gtfrnpgdqz.html

[U27] Py：异步 HTTP
来源：http://dali.jyoumei.cn/Article/details/gtdumqwpdh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yueranfly.top/Article/details/gtcgfuixoy.html

[U28] Py：类型别名
来源：http://dali.jinqigufen.top/Article/details/gtksxyldjz.html

UserId = int
来源：http://dali.gaohongyu789.top/Article/details/gtyrkojwlj.html

[U29] Py：属性校验
来源：http://dali.yj20258888.top/Article/details/gtsguxqcgm.html

@property 与 @x.setter 配合
来源：http://dali.hysaishi.cn/Article/details/gtwmfqmmtz.html

[U30] Py：数据类
来源：http://dali.redwolf501.top/Article/details/gtupsxccwd.html

@dataclass(slots=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtddztmnmb.html

[U31] Py：单测
来源：http://dali.zhiwuduotai.top/Article/details/gttovjqkpk.html

python -m pytest -q
来源：http://dali.yueranfly.top/Article/details/gtndsujrwu.html

[U32] Py：代码格式化
来源：http://dali.jlsjyb.cn/Article/details/gtxgwmyvrz.html

ruff format . && ruff check --fix .
来源：http://dali.nanxinkj.top/Article/details/gtmixvpawo.html

[U33] Py：打包发布
来源：http://dali.yonumen.top/Article/details/gtaqkfkwdu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.wangshuangyany.cn/Article/details/gtunffzwwq.html

[U34] Py：判断编码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwyihhepn.html

chardet.detect(raw)
来源：http://dali.ppjwa.cn/Article/details/gtyqogwvmj.html

[U35] Py：发送邮件
来源：http://dali.gaohongyu789.top/Article/details/gtpguirxjb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jiagoushi.top/Article/details/gtwtmrdnmg.html

[U36] Py：定时任务
来源：http://dali.jiagoushi.top/Article/details/gttiadzxnb.html

schedule.every(10).minutes.do(job)
来源：http://dali.aibaodan.cn/Article/details/gtldzugxgg.html

[U37] Py：读写 Excel
来源：http://dali.jiagoushi.top/Article/details/gtzcdjljnm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xinyue.icu/Article/details/gtfyngycgv.html

[U38] Py：获取脚本所在目录
来源：http://dali.sufxvd.cn/Article/details/gtkfhdizwp.html

Path(__file__).resolve().parent
来源：http://dali.cheryme.top/Article/details/gtdbtrxjhy.html

[U39] Py：判断是否在交互环境
来源：http://dali.yuanzhike.top/Article/details/gteiptarwm.html

sys.stdout.isatty()
来源：http://dali.nwbrower.top/Article/details/gtafahtnbf.html

[U40] Py：打印到标准错误
来源：http://dali.fengsongda.top/Article/details/gtowtjspxo.html

print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gtsbodessc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.svipenyu.cn/Article/details/gtwjouvgiy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.guannengcc.top/Article/details/gtagzivcql.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ppjwa.cn/Article/details/gtwxwqojis.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinqigufen.top/Article/details/gtcngjhzfl.html

[U43] PHP：声明命名空间
来源：http://dali.redwolf501.top/Article/details/gtworfvcxa.html

namespace App\Http;
来源：http://dali.cdnleiting.top/Article/details/gttscnmqxi.html

[U44] PHP：开启严格类型
来源：http://dali.daria6918.cn/Article/details/gtxbterssx.html

declare(strict_types=1);
来源：http://dali.zhoulong.xyz/Article/details/gtshfpmjmq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gogol.net.cn/Article/details/gtpeualsep.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtnpmozcha.html

[U46] PHP：可空类型
来源：http://dali.dashuyun.cn/Article/details/gtfqnaujjm.html

?string $name = null
来源：http://dali.mhx1999.top/Article/details/gtuwksthlr.html

[U47] PHP：联合类型
来源：http://dali.zhiwuduotai.top/Article/details/gthletshbr.html

int|string $id
来源：http://dali.tianlin.xyz/Article/details/gtfyoztydq.html

[U48] PHP：纯枚举
来源：http://dali.tanke756.top/Article/details/gtwjzgpqde.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.snrcjt.cn/Article/details/gtpglfnyiu.html

[U49] PHP：只读属性
来源：http://dali.ydzc1.top/Article/details/gtqzovvgml.html

public readonly string $name
来源：http://dali.ivvv.top/Article/details/gtmznnigjl.html

[U50] PHP：构造器属性提升
来源：http://dali.jqgufenzy.top/Article/details/gtvfefygez.html

public function __construct(private int $id) {}
来源：http://dali.jyoumei.cn/Article/details/gtejvpisjs.html

[U51] PHP：数组解构
来源：http://dali.xinyue.icu/Article/details/gtumyiivyy.html

[$a, $b] = $arr;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlcdglsn.html

[U52] PHP：箭头函数
来源：http://dali.feifeiyinyue.top/Article/details/gtvkliebbq.html

$double = fn($x) => $x * 2;
来源：http://dali.hammf.cn/Article/details/gtkfzytbsc.html

[U53] PHP：空合并运算符
来源：http://dali.jqgfzy.top/Article/details/gtbysmrqzb.html

$v = $a ?? $b ?? "default";
来源：http://dali.xziqi.cn/Article/details/gtssmjptbo.html

[U54] PHP：空安全调用
来源：http://dali.316326.xyz/Article/details/gtbbfrrmwt.html

$obj?->method()
来源：http://dali.9152youxi.cn/Article/details/gtsvhegpob.html

[U55] PHP：match 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtsbbgjcan.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.smart0.xyz/Article/details/gtjjcgjsgm.html

[U56] PHP：命名参数
来源：http://dali.cdnleiting.top/Article/details/gtbxlzequf.html

f(a: 1, b: 2)
来源：http://dali.xinyue.icu/Article/details/gtrbkdkfvo.html

[U57] PHP：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtvldzmuoh.html

"值: {$a}"
来源：http://dali.yj20258.top/Article/details/gtbriwnyix.html

[U58] PHP：数组三件套
来源：http://dali.wangdashe.top/Article/details/gteeybocre.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkaihteg.html

[U59] PHP：自定义排序
来源：http://dali.xziqi.cn/Article/details/gtyjathsor.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztvvwtdf.html

[U60] PHP：JSON 编解码
来源：http://dali.hammf.cn/Article/details/gtphslwhpk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinqigfzy.top/Article/details/gtbxbmqbgw.html

[U61] PHP：正则
来源：http://dali.yonumen.top/Article/details/gtvljwpsjp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtgwhincby.html

[U62] PHP：日期对象
来源：http://dali.gotoacloud.top/Article/details/gtlielyrhh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cdnleiting.top/Article/details/gtfzcuaoqc.html

[U63] PHP：文件读写
来源：http://dali.yonumen.top/Article/details/gtpnjdocmw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhengqikj.top/Article/details/gtluanfsbf.html

[U64] PHP：目录遍历
来源：http://dali.hywenlv.cn/Article/details/gtbygkiewp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gzhubu.top/Article/details/gtstctjnya.html

[U65] PHP：会话
来源：http://dali.yuxming.cn/Article/details/gtmyryhzyn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtaotzjsfw.html

[U66] PHP：设置 Cookie
来源：http://dali.jinghuilouyu.cn/Article/details/gtvuqxejil.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.birdmap.top/Article/details/gtujgrnuir.html

[U67] PHP：处理文件上传
来源：http://dali.jinqigfzy.top/Article/details/gtegoozkka.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.chenzaomai.com/Article/details/gtbmenizex.html

[U68] PHP：PDO 连接
来源：http://dali.svipenyu.cn/Article/details/gtmfdnoiwu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.wangdashe.top/Article/details/gtgwvccnbz.html

[U69] PHP：PDO 预处理
来源：http://dali.daxiang520.top/Article/details/gtatgzdyll.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gotoacloud.top/Article/details/gtgahvndzc.html

[U70] PHP：PDO 事务
来源：http://dali.hnqzz.top/Article/details/gtzjnhmkip.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tanke756.top/Article/details/gtqpsllahy.html

[U71] PHP：抛出异常
来源：http://dali.yongpay.top/Article/details/gtajzsqahb.html

throw new RuntimeException("失败", 500);
来源：http://dali.hfpthk.cn/Article/details/gtfpzlnzdc.html

[U72] PHP：写错误日志
来源：http://dali.jiagoushi.top/Article/details/gtbjnnkpwi.html

error_log("失败: " . $e->getMessage());
来源：http://dali.kuanghao11.cn/Article/details/gtavoyfvon.html

[U73] PHP：读取 ini 配置
来源：http://dali.c1oappe.top/Article/details/gtfcylxjkw.html

parse_ini_file("config.ini", true)
来源：http://dali.zycfv.cn/Article/details/gtzqbbrrny.html

[U74] PHP：读取环境变量
来源：http://dali.redwolf501.top/Article/details/gtfsfnxkoh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shzxlz.cn/Article/details/gtdwdylmzz.html

[U75] PHP：依赖注入
来源：http://dali.jqgfzy.top/Article/details/gtjhrwgioa.html

composer require psr/container
来源：http://dali.ehwqpu.com/Article/details/gtaixstqax.html

[U76] PHP：简单路由
来源：http://dali.jqgufenzy.top/Article/details/gtrhxjwzbf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shzxlz.cn/Article/details/gtnfukviqc.html

[U77] PHP：模板渲染
来源：http://dali.xuetiantiany.cn/Article/details/gtxcgkkfiw.html

composer require twig/twig
来源：http://dali.yj20258.top/Article/details/gtfreivyjw.html

[U78] PHP：单元测试
来源：http://dali.vqdsnc.cn/Article/details/gtsrkdqdiz.html

composer require --dev phpunit/phpunit
来源：http://dali.birdmap.top/Article/details/gtzbkwfylc.html

[U79] PHP：静态分析
来源：http://dali.shzxlz.cn/Article/details/gtmyugpbsv.html

composer require --dev phpstan/phpstan
来源：http://dali.9152youxi.cn/Article/details/gtqwwtkqbz.html

[U80] PHP：代码规范修复
来源：http://dali.jqgufenzy.top/Article/details/gtjactklue.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yj20258888.top/Article/details/gtqkwgyfhc.html

[U81] JS：初始化项目
来源：http://dali.tianlin.xyz/Article/details/gttpjabgfj.html

npm init -y;  npm i express
来源：http://dali.pengpengdd.cyou/Article/details/gtatmnhtws.html

[U82] JS：package.json 脚本
来源：http://dali.yj20258888.top/Article/details/gtspteovhy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.0kj1m.cn/Article/details/gtjfagdajm.html

[U83] JS：ES Module 导入导出
来源：http://dali.shuidangran.top/Article/details/gtshcffixv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cucudq.cn/Article/details/gtctmorenk.html

[U84] JS：CommonJS 写法
来源：http://dali.jinqigfzy.top/Article/details/gtuzlndcit.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cqqwz.cn/Article/details/gtqgbufhgn.html

[U85] JS：可选链
来源：http://dali.mhx1999.top/Article/details/gtepmxrgrv.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gtdftvfdha.html

[U86] JS：空值合并
来源：http://dali.tianlin.xyz/Article/details/gtoligudof.html

a ?? b
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfvzprnf.html

[U87] JS：解构默认值
来源：http://dali.quarkkingdee.top/Article/details/gtftuvqfai.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhengqikj.top/Article/details/gtrtfivinx.html

[U88] JS：对象展开合并
来源：http://dali.hongshengwenyu.top/Article/details/gtjtfqnxcd.html

{ ...a, ...b }
来源：http://dali.andypj.xyz/Article/details/gttvjgzlyj.html

[U89] JS：数组去重
来源：http://dali.316326.xyz/Article/details/gtcpzuifac.html

[...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gtbxxsvgxc.html

[U90] JS：数字数组排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzcyilpg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrqelbce.html

[U91] JS：对象键值遍历
来源：http://dali.316326.xyz/Article/details/gtulfbgyax.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cashguo.top/Article/details/gtshllmdzs.html

[U92] JS：深拷贝
来源：http://dali.sufxvd.cn/Article/details/gtbmcvgvqs.html

structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtbepncapb.html

[U93] JS：模板字符串
来源：http://dali.ivvv.top/Article/details/gtgciljcqo.html

`共 ${n} 条`
来源：http://dali.gogol.net.cn/Article/details/gtcnvbklby.html

[U94] JS：箭头函数
来源：http://dali.pycfn.com/Article/details/gtjvgmyqoc.html

const double = x => x * 2;
来源：http://dali.zhixingplan.top/Article/details/gtoiqflmrz.html

[U95] JS：Promise 包装
来源：http://dali.kuanghao11.cn/Article/details/gtthlbaazi.html

new Promise((resolve, reject) => {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiedmvqbz.html

[U96] JS：async/await 与异常
来源：http://dali.jinqigfzy.top/Article/details/gtfbgsaint.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gtsrlsysgn.html

[U97] JS：并发请求
来源：http://dali.vqdsnc.cn/Article/details/gtjkeikaiy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gttbbfshhk.html

[U98] JS：fetch 带 JSON
来源：http://dali.sweek.top/Article/details/gttdsybeyf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.9152youxi.cn/Article/details/gtyqfmzcos.html

[U99] JS：事件监听
来源：http://dali.xuetiantiany.cn/Article/details/gtuavfrshq.html

el.addEventListener("click", e => {})
来源：http://dali.daria6918.cn/Article/details/gtqngbrtkx.html

[U100] JS：DOM 查询
来源：http://dali.xylfe.cn/Article/details/gtufvxntqs.html

document.querySelector(".item")
来源：http://dali.ppjwa.cn/Article/details/gtewyzikxz.html

[U101] JS：classList 操作
来源：http://dali.ybcxt.top/Article/details/gthgqqieei.html

el.classList.toggle("active")
来源：http://dali.daxiang520.top/Article/details/gtbjqfgyco.html

[U102] JS：本地存储
来源：http://dali.iojbl.cn/Article/details/gtbwvzuuuq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shanyushiyangtech.top/Article/details/gtujqbxzid.html

[U103] JS：定时器
来源：http://dali.jinqigufen.top/Article/details/gtswswqlqc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinqigfzy.top/Article/details/gtqjthvnos.html

[U104] JS：防抖
来源：http://dali.sweek.top/Article/details/gtdwxhsdmv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gtwqqedafk.html

[U105] JS：节流
来源：http://dali.jqgfzy.top/Article/details/gtaszmdlce.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtmxxfwrwu.html

[U106] JS：日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gtillqcdhs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.kuanghao11.cn/Article/details/gtimqqtbgh.html

[U107] JS：数字千分位
来源：http://dali.ivvv.top/Article/details/gtjnutetki.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sysykeji.top/Article/details/gthjunwkif.html

[U108] JS：随机整数
来源：http://dali.yueranfly.top/Article/details/gtmjydfumv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.fengsongda.top/Article/details/gtotlkvobh.html

[U109] JS：数组分组
来源：http://dali.xziqi.cn/Article/details/gtvbyurbam.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigufen.top/Article/details/gtlfdtcajs.html

[U110] JS：数组分块
来源：http://dali.ppjwa.cn/Article/details/gtymgjikkb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hfpthk.cn/Article/details/gtqgcbftbk.html

[U111] JS：对象转 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcwubdlh.html

new Map(Object.entries(obj))
来源：http://dali.xuanzx.com/Article/details/gteabjspsz.html

[U112] JS：字符串补位
来源：http://dali.kuanghao11.cn/Article/details/gtgrbplqnf.html

"7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtiyrlxxww.html

[U113] JS：正则替换全部
来源：http://dali.gzhubu.top/Article/details/gtjnlhwujc.html

s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtwsdlhlev.html

[U114] JS：JSON 深比较
来源：http://dali.tianlin.xyz/Article/details/gtxatapjax.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.mhx1999.top/Article/details/gthpgvfjfj.html

[U115] JS：生成 UUID
来源：http://dali.tianlin.xyz/Article/details/gtqwcqiaha.html

crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtyerzaugm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinghuilouyu.cn/Article/details/gtprbibsft.html

/** @param {string} name */ function f(name) {}
来源：http://dali.snrcjt.cn/Article/details/gtvqudhsnu.html

[U117] JS：单元测试
来源：http://dali.fzhhl.top/Article/details/gtxlejsbcj.html

npm i -D vitest;  npx vitest
来源：http://dali.9152youxi.cn/Article/details/gtwzszjfks.html

[U118] JS：开发服务器
来源：http://dali.wangshuangyany.cn/Article/details/gtoytjsxug.html

npm i -D vite;  npx vite
来源：http://dali.9152youxi.cn/Article/details/gtawpsjdvl.html

[U119] JS：生产构建
来源：http://dali.hnqzz.top/Article/details/gttvrwhybj.html

npx vite build
来源：http://dali.yuanzhike.top/Article/details/gtfqwvgbkf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hfpthk.cn/Article/details/gtiiomlsdt.html

import.meta.env.VITE_API_URL
来源：http://dali.yonumen.top/Article/details/gthlufhpsv.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtlujcdjur.html

统计汇总
来源：http://dali.chenlongwang.top/Article/details/gtfftxfzmf.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtlaoeztyk.html

按语言统计（条）：
来源：http://dali.tianlin.xyz/Article/details/gtsmiyltdo.html

Python ......... 252
来源：http://dali.nanxinkj.top/Article/details/gtvjpsymcp.html

PHP ............ 252
来源：http://dali.yueranfly.top/Article/details/gtvkosjlqr.html

JavaScript ..... 252
来源：http://dali.tian-w.cn/Article/details/gtwxyydnwy.html

TypeScript ..... 212
来源：http://dali.yongpay.top/Article/details/gtcgmehfpk.html

Java ........... 212
来源：http://dali.shangyingyoupin.top/Article/details/gtxtgqsxpp.html

Go ............. 212
来源：http://dali.ybcxt.top/Article/details/gtrgzcdepd.html

Ruby ........... 212
来源：http://dali.birdmap.top/Article/details/gtegrxegil.html

C# ............. 212
来源：http://dali.gogol.net.cn/Article/details/gtmpeturku.html

C .............. 30
来源：http://dali.gaohongyu789.top/Article/details/gtvlboilmg.html

C++ ............ 30
来源：http://dali.aibaodan.cn/Article/details/gtjssuydea.html

SQL ............ 90
来源：http://dali.svipenyu.cn/Article/details/gtowgmbxlh.html

Bash ........... 80
来源：http://dali.hnxiangtu.top/Article/details/gtlzwumegt.html

Kotlin ......... 15
来源：http://dali.sysykeji.top/Article/details/gtcfvzjbsb.html

Swift .......... 15
来源：http://dali.hysaishi.cn/Article/details/gtimduxhov.html

Lua ............ 10
来源：http://dali.xinyue.icu/Article/details/gteduijfxf.html

Perl ........... 10
来源：http://dali.chenlongwang.top/Article/details/gtzmfiyvvj.html

Scala .......... 10
来源：http://dali.hfpthk.cn/Article/details/gtobelsxla.html

------------------------------------
来源：http://dali.316326.xyz/Article/details/gtdtivjzai.html

合计 ........... 2106 条
来源：http://dali.zdqjudy.top/Article/details/gtebdshwhh.html

按章节统计：
来源：http://dali.dianchejie.cn/Article/details/gtmhukiouu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yonumen.top/Article/details/gtokjrdpgx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.iojbl.cn/Article/details/gtroaeccgy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ehwqpu.com/Article/details/gtewgcqlzp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cqqwz.cn/Article/details/gtwlprqrix.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zdqjudy.top/Article/details/gtztzbydme.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.feifeiyinyue.top/Article/details/gtobxtgfsd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.meibo888.top/Article/details/gtbnplldrz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwcmxmkq.html


<!-- 参考信息 -->