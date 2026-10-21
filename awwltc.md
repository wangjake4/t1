代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.yonumen.top/Article/details/gtgebjbwtx.html

[T55] Scala：集合过滤
来源：http://dali.gzhubu.top/Article/details/gtqugeuoth.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhixingplan.top/Article/details/gtomacgcno.html

[T56] Scala：样例类
来源：http://dali.ivvv.top/Article/details/gthclhhspt.html

case class User(name: String, age: Int)
来源：http://dali.zycfv.cn/Article/details/gtgzhzwmtk.html

[T57] Scala：模式匹配
来源：http://dali.aizwys.cn/Article/details/gtmesavyys.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ehwqpu.com/Article/details/gtgsilkams.html

[T58] Scala：函数定义
来源：http://dali.hywenlv.cn/Article/details/gtdaxkcmfr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ivvv.top/Article/details/gtibpbwgaz.html

[T59] Scala：循环
来源：http://dali.birdmap.top/Article/details/gtpsajahlj.html

for (i <- 1 to 10) println(i)
来源：http://dali.316326.xyz/Article/details/gtwqlorjsk.html

[T60] Scala：折叠
来源：http://dali.jqgufenzy.top/Article/details/gtgayjcjux.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cashguo.top/Article/details/gtpwehmqmb.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gttswshvxe.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.fzhhl.top/Article/details/gtixehdomd.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtkqecejlv.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigfzy.top/Article/details/gttioutipc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gaohongyu789.top/Article/details/gtwrcyeuch.html

[U02] Py：导出 / 安装依赖
来源：http://dali.daria6918.cn/Article/details/gtrbgnsnok.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj202588.top/Article/details/gtracgiedj.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgfzy.top/Article/details/gtbrfxpbck.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cashguo.top/Article/details/gtovzhdibk.html

[U04] Py：变量调试打印
来源：http://dali.nwbrower.top/Article/details/gtrmsvwvnf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aibaodan.cn/Article/details/gtfyhsqlsc.html

[U05] Py：列表去重且保序
来源：http://dali.ybcxt.top/Article/details/gtviejbqoj.html

list(dict.fromkeys(arr))
来源：http://dali.9152youxi.cn/Article/details/gtrfvhcgwp.html

[U06] Py：合并两个字典
来源：http://dali.shangyingyoupin.top/Article/details/gtydtovkpr.html

{**a, **b}
来源：http://dali.yj202588.top/Article/details/gtufssvacy.html

[U07] Py：反转字典键值
来源：http://dali.cheryme.top/Article/details/gtsacoxxwl.html

{v: k for k, v in d.items()}
来源：http://dali.yongpay.top/Article/details/gtmcmtwlpy.html

[U08] Py：展平二维列表
来源：http://dali.jqgfzy.top/Article/details/gtnkvcpydi.html

[y for x in nested for y in x]
来源：http://dali.gotoacloud.top/Article/details/gtkczirpyw.html

[U09] Py：字典取最大值的键
来源：http://dali.0kj1m.cn/Article/details/gtabssjtox.html

max(d, key=d.get)
来源：http://dali.ehwqpu.com/Article/details/gtpztppccu.html

[U10] Py：按值排序字典
来源：http://dali.jqgfzy.top/Article/details/gtmsuupnsb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yuxming.cn/Article/details/gtaskrwfmb.html

[U11] Py：生成器表达式
来源：http://dali.hywenlv.cn/Article/details/gtnybhisax.html

(x * 2 for x in arr)
来源：http://dali.yj20258.top/Article/details/gtlmexubga.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.chenzaomai.com/Article/details/gtogsqqbqr.html

Counter(arr).most_common(3)
来源：http://dali.yuanzhike.top/Article/details/gtmthtutjl.html

[U13] Py：固定长度队列
来源：http://dali.sweek.top/Article/details/gtqajaclul.html

deque(maxlen=10)
来源：http://dali.zhengqikj.top/Article/details/gtlcpndwau.html

[U14] Py：分组收集到列表
来源：http://dali.cdnleiting.top/Article/details/gtzmcbkqih.html

defaultdict(list)
来源：http://dali.zdqjudy.top/Article/details/gtxbdgzcbe.html

[U15] Py：高精度计时
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxmsnzwo.html

t = time.perf_counter()
来源：http://dali.iojbl.cn/Article/details/gtrngmwhjn.html

[U16] Py：命令行参数解析
来源：http://dali.sysykeji.top/Article/details/gtwzwcxmoy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuanzhike.top/Article/details/gtmkdjbrdr.html

[U17] Py：初始化日志
来源：http://dali.yonumen.top/Article/details/gtyfvwtdor.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ivvv.top/Article/details/gtpfdekjeo.html

[U18] Py：预编译正则
来源：http://dali.cucudq.cn/Article/details/gtnmntgsvh.html

pat = re.compile(r"\d+")
来源：http://dali.xylfe.cn/Article/details/gteupmarro.html

[U19] Py：正则替换带回调
来源：http://dali.cheryme.top/Article/details/gtznszdrih.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sxryk.cn/Article/details/gtzzduhcmc.html

[U20] Py：缓存函数结果
来源：http://dali.jqgufenzy.top/Article/details/gtqxotnltv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jianghu66.top/Article/details/gtgxziloee.html

[U21] Py：自定义上下文管理器
来源：http://dali.dianchejie.cn/Article/details/gtjhgzjgfv.html

@contextlib.contextmanager
来源：http://dali.chenlongwang.top/Article/details/gtnrngewwz.html

[U22] Py：矩阵转置
来源：http://dali.yueranfly.top/Article/details/gtunjqmiuf.html

list(zip(*m))
来源：http://dali.yongpay.top/Article/details/gtrpuibfbq.html

[U23] Py：分块读取大文件
来源：http://dali.jlsjyb.cn/Article/details/gtmxttodvp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hongshengwenyu.top/Article/details/gtuvlhgkwe.html

[U24] Py：路径操作
来源：http://dali.aibaodan.cn/Article/details/gtrnfbzuuv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsqyavvi.html

[U25] Py：CSV 按字典读
来源：http://dali.xuanzx.com/Article/details/gtalijqroq.html

csv.DictReader(f)
来源：http://dali.yj20258888.top/Article/details/gtjovnhxre.html

[U26] Py：并发下载
来源：http://dali.zycfv.cn/Article/details/gtcmjgcnno.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.havefunace.top/Article/details/gtxqnxgiir.html

[U27] Py：异步 HTTP
来源：http://dali.tianlin.xyz/Article/details/gtaxbelpkz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sysykeji.top/Article/details/gtgouhapea.html

[U28] Py：类型别名
来源：http://dali.chenjidiqi.icu/Article/details/gtpmbrwmip.html

UserId = int
来源：http://dali.guowangkeji.top/Article/details/gthknqbkeh.html

[U29] Py：属性校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqzeyxzp.html

@property 与 @x.setter 配合
来源：http://dali.sweek.top/Article/details/gtibrchdia.html

[U30] Py：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkjsegza.html

@dataclass(slots=True)
来源：http://dali.xinyue.icu/Article/details/gtltmamouw.html

[U31] Py：单测
来源：http://dali.pengpengdd.cyou/Article/details/gtejyttyck.html

python -m pytest -q
来源：http://dali.daxiang520.top/Article/details/gtqzbnfvvn.html

[U32] Py：代码格式化
来源：http://dali.daxiang520.top/Article/details/gtowzzzcrz.html

ruff format . && ruff check --fix .
来源：http://dali.cashguo.top/Article/details/gtubqvfjzw.html

[U33] Py：打包发布
来源：http://dali.zhongyouzk.top/Article/details/gtlkxlkiwh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nwbrower.top/Article/details/gtrzkkvdpf.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gtgpbboahn.html

chardet.detect(raw)
来源：http://dali.cucudq.cn/Article/details/gtilotqgdz.html

[U35] Py：发送邮件
来源：http://dali.chenzaomai.com/Article/details/gtzhhadogw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cucudq.cn/Article/details/gtyqdnwkoh.html

[U36] Py：定时任务
来源：http://dali.kuanghao11.cn/Article/details/gtpzznlxki.html

schedule.every(10).minutes.do(job)
来源：http://dali.fengsongda.top/Article/details/gtmuaucxmj.html

[U37] Py：读写 Excel
来源：http://dali.ppjwa.cn/Article/details/gtrwnutysh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shzxlz.cn/Article/details/gtdwthpbjo.html

[U38] Py：获取脚本所在目录
来源：http://dali.nanxuanxn.top/Article/details/gtxmptkgjp.html

Path(__file__).resolve().parent
来源：http://dali.hfpthk.cn/Article/details/gtwlvubisg.html

[U39] Py：判断是否在交互环境
来源：http://dali.zycfv.cn/Article/details/gtuxhuzqeq.html

sys.stdout.isatty()
来源：http://dali.0kj1m.cn/Article/details/gtcvyblgqt.html

[U40] Py：打印到标准错误
来源：http://dali.jinqigfzy.top/Article/details/gtvkppcytv.html

print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gtpshwuhpr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cashguo.top/Article/details/gtjqybncjc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.pengpengdd.cyou/Article/details/gttucbwrdm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hywenlv.cn/Article/details/gtemdikmbi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.c1oappe.top/Article/details/gtjbmcbcfl.html

[U43] PHP：声明命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gtgwudkaer.html

namespace App\Http;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwprbdfd.html

[U44] PHP：开启严格类型
来源：http://dali.zhixingplan.top/Article/details/gtmuzxqgkx.html

declare(strict_types=1);
来源：http://dali.xuetiantiany.cn/Article/details/gtaazzzhhi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhiwuduotai.top/Article/details/gtdhdcnpkj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gtfrgfllnh.html

[U46] PHP：可空类型
来源：http://dali.zycfv.cn/Article/details/gtetpsuytu.html

?string $name = null
来源：http://dali.cdnleiting.top/Article/details/gtbybfknrq.html

[U47] PHP：联合类型
来源：http://dali.jqgufenzy.top/Article/details/gtgxfvjndp.html

int|string $id
来源：http://dali.yongpay.top/Article/details/gtwhpdblbh.html

[U48] PHP：纯枚举
来源：http://dali.chenzaomai.com/Article/details/gtenrebapk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhoulong.xyz/Article/details/gtjffrehgf.html

[U49] PHP：只读属性
来源：http://dali.dianchejie.cn/Article/details/gtrblsmowe.html

public readonly string $name
来源：http://dali.nwbrower.top/Article/details/gtrlxnpkxk.html

[U50] PHP：构造器属性提升
来源：http://dali.yangfankeji.com/Article/details/gtbkrvrovr.html

public function __construct(private int $id) {}
来源：http://dali.hnxiangtu.top/Article/details/gtqxspjaxw.html

[U51] PHP：数组解构
来源：http://dali.zdqjudy.top/Article/details/gtivuahstd.html

[$a, $b] = $arr;
来源：http://dali.c1oappe.top/Article/details/gtjtgtkvls.html

[U52] PHP：箭头函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsdqtvdy.html

$double = fn($x) => $x * 2;
来源：http://dali.xuetiantiany.cn/Article/details/gtfsbqkldz.html

[U53] PHP：空合并运算符
来源：http://dali.ppjwa.cn/Article/details/gtsvnjtcni.html

$v = $a ?? $b ?? "default";
来源：http://dali.cqqwz.cn/Article/details/gtnuftitpb.html

[U54] PHP：空安全调用
来源：http://dali.chenjidiqi.icu/Article/details/gtvbvezrrd.html

$obj?->method()
来源：http://dali.hongshengwenyu.top/Article/details/gttbvctppl.html

[U55] PHP：match 表达式
来源：http://dali.sweek.top/Article/details/gtwfkqqzul.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hnxiangtu.top/Article/details/gtnfveqbon.html

[U56] PHP：命名参数
来源：http://dali.zhixingplan.top/Article/details/gtuftiuhfb.html

f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtvnfrynli.html

[U57] PHP：字符串插值
来源：http://dali.yj20258.top/Article/details/gtkwqpnjrq.html

"值: {$a}"
来源：http://dali.dashuyun.cn/Article/details/gttfzigalc.html

[U58] PHP：数组三件套
来源：http://dali.316326.xyz/Article/details/gtuzfvmruh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.andypj.xyz/Article/details/gtsesrguyf.html

[U59] PHP：自定义排序
来源：http://dali.hnxiangtu.top/Article/details/gtisowspcj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gtmstazppn.html

[U60] PHP：JSON 编解码
来源：http://dali.xuanzx.com/Article/details/gtjpkqrlfw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.vqdsnc.cn/Article/details/gtfbmriwou.html

[U61] PHP：正则
来源：http://dali.yonumen.top/Article/details/gtajvqahrk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.tianlin.xyz/Article/details/gtisnotckl.html

[U62] PHP：日期对象
来源：http://dali.tianlin.xyz/Article/details/gtzqvtjgzw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.fzhhl.top/Article/details/gthehecapf.html

[U63] PHP：文件读写
来源：http://dali.birdmap.top/Article/details/gtxcyzuqwv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.kuanghao11.cn/Article/details/gtubnymwks.html

[U64] PHP：目录遍历
来源：http://dali.aibaodan.cn/Article/details/gtwcjhntts.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gteuatcene.html

[U65] PHP：会话
来源：http://dali.cdnleiting.top/Article/details/gtffagrgwb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrmhpjdd.html

[U66] PHP：设置 Cookie
来源：http://dali.0kj1m.cn/Article/details/gtkewrvzcw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.redwolf501.top/Article/details/gtxdymimde.html

[U67] PHP：处理文件上传
来源：http://dali.yueranfly.top/Article/details/gtqusvfvjo.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhongyouzk.top/Article/details/gtrydjejej.html

[U68] PHP：PDO 连接
来源：http://dali.wangdashe.top/Article/details/gteqbubyhi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jiagoushi.top/Article/details/gtguvlhmgu.html

[U69] PHP：PDO 预处理
来源：http://dali.feifeiyinyue.top/Article/details/gtsmrhafyl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhengqikj.top/Article/details/gtnozhpsjb.html

[U70] PHP：PDO 事务
来源：http://dali.xziqi.cn/Article/details/gtxrhkumdy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.shzxlz.cn/Article/details/gtlgogwvic.html

[U71] PHP：抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gtdqgfkqof.html

throw new RuntimeException("失败", 500);
来源：http://dali.yuxming.cn/Article/details/gtpdahdwaa.html

[U72] PHP：写错误日志
来源：http://dali.yanxiufei.cn/Article/details/gtcgvttuqf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfygwylv.html

[U73] PHP：读取 ini 配置
来源：http://dali.gogol.net.cn/Article/details/gtgugvfvqj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjcvhjgk.html

[U74] PHP：读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtbxaoxncs.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gotoacloud.top/Article/details/gteubigyur.html

[U75] PHP：依赖注入
来源：http://dali.chenjidiqi.icu/Article/details/gtdubtohcr.html

composer require psr/container
来源：http://dali.andypj.xyz/Article/details/gtitsdkduv.html

[U76] PHP：简单路由
来源：http://dali.wangshuangyany.cn/Article/details/gtswvzbsrm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhoulong.xyz/Article/details/gtgodovses.html

[U77] PHP：模板渲染
来源：http://dali.hywenlv.cn/Article/details/gtjksgxrcy.html

composer require twig/twig
来源：http://dali.guannengcc.top/Article/details/gtiywxiqtp.html

[U78] PHP：单元测试
来源：http://dali.zhoulong.xyz/Article/details/gtfmuvpeqb.html

composer require --dev phpunit/phpunit
来源：http://dali.pycfn.com/Article/details/gtbwecxnwo.html

[U79] PHP：静态分析
来源：http://dali.aizwys.cn/Article/details/gtxctlxczf.html

composer require --dev phpstan/phpstan
来源：http://dali.jyoumei.cn/Article/details/gtkhkkhtox.html

[U80] PHP：代码规范修复
来源：http://dali.nanxuanxn.top/Article/details/gteoprwvlt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.wangshuangyany.cn/Article/details/gtsouchdcm.html

[U81] JS：初始化项目
来源：http://dali.daxiang520.top/Article/details/gthfqzwyus.html

npm init -y;  npm i express
来源：http://dali.jianghu66.top/Article/details/gtoqhsutym.html

[U82] JS：package.json 脚本
来源：http://dali.tanke756.top/Article/details/gtvaebqkup.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.chenjidiqi.icu/Article/details/gtbsizfvww.html

[U83] JS：ES Module 导入导出
来源：http://dali.gotoacloud.top/Article/details/gtkwwitzgd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gtkxprtlme.html

[U84] JS：CommonJS 写法
来源：http://dali.hammf.cn/Article/details/gthkjovzfm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yuxming.cn/Article/details/gtmhclhypv.html

[U85] JS：可选链
来源：http://dali.zhixingplan.top/Article/details/gtbechtklp.html

a?.b?.c
来源：http://dali.hnxiangtu.top/Article/details/gtuqcbnwvf.html

[U86] JS：空值合并
来源：http://dali.svipenyu.cn/Article/details/gtyoqifwzp.html

a ?? b
来源：http://dali.hfpthk.cn/Article/details/gtisultsdv.html

[U87] JS：解构默认值
来源：http://dali.xuetiantiany.cn/Article/details/gtekedfubt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ppjwa.cn/Article/details/gtwmmonhku.html

[U88] JS：对象展开合并
来源：http://dali.shanyushiyangtech.top/Article/details/gthnzyeufa.html

{ ...a, ...b }
来源：http://dali.wangshuangyany.cn/Article/details/gtaaizoita.html

[U89] JS：数组去重
来源：http://dali.aibaodan.cn/Article/details/gtmgnqllgi.html

[...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gtuhhdeojl.html

[U90] JS：数字数组排序
来源：http://dali.tian-w.cn/Article/details/gtvkqaamio.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gthbeiattt.html

[U91] JS：对象键值遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtnzueedrd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cdnleiting.top/Article/details/gtfvvrhohz.html

[U92] JS：深拷贝
来源：http://dali.yj20258888.top/Article/details/gtipfuxsyd.html

structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtzhgnaztc.html

[U93] JS：模板字符串
来源：http://dali.ppjwa.cn/Article/details/gtkrfrbsxn.html

`共 ${n} 条`
来源：http://dali.fengsongda.top/Article/details/gthgajrigg.html

[U94] JS：箭头函数
来源：http://dali.hnxiangtu.top/Article/details/gtvxzvaino.html

const double = x => x * 2;
来源：http://dali.sufxvd.cn/Article/details/gtgvmsuwyk.html

[U95] JS：Promise 包装
来源：http://dali.yonumen.top/Article/details/gtvsqyexiw.html

new Promise((resolve, reject) => {})
来源：http://dali.haohaochexian.top/Article/details/gtyaxfbdas.html

[U96] JS：async/await 与异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtautuvuih.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gtaafrflwg.html

[U97] JS：并发请求
来源：http://dali.nanxuanxn.top/Article/details/gtzjndifuk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtlebaoaoe.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gtajfwbehv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.fzhhl.top/Article/details/gtwdsdrvwr.html

[U99] JS：事件监听
来源：http://dali.c1oappe.top/Article/details/gtottmyonr.html

el.addEventListener("click", e => {})
来源：http://dali.pycfn.com/Article/details/gtrbrqbicp.html

[U100] JS：DOM 查询
来源：http://dali.9152youxi.cn/Article/details/gthnnkswzr.html

document.querySelector(".item")
来源：http://dali.daxiang520.top/Article/details/gtrhdnjmot.html

[U101] JS：classList 操作
来源：http://dali.yueranfly.top/Article/details/gthxdiggzx.html

el.classList.toggle("active")
来源：http://dali.sufxvd.cn/Article/details/gtrzckydzn.html

[U102] JS：本地存储
来源：http://dali.smart0.xyz/Article/details/gterpbdpms.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jlsjyb.cn/Article/details/gtyvxprhdd.html

[U103] JS：定时器
来源：http://dali.cashguo.top/Article/details/gtboycaldy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.svipenyu.cn/Article/details/gtbhfrcaqy.html

[U104] JS：防抖
来源：http://dali.zhiwuduotai.top/Article/details/gtvlwydgcp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtdpfhbcbe.html

[U105] JS：节流
来源：http://dali.ybcxt.top/Article/details/gtjmfffikr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.quarkkingdee.top/Article/details/gtihwhnfff.html

[U106] JS：日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtkgytgaqu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hnxiangtu.top/Article/details/gtwapyhbzk.html

[U107] JS：数字千分位
来源：http://dali.cqqwz.cn/Article/details/gtbkwtiyko.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwotbzfij.html

[U108] JS：随机整数
来源：http://dali.nwbrower.top/Article/details/gtgtcidcup.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ivvv.top/Article/details/gteyjhrzxs.html

[U109] JS：数组分组
来源：http://dali.hnqzz.top/Article/details/gtdthjevjh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yueranfly.top/Article/details/gtevezkysz.html

[U110] JS：数组分块
来源：http://dali.hongshengwenyu.top/Article/details/gtkhhxisry.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shuidangran.top/Article/details/gtqqiihpro.html

[U111] JS：对象转 Map
来源：http://dali.xuetiantiany.cn/Article/details/gtkmgnruoq.html

new Map(Object.entries(obj))
来源：http://dali.yongpay.top/Article/details/gtewruisdp.html

[U112] JS：字符串补位
来源：http://dali.zhoulong.xyz/Article/details/gtdgrjfwmt.html

"7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gthsrygkwx.html

[U113] JS：正则替换全部
来源：http://dali.jinqigfzy.top/Article/details/gteloenltu.html

s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtvmmszhvv.html

[U114] JS：JSON 深比较
来源：http://dali.hywenlv.cn/Article/details/gtourpuhda.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.kuanghao11.cn/Article/details/gtjwixcsur.html

[U115] JS：生成 UUID
来源：http://dali.yueranfly.top/Article/details/gtgmmzizrn.html

crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtcwzascxj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.chenjidiqi.icu/Article/details/gtgrkjkshn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtivdbcbgn.html

[U117] JS：单元测试
来源：http://dali.sxryk.cn/Article/details/gtbkamtnsc.html

npm i -D vitest;  npx vitest
来源：http://dali.hnxiangtu.top/Article/details/gtkhoxxbht.html

[U118] JS：开发服务器
来源：http://dali.yj20258888.top/Article/details/gtdwrzcatf.html

npm i -D vite;  npx vite
来源：http://dali.bjfxy.top/Article/details/gtzpbaxafk.html

[U119] JS：生产构建
来源：http://dali.xylfe.cn/Article/details/gtwnwhuwys.html

npx vite build
来源：http://dali.0kj1m.cn/Article/details/gturihnznp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.9152youxi.cn/Article/details/gtmpgmmari.html

import.meta.env.VITE_API_URL
来源：http://dali.zhongyouzk.top/Article/details/gtdnzfvmof.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtxhonhdno.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gtjdnemyxa.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtqxacqdjq.html

按语言统计（条）：
来源：http://dali.gogol.net.cn/Article/details/gtlpawviyl.html

Python ......... 252
来源：http://dali.quarkkingdee.top/Article/details/gttsqxtkih.html

PHP ............ 252
来源：http://dali.sufxvd.cn/Article/details/gtuhwcivvs.html

JavaScript ..... 252
来源：http://dali.tianlin.xyz/Article/details/gtrhrqtbnb.html

TypeScript ..... 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrpxtjya.html

Java ........... 212
来源：http://dali.cucudq.cn/Article/details/gttylhdeig.html

Go ............. 212
来源：http://dali.zycfv.cn/Article/details/gtibasdzhu.html

Ruby ........... 212
来源：http://dali.birdmap.top/Article/details/gtepjeuscu.html

C# ............. 212
来源：http://dali.fzhhl.top/Article/details/gtwvdiuttu.html

C .............. 30
来源：http://dali.aizwys.cn/Article/details/gtvkpznlfr.html

C++ ............ 30
来源：http://dali.jyoumei.cn/Article/details/gtjhxavauo.html

SQL ............ 90
来源：http://dali.tanke756.top/Article/details/gtwesmsirf.html

Bash ........... 80
来源：http://dali.yj202588.top/Article/details/gtsxivxsky.html

Kotlin ......... 15
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpouyiclm.html

Swift .......... 15
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzekwbqf.html

Lua ............ 10
来源：http://dali.wangdashe.top/Article/details/gtawcmdrmm.html

Perl ........... 10
来源：http://dali.feifeiyinyue.top/Article/details/gtifotidae.html

Scala .......... 10
来源：http://dali.bjfxy.top/Article/details/gtjrmjhjgx.html

------------------------------------
来源：http://dali.shuidangran.top/Article/details/gtwfiybqtm.html

合计 ........... 2106 条
来源：http://dali.9152youxi.cn/Article/details/gtsdszfudc.html

按章节统计：
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxbkfldm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xuetiantiany.cn/Article/details/gtunwtlwyy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhoulong.xyz/Article/details/gtfzttrecv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gtdrydkkzw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.pengpengdd.cyou/Article/details/gtuqpdwism.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sweek.top/Article/details/gtlluqytzp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.wangshuangyany.cn/Article/details/gtsntgrqmr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gtewumnafk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gtxgxvnlpu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gtedshngzq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gzhubu.top/Article/details/gtktmjzvxi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtaswlnack.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtoeenbgzj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmetrkrzq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hammf.cn/Article/details/gtkgiftnhr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.c1oappe.top/Article/details/gtzurlqwqs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtgztdqdkp.html

Q SQL 专题                              90
来源：http://dali.nanxinkj.top/Article/details/gthnoozdxn.html

R Bash 专题                             80
来源：http://dali.yonumen.top/Article/details/gtmdhdgabr.html

S C / C++ 专题                          60
来源：http://dali.cqqwz.cn/Article/details/gtbfdixgpe.html

T 其他语言补充                          60
来源：http://dali.yuxming.cn/Article/details/gtltlwhiem.html


<!-- 参考信息 -->