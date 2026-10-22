代发 wailian999

[U07] Py：反转字典键值
来源：http://dali.yj202588.top/Article/details/gt2wbwerinj.html

{v: k for k, v in d.items()}
来源：http://dali.smart0.xyz/Article/details/gt2pirrjffo.html

[U08] Py：展平二维列表
来源：http://dali.hfpthk.cn/Article/details/gt2vrltkjmd.html

[y for x in nested for y in x]
来源：http://dali.xuanzx.com/Article/details/gt2ukujstho.html

[U09] Py：字典取最大值的键
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bpmpmcwg.html

max(d, key=d.get)
来源：http://dali.zdqjudy.top/Article/details/gt2mobkhqvh.html

[U10] Py：按值排序字典
来源：http://dali.tian-w.cn/Article/details/gt2lcryljkg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.iojbl.cn/Article/details/gt2isniwnpu.html

[U11] Py：生成器表达式
来源：http://dali.zycfv.cn/Article/details/gt2snlycsrm.html

(x * 2 for x in arr)
来源：http://dali.havefunace.top/Article/details/gt2nkwgmbwj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tvnwszzi.html

Counter(arr).most_common(3)
来源：http://dali.wangdashe.top/Article/details/gt2cdwldjxp.html

[U13] Py：固定长度队列
来源：http://dali.shuidangran.top/Article/details/gt2fckwncqd.html

deque(maxlen=10)
来源：http://dali.xziqi.cn/Article/details/gt2lcggceki.html

[U14] Py：分组收集到列表
来源：http://dali.jlsjyb.cn/Article/details/gt2jlomddkk.html

defaultdict(list)
来源：http://dali.chenlongwang.top/Article/details/gt2thgwpzkp.html

[U15] Py：高精度计时
来源：http://dali.yj20258.top/Article/details/gt2bmsedidf.html

t = time.perf_counter()
来源：http://dali.sxryk.cn/Article/details/gt2fgdweiro.html

[U16] Py：命令行参数解析
来源：http://dali.cheryme.top/Article/details/gt2kytfqqrh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ivvv.top/Article/details/gt2bpnnxqwi.html

[U17] Py：初始化日志
来源：http://dali.ivvv.top/Article/details/gt2xmwqugix.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhongyouzk.top/Article/details/gt2yskkwztu.html

[U18] Py：预编译正则
来源：http://dali.zhengqikj.top/Article/details/gt2rkfcikxu.html

pat = re.compile(r"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gt2utbzshca.html

[U19] Py：正则替换带回调
来源：http://dali.mhx1999.top/Article/details/gt2nilcylrx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sxryk.cn/Article/details/gt2ipxsvuuc.html

[U20] Py：缓存函数结果
来源：http://dali.andypj.xyz/Article/details/gt2lbohfgyn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhengqikj.top/Article/details/gt2xzcpshfx.html

[U21] Py：自定义上下文管理器
来源：http://dali.jqgufenzy.top/Article/details/gt2drjqzjpy.html

@contextlib.contextmanager
来源：http://dali.cheryme.top/Article/details/gt2haendeur.html

[U22] Py：矩阵转置
来源：http://dali.gogol.net.cn/Article/details/gt2jpevfvub.html

list(zip(*m))
来源：http://dali.pengpengdd.cyou/Article/details/gt2xusfygal.html

[U23] Py：分块读取大文件
来源：http://dali.chenzaomai.com/Article/details/gt2sqnejggc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sweek.top/Article/details/gt2bblpmrtb.html

[U24] Py：路径操作
来源：http://dali.aibaodan.cn/Article/details/gt2xyuecnuo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gt2ykdztplh.html

[U25] Py：CSV 按字典读
来源：http://dali.andypj.xyz/Article/details/gt2peeykisw.html

csv.DictReader(f)
来源：http://dali.andypj.xyz/Article/details/gt2eahsexlp.html

[U26] Py：并发下载
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nbkoddbo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenlongwang.top/Article/details/gt2voeqronj.html

[U27] Py：异步 HTTP
来源：http://dali.tian-w.cn/Article/details/gt2fefafnlm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yvedp.cn/Article/details/gt2dykokgws.html

[U28] Py：类型别名
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qpipbpoh.html

UserId = int
来源：http://dali.yuanzhike.top/Article/details/gt2mxgawjkc.html

[U29] Py：属性校验
来源：http://dali.jianghu66.top/Article/details/gt2jgagkhtb.html

@property 与 @x.setter 配合
来源：http://dali.aizwys.cn/Article/details/gt2nzffkqdj.html

[U30] Py：数据类
来源：http://dali.daxiang520.top/Article/details/gt2qabssmor.html

@dataclass(slots=True)
来源：http://dali.shuidangran.top/Article/details/gt2dsgunivy.html

[U31] Py：单测
来源：http://dali.yanxiufei.cn/Article/details/gt2wvilaifb.html

python -m pytest -q
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rpzfodia.html

[U32] Py：代码格式化
来源：http://dali.yj20258888.top/Article/details/gt2kqclanyi.html

ruff format . && ruff check --fix .
来源：http://dali.hammf.cn/Article/details/gt2qbhegorr.html

[U33] Py：打包发布
来源：http://dali.zhixingplan.top/Article/details/gt2oklmriiv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenjidiqi.icu/Article/details/gt2cigqanot.html

[U34] Py：判断编码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bnnnkfmu.html

chardet.detect(raw)
来源：http://dali.xuetiantiany.cn/Article/details/gt2objpmyht.html

[U35] Py：发送邮件
来源：http://dali.pycfn.com/Article/details/gt2hxxvjmxd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.aizwys.cn/Article/details/gt2qhlbgife.html

[U36] Py：定时任务
来源：http://dali.zycfv.cn/Article/details/gt2mqxzuygp.html

schedule.every(10).minutes.do(job)
来源：http://dali.fengsongda.top/Article/details/gt2ylypqaoc.html

[U37] Py：读写 Excel
来源：http://dali.yueranfly.top/Article/details/gt2hzmpdbsy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ehwqpu.com/Article/details/gt2efljvcdw.html

[U38] Py：获取脚本所在目录
来源：http://dali.aizwys.cn/Article/details/gt2euycassx.html

Path(__file__).resolve().parent
来源：http://dali.haohaochexian.top/Article/details/gt2ycazwfol.html

[U39] Py：判断是否在交互环境
来源：http://dali.yongpay.top/Article/details/gt2ybiqpfpv.html

sys.stdout.isatty()
来源：http://dali.nanxinkj.top/Article/details/gt2sspxexgd.html

[U40] Py：打印到标准错误
来源：http://dali.smart0.xyz/Article/details/gt2wargpjkz.html

print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gt2bzathfjn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.svipenyu.cn/Article/details/gt2pdmdrgdy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yangfankeji.com/Article/details/gt2yraqdzcz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eiditkbl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.kuanghao11.cn/Article/details/gt2crovwwby.html

[U43] PHP：声明命名空间
来源：http://dali.hnxiangtu.top/Article/details/gt2rnaxmwtk.html

namespace App\Http;
来源：http://dali.xinyue.icu/Article/details/gt2ahfiscxv.html

[U44] PHP：开启严格类型
来源：http://dali.hywenlv.cn/Article/details/gt2icbrrgzz.html

declare(strict_types=1);
来源：http://dali.yvedp.cn/Article/details/gt2wfjsspem.html

[U45] PHP：类型声明与返回类型
来源：http://dali.iojbl.cn/Article/details/gt2enzjcrbo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gt2mirlllgr.html

[U46] PHP：可空类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghsextef.html

?string $name = null
来源：http://dali.jinqigufen.top/Article/details/gt2pzsfuqwv.html

[U47] PHP：联合类型
来源：http://dali.zhengqikj.top/Article/details/gt2erntbfaw.html

int|string $id
来源：http://dali.yj20258.top/Article/details/gt2ykkrkdsv.html

[U48] PHP：纯枚举
来源：http://dali.yj202588.top/Article/details/gt2slsvuidz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sweek.top/Article/details/gt2knewindh.html

[U49] PHP：只读属性
来源：http://dali.xylfe.cn/Article/details/gt2tixoydnr.html

public readonly string $name
来源：http://dali.gaohongyu789.top/Article/details/gt2lzrakqwh.html

[U50] PHP：构造器属性提升
来源：http://dali.nanxuanxn.top/Article/details/gt2htbqairr.html

public function __construct(private int $id) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2tgokvhgm.html

[U51] PHP：数组解构
来源：http://dali.hnxiangtu.top/Article/details/gt2eunyieei.html

[$a, $b] = $arr;
来源：http://dali.ppjwa.cn/Article/details/gt2ewfoxmxh.html

[U52] PHP：箭头函数
来源：http://dali.jlsjyb.cn/Article/details/gt2hxmtphtn.html

$double = fn($x) => $x * 2;
来源：http://dali.guowangkeji.top/Article/details/gt2tvbgzqhg.html

[U53] PHP：空合并运算符
来源：http://dali.gogol.net.cn/Article/details/gt2cwtqhcih.html

$v = $a ?? $b ?? "default";
来源：http://dali.ehwqpu.com/Article/details/gt2gsrxtotr.html

[U54] PHP：空安全调用
来源：http://dali.zdqjudy.top/Article/details/gt2fmpllzjr.html

$obj?->method()
来源：http://dali.sweek.top/Article/details/gt2gboikqvj.html

[U55] PHP：match 表达式
来源：http://dali.haohaochexian.top/Article/details/gt2xhpdmnxv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jlsjyb.cn/Article/details/gt2ffanbhrq.html

[U56] PHP：命名参数
来源：http://dali.yongpay.top/Article/details/gt2uowyadpd.html

f(a: 1, b: 2)
来源：http://dali.shzxlz.cn/Article/details/gt2azfbquqn.html

[U57] PHP：字符串插值
来源：http://dali.aizwys.cn/Article/details/gt2myoufxca.html

"值: {$a}"
来源：http://dali.sufxvd.cn/Article/details/gt2chypsrpl.html

[U58] PHP：数组三件套
来源：http://dali.nanxinkj.top/Article/details/gt2mkysmluj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ehwqpu.com/Article/details/gt2uzwifbgj.html

[U59] PHP：自定义排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2poxaxbro.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.snrcjt.cn/Article/details/gt2vcmrxjgf.html

[U60] PHP：JSON 编解码
来源：http://dali.zdqjudy.top/Article/details/gt2jmegulah.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ehwqpu.com/Article/details/gt2ldsjpype.html

[U61] PHP：正则
来源：http://dali.zycfv.cn/Article/details/gt2hvsdrazr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yonumen.top/Article/details/gt2inotfrdu.html

[U62] PHP：日期对象
来源：http://dali.hfpthk.cn/Article/details/gt2awixfzdx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cheryme.top/Article/details/gt2donwgrsm.html

[U63] PHP：文件读写
来源：http://dali.zhengqikj.top/Article/details/gt2mntkdpoa.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhongyouzk.top/Article/details/gt2uskcgldd.html

[U64] PHP：目录遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2jlqgsjxp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.svipenyu.cn/Article/details/gt2fhwwknat.html

[U65] PHP：会话
来源：http://dali.cheryme.top/Article/details/gt2mutnzmri.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.tanke756.top/Article/details/gt2ribkzenn.html

[U66] PHP：设置 Cookie
来源：http://dali.meibo888.top/Article/details/gt2yytrujha.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jiagoushi.top/Article/details/gt2ycroduzm.html

[U67] PHP：处理文件上传
来源：http://dali.ybcxt.top/Article/details/gt2gnmyuzwh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yj20258.top/Article/details/gt2dvtdcjtx.html

[U68] PHP：PDO 连接
来源：http://dali.hywenlv.cn/Article/details/gt2rhndupzh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.birdmap.top/Article/details/gt2pffxsnbp.html

[U69] PHP：PDO 预处理
来源：http://dali.yuxming.cn/Article/details/gt2gvivmjqw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sysykeji.top/Article/details/gt2afrbniov.html

[U70] PHP：PDO 事务
来源：http://dali.gaohongyu789.top/Article/details/gt2bfycntfu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hongshengwenyu.top/Article/details/gt2meqprspv.html

[U71] PHP：抛出异常
来源：http://dali.jyoumei.cn/Article/details/gt2sszuobcd.html

throw new RuntimeException("失败", 500);
来源：http://dali.shuidangran.top/Article/details/gt2tuetbtil.html

[U72] PHP：写错误日志
来源：http://dali.dianchejie.cn/Article/details/gt2hblrtizq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinqigfzy.top/Article/details/gt2ereixxtp.html

[U73] PHP：读取 ini 配置
来源：http://dali.hywenlv.cn/Article/details/gt2vnxqutwf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2wopuhwfz.html

[U74] PHP：读取环境变量
来源：http://dali.zdqjudy.top/Article/details/gt2plkgwmlx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hywenlv.cn/Article/details/gt2yypxdkgh.html

[U75] PHP：依赖注入
来源：http://dali.nanxinkj.top/Article/details/gt2sodnuxmp.html

composer require psr/container
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cymefltd.html

[U76] PHP：简单路由
来源：http://dali.yj20258.top/Article/details/gt2ycskgrjx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhengqikj.top/Article/details/gt2epjmmoon.html

[U77] PHP：模板渲染
来源：http://dali.daria6918.cn/Article/details/gt2iudvmlqw.html

composer require twig/twig
来源：http://dali.hfpthk.cn/Article/details/gt2uljquocu.html

[U78] PHP：单元测试
来源：http://dali.nanxuanxn.top/Article/details/gt2achhtixw.html

composer require --dev phpunit/phpunit
来源：http://dali.xylfe.cn/Article/details/gt2mygskpxc.html

[U79] PHP：静态分析
来源：http://dali.zdqjudy.top/Article/details/gt2blawgjyq.html

composer require --dev phpstan/phpstan
来源：http://dali.birdmap.top/Article/details/gt2mpmdzwuk.html

[U80] PHP：代码规范修复
来源：http://dali.yongpay.top/Article/details/gt2pyuxfsya.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.tianlin.xyz/Article/details/gt2ynjxyiue.html

[U81] JS：初始化项目
来源：http://dali.aibaodan.cn/Article/details/gt2pmrkjiko.html

npm init -y;  npm i express
来源：http://dali.daria6918.cn/Article/details/gt2sfsmrgov.html

[U82] JS：package.json 脚本
来源：http://dali.haohaochexian.top/Article/details/gt2qbmgllgq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.0kj1m.cn/Article/details/gt2vtfxiytg.html

[U83] JS：ES Module 导入导出
来源：http://dali.birdmap.top/Article/details/gt2mrryicoq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jqgufenzy.top/Article/details/gt2vtksxchc.html

[U84] JS：CommonJS 写法
来源：http://dali.nwbrower.top/Article/details/gt2qkunwtep.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.pengpengdd.cyou/Article/details/gt2fhugfhah.html

[U85] JS：可选链
来源：http://dali.hysaishi.cn/Article/details/gt2sjulcqvj.html

a?.b?.c
来源：http://dali.bjfxy.top/Article/details/gt2tpehmifx.html

[U86] JS：空值合并
来源：http://dali.ivvv.top/Article/details/gt2merfqhme.html

a ?? b
来源：http://dali.zhoulong.xyz/Article/details/gt2axbwrxve.html

[U87] JS：解构默认值
来源：http://dali.yuanzhike.top/Article/details/gt2vmqqpmea.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yvedp.cn/Article/details/gt2qltngjyb.html

[U88] JS：对象展开合并
来源：http://dali.kuanghao11.cn/Article/details/gt2arhnjrmt.html

{ ...a, ...b }
来源：http://dali.hywenlv.cn/Article/details/gt2aavhxiba.html

[U89] JS：数组去重
来源：http://dali.yongpay.top/Article/details/gt2tcvaleiy.html

[...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gt2xlhmcakr.html

[U90] JS：数字数组排序
来源：http://dali.guowangkeji.top/Article/details/gt2tlnismzi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gt2dymdxdgf.html

[U91] JS：对象键值遍历
来源：http://dali.jqgfzy.top/Article/details/gt2balhiffy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sxryk.cn/Article/details/gt2zfckhxmm.html

[U92] JS：深拷贝
来源：http://dali.zycfv.cn/Article/details/gt2gsvjekqg.html

structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uhrekfda.html

[U93] JS：模板字符串
来源：http://dali.pycfn.com/Article/details/gt2rpcnxmqe.html

`共 ${n} 条`
来源：http://dali.ydzc1.top/Article/details/gt2vuuaweva.html

[U94] JS：箭头函数
来源：http://dali.snrcjt.cn/Article/details/gt2cthscaqs.html

const double = x => x * 2;
来源：http://dali.nwbrower.top/Article/details/gt2qcyaqrgf.html

[U95] JS：Promise 包装
来源：http://dali.fengsongda.top/Article/details/gt2lwuumsjp.html

new Promise((resolve, reject) => {})
来源：http://dali.chenjidiqi.icu/Article/details/gt2kxlzzwpe.html

[U96] JS：async/await 与异常
来源：http://dali.jiagoushi.top/Article/details/gt2pwwvncol.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gt2tpbfijax.html

[U97] JS：并发请求
来源：http://dali.tian-w.cn/Article/details/gt2eewfcvil.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gt2bawhnvxi.html

[U98] JS：fetch 带 JSON
来源：http://dali.yangfankeji.com/Article/details/gt2ygpnixvm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.tianlin.xyz/Article/details/gt2nxnvatwu.html

[U99] JS：事件监听
来源：http://dali.jqgfzy.top/Article/details/gt2bacjjljy.html

el.addEventListener("click", e => {})
来源：http://dali.zdqjudy.top/Article/details/gt2tyepuuot.html

[U100] JS：DOM 查询
来源：http://dali.fengsongda.top/Article/details/gt2rzaquvjf.html

document.querySelector(".item")
来源：http://dali.vqdsnc.cn/Article/details/gt2igyrnaqx.html

[U101] JS：classList 操作
来源：http://dali.jinqigfzy.top/Article/details/gt2gbqmmpcd.html

el.classList.toggle("active")
来源：http://dali.hfpthk.cn/Article/details/gt2xcjcbytg.html

[U102] JS：本地存储
来源：http://dali.xziqi.cn/Article/details/gt2pjdeounx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.daxiang520.top/Article/details/gt2vmhxislj.html

[U103] JS：定时器
来源：http://dali.cucudq.cn/Article/details/gt2pxyhgzet.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.snrcjt.cn/Article/details/gt2rhibnspr.html

[U104] JS：防抖
来源：http://dali.kuanghao11.cn/Article/details/gt2jjcwcohh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gt2jrbargur.html

[U105] JS：节流
来源：http://dali.nanxinkj.top/Article/details/gt2ckiuijmw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bqlemsvl.html

[U106] JS：日期格式化
来源：http://dali.cqqwz.cn/Article/details/gt2oznvdouy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gotoacloud.top/Article/details/gt2mwdsjfwb.html

[U107] JS：数字千分位
来源：http://dali.jyoumei.cn/Article/details/gt2blcogffd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sffwxmhh.html

[U108] JS：随机整数
来源：http://dali.wangdashe.top/Article/details/gt2lidtuxxx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xuanzx.com/Article/details/gt2lwuvaijk.html

[U109] JS：数组分组
来源：http://dali.redwolf501.top/Article/details/gt2qtlswnbe.html

Object.groupBy(arr, x => x.type)
来源：http://dali.9152youxi.cn/Article/details/gt2sedkgrtb.html

[U110] JS：数组分块
来源：http://dali.snrcjt.cn/Article/details/gt2rzlpugcs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yonumen.top/Article/details/gt2elkpkkdo.html

[U111] JS：对象转 Map
来源：http://dali.zdqjudy.top/Article/details/gt2uvznywwc.html

new Map(Object.entries(obj))
来源：http://dali.yj20258.top/Article/details/gt2nxhzbbpb.html

[U112] JS：字符串补位
来源：http://dali.pengpengdd.cyou/Article/details/gt2xnuewlxb.html

"7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gt2sljrlfek.html

[U113] JS：正则替换全部
来源：http://dali.feifeiyinyue.top/Article/details/gt2uhaznfjj.html

s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2cretkxry.html

[U114] JS：JSON 深比较
来源：http://dali.cashguo.top/Article/details/gt2pbdhrjyv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gt2zjdjcdur.html

[U115] JS：生成 UUID
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mquxefzv.html

crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gt2ygumekbo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yueranfly.top/Article/details/gt2qidccynq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cheryme.top/Article/details/gt2klxrfolf.html

[U117] JS：单元测试
来源：http://dali.aizwys.cn/Article/details/gt2kdtwenwy.html

npm i -D vitest;  npx vitest
来源：http://dali.yj20258.top/Article/details/gt2wqmlvesz.html

[U118] JS：开发服务器
来源：http://dali.9152youxi.cn/Article/details/gt2dvorjrve.html

npm i -D vite;  npx vite
来源：http://dali.guannengcc.top/Article/details/gt2ulkofqod.html

[U119] JS：生产构建
来源：http://dali.hammf.cn/Article/details/gt2nlxhhgmw.html

npx vite build
来源：http://dali.hysaishi.cn/Article/details/gt2mvxgsktl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yonumen.top/Article/details/gt2bymfizmo.html

import.meta.env.VITE_API_URL
来源：http://dali.andypj.xyz/Article/details/gt2zticuqkm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2lfaulbku.html

统计汇总
来源：http://dali.chenjidiqi.icu/Article/details/gt2qhrxdkbs.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qojdqdrc.html

按语言统计（条）：
来源：http://dali.svipenyu.cn/Article/details/gt2srfqpauc.html

Python ......... 252
来源：http://dali.zycfv.cn/Article/details/gt2tiukwdep.html

PHP ............ 252
来源：http://dali.ydzc1.top/Article/details/gt2jlczhdvq.html

JavaScript ..... 252
来源：http://dali.jyoumei.cn/Article/details/gt2ixiraoxy.html

TypeScript ..... 212
来源：http://dali.9152youxi.cn/Article/details/gt2ihyakrsn.html

Java ........... 212
来源：http://dali.haohaochexian.top/Article/details/gt2bztlesgs.html

Go ............. 212
来源：http://dali.sufxvd.cn/Article/details/gt2deazybyu.html

Ruby ........... 212
来源：http://dali.daria6918.cn/Article/details/gt2nzhqntfa.html

C# ............. 212
来源：http://dali.yvedp.cn/Article/details/gt2tuqpzfbp.html

C .............. 30
来源：http://dali.quarkkingdee.top/Article/details/gt2fylaqbco.html

C++ ............ 30
来源：http://dali.nanxinkj.top/Article/details/gt2omnfzrxe.html

SQL ............ 90
来源：http://dali.c1oappe.top/Article/details/gt2qoudmtpb.html

Bash ........... 80
来源：http://dali.aizwys.cn/Article/details/gt2honjpmup.html

Kotlin ......... 15
来源：http://dali.xuanzx.com/Article/details/gt2whshixxm.html

Swift .......... 15
来源：http://dali.zhixingplan.top/Article/details/gt2kyufxkld.html

Lua ............ 10
来源：http://dali.hnxiangtu.top/Article/details/gt2cdilftdw.html

Perl ........... 10
来源：http://dali.pycfn.com/Article/details/gt2pgueesho.html

Scala .......... 10
来源：http://dali.dianchejie.cn/Article/details/gt2jjswbgmd.html

------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gt2mxrriihv.html

合计 ........... 2106 条
来源：http://dali.shuidangran.top/Article/details/gt2cqjxwlnr.html

按章节统计：
来源：http://dali.sweek.top/Article/details/gt2lfxxqiwe.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hysaishi.cn/Article/details/gt2eehroegm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cheryme.top/Article/details/gt2xtqlulvf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yongpay.top/Article/details/gt2kpgpycmd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nanxuanxn.top/Article/details/gt2ytfpmvsb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.tian-w.cn/Article/details/gt2nruiepqz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.daxiang520.top/Article/details/gt2icapoxdn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ybcxt.top/Article/details/gt2wuvyeyvz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.tian-w.cn/Article/details/gt2wkfvkgzt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gt2uiroqoto.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sxryk.cn/Article/details/gt2tqqilrsq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gt2pjhgseck.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gt2mrzmmpft.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gt2lwzxzmur.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.316326.xyz/Article/details/gt2zvgbamog.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.smart0.xyz/Article/details/gt2jiwytiyt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gt2qnckfjop.html

Q SQL 专题                              90
来源：http://dali.gaohongyu789.top/Article/details/gt2qoncbzkh.html

R Bash 专题                             80
来源：http://dali.haohaochexian.top/Article/details/gt2mqljeknr.html

S C / C++ 专题                          60
来源：http://dali.yangfankeji.com/Article/details/gt2luewfeog.html

T 其他语言补充                          60
来源：http://dali.meibo888.top/Article/details/gt2xiudqbdo.html

U 高频实用片段                         120
来源：http://dali.yvedp.cn/Article/details/gt2qbuxdshq.html

------------------------------------
来源：http://dali.birdmap.top/Article/details/gt2deyiwmtk.html

合计                                  2106 条
来源：http://dali.tanke756.top/Article/details/gt2rymmlqor.html

--------------------------------------------------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gt2sznmggvn.html

使用提醒
来源：http://dali.jqgufenzy.top/Article/details/gt2fxagzmfe.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gt2tygfnjus.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhixingplan.top/Article/details/gt2tlopcnpm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ybcxt.top/Article/details/gt2uijogfni.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.fengsongda.top/Article/details/gt2gayxyatp.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ybcxt.top/Article/details/gt2sddionsa.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.fengsongda.top/Article/details/gt2kslojgeg.html

—— 文件结束 ——
来源：http://dali.tian-w.cn/Article/details/gt2izpncsbu.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2efoxlzfk.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hongshengwenyu.top/Article/details/gt2zznmbzhv.html

Common Programming Examples Cheat Book
来源：http://dali.tanke756.top/Article/details/gt2pfcvdcrh.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ckbrtkgj.html

【收录内容】
来源：http://dali.yonumen.top/Article/details/gt2fbpfecqw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hywenlv.cn/Article/details/gt2tjrxoeuv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.nanxinkj.top/Article/details/gt2gpfoiqmh.html

SQL · Bash · C · C++
来源：http://dali.ehwqpu.com/Article/details/gt2kvqhlgcg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sufxvd.cn/Article/details/gt2cxwbkavg.html

【使用说明】
来源：http://dali.daria6918.cn/Article/details/gt2bavudwzd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xuetiantiany.cn/Article/details/gt2kekunotw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.redwolf501.top/Article/details/gt2tefkvqsa.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.dashuyun.cn/Article/details/gt2dobkbjqi.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.pengpengdd.cyou/Article/details/gt2hpuiyovk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.nwbrower.top/Article/details/gt2rofamojr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xylfe.cn/Article/details/gt2kuieigfw.html


<!-- 参考信息 -->