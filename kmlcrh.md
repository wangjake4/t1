代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.birdmap.top/Article/details/gt2dukgapii.html

[T55] Scala：集合过滤
来源：http://dali.fengsongda.top/Article/details/gt2ngzwinlf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qfyzqgju.html

[T56] Scala：样例类
来源：http://dali.gzhubu.top/Article/details/gt2wouypuxa.html

case class User(name: String, age: Int)
来源：http://dali.ehwqpu.com/Article/details/gt2prfrhrkz.html

[T57] Scala：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gt2fxqzbkvi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.feifeiyinyue.top/Article/details/gt2acyfxbzj.html

[T58] Scala：函数定义
来源：http://dali.yuanzhike.top/Article/details/gt2nfbjukzt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daxiang520.top/Article/details/gt2tlukcwoo.html

[T59] Scala：循环
来源：http://dali.zhoulong.xyz/Article/details/gt2dkgupcsk.html

for (i <- 1 to 10) println(i)
来源：http://dali.sxryk.cn/Article/details/gt2hkdhwukv.html

[T60] Scala：折叠
来源：http://dali.yueranfly.top/Article/details/gt2dfmcnxok.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hnxiangtu.top/Article/details/gt2pdvfimri.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2wqzemyjq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxinkj.top/Article/details/gt2cwwpfvoq.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2bhffzldu.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigfzy.top/Article/details/gt2efnzsqma.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cashguo.top/Article/details/gt2vztbmaqg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tanke756.top/Article/details/gt2hvsovgnk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jsaktqcy.html

[U03] Py：加载 .env 配置
来源：http://dali.guannengcc.top/Article/details/gt2qfjtjgng.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.andypj.xyz/Article/details/gt2uitgudmg.html

[U04] Py：变量调试打印
来源：http://dali.yj20258.top/Article/details/gt2znaimbpd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cheryme.top/Article/details/gt2yjmyvpsa.html

[U05] Py：列表去重且保序
来源：http://dali.aizwys.cn/Article/details/gt2lwuujxjc.html

list(dict.fromkeys(arr))
来源：http://dali.zhoulong.xyz/Article/details/gt2tiesmvmn.html

[U06] Py：合并两个字典
来源：http://dali.chenlongwang.top/Article/details/gt2lindiosl.html

{**a, **b}
来源：http://dali.sufxvd.cn/Article/details/gt2cczqtjpg.html

[U07] Py：反转字典键值
来源：http://dali.dianchejie.cn/Article/details/gt2unzsqwrx.html

{v: k for k, v in d.items()}
来源：http://dali.shzxlz.cn/Article/details/gt2xiedzucx.html

[U08] Py：展平二维列表
来源：http://dali.havefunace.top/Article/details/gt2ztnxilvm.html

[y for x in nested for y in x]
来源：http://dali.andypj.xyz/Article/details/gt2xiqxqgyt.html

[U09] Py：字典取最大值的键
来源：http://dali.havefunace.top/Article/details/gt2wxniyytn.html

max(d, key=d.get)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lclhdium.html

[U10] Py：按值排序字典
来源：http://dali.jyoumei.cn/Article/details/gt2kgsqqlgo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yonumen.top/Article/details/gt2nhjggrja.html

[U11] Py：生成器表达式
来源：http://dali.havefunace.top/Article/details/gt2qyowvwbd.html

(x * 2 for x in arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2xodtyxbe.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.birdmap.top/Article/details/gt2wizmjgkf.html

Counter(arr).most_common(3)
来源：http://dali.xinyue.icu/Article/details/gt2pdskqbqe.html

[U13] Py：固定长度队列
来源：http://dali.cashguo.top/Article/details/gt2gaefulrm.html

deque(maxlen=10)
来源：http://dali.sxryk.cn/Article/details/gt2llfqtuic.html

[U14] Py：分组收集到列表
来源：http://dali.gaohongyu789.top/Article/details/gt2bmlgghbh.html

defaultdict(list)
来源：http://dali.hnqzz.top/Article/details/gt2tjlqxuvm.html

[U15] Py：高精度计时
来源：http://dali.zhengqikj.top/Article/details/gt2snvicmqo.html

t = time.perf_counter()
来源：http://dali.meibo888.top/Article/details/gt2xfwphxxw.html

[U16] Py：命令行参数解析
来源：http://dali.hongshengwenyu.top/Article/details/gt2avobyjce.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinqigfzy.top/Article/details/gt2bvsbjnlq.html

[U17] Py：初始化日志
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eostolzs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guannengcc.top/Article/details/gt2ntxxbfoh.html

[U18] Py：预编译正则
来源：http://dali.fengsongda.top/Article/details/gt2pucqerfb.html

pat = re.compile(r"\d+")
来源：http://dali.wangdashe.top/Article/details/gt2fksnqtlh.html

[U19] Py：正则替换带回调
来源：http://dali.yj202588.top/Article/details/gt2gznqmait.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nanxuanxn.top/Article/details/gt2ggwglepg.html

[U20] Py：缓存函数结果
来源：http://dali.xylfe.cn/Article/details/gt2whazwpuw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gzhubu.top/Article/details/gt2udvvhrtf.html

[U21] Py：自定义上下文管理器
来源：http://dali.daria6918.cn/Article/details/gt2jzhwmryx.html

@contextlib.contextmanager
来源：http://dali.yonumen.top/Article/details/gt2lknhkdjf.html

[U22] Py：矩阵转置
来源：http://dali.wangshuangyany.cn/Article/details/gt2awmmhnad.html

list(zip(*m))
来源：http://dali.yj202588.top/Article/details/gt2hsokkpwm.html

[U23] Py：分块读取大文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2kbpqkxqr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jqgufenzy.top/Article/details/gt2zbaibwgl.html

[U24] Py：路径操作
来源：http://dali.chenzaomai.com/Article/details/gt2eexumano.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gt2mvpewixm.html

[U25] Py：CSV 按字典读
来源：http://dali.mhx1999.top/Article/details/gt2qfyrmtpc.html

csv.DictReader(f)
来源：http://dali.iojbl.cn/Article/details/gt2aawrtmyd.html

[U26] Py：并发下载
来源：http://dali.cashguo.top/Article/details/gt2jrhnhiup.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jqgufenzy.top/Article/details/gt2cwbmjlvm.html

[U27] Py：异步 HTTP
来源：http://dali.gaohongyu789.top/Article/details/gt2bljhkvdj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sweek.top/Article/details/gt2mzyhrklh.html

[U28] Py：类型别名
来源：http://dali.jqgfzy.top/Article/details/gt2rotodxlc.html

UserId = int
来源：http://dali.dianchejie.cn/Article/details/gt2zpshzuls.html

[U29] Py：属性校验
来源：http://dali.cqqwz.cn/Article/details/gt2pfddiiuo.html

@property 与 @x.setter 配合
来源：http://dali.mhx1999.top/Article/details/gt2ftlqzhlz.html

[U30] Py：数据类
来源：http://dali.smart0.xyz/Article/details/gt2gxlargtz.html

@dataclass(slots=True)
来源：http://dali.tian-w.cn/Article/details/gt2fwaufwnr.html

[U31] Py：单测
来源：http://dali.guowangkeji.top/Article/details/gt2tclztoey.html

python -m pytest -q
来源：http://dali.nanxuanxn.top/Article/details/gt2lhunmqlw.html

[U32] Py：代码格式化
来源：http://dali.yonumen.top/Article/details/gt2gqqkcpfj.html

ruff format . && ruff check --fix .
来源：http://dali.iojbl.cn/Article/details/gt2cpleolqs.html

[U33] Py：打包发布
来源：http://dali.smart0.xyz/Article/details/gt2sbnzmxss.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.andypj.xyz/Article/details/gt2wspseqef.html

[U34] Py：判断编码
来源：http://dali.daxiang520.top/Article/details/gt2obzyhcfn.html

chardet.detect(raw)
来源：http://dali.hfpthk.cn/Article/details/gt2yqkebuqm.html

[U35] Py：发送邮件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ckadiknn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.aizwys.cn/Article/details/gt2uzyjuibg.html

[U36] Py：定时任务
来源：http://dali.quarkkingdee.top/Article/details/gt2osjgdjcu.html

schedule.every(10).minutes.do(job)
来源：http://dali.snrcjt.cn/Article/details/gt2hzjcbjvu.html

[U37] Py：读写 Excel
来源：http://dali.redwolf501.top/Article/details/gt2qedrxfly.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.fzhhl.top/Article/details/gt2chubwktm.html

[U38] Py：获取脚本所在目录
来源：http://dali.nanxinkj.top/Article/details/gt2doyslrai.html

Path(__file__).resolve().parent
来源：http://dali.fzhhl.top/Article/details/gt2jplenuxq.html

[U39] Py：判断是否在交互环境
来源：http://dali.iojbl.cn/Article/details/gt2txpvfimc.html

sys.stdout.isatty()
来源：http://dali.smart0.xyz/Article/details/gt2sgcnuowr.html

[U40] Py：打印到标准错误
来源：http://dali.zdqjudy.top/Article/details/gt2ppmbupsy.html

print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gt2smnzpgyi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.haohaochexian.top/Article/details/gt2ejlhuxva.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.daxiang520.top/Article/details/gt2fbhcxnqq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cucudq.cn/Article/details/gt2blgguqfe.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.dashuyun.cn/Article/details/gt2kmwvgxak.html

[U43] PHP：声明命名空间
来源：http://dali.zhongyouzk.top/Article/details/gt2rienunox.html

namespace App\Http;
来源：http://dali.hammf.cn/Article/details/gt2wkiqnqma.html

[U44] PHP：开启严格类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2svzjiipp.html

declare(strict_types=1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tkblquri.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenlongwang.top/Article/details/gt2uacqdtxq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gt2cdwcxtyv.html

[U46] PHP：可空类型
来源：http://dali.quarkkingdee.top/Article/details/gt2amwmurnv.html

?string $name = null
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ojdhwoug.html

[U47] PHP：联合类型
来源：http://dali.9152youxi.cn/Article/details/gt2muynjixj.html

int|string $id
来源：http://dali.ydzc1.top/Article/details/gt2qnfheequ.html

[U48] PHP：纯枚举
来源：http://dali.meibo888.top/Article/details/gt2azpyyene.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yangfankeji.com/Article/details/gt2bcmprerd.html

[U49] PHP：只读属性
来源：http://dali.cucudq.cn/Article/details/gt2haqmpwvx.html

public readonly string $name
来源：http://dali.yvedp.cn/Article/details/gt2rufyvvzm.html

[U50] PHP：构造器属性提升
来源：http://dali.aibaodan.cn/Article/details/gt2wbxwtkbn.html

public function __construct(private int $id) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2mpyoguit.html

[U51] PHP：数组解构
来源：http://dali.pycfn.com/Article/details/gt2iafejind.html

[$a, $b] = $arr;
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmnqctrf.html

[U52] PHP：箭头函数
来源：http://dali.cashguo.top/Article/details/gt2pfexerwz.html

$double = fn($x) => $x * 2;
来源：http://dali.redwolf501.top/Article/details/gt2qwxxdqcy.html

[U53] PHP：空合并运算符
来源：http://dali.chenzaomai.com/Article/details/gt2wbhddcoo.html

$v = $a ?? $b ?? "default";
来源：http://dali.vqdsnc.cn/Article/details/gt2zewrmheg.html

[U54] PHP：空安全调用
来源：http://dali.ppjwa.cn/Article/details/gt2jlktwomm.html

$obj?->method()
来源：http://dali.316326.xyz/Article/details/gt2lvhqtelh.html

[U55] PHP：match 表达式
来源：http://dali.cashguo.top/Article/details/gt2rtzocksb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.316326.xyz/Article/details/gt2lknaplld.html

[U56] PHP：命名参数
来源：http://dali.cqqwz.cn/Article/details/gt2rtjxpgkm.html

f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gt2dzicmfsu.html

[U57] PHP：字符串插值
来源：http://dali.cheryme.top/Article/details/gt2iqkwdvld.html

"值: {$a}"
来源：http://dali.ybcxt.top/Article/details/gt2ghnknyea.html

[U58] PHP：数组三件套
来源：http://dali.bjfxy.top/Article/details/gt2juiozduv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cglqekdz.html

[U59] PHP：自定义排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nffjecgm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gt2odomxqlh.html

[U60] PHP：JSON 编解码
来源：http://dali.chenjidiqi.icu/Article/details/gt2zjgigpil.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zycfv.cn/Article/details/gt2yumdearb.html

[U61] PHP：正则
来源：http://dali.iojbl.cn/Article/details/gt2sdslhyyq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2jzzhglii.html

[U62] PHP：日期对象
来源：http://dali.wangdashe.top/Article/details/gt2hnuhhvez.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.fengsongda.top/Article/details/gt2uaxzyvjh.html

[U63] PHP：文件读写
来源：http://dali.tanke756.top/Article/details/gt2ydwgogmc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.chenzaomai.com/Article/details/gt2mpdezyem.html

[U64] PHP：目录遍历
来源：http://dali.yj202588.top/Article/details/gt2vbrazfdv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jiagoushi.top/Article/details/gt2llpvzwkp.html

[U65] PHP：会话
来源：http://dali.daria6918.cn/Article/details/gt2xllcvexp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2zisiiorc.html

[U66] PHP：设置 Cookie
来源：http://dali.cheryme.top/Article/details/gt2iqqylksx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yueranfly.top/Article/details/gt2ophfywej.html

[U67] PHP：处理文件上传
来源：http://dali.yuxming.cn/Article/details/gt2zxijjcsf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jiagoushi.top/Article/details/gt2fvfxssue.html

[U68] PHP：PDO 连接
来源：http://dali.yanxiufei.cn/Article/details/gt2nvnljkqy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.dashuyun.cn/Article/details/gt2ibuieahc.html

[U69] PHP：PDO 预处理
来源：http://dali.sxryk.cn/Article/details/gt2zklkvkln.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hnqzz.top/Article/details/gt2okaytdaw.html

[U70] PHP：PDO 事务
来源：http://dali.andypj.xyz/Article/details/gt2pgyseikj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yvedp.cn/Article/details/gt2fxnjnyzl.html

[U71] PHP：抛出异常
来源：http://dali.xuetiantiany.cn/Article/details/gt2ajbkjxyk.html

throw new RuntimeException("失败", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hpkstwoh.html

[U72] PHP：写错误日志
来源：http://dali.dashuyun.cn/Article/details/gt2ehuzkfgm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xinyue.icu/Article/details/gt2chqzqlyv.html

[U73] PHP：读取 ini 配置
来源：http://dali.ehwqpu.com/Article/details/gt2bqmhhsrn.html

parse_ini_file("config.ini", true)
来源：http://dali.ydzc1.top/Article/details/gt2wpkivygj.html

[U74] PHP：读取环境变量
来源：http://dali.guannengcc.top/Article/details/gt2adqtmwdr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xinyue.icu/Article/details/gt2qqfrfgfs.html

[U75] PHP：依赖注入
来源：http://dali.vqdsnc.cn/Article/details/gt2rsjtowbj.html

composer require psr/container
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yncdrkjr.html

[U76] PHP：简单路由
来源：http://dali.gzhubu.top/Article/details/gt2dclwricv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hnqzz.top/Article/details/gt2dqqxxpga.html

[U77] PHP：模板渲染
来源：http://dali.hfpthk.cn/Article/details/gt2uasznwsu.html

composer require twig/twig
来源：http://dali.jqgfzy.top/Article/details/gt2eztrcfsf.html

[U78] PHP：单元测试
来源：http://dali.zhongyouzk.top/Article/details/gt2bmgnkrtn.html

composer require --dev phpunit/phpunit
来源：http://dali.sweek.top/Article/details/gt2yddmwdap.html

[U79] PHP：静态分析
来源：http://dali.yangfankeji.com/Article/details/gt2iyhzchiv.html

composer require --dev phpstan/phpstan
来源：http://dali.yj20258888.top/Article/details/gt2uajstenp.html

[U80] PHP：代码规范修复
来源：http://dali.yj20258888.top/Article/details/gt2ypcpxzoh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.redwolf501.top/Article/details/gt2cvgqrtmj.html

[U81] JS：初始化项目
来源：http://dali.xziqi.cn/Article/details/gt2wzgplbeb.html

npm init -y;  npm i express
来源：http://dali.pengpengdd.cyou/Article/details/gt2voulowop.html

[U82] JS：package.json 脚本
来源：http://dali.chenzaomai.com/Article/details/gt2vjlihupt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jiagoushi.top/Article/details/gt2togcmawn.html

[U83] JS：ES Module 导入导出
来源：http://dali.jianghu66.top/Article/details/gt2rzftekpb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.dashuyun.cn/Article/details/gt2sdbwsoxq.html

[U84] JS：CommonJS 写法
来源：http://dali.aizwys.cn/Article/details/gt2nhlwwqtg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.feifeiyinyue.top/Article/details/gt2vknxajgv.html

[U85] JS：可选链
来源：http://dali.wangdashe.top/Article/details/gt2daxgpiqe.html

a?.b?.c
来源：http://dali.xuanzx.com/Article/details/gt2nueiepol.html

[U86] JS：空值合并
来源：http://dali.zhiwuduotai.top/Article/details/gt2noekgwxh.html

a ?? b
来源：http://dali.yj202588.top/Article/details/gt2bmnhehsp.html

[U87] JS：解构默认值
来源：http://dali.sxryk.cn/Article/details/gt2orhowflt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.fengsongda.top/Article/details/gt2nmwlntrd.html

[U88] JS：对象展开合并
来源：http://dali.cashguo.top/Article/details/gt2roqcygal.html

{ ...a, ...b }
来源：http://dali.ybcxt.top/Article/details/gt2rpipvvnm.html

[U89] JS：数组去重
来源：http://dali.chenjidiqi.icu/Article/details/gt2sqcmaaro.html

[...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gt2dsiayadw.html

[U90] JS：数字数组排序
来源：http://dali.dashuyun.cn/Article/details/gt2ucjfyoyd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gt2pgncxjpb.html

[U91] JS：对象键值遍历
来源：http://dali.gotoacloud.top/Article/details/gt2ahacuavw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.tianlin.xyz/Article/details/gt2dbibzyjw.html

[U92] JS：深拷贝
来源：http://dali.zhengqikj.top/Article/details/gt2exqvdfsd.html

structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2ckkbuyrq.html

[U93] JS：模板字符串
来源：http://dali.andypj.xyz/Article/details/gt2zgcofcks.html

`共 ${n} 条`
来源：http://dali.kuanghao11.cn/Article/details/gt2fdsjfgvi.html

[U94] JS：箭头函数
来源：http://dali.yj202588.top/Article/details/gt2xofexydc.html

const double = x => x * 2;
来源：http://dali.zdqjudy.top/Article/details/gt2ahoqyeua.html

[U95] JS：Promise 包装
来源：http://dali.tian-w.cn/Article/details/gt2nxcclrrx.html

new Promise((resolve, reject) => {})
来源：http://dali.haohaochexian.top/Article/details/gt2qjxchhlh.html

[U96] JS：async/await 与异常
来源：http://dali.yuanzhike.top/Article/details/gt2kkqjqtuf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gt2zmpdvarv.html

[U97] JS：并发请求
来源：http://dali.sxryk.cn/Article/details/gt2ruirimll.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ifnzutsf.html

[U98] JS：fetch 带 JSON
来源：http://dali.jyoumei.cn/Article/details/gt2febuvtrp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.vqdsnc.cn/Article/details/gt2bsvusttc.html

[U99] JS：事件监听
来源：http://dali.aizwys.cn/Article/details/gt2edijegos.html

el.addEventListener("click", e => {})
来源：http://dali.xziqi.cn/Article/details/gt2tjhgxpdi.html

[U100] JS：DOM 查询
来源：http://dali.gogol.net.cn/Article/details/gt2aezkxhef.html

document.querySelector(".item")
来源：http://dali.yuanzhike.top/Article/details/gt2fuvpuknm.html

[U101] JS：classList 操作
来源：http://dali.aibaodan.cn/Article/details/gt2wotzcxrl.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2tojrhqtk.html

[U102] JS：本地存储
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hehpztou.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shangyingyoupin.top/Article/details/gt2bduhhwtc.html

[U103] JS：定时器
来源：http://dali.gaohongyu789.top/Article/details/gt2gpfkojnc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinqigfzy.top/Article/details/gt2szlkycbc.html

[U104] JS：防抖
来源：http://dali.gzhubu.top/Article/details/gt2xoqgidqj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gt2juvuymxy.html

[U105] JS：节流
来源：http://dali.zhongyouzk.top/Article/details/gt2ruszcxqo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cqqwz.cn/Article/details/gt2exqrgnwm.html

[U106] JS：日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gt2uexqjqyn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhixingplan.top/Article/details/gt2iwqtfext.html

[U107] JS：数字千分位
来源：http://dali.zdqjudy.top/Article/details/gt2nmlhpqyw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gt2pttrvfcz.html

[U108] JS：随机整数
来源：http://dali.yanxiufei.cn/Article/details/gt2vskhzsph.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.wangdashe.top/Article/details/gt2ldloihor.html

[U109] JS：数组分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2xbdbfyqk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pxzzkzyy.html

[U110] JS：数组分块
来源：http://dali.yanxiufei.cn/Article/details/gt2rkfpguaw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ivvv.top/Article/details/gt2vhjqobke.html

[U111] JS：对象转 Map
来源：http://dali.fzhhl.top/Article/details/gt2qwergfoc.html

new Map(Object.entries(obj))
来源：http://dali.meibo888.top/Article/details/gt2gzloybst.html

[U112] JS：字符串补位
来源：http://dali.hfpthk.cn/Article/details/gt2smaztpxa.html

"7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gt2eeogynyp.html

[U113] JS：正则替换全部
来源：http://dali.jqgufenzy.top/Article/details/gt2nizxciwx.html

s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2hiutxmwy.html

[U114] JS：JSON 深比较
来源：http://dali.fzhhl.top/Article/details/gt2bhygthwc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hammf.cn/Article/details/gt2brgawepi.html

[U115] JS：生成 UUID
来源：http://dali.cucudq.cn/Article/details/gt2oodzvkif.html

crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gt2wdijdcvp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.svipenyu.cn/Article/details/gt2rwvypahs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.mhx1999.top/Article/details/gt2ookxpjwm.html

[U117] JS：单元测试
来源：http://dali.gogol.net.cn/Article/details/gt2bfleannt.html

npm i -D vitest;  npx vitest
来源：http://dali.zhiwuduotai.top/Article/details/gt2xyfnyibk.html

[U118] JS：开发服务器
来源：http://dali.tian-w.cn/Article/details/gt2wkfajxgd.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgylgzx.html

[U119] JS：生产构建
来源：http://dali.jqgufenzy.top/Article/details/gt2twiurgpm.html

npx vite build
来源：http://dali.wangdashe.top/Article/details/gt2ooavpwzp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xziqi.cn/Article/details/gt2lazkmirg.html

import.meta.env.VITE_API_URL
来源：http://dali.pycfn.com/Article/details/gt2zmjsglvm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2aylffteb.html

统计汇总
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2orimsmbp.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2jwhbymib.html

按语言统计（条）：
来源：http://dali.andypj.xyz/Article/details/gt2quazzrpc.html

Python ......... 252
来源：http://dali.yvedp.cn/Article/details/gt2lbtpjngk.html

PHP ............ 252
来源：http://dali.xinyue.icu/Article/details/gt2xjwnqfxt.html

JavaScript ..... 252
来源：http://dali.yj20258.top/Article/details/gt2gzbclfzl.html

TypeScript ..... 212
来源：http://dali.gzhubu.top/Article/details/gt2vpffxzru.html

Java ........... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kghucpdx.html

Go ............. 212
来源：http://dali.hongshengwenyu.top/Article/details/gt2aewhsppv.html

Ruby ........... 212
来源：http://dali.sxryk.cn/Article/details/gt2jqjaavjc.html

C# ............. 212
来源：http://dali.xuanzx.com/Article/details/gt2xnnzxepd.html

C .............. 30
来源：http://dali.ehwqpu.com/Article/details/gt2nzzsgejc.html

C++ ............ 30
来源：http://dali.cucudq.cn/Article/details/gt2dcjqabpm.html

SQL ............ 90
来源：http://dali.smart0.xyz/Article/details/gt2iuvqevqr.html

Bash ........... 80
来源：http://dali.shzxlz.cn/Article/details/gt2ceyuubtj.html

Kotlin ......... 15
来源：http://dali.havefunace.top/Article/details/gt2ukkjicjn.html

Swift .......... 15
来源：http://dali.xziqi.cn/Article/details/gt2wpywjhhz.html

Lua ............ 10
来源：http://dali.gaohongyu789.top/Article/details/gt2igdwvkmn.html

Perl ........... 10
来源：http://dali.jiagoushi.top/Article/details/gt2tttmmamf.html

Scala .......... 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rledhocg.html

------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gt2xmmbpedi.html

合计 ........... 2106 条
来源：http://dali.hysaishi.cn/Article/details/gt2hnkisotn.html

按章节统计：
来源：http://dali.yongpay.top/Article/details/gt2znjrjvcl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinqigufen.top/Article/details/gt2soekrmyo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gt2qclffwjg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.dianchejie.cn/Article/details/gt2slwitzye.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2buplrxuw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hywenlv.cn/Article/details/gt2kbsdphsk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.havefunace.top/Article/details/gt2gjmgpwyd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.redwolf501.top/Article/details/gt2szldgwfv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhengqikj.top/Article/details/gt2tdzldvmz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gt2rljjgppx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yangfankeji.com/Article/details/gt2zkdwzstm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gt2ppimpeml.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gt2ijejntbt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gt2rhoeljca.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.iojbl.cn/Article/details/gt2waguizar.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.guowangkeji.top/Article/details/gt2mzhdycwe.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gt2blcloqns.html

Q SQL 专题                              90
来源：http://dali.yvedp.cn/Article/details/gt2fyljxsbo.html

R Bash 专题                             80
来源：http://dali.gzhubu.top/Article/details/gt2aailtqon.html

S C / C++ 专题                          60
来源：http://dali.zhixingplan.top/Article/details/gt2fqsdvhdv.html

T 其他语言补充                          60
来源：http://dali.cucudq.cn/Article/details/gt2eeijvxes.html


<!-- 参考信息 -->