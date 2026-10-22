代发 wailian999

[U29] Py：属性校验
来源：http://dali.gotoacloud.top/Article/details/gt2yqfgzaos.html

@property 与 @x.setter 配合
来源：http://dali.sweek.top/Article/details/gt2tfuhuguy.html

[U30] Py：数据类
来源：http://dali.yuxming.cn/Article/details/gt2edezvvfu.html

@dataclass(slots=True)
来源：http://dali.shzxlz.cn/Article/details/gt2ldryaebw.html

[U31] Py：单测
来源：http://dali.zhongyouzk.top/Article/details/gt2gyszmjnw.html

python -m pytest -q
来源：http://dali.meibo888.top/Article/details/gt2doosefjq.html

[U32] Py：代码格式化
来源：http://dali.fengsongda.top/Article/details/gt2qgtwquup.html

ruff format . && ruff check --fix .
来源：http://dali.haohaochexian.top/Article/details/gt2lgsioflp.html

[U33] Py：打包发布
来源：http://dali.zycfv.cn/Article/details/gt2nsroxana.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxzcnvev.html

[U34] Py：判断编码
来源：http://dali.sweek.top/Article/details/gt2cnfspmnk.html

chardet.detect(raw)
来源：http://dali.ppjwa.cn/Article/details/gt2wzxwjlkc.html

[U35] Py：发送邮件
来源：http://dali.jlsjyb.cn/Article/details/gt2odlgrvlw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj20258888.top/Article/details/gt2mivfoapv.html

[U36] Py：定时任务
来源：http://dali.fzhhl.top/Article/details/gt2mduldryh.html

schedule.every(10).minutes.do(job)
来源：http://dali.tianlin.xyz/Article/details/gt2zqbfcuey.html

[U37] Py：读写 Excel
来源：http://dali.vqdsnc.cn/Article/details/gt2lfitfqoc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinqigfzy.top/Article/details/gt2ewoofoxf.html

[U38] Py：获取脚本所在目录
来源：http://dali.tian-w.cn/Article/details/gt2boplkuzj.html

Path(__file__).resolve().parent
来源：http://dali.hammf.cn/Article/details/gt2bvmpzjqm.html

[U39] Py：判断是否在交互环境
来源：http://dali.nanxinkj.top/Article/details/gt2tbopnrqo.html

sys.stdout.isatty()
来源：http://dali.yuanzhike.top/Article/details/gt2irqbnrsd.html

[U40] Py：打印到标准错误
来源：http://dali.daria6918.cn/Article/details/gt2bxdlypav.html

print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gt2yrwlbbrb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.kuanghao11.cn/Article/details/gt2sjzgpuqx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yuxming.cn/Article/details/gt2frhuuyvb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.aizwys.cn/Article/details/gt2jchqnbce.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cqqwz.cn/Article/details/gt2wuzvkqvi.html

[U43] PHP：声明命名空间
来源：http://dali.iojbl.cn/Article/details/gt2mnbxljsn.html

namespace App\Http;
来源：http://dali.xylfe.cn/Article/details/gt2qfswwrxo.html

[U44] PHP：开启严格类型
来源：http://dali.sufxvd.cn/Article/details/gt2bvktyghh.html

declare(strict_types=1);
来源：http://dali.yj20258888.top/Article/details/gt2gvnlksba.html

[U45] PHP：类型声明与返回类型
来源：http://dali.sxryk.cn/Article/details/gt2nrjdzuxx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gt2ielzwaan.html

[U46] PHP：可空类型
来源：http://dali.hnxiangtu.top/Article/details/gt2meeswzuo.html

?string $name = null
来源：http://dali.hnxiangtu.top/Article/details/gt2rdnvnesk.html

[U47] PHP：联合类型
来源：http://dali.wangdashe.top/Article/details/gt2qwkfhcka.html

int|string $id
来源：http://dali.zdqjudy.top/Article/details/gt2gxzqhxzy.html

[U48] PHP：纯枚举
来源：http://dali.andypj.xyz/Article/details/gt2gltiqone.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yj202588.top/Article/details/gt2autdlnwg.html

[U49] PHP：只读属性
来源：http://dali.wangshuangyany.cn/Article/details/gt2pfkyuwiz.html

public readonly string $name
来源：http://dali.daria6918.cn/Article/details/gt2knrbpxfs.html

[U50] PHP：构造器属性提升
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xppupkvj.html

public function __construct(private int $id) {}
来源：http://dali.316326.xyz/Article/details/gt2sjtppxly.html

[U51] PHP：数组解构
来源：http://dali.meibo888.top/Article/details/gt2miuvpkbw.html

[$a, $b] = $arr;
来源：http://dali.smart0.xyz/Article/details/gt2trdghvjb.html

[U52] PHP：箭头函数
来源：http://dali.zhengqikj.top/Article/details/gt2nqxpdgvl.html

$double = fn($x) => $x * 2;
来源：http://dali.jianghu66.top/Article/details/gt2ucruofgo.html

[U53] PHP：空合并运算符
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lejooobf.html

$v = $a ?? $b ?? "default";
来源：http://dali.mhx1999.top/Article/details/gt2pbzofvsm.html

[U54] PHP：空安全调用
来源：http://dali.fengsongda.top/Article/details/gt2juhzazvi.html

$obj?->method()
来源：http://dali.smart0.xyz/Article/details/gt2mvszlfot.html

[U55] PHP：match 表达式
来源：http://dali.ehwqpu.com/Article/details/gt2wcktcbmg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yongpay.top/Article/details/gt2olfbauis.html

[U56] PHP：命名参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwmpqkbn.html

f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kuucwucb.html

[U57] PHP：字符串插值
来源：http://dali.yj20258.top/Article/details/gt2tuivkjrp.html

"值: {$a}"
来源：http://dali.hammf.cn/Article/details/gt2oncqvngx.html

[U58] PHP：数组三件套
来源：http://dali.tanke756.top/Article/details/gt2gplhjkuy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zlskpgtt.html

[U59] PHP：自定义排序
来源：http://dali.ivvv.top/Article/details/gt2zjibavuw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xcfoavpo.html

[U60] PHP：JSON 编解码
来源：http://dali.zycfv.cn/Article/details/gt2avwgzccb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2moiaieze.html

[U61] PHP：正则
来源：http://dali.yuanzhike.top/Article/details/gt2edwbqrjd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yueranfly.top/Article/details/gt2lvcxtzts.html

[U62] PHP：日期对象
来源：http://dali.jiagoushi.top/Article/details/gt2rsxihicg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xuanzx.com/Article/details/gt2qyzipqnn.html

[U63] PHP：文件读写
来源：http://dali.zhongyouzk.top/Article/details/gt2ccsjdmgt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zdqjudy.top/Article/details/gt2syfbjnmj.html

[U64] PHP：目录遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2hummoakd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jqgfzy.top/Article/details/gt2ackoepjo.html

[U65] PHP：会话
来源：http://dali.yj20258.top/Article/details/gt2imkibygs.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shuidangran.top/Article/details/gt2jyroqezs.html

[U66] PHP：设置 Cookie
来源：http://dali.shuidangran.top/Article/details/gt2zhcqxvfz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zalmgioy.html

[U67] PHP：处理文件上传
来源：http://dali.yangfankeji.com/Article/details/gt2ozinhkzr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.nanxinkj.top/Article/details/gt2dqblvsdc.html

[U68] PHP：PDO 连接
来源：http://dali.zhongyouzk.top/Article/details/gt2uexyhvfv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.316326.xyz/Article/details/gt2uzyflbly.html

[U69] PHP：PDO 预处理
来源：http://dali.meibo888.top/Article/details/gt2bgaojeeq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.c1oappe.top/Article/details/gt2ohzfwhzg.html

[U70] PHP：PDO 事务
来源：http://dali.yj202588.top/Article/details/gt2tylzujqf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.shuidangran.top/Article/details/gt2wigwfruv.html

[U71] PHP：抛出异常
来源：http://dali.zhengqikj.top/Article/details/gt2ebsuxjed.html

throw new RuntimeException("失败", 500);
来源：http://dali.guannengcc.top/Article/details/gt2vntxdylk.html

[U72] PHP：写错误日志
来源：http://dali.birdmap.top/Article/details/gt2gumaebnp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jlsjyb.cn/Article/details/gt2crahtjqd.html

[U73] PHP：读取 ini 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svnnvjhr.html

parse_ini_file("config.ini", true)
来源：http://dali.ehwqpu.com/Article/details/gt2rfalrkwp.html

[U74] PHP：读取环境变量
来源：http://dali.ivvv.top/Article/details/gt2gyqevefb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xuetiantiany.cn/Article/details/gt2rleykmoj.html

[U75] PHP：依赖注入
来源：http://dali.zdqjudy.top/Article/details/gt2etfhsaey.html

composer require psr/container
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2muiwdqdj.html

[U76] PHP：简单路由
来源：http://dali.shuidangran.top/Article/details/gt2mssdtkup.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yongpay.top/Article/details/gt2ahqynuna.html

[U77] PHP：模板渲染
来源：http://dali.xinyue.icu/Article/details/gt2fvclcjwu.html

composer require twig/twig
来源：http://dali.nwbrower.top/Article/details/gt2gaxzkujm.html

[U78] PHP：单元测试
来源：http://dali.yuxming.cn/Article/details/gt2tttufrly.html

composer require --dev phpunit/phpunit
来源：http://dali.aizwys.cn/Article/details/gt2wfccfuww.html

[U79] PHP：静态分析
来源：http://dali.cashguo.top/Article/details/gt2yxiigcyy.html

composer require --dev phpstan/phpstan
来源：http://dali.yuanzhike.top/Article/details/gt2hpalvorg.html

[U80] PHP：代码规范修复
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yvyprghy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tdpsklvi.html

[U81] JS：初始化项目
来源：http://dali.c1oappe.top/Article/details/gt2lwjqvjyf.html

npm init -y;  npm i express
来源：http://dali.jiagoushi.top/Article/details/gt2lhzzjoix.html

[U82] JS：package.json 脚本
来源：http://dali.xinyue.icu/Article/details/gt2nwtidvtt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hywenlv.cn/Article/details/gt2vltqbsgb.html

[U83] JS：ES Module 导入导出
来源：http://dali.xuanzx.com/Article/details/gt2qqpwaadh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.andypj.xyz/Article/details/gt2mkdxjgai.html

[U84] JS：CommonJS 写法
来源：http://dali.jinqigufen.top/Article/details/gt2nfsbbled.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.snrcjt.cn/Article/details/gt2jlmrwfad.html

[U85] JS：可选链
来源：http://dali.xuanzx.com/Article/details/gt2evbmtbht.html

a?.b?.c
来源：http://dali.iojbl.cn/Article/details/gt2ikraxyrt.html

[U86] JS：空值合并
来源：http://dali.sweek.top/Article/details/gt2cylnyzwz.html

a ?? b
来源：http://dali.yj202588.top/Article/details/gt2xehqgwep.html

[U87] JS：解构默认值
来源：http://dali.zhixingplan.top/Article/details/gt2nzsvkniy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hysaishi.cn/Article/details/gt2vsxggakd.html

[U88] JS：对象展开合并
来源：http://dali.jinqigfzy.top/Article/details/gt2lkmrnwve.html

{ ...a, ...b }
来源：http://dali.hysaishi.cn/Article/details/gt2diajlogx.html

[U89] JS：数组去重
来源：http://dali.dianchejie.cn/Article/details/gt2wrdvmfbq.html

[...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gt2ycwbviym.html

[U90] JS：数字数组排序
来源：http://dali.svipenyu.cn/Article/details/gt2gjitpkds.html

[...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gt2ergbjmej.html

[U91] JS：对象键值遍历
来源：http://dali.nwbrower.top/Article/details/gt2gvdqmvje.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jqgfzy.top/Article/details/gt2miowwzdx.html

[U92] JS：深拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gt2qqbylsek.html

structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2sseltbsz.html

[U93] JS：模板字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2lqtwgazn.html

`共 ${n} 条`
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gjmwpwzs.html

[U94] JS：箭头函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fuwlzllz.html

const double = x => x * 2;
来源：http://dali.gaohongyu789.top/Article/details/gt2tmjfsgnt.html

[U95] JS：Promise 包装
来源：http://dali.cheryme.top/Article/details/gt2daknljiq.html

new Promise((resolve, reject) => {})
来源：http://dali.zhongyouzk.top/Article/details/gt2hkzyzbux.html

[U96] JS：async/await 与异常
来源：http://dali.0kj1m.cn/Article/details/gt2bplwhmul.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gt2bbdkzgmn.html

[U97] JS：并发请求
来源：http://dali.hnqzz.top/Article/details/gt2bitkxkbf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gt2zxftrrvl.html

[U98] JS：fetch 带 JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gt2muickmpz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gotoacloud.top/Article/details/gt2xqylnglu.html

[U99] JS：事件监听
来源：http://dali.gogol.net.cn/Article/details/gt2kwrtvwvk.html

el.addEventListener("click", e => {})
来源：http://dali.xziqi.cn/Article/details/gt2onrmkujh.html

[U100] JS：DOM 查询
来源：http://dali.guowangkeji.top/Article/details/gt2xclxlvuc.html

document.querySelector(".item")
来源：http://dali.aizwys.cn/Article/details/gt2ogtzktlb.html

[U101] JS：classList 操作
来源：http://dali.xuetiantiany.cn/Article/details/gt2eeemlujr.html

el.classList.toggle("active")
来源：http://dali.zhongyouzk.top/Article/details/gt2ometwisd.html

[U102] JS：本地存储
来源：http://dali.smart0.xyz/Article/details/gt2ibywaawi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.gaohongyu789.top/Article/details/gt2lqfxyizf.html

[U103] JS：定时器
来源：http://dali.svipenyu.cn/Article/details/gt2pjxjtdqx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gzhubu.top/Article/details/gt2hlqrjksk.html

[U104] JS：防抖
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lafirrye.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gt2rlupmipa.html

[U105] JS：节流
来源：http://dali.hongshengwenyu.top/Article/details/gt2yojkgxgl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zdqjudy.top/Article/details/gt2zofnbamz.html

[U106] JS：日期格式化
来源：http://dali.ydzc1.top/Article/details/gt2pakrjcun.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sweek.top/Article/details/gt2paojbqdd.html

[U107] JS：数字千分位
来源：http://dali.yvedp.cn/Article/details/gt2eixptdxa.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zycfv.cn/Article/details/gt2fbfifvrg.html

[U108] JS：随机整数
来源：http://dali.haohaochexian.top/Article/details/gt2lszusrvf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhoulong.xyz/Article/details/gt2pbjbaifc.html

[U109] JS：数组分组
来源：http://dali.jqgufenzy.top/Article/details/gt2yodbrdfa.html

Object.groupBy(arr, x => x.type)
来源：http://dali.aibaodan.cn/Article/details/gt2rdwkeuas.html

[U110] JS：数组分块
来源：http://dali.jinghuilouyu.cn/Article/details/gt2acinbezy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mqfswyqg.html

[U111] JS：对象转 Map
来源：http://dali.iojbl.cn/Article/details/gt2hpmmqbjk.html

new Map(Object.entries(obj))
来源：http://dali.smart0.xyz/Article/details/gt2mpxdeovh.html

[U112] JS：字符串补位
来源：http://dali.zycfv.cn/Article/details/gt2suukcsep.html

"7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gt2hnhviqaq.html

[U113] JS：正则替换全部
来源：http://dali.guannengcc.top/Article/details/gt2bordskak.html

s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aqxagrlz.html

[U114] JS：JSON 深比较
来源：http://dali.316326.xyz/Article/details/gt2uvdlanos.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gt2ncxygztn.html

[U115] JS：生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gt2mmbvskpw.html

crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gt2phdwltth.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cqqwz.cn/Article/details/gt2sptudefj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2kvtbemiq.html

[U117] JS：单元测试
来源：http://dali.mhx1999.top/Article/details/gt2dwtalfdg.html

npm i -D vitest;  npx vitest
来源：http://dali.vqdsnc.cn/Article/details/gt2mayvnbry.html

[U118] JS：开发服务器
来源：http://dali.gogol.net.cn/Article/details/gt2jsegmptt.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkvmrlc.html

[U119] JS：生产构建
来源：http://dali.aibaodan.cn/Article/details/gt2grikyqts.html

npx vite build
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kmrvnfjp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shzxlz.cn/Article/details/gt2jtnvfpvj.html

import.meta.env.VITE_API_URL
来源：http://dali.feifeiyinyue.top/Article/details/gt2qdlydvsn.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2daujugjq.html

统计汇总
来源：http://dali.nwbrower.top/Article/details/gt2usfdchgb.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hlyaxudm.html

按语言统计（条）：
来源：http://dali.feifeiyinyue.top/Article/details/gt2exnjnpih.html

Python ......... 252
来源：http://dali.yueranfly.top/Article/details/gt2fijdsitq.html

PHP ............ 252
来源：http://dali.xinyue.icu/Article/details/gt2ytrtxuqu.html

JavaScript ..... 252
来源：http://dali.ybcxt.top/Article/details/gt2ejqpwviq.html

TypeScript ..... 212
来源：http://dali.birdmap.top/Article/details/gt2qwzffuwy.html

Java ........... 212
来源：http://dali.mhx1999.top/Article/details/gt2mrhivoju.html

Go ............. 212
来源：http://dali.guowangkeji.top/Article/details/gt2evcquebd.html

Ruby ........... 212
来源：http://dali.svipenyu.cn/Article/details/gt2splppzqc.html

C# ............. 212
来源：http://dali.sufxvd.cn/Article/details/gt2vztjholc.html

C .............. 30
来源：http://dali.birdmap.top/Article/details/gt2noytpfpk.html

C++ ............ 30
来源：http://dali.gaohongyu789.top/Article/details/gt2pzkxnfnw.html

SQL ............ 90
来源：http://dali.quarkkingdee.top/Article/details/gt2vkldvikv.html

Bash ........... 80
来源：http://dali.ybcxt.top/Article/details/gt2zayvulmf.html

Kotlin ......... 15
来源：http://dali.snrcjt.cn/Article/details/gt2nmssvewr.html

Swift .......... 15
来源：http://dali.xuanzx.com/Article/details/gt2etnivcgy.html

Lua ............ 10
来源：http://dali.yueranfly.top/Article/details/gt2fnanrulv.html

Perl ........... 10
来源：http://dali.sxryk.cn/Article/details/gt2qedjiskl.html

Scala .......... 10
来源：http://dali.xuetiantiany.cn/Article/details/gt2okzvxbha.html

------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gt2fppootqd.html

合计 ........... 2106 条
来源：http://dali.yuanzhike.top/Article/details/gt2qosyipyz.html

按章节统计：
来源：http://dali.hongshengwenyu.top/Article/details/gt2orrisugp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sweek.top/Article/details/gt2shmwtzlv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.daria6918.cn/Article/details/gt2iltefepj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cdnleiting.top/Article/details/gt2hjcgffjh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.iojbl.cn/Article/details/gt2injweohd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.guowangkeji.top/Article/details/gt2scwteacl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yueranfly.top/Article/details/gt2nrlvnmjp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gt2qdkuubfo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yongpay.top/Article/details/gt2ykmoxsmn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kixsfsnw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.nanxuanxn.top/Article/details/gt2eunaxhkt.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gt2kqtbocwm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gt2zaggnlnm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gt2tcuxsvfu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.pycfn.com/Article/details/gt2puehrrks.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yueranfly.top/Article/details/gt2onankece.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gt2segedzhz.html

Q SQL 专题                              90
来源：http://dali.cashguo.top/Article/details/gt2czikvhqq.html

R Bash 专题                             80
来源：http://dali.sxryk.cn/Article/details/gt2aghxaylo.html

S C / C++ 专题                          60
来源：http://dali.316326.xyz/Article/details/gt2xnfhtfht.html

T 其他语言补充                          60
来源：http://dali.jlsjyb.cn/Article/details/gt2gwaretbj.html

U 高频实用片段                         120
来源：http://dali.andypj.xyz/Article/details/gt2ldgmdrvs.html

------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gt2tcpciqci.html

合计                                  2106 条
来源：http://dali.c1oappe.top/Article/details/gt2fhgiqape.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gt2qkfgwrdq.html

使用提醒
来源：http://dali.316326.xyz/Article/details/gt2gwaspgxj.html

--------------------------------------------------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gt2leipylvm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.tanke756.top/Article/details/gt2zbrmlvcd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gaohongyu789.top/Article/details/gt2wbvaeqez.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vommmeva.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.iojbl.cn/Article/details/gt2kfbcgimr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jianghu66.top/Article/details/gt2lxyojttw.html

—— 文件结束 ——
来源：http://dali.haohaochexian.top/Article/details/gt2neaeoexz.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2voehgkig.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cdpwdqaf.html

Common Programming Examples Cheat Book
来源：http://dali.sufxvd.cn/Article/details/gt2snttmrdk.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vetzwlps.html

【收录内容】
来源：http://dali.yuxming.cn/Article/details/gt2eewwfgul.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.meibo888.top/Article/details/gt2vqsippir.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.tianlin.xyz/Article/details/gt2ptkkljlz.html

SQL · Bash · C · C++
来源：http://dali.vqdsnc.cn/Article/details/gt2cgupmhiw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yuxming.cn/Article/details/gt2scuowlvo.html

【使用说明】
来源：http://dali.aizwys.cn/Article/details/gt2cohqkiyv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.gogol.net.cn/Article/details/gt2qpvbubii.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xinyue.icu/Article/details/gt2oonuhwrr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.birdmap.top/Article/details/gt2tcekuvgj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.pengpengdd.cyou/Article/details/gt2gkglxeij.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.0kj1m.cn/Article/details/gt2vxoxcaea.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cdnleiting.top/Article/details/gt2fdkvxuuz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.chenzaomai.com/Article/details/gt2cfawaema.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hammf.cn/Article/details/gt2mtiskkmg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhongyouzk.top/Article/details/gt2lhneouzk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.quarkkingdee.top/Article/details/gt2lydiljdg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.c1oappe.top/Article/details/gt2ohvnueri.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xziqi.cn/Article/details/gt2jlxrgvbg.html

【文件统计】
来源：http://dali.0kj1m.cn/Article/details/gt2patoyjsn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jyoumei.cn/Article/details/gt2xfegokiw.html

--------------------------------------------------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlojrmud.html

目  录
来源：http://dali.yvedp.cn/Article/details/gt2ogirzmme.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gt2zrecnlts.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2uqnwcdam.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shzxlz.cn/Article/details/gt2wlaatbbc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gt2wmlibyry.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2jpbqtjsl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hnqzz.top/Article/details/gt2sllshrlg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.svipenyu.cn/Article/details/gt2omjdlygq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.iojbl.cn/Article/details/gt2bdjtlkwh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.dashuyun.cn/Article/details/gt2qyccvlut.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gt2xltesxnl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2dnzhlfrf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gt2hfznnbuf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gt2lglcxshm.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gt2ydqruilt.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.chenzaomai.com/Article/details/gt2zscaulco.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2uadrsfoe.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gt2kbquelld.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.tianlin.xyz/Article/details/gt2fhkeloes.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2nucbzrbv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2vewaoagj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yanxiufei.cn/Article/details/gt2rafaymiy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.havefunace.top/Article/details/gt2huqgqojt.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2aviupekc.html

A. 基础语法与类型
来源：http://dali.yuxming.cn/Article/details/gt2wnunxbhr.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2kljbomhv.html

[A01] Hello World
来源：http://dali.wangdashe.top/Article/details/gt2cidqhtvf.html

Py:   print("Hello, World!")
来源：http://dali.ehwqpu.com/Article/details/gt2idxajsxf.html

PHP:  echo "Hello, World!";
来源：http://dali.sweek.top/Article/details/gt2pdwxnjkn.html

JS:   console.log("Hello, World!");
来源：http://dali.fengsongda.top/Article/details/gt2rxvartel.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yj20258.top/Article/details/gt2hcajxker.html

Java: System.out.println("Hello, World!");
来源：http://dali.mhx1999.top/Article/details/gt2vdcxprdk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.aibaodan.cn/Article/details/gt2bhablbur.html

Ruby: puts "Hello, World!"
来源：http://dali.yvedp.cn/Article/details/gt2plqqphnl.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.vqdsnc.cn/Article/details/gt2mkhtbvmc.html


<!-- 参考信息 -->