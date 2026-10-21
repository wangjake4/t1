代发 wailian999

[T49] Perl：函数
来源：http://dali.sxryk.cn/Article/details/gtjqxkthez.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtlennuksj.html

[T50] Perl：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphbwhewu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ybcxt.top/Article/details/gtxadnunug.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.9152youxi.cn/Article/details/gtglggscyk.html

[T51] Scala：Hello World
来源：http://dali.xylfe.cn/Article/details/gtrdqjqxld.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtyczsnell.html

[T52] Scala：变量
来源：http://dali.zhengqikj.top/Article/details/gtpyrbfwrl.html

val a = 1;  var b = 2
来源：http://dali.quarkkingdee.top/Article/details/gtfcjqdmmu.html

[T53] Scala：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtvylolnhb.html

s"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gtgrfhwsse.html

[T54] Scala：集合映射
来源：http://dali.0kj1m.cn/Article/details/gthvkemagc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sxryk.cn/Article/details/gtgxjdtieu.html

[T55] Scala：集合过滤
来源：http://dali.dashuyun.cn/Article/details/gtafwkaxsj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gterysugpq.html

[T56] Scala：样例类
来源：http://dali.jyoumei.cn/Article/details/gtzyxhbdms.html

case class User(name: String, age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvkzkyzo.html

[T57] Scala：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gtsydvyhvo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.havefunace.top/Article/details/gtuexofjlb.html

[T58] Scala：函数定义
来源：http://dali.sxryk.cn/Article/details/gthnwmkhno.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xylfe.cn/Article/details/gtpktphtrv.html

[T59] Scala：循环
来源：http://dali.hywenlv.cn/Article/details/gtugtjnuug.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtwxnuamfq.html

[T60] Scala：折叠
来源：http://dali.nanxuanxn.top/Article/details/gtmhcsbbkm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ydzc1.top/Article/details/gtabfhmosi.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtpcotxnla.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yueranfly.top/Article/details/gtvfxxyide.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtfqvmorza.html

[U01] Py：创建虚拟环境
来源：http://dali.hfpthk.cn/Article/details/gtugnkzuox.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangdashe.top/Article/details/gtdzxiqruh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.quarkkingdee.top/Article/details/gtrbicmwhg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sysykeji.top/Article/details/gtxizadcxa.html

[U03] Py：加载 .env 配置
来源：http://dali.chenjidiqi.icu/Article/details/gtszsrkqyp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuonvdwkg.html

[U04] Py：变量调试打印
来源：http://dali.shangyingyoupin.top/Article/details/gtaqwbflgp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.c1oappe.top/Article/details/gtpmbdfvus.html

[U05] Py：列表去重且保序
来源：http://dali.tanke756.top/Article/details/gtvqxscwxk.html

list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtlhexvndr.html

[U06] Py：合并两个字典
来源：http://dali.sweek.top/Article/details/gtgzcxsrxt.html

{**a, **b}
来源：http://dali.quarkkingdee.top/Article/details/gtuoqkikuq.html

[U07] Py：反转字典键值
来源：http://dali.daria6918.cn/Article/details/gtyodwhtjw.html

{v: k for k, v in d.items()}
来源：http://dali.nanxinkj.top/Article/details/gtdqwkdmxx.html

[U08] Py：展平二维列表
来源：http://dali.yonumen.top/Article/details/gtngmlhxom.html

[y for x in nested for y in x]
来源：http://dali.nanxinkj.top/Article/details/gteownsolp.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigfzy.top/Article/details/gteffdserf.html

max(d, key=d.get)
来源：http://dali.yj202588.top/Article/details/gtxytcayzy.html

[U10] Py：按值排序字典
来源：http://dali.sweek.top/Article/details/gtuwueqxrp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yuanzhike.top/Article/details/gtqjypzfrc.html

[U11] Py：生成器表达式
来源：http://dali.nanxuanxn.top/Article/details/gtlnhknpgu.html

(x * 2 for x in arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwoazufax.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.0kj1m.cn/Article/details/gtyfxdzuma.html

Counter(arr).most_common(3)
来源：http://dali.dianchejie.cn/Article/details/gtouxdosnz.html

[U13] Py：固定长度队列
来源：http://dali.tian-w.cn/Article/details/gtqorosmqb.html

deque(maxlen=10)
来源：http://dali.kuanghao11.cn/Article/details/gtsfstillq.html

[U14] Py：分组收集到列表
来源：http://dali.feifeiyinyue.top/Article/details/gtlukuizmy.html

defaultdict(list)
来源：http://dali.jlsjyb.cn/Article/details/gtzdjzvzfu.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gtswuibzif.html

t = time.perf_counter()
来源：http://dali.xziqi.cn/Article/details/gtikvitvau.html

[U16] Py：命令行参数解析
来源：http://dali.hnxiangtu.top/Article/details/gtnlzgesps.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.andypj.xyz/Article/details/gtfyfsurtf.html

[U17] Py：初始化日志
来源：http://dali.hfpthk.cn/Article/details/gtwbsnetik.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.quarkkingdee.top/Article/details/gtqkxuqvww.html

[U18] Py：预编译正则
来源：http://dali.zhoulong.xyz/Article/details/gtfikospcb.html

pat = re.compile(r"\d+")
来源：http://dali.guowangkeji.top/Article/details/gtscpsstcx.html

[U19] Py：正则替换带回调
来源：http://dali.sxryk.cn/Article/details/gtzqmkzdsh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shangyingyoupin.top/Article/details/gtvmicnjjy.html

[U20] Py：缓存函数结果
来源：http://dali.cheryme.top/Article/details/gtnlxwezgw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jiagoushi.top/Article/details/gtaxwsqkpx.html

[U21] Py：自定义上下文管理器
来源：http://dali.shuidangran.top/Article/details/gtacxoyzed.html

@contextlib.contextmanager
来源：http://dali.feifeiyinyue.top/Article/details/gteknivrtt.html

[U22] Py：矩阵转置
来源：http://dali.aizwys.cn/Article/details/gtwarpksol.html

list(zip(*m))
来源：http://dali.gaohongyu789.top/Article/details/gtpzjinyqr.html

[U23] Py：分块读取大文件
来源：http://dali.gaohongyu789.top/Article/details/gtrwrgvtnu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.daxiang520.top/Article/details/gtjvdplult.html

[U24] Py：路径操作
来源：http://dali.havefunace.top/Article/details/gtesxjbmyl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sweek.top/Article/details/gtuahfupdy.html

[U25] Py：CSV 按字典读
来源：http://dali.aizwys.cn/Article/details/gtzmefmxrp.html

csv.DictReader(f)
来源：http://dali.ehwqpu.com/Article/details/gtdkontbks.html

[U26] Py：并发下载
来源：http://dali.iojbl.cn/Article/details/gtsxxoihls.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigufen.top/Article/details/gtocrvhuio.html

[U27] Py：异步 HTTP
来源：http://dali.yuxming.cn/Article/details/gtbwligopl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yj20258888.top/Article/details/gtlydrkrat.html

[U28] Py：类型别名
来源：http://dali.yonumen.top/Article/details/gtsmibcjqo.html

UserId = int
来源：http://dali.pengpengdd.cyou/Article/details/gtajptkgku.html

[U29] Py：属性校验
来源：http://dali.wangdashe.top/Article/details/gtgnxfovdb.html

@property 与 @x.setter 配合
来源：http://dali.ivvv.top/Article/details/gtxkdcmpui.html

[U30] Py：数据类
来源：http://dali.zhengqikj.top/Article/details/gteikzklfa.html

@dataclass(slots=True)
来源：http://dali.smart0.xyz/Article/details/gteuzrgosb.html

[U31] Py：单测
来源：http://dali.ppjwa.cn/Article/details/gtgagjstiw.html

python -m pytest -q
来源：http://dali.nwbrower.top/Article/details/gtrfyoxyko.html

[U32] Py：代码格式化
来源：http://dali.hysaishi.cn/Article/details/gtkdidzoiq.html

ruff format . && ruff check --fix .
来源：http://dali.hongshengwenyu.top/Article/details/gtynbuprfu.html

[U33] Py：打包发布
来源：http://dali.gzhubu.top/Article/details/gtekkcivuh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cashguo.top/Article/details/gtioknpvbb.html

[U34] Py：判断编码
来源：http://dali.yvedp.cn/Article/details/gtmzpsplxu.html

chardet.detect(raw)
来源：http://dali.cqqwz.cn/Article/details/gtskhwmiuj.html

[U35] Py：发送邮件
来源：http://dali.birdmap.top/Article/details/gtxjavyulp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.daxiang520.top/Article/details/gtakghdcdv.html

[U36] Py：定时任务
来源：http://dali.shzxlz.cn/Article/details/gtbnwlqwam.html

schedule.every(10).minutes.do(job)
来源：http://dali.ehwqpu.com/Article/details/gtjuxzqlnb.html

[U37] Py：读写 Excel
来源：http://dali.chenzaomai.com/Article/details/gtizoghlev.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.redwolf501.top/Article/details/gtoetkrzcb.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtrezlhcur.html

Path(__file__).resolve().parent
来源：http://dali.shuidangran.top/Article/details/gtswkfvkxm.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzhjceqi.html

sys.stdout.isatty()
来源：http://dali.dashuyun.cn/Article/details/gtrxbzmzzo.html

[U40] Py：打印到标准错误
来源：http://dali.haohaochexian.top/Article/details/gtctcjnfqr.html

print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gtveftaokd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.fzhhl.top/Article/details/gtjmrzrear.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.kuanghao11.cn/Article/details/gtxlizrjjz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shuidangran.top/Article/details/gtbxyjnica.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.bjfxy.top/Article/details/gtniwnwrwm.html

[U43] PHP：声明命名空间
来源：http://dali.pycfn.com/Article/details/gtfjonyvap.html

namespace App\Http;
来源：http://dali.wangdashe.top/Article/details/gtyalnuiwk.html

[U44] PHP：开启严格类型
来源：http://dali.zhongyouzk.top/Article/details/gtppxklxkz.html

declare(strict_types=1);
来源：http://dali.zhoulong.xyz/Article/details/gtvmwrrxgq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ppjwa.cn/Article/details/gtmigrjakn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gtyqzkqbjt.html

[U46] PHP：可空类型
来源：http://dali.jqgfzy.top/Article/details/gtcdgjfcyy.html

?string $name = null
来源：http://dali.xziqi.cn/Article/details/gtzbmiyoxr.html

[U47] PHP：联合类型
来源：http://dali.andypj.xyz/Article/details/gtivaavubm.html

int|string $id
来源：http://dali.tianlin.xyz/Article/details/gthxolmygn.html

[U48] PHP：纯枚举
来源：http://dali.chenzaomai.com/Article/details/gtmfrsaphu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhengqikj.top/Article/details/gtlfjupcqa.html

[U49] PHP：只读属性
来源：http://dali.feifeiyinyue.top/Article/details/gttifweaya.html

public readonly string $name
来源：http://dali.zycfv.cn/Article/details/gtoavbdyjw.html

[U50] PHP：构造器属性提升
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcmrdmnf.html

public function __construct(private int $id) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtqqvyjrsa.html

[U51] PHP：数组解构
来源：http://dali.daxiang520.top/Article/details/gtjtuwolmj.html

[$a, $b] = $arr;
来源：http://dali.shzxlz.cn/Article/details/gtwrdybztl.html

[U52] PHP：箭头函数
来源：http://dali.aizwys.cn/Article/details/gtabufgzae.html

$double = fn($x) => $x * 2;
来源：http://dali.tianlin.xyz/Article/details/gtghxfuwrx.html

[U53] PHP：空合并运算符
来源：http://dali.haohaochexian.top/Article/details/gtejfajstk.html

$v = $a ?? $b ?? "default";
来源：http://dali.jiagoushi.top/Article/details/gtnocdaare.html

[U54] PHP：空安全调用
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtcinsjr.html

$obj?->method()
来源：http://dali.guannengcc.top/Article/details/gtanyifdfb.html

[U55] PHP：match 表达式
来源：http://dali.fzhhl.top/Article/details/gtdylodmxd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yanxiufei.cn/Article/details/gtvactqznk.html

[U56] PHP：命名参数
来源：http://dali.pycfn.com/Article/details/gtzjfgiibs.html

f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gtoanuccja.html

[U57] PHP：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gtaqcocslt.html

"值: {$a}"
来源：http://dali.ehwqpu.com/Article/details/gtmfhzatny.html

[U58] PHP：数组三件套
来源：http://dali.zhixingplan.top/Article/details/gtolxuieoq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ivvv.top/Article/details/gtbcfgejyo.html

[U59] PHP：自定义排序
来源：http://dali.hnxiangtu.top/Article/details/gtmjxzpsku.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gtxbtzvbbr.html

[U60] PHP：JSON 编解码
来源：http://dali.xinyue.icu/Article/details/gtrnqhxbnr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hfpthk.cn/Article/details/gtliopmodl.html

[U61] PHP：正则
来源：http://dali.ydzc1.top/Article/details/gtddsvdhff.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sxryk.cn/Article/details/gtorkmhdeg.html

[U62] PHP：日期对象
来源：http://dali.gogol.net.cn/Article/details/gtgdpiiyda.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj20258888.top/Article/details/gtyeffsgmw.html

[U63] PHP：文件读写
来源：http://dali.xinyue.icu/Article/details/gtiaxkymwv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xylfe.cn/Article/details/gtlmntbpvx.html

[U64] PHP：目录遍历
来源：http://dali.yvedp.cn/Article/details/gtdoejfxqz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtianuwtum.html

[U65] PHP：会话
来源：http://dali.smart0.xyz/Article/details/gtturjoldr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtxmkxvfns.html

[U66] PHP：设置 Cookie
来源：http://dali.hfpthk.cn/Article/details/gtyrjcpncr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jlsjyb.cn/Article/details/gtbvdxefdw.html

[U67] PHP：处理文件上传
来源：http://dali.jinqigfzy.top/Article/details/gtjwobmccl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yonumen.top/Article/details/gtljhesoam.html

[U68] PHP：PDO 连接
来源：http://dali.ybcxt.top/Article/details/gtumvvnqru.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.316326.xyz/Article/details/gtvpctghyy.html

[U69] PHP：PDO 预处理
来源：http://dali.ehwqpu.com/Article/details/gtmjrscgxt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ppjwa.cn/Article/details/gtfthnxyyf.html

[U70] PHP：PDO 事务
来源：http://dali.zhongyouzk.top/Article/details/gtrrzmkrun.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yuxming.cn/Article/details/gtjtuvqfqy.html

[U71] PHP：抛出异常
来源：http://dali.aizwys.cn/Article/details/gtuazokpyz.html

throw new RuntimeException("失败", 500);
来源：http://dali.cheryme.top/Article/details/gtyonlnlow.html

[U72] PHP：写错误日志
来源：http://dali.cqqwz.cn/Article/details/gtdvutpcew.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yanxiufei.cn/Article/details/gtajoddgvo.html

[U73] PHP：读取 ini 配置
来源：http://dali.sysykeji.top/Article/details/gtjutgjxmi.html

parse_ini_file("config.ini", true)
来源：http://dali.gogol.net.cn/Article/details/gtvjtjrwwi.html

[U74] PHP：读取环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gtuupxmcuv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.nanxuanxn.top/Article/details/gtynpfxgbe.html

[U75] PHP：依赖注入
来源：http://dali.dashuyun.cn/Article/details/gtturnkygz.html

composer require psr/container
来源：http://dali.hfpthk.cn/Article/details/gtdhfvgejq.html

[U76] PHP：简单路由
来源：http://dali.ivvv.top/Article/details/gttwrltmhl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yangfankeji.com/Article/details/gthwbfdtao.html

[U77] PHP：模板渲染
来源：http://dali.shuidangran.top/Article/details/gtgmhfljiz.html

composer require twig/twig
来源：http://dali.ydzc1.top/Article/details/gtprkxwmlq.html

[U78] PHP：单元测试
来源：http://dali.cdnleiting.top/Article/details/gtkipipbdc.html

composer require --dev phpunit/phpunit
来源：http://dali.yj20258.top/Article/details/gteekvplvk.html

[U79] PHP：静态分析
来源：http://dali.andypj.xyz/Article/details/gtdkhqqglj.html

composer require --dev phpstan/phpstan
来源：http://dali.yonumen.top/Article/details/gtjsstcjpg.html

[U80] PHP：代码规范修复
来源：http://dali.sxryk.cn/Article/details/gtgvgvlaoz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.snrcjt.cn/Article/details/gtzeqeciea.html

[U81] JS：初始化项目
来源：http://dali.shuidangran.top/Article/details/gtnrocompj.html

npm init -y;  npm i express
来源：http://dali.hywenlv.cn/Article/details/gtynllgfib.html

[U82] JS：package.json 脚本
来源：http://dali.zhiwuduotai.top/Article/details/gtbrhigfdq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaaslggsg.html

[U83] JS：ES Module 导入导出
来源：http://dali.svipenyu.cn/Article/details/gtfqumpnwd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gtecllqlhr.html

[U84] JS：CommonJS 写法
来源：http://dali.daria6918.cn/Article/details/gtumberasg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.dashuyun.cn/Article/details/gtowvgvtur.html

[U85] JS：可选链
来源：http://dali.shanyushiyangtech.top/Article/details/gteyufelhj.html

a?.b?.c
来源：http://dali.haohaochexian.top/Article/details/gtkfieqxci.html

[U86] JS：空值合并
来源：http://dali.zhiwuduotai.top/Article/details/gtapyvtnrr.html

a ?? b
来源：http://dali.jianghu66.top/Article/details/gtivetckvh.html

[U87] JS：解构默认值
来源：http://dali.nwbrower.top/Article/details/gtnywtyyxu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.chenzaomai.com/Article/details/gtitsinqos.html

[U88] JS：对象展开合并
来源：http://dali.snrcjt.cn/Article/details/gtlyxgdtro.html

{ ...a, ...b }
来源：http://dali.yj20258.top/Article/details/gtadwwdnva.html

[U89] JS：数组去重
来源：http://dali.yueranfly.top/Article/details/gtutbxhaez.html

[...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtbbgnjkrh.html

[U90] JS：数字数组排序
来源：http://dali.ehwqpu.com/Article/details/gtdamtxsgi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtpumwcoje.html

[U91] JS：对象键值遍历
来源：http://dali.hfpthk.cn/Article/details/gtqkjsvzap.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.chenlongwang.top/Article/details/gtrwvhiusm.html

[U92] JS：深拷贝
来源：http://dali.yj202588.top/Article/details/gtkbndiook.html

structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gttbreggxa.html

[U93] JS：模板字符串
来源：http://dali.xinyue.icu/Article/details/gtcikaenin.html

`共 ${n} 条`
来源：http://dali.aibaodan.cn/Article/details/gtxiuqtaxl.html

[U94] JS：箭头函数
来源：http://dali.jlsjyb.cn/Article/details/gtesxhmqhb.html

const double = x => x * 2;
来源：http://dali.zhengqikj.top/Article/details/gtwzvkducb.html

[U95] JS：Promise 包装
来源：http://dali.snrcjt.cn/Article/details/gtqwpeuvqy.html

new Promise((resolve, reject) => {})
来源：http://dali.316326.xyz/Article/details/gtexhgrvsg.html

[U96] JS：async/await 与异常
来源：http://dali.zhongyouzk.top/Article/details/gtegruahos.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtdzjafntm.html

[U97] JS：并发请求
来源：http://dali.zhongyouzk.top/Article/details/gtwnbqwhzx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtqlrlcabn.html

[U98] JS：fetch 带 JSON
来源：http://dali.gogol.net.cn/Article/details/gtofyjfecu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sweek.top/Article/details/gtntenytbs.html

[U99] JS：事件监听
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrksnbre.html

el.addEventListener("click", e => {})
来源：http://dali.xziqi.cn/Article/details/gtjtmjjjks.html

[U100] JS：DOM 查询
来源：http://dali.hysaishi.cn/Article/details/gtoyccijev.html

document.querySelector(".item")
来源：http://dali.hongshengwenyu.top/Article/details/gtarsnkxmq.html

[U101] JS：classList 操作
来源：http://dali.ehwqpu.com/Article/details/gtdrszapeg.html

el.classList.toggle("active")
来源：http://dali.jinghuilouyu.cn/Article/details/gttqpdsgwh.html

[U102] JS：本地存储
来源：http://dali.sweek.top/Article/details/gtirasulcq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.aibaodan.cn/Article/details/gtdyqowzhr.html

[U103] JS：定时器
来源：http://dali.vqdsnc.cn/Article/details/gtyxnypewh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hywenlv.cn/Article/details/gtsqpfsloa.html

[U104] JS：防抖
来源：http://dali.sxryk.cn/Article/details/gtdadnafcq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxnuaufw.html

[U105] JS：节流
来源：http://dali.yanxiufei.cn/Article/details/gthfenniuk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jqgfzy.top/Article/details/gtxmsmtrla.html

[U106] JS：日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtymifarly.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xinyue.icu/Article/details/gteqapvidd.html

[U107] JS：数字千分位
来源：http://dali.sxryk.cn/Article/details/gtinccaccw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gotoacloud.top/Article/details/gtufntsffb.html

[U108] JS：随机整数
来源：http://dali.iojbl.cn/Article/details/gtcnhfvspi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.fengsongda.top/Article/details/gtdkbnrapa.html

[U109] JS：数组分组
来源：http://dali.hywenlv.cn/Article/details/gtenpxtheu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gtttkobkwf.html

[U110] JS：数组分块
来源：http://dali.smart0.xyz/Article/details/gtkfkgbnqc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shuidangran.top/Article/details/gtxrjvoudg.html

[U111] JS：对象转 Map
来源：http://dali.yangfankeji.com/Article/details/gtjbgxmrwx.html

new Map(Object.entries(obj))
来源：http://dali.svipenyu.cn/Article/details/gtzrrzgdxx.html

[U112] JS：字符串补位
来源：http://dali.yongpay.top/Article/details/gteuwxaqqk.html

"7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtspattenu.html

[U113] JS：正则替换全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcoffckbv.html

s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtwfvvoxco.html

[U114] JS：JSON 深比较
来源：http://dali.yongpay.top/Article/details/gtfctajwdb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gtgwdphckw.html

[U115] JS：生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gtaemkxwwm.html

crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtdcyoerrs.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhiwuduotai.top/Article/details/gtkwcrjepw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.guowangkeji.top/Article/details/gtlpewmizt.html

[U117] JS：单元测试
来源：http://dali.vqdsnc.cn/Article/details/gtbtsulnhk.html

npm i -D vitest;  npx vitest
来源：http://dali.pengpengdd.cyou/Article/details/gtfvtzcmlc.html

[U118] JS：开发服务器
来源：http://dali.redwolf501.top/Article/details/gtannibbnz.html

npm i -D vite;  npx vite
来源：http://dali.bjfxy.top/Article/details/gtcgzwkrrt.html

[U119] JS：生产构建
来源：http://dali.snrcjt.cn/Article/details/gtgkrsqmfl.html

npx vite build
来源：http://dali.chenlongwang.top/Article/details/gtxmpymzvm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xuetiantiany.cn/Article/details/gtcbqrmrxb.html

import.meta.env.VITE_API_URL
来源：http://dali.jqgufenzy.top/Article/details/gtnbqvhocy.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtafvyfuqz.html

统计汇总
来源：http://dali.jlsjyb.cn/Article/details/gtfsksbzhq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtzqcwlwrq.html

按语言统计（条）：
来源：http://dali.yangfankeji.com/Article/details/gtrwvwhfrz.html

Python ......... 252
来源：http://dali.xinyue.icu/Article/details/gtsvlccbak.html

PHP ............ 252
来源：http://dali.yueranfly.top/Article/details/gthvimomim.html

JavaScript ..... 252
来源：http://dali.sweek.top/Article/details/gttvgtwppe.html

TypeScript ..... 212
来源：http://dali.pycfn.com/Article/details/gtcmdqwocq.html

Java ........... 212
来源：http://dali.vqdsnc.cn/Article/details/gthfisrofh.html

Go ............. 212
来源：http://dali.yj20258.top/Article/details/gtcsxrmebj.html

Ruby ........... 212
来源：http://dali.gogol.net.cn/Article/details/gtkxmhanhy.html

C# ............. 212
来源：http://dali.dianchejie.cn/Article/details/gtjnxypnuw.html

C .............. 30
来源：http://dali.hysaishi.cn/Article/details/gtsdjvczbd.html

C++ ............ 30
来源：http://dali.zhengqikj.top/Article/details/gtdgrpfeuv.html

SQL ............ 90
来源：http://dali.hnxiangtu.top/Article/details/gtdgsnfevx.html

Bash ........... 80
来源：http://dali.yanxiufei.cn/Article/details/gtvckivpqj.html

Kotlin ......... 15
来源：http://dali.chenzaomai.com/Article/details/gtdotwwpux.html

Swift .......... 15
来源：http://dali.zhongyouzk.top/Article/details/gtifbslisa.html

Lua ............ 10
来源：http://dali.meibo888.top/Article/details/gtpmukzgky.html

Perl ........... 10
来源：http://dali.snrcjt.cn/Article/details/gtzedzejbm.html

Scala .......... 10
来源：http://dali.redwolf501.top/Article/details/gtvhiagffq.html

------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtseoxvxih.html

合计 ........... 2106 条
来源：http://dali.yueranfly.top/Article/details/gtdpayokbl.html

按章节统计：
来源：http://dali.yj20258888.top/Article/details/gtfknrdoln.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hfpthk.cn/Article/details/gtujozbshh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jlsjyb.cn/Article/details/gtbhhiizuo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yj202588.top/Article/details/gtmdamxycl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nanxuanxn.top/Article/details/gtvhbgfurc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.chenjidiqi.icu/Article/details/gtpevfiidm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhongyouzk.top/Article/details/gtzbzmocuk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gtdxfztrlu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.svipenyu.cn/Article/details/gtybyctnar.html


<!-- 参考信息 -->