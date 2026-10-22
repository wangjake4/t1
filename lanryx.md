代发 wailian999

[U17] Py：初始化日志
来源：http://dali.aizwys.cn/Article/details/gt2wkswnrsv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daria6918.cn/Article/details/gt2jlemitcl.html

[U18] Py：预编译正则
来源：http://dali.birdmap.top/Article/details/gt2eocyjwii.html

pat = re.compile(r"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rfmvvadc.html

[U19] Py：正则替换带回调
来源：http://dali.fzhhl.top/Article/details/gt2estomydn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.andypj.xyz/Article/details/gt2rflrsmpn.html

[U20] Py：缓存函数结果
来源：http://dali.sweek.top/Article/details/gt2tvvamzwv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jyoumei.cn/Article/details/gt2qvhywxuk.html

[U21] Py：自定义上下文管理器
来源：http://dali.jyoumei.cn/Article/details/gt2bcnjxjmt.html

@contextlib.contextmanager
来源：http://dali.smart0.xyz/Article/details/gt2hspchhuo.html

[U22] Py：矩阵转置
来源：http://dali.tanke756.top/Article/details/gt2tgubatir.html

list(zip(*m))
来源：http://dali.sufxvd.cn/Article/details/gt2wliwvvlq.html

[U23] Py：分块读取大文件
来源：http://dali.nanxuanxn.top/Article/details/gt2caeyeasy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.vqdsnc.cn/Article/details/gt2pfxlcpdt.html

[U24] Py：路径操作
来源：http://dali.meibo888.top/Article/details/gt2fmzjiibw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gt2yztjobwp.html

[U25] Py：CSV 按字典读
来源：http://dali.xuanzx.com/Article/details/gt2nptjpdor.html

csv.DictReader(f)
来源：http://dali.gotoacloud.top/Article/details/gt2ovehjpgs.html

[U26] Py：并发下载
来源：http://dali.quarkkingdee.top/Article/details/gt2niwwvqjv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ybcxt.top/Article/details/gt2xotuxbbh.html

[U27] Py：异步 HTTP
来源：http://dali.zhongyouzk.top/Article/details/gt2kiqavfzq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yueranfly.top/Article/details/gt2ajhkvyls.html

[U28] Py：类型别名
来源：http://dali.hywenlv.cn/Article/details/gt2jtqkmron.html

UserId = int
来源：http://dali.jqgfzy.top/Article/details/gt2fetlaghs.html

[U29] Py：属性校验
来源：http://dali.jinqigfzy.top/Article/details/gt2uikttxox.html

@property 与 @x.setter 配合
来源：http://dali.xylfe.cn/Article/details/gt2ojucowmg.html

[U30] Py：数据类
来源：http://dali.tianlin.xyz/Article/details/gt2ewjjoqwq.html

@dataclass(slots=True)
来源：http://dali.redwolf501.top/Article/details/gt2eqkodhts.html

[U31] Py：单测
来源：http://dali.cheryme.top/Article/details/gt2pfuzdcbn.html

python -m pytest -q
来源：http://dali.smart0.xyz/Article/details/gt2zepnxlmo.html

[U32] Py：代码格式化
来源：http://dali.cashguo.top/Article/details/gt2wvbczxkd.html

ruff format . && ruff check --fix .
来源：http://dali.guannengcc.top/Article/details/gt2lkvloosw.html

[U33] Py：打包发布
来源：http://dali.aibaodan.cn/Article/details/gt2yxqbktca.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.redwolf501.top/Article/details/gt2chietcin.html

[U34] Py：判断编码
来源：http://dali.yuxming.cn/Article/details/gt2frserwtv.html

chardet.detect(raw)
来源：http://dali.svipenyu.cn/Article/details/gt2psfiievs.html

[U35] Py：发送邮件
来源：http://dali.ivvv.top/Article/details/gt2nxmgqwxf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cucudq.cn/Article/details/gt2fcnkdgkr.html

[U36] Py：定时任务
来源：http://dali.fzhhl.top/Article/details/gt2jtqxeqtp.html

schedule.every(10).minutes.do(job)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uzpblhzv.html

[U37] Py：读写 Excel
来源：http://dali.shuidangran.top/Article/details/gt2ytogltct.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhoulong.xyz/Article/details/gt2ootyylwk.html

[U38] Py：获取脚本所在目录
来源：http://dali.cucudq.cn/Article/details/gt2sudwxmqk.html

Path(__file__).resolve().parent
来源：http://dali.nanxuanxn.top/Article/details/gt2avujlgcq.html

[U39] Py：判断是否在交互环境
来源：http://dali.feifeiyinyue.top/Article/details/gt2grciqhen.html

sys.stdout.isatty()
来源：http://dali.shzxlz.cn/Article/details/gt2kzvsghlf.html

[U40] Py：打印到标准错误
来源：http://dali.cucudq.cn/Article/details/gt2ffftgwog.html

print("err", file=sys.stderr)
来源：http://dali.daxiang520.top/Article/details/gt2pwfdixds.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.guannengcc.top/Article/details/gt2gjaxajch.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sysykeji.top/Article/details/gt2pkcggfsi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.feifeiyinyue.top/Article/details/gt2hhediaha.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhongyouzk.top/Article/details/gt2grfwwrjv.html

[U43] PHP：声明命名空间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kgngnyiw.html

namespace App\Http;
来源：http://dali.pengpengdd.cyou/Article/details/gt2olmfrpfc.html

[U44] PHP：开启严格类型
来源：http://dali.yj20258.top/Article/details/gt2ulndtozz.html

declare(strict_types=1);
来源：http://dali.hnqzz.top/Article/details/gt2cytvcskv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yueranfly.top/Article/details/gt2iizdmege.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2origduph.html

[U46] PHP：可空类型
来源：http://dali.sysykeji.top/Article/details/gt2tumxdsnj.html

?string $name = null
来源：http://dali.daria6918.cn/Article/details/gt2fljeypom.html

[U47] PHP：联合类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2umlksksa.html

int|string $id
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qbgkarmf.html

[U48] PHP：纯枚举
来源：http://dali.hywenlv.cn/Article/details/gt2ooabfhnx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jiagoushi.top/Article/details/gt2sahlezrs.html

[U49] PHP：只读属性
来源：http://dali.xziqi.cn/Article/details/gt2ytguwagw.html

public readonly string $name
来源：http://dali.meibo888.top/Article/details/gt2aujhlnyc.html

[U50] PHP：构造器属性提升
来源：http://dali.yangfankeji.com/Article/details/gt2awewcnvx.html

public function __construct(private int $id) {}
来源：http://dali.meibo888.top/Article/details/gt2fwulshxk.html

[U51] PHP：数组解构
来源：http://dali.yj202588.top/Article/details/gt2vjnkgybt.html

[$a, $b] = $arr;
来源：http://dali.xuetiantiany.cn/Article/details/gt2azrblpww.html

[U52] PHP：箭头函数
来源：http://dali.zhengqikj.top/Article/details/gt2zozapznt.html

$double = fn($x) => $x * 2;
来源：http://dali.wangdashe.top/Article/details/gt2vryxtgoc.html

[U53] PHP：空合并运算符
来源：http://dali.vqdsnc.cn/Article/details/gt2txpdxbee.html

$v = $a ?? $b ?? "default";
来源：http://dali.ybcxt.top/Article/details/gt2zbzrreie.html

[U54] PHP：空安全调用
来源：http://dali.gogol.net.cn/Article/details/gt2ofmnubgl.html

$obj?->method()
来源：http://dali.gotoacloud.top/Article/details/gt2nexossat.html

[U55] PHP：match 表达式
来源：http://dali.ppjwa.cn/Article/details/gt2cbswieip.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gt2cfflnaub.html

[U56] PHP：命名参数
来源：http://dali.gaohongyu789.top/Article/details/gt2cwnsufrm.html

f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gt2qkhxdlho.html

[U57] PHP：字符串插值
来源：http://dali.yvedp.cn/Article/details/gt2xthlxzxs.html

"值: {$a}"
来源：http://dali.xziqi.cn/Article/details/gt2uxivfghz.html

[U58] PHP：数组三件套
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifnaqfiq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxmvwot.html

[U59] PHP：自定义排序
来源：http://dali.mhx1999.top/Article/details/gt2gotmnvam.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gt2ktxkbjoc.html

[U60] PHP：JSON 编解码
来源：http://dali.meibo888.top/Article/details/gt2vjkifymh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhiwuduotai.top/Article/details/gt2euhsrtbv.html

[U61] PHP：正则
来源：http://dali.xziqi.cn/Article/details/gt2lujthapp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2nrmyixbe.html

[U62] PHP：日期对象
来源：http://dali.xinyue.icu/Article/details/gt2kycwxylm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ydzc1.top/Article/details/gt2ddtqdgla.html

[U63] PHP：文件读写
来源：http://dali.guannengcc.top/Article/details/gt2igjjisee.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.9152youxi.cn/Article/details/gt2vvgzzagb.html

[U64] PHP：目录遍历
来源：http://dali.xylfe.cn/Article/details/gt2kollejll.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.chenzaomai.com/Article/details/gt2pyqmjpor.html

[U65] PHP：会话
来源：http://dali.hongshengwenyu.top/Article/details/gt2txetpztu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gt2pfxkgeew.html

[U66] PHP：设置 Cookie
来源：http://dali.hfpthk.cn/Article/details/gt2yhdlldaw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2xcxgcxok.html

[U67] PHP：处理文件上传
来源：http://dali.zhengqikj.top/Article/details/gt2rqrrhsgx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.havefunace.top/Article/details/gt2mhrqlaia.html

[U68] PHP：PDO 连接
来源：http://dali.hnqzz.top/Article/details/gt2zgwzmdts.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.wangshuangyany.cn/Article/details/gt2evuqlhxg.html

[U69] PHP：PDO 预处理
来源：http://dali.pengpengdd.cyou/Article/details/gt2uavowmbx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinqigfzy.top/Article/details/gt2awzuovzi.html

[U70] PHP：PDO 事务
来源：http://dali.nanxinkj.top/Article/details/gt2uursiwba.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.havefunace.top/Article/details/gt2ldbpvanw.html

[U71] PHP：抛出异常
来源：http://dali.yuxming.cn/Article/details/gt2zvpwmbuy.html

throw new RuntimeException("失败", 500);
来源：http://dali.yonumen.top/Article/details/gt2qfenlpuq.html

[U72] PHP：写错误日志
来源：http://dali.chenlongwang.top/Article/details/gt2yjpigvqp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jqgfzy.top/Article/details/gt2ljovtstp.html

[U73] PHP：读取 ini 配置
来源：http://dali.0kj1m.cn/Article/details/gt2icmymciw.html

parse_ini_file("config.ini", true)
来源：http://dali.guowangkeji.top/Article/details/gt2fwierwlx.html

[U74] PHP：读取环境变量
来源：http://dali.ivvv.top/Article/details/gt2ateigcfw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.birdmap.top/Article/details/gt2faixjtmm.html

[U75] PHP：依赖注入
来源：http://dali.wangdashe.top/Article/details/gt2ypvtottf.html

composer require psr/container
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qlnotszo.html

[U76] PHP：简单路由
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2orwjmnlu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.fzhhl.top/Article/details/gt2girrsrby.html

[U77] PHP：模板渲染
来源：http://dali.redwolf501.top/Article/details/gt2oqjwpqgg.html

composer require twig/twig
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmlmwmwr.html

[U78] PHP：单元测试
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbhfyakm.html

composer require --dev phpunit/phpunit
来源：http://dali.tianlin.xyz/Article/details/gt2urexvnxw.html

[U79] PHP：静态分析
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ptxbupbj.html

composer require --dev phpstan/phpstan
来源：http://dali.fengsongda.top/Article/details/gt2ruaigovo.html

[U80] PHP：代码规范修复
来源：http://dali.gogol.net.cn/Article/details/gt2ufjgfdia.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sweek.top/Article/details/gt2sskebari.html

[U81] JS：初始化项目
来源：http://dali.cucudq.cn/Article/details/gt2oahzfvcf.html

npm init -y;  npm i express
来源：http://dali.zhengqikj.top/Article/details/gt2sqckghty.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrqfxto.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.birdmap.top/Article/details/gt2nkqbgsxq.html

[U83] JS：ES Module 导入导出
来源：http://dali.sysykeji.top/Article/details/gt2xpbjjomj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2srqckcxr.html

[U84] JS：CommonJS 写法
来源：http://dali.haohaochexian.top/Article/details/gt2maqukrkc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shuidangran.top/Article/details/gt2lrsvnkeo.html

[U85] JS：可选链
来源：http://dali.yvedp.cn/Article/details/gt2utiuampr.html

a?.b?.c
来源：http://dali.c1oappe.top/Article/details/gt2xxrunogx.html

[U86] JS：空值合并
来源：http://dali.c1oappe.top/Article/details/gt2ovzheymj.html

a ?? b
来源：http://dali.sysykeji.top/Article/details/gt2ovnsnaas.html

[U87] JS：解构默认值
来源：http://dali.jlsjyb.cn/Article/details/gt2ewyulixy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.snrcjt.cn/Article/details/gt2ofjjyach.html

[U88] JS：对象展开合并
来源：http://dali.chenzaomai.com/Article/details/gt2usawmmgw.html

{ ...a, ...b }
来源：http://dali.jinqigfzy.top/Article/details/gt2noxsgztl.html

[U89] JS：数组去重
来源：http://dali.hammf.cn/Article/details/gt2xfoyywrm.html

[...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gt2yfgdnogj.html

[U90] JS：数字数组排序
来源：http://dali.dashuyun.cn/Article/details/gt2hlewxnpp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2diskzdig.html

[U91] JS：对象键值遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2dzhokwyf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.haohaochexian.top/Article/details/gt2cgyvdufw.html

[U92] JS：深拷贝
来源：http://dali.dashuyun.cn/Article/details/gt2pqnniadw.html

structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nsxvrrnp.html

[U93] JS：模板字符串
来源：http://dali.hysaishi.cn/Article/details/gt2wqsacigf.html

`共 ${n} 条`
来源：http://dali.cucudq.cn/Article/details/gt2wxnpamcl.html

[U94] JS：箭头函数
来源：http://dali.zhongyouzk.top/Article/details/gt2npylztnm.html

const double = x => x * 2;
来源：http://dali.yj20258.top/Article/details/gt2paziegfe.html

[U95] JS：Promise 包装
来源：http://dali.sweek.top/Article/details/gt2acvluvda.html

new Promise((resolve, reject) => {})
来源：http://dali.hfpthk.cn/Article/details/gt2dlncunyg.html

[U96] JS：async/await 与异常
来源：http://dali.zhixingplan.top/Article/details/gt2mmmgnmdm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2lkvtxzeq.html

[U97] JS：并发请求
来源：http://dali.jiagoushi.top/Article/details/gt2ikvldbde.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gt2ghtexuzd.html

[U98] JS：fetch 带 JSON
来源：http://dali.wangdashe.top/Article/details/gt2fqqkefmk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.316326.xyz/Article/details/gt2uyzxiwfe.html

[U99] JS：事件监听
来源：http://dali.jianghu66.top/Article/details/gt2ueggxwta.html

el.addEventListener("click", e => {})
来源：http://dali.hongshengwenyu.top/Article/details/gt2lykwlatv.html

[U100] JS：DOM 查询
来源：http://dali.cashguo.top/Article/details/gt2rhmzwhss.html

document.querySelector(".item")
来源：http://dali.fzhhl.top/Article/details/gt2jjvxnima.html

[U101] JS：classList 操作
来源：http://dali.wangshuangyany.cn/Article/details/gt2czahbmnp.html

el.classList.toggle("active")
来源：http://dali.dianchejie.cn/Article/details/gt2ipaxydcr.html

[U102] JS：本地存储
来源：http://dali.tianlin.xyz/Article/details/gt2gvbomwlx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jiagoushi.top/Article/details/gt2ficivbtu.html

[U103] JS：定时器
来源：http://dali.bjfxy.top/Article/details/gt2qpncbqob.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ivvv.top/Article/details/gt2pokqkpkd.html

[U104] JS：防抖
来源：http://dali.shanyushiyangtech.top/Article/details/gt2burtboga.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gt2qeguygjg.html

[U105] JS：节流
来源：http://dali.wangshuangyany.cn/Article/details/gt2kaxoaczv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.aizwys.cn/Article/details/gt2rlynjzok.html

[U106] JS：日期格式化
来源：http://dali.chenlongwang.top/Article/details/gt2ufhrrlbs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cashguo.top/Article/details/gt2cftrljvy.html

[U107] JS：数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gt2mjkrrbeu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yonumen.top/Article/details/gt2hqgnhqqh.html

[U108] JS：随机整数
来源：http://dali.hfpthk.cn/Article/details/gt2qfcrnuxa.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.fengsongda.top/Article/details/gt2zkunjluk.html

[U109] JS：数组分组
来源：http://dali.hammf.cn/Article/details/gt2gbfwydrg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gt2nrgjnoai.html

[U110] JS：数组分块
来源：http://dali.shuidangran.top/Article/details/gt2rvdyzuhk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jqgfzy.top/Article/details/gt2wieqejyu.html

[U111] JS：对象转 Map
来源：http://dali.yj202588.top/Article/details/gt2qpgqreor.html

new Map(Object.entries(obj))
来源：http://dali.fengsongda.top/Article/details/gt2vsjigwse.html

[U112] JS：字符串补位
来源：http://dali.nanxuanxn.top/Article/details/gt2gywwgxjt.html

"7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gt2jvqycxrw.html

[U113] JS：正则替换全部
来源：http://dali.hywenlv.cn/Article/details/gt2qwchkuoy.html

s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2auwwapje.html

[U114] JS：JSON 深比较
来源：http://dali.zhengqikj.top/Article/details/gt2imjcmesy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gt2nyienxod.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2unewpkbt.html

crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gt2camqawhd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.fengsongda.top/Article/details/gt2sidbdmbu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jiagoushi.top/Article/details/gt2jhacmnge.html

[U117] JS：单元测试
来源：http://dali.0kj1m.cn/Article/details/gt2gdqdljiy.html

npm i -D vitest;  npx vitest
来源：http://dali.yj20258.top/Article/details/gt2snyoddab.html

[U118] JS：开发服务器
来源：http://dali.shuidangran.top/Article/details/gt2lhxulawq.html

npm i -D vite;  npx vite
来源：http://dali.9152youxi.cn/Article/details/gt2vmtwxgsb.html

[U119] JS：生产构建
来源：http://dali.vqdsnc.cn/Article/details/gt2wjgptesp.html

npx vite build
来源：http://dali.pycfn.com/Article/details/gt2wrryxyqz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.wangdashe.top/Article/details/gt2awummnzu.html

import.meta.env.VITE_API_URL
来源：http://dali.zhiwuduotai.top/Article/details/gt2ztwlcoog.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2vnunjuel.html

统计汇总
来源：http://dali.yueranfly.top/Article/details/gt2uuwxnhsg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2iehbtzxa.html

按语言统计（条）：
来源：http://dali.sweek.top/Article/details/gt2balyismn.html

Python ......... 252
来源：http://dali.cucudq.cn/Article/details/gt2zidlgcgz.html

PHP ............ 252
来源：http://dali.ivvv.top/Article/details/gt2xpsqeear.html

JavaScript ..... 252
来源：http://dali.zhengqikj.top/Article/details/gt2slgnczga.html

TypeScript ..... 212
来源：http://dali.shuidangran.top/Article/details/gt2kpbhroai.html

Java ........... 212
来源：http://dali.feifeiyinyue.top/Article/details/gt2blnknfsf.html

Go ............. 212
来源：http://dali.ydzc1.top/Article/details/gt2edbeoaly.html

Ruby ........... 212
来源：http://dali.hammf.cn/Article/details/gt2fosxejuj.html

C# ............. 212
来源：http://dali.wangdashe.top/Article/details/gt2kwdsojcq.html

C .............. 30
来源：http://dali.xziqi.cn/Article/details/gt2mmfhnmpf.html

C++ ............ 30
来源：http://dali.hongshengwenyu.top/Article/details/gt2xlqjjkcz.html

SQL ............ 90
来源：http://dali.gaohongyu789.top/Article/details/gt2mmzsrukp.html

Bash ........... 80
来源：http://dali.ybcxt.top/Article/details/gt2wsthcqeb.html

Kotlin ......... 15
来源：http://dali.chenjidiqi.icu/Article/details/gt2nihcvdtv.html

Swift .......... 15
来源：http://dali.iojbl.cn/Article/details/gt2gyrmgxkp.html

Lua ............ 10
来源：http://dali.gotoacloud.top/Article/details/gt2nnersbwv.html

Perl ........... 10
来源：http://dali.zhiwuduotai.top/Article/details/gt2zrcsvbzo.html

Scala .......... 10
来源：http://dali.jyoumei.cn/Article/details/gt2yvyuwkst.html

------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gt2ptfhrrpt.html

合计 ........... 2106 条
来源：http://dali.svipenyu.cn/Article/details/gt2kzpumccj.html

按章节统计：
来源：http://dali.smart0.xyz/Article/details/gt2kidgfirb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.pycfn.com/Article/details/gt2mcyphfqd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.dashuyun.cn/Article/details/gt2tuhurfis.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gt2fjiugtrl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.dianchejie.cn/Article/details/gt2mvcrjaad.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.mhx1999.top/Article/details/gt2ziuniplp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.9152youxi.cn/Article/details/gt2nzfbpiop.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gt2qsfuhzsi.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hywenlv.cn/Article/details/gt2zmpmqsea.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gt2pqzhdjyy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhixingplan.top/Article/details/gt2jqkhrcjd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gt2xggrhxsn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gt2plxifhpu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gt2dvryhkka.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ppjwa.cn/Article/details/gt2dlohxuqq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.birdmap.top/Article/details/gt2yfwnmsmg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gt2rxckdfaq.html

Q SQL 专题                              90
来源：http://dali.wangdashe.top/Article/details/gt2aearzubf.html

R Bash 专题                             80
来源：http://dali.chenlongwang.top/Article/details/gt2hrahsahq.html

S C / C++ 专题                          60
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tzxfdkdz.html

T 其他语言补充                          60
来源：http://dali.cucudq.cn/Article/details/gt2wsoribuy.html

U 高频实用片段                         120
来源：http://dali.bjfxy.top/Article/details/gt2damwumnj.html

------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gt2fpayofvw.html

合计                                  2106 条
来源：http://dali.ybcxt.top/Article/details/gt2kihjkwox.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xvvmoteu.html

使用提醒
来源：http://dali.andypj.xyz/Article/details/gt2nsklueof.html

--------------------------------------------------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gt2nqpyxgfo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xuanzx.com/Article/details/gt2zcmtpxcp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhongyouzk.top/Article/details/gt2jwcnauqa.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.pengpengdd.cyou/Article/details/gt2muortwxh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhengqikj.top/Article/details/gt2nuyjhkhi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ybcxt.top/Article/details/gt2zmhutwzo.html

—— 文件结束 ——
来源：http://dali.dashuyun.cn/Article/details/gt2njngbrze.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2rahiamqt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.quarkkingdee.top/Article/details/gt2tagzdlyp.html

Common Programming Examples Cheat Book
来源：http://dali.yvedp.cn/Article/details/gt2ptxwuggk.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2fjphjndc.html

【收录内容】
来源：http://dali.pengpengdd.cyou/Article/details/gt2scbqgstt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hongshengwenyu.top/Article/details/gt2ulbnsgdq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hysaishi.cn/Article/details/gt2jzkxtwkq.html

SQL · Bash · C · C++
来源：http://dali.wangdashe.top/Article/details/gt2qskqzpbf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.wangshuangyany.cn/Article/details/gt2jddrzqij.html

【使用说明】
来源：http://dali.jlsjyb.cn/Article/details/gt2jvditwmy.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.kuanghao11.cn/Article/details/gt2hpozhonz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xuanzx.com/Article/details/gt2pctqkfli.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xuetiantiany.cn/Article/details/gt2lpzqwopg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shuidangran.top/Article/details/gt2tamekrmv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.c1oappe.top/Article/details/gt2mnxazvda.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xziqi.cn/Article/details/gt2ayhtgxhm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yonumen.top/Article/details/gt2rylbrgqp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yuxming.cn/Article/details/gt2knsjgmpb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xziqi.cn/Article/details/gt2rqrkzxzi.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xylfe.cn/Article/details/gt2cmyezxsj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ivvv.top/Article/details/gt2wazmwinb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.nanxuanxn.top/Article/details/gt2mhambnjp.html

【文件统计】
来源：http://dali.daria6918.cn/Article/details/gt2sgaxxvcd.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.316326.xyz/Article/details/gt2vkbgpaas.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gt2ldrwhisq.html

目  录
来源：http://dali.jqgfzy.top/Article/details/gt2ziocsyos.html

--------------------------------------------------------------------------------
来源：http://dali.ydzc1.top/Article/details/gt2sdwdjwqq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yuanzhike.top/Article/details/gt2jijthrop.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2fdzukowa.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aqbdepxs.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bqkibald.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.c1oappe.top/Article/details/gt2mamnwdbc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2lvmbhzqs.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cashguo.top/Article/details/gt2yzmqfurw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yueranfly.top/Article/details/gt2pqqvghfx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.gotoacloud.top/Article/details/gt2mgariuef.html


<!-- 参考信息 -->