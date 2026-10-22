代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.cucudq.cn/Article/details/gt2qabnbbie.html

[T55] Scala：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gt2ekaljmpu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sysykeji.top/Article/details/gt2owctjmrn.html

[T56] Scala：样例类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2skkpzcbj.html

case class User(name: String, age: Int)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2shkhjgfj.html

[T57] Scala：模式匹配
来源：http://dali.zhengqikj.top/Article/details/gt2kzcdrhlf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sweek.top/Article/details/gt2kqullama.html

[T58] Scala：函数定义
来源：http://dali.iojbl.cn/Article/details/gt2gwuadyyq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.meibo888.top/Article/details/gt2gahfyhwo.html

[T59] Scala：循环
来源：http://dali.sweek.top/Article/details/gt2ryqfplrw.html

for (i <- 1 to 10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gt2ookydroy.html

[T60] Scala：折叠
来源：http://dali.0kj1m.cn/Article/details/gt2iqefclwh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zkriqvqv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2jytzrpja.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hywenlv.cn/Article/details/gt2fnxfbpul.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2heapyuxn.html

[U01] Py：创建虚拟环境
来源：http://dali.havefunace.top/Article/details/gt2ngsvwejt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tianlin.xyz/Article/details/gt2zffyqugy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tianlin.xyz/Article/details/gt2fnrnetxr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jiagoushi.top/Article/details/gt2zojmbnib.html

[U03] Py：加载 .env 配置
来源：http://dali.jianghu66.top/Article/details/gt2xazwtdhj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xylfe.cn/Article/details/gt2thbhrier.html

[U04] Py：变量调试打印
来源：http://dali.daria6918.cn/Article/details/gt2xlsqyzzy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nanxinkj.top/Article/details/gt2rbuckxba.html

[U05] Py：列表去重且保序
来源：http://dali.xylfe.cn/Article/details/gt2nlipamsb.html

list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gt2tstfhtgb.html

[U06] Py：合并两个字典
来源：http://dali.zhengqikj.top/Article/details/gt2jghjllmt.html

{**a, **b}
来源：http://dali.snrcjt.cn/Article/details/gt2trfldvvw.html

[U07] Py：反转字典键值
来源：http://dali.gotoacloud.top/Article/details/gt2aqrefecg.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258.top/Article/details/gt2aeviriki.html

[U08] Py：展平二维列表
来源：http://dali.vqdsnc.cn/Article/details/gt2avgkoedq.html

[y for x in nested for y in x]
来源：http://dali.yueranfly.top/Article/details/gt2xqtpabsr.html

[U09] Py：字典取最大值的键
来源：http://dali.aizwys.cn/Article/details/gt2pytfggte.html

max(d, key=d.get)
来源：http://dali.bjfxy.top/Article/details/gt2wazcjwtt.html

[U10] Py：按值排序字典
来源：http://dali.aibaodan.cn/Article/details/gt2qeqlvgza.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.meibo888.top/Article/details/gt2coqjbana.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yrivnnzy.html

(x * 2 for x in arr)
来源：http://dali.yj202588.top/Article/details/gt2nvavkcuc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvkbumf.html

Counter(arr).most_common(3)
来源：http://dali.andypj.xyz/Article/details/gt2oixienwk.html

[U13] Py：固定长度队列
来源：http://dali.0kj1m.cn/Article/details/gt2auvlnrmf.html

deque(maxlen=10)
来源：http://dali.zycfv.cn/Article/details/gt2bvrfqrnp.html

[U14] Py：分组收集到列表
来源：http://dali.chenlongwang.top/Article/details/gt2uvuguqfx.html

defaultdict(list)
来源：http://dali.gzhubu.top/Article/details/gt2dqakkvkw.html

[U15] Py：高精度计时
来源：http://dali.redwolf501.top/Article/details/gt2unngrcmb.html

t = time.perf_counter()
来源：http://dali.hfpthk.cn/Article/details/gt2ccoywioe.html

[U16] Py：命令行参数解析
来源：http://dali.shangyingyoupin.top/Article/details/gt2ywmlrxbr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pjglfxfe.html

[U17] Py：初始化日志
来源：http://dali.gzhubu.top/Article/details/gt2uzkciwyx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jyoumei.cn/Article/details/gt2olfvpamj.html

[U18] Py：预编译正则
来源：http://dali.iojbl.cn/Article/details/gt2mmbdnokd.html

pat = re.compile(r"\d+")
来源：http://dali.hnqzz.top/Article/details/gt2bmbuwwtf.html

[U19] Py：正则替换带回调
来源：http://dali.zdqjudy.top/Article/details/gt2maoonizk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jlsjyb.cn/Article/details/gt2tgbkjyzr.html

[U20] Py：缓存函数结果
来源：http://dali.hysaishi.cn/Article/details/gt2pzuhfbyp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wwwmajyt.html

[U21] Py：自定义上下文管理器
来源：http://dali.meibo888.top/Article/details/gt2nlkgdwys.html

@contextlib.contextmanager
来源：http://dali.shzxlz.cn/Article/details/gt2dtxnvmva.html

[U22] Py：矩阵转置
来源：http://dali.fzhhl.top/Article/details/gt2pgtnotuz.html

list(zip(*m))
来源：http://dali.hfpthk.cn/Article/details/gt2fmijkcxn.html

[U23] Py：分块读取大文件
来源：http://dali.shzxlz.cn/Article/details/gt2gnrpgaex.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhengqikj.top/Article/details/gt2aihgjmmv.html

[U24] Py：路径操作
来源：http://dali.gzhubu.top/Article/details/gt2sbbahwbu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jianghu66.top/Article/details/gt2rdbmkroa.html

[U25] Py：CSV 按字典读
来源：http://dali.birdmap.top/Article/details/gt2minqsvzf.html

csv.DictReader(f)
来源：http://dali.xylfe.cn/Article/details/gt2ssljbrdm.html

[U26] Py：并发下载
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vpdlzibj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.haohaochexian.top/Article/details/gt2fpxhljto.html

[U27] Py：异步 HTTP
来源：http://dali.jlsjyb.cn/Article/details/gt2qfsllwcq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.wangshuangyany.cn/Article/details/gt2bwzceqfl.html

[U28] Py：类型别名
来源：http://dali.cashguo.top/Article/details/gt2ucekzsok.html

UserId = int
来源：http://dali.jqgufenzy.top/Article/details/gt2szhldkff.html

[U29] Py：属性校验
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ygefsorr.html

@property 与 @x.setter 配合
来源：http://dali.jyoumei.cn/Article/details/gt2htlusmco.html

[U30] Py：数据类
来源：http://dali.nanxinkj.top/Article/details/gt2atxudnto.html

@dataclass(slots=True)
来源：http://dali.yuxming.cn/Article/details/gt2awojxrjc.html

[U31] Py：单测
来源：http://dali.cdnleiting.top/Article/details/gt2zxlvwzte.html

python -m pytest -q
来源：http://dali.shuidangran.top/Article/details/gt2tgedjqcv.html

[U32] Py：代码格式化
来源：http://dali.hammf.cn/Article/details/gt2xhpggsbx.html

ruff format . && ruff check --fix .
来源：http://dali.feifeiyinyue.top/Article/details/gt2bmrfavjt.html

[U33] Py：打包发布
来源：http://dali.tian-w.cn/Article/details/gt2hqcqqxsg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yanxiufei.cn/Article/details/gt2hzrggfvz.html

[U34] Py：判断编码
来源：http://dali.cqqwz.cn/Article/details/gt2rgtqxjkk.html

chardet.detect(raw)
来源：http://dali.nanxuanxn.top/Article/details/gt2ystuwmhv.html

[U35] Py：发送邮件
来源：http://dali.zhengqikj.top/Article/details/gt2jhrygikr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.guowangkeji.top/Article/details/gt2fxtijrzq.html

[U36] Py：定时任务
来源：http://dali.yongpay.top/Article/details/gt2qfxbemzw.html

schedule.every(10).minutes.do(job)
来源：http://dali.jiagoushi.top/Article/details/gt2wticgoje.html

[U37] Py：读写 Excel
来源：http://dali.zhongyouzk.top/Article/details/gt2qcaxcevh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ndjfrhno.html

[U38] Py：获取脚本所在目录
来源：http://dali.ppjwa.cn/Article/details/gt2bsdbjowj.html

Path(__file__).resolve().parent
来源：http://dali.nanxinkj.top/Article/details/gt2wrkanrlk.html

[U39] Py：判断是否在交互环境
来源：http://dali.yonumen.top/Article/details/gt2iquunujb.html

sys.stdout.isatty()
来源：http://dali.haohaochexian.top/Article/details/gt2ndzyqpkf.html

[U40] Py：打印到标准错误
来源：http://dali.snrcjt.cn/Article/details/gt2jfpoewhc.html

print("err", file=sys.stderr)
来源：http://dali.havefunace.top/Article/details/gt2jxutveot.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.guowangkeji.top/Article/details/gt2cgoawazo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xziqi.cn/Article/details/gt2pxazowqi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jqgfzy.top/Article/details/gt2nnghtbxh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nanxuanxn.top/Article/details/gt2ctdxoofp.html

[U43] PHP：声明命名空间
来源：http://dali.ppjwa.cn/Article/details/gt2iysptwks.html

namespace App\Http;
来源：http://dali.jianghu66.top/Article/details/gt2edyghkvx.html

[U44] PHP：开启严格类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2avcrylii.html

declare(strict_types=1);
来源：http://dali.tianlin.xyz/Article/details/gt2xpdreyab.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jianghu66.top/Article/details/gt2lvmtwsgm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gt2ipevharz.html

[U46] PHP：可空类型
来源：http://dali.tianlin.xyz/Article/details/gt2privgqty.html

?string $name = null
来源：http://dali.sysykeji.top/Article/details/gt2ulemcetj.html

[U47] PHP：联合类型
来源：http://dali.yuanzhike.top/Article/details/gt2uebfpejs.html

int|string $id
来源：http://dali.yongpay.top/Article/details/gt2iwrqilrx.html

[U48] PHP：纯枚举
来源：http://dali.iojbl.cn/Article/details/gt2cbwshjmu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.wangdashe.top/Article/details/gt2vqsnclsu.html

[U49] PHP：只读属性
来源：http://dali.pengpengdd.cyou/Article/details/gt2zgsottgb.html

public readonly string $name
来源：http://dali.daxiang520.top/Article/details/gt2nekoduab.html

[U50] PHP：构造器属性提升
来源：http://dali.ehwqpu.com/Article/details/gt2kfcrtdyy.html

public function __construct(private int $id) {}
来源：http://dali.jqgfzy.top/Article/details/gt2vpthcucv.html

[U51] PHP：数组解构
来源：http://dali.fzhhl.top/Article/details/gt2jcumrlio.html

[$a, $b] = $arr;
来源：http://dali.sxryk.cn/Article/details/gt2tevnziqe.html

[U52] PHP：箭头函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2azlezvmd.html

$double = fn($x) => $x * 2;
来源：http://dali.xylfe.cn/Article/details/gt2bhvulqbk.html

[U53] PHP：空合并运算符
来源：http://dali.gaohongyu789.top/Article/details/gt2iwzwgyrq.html

$v = $a ?? $b ?? "default";
来源：http://dali.bjfxy.top/Article/details/gt2norfehka.html

[U54] PHP：空安全调用
来源：http://dali.wangshuangyany.cn/Article/details/gt2phgwdoza.html

$obj?->method()
来源：http://dali.gaohongyu789.top/Article/details/gt2uudoqxih.html

[U55] PHP：match 表达式
来源：http://dali.gotoacloud.top/Article/details/gt2kwplhyoe.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xziqi.cn/Article/details/gt2tnrwsbyr.html

[U56] PHP：命名参数
来源：http://dali.gogol.net.cn/Article/details/gt2aydstebf.html

f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2ztgudzjt.html

[U57] PHP：字符串插值
来源：http://dali.gzhubu.top/Article/details/gt2hcwdylce.html

"值: {$a}"
来源：http://dali.jianghu66.top/Article/details/gt2oetfkgel.html

[U58] PHP：数组三件套
来源：http://dali.jyoumei.cn/Article/details/gt2jgnmqxxo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mmnwgxrc.html

[U59] PHP：自定义排序
来源：http://dali.yuanzhike.top/Article/details/gt2nolifgot.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhongyouzk.top/Article/details/gt2geazvwir.html

[U60] PHP：JSON 编解码
来源：http://dali.meibo888.top/Article/details/gt2hbuaorrd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bxyxdcch.html

[U61] PHP：正则
来源：http://dali.gogol.net.cn/Article/details/gt2jdmwgqan.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.redwolf501.top/Article/details/gt2ihjimxzz.html

[U62] PHP：日期对象
来源：http://dali.nanxuanxn.top/Article/details/gt2gnyulvgw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj20258.top/Article/details/gt2sutziafj.html

[U63] PHP：文件读写
来源：http://dali.0kj1m.cn/Article/details/gt2vwqidgbt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cdnleiting.top/Article/details/gt2mnjhecje.html

[U64] PHP：目录遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mxeungpr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.fzhhl.top/Article/details/gt2oopehycx.html

[U65] PHP：会话
来源：http://dali.fzhhl.top/Article/details/gt2ttwicwvp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2iwgueklr.html

[U66] PHP：设置 Cookie
来源：http://dali.gaohongyu789.top/Article/details/gt2hptwxhai.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.0kj1m.cn/Article/details/gt2laibxixk.html

[U67] PHP：处理文件上传
来源：http://dali.ydzc1.top/Article/details/gt2qgcpsgrn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kxfecwti.html

[U68] PHP：PDO 连接
来源：http://dali.xuetiantiany.cn/Article/details/gt2wyfkasyw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xylfe.cn/Article/details/gt2dqqgjvut.html

[U69] PHP：PDO 预处理
来源：http://dali.cdnleiting.top/Article/details/gt2maujyxke.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cdnleiting.top/Article/details/gt2ykgvjiuf.html

[U70] PHP：PDO 事务
来源：http://dali.dashuyun.cn/Article/details/gt2adrkdqqb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2whohxtor.html

[U71] PHP：抛出异常
来源：http://dali.zhixingplan.top/Article/details/gt2kebxrhyi.html

throw new RuntimeException("失败", 500);
来源：http://dali.shzxlz.cn/Article/details/gt2wcjzdlin.html

[U72] PHP：写错误日志
来源：http://dali.tanke756.top/Article/details/gt2hnnrroqh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenjidiqi.icu/Article/details/gt2fcxzryqd.html

[U73] PHP：读取 ini 配置
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uihlmkeg.html

parse_ini_file("config.ini", true)
来源：http://dali.daria6918.cn/Article/details/gt2hpycqyrl.html

[U74] PHP：读取环境变量
来源：http://dali.ehwqpu.com/Article/details/gt2tjxoqqth.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sysykeji.top/Article/details/gt2xakstiii.html

[U75] PHP：依赖注入
来源：http://dali.snrcjt.cn/Article/details/gt2oslaujau.html

composer require psr/container
来源：http://dali.jianghu66.top/Article/details/gt2iccxhayw.html

[U76] PHP：简单路由
来源：http://dali.zdqjudy.top/Article/details/gt2syxbjxpu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.pycfn.com/Article/details/gt2wsdltsgc.html

[U77] PHP：模板渲染
来源：http://dali.chenjidiqi.icu/Article/details/gt2ndrwmvpg.html

composer require twig/twig
来源：http://dali.wangdashe.top/Article/details/gt2ktcukdec.html

[U78] PHP：单元测试
来源：http://dali.gaohongyu789.top/Article/details/gt2cvydoxrg.html

composer require --dev phpunit/phpunit
来源：http://dali.yueranfly.top/Article/details/gt2iitncpyu.html

[U79] PHP：静态分析
来源：http://dali.9152youxi.cn/Article/details/gt2jnymnkvm.html

composer require --dev phpstan/phpstan
来源：http://dali.tianlin.xyz/Article/details/gt2ssentmot.html

[U80] PHP：代码规范修复
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2btpyhrio.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yanxiufei.cn/Article/details/gt2xtamxqpb.html

[U81] JS：初始化项目
来源：http://dali.iojbl.cn/Article/details/gt2sdfascol.html

npm init -y;  npm i express
来源：http://dali.jinqigfzy.top/Article/details/gt2xnecjbtp.html

[U82] JS：package.json 脚本
来源：http://dali.dianchejie.cn/Article/details/gt2gercvuwr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.pycfn.com/Article/details/gt2gywlvceu.html

[U83] JS：ES Module 导入导出
来源：http://dali.shzxlz.cn/Article/details/gt2wmikjlcn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hysaishi.cn/Article/details/gt2gtjbqavh.html

[U84] JS：CommonJS 写法
来源：http://dali.9152youxi.cn/Article/details/gt2umwznkpa.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.fengsongda.top/Article/details/gt2fybgouqy.html

[U85] JS：可选链
来源：http://dali.316326.xyz/Article/details/gt2idxocdcl.html

a?.b?.c
来源：http://dali.daria6918.cn/Article/details/gt2ickhdawo.html

[U86] JS：空值合并
来源：http://dali.hnqzz.top/Article/details/gt2yaxrerob.html

a ?? b
来源：http://dali.hywenlv.cn/Article/details/gt2qouhsaxy.html

[U87] JS：解构默认值
来源：http://dali.xylfe.cn/Article/details/gt2okfxxixk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.9152youxi.cn/Article/details/gt2ljwteaip.html

[U88] JS：对象展开合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nuqtwamx.html

{ ...a, ...b }
来源：http://dali.chenlongwang.top/Article/details/gt2pylwkktx.html

[U89] JS：数组去重
来源：http://dali.shzxlz.cn/Article/details/gt2vnnbffcc.html

[...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gt2nsqycxoo.html

[U90] JS：数字数组排序
来源：http://dali.cdnleiting.top/Article/details/gt2xuppbakc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gt2crlzvmcy.html

[U91] JS：对象键值遍历
来源：http://dali.ppjwa.cn/Article/details/gt2hdbiotxu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.tanke756.top/Article/details/gt2yqrbpnkq.html

[U92] JS：深拷贝
来源：http://dali.xinyue.icu/Article/details/gt2cizyphey.html

structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gt2qvdjrvjy.html

[U93] JS：模板字符串
来源：http://dali.ppjwa.cn/Article/details/gt2uippccve.html

`共 ${n} 条`
来源：http://dali.sysykeji.top/Article/details/gt2ltgfpxxg.html

[U94] JS：箭头函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rsntihyz.html

const double = x => x * 2;
来源：http://dali.meibo888.top/Article/details/gt2edffuuvx.html

[U95] JS：Promise 包装
来源：http://dali.ppjwa.cn/Article/details/gt2nzbarqpk.html

new Promise((resolve, reject) => {})
来源：http://dali.316326.xyz/Article/details/gt2lqzjyilq.html

[U96] JS：async/await 与异常
来源：http://dali.cashguo.top/Article/details/gt2hseplhpx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gt2sqboaqjq.html

[U97] JS：并发请求
来源：http://dali.ivvv.top/Article/details/gt2imfminva.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnvhuukn.html

[U98] JS：fetch 带 JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rcqyjtaj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.dianchejie.cn/Article/details/gt2dooqhrvy.html

[U99] JS：事件监听
来源：http://dali.meibo888.top/Article/details/gt2gjipadyd.html

el.addEventListener("click", e => {})
来源：http://dali.chenjidiqi.icu/Article/details/gt2zcyhykqc.html

[U100] JS：DOM 查询
来源：http://dali.c1oappe.top/Article/details/gt2gsaaxbcl.html

document.querySelector(".item")
来源：http://dali.dianchejie.cn/Article/details/gt2tcdrfaqq.html

[U101] JS：classList 操作
来源：http://dali.zhoulong.xyz/Article/details/gt2jrsilcdg.html

el.classList.toggle("active")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rkkyizpt.html

[U102] JS：本地存储
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xqwkieqc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shangyingyoupin.top/Article/details/gt2exmynwxh.html

[U103] JS：定时器
来源：http://dali.tianlin.xyz/Article/details/gt2czuytcji.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.redwolf501.top/Article/details/gt2dqmfjwey.html

[U104] JS：防抖
来源：http://dali.fzhhl.top/Article/details/gt2gngfocfo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gt2pokzselp.html

[U105] JS：节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eyywctof.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hywenlv.cn/Article/details/gt2ipkanmaf.html

[U106] JS：日期格式化
来源：http://dali.chenzaomai.com/Article/details/gt2ytgsdkow.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yrnhsjvd.html

[U107] JS：数字千分位
来源：http://dali.fengsongda.top/Article/details/gt2tifdstol.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jqgfzy.top/Article/details/gt2gsonplzx.html

[U108] JS：随机整数
来源：http://dali.shzxlz.cn/Article/details/gt2zutrjpnp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cvzbjmgi.html

[U109] JS：数组分组
来源：http://dali.jinqigufen.top/Article/details/gt2kqoutyot.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gt2xzwgkdud.html

[U110] JS：数组分块
来源：http://dali.cheryme.top/Article/details/gt2jcxuvsof.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.c1oappe.top/Article/details/gt2cfjilpxk.html

[U111] JS：对象转 Map
来源：http://dali.zycfv.cn/Article/details/gt2mtmbfkrj.html

new Map(Object.entries(obj))
来源：http://dali.ehwqpu.com/Article/details/gt2iuwstere.html

[U112] JS：字符串补位
来源：http://dali.yonumen.top/Article/details/gt2pqlncacj.html

"7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gt2pubdjuzg.html

[U113] JS：正则替换全部
来源：http://dali.zycfv.cn/Article/details/gt2rmmjnjzu.html

s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2iceopoah.html

[U114] JS：JSON 深比较
来源：http://dali.dianchejie.cn/Article/details/gt2payeuuwa.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gt2pypitfsw.html

[U115] JS：生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bsffaxfb.html

crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gt2spfciuvb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.haohaochexian.top/Article/details/gt2vgzbgvmt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jianghu66.top/Article/details/gt2qwukolcz.html

[U117] JS：单元测试
来源：http://dali.tianlin.xyz/Article/details/gt2tkvffmyv.html

npm i -D vitest;  npx vitest
来源：http://dali.ivvv.top/Article/details/gt2glpahscf.html

[U118] JS：开发服务器
来源：http://dali.zycfv.cn/Article/details/gt2ztghgegw.html

npm i -D vite;  npx vite
来源：http://dali.quarkkingdee.top/Article/details/gt2yiqaqepx.html

[U119] JS：生产构建
来源：http://dali.ivvv.top/Article/details/gt2rofmjrtq.html

npx vite build
来源：http://dali.kuanghao11.cn/Article/details/gt2mdmpbgzv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.fengsongda.top/Article/details/gt2htltjpid.html

import.meta.env.VITE_API_URL
来源：http://dali.ppjwa.cn/Article/details/gt2mthjsifz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2djlyvnpq.html

统计汇总
来源：http://dali.sufxvd.cn/Article/details/gt2aggppxit.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2dglgnphl.html

按语言统计（条）：
来源：http://dali.cheryme.top/Article/details/gt2mkcuexym.html

Python ......... 252
来源：http://dali.feifeiyinyue.top/Article/details/gt2xnsipnfp.html

PHP ............ 252
来源：http://dali.chenjidiqi.icu/Article/details/gt2gupqzdhp.html

JavaScript ..... 252
来源：http://dali.xziqi.cn/Article/details/gt2suitgsaa.html

TypeScript ..... 212
来源：http://dali.guowangkeji.top/Article/details/gt2yuhgvmdo.html

Java ........... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gt2acpieflv.html

Go ............. 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tgqovxqg.html

Ruby ........... 212
来源：http://dali.0kj1m.cn/Article/details/gt2ybpkrxnt.html

C# ............. 212
来源：http://dali.fzhhl.top/Article/details/gt2muikbezv.html

C .............. 30
来源：http://dali.jlsjyb.cn/Article/details/gt2hqvdecmj.html

C++ ............ 30
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjxvzche.html

SQL ............ 90
来源：http://dali.cashguo.top/Article/details/gt2cbplcxrj.html

Bash ........... 80
来源：http://dali.mhx1999.top/Article/details/gt2sgwyklfq.html

Kotlin ......... 15
来源：http://dali.andypj.xyz/Article/details/gt2wrxeftbx.html

Swift .......... 15
来源：http://dali.hongshengwenyu.top/Article/details/gt2ksyckgmr.html

Lua ............ 10
来源：http://dali.meibo888.top/Article/details/gt2vvwfgcmk.html

Perl ........... 10
来源：http://dali.mhx1999.top/Article/details/gt2kijrldln.html

Scala .......... 10
来源：http://dali.tianlin.xyz/Article/details/gt2oxhsavwm.html

------------------------------------
来源：http://dali.fengsongda.top/Article/details/gt2gvigrtqf.html

合计 ........... 2106 条
来源：http://dali.zhengqikj.top/Article/details/gt2yhfjyldz.html

按章节统计：
来源：http://dali.yangfankeji.com/Article/details/gt2mfskrhfi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sweek.top/Article/details/gt2splailzf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gt2xcnmkhoj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gt2hbygtisv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sweek.top/Article/details/gt2vzngwcue.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhongyouzk.top/Article/details/gt2bhrwbxfj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xinyue.icu/Article/details/gt2dumkuhoc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.chenlongwang.top/Article/details/gt2ekfoilnq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sysykeji.top/Article/details/gt2mkllbeig.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gt2nsgaagmo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yj20258888.top/Article/details/gt2rljnlbcf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gt2nvrpkkei.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gt2vncylaiw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gt2nnrsabik.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwlebaar.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.tanke756.top/Article/details/gt2guelznuf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gt2rzhjidiy.html

Q SQL 专题                              90
来源：http://dali.gotoacloud.top/Article/details/gt2vfabcjcb.html

R Bash 专题                             80
来源：http://dali.tianlin.xyz/Article/details/gt2dvretqtm.html

S C / C++ 专题                          60
来源：http://dali.smart0.xyz/Article/details/gt2wotdnzcm.html

T 其他语言补充                          60
来源：http://dali.tian-w.cn/Article/details/gt2kznwcdmq.html


<!-- 参考信息 -->