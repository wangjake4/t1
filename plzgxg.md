代发 wailian999

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mdgbovnq.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2lickzoho.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tianlin.xyz/Article/details/gt2zqxtthep.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2rxaeufsg.html

[U01] Py：创建虚拟环境
来源：http://dali.316326.xyz/Article/details/gt2dwgzgseu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenlongwang.top/Article/details/gt2njzdlwwe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.quarkkingdee.top/Article/details/gt2fbgdicgy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gmkkxssm.html

[U03] Py：加载 .env 配置
来源：http://dali.xinyue.icu/Article/details/gt2bavvyrkz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cashguo.top/Article/details/gt2qzxxovyl.html

[U04] Py：变量调试打印
来源：http://dali.sufxvd.cn/Article/details/gt2edtnqmsr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qnmvvnbu.html

[U05] Py：列表去重且保序
来源：http://dali.hfpthk.cn/Article/details/gt2mausdelh.html

list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gt2dfhntuic.html

[U06] Py：合并两个字典
来源：http://dali.ybcxt.top/Article/details/gt2jfdgcrib.html

{**a, **b}
来源：http://dali.yangfankeji.com/Article/details/gt2shbbwshm.html

[U07] Py：反转字典键值
来源：http://dali.havefunace.top/Article/details/gt2whifiltt.html

{v: k for k, v in d.items()}
来源：http://dali.fzhhl.top/Article/details/gt2httbfvvq.html

[U08] Py：展平二维列表
来源：http://dali.fengsongda.top/Article/details/gt2jzvzfdna.html

[y for x in nested for y in x]
来源：http://dali.hywenlv.cn/Article/details/gt2qbcbmefz.html

[U09] Py：字典取最大值的键
来源：http://dali.daxiang520.top/Article/details/gt2lncjnscx.html

max(d, key=d.get)
来源：http://dali.nanxuanxn.top/Article/details/gt2npgwytqe.html

[U10] Py：按值排序字典
来源：http://dali.havefunace.top/Article/details/gt2ljzswtqb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigufen.top/Article/details/gt2zowdxyjf.html

[U11] Py：生成器表达式
来源：http://dali.feifeiyinyue.top/Article/details/gt2splzjzsd.html

(x * 2 for x in arr)
来源：http://dali.yvedp.cn/Article/details/gt2bwkobytu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tianlin.xyz/Article/details/gt2akkfoidq.html

Counter(arr).most_common(3)
来源：http://dali.xylfe.cn/Article/details/gt2gnjzighz.html

[U13] Py：固定长度队列
来源：http://dali.jianghu66.top/Article/details/gt2qlxwkuoq.html

deque(maxlen=10)
来源：http://dali.chenlongwang.top/Article/details/gt2oculxnhy.html

[U14] Py：分组收集到列表
来源：http://dali.aizwys.cn/Article/details/gt2kmnijbvj.html

defaultdict(list)
来源：http://dali.hysaishi.cn/Article/details/gt2madwzngj.html

[U15] Py：高精度计时
来源：http://dali.quarkkingdee.top/Article/details/gt2lkchcirl.html

t = time.perf_counter()
来源：http://dali.cucudq.cn/Article/details/gt2iclmjuff.html

[U16] Py：命令行参数解析
来源：http://dali.guowangkeji.top/Article/details/gt2lfkrphts.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.svipenyu.cn/Article/details/gt2aftoethe.html

[U17] Py：初始化日志
来源：http://dali.xziqi.cn/Article/details/gt2qimflsxq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yongpay.top/Article/details/gt2sduzkjci.html

[U18] Py：预编译正则
来源：http://dali.fzhhl.top/Article/details/gt2phglyheu.html

pat = re.compile(r"\d+")
来源：http://dali.tanke756.top/Article/details/gt2lhggghkw.html

[U19] Py：正则替换带回调
来源：http://dali.gaohongyu789.top/Article/details/gt2jzzronoi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xuanzx.com/Article/details/gt2dyvzceye.html

[U20] Py：缓存函数结果
来源：http://dali.svipenyu.cn/Article/details/gt2iyywqgnr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tujetthg.html

[U21] Py：自定义上下文管理器
来源：http://dali.sweek.top/Article/details/gt2dgxgyubk.html

@contextlib.contextmanager
来源：http://dali.hywenlv.cn/Article/details/gt2sqymvzvs.html

[U22] Py：矩阵转置
来源：http://dali.jlsjyb.cn/Article/details/gt2cntojhwk.html

list(zip(*m))
来源：http://dali.wangdashe.top/Article/details/gt2rcxlfdvw.html

[U23] Py：分块读取大文件
来源：http://dali.yj20258888.top/Article/details/gt2psvvkkip.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yuanzhike.top/Article/details/gt2dlsemspo.html

[U24] Py：路径操作
来源：http://dali.nanxinkj.top/Article/details/gt2vmlgosin.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctalhnay.html

[U25] Py：CSV 按字典读
来源：http://dali.hongshengwenyu.top/Article/details/gt2khwktant.html

csv.DictReader(f)
来源：http://dali.ehwqpu.com/Article/details/gt2hdauhruu.html

[U26] Py：并发下载
来源：http://dali.ivvv.top/Article/details/gt2kynrwtwl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhiwuduotai.top/Article/details/gt2utmrgrku.html

[U27] Py：异步 HTTP
来源：http://dali.zhongyouzk.top/Article/details/gt2lyjbukvu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cdnleiting.top/Article/details/gt2scqtmcgv.html

[U28] Py：类型别名
来源：http://dali.pengpengdd.cyou/Article/details/gt2nkqllvwu.html

UserId = int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbhvptcf.html

[U29] Py：属性校验
来源：http://dali.svipenyu.cn/Article/details/gt2cjbljdvx.html

@property 与 @x.setter 配合
来源：http://dali.meibo888.top/Article/details/gt2eiizfqow.html

[U30] Py：数据类
来源：http://dali.pycfn.com/Article/details/gt2cuewttqb.html

@dataclass(slots=True)
来源：http://dali.xziqi.cn/Article/details/gt2rhjyxmfj.html

[U31] Py：单测
来源：http://dali.daria6918.cn/Article/details/gt2lglakhhi.html

python -m pytest -q
来源：http://dali.gogol.net.cn/Article/details/gt2lifsasph.html

[U32] Py：代码格式化
来源：http://dali.nwbrower.top/Article/details/gt2qhxdtnol.html

ruff format . && ruff check --fix .
来源：http://dali.zycfv.cn/Article/details/gt2hjwdblyc.html

[U33] Py：打包发布
来源：http://dali.smart0.xyz/Article/details/gt2mowvvapg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hywenlv.cn/Article/details/gt2zsiqgzfm.html

[U34] Py：判断编码
来源：http://dali.wangdashe.top/Article/details/gt2keajmsrn.html

chardet.detect(raw)
来源：http://dali.smart0.xyz/Article/details/gt2dlnqtikf.html

[U35] Py：发送邮件
来源：http://dali.yvedp.cn/Article/details/gt2eztuzxav.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.bjfxy.top/Article/details/gt2uogdzjcc.html

[U36] Py：定时任务
来源：http://dali.hongshengwenyu.top/Article/details/gt2spkddlvz.html

schedule.every(10).minutes.do(job)
来源：http://dali.nanxuanxn.top/Article/details/gt2pzqitebq.html

[U37] Py：读写 Excel
来源：http://dali.gotoacloud.top/Article/details/gt2rddhgrby.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.0kj1m.cn/Article/details/gt2gtsdbpok.html

[U38] Py：获取脚本所在目录
来源：http://dali.snrcjt.cn/Article/details/gt2qodjtitg.html

Path(__file__).resolve().parent
来源：http://dali.gzhubu.top/Article/details/gt2ercrbjou.html

[U39] Py：判断是否在交互环境
来源：http://dali.gogol.net.cn/Article/details/gt2liqnecpj.html

sys.stdout.isatty()
来源：http://dali.ehwqpu.com/Article/details/gt2btxzhwar.html

[U40] Py：打印到标准错误
来源：http://dali.xylfe.cn/Article/details/gt2bhhzlcdq.html

print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gt2zyltghjq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ybcxt.top/Article/details/gt2efiimjww.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sufxvd.cn/Article/details/gt2feznmlvp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cucudq.cn/Article/details/gt2ktafaqsv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.dashuyun.cn/Article/details/gt2jkxfipdq.html

[U43] PHP：声明命名空间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oatittci.html

namespace App\Http;
来源：http://dali.hysaishi.cn/Article/details/gt2gixomyvd.html

[U44] PHP：开启严格类型
来源：http://dali.jinqigfzy.top/Article/details/gt2wjyynnib.html

declare(strict_types=1);
来源：http://dali.gaohongyu789.top/Article/details/gt2jijfrpvl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2elfzcbzv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gt2iridpwjh.html

[U46] PHP：可空类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2dcihgfiz.html

?string $name = null
来源：http://dali.sweek.top/Article/details/gt2bhrcigjh.html

[U47] PHP：联合类型
来源：http://dali.jiagoushi.top/Article/details/gt2tortpjum.html

int|string $id
来源：http://dali.ybcxt.top/Article/details/gt2yytvpgsd.html

[U48] PHP：纯枚举
来源：http://dali.yangfankeji.com/Article/details/gt2xwxnxvko.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xinyue.icu/Article/details/gt2mrxizwvz.html

[U49] PHP：只读属性
来源：http://dali.pycfn.com/Article/details/gt2xhperksb.html

public readonly string $name
来源：http://dali.zycfv.cn/Article/details/gt2zoryuxnb.html

[U50] PHP：构造器属性提升
来源：http://dali.shuidangran.top/Article/details/gt2smasfexh.html

public function __construct(private int $id) {}
来源：http://dali.sxryk.cn/Article/details/gt2xhmnaehu.html

[U51] PHP：数组解构
来源：http://dali.zhengqikj.top/Article/details/gt2jutkocgt.html

[$a, $b] = $arr;
来源：http://dali.kuanghao11.cn/Article/details/gt2lfdvrnfv.html

[U52] PHP：箭头函数
来源：http://dali.zhixingplan.top/Article/details/gt2sdgtfoiv.html

$double = fn($x) => $x * 2;
来源：http://dali.cqqwz.cn/Article/details/gt2qhzjuyfg.html

[U53] PHP：空合并运算符
来源：http://dali.pycfn.com/Article/details/gt2vyxibtnw.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinqigfzy.top/Article/details/gt2aivoarys.html

[U54] PHP：空安全调用
来源：http://dali.jianghu66.top/Article/details/gt2vmibvwag.html

$obj?->method()
来源：http://dali.hnxiangtu.top/Article/details/gt2idprtcnd.html

[U55] PHP：match 表达式
来源：http://dali.dianchejie.cn/Article/details/gt2vtumfynn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zdqjudy.top/Article/details/gt2omgssauk.html

[U56] PHP：命名参数
来源：http://dali.sweek.top/Article/details/gt2anosdfag.html

f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gt2ymxjdvuk.html

[U57] PHP：字符串插值
来源：http://dali.shuidangran.top/Article/details/gt2lhnjtyrz.html

"值: {$a}"
来源：http://dali.redwolf501.top/Article/details/gt2qsegbhnv.html

[U58] PHP：数组三件套
来源：http://dali.gogol.net.cn/Article/details/gt2oxiajbrn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zdqjudy.top/Article/details/gt2ycdqsmmp.html

[U59] PHP：自定义排序
来源：http://dali.dianchejie.cn/Article/details/gt2jdscshvk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gt2kyplobju.html

[U60] PHP：JSON 编解码
来源：http://dali.quarkkingdee.top/Article/details/gt2gutumrjl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcmjisy.html

[U61] PHP：正则
来源：http://dali.vqdsnc.cn/Article/details/gt2yuiqrtls.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2wslmvyse.html

[U62] PHP：日期对象
来源：http://dali.shuidangran.top/Article/details/gt2zeeycbrq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yanxiufei.cn/Article/details/gt2gjkwosze.html

[U63] PHP：文件读写
来源：http://dali.tian-w.cn/Article/details/gt2tskxfwgf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.quarkkingdee.top/Article/details/gt2yplssabx.html

[U64] PHP：目录遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2dlxxxnjx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.redwolf501.top/Article/details/gt2vgchhwif.html

[U65] PHP：会话
来源：http://dali.shangyingyoupin.top/Article/details/gt2mcrmgjnk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2uvxjgsxd.html

[U66] PHP：设置 Cookie
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgjdnnog.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sysykeji.top/Article/details/gt2jtzjdzcf.html

[U67] PHP：处理文件上传
来源：http://dali.havefunace.top/Article/details/gt2qnsdeora.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jinqigfzy.top/Article/details/gt2caagxyxb.html

[U68] PHP：PDO 连接
来源：http://dali.jinqigufen.top/Article/details/gt2ijrxvmcz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sxryk.cn/Article/details/gt2xrhrkycc.html

[U69] PHP：PDO 预处理
来源：http://dali.hysaishi.cn/Article/details/gt2yhgkuect.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dxaemjod.html

[U70] PHP：PDO 事务
来源：http://dali.xuetiantiany.cn/Article/details/gt2iseufpvd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.chenzaomai.com/Article/details/gt2ryhjjnxj.html

[U71] PHP：抛出异常
来源：http://dali.nanxinkj.top/Article/details/gt2dsfrkjlf.html

throw new RuntimeException("失败", 500);
来源：http://dali.iojbl.cn/Article/details/gt2gmycsmgo.html

[U72] PHP：写错误日志
来源：http://dali.sxryk.cn/Article/details/gt2uktvjgeq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnvuzlu.html

[U73] PHP：读取 ini 配置
来源：http://dali.xuetiantiany.cn/Article/details/gt2kqwnkrkq.html

parse_ini_file("config.ini", true)
来源：http://dali.tian-w.cn/Article/details/gt2findkpiq.html

[U74] PHP：读取环境变量
来源：http://dali.birdmap.top/Article/details/gt2rowfooba.html

getenv("APP_ENV") ?: "production"
来源：http://dali.guowangkeji.top/Article/details/gt2srxvxogl.html

[U75] PHP：依赖注入
来源：http://dali.birdmap.top/Article/details/gt2fcrthrbl.html

composer require psr/container
来源：http://dali.xuetiantiany.cn/Article/details/gt2cqkmwmhs.html

[U76] PHP：简单路由
来源：http://dali.hnxiangtu.top/Article/details/gt2ptgjtdby.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xziqi.cn/Article/details/gt2pfvjmhur.html

[U77] PHP：模板渲染
来源：http://dali.dianchejie.cn/Article/details/gt2qyrxcadm.html

composer require twig/twig
来源：http://dali.sweek.top/Article/details/gt2clgreank.html

[U78] PHP：单元测试
来源：http://dali.zycfv.cn/Article/details/gt2fjvkpzba.html

composer require --dev phpunit/phpunit
来源：http://dali.sweek.top/Article/details/gt2uorlmoha.html

[U79] PHP：静态分析
来源：http://dali.gzhubu.top/Article/details/gt2ciujwrsl.html

composer require --dev phpstan/phpstan
来源：http://dali.ydzc1.top/Article/details/gt2grzloxbi.html

[U80] PHP：代码规范修复
来源：http://dali.yanxiufei.cn/Article/details/gt2xgsufmew.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.dashuyun.cn/Article/details/gt2qemltwmg.html

[U81] JS：初始化项目
来源：http://dali.yuxming.cn/Article/details/gt2echjmboe.html

npm init -y;  npm i express
来源：http://dali.dashuyun.cn/Article/details/gt2hvhvqtep.html

[U82] JS：package.json 脚本
来源：http://dali.shangyingyoupin.top/Article/details/gt2ebdnahvf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.haohaochexian.top/Article/details/gt2dcxmauni.html

[U83] JS：ES Module 导入导出
来源：http://dali.yuxming.cn/Article/details/gt2swaxwutk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gt2hsribfgi.html

[U84] JS：CommonJS 写法
来源：http://dali.vqdsnc.cn/Article/details/gt2oqeljysj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.nanxinkj.top/Article/details/gt2fskpvpvx.html

[U85] JS：可选链
来源：http://dali.bjfxy.top/Article/details/gt2chaclzdr.html

a?.b?.c
来源：http://dali.hfpthk.cn/Article/details/gt2qkupwqly.html

[U86] JS：空值合并
来源：http://dali.jiagoushi.top/Article/details/gt2zjnzqnri.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2yqiztgoa.html

[U87] JS：解构默认值
来源：http://dali.tanke756.top/Article/details/gt2brecnynm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.dashuyun.cn/Article/details/gt2nvvhixrj.html

[U88] JS：对象展开合并
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bnkglmta.html

{ ...a, ...b }
来源：http://dali.gaohongyu789.top/Article/details/gt2kpckiyth.html

[U89] JS：数组去重
来源：http://dali.jiagoushi.top/Article/details/gt2xlacyiyb.html

[...new Set(arr)]
来源：http://dali.daria6918.cn/Article/details/gt2actepjlw.html

[U90] JS：数字数组排序
来源：http://dali.ppjwa.cn/Article/details/gt2rdcwdpzi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gt2lbjgyyqw.html

[U91] JS：对象键值遍历
来源：http://dali.sufxvd.cn/Article/details/gt2nllfvnir.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.meibo888.top/Article/details/gt2uizbctfe.html

[U92] JS：深拷贝
来源：http://dali.daria6918.cn/Article/details/gt2leuxxyrw.html

structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gt2efsfuxdo.html

[U93] JS：模板字符串
来源：http://dali.fengsongda.top/Article/details/gt2xjwrlvmd.html

`共 ${n} 条`
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hcvbqoyg.html

[U94] JS：箭头函数
来源：http://dali.jlsjyb.cn/Article/details/gt2vlkqmiur.html

const double = x => x * 2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xmixtsxi.html

[U95] JS：Promise 包装
来源：http://dali.wangdashe.top/Article/details/gt2rmmtodbw.html

new Promise((resolve, reject) => {})
来源：http://dali.cheryme.top/Article/details/gt2ylbhkzml.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2idmnhbpm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gt2daffmtyd.html

[U97] JS：并发请求
来源：http://dali.yuxming.cn/Article/details/gt2swcdzapq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gt2xsbwkpvz.html

[U98] JS：fetch 带 JSON
来源：http://dali.wangdashe.top/Article/details/gt2uocqvaqm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2nznjwpso.html

[U99] JS：事件监听
来源：http://dali.ehwqpu.com/Article/details/gt2cnpcbmbq.html

el.addEventListener("click", e => {})
来源：http://dali.xinyue.icu/Article/details/gt2tfcftbzx.html

[U100] JS：DOM 查询
来源：http://dali.yonumen.top/Article/details/gt2bwlkfona.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvxhyem.html

[U101] JS：classList 操作
来源：http://dali.gotoacloud.top/Article/details/gt2ezmlcauc.html

el.classList.toggle("active")
来源：http://dali.gaohongyu789.top/Article/details/gt2jvidrxnk.html

[U102] JS：本地存储
来源：http://dali.jiagoushi.top/Article/details/gt2trqiznnj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinqigfzy.top/Article/details/gt2filjhrwy.html

[U103] JS：定时器
来源：http://dali.haohaochexian.top/Article/details/gt2axwxxhtr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yuxming.cn/Article/details/gt2tkgzpdvd.html

[U104] JS：防抖
来源：http://dali.yuxming.cn/Article/details/gt2bozsgucm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gt2cezwxugz.html

[U105] JS：节流
来源：http://dali.yangfankeji.com/Article/details/gt2dikvfrmf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cucudq.cn/Article/details/gt2uuzdatft.html

[U106] JS：日期格式化
来源：http://dali.redwolf501.top/Article/details/gt2klucwnki.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.redwolf501.top/Article/details/gt2wsjohnne.html

[U107] JS：数字千分位
来源：http://dali.haohaochexian.top/Article/details/gt2ejesfuwr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.dashuyun.cn/Article/details/gt2xompffdv.html

[U108] JS：随机整数
来源：http://dali.xuanzx.com/Article/details/gt2cugqpfrw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhiwuduotai.top/Article/details/gt2ojgdeggl.html

[U109] JS：数组分组
来源：http://dali.zhoulong.xyz/Article/details/gt2ybimytci.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gt2efzlkeaw.html

[U110] JS：数组分块
来源：http://dali.yuanzhike.top/Article/details/gt2xpgqazsq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yj20258888.top/Article/details/gt2oygupswm.html

[U111] JS：对象转 Map
来源：http://dali.ppjwa.cn/Article/details/gt2wwcdupmh.html

new Map(Object.entries(obj))
来源：http://dali.iojbl.cn/Article/details/gt2wadfmrbs.html

[U112] JS：字符串补位
来源：http://dali.yj20258.top/Article/details/gt2cyoyrskv.html

"7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xibdslas.html

[U113] JS：正则替换全部
来源：http://dali.daria6918.cn/Article/details/gt2jzbacixg.html

s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2ukelvelw.html

[U114] JS：JSON 深比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vpfghtud.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsndwxxb.html

[U115] JS：生成 UUID
来源：http://dali.shuidangran.top/Article/details/gt2wicfrlhw.html

crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gt2numhyqwe.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yj20258.top/Article/details/gt2gnvtkzeu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2csgxckkl.html

[U117] JS：单元测试
来源：http://dali.bjfxy.top/Article/details/gt2kqlaptev.html

npm i -D vitest;  npx vitest
来源：http://dali.haohaochexian.top/Article/details/gt2byplzbnt.html

[U118] JS：开发服务器
来源：http://dali.gzhubu.top/Article/details/gt2minbfumo.html

npm i -D vite;  npx vite
来源：http://dali.fzhhl.top/Article/details/gt2ilywknws.html

[U119] JS：生产构建
来源：http://dali.mhx1999.top/Article/details/gt2gndteodf.html

npx vite build
来源：http://dali.quarkkingdee.top/Article/details/gt2duyrdufo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nwbrower.top/Article/details/gt2dvmzpzxg.html

import.meta.env.VITE_API_URL
来源：http://dali.aibaodan.cn/Article/details/gt2spowoduz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2jvakxnsw.html

统计汇总
来源：http://dali.gogol.net.cn/Article/details/gt2ntizriae.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2nsayhuxf.html

按语言统计（条）：
来源：http://dali.tianlin.xyz/Article/details/gt2vztadoax.html

Python ......... 252
来源：http://dali.hnqzz.top/Article/details/gt2iphracrb.html

PHP ............ 252
来源：http://dali.meibo888.top/Article/details/gt2bioadxgl.html

JavaScript ..... 252
来源：http://dali.tianlin.xyz/Article/details/gt2jhearmei.html

TypeScript ..... 212
来源：http://dali.dianchejie.cn/Article/details/gt2amzqazvm.html

Java ........... 212
来源：http://dali.yj20258888.top/Article/details/gt2kywcbjjb.html

Go ............. 212
来源：http://dali.cashguo.top/Article/details/gt2kkmldoez.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uefaonvb.html

C# ............. 212
来源：http://dali.vqdsnc.cn/Article/details/gt2njqmlkwq.html

C .............. 30
来源：http://dali.jiagoushi.top/Article/details/gt2rjjtnlhs.html

C++ ............ 30
来源：http://dali.c1oappe.top/Article/details/gt2oblfubjl.html

SQL ............ 90
来源：http://dali.chenzaomai.com/Article/details/gt2emumaaul.html

Bash ........... 80
来源：http://dali.ppjwa.cn/Article/details/gt2vkoxlcmn.html

Kotlin ......... 15
来源：http://dali.sysykeji.top/Article/details/gt2wpvtjezr.html

Swift .......... 15
来源：http://dali.yj20258888.top/Article/details/gt2evwwwjdb.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmfwdja.html

Perl ........... 10
来源：http://dali.jqgufenzy.top/Article/details/gt2lnotescr.html

Scala .......... 10
来源：http://dali.yuanzhike.top/Article/details/gt2krrjxpmy.html

------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gt2uthcbbbr.html

合计 ........... 2106 条
来源：http://dali.yj20258888.top/Article/details/gt2ysycpohm.html

按章节统计：
来源：http://dali.9152youxi.cn/Article/details/gt2qqsooggv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.bjfxy.top/Article/details/gt2opfukxya.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gt2ifvzevkv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gt2iztkosmc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hxtyqlpr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ehwqpu.com/Article/details/gt2yyhzlssd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.nanxuanxn.top/Article/details/gt2tkljslma.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.feifeiyinyue.top/Article/details/gt2sliatpzn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yanxiufei.cn/Article/details/gt2znxjflia.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gt2orqzqugk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.pengpengdd.cyou/Article/details/gt2durdyksn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gt2nizrvney.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gt2ccxrmfab.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gt2ztfzxvzu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj20258888.top/Article/details/gt2kmkrvbge.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hongshengwenyu.top/Article/details/gt2dmqwngbx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gt2auoaxjjc.html

Q SQL 专题                              90
来源：http://dali.nwbrower.top/Article/details/gt2pizbnycb.html

R Bash 专题                             80
来源：http://dali.zhongyouzk.top/Article/details/gt2afljsgzr.html

S C / C++ 专题                          60
来源：http://dali.sufxvd.cn/Article/details/gt2thddjega.html

T 其他语言补充                          60
来源：http://dali.9152youxi.cn/Article/details/gt2hkmgqdjc.html

U 高频实用片段                         120
来源：http://dali.hnxiangtu.top/Article/details/gt2ycgnbpai.html

------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gt2aufayonm.html

合计                                  2106 条
来源：http://dali.iojbl.cn/Article/details/gt2axeaesid.html

--------------------------------------------------------------------------------
来源：http://dali.tian-w.cn/Article/details/gt2orlqngkc.html

使用提醒
来源：http://dali.cucudq.cn/Article/details/gt2xmexwzuz.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gt2qsuvuskn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jianghu66.top/Article/details/gt2biffboep.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hysaishi.cn/Article/details/gt2jtfferol.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hfeuikfm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.kuanghao11.cn/Article/details/gt2kfjemfxe.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.smart0.xyz/Article/details/gt2znarlnrx.html

—— 文件结束 ——
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nubmmzhk.html


<!-- 参考信息 -->