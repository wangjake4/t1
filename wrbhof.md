代发 wailian999

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xziqi.cn/Article/details/gthbjfmkjy.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtxoslbymi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zdqjudy.top/Article/details/gtbmlkddva.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtoaxvacfq.html

[U01] Py：创建虚拟环境
来源：http://dali.zhiwuduotai.top/Article/details/gtxssjdhxv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsldlttgq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yvedp.cn/Article/details/gtsjmmwdtt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daxiang520.top/Article/details/gtprtmzkkk.html

[U03] Py：加载 .env 配置
来源：http://dali.quarkkingdee.top/Article/details/gtdphjtidu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.fzhhl.top/Article/details/gtlsdbeizf.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxaudeqdl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.andypj.xyz/Article/details/gtxyuqziic.html

[U05] Py：列表去重且保序
来源：http://dali.hnqzz.top/Article/details/gtlaudboop.html

list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gtkmyhzsqs.html

[U06] Py：合并两个字典
来源：http://dali.yj20258888.top/Article/details/gthkimgpju.html

{**a, **b}
来源：http://dali.zhixingplan.top/Article/details/gtmnzvszlh.html

[U07] Py：反转字典键值
来源：http://dali.zycfv.cn/Article/details/gtlxfllkyy.html

{v: k for k, v in d.items()}
来源：http://dali.chenzaomai.com/Article/details/gtaztimjey.html

[U08] Py：展平二维列表
来源：http://dali.chenlongwang.top/Article/details/gtxvoqakfs.html

[y for x in nested for y in x]
来源：http://dali.wangdashe.top/Article/details/gtolrkmrqq.html

[U09] Py：字典取最大值的键
来源：http://dali.mhx1999.top/Article/details/gtitezafys.html

max(d, key=d.get)
来源：http://dali.yj20258888.top/Article/details/gtazlxzjrn.html

[U10] Py：按值排序字典
来源：http://dali.gogol.net.cn/Article/details/gtnktfujfj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.c1oappe.top/Article/details/gtxfmyzqse.html

[U11] Py：生成器表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzobdayqh.html

(x * 2 for x in arr)
来源：http://dali.guowangkeji.top/Article/details/gtmttvevbu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.0kj1m.cn/Article/details/gtgylwvxxp.html

Counter(arr).most_common(3)
来源：http://dali.cucudq.cn/Article/details/gtcfudmocq.html

[U13] Py：固定长度队列
来源：http://dali.birdmap.top/Article/details/gtpofwqhgp.html

deque(maxlen=10)
来源：http://dali.pengpengdd.cyou/Article/details/gtykvxmvpl.html

[U14] Py：分组收集到列表
来源：http://dali.gaohongyu789.top/Article/details/gtbemzdgjn.html

defaultdict(list)
来源：http://dali.jinqigfzy.top/Article/details/gtyiugexqz.html

[U15] Py：高精度计时
来源：http://dali.cheryme.top/Article/details/gtimmahqye.html

t = time.perf_counter()
来源：http://dali.xziqi.cn/Article/details/gtwmcxogrp.html

[U16] Py：命令行参数解析
来源：http://dali.gaohongyu789.top/Article/details/gtuqfiubqp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yueranfly.top/Article/details/gtljevvttf.html

[U17] Py：初始化日志
来源：http://dali.xziqi.cn/Article/details/gtxifvlnpo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.pengpengdd.cyou/Article/details/gtimqblnzk.html

[U18] Py：预编译正则
来源：http://dali.smart0.xyz/Article/details/gtkwxcbgww.html

pat = re.compile(r"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdatwcont.html

[U19] Py：正则替换带回调
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzipyxgz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xuanzx.com/Article/details/gtewxadnto.html

[U20] Py：缓存函数结果
来源：http://dali.yongpay.top/Article/details/gtnpipmhdf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.guannengcc.top/Article/details/gtwmgankge.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccuxjcen.html

@contextlib.contextmanager
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzaijcqth.html

[U22] Py：矩阵转置
来源：http://dali.tianlin.xyz/Article/details/gtrshkbpjj.html

list(zip(*m))
来源：http://dali.feifeiyinyue.top/Article/details/gttzrxbqbn.html

[U23] Py：分块读取大文件
来源：http://dali.guowangkeji.top/Article/details/gtuvjqjxgt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shzxlz.cn/Article/details/gtntlnxcqf.html

[U24] Py：路径操作
来源：http://dali.316326.xyz/Article/details/gtemxqghna.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtsfxemane.html

[U25] Py：CSV 按字典读
来源：http://dali.xuetiantiany.cn/Article/details/gtczmpokwk.html

csv.DictReader(f)
来源：http://dali.sweek.top/Article/details/gtorchuyrp.html

[U26] Py：并发下载
来源：http://dali.tanke756.top/Article/details/gteduhhzxd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigfzy.top/Article/details/gtsqmkdqjl.html

[U27] Py：异步 HTTP
来源：http://dali.gaohongyu789.top/Article/details/gtmyqwxeoq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.pycfn.com/Article/details/gthgcgodto.html

[U28] Py：类型别名
来源：http://dali.chenjidiqi.icu/Article/details/gtugokmdph.html

UserId = int
来源：http://dali.ppjwa.cn/Article/details/gtwdtprrmn.html

[U29] Py：属性校验
来源：http://dali.tanke756.top/Article/details/gtagfsoonx.html

@property 与 @x.setter 配合
来源：http://dali.pycfn.com/Article/details/gtowgjjfas.html

[U30] Py：数据类
来源：http://dali.guannengcc.top/Article/details/gtshykntiz.html

@dataclass(slots=True)
来源：http://dali.dianchejie.cn/Article/details/gtsyiaxsgg.html

[U31] Py：单测
来源：http://dali.hysaishi.cn/Article/details/gtnljuvnzo.html

python -m pytest -q
来源：http://dali.zhongyouzk.top/Article/details/gttesdawzm.html

[U32] Py：代码格式化
来源：http://dali.birdmap.top/Article/details/gtuexdcbmm.html

ruff format . && ruff check --fix .
来源：http://dali.nanxinkj.top/Article/details/gttwymfpks.html

[U33] Py：打包发布
来源：http://dali.zhongyouzk.top/Article/details/gtxyslxnrr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinqigufen.top/Article/details/gtkpjwrafl.html

[U34] Py：判断编码
来源：http://dali.zhixingplan.top/Article/details/gtdibzlzex.html

chardet.detect(raw)
来源：http://dali.wangdashe.top/Article/details/gtwpmlctro.html

[U35] Py：发送邮件
来源：http://dali.nanxinkj.top/Article/details/gtsoonwinb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtksqbjpel.html

[U36] Py：定时任务
来源：http://dali.ybcxt.top/Article/details/gtzutlecke.html

schedule.every(10).minutes.do(job)
来源：http://dali.ehwqpu.com/Article/details/gtjswnueio.html

[U37] Py：读写 Excel
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskknroyw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zycfv.cn/Article/details/gtbfurimwh.html

[U38] Py：获取脚本所在目录
来源：http://dali.cdnleiting.top/Article/details/gtldmojjpc.html

Path(__file__).resolve().parent
来源：http://dali.fzhhl.top/Article/details/gtormjctuj.html

[U39] Py：判断是否在交互环境
来源：http://dali.hysaishi.cn/Article/details/gtrrhentqe.html

sys.stdout.isatty()
来源：http://dali.tianlin.xyz/Article/details/gteofdkbso.html

[U40] Py：打印到标准错误
来源：http://dali.cheryme.top/Article/details/gtvzmoavxj.html

print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gtyletiefh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.dianchejie.cn/Article/details/gtnvaiwzwo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.wangdashe.top/Article/details/gtgfgphlmo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.iojbl.cn/Article/details/gtufgchqwb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xinyue.icu/Article/details/gtcznnegpc.html

[U43] PHP：声明命名空间
来源：http://dali.9152youxi.cn/Article/details/gtvdcnfage.html

namespace App\Http;
来源：http://dali.ywan-chungtsiang.top/Article/details/gteaqybhsa.html

[U44] PHP：开启严格类型
来源：http://dali.ivvv.top/Article/details/gtfmmfkwto.html

declare(strict_types=1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbiiexfe.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ydzc1.top/Article/details/gtokurikzl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtxggiudsb.html

[U46] PHP：可空类型
来源：http://dali.gogol.net.cn/Article/details/gtdcsfaizv.html

?string $name = null
来源：http://dali.havefunace.top/Article/details/gtmhfvgqag.html

[U47] PHP：联合类型
来源：http://dali.chenjidiqi.icu/Article/details/gtoswerpxg.html

int|string $id
来源：http://dali.pycfn.com/Article/details/gttcakedfz.html

[U48] PHP：纯枚举
来源：http://dali.vqdsnc.cn/Article/details/gtimgrmmna.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhoulong.xyz/Article/details/gttauujmjf.html

[U49] PHP：只读属性
来源：http://dali.jinqigufen.top/Article/details/gtjfrvvfpi.html

public readonly string $name
来源：http://dali.fengsongda.top/Article/details/gtkrfwhrzn.html

[U50] PHP：构造器属性提升
来源：http://dali.iojbl.cn/Article/details/gtpfletffi.html

public function __construct(private int $id) {}
来源：http://dali.mhx1999.top/Article/details/gtvwjcjvug.html

[U51] PHP：数组解构
来源：http://dali.nanxuanxn.top/Article/details/gtiktkcfpb.html

[$a, $b] = $arr;
来源：http://dali.sufxvd.cn/Article/details/gttnlvtjvk.html

[U52] PHP：箭头函数
来源：http://dali.iojbl.cn/Article/details/gtrcwwhwrr.html

$double = fn($x) => $x * 2;
来源：http://dali.yangfankeji.com/Article/details/gtgkmncytc.html

[U53] PHP：空合并运算符
来源：http://dali.zhiwuduotai.top/Article/details/gtgnyxvczi.html

$v = $a ?? $b ?? "default";
来源：http://dali.hnxiangtu.top/Article/details/gtkomphpyd.html

[U54] PHP：空安全调用
来源：http://dali.gotoacloud.top/Article/details/gtegmsajai.html

$obj?->method()
来源：http://dali.hysaishi.cn/Article/details/gtrrhbrnbv.html

[U55] PHP：match 表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnayqsnct.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.tianlin.xyz/Article/details/gtngaygqbu.html

[U56] PHP：命名参数
来源：http://dali.tian-w.cn/Article/details/gtdjhwufni.html

f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gtatzpumdr.html

[U57] PHP：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtghabjdwp.html

"值: {$a}"
来源：http://dali.cucudq.cn/Article/details/gtklzcados.html

[U58] PHP：数组三件套
来源：http://dali.dashuyun.cn/Article/details/gtpdqylqcn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hnqzz.top/Article/details/gtxslfcvuy.html

[U59] PHP：自定义排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqealspxa.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cqqwz.cn/Article/details/gtdwruliat.html

[U60] PHP：JSON 编解码
来源：http://dali.jianghu66.top/Article/details/gtpnrdljib.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhwrhvwb.html

[U61] PHP：正则
来源：http://dali.jyoumei.cn/Article/details/gtntlbctvj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtoeufhada.html

[U62] PHP：日期对象
来源：http://dali.haohaochexian.top/Article/details/gtkmizzngn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cqqwz.cn/Article/details/gtohngcvsf.html

[U63] PHP：文件读写
来源：http://dali.haohaochexian.top/Article/details/gtpguqpflf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqyblaib.html

[U64] PHP：目录遍历
来源：http://dali.fengsongda.top/Article/details/gtlwnjhloy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhixingplan.top/Article/details/gtfofjwenn.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gtbqreycot.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gttvvqsomq.html

[U66] PHP：设置 Cookie
来源：http://dali.wangdashe.top/Article/details/gtwzapxzrp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nanxinkj.top/Article/details/gtkgtosysj.html

[U67] PHP：处理文件上传
来源：http://dali.feifeiyinyue.top/Article/details/gtkvifwljd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.aizwys.cn/Article/details/gtmswqzyga.html

[U68] PHP：PDO 连接
来源：http://dali.daxiang520.top/Article/details/gtolqjwuiu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gzhubu.top/Article/details/gtqlzmbyev.html

[U69] PHP：PDO 预处理
来源：http://dali.hywenlv.cn/Article/details/gtexlntnsd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.tianlin.xyz/Article/details/gtjiyulzge.html

[U70] PHP：PDO 事务
来源：http://dali.cdnleiting.top/Article/details/gtfaweycbr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.vqdsnc.cn/Article/details/gttxzolapi.html

[U71] PHP：抛出异常
来源：http://dali.daria6918.cn/Article/details/gtjhsheuzz.html

throw new RuntimeException("失败", 500);
来源：http://dali.gotoacloud.top/Article/details/gtdynjxekv.html

[U72] PHP：写错误日志
来源：http://dali.fzhhl.top/Article/details/gtxyuhwkui.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gtlacsfaqe.html

[U73] PHP：读取 ini 配置
来源：http://dali.yanxiufei.cn/Article/details/gtwqeibiys.html

parse_ini_file("config.ini", true)
来源：http://dali.shzxlz.cn/Article/details/gtjoslivgb.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gtgvrwxokm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.daxiang520.top/Article/details/gtkpnoqfpu.html

[U75] PHP：依赖注入
来源：http://dali.quarkkingdee.top/Article/details/gtvcaveccb.html

composer require psr/container
来源：http://dali.daxiang520.top/Article/details/gtvamsgxmt.html

[U76] PHP：简单路由
来源：http://dali.yanxiufei.cn/Article/details/gtauoehpiw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ehwqpu.com/Article/details/gtsqiugsed.html

[U77] PHP：模板渲染
来源：http://dali.hnqzz.top/Article/details/gtlafghkgp.html

composer require twig/twig
来源：http://dali.haohaochexian.top/Article/details/gtzapjubsi.html

[U78] PHP：单元测试
来源：http://dali.hywenlv.cn/Article/details/gtrslwhiyt.html

composer require --dev phpunit/phpunit
来源：http://dali.ivvv.top/Article/details/gtzdiyphxp.html

[U79] PHP：静态分析
来源：http://dali.0kj1m.cn/Article/details/gtnapnflpy.html

composer require --dev phpstan/phpstan
来源：http://dali.nanxinkj.top/Article/details/gtilntnpgp.html

[U80] PHP：代码规范修复
来源：http://dali.yj202588.top/Article/details/gtubvkrpec.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.tanke756.top/Article/details/gtcfmkjtky.html

[U81] JS：初始化项目
来源：http://dali.yangfankeji.com/Article/details/gtjxamwtff.html

npm init -y;  npm i express
来源：http://dali.wangdashe.top/Article/details/gttrahnano.html

[U82] JS：package.json 脚本
来源：http://dali.dianchejie.cn/Article/details/gtnjfunuer.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.chenlongwang.top/Article/details/gtxtpoypzs.html

[U83] JS：ES Module 导入导出
来源：http://dali.tianlin.xyz/Article/details/gtktrfojxg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.tanke756.top/Article/details/gteqrparuf.html

[U84] JS：CommonJS 写法
来源：http://dali.cashguo.top/Article/details/gtczceueql.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zycfv.cn/Article/details/gtsmzuxxro.html

[U85] JS：可选链
来源：http://dali.wangshuangyany.cn/Article/details/gtsetrfocr.html

a?.b?.c
来源：http://dali.fzhhl.top/Article/details/gtgoftnlgh.html

[U86] JS：空值合并
来源：http://dali.jiagoushi.top/Article/details/gtdexamcmz.html

a ?? b
来源：http://dali.mhx1999.top/Article/details/gtqwlbjlib.html

[U87] JS：解构默认值
来源：http://dali.chenzaomai.com/Article/details/gtlsffcmnn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.dianchejie.cn/Article/details/gtnencjcwh.html

[U88] JS：对象展开合并
来源：http://dali.yuanzhike.top/Article/details/gtfywtzban.html

{ ...a, ...b }
来源：http://dali.sufxvd.cn/Article/details/gteyymurss.html

[U89] JS：数组去重
来源：http://dali.0kj1m.cn/Article/details/gthjulkxzl.html

[...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtzrwfqcjb.html

[U90] JS：数字数组排序
来源：http://dali.guowangkeji.top/Article/details/gtzulkoqcm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gthtaplugt.html

[U91] JS：对象键值遍历
来源：http://dali.jiagoushi.top/Article/details/gtyzmczpkh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.kuanghao11.cn/Article/details/gtnvlhokdw.html

[U92] JS：深拷贝
来源：http://dali.zdqjudy.top/Article/details/gthiiffumo.html

structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gtfrwrwtap.html

[U93] JS：模板字符串
来源：http://dali.feifeiyinyue.top/Article/details/gttsagbhpv.html

`共 ${n} 条`
来源：http://dali.gogol.net.cn/Article/details/gthjjvnqez.html

[U94] JS：箭头函数
来源：http://dali.sxryk.cn/Article/details/gtgaleiivp.html

const double = x => x * 2;
来源：http://dali.tian-w.cn/Article/details/gtquadxwsa.html

[U95] JS：Promise 包装
来源：http://dali.ehwqpu.com/Article/details/gtxqszenak.html

new Promise((resolve, reject) => {})
来源：http://dali.pengpengdd.cyou/Article/details/gtojfsgwgb.html

[U96] JS：async/await 与异常
来源：http://dali.svipenyu.cn/Article/details/gtlmswzwtm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtnpammbsp.html

[U97] JS：并发请求
来源：http://dali.ehwqpu.com/Article/details/gtaugxncun.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtnystymfg.html

[U98] JS：fetch 带 JSON
来源：http://dali.ehwqpu.com/Article/details/gtzwyxwqlf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hnqzz.top/Article/details/gtskayjxiq.html

[U99] JS：事件监听
来源：http://dali.yj20258.top/Article/details/gtbwpzzher.html

el.addEventListener("click", e => {})
来源：http://dali.0kj1m.cn/Article/details/gtmxsekche.html

[U100] JS：DOM 查询
来源：http://dali.gogol.net.cn/Article/details/gtxhfbbmfw.html

document.querySelector(".item")
来源：http://dali.cucudq.cn/Article/details/gtcrjsifrn.html

[U101] JS：classList 操作
来源：http://dali.yj202588.top/Article/details/gtjgdgttcb.html

el.classList.toggle("active")
来源：http://dali.gogol.net.cn/Article/details/gtbswhkgak.html

[U102] JS：本地存储
来源：http://dali.hysaishi.cn/Article/details/gtxxlvfasp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.havefunace.top/Article/details/gtjwwbbjmg.html

[U103] JS：定时器
来源：http://dali.bjfxy.top/Article/details/gtbpabnuqv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.andypj.xyz/Article/details/gtdjmdlxnl.html

[U104] JS：防抖
来源：http://dali.xuanzx.com/Article/details/gtyrfpawzh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtsefeyfto.html

[U105] JS：节流
来源：http://dali.haohaochexian.top/Article/details/gtrgocphes.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.daxiang520.top/Article/details/gtaubfkhql.html

[U106] JS：日期格式化
来源：http://dali.hnqzz.top/Article/details/gtaowddvit.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yueranfly.top/Article/details/gtpyminvew.html

[U107] JS：数字千分位
来源：http://dali.yongpay.top/Article/details/gtwnbykeyp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gtpnzumlwi.html

[U108] JS：随机整数
来源：http://dali.aibaodan.cn/Article/details/gthzcabfrs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.chenjidiqi.icu/Article/details/gtgaqkccql.html

[U109] JS：数组分组
来源：http://dali.yj202588.top/Article/details/gtzonjrcah.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xuetiantiany.cn/Article/details/gtowdfjcal.html

[U110] JS：数组分块
来源：http://dali.ppjwa.cn/Article/details/gthjkpianx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jiagoushi.top/Article/details/gthqotxzru.html

[U111] JS：对象转 Map
来源：http://dali.jiagoushi.top/Article/details/gttyypvnpp.html

new Map(Object.entries(obj))
来源：http://dali.zhoulong.xyz/Article/details/gtanjtoidv.html

[U112] JS：字符串补位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdhqcghw.html

"7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtolljyzdp.html

[U113] JS：正则替换全部
来源：http://dali.cheryme.top/Article/details/gtzgoankdd.html

s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtgioqhihd.html

[U114] JS：JSON 深比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijksyfxl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gtnvuvbpsb.html

[U115] JS：生成 UUID
来源：http://dali.tian-w.cn/Article/details/gtgdclknhd.html

crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gtwkxeywmn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.chenzaomai.com/Article/details/gtxyetcgei.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yongpay.top/Article/details/gtudnmkpci.html

[U117] JS：单元测试
来源：http://dali.jinghuilouyu.cn/Article/details/gtlovvkfug.html

npm i -D vitest;  npx vitest
来源：http://dali.cucudq.cn/Article/details/gtwayqmder.html

[U118] JS：开发服务器
来源：http://dali.kuanghao11.cn/Article/details/gtfmeqtzgo.html

npm i -D vite;  npx vite
来源：http://dali.zhixingplan.top/Article/details/gtictkgmkc.html

[U119] JS：生产构建
来源：http://dali.meibo888.top/Article/details/gtttsvsmsh.html

npx vite build
来源：http://dali.ivvv.top/Article/details/gtyaqdhqtb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shuidangran.top/Article/details/gtrqesumhh.html

import.meta.env.VITE_API_URL
来源：http://dali.jqgfzy.top/Article/details/gtjjvcaoiq.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtcffsffwv.html

统计汇总
来源：http://dali.zhiwuduotai.top/Article/details/gtjmwxzwdi.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtdfiejsta.html

按语言统计（条）：
来源：http://dali.shuidangran.top/Article/details/gtmjpxtbdg.html

Python ......... 252
来源：http://dali.quarkkingdee.top/Article/details/gtdzmrkkji.html

PHP ............ 252
来源：http://dali.havefunace.top/Article/details/gtgpyxfeyj.html

JavaScript ..... 252
来源：http://dali.hywenlv.cn/Article/details/gtdmsbdgur.html

TypeScript ..... 212
来源：http://dali.xuanzx.com/Article/details/gtysaydkaa.html

Java ........... 212
来源：http://dali.pycfn.com/Article/details/gtmxqkfqxg.html

Go ............. 212
来源：http://dali.yonumen.top/Article/details/gtymlyndca.html

Ruby ........... 212
来源：http://dali.guannengcc.top/Article/details/gtqoxlcmps.html

C# ............. 212
来源：http://dali.cqqwz.cn/Article/details/gtubrnlhzu.html

C .............. 30
来源：http://dali.nanxinkj.top/Article/details/gtmysixyus.html

C++ ............ 30
来源：http://dali.vqdsnc.cn/Article/details/gtgkiidobr.html

SQL ............ 90
来源：http://dali.xylfe.cn/Article/details/gtrvwmbbrc.html

Bash ........... 80
来源：http://dali.zdqjudy.top/Article/details/gtfihzcdnq.html

Kotlin ......... 15
来源：http://dali.nanxinkj.top/Article/details/gtueoslhcu.html

Swift .......... 15
来源：http://dali.bjfxy.top/Article/details/gtslyhqopa.html

Lua ............ 10
来源：http://dali.tian-w.cn/Article/details/gtobbcnnnj.html

Perl ........... 10
来源：http://dali.xuetiantiany.cn/Article/details/gtksgzqwej.html

Scala .......... 10
来源：http://dali.quarkkingdee.top/Article/details/gtfwnibooy.html

------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gtiatppjwm.html

合计 ........... 2106 条
来源：http://dali.guowangkeji.top/Article/details/gtnklquvpk.html

按章节统计：
来源：http://dali.chenzaomai.com/Article/details/gtgkqtqrwa.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.wangdashe.top/Article/details/gtajculydj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gtlrtdfkhd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jqgfzy.top/Article/details/gtfcumdymf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sufxvd.cn/Article/details/gtzqviqlce.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.daxiang520.top/Article/details/gtvcwtrvxy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.gotoacloud.top/Article/details/gtjurkawzy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yanxiufei.cn/Article/details/gtyzmewznc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.wangshuangyany.cn/Article/details/gtymgmyiiv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gtdtrvqfqw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.dianchejie.cn/Article/details/gtckocijjd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtauuarkpt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtnyhnaykc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gtebnwnxei.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.smart0.xyz/Article/details/gtebcvefpt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.redwolf501.top/Article/details/gtshjopgen.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtcoogrqqh.html

Q SQL 专题                              90
来源：http://dali.pengpengdd.cyou/Article/details/gtutwzktzn.html

R Bash 专题                             80
来源：http://dali.yanxiufei.cn/Article/details/gtpbvrgezv.html

S C / C++ 专题                          60
来源：http://dali.xziqi.cn/Article/details/gtnlnberat.html

T 其他语言补充                          60
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmpgcpzi.html

U 高频实用片段                         120
来源：http://dali.gotoacloud.top/Article/details/gtieyllhxm.html

------------------------------------
来源：http://dali.sweek.top/Article/details/gtsahrzdey.html

合计                                  2106 条
来源：http://dali.xziqi.cn/Article/details/gtadexmntp.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsravoblu.html

使用提醒
来源：http://dali.svipenyu.cn/Article/details/gtehdwpqdp.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtlrrjepjk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yongpay.top/Article/details/gtwmvsmifs.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yuanzhike.top/Article/details/gtzdyguvay.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yueranfly.top/Article/details/gtwkgfgwev.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jinqigufen.top/Article/details/gthsefviav.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.aizwys.cn/Article/details/gtbabcsast.html

—— 文件结束 ——
来源：http://dali.sweek.top/Article/details/gtzpimdzle.html


<!-- 参考信息 -->