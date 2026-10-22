代发 wailian999

[U05] Py：列表去重且保序
来源：http://dali.gogol.net.cn/Article/details/gt2esivznzc.html

list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gt2yseqlmxd.html

[U06] Py：合并两个字典
来源：http://dali.hnxiangtu.top/Article/details/gt2gndubrgy.html

{**a, **b}
来源：http://dali.aizwys.cn/Article/details/gt2gjyvjwmg.html

[U07] Py：反转字典键值
来源：http://dali.tianlin.xyz/Article/details/gt2aptczadi.html

{v: k for k, v in d.items()}
来源：http://dali.daria6918.cn/Article/details/gt2fhmwlksy.html

[U08] Py：展平二维列表
来源：http://dali.nanxinkj.top/Article/details/gt2qynjmocf.html

[y for x in nested for y in x]
来源：http://dali.andypj.xyz/Article/details/gt2szbxzgro.html

[U09] Py：字典取最大值的键
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hwccjyqq.html

max(d, key=d.get)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2veevupmb.html

[U10] Py：按值排序字典
来源：http://dali.jinqigufen.top/Article/details/gt2fyfaeiln.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gotoacloud.top/Article/details/gt2bctpgqqx.html

[U11] Py：生成器表达式
来源：http://dali.bjfxy.top/Article/details/gt2fhsihytf.html

(x * 2 for x in arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2axzzstmt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.quarkkingdee.top/Article/details/gt2ivbztmoo.html

Counter(arr).most_common(3)
来源：http://dali.aibaodan.cn/Article/details/gt2rwjtjehq.html

[U13] Py：固定长度队列
来源：http://dali.kuanghao11.cn/Article/details/gt2pbdojlzy.html

deque(maxlen=10)
来源：http://dali.yangfankeji.com/Article/details/gt2tgxhiwny.html

[U14] Py：分组收集到列表
来源：http://dali.fengsongda.top/Article/details/gt2jvzejmgm.html

defaultdict(list)
来源：http://dali.hammf.cn/Article/details/gt2hjjpxymc.html

[U15] Py：高精度计时
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2secapdip.html

t = time.perf_counter()
来源：http://dali.hysaishi.cn/Article/details/gt2kjsphstw.html

[U16] Py：命令行参数解析
来源：http://dali.tianlin.xyz/Article/details/gt2eeqjhmih.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xziqi.cn/Article/details/gt2ptqqrvgj.html

[U17] Py：初始化日志
来源：http://dali.jyoumei.cn/Article/details/gt2cpqutsvu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.aibaodan.cn/Article/details/gt2vnmqqaqs.html

[U18] Py：预编译正则
来源：http://dali.snrcjt.cn/Article/details/gt2iwszbbyg.html

pat = re.compile(r"\d+")
来源：http://dali.aibaodan.cn/Article/details/gt2lewcvgue.html

[U19] Py：正则替换带回调
来源：http://dali.chenlongwang.top/Article/details/gt2lnuaqsvd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hysaishi.cn/Article/details/gt2edutkybt.html

[U20] Py：缓存函数结果
来源：http://dali.sufxvd.cn/Article/details/gt2gpzgyjej.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sweek.top/Article/details/gt2fmaaiask.html

[U21] Py：自定义上下文管理器
来源：http://dali.iojbl.cn/Article/details/gt2hiddokes.html

@contextlib.contextmanager
来源：http://dali.svipenyu.cn/Article/details/gt2zkwklbdz.html

[U22] Py：矩阵转置
来源：http://dali.cucudq.cn/Article/details/gt2tddizcis.html

list(zip(*m))
来源：http://dali.sxryk.cn/Article/details/gt2mtvxgwif.html

[U23] Py：分块读取大文件
来源：http://dali.ydzc1.top/Article/details/gt2xzshstxg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhiwuduotai.top/Article/details/gt2uzihbpqw.html

[U24] Py：路径操作
来源：http://dali.316326.xyz/Article/details/gt2ahiwmkco.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gt2nfsivnnw.html

[U25] Py：CSV 按字典读
来源：http://dali.hongshengwenyu.top/Article/details/gt2hozhifgc.html

csv.DictReader(f)
来源：http://dali.yongpay.top/Article/details/gt2hsfsnqam.html

[U26] Py：并发下载
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njycpomj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.svipenyu.cn/Article/details/gt2xhijskrk.html

[U27] Py：异步 HTTP
来源：http://dali.zhongyouzk.top/Article/details/gt2ctdytssn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ydzc1.top/Article/details/gt2cpkgwokm.html

[U28] Py：类型别名
来源：http://dali.dianchejie.cn/Article/details/gt2blspfvyb.html

UserId = int
来源：http://dali.jqgufenzy.top/Article/details/gt2ndmmmmmw.html

[U29] Py：属性校验
来源：http://dali.nanxinkj.top/Article/details/gt2qsjztgmm.html

@property 与 @x.setter 配合
来源：http://dali.xziqi.cn/Article/details/gt2vcvbousg.html

[U30] Py：数据类
来源：http://dali.quarkkingdee.top/Article/details/gt2amkupeqy.html

@dataclass(slots=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rvupumyj.html

[U31] Py：单测
来源：http://dali.cheryme.top/Article/details/gt2lzcnpsjb.html

python -m pytest -q
来源：http://dali.yanxiufei.cn/Article/details/gt2fmvjzvfi.html

[U32] Py：代码格式化
来源：http://dali.jinqigfzy.top/Article/details/gt2ozbsezhm.html

ruff format . && ruff check --fix .
来源：http://dali.tanke756.top/Article/details/gt2mkmxslby.html

[U33] Py：打包发布
来源：http://dali.guowangkeji.top/Article/details/gt2wwtenxzk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.wangshuangyany.cn/Article/details/gt2bjjiamnk.html

[U34] Py：判断编码
来源：http://dali.ppjwa.cn/Article/details/gt2xrnsoywo.html

chardet.detect(raw)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ilagwppq.html

[U35] Py：发送邮件
来源：http://dali.guowangkeji.top/Article/details/gt2iqrxmfji.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.guowangkeji.top/Article/details/gt2nvwlwgsm.html

[U36] Py：定时任务
来源：http://dali.cdnleiting.top/Article/details/gt2fjihrobo.html

schedule.every(10).minutes.do(job)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqcjgzip.html

[U37] Py：读写 Excel
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kjmuyiid.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yangfankeji.com/Article/details/gt2tjsbimlv.html

[U38] Py：获取脚本所在目录
来源：http://dali.gzhubu.top/Article/details/gt2zwtujlxo.html

Path(__file__).resolve().parent
来源：http://dali.yuanzhike.top/Article/details/gt2jgoibbit.html

[U39] Py：判断是否在交互环境
来源：http://dali.cdnleiting.top/Article/details/gt2ecjajpgh.html

sys.stdout.isatty()
来源：http://dali.sysykeji.top/Article/details/gt2vdahvtwq.html

[U40] Py：打印到标准错误
来源：http://dali.guowangkeji.top/Article/details/gt2atxmpxvv.html

print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gt2hjycmuit.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yuanzhike.top/Article/details/gt2oiullvhn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2murizkbi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jyoumei.cn/Article/details/gt2sjaspvoc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yueranfly.top/Article/details/gt2bjmkzyum.html

[U43] PHP：声明命名空间
来源：http://dali.hnxiangtu.top/Article/details/gt2rcgungak.html

namespace App\Http;
来源：http://dali.bjfxy.top/Article/details/gt2rzngsypz.html

[U44] PHP：开启严格类型
来源：http://dali.yangfankeji.com/Article/details/gt2iiybjpea.html

declare(strict_types=1);
来源：http://dali.xuanzx.com/Article/details/gt2gkzggabv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.haohaochexian.top/Article/details/gt2ieseheeu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2crnsbjow.html

[U46] PHP：可空类型
来源：http://dali.guannengcc.top/Article/details/gt2hstjqxen.html

?string $name = null
来源：http://dali.fengsongda.top/Article/details/gt2dxsvgbsz.html

[U47] PHP：联合类型
来源：http://dali.yongpay.top/Article/details/gt2ezvbmdes.html

int|string $id
来源：http://dali.gogol.net.cn/Article/details/gt2splodqrp.html

[U48] PHP：纯枚举
来源：http://dali.daxiang520.top/Article/details/gt2edjyzkxf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ivvv.top/Article/details/gt2kpovgldv.html

[U49] PHP：只读属性
来源：http://dali.jqgufenzy.top/Article/details/gt2lxiessug.html

public readonly string $name
来源：http://dali.gzhubu.top/Article/details/gt2rzwgnqrg.html

[U50] PHP：构造器属性提升
来源：http://dali.cucudq.cn/Article/details/gt2stgqrywt.html

public function __construct(private int $id) {}
来源：http://dali.redwolf501.top/Article/details/gt2hhilrocv.html

[U51] PHP：数组解构
来源：http://dali.316326.xyz/Article/details/gt2sphiibjq.html

[$a, $b] = $arr;
来源：http://dali.vqdsnc.cn/Article/details/gt2psykijgs.html

[U52] PHP：箭头函数
来源：http://dali.yangfankeji.com/Article/details/gt2tzaucfvs.html

$double = fn($x) => $x * 2;
来源：http://dali.aizwys.cn/Article/details/gt2ekoqcbrs.html

[U53] PHP：空合并运算符
来源：http://dali.jyoumei.cn/Article/details/gt2fivvqjgj.html

$v = $a ?? $b ?? "default";
来源：http://dali.dashuyun.cn/Article/details/gt2wqhwvwjt.html

[U54] PHP：空安全调用
来源：http://dali.tianlin.xyz/Article/details/gt2mzamjxvt.html

$obj?->method()
来源：http://dali.daria6918.cn/Article/details/gt2wrcuutjs.html

[U55] PHP：match 表达式
来源：http://dali.nwbrower.top/Article/details/gt2fhozdrpr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jiagoushi.top/Article/details/gt2pwkdbbra.html

[U56] PHP：命名参数
来源：http://dali.xziqi.cn/Article/details/gt2lnuputbw.html

f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gt2ylacqtqy.html

[U57] PHP：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gt2rshihkue.html

"值: {$a}"
来源：http://dali.dashuyun.cn/Article/details/gt2caztnubq.html

[U58] PHP：数组三件套
来源：http://dali.xinyue.icu/Article/details/gt2hyfgiksb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hammf.cn/Article/details/gt2onkxigyo.html

[U59] PHP：自定义排序
来源：http://dali.fzhhl.top/Article/details/gt2vjfwlkeg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fdhusmau.html

[U60] PHP：JSON 编解码
来源：http://dali.ybcxt.top/Article/details/gt2gwbqrdth.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinqigufen.top/Article/details/gt2wzoheekj.html

[U61] PHP：正则
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pipjccio.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.aizwys.cn/Article/details/gt2npqujlbu.html

[U62] PHP：日期对象
来源：http://dali.hnqzz.top/Article/details/gt2tkuanrlx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.snrcjt.cn/Article/details/gt2unuvotfm.html

[U63] PHP：文件读写
来源：http://dali.ehwqpu.com/Article/details/gt2tkmdaemx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xuanzx.com/Article/details/gt2zuvqnujg.html

[U64] PHP：目录遍历
来源：http://dali.gogol.net.cn/Article/details/gt2ouqptajs.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj20258888.top/Article/details/gt2wbvcmlhy.html

[U65] PHP：会话
来源：http://dali.xuetiantiany.cn/Article/details/gt2byorbquu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xylfe.cn/Article/details/gt2ptqaaipr.html

[U66] PHP：设置 Cookie
来源：http://dali.wangdashe.top/Article/details/gt2oonbwqcp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pglmqrni.html

[U67] PHP：处理文件上传
来源：http://dali.redwolf501.top/Article/details/gt2yyksmszp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sakayxba.html

[U68] PHP：PDO 连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2csgpbrmp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.andypj.xyz/Article/details/gt2dhihxuzj.html

[U69] PHP：PDO 预处理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xsnjhsie.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xinyue.icu/Article/details/gt2vccvaedo.html

[U70] PHP：PDO 事务
来源：http://dali.shuidangran.top/Article/details/gt2ldcidxii.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.wangdashe.top/Article/details/gt2dmlwicll.html

[U71] PHP：抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2rptdsrkn.html

throw new RuntimeException("失败", 500);
来源：http://dali.hnxiangtu.top/Article/details/gt2rwmoeqdz.html

[U72] PHP：写错误日志
来源：http://dali.9152youxi.cn/Article/details/gt2jnjsugog.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cashguo.top/Article/details/gt2hssgexyj.html

[U73] PHP：读取 ini 配置
来源：http://dali.yvedp.cn/Article/details/gt2leixjoqt.html

parse_ini_file("config.ini", true)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lgubutrq.html

[U74] PHP：读取环境变量
来源：http://dali.nanxinkj.top/Article/details/gt2nuzuhsnv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xuanzx.com/Article/details/gt2attwhoez.html

[U75] PHP：依赖注入
来源：http://dali.bjfxy.top/Article/details/gt2uhqsqfao.html

composer require psr/container
来源：http://dali.redwolf501.top/Article/details/gt2fmlbrogp.html

[U76] PHP：简单路由
来源：http://dali.zycfv.cn/Article/details/gt2vqelxyxn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ikfbxlgk.html

[U77] PHP：模板渲染
来源：http://dali.xinyue.icu/Article/details/gt2srloemsb.html

composer require twig/twig
来源：http://dali.daxiang520.top/Article/details/gt2orkfnhmk.html

[U78] PHP：单元测试
来源：http://dali.wangdashe.top/Article/details/gt2tftdaqes.html

composer require --dev phpunit/phpunit
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2akrujvgt.html

[U79] PHP：静态分析
来源：http://dali.redwolf501.top/Article/details/gt2gdhuiuwb.html

composer require --dev phpstan/phpstan
来源：http://dali.haohaochexian.top/Article/details/gt2tgsqqigy.html

[U80] PHP：代码规范修复
来源：http://dali.tanke756.top/Article/details/gt2iujuuhea.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hfpthk.cn/Article/details/gt2dtwaqvgo.html

[U81] JS：初始化项目
来源：http://dali.sysykeji.top/Article/details/gt2fogqzvxu.html

npm init -y;  npm i express
来源：http://dali.fzhhl.top/Article/details/gt2hwecshzj.html

[U82] JS：package.json 脚本
来源：http://dali.c1oappe.top/Article/details/gt2vdftzrng.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.nwbrower.top/Article/details/gt2trqpkdev.html

[U83] JS：ES Module 导入导出
来源：http://dali.ybcxt.top/Article/details/gt2ulfxykhw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gt2pfvgjxql.html

[U84] JS：CommonJS 写法
来源：http://dali.yvedp.cn/Article/details/gt2mfxscqxa.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hywenlv.cn/Article/details/gt2xvwaruov.html

[U85] JS：可选链
来源：http://dali.nwbrower.top/Article/details/gt2iqcprhqm.html

a?.b?.c
来源：http://dali.hnxiangtu.top/Article/details/gt2frsajqiv.html

[U86] JS：空值合并
来源：http://dali.c1oappe.top/Article/details/gt2euehijjo.html

a ?? b
来源：http://dali.hfpthk.cn/Article/details/gt2fnywqtbj.html

[U87] JS：解构默认值
来源：http://dali.cdnleiting.top/Article/details/gt2pebwlxgy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zlayfrjg.html

[U88] JS：对象展开合并
来源：http://dali.yueranfly.top/Article/details/gt2xynputnq.html

{ ...a, ...b }
来源：http://dali.ybcxt.top/Article/details/gt2wmuehoic.html

[U89] JS：数组去重
来源：http://dali.zhoulong.xyz/Article/details/gt2cicbhjit.html

[...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gt2ibwekcyw.html

[U90] JS：数字数组排序
来源：http://dali.yj20258888.top/Article/details/gt2zocpyooh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gt2jjzyulax.html

[U91] JS：对象键值遍历
来源：http://dali.c1oappe.top/Article/details/gt2fcyxiivh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hnqzz.top/Article/details/gt2mrpacslp.html

[U92] JS：深拷贝
来源：http://dali.redwolf501.top/Article/details/gt2rvvfzebd.html

structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gt2jsciqpog.html

[U93] JS：模板字符串
来源：http://dali.yangfankeji.com/Article/details/gt2vqbflvff.html

`共 ${n} 条`
来源：http://dali.jyoumei.cn/Article/details/gt2eoddxvmt.html

[U94] JS：箭头函数
来源：http://dali.jinqigfzy.top/Article/details/gt2xgokbhyl.html

const double = x => x * 2;
来源：http://dali.jlsjyb.cn/Article/details/gt2kuvviwyc.html

[U95] JS：Promise 包装
来源：http://dali.316326.xyz/Article/details/gt2bgmrgxot.html

new Promise((resolve, reject) => {})
来源：http://dali.hammf.cn/Article/details/gt2asixqido.html

[U96] JS：async/await 与异常
来源：http://dali.jinqigufen.top/Article/details/gt2gjhdxhjk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gt2iyqltafu.html

[U97] JS：并发请求
来源：http://dali.havefunace.top/Article/details/gt2miubntqa.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gt2ndrvbdpu.html

[U98] JS：fetch 带 JSON
来源：http://dali.birdmap.top/Article/details/gt2nziryino.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.fzhhl.top/Article/details/gt2jtqtgtxk.html

[U99] JS：事件监听
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nfyfotdh.html

el.addEventListener("click", e => {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gfbyptxb.html

[U100] JS：DOM 查询
来源：http://dali.9152youxi.cn/Article/details/gt2mmwdbqqf.html

document.querySelector(".item")
来源：http://dali.yonumen.top/Article/details/gt2ipgovuhe.html

[U101] JS：classList 操作
来源：http://dali.cucudq.cn/Article/details/gt2kzqtmhkf.html

el.classList.toggle("active")
来源：http://dali.quarkkingdee.top/Article/details/gt2fqzlpxsi.html

[U102] JS：本地存储
来源：http://dali.yuanzhike.top/Article/details/gt2ihykzgru.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ybcxt.top/Article/details/gt2xkhoulnt.html

[U103] JS：定时器
来源：http://dali.sweek.top/Article/details/gt2tqwxcavo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xylfe.cn/Article/details/gt2skgyzjew.html

[U104] JS：防抖
来源：http://dali.sysykeji.top/Article/details/gt2wbptbyco.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gt2nipueins.html

[U105] JS：节流
来源：http://dali.gzhubu.top/Article/details/gt2pgmsypyh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.dashuyun.cn/Article/details/gt2nyothhem.html

[U106] JS：日期格式化
来源：http://dali.hysaishi.cn/Article/details/gt2arjppeue.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.haohaochexian.top/Article/details/gt2ymvqblku.html

[U107] JS：数字千分位
来源：http://dali.jqgfzy.top/Article/details/gt2hjdftvnr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cheryme.top/Article/details/gt2rcuyppxc.html

[U108] JS：随机整数
来源：http://dali.haohaochexian.top/Article/details/gt2ggljbdja.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.fzhhl.top/Article/details/gt2vuflbyyk.html

[U109] JS：数组分组
来源：http://dali.daxiang520.top/Article/details/gt2fvtatqnz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gt2ncwoxcko.html

[U110] JS：数组分块
来源：http://dali.birdmap.top/Article/details/gt2rtzqapzb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cheryme.top/Article/details/gt2qliuhscx.html

[U111] JS：对象转 Map
来源：http://dali.jinqigfzy.top/Article/details/gt2ggqgabqf.html

new Map(Object.entries(obj))
来源：http://dali.jianghu66.top/Article/details/gt2oshfmrfo.html

[U112] JS：字符串补位
来源：http://dali.hfpthk.cn/Article/details/gt2auhcegdb.html

"7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gt2gqrwuotd.html

[U113] JS：正则替换全部
来源：http://dali.aizwys.cn/Article/details/gt2ckjgxock.html

s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2pywixpne.html

[U114] JS：JSON 深比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2cvfxxzut.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gaohongyu789.top/Article/details/gt2skuoxyjt.html

[U115] JS：生成 UUID
来源：http://dali.hfpthk.cn/Article/details/gt2koqqsqvx.html

crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2umgtdjte.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.fzhhl.top/Article/details/gt2irxdxbuc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2wxhtdbpt.html

[U117] JS：单元测试
来源：http://dali.nanxinkj.top/Article/details/gt2pabimcix.html

npm i -D vitest;  npx vitest
来源：http://dali.mhx1999.top/Article/details/gt2qeshufsf.html

[U118] JS：开发服务器
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrnmnxkd.html

npm i -D vite;  npx vite
来源：http://dali.nwbrower.top/Article/details/gt2arpilkoz.html

[U119] JS：生产构建
来源：http://dali.yueranfly.top/Article/details/gt2bubnfdqy.html

npx vite build
来源：http://dali.ydzc1.top/Article/details/gt2chftcwbq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xziqi.cn/Article/details/gt2jugpzpqm.html

import.meta.env.VITE_API_URL
来源：http://dali.aibaodan.cn/Article/details/gt2mrklhifl.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2xsevwcxk.html

统计汇总
来源：http://dali.jlsjyb.cn/Article/details/gt2xakulzyo.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fyqztagw.html

按语言统计（条）：
来源：http://dali.chenzaomai.com/Article/details/gt2cyrojthq.html

Python ......... 252
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxwulsum.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwvrtck.html

JavaScript ..... 252
来源：http://dali.haohaochexian.top/Article/details/gt2dbohqzfw.html

TypeScript ..... 212
来源：http://dali.bjfxy.top/Article/details/gt2ekosktfr.html

Java ........... 212
来源：http://dali.hfpthk.cn/Article/details/gt2jcbusbmu.html

Go ............. 212
来源：http://dali.nanxinkj.top/Article/details/gt2vowglsgg.html

Ruby ........... 212
来源：http://dali.aizwys.cn/Article/details/gt2gsyxjtkk.html

C# ............. 212
来源：http://dali.chenjidiqi.icu/Article/details/gt2wfpmutld.html

C .............. 30
来源：http://dali.pycfn.com/Article/details/gt2fsllmqqi.html

C++ ............ 30
来源：http://dali.chenzaomai.com/Article/details/gt2fckuhgnb.html

SQL ............ 90
来源：http://dali.zhongyouzk.top/Article/details/gt2lpdnybik.html

Bash ........... 80
来源：http://dali.bjfxy.top/Article/details/gt2prvlmxbo.html

Kotlin ......... 15
来源：http://dali.birdmap.top/Article/details/gt2wbvakqja.html

Swift .......... 15
来源：http://dali.hammf.cn/Article/details/gt2fphhihsi.html

Lua ............ 10
来源：http://dali.cucudq.cn/Article/details/gt2jjdudqgf.html

Perl ........... 10
来源：http://dali.yongpay.top/Article/details/gt2nwmezbqs.html

Scala .......... 10
来源：http://dali.daria6918.cn/Article/details/gt2ysvovftw.html

------------------------------------
来源：http://dali.yj20258.top/Article/details/gt2mwpqndhu.html

合计 ........... 2106 条
来源：http://dali.yj202588.top/Article/details/gt2qxmuouym.html

按章节统计：
来源：http://dali.dianchejie.cn/Article/details/gt2bnssythk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.daria6918.cn/Article/details/gt2slcfgzjq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hnxiangtu.top/Article/details/gt2qpqrrsui.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gt2kjjmlqka.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gt2izazbgke.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shzxlz.cn/Article/details/gt2rglxeojt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.dashuyun.cn/Article/details/gt2bgxxiubh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gt2qzlmdusg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sysykeji.top/Article/details/gt2sojqumrz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gt2geuuhrqw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.tanke756.top/Article/details/gt2etobqgeo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gt2gembrrfq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gt2sxdzdymo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gt2sycbnkgo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.pengpengdd.cyou/Article/details/gt2cmlwglld.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhiwuduotai.top/Article/details/gt2ewekhahb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ucnjdlvd.html

Q SQL 专题                              90
来源：http://dali.guannengcc.top/Article/details/gt2rmhwliqe.html

R Bash 专题                             80
来源：http://dali.jinqigufen.top/Article/details/gt2gadpnurd.html

S C / C++ 专题                          60
来源：http://dali.yangfankeji.com/Article/details/gt2mbzkyygx.html

T 其他语言补充                          60
来源：http://dali.tian-w.cn/Article/details/gt2cbwqcmxh.html

U 高频实用片段                         120
来源：http://dali.nanxuanxn.top/Article/details/gt2ozhldmrc.html

------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lngomcer.html

合计                                  2106 条
来源：http://dali.hammf.cn/Article/details/gt2zezsxyqn.html

--------------------------------------------------------------------------------
来源：http://dali.yvedp.cn/Article/details/gt2bmpbnhqc.html

使用提醒
来源：http://dali.cqqwz.cn/Article/details/gt2xwgecgpf.html

--------------------------------------------------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gt2fmnzvgia.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yanxiufei.cn/Article/details/gt2wtjlnzdz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hongshengwenyu.top/Article/details/gt2ddlxbert.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.guowangkeji.top/Article/details/gt2tgrmyezb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gdvjwqyi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.guannengcc.top/Article/details/gt2rfagoqed.html

—— 文件结束 ——
来源：http://dali.bjfxy.top/Article/details/gt2xvvjgruh.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2gtbuinso.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.snrcjt.cn/Article/details/gt2djqpdraz.html

Common Programming Examples Cheat Book
来源：http://dali.sweek.top/Article/details/gt2sraixecz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2lhaybmid.html

【收录内容】
来源：http://dali.smart0.xyz/Article/details/gt2ywjjbwrc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yongpay.top/Article/details/gt2tgssculv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gogol.net.cn/Article/details/gt2vvlejppp.html

SQL · Bash · C · C++
来源：http://dali.hammf.cn/Article/details/gt2fdewqzpq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jlsjyb.cn/Article/details/gt2wxvhxllp.html

【使用说明】
来源：http://dali.shzxlz.cn/Article/details/gt2eobzcblk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.dianchejie.cn/Article/details/gt2lpkfkpnp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yangfankeji.com/Article/details/gt2fnnhogal.html


<!-- 参考信息 -->