代发 wailian999

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtuakxagyk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jlsjyb.cn/Article/details/gtsmgneedg.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gttlwdaspq.html

[Q01] 创建表
来源：http://dali.nwbrower.top/Article/details/gtqooevfum.html

CREATE TABLE users (
来源：http://dali.fengsongda.top/Article/details/gtdmknzixr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gthdpwwgmn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gteswsnmrp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.vqdsnc.cn/Article/details/gttecddrws.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hfpthk.cn/Article/details/gtjrajoqst.html

);
来源：http://dali.jlsjyb.cn/Article/details/gtzhmoxxau.html

[Q02] 创建带外键的表
来源：http://dali.nanxinkj.top/Article/details/gtmdvpgfvl.html

CREATE TABLE orders (
来源：http://dali.hywenlv.cn/Article/details/gttmjhgfgm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtyxkeeqey.html

user_id INT NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gtbewhcqoh.html

amount DECIMAL(10, 2),
来源：http://dali.xinyue.icu/Article/details/gtxxojlvwe.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.feifeiyinyue.top/Article/details/gthyintork.html

);
来源：http://dali.snrcjt.cn/Article/details/gtwfanxlht.html

[Q03] 增加列
来源：http://dali.xylfe.cn/Article/details/gtnihcmcte.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvodhonn.html

[Q04] 修改列类型
来源：http://dali.pengpengdd.cyou/Article/details/gtqxhszxsh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj202588.top/Article/details/gtmcwlohys.html

[Q05] 重命名列
来源：http://dali.xinyue.icu/Article/details/gtiqozxjss.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuanzhike.top/Article/details/gthsiibxkl.html

[Q06] 删除列
来源：http://dali.redwolf501.top/Article/details/gtjyvbgcbj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.birdmap.top/Article/details/gtorkaycwc.html

[Q07] 删除表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmekvasck.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrdsbpfh.html

[Q08] 创建普通索引
来源：http://dali.ivvv.top/Article/details/gtuchuwosu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgeiqyqx.html

[Q09] 创建唯一索引
来源：http://dali.dianchejie.cn/Article/details/gtrqscsnhj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gtdhqjfihr.html

[Q10] 插入单行
来源：http://dali.sxryk.cn/Article/details/gttrmkxymm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gtdgaewmev.html

[Q11] 一次插入多行
来源：http://dali.cucudq.cn/Article/details/gtnhwvxggx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.iojbl.cn/Article/details/gtfdeodppw.html

[Q12] 插入后取自增 ID
来源：http://dali.jyoumei.cn/Article/details/gtjqwrbdyo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yonumen.top/Article/details/gtfxauizmn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfctwpgne.html

[Q13] 忽略重复插入
来源：http://dali.yanxiufei.cn/Article/details/gtibsldvyg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenzaomai.com/Article/details/gtifybhqte.html

[Q14] 存在则更新（upsert）
来源：http://dali.ydzc1.top/Article/details/gtmbniyczy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ppjwa.cn/Article/details/gtrtoaerof.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ydzc1.top/Article/details/gtszsaujqp.html

[Q15] 查询全部
来源：http://dali.gogol.net.cn/Article/details/gtigyevhmz.html

SELECT * FROM users;
来源：http://dali.ydzc1.top/Article/details/gtcpqvoxgs.html

[Q16] 查询指定列
来源：http://dali.yj202588.top/Article/details/gtockmkvbw.html

SELECT id, name FROM users;
来源：http://dali.guannengcc.top/Article/details/gtebjutrfg.html

[Q17] 条件查询
来源：http://dali.yongpay.top/Article/details/gtxjffjzec.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xylfe.cn/Article/details/gttbtnhgio.html

[Q18] 模糊匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtrvphjgpo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ybcxt.top/Article/details/gtgzuzcmrs.html

[Q19] 范围查询
来源：http://dali.jyoumei.cn/Article/details/gtytnydsqr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258888.top/Article/details/gtaiqbtymq.html

[Q20] IN 列表
来源：http://dali.ppjwa.cn/Article/details/gtpamlqlnn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtpdbngtdw.html

[Q21] 空值判断
来源：http://dali.jqgfzy.top/Article/details/gtygkmdsqy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nwbrower.top/Article/details/gtfnyvafmo.html

[Q22] 排序
来源：http://dali.ybcxt.top/Article/details/gtksdfqqtb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.guannengcc.top/Article/details/gtxapkicvc.html

[Q23] 分页
来源：http://dali.ehwqpu.com/Article/details/gtywjqbeyy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhengqikj.top/Article/details/gtfmlyflxt.html

[Q24] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gtxvzyappg.html

SELECT DISTINCT city FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtblhidgnp.html

[Q25] 只取前 N 条
来源：http://dali.jianghu66.top/Article/details/gtwvzjnpuu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ydzc1.top/Article/details/gtcwzzhkcv.html

[Q26] 计数
来源：http://dali.shuidangran.top/Article/details/gtpuzbvkyt.html

SELECT COUNT(*) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtrblxjpcr.html

[Q27] 条件计数
来源：http://dali.ybcxt.top/Article/details/gthqajzglt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ydzc1.top/Article/details/gtoqbbpozf.html

[Q28] 求和与平均
来源：http://dali.pycfn.com/Article/details/gtkfufsxsv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtyfywwbsn.html

[Q29] 最大最小值
来源：http://dali.guannengcc.top/Article/details/gtjalkzilt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtyiflnhrd.html

[Q30] 分组统计
来源：http://dali.dashuyun.cn/Article/details/gtiarjzbil.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gtooywwzhz.html

[Q31] 分组后过滤
来源：http://dali.svipenyu.cn/Article/details/gtiicnwuok.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.iojbl.cn/Article/details/gtqolptpxq.html

[Q32] 分组拼接字符串
来源：http://dali.jianghu66.top/Article/details/gtojbktwhm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gtxnpfagho.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tanke756.top/Article/details/gtcmoqpfik.html

[Q33] 多列分组
来源：http://dali.smart0.xyz/Article/details/gtjjuzzhht.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cdnleiting.top/Article/details/gtwidcxrqa.html

[Q34] 每组取第一条
来源：http://dali.gaohongyu789.top/Article/details/gtmfzxknlm.html

SELECT * FROM (
来源：http://dali.nanxuanxn.top/Article/details/gtvxxzroro.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigfzy.top/Article/details/gtfqhjybun.html

) t WHERE rn = 1;
来源：http://dali.yangfankeji.com/Article/details/gtevtgkksq.html

[Q35] 内连接
来源：http://dali.aibaodan.cn/Article/details/gtdtfkaycv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gtgsiljkhn.html

[Q36] 左连接
来源：http://dali.fzhhl.top/Article/details/gtewlfmxve.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gteocwplkw.html

[Q37] 右连接
来源：http://dali.yanxiufei.cn/Article/details/gtokepadoo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zycfv.cn/Article/details/gtmkyglkti.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tanke756.top/Article/details/gtjyztmmxt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daxiang520.top/Article/details/gtwcdizwcv.html

[Q39] 自连接（查上下级）
来源：http://dali.zhengqikj.top/Article/details/gtxlqyacuf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhongyouzk.top/Article/details/gtlwuhrlrk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zycfv.cn/Article/details/gtrhwyumah.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yanxiufei.cn/Article/details/gtqzlnvvew.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shzxlz.cn/Article/details/gthpapezrb.html

[Q41] 多表连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyistxphx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zycfv.cn/Article/details/gtkogojbra.html

JOIN users u ON u.id = o.user_id
来源：http://dali.daxiang520.top/Article/details/gtmjfrxksx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtmxjrfxeu.html

[Q42] 连接条件附加过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtodzyaulv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj202588.top/Article/details/gtnnfuhjbs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenlongwang.top/Article/details/gtimgiihnt.html

[Q43] 标量子查询
来源：http://dali.zhengqikj.top/Article/details/gtpxcworcb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cqqwz.cn/Article/details/gtwglwihfc.html

[Q44] IN 子查询
来源：http://dali.pengpengdd.cyou/Article/details/gtevioyyml.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ppjwa.cn/Article/details/gtezmnjcry.html

[Q45] EXISTS 判断存在
来源：http://dali.jiagoushi.top/Article/details/gtjesbfipk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gtsponljco.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zycfv.cn/Article/details/gtdwnyjhuv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gtnlivrzgp.html

[Q47] 与平均值比较
来源：http://dali.yonumen.top/Article/details/gtzwhucivt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jianghu66.top/Article/details/gtvqbubnnt.html

[Q48] CTE 公用表表达式
来源：http://dali.snrcjt.cn/Article/details/gtjbjfxjoo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.guannengcc.top/Article/details/gtjrnfhjha.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zdqjudy.top/Article/details/gtpsqrmlsg.html

[Q49] 更新单行
来源：http://dali.meibo888.top/Article/details/gtxnxrmmxq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gtoiubfsbh.html

[Q50] 批量更新
来源：http://dali.mhx1999.top/Article/details/gtogdstdkp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gtdelxfbeu.html

[Q51] 用子查询更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaniizgcl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.meibo888.top/Article/details/gtuipyvhgo.html

[Q52] 删除指定行
来源：http://dali.tanke756.top/Article/details/gtyywcmddc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gtkoebvpyh.html

[Q53] 按条件删除
来源：http://dali.sufxvd.cn/Article/details/gtvscsasao.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.kuanghao11.cn/Article/details/gtdpkrouav.html

[Q54] 清空表
来源：http://dali.jlsjyb.cn/Article/details/gthtmaepyi.html

TRUNCATE TABLE logs;
来源：http://dali.9152youxi.cn/Article/details/gtvsbvczvu.html

[Q55] 排名（并列占位）
来源：http://dali.redwolf501.top/Article/details/gtxgtaeefx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yuxming.cn/Article/details/gtxiuyhljt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtpthdhook.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuanzx.com/Article/details/gtheulkdju.html

[Q57] 行号
来源：http://dali.sweek.top/Article/details/gthuaxjafn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtuhmtaqrz.html

[Q58] 累计求和
来源：http://dali.daria6918.cn/Article/details/gtennmpkeo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtgoqcpoqg.html

[Q59] 分组内累计
来源：http://dali.ybcxt.top/Article/details/gttydostsk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtsvbuaunm.html

[Q60] 取上一行 / 下一行
来源：http://dali.xylfe.cn/Article/details/gtjxmxlhsv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cqqwz.cn/Article/details/gtvujvpgoe.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtjrdbwesh.html

[Q61] 移动平均
来源：http://dali.ehwqpu.com/Article/details/gtrtqbsjts.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtbqosqwed.html

[Q62] 分组占比
来源：http://dali.tianlin.xyz/Article/details/gtfrapdgpi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtguiheigq.html

[Q63] 开启事务
来源：http://dali.wangdashe.top/Article/details/gtykesbqlx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.haohaochexian.top/Article/details/gtcqpxayna.html

[Q64] 提交事务
来源：http://dali.meibo888.top/Article/details/gtcexyodpx.html

COMMIT;
来源：http://dali.tianlin.xyz/Article/details/gtxdzvymgc.html

[Q65] 回滚事务
来源：http://dali.sweek.top/Article/details/gtpggqqdlj.html

ROLLBACK;
来源：http://dali.zycfv.cn/Article/details/gtdldldjyn.html

[Q66] 行锁查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxjiqmlj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258.top/Article/details/gtcgzdqazs.html

[Q67] 设置隔离级别
来源：http://dali.ydzc1.top/Article/details/gtnnbiwvhn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenjidiqi.icu/Article/details/gtpecmvewq.html

[Q68] 保存点
来源：http://dali.xylfe.cn/Article/details/gtzbsaiqnd.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkfqdsdw.html

ROLLBACK TO sp1;
来源：http://dali.cqqwz.cn/Article/details/gtcpztwugf.html

[Q69] 查看执行计划
来源：http://dali.shangyingyoupin.top/Article/details/gtatplxvnv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhongyouzk.top/Article/details/gtmlyyjkrk.html

[Q70] 更新统计信息
来源：http://dali.havefunace.top/Article/details/gtleisozwz.html

ANALYZE TABLE users;
来源：http://dali.ehwqpu.com/Article/details/gtetzlnivb.html

[Q71] 查看建表语句
来源：http://dali.yuxming.cn/Article/details/gtiqaczqdi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sufxvd.cn/Article/details/gtixbhqdjf.html

[Q72] 查看索引
来源：http://dali.gogol.net.cn/Article/details/gtmvheopvo.html

SHOW INDEX FROM users;
来源：http://dali.ybcxt.top/Article/details/gtivtbhnzg.html

[Q73] 查看表状态
来源：http://dali.jlsjyb.cn/Article/details/gtpyashtde.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszyhuogc.html

[Q74] 强制使用索引
来源：http://dali.xuanzx.com/Article/details/gteclerrbe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yongpay.top/Article/details/gtodwgxuno.html

[Q75] 日期格式化
来源：http://dali.yongpay.top/Article/details/gtowpqboce.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtvjsfvjzq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhixingplan.top/Article/details/gtdwgseqis.html

[Q76] 按天统计
来源：http://dali.jinqigfzy.top/Article/details/gtbpwkaybn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxinkj.top/Article/details/gtfsedvort.html

[Q77] 时间加减
来源：http://dali.sufxvd.cn/Article/details/gtuqbrxeri.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.aibaodan.cn/Article/details/gtyaqcopkr.html

[Q78] 当前时间
来源：http://dali.smart0.xyz/Article/details/gtlvtejuur.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hywenlv.cn/Article/details/gtlzavqteh.html

[Q79] 字符串拼接
来源：http://dali.daria6918.cn/Article/details/gtdgohzemf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aizwys.cn/Article/details/gthatesqjw.html

[Q80] 字符串截取
来源：http://dali.jinqigfzy.top/Article/details/gtnjewigea.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyqjkgqk.html

[Q81] 字符串替换
来源：http://dali.tian-w.cn/Article/details/gtanesvtik.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tianlin.xyz/Article/details/gticotpgjm.html

[Q82] 字符长度与字节长度
来源：http://dali.redwolf501.top/Article/details/gttveiycdj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtkuleoain.html

[Q83] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtgxjuotxt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtuyfbekno.html

[Q84] 去除首尾空格
来源：http://dali.yanxiufei.cn/Article/details/gtlvnudknr.html

SELECT TRIM(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtgdiiejat.html

[Q85] 数值取整
来源：http://dali.pycfn.com/Article/details/gthyvdaidp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jianghu66.top/Article/details/gtjohhmuoj.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjmxkuel.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbijepbha.html

[Q87] JSON 字段做条件
来源：http://dali.9152youxi.cn/Article/details/gtbfgxunbh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fzhhl.top/Article/details/gtvrournvv.html

[Q88] 行转列（条件聚合）
来源：http://dali.sufxvd.cn/Article/details/gtlbudfbdo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhoulong.xyz/Article/details/gtmatmpojk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtvpknwigz.html

[Q89] 判断表是否存在
来源：http://dali.nwbrower.top/Article/details/gtjrqmcauf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sysykeji.top/Article/details/gtoiqnbzlc.html

[Q90] 生成序号列
来源：http://dali.guannengcc.top/Article/details/gtwixekhln.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.iojbl.cn/Article/details/gtufixrfsd.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwsywlbm.html

R. Bash 专题
来源：http://dali.tanke756.top/Article/details/gtmpxjvrcp.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtdwborckb.html

[R01] shebang 与严格模式
来源：http://dali.vqdsnc.cn/Article/details/gtupvnfrwy.html

#!/usr/bin/env bash
来源：http://dali.havefunace.top/Article/details/gtgfruswdo.html

set -euo pipefail
来源：http://dali.guowangkeji.top/Article/details/gtkgirkcva.html

[R02] 变量赋值与使用
来源：http://dali.andypj.xyz/Article/details/gtksznfqht.html

name="Tom"; echo "$name"
来源：http://dali.sufxvd.cn/Article/details/gttvzirxot.html

[R03] 只读变量
来源：http://dali.gotoacloud.top/Article/details/gtkhbpgnwc.html

readonly PI=3.14
来源：http://dali.hammf.cn/Article/details/gtxetetovd.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gtiovscito.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jlsjyb.cn/Article/details/gtbmicoifc.html

[R05] 参数默认值
来源：http://dali.bjfxy.top/Article/details/gtkxhfyvyx.html

name="${1:-default}"
来源：http://dali.xuetiantiany.cn/Article/details/gtrbgxyvbt.html

[R06] 判断命令是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtqcpdgzmk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlrwkigsr.html

[R07] if 判断文件
来源：http://dali.hywenlv.cn/Article/details/gtyfwfblkc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.redwolf501.top/Article/details/gtqrkglntl.html

[R08] 数值比较
来源：http://dali.dashuyun.cn/Article/details/gtidmxzsuv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtqkejfhas.html

[R09] 字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtxyltmdlb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtivfemcva.html

[R10] 正则匹配
来源：http://dali.birdmap.top/Article/details/gtfluizlxr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhoulong.xyz/Article/details/gteuxqomid.html

[R11] case 多分支
来源：http://dali.yj202588.top/Article/details/gtiocazils.html

case "$1" in
来源：http://dali.hnqzz.top/Article/details/gtoviturvr.html

start) echo "启动" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtfxivrriw.html

stop)  echo "停止" ;;
来源：http://dali.jiagoushi.top/Article/details/gtsdxfrzcc.html

*)     echo "未知命令" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtaidquoyw.html

esac
来源：http://dali.chenzaomai.com/Article/details/gtlvxkfsqj.html

[R12] for 遍历文件
来源：http://dali.hongshengwenyu.top/Article/details/gtgdpakfck.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ehwqpu.com/Article/details/gtizqgbvaw.html

[R13] for 计数循环
来源：http://dali.jinqigufen.top/Article/details/gtlwcyrtkn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gttkqnvbuc.html

[R14] C 风格 for
来源：http://dali.wangshuangyany.cn/Article/details/gtectohyxo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmyfyyux.html

[R15] while 逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsgozbxo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sufxvd.cn/Article/details/gtihfusmkz.html

[R16] until 等待条件
来源：http://dali.zhixingplan.top/Article/details/gtmimqviog.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gtgzicgeeg.html

[R17] 数组定义与取值
来源：http://dali.zycfv.cn/Article/details/gtvjbboqji.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxoskluzu.html

[R18] 遍历数组
来源：http://dali.yj20258.top/Article/details/gtsejfjhyw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yangfankeji.com/Article/details/gtrntjhmlu.html

[R19] 数组长度
来源：http://dali.gzhubu.top/Article/details/gthhyidtbl.html

echo "${#arr[@]}"
来源：http://dali.birdmap.top/Article/details/gtlwjmfsap.html

[R20] 关联数组（字典）
来源：http://dali.chenzaomai.com/Article/details/gtvgmokrpi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pengpengdd.cyou/Article/details/gtvoggtiiy.html

[R21] 字符串长度
来源：http://dali.pycfn.com/Article/details/gtnzqvsxtq.html

echo "${#s}"
来源：http://dali.yj20258888.top/Article/details/gtfqdomcwi.html

[R22] 截取子串
来源：http://dali.daxiang520.top/Article/details/gtciutrnmx.html

echo "${s:0:5}"
来源：http://dali.cucudq.cn/Article/details/gtnrycqgfv.html

[R23] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtmdckubcj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.9152youxi.cn/Article/details/gtnhckhicx.html

[R24] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gtzgrymdtg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hysaishi.cn/Article/details/gtmvwkzgmz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zdqjudy.top/Article/details/gtucumzamp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtelpygijq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gtympaeqsf.html

now=$(date +%F); echo "$now"
来源：http://dali.andypj.xyz/Article/details/gtdfmudefa.html

[R27] 算术展开
来源：http://dali.chenjidiqi.icu/Article/details/gtrqnbtcei.html

echo $((1 + 2 * 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtqnshjhun.html

[R28] 浮点运算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzripkac.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqwcprql.html

[R29] 定义函数
来源：http://dali.dianchejie.cn/Article/details/gtefvhxccb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sufxvd.cn/Article/details/gthpcztjqz.html

[R30] 函数返回状态码
来源：http://dali.mhx1999.top/Article/details/gtzjyofidp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhiwuduotai.top/Article/details/gtxkrqbfkd.html

[R31] 局部变量
来源：http://dali.guannengcc.top/Article/details/gtzlpmxvjy.html

f() { local x=1; echo "$x"; }
来源：http://dali.yangfankeji.com/Article/details/gtfmqcpjzo.html

[R32] 参数个数校验
来源：http://dali.wangdashe.top/Article/details/gtbkqfjlup.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gtzelfvdmy.html

[R33] 捕获错误并提示行号
来源：http://dali.fzhhl.top/Article/details/gtyxpnapkd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cucudq.cn/Article/details/gtbriwyklp.html

[R34] 退出时清理
来源：http://dali.xziqi.cn/Article/details/gtedmozkdr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtfimhiqjw.html

[R35] 后台执行并等待
来源：http://dali.tianlin.xyz/Article/details/gtsttsuhpf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.quarkkingdee.top/Article/details/gtewpsmadb.html

[R36] 并发执行多个任务
来源：http://dali.chenzaomai.com/Article/details/gtbhhrlwci.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sxryk.cn/Article/details/gtajhnufto.html

[R37] 把输出赋给变量
来源：http://dali.andypj.xyz/Article/details/gtbzcjtnmr.html

files=$(ls -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtszqqlyym.html

[R38] 管道串联
来源：http://dali.sxryk.cn/Article/details/gtmfdfqyal.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gtlfxexxou.html

[R39] 重定向标准输出与错误
来源：http://dali.shuidangran.top/Article/details/gtnczlgysz.html

cmd > out.log 2>&1
来源：http://dali.birdmap.top/Article/details/gtiyoixbgw.html

[R40] 追加写日志
来源：http://dali.hnxiangtu.top/Article/details/gtvduztsdp.html

echo "log" >> out.log
来源：http://dali.zhengqikj.top/Article/details/gtponcvrnp.html

[R41] 丢弃输出
来源：http://dali.hysaishi.cn/Article/details/gtsfzavcxy.html

cmd >/dev/null 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gtulsfdzog.html

[R42] 输入重定向
来源：http://dali.shangyingyoupin.top/Article/details/gtizfwwhdq.html

wc -l < a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtgoaxpemc.html

[R43] 按名字查找文件
来源：http://dali.cdnleiting.top/Article/details/gtmymcpmvl.html


<!-- 参考信息 -->