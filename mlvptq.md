代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gogol.net.cn/Article/details/gtxlybrrae.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tanke756.top/Article/details/gtvdsgyggv.html

[Q13] 忽略重复插入
来源：http://dali.xuanzx.com/Article/details/gtpiohyegp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtsiegcaoz.html

[Q14] 存在则更新（upsert）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpuyiutj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhongyouzk.top/Article/details/gtfbccudpb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhongyouzk.top/Article/details/gtanjjaghq.html

[Q15] 查询全部
来源：http://dali.zhixingplan.top/Article/details/gttizghskj.html

SELECT * FROM users;
来源：http://dali.cucudq.cn/Article/details/gtkxwboyww.html

[Q16] 查询指定列
来源：http://dali.xziqi.cn/Article/details/gtxmcterzn.html

SELECT id, name FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtizepfxqh.html

[Q17] 条件查询
来源：http://dali.yongpay.top/Article/details/gtqsqnbjip.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gttrkihgej.html

[Q18] 模糊匹配
来源：http://dali.hammf.cn/Article/details/gtbhgmevnh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gogol.net.cn/Article/details/gtpnfhagyw.html

[Q19] 范围查询
来源：http://dali.jiagoushi.top/Article/details/gtcstqitkc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenzaomai.com/Article/details/gtsxgnmnbi.html

[Q20] IN 列表
来源：http://dali.wangdashe.top/Article/details/gtmoiyalai.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tian-w.cn/Article/details/gtwgpkluvg.html

[Q21] 空值判断
来源：http://dali.zhiwuduotai.top/Article/details/gtfdwvyoaj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hysaishi.cn/Article/details/gtnbvvgdcz.html

[Q22] 排序
来源：http://dali.ehwqpu.com/Article/details/gtyglgcuww.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zdqjudy.top/Article/details/gtfprsyftk.html

[Q23] 分页
来源：http://dali.quarkkingdee.top/Article/details/gtzmkqnzmu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tanke756.top/Article/details/gtlyodynrd.html

[Q24] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdibadls.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuljxxilf.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gtmwoacbfg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hnqzz.top/Article/details/gtcysrlbpk.html

[Q26] 计数
来源：http://dali.hfpthk.cn/Article/details/gtztnvffbi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtyqdyenzs.html

[Q27] 条件计数
来源：http://dali.tian-w.cn/Article/details/gtsreruock.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.smart0.xyz/Article/details/gtzubkaotp.html

[Q28] 求和与平均
来源：http://dali.sxryk.cn/Article/details/gtpymrdplr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtvvzhzulv.html

[Q29] 最大最小值
来源：http://dali.shuidangran.top/Article/details/gtwqpmhnfn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yonumen.top/Article/details/gtrdensvou.html

[Q30] 分组统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgjfpkaz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtrwximben.html

[Q31] 分组后过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtshabsieh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.havefunace.top/Article/details/gtlaxsbigb.html

[Q32] 分组拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtsflugbln.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gthoezqkzk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhengqikj.top/Article/details/gtnbcdqzkp.html

[Q33] 多列分组
来源：http://dali.shzxlz.cn/Article/details/gtrggctgyq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cheryme.top/Article/details/gtubawajxy.html

[Q34] 每组取第一条
来源：http://dali.hammf.cn/Article/details/gtmciihjso.html

SELECT * FROM (
来源：http://dali.cashguo.top/Article/details/gtezrvdako.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pycfn.com/Article/details/gtoaowhywz.html

) t WHERE rn = 1;
来源：http://dali.ybcxt.top/Article/details/gtidngyaut.html

[Q35] 内连接
来源：http://dali.yangfankeji.com/Article/details/gttjqugnzz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gtagesymwd.html

[Q36] 左连接
来源：http://dali.meibo888.top/Article/details/gtfkuhxzpj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xinyue.icu/Article/details/gtliepqeyu.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gtamtmnccn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.vqdsnc.cn/Article/details/gtcaapoqbp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.snrcjt.cn/Article/details/gtzxmgziwb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tanke756.top/Article/details/gtnnixmzry.html

[Q39] 自连接（查上下级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbbmcdpr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangtech.top/Article/details/gtefipqnmf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.havefunace.top/Article/details/gtwbwyxbqv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xylfe.cn/Article/details/gtoxstsluq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenjidiqi.icu/Article/details/gtbkimesye.html

[Q41] 多表连接
来源：http://dali.hnxiangtu.top/Article/details/gtbvqxqesg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shzxlz.cn/Article/details/gtubrgfvic.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgufenzy.top/Article/details/gtijtmzrur.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.andypj.xyz/Article/details/gtevxfkaoo.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgufenzy.top/Article/details/gtkpkmrntm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hongshengwenyu.top/Article/details/gttsxrcllz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dashuyun.cn/Article/details/gtemuwiwzf.html

[Q43] 标量子查询
来源：http://dali.meibo888.top/Article/details/gtimkcnxfo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daria6918.cn/Article/details/gtctlmgtrf.html

[Q44] IN 子查询
来源：http://dali.zhiwuduotai.top/Article/details/gtkhiyugpu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shangyingyoupin.top/Article/details/gtttmjvlri.html

[Q45] EXISTS 判断存在
来源：http://dali.cqqwz.cn/Article/details/gtzankfdct.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hfpthk.cn/Article/details/gthptpusze.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtclzsvrtp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gtgbrayhnw.html

[Q47] 与平均值比较
来源：http://dali.zhiwuduotai.top/Article/details/gterhcuwpo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsnnivxi.html

[Q48] CTE 公用表表达式
来源：http://dali.tian-w.cn/Article/details/gtmilhnwvc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.andypj.xyz/Article/details/gtuplihapq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jiagoushi.top/Article/details/gtxbcjvdit.html

[Q49] 更新单行
来源：http://dali.yanxiufei.cn/Article/details/gtjanfthvk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gtksonxqks.html

[Q50] 批量更新
来源：http://dali.vqdsnc.cn/Article/details/gtzynserik.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tian-w.cn/Article/details/gticptmdmi.html

[Q51] 用子查询更新
来源：http://dali.nanxinkj.top/Article/details/gtmpyesljj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hfpthk.cn/Article/details/gtahgveuop.html

[Q52] 删除指定行
来源：http://dali.dianchejie.cn/Article/details/gtimfhbhyr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gtfiqbhzcc.html

[Q53] 按条件删除
来源：http://dali.aibaodan.cn/Article/details/gtycwnhvfp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.kuanghao11.cn/Article/details/gttcaqfrzf.html

[Q54] 清空表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjelgejlk.html

TRUNCATE TABLE logs;
来源：http://dali.chenjidiqi.icu/Article/details/gtcsqmhrtn.html

[Q55] 排名（并列占位）
来源：http://dali.shuidangran.top/Article/details/gtyredbvdb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.316326.xyz/Article/details/gtbhojscvq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuanzx.com/Article/details/gtjjcdymvi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.smart0.xyz/Article/details/gtuvjxtqko.html

[Q57] 行号
来源：http://dali.pycfn.com/Article/details/gtsbqlxnyy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gthbsnmjwp.html

[Q58] 累计求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwclywhd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtbgxcamzu.html

[Q59] 分组内累计
来源：http://dali.gzhubu.top/Article/details/gtwwwoayxh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrnyuauc.html

[Q60] 取上一行 / 下一行
来源：http://dali.cashguo.top/Article/details/gtofjaghnl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cucudq.cn/Article/details/gtflvfuxrb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtfddruncv.html

[Q61] 移动平均
来源：http://dali.aizwys.cn/Article/details/gtboxnniaz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtgikkhirg.html

[Q62] 分组占比
来源：http://dali.ydzc1.top/Article/details/gtybchceqm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gtvpatsuzr.html

[Q63] 开启事务
来源：http://dali.jqgufenzy.top/Article/details/gtbvgxjslq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqywnmjg.html

[Q64] 提交事务
来源：http://dali.zycfv.cn/Article/details/gthgsugsvi.html

COMMIT;
来源：http://dali.kuanghao11.cn/Article/details/gtdpwwzmwy.html

[Q65] 回滚事务
来源：http://dali.fzhhl.top/Article/details/gtsrydvtvk.html

ROLLBACK;
来源：http://dali.hfpthk.cn/Article/details/gtbvgdzvai.html

[Q66] 行锁查询
来源：http://dali.meibo888.top/Article/details/gtygutxgqj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.0kj1m.cn/Article/details/gtwonohjpu.html

[Q67] 设置隔离级别
来源：http://dali.ybcxt.top/Article/details/gtvjiedngx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jiagoushi.top/Article/details/gtopcfmodl.html

[Q68] 保存点
来源：http://dali.c1oappe.top/Article/details/gttrmstcgg.html

SAVEPOINT sp1;
来源：http://dali.wangdashe.top/Article/details/gthfoxuspm.html

ROLLBACK TO sp1;
来源：http://dali.vqdsnc.cn/Article/details/gthbhkwzpc.html

[Q69] 查看执行计划
来源：http://dali.cdnleiting.top/Article/details/gtrjrzjtak.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ydzc1.top/Article/details/gtrnnkvrlq.html

[Q70] 更新统计信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgowsxpg.html

ANALYZE TABLE users;
来源：http://dali.vqdsnc.cn/Article/details/gtzzixpxnq.html

[Q71] 查看建表语句
来源：http://dali.9152youxi.cn/Article/details/gtwqdneiiq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigufen.top/Article/details/gtngejrpkb.html

[Q72] 查看索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbsdxqoag.html

SHOW INDEX FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtlzrpygig.html

[Q73] 查看表状态
来源：http://dali.sysykeji.top/Article/details/gtfldixfpl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuanzx.com/Article/details/gtupvjnpbq.html

[Q74] 强制使用索引
来源：http://dali.fzhhl.top/Article/details/gtmzymydlf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gotoacloud.top/Article/details/gtizbxbfbn.html

[Q75] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtuphrbgph.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtueqynzme.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ivvv.top/Article/details/gtqatlepti.html

[Q76] 按天统计
来源：http://dali.pengpengdd.cyou/Article/details/gtesgxwtus.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shangyingyoupin.top/Article/details/gtoncidknz.html

[Q77] 时间加减
来源：http://dali.yj20258888.top/Article/details/gtgbwmbqun.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.9152youxi.cn/Article/details/gtjyaigegu.html

[Q78] 当前时间
来源：http://dali.yangfankeji.com/Article/details/gthnlkxjvt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shangyingyoupin.top/Article/details/gtmzwlnovp.html

[Q79] 字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gtwzqvulnr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenjidiqi.icu/Article/details/gtowkcoaju.html

[Q80] 字符串截取
来源：http://dali.sufxvd.cn/Article/details/gtqzvdfnfw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtbzkxbapm.html

[Q81] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gtijkgtqbs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gtsxyawlli.html

[Q82] 字符长度与字节长度
来源：http://dali.dianchejie.cn/Article/details/gtxqfbrkvf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtytsbfoyb.html

[Q83] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gtcbofezza.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtwigtegko.html

[Q84] 去除首尾空格
来源：http://dali.bjfxy.top/Article/details/gtakiwtgvx.html

SELECT TRIM(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtojxpjlec.html

[Q85] 数值取整
来源：http://dali.ivvv.top/Article/details/gtzetzsfvs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guowangkeji.top/Article/details/gttopavbpr.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgufenzy.top/Article/details/gtwpexbvhv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sufxvd.cn/Article/details/gteosodvrs.html

[Q87] JSON 字段做条件
来源：http://dali.chenjidiqi.icu/Article/details/gtbmwwvbka.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sufxvd.cn/Article/details/gtcpbmtlco.html

[Q88] 行转列（条件聚合）
来源：http://dali.sysykeji.top/Article/details/gtmbcfxdgq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.9152youxi.cn/Article/details/gtpqsksmka.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtirtppjya.html

[Q89] 判断表是否存在
来源：http://dali.sufxvd.cn/Article/details/gtwczbhlxz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxuanxn.top/Article/details/gtrqpqrvwu.html

[Q90] 生成序号列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteusioiri.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnxiangtu.top/Article/details/gtbfqivstg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtbztixxak.html

R. Bash 专题
来源：http://dali.jqgufenzy.top/Article/details/gtdtbvdqko.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtbxmwewye.html

[R01] shebang 与严格模式
来源：http://dali.sxryk.cn/Article/details/gtzhhnvrtd.html

#!/usr/bin/env bash
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmhuzgej.html

set -euo pipefail
来源：http://dali.shzxlz.cn/Article/details/gtdcsiwpoq.html

[R02] 变量赋值与使用
来源：http://dali.ppjwa.cn/Article/details/gtlnjkflix.html

name="Tom"; echo "$name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkplxpain.html

[R03] 只读变量
来源：http://dali.tian-w.cn/Article/details/gtxiojqmsq.html

readonly PI=3.14
来源：http://dali.yj20258888.top/Article/details/gtyyyhotba.html

[R04] 位置参数
来源：http://dali.dianchejie.cn/Article/details/gtkrecxmqk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.redwolf501.top/Article/details/gtwphsdrkt.html

[R05] 参数默认值
来源：http://dali.havefunace.top/Article/details/gtvgxokjay.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gtxvhbmedn.html

[R06] 判断命令是否存在
来源：http://dali.havefunace.top/Article/details/gtoaiviltq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gtoqnpuekt.html

[R07] if 判断文件
来源：http://dali.jqgfzy.top/Article/details/gtixfmknrk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.bjfxy.top/Article/details/gtssfytqjp.html

[R08] 数值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqunbhtn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtnqlrhsru.html

[R09] 字符串比较
来源：http://dali.9152youxi.cn/Article/details/gtkuqwggzx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hysaishi.cn/Article/details/gtfascsnfd.html

[R10] 正则匹配
来源：http://dali.yj20258888.top/Article/details/gtusvrrvvt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtdqnmapuz.html

[R11] case 多分支
来源：http://dali.zhengqikj.top/Article/details/gtodecsogd.html

case "$1" in
来源：http://dali.fzhhl.top/Article/details/gtczkhbwao.html

start) echo "启动" ;;
来源：http://dali.hammf.cn/Article/details/gtcaskqwct.html

stop)  echo "停止" ;;
来源：http://dali.iojbl.cn/Article/details/gtwuvahezh.html

*)     echo "未知命令" ;;
来源：http://dali.chenlongwang.top/Article/details/gtfvqkeuef.html

esac
来源：http://dali.pycfn.com/Article/details/gthimqzkhc.html

[R12] for 遍历文件
来源：http://dali.gzhubu.top/Article/details/gtoaibqlpl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.redwolf501.top/Article/details/gttvxfjhvg.html

[R13] for 计数循环
来源：http://dali.yj202588.top/Article/details/gtkwztpaee.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gtoyugfpjw.html

[R14] C 风格 for
来源：http://dali.zhiwuduotai.top/Article/details/gtbspgurmr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gtdgwmwvsp.html

[R15] while 逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtasfevjql.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxuanxn.top/Article/details/gtmzkgmyvo.html

[R16] until 等待条件
来源：http://dali.cheryme.top/Article/details/gttrrdeutf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.birdmap.top/Article/details/gtibbwmion.html

[R17] 数组定义与取值
来源：http://dali.zhoulong.xyz/Article/details/gtmfsuvuno.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhixingplan.top/Article/details/gtgmblmpbl.html

[R18] 遍历数组
来源：http://dali.chenzaomai.com/Article/details/gtegpfzpor.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258888.top/Article/details/gtnsygvkqi.html

[R19] 数组长度
来源：http://dali.yonumen.top/Article/details/gtawrsmqmm.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnpnkcfhe.html

[R20] 关联数组（字典）
来源：http://dali.9152youxi.cn/Article/details/gthahvkosu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sufxvd.cn/Article/details/gtojcvyiwm.html

[R21] 字符串长度
来源：http://dali.haohaochexian.top/Article/details/gthzwutcqg.html

echo "${#s}"
来源：http://dali.sxryk.cn/Article/details/gtnmpuahek.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gtjixbkbqh.html

echo "${s:0:5}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtythapbvy.html

[R23] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gtulhdwkrt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangdashe.top/Article/details/gtmsjxqfqg.html

[R24] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtergfnpej.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj202588.top/Article/details/gtbtuuhpmz.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenlongwang.top/Article/details/gthyctycpc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigfzy.top/Article/details/gtcpobkasr.html

[R26] 命令替换
来源：http://dali.wangdashe.top/Article/details/gtwetqcizu.html

now=$(date +%F); echo "$now"
来源：http://dali.tanke756.top/Article/details/gtrzdbqhfr.html

[R27] 算术展开
来源：http://dali.gzhubu.top/Article/details/gtczlkmhkh.html

echo $((1 + 2 * 3))
来源：http://dali.redwolf501.top/Article/details/gtnisblbih.html

[R28] 浮点运算
来源：http://dali.iojbl.cn/Article/details/gtgcmodffo.html

echo "scale=2; 10/3" | bc
来源：http://dali.yvedp.cn/Article/details/gthqkgkqgy.html

[R29] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gtrnzwgofk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cashguo.top/Article/details/gtkkkprcsh.html

[R30] 函数返回状态码
来源：http://dali.yanxiufei.cn/Article/details/gtqiqzoesw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hysaishi.cn/Article/details/gtxddidsvo.html

[R31] 局部变量
来源：http://dali.zhixingplan.top/Article/details/gtwurmwtwp.html

f() { local x=1; echo "$x"; }
来源：http://dali.cashguo.top/Article/details/gtepvdzpwk.html

[R32] 参数个数校验
来源：http://dali.cdnleiting.top/Article/details/gtuvfidfjl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gtreijqlyv.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgfzy.top/Article/details/gtulgfktxv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigfzy.top/Article/details/gtnqislhvq.html

[R34] 退出时清理
来源：http://dali.tanke756.top/Article/details/gtmhwkqihu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtnhiffhyj.html

[R35] 后台执行并等待
来源：http://dali.pycfn.com/Article/details/gtaexgvsbf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.9152youxi.cn/Article/details/gtdjfzwsur.html

[R36] 并发执行多个任务
来源：http://dali.yuxming.cn/Article/details/gtnedwlayn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.havefunace.top/Article/details/gtoagqgnwv.html

[R37] 把输出赋给变量
来源：http://dali.sufxvd.cn/Article/details/gtiepczzpx.html

files=$(ls -1)
来源：http://dali.tanke756.top/Article/details/gtvxqcoion.html

[R38] 管道串联
来源：http://dali.hnqzz.top/Article/details/gtacskhwll.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yongpay.top/Article/details/gtlhauitur.html

[R39] 重定向标准输出与错误
来源：http://dali.feifeiyinyue.top/Article/details/gtignnjbys.html

cmd > out.log 2>&1
来源：http://dali.yj20258888.top/Article/details/gtyhcnczbh.html

[R40] 追加写日志
来源：http://dali.ivvv.top/Article/details/gtcobazfgs.html

echo "log" >> out.log
来源：http://dali.kuanghao11.cn/Article/details/gtxjrzolut.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gtezscqfhx.html

cmd >/dev/null 2>&1
来源：http://dali.dashuyun.cn/Article/details/gtsjevaoqr.html

[R42] 输入重定向
来源：http://dali.shzxlz.cn/Article/details/gtmlvkcvwf.html

wc -l < a.txt
来源：http://dali.aibaodan.cn/Article/details/gtlpnobcxa.html

[R43] 按名字查找文件
来源：http://dali.jinqigfzy.top/Article/details/gtuqkrumxw.html

find . -name "*.log" -type f
来源：http://dali.hnqzz.top/Article/details/gtwjcojjhl.html

[R44] 按修改时间查找
来源：http://dali.ydzc1.top/Article/details/gtsdjwhtnd.html

find . -mtime -7 -type f
来源：http://dali.ybcxt.top/Article/details/gttefcxpgl.html

[R45] 批量删除
来源：http://dali.hysaishi.cn/Article/details/gtytesxwdt.html

find . -name "*.tmp" -delete
来源：http://dali.chenlongwang.top/Article/details/gtxsyeoagr.html

[R46] 递归替换文件内容
来源：http://dali.cdnleiting.top/Article/details/gthowbbobv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.meibo888.top/Article/details/gtolkhdkmj.html

[R47] sed 单行替换
来源：http://dali.yueranfly.top/Article/details/gtvhicrahx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmbdnhcs.html

[R48] awk 取指定列
来源：http://dali.zhoulong.xyz/Article/details/gthfghrbwy.html

awk '{print $1, $3}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtazwpmrgg.html

[R49] awk 带条件
来源：http://dali.cheryme.top/Article/details/gtvdaweojk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cashguo.top/Article/details/gtckyoeyws.html

[R50] awk 求和
来源：http://dali.kuanghao11.cn/Article/details/gtorofbwum.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.iojbl.cn/Article/details/gtdevanhgt.html

[R51] 排序去重取前几
来源：http://dali.shuidangran.top/Article/details/gtuxwptwfl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gzhubu.top/Article/details/gtmvgjxmqh.html

[R52] 统计行数
来源：http://dali.xuetiantiany.cn/Article/details/gtofhztdec.html

wc -l a.txt
来源：http://dali.snrcjt.cn/Article/details/gtnflvmfyp.html

[R53] 查看文件头与实时尾
来源：http://dali.jiagoushi.top/Article/details/gtljfmahhq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dashuyun.cn/Article/details/gthykasnqi.html

[R54] 比较两个文件
来源：http://dali.yanxiufei.cn/Article/details/gtnupafxlx.html

diff a.txt b.txt
来源：http://dali.yj20258.top/Article/details/gtxjgvnxpu.html

[R55] 压缩与解压
来源：http://dali.andypj.xyz/Article/details/gtwilxhlae.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ppjwa.cn/Article/details/gtketowhjd.html

[R56] 远程拷贝
来源：http://dali.yonumen.top/Article/details/gtjtvnnula.html

scp file user@host:/path/
来源：http://dali.aibaodan.cn/Article/details/gttwdyxpzt.html

[R57] 远程执行命令
来源：http://dali.quarkkingdee.top/Article/details/gtjjnnfosv.html

ssh user@host 'uptime'
来源：http://dali.zhixingplan.top/Article/details/gtixlmdbxn.html

[R58] 下载文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuffetauj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hnqzz.top/Article/details/gtelsfordn.html

[R59] 发 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtjwyjlhql.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tian-w.cn/Article/details/gtbexwyqaf.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gtfjckxmwt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gtgclvxqfs.html

[R61] 磁盘占用
来源：http://dali.daria6918.cn/Article/details/gtqlqprctl.html


<!-- 参考信息 -->