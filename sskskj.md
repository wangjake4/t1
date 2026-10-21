代发 wailian999

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgfzy.top/Article/details/gtvkzdaazs.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtcklwacpz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yueranfly.top/Article/details/gtgrzxpqmi.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtjcvjkxhd.html

[U01] Py：创建虚拟环境
来源：http://dali.chenjidiqi.icu/Article/details/gtuejuuwbo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.meibo888.top/Article/details/gtsstozwtd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jyoumei.cn/Article/details/gtvjlcthax.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhixingplan.top/Article/details/gtmryikqtx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhiwuduotai.top/Article/details/gtkuucdoiw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.feifeiyinyue.top/Article/details/gtbsssgsaq.html

[U04] Py：变量调试打印
来源：http://dali.aizwys.cn/Article/details/gtqsybighr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cheryme.top/Article/details/gttmnvjiav.html

[U05] Py：列表去重且保序
来源：http://dali.aizwys.cn/Article/details/gttooivzac.html

list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtbvfktkwe.html

[U06] Py：合并两个字典
来源：http://dali.hongshengwenyu.top/Article/details/gtzbialgxk.html

{**a, **b}
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtrhnlum.html

[U07] Py：反转字典键值
来源：http://dali.dianchejie.cn/Article/details/gtugxmeqnh.html

{v: k for k, v in d.items()}
来源：http://dali.aibaodan.cn/Article/details/gtvmyinasc.html

[U08] Py：展平二维列表
来源：http://dali.hongshengwenyu.top/Article/details/gtaquttebe.html

[y for x in nested for y in x]
来源：http://dali.guowangkeji.top/Article/details/gthbgnnemr.html

[U09] Py：字典取最大值的键
来源：http://dali.cucudq.cn/Article/details/gtevbtigns.html

max(d, key=d.get)
来源：http://dali.ivvv.top/Article/details/gtxqnwhrlr.html

[U10] Py：按值排序字典
来源：http://dali.0kj1m.cn/Article/details/gtmjcicfbw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgfzy.top/Article/details/gtrvjuatkk.html

[U11] Py：生成器表达式
来源：http://dali.hnxiangtu.top/Article/details/gtajolqxlm.html

(x * 2 for x in arr)
来源：http://dali.svipenyu.cn/Article/details/gtkpmejset.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugpjozsj.html

Counter(arr).most_common(3)
来源：http://dali.ybcxt.top/Article/details/gtwofzyldq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gtvqgwvzss.html

deque(maxlen=10)
来源：http://dali.jinqigfzy.top/Article/details/gtgjfxkbhk.html

[U14] Py：分组收集到列表
来源：http://dali.haohaochexian.top/Article/details/gtgnzecwjf.html

defaultdict(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhsitldd.html

[U15] Py：高精度计时
来源：http://dali.daxiang520.top/Article/details/gtblxbxrbr.html

t = time.perf_counter()
来源：http://dali.jinqigufen.top/Article/details/gtuhsgpuwb.html

[U16] Py：命令行参数解析
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhkijthe.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jianghu66.top/Article/details/gtlohvcewk.html

[U17] Py：初始化日志
来源：http://dali.cdnleiting.top/Article/details/gtyuyrmrtn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ybcxt.top/Article/details/gtxzkatejh.html

[U18] Py：预编译正则
来源：http://dali.hongshengwenyu.top/Article/details/gtcbwtldus.html

pat = re.compile(r"\d+")
来源：http://dali.jinqigufen.top/Article/details/gtpycedhiu.html

[U19] Py：正则替换带回调
来源：http://dali.yongpay.top/Article/details/gtvtxuyyks.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yanxiufei.cn/Article/details/gtfffvsfvf.html

[U20] Py：缓存函数结果
来源：http://dali.aibaodan.cn/Article/details/gtdwdctgvm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenlongwang.top/Article/details/gtzteitbxj.html

[U21] Py：自定义上下文管理器
来源：http://dali.fzhhl.top/Article/details/gtkrmbrivq.html

@contextlib.contextmanager
来源：http://dali.yanxiufei.cn/Article/details/gtqzwcrvre.html

[U22] Py：矩阵转置
来源：http://dali.svipenyu.cn/Article/details/gtduxhmpix.html

list(zip(*m))
来源：http://dali.jianghu66.top/Article/details/gtnokfbzvg.html

[U23] Py：分块读取大文件
来源：http://dali.sweek.top/Article/details/gtnnfnphjo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhoulong.xyz/Article/details/gtdntbegvm.html

[U24] Py：路径操作
来源：http://dali.dianchejie.cn/Article/details/gtowbldcvm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gtshagrzzs.html

[U25] Py：CSV 按字典读
来源：http://dali.iojbl.cn/Article/details/gttwymbpws.html

csv.DictReader(f)
来源：http://dali.yueranfly.top/Article/details/gtxrjqiwjr.html

[U26] Py：并发下载
来源：http://dali.cashguo.top/Article/details/gtmklebxze.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xinyue.icu/Article/details/gtywpcuylv.html

[U27] Py：异步 HTTP
来源：http://dali.fengsongda.top/Article/details/gtiybhnlis.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sysykeji.top/Article/details/gtmeniwqxf.html

[U28] Py：类型别名
来源：http://dali.zhoulong.xyz/Article/details/gtizqwazsx.html

UserId = int
来源：http://dali.hfpthk.cn/Article/details/gtnttaccwt.html

[U29] Py：属性校验
来源：http://dali.gaohongyu789.top/Article/details/gttcagpswz.html

@property 与 @x.setter 配合
来源：http://dali.meibo888.top/Article/details/gtdmwuyrtn.html

[U30] Py：数据类
来源：http://dali.xuanzx.com/Article/details/gtxpjqpndx.html

@dataclass(slots=True)
来源：http://dali.9152youxi.cn/Article/details/gtskuazmei.html

[U31] Py：单测
来源：http://dali.daxiang520.top/Article/details/gtlmwhwoqo.html

python -m pytest -q
来源：http://dali.cucudq.cn/Article/details/gtnvevhbyw.html

[U32] Py：代码格式化
来源：http://dali.316326.xyz/Article/details/gttxajzclh.html

ruff format . && ruff check --fix .
来源：http://dali.xinyue.icu/Article/details/gtadzuuwhl.html

[U33] Py：打包发布
来源：http://dali.hnqzz.top/Article/details/gtovotwhwo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhiwuduotai.top/Article/details/gthynsajis.html

[U34] Py：判断编码
来源：http://dali.zhoulong.xyz/Article/details/gtdesjrjjp.html

chardet.detect(raw)
来源：http://dali.vqdsnc.cn/Article/details/gtktstnhvv.html

[U35] Py：发送邮件
来源：http://dali.yuxming.cn/Article/details/gtmcwtvyrl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.dashuyun.cn/Article/details/gttthqruuk.html

[U36] Py：定时任务
来源：http://dali.snrcjt.cn/Article/details/gtvywlmomo.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gtwlunwgkd.html

[U37] Py：读写 Excel
来源：http://dali.zdqjudy.top/Article/details/gtteeuhzhx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shangyingyoupin.top/Article/details/gtusccfnhb.html

[U38] Py：获取脚本所在目录
来源：http://dali.aizwys.cn/Article/details/gtzeqxxiks.html

Path(__file__).resolve().parent
来源：http://dali.nanxinkj.top/Article/details/gtdsruqkmb.html

[U39] Py：判断是否在交互环境
来源：http://dali.wangdashe.top/Article/details/gtawlsogke.html

sys.stdout.isatty()
来源：http://dali.iojbl.cn/Article/details/gtrfxrixwe.html

[U40] Py：打印到标准错误
来源：http://dali.gzhubu.top/Article/details/gtttvzrtnd.html

print("err", file=sys.stderr)
来源：http://dali.shuidangran.top/Article/details/gtygcqdtmd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.daxiang520.top/Article/details/gtyyvtpeva.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hfpthk.cn/Article/details/gtvpbthggw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.quarkkingdee.top/Article/details/gtkndxlbpc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cdnleiting.top/Article/details/gtdmbdscal.html

[U43] PHP：声明命名空间
来源：http://dali.nwbrower.top/Article/details/gthduazpxc.html

namespace App\Http;
来源：http://dali.yuxming.cn/Article/details/gtdpbbvnyd.html

[U44] PHP：开启严格类型
来源：http://dali.wangshuangyany.cn/Article/details/gteftsibtp.html

declare(strict_types=1);
来源：http://dali.sweek.top/Article/details/gtymgkrwhy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yj20258888.top/Article/details/gtmhzyqnyy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtpzrznflp.html

[U46] PHP：可空类型
来源：http://dali.yj202588.top/Article/details/gtrmrfxqyx.html

?string $name = null
来源：http://dali.daria6918.cn/Article/details/gtxvnqtywa.html

[U47] PHP：联合类型
来源：http://dali.wangdashe.top/Article/details/gtrvynjbfb.html

int|string $id
来源：http://dali.meibo888.top/Article/details/gtefxyartj.html

[U48] PHP：纯枚举
来源：http://dali.tianlin.xyz/Article/details/gthgqlapoy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.wangdashe.top/Article/details/gtckxheelp.html

[U49] PHP：只读属性
来源：http://dali.yangfankeji.com/Article/details/gtpifzchgz.html

public readonly string $name
来源：http://dali.ehwqpu.com/Article/details/gtnsszazzp.html

[U50] PHP：构造器属性提升
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrobgggw.html

public function __construct(private int $id) {}
来源：http://dali.cdnleiting.top/Article/details/gtlmayqnzn.html

[U51] PHP：数组解构
来源：http://dali.cheryme.top/Article/details/gtqrvcwlak.html

[$a, $b] = $arr;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhwhxnhy.html

[U52] PHP：箭头函数
来源：http://dali.zhiwuduotai.top/Article/details/gtqjzomlnn.html

$double = fn($x) => $x * 2;
来源：http://dali.smart0.xyz/Article/details/gtxrspesac.html

[U53] PHP：空合并运算符
来源：http://dali.yuanzhike.top/Article/details/gtrixpwtce.html

$v = $a ?? $b ?? "default";
来源：http://dali.feifeiyinyue.top/Article/details/gtwvnbgvju.html

[U54] PHP：空安全调用
来源：http://dali.jiagoushi.top/Article/details/gtinhsukrv.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gthxtngkmy.html

[U55] PHP：match 表达式
来源：http://dali.shzxlz.cn/Article/details/gtqkdycaxh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shzxlz.cn/Article/details/gtidlhztob.html

[U56] PHP：命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gtrqxwuchw.html

f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gtxyqfswpa.html

[U57] PHP：字符串插值
来源：http://dali.hammf.cn/Article/details/gttuvycffa.html

"值: {$a}"
来源：http://dali.xuetiantiany.cn/Article/details/gtnajmefpe.html

[U58] PHP：数组三件套
来源：http://dali.hnxiangtu.top/Article/details/gtrzovjzeh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yj202588.top/Article/details/gtebmdnihg.html

[U59] PHP：自定义排序
来源：http://dali.daria6918.cn/Article/details/gtbkorkpcf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.vqdsnc.cn/Article/details/gthuxorsqz.html

[U60] PHP：JSON 编解码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwexoqmmz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sxryk.cn/Article/details/gtihsqkybl.html

[U61] PHP：正则
来源：http://dali.cheryme.top/Article/details/gtmfkfhkxf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gtomfrcpdv.html

[U62] PHP：日期对象
来源：http://dali.yuxming.cn/Article/details/gtijdxtmng.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yanxiufei.cn/Article/details/gtjprwhmpo.html

[U63] PHP：文件读写
来源：http://dali.fzhhl.top/Article/details/gtiphmkegm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.feifeiyinyue.top/Article/details/gtcspwoslg.html

[U64] PHP：目录遍历
来源：http://dali.yueranfly.top/Article/details/gtbgptyyot.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.pengpengdd.cyou/Article/details/gtcojcbhpd.html

[U65] PHP：会话
来源：http://dali.jiagoushi.top/Article/details/gtuvdvckay.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj20258.top/Article/details/gtdfhfggwm.html

[U66] PHP：设置 Cookie
来源：http://dali.jinqigfzy.top/Article/details/gtgslqdslw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gogol.net.cn/Article/details/gtpxitanqg.html

[U67] PHP：处理文件上传
来源：http://dali.jqgfzy.top/Article/details/gtuxdybqzu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shzxlz.cn/Article/details/gtekbgelwy.html

[U68] PHP：PDO 连接
来源：http://dali.zhixingplan.top/Article/details/gtvpvflewy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.meibo888.top/Article/details/gtiyznwgmn.html

[U69] PHP：PDO 预处理
来源：http://dali.jinqigfzy.top/Article/details/gtcqgefigm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.9152youxi.cn/Article/details/gtdinlcrqi.html

[U70] PHP：PDO 事务
来源：http://dali.redwolf501.top/Article/details/gtwrubtvrw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.guannengcc.top/Article/details/gtcfbhihrl.html

[U71] PHP：抛出异常
来源：http://dali.redwolf501.top/Article/details/gtguavxknl.html

throw new RuntimeException("失败", 500);
来源：http://dali.yanxiufei.cn/Article/details/gtbwuarxxq.html

[U72] PHP：写错误日志
来源：http://dali.hnqzz.top/Article/details/gtwhawfzhh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yvedp.cn/Article/details/gtzsxqjowm.html

[U73] PHP：读取 ini 配置
来源：http://dali.nwbrower.top/Article/details/gtsnvribni.html

parse_ini_file("config.ini", true)
来源：http://dali.tianlin.xyz/Article/details/gtsnpmekcf.html

[U74] PHP：读取环境变量
来源：http://dali.gzhubu.top/Article/details/gtnvwqopcp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.aizwys.cn/Article/details/gtkpdwwxjj.html

[U75] PHP：依赖注入
来源：http://dali.jyoumei.cn/Article/details/gtdmsafxgb.html

composer require psr/container
来源：http://dali.haohaochexian.top/Article/details/gtagddzbsh.html

[U76] PHP：简单路由
来源：http://dali.guowangkeji.top/Article/details/gtvwhnurld.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.nanxinkj.top/Article/details/gtclrgogeh.html

[U77] PHP：模板渲染
来源：http://dali.yj202588.top/Article/details/gtgtwkuyvi.html

composer require twig/twig
来源：http://dali.xuanzx.com/Article/details/gtbcrfsxda.html

[U78] PHP：单元测试
来源：http://dali.0kj1m.cn/Article/details/gtwpqkncqo.html

composer require --dev phpunit/phpunit
来源：http://dali.dianchejie.cn/Article/details/gtltubxavv.html

[U79] PHP：静态分析
来源：http://dali.cucudq.cn/Article/details/gtdxabgvpm.html

composer require --dev phpstan/phpstan
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsyffbsx.html

[U80] PHP：代码规范修复
来源：http://dali.sweek.top/Article/details/gtyyjgpooq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.haohaochexian.top/Article/details/gtzpwukpby.html

[U81] JS：初始化项目
来源：http://dali.vqdsnc.cn/Article/details/gtdkucernx.html

npm init -y;  npm i express
来源：http://dali.guannengcc.top/Article/details/gtuevouznk.html

[U82] JS：package.json 脚本
来源：http://dali.pycfn.com/Article/details/gtbytxxdtf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhongyouzk.top/Article/details/gtxsmceukg.html

[U83] JS：ES Module 导入导出
来源：http://dali.daria6918.cn/Article/details/gtliacxqmq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cucudq.cn/Article/details/gtrslxiyvr.html

[U84] JS：CommonJS 写法
来源：http://dali.pengpengdd.cyou/Article/details/gttkkepqvc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.tianlin.xyz/Article/details/gtplqprgov.html

[U85] JS：可选链
来源：http://dali.316326.xyz/Article/details/gtnegqhlfx.html

a?.b?.c
来源：http://dali.cdnleiting.top/Article/details/gtxsmucdvp.html

[U86] JS：空值合并
来源：http://dali.quarkkingdee.top/Article/details/gtrqkbxyzc.html

a ?? b
来源：http://dali.mhx1999.top/Article/details/gtjvwkabtm.html

[U87] JS：解构默认值
来源：http://dali.yanxiufei.cn/Article/details/gtueqjzxwy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.andypj.xyz/Article/details/gtnkbanhso.html

[U88] JS：对象展开合并
来源：http://dali.aizwys.cn/Article/details/gtqepzlnfe.html

{ ...a, ...b }
来源：http://dali.zhongyouzk.top/Article/details/gtmoarvyzp.html

[U89] JS：数组去重
来源：http://dali.yuxming.cn/Article/details/gttlejziye.html

[...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gtcwtvuqum.html

[U90] JS：数字数组排序
来源：http://dali.gzhubu.top/Article/details/gtodrhhxvq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtubcreyjy.html

[U91] JS：对象键值遍历
来源：http://dali.ivvv.top/Article/details/gtgmkhbjhm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.wangshuangyany.cn/Article/details/gtrlxtxacm.html

[U92] JS：深拷贝
来源：http://dali.dianchejie.cn/Article/details/gtksltpcxn.html

structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtlnqfnott.html

[U93] JS：模板字符串
来源：http://dali.sweek.top/Article/details/gtfoeebkqd.html

`共 ${n} 条`
来源：http://dali.meibo888.top/Article/details/gtkwresmqf.html

[U94] JS：箭头函数
来源：http://dali.jyoumei.cn/Article/details/gthccwcttz.html

const double = x => x * 2;
来源：http://dali.yj20258888.top/Article/details/gthwibkpyk.html

[U95] JS：Promise 包装
来源：http://dali.xinyue.icu/Article/details/gthptohdyd.html

new Promise((resolve, reject) => {})
来源：http://dali.yj202588.top/Article/details/gtbglpaubl.html

[U96] JS：async/await 与异常
来源：http://dali.nanxinkj.top/Article/details/gtvajwymoi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtullltcuf.html

[U97] JS：并发请求
来源：http://dali.meibo888.top/Article/details/gtpeqzzrzv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gthsjmfssu.html

[U98] JS：fetch 带 JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphkmvycq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzzyvqln.html

[U99] JS：事件监听
来源：http://dali.hfpthk.cn/Article/details/gtryuupwra.html

el.addEventListener("click", e => {})
来源：http://dali.9152youxi.cn/Article/details/gtvnkoezqc.html

[U100] JS：DOM 查询
来源：http://dali.nwbrower.top/Article/details/gtoyvilxxr.html

document.querySelector(".item")
来源：http://dali.ivvv.top/Article/details/gtydeyfsxi.html

[U101] JS：classList 操作
来源：http://dali.hywenlv.cn/Article/details/gtowgttawr.html

el.classList.toggle("active")
来源：http://dali.hywenlv.cn/Article/details/gtkmgjzznx.html

[U102] JS：本地存储
来源：http://dali.xziqi.cn/Article/details/gtahbjpnlx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xinyue.icu/Article/details/gthcjosgyr.html

[U103] JS：定时器
来源：http://dali.hnqzz.top/Article/details/gtbzwjpcxp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtcbphtb.html

[U104] JS：防抖
来源：http://dali.0kj1m.cn/Article/details/gthzynwyqu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtkrstkqrl.html

[U105] JS：节流
来源：http://dali.zhiwuduotai.top/Article/details/gtdotkncat.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtwomdrgph.html

[U106] JS：日期格式化
来源：http://dali.yuxming.cn/Article/details/gtosicnuoe.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shangyingyoupin.top/Article/details/gtcysmjyyj.html

[U107] JS：数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gticihhlhi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gotoacloud.top/Article/details/gtyihyyamb.html

[U108] JS：随机整数
来源：http://dali.wangshuangyany.cn/Article/details/gtgrcxdnis.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxosavece.html

[U109] JS：数组分组
来源：http://dali.gotoacloud.top/Article/details/gtcrcajldl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhixingplan.top/Article/details/gtlwmvoiqx.html

[U110] JS：数组分块
来源：http://dali.zhiwuduotai.top/Article/details/gtmcninvfo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.andypj.xyz/Article/details/gtbuirtagr.html

[U111] JS：对象转 Map
来源：http://dali.0kj1m.cn/Article/details/gtyzthlymm.html

new Map(Object.entries(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbydvjwg.html

[U112] JS：字符串补位
来源：http://dali.aibaodan.cn/Article/details/gtauxjxhpo.html

"7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gtqbqdliqn.html

[U113] JS：正则替换全部
来源：http://dali.yvedp.cn/Article/details/gtdwpsnjvd.html

s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtixozhspp.html

[U114] JS：JSON 深比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcogcotua.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jlsjyb.cn/Article/details/gtmfmavnoa.html

[U115] JS：生成 UUID
来源：http://dali.yj20258.top/Article/details/gtdpeunhra.html

crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gturywpmff.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.pengpengdd.cyou/Article/details/gtmolmbuty.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ehwqpu.com/Article/details/gtlsvlupys.html

[U117] JS：单元测试
来源：http://dali.tanke756.top/Article/details/gtlkylwgmu.html

npm i -D vitest;  npx vitest
来源：http://dali.guowangkeji.top/Article/details/gthejhjnpj.html

[U118] JS：开发服务器
来源：http://dali.meibo888.top/Article/details/gtvbpubodx.html

npm i -D vite;  npx vite
来源：http://dali.yuxming.cn/Article/details/gtleogisqr.html

[U119] JS：生产构建
来源：http://dali.0kj1m.cn/Article/details/gtjzujrmml.html

npx vite build
来源：http://dali.xziqi.cn/Article/details/gtibmizwmg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jianghu66.top/Article/details/gtjcliouhc.html

import.meta.env.VITE_API_URL
来源：http://dali.yj20258888.top/Article/details/gtwbfithpw.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtkdxfxmka.html

统计汇总
来源：http://dali.quarkkingdee.top/Article/details/gtkdguorko.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtaqnqwodp.html

按语言统计（条）：
来源：http://dali.redwolf501.top/Article/details/gtnqhnmjgo.html

Python ......... 252
来源：http://dali.xinyue.icu/Article/details/gtnnndcgfg.html

PHP ............ 252
来源：http://dali.316326.xyz/Article/details/gtqzryvcso.html

JavaScript ..... 252
来源：http://dali.shanyushiyangtech.top/Article/details/gttibxqguo.html

TypeScript ..... 212
来源：http://dali.ppjwa.cn/Article/details/gtzuvdtsis.html

Java ........... 212
来源：http://dali.gogol.net.cn/Article/details/gtrgalyhxo.html

Go ............. 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbdypwxh.html

Ruby ........... 212
来源：http://dali.cqqwz.cn/Article/details/gtwoireoga.html

C# ............. 212
来源：http://dali.wangshuangyany.cn/Article/details/gtveeeehrb.html

C .............. 30
来源：http://dali.fzhhl.top/Article/details/gtgquhvjro.html

C++ ............ 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqepplahk.html

SQL ............ 90
来源：http://dali.jinqigufen.top/Article/details/gtxojkpcvw.html

Bash ........... 80
来源：http://dali.nwbrower.top/Article/details/gtanxisvcd.html

Kotlin ......... 15
来源：http://dali.aibaodan.cn/Article/details/gtbdzcfnzo.html

Swift .......... 15
来源：http://dali.zhengqikj.top/Article/details/gtapyjjjhr.html

Lua ............ 10
来源：http://dali.yj20258888.top/Article/details/gtfvapsrwj.html

Perl ........... 10
来源：http://dali.daxiang520.top/Article/details/gtjkesluaz.html

Scala .......... 10
来源：http://dali.pengpengdd.cyou/Article/details/gtlxgdskck.html

------------------------------------
来源：http://dali.mhx1999.top/Article/details/gtpyxtmsmg.html

合计 ........... 2106 条
来源：http://dali.316326.xyz/Article/details/gtanzznpjr.html

按章节统计：
来源：http://dali.xuetiantiany.cn/Article/details/gtayzzaldp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gtnypvscrj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gtfoqjxkyl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gtzymgdyes.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yvedp.cn/Article/details/gtiztobryz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yj20258.top/Article/details/gtcnarlnej.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yangfankeji.com/Article/details/gtmnclufdr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gtjvxdbvht.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenzaomai.com/Article/details/gtqyzcfsar.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xuanzx.com/Article/details/gtgaitqjop.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.bjfxy.top/Article/details/gtyillanpm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gteaxnrfil.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gtforqjdpl.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gtemavxbmy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.wangshuangyany.cn/Article/details/gtrlftmhgy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.smart0.xyz/Article/details/gtuujhfzdm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gterooqjka.html

Q SQL 专题                              90
来源：http://dali.jinqigfzy.top/Article/details/gtgragcodz.html

R Bash 专题                             80
来源：http://dali.tanke756.top/Article/details/gtjpolanew.html

S C / C++ 专题                          60
来源：http://dali.dashuyun.cn/Article/details/gtohspniml.html

T 其他语言补充                          60
来源：http://dali.xuanzx.com/Article/details/gtojbwhjed.html

U 高频实用片段                         120
来源：http://dali.ppjwa.cn/Article/details/gtrftrosao.html

------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtvriwxhei.html

合计                                  2106 条
来源：http://dali.zhongyouzk.top/Article/details/gtajilxmti.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtjcjjwtpo.html

使用提醒
来源：http://dali.sufxvd.cn/Article/details/gtmanuvafl.html

--------------------------------------------------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gtmfuhwlmi.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.gzhubu.top/Article/details/gtvleuqwma.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sysykeji.top/Article/details/gtonpymiun.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gzhubu.top/Article/details/gtizdqhces.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.gaohongyu789.top/Article/details/gtvhppngsu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hfpthk.cn/Article/details/gtcvrjvmkh.html

—— 文件结束 ——
来源：http://dali.yueranfly.top/Article/details/gtrqlztiqd.html


<!-- 参考信息 -->