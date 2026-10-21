代发 wailian999

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.mhx1999.top/Article/details/gtmpsvunpq.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtijmhqrba.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxinkj.top/Article/details/gtsdoepwdm.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtdhfbikpt.html

[U01] Py：创建虚拟环境
来源：http://dali.316326.xyz/Article/details/gtppuatlng.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aibaodan.cn/Article/details/gtuqoxbeng.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jiagoushi.top/Article/details/gtetyiikrm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.fzhhl.top/Article/details/gtlbuvpdks.html

[U03] Py：加载 .env 配置
来源：http://dali.birdmap.top/Article/details/gtpsrkyvxk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenjidiqi.icu/Article/details/gtmkfvrqeb.html

[U04] Py：变量调试打印
来源：http://dali.guannengcc.top/Article/details/gttlwdzuib.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pycfn.com/Article/details/gtowgejvzl.html

[U05] Py：列表去重且保序
来源：http://dali.jinghuilouyu.cn/Article/details/gtwyxfmahz.html

list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxkjsxpb.html

[U06] Py：合并两个字典
来源：http://dali.jianghu66.top/Article/details/gtjjufbxhw.html

{**a, **b}
来源：http://dali.sufxvd.cn/Article/details/gtztxbdgdu.html

[U07] Py：反转字典键值
来源：http://dali.shuidangran.top/Article/details/gtvdakuedk.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangtech.top/Article/details/gteblxgxoj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gturjqgnop.html

[y for x in nested for y in x]
来源：http://dali.chenjidiqi.icu/Article/details/gtvmsjqqtc.html

[U09] Py：字典取最大值的键
来源：http://dali.jlsjyb.cn/Article/details/gtkrvesbbw.html

max(d, key=d.get)
来源：http://dali.yonumen.top/Article/details/gtfuitsjsy.html

[U10] Py：按值排序字典
来源：http://dali.gzhubu.top/Article/details/gtyiyqqwaw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sysykeji.top/Article/details/gtrqttfjoh.html

[U11] Py：生成器表达式
来源：http://dali.hysaishi.cn/Article/details/gtkivnpfdy.html

(x * 2 for x in arr)
来源：http://dali.xylfe.cn/Article/details/gtqtqkpcfl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pycfn.com/Article/details/gtgdimimib.html

Counter(arr).most_common(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjfuzxja.html

[U13] Py：固定长度队列
来源：http://dali.hammf.cn/Article/details/gtafgnehhd.html

deque(maxlen=10)
来源：http://dali.gotoacloud.top/Article/details/gtvrccsmdv.html

[U14] Py：分组收集到列表
来源：http://dali.dianchejie.cn/Article/details/gtsgswibou.html

defaultdict(list)
来源：http://dali.gogol.net.cn/Article/details/gtgyubyewe.html

[U15] Py：高精度计时
来源：http://dali.sufxvd.cn/Article/details/gtdoajtmtf.html

t = time.perf_counter()
来源：http://dali.chenjidiqi.icu/Article/details/gtcnpcluav.html

[U16] Py：命令行参数解析
来源：http://dali.zhongyouzk.top/Article/details/gtjyrznlvg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yangfankeji.com/Article/details/gtdnsvdylz.html

[U17] Py：初始化日志
来源：http://dali.guowangkeji.top/Article/details/gtvxnfehmg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.feifeiyinyue.top/Article/details/gtnokwwoxk.html

[U18] Py：预编译正则
来源：http://dali.daxiang520.top/Article/details/gtpruclqvl.html

pat = re.compile(r"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwcvjjxo.html

[U19] Py：正则替换带回调
来源：http://dali.jinqigufen.top/Article/details/gtiwgtshvv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigfzy.top/Article/details/gtkctdjgwv.html

[U20] Py：缓存函数结果
来源：http://dali.ppjwa.cn/Article/details/gtwanfxkqp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxuanxn.top/Article/details/gtdauihpxz.html

[U21] Py：自定义上下文管理器
来源：http://dali.ppjwa.cn/Article/details/gttydonsoa.html

@contextlib.contextmanager
来源：http://dali.kuanghao11.cn/Article/details/gtxyxtzkwm.html

[U22] Py：矩阵转置
来源：http://dali.vqdsnc.cn/Article/details/gttujujvlh.html

list(zip(*m))
来源：http://dali.shangyingyoupin.top/Article/details/gtzykaaxsg.html

[U23] Py：分块读取大文件
来源：http://dali.pengpengdd.cyou/Article/details/gtbadvqjmj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hongshengwenyu.top/Article/details/gtuobtgtbc.html

[U24] Py：路径操作
来源：http://dali.yj202588.top/Article/details/gtjtpraupl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gtgzfzgwei.html

[U25] Py：CSV 按字典读
来源：http://dali.gzhubu.top/Article/details/gttyyxitjn.html

csv.DictReader(f)
来源：http://dali.0kj1m.cn/Article/details/gtygbjjmar.html

[U26] Py：并发下载
来源：http://dali.yongpay.top/Article/details/gtptlwjxpb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ydzc1.top/Article/details/gtekmwqtwn.html

[U27] Py：异步 HTTP
来源：http://dali.zhiwuduotai.top/Article/details/gtsxluogor.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cqqwz.cn/Article/details/gthxxsfokr.html

[U28] Py：类型别名
来源：http://dali.shuidangran.top/Article/details/gtzocexkvj.html

UserId = int
来源：http://dali.xuanzx.com/Article/details/gtlxfrwskh.html

[U29] Py：属性校验
来源：http://dali.hfpthk.cn/Article/details/gtvduorlyd.html

@property 与 @x.setter 配合
来源：http://dali.kuanghao11.cn/Article/details/gtkvbzxrdi.html

[U30] Py：数据类
来源：http://dali.gaohongyu789.top/Article/details/gtechmrkum.html

@dataclass(slots=True)
来源：http://dali.hnxiangtu.top/Article/details/gtckhswmvi.html

[U31] Py：单测
来源：http://dali.yvedp.cn/Article/details/gtkzuncfbx.html

python -m pytest -q
来源：http://dali.zhixingplan.top/Article/details/gtaddcbncu.html

[U32] Py：代码格式化
来源：http://dali.birdmap.top/Article/details/gtwlxcxmgt.html

ruff format . && ruff check --fix .
来源：http://dali.sxryk.cn/Article/details/gthqspvrvp.html

[U33] Py：打包发布
来源：http://dali.hongshengwenyu.top/Article/details/gteeqwqcwe.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hammf.cn/Article/details/gtmahqpzwm.html

[U34] Py：判断编码
来源：http://dali.gotoacloud.top/Article/details/gtigqzfedv.html

chardet.detect(raw)
来源：http://dali.redwolf501.top/Article/details/gtdynbpsxh.html

[U35] Py：发送邮件
来源：http://dali.hnqzz.top/Article/details/gtadhawskx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xuanzx.com/Article/details/gtfcknzkac.html

[U36] Py：定时任务
来源：http://dali.hammf.cn/Article/details/gthiszwrxe.html

schedule.every(10).minutes.do(job)
来源：http://dali.chenjidiqi.icu/Article/details/gtfzidayhj.html

[U37] Py：读写 Excel
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqfbilup.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jqgfzy.top/Article/details/gtmnehtkci.html

[U38] Py：获取脚本所在目录
来源：http://dali.aibaodan.cn/Article/details/gtzehmeibg.html

Path(__file__).resolve().parent
来源：http://dali.yj20258.top/Article/details/gtddvewhwt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhiwuduotai.top/Article/details/gtojftpwuu.html

sys.stdout.isatty()
来源：http://dali.zhoulong.xyz/Article/details/gtotwgrsmk.html

[U40] Py：打印到标准错误
来源：http://dali.zhixingplan.top/Article/details/gtvnprzgcn.html

print("err", file=sys.stderr)
来源：http://dali.hammf.cn/Article/details/gtsbomxdny.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gzhubu.top/Article/details/gterhhrsvd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jianghu66.top/Article/details/gtbzvbquor.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yongpay.top/Article/details/gttkamabkw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xuetiantiany.cn/Article/details/gtcyimfqvd.html

[U43] PHP：声明命名空间
来源：http://dali.gogol.net.cn/Article/details/gtdlscvnpl.html

namespace App\Http;
来源：http://dali.9152youxi.cn/Article/details/gtwvsppnfa.html

[U44] PHP：开启严格类型
来源：http://dali.yvedp.cn/Article/details/gtespjipxb.html

declare(strict_types=1);
来源：http://dali.zhiwuduotai.top/Article/details/gtramhrkey.html

[U45] PHP：类型声明与返回类型
来源：http://dali.fengsongda.top/Article/details/gtkjftlees.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtdfmtxdny.html

[U46] PHP：可空类型
来源：http://dali.pycfn.com/Article/details/gtzxugiqgr.html

?string $name = null
来源：http://dali.yj202588.top/Article/details/gtgkrtwidb.html

[U47] PHP：联合类型
来源：http://dali.hfpthk.cn/Article/details/gtdhwzurrn.html

int|string $id
来源：http://dali.iojbl.cn/Article/details/gticftxudg.html

[U48] PHP：纯枚举
来源：http://dali.bjfxy.top/Article/details/gtrvvsmvno.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hywenlv.cn/Article/details/gtwisvgrjt.html

[U49] PHP：只读属性
来源：http://dali.cdnleiting.top/Article/details/gtaellafts.html

public readonly string $name
来源：http://dali.cqqwz.cn/Article/details/gtfguzqnub.html

[U50] PHP：构造器属性提升
来源：http://dali.yonumen.top/Article/details/gtfnzvksxu.html

public function __construct(private int $id) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtdswmjogp.html

[U51] PHP：数组解构
来源：http://dali.daxiang520.top/Article/details/gtglwrqwrs.html

[$a, $b] = $arr;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgwfltef.html

[U52] PHP：箭头函数
来源：http://dali.zhiwuduotai.top/Article/details/gtzawmkjbc.html

$double = fn($x) => $x * 2;
来源：http://dali.zhoulong.xyz/Article/details/gtrcsondmy.html

[U53] PHP：空合并运算符
来源：http://dali.nwbrower.top/Article/details/gtlsorvklw.html

$v = $a ?? $b ?? "default";
来源：http://dali.nanxinkj.top/Article/details/gtbbldplyb.html

[U54] PHP：空安全调用
来源：http://dali.yonumen.top/Article/details/gtnumidbfr.html

$obj?->method()
来源：http://dali.zhoulong.xyz/Article/details/gtjypsqvcd.html

[U55] PHP：match 表达式
来源：http://dali.hywenlv.cn/Article/details/gtbotofpqs.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ehwqpu.com/Article/details/gtiewsrjkm.html

[U56] PHP：命名参数
来源：http://dali.zhengqikj.top/Article/details/gtqwzdamyt.html

f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtxfzioskj.html

[U57] PHP：字符串插值
来源：http://dali.shuidangran.top/Article/details/gtxjsfltvr.html

"值: {$a}"
来源：http://dali.hfpthk.cn/Article/details/gtcutoqlzq.html

[U58] PHP：数组三件套
来源：http://dali.c1oappe.top/Article/details/gtshixpgcl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtvvsqkqsd.html

[U59] PHP：自定义排序
来源：http://dali.316326.xyz/Article/details/gtewgcohzc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqerbmxc.html

[U60] PHP：JSON 编解码
来源：http://dali.yongpay.top/Article/details/gtedbqyvdm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtgbzsawts.html

[U61] PHP：正则
来源：http://dali.shuidangran.top/Article/details/gtygvcpedd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.dashuyun.cn/Article/details/gtxxbcxums.html

[U62] PHP：日期对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkuvjehyf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.mhx1999.top/Article/details/gtrplrhkmr.html

[U63] PHP：文件读写
来源：http://dali.ydzc1.top/Article/details/gtinggbnyg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xinyue.icu/Article/details/gtvvnwbsph.html

[U64] PHP：目录遍历
来源：http://dali.fzhhl.top/Article/details/gtazgbrdex.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.feifeiyinyue.top/Article/details/gtgrzdrtwo.html

[U65] PHP：会话
来源：http://dali.feifeiyinyue.top/Article/details/gtpiaassdh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtsxgwyokz.html

[U66] PHP：设置 Cookie
来源：http://dali.quarkkingdee.top/Article/details/gthmnefvoy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.wangdashe.top/Article/details/gtcirqveyl.html

[U67] PHP：处理文件上传
来源：http://dali.jyoumei.cn/Article/details/gtnobbwspc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hnxiangtu.top/Article/details/gtcwshwnbn.html

[U68] PHP：PDO 连接
来源：http://dali.pengpengdd.cyou/Article/details/gtjyzcgnay.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhongyouzk.top/Article/details/gtwvwccvgy.html

[U69] PHP：PDO 预处理
来源：http://dali.svipenyu.cn/Article/details/gtovtkuinw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.316326.xyz/Article/details/gtmaigmlbd.html

[U70] PHP：PDO 事务
来源：http://dali.hfpthk.cn/Article/details/gtfgertifu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ybcxt.top/Article/details/gtndouckor.html

[U71] PHP：抛出异常
来源：http://dali.hywenlv.cn/Article/details/gteovnjggm.html

throw new RuntimeException("失败", 500);
来源：http://dali.guannengcc.top/Article/details/gtcyrfedht.html

[U72] PHP：写错误日志
来源：http://dali.jqgufenzy.top/Article/details/gtvpfnyjnv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.meibo888.top/Article/details/gttevkdrds.html

[U73] PHP：读取 ini 配置
来源：http://dali.xinyue.icu/Article/details/gtpcfqqqbi.html

parse_ini_file("config.ini", true)
来源：http://dali.guannengcc.top/Article/details/gtrvfhmqby.html

[U74] PHP：读取环境变量
来源：http://dali.yj202588.top/Article/details/gtpfsuchvs.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xziqi.cn/Article/details/gtafmitbpd.html

[U75] PHP：依赖注入
来源：http://dali.nwbrower.top/Article/details/gtybuhwwqm.html

composer require psr/container
来源：http://dali.hammf.cn/Article/details/gtjfularmc.html

[U76] PHP：简单路由
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblsdeqpe.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jianghu66.top/Article/details/gtigqxhhpi.html

[U77] PHP：模板渲染
来源：http://dali.zhengqikj.top/Article/details/gtecdngjzm.html

composer require twig/twig
来源：http://dali.pengpengdd.cyou/Article/details/gtovmspsot.html

[U78] PHP：单元测试
来源：http://dali.jinqigufen.top/Article/details/gtlcakyuql.html

composer require --dev phpunit/phpunit
来源：http://dali.daxiang520.top/Article/details/gtkpprlmdk.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gtnzqwgrdw.html

composer require --dev phpstan/phpstan
来源：http://dali.shangyingyoupin.top/Article/details/gtozqnljgw.html

[U80] PHP：代码规范修复
来源：http://dali.meibo888.top/Article/details/gtkritcwqm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.gaohongyu789.top/Article/details/gtycsjmfub.html

[U81] JS：初始化项目
来源：http://dali.shanyushiyangtech.top/Article/details/gtfohqlsza.html

npm init -y;  npm i express
来源：http://dali.hnqzz.top/Article/details/gthkfdfsqf.html

[U82] JS：package.json 脚本
来源：http://dali.dashuyun.cn/Article/details/gtyggdshlb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.c1oappe.top/Article/details/gtsvbfvswx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zycfv.cn/Article/details/gtrzdgpbfk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yj20258888.top/Article/details/gtaypriajq.html

[U84] JS：CommonJS 写法
来源：http://dali.fengsongda.top/Article/details/gtyaekrvof.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yangfankeji.com/Article/details/gtucsmegku.html

[U85] JS：可选链
来源：http://dali.jlsjyb.cn/Article/details/gtokovzwhy.html

a?.b?.c
来源：http://dali.gaohongyu789.top/Article/details/gticybfkhz.html

[U86] JS：空值合并
来源：http://dali.yangfankeji.com/Article/details/gtyjfvssus.html

a ?? b
来源：http://dali.hongshengwenyu.top/Article/details/gtujibqgui.html

[U87] JS：解构默认值
来源：http://dali.zhengqikj.top/Article/details/gtntxktmrh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.kuanghao11.cn/Article/details/gtwvsputey.html

[U88] JS：对象展开合并
来源：http://dali.sufxvd.cn/Article/details/gthhwirlgb.html

{ ...a, ...b }
来源：http://dali.yvedp.cn/Article/details/gtgctjlvvk.html

[U89] JS：数组去重
来源：http://dali.bjfxy.top/Article/details/gtywjayugt.html

[...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gtrdegnquc.html

[U90] JS：数字数组排序
来源：http://dali.c1oappe.top/Article/details/gtpwurzppo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtolbrwbrh.html

[U91] JS：对象键值遍历
来源：http://dali.zycfv.cn/Article/details/gtfzgjojfw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yangfankeji.com/Article/details/gtaojqwvwn.html

[U92] JS：深拷贝
来源：http://dali.jinqigufen.top/Article/details/gtsrxaqgcg.html

structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtxjpznlyw.html

[U93] JS：模板字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwalbijw.html

`共 ${n} 条`
来源：http://dali.gotoacloud.top/Article/details/gtyrwzkeua.html

[U94] JS：箭头函数
来源：http://dali.xuanzx.com/Article/details/gtbrtfjcqx.html

const double = x => x * 2;
来源：http://dali.yj20258888.top/Article/details/gtamwocifz.html

[U95] JS：Promise 包装
来源：http://dali.cucudq.cn/Article/details/gtriczsgrz.html

new Promise((resolve, reject) => {})
来源：http://dali.yj20258888.top/Article/details/gtcsmffzkm.html

[U96] JS：async/await 与异常
来源：http://dali.jinqigfzy.top/Article/details/gtsjbfwebn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtrctnotxy.html

[U97] JS：并发请求
来源：http://dali.kuanghao11.cn/Article/details/gtivklqcot.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtnmvuaxbu.html

[U98] JS：fetch 带 JSON
来源：http://dali.svipenyu.cn/Article/details/gtcipbgmxz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.tanke756.top/Article/details/gtimwulysh.html

[U99] JS：事件监听
来源：http://dali.yj20258.top/Article/details/gtauucawju.html

el.addEventListener("click", e => {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmsncizo.html

[U100] JS：DOM 查询
来源：http://dali.zdqjudy.top/Article/details/gtsniafjug.html

document.querySelector(".item")
来源：http://dali.shuidangran.top/Article/details/gtdxelznyx.html

[U101] JS：classList 操作
来源：http://dali.jyoumei.cn/Article/details/gtcbovlepc.html

el.classList.toggle("active")
来源：http://dali.bjfxy.top/Article/details/gtnkgqzjhb.html

[U102] JS：本地存储
来源：http://dali.c1oappe.top/Article/details/gtjpeacbea.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinqigfzy.top/Article/details/gtbfxbwllg.html

[U103] JS：定时器
来源：http://dali.cdnleiting.top/Article/details/gthbmvwfhl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.wangshuangyany.cn/Article/details/gtgblhtwjf.html

[U104] JS：防抖
来源：http://dali.xuanzx.com/Article/details/gtzpxcxgma.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gtoxbaetlg.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gtcmgihaws.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.fzhhl.top/Article/details/gtutztxkdw.html

[U106] JS：日期格式化
来源：http://dali.tanke756.top/Article/details/gtflsxtley.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jyoumei.cn/Article/details/gtefrfiugh.html

[U107] JS：数字千分位
来源：http://dali.ydzc1.top/Article/details/gtyrebjxnb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nanxuanxn.top/Article/details/gtsqialuqt.html

[U108] JS：随机整数
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzcpvdzh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.svipenyu.cn/Article/details/gtfbbitwpu.html

[U109] JS：数组分组
来源：http://dali.mhx1999.top/Article/details/gtmpljnsqo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gtnpdvpajg.html

[U110] JS：数组分块
来源：http://dali.yueranfly.top/Article/details/gtfvggvvzj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuxming.cn/Article/details/gtxtuymtey.html

[U111] JS：对象转 Map
来源：http://dali.cdnleiting.top/Article/details/gtgxaymzga.html

new Map(Object.entries(obj))
来源：http://dali.zhixingplan.top/Article/details/gtmwghjube.html

[U112] JS：字符串补位
来源：http://dali.zhongyouzk.top/Article/details/gtttjurmyu.html

"7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtyhpvbasr.html

[U113] JS：正则替换全部
来源：http://dali.dianchejie.cn/Article/details/gtgocqvptv.html

s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtdcrwrqrj.html

[U114] JS：JSON 深比较
来源：http://dali.kuanghao11.cn/Article/details/gtpgwqbvdd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtpgltdcsk.html

[U115] JS：生成 UUID
来源：http://dali.bjfxy.top/Article/details/gtrcqcvwuj.html

crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gtsvlrveli.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cheryme.top/Article/details/gtesreriit.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tanke756.top/Article/details/gtrebjtzbs.html

[U117] JS：单元测试
来源：http://dali.snrcjt.cn/Article/details/gtkzgwcido.html

npm i -D vitest;  npx vitest
来源：http://dali.nanxinkj.top/Article/details/gtnfowqlpz.html

[U118] JS：开发服务器
来源：http://dali.aizwys.cn/Article/details/gtaulhswhq.html

npm i -D vite;  npx vite
来源：http://dali.smart0.xyz/Article/details/gtshrwtuvh.html

[U119] JS：生产构建
来源：http://dali.tian-w.cn/Article/details/gtgqkxqyij.html

npx vite build
来源：http://dali.sysykeji.top/Article/details/gtaguvmdbo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sysykeji.top/Article/details/gtqxaifndz.html

import.meta.env.VITE_API_URL
来源：http://dali.yanxiufei.cn/Article/details/gtzxwbnvvn.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtacnlkqrh.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gteouimlhn.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtpzrriuio.html

按语言统计（条）：
来源：http://dali.shzxlz.cn/Article/details/gtycicmakc.html

Python ......... 252
来源：http://dali.nwbrower.top/Article/details/gtvxkfzdkn.html

PHP ............ 252
来源：http://dali.havefunace.top/Article/details/gtmhaeohju.html

JavaScript ..... 252
来源：http://dali.yuanzhike.top/Article/details/gtkfoseiqp.html

TypeScript ..... 212
来源：http://dali.hnxiangtu.top/Article/details/gtiklhvncx.html

Java ........... 212
来源：http://dali.yanxiufei.cn/Article/details/gtcdtgdveq.html

Go ............. 212
来源：http://dali.tian-w.cn/Article/details/gtefqyjccb.html

Ruby ........... 212
来源：http://dali.tanke756.top/Article/details/gtvyebpnca.html

C# ............. 212
来源：http://dali.yuanzhike.top/Article/details/gtthkayzjl.html

C .............. 30
来源：http://dali.daxiang520.top/Article/details/gtdrcasyar.html

C++ ............ 30
来源：http://dali.ppjwa.cn/Article/details/gtknbmjgvs.html

SQL ............ 90
来源：http://dali.andypj.xyz/Article/details/gtqsazczwf.html

Bash ........... 80
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlylxhhkt.html

Kotlin ......... 15
来源：http://dali.daxiang520.top/Article/details/gtgerofjei.html

Swift .......... 15
来源：http://dali.ybcxt.top/Article/details/gtmrseqczk.html

Lua ............ 10
来源：http://dali.yvedp.cn/Article/details/gtxuddinjw.html

Perl ........... 10
来源：http://dali.yueranfly.top/Article/details/gtbmeizrwl.html

Scala .......... 10
来源：http://dali.smart0.xyz/Article/details/gtdgurkint.html

------------------------------------
来源：http://dali.yj20258.top/Article/details/gtrttvljbi.html

合计 ........... 2106 条
来源：http://dali.yj20258888.top/Article/details/gtdnciykzo.html

按章节统计：
来源：http://dali.smart0.xyz/Article/details/gtjfsopbop.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.guowangkeji.top/Article/details/gtttcklbix.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.aibaodan.cn/Article/details/gtyslzuyvi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hysaishi.cn/Article/details/gttqnsiqxj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gtcqhiizzp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhsizjjq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xuanzx.com/Article/details/gtdrcqzvjb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gzhubu.top/Article/details/gthujwguds.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cheryme.top/Article/details/gtsalzlnxl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gtwionfckp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jqgfzy.top/Article/details/gtfedperen.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtbfamyenn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gtnbhvxgos.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gtygjkxksj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cheryme.top/Article/details/gtkioejmro.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.quarkkingdee.top/Article/details/gtfublvybw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gtqmsbfnjz.html

Q SQL 专题                              90
来源：http://dali.sufxvd.cn/Article/details/gtzguagzzm.html

R Bash 专题                             80
来源：http://dali.jinqigufen.top/Article/details/gtqucpykyk.html

S C / C++ 专题                          60
来源：http://dali.jinqigufen.top/Article/details/gtcgywgypv.html

T 其他语言补充                          60
来源：http://dali.zycfv.cn/Article/details/gtvpzlevwf.html

U 高频实用片段                         120
来源：http://dali.jqgfzy.top/Article/details/gthjcwqwhm.html

------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtpfhfwzhu.html

合计                                  2106 条
来源：http://dali.xinyue.icu/Article/details/gtqjivbmnm.html

--------------------------------------------------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gtbvnjtbfu.html

使用提醒
来源：http://dali.daxiang520.top/Article/details/gtuvyfyhin.html

--------------------------------------------------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtfiauxick.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yanxiufei.cn/Article/details/gtjhrldybj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ydzc1.top/Article/details/gtxqdakiuu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yangfankeji.com/Article/details/gtklaoubws.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.c1oappe.top/Article/details/gtiskhozcd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yonumen.top/Article/details/gthkggyfkn.html

—— 文件结束 ——
来源：http://dali.gogol.net.cn/Article/details/gtrumtdyxt.html


<!-- 参考信息 -->