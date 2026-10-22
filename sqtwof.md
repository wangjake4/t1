代发 wailian999

val a = 1;  var b = 2
来源：http://dali.jyoumei.cn/Article/details/gt2xcnipqcs.html

[T53] Scala：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gt2ystguben.html

s"值: $b"
来源：http://dali.yonumen.top/Article/details/gt2jyovwfel.html

[T54] Scala：集合映射
来源：http://dali.zhixingplan.top/Article/details/gt2gvacplij.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yonumen.top/Article/details/gt2fuskksky.html

[T55] Scala：集合过滤
来源：http://dali.bjfxy.top/Article/details/gt2iqfnlsuc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uliujzec.html

[T56] Scala：样例类
来源：http://dali.zhiwuduotai.top/Article/details/gt2chllimkp.html

case class User(name: String, age: Int)
来源：http://dali.ehwqpu.com/Article/details/gt2hrqstcob.html

[T57] Scala：模式匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2yfpdcdsv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dbmsxmyd.html

[T58] Scala：函数定义
来源：http://dali.zhixingplan.top/Article/details/gt2umdtqbpv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yonumen.top/Article/details/gt2rcblszls.html

[T59] Scala：循环
来源：http://dali.jqgfzy.top/Article/details/gt2jnskbley.html

for (i <- 1 to 10) println(i)
来源：http://dali.smart0.xyz/Article/details/gt2fcdkvffp.html

[T60] Scala：折叠
来源：http://dali.havefunace.top/Article/details/gt2qmrxexns.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuanzx.com/Article/details/gt2qmuhkfzf.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2dchcrwoh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.haohaochexian.top/Article/details/gt2qiiwjhvy.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ycroralr.html

[U01] Py：创建虚拟环境
来源：http://dali.sweek.top/Article/details/gt2itpxgril.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jiagoushi.top/Article/details/gt2anqjnqff.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj20258.top/Article/details/gt2rqfocsxr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yangfankeji.com/Article/details/gt2nrxobuif.html

[U03] Py：加载 .env 配置
来源：http://dali.zhixingplan.top/Article/details/gt2wyfxqeoy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinqigfzy.top/Article/details/gt2luqktqyx.html

[U04] Py：变量调试打印
来源：http://dali.tian-w.cn/Article/details/gt2wthqifdd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hfpthk.cn/Article/details/gt2lcrumrvc.html

[U05] Py：列表去重且保序
来源：http://dali.jqgfzy.top/Article/details/gt2hjklslue.html

list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gt2bastynxz.html

[U06] Py：合并两个字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mhjyqkpg.html

{**a, **b}
来源：http://dali.svipenyu.cn/Article/details/gt2olugngfo.html

[U07] Py：反转字典键值
来源：http://dali.xinyue.icu/Article/details/gt2psobawvy.html

{v: k for k, v in d.items()}
来源：http://dali.shangyingyoupin.top/Article/details/gt2znnxlozt.html

[U08] Py：展平二维列表
来源：http://dali.jinqigufen.top/Article/details/gt2hsgufpnj.html

[y for x in nested for y in x]
来源：http://dali.jqgufenzy.top/Article/details/gt2iepejjah.html

[U09] Py：字典取最大值的键
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cjvwmict.html

max(d, key=d.get)
来源：http://dali.zycfv.cn/Article/details/gt2oluhcmhe.html

[U10] Py：按值排序字典
来源：http://dali.cucudq.cn/Article/details/gt2nsmexpiz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2unirvvqt.html

[U11] Py：生成器表达式
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqmhugat.html

(x * 2 for x in arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ayykywha.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.316326.xyz/Article/details/gt2tpocslfe.html

Counter(arr).most_common(3)
来源：http://dali.yonumen.top/Article/details/gt2sfatxhuk.html

[U13] Py：固定长度队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wvobgwqc.html

deque(maxlen=10)
来源：http://dali.bjfxy.top/Article/details/gt2yidrfdxt.html

[U14] Py：分组收集到列表
来源：http://dali.mhx1999.top/Article/details/gt2taeptqta.html

defaultdict(list)
来源：http://dali.chenzaomai.com/Article/details/gt2nsfsyuwv.html

[U15] Py：高精度计时
来源：http://dali.jqgufenzy.top/Article/details/gt2ilxtynkr.html

t = time.perf_counter()
来源：http://dali.kuanghao11.cn/Article/details/gt2suxpsnvs.html

[U16] Py：命令行参数解析
来源：http://dali.yanxiufei.cn/Article/details/gt2ngxxxqaw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jyoumei.cn/Article/details/gt2fccrvyfa.html

[U17] Py：初始化日志
来源：http://dali.9152youxi.cn/Article/details/gt2icvzsvku.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yueranfly.top/Article/details/gt2pgfwtngp.html

[U18] Py：预编译正则
来源：http://dali.chenlongwang.top/Article/details/gt2zlegmamq.html

pat = re.compile(r"\d+")
来源：http://dali.ybcxt.top/Article/details/gt2pbletaht.html

[U19] Py：正则替换带回调
来源：http://dali.dianchejie.cn/Article/details/gt2rknhalod.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yanxiufei.cn/Article/details/gt2oczjiqrq.html

[U20] Py：缓存函数结果
来源：http://dali.0kj1m.cn/Article/details/gt2rtercauw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ivvv.top/Article/details/gt2ovvsvxco.html

[U21] Py：自定义上下文管理器
来源：http://dali.ivvv.top/Article/details/gt2gootydmy.html

@contextlib.contextmanager
来源：http://dali.chenzaomai.com/Article/details/gt2eouvlbcv.html

[U22] Py：矩阵转置
来源：http://dali.jqgfzy.top/Article/details/gt2ntpeltfc.html

list(zip(*m))
来源：http://dali.zhongyouzk.top/Article/details/gt2epaqaxfa.html

[U23] Py：分块读取大文件
来源：http://dali.andypj.xyz/Article/details/gt2nvkxuqcn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.iojbl.cn/Article/details/gt2fazpdsva.html

[U24] Py：路径操作
来源：http://dali.birdmap.top/Article/details/gt2zsbvigqv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ivvv.top/Article/details/gt2rqwugktq.html

[U25] Py：CSV 按字典读
来源：http://dali.xuetiantiany.cn/Article/details/gt2omzmahvk.html

csv.DictReader(f)
来源：http://dali.nanxinkj.top/Article/details/gt2mzizvhaz.html

[U26] Py：并发下载
来源：http://dali.xuanzx.com/Article/details/gt2ndszxknh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.vqdsnc.cn/Article/details/gt2ypmsqocb.html

[U27] Py：异步 HTTP
来源：http://dali.quarkkingdee.top/Article/details/gt2bzrefokq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuxming.cn/Article/details/gt2uetmsyix.html

[U28] Py：类型别名
来源：http://dali.316326.xyz/Article/details/gt2gxkqdldt.html

UserId = int
来源：http://dali.jqgfzy.top/Article/details/gt2trbxirje.html

[U29] Py：属性校验
来源：http://dali.yuanzhike.top/Article/details/gt2gbrimrdr.html

@property 与 @x.setter 配合
来源：http://dali.dianchejie.cn/Article/details/gt2cjjggjrl.html

[U30] Py：数据类
来源：http://dali.svipenyu.cn/Article/details/gt2nalldyrz.html

@dataclass(slots=True)
来源：http://dali.yongpay.top/Article/details/gt2pyinkdth.html

[U31] Py：单测
来源：http://dali.ppjwa.cn/Article/details/gt2jrpxqtyw.html

python -m pytest -q
来源：http://dali.kuanghao11.cn/Article/details/gt2sxkillsh.html

[U32] Py：代码格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ovtgdruo.html

ruff format . && ruff check --fix .
来源：http://dali.havefunace.top/Article/details/gt2vwkwsafi.html

[U33] Py：打包发布
来源：http://dali.gzhubu.top/Article/details/gt2fdbndufs.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cashguo.top/Article/details/gt2edexlqco.html

[U34] Py：判断编码
来源：http://dali.haohaochexian.top/Article/details/gt2bejsvpzy.html

chardet.detect(raw)
来源：http://dali.guannengcc.top/Article/details/gt2nhdqrepu.html

[U35] Py：发送邮件
来源：http://dali.yongpay.top/Article/details/gt2pmufevff.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gogol.net.cn/Article/details/gt2xpavhcyr.html

[U36] Py：定时任务
来源：http://dali.gaohongyu789.top/Article/details/gt2hhswhpxw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zycfv.cn/Article/details/gt2podkxthb.html

[U37] Py：读写 Excel
来源：http://dali.aibaodan.cn/Article/details/gt2yklwaiyb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ifblfftx.html

[U38] Py：获取脚本所在目录
来源：http://dali.sxryk.cn/Article/details/gt2qmikdrwr.html

Path(__file__).resolve().parent
来源：http://dali.zhiwuduotai.top/Article/details/gt2tjpogsnf.html

[U39] Py：判断是否在交互环境
来源：http://dali.yuanzhike.top/Article/details/gt2rnvdcwod.html

sys.stdout.isatty()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ocakvfya.html

[U40] Py：打印到标准错误
来源：http://dali.gzhubu.top/Article/details/gt2cncdehdt.html

print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gt2vezrbbrl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kcbxaixq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinqigufen.top/Article/details/gt2fvpicyck.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xylfe.cn/Article/details/gt2pqlxvqdv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yanxiufei.cn/Article/details/gt2wqxhldxj.html

[U43] PHP：声明命名空间
来源：http://dali.cqqwz.cn/Article/details/gt2okxqsyxh.html

namespace App\Http;
来源：http://dali.shuidangran.top/Article/details/gt2isggtfhg.html

[U44] PHP：开启严格类型
来源：http://dali.pycfn.com/Article/details/gt2pouaocpz.html

declare(strict_types=1);
来源：http://dali.zhixingplan.top/Article/details/gt2rlglttzo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ppjwa.cn/Article/details/gt2wtgghcqv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gt2mllzjrgh.html

[U46] PHP：可空类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2davgtcwj.html

?string $name = null
来源：http://dali.tanke756.top/Article/details/gt2rgkvpcwb.html

[U47] PHP：联合类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ermkxesv.html

int|string $id
来源：http://dali.guowangkeji.top/Article/details/gt2qrxgoyfr.html

[U48] PHP：纯枚举
来源：http://dali.fengsongda.top/Article/details/gt2abwtggxk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2dlblbwrv.html

[U49] PHP：只读属性
来源：http://dali.cucudq.cn/Article/details/gt2yltfnrep.html

public readonly string $name
来源：http://dali.xuanzx.com/Article/details/gt2livbbefv.html

[U50] PHP：构造器属性提升
来源：http://dali.gaohongyu789.top/Article/details/gt2phjuqdwm.html

public function __construct(private int $id) {}
来源：http://dali.hnqzz.top/Article/details/gt2akxpdcdt.html

[U51] PHP：数组解构
来源：http://dali.ydzc1.top/Article/details/gt2etwzuaoc.html

[$a, $b] = $arr;
来源：http://dali.yuanzhike.top/Article/details/gt2ygfjgxrn.html

[U52] PHP：箭头函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cezjecey.html

$double = fn($x) => $x * 2;
来源：http://dali.jinqigufen.top/Article/details/gt2przjgoxj.html

[U53] PHP：空合并运算符
来源：http://dali.havefunace.top/Article/details/gt2shvjmrkj.html

$v = $a ?? $b ?? "default";
来源：http://dali.shuidangran.top/Article/details/gt2thefyhvc.html

[U54] PHP：空安全调用
来源：http://dali.zhoulong.xyz/Article/details/gt2drpnthye.html

$obj?->method()
来源：http://dali.dashuyun.cn/Article/details/gt2xcmrxjbj.html

[U55] PHP：match 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxsybzze.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.wangdashe.top/Article/details/gt2wsttclev.html

[U56] PHP：命名参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vvrwptoy.html

f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cwuxuqde.html

[U57] PHP：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gt2icaytqbb.html

"值: {$a}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2xstquxfm.html

[U58] PHP：数组三件套
来源：http://dali.jlsjyb.cn/Article/details/gt2zogxpevk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2xrucxhaq.html

[U59] PHP：自定义排序
来源：http://dali.bjfxy.top/Article/details/gt2luiaxxbq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gt2knrkjhmt.html

[U60] PHP：JSON 编解码
来源：http://dali.chenzaomai.com/Article/details/gt2jujrhbbm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ydzc1.top/Article/details/gt2dmwstaxe.html

[U61] PHP：正则
来源：http://dali.c1oappe.top/Article/details/gt2oopkahdc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2jmkdybjt.html

[U62] PHP：日期对象
来源：http://dali.jyoumei.cn/Article/details/gt2eeewvsjt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ybcxt.top/Article/details/gt2lpirrdww.html

[U63] PHP：文件读写
来源：http://dali.xuanzx.com/Article/details/gt2zamhvvgn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.chenzaomai.com/Article/details/gt2syigzujf.html

[U64] PHP：目录遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2vxgbdubl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpeaspp.html

[U65] PHP：会话
来源：http://dali.yj202588.top/Article/details/gt2qqnbnxwz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj202588.top/Article/details/gt2tcfrdjga.html

[U66] PHP：设置 Cookie
来源：http://dali.chenzaomai.com/Article/details/gt2lriyjlyk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.chenlongwang.top/Article/details/gt2grkhtlbl.html

[U67] PHP：处理文件上传
来源：http://dali.jqgfzy.top/Article/details/gt2qxoqcoeu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hnqzz.top/Article/details/gt2wpazfuro.html

[U68] PHP：PDO 连接
来源：http://dali.fzhhl.top/Article/details/gt2dtqwtwzb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.316326.xyz/Article/details/gt2wewjobpu.html

[U69] PHP：PDO 预处理
来源：http://dali.zdqjudy.top/Article/details/gt2aqdjdiik.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhongyouzk.top/Article/details/gt2afnbbatg.html

[U70] PHP：PDO 事务
来源：http://dali.birdmap.top/Article/details/gt2vpepjtlc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yj202588.top/Article/details/gt2vxdgypeg.html

[U71] PHP：抛出异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2npfiuusr.html

throw new RuntimeException("失败", 500);
来源：http://dali.cheryme.top/Article/details/gt2rrivywvh.html

[U72] PHP：写错误日志
来源：http://dali.xylfe.cn/Article/details/gt2ohscqwhx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.c1oappe.top/Article/details/gt2ufbuohxg.html

[U73] PHP：读取 ini 配置
来源：http://dali.hnqzz.top/Article/details/gt2robntmzw.html

parse_ini_file("config.ini", true)
来源：http://dali.hongshengwenyu.top/Article/details/gt2efmfvxtm.html

[U74] PHP：读取环境变量
来源：http://dali.haohaochexian.top/Article/details/gt2eeaqxatx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jyoumei.cn/Article/details/gt2ckluzxiz.html

[U75] PHP：依赖注入
来源：http://dali.jyoumei.cn/Article/details/gt2oiqyawog.html

composer require psr/container
来源：http://dali.feifeiyinyue.top/Article/details/gt2vdtpatqc.html

[U76] PHP：简单路由
来源：http://dali.316326.xyz/Article/details/gt2qyvzrcru.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.aibaodan.cn/Article/details/gt2kzvbznro.html

[U77] PHP：模板渲染
来源：http://dali.shangyingyoupin.top/Article/details/gt2ezkyfiyd.html

composer require twig/twig
来源：http://dali.gogol.net.cn/Article/details/gt2ahxfxofb.html

[U78] PHP：单元测试
来源：http://dali.yuanzhike.top/Article/details/gt2orjpwyee.html

composer require --dev phpunit/phpunit
来源：http://dali.yongpay.top/Article/details/gt2mwzbwost.html

[U79] PHP：静态分析
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmzftwye.html

composer require --dev phpstan/phpstan
来源：http://dali.ivvv.top/Article/details/gt2sdcqoaax.html

[U80] PHP：代码规范修复
来源：http://dali.hnqzz.top/Article/details/gt2tdnffvww.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.gotoacloud.top/Article/details/gt2pajwxbmy.html

[U81] JS：初始化项目
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iolelhtj.html

npm init -y;  npm i express
来源：http://dali.aibaodan.cn/Article/details/gt2kdzqyuhr.html

[U82] JS：package.json 脚本
来源：http://dali.hysaishi.cn/Article/details/gt2jlqswjuu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.316326.xyz/Article/details/gt2lhextegs.html

[U83] JS：ES Module 导入导出
来源：http://dali.ydzc1.top/Article/details/gt2midyeliq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.wangdashe.top/Article/details/gt2szulvjwv.html

[U84] JS：CommonJS 写法
来源：http://dali.zdqjudy.top/Article/details/gt2qmhdxlry.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shuidangran.top/Article/details/gt2znpywpga.html

[U85] JS：可选链
来源：http://dali.c1oappe.top/Article/details/gt2eqegkvtd.html

a?.b?.c
来源：http://dali.birdmap.top/Article/details/gt2anirciqd.html

[U86] JS：空值合并
来源：http://dali.cdnleiting.top/Article/details/gt2hvcbemgg.html

a ?? b
来源：http://dali.nanxuanxn.top/Article/details/gt2poxbtxbu.html

[U87] JS：解构默认值
来源：http://dali.sufxvd.cn/Article/details/gt2plomlphu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xuanzx.com/Article/details/gt2idzysgvs.html

[U88] JS：对象展开合并
来源：http://dali.feifeiyinyue.top/Article/details/gt2qebdqdrt.html

{ ...a, ...b }
来源：http://dali.cqqwz.cn/Article/details/gt2vfsnecgo.html

[U89] JS：数组去重
来源：http://dali.jlsjyb.cn/Article/details/gt2pseoaios.html

[...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2gfbfwdqs.html

[U90] JS：数字数组排序
来源：http://dali.sysykeji.top/Article/details/gt2wzfbmezi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gt2sbkejifd.html

[U91] JS：对象键值遍历
来源：http://dali.cdnleiting.top/Article/details/gt2hcactdmq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yanxiufei.cn/Article/details/gt2uudbwlzf.html

[U92] JS：深拷贝
来源：http://dali.zhengqikj.top/Article/details/gt2cyzzkyqk.html

structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gt2pxlyukru.html

[U93] JS：模板字符串
来源：http://dali.tanke756.top/Article/details/gt2azdrwdjx.html

`共 ${n} 条`
来源：http://dali.sweek.top/Article/details/gt2yqtappev.html

[U94] JS：箭头函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adcutrfj.html

const double = x => x * 2;
来源：http://dali.zycfv.cn/Article/details/gt2wgiylxar.html

[U95] JS：Promise 包装
来源：http://dali.jiagoushi.top/Article/details/gt2bfoanrjw.html

new Promise((resolve, reject) => {})
来源：http://dali.cashguo.top/Article/details/gt2yepjdtmd.html

[U96] JS：async/await 与异常
来源：http://dali.haohaochexian.top/Article/details/gt2lhvozwuj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gt2cjvbbycu.html

[U97] JS：并发请求
来源：http://dali.jqgfzy.top/Article/details/gt2cviimozt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2cvcorfcg.html

[U98] JS：fetch 带 JSON
来源：http://dali.haohaochexian.top/Article/details/gt2yzinwekh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.bjfxy.top/Article/details/gt2stjviato.html

[U99] JS：事件监听
来源：http://dali.yonumen.top/Article/details/gt2vigjzhbw.html

el.addEventListener("click", e => {})
来源：http://dali.pycfn.com/Article/details/gt2igwyphrj.html

[U100] JS：DOM 查询
来源：http://dali.yongpay.top/Article/details/gt2qqvpcqhk.html

document.querySelector(".item")
来源：http://dali.chenlongwang.top/Article/details/gt2kuetcvdq.html

[U101] JS：classList 操作
来源：http://dali.cucudq.cn/Article/details/gt2kmpkqbqm.html

el.classList.toggle("active")
来源：http://dali.meibo888.top/Article/details/gt2amkkoxgl.html

[U102] JS：本地存储
来源：http://dali.svipenyu.cn/Article/details/gt2ordqaqnn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nanxinkj.top/Article/details/gt2rhxboywv.html

[U103] JS：定时器
来源：http://dali.feifeiyinyue.top/Article/details/gt2fgqfbtsp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yonumen.top/Article/details/gt2zxaosica.html

[U104] JS：防抖
来源：http://dali.havefunace.top/Article/details/gt2sbejkdpy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gt2juoxonxc.html

[U105] JS：节流
来源：http://dali.ybcxt.top/Article/details/gt2rdrrcoyu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenlongwang.top/Article/details/gt2lyqennqe.html

[U106] JS：日期格式化
来源：http://dali.meibo888.top/Article/details/gt2xtqvqrph.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.vqdsnc.cn/Article/details/gt2beoolfoz.html

[U107] JS：数字千分位
来源：http://dali.daria6918.cn/Article/details/gt2djwgyymi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.smart0.xyz/Article/details/gt2aogcaaxs.html

[U108] JS：随机整数
来源：http://dali.hnxiangtu.top/Article/details/gt2yjrguits.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ppjwa.cn/Article/details/gt2nmkrnhtp.html

[U109] JS：数组分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2ljpthgtn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.9152youxi.cn/Article/details/gt2taqkrzns.html

[U110] JS：数组分块
来源：http://dali.hfpthk.cn/Article/details/gt2zrvcmsfh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.wangdashe.top/Article/details/gt2vbwcgnea.html

[U111] JS：对象转 Map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oixsfuja.html

new Map(Object.entries(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gt2qfrazapp.html

[U112] JS：字符串补位
来源：http://dali.yuxming.cn/Article/details/gt2yvykegbj.html

"7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gt2xyodhtmu.html

[U113] JS：正则替换全部
来源：http://dali.andypj.xyz/Article/details/gt2olveryyj.html

s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2nqlzresb.html

[U114] JS：JSON 深比较
来源：http://dali.daria6918.cn/Article/details/gt2ihthylnn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.svipenyu.cn/Article/details/gt2mjpslose.html

[U115] JS：生成 UUID
来源：http://dali.cucudq.cn/Article/details/gt2yeysivuv.html

crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gt2btrjghgg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.kuanghao11.cn/Article/details/gt2anmixyog.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hfpthk.cn/Article/details/gt2gbzxkkwp.html

[U117] JS：单元测试
来源：http://dali.jyoumei.cn/Article/details/gt2ftoinxga.html

npm i -D vitest;  npx vitest
来源：http://dali.svipenyu.cn/Article/details/gt2phxockrx.html

[U118] JS：开发服务器
来源：http://dali.hongshengwenyu.top/Article/details/gt2oaplgnkp.html

npm i -D vite;  npx vite
来源：http://dali.yanxiufei.cn/Article/details/gt2septypov.html

[U119] JS：生产构建
来源：http://dali.ybcxt.top/Article/details/gt2rpsywqbs.html

npx vite build
来源：http://dali.dianchejie.cn/Article/details/gt2ejroqmwm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.svipenyu.cn/Article/details/gt2iosshkbc.html

import.meta.env.VITE_API_URL
来源：http://dali.sufxvd.cn/Article/details/gt2ezbtwzpq.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2owfdskwk.html

统计汇总
来源：http://dali.jianghu66.top/Article/details/gt2lancdpqb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ddrkwjmt.html

按语言统计（条）：
来源：http://dali.andypj.xyz/Article/details/gt2pkozznty.html

Python ......... 252
来源：http://dali.gzhubu.top/Article/details/gt2coqsimoa.html

PHP ............ 252
来源：http://dali.fzhhl.top/Article/details/gt2ycupflns.html

JavaScript ..... 252
来源：http://dali.mhx1999.top/Article/details/gt2ekgpigjn.html

TypeScript ..... 212
来源：http://dali.0kj1m.cn/Article/details/gt2sdfejfvx.html

Java ........... 212
来源：http://dali.xuanzx.com/Article/details/gt2ugmbmwlp.html

Go ............. 212
来源：http://dali.c1oappe.top/Article/details/gt2ofhyomny.html

Ruby ........... 212
来源：http://dali.zdqjudy.top/Article/details/gt2osrvxozo.html

C# ............. 212
来源：http://dali.sweek.top/Article/details/gt2ysyqalga.html

C .............. 30
来源：http://dali.yj202588.top/Article/details/gt2wxenikhe.html

C++ ............ 30
来源：http://dali.jqgufenzy.top/Article/details/gt2cjktfspa.html

SQL ............ 90
来源：http://dali.hywenlv.cn/Article/details/gt2zwnmkcvb.html

Bash ........... 80
来源：http://dali.ybcxt.top/Article/details/gt2efnclose.html

Kotlin ......... 15
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hamelujb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxrahbm.html

Lua ............ 10
来源：http://dali.xuanzx.com/Article/details/gt2wytaotfl.html

Perl ........... 10
来源：http://dali.yj202588.top/Article/details/gt2pleiuuee.html

Scala .......... 10
来源：http://dali.gaohongyu789.top/Article/details/gt2uototqzy.html

------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wobbsftd.html

合计 ........... 2106 条
来源：http://dali.daria6918.cn/Article/details/gt2owbtkodq.html

按章节统计：
来源：http://dali.gotoacloud.top/Article/details/gt2qeywbwwh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhixingplan.top/Article/details/gt2bqyvirls.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sgyeglxr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhoulong.xyz/Article/details/gt2tstnnyku.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.dianchejie.cn/Article/details/gt2traqjvtm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jqgfzy.top/Article/details/gt2ycteikvq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.redwolf501.top/Article/details/gt2iamowjsl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.smart0.xyz/Article/details/gt2thgqcwfv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zycfv.cn/Article/details/gt2hhkwwppn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gt2qeimccgw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shzxlz.cn/Article/details/gt2qstjiyag.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gt2dkmrhwms.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gt2ivkhbmnk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gt2qocbfgcg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shzxlz.cn/Article/details/gt2mrmfttev.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ppjwa.cn/Article/details/gt2oodvolhx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gt2yslsoqtx.html


<!-- 参考信息 -->