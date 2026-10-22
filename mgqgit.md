代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenzaomai.com/Article/details/gt2jgddlwbe.html

);
来源：http://dali.cqqwz.cn/Article/details/gt2qlyonbeo.html

[Q02] 创建带外键的表
来源：http://dali.chenlongwang.top/Article/details/gt2ybnrxjtx.html

CREATE TABLE orders (
来源：http://dali.nanxinkj.top/Article/details/gt2pmwfshzm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gt2igdywsub.html

user_id INT NOT NULL,
来源：http://dali.aibaodan.cn/Article/details/gt2vkbgehfg.html

amount DECIMAL(10, 2),
来源：http://dali.chenjidiqi.icu/Article/details/gt2czvgpplp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhixingplan.top/Article/details/gt2jypxhfxk.html

);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2imkgdwxm.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gt2pwngkuol.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.havefunace.top/Article/details/gt2jyduxmmy.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2magmidst.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.haohaochexian.top/Article/details/gt2lxgqnvue.html

[Q05] 重命名列
来源：http://dali.nanxuanxn.top/Article/details/gt2qslyjqup.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.c1oappe.top/Article/details/gt2wljynmvr.html

[Q06] 删除列
来源：http://dali.ppjwa.cn/Article/details/gt2ihbermgq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2klypygvj.html

[Q07] 删除表
来源：http://dali.fengsongda.top/Article/details/gt2xdbdkebt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xziqi.cn/Article/details/gt2ntoytfgy.html

[Q08] 创建普通索引
来源：http://dali.yuanzhike.top/Article/details/gt2usldpzmk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.quarkkingdee.top/Article/details/gt2dilvlzgt.html

[Q09] 创建唯一索引
来源：http://dali.jyoumei.cn/Article/details/gt2vfntwthf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fycedufa.html

[Q10] 插入单行
来源：http://dali.jqgufenzy.top/Article/details/gt2inateqci.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.316326.xyz/Article/details/gt2lseqktrc.html

[Q11] 一次插入多行
来源：http://dali.haohaochexian.top/Article/details/gt2uejpzfqo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.svipenyu.cn/Article/details/gt2gmyurcvy.html

[Q12] 插入后取自增 ID
来源：http://dali.feifeiyinyue.top/Article/details/gt2uuntfmyd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxuanxn.top/Article/details/gt2kdhjkqzq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.daxiang520.top/Article/details/gt2runhaerb.html

[Q13] 忽略重复插入
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hkbtwqgk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.svipenyu.cn/Article/details/gt2lmjgqchd.html

[Q14] 存在则更新（upsert）
来源：http://dali.birdmap.top/Article/details/gt2kgdlwtwf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zycfv.cn/Article/details/gt2zdzyfxud.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dashuyun.cn/Article/details/gt2agqlrrdz.html

[Q15] 查询全部
来源：http://dali.yongpay.top/Article/details/gt2pchuvhal.html

SELECT * FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2ykrereoy.html

[Q16] 查询指定列
来源：http://dali.xylfe.cn/Article/details/gt2fawqwzbl.html

SELECT id, name FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2fuwuukvd.html

[Q17] 条件查询
来源：http://dali.yongpay.top/Article/details/gt2iqyolzub.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258.top/Article/details/gt2bpfbetjk.html

[Q18] 模糊匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2gstxauhw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fzhhl.top/Article/details/gt2lphpprrc.html

[Q19] 范围查询
来源：http://dali.yanxiufei.cn/Article/details/gt2haesbsox.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nwbrower.top/Article/details/gt2gyfcxstf.html

[Q20] IN 列表
来源：http://dali.yvedp.cn/Article/details/gt2afnkyvun.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuanzx.com/Article/details/gt2qkjqiukj.html

[Q21] 空值判断
来源：http://dali.zhengqikj.top/Article/details/gt2dpcrbrov.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shuidangran.top/Article/details/gt2zqyerkzt.html

[Q22] 排序
来源：http://dali.daria6918.cn/Article/details/gt2qajxjubf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhongyouzk.top/Article/details/gt2zwmhptmv.html

[Q23] 分页
来源：http://dali.fengsongda.top/Article/details/gt2jwueollm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ydzc1.top/Article/details/gt2koknnvdb.html

[Q24] 去重
来源：http://dali.iojbl.cn/Article/details/gt2potknbam.html

SELECT DISTINCT city FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2sogggxfq.html

[Q25] 只取前 N 条
来源：http://dali.birdmap.top/Article/details/gt2zidxllsw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jiagoushi.top/Article/details/gt2ggbmxzfb.html

[Q26] 计数
来源：http://dali.c1oappe.top/Article/details/gt2ahwhlena.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2mllbzjaz.html

[Q27] 条件计数
来源：http://dali.aibaodan.cn/Article/details/gt2roeobame.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2haocqfxp.html

[Q28] 求和与平均
来源：http://dali.zycfv.cn/Article/details/gt2wblfjubm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2ifipxwzd.html

[Q29] 最大最小值
来源：http://dali.wangshuangyany.cn/Article/details/gt2qnbplzeu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sweek.top/Article/details/gt2gasvqngc.html

[Q30] 分组统计
来源：http://dali.havefunace.top/Article/details/gt2qpccnhwu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gt2fofxksbl.html

[Q31] 分组后过滤
来源：http://dali.hfpthk.cn/Article/details/gt2ustdrwue.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.svipenyu.cn/Article/details/gt2joiyjjcu.html

[Q32] 分组拼接字符串
来源：http://dali.fzhhl.top/Article/details/gt2fzylddax.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gt2yfvzroey.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.mhx1999.top/Article/details/gt2ncmbawsk.html

[Q33] 多列分组
来源：http://dali.chenjidiqi.icu/Article/details/gt2lzjctwqg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gzhubu.top/Article/details/gt2ozlteepn.html

[Q34] 每组取第一条
来源：http://dali.xuanzx.com/Article/details/gt2ygrnvicv.html

SELECT * FROM (
来源：http://dali.aibaodan.cn/Article/details/gt2wbaqsqbd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gotoacloud.top/Article/details/gt2xrikiovs.html

) t WHERE rn = 1;
来源：http://dali.yj202588.top/Article/details/gt2qimjslmu.html

[Q35] 内连接
来源：http://dali.iojbl.cn/Article/details/gt2pxwrklaa.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cashguo.top/Article/details/gt2viisvpkb.html

[Q36] 左连接
来源：http://dali.sufxvd.cn/Article/details/gt2unmuphqu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gt2bxzxespc.html

[Q37] 右连接
来源：http://dali.zhiwuduotai.top/Article/details/gt2aybgjptv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuanzhike.top/Article/details/gt2nrojuusy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.vqdsnc.cn/Article/details/gt2nkprqbwj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258.top/Article/details/gt2jcxfiyeh.html

[Q39] 自连接（查上下级）
来源：http://dali.snrcjt.cn/Article/details/gt2fqqrypmi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgfzy.top/Article/details/gt2opeolmzf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2gsxutyho.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ppjwa.cn/Article/details/gt2cmshnivg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yonumen.top/Article/details/gt2jpfaldwx.html

[Q41] 多表连接
来源：http://dali.kuanghao11.cn/Article/details/gt2lhtbhtiu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gotoacloud.top/Article/details/gt2akzurseh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yueranfly.top/Article/details/gt2vnrroslt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xziqi.cn/Article/details/gt2pjcxbbzn.html

[Q42] 连接条件附加过滤
来源：http://dali.ppjwa.cn/Article/details/gt2chpenrng.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nwbrower.top/Article/details/gt2ghthbpco.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daria6918.cn/Article/details/gt2yqvzljkl.html

[Q43] 标量子查询
来源：http://dali.hywenlv.cn/Article/details/gt2xtrggjnt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.9152youxi.cn/Article/details/gt2bkhbtpxo.html

[Q44] IN 子查询
来源：http://dali.sufxvd.cn/Article/details/gt2sekdodkb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cdnleiting.top/Article/details/gt2xeuqyuun.html

[Q45] EXISTS 判断存在
来源：http://dali.zhongyouzk.top/Article/details/gt2kzvvihzl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rmbmdlkn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shzxlz.cn/Article/details/gt2dwdaoukn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gt2jmpdlfbb.html

[Q47] 与平均值比较
来源：http://dali.ydzc1.top/Article/details/gt2dyqqlsgx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangdashe.top/Article/details/gt2wsjuwhpb.html

[Q48] CTE 公用表表达式
来源：http://dali.jyoumei.cn/Article/details/gt2crydglnk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.quarkkingdee.top/Article/details/gt2nsvezowr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xinyue.icu/Article/details/gt2femrhslc.html

[Q49] 更新单行
来源：http://dali.9152youxi.cn/Article/details/gt2kmtabhzo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gt2hnywriav.html

[Q50] 批量更新
来源：http://dali.hammf.cn/Article/details/gt2xtfzjtix.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cqqwz.cn/Article/details/gt2ncybbrmg.html

[Q51] 用子查询更新
来源：http://dali.smart0.xyz/Article/details/gt2ofjmvige.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.316326.xyz/Article/details/gt2ifpxnfmn.html

[Q52] 删除指定行
来源：http://dali.wangshuangyany.cn/Article/details/gt2ubmwxtrg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gt2onzeypyj.html

[Q53] 按条件删除
来源：http://dali.cheryme.top/Article/details/gt2ygdamuur.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.snrcjt.cn/Article/details/gt2tamqqxtn.html

[Q54] 清空表
来源：http://dali.zhiwuduotai.top/Article/details/gt2lrwpdldq.html

TRUNCATE TABLE logs;
来源：http://dali.yueranfly.top/Article/details/gt2tblastas.html

[Q55] 排名（并列占位）
来源：http://dali.yj202588.top/Article/details/gt2nupxbean.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj202588.top/Article/details/gt2kshokqeu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jyoumei.cn/Article/details/gt2owqepgwr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cashguo.top/Article/details/gt2cbogelzk.html

[Q57] 行号
来源：http://dali.yj20258888.top/Article/details/gt2jbnavetd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.birdmap.top/Article/details/gt2dymkotcj.html

[Q58] 累计求和
来源：http://dali.feifeiyinyue.top/Article/details/gt2tajhbnlq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2ydtvfifn.html

[Q59] 分组内累计
来源：http://dali.yvedp.cn/Article/details/gt2vysmdiyj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2ojyywmnx.html

[Q60] 取上一行 / 下一行
来源：http://dali.havefunace.top/Article/details/gt2nnhbwbco.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dianchejie.cn/Article/details/gt2tnfepvso.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2opgsrqbc.html

[Q61] 移动平均
来源：http://dali.yuanzhike.top/Article/details/gt2qcqkupue.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2mqvpcpzd.html

[Q62] 分组占比
来源：http://dali.zhixingplan.top/Article/details/gt2tvbdkrcs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gt2djhzljzi.html

[Q63] 开启事务
来源：http://dali.jqgufenzy.top/Article/details/gt2xaklmnik.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgfzy.top/Article/details/gt2omfetgxj.html

[Q64] 提交事务
来源：http://dali.yuanzhike.top/Article/details/gt2pjhrmrjc.html

COMMIT;
来源：http://dali.hammf.cn/Article/details/gt2ycdxdgue.html

[Q65] 回滚事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fdysepjn.html

ROLLBACK;
来源：http://dali.tanke756.top/Article/details/gt2tmnmbaqt.html

[Q66] 行锁查询
来源：http://dali.xziqi.cn/Article/details/gt2pusaljeq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ueqswffp.html

[Q67] 设置隔离级别
来源：http://dali.xinyue.icu/Article/details/gt2nfgdehlh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnxiangtu.top/Article/details/gt2csezamoc.html

[Q68] 保存点
来源：http://dali.yuxming.cn/Article/details/gt2gnyxuetq.html

SAVEPOINT sp1;
来源：http://dali.jqgfzy.top/Article/details/gt2izjgtysz.html

ROLLBACK TO sp1;
来源：http://dali.havefunace.top/Article/details/gt2zyqyrwnl.html

[Q69] 查看执行计划
来源：http://dali.yueranfly.top/Article/details/gt2buzyggpk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuxming.cn/Article/details/gt2egydbzab.html

[Q70] 更新统计信息
来源：http://dali.zhengqikj.top/Article/details/gt2npxdjpir.html

ANALYZE TABLE users;
来源：http://dali.fzhhl.top/Article/details/gt2xymwuuau.html

[Q71] 查看建表语句
来源：http://dali.dianchejie.cn/Article/details/gt2irdnjwvw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cashguo.top/Article/details/gt2psbmeciu.html

[Q72] 查看索引
来源：http://dali.iojbl.cn/Article/details/gt2hzvbacjv.html

SHOW INDEX FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2bighlkcp.html

[Q73] 查看表状态
来源：http://dali.ydzc1.top/Article/details/gt2wajctons.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gogol.net.cn/Article/details/gt2wixpggqu.html

[Q74] 强制使用索引
来源：http://dali.yanxiufei.cn/Article/details/gt2bofazhqe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shuidangran.top/Article/details/gt2cuiztivv.html

[Q75] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gt2cmdeusjn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2howpkkou.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hammf.cn/Article/details/gt2cdedxcry.html

[Q76] 按天统计
来源：http://dali.0kj1m.cn/Article/details/gt2behcqhsp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hywenlv.cn/Article/details/gt2zzjiahtz.html

[Q77] 时间加减
来源：http://dali.xuetiantiany.cn/Article/details/gt2nvdweycl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xylfe.cn/Article/details/gt2otqxcfdc.html

[Q78] 当前时间
来源：http://dali.tanke756.top/Article/details/gt2oeyjqbdf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangdashe.top/Article/details/gt2tjwazcxn.html

[Q79] 字符串拼接
来源：http://dali.havefunace.top/Article/details/gt2chamtafs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenzaomai.com/Article/details/gt2pviupatu.html

[Q80] 字符串截取
来源：http://dali.sxryk.cn/Article/details/gt2tvhfbyht.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2wetiyucn.html

[Q81] 字符串替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2edeytzvv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2fmiabchj.html

[Q82] 字符长度与字节长度
来源：http://dali.hfpthk.cn/Article/details/gt2kmbtgyqk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2fmqmevfx.html

[Q83] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rbsybbzd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2zwwewoij.html

[Q84] 去除首尾空格
来源：http://dali.feifeiyinyue.top/Article/details/gt2ipjpljvi.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2cfabizgn.html

[Q85] 数值取整
来源：http://dali.zhoulong.xyz/Article/details/gt2ttvxerrq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tianlin.xyz/Article/details/gt2rvmwgmzw.html

[Q86] 读取 JSON 字段
来源：http://dali.aizwys.cn/Article/details/gt2ezdcelmh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aibaodan.cn/Article/details/gt2lwitjpql.html

[Q87] JSON 字段做条件
来源：http://dali.havefunace.top/Article/details/gt2yjkntzdh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xinyue.icu/Article/details/gt2rubamows.html

[Q88] 行转列（条件聚合）
来源：http://dali.svipenyu.cn/Article/details/gt2tfqoycck.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pycfn.com/Article/details/gt2gftmunxi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bpoimvga.html

[Q89] 判断表是否存在
来源：http://dali.cqqwz.cn/Article/details/gt2lhdksyex.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hysaishi.cn/Article/details/gt2fcglllyo.html

[Q90] 生成序号列
来源：http://dali.yuxming.cn/Article/details/gt2zfrdwcue.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuetiantiany.cn/Article/details/gt2alpsfzxp.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2xdpkqzyx.html

R. Bash 专题
来源：http://dali.wangdashe.top/Article/details/gt2kdjowyxt.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2mmkqhvot.html

[R01] shebang 与严格模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxpnzemd.html

#!/usr/bin/env bash
来源：http://dali.haohaochexian.top/Article/details/gt2ucjqogdf.html

set -euo pipefail
来源：http://dali.zycfv.cn/Article/details/gt2lrqitqej.html

[R02] 变量赋值与使用
来源：http://dali.xziqi.cn/Article/details/gt2pqnmcixt.html

name="Tom"; echo "$name"
来源：http://dali.yuanzhike.top/Article/details/gt2jbgxfbwy.html

[R03] 只读变量
来源：http://dali.chenlongwang.top/Article/details/gt2ofopznlt.html

readonly PI=3.14
来源：http://dali.nwbrower.top/Article/details/gt2qnuwoask.html

[R04] 位置参数
来源：http://dali.quarkkingdee.top/Article/details/gt2pnvgrikr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenzaomai.com/Article/details/gt2nipbgfeq.html

[R05] 参数默认值
来源：http://dali.pycfn.com/Article/details/gt2wzzckrfn.html

name="${1:-default}"
来源：http://dali.tian-w.cn/Article/details/gt2vijiglgv.html

[R06] 判断命令是否存在
来源：http://dali.jianghu66.top/Article/details/gt2gwhuaehq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gt2ylwzxuno.html

[R07] if 判断文件
来源：http://dali.yuanzhike.top/Article/details/gt2xepxvanf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jianghu66.top/Article/details/gt2xetgchqm.html

[R08] 数值比较
来源：http://dali.zhengqikj.top/Article/details/gt2bvwywtda.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xylfe.cn/Article/details/gt2rflmkolb.html

[R09] 字符串比较
来源：http://dali.yvedp.cn/Article/details/gt2gyibbrcn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sysykeji.top/Article/details/gt2hpakrbfu.html

[R10] 正则匹配
来源：http://dali.andypj.xyz/Article/details/gt2khhhscoi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.c1oappe.top/Article/details/gt2cpquqvzb.html

[R11] case 多分支
来源：http://dali.xziqi.cn/Article/details/gt2xhyajoqz.html

case "$1" in
来源：http://dali.dianchejie.cn/Article/details/gt2audnbhgc.html

start) echo "启动" ;;
来源：http://dali.pycfn.com/Article/details/gt2wpthbjxi.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ldgpoqja.html

*)     echo "未知命令" ;;
来源：http://dali.tianlin.xyz/Article/details/gt2fjkuzddm.html

esac
来源：http://dali.9152youxi.cn/Article/details/gt2wlpcyyjs.html

[R12] for 遍历文件
来源：http://dali.zhoulong.xyz/Article/details/gt2dyjtikoj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vqrzyqss.html

[R13] for 计数循环
来源：http://dali.xylfe.cn/Article/details/gt2mykocwhz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2hugqgcry.html

[R14] C 风格 for
来源：http://dali.daxiang520.top/Article/details/gt2yziimwhw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2zkjsgnul.html

[R15] while 逐行读文件
来源：http://dali.tian-w.cn/Article/details/gt2zwyfjaen.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.snrcjt.cn/Article/details/gt2cnipkenb.html

[R16] until 等待条件
来源：http://dali.jinqigfzy.top/Article/details/gt2kghssiui.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gt2cztmovgy.html

[R17] 数组定义与取值
来源：http://dali.daria6918.cn/Article/details/gt2bmmofylh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yongpay.top/Article/details/gt2qezxewrp.html

[R18] 遍历数组
来源：http://dali.yj20258.top/Article/details/gt2xeilzkol.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigufen.top/Article/details/gt2sxlghmkk.html

[R19] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gt2caennvle.html

echo "${#arr[@]}"
来源：http://dali.mhx1999.top/Article/details/gt2burwtfra.html

[R20] 关联数组（字典）
来源：http://dali.nwbrower.top/Article/details/gt2cuqtlwii.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258888.top/Article/details/gt2stwzfqjq.html

[R21] 字符串长度
来源：http://dali.birdmap.top/Article/details/gt2zsaarzul.html

echo "${#s}"
来源：http://dali.jqgfzy.top/Article/details/gt2ixkiylpw.html

[R22] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gt2wwlelcyr.html

echo "${s:0:5}"
来源：http://dali.guannengcc.top/Article/details/gt2huwiyxgq.html

[R23] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2exgutglk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fengsongda.top/Article/details/gt2vjbmqwei.html

[R24] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gt2hylbezoz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hywenlv.cn/Article/details/gt2rwflrtyi.html

[R25] 去后缀 / 去前缀
来源：http://dali.guannengcc.top/Article/details/gt2zxjqpizn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.haohaochexian.top/Article/details/gt2qhjreqcs.html

[R26] 命令替换
来源：http://dali.hysaishi.cn/Article/details/gt2xcuromsh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhengqikj.top/Article/details/gt2krrqhmkz.html

[R27] 算术展开
来源：http://dali.shuidangran.top/Article/details/gt2hsakmtje.html

echo $((1 + 2 * 3))
来源：http://dali.guowangkeji.top/Article/details/gt2cdferxsn.html

[R28] 浮点运算
来源：http://dali.smart0.xyz/Article/details/gt2zhabnctv.html

echo "scale=2; 10/3" | bc
来源：http://dali.mhx1999.top/Article/details/gt2rglyszcn.html

[R29] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gt2wbantvig.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.smart0.xyz/Article/details/gt2fzktkowz.html

[R30] 函数返回状态码
来源：http://dali.aibaodan.cn/Article/details/gt2yopytqau.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigfzy.top/Article/details/gt2npprufcz.html

[R31] 局部变量
来源：http://dali.hnqzz.top/Article/details/gt2vrlxkfsp.html

f() { local x=1; echo "$x"; }
来源：http://dali.xziqi.cn/Article/details/gt2gywajupc.html

[R32] 参数个数校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2orefflgs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gt2xiwtsgks.html

[R33] 捕获错误并提示行号
来源：http://dali.c1oappe.top/Article/details/gt2nohrotub.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinghuilouyu.cn/Article/details/gt2otnvcmem.html

[R34] 退出时清理
来源：http://dali.hnxiangtu.top/Article/details/gt2sfqbrldi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gt2oinhxvla.html

[R35] 后台执行并等待
来源：http://dali.hnqzz.top/Article/details/gt2thkvpwhn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hammf.cn/Article/details/gt2bkmertdj.html

[R36] 并发执行多个任务
来源：http://dali.hysaishi.cn/Article/details/gt2udeikfuk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gt2mucbkeei.html

[R37] 把输出赋给变量
来源：http://dali.vqdsnc.cn/Article/details/gt2qcjazzls.html

files=$(ls -1)
来源：http://dali.shuidangran.top/Article/details/gt2yexiurdn.html

[R38] 管道串联
来源：http://dali.xuetiantiany.cn/Article/details/gt2kkfxvlxv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.dashuyun.cn/Article/details/gt2ejkwbpdq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhiwuduotai.top/Article/details/gt2izwalrmb.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gt2waxchndd.html

[R40] 追加写日志
来源：http://dali.bjfxy.top/Article/details/gt2nypziykn.html

echo "log" >> out.log
来源：http://dali.xuetiantiany.cn/Article/details/gt2fdbnwdan.html

[R41] 丢弃输出
来源：http://dali.dashuyun.cn/Article/details/gt2zmlhuelf.html

cmd >/dev/null 2>&1
来源：http://dali.hywenlv.cn/Article/details/gt2qtatycpk.html

[R42] 输入重定向
来源：http://dali.guowangkeji.top/Article/details/gt2xtddtywr.html

wc -l < a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2gspecfmf.html

[R43] 按名字查找文件
来源：http://dali.tanke756.top/Article/details/gt2mxamyrxl.html

find . -name "*.log" -type f
来源：http://dali.pycfn.com/Article/details/gt2smsqkaqs.html

[R44] 按修改时间查找
来源：http://dali.haohaochexian.top/Article/details/gt2jfpiakgn.html

find . -mtime -7 -type f
来源：http://dali.jiagoushi.top/Article/details/gt2eldpuunk.html

[R45] 批量删除
来源：http://dali.ivvv.top/Article/details/gt2nsvqwnvk.html

find . -name "*.tmp" -delete
来源：http://dali.jinghuilouyu.cn/Article/details/gt2adkkeyau.html

[R46] 递归替换文件内容
来源：http://dali.sweek.top/Article/details/gt2wvbnguos.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvavvgtg.html

[R47] sed 单行替换
来源：http://dali.chenzaomai.com/Article/details/gt2cilxmqqd.html


<!-- 参考信息 -->