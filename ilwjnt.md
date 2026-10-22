代发 wailian999

[U01] Py：创建虚拟环境
来源：http://dali.gotoacloud.top/Article/details/gt2qkfurkgn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guannengcc.top/Article/details/gt2ogvnxkby.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cheryme.top/Article/details/gt2nqtjdvvg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hfpthk.cn/Article/details/gt2okuccuzm.html

[U03] Py：加载 .env 配置
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pfetmbhl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vklnsifk.html

[U04] Py：变量调试打印
来源：http://dali.sxryk.cn/Article/details/gt2bsswjmgb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2urmrobjj.html

[U05] Py：列表去重且保序
来源：http://dali.hysaishi.cn/Article/details/gt2ghzbfzzz.html

list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2mniamqix.html

[U06] Py：合并两个字典
来源：http://dali.zhixingplan.top/Article/details/gt2mmhrddgc.html

{**a, **b}
来源：http://dali.hfpthk.cn/Article/details/gt2bbsktyij.html

[U07] Py：反转字典键值
来源：http://dali.ydzc1.top/Article/details/gt2dyvbxnjl.html

{v: k for k, v in d.items()}
来源：http://dali.dashuyun.cn/Article/details/gt2pefxoqpn.html

[U08] Py：展平二维列表
来源：http://dali.havefunace.top/Article/details/gt2zmdxpcre.html

[y for x in nested for y in x]
来源：http://dali.daria6918.cn/Article/details/gt2vjmallev.html

[U09] Py：字典取最大值的键
来源：http://dali.chenzaomai.com/Article/details/gt2kystvjtn.html

max(d, key=d.get)
来源：http://dali.xuanzx.com/Article/details/gt2tppjubje.html

[U10] Py：按值排序字典
来源：http://dali.chenjidiqi.icu/Article/details/gt2wzhpqcqe.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.dashuyun.cn/Article/details/gt2igoelcnt.html

[U11] Py：生成器表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fcbwbmlx.html

(x * 2 for x in arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pvlpochl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2zenseiis.html

Counter(arr).most_common(3)
来源：http://dali.aibaodan.cn/Article/details/gt2tfzevpjw.html

[U13] Py：固定长度队列
来源：http://dali.cashguo.top/Article/details/gt2moqicbqu.html

deque(maxlen=10)
来源：http://dali.cheryme.top/Article/details/gt2zflrjedi.html

[U14] Py：分组收集到列表
来源：http://dali.cucudq.cn/Article/details/gt2enjdthhc.html

defaultdict(list)
来源：http://dali.316326.xyz/Article/details/gt2dqruxmth.html

[U15] Py：高精度计时
来源：http://dali.sweek.top/Article/details/gt2oktuqbep.html

t = time.perf_counter()
来源：http://dali.jinqigufen.top/Article/details/gt2jcfhwwwa.html

[U16] Py：命令行参数解析
来源：http://dali.zhongyouzk.top/Article/details/gt2bhoxqexz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.guannengcc.top/Article/details/gt2cyqfvyyz.html

[U17] Py：初始化日志
来源：http://dali.haohaochexian.top/Article/details/gt2clmhaksd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yj20258888.top/Article/details/gt2ryohckez.html

[U18] Py：预编译正则
来源：http://dali.yangfankeji.com/Article/details/gt2eilgqvqy.html

pat = re.compile(r"\d+")
来源：http://dali.ivvv.top/Article/details/gt2ynemlfyj.html

[U19] Py：正则替换带回调
来源：http://dali.vqdsnc.cn/Article/details/gt2pdcfhiwb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.redwolf501.top/Article/details/gt2xnzlzfuy.html

[U20] Py：缓存函数结果
来源：http://dali.zdqjudy.top/Article/details/gt2jqyddgas.html

@functools.lru_cache(maxsize=None)
来源：http://dali.svipenyu.cn/Article/details/gt2hcuwomkv.html

[U21] Py：自定义上下文管理器
来源：http://dali.smart0.xyz/Article/details/gt2uigyzcbd.html

@contextlib.contextmanager
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ybpehots.html

[U22] Py：矩阵转置
来源：http://dali.quarkkingdee.top/Article/details/gt2qrlshneu.html

list(zip(*m))
来源：http://dali.zhongyouzk.top/Article/details/gt2delvprvq.html

[U23] Py：分块读取大文件
来源：http://dali.ppjwa.cn/Article/details/gt2jttxxcop.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.feifeiyinyue.top/Article/details/gt2hrieaxyn.html

[U24] Py：路径操作
来源：http://dali.0kj1m.cn/Article/details/gt2rpqtsmza.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xylfe.cn/Article/details/gt2ttzxdrba.html

[U25] Py：CSV 按字典读
来源：http://dali.gogol.net.cn/Article/details/gt2psmoodua.html

csv.DictReader(f)
来源：http://dali.jqgufenzy.top/Article/details/gt2fxnnjulg.html

[U26] Py：并发下载
来源：http://dali.kuanghao11.cn/Article/details/gt2iwygbvlj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hysaishi.cn/Article/details/gt2oeqihayu.html

[U27] Py：异步 HTTP
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pjlkrnuk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhengqikj.top/Article/details/gt2ubjyjjtc.html

[U28] Py：类型别名
来源：http://dali.cqqwz.cn/Article/details/gt2mamvpzsp.html

UserId = int
来源：http://dali.yj20258.top/Article/details/gt2pxgkldzi.html

[U29] Py：属性校验
来源：http://dali.yongpay.top/Article/details/gt2pdeacate.html

@property 与 @x.setter 配合
来源：http://dali.shzxlz.cn/Article/details/gt2mnwecdez.html

[U30] Py：数据类
来源：http://dali.0kj1m.cn/Article/details/gt2abcyhwaz.html

@dataclass(slots=True)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zrysjewu.html

[U31] Py：单测
来源：http://dali.zhoulong.xyz/Article/details/gt2xkrpxvzq.html

python -m pytest -q
来源：http://dali.yanxiufei.cn/Article/details/gt2cpfqzfjl.html

[U32] Py：代码格式化
来源：http://dali.pengpengdd.cyou/Article/details/gt2tenxrwwe.html

ruff format . && ruff check --fix .
来源：http://dali.ydzc1.top/Article/details/gt2fhusugkp.html

[U33] Py：打包发布
来源：http://dali.hnxiangtu.top/Article/details/gt2pbocfgnt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xfugqsfv.html

[U34] Py：判断编码
来源：http://dali.gaohongyu789.top/Article/details/gt2mlmdzuou.html

chardet.detect(raw)
来源：http://dali.daria6918.cn/Article/details/gt2mrjkftjo.html

[U35] Py：发送邮件
来源：http://dali.yangfankeji.com/Article/details/gt2kkvmoeyq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.mhx1999.top/Article/details/gt2eggaeeho.html

[U36] Py：定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xzgqeewc.html

schedule.every(10).minutes.do(job)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gjeqnafi.html

[U37] Py：读写 Excel
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cvltdkxh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jqgufenzy.top/Article/details/gt2orhgbyao.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zbaltyjt.html

Path(__file__).resolve().parent
来源：http://dali.ehwqpu.com/Article/details/gt2edotocze.html

[U39] Py：判断是否在交互环境
来源：http://dali.zdqjudy.top/Article/details/gt2vfdfliml.html

sys.stdout.isatty()
来源：http://dali.tianlin.xyz/Article/details/gt2sbydnmky.html

[U40] Py：打印到标准错误
来源：http://dali.yvedp.cn/Article/details/gt2bsomonoz.html

print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gt2ylpicbfy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xziqi.cn/Article/details/gt2lwranguh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hywenlv.cn/Article/details/gt2plauzltr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.nanxuanxn.top/Article/details/gt2gugmkztl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hfpthk.cn/Article/details/gt2mjqohmfh.html

[U43] PHP：声明命名空间
来源：http://dali.daria6918.cn/Article/details/gt2khqsdzhg.html

namespace App\Http;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aelkbdmm.html

[U44] PHP：开启严格类型
来源：http://dali.9152youxi.cn/Article/details/gt2jnthooru.html

declare(strict_types=1);
来源：http://dali.wangdashe.top/Article/details/gt2mtkfpsvz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hfpthk.cn/Article/details/gt2yzxawtsf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gt2xsqwmpwp.html

[U46] PHP：可空类型
来源：http://dali.shzxlz.cn/Article/details/gt2kruwnozv.html

?string $name = null
来源：http://dali.bjfxy.top/Article/details/gt2wnnarogu.html

[U47] PHP：联合类型
来源：http://dali.wangdashe.top/Article/details/gt2ovhmbxyk.html

int|string $id
来源：http://dali.pycfn.com/Article/details/gt2ycwqojjq.html

[U48] PHP：纯枚举
来源：http://dali.yangfankeji.com/Article/details/gt2smqpjnee.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zdqjudy.top/Article/details/gt2ujgeejed.html

[U49] PHP：只读属性
来源：http://dali.mhx1999.top/Article/details/gt2sbjbjcfq.html

public readonly string $name
来源：http://dali.cheryme.top/Article/details/gt2dkkpyjqt.html

[U50] PHP：构造器属性提升
来源：http://dali.pycfn.com/Article/details/gt2clmyvetf.html

public function __construct(private int $id) {}
来源：http://dali.chenzaomai.com/Article/details/gt2ctrhdqsb.html

[U51] PHP：数组解构
来源：http://dali.hammf.cn/Article/details/gt2zzjteejj.html

[$a, $b] = $arr;
来源：http://dali.meibo888.top/Article/details/gt2plhccqzs.html

[U52] PHP：箭头函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aewcbzia.html

$double = fn($x) => $x * 2;
来源：http://dali.sufxvd.cn/Article/details/gt2fngylxdk.html

[U53] PHP：空合并运算符
来源：http://dali.ybcxt.top/Article/details/gt2aclidxse.html

$v = $a ?? $b ?? "default";
来源：http://dali.hysaishi.cn/Article/details/gt2terzfodo.html

[U54] PHP：空安全调用
来源：http://dali.zycfv.cn/Article/details/gt2ojcmsdis.html

$obj?->method()
来源：http://dali.9152youxi.cn/Article/details/gt2bpaggmne.html

[U55] PHP：match 表达式
来源：http://dali.haohaochexian.top/Article/details/gt2qhutxrad.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cashguo.top/Article/details/gt2xfeacmsb.html

[U56] PHP：命名参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2wpaodhrz.html

f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gt2byeeklzh.html

[U57] PHP：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jkfzpmhk.html

"值: {$a}"
来源：http://dali.guannengcc.top/Article/details/gt2khwsfmen.html

[U58] PHP：数组三件套
来源：http://dali.guowangkeji.top/Article/details/gt2wccjwhbu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cjrfqnuo.html

[U59] PHP：自定义排序
来源：http://dali.zdqjudy.top/Article/details/gt2fljjsiqc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258888.top/Article/details/gt2kydxaxie.html

[U60] PHP：JSON 编解码
来源：http://dali.andypj.xyz/Article/details/gt2kmebftev.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yj20258.top/Article/details/gt2vctesygx.html

[U61] PHP：正则
来源：http://dali.xinyue.icu/Article/details/gt2uuccnbxb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ddgcfksn.html

[U62] PHP：日期对象
来源：http://dali.gaohongyu789.top/Article/details/gt2gnhlaexz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.havefunace.top/Article/details/gt2gksfxnem.html

[U63] PHP：文件读写
来源：http://dali.cqqwz.cn/Article/details/gt2jypdznwl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinqigfzy.top/Article/details/gt2zuljurrf.html

[U64] PHP：目录遍历
来源：http://dali.hnqzz.top/Article/details/gt2edduiqnb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nwbrower.top/Article/details/gt2gtoyifqm.html

[U65] PHP：会话
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wynjsoso.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2dawmczxc.html

[U66] PHP：设置 Cookie
来源：http://dali.bjfxy.top/Article/details/gt2hgmjbljx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jfosxyhx.html

[U67] PHP：处理文件上传
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdjjnlmv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cashguo.top/Article/details/gt2ewurgipb.html

[U68] PHP：PDO 连接
来源：http://dali.hysaishi.cn/Article/details/gt2hbjpomvu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.quarkkingdee.top/Article/details/gt2ofbqefxq.html

[U69] PHP：PDO 预处理
来源：http://dali.sxryk.cn/Article/details/gt2fyumuupj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.9152youxi.cn/Article/details/gt2quaeiyiw.html

[U70] PHP：PDO 事务
来源：http://dali.guowangkeji.top/Article/details/gt2dxyqkuxr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.c1oappe.top/Article/details/gt2raeczgsa.html

[U71] PHP：抛出异常
来源：http://dali.nanxinkj.top/Article/details/gt2pfqnyfge.html

throw new RuntimeException("失败", 500);
来源：http://dali.sufxvd.cn/Article/details/gt2fiibemsf.html

[U72] PHP：写错误日志
来源：http://dali.jinqigufen.top/Article/details/gt2kkhqantu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhengqikj.top/Article/details/gt2deufsaki.html

[U73] PHP：读取 ini 配置
来源：http://dali.sufxvd.cn/Article/details/gt2smnprups.html

parse_ini_file("config.ini", true)
来源：http://dali.jqgufenzy.top/Article/details/gt2qpvhuskk.html

[U74] PHP：读取环境变量
来源：http://dali.quarkkingdee.top/Article/details/gt2gbufyoid.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qjsmeqib.html

[U75] PHP：依赖注入
来源：http://dali.pengpengdd.cyou/Article/details/gt2mkdqduwu.html

composer require psr/container
来源：http://dali.fzhhl.top/Article/details/gt2zkwymdua.html

[U76] PHP：简单路由
来源：http://dali.jqgfzy.top/Article/details/gt2dnxxnzsy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zycfv.cn/Article/details/gt2fzrczvgt.html

[U77] PHP：模板渲染
来源：http://dali.yj20258888.top/Article/details/gt2gngjhjzh.html

composer require twig/twig
来源：http://dali.yangfankeji.com/Article/details/gt2bbqkorkn.html

[U78] PHP：单元测试
来源：http://dali.jyoumei.cn/Article/details/gt2nmkjfomi.html

composer require --dev phpunit/phpunit
来源：http://dali.cucudq.cn/Article/details/gt2xscdbzgz.html

[U79] PHP：静态分析
来源：http://dali.zhiwuduotai.top/Article/details/gt2efxlkcya.html

composer require --dev phpstan/phpstan
来源：http://dali.chenzaomai.com/Article/details/gt2xasmdsym.html

[U80] PHP：代码规范修复
来源：http://dali.daxiang520.top/Article/details/gt2qjscjzbi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yanxiufei.cn/Article/details/gt2qrszoaym.html

[U81] JS：初始化项目
来源：http://dali.wangdashe.top/Article/details/gt2emwedtfs.html

npm init -y;  npm i express
来源：http://dali.zhixingplan.top/Article/details/gt2dsokkhar.html

[U82] JS：package.json 脚本
来源：http://dali.yongpay.top/Article/details/gt2mhvstggy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cdnleiting.top/Article/details/gt2vpnubuwy.html

[U83] JS：ES Module 导入导出
来源：http://dali.shzxlz.cn/Article/details/gt2illrzxhx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qsvejknf.html

[U84] JS：CommonJS 写法
来源：http://dali.yueranfly.top/Article/details/gt2lexuvxnb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.chenzaomai.com/Article/details/gt2ixnirbyz.html

[U85] JS：可选链
来源：http://dali.yuanzhike.top/Article/details/gt2kknfqdgc.html

a?.b?.c
来源：http://dali.yonumen.top/Article/details/gt2pprzhbur.html

[U86] JS：空值合并
来源：http://dali.sufxvd.cn/Article/details/gt2guqvnabh.html

a ?? b
来源：http://dali.ivvv.top/Article/details/gt2fyqytjsu.html

[U87] JS：解构默认值
来源：http://dali.zhoulong.xyz/Article/details/gt2mgzfkgca.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yanxiufei.cn/Article/details/gt2hfqvyebr.html

[U88] JS：对象展开合并
来源：http://dali.tanke756.top/Article/details/gt2jnnlmmox.html

{ ...a, ...b }
来源：http://dali.zhongyouzk.top/Article/details/gt2fgqgvoci.html

[U89] JS：数组去重
来源：http://dali.ydzc1.top/Article/details/gt2ucsrirpr.html

[...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gt2cmawovtu.html

[U90] JS：数字数组排序
来源：http://dali.jqgfzy.top/Article/details/gt2katrazic.html

[...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gt2msyycrzi.html

[U91] JS：对象键值遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2okybwazp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.tian-w.cn/Article/details/gt2yhzxamhf.html

[U92] JS：深拷贝
来源：http://dali.gotoacloud.top/Article/details/gt2ivfkopso.html

structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2gnicfqfh.html

[U93] JS：模板字符串
来源：http://dali.chenzaomai.com/Article/details/gt2hggccfxc.html

`共 ${n} 条`
来源：http://dali.chenjidiqi.icu/Article/details/gt2jwehzqqw.html

[U94] JS：箭头函数
来源：http://dali.pycfn.com/Article/details/gt2ngiwauui.html

const double = x => x * 2;
来源：http://dali.havefunace.top/Article/details/gt2ojrsedud.html

[U95] JS：Promise 包装
来源：http://dali.pengpengdd.cyou/Article/details/gt2gnfwkfqf.html

new Promise((resolve, reject) => {})
来源：http://dali.tianlin.xyz/Article/details/gt2rjbpzbed.html

[U96] JS：async/await 与异常
来源：http://dali.9152youxi.cn/Article/details/gt2oiwljvqf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gt2xpmrrtct.html

[U97] JS：并发请求
来源：http://dali.jinqigfzy.top/Article/details/gt2lowjkgpl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gt2ypjqainn.html

[U98] JS：fetch 带 JSON
来源：http://dali.ivvv.top/Article/details/gt2vwfdzydh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gaohongyu789.top/Article/details/gt2jqzhiwqm.html

[U99] JS：事件监听
来源：http://dali.cucudq.cn/Article/details/gt2ycusyhlc.html

el.addEventListener("click", e => {})
来源：http://dali.cheryme.top/Article/details/gt2zeoxgxgz.html

[U100] JS：DOM 查询
来源：http://dali.svipenyu.cn/Article/details/gt2aadkqdqm.html

document.querySelector(".item")
来源：http://dali.cheryme.top/Article/details/gt2qbcogebl.html

[U101] JS：classList 操作
来源：http://dali.birdmap.top/Article/details/gt2blsblvhk.html

el.classList.toggle("active")
来源：http://dali.quarkkingdee.top/Article/details/gt2xeggmijz.html

[U102] JS：本地存储
来源：http://dali.kuanghao11.cn/Article/details/gt2eoqeekez.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.guannengcc.top/Article/details/gt2hsfqzrls.html

[U103] JS：定时器
来源：http://dali.xinyue.icu/Article/details/gt2kavkyztd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xinyue.icu/Article/details/gt2qcokfgpe.html

[U104] JS：防抖
来源：http://dali.dashuyun.cn/Article/details/gt2mupejbtp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gt2mtbicbcp.html

[U105] JS：节流
来源：http://dali.ppjwa.cn/Article/details/gt2prhqiffm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2krxcawdk.html

[U106] JS：日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lovvfzca.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.dianchejie.cn/Article/details/gt2gzvzttjf.html

[U107] JS：数字千分位
来源：http://dali.yuxming.cn/Article/details/gt2pwhrmrzl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xinyue.icu/Article/details/gt2guxuezii.html

[U108] JS：随机整数
来源：http://dali.gogol.net.cn/Article/details/gt2hjobxxly.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jiagoushi.top/Article/details/gt2etucpufx.html

[U109] JS：数组分组
来源：http://dali.pengpengdd.cyou/Article/details/gt2opiviqrs.html

Object.groupBy(arr, x => x.type)
来源：http://dali.9152youxi.cn/Article/details/gt2eqygnkbe.html

[U110] JS：数组分块
来源：http://dali.wangshuangyany.cn/Article/details/gt2idztetos.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.vqdsnc.cn/Article/details/gt2igbcgwud.html

[U111] JS：对象转 Map
来源：http://dali.cucudq.cn/Article/details/gt2fkewrrzu.html

new Map(Object.entries(obj))
来源：http://dali.haohaochexian.top/Article/details/gt2djesaqlc.html

[U112] JS：字符串补位
来源：http://dali.ehwqpu.com/Article/details/gt2gncgmqzi.html

"7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gt2rrcvroqd.html

[U113] JS：正则替换全部
来源：http://dali.yj20258888.top/Article/details/gt2pujwwlsc.html

s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2acechkug.html

[U114] JS：JSON 深比较
来源：http://dali.sweek.top/Article/details/gt2gyxecgue.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.haohaochexian.top/Article/details/gt2fdsjgvji.html

[U115] JS：生成 UUID
来源：http://dali.yongpay.top/Article/details/gt2vzwafcbm.html

crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gt2kdrsvbjc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xuetiantiany.cn/Article/details/gt2wyvpfxiv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yueranfly.top/Article/details/gt2ipxvklzl.html

[U117] JS：单元测试
来源：http://dali.nwbrower.top/Article/details/gt2pbjipfgv.html

npm i -D vitest;  npx vitest
来源：http://dali.meibo888.top/Article/details/gt2gaozccjv.html

[U118] JS：开发服务器
来源：http://dali.ppjwa.cn/Article/details/gt2esntglro.html

npm i -D vite;  npx vite
来源：http://dali.gaohongyu789.top/Article/details/gt2talyloeh.html

[U119] JS：生产构建
来源：http://dali.wangshuangyany.cn/Article/details/gt2hmptbxqg.html

npx vite build
来源：http://dali.cashguo.top/Article/details/gt2xwwmotzy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zdqjudy.top/Article/details/gt2wexmqjsj.html

import.meta.env.VITE_API_URL
来源：http://dali.yanxiufei.cn/Article/details/gt2ypldopif.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2uqulpumq.html

统计汇总
来源：http://dali.aizwys.cn/Article/details/gt2vulkzept.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2fjoaqymz.html

按语言统计（条）：
来源：http://dali.aizwys.cn/Article/details/gt2qszjtzbv.html

Python ......... 252
来源：http://dali.fengsongda.top/Article/details/gt2igrfkfvn.html

PHP ............ 252
来源：http://dali.sweek.top/Article/details/gt2nvyzrwdr.html

JavaScript ..... 252
来源：http://dali.daxiang520.top/Article/details/gt2fqnfytbh.html

TypeScript ..... 212
来源：http://dali.chenzaomai.com/Article/details/gt2gnrujmop.html

Java ........... 212
来源：http://dali.kuanghao11.cn/Article/details/gt2vngqhyac.html

Go ............. 212
来源：http://dali.fengsongda.top/Article/details/gt2pmzhzyod.html

Ruby ........... 212
来源：http://dali.zycfv.cn/Article/details/gt2imfvlveb.html

C# ............. 212
来源：http://dali.yueranfly.top/Article/details/gt2imjneogt.html

C .............. 30
来源：http://dali.pycfn.com/Article/details/gt2csiigrlb.html

C++ ............ 30
来源：http://dali.xuanzx.com/Article/details/gt2fptuylys.html

SQL ............ 90
来源：http://dali.jqgufenzy.top/Article/details/gt2eacciaec.html

Bash ........... 80
来源：http://dali.dashuyun.cn/Article/details/gt2bxevolxy.html

Kotlin ......... 15
来源：http://dali.gaohongyu789.top/Article/details/gt2glqwnbkm.html

Swift .......... 15
来源：http://dali.yongpay.top/Article/details/gt2mnnkdmgz.html

Lua ............ 10
来源：http://dali.svipenyu.cn/Article/details/gt2tvmdnyhi.html

Perl ........... 10
来源：http://dali.mhx1999.top/Article/details/gt2xolssssh.html

Scala .......... 10
来源：http://dali.cashguo.top/Article/details/gt2rcioitlu.html

------------------------------------
来源：http://dali.guannengcc.top/Article/details/gt2hsuitdnx.html

合计 ........... 2106 条
来源：http://dali.quarkkingdee.top/Article/details/gt2jgojbxrs.html

按章节统计：
来源：http://dali.yj20258888.top/Article/details/gt2npngvzys.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.pycfn.com/Article/details/gt2fthyaucq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gt2xxyzygyi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jlsjyb.cn/Article/details/gt2ysvxgpqi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yonumen.top/Article/details/gt2ylhxzzwe.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zycfv.cn/Article/details/gt2cevihgrd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rykqcfwq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gt2oetsqwop.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenjidiqi.icu/Article/details/gt2axttooqm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tgmfpmcs.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.c1oappe.top/Article/details/gt2arykovyf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gt2oyfoxndr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gt2lmjzzokv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gt2ovgtspfv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zdqjudy.top/Article/details/gt2pkilxcpp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xylfe.cn/Article/details/gt2hbygxzty.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gt2yoolwwhp.html

Q SQL 专题                              90
来源：http://dali.ybcxt.top/Article/details/gt2zdhrwvvg.html

R Bash 专题                             80
来源：http://dali.yuanzhike.top/Article/details/gt2qtclmahb.html

S C / C++ 专题                          60
来源：http://dali.guannengcc.top/Article/details/gt2lmqpbxhw.html

T 其他语言补充                          60
来源：http://dali.daria6918.cn/Article/details/gt2yokcxnyt.html

U 高频实用片段                         120
来源：http://dali.redwolf501.top/Article/details/gt2tgguygvh.html

------------------------------------
来源：http://dali.aizwys.cn/Article/details/gt2atqrxqdn.html

合计                                  2106 条
来源：http://dali.hongshengwenyu.top/Article/details/gt2fvtkmmlp.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gt2xdyspylg.html

使用提醒
来源：http://dali.xuanzx.com/Article/details/gt2dyggxnck.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gt2elzofvmp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jqgufenzy.top/Article/details/gt2cirmqidk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2smwsbdtt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cucudq.cn/Article/details/gt2tqmrifjb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yvedp.cn/Article/details/gt2jhbtvtdf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhengqikj.top/Article/details/gt2rhycknvw.html

—— 文件结束 ——
来源：http://dali.chenzaomai.com/Article/details/gt2kulyndnb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2fjffqcbj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.gotoacloud.top/Article/details/gt2touopylk.html

Common Programming Examples Cheat Book
来源：http://dali.0kj1m.cn/Article/details/gt2adrtznou.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2jyleqiun.html


<!-- 参考信息 -->