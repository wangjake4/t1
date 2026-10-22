代发 wailian999

[U01] Py：创建虚拟环境
来源：http://dali.gzhubu.top/Article/details/gthpgzffaj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.smart0.xyz/Article/details/gtgyhnbqhg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.feifeiyinyue.top/Article/details/gtjhkwhvga.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yuanzhike.top/Article/details/gttvqtpghp.html

[U03] Py：加载 .env 配置
来源：http://dali.yueranfly.top/Article/details/gtxeyhgzko.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinqigufen.top/Article/details/gtqgrbsdua.html

[U04] Py：变量调试打印
来源：http://dali.dashuyun.cn/Article/details/gtwvkpxodw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.0kj1m.cn/Article/details/gtwsbrjmxz.html

[U05] Py：列表去重且保序
来源：http://dali.jyoumei.cn/Article/details/gtddlbfssi.html

list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gtluuzgsvf.html

[U06] Py：合并两个字典
来源：http://dali.ybcxt.top/Article/details/gtzefomasd.html

{**a, **b}
来源：http://dali.yonumen.top/Article/details/gtblcetoec.html

[U07] Py：反转字典键值
来源：http://dali.0kj1m.cn/Article/details/gtgzzafqwf.html

{v: k for k, v in d.items()}
来源：http://dali.zdqjudy.top/Article/details/gtbgcbjluw.html

[U08] Py：展平二维列表
来源：http://dali.daxiang520.top/Article/details/gtjkzdqnvo.html

[y for x in nested for y in x]
来源：http://dali.yvedp.cn/Article/details/gtqjaehxbt.html

[U09] Py：字典取最大值的键
来源：http://dali.feifeiyinyue.top/Article/details/gtrpqgmspa.html

max(d, key=d.get)
来源：http://dali.sysykeji.top/Article/details/gtmbqrxnxh.html

[U10] Py：按值排序字典
来源：http://dali.mhx1999.top/Article/details/gtgxriurlf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ybcxt.top/Article/details/gtkbixcvpu.html

[U11] Py：生成器表达式
来源：http://dali.ydzc1.top/Article/details/gttezfhnqh.html

(x * 2 for x in arr)
来源：http://dali.aizwys.cn/Article/details/gtfyhaivdd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinqigufen.top/Article/details/gtanvgomgp.html

Counter(arr).most_common(3)
来源：http://dali.nanxinkj.top/Article/details/gtjjhsavys.html

[U13] Py：固定长度队列
来源：http://dali.cdnleiting.top/Article/details/gtzkpovzhi.html

deque(maxlen=10)
来源：http://dali.yj202588.top/Article/details/gtmfxpgnob.html

[U14] Py：分组收集到列表
来源：http://dali.zycfv.cn/Article/details/gtxsdutbsd.html

defaultdict(list)
来源：http://dali.ydzc1.top/Article/details/gtmxgahmbg.html

[U15] Py：高精度计时
来源：http://dali.meibo888.top/Article/details/gtbcordwhz.html

t = time.perf_counter()
来源：http://dali.gogol.net.cn/Article/details/gtzpbwqpsv.html

[U16] Py：命令行参数解析
来源：http://dali.meibo888.top/Article/details/gthmrlzrba.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.fengsongda.top/Article/details/gtnfpkyvbl.html

[U17] Py：初始化日志
来源：http://dali.zycfv.cn/Article/details/gtjgugtyzg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhongyouzk.top/Article/details/gtihczpema.html

[U18] Py：预编译正则
来源：http://dali.kuanghao11.cn/Article/details/gtiakqkdki.html

pat = re.compile(r"\d+")
来源：http://dali.nwbrower.top/Article/details/gturwnzhbd.html

[U19] Py：正则替换带回调
来源：http://dali.jyoumei.cn/Article/details/gthcvgteaq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tian-w.cn/Article/details/gtvwteabdk.html

[U20] Py：缓存函数结果
来源：http://dali.yvedp.cn/Article/details/gtaieejtqf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.316326.xyz/Article/details/gtzmeyoxum.html

[U21] Py：自定义上下文管理器
来源：http://dali.iojbl.cn/Article/details/gtcciaxajo.html

@contextlib.contextmanager
来源：http://dali.zycfv.cn/Article/details/gtgyrjiujj.html

[U22] Py：矩阵转置
来源：http://dali.zhongyouzk.top/Article/details/gtmqfuzzwa.html

list(zip(*m))
来源：http://dali.shzxlz.cn/Article/details/gtlvbwlece.html

[U23] Py：分块读取大文件
来源：http://dali.iojbl.cn/Article/details/gtjinooras.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cucudq.cn/Article/details/gtyvoxwrgx.html

[U24] Py：路径操作
来源：http://dali.zycfv.cn/Article/details/gthdvjrcqv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.mhx1999.top/Article/details/gticmpstzb.html

[U25] Py：CSV 按字典读
来源：http://dali.yvedp.cn/Article/details/gtmourzabp.html

csv.DictReader(f)
来源：http://dali.jyoumei.cn/Article/details/gtmorspxuq.html

[U26] Py：并发下载
来源：http://dali.wangdashe.top/Article/details/gtgvnqviic.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jiagoushi.top/Article/details/gtizabuvse.html

[U27] Py：异步 HTTP
来源：http://dali.sufxvd.cn/Article/details/gtimwhuxkj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.nwbrower.top/Article/details/gtxjjcztpi.html

[U28] Py：类型别名
来源：http://dali.yanxiufei.cn/Article/details/gtizyuhial.html

UserId = int
来源：http://dali.ehwqpu.com/Article/details/gtdzgbvxed.html

[U29] Py：属性校验
来源：http://dali.ehwqpu.com/Article/details/gtjgqbwfcj.html

@property 与 @x.setter 配合
来源：http://dali.xylfe.cn/Article/details/gtbfrnljrb.html

[U30] Py：数据类
来源：http://dali.wangshuangyany.cn/Article/details/gtrdchxcjd.html

@dataclass(slots=True)
来源：http://dali.ehwqpu.com/Article/details/gteqshwzop.html

[U31] Py：单测
来源：http://dali.daria6918.cn/Article/details/gttbmvjwwp.html

python -m pytest -q
来源：http://dali.guowangkeji.top/Article/details/gtjknjrwzj.html

[U32] Py：代码格式化
来源：http://dali.jyoumei.cn/Article/details/gtkbrncmru.html

ruff format . && ruff check --fix .
来源：http://dali.ppjwa.cn/Article/details/gtjqmcebaw.html

[U33] Py：打包发布
来源：http://dali.ybcxt.top/Article/details/gtfdfaglqn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yvedp.cn/Article/details/gtszjohmdn.html

[U34] Py：判断编码
来源：http://dali.gzhubu.top/Article/details/gtlasxgwtt.html

chardet.detect(raw)
来源：http://dali.cashguo.top/Article/details/gtaeiuvbxl.html

[U35] Py：发送邮件
来源：http://dali.sysykeji.top/Article/details/gtytxhgfei.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ybcxt.top/Article/details/gtxkxczfwj.html

[U36] Py：定时任务
来源：http://dali.pengpengdd.cyou/Article/details/gtjegfmorp.html

schedule.every(10).minutes.do(job)
来源：http://dali.cqqwz.cn/Article/details/gtnzwdjzhc.html

[U37] Py：读写 Excel
来源：http://dali.bjfxy.top/Article/details/gtdonajdnw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yuxming.cn/Article/details/gtfxjgheaz.html

[U38] Py：获取脚本所在目录
来源：http://dali.quarkkingdee.top/Article/details/gtsdcbasry.html

Path(__file__).resolve().parent
来源：http://dali.pengpengdd.cyou/Article/details/gtvvjwnpnl.html

[U39] Py：判断是否在交互环境
来源：http://dali.guowangkeji.top/Article/details/gtwnmqgmzh.html

sys.stdout.isatty()
来源：http://dali.birdmap.top/Article/details/gtzwedddqz.html

[U40] Py：打印到标准错误
来源：http://dali.ehwqpu.com/Article/details/gtrswrwbjm.html

print("err", file=sys.stderr)
来源：http://dali.cashguo.top/Article/details/gtdtlhpext.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.meibo888.top/Article/details/gtxajuxqdw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cheryme.top/Article/details/gtjyfkzelx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhoulong.xyz/Article/details/gtneqdxhgx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cucudq.cn/Article/details/gtutkpthxh.html

[U43] PHP：声明命名空间
来源：http://dali.pycfn.com/Article/details/gtsbvwnncz.html

namespace App\Http;
来源：http://dali.ehwqpu.com/Article/details/gtahuklpep.html

[U44] PHP：开启严格类型
来源：http://dali.tianlin.xyz/Article/details/gtwrqczzvi.html

declare(strict_types=1);
来源：http://dali.birdmap.top/Article/details/gtucewierz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.nanxinkj.top/Article/details/gtlnhviqha.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtyfiwpxeh.html

[U46] PHP：可空类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtmexvzjpe.html

?string $name = null
来源：http://dali.fengsongda.top/Article/details/gtwqhdbqas.html

[U47] PHP：联合类型
来源：http://dali.xuetiantiany.cn/Article/details/gtdkicqhbu.html

int|string $id
来源：http://dali.jlsjyb.cn/Article/details/gtrypljgmj.html

[U48] PHP：纯枚举
来源：http://dali.aizwys.cn/Article/details/gtdcaondpk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdexpashj.html

[U49] PHP：只读属性
来源：http://dali.hammf.cn/Article/details/gtddqhleeh.html

public readonly string $name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnevdbku.html

[U50] PHP：构造器属性提升
来源：http://dali.mhx1999.top/Article/details/gtshnbwbzv.html

public function __construct(private int $id) {}
来源：http://dali.mhx1999.top/Article/details/gtbjwcaqxq.html

[U51] PHP：数组解构
来源：http://dali.jinqigfzy.top/Article/details/gthswwltoz.html

[$a, $b] = $arr;
来源：http://dali.yj20258888.top/Article/details/gtjkykzcja.html

[U52] PHP：箭头函数
来源：http://dali.shangyingyoupin.top/Article/details/gtayzrzruk.html

$double = fn($x) => $x * 2;
来源：http://dali.iojbl.cn/Article/details/gtbnjvijaa.html

[U53] PHP：空合并运算符
来源：http://dali.dashuyun.cn/Article/details/gtepevbhfg.html

$v = $a ?? $b ?? "default";
来源：http://dali.jianghu66.top/Article/details/gtyrsxwfzm.html

[U54] PHP：空安全调用
来源：http://dali.yj202588.top/Article/details/gtwkaauhpk.html

$obj?->method()
来源：http://dali.jyoumei.cn/Article/details/gtnbtyvugt.html

[U55] PHP：match 表达式
来源：http://dali.0kj1m.cn/Article/details/gtfyootmew.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xuetiantiany.cn/Article/details/gtfkulebpt.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gtjafpqrbd.html

f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gtvkuriwpz.html

[U57] PHP：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtywxxpjom.html

"值: {$a}"
来源：http://dali.gotoacloud.top/Article/details/gtufhqfkts.html

[U58] PHP：数组三件套
来源：http://dali.sufxvd.cn/Article/details/gtvmgeifch.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtfgazzulo.html

[U59] PHP：自定义排序
来源：http://dali.yangfankeji.com/Article/details/gtwfnlytep.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gtclaokxpj.html

[U60] PHP：JSON 编解码
来源：http://dali.0kj1m.cn/Article/details/gtwynpdhls.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.tian-w.cn/Article/details/gtepvkadgg.html

[U61] PHP：正则
来源：http://dali.yanxiufei.cn/Article/details/gtdreppucv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtfmuxlcxa.html

[U62] PHP：日期对象
来源：http://dali.jinqigfzy.top/Article/details/gtkkfwchhq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hongshengwenyu.top/Article/details/gtpjevqvdv.html

[U63] PHP：文件读写
来源：http://dali.yonumen.top/Article/details/gtuvrgrnlr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shzxlz.cn/Article/details/gtxsjbyuue.html

[U64] PHP：目录遍历
来源：http://dali.316326.xyz/Article/details/gtazkjrpgt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.0kj1m.cn/Article/details/gtpexteofs.html

[U65] PHP：会话
来源：http://dali.jinqigufen.top/Article/details/gtuwuainuq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zycfv.cn/Article/details/gthgawykma.html

[U66] PHP：设置 Cookie
来源：http://dali.316326.xyz/Article/details/gtfthfenns.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.daxiang520.top/Article/details/gtgefsioxz.html

[U67] PHP：处理文件上传
来源：http://dali.andypj.xyz/Article/details/gtbtzekaou.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.0kj1m.cn/Article/details/gtqwnpjaek.html

[U68] PHP：PDO 连接
来源：http://dali.andypj.xyz/Article/details/gtntilltsp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gtbkaoupkn.html

[U69] PHP：PDO 预处理
来源：http://dali.daria6918.cn/Article/details/gttlkivfoi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jiagoushi.top/Article/details/gtvjbkllog.html

[U70] PHP：PDO 事务
来源：http://dali.guannengcc.top/Article/details/gttrufqfsu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.daxiang520.top/Article/details/gtckcvgqrs.html

[U71] PHP：抛出异常
来源：http://dali.chenlongwang.top/Article/details/gtaedglbzl.html

throw new RuntimeException("失败", 500);
来源：http://dali.hnxiangtu.top/Article/details/gtmpvyszpa.html

[U72] PHP：写错误日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfpnyoel.html

error_log("失败: " . $e->getMessage());
来源：http://dali.nwbrower.top/Article/details/gtugcvvpzb.html

[U73] PHP：读取 ini 配置
来源：http://dali.birdmap.top/Article/details/gtyyyreygx.html

parse_ini_file("config.ini", true)
来源：http://dali.svipenyu.cn/Article/details/gtajovykwo.html

[U74] PHP：读取环境变量
来源：http://dali.havefunace.top/Article/details/gtrnuezvte.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhixingplan.top/Article/details/gtaunxckmq.html

[U75] PHP：依赖注入
来源：http://dali.shangyingyoupin.top/Article/details/gtguozgdex.html

composer require psr/container
来源：http://dali.tanke756.top/Article/details/gtysxrzuju.html

[U76] PHP：简单路由
来源：http://dali.daxiang520.top/Article/details/gtbysfrwbs.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.gogol.net.cn/Article/details/gtxfygkyzz.html

[U77] PHP：模板渲染
来源：http://dali.xinyue.icu/Article/details/gtcwhlmyos.html

composer require twig/twig
来源：http://dali.sufxvd.cn/Article/details/gtvxgsohjw.html

[U78] PHP：单元测试
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyededupw.html

composer require --dev phpunit/phpunit
来源：http://dali.yj202588.top/Article/details/gtnvsxlnql.html

[U79] PHP：静态分析
来源：http://dali.daxiang520.top/Article/details/gtgzmomzjj.html

composer require --dev phpstan/phpstan
来源：http://dali.hfpthk.cn/Article/details/gtvmwqwmyv.html

[U80] PHP：代码规范修复
来源：http://dali.jinghuilouyu.cn/Article/details/gtxormkmqz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yanxiufei.cn/Article/details/gtcafnpulo.html

[U81] JS：初始化项目
来源：http://dali.fzhhl.top/Article/details/gtprjdoktd.html

npm init -y;  npm i express
来源：http://dali.guannengcc.top/Article/details/gtgafqaiui.html

[U82] JS：package.json 脚本
来源：http://dali.hfpthk.cn/Article/details/gtdrjsarud.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.aizwys.cn/Article/details/gtxcpknhqu.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinqigufen.top/Article/details/gtujsshtqq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxpqoljd.html

[U84] JS：CommonJS 写法
来源：http://dali.zhiwuduotai.top/Article/details/gtctwzxrdw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.snrcjt.cn/Article/details/gthrnuftgu.html

[U85] JS：可选链
来源：http://dali.zhiwuduotai.top/Article/details/gtbkqhupsz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gtntdkzuac.html

[U86] JS：空值合并
来源：http://dali.guannengcc.top/Article/details/gtqdcagvai.html

a ?? b
来源：http://dali.zhixingplan.top/Article/details/gtnddzpbln.html

[U87] JS：解构默认值
来源：http://dali.pengpengdd.cyou/Article/details/gtpdbppkgh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.aibaodan.cn/Article/details/gttihurkzp.html

[U88] JS：对象展开合并
来源：http://dali.dashuyun.cn/Article/details/gtlhgjoomr.html

{ ...a, ...b }
来源：http://dali.zhixingplan.top/Article/details/gtcjnbhtme.html

[U89] JS：数组去重
来源：http://dali.yj20258.top/Article/details/gtigjtfytj.html

[...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtniobfanx.html

[U90] JS：数字数组排序
来源：http://dali.svipenyu.cn/Article/details/gtggexadap.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomiyhqai.html

[U91] JS：对象键值遍历
来源：http://dali.shzxlz.cn/Article/details/gtojkdwixz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shanyushiyangtech.top/Article/details/gtygjksvxj.html

[U92] JS：深拷贝
来源：http://dali.zhixingplan.top/Article/details/gtmxleizub.html

structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtntbacurz.html

[U93] JS：模板字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtomdcdqqx.html

`共 ${n} 条`
来源：http://dali.aizwys.cn/Article/details/gtqsjcckzs.html

[U94] JS：箭头函数
来源：http://dali.svipenyu.cn/Article/details/gturdtozsf.html

const double = x => x * 2;
来源：http://dali.havefunace.top/Article/details/gtbbulasmu.html

[U95] JS：Promise 包装
来源：http://dali.hnqzz.top/Article/details/gtlnhqjqix.html

new Promise((resolve, reject) => {})
来源：http://dali.pengpengdd.cyou/Article/details/gtvuzgoidj.html

[U96] JS：async/await 与异常
来源：http://dali.hnxiangtu.top/Article/details/gtbbnyfylx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtlkqqsjyn.html

[U97] JS：并发请求
来源：http://dali.nanxinkj.top/Article/details/gtgmjgirjf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtlmlxruhq.html

[U98] JS：fetch 带 JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtrhsuswlz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.svipenyu.cn/Article/details/gtmebpqhby.html

[U99] JS：事件监听
来源：http://dali.wangdashe.top/Article/details/gtickkxhte.html

el.addEventListener("click", e => {})
来源：http://dali.hnxiangtu.top/Article/details/gtzgqjqlgo.html

[U100] JS：DOM 查询
来源：http://dali.smart0.xyz/Article/details/gthaynbetv.html

document.querySelector(".item")
来源：http://dali.yj202588.top/Article/details/gtaiqqriic.html

[U101] JS：classList 操作
来源：http://dali.zhengqikj.top/Article/details/gtcdlgwexv.html

el.classList.toggle("active")
来源：http://dali.tian-w.cn/Article/details/gtrpxjgklk.html

[U102] JS：本地存储
来源：http://dali.ppjwa.cn/Article/details/gtnyrzgzie.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.pengpengdd.cyou/Article/details/gtejynkgxv.html

[U103] JS：定时器
来源：http://dali.jiagoushi.top/Article/details/gtkkmpryrn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jyoumei.cn/Article/details/gtzejsfbrd.html

[U104] JS：防抖
来源：http://dali.hammf.cn/Article/details/gtgylcxfut.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtgadcdhsc.html

[U105] JS：节流
来源：http://dali.ivvv.top/Article/details/gtztuigshz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhoulong.xyz/Article/details/gtrthnedtt.html

[U106] JS：日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtaobhivwh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinqigufen.top/Article/details/gtjrxtjqtc.html

[U107] JS：数字千分位
来源：http://dali.iojbl.cn/Article/details/gthxcpggwq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gogol.net.cn/Article/details/gtqmmuacpi.html

[U108] JS：随机整数
来源：http://dali.ybcxt.top/Article/details/gtzvtqbbfb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yuanzhike.top/Article/details/gthexmsudc.html

[U109] JS：数组分组
来源：http://dali.aibaodan.cn/Article/details/gtmavkfqjn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.c1oappe.top/Article/details/gtcqkizwqm.html

[U110] JS：数组分块
来源：http://dali.zhiwuduotai.top/Article/details/gtsvmtaqry.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cucudq.cn/Article/details/gtkcmnyfwj.html

[U111] JS：对象转 Map
来源：http://dali.chenlongwang.top/Article/details/gtwyddabqv.html

new Map(Object.entries(obj))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxejngfsw.html

[U112] JS：字符串补位
来源：http://dali.birdmap.top/Article/details/gtwbqjfvlf.html

"7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtzxpyqekz.html

[U113] JS：正则替换全部
来源：http://dali.sufxvd.cn/Article/details/gtmnwtnxrk.html

s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtzbgyjzct.html

[U114] JS：JSON 深比较
来源：http://dali.tanke756.top/Article/details/gtrxhgciff.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtstevfdrr.html

[U115] JS：生成 UUID
来源：http://dali.sysykeji.top/Article/details/gtmjfpecbu.html

crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtlautvedc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zycfv.cn/Article/details/gtsufgvowl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ydzc1.top/Article/details/gtvngtguua.html

[U117] JS：单元测试
来源：http://dali.sxryk.cn/Article/details/gtiyfznhyi.html

npm i -D vitest;  npx vitest
来源：http://dali.fzhhl.top/Article/details/gttgbfnkjc.html

[U118] JS：开发服务器
来源：http://dali.yueranfly.top/Article/details/gttmrsrzhh.html

npm i -D vite;  npx vite
来源：http://dali.316326.xyz/Article/details/gtlbcllafc.html

[U119] JS：生产构建
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbclrzvqs.html

npx vite build
来源：http://dali.bjfxy.top/Article/details/gtxncksrsq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yvedp.cn/Article/details/gtzfhqrndf.html

import.meta.env.VITE_API_URL
来源：http://dali.haohaochexian.top/Article/details/gtcuqbhitc.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtymuwcnvm.html

统计汇总
来源：http://dali.shuidangran.top/Article/details/gtpyqjziab.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtskwskwex.html

按语言统计（条）：
来源：http://dali.cheryme.top/Article/details/gtqvdxvklo.html

Python ......... 252
来源：http://dali.guannengcc.top/Article/details/gtjdmmvntq.html

PHP ............ 252
来源：http://dali.hnqzz.top/Article/details/gtnyzrdeat.html

JavaScript ..... 252
来源：http://dali.yvedp.cn/Article/details/gtkpwrmqdb.html

TypeScript ..... 212
来源：http://dali.hywenlv.cn/Article/details/gtibnwtymi.html

Java ........... 212
来源：http://dali.svipenyu.cn/Article/details/gtvloktxik.html

Go ............. 212
来源：http://dali.birdmap.top/Article/details/gtavgbevlm.html

Ruby ........... 212
来源：http://dali.316326.xyz/Article/details/gtimnchuto.html

C# ............. 212
来源：http://dali.jinqigfzy.top/Article/details/gtwzymvngf.html

C .............. 30
来源：http://dali.jiagoushi.top/Article/details/gtgdlaxevk.html

C++ ............ 30
来源：http://dali.ybcxt.top/Article/details/gtroiisvcc.html

SQL ............ 90
来源：http://dali.hnqzz.top/Article/details/gtmubokaeb.html

Bash ........... 80
来源：http://dali.aibaodan.cn/Article/details/gttcjhgewq.html

Kotlin ......... 15
来源：http://dali.vqdsnc.cn/Article/details/gtoutzywgm.html

Swift .......... 15
来源：http://dali.redwolf501.top/Article/details/gtrvlfxifg.html

Lua ............ 10
来源：http://dali.pengpengdd.cyou/Article/details/gttbgaihgj.html

Perl ........... 10
来源：http://dali.zhengqikj.top/Article/details/gtvlkeoowx.html

Scala .......... 10
来源：http://dali.dashuyun.cn/Article/details/gtjuolbplr.html

------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gtkfgzpcgc.html

合计 ........... 2106 条
来源：http://dali.yueranfly.top/Article/details/gtesgqicvp.html

按章节统计：
来源：http://dali.xinyue.icu/Article/details/gtsmovdltd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.redwolf501.top/Article/details/gtoxheczid.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sysykeji.top/Article/details/gtblsslqmp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenlongwang.top/Article/details/gtkbrwujeo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jiagoushi.top/Article/details/gtxtsurulk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hnxiangtu.top/Article/details/gtvgvofvlo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.chenzaomai.com/Article/details/gtafocfdqt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.redwolf501.top/Article/details/gtswnlsvpk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gtfwmmlaqu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gtlilqhdyg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sweek.top/Article/details/gtaftgmzdl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gtjixtdtza.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvsampho.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtpubbqxng.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.fengsongda.top/Article/details/gtsjddywzk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jlsjyb.cn/Article/details/gtenmesswy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtilurbipo.html

Q SQL 专题                              90
来源：http://dali.hfpthk.cn/Article/details/gtpzurvxkd.html

R Bash 专题                             80
来源：http://dali.jqgfzy.top/Article/details/gtypnioerq.html

S C / C++ 专题                          60
来源：http://dali.yangfankeji.com/Article/details/gtbowavyxa.html

T 其他语言补充                          60
来源：http://dali.yvedp.cn/Article/details/gtrvnwpzjb.html

U 高频实用片段                         120
来源：http://dali.ivvv.top/Article/details/gtnhsspdol.html

------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtmgrqgema.html

合计                                  2106 条
来源：http://dali.ybcxt.top/Article/details/gtwxvbegxe.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtpcoowkhf.html

使用提醒
来源：http://dali.xuanzx.com/Article/details/gtubcbejfx.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtfctvrhfc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.wangdashe.top/Article/details/gtsyfcuzbe.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sysykeji.top/Article/details/gtqdrxbhbf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlovokwbg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.svipenyu.cn/Article/details/gtkkzszaak.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.guowangkeji.top/Article/details/gtpexutnjy.html

—— 文件结束 ——
来源：http://dali.9152youxi.cn/Article/details/gtqgnmveqz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejlxycio.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.birdmap.top/Article/details/gtwurqcunv.html

Common Programming Examples Cheat Book
来源：http://dali.yongpay.top/Article/details/gtmrnpaqtj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtepgctqtq.html


<!-- 参考信息 -->