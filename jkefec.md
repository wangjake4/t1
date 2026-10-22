代发 wailian999

[T49] Perl：函数
来源：http://dali.sxryk.cn/Article/details/gtfrfqszpz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtzgybpwai.html

[T50] Perl：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtmogvhlhp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aizwys.cn/Article/details/gtjujhjnul.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ybcxt.top/Article/details/gtepxietih.html

[T51] Scala：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtxndieqao.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gtrkoggaag.html

[T52] Scala：变量
来源：http://dali.quarkkingdee.top/Article/details/gtqtguqiat.html

val a = 1;  var b = 2
来源：http://dali.yj20258888.top/Article/details/gtbvvajeet.html

[T53] Scala：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtsykolndm.html

s"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gthirmypjj.html

[T54] Scala：集合映射
来源：http://dali.bjfxy.top/Article/details/gtufbaiiet.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.kuanghao11.cn/Article/details/gtfgsqjwdt.html

[T55] Scala：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gtuihmxnrm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.dianchejie.cn/Article/details/gtngnckybs.html

[T56] Scala：样例类
来源：http://dali.yvedp.cn/Article/details/gtozsfaeph.html

case class User(name: String, age: Int)
来源：http://dali.shanyushiyangtech.top/Article/details/gthuxpwixk.html

[T57] Scala：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gtwwuppiws.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dianchejie.cn/Article/details/gtopiyksbm.html

[T58] Scala：函数定义
来源：http://dali.jqgfzy.top/Article/details/gtnnfkcfon.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.iojbl.cn/Article/details/gtheqgwfju.html

[T59] Scala：循环
来源：http://dali.daria6918.cn/Article/details/gtcbkrfvug.html

for (i <- 1 to 10) println(i)
来源：http://dali.xylfe.cn/Article/details/gtawwhsuna.html

[T60] Scala：折叠
来源：http://dali.ehwqpu.com/Article/details/gtdxcqfuku.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.c1oappe.top/Article/details/gtprefxkpy.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtgxngtaaa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnxiangtu.top/Article/details/gthorbxklg.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfskkbcjs.html

[U01] Py：创建虚拟环境
来源：http://dali.xinyue.icu/Article/details/gtyhtidbav.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sufxvd.cn/Article/details/gtkfkcexfp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.wangdashe.top/Article/details/gtrcnlefjf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj20258888.top/Article/details/gtzdbxghlb.html

[U03] Py：加载 .env 配置
来源：http://dali.xziqi.cn/Article/details/gtktfbcerp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenjidiqi.icu/Article/details/gtxhxxigiz.html

[U04] Py：变量调试打印
来源：http://dali.hfpthk.cn/Article/details/gtyxzajetv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.c1oappe.top/Article/details/gtyxpmpxdt.html

[U05] Py：列表去重且保序
来源：http://dali.mhx1999.top/Article/details/gtilxlmbmo.html

list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gtqsjuzmim.html

[U06] Py：合并两个字典
来源：http://dali.smart0.xyz/Article/details/gtqalkfzks.html

{**a, **b}
来源：http://dali.hfpthk.cn/Article/details/gtxfyjdvqn.html

[U07] Py：反转字典键值
来源：http://dali.yangfankeji.com/Article/details/gtysgtolnm.html

{v: k for k, v in d.items()}
来源：http://dali.yvedp.cn/Article/details/gtvoorrbqp.html

[U08] Py：展平二维列表
来源：http://dali.zhongyouzk.top/Article/details/gtzoqnlopr.html

[y for x in nested for y in x]
来源：http://dali.yuanzhike.top/Article/details/gtsdrnynpx.html

[U09] Py：字典取最大值的键
来源：http://dali.pycfn.com/Article/details/gtbuvariun.html

max(d, key=d.get)
来源：http://dali.jyoumei.cn/Article/details/gtsnwdxehj.html

[U10] Py：按值排序字典
来源：http://dali.tianlin.xyz/Article/details/gtpgjznnfj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cdnleiting.top/Article/details/gtwwvnbdio.html

[U11] Py：生成器表达式
来源：http://dali.tian-w.cn/Article/details/gtnsrgppdk.html

(x * 2 for x in arr)
来源：http://dali.yonumen.top/Article/details/gtjypxocma.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tian-w.cn/Article/details/gtbcxtjoex.html

Counter(arr).most_common(3)
来源：http://dali.tian-w.cn/Article/details/gtboeukjan.html

[U13] Py：固定长度队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwkvlldo.html

deque(maxlen=10)
来源：http://dali.yongpay.top/Article/details/gtrgsgkghw.html

[U14] Py：分组收集到列表
来源：http://dali.guannengcc.top/Article/details/gtnmkrniso.html

defaultdict(list)
来源：http://dali.ppjwa.cn/Article/details/gtvrmrdpzx.html

[U15] Py：高精度计时
来源：http://dali.jinqigufen.top/Article/details/gtzpdsjdai.html

t = time.perf_counter()
来源：http://dali.svipenyu.cn/Article/details/gtwvoisrxs.html

[U16] Py：命令行参数解析
来源：http://dali.xuanzx.com/Article/details/gtktzpmsrg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.snrcjt.cn/Article/details/gtvusxejbn.html

[U17] Py：初始化日志
来源：http://dali.nwbrower.top/Article/details/gtypegzavs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ppjwa.cn/Article/details/gtedhezfyv.html

[U18] Py：预编译正则
来源：http://dali.zhoulong.xyz/Article/details/gtxvwgqjuh.html

pat = re.compile(r"\d+")
来源：http://dali.gzhubu.top/Article/details/gtaqrzuhlp.html

[U19] Py：正则替换带回调
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfaxcniv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ydzc1.top/Article/details/gtaqhjavzv.html

[U20] Py：缓存函数结果
来源：http://dali.jlsjyb.cn/Article/details/gtxnbuwity.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shzxlz.cn/Article/details/gtwtchhklg.html

[U21] Py：自定义上下文管理器
来源：http://dali.shangyingyoupin.top/Article/details/gtqtesshco.html

@contextlib.contextmanager
来源：http://dali.aibaodan.cn/Article/details/gtlzwzzmdc.html

[U22] Py：矩阵转置
来源：http://dali.zhoulong.xyz/Article/details/gtyznxzfvq.html

list(zip(*m))
来源：http://dali.snrcjt.cn/Article/details/gtjehbjbjg.html

[U23] Py：分块读取大文件
来源：http://dali.smart0.xyz/Article/details/gtfxxlqzlt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hongshengwenyu.top/Article/details/gtxquqpvua.html

[U24] Py：路径操作
来源：http://dali.zhixingplan.top/Article/details/gthoihhuql.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gtvuqlbibo.html

[U25] Py：CSV 按字典读
来源：http://dali.daria6918.cn/Article/details/gtdebiemjw.html

csv.DictReader(f)
来源：http://dali.chenlongwang.top/Article/details/gtxvlenqio.html

[U26] Py：并发下载
来源：http://dali.daxiang520.top/Article/details/gttegnvjdh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yuanzhike.top/Article/details/gtsftprrbs.html

[U27] Py：异步 HTTP
来源：http://dali.wangshuangyany.cn/Article/details/gtujbrdfcs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tian-w.cn/Article/details/gtgvyhptnw.html

[U28] Py：类型别名
来源：http://dali.sweek.top/Article/details/gtdzxqanas.html

UserId = int
来源：http://dali.chenlongwang.top/Article/details/gtnqptucoh.html

[U29] Py：属性校验
来源：http://dali.hnxiangtu.top/Article/details/gtqofnwrum.html

@property 与 @x.setter 配合
来源：http://dali.vqdsnc.cn/Article/details/gtetwqcvhq.html

[U30] Py：数据类
来源：http://dali.guannengcc.top/Article/details/gtbhhagrqf.html

@dataclass(slots=True)
来源：http://dali.zhongyouzk.top/Article/details/gtoftuzyjk.html

[U31] Py：单测
来源：http://dali.dianchejie.cn/Article/details/gtijgdmvru.html

python -m pytest -q
来源：http://dali.9152youxi.cn/Article/details/gtizcncria.html

[U32] Py：代码格式化
来源：http://dali.yvedp.cn/Article/details/gteuteiseo.html

ruff format . && ruff check --fix .
来源：http://dali.ehwqpu.com/Article/details/gtptncjdcf.html

[U33] Py：打包发布
来源：http://dali.c1oappe.top/Article/details/gtmexsasrn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhoulong.xyz/Article/details/gtbdjsyttd.html

[U34] Py：判断编码
来源：http://dali.jiagoushi.top/Article/details/gtrucxpjmh.html

chardet.detect(raw)
来源：http://dali.hfpthk.cn/Article/details/gtouneuhfi.html

[U35] Py：发送邮件
来源：http://dali.cdnleiting.top/Article/details/gttfwpdgjl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.chenzaomai.com/Article/details/gtzampouve.html

[U36] Py：定时任务
来源：http://dali.wangshuangyany.cn/Article/details/gtetthfvlv.html

schedule.every(10).minutes.do(job)
来源：http://dali.xziqi.cn/Article/details/gtxpxxqntf.html

[U37] Py：读写 Excel
来源：http://dali.redwolf501.top/Article/details/gtnqcmzupd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhengqikj.top/Article/details/gtjiahstib.html

[U38] Py：获取脚本所在目录
来源：http://dali.sufxvd.cn/Article/details/gtrjoyohow.html

Path(__file__).resolve().parent
来源：http://dali.xylfe.cn/Article/details/gtavcgpyci.html

[U39] Py：判断是否在交互环境
来源：http://dali.yj20258.top/Article/details/gtcuxgkfbd.html

sys.stdout.isatty()
来源：http://dali.jinqigfzy.top/Article/details/gtxgiontgc.html

[U40] Py：打印到标准错误
来源：http://dali.cheryme.top/Article/details/gtlftopeqn.html

print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gttmzthzut.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxwtjwby.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sxryk.cn/Article/details/gtdgjqfkir.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhixingplan.top/Article/details/gtvvljxrqt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shzxlz.cn/Article/details/gtqdfnjwkh.html

[U43] PHP：声明命名空间
来源：http://dali.havefunace.top/Article/details/gtzvktfcpq.html

namespace App\Http;
来源：http://dali.hnxiangtu.top/Article/details/gterjhrgts.html

[U44] PHP：开启严格类型
来源：http://dali.andypj.xyz/Article/details/gtcssxfuyy.html

declare(strict_types=1);
来源：http://dali.svipenyu.cn/Article/details/gtoinobmym.html

[U45] PHP：类型声明与返回类型
来源：http://dali.haohaochexian.top/Article/details/gtttdsbbar.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtfxxuglqr.html

[U46] PHP：可空类型
来源：http://dali.jinqigufen.top/Article/details/gtgnagslcv.html

?string $name = null
来源：http://dali.hywenlv.cn/Article/details/gtbfjfrcey.html

[U47] PHP：联合类型
来源：http://dali.jyoumei.cn/Article/details/gtjjlbzzcq.html

int|string $id
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbklocpig.html

[U48] PHP：纯枚举
来源：http://dali.yueranfly.top/Article/details/gtqcsyqpoz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtvywzmt.html

[U49] PHP：只读属性
来源：http://dali.yongpay.top/Article/details/gthuxwtlpe.html

public readonly string $name
来源：http://dali.c1oappe.top/Article/details/gtsohvppli.html

[U50] PHP：构造器属性提升
来源：http://dali.chenjidiqi.icu/Article/details/gtvdlysedu.html

public function __construct(private int $id) {}
来源：http://dali.cashguo.top/Article/details/gtynxzbgfk.html

[U51] PHP：数组解构
来源：http://dali.gaohongyu789.top/Article/details/gtolvrsdtb.html

[$a, $b] = $arr;
来源：http://dali.xuetiantiany.cn/Article/details/gtmktliior.html

[U52] PHP：箭头函数
来源：http://dali.yj20258.top/Article/details/gtgvretdpy.html

$double = fn($x) => $x * 2;
来源：http://dali.jinqigufen.top/Article/details/gtybduedyc.html

[U53] PHP：空合并运算符
来源：http://dali.ppjwa.cn/Article/details/gtscralbll.html

$v = $a ?? $b ?? "default";
来源：http://dali.chenjidiqi.icu/Article/details/gtqaiiobkf.html

[U54] PHP：空安全调用
来源：http://dali.smart0.xyz/Article/details/gtrgathnbo.html

$obj?->method()
来源：http://dali.gaohongyu789.top/Article/details/gtetwaxnxx.html

[U55] PHP：match 表达式
来源：http://dali.smart0.xyz/Article/details/gtsnysxwze.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xinyue.icu/Article/details/gtwsabcxwu.html

[U56] PHP：命名参数
来源：http://dali.sysykeji.top/Article/details/gtqrnsfjkd.html

f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gtbqoupskn.html

[U57] PHP：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtjiltofev.html

"值: {$a}"
来源：http://dali.zdqjudy.top/Article/details/gtugrdzdzy.html

[U58] PHP：数组三件套
来源：http://dali.hnxiangtu.top/Article/details/gteaaigoxp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.aibaodan.cn/Article/details/gtmdbzqlxa.html

[U59] PHP：自定义排序
来源：http://dali.quarkkingdee.top/Article/details/gtizjvkgkb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gtjxshtxxe.html

[U60] PHP：JSON 编解码
来源：http://dali.jianghu66.top/Article/details/gtdfttizrq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttaojloya.html

[U61] PHP：正则
来源：http://dali.fzhhl.top/Article/details/gtncjdbkhr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gtfsfjzjxn.html

[U62] PHP：日期对象
来源：http://dali.tian-w.cn/Article/details/gthgvcwlvk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jiagoushi.top/Article/details/gttqpnpeky.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gtnahmyavo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.tian-w.cn/Article/details/gtwylwzdwu.html

[U64] PHP：目录遍历
来源：http://dali.pycfn.com/Article/details/gtcabvmzho.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.9152youxi.cn/Article/details/gtkttpimgt.html

[U65] PHP：会话
来源：http://dali.0kj1m.cn/Article/details/gtfujuvdkm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gthjdkgnqg.html

[U66] PHP：设置 Cookie
来源：http://dali.xuetiantiany.cn/Article/details/gtdmhlsjhi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.chenlongwang.top/Article/details/gtbhftfghx.html

[U67] PHP：处理文件上传
来源：http://dali.yj20258888.top/Article/details/gtymyhkawv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yanxiufei.cn/Article/details/gtmurksymr.html

[U68] PHP：PDO 连接
来源：http://dali.gzhubu.top/Article/details/gtbraoxhlw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.kuanghao11.cn/Article/details/gtrhtdzigr.html

[U69] PHP：PDO 预处理
来源：http://dali.yueranfly.top/Article/details/gtblanttki.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.fzhhl.top/Article/details/gtfbouszij.html

[U70] PHP：PDO 事务
来源：http://dali.guowangkeji.top/Article/details/gtmnojkvji.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.chenjidiqi.icu/Article/details/gtghsmnhmo.html

[U71] PHP：抛出异常
来源：http://dali.sxryk.cn/Article/details/gtiaowvbcq.html

throw new RuntimeException("失败", 500);
来源：http://dali.yuanzhike.top/Article/details/gtrqsjlkzb.html

[U72] PHP：写错误日志
来源：http://dali.0kj1m.cn/Article/details/gteeeukflv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xuetiantiany.cn/Article/details/gtxfrpjyqk.html

[U73] PHP：读取 ini 配置
来源：http://dali.yuanzhike.top/Article/details/gtinrqluje.html

parse_ini_file("config.ini", true)
来源：http://dali.sysykeji.top/Article/details/gtrocwszsi.html

[U74] PHP：读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwgruocd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhongyouzk.top/Article/details/gtzynnebse.html

[U75] PHP：依赖注入
来源：http://dali.nwbrower.top/Article/details/gtbyqopuzi.html

composer require psr/container
来源：http://dali.yueranfly.top/Article/details/gtmjgpzzih.html

[U76] PHP：简单路由
来源：http://dali.zhixingplan.top/Article/details/gtypxgacfq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hywenlv.cn/Article/details/gtghrodqlm.html

[U77] PHP：模板渲染
来源：http://dali.guannengcc.top/Article/details/gtmqvjtazn.html

composer require twig/twig
来源：http://dali.jlsjyb.cn/Article/details/gtioikmdan.html

[U78] PHP：单元测试
来源：http://dali.cashguo.top/Article/details/gthwtkdkev.html

composer require --dev phpunit/phpunit
来源：http://dali.nanxinkj.top/Article/details/gttgthxqum.html

[U79] PHP：静态分析
来源：http://dali.pycfn.com/Article/details/gtcqagaoaj.html

composer require --dev phpstan/phpstan
来源：http://dali.kuanghao11.cn/Article/details/gtfpptohyn.html

[U80] PHP：代码规范修复
来源：http://dali.daria6918.cn/Article/details/gtynfezbci.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gtogsgstgv.html

[U81] JS：初始化项目
来源：http://dali.yangfankeji.com/Article/details/gtzctngavo.html

npm init -y;  npm i express
来源：http://dali.cqqwz.cn/Article/details/gtkiugkuow.html

[U82] JS：package.json 脚本
来源：http://dali.ydzc1.top/Article/details/gtyqjznixs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shuidangran.top/Article/details/gttcrbbmrj.html

[U83] JS：ES Module 导入导出
来源：http://dali.tian-w.cn/Article/details/gtjjfyvlqg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gogol.net.cn/Article/details/gtoeykohuk.html

[U84] JS：CommonJS 写法
来源：http://dali.tanke756.top/Article/details/gtzsebmkwn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.redwolf501.top/Article/details/gtjyuxwghb.html

[U85] JS：可选链
来源：http://dali.hnxiangtu.top/Article/details/gtpketmyry.html

a?.b?.c
来源：http://dali.gzhubu.top/Article/details/gtmpajfzcm.html

[U86] JS：空值合并
来源：http://dali.jinqigfzy.top/Article/details/gtdzwdjfcq.html

a ?? b
来源：http://dali.fengsongda.top/Article/details/gtckgbifxh.html

[U87] JS：解构默认值
来源：http://dali.pycfn.com/Article/details/gtkunzxzdr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.aizwys.cn/Article/details/gtrzmnqkhl.html

[U88] JS：对象展开合并
来源：http://dali.zhixingplan.top/Article/details/gtkvpxjbyz.html

{ ...a, ...b }
来源：http://dali.ppjwa.cn/Article/details/gtxcxefwnx.html

[U89] JS：数组去重
来源：http://dali.yj202588.top/Article/details/gtwwyfndjz.html

[...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxloicqz.html

[U90] JS：数字数组排序
来源：http://dali.hysaishi.cn/Article/details/gtapyvcfys.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gtnfhlbzhk.html

[U91] JS：对象键值遍历
来源：http://dali.sweek.top/Article/details/gtnkjlxoij.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gzhubu.top/Article/details/gtmnlyxqiu.html

[U92] JS：深拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtfijffxng.html

structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtpvzvxwnh.html

[U93] JS：模板字符串
来源：http://dali.mhx1999.top/Article/details/gtqojjzjls.html

`共 ${n} 条`
来源：http://dali.ehwqpu.com/Article/details/gtjfttalra.html

[U94] JS：箭头函数
来源：http://dali.redwolf501.top/Article/details/gtjcjvcnxq.html

const double = x => x * 2;
来源：http://dali.guowangkeji.top/Article/details/gtslzqxkof.html

[U95] JS：Promise 包装
来源：http://dali.chenzaomai.com/Article/details/gtikqezfig.html

new Promise((resolve, reject) => {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwflmrfc.html

[U96] JS：async/await 与异常
来源：http://dali.nwbrower.top/Article/details/gtxalksfjg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtjhekyexj.html

[U97] JS：并发请求
来源：http://dali.ppjwa.cn/Article/details/gtgobidrsy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtagonsqlr.html

[U98] JS：fetch 带 JSON
来源：http://dali.dianchejie.cn/Article/details/gttxemikwv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.andypj.xyz/Article/details/gtzmocbwds.html

[U99] JS：事件监听
来源：http://dali.yj20258888.top/Article/details/gtfqkdfjzk.html

el.addEventListener("click", e => {})
来源：http://dali.cashguo.top/Article/details/gtyzcpmrue.html

[U100] JS：DOM 查询
来源：http://dali.jqgufenzy.top/Article/details/gttiqrazzz.html

document.querySelector(".item")
来源：http://dali.aizwys.cn/Article/details/gtjkcvxzye.html

[U101] JS：classList 操作
来源：http://dali.sysykeji.top/Article/details/gtqeuknokk.html

el.classList.toggle("active")
来源：http://dali.hysaishi.cn/Article/details/gtepeledvb.html

[U102] JS：本地存储
来源：http://dali.havefunace.top/Article/details/gtbongvlpa.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.dashuyun.cn/Article/details/gtymqqaxki.html

[U103] JS：定时器
来源：http://dali.fzhhl.top/Article/details/gttqsxczrs.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ppjwa.cn/Article/details/gtijnqgooy.html

[U104] JS：防抖
来源：http://dali.shzxlz.cn/Article/details/gtkyiaoars.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtvhamplsd.html

[U105] JS：节流
来源：http://dali.jlsjyb.cn/Article/details/gtxhsvxqiz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tian-w.cn/Article/details/gtekgbolym.html

[U106] JS：日期格式化
来源：http://dali.tian-w.cn/Article/details/gtifzgrnrj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yuanzhike.top/Article/details/gtjoiurnpw.html

[U107] JS：数字千分位
来源：http://dali.sweek.top/Article/details/gtzacmadcn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cashguo.top/Article/details/gtezdrzqqn.html

[U108] JS：随机整数
来源：http://dali.gotoacloud.top/Article/details/gtuiislici.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jianghu66.top/Article/details/gtbdabyxvh.html

[U109] JS：数组分组
来源：http://dali.ehwqpu.com/Article/details/gttvicbqks.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gtjrgjwybx.html

[U110] JS：数组分块
来源：http://dali.sxryk.cn/Article/details/gtxlbgqwrd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hfpthk.cn/Article/details/gtluxdsked.html

[U111] JS：对象转 Map
来源：http://dali.andypj.xyz/Article/details/gtgddcdosv.html

new Map(Object.entries(obj))
来源：http://dali.jinghuilouyu.cn/Article/details/gtzuqixxxb.html

[U112] JS：字符串补位
来源：http://dali.zhiwuduotai.top/Article/details/gtksrriarn.html

"7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gtwjywxmiv.html

[U113] JS：正则替换全部
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrdqiwbf.html

s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtnrmnlgwi.html

[U114] JS：JSON 深比较
来源：http://dali.cashguo.top/Article/details/gttdxrbnlt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gtxebqebsb.html

[U115] JS：生成 UUID
来源：http://dali.nwbrower.top/Article/details/gtdtwnhlck.html

crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gtbltarvyc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.guannengcc.top/Article/details/gtncmdgcjz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gotoacloud.top/Article/details/gtialvkamg.html

[U117] JS：单元测试
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhgybagk.html

npm i -D vitest;  npx vitest
来源：http://dali.redwolf501.top/Article/details/gtkzvyzhxa.html

[U118] JS：开发服务器
来源：http://dali.xinyue.icu/Article/details/gtbibckdmn.html

npm i -D vite;  npx vite
来源：http://dali.sufxvd.cn/Article/details/gtgusnzlyx.html

[U119] JS：生产构建
来源：http://dali.gotoacloud.top/Article/details/gtoloqiygz.html

npx vite build
来源：http://dali.sufxvd.cn/Article/details/gtmdbvyryu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.feifeiyinyue.top/Article/details/gtatutgsgn.html

import.meta.env.VITE_API_URL
来源：http://dali.sxryk.cn/Article/details/gtxsfkawlb.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbcayqwb.html

统计汇总
来源：http://dali.quarkkingdee.top/Article/details/gtukwjyzcg.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtoskqjjfl.html

按语言统计（条）：
来源：http://dali.smart0.xyz/Article/details/gtzajzcgdq.html

Python ......... 252
来源：http://dali.sxryk.cn/Article/details/gtmhjfpipj.html

PHP ............ 252
来源：http://dali.316326.xyz/Article/details/gtewhkejun.html

JavaScript ..... 252
来源：http://dali.aibaodan.cn/Article/details/gtfllzmooe.html

TypeScript ..... 212
来源：http://dali.jianghu66.top/Article/details/gtpnxsmqsf.html

Java ........... 212
来源：http://dali.daxiang520.top/Article/details/gtebcoledw.html

Go ............. 212
来源：http://dali.aizwys.cn/Article/details/gtdgrngzpu.html

Ruby ........... 212
来源：http://dali.chenlongwang.top/Article/details/gthlnvqkhn.html

C# ............. 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmepnyap.html

C .............. 30
来源：http://dali.yj202588.top/Article/details/gtcsimpmkz.html

C++ ............ 30
来源：http://dali.cashguo.top/Article/details/gtahdgwxty.html

SQL ............ 90
来源：http://dali.sxryk.cn/Article/details/gtaacfoegb.html

Bash ........... 80
来源：http://dali.cucudq.cn/Article/details/gtbynofeof.html

Kotlin ......... 15
来源：http://dali.andypj.xyz/Article/details/gtzabzzvhw.html

Swift .......... 15
来源：http://dali.cashguo.top/Article/details/gtdhwqwtct.html

Lua ............ 10
来源：http://dali.sweek.top/Article/details/gtwxmwamqi.html

Perl ........... 10
来源：http://dali.birdmap.top/Article/details/gtqsqqbbrq.html

Scala .......... 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkebdvuc.html

------------------------------------
来源：http://dali.fengsongda.top/Article/details/gtmdwrnfqn.html

合计 ........... 2106 条
来源：http://dali.cheryme.top/Article/details/gtxdollsxj.html

按章节统计：
来源：http://dali.birdmap.top/Article/details/gtblmmqhjp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hywenlv.cn/Article/details/gtxkifokkz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jlsjyb.cn/Article/details/gtzyummvef.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.nanxuanxn.top/Article/details/gturpnmyqi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ivvv.top/Article/details/gtnkabkluz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.vqdsnc.cn/Article/details/gtwcwhcyfs.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ydzc1.top/Article/details/gtlcmbjfuh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yanxiufei.cn/Article/details/gttqmdmjja.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shuidangran.top/Article/details/gtouivsabc.html


<!-- 参考信息 -->