代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hnxiangtu.top/Article/details/gt2mqevmnnw.html

[T59] Scala：循环
来源：http://dali.mhx1999.top/Article/details/gt2aommdotn.html

for (i <- 1 to 10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gt2hcgcmlhu.html

[T60] Scala：折叠
来源：http://dali.havefunace.top/Article/details/gt2wjzkhcbo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuanzhike.top/Article/details/gt2fcpszoyq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2aonisnln.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.fzhhl.top/Article/details/gt2zonbpgnu.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2fphcqjjm.html

[U01] Py：创建虚拟环境
来源：http://dali.chenzaomai.com/Article/details/gt2cbaogveg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangshuangyany.cn/Article/details/gt2cfydrfgc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jqgfzy.top/Article/details/gt2lfesltcn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yuxming.cn/Article/details/gt2zvlynnmw.html

[U03] Py：加载 .env 配置
来源：http://dali.bjfxy.top/Article/details/gt2ngaqawcp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenzaomai.com/Article/details/gt2wptgxokh.html

[U04] Py：变量调试打印
来源：http://dali.yuanzhike.top/Article/details/gt2myyqemgh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.fengsongda.top/Article/details/gt2rtpeibif.html

[U05] Py：列表去重且保序
来源：http://dali.yj20258.top/Article/details/gt2gustmsma.html

list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gt2smmyntfz.html

[U06] Py：合并两个字典
来源：http://dali.iojbl.cn/Article/details/gt2ydskbdrl.html

{**a, **b}
来源：http://dali.yj20258888.top/Article/details/gt2kwbbkzgx.html

[U07] Py：反转字典键值
来源：http://dali.snrcjt.cn/Article/details/gt2lsdmzvtx.html

{v: k for k, v in d.items()}
来源：http://dali.hnxiangtu.top/Article/details/gt2svwvnloo.html

[U08] Py：展平二维列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eolocurq.html

[y for x in nested for y in x]
来源：http://dali.c1oappe.top/Article/details/gt2jdkeftmr.html

[U09] Py：字典取最大值的键
来源：http://dali.hnqzz.top/Article/details/gt2jpgctfhm.html

max(d, key=d.get)
来源：http://dali.zhongyouzk.top/Article/details/gt2ptgobpcj.html

[U10] Py：按值排序字典
来源：http://dali.xinyue.icu/Article/details/gt2wegllgwg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj202588.top/Article/details/gt2nbpehlkd.html

[U11] Py：生成器表达式
来源：http://dali.iojbl.cn/Article/details/gt2velsyysi.html

(x * 2 for x in arr)
来源：http://dali.hnqzz.top/Article/details/gt2bnpawepu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ehwqpu.com/Article/details/gt2awiiomjm.html

Counter(arr).most_common(3)
来源：http://dali.fzhhl.top/Article/details/gt2lbmwjsnq.html

[U13] Py：固定长度队列
来源：http://dali.iojbl.cn/Article/details/gt2dxehbevt.html

deque(maxlen=10)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2genjekzv.html

[U14] Py：分组收集到列表
来源：http://dali.cheryme.top/Article/details/gt2fpdhxjcb.html

defaultdict(list)
来源：http://dali.chenlongwang.top/Article/details/gt2noxyftvc.html

[U15] Py：高精度计时
来源：http://dali.yuanzhike.top/Article/details/gt2msxygafz.html

t = time.perf_counter()
来源：http://dali.jqgufenzy.top/Article/details/gt2cjjixcqq.html

[U16] Py：命令行参数解析
来源：http://dali.hysaishi.cn/Article/details/gt2gnsepxof.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cdnleiting.top/Article/details/gt2nbvsiuuw.html

[U17] Py：初始化日志
来源：http://dali.jyoumei.cn/Article/details/gt2mhgpmhsn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gaohongyu789.top/Article/details/gt2zvxaeint.html

[U18] Py：预编译正则
来源：http://dali.xinyue.icu/Article/details/gt2qdurqflu.html

pat = re.compile(r"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gt2decyjkgk.html

[U19] Py：正则替换带回调
来源：http://dali.cheryme.top/Article/details/gt2yqvxqdxy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jlsjyb.cn/Article/details/gt2aommojdb.html

[U20] Py：缓存函数结果
来源：http://dali.jiagoushi.top/Article/details/gt2tquqhkzd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.9152youxi.cn/Article/details/gt2ympjvefj.html

[U21] Py：自定义上下文管理器
来源：http://dali.yanxiufei.cn/Article/details/gt2vylsndus.html

@contextlib.contextmanager
来源：http://dali.haohaochexian.top/Article/details/gt2hpdgjfis.html

[U22] Py：矩阵转置
来源：http://dali.snrcjt.cn/Article/details/gt2edjbxgrm.html

list(zip(*m))
来源：http://dali.iojbl.cn/Article/details/gt2tbarjrcw.html

[U23] Py：分块读取大文件
来源：http://dali.sxryk.cn/Article/details/gt2lywtwwbr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ybcxt.top/Article/details/gt2gepnggqa.html

[U24] Py：路径操作
来源：http://dali.cdnleiting.top/Article/details/gt2vyusfpgy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gt2xgiqybnw.html

[U25] Py：CSV 按字典读
来源：http://dali.ppjwa.cn/Article/details/gt2iykdftjl.html

csv.DictReader(f)
来源：http://dali.dashuyun.cn/Article/details/gt2tawrafmf.html

[U26] Py：并发下载
来源：http://dali.snrcjt.cn/Article/details/gt2ckfofmmr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.daria6918.cn/Article/details/gt2nhkitsid.html

[U27] Py：异步 HTTP
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iatzzrfe.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uuzavfxi.html

[U28] Py：类型别名
来源：http://dali.ivvv.top/Article/details/gt2abbsfvhp.html

UserId = int
来源：http://dali.zhengqikj.top/Article/details/gt2qupwmvfu.html

[U29] Py：属性校验
来源：http://dali.daria6918.cn/Article/details/gt2rvbkeggx.html

@property 与 @x.setter 配合
来源：http://dali.yj20258888.top/Article/details/gt2rlwluoqa.html

[U30] Py：数据类
来源：http://dali.gogol.net.cn/Article/details/gt2srsjeumh.html

@dataclass(slots=True)
来源：http://dali.kuanghao11.cn/Article/details/gt2morxmgse.html

[U31] Py：单测
来源：http://dali.cqqwz.cn/Article/details/gt2rywufmwg.html

python -m pytest -q
来源：http://dali.zhongyouzk.top/Article/details/gt2woerzasp.html

[U32] Py：代码格式化
来源：http://dali.tanke756.top/Article/details/gt2jqhyahng.html

ruff format . && ruff check --fix .
来源：http://dali.mhx1999.top/Article/details/gt2ojiqoinb.html

[U33] Py：打包发布
来源：http://dali.vqdsnc.cn/Article/details/gt2sxlkdfrt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yongpay.top/Article/details/gt2uqtvoohi.html

[U34] Py：判断编码
来源：http://dali.gaohongyu789.top/Article/details/gt2zesmiujg.html

chardet.detect(raw)
来源：http://dali.chenzaomai.com/Article/details/gt2ojhwrbhh.html

[U35] Py：发送邮件
来源：http://dali.fzhhl.top/Article/details/gt2lqvknunp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2davufizk.html

[U36] Py：定时任务
来源：http://dali.aibaodan.cn/Article/details/gt2lfrllkrl.html

schedule.every(10).minutes.do(job)
来源：http://dali.hysaishi.cn/Article/details/gt2zpqefots.html

[U37] Py：读写 Excel
来源：http://dali.kuanghao11.cn/Article/details/gt2kvhiugwi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shuidangran.top/Article/details/gt2xyokfzfg.html

[U38] Py：获取脚本所在目录
来源：http://dali.cdnleiting.top/Article/details/gt2kkjkgyeo.html

Path(__file__).resolve().parent
来源：http://dali.haohaochexian.top/Article/details/gt2nuhlialj.html

[U39] Py：判断是否在交互环境
来源：http://dali.guowangkeji.top/Article/details/gt2pxcoqffg.html

sys.stdout.isatty()
来源：http://dali.gogol.net.cn/Article/details/gt2xybydwer.html

[U40] Py：打印到标准错误
来源：http://dali.jinqigfzy.top/Article/details/gt2esojnmnx.html

print("err", file=sys.stderr)
来源：http://dali.ivvv.top/Article/details/gt2qbjfjpfc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.guowangkeji.top/Article/details/gt2iczltikz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.wangshuangyany.cn/Article/details/gt2jkilsmrz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.aibaodan.cn/Article/details/gt2lgdtcdui.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yongpay.top/Article/details/gt2enhiubgm.html

[U43] PHP：声明命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gt2fuailujd.html

namespace App\Http;
来源：http://dali.zdqjudy.top/Article/details/gt2yilsygzl.html

[U44] PHP：开启严格类型
来源：http://dali.hnxiangtu.top/Article/details/gt2mtdrkmjn.html

declare(strict_types=1);
来源：http://dali.redwolf501.top/Article/details/gt2gccycdbq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.tian-w.cn/Article/details/gt2ldhlnvpk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2hkjmnojo.html

[U46] PHP：可空类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xdbclryk.html

?string $name = null
来源：http://dali.dashuyun.cn/Article/details/gt2hdrvvvzs.html

[U47] PHP：联合类型
来源：http://dali.hammf.cn/Article/details/gt2pufrxlkq.html

int|string $id
来源：http://dali.c1oappe.top/Article/details/gt2fuyhcbhd.html

[U48] PHP：纯枚举
来源：http://dali.gotoacloud.top/Article/details/gt2agbybyuh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinqigufen.top/Article/details/gt2ejvxxwdk.html

[U49] PHP：只读属性
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kjhlggxk.html

public readonly string $name
来源：http://dali.chenlongwang.top/Article/details/gt2racfzohx.html

[U50] PHP：构造器属性提升
来源：http://dali.xuetiantiany.cn/Article/details/gt2kxebocrh.html

public function __construct(private int $id) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2sgyubarw.html

[U51] PHP：数组解构
来源：http://dali.hywenlv.cn/Article/details/gt2ldfeckwb.html

[$a, $b] = $arr;
来源：http://dali.hnqzz.top/Article/details/gt2jgongwya.html

[U52] PHP：箭头函数
来源：http://dali.sweek.top/Article/details/gt2lipcbwnk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2slpdgxic.html

[U53] PHP：空合并运算符
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2buwqcdcv.html

$v = $a ?? $b ?? "default";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fhuvvfem.html

[U54] PHP：空安全调用
来源：http://dali.jinqigufen.top/Article/details/gt2jisbdfdv.html

$obj?->method()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ztzoubij.html

[U55] PHP：match 表达式
来源：http://dali.yj202588.top/Article/details/gt2ggxodtuf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xinyue.icu/Article/details/gt2vvhobsiq.html

[U56] PHP：命名参数
来源：http://dali.daxiang520.top/Article/details/gt2hkcxtyla.html

f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gt2nzkwylim.html

[U57] PHP：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gt2fcbigrlo.html

"值: {$a}"
来源：http://dali.chenzaomai.com/Article/details/gt2zovfuvdr.html

[U58] PHP：数组三件套
来源：http://dali.guowangkeji.top/Article/details/gt2kcpjdtgw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2xnejmxja.html

[U59] PHP：自定义排序
来源：http://dali.jlsjyb.cn/Article/details/gt2ifooohsi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jyoumei.cn/Article/details/gt2qlevmvtx.html

[U60] PHP：JSON 编解码
来源：http://dali.hongshengwenyu.top/Article/details/gt2rjmdkwrf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.guowangkeji.top/Article/details/gt2huvzxueh.html

[U61] PHP：正则
来源：http://dali.tian-w.cn/Article/details/gt2xgwhqkzq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gt2digymxmt.html

[U62] PHP：日期对象
来源：http://dali.tanke756.top/Article/details/gt2ipvrsvvd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jqgufenzy.top/Article/details/gt2rkifbyfi.html

[U63] PHP：文件读写
来源：http://dali.yangfankeji.com/Article/details/gt2kocoopbz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jlsjyb.cn/Article/details/gt2klobhnyn.html

[U64] PHP：目录遍历
来源：http://dali.xylfe.cn/Article/details/gt2fdpceicq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hfpthk.cn/Article/details/gt2naiftbim.html

[U65] PHP：会话
来源：http://dali.redwolf501.top/Article/details/gt2pkelwnns.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cheryme.top/Article/details/gt2crqwchbv.html

[U66] PHP：设置 Cookie
来源：http://dali.kuanghao11.cn/Article/details/gt2nrnrzzih.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.wangdashe.top/Article/details/gt2qgpxjseb.html

[U67] PHP：处理文件上传
来源：http://dali.jqgufenzy.top/Article/details/gt2vndcyprl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.0kj1m.cn/Article/details/gt2uxgyahwo.html

[U68] PHP：PDO 连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2spjllanf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zdqjudy.top/Article/details/gt2pydptcgj.html

[U69] PHP：PDO 预处理
来源：http://dali.cashguo.top/Article/details/gt2okdfjrom.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mxpgtfmi.html

[U70] PHP：PDO 事务
来源：http://dali.yj20258.top/Article/details/gt2jrbmkxda.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.meibo888.top/Article/details/gt2yhlcadvt.html

[U71] PHP：抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ugbwcbjo.html

throw new RuntimeException("失败", 500);
来源：http://dali.hammf.cn/Article/details/gt2mpcacxll.html

[U72] PHP：写错误日志
来源：http://dali.wangdashe.top/Article/details/gt2rpsithzg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yvedp.cn/Article/details/gt2qllasaxp.html

[U73] PHP：读取 ini 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwmfixvg.html

parse_ini_file("config.ini", true)
来源：http://dali.andypj.xyz/Article/details/gt2eobtrraj.html

[U74] PHP：读取环境变量
来源：http://dali.yuxming.cn/Article/details/gt2neumplwv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.9152youxi.cn/Article/details/gt2hrlxhycd.html

[U75] PHP：依赖注入
来源：http://dali.pycfn.com/Article/details/gt2axsebett.html

composer require psr/container
来源：http://dali.sweek.top/Article/details/gt2sviyhrje.html

[U76] PHP：简单路由
来源：http://dali.cucudq.cn/Article/details/gt2nbiiscwx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.gzhubu.top/Article/details/gt2pznyshzo.html

[U77] PHP：模板渲染
来源：http://dali.yuanzhike.top/Article/details/gt2ofvumeep.html

composer require twig/twig
来源：http://dali.gogol.net.cn/Article/details/gt2cgadztst.html

[U78] PHP：单元测试
来源：http://dali.chenlongwang.top/Article/details/gt2vjjdkbku.html

composer require --dev phpunit/phpunit
来源：http://dali.vqdsnc.cn/Article/details/gt2ilxewbnf.html

[U79] PHP：静态分析
来源：http://dali.gotoacloud.top/Article/details/gt2mrchlgpv.html

composer require --dev phpstan/phpstan
来源：http://dali.nanxinkj.top/Article/details/gt2ntznfmhw.html

[U80] PHP：代码规范修复
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hqrkrcbw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.fengsongda.top/Article/details/gt2nmqgvqnw.html

[U81] JS：初始化项目
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dnvzphnl.html

npm init -y;  npm i express
来源：http://dali.aizwys.cn/Article/details/gt2wbafqmys.html

[U82] JS：package.json 脚本
来源：http://dali.hywenlv.cn/Article/details/gt2cpcoiezs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hysaishi.cn/Article/details/gt2vdwuacqs.html

[U83] JS：ES Module 导入导出
来源：http://dali.mhx1999.top/Article/details/gt2qmobvslt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hnqzz.top/Article/details/gt2ycnkhzeb.html

[U84] JS：CommonJS 写法
来源：http://dali.yj202588.top/Article/details/gt2leujrnql.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.sufxvd.cn/Article/details/gt2quusvilj.html

[U85] JS：可选链
来源：http://dali.hywenlv.cn/Article/details/gt2qribbbgq.html

a?.b?.c
来源：http://dali.tian-w.cn/Article/details/gt2zdwrywdx.html

[U86] JS：空值合并
来源：http://dali.havefunace.top/Article/details/gt2lqtzrvru.html

a ?? b
来源：http://dali.nwbrower.top/Article/details/gt2mwefoqir.html

[U87] JS：解构默认值
来源：http://dali.tianlin.xyz/Article/details/gt2eaudzyme.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yj202588.top/Article/details/gt2hdhwedom.html

[U88] JS：对象展开合并
来源：http://dali.yanxiufei.cn/Article/details/gt2gapfrogh.html

{ ...a, ...b }
来源：http://dali.jianghu66.top/Article/details/gt2lsahwwoe.html

[U89] JS：数组去重
来源：http://dali.haohaochexian.top/Article/details/gt2uwouurxp.html

[...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gt2pswztyuq.html

[U90] JS：数字数组排序
来源：http://dali.jinqigfzy.top/Article/details/gt2luauxldc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gt2wnrvnkpf.html

[U91] JS：对象键值遍历
来源：http://dali.hfpthk.cn/Article/details/gt2ychlujgs.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj202588.top/Article/details/gt2gseziaqx.html

[U92] JS：深拷贝
来源：http://dali.zycfv.cn/Article/details/gt2ungbjxkk.html

structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gt2gottvmpg.html

[U93] JS：模板字符串
来源：http://dali.yj20258.top/Article/details/gt2fqndsoti.html

`共 ${n} 条`
来源：http://dali.nanxinkj.top/Article/details/gt2jtkkhcls.html

[U94] JS：箭头函数
来源：http://dali.chenzaomai.com/Article/details/gt2lbvgunge.html

const double = x => x * 2;
来源：http://dali.hammf.cn/Article/details/gt2grqwrrpl.html

[U95] JS：Promise 包装
来源：http://dali.xylfe.cn/Article/details/gt2sshaxphz.html

new Promise((resolve, reject) => {})
来源：http://dali.meibo888.top/Article/details/gt2mvknohlu.html

[U96] JS：async/await 与异常
来源：http://dali.nwbrower.top/Article/details/gt2xeonwnnw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gt2uxtwjhqo.html

[U97] JS：并发请求
来源：http://dali.xuanzx.com/Article/details/gt2axhuvmoj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gt2cysxznvj.html

[U98] JS：fetch 带 JSON
来源：http://dali.wangdashe.top/Article/details/gt2jjcoxntn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmfailbn.html

[U99] JS：事件监听
来源：http://dali.guannengcc.top/Article/details/gt2ofzlzmqt.html

el.addEventListener("click", e => {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rbfacbhd.html

[U100] JS：DOM 查询
来源：http://dali.dianchejie.cn/Article/details/gt2deejqnsp.html

document.querySelector(".item")
来源：http://dali.gaohongyu789.top/Article/details/gt2kqlfljza.html

[U101] JS：classList 操作
来源：http://dali.nanxinkj.top/Article/details/gt2cryjzrgu.html

el.classList.toggle("active")
来源：http://dali.sysykeji.top/Article/details/gt2jbkidhig.html

[U102] JS：本地存储
来源：http://dali.daxiang520.top/Article/details/gt2dbvpimvh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nwbrower.top/Article/details/gt2huczdmbf.html

[U103] JS：定时器
来源：http://dali.chenlongwang.top/Article/details/gt2fqstbkfg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jyoumei.cn/Article/details/gt2dhxkglpn.html

[U104] JS：防抖
来源：http://dali.meibo888.top/Article/details/gt2ucokterc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gt2juwtlhac.html

[U105] JS：节流
来源：http://dali.yangfankeji.com/Article/details/gt2drmrafsl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yueranfly.top/Article/details/gt2jetlsujz.html

[U106] JS：日期格式化
来源：http://dali.aizwys.cn/Article/details/gt2lurrygvu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.9152youxi.cn/Article/details/gt2hsutjurr.html

[U107] JS：数字千分位
来源：http://dali.dashuyun.cn/Article/details/gt2kyznbxny.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2marqacay.html

[U108] JS：随机整数
来源：http://dali.hongshengwenyu.top/Article/details/gt2jluckjha.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yanxiufei.cn/Article/details/gt2fmrfkwol.html

[U109] JS：数组分组
来源：http://dali.zhengqikj.top/Article/details/gt2ylbzykno.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gt2lyqdcuqf.html

[U110] JS：数组分块
来源：http://dali.guannengcc.top/Article/details/gt2jdohhnew.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.aibaodan.cn/Article/details/gt2lxzoljkj.html

[U111] JS：对象转 Map
来源：http://dali.nwbrower.top/Article/details/gt2pdflkiex.html

new Map(Object.entries(obj))
来源：http://dali.hnxiangtu.top/Article/details/gt2bdxvjipq.html

[U112] JS：字符串补位
来源：http://dali.hywenlv.cn/Article/details/gt2pkyzdrul.html

"7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gt2qbsmvctq.html

[U113] JS：正则替换全部
来源：http://dali.iojbl.cn/Article/details/gt2humiwwpv.html

s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2bfhmxqsb.html

[U114] JS：JSON 深比较
来源：http://dali.yueranfly.top/Article/details/gt2hudnbica.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gt2ygihevwz.html

[U115] JS：生成 UUID
来源：http://dali.wangshuangyany.cn/Article/details/gt2pftedrlq.html

crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gt2jgwvzohk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.iojbl.cn/Article/details/gt2logvrzuf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daxiang520.top/Article/details/gt2bfddljsd.html

[U117] JS：单元测试
来源：http://dali.jqgfzy.top/Article/details/gt2twxbroih.html

npm i -D vitest;  npx vitest
来源：http://dali.hnxiangtu.top/Article/details/gt2liazykwt.html

[U118] JS：开发服务器
来源：http://dali.shangyingyoupin.top/Article/details/gt2brtlsugb.html

npm i -D vite;  npx vite
来源：http://dali.quarkkingdee.top/Article/details/gt2telldobl.html

[U119] JS：生产构建
来源：http://dali.hnqzz.top/Article/details/gt2qjjobtlv.html

npx vite build
来源：http://dali.guannengcc.top/Article/details/gt2jkkpjahr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.guannengcc.top/Article/details/gt2sqpzrfyq.html

import.meta.env.VITE_API_URL
来源：http://dali.xylfe.cn/Article/details/gt2vgsfayuz.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2fkzpqceh.html

统计汇总
来源：http://dali.yangfankeji.com/Article/details/gt2nyosfxex.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ilpkmrkt.html

按语言统计（条）：
来源：http://dali.ydzc1.top/Article/details/gt2tawgbawv.html

Python ......... 252
来源：http://dali.quarkkingdee.top/Article/details/gt2ilmatrjx.html

PHP ............ 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fuxylbtj.html

JavaScript ..... 252
来源：http://dali.shangyingyoupin.top/Article/details/gt2sccvdtej.html

TypeScript ..... 212
来源：http://dali.guannengcc.top/Article/details/gt2nncmkcxi.html

Java ........... 212
来源：http://dali.chenjidiqi.icu/Article/details/gt2edgjgxtz.html

Go ............. 212
来源：http://dali.zhongyouzk.top/Article/details/gt2eldpceyq.html

Ruby ........... 212
来源：http://dali.tianlin.xyz/Article/details/gt2nlzrivjk.html

C# ............. 212
来源：http://dali.chenzaomai.com/Article/details/gt2oloyugip.html

C .............. 30
来源：http://dali.zhiwuduotai.top/Article/details/gt2oepwwfjy.html

C++ ............ 30
来源：http://dali.wangdashe.top/Article/details/gt2zvfpzjia.html

SQL ............ 90
来源：http://dali.c1oappe.top/Article/details/gt2ygtdilya.html

Bash ........... 80
来源：http://dali.pycfn.com/Article/details/gt2btvldoqk.html

Kotlin ......... 15
来源：http://dali.yanxiufei.cn/Article/details/gt2pesqzrdp.html

Swift .......... 15
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dyxmhdfk.html

Lua ............ 10
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gcqsmwun.html

Perl ........... 10
来源：http://dali.wangshuangyany.cn/Article/details/gt2mgffxqdv.html

Scala .......... 10
来源：http://dali.yonumen.top/Article/details/gt2bgyruvbc.html

------------------------------------
来源：http://dali.cheryme.top/Article/details/gt2vpablxob.html

合计 ........... 2106 条
来源：http://dali.cucudq.cn/Article/details/gt2mwbgrstg.html

按章节统计：
来源：http://dali.daria6918.cn/Article/details/gt2obctuxsy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gzhubu.top/Article/details/gt2erocxbha.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.chenlongwang.top/Article/details/gt2ejrscxbu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gt2eogzbiqn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.fengsongda.top/Article/details/gt2gqctoyvi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gogol.net.cn/Article/details/gt2hugwmfvm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.daxiang520.top/Article/details/gt2sdwomdug.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gt2jprypmlg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jiagoushi.top/Article/details/gt2mjdtltmp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hxfbvatz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhoulong.xyz/Article/details/gt2oxhcpras.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gt2klmsvnzw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gt2vmusjihn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gt2zbjtstmw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ydzc1.top/Article/details/gt2ajjaeuun.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.kuanghao11.cn/Article/details/gt2stiqwtia.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gt2mqzwgzpg.html

Q SQL 专题                              90
来源：http://dali.fzhhl.top/Article/details/gt2dxdeigkp.html

R Bash 专题                             80
来源：http://dali.cqqwz.cn/Article/details/gt2iagbegfg.html

S C / C++ 专题                          60
来源：http://dali.jinqigfzy.top/Article/details/gt2nlysjdfz.html

T 其他语言补充                          60
来源：http://dali.fzhhl.top/Article/details/gt2rargouts.html

U 高频实用片段                         120
来源：http://dali.daria6918.cn/Article/details/gt2pbvmussv.html

------------------------------------
来源：http://dali.meibo888.top/Article/details/gt2lqvsnhjl.html

合计                                  2106 条
来源：http://dali.yvedp.cn/Article/details/gt2peulyvog.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gt2ujznlevs.html

使用提醒
来源：http://dali.daxiang520.top/Article/details/gt2cdylwscv.html

--------------------------------------------------------------------------------
来源：http://dali.guannengcc.top/Article/details/gt2ldpqgtfp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nanxinkj.top/Article/details/gt2svnrreli.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.andypj.xyz/Article/details/gt2ghzmgslj.html


<!-- 参考信息 -->