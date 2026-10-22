代发 wailian999

[U01] Py：创建虚拟环境
来源：http://dali.yvedp.cn/Article/details/gthupphydf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmeshyoyi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ppjwa.cn/Article/details/gtafznmdpw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhixingplan.top/Article/details/gtktnxmppf.html

[U03] Py：加载 .env 配置
来源：http://dali.zhengqikj.top/Article/details/gtwgszhhoy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcsueufs.html

[U04] Py：变量调试打印
来源：http://dali.yonumen.top/Article/details/gtcplsztsu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ydzc1.top/Article/details/gtdplkqhko.html

[U05] Py：列表去重且保序
来源：http://dali.aibaodan.cn/Article/details/gtmgahjxpa.html

list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gtvcobrqdm.html

[U06] Py：合并两个字典
来源：http://dali.hfpthk.cn/Article/details/gtcxyydfmt.html

{**a, **b}
来源：http://dali.vqdsnc.cn/Article/details/gtbuplicpb.html

[U07] Py：反转字典键值
来源：http://dali.yj20258888.top/Article/details/gtmmlpfkks.html

{v: k for k, v in d.items()}
来源：http://dali.zhiwuduotai.top/Article/details/gtgfpyycfe.html

[U08] Py：展平二维列表
来源：http://dali.shangyingyoupin.top/Article/details/gtmlipivbv.html

[y for x in nested for y in x]
来源：http://dali.gogol.net.cn/Article/details/gtqfjzbhsw.html

[U09] Py：字典取最大值的键
来源：http://dali.gotoacloud.top/Article/details/gteilbohss.html

max(d, key=d.get)
来源：http://dali.yueranfly.top/Article/details/gtzknmhsov.html

[U10] Py：按值排序字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzexetpj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.vqdsnc.cn/Article/details/gtfcmyvqij.html

[U11] Py：生成器表达式
来源：http://dali.jlsjyb.cn/Article/details/gtdueubcth.html

(x * 2 for x in arr)
来源：http://dali.guannengcc.top/Article/details/gtfuvgymok.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.aibaodan.cn/Article/details/gtcbzmvvxv.html

Counter(arr).most_common(3)
来源：http://dali.hnxiangtu.top/Article/details/gtrtmjspsv.html

[U13] Py：固定长度队列
来源：http://dali.aizwys.cn/Article/details/gtrnfsrhpu.html

deque(maxlen=10)
来源：http://dali.shzxlz.cn/Article/details/gtiaabaxux.html

[U14] Py：分组收集到列表
来源：http://dali.cucudq.cn/Article/details/gtqbopwdny.html

defaultdict(list)
来源：http://dali.zdqjudy.top/Article/details/gtixsgvwze.html

[U15] Py：高精度计时
来源：http://dali.vqdsnc.cn/Article/details/gthtktcnni.html

t = time.perf_counter()
来源：http://dali.jianghu66.top/Article/details/gtmrykaatd.html

[U16] Py：命令行参数解析
来源：http://dali.tianlin.xyz/Article/details/gttcohslny.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.wangdashe.top/Article/details/gtotrpfozb.html

[U17] Py：初始化日志
来源：http://dali.pengpengdd.cyou/Article/details/gtlsjvevzz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hysaishi.cn/Article/details/gtcnerkuda.html

[U18] Py：预编译正则
来源：http://dali.sweek.top/Article/details/gtxodztdzr.html

pat = re.compile(r"\d+")
来源：http://dali.xinyue.icu/Article/details/gtsuiwniuk.html

[U19] Py：正则替换带回调
来源：http://dali.havefunace.top/Article/details/gtlyeyrbhp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xinyue.icu/Article/details/gtyjfctprz.html

[U20] Py：缓存函数结果
来源：http://dali.fengsongda.top/Article/details/gtcsgmjuyg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.andypj.xyz/Article/details/gtqtmtbqxu.html

[U21] Py：自定义上下文管理器
来源：http://dali.sxryk.cn/Article/details/gtbpzzjetz.html

@contextlib.contextmanager
来源：http://dali.xuanzx.com/Article/details/gtqrabhwiq.html

[U22] Py：矩阵转置
来源：http://dali.redwolf501.top/Article/details/gtrdowhljg.html

list(zip(*m))
来源：http://dali.nanxinkj.top/Article/details/gttkzzudya.html

[U23] Py：分块读取大文件
来源：http://dali.zycfv.cn/Article/details/gtcquffvhl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucxvukcj.html

[U24] Py：路径操作
来源：http://dali.yongpay.top/Article/details/gtmbilfdbf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gttklsrvtj.html

[U25] Py：CSV 按字典读
来源：http://dali.chenzaomai.com/Article/details/gtjazoedzk.html

csv.DictReader(f)
来源：http://dali.dianchejie.cn/Article/details/gthryurvtb.html

[U26] Py：并发下载
来源：http://dali.daria6918.cn/Article/details/gtgxefemts.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sysykeji.top/Article/details/gtzebiaden.html

[U27] Py：异步 HTTP
来源：http://dali.mhx1999.top/Article/details/gtursorpnr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yongpay.top/Article/details/gtjleyjnsn.html

[U28] Py：类型别名
来源：http://dali.gotoacloud.top/Article/details/gtucuqoyhn.html

UserId = int
来源：http://dali.feifeiyinyue.top/Article/details/gtxacwgcgr.html

[U29] Py：属性校验
来源：http://dali.smart0.xyz/Article/details/gtmoybhvpe.html

@property 与 @x.setter 配合
来源：http://dali.kuanghao11.cn/Article/details/gtgjejeotv.html

[U30] Py：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gtnijyaywn.html

@dataclass(slots=True)
来源：http://dali.ehwqpu.com/Article/details/gtptqcznzf.html

[U31] Py：单测
来源：http://dali.ehwqpu.com/Article/details/gtysygsipc.html

python -m pytest -q
来源：http://dali.jiagoushi.top/Article/details/gtnxfbjmst.html

[U32] Py：代码格式化
来源：http://dali.zhixingplan.top/Article/details/gtkytyxbam.html

ruff format . && ruff check --fix .
来源：http://dali.feifeiyinyue.top/Article/details/gtlykkkaom.html

[U33] Py：打包发布
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkblwhpt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gotoacloud.top/Article/details/gtgmqfront.html

[U34] Py：判断编码
来源：http://dali.yanxiufei.cn/Article/details/gtylzchivh.html

chardet.detect(raw)
来源：http://dali.nwbrower.top/Article/details/gtgasnrosv.html

[U35] Py：发送邮件
来源：http://dali.tianlin.xyz/Article/details/gtobbimxhe.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.guowangkeji.top/Article/details/gtxywryqoo.html

[U36] Py：定时任务
来源：http://dali.xuanzx.com/Article/details/gtmyhqwnxf.html

schedule.every(10).minutes.do(job)
来源：http://dali.0kj1m.cn/Article/details/gtnupshrjd.html

[U37] Py：读写 Excel
来源：http://dali.feifeiyinyue.top/Article/details/gtwsngxyng.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.aibaodan.cn/Article/details/gtbuvkezpp.html

[U38] Py：获取脚本所在目录
来源：http://dali.nwbrower.top/Article/details/gtnnpuwrhd.html

Path(__file__).resolve().parent
来源：http://dali.jyoumei.cn/Article/details/gtbymiaoxr.html

[U39] Py：判断是否在交互环境
来源：http://dali.svipenyu.cn/Article/details/gtdcvfqmua.html

sys.stdout.isatty()
来源：http://dali.0kj1m.cn/Article/details/gtxhdoitoe.html

[U40] Py：打印到标准错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqvmkltz.html

print("err", file=sys.stderr)
来源：http://dali.jianghu66.top/Article/details/gtuezlmgoc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.pengpengdd.cyou/Article/details/gtatikcpqb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tian-w.cn/Article/details/gtoxffuusq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gtdnibkpno.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdnaayxa.html

[U43] PHP：声明命名空间
来源：http://dali.birdmap.top/Article/details/gtutxjzcmj.html

namespace App\Http;
来源：http://dali.yuanzhike.top/Article/details/gtzxcbgwmj.html

[U44] PHP：开启严格类型
来源：http://dali.jyoumei.cn/Article/details/gtcizqqwlu.html

declare(strict_types=1);
来源：http://dali.yonumen.top/Article/details/gtnvetpvnw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.andypj.xyz/Article/details/gtzlzwposp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gtmzslrpat.html

[U46] PHP：可空类型
来源：http://dali.zycfv.cn/Article/details/gtyhuxntll.html

?string $name = null
来源：http://dali.ehwqpu.com/Article/details/gthhwgbtgm.html

[U47] PHP：联合类型
来源：http://dali.nanxinkj.top/Article/details/gtfgosebsr.html

int|string $id
来源：http://dali.quarkkingdee.top/Article/details/gtufanfvwk.html

[U48] PHP：纯枚举
来源：http://dali.yonumen.top/Article/details/gtiizcszvj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sufxvd.cn/Article/details/gtrczfsxwj.html

[U49] PHP：只读属性
来源：http://dali.ivvv.top/Article/details/gtqtsahkdm.html

public readonly string $name
来源：http://dali.xinyue.icu/Article/details/gtftwiubly.html

[U50] PHP：构造器属性提升
来源：http://dali.gzhubu.top/Article/details/gtdohvdiqz.html

public function __construct(private int $id) {}
来源：http://dali.vqdsnc.cn/Article/details/gttyilhvrr.html

[U51] PHP：数组解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttfripmb.html

[$a, $b] = $arr;
来源：http://dali.jinqigfzy.top/Article/details/gthbilktqz.html

[U52] PHP：箭头函数
来源：http://dali.yanxiufei.cn/Article/details/gtxclgqrdg.html

$double = fn($x) => $x * 2;
来源：http://dali.sufxvd.cn/Article/details/gtpmxkfaoz.html

[U53] PHP：空合并运算符
来源：http://dali.fengsongda.top/Article/details/gtsrdrrncn.html

$v = $a ?? $b ?? "default";
来源：http://dali.yuanzhike.top/Article/details/gtrovahiqc.html

[U54] PHP：空安全调用
来源：http://dali.zhixingplan.top/Article/details/gtipkerexv.html

$obj?->method()
来源：http://dali.xziqi.cn/Article/details/gtjujyxhfi.html

[U55] PHP：match 表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnidvdhhs.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shuidangran.top/Article/details/gtnqyxbnnb.html

[U56] PHP：命名参数
来源：http://dali.meibo888.top/Article/details/gtenwewwmq.html

f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gtkzapcyok.html

[U57] PHP：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtxcedhdnt.html

"值: {$a}"
来源：http://dali.sweek.top/Article/details/gtbekytcpv.html

[U58] PHP：数组三件套
来源：http://dali.pengpengdd.cyou/Article/details/gtpgtoisrg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ivvv.top/Article/details/gtgpdxpqmp.html

[U59] PHP：自定义排序
来源：http://dali.zdqjudy.top/Article/details/gtudakwguz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gtlwfxfkpz.html

[U60] PHP：JSON 编解码
来源：http://dali.jianghu66.top/Article/details/gtxgmzvfwg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yuanzhike.top/Article/details/gtytovzpbs.html

[U61] PHP：正则
来源：http://dali.chenzaomai.com/Article/details/gtfapfoiwm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gtypkdyrjj.html

[U62] PHP：日期对象
来源：http://dali.xinyue.icu/Article/details/gthsohjbhy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.9152youxi.cn/Article/details/gtfelrodyh.html

[U63] PHP：文件读写
来源：http://dali.yanxiufei.cn/Article/details/gtoobyzgkg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.nanxuanxn.top/Article/details/gtmiaymqsz.html

[U64] PHP：目录遍历
来源：http://dali.yj20258.top/Article/details/gtjuszybty.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.meibo888.top/Article/details/gtjmxbncqe.html

[U65] PHP：会话
来源：http://dali.zhongyouzk.top/Article/details/gtitdffuyt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtmvjijlqr.html

[U66] PHP：设置 Cookie
来源：http://dali.bjfxy.top/Article/details/gtmupdsrkq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ppjwa.cn/Article/details/gttlezpdjk.html

[U67] PHP：处理文件上传
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogdstksn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yvedp.cn/Article/details/gtuzdsexze.html

[U68] PHP：PDO 连接
来源：http://dali.aizwys.cn/Article/details/gtlrgdebbp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjfvmogb.html

[U69] PHP：PDO 预处理
来源：http://dali.jinqigufen.top/Article/details/gtfhhgrshu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yuxming.cn/Article/details/gtbzsmtqzz.html

[U70] PHP：PDO 事务
来源：http://dali.jinqigufen.top/Article/details/gtuuxthmyr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ybcxt.top/Article/details/gtfjankobx.html

[U71] PHP：抛出异常
来源：http://dali.dianchejie.cn/Article/details/gtcoxqbrli.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhongyouzk.top/Article/details/gthqroopve.html

[U72] PHP：写错误日志
来源：http://dali.ehwqpu.com/Article/details/gtawkjwygg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shuidangran.top/Article/details/gtxffkqunt.html

[U73] PHP：读取 ini 配置
来源：http://dali.shuidangran.top/Article/details/gtyajviuib.html

parse_ini_file("config.ini", true)
来源：http://dali.gotoacloud.top/Article/details/gtdwyltdio.html

[U74] PHP：读取环境变量
来源：http://dali.smart0.xyz/Article/details/gtvmmnnazd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.quarkkingdee.top/Article/details/gtgxbwvamg.html

[U75] PHP：依赖注入
来源：http://dali.yongpay.top/Article/details/gtqusukkxc.html

composer require psr/container
来源：http://dali.fzhhl.top/Article/details/gtxycuifkw.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gtrzeticxr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ybcxt.top/Article/details/gtkeyjdwql.html

[U77] PHP：模板渲染
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsorejlp.html

composer require twig/twig
来源：http://dali.cdnleiting.top/Article/details/gteofjfdps.html

[U78] PHP：单元测试
来源：http://dali.hnqzz.top/Article/details/gtfhhoprxg.html

composer require --dev phpunit/phpunit
来源：http://dali.xuanzx.com/Article/details/gtyswiuzix.html

[U79] PHP：静态分析
来源：http://dali.kuanghao11.cn/Article/details/gtnitfkdpu.html

composer require --dev phpstan/phpstan
来源：http://dali.smart0.xyz/Article/details/gtzrwvzylp.html

[U80] PHP：代码规范修复
来源：http://dali.cucudq.cn/Article/details/gtjscwbkbp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jianghu66.top/Article/details/gtinuwiasy.html

[U81] JS：初始化项目
来源：http://dali.fengsongda.top/Article/details/gtbrlokhjp.html

npm init -y;  npm i express
来源：http://dali.gotoacloud.top/Article/details/gthjurfuit.html

[U82] JS：package.json 脚本
来源：http://dali.wangshuangyany.cn/Article/details/gtmyuilnql.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.wangdashe.top/Article/details/gteadrahvu.html

[U83] JS：ES Module 导入导出
来源：http://dali.cqqwz.cn/Article/details/gtljbjpmcy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gtcgzdwjfc.html

[U84] JS：CommonJS 写法
来源：http://dali.cdnleiting.top/Article/details/gtrxxzfnck.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.birdmap.top/Article/details/gtmqiyeqwi.html

[U85] JS：可选链
来源：http://dali.xuetiantiany.cn/Article/details/gttdntqzaq.html

a?.b?.c
来源：http://dali.xinyue.icu/Article/details/gtgowgdgrb.html

[U86] JS：空值合并
来源：http://dali.yj20258888.top/Article/details/gtghkehzln.html

a ?? b
来源：http://dali.cheryme.top/Article/details/gtphhmrchm.html

[U87] JS：解构默认值
来源：http://dali.xylfe.cn/Article/details/gtopkrfifx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cucudq.cn/Article/details/gtwtwvzpcd.html

[U88] JS：对象展开合并
来源：http://dali.smart0.xyz/Article/details/gtqxdwexoi.html

{ ...a, ...b }
来源：http://dali.nwbrower.top/Article/details/gthswxtakz.html

[U89] JS：数组去重
来源：http://dali.smart0.xyz/Article/details/gtmgewhwlh.html

[...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtwqfcdbtz.html

[U90] JS：数字数组排序
来源：http://dali.quarkkingdee.top/Article/details/gtdrqpxyfz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gtbpwwokny.html

[U91] JS：对象键值遍历
来源：http://dali.gogol.net.cn/Article/details/gtwwgbpiqe.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cdnleiting.top/Article/details/gtqmqkrpog.html

[U92] JS：深拷贝
来源：http://dali.hywenlv.cn/Article/details/gtwoyhlgwz.html

structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtwbhvutnm.html

[U93] JS：模板字符串
来源：http://dali.yj202588.top/Article/details/gtzeifvxzv.html

`共 ${n} 条`
来源：http://dali.yanxiufei.cn/Article/details/gtqbibcile.html

[U94] JS：箭头函数
来源：http://dali.jianghu66.top/Article/details/gtnzfosbgh.html

const double = x => x * 2;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukzwdmzz.html

[U95] JS：Promise 包装
来源：http://dali.nanxinkj.top/Article/details/gtltcvdcoi.html

new Promise((resolve, reject) => {})
来源：http://dali.yj202588.top/Article/details/gtcrrouuom.html

[U96] JS：async/await 与异常
来源：http://dali.birdmap.top/Article/details/gtmrjdrkof.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtfwpjdwbo.html

[U97] JS：并发请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfuztyra.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gtzoewmvgq.html

[U98] JS：fetch 带 JSON
来源：http://dali.cqqwz.cn/Article/details/gtmcdzgxch.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.pengpengdd.cyou/Article/details/gtlniolyvu.html

[U99] JS：事件监听
来源：http://dali.jqgufenzy.top/Article/details/gttoiildzc.html

el.addEventListener("click", e => {})
来源：http://dali.yangfankeji.com/Article/details/gtrbochwuk.html

[U100] JS：DOM 查询
来源：http://dali.jqgfzy.top/Article/details/gtqmdhlezh.html

document.querySelector(".item")
来源：http://dali.xuetiantiany.cn/Article/details/gteaqurblh.html

[U101] JS：classList 操作
来源：http://dali.yuanzhike.top/Article/details/gtaejvushm.html

el.classList.toggle("active")
来源：http://dali.zhengqikj.top/Article/details/gtoykvaphs.html

[U102] JS：本地存储
来源：http://dali.nanxinkj.top/Article/details/gtztxopoxs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xuanzx.com/Article/details/gthcyzrfqq.html

[U103] JS：定时器
来源：http://dali.tianlin.xyz/Article/details/gtznjoybop.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.feifeiyinyue.top/Article/details/gtntnboqaq.html

[U104] JS：防抖
来源：http://dali.zdqjudy.top/Article/details/gtvylueogj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gthqidulip.html

[U105] JS：节流
来源：http://dali.gogol.net.cn/Article/details/gtucetdoap.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xylfe.cn/Article/details/gtvscszopw.html

[U106] JS：日期格式化
来源：http://dali.shuidangran.top/Article/details/gtsekjvdpx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xylfe.cn/Article/details/gtdubncrag.html

[U107] JS：数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gtrpejfssf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gtsdfaypfe.html

[U108] JS：随机整数
来源：http://dali.fengsongda.top/Article/details/gtbjoetvkh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xziqi.cn/Article/details/gtvzhrcitd.html

[U109] JS：数组分组
来源：http://dali.gzhubu.top/Article/details/gtnhyeipqd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gtzjinuhtg.html

[U110] JS：数组分块
来源：http://dali.sxryk.cn/Article/details/gtutcaqajs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.daria6918.cn/Article/details/gtmqgcjjqs.html

[U111] JS：对象转 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyvburbd.html

new Map(Object.entries(obj))
来源：http://dali.sysykeji.top/Article/details/gtwheljsnz.html

[U112] JS：字符串补位
来源：http://dali.cashguo.top/Article/details/gtbzulmkxl.html

"7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtcfsnqiht.html

[U113] JS：正则替换全部
来源：http://dali.xylfe.cn/Article/details/gtbxdztxrr.html

s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtoodlgzqn.html

[U114] JS：JSON 深比较
来源：http://dali.nwbrower.top/Article/details/gtjawruqbs.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gteqtkqrko.html

[U115] JS：生成 UUID
来源：http://dali.zdqjudy.top/Article/details/gtiwlipocv.html

crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoseofnla.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrniumoxv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.sysykeji.top/Article/details/gtkmuldsbc.html

[U117] JS：单元测试
来源：http://dali.shangyingyoupin.top/Article/details/gtxeelvqhp.html

npm i -D vitest;  npx vitest
来源：http://dali.jiagoushi.top/Article/details/gtgyijaflr.html

[U118] JS：开发服务器
来源：http://dali.sweek.top/Article/details/gtuahyiyce.html

npm i -D vite;  npx vite
来源：http://dali.nanxuanxn.top/Article/details/gtbiaaqhkd.html

[U119] JS：生产构建
来源：http://dali.sufxvd.cn/Article/details/gthqpsugzu.html

npx vite build
来源：http://dali.guowangkeji.top/Article/details/gtczsfkdlv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ehwqpu.com/Article/details/gtehvuzidx.html

import.meta.env.VITE_API_URL
来源：http://dali.sufxvd.cn/Article/details/gtcrgbxtlz.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtmunowyoy.html

统计汇总
来源：http://dali.hywenlv.cn/Article/details/gtjvncgovn.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtgcruzbzw.html

按语言统计（条）：
来源：http://dali.nanxuanxn.top/Article/details/gtshkabztt.html

Python ......... 252
来源：http://dali.hnqzz.top/Article/details/gtidyayxft.html

PHP ............ 252
来源：http://dali.bjfxy.top/Article/details/gtwzabayci.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gtbugubsww.html

TypeScript ..... 212
来源：http://dali.316326.xyz/Article/details/gtolqtvqic.html

Java ........... 212
来源：http://dali.iojbl.cn/Article/details/gtukafjeoa.html

Go ............. 212
来源：http://dali.9152youxi.cn/Article/details/gtjtjzujyj.html

Ruby ........... 212
来源：http://dali.cashguo.top/Article/details/gtgahowkwz.html

C# ............. 212
来源：http://dali.iojbl.cn/Article/details/gtozamvczd.html

C .............. 30
来源：http://dali.yj202588.top/Article/details/gtaunuejzq.html

C++ ............ 30
来源：http://dali.yuxming.cn/Article/details/gtbqqjqigc.html

SQL ............ 90
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmthxbdnm.html

Bash ........... 80
来源：http://dali.ybcxt.top/Article/details/gtatsfbihu.html

Kotlin ......... 15
来源：http://dali.snrcjt.cn/Article/details/gtnfwfftqw.html

Swift .......... 15
来源：http://dali.hywenlv.cn/Article/details/gtcptvlfwk.html

Lua ............ 10
来源：http://dali.redwolf501.top/Article/details/gtavcncpbu.html

Perl ........... 10
来源：http://dali.ivvv.top/Article/details/gtovxbcsze.html

Scala .......... 10
来源：http://dali.pengpengdd.cyou/Article/details/gtrmneploi.html

------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gtvectrbte.html

合计 ........... 2106 条
来源：http://dali.hammf.cn/Article/details/gtrqwowhbc.html

按章节统计：
来源：http://dali.chenzaomai.com/Article/details/gtlakcurvs.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.haohaochexian.top/Article/details/gtwrgwtxrn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jianghu66.top/Article/details/gtgnjccecb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gtuqktjwtf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.quarkkingdee.top/Article/details/gtzobuvsln.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yangfankeji.com/Article/details/gtmywfsxxe.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hfpthk.cn/Article/details/gtlgjhqtkx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gteyyhmisl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenzaomai.com/Article/details/gtcvtznngd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtjglqrnal.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cucudq.cn/Article/details/gtacajkwtd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtaoogiqxl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gtpfkgsreg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gtucyhklpi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xinyue.icu/Article/details/gtzwlqdzai.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.nanxuanxn.top/Article/details/gtlwxjrxev.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtmjxtqlfx.html

Q SQL 专题                              90
来源：http://dali.guowangkeji.top/Article/details/gtxyjxtiug.html

R Bash 专题                             80
来源：http://dali.xinyue.icu/Article/details/gthtotozkb.html

S C / C++ 专题                          60
来源：http://dali.wangdashe.top/Article/details/gtftvspmvc.html

T 其他语言补充                          60
来源：http://dali.dianchejie.cn/Article/details/gtiaeurdnl.html

U 高频实用片段                         120
来源：http://dali.jqgufenzy.top/Article/details/gtqpgzjvie.html

------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtvgkngobe.html

合计                                  2106 条
来源：http://dali.yj20258888.top/Article/details/gtmmkxyvhx.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtjfifnpvf.html

使用提醒
来源：http://dali.redwolf501.top/Article/details/gtqrvxeyft.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gttwjkegqy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.fengsongda.top/Article/details/gtgsekouwc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.svipenyu.cn/Article/details/gtfxwisdfy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xuanzx.com/Article/details/gtrxfwgjmh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.fzhhl.top/Article/details/gttynbqxgf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhongyouzk.top/Article/details/gtmohwkbvn.html

—— 文件结束 ——
来源：http://dali.chenzaomai.com/Article/details/gtmvnodics.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtpynfayuh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.nanxuanxn.top/Article/details/gtydrjyhgz.html

Common Programming Examples Cheat Book
来源：http://dali.cucudq.cn/Article/details/gtrvzrlzjb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtbsrfolfp.html


<!-- 参考信息 -->