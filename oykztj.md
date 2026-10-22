代发 wailian999

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.guowangkeji.top/Article/details/gt2obmamlqu.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2edyebabc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yvedp.cn/Article/details/gt2ubhhddac.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2gpxzeqbc.html

[U01] Py：创建虚拟环境
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ulsmnrwm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jlsjyb.cn/Article/details/gt2xstuipbb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fengsongda.top/Article/details/gt2eargfqqo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.fzhhl.top/Article/details/gt2slzlpkzl.html

[U03] Py：加载 .env 配置
来源：http://dali.ybcxt.top/Article/details/gt2zlhjiyeq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ydzc1.top/Article/details/gt2sbmgjfxc.html

[U04] Py：变量调试打印
来源：http://dali.ydzc1.top/Article/details/gt2gyeyrzeq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.havefunace.top/Article/details/gt2dokywxob.html

[U05] Py：列表去重且保序
来源：http://dali.feifeiyinyue.top/Article/details/gt2yapznyfi.html

list(dict.fromkeys(arr))
来源：http://dali.sxryk.cn/Article/details/gt2kxqevsfc.html

[U06] Py：合并两个字典
来源：http://dali.0kj1m.cn/Article/details/gt2zclhiznr.html

{**a, **b}
来源：http://dali.yuanzhike.top/Article/details/gt2zkduwqxl.html

[U07] Py：反转字典键值
来源：http://dali.zdqjudy.top/Article/details/gt2fahhjulw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwbxirm.html

[U08] Py：展平二维列表
来源：http://dali.zhoulong.xyz/Article/details/gt2ugxpgkrl.html

[y for x in nested for y in x]
来源：http://dali.ehwqpu.com/Article/details/gt2yfnyqryi.html

[U09] Py：字典取最大值的键
来源：http://dali.hywenlv.cn/Article/details/gt2zfszpamb.html

max(d, key=d.get)
来源：http://dali.jlsjyb.cn/Article/details/gt2ojdpzgrr.html

[U10] Py：按值排序字典
来源：http://dali.cashguo.top/Article/details/gt2bujvjxdl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hammf.cn/Article/details/gt2ogsjpaxv.html

[U11] Py：生成器表达式
来源：http://dali.yonumen.top/Article/details/gt2oyxopqlt.html

(x * 2 for x in arr)
来源：http://dali.cdnleiting.top/Article/details/gt2njhclsjq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gaohongyu789.top/Article/details/gt2rvtohkml.html

Counter(arr).most_common(3)
来源：http://dali.yuxming.cn/Article/details/gt2cnwzjjef.html

[U13] Py：固定长度队列
来源：http://dali.yueranfly.top/Article/details/gt2sqizmsdf.html

deque(maxlen=10)
来源：http://dali.fzhhl.top/Article/details/gt2kyihvveo.html

[U14] Py：分组收集到列表
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjucvfla.html

defaultdict(list)
来源：http://dali.yj202588.top/Article/details/gt2yxhgjeio.html

[U15] Py：高精度计时
来源：http://dali.dashuyun.cn/Article/details/gt2juajshom.html

t = time.perf_counter()
来源：http://dali.jiagoushi.top/Article/details/gt2ojkbtlac.html

[U16] Py：命令行参数解析
来源：http://dali.yuxming.cn/Article/details/gt2dpciwuly.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yj20258888.top/Article/details/gt2mwwaptcu.html

[U17] Py：初始化日志
来源：http://dali.hnqzz.top/Article/details/gt2hrhqyriv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yonumen.top/Article/details/gt2alayenya.html

[U18] Py：预编译正则
来源：http://dali.hywenlv.cn/Article/details/gt2ytjzyqjo.html

pat = re.compile(r"\d+")
来源：http://dali.sysykeji.top/Article/details/gt2tqtwxwft.html

[U19] Py：正则替换带回调
来源：http://dali.guowangkeji.top/Article/details/gt2lfrkgczs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.fengsongda.top/Article/details/gt2owgqumwn.html

[U20] Py：缓存函数结果
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nevsbtkt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xziqi.cn/Article/details/gt2mcllyumb.html

[U21] Py：自定义上下文管理器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxxfjbco.html

@contextlib.contextmanager
来源：http://dali.yuxming.cn/Article/details/gt2fzvxzkec.html

[U22] Py：矩阵转置
来源：http://dali.nanxuanxn.top/Article/details/gt2ssctrpvt.html

list(zip(*m))
来源：http://dali.zhongyouzk.top/Article/details/gt2rpvvswke.html

[U23] Py：分块读取大文件
来源：http://dali.quarkkingdee.top/Article/details/gt2hmvopcyt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yuanzhike.top/Article/details/gt2sesbrqsl.html

[U24] Py：路径操作
来源：http://dali.chenzaomai.com/Article/details/gt2prwkilnk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yvedp.cn/Article/details/gt2dyntuuaf.html

[U25] Py：CSV 按字典读
来源：http://dali.pengpengdd.cyou/Article/details/gt2zggrnmty.html

csv.DictReader(f)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qhccvlqj.html

[U26] Py：并发下载
来源：http://dali.jinghuilouyu.cn/Article/details/gt2unjekbqw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.dianchejie.cn/Article/details/gt2exktznmu.html

[U27] Py：异步 HTTP
来源：http://dali.xinyue.icu/Article/details/gt2fnadwrgv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.bjfxy.top/Article/details/gt2dikgzfgc.html

[U28] Py：类型别名
来源：http://dali.zhiwuduotai.top/Article/details/gt2ynbsscio.html

UserId = int
来源：http://dali.yuanzhike.top/Article/details/gt2pztzlbue.html

[U29] Py：属性校验
来源：http://dali.cqqwz.cn/Article/details/gt2phaxkfzm.html

@property 与 @x.setter 配合
来源：http://dali.hfpthk.cn/Article/details/gt2nfjinofj.html

[U30] Py：数据类
来源：http://dali.yonumen.top/Article/details/gt2tnweiosv.html

@dataclass(slots=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ovnshfrr.html

[U31] Py：单测
来源：http://dali.dianchejie.cn/Article/details/gt2edwulaxm.html

python -m pytest -q
来源：http://dali.zhixingplan.top/Article/details/gt2qcjjtygu.html

[U32] Py：代码格式化
来源：http://dali.zdqjudy.top/Article/details/gt2dkcqocsd.html

ruff format . && ruff check --fix .
来源：http://dali.pycfn.com/Article/details/gt2kgkuanhr.html

[U33] Py：打包发布
来源：http://dali.guowangkeji.top/Article/details/gt2shcjqwsa.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yongpay.top/Article/details/gt2luzkodyp.html

[U34] Py：判断编码
来源：http://dali.hywenlv.cn/Article/details/gt2eotgdtik.html

chardet.detect(raw)
来源：http://dali.ppjwa.cn/Article/details/gt2qedmpyos.html

[U35] Py：发送邮件
来源：http://dali.snrcjt.cn/Article/details/gt2nwicssrb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj20258.top/Article/details/gt2qwbypesp.html

[U36] Py：定时任务
来源：http://dali.dashuyun.cn/Article/details/gt2zzxrsksw.html

schedule.every(10).minutes.do(job)
来源：http://dali.dianchejie.cn/Article/details/gt2vullodwr.html

[U37] Py：读写 Excel
来源：http://dali.yongpay.top/Article/details/gt2uetmjrhy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.quarkkingdee.top/Article/details/gt2qezmqnwb.html

[U38] Py：获取脚本所在目录
来源：http://dali.guowangkeji.top/Article/details/gt2xkqaqpsa.html

Path(__file__).resolve().parent
来源：http://dali.yongpay.top/Article/details/gt2gnnerqst.html

[U39] Py：判断是否在交互环境
来源：http://dali.daxiang520.top/Article/details/gt2msyrqkwe.html

sys.stdout.isatty()
来源：http://dali.yueranfly.top/Article/details/gt2kzptvvdg.html

[U40] Py：打印到标准错误
来源：http://dali.nwbrower.top/Article/details/gt2nnafwhra.html

print("err", file=sys.stderr)
来源：http://dali.kuanghao11.cn/Article/details/gt2usnuxmig.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.pengpengdd.cyou/Article/details/gt2osypdlbv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cqqwz.cn/Article/details/gt2hstpekfq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hammf.cn/Article/details/gt2vxoyxtmh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xinyue.icu/Article/details/gt2suemswem.html

[U43] PHP：声明命名空间
来源：http://dali.ivvv.top/Article/details/gt2nemrjaew.html

namespace App\Http;
来源：http://dali.hfpthk.cn/Article/details/gt2yoknnuxt.html

[U44] PHP：开启严格类型
来源：http://dali.xinyue.icu/Article/details/gt2qixdptrp.html

declare(strict_types=1);
来源：http://dali.aizwys.cn/Article/details/gt2wgwfvpet.html

[U45] PHP：类型声明与返回类型
来源：http://dali.wangdashe.top/Article/details/gt2jxrkbjtc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gt2xhclrmle.html

[U46] PHP：可空类型
来源：http://dali.yuxming.cn/Article/details/gt2siamelvi.html

?string $name = null
来源：http://dali.aizwys.cn/Article/details/gt2atibgzgw.html

[U47] PHP：联合类型
来源：http://dali.svipenyu.cn/Article/details/gt2popvhcoh.html

int|string $id
来源：http://dali.sufxvd.cn/Article/details/gt2wxwalyio.html

[U48] PHP：纯枚举
来源：http://dali.zhixingplan.top/Article/details/gt2lkczjrrj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yueranfly.top/Article/details/gt2yrhaluqh.html

[U49] PHP：只读属性
来源：http://dali.andypj.xyz/Article/details/gt2zaskglkr.html

public readonly string $name
来源：http://dali.hnxiangtu.top/Article/details/gt2gffdwcyp.html

[U50] PHP：构造器属性提升
来源：http://dali.wangdashe.top/Article/details/gt2zwyfynib.html

public function __construct(private int $id) {}
来源：http://dali.jqgfzy.top/Article/details/gt2sbzyrslw.html

[U51] PHP：数组解构
来源：http://dali.yvedp.cn/Article/details/gt2jundrret.html

[$a, $b] = $arr;
来源：http://dali.ydzc1.top/Article/details/gt2fsoinccr.html

[U52] PHP：箭头函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zmygitvw.html

$double = fn($x) => $x * 2;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkbmtbwf.html

[U53] PHP：空合并运算符
来源：http://dali.yuxming.cn/Article/details/gt2jjlvgtff.html

$v = $a ?? $b ?? "default";
来源：http://dali.zycfv.cn/Article/details/gt2qywbcoij.html

[U54] PHP：空安全调用
来源：http://dali.gotoacloud.top/Article/details/gt2zgrqwelr.html

$obj?->method()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bpjyfprn.html

[U55] PHP：match 表达式
来源：http://dali.ppjwa.cn/Article/details/gt2yyegdtsf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.feifeiyinyue.top/Article/details/gt2onamrroi.html

[U56] PHP：命名参数
来源：http://dali.daria6918.cn/Article/details/gt2ohukgkwq.html

f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gt2ngjruflp.html

[U57] PHP：字符串插值
来源：http://dali.yj202588.top/Article/details/gt2pwvnjucf.html

"值: {$a}"
来源：http://dali.meibo888.top/Article/details/gt2bepvyhrn.html

[U58] PHP：数组三件套
来源：http://dali.fzhhl.top/Article/details/gt2uzohehzx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cucudq.cn/Article/details/gt2hmxwcazd.html

[U59] PHP：自定义排序
来源：http://dali.guannengcc.top/Article/details/gt2ershmokc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gt2ijfpluuf.html

[U60] PHP：JSON 编解码
来源：http://dali.mhx1999.top/Article/details/gt2jfjerogy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hysaishi.cn/Article/details/gt2nnqoetto.html

[U61] PHP：正则
来源：http://dali.sxryk.cn/Article/details/gt2dhhtetzh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.daria6918.cn/Article/details/gt2rcztrocw.html

[U62] PHP：日期对象
来源：http://dali.zycfv.cn/Article/details/gt2umrbnlzs.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vvjsshae.html

[U63] PHP：文件读写
来源：http://dali.havefunace.top/Article/details/gt2xmsrymsx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.nanxuanxn.top/Article/details/gt2gmnultzi.html

[U64] PHP：目录遍历
来源：http://dali.0kj1m.cn/Article/details/gt2ggtluecx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yangfankeji.com/Article/details/gt2jawpsiao.html

[U65] PHP：会话
来源：http://dali.ivvv.top/Article/details/gt2vzllndxj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2iodxcayk.html

[U66] PHP：设置 Cookie
来源：http://dali.yvedp.cn/Article/details/gt2uwdgmjdo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yj202588.top/Article/details/gt2aezthreb.html

[U67] PHP：处理文件上传
来源：http://dali.hammf.cn/Article/details/gt2izdayxjc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.pycfn.com/Article/details/gt2vuktkssv.html

[U68] PHP：PDO 连接
来源：http://dali.cqqwz.cn/Article/details/gt2afqzkijy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinqigufen.top/Article/details/gt2wxbynrir.html

[U69] PHP：PDO 预处理
来源：http://dali.daria6918.cn/Article/details/gt2tfhjpnmw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj20258888.top/Article/details/gt2jazckyqp.html

[U70] PHP：PDO 事务
来源：http://dali.daxiang520.top/Article/details/gt2zkmdgzzz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yuanzhike.top/Article/details/gt2vihwlnvq.html

[U71] PHP：抛出异常
来源：http://dali.daxiang520.top/Article/details/gt2haizvbga.html

throw new RuntimeException("失败", 500);
来源：http://dali.snrcjt.cn/Article/details/gt2ahjftatu.html

[U72] PHP：写错误日志
来源：http://dali.andypj.xyz/Article/details/gt2jirzbeky.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hnxiangtu.top/Article/details/gt2uttnrgtn.html

[U73] PHP：读取 ini 配置
来源：http://dali.jiagoushi.top/Article/details/gt2lhpakqwe.html

parse_ini_file("config.ini", true)
来源：http://dali.birdmap.top/Article/details/gt2izyqlzac.html

[U74] PHP：读取环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wwrsdzrr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shangyingyoupin.top/Article/details/gt2thlfkenv.html

[U75] PHP：依赖注入
来源：http://dali.shzxlz.cn/Article/details/gt2axtdwmhe.html

composer require psr/container
来源：http://dali.shzxlz.cn/Article/details/gt2wxwrzcld.html

[U76] PHP：简单路由
来源：http://dali.smart0.xyz/Article/details/gt2yldumocz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yongpay.top/Article/details/gt2lbdkytjm.html

[U77] PHP：模板渲染
来源：http://dali.gogol.net.cn/Article/details/gt2srhqfurw.html

composer require twig/twig
来源：http://dali.zhiwuduotai.top/Article/details/gt2ldbxfmev.html

[U78] PHP：单元测试
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tnksnlog.html

composer require --dev phpunit/phpunit
来源：http://dali.yongpay.top/Article/details/gt2zpumezwl.html

[U79] PHP：静态分析
来源：http://dali.yj20258.top/Article/details/gt2ecivtfro.html

composer require --dev phpstan/phpstan
来源：http://dali.jianghu66.top/Article/details/gt2vlpiqppy.html

[U80] PHP：代码规范修复
来源：http://dali.xinyue.icu/Article/details/gt2ntxdtrgv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cucudq.cn/Article/details/gt2ifaitmin.html

[U81] JS：初始化项目
来源：http://dali.zhixingplan.top/Article/details/gt2yciudcve.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2faqeyxrc.html

[U82] JS：package.json 脚本
来源：http://dali.xuetiantiany.cn/Article/details/gt2iheghxun.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ydzc1.top/Article/details/gt2qcugdlug.html

[U83] JS：ES Module 导入导出
来源：http://dali.nanxinkj.top/Article/details/gt2yvefiztk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.dashuyun.cn/Article/details/gt2rbjfrxmz.html

[U84] JS：CommonJS 写法
来源：http://dali.wangshuangyany.cn/Article/details/gt2hfzsvmic.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.haohaochexian.top/Article/details/gt2rozmbrnj.html

[U85] JS：可选链
来源：http://dali.jiagoushi.top/Article/details/gt2wribwlwq.html

a?.b?.c
来源：http://dali.yvedp.cn/Article/details/gt2wxsexgju.html

[U86] JS：空值合并
来源：http://dali.yj20258.top/Article/details/gt2mvacinom.html

a ?? b
来源：http://dali.meibo888.top/Article/details/gt2kwzdnnbp.html

[U87] JS：解构默认值
来源：http://dali.xinyue.icu/Article/details/gt2gkdbbltp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.guannengcc.top/Article/details/gt2iiwinpsr.html

[U88] JS：对象展开合并
来源：http://dali.yangfankeji.com/Article/details/gt2vufobpyz.html

{ ...a, ...b }
来源：http://dali.smart0.xyz/Article/details/gt2rigdhmiu.html

[U89] JS：数组去重
来源：http://dali.daria6918.cn/Article/details/gt2sncnjkfd.html

[...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gt2xamocktd.html

[U90] JS：数字数组排序
来源：http://dali.zhoulong.xyz/Article/details/gt2qrzveemp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gt2epjygepo.html

[U91] JS：对象键值遍历
来源：http://dali.ppjwa.cn/Article/details/gt2vqommkmr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.andypj.xyz/Article/details/gt2kvnfjivh.html

[U92] JS：深拷贝
来源：http://dali.hnqzz.top/Article/details/gt2rypiyzjz.html

structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gt2dfqruxlx.html

[U93] JS：模板字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzimsaef.html

`共 ${n} 条`
来源：http://dali.redwolf501.top/Article/details/gt2bpgvrsnw.html

[U94] JS：箭头函数
来源：http://dali.316326.xyz/Article/details/gt2alfcsqgv.html

const double = x => x * 2;
来源：http://dali.zycfv.cn/Article/details/gt2fsswmgtm.html

[U95] JS：Promise 包装
来源：http://dali.316326.xyz/Article/details/gt2rbowjdhk.html

new Promise((resolve, reject) => {})
来源：http://dali.shangyingyoupin.top/Article/details/gt2cmnczezd.html

[U96] JS：async/await 与异常
来源：http://dali.hnxiangtu.top/Article/details/gt2zshgjfgs.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gt2zmbqndrk.html

[U97] JS：并发请求
来源：http://dali.smart0.xyz/Article/details/gt2aivzdqyr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gt2efvxrwso.html

[U98] JS：fetch 带 JSON
来源：http://dali.daxiang520.top/Article/details/gt2gqnjejsx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yangfankeji.com/Article/details/gt2eciaryse.html

[U99] JS：事件监听
来源：http://dali.0kj1m.cn/Article/details/gt2qrmtvuyi.html

el.addEventListener("click", e => {})
来源：http://dali.hywenlv.cn/Article/details/gt2fejdnhls.html

[U100] JS：DOM 查询
来源：http://dali.chenjidiqi.icu/Article/details/gt2njpumscz.html

document.querySelector(".item")
来源：http://dali.daxiang520.top/Article/details/gt2ikczjkoo.html

[U101] JS：classList 操作
来源：http://dali.ivvv.top/Article/details/gt2cnkqdzzu.html

el.classList.toggle("active")
来源：http://dali.jlsjyb.cn/Article/details/gt2qtketbxb.html

[U102] JS：本地存储
来源：http://dali.bjfxy.top/Article/details/gt2haheroak.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.gogol.net.cn/Article/details/gt2exkcylvu.html

[U103] JS：定时器
来源：http://dali.birdmap.top/Article/details/gt2zzaxkjgx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yuxming.cn/Article/details/gt2gfeqxlua.html

[U104] JS：防抖
来源：http://dali.0kj1m.cn/Article/details/gt2jvfanpwj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gt2ybixxsdj.html

[U105] JS：节流
来源：http://dali.cheryme.top/Article/details/gt2vjaeaeix.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2vmafeyec.html

[U106] JS：日期格式化
来源：http://dali.yueranfly.top/Article/details/gt2yoytwmbq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenlongwang.top/Article/details/gt2inmksjhs.html

[U107] JS：数字千分位
来源：http://dali.cdnleiting.top/Article/details/gt2hnkbthvl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yanxiufei.cn/Article/details/gt2irkaakaj.html

[U108] JS：随机整数
来源：http://dali.shuidangran.top/Article/details/gt2kgpochoc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wydpqtmr.html

[U109] JS：数组分组
来源：http://dali.ivvv.top/Article/details/gt2ncvcldmc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gt2gsmtrbwb.html

[U110] JS：数组分块
来源：http://dali.quarkkingdee.top/Article/details/gt2unmrlgun.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yanxiufei.cn/Article/details/gt2iydzeoou.html

[U111] JS：对象转 Map
来源：http://dali.hnqzz.top/Article/details/gt2kliwsysk.html

new Map(Object.entries(obj))
来源：http://dali.jiagoushi.top/Article/details/gt2cqjgqdco.html

[U112] JS：字符串补位
来源：http://dali.dashuyun.cn/Article/details/gt2ohbbhyxs.html

"7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vzzulfuy.html

[U113] JS：正则替换全部
来源：http://dali.zhoulong.xyz/Article/details/gt2ffrpcfon.html

s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2hiybzejr.html

[U114] JS：JSON 深比较
来源：http://dali.yj20258888.top/Article/details/gt2vdrticek.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.9152youxi.cn/Article/details/gt2hjehakeg.html

[U115] JS：生成 UUID
来源：http://dali.daria6918.cn/Article/details/gt2uqtokgwn.html

crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gt2dbaojvtt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.tianlin.xyz/Article/details/gt2qoonjeyj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uscjtevl.html

[U117] JS：单元测试
来源：http://dali.yueranfly.top/Article/details/gt2qubpkrtf.html

npm i -D vitest;  npx vitest
来源：http://dali.yuxming.cn/Article/details/gt2swxkqxto.html

[U118] JS：开发服务器
来源：http://dali.chenjidiqi.icu/Article/details/gt2gsgokiih.html

npm i -D vite;  npx vite
来源：http://dali.hysaishi.cn/Article/details/gt2xdrfphjq.html

[U119] JS：生产构建
来源：http://dali.hammf.cn/Article/details/gt2aytjuski.html

npx vite build
来源：http://dali.yueranfly.top/Article/details/gt2fzhozarj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hfpthk.cn/Article/details/gt2nqdsvimo.html

import.meta.env.VITE_API_URL
来源：http://dali.feifeiyinyue.top/Article/details/gt2jgqojqzn.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2zutquakl.html

统计汇总
来源：http://dali.0kj1m.cn/Article/details/gt2sqvrswin.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2lgqlkygd.html

按语言统计（条）：
来源：http://dali.snrcjt.cn/Article/details/gt2zwigzhmr.html

Python ......... 252
来源：http://dali.haohaochexian.top/Article/details/gt2yrnegnkj.html

PHP ............ 252
来源：http://dali.birdmap.top/Article/details/gt2wnolceob.html

JavaScript ..... 252
来源：http://dali.yj202588.top/Article/details/gt2xqxoyumy.html

TypeScript ..... 212
来源：http://dali.dashuyun.cn/Article/details/gt2xxxminwx.html

Java ........... 212
来源：http://dali.fengsongda.top/Article/details/gt2pnknmgmy.html

Go ............. 212
来源：http://dali.zhoulong.xyz/Article/details/gt2hekjbkrc.html

Ruby ........... 212
来源：http://dali.jinqigufen.top/Article/details/gt2egtmisyw.html

C# ............. 212
来源：http://dali.guowangkeji.top/Article/details/gt2lmdibsxa.html

C .............. 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eegenbba.html

C++ ............ 30
来源：http://dali.cdnleiting.top/Article/details/gt2uttmpogj.html

SQL ............ 90
来源：http://dali.gogol.net.cn/Article/details/gt2znejrves.html

Bash ........... 80
来源：http://dali.316326.xyz/Article/details/gt2thnpodew.html

Kotlin ......... 15
来源：http://dali.yangfankeji.com/Article/details/gt2sbxvnugc.html

Swift .......... 15
来源：http://dali.jlsjyb.cn/Article/details/gt2mhrueyeb.html

Lua ............ 10
来源：http://dali.wangshuangyany.cn/Article/details/gt2phxjrizp.html

Perl ........... 10
来源：http://dali.yangfankeji.com/Article/details/gt2qqoaqzax.html

Scala .......... 10
来源：http://dali.dianchejie.cn/Article/details/gt2dnxkgdtt.html

------------------------------------
来源：http://dali.hammf.cn/Article/details/gt2fchnbxgh.html

合计 ........... 2106 条
来源：http://dali.gaohongyu789.top/Article/details/gt2rlkauptf.html

按章节统计：
来源：http://dali.tianlin.xyz/Article/details/gt2kpihzndo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rcmipozh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gt2labxuxff.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gt2ixxihnek.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yuxming.cn/Article/details/gt2fwihlhoa.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ruzdxxub.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.andypj.xyz/Article/details/gt2vgyopfwk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.meibo888.top/Article/details/gt2telfddck.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.feifeiyinyue.top/Article/details/gt2oeipnlfq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gt2dyprxbdi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.fzhhl.top/Article/details/gt2tqittham.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tcfpxydr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gt2wwiyqjzn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gt2uudqzzye.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhiwuduotai.top/Article/details/gt2jfcufkqo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.wangshuangyany.cn/Article/details/gt2yltrvsip.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gt2qqehoxkz.html

Q SQL 专题                              90
来源：http://dali.yangfankeji.com/Article/details/gt2pjykpzvd.html

R Bash 专题                             80
来源：http://dali.daria6918.cn/Article/details/gt2epngmdel.html

S C / C++ 专题                          60
来源：http://dali.jyoumei.cn/Article/details/gt2lrjrjikt.html

T 其他语言补充                          60
来源：http://dali.meibo888.top/Article/details/gt2nxrcckbo.html

U 高频实用片段                         120
来源：http://dali.jinqigfzy.top/Article/details/gt2dxddimqd.html

------------------------------------
来源：http://dali.redwolf501.top/Article/details/gt2zmjeddjr.html

合计                                  2106 条
来源：http://dali.andypj.xyz/Article/details/gt2ayrsbnlv.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gt2gzwogwlu.html

使用提醒
来源：http://dali.shangyingyoupin.top/Article/details/gt2oktjkqbd.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gt2cpewpvrn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nfkgikbb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hammf.cn/Article/details/gt2emsnsryw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.nwbrower.top/Article/details/gt2wiqivfnf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.redwolf501.top/Article/details/gt2gbrxqjps.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.feifeiyinyue.top/Article/details/gt2bikqqcvd.html

—— 文件结束 ——
来源：http://dali.fengsongda.top/Article/details/gt2lbpneote.html


<!-- 参考信息 -->