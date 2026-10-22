代发 wailian999

================================================================================
来源：http://dali.hammf.cn/Article/details/gtalcslmal.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yvedp.cn/Article/details/gtgctayebj.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtcgtdsgsd.html

[Q01] 创建表
来源：http://dali.iojbl.cn/Article/details/gtbxortogg.html

CREATE TABLE users (
来源：http://dali.yuxming.cn/Article/details/gtpzootxaz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gtugancoca.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gthgjupwkd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tianlin.xyz/Article/details/gtejebljrl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyyoziulw.html

);
来源：http://dali.sysykeji.top/Article/details/gtuqdwfgjx.html

[Q02] 创建带外键的表
来源：http://dali.jlsjyb.cn/Article/details/gtxgfivssz.html

CREATE TABLE orders (
来源：http://dali.9152youxi.cn/Article/details/gtozhksvkp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gteyyoyscy.html

user_id INT NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtntvpqznl.html

amount DECIMAL(10, 2),
来源：http://dali.0kj1m.cn/Article/details/gtibligcxt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shzxlz.cn/Article/details/gtftqflwxz.html

);
来源：http://dali.meibo888.top/Article/details/gtzvcbdzef.html

[Q03] 增加列
来源：http://dali.guannengcc.top/Article/details/gttytvqghb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sufxvd.cn/Article/details/gtwimiyeyv.html

[Q04] 修改列类型
来源：http://dali.hammf.cn/Article/details/gtoxcfcfxc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pycfn.com/Article/details/gtektdmhmo.html

[Q05] 重命名列
来源：http://dali.yj202588.top/Article/details/gtxhieguic.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhoulong.xyz/Article/details/gtrhcxkmyz.html

[Q06] 删除列
来源：http://dali.hnxiangtu.top/Article/details/gtgvtdtarv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.316326.xyz/Article/details/gtbojtuijr.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gtmxzxmost.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daria6918.cn/Article/details/gtolwukdds.html

[Q08] 创建普通索引
来源：http://dali.zhixingplan.top/Article/details/gtbmsjzlyj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tanke756.top/Article/details/gtqkjzlsvv.html

[Q09] 创建唯一索引
来源：http://dali.c1oappe.top/Article/details/gtyxymrclb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gtwbkwkvpn.html

[Q10] 插入单行
来源：http://dali.cucudq.cn/Article/details/gtnrztinyu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivxdfisf.html

[Q11] 一次插入多行
来源：http://dali.jinghuilouyu.cn/Article/details/gtohhksdld.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hywenlv.cn/Article/details/gtojfbhrwa.html

[Q12] 插入后取自增 ID
来源：http://dali.9152youxi.cn/Article/details/gtntasdofz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.fengsongda.top/Article/details/gtpqknizid.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tanke756.top/Article/details/gtruaswjbk.html

[Q13] 忽略重复插入
来源：http://dali.pycfn.com/Article/details/gtrhwdpobx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xinyue.icu/Article/details/gtojfmvjss.html

[Q14] 存在则更新（upsert）
来源：http://dali.jianghu66.top/Article/details/gtnexbpmct.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gogol.net.cn/Article/details/gtamknrtff.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqwhjfox.html

[Q15] 查询全部
来源：http://dali.birdmap.top/Article/details/gtsbsacfpf.html

SELECT * FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtqjejsaeb.html

[Q16] 查询指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtondsxriw.html

SELECT id, name FROM users;
来源：http://dali.ybcxt.top/Article/details/gtxszxzysq.html

[Q17] 条件查询
来源：http://dali.ivvv.top/Article/details/gtwemmkcxr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gtxtdreyzv.html

[Q18] 模糊匹配
来源：http://dali.cashguo.top/Article/details/gtzzbsqssm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tian-w.cn/Article/details/gtmfootxpk.html

[Q19] 范围查询
来源：http://dali.aizwys.cn/Article/details/gtuhnnasbh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gotoacloud.top/Article/details/gtyqdvxiir.html

[Q20] IN 列表
来源：http://dali.quarkkingdee.top/Article/details/gtfsdfnjki.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ybcxt.top/Article/details/gteoexksea.html

[Q21] 空值判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticaxebjm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnxiangtu.top/Article/details/gtxlwfsmmv.html

[Q22] 排序
来源：http://dali.daria6918.cn/Article/details/gtqxpfdirz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jlsjyb.cn/Article/details/gtbixrouia.html

[Q23] 分页
来源：http://dali.ppjwa.cn/Article/details/gttsupugcn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sweek.top/Article/details/gtmathdgpy.html

[Q24] 去重
来源：http://dali.smart0.xyz/Article/details/gtlwqsvghv.html

SELECT DISTINCT city FROM users;
来源：http://dali.316326.xyz/Article/details/gtsqtgsxvo.html

[Q25] 只取前 N 条
来源：http://dali.meibo888.top/Article/details/gtgchxwcsn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinghuilouyu.cn/Article/details/gttfnzczol.html

[Q26] 计数
来源：http://dali.hysaishi.cn/Article/details/gtpydwzucf.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtqwmbobss.html

[Q27] 条件计数
来源：http://dali.smart0.xyz/Article/details/gtykkaladn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcrsnacb.html

[Q28] 求和与平均
来源：http://dali.redwolf501.top/Article/details/gtgcrvxyok.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtctosoqwg.html

[Q29] 最大最小值
来源：http://dali.hnqzz.top/Article/details/gtfcxtvzwh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtnnilbl.html

[Q30] 分组统计
来源：http://dali.cucudq.cn/Article/details/gtthjatyls.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gtunfherdv.html

[Q31] 分组后过滤
来源：http://dali.cheryme.top/Article/details/gtmfqzkmvf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtbliiwhcq.html

[Q32] 分组拼接字符串
来源：http://dali.yj20258.top/Article/details/gtkuyuwbtg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtqzmcjrfn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.redwolf501.top/Article/details/gtwwydvtpn.html

[Q33] 多列分组
来源：http://dali.yj20258888.top/Article/details/gtjrypuybi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuetiantiany.cn/Article/details/gtvmdkzvlr.html

[Q34] 每组取第一条
来源：http://dali.wangdashe.top/Article/details/gtksimckhu.html

SELECT * FROM (
来源：http://dali.zhiwuduotai.top/Article/details/gtxuthvvox.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.wangshuangyany.cn/Article/details/gtkagxlhdf.html

) t WHERE rn = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtttxuxczu.html

[Q35] 内连接
来源：http://dali.iojbl.cn/Article/details/gtpkdemcho.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimbhdhff.html

[Q36] 左连接
来源：http://dali.zhiwuduotai.top/Article/details/gtwedrwxsk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gtneflqrjb.html

[Q37] 右连接
来源：http://dali.xziqi.cn/Article/details/gtlkwxwtiv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aibaodan.cn/Article/details/gtsqihvtzu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.dianchejie.cn/Article/details/gtttegased.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sxryk.cn/Article/details/gtasfmjvoq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnuyuzbhz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fengsongda.top/Article/details/gteczpnhtt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gtgddxrvep.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gotoacloud.top/Article/details/gttahnhqnv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sufxvd.cn/Article/details/gtznkffwvf.html

[Q41] 多表连接
来源：http://dali.haohaochexian.top/Article/details/gtunyljocj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.0kj1m.cn/Article/details/gtwkypjpmu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhongyouzk.top/Article/details/gtnadmnvtd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fzhhl.top/Article/details/gtecqfibfc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhengqikj.top/Article/details/gtlnlouysf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sxryk.cn/Article/details/gtdvmiuxzy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gzhubu.top/Article/details/gtioicicor.html

[Q43] 标量子查询
来源：http://dali.shangyingyoupin.top/Article/details/gtfmwzteeh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cqqwz.cn/Article/details/gtfhgqffby.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gttgoqevkc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258888.top/Article/details/gtmurabkzv.html

[Q45] EXISTS 判断存在
来源：http://dali.yuanzhike.top/Article/details/gtgieqaewx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pycfn.com/Article/details/gtcrvkbsha.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwhguvdr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gtwtehmekl.html

[Q47] 与平均值比较
来源：http://dali.zhoulong.xyz/Article/details/gtfjrjbhdn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ybcxt.top/Article/details/gtrdqurqhl.html

[Q48] CTE 公用表表达式
来源：http://dali.jyoumei.cn/Article/details/gtvrezwqsh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigufen.top/Article/details/gtaaovscqy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nwbrower.top/Article/details/gttragupjo.html

[Q49] 更新单行
来源：http://dali.pengpengdd.cyou/Article/details/gtzlfsuswi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuxming.cn/Article/details/gtdghycwnk.html

[Q50] 批量更新
来源：http://dali.hnqzz.top/Article/details/gtdevmckba.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenzaomai.com/Article/details/gtngpdhald.html

[Q51] 用子查询更新
来源：http://dali.ydzc1.top/Article/details/gtyefchiem.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzftsyqb.html

[Q52] 删除指定行
来源：http://dali.smart0.xyz/Article/details/gtsssvehyx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtdwqsczvm.html

[Q53] 按条件删除
来源：http://dali.cashguo.top/Article/details/gtutatddaw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gtuojyyrgl.html

[Q54] 清空表
来源：http://dali.snrcjt.cn/Article/details/gtrozsiteq.html

TRUNCATE TABLE logs;
来源：http://dali.shzxlz.cn/Article/details/gtvuibnhtg.html

[Q55] 排名（并列占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkounsmxs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gtvoacxold.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbxjcncy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gtsmojthzm.html

[Q57] 行号
来源：http://dali.cucudq.cn/Article/details/gttyacuiko.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.mhx1999.top/Article/details/gtrguzlkmu.html

[Q58] 累计求和
来源：http://dali.kuanghao11.cn/Article/details/gtlbzxjnpd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cashguo.top/Article/details/gtouzqwebi.html

[Q59] 分组内累计
来源：http://dali.yj20258888.top/Article/details/gtcogjwpqs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtorlobpnc.html

[Q60] 取上一行 / 下一行
来源：http://dali.redwolf501.top/Article/details/gtsxijsfol.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.andypj.xyz/Article/details/gtorxvkvwt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtlvsfuvll.html

[Q61] 移动平均
来源：http://dali.ehwqpu.com/Article/details/gtkhcsbcot.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtfktybgfk.html

[Q62] 分组占比
来源：http://dali.iojbl.cn/Article/details/gtfhafmtmr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtlmrtvcia.html

[Q63] 开启事务
来源：http://dali.fengsongda.top/Article/details/gtoyxfvupe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhongyouzk.top/Article/details/gtnpaygajr.html

[Q64] 提交事务
来源：http://dali.yangfankeji.com/Article/details/gtrgzqhotv.html

COMMIT;
来源：http://dali.dianchejie.cn/Article/details/gtgzklykjj.html

[Q65] 回滚事务
来源：http://dali.haohaochexian.top/Article/details/gtnowlxqwk.html

ROLLBACK;
来源：http://dali.jqgfzy.top/Article/details/gtzwlpwmub.html

[Q66] 行锁查询
来源：http://dali.hywenlv.cn/Article/details/gtnyopbfnp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.c1oappe.top/Article/details/gtxiztigbs.html

[Q67] 设置隔离级别
来源：http://dali.tianlin.xyz/Article/details/gtjlygugzf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenlongwang.top/Article/details/gtuhimackz.html

[Q68] 保存点
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyttfqfha.html

SAVEPOINT sp1;
来源：http://dali.iojbl.cn/Article/details/gtjpvnbrwr.html

ROLLBACK TO sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gtevczwvhj.html

[Q69] 查看执行计划
来源：http://dali.cashguo.top/Article/details/gtjxudsasx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenlongwang.top/Article/details/gtkopqmtdj.html

[Q70] 更新统计信息
来源：http://dali.jiagoushi.top/Article/details/gtfumattkj.html

ANALYZE TABLE users;
来源：http://dali.haohaochexian.top/Article/details/gtvtrhjmjw.html

[Q71] 查看建表语句
来源：http://dali.shzxlz.cn/Article/details/gtymjqrptd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhoulong.xyz/Article/details/gtpglpmjkf.html

[Q72] 查看索引
来源：http://dali.gogol.net.cn/Article/details/gtnskdstyy.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtpmwkwpgx.html

[Q73] 查看表状态
来源：http://dali.daxiang520.top/Article/details/gtshjpkxue.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gzhubu.top/Article/details/gthmkubrya.html

[Q74] 强制使用索引
来源：http://dali.zhengqikj.top/Article/details/gtgjfnwnof.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxuanxn.top/Article/details/gthdbmnpnt.html

[Q75] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gtwbujighv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pycfn.com/Article/details/gtpgvmqhyf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.quarkkingdee.top/Article/details/gtijueejki.html

[Q76] 按天统计
来源：http://dali.smart0.xyz/Article/details/gtfzncafdv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daxiang520.top/Article/details/gtoffufbbj.html

[Q77] 时间加减
来源：http://dali.sufxvd.cn/Article/details/gtfanyrokl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzbbgbvn.html

[Q78] 当前时间
来源：http://dali.fzhhl.top/Article/details/gtgiyoeanh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jlsjyb.cn/Article/details/gtzuiahkkf.html

[Q79] 字符串拼接
来源：http://dali.cdnleiting.top/Article/details/gtmhazssst.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ydzc1.top/Article/details/gtlnjscplr.html

[Q80] 字符串截取
来源：http://dali.yj20258.top/Article/details/gtvfwrawhl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hammf.cn/Article/details/gtspfjziek.html

[Q81] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gtodvdxqrl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtpqismlxl.html

[Q82] 字符长度与字节长度
来源：http://dali.9152youxi.cn/Article/details/gtnmlyymvg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtyedzwsky.html

[Q83] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtkvoznxum.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtdjrwcsbg.html

[Q84] 去除首尾空格
来源：http://dali.shzxlz.cn/Article/details/gtpbwlnjmp.html

SELECT TRIM(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gtoehwhkor.html

[Q85] 数值取整
来源：http://dali.quarkkingdee.top/Article/details/gthecnrexi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yueranfly.top/Article/details/gtysracftf.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258.top/Article/details/gtfxhlnzot.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fengsongda.top/Article/details/gtndvvgsec.html

[Q87] JSON 字段做条件
来源：http://dali.jyoumei.cn/Article/details/gtqiplagis.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cucudq.cn/Article/details/gtawjlkyik.html

[Q88] 行转列（条件聚合）
来源：http://dali.sxryk.cn/Article/details/gtnzcrzvyc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cdnleiting.top/Article/details/gtamiimzqi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ydzc1.top/Article/details/gtkmdtwsrn.html

[Q89] 判断表是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtirtpmqft.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.andypj.xyz/Article/details/gtmtmdmjwf.html

[Q90] 生成序号列
来源：http://dali.chenzaomai.com/Article/details/gtqrfnkeje.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.feifeiyinyue.top/Article/details/gtgzrjgoqi.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtapjpnwtu.html

R. Bash 专题
来源：http://dali.yj202588.top/Article/details/gtyxwgwtyt.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtffjvbakk.html

[R01] shebang 与严格模式
来源：http://dali.jqgfzy.top/Article/details/gthjwcbpss.html

#!/usr/bin/env bash
来源：http://dali.mhx1999.top/Article/details/gtzojztobd.html

set -euo pipefail
来源：http://dali.kuanghao11.cn/Article/details/gtihujgflh.html

[R02] 变量赋值与使用
来源：http://dali.zhongyouzk.top/Article/details/gtvxnntavn.html

name="Tom"; echo "$name"
来源：http://dali.dashuyun.cn/Article/details/gttgawejlh.html

[R03] 只读变量
来源：http://dali.zhongyouzk.top/Article/details/gthmljdcrf.html

readonly PI=3.14
来源：http://dali.daxiang520.top/Article/details/gtqooxjakc.html

[R04] 位置参数
来源：http://dali.jqgufenzy.top/Article/details/gtidoviknq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.quarkkingdee.top/Article/details/gtqghenqtr.html

[R05] 参数默认值
来源：http://dali.tianlin.xyz/Article/details/gtldszvwkk.html

name="${1:-default}"
来源：http://dali.wangdashe.top/Article/details/gtsimiyypr.html

[R06] 判断命令是否存在
来源：http://dali.xylfe.cn/Article/details/gtuqjgnzyl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gtegrgyfjx.html

[R07] if 判断文件
来源：http://dali.fzhhl.top/Article/details/gtpajqdxmk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtdbjjqlkm.html

[R08] 数值比较
来源：http://dali.yonumen.top/Article/details/gthyaucjlk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dianchejie.cn/Article/details/gttdrbixyn.html

[R09] 字符串比较
来源：http://dali.yj20258.top/Article/details/gtybpkopea.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xinyue.icu/Article/details/gtkcjkdgwk.html

[R10] 正则匹配
来源：http://dali.yj202588.top/Article/details/gtkpnbgxne.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fengsongda.top/Article/details/gtqzwygtfc.html

[R11] case 多分支
来源：http://dali.tianlin.xyz/Article/details/gtdioktseo.html

case "$1" in
来源：http://dali.shzxlz.cn/Article/details/gteckrvdgk.html

start) echo "启动" ;;
来源：http://dali.dianchejie.cn/Article/details/gtcbavysor.html

stop)  echo "停止" ;;
来源：http://dali.sufxvd.cn/Article/details/gtfsjzhcfx.html

*)     echo "未知命令" ;;
来源：http://dali.iojbl.cn/Article/details/gtdnilapkh.html

esac
来源：http://dali.nanxinkj.top/Article/details/gtbirrbmbf.html

[R12] for 遍历文件
来源：http://dali.nanxinkj.top/Article/details/gtxmxarpsi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hammf.cn/Article/details/gtxpagwflx.html

[R13] for 计数循环
来源：http://dali.hammf.cn/Article/details/gtweqdfgwp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimjljgmx.html

[R14] C 风格 for
来源：http://dali.jinqigfzy.top/Article/details/gtyresbfwq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gtttrmulom.html

[R15] while 逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtbwvnpcic.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fengsongda.top/Article/details/gtiuqckwpl.html

[R16] until 等待条件
来源：http://dali.9152youxi.cn/Article/details/gtjfeefbyg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gthlswniiz.html

[R17] 数组定义与取值
来源：http://dali.jinghuilouyu.cn/Article/details/gtneapjbgf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xylfe.cn/Article/details/gtiesnxbjd.html

[R18] 遍历数组
来源：http://dali.tianlin.xyz/Article/details/gtruwdiaaq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jqgufenzy.top/Article/details/gtjfetssfa.html

[R19] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtacdsyhfl.html

echo "${#arr[@]}"
来源：http://dali.andypj.xyz/Article/details/gtmzlrfbsu.html

[R20] 关联数组（字典）
来源：http://dali.shuidangran.top/Article/details/gtkbddkjqj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.birdmap.top/Article/details/gtieiwmypa.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtqgyazlpj.html

echo "${#s}"
来源：http://dali.jyoumei.cn/Article/details/gttpoisrvl.html

[R22] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gtaslakgdi.html

echo "${s:0:5}"
来源：http://dali.jinqigfzy.top/Article/details/gtngmithui.html

[R23] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gtiujhrapu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jyoumei.cn/Article/details/gtgwyxqmfz.html

[R24] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gtjthyljdh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hammf.cn/Article/details/gtqwetbwju.html

[R25] 去后缀 / 去前缀
来源：http://dali.gogol.net.cn/Article/details/gtoledfqrz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sweek.top/Article/details/gtbuogqwlu.html

[R26] 命令替换
来源：http://dali.guannengcc.top/Article/details/gtmusgkbaz.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxinkj.top/Article/details/gtftjkqsaf.html

[R27] 算术展开
来源：http://dali.zdqjudy.top/Article/details/gthivtsoux.html

echo $((1 + 2 * 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmayvbcgq.html

[R28] 浮点运算
来源：http://dali.gotoacloud.top/Article/details/gtgzfklhfc.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnqzz.top/Article/details/gtzkwaofxw.html

[R29] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gtjfcxebry.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fengsongda.top/Article/details/gtdbclenun.html

[R30] 函数返回状态码
来源：http://dali.zhixingplan.top/Article/details/gtxzbzupfv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nwbrower.top/Article/details/gtljluffmg.html

[R31] 局部变量
来源：http://dali.jqgfzy.top/Article/details/gtmkcvjkuc.html

f() { local x=1; echo "$x"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtioqlkcwu.html

[R32] 参数个数校验
来源：http://dali.hfpthk.cn/Article/details/gtngfqitsh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gtkfqhogqo.html

[R33] 捕获错误并提示行号
来源：http://dali.yj202588.top/Article/details/gtoopbaryx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sysykeji.top/Article/details/gtioytnskg.html

[R34] 退出时清理
来源：http://dali.zhoulong.xyz/Article/details/gtramyxint.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gtzhxmwjfu.html

[R35] 后台执行并等待
来源：http://dali.iojbl.cn/Article/details/gtpnxbafsu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangshuangyany.cn/Article/details/gtoafqjcnw.html

[R36] 并发执行多个任务
来源：http://dali.wangdashe.top/Article/details/gtkszsiimc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gzhubu.top/Article/details/gtsyndrpoo.html

[R37] 把输出赋给变量
来源：http://dali.aibaodan.cn/Article/details/gtcjceltxt.html

files=$(ls -1)
来源：http://dali.nanxinkj.top/Article/details/gtpitqxver.html

[R38] 管道串联
来源：http://dali.smart0.xyz/Article/details/gtvoulpgmy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.316326.xyz/Article/details/gtnqyhmcsx.html

[R39] 重定向标准输出与错误
来源：http://dali.sxryk.cn/Article/details/gtmulnbmcl.html

cmd > out.log 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gtvocnujrb.html

[R40] 追加写日志
来源：http://dali.zdqjudy.top/Article/details/gtvvwfmgmy.html

echo "log" >> out.log
来源：http://dali.svipenyu.cn/Article/details/gtzkqdwrhl.html

[R41] 丢弃输出
来源：http://dali.dashuyun.cn/Article/details/gtqtggtnhv.html

cmd >/dev/null 2>&1
来源：http://dali.jyoumei.cn/Article/details/gtqnkirmdr.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gtaipgrihk.html

wc -l < a.txt
来源：http://dali.daxiang520.top/Article/details/gtkjarszku.html

[R43] 按名字查找文件
来源：http://dali.shuidangran.top/Article/details/gtzuqcqnbp.html


<!-- 参考信息 -->