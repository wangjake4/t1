代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ppjwa.cn/Article/details/gtnjvsxgkx.html

[T59] Scala：循环
来源：http://dali.wangdashe.top/Article/details/gtyeewkckf.html

for (i <- 1 to 10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gttptewrjq.html

[T60] Scala：折叠
来源：http://dali.9152youxi.cn/Article/details/gtzamjtoyx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrpljfnr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtwxfzowwa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shzxlz.cn/Article/details/gtdgsylzbe.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtxqgvefdj.html

[U01] Py：创建虚拟环境
来源：http://dali.zdqjudy.top/Article/details/gtdkbwfcfs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jlsjyb.cn/Article/details/gtshjdphdd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuetiantiany.cn/Article/details/gtbvwpdkrz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hfpthk.cn/Article/details/gtnyhwqsyn.html

[U03] Py：加载 .env 配置
来源：http://dali.quarkkingdee.top/Article/details/gtmzqulxjv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zdqjudy.top/Article/details/gtssmeiigh.html

[U04] Py：变量调试打印
来源：http://dali.hysaishi.cn/Article/details/gthscjmpfg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cucudq.cn/Article/details/gtlepapdrk.html

[U05] Py：列表去重且保序
来源：http://dali.fzhhl.top/Article/details/gtlerpcchr.html

list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gtaspnjzhu.html

[U06] Py：合并两个字典
来源：http://dali.jianghu66.top/Article/details/gtmxohuonu.html

{**a, **b}
来源：http://dali.nwbrower.top/Article/details/gtkwonfbui.html

[U07] Py：反转字典键值
来源：http://dali.cqqwz.cn/Article/details/gtwgnicgmq.html

{v: k for k, v in d.items()}
来源：http://dali.wangdashe.top/Article/details/gtlebhsenk.html

[U08] Py：展平二维列表
来源：http://dali.fengsongda.top/Article/details/gtmlpkipzd.html

[y for x in nested for y in x]
来源：http://dali.daxiang520.top/Article/details/gtdbyzocon.html

[U09] Py：字典取最大值的键
来源：http://dali.sufxvd.cn/Article/details/gtzzdxdyll.html

max(d, key=d.get)
来源：http://dali.jqgufenzy.top/Article/details/gtmrdxplnh.html

[U10] Py：按值排序字典
来源：http://dali.jiagoushi.top/Article/details/gtmqvsjktk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hnqzz.top/Article/details/gtqsthmaih.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtgydmijal.html

(x * 2 for x in arr)
来源：http://dali.redwolf501.top/Article/details/gtkotwsccb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnqzz.top/Article/details/gtvxuwwgtr.html

Counter(arr).most_common(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtqfvufitf.html

[U13] Py：固定长度队列
来源：http://dali.yuanzhike.top/Article/details/gtlgtvoojw.html

deque(maxlen=10)
来源：http://dali.smart0.xyz/Article/details/gtnzlhzimu.html

[U14] Py：分组收集到列表
来源：http://dali.jiagoushi.top/Article/details/gtocxzxurz.html

defaultdict(list)
来源：http://dali.jqgfzy.top/Article/details/gtxjumdkwq.html

[U15] Py：高精度计时
来源：http://dali.hywenlv.cn/Article/details/gttnefhleg.html

t = time.perf_counter()
来源：http://dali.sweek.top/Article/details/gtnbffbffc.html

[U16] Py：命令行参数解析
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbrmdzts.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.mhx1999.top/Article/details/gtgogednnd.html

[U17] Py：初始化日志
来源：http://dali.ybcxt.top/Article/details/gtsrdkvfdz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jqgufenzy.top/Article/details/gtyrjulouk.html

[U18] Py：预编译正则
来源：http://dali.hongshengwenyu.top/Article/details/gtfmmuhxsn.html

pat = re.compile(r"\d+")
来源：http://dali.smart0.xyz/Article/details/gtiyelbxik.html

[U19] Py：正则替换带回调
来源：http://dali.bjfxy.top/Article/details/gtfbdbggsb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.aizwys.cn/Article/details/gtignyooao.html

[U20] Py：缓存函数结果
来源：http://dali.pengpengdd.cyou/Article/details/gtkuwducuj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xuanzx.com/Article/details/gthsznwuso.html

[U21] Py：自定义上下文管理器
来源：http://dali.nanxinkj.top/Article/details/gtbutunfcn.html

@contextlib.contextmanager
来源：http://dali.sysykeji.top/Article/details/gtjydahcan.html

[U22] Py：矩阵转置
来源：http://dali.chenjidiqi.icu/Article/details/gtsdecehtz.html

list(zip(*m))
来源：http://dali.nwbrower.top/Article/details/gtgzvpbnyp.html

[U23] Py：分块读取大文件
来源：http://dali.jlsjyb.cn/Article/details/gtvaehfisc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gaohongyu789.top/Article/details/gtglbvhzdb.html

[U24] Py：路径操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gticycscia.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gtxhvivuqz.html

[U25] Py：CSV 按字典读
来源：http://dali.guannengcc.top/Article/details/gtjbmdaupj.html

csv.DictReader(f)
来源：http://dali.cashguo.top/Article/details/gthpgimhfe.html

[U26] Py：并发下载
来源：http://dali.zhiwuduotai.top/Article/details/gtsjeoggfk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yonumen.top/Article/details/gtokncdnke.html

[U27] Py：异步 HTTP
来源：http://dali.jqgufenzy.top/Article/details/gtrpgmmiky.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jyoumei.cn/Article/details/gtxipaabqb.html

[U28] Py：类型别名
来源：http://dali.nanxuanxn.top/Article/details/gtqazdvxnx.html

UserId = int
来源：http://dali.aizwys.cn/Article/details/gtsjdbbrmf.html

[U29] Py：属性校验
来源：http://dali.xuanzx.com/Article/details/gtuahtpzzd.html

@property 与 @x.setter 配合
来源：http://dali.yonumen.top/Article/details/gtjeshwzod.html

[U30] Py：数据类
来源：http://dali.hammf.cn/Article/details/gtoixhsjoy.html

@dataclass(slots=True)
来源：http://dali.hfpthk.cn/Article/details/gtormqmhtc.html

[U31] Py：单测
来源：http://dali.jianghu66.top/Article/details/gtjpepaszv.html

python -m pytest -q
来源：http://dali.svipenyu.cn/Article/details/gtastwknbe.html

[U32] Py：代码格式化
来源：http://dali.haohaochexian.top/Article/details/gtonzeqxdx.html

ruff format . && ruff check --fix .
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmsopwnga.html

[U33] Py：打包发布
来源：http://dali.zhiwuduotai.top/Article/details/gtbldymzqv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sufxvd.cn/Article/details/gtzrkbboug.html

[U34] Py：判断编码
来源：http://dali.vqdsnc.cn/Article/details/gtcxcfgwvj.html

chardet.detect(raw)
来源：http://dali.ydzc1.top/Article/details/gthwuqhnpd.html

[U35] Py：发送邮件
来源：http://dali.zycfv.cn/Article/details/gtwxlsttrv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yanxiufei.cn/Article/details/gtugmvtqcd.html

[U36] Py：定时任务
来源：http://dali.yueranfly.top/Article/details/gtndraqqbw.html

schedule.every(10).minutes.do(job)
来源：http://dali.yuxming.cn/Article/details/gtrpmhrqht.html

[U37] Py：读写 Excel
来源：http://dali.cashguo.top/Article/details/gtkhdbuzzq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.sweek.top/Article/details/gtyzziujpr.html

[U38] Py：获取脚本所在目录
来源：http://dali.tianlin.xyz/Article/details/gtncblyryr.html

Path(__file__).resolve().parent
来源：http://dali.gogol.net.cn/Article/details/gtkqlphfso.html

[U39] Py：判断是否在交互环境
来源：http://dali.cqqwz.cn/Article/details/gttdpcncjm.html

sys.stdout.isatty()
来源：http://dali.shzxlz.cn/Article/details/gtlmewckfo.html

[U40] Py：打印到标准错误
来源：http://dali.fzhhl.top/Article/details/gtwmngglqx.html

print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gtassdorbw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xuetiantiany.cn/Article/details/gtcnjwykxl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtfoxkbg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shzxlz.cn/Article/details/gtawgcocyo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.svipenyu.cn/Article/details/gtqsggjeog.html

[U43] PHP：声明命名空间
来源：http://dali.tianlin.xyz/Article/details/gtxtvwdais.html

namespace App\Http;
来源：http://dali.pycfn.com/Article/details/gtryuifaqg.html

[U44] PHP：开启严格类型
来源：http://dali.hnqzz.top/Article/details/gtyyteudcv.html

declare(strict_types=1);
来源：http://dali.wangshuangyany.cn/Article/details/gtrowshfdh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.316326.xyz/Article/details/gtyqnfveej.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtatszcrau.html

[U46] PHP：可空类型
来源：http://dali.yanxiufei.cn/Article/details/gtuzqujoev.html

?string $name = null
来源：http://dali.guannengcc.top/Article/details/gtqbqouepf.html

[U47] PHP：联合类型
来源：http://dali.cheryme.top/Article/details/gthjyksaxo.html

int|string $id
来源：http://dali.guowangkeji.top/Article/details/gtzbjqjlyq.html

[U48] PHP：纯枚举
来源：http://dali.wangdashe.top/Article/details/gtkfgspzix.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jlsjyb.cn/Article/details/gtyjfkmhyp.html

[U49] PHP：只读属性
来源：http://dali.hnxiangtu.top/Article/details/gtryxzttdt.html

public readonly string $name
来源：http://dali.feifeiyinyue.top/Article/details/gtunxcwbne.html

[U50] PHP：构造器属性提升
来源：http://dali.shzxlz.cn/Article/details/gtlvyoswcl.html

public function __construct(private int $id) {}
来源：http://dali.meibo888.top/Article/details/gtcpwtcbuz.html

[U51] PHP：数组解构
来源：http://dali.shangyingyoupin.top/Article/details/gtfqfppcss.html

[$a, $b] = $arr;
来源：http://dali.xuetiantiany.cn/Article/details/gtazlhrkpd.html

[U52] PHP：箭头函数
来源：http://dali.jinqigfzy.top/Article/details/gtxorgurxi.html

$double = fn($x) => $x * 2;
来源：http://dali.xylfe.cn/Article/details/gtefaqmbci.html

[U53] PHP：空合并运算符
来源：http://dali.hammf.cn/Article/details/gtsqnmsmxi.html

$v = $a ?? $b ?? "default";
来源：http://dali.tianlin.xyz/Article/details/gtkaixaqqt.html

[U54] PHP：空安全调用
来源：http://dali.dianchejie.cn/Article/details/gtdbtdvdul.html

$obj?->method()
来源：http://dali.gaohongyu789.top/Article/details/gtdnfxedyq.html

[U55] PHP：match 表达式
来源：http://dali.guowangkeji.top/Article/details/gtymrsqnzm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shangyingyoupin.top/Article/details/gtfsxwtykl.html

[U56] PHP：命名参数
来源：http://dali.meibo888.top/Article/details/gtjguuzaip.html

f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtngkhoupe.html

[U57] PHP：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtvdlcjtnh.html

"值: {$a}"
来源：http://dali.xziqi.cn/Article/details/gtkyzcsllu.html

[U58] PHP：数组三件套
来源：http://dali.chenlongwang.top/Article/details/gtmfpfafdj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmleeuync.html

[U59] PHP：自定义排序
来源：http://dali.cqqwz.cn/Article/details/gtrguqavip.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.mhx1999.top/Article/details/gtiuagdhzc.html

[U60] PHP：JSON 编解码
来源：http://dali.hfpthk.cn/Article/details/gtswtrvwwl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.9152youxi.cn/Article/details/gtkujebmiv.html

[U61] PHP：正则
来源：http://dali.jyoumei.cn/Article/details/gtfrjufxwu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.pycfn.com/Article/details/gttplgzgrr.html

[U62] PHP：日期对象
来源：http://dali.wangshuangyany.cn/Article/details/gtvzspitqm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jqgufenzy.top/Article/details/gtvlrsyslk.html

[U63] PHP：文件读写
来源：http://dali.yonumen.top/Article/details/gtrqlettwx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhixingplan.top/Article/details/gtggncdgmg.html

[U64] PHP：目录遍历
来源：http://dali.yuanzhike.top/Article/details/gtuzbdgwvf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.andypj.xyz/Article/details/gtqqervmsa.html

[U65] PHP：会话
来源：http://dali.hnxiangtu.top/Article/details/gtiuxlrolw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtslvmbtne.html

[U66] PHP：设置 Cookie
来源：http://dali.sxryk.cn/Article/details/gtvzltinzf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhoulong.xyz/Article/details/gtmhshinxd.html

[U67] PHP：处理文件上传
来源：http://dali.bjfxy.top/Article/details/gtdhirygat.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhiwuduotai.top/Article/details/gtcnhopjlo.html

[U68] PHP：PDO 连接
来源：http://dali.vqdsnc.cn/Article/details/gtwvzznolo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.daria6918.cn/Article/details/gtnjwfgnra.html

[U69] PHP：PDO 预处理
来源：http://dali.fengsongda.top/Article/details/gttfoixktr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yongpay.top/Article/details/gtvvqgbzug.html

[U70] PHP：PDO 事务
来源：http://dali.tianlin.xyz/Article/details/gtaxnkqquh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tian-w.cn/Article/details/gtpgdhkydt.html

[U71] PHP：抛出异常
来源：http://dali.xinyue.icu/Article/details/gtzkcvlzsf.html

throw new RuntimeException("失败", 500);
来源：http://dali.ydzc1.top/Article/details/gtdgmcpvxr.html

[U72] PHP：写错误日志
来源：http://dali.zhoulong.xyz/Article/details/gtxhtianov.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhiwuduotai.top/Article/details/gtemzsptdn.html

[U73] PHP：读取 ini 配置
来源：http://dali.ydzc1.top/Article/details/gtpflcgmjz.html

parse_ini_file("config.ini", true)
来源：http://dali.yj20258888.top/Article/details/gtwjrbcsaf.html

[U74] PHP：读取环境变量
来源：http://dali.pycfn.com/Article/details/gtzfkugpxc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.tanke756.top/Article/details/gtmleyoeiy.html

[U75] PHP：依赖注入
来源：http://dali.cqqwz.cn/Article/details/gtlthpdepp.html

composer require psr/container
来源：http://dali.cheryme.top/Article/details/gtwxrninxe.html

[U76] PHP：简单路由
来源：http://dali.xziqi.cn/Article/details/gtdcrmvpmd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.wangdashe.top/Article/details/gtmmdmyfir.html

[U77] PHP：模板渲染
来源：http://dali.birdmap.top/Article/details/gtwgdkngpt.html

composer require twig/twig
来源：http://dali.sxryk.cn/Article/details/gtlsaysyjw.html

[U78] PHP：单元测试
来源：http://dali.ybcxt.top/Article/details/gtorkktkze.html

composer require --dev phpunit/phpunit
来源：http://dali.vqdsnc.cn/Article/details/gtttwumtwb.html

[U79] PHP：静态分析
来源：http://dali.yangfankeji.com/Article/details/gtxdfgdmsi.html

composer require --dev phpstan/phpstan
来源：http://dali.pengpengdd.cyou/Article/details/gtawgjrhdl.html

[U80] PHP：代码规范修复
来源：http://dali.sxryk.cn/Article/details/gtxdexvrjl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cashguo.top/Article/details/gtytvmtmte.html

[U81] JS：初始化项目
来源：http://dali.guannengcc.top/Article/details/gteuxiapaf.html

npm init -y;  npm i express
来源：http://dali.jinghuilouyu.cn/Article/details/gttqsgcrje.html

[U82] JS：package.json 脚本
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnywuekn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaptfgbzw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zdqjudy.top/Article/details/gtxkujlqls.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.feifeiyinyue.top/Article/details/gtqorcpsxx.html

[U84] JS：CommonJS 写法
来源：http://dali.tianlin.xyz/Article/details/gthszicejt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.nanxinkj.top/Article/details/gtoddtzyca.html

[U85] JS：可选链
来源：http://dali.jqgufenzy.top/Article/details/gtxyugxsep.html

a?.b?.c
来源：http://dali.sufxvd.cn/Article/details/gtekrfkpyx.html

[U86] JS：空值合并
来源：http://dali.hfpthk.cn/Article/details/gtsefrnwnn.html

a ?? b
来源：http://dali.nanxinkj.top/Article/details/gtruktzhkl.html

[U87] JS：解构默认值
来源：http://dali.mhx1999.top/Article/details/gtxhyaqhtw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtpxqjlr.html

[U88] JS：对象展开合并
来源：http://dali.daxiang520.top/Article/details/gttmrgnxcj.html

{ ...a, ...b }
来源：http://dali.andypj.xyz/Article/details/gttmhbncid.html

[U89] JS：数组去重
来源：http://dali.ppjwa.cn/Article/details/gtiuiijnax.html

[...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gtrknhdpww.html

[U90] JS：数字数组排序
来源：http://dali.xuanzx.com/Article/details/gtmxoksvmo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gttioizyap.html

[U91] JS：对象键值遍历
来源：http://dali.dashuyun.cn/Article/details/gtslaidifl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zdqjudy.top/Article/details/gtkkwqhhaz.html

[U92] JS：深拷贝
来源：http://dali.ivvv.top/Article/details/gtandanqfj.html

structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtnnwrrjhw.html

[U93] JS：模板字符串
来源：http://dali.quarkkingdee.top/Article/details/gtplqtdoln.html

`共 ${n} 条`
来源：http://dali.wangdashe.top/Article/details/gtqzymosex.html

[U94] JS：箭头函数
来源：http://dali.316326.xyz/Article/details/gtquiyzgsl.html

const double = x => x * 2;
来源：http://dali.xinyue.icu/Article/details/gtsinpvrdd.html

[U95] JS：Promise 包装
来源：http://dali.guannengcc.top/Article/details/gtgtxjzxve.html

new Promise((resolve, reject) => {})
来源：http://dali.quarkkingdee.top/Article/details/gtvmjepgvo.html

[U96] JS：async/await 与异常
来源：http://dali.jinqigufen.top/Article/details/gtuiewquvu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtkcxhmyjb.html

[U97] JS：并发请求
来源：http://dali.yongpay.top/Article/details/gtobnfnetv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gtalfpjukf.html

[U98] JS：fetch 带 JSON
来源：http://dali.kuanghao11.cn/Article/details/gtidendjae.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cashguo.top/Article/details/gtvihlmmva.html

[U99] JS：事件监听
来源：http://dali.nanxinkj.top/Article/details/gtcphiyhur.html

el.addEventListener("click", e => {})
来源：http://dali.hammf.cn/Article/details/gtibjxboqo.html

[U100] JS：DOM 查询
来源：http://dali.tian-w.cn/Article/details/gtdovmxfah.html

document.querySelector(".item")
来源：http://dali.havefunace.top/Article/details/gtgvtmrpqg.html

[U101] JS：classList 操作
来源：http://dali.yvedp.cn/Article/details/gtmizxkhmc.html

el.classList.toggle("active")
来源：http://dali.ivvv.top/Article/details/gtwkprtxce.html

[U102] JS：本地存储
来源：http://dali.fengsongda.top/Article/details/gttpuogujs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cashguo.top/Article/details/gtdhqrxgug.html

[U103] JS：定时器
来源：http://dali.wangshuangyany.cn/Article/details/gtyevdgpyp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.quarkkingdee.top/Article/details/gthsxixjsa.html

[U104] JS：防抖
来源：http://dali.fzhhl.top/Article/details/gtpdikbamb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtqifmqhvo.html

[U105] JS：节流
来源：http://dali.pycfn.com/Article/details/gtvxexunrx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jlsjyb.cn/Article/details/gttexubxzf.html

[U106] JS：日期格式化
来源：http://dali.hysaishi.cn/Article/details/gtsptbqyzr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zycfv.cn/Article/details/gtvjierdlf.html

[U107] JS：数字千分位
来源：http://dali.snrcjt.cn/Article/details/gtwypjzfae.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gtohtiusub.html

[U108] JS：随机整数
来源：http://dali.dashuyun.cn/Article/details/gtnywlrjaz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hammf.cn/Article/details/gtiplmxzjo.html

[U109] JS：数组分组
来源：http://dali.snrcjt.cn/Article/details/gtkkfhmbvb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hysaishi.cn/Article/details/gtluxizgrp.html

[U110] JS：数组分块
来源：http://dali.fengsongda.top/Article/details/gtvvzkoxmj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gzhubu.top/Article/details/gtokmwgdde.html

[U111] JS：对象转 Map
来源：http://dali.guowangkeji.top/Article/details/gtqbbaecbk.html

new Map(Object.entries(obj))
来源：http://dali.zhiwuduotai.top/Article/details/gtcjlcvmzk.html

[U112] JS：字符串补位
来源：http://dali.sysykeji.top/Article/details/gtlfgckntj.html

"7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxlxzsbp.html

[U113] JS：正则替换全部
来源：http://dali.0kj1m.cn/Article/details/gtctkgxynh.html

s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtyfjnsqsa.html

[U114] JS：JSON 深比较
来源：http://dali.hnxiangtu.top/Article/details/gturnbtfzf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cdnleiting.top/Article/details/gtxgipfvdz.html

[U115] JS：生成 UUID
来源：http://dali.hongshengwenyu.top/Article/details/gtdzdhkzxn.html

crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gtvgrfrsxa.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jyoumei.cn/Article/details/gtxevrnkxn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ehwqpu.com/Article/details/gtmvyrntqp.html

[U117] JS：单元测试
来源：http://dali.bjfxy.top/Article/details/gtckknhuzj.html

npm i -D vitest;  npx vitest
来源：http://dali.daria6918.cn/Article/details/gtzmrdleev.html

[U118] JS：开发服务器
来源：http://dali.hfpthk.cn/Article/details/gttpspsxsw.html

npm i -D vite;  npx vite
来源：http://dali.aibaodan.cn/Article/details/gtbxwdaogm.html

[U119] JS：生产构建
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrkutrkc.html

npx vite build
来源：http://dali.cdnleiting.top/Article/details/gtkydhpmrt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.chenjidiqi.icu/Article/details/gtnheikxju.html

import.meta.env.VITE_API_URL
来源：http://dali.aizwys.cn/Article/details/gtsshmazfa.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtwxzizavp.html

统计汇总
来源：http://dali.kuanghao11.cn/Article/details/gtoptawugb.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gteruebjbm.html

按语言统计（条）：
来源：http://dali.gzhubu.top/Article/details/gtcizfzeoe.html

Python ......... 252
来源：http://dali.sxryk.cn/Article/details/gtivnblosi.html

PHP ............ 252
来源：http://dali.birdmap.top/Article/details/gtniupbhjw.html

JavaScript ..... 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvpcwwvp.html

TypeScript ..... 212
来源：http://dali.ppjwa.cn/Article/details/gtfgogniid.html

Java ........... 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppybvlus.html

Go ............. 212
来源：http://dali.zhongyouzk.top/Article/details/gtqefmczub.html

Ruby ........... 212
来源：http://dali.yj20258.top/Article/details/gtvrvpedsn.html

C# ............. 212
来源：http://dali.vqdsnc.cn/Article/details/gtmqjfpnjm.html

C .............. 30
来源：http://dali.yj20258.top/Article/details/gtqazclnaa.html

C++ ............ 30
来源：http://dali.cqqwz.cn/Article/details/gtjcwlvojj.html

SQL ............ 90
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfueseirk.html

Bash ........... 80
来源：http://dali.zhiwuduotai.top/Article/details/gtpgsrrlym.html

Kotlin ......... 15
来源：http://dali.yj20258888.top/Article/details/gtqcjswhlq.html

Swift .......... 15
来源：http://dali.jyoumei.cn/Article/details/gtpedgdzst.html

Lua ............ 10
来源：http://dali.xylfe.cn/Article/details/gtqwhnfaje.html

Perl ........... 10
来源：http://dali.aibaodan.cn/Article/details/gtzvlzhgaw.html

Scala .......... 10
来源：http://dali.yangfankeji.com/Article/details/gtadplupip.html

------------------------------------
来源：http://dali.nwbrower.top/Article/details/gtufqfgmtq.html

合计 ........... 2106 条
来源：http://dali.svipenyu.cn/Article/details/gtiocxusjz.html

按章节统计：
来源：http://dali.jinqigfzy.top/Article/details/gtuoplgcqy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xinyue.icu/Article/details/gtzucwiipc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigfzy.top/Article/details/gthjpaeujq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gtlrikmmbm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shangyingyoupin.top/Article/details/gtqjjaophd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yj202588.top/Article/details/gtmvzfydjg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jlsjyb.cn/Article/details/gtsgrlaqsf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jianghu66.top/Article/details/gticspuoxn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhengqikj.top/Article/details/gtgxsihbhi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gtlrtzuxof.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xylfe.cn/Article/details/gtgkjcfutn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtrqrmfgzk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtcjhussud.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gtqpvzevcr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cucudq.cn/Article/details/gtjonjajgp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.pycfn.com/Article/details/gtlcooiiwg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gtjgvqwjgs.html

Q SQL 专题                              90
来源：http://dali.sweek.top/Article/details/gtogjsuuqx.html

R Bash 专题                             80
来源：http://dali.vqdsnc.cn/Article/details/gtthfgfcmx.html

S C / C++ 专题                          60
来源：http://dali.jqgfzy.top/Article/details/gtfamaenvi.html

T 其他语言补充                          60
来源：http://dali.yueranfly.top/Article/details/gttotwxcam.html

U 高频实用片段                         120
来源：http://dali.birdmap.top/Article/details/gtbpefcxjk.html

------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gtlrdtgaab.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gtfpqsfqxt.html

--------------------------------------------------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtxbhmgqac.html

使用提醒
来源：http://dali.yuanzhike.top/Article/details/gtjwtjaezu.html

--------------------------------------------------------------------------------
来源：http://dali.smart0.xyz/Article/details/gtfpetzyid.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.wangshuangyany.cn/Article/details/gtujoiljdj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.aibaodan.cn/Article/details/gtnziyhesf.html


<!-- 参考信息 -->