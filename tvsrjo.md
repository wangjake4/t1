代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hammf.cn/Article/details/gt2wnwbiamp.html

[Q26] 计数
来源：http://dali.xziqi.cn/Article/details/gt2vczcooam.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2yfmfhubn.html

[Q27] 条件计数
来源：http://dali.hfpthk.cn/Article/details/gt2qjxncwke.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2avgogdoh.html

[Q28] 求和与平均
来源：http://dali.jlsjyb.cn/Article/details/gt2gfpwroxk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2hajpfrzy.html

[Q29] 最大最小值
来源：http://dali.gzhubu.top/Article/details/gt2veudhqfa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2sscpabat.html

[Q30] 分组统计
来源：http://dali.iojbl.cn/Article/details/gt2dathdcxv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gt2znnruzfh.html

[Q31] 分组后过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2zhetljdd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yangfankeji.com/Article/details/gt2vyxczyon.html

[Q32] 分组拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gt2rynihocg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gt2rjzpfeqc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenlongwang.top/Article/details/gt2vbkoeaaw.html

[Q33] 多列分组
来源：http://dali.hfpthk.cn/Article/details/gt2arfprhcs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cashguo.top/Article/details/gt2ewvvnxbo.html

[Q34] 每组取第一条
来源：http://dali.zhixingplan.top/Article/details/gt2qrpqrtzc.html

SELECT * FROM (
来源：http://dali.aizwys.cn/Article/details/gt2jporhzhe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gzhubu.top/Article/details/gt2rowafmsu.html

) t WHERE rn = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2bsjiiuxp.html

[Q35] 内连接
来源：http://dali.svipenyu.cn/Article/details/gt2fyvzpzzm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ufyqirls.html

[Q36] 左连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vtpssint.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gt2wzudetww.html

[Q37] 右连接
来源：http://dali.aizwys.cn/Article/details/gt2hjotftle.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvjpuwju.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxuanxn.top/Article/details/gt2gmpizymb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ehwqpu.com/Article/details/gt2vzzsjxnz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhiwuduotai.top/Article/details/gt2evelldhq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fzhhl.top/Article/details/gt2pkzyizop.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.mhx1999.top/Article/details/gt2yfghlvvv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2govnxsip.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj20258.top/Article/details/gt2svtnofka.html

[Q41] 多表连接
来源：http://dali.nwbrower.top/Article/details/gt2buiskbvs.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gotoacloud.top/Article/details/gt2gfcvdvox.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sclgpvuz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj202588.top/Article/details/gt2lbshehgc.html

[Q42] 连接条件附加过滤
来源：http://dali.ppjwa.cn/Article/details/gt2jriihofe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yonumen.top/Article/details/gt2rmlrpvxr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gt2apugxcrv.html

[Q43] 标量子查询
来源：http://dali.guowangkeji.top/Article/details/gt2kfzfedhc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dianchejie.cn/Article/details/gt2bqdkcdht.html

[Q44] IN 子查询
来源：http://dali.pengpengdd.cyou/Article/details/gt2ghwkbcsh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ajgxjpnq.html

[Q45] EXISTS 判断存在
来源：http://dali.snrcjt.cn/Article/details/gt2frgbllke.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gt2yjggmtum.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tanke756.top/Article/details/gt2eddsmojc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gt2fimrbclt.html

[Q47] 与平均值比较
来源：http://dali.jinqigufen.top/Article/details/gt2dxxrydsr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cashguo.top/Article/details/gt2wpnoiahk.html

[Q48] CTE 公用表表达式
来源：http://dali.yj202588.top/Article/details/gt2vuzafohg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zycfv.cn/Article/details/gt2hfbtdfuo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgfzy.top/Article/details/gt2lxftlnzp.html

[Q49] 更新单行
来源：http://dali.cqqwz.cn/Article/details/gt2yihsajtz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oeyoksdo.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2svvmtdli.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jjewyeiu.html

[Q51] 用子查询更新
来源：http://dali.guannengcc.top/Article/details/gt2khbclxik.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sysykeji.top/Article/details/gt2giolphso.html

[Q52] 删除指定行
来源：http://dali.xuetiantiany.cn/Article/details/gt2stbnjxgn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gt2utjgoqjg.html

[Q53] 按条件删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cjxhrwby.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.vqdsnc.cn/Article/details/gt2mfiwloha.html

[Q54] 清空表
来源：http://dali.xziqi.cn/Article/details/gt2jnpmpjkv.html

TRUNCATE TABLE logs;
来源：http://dali.aizwys.cn/Article/details/gt2eocxtqfo.html

[Q55] 排名（并列占位）
来源：http://dali.yj202588.top/Article/details/gt2kodezppw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gt2kryxdztd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yanxiufei.cn/Article/details/gt2uimkvrxt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gt2tsudzmmw.html

[Q57] 行号
来源：http://dali.chenjidiqi.icu/Article/details/gt2urhxkgzh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2xeifbhif.html

[Q58] 累计求和
来源：http://dali.gaohongyu789.top/Article/details/gt2moquezdd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2ptlryepg.html

[Q59] 分组内累计
来源：http://dali.cqqwz.cn/Article/details/gt2jxhlptlm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2uqrpjvlt.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qybafklh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258.top/Article/details/gt2cucrgqdu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kqwbeoep.html

[Q61] 移动平均
来源：http://dali.pengpengdd.cyou/Article/details/gt2ytsneeia.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2ufuzqsja.html

[Q62] 分组占比
来源：http://dali.ppjwa.cn/Article/details/gt2uenpykyr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gt2hcecvguu.html

[Q63] 开启事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xbnagddy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hysaishi.cn/Article/details/gt2mvlzgwpx.html

[Q64] 提交事务
来源：http://dali.redwolf501.top/Article/details/gt2jcciacdt.html

COMMIT;
来源：http://dali.redwolf501.top/Article/details/gt2wbmgzhtb.html

[Q65] 回滚事务
来源：http://dali.hnxiangtu.top/Article/details/gt2qcanfciy.html

ROLLBACK;
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjqrncut.html

[Q66] 行锁查询
来源：http://dali.mhx1999.top/Article/details/gt2rmxflupy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cheryme.top/Article/details/gt2gznhnwno.html

[Q67] 设置隔离级别
来源：http://dali.wangshuangyany.cn/Article/details/gt2oefxipwo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.0kj1m.cn/Article/details/gt2oabbdvbz.html

[Q68] 保存点
来源：http://dali.yvedp.cn/Article/details/gt2uzfnzdwf.html

SAVEPOINT sp1;
来源：http://dali.jiagoushi.top/Article/details/gt2ezhhcbmp.html

ROLLBACK TO sp1;
来源：http://dali.hnqzz.top/Article/details/gt2kcuptkwg.html

[Q69] 查看执行计划
来源：http://dali.hnqzz.top/Article/details/gt2hbfwppxy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhiwuduotai.top/Article/details/gt2wpbyqeph.html

[Q70] 更新统计信息
来源：http://dali.tianlin.xyz/Article/details/gt2dvcrkles.html

ANALYZE TABLE users;
来源：http://dali.ybcxt.top/Article/details/gt2zknapczi.html

[Q71] 查看建表语句
来源：http://dali.yanxiufei.cn/Article/details/gt2nkkgdeft.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tobtmnbb.html

[Q72] 查看索引
来源：http://dali.havefunace.top/Article/details/gt2vglcpbel.html

SHOW INDEX FROM users;
来源：http://dali.meibo888.top/Article/details/gt2uhrjnukf.html

[Q73] 查看表状态
来源：http://dali.jinqigfzy.top/Article/details/gt2kkvsdokp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gotoacloud.top/Article/details/gt2vlabtelk.html

[Q74] 强制使用索引
来源：http://dali.c1oappe.top/Article/details/gt2snqhczok.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ivvv.top/Article/details/gt2apqadprs.html

[Q75] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gt2fckcjexk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2kooloomy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ydzc1.top/Article/details/gt2lcgsrrlf.html

[Q76] 按天统计
来源：http://dali.ppjwa.cn/Article/details/gt2dhepwhnf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fengsongda.top/Article/details/gt2ulrzkrvu.html

[Q77] 时间加减
来源：http://dali.hfpthk.cn/Article/details/gt2pzgqxzro.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigufen.top/Article/details/gt2mlpvsigc.html

[Q78] 当前时间
来源：http://dali.jlsjyb.cn/Article/details/gt2shzoddfa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2betwwszk.html

[Q79] 字符串拼接
来源：http://dali.cheryme.top/Article/details/gt2hzoiexwk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fengsongda.top/Article/details/gt2qhaipmqc.html

[Q80] 字符串截取
来源：http://dali.kuanghao11.cn/Article/details/gt2jyyeoxsu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2nvzzxckb.html

[Q81] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gt2zahewrcx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2ofnakyhk.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgufenzy.top/Article/details/gt2uweonwxx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2pyckklwr.html

[Q83] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gt2kjmwtkww.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2mccranek.html

[Q84] 去除首尾空格
来源：http://dali.yangfankeji.com/Article/details/gt2uhawesbi.html

SELECT TRIM(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2ijpywgjr.html

[Q85] 数值取整
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwqlqqfk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fengsongda.top/Article/details/gt2lfumvchy.html

[Q86] 读取 JSON 字段
来源：http://dali.cdnleiting.top/Article/details/gt2ewdvucnm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yangfankeji.com/Article/details/gt2sqnvravr.html

[Q87] JSON 字段做条件
来源：http://dali.jyoumei.cn/Article/details/gt2onahdkcp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.c1oappe.top/Article/details/gt2kbjegoud.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenzaomai.com/Article/details/gt2xncftjni.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tianlin.xyz/Article/details/gt2ntnecvpi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2ndaqjehl.html

[Q89] 判断表是否存在
来源：http://dali.jyoumei.cn/Article/details/gt2zwajvvrv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gt2uiqdvyrh.html

[Q90] 生成序号列
来源：http://dali.daxiang520.top/Article/details/gt2rdxrbqiu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnqzz.top/Article/details/gt2wwknbysv.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2vxykbngy.html

R. Bash 专题
来源：http://dali.feifeiyinyue.top/Article/details/gt2tatxnitn.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2yqclxjpb.html

[R01] shebang 与严格模式
来源：http://dali.kuanghao11.cn/Article/details/gt2arzandrc.html

#!/usr/bin/env bash
来源：http://dali.redwolf501.top/Article/details/gt2pwogimkz.html

set -euo pipefail
来源：http://dali.pycfn.com/Article/details/gt2ztjwlton.html

[R02] 变量赋值与使用
来源：http://dali.ehwqpu.com/Article/details/gt2sthhypej.html

name="Tom"; echo "$name"
来源：http://dali.jinqigfzy.top/Article/details/gt2styhurtn.html

[R03] 只读变量
来源：http://dali.fengsongda.top/Article/details/gt2jhlxwugd.html

readonly PI=3.14
来源：http://dali.hongshengwenyu.top/Article/details/gt2miqfieov.html

[R04] 位置参数
来源：http://dali.gogol.net.cn/Article/details/gt2tvgupiqt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.meibo888.top/Article/details/gt2zjfoxhlw.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gt2kpvlpikc.html

name="${1:-default}"
来源：http://dali.zdqjudy.top/Article/details/gt2kwuzquns.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uzonbrxa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gt2asoowqmm.html

[R07] if 判断文件
来源：http://dali.quarkkingdee.top/Article/details/gt2kxddmltt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnqzz.top/Article/details/gt2adaiogtv.html

[R08] 数值比较
来源：http://dali.fzhhl.top/Article/details/gt2fllqvasq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ehwqpu.com/Article/details/gt2fvrhhbba.html

[R09] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gt2lktkpjhp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gt2bdnneekl.html

[R10] 正则匹配
来源：http://dali.9152youxi.cn/Article/details/gt2ijegpamt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gzhubu.top/Article/details/gt2rpqistlt.html

[R11] case 多分支
来源：http://dali.aibaodan.cn/Article/details/gt2mtkygtgt.html

case "$1" in
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oestzpue.html

start) echo "启动" ;;
来源：http://dali.hywenlv.cn/Article/details/gt2nvcdbxwc.html

stop)  echo "停止" ;;
来源：http://dali.cdnleiting.top/Article/details/gt2pmvwjflt.html

*)     echo "未知命令" ;;
来源：http://dali.guannengcc.top/Article/details/gt2gdlwdayn.html

esac
来源：http://dali.xinyue.icu/Article/details/gt2qyqjhsni.html

[R12] for 遍历文件
来源：http://dali.gaohongyu789.top/Article/details/gt2lzikcqdb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuanzx.com/Article/details/gt2ycfhvhwb.html

[R13] for 计数循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2yeiglmbq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2pbfetsyt.html

[R14] C 风格 for
来源：http://dali.sxryk.cn/Article/details/gt2lfwncxzb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gt2imyqzkef.html

[R15] while 逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gt2nzdnnagb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj202588.top/Article/details/gt2kdqcgghi.html

[R16] until 等待条件
来源：http://dali.birdmap.top/Article/details/gt2msfnoyag.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2zgkyyqis.html

[R17] 数组定义与取值
来源：http://dali.bjfxy.top/Article/details/gt2qktkrkmt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yvedp.cn/Article/details/gt2dixnduhm.html

[R18] 遍历数组
来源：http://dali.xinyue.icu/Article/details/gt2cpgrkdal.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2janzalql.html

[R19] 数组长度
来源：http://dali.daria6918.cn/Article/details/gt2isbycute.html

echo "${#arr[@]}"
来源：http://dali.cashguo.top/Article/details/gt2ubeqonbc.html

[R20] 关联数组（字典）
来源：http://dali.svipenyu.cn/Article/details/gt2chyymjsy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yangfankeji.com/Article/details/gt2pwpgghew.html

[R21] 字符串长度
来源：http://dali.snrcjt.cn/Article/details/gt2ltgfndji.html

echo "${#s}"
来源：http://dali.fengsongda.top/Article/details/gt2lpuvdifm.html

[R22] 截取子串
来源：http://dali.ybcxt.top/Article/details/gt2uzbesnbh.html

echo "${s:0:5}"
来源：http://dali.yj20258.top/Article/details/gt2szugvain.html

[R23] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gt2dgytoesk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.kuanghao11.cn/Article/details/gt2qxuvfjkt.html

[R24] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gt2fmzcagoj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ybcxt.top/Article/details/gt2wgnikvdx.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj202588.top/Article/details/gt2hbrxlqry.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxuanxn.top/Article/details/gt2vyjbgpya.html

[R26] 命令替换
来源：http://dali.jqgufenzy.top/Article/details/gt2kdmmfvvp.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigufen.top/Article/details/gt2hehbhsdf.html

[R27] 算术展开
来源：http://dali.jqgufenzy.top/Article/details/gt2rnahamju.html

echo $((1 + 2 * 3))
来源：http://dali.xinyue.icu/Article/details/gt2hoymaqob.html

[R28] 浮点运算
来源：http://dali.zhongyouzk.top/Article/details/gt2fpadzsfj.html

echo "scale=2; 10/3" | bc
来源：http://dali.shuidangran.top/Article/details/gt2gqmeaxtw.html

[R29] 定义函数
来源：http://dali.yueranfly.top/Article/details/gt2asavamqx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.snrcjt.cn/Article/details/gt2iemvbmaa.html

[R30] 函数返回状态码
来源：http://dali.gzhubu.top/Article/details/gt2fgfthacy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.haohaochexian.top/Article/details/gt2erktijjk.html

[R31] 局部变量
来源：http://dali.sysykeji.top/Article/details/gt2usizsitb.html

f() { local x=1; echo "$x"; }
来源：http://dali.xylfe.cn/Article/details/gt2eynhypkj.html

[R32] 参数个数校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eexpnfon.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ykfbqegk.html

[R33] 捕获错误并提示行号
来源：http://dali.xinyue.icu/Article/details/gt2pixsewtc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yueranfly.top/Article/details/gt2mpzcgphs.html

[R34] 退出时清理
来源：http://dali.ehwqpu.com/Article/details/gt2jsmtfcph.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gt2tebvjtaj.html

[R35] 后台执行并等待
来源：http://dali.daria6918.cn/Article/details/gt2wyfsqedx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guannengcc.top/Article/details/gt2azskkuyx.html

[R36] 并发执行多个任务
来源：http://dali.shangyingyoupin.top/Article/details/gt2eonxcexp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pycfn.com/Article/details/gt2ibafacgn.html

[R37] 把输出赋给变量
来源：http://dali.xuanzx.com/Article/details/gt2dijrdwss.html

files=$(ls -1)
来源：http://dali.bjfxy.top/Article/details/gt2oaabrnuu.html

[R38] 管道串联
来源：http://dali.shangyingyoupin.top/Article/details/gt2hynhkkda.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2waciwgcw.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jdoeqmuj.html

cmd > out.log 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gt2alktcjjh.html

[R40] 追加写日志
来源：http://dali.snrcjt.cn/Article/details/gt2gxjwccuv.html

echo "log" >> out.log
来源：http://dali.hysaishi.cn/Article/details/gt2afrmfdoh.html

[R41] 丢弃输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdrwuqgi.html

cmd >/dev/null 2>&1
来源：http://dali.c1oappe.top/Article/details/gt2lwkatbdl.html

[R42] 输入重定向
来源：http://dali.jiagoushi.top/Article/details/gt2izopoxms.html

wc -l < a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2lnenmuaq.html

[R43] 按名字查找文件
来源：http://dali.chenzaomai.com/Article/details/gt2nastsbmh.html

find . -name "*.log" -type f
来源：http://dali.cdnleiting.top/Article/details/gt2ctsggkrp.html

[R44] 按修改时间查找
来源：http://dali.shzxlz.cn/Article/details/gt2ljvnctng.html

find . -mtime -7 -type f
来源：http://dali.guannengcc.top/Article/details/gt2enomdcbl.html

[R45] 批量删除
来源：http://dali.meibo888.top/Article/details/gt2clwwcgjg.html

find . -name "*.tmp" -delete
来源：http://dali.xziqi.cn/Article/details/gt2sqouisen.html

[R46] 递归替换文件内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ybngumnu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fengsongda.top/Article/details/gt2kyjhmhck.html

[R47] sed 单行替换
来源：http://dali.haohaochexian.top/Article/details/gt2yisncxwl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2rrflanxb.html

[R48] awk 取指定列
来源：http://dali.aibaodan.cn/Article/details/gt2jouflofp.html

awk '{print $1, $3}' a.txt
来源：http://dali.aizwys.cn/Article/details/gt2ikfukboh.html

[R49] awk 带条件
来源：http://dali.sweek.top/Article/details/gt2yvqipmby.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.andypj.xyz/Article/details/gt2ffhepunm.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nurykybe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gt2oeatkafe.html

[R51] 排序去重取前几
来源：http://dali.zycfv.cn/Article/details/gt2rvlhtozu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenlongwang.top/Article/details/gt2dmuidgcu.html

[R52] 统计行数
来源：http://dali.fzhhl.top/Article/details/gt2dyajtrcq.html

wc -l a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzypbahx.html

[R53] 查看文件头与实时尾
来源：http://dali.hfpthk.cn/Article/details/gt2nwdsjyvx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.smart0.xyz/Article/details/gt2btoebzvo.html

[R54] 比较两个文件
来源：http://dali.aibaodan.cn/Article/details/gt2zygvburp.html

diff a.txt b.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2uyzhlqft.html

[R55] 压缩与解压
来源：http://dali.gaohongyu789.top/Article/details/gt2kqyyvxer.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dashuyun.cn/Article/details/gt2wdxlprbf.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ngbhffsh.html

scp file user@host:/path/
来源：http://dali.tanke756.top/Article/details/gt2eybcdhcq.html

[R57] 远程执行命令
来源：http://dali.sxryk.cn/Article/details/gt2mkzmeuxd.html

ssh user@host 'uptime'
来源：http://dali.bjfxy.top/Article/details/gt2hywgekjc.html

[R58] 下载文件
来源：http://dali.tanke756.top/Article/details/gt2ssedzqlh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dianchejie.cn/Article/details/gt2pienyfyj.html

[R59] 发 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gt2fwexuvak.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.snrcjt.cn/Article/details/gt2rpqnwkkc.html

[R60] 只看 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gt2jqulxjmy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gt2miukcoez.html

[R61] 磁盘占用
来源：http://dali.cheryme.top/Article/details/gt2bookzfdf.html

df -h;  du -sh *
来源：http://dali.ydzc1.top/Article/details/gt2rvchlzoq.html

[R62] 找最占空间的文件
来源：http://dali.fengsongda.top/Article/details/gt2ziaslbvt.html

du -ah . | sort -rh | head -10
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfsckiku.html

[R63] 内存与进程
来源：http://dali.zdqjudy.top/Article/details/gt2pxslofbt.html

free -h;  ps aux | grep nginx
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqykcmxh.html

[R64] 结束进程
来源：http://dali.c1oappe.top/Article/details/gt2zdolcarw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenzaomai.com/Article/details/gt2fptkokif.html

[R65] 查看端口占用
来源：http://dali.chenjidiqi.icu/Article/details/gt2udzbjcav.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhixingplan.top/Article/details/gt2rojirlbn.html

[R66] 定时任务
来源：http://dali.ehwqpu.com/Article/details/gt2xxqblqvj.html

crontab -e;  crontab -l
来源：http://dali.xuanzx.com/Article/details/gt2gmfcbevi.html

[R67] 生成随机十六进制串
来源：http://dali.sysykeji.top/Article/details/gt2wngjrvdc.html

openssl rand -hex 16
来源：http://dali.gaohongyu789.top/Article/details/gt2whmktqga.html

[R68] 计算文件校验值
来源：http://dali.ehwqpu.com/Article/details/gt2swfytimb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2rhfrnvzq.html

[R69] 生成随机密码
来源：http://dali.ehwqpu.com/Article/details/gt2ufovojru.html

head -c 16 /dev/urandom | base64
来源：http://dali.xylfe.cn/Article/details/gt2iudnyhiv.html

[R70] 时间戳与互转
来源：http://dali.yvedp.cn/Article/details/gt2vgrmqlpu.html

date +%s;  date -d @1700000000
来源：http://dali.jqgfzy.top/Article/details/gt2gdlatrxl.html

[R71] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gt2ajfxigor.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zycfv.cn/Article/details/gt2ckujvebc.html

[R72] 等待端口就绪
来源：http://dali.jiagoushi.top/Article/details/gt2jegzaldf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gt2elebrgvl.html

[R73] 分割大日志
来源：http://dali.dianchejie.cn/Article/details/gt2lrupzvxx.html

split -l 1000 big.log part_
来源：http://dali.redwolf501.top/Article/details/gt2pruuegya.html

[R74] 批量重命名
来源：http://dali.dianchejie.cn/Article/details/gt2pgykugsf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2rehueept.html

[R75] 导出环境变量
来源：http://dali.tian-w.cn/Article/details/gt2kvvhxfru.html


<!-- 参考信息 -->