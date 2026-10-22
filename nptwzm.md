代发 wailian999

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinqigufen.top/Article/details/gt2bltblrgb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2ecrvvyyc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2itjhtlnr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2oqeajsiz.html

[U01] Py：创建虚拟环境
来源：http://dali.jiagoushi.top/Article/details/gt2zehzfkho.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenzaomai.com/Article/details/gt2ptbugtxt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dashuyun.cn/Article/details/gt2bdfisnhq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tian-w.cn/Article/details/gt2bfilnuwz.html

[U03] Py：加载 .env 配置
来源：http://dali.yvedp.cn/Article/details/gt2mcuyloqv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.daria6918.cn/Article/details/gt2tuszxnlx.html

[U04] Py：变量调试打印
来源：http://dali.jianghu66.top/Article/details/gt2nvjymbil.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hongshengwenyu.top/Article/details/gt2wjmkcmgr.html

[U05] Py：列表去重且保序
来源：http://dali.gotoacloud.top/Article/details/gt2nsunnvle.html

list(dict.fromkeys(arr))
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxgknmlk.html

[U06] Py：合并两个字典
来源：http://dali.yangfankeji.com/Article/details/gt2lirnmarm.html

{**a, **b}
来源：http://dali.iojbl.cn/Article/details/gt2mfxzimdf.html

[U07] Py：反转字典键值
来源：http://dali.yanxiufei.cn/Article/details/gt2bbdgxduy.html

{v: k for k, v in d.items()}
来源：http://dali.dashuyun.cn/Article/details/gt2mhphpolm.html

[U08] Py：展平二维列表
来源：http://dali.9152youxi.cn/Article/details/gt2thccuobo.html

[y for x in nested for y in x]
来源：http://dali.hywenlv.cn/Article/details/gt2glzfkqph.html

[U09] Py：字典取最大值的键
来源：http://dali.hywenlv.cn/Article/details/gt2hkgzsrcq.html

max(d, key=d.get)
来源：http://dali.aizwys.cn/Article/details/gt2ofdwhwix.html

[U10] Py：按值排序字典
来源：http://dali.ehwqpu.com/Article/details/gt2iyxsndif.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nklfzupn.html

[U11] Py：生成器表达式
来源：http://dali.daxiang520.top/Article/details/gt2uogmlmja.html

(x * 2 for x in arr)
来源：http://dali.cqqwz.cn/Article/details/gt2ynxvteyg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jianghu66.top/Article/details/gt2rrundulr.html

Counter(arr).most_common(3)
来源：http://dali.fengsongda.top/Article/details/gt2zvjjnsuh.html

[U13] Py：固定长度队列
来源：http://dali.zhoulong.xyz/Article/details/gt2tnjjddbx.html

deque(maxlen=10)
来源：http://dali.ehwqpu.com/Article/details/gt2yuqbmijs.html

[U14] Py：分组收集到列表
来源：http://dali.ehwqpu.com/Article/details/gt2lblbgkge.html

defaultdict(list)
来源：http://dali.yuanzhike.top/Article/details/gt2vjhaenyp.html

[U15] Py：高精度计时
来源：http://dali.guannengcc.top/Article/details/gt2ullyovle.html

t = time.perf_counter()
来源：http://dali.fzhhl.top/Article/details/gt2lmohwpyn.html

[U16] Py：命令行参数解析
来源：http://dali.meibo888.top/Article/details/gt2eludrvrp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ybcxt.top/Article/details/gt2szlebzrz.html

[U17] Py：初始化日志
来源：http://dali.chenjidiqi.icu/Article/details/gt2lnjvxvqk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.wangdashe.top/Article/details/gt2qfgbggcr.html

[U18] Py：预编译正则
来源：http://dali.guannengcc.top/Article/details/gt2oihftuej.html

pat = re.compile(r"\d+")
来源：http://dali.jlsjyb.cn/Article/details/gt2ljabcwuu.html

[U19] Py：正则替换带回调
来源：http://dali.daria6918.cn/Article/details/gt2ayvqdnav.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jqgfzy.top/Article/details/gt2fnwympuk.html

[U20] Py：缓存函数结果
来源：http://dali.ehwqpu.com/Article/details/gt2dkjtcyzk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zdqjudy.top/Article/details/gt2tugefist.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinghuilouyu.cn/Article/details/gt2funwefcr.html

@contextlib.contextmanager
来源：http://dali.smart0.xyz/Article/details/gt2teiorylq.html

[U22] Py：矩阵转置
来源：http://dali.xylfe.cn/Article/details/gt2zmbsfuqh.html

list(zip(*m))
来源：http://dali.kuanghao11.cn/Article/details/gt2zdfyrfio.html

[U23] Py：分块读取大文件
来源：http://dali.xinyue.icu/Article/details/gt2hbhsqbsn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gaohongyu789.top/Article/details/gt2xkplhxoa.html

[U24] Py：路径操作
来源：http://dali.yj20258888.top/Article/details/gt2yykviegq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gt2yxsmfdfp.html

[U25] Py：CSV 按字典读
来源：http://dali.c1oappe.top/Article/details/gt2ejqpkqth.html

csv.DictReader(f)
来源：http://dali.guowangkeji.top/Article/details/gt2mjieiieo.html

[U26] Py：并发下载
来源：http://dali.xziqi.cn/Article/details/gt2kcosxbmp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sweek.top/Article/details/gt2btmkefdd.html

[U27] Py：异步 HTTP
来源：http://dali.nwbrower.top/Article/details/gt2jkexkxas.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shuidangran.top/Article/details/gt2dnyjvdrk.html

[U28] Py：类型别名
来源：http://dali.xuetiantiany.cn/Article/details/gt2vcauzdvp.html

UserId = int
来源：http://dali.andypj.xyz/Article/details/gt2zmfizuov.html

[U29] Py：属性校验
来源：http://dali.vqdsnc.cn/Article/details/gt2lkvchrkx.html

@property 与 @x.setter 配合
来源：http://dali.kuanghao11.cn/Article/details/gt2njaemgaf.html

[U30] Py：数据类
来源：http://dali.guannengcc.top/Article/details/gt2qtwbnjnb.html

@dataclass(slots=True)
来源：http://dali.yueranfly.top/Article/details/gt2kxjqqlrf.html

[U31] Py：单测
来源：http://dali.tanke756.top/Article/details/gt2hdwcuqfl.html

python -m pytest -q
来源：http://dali.zhongyouzk.top/Article/details/gt2kwsdeuua.html

[U32] Py：代码格式化
来源：http://dali.jlsjyb.cn/Article/details/gt2lcbcsjbf.html

ruff format . && ruff check --fix .
来源：http://dali.yueranfly.top/Article/details/gt2drefbric.html

[U33] Py：打包发布
来源：http://dali.cucudq.cn/Article/details/gt2cdigtsbj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jqgufenzy.top/Article/details/gt2kmqmktrw.html

[U34] Py：判断编码
来源：http://dali.yvedp.cn/Article/details/gt2excdumrh.html

chardet.detect(raw)
来源：http://dali.dashuyun.cn/Article/details/gt2uydazzoo.html

[U35] Py：发送邮件
来源：http://dali.aizwys.cn/Article/details/gt2vdofpqbj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ehwqpu.com/Article/details/gt2zxffbcya.html

[U36] Py：定时任务
来源：http://dali.jqgfzy.top/Article/details/gt2sikzqjwv.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinqigufen.top/Article/details/gt2snvwnjuz.html

[U37] Py：读写 Excel
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yscevdhw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yueranfly.top/Article/details/gt2njhgsotq.html

[U38] Py：获取脚本所在目录
来源：http://dali.wangdashe.top/Article/details/gt2pxduliqd.html

Path(__file__).resolve().parent
来源：http://dali.feifeiyinyue.top/Article/details/gt2vqjpsldc.html

[U39] Py：判断是否在交互环境
来源：http://dali.sysykeji.top/Article/details/gt2iyjhrdit.html

sys.stdout.isatty()
来源：http://dali.yuanzhike.top/Article/details/gt2japtfufu.html

[U40] Py：打印到标准错误
来源：http://dali.yj20258.top/Article/details/gt2kxrmpjdn.html

print("err", file=sys.stderr)
来源：http://dali.ivvv.top/Article/details/gt2vyfspbdr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenzaomai.com/Article/details/gt2vsvmivea.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.pycfn.com/Article/details/gt2pqmygift.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xuetiantiany.cn/Article/details/gt2rmdutozh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jqgfzy.top/Article/details/gt2vngiuhil.html

[U43] PHP：声明命名空间
来源：http://dali.fengsongda.top/Article/details/gt2kcuclcqu.html

namespace App\Http;
来源：http://dali.xziqi.cn/Article/details/gt2unjltlqo.html

[U44] PHP：开启严格类型
来源：http://dali.svipenyu.cn/Article/details/gt2dypviirt.html

declare(strict_types=1);
来源：http://dali.birdmap.top/Article/details/gt2vqbqnwge.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2zcqzgxtz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxuiepzj.html

[U46] PHP：可空类型
来源：http://dali.zhixingplan.top/Article/details/gt2pucuurpq.html

?string $name = null
来源：http://dali.ehwqpu.com/Article/details/gt2jhrrcczx.html

[U47] PHP：联合类型
来源：http://dali.hywenlv.cn/Article/details/gt2mvjjsffm.html

int|string $id
来源：http://dali.cdnleiting.top/Article/details/gt2tmtwcgqj.html

[U48] PHP：纯枚举
来源：http://dali.yj20258888.top/Article/details/gt2moarcppc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2txltnvab.html

[U49] PHP：只读属性
来源：http://dali.ybcxt.top/Article/details/gt2hoolceyn.html

public readonly string $name
来源：http://dali.0kj1m.cn/Article/details/gt2luiifjgh.html

[U50] PHP：构造器属性提升
来源：http://dali.xinyue.icu/Article/details/gt2snvgguix.html

public function __construct(private int $id) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2mlejjjvg.html

[U51] PHP：数组解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xfudsbke.html

[$a, $b] = $arr;
来源：http://dali.ydzc1.top/Article/details/gt2uypsowvf.html

[U52] PHP：箭头函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rfwyearc.html

$double = fn($x) => $x * 2;
来源：http://dali.daria6918.cn/Article/details/gt2ynygezba.html

[U53] PHP：空合并运算符
来源：http://dali.cqqwz.cn/Article/details/gt2egluuenk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhoulong.xyz/Article/details/gt2yvapxnrq.html

[U54] PHP：空安全调用
来源：http://dali.gogol.net.cn/Article/details/gt2sjvvmygt.html

$obj?->method()
来源：http://dali.fengsongda.top/Article/details/gt2yqnglrye.html

[U55] PHP：match 表达式
来源：http://dali.gogol.net.cn/Article/details/gt2lvzfzkwn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hnxiangtu.top/Article/details/gt2qymmzizh.html

[U56] PHP：命名参数
来源：http://dali.cucudq.cn/Article/details/gt2lcjelkea.html

f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gt2dxwabrbb.html

[U57] PHP：字符串插值
来源：http://dali.sweek.top/Article/details/gt2thcoleid.html

"值: {$a}"
来源：http://dali.ivvv.top/Article/details/gt2itmsoaez.html

[U58] PHP：数组三件套
来源：http://dali.aibaodan.cn/Article/details/gt2vrckwtiw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jianghu66.top/Article/details/gt2jjlffnyy.html

[U59] PHP：自定义排序
来源：http://dali.zdqjudy.top/Article/details/gt2ifugqejn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2vmpsacvd.html

[U60] PHP：JSON 编解码
来源：http://dali.xylfe.cn/Article/details/gt2ebifruqn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.andypj.xyz/Article/details/gt2hhuyzajy.html

[U61] PHP：正则
来源：http://dali.yanxiufei.cn/Article/details/gt2kikdfeef.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gt2aqegezej.html

[U62] PHP：日期对象
来源：http://dali.316326.xyz/Article/details/gt2icpogczw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.chenzaomai.com/Article/details/gt2rlifhnkr.html

[U63] PHP：文件读写
来源：http://dali.nanxuanxn.top/Article/details/gt2qpcmhoms.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.guannengcc.top/Article/details/gt2tgoscopm.html

[U64] PHP：目录遍历
来源：http://dali.shzxlz.cn/Article/details/gt2therqffn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cashguo.top/Article/details/gt2jynybahm.html

[U65] PHP：会话
来源：http://dali.tianlin.xyz/Article/details/gt2brjplykg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2kqqzqvle.html

[U66] PHP：设置 Cookie
来源：http://dali.zhixingplan.top/Article/details/gt2nbforumm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sysykeji.top/Article/details/gt2torcbvno.html

[U67] PHP：处理文件上传
来源：http://dali.dashuyun.cn/Article/details/gt2olevcnpb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xuetiantiany.cn/Article/details/gt2gybtiqsn.html

[U68] PHP：PDO 连接
来源：http://dali.gzhubu.top/Article/details/gt2pdxnufce.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yuxming.cn/Article/details/gt2lbqabqip.html

[U69] PHP：PDO 预处理
来源：http://dali.mhx1999.top/Article/details/gt2ncsutocz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ivvv.top/Article/details/gt2tnohsbii.html

[U70] PHP：PDO 事务
来源：http://dali.gotoacloud.top/Article/details/gt2nanhmgav.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yongpay.top/Article/details/gt2vwplcnzp.html

[U71] PHP：抛出异常
来源：http://dali.shzxlz.cn/Article/details/gt2yjjmrnbx.html

throw new RuntimeException("失败", 500);
来源：http://dali.sysykeji.top/Article/details/gt2bzqromja.html

[U72] PHP：写错误日志
来源：http://dali.vqdsnc.cn/Article/details/gt2lwgcqzug.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yj20258.top/Article/details/gt2vpearuev.html

[U73] PHP：读取 ini 配置
来源：http://dali.9152youxi.cn/Article/details/gt2tpoziwwh.html

parse_ini_file("config.ini", true)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cnqeynjd.html

[U74] PHP：读取环境变量
来源：http://dali.yvedp.cn/Article/details/gt2tzgrwaur.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj20258.top/Article/details/gt2cscbesuu.html

[U75] PHP：依赖注入
来源：http://dali.yj202588.top/Article/details/gt2kchxtray.html

composer require psr/container
来源：http://dali.ybcxt.top/Article/details/gt2ouyehzpa.html

[U76] PHP：简单路由
来源：http://dali.yj202588.top/Article/details/gt2wqyuwqat.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.316326.xyz/Article/details/gt2bgxzfvtd.html

[U77] PHP：模板渲染
来源：http://dali.pengpengdd.cyou/Article/details/gt2labvrwnk.html

composer require twig/twig
来源：http://dali.cucudq.cn/Article/details/gt2npikotxu.html

[U78] PHP：单元测试
来源：http://dali.xuanzx.com/Article/details/gt2njmtrqzx.html

composer require --dev phpunit/phpunit
来源：http://dali.aizwys.cn/Article/details/gt2ehhgufdh.html

[U79] PHP：静态分析
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ogqnkszt.html

composer require --dev phpstan/phpstan
来源：http://dali.kuanghao11.cn/Article/details/gt2vegyvxnp.html

[U80] PHP：代码规范修复
来源：http://dali.xuetiantiany.cn/Article/details/gt2xubtdtwl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.daria6918.cn/Article/details/gt2bxlvuooe.html

[U81] JS：初始化项目
来源：http://dali.nwbrower.top/Article/details/gt2kqugcort.html

npm init -y;  npm i express
来源：http://dali.ybcxt.top/Article/details/gt2fusbstdu.html

[U82] JS：package.json 脚本
来源：http://dali.jlsjyb.cn/Article/details/gt2vxkfwdpn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cashguo.top/Article/details/gt2iaouxnpf.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vcniapta.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhoulong.xyz/Article/details/gt2wegyigsy.html

[U84] JS：CommonJS 写法
来源：http://dali.xuanzx.com/Article/details/gt2hkvzlqdx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.redwolf501.top/Article/details/gt2iubvujui.html

[U85] JS：可选链
来源：http://dali.zhixingplan.top/Article/details/gt2webfbpzb.html

a?.b?.c
来源：http://dali.ybcxt.top/Article/details/gt2gplnxltv.html

[U86] JS：空值合并
来源：http://dali.zycfv.cn/Article/details/gt2otqmegdz.html

a ?? b
来源：http://dali.hnxiangtu.top/Article/details/gt2povchihb.html

[U87] JS：解构默认值
来源：http://dali.gzhubu.top/Article/details/gt2vykzzhqq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jiagoushi.top/Article/details/gt2udprlxql.html

[U88] JS：对象展开合并
来源：http://dali.bjfxy.top/Article/details/gt2jgdtdxxe.html

{ ...a, ...b }
来源：http://dali.dianchejie.cn/Article/details/gt2mzchonzv.html

[U89] JS：数组去重
来源：http://dali.zhongyouzk.top/Article/details/gt2itlmagwm.html

[...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gt2xplqmbxz.html

[U90] JS：数字数组排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kdgulelo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gt2zcutmsnl.html

[U91] JS：对象键值遍历
来源：http://dali.fengsongda.top/Article/details/gt2frlereli.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hnxiangtu.top/Article/details/gt2quygvwrm.html

[U92] JS：深拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gt2naqkgnww.html

structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gt2wtqfbdjr.html

[U93] JS：模板字符串
来源：http://dali.hfpthk.cn/Article/details/gt2yatlvidc.html

`共 ${n} 条`
来源：http://dali.hfpthk.cn/Article/details/gt2citywuun.html

[U94] JS：箭头函数
来源：http://dali.ivvv.top/Article/details/gt2anpmdxln.html

const double = x => x * 2;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sjnbgmlj.html

[U95] JS：Promise 包装
来源：http://dali.gotoacloud.top/Article/details/gt2tcwucsbf.html

new Promise((resolve, reject) => {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vfwkuurq.html

[U96] JS：async/await 与异常
来源：http://dali.ppjwa.cn/Article/details/gt2mtbapmza.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2cmpfbehy.html

[U97] JS：并发请求
来源：http://dali.cqqwz.cn/Article/details/gt2fgybpkoi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gt2wxqdenak.html

[U98] JS：fetch 带 JSON
来源：http://dali.shangyingyoupin.top/Article/details/gt2vitqqmif.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2deuieajf.html

[U99] JS：事件监听
来源：http://dali.jlsjyb.cn/Article/details/gt2hrmlpnrh.html

el.addEventListener("click", e => {})
来源：http://dali.dashuyun.cn/Article/details/gt2jkvgdanc.html

[U100] JS：DOM 查询
来源：http://dali.aizwys.cn/Article/details/gt2fwhgbleo.html

document.querySelector(".item")
来源：http://dali.sufxvd.cn/Article/details/gt2phgyrssw.html

[U101] JS：classList 操作
来源：http://dali.zhongyouzk.top/Article/details/gt2lyiahwmj.html

el.classList.toggle("active")
来源：http://dali.sweek.top/Article/details/gt2crvpnuzz.html

[U102] JS：本地存储
来源：http://dali.zhongyouzk.top/Article/details/gt2majckyqy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shangyingyoupin.top/Article/details/gt2ilgorcxa.html

[U103] JS：定时器
来源：http://dali.xylfe.cn/Article/details/gt2rjxnrvst.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.dianchejie.cn/Article/details/gt2nimdsejv.html

[U104] JS：防抖
来源：http://dali.yangfankeji.com/Article/details/gt2kgsoyemv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gt2rtnxaawh.html

[U105] JS：节流
来源：http://dali.yj20258888.top/Article/details/gt2syqnzdcs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nwbrower.top/Article/details/gt2kkjtienc.html

[U106] JS：日期格式化
来源：http://dali.andypj.xyz/Article/details/gt2blhgjvio.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.guowangkeji.top/Article/details/gt2ilcwsnpk.html

[U107] JS：数字千分位
来源：http://dali.cashguo.top/Article/details/gt2lwmjewsp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zycfv.cn/Article/details/gt2lzqouzrb.html

[U108] JS：随机整数
来源：http://dali.aizwys.cn/Article/details/gt2jgysnqur.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.wangshuangyany.cn/Article/details/gt2odqkzrsy.html

[U109] JS：数组分组
来源：http://dali.jiagoushi.top/Article/details/gt2uedbrtzu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ydzc1.top/Article/details/gt2xrqfeieh.html

[U110] JS：数组分块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ahxihhvs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zycfv.cn/Article/details/gt2pipukdpo.html

[U111] JS：对象转 Map
来源：http://dali.iojbl.cn/Article/details/gt2tajztjyd.html

new Map(Object.entries(obj))
来源：http://dali.yangfankeji.com/Article/details/gt2mprxjmsb.html

[U112] JS：字符串补位
来源：http://dali.sweek.top/Article/details/gt2umyvfryr.html

"7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gt2fxhbmeom.html

[U113] JS：正则替换全部
来源：http://dali.yuxming.cn/Article/details/gt2xxdxaqct.html

s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2cpzyhhid.html

[U114] JS：JSON 深比较
来源：http://dali.aibaodan.cn/Article/details/gt2xzlzspxj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gaohongyu789.top/Article/details/gt2ckmqqmnu.html

[U115] JS：生成 UUID
来源：http://dali.aibaodan.cn/Article/details/gt2fohbnxia.html

crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gt2jxdgjyii.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sxryk.cn/Article/details/gt2edieukpn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hfpthk.cn/Article/details/gt2ypnzxfsa.html

[U117] JS：单元测试
来源：http://dali.jqgufenzy.top/Article/details/gt2wtsoyawk.html

npm i -D vitest;  npx vitest
来源：http://dali.zhongyouzk.top/Article/details/gt2ctfzkflo.html

[U118] JS：开发服务器
来源：http://dali.zhixingplan.top/Article/details/gt2uhobftmu.html

npm i -D vite;  npx vite
来源：http://dali.jiagoushi.top/Article/details/gt2zjwxxsap.html

[U119] JS：生产构建
来源：http://dali.vqdsnc.cn/Article/details/gt2adargsat.html

npx vite build
来源：http://dali.hnqzz.top/Article/details/gt2udozmgfj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sxryk.cn/Article/details/gt2gvrjyvdn.html

import.meta.env.VITE_API_URL
来源：http://dali.yongpay.top/Article/details/gt2xtyuaeey.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kucqwode.html

统计汇总
来源：http://dali.tanke756.top/Article/details/gt2rdsvczle.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2papocyce.html

按语言统计（条）：
来源：http://dali.jinghuilouyu.cn/Article/details/gt2msvqzvdl.html

Python ......... 252
来源：http://dali.bjfxy.top/Article/details/gt2zvkgmuiw.html

PHP ............ 252
来源：http://dali.yvedp.cn/Article/details/gt2pykfuler.html

JavaScript ..... 252
来源：http://dali.jiagoushi.top/Article/details/gt2yxggwatp.html

TypeScript ..... 212
来源：http://dali.316326.xyz/Article/details/gt2btftqdug.html

Java ........... 212
来源：http://dali.tian-w.cn/Article/details/gt2gokqnmwx.html

Go ............. 212
来源：http://dali.haohaochexian.top/Article/details/gt2ftcizjzd.html

Ruby ........... 212
来源：http://dali.zhengqikj.top/Article/details/gt2ucpekogr.html

C# ............. 212
来源：http://dali.nanxuanxn.top/Article/details/gt2wziavhex.html

C .............. 30
来源：http://dali.xylfe.cn/Article/details/gt2sbjhfnml.html

C++ ............ 30
来源：http://dali.xziqi.cn/Article/details/gt2wnmydxua.html

SQL ............ 90
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pvpzigme.html

Bash ........... 80
来源：http://dali.sysykeji.top/Article/details/gt2svkzoguk.html

Kotlin ......... 15
来源：http://dali.ehwqpu.com/Article/details/gt2owrafpuj.html

Swift .......... 15
来源：http://dali.jqgufenzy.top/Article/details/gt2hwrwhdjj.html

Lua ............ 10
来源：http://dali.dianchejie.cn/Article/details/gt2invptkgz.html

Perl ........... 10
来源：http://dali.ppjwa.cn/Article/details/gt2tvxvfrcm.html

Scala .......... 10
来源：http://dali.hammf.cn/Article/details/gt2bskybujr.html

------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gt2mmfefflj.html

合计 ........... 2106 条
来源：http://dali.jqgfzy.top/Article/details/gt2zexngpkl.html

按章节统计：
来源：http://dali.aibaodan.cn/Article/details/gt2wqoqyvmn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yj20258888.top/Article/details/gt2abvkrbmq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gt2jlhldgko.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gt2hkuuqddd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.daxiang520.top/Article/details/gt2tnkhnjdq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cqqwz.cn/Article/details/gt2jxvwqckj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.aizwys.cn/Article/details/gt2pezzairq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gt2bydnmlss.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.svipenyu.cn/Article/details/gt2puezqxfm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gt2ijrtwwoe.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yueranfly.top/Article/details/gt2lbguzxos.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gt2htpcpubc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gt2anqhiikq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gt2regyqhne.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cheryme.top/Article/details/gt2nwhuqbpa.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinqigfzy.top/Article/details/gt2nfcqgama.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gt2rbfdjafb.html

Q SQL 专题                              90
来源：http://dali.tianlin.xyz/Article/details/gt2jqgcfene.html

R Bash 专题                             80
来源：http://dali.iojbl.cn/Article/details/gt2dgxtuaei.html

S C / C++ 专题                          60
来源：http://dali.vqdsnc.cn/Article/details/gt2dmbwmyzp.html

T 其他语言补充                          60
来源：http://dali.jlsjyb.cn/Article/details/gt2omglazer.html

U 高频实用片段                         120
来源：http://dali.jqgufenzy.top/Article/details/gt2vprlctnj.html

------------------------------------
来源：http://dali.zycfv.cn/Article/details/gt2cfegtbxl.html

合计                                  2106 条
来源：http://dali.yueranfly.top/Article/details/gt2izqgyllm.html

--------------------------------------------------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gt2pxhfwfyq.html

使用提醒
来源：http://dali.aizwys.cn/Article/details/gt2gwpucypd.html

--------------------------------------------------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pzppfbhp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zdqjudy.top/Article/details/gt2ztdpohsi.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jiagoushi.top/Article/details/gt2lqlnmlyb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xrrmvrgu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.chenlongwang.top/Article/details/gt2hffjkver.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.mhx1999.top/Article/details/gt2vaclhgcg.html

—— 文件结束 ——
来源：http://dali.gotoacloud.top/Article/details/gt2xphnfsbq.html


<!-- 参考信息 -->