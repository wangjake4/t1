代发 wailian999

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.daria6918.cn/Article/details/gtasffwkew.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtjfqcxori.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aibaodan.cn/Article/details/gthprqjvzm.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtzwyfwpgw.html

[U01] Py：创建虚拟环境
来源：http://dali.tian-w.cn/Article/details/gtvohzyias.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xinyue.icu/Article/details/gteumhcarb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yanxiufei.cn/Article/details/gtjlekiccg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.kuanghao11.cn/Article/details/gtvdclzvum.html

[U03] Py：加载 .env 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyiwtucl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.0kj1m.cn/Article/details/gtuqifbhbb.html

[U04] Py：变量调试打印
来源：http://dali.yvedp.cn/Article/details/gtbyvblhmj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nwbrower.top/Article/details/gtkcueirzr.html

[U05] Py：列表去重且保序
来源：http://dali.ehwqpu.com/Article/details/gtxhturepv.html

list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtigygxitu.html

[U06] Py：合并两个字典
来源：http://dali.svipenyu.cn/Article/details/gtlgswslal.html

{**a, **b}
来源：http://dali.shzxlz.cn/Article/details/gthqarbvsi.html

[U07] Py：反转字典键值
来源：http://dali.aizwys.cn/Article/details/gtnhrlvojk.html

{v: k for k, v in d.items()}
来源：http://dali.xinyue.icu/Article/details/gtzjtuykbt.html

[U08] Py：展平二维列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebxcfqye.html

[y for x in nested for y in x]
来源：http://dali.cheryme.top/Article/details/gtglfwvwfp.html

[U09] Py：字典取最大值的键
来源：http://dali.mhx1999.top/Article/details/gtcbuhsczp.html

max(d, key=d.get)
来源：http://dali.jqgufenzy.top/Article/details/gtiqbbcddt.html

[U10] Py：按值排序字典
来源：http://dali.xylfe.cn/Article/details/gtlycpbrfi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hnqzz.top/Article/details/gtkyxwpadq.html

[U11] Py：生成器表达式
来源：http://dali.cqqwz.cn/Article/details/gtqhxglnox.html

(x * 2 for x in arr)
来源：http://dali.cucudq.cn/Article/details/gttguzrjqy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cqqwz.cn/Article/details/gtdgkntjjp.html

Counter(arr).most_common(3)
来源：http://dali.shuidangran.top/Article/details/gtndezugud.html

[U13] Py：固定长度队列
来源：http://dali.cdnleiting.top/Article/details/gtlwvoohva.html

deque(maxlen=10)
来源：http://dali.hfpthk.cn/Article/details/gtymdixrzv.html

[U14] Py：分组收集到列表
来源：http://dali.xinyue.icu/Article/details/gtvpuiddtk.html

defaultdict(list)
来源：http://dali.hfpthk.cn/Article/details/gtnntpjqmk.html

[U15] Py：高精度计时
来源：http://dali.cdnleiting.top/Article/details/gtjovvlwqe.html

t = time.perf_counter()
来源：http://dali.yuxming.cn/Article/details/gtxtkdkbog.html

[U16] Py：命令行参数解析
来源：http://dali.vqdsnc.cn/Article/details/gtofinpmgj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuanzhike.top/Article/details/gtzuikaprb.html

[U17] Py：初始化日志
来源：http://dali.dianchejie.cn/Article/details/gtohrldwfq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yj20258888.top/Article/details/gtmzpebajy.html

[U18] Py：预编译正则
来源：http://dali.shzxlz.cn/Article/details/gtsxmqidpp.html

pat = re.compile(r"\d+")
来源：http://dali.nanxinkj.top/Article/details/gtgfunkxne.html

[U19] Py：正则替换带回调
来源：http://dali.jqgfzy.top/Article/details/gtgqdmpydh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj20258888.top/Article/details/gtcmpuoqqb.html

[U20] Py：缓存函数结果
来源：http://dali.ydzc1.top/Article/details/gtwhnlwqdf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.pengpengdd.cyou/Article/details/gtjvkxnutq.html

[U21] Py：自定义上下文管理器
来源：http://dali.wangshuangyany.cn/Article/details/gtkmdvyvvq.html

@contextlib.contextmanager
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlheudoeq.html

[U22] Py：矩阵转置
来源：http://dali.0kj1m.cn/Article/details/gtaxhelfsp.html

list(zip(*m))
来源：http://dali.sysykeji.top/Article/details/gtyjkqprmz.html

[U23] Py：分块读取大文件
来源：http://dali.nanxinkj.top/Article/details/gttifvhhie.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenjidiqi.icu/Article/details/gtptqujime.html

[U24] Py：路径操作
来源：http://dali.iojbl.cn/Article/details/gtzjexwrku.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gtaqoppaen.html

[U25] Py：CSV 按字典读
来源：http://dali.zdqjudy.top/Article/details/gtbhhnyyme.html

csv.DictReader(f)
来源：http://dali.cdnleiting.top/Article/details/gtkppfqmmg.html

[U26] Py：并发下载
来源：http://dali.chenzaomai.com/Article/details/gtircqqdjd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.quarkkingdee.top/Article/details/gtsjufjcxk.html

[U27] Py：异步 HTTP
来源：http://dali.pengpengdd.cyou/Article/details/gtyrrncnrh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.iojbl.cn/Article/details/gtsxjmqsze.html

[U28] Py：类型别名
来源：http://dali.shzxlz.cn/Article/details/gtqebgassq.html

UserId = int
来源：http://dali.hfpthk.cn/Article/details/gtwzkxrmoc.html

[U29] Py：属性校验
来源：http://dali.yuanzhike.top/Article/details/gtdvsmsvfb.html

@property 与 @x.setter 配合
来源：http://dali.9152youxi.cn/Article/details/gtssvjigas.html

[U30] Py：数据类
来源：http://dali.yj20258888.top/Article/details/gtfvudhgsf.html

@dataclass(slots=True)
来源：http://dali.gogol.net.cn/Article/details/gtoiwntzgu.html

[U31] Py：单测
来源：http://dali.hysaishi.cn/Article/details/gtlngvkgrc.html

python -m pytest -q
来源：http://dali.chenzaomai.com/Article/details/gtkmztljbc.html

[U32] Py：代码格式化
来源：http://dali.havefunace.top/Article/details/gtzifiinqg.html

ruff format . && ruff check --fix .
来源：http://dali.shuidangran.top/Article/details/gtmnrjzsjx.html

[U33] Py：打包发布
来源：http://dali.ydzc1.top/Article/details/gtqlizoklb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.tianlin.xyz/Article/details/gtdkwrzsco.html

[U34] Py：判断编码
来源：http://dali.shzxlz.cn/Article/details/gtyjjhakft.html

chardet.detect(raw)
来源：http://dali.sweek.top/Article/details/gtvmrukins.html

[U35] Py：发送邮件
来源：http://dali.gogol.net.cn/Article/details/gtjhjjfkzi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yangfankeji.com/Article/details/gtloilvysq.html

[U36] Py：定时任务
来源：http://dali.haohaochexian.top/Article/details/gtsjhxizjv.html

schedule.every(10).minutes.do(job)
来源：http://dali.xinyue.icu/Article/details/gtbmfqkdzt.html

[U37] Py：读写 Excel
来源：http://dali.jyoumei.cn/Article/details/gttivlbyjb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.chenzaomai.com/Article/details/gtswtbwzlw.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gtchcqntza.html

Path(__file__).resolve().parent
来源：http://dali.yongpay.top/Article/details/gtfdubkrww.html

[U39] Py：判断是否在交互环境
来源：http://dali.aibaodan.cn/Article/details/gtfhamwrix.html

sys.stdout.isatty()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzqhsppl.html

[U40] Py：打印到标准错误
来源：http://dali.cheryme.top/Article/details/gtzvvzpmxi.html

print("err", file=sys.stderr)
来源：http://dali.jinqigfzy.top/Article/details/gtpediaqts.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.meibo888.top/Article/details/gtahxjbnvw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shangyingyoupin.top/Article/details/gtlzusvdwg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.0kj1m.cn/Article/details/gtgxcbmtpr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.sweek.top/Article/details/gtwfndefka.html

[U43] PHP：声明命名空间
来源：http://dali.yuanzhike.top/Article/details/gtadkdgoom.html

namespace App\Http;
来源：http://dali.aizwys.cn/Article/details/gttwmpbutd.html

[U44] PHP：开启严格类型
来源：http://dali.zhixingplan.top/Article/details/gtdzocnjmn.html

declare(strict_types=1);
来源：http://dali.tian-w.cn/Article/details/gtuqsgnqre.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yuxming.cn/Article/details/gtejrkstpq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtgtausekz.html

[U46] PHP：可空类型
来源：http://dali.hysaishi.cn/Article/details/gtxevqgtgt.html

?string $name = null
来源：http://dali.ehwqpu.com/Article/details/gttqpcpnls.html

[U47] PHP：联合类型
来源：http://dali.shuidangran.top/Article/details/gtxkmwsaaa.html

int|string $id
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfcwmsui.html

[U48] PHP：纯枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtjmqsxvef.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shzxlz.cn/Article/details/gtzdnawhbh.html

[U49] PHP：只读属性
来源：http://dali.gotoacloud.top/Article/details/gtvaudasfp.html

public readonly string $name
来源：http://dali.sxryk.cn/Article/details/gtdijduxdw.html

[U50] PHP：构造器属性提升
来源：http://dali.yvedp.cn/Article/details/gtfvmvylqo.html

public function __construct(private int $id) {}
来源：http://dali.shzxlz.cn/Article/details/gtfbharzsj.html

[U51] PHP：数组解构
来源：http://dali.hongshengwenyu.top/Article/details/gtfsgwmvfk.html

[$a, $b] = $arr;
来源：http://dali.shanyushiyangtech.top/Article/details/gthosbwoqt.html

[U52] PHP：箭头函数
来源：http://dali.shangyingyoupin.top/Article/details/gtwzohoghe.html

$double = fn($x) => $x * 2;
来源：http://dali.wangshuangyany.cn/Article/details/gtxpywrhje.html

[U53] PHP：空合并运算符
来源：http://dali.c1oappe.top/Article/details/gtzeuxshdt.html

$v = $a ?? $b ?? "default";
来源：http://dali.mhx1999.top/Article/details/gtohqcpnoy.html

[U54] PHP：空安全调用
来源：http://dali.jianghu66.top/Article/details/gtanxqgibk.html

$obj?->method()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjuuiczdz.html

[U55] PHP：match 表达式
来源：http://dali.aizwys.cn/Article/details/gtxtxpczsq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zdqjudy.top/Article/details/gtgpjgporb.html

[U56] PHP：命名参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdvsigol.html

f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtrcqohirk.html

[U57] PHP：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqoyvrkp.html

"值: {$a}"
来源：http://dali.jianghu66.top/Article/details/gtrvwdkgeo.html

[U58] PHP：数组三件套
来源：http://dali.hywenlv.cn/Article/details/gttikjikkn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shzxlz.cn/Article/details/gtotgwsshu.html

[U59] PHP：自定义排序
来源：http://dali.sufxvd.cn/Article/details/gtqaabmioh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gaohongyu789.top/Article/details/gtojdqfxvt.html

[U60] PHP：JSON 编解码
来源：http://dali.smart0.xyz/Article/details/gtqenbxcfy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jiagoushi.top/Article/details/gteltdlzph.html

[U61] PHP：正则
来源：http://dali.nwbrower.top/Article/details/gtavukehya.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gtjrziqpuc.html

[U62] PHP：日期对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibkjtkmu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jqgufenzy.top/Article/details/gtqodxfdpk.html

[U63] PHP：文件读写
来源：http://dali.cqqwz.cn/Article/details/gtteihleud.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.daxiang520.top/Article/details/gtqhumrkex.html

[U64] PHP：目录遍历
来源：http://dali.birdmap.top/Article/details/gtlidfvmbm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj20258.top/Article/details/gtpdwtckbm.html

[U65] PHP：会话
来源：http://dali.316326.xyz/Article/details/gtmcswyrfv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.tanke756.top/Article/details/gtenwkbwpa.html

[U66] PHP：设置 Cookie
来源：http://dali.hongshengwenyu.top/Article/details/gtucjieqzo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.havefunace.top/Article/details/gthiiyyyph.html

[U67] PHP：处理文件上传
来源：http://dali.dianchejie.cn/Article/details/gtcozjorhz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.redwolf501.top/Article/details/gtzsvvqqxx.html

[U68] PHP：PDO 连接
来源：http://dali.xziqi.cn/Article/details/gtlwondxky.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yvedp.cn/Article/details/gtpbzlroji.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gtagrzeodd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jqgfzy.top/Article/details/gtzyzjxegr.html

[U70] PHP：PDO 事务
来源：http://dali.hnqzz.top/Article/details/gtzaphtnbd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cheryme.top/Article/details/gtgxjtnjlr.html

[U71] PHP：抛出异常
来源：http://dali.birdmap.top/Article/details/gtsxxhsdyu.html

throw new RuntimeException("失败", 500);
来源：http://dali.0kj1m.cn/Article/details/gtcfymnwwv.html

[U72] PHP：写错误日志
来源：http://dali.zdqjudy.top/Article/details/gtlcosiatz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.fzhhl.top/Article/details/gtupglsced.html

[U73] PHP：读取 ini 配置
来源：http://dali.vqdsnc.cn/Article/details/gtjtipsnfk.html

parse_ini_file("config.ini", true)
来源：http://dali.gaohongyu789.top/Article/details/gtsoannifd.html

[U74] PHP：读取环境变量
来源：http://dali.yuxming.cn/Article/details/gtrimozcse.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jyoumei.cn/Article/details/gtjroayjqq.html

[U75] PHP：依赖注入
来源：http://dali.fengsongda.top/Article/details/gtyekdnzjt.html

composer require psr/container
来源：http://dali.jqgfzy.top/Article/details/gtmtzbxqvq.html

[U76] PHP：简单路由
来源：http://dali.9152youxi.cn/Article/details/gtcerehylw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xinyue.icu/Article/details/gtwjrahgjm.html

[U77] PHP：模板渲染
来源：http://dali.daxiang520.top/Article/details/gtebemcqzv.html

composer require twig/twig
来源：http://dali.0kj1m.cn/Article/details/gtwhnfiygv.html

[U78] PHP：单元测试
来源：http://dali.cucudq.cn/Article/details/gtxmgqbmrr.html

composer require --dev phpunit/phpunit
来源：http://dali.aibaodan.cn/Article/details/gtpaqyqucc.html

[U79] PHP：静态分析
来源：http://dali.iojbl.cn/Article/details/gtqwjwhlhu.html

composer require --dev phpstan/phpstan
来源：http://dali.dianchejie.cn/Article/details/gthagvyuhl.html

[U80] PHP：代码规范修复
来源：http://dali.chenlongwang.top/Article/details/gtdvigbyrt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yvedp.cn/Article/details/gtkomfhrgg.html

[U81] JS：初始化项目
来源：http://dali.jinqigufen.top/Article/details/gtawcqgcwe.html

npm init -y;  npm i express
来源：http://dali.hfpthk.cn/Article/details/gtvtgbxejq.html

[U82] JS：package.json 脚本
来源：http://dali.wangdashe.top/Article/details/gtksyskivl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.chenjidiqi.icu/Article/details/gtbuhuxohd.html

[U83] JS：ES Module 导入导出
来源：http://dali.sysykeji.top/Article/details/gtxfnykiul.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yonumen.top/Article/details/gtabcdyvfj.html

[U84] JS：CommonJS 写法
来源：http://dali.hysaishi.cn/Article/details/gtfmlokkqw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.tanke756.top/Article/details/gtjnjejyok.html

[U85] JS：可选链
来源：http://dali.jqgufenzy.top/Article/details/gtbyheogve.html

a?.b?.c
来源：http://dali.dashuyun.cn/Article/details/gtcbyufvfa.html

[U86] JS：空值合并
来源：http://dali.yongpay.top/Article/details/gtnsgyhgqg.html

a ?? b
来源：http://dali.zhoulong.xyz/Article/details/gtcfdaqluj.html

[U87] JS：解构默认值
来源：http://dali.birdmap.top/Article/details/gtutiftbww.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinqigufen.top/Article/details/gtwrnmfhug.html

[U88] JS：对象展开合并
来源：http://dali.zycfv.cn/Article/details/gtpmfbnlye.html

{ ...a, ...b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvtanidd.html

[U89] JS：数组去重
来源：http://dali.feifeiyinyue.top/Article/details/gttclqtdxh.html

[...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gtajjtvwsf.html

[U90] JS：数字数组排序
来源：http://dali.jianghu66.top/Article/details/gtskcjwowo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtgytcsxay.html

[U91] JS：对象键值遍历
来源：http://dali.ydzc1.top/Article/details/gtvmtxtull.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngshjywi.html

[U92] JS：深拷贝
来源：http://dali.yvedp.cn/Article/details/gtejrskajy.html

structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtfvqmmptw.html

[U93] JS：模板字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtnebaqcct.html

`共 ${n} 条`
来源：http://dali.aizwys.cn/Article/details/gtpcvbarem.html

[U94] JS：箭头函数
来源：http://dali.andypj.xyz/Article/details/gtczmqxbhf.html

const double = x => x * 2;
来源：http://dali.aibaodan.cn/Article/details/gtmvgwgvev.html

[U95] JS：Promise 包装
来源：http://dali.yanxiufei.cn/Article/details/gtfouvoyuj.html

new Promise((resolve, reject) => {})
来源：http://dali.chenzaomai.com/Article/details/gtbpdfavwo.html

[U96] JS：async/await 与异常
来源：http://dali.hywenlv.cn/Article/details/gtjspdplrj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtbpspcxkw.html

[U97] JS：并发请求
来源：http://dali.vqdsnc.cn/Article/details/gtwxwqncso.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtckeiedlo.html

[U98] JS：fetch 带 JSON
来源：http://dali.aizwys.cn/Article/details/gtnhmblole.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.nanxinkj.top/Article/details/gtiqqeutkf.html

[U99] JS：事件监听
来源：http://dali.yanxiufei.cn/Article/details/gtztoolkmp.html

el.addEventListener("click", e => {})
来源：http://dali.nanxuanxn.top/Article/details/gtlqflmhea.html

[U100] JS：DOM 查询
来源：http://dali.iojbl.cn/Article/details/gtagqpzvrb.html

document.querySelector(".item")
来源：http://dali.hysaishi.cn/Article/details/gtpuzogtox.html

[U101] JS：classList 操作
来源：http://dali.pycfn.com/Article/details/gtpgkhprgv.html

el.classList.toggle("active")
来源：http://dali.dianchejie.cn/Article/details/gtgttkxjvp.html

[U102] JS：本地存储
来源：http://dali.xziqi.cn/Article/details/gtsbiwtagn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sysykeji.top/Article/details/gtaunvprqt.html

[U103] JS：定时器
来源：http://dali.316326.xyz/Article/details/gtgwyrnrcu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.guowangkeji.top/Article/details/gtlbuqqesk.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gtqjhpxzks.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gtrmdtlxkb.html

[U105] JS：节流
来源：http://dali.ydzc1.top/Article/details/gtrwmgnxbo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.fzhhl.top/Article/details/gtrpgwnoiq.html

[U106] JS：日期格式化
来源：http://dali.daria6918.cn/Article/details/gtwkwxjpje.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.haohaochexian.top/Article/details/gtuqbxvurm.html

[U107] JS：数字千分位
来源：http://dali.pengpengdd.cyou/Article/details/gtxksectar.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zycfv.cn/Article/details/gtkxcsptwn.html

[U108] JS：随机整数
来源：http://dali.sysykeji.top/Article/details/gtwijfxvvh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jqgufenzy.top/Article/details/gttedwhcuu.html

[U109] JS：数组分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggnuxybq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.aizwys.cn/Article/details/gtnpsziqgj.html

[U110] JS：数组分块
来源：http://dali.snrcjt.cn/Article/details/gtyhgczuom.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ivvv.top/Article/details/gtevrrpjmz.html

[U111] JS：对象转 Map
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcnggnky.html

new Map(Object.entries(obj))
来源：http://dali.nanxuanxn.top/Article/details/gttgjvquan.html

[U112] JS：字符串补位
来源：http://dali.sysykeji.top/Article/details/gttmkohryg.html

"7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtbasmjlst.html

[U113] JS：正则替换全部
来源：http://dali.ybcxt.top/Article/details/gtzcpslwgy.html

s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtsxijfnba.html

[U114] JS：JSON 深比较
来源：http://dali.nwbrower.top/Article/details/gtturfjyjm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgscltnb.html

[U115] JS：生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gtghtcapwh.html

crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtfhbvapvr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yj20258888.top/Article/details/gtoulrcmtc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.9152youxi.cn/Article/details/gtfaaikkno.html

[U117] JS：单元测试
来源：http://dali.sxryk.cn/Article/details/gtkjrozxvh.html

npm i -D vitest;  npx vitest
来源：http://dali.ehwqpu.com/Article/details/gtuexfneck.html

[U118] JS：开发服务器
来源：http://dali.hysaishi.cn/Article/details/gtmruhdnle.html

npm i -D vite;  npx vite
来源：http://dali.yj20258.top/Article/details/gtoamqkjls.html

[U119] JS：生产构建
来源：http://dali.chenzaomai.com/Article/details/gtoxjaizyc.html

npx vite build
来源：http://dali.snrcjt.cn/Article/details/gtcqrityyo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cdnleiting.top/Article/details/gttzovrses.html

import.meta.env.VITE_API_URL
来源：http://dali.sweek.top/Article/details/gtpdcgyayw.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtorwmkxrk.html

统计汇总
来源：http://dali.cheryme.top/Article/details/gtqbbasiav.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtvblhoppz.html

按语言统计（条）：
来源：http://dali.cashguo.top/Article/details/gtspesonvx.html

Python ......... 252
来源：http://dali.yuanzhike.top/Article/details/gtdpobpnor.html

PHP ............ 252
来源：http://dali.jinqigfzy.top/Article/details/gteigcqyvl.html

JavaScript ..... 252
来源：http://dali.pycfn.com/Article/details/gtuoweuoua.html

TypeScript ..... 212
来源：http://dali.snrcjt.cn/Article/details/gtphipxytj.html

Java ........... 212
来源：http://dali.guowangkeji.top/Article/details/gtdrgonxnj.html

Go ............. 212
来源：http://dali.xylfe.cn/Article/details/gtoaajwunl.html

Ruby ........... 212
来源：http://dali.chenjidiqi.icu/Article/details/gtdiyetmir.html

C# ............. 212
来源：http://dali.svipenyu.cn/Article/details/gtvrcwbblk.html

C .............. 30
来源：http://dali.sxryk.cn/Article/details/gtyqvwsgfh.html

C++ ............ 30
来源：http://dali.gzhubu.top/Article/details/gthvdwzzur.html

SQL ............ 90
来源：http://dali.gotoacloud.top/Article/details/gtoizuixin.html

Bash ........... 80
来源：http://dali.chenjidiqi.icu/Article/details/gtwistnesa.html

Kotlin ......... 15
来源：http://dali.birdmap.top/Article/details/gtoblsjjal.html

Swift .......... 15
来源：http://dali.cucudq.cn/Article/details/gtbhqcmpxi.html

Lua ............ 10
来源：http://dali.tian-w.cn/Article/details/gtfkargrjc.html

Perl ........... 10
来源：http://dali.guowangkeji.top/Article/details/gtnciwemei.html

Scala .......... 10
来源：http://dali.yanxiufei.cn/Article/details/gtffefzeuz.html

------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gtupnkowqj.html

合计 ........... 2106 条
来源：http://dali.iojbl.cn/Article/details/gtzbambkvy.html

按章节统计：
来源：http://dali.ydzc1.top/Article/details/gtzuhdyoft.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gogol.net.cn/Article/details/gtphfoogdr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.quarkkingdee.top/Article/details/gtnvlemzos.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gtijypaodb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.havefunace.top/Article/details/gthayxstyw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.kuanghao11.cn/Article/details/gttjryymvk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.aizwys.cn/Article/details/gtddzekyvj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yongpay.top/Article/details/gtjhjilafd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.guowangkeji.top/Article/details/gtnnxtrryb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gttrxhomux.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jqgufenzy.top/Article/details/gtivyfcjnt.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtzhedoqjc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gtnwxqpwbi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtrsjcbbav.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.birdmap.top/Article/details/gtaexdhrxq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.vqdsnc.cn/Article/details/gttrcgxijm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtlqhrmzbn.html

Q SQL 专题                              90
来源：http://dali.hysaishi.cn/Article/details/gttjpnftdr.html

R Bash 专题                             80
来源：http://dali.svipenyu.cn/Article/details/gtyqehvmft.html

S C / C++ 专题                          60
来源：http://dali.snrcjt.cn/Article/details/gtpgumqysm.html

T 其他语言补充                          60
来源：http://dali.hongshengwenyu.top/Article/details/gtemewgeip.html

U 高频实用片段                         120
来源：http://dali.smart0.xyz/Article/details/gtjwtpmfck.html

------------------------------------
来源：http://dali.redwolf501.top/Article/details/gttrrvrfhc.html

合计                                  2106 条
来源：http://dali.yj20258.top/Article/details/gtfotbbdqt.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtzcxbafvh.html

使用提醒
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzahshjm.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gthlkjgwhg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zycfv.cn/Article/details/gtflmjlcii.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jianghu66.top/Article/details/gtwwanxywt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.guannengcc.top/Article/details/gtzwvylzie.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.c1oappe.top/Article/details/gtzahtadge.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.guannengcc.top/Article/details/gtkpbasisc.html

—— 文件结束 ——
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkchjdmfs.html


<!-- 参考信息 -->