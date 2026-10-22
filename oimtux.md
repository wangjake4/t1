代发 wailian999

[U01] Py：创建虚拟环境
来源：http://dali.fengsongda.top/Article/details/gt2aakhruib.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.meibo888.top/Article/details/gt2hpmyabog.html

[U02] Py：导出 / 安装依赖
来源：http://dali.316326.xyz/Article/details/gt2mqmurnsh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tanke756.top/Article/details/gt2isuxznkj.html

[U03] Py：加载 .env 配置
来源：http://dali.jinqigfzy.top/Article/details/gt2wdlkbksf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tanke756.top/Article/details/gt2vvydeclc.html

[U04] Py：变量调试打印
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cwvuivob.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sysykeji.top/Article/details/gt2xpgspyck.html

[U05] Py：列表去重且保序
来源：http://dali.tian-w.cn/Article/details/gt2qqymctwf.html

list(dict.fromkeys(arr))
来源：http://dali.fengsongda.top/Article/details/gt2njgxrcwl.html

[U06] Py：合并两个字典
来源：http://dali.ivvv.top/Article/details/gt2nwzwufyl.html

{**a, **b}
来源：http://dali.sxryk.cn/Article/details/gt2thmwdxmx.html

[U07] Py：反转字典键值
来源：http://dali.fzhhl.top/Article/details/gt2kpfceecz.html

{v: k for k, v in d.items()}
来源：http://dali.yonumen.top/Article/details/gt2ijyduphg.html

[U08] Py：展平二维列表
来源：http://dali.smart0.xyz/Article/details/gt2eamprmfz.html

[y for x in nested for y in x]
来源：http://dali.yueranfly.top/Article/details/gt2mtwjkffr.html

[U09] Py：字典取最大值的键
来源：http://dali.fengsongda.top/Article/details/gt2xnnclkkm.html

max(d, key=d.get)
来源：http://dali.yuanzhike.top/Article/details/gt2mxplptjc.html

[U10] Py：按值排序字典
来源：http://dali.ivvv.top/Article/details/gt2oehexdnl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.iojbl.cn/Article/details/gt2tkuxxfdz.html

[U11] Py：生成器表达式
来源：http://dali.tianlin.xyz/Article/details/gt2nsdsztwk.html

(x * 2 for x in arr)
来源：http://dali.dashuyun.cn/Article/details/gt2cpxmvodf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.snrcjt.cn/Article/details/gt2fzqnxldh.html

Counter(arr).most_common(3)
来源：http://dali.hywenlv.cn/Article/details/gt2mikrekdc.html

[U13] Py：固定长度队列
来源：http://dali.jyoumei.cn/Article/details/gt2oexsyacg.html

deque(maxlen=10)
来源：http://dali.jyoumei.cn/Article/details/gt2btiutvyr.html

[U14] Py：分组收集到列表
来源：http://dali.xylfe.cn/Article/details/gt2drprvgns.html

defaultdict(list)
来源：http://dali.yvedp.cn/Article/details/gt2jblzvxmt.html

[U15] Py：高精度计时
来源：http://dali.gotoacloud.top/Article/details/gt2chlxfqxc.html

t = time.perf_counter()
来源：http://dali.vqdsnc.cn/Article/details/gt2kcedbiof.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pzespzrl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hywenlv.cn/Article/details/gt2lznbgwqk.html

[U17] Py：初始化日志
来源：http://dali.hysaishi.cn/Article/details/gt2qcbpmdee.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.snrcjt.cn/Article/details/gt2lqhtitsa.html

[U18] Py：预编译正则
来源：http://dali.hammf.cn/Article/details/gt2khtlzjqk.html

pat = re.compile(r"\d+")
来源：http://dali.yongpay.top/Article/details/gt2tdisdndi.html

[U19] Py：正则替换带回调
来源：http://dali.yj20258888.top/Article/details/gt2mvctjein.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zycfv.cn/Article/details/gt2ilmwfkdw.html

[U20] Py：缓存函数结果
来源：http://dali.jqgfzy.top/Article/details/gt2gtyffgex.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yanxiufei.cn/Article/details/gt2ccnjodle.html

[U21] Py：自定义上下文管理器
来源：http://dali.cqqwz.cn/Article/details/gt2rpezjewb.html

@contextlib.contextmanager
来源：http://dali.ivvv.top/Article/details/gt2erefsugu.html

[U22] Py：矩阵转置
来源：http://dali.shangyingyoupin.top/Article/details/gt2hmrufyzi.html

list(zip(*m))
来源：http://dali.kuanghao11.cn/Article/details/gt2gvxurxtz.html

[U23] Py：分块读取大文件
来源：http://dali.tian-w.cn/Article/details/gt2hejogqmr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xinyue.icu/Article/details/gt2ypneddkg.html

[U24] Py：路径操作
来源：http://dali.hammf.cn/Article/details/gt2vztqfckl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gt2irpxmibl.html

[U25] Py：CSV 按字典读
来源：http://dali.wangshuangyany.cn/Article/details/gt2bkubjjvm.html

csv.DictReader(f)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uhzdouzc.html

[U26] Py：并发下载
来源：http://dali.nanxinkj.top/Article/details/gt2zgqobhrc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.daria6918.cn/Article/details/gt2ynwpvcnt.html

[U27] Py：异步 HTTP
来源：http://dali.hnxiangtu.top/Article/details/gt2mgscycbx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.iojbl.cn/Article/details/gt2iblcxcyr.html

[U28] Py：类型别名
来源：http://dali.yongpay.top/Article/details/gt2dcwwgfjg.html

UserId = int
来源：http://dali.xylfe.cn/Article/details/gt2zysisatc.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2amlxxvfs.html

@property 与 @x.setter 配合
来源：http://dali.haohaochexian.top/Article/details/gt2jzvsmjuh.html

[U30] Py：数据类
来源：http://dali.nanxinkj.top/Article/details/gt2nrbiknxe.html

@dataclass(slots=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fgrpaqmw.html

[U31] Py：单测
来源：http://dali.c1oappe.top/Article/details/gt2jmxlyawt.html

python -m pytest -q
来源：http://dali.yj20258888.top/Article/details/gt2dddgmuxi.html

[U32] Py：代码格式化
来源：http://dali.andypj.xyz/Article/details/gt2xqddgwvw.html

ruff format . && ruff check --fix .
来源：http://dali.9152youxi.cn/Article/details/gt2udqujgox.html

[U33] Py：打包发布
来源：http://dali.yangfankeji.com/Article/details/gt2mkyavzlk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhixingplan.top/Article/details/gt2sljfbsaa.html

[U34] Py：判断编码
来源：http://dali.sxryk.cn/Article/details/gt2dztbfkjl.html

chardet.detect(raw)
来源：http://dali.gotoacloud.top/Article/details/gt2ehypjymn.html

[U35] Py：发送邮件
来源：http://dali.snrcjt.cn/Article/details/gt2yjevlxqk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yonumen.top/Article/details/gt2knglaifl.html

[U36] Py：定时任务
来源：http://dali.dianchejie.cn/Article/details/gt2xpcbnsdi.html

schedule.every(10).minutes.do(job)
来源：http://dali.0kj1m.cn/Article/details/gt2pcxbqvnh.html

[U37] Py：读写 Excel
来源：http://dali.chenlongwang.top/Article/details/gt2fuwachja.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.sweek.top/Article/details/gt2niftslpk.html

[U38] Py：获取脚本所在目录
来源：http://dali.tian-w.cn/Article/details/gt2evglodfr.html

Path(__file__).resolve().parent
来源：http://dali.aibaodan.cn/Article/details/gt2gyyexypx.html

[U39] Py：判断是否在交互环境
来源：http://dali.ydzc1.top/Article/details/gt2ktszdmia.html

sys.stdout.isatty()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jlfzskjq.html

[U40] Py：打印到标准错误
来源：http://dali.jiagoushi.top/Article/details/gt2fsnpsrit.html

print("err", file=sys.stderr)
来源：http://dali.yangfankeji.com/Article/details/gt2enwrkdpj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2czrbigxx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hnqzz.top/Article/details/gt2pmyaqyza.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jlsjyb.cn/Article/details/gt2ciwkwnwf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yj20258888.top/Article/details/gt2wunvggnw.html

[U43] PHP：声明命名空间
来源：http://dali.yj20258888.top/Article/details/gt2ywmptoip.html

namespace App\Http;
来源：http://dali.cheryme.top/Article/details/gt2trkdykbo.html

[U44] PHP：开启严格类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2dwopynzw.html

declare(strict_types=1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kawsdadd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.316326.xyz/Article/details/gt2pywzpjkx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gt2ziujttcr.html

[U46] PHP：可空类型
来源：http://dali.jiagoushi.top/Article/details/gt2nuuacwfy.html

?string $name = null
来源：http://dali.cashguo.top/Article/details/gt2kpkkbxvy.html

[U47] PHP：联合类型
来源：http://dali.sweek.top/Article/details/gt2gngxtbcy.html

int|string $id
来源：http://dali.jinqigufen.top/Article/details/gt2rjfygqwn.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuqekfp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2awbpzgus.html

[U49] PHP：只读属性
来源：http://dali.dianchejie.cn/Article/details/gt2kqxpcfnt.html

public readonly string $name
来源：http://dali.andypj.xyz/Article/details/gt2whptitqk.html

[U50] PHP：构造器属性提升
来源：http://dali.ehwqpu.com/Article/details/gt2jbkldxsh.html

public function __construct(private int $id) {}
来源：http://dali.guannengcc.top/Article/details/gt2hjzbggzk.html

[U51] PHP：数组解构
来源：http://dali.nwbrower.top/Article/details/gt2kpdsmkji.html

[$a, $b] = $arr;
来源：http://dali.tanke756.top/Article/details/gt2dtoludgu.html

[U52] PHP：箭头函数
来源：http://dali.shzxlz.cn/Article/details/gt2tduehqlb.html

$double = fn($x) => $x * 2;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2umcdyiev.html

[U53] PHP：空合并运算符
来源：http://dali.gzhubu.top/Article/details/gt2ccoitdlz.html

$v = $a ?? $b ?? "default";
来源：http://dali.aizwys.cn/Article/details/gt2mzmzaetb.html

[U54] PHP：空安全调用
来源：http://dali.chenlongwang.top/Article/details/gt2rveghtuv.html

$obj?->method()
来源：http://dali.vqdsnc.cn/Article/details/gt2wkfriukt.html

[U55] PHP：match 表达式
来源：http://dali.gotoacloud.top/Article/details/gt2xiocwtjg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jianghu66.top/Article/details/gt2gazpnfdc.html

[U56] PHP：命名参数
来源：http://dali.andypj.xyz/Article/details/gt2mpanmwzn.html

f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gt2fxjccudp.html

[U57] PHP：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gt2jkpaznza.html

"值: {$a}"
来源：http://dali.zdqjudy.top/Article/details/gt2xjejgoxg.html

[U58] PHP：数组三件套
来源：http://dali.yj20258888.top/Article/details/gt2qwofvvwb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ivvv.top/Article/details/gt2cupqdaxb.html

[U59] PHP：自定义排序
来源：http://dali.birdmap.top/Article/details/gt2zluxynnb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gt2kpxrsnsw.html

[U60] PHP：JSON 编解码
来源：http://dali.iojbl.cn/Article/details/gt2lldfncyh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sweek.top/Article/details/gt2rghootzo.html

[U61] PHP：正则
来源：http://dali.snrcjt.cn/Article/details/gt2tyjobmfg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2kgiraiyj.html

[U62] PHP：日期对象
来源：http://dali.fengsongda.top/Article/details/gt2vkqrgruw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.316326.xyz/Article/details/gt2skjcubem.html

[U63] PHP：文件读写
来源：http://dali.jinqigufen.top/Article/details/gt2hoaouvrc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cashguo.top/Article/details/gt2uzkxnnos.html

[U64] PHP：目录遍历
来源：http://dali.haohaochexian.top/Article/details/gt2vsxxajkm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xylfe.cn/Article/details/gt2rlqrzyqk.html

[U65] PHP：会话
来源：http://dali.hysaishi.cn/Article/details/gt2dgnqfysc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yongpay.top/Article/details/gt2rnycwzrh.html

[U66] PHP：设置 Cookie
来源：http://dali.cqqwz.cn/Article/details/gt2gcodolgj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.vqdsnc.cn/Article/details/gt2tceuovcc.html

[U67] PHP：处理文件上传
来源：http://dali.yonumen.top/Article/details/gt2jtylebjk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.chenzaomai.com/Article/details/gt2nqpfobis.html

[U68] PHP：PDO 连接
来源：http://dali.yj20258888.top/Article/details/gt2vnelqjdl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hysaishi.cn/Article/details/gt2xjewoipc.html

[U69] PHP：PDO 预处理
来源：http://dali.jlsjyb.cn/Article/details/gt2hysjvdvv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.chenlongwang.top/Article/details/gt2kzrnqdmo.html

[U70] PHP：PDO 事务
来源：http://dali.ydzc1.top/Article/details/gt2sgqfphod.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yj20258888.top/Article/details/gt2mckardzd.html

[U71] PHP：抛出异常
来源：http://dali.bjfxy.top/Article/details/gt2qnhdaedk.html

throw new RuntimeException("失败", 500);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mrpyeshx.html

[U72] PHP：写错误日志
来源：http://dali.sxryk.cn/Article/details/gt2jpdwxdpe.html

error_log("失败: " . $e->getMessage());
来源：http://dali.wangshuangyany.cn/Article/details/gt2dhhseqsb.html

[U73] PHP：读取 ini 配置
来源：http://dali.yonumen.top/Article/details/gt2ywljihuv.html

parse_ini_file("config.ini", true)
来源：http://dali.hfpthk.cn/Article/details/gt2cobtcsee.html

[U74] PHP：读取环境变量
来源：http://dali.zdqjudy.top/Article/details/gt2jzvdpovz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xuetiantiany.cn/Article/details/gt2sppdxlpt.html

[U75] PHP：依赖注入
来源：http://dali.c1oappe.top/Article/details/gt2xxlykvaf.html

composer require psr/container
来源：http://dali.mhx1999.top/Article/details/gt2vwkxqvms.html

[U76] PHP：简单路由
来源：http://dali.haohaochexian.top/Article/details/gt2lhogqecu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.aibaodan.cn/Article/details/gt2btaizyaq.html

[U77] PHP：模板渲染
来源：http://dali.sweek.top/Article/details/gt2bqldhbcg.html

composer require twig/twig
来源：http://dali.birdmap.top/Article/details/gt2mpwipnyr.html

[U78] PHP：单元测试
来源：http://dali.yj20258.top/Article/details/gt2rwmucpzn.html

composer require --dev phpunit/phpunit
来源：http://dali.haohaochexian.top/Article/details/gt2hrtsiqna.html

[U79] PHP：静态分析
来源：http://dali.jyoumei.cn/Article/details/gt2iaqusdke.html

composer require --dev phpstan/phpstan
来源：http://dali.sufxvd.cn/Article/details/gt2dsziyzcq.html

[U80] PHP：代码规范修复
来源：http://dali.jiagoushi.top/Article/details/gt2pljcyyvu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.316326.xyz/Article/details/gt2abgtruwi.html

[U81] JS：初始化项目
来源：http://dali.tian-w.cn/Article/details/gt2undstduq.html

npm init -y;  npm i express
来源：http://dali.xylfe.cn/Article/details/gt2qloijtvz.html

[U82] JS：package.json 脚本
来源：http://dali.c1oappe.top/Article/details/gt2wcbhagmg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ivvv.top/Article/details/gt2kmuchwlw.html

[U83] JS：ES Module 导入导出
来源：http://dali.aizwys.cn/Article/details/gt2bfflrcmq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gt2hvnymmdq.html

[U84] JS：CommonJS 写法
来源：http://dali.cucudq.cn/Article/details/gt2nmjzwklt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.chenjidiqi.icu/Article/details/gt2xdpsmkbz.html

[U85] JS：可选链
来源：http://dali.zhengqikj.top/Article/details/gt2cqlohfwp.html

a?.b?.c
来源：http://dali.smart0.xyz/Article/details/gt2rekzbxjl.html

[U86] JS：空值合并
来源：http://dali.feifeiyinyue.top/Article/details/gt2adiyyxwn.html

a ?? b
来源：http://dali.ivvv.top/Article/details/gt2ruvutojf.html

[U87] JS：解构默认值
来源：http://dali.fengsongda.top/Article/details/gt2grvirgnu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.iojbl.cn/Article/details/gt2bldzcert.html

[U88] JS：对象展开合并
来源：http://dali.shzxlz.cn/Article/details/gt2jbszpfpw.html

{ ...a, ...b }
来源：http://dali.hongshengwenyu.top/Article/details/gt2mbrczlhf.html

[U89] JS：数组去重
来源：http://dali.andypj.xyz/Article/details/gt2pczimcbo.html

[...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gt2pasklexj.html

[U90] JS：数字数组排序
来源：http://dali.birdmap.top/Article/details/gt2iekwjnia.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gt2jzgifpud.html

[U91] JS：对象键值遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rmvvvbyq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yuanzhike.top/Article/details/gt2gtkjohsn.html

[U92] JS：深拷贝
来源：http://dali.jqgfzy.top/Article/details/gt2izseetku.html

structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gt2wsuaicsk.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqvcqwf.html

`共 ${n} 条`
来源：http://dali.quarkkingdee.top/Article/details/gt2rfzquuqh.html

[U94] JS：箭头函数
来源：http://dali.316326.xyz/Article/details/gt2olvjkrbk.html

const double = x => x * 2;
来源：http://dali.cqqwz.cn/Article/details/gt2ncpxphjj.html

[U95] JS：Promise 包装
来源：http://dali.dianchejie.cn/Article/details/gt2enslyexs.html

new Promise((resolve, reject) => {})
来源：http://dali.vqdsnc.cn/Article/details/gt2xbvkauwq.html

[U96] JS：async/await 与异常
来源：http://dali.quarkkingdee.top/Article/details/gt2mtwhwdoq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gt2mjcgfqkn.html

[U97] JS：并发请求
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qxhblfah.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gt2uvssvwxp.html

[U98] JS：fetch 带 JSON
来源：http://dali.aizwys.cn/Article/details/gt2eizgdfvb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hywenlv.cn/Article/details/gt2arphszdo.html

[U99] JS：事件监听
来源：http://dali.snrcjt.cn/Article/details/gt2fidwgyyz.html

el.addEventListener("click", e => {})
来源：http://dali.ivvv.top/Article/details/gt2idfxhdcd.html

[U100] JS：DOM 查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2lihjsrwf.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2szdqzdex.html

[U101] JS：classList 操作
来源：http://dali.pycfn.com/Article/details/gt2gjrcrcew.html

el.classList.toggle("active")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ioutseeg.html

[U102] JS：本地存储
来源：http://dali.c1oappe.top/Article/details/gt2qlwlmnlr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.bjfxy.top/Article/details/gt2bhgupihf.html

[U103] JS：定时器
来源：http://dali.ydzc1.top/Article/details/gt2oadakxvh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gaohongyu789.top/Article/details/gt2tzcghndf.html

[U104] JS：防抖
来源：http://dali.daria6918.cn/Article/details/gt2nwmvyazp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gt2jixwxrpw.html

[U105] JS：节流
来源：http://dali.ppjwa.cn/Article/details/gt2dgcoyodt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2wfhmelnq.html

[U106] JS：日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gt2lzizekym.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cszmeffg.html

[U107] JS：数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gt2anbmzysc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sysykeji.top/Article/details/gt2kgiaqaou.html

[U108] JS：随机整数
来源：http://dali.yanxiufei.cn/Article/details/gt2tprfwmqe.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.haohaochexian.top/Article/details/gt2vdszmwep.html

[U109] JS：数组分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipneezkx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jlsjyb.cn/Article/details/gt2hyopyrgg.html

[U110] JS：数组分块
来源：http://dali.smart0.xyz/Article/details/gt2xolcydgu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yonumen.top/Article/details/gt2quibyqjl.html

[U111] JS：对象转 Map
来源：http://dali.sysykeji.top/Article/details/gt2ruwrnaph.html

new Map(Object.entries(obj))
来源：http://dali.gzhubu.top/Article/details/gt2gxbwuufk.html

[U112] JS：字符串补位
来源：http://dali.ehwqpu.com/Article/details/gt2oaftnoaj.html

"7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gt2otactktd.html

[U113] JS：正则替换全部
来源：http://dali.hfpthk.cn/Article/details/gt2lwvlkiuq.html

s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2qwpqyccs.html

[U114] JS：JSON 深比较
来源：http://dali.ivvv.top/Article/details/gt2fdiorooy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gt2chbugkjj.html

[U115] JS：生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gt2ruoiwitd.html

crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gt2tqjqzxku.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yonumen.top/Article/details/gt2ugqltcyh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xziqi.cn/Article/details/gt2krzqznnu.html

[U117] JS：单元测试
来源：http://dali.smart0.xyz/Article/details/gt2xsltgatr.html

npm i -D vitest;  npx vitest
来源：http://dali.mhx1999.top/Article/details/gt2lunigqxv.html

[U118] JS：开发服务器
来源：http://dali.sysykeji.top/Article/details/gt2edmipnbh.html

npm i -D vite;  npx vite
来源：http://dali.feifeiyinyue.top/Article/details/gt2yxlkbkrq.html

[U119] JS：生产构建
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pzmcvsbu.html

npx vite build
来源：http://dali.xylfe.cn/Article/details/gt2jqdgnvnx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zycfv.cn/Article/details/gt2ykuhmeud.html

import.meta.env.VITE_API_URL
来源：http://dali.xylfe.cn/Article/details/gt2iwzaxlrj.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2qmegarms.html

统计汇总
来源：http://dali.yuanzhike.top/Article/details/gt2pvsnicqw.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2zdgaebog.html

按语言统计（条）：
来源：http://dali.ehwqpu.com/Article/details/gt2siodwohh.html

Python ......... 252
来源：http://dali.gogol.net.cn/Article/details/gt2pgfjqgmw.html

PHP ............ 252
来源：http://dali.xylfe.cn/Article/details/gt2ztmdfprv.html

JavaScript ..... 252
来源：http://dali.tian-w.cn/Article/details/gt2btkugtna.html

TypeScript ..... 212
来源：http://dali.haohaochexian.top/Article/details/gt2guscesjx.html

Java ........... 212
来源：http://dali.jiagoushi.top/Article/details/gt2xczszxhx.html

Go ............. 212
来源：http://dali.vqdsnc.cn/Article/details/gt2mgvfiymy.html

Ruby ........... 212
来源：http://dali.hnxiangtu.top/Article/details/gt2dulvwpin.html

C# ............. 212
来源：http://dali.9152youxi.cn/Article/details/gt2gjfnkyvg.html

C .............. 30
来源：http://dali.hnxiangtu.top/Article/details/gt2ohxdonhv.html

C++ ............ 30
来源：http://dali.daxiang520.top/Article/details/gt2kaxfaahx.html

SQL ............ 90
来源：http://dali.hfpthk.cn/Article/details/gt2opshpyop.html

Bash ........... 80
来源：http://dali.jinqigfzy.top/Article/details/gt2pxcaqsje.html

Kotlin ......... 15
来源：http://dali.316326.xyz/Article/details/gt2asnvbtxg.html

Swift .......... 15
来源：http://dali.hammf.cn/Article/details/gt2gjxqlidt.html

Lua ............ 10
来源：http://dali.shzxlz.cn/Article/details/gt2shrcofck.html

Perl ........... 10
来源：http://dali.vqdsnc.cn/Article/details/gt2bzsbyfeu.html

Scala .......... 10
来源：http://dali.sweek.top/Article/details/gt2gvofblmb.html

------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gt2vaosurao.html

合计 ........... 2106 条
来源：http://dali.xuetiantiany.cn/Article/details/gt2suxqfxnc.html

按章节统计：
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrskpolh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhoulong.xyz/Article/details/gt2lbccyjtk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jlsjyb.cn/Article/details/gt2vpjbhpjf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gt2upqanixw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cheryme.top/Article/details/gt2upqaahho.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yonumen.top/Article/details/gt2qempisqx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.meibo888.top/Article/details/gt2xrsrlfke.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxwsvbq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yonumen.top/Article/details/gt2ihgqhuak.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gt2buavffer.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.daxiang520.top/Article/details/gt2nwfruyit.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gt2bvbudcvl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gt2ktzustfi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ifnuddbi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.redwolf501.top/Article/details/gt2lnmkweis.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.quarkkingdee.top/Article/details/gt2ghsaeplx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gt2yrtoadvr.html

Q SQL 专题                              90
来源：http://dali.ivvv.top/Article/details/gt2inyogsju.html

R Bash 专题                             80
来源：http://dali.chenjidiqi.icu/Article/details/gt2cddouilf.html

S C / C++ 专题                          60
来源：http://dali.yueranfly.top/Article/details/gt2pxsbgmpn.html

T 其他语言补充                          60
来源：http://dali.yvedp.cn/Article/details/gt2bnowzndb.html

U 高频实用片段                         120
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ggijsljq.html

------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gt2toyclaxe.html

合计                                  2106 条
来源：http://dali.hnxiangtu.top/Article/details/gt2bdlgtdid.html

--------------------------------------------------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gt2apjfmtlm.html

使用提醒
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dedletwj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tyibfsew.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.pengpengdd.cyou/Article/details/gt2yjnvveft.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jqgfzy.top/Article/details/gt2xmtpchsc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hysaishi.cn/Article/details/gt2rxyyxuhe.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.9152youxi.cn/Article/details/gt2qmerkmhh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ydzc1.top/Article/details/gt2fwztmslo.html

—— 文件结束 ——
来源：http://dali.cucudq.cn/Article/details/gt2aadytcez.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ayanlcgf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cashguo.top/Article/details/gt2uxnjgeac.html

Common Programming Examples Cheat Book
来源：http://dali.svipenyu.cn/Article/details/gt2upplhahq.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2cugxywxx.html


<!-- 参考信息 -->