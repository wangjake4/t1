代发 wailian999

[U03] Py：加载 .env 配置
来源：http://dali.birdmap.top/Article/details/gt2qvakbqgg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cheryme.top/Article/details/gt2qejpypva.html

[U04] Py：变量调试打印
来源：http://dali.zycfv.cn/Article/details/gt2faapixyt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhiwuduotai.top/Article/details/gt2ujawvxof.html

[U05] Py：列表去重且保序
来源：http://dali.hnxiangtu.top/Article/details/gt2rkenllcy.html

list(dict.fromkeys(arr))
来源：http://dali.bjfxy.top/Article/details/gt2jxgstjqh.html

[U06] Py：合并两个字典
来源：http://dali.chenlongwang.top/Article/details/gt2uybzifcj.html

{**a, **b}
来源：http://dali.snrcjt.cn/Article/details/gt2rxxanovx.html

[U07] Py：反转字典键值
来源：http://dali.zdqjudy.top/Article/details/gt2yqvtgvsk.html

{v: k for k, v in d.items()}
来源：http://dali.cucudq.cn/Article/details/gt2zgacopfb.html

[U08] Py：展平二维列表
来源：http://dali.dianchejie.cn/Article/details/gt2bxinjchb.html

[y for x in nested for y in x]
来源：http://dali.andypj.xyz/Article/details/gt2lqxbiujg.html

[U09] Py：字典取最大值的键
来源：http://dali.tanke756.top/Article/details/gt2oslhexme.html

max(d, key=d.get)
来源：http://dali.andypj.xyz/Article/details/gt2ghhopjpn.html

[U10] Py：按值排序字典
来源：http://dali.cqqwz.cn/Article/details/gt2dvkijmaq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenjidiqi.icu/Article/details/gt2wliqiaul.html

[U11] Py：生成器表达式
来源：http://dali.feifeiyinyue.top/Article/details/gt2kiqncfjp.html

(x * 2 for x in arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yedbpytc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinqigufen.top/Article/details/gt2sxgfdmqb.html

Counter(arr).most_common(3)
来源：http://dali.hfpthk.cn/Article/details/gt2pzpdntnk.html

[U13] Py：固定长度队列
来源：http://dali.wangdashe.top/Article/details/gt2qmsmthuc.html

deque(maxlen=10)
来源：http://dali.haohaochexian.top/Article/details/gt2oxekkpgc.html

[U14] Py：分组收集到列表
来源：http://dali.jqgfzy.top/Article/details/gt2eylrkcbz.html

defaultdict(list)
来源：http://dali.ivvv.top/Article/details/gt2tajpanmo.html

[U15] Py：高精度计时
来源：http://dali.dashuyun.cn/Article/details/gt2vxrziaiv.html

t = time.perf_counter()
来源：http://dali.aibaodan.cn/Article/details/gt2gjhyhilk.html

[U16] Py：命令行参数解析
来源：http://dali.hywenlv.cn/Article/details/gt2igyvqvua.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jiagoushi.top/Article/details/gt2adpjuyxz.html

[U17] Py：初始化日志
来源：http://dali.daxiang520.top/Article/details/gt2mntayawk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.iojbl.cn/Article/details/gt2gfniilbe.html

[U18] Py：预编译正则
来源：http://dali.316326.xyz/Article/details/gt2oxumbzvm.html

pat = re.compile(r"\d+")
来源：http://dali.yongpay.top/Article/details/gt2kbgxmgki.html

[U19] Py：正则替换带回调
来源：http://dali.andypj.xyz/Article/details/gt2thpybluq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zdqjudy.top/Article/details/gt2jxsnvjiu.html

[U20] Py：缓存函数结果
来源：http://dali.guannengcc.top/Article/details/gt2qngzaakb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zdqjudy.top/Article/details/gt2xkaisbuj.html

[U21] Py：自定义上下文管理器
来源：http://dali.feifeiyinyue.top/Article/details/gt2futbryyr.html

@contextlib.contextmanager
来源：http://dali.xziqi.cn/Article/details/gt2ijvikbot.html

[U22] Py：矩阵转置
来源：http://dali.zhixingplan.top/Article/details/gt2rlwvcoti.html

list(zip(*m))
来源：http://dali.zycfv.cn/Article/details/gt2tazsafeh.html

[U23] Py：分块读取大文件
来源：http://dali.xziqi.cn/Article/details/gt2volsmhfv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yongpay.top/Article/details/gt2soddvegv.html

[U24] Py：路径操作
来源：http://dali.daxiang520.top/Article/details/gt2dhejrmrt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gt2vmaxzeyw.html

[U25] Py：CSV 按字典读
来源：http://dali.smart0.xyz/Article/details/gt2rqylahgr.html

csv.DictReader(f)
来源：http://dali.hnqzz.top/Article/details/gt2ejmnowzy.html

[U26] Py：并发下载
来源：http://dali.fzhhl.top/Article/details/gt2pjmdvxhe.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gcoqffpt.html

[U27] Py：异步 HTTP
来源：http://dali.hysaishi.cn/Article/details/gt2kbwcrbtd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jiagoushi.top/Article/details/gt2pexbglvw.html

[U28] Py：类型别名
来源：http://dali.zhiwuduotai.top/Article/details/gt2plkfffse.html

UserId = int
来源：http://dali.ydzc1.top/Article/details/gt2vmthdiex.html

[U29] Py：属性校验
来源：http://dali.hywenlv.cn/Article/details/gt2oifjzlan.html

@property 与 @x.setter 配合
来源：http://dali.yvedp.cn/Article/details/gt2wojljuzy.html

[U30] Py：数据类
来源：http://dali.quarkkingdee.top/Article/details/gt2rikauozu.html

@dataclass(slots=True)
来源：http://dali.wangshuangyany.cn/Article/details/gt2divucnjy.html

[U31] Py：单测
来源：http://dali.wangshuangyany.cn/Article/details/gt2feqslurv.html

python -m pytest -q
来源：http://dali.yuxming.cn/Article/details/gt2bupmsfuu.html

[U32] Py：代码格式化
来源：http://dali.guowangkeji.top/Article/details/gt2wcwdhbph.html

ruff format . && ruff check --fix .
来源：http://dali.zhongyouzk.top/Article/details/gt2piulnzoz.html

[U33] Py：打包发布
来源：http://dali.havefunace.top/Article/details/gt2ukltqkal.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ehwqpu.com/Article/details/gt2oivzophc.html

[U34] Py：判断编码
来源：http://dali.pycfn.com/Article/details/gt2vxghlksi.html

chardet.detect(raw)
来源：http://dali.iojbl.cn/Article/details/gt2bnxmjcht.html

[U35] Py：发送邮件
来源：http://dali.xuanzx.com/Article/details/gt2pjaevxgt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.dashuyun.cn/Article/details/gt2bwafmlti.html

[U36] Py：定时任务
来源：http://dali.ydzc1.top/Article/details/gt2sldcvdjj.html

schedule.every(10).minutes.do(job)
来源：http://dali.yuxming.cn/Article/details/gt2ewbitipv.html

[U37] Py：读写 Excel
来源：http://dali.tian-w.cn/Article/details/gt2rlogicbx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj20258.top/Article/details/gt2eiwjcjkv.html

[U38] Py：获取脚本所在目录
来源：http://dali.sysykeji.top/Article/details/gt2fhfcivgo.html

Path(__file__).resolve().parent
来源：http://dali.jyoumei.cn/Article/details/gt2wifrziut.html

[U39] Py：判断是否在交互环境
来源：http://dali.wangdashe.top/Article/details/gt2syinwkeu.html

sys.stdout.isatty()
来源：http://dali.daxiang520.top/Article/details/gt2xprthvgx.html

[U40] Py：打印到标准错误
来源：http://dali.pycfn.com/Article/details/gt2ffoewijn.html

print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gt2bbwuvezb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj20258.top/Article/details/gt2fqyzjyqx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hammf.cn/Article/details/gt2nbuswoni.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hywenlv.cn/Article/details/gt2ojddofdo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xziqi.cn/Article/details/gt2ayajrxkx.html

[U43] PHP：声明命名空间
来源：http://dali.xinyue.icu/Article/details/gt2anvxquyu.html

namespace App\Http;
来源：http://dali.yvedp.cn/Article/details/gt2wbolyvkw.html

[U44] PHP：开启严格类型
来源：http://dali.wangdashe.top/Article/details/gt2tzejntzf.html

declare(strict_types=1);
来源：http://dali.pycfn.com/Article/details/gt2olrkhdtn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinqigfzy.top/Article/details/gt2qkstfcyr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rlwrgbep.html

[U46] PHP：可空类型
来源：http://dali.xylfe.cn/Article/details/gt2eenneire.html

?string $name = null
来源：http://dali.yuanzhike.top/Article/details/gt2ngwprgxa.html

[U47] PHP：联合类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2tnqempmw.html

int|string $id
来源：http://dali.yongpay.top/Article/details/gt2xtscmtcs.html

[U48] PHP：纯枚举
来源：http://dali.iojbl.cn/Article/details/gt2bpsikmio.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hysaishi.cn/Article/details/gt2vxhkbypn.html

[U49] PHP：只读属性
来源：http://dali.zhoulong.xyz/Article/details/gt2mzsvnnkf.html

public readonly string $name
来源：http://dali.feifeiyinyue.top/Article/details/gt2prpahmcx.html

[U50] PHP：构造器属性提升
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xdcaheeg.html

public function __construct(private int $id) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2leusflse.html

[U51] PHP：数组解构
来源：http://dali.yj20258888.top/Article/details/gt2axpjcfvq.html

[$a, $b] = $arr;
来源：http://dali.yuanzhike.top/Article/details/gt2ibzfimvi.html

[U52] PHP：箭头函数
来源：http://dali.gzhubu.top/Article/details/gt2famflurk.html

$double = fn($x) => $x * 2;
来源：http://dali.iojbl.cn/Article/details/gt2afsmpwnp.html

[U53] PHP：空合并运算符
来源：http://dali.zhiwuduotai.top/Article/details/gt2qwhsgjzk.html

$v = $a ?? $b ?? "default";
来源：http://dali.9152youxi.cn/Article/details/gt2idarwqzu.html

[U54] PHP：空安全调用
来源：http://dali.havefunace.top/Article/details/gt2apsnamco.html

$obj?->method()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lyxhbfln.html

[U55] PHP：match 表达式
来源：http://dali.wangshuangyany.cn/Article/details/gt2gynwgrue.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.daria6918.cn/Article/details/gt2cyjnovhj.html

[U56] PHP：命名参数
来源：http://dali.yuanzhike.top/Article/details/gt2woztyloh.html

f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2htzyzfbf.html

[U57] PHP：字符串插值
来源：http://dali.gzhubu.top/Article/details/gt2knzcpvya.html

"值: {$a}"
来源：http://dali.guannengcc.top/Article/details/gt2fwqygyqy.html

[U58] PHP：数组三件套
来源：http://dali.chenjidiqi.icu/Article/details/gt2lwduvotw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhixingplan.top/Article/details/gt2qyxsrybk.html

[U59] PHP：自定义排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hidhcwbe.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gt2rpujknjs.html

[U60] PHP：JSON 编解码
来源：http://dali.zhongyouzk.top/Article/details/gt2begxocbc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.0kj1m.cn/Article/details/gt2ulilcyiw.html

[U61] PHP：正则
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cbrfcsor.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2alruexpo.html

[U62] PHP：日期对象
来源：http://dali.yvedp.cn/Article/details/gt2oenhhono.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xinyue.icu/Article/details/gt2gmribxng.html

[U63] PHP：文件读写
来源：http://dali.sxryk.cn/Article/details/gt2dhwjpcpd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinqigfzy.top/Article/details/gt2yywvqhof.html

[U64] PHP：目录遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2panyewyo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shuidangran.top/Article/details/gt2klfijvub.html

[U65] PHP：会话
来源：http://dali.smart0.xyz/Article/details/gt2cxwplrsn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2axqrdcnb.html

[U66] PHP：设置 Cookie
来源：http://dali.jqgufenzy.top/Article/details/gt2yzwxqyiv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.daria6918.cn/Article/details/gt2rpgynedj.html

[U67] PHP：处理文件上传
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jnpijemn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2sizexqnz.html

[U68] PHP：PDO 连接
来源：http://dali.yj20258.top/Article/details/gt2rpoadjmg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hnqzz.top/Article/details/gt2eaqhdpkm.html

[U69] PHP：PDO 预处理
来源：http://dali.sysykeji.top/Article/details/gt2emaijrpi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shzxlz.cn/Article/details/gt2dvxbnvwu.html

[U70] PHP：PDO 事务
来源：http://dali.guannengcc.top/Article/details/gt2apzcyndr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.pycfn.com/Article/details/gt2ryhzarij.html

[U71] PHP：抛出异常
来源：http://dali.yuxming.cn/Article/details/gt2lmlrppxt.html

throw new RuntimeException("失败", 500);
来源：http://dali.shangyingyoupin.top/Article/details/gt2dfqqojcn.html

[U72] PHP：写错误日志
来源：http://dali.andypj.xyz/Article/details/gt2xawzmwtg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zdqjudy.top/Article/details/gt2ombuavrf.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhixingplan.top/Article/details/gt2mjshrnvd.html

parse_ini_file("config.ini", true)
来源：http://dali.yj20258.top/Article/details/gt2gguaccoc.html

[U74] PHP：读取环境变量
来源：http://dali.hammf.cn/Article/details/gt2zpveajzk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.9152youxi.cn/Article/details/gt2kjqfoxui.html

[U75] PHP：依赖注入
来源：http://dali.jianghu66.top/Article/details/gt2zrrjxoeb.html

composer require psr/container
来源：http://dali.bjfxy.top/Article/details/gt2deurdqly.html

[U76] PHP：简单路由
来源：http://dali.smart0.xyz/Article/details/gt2ibtixutv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shuidangran.top/Article/details/gt2hldqcgdq.html

[U77] PHP：模板渲染
来源：http://dali.zhiwuduotai.top/Article/details/gt2jycqbnve.html

composer require twig/twig
来源：http://dali.gaohongyu789.top/Article/details/gt2wgvlnhkr.html

[U78] PHP：单元测试
来源：http://dali.xziqi.cn/Article/details/gt2tsaywmys.html

composer require --dev phpunit/phpunit
来源：http://dali.yj202588.top/Article/details/gt2rdphnzmh.html

[U79] PHP：静态分析
来源：http://dali.ybcxt.top/Article/details/gt2rgvrqwaq.html

composer require --dev phpstan/phpstan
来源：http://dali.ivvv.top/Article/details/gt2bkturnbw.html

[U80] PHP：代码规范修复
来源：http://dali.nanxuanxn.top/Article/details/gt2igkuoljw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhzzealj.html

[U81] JS：初始化项目
来源：http://dali.hywenlv.cn/Article/details/gt2lalptwsy.html

npm init -y;  npm i express
来源：http://dali.jlsjyb.cn/Article/details/gt2qplukxpv.html

[U82] JS：package.json 脚本
来源：http://dali.chenjidiqi.icu/Article/details/gt2hailosjp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.feifeiyinyue.top/Article/details/gt2oqrfowwa.html

[U83] JS：ES Module 导入导出
来源：http://dali.jqgufenzy.top/Article/details/gt2sydpdhhm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.feifeiyinyue.top/Article/details/gt2cufeodat.html

[U84] JS：CommonJS 写法
来源：http://dali.tianlin.xyz/Article/details/gt2ejyzjnqz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hysaishi.cn/Article/details/gt2phkthwqy.html

[U85] JS：可选链
来源：http://dali.feifeiyinyue.top/Article/details/gt2duznpess.html

a?.b?.c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbtlfztg.html

[U86] JS：空值合并
来源：http://dali.pycfn.com/Article/details/gt2pgcndpiv.html

a ?? b
来源：http://dali.vqdsnc.cn/Article/details/gt2axnkontt.html

[U87] JS：解构默认值
来源：http://dali.mhx1999.top/Article/details/gt2hpnsrevl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shangyingyoupin.top/Article/details/gt2txvqfotc.html

[U88] JS：对象展开合并
来源：http://dali.daxiang520.top/Article/details/gt2asqqlkof.html

{ ...a, ...b }
来源：http://dali.hongshengwenyu.top/Article/details/gt2fujrirhv.html

[U89] JS：数组去重
来源：http://dali.tanke756.top/Article/details/gt2xwtpffkd.html

[...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gt2cdehyaol.html

[U90] JS：数字数组排序
来源：http://dali.quarkkingdee.top/Article/details/gt2mikyvtdp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gt2mxeqopoq.html

[U91] JS：对象键值遍历
来源：http://dali.jianghu66.top/Article/details/gt2ewugyaat.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.guannengcc.top/Article/details/gt2hptksgof.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qdacwutz.html

structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gt2ajurvrpf.html

[U93] JS：模板字符串
来源：http://dali.tanke756.top/Article/details/gt2qavaolie.html

`共 ${n} 条`
来源：http://dali.zhiwuduotai.top/Article/details/gt2gbllrlbn.html

[U94] JS：箭头函数
来源：http://dali.tanke756.top/Article/details/gt2ktvizhlc.html

const double = x => x * 2;
来源：http://dali.yj20258.top/Article/details/gt2noiglziy.html

[U95] JS：Promise 包装
来源：http://dali.yj20258888.top/Article/details/gt2tdarfccg.html

new Promise((resolve, reject) => {})
来源：http://dali.meibo888.top/Article/details/gt2pigitsfo.html

[U96] JS：async/await 与异常
来源：http://dali.hammf.cn/Article/details/gt2ffsglfqe.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gt2hnjqlait.html

[U97] JS：并发请求
来源：http://dali.bjfxy.top/Article/details/gt2jnbgjyyg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gt2cohdruan.html

[U98] JS：fetch 带 JSON
来源：http://dali.ppjwa.cn/Article/details/gt2ertsadwi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jianghu66.top/Article/details/gt2mmunvbfn.html

[U99] JS：事件监听
来源：http://dali.yanxiufei.cn/Article/details/gt2czcuvwfs.html

el.addEventListener("click", e => {})
来源：http://dali.hnxiangtu.top/Article/details/gt2gsenbahz.html

[U100] JS：DOM 查询
来源：http://dali.aizwys.cn/Article/details/gt2vdwopcjm.html

document.querySelector(".item")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xljrpidl.html

[U101] JS：classList 操作
来源：http://dali.pycfn.com/Article/details/gt2faxazkmq.html

el.classList.toggle("active")
来源：http://dali.shangyingyoupin.top/Article/details/gt2scyzwktq.html

[U102] JS：本地存储
来源：http://dali.ivvv.top/Article/details/gt2spdtjdzj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yonumen.top/Article/details/gt2ksunwwby.html

[U103] JS：定时器
来源：http://dali.yj20258888.top/Article/details/gt2cknxjhtk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yj20258.top/Article/details/gt2aegbuyeq.html

[U104] JS：防抖
来源：http://dali.chenjidiqi.icu/Article/details/gt2ilukztok.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gt2edkoptbh.html

[U105] JS：节流
来源：http://dali.sweek.top/Article/details/gt2govuwefw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ybcxt.top/Article/details/gt2gsimfdgy.html

[U106] JS：日期格式化
来源：http://dali.hnqzz.top/Article/details/gt2eujrvcff.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rxmdhsjz.html

[U107] JS：数字千分位
来源：http://dali.haohaochexian.top/Article/details/gt2pbckqazt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jqgufenzy.top/Article/details/gt2rqlzcnsy.html

[U108] JS：随机整数
来源：http://dali.hnxiangtu.top/Article/details/gt2mpnqlseg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhiwuduotai.top/Article/details/gt2csuxanrt.html

[U109] JS：数组分组
来源：http://dali.kuanghao11.cn/Article/details/gt2blfkfxff.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hywenlv.cn/Article/details/gt2uvxvgyfb.html

[U110] JS：数组分块
来源：http://dali.yuxming.cn/Article/details/gt2lkzmrtct.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lkqisjyb.html

[U111] JS：对象转 Map
来源：http://dali.shuidangran.top/Article/details/gt2sygsxrdx.html

new Map(Object.entries(obj))
来源：http://dali.ybcxt.top/Article/details/gt2vwcnmwmm.html

[U112] JS：字符串补位
来源：http://dali.fengsongda.top/Article/details/gt2thswoqhl.html

"7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gt2tzzebalh.html

[U113] JS：正则替换全部
来源：http://dali.svipenyu.cn/Article/details/gt2xcpxblep.html

s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xnidofmh.html

[U114] JS：JSON 深比较
来源：http://dali.shuidangran.top/Article/details/gt2enihotkc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sxryk.cn/Article/details/gt2hhzsixpa.html

[U115] JS：生成 UUID
来源：http://dali.chenzaomai.com/Article/details/gt2tlswpajw.html

crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gt2edgsoaef.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xuetiantiany.cn/Article/details/gt2ivwamcef.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj202588.top/Article/details/gt2efoppjhl.html

[U117] JS：单元测试
来源：http://dali.9152youxi.cn/Article/details/gt2pbfhqgni.html

npm i -D vitest;  npx vitest
来源：http://dali.tanke756.top/Article/details/gt2ayxswtvx.html

[U118] JS：开发服务器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qmtliegt.html

npm i -D vite;  npx vite
来源：http://dali.jianghu66.top/Article/details/gt2woylfqiq.html

[U119] JS：生产构建
来源：http://dali.cdnleiting.top/Article/details/gt2dtqsxgkv.html

npx vite build
来源：http://dali.hnxiangtu.top/Article/details/gt2qzhluevq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shuidangran.top/Article/details/gt2npzqrumo.html

import.meta.env.VITE_API_URL
来源：http://dali.fzhhl.top/Article/details/gt2fifsggan.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2octakbbc.html

统计汇总
来源：http://dali.tian-w.cn/Article/details/gt2cgbaitfc.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2pxioeqls.html

按语言统计（条）：
来源：http://dali.andypj.xyz/Article/details/gt2spnclyjj.html

Python ......... 252
来源：http://dali.yvedp.cn/Article/details/gt2noeyewzc.html

PHP ............ 252
来源：http://dali.wangshuangyany.cn/Article/details/gt2lsrjmibb.html

JavaScript ..... 252
来源：http://dali.ydzc1.top/Article/details/gt2cllinayk.html

TypeScript ..... 212
来源：http://dali.tianlin.xyz/Article/details/gt2fhznkhrn.html

Java ........... 212
来源：http://dali.sxryk.cn/Article/details/gt2uowyeeny.html

Go ............. 212
来源：http://dali.hysaishi.cn/Article/details/gt2vhbgbdip.html

Ruby ........... 212
来源：http://dali.sxryk.cn/Article/details/gt2plggfqii.html

C# ............. 212
来源：http://dali.yongpay.top/Article/details/gt2vuvbsuzt.html

C .............. 30
来源：http://dali.zhoulong.xyz/Article/details/gt2foxjzaop.html

C++ ............ 30
来源：http://dali.smart0.xyz/Article/details/gt2zsfomgpz.html

SQL ............ 90
来源：http://dali.nwbrower.top/Article/details/gt2hzbdsudm.html

Bash ........... 80
来源：http://dali.zhengqikj.top/Article/details/gt2hrrojlqu.html

Kotlin ......... 15
来源：http://dali.zdqjudy.top/Article/details/gt2qkbwwuyg.html

Swift .......... 15
来源：http://dali.andypj.xyz/Article/details/gt2dkaqogzf.html

Lua ............ 10
来源：http://dali.xylfe.cn/Article/details/gt2ttiugaxf.html

Perl ........... 10
来源：http://dali.jqgufenzy.top/Article/details/gt2mefzehuu.html

Scala .......... 10
来源：http://dali.fengsongda.top/Article/details/gt2qqhkgcfu.html

------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gt2nrzogtfi.html

合计 ........... 2106 条
来源：http://dali.zhengqikj.top/Article/details/gt2ifendigz.html

按章节统计：
来源：http://dali.aizwys.cn/Article/details/gt2fxumhrpv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.c1oappe.top/Article/details/gt2voscwzrl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gzhubu.top/Article/details/gt2osvolxhu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.nwbrower.top/Article/details/gt2kyjouwzi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.chenjidiqi.icu/Article/details/gt2dswbglyl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.fzhhl.top/Article/details/gt2nmepcict.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sysykeji.top/Article/details/gt2nxrzppig.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.dianchejie.cn/Article/details/gt2nbvslsbn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj20258888.top/Article/details/gt2hbolllyz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gt2ijypspqc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhongyouzk.top/Article/details/gt2inyhrlaz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gt2qpbmmkad.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gt2pfzgmfkq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gt2kisotsma.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sufxvd.cn/Article/details/gt2wfliembd.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hysaishi.cn/Article/details/gt2cmtoqyxp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gt2ekgiozjo.html

Q SQL 专题                              90
来源：http://dali.sxryk.cn/Article/details/gt2mpamaczf.html

R Bash 专题                             80
来源：http://dali.guowangkeji.top/Article/details/gt2jvmlyxxx.html

S C / C++ 专题                          60
来源：http://dali.jinqigufen.top/Article/details/gt2hrcmxhiq.html

T 其他语言补充                          60
来源：http://dali.cashguo.top/Article/details/gt2onjzrpfi.html

U 高频实用片段                         120
来源：http://dali.cucudq.cn/Article/details/gt2lscyvlzd.html

------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gt2jjxsiars.html

合计                                  2106 条
来源：http://dali.havefunace.top/Article/details/gt2hewuress.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gt2nfjdkifh.html

使用提醒
来源：http://dali.guannengcc.top/Article/details/gt2kyvqowrd.html

--------------------------------------------------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gt2pfbtkesr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.quarkkingdee.top/Article/details/gt2mrndmrym.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yongpay.top/Article/details/gt2rdzwfvsc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.pengpengdd.cyou/Article/details/gt2mlutidei.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ppjwa.cn/Article/details/gt2vmsxrpys.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.dashuyun.cn/Article/details/gt2mvycknzh.html

—— 文件结束 ——
来源：http://dali.redwolf501.top/Article/details/gt2szmxyphp.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2tslaojqj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.birdmap.top/Article/details/gt2npxrijfa.html

Common Programming Examples Cheat Book
来源：http://dali.birdmap.top/Article/details/gt2atqesdvk.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2fpwfwzbv.html

【收录内容】
来源：http://dali.daxiang520.top/Article/details/gt2afodsjbc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.chenjidiqi.icu/Article/details/gt2llalhpfq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.redwolf501.top/Article/details/gt2abejokvo.html

SQL · Bash · C · C++
来源：http://dali.c1oappe.top/Article/details/gt2kxejehnn.html


<!-- 参考信息 -->