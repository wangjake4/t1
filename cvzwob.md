代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rixuixub.html

[T59] Scala：循环
来源：http://dali.jyoumei.cn/Article/details/gt2djlanvbh.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kohgtgcz.html

[T60] Scala：折叠
来源：http://dali.hnqzz.top/Article/details/gt2nbchofcq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izmgctxa.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2zcuolrea.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigufen.top/Article/details/gt2olxnzcqm.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2tedioglt.html

[U01] Py：创建虚拟环境
来源：http://dali.chenlongwang.top/Article/details/gt2bgstgmcw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kvdcozbg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yvedp.cn/Article/details/gt2ajhydbng.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xylfe.cn/Article/details/gt2obhltoxk.html

[U03] Py：加载 .env 配置
来源：http://dali.tian-w.cn/Article/details/gt2vhvrzoox.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gzhubu.top/Article/details/gt2jbweskxs.html

[U04] Py：变量调试打印
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oqlnfyfa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.svipenyu.cn/Article/details/gt2qbwruahp.html

[U05] Py：列表去重且保序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxuqsrqx.html

list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gt2uozegryb.html

[U06] Py：合并两个字典
来源：http://dali.jlsjyb.cn/Article/details/gt2awnkisom.html

{**a, **b}
来源：http://dali.cqqwz.cn/Article/details/gt2kaavioco.html

[U07] Py：反转字典键值
来源：http://dali.xylfe.cn/Article/details/gt2zmdqeizq.html

{v: k for k, v in d.items()}
来源：http://dali.daria6918.cn/Article/details/gt2hbbgrrmi.html

[U08] Py：展平二维列表
来源：http://dali.9152youxi.cn/Article/details/gt2blisphyx.html

[y for x in nested for y in x]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbgrsdej.html

[U09] Py：字典取最大值的键
来源：http://dali.zdqjudy.top/Article/details/gt2vpqwrhrz.html

max(d, key=d.get)
来源：http://dali.meibo888.top/Article/details/gt2csthdtwp.html

[U10] Py：按值排序字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mpjuhtbj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tanke756.top/Article/details/gt2xvtccpix.html

[U11] Py：生成器表达式
来源：http://dali.zhoulong.xyz/Article/details/gt2excedoar.html

(x * 2 for x in arr)
来源：http://dali.hywenlv.cn/Article/details/gt2ytphrejx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ybcxt.top/Article/details/gt2hqhhqlck.html

Counter(arr).most_common(3)
来源：http://dali.tianlin.xyz/Article/details/gt2bqntgeej.html

[U13] Py：固定长度队列
来源：http://dali.nanxinkj.top/Article/details/gt2bqycinzc.html

deque(maxlen=10)
来源：http://dali.zdqjudy.top/Article/details/gt2saczvqhf.html

[U14] Py：分组收集到列表
来源：http://dali.mhx1999.top/Article/details/gt2yhfaqyrr.html

defaultdict(list)
来源：http://dali.hnxiangtu.top/Article/details/gt2zyfzzign.html

[U15] Py：高精度计时
来源：http://dali.xuetiantiany.cn/Article/details/gt2oatmdcbi.html

t = time.perf_counter()
来源：http://dali.cdnleiting.top/Article/details/gt2sybztzlu.html

[U16] Py：命令行参数解析
来源：http://dali.yonumen.top/Article/details/gt2emcsfqot.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.svipenyu.cn/Article/details/gt2kopgalgr.html

[U17] Py：初始化日志
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqjorauk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bqrcuwyf.html

[U18] Py：预编译正则
来源：http://dali.xinyue.icu/Article/details/gt2ctjtnjyw.html

pat = re.compile(r"\d+")
来源：http://dali.dashuyun.cn/Article/details/gt2fekcsspl.html

[U19] Py：正则替换带回调
来源：http://dali.jqgufenzy.top/Article/details/gt2fqfaecvo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ggjzangm.html

[U20] Py：缓存函数结果
来源：http://dali.jinqigfzy.top/Article/details/gt2ogdqhkbz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jyoumei.cn/Article/details/gt2vuztokda.html

[U21] Py：自定义上下文管理器
来源：http://dali.kuanghao11.cn/Article/details/gt2nilvjjgt.html

@contextlib.contextmanager
来源：http://dali.vqdsnc.cn/Article/details/gt2jlcbuavo.html

[U22] Py：矩阵转置
来源：http://dali.yanxiufei.cn/Article/details/gt2hvabscnm.html

list(zip(*m))
来源：http://dali.gogol.net.cn/Article/details/gt2avrnilrq.html

[U23] Py：分块读取大文件
来源：http://dali.vqdsnc.cn/Article/details/gt2fazwddaj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhongyouzk.top/Article/details/gt2lpuzjusi.html

[U24] Py：路径操作
来源：http://dali.xuanzx.com/Article/details/gt2zzqrpbqu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gt2pacriocu.html

[U25] Py：CSV 按字典读
来源：http://dali.zhoulong.xyz/Article/details/gt2hthscquf.html

csv.DictReader(f)
来源：http://dali.guowangkeji.top/Article/details/gt2appezfwz.html

[U26] Py：并发下载
来源：http://dali.aizwys.cn/Article/details/gt2sjojupjh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.fzhhl.top/Article/details/gt2vvthanxc.html

[U27] Py：异步 HTTP
来源：http://dali.pengpengdd.cyou/Article/details/gt2ltkvwzmu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.c1oappe.top/Article/details/gt2osnagskb.html

[U28] Py：类型别名
来源：http://dali.hnxiangtu.top/Article/details/gt2rgjrtgrm.html

UserId = int
来源：http://dali.aibaodan.cn/Article/details/gt2yrnipajj.html

[U29] Py：属性校验
来源：http://dali.shuidangran.top/Article/details/gt2mgptyeqj.html

@property 与 @x.setter 配合
来源：http://dali.316326.xyz/Article/details/gt2ymsielmr.html

[U30] Py：数据类
来源：http://dali.kuanghao11.cn/Article/details/gt2yycvrqas.html

@dataclass(slots=True)
来源：http://dali.aizwys.cn/Article/details/gt2sfdmvgot.html

[U31] Py：单测
来源：http://dali.guannengcc.top/Article/details/gt2wbquzkem.html

python -m pytest -q
来源：http://dali.zdqjudy.top/Article/details/gt2kigbmgxm.html

[U32] Py：代码格式化
来源：http://dali.c1oappe.top/Article/details/gt2nfjbyofx.html

ruff format . && ruff check --fix .
来源：http://dali.redwolf501.top/Article/details/gt2fdchtfvk.html

[U33] Py：打包发布
来源：http://dali.hongshengwenyu.top/Article/details/gt2fqhibhoq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hnqzz.top/Article/details/gt2pvjqalqp.html

[U34] Py：判断编码
来源：http://dali.hongshengwenyu.top/Article/details/gt2oaofjupk.html

chardet.detect(raw)
来源：http://dali.aizwys.cn/Article/details/gt2cjfqqiql.html

[U35] Py：发送邮件
来源：http://dali.haohaochexian.top/Article/details/gt2xopoeazn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jqgufenzy.top/Article/details/gt2dwpbmesx.html

[U36] Py：定时任务
来源：http://dali.pengpengdd.cyou/Article/details/gt2oxtevzcw.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pdwphsja.html

[U37] Py：读写 Excel
来源：http://dali.havefunace.top/Article/details/gt2wfjwzrfo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gaohongyu789.top/Article/details/gt2pigospmv.html

[U38] Py：获取脚本所在目录
来源：http://dali.shangyingyoupin.top/Article/details/gt2qxxaednj.html

Path(__file__).resolve().parent
来源：http://dali.nanxinkj.top/Article/details/gt2xqbfxduc.html

[U39] Py：判断是否在交互环境
来源：http://dali.9152youxi.cn/Article/details/gt2rrjqjlif.html

sys.stdout.isatty()
来源：http://dali.shangyingyoupin.top/Article/details/gt2urhkuhtb.html

[U40] Py：打印到标准错误
来源：http://dali.feifeiyinyue.top/Article/details/gt2gljktjoa.html

print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gt2vjvrrbhx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.aizwys.cn/Article/details/gt2rqhibdjw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jiagoushi.top/Article/details/gt2weolpdgk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sweek.top/Article/details/gt2dgziqpmu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zvdmdteh.html

[U43] PHP：声明命名空间
来源：http://dali.jqgfzy.top/Article/details/gt2tibzaufg.html

namespace App\Http;
来源：http://dali.jiagoushi.top/Article/details/gt2uztoodbf.html

[U44] PHP：开启严格类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2giquukds.html

declare(strict_types=1);
来源：http://dali.fzhhl.top/Article/details/gt2hwobisjz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yj202588.top/Article/details/gt2czvfkfsj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gt2claekspd.html

[U46] PHP：可空类型
来源：http://dali.haohaochexian.top/Article/details/gt2mywfcbog.html

?string $name = null
来源：http://dali.tianlin.xyz/Article/details/gt2lvzuiwmn.html

[U47] PHP：联合类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2oroesyoj.html

int|string $id
来源：http://dali.hywenlv.cn/Article/details/gt2clxmdxxk.html

[U48] PHP：纯枚举
来源：http://dali.chenlongwang.top/Article/details/gt2wnjcazhk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yj20258.top/Article/details/gt2lmjgdchp.html

[U49] PHP：只读属性
来源：http://dali.hfpthk.cn/Article/details/gt2qpuxscdu.html

public readonly string $name
来源：http://dali.yangfankeji.com/Article/details/gt2ozmhajyi.html

[U50] PHP：构造器属性提升
来源：http://dali.xuanzx.com/Article/details/gt2sjsgstvc.html

public function __construct(private int $id) {}
来源：http://dali.snrcjt.cn/Article/details/gt2hlghlgnh.html

[U51] PHP：数组解构
来源：http://dali.jqgfzy.top/Article/details/gt2mpcgteuy.html

[$a, $b] = $arr;
来源：http://dali.yj202588.top/Article/details/gt2wzywswto.html

[U52] PHP：箭头函数
来源：http://dali.andypj.xyz/Article/details/gt2fsahhqyk.html

$double = fn($x) => $x * 2;
来源：http://dali.daxiang520.top/Article/details/gt2gffhhixp.html

[U53] PHP：空合并运算符
来源：http://dali.zhoulong.xyz/Article/details/gt2odtxazeu.html

$v = $a ?? $b ?? "default";
来源：http://dali.birdmap.top/Article/details/gt2drpyfdjy.html

[U54] PHP：空安全调用
来源：http://dali.pengpengdd.cyou/Article/details/gt2qxytsfto.html

$obj?->method()
来源：http://dali.fengsongda.top/Article/details/gt2iuacqhvu.html

[U55] PHP：match 表达式
来源：http://dali.jinqigufen.top/Article/details/gt2kejgixke.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.quarkkingdee.top/Article/details/gt2gpzzgxyj.html

[U56] PHP：命名参数
来源：http://dali.jqgufenzy.top/Article/details/gt2xchpcvxt.html

f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gt2tmyiruwd.html

[U57] PHP：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gt2hnzrydgr.html

"值: {$a}"
来源：http://dali.cqqwz.cn/Article/details/gt2lyvcaszr.html

[U58] PHP：数组三件套
来源：http://dali.zhixingplan.top/Article/details/gt2ydzgdydr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yueranfly.top/Article/details/gt2asyccfyd.html

[U59] PHP：自定义排序
来源：http://dali.zhoulong.xyz/Article/details/gt2cqqyulaa.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gt2lnbczsxl.html

[U60] PHP：JSON 编解码
来源：http://dali.sufxvd.cn/Article/details/gt2cntpyxuj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhengqikj.top/Article/details/gt2zxhzyjao.html

[U61] PHP：正则
来源：http://dali.9152youxi.cn/Article/details/gt2mclfeykl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2zovukqcd.html

[U62] PHP：日期对象
来源：http://dali.quarkkingdee.top/Article/details/gt2dhbydbxi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gotoacloud.top/Article/details/gt2siotsbhn.html

[U63] PHP：文件读写
来源：http://dali.sxryk.cn/Article/details/gt2qdmyglmd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gogol.net.cn/Article/details/gt2yftvyppj.html

[U64] PHP：目录遍历
来源：http://dali.aibaodan.cn/Article/details/gt2puglwapl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nwbrower.top/Article/details/gt2orzwnlxy.html

[U65] PHP：会话
来源：http://dali.guowangkeji.top/Article/details/gt2vqpbyand.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2hdsnvwsl.html

[U66] PHP：设置 Cookie
来源：http://dali.nanxuanxn.top/Article/details/gt2uzjolyvi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2phoiosyv.html

[U67] PHP：处理文件上传
来源：http://dali.quarkkingdee.top/Article/details/gt2awikmzoo.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yj20258.top/Article/details/gt2vsrmriwj.html

[U68] PHP：PDO 连接
来源：http://dali.ydzc1.top/Article/details/gt2hshnrfmf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.feifeiyinyue.top/Article/details/gt2aawbdibi.html

[U69] PHP：PDO 预处理
来源：http://dali.yanxiufei.cn/Article/details/gt2vtvugfjs.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.meibo888.top/Article/details/gt2ttudprwd.html

[U70] PHP：PDO 事务
来源：http://dali.jianghu66.top/Article/details/gt2zhifylop.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xuetiantiany.cn/Article/details/gt2toilsvei.html

[U71] PHP：抛出异常
来源：http://dali.gogol.net.cn/Article/details/gt2spwlltzf.html

throw new RuntimeException("失败", 500);
来源：http://dali.gzhubu.top/Article/details/gt2mjhfclhm.html

[U72] PHP：写错误日志
来源：http://dali.hammf.cn/Article/details/gt2uclugdeb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cqqwz.cn/Article/details/gt2pddvyicy.html

[U73] PHP：读取 ini 配置
来源：http://dali.wangshuangyany.cn/Article/details/gt2pmzwulct.html

parse_ini_file("config.ini", true)
来源：http://dali.aibaodan.cn/Article/details/gt2bfhkobhd.html

[U74] PHP：读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lrjdsrho.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhengqikj.top/Article/details/gt2kwpwhoyq.html

[U75] PHP：依赖注入
来源：http://dali.cheryme.top/Article/details/gt2kfbfkaho.html

composer require psr/container
来源：http://dali.gaohongyu789.top/Article/details/gt2rzhfofdf.html

[U76] PHP：简单路由
来源：http://dali.yangfankeji.com/Article/details/gt2yjtnkkjg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.quarkkingdee.top/Article/details/gt2cppwcjkf.html

[U77] PHP：模板渲染
来源：http://dali.hywenlv.cn/Article/details/gt2tqhedrfa.html

composer require twig/twig
来源：http://dali.feifeiyinyue.top/Article/details/gt2kouxzpys.html

[U78] PHP：单元测试
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2svfmkydx.html

composer require --dev phpunit/phpunit
来源：http://dali.gaohongyu789.top/Article/details/gt2zrkutagt.html

[U79] PHP：静态分析
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oskmjgvf.html

composer require --dev phpstan/phpstan
来源：http://dali.gotoacloud.top/Article/details/gt2qyefnmzo.html

[U80] PHP：代码规范修复
来源：http://dali.andypj.xyz/Article/details/gt2rynonmlq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xylfe.cn/Article/details/gt2ergqylgp.html

[U81] JS：初始化项目
来源：http://dali.meibo888.top/Article/details/gt2winriohh.html

npm init -y;  npm i express
来源：http://dali.jqgufenzy.top/Article/details/gt2xjsqcjkr.html

[U82] JS：package.json 脚本
来源：http://dali.9152youxi.cn/Article/details/gt2aczgfwke.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.dianchejie.cn/Article/details/gt2pedxqdwl.html

[U83] JS：ES Module 导入导出
来源：http://dali.chenjidiqi.icu/Article/details/gt2xlcupujc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.dashuyun.cn/Article/details/gt2wdakobfl.html

[U84] JS：CommonJS 写法
来源：http://dali.c1oappe.top/Article/details/gt2uzaubkfp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ppjwa.cn/Article/details/gt2fafchzpb.html

[U85] JS：可选链
来源：http://dali.aizwys.cn/Article/details/gt2ttyazwrc.html

a?.b?.c
来源：http://dali.vqdsnc.cn/Article/details/gt2csexukik.html

[U86] JS：空值合并
来源：http://dali.snrcjt.cn/Article/details/gt2rmpbbnmj.html

a ?? b
来源：http://dali.shuidangran.top/Article/details/gt2btugfjrl.html

[U87] JS：解构默认值
来源：http://dali.zhiwuduotai.top/Article/details/gt2huxmrsmy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.tanke756.top/Article/details/gt2socxxuat.html

[U88] JS：对象展开合并
来源：http://dali.snrcjt.cn/Article/details/gt2gnwaxqqf.html

{ ...a, ...b }
来源：http://dali.gzhubu.top/Article/details/gt2iaxfrfnx.html

[U89] JS：数组去重
来源：http://dali.chenzaomai.com/Article/details/gt2wmelakhs.html

[...new Set(arr)]
来源：http://dali.daria6918.cn/Article/details/gt2nbwundyi.html

[U90] JS：数字数组排序
来源：http://dali.9152youxi.cn/Article/details/gt2bpctnnop.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gt2gomhshix.html

[U91] JS：对象键值遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fjrrqtdx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.316326.xyz/Article/details/gt2oiklrepv.html

[U92] JS：深拷贝
来源：http://dali.jyoumei.cn/Article/details/gt2pjulacft.html

structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gt2mljteach.html

[U93] JS：模板字符串
来源：http://dali.c1oappe.top/Article/details/gt2wynekzps.html

`共 ${n} 条`
来源：http://dali.dashuyun.cn/Article/details/gt2puvnijvz.html

[U94] JS：箭头函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2mejxwmno.html

const double = x => x * 2;
来源：http://dali.sufxvd.cn/Article/details/gt2wkuntfev.html

[U95] JS：Promise 包装
来源：http://dali.hywenlv.cn/Article/details/gt2wwwiohif.html

new Promise((resolve, reject) => {})
来源：http://dali.jinqigfzy.top/Article/details/gt2fbtwkxyi.html

[U96] JS：async/await 与异常
来源：http://dali.yj20258888.top/Article/details/gt2lxwvwnhh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gt2uwwmfegw.html

[U97] JS：并发请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nlhdqiqb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gt2soxrrwqf.html

[U98] JS：fetch 带 JSON
来源：http://dali.ivvv.top/Article/details/gt2rmswwfig.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nebyapcd.html

[U99] JS：事件监听
来源：http://dali.tianlin.xyz/Article/details/gt2kqduuuef.html

el.addEventListener("click", e => {})
来源：http://dali.yuxming.cn/Article/details/gt2fdjpnfhf.html

[U100] JS：DOM 查询
来源：http://dali.smart0.xyz/Article/details/gt2hfxhlbin.html

document.querySelector(".item")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dvsauhiz.html

[U101] JS：classList 操作
来源：http://dali.feifeiyinyue.top/Article/details/gt2rlpjxsxs.html

el.classList.toggle("active")
来源：http://dali.dianchejie.cn/Article/details/gt2ittkagej.html

[U102] JS：本地存储
来源：http://dali.pengpengdd.cyou/Article/details/gt2ytlcbmwz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.mhx1999.top/Article/details/gt2hxyurcia.html

[U103] JS：定时器
来源：http://dali.pycfn.com/Article/details/gt2hjvmulgx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yuxming.cn/Article/details/gt2tigxccmn.html

[U104] JS：防抖
来源：http://dali.redwolf501.top/Article/details/gt2dtjtjknr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2tkthwjwi.html

[U105] JS：节流
来源：http://dali.jyoumei.cn/Article/details/gt2hkplytpy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xinyue.icu/Article/details/gt2xwzginwc.html

[U106] JS：日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wuzwvyxj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinqigfzy.top/Article/details/gt2qcvwkyuu.html

[U107] JS：数字千分位
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmrgvmeo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.316326.xyz/Article/details/gt2rbtlrceu.html

[U108] JS：随机整数
来源：http://dali.chenlongwang.top/Article/details/gt2cjrelxei.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.iojbl.cn/Article/details/gt2jcutpqav.html

[U109] JS：数组分组
来源：http://dali.cqqwz.cn/Article/details/gt2qxwpfnkl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ybcxt.top/Article/details/gt2deimtjhn.html

[U110] JS：数组分块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jpcccdto.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.andypj.xyz/Article/details/gt2drutgiqa.html

[U111] JS：对象转 Map
来源：http://dali.hysaishi.cn/Article/details/gt2zottnneh.html

new Map(Object.entries(obj))
来源：http://dali.zhengqikj.top/Article/details/gt2ilgnguvh.html

[U112] JS：字符串补位
来源：http://dali.guannengcc.top/Article/details/gt2lvcnkrye.html

"7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gt2gvsjlbet.html

[U113] JS：正则替换全部
来源：http://dali.9152youxi.cn/Article/details/gt2nkjsjjhf.html

s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2vhyfipwk.html

[U114] JS：JSON 深比较
来源：http://dali.daria6918.cn/Article/details/gt2andtfnbu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuanzhike.top/Article/details/gt2wqmbfhdc.html

[U115] JS：生成 UUID
来源：http://dali.cashguo.top/Article/details/gt2tpjhnnvy.html

crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gt2lkclieyf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jyoumei.cn/Article/details/gt2tswxlvlb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj20258888.top/Article/details/gt2relzejgx.html

[U117] JS：单元测试
来源：http://dali.nwbrower.top/Article/details/gt2disnvdcd.html

npm i -D vitest;  npx vitest
来源：http://dali.svipenyu.cn/Article/details/gt2ahlmtolf.html

[U118] JS：开发服务器
来源：http://dali.wangshuangyany.cn/Article/details/gt2eqkegwiy.html

npm i -D vite;  npx vite
来源：http://dali.gaohongyu789.top/Article/details/gt2qxienufv.html

[U119] JS：生产构建
来源：http://dali.ivvv.top/Article/details/gt2bbqcliet.html

npx vite build
来源：http://dali.hysaishi.cn/Article/details/gt2fqfnyagh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cucudq.cn/Article/details/gt2chbcxgnf.html

import.meta.env.VITE_API_URL
来源：http://dali.hywenlv.cn/Article/details/gt2oiovmajw.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2gzarllym.html

统计汇总
来源：http://dali.havefunace.top/Article/details/gt2pptjgwvy.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2cykzrvad.html

按语言统计（条）：
来源：http://dali.smart0.xyz/Article/details/gt2tdzrngkt.html

Python ......... 252
来源：http://dali.pycfn.com/Article/details/gt2ehftyvtc.html

PHP ............ 252
来源：http://dali.kuanghao11.cn/Article/details/gt2skjwdwwq.html

JavaScript ..... 252
来源：http://dali.sufxvd.cn/Article/details/gt2qdysocqf.html

TypeScript ..... 212
来源：http://dali.bjfxy.top/Article/details/gt2sycozaoe.html

Java ........... 212
来源：http://dali.bjfxy.top/Article/details/gt2kxcrkokg.html

Go ............. 212
来源：http://dali.aizwys.cn/Article/details/gt2cxvqnjwg.html

Ruby ........... 212
来源：http://dali.fzhhl.top/Article/details/gt2gmeqrlno.html

C# ............. 212
来源：http://dali.gotoacloud.top/Article/details/gt2dknwucyw.html

C .............. 30
来源：http://dali.gogol.net.cn/Article/details/gt2aalghcrm.html

C++ ............ 30
来源：http://dali.jqgfzy.top/Article/details/gt2ajtkkdgy.html

SQL ............ 90
来源：http://dali.pycfn.com/Article/details/gt2ijpzsvff.html

Bash ........... 80
来源：http://dali.nanxuanxn.top/Article/details/gt2tyaieots.html

Kotlin ......... 15
来源：http://dali.aizwys.cn/Article/details/gt2hipluqtd.html

Swift .......... 15
来源：http://dali.yueranfly.top/Article/details/gt2cdzmoagh.html

Lua ............ 10
来源：http://dali.zhixingplan.top/Article/details/gt2juasxgwp.html

Perl ........... 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2abkigomr.html

Scala .......... 10
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wgdhmkzt.html

------------------------------------
来源：http://dali.sweek.top/Article/details/gt2wspmiguw.html

合计 ........... 2106 条
来源：http://dali.xylfe.cn/Article/details/gt2kvewwazw.html

按章节统计：
来源：http://dali.yuanzhike.top/Article/details/gt2sgbukmzn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gzhubu.top/Article/details/gt2imluevmg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gaohongyu789.top/Article/details/gt2lohjzyca.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.0kj1m.cn/Article/details/gt2qltzbhni.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jlsjyb.cn/Article/details/gt2xhgihctg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yuanzhike.top/Article/details/gt2ecfasojz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.wangdashe.top/Article/details/gt2xozvoqds.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gt2bhnrmqhp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gt2kqwysgzp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gt2lvmzwzwu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gt2xgpwuwwx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gt2gxtazqyk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gt2lwiwfpyq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gt2wnsiojxd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.tian-w.cn/Article/details/gt2gicsdpxz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.bjfxy.top/Article/details/gt2cxqbqcjz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gt2zorncaya.html

Q SQL 专题                              90
来源：http://dali.ppjwa.cn/Article/details/gt2fiudcbqs.html

R Bash 专题                             80
来源：http://dali.jinqigfzy.top/Article/details/gt2wjleegsv.html

S C / C++ 专题                          60
来源：http://dali.zhengqikj.top/Article/details/gt2ijybqdfx.html

T 其他语言补充                          60
来源：http://dali.gzhubu.top/Article/details/gt2xavduuct.html

U 高频实用片段                         120
来源：http://dali.quarkkingdee.top/Article/details/gt2qngpapwj.html

------------------------------------
来源：http://dali.gzhubu.top/Article/details/gt2rjicqlmm.html

合计                                  2106 条
来源：http://dali.meibo888.top/Article/details/gt2dojdmuys.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zeryanld.html

使用提醒
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xmfzkvst.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gt2gojjfsew.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2tmidqrhy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zycfv.cn/Article/details/gt2jsxdrraj.html


<!-- 参考信息 -->