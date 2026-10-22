代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jiagoushi.top/Article/details/gtepkusmpn.html

[Q07] 删除表
来源：http://dali.cheryme.top/Article/details/gtuvfxbzph.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jianghu66.top/Article/details/gtwxqwrscq.html

[Q08] 创建普通索引
来源：http://dali.hammf.cn/Article/details/gthdbeekeu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrnbcdds.html

[Q09] 创建唯一索引
来源：http://dali.nanxuanxn.top/Article/details/gtvwqlcpfa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gtjsexrrto.html

[Q10] 插入单行
来源：http://dali.guowangkeji.top/Article/details/gtggumfteh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtlkccuyrt.html

[Q11] 一次插入多行
来源：http://dali.dashuyun.cn/Article/details/gtrfzpfmhu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nwbrower.top/Article/details/gtgthjwxtb.html

[Q12] 插入后取自增 ID
来源：http://dali.yuanzhike.top/Article/details/gtrcnhcidb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.kuanghao11.cn/Article/details/gtafoqhmkt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.svipenyu.cn/Article/details/gtxcgajwbz.html

[Q13] 忽略重复插入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfmsfnrp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cucudq.cn/Article/details/gtbmmauyrg.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuxming.cn/Article/details/gtdatnuxxb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ydzc1.top/Article/details/gtofgqrzji.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sysykeji.top/Article/details/gtvxonoaim.html

[Q15] 查询全部
来源：http://dali.cdnleiting.top/Article/details/gtnoexgqaj.html

SELECT * FROM users;
来源：http://dali.meibo888.top/Article/details/gtdutxlzoc.html

[Q16] 查询指定列
来源：http://dali.dianchejie.cn/Article/details/gtfwuslkyr.html

SELECT id, name FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtqywfjhdz.html

[Q17] 条件查询
来源：http://dali.haohaochexian.top/Article/details/gtuelfzjcy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hfpthk.cn/Article/details/gtbpasosla.html

[Q18] 模糊匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtmoqmaimm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.vqdsnc.cn/Article/details/gtrtoswtja.html

[Q19] 范围查询
来源：http://dali.yangfankeji.com/Article/details/gtuxrvberh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigufen.top/Article/details/gtagvqpntv.html

[Q20] IN 列表
来源：http://dali.tian-w.cn/Article/details/gtqlswggnu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xylfe.cn/Article/details/gtkjhircat.html

[Q21] 空值判断
来源：http://dali.aibaodan.cn/Article/details/gtkhewrrdg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxuanxn.top/Article/details/gteptndmnb.html

[Q22] 排序
来源：http://dali.hfpthk.cn/Article/details/gtoqhbjjqm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenzaomai.com/Article/details/gtjqcldrob.html

[Q23] 分页
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvsveyghg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daxiang520.top/Article/details/gtabbogtbv.html

[Q24] 去重
来源：http://dali.tianlin.xyz/Article/details/gtfqikdclp.html

SELECT DISTINCT city FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtjycrvgjc.html

[Q25] 只取前 N 条
来源：http://dali.chenzaomai.com/Article/details/gtnhbrtjif.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aibaodan.cn/Article/details/gteyhpptaq.html

[Q26] 计数
来源：http://dali.shanyushiyangtech.top/Article/details/gtyostvifa.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gticbwphuj.html

[Q27] 条件计数
来源：http://dali.xylfe.cn/Article/details/gtsjpnmduq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtlqwyjvcw.html

[Q28] 求和与平均
来源：http://dali.xuetiantiany.cn/Article/details/gtywrpcmaz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtdewaltlk.html

[Q29] 最大最小值
来源：http://dali.birdmap.top/Article/details/gtrwbomhqd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtbxxnzkov.html

[Q30] 分组统计
来源：http://dali.xziqi.cn/Article/details/gtkaogghgr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtvynqkgfy.html

[Q31] 分组后过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtamzjkajx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yongpay.top/Article/details/gtiqempnmc.html

[Q32] 分组拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtxibfhrsl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtchlkqnfq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.aizwys.cn/Article/details/gtsmbjhxht.html

[Q33] 多列分组
来源：http://dali.hammf.cn/Article/details/gtkpzktjio.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyfajttp.html

[Q34] 每组取第一条
来源：http://dali.gzhubu.top/Article/details/gtlpjbhkzb.html

SELECT * FROM (
来源：http://dali.wangdashe.top/Article/details/gtubzuilju.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gaohongyu789.top/Article/details/gtnyzsjnyq.html

) t WHERE rn = 1;
来源：http://dali.nwbrower.top/Article/details/gtaiwshfmp.html

[Q35] 内连接
来源：http://dali.sysykeji.top/Article/details/gtqucmmgcy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gtyzkjmezn.html

[Q36] 左连接
来源：http://dali.9152youxi.cn/Article/details/gtphxbzuhk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gteuhtxfhm.html

[Q37] 右连接
来源：http://dali.yj202588.top/Article/details/gtywfkwpap.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shuidangran.top/Article/details/gtvgowuogv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zdqjudy.top/Article/details/gtxqiwaqft.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sweek.top/Article/details/gtnhhpurnf.html

[Q39] 自连接（查上下级）
来源：http://dali.dashuyun.cn/Article/details/gtnnzjwpzn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangdashe.top/Article/details/gtttcwvhpm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.guannengcc.top/Article/details/gtfjasdnxc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gtixnoycnk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sweek.top/Article/details/gtxoqupkwm.html

[Q41] 多表连接
来源：http://dali.redwolf501.top/Article/details/gtamimiixa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigfzy.top/Article/details/gtfmfknpeh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cucudq.cn/Article/details/gtuqmytaxl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ivvv.top/Article/details/gtkcimjeuk.html

[Q42] 连接条件附加过滤
来源：http://dali.hfpthk.cn/Article/details/gtipdoxgvm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.0kj1m.cn/Article/details/gtmtfbcomz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgufenzy.top/Article/details/gtumszbspd.html

[Q43] 标量子查询
来源：http://dali.daria6918.cn/Article/details/gthkyttzes.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xylfe.cn/Article/details/gtrcuckcgr.html

[Q44] IN 子查询
来源：http://dali.jinqigufen.top/Article/details/gtgkgkymas.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jianghu66.top/Article/details/gtyrypicxa.html

[Q45] EXISTS 判断存在
来源：http://dali.sufxvd.cn/Article/details/gtqoruhhei.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gtzhpfnqwf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysnxeuxe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtdhzhastc.html

[Q47] 与平均值比较
来源：http://dali.meibo888.top/Article/details/gtdnouggya.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ydzc1.top/Article/details/gtoolmlfwz.html

[Q48] CTE 公用表表达式
来源：http://dali.c1oappe.top/Article/details/gtpummlstf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuanzx.com/Article/details/gthiwofohl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yueranfly.top/Article/details/gtmrmfjkts.html

[Q49] 更新单行
来源：http://dali.hysaishi.cn/Article/details/gtjmsfikmf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gtckvkeyvw.html

[Q50] 批量更新
来源：http://dali.gaohongyu789.top/Article/details/gtdukqprpn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gtbarujtxn.html

[Q51] 用子查询更新
来源：http://dali.pycfn.com/Article/details/gtntvvtnjl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sxryk.cn/Article/details/gtqhqyffrc.html

[Q52] 删除指定行
来源：http://dali.jlsjyb.cn/Article/details/gtwfvyrbsk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtznjurghb.html

[Q53] 按条件删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdnjcewe.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhxwtlvv.html

[Q54] 清空表
来源：http://dali.mhx1999.top/Article/details/gtuxeuvywv.html

TRUNCATE TABLE logs;
来源：http://dali.wangdashe.top/Article/details/gtzrdglpqv.html

[Q55] 排名（并列占位）
来源：http://dali.ivvv.top/Article/details/gtqbrhoacu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gtdpzqdbyp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258.top/Article/details/gthgoqhwwc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zycfv.cn/Article/details/gtmigapocx.html

[Q57] 行号
来源：http://dali.shangyingyoupin.top/Article/details/gtzloajilx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.mhx1999.top/Article/details/gttylkccnh.html

[Q58] 累计求和
来源：http://dali.zhongyouzk.top/Article/details/gtzeswyzqd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtspfhfqvx.html

[Q59] 分组内累计
来源：http://dali.yuxming.cn/Article/details/gtvduoyioz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtwviyvmku.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhixingplan.top/Article/details/gtbjplaetp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.c1oappe.top/Article/details/gttjacyuoe.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtrdhvotte.html

[Q61] 移动平均
来源：http://dali.andypj.xyz/Article/details/gtterxjuvm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtdtzyveop.html

[Q62] 分组占比
来源：http://dali.hnqzz.top/Article/details/gtzsnwbmhr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtbklcndsq.html

[Q63] 开启事务
来源：http://dali.xuetiantiany.cn/Article/details/gtlsefrlok.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ivvv.top/Article/details/gtbyijurcn.html

[Q64] 提交事务
来源：http://dali.shuidangran.top/Article/details/gtdlalgcpo.html

COMMIT;
来源：http://dali.ywan-chungtsiang.top/Article/details/gteiyvovts.html

[Q65] 回滚事务
来源：http://dali.sweek.top/Article/details/gtxvjibhsm.html

ROLLBACK;
来源：http://dali.zycfv.cn/Article/details/gtoakpxdet.html

[Q66] 行锁查询
来源：http://dali.sufxvd.cn/Article/details/gtkatcgzzn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sxryk.cn/Article/details/gttgprzzgm.html

[Q67] 设置隔离级别
来源：http://dali.quarkkingdee.top/Article/details/gtsaqpqrfz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nwbrower.top/Article/details/gtjolfmebg.html

[Q68] 保存点
来源：http://dali.ppjwa.cn/Article/details/gtavyzzdti.html

SAVEPOINT sp1;
来源：http://dali.gogol.net.cn/Article/details/gtrvldchtg.html

ROLLBACK TO sp1;
来源：http://dali.meibo888.top/Article/details/gtsnisyqcm.html

[Q69] 查看执行计划
来源：http://dali.chenlongwang.top/Article/details/gthqhrpxjv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangdashe.top/Article/details/gtjbgykunx.html

[Q70] 更新统计信息
来源：http://dali.jinqigfzy.top/Article/details/gtxeffpmmr.html

ANALYZE TABLE users;
来源：http://dali.hysaishi.cn/Article/details/gtkxduggub.html

[Q71] 查看建表语句
来源：http://dali.shzxlz.cn/Article/details/gtclijvtmy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shzxlz.cn/Article/details/gtndxohzka.html

[Q72] 查看索引
来源：http://dali.hysaishi.cn/Article/details/gtbmxhqwis.html

SHOW INDEX FROM users;
来源：http://dali.pycfn.com/Article/details/gtpcxljpfe.html

[Q73] 查看表状态
来源：http://dali.yj202588.top/Article/details/gtlxdhhqir.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxinkj.top/Article/details/gtbcgxsdbo.html

[Q74] 强制使用索引
来源：http://dali.cheryme.top/Article/details/gtimbfeowo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aibaodan.cn/Article/details/gttwcarqob.html

[Q75] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gtcfsklcha.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtjswwjjah.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258888.top/Article/details/gteyunznnl.html

[Q76] 按天统计
来源：http://dali.cdnleiting.top/Article/details/gtlsxbouur.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhiwuduotai.top/Article/details/gtpyqoyifm.html

[Q77] 时间加减
来源：http://dali.guowangkeji.top/Article/details/gtpgxuvkjq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdjvdwnn.html

[Q78] 当前时间
来源：http://dali.hammf.cn/Article/details/gtdfgtrjdt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigfzy.top/Article/details/gtpsowzhaz.html

[Q79] 字符串拼接
来源：http://dali.hnqzz.top/Article/details/gtriciqtrb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.guowangkeji.top/Article/details/gtqtgpnmlq.html

[Q80] 字符串截取
来源：http://dali.wangshuangyany.cn/Article/details/gtzarwmpql.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtaxmlrjll.html

[Q81] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gtzzvnsxco.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtloeymdan.html

[Q82] 字符长度与字节长度
来源：http://dali.gotoacloud.top/Article/details/gtrhdsbajq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gttrzlzqgh.html

[Q83] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtudhcljcx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtyzfiqbvi.html

[Q84] 去除首尾空格
来源：http://dali.nanxuanxn.top/Article/details/gtclrwzyui.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtiuekmzyy.html

[Q85] 数值取整
来源：http://dali.redwolf501.top/Article/details/gtlrsldunc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yongpay.top/Article/details/gttzfvbyob.html

[Q86] 读取 JSON 字段
来源：http://dali.gaohongyu789.top/Article/details/gtjwvezxke.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dianchejie.cn/Article/details/gtymfiaubb.html

[Q87] JSON 字段做条件
来源：http://dali.cashguo.top/Article/details/gttkpwibos.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sufxvd.cn/Article/details/gttpxhbinu.html

[Q88] 行转列（条件聚合）
来源：http://dali.sysykeji.top/Article/details/gtbwjnywgj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gotoacloud.top/Article/details/gtpnixigmv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtdeybjhhs.html

[Q89] 判断表是否存在
来源：http://dali.ehwqpu.com/Article/details/gtdvlliwrc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnksztqvf.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqzknngt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhixingplan.top/Article/details/gtbxoieicd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtrkdsnqqj.html

R. Bash 专题
来源：http://dali.zhoulong.xyz/Article/details/gtlrtyzkab.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gttinltoic.html

[R01] shebang 与严格模式
来源：http://dali.nwbrower.top/Article/details/gtahjqsrhu.html

#!/usr/bin/env bash
来源：http://dali.nanxinkj.top/Article/details/gtraibknpc.html

set -euo pipefail
来源：http://dali.guannengcc.top/Article/details/gtvdjdxiir.html

[R02] 变量赋值与使用
来源：http://dali.0kj1m.cn/Article/details/gtxlinwdcn.html

name="Tom"; echo "$name"
来源：http://dali.yvedp.cn/Article/details/gtskrqrebm.html

[R03] 只读变量
来源：http://dali.xuanzx.com/Article/details/gtmseiends.html

readonly PI=3.14
来源：http://dali.chenzaomai.com/Article/details/gtjusribmm.html

[R04] 位置参数
来源：http://dali.jinqigufen.top/Article/details/gthjuqchqu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.mhx1999.top/Article/details/gtweljvlgw.html

[R05] 参数默认值
来源：http://dali.ppjwa.cn/Article/details/gtrgwglhmx.html

name="${1:-default}"
来源：http://dali.svipenyu.cn/Article/details/gtyntqfwre.html

[R06] 判断命令是否存在
来源：http://dali.zdqjudy.top/Article/details/gtqnvzprxi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gtslyqpmtg.html

[R07] if 判断文件
来源：http://dali.xinyue.icu/Article/details/gtfvvkcyng.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ybcxt.top/Article/details/gtnabyaxjy.html

[R08] 数值比较
来源：http://dali.sysykeji.top/Article/details/gtbtklsrbo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cashguo.top/Article/details/gthrsmziwr.html

[R09] 字符串比较
来源：http://dali.ehwqpu.com/Article/details/gtdwdslajw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.0kj1m.cn/Article/details/gttyqrsczb.html

[R10] 正则匹配
来源：http://dali.yuxming.cn/Article/details/gtsgssnoea.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ybcxt.top/Article/details/gtrsomljki.html

[R11] case 多分支
来源：http://dali.wangshuangyany.cn/Article/details/gtrfrbrcku.html

case "$1" in
来源：http://dali.ehwqpu.com/Article/details/gtpusyonjx.html

start) echo "启动" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtxnbjalte.html

stop)  echo "停止" ;;
来源：http://dali.redwolf501.top/Article/details/gttaxoqkcd.html

*)     echo "未知命令" ;;
来源：http://dali.xziqi.cn/Article/details/gtzrtkubdx.html

esac
来源：http://dali.fzhhl.top/Article/details/gtdayfnnpm.html

[R12] for 遍历文件
来源：http://dali.ybcxt.top/Article/details/gthnlronih.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtvqjvlrsu.html

[R13] for 计数循环
来源：http://dali.fzhhl.top/Article/details/gtmgacohnh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqiayczv.html

[R14] C 风格 for
来源：http://dali.tanke756.top/Article/details/gtiizexflx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gtwcidekyk.html

[R15] while 逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtyyygrfah.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnruwcsbn.html

[R16] until 等待条件
来源：http://dali.yj20258.top/Article/details/gtkunjddpw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkbkdgjc.html

[R17] 数组定义与取值
来源：http://dali.9152youxi.cn/Article/details/gtqttrqyjt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.andypj.xyz/Article/details/gtwotewiww.html

[R18] 遍历数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtvuwnnrqe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtwafangan.html

[R19] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfzdsowe.html

echo "${#arr[@]}"
来源：http://dali.havefunace.top/Article/details/gtuhynnsur.html

[R20] 关联数组（字典）
来源：http://dali.tanke756.top/Article/details/gtmdtcsxli.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cqqwz.cn/Article/details/gtxhrswwzo.html

[R21] 字符串长度
来源：http://dali.fzhhl.top/Article/details/gtyhwavxfh.html

echo "${#s}"
来源：http://dali.yongpay.top/Article/details/gtcfdvtqfd.html

[R22] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gtavvdnejy.html

echo "${s:0:5}"
来源：http://dali.jqgufenzy.top/Article/details/gtrytlmgwu.html

[R23] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gtvtklfccf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daria6918.cn/Article/details/gtfocpvebx.html

[R24] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gtwrjthrbo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jianghu66.top/Article/details/gtiupyismr.html

[R25] 去后缀 / 去前缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtwenjls.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxuanxn.top/Article/details/gtglvilgtx.html

[R26] 命令替换
来源：http://dali.gotoacloud.top/Article/details/gtdbamyndl.html

now=$(date +%F); echo "$now"
来源：http://dali.zdqjudy.top/Article/details/gtumqgwmik.html

[R27] 算术展开
来源：http://dali.haohaochexian.top/Article/details/gtinbpvizc.html

echo $((1 + 2 * 3))
来源：http://dali.cashguo.top/Article/details/gtzdvxusun.html

[R28] 浮点运算
来源：http://dali.xylfe.cn/Article/details/gtpbsyupae.html

echo "scale=2; 10/3" | bc
来源：http://dali.aibaodan.cn/Article/details/gtxefnhqan.html

[R29] 定义函数
来源：http://dali.ybcxt.top/Article/details/gtzodcyune.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenjidiqi.icu/Article/details/gtbrxnjtsh.html

[R30] 函数返回状态码
来源：http://dali.zdqjudy.top/Article/details/gtabdurcmu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tianlin.xyz/Article/details/gtrzqlnrpo.html

[R31] 局部变量
来源：http://dali.pycfn.com/Article/details/gtqmjiraaj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhengqikj.top/Article/details/gtvfbpbhza.html

[R32] 参数个数校验
来源：http://dali.yonumen.top/Article/details/gtrdlxwzyd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gtzmgjflcb.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxuanxn.top/Article/details/gtzjvpnbot.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.bjfxy.top/Article/details/gttywuizlx.html

[R34] 退出时清理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtruwhxisw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gthjiravez.html

[R35] 后台执行并等待
来源：http://dali.zhoulong.xyz/Article/details/gtkooaoifg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwatgteaj.html

[R36] 并发执行多个任务
来源：http://dali.chenlongwang.top/Article/details/gtnbfdtomg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.smart0.xyz/Article/details/gtnwjwbhcl.html

[R37] 把输出赋给变量
来源：http://dali.jyoumei.cn/Article/details/gtsajyjuyg.html

files=$(ls -1)
来源：http://dali.yonumen.top/Article/details/gthsrlmpgv.html

[R38] 管道串联
来源：http://dali.fengsongda.top/Article/details/gtqyybowgs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gtkrpqnume.html

[R39] 重定向标准输出与错误
来源：http://dali.tianlin.xyz/Article/details/gtnfxmjpae.html

cmd > out.log 2>&1
来源：http://dali.daxiang520.top/Article/details/gtzlhumeoh.html

[R40] 追加写日志
来源：http://dali.yueranfly.top/Article/details/gtdrplejmq.html

echo "log" >> out.log
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtlgwhkj.html

[R41] 丢弃输出
来源：http://dali.guannengcc.top/Article/details/gtctlkptnv.html

cmd >/dev/null 2>&1
来源：http://dali.nwbrower.top/Article/details/gtqsknztxy.html

[R42] 输入重定向
来源：http://dali.gotoacloud.top/Article/details/gtqjvzduzz.html

wc -l < a.txt
来源：http://dali.9152youxi.cn/Article/details/gtqwlnjkcb.html

[R43] 按名字查找文件
来源：http://dali.jinqigfzy.top/Article/details/gtntyvfbdw.html

find . -name "*.log" -type f
来源：http://dali.xziqi.cn/Article/details/gtpjntljho.html

[R44] 按修改时间查找
来源：http://dali.wangdashe.top/Article/details/gtqciobopx.html

find . -mtime -7 -type f
来源：http://dali.tian-w.cn/Article/details/gtwtyaogqr.html

[R45] 批量删除
来源：http://dali.shanyushiyangtech.top/Article/details/gtbcbvybjc.html

find . -name "*.tmp" -delete
来源：http://dali.ehwqpu.com/Article/details/gtphchxbsg.html

[R46] 递归替换文件内容
来源：http://dali.zhongyouzk.top/Article/details/gtgstaxfyj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258888.top/Article/details/gtxovmnrun.html

[R47] sed 单行替换
来源：http://dali.jqgufenzy.top/Article/details/gteswfqznk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daxiang520.top/Article/details/gtzvudmzzw.html

[R48] awk 取指定列
来源：http://dali.mhx1999.top/Article/details/gtrwpbgodp.html

awk '{print $1, $3}' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtbygtooso.html

[R49] awk 带条件
来源：http://dali.vqdsnc.cn/Article/details/gtwzpbfych.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yonumen.top/Article/details/gtiglvefzo.html

[R50] awk 求和
来源：http://dali.pycfn.com/Article/details/gtumngkutb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258888.top/Article/details/gteoxxkbsz.html

[R51] 排序去重取前几
来源：http://dali.gzhubu.top/Article/details/gtuvyyrsod.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jiagoushi.top/Article/details/gtgbeadcmx.html

[R52] 统计行数
来源：http://dali.dashuyun.cn/Article/details/gtezvsaexd.html

wc -l a.txt
来源：http://dali.ydzc1.top/Article/details/gtuglbqoui.html

[R53] 查看文件头与实时尾
来源：http://dali.yonumen.top/Article/details/gtvmecusmc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hysaishi.cn/Article/details/gtaedjmqyb.html

[R54] 比较两个文件
来源：http://dali.jyoumei.cn/Article/details/gtwfykwskx.html

diff a.txt b.txt
来源：http://dali.andypj.xyz/Article/details/gtpsxdbxil.html

[R55] 压缩与解压
来源：http://dali.jinghuilouyu.cn/Article/details/gtifwgtlki.html


<!-- 参考信息 -->