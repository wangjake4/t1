代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cashguo.top/Article/details/gtijejccqc.html

[Q11] 一次插入多行
来源：http://dali.feifeiyinyue.top/Article/details/gtuagjfwup.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sxryk.cn/Article/details/gtwvmbfbhh.html

[Q12] 插入后取自增 ID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowtbltgz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jiagoushi.top/Article/details/gtdnruemlm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuetiantiany.cn/Article/details/gtitcsypbk.html

[Q13] 忽略重复插入
来源：http://dali.nwbrower.top/Article/details/gtxsczpmoy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fzhhl.top/Article/details/gthagjhamn.html

[Q14] 存在则更新（upsert）
来源：http://dali.ydzc1.top/Article/details/gtjtvuyugp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gogol.net.cn/Article/details/gtqstyzshj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigfzy.top/Article/details/gttznxwqke.html

[Q15] 查询全部
来源：http://dali.jinqigufen.top/Article/details/gtwvvwzkge.html

SELECT * FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtufjdwgcw.html

[Q16] 查询指定列
来源：http://dali.tianlin.xyz/Article/details/gtsliiwxxd.html

SELECT id, name FROM users;
来源：http://dali.xziqi.cn/Article/details/gtysfqkkuy.html

[Q17] 条件查询
来源：http://dali.feifeiyinyue.top/Article/details/gtdmvcaavd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtibccvqon.html

[Q18] 模糊匹配
来源：http://dali.xylfe.cn/Article/details/gtvaatwjrn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gaohongyu789.top/Article/details/gtfcyqidqk.html

[Q19] 范围查询
来源：http://dali.svipenyu.cn/Article/details/gtpjxppunp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yangfankeji.com/Article/details/gtlchdadtf.html

[Q20] IN 列表
来源：http://dali.fzhhl.top/Article/details/gtwlmjbfkj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.aizwys.cn/Article/details/gtystsebcm.html

[Q21] 空值判断
来源：http://dali.fengsongda.top/Article/details/gtjwoprmby.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.316326.xyz/Article/details/gtzqwufekn.html

[Q22] 排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqemsgkih.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cucudq.cn/Article/details/gtpcruzamd.html

[Q23] 分页
来源：http://dali.316326.xyz/Article/details/gtxlgfojha.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.quarkkingdee.top/Article/details/gtymcdmqjs.html

[Q24] 去重
来源：http://dali.yuanzhike.top/Article/details/gtumhdioka.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtvntlmcbg.html

[Q25] 只取前 N 条
来源：http://dali.sxryk.cn/Article/details/gtepvsqwry.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhoulong.xyz/Article/details/gtaogpoyhv.html

[Q26] 计数
来源：http://dali.bjfxy.top/Article/details/gtjapnannj.html

SELECT COUNT(*) FROM users;
来源：http://dali.ivvv.top/Article/details/gtfwjybxmw.html

[Q27] 条件计数
来源：http://dali.cheryme.top/Article/details/gtyzfdnhlb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjzabkkl.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gtvgrijzwa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtlxvobjes.html

[Q29] 最大最小值
来源：http://dali.ehwqpu.com/Article/details/gtkdndgbwu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gttqblwkwl.html

[Q30] 分组统计
来源：http://dali.gogol.net.cn/Article/details/gtompnfolm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtzmceygrd.html

[Q31] 分组后过滤
来源：http://dali.zdqjudy.top/Article/details/gtrbkhycho.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cqqwz.cn/Article/details/gtcfdmudqn.html

[Q32] 分组拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtcexjcpib.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gtljgmbrai.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ydzc1.top/Article/details/gtequylzzv.html

[Q33] 多列分组
来源：http://dali.cheryme.top/Article/details/gtktfrbwgt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuetiantiany.cn/Article/details/gtiovzfkdd.html

[Q34] 每组取第一条
来源：http://dali.nwbrower.top/Article/details/gthycycbqm.html

SELECT * FROM (
来源：http://dali.gogol.net.cn/Article/details/gtqmubsfbo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dianchejie.cn/Article/details/gtaifcdnfg.html

) t WHERE rn = 1;
来源：http://dali.jyoumei.cn/Article/details/gtxxzqikll.html

[Q35] 内连接
来源：http://dali.yuanzhike.top/Article/details/gtgltcumta.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gtzxsakniq.html

[Q36] 左连接
来源：http://dali.birdmap.top/Article/details/gtzmlhbpho.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gtehibagtw.html

[Q37] 右连接
来源：http://dali.zycfv.cn/Article/details/gtqsqmurof.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfxenzon.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tian-w.cn/Article/details/gtaviiascg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shzxlz.cn/Article/details/gtrstcmulw.html

[Q39] 自连接（查上下级）
来源：http://dali.pycfn.com/Article/details/gtdddnybwy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhiwuduotai.top/Article/details/gtswaxewzm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sufxvd.cn/Article/details/gtjtezujah.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangshuangyany.cn/Article/details/gtwqdwlvgt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cashguo.top/Article/details/gtfdoijehk.html

[Q41] 多表连接
来源：http://dali.yuxming.cn/Article/details/gtlnyyveld.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cheryme.top/Article/details/gtyeicjtcd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gotoacloud.top/Article/details/gtovazadcl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hammf.cn/Article/details/gtwpkouwud.html

[Q42] 连接条件附加过滤
来源：http://dali.hnxiangtu.top/Article/details/gtpucktztw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yongpay.top/Article/details/gtcnbygfoz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cdnleiting.top/Article/details/gtkcuthcch.html

[Q43] 标量子查询
来源：http://dali.hammf.cn/Article/details/gtyqxufwib.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gtfxmkijwq.html

[Q44] IN 子查询
来源：http://dali.zhoulong.xyz/Article/details/gtphmufdhc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ppjwa.cn/Article/details/gtynokhyfa.html

[Q45] EXISTS 判断存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgmlsddw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gtobynhtgj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aizwys.cn/Article/details/gthbaydjvf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gtcufnjyds.html

[Q47] 与平均值比较
来源：http://dali.jianghu66.top/Article/details/gtygppbhsf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zycfv.cn/Article/details/gtapjpzzgf.html

[Q48] CTE 公用表表达式
来源：http://dali.wangdashe.top/Article/details/gtamlguyty.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.redwolf501.top/Article/details/gtbnlbaimb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtranmerpw.html

[Q49] 更新单行
来源：http://dali.aizwys.cn/Article/details/gtwgrrnzxh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gtzswhoovd.html

[Q50] 批量更新
来源：http://dali.zdqjudy.top/Article/details/gtnucjpjrw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.meibo888.top/Article/details/gtbznnwsjc.html

[Q51] 用子查询更新
来源：http://dali.wangdashe.top/Article/details/gtqypcxnwz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtlryviwjr.html

[Q52] 删除指定行
来源：http://dali.pycfn.com/Article/details/gtphuodxke.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gtuetapioi.html

[Q53] 按条件删除
来源：http://dali.0kj1m.cn/Article/details/gtqirspump.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.316326.xyz/Article/details/gtugubgxcf.html

[Q54] 清空表
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnhjgpqf.html

TRUNCATE TABLE logs;
来源：http://dali.guowangkeji.top/Article/details/gtuycgtzqv.html

[Q55] 排名（并列占位）
来源：http://dali.jlsjyb.cn/Article/details/gtjsvccaou.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gtmqxtsrjs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuanzhike.top/Article/details/gthscsdmhq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gtjqawhvsp.html

[Q57] 行号
来源：http://dali.hammf.cn/Article/details/gtmqksbier.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xziqi.cn/Article/details/gtkbvnbuxs.html

[Q58] 累计求和
来源：http://dali.pengpengdd.cyou/Article/details/gtgpeuoraj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtrzwfkrdr.html

[Q59] 分组内累计
来源：http://dali.aizwys.cn/Article/details/gthkpcmlst.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtxfemeyzc.html

[Q60] 取上一行 / 下一行
来源：http://dali.aizwys.cn/Article/details/gtzjvtfqpy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hfpthk.cn/Article/details/gtugndfqor.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.birdmap.top/Article/details/gtbnjeyysv.html

[Q61] 移动平均
来源：http://dali.yvedp.cn/Article/details/gtwouauewl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtwlcptibb.html

[Q62] 分组占比
来源：http://dali.nanxuanxn.top/Article/details/gtwlkxjjvi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gttxwikzml.html

[Q63] 开启事务
来源：http://dali.ppjwa.cn/Article/details/gtkpqmsnel.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknrpspju.html

[Q64] 提交事务
来源：http://dali.ydzc1.top/Article/details/gtivshibdl.html

COMMIT;
来源：http://dali.aizwys.cn/Article/details/gtjeqalznz.html

[Q65] 回滚事务
来源：http://dali.ivvv.top/Article/details/gtvfjaxuuw.html

ROLLBACK;
来源：http://dali.zdqjudy.top/Article/details/gtbvvkyfmg.html

[Q66] 行锁查询
来源：http://dali.ydzc1.top/Article/details/gtoxftnipt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuxming.cn/Article/details/gtxhpyygqb.html

[Q67] 设置隔离级别
来源：http://dali.andypj.xyz/Article/details/gtkxandpqa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.havefunace.top/Article/details/gteguznxhz.html

[Q68] 保存点
来源：http://dali.dashuyun.cn/Article/details/gtokjhfebv.html

SAVEPOINT sp1;
来源：http://dali.ivvv.top/Article/details/gtdouatvyi.html

ROLLBACK TO sp1;
来源：http://dali.sufxvd.cn/Article/details/gtszilkwjc.html

[Q69] 查看执行计划
来源：http://dali.jiagoushi.top/Article/details/gthnlvrgpa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuanzhike.top/Article/details/gtwwpunylk.html

[Q70] 更新统计信息
来源：http://dali.yuanzhike.top/Article/details/gthpfyxdjj.html

ANALYZE TABLE users;
来源：http://dali.yanxiufei.cn/Article/details/gtfxrernbb.html

[Q71] 查看建表语句
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjmrrkbt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.birdmap.top/Article/details/gttjdxlrku.html

[Q72] 查看索引
来源：http://dali.jiagoushi.top/Article/details/gteazfogzf.html

SHOW INDEX FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtqoqwpmmm.html

[Q73] 查看表状态
来源：http://dali.ppjwa.cn/Article/details/gtbjamvaka.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.birdmap.top/Article/details/gtfdvyqpkf.html

[Q74] 强制使用索引
来源：http://dali.yuanzhike.top/Article/details/gtusynhxwr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zdqjudy.top/Article/details/gtestkaqof.html

[Q75] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gtvsrzezgi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtbpwpzjck.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nwbrower.top/Article/details/gtnkzriokg.html

[Q76] 按天统计
来源：http://dali.bjfxy.top/Article/details/gtufrpnksu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tanke756.top/Article/details/gtnlsmqmoq.html

[Q77] 时间加减
来源：http://dali.fzhhl.top/Article/details/gtpvghoouo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tian-w.cn/Article/details/gtavoiuabh.html

[Q78] 当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gttxxzutpu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangshuangyany.cn/Article/details/gtryzhaprp.html

[Q79] 字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gtvimrpixd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jianghu66.top/Article/details/gtqdervves.html

[Q80] 字符串截取
来源：http://dali.yuxming.cn/Article/details/gtesodfyhm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtezxgdnzj.html

[Q81] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gtlwfxsnyx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtegxutpwc.html

[Q82] 字符长度与字节长度
来源：http://dali.gzhubu.top/Article/details/gtmjbsyfzr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtbyuterqp.html

[Q83] 大小写转换
来源：http://dali.meibo888.top/Article/details/gtzvfqhrtk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtdcijauhn.html

[Q84] 去除首尾空格
来源：http://dali.yj202588.top/Article/details/gtubsrcxcr.html

SELECT TRIM(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtaellydwh.html

[Q85] 数值取整
来源：http://dali.xylfe.cn/Article/details/gtsiljnibg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xinyue.icu/Article/details/gttxgvexzf.html

[Q86] 读取 JSON 字段
来源：http://dali.sysykeji.top/Article/details/gtlhmfeuuq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cqqwz.cn/Article/details/gtsiadoiqr.html

[Q87] JSON 字段做条件
来源：http://dali.hfpthk.cn/Article/details/gtaptfefgf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yangfankeji.com/Article/details/gtbnwpmnpq.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenzaomai.com/Article/details/gtlarqtcdv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xylfe.cn/Article/details/gtjthxzfxi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shuidangran.top/Article/details/gttnsxruet.html

[Q89] 判断表是否存在
来源：http://dali.yuanzhike.top/Article/details/gtkxkcnnin.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.kuanghao11.cn/Article/details/gtorplojur.html

[Q90] 生成序号列
来源：http://dali.9152youxi.cn/Article/details/gtytfagtqm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzugunecc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtvukukavl.html

R. Bash 专题
来源：http://dali.gotoacloud.top/Article/details/gtojuxrpma.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gthhkeqojl.html

[R01] shebang 与严格模式
来源：http://dali.jqgfzy.top/Article/details/gtyquofehu.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzgvzzny.html

set -euo pipefail
来源：http://dali.guowangkeji.top/Article/details/gtbfalrpsi.html

[R02] 变量赋值与使用
来源：http://dali.hfpthk.cn/Article/details/gtpekzvmra.html

name="Tom"; echo "$name"
来源：http://dali.shangyingyoupin.top/Article/details/gtkqewcjsv.html

[R03] 只读变量
来源：http://dali.xuetiantiany.cn/Article/details/gtnmpwyqpe.html

readonly PI=3.14
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuapjrfcx.html

[R04] 位置参数
来源：http://dali.dashuyun.cn/Article/details/gttamtolqb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhongyouzk.top/Article/details/gtrruucgno.html

[R05] 参数默认值
来源：http://dali.jqgfzy.top/Article/details/gtencrbhgy.html

name="${1:-default}"
来源：http://dali.gaohongyu789.top/Article/details/gtwptrkbup.html

[R06] 判断命令是否存在
来源：http://dali.iojbl.cn/Article/details/gtmwunxfkm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtgnutdgbn.html

[R07] if 判断文件
来源：http://dali.fzhhl.top/Article/details/gtgodcuuor.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tianlin.xyz/Article/details/gtsvziizqs.html

[R08] 数值比较
来源：http://dali.nwbrower.top/Article/details/gtkxsskzbg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hysaishi.cn/Article/details/gtsdsgokuy.html

[R09] 字符串比较
来源：http://dali.yangfankeji.com/Article/details/gtcfcrlfoo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zycfv.cn/Article/details/gtfuysrhrw.html

[R10] 正则匹配
来源：http://dali.jqgufenzy.top/Article/details/gtcppjhlnx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gttxepvige.html

[R11] case 多分支
来源：http://dali.andypj.xyz/Article/details/gtplzmncps.html

case "$1" in
来源：http://dali.yuxming.cn/Article/details/gtzqwxxlkd.html

start) echo "启动" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtqliwaykj.html

stop)  echo "停止" ;;
来源：http://dali.xziqi.cn/Article/details/gtvjsghhjg.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtbwettooe.html

esac
来源：http://dali.cdnleiting.top/Article/details/gtslmoraio.html

[R12] for 遍历文件
来源：http://dali.hongshengwenyu.top/Article/details/gtuqavyvee.html

for f in *.txt; do echo "$f"; done
来源：http://dali.andypj.xyz/Article/details/gtxtyqveay.html

[R13] for 计数循环
来源：http://dali.smart0.xyz/Article/details/gtwwryhqxt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtueyqmffr.html

[R14] C 风格 for
来源：http://dali.hywenlv.cn/Article/details/gtwcrkvewx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gtwcvvmtko.html

[R15] while 逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtdenztoda.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sufxvd.cn/Article/details/gtqixxgvse.html

[R16] until 等待条件
来源：http://dali.nanxuanxn.top/Article/details/gtkungikwe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtpbsvtzfj.html

[R17] 数组定义与取值
来源：http://dali.zhiwuduotai.top/Article/details/gtwylbocco.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shzxlz.cn/Article/details/gtczzghxbv.html

[R18] 遍历数组
来源：http://dali.guannengcc.top/Article/details/gtnljjwtzz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtpixypgji.html

[R19] 数组长度
来源：http://dali.daxiang520.top/Article/details/gtiaxvbnbq.html

echo "${#arr[@]}"
来源：http://dali.nanxuanxn.top/Article/details/gtzmomoqbc.html

[R20] 关联数组（字典）
来源：http://dali.yueranfly.top/Article/details/gtpsflrrbl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.smart0.xyz/Article/details/gtgspxkmtv.html

[R21] 字符串长度
来源：http://dali.wangdashe.top/Article/details/gtgfycpzwg.html

echo "${#s}"
来源：http://dali.chenlongwang.top/Article/details/gtiqasicxn.html

[R22] 截取子串
来源：http://dali.sxryk.cn/Article/details/gtvpgflxkw.html

echo "${s:0:5}"
来源：http://dali.jianghu66.top/Article/details/gtolllpqaf.html

[R23] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gtvpouliqe.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxuanxn.top/Article/details/gtzbrmmfao.html

[R24] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gteafmibuj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gtoqugxefv.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenlongwang.top/Article/details/gtkwhyypbs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jiagoushi.top/Article/details/gtzcncactg.html

[R26] 命令替换
来源：http://dali.hywenlv.cn/Article/details/gtplptqirw.html

now=$(date +%F); echo "$now"
来源：http://dali.gogol.net.cn/Article/details/gtmlrmczou.html

[R27] 算术展开
来源：http://dali.316326.xyz/Article/details/gtcypwpesm.html

echo $((1 + 2 * 3))
来源：http://dali.sufxvd.cn/Article/details/gtymjisipz.html

[R28] 浮点运算
来源：http://dali.vqdsnc.cn/Article/details/gtqclcpoip.html

echo "scale=2; 10/3" | bc
来源：http://dali.haohaochexian.top/Article/details/gtgscsjjbe.html

[R29] 定义函数
来源：http://dali.sweek.top/Article/details/gtlmfxuqzh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuanzx.com/Article/details/gtlvjorlyi.html

[R30] 函数返回状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtnryqorta.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuanzhike.top/Article/details/gtobbuqfhf.html

[R31] 局部变量
来源：http://dali.0kj1m.cn/Article/details/gtxsrynbnl.html

f() { local x=1; echo "$x"; }
来源：http://dali.ybcxt.top/Article/details/gtqftniwqy.html

[R32] 参数个数校验
来源：http://dali.jqgfzy.top/Article/details/gtatywcxev.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gtnfiivvag.html

[R33] 捕获错误并提示行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwrsqhxh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guowangkeji.top/Article/details/gtayhkceew.html

[R34] 退出时清理
来源：http://dali.chenjidiqi.icu/Article/details/gtwocwsprt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gtlqvjrvkc.html

[R35] 后台执行并等待
来源：http://dali.gotoacloud.top/Article/details/gtauzeetlu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sxryk.cn/Article/details/gtddxsxvrh.html

[R36] 并发执行多个任务
来源：http://dali.dianchejie.cn/Article/details/gtdldlpnbg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.haohaochexian.top/Article/details/gtmpsithyq.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtccmlwyyt.html

files=$(ls -1)
来源：http://dali.fzhhl.top/Article/details/gtswjhmgdv.html

[R38] 管道串联
来源：http://dali.cheryme.top/Article/details/gtjmfcnzgi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258.top/Article/details/gtipbfyigi.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgufenzy.top/Article/details/gtrruttpvz.html

cmd > out.log 2>&1
来源：http://dali.mhx1999.top/Article/details/gtrtodmcwd.html

[R40] 追加写日志
来源：http://dali.c1oappe.top/Article/details/gtydbwspbt.html

echo "log" >> out.log
来源：http://dali.yangfankeji.com/Article/details/gtkomalurv.html

[R41] 丢弃输出
来源：http://dali.jinqigfzy.top/Article/details/gtpjgilodz.html

cmd >/dev/null 2>&1
来源：http://dali.ydzc1.top/Article/details/gtcixdilup.html

[R42] 输入重定向
来源：http://dali.aibaodan.cn/Article/details/gtwtrfpsmm.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gtmqsycehd.html

[R43] 按名字查找文件
来源：http://dali.iojbl.cn/Article/details/gthhorrpdv.html

find . -name "*.log" -type f
来源：http://dali.sysykeji.top/Article/details/gtkxnnbteh.html

[R44] 按修改时间查找
来源：http://dali.yongpay.top/Article/details/gtywbmlphb.html

find . -mtime -7 -type f
来源：http://dali.gotoacloud.top/Article/details/gttmqcmveq.html

[R45] 批量删除
来源：http://dali.birdmap.top/Article/details/gtplzhxkig.html

find . -name "*.tmp" -delete
来源：http://dali.c1oappe.top/Article/details/gtfnraemvf.html

[R46] 递归替换文件内容
来源：http://dali.chenjidiqi.icu/Article/details/gtosffxumq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.bjfxy.top/Article/details/gtjxpvsrrc.html

[R47] sed 单行替换
来源：http://dali.shangyingyoupin.top/Article/details/gticklgbgp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xylfe.cn/Article/details/gtsixtpdee.html

[R48] awk 取指定列
来源：http://dali.yvedp.cn/Article/details/gthygldnzl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gthvcfculs.html

[R49] awk 带条件
来源：http://dali.tanke756.top/Article/details/gtajotiyzq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daxiang520.top/Article/details/gtlenuhceb.html

[R50] awk 求和
来源：http://dali.shuidangran.top/Article/details/gtzrqkvhsy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtwflxizxx.html

[R51] 排序去重取前几
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnyqyazz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxuanxn.top/Article/details/gtrfjeorjw.html

[R52] 统计行数
来源：http://dali.ybcxt.top/Article/details/gtsfzvbgft.html

wc -l a.txt
来源：http://dali.guowangkeji.top/Article/details/gtqjsnwvdh.html

[R53] 查看文件头与实时尾
来源：http://dali.316326.xyz/Article/details/gtxhmtqkgz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gtkidutdfy.html

[R54] 比较两个文件
来源：http://dali.hnqzz.top/Article/details/gtgivusksk.html

diff a.txt b.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtglcxqwqw.html

[R55] 压缩与解压
来源：http://dali.mhx1999.top/Article/details/gtxyeebqge.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgfzy.top/Article/details/gtnlmwrfdo.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gtctikljgf.html

scp file user@host:/path/
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwmkyase.html

[R57] 远程执行命令
来源：http://dali.mhx1999.top/Article/details/gtrctmgqcg.html

ssh user@host 'uptime'
来源：http://dali.mhx1999.top/Article/details/gtbnilltac.html

[R58] 下载文件
来源：http://dali.xziqi.cn/Article/details/gtymmsyjjh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.9152youxi.cn/Article/details/gtjcuxgzsb.html

[R59] 发 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtirejcfok.html


<!-- 参考信息 -->