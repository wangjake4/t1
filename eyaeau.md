代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cdnleiting.top/Article/details/gtzisltnqh.html

[T59] Scala：循环
来源：http://dali.iojbl.cn/Article/details/gtppkmifhe.html

for (i <- 1 to 10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gtuthznxyt.html

[T60] Scala：折叠
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkowlzjb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.haohaochexian.top/Article/details/gtojellzwl.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtanjhiwjp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.bjfxy.top/Article/details/gtbxgqytwc.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtpeqqzoaw.html

[U01] Py：创建虚拟环境
来源：http://dali.bjfxy.top/Article/details/gtuyvaksxy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tanke756.top/Article/details/gtbyqcfvgb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jqgufenzy.top/Article/details/gtolluytmh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guannengcc.top/Article/details/gtvtxcamfa.html

[U03] Py：加载 .env 配置
来源：http://dali.ybcxt.top/Article/details/gtqyswqpza.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xylfe.cn/Article/details/gtwnqehtxu.html

[U04] Py：变量调试打印
来源：http://dali.ehwqpu.com/Article/details/gtxdpvyqgs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xylfe.cn/Article/details/gtbimzonnh.html

[U05] Py：列表去重且保序
来源：http://dali.zhixingplan.top/Article/details/gtudmmluac.html

list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gtdynfqanu.html

[U06] Py：合并两个字典
来源：http://dali.yvedp.cn/Article/details/gttpdtqydc.html

{**a, **b}
来源：http://dali.jianghu66.top/Article/details/gtierrbgef.html

[U07] Py：反转字典键值
来源：http://dali.cdnleiting.top/Article/details/gtcfawbown.html

{v: k for k, v in d.items()}
来源：http://dali.gogol.net.cn/Article/details/gtfczwfmrd.html

[U08] Py：展平二维列表
来源：http://dali.zycfv.cn/Article/details/gtmiobvgje.html

[y for x in nested for y in x]
来源：http://dali.gogol.net.cn/Article/details/gtmlubfdpw.html

[U09] Py：字典取最大值的键
来源：http://dali.chenlongwang.top/Article/details/gtfadjezaq.html

max(d, key=d.get)
来源：http://dali.ivvv.top/Article/details/gtdgwigbxn.html

[U10] Py：按值排序字典
来源：http://dali.cqqwz.cn/Article/details/gtstynvmaj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgaugrcg.html

[U11] Py：生成器表达式
来源：http://dali.chenlongwang.top/Article/details/gtyiuvaqlp.html

(x * 2 for x in arr)
来源：http://dali.wangdashe.top/Article/details/gttkvcwfwm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.daria6918.cn/Article/details/gtsxlrjolf.html

Counter(arr).most_common(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmaazugzy.html

[U13] Py：固定长度队列
来源：http://dali.fzhhl.top/Article/details/gtswupdbdm.html

deque(maxlen=10)
来源：http://dali.ppjwa.cn/Article/details/gtjfeezavk.html

[U14] Py：分组收集到列表
来源：http://dali.quarkkingdee.top/Article/details/gtxsoditob.html

defaultdict(list)
来源：http://dali.xylfe.cn/Article/details/gtjgrhonwz.html

[U15] Py：高精度计时
来源：http://dali.andypj.xyz/Article/details/gtkypdzcvx.html

t = time.perf_counter()
来源：http://dali.jyoumei.cn/Article/details/gtvggeswnm.html

[U16] Py：命令行参数解析
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtruwkbzfp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.chenjidiqi.icu/Article/details/gtxtdqrwcz.html

[U17] Py：初始化日志
来源：http://dali.quarkkingdee.top/Article/details/gtbphgsdpy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.chenjidiqi.icu/Article/details/gtquqaacbw.html

[U18] Py：预编译正则
来源：http://dali.wangdashe.top/Article/details/gtiwilrrpa.html

pat = re.compile(r"\d+")
来源：http://dali.cqqwz.cn/Article/details/gtsolqjcyj.html

[U19] Py：正则替换带回调
来源：http://dali.sufxvd.cn/Article/details/gttrhnnlmf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtalbvljmn.html

[U20] Py：缓存函数结果
来源：http://dali.xylfe.cn/Article/details/gtrcnhspef.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xylfe.cn/Article/details/gtcujallyw.html

[U21] Py：自定义上下文管理器
来源：http://dali.gotoacloud.top/Article/details/gtwijembzo.html

@contextlib.contextmanager
来源：http://dali.wangshuangyany.cn/Article/details/gtaafxmgbd.html

[U22] Py：矩阵转置
来源：http://dali.hywenlv.cn/Article/details/gttwqbbrlw.html

list(zip(*m))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwqikyie.html

[U23] Py：分块读取大文件
来源：http://dali.zhiwuduotai.top/Article/details/gtxvwkxjno.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hammf.cn/Article/details/gtoukywuza.html

[U24] Py：路径操作
来源：http://dali.redwolf501.top/Article/details/gtruijrsnd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gtzzqfnodx.html

[U25] Py：CSV 按字典读
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdpgkrnx.html

csv.DictReader(f)
来源：http://dali.andypj.xyz/Article/details/gtbisadlma.html

[U26] Py：并发下载
来源：http://dali.birdmap.top/Article/details/gtaiwiqdpt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jqgufenzy.top/Article/details/gtesahcrke.html

[U27] Py：异步 HTTP
来源：http://dali.bjfxy.top/Article/details/gtnbucqeux.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hfpthk.cn/Article/details/gtjrtoisrn.html

[U28] Py：类型别名
来源：http://dali.dashuyun.cn/Article/details/gtvnrjayiv.html

UserId = int
来源：http://dali.sxryk.cn/Article/details/gtywyzxjwq.html

[U29] Py：属性校验
来源：http://dali.smart0.xyz/Article/details/gtlgxojbva.html

@property 与 @x.setter 配合
来源：http://dali.xylfe.cn/Article/details/gteppcislk.html

[U30] Py：数据类
来源：http://dali.yongpay.top/Article/details/gthxrlwahp.html

@dataclass(slots=True)
来源：http://dali.yangfankeji.com/Article/details/gtnrlqpkym.html

[U31] Py：单测
来源：http://dali.hongshengwenyu.top/Article/details/gtwjjbinvn.html

python -m pytest -q
来源：http://dali.aizwys.cn/Article/details/gtmiiiqzpt.html

[U32] Py：代码格式化
来源：http://dali.jqgufenzy.top/Article/details/gtbalxncfl.html

ruff format . && ruff check --fix .
来源：http://dali.zhoulong.xyz/Article/details/gtvsufwvhk.html

[U33] Py：打包发布
来源：http://dali.ybcxt.top/Article/details/gtvydmpjeg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gaohongyu789.top/Article/details/gtvwkpjphp.html

[U34] Py：判断编码
来源：http://dali.shzxlz.cn/Article/details/gtndprfvjn.html

chardet.detect(raw)
来源：http://dali.shzxlz.cn/Article/details/gtilglwvev.html

[U35] Py：发送邮件
来源：http://dali.0kj1m.cn/Article/details/gtzdkzomdy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jlsjyb.cn/Article/details/gtiamnqegl.html

[U36] Py：定时任务
来源：http://dali.yueranfly.top/Article/details/gtiwlkartt.html

schedule.every(10).minutes.do(job)
来源：http://dali.smart0.xyz/Article/details/gtpnupnvsn.html

[U37] Py：读写 Excel
来源：http://dali.ivvv.top/Article/details/gtcspkdomb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hysaishi.cn/Article/details/gtdgtypkhn.html

[U38] Py：获取脚本所在目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkbooimm.html

Path(__file__).resolve().parent
来源：http://dali.zhoulong.xyz/Article/details/gtvttcjopq.html

[U39] Py：判断是否在交互环境
来源：http://dali.yuanzhike.top/Article/details/gtaiubtupr.html

sys.stdout.isatty()
来源：http://dali.xziqi.cn/Article/details/gtqjlnvggk.html

[U40] Py：打印到标准错误
来源：http://dali.9152youxi.cn/Article/details/gtiwqrwggo.html

print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gtkinznzww.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cucudq.cn/Article/details/gtllbynwze.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.quarkkingdee.top/Article/details/gtgjpeahwu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ybcxt.top/Article/details/gtppdrvita.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.c1oappe.top/Article/details/gtvurybita.html

[U43] PHP：声明命名空间
来源：http://dali.jinqigfzy.top/Article/details/gtlrqgnppz.html

namespace App\Http;
来源：http://dali.c1oappe.top/Article/details/gtbxzymxrd.html

[U44] PHP：开启严格类型
来源：http://dali.pengpengdd.cyou/Article/details/gtfnooesnh.html

declare(strict_types=1);
来源：http://dali.xziqi.cn/Article/details/gtfzneclxz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jqgfzy.top/Article/details/gtwwsemhte.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gtksdkufqk.html

[U46] PHP：可空类型
来源：http://dali.gaohongyu789.top/Article/details/gthyevxgcw.html

?string $name = null
来源：http://dali.hysaishi.cn/Article/details/gtjddzgeod.html

[U47] PHP：联合类型
来源：http://dali.jyoumei.cn/Article/details/gtvnznyvqb.html

int|string $id
来源：http://dali.dianchejie.cn/Article/details/gtbmcfeusw.html

[U48] PHP：纯枚举
来源：http://dali.meibo888.top/Article/details/gtltfbmomj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.316326.xyz/Article/details/gtycljnvex.html

[U49] PHP：只读属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyzgbslo.html

public readonly string $name
来源：http://dali.cashguo.top/Article/details/gtljceclra.html

[U50] PHP：构造器属性提升
来源：http://dali.zhengqikj.top/Article/details/gtaleqtofh.html

public function __construct(private int $id) {}
来源：http://dali.quarkkingdee.top/Article/details/gttlqgxudq.html

[U51] PHP：数组解构
来源：http://dali.hnqzz.top/Article/details/gtemiibeyv.html

[$a, $b] = $arr;
来源：http://dali.jinqigfzy.top/Article/details/gtjsmshngl.html

[U52] PHP：箭头函数
来源：http://dali.pycfn.com/Article/details/gtpixljjwi.html

$double = fn($x) => $x * 2;
来源：http://dali.hammf.cn/Article/details/gtwzunyjjh.html

[U53] PHP：空合并运算符
来源：http://dali.yvedp.cn/Article/details/gtemivpflt.html

$v = $a ?? $b ?? "default";
来源：http://dali.shzxlz.cn/Article/details/gthdrwedbl.html

[U54] PHP：空安全调用
来源：http://dali.zycfv.cn/Article/details/gtglegfjui.html

$obj?->method()
来源：http://dali.mhx1999.top/Article/details/gthszdiltb.html

[U55] PHP：match 表达式
来源：http://dali.yj20258888.top/Article/details/gtnodbrmhk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yonumen.top/Article/details/gtqrsxtrqe.html

[U56] PHP：命名参数
来源：http://dali.wangdashe.top/Article/details/gtqulzulqz.html

f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtxfetidyl.html

[U57] PHP：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtktucxkex.html

"值: {$a}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotrhpmqs.html

[U58] PHP：数组三件套
来源：http://dali.yuanzhike.top/Article/details/gtfkqckxxl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinqigufen.top/Article/details/gtmefapjmj.html

[U59] PHP：自定义排序
来源：http://dali.dianchejie.cn/Article/details/gtmyovotky.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gtlzodzjgt.html

[U60] PHP：JSON 编解码
来源：http://dali.zhengqikj.top/Article/details/gtkfwgdwao.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.guannengcc.top/Article/details/gtadymdnlo.html

[U61] PHP：正则
来源：http://dali.mhx1999.top/Article/details/gttgldpfvb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqvowkcb.html

[U62] PHP：日期对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbyprbdsb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.fengsongda.top/Article/details/gtowunuykm.html

[U63] PHP：文件读写
来源：http://dali.dianchejie.cn/Article/details/gtholhbrau.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yj20258.top/Article/details/gtykospqda.html

[U64] PHP：目录遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gthdgpbaya.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yongpay.top/Article/details/gtgqtkqhja.html

[U65] PHP：会话
来源：http://dali.dashuyun.cn/Article/details/gtlnpzpgui.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtcrvzuqke.html

[U66] PHP：设置 Cookie
来源：http://dali.zdqjudy.top/Article/details/gtfsvshfrp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.chenlongwang.top/Article/details/gtpnfvjuog.html

[U67] PHP：处理文件上传
来源：http://dali.yanxiufei.cn/Article/details/gthzvheznx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.svipenyu.cn/Article/details/gtjxzogrck.html

[U68] PHP：PDO 连接
来源：http://dali.zycfv.cn/Article/details/gtekzdgrmo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tian-w.cn/Article/details/gtnynjjupm.html

[U69] PHP：PDO 预处理
来源：http://dali.zhixingplan.top/Article/details/gtdrrtyumt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yanxiufei.cn/Article/details/gtplqyvetj.html

[U70] PHP：PDO 事务
来源：http://dali.xuetiantiany.cn/Article/details/gtxxlyhxap.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hammf.cn/Article/details/gtztlrqlyy.html

[U71] PHP：抛出异常
来源：http://dali.tian-w.cn/Article/details/gteamhcjam.html

throw new RuntimeException("失败", 500);
来源：http://dali.quarkkingdee.top/Article/details/gtushdanmt.html

[U72] PHP：写错误日志
来源：http://dali.yanxiufei.cn/Article/details/gtdepcwmjl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.meibo888.top/Article/details/gtbaqkdacp.html

[U73] PHP：读取 ini 配置
来源：http://dali.9152youxi.cn/Article/details/gtmjphhwzf.html

parse_ini_file("config.ini", true)
来源：http://dali.cqqwz.cn/Article/details/gteiwmambd.html

[U74] PHP：读取环境变量
来源：http://dali.hammf.cn/Article/details/gtjyvxwird.html

getenv("APP_ENV") ?: "production"
来源：http://dali.meibo888.top/Article/details/gttjulrwpt.html

[U75] PHP：依赖注入
来源：http://dali.zhiwuduotai.top/Article/details/gtspzfxecd.html

composer require psr/container
来源：http://dali.zhixingplan.top/Article/details/gtecxlqixj.html

[U76] PHP：简单路由
来源：http://dali.kuanghao11.cn/Article/details/gtzogqxibj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.vqdsnc.cn/Article/details/gtaakcmntg.html

[U77] PHP：模板渲染
来源：http://dali.birdmap.top/Article/details/gtuzfgvhef.html

composer require twig/twig
来源：http://dali.cucudq.cn/Article/details/gthxedcfvl.html

[U78] PHP：单元测试
来源：http://dali.meibo888.top/Article/details/gtgsezspew.html

composer require --dev phpunit/phpunit
来源：http://dali.iojbl.cn/Article/details/gtmxccebpg.html

[U79] PHP：静态分析
来源：http://dali.jqgfzy.top/Article/details/gtquavmzne.html

composer require --dev phpstan/phpstan
来源：http://dali.jiagoushi.top/Article/details/gtpjzlquhe.html

[U80] PHP：代码规范修复
来源：http://dali.mhx1999.top/Article/details/gtiacxfpdt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nanxuanxn.top/Article/details/gtbkskogan.html

[U81] JS：初始化项目
来源：http://dali.tianlin.xyz/Article/details/gtttwdpgkt.html

npm init -y;  npm i express
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitszcotj.html

[U82] JS：package.json 脚本
来源：http://dali.hysaishi.cn/Article/details/gteljuoenl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xuetiantiany.cn/Article/details/gtalmnuzbr.html

[U83] JS：ES Module 导入导出
来源：http://dali.yangfankeji.com/Article/details/gtyosmggix.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gogol.net.cn/Article/details/gtvzokkmoh.html

[U84] JS：CommonJS 写法
来源：http://dali.316326.xyz/Article/details/gtkzrtwlcl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.pengpengdd.cyou/Article/details/gtrdryprsc.html

[U85] JS：可选链
来源：http://dali.hnxiangtu.top/Article/details/gtzzmcotxz.html

a?.b?.c
来源：http://dali.tianlin.xyz/Article/details/gtfwroqvmh.html

[U86] JS：空值合并
来源：http://dali.hnqzz.top/Article/details/gtqpbwhrlh.html

a ?? b
来源：http://dali.yuxming.cn/Article/details/gtcmpvuwuw.html

[U87] JS：解构默认值
来源：http://dali.hongshengwenyu.top/Article/details/gtainwscrn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ybcxt.top/Article/details/gtkumibofx.html

[U88] JS：对象展开合并
来源：http://dali.hfpthk.cn/Article/details/gtdlzjnoii.html

{ ...a, ...b }
来源：http://dali.nanxuanxn.top/Article/details/gtvnqqvoiu.html

[U89] JS：数组去重
来源：http://dali.xylfe.cn/Article/details/gttklhxges.html

[...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtxykwwtdh.html

[U90] JS：数字数组排序
来源：http://dali.birdmap.top/Article/details/gtcdxhyviq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gtbracqrdb.html

[U91] JS：对象键值遍历
来源：http://dali.cqqwz.cn/Article/details/gttsdffbcg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jianghu66.top/Article/details/gtakzmlgfz.html

[U92] JS：深拷贝
来源：http://dali.snrcjt.cn/Article/details/gtldkpvpim.html

structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gtuoakkuky.html

[U93] JS：模板字符串
来源：http://dali.hnqzz.top/Article/details/gtxtyqllbp.html

`共 ${n} 条`
来源：http://dali.snrcjt.cn/Article/details/gtxatunmut.html

[U94] JS：箭头函数
来源：http://dali.gogol.net.cn/Article/details/gtcibmrspo.html

const double = x => x * 2;
来源：http://dali.hnqzz.top/Article/details/gtnkegizmm.html

[U95] JS：Promise 包装
来源：http://dali.havefunace.top/Article/details/gtcwwsszke.html

new Promise((resolve, reject) => {})
来源：http://dali.xylfe.cn/Article/details/gtboflzwom.html

[U96] JS：async/await 与异常
来源：http://dali.birdmap.top/Article/details/gtuyvhjxst.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtrcxuqozg.html

[U97] JS：并发请求
来源：http://dali.andypj.xyz/Article/details/gtcztbpyfb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtjjfvfbom.html

[U98] JS：fetch 带 JSON
来源：http://dali.iojbl.cn/Article/details/gtgfxpoqta.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.fengsongda.top/Article/details/gtgjaxumjj.html

[U99] JS：事件监听
来源：http://dali.ivvv.top/Article/details/gtwoafhpvl.html

el.addEventListener("click", e => {})
来源：http://dali.chenlongwang.top/Article/details/gtgzzktxqu.html

[U100] JS：DOM 查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbsaosiu.html

document.querySelector(".item")
来源：http://dali.shangyingyoupin.top/Article/details/gtgwtmjziz.html

[U101] JS：classList 操作
来源：http://dali.mhx1999.top/Article/details/gtisphpemd.html

el.classList.toggle("active")
来源：http://dali.jianghu66.top/Article/details/gtfnvhhbrn.html

[U102] JS：本地存储
来源：http://dali.yuanzhike.top/Article/details/gtnifmotbm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.wangdashe.top/Article/details/gtypyczufx.html

[U103] JS：定时器
来源：http://dali.sufxvd.cn/Article/details/gtxxjhtawy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sxryk.cn/Article/details/gtuqgqwhlg.html

[U104] JS：防抖
来源：http://dali.guannengcc.top/Article/details/gtmnagvhes.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gtvbmrcvjt.html

[U105] JS：节流
来源：http://dali.nwbrower.top/Article/details/gtnsdqyrqp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.meibo888.top/Article/details/gtamtsgphs.html

[U106] JS：日期格式化
来源：http://dali.cdnleiting.top/Article/details/gtxyrioyfy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.fzhhl.top/Article/details/gtlxemefzk.html

[U107] JS：数字千分位
来源：http://dali.yonumen.top/Article/details/gtkftncpwc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gtpzglcidt.html

[U108] JS：随机整数
来源：http://dali.yueranfly.top/Article/details/gtoptzlmcs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ydzc1.top/Article/details/gtkwjnggxr.html

[U109] JS：数组分组
来源：http://dali.hnxiangtu.top/Article/details/gttizdyizg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gtukxmmtqb.html

[U110] JS：数组分块
来源：http://dali.hongshengwenyu.top/Article/details/gtsydkhwne.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuxming.cn/Article/details/gtvxbyhufs.html

[U111] JS：对象转 Map
来源：http://dali.sufxvd.cn/Article/details/gtcuqgtlpi.html

new Map(Object.entries(obj))
来源：http://dali.nanxuanxn.top/Article/details/gtoyairjnj.html

[U112] JS：字符串补位
来源：http://dali.cqqwz.cn/Article/details/gtwboaffpk.html

"7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtkksdykes.html

[U113] JS：正则替换全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcklxqclk.html

s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtnlasjdvc.html

[U114] JS：JSON 深比较
来源：http://dali.chenjidiqi.icu/Article/details/gtxhjejrel.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yangfankeji.com/Article/details/gtpulbarxk.html

[U115] JS：生成 UUID
来源：http://dali.shuidangran.top/Article/details/gtngppqwnn.html

crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gtsklkntms.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cucudq.cn/Article/details/gtrbotwfcu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhengqikj.top/Article/details/gtjccagwok.html

[U117] JS：单元测试
来源：http://dali.nanxinkj.top/Article/details/gtkbptepnp.html

npm i -D vitest;  npx vitest
来源：http://dali.cqqwz.cn/Article/details/gtqxxrmksq.html

[U118] JS：开发服务器
来源：http://dali.aibaodan.cn/Article/details/gtwkqglzpv.html

npm i -D vite;  npx vite
来源：http://dali.ppjwa.cn/Article/details/gtyngrvbqm.html

[U119] JS：生产构建
来源：http://dali.guowangkeji.top/Article/details/gtwkvwwksf.html

npx vite build
来源：http://dali.zhongyouzk.top/Article/details/gtfwyoksmx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jiagoushi.top/Article/details/gtjhmbhpvj.html

import.meta.env.VITE_API_URL
来源：http://dali.sxryk.cn/Article/details/gtmlrofvht.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtzhkezsdx.html

统计汇总
来源：http://dali.yvedp.cn/Article/details/gteoxshsaz.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtpxlywohg.html

按语言统计（条）：
来源：http://dali.tianlin.xyz/Article/details/gtwtrmjwoc.html

Python ......... 252
来源：http://dali.hongshengwenyu.top/Article/details/gtgkfmbazo.html

PHP ............ 252
来源：http://dali.zhengqikj.top/Article/details/gtywelzogm.html

JavaScript ..... 252
来源：http://dali.iojbl.cn/Article/details/gtciudswep.html

TypeScript ..... 212
来源：http://dali.hnqzz.top/Article/details/gtwdqupkfc.html

Java ........... 212
来源：http://dali.hfpthk.cn/Article/details/gtevqfuuwa.html

Go ............. 212
来源：http://dali.andypj.xyz/Article/details/gtlkwbnwur.html

Ruby ........... 212
来源：http://dali.hnqzz.top/Article/details/gtsbjzhecn.html

C# ............. 212
来源：http://dali.dashuyun.cn/Article/details/gtuhntbivi.html

C .............. 30
来源：http://dali.c1oappe.top/Article/details/gtrofmziuu.html

C++ ............ 30
来源：http://dali.redwolf501.top/Article/details/gtbtexgviw.html

SQL ............ 90
来源：http://dali.yueranfly.top/Article/details/gtzjslcvmy.html

Bash ........... 80
来源：http://dali.wangshuangyany.cn/Article/details/gtvnorvryv.html

Kotlin ......... 15
来源：http://dali.cdnleiting.top/Article/details/gtfkfzxfpg.html

Swift .......... 15
来源：http://dali.pengpengdd.cyou/Article/details/gtqggevgrz.html

Lua ............ 10
来源：http://dali.birdmap.top/Article/details/gtqnjghjvu.html

Perl ........... 10
来源：http://dali.yonumen.top/Article/details/gtcftinrjw.html

Scala .......... 10
来源：http://dali.vqdsnc.cn/Article/details/gtxekwimvy.html

------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtfehhahlv.html

合计 ........... 2106 条
来源：http://dali.aizwys.cn/Article/details/gtkahjzqox.html

按章节统计：
来源：http://dali.jinqigufen.top/Article/details/gtgkufbjvk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nanxinkj.top/Article/details/gtpcfrlncy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cucudq.cn/Article/details/gtfavedqyc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hnxiangtu.top/Article/details/gtvvwdrisr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgoxyfqpi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfertuosl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yonumen.top/Article/details/gthihzuart.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gtjmgqvjaq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xuetiantiany.cn/Article/details/gtcgeeaazq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gttdrjvrlg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hnqzz.top/Article/details/gtkatlnthj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gtanaireoo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gtvhdwcucp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtrmadfqdv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.meibo888.top/Article/details/gternytddb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhiwuduotai.top/Article/details/gttdtpojiy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gtydytreeu.html

Q SQL 专题                              90
来源：http://dali.sxryk.cn/Article/details/gtmfvinxxh.html

R Bash 专题                             80
来源：http://dali.fzhhl.top/Article/details/gtygvthcyv.html

S C / C++ 专题                          60
来源：http://dali.ybcxt.top/Article/details/gtzfdlothm.html

T 其他语言补充                          60
来源：http://dali.jianghu66.top/Article/details/gtbjhfcqsq.html

U 高频实用片段                         120
来源：http://dali.sysykeji.top/Article/details/gtrmdmlvup.html

------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtpclivqbj.html

合计                                  2106 条
来源：http://dali.jlsjyb.cn/Article/details/gtoqjiakga.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gtckugjwpx.html

使用提醒
来源：http://dali.xuetiantiany.cn/Article/details/gtsancdcyv.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtkmmredzx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.pengpengdd.cyou/Article/details/gtaiqpncgy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhiwuduotai.top/Article/details/gtavlhrdkw.html


<!-- 参考信息 -->