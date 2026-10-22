代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplecbyvt.html

[T59] Scala：循环
来源：http://dali.yj20258888.top/Article/details/gtcojsnjtf.html

for (i <- 1 to 10) println(i)
来源：http://dali.svipenyu.cn/Article/details/gtwkxzhbrl.html

[T60] Scala：折叠
来源：http://dali.jqgfzy.top/Article/details/gtnhcmhsae.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tanke756.top/Article/details/gtgvjicqxw.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtapgdcxbq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tanke756.top/Article/details/gtrznbrtcr.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtxswdldhv.html

[U01] Py：创建虚拟环境
来源：http://dali.gogol.net.cn/Article/details/gtyswsltqz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenzaomai.com/Article/details/gtrgotswba.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nanxuanxn.top/Article/details/gtzjfdompw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinqigufen.top/Article/details/gtvshyioih.html

[U03] Py：加载 .env 配置
来源：http://dali.xinyue.icu/Article/details/gtulivlddl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ppjwa.cn/Article/details/gtkbxgefvo.html

[U04] Py：变量调试打印
来源：http://dali.xylfe.cn/Article/details/gtrdfnbwrh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yongpay.top/Article/details/gtdtnxhqjk.html

[U05] Py：列表去重且保序
来源：http://dali.zycfv.cn/Article/details/gtrvgynysw.html

list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gtwdvpckee.html

[U06] Py：合并两个字典
来源：http://dali.jinqigfzy.top/Article/details/gtuvvtjwyr.html

{**a, **b}
来源：http://dali.vqdsnc.cn/Article/details/gtpmaavutq.html

[U07] Py：反转字典键值
来源：http://dali.jqgufenzy.top/Article/details/gtblcpodvu.html

{v: k for k, v in d.items()}
来源：http://dali.gaohongyu789.top/Article/details/gtarlcskzg.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangtech.top/Article/details/gttufvmmhj.html

[y for x in nested for y in x]
来源：http://dali.bjfxy.top/Article/details/gtjvsmxymq.html

[U09] Py：字典取最大值的键
来源：http://dali.kuanghao11.cn/Article/details/gtsxfeunii.html

max(d, key=d.get)
来源：http://dali.zhengqikj.top/Article/details/gtcengoxch.html

[U10] Py：按值排序字典
来源：http://dali.hysaishi.cn/Article/details/gtcwgxocmi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shangyingyoupin.top/Article/details/gtbcersonr.html

[U11] Py：生成器表达式
来源：http://dali.xuanzx.com/Article/details/gtuomuguff.html

(x * 2 for x in arr)
来源：http://dali.yuxming.cn/Article/details/gtqqdieosm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuyviknhw.html

Counter(arr).most_common(3)
来源：http://dali.zdqjudy.top/Article/details/gteybyrmow.html

[U13] Py：固定长度队列
来源：http://dali.mhx1999.top/Article/details/gtgoggkrmo.html

deque(maxlen=10)
来源：http://dali.jqgfzy.top/Article/details/gtqtulnnei.html

[U14] Py：分组收集到列表
来源：http://dali.yonumen.top/Article/details/gtbibjyeuk.html

defaultdict(list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwlzbrwp.html

[U15] Py：高精度计时
来源：http://dali.cdnleiting.top/Article/details/gtijvnaqva.html

t = time.perf_counter()
来源：http://dali.ydzc1.top/Article/details/gthinamivx.html

[U16] Py：命令行参数解析
来源：http://dali.chenjidiqi.icu/Article/details/gtkvevdtqb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cqqwz.cn/Article/details/gttvjvmupx.html

[U17] Py：初始化日志
来源：http://dali.kuanghao11.cn/Article/details/gtaxzjdsgx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.birdmap.top/Article/details/gtuapmlszp.html

[U18] Py：预编译正则
来源：http://dali.yuxming.cn/Article/details/gtgjfxousz.html

pat = re.compile(r"\d+")
来源：http://dali.gotoacloud.top/Article/details/gtyxlqayay.html

[U19] Py：正则替换带回调
来源：http://dali.cashguo.top/Article/details/gtvcxybyke.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.haohaochexian.top/Article/details/gtixxmpmvu.html

[U20] Py：缓存函数结果
来源：http://dali.hywenlv.cn/Article/details/gtcqlzfbks.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sxryk.cn/Article/details/gtogtqikbk.html

[U21] Py：自定义上下文管理器
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmhvttqe.html

@contextlib.contextmanager
来源：http://dali.meibo888.top/Article/details/gtvyqwxioz.html

[U22] Py：矩阵转置
来源：http://dali.nwbrower.top/Article/details/gtyrftxdqt.html

list(zip(*m))
来源：http://dali.zhixingplan.top/Article/details/gtwmwyyept.html

[U23] Py：分块读取大文件
来源：http://dali.jyoumei.cn/Article/details/gtwlkeckpm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.guowangkeji.top/Article/details/gtxzvosbku.html

[U24] Py：路径操作
来源：http://dali.xinyue.icu/Article/details/gtivtjmrzt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gtosxvmsdl.html

[U25] Py：CSV 按字典读
来源：http://dali.vqdsnc.cn/Article/details/gteupplosf.html

csv.DictReader(f)
来源：http://dali.cheryme.top/Article/details/gtwqnljnrq.html

[U26] Py：并发下载
来源：http://dali.hammf.cn/Article/details/gtvcbhfevv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yonumen.top/Article/details/gtiistcarg.html

[U27] Py：异步 HTTP
来源：http://dali.zhaomingkeji.xyz/Article/details/gtticvpglo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.bjfxy.top/Article/details/gtefphtrjx.html

[U28] Py：类型别名
来源：http://dali.sxryk.cn/Article/details/gtcjjesckv.html

UserId = int
来源：http://dali.jlsjyb.cn/Article/details/gtasovxsof.html

[U29] Py：属性校验
来源：http://dali.yj202588.top/Article/details/gtxezwkkrb.html

@property 与 @x.setter 配合
来源：http://dali.yanxiufei.cn/Article/details/gtareeddyl.html

[U30] Py：数据类
来源：http://dali.kuanghao11.cn/Article/details/gtfwcpufvj.html

@dataclass(slots=True)
来源：http://dali.ybcxt.top/Article/details/gthvpbufur.html

[U31] Py：单测
来源：http://dali.nwbrower.top/Article/details/gteiqojpqf.html

python -m pytest -q
来源：http://dali.svipenyu.cn/Article/details/gtytewieud.html

[U32] Py：代码格式化
来源：http://dali.smart0.xyz/Article/details/gtojqpbvfe.html

ruff format . && ruff check --fix .
来源：http://dali.smart0.xyz/Article/details/gtqecvtdar.html

[U33] Py：打包发布
来源：http://dali.sweek.top/Article/details/gtlrirhotq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gogol.net.cn/Article/details/gtpwwxgvfq.html

[U34] Py：判断编码
来源：http://dali.guowangkeji.top/Article/details/gtltrpsiub.html

chardet.detect(raw)
来源：http://dali.fzhhl.top/Article/details/gtlpbparfz.html

[U35] Py：发送邮件
来源：http://dali.zycfv.cn/Article/details/gtenjqpchc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hongshengwenyu.top/Article/details/gtwuqlkcea.html

[U36] Py：定时任务
来源：http://dali.zhixingplan.top/Article/details/gteguigote.html

schedule.every(10).minutes.do(job)
来源：http://dali.tanke756.top/Article/details/gtqqyivkwp.html

[U37] Py：读写 Excel
来源：http://dali.guowangkeji.top/Article/details/gtybmtleuo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gaohongyu789.top/Article/details/gtuyxdgthu.html

[U38] Py：获取脚本所在目录
来源：http://dali.fzhhl.top/Article/details/gtjacvdjuv.html

Path(__file__).resolve().parent
来源：http://dali.zhongyouzk.top/Article/details/gtkdcjuner.html

[U39] Py：判断是否在交互环境
来源：http://dali.hammf.cn/Article/details/gtkxpbkaxz.html

sys.stdout.isatty()
来源：http://dali.0kj1m.cn/Article/details/gtdlwdgkla.html

[U40] Py：打印到标准错误
来源：http://dali.shzxlz.cn/Article/details/gtwpnevhtm.html

print("err", file=sys.stderr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdkryfox.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.haohaochexian.top/Article/details/gtmmgjsqbv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tianlin.xyz/Article/details/gtgsozqtcu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xylfe.cn/Article/details/gtyouyhxrx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.316326.xyz/Article/details/gtmxpimedw.html

[U43] PHP：声明命名空间
来源：http://dali.xziqi.cn/Article/details/gtubzyykkd.html

namespace App\Http;
来源：http://dali.yuxming.cn/Article/details/gthxedhzow.html

[U44] PHP：开启严格类型
来源：http://dali.daria6918.cn/Article/details/gtumbhtoji.html

declare(strict_types=1);
来源：http://dali.yonumen.top/Article/details/gtmmsfdeka.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jiagoushi.top/Article/details/gtinbblmrm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtdypjotxk.html

[U46] PHP：可空类型
来源：http://dali.sxryk.cn/Article/details/gtotlbloay.html

?string $name = null
来源：http://dali.kuanghao11.cn/Article/details/gtwmqchyiv.html

[U47] PHP：联合类型
来源：http://dali.yj20258.top/Article/details/gtuvphbsns.html

int|string $id
来源：http://dali.0kj1m.cn/Article/details/gttcwdrsob.html

[U48] PHP：纯枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsotrrze.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gtdfjlllcj.html

[U49] PHP：只读属性
来源：http://dali.cdnleiting.top/Article/details/gtzefcksis.html

public readonly string $name
来源：http://dali.gotoacloud.top/Article/details/gtkabmhcai.html

[U50] PHP：构造器属性提升
来源：http://dali.chenlongwang.top/Article/details/gtxpkycmbu.html

public function __construct(private int $id) {}
来源：http://dali.pengpengdd.cyou/Article/details/gthvwjoyer.html

[U51] PHP：数组解构
来源：http://dali.yanxiufei.cn/Article/details/gtytgwdufo.html

[$a, $b] = $arr;
来源：http://dali.tanke756.top/Article/details/gtmfxzbypj.html

[U52] PHP：箭头函数
来源：http://dali.xziqi.cn/Article/details/gtxnpvmtfj.html

$double = fn($x) => $x * 2;
来源：http://dali.haohaochexian.top/Article/details/gtvlvuvazb.html

[U53] PHP：空合并运算符
来源：http://dali.andypj.xyz/Article/details/gtqrpqcbgm.html

$v = $a ?? $b ?? "default";
来源：http://dali.hongshengwenyu.top/Article/details/gtdbbfvqea.html

[U54] PHP：空安全调用
来源：http://dali.ivvv.top/Article/details/gtxdaxbrcn.html

$obj?->method()
来源：http://dali.dashuyun.cn/Article/details/gtsqpxzwup.html

[U55] PHP：match 表达式
来源：http://dali.xylfe.cn/Article/details/gtsogyfjxd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.birdmap.top/Article/details/gtbwchbkyn.html

[U56] PHP：命名参数
来源：http://dali.redwolf501.top/Article/details/gtfifkgdue.html

f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gtfdolqzge.html

[U57] PHP：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtseblbztu.html

"值: {$a}"
来源：http://dali.yj202588.top/Article/details/gtaiekdijd.html

[U58] PHP：数组三件套
来源：http://dali.ybcxt.top/Article/details/gtkfcwshvq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cdnleiting.top/Article/details/gtumofbwgs.html

[U59] PHP：自定义排序
来源：http://dali.yongpay.top/Article/details/gtxbrxmkut.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtnlvhipwy.html

[U60] PHP：JSON 编解码
来源：http://dali.c1oappe.top/Article/details/gtpiueokka.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplxedrnf.html

[U61] PHP：正则
来源：http://dali.hfpthk.cn/Article/details/gtjfozmjte.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtsaptigtd.html

[U62] PHP：日期对象
来源：http://dali.redwolf501.top/Article/details/gtyovuaakl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tanke756.top/Article/details/gtdbcojvgo.html

[U63] PHP：文件读写
来源：http://dali.cqqwz.cn/Article/details/gtrhbyvpvq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.quarkkingdee.top/Article/details/gtdwisbwbw.html

[U64] PHP：目录遍历
来源：http://dali.9152youxi.cn/Article/details/gtjorkeqdl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.vqdsnc.cn/Article/details/gtanahxtzb.html

[U65] PHP：会话
来源：http://dali.shangyingyoupin.top/Article/details/gtufaahzlv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtmsuxmubt.html

[U66] PHP：设置 Cookie
来源：http://dali.jinqigufen.top/Article/details/gtnndatwky.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ybcxt.top/Article/details/gtiiqehhom.html

[U67] PHP：处理文件上传
来源：http://dali.cashguo.top/Article/details/gtqsvbtikt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.wangdashe.top/Article/details/gtgxjdeixf.html

[U68] PHP：PDO 连接
来源：http://dali.316326.xyz/Article/details/gtystxgtpe.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ehwqpu.com/Article/details/gtdvydtfys.html

[U69] PHP：PDO 预处理
来源：http://dali.fengsongda.top/Article/details/gtvmveenbz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.pycfn.com/Article/details/gtgsybsqbj.html

[U70] PHP：PDO 事务
来源：http://dali.redwolf501.top/Article/details/gtpkiilpjg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yanxiufei.cn/Article/details/gtdahdickk.html

[U71] PHP：抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtlwgsaxmv.html

throw new RuntimeException("失败", 500);
来源：http://dali.cheryme.top/Article/details/gtyudlipzn.html

[U72] PHP：写错误日志
来源：http://dali.zhoulong.xyz/Article/details/gtxtrnygty.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrlswofo.html

[U73] PHP：读取 ini 配置
来源：http://dali.birdmap.top/Article/details/gtipxwuuwi.html

parse_ini_file("config.ini", true)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipchiyik.html

[U74] PHP：读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gtimubblfh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.andypj.xyz/Article/details/gttwvamjax.html

[U75] PHP：依赖注入
来源：http://dali.yj202588.top/Article/details/gthzqlysam.html

composer require psr/container
来源：http://dali.shanyushiyangtech.top/Article/details/gtgptjwzzo.html

[U76] PHP：简单路由
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjgzdysd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.aibaodan.cn/Article/details/gteyialqdc.html

[U77] PHP：模板渲染
来源：http://dali.yonumen.top/Article/details/gtzujuwvgk.html

composer require twig/twig
来源：http://dali.ybcxt.top/Article/details/gtfttgnmnj.html

[U78] PHP：单元测试
来源：http://dali.aizwys.cn/Article/details/gtpsmpzeoe.html

composer require --dev phpunit/phpunit
来源：http://dali.dashuyun.cn/Article/details/gtuufumczo.html

[U79] PHP：静态分析
来源：http://dali.pengpengdd.cyou/Article/details/gtrvqyixgq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhongyouzk.top/Article/details/gtgqumnxab.html

[U80] PHP：代码规范修复
来源：http://dali.hongshengwenyu.top/Article/details/gtqrodsswf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhiwuduotai.top/Article/details/gtbrhimtqy.html

[U81] JS：初始化项目
来源：http://dali.ydzc1.top/Article/details/gtchmeywgo.html

npm init -y;  npm i express
来源：http://dali.aizwys.cn/Article/details/gtfxnhkgcj.html

[U82] JS：package.json 脚本
来源：http://dali.ydzc1.top/Article/details/gtnilafsbd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shuidangran.top/Article/details/gtehbsaxlx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zycfv.cn/Article/details/gtotgrravj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xziqi.cn/Article/details/gtvfsciydg.html

[U84] JS：CommonJS 写法
来源：http://dali.haohaochexian.top/Article/details/gtcrhjkoxm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cashguo.top/Article/details/gtwvrdftmr.html

[U85] JS：可选链
来源：http://dali.jlsjyb.cn/Article/details/gtejmbszse.html

a?.b?.c
来源：http://dali.yuanzhike.top/Article/details/gtingdtuln.html

[U86] JS：空值合并
来源：http://dali.dashuyun.cn/Article/details/gtwfjhjfgd.html

a ?? b
来源：http://dali.shuidangran.top/Article/details/gtnewqmhso.html

[U87] JS：解构默认值
来源：http://dali.zdqjudy.top/Article/details/gtfbsfgvfj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.mhx1999.top/Article/details/gtceblznko.html

[U88] JS：对象展开合并
来源：http://dali.tanke756.top/Article/details/gttiqfwdoi.html

{ ...a, ...b }
来源：http://dali.yj20258888.top/Article/details/gtydxpnvkn.html

[U89] JS：数组去重
来源：http://dali.redwolf501.top/Article/details/gtjpqsuoxh.html

[...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtubvlyhwy.html

[U90] JS：数字数组排序
来源：http://dali.hammf.cn/Article/details/gtjogbkxse.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtodkuadvk.html

[U91] JS：对象键值遍历
来源：http://dali.meibo888.top/Article/details/gtdyebwfxw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gaohongyu789.top/Article/details/gteyplemja.html

[U92] JS：深拷贝
来源：http://dali.dashuyun.cn/Article/details/gtiqglarxe.html

structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtezzmqcdh.html

[U93] JS：模板字符串
来源：http://dali.bjfxy.top/Article/details/gtptoqkyxk.html

`共 ${n} 条`
来源：http://dali.yvedp.cn/Article/details/gtaqccjaqn.html

[U94] JS：箭头函数
来源：http://dali.hnqzz.top/Article/details/gtuzdocqxe.html

const double = x => x * 2;
来源：http://dali.chenlongwang.top/Article/details/gtntlkufdq.html

[U95] JS：Promise 包装
来源：http://dali.c1oappe.top/Article/details/gtgeitfoek.html

new Promise((resolve, reject) => {})
来源：http://dali.fengsongda.top/Article/details/gtrjikhgcw.html

[U96] JS：async/await 与异常
来源：http://dali.zhongyouzk.top/Article/details/gtttyjqynx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gteluogcgu.html

[U97] JS：并发请求
来源：http://dali.zhixingplan.top/Article/details/gtqgwevnnj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gttrzxufjh.html

[U98] JS：fetch 带 JSON
来源：http://dali.meibo888.top/Article/details/gttfcirkxg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sufxvd.cn/Article/details/gtpmthrggo.html

[U99] JS：事件监听
来源：http://dali.dashuyun.cn/Article/details/gtacizuhuv.html

el.addEventListener("click", e => {})
来源：http://dali.pycfn.com/Article/details/gtuskcxete.html

[U100] JS：DOM 查询
来源：http://dali.cheryme.top/Article/details/gtihjcyjsz.html

document.querySelector(".item")
来源：http://dali.jinqigfzy.top/Article/details/gtpifglggu.html

[U101] JS：classList 操作
来源：http://dali.shzxlz.cn/Article/details/gtibfcufzx.html

el.classList.toggle("active")
来源：http://dali.shangyingyoupin.top/Article/details/gtuvjvzepd.html

[U102] JS：本地存储
来源：http://dali.jqgfzy.top/Article/details/gtphqvsfcq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.andypj.xyz/Article/details/gtctmzjndh.html

[U103] JS：定时器
来源：http://dali.ppjwa.cn/Article/details/gtwgdvgwlg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shzxlz.cn/Article/details/gtzxyhtabc.html

[U104] JS：防抖
来源：http://dali.zhongyouzk.top/Article/details/gtqyvdfyqe.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtknabtzrb.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gtdlhjmjsj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzcdxymu.html

[U106] JS：日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtsgvpjfzb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.wangdashe.top/Article/details/gtowuhycca.html

[U107] JS：数字千分位
来源：http://dali.hysaishi.cn/Article/details/gtpbkzfrrv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hnqzz.top/Article/details/gtbmprzzuo.html

[U108] JS：随机整数
来源：http://dali.jqgufenzy.top/Article/details/gtloigqheg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.wangdashe.top/Article/details/gtyuqwhlnc.html

[U109] JS：数组分组
来源：http://dali.nanxuanxn.top/Article/details/gtcdouzydk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hywenlv.cn/Article/details/gtbecedfep.html

[U110] JS：数组分块
来源：http://dali.xziqi.cn/Article/details/gtvpffzett.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hongshengwenyu.top/Article/details/gtjpccbccs.html

[U111] JS：对象转 Map
来源：http://dali.yongpay.top/Article/details/gtytxhptil.html

new Map(Object.entries(obj))
来源：http://dali.iojbl.cn/Article/details/gtknhzifoq.html

[U112] JS：字符串补位
来源：http://dali.sufxvd.cn/Article/details/gtpdtnmbkn.html

"7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtiewkrqpd.html

[U113] JS：正则替换全部
来源：http://dali.sufxvd.cn/Article/details/gttgebofrz.html

s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtchuelfni.html

[U114] JS：JSON 深比较
来源：http://dali.xinyue.icu/Article/details/gtxjuepaqb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gtqczpxfmw.html

[U115] JS：生成 UUID
来源：http://dali.fengsongda.top/Article/details/gtcdqmsfto.html

crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtwjlrmneq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhoulong.xyz/Article/details/gttozvtfmb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhoulong.xyz/Article/details/gtfbaxuvxz.html

[U117] JS：单元测试
来源：http://dali.smart0.xyz/Article/details/gtgxjcbept.html

npm i -D vitest;  npx vitest
来源：http://dali.gogol.net.cn/Article/details/gtadjlltrw.html

[U118] JS：开发服务器
来源：http://dali.tanke756.top/Article/details/gtytxwwlkn.html

npm i -D vite;  npx vite
来源：http://dali.haohaochexian.top/Article/details/gtapwsoeve.html

[U119] JS：生产构建
来源：http://dali.wangshuangyany.cn/Article/details/gtcrdwfhsi.html

npx vite build
来源：http://dali.gotoacloud.top/Article/details/gtsuobadjw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ehwqpu.com/Article/details/gtfrhviagr.html

import.meta.env.VITE_API_URL
来源：http://dali.pycfn.com/Article/details/gtnsrmwzlj.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtxjxycill.html

统计汇总
来源：http://dali.redwolf501.top/Article/details/gtkovtgohs.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrrztvoh.html

按语言统计（条）：
来源：http://dali.aizwys.cn/Article/details/gtdmwjlmni.html

Python ......... 252
来源：http://dali.jqgfzy.top/Article/details/gtjnslnfjl.html

PHP ............ 252
来源：http://dali.yongpay.top/Article/details/gtzjcplsqq.html

JavaScript ..... 252
来源：http://dali.mhx1999.top/Article/details/gthooqescy.html

TypeScript ..... 212
来源：http://dali.jinqigufen.top/Article/details/gttjmvzfbo.html

Java ........... 212
来源：http://dali.yj20258.top/Article/details/gtkmbdwbad.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gtxpcymjlf.html

Ruby ........... 212
来源：http://dali.gzhubu.top/Article/details/gtqrxxslic.html

C# ............. 212
来源：http://dali.nanxinkj.top/Article/details/gtlfbnmkeh.html

C .............. 30
来源：http://dali.chenlongwang.top/Article/details/gtnayarqrc.html

C++ ............ 30
来源：http://dali.mhx1999.top/Article/details/gtktulblzt.html

SQL ............ 90
来源：http://dali.gaohongyu789.top/Article/details/gtfwsratik.html

Bash ........... 80
来源：http://dali.sxryk.cn/Article/details/gtqyhidktg.html

Kotlin ......... 15
来源：http://dali.ybcxt.top/Article/details/gtmzmiqaoq.html

Swift .......... 15
来源：http://dali.hongshengwenyu.top/Article/details/gtfbyoxzvb.html

Lua ............ 10
来源：http://dali.dianchejie.cn/Article/details/gtuhodixwr.html

Perl ........... 10
来源：http://dali.jiagoushi.top/Article/details/gtqxkrhljs.html

Scala .......... 10
来源：http://dali.ppjwa.cn/Article/details/gtyjstvaag.html

------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gtfjtkugsx.html

合计 ........... 2106 条
来源：http://dali.jqgufenzy.top/Article/details/gtxtohsbch.html

按章节统计：
来源：http://dali.shangyingyoupin.top/Article/details/gtdrbemxwh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yj20258.top/Article/details/gtcivozotb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.tianlin.xyz/Article/details/gtgmwbrrdb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.bjfxy.top/Article/details/gtqakurhxq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hywenlv.cn/Article/details/gtxqosffod.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhiwuduotai.top/Article/details/gtbykozwwz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cqqwz.cn/Article/details/gtdlvpdvzn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gtpeqbquiz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj202588.top/Article/details/gtlhilftvw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gtgrpzarts.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrrnffho.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtcbydvmya.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gtkjvovowg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gthvxajibw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jinqigufen.top/Article/details/gtszaskpmt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.sysykeji.top/Article/details/gtylkqzrqj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gtyxetzhyy.html

Q SQL 专题                              90
来源：http://dali.yuxming.cn/Article/details/gtagxgfuow.html

R Bash 专题                             80
来源：http://dali.zhoulong.xyz/Article/details/gtgxdvrsij.html

S C / C++ 专题                          60
来源：http://dali.0kj1m.cn/Article/details/gtumufxgsm.html

T 其他语言补充                          60
来源：http://dali.smart0.xyz/Article/details/gtvvzdzxpp.html

U 高频实用片段                         120
来源：http://dali.hammf.cn/Article/details/gtjbrarkri.html

------------------------------------
来源：http://dali.tian-w.cn/Article/details/gtatftnhyq.html

合计                                  2106 条
来源：http://dali.jinqigufen.top/Article/details/gtlgxtnrdn.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gtimibjfti.html

使用提醒
来源：http://dali.birdmap.top/Article/details/gtczfyzgpu.html

--------------------------------------------------------------------------------
来源：http://dali.nwbrower.top/Article/details/gtvkmmmtfv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jyoumei.cn/Article/details/gtyokyadeq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwkbabue.html


<!-- 参考信息 -->