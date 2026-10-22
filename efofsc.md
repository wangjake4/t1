代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2flnrdegq.html

[Q30] 分组统计
来源：http://dali.ybcxt.top/Article/details/gt2fpgsnncd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gt2iqsyruwe.html

[Q31] 分组后过滤
来源：http://dali.chenzaomai.com/Article/details/gt2bzqlishh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tian-w.cn/Article/details/gt2kvbjagro.html

[Q32] 分组拼接字符串
来源：http://dali.guannengcc.top/Article/details/gt2lkizmarm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gt2pfxyxkle.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dashuyun.cn/Article/details/gt2aueulqtn.html

[Q33] 多列分组
来源：http://dali.yangfankeji.com/Article/details/gt2nsntehvd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.0kj1m.cn/Article/details/gt2cquxbimg.html

[Q34] 每组取第一条
来源：http://dali.cqqwz.cn/Article/details/gt2hfwnlqmk.html

SELECT * FROM (
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rcmumngu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258.top/Article/details/gt2oqajwqiu.html

) t WHERE rn = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2shjtlpsf.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2cuvejkdw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xziqi.cn/Article/details/gt2rwbgryvu.html

[Q36] 左连接
来源：http://dali.ivvv.top/Article/details/gt2shlxmukp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gt2iedwzicn.html

[Q37] 右连接
来源：http://dali.aibaodan.cn/Article/details/gt2biekqfgt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.9152youxi.cn/Article/details/gt2ubkqdqxn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cucudq.cn/Article/details/gt2kthlhqah.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cdnleiting.top/Article/details/gt2jdpgwkzb.html

[Q39] 自连接（查上下级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bavikdhn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tanke756.top/Article/details/gt2rknecnpw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2hhmsjamt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hammf.cn/Article/details/gt2oyzutzkp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgfzy.top/Article/details/gt2qmlxsjlt.html

[Q41] 多表连接
来源：http://dali.zhoulong.xyz/Article/details/gt2qhtgwnvl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gzhubu.top/Article/details/gt2fzfbrodl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jianghu66.top/Article/details/gt2dhvdwmbs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daria6918.cn/Article/details/gt2cuoskzwt.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxinkj.top/Article/details/gt2eobvntdi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.svipenyu.cn/Article/details/gt2sxbfpooj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dianchejie.cn/Article/details/gt2scutthrg.html

[Q43] 标量子查询
来源：http://dali.daxiang520.top/Article/details/gt2kxnmssts.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nanxinkj.top/Article/details/gt2jqezktvm.html

[Q44] IN 子查询
来源：http://dali.yj20258.top/Article/details/gt2pojrnbtz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.316326.xyz/Article/details/gt2toecnlav.html

[Q45] EXISTS 判断存在
来源：http://dali.xuanzx.com/Article/details/gt2xtjkspmp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gt2mpfkuhpz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fengsongda.top/Article/details/gt2aoriggbm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gt2erwyqjlr.html

[Q47] 与平均值比较
来源：http://dali.chenzaomai.com/Article/details/gt2kgluotmq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fzhhl.top/Article/details/gt2kmzwfhlw.html

[Q48] CTE 公用表表达式
来源：http://dali.shzxlz.cn/Article/details/gt2dgbddfjt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuanzx.com/Article/details/gt2dlyugusl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhiwuduotai.top/Article/details/gt2puibkrux.html

[Q49] 更新单行
来源：http://dali.bjfxy.top/Article/details/gt2rutounhq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gt2lmspedpe.html

[Q50] 批量更新
来源：http://dali.shzxlz.cn/Article/details/gt2qvdusyzr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.c1oappe.top/Article/details/gt2xuotucbw.html

[Q51] 用子查询更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2affsgwkb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.aizwys.cn/Article/details/gt2eyuywtgw.html

[Q52] 删除指定行
来源：http://dali.sweek.top/Article/details/gt2riicfbmr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nwbrower.top/Article/details/gt2favmebzi.html

[Q53] 按条件删除
来源：http://dali.316326.xyz/Article/details/gt2ikolwlfj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gt2etshkktm.html

[Q54] 清空表
来源：http://dali.tanke756.top/Article/details/gt2pywemazn.html

TRUNCATE TABLE logs;
来源：http://dali.yangfankeji.com/Article/details/gt2kjkrblmj.html

[Q55] 排名（并列占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nhwdvdul.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gt2bjpsudiz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sxryk.cn/Article/details/gt2cilscdbx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ybcxt.top/Article/details/gt2lcwqjnrf.html

[Q57] 行号
来源：http://dali.fzhhl.top/Article/details/gt2mpillrmn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2jifbxomj.html

[Q58] 累计求和
来源：http://dali.9152youxi.cn/Article/details/gt2brrayaiv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2meliaphu.html

[Q59] 分组内累计
来源：http://dali.jqgfzy.top/Article/details/gt2otulvbxe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gt2lhzqieoi.html

[Q60] 取上一行 / 下一行
来源：http://dali.aizwys.cn/Article/details/gt2cmcwkjsh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gogol.net.cn/Article/details/gt2izhpjkvh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gt2ijezabrw.html

[Q61] 移动平均
来源：http://dali.yuxming.cn/Article/details/gt2egwaktcz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gt2qgdhzmeg.html

[Q62] 分组占比
来源：http://dali.yangfankeji.com/Article/details/gt2raecdwmi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gt2bxlabyvj.html

[Q63] 开启事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zlbsstex.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbwnliyp.html

[Q64] 提交事务
来源：http://dali.yuanzhike.top/Article/details/gt2bfodecwt.html

COMMIT;
来源：http://dali.chenzaomai.com/Article/details/gt2jhzrdjvd.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2diuzhtkc.html

ROLLBACK;
来源：http://dali.0kj1m.cn/Article/details/gt2wnsmvgeb.html

[Q66] 行锁查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pecydggl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhoulong.xyz/Article/details/gt2ruvgztjm.html

[Q67] 设置隔离级别
来源：http://dali.sweek.top/Article/details/gt2elmegwxi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgufenzy.top/Article/details/gt2ubxyuptq.html

[Q68] 保存点
来源：http://dali.yongpay.top/Article/details/gt2fjjyfjvx.html

SAVEPOINT sp1;
来源：http://dali.ybcxt.top/Article/details/gt2vfxqgqgi.html

ROLLBACK TO sp1;
来源：http://dali.fzhhl.top/Article/details/gt2akykbgka.html

[Q69] 查看执行计划
来源：http://dali.xinyue.icu/Article/details/gt2qerftyaf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tanke756.top/Article/details/gt2kxmgmbeh.html

[Q70] 更新统计信息
来源：http://dali.jqgufenzy.top/Article/details/gt2vjmlspxa.html

ANALYZE TABLE users;
来源：http://dali.daxiang520.top/Article/details/gt2wvxrsspy.html

[Q71] 查看建表语句
来源：http://dali.sxryk.cn/Article/details/gt2pafigwps.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hfpthk.cn/Article/details/gt2bkbkjjjz.html

[Q72] 查看索引
来源：http://dali.guowangkeji.top/Article/details/gt2dldiunms.html

SHOW INDEX FROM users;
来源：http://dali.yj202588.top/Article/details/gt2lgypixty.html

[Q73] 查看表状态
来源：http://dali.aizwys.cn/Article/details/gt2idlqymup.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hywenlv.cn/Article/details/gt2hbrocwep.html

[Q74] 强制使用索引
来源：http://dali.cqqwz.cn/Article/details/gt2bqisrlvv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hfpthk.cn/Article/details/gt2vmyuisba.html

[Q75] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gt2dgxmstph.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qsnuxwgw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangshuangyany.cn/Article/details/gt2fsjwofgh.html

[Q76] 按天统计
来源：http://dali.dianchejie.cn/Article/details/gt2xjngullp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgfzy.top/Article/details/gt2burwtddw.html

[Q77] 时间加减
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qqixihao.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.svipenyu.cn/Article/details/gt2bvgdypuj.html

[Q78] 当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gt2ouhgwjxs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jianghu66.top/Article/details/gt2hbwuvogb.html

[Q79] 字符串拼接
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hqogmuwn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenlongwang.top/Article/details/gt2mecfkdlt.html

[Q80] 字符串截取
来源：http://dali.xylfe.cn/Article/details/gt2fufemfnh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2jsovqsac.html

[Q81] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gt2igrtqajr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2splqxhif.html

[Q82] 字符长度与字节长度
来源：http://dali.cheryme.top/Article/details/gt2eejujzeh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2wdegyaxq.html

[Q83] 大小写转换
来源：http://dali.hammf.cn/Article/details/gt2xlyvtgqh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2fiuhzbni.html

[Q84] 去除首尾空格
来源：http://dali.ivvv.top/Article/details/gt2zngpldla.html

SELECT TRIM(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2gldlsebb.html

[Q85] 数值取整
来源：http://dali.gzhubu.top/Article/details/gt2yicuhlnt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gaohongyu789.top/Article/details/gt2oepiopjl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mccsaezw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sxryk.cn/Article/details/gt2hycllitp.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gt2kphrssuh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gzhubu.top/Article/details/gt2wkabkeql.html

[Q88] 行转列（条件聚合）
来源：http://dali.fzhhl.top/Article/details/gt2tdkykrpf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fengsongda.top/Article/details/gt2gcxawouf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2qintsefh.html

[Q89] 判断表是否存在
来源：http://dali.nanxuanxn.top/Article/details/gt2lzbwiynb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pycfn.com/Article/details/gt2cymdteut.html

[Q90] 生成序号列
来源：http://dali.zycfv.cn/Article/details/gt2swdgrxro.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yueranfly.top/Article/details/gt2pehmqobb.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2oniybyrg.html

R. Bash 专题
来源：http://dali.gaohongyu789.top/Article/details/gt2guzhvwsp.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2ymjpkbpt.html

[R01] shebang 与严格模式
来源：http://dali.guowangkeji.top/Article/details/gt2bafgropm.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjtwiggr.html

set -euo pipefail
来源：http://dali.chenlongwang.top/Article/details/gt2oujzyrjk.html

[R02] 变量赋值与使用
来源：http://dali.shuidangran.top/Article/details/gt2wanbuihq.html

name="Tom"; echo "$name"
来源：http://dali.cashguo.top/Article/details/gt2sgnaduhg.html

[R03] 只读变量
来源：http://dali.jiagoushi.top/Article/details/gt2posthlye.html

readonly PI=3.14
来源：http://dali.daxiang520.top/Article/details/gt2trmgzmiw.html

[R04] 位置参数
来源：http://dali.xziqi.cn/Article/details/gt2qwrxxbgx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.mhx1999.top/Article/details/gt2ctyphxco.html

[R05] 参数默认值
来源：http://dali.gotoacloud.top/Article/details/gt2ynfyygel.html

name="${1:-default}"
来源：http://dali.gaohongyu789.top/Article/details/gt2reampgjt.html

[R06] 判断命令是否存在
来源：http://dali.nwbrower.top/Article/details/gt2wtmldsub.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gt2iodfdcqr.html

[R07] if 判断文件
来源：http://dali.fzhhl.top/Article/details/gt2fxttwjxy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.aizwys.cn/Article/details/gt2ficwwrgh.html

[R08] 数值比较
来源：http://dali.jinqigfzy.top/Article/details/gt2guxidfdb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnqzz.top/Article/details/gt2vrsxxwrg.html

[R09] 字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gt2oagujpvo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zupfxhwa.html

[R10] 正则匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wpncimaa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vlovqcdu.html

[R11] case 多分支
来源：http://dali.nanxuanxn.top/Article/details/gt2kqyfchpf.html

case "$1" in
来源：http://dali.jqgufenzy.top/Article/details/gt2nymqmkph.html

start) echo "启动" ;;
来源：http://dali.ivvv.top/Article/details/gt2lnynltoq.html

stop)  echo "停止" ;;
来源：http://dali.zhengqikj.top/Article/details/gt2buuszwdm.html

*)     echo "未知命令" ;;
来源：http://dali.jianghu66.top/Article/details/gt2eqescbnn.html

esac
来源：http://dali.yuanzhike.top/Article/details/gt2cmcqazmr.html

[R12] for 遍历文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yooiubdh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj202588.top/Article/details/gt2vwftwovp.html

[R13] for 计数循环
来源：http://dali.9152youxi.cn/Article/details/gt2ivqeofaf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gt2uwdannla.html

[R14] C 风格 for
来源：http://dali.yj20258888.top/Article/details/gt2krmhrqnt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gt2ucuizpmy.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gt2yjuwofcn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2tnguvuhx.html

[R16] until 等待条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ovljnvde.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gt2djjzmkmn.html

[R17] 数组定义与取值
来源：http://dali.hnqzz.top/Article/details/gt2gyzffgmt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yangfankeji.com/Article/details/gt2hcxpuvin.html

[R18] 遍历数组
来源：http://dali.jiagoushi.top/Article/details/gt2wxxinttk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gt2ztjcczip.html

[R19] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gt2rawukcxr.html

echo "${#arr[@]}"
来源：http://dali.dianchejie.cn/Article/details/gt2syjktfvy.html

[R20] 关联数组（字典）
来源：http://dali.xuanzx.com/Article/details/gt2zmkclusy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuanzhike.top/Article/details/gt2kwdcxlig.html

[R21] 字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lcyhhinm.html

echo "${#s}"
来源：http://dali.kuanghao11.cn/Article/details/gt2sjtakrsd.html

[R22] 截取子串
来源：http://dali.xuanzx.com/Article/details/gt2jpbgqsmc.html

echo "${s:0:5}"
来源：http://dali.gogol.net.cn/Article/details/gt2lbzwwsag.html

[R23] 字符串替换
来源：http://dali.yongpay.top/Article/details/gt2wgtdtnit.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hysaishi.cn/Article/details/gt2ibiyhrgj.html

[R24] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gt2mkiujcme.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.0kj1m.cn/Article/details/gt2fzevykfa.html

[R25] 去后缀 / 去前缀
来源：http://dali.cashguo.top/Article/details/gt2gkejoley.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hywenlv.cn/Article/details/gt2mbhwfvnl.html

[R26] 命令替换
来源：http://dali.zdqjudy.top/Article/details/gt2oztyckew.html

now=$(date +%F); echo "$now"
来源：http://dali.nwbrower.top/Article/details/gt2gjsmqvuh.html

[R27] 算术展开
来源：http://dali.yanxiufei.cn/Article/details/gt2nzbylghd.html

echo $((1 + 2 * 3))
来源：http://dali.shzxlz.cn/Article/details/gt2wvdidnzp.html

[R28] 浮点运算
来源：http://dali.yvedp.cn/Article/details/gt2zszjuafv.html

echo "scale=2; 10/3" | bc
来源：http://dali.tian-w.cn/Article/details/gt2qtabtjfp.html

[R29] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gt2ycibuwxw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258888.top/Article/details/gt2fwdjaocs.html

[R30] 函数返回状态码
来源：http://dali.vqdsnc.cn/Article/details/gt2ssaeeuql.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgufenzy.top/Article/details/gt2zruwdcov.html

[R31] 局部变量
来源：http://dali.hnxiangtu.top/Article/details/gt2mqpcxhrr.html

f() { local x=1; echo "$x"; }
来源：http://dali.xylfe.cn/Article/details/gt2ffhihkdq.html

[R32] 参数个数校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbrixceu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gt2vqwobidy.html

[R33] 捕获错误并提示行号
来源：http://dali.quarkkingdee.top/Article/details/gt2zsthrycv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shuidangran.top/Article/details/gt2fwhuqddr.html

[R34] 退出时清理
来源：http://dali.yj20258888.top/Article/details/gt2wtxskdtx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gt2qkxwhysh.html

[R35] 后台执行并等待
来源：http://dali.xinyue.icu/Article/details/gt2tozvhcdy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yangfankeji.com/Article/details/gt2ibfgzcmm.html

[R36] 并发执行多个任务
来源：http://dali.iojbl.cn/Article/details/gt2lxvpsuds.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hammf.cn/Article/details/gt2pytbpeys.html

[R37] 把输出赋给变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mchocxhw.html

files=$(ls -1)
来源：http://dali.mhx1999.top/Article/details/gt2kabgkqcm.html

[R38] 管道串联
来源：http://dali.fzhhl.top/Article/details/gt2dkhjonuq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yanxiufei.cn/Article/details/gt2iqeghugl.html

[R39] 重定向标准输出与错误
来源：http://dali.pycfn.com/Article/details/gt2omglnafm.html

cmd > out.log 2>&1
来源：http://dali.aibaodan.cn/Article/details/gt2lykabsis.html

[R40] 追加写日志
来源：http://dali.daxiang520.top/Article/details/gt2pznsbddr.html

echo "log" >> out.log
来源：http://dali.havefunace.top/Article/details/gt2dmsqiruu.html

[R41] 丢弃输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vjxgmjiw.html

cmd >/dev/null 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gt2tznktaau.html

[R42] 输入重定向
来源：http://dali.cdnleiting.top/Article/details/gt2frzfdwff.html

wc -l < a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2nlpurxki.html

[R43] 按名字查找文件
来源：http://dali.birdmap.top/Article/details/gt2tusxvyxv.html

find . -name "*.log" -type f
来源：http://dali.redwolf501.top/Article/details/gt2ynavdbpv.html

[R44] 按修改时间查找
来源：http://dali.ydzc1.top/Article/details/gt2neyixbcz.html

find . -mtime -7 -type f
来源：http://dali.yj20258.top/Article/details/gt2gsedmqmz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ricoldex.html

find . -name "*.tmp" -delete
来源：http://dali.tanke756.top/Article/details/gt2zznfcqrx.html

[R46] 递归替换文件内容
来源：http://dali.wangdashe.top/Article/details/gt2rbnebjwi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuetiantiany.cn/Article/details/gt2xlatzmer.html

[R47] sed 单行替换
来源：http://dali.cashguo.top/Article/details/gt2ubvifpwk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fengsongda.top/Article/details/gt2uwtxyzjd.html

[R48] awk 取指定列
来源：http://dali.pycfn.com/Article/details/gt2gadxzrkv.html

awk '{print $1, $3}' a.txt
来源：http://dali.meibo888.top/Article/details/gt2bdkvggpu.html

[R49] awk 带条件
来源：http://dali.jqgufenzy.top/Article/details/gt2puzkottw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tanke756.top/Article/details/gt2xlnpvuew.html

[R50] awk 求和
来源：http://dali.shzxlz.cn/Article/details/gt2clnxtqht.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guannengcc.top/Article/details/gt2rjewbbjk.html

[R51] 排序去重取前几
来源：http://dali.dashuyun.cn/Article/details/gt2jpjmcipc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yvedp.cn/Article/details/gt2qsdlqiqu.html

[R52] 统计行数
来源：http://dali.ybcxt.top/Article/details/gt2ghjafibk.html

wc -l a.txt
来源：http://dali.xziqi.cn/Article/details/gt2skdyyrpz.html

[R53] 查看文件头与实时尾
来源：http://dali.xziqi.cn/Article/details/gt2qcdgmlbu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxinkj.top/Article/details/gt2awigrajt.html

[R54] 比较两个文件
来源：http://dali.iojbl.cn/Article/details/gt2ikogckpc.html

diff a.txt b.txt
来源：http://dali.nanxinkj.top/Article/details/gt2nnnubsed.html

[R55] 压缩与解压
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rrycqrmr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gotoacloud.top/Article/details/gt2pgcsmbon.html

[R56] 远程拷贝
来源：http://dali.chenzaomai.com/Article/details/gt2rqgulzeq.html

scp file user@host:/path/
来源：http://dali.shangyingyoupin.top/Article/details/gt2kltpwqkv.html

[R57] 远程执行命令
来源：http://dali.cdnleiting.top/Article/details/gt2idncicua.html

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gt2zpsnxphs.html

[R58] 下载文件
来源：http://dali.yueranfly.top/Article/details/gt2zxvmxhbz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.daxiang520.top/Article/details/gt2rpwzbrvi.html

[R59] 发 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2tngwilaz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.iojbl.cn/Article/details/gt2aibebokq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gt2aujebmes.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dashuyun.cn/Article/details/gt2qdolybid.html

[R61] 磁盘占用
来源：http://dali.havefunace.top/Article/details/gt2mdydevai.html

df -h;  du -sh *
来源：http://dali.shzxlz.cn/Article/details/gt2fnqozvll.html

[R62] 找最占空间的文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sysgqxkl.html

du -ah . | sort -rh | head -10
来源：http://dali.hnxiangtu.top/Article/details/gt2hotyteqg.html

[R63] 内存与进程
来源：http://dali.hfpthk.cn/Article/details/gt2durqwadn.html

free -h;  ps aux | grep nginx
来源：http://dali.jiagoushi.top/Article/details/gt2gvfhnvoy.html

[R64] 结束进程
来源：http://dali.yj20258.top/Article/details/gt2aupnlimb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuanzhike.top/Article/details/gt2hqxkxtcr.html

[R65] 查看端口占用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rskdsodg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenzaomai.com/Article/details/gt2fdcadecd.html

[R66] 定时任务
来源：http://dali.sweek.top/Article/details/gt2zaqjnpsd.html

crontab -e;  crontab -l
来源：http://dali.sweek.top/Article/details/gt2ikhaaayg.html

[R67] 生成随机十六进制串
来源：http://dali.chenjidiqi.icu/Article/details/gt2obtkyyym.html

openssl rand -hex 16
来源：http://dali.jlsjyb.cn/Article/details/gt2osbpyahu.html

[R68] 计算文件校验值
来源：http://dali.yonumen.top/Article/details/gt2iuatbcuz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2uuicpbzi.html

[R69] 生成随机密码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tvoznmuf.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lnwhfcdo.html

[R70] 时间戳与互转
来源：http://dali.wangdashe.top/Article/details/gt2ozfvtptd.html

date +%s;  date -d @1700000000
来源：http://dali.gzhubu.top/Article/details/gt2tjmjskli.html

[R71] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gt2ieajsrge.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnxiangtu.top/Article/details/gt2aphlbfqf.html

[R72] 等待端口就绪
来源：http://dali.yj20258.top/Article/details/gt2ufmdjvnq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2jfgdvvoq.html

[R73] 分割大日志
来源：http://dali.hnqzz.top/Article/details/gt2usjqliwd.html

split -l 1000 big.log part_
来源：http://dali.smart0.xyz/Article/details/gt2jxbebhih.html

[R74] 批量重命名
来源：http://dali.zhongyouzk.top/Article/details/gt2rlgwdgjt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxinkj.top/Article/details/gt2qgiwujwr.html

[R75] 导出环境变量
来源：http://dali.zhixingplan.top/Article/details/gt2dvlaokak.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhongyouzk.top/Article/details/gt2vsvsyivj.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gt2vuxjnlcg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gt2trdyvxhg.html

[R77] 读取用户输入
来源：http://dali.jianghu66.top/Article/details/gt2gmnfmwer.html

read -rp "请输入: " ans
来源：http://dali.wangshuangyany.cn/Article/details/gt2dfauhgqe.html

[R78] 交互式菜单
来源：http://dali.yvedp.cn/Article/details/gt2mbbkhego.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xziqi.cn/Article/details/gt2dtbyixcy.html

[R79] 解析命令行选项
来源：http://dali.gzhubu.top/Article/details/gt2uuqqxysp.html


<!-- 参考信息 -->