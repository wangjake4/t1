代发 wailian999

[U55] PHP：match 表达式
来源：http://dali.hnqzz.top/Article/details/gtjnptmtyi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj202588.top/Article/details/gtjwrlxvkg.html

[U56] PHP：命名参数
来源：http://dali.ehwqpu.com/Article/details/gtpgfxzphi.html

f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtocfqfulb.html

[U57] PHP：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtdkcpzvca.html

"值: {$a}"
来源：http://dali.xylfe.cn/Article/details/gtsywdpbpp.html

[U58] PHP：数组三件套
来源：http://dali.jyoumei.cn/Article/details/gtzbdtycxq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.haohaochexian.top/Article/details/gthjwjifqs.html

[U59] PHP：自定义排序
来源：http://dali.dianchejie.cn/Article/details/gtdzxvezvg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgfzy.top/Article/details/gtgvupptuh.html

[U60] PHP：JSON 编解码
来源：http://dali.jinghuilouyu.cn/Article/details/gtyakhudvp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.snrcjt.cn/Article/details/gtunwdayjz.html

[U61] PHP：正则
来源：http://dali.xuanzx.com/Article/details/gtzxfqsyxc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.aibaodan.cn/Article/details/gtvpufskwq.html

[U62] PHP：日期对象
来源：http://dali.dianchejie.cn/Article/details/gtcyiasfld.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jqgufenzy.top/Article/details/gtcswsfjiv.html

[U63] PHP：文件读写
来源：http://dali.zycfv.cn/Article/details/gtvgzlhvti.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhixingplan.top/Article/details/gtgyyrtjmh.html

[U64] PHP：目录遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtqydrqxzy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj20258.top/Article/details/gtvegdediy.html

[U65] PHP：会话
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnypvxyt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtgtbxmojq.html

[U66] PHP：设置 Cookie
来源：http://dali.zhiwuduotai.top/Article/details/gtsgepqttk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.guowangkeji.top/Article/details/gtoipcqefq.html

[U67] PHP：处理文件上传
来源：http://dali.meibo888.top/Article/details/gtyzalszrr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jinqigufen.top/Article/details/gtwumivmux.html

[U68] PHP：PDO 连接
来源：http://dali.cdnleiting.top/Article/details/gtvkawfvli.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhengqikj.top/Article/details/gtlsjbrnts.html

[U69] PHP：PDO 预处理
来源：http://dali.redwolf501.top/Article/details/gtktayjvue.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cucudq.cn/Article/details/gtyvxmkkln.html

[U70] PHP：PDO 事务
来源：http://dali.yuanzhike.top/Article/details/gtpwybckav.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xuanzx.com/Article/details/gtugmblwtx.html

[U71] PHP：抛出异常
来源：http://dali.chenlongwang.top/Article/details/gtcxzskdfq.html

throw new RuntimeException("失败", 500);
来源：http://dali.cdnleiting.top/Article/details/gtzojjnbru.html

[U72] PHP：写错误日志
来源：http://dali.wangdashe.top/Article/details/gtfxehstxw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cheryme.top/Article/details/gtgxxxzbxu.html

[U73] PHP：读取 ini 配置
来源：http://dali.nanxinkj.top/Article/details/gtdjplrzym.html

parse_ini_file("config.ini", true)
来源：http://dali.jyoumei.cn/Article/details/gtnbrhxzsu.html

[U74] PHP：读取环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayebhoaq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhoulong.xyz/Article/details/gtccsaqody.html

[U75] PHP：依赖注入
来源：http://dali.zdqjudy.top/Article/details/gtlxzhovth.html

composer require psr/container
来源：http://dali.tianlin.xyz/Article/details/gtyqwockyi.html

[U76] PHP：简单路由
来源：http://dali.jqgufenzy.top/Article/details/gtsvthxzeu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.gaohongyu789.top/Article/details/gtxzexnsvh.html

[U77] PHP：模板渲染
来源：http://dali.xylfe.cn/Article/details/gthatudcna.html

composer require twig/twig
来源：http://dali.dashuyun.cn/Article/details/gtbtenmzpg.html

[U78] PHP：单元测试
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhxnceor.html

composer require --dev phpunit/phpunit
来源：http://dali.guowangkeji.top/Article/details/gtvnxlogrk.html

[U79] PHP：静态分析
来源：http://dali.shangyingyoupin.top/Article/details/gtgusfspez.html

composer require --dev phpstan/phpstan
来源：http://dali.nanxinkj.top/Article/details/gtembaqekc.html

[U80] PHP：代码规范修复
来源：http://dali.snrcjt.cn/Article/details/gttltnkyar.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jyoumei.cn/Article/details/gtwyxiinad.html

[U81] JS：初始化项目
来源：http://dali.gogol.net.cn/Article/details/gthgvvogdl.html

npm init -y;  npm i express
来源：http://dali.xylfe.cn/Article/details/gtltebujzg.html

[U82] JS：package.json 脚本
来源：http://dali.smart0.xyz/Article/details/gtkmznhpfk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhixingplan.top/Article/details/gtqvpqulej.html

[U83] JS：ES Module 导入导出
来源：http://dali.iojbl.cn/Article/details/gtjdiqpesc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hywenlv.cn/Article/details/gtzjozhkdw.html

[U84] JS：CommonJS 写法
来源：http://dali.jlsjyb.cn/Article/details/gtpaybejnp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.svipenyu.cn/Article/details/gtcqkgxzqm.html

[U85] JS：可选链
来源：http://dali.meibo888.top/Article/details/gtdjxohhje.html

a?.b?.c
来源：http://dali.zycfv.cn/Article/details/gttxqilieq.html

[U86] JS：空值合并
来源：http://dali.316326.xyz/Article/details/gthldrhpur.html

a ?? b
来源：http://dali.tanke756.top/Article/details/gtuimbqmot.html

[U87] JS：解构默认值
来源：http://dali.wangshuangyany.cn/Article/details/gtejrnwjau.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhiwuduotai.top/Article/details/gtijaektjc.html

[U88] JS：对象展开合并
来源：http://dali.cashguo.top/Article/details/gtlpbymuba.html

{ ...a, ...b }
来源：http://dali.xziqi.cn/Article/details/gttlntjfcg.html

[U89] JS：数组去重
来源：http://dali.yonumen.top/Article/details/gtdlfgknvv.html

[...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtbqdqlsde.html

[U90] JS：数字数组排序
来源：http://dali.iojbl.cn/Article/details/gtcntoxifz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwjjhqyq.html

[U91] JS：对象键值遍历
来源：http://dali.wangdashe.top/Article/details/gtazykadac.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhiwuduotai.top/Article/details/gtsekhltwv.html

[U92] JS：深拷贝
来源：http://dali.hysaishi.cn/Article/details/gthzzxpvjy.html

structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtvwmecoxp.html

[U93] JS：模板字符串
来源：http://dali.jinqigufen.top/Article/details/gtcqrxxrsm.html

`共 ${n} 条`
来源：http://dali.ppjwa.cn/Article/details/gtnyrtahsl.html

[U94] JS：箭头函数
来源：http://dali.xinyue.icu/Article/details/gtshrorlrn.html

const double = x => x * 2;
来源：http://dali.haohaochexian.top/Article/details/gtpdpzmaqo.html

[U95] JS：Promise 包装
来源：http://dali.zhiwuduotai.top/Article/details/gtrlfzrmrs.html

new Promise((resolve, reject) => {})
来源：http://dali.havefunace.top/Article/details/gtqmbovsoa.html

[U96] JS：async/await 与异常
来源：http://dali.svipenyu.cn/Article/details/gtwyprjmev.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtjsegyynk.html

[U97] JS：并发请求
来源：http://dali.gotoacloud.top/Article/details/gtglwedjaa.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtotcyzifs.html

[U98] JS：fetch 带 JSON
来源：http://dali.hfpthk.cn/Article/details/gtqmerauhi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jqgfzy.top/Article/details/gtshsskgtl.html

[U99] JS：事件监听
来源：http://dali.yongpay.top/Article/details/gtiksshtmw.html

el.addEventListener("click", e => {})
来源：http://dali.havefunace.top/Article/details/gteibscjub.html

[U100] JS：DOM 查询
来源：http://dali.chenjidiqi.icu/Article/details/gtrsfnxddq.html

document.querySelector(".item")
来源：http://dali.aizwys.cn/Article/details/gtltooybae.html

[U101] JS：classList 操作
来源：http://dali.daxiang520.top/Article/details/gtiiqfvoed.html

el.classList.toggle("active")
来源：http://dali.zhixingplan.top/Article/details/gtcjjcrhxw.html

[U102] JS：本地存储
来源：http://dali.redwolf501.top/Article/details/gtrenvabsd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.haohaochexian.top/Article/details/gthfhebzzt.html

[U103] JS：定时器
来源：http://dali.gaohongyu789.top/Article/details/gtfiwdycpf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cqqwz.cn/Article/details/gtprcbddgw.html

[U104] JS：防抖
来源：http://dali.wangshuangyany.cn/Article/details/gtngimgywp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gtzjfsxkbf.html

[U105] JS：节流
来源：http://dali.jianghu66.top/Article/details/gtkiurgfgt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ivvv.top/Article/details/gtpoyfgowf.html

[U106] JS：日期格式化
来源：http://dali.bjfxy.top/Article/details/gtyrfzelln.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.tianlin.xyz/Article/details/gtqauqsnpc.html

[U107] JS：数字千分位
来源：http://dali.mhx1999.top/Article/details/gtmnzoykic.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gtjvecjbeo.html

[U108] JS：随机整数
来源：http://dali.gzhubu.top/Article/details/gtcrcemrwb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.smart0.xyz/Article/details/gteunibzjd.html

[U109] JS：数组分组
来源：http://dali.fzhhl.top/Article/details/gtixnuqxec.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gtjbwyrwrb.html

[U110] JS：数组分块
来源：http://dali.yj202588.top/Article/details/gtkjukzcse.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gtergmecue.html

[U111] JS：对象转 Map
来源：http://dali.gaohongyu789.top/Article/details/gtnrtnhefp.html

new Map(Object.entries(obj))
来源：http://dali.xziqi.cn/Article/details/gttlblkqjb.html

[U112] JS：字符串补位
来源：http://dali.zhoulong.xyz/Article/details/gtboyjdebk.html

"7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gtqrkzpmuw.html

[U113] JS：正则替换全部
来源：http://dali.nanxuanxn.top/Article/details/gtxgwmubuz.html

s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtdhyfptjt.html

[U114] JS：JSON 深比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqisgrav.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhoulong.xyz/Article/details/gtespnemmr.html

[U115] JS：生成 UUID
来源：http://dali.yvedp.cn/Article/details/gtmuxxmops.html

crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtfzmksoxe.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.havefunace.top/Article/details/gtckpyajaa.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtsuoxdbqh.html

[U117] JS：单元测试
来源：http://dali.xylfe.cn/Article/details/gtwmnqizjb.html

npm i -D vitest;  npx vitest
来源：http://dali.gogol.net.cn/Article/details/gtifkklynk.html

[U118] JS：开发服务器
来源：http://dali.hnqzz.top/Article/details/gtgjofbthq.html

npm i -D vite;  npx vite
来源：http://dali.zycfv.cn/Article/details/gtrhcqgkgb.html

[U119] JS：生产构建
来源：http://dali.hnxiangtu.top/Article/details/gtywicfvpf.html

npx vite build
来源：http://dali.wangdashe.top/Article/details/gtrvopdqlx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzzhthjr.html

import.meta.env.VITE_API_URL
来源：http://dali.yonumen.top/Article/details/gtdddmahym.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtsnypvmxo.html

统计汇总
来源：http://dali.ybcxt.top/Article/details/gtppwyiseg.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gthycbilzl.html

按语言统计（条）：
来源：http://dali.yanxiufei.cn/Article/details/gtybprigxe.html

Python ......... 252
来源：http://dali.hnqzz.top/Article/details/gtowyhcoki.html

PHP ............ 252
来源：http://dali.yonumen.top/Article/details/gtplcfjxgm.html

JavaScript ..... 252
来源：http://dali.zdqjudy.top/Article/details/gtciqlbkwy.html

TypeScript ..... 212
来源：http://dali.hnqzz.top/Article/details/gtzdvwtukn.html

Java ........... 212
来源：http://dali.haohaochexian.top/Article/details/gtpqaxjhzg.html

Go ............. 212
来源：http://dali.zhoulong.xyz/Article/details/gtkwbydzxj.html

Ruby ........... 212
来源：http://dali.mhx1999.top/Article/details/gttnpexjns.html

C# ............. 212
来源：http://dali.cheryme.top/Article/details/gtepbyreuq.html

C .............. 30
来源：http://dali.yj20258.top/Article/details/gtkvzuxtfk.html

C++ ............ 30
来源：http://dali.yuxming.cn/Article/details/gtxypbgcdd.html

SQL ............ 90
来源：http://dali.cdnleiting.top/Article/details/gtziiwvtws.html

Bash ........... 80
来源：http://dali.zhixingplan.top/Article/details/gtpcazwcjk.html

Kotlin ......... 15
来源：http://dali.kuanghao11.cn/Article/details/gtfcgmbhwu.html

Swift .......... 15
来源：http://dali.bjfxy.top/Article/details/gtwivdovnk.html

Lua ............ 10
来源：http://dali.yuanzhike.top/Article/details/gtqcolwyfc.html

Perl ........... 10
来源：http://dali.meibo888.top/Article/details/gtwusvqpsr.html

Scala .......... 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdkpiaqck.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gtetfeesfa.html

合计 ........... 2106 条
来源：http://dali.yongpay.top/Article/details/gtdezckvvf.html

按章节统计：
来源：http://dali.jianghu66.top/Article/details/gtqyfiwlwq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cqqwz.cn/Article/details/gtdbgroeov.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.birdmap.top/Article/details/gtsfmopgqa.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ybcxt.top/Article/details/gttatxovoe.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yongpay.top/Article/details/gtakxrbmtj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ivvv.top/Article/details/gtrnxqclgc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jiagoushi.top/Article/details/gtppyeavsr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xziqi.cn/Article/details/gtpzbqoekg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.kuanghao11.cn/Article/details/gtgoyqamfs.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gtjvbetltd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hnxiangtu.top/Article/details/gtyjzyknby.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gttcwdyzig.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gtzkwrijmb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gtmzixfmry.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jiagoushi.top/Article/details/gtpapksrzp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.feifeiyinyue.top/Article/details/gtmctsbyin.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gtsnbljxnz.html

Q SQL 专题                              90
来源：http://dali.hongshengwenyu.top/Article/details/gtdsqjcpji.html

R Bash 专题                             80
来源：http://dali.jinyuanbaomall.cn/Article/details/gthveygtyc.html

S C / C++ 专题                          60
来源：http://dali.hnqzz.top/Article/details/gtqxekmsmn.html

T 其他语言补充                          60
来源：http://dali.ydzc1.top/Article/details/gtrcntitst.html

U 高频实用片段                         120
来源：http://dali.quarkkingdee.top/Article/details/gtqdtsiodj.html

------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfiicxie.html

合计                                  2106 条
来源：http://dali.xuanzx.com/Article/details/gtmsmosutd.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcoellfgg.html

使用提醒
来源：http://dali.mhx1999.top/Article/details/gtyktvagtm.html

--------------------------------------------------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshcqkcnq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.quarkkingdee.top/Article/details/gtuttbqpze.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinqigfzy.top/Article/details/gtgspdbeqp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.daria6918.cn/Article/details/gtgiveeabd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhongyouzk.top/Article/details/gtsyarxvxl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hnqzz.top/Article/details/gthxresemv.html

—— 文件结束 ——
来源：http://dali.jlsjyb.cn/Article/details/gtznbrgkur.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtwlpbnsex.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.meibo888.top/Article/details/gtkdtxvwmb.html

Common Programming Examples Cheat Book
来源：http://dali.havefunace.top/Article/details/gttvmwbgbv.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtzfrnplis.html

【收录内容】
来源：http://dali.snrcjt.cn/Article/details/gtkqrhwzdn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jqgfzy.top/Article/details/gtoanzkqas.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.svipenyu.cn/Article/details/gtubnvfnrs.html

SQL · Bash · C · C++
来源：http://dali.c1oappe.top/Article/details/gtngkzwxiq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.haohaochexian.top/Article/details/gthejvymqv.html

【使用说明】
来源：http://dali.zhixingplan.top/Article/details/gtocrjenps.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ivvv.top/Article/details/gtfcftxhib.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hysaishi.cn/Article/details/gtekzurzia.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yueranfly.top/Article/details/gtaqphfaik.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jlsjyb.cn/Article/details/gthkqnahgi.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.haohaochexian.top/Article/details/gtulubtvsx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenjidiqi.icu/Article/details/gtvolwlywv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.wangdashe.top/Article/details/gtjvygrjzu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cucudq.cn/Article/details/gtizqxpzru.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnorwwvmy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cashguo.top/Article/details/gthzjtdnum.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ehwqpu.com/Article/details/gtxjuzdqmj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.dashuyun.cn/Article/details/gturozurkh.html

【文件统计】
来源：http://dali.dashuyun.cn/Article/details/gtoaefrofw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xinyue.icu/Article/details/gtmvaebgxd.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtzqsppime.html

目  录
来源：http://dali.yueranfly.top/Article/details/gtsanodgly.html

--------------------------------------------------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gtschgtipf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ehwqpu.com/Article/details/gtpluojklb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.haohaochexian.top/Article/details/gththnyqsw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zdqjudy.top/Article/details/gtaifmoaqp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ehwqpu.com/Article/details/gtohcsmpki.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.daxiang520.top/Article/details/gtgppxwqan.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zdqjudy.top/Article/details/gthbevoebs.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.0kj1m.cn/Article/details/gtavjrdige.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gtaimmdfhq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.birdmap.top/Article/details/gtkygkamom.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.gogol.net.cn/Article/details/gtstardijg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtlqologxg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gtkumfnqeo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtmlhxzqbe.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shuidangran.top/Article/details/gtriropoka.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hysaishi.cn/Article/details/gtfvvlmsti.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gtqonoxduz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.nanxuanxn.top/Article/details/gtbposhkcm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gtwmlqmqkf.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhoulong.xyz/Article/details/gtmiudzpqy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gotoacloud.top/Article/details/gtbifotpul.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtpjltowtb.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtdvblersf.html

A. 基础语法与类型
来源：http://dali.yj20258888.top/Article/details/gtioqmooon.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfdxyklf.html

[A01] Hello World
来源：http://dali.sysykeji.top/Article/details/gtygsmlhxd.html

Py:   print("Hello, World!")
来源：http://dali.cheryme.top/Article/details/gtwssuydmg.html

PHP:  echo "Hello, World!";
来源：http://dali.jqgfzy.top/Article/details/gtpxjqtjha.html

JS:   console.log("Hello, World!");
来源：http://dali.yj20258888.top/Article/details/gtdaktlcne.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.feifeiyinyue.top/Article/details/gtggctapou.html

Java: System.out.println("Hello, World!");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcashxwfl.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhoulong.xyz/Article/details/gtbpdihmbo.html

Ruby: puts "Hello, World!"
来源：http://dali.yj202588.top/Article/details/gtagrdskrc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jinqigufen.top/Article/details/gtbtwbaoye.html

[A02] 变量声明与赋值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezvvwcmz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gotoacloud.top/Article/details/gtzsjuvdhb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj202588.top/Article/details/gtkvbkuhmz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cucudq.cn/Article/details/gtnodbticq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zdqjudy.top/Article/details/gtgebxlmsr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yvedp.cn/Article/details/gtqxblxrne.html

Go:   name := "Alex"; age := 20
来源：http://dali.ivvv.top/Article/details/gtlmkwcrvc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.tian-w.cn/Article/details/gtxuyqsrdu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yueranfly.top/Article/details/gtpprrrsvu.html

[A03] 常量定义
来源：http://dali.ybcxt.top/Article/details/gtxpwvwhah.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.vqdsnc.cn/Article/details/gtolkaxqcb.html

PHP:  const PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtksbryqbi.html

JS:   const PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtgpmiqzdp.html

TS:   const PI: number = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtkntanyns.html

Java: static final double PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtnjfshmut.html

Go:   const PI = 3.14159
来源：http://dali.fengsongda.top/Article/details/gtfufkjwic.html

Ruby: PI = 3.14159
来源：http://dali.daxiang520.top/Article/details/gttznjeeyb.html

C#:   const double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtmszmdhnv.html

[A04] 判断变量类型
来源：http://dali.guowangkeji.top/Article/details/gtcvfzvats.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jyoumei.cn/Article/details/gtkyipabmd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.daxiang520.top/Article/details/gtwijpbsfh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdhwxlve.html

TS:   typeof x; x instanceof Date
来源：http://dali.shangyingyoupin.top/Article/details/gtlhqxaiml.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zycfv.cn/Article/details/gtpcmmgplg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.tanke756.top/Article/details/gtstengzmj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yj20258888.top/Article/details/gtuyrmcbvo.html

C#:   x.GetType().Name; x is int
来源：http://dali.yanxiufei.cn/Article/details/gtrismliec.html

[A05] 整数除法与取模
来源：http://dali.jiagoushi.top/Article/details/gtgxzjzrsn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.c1oappe.top/Article/details/gtmlyrzfig.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvyfmlap.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtropbktbx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ivvv.top/Article/details/gtdpvzunxz.html

Java: 7 / 2; 7 % 2
来源：http://dali.nwbrower.top/Article/details/gtpzxflmlp.html

Go:   7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gtuphfzeks.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.cheryme.top/Article/details/gtkryfrydk.html

C#:   7 / 2; 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtlyxpnmhy.html

[A06] 字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgzbjxjf.html

Py:   int("42"); float("3.14")
来源：http://dali.jinqigufen.top/Article/details/gthatwozes.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shangyingyoupin.top/Article/details/gtjpzzvsaw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jlsjyb.cn/Article/details/gtdlrcumrm.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.aizwys.cn/Article/details/gtzgxkbzhk.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhongyouzk.top/Article/details/gttutbstio.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yanxiufei.cn/Article/details/gtkcrtxwws.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.nwbrower.top/Article/details/gtxhexwfdb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gtidaobvsl.html

[A07] 数字转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtyjdqomho.html

Py:   str(42)
来源：http://dali.jlsjyb.cn/Article/details/gtixqivqox.html

PHP:  (string) 42; strval(42)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttluvcwye.html

JS:   String(42); (42).toString()
来源：http://dali.gaohongyu789.top/Article/details/gtfvywoyiy.html

TS:   String(42)
来源：http://dali.guannengcc.top/Article/details/gtgafcjhdk.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.vqdsnc.cn/Article/details/gtmemsamgz.html

Go:   strconv.Itoa(42)
来源：http://dali.zhiwuduotai.top/Article/details/gtwyfvotss.html


<!-- 参考信息 -->