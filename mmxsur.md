代发 wailian999

[U31] Py：单测
来源：http://dali.316326.xyz/Article/details/gt2erktvyqs.html

python -m pytest -q
来源：http://dali.hfpthk.cn/Article/details/gt2jhlczvmq.html

[U32] Py：代码格式化
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqipmlgc.html

ruff format . && ruff check --fix .
来源：http://dali.cashguo.top/Article/details/gt2kgnbrvou.html

[U33] Py：打包发布
来源：http://dali.birdmap.top/Article/details/gt2trudwddz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ydzc1.top/Article/details/gt2tqhmkqhw.html

[U34] Py：判断编码
来源：http://dali.sysykeji.top/Article/details/gt2xjxilqbe.html

chardet.detect(raw)
来源：http://dali.tian-w.cn/Article/details/gt2khiatexr.html

[U35] Py：发送邮件
来源：http://dali.kuanghao11.cn/Article/details/gt2mrapjimu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hammf.cn/Article/details/gt2zjcpyqby.html

[U36] Py：定时任务
来源：http://dali.ydzc1.top/Article/details/gt2crwwgkmx.html

schedule.every(10).minutes.do(job)
来源：http://dali.tian-w.cn/Article/details/gt2edqkunnf.html

[U37] Py：读写 Excel
来源：http://dali.yanxiufei.cn/Article/details/gt2jfabwacb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ybcxt.top/Article/details/gt2mchrmqnl.html

[U38] Py：获取脚本所在目录
来源：http://dali.ivvv.top/Article/details/gt2gzafexue.html

Path(__file__).resolve().parent
来源：http://dali.andypj.xyz/Article/details/gt2svqfimed.html

[U39] Py：判断是否在交互环境
来源：http://dali.yj20258888.top/Article/details/gt2syurlvdb.html

sys.stdout.isatty()
来源：http://dali.snrcjt.cn/Article/details/gt2jjlwzduq.html

[U40] Py：打印到标准错误
来源：http://dali.aibaodan.cn/Article/details/gt2pktpxdip.html

print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gt2vpvjfnbw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cdnleiting.top/Article/details/gt2kofoujcj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.havefunace.top/Article/details/gt2oaxqurxu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.daxiang520.top/Article/details/gt2ltcwbeye.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yj202588.top/Article/details/gt2vbpbjtwo.html

[U43] PHP：声明命名空间
来源：http://dali.zhoulong.xyz/Article/details/gt2lpbbavef.html

namespace App\Http;
来源：http://dali.9152youxi.cn/Article/details/gt2tbutiemd.html

[U44] PHP：开启严格类型
来源：http://dali.tianlin.xyz/Article/details/gt2vodikwye.html

declare(strict_types=1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2lhbunsxv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.guowangkeji.top/Article/details/gt2brjhpoyx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gt2kuvomflp.html

[U46] PHP：可空类型
来源：http://dali.birdmap.top/Article/details/gt2vhnvgzdr.html

?string $name = null
来源：http://dali.daxiang520.top/Article/details/gt2tworpsjc.html

[U47] PHP：联合类型
来源：http://dali.yuanzhike.top/Article/details/gt2mdtlrkii.html

int|string $id
来源：http://dali.daria6918.cn/Article/details/gt2sggfmtmr.html

[U48] PHP：纯枚举
来源：http://dali.chenlongwang.top/Article/details/gt2oxwsdyoy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.bjfxy.top/Article/details/gt2yhlufwtr.html

[U49] PHP：只读属性
来源：http://dali.yongpay.top/Article/details/gt2jfawhhsh.html

public readonly string $name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kscgctzo.html

[U50] PHP：构造器属性提升
来源：http://dali.nanxuanxn.top/Article/details/gt2bpemipav.html

public function __construct(private int $id) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dsvbvevv.html

[U51] PHP：数组解构
来源：http://dali.gzhubu.top/Article/details/gt2hhqumkrx.html

[$a, $b] = $arr;
来源：http://dali.zhongyouzk.top/Article/details/gt2dwojplgo.html

[U52] PHP：箭头函数
来源：http://dali.fzhhl.top/Article/details/gt2zyyrdeon.html

$double = fn($x) => $x * 2;
来源：http://dali.xinyue.icu/Article/details/gt2pgvxuurq.html

[U53] PHP：空合并运算符
来源：http://dali.gotoacloud.top/Article/details/gt2wftrkonb.html

$v = $a ?? $b ?? "default";
来源：http://dali.nanxuanxn.top/Article/details/gt2pdccdepp.html

[U54] PHP：空安全调用
来源：http://dali.ydzc1.top/Article/details/gt2ehxrhmqw.html

$obj?->method()
来源：http://dali.aibaodan.cn/Article/details/gt2woibyztv.html

[U55] PHP：match 表达式
来源：http://dali.yangfankeji.com/Article/details/gt2ilaigwim.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gt2oxjbszkn.html

[U56] PHP：命名参数
来源：http://dali.xinyue.icu/Article/details/gt2wfworfns.html

f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gt2kldvtkso.html

[U57] PHP：字符串插值
来源：http://dali.ydzc1.top/Article/details/gt2ewjuwymg.html

"值: {$a}"
来源：http://dali.birdmap.top/Article/details/gt2ogfarzuv.html

[U58] PHP：数组三件套
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mdztlbao.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ppjwa.cn/Article/details/gt2ihkvmewo.html

[U59] PHP：自定义排序
来源：http://dali.xziqi.cn/Article/details/gt2tomkfnlf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sufxvd.cn/Article/details/gt2nhwciknf.html

[U60] PHP：JSON 编解码
来源：http://dali.shzxlz.cn/Article/details/gt2dywfolux.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2frpyeiso.html

[U61] PHP：正则
来源：http://dali.fzhhl.top/Article/details/gt2gvsuvwfy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2gduskjjs.html

[U62] PHP：日期对象
来源：http://dali.zycfv.cn/Article/details/gt2jnomsbxh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tanke756.top/Article/details/gt2jgfdofec.html

[U63] PHP：文件读写
来源：http://dali.yj202588.top/Article/details/gt2waobbmsx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.redwolf501.top/Article/details/gt2gcbjxhpe.html

[U64] PHP：目录遍历
来源：http://dali.hywenlv.cn/Article/details/gt2uvtwkytj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jqgufenzy.top/Article/details/gt2mubgsfur.html

[U65] PHP：会话
来源：http://dali.jiagoushi.top/Article/details/gt2vilmayti.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2tbkpeoky.html

[U66] PHP：设置 Cookie
来源：http://dali.cucudq.cn/Article/details/gt2keskwhli.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.tianlin.xyz/Article/details/gt2tdrgksdu.html

[U67] PHP：处理文件上传
来源：http://dali.birdmap.top/Article/details/gt2hrrjxmkm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.fzhhl.top/Article/details/gt2ncytrsfj.html

[U68] PHP：PDO 连接
来源：http://dali.chenlongwang.top/Article/details/gt2nltzemwx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hfpthk.cn/Article/details/gt2rkwcavka.html

[U69] PHP：PDO 预处理
来源：http://dali.yvedp.cn/Article/details/gt2iesloofz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.nanxinkj.top/Article/details/gt2hcaqrsgm.html

[U70] PHP：PDO 事务
来源：http://dali.pengpengdd.cyou/Article/details/gt2nroaatyk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.0kj1m.cn/Article/details/gt2swpgvsfd.html

[U71] PHP：抛出异常
来源：http://dali.fengsongda.top/Article/details/gt2wttbpgbm.html

throw new RuntimeException("失败", 500);
来源：http://dali.pycfn.com/Article/details/gt2gqwhgztq.html

[U72] PHP：写错误日志
来源：http://dali.jinqigufen.top/Article/details/gt2xyaqffxg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cheryme.top/Article/details/gt2yxueoqbb.html

[U73] PHP：读取 ini 配置
来源：http://dali.ivvv.top/Article/details/gt2pnfefjhn.html

parse_ini_file("config.ini", true)
来源：http://dali.gzhubu.top/Article/details/gt2vbxifagj.html

[U74] PHP：读取环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2atelzpoj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.nanxinkj.top/Article/details/gt2wxfowkwi.html

[U75] PHP：依赖注入
来源：http://dali.smart0.xyz/Article/details/gt2oxrixhiv.html

composer require psr/container
来源：http://dali.ivvv.top/Article/details/gt2pynrhrmr.html

[U76] PHP：简单路由
来源：http://dali.yuxming.cn/Article/details/gt2gkwehbgz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.sysykeji.top/Article/details/gt2hzeuebnu.html

[U77] PHP：模板渲染
来源：http://dali.9152youxi.cn/Article/details/gt2wyyzrzan.html

composer require twig/twig
来源：http://dali.sysykeji.top/Article/details/gt2nkbbudyt.html

[U78] PHP：单元测试
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2teunduyk.html

composer require --dev phpunit/phpunit
来源：http://dali.hammf.cn/Article/details/gt2vxpcfpxx.html

[U79] PHP：静态分析
来源：http://dali.yueranfly.top/Article/details/gt2qfnkupjg.html

composer require --dev phpstan/phpstan
来源：http://dali.andypj.xyz/Article/details/gt2gbgkxzrg.html

[U80] PHP：代码规范修复
来源：http://dali.hfpthk.cn/Article/details/gt2rhganxbc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.guannengcc.top/Article/details/gt2ndgcdzfc.html

[U81] JS：初始化项目
来源：http://dali.jinqigfzy.top/Article/details/gt2uxbmtmlc.html

npm init -y;  npm i express
来源：http://dali.zhoulong.xyz/Article/details/gt2kvlllzwi.html

[U82] JS：package.json 脚本
来源：http://dali.kuanghao11.cn/Article/details/gt2urejzjfx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tfzuwaya.html

[U83] JS：ES Module 导入导出
来源：http://dali.zdqjudy.top/Article/details/gt2oonpnjrm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gt2swyxfzur.html

[U84] JS：CommonJS 写法
来源：http://dali.yj20258.top/Article/details/gt2zhmieriy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yj20258.top/Article/details/gt2lwpqdtme.html

[U85] JS：可选链
来源：http://dali.pengpengdd.cyou/Article/details/gt2rnfvspou.html

a?.b?.c
来源：http://dali.hysaishi.cn/Article/details/gt2tujpfcyc.html

[U86] JS：空值合并
来源：http://dali.zhiwuduotai.top/Article/details/gt2bcqfzudb.html

a ?? b
来源：http://dali.cheryme.top/Article/details/gt2gclqjynm.html

[U87] JS：解构默认值
来源：http://dali.gogol.net.cn/Article/details/gt2xzxrakxj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jyoumei.cn/Article/details/gt2jvlsfpky.html

[U88] JS：对象展开合并
来源：http://dali.xziqi.cn/Article/details/gt2kziwtqzc.html

{ ...a, ...b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iqnczior.html

[U89] JS：数组去重
来源：http://dali.jqgfzy.top/Article/details/gt2cuhbehph.html

[...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gt2vkstkqrp.html

[U90] JS：数字数组排序
来源：http://dali.yj202588.top/Article/details/gt2hldwzyoo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gt2insqpoko.html

[U91] JS：对象键值遍历
来源：http://dali.ivvv.top/Article/details/gt2tmtxykzr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.redwolf501.top/Article/details/gt2mfahwncw.html

[U92] JS：深拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gt2hmasdfjr.html

structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gt2flhylwcp.html

[U93] JS：模板字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2bfcevapi.html

`共 ${n} 条`
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2enetwknh.html

[U94] JS：箭头函数
来源：http://dali.yonumen.top/Article/details/gt2gtckvuuq.html

const double = x => x * 2;
来源：http://dali.smart0.xyz/Article/details/gt2ncbtsnzi.html

[U95] JS：Promise 包装
来源：http://dali.meibo888.top/Article/details/gt2icrdvjyb.html

new Promise((resolve, reject) => {})
来源：http://dali.zdqjudy.top/Article/details/gt2glbdwmpw.html

[U96] JS：async/await 与异常
来源：http://dali.snrcjt.cn/Article/details/gt2pscyosaq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gt2epufqfio.html

[U97] JS：并发请求
来源：http://dali.shuidangran.top/Article/details/gt2keuuuxww.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gt2vkcqafzv.html

[U98] JS：fetch 带 JSON
来源：http://dali.xinyue.icu/Article/details/gt2vhxermov.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2wzquggrd.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2wceezbhd.html

el.addEventListener("click", e => {})
来源：http://dali.chenjidiqi.icu/Article/details/gt2ynyefepc.html

[U100] JS：DOM 查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2qraenemv.html

document.querySelector(".item")
来源：http://dali.xinyue.icu/Article/details/gt2ergzfhwo.html

[U101] JS：classList 操作
来源：http://dali.iojbl.cn/Article/details/gt2ffowcuhu.html

el.classList.toggle("active")
来源：http://dali.fzhhl.top/Article/details/gt2kqelqgtw.html

[U102] JS：本地存储
来源：http://dali.vqdsnc.cn/Article/details/gt2hwvlhmnq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jyoumei.cn/Article/details/gt2medtuhyf.html

[U103] JS：定时器
来源：http://dali.ydzc1.top/Article/details/gt2cqavdhtb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yanxiufei.cn/Article/details/gt2qbvfjves.html

[U104] JS：防抖
来源：http://dali.nwbrower.top/Article/details/gt2yjvrpddd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2dnmsvrro.html

[U105] JS：节流
来源：http://dali.zhixingplan.top/Article/details/gt2gtjrbrhs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhiwuduotai.top/Article/details/gt2eacsxrly.html

[U106] JS：日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gt2txfafopd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdkeyzqt.html

[U107] JS：数字千分位
来源：http://dali.pengpengdd.cyou/Article/details/gt2ptbehuah.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.bjfxy.top/Article/details/gt2osqqaijs.html

[U108] JS：随机整数
来源：http://dali.meibo888.top/Article/details/gt2xfasawxi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gzhubu.top/Article/details/gt2lfbudfhg.html

[U109] JS：数组分组
来源：http://dali.iojbl.cn/Article/details/gt2hvyjjsmr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.iojbl.cn/Article/details/gt2tafakpjd.html

[U110] JS：数组分块
来源：http://dali.tanke756.top/Article/details/gt2gsrtuqai.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.quarkkingdee.top/Article/details/gt2bpuhitdt.html

[U111] JS：对象转 Map
来源：http://dali.xinyue.icu/Article/details/gt2aasbhhmx.html

new Map(Object.entries(obj))
来源：http://dali.nanxuanxn.top/Article/details/gt2ycmbwuks.html

[U112] JS：字符串补位
来源：http://dali.chenlongwang.top/Article/details/gt2nvtqpcdt.html

"7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vqxochhi.html

[U113] JS：正则替换全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2szshgbdg.html

s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2yoxtdmen.html

[U114] JS：JSON 深比较
来源：http://dali.fzhhl.top/Article/details/gt2pyfpipof.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gt2dnqnpgty.html

[U115] JS：生成 UUID
来源：http://dali.cdnleiting.top/Article/details/gt2mtimmajw.html

crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gt2hnzozhyt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinqigufen.top/Article/details/gt2yvfowcbo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tanke756.top/Article/details/gt2juzkwkwz.html

[U117] JS：单元测试
来源：http://dali.jqgfzy.top/Article/details/gt2uxmzdjhk.html

npm i -D vitest;  npx vitest
来源：http://dali.feifeiyinyue.top/Article/details/gt2aoyqfzxk.html

[U118] JS：开发服务器
来源：http://dali.hnqzz.top/Article/details/gt2vxqgeoan.html

npm i -D vite;  npx vite
来源：http://dali.shuidangran.top/Article/details/gt2vrfttrsa.html

[U119] JS：生产构建
来源：http://dali.xinyue.icu/Article/details/gt2kvchohxv.html

npx vite build
来源：http://dali.guannengcc.top/Article/details/gt2nmhghctp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ahjcrabk.html

import.meta.env.VITE_API_URL
来源：http://dali.mhx1999.top/Article/details/gt2otsveudt.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2nziupjvv.html

统计汇总
来源：http://dali.pengpengdd.cyou/Article/details/gt2vajrpblc.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2uivquwal.html

按语言统计（条）：
来源：http://dali.yuanzhike.top/Article/details/gt2yshnisra.html

Python ......... 252
来源：http://dali.havefunace.top/Article/details/gt2qhunkswe.html

PHP ............ 252
来源：http://dali.pengpengdd.cyou/Article/details/gt2wzowhwwd.html

JavaScript ..... 252
来源：http://dali.dashuyun.cn/Article/details/gt2urkdpjtf.html

TypeScript ..... 212
来源：http://dali.cdnleiting.top/Article/details/gt2xelnzcou.html

Java ........... 212
来源：http://dali.ppjwa.cn/Article/details/gt2lgbdbiml.html

Go ............. 212
来源：http://dali.aibaodan.cn/Article/details/gt2vqfsfwqz.html

Ruby ........... 212
来源：http://dali.mhx1999.top/Article/details/gt2dvvuaeuq.html

C# ............. 212
来源：http://dali.quarkkingdee.top/Article/details/gt2uhnxfiws.html

C .............. 30
来源：http://dali.ppjwa.cn/Article/details/gt2ygtdgqtv.html

C++ ............ 30
来源：http://dali.guowangkeji.top/Article/details/gt2dkxsivfb.html

SQL ............ 90
来源：http://dali.yueranfly.top/Article/details/gt2auwimoqe.html

Bash ........... 80
来源：http://dali.ybcxt.top/Article/details/gt2oigyunzy.html

Kotlin ......... 15
来源：http://dali.andypj.xyz/Article/details/gt2bzrgobxh.html

Swift .......... 15
来源：http://dali.cdnleiting.top/Article/details/gt2tzvctbbx.html

Lua ............ 10
来源：http://dali.jinqigufen.top/Article/details/gt2faetrbjv.html

Perl ........... 10
来源：http://dali.meibo888.top/Article/details/gt2hbtbmwgw.html

Scala .......... 10
来源：http://dali.cashguo.top/Article/details/gt2glycwfys.html

------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gt2ndcxdblf.html

合计 ........... 2106 条
来源：http://dali.xylfe.cn/Article/details/gt2dmyssbaw.html

按章节统计：
来源：http://dali.haohaochexian.top/Article/details/gt2nuidsdau.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xglhlrlm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.bjfxy.top/Article/details/gt2fgrrsovm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gt2asolzizh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yj20258.top/Article/details/gt2hmpguoxd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2jmktxtdm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.chenzaomai.com/Article/details/gt2qjwjuinc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigfzy.top/Article/details/gt2coggaxkz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxnrxev.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gt2tsfcvkmj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gt2xefoxvmp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gt2ihqhoeqf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gt2ikvkwhjo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gt2eeyztlig.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lgifuogp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.nwbrower.top/Article/details/gt2qhfkdtog.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gt2dgfaqdwr.html

Q SQL 专题                              90
来源：http://dali.cqqwz.cn/Article/details/gt2jgbfuvbs.html

R Bash 专题                             80
来源：http://dali.andypj.xyz/Article/details/gt2laerneyv.html

S C / C++ 专题                          60
来源：http://dali.dashuyun.cn/Article/details/gt2ysunmqic.html

T 其他语言补充                          60
来源：http://dali.yuanzhike.top/Article/details/gt2ciqzmgwt.html

U 高频实用片段                         120
来源：http://dali.quarkkingdee.top/Article/details/gt2odoqosjq.html

------------------------------------
来源：http://dali.xylfe.cn/Article/details/gt2fllinmis.html

合计                                  2106 条
来源：http://dali.zhixingplan.top/Article/details/gt2udxzrhun.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gt2jsflzkmc.html

使用提醒
来源：http://dali.hfpthk.cn/Article/details/gt2ndzcbkxo.html

--------------------------------------------------------------------------------
来源：http://dali.cashguo.top/Article/details/gt2urmvtufq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hnqzz.top/Article/details/gt2lntyibkn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinqigfzy.top/Article/details/gt2acoexwdr.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yvedp.cn/Article/details/gt2qlxftepp.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jinqigfzy.top/Article/details/gt2khpjrxml.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.guowangkeji.top/Article/details/gt2nmqemwwr.html

—— 文件结束 ——
来源：http://dali.aizwys.cn/Article/details/gt2jksuyvbp.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2hoaqqfxa.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.guannengcc.top/Article/details/gt2ykgiiwse.html

Common Programming Examples Cheat Book
来源：http://dali.0kj1m.cn/Article/details/gt2rpzwkgro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rfygcyyt.html

【收录内容】
来源：http://dali.yj20258888.top/Article/details/gt2awacebib.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.aizwys.cn/Article/details/gt2krmizkhl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yj202588.top/Article/details/gt2eorjunsc.html

SQL · Bash · C · C++
来源：http://dali.aibaodan.cn/Article/details/gt2gmwmotsh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.pengpengdd.cyou/Article/details/gt2zyeznbch.html

【使用说明】
来源：http://dali.hnqzz.top/Article/details/gt2snefafie.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhixingplan.top/Article/details/gt2juhotzjn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xinyue.icu/Article/details/gt2nmqsvefx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2obdyrsos.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yueranfly.top/Article/details/gt2jhuoeozu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xuetiantiany.cn/Article/details/gt2ekhpbqqt.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shzxlz.cn/Article/details/gt2tmoesmav.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.shuidangran.top/Article/details/gt2rtilrvcv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.iojbl.cn/Article/details/gt2jglteugj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cheryme.top/Article/details/gt2mkpvoqhq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.vqdsnc.cn/Article/details/gt2dtkdljtg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xylfe.cn/Article/details/gt2mgyrplez.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cucudq.cn/Article/details/gt2eitdzisl.html

【文件统计】
来源：http://dali.haohaochexian.top/Article/details/gt2xdtnmdrc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uegoapks.html

--------------------------------------------------------------------------------
来源：http://dali.cucudq.cn/Article/details/gt2iglkyrdl.html

目  录
来源：http://dali.havefunace.top/Article/details/gt2ijcmkhoi.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gt2gbjkpwxl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.aibaodan.cn/Article/details/gt2oimbtvbf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cashguo.top/Article/details/gt2kwvykpqi.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.iojbl.cn/Article/details/gt2ekuqawdn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.birdmap.top/Article/details/gt2cicmznvx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2bfcmmsmc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jiagoushi.top/Article/details/gt2scncuwaz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.sxryk.cn/Article/details/gt2tzrpwnab.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ppjwa.cn/Article/details/gt2ezyrfprr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gt2aydfovvz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bgqpvehy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2hjmxsbtm.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gt2ywdeolkj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfgkbtd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xuanzx.com/Article/details/gt2bdxtwvcv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zdqjudy.top/Article/details/gt2xtxrhmzg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gt2cywzzcuk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.wangdashe.top/Article/details/gt2nbqdcppw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2skoexyvu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.fzhhl.top/Article/details/gt2pssqacnl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zdqjudy.top/Article/details/gt2saxfnnbl.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.nwbrower.top/Article/details/gt2vtfsdixq.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2olsdhisi.html

A. 基础语法与类型
来源：http://dali.jqgfzy.top/Article/details/gt2wvfulfwn.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2oycxykbv.html

[A01] Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2unqombdr.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfuprin.html

PHP:  echo "Hello, World!";
来源：http://dali.kuanghao11.cn/Article/details/gt2gkunnlkc.html

JS:   console.log("Hello, World!");
来源：http://dali.nanxinkj.top/Article/details/gt2hsioyhus.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.wangdashe.top/Article/details/gt2tjvnlice.html

Java: System.out.println("Hello, World!");
来源：http://dali.ppjwa.cn/Article/details/gt2jpurcnoa.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qiswqbca.html

Ruby: puts "Hello, World!"
来源：http://dali.andypj.xyz/Article/details/gt2osuqwkbx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xuanzx.com/Article/details/gt2cxerwgob.html

[A02] 变量声明与赋值
来源：http://dali.yj202588.top/Article/details/gt2xqmensyp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ybcxt.top/Article/details/gt2oleixuvi.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.chenzaomai.com/Article/details/gt2ynkytrsp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.nwbrower.top/Article/details/gt2fwnecfqs.html


<!-- 参考信息 -->