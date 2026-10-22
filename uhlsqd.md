代发 wailian999

[U05] Py：列表去重且保序
来源：http://dali.wangshuangyany.cn/Article/details/gt2sqohnqfk.html

list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gt2ulzjcgtr.html

[U06] Py：合并两个字典
来源：http://dali.c1oappe.top/Article/details/gt2crauypep.html

{**a, **b}
来源：http://dali.zhengqikj.top/Article/details/gt2zizducqm.html

[U07] Py：反转字典键值
来源：http://dali.ehwqpu.com/Article/details/gt2ubazfcjr.html

{v: k for k, v in d.items()}
来源：http://dali.dianchejie.cn/Article/details/gt2wlamsplh.html

[U08] Py：展平二维列表
来源：http://dali.yj20258888.top/Article/details/gt2pudrewya.html

[y for x in nested for y in x]
来源：http://dali.hfpthk.cn/Article/details/gt2qpoduhso.html

[U09] Py：字典取最大值的键
来源：http://dali.shzxlz.cn/Article/details/gt2ktcstipq.html

max(d, key=d.get)
来源：http://dali.dianchejie.cn/Article/details/gt2zpykndjy.html

[U10] Py：按值排序字典
来源：http://dali.yuxming.cn/Article/details/gt2efctbmkc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigfzy.top/Article/details/gt2ahoqtdzh.html

[U11] Py：生成器表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2zqdzsgig.html

(x * 2 for x in arr)
来源：http://dali.xuanzx.com/Article/details/gt2wvhttweu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.quarkkingdee.top/Article/details/gt2pypjzpmc.html

Counter(arr).most_common(3)
来源：http://dali.xinyue.icu/Article/details/gt2fsrncgxw.html

[U13] Py：固定长度队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2xvkmqijc.html

deque(maxlen=10)
来源：http://dali.ybcxt.top/Article/details/gt2muukgolz.html

[U14] Py：分组收集到列表
来源：http://dali.sweek.top/Article/details/gt2nwgrhpho.html

defaultdict(list)
来源：http://dali.316326.xyz/Article/details/gt2gjsjyary.html

[U15] Py：高精度计时
来源：http://dali.xylfe.cn/Article/details/gt2wmeeojwe.html

t = time.perf_counter()
来源：http://dali.tianlin.xyz/Article/details/gt2iafiytqn.html

[U16] Py：命令行参数解析
来源：http://dali.cdnleiting.top/Article/details/gt2okbbdmta.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cucudq.cn/Article/details/gt2fbxlpbgu.html

[U17] Py：初始化日志
来源：http://dali.shzxlz.cn/Article/details/gt2yypbnwps.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cucudq.cn/Article/details/gt2fziiqqjo.html

[U18] Py：预编译正则
来源：http://dali.aibaodan.cn/Article/details/gt2bjxsdonu.html

pat = re.compile(r"\d+")
来源：http://dali.svipenyu.cn/Article/details/gt2lqsbjvqc.html

[U19] Py：正则替换带回调
来源：http://dali.zhixingplan.top/Article/details/gt2wmylgabe.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.guowangkeji.top/Article/details/gt2iebzfezo.html

[U20] Py：缓存函数结果
来源：http://dali.zdqjudy.top/Article/details/gt2hswzqkoy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shzxlz.cn/Article/details/gt2jgsfwauf.html

[U21] Py：自定义上下文管理器
来源：http://dali.bjfxy.top/Article/details/gt2xnrqstmw.html

@contextlib.contextmanager
来源：http://dali.cheryme.top/Article/details/gt2jfjimjsx.html

[U22] Py：矩阵转置
来源：http://dali.chenjidiqi.icu/Article/details/gt2ywvyesgo.html

list(zip(*m))
来源：http://dali.aizwys.cn/Article/details/gt2hungarix.html

[U23] Py：分块读取大文件
来源：http://dali.aizwys.cn/Article/details/gt2glcavcnr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xziqi.cn/Article/details/gt2tdlgbkou.html

[U24] Py：路径操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gjcpwlfy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gt2kzlmtcjc.html

[U25] Py：CSV 按字典读
来源：http://dali.aizwys.cn/Article/details/gt2gxrlnzco.html

csv.DictReader(f)
来源：http://dali.redwolf501.top/Article/details/gt2hhtrxbzk.html

[U26] Py：并发下载
来源：http://dali.daria6918.cn/Article/details/gt2exgbkwhv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yanxiufei.cn/Article/details/gt2xqmxqfeb.html

[U27] Py：异步 HTTP
来源：http://dali.gzhubu.top/Article/details/gt2curpejdh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yj20258.top/Article/details/gt2cscleals.html

[U28] Py：类型别名
来源：http://dali.jinqigfzy.top/Article/details/gt2itlfcdxu.html

UserId = int
来源：http://dali.xinyue.icu/Article/details/gt2vofmexog.html

[U29] Py：属性校验
来源：http://dali.cucudq.cn/Article/details/gt2nnxuufhe.html

@property 与 @x.setter 配合
来源：http://dali.jqgufenzy.top/Article/details/gt2lmqvllxc.html

[U30] Py：数据类
来源：http://dali.yj20258.top/Article/details/gt2ohytztap.html

@dataclass(slots=True)
来源：http://dali.gzhubu.top/Article/details/gt2huygchbq.html

[U31] Py：单测
来源：http://dali.hnxiangtu.top/Article/details/gt2ajqihxsq.html

python -m pytest -q
来源：http://dali.wangshuangyany.cn/Article/details/gt2mfdmglss.html

[U32] Py：代码格式化
来源：http://dali.sxryk.cn/Article/details/gt2tivacryk.html

ruff format . && ruff check --fix .
来源：http://dali.zycfv.cn/Article/details/gt2btosxlnk.html

[U33] Py：打包发布
来源：http://dali.xylfe.cn/Article/details/gt2vpplcnyi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cqqwz.cn/Article/details/gt2fzhpqrlk.html

[U34] Py：判断编码
来源：http://dali.quarkkingdee.top/Article/details/gt2obxyhfol.html

chardet.detect(raw)
来源：http://dali.zdqjudy.top/Article/details/gt2axakgemn.html

[U35] Py：发送邮件
来源：http://dali.mhx1999.top/Article/details/gt2vvnyysem.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gbwkkxua.html

[U36] Py：定时任务
来源：http://dali.dianchejie.cn/Article/details/gt2wtkihyxn.html

schedule.every(10).minutes.do(job)
来源：http://dali.cucudq.cn/Article/details/gt2piwpbnjt.html

[U37] Py：读写 Excel
来源：http://dali.snrcjt.cn/Article/details/gt2rmwsalbx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.feifeiyinyue.top/Article/details/gt2xtrqnnmm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqiurekd.html

Path(__file__).resolve().parent
来源：http://dali.jyoumei.cn/Article/details/gt2rkrrycce.html

[U39] Py：判断是否在交互环境
来源：http://dali.tian-w.cn/Article/details/gt2xdqzqkxx.html

sys.stdout.isatty()
来源：http://dali.nanxinkj.top/Article/details/gt2rbbjjfew.html

[U40] Py：打印到标准错误
来源：http://dali.yvedp.cn/Article/details/gt2krdomawl.html

print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gt2rffrqhfj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yueranfly.top/Article/details/gt2vtmpdmyj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.fzhhl.top/Article/details/gt2ejmnnbxt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.redwolf501.top/Article/details/gt2zcbllqsu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhongyouzk.top/Article/details/gt2fuwfgyrh.html

[U43] PHP：声明命名空间
来源：http://dali.jqgfzy.top/Article/details/gt2aphsisks.html

namespace App\Http;
来源：http://dali.jqgfzy.top/Article/details/gt2heufhvoj.html

[U44] PHP：开启严格类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wuxogpdf.html

declare(strict_types=1);
来源：http://dali.hfpthk.cn/Article/details/gt2milueplv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.aibaodan.cn/Article/details/gt2jqbywegl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gdzourjy.html

[U46] PHP：可空类型
来源：http://dali.jyoumei.cn/Article/details/gt2uwbnwppa.html

?string $name = null
来源：http://dali.yj20258888.top/Article/details/gt2onpztxqr.html

[U47] PHP：联合类型
来源：http://dali.jqgufenzy.top/Article/details/gt2qbiwhroq.html

int|string $id
来源：http://dali.nanxuanxn.top/Article/details/gt2flrehyxm.html

[U48] PHP：纯枚举
来源：http://dali.0kj1m.cn/Article/details/gt2rwygnmmj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2gtmaqoys.html

[U49] PHP：只读属性
来源：http://dali.mhx1999.top/Article/details/gt2vbwxlper.html

public readonly string $name
来源：http://dali.yueranfly.top/Article/details/gt2uxmnzhhb.html

[U50] PHP：构造器属性提升
来源：http://dali.9152youxi.cn/Article/details/gt2ofnvsvgx.html

public function __construct(private int $id) {}
来源：http://dali.gogol.net.cn/Article/details/gt2udsojaaz.html

[U51] PHP：数组解构
来源：http://dali.chenzaomai.com/Article/details/gt2uxjzzoty.html

[$a, $b] = $arr;
来源：http://dali.yj20258888.top/Article/details/gt2hjtweujm.html

[U52] PHP：箭头函数
来源：http://dali.havefunace.top/Article/details/gt2ljcyhdyn.html

$double = fn($x) => $x * 2;
来源：http://dali.aibaodan.cn/Article/details/gt2srklaueh.html

[U53] PHP：空合并运算符
来源：http://dali.zhixingplan.top/Article/details/gt2yiasdbnm.html

$v = $a ?? $b ?? "default";
来源：http://dali.wangshuangyany.cn/Article/details/gt2vqgjbhws.html

[U54] PHP：空安全调用
来源：http://dali.sufxvd.cn/Article/details/gt2jxrrepty.html

$obj?->method()
来源：http://dali.sufxvd.cn/Article/details/gt2vwxejyfr.html

[U55] PHP：match 表达式
来源：http://dali.aibaodan.cn/Article/details/gt2kakwmshg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhongyouzk.top/Article/details/gt2yrsxbhmc.html

[U56] PHP：命名参数
来源：http://dali.ehwqpu.com/Article/details/gt2mupintpg.html

f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ruqafuqk.html

[U57] PHP：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gt2tcacsyup.html

"值: {$a}"
来源：http://dali.jyoumei.cn/Article/details/gt2vryvcthj.html

[U58] PHP：数组三件套
来源：http://dali.hnxiangtu.top/Article/details/gt2efttmrtc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2milcmgvv.html

[U59] PHP：自定义排序
来源：http://dali.tian-w.cn/Article/details/gt2xuszazis.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xylfe.cn/Article/details/gt2xwectlzj.html

[U60] PHP：JSON 编解码
来源：http://dali.ybcxt.top/Article/details/gt2zugxwryr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.snrcjt.cn/Article/details/gt2bmsfdugw.html

[U61] PHP：正则
来源：http://dali.zhoulong.xyz/Article/details/gt2ezbblhxg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gt2jtygcove.html

[U62] PHP：日期对象
来源：http://dali.daxiang520.top/Article/details/gt2ibjzqywn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shuidangran.top/Article/details/gt2jjnczemo.html

[U63] PHP：文件读写
来源：http://dali.zhoulong.xyz/Article/details/gt2flqembhl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gogol.net.cn/Article/details/gt2vxrazxop.html

[U64] PHP：目录遍历
来源：http://dali.guowangkeji.top/Article/details/gt2okfblyrr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ivvv.top/Article/details/gt2pvzaqdbm.html

[U65] PHP：会话
来源：http://dali.hfpthk.cn/Article/details/gt2eaaxplve.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.nwbrower.top/Article/details/gt2ntrrrclx.html

[U66] PHP：设置 Cookie
来源：http://dali.ppjwa.cn/Article/details/gt2xmxevjsc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhengqikj.top/Article/details/gt2mlvypxda.html

[U67] PHP：处理文件上传
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ocjyncpc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xuetiantiany.cn/Article/details/gt2twhxnndb.html

[U68] PHP：PDO 连接
来源：http://dali.cheryme.top/Article/details/gt2imlgavjs.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenjidiqi.icu/Article/details/gt2clgzyxgf.html

[U69] PHP：PDO 预处理
来源：http://dali.daxiang520.top/Article/details/gt2qfrbsxov.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hfpthk.cn/Article/details/gt2ttccszvk.html

[U70] PHP：PDO 事务
来源：http://dali.yongpay.top/Article/details/gt2fbzsnmxo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xuanzx.com/Article/details/gt2dyqppizf.html

[U71] PHP：抛出异常
来源：http://dali.jianghu66.top/Article/details/gt2qrlqnpgq.html

throw new RuntimeException("失败", 500);
来源：http://dali.feifeiyinyue.top/Article/details/gt2shektsjz.html

[U72] PHP：写错误日志
来源：http://dali.tian-w.cn/Article/details/gt2anmlsibv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vurpzrsb.html

[U73] PHP：读取 ini 配置
来源：http://dali.fengsongda.top/Article/details/gt2rbkxmgja.html

parse_ini_file("config.ini", true)
来源：http://dali.guannengcc.top/Article/details/gt2sxeajidj.html

[U74] PHP：读取环境变量
来源：http://dali.smart0.xyz/Article/details/gt2xubszdry.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cheryme.top/Article/details/gt2spoyzgvo.html

[U75] PHP：依赖注入
来源：http://dali.tianlin.xyz/Article/details/gt2igrfifaf.html

composer require psr/container
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2drowrlrm.html

[U76] PHP：简单路由
来源：http://dali.xinyue.icu/Article/details/gt2jjqfmlfi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.quarkkingdee.top/Article/details/gt2jxzkjyuk.html

[U77] PHP：模板渲染
来源：http://dali.havefunace.top/Article/details/gt2irdattqw.html

composer require twig/twig
来源：http://dali.wangdashe.top/Article/details/gt2ipbxqtyw.html

[U78] PHP：单元测试
来源：http://dali.yonumen.top/Article/details/gt2hhlphjuz.html

composer require --dev phpunit/phpunit
来源：http://dali.yueranfly.top/Article/details/gt2wgqibesl.html

[U79] PHP：静态分析
来源：http://dali.hfpthk.cn/Article/details/gt2xrvzjtnz.html

composer require --dev phpstan/phpstan
来源：http://dali.sxryk.cn/Article/details/gt2sugnhxcx.html

[U80] PHP：代码规范修复
来源：http://dali.zhoulong.xyz/Article/details/gt2ababbzuh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.iojbl.cn/Article/details/gt2qnyjzvwd.html

[U81] JS：初始化项目
来源：http://dali.fzhhl.top/Article/details/gt2eafzrkxv.html

npm init -y;  npm i express
来源：http://dali.xziqi.cn/Article/details/gt2xtxnxqvy.html

[U82] JS：package.json 脚本
来源：http://dali.jlsjyb.cn/Article/details/gt2cnpimvyi.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lxddiwmn.html

[U83] JS：ES Module 导入导出
来源：http://dali.jqgfzy.top/Article/details/gt2yspqflxf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yuxming.cn/Article/details/gt2tvnezhlw.html

[U84] JS：CommonJS 写法
来源：http://dali.yvedp.cn/Article/details/gt2sqtgdoux.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2smlqzsbi.html

[U85] JS：可选链
来源：http://dali.tanke756.top/Article/details/gt2ejlbbhrh.html

a?.b?.c
来源：http://dali.zdqjudy.top/Article/details/gt2dyhxghbx.html

[U86] JS：空值合并
来源：http://dali.zhiwuduotai.top/Article/details/gt2ztrjvtqd.html

a ?? b
来源：http://dali.zhongyouzk.top/Article/details/gt2opkwfnbm.html

[U87] JS：解构默认值
来源：http://dali.0kj1m.cn/Article/details/gt2nbembmbd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.aizwys.cn/Article/details/gt2slovibdt.html

[U88] JS：对象展开合并
来源：http://dali.hnxiangtu.top/Article/details/gt2xbcdjoag.html

{ ...a, ...b }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rcvndevz.html

[U89] JS：数组去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjkifdob.html

[...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gt2apnydgpj.html

[U90] JS：数字数组排序
来源：http://dali.dashuyun.cn/Article/details/gt2qhmgqgkb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gt2pbmrndiz.html

[U91] JS：对象键值遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2zlalkurj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj20258888.top/Article/details/gt2ijtsvxlu.html

[U92] JS：深拷贝
来源：http://dali.ybcxt.top/Article/details/gt2vqxeodzc.html

structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gewgmons.html

[U93] JS：模板字符串
来源：http://dali.gogol.net.cn/Article/details/gt2zluvbjmo.html

`共 ${n} 条`
来源：http://dali.pengpengdd.cyou/Article/details/gt2qoiufnxj.html

[U94] JS：箭头函数
来源：http://dali.dianchejie.cn/Article/details/gt2pynyipkl.html

const double = x => x * 2;
来源：http://dali.sxryk.cn/Article/details/gt2fwovpfsy.html

[U95] JS：Promise 包装
来源：http://dali.zycfv.cn/Article/details/gt2fesaoncw.html

new Promise((resolve, reject) => {})
来源：http://dali.jyoumei.cn/Article/details/gt2akeyoabj.html

[U96] JS：async/await 与异常
来源：http://dali.redwolf501.top/Article/details/gt2cowffnqw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gt2fcihtbpu.html

[U97] JS：并发请求
来源：http://dali.haohaochexian.top/Article/details/gt2xkjqgkpk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gt2ojgervmh.html

[U98] JS：fetch 带 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gt2rhkkraiu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hfpthk.cn/Article/details/gt2lkkfmasc.html

[U99] JS：事件监听
来源：http://dali.shuidangran.top/Article/details/gt2yarrthrv.html

el.addEventListener("click", e => {})
来源：http://dali.xinyue.icu/Article/details/gt2oauqkglj.html

[U100] JS：DOM 查询
来源：http://dali.hammf.cn/Article/details/gt2kaipetro.html

document.querySelector(".item")
来源：http://dali.hnxiangtu.top/Article/details/gt2pqhxxjbu.html

[U101] JS：classList 操作
来源：http://dali.zhongyouzk.top/Article/details/gt2qdohukvc.html

el.classList.toggle("active")
来源：http://dali.jqgfzy.top/Article/details/gt2mbwmpqxz.html

[U102] JS：本地存储
来源：http://dali.chenzaomai.com/Article/details/gt2szbpltqh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yangfankeji.com/Article/details/gt2igwmfrnx.html

[U103] JS：定时器
来源：http://dali.zhoulong.xyz/Article/details/gt2vxbnswdr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.aizwys.cn/Article/details/gt2bmoidyye.html

[U104] JS：防抖
来源：http://dali.9152youxi.cn/Article/details/gt2wyejsfix.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gt2sirnbnwe.html

[U105] JS：节流
来源：http://dali.yj202588.top/Article/details/gt2fmpriedg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cqqwz.cn/Article/details/gt2mrkqqtcj.html

[U106] JS：日期格式化
来源：http://dali.gogol.net.cn/Article/details/gt2osctpkkc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenlongwang.top/Article/details/gt2itzpjtsa.html

[U107] JS：数字千分位
来源：http://dali.xuanzx.com/Article/details/gt2eemjcwxq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gt2fcueqwlz.html

[U108] JS：随机整数
来源：http://dali.ivvv.top/Article/details/gt2hmalygwi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.chenzaomai.com/Article/details/gt2prvtemcf.html

[U109] JS：数组分组
来源：http://dali.redwolf501.top/Article/details/gt2zzntiduw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gt2mrppzsgj.html

[U110] JS：数组分块
来源：http://dali.nanxuanxn.top/Article/details/gt2bkpgxfpb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xinyue.icu/Article/details/gt2grcepzii.html

[U111] JS：对象转 Map
来源：http://dali.xuetiantiany.cn/Article/details/gt2diufpths.html

new Map(Object.entries(obj))
来源：http://dali.tian-w.cn/Article/details/gt2aahqknts.html

[U112] JS：字符串补位
来源：http://dali.smart0.xyz/Article/details/gt2fmrqzfqw.html

"7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gt2nfyntqdg.html

[U113] JS：正则替换全部
来源：http://dali.jyoumei.cn/Article/details/gt2gfxduwhk.html

s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2cpqmryfo.html

[U114] JS：JSON 深比较
来源：http://dali.jinqigfzy.top/Article/details/gt2otuhhvgd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.haohaochexian.top/Article/details/gt2mwmiyedf.html

[U115] JS：生成 UUID
来源：http://dali.snrcjt.cn/Article/details/gt2zqbokkts.html

crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gt2uyczujkv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.daxiang520.top/Article/details/gt2rykcwisc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.iojbl.cn/Article/details/gt2ympszqfq.html

[U117] JS：单元测试
来源：http://dali.smart0.xyz/Article/details/gt2ipnwsjpt.html

npm i -D vitest;  npx vitest
来源：http://dali.shangyingyoupin.top/Article/details/gt2xodwkgul.html

[U118] JS：开发服务器
来源：http://dali.tianlin.xyz/Article/details/gt2eotfihka.html

npm i -D vite;  npx vite
来源：http://dali.shuidangran.top/Article/details/gt2qmdagfsh.html

[U119] JS：生产构建
来源：http://dali.jiagoushi.top/Article/details/gt2agvqnfzi.html

npx vite build
来源：http://dali.xziqi.cn/Article/details/gt2fewltmcz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.fengsongda.top/Article/details/gt2tudkrlnk.html

import.meta.env.VITE_API_URL
来源：http://dali.wangdashe.top/Article/details/gt2qqdkpifx.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2fcjjqoze.html

统计汇总
来源：http://dali.0kj1m.cn/Article/details/gt2wulwesig.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2afxfnesd.html

按语言统计（条）：
来源：http://dali.jinqigufen.top/Article/details/gt2pafqepwv.html

Python ......... 252
来源：http://dali.haohaochexian.top/Article/details/gt2slfbniir.html

PHP ............ 252
来源：http://dali.chenlongwang.top/Article/details/gt2uoidduag.html

JavaScript ..... 252
来源：http://dali.yuanzhike.top/Article/details/gt2ieoqovac.html

TypeScript ..... 212
来源：http://dali.jianghu66.top/Article/details/gt2ozjuooii.html

Java ........... 212
来源：http://dali.snrcjt.cn/Article/details/gt2akgcyysh.html

Go ............. 212
来源：http://dali.xuetiantiany.cn/Article/details/gt2kfmobmup.html

Ruby ........... 212
来源：http://dali.xziqi.cn/Article/details/gt2bczwulzz.html

C# ............. 212
来源：http://dali.zycfv.cn/Article/details/gt2rzgqfjve.html

C .............. 30
来源：http://dali.hfpthk.cn/Article/details/gt2rntnvaeg.html

C++ ............ 30
来源：http://dali.chenlongwang.top/Article/details/gt2kkzsozfu.html

SQL ............ 90
来源：http://dali.yueranfly.top/Article/details/gt2fbnwpeij.html

Bash ........... 80
来源：http://dali.chenlongwang.top/Article/details/gt2tpupesnk.html

Kotlin ......... 15
来源：http://dali.yj20258.top/Article/details/gt2ljanlzdx.html

Swift .......... 15
来源：http://dali.hongshengwenyu.top/Article/details/gt2tqecbcgd.html

Lua ............ 10
来源：http://dali.meibo888.top/Article/details/gt2tmnsudhw.html

Perl ........... 10
来源：http://dali.tianlin.xyz/Article/details/gt2ktrdxtko.html

Scala .......... 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fzcqbjvd.html

------------------------------------
来源：http://dali.daxiang520.top/Article/details/gt2llogcgfl.html

合计 ........... 2106 条
来源：http://dali.yonumen.top/Article/details/gt2plukdttg.html

按章节统计：
来源：http://dali.xinyue.icu/Article/details/gt2prroqwsd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cucudq.cn/Article/details/gt2yflyuiyl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gt2vgtepcqv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ydzc1.top/Article/details/gt2npntjkpm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.vqdsnc.cn/Article/details/gt2lzxaqznk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cdnleiting.top/Article/details/gt2xlyxqwwd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hammf.cn/Article/details/gt2xibvpxim.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tflddzes.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.dashuyun.cn/Article/details/gt2tnzpoicp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gt2gwvqdmpd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xziqi.cn/Article/details/gt2qbzmwfei.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gt2rtwawrhh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gt2ikkhendh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gt2dzevempm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cheryme.top/Article/details/gt2zvuvqucv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shuidangran.top/Article/details/gt2pdiyrymy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ofjilnzx.html

Q SQL 专题                              90
来源：http://dali.wangshuangyany.cn/Article/details/gt2mxtgyyyt.html

R Bash 专题                             80
来源：http://dali.daxiang520.top/Article/details/gt2iknsarth.html

S C / C++ 专题                          60
来源：http://dali.yuxming.cn/Article/details/gt2vimkxiba.html

T 其他语言补充                          60
来源：http://dali.gaohongyu789.top/Article/details/gt2pwwurndj.html

U 高频实用片段                         120
来源：http://dali.nanxinkj.top/Article/details/gt2hkegujly.html

------------------------------------
来源：http://dali.yj202588.top/Article/details/gt2bxxvcnse.html

合计                                  2106 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ukbltqtj.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gt2qehixouc.html

使用提醒
来源：http://dali.316326.xyz/Article/details/gt2owcqwtne.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gt2nlmxpikm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.wangshuangyany.cn/Article/details/gt2zuutxukl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwxrhoyq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.fzhhl.top/Article/details/gt2hbqjzjwd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.gotoacloud.top/Article/details/gt2ucmgsmyo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wukzwyhu.html

—— 文件结束 ——
来源：http://dali.nwbrower.top/Article/details/gt2xxasjkik.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2nyyifozw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cdnleiting.top/Article/details/gt2ldnywsbr.html

Common Programming Examples Cheat Book
来源：http://dali.cucudq.cn/Article/details/gt2gfdthzcg.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2evnfbmeq.html

【收录内容】
来源：http://dali.pycfn.com/Article/details/gt2xedsfavj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.aizwys.cn/Article/details/gt2btfssdih.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.mhx1999.top/Article/details/gt2zeritujk.html

SQL · Bash · C · C++
来源：http://dali.yanxiufei.cn/Article/details/gt2aeslvxxb.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ivvv.top/Article/details/gt2ssspsvrb.html

【使用说明】
来源：http://dali.jlsjyb.cn/Article/details/gt2hjjzulgi.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zssdauno.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jianghu66.top/Article/details/gt2cdboeysd.html


<!-- 参考信息 -->