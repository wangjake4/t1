代发 wailian999

[U05] Py：列表去重且保序
来源：http://dali.aizwys.cn/Article/details/gt2eyetnzog.html

list(dict.fromkeys(arr))
来源：http://dali.hongshengwenyu.top/Article/details/gt2ugbryfgg.html

[U06] Py：合并两个字典
来源：http://dali.chenzaomai.com/Article/details/gt2ijvrtman.html

{**a, **b}
来源：http://dali.nwbrower.top/Article/details/gt2ifobgmac.html

[U07] Py：反转字典键值
来源：http://dali.ydzc1.top/Article/details/gt2fnyjmzlr.html

{v: k for k, v in d.items()}
来源：http://dali.yueranfly.top/Article/details/gt2dyqtfezk.html

[U08] Py：展平二维列表
来源：http://dali.cqqwz.cn/Article/details/gt2ztxqnbom.html

[y for x in nested for y in x]
来源：http://dali.tianlin.xyz/Article/details/gt2alftsski.html

[U09] Py：字典取最大值的键
来源：http://dali.dianchejie.cn/Article/details/gt2foczbsqi.html

max(d, key=d.get)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yxogtntq.html

[U10] Py：按值排序字典
来源：http://dali.tian-w.cn/Article/details/gt2rzbjhgvs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yangfankeji.com/Article/details/gt2gpjdijuj.html

[U11] Py：生成器表达式
来源：http://dali.yj202588.top/Article/details/gt2fquukmgr.html

(x * 2 for x in arr)
来源：http://dali.gotoacloud.top/Article/details/gt2hltxbdit.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jyoumei.cn/Article/details/gt2mjbkhiwi.html

Counter(arr).most_common(3)
来源：http://dali.gotoacloud.top/Article/details/gt2zjqlykal.html

[U13] Py：固定长度队列
来源：http://dali.hysaishi.cn/Article/details/gt2anykwtvv.html

deque(maxlen=10)
来源：http://dali.sysykeji.top/Article/details/gt2dktjbjus.html

[U14] Py：分组收集到列表
来源：http://dali.tanke756.top/Article/details/gt2zqqgevht.html

defaultdict(list)
来源：http://dali.yuanzhike.top/Article/details/gt2tnjnmjxx.html

[U15] Py：高精度计时
来源：http://dali.yuanzhike.top/Article/details/gt2ebntlczz.html

t = time.perf_counter()
来源：http://dali.gzhubu.top/Article/details/gt2eirdzjyc.html

[U16] Py：命令行参数解析
来源：http://dali.hnxiangtu.top/Article/details/gt2zvsjbytq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.redwolf501.top/Article/details/gt2zflgszzo.html

[U17] Py：初始化日志
来源：http://dali.wangshuangyany.cn/Article/details/gt2gdcunwva.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gaohongyu789.top/Article/details/gt2pfakamjt.html

[U18] Py：预编译正则
来源：http://dali.pycfn.com/Article/details/gt2nzrrixam.html

pat = re.compile(r"\d+")
来源：http://dali.dianchejie.cn/Article/details/gt2nfzpybku.html

[U19] Py：正则替换带回调
来源：http://dali.shzxlz.cn/Article/details/gt2szpvgsmi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.dashuyun.cn/Article/details/gt2zxyeiueh.html

[U20] Py：缓存函数结果
来源：http://dali.dianchejie.cn/Article/details/gt2fhmtlxma.html

@functools.lru_cache(maxsize=None)
来源：http://dali.meibo888.top/Article/details/gt2cbqxuvqw.html

[U21] Py：自定义上下文管理器
来源：http://dali.cashguo.top/Article/details/gt2eadmursz.html

@contextlib.contextmanager
来源：http://dali.zhongyouzk.top/Article/details/gt2qhczfjti.html

[U22] Py：矩阵转置
来源：http://dali.nanxuanxn.top/Article/details/gt2gmooaeen.html

list(zip(*m))
来源：http://dali.dashuyun.cn/Article/details/gt2oikzuofi.html

[U23] Py：分块读取大文件
来源：http://dali.gaohongyu789.top/Article/details/gt2ncxcrbyj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yuanzhike.top/Article/details/gt2vgmzlfol.html

[U24] Py：路径操作
来源：http://dali.yonumen.top/Article/details/gt2zzjbufxx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gt2khdncafs.html

[U25] Py：CSV 按字典读
来源：http://dali.yj20258.top/Article/details/gt2lmphyavy.html

csv.DictReader(f)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qqrfkhrd.html

[U26] Py：并发下载
来源：http://dali.wangshuangyany.cn/Article/details/gt2trltcaih.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.iojbl.cn/Article/details/gt2btxzijsv.html

[U27] Py：异步 HTTP
来源：http://dali.smart0.xyz/Article/details/gt2wcisamun.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xylfe.cn/Article/details/gt2ltpessqh.html

[U28] Py：类型别名
来源：http://dali.xuanzx.com/Article/details/gt2amayadug.html

UserId = int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qbtnibwh.html

[U29] Py：属性校验
来源：http://dali.tian-w.cn/Article/details/gt2mwxxpxlu.html

@property 与 @x.setter 配合
来源：http://dali.tanke756.top/Article/details/gt2kfbgxrpb.html

[U30] Py：数据类
来源：http://dali.sxryk.cn/Article/details/gt2uxnjlnck.html

@dataclass(slots=True)
来源：http://dali.c1oappe.top/Article/details/gt2pplucryg.html

[U31] Py：单测
来源：http://dali.bjfxy.top/Article/details/gt2mmovaslk.html

python -m pytest -q
来源：http://dali.yonumen.top/Article/details/gt2hfviiski.html

[U32] Py：代码格式化
来源：http://dali.quarkkingdee.top/Article/details/gt2ppqawgcl.html

ruff format . && ruff check --fix .
来源：http://dali.shangyingyoupin.top/Article/details/gt2bqktbxrv.html

[U33] Py：打包发布
来源：http://dali.yangfankeji.com/Article/details/gt2euyrmwfk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jiibblbq.html

[U34] Py：判断编码
来源：http://dali.vqdsnc.cn/Article/details/gt2itzyjyrt.html

chardet.detect(raw)
来源：http://dali.jianghu66.top/Article/details/gt2hmmrfwar.html

[U35] Py：发送邮件
来源：http://dali.yueranfly.top/Article/details/gt2zdlqngdo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.bjfxy.top/Article/details/gt2iqoatcqs.html

[U36] Py：定时任务
来源：http://dali.chenlongwang.top/Article/details/gt2wlgjphar.html

schedule.every(10).minutes.do(job)
来源：http://dali.jyoumei.cn/Article/details/gt2midiuldd.html

[U37] Py：读写 Excel
来源：http://dali.tanke756.top/Article/details/gt2iesnjmre.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.c1oappe.top/Article/details/gt2hicdkhaa.html

[U38] Py：获取脚本所在目录
来源：http://dali.aibaodan.cn/Article/details/gt2qonblfev.html

Path(__file__).resolve().parent
来源：http://dali.hnxiangtu.top/Article/details/gt2buwmpuah.html

[U39] Py：判断是否在交互环境
来源：http://dali.hnxiangtu.top/Article/details/gt2vuoulkse.html

sys.stdout.isatty()
来源：http://dali.hammf.cn/Article/details/gt2kbnyrxwk.html

[U40] Py：打印到标准错误
来源：http://dali.jinqigfzy.top/Article/details/gt2pdnkumvm.html

print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gt2fofcntkz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xylfe.cn/Article/details/gt2pkubjpmc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jianghu66.top/Article/details/gt2znpptudi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cdnleiting.top/Article/details/gt2rtvuxcqz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.guowangkeji.top/Article/details/gt2nffffcae.html

[U43] PHP：声明命名空间
来源：http://dali.jyoumei.cn/Article/details/gt2dpcizfaw.html

namespace App\Http;
来源：http://dali.zhengqikj.top/Article/details/gt2yewvugbz.html

[U44] PHP：开启严格类型
来源：http://dali.jqgufenzy.top/Article/details/gt2syjjwssw.html

declare(strict_types=1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gokxooze.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hywenlv.cn/Article/details/gt2qtmsjvlw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gt2syabbann.html

[U46] PHP：可空类型
来源：http://dali.ydzc1.top/Article/details/gt2frcqkleh.html

?string $name = null
来源：http://dali.yonumen.top/Article/details/gt2kxyiqnqa.html

[U47] PHP：联合类型
来源：http://dali.tanke756.top/Article/details/gt2dvwnwnly.html

int|string $id
来源：http://dali.dashuyun.cn/Article/details/gt2qoapztid.html

[U48] PHP：纯枚举
来源：http://dali.smart0.xyz/Article/details/gt2jntrxwtc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ppjwa.cn/Article/details/gt2naewubjk.html

[U49] PHP：只读属性
来源：http://dali.zycfv.cn/Article/details/gt2ujatjmbq.html

public readonly string $name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwdurjqh.html

[U50] PHP：构造器属性提升
来源：http://dali.hnqzz.top/Article/details/gt2otuybclf.html

public function __construct(private int $id) {}
来源：http://dali.cucudq.cn/Article/details/gt2inkfyipj.html

[U51] PHP：数组解构
来源：http://dali.yuxming.cn/Article/details/gt2amdwzjnr.html

[$a, $b] = $arr;
来源：http://dali.hfpthk.cn/Article/details/gt2bossgpql.html

[U52] PHP：箭头函数
来源：http://dali.ydzc1.top/Article/details/gt2vgreozjj.html

$double = fn($x) => $x * 2;
来源：http://dali.jqgfzy.top/Article/details/gt2rtvggcdh.html

[U53] PHP：空合并运算符
来源：http://dali.zycfv.cn/Article/details/gt2nrxhsxlc.html

$v = $a ?? $b ?? "default";
来源：http://dali.xuanzx.com/Article/details/gt2uchkmuaz.html

[U54] PHP：空安全调用
来源：http://dali.yonumen.top/Article/details/gt2kbbdodof.html

$obj?->method()
来源：http://dali.dashuyun.cn/Article/details/gt2mdlwpqhb.html

[U55] PHP：match 表达式
来源：http://dali.9152youxi.cn/Article/details/gt2nteafqpv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.smart0.xyz/Article/details/gt2tcuqurrl.html

[U56] PHP：命名参数
来源：http://dali.meibo888.top/Article/details/gt2kercvhfu.html

f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gt2oqmcqfnq.html

[U57] PHP：字符串插值
来源：http://dali.xziqi.cn/Article/details/gt2orphqufn.html

"值: {$a}"
来源：http://dali.ybcxt.top/Article/details/gt2xnkedxlh.html

[U58] PHP：数组三件套
来源：http://dali.snrcjt.cn/Article/details/gt2vjltdrpx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.pycfn.com/Article/details/gt2ovpwmmlj.html

[U59] PHP：自定义排序
来源：http://dali.c1oappe.top/Article/details/gt2ooxgdwom.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangdashe.top/Article/details/gt2hzozvjgm.html

[U60] PHP：JSON 编解码
来源：http://dali.fengsongda.top/Article/details/gt2ilpebshp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.tian-w.cn/Article/details/gt2mgxcccmz.html

[U61] PHP：正则
来源：http://dali.zhongyouzk.top/Article/details/gt2rszyunxn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2ndvqsadb.html

[U62] PHP：日期对象
来源：http://dali.jinqigufen.top/Article/details/gt2qaqbonfh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.316326.xyz/Article/details/gt2hgzqbzwb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjgoqzn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twnahzpw.html

[U64] PHP：目录遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2vutypntq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2degmsytu.html

[U65] PHP：会话
来源：http://dali.yueranfly.top/Article/details/gt2yfocttbb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ngmimxsc.html

[U66] PHP：设置 Cookie
来源：http://dali.cheryme.top/Article/details/gt2zghbxotl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.redwolf501.top/Article/details/gt2ihdlezba.html

[U67] PHP：处理文件上传
来源：http://dali.9152youxi.cn/Article/details/gt2tictfnpe.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.wangdashe.top/Article/details/gt2wrwxtuav.html

[U68] PHP：PDO 连接
来源：http://dali.nanxuanxn.top/Article/details/gt2tfbrkbxy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinqigfzy.top/Article/details/gt2fohvmdgl.html

[U69] PHP：PDO 预处理
来源：http://dali.jqgfzy.top/Article/details/gt2vtiolvcz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhoulong.xyz/Article/details/gt2wmxlgjau.html

[U70] PHP：PDO 事务
来源：http://dali.yonumen.top/Article/details/gt2amdbdyxa.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yangfankeji.com/Article/details/gt2vykqqlwn.html

[U71] PHP：抛出异常
来源：http://dali.meibo888.top/Article/details/gt2ywylvtgr.html

throw new RuntimeException("失败", 500);
来源：http://dali.ydzc1.top/Article/details/gt2bgctcsem.html

[U72] PHP：写错误日志
来源：http://dali.zhoulong.xyz/Article/details/gt2onahibjc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ydzc1.top/Article/details/gt2dorepazm.html

[U73] PHP：读取 ini 配置
来源：http://dali.gzhubu.top/Article/details/gt2kfvwqnhk.html

parse_ini_file("config.ini", true)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xyiguuth.html

[U74] PHP：读取环境变量
来源：http://dali.redwolf501.top/Article/details/gt2nzkfphwe.html

getenv("APP_ENV") ?: "production"
来源：http://dali.redwolf501.top/Article/details/gt2zuhudawj.html

[U75] PHP：依赖注入
来源：http://dali.andypj.xyz/Article/details/gt2jfwtohhy.html

composer require psr/container
来源：http://dali.zhoulong.xyz/Article/details/gt2dnakuhir.html

[U76] PHP：简单路由
来源：http://dali.jianghu66.top/Article/details/gt2pzafrkun.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.chenjidiqi.icu/Article/details/gt2uukzfkhc.html

[U77] PHP：模板渲染
来源：http://dali.pengpengdd.cyou/Article/details/gt2zyfxnsoy.html

composer require twig/twig
来源：http://dali.316326.xyz/Article/details/gt2bjxkwdcq.html

[U78] PHP：单元测试
来源：http://dali.gaohongyu789.top/Article/details/gt2wgthplrd.html

composer require --dev phpunit/phpunit
来源：http://dali.feifeiyinyue.top/Article/details/gt2dysxmdve.html

[U79] PHP：静态分析
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fkbktyve.html

composer require --dev phpstan/phpstan
来源：http://dali.hongshengwenyu.top/Article/details/gt2olabtxtc.html

[U80] PHP：代码规范修复
来源：http://dali.yangfankeji.com/Article/details/gt2tntcamxz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.tian-w.cn/Article/details/gt2yazvwibv.html

[U81] JS：初始化项目
来源：http://dali.zhongyouzk.top/Article/details/gt2gqmtjknd.html

npm init -y;  npm i express
来源：http://dali.yuanzhike.top/Article/details/gt2scrtbshq.html

[U82] JS：package.json 脚本
来源：http://dali.daria6918.cn/Article/details/gt2ezwboynt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.tanke756.top/Article/details/gt2zheoqscg.html

[U83] JS：ES Module 导入导出
来源：http://dali.sufxvd.cn/Article/details/gt2maipgexn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sufxvd.cn/Article/details/gt2zdjknwum.html

[U84] JS：CommonJS 写法
来源：http://dali.zhengqikj.top/Article/details/gt2urjtdamy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.wangshuangyany.cn/Article/details/gt2zsfkgkup.html

[U85] JS：可选链
来源：http://dali.aibaodan.cn/Article/details/gt2ngmbwjyc.html

a?.b?.c
来源：http://dali.jiagoushi.top/Article/details/gt2kqeovgdr.html

[U86] JS：空值合并
来源：http://dali.zhengqikj.top/Article/details/gt2hvqovlun.html

a ?? b
来源：http://dali.andypj.xyz/Article/details/gt2mspklsfo.html

[U87] JS：解构默认值
来源：http://dali.xylfe.cn/Article/details/gt2tzudsduu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.wangshuangyany.cn/Article/details/gt2uafajjmg.html

[U88] JS：对象展开合并
来源：http://dali.tianlin.xyz/Article/details/gt2nemwyrhn.html

{ ...a, ...b }
来源：http://dali.xylfe.cn/Article/details/gt2gbjtkrpj.html

[U89] JS：数组去重
来源：http://dali.hammf.cn/Article/details/gt2hjdlysrw.html

[...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gt2pxqxxpwc.html

[U90] JS：数字数组排序
来源：http://dali.yj20258888.top/Article/details/gt2dfvhzvby.html

[...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gt2okiivrjm.html

[U91] JS：对象键值遍历
来源：http://dali.daria6918.cn/Article/details/gt2ijwocvto.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.aizwys.cn/Article/details/gt2tmmjatcu.html

[U92] JS：深拷贝
来源：http://dali.xuanzx.com/Article/details/gt2warbobvr.html

structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2osedopve.html

[U93] JS：模板字符串
来源：http://dali.tian-w.cn/Article/details/gt2ugxqqxpk.html

`共 ${n} 条`
来源：http://dali.cashguo.top/Article/details/gt2wftqyzkc.html

[U94] JS：箭头函数
来源：http://dali.yanxiufei.cn/Article/details/gt2qaluuwvs.html

const double = x => x * 2;
来源：http://dali.gaohongyu789.top/Article/details/gt2jidyfebo.html

[U95] JS：Promise 包装
来源：http://dali.zhengqikj.top/Article/details/gt2gnsgizgo.html

new Promise((resolve, reject) => {})
来源：http://dali.birdmap.top/Article/details/gt2bvbuxjkm.html

[U96] JS：async/await 与异常
来源：http://dali.snrcjt.cn/Article/details/gt2drujwdjm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gt2njmmcltv.html

[U97] JS：并发请求
来源：http://dali.jianghu66.top/Article/details/gt2kcanoaaa.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gt2ecvnuzxt.html

[U98] JS：fetch 带 JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2woccvbhd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.meibo888.top/Article/details/gt2oohynjzr.html

[U99] JS：事件监听
来源：http://dali.daria6918.cn/Article/details/gt2uldssfqu.html

el.addEventListener("click", e => {})
来源：http://dali.yueranfly.top/Article/details/gt2itysqoyr.html

[U100] JS：DOM 查询
来源：http://dali.sxryk.cn/Article/details/gt2mixqtrba.html

document.querySelector(".item")
来源：http://dali.cdnleiting.top/Article/details/gt2cyjzfmyu.html

[U101] JS：classList 操作
来源：http://dali.yongpay.top/Article/details/gt2vcsyrbgi.html

el.classList.toggle("active")
来源：http://dali.yueranfly.top/Article/details/gt2tfxtnmxl.html

[U102] JS：本地存储
来源：http://dali.cqqwz.cn/Article/details/gt2hyitttdf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.gotoacloud.top/Article/details/gt2rcutboyw.html

[U103] JS：定时器
来源：http://dali.guowangkeji.top/Article/details/gt2rneligle.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tslshwdv.html

[U104] JS：防抖
来源：http://dali.wangdashe.top/Article/details/gt2osygcbug.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjgdpwj.html

[U105] JS：节流
来源：http://dali.9152youxi.cn/Article/details/gt2skxbtsal.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.0kj1m.cn/Article/details/gt2qdgnjvnm.html

[U106] JS：日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gt2venxvlww.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yuanzhike.top/Article/details/gt2zcmxpjsd.html

[U107] JS：数字千分位
来源：http://dali.jianghu66.top/Article/details/gt2yfgcbvxy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xylfe.cn/Article/details/gt2uyzbhrkj.html

[U108] JS：随机整数
来源：http://dali.guowangkeji.top/Article/details/gt2xheayqve.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shzxlz.cn/Article/details/gt2yxhulsvu.html

[U109] JS：数组分组
来源：http://dali.daria6918.cn/Article/details/gt2kopwpvfj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jqgfzy.top/Article/details/gt2otfqqbph.html

[U110] JS：数组分块
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2brsfjeem.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.aizwys.cn/Article/details/gt2ngaerzbx.html

[U111] JS：对象转 Map
来源：http://dali.jiagoushi.top/Article/details/gt2idasxkia.html

new Map(Object.entries(obj))
来源：http://dali.zhoulong.xyz/Article/details/gt2sefsktlg.html

[U112] JS：字符串补位
来源：http://dali.xuetiantiany.cn/Article/details/gt2pofsgxoa.html

"7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gt2apikudtk.html

[U113] JS：正则替换全部
来源：http://dali.bjfxy.top/Article/details/gt2ipaoaqfh.html

s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2ecdzlody.html

[U114] JS：JSON 深比较
来源：http://dali.cucudq.cn/Article/details/gt2rcpsptvx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ppjwa.cn/Article/details/gt2exgfximf.html

[U115] JS：生成 UUID
来源：http://dali.birdmap.top/Article/details/gt2bbbdkhqg.html

crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gt2vmyrwjil.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sxryk.cn/Article/details/gt2tepkdvdp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2pieqonia.html

[U117] JS：单元测试
来源：http://dali.jinqigfzy.top/Article/details/gt2urygftss.html

npm i -D vitest;  npx vitest
来源：http://dali.cqqwz.cn/Article/details/gt2jjnxoekh.html

[U118] JS：开发服务器
来源：http://dali.gzhubu.top/Article/details/gt2wkogzlml.html

npm i -D vite;  npx vite
来源：http://dali.zdqjudy.top/Article/details/gt2dmplbsra.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2zifwduah.html

npx vite build
来源：http://dali.yueranfly.top/Article/details/gt2shzabfky.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.wangdashe.top/Article/details/gt2ptfnjbne.html

import.meta.env.VITE_API_URL
来源：http://dali.ppjwa.cn/Article/details/gt2megmcbig.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2bwyqgths.html

统计汇总
来源：http://dali.wangdashe.top/Article/details/gt2yoegtzch.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2uigeayij.html

按语言统计（条）：
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpjxltsr.html

Python ......... 252
来源：http://dali.hywenlv.cn/Article/details/gt2dkpzwfes.html

PHP ............ 252
来源：http://dali.hysaishi.cn/Article/details/gt2gtwhoeqv.html

JavaScript ..... 252
来源：http://dali.wangdashe.top/Article/details/gt2dswaczgr.html

TypeScript ..... 212
来源：http://dali.daxiang520.top/Article/details/gt2nmijmgyj.html

Java ........... 212
来源：http://dali.guannengcc.top/Article/details/gt2rppisqgo.html

Go ............. 212
来源：http://dali.iojbl.cn/Article/details/gt2hdxzgirf.html

Ruby ........... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bfgniszx.html

C# ............. 212
来源：http://dali.zhengqikj.top/Article/details/gt2inqcqkxj.html

C .............. 30
来源：http://dali.guannengcc.top/Article/details/gt2tuihrzxk.html

C++ ............ 30
来源：http://dali.feifeiyinyue.top/Article/details/gt2zpaqevbe.html

SQL ............ 90
来源：http://dali.zhoulong.xyz/Article/details/gt2pzbvower.html

Bash ........... 80
来源：http://dali.dianchejie.cn/Article/details/gt2eutleykc.html

Kotlin ......... 15
来源：http://dali.pycfn.com/Article/details/gt2cgsbywea.html

Swift .......... 15
来源：http://dali.jianghu66.top/Article/details/gt2yqlupvql.html

Lua ............ 10
来源：http://dali.quarkkingdee.top/Article/details/gt2gmopbppu.html

Perl ........... 10
来源：http://dali.vqdsnc.cn/Article/details/gt2ywusvaor.html

Scala .......... 10
来源：http://dali.iojbl.cn/Article/details/gt2nkafsqea.html

------------------------------------
来源：http://dali.xuanzx.com/Article/details/gt2dfjkminx.html

合计 ........... 2106 条
来源：http://dali.ybcxt.top/Article/details/gt2rycwbdxj.html

按章节统计：
来源：http://dali.yangfankeji.com/Article/details/gt2jsagukmx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shangyingyoupin.top/Article/details/gt2ybgnpgdq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gt2zahsxvdt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gt2hbtwyglt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gt2hgbfqlfn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hysaishi.cn/Article/details/gt2htuuigvc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.chenjidiqi.icu/Article/details/gt2axtgfqhu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jqgfzy.top/Article/details/gt2cinfhttv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yuxming.cn/Article/details/gt2ffoijkoi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gt2oiuzyvwc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.quarkkingdee.top/Article/details/gt2vgsztkpr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gt2vsnnkwnz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gt2uljmmyrt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gt2okdhujsh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shzxlz.cn/Article/details/gt2vdfqxmaj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.meibo888.top/Article/details/gt2rygrikmw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gt2hufgatet.html

Q SQL 专题                              90
来源：http://dali.pycfn.com/Article/details/gt2zkkxzxwj.html

R Bash 专题                             80
来源：http://dali.sxryk.cn/Article/details/gt2ignwbpib.html

S C / C++ 专题                          60
来源：http://dali.xylfe.cn/Article/details/gt2nrwbehug.html

T 其他语言补充                          60
来源：http://dali.zhengqikj.top/Article/details/gt2njsexlaq.html

U 高频实用片段                         120
来源：http://dali.nanxuanxn.top/Article/details/gt2kdshbhgx.html

------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gt2mstuvfaz.html

合计                                  2106 条
来源：http://dali.aizwys.cn/Article/details/gt2kivicvng.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gt2fotsannd.html

使用提醒
来源：http://dali.cqqwz.cn/Article/details/gt2scqixasr.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gt2tftakoma.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yj20258.top/Article/details/gt2gmnlvyyx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sxryk.cn/Article/details/gt2uqlkpcjr.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yvedp.cn/Article/details/gt2nzlvicqn.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.nanxuanxn.top/Article/details/gt2jyruxgwn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ehwqpu.com/Article/details/gt2ltwsfwda.html

—— 文件结束 ——
来源：http://dali.yangfankeji.com/Article/details/gt2girptptl.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2mhmfrryz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.feifeiyinyue.top/Article/details/gt2gvhoeznb.html

Common Programming Examples Cheat Book
来源：http://dali.cucudq.cn/Article/details/gt2fzuswips.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2rzrjmpgc.html

【收录内容】
来源：http://dali.gzhubu.top/Article/details/gt2ufuuwqoo.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.wangdashe.top/Article/details/gt2hstgwtfa.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2liqtpezc.html

SQL · Bash · C · C++
来源：http://dali.ydzc1.top/Article/details/gt2ikkhukql.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yanxiufei.cn/Article/details/gt2etwiganq.html

【使用说明】
来源：http://dali.chenlongwang.top/Article/details/gt2mzhcuxar.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.meibo888.top/Article/details/gt2nbibsmny.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.bjfxy.top/Article/details/gt2cyfoxdpk.html


<!-- 参考信息 -->