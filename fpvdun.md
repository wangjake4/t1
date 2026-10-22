代发 wailian999

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gogol.net.cn/Article/details/gt2awvrfmey.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2gqrvhxee.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shuidangran.top/Article/details/gt2ssygedik.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2yybpzvvj.html

[U01] Py：创建虚拟环境
来源：http://dali.guannengcc.top/Article/details/gt2ikugisqz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aibaodan.cn/Article/details/gt2bshkzubd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.birdmap.top/Article/details/gt2agzauobb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xziqi.cn/Article/details/gt2ayepdnwn.html

[U03] Py：加载 .env 配置
来源：http://dali.zhixingplan.top/Article/details/gt2glggqkur.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgfzy.top/Article/details/gt2qxxssite.html

[U04] Py：变量调试打印
来源：http://dali.quarkkingdee.top/Article/details/gt2jxtbgocb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenzaomai.com/Article/details/gt2mvuvwtsi.html

[U05] Py：列表去重且保序
来源：http://dali.yueranfly.top/Article/details/gt2pdtddirz.html

list(dict.fromkeys(arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2stxjlgmf.html

[U06] Py：合并两个字典
来源：http://dali.birdmap.top/Article/details/gt2lkietfyj.html

{**a, **b}
来源：http://dali.zhixingplan.top/Article/details/gt2zrrrbedt.html

[U07] Py：反转字典键值
来源：http://dali.birdmap.top/Article/details/gt2ddiebycq.html

{v: k for k, v in d.items()}
来源：http://dali.aibaodan.cn/Article/details/gt2wulgaubf.html

[U08] Py：展平二维列表
来源：http://dali.yangfankeji.com/Article/details/gt2wkuigrna.html

[y for x in nested for y in x]
来源：http://dali.hfpthk.cn/Article/details/gt2uimncens.html

[U09] Py：字典取最大值的键
来源：http://dali.snrcjt.cn/Article/details/gt2fsoxqzwu.html

max(d, key=d.get)
来源：http://dali.pycfn.com/Article/details/gt2cnzfxorn.html

[U10] Py：按值排序字典
来源：http://dali.fzhhl.top/Article/details/gt2eqjgnfbw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hongshengwenyu.top/Article/details/gt2ivjacrdo.html

[U11] Py：生成器表达式
来源：http://dali.meibo888.top/Article/details/gt2sdvvnmkv.html

(x * 2 for x in arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oigppzug.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.andypj.xyz/Article/details/gt2acmvobee.html

Counter(arr).most_common(3)
来源：http://dali.nwbrower.top/Article/details/gt2ajkcazun.html

[U13] Py：固定长度队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2waxxropw.html

deque(maxlen=10)
来源：http://dali.iojbl.cn/Article/details/gt2yisohdqm.html

[U14] Py：分组收集到列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vdgvioza.html

defaultdict(list)
来源：http://dali.hammf.cn/Article/details/gt2alkkffij.html

[U15] Py：高精度计时
来源：http://dali.snrcjt.cn/Article/details/gt2ucchsxdf.html

t = time.perf_counter()
来源：http://dali.hammf.cn/Article/details/gt2pccftfnc.html

[U16] Py：命令行参数解析
来源：http://dali.guowangkeji.top/Article/details/gt2zmevvyey.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nwbrower.top/Article/details/gt2cdudhplm.html

[U17] Py：初始化日志
来源：http://dali.daria6918.cn/Article/details/gt2trjdixig.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ybcxt.top/Article/details/gt2nkoropxe.html

[U18] Py：预编译正则
来源：http://dali.ydzc1.top/Article/details/gt2qqteerya.html

pat = re.compile(r"\d+")
来源：http://dali.haohaochexian.top/Article/details/gt2oiwgsrfc.html

[U19] Py：正则替换带回调
来源：http://dali.hfpthk.cn/Article/details/gt2kwezdtdy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sufxvd.cn/Article/details/gt2dwkepukt.html

[U20] Py：缓存函数结果
来源：http://dali.hysaishi.cn/Article/details/gt2mhffqxlz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gzhubu.top/Article/details/gt2lisjwtgx.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yovenigh.html

@contextlib.contextmanager
来源：http://dali.cdnleiting.top/Article/details/gt2wnasncvh.html

[U22] Py：矩阵转置
来源：http://dali.aibaodan.cn/Article/details/gt2vrkixklo.html

list(zip(*m))
来源：http://dali.daria6918.cn/Article/details/gt2dqckureo.html

[U23] Py：分块读取大文件
来源：http://dali.0kj1m.cn/Article/details/gt2noqxoudy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhixingplan.top/Article/details/gt2peglrjst.html

[U24] Py：路径操作
来源：http://dali.dianchejie.cn/Article/details/gt2fujewjme.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gt2wxoxhsyp.html

[U25] Py：CSV 按字典读
来源：http://dali.hysaishi.cn/Article/details/gt2oiyqbtwr.html

csv.DictReader(f)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfbrrnlv.html

[U26] Py：并发下载
来源：http://dali.chenlongwang.top/Article/details/gt2rpamzlaf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jiagoushi.top/Article/details/gt2bivzscxl.html

[U27] Py：异步 HTTP
来源：http://dali.pengpengdd.cyou/Article/details/gt2fgiuyyte.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenzaomai.com/Article/details/gt2abwdqecv.html

[U28] Py：类型别名
来源：http://dali.yonumen.top/Article/details/gt2oklmorbj.html

UserId = int
来源：http://dali.tian-w.cn/Article/details/gt2pcncgthe.html

[U29] Py：属性校验
来源：http://dali.wangshuangyany.cn/Article/details/gt2ajfujrnn.html

@property 与 @x.setter 配合
来源：http://dali.cheryme.top/Article/details/gt2nduoikft.html

[U30] Py：数据类
来源：http://dali.yj20258.top/Article/details/gt2dcxkhoiy.html

@dataclass(slots=True)
来源：http://dali.zhixingplan.top/Article/details/gt2sonadxqm.html

[U31] Py：单测
来源：http://dali.316326.xyz/Article/details/gt2bixszoao.html

python -m pytest -q
来源：http://dali.xylfe.cn/Article/details/gt2nqthtldz.html

[U32] Py：代码格式化
来源：http://dali.iojbl.cn/Article/details/gt2tjclwfcw.html

ruff format . && ruff check --fix .
来源：http://dali.yongpay.top/Article/details/gt2ivtwbquk.html

[U33] Py：打包发布
来源：http://dali.xuanzx.com/Article/details/gt2igattaae.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hammf.cn/Article/details/gt2zkyqhpcb.html

[U34] Py：判断编码
来源：http://dali.zhixingplan.top/Article/details/gt2jlprkvaa.html

chardet.detect(raw)
来源：http://dali.ppjwa.cn/Article/details/gt2tqhschkm.html

[U35] Py：发送邮件
来源：http://dali.ehwqpu.com/Article/details/gt2kqafbruu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lreqofbx.html

[U36] Py：定时任务
来源：http://dali.jianghu66.top/Article/details/gt2hidzdrvd.html

schedule.every(10).minutes.do(job)
来源：http://dali.sweek.top/Article/details/gt2shqkptrb.html

[U37] Py：读写 Excel
来源：http://dali.zdqjudy.top/Article/details/gt2viknophq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hnxiangtu.top/Article/details/gt2qfrpfuat.html

[U38] Py：获取脚本所在目录
来源：http://dali.fengsongda.top/Article/details/gt2vxkdeuoi.html

Path(__file__).resolve().parent
来源：http://dali.birdmap.top/Article/details/gt2sogazgrm.html

[U39] Py：判断是否在交互环境
来源：http://dali.kuanghao11.cn/Article/details/gt2ssdqbyhb.html

sys.stdout.isatty()
来源：http://dali.xylfe.cn/Article/details/gt2gohiwhrb.html

[U40] Py：打印到标准错误
来源：http://dali.cdnleiting.top/Article/details/gt2yqbfcnxm.html

print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gt2tlwysqgj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.wangshuangyany.cn/Article/details/gt2iyzvphmo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.316326.xyz/Article/details/gt2lrmeteeu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zdqjudy.top/Article/details/gt2uihjfjaz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zdqjudy.top/Article/details/gt2jtcfekwq.html

[U43] PHP：声明命名空间
来源：http://dali.zhongyouzk.top/Article/details/gt2pmkeagzq.html

namespace App\Http;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hmodqwmq.html

[U44] PHP：开启严格类型
来源：http://dali.gzhubu.top/Article/details/gt2ihyaofzt.html

declare(strict_types=1);
来源：http://dali.hywenlv.cn/Article/details/gt2mcipojsp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2vqtqeqrg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gt2vcwxwbvo.html

[U46] PHP：可空类型
来源：http://dali.jqgfzy.top/Article/details/gt2wcnxxblz.html

?string $name = null
来源：http://dali.pengpengdd.cyou/Article/details/gt2muiuzsgp.html

[U47] PHP：联合类型
来源：http://dali.jqgufenzy.top/Article/details/gt2qkfxjkpo.html

int|string $id
来源：http://dali.chenlongwang.top/Article/details/gt2bioalylm.html

[U48] PHP：纯枚举
来源：http://dali.zhiwuduotai.top/Article/details/gt2hbfebcek.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ydzc1.top/Article/details/gt2laoihjzl.html

[U49] PHP：只读属性
来源：http://dali.hnxiangtu.top/Article/details/gt2ebxzhakz.html

public readonly string $name
来源：http://dali.dashuyun.cn/Article/details/gt2znkfintc.html

[U50] PHP：构造器属性提升
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dmnzklxe.html

public function __construct(private int $id) {}
来源：http://dali.tanke756.top/Article/details/gt2loebefxu.html

[U51] PHP：数组解构
来源：http://dali.fzhhl.top/Article/details/gt2avwuwzuk.html

[$a, $b] = $arr;
来源：http://dali.guannengcc.top/Article/details/gt2qqqetnhr.html

[U52] PHP：箭头函数
来源：http://dali.yj20258888.top/Article/details/gt2nqwjkvzb.html

$double = fn($x) => $x * 2;
来源：http://dali.cheryme.top/Article/details/gt2ebjjctxo.html

[U53] PHP：空合并运算符
来源：http://dali.svipenyu.cn/Article/details/gt2zyexsoat.html

$v = $a ?? $b ?? "default";
来源：http://dali.316326.xyz/Article/details/gt2rcbapsuq.html

[U54] PHP：空安全调用
来源：http://dali.gogol.net.cn/Article/details/gt2jhsyjzsr.html

$obj?->method()
来源：http://dali.316326.xyz/Article/details/gt2xgeeswvh.html

[U55] PHP：match 表达式
来源：http://dali.sxryk.cn/Article/details/gt2sxbovafe.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hnxiangtu.top/Article/details/gt2usnuwoyg.html

[U56] PHP：命名参数
来源：http://dali.cheryme.top/Article/details/gt2omihqpcz.html

f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2akcchugg.html

[U57] PHP：字符串插值
来源：http://dali.yj20258888.top/Article/details/gt2ewwtdplk.html

"值: {$a}"
来源：http://dali.shuidangran.top/Article/details/gt2qnhpmqmu.html

[U58] PHP：数组三件套
来源：http://dali.mhx1999.top/Article/details/gt2rcuoaxmf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sxryk.cn/Article/details/gt2cxmbbnvr.html

[U59] PHP：自定义排序
来源：http://dali.jianghu66.top/Article/details/gt2dqglagrm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gt2tqlhcuvs.html

[U60] PHP：JSON 编解码
来源：http://dali.nanxuanxn.top/Article/details/gt2psrzbolg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2qlqajeeg.html

[U61] PHP：正则
来源：http://dali.cqqwz.cn/Article/details/gt2rkykunwk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2nvjpqkvk.html

[U62] PHP：日期对象
来源：http://dali.guowangkeji.top/Article/details/gt2rsgnlwck.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hywenlv.cn/Article/details/gt2nqmvnpes.html

[U63] PHP：文件读写
来源：http://dali.hammf.cn/Article/details/gt2kvewfbnf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hysaishi.cn/Article/details/gt2ckrfggnp.html

[U64] PHP：目录遍历
来源：http://dali.svipenyu.cn/Article/details/gt2hisytxtc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.feifeiyinyue.top/Article/details/gt2qvnqzade.html

[U65] PHP：会话
来源：http://dali.aibaodan.cn/Article/details/gt2owugyqdl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2gybcffoc.html

[U66] PHP：设置 Cookie
来源：http://dali.iojbl.cn/Article/details/gt2qieepetj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sysykeji.top/Article/details/gt2jmhcsemr.html

[U67] PHP：处理文件上传
来源：http://dali.ydzc1.top/Article/details/gt2hmefoyij.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.bjfxy.top/Article/details/gt2pmdtxvsz.html

[U68] PHP：PDO 连接
来源：http://dali.dianchejie.cn/Article/details/gt2zdxynlqc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yj20258888.top/Article/details/gt2sikdkwwx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2psspckjg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yonumen.top/Article/details/gt2iubvbgrd.html

[U70] PHP：PDO 事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mdysfwkw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jyoumei.cn/Article/details/gt2vimnvwct.html

[U71] PHP：抛出异常
来源：http://dali.xinyue.icu/Article/details/gt2bevfobzf.html

throw new RuntimeException("失败", 500);
来源：http://dali.nwbrower.top/Article/details/gt2uziwixew.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrilewp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.redwolf501.top/Article/details/gt2rirsoufy.html

[U73] PHP：读取 ini 配置
来源：http://dali.tanke756.top/Article/details/gt2sindtptg.html

parse_ini_file("config.ini", true)
来源：http://dali.jinqigfzy.top/Article/details/gt2skfdyqrz.html

[U74] PHP：读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gt2bcgdztgt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yonumen.top/Article/details/gt2cunypaam.html

[U75] PHP：依赖注入
来源：http://dali.hnxiangtu.top/Article/details/gt2blfhdhak.html

composer require psr/container
来源：http://dali.zhengqikj.top/Article/details/gt2zvysfzbf.html

[U76] PHP：简单路由
来源：http://dali.hnxiangtu.top/Article/details/gt2iobarmie.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yvedp.cn/Article/details/gt2tjkcgjck.html

[U77] PHP：模板渲染
来源：http://dali.zhixingplan.top/Article/details/gt2xyjqugmo.html

composer require twig/twig
来源：http://dali.guowangkeji.top/Article/details/gt2pjyonomj.html

[U78] PHP：单元测试
来源：http://dali.pycfn.com/Article/details/gt2kdqlztfg.html

composer require --dev phpunit/phpunit
来源：http://dali.yueranfly.top/Article/details/gt2bfhkramj.html

[U79] PHP：静态分析
来源：http://dali.andypj.xyz/Article/details/gt2yszuueqz.html

composer require --dev phpstan/phpstan
来源：http://dali.nanxinkj.top/Article/details/gt2zcnhwacp.html

[U80] PHP：代码规范修复
来源：http://dali.shzxlz.cn/Article/details/gt2alvfdxxc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.fzhhl.top/Article/details/gt2yuduuucw.html

[U81] JS：初始化项目
来源：http://dali.mhx1999.top/Article/details/gt2lxpaclji.html

npm init -y;  npm i express
来源：http://dali.cashguo.top/Article/details/gt2mpxgkkrj.html

[U82] JS：package.json 脚本
来源：http://dali.dianchejie.cn/Article/details/gt2uqsfnjnu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tqcuqdzv.html

[U83] JS：ES Module 导入导出
来源：http://dali.chenzaomai.com/Article/details/gt2utfgihoj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.tianlin.xyz/Article/details/gt2pjayjnom.html

[U84] JS：CommonJS 写法
来源：http://dali.chenjidiqi.icu/Article/details/gt2zjlggatx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.tian-w.cn/Article/details/gt2oknurxcf.html

[U85] JS：可选链
来源：http://dali.ppjwa.cn/Article/details/gt2loboziam.html

a?.b?.c
来源：http://dali.cucudq.cn/Article/details/gt2yyriioeg.html

[U86] JS：空值合并
来源：http://dali.jinqigufen.top/Article/details/gt2ywwmgrhe.html

a ?? b
来源：http://dali.yj20258.top/Article/details/gt2rxgsajkb.html

[U87] JS：解构默认值
来源：http://dali.pengpengdd.cyou/Article/details/gt2vxodrrbh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.nanxuanxn.top/Article/details/gt2musceblu.html

[U88] JS：对象展开合并
来源：http://dali.zhiwuduotai.top/Article/details/gt2fotnmeea.html

{ ...a, ...b }
来源：http://dali.iojbl.cn/Article/details/gt2zdypalvz.html

[U89] JS：数组去重
来源：http://dali.cheryme.top/Article/details/gt2wqpevfyg.html

[...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gt2opdoenve.html

[U90] JS：数字数组排序
来源：http://dali.gaohongyu789.top/Article/details/gt2aoyjeiyo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gt2pczspegw.html

[U91] JS：对象键值遍历
来源：http://dali.yangfankeji.com/Article/details/gt2exwlaucl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yangfankeji.com/Article/details/gt2mqonzylu.html

[U92] JS：深拷贝
来源：http://dali.sxryk.cn/Article/details/gt2aqbkbfwa.html

structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2fyctptwc.html

[U93] JS：模板字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hpsrsmda.html

`共 ${n} 条`
来源：http://dali.jqgufenzy.top/Article/details/gt2oplluigc.html

[U94] JS：箭头函数
来源：http://dali.aizwys.cn/Article/details/gt2crtrtiub.html

const double = x => x * 2;
来源：http://dali.jianghu66.top/Article/details/gt2hotbcpdy.html

[U95] JS：Promise 包装
来源：http://dali.zdqjudy.top/Article/details/gt2zvlqagim.html

new Promise((resolve, reject) => {})
来源：http://dali.guannengcc.top/Article/details/gt2vwdylacr.html

[U96] JS：async/await 与异常
来源：http://dali.shuidangran.top/Article/details/gt2sfpknbqp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gt2jespartm.html

[U97] JS：并发请求
来源：http://dali.iojbl.cn/Article/details/gt2zvffooiq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gt2nqxfjfag.html

[U98] JS：fetch 带 JSON
来源：http://dali.smart0.xyz/Article/details/gt2miiovnka.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.smart0.xyz/Article/details/gt2asdixfzv.html

[U99] JS：事件监听
来源：http://dali.kuanghao11.cn/Article/details/gt2llnnwwmb.html

el.addEventListener("click", e => {})
来源：http://dali.shangyingyoupin.top/Article/details/gt2dliovatk.html

[U100] JS：DOM 查询
来源：http://dali.nanxuanxn.top/Article/details/gt2yhdkkjhl.html

document.querySelector(".item")
来源：http://dali.nanxuanxn.top/Article/details/gt2yugaeuhb.html

[U101] JS：classList 操作
来源：http://dali.cqqwz.cn/Article/details/gt2rwiwrcrn.html

el.classList.toggle("active")
来源：http://dali.mhx1999.top/Article/details/gt2aksnswqh.html

[U102] JS：本地存储
来源：http://dali.daria6918.cn/Article/details/gt2vynvoywi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.gzhubu.top/Article/details/gt2zqkvkjrf.html

[U103] JS：定时器
来源：http://dali.hysaishi.cn/Article/details/gt2fwwcyhmb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vpnlgfsq.html

[U104] JS：防抖
来源：http://dali.dianchejie.cn/Article/details/gt2rjlbvcwy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ivvv.top/Article/details/gt2vhfulcqn.html

[U105] JS：节流
来源：http://dali.chenlongwang.top/Article/details/gt2nxwlwbbp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.fzhhl.top/Article/details/gt2sbvwrskt.html

[U106] JS：日期格式化
来源：http://dali.xuanzx.com/Article/details/gt2fgollqbv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvunznv.html

[U107] JS：数字千分位
来源：http://dali.daria6918.cn/Article/details/gt2hfhpfdch.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gt2poesltor.html

[U108] JS：随机整数
来源：http://dali.hammf.cn/Article/details/gt2fwdsafcr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yongpay.top/Article/details/gt2ibklfhfp.html

[U109] JS：数组分组
来源：http://dali.aibaodan.cn/Article/details/gt2flgkygxa.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yvedp.cn/Article/details/gt2jkrdzbnp.html

[U110] JS：数组分块
来源：http://dali.havefunace.top/Article/details/gt2cjreljxh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tian-w.cn/Article/details/gt2bcnpicqg.html

[U111] JS：对象转 Map
来源：http://dali.cqqwz.cn/Article/details/gt2gqxcfkom.html

new Map(Object.entries(obj))
来源：http://dali.haohaochexian.top/Article/details/gt2jgstbbzz.html

[U112] JS：字符串补位
来源：http://dali.mhx1999.top/Article/details/gt2tskaehem.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyqklvm.html

[U113] JS：正则替换全部
来源：http://dali.sufxvd.cn/Article/details/gt2sjrxqfzh.html

s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2rohdmjrh.html

[U114] JS：JSON 深比较
来源：http://dali.andypj.xyz/Article/details/gt2nukipsgx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.bjfxy.top/Article/details/gt2dmkuovuw.html

[U115] JS：生成 UUID
来源：http://dali.zhoulong.xyz/Article/details/gt2uivnwzwo.html

crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zmhlugts.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vvtrrriv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cucudq.cn/Article/details/gt2jdmbwrsl.html

[U117] JS：单元测试
来源：http://dali.gaohongyu789.top/Article/details/gt2nqtlmsrg.html

npm i -D vitest;  npx vitest
来源：http://dali.xuanzx.com/Article/details/gt2shhghnyl.html

[U118] JS：开发服务器
来源：http://dali.hfpthk.cn/Article/details/gt2obaszcis.html

npm i -D vite;  npx vite
来源：http://dali.c1oappe.top/Article/details/gt2gjouveoc.html

[U119] JS：生产构建
来源：http://dali.quarkkingdee.top/Article/details/gt2xoelazha.html

npx vite build
来源：http://dali.hfpthk.cn/Article/details/gt2fdpeuida.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.havefunace.top/Article/details/gt2mvgzloig.html

import.meta.env.VITE_API_URL
来源：http://dali.xuanzx.com/Article/details/gt2nfhcvjfv.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2nacxlccl.html

统计汇总
来源：http://dali.jiagoushi.top/Article/details/gt2yakucikw.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2xjrjxykt.html

按语言统计（条）：
来源：http://dali.meibo888.top/Article/details/gt2usldgnil.html

Python ......... 252
来源：http://dali.jinghuilouyu.cn/Article/details/gt2drlrfoul.html

PHP ............ 252
来源：http://dali.dianchejie.cn/Article/details/gt2lhgocxbd.html

JavaScript ..... 252
来源：http://dali.chenlongwang.top/Article/details/gt2ojmexrzf.html

TypeScript ..... 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ubqjpjwk.html

Java ........... 212
来源：http://dali.jinqigfzy.top/Article/details/gt2pealjhnb.html

Go ............. 212
来源：http://dali.quarkkingdee.top/Article/details/gt2fiswoblo.html

Ruby ........... 212
来源：http://dali.quarkkingdee.top/Article/details/gt2gkvdbpwx.html

C# ............. 212
来源：http://dali.ybcxt.top/Article/details/gt2jqxbjzxo.html

C .............. 30
来源：http://dali.nanxinkj.top/Article/details/gt2varxhuqm.html

C++ ............ 30
来源：http://dali.quarkkingdee.top/Article/details/gt2lsphpeam.html

SQL ............ 90
来源：http://dali.zhoulong.xyz/Article/details/gt2rahkybnx.html

Bash ........... 80
来源：http://dali.yuxming.cn/Article/details/gt2ybqiiuxp.html

Kotlin ......... 15
来源：http://dali.yvedp.cn/Article/details/gt2drsckeez.html

Swift .......... 15
来源：http://dali.hammf.cn/Article/details/gt2oylczfnh.html

Lua ............ 10
来源：http://dali.yj20258.top/Article/details/gt2xoqkzzyt.html

Perl ........... 10
来源：http://dali.hywenlv.cn/Article/details/gt2tqseuigy.html

Scala .......... 10
来源：http://dali.sysykeji.top/Article/details/gt2ahjylfhz.html

------------------------------------
来源：http://dali.sxryk.cn/Article/details/gt2sabodqgg.html

合计 ........... 2106 条
来源：http://dali.pycfn.com/Article/details/gt2zvnqihov.html

按章节统计：
来源：http://dali.daria6918.cn/Article/details/gt2iuymsitu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gogol.net.cn/Article/details/gt2bnjbfnoe.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hammf.cn/Article/details/gt2nlirlvko.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gt2khjmxgyb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ybcxt.top/Article/details/gt2kbdvsdff.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sufxvd.cn/Article/details/gt2mtcolupp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.birdmap.top/Article/details/gt2teowyqaz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gt2jrhwrkwt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gt2ryvmcjky.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gt2lzbnbwwn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sweek.top/Article/details/gt2vksnsrda.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gt2dduipxqv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gt2esjlzbwh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gt2zuasxiiu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.pycfn.com/Article/details/gt2vekhoxpd.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cucudq.cn/Article/details/gt2zjhhfruz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gt2enxwhyfh.html

Q SQL 专题                              90
来源：http://dali.sufxvd.cn/Article/details/gt2ejvzmaho.html

R Bash 专题                             80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2halondez.html

S C / C++ 专题                          60
来源：http://dali.hfpthk.cn/Article/details/gt2saydztwg.html

T 其他语言补充                          60
来源：http://dali.cqqwz.cn/Article/details/gt2bpvbrejs.html

U 高频实用片段                         120
来源：http://dali.dashuyun.cn/Article/details/gt2etnhabcg.html

------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gt2bqpgztts.html

合计                                  2106 条
来源：http://dali.jinqigufen.top/Article/details/gt2sbeoyljc.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gt2ezgcchug.html

使用提醒
来源：http://dali.nanxuanxn.top/Article/details/gt2nuwuiwzs.html

--------------------------------------------------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gt2ymlvvnpe.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2zymapisw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.fengsongda.top/Article/details/gt2mmlpwlce.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jorqkamk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hammf.cn/Article/details/gt2szyxqvmx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.tianlin.xyz/Article/details/gt2bigfrkai.html

—— 文件结束 ——
来源：http://dali.dashuyun.cn/Article/details/gt2lrbczqta.html


<!-- 参考信息 -->