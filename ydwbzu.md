代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnasbzfx.html

[T59] Scala：循环
来源：http://dali.pengpengdd.cyou/Article/details/gtsvwyadrd.html

for (i <- 1 to 10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsinwqpq.html

[T60] Scala：折叠
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqschqrm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xziqi.cn/Article/details/gtbwwqwrcz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtnjarorqq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtcqrkmoak.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtzkcqclkg.html

[U01] Py：创建虚拟环境
来源：http://dali.havefunace.top/Article/details/gtvamezyqj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sufxvd.cn/Article/details/gtyryoismv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tian-w.cn/Article/details/gtagijjyjt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.meibo888.top/Article/details/gtwgjkopjk.html

[U03] Py：加载 .env 配置
来源：http://dali.yj202588.top/Article/details/gtvhygxoxm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.fzhhl.top/Article/details/gtyketejpc.html

[U04] Py：变量调试打印
来源：http://dali.cdnleiting.top/Article/details/gtzewzxrfs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.dianchejie.cn/Article/details/gttgqnurzk.html

[U05] Py：列表去重且保序
来源：http://dali.ppjwa.cn/Article/details/gtlrkhesgd.html

list(dict.fromkeys(arr))
来源：http://dali.fengsongda.top/Article/details/gthfcewsef.html

[U06] Py：合并两个字典
来源：http://dali.xinyue.icu/Article/details/gtbtuexfua.html

{**a, **b}
来源：http://dali.0kj1m.cn/Article/details/gttlnhxpdz.html

[U07] Py：反转字典键值
来源：http://dali.shangyingyoupin.top/Article/details/gtmawuhyoq.html

{v: k for k, v in d.items()}
来源：http://dali.chenzaomai.com/Article/details/gtpxhorsxl.html

[U08] Py：展平二维列表
来源：http://dali.chenzaomai.com/Article/details/gtlxtqkjak.html

[y for x in nested for y in x]
来源：http://dali.wangdashe.top/Article/details/gthuxsuqgp.html

[U09] Py：字典取最大值的键
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxbeuang.html

max(d, key=d.get)
来源：http://dali.hysaishi.cn/Article/details/gtwnkccsiv.html

[U10] Py：按值排序字典
来源：http://dali.daria6918.cn/Article/details/gtkrwecuvl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhiwuduotai.top/Article/details/gtyetsnyqk.html

[U11] Py：生成器表达式
来源：http://dali.xylfe.cn/Article/details/gtsyzegscu.html

(x * 2 for x in arr)
来源：http://dali.cashguo.top/Article/details/gtcossglde.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.quarkkingdee.top/Article/details/gtzuzsshzj.html

Counter(arr).most_common(3)
来源：http://dali.jianghu66.top/Article/details/gtcrasmqkg.html

[U13] Py：固定长度队列
来源：http://dali.cucudq.cn/Article/details/gtwhsunpkl.html

deque(maxlen=10)
来源：http://dali.jiagoushi.top/Article/details/gtsbpzvtgc.html

[U14] Py：分组收集到列表
来源：http://dali.fzhhl.top/Article/details/gtojrnqcry.html

defaultdict(list)
来源：http://dali.wangdashe.top/Article/details/gtuemcrbyg.html

[U15] Py：高精度计时
来源：http://dali.birdmap.top/Article/details/gtqqmdbwww.html

t = time.perf_counter()
来源：http://dali.redwolf501.top/Article/details/gtxjilxouw.html

[U16] Py：命令行参数解析
来源：http://dali.mhx1999.top/Article/details/gtawjpzpfl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shuidangran.top/Article/details/gtnvnoamem.html

[U17] Py：初始化日志
来源：http://dali.zhengqikj.top/Article/details/gtogomrflr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yongpay.top/Article/details/gtgyceanes.html

[U18] Py：预编译正则
来源：http://dali.cashguo.top/Article/details/gtqbdciivx.html

pat = re.compile(r"\d+")
来源：http://dali.yongpay.top/Article/details/gtipglrlrv.html

[U19] Py：正则替换带回调
来源：http://dali.aizwys.cn/Article/details/gtsztdrzzn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.feifeiyinyue.top/Article/details/gtnvrroncl.html

[U20] Py：缓存函数结果
来源：http://dali.9152youxi.cn/Article/details/gtyjweitgb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xinyue.icu/Article/details/gtgrwthile.html

[U21] Py：自定义上下文管理器
来源：http://dali.snrcjt.cn/Article/details/gtlbbmvsoq.html

@contextlib.contextmanager
来源：http://dali.zhiwuduotai.top/Article/details/gtjrpaylra.html

[U22] Py：矩阵转置
来源：http://dali.bjfxy.top/Article/details/gttqvpqkku.html

list(zip(*m))
来源：http://dali.guannengcc.top/Article/details/gtnfzrcpeu.html

[U23] Py：分块读取大文件
来源：http://dali.ydzc1.top/Article/details/gtvnqsxghh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.birdmap.top/Article/details/gtgzgzrixh.html

[U24] Py：路径操作
来源：http://dali.shzxlz.cn/Article/details/gtctgswtqo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.meibo888.top/Article/details/gtdbfpjyza.html

[U25] Py：CSV 按字典读
来源：http://dali.iojbl.cn/Article/details/gtxvyudgcb.html

csv.DictReader(f)
来源：http://dali.nanxinkj.top/Article/details/gteyvziwjm.html

[U26] Py：并发下载
来源：http://dali.xuetiantiany.cn/Article/details/gtyfqiloqh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.haohaochexian.top/Article/details/gtxhrtzsfy.html

[U27] Py：异步 HTTP
来源：http://dali.tian-w.cn/Article/details/gttykprbny.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cqqwz.cn/Article/details/gtvwwotybr.html

[U28] Py：类型别名
来源：http://dali.hnxiangtu.top/Article/details/gtwjxagund.html

UserId = int
来源：http://dali.yuanzhike.top/Article/details/gtvniawigx.html

[U29] Py：属性校验
来源：http://dali.tian-w.cn/Article/details/gtoyyjgvlc.html

@property 与 @x.setter 配合
来源：http://dali.guowangkeji.top/Article/details/gtnodbyvny.html

[U30] Py：数据类
来源：http://dali.meibo888.top/Article/details/gtjqyepuww.html

@dataclass(slots=True)
来源：http://dali.jqgufenzy.top/Article/details/gtynjoenvk.html

[U31] Py：单测
来源：http://dali.zycfv.cn/Article/details/gtyikasaew.html

python -m pytest -q
来源：http://dali.gaohongyu789.top/Article/details/gthcraphxs.html

[U32] Py：代码格式化
来源：http://dali.ppjwa.cn/Article/details/gtctomhyvm.html

ruff format . && ruff check --fix .
来源：http://dali.xuanzx.com/Article/details/gttbdbiyfo.html

[U33] Py：打包发布
来源：http://dali.shangyingyoupin.top/Article/details/gtqjfgxrcr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xylfe.cn/Article/details/gtbyjwkcmq.html

[U34] Py：判断编码
来源：http://dali.jlsjyb.cn/Article/details/gtvarrevdo.html

chardet.detect(raw)
来源：http://dali.ivvv.top/Article/details/gtmmluvuql.html

[U35] Py：发送邮件
来源：http://dali.yj20258.top/Article/details/gtwsmcxamg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hnxiangtu.top/Article/details/gtcckkygfd.html

[U36] Py：定时任务
来源：http://dali.nanxuanxn.top/Article/details/gtzjoffzgb.html

schedule.every(10).minutes.do(job)
来源：http://dali.redwolf501.top/Article/details/gtzlbgmvsw.html

[U37] Py：读写 Excel
来源：http://dali.xuetiantiany.cn/Article/details/gtmlksudrp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ehwqpu.com/Article/details/gtasziovsx.html

[U38] Py：获取脚本所在目录
来源：http://dali.gaohongyu789.top/Article/details/gtyecjbvgl.html

Path(__file__).resolve().parent
来源：http://dali.0kj1m.cn/Article/details/gtnuotahsr.html

[U39] Py：判断是否在交互环境
来源：http://dali.chenjidiqi.icu/Article/details/gtyhrmusme.html

sys.stdout.isatty()
来源：http://dali.andypj.xyz/Article/details/gtjambwwpo.html

[U40] Py：打印到标准错误
来源：http://dali.zhengqikj.top/Article/details/gtkqktixhk.html

print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gtvhcxjxsi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.c1oappe.top/Article/details/gthnahhkqe.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sysykeji.top/Article/details/gtsjtbvkga.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhengqikj.top/Article/details/gtogiakijk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zycfv.cn/Article/details/gtblmdpmkq.html

[U43] PHP：声明命名空间
来源：http://dali.birdmap.top/Article/details/gtngwtjcfp.html

namespace App\Http;
来源：http://dali.yvedp.cn/Article/details/gtrajojeip.html

[U44] PHP：开启严格类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytssiaro.html

declare(strict_types=1);
来源：http://dali.jlsjyb.cn/Article/details/gtikhuxkwr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.kuanghao11.cn/Article/details/gtebqggnhm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtftzaeqdb.html

[U46] PHP：可空类型
来源：http://dali.iojbl.cn/Article/details/gtwydmhumz.html

?string $name = null
来源：http://dali.nanxinkj.top/Article/details/gtgfgxmkzi.html

[U47] PHP：联合类型
来源：http://dali.dashuyun.cn/Article/details/gtcgxrbjpr.html

int|string $id
来源：http://dali.zhongyouzk.top/Article/details/gtwjoqmpkp.html

[U48] PHP：纯枚举
来源：http://dali.dianchejie.cn/Article/details/gtrwzrstcf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.daria6918.cn/Article/details/gtwvhvbtml.html

[U49] PHP：只读属性
来源：http://dali.gaohongyu789.top/Article/details/gtwkdlogko.html

public readonly string $name
来源：http://dali.yj20258.top/Article/details/gtbplsjgtm.html

[U50] PHP：构造器属性提升
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunjwbxuk.html

public function __construct(private int $id) {}
来源：http://dali.pycfn.com/Article/details/gtifcnioty.html

[U51] PHP：数组解构
来源：http://dali.ydzc1.top/Article/details/gtxgzutzfo.html

[$a, $b] = $arr;
来源：http://dali.daxiang520.top/Article/details/gtmxkyckdr.html

[U52] PHP：箭头函数
来源：http://dali.fzhhl.top/Article/details/gtqsidyfwb.html

$double = fn($x) => $x * 2;
来源：http://dali.jqgufenzy.top/Article/details/gtmoemglwm.html

[U53] PHP：空合并运算符
来源：http://dali.jlsjyb.cn/Article/details/gtjqumptla.html

$v = $a ?? $b ?? "default";
来源：http://dali.gaohongyu789.top/Article/details/gtauxhquyi.html

[U54] PHP：空安全调用
来源：http://dali.feifeiyinyue.top/Article/details/gtaubrkpoa.html

$obj?->method()
来源：http://dali.andypj.xyz/Article/details/gttpfplgti.html

[U55] PHP：match 表达式
来源：http://dali.gaohongyu789.top/Article/details/gtkneveezx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.daria6918.cn/Article/details/gtwhnkgbfv.html

[U56] PHP：命名参数
来源：http://dali.hammf.cn/Article/details/gtqmlwnllr.html

f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gtaqlqijli.html

[U57] PHP：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gttdjjefsa.html

"值: {$a}"
来源：http://dali.zhoulong.xyz/Article/details/gtdbicebqj.html

[U58] PHP：数组三件套
来源：http://dali.chenzaomai.com/Article/details/gtbheixyfh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yuxming.cn/Article/details/gtirbbuzwr.html

[U59] PHP：自定义排序
来源：http://dali.shuidangran.top/Article/details/gtsglkvghw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hywenlv.cn/Article/details/gtbyuzvczr.html

[U60] PHP：JSON 编解码
来源：http://dali.mhx1999.top/Article/details/gthcyfhadf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhoulong.xyz/Article/details/gtvgyjkcjo.html

[U61] PHP：正则
来源：http://dali.shanyushiyangtech.top/Article/details/gtescygksw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jyoumei.cn/Article/details/gtzpcxahln.html

[U62] PHP：日期对象
来源：http://dali.wangdashe.top/Article/details/gtdxmgogas.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhoulong.xyz/Article/details/gtsrlcwman.html

[U63] PHP：文件读写
来源：http://dali.meibo888.top/Article/details/gtkgpternf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.dianchejie.cn/Article/details/gtcicqxhhv.html

[U64] PHP：目录遍历
来源：http://dali.jqgfzy.top/Article/details/gtbwuqdyxn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nanxinkj.top/Article/details/gtyhnumxmx.html

[U65] PHP：会话
来源：http://dali.cucudq.cn/Article/details/gthmrkouqt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.birdmap.top/Article/details/gtistybvbn.html

[U66] PHP：设置 Cookie
来源：http://dali.jinyuanbaomall.cn/Article/details/gticbolkgw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jyoumei.cn/Article/details/gtnmekguzc.html

[U67] PHP：处理文件上传
来源：http://dali.jlsjyb.cn/Article/details/gtqjtvmxle.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ppjwa.cn/Article/details/gtmkgjznbc.html

[U68] PHP：PDO 连接
来源：http://dali.meibo888.top/Article/details/gthtfdhymh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ybcxt.top/Article/details/gtmkpybqry.html

[U69] PHP：PDO 预处理
来源：http://dali.jinqigfzy.top/Article/details/gtdklwkjmc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gzhubu.top/Article/details/gtueksxpen.html

[U70] PHP：PDO 事务
来源：http://dali.zycfv.cn/Article/details/gtvkugmqhq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hfpthk.cn/Article/details/gthfkzblmy.html

[U71] PHP：抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gtnpvptuuc.html

throw new RuntimeException("失败", 500);
来源：http://dali.hfpthk.cn/Article/details/gthuogvmyr.html

[U72] PHP：写错误日志
来源：http://dali.9152youxi.cn/Article/details/gtxfvqmwyf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ivvv.top/Article/details/gtcjcwfqmp.html

[U73] PHP：读取 ini 配置
来源：http://dali.gogol.net.cn/Article/details/gtximsnaxv.html

parse_ini_file("config.ini", true)
来源：http://dali.jyoumei.cn/Article/details/gtuhfhqhxi.html

[U74] PHP：读取环境变量
来源：http://dali.birdmap.top/Article/details/gtymhpbmpa.html

getenv("APP_ENV") ?: "production"
来源：http://dali.smart0.xyz/Article/details/gtovyijchk.html

[U75] PHP：依赖注入
来源：http://dali.mhx1999.top/Article/details/gttcqneceh.html

composer require psr/container
来源：http://dali.yuanzhike.top/Article/details/gtbahbtsae.html

[U76] PHP：简单路由
来源：http://dali.yvedp.cn/Article/details/gtehudytgr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jinqigufen.top/Article/details/gttjhhzedt.html

[U77] PHP：模板渲染
来源：http://dali.vqdsnc.cn/Article/details/gtfgukesci.html

composer require twig/twig
来源：http://dali.haohaochexian.top/Article/details/gtgjhnklxk.html

[U78] PHP：单元测试
来源：http://dali.ivvv.top/Article/details/gtasqrukxa.html

composer require --dev phpunit/phpunit
来源：http://dali.chenjidiqi.icu/Article/details/gtxgkmsird.html

[U79] PHP：静态分析
来源：http://dali.cqqwz.cn/Article/details/gtoccqvqec.html

composer require --dev phpstan/phpstan
来源：http://dali.dianchejie.cn/Article/details/gtwxmltxlu.html

[U80] PHP：代码规范修复
来源：http://dali.yj20258.top/Article/details/gtktxipqmq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.chenlongwang.top/Article/details/gtjiltounp.html

[U81] JS：初始化项目
来源：http://dali.jinyuanbaomall.cn/Article/details/gttphedocs.html

npm init -y;  npm i express
来源：http://dali.nanxinkj.top/Article/details/gtvwkvtyqx.html

[U82] JS：package.json 脚本
来源：http://dali.sysykeji.top/Article/details/gtajpiayyv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.chenjidiqi.icu/Article/details/gtwuntsdyo.html

[U83] JS：ES Module 导入导出
来源：http://dali.gogol.net.cn/Article/details/gtrqwylwlk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yonumen.top/Article/details/gtxqeqcxbu.html

[U84] JS：CommonJS 写法
来源：http://dali.fzhhl.top/Article/details/gtfjdsdmcg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.vqdsnc.cn/Article/details/gtwgdjwivq.html

[U85] JS：可选链
来源：http://dali.shzxlz.cn/Article/details/gthbjmeylk.html

a?.b?.c
来源：http://dali.chenjidiqi.icu/Article/details/gtpbbpciyi.html

[U86] JS：空值合并
来源：http://dali.nanxuanxn.top/Article/details/gtavicuzee.html

a ?? b
来源：http://dali.daria6918.cn/Article/details/gtqkwtgpjb.html

[U87] JS：解构默认值
来源：http://dali.chenjidiqi.icu/Article/details/gtrxmwwhqw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.9152youxi.cn/Article/details/gtgitykcae.html

[U88] JS：对象展开合并
来源：http://dali.guannengcc.top/Article/details/gtlufhjsfm.html

{ ...a, ...b }
来源：http://dali.svipenyu.cn/Article/details/gtownduuxq.html

[U89] JS：数组去重
来源：http://dali.jiagoushi.top/Article/details/gtngkbebvx.html

[...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtuufnmjer.html

[U90] JS：数字数组排序
来源：http://dali.ydzc1.top/Article/details/gtittkfrzs.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtlbtckxvr.html

[U91] JS：对象键值遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdimwpnxv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shangyingyoupin.top/Article/details/gtoigixmwb.html

[U92] JS：深拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtlzxqnieq.html

structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtwiyomytz.html

[U93] JS：模板字符串
来源：http://dali.yonumen.top/Article/details/gttdctjjly.html

`共 ${n} 条`
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykpmaiqp.html

[U94] JS：箭头函数
来源：http://dali.kuanghao11.cn/Article/details/gtlqfjtyun.html

const double = x => x * 2;
来源：http://dali.zhoulong.xyz/Article/details/gtplrfxifs.html

[U95] JS：Promise 包装
来源：http://dali.yanxiufei.cn/Article/details/gtrmvnwygw.html

new Promise((resolve, reject) => {})
来源：http://dali.jqgfzy.top/Article/details/gtwafpbmsf.html

[U96] JS：async/await 与异常
来源：http://dali.guowangkeji.top/Article/details/gtekqryhyg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtpyivgjxb.html

[U97] JS：并发请求
来源：http://dali.havefunace.top/Article/details/gtjqjpstgu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtkhyhyydm.html

[U98] JS：fetch 带 JSON
来源：http://dali.9152youxi.cn/Article/details/gtdegipgcu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yonumen.top/Article/details/gtskdccqpi.html

[U99] JS：事件监听
来源：http://dali.xylfe.cn/Article/details/gtmyzfwjns.html

el.addEventListener("click", e => {})
来源：http://dali.svipenyu.cn/Article/details/gtqrqefccp.html

[U100] JS：DOM 查询
来源：http://dali.aizwys.cn/Article/details/gtgrlebutg.html

document.querySelector(".item")
来源：http://dali.jianghu66.top/Article/details/gtwpiigpqe.html

[U101] JS：classList 操作
来源：http://dali.hywenlv.cn/Article/details/gtyvfqdrus.html

el.classList.toggle("active")
来源：http://dali.c1oappe.top/Article/details/gtsbzyiqvq.html

[U102] JS：本地存储
来源：http://dali.chenlongwang.top/Article/details/gtsqbrjznh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.0kj1m.cn/Article/details/gtpprpzayx.html

[U103] JS：定时器
来源：http://dali.jianghu66.top/Article/details/gtleledqke.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cashguo.top/Article/details/gtsvhreygy.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gtrdwummsu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gtetlejulk.html

[U105] JS：节流
来源：http://dali.pycfn.com/Article/details/gtryvykkvq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.fengsongda.top/Article/details/gtcbxqkozz.html

[U106] JS：日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtezhzdnbb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.fzhhl.top/Article/details/gtdkxzpjiu.html

[U107] JS：数字千分位
来源：http://dali.guowangkeji.top/Article/details/gtdnkubhot.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yueranfly.top/Article/details/gtzbrphlog.html

[U108] JS：随机整数
来源：http://dali.ehwqpu.com/Article/details/gtycofoghh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tanke756.top/Article/details/gtntzidjqf.html

[U109] JS：数组分组
来源：http://dali.zdqjudy.top/Article/details/gtnuvrdwzl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gtkngqyqrj.html

[U110] JS：数组分块
来源：http://dali.yuanzhike.top/Article/details/gtmnltrjcu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tianlin.xyz/Article/details/gtcimcbiam.html

[U111] JS：对象转 Map
来源：http://dali.yj20258.top/Article/details/gtfzirjjlb.html

new Map(Object.entries(obj))
来源：http://dali.mhx1999.top/Article/details/gtvktprsyf.html

[U112] JS：字符串补位
来源：http://dali.zhixingplan.top/Article/details/gtwfjnccde.html

"7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtoehekqyv.html

[U113] JS：正则替换全部
来源：http://dali.xylfe.cn/Article/details/gthlybwopa.html

s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtjcwscypr.html

[U114] JS：JSON 深比较
来源：http://dali.yuanzhike.top/Article/details/gtbbyyfjnf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.c1oappe.top/Article/details/gtzxyrslqv.html

[U115] JS：生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gtiwxerccd.html

crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpocunrly.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jianghu66.top/Article/details/gtlrlxxjzp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.bjfxy.top/Article/details/gtcotoxwwn.html

[U117] JS：单元测试
来源：http://dali.yj20258.top/Article/details/gttvsgpibg.html

npm i -D vitest;  npx vitest
来源：http://dali.sweek.top/Article/details/gtptbcwyoe.html

[U118] JS：开发服务器
来源：http://dali.pengpengdd.cyou/Article/details/gtqmxwahpe.html

npm i -D vite;  npx vite
来源：http://dali.yanxiufei.cn/Article/details/gtxtkcjpav.html

[U119] JS：生产构建
来源：http://dali.gotoacloud.top/Article/details/gtnvbaheyh.html

npx vite build
来源：http://dali.nwbrower.top/Article/details/gtetoskmkq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinghuilouyu.cn/Article/details/gtduhxqwmv.html

import.meta.env.VITE_API_URL
来源：http://dali.xinyue.icu/Article/details/gtpuujpkdp.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtatkfvotw.html

统计汇总
来源：http://dali.ppjwa.cn/Article/details/gtrvofzjgs.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtpkfgwted.html

按语言统计（条）：
来源：http://dali.yueranfly.top/Article/details/gtzfqzwxwe.html

Python ......... 252
来源：http://dali.zdqjudy.top/Article/details/gtqxhkhswo.html

PHP ............ 252
来源：http://dali.ivvv.top/Article/details/gtqwrzlydg.html

JavaScript ..... 252
来源：http://dali.svipenyu.cn/Article/details/gtplbjuarh.html

TypeScript ..... 212
来源：http://dali.hfpthk.cn/Article/details/gtttulftum.html

Java ........... 212
来源：http://dali.fengsongda.top/Article/details/gtxbfqlydf.html

Go ............. 212
来源：http://dali.redwolf501.top/Article/details/gtkijanyjo.html

Ruby ........... 212
来源：http://dali.cqqwz.cn/Article/details/gtxuralgaw.html

C# ............. 212
来源：http://dali.xylfe.cn/Article/details/gtvpssyuiw.html

C .............. 30
来源：http://dali.tian-w.cn/Article/details/gtuxvjfjzh.html

C++ ............ 30
来源：http://dali.ydzc1.top/Article/details/gtnajiubsu.html

SQL ............ 90
来源：http://dali.9152youxi.cn/Article/details/gtciedlxxs.html

Bash ........... 80
来源：http://dali.sufxvd.cn/Article/details/gticalrhau.html

Kotlin ......... 15
来源：http://dali.jinqigufen.top/Article/details/gtukbcprmq.html

Swift .......... 15
来源：http://dali.hnxiangtu.top/Article/details/gtsravqdrb.html

Lua ............ 10
来源：http://dali.jqgfzy.top/Article/details/gtzpjmbtja.html

Perl ........... 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejrmjaot.html

Scala .......... 10
来源：http://dali.hysaishi.cn/Article/details/gtnqjeudtr.html

------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtolawuovk.html

合计 ........... 2106 条
来源：http://dali.gaohongyu789.top/Article/details/gtybwxfudw.html

按章节统计：
来源：http://dali.xinyue.icu/Article/details/gtnvjrhawl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yonumen.top/Article/details/gtuzqcbbqk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yvedp.cn/Article/details/gtlghgaoys.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gtwoubmewf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ydzc1.top/Article/details/gtofrvnvym.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gzhubu.top/Article/details/gtbnsbqztt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.daxiang520.top/Article/details/gtxcoppzws.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gtwstxtyaf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nwbrower.top/Article/details/gtzzlrygbe.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gtpmecvbpo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.nanxinkj.top/Article/details/gtdpnsfrdk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtlyddfosu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtqcdjzdfk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtghatxncb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.dianchejie.cn/Article/details/gteykslvtn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yj20258888.top/Article/details/gtvlvmfidr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gteckgltqj.html

Q SQL 专题                              90
来源：http://dali.nanxuanxn.top/Article/details/gtasfbosva.html

R Bash 专题                             80
来源：http://dali.yongpay.top/Article/details/gtbtasrnqi.html

S C / C++ 专题                          60
来源：http://dali.zdqjudy.top/Article/details/gtuihxqjdm.html

T 其他语言补充                          60
来源：http://dali.yj20258.top/Article/details/gtmbkbxnux.html

U 高频实用片段                         120
来源：http://dali.sxryk.cn/Article/details/gttfxfjzsy.html

------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gtnngaymjw.html

合计                                  2106 条
来源：http://dali.pycfn.com/Article/details/gtlgmjdpai.html

--------------------------------------------------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gttshkszie.html

使用提醒
来源：http://dali.feifeiyinyue.top/Article/details/gtshggtoii.html

--------------------------------------------------------------------------------
来源：http://dali.meibo888.top/Article/details/gtkzeqrieh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.c1oappe.top/Article/details/gtnlwjnvmb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yj20258.top/Article/details/gthhcloemf.html


<!-- 参考信息 -->