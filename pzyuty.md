代发 wailian999

[U55] PHP：match 表达式
来源：http://dali.gaohongyu789.top/Article/details/gtmsuvkvoq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.smart0.xyz/Article/details/gthkswcyxh.html

[U56] PHP：命名参数
来源：http://dali.dashuyun.cn/Article/details/gtchtseaaj.html

f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gtnajsozke.html

[U57] PHP：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtqnmxjzgu.html

"值: {$a}"
来源：http://dali.9152youxi.cn/Article/details/gtzcaaayuw.html

[U58] PHP：数组三件套
来源：http://dali.daxiang520.top/Article/details/gtaaizkava.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cdnleiting.top/Article/details/gtoprxyfcg.html

[U59] PHP：自定义排序
来源：http://dali.chenjidiqi.icu/Article/details/gtsmpbyrgw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzchbasus.html

[U60] PHP：JSON 编解码
来源：http://dali.redwolf501.top/Article/details/gtqvnnsvyx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jiagoushi.top/Article/details/gtvejvixqc.html

[U61] PHP：正则
来源：http://dali.316326.xyz/Article/details/gthvizmcrd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.svipenyu.cn/Article/details/gtfvywpxle.html

[U62] PHP：日期对象
来源：http://dali.zhoulong.xyz/Article/details/gtedlibbcf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ivvv.top/Article/details/gtyoczomui.html

[U63] PHP：文件读写
来源：http://dali.xinyue.icu/Article/details/gtdvdpxpsu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.tanke756.top/Article/details/gtowlgahae.html

[U64] PHP：目录遍历
来源：http://dali.meibo888.top/Article/details/gtvbnhqoyy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sweek.top/Article/details/gtwuqzqlhq.html

[U65] PHP：会话
来源：http://dali.cucudq.cn/Article/details/gtpsybqtvf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtchhlgybw.html

[U66] PHP：设置 Cookie
来源：http://dali.yuxming.cn/Article/details/gtjicqarjf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yuanzhike.top/Article/details/gtdfgvgsou.html

[U67] PHP：处理文件上传
来源：http://dali.svipenyu.cn/Article/details/gtpuoxdxjw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbtyuonw.html

[U68] PHP：PDO 连接
来源：http://dali.yuxming.cn/Article/details/gtygfwqibv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ydzc1.top/Article/details/gtijanpzod.html

[U69] PHP：PDO 预处理
来源：http://dali.zhongyouzk.top/Article/details/gtunbnmqgk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jqgfzy.top/Article/details/gtdjrztess.html

[U70] PHP：PDO 事务
来源：http://dali.hnqzz.top/Article/details/gtoipvxock.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.mhx1999.top/Article/details/gthqxwztkn.html

[U71] PHP：抛出异常
来源：http://dali.guowangkeji.top/Article/details/gtxehggkzd.html

throw new RuntimeException("失败", 500);
来源：http://dali.dianchejie.cn/Article/details/gtizyfsovk.html

[U72] PHP：写错误日志
来源：http://dali.haohaochexian.top/Article/details/gtpphrtnbs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zycfv.cn/Article/details/gteetqmufz.html

[U73] PHP：读取 ini 配置
来源：http://dali.pycfn.com/Article/details/gtjmabkwvs.html

parse_ini_file("config.ini", true)
来源：http://dali.zdqjudy.top/Article/details/gtaedvamus.html

[U74] PHP：读取环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gtogrwjlvd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cqqwz.cn/Article/details/gtrwwadvfq.html

[U75] PHP：依赖注入
来源：http://dali.zhixingplan.top/Article/details/gtcxepoiry.html

composer require psr/container
来源：http://dali.xuanzx.com/Article/details/gtrainilxy.html

[U76] PHP：简单路由
来源：http://dali.snrcjt.cn/Article/details/gtblxwxnqy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cqqwz.cn/Article/details/gtwbsinguo.html

[U77] PHP：模板渲染
来源：http://dali.sufxvd.cn/Article/details/gtaubqnxvr.html

composer require twig/twig
来源：http://dali.zhoulong.xyz/Article/details/gtcnkgsgsc.html

[U78] PHP：单元测试
来源：http://dali.aibaodan.cn/Article/details/gtudoprqct.html

composer require --dev phpunit/phpunit
来源：http://dali.daxiang520.top/Article/details/gtvgglegqs.html

[U79] PHP：静态分析
来源：http://dali.sufxvd.cn/Article/details/gtvqgmvuff.html

composer require --dev phpstan/phpstan
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbadmjgug.html

[U80] PHP：代码规范修复
来源：http://dali.hnqzz.top/Article/details/gtcyrvkxmg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.tian-w.cn/Article/details/gtaxzhcvtu.html

[U81] JS：初始化项目
来源：http://dali.smart0.xyz/Article/details/gtjclxbndi.html

npm init -y;  npm i express
来源：http://dali.ppjwa.cn/Article/details/gtguftdxan.html

[U82] JS：package.json 脚本
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokguobpr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yonumen.top/Article/details/gtokmbcknq.html

[U83] JS：ES Module 导入导出
来源：http://dali.haohaochexian.top/Article/details/gtyuxhtxfc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.fengsongda.top/Article/details/gtifqzjzlb.html

[U84] JS：CommonJS 写法
来源：http://dali.dashuyun.cn/Article/details/gttdnefbfp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yj20258.top/Article/details/gtiutqsjjj.html

[U85] JS：可选链
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxupdyttb.html

a?.b?.c
来源：http://dali.hnqzz.top/Article/details/gtvsxzvrem.html

[U86] JS：空值合并
来源：http://dali.chenlongwang.top/Article/details/gtejsyoavf.html

a ?? b
来源：http://dali.hammf.cn/Article/details/gtlycuiikl.html

[U87] JS：解构默认值
来源：http://dali.jyoumei.cn/Article/details/gtlyqaklbt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yuxming.cn/Article/details/gtstmifljp.html

[U88] JS：对象展开合并
来源：http://dali.ivvv.top/Article/details/gttqlkwtwi.html

{ ...a, ...b }
来源：http://dali.aibaodan.cn/Article/details/gtpizcrzgd.html

[U89] JS：数组去重
来源：http://dali.guannengcc.top/Article/details/gtoofuqrdn.html

[...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gtqzpojpqk.html

[U90] JS：数字数组排序
来源：http://dali.jianghu66.top/Article/details/gtkuvakmgo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gtwpdqnltw.html

[U91] JS：对象键值遍历
来源：http://dali.316326.xyz/Article/details/gtxdbwfiyt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ivvv.top/Article/details/gthqlfypyz.html

[U92] JS：深拷贝
来源：http://dali.c1oappe.top/Article/details/gtffiyrxdm.html

structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtatdrbtqx.html

[U93] JS：模板字符串
来源：http://dali.guowangkeji.top/Article/details/gthxurecfx.html

`共 ${n} 条`
来源：http://dali.chenjidiqi.icu/Article/details/gttjbhdedb.html

[U94] JS：箭头函数
来源：http://dali.meibo888.top/Article/details/gtajpyqrly.html

const double = x => x * 2;
来源：http://dali.yuanzhike.top/Article/details/gttxyibxip.html

[U95] JS：Promise 包装
来源：http://dali.cheryme.top/Article/details/gthqrerrga.html

new Promise((resolve, reject) => {})
来源：http://dali.xylfe.cn/Article/details/gtnrixjtes.html

[U96] JS：async/await 与异常
来源：http://dali.tianlin.xyz/Article/details/gtwvjpulyw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gtletqcvjp.html

[U97] JS：并发请求
来源：http://dali.jqgfzy.top/Article/details/gtiopuvsvd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtbqjhxfnu.html

[U98] JS：fetch 带 JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagljmidi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.dianchejie.cn/Article/details/gtnuganzpk.html

[U99] JS：事件监听
来源：http://dali.zhongyouzk.top/Article/details/gtptxpevkf.html

el.addEventListener("click", e => {})
来源：http://dali.chenjidiqi.icu/Article/details/gtmstdfyxr.html

[U100] JS：DOM 查询
来源：http://dali.xuanzx.com/Article/details/gtzwyzxlnv.html

document.querySelector(".item")
来源：http://dali.jinqigfzy.top/Article/details/gtpjhelmyc.html

[U101] JS：classList 操作
来源：http://dali.quarkkingdee.top/Article/details/gtcwxboosc.html

el.classList.toggle("active")
来源：http://dali.jianghu66.top/Article/details/gtujcvnuqr.html

[U102] JS：本地存储
来源：http://dali.kuanghao11.cn/Article/details/gtiqclnmvq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zycfv.cn/Article/details/gtvcfrhhav.html

[U103] JS：定时器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmiyeqwl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.andypj.xyz/Article/details/gtutkuofcd.html

[U104] JS：防抖
来源：http://dali.sysykeji.top/Article/details/gtintagwqs.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gtqwcrxdcn.html

[U105] JS：节流
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxyywxer.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.wangdashe.top/Article/details/gtmfdeynbq.html

[U106] JS：日期格式化
来源：http://dali.ehwqpu.com/Article/details/gtbtrwytfb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.pycfn.com/Article/details/gtvcycyafn.html

[U107] JS：数字千分位
来源：http://dali.sweek.top/Article/details/gtnehbvnhj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gtdgogaspu.html

[U108] JS：随机整数
来源：http://dali.hammf.cn/Article/details/gtupbqgzsk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yonumen.top/Article/details/gtdqdntbfo.html

[U109] JS：数组分组
来源：http://dali.c1oappe.top/Article/details/gtlgfjmpev.html

Object.groupBy(arr, x => x.type)
来源：http://dali.iojbl.cn/Article/details/gtntdqxloc.html

[U110] JS：数组分块
来源：http://dali.wangdashe.top/Article/details/gtlznadlpb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.pycfn.com/Article/details/gtyijaixre.html

[U111] JS：对象转 Map
来源：http://dali.dashuyun.cn/Article/details/gtyfglavmu.html

new Map(Object.entries(obj))
来源：http://dali.zhongyouzk.top/Article/details/gtuekpymgj.html

[U112] JS：字符串补位
来源：http://dali.ehwqpu.com/Article/details/gtlkqfdvxk.html

"7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtdavktuty.html

[U113] JS：正则替换全部
来源：http://dali.0kj1m.cn/Article/details/gtygfyiyod.html

s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtpcyvnftc.html

[U114] JS：JSON 深比较
来源：http://dali.pycfn.com/Article/details/gtklzxuarz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtndttxjuh.html

[U115] JS：生成 UUID
来源：http://dali.birdmap.top/Article/details/gttlqpfiei.html

crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gtzjrnipaf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhoulong.xyz/Article/details/gtqcxghlhj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.andypj.xyz/Article/details/gtttphclaw.html

[U117] JS：单元测试
来源：http://dali.chenjidiqi.icu/Article/details/gtmsfdzplk.html

npm i -D vitest;  npx vitest
来源：http://dali.jqgfzy.top/Article/details/gtrhlrxcuw.html

[U118] JS：开发服务器
来源：http://dali.hnxiangtu.top/Article/details/gtfsllornp.html

npm i -D vite;  npx vite
来源：http://dali.gzhubu.top/Article/details/gtfyfzsqdx.html

[U119] JS：生产构建
来源：http://dali.feifeiyinyue.top/Article/details/gtpwcammow.html

npx vite build
来源：http://dali.hywenlv.cn/Article/details/gtwpthxmtd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yanxiufei.cn/Article/details/gtsktbvqng.html

import.meta.env.VITE_API_URL
来源：http://dali.svipenyu.cn/Article/details/gtntsnvtiv.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtmeohdhhv.html

统计汇总
来源：http://dali.sweek.top/Article/details/gtpxmtkdzk.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtycygirmj.html

按语言统计（条）：
来源：http://dali.kuanghao11.cn/Article/details/gtfomlexkd.html

Python ......... 252
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhtikgta.html

PHP ............ 252
来源：http://dali.gaohongyu789.top/Article/details/gtrveseegr.html

JavaScript ..... 252
来源：http://dali.316326.xyz/Article/details/gtzuzozufa.html

TypeScript ..... 212
来源：http://dali.hammf.cn/Article/details/gtpszrgukj.html

Java ........... 212
来源：http://dali.pycfn.com/Article/details/gtbrnvkmdv.html

Go ............. 212
来源：http://dali.tian-w.cn/Article/details/gttvscmwsp.html

Ruby ........... 212
来源：http://dali.daxiang520.top/Article/details/gtlhbgwjwy.html

C# ............. 212
来源：http://dali.dianchejie.cn/Article/details/gtplxpftty.html

C .............. 30
来源：http://dali.fzhhl.top/Article/details/gtoagdwatb.html

C++ ............ 30
来源：http://dali.xuanzx.com/Article/details/gtvdvrsnlk.html

SQL ............ 90
来源：http://dali.hnxiangtu.top/Article/details/gtdapqtjhg.html

Bash ........... 80
来源：http://dali.cdnleiting.top/Article/details/gtzaxmcoqn.html

Kotlin ......... 15
来源：http://dali.nanxuanxn.top/Article/details/gthxznvugc.html

Swift .......... 15
来源：http://dali.havefunace.top/Article/details/gtlxnfayxw.html

Lua ............ 10
来源：http://dali.zycfv.cn/Article/details/gtiufwgeja.html

Perl ........... 10
来源：http://dali.shuidangran.top/Article/details/gtrjwkwrbw.html

Scala .......... 10
来源：http://dali.hongshengwenyu.top/Article/details/gtswzfiiyg.html

------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtbpuvqvna.html

合计 ........... 2106 条
来源：http://dali.jinqigufen.top/Article/details/gtdhopqowo.html

按章节统计：
来源：http://dali.chenlongwang.top/Article/details/gtzuziebab.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jiagoushi.top/Article/details/gttzuahtpg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ybcxt.top/Article/details/gtnlatchwa.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gtklfkjgaf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.0kj1m.cn/Article/details/gtcttpjbsk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jyoumei.cn/Article/details/gthitqlvyj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.kuanghao11.cn/Article/details/gtzjpgvofh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowdtjeji.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.havefunace.top/Article/details/gtsjmjackv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gtslfhhtob.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yanxiufei.cn/Article/details/gtxvsqooqa.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gtbcmqjley.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gtwbjsvhar.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gtkoysxgkm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gaohongyu789.top/Article/details/gtalfgpvcw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gzhubu.top/Article/details/gtmnhlmquc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtodwnxhfn.html

Q SQL 专题                              90
来源：http://dali.meibo888.top/Article/details/gtyqwrrtca.html

R Bash 专题                             80
来源：http://dali.sufxvd.cn/Article/details/gtgjnmvkyd.html

S C / C++ 专题                          60
来源：http://dali.gogol.net.cn/Article/details/gtddxgsgcl.html

T 其他语言补充                          60
来源：http://dali.quarkkingdee.top/Article/details/gtrlzyewdf.html

U 高频实用片段                         120
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxuvcfnl.html

------------------------------------
来源：http://dali.tian-w.cn/Article/details/gttqlolmci.html

合计                                  2106 条
来源：http://dali.xuanzx.com/Article/details/gtqcnnokvn.html

--------------------------------------------------------------------------------
来源：http://dali.smart0.xyz/Article/details/gtlkpzmuat.html

使用提醒
来源：http://dali.nanxinkj.top/Article/details/gtnyutoesk.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtvmficsiu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cqqwz.cn/Article/details/gtalgorfcb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ppjwa.cn/Article/details/gtmtbypcaq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.andypj.xyz/Article/details/gtylvgdzmo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zycfv.cn/Article/details/gtdnpaeivv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.guannengcc.top/Article/details/gtpfekdvqq.html

—— 文件结束 ——
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvvsltvw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gteblrnbjv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.0kj1m.cn/Article/details/gtintjuczj.html

Common Programming Examples Cheat Book
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcgpdqtg.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtpgftyuby.html

【收录内容】
来源：http://dali.tian-w.cn/Article/details/gtbehxronj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.feifeiyinyue.top/Article/details/gtanpdmcnj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.pengpengdd.cyou/Article/details/gtedrssxyj.html

SQL · Bash · C · C++
来源：http://dali.hfpthk.cn/Article/details/gtmuguxqvf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.fzhhl.top/Article/details/gtlhsuoxuf.html

【使用说明】
来源：http://dali.xziqi.cn/Article/details/gtiztdjcuw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hfpthk.cn/Article/details/gtnaapesez.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cqqwz.cn/Article/details/gtzvwmjtnq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.tianlin.xyz/Article/details/gtiulnpdrj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.tanke756.top/Article/details/gtwwgtomqi.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hnxiangtu.top/Article/details/gtgsxlexin.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cashguo.top/Article/details/gtwiaotfha.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jyoumei.cn/Article/details/gtysyjwfoa.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.vqdsnc.cn/Article/details/gtrmohoovj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ivvv.top/Article/details/gtchjkchjn.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cdnleiting.top/Article/details/gtqoucxhas.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ppjwa.cn/Article/details/gtffxdjdya.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ehwqpu.com/Article/details/gtrfeqoaxn.html

【文件统计】
来源：http://dali.xuanzx.com/Article/details/gtcxhjynly.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.guannengcc.top/Article/details/gtnvovmzaw.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gtkjehpdvp.html

目  录
来源：http://dali.gotoacloud.top/Article/details/gtdnhivake.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtplsupvlf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jinqigfzy.top/Article/details/gtpucfcfiy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtlgpitnbx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.aibaodan.cn/Article/details/gtlcqklvux.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yj20258.top/Article/details/gtweiedyju.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shuidangran.top/Article/details/gtlkrlltns.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtuyfqeoov.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlgifiqv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtolygcgrr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gtgerxzutg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yvedp.cn/Article/details/gtjwmzkspu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gtulewejah.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gtrfwiyyod.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.birdmap.top/Article/details/gtkflynadd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gzhubu.top/Article/details/gtwohnlole.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xziqi.cn/Article/details/gtthexesge.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jiagoushi.top/Article/details/gtjwlrjquy.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhongyouzk.top/Article/details/gtrowmnebe.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hysaishi.cn/Article/details/gtgjolhnhp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.tanke756.top/Article/details/gtyuzaxaoj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gtrlpnfmgt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.iojbl.cn/Article/details/gtggzbizgk.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtcbulsqak.html

A. 基础语法与类型
来源：http://dali.jinqigfzy.top/Article/details/gtxipuyanf.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtttufmvol.html

[A01] Hello World
来源：http://dali.yuxming.cn/Article/details/gtmqfoxadw.html

Py:   print("Hello, World!")
来源：http://dali.fengsongda.top/Article/details/gtviprnxej.html

PHP:  echo "Hello, World!";
来源：http://dali.andypj.xyz/Article/details/gtztzgyssv.html

JS:   console.log("Hello, World!");
来源：http://dali.yj20258888.top/Article/details/gtseuivlqj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xuetiantiany.cn/Article/details/gtfvsvipxg.html

Java: System.out.println("Hello, World!");
来源：http://dali.tian-w.cn/Article/details/gtfkryrolf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xylfe.cn/Article/details/gtmhliffzx.html

Ruby: puts "Hello, World!"
来源：http://dali.jiagoushi.top/Article/details/gtipkwuxhc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.quarkkingdee.top/Article/details/gtgnkcwbhh.html

[A02] 变量声明与赋值
来源：http://dali.xuanzx.com/Article/details/gthbulpyjh.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.316326.xyz/Article/details/gtlsevqoqe.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.andypj.xyz/Article/details/gtsntlvtao.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gtuacxztog.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgbrantz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cdnleiting.top/Article/details/gtxenwbycd.html

Go:   name := "Alex"; age := 20
来源：http://dali.hnxiangtu.top/Article/details/gtqzkyunzr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.tian-w.cn/Article/details/gtqfetpkgn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.aizwys.cn/Article/details/gtkrxmmebw.html

[A03] 常量定义
来源：http://dali.guowangkeji.top/Article/details/gtlyeufpsq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.nanxinkj.top/Article/details/gtcighqlut.html

PHP:  const PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtrszkvhjy.html

JS:   const PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtdjxeffyc.html

TS:   const PI: number = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtlvtcsssm.html

Java: static final double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtoqtohsxq.html

Go:   const PI = 3.14159
来源：http://dali.yuanzhike.top/Article/details/gtydaewkzo.html

Ruby: PI = 3.14159
来源：http://dali.316326.xyz/Article/details/gtwfuzwota.html

C#:   const double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtkhleaslz.html

[A04] 判断变量类型
来源：http://dali.ppjwa.cn/Article/details/gtejucimco.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.tanke756.top/Article/details/gtwihncsjp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jqgfzy.top/Article/details/gtopdnoete.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.havefunace.top/Article/details/gtvdgxbmgz.html

TS:   typeof x; x instanceof Date
来源：http://dali.chenjidiqi.icu/Article/details/gtyfxcdabl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhongyouzk.top/Article/details/gtupmjclkm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xuetiantiany.cn/Article/details/gtrhjqklck.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cashguo.top/Article/details/gtzbdgaohq.html

C#:   x.GetType().Name; x is int
来源：http://dali.hammf.cn/Article/details/gtmorawayd.html

[A05] 整数除法与取模
来源：http://dali.jqgfzy.top/Article/details/gtbjlzunaf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xziqi.cn/Article/details/gtmwmmcsbi.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gtyxmwdoeh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gtnjohmjul.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtsysftkvt.html

Java: 7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gtcpjciruq.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtlabwskop.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtrplapaks.html

C#:   7 / 2; 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gtnojypvkv.html

[A06] 字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmyluvyyd.html

Py:   int("42"); float("3.14")
来源：http://dali.sxryk.cn/Article/details/gtdpfzpzrr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.quarkkingdee.top/Article/details/gttqbfvild.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jinqigufen.top/Article/details/gtoyajqdmn.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zycfv.cn/Article/details/gtpwmtqiqg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.haohaochexian.top/Article/details/gtoihlmeqz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcqhaxjd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.haohaochexian.top/Article/details/gtiwxvpsft.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.snrcjt.cn/Article/details/gtcldistpa.html

[A07] 数字转字符串
来源：http://dali.0kj1m.cn/Article/details/gtxmbhrkui.html

Py:   str(42)
来源：http://dali.nanxuanxn.top/Article/details/gtpyrrkirk.html

PHP:  (string) 42; strval(42)
来源：http://dali.yj202588.top/Article/details/gtqzzgehha.html

JS:   String(42); (42).toString()
来源：http://dali.hysaishi.cn/Article/details/gtnymesdwo.html

TS:   String(42)
来源：http://dali.ivvv.top/Article/details/gtcujuztww.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaujuewdu.html

Go:   strconv.Itoa(42)
来源：http://dali.yangfankeji.com/Article/details/gtykjhyoxl.html


<!-- 参考信息 -->