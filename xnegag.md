代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgwnhgkq.html

[T59] Scala：循环
来源：http://dali.yongpay.top/Article/details/gtclzzesil.html

for (i <- 1 to 10) println(i)
来源：http://dali.nwbrower.top/Article/details/gtpqdcxktl.html

[T60] Scala：折叠
来源：http://dali.ehwqpu.com/Article/details/gtduuvtffu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuetiantiany.cn/Article/details/gtxuhjxtpi.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtshnrkkwr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gogol.net.cn/Article/details/gtbxuxefye.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtpntbykwy.html

[U01] Py：创建虚拟环境
来源：http://dali.hysaishi.cn/Article/details/gtjkntgwtk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tian-w.cn/Article/details/gtxjsneczt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.vqdsnc.cn/Article/details/gtdlxiwljq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhengqikj.top/Article/details/gteohpqctg.html

[U03] Py：加载 .env 配置
来源：http://dali.svipenyu.cn/Article/details/gtxpknrqaf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuxming.cn/Article/details/gtovsdjtxj.html

[U04] Py：变量调试打印
来源：http://dali.zhongyouzk.top/Article/details/gthkkmpmbr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xylfe.cn/Article/details/gturyfxomx.html

[U05] Py：列表去重且保序
来源：http://dali.wangshuangyany.cn/Article/details/gtkrxhvmkk.html

list(dict.fromkeys(arr))
来源：http://dali.zycfv.cn/Article/details/gtlnfzyhef.html

[U06] Py：合并两个字典
来源：http://dali.jyoumei.cn/Article/details/gtbilsloxa.html

{**a, **b}
来源：http://dali.smart0.xyz/Article/details/gtwsoijyjb.html

[U07] Py：反转字典键值
来源：http://dali.ivvv.top/Article/details/gtphiidszr.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifjgmjde.html

[U08] Py：展平二维列表
来源：http://dali.snrcjt.cn/Article/details/gtrcjhpama.html

[y for x in nested for y in x]
来源：http://dali.birdmap.top/Article/details/gtmvbrmtlu.html

[U09] Py：字典取最大值的键
来源：http://dali.snrcjt.cn/Article/details/gtkauqnnvi.html

max(d, key=d.get)
来源：http://dali.xylfe.cn/Article/details/gtnpyrwvna.html

[U10] Py：按值排序字典
来源：http://dali.haohaochexian.top/Article/details/gtlwvjtpvx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.andypj.xyz/Article/details/gtiqxhhhji.html

[U11] Py：生成器表达式
来源：http://dali.mhx1999.top/Article/details/gthhiervha.html

(x * 2 for x in arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtqtyfgfbi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yuanzhike.top/Article/details/gtctbxvfgp.html

Counter(arr).most_common(3)
来源：http://dali.bjfxy.top/Article/details/gtrsbayept.html

[U13] Py：固定长度队列
来源：http://dali.fzhhl.top/Article/details/gtjnwducxu.html

deque(maxlen=10)
来源：http://dali.gotoacloud.top/Article/details/gtazsoqqkv.html

[U14] Py：分组收集到列表
来源：http://dali.feifeiyinyue.top/Article/details/gtpkehtrjy.html

defaultdict(list)
来源：http://dali.xuanzx.com/Article/details/gtaxxwirvr.html

[U15] Py：高精度计时
来源：http://dali.jinqigufen.top/Article/details/gtcljdhidk.html

t = time.perf_counter()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwskhovvh.html

[U16] Py：命令行参数解析
来源：http://dali.hywenlv.cn/Article/details/gtuledsrbf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aizwys.cn/Article/details/gtgeqrrihx.html

[U17] Py：初始化日志
来源：http://dali.svipenyu.cn/Article/details/gtvimxmakl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yuanzhike.top/Article/details/gtxpyqlhwq.html

[U18] Py：预编译正则
来源：http://dali.birdmap.top/Article/details/gtvojqqblc.html

pat = re.compile(r"\d+")
来源：http://dali.daxiang520.top/Article/details/gteoqmpwhg.html

[U19] Py：正则替换带回调
来源：http://dali.shanyushiyangtech.top/Article/details/gtivvaiefb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.haohaochexian.top/Article/details/gtibfkcyqt.html

[U20] Py：缓存函数结果
来源：http://dali.pycfn.com/Article/details/gtnnnleqjr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yuxming.cn/Article/details/gtyqptustp.html

[U21] Py：自定义上下文管理器
来源：http://dali.fengsongda.top/Article/details/gtkeyixasd.html

@contextlib.contextmanager
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhxhydfz.html

[U22] Py：矩阵转置
来源：http://dali.aizwys.cn/Article/details/gtofcgajnm.html

list(zip(*m))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqhsxqoc.html

[U23] Py：分块读取大文件
来源：http://dali.zhiwuduotai.top/Article/details/gtcczvdtnc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tian-w.cn/Article/details/gtwhzdjodb.html

[U24] Py：路径操作
来源：http://dali.mhx1999.top/Article/details/gtnfgxmpua.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gtkydxywta.html

[U25] Py：CSV 按字典读
来源：http://dali.sufxvd.cn/Article/details/gtzjgnldir.html

csv.DictReader(f)
来源：http://dali.cdnleiting.top/Article/details/gtxrarvklk.html

[U26] Py：并发下载
来源：http://dali.fzhhl.top/Article/details/gtvuunukwn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hongshengwenyu.top/Article/details/gtsobrcwme.html

[U27] Py：异步 HTTP
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzbzdoiu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ydzc1.top/Article/details/gtmqpidlsh.html

[U28] Py：类型别名
来源：http://dali.cdnleiting.top/Article/details/gtxopcigrg.html

UserId = int
来源：http://dali.9152youxi.cn/Article/details/gtxhfzwait.html

[U29] Py：属性校验
来源：http://dali.316326.xyz/Article/details/gtglwnvrkh.html

@property 与 @x.setter 配合
来源：http://dali.cqqwz.cn/Article/details/gtspxrksnt.html

[U30] Py：数据类
来源：http://dali.9152youxi.cn/Article/details/gtijtrangc.html

@dataclass(slots=True)
来源：http://dali.xuanzx.com/Article/details/gthdlyvrmt.html

[U31] Py：单测
来源：http://dali.cdnleiting.top/Article/details/gtiffjtxui.html

python -m pytest -q
来源：http://dali.cdnleiting.top/Article/details/gtcuozgcnt.html

[U32] Py：代码格式化
来源：http://dali.iojbl.cn/Article/details/gttljxqfrq.html

ruff format . && ruff check --fix .
来源：http://dali.xuanzx.com/Article/details/gtlmfpelkx.html

[U33] Py：打包发布
来源：http://dali.gzhubu.top/Article/details/gtlvmkutmp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.dashuyun.cn/Article/details/gtihgmqbtg.html

[U34] Py：判断编码
来源：http://dali.yj20258888.top/Article/details/gtqhowaoop.html

chardet.detect(raw)
来源：http://dali.xylfe.cn/Article/details/gtpbfkyqol.html

[U35] Py：发送邮件
来源：http://dali.pycfn.com/Article/details/gtvmxhiqti.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cheryme.top/Article/details/gtwjoxqdjj.html

[U36] Py：定时任务
来源：http://dali.ehwqpu.com/Article/details/gteqyicjrw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhoulong.xyz/Article/details/gtrcuobxaz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gtajkjfbiz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tianlin.xyz/Article/details/gtyxgvnktf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyeiimrvz.html

Path(__file__).resolve().parent
来源：http://dali.ydzc1.top/Article/details/gtncxetxol.html

[U39] Py：判断是否在交互环境
来源：http://dali.zdqjudy.top/Article/details/gtdujyzjab.html

sys.stdout.isatty()
来源：http://dali.feifeiyinyue.top/Article/details/gtrjkxodxt.html

[U40] Py：打印到标准错误
来源：http://dali.c1oappe.top/Article/details/gtuwnokekl.html

print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gtpuojmalh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hammf.cn/Article/details/gthbhsseqq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.daxiang520.top/Article/details/gtzgmrposz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.meibo888.top/Article/details/gtwezsguag.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.316326.xyz/Article/details/gtoeipgjdw.html

[U43] PHP：声明命名空间
来源：http://dali.gaohongyu789.top/Article/details/gtoagdpebi.html

namespace App\Http;
来源：http://dali.yuxming.cn/Article/details/gtjtyxmdsz.html

[U44] PHP：开启严格类型
来源：http://dali.pycfn.com/Article/details/gtumtswvwf.html

declare(strict_types=1);
来源：http://dali.cdnleiting.top/Article/details/gtxhacnors.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopdvgrwz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gtusppfkdu.html

[U46] PHP：可空类型
来源：http://dali.meibo888.top/Article/details/gtztvomuqh.html

?string $name = null
来源：http://dali.xziqi.cn/Article/details/gtukabzrmh.html

[U47] PHP：联合类型
来源：http://dali.yuxming.cn/Article/details/gtrldiphdr.html

int|string $id
来源：http://dali.fengsongda.top/Article/details/gtyvcfcrtu.html

[U48] PHP：纯枚举
来源：http://dali.yanxiufei.cn/Article/details/gtiplfaacy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvmcmhxb.html

[U49] PHP：只读属性
来源：http://dali.xuetiantiany.cn/Article/details/gtclgpfgxf.html

public readonly string $name
来源：http://dali.dashuyun.cn/Article/details/gtwnipnsrk.html

[U50] PHP：构造器属性提升
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwurzovb.html

public function __construct(private int $id) {}
来源：http://dali.tanke756.top/Article/details/gttrnzgzpq.html

[U51] PHP：数组解构
来源：http://dali.zhengqikj.top/Article/details/gtvnymealw.html

[$a, $b] = $arr;
来源：http://dali.xuanzx.com/Article/details/gtwsiytbxj.html

[U52] PHP：箭头函数
来源：http://dali.snrcjt.cn/Article/details/gtzgzhohjl.html

$double = fn($x) => $x * 2;
来源：http://dali.yuxming.cn/Article/details/gthopxqvhe.html

[U53] PHP：空合并运算符
来源：http://dali.jqgfzy.top/Article/details/gtrarpqbbp.html

$v = $a ?? $b ?? "default";
来源：http://dali.aibaodan.cn/Article/details/gtbkeqobim.html

[U54] PHP：空安全调用
来源：http://dali.nanxinkj.top/Article/details/gtkygffavo.html

$obj?->method()
来源：http://dali.yj20258888.top/Article/details/gtgfdcjzgc.html

[U55] PHP：match 表达式
来源：http://dali.haohaochexian.top/Article/details/gtlqwyibpj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinqigufen.top/Article/details/gtgxfozdjm.html

[U56] PHP：命名参数
来源：http://dali.jinqigfzy.top/Article/details/gtygdecanc.html

f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtpifnocat.html

[U57] PHP：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtylsoieyz.html

"值: {$a}"
来源：http://dali.wangdashe.top/Article/details/gtkandcyld.html

[U58] PHP：数组三件套
来源：http://dali.9152youxi.cn/Article/details/gtptpsofjv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hywenlv.cn/Article/details/gtrvfpcrzr.html

[U59] PHP：自定义排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtpplhsyll.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.redwolf501.top/Article/details/gtkfmamowi.html

[U60] PHP：JSON 编解码
来源：http://dali.yj202588.top/Article/details/gtirsgrbrd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gogol.net.cn/Article/details/gtmchrsweo.html

[U61] PHP：正则
来源：http://dali.jlsjyb.cn/Article/details/gtiajjfaiw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gtldwifuyv.html

[U62] PHP：日期对象
来源：http://dali.yongpay.top/Article/details/gtvcjnmqra.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xylfe.cn/Article/details/gtuumbxtat.html

[U63] PHP：文件读写
来源：http://dali.andypj.xyz/Article/details/gtsfanbvvz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhiwuduotai.top/Article/details/gtifhpodlb.html

[U64] PHP：目录遍历
来源：http://dali.hammf.cn/Article/details/gtlnrfaust.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nanxinkj.top/Article/details/gtsqocfmje.html

[U65] PHP：会话
来源：http://dali.cdnleiting.top/Article/details/gtokvksbju.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ivvv.top/Article/details/gtjqhofawe.html

[U66] PHP：设置 Cookie
来源：http://dali.yueranfly.top/Article/details/gtktfabtub.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xylfe.cn/Article/details/gtjxxnpybj.html

[U67] PHP：处理文件上传
来源：http://dali.zhengqikj.top/Article/details/gtmtugcmxe.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.chenlongwang.top/Article/details/gtvegkliof.html

[U68] PHP：PDO 连接
来源：http://dali.yj20258.top/Article/details/gtcplxtmis.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.havefunace.top/Article/details/gtkpuyqhmu.html

[U69] PHP：PDO 预处理
来源：http://dali.yj20258888.top/Article/details/gtrjarkdtx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ppjwa.cn/Article/details/gtyjktqrsg.html

[U70] PHP：PDO 事务
来源：http://dali.hnqzz.top/Article/details/gtzaonmutf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.chenzaomai.com/Article/details/gthkfxkozv.html

[U71] PHP：抛出异常
来源：http://dali.yj202588.top/Article/details/gtglxoyohq.html

throw new RuntimeException("失败", 500);
来源：http://dali.hfpthk.cn/Article/details/gtyxwusbmm.html

[U72] PHP：写错误日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtftelxnuh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ivvv.top/Article/details/gtwoipfwxf.html

[U73] PHP：读取 ini 配置
来源：http://dali.c1oappe.top/Article/details/gtydsoeqvf.html

parse_ini_file("config.ini", true)
来源：http://dali.fzhhl.top/Article/details/gtlsceijcv.html

[U74] PHP：读取环境变量
来源：http://dali.yj20258.top/Article/details/gteoppcwng.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj20258888.top/Article/details/gtbzbkkltv.html

[U75] PHP：依赖注入
来源：http://dali.hysaishi.cn/Article/details/gtalrmuxti.html

composer require psr/container
来源：http://dali.0kj1m.cn/Article/details/gtbpclwhyd.html

[U76] PHP：简单路由
来源：http://dali.yuxming.cn/Article/details/gtzquhiazv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yj20258.top/Article/details/gtlwgufqrl.html

[U77] PHP：模板渲染
来源：http://dali.havefunace.top/Article/details/gtwiyxmdvp.html

composer require twig/twig
来源：http://dali.xuetiantiany.cn/Article/details/gtzwzpkfmq.html

[U78] PHP：单元测试
来源：http://dali.gogol.net.cn/Article/details/gtdtraeyqr.html

composer require --dev phpunit/phpunit
来源：http://dali.jqgfzy.top/Article/details/gtclkxxumw.html

[U79] PHP：静态分析
来源：http://dali.svipenyu.cn/Article/details/gtiyavvagu.html

composer require --dev phpstan/phpstan
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipmjfmqu.html

[U80] PHP：代码规范修复
来源：http://dali.ybcxt.top/Article/details/gtkgtjyhzh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.chenzaomai.com/Article/details/gtwrpdrumz.html

[U81] JS：初始化项目
来源：http://dali.yj202588.top/Article/details/gtikqfexvj.html

npm init -y;  npm i express
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjriicmjc.html

[U82] JS：package.json 脚本
来源：http://dali.hysaishi.cn/Article/details/gtcmbzxibt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.kuanghao11.cn/Article/details/gtvghddbfz.html

[U83] JS：ES Module 导入导出
来源：http://dali.jianghu66.top/Article/details/gtqhdbobxv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yongpay.top/Article/details/gtxtxowcat.html

[U84] JS：CommonJS 写法
来源：http://dali.fengsongda.top/Article/details/gtxstnfiyt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cdnleiting.top/Article/details/gtdnhqviog.html

[U85] JS：可选链
来源：http://dali.daria6918.cn/Article/details/gtnqrxqqnh.html

a?.b?.c
来源：http://dali.sysykeji.top/Article/details/gtkdqazldx.html

[U86] JS：空值合并
来源：http://dali.wangdashe.top/Article/details/gtgadlltmo.html

a ?? b
来源：http://dali.quarkkingdee.top/Article/details/gtumvmtzmq.html

[U87] JS：解构默认值
来源：http://dali.cdnleiting.top/Article/details/gtasmrcvol.html

const { a = 1, b = 2 } = obj;
来源：http://dali.svipenyu.cn/Article/details/gtnsjyhqyv.html

[U88] JS：对象展开合并
来源：http://dali.hongshengwenyu.top/Article/details/gtcjfrqeaz.html

{ ...a, ...b }
来源：http://dali.ybcxt.top/Article/details/gtkbqqgvjg.html

[U89] JS：数组去重
来源：http://dali.kuanghao11.cn/Article/details/gtcrryuhfo.html

[...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtztvhmbqu.html

[U90] JS：数字数组排序
来源：http://dali.zhongyouzk.top/Article/details/gtkcfsvrlv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gtwtjfpozg.html

[U91] JS：对象键值遍历
来源：http://dali.yonumen.top/Article/details/gtwsvwzzix.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbvxuwxo.html

[U92] JS：深拷贝
来源：http://dali.gotoacloud.top/Article/details/gttrdnsbjs.html

structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gtulrkuftq.html

[U93] JS：模板字符串
来源：http://dali.9152youxi.cn/Article/details/gtsbpoeezo.html

`共 ${n} 条`
来源：http://dali.zhengqikj.top/Article/details/gtnejcbjvl.html

[U94] JS：箭头函数
来源：http://dali.birdmap.top/Article/details/gtsdjhlavs.html

const double = x => x * 2;
来源：http://dali.cdnleiting.top/Article/details/gtlsckcqts.html

[U95] JS：Promise 包装
来源：http://dali.shzxlz.cn/Article/details/gthsiidwmt.html

new Promise((resolve, reject) => {})
来源：http://dali.havefunace.top/Article/details/gtycjyimkh.html

[U96] JS：async/await 与异常
来源：http://dali.yongpay.top/Article/details/gtkajzmhxb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gttcdlehnh.html

[U97] JS：并发请求
来源：http://dali.feifeiyinyue.top/Article/details/gtstgscvfi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gtoulxkles.html

[U98] JS：fetch 带 JSON
来源：http://dali.hfpthk.cn/Article/details/gtmylbuqch.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shuidangran.top/Article/details/gtzhvuvfov.html

[U99] JS：事件监听
来源：http://dali.bjfxy.top/Article/details/gtgqmucqjs.html

el.addEventListener("click", e => {})
来源：http://dali.bjfxy.top/Article/details/gtrrkacqjt.html

[U100] JS：DOM 查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgeghznu.html

document.querySelector(".item")
来源：http://dali.hywenlv.cn/Article/details/gtveguhcgd.html

[U101] JS：classList 操作
来源：http://dali.chenjidiqi.icu/Article/details/gtetbphdfn.html

el.classList.toggle("active")
来源：http://dali.cheryme.top/Article/details/gtzxsewpfp.html

[U102] JS：本地存储
来源：http://dali.jyoumei.cn/Article/details/gtldubppbd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.tian-w.cn/Article/details/gtovzxdewq.html

[U103] JS：定时器
来源：http://dali.smart0.xyz/Article/details/gtocfgxvix.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.quarkkingdee.top/Article/details/gtjiqioqgz.html

[U104] JS：防抖
来源：http://dali.cashguo.top/Article/details/gtnxtgvpck.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gtousuozzh.html

[U105] JS：节流
来源：http://dali.zycfv.cn/Article/details/gtpaygvcxs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xylfe.cn/Article/details/gttvegqfkl.html

[U106] JS：日期格式化
来源：http://dali.iojbl.cn/Article/details/gtuiujyciu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.fzhhl.top/Article/details/gthqeelgus.html

[U107] JS：数字千分位
来源：http://dali.kuanghao11.cn/Article/details/gtiwvixatv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gtemzagkbo.html

[U108] JS：随机整数
来源：http://dali.nwbrower.top/Article/details/gtzyatpekz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jiagoushi.top/Article/details/gtlsdxbblq.html

[U109] JS：数组分组
来源：http://dali.ybcxt.top/Article/details/gtfcbkpkna.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ydzc1.top/Article/details/gtbzfqvzjw.html

[U110] JS：数组分块
来源：http://dali.gzhubu.top/Article/details/gthysoyruq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hammf.cn/Article/details/gthiqhvcpz.html

[U111] JS：对象转 Map
来源：http://dali.gotoacloud.top/Article/details/gtrmqroees.html

new Map(Object.entries(obj))
来源：http://dali.dashuyun.cn/Article/details/gthhfhrlor.html

[U112] JS：字符串补位
来源：http://dali.yueranfly.top/Article/details/gtkufelexn.html

"7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtmlxyetqc.html

[U113] JS：正则替换全部
来源：http://dali.fzhhl.top/Article/details/gtxkzirbbq.html

s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtqvgppqlg.html

[U114] JS：JSON 深比较
来源：http://dali.ppjwa.cn/Article/details/gtwqgyzxha.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenlongwang.top/Article/details/gtknyaayka.html

[U115] JS：生成 UUID
来源：http://dali.haohaochexian.top/Article/details/gtlndainja.html

crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtcgajljfr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.wangshuangyany.cn/Article/details/gtxlmacuzf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gaohongyu789.top/Article/details/gtnubbngeb.html

[U117] JS：单元测试
来源：http://dali.yj20258888.top/Article/details/gthcjytttf.html

npm i -D vitest;  npx vitest
来源：http://dali.zycfv.cn/Article/details/gteacbefri.html

[U118] JS：开发服务器
来源：http://dali.zhengqikj.top/Article/details/gtanhviadc.html

npm i -D vite;  npx vite
来源：http://dali.yangfankeji.com/Article/details/gtnepijkow.html

[U119] JS：生产构建
来源：http://dali.yj20258.top/Article/details/gtckywdlnk.html

npx vite build
来源：http://dali.pengpengdd.cyou/Article/details/gtwnyuiykw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yangfankeji.com/Article/details/gttougrgfi.html

import.meta.env.VITE_API_URL
来源：http://dali.nanxinkj.top/Article/details/gtexwpohfz.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtqrsqcboi.html

统计汇总
来源：http://dali.ppjwa.cn/Article/details/gtzmqqzjnr.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtczydtnxs.html

按语言统计（条）：
来源：http://dali.chenzaomai.com/Article/details/gtqqblqxdw.html

Python ......... 252
来源：http://dali.iojbl.cn/Article/details/gtiaerfggn.html

PHP ............ 252
来源：http://dali.gotoacloud.top/Article/details/gtyfylwcrz.html

JavaScript ..... 252
来源：http://dali.zdqjudy.top/Article/details/gtqyfisoyo.html

TypeScript ..... 212
来源：http://dali.aibaodan.cn/Article/details/gtehgdvwbf.html

Java ........... 212
来源：http://dali.chenlongwang.top/Article/details/gtorwcxyxb.html

Go ............. 212
来源：http://dali.sweek.top/Article/details/gtecrralwm.html

Ruby ........... 212
来源：http://dali.hywenlv.cn/Article/details/gtkprqsvow.html

C# ............. 212
来源：http://dali.sysykeji.top/Article/details/gtgirofwcz.html

C .............. 30
来源：http://dali.zycfv.cn/Article/details/gtskoqhixr.html

C++ ............ 30
来源：http://dali.tianlin.xyz/Article/details/gttudyzirl.html

SQL ............ 90
来源：http://dali.xylfe.cn/Article/details/gtnxwqkntb.html

Bash ........... 80
来源：http://dali.vqdsnc.cn/Article/details/gtgrelqsif.html

Kotlin ......... 15
来源：http://dali.havefunace.top/Article/details/gtewkwpthm.html

Swift .......... 15
来源：http://dali.shuidangran.top/Article/details/gteypglxww.html

Lua ............ 10
来源：http://dali.dashuyun.cn/Article/details/gtiyvboelo.html

Perl ........... 10
来源：http://dali.wangshuangyany.cn/Article/details/gthwpczhrm.html

Scala .......... 10
来源：http://dali.iojbl.cn/Article/details/gtiqtovwgh.html

------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtcbnrgheh.html

合计 ........... 2106 条
来源：http://dali.pengpengdd.cyou/Article/details/gtkypxcdci.html

按章节统计：
来源：http://dali.aibaodan.cn/Article/details/gtuilcwtic.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hnxiangtu.top/Article/details/gtiiunnlrd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.snrcjt.cn/Article/details/gtczpmxgsy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.dianchejie.cn/Article/details/gtpkqvfwiw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cucudq.cn/Article/details/gtynzkhzkz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.wangdashe.top/Article/details/gtcrchxgbq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.daxiang520.top/Article/details/gtdjqmztaq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.bjfxy.top/Article/details/gtkozuthck.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.daria6918.cn/Article/details/gtxujdkljr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gtvtwdjejm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yuanzhike.top/Article/details/gtpoxgcymo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gtamuoeoqk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtycnvdhse.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gtblgspvnz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.guannengcc.top/Article/details/gtyeuwyyuf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.pengpengdd.cyou/Article/details/gtvrnwqnxt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtnnggqtsy.html

Q SQL 专题                              90
来源：http://dali.xinyue.icu/Article/details/gttxyjmmqw.html

R Bash 专题                             80
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsdjdppr.html

S C / C++ 专题                          60
来源：http://dali.9152youxi.cn/Article/details/gtxfbxsyde.html

T 其他语言补充                          60
来源：http://dali.fzhhl.top/Article/details/gttlyawhny.html

U 高频实用片段                         120
来源：http://dali.xuetiantiany.cn/Article/details/gtvvxqsxki.html

------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gtvqnydiyr.html

合计                                  2106 条
来源：http://dali.cdnleiting.top/Article/details/gtacaecocy.html

--------------------------------------------------------------------------------
来源：http://dali.shuidangran.top/Article/details/gtdojyjoma.html

使用提醒
来源：http://dali.xuanzx.com/Article/details/gtrlsvbvnt.html

--------------------------------------------------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gtjkedjase.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hammf.cn/Article/details/gtwdmnirbq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.quarkkingdee.top/Article/details/gtpvcalbhe.html


<!-- 参考信息 -->