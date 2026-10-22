代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yanxiufei.cn/Article/details/gt2dnuarqrn.html

[T59] Scala：循环
来源：http://dali.daria6918.cn/Article/details/gt2ryxobjam.html

for (i <- 1 to 10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gt2yuxfrhvc.html

[T60] Scala：折叠
来源：http://dali.hnxiangtu.top/Article/details/gt2nlppquqg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhoulong.xyz/Article/details/gt2djcmfbco.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2iufzogfy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xylfe.cn/Article/details/gt2djetsmnz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2dlxujkne.html

[U01] Py：创建虚拟环境
来源：http://dali.xziqi.cn/Article/details/gt2nzhztgyt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xziqi.cn/Article/details/gt2rtmduerv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.kuanghao11.cn/Article/details/gt2upqqfear.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nanxinkj.top/Article/details/gt2zykupwfo.html

[U03] Py：加载 .env 配置
来源：http://dali.zhixingplan.top/Article/details/gt2jddbnitq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yonumen.top/Article/details/gt2psfcbwge.html

[U04] Py：变量调试打印
来源：http://dali.gotoacloud.top/Article/details/gt2ppsafeix.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.wangshuangyany.cn/Article/details/gt2mzgmecdn.html

[U05] Py：列表去重且保序
来源：http://dali.fengsongda.top/Article/details/gt2qoccigjg.html

list(dict.fromkeys(arr))
来源：http://dali.yj202588.top/Article/details/gt2droqbhlv.html

[U06] Py：合并两个字典
来源：http://dali.xuanzx.com/Article/details/gt2dkznbbwz.html

{**a, **b}
来源：http://dali.quarkkingdee.top/Article/details/gt2hifzrqab.html

[U07] Py：反转字典键值
来源：http://dali.sysykeji.top/Article/details/gt2uodycfeh.html

{v: k for k, v in d.items()}
来源：http://dali.hammf.cn/Article/details/gt2wpiwxbvd.html

[U08] Py：展平二维列表
来源：http://dali.quarkkingdee.top/Article/details/gt2soutween.html

[y for x in nested for y in x]
来源：http://dali.zycfv.cn/Article/details/gt2huwyzmln.html

[U09] Py：字典取最大值的键
来源：http://dali.jlsjyb.cn/Article/details/gt2ixqvskzl.html

max(d, key=d.get)
来源：http://dali.gaohongyu789.top/Article/details/gt2jvntefnz.html

[U10] Py：按值排序字典
来源：http://dali.ivvv.top/Article/details/gt2uyynfufe.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hnxiangtu.top/Article/details/gt2owubkkew.html

[U11] Py：生成器表达式
来源：http://dali.316326.xyz/Article/details/gt2tdnthgjg.html

(x * 2 for x in arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctjcuhix.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.kuanghao11.cn/Article/details/gt2ltuaddqa.html

Counter(arr).most_common(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lslqhilh.html

[U13] Py：固定长度队列
来源：http://dali.kuanghao11.cn/Article/details/gt2bunycvyg.html

deque(maxlen=10)
来源：http://dali.pycfn.com/Article/details/gt2jeiunpmm.html

[U14] Py：分组收集到列表
来源：http://dali.yonumen.top/Article/details/gt2lvexpjbr.html

defaultdict(list)
来源：http://dali.nwbrower.top/Article/details/gt2nfzdhmva.html

[U15] Py：高精度计时
来源：http://dali.yanxiufei.cn/Article/details/gt2dyxunlng.html

t = time.perf_counter()
来源：http://dali.pengpengdd.cyou/Article/details/gt2pwepovmh.html

[U16] Py：命令行参数解析
来源：http://dali.zhiwuduotai.top/Article/details/gt2xnzklxre.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shzxlz.cn/Article/details/gt2eweazmxq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfhaewx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guowangkeji.top/Article/details/gt2nfozyzxd.html

[U18] Py：预编译正则
来源：http://dali.hysaishi.cn/Article/details/gt2bkmcjklv.html

pat = re.compile(r"\d+")
来源：http://dali.andypj.xyz/Article/details/gt2didzfcxg.html

[U19] Py：正则替换带回调
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qvfdsspy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuxming.cn/Article/details/gt2xieqgucy.html

[U20] Py：缓存函数结果
来源：http://dali.shanyushiyangtech.top/Article/details/gt2exlnzole.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jqgufenzy.top/Article/details/gt2sqrusmbz.html

[U21] Py：自定义上下文管理器
来源：http://dali.smart0.xyz/Article/details/gt2lpwpkuyd.html

@contextlib.contextmanager
来源：http://dali.nwbrower.top/Article/details/gt2gmlcpcrv.html

[U22] Py：矩阵转置
来源：http://dali.yuanzhike.top/Article/details/gt2jgfflgme.html

list(zip(*m))
来源：http://dali.havefunace.top/Article/details/gt2ivuunkbp.html

[U23] Py：分块读取大文件
来源：http://dali.jqgufenzy.top/Article/details/gt2lxamsdgs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.kuanghao11.cn/Article/details/gt2ggkrhoad.html

[U24] Py：路径操作
来源：http://dali.birdmap.top/Article/details/gt2lxtdkpvl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gt2wymaukrp.html

[U25] Py：CSV 按字典读
来源：http://dali.kuanghao11.cn/Article/details/gt2kkledjpa.html

csv.DictReader(f)
来源：http://dali.shzxlz.cn/Article/details/gt2nrbfvrdj.html

[U26] Py：并发下载
来源：http://dali.tanke756.top/Article/details/gt2frtevdps.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.quarkkingdee.top/Article/details/gt2mzyrrvyd.html

[U27] Py：异步 HTTP
来源：http://dali.fengsongda.top/Article/details/gt2tpsftzuj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gzhubu.top/Article/details/gt2ellmekhm.html

[U28] Py：类型别名
来源：http://dali.daria6918.cn/Article/details/gt2gkphtien.html

UserId = int
来源：http://dali.cucudq.cn/Article/details/gt2zvuczlzj.html

[U29] Py：属性校验
来源：http://dali.ppjwa.cn/Article/details/gt2dkhkhycg.html

@property 与 @x.setter 配合
来源：http://dali.sufxvd.cn/Article/details/gt2mjrqrlxd.html

[U30] Py：数据类
来源：http://dali.ppjwa.cn/Article/details/gt2ofhaamxl.html

@dataclass(slots=True)
来源：http://dali.sysykeji.top/Article/details/gt2vftsbbnc.html

[U31] Py：单测
来源：http://dali.haohaochexian.top/Article/details/gt2cmgmqxof.html

python -m pytest -q
来源：http://dali.hammf.cn/Article/details/gt2mbgvhgru.html

[U32] Py：代码格式化
来源：http://dali.guannengcc.top/Article/details/gt2zkfvxpqu.html

ruff format . && ruff check --fix .
来源：http://dali.zhixingplan.top/Article/details/gt2ciasiusm.html

[U33] Py：打包发布
来源：http://dali.shangyingyoupin.top/Article/details/gt2dtmlripq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.meibo888.top/Article/details/gt2exggppbi.html

[U34] Py：判断编码
来源：http://dali.nwbrower.top/Article/details/gt2oqdwnfvn.html

chardet.detect(raw)
来源：http://dali.cucudq.cn/Article/details/gt2xytvpxid.html

[U35] Py：发送邮件
来源：http://dali.zycfv.cn/Article/details/gt2dtsotapb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.andypj.xyz/Article/details/gt2gbhbefmp.html

[U36] Py：定时任务
来源：http://dali.c1oappe.top/Article/details/gt2jfljwqac.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhongyouzk.top/Article/details/gt2vjsasngi.html

[U37] Py：读写 Excel
来源：http://dali.cashguo.top/Article/details/gt2dxsowdpb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.0kj1m.cn/Article/details/gt2iqfecpya.html

[U38] Py：获取脚本所在目录
来源：http://dali.xylfe.cn/Article/details/gt2fhgpctfj.html

Path(__file__).resolve().parent
来源：http://dali.yvedp.cn/Article/details/gt2qevharsh.html

[U39] Py：判断是否在交互环境
来源：http://dali.yueranfly.top/Article/details/gt2fekucske.html

sys.stdout.isatty()
来源：http://dali.zhoulong.xyz/Article/details/gt2finadorl.html

[U40] Py：打印到标准错误
来源：http://dali.yj202588.top/Article/details/gt2hisqvmdk.html

print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fixwrdwr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yuxming.cn/Article/details/gt2kuiqrdvz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhongyouzk.top/Article/details/gt2engzoeyc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yuxming.cn/Article/details/gt2nsdjtsps.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ehwqpu.com/Article/details/gt2ejdekfbl.html

[U43] PHP：声明命名空间
来源：http://dali.c1oappe.top/Article/details/gt2dewbsdrx.html

namespace App\Http;
来源：http://dali.ydzc1.top/Article/details/gt2tqsvfjbs.html

[U44] PHP：开启严格类型
来源：http://dali.hywenlv.cn/Article/details/gt2soibgcul.html

declare(strict_types=1);
来源：http://dali.jlsjyb.cn/Article/details/gt2ixcjaxuv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hnqzz.top/Article/details/gt2kpttgenc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lipkxvmm.html

[U46] PHP：可空类型
来源：http://dali.ivvv.top/Article/details/gt2szdsczwx.html

?string $name = null
来源：http://dali.9152youxi.cn/Article/details/gt2xgkqvcof.html

[U47] PHP：联合类型
来源：http://dali.ehwqpu.com/Article/details/gt2foipfohj.html

int|string $id
来源：http://dali.xinyue.icu/Article/details/gt2agfbgbyb.html

[U48] PHP：纯枚举
来源：http://dali.hysaishi.cn/Article/details/gt2hcgbzqzl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.daria6918.cn/Article/details/gt2mohnyiot.html

[U49] PHP：只读属性
来源：http://dali.dianchejie.cn/Article/details/gt2ljiemdxp.html

public readonly string $name
来源：http://dali.yj202588.top/Article/details/gt2sksrjoas.html

[U50] PHP：构造器属性提升
来源：http://dali.ppjwa.cn/Article/details/gt2tfklxddj.html

public function __construct(private int $id) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2iktqfjyg.html

[U51] PHP：数组解构
来源：http://dali.redwolf501.top/Article/details/gt2yfcinbet.html

[$a, $b] = $arr;
来源：http://dali.tanke756.top/Article/details/gt2qcwqzbzl.html

[U52] PHP：箭头函数
来源：http://dali.nanxinkj.top/Article/details/gt2mhtrjnqx.html

$double = fn($x) => $x * 2;
来源：http://dali.yj202588.top/Article/details/gt2rinboeth.html

[U53] PHP：空合并运算符
来源：http://dali.316326.xyz/Article/details/gt2tvuuonjc.html

$v = $a ?? $b ?? "default";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxykqgyh.html

[U54] PHP：空安全调用
来源：http://dali.smart0.xyz/Article/details/gt2pjousxgk.html

$obj?->method()
来源：http://dali.bjfxy.top/Article/details/gt2rhzpyjze.html

[U55] PHP：match 表达式
来源：http://dali.svipenyu.cn/Article/details/gt2vsccklop.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.chenjidiqi.icu/Article/details/gt2ccnnkfpd.html

[U56] PHP：命名参数
来源：http://dali.quarkkingdee.top/Article/details/gt2zhglwzfw.html

f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gt2ifbzslzy.html

[U57] PHP：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gt2nzsfqvbu.html

"值: {$a}"
来源：http://dali.aizwys.cn/Article/details/gt2yyaldtdl.html

[U58] PHP：数组三件套
来源：http://dali.chenlongwang.top/Article/details/gt2cxndjtxj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tian-w.cn/Article/details/gt2tollrbnb.html

[U59] PHP：自定义排序
来源：http://dali.aibaodan.cn/Article/details/gt2wckrdvyy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sufxvd.cn/Article/details/gt2mwdtwgtc.html

[U60] PHP：JSON 编解码
来源：http://dali.jinqigfzy.top/Article/details/gt2busrbkhj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.haohaochexian.top/Article/details/gt2vajxwjea.html

[U61] PHP：正则
来源：http://dali.sysykeji.top/Article/details/gt2twgcgwbl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2dhxnfiay.html

[U62] PHP：日期对象
来源：http://dali.jianghu66.top/Article/details/gt2rzsfdkbq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.dashuyun.cn/Article/details/gt2humnykft.html

[U63] PHP：文件读写
来源：http://dali.feifeiyinyue.top/Article/details/gt2edcobtjf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yj202588.top/Article/details/gt2iqxgicdw.html

[U64] PHP：目录遍历
来源：http://dali.jinqigufen.top/Article/details/gt2mfjswjjz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nanxinkj.top/Article/details/gt2epploiip.html

[U65] PHP：会话
来源：http://dali.chenzaomai.com/Article/details/gt2wnfjghpb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2ifrryyot.html

[U66] PHP：设置 Cookie
来源：http://dali.hongshengwenyu.top/Article/details/gt2fbhnddzf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yvedp.cn/Article/details/gt2cgpexmkd.html

[U67] PHP：处理文件上传
来源：http://dali.yj20258888.top/Article/details/gt2nzpxpiyo.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yuanzhike.top/Article/details/gt2cyevhmgc.html

[U68] PHP：PDO 连接
来源：http://dali.chenjidiqi.icu/Article/details/gt2ecuqgvvc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.wangshuangyany.cn/Article/details/gt2upyzkmco.html

[U69] PHP：PDO 预处理
来源：http://dali.guannengcc.top/Article/details/gt2qdimajnx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.svipenyu.cn/Article/details/gt2rulimxcp.html

[U70] PHP：PDO 事务
来源：http://dali.tian-w.cn/Article/details/gt2bvgnyfkm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cdnleiting.top/Article/details/gt2udymmwor.html

[U71] PHP：抛出异常
来源：http://dali.ybcxt.top/Article/details/gt2xhymodxs.html

throw new RuntimeException("失败", 500);
来源：http://dali.nanxinkj.top/Article/details/gt2tmynzvbf.html

[U72] PHP：写错误日志
来源：http://dali.yueranfly.top/Article/details/gt2lsildrgq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gzhubu.top/Article/details/gt2vtcqtnqy.html

[U73] PHP：读取 ini 配置
来源：http://dali.yj20258.top/Article/details/gt2dzvaovts.html

parse_ini_file("config.ini", true)
来源：http://dali.yuxming.cn/Article/details/gt2eaokonnz.html

[U74] PHP：读取环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2vctkxhkl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.chenlongwang.top/Article/details/gt2hhojgyxq.html

[U75] PHP：依赖注入
来源：http://dali.vqdsnc.cn/Article/details/gt2ysrdqypw.html

composer require psr/container
来源：http://dali.shuidangran.top/Article/details/gt2piybyhoi.html

[U76] PHP：简单路由
来源：http://dali.daxiang520.top/Article/details/gt2qfjiqoha.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xxqisiod.html

[U77] PHP：模板渲染
来源：http://dali.cucudq.cn/Article/details/gt2szcbjoni.html

composer require twig/twig
来源：http://dali.guannengcc.top/Article/details/gt2zyclqkju.html

[U78] PHP：单元测试
来源：http://dali.dianchejie.cn/Article/details/gt2jzhpydlg.html

composer require --dev phpunit/phpunit
来源：http://dali.9152youxi.cn/Article/details/gt2stjbmjbg.html

[U79] PHP：静态分析
来源：http://dali.sxryk.cn/Article/details/gt2wpepwgvw.html

composer require --dev phpstan/phpstan
来源：http://dali.cashguo.top/Article/details/gt2hhnuccni.html

[U80] PHP：代码规范修复
来源：http://dali.sufxvd.cn/Article/details/gt2ovvxfqyg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yueranfly.top/Article/details/gt2bntumeuw.html

[U81] JS：初始化项目
来源：http://dali.hnxiangtu.top/Article/details/gt2gtpeogsl.html

npm init -y;  npm i express
来源：http://dali.birdmap.top/Article/details/gt2qqrortoo.html

[U82] JS：package.json 脚本
来源：http://dali.316326.xyz/Article/details/gt2xjqszcdf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yonumen.top/Article/details/gt2wfspkdvt.html

[U83] JS：ES Module 导入导出
来源：http://dali.0kj1m.cn/Article/details/gt2ecadilws.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.0kj1m.cn/Article/details/gt2wojtlueu.html

[U84] JS：CommonJS 写法
来源：http://dali.jinqigfzy.top/Article/details/gt2tmxttcqz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhixingplan.top/Article/details/gt2tntkntpb.html

[U85] JS：可选链
来源：http://dali.redwolf501.top/Article/details/gt2okidvlch.html

a?.b?.c
来源：http://dali.shuidangran.top/Article/details/gt2lnziwufa.html

[U86] JS：空值合并
来源：http://dali.sufxvd.cn/Article/details/gt2vcelgadx.html

a ?? b
来源：http://dali.daxiang520.top/Article/details/gt2qzpheila.html

[U87] JS：解构默认值
来源：http://dali.nanxinkj.top/Article/details/gt2wdxtesrk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hongshengwenyu.top/Article/details/gt2xkveifvi.html

[U88] JS：对象展开合并
来源：http://dali.ppjwa.cn/Article/details/gt2djzvsixh.html

{ ...a, ...b }
来源：http://dali.yonumen.top/Article/details/gt2rpagembw.html

[U89] JS：数组去重
来源：http://dali.shzxlz.cn/Article/details/gt2qltayrsk.html

[...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hilhygkk.html

[U90] JS：数字数组排序
来源：http://dali.pycfn.com/Article/details/gt2dbidavim.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gt2pogcmqfq.html

[U91] JS：对象键值遍历
来源：http://dali.sweek.top/Article/details/gt2hiezpxki.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.nwbrower.top/Article/details/gt2tcohewyw.html

[U92] JS：深拷贝
来源：http://dali.jiagoushi.top/Article/details/gt2pyulhayc.html

structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2pavubptv.html

[U93] JS：模板字符串
来源：http://dali.9152youxi.cn/Article/details/gt2cwaqcpjq.html

`共 ${n} 条`
来源：http://dali.zhoulong.xyz/Article/details/gt2gjwfphzo.html

[U94] JS：箭头函数
来源：http://dali.haohaochexian.top/Article/details/gt2wdmqmewn.html

const double = x => x * 2;
来源：http://dali.nanxuanxn.top/Article/details/gt2zlyxhmaq.html

[U95] JS：Promise 包装
来源：http://dali.gogol.net.cn/Article/details/gt2hkwwglsj.html

new Promise((resolve, reject) => {})
来源：http://dali.cdnleiting.top/Article/details/gt2eyjnlkea.html

[U96] JS：async/await 与异常
来源：http://dali.ppjwa.cn/Article/details/gt2aojhlsxf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gt2dtycvgwm.html

[U97] JS：并发请求
来源：http://dali.nwbrower.top/Article/details/gt2xiubiskr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gt2okomjrbf.html

[U98] JS：fetch 带 JSON
来源：http://dali.tanke756.top/Article/details/gt2lzrtezfn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.daxiang520.top/Article/details/gt2ptuhjlkk.html

[U99] JS：事件监听
来源：http://dali.hnxiangtu.top/Article/details/gt2yvkeewpr.html

el.addEventListener("click", e => {})
来源：http://dali.gogol.net.cn/Article/details/gt2bpwjmsrg.html

[U100] JS：DOM 查询
来源：http://dali.haohaochexian.top/Article/details/gt2nvjswmnb.html

document.querySelector(".item")
来源：http://dali.cdnleiting.top/Article/details/gt2kgndxwva.html

[U101] JS：classList 操作
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjpbbfpw.html

el.classList.toggle("active")
来源：http://dali.hnxiangtu.top/Article/details/gt2pibblkbr.html

[U102] JS：本地存储
来源：http://dali.feifeiyinyue.top/Article/details/gt2ilymeivo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jlsjyb.cn/Article/details/gt2azhhotpd.html

[U103] JS：定时器
来源：http://dali.yongpay.top/Article/details/gt2nuyhmofj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.daxiang520.top/Article/details/gt2lnyyydez.html

[U104] JS：防抖
来源：http://dali.hysaishi.cn/Article/details/gt2ybkrmdrr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gt2fvaysnpj.html

[U105] JS：节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umbykumy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.kuanghao11.cn/Article/details/gt2ormgvxbm.html

[U106] JS：日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gt2cfowjcgi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gzhubu.top/Article/details/gt2bfsnrvrd.html

[U107] JS：数字千分位
来源：http://dali.kuanghao11.cn/Article/details/gt2skuhuxwz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gt2cwxgftlt.html

[U108] JS：随机整数
来源：http://dali.hywenlv.cn/Article/details/gt2byhpspmz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hywenlv.cn/Article/details/gt2kunjqibf.html

[U109] JS：数组分组
来源：http://dali.pycfn.com/Article/details/gt2zvxispnc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.havefunace.top/Article/details/gt2bizxyorq.html

[U110] JS：数组分块
来源：http://dali.jyoumei.cn/Article/details/gt2ecdajfba.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hysaishi.cn/Article/details/gt2popiqieb.html

[U111] JS：对象转 Map
来源：http://dali.guowangkeji.top/Article/details/gt2uornfsyl.html

new Map(Object.entries(obj))
来源：http://dali.hywenlv.cn/Article/details/gt2dgpcunvr.html

[U112] JS：字符串补位
来源：http://dali.jinqigfzy.top/Article/details/gt2wghcfmtx.html

"7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gt2vreabkdf.html

[U113] JS：正则替换全部
来源：http://dali.cashguo.top/Article/details/gt2yagzuyie.html

s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2hujyhhqd.html

[U114] JS：JSON 深比较
来源：http://dali.nwbrower.top/Article/details/gt2ndyndycj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xylfe.cn/Article/details/gt2rpmmthcx.html

[U115] JS：生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gt2bowxlhfw.html

crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gt2scwuemle.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.birdmap.top/Article/details/gt2femmvius.html

/** @param {string} name */ function f(name) {}
来源：http://dali.andypj.xyz/Article/details/gt2cmqudqwf.html

[U117] JS：单元测试
来源：http://dali.guannengcc.top/Article/details/gt2yjcjvdbw.html

npm i -D vitest;  npx vitest
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ewhwmpyv.html

[U118] JS：开发服务器
来源：http://dali.smart0.xyz/Article/details/gt2uoialggt.html

npm i -D vite;  npx vite
来源：http://dali.yvedp.cn/Article/details/gt2qyluondc.html

[U119] JS：生产构建
来源：http://dali.daria6918.cn/Article/details/gt2bjbjtuoy.html

npx vite build
来源：http://dali.jinqigufen.top/Article/details/gt2bzdytdfu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.redwolf501.top/Article/details/gt2nxvtmbjh.html

import.meta.env.VITE_API_URL
来源：http://dali.shuidangran.top/Article/details/gt2mjvaqjzv.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2qomooljr.html

统计汇总
来源：http://dali.hfpthk.cn/Article/details/gt2mjjizxqc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2ptitvmbn.html

按语言统计（条）：
来源：http://dali.shangyingyoupin.top/Article/details/gt2qeaajkzi.html

Python ......... 252
来源：http://dali.pycfn.com/Article/details/gt2xvlrjksr.html

PHP ............ 252
来源：http://dali.xinyue.icu/Article/details/gt2fuiliprr.html

JavaScript ..... 252
来源：http://dali.svipenyu.cn/Article/details/gt2hbcwuchc.html

TypeScript ..... 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fnwdppzd.html

Java ........... 212
来源：http://dali.daxiang520.top/Article/details/gt2tvdqqsqs.html

Go ............. 212
来源：http://dali.zycfv.cn/Article/details/gt2vugcxoaq.html

Ruby ........... 212
来源：http://dali.yanxiufei.cn/Article/details/gt2ycwcpmec.html

C# ............. 212
来源：http://dali.tianlin.xyz/Article/details/gt2xslatqdv.html

C .............. 30
来源：http://dali.haohaochexian.top/Article/details/gt2sqavoraq.html

C++ ............ 30
来源：http://dali.yj20258.top/Article/details/gt2oxevroez.html

SQL ............ 90
来源：http://dali.zycfv.cn/Article/details/gt2qtvzbuvm.html

Bash ........... 80
来源：http://dali.gogol.net.cn/Article/details/gt2omolbupd.html

Kotlin ......... 15
来源：http://dali.shangyingyoupin.top/Article/details/gt2vdmdppxc.html

Swift .......... 15
来源：http://dali.birdmap.top/Article/details/gt2qlnbcsib.html

Lua ............ 10
来源：http://dali.daria6918.cn/Article/details/gt2qxhpwdis.html

Perl ........... 10
来源：http://dali.aizwys.cn/Article/details/gt2iqsbnhxx.html

Scala .......... 10
来源：http://dali.sxryk.cn/Article/details/gt2coalvuev.html

------------------------------------
来源：http://dali.yj20258.top/Article/details/gt2zkjhdoiv.html

合计 ........... 2106 条
来源：http://dali.yueranfly.top/Article/details/gt2mxdushwf.html

按章节统计：
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rieqqkzj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.aibaodan.cn/Article/details/gt2lksojdhg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gt2uzhshxcs.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gt2ptefmlip.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vzehjwif.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ybcxt.top/Article/details/gt2zuvbcsbd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzmnobx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gt2atnmelix.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cqqwz.cn/Article/details/gt2agbtyyfj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gt2asdbsxzs.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jqgfzy.top/Article/details/gt2wvuwvgif.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gt2hqpwwlof.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gt2qhzkollc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gt2vvnjvtvv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xuetiantiany.cn/Article/details/gt2nkqggvfo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zdqjudy.top/Article/details/gt2wiuxzvii.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gt2bpmjnpbv.html

Q SQL 专题                              90
来源：http://dali.zhixingplan.top/Article/details/gt2lcdigeyp.html

R Bash 专题                             80
来源：http://dali.yueranfly.top/Article/details/gt2nhxwvpuj.html

S C / C++ 专题                          60
来源：http://dali.0kj1m.cn/Article/details/gt2gkhfvieo.html

T 其他语言补充                          60
来源：http://dali.dianchejie.cn/Article/details/gt2donyatge.html

U 高频实用片段                         120
来源：http://dali.ydzc1.top/Article/details/gt2akkazjrp.html

------------------------------------
来源：http://dali.yvedp.cn/Article/details/gt2cagszvsp.html

合计                                  2106 条
来源：http://dali.gaohongyu789.top/Article/details/gt2trppyuvf.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gt2labauhcm.html

使用提醒
来源：http://dali.havefunace.top/Article/details/gt2bbazroqp.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gt2oiursyun.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.dashuyun.cn/Article/details/gt2ikdytouf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jahewsqp.html


<!-- 参考信息 -->