代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gt2hicivgkk.html

"值: {$a}"
来源：http://dali.yongpay.top/Article/details/gt2bvrquiwt.html

[U58] PHP：数组三件套
来源：http://dali.fengsongda.top/Article/details/gt2iipypqgd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yongpay.top/Article/details/gt2qxhaecck.html

[U59] PHP：自定义排序
来源：http://dali.cucudq.cn/Article/details/gt2jemchmqr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xylfe.cn/Article/details/gt2pyyyohdf.html

[U60] PHP：JSON 编解码
来源：http://dali.daxiang520.top/Article/details/gt2uaxmgdoj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yj202588.top/Article/details/gt2yqqlmmzl.html

[U61] PHP：正则
来源：http://dali.ydzc1.top/Article/details/gt2jbpeicft.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2bkbkkzjz.html

[U62] PHP：日期对象
来源：http://dali.nanxuanxn.top/Article/details/gt2cvmzgmpg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hysaishi.cn/Article/details/gt2jxbczuwt.html

[U63] PHP：文件读写
来源：http://dali.hammf.cn/Article/details/gt2sxdaxqmi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sweek.top/Article/details/gt2vsifktsk.html

[U64] PHP：目录遍历
来源：http://dali.yuanzhike.top/Article/details/gt2geffhyjy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj202588.top/Article/details/gt2hehsokob.html

[U65] PHP：会话
来源：http://dali.jqgufenzy.top/Article/details/gt2hkygvaul.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2qwgjsved.html

[U66] PHP：设置 Cookie
来源：http://dali.xinyue.icu/Article/details/gt2dfndrajd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ppjwa.cn/Article/details/gt2hmtlfqin.html

[U67] PHP：处理文件上传
来源：http://dali.jinqigufen.top/Article/details/gt2ilhgdlgk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxjdjpfr.html

[U68] PHP：PDO 连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wgrjmtxp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tianlin.xyz/Article/details/gt2dwvryfje.html

[U69] PHP：PDO 预处理
来源：http://dali.fengsongda.top/Article/details/gt2sfoghliz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xylfe.cn/Article/details/gt2ujckpivw.html

[U70] PHP：PDO 事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oxashtst.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ehwqpu.com/Article/details/gt2nhjtztcf.html

[U71] PHP：抛出异常
来源：http://dali.zdqjudy.top/Article/details/gt2nkvatear.html

throw new RuntimeException("失败", 500);
来源：http://dali.jqgfzy.top/Article/details/gt2ygbnwauo.html

[U72] PHP：写错误日志
来源：http://dali.jqgfzy.top/Article/details/gt2dzajmmia.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhoulong.xyz/Article/details/gt2zuualxew.html

[U73] PHP：读取 ini 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nifxlosj.html

parse_ini_file("config.ini", true)
来源：http://dali.nanxuanxn.top/Article/details/gt2unuwsvpx.html

[U74] PHP：读取环境变量
来源：http://dali.guannengcc.top/Article/details/gt2nurwpssg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fyorpepe.html

[U75] PHP：依赖注入
来源：http://dali.jqgfzy.top/Article/details/gt2oeaizbjs.html

composer require psr/container
来源：http://dali.nwbrower.top/Article/details/gt2cbhjiyqi.html

[U76] PHP：简单路由
来源：http://dali.cashguo.top/Article/details/gt2bhbwpmhj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ijpdchwb.html

[U77] PHP：模板渲染
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kvxcpvra.html

composer require twig/twig
来源：http://dali.jianghu66.top/Article/details/gt2yzcxjelo.html

[U78] PHP：单元测试
来源：http://dali.xziqi.cn/Article/details/gt2ldgzydhv.html

composer require --dev phpunit/phpunit
来源：http://dali.cdnleiting.top/Article/details/gt2duawvpjb.html

[U79] PHP：静态分析
来源：http://dali.ybcxt.top/Article/details/gt2cydmpaiu.html

composer require --dev phpstan/phpstan
来源：http://dali.sweek.top/Article/details/gt2sqrklnbz.html

[U80] PHP：代码规范修复
来源：http://dali.fzhhl.top/Article/details/gt2jkkxbghv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uyrcybje.html

[U81] JS：初始化项目
来源：http://dali.cdnleiting.top/Article/details/gt2xoglvqus.html

npm init -y;  npm i express
来源：http://dali.jqgfzy.top/Article/details/gt2kyuqtypj.html

[U82] JS：package.json 脚本
来源：http://dali.wangdashe.top/Article/details/gt2tvxepitr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.nanxinkj.top/Article/details/gt2cjtfuzau.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2huzspbqy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yangfankeji.com/Article/details/gt2iqyeowwb.html

[U84] JS：CommonJS 写法
来源：http://dali.yueranfly.top/Article/details/gt2zxjyasut.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.wangdashe.top/Article/details/gt2hhsdyupy.html

[U85] JS：可选链
来源：http://dali.haohaochexian.top/Article/details/gt2vxwhqygz.html

a?.b?.c
来源：http://dali.kuanghao11.cn/Article/details/gt2wlesjnnn.html

[U86] JS：空值合并
来源：http://dali.gaohongyu789.top/Article/details/gt2axvifyom.html

a ?? b
来源：http://dali.jinqigfzy.top/Article/details/gt2usnecqjq.html

[U87] JS：解构默认值
来源：http://dali.haohaochexian.top/Article/details/gt2wzqpmkwk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.tanke756.top/Article/details/gt2kfizpamu.html

[U88] JS：对象展开合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jcssycho.html

{ ...a, ...b }
来源：http://dali.pycfn.com/Article/details/gt2gxjgpvxn.html

[U89] JS：数组去重
来源：http://dali.vqdsnc.cn/Article/details/gt2qdcbpjst.html

[...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gt2awrkbtor.html

[U90] JS：数字数组排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qrfiaoqn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gt2slmyonss.html

[U91] JS：对象键值遍历
来源：http://dali.zdqjudy.top/Article/details/gt2ituntpgu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yanxiufei.cn/Article/details/gt2debzblhj.html

[U92] JS：深拷贝
来源：http://dali.fzhhl.top/Article/details/gt2ozejvgbm.html

structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2vgushfcm.html

[U93] JS：模板字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cacyqtzk.html

`共 ${n} 条`
来源：http://dali.yueranfly.top/Article/details/gt2cbnhxlhr.html

[U94] JS：箭头函数
来源：http://dali.xziqi.cn/Article/details/gt2zghveacm.html

const double = x => x * 2;
来源：http://dali.tian-w.cn/Article/details/gt2hldzpknr.html

[U95] JS：Promise 包装
来源：http://dali.jiagoushi.top/Article/details/gt2thlixycw.html

new Promise((resolve, reject) => {})
来源：http://dali.xylfe.cn/Article/details/gt2ruqknqeo.html

[U96] JS：async/await 与异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2prvbktbr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gt2gsvndahw.html

[U97] JS：并发请求
来源：http://dali.jinqigfzy.top/Article/details/gt2cryoxurg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gt2gtqzfkft.html

[U98] JS：fetch 带 JSON
来源：http://dali.ivvv.top/Article/details/gt2ujjepegc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2ldijfxqp.html

[U99] JS：事件监听
来源：http://dali.xziqi.cn/Article/details/gt2lijnlpmu.html

el.addEventListener("click", e => {})
来源：http://dali.fzhhl.top/Article/details/gt2xjpobibz.html

[U100] JS：DOM 查询
来源：http://dali.daria6918.cn/Article/details/gt2ahsalpzi.html

document.querySelector(".item")
来源：http://dali.9152youxi.cn/Article/details/gt2heboxvdm.html

[U101] JS：classList 操作
来源：http://dali.yj20258888.top/Article/details/gt2iufekegs.html

el.classList.toggle("active")
来源：http://dali.hnxiangtu.top/Article/details/gt2nqkrdurv.html

[U102] JS：本地存储
来源：http://dali.dashuyun.cn/Article/details/gt2gkqlotbz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hysaishi.cn/Article/details/gt2crieutsr.html

[U103] JS：定时器
来源：http://dali.yanxiufei.cn/Article/details/gt2aejgifjy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ybcxt.top/Article/details/gt2bvdbwevi.html

[U104] JS：防抖
来源：http://dali.daria6918.cn/Article/details/gt2dvuarvfw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gt2swdeysmb.html

[U105] JS：节流
来源：http://dali.guannengcc.top/Article/details/gt2ktlonpwi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gogol.net.cn/Article/details/gt2rqenoqxd.html

[U106] JS：日期格式化
来源：http://dali.jyoumei.cn/Article/details/gt2fwdtowrt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yuxming.cn/Article/details/gt2glxxfedc.html

[U107] JS：数字千分位
来源：http://dali.c1oappe.top/Article/details/gt2uwgsxeya.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhixingplan.top/Article/details/gt2xcriknnl.html

[U108] JS：随机整数
来源：http://dali.sysykeji.top/Article/details/gt2aeeliypt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhongyouzk.top/Article/details/gt2iduwaqem.html

[U109] JS：数组分组
来源：http://dali.aibaodan.cn/Article/details/gt2fovxjlhk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cashguo.top/Article/details/gt2zrgjsvxn.html

[U110] JS：数组分块
来源：http://dali.nwbrower.top/Article/details/gt2mkgdtcar.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yangfankeji.com/Article/details/gt2eahxddnf.html

[U111] JS：对象转 Map
来源：http://dali.c1oappe.top/Article/details/gt2bhnsdkmo.html

new Map(Object.entries(obj))
来源：http://dali.zycfv.cn/Article/details/gt2ghwrghlx.html

[U112] JS：字符串补位
来源：http://dali.yonumen.top/Article/details/gt2ftpyihnf.html

"7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2huswjhjr.html

[U113] JS：正则替换全部
来源：http://dali.cheryme.top/Article/details/gt2qchzlbdl.html

s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2yfhoggeu.html

[U114] JS：JSON 深比较
来源：http://dali.ppjwa.cn/Article/details/gt2veyjppfh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gaohongyu789.top/Article/details/gt2fkzseibv.html

[U115] JS：生成 UUID
来源：http://dali.gzhubu.top/Article/details/gt2eskxenqn.html

crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gt2odjfgmip.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ydzc1.top/Article/details/gt2zestjixo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2xipbynli.html

[U117] JS：单元测试
来源：http://dali.jiagoushi.top/Article/details/gt2yewjpgjp.html

npm i -D vitest;  npx vitest
来源：http://dali.andypj.xyz/Article/details/gt2hpexyxde.html

[U118] JS：开发服务器
来源：http://dali.tian-w.cn/Article/details/gt2jtiqmdoy.html

npm i -D vite;  npx vite
来源：http://dali.hnxiangtu.top/Article/details/gt2gpnzgzzg.html

[U119] JS：生产构建
来源：http://dali.jiagoushi.top/Article/details/gt2vtecigja.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwakvvk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.redwolf501.top/Article/details/gt2lsdqrchd.html

import.meta.env.VITE_API_URL
来源：http://dali.hnqzz.top/Article/details/gt2sxzxktwu.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2kihkftqn.html

统计汇总
来源：http://dali.pengpengdd.cyou/Article/details/gt2zcldvdar.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2dlqevwvi.html

按语言统计（条）：
来源：http://dali.9152youxi.cn/Article/details/gt2jpzsfvsf.html

Python ......... 252
来源：http://dali.hywenlv.cn/Article/details/gt2vdwiseos.html

PHP ............ 252
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nojmfgxv.html

JavaScript ..... 252
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dffyeahe.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgsmbpf.html

Java ........... 212
来源：http://dali.ybcxt.top/Article/details/gt2ewhewuhx.html

Go ............. 212
来源：http://dali.hongshengwenyu.top/Article/details/gt2ptzijxib.html

Ruby ........... 212
来源：http://dali.zhixingplan.top/Article/details/gt2ljpokxpj.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qughieui.html

C .............. 30
来源：http://dali.nwbrower.top/Article/details/gt2jiiailoa.html

C++ ............ 30
来源：http://dali.nwbrower.top/Article/details/gt2vitdfbzv.html

SQL ............ 90
来源：http://dali.hysaishi.cn/Article/details/gt2zkdjmhdw.html

Bash ........... 80
来源：http://dali.gaohongyu789.top/Article/details/gt2mqgtsdad.html

Kotlin ......... 15
来源：http://dali.nanxuanxn.top/Article/details/gt2kslqsyjk.html

Swift .......... 15
来源：http://dali.jiagoushi.top/Article/details/gt2yjmjsheu.html

Lua ............ 10
来源：http://dali.snrcjt.cn/Article/details/gt2gafmasfb.html

Perl ........... 10
来源：http://dali.9152youxi.cn/Article/details/gt2xrsupojp.html

Scala .......... 10
来源：http://dali.dashuyun.cn/Article/details/gt2afnnvfks.html

------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aysmdnve.html

合计 ........... 2106 条
来源：http://dali.feifeiyinyue.top/Article/details/gt2whurwdrq.html

按章节统计：
来源：http://dali.xziqi.cn/Article/details/gt2pbqsqcnk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gt2ufhsbcvw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gaohongyu789.top/Article/details/gt2cgwjbjfr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gt2ciztrlbn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shanyushiyangtech.top/Article/details/gt2phknbavi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ydzc1.top/Article/details/gt2lfdbyryr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yonumen.top/Article/details/gt2ltdkuqxk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gzhubu.top/Article/details/gt2iniksfek.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.vqdsnc.cn/Article/details/gt2xvxmjbdz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gt2rjyeuuai.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.vqdsnc.cn/Article/details/gt2iufvkgvc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gt2vizvcsbn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gt2ztplqxlu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gt2tpnxpskg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ydzc1.top/Article/details/gt2fbiobdbj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.smart0.xyz/Article/details/gt2pnwfqpfu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gt2vprjvokd.html

Q SQL 专题                              90
来源：http://dali.ybcxt.top/Article/details/gt2mpooqylo.html

R Bash 专题                             80
来源：http://dali.dashuyun.cn/Article/details/gt2darluxxq.html

S C / C++ 专题                          60
来源：http://dali.cheryme.top/Article/details/gt2mcmczryi.html

T 其他语言补充                          60
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dqduduxd.html

U 高频实用片段                         120
来源：http://dali.yvedp.cn/Article/details/gt2ufpoydnh.html

------------------------------------
来源：http://dali.yuxming.cn/Article/details/gt2pbfijoit.html

合计                                  2106 条
来源：http://dali.iojbl.cn/Article/details/gt2qwwqarya.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xlohvgxf.html

使用提醒
来源：http://dali.daxiang520.top/Article/details/gt2hdfgwwfj.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gt2sadwjrdb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jianghu66.top/Article/details/gt2rmvoidrj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yj20258.top/Article/details/gt2teffvkct.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.andypj.xyz/Article/details/gt2cloixbxj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yangfankeji.com/Article/details/gt2dgyzgzer.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hnxiangtu.top/Article/details/gt2jnlwlnyv.html

—— 文件结束 ——
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cvwimdus.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2mqjvpsoi.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhengqikj.top/Article/details/gt2bqwodjst.html

Common Programming Examples Cheat Book
来源：http://dali.shuidangran.top/Article/details/gt2zxuijfws.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2rgqpsdaz.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ildxtydq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.chenzaomai.com/Article/details/gt2vwqulcii.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2snwbjvep.html

SQL · Bash · C · C++
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wwuptujn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cashguo.top/Article/details/gt2eljiwqev.html

【使用说明】
来源：http://dali.pengpengdd.cyou/Article/details/gt2cscvogbr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zdqjudy.top/Article/details/gt2wapvxcpc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.c1oappe.top/Article/details/gt2ftjoxbjj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xylfe.cn/Article/details/gt2wjnuohiy.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ivvv.top/Article/details/gt2wubovsaw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.smart0.xyz/Article/details/gt2ioylciqb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gzhubu.top/Article/details/gt2kxttxodf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.sysykeji.top/Article/details/gt2aerbkanb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zhwaiocn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hnxiangtu.top/Article/details/gt2rwsmpzeh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jinqigufen.top/Article/details/gt2dzenqmea.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhoulong.xyz/Article/details/gt2esaycbob.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.redwolf501.top/Article/details/gt2zdauloiu.html

【文件统计】
来源：http://dali.nanxuanxn.top/Article/details/gt2lnnjuvxa.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.guowangkeji.top/Article/details/gt2hfzzexjq.html

--------------------------------------------------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gt2vznudvmb.html

目  录
来源：http://dali.jianghu66.top/Article/details/gt2vbpylwfn.html

--------------------------------------------------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gt2gqimjbse.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.nanxinkj.top/Article/details/gt2kxlauhkx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.haohaochexian.top/Article/details/gt2gludrugv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uwilpwow.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.redwolf501.top/Article/details/gt2uriivsjk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.316326.xyz/Article/details/gt2xpvkbixe.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.dianchejie.cn/Article/details/gt2chodqqbp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2frdlfbdj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.tian-w.cn/Article/details/gt2vguznqss.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.wangdashe.top/Article/details/gt2cdozpdxl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.tanke756.top/Article/details/gt2iarlfhfa.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gt2opsvvagu.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gt2gkpeyvje.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gt2wbnfxheh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2vnhnreew.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dpvxbwjd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gt2mnmihndo.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2bnmmpaqf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.chenzaomai.com/Article/details/gt2mmekmeaw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jianghu66.top/Article/details/gt2cmhqwvrw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gotoacloud.top/Article/details/gt2ebthddox.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2jqsgkdfj.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2papdoafi.html

A. 基础语法与类型
来源：http://dali.guannengcc.top/Article/details/gt2qsxnhoau.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2tqunxurv.html

[A01] Hello World
来源：http://dali.iojbl.cn/Article/details/gt2ezkqdpms.html

Py:   print("Hello, World!")
来源：http://dali.yanxiufei.cn/Article/details/gt2pltrliqv.html

PHP:  echo "Hello, World!";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mcadqqii.html

JS:   console.log("Hello, World!");
来源：http://dali.yonumen.top/Article/details/gt2munwzwii.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yj20258.top/Article/details/gt2ugdcqaqx.html

Java: System.out.println("Hello, World!");
来源：http://dali.hnxiangtu.top/Article/details/gt2dzydzsbu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yonumen.top/Article/details/gt2lqfrchat.html

Ruby: puts "Hello, World!"
来源：http://dali.9152youxi.cn/Article/details/gt2hwzciqwh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yvedp.cn/Article/details/gt2phrnwqmt.html

[A02] 变量声明与赋值
来源：http://dali.xuanzx.com/Article/details/gt2paxfcsjm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.nanxuanxn.top/Article/details/gt2askiauuf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jianghu66.top/Article/details/gt2skajjkkg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.andypj.xyz/Article/details/gt2bzrsjqun.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.9152youxi.cn/Article/details/gt2ckxlpmtt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jyoumei.cn/Article/details/gt2oebpmydp.html

Go:   name := "Alex"; age := 20
来源：http://dali.wangshuangyany.cn/Article/details/gt2qgguziya.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jlsjyb.cn/Article/details/gt2ugigpndz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.tianlin.xyz/Article/details/gt2jszfvwgx.html

[A03] 常量定义
来源：http://dali.haohaochexian.top/Article/details/gt2nlcstkfk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.9152youxi.cn/Article/details/gt2dfzevcqo.html

PHP:  const PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gt2zkqjxjim.html

JS:   const PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2oubeiola.html

TS:   const PI: number = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2spmbirpn.html

Java: static final double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aaejgwop.html

Go:   const PI = 3.14159
来源：http://dali.ybcxt.top/Article/details/gt2qrwdqarg.html

Ruby: PI = 3.14159
来源：http://dali.redwolf501.top/Article/details/gt2cfrabzko.html

C#:   const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gt2qwevxxil.html

[A04] 判断变量类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2ermvchth.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ppjwa.cn/Article/details/gt2ohtevexg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xinyue.icu/Article/details/gt2uecgejau.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hywenlv.cn/Article/details/gt2ywpntgaf.html

TS:   typeof x; x instanceof Date
来源：http://dali.dianchejie.cn/Article/details/gt2pmohprtb.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yanxiufei.cn/Article/details/gt2ydtezjlx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.aizwys.cn/Article/details/gt2ijgtnnnx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2novkcdxl.html

C#:   x.GetType().Name; x is int
来源：http://dali.jqgfzy.top/Article/details/gt2ncnbklwi.html

[A05] 整数除法与取模
来源：http://dali.shuidangran.top/Article/details/gt2ntqsxyob.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shuidangran.top/Article/details/gt2nnvoessp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gt2kbhuhulh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gt2awpnurcf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gt2vavtkpao.html

Java: 7 / 2; 7 % 2
来源：http://dali.ivvv.top/Article/details/gt2euoopafv.html

Go:   7 / 2; 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gt2wyklrmfa.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gt2lkbqkvld.html

C#:   7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gt2sleqqbgm.html

[A06] 字符串转数字
来源：http://dali.zdqjudy.top/Article/details/gt2reuuaids.html

Py:   int("42"); float("3.14")
来源：http://dali.jinqigufen.top/Article/details/gt2oogarpzk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mdwivgda.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ehwqpu.com/Article/details/gt2qvmbsfda.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.tian-w.cn/Article/details/gt2evhbllix.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jinqigfzy.top/Article/details/gt2oytvpoes.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jiagoushi.top/Article/details/gt2deaslwwl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yuxming.cn/Article/details/gt2wvbhazgp.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.bjfxy.top/Article/details/gt2dxaocctf.html

[A07] 数字转字符串
来源：http://dali.yonumen.top/Article/details/gt2gabfujnm.html

Py:   str(42)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xnlfcujr.html

PHP:  (string) 42; strval(42)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lzvkwajz.html

JS:   String(42); (42).toString()
来源：http://dali.hfpthk.cn/Article/details/gt2efebwgwp.html

TS:   String(42)
来源：http://dali.quarkkingdee.top/Article/details/gt2kcswxlaw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zycfv.cn/Article/details/gt2ulxrtuqa.html

Go:   strconv.Itoa(42)
来源：http://dali.yuxming.cn/Article/details/gt2thyujimd.html

Ruby: 42.to_s
来源：http://dali.pengpengdd.cyou/Article/details/gt2zttzqqkq.html

C#:   42.ToString()
来源：http://dali.chenzaomai.com/Article/details/gt2pchsqlgq.html

[A08] 取整与四舍五入
来源：http://dali.316326.xyz/Article/details/gt2vgyzavgw.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gt2ohqudqfz.html


<!-- 参考信息 -->