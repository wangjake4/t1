代发 wailian999

while (my $line = <$fh>) { print $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwebiftvm.html

[T51] Scala：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtlvulluzi.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gtwlxxhtrb.html

[T52] Scala：变量
来源：http://dali.nanxuanxn.top/Article/details/gtgqdostjy.html

val a = 1;  var b = 2
来源：http://dali.cucudq.cn/Article/details/gtfrknwzao.html

[T53] Scala：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtiwitsrhw.html

s"值: $b"
来源：http://dali.pycfn.com/Article/details/gtcsnimryc.html

[T54] Scala：集合映射
来源：http://dali.316326.xyz/Article/details/gtsuwafydb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.guannengcc.top/Article/details/gtqiggrhsv.html

[T55] Scala：集合过滤
来源：http://dali.iojbl.cn/Article/details/gtvohfposu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cucudq.cn/Article/details/gtaritanli.html

[T56] Scala：样例类
来源：http://dali.quarkkingdee.top/Article/details/gtttpvbjql.html

case class User(name: String, age: Int)
来源：http://dali.gogol.net.cn/Article/details/gticmnaukn.html

[T57] Scala：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gtrfvllcvu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgliuyefw.html

[T58] Scala：函数定义
来源：http://dali.xuetiantiany.cn/Article/details/gtxpcnqdlw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.c1oappe.top/Article/details/gtqbkgkvvl.html

[T59] Scala：循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtaruftfwa.html

for (i <- 1 to 10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gtufjyylcv.html

[T60] Scala：折叠
来源：http://dali.smart0.xyz/Article/details/gtxmantzag.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinqigfzy.top/Article/details/gtqtdiszuz.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gttxlstghp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.havefunace.top/Article/details/gtdsbquswg.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtwaxatayo.html

[U01] Py：创建虚拟环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnntshwa.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yvedp.cn/Article/details/gtkhqggvtr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shzxlz.cn/Article/details/gtpeyeojsn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.0kj1m.cn/Article/details/gtxvbpisud.html

[U03] Py：加载 .env 配置
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmlbnanw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.svipenyu.cn/Article/details/gtnbkunjut.html

[U04] Py：变量调试打印
来源：http://dali.wangshuangyany.cn/Article/details/gteeehabah.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.0kj1m.cn/Article/details/gtmutcwiab.html

[U05] Py：列表去重且保序
来源：http://dali.cucudq.cn/Article/details/gtlpxuhqbw.html

list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gtmwpxsace.html

[U06] Py：合并两个字典
来源：http://dali.xuanzx.com/Article/details/gtwkkymwep.html

{**a, **b}
来源：http://dali.cdnleiting.top/Article/details/gtyaibumfh.html

[U07] Py：反转字典键值
来源：http://dali.c1oappe.top/Article/details/gtnobynshl.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258.top/Article/details/gtujbvfwhm.html

[U08] Py：展平二维列表
来源：http://dali.fengsongda.top/Article/details/gtynzogoct.html

[y for x in nested for y in x]
来源：http://dali.jinqigfzy.top/Article/details/gtkvtyksaq.html

[U09] Py：字典取最大值的键
来源：http://dali.316326.xyz/Article/details/gtlzttqgfy.html

max(d, key=d.get)
来源：http://dali.ehwqpu.com/Article/details/gtyoiurxer.html

[U10] Py：按值排序字典
来源：http://dali.gogol.net.cn/Article/details/gtgdlwbkvi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sweek.top/Article/details/gtrpcuyaau.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gteipzvdsw.html

(x * 2 for x in arr)
来源：http://dali.jqgfzy.top/Article/details/gtbfnxcbmx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.redwolf501.top/Article/details/gtpecwmqbg.html

Counter(arr).most_common(3)
来源：http://dali.xziqi.cn/Article/details/gtmpslaqlo.html

[U13] Py：固定长度队列
来源：http://dali.hnxiangtu.top/Article/details/gtmjsxuupo.html

deque(maxlen=10)
来源：http://dali.kuanghao11.cn/Article/details/gtchvlxhxc.html

[U14] Py：分组收集到列表
来源：http://dali.jinqigufen.top/Article/details/gtovhwszqs.html

defaultdict(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqzazpei.html

[U15] Py：高精度计时
来源：http://dali.jlsjyb.cn/Article/details/gtgfsidxhn.html

t = time.perf_counter()
来源：http://dali.tanke756.top/Article/details/gtwywzsjzu.html

[U16] Py：命令行参数解析
来源：http://dali.hysaishi.cn/Article/details/gtqpkudjfd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yj20258.top/Article/details/gtwxdbkoiu.html

[U17] Py：初始化日志
来源：http://dali.cheryme.top/Article/details/gtxuctjsua.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.birdmap.top/Article/details/gtihedaeha.html

[U18] Py：预编译正则
来源：http://dali.shanyushiyangtech.top/Article/details/gthdpgwknk.html

pat = re.compile(r"\d+")
来源：http://dali.shuidangran.top/Article/details/gtohadjksp.html

[U19] Py：正则替换带回调
来源：http://dali.yvedp.cn/Article/details/gtxpmiugef.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sxryk.cn/Article/details/gtezlsekap.html

[U20] Py：缓存函数结果
来源：http://dali.cucudq.cn/Article/details/gtxsunkabd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xylfe.cn/Article/details/gtlidtnsno.html

[U21] Py：自定义上下文管理器
来源：http://dali.0kj1m.cn/Article/details/gtqzdsrmsq.html

@contextlib.contextmanager
来源：http://dali.yvedp.cn/Article/details/gtsxnqznqg.html

[U22] Py：矩阵转置
来源：http://dali.wangshuangyany.cn/Article/details/gtwqndtnpa.html

list(zip(*m))
来源：http://dali.ydzc1.top/Article/details/gtgzjnwxwa.html

[U23] Py：分块读取大文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvfvqfzs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ppjwa.cn/Article/details/gtnrpuhykb.html

[U24] Py：路径操作
来源：http://dali.aizwys.cn/Article/details/gthsulyzcm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gtzjetoyts.html

[U25] Py：CSV 按字典读
来源：http://dali.chenjidiqi.icu/Article/details/gtlkgjvtto.html

csv.DictReader(f)
来源：http://dali.yueranfly.top/Article/details/gteidsmbou.html

[U26] Py：并发下载
来源：http://dali.sweek.top/Article/details/gtngcxrola.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cashguo.top/Article/details/gtdmorgert.html

[U27] Py：异步 HTTP
来源：http://dali.jyoumei.cn/Article/details/gtxjaisxoe.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yonumen.top/Article/details/gtannrgasa.html

[U28] Py：类型别名
来源：http://dali.zhiwuduotai.top/Article/details/gtvnwtkipi.html

UserId = int
来源：http://dali.haohaochexian.top/Article/details/gtplbnieli.html

[U29] Py：属性校验
来源：http://dali.ppjwa.cn/Article/details/gtsucqvyog.html

@property 与 @x.setter 配合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwuxvbwx.html

[U30] Py：数据类
来源：http://dali.9152youxi.cn/Article/details/gtaelwuubc.html

@dataclass(slots=True)
来源：http://dali.quarkkingdee.top/Article/details/gtbxuxokzo.html

[U31] Py：单测
来源：http://dali.chenzaomai.com/Article/details/gtjsiqmwjp.html

python -m pytest -q
来源：http://dali.jinghuilouyu.cn/Article/details/gtwubqweit.html

[U32] Py：代码格式化
来源：http://dali.smart0.xyz/Article/details/gtvmooumak.html

ruff format . && ruff check --fix .
来源：http://dali.shangyingyoupin.top/Article/details/gtxdgrcevn.html

[U33] Py：打包发布
来源：http://dali.cucudq.cn/Article/details/gtniwclrxi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.daxiang520.top/Article/details/gtfzozhxed.html

[U34] Py：判断编码
来源：http://dali.ehwqpu.com/Article/details/gtlfbyvygg.html

chardet.detect(raw)
来源：http://dali.cucudq.cn/Article/details/gturkuyqzh.html

[U35] Py：发送邮件
来源：http://dali.pycfn.com/Article/details/gtacgxeabu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhiwuduotai.top/Article/details/gtfibsknaj.html

[U36] Py：定时任务
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpuutwfd.html

schedule.every(10).minutes.do(job)
来源：http://dali.pengpengdd.cyou/Article/details/gtrntrxjdk.html

[U37] Py：读写 Excel
来源：http://dali.cucudq.cn/Article/details/gtypjvfprp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.nanxinkj.top/Article/details/gtlqshllba.html

[U38] Py：获取脚本所在目录
来源：http://dali.guannengcc.top/Article/details/gtlnbikxsz.html

Path(__file__).resolve().parent
来源：http://dali.redwolf501.top/Article/details/gtpulfomiz.html

[U39] Py：判断是否在交互环境
来源：http://dali.fengsongda.top/Article/details/gtpeplsrxk.html

sys.stdout.isatty()
来源：http://dali.shzxlz.cn/Article/details/gtvgqvvipo.html

[U40] Py：打印到标准错误
来源：http://dali.svipenyu.cn/Article/details/gtgrvphvto.html

print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gtoxgupdzl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cashguo.top/Article/details/gtrjsgqses.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tianlin.xyz/Article/details/gtsjoqijab.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yvedp.cn/Article/details/gtaizqzwle.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.iojbl.cn/Article/details/gtfklumqay.html

[U43] PHP：声明命名空间
来源：http://dali.mhx1999.top/Article/details/gtrsnriytm.html

namespace App\Http;
来源：http://dali.yj20258.top/Article/details/gtxcrkwigb.html

[U44] PHP：开启严格类型
来源：http://dali.jyoumei.cn/Article/details/gtdagjkeon.html

declare(strict_types=1);
来源：http://dali.yuxming.cn/Article/details/gtydteyirl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yj20258888.top/Article/details/gtdbrneydh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwguynrp.html

[U46] PHP：可空类型
来源：http://dali.ivvv.top/Article/details/gtsxuzijfr.html

?string $name = null
来源：http://dali.sxryk.cn/Article/details/gtfgqntocy.html

[U47] PHP：联合类型
来源：http://dali.svipenyu.cn/Article/details/gtnrdvblat.html

int|string $id
来源：http://dali.pycfn.com/Article/details/gtjbgqjoan.html

[U48] PHP：纯枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtdprdgcdo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.c1oappe.top/Article/details/gtcdipaudq.html

[U49] PHP：只读属性
来源：http://dali.daria6918.cn/Article/details/gtkytmcojp.html

public readonly string $name
来源：http://dali.quarkkingdee.top/Article/details/gtwlplfrxu.html

[U50] PHP：构造器属性提升
来源：http://dali.smart0.xyz/Article/details/gtzrkeebye.html

public function __construct(private int $id) {}
来源：http://dali.cheryme.top/Article/details/gtzxtjgnmv.html

[U51] PHP：数组解构
来源：http://dali.zhiwuduotai.top/Article/details/gttgzynrin.html

[$a, $b] = $arr;
来源：http://dali.cucudq.cn/Article/details/gtqzyxskqw.html

[U52] PHP：箭头函数
来源：http://dali.316326.xyz/Article/details/gtkjmwjdtq.html

$double = fn($x) => $x * 2;
来源：http://dali.havefunace.top/Article/details/gtxqbajeye.html

[U53] PHP：空合并运算符
来源：http://dali.vqdsnc.cn/Article/details/gtttgcfoqg.html

$v = $a ?? $b ?? "default";
来源：http://dali.sysykeji.top/Article/details/gtmzcrjnby.html

[U54] PHP：空安全调用
来源：http://dali.jqgufenzy.top/Article/details/gtslpbgtio.html

$obj?->method()
来源：http://dali.ivvv.top/Article/details/gtcdcyvbuu.html

[U55] PHP：match 表达式
来源：http://dali.havefunace.top/Article/details/gtoahbnqle.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hysaishi.cn/Article/details/gtlutglzxp.html

[U56] PHP：命名参数
来源：http://dali.hammf.cn/Article/details/gtveatxiqm.html

f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gtsgylxlko.html

[U57] PHP：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyxuwalf.html

"值: {$a}"
来源：http://dali.hysaishi.cn/Article/details/gtfdixmval.html

[U58] PHP：数组三件套
来源：http://dali.zycfv.cn/Article/details/gtwonmwqhi.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtozeycoab.html

[U59] PHP：自定义排序
来源：http://dali.hysaishi.cn/Article/details/gteiogdhgy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zdqjudy.top/Article/details/gtyokxjfwg.html

[U60] PHP：JSON 编解码
来源：http://dali.jqgufenzy.top/Article/details/gtnuagvqpv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gogol.net.cn/Article/details/gtxhakwxgw.html

[U61] PHP：正则
来源：http://dali.yangfankeji.com/Article/details/gtrbvvgtmv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gtfkjyojsb.html

[U62] PHP：日期对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtkctrprsl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shzxlz.cn/Article/details/gtlnbdfjmv.html

[U63] PHP：文件读写
来源：http://dali.chenjidiqi.icu/Article/details/gtpylimcdf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yj202588.top/Article/details/gtrokczcxe.html

[U64] PHP：目录遍历
来源：http://dali.316326.xyz/Article/details/gtdxsypoqu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ybcxt.top/Article/details/gtosnbdeba.html

[U65] PHP：会话
来源：http://dali.gzhubu.top/Article/details/gtgbjivhjn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtsouvjcgj.html

[U66] PHP：设置 Cookie
来源：http://dali.haohaochexian.top/Article/details/gtnqbqvxup.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hnqzz.top/Article/details/gtzknlkcsf.html

[U67] PHP：处理文件上传
来源：http://dali.redwolf501.top/Article/details/gtvsmlaeba.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.bjfxy.top/Article/details/gtwueurtpz.html

[U68] PHP：PDO 连接
来源：http://dali.yvedp.cn/Article/details/gtodionjmx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.daria6918.cn/Article/details/gtqdideyno.html

[U69] PHP：PDO 预处理
来源：http://dali.ppjwa.cn/Article/details/gtkvzqfdai.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.iojbl.cn/Article/details/gtbaiznrzm.html

[U70] PHP：PDO 事务
来源：http://dali.jqgufenzy.top/Article/details/gtcowbutuf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.316326.xyz/Article/details/gteieeyzey.html

[U71] PHP：抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokqtnadl.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhongyouzk.top/Article/details/gtzzpwxaev.html

[U72] PHP：写错误日志
来源：http://dali.hammf.cn/Article/details/gtthtbnciq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.dashuyun.cn/Article/details/gtskortvgg.html

[U73] PHP：读取 ini 配置
来源：http://dali.yanxiufei.cn/Article/details/gtzmjzqtjo.html

parse_ini_file("config.ini", true)
来源：http://dali.snrcjt.cn/Article/details/gtemwufnpy.html

[U74] PHP：读取环境变量
来源：http://dali.xylfe.cn/Article/details/gtgxlxrdfp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cqqwz.cn/Article/details/gtwmvycczl.html

[U75] PHP：依赖注入
来源：http://dali.nanxuanxn.top/Article/details/gtltzquegv.html

composer require psr/container
来源：http://dali.yj202588.top/Article/details/gtcafievem.html

[U76] PHP：简单路由
来源：http://dali.chenjidiqi.icu/Article/details/gtdrqkiokv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yongpay.top/Article/details/gtrjrlmtpz.html

[U77] PHP：模板渲染
来源：http://dali.dianchejie.cn/Article/details/gtixxyhzum.html

composer require twig/twig
来源：http://dali.yangfankeji.com/Article/details/gtelxibbxo.html

[U78] PHP：单元测试
来源：http://dali.xinyue.icu/Article/details/gtybyroihs.html

composer require --dev phpunit/phpunit
来源：http://dali.shuidangran.top/Article/details/gtrfpacwix.html

[U79] PHP：静态分析
来源：http://dali.yvedp.cn/Article/details/gtjdsnfmqy.html

composer require --dev phpstan/phpstan
来源：http://dali.andypj.xyz/Article/details/gtumoqaebk.html

[U80] PHP：代码规范修复
来源：http://dali.guowangkeji.top/Article/details/gthbbhcjae.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.dianchejie.cn/Article/details/gtzjryquqz.html

[U81] JS：初始化项目
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsaozjlbf.html

npm init -y;  npm i express
来源：http://dali.pengpengdd.cyou/Article/details/gtdantqpyy.html

[U82] JS：package.json 脚本
来源：http://dali.chenlongwang.top/Article/details/gtxwrvvpzp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwsajkdw.html

[U83] JS：ES Module 导入导出
来源：http://dali.hongshengwenyu.top/Article/details/gtqdfgygys.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hysaishi.cn/Article/details/gtjvjndvlq.html

[U84] JS：CommonJS 写法
来源：http://dali.shanyushiyangtech.top/Article/details/gtjydhlhzc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.tian-w.cn/Article/details/gtybhkyqsg.html

[U85] JS：可选链
来源：http://dali.aibaodan.cn/Article/details/gtofhuzbdy.html

a?.b?.c
来源：http://dali.hongshengwenyu.top/Article/details/gtlhzcmdsh.html

[U86] JS：空值合并
来源：http://dali.yanxiufei.cn/Article/details/gtvxzjeogp.html

a ?? b
来源：http://dali.yuanzhike.top/Article/details/gtrbsnbkqc.html

[U87] JS：解构默认值
来源：http://dali.gzhubu.top/Article/details/gtzoncaycg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.nanxinkj.top/Article/details/gtdsojpwcw.html

[U88] JS：对象展开合并
来源：http://dali.jqgufenzy.top/Article/details/gtygklncgm.html

{ ...a, ...b }
来源：http://dali.aibaodan.cn/Article/details/gtpiyhebqj.html

[U89] JS：数组去重
来源：http://dali.hongshengwenyu.top/Article/details/gtvbtxltas.html

[...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gtugjholpo.html

[U90] JS：数字数组排序
来源：http://dali.feifeiyinyue.top/Article/details/gtjjrrvlwf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtnkhlemng.html

[U91] JS：对象键值遍历
来源：http://dali.jiagoushi.top/Article/details/gtkudkstgc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cdnleiting.top/Article/details/gtnekrzmyw.html

[U92] JS：深拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtwhalhllf.html

structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtgbxqzqmf.html

[U93] JS：模板字符串
来源：http://dali.jqgfzy.top/Article/details/gtmpgqokeu.html

`共 ${n} 条`
来源：http://dali.gaohongyu789.top/Article/details/gtaxxjxsti.html

[U94] JS：箭头函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulwhmqyk.html

const double = x => x * 2;
来源：http://dali.sysykeji.top/Article/details/gtcywbyvuq.html

[U95] JS：Promise 包装
来源：http://dali.tian-w.cn/Article/details/gtanuwqylm.html

new Promise((resolve, reject) => {})
来源：http://dali.daxiang520.top/Article/details/gtepfmlqoq.html

[U96] JS：async/await 与异常
来源：http://dali.dianchejie.cn/Article/details/gtddjukqmq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gtsuljrhgc.html

[U97] JS：并发请求
来源：http://dali.ybcxt.top/Article/details/gtwmnjhwap.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gtvhgmbmuc.html

[U98] JS：fetch 带 JSON
来源：http://dali.dianchejie.cn/Article/details/gtlokblpir.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.ppjwa.cn/Article/details/gtuptokcby.html

[U99] JS：事件监听
来源：http://dali.yongpay.top/Article/details/gthhdnknhd.html

el.addEventListener("click", e => {})
来源：http://dali.hongshengwenyu.top/Article/details/gtwrvnbjja.html

[U100] JS：DOM 查询
来源：http://dali.zhongyouzk.top/Article/details/gtudwrexkk.html

document.querySelector(".item")
来源：http://dali.nwbrower.top/Article/details/gtbgsdacja.html

[U101] JS：classList 操作
来源：http://dali.chenjidiqi.icu/Article/details/gtzffhdbga.html

el.classList.toggle("active")
来源：http://dali.wangdashe.top/Article/details/gtdcuuiwwm.html

[U102] JS：本地存储
来源：http://dali.tian-w.cn/Article/details/gtygwtsfbp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xylfe.cn/Article/details/gtyomixjqv.html

[U103] JS：定时器
来源：http://dali.jlsjyb.cn/Article/details/gtlaoyzyqm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yuxming.cn/Article/details/gtcgocsaim.html

[U104] JS：防抖
来源：http://dali.xziqi.cn/Article/details/gtmyivopcl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztzzkkbm.html

[U105] JS：节流
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgseacaj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhengqikj.top/Article/details/gtowxhyxao.html

[U106] JS：日期格式化
来源：http://dali.mhx1999.top/Article/details/gtvtpxjftt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenjidiqi.icu/Article/details/gthefjglhg.html

[U107] JS：数字千分位
来源：http://dali.jinqigufen.top/Article/details/gtjufhgagq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gthxkxmbaj.html

[U108] JS：随机整数
来源：http://dali.jqgufenzy.top/Article/details/gtivlbrsvl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.aibaodan.cn/Article/details/gtgkfxwahe.html

[U109] JS：数组分组
来源：http://dali.9152youxi.cn/Article/details/gtuwtzophn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yvedp.cn/Article/details/gtvyqhhuez.html

[U110] JS：数组分块
来源：http://dali.cdnleiting.top/Article/details/gtuqqkkfdv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuanzhike.top/Article/details/gttqnkdhnr.html

[U111] JS：对象转 Map
来源：http://dali.pengpengdd.cyou/Article/details/gttdodllwn.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gtobttdaks.html

[U112] JS：字符串补位
来源：http://dali.zhongyouzk.top/Article/details/gtqqbhxflx.html

"7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtqpxwtmsx.html

[U113] JS：正则替换全部
来源：http://dali.dashuyun.cn/Article/details/gtxmrpxxnx.html

s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtnnuchitw.html

[U114] JS：JSON 深比较
来源：http://dali.zdqjudy.top/Article/details/gtnkycmsdx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarolaiib.html

[U115] JS：生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gtvataditl.html

crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtsarxrvbn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.birdmap.top/Article/details/gtxduhihap.html

/** @param {string} name */ function f(name) {}
来源：http://dali.c1oappe.top/Article/details/gtuddwoedi.html

[U117] JS：单元测试
来源：http://dali.shzxlz.cn/Article/details/gtooxlkpzn.html

npm i -D vitest;  npx vitest
来源：http://dali.aibaodan.cn/Article/details/gtubghtmky.html

[U118] JS：开发服务器
来源：http://dali.chenzaomai.com/Article/details/gtrimuqccd.html

npm i -D vite;  npx vite
来源：http://dali.havefunace.top/Article/details/gtpdhkszsm.html

[U119] JS：生产构建
来源：http://dali.0kj1m.cn/Article/details/gtfswcmqsn.html

npx vite build
来源：http://dali.aibaodan.cn/Article/details/gtppobpysk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shzxlz.cn/Article/details/gtyjswxsly.html

import.meta.env.VITE_API_URL
来源：http://dali.jyoumei.cn/Article/details/gtobbpwwvk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtosvzbnob.html

统计汇总
来源：http://dali.hnxiangtu.top/Article/details/gtgfminwqx.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gturdlkhsz.html

按语言统计（条）：
来源：http://dali.dashuyun.cn/Article/details/gtyomgmyva.html

Python ......... 252
来源：http://dali.aibaodan.cn/Article/details/gtrgamrvgc.html

PHP ............ 252
来源：http://dali.yuxming.cn/Article/details/gtzvesqstd.html

JavaScript ..... 252
来源：http://dali.yueranfly.top/Article/details/gtoaderwlj.html

TypeScript ..... 212
来源：http://dali.vqdsnc.cn/Article/details/gtzdrhdpna.html

Java ........... 212
来源：http://dali.gotoacloud.top/Article/details/gttvkioivv.html

Go ............. 212
来源：http://dali.ydzc1.top/Article/details/gtmtqseweg.html

Ruby ........... 212
来源：http://dali.mhx1999.top/Article/details/gtqbystzaw.html

C# ............. 212
来源：http://dali.pengpengdd.cyou/Article/details/gtvskqckgd.html

C .............. 30
来源：http://dali.jlsjyb.cn/Article/details/gtcaxdhwqq.html

C++ ............ 30
来源：http://dali.zhengqikj.top/Article/details/gtrdmsippe.html

SQL ............ 90
来源：http://dali.jqgufenzy.top/Article/details/gtdhqjjcyy.html

Bash ........... 80
来源：http://dali.jqgufenzy.top/Article/details/gtdtdtbwdb.html

Kotlin ......... 15
来源：http://dali.zdqjudy.top/Article/details/gtclxotnbz.html

Swift .......... 15
来源：http://dali.birdmap.top/Article/details/gtgciwpaex.html

Lua ............ 10
来源：http://dali.shuidangran.top/Article/details/gtsdsjzfke.html

Perl ........... 10
来源：http://dali.dianchejie.cn/Article/details/gticehdyfn.html

Scala .......... 10
来源：http://dali.zhongyouzk.top/Article/details/gtzirvcwjh.html

------------------------------------
来源：http://dali.cheryme.top/Article/details/gtjwsbhqts.html

合计 ........... 2106 条
来源：http://dali.cucudq.cn/Article/details/gtlmhkyysv.html

按章节统计：
来源：http://dali.jqgfzy.top/Article/details/gtdyxuxxgw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xuanzx.com/Article/details/gtzqiivlzr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hongshengwenyu.top/Article/details/gtnohuqzaf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhongyouzk.top/Article/details/gtbfmnpfca.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jyoumei.cn/Article/details/gtdpfrujfa.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.svipenyu.cn/Article/details/gtfxawmexw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hywenlv.cn/Article/details/gtjlttdcaf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ydzc1.top/Article/details/gtgxdltwzd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.dianchejie.cn/Article/details/gtuyoxozyj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtadvkcyhk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangtech.top/Article/details/gtzslccumb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gtyorknzrj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gtucvhjfzs.html


<!-- 参考信息 -->