代发 wailian999

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.guowangkeji.top/Article/details/gtfgeyarjz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtxqybawtf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shuidangran.top/Article/details/gtmsrqfzop.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuldpjzsq.html

[U01] Py：创建虚拟环境
来源：http://dali.zhiwuduotai.top/Article/details/gtbodefquw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjsvcmba.html

[U02] Py：导出 / 安装依赖
来源：http://dali.316326.xyz/Article/details/gtnjkunevq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nwbrower.top/Article/details/gtxqpcotaw.html

[U03] Py：加载 .env 配置
来源：http://dali.zycfv.cn/Article/details/gtwwjzuqal.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gaohongyu789.top/Article/details/gtmeeczzuv.html

[U04] Py：变量调试打印
来源：http://dali.hfpthk.cn/Article/details/gtlijrkgxs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aizwys.cn/Article/details/gtpwtxfhpm.html

[U05] Py：列表去重且保序
来源：http://dali.daxiang520.top/Article/details/gtgrgraojr.html

list(dict.fromkeys(arr))
来源：http://dali.yj202588.top/Article/details/gtrekoudjo.html

[U06] Py：合并两个字典
来源：http://dali.zycfv.cn/Article/details/gtlyvmsqpy.html

{**a, **b}
来源：http://dali.xuanzx.com/Article/details/gtztrcrpip.html

[U07] Py：反转字典键值
来源：http://dali.hywenlv.cn/Article/details/gtpijgjahr.html

{v: k for k, v in d.items()}
来源：http://dali.gogol.net.cn/Article/details/gtvlfzwndh.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gtxztctmkt.html

[y for x in nested for y in x]
来源：http://dali.chenzaomai.com/Article/details/gtzqmhwjak.html

[U09] Py：字典取最大值的键
来源：http://dali.aizwys.cn/Article/details/gtjnlwbzas.html

max(d, key=d.get)
来源：http://dali.xziqi.cn/Article/details/gtyanvbrsm.html

[U10] Py：按值排序字典
来源：http://dali.zhengqikj.top/Article/details/gtigesvhhs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.aibaodan.cn/Article/details/gtbgcmlgvh.html

[U11] Py：生成器表达式
来源：http://dali.ehwqpu.com/Article/details/gtlyvoxfxt.html

(x * 2 for x in arr)
来源：http://dali.chenlongwang.top/Article/details/gtznphcepo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.c1oappe.top/Article/details/gtbpyqpznc.html

Counter(arr).most_common(3)
来源：http://dali.ydzc1.top/Article/details/gtyfredjja.html

[U13] Py：固定长度队列
来源：http://dali.ybcxt.top/Article/details/gttqlzpvhl.html

deque(maxlen=10)
来源：http://dali.jqgfzy.top/Article/details/gtcnhgskpv.html

[U14] Py：分组收集到列表
来源：http://dali.dianchejie.cn/Article/details/gtjhhicend.html

defaultdict(list)
来源：http://dali.hnxiangtu.top/Article/details/gtwbpllcte.html

[U15] Py：高精度计时
来源：http://dali.shangyingyoupin.top/Article/details/gtfxkuptpk.html

t = time.perf_counter()
来源：http://dali.fengsongda.top/Article/details/gtxalcqons.html

[U16] Py：命令行参数解析
来源：http://dali.yuanzhike.top/Article/details/gtzozllgzv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hammf.cn/Article/details/gtdulzvuwg.html

[U17] Py：初始化日志
来源：http://dali.andypj.xyz/Article/details/gtqwugoqin.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yanxiufei.cn/Article/details/gtnupuodsl.html

[U18] Py：预编译正则
来源：http://dali.sufxvd.cn/Article/details/gteamswber.html

pat = re.compile(r"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgcsojwq.html

[U19] Py：正则替换带回调
来源：http://dali.xinyue.icu/Article/details/gtccozfjmg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.kuanghao11.cn/Article/details/gtudjwkcra.html

[U20] Py：缓存函数结果
来源：http://dali.jinghuilouyu.cn/Article/details/gttvjhipam.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xuetiantiany.cn/Article/details/gtzvpjmmvu.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnxiangtu.top/Article/details/gtchirtcsa.html

@contextlib.contextmanager
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsfnrnah.html

[U22] Py：矩阵转置
来源：http://dali.9152youxi.cn/Article/details/gtdtvtopsv.html

list(zip(*m))
来源：http://dali.hysaishi.cn/Article/details/gtfkrnjncf.html

[U23] Py：分块读取大文件
来源：http://dali.ppjwa.cn/Article/details/gttpobqmvr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.guannengcc.top/Article/details/gtwokaqdtu.html

[U24] Py：路径操作
来源：http://dali.sweek.top/Article/details/gtwwfmjzit.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gtisvezcbf.html

[U25] Py：CSV 按字典读
来源：http://dali.chenjidiqi.icu/Article/details/gtkbfginge.html

csv.DictReader(f)
来源：http://dali.dianchejie.cn/Article/details/gtsxnupddt.html

[U26] Py：并发下载
来源：http://dali.jinqigufen.top/Article/details/gtmanilsbt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jqgfzy.top/Article/details/gtxwvflajf.html

[U27] Py：异步 HTTP
来源：http://dali.shuidangran.top/Article/details/gtqiiienpm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shangyingyoupin.top/Article/details/gtkwwhxwjc.html

[U28] Py：类型别名
来源：http://dali.nanxinkj.top/Article/details/gtrzbpdkal.html

UserId = int
来源：http://dali.jqgufenzy.top/Article/details/gtjlcugvln.html

[U29] Py：属性校验
来源：http://dali.quarkkingdee.top/Article/details/gtungvgqro.html

@property 与 @x.setter 配合
来源：http://dali.fengsongda.top/Article/details/gttpmpcugy.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gtwogkwtpn.html

@dataclass(slots=True)
来源：http://dali.9152youxi.cn/Article/details/gtvpmiomax.html

[U31] Py：单测
来源：http://dali.xuanzx.com/Article/details/gtjvskwonb.html

python -m pytest -q
来源：http://dali.yonumen.top/Article/details/gtvrnoiuxx.html

[U32] Py：代码格式化
来源：http://dali.dianchejie.cn/Article/details/gthmtezamg.html

ruff format . && ruff check --fix .
来源：http://dali.zdqjudy.top/Article/details/gtzojijeny.html

[U33] Py：打包发布
来源：http://dali.andypj.xyz/Article/details/gtxzdmxzcc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznuhxvwc.html

[U34] Py：判断编码
来源：http://dali.guannengcc.top/Article/details/gtpekhzusc.html

chardet.detect(raw)
来源：http://dali.xuanzx.com/Article/details/gtedgrdetj.html

[U35] Py：发送邮件
来源：http://dali.ivvv.top/Article/details/gtikyzuppe.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.pengpengdd.cyou/Article/details/gtikqomcil.html

[U36] Py：定时任务
来源：http://dali.yanxiufei.cn/Article/details/gtutykjncs.html

schedule.every(10).minutes.do(job)
来源：http://dali.quarkkingdee.top/Article/details/gtdmvaubzl.html

[U37] Py：读写 Excel
来源：http://dali.yuanzhike.top/Article/details/gtudqjdtuk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cqqwz.cn/Article/details/gtilaghmti.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhiwuduotai.top/Article/details/gtriauicam.html

Path(__file__).resolve().parent
来源：http://dali.fengsongda.top/Article/details/gtfskdshxi.html

[U39] Py：判断是否在交互环境
来源：http://dali.c1oappe.top/Article/details/gthlucrthn.html

sys.stdout.isatty()
来源：http://dali.zhongyouzk.top/Article/details/gtxdwbdfft.html

[U40] Py：打印到标准错误
来源：http://dali.yueranfly.top/Article/details/gtwtizdmhw.html

print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gtewhrjwta.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xziqi.cn/Article/details/gtfvxmythn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.svipenyu.cn/Article/details/gtsnmhwosl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.meibo888.top/Article/details/gtrntqhffq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnpfiqmh.html

[U43] PHP：声明命名空间
来源：http://dali.jyoumei.cn/Article/details/gteylbruut.html

namespace App\Http;
来源：http://dali.ehwqpu.com/Article/details/gtcnifojii.html

[U44] PHP：开启严格类型
来源：http://dali.wangshuangyany.cn/Article/details/gttlfeuewq.html

declare(strict_types=1);
来源：http://dali.zhixingplan.top/Article/details/gtitnjocde.html

[U45] PHP：类型声明与返回类型
来源：http://dali.mhx1999.top/Article/details/gtslijqjpu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtljecwsvk.html

[U46] PHP：可空类型
来源：http://dali.birdmap.top/Article/details/gtvqcgstbc.html

?string $name = null
来源：http://dali.gogol.net.cn/Article/details/gtrippgikb.html

[U47] PHP：联合类型
来源：http://dali.nanxuanxn.top/Article/details/gtxdtodbvq.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gtsjmduchh.html

[U48] PHP：纯枚举
来源：http://dali.gzhubu.top/Article/details/gtxrbdumjy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.guannengcc.top/Article/details/gtwposqcbj.html

[U49] PHP：只读属性
来源：http://dali.yonumen.top/Article/details/gtvqpkcgkg.html

public readonly string $name
来源：http://dali.jqgufenzy.top/Article/details/gtrjqfzkjc.html

[U50] PHP：构造器属性提升
来源：http://dali.sweek.top/Article/details/gtwuwgncqu.html

public function __construct(private int $id) {}
来源：http://dali.andypj.xyz/Article/details/gtgklpjrlu.html

[U51] PHP：数组解构
来源：http://dali.dashuyun.cn/Article/details/gthyujyacj.html

[$a, $b] = $arr;
来源：http://dali.jianghu66.top/Article/details/gtozyuhawx.html

[U52] PHP：箭头函数
来源：http://dali.jqgfzy.top/Article/details/gtibtyfwgd.html

$double = fn($x) => $x * 2;
来源：http://dali.yonumen.top/Article/details/gtcjttnxyi.html

[U53] PHP：空合并运算符
来源：http://dali.zhongyouzk.top/Article/details/gtkajuseye.html

$v = $a ?? $b ?? "default";
来源：http://dali.birdmap.top/Article/details/gtpymeywjh.html

[U54] PHP：空安全调用
来源：http://dali.hnqzz.top/Article/details/gtbkaoohzg.html

$obj?->method()
来源：http://dali.havefunace.top/Article/details/gtxbjmgdrh.html

[U55] PHP：match 表达式
来源：http://dali.zycfv.cn/Article/details/gtsgxaxsmx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.dianchejie.cn/Article/details/gtireqivpo.html

[U56] PHP：命名参数
来源：http://dali.wangdashe.top/Article/details/gttskcilyj.html

f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gtuknxhlql.html

[U57] PHP：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtfynfknsd.html

"值: {$a}"
来源：http://dali.ybcxt.top/Article/details/gtejtsxeuz.html

[U58] PHP：数组三件套
来源：http://dali.nanxinkj.top/Article/details/gthpdvotes.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yueranfly.top/Article/details/gtirykxgnu.html

[U59] PHP：自定义排序
来源：http://dali.yj20258.top/Article/details/gtvymvqlvj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.vqdsnc.cn/Article/details/gtkkrkqrwb.html

[U60] PHP：JSON 编解码
来源：http://dali.316326.xyz/Article/details/gtogphsqpr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtcqnewqdp.html

[U61] PHP：正则
来源：http://dali.xuetiantiany.cn/Article/details/gttuiqetil.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gtnoscesmy.html

[U62] PHP：日期对象
来源：http://dali.pengpengdd.cyou/Article/details/gtrzwleeog.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.pycfn.com/Article/details/gtkkvnumhc.html

[U63] PHP：文件读写
来源：http://dali.xuetiantiany.cn/Article/details/gtdziucspd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shuidangran.top/Article/details/gtwzelfbco.html

[U64] PHP：目录遍历
来源：http://dali.yj20258.top/Article/details/gtuqcgtjfh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.aibaodan.cn/Article/details/gtrrvzmrvy.html

[U65] PHP：会话
来源：http://dali.wangshuangyany.cn/Article/details/gtrpiqpqra.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtzugljwhr.html

[U66] PHP：设置 Cookie
来源：http://dali.sxryk.cn/Article/details/gtpdykyhrj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yj20258888.top/Article/details/gtvzsmkflp.html

[U67] PHP：处理文件上传
来源：http://dali.chenjidiqi.icu/Article/details/gtjptjtfpl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shanyushiyangtech.top/Article/details/gtamubwamh.html

[U68] PHP：PDO 连接
来源：http://dali.sysykeji.top/Article/details/gtczdqahyp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zycfv.cn/Article/details/gtukbbnnca.html

[U69] PHP：PDO 预处理
来源：http://dali.zycfv.cn/Article/details/gtywbbcrmw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.feifeiyinyue.top/Article/details/gtgddyyled.html

[U70] PHP：PDO 事务
来源：http://dali.xuetiantiany.cn/Article/details/gtycvlpuxo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.shanyushiyangkeji.top/Article/details/gthswzzoly.html

[U71] PHP：抛出异常
来源：http://dali.shuidangran.top/Article/details/gtfbwqinmv.html

throw new RuntimeException("失败", 500);
来源：http://dali.0kj1m.cn/Article/details/gtopcattmk.html

[U72] PHP：写错误日志
来源：http://dali.tian-w.cn/Article/details/gtzubshhhq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cqqwz.cn/Article/details/gtffzskbvn.html

[U73] PHP：读取 ini 配置
来源：http://dali.hongshengwenyu.top/Article/details/gtnzfkrtbx.html

parse_ini_file("config.ini", true)
来源：http://dali.cashguo.top/Article/details/gttizdqpxy.html

[U74] PHP：读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gttxadkvhy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj20258.top/Article/details/gtxqrmhygf.html

[U75] PHP：依赖注入
来源：http://dali.yj20258.top/Article/details/gtixcezmno.html

composer require psr/container
来源：http://dali.hywenlv.cn/Article/details/gtuxkinegm.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gttiufruam.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.daxiang520.top/Article/details/gtvnuvkrbx.html

[U77] PHP：模板渲染
来源：http://dali.yj20258.top/Article/details/gtrzknwduk.html

composer require twig/twig
来源：http://dali.shangyingyoupin.top/Article/details/gtcbkdpcvu.html

[U78] PHP：单元测试
来源：http://dali.dianchejie.cn/Article/details/gtttgbxneu.html

composer require --dev phpunit/phpunit
来源：http://dali.kuanghao11.cn/Article/details/gtvumctozx.html

[U79] PHP：静态分析
来源：http://dali.nanxinkj.top/Article/details/gthrkggwhs.html

composer require --dev phpstan/phpstan
来源：http://dali.yonumen.top/Article/details/gtutnytpox.html

[U80] PHP：代码规范修复
来源：http://dali.cqqwz.cn/Article/details/gtdlbzxzvp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shuidangran.top/Article/details/gtipxyyehw.html

[U81] JS：初始化项目
来源：http://dali.xuanzx.com/Article/details/gtpkmuhghd.html

npm init -y;  npm i express
来源：http://dali.yonumen.top/Article/details/gtacfzvnzx.html

[U82] JS：package.json 脚本
来源：http://dali.guowangkeji.top/Article/details/gtvmprevrn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhoulong.xyz/Article/details/gtoquodkfg.html

[U83] JS：ES Module 导入导出
来源：http://dali.smart0.xyz/Article/details/gtkmlxrzyg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsabhueiz.html

[U84] JS：CommonJS 写法
来源：http://dali.yj202588.top/Article/details/gtabjzchsz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.guannengcc.top/Article/details/gtzlxzfcur.html

[U85] JS：可选链
来源：http://dali.jianghu66.top/Article/details/gtywpgvxhe.html

a?.b?.c
来源：http://dali.aibaodan.cn/Article/details/gtygziioct.html

[U86] JS：空值合并
来源：http://dali.nwbrower.top/Article/details/gtfssnrrbg.html

a ?? b
来源：http://dali.chenzaomai.com/Article/details/gtzaaeahaa.html

[U87] JS：解构默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsavigssc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yanxiufei.cn/Article/details/gtddcfpglx.html

[U88] JS：对象展开合并
来源：http://dali.jyoumei.cn/Article/details/gtmosueipa.html

{ ...a, ...b }
来源：http://dali.pengpengdd.cyou/Article/details/gtqendwwsf.html

[U89] JS：数组去重
来源：http://dali.zhongyouzk.top/Article/details/gtqcstvqha.html

[...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtegicgvct.html

[U90] JS：数字数组排序
来源：http://dali.cqqwz.cn/Article/details/gtkgfihdgm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gtxtykyjpl.html

[U91] JS：对象键值遍历
来源：http://dali.ppjwa.cn/Article/details/gtovqqjhxp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj20258.top/Article/details/gtpwrgfquk.html

[U92] JS：深拷贝
来源：http://dali.jianghu66.top/Article/details/gtuuvuflzp.html

structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gtdoudmqrl.html

[U93] JS：模板字符串
来源：http://dali.xziqi.cn/Article/details/gtxkawkqwa.html

`共 ${n} 条`
来源：http://dali.aibaodan.cn/Article/details/gtcxijmzsp.html

[U94] JS：箭头函数
来源：http://dali.yongpay.top/Article/details/gtqqvtbxub.html

const double = x => x * 2;
来源：http://dali.gzhubu.top/Article/details/gtqfvazwna.html

[U95] JS：Promise 包装
来源：http://dali.jqgufenzy.top/Article/details/gtrzzsairx.html

new Promise((resolve, reject) => {})
来源：http://dali.xziqi.cn/Article/details/gtkqamzrld.html

[U96] JS：async/await 与异常
来源：http://dali.jiagoushi.top/Article/details/gtcfaroank.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtqbktdvbh.html

[U97] JS：并发请求
来源：http://dali.haohaochexian.top/Article/details/gtmkccoesq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtqlvsipry.html

[U98] JS：fetch 带 JSON
来源：http://dali.ivvv.top/Article/details/gtpetiigmp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj20258.top/Article/details/gtvxxhbfra.html

[U99] JS：事件监听
来源：http://dali.zycfv.cn/Article/details/gtwndxlcvs.html

el.addEventListener("click", e => {})
来源：http://dali.zycfv.cn/Article/details/gtkvqktyck.html

[U100] JS：DOM 查询
来源：http://dali.jyoumei.cn/Article/details/gtinuxhavg.html

document.querySelector(".item")
来源：http://dali.jinqigfzy.top/Article/details/gtgygsbrzv.html

[U101] JS：classList 操作
来源：http://dali.zhoulong.xyz/Article/details/gtdgksqfss.html

el.classList.toggle("active")
来源：http://dali.zhixingplan.top/Article/details/gthaogsuli.html

[U102] JS：本地存储
来源：http://dali.yj20258.top/Article/details/gtalozrscp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.svipenyu.cn/Article/details/gtuvlsauzx.html

[U103] JS：定时器
来源：http://dali.birdmap.top/Article/details/gtxzxkzzfk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.guannengcc.top/Article/details/gtezlywiid.html

[U104] JS：防抖
来源：http://dali.chenjidiqi.icu/Article/details/gtwtizdbjo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdvvdrkj.html

[U105] JS：节流
来源：http://dali.yj202588.top/Article/details/gtdtclkwqy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.dashuyun.cn/Article/details/gtyowxedwr.html

[U106] JS：日期格式化
来源：http://dali.hysaishi.cn/Article/details/gtnzlqqzej.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cucudq.cn/Article/details/gtmsyhvtvp.html

[U107] JS：数字千分位
来源：http://dali.wangshuangyany.cn/Article/details/gtdrdsjjih.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xuanzx.com/Article/details/gtkknroywl.html

[U108] JS：随机整数
来源：http://dali.hongshengwenyu.top/Article/details/gtpsuxghkm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.haohaochexian.top/Article/details/gtdnqydcae.html

[U109] JS：数组分组
来源：http://dali.xinyue.icu/Article/details/gtutalaplw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gtmwsgecvi.html

[U110] JS：数组分块
来源：http://dali.nanxinkj.top/Article/details/gtisdvsqbu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yvedp.cn/Article/details/gtrraxappn.html

[U111] JS：对象转 Map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkbualik.html

new Map(Object.entries(obj))
来源：http://dali.ppjwa.cn/Article/details/gtwlbyscte.html

[U112] JS：字符串补位
来源：http://dali.cqqwz.cn/Article/details/gtiosdibsm.html

"7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtmkwiveqb.html

[U113] JS：正则替换全部
来源：http://dali.aizwys.cn/Article/details/gtgdrdrydz.html

s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtdfrupwbt.html

[U114] JS：JSON 深比较
来源：http://dali.jyoumei.cn/Article/details/gtakdfqohy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhixingplan.top/Article/details/gtqidwuagv.html

[U115] JS：生成 UUID
来源：http://dali.hammf.cn/Article/details/gtxsiyzzca.html

crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtenpnbuwr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shzxlz.cn/Article/details/gttptejmaa.html

/** @param {string} name */ function f(name) {}
来源：http://dali.316326.xyz/Article/details/gtvkllddsv.html

[U117] JS：单元测试
来源：http://dali.redwolf501.top/Article/details/gtxbjvkgec.html

npm i -D vitest;  npx vitest
来源：http://dali.yanxiufei.cn/Article/details/gtycetrowv.html

[U118] JS：开发服务器
来源：http://dali.xinyue.icu/Article/details/gtanaqavor.html

npm i -D vite;  npx vite
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsrfdltz.html

[U119] JS：生产构建
来源：http://dali.gaohongyu789.top/Article/details/gtxzyhsfqq.html

npx vite build
来源：http://dali.jqgufenzy.top/Article/details/gtvlpuxiqe.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sweek.top/Article/details/gtupjvqtlo.html

import.meta.env.VITE_API_URL
来源：http://dali.zhiwuduotai.top/Article/details/gtztezsgsa.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtcbmlovss.html

统计汇总
来源：http://dali.ppjwa.cn/Article/details/gtisqfgrlt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtehedptxc.html

按语言统计（条）：
来源：http://dali.redwolf501.top/Article/details/gtlqreyqkq.html

Python ......... 252
来源：http://dali.yuxming.cn/Article/details/gtltgilwfy.html

PHP ............ 252
来源：http://dali.tanke756.top/Article/details/gtzzbxdhcn.html

JavaScript ..... 252
来源：http://dali.hysaishi.cn/Article/details/gtqgxjcujm.html

TypeScript ..... 212
来源：http://dali.hfpthk.cn/Article/details/gtgnjwyxpw.html

Java ........... 212
来源：http://dali.yj20258888.top/Article/details/gtfltdsamb.html

Go ............. 212
来源：http://dali.shzxlz.cn/Article/details/gthycincvx.html

Ruby ........... 212
来源：http://dali.c1oappe.top/Article/details/gtqgthadtl.html

C# ............. 212
来源：http://dali.hywenlv.cn/Article/details/gtvgbfxgkl.html

C .............. 30
来源：http://dali.shangyingyoupin.top/Article/details/gtxrtrpdcy.html

C++ ............ 30
来源：http://dali.guowangkeji.top/Article/details/gtcwahixzz.html

SQL ............ 90
来源：http://dali.hysaishi.cn/Article/details/gtpmrlgrhv.html

Bash ........... 80
来源：http://dali.ydzc1.top/Article/details/gtqraibmvh.html

Kotlin ......... 15
来源：http://dali.wangdashe.top/Article/details/gtvaaweytg.html

Swift .......... 15
来源：http://dali.yonumen.top/Article/details/gtwdqfhzyh.html

Lua ............ 10
来源：http://dali.sxryk.cn/Article/details/gtvwwpomdv.html

Perl ........... 10
来源：http://dali.zhixingplan.top/Article/details/gttmvmsumn.html

Scala .......... 10
来源：http://dali.iojbl.cn/Article/details/gtzskheyuv.html

------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwkogalb.html

合计 ........... 2106 条
来源：http://dali.guowangkeji.top/Article/details/gtxxglcvny.html

按章节统计：
来源：http://dali.yangfankeji.com/Article/details/gtrrggzqzf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.quarkkingdee.top/Article/details/gtvaytjbqr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.fzhhl.top/Article/details/gtiibbntul.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfiwspeq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yj20258.top/Article/details/gtbitpbxlz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cheryme.top/Article/details/gtnkoznbjw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.daria6918.cn/Article/details/gtkqpdgawe.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tianlin.xyz/Article/details/gtntfwdefu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gtuadgdscx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gtcwyjivqo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xinyue.icu/Article/details/gtuojsvaus.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gthirvtvuy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtyezegrgj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtwqtvmoxg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jiagoushi.top/Article/details/gtiaxaxxwl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jiagoushi.top/Article/details/gtlvuleexu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gthwhqpgxv.html

Q SQL 专题                              90
来源：http://dali.zdqjudy.top/Article/details/gtmbasktgm.html

R Bash 专题                             80
来源：http://dali.cqqwz.cn/Article/details/gtcbmgwvrw.html

S C / C++ 专题                          60
来源：http://dali.hammf.cn/Article/details/gtswocwlsx.html

T 其他语言补充                          60
来源：http://dali.pycfn.com/Article/details/gtqnydrnvs.html

U 高频实用片段                         120
来源：http://dali.kuanghao11.cn/Article/details/gtbsqmhzaw.html

------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtajphipel.html

合计                                  2106 条
来源：http://dali.feifeiyinyue.top/Article/details/gtqispjdmp.html

--------------------------------------------------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtenjbhsha.html

使用提醒
来源：http://dali.xziqi.cn/Article/details/gtwotjcozl.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtttswybmz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jinqigufen.top/Article/details/gtzhhewycw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvhiiyin.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yj20258.top/Article/details/gtsczxbawy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.shanyushiyangtech.top/Article/details/gtetuxnjjq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ybcxt.top/Article/details/gtevscsrgg.html

—— 文件结束 ——
来源：http://dali.zdqjudy.top/Article/details/gtnngjhvdj.html


<!-- 参考信息 -->