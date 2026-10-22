代发 wailian999

[U05] Py：列表去重且保序
来源：http://dali.hammf.cn/Article/details/gt2xtjisiaw.html

list(dict.fromkeys(arr))
来源：http://dali.xuetiantiany.cn/Article/details/gt2zzxaxwdf.html

[U06] Py：合并两个字典
来源：http://dali.jinqigfzy.top/Article/details/gt2qamgijhk.html

{**a, **b}
来源：http://dali.redwolf501.top/Article/details/gt2iozmvpda.html

[U07] Py：反转字典键值
来源：http://dali.nanxinkj.top/Article/details/gt2jxskjzdf.html

{v: k for k, v in d.items()}
来源：http://dali.feifeiyinyue.top/Article/details/gt2awigtpyu.html

[U08] Py：展平二维列表
来源：http://dali.yueranfly.top/Article/details/gt2egbqcafm.html

[y for x in nested for y in x]
来源：http://dali.zhengqikj.top/Article/details/gt2ghkssxsk.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigfzy.top/Article/details/gt2rvvavooj.html

max(d, key=d.get)
来源：http://dali.316326.xyz/Article/details/gt2gfdpoyhs.html

[U10] Py：按值排序字典
来源：http://dali.pycfn.com/Article/details/gt2itqxvyae.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yongpay.top/Article/details/gt2rrtgeqge.html

[U11] Py：生成器表达式
来源：http://dali.yonumen.top/Article/details/gt2yyjhpamm.html

(x * 2 for x in arr)
来源：http://dali.guowangkeji.top/Article/details/gt2emgndjcu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.9152youxi.cn/Article/details/gt2imaozfdl.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2psjzvxya.html

[U13] Py：固定长度队列
来源：http://dali.ivvv.top/Article/details/gt2kgihhiru.html

deque(maxlen=10)
来源：http://dali.tanke756.top/Article/details/gt2nuryhkyf.html

[U14] Py：分组收集到列表
来源：http://dali.hammf.cn/Article/details/gt2kefpbort.html

defaultdict(list)
来源：http://dali.birdmap.top/Article/details/gt2pmunqogw.html

[U15] Py：高精度计时
来源：http://dali.jyoumei.cn/Article/details/gt2yyhmtcmg.html

t = time.perf_counter()
来源：http://dali.yanxiufei.cn/Article/details/gt2dzbpwssg.html

[U16] Py：命令行参数解析
来源：http://dali.yj20258.top/Article/details/gt2woxlsugt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.fzhhl.top/Article/details/gt2xuxsclrl.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2swgsvraf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinqigfzy.top/Article/details/gt2ttnxbfqm.html

[U18] Py：预编译正则
来源：http://dali.hammf.cn/Article/details/gt2azdcytxj.html

pat = re.compile(r"\d+")
来源：http://dali.gaohongyu789.top/Article/details/gt2xtfecvks.html

[U19] Py：正则替换带回调
来源：http://dali.yuanzhike.top/Article/details/gt2wdqexmzf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.dashuyun.cn/Article/details/gt2qsfxjksg.html

[U20] Py：缓存函数结果
来源：http://dali.chenjidiqi.icu/Article/details/gt2ihehpaza.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ggzludyd.html

[U21] Py：自定义上下文管理器
来源：http://dali.yongpay.top/Article/details/gt2ctyfsdui.html

@contextlib.contextmanager
来源：http://dali.zhoulong.xyz/Article/details/gt2mjmwdwpn.html

[U22] Py：矩阵转置
来源：http://dali.0kj1m.cn/Article/details/gt2qjeumteb.html

list(zip(*m))
来源：http://dali.zycfv.cn/Article/details/gt2juvzqqum.html

[U23] Py：分块读取大文件
来源：http://dali.zycfv.cn/Article/details/gt2pidvwgiw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ydzc1.top/Article/details/gt2gswsbycj.html

[U24] Py：路径操作
来源：http://dali.zhengqikj.top/Article/details/gt2qsyejxqu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gt2ibhvsoiz.html

[U25] Py：CSV 按字典读
来源：http://dali.aibaodan.cn/Article/details/gt2jxlunfal.html

csv.DictReader(f)
来源：http://dali.sufxvd.cn/Article/details/gt2hshfayla.html

[U26] Py：并发下载
来源：http://dali.chenjidiqi.icu/Article/details/gt2vowidvec.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xuanzx.com/Article/details/gt2eeiysmzy.html

[U27] Py：异步 HTTP
来源：http://dali.xylfe.cn/Article/details/gt2egoiziet.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tian-w.cn/Article/details/gt2nahjcest.html

[U28] Py：类型别名
来源：http://dali.xuetiantiany.cn/Article/details/gt2tsqlhmpv.html

UserId = int
来源：http://dali.cucudq.cn/Article/details/gt2emgcqkmo.html

[U29] Py：属性校验
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rklhbgim.html

@property 与 @x.setter 配合
来源：http://dali.xylfe.cn/Article/details/gt2drrtxskp.html

[U30] Py：数据类
来源：http://dali.cashguo.top/Article/details/gt2phigbbpc.html

@dataclass(slots=True)
来源：http://dali.jqgfzy.top/Article/details/gt2wnsdkitk.html

[U31] Py：单测
来源：http://dali.vqdsnc.cn/Article/details/gt2sepezqgg.html

python -m pytest -q
来源：http://dali.hywenlv.cn/Article/details/gt2fngcdhtq.html

[U32] Py：代码格式化
来源：http://dali.jianghu66.top/Article/details/gt2lvbkcsog.html

ruff format . && ruff check --fix .
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smzltcsj.html

[U33] Py：打包发布
来源：http://dali.hywenlv.cn/Article/details/gt2lzzzpqtq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.dashuyun.cn/Article/details/gt2muivnbxp.html

[U34] Py：判断编码
来源：http://dali.cashguo.top/Article/details/gt2bvzokmcu.html

chardet.detect(raw)
来源：http://dali.sysykeji.top/Article/details/gt2ynoedamh.html

[U35] Py：发送邮件
来源：http://dali.smart0.xyz/Article/details/gt2fosgihuq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gzhubu.top/Article/details/gt2xcwtifge.html

[U36] Py：定时任务
来源：http://dali.0kj1m.cn/Article/details/gt2hkrzosid.html

schedule.every(10).minutes.do(job)
来源：http://dali.cdnleiting.top/Article/details/gt2nudvtybu.html

[U37] Py：读写 Excel
来源：http://dali.nanxuanxn.top/Article/details/gt2aqycuyob.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.havefunace.top/Article/details/gt2eclqjelh.html

[U38] Py：获取脚本所在目录
来源：http://dali.sweek.top/Article/details/gt2thufkgrc.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2kucbwial.html

[U39] Py：判断是否在交互环境
来源：http://dali.zycfv.cn/Article/details/gt2smxzqrlq.html

sys.stdout.isatty()
来源：http://dali.yueranfly.top/Article/details/gt2hwppvmlg.html

[U40] Py：打印到标准错误
来源：http://dali.cqqwz.cn/Article/details/gt2vmrbqutu.html

print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fvzyndwu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.feifeiyinyue.top/Article/details/gt2uiproqkm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.mhx1999.top/Article/details/gt2puzmutuj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.mhx1999.top/Article/details/gt2orolwpdb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jiagoushi.top/Article/details/gt2ziidzqzk.html

[U43] PHP：声明命名空间
来源：http://dali.hammf.cn/Article/details/gt2gzbfyfco.html

namespace App\Http;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ziukisvv.html

[U44] PHP：开启严格类型
来源：http://dali.zhengqikj.top/Article/details/gt2psniipyh.html

declare(strict_types=1);
来源：http://dali.hywenlv.cn/Article/details/gt2hccsqtcj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.tianlin.xyz/Article/details/gt2xwvbjpbc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2baosvjhy.html

[U46] PHP：可空类型
来源：http://dali.dashuyun.cn/Article/details/gt2czwaqnvn.html

?string $name = null
来源：http://dali.shzxlz.cn/Article/details/gt2lgppdtwm.html

[U47] PHP：联合类型
来源：http://dali.sufxvd.cn/Article/details/gt2szyyphkm.html

int|string $id
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2edjkhsxi.html

[U48] PHP：纯枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jikhokhk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gmxusbvy.html

[U49] PHP：只读属性
来源：http://dali.aizwys.cn/Article/details/gt2ocqtpynb.html

public readonly string $name
来源：http://dali.chenjidiqi.icu/Article/details/gt2jruedqas.html

[U50] PHP：构造器属性提升
来源：http://dali.gaohongyu789.top/Article/details/gt2raxtndee.html

public function __construct(private int $id) {}
来源：http://dali.hnqzz.top/Article/details/gt2rxmzgvpb.html

[U51] PHP：数组解构
来源：http://dali.xylfe.cn/Article/details/gt2enzvfpwc.html

[$a, $b] = $arr;
来源：http://dali.cdnleiting.top/Article/details/gt2pmkfmono.html

[U52] PHP：箭头函数
来源：http://dali.kuanghao11.cn/Article/details/gt2pziyufla.html

$double = fn($x) => $x * 2;
来源：http://dali.gogol.net.cn/Article/details/gt2mwacpjao.html

[U53] PHP：空合并运算符
来源：http://dali.nanxuanxn.top/Article/details/gt2akbjtxhb.html

$v = $a ?? $b ?? "default";
来源：http://dali.yj20258888.top/Article/details/gt2qgllrpmq.html

[U54] PHP：空安全调用
来源：http://dali.hysaishi.cn/Article/details/gt2cuwlaxnz.html

$obj?->method()
来源：http://dali.redwolf501.top/Article/details/gt2phzwqtqr.html

[U55] PHP：match 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yypigohb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.wangdashe.top/Article/details/gt2hokjhnvy.html

[U56] PHP：命名参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iksjjzif.html

f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gt2ufatacnc.html

[U57] PHP：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gt2pzavlnye.html

"值: {$a}"
来源：http://dali.hfpthk.cn/Article/details/gt2lacpoxvr.html

[U58] PHP：数组三件套
来源：http://dali.hysaishi.cn/Article/details/gt2qfiryige.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jianghu66.top/Article/details/gt2jloxrdhd.html

[U59] PHP：自定义排序
来源：http://dali.smart0.xyz/Article/details/gt2oluiwmib.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jlsjyb.cn/Article/details/gt2bzmwnsbj.html

[U60] PHP：JSON 编解码
来源：http://dali.316326.xyz/Article/details/gt2naoblrqj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yuxming.cn/Article/details/gt2sloovelb.html

[U61] PHP：正则
来源：http://dali.ehwqpu.com/Article/details/gt2bwsmjyny.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2fdzplxbo.html

[U62] PHP：日期对象
来源：http://dali.yonumen.top/Article/details/gt2bajxamyu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hammf.cn/Article/details/gt2uxqxymih.html

[U63] PHP：文件读写
来源：http://dali.daxiang520.top/Article/details/gt2ffrohtuq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhiwuduotai.top/Article/details/gt2fbtrbyqk.html

[U64] PHP：目录遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2vhtxgsoa.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lgrcqxew.html

[U65] PHP：会话
来源：http://dali.kuanghao11.cn/Article/details/gt2njblapja.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jianghu66.top/Article/details/gt2fdeldkda.html

[U66] PHP：设置 Cookie
来源：http://dali.daxiang520.top/Article/details/gt2uhsplqez.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ivvv.top/Article/details/gt2sustitnu.html

[U67] PHP：处理文件上传
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sggrdpqr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.c1oappe.top/Article/details/gt2jcdllrvr.html

[U68] PHP：PDO 连接
来源：http://dali.cdnleiting.top/Article/details/gt2cddpgtch.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xziqi.cn/Article/details/gt2xeteabwk.html

[U69] PHP：PDO 预处理
来源：http://dali.cucudq.cn/Article/details/gt2ixxirzkm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhixingplan.top/Article/details/gt2frwjaxgd.html

[U70] PHP：PDO 事务
来源：http://dali.snrcjt.cn/Article/details/gt2ecazfdmd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xtjwrquo.html

[U71] PHP：抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gt2hypfhsou.html

throw new RuntimeException("失败", 500);
来源：http://dali.aizwys.cn/Article/details/gt2ghrgtqnt.html

[U72] PHP：写错误日志
来源：http://dali.smart0.xyz/Article/details/gt2xvhokutr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sysykeji.top/Article/details/gt2gjoyropy.html

[U73] PHP：读取 ini 配置
来源：http://dali.gaohongyu789.top/Article/details/gt2obttypzb.html

parse_ini_file("config.ini", true)
来源：http://dali.yvedp.cn/Article/details/gt2wsiowfec.html

[U74] PHP：读取环境变量
来源：http://dali.c1oappe.top/Article/details/gt2zeykudql.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sweek.top/Article/details/gt2edxqlnpy.html

[U75] PHP：依赖注入
来源：http://dali.gotoacloud.top/Article/details/gt2aaayrevn.html

composer require psr/container
来源：http://dali.daxiang520.top/Article/details/gt2ecoxbpfj.html

[U76] PHP：简单路由
来源：http://dali.cashguo.top/Article/details/gt2nwmlfqxj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.dashuyun.cn/Article/details/gt2yphalhfh.html

[U77] PHP：模板渲染
来源：http://dali.zhoulong.xyz/Article/details/gt2unvbuuiw.html

composer require twig/twig
来源：http://dali.quarkkingdee.top/Article/details/gt2giotuqrn.html

[U78] PHP：单元测试
来源：http://dali.cqqwz.cn/Article/details/gt2fzpvzlac.html

composer require --dev phpunit/phpunit
来源：http://dali.zhongyouzk.top/Article/details/gt2rhmnkold.html

[U79] PHP：静态分析
来源：http://dali.kuanghao11.cn/Article/details/gt2upuveizb.html

composer require --dev phpstan/phpstan
来源：http://dali.daxiang520.top/Article/details/gt2fojdajdq.html

[U80] PHP：代码规范修复
来源：http://dali.birdmap.top/Article/details/gt2dwvavupm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yj20258888.top/Article/details/gt2yhikupuv.html

[U81] JS：初始化项目
来源：http://dali.cucudq.cn/Article/details/gt2epkjtgch.html

npm init -y;  npm i express
来源：http://dali.gogol.net.cn/Article/details/gt2izycgewr.html

[U82] JS：package.json 脚本
来源：http://dali.yvedp.cn/Article/details/gt2kkcgobwe.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sysykeji.top/Article/details/gt2ufswoxnu.html

[U83] JS：ES Module 导入导出
来源：http://dali.yangfankeji.com/Article/details/gt2dtdccpks.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gt2bykzayig.html

[U84] JS：CommonJS 写法
来源：http://dali.xylfe.cn/Article/details/gt2gykbxnqs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhengqikj.top/Article/details/gt2tumocxtg.html

[U85] JS：可选链
来源：http://dali.mhx1999.top/Article/details/gt2gsjzvpjw.html

a?.b?.c
来源：http://dali.cashguo.top/Article/details/gt2zftnujma.html

[U86] JS：空值合并
来源：http://dali.yj20258.top/Article/details/gt2naucuzvt.html

a ?? b
来源：http://dali.yj20258.top/Article/details/gt2epodyufw.html

[U87] JS：解构默认值
来源：http://dali.zdqjudy.top/Article/details/gt2ihzypsva.html

const { a = 1, b = 2 } = obj;
来源：http://dali.aizwys.cn/Article/details/gt2izsixbby.html

[U88] JS：对象展开合并
来源：http://dali.cdnleiting.top/Article/details/gt2vnbfoxah.html

{ ...a, ...b }
来源：http://dali.xuanzx.com/Article/details/gt2slxatpzn.html

[U89] JS：数组去重
来源：http://dali.jinqigfzy.top/Article/details/gt2huxgsxcl.html

[...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gt2naqahxit.html

[U90] JS：数字数组排序
来源：http://dali.jyoumei.cn/Article/details/gt2gwreqmmx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gt2cbhvgrau.html

[U91] JS：对象键值遍历
来源：http://dali.ehwqpu.com/Article/details/gt2xhikqiih.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zdqjudy.top/Article/details/gt2kaviqqey.html

[U92] JS：深拷贝
来源：http://dali.yuanzhike.top/Article/details/gt2lzcgqqcy.html

structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gt2popldsbd.html

[U93] JS：模板字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ekvhzsju.html

`共 ${n} 条`
来源：http://dali.jianghu66.top/Article/details/gt2elhpfxry.html

[U94] JS：箭头函数
来源：http://dali.gogol.net.cn/Article/details/gt2ywnjndxo.html

const double = x => x * 2;
来源：http://dali.aibaodan.cn/Article/details/gt2jgecnjjz.html

[U95] JS：Promise 包装
来源：http://dali.mhx1999.top/Article/details/gt2obgsvrsn.html

new Promise((resolve, reject) => {})
来源：http://dali.hysaishi.cn/Article/details/gt2osndeovs.html

[U96] JS：async/await 与异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2lblgmuup.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gt2whyvkqyb.html

[U97] JS：并发请求
来源：http://dali.haohaochexian.top/Article/details/gt2teacorhn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gt2cbyetxjs.html

[U98] JS：fetch 带 JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gt2npndppia.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2eqztqpbr.html

[U99] JS：事件监听
来源：http://dali.cashguo.top/Article/details/gt2cunlltzf.html

el.addEventListener("click", e => {})
来源：http://dali.gaohongyu789.top/Article/details/gt2ipfvoajw.html

[U100] JS：DOM 查询
来源：http://dali.sufxvd.cn/Article/details/gt2puuedazw.html

document.querySelector(".item")
来源：http://dali.yuanzhike.top/Article/details/gt2zhvrdpco.html

[U101] JS：classList 操作
来源：http://dali.sysykeji.top/Article/details/gt2yrepvqrf.html

el.classList.toggle("active")
来源：http://dali.9152youxi.cn/Article/details/gt2qijwruva.html

[U102] JS：本地存储
来源：http://dali.chenzaomai.com/Article/details/gt2xdygxvmz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zdqjudy.top/Article/details/gt2mefmclsd.html

[U103] JS：定时器
来源：http://dali.yvedp.cn/Article/details/gt2yjtnaitx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jlsjyb.cn/Article/details/gt2vqpzznsn.html

[U104] JS：防抖
来源：http://dali.meibo888.top/Article/details/gt2rsddlbtd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gt2gptnblln.html

[U105] JS：节流
来源：http://dali.gogol.net.cn/Article/details/gt2embyeuel.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yonumen.top/Article/details/gt2zkwpvdgm.html

[U106] JS：日期格式化
来源：http://dali.316326.xyz/Article/details/gt2kkjywkpz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zdqjudy.top/Article/details/gt2wugdrsnp.html

[U107] JS：数字千分位
来源：http://dali.hysaishi.cn/Article/details/gt2kvvkfggj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.smart0.xyz/Article/details/gt2fchsrpgr.html

[U108] JS：随机整数
来源：http://dali.yanxiufei.cn/Article/details/gt2aomtqdhl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zycfv.cn/Article/details/gt2aowbdjyq.html

[U109] JS：数组分组
来源：http://dali.tanke756.top/Article/details/gt2tnaavcgs.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xylbwahi.html

[U110] JS：数组分块
来源：http://dali.yj20258888.top/Article/details/gt2fewzirje.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhiwuduotai.top/Article/details/gt2knmnafbn.html

[U111] JS：对象转 Map
来源：http://dali.snrcjt.cn/Article/details/gt2pntnptor.html

new Map(Object.entries(obj))
来源：http://dali.aibaodan.cn/Article/details/gt2wyznuhzo.html

[U112] JS：字符串补位
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ycsechaq.html

"7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gt2dcrxwjap.html

[U113] JS：正则替换全部
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pzfkkbhw.html

s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2nnfcddmd.html

[U114] JS：JSON 深比较
来源：http://dali.svipenyu.cn/Article/details/gt2qpekzgey.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gt2fcfecwme.html

[U115] JS：生成 UUID
来源：http://dali.fzhhl.top/Article/details/gt2abkqunbd.html

crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gt2jahyeust.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.smart0.xyz/Article/details/gt2azqeatlj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gogol.net.cn/Article/details/gt2pekcrhjs.html

[U117] JS：单元测试
来源：http://dali.jianghu66.top/Article/details/gt2xlttdymk.html

npm i -D vitest;  npx vitest
来源：http://dali.jiagoushi.top/Article/details/gt2lslutsbn.html

[U118] JS：开发服务器
来源：http://dali.yuanzhike.top/Article/details/gt2ldijmzar.html

npm i -D vite;  npx vite
来源：http://dali.pycfn.com/Article/details/gt2kaaigtll.html

[U119] JS：生产构建
来源：http://dali.fzhhl.top/Article/details/gt2eflnlhfa.html

npx vite build
来源：http://dali.gzhubu.top/Article/details/gt2vvgjrsvh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.wangdashe.top/Article/details/gt2urarlizv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhongyouzk.top/Article/details/gt2srarbmjv.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2fcrikmgx.html

统计汇总
来源：http://dali.hfpthk.cn/Article/details/gt2tjjvlcpy.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2qrdyffsv.html

按语言统计（条）：
来源：http://dali.sysykeji.top/Article/details/gt2ngsjmzha.html

Python ......... 252
来源：http://dali.gzhubu.top/Article/details/gt2lhaugrss.html

PHP ............ 252
来源：http://dali.bjfxy.top/Article/details/gt2zeetpbap.html

JavaScript ..... 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umlelyyf.html

TypeScript ..... 212
来源：http://dali.hfpthk.cn/Article/details/gt2qypufupw.html

Java ........... 212
来源：http://dali.zhiwuduotai.top/Article/details/gt2novtawvu.html

Go ............. 212
来源：http://dali.cashguo.top/Article/details/gt2vzrwsiuj.html

Ruby ........... 212
来源：http://dali.sxryk.cn/Article/details/gt2evvpihaz.html

C# ............. 212
来源：http://dali.havefunace.top/Article/details/gt2tjdzyhyi.html

C .............. 30
来源：http://dali.shzxlz.cn/Article/details/gt2xxcqdpsa.html

C++ ............ 30
来源：http://dali.hfpthk.cn/Article/details/gt2htksjzna.html

SQL ............ 90
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjtrqvpx.html

Bash ........... 80
来源：http://dali.pycfn.com/Article/details/gt2dcdklbfz.html

Kotlin ......... 15
来源：http://dali.nanxinkj.top/Article/details/gt2jucktsfn.html

Swift .......... 15
来源：http://dali.kuanghao11.cn/Article/details/gt2pugjbygq.html

Lua ............ 10
来源：http://dali.aizwys.cn/Article/details/gt2beqgiolk.html

Perl ........... 10
来源：http://dali.yanxiufei.cn/Article/details/gt2ukmzowys.html

Scala .......... 10
来源：http://dali.yuanzhike.top/Article/details/gt2sewqfzva.html

------------------------------------
来源：http://dali.hnqzz.top/Article/details/gt2fzdyweeg.html

合计 ........... 2106 条
来源：http://dali.pycfn.com/Article/details/gt2uypuxhfm.html

按章节统计：
来源：http://dali.vqdsnc.cn/Article/details/gt2owxxrgkf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hammf.cn/Article/details/gt2ttzigxsy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbirkrfg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcmnqqic.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ivvv.top/Article/details/gt2xboxefox.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.nwbrower.top/Article/details/gt2xpmwiqgw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tianlin.xyz/Article/details/gt2cqgsgufn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hammf.cn/Article/details/gt2svzmayqb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenzaomai.com/Article/details/gt2bzgvsofq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gt2rftyqwzd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yuanzhike.top/Article/details/gt2aarotpec.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gt2vbvszqtn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gt2apljuoug.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gt2uhzoaikw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.redwolf501.top/Article/details/gt2bpydeyvu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xylfe.cn/Article/details/gt2ixzhskvp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gt2yqgglbdp.html

Q SQL 专题                              90
来源：http://dali.jianghu66.top/Article/details/gt2fvshqvqx.html

R Bash 专题                             80
来源：http://dali.9152youxi.cn/Article/details/gt2qecupbcu.html

S C / C++ 专题                          60
来源：http://dali.jiagoushi.top/Article/details/gt2ycslzzrm.html

T 其他语言补充                          60
来源：http://dali.chenlongwang.top/Article/details/gt2jqbhanzm.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2jbufwpvb.html

------------------------------------
来源：http://dali.nwbrower.top/Article/details/gt2aefbpapc.html

合计                                  2106 条
来源：http://dali.jinqigfzy.top/Article/details/gt2ivzswjft.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ykbwnbby.html

使用提醒
来源：http://dali.gaohongyu789.top/Article/details/gt2wyesrvgc.html

--------------------------------------------------------------------------------
来源：http://dali.cashguo.top/Article/details/gt2gcenzknq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xuanzx.com/Article/details/gt2tnnaodve.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yueranfly.top/Article/details/gt2xdsglrhh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ybcxt.top/Article/details/gt2wgbummnd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.nwbrower.top/Article/details/gt2krqqupht.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.daxiang520.top/Article/details/gt2hiicvjgc.html

—— 文件结束 ——
来源：http://dali.cqqwz.cn/Article/details/gt2zwcbcifi.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2gddrobop.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.0kj1m.cn/Article/details/gt2slhzjfyb.html

Common Programming Examples Cheat Book
来源：http://dali.shzxlz.cn/Article/details/gt2rndnrfwt.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2iptmpvyz.html

【收录内容】
来源：http://dali.dianchejie.cn/Article/details/gt2siovnual.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yangfankeji.com/Article/details/gt2zavmovor.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhongyouzk.top/Article/details/gt2beengmrw.html

SQL · Bash · C · C++
来源：http://dali.sysykeji.top/Article/details/gt2mgrzllin.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yonumen.top/Article/details/gt2lyoezhjd.html

【使用说明】
来源：http://dali.cqqwz.cn/Article/details/gt2rnrvzogj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cdnleiting.top/Article/details/gt2yrutbiik.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.feifeiyinyue.top/Article/details/gt2hbigwxag.html


<!-- 参考信息 -->