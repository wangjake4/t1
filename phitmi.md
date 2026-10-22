代发 wailian999

);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2puwxmywq.html

[Q03] 增加列
来源：http://dali.aizwys.cn/Article/details/gt2vuealcgb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jyoumei.cn/Article/details/gt2eyhvauph.html

[Q04] 修改列类型
来源：http://dali.zhixingplan.top/Article/details/gt2begqdfjr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnqzz.top/Article/details/gt2qtlfrlqj.html

[Q05] 重命名列
来源：http://dali.bjfxy.top/Article/details/gt2mvtcbxts.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xylfe.cn/Article/details/gt2nhdqunat.html

[Q06] 删除列
来源：http://dali.iojbl.cn/Article/details/gt2yeodagva.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hfpthk.cn/Article/details/gt2gvfufhun.html

[Q07] 删除表
来源：http://dali.316326.xyz/Article/details/gt2inofywyg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinqigufen.top/Article/details/gt2lqbrrxxo.html

[Q08] 创建普通索引
来源：http://dali.feifeiyinyue.top/Article/details/gt2lploevux.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gt2fpcqoyxm.html

[Q09] 创建唯一索引
来源：http://dali.yuanzhike.top/Article/details/gt2tbpclwjy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ysgbutit.html

[Q10] 插入单行
来源：http://dali.vqdsnc.cn/Article/details/gt2ugfftchl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gzhubu.top/Article/details/gt2hhjeqgib.html

[Q11] 一次插入多行
来源：http://dali.aizwys.cn/Article/details/gt2ibxivpxm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gt2ueyugvjg.html

[Q12] 插入后取自增 ID
来源：http://dali.smart0.xyz/Article/details/gt2cgplrvkf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yqswqdpo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hongshengwenyu.top/Article/details/gt2nyggugqr.html

[Q13] 忽略重复插入
来源：http://dali.meibo888.top/Article/details/gt2bzwgsrop.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gt2caonqnun.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxinkj.top/Article/details/gt2orfsmdgp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cqqwz.cn/Article/details/gt2cezglcjo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulfklemq.html

[Q15] 查询全部
来源：http://dali.hywenlv.cn/Article/details/gt2epstcocy.html

SELECT * FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2dufserij.html

[Q16] 查询指定列
来源：http://dali.tanke756.top/Article/details/gt2rcyrvkfl.html

SELECT id, name FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2bjzvutmq.html

[Q17] 条件查询
来源：http://dali.havefunace.top/Article/details/gt2rhtamyqb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sxryk.cn/Article/details/gt2tylkebhf.html

[Q18] 模糊匹配
来源：http://dali.daria6918.cn/Article/details/gt2dahupwpo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258.top/Article/details/gt2wvhrhpjl.html

[Q19] 范围查询
来源：http://dali.hysaishi.cn/Article/details/gt2oixsrtmj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj202588.top/Article/details/gt2jrcpqftz.html

[Q20] IN 列表
来源：http://dali.dianchejie.cn/Article/details/gt2prnfpnuh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xinyue.icu/Article/details/gt2abokosgi.html

[Q21] 空值判断
来源：http://dali.nanxuanxn.top/Article/details/gt2dzaiqgjt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sysykeji.top/Article/details/gt2csyxtpay.html

[Q22] 排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oxvvrhqc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhongyouzk.top/Article/details/gt2fypeuksa.html

[Q23] 分页
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vkivfyop.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhongyouzk.top/Article/details/gt2dplbrulb.html

[Q24] 去重
来源：http://dali.c1oappe.top/Article/details/gt2bhwnjthj.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2dcclcmpe.html

[Q25] 只取前 N 条
来源：http://dali.316326.xyz/Article/details/gt2taajnlcs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cfcljxdn.html

[Q26] 计数
来源：http://dali.xziqi.cn/Article/details/gt2jovlnthc.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rtfrkzkt.html

[Q27] 条件计数
来源：http://dali.yuanzhike.top/Article/details/gt2txnifzpl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2apiozsju.html

[Q28] 求和与平均
来源：http://dali.zhoulong.xyz/Article/details/gt2mqyyvhrc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2yvujdwvu.html

[Q29] 最大最小值
来源：http://dali.sweek.top/Article/details/gt2vjmuyybb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2zmdnrzcx.html

[Q30] 分组统计
来源：http://dali.c1oappe.top/Article/details/gt2svehvket.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gt2cnfppnfu.html

[Q31] 分组后过滤
来源：http://dali.bjfxy.top/Article/details/gt2avnmfhod.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.meibo888.top/Article/details/gt2hankpcnd.html

[Q32] 分组拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gt2zjbwkyeg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gt2htccelzk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.9152youxi.cn/Article/details/gt2bkwikmtd.html

[Q33] 多列分组
来源：http://dali.gogol.net.cn/Article/details/gt2nrgdsdns.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2apccvfan.html

[Q34] 每组取第一条
来源：http://dali.mhx1999.top/Article/details/gt2zvwylbel.html

SELECT * FROM (
来源：http://dali.tanke756.top/Article/details/gt2wujithjn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258.top/Article/details/gt2jsfunkpc.html

) t WHERE rn = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2dnpyclob.html

[Q35] 内连接
来源：http://dali.zhengqikj.top/Article/details/gt2hamorcgm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenjidiqi.icu/Article/details/gt2rfxolmat.html

[Q36] 左连接
来源：http://dali.guannengcc.top/Article/details/gt2wypponak.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gt2waijneqm.html

[Q37] 右连接
来源：http://dali.haohaochexian.top/Article/details/gt2vmpotfel.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ybcxt.top/Article/details/gt2grahrbkp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zvakozlt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shuidangran.top/Article/details/gt2urnafsrg.html

[Q39] 自连接（查上下级）
来源：http://dali.vqdsnc.cn/Article/details/gt2xojwadxp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gotoacloud.top/Article/details/gt2ugweskvx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.redwolf501.top/Article/details/gt2tzvmuqip.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qqvbmwkk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hysaishi.cn/Article/details/gt2ajdbvfmq.html

[Q41] 多表连接
来源：http://dali.shzxlz.cn/Article/details/gt2nnysvvln.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xylfe.cn/Article/details/gt2tkzfzgue.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258.top/Article/details/gt2ebobmbdo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.pycfn.com/Article/details/gt2lnuuruuw.html

[Q42] 连接条件附加过滤
来源：http://dali.ppjwa.cn/Article/details/gt2svpcrmjl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgufenzy.top/Article/details/gt2ahssnecd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.havefunace.top/Article/details/gt2mplonrqc.html

[Q43] 标量子查询
来源：http://dali.yangfankeji.com/Article/details/gt2ixzzuawq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.vqdsnc.cn/Article/details/gt2mjolkzuy.html

[Q44] IN 子查询
来源：http://dali.dianchejie.cn/Article/details/gt2qtbohgdy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.bjfxy.top/Article/details/gt2ipuznqsh.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258888.top/Article/details/gt2ajujqxnx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gt2pxfhplwq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.snrcjt.cn/Article/details/gt2bicuksbn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gt2vnkigbpb.html

[Q47] 与平均值比较
来源：http://dali.316326.xyz/Article/details/gt2vflxjbmo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jlsjyb.cn/Article/details/gt2iymlqmyb.html

[Q48] CTE 公用表表达式
来源：http://dali.jlsjyb.cn/Article/details/gt2noxgmkaj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sweek.top/Article/details/gt2hzpixcsk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cdnleiting.top/Article/details/gt2uzfcixlq.html

[Q49] 更新单行
来源：http://dali.hnxiangtu.top/Article/details/gt2qrofftkx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gt2trnfyhtv.html

[Q50] 批量更新
来源：http://dali.jiagoushi.top/Article/details/gt2czbvsdki.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gnfmzlll.html

[Q51] 用子查询更新
来源：http://dali.chenlongwang.top/Article/details/gt2csvyyrfe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hysaishi.cn/Article/details/gt2elaakvxe.html

[Q52] 删除指定行
来源：http://dali.9152youxi.cn/Article/details/gt2dwqooiki.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gt2jnrgnhgf.html

[Q53] 按条件删除
来源：http://dali.iojbl.cn/Article/details/gt2dxpcbimx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gt2kwnsmory.html

[Q54] 清空表
来源：http://dali.dashuyun.cn/Article/details/gt2nkoqpqer.html

TRUNCATE TABLE logs;
来源：http://dali.dianchejie.cn/Article/details/gt2shwyqkyd.html

[Q55] 排名（并列占位）
来源：http://dali.jqgufenzy.top/Article/details/gt2posjysqe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ivvv.top/Article/details/gt2zbqcgjej.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yonumen.top/Article/details/gt2kqisjpld.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.havefunace.top/Article/details/gt2mpfgtyrk.html

[Q57] 行号
来源：http://dali.wangshuangyany.cn/Article/details/gt2bwysumms.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2rsmdcmve.html

[Q58] 累计求和
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yiupwnjs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2wecdxfwd.html

[Q59] 分组内累计
来源：http://dali.sufxvd.cn/Article/details/gt2yqsuoezt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2wbwnqmxn.html

[Q60] 取上一行 / 下一行
来源：http://dali.andypj.xyz/Article/details/gt2ivducccz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sysykeji.top/Article/details/gt2pftimnrb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2ggjlxubl.html

[Q61] 移动平均
来源：http://dali.zhixingplan.top/Article/details/gt2eituajht.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2gdpdtpgr.html

[Q62] 分组占比
来源：http://dali.jlsjyb.cn/Article/details/gt2rynqohmd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gt2duhavqoa.html

[Q63] 开启事务
来源：http://dali.cqqwz.cn/Article/details/gt2pixtrlci.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgfzy.top/Article/details/gt2ritwweyp.html

[Q64] 提交事务
来源：http://dali.smart0.xyz/Article/details/gt2snanrtwn.html

COMMIT;
来源：http://dali.yangfankeji.com/Article/details/gt2fstrcfwl.html

[Q65] 回滚事务
来源：http://dali.feifeiyinyue.top/Article/details/gt2txbhxmpv.html

ROLLBACK;
来源：http://dali.zhoulong.xyz/Article/details/gt2lmntactj.html

[Q66] 行锁查询
来源：http://dali.jinqigufen.top/Article/details/gt2honmvdge.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yvedp.cn/Article/details/gt2grskmnmd.html

[Q67] 设置隔离级别
来源：http://dali.chenjidiqi.icu/Article/details/gt2kwtfmiqe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sufxvd.cn/Article/details/gt2zsspftuw.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gt2pnvpikex.html

SAVEPOINT sp1;
来源：http://dali.nwbrower.top/Article/details/gt2tayvnolb.html

ROLLBACK TO sp1;
来源：http://dali.cheryme.top/Article/details/gt2sldpgqwh.html

[Q69] 查看执行计划
来源：http://dali.jiagoushi.top/Article/details/gt2csuobzaj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenjidiqi.icu/Article/details/gt2ircfvkqn.html

[Q70] 更新统计信息
来源：http://dali.cqqwz.cn/Article/details/gt2tmyrltcq.html

ANALYZE TABLE users;
来源：http://dali.svipenyu.cn/Article/details/gt2muowurfn.html

[Q71] 查看建表语句
来源：http://dali.chenlongwang.top/Article/details/gt2zalsybpf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shuidangran.top/Article/details/gt2fmfnjqfx.html

[Q72] 查看索引
来源：http://dali.0kj1m.cn/Article/details/gt2gmwehzyg.html

SHOW INDEX FROM users;
来源：http://dali.ivvv.top/Article/details/gt2apbbepub.html

[Q73] 查看表状态
来源：http://dali.redwolf501.top/Article/details/gt2kthokrfp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gt2vdemwupf.html

[Q74] 强制使用索引
来源：http://dali.zhoulong.xyz/Article/details/gt2xuazlyvp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xylfe.cn/Article/details/gt2qqqpupas.html

[Q75] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gt2jdxfzenz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2tzbcqkzq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ivvv.top/Article/details/gt2cqbujmxv.html

[Q76] 按天统计
来源：http://dali.fzhhl.top/Article/details/gt2nmtyqfzl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pengpengdd.cyou/Article/details/gt2xisayftm.html

[Q77] 时间加减
来源：http://dali.vqdsnc.cn/Article/details/gt2lnlwrxqj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sxryk.cn/Article/details/gt2fnjvbeks.html

[Q78] 当前时间
来源：http://dali.zhongyouzk.top/Article/details/gt2sojvpjkx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgufenzy.top/Article/details/gt2ymjrohbk.html

[Q79] 字符串拼接
来源：http://dali.sxryk.cn/Article/details/gt2mrgdhvjn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tianlin.xyz/Article/details/gt2tfoazgjj.html

[Q80] 字符串截取
来源：http://dali.gzhubu.top/Article/details/gt2fhdqoams.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2xpsdslup.html

[Q81] 字符串替换
来源：http://dali.aibaodan.cn/Article/details/gt2ppsvtkuq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2tauanvvx.html

[Q82] 字符长度与字节长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2zauvclen.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2tlnoypdq.html

[Q83] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gt2lgnnzhzo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2zbxukuth.html

[Q84] 去除首尾空格
来源：http://dali.ybcxt.top/Article/details/gt2ywrmjxey.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2zpaifqlv.html

[Q85] 数值取整
来源：http://dali.hnqzz.top/Article/details/gt2cypecilv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tian-w.cn/Article/details/gt2xjjlobla.html

[Q86] 读取 JSON 字段
来源：http://dali.kuanghao11.cn/Article/details/gt2bibditnk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gaohongyu789.top/Article/details/gt2znrjkaxu.html

[Q87] JSON 字段做条件
来源：http://dali.iojbl.cn/Article/details/gt2eraocfhs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hongshengwenyu.top/Article/details/gt2hsxgsdrc.html

[Q88] 行转列（条件聚合）
来源：http://dali.shangyingyoupin.top/Article/details/gt2mtgnknsa.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jianghu66.top/Article/details/gt2ihwlplxu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukthfdka.html

[Q89] 判断表是否存在
来源：http://dali.haohaochexian.top/Article/details/gt2yqyrvpkg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jianghu66.top/Article/details/gt2yhdhnvod.html

[Q90] 生成序号列
来源：http://dali.cashguo.top/Article/details/gt2ahqkiull.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgfzy.top/Article/details/gt2yhgfzksl.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2xggchbqy.html

R. Bash 专题
来源：http://dali.zhongyouzk.top/Article/details/gt2nyrxbhmv.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2zzqyvohm.html

[R01] shebang 与严格模式
来源：http://dali.vqdsnc.cn/Article/details/gt2yyomlngo.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojdgnahd.html

set -euo pipefail
来源：http://dali.haohaochexian.top/Article/details/gt2eiwyhyda.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gt2itkqhpnw.html

name="Tom"; echo "$name"
来源：http://dali.mhx1999.top/Article/details/gt2ajcgikif.html

[R03] 只读变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2ywpmaqzz.html

readonly PI=3.14
来源：http://dali.cdnleiting.top/Article/details/gt2sctciumu.html

[R04] 位置参数
来源：http://dali.shzxlz.cn/Article/details/gt2sgomsfop.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.snrcjt.cn/Article/details/gt2otvnwazl.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gt2bksbfwtf.html

name="${1:-default}"
来源：http://dali.jyoumei.cn/Article/details/gt2ohwpexrf.html

[R06] 判断命令是否存在
来源：http://dali.yvedp.cn/Article/details/gt2igppxvky.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2szeneqzm.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gt2tlojatnj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yueranfly.top/Article/details/gt2lhlosgvt.html

[R08] 数值比较
来源：http://dali.smart0.xyz/Article/details/gt2wrvmieiv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangdashe.top/Article/details/gt2yralxapw.html

[R09] 字符串比较
来源：http://dali.guannengcc.top/Article/details/gt2xzzucamm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gt2vbhmghpa.html

[R10] 正则匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bezqkpfi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gt2chnovedb.html

[R11] case 多分支
来源：http://dali.yongpay.top/Article/details/gt2nmrcqlil.html

case "$1" in
来源：http://dali.jinqigfzy.top/Article/details/gt2cntxyxvg.html

start) echo "启动" ;;
来源：http://dali.0kj1m.cn/Article/details/gt2upkvarji.html

stop)  echo "停止" ;;
来源：http://dali.daria6918.cn/Article/details/gt2kjvxcvhn.html

*)     echo "未知命令" ;;
来源：http://dali.andypj.xyz/Article/details/gt2zggynxlq.html

esac
来源：http://dali.xuanzx.com/Article/details/gt2zyytelvv.html

[R12] for 遍历文件
来源：http://dali.pycfn.com/Article/details/gt2dhdiludv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ybcxt.top/Article/details/gt2oifvcbfd.html

[R13] for 计数循环
来源：http://dali.jyoumei.cn/Article/details/gt2jqhcbtod.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gpjsspyy.html

[R14] C 风格 for
来源：http://dali.xylfe.cn/Article/details/gt2vbkfrzos.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fzhhl.top/Article/details/gt2waybuefa.html

[R15] while 逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gt2etafnbkq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guannengcc.top/Article/details/gt2ctxohkme.html

[R16] until 等待条件
来源：http://dali.hnxiangtu.top/Article/details/gt2tqjiohie.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xziqi.cn/Article/details/gt2kyfvqwjb.html

[R17] 数组定义与取值
来源：http://dali.feifeiyinyue.top/Article/details/gt2toxzirhd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sweek.top/Article/details/gt2xgwifkun.html

[R18] 遍历数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2rcnhsagh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.iojbl.cn/Article/details/gt2qmqeisyi.html

[R19] 数组长度
来源：http://dali.yuxming.cn/Article/details/gt2xyjjkpkq.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gt2gkryuepy.html

[R20] 关联数组（字典）
来源：http://dali.yangfankeji.com/Article/details/gt2vpzcbivc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daria6918.cn/Article/details/gt2oeekiplh.html

[R21] 字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2npatiolq.html

echo "${#s}"
来源：http://dali.nanxuanxn.top/Article/details/gt2tfpiuzuu.html

[R22] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gt2rsmoollt.html

echo "${s:0:5}"
来源：http://dali.wangdashe.top/Article/details/gt2jfhvotfk.html

[R23] 字符串替换
来源：http://dali.fengsongda.top/Article/details/gt2zawzcalw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ppjwa.cn/Article/details/gt2xydeessb.html

[R24] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2npcjkmnc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.vqdsnc.cn/Article/details/gt2eykypbek.html

[R25] 去后缀 / 去前缀
来源：http://dali.9152youxi.cn/Article/details/gt2eioilypj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jiagoushi.top/Article/details/gt2kepfapie.html

[R26] 命令替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gaouxvab.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxinkj.top/Article/details/gt2khrbqgjc.html

[R27] 算术展开
来源：http://dali.wangshuangyany.cn/Article/details/gt2bsghrxsm.html

echo $((1 + 2 * 3))
来源：http://dali.yonumen.top/Article/details/gt2irfkoczk.html

[R28] 浮点运算
来源：http://dali.aibaodan.cn/Article/details/gt2ixvgbxkl.html

echo "scale=2; 10/3" | bc
来源：http://dali.yonumen.top/Article/details/gt2dutxsbmy.html

[R29] 定义函数
来源：http://dali.hfpthk.cn/Article/details/gt2fiicwynm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ybcxt.top/Article/details/gt2ibciuust.html

[R30] 函数返回状态码
来源：http://dali.yj20258888.top/Article/details/gt2lvqutsst.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cqqwz.cn/Article/details/gt2qldnourr.html

[R31] 局部变量
来源：http://dali.zhengqikj.top/Article/details/gt2emulstbn.html

f() { local x=1; echo "$x"; }
来源：http://dali.hammf.cn/Article/details/gt2zhypkrdq.html

[R32] 参数个数校验
来源：http://dali.yanxiufei.cn/Article/details/gt2qnnaojyk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gt2isegrtky.html

[R33] 捕获错误并提示行号
来源：http://dali.guowangkeji.top/Article/details/gt2btrnplkk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ybcxt.top/Article/details/gt2xvyrfdkn.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gt2eqimndih.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gt2rjknvmvf.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gt2bcgynzpo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigfzy.top/Article/details/gt2mbwfhype.html

[R36] 并发执行多个任务
来源：http://dali.yuxming.cn/Article/details/gt2jofahxzn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shzxlz.cn/Article/details/gt2twkuztzh.html

[R37] 把输出赋给变量
来源：http://dali.hnxiangtu.top/Article/details/gt2yhztwzfb.html

files=$(ls -1)
来源：http://dali.vqdsnc.cn/Article/details/gt2ddcrumha.html

[R38] 管道串联
来源：http://dali.jqgufenzy.top/Article/details/gt2mabgjqdk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgfzy.top/Article/details/gt2bticitwd.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rhafljzw.html

cmd > out.log 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gt2kmhmzsdt.html

[R40] 追加写日志
来源：http://dali.cucudq.cn/Article/details/gt2ozbinowp.html

echo "log" >> out.log
来源：http://dali.xuetiantiany.cn/Article/details/gt2aehrovef.html

[R41] 丢弃输出
来源：http://dali.jinqigufen.top/Article/details/gt2gxavxbar.html

cmd >/dev/null 2>&1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hvpmywot.html

[R42] 输入重定向
来源：http://dali.wangdashe.top/Article/details/gt2azwufxhv.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gt2fqeypamb.html

[R43] 按名字查找文件
来源：http://dali.redwolf501.top/Article/details/gt2gucqaiul.html

find . -name "*.log" -type f
来源：http://dali.sysykeji.top/Article/details/gt2olophznw.html

[R44] 按修改时间查找
来源：http://dali.sweek.top/Article/details/gt2kgqhsdxv.html

find . -mtime -7 -type f
来源：http://dali.redwolf501.top/Article/details/gt2obsupqkj.html

[R45] 批量删除
来源：http://dali.hongshengwenyu.top/Article/details/gt2soccvsgc.html

find . -name "*.tmp" -delete
来源：http://dali.birdmap.top/Article/details/gt2ldhvhsvt.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gt2djgfgakt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.quarkkingdee.top/Article/details/gt2rjvcvnrb.html

[R47] sed 单行替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdiotezy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gzhubu.top/Article/details/gt2ybwflysm.html

[R48] awk 取指定列
来源：http://dali.shzxlz.cn/Article/details/gt2efltvyki.html

awk '{print $1, $3}' a.txt
来源：http://dali.andypj.xyz/Article/details/gt2kzwwnufa.html

[R49] awk 带条件
来源：http://dali.0kj1m.cn/Article/details/gt2gmzeizwp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hysaishi.cn/Article/details/gt2tpetiwmr.html

[R50] awk 求和
来源：http://dali.svipenyu.cn/Article/details/gt2nkeqgmyt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2lyqaqtjo.html

[R51] 排序去重取前几
来源：http://dali.ybcxt.top/Article/details/gt2psvwewko.html


<!-- 参考信息 -->