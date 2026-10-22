代发 wailian999

[U31] Py：单测
来源：http://dali.ehwqpu.com/Article/details/gt2xfxambiv.html

python -m pytest -q
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2caohbuxf.html

[U32] Py：代码格式化
来源：http://dali.pengpengdd.cyou/Article/details/gt2cdidxhhd.html

ruff format . && ruff check --fix .
来源：http://dali.chenjidiqi.icu/Article/details/gt2couibfld.html

[U33] Py：打包发布
来源：http://dali.hysaishi.cn/Article/details/gt2njasrgmt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gzhubu.top/Article/details/gt2kqpmlmmz.html

[U34] Py：判断编码
来源：http://dali.tian-w.cn/Article/details/gt2tybsikvt.html

chardet.detect(raw)
来源：http://dali.jyoumei.cn/Article/details/gt2gpcpgwkk.html

[U35] Py：发送邮件
来源：http://dali.yvedp.cn/Article/details/gt2fmizrkqe.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.chenzaomai.com/Article/details/gt2mwnihubj.html

[U36] Py：定时任务
来源：http://dali.shuidangran.top/Article/details/gt2edskjjhy.html

schedule.every(10).minutes.do(job)
来源：http://dali.ppjwa.cn/Article/details/gt2sjyfoqpm.html

[U37] Py：读写 Excel
来源：http://dali.smart0.xyz/Article/details/gt2lxdcilzu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.316326.xyz/Article/details/gt2decbrerj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhiwuduotai.top/Article/details/gt2baxgcphl.html

Path(__file__).resolve().parent
来源：http://dali.dashuyun.cn/Article/details/gt2chglumsw.html

[U39] Py：判断是否在交互环境
来源：http://dali.hywenlv.cn/Article/details/gt2vsnfrklp.html

sys.stdout.isatty()
来源：http://dali.yj202588.top/Article/details/gt2jfgucmrb.html

[U40] Py：打印到标准错误
来源：http://dali.jianghu66.top/Article/details/gt2jbuzimsw.html

print("err", file=sys.stderr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2skmgbmqc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jlsjyb.cn/Article/details/gt2avdpszji.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ppjwa.cn/Article/details/gt2jjxfjsat.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.iojbl.cn/Article/details/gt2gkgjzfwu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.sxryk.cn/Article/details/gt2ggrubqil.html

[U43] PHP：声明命名空间
来源：http://dali.meibo888.top/Article/details/gt2wrhwgjfp.html

namespace App\Http;
来源：http://dali.snrcjt.cn/Article/details/gt2xjscoeyy.html

[U44] PHP：开启严格类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2wosrvfjj.html

declare(strict_types=1);
来源：http://dali.yuxming.cn/Article/details/gt2pgbdecow.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ajllxvaq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gt2smlsxlxc.html

[U46] PHP：可空类型
来源：http://dali.snrcjt.cn/Article/details/gt2odllejin.html

?string $name = null
来源：http://dali.aibaodan.cn/Article/details/gt2tljkscfu.html

[U47] PHP：联合类型
来源：http://dali.xinyue.icu/Article/details/gt2cfkqhlwd.html

int|string $id
来源：http://dali.mhx1999.top/Article/details/gt2sedvxbhe.html

[U48] PHP：纯枚举
来源：http://dali.fzhhl.top/Article/details/gt2mpxxrfke.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shuidangran.top/Article/details/gt2oeaarqnd.html

[U49] PHP：只读属性
来源：http://dali.c1oappe.top/Article/details/gt2fnvbdwrw.html

public readonly string $name
来源：http://dali.zycfv.cn/Article/details/gt2qmapslek.html

[U50] PHP：构造器属性提升
来源：http://dali.9152youxi.cn/Article/details/gt2jhndvpfs.html

public function __construct(private int $id) {}
来源：http://dali.yonumen.top/Article/details/gt2uisvknqa.html

[U51] PHP：数组解构
来源：http://dali.hnqzz.top/Article/details/gt2suwtlzrt.html

[$a, $b] = $arr;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rchavltz.html

[U52] PHP：箭头函数
来源：http://dali.xylfe.cn/Article/details/gt2jutmgyol.html

$double = fn($x) => $x * 2;
来源：http://dali.haohaochexian.top/Article/details/gt2gnxyvnpu.html

[U53] PHP：空合并运算符
来源：http://dali.quarkkingdee.top/Article/details/gt2rfyneydd.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhengqikj.top/Article/details/gt2fblyqvse.html

[U54] PHP：空安全调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwwqgbcj.html

$obj?->method()
来源：http://dali.feifeiyinyue.top/Article/details/gt2osnyfcvj.html

[U55] PHP：match 表达式
来源：http://dali.yj20258888.top/Article/details/gt2hkuarytp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hfpthk.cn/Article/details/gt2dpevyovt.html

[U56] PHP：命名参数
来源：http://dali.yueranfly.top/Article/details/gt2iapwsqdo.html

f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gt2enmmylvu.html

[U57] PHP：字符串插值
来源：http://dali.ybcxt.top/Article/details/gt2dblgiyqt.html

"值: {$a}"
来源：http://dali.daxiang520.top/Article/details/gt2zhgixwtt.html

[U58] PHP：数组三件套
来源：http://dali.fzhhl.top/Article/details/gt2owfidcmv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ivvv.top/Article/details/gt2zohczlqp.html

[U59] PHP：自定义排序
来源：http://dali.ehwqpu.com/Article/details/gt2esalmnxz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xinyue.icu/Article/details/gt2nybxoxwa.html

[U60] PHP：JSON 编解码
来源：http://dali.cdnleiting.top/Article/details/gt2awxdypoc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gotoacloud.top/Article/details/gt2cvxkjopi.html

[U61] PHP：正则
来源：http://dali.kuanghao11.cn/Article/details/gt2sivzdfyg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.c1oappe.top/Article/details/gt2jcuezkaw.html

[U62] PHP：日期对象
来源：http://dali.yueranfly.top/Article/details/gt2piwbmfag.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhoulong.xyz/Article/details/gt2svtdtprz.html

[U63] PHP：文件读写
来源：http://dali.jinqigufen.top/Article/details/gt2xhdbwaal.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jiagoushi.top/Article/details/gt2atyjdzuh.html

[U64] PHP：目录遍历
来源：http://dali.yvedp.cn/Article/details/gt2htnclkzh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.aizwys.cn/Article/details/gt2ylpkiabv.html

[U65] PHP：会话
来源：http://dali.shzxlz.cn/Article/details/gt2hdjzluoa.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.wangdashe.top/Article/details/gt2tdnoixcp.html

[U66] PHP：设置 Cookie
来源：http://dali.cqqwz.cn/Article/details/gt2cvdcvpwz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.redwolf501.top/Article/details/gt2qrditwae.html

[U67] PHP：处理文件上传
来源：http://dali.daxiang520.top/Article/details/gt2ecgftalr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.wangdashe.top/Article/details/gt2evtbqmvs.html

[U68] PHP：PDO 连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2snilyoso.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yuanzhike.top/Article/details/gt2suymhlbl.html

[U69] PHP：PDO 预处理
来源：http://dali.gaohongyu789.top/Article/details/gt2bhklhzdc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jlsjyb.cn/Article/details/gt2idbxtfsu.html

[U70] PHP：PDO 事务
来源：http://dali.dianchejie.cn/Article/details/gt2vildfcrb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ehwqpu.com/Article/details/gt2ovwcekcs.html

[U71] PHP：抛出异常
来源：http://dali.svipenyu.cn/Article/details/gt2mlxylnds.html

throw new RuntimeException("失败", 500);
来源：http://dali.hammf.cn/Article/details/gt2lqkujgja.html

[U72] PHP：写错误日志
来源：http://dali.xylfe.cn/Article/details/gt2knjuoopu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yj202588.top/Article/details/gt2indzatel.html

[U73] PHP：读取 ini 配置
来源：http://dali.9152youxi.cn/Article/details/gt2efenmzkc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhengqikj.top/Article/details/gt2rxlmgncu.html

[U74] PHP：读取环境变量
来源：http://dali.zdqjudy.top/Article/details/gt2ukibqcsk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yuanzhike.top/Article/details/gt2awsiwhbe.html

[U75] PHP：依赖注入
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxvlexbl.html

composer require psr/container
来源：http://dali.yuanzhike.top/Article/details/gt2dduhnejm.html

[U76] PHP：简单路由
来源：http://dali.ivvv.top/Article/details/gt2fnijhjwu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hnqzz.top/Article/details/gt2jdngpjlm.html

[U77] PHP：模板渲染
来源：http://dali.0kj1m.cn/Article/details/gt2xrkkhfby.html

composer require twig/twig
来源：http://dali.aizwys.cn/Article/details/gt2fvsrflze.html

[U78] PHP：单元测试
来源：http://dali.smart0.xyz/Article/details/gt2hcqezlzr.html

composer require --dev phpunit/phpunit
来源：http://dali.redwolf501.top/Article/details/gt2qcycabui.html

[U79] PHP：静态分析
来源：http://dali.fengsongda.top/Article/details/gt2pcxnqasx.html

composer require --dev phpstan/phpstan
来源：http://dali.daria6918.cn/Article/details/gt2idvoenbl.html

[U80] PHP：代码规范修复
来源：http://dali.cheryme.top/Article/details/gt2tipgsvyq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgufenzy.top/Article/details/gt2dvvzartm.html

[U81] JS：初始化项目
来源：http://dali.wangshuangyany.cn/Article/details/gt2uklzumom.html

npm init -y;  npm i express
来源：http://dali.xinyue.icu/Article/details/gt2riqbepcd.html

[U82] JS：package.json 脚本
来源：http://dali.jyoumei.cn/Article/details/gt2blgrqcxa.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yvedp.cn/Article/details/gt2hwvzxmro.html

[U83] JS：ES Module 导入导出
来源：http://dali.hongshengwenyu.top/Article/details/gt2arylctmn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gt2fgdrbogu.html

[U84] JS：CommonJS 写法
来源：http://dali.gaohongyu789.top/Article/details/gt2ztuidioh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.mhx1999.top/Article/details/gt2gjskrxjo.html

[U85] JS：可选链
来源：http://dali.redwolf501.top/Article/details/gt2emxpzjgn.html

a?.b?.c
来源：http://dali.jiagoushi.top/Article/details/gt2qzshqhmq.html

[U86] JS：空值合并
来源：http://dali.yuxming.cn/Article/details/gt2lfznotll.html

a ?? b
来源：http://dali.ydzc1.top/Article/details/gt2ymersylg.html

[U87] JS：解构默认值
来源：http://dali.jlsjyb.cn/Article/details/gt2xlcayerh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.birdmap.top/Article/details/gt2csmvnztq.html

[U88] JS：对象展开合并
来源：http://dali.aibaodan.cn/Article/details/gt2ipdmmpch.html

{ ...a, ...b }
来源：http://dali.cashguo.top/Article/details/gt2uumcpezr.html

[U89] JS：数组去重
来源：http://dali.mhx1999.top/Article/details/gt2ariclzus.html

[...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lgvbhrfl.html

[U90] JS：数字数组排序
来源：http://dali.cqqwz.cn/Article/details/gt2zmarefzn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gt2jpwttvmu.html

[U91] JS：对象键值遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2njclnuit.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jyoumei.cn/Article/details/gt2ebgisgvp.html

[U92] JS：深拷贝
来源：http://dali.nwbrower.top/Article/details/gt2lxlomnuz.html

structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2dtuvkemd.html

[U93] JS：模板字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hyksfssl.html

`共 ${n} 条`
来源：http://dali.smart0.xyz/Article/details/gt2kfdytmvr.html

[U94] JS：箭头函数
来源：http://dali.yangfankeji.com/Article/details/gt2rgzfqfzu.html

const double = x => x * 2;
来源：http://dali.bjfxy.top/Article/details/gt2pjegsncz.html

[U95] JS：Promise 包装
来源：http://dali.ivvv.top/Article/details/gt2wzfjgefa.html

new Promise((resolve, reject) => {})
来源：http://dali.zhengqikj.top/Article/details/gt2kohoihbd.html

[U96] JS：async/await 与异常
来源：http://dali.shzxlz.cn/Article/details/gt2eucidwkf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gt2gljzpkcl.html

[U97] JS：并发请求
来源：http://dali.jiagoushi.top/Article/details/gt2lksbsvpu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gt2frkrnthq.html

[U98] JS：fetch 带 JSON
来源：http://dali.sweek.top/Article/details/gt2beglzbht.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.redwolf501.top/Article/details/gt2klsauzid.html

[U99] JS：事件监听
来源：http://dali.9152youxi.cn/Article/details/gt2llopyvrn.html

el.addEventListener("click", e => {})
来源：http://dali.daria6918.cn/Article/details/gt2ehruyrmm.html

[U100] JS：DOM 查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2zlkkqjac.html

document.querySelector(".item")
来源：http://dali.yj202588.top/Article/details/gt2vjamitvc.html

[U101] JS：classList 操作
来源：http://dali.dianchejie.cn/Article/details/gt2icgkdaav.html

el.classList.toggle("active")
来源：http://dali.hammf.cn/Article/details/gt2lwsuzgqe.html

[U102] JS：本地存储
来源：http://dali.sxryk.cn/Article/details/gt2jlgcqrnh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.svipenyu.cn/Article/details/gt2ybpuunvg.html

[U103] JS：定时器
来源：http://dali.tianlin.xyz/Article/details/gt2jrpkdruk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sweek.top/Article/details/gt2iomdxylg.html

[U104] JS：防抖
来源：http://dali.hysaishi.cn/Article/details/gt2tkthjbks.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gt2dfqmoeuj.html

[U105] JS：节流
来源：http://dali.yangfankeji.com/Article/details/gt2xgegqhii.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sysykeji.top/Article/details/gt2wlgimlxy.html

[U106] JS：日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gt2jfpsjncm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.quarkkingdee.top/Article/details/gt2padnaqes.html

[U107] JS：数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eynhzweh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yvedp.cn/Article/details/gt2daqufanq.html

[U108] JS：随机整数
来源：http://dali.ydzc1.top/Article/details/gt2egtnayfq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hnxiangtu.top/Article/details/gt2bztyyfmp.html

[U109] JS：数组分组
来源：http://dali.cqqwz.cn/Article/details/gt2ybmqfulc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gt2qekpiuwq.html

[U110] JS：数组分块
来源：http://dali.cqqwz.cn/Article/details/gt2rktllssb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gnjmixaf.html

[U111] JS：对象转 Map
来源：http://dali.nanxinkj.top/Article/details/gt2pskclpuc.html

new Map(Object.entries(obj))
来源：http://dali.chenlongwang.top/Article/details/gt2yikuxfpp.html

[U112] JS：字符串补位
来源：http://dali.wangdashe.top/Article/details/gt2uqvippot.html

"7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2esfuhnfe.html

[U113] JS：正则替换全部
来源：http://dali.kuanghao11.cn/Article/details/gt2zoumedlk.html

s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2gixqoosb.html

[U114] JS：JSON 深比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2xuooyicn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gt2qdcondut.html

[U115] JS：生成 UUID
来源：http://dali.ivvv.top/Article/details/gt2ixzazexl.html

crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gt2ktymkjos.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jiagoushi.top/Article/details/gt2vfmemrat.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yuanzhike.top/Article/details/gt2kmlseajx.html

[U117] JS：单元测试
来源：http://dali.yuxming.cn/Article/details/gt2wymkkiih.html

npm i -D vitest;  npx vitest
来源：http://dali.zhongyouzk.top/Article/details/gt2wheoadyp.html

[U118] JS：开发服务器
来源：http://dali.tian-w.cn/Article/details/gt2xiqwlaii.html

npm i -D vite;  npx vite
来源：http://dali.dashuyun.cn/Article/details/gt2pzzhpkvk.html

[U119] JS：生产构建
来源：http://dali.xuanzx.com/Article/details/gt2batnxxsw.html

npx vite build
来源：http://dali.ydzc1.top/Article/details/gt2xvhgtmpn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cashguo.top/Article/details/gt2tcsiawxi.html

import.meta.env.VITE_API_URL
来源：http://dali.zhongyouzk.top/Article/details/gt2yriintxh.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2iqhxyvez.html

统计汇总
来源：http://dali.yanxiufei.cn/Article/details/gt2gggqamxo.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eosbnbcy.html

按语言统计（条）：
来源：http://dali.yonumen.top/Article/details/gt2qgtcscmg.html

Python ......... 252
来源：http://dali.haohaochexian.top/Article/details/gt2ldbzelkl.html

PHP ............ 252
来源：http://dali.gaohongyu789.top/Article/details/gt2ouohfkvo.html

JavaScript ..... 252
来源：http://dali.chenlongwang.top/Article/details/gt2rtmntdgf.html

TypeScript ..... 212
来源：http://dali.zhiwuduotai.top/Article/details/gt2lzovnshu.html

Java ........... 212
来源：http://dali.yuxming.cn/Article/details/gt2pxhkkicm.html

Go ............. 212
来源：http://dali.yuxming.cn/Article/details/gt2iqmpxyso.html

Ruby ........... 212
来源：http://dali.zycfv.cn/Article/details/gt2focbzwgr.html

C# ............. 212
来源：http://dali.tian-w.cn/Article/details/gt2mjdnurto.html

C .............. 30
来源：http://dali.316326.xyz/Article/details/gt2gwypsudg.html

C++ ............ 30
来源：http://dali.ivvv.top/Article/details/gt2ewagfcfx.html

SQL ............ 90
来源：http://dali.zdqjudy.top/Article/details/gt2tllwratk.html

Bash ........... 80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kadxboyk.html

Kotlin ......... 15
来源：http://dali.yvedp.cn/Article/details/gt2npcpzvdn.html

Swift .......... 15
来源：http://dali.pengpengdd.cyou/Article/details/gt2qzxlgjdm.html

Lua ............ 10
来源：http://dali.hywenlv.cn/Article/details/gt2gyyxbdve.html

Perl ........... 10
来源：http://dali.svipenyu.cn/Article/details/gt2uayrtgck.html

Scala .......... 10
来源：http://dali.gzhubu.top/Article/details/gt2vdybxgsw.html

------------------------------------
来源：http://dali.sxryk.cn/Article/details/gt2blopyhkq.html

合计 ........... 2106 条
来源：http://dali.yuanzhike.top/Article/details/gt2ldbmldns.html

按章节统计：
来源：http://dali.zhiwuduotai.top/Article/details/gt2uekhtiha.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yuanzhike.top/Article/details/gt2yoyzfedk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.chenjidiqi.icu/Article/details/gt2axljlnpd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cucudq.cn/Article/details/gt2floautnj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.daxiang520.top/Article/details/gt2hijhnvsn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.bjfxy.top/Article/details/gt2tjxrfqvo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.feifeiyinyue.top/Article/details/gt2dzshmfyz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hfpthk.cn/Article/details/gt2dpnyfpcq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.aizwys.cn/Article/details/gt2slcvjwsn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gt2wwznnjtw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.fengsongda.top/Article/details/gt2waiuhiyz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gt2ljdddynw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kuowjtda.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gt2kneocwao.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.haohaochexian.top/Article/details/gt2qiehndlv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.redwolf501.top/Article/details/gt2zotodhwd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gt2pohywjxc.html

Q SQL 专题                              90
来源：http://dali.meibo888.top/Article/details/gt2wlsfknvl.html

R Bash 专题                             80
来源：http://dali.cheryme.top/Article/details/gt2uyabvapb.html

S C / C++ 专题                          60
来源：http://dali.xinyue.icu/Article/details/gt2okhsnkgg.html

T 其他语言补充                          60
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cxyeefvu.html

U 高频实用片段                         120
来源：http://dali.sweek.top/Article/details/gt2fbndrqpo.html

------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gt2vskobidf.html

合计                                  2106 条
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kjuycbrr.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gt2awcvfcpa.html

使用提醒
来源：http://dali.jiagoushi.top/Article/details/gt2kstchdtd.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gt2abtaivul.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwxulqap.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.9152youxi.cn/Article/details/gt2fvgmdhsb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhengqikj.top/Article/details/gt2jehlosdg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yj202588.top/Article/details/gt2nfetsbjx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.aibaodan.cn/Article/details/gt2vrsmpque.html

—— 文件结束 ——
来源：http://dali.snrcjt.cn/Article/details/gt2uapnekzr.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2jpcaslkm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.sysykeji.top/Article/details/gt2ucpszwbo.html

Common Programming Examples Cheat Book
来源：http://dali.vqdsnc.cn/Article/details/gt2lhdjzswm.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2girerpen.html

【收录内容】
来源：http://dali.feifeiyinyue.top/Article/details/gt2udcwukwx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hfpthk.cn/Article/details/gt2fhfamvnd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.vqdsnc.cn/Article/details/gt2ihvlmdsn.html

SQL · Bash · C · C++
来源：http://dali.quarkkingdee.top/Article/details/gt2ipfcjhxt.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shuidangran.top/Article/details/gt2ildljwuk.html

【使用说明】
来源：http://dali.gotoacloud.top/Article/details/gt2pslrwrwv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ehwqpu.com/Article/details/gt2ffvqwsuq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.gotoacloud.top/Article/details/gt2ahwnvmdk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yanxiufei.cn/Article/details/gt2jzimbpao.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.nwbrower.top/Article/details/gt2xtmjbdnk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lrppvbgl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yj20258.top/Article/details/gt2umtindqd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.tanke756.top/Article/details/gt2qjakjbky.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.316326.xyz/Article/details/gt2jsrbekkn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.guowangkeji.top/Article/details/gt2odjdgiuu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xziqi.cn/Article/details/gt2lbunbhnz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.guowangkeji.top/Article/details/gt2gavglsao.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.feifeiyinyue.top/Article/details/gt2ewgrtcrt.html

【文件统计】
来源：http://dali.zhiwuduotai.top/Article/details/gt2gjhtoidu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shzxlz.cn/Article/details/gt2bxcvofkz.html

--------------------------------------------------------------------------------
来源：http://dali.nwbrower.top/Article/details/gt2aiqncrmo.html

目  录
来源：http://dali.zhixingplan.top/Article/details/gt2nozqrzzr.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gt2udravqiw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.aibaodan.cn/Article/details/gt2hptvkqfs.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ehwqpu.com/Article/details/gt2gonuunaz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2gaqpbzps.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2rrcozwxf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2lodctscs.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ppjwa.cn/Article/details/gt2lsxptrut.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2pwllddcr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xylfe.cn/Article/details/gt2lvklmgsb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ehwqpu.com/Article/details/gt2itdjmldo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.tianlin.xyz/Article/details/gt2qrboxcpc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ybcxt.top/Article/details/gt2mlbbzwaw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yvedp.cn/Article/details/gt2liaslnbs.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gt2zjodmtqz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yuanzhike.top/Article/details/gt2vyvdzzkt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ybcxt.top/Article/details/gt2doflosgr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ierqfxcn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.meibo888.top/Article/details/gt2ydmkbdfj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.0kj1m.cn/Article/details/gt2igkwvwfh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2zqjwzdyw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gt2tgaszkjy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gt2lttctkxe.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2xqmwjstv.html

A. 基础语法与类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmxcftem.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ktbfcxyr.html

[A01] Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sgctassv.html

Py:   print("Hello, World!")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cferysnm.html

PHP:  echo "Hello, World!";
来源：http://dali.ydzc1.top/Article/details/gt2yppbjxpr.html

JS:   console.log("Hello, World!");
来源：http://dali.yuxming.cn/Article/details/gt2mhsdqyir.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yj20258888.top/Article/details/gt2vawltojj.html

Java: System.out.println("Hello, World!");
来源：http://dali.gogol.net.cn/Article/details/gt2kjqisuvv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.tian-w.cn/Article/details/gt2fbcetqng.html

Ruby: puts "Hello, World!"
来源：http://dali.kuanghao11.cn/Article/details/gt2hryszcom.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2roxazeel.html

[A02] 变量声明与赋值
来源：http://dali.iojbl.cn/Article/details/gt2ytptxjfy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hfpthk.cn/Article/details/gt2iweshxqo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.quarkkingdee.top/Article/details/gt2zkrtnyvu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cdnleiting.top/Article/details/gt2atywuaek.html


<!-- 参考信息 -->