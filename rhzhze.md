代发 wailian999

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtuygsdtgq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknzcitxp.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtcqgujcqb.html

[Q01] 创建表
来源：http://dali.hongshengwenyu.top/Article/details/gtdybbxhvs.html

CREATE TABLE users (
来源：http://dali.aibaodan.cn/Article/details/gtkvxhmvwr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gtguplllcq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cheryme.top/Article/details/gtkjugfnnj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.316326.xyz/Article/details/gtnspmhjsm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sufxvd.cn/Article/details/gtkpklqdgu.html

);
来源：http://dali.yonumen.top/Article/details/gtdguvawhi.html

[Q02] 创建带外键的表
来源：http://dali.hysaishi.cn/Article/details/gtxjnxrzar.html

CREATE TABLE orders (
来源：http://dali.yvedp.cn/Article/details/gtnuokmqwo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gtxnbyvuvd.html

user_id INT NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gtsdzbsqdb.html

amount DECIMAL(10, 2),
来源：http://dali.ybcxt.top/Article/details/gtzpmzfcdi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.svipenyu.cn/Article/details/gtxmupsxmc.html

);
来源：http://dali.shuidangran.top/Article/details/gtrkrwsxyo.html

[Q03] 增加列
来源：http://dali.daria6918.cn/Article/details/gtjenpmahx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.haohaochexian.top/Article/details/gtygfmgwvp.html

[Q04] 修改列类型
来源：http://dali.yj20258.top/Article/details/gtqafhrelg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zdqjudy.top/Article/details/gtkzjwturq.html

[Q05] 重命名列
来源：http://dali.haohaochexian.top/Article/details/gtbgdrnypm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuanzhike.top/Article/details/gtyuveblrb.html

[Q06] 删除列
来源：http://dali.daxiang520.top/Article/details/gtnovrmlqa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenjidiqi.icu/Article/details/gtdvtclobj.html

[Q07] 删除表
来源：http://dali.cashguo.top/Article/details/gtftvbulql.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbwqfymof.html

[Q08] 创建普通索引
来源：http://dali.chenlongwang.top/Article/details/gtjssqbhge.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gtgmfjgzpe.html

[Q09] 创建唯一索引
来源：http://dali.zycfv.cn/Article/details/gtprfiyegw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dianchejie.cn/Article/details/gtuhtjlyiq.html

[Q10] 插入单行
来源：http://dali.gotoacloud.top/Article/details/gtdnyqclte.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtjrdafxuj.html

[Q11] 一次插入多行
来源：http://dali.sysykeji.top/Article/details/gtpfyxaipg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gtnoxhmkcc.html

[Q12] 插入后取自增 ID
来源：http://dali.wangshuangyany.cn/Article/details/gtfhyxizlm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.dashuyun.cn/Article/details/gtanmbzeua.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.haohaochexian.top/Article/details/gtldbhspgf.html

[Q13] 忽略重复插入
来源：http://dali.sufxvd.cn/Article/details/gtjrpivjbw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtfuwdlrng.html

[Q14] 存在则更新（upsert）
来源：http://dali.xylfe.cn/Article/details/gtjdziiuiw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtteenosir.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnmselcu.html

[Q15] 查询全部
来源：http://dali.xuetiantiany.cn/Article/details/gtpkpcnjwb.html

SELECT * FROM users;
来源：http://dali.tian-w.cn/Article/details/gtpnkwgdlu.html

[Q16] 查询指定列
来源：http://dali.cashguo.top/Article/details/gtsgsnxpty.html

SELECT id, name FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtokbrnusl.html

[Q17] 条件查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhblahai.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tanke756.top/Article/details/gtfdytzopl.html

[Q18] 模糊匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrbxubzp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgfzy.top/Article/details/gtqpzbmzko.html

[Q19] 范围查询
来源：http://dali.jqgfzy.top/Article/details/gtnwitspsy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hongshengwenyu.top/Article/details/gtqweakkbc.html

[Q20] IN 列表
来源：http://dali.yuanzhike.top/Article/details/gtmwxwzszv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.smart0.xyz/Article/details/gtqyvizjur.html

[Q21] 空值判断
来源：http://dali.gotoacloud.top/Article/details/gtajantufs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinqigfzy.top/Article/details/gtbxcavruc.html

[Q22] 排序
来源：http://dali.dianchejie.cn/Article/details/gtwnvzzvfm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.quarkkingdee.top/Article/details/gtcnjmryzl.html

[Q23] 分页
来源：http://dali.shzxlz.cn/Article/details/gteosifjaf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hysaishi.cn/Article/details/gtyannkert.html

[Q24] 去重
来源：http://dali.jyoumei.cn/Article/details/gtommwhbcj.html

SELECT DISTINCT city FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtnzxncfps.html

[Q25] 只取前 N 条
来源：http://dali.fengsongda.top/Article/details/gttoeoaabx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sweek.top/Article/details/gtgkvecnnn.html

[Q26] 计数
来源：http://dali.feifeiyinyue.top/Article/details/gtdkogvsot.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtqdxacboh.html

[Q27] 条件计数
来源：http://dali.zhoulong.xyz/Article/details/gtgzaydcud.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtcngrktxq.html

[Q28] 求和与平均
来源：http://dali.yuxming.cn/Article/details/gtehxvxatq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtraockldq.html

[Q29] 最大最小值
来源：http://dali.jyoumei.cn/Article/details/gtqauynazc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtncwjztle.html

[Q30] 分组统计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaocnymzt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtuzpjujbt.html

[Q31] 分组后过滤
来源：http://dali.mhx1999.top/Article/details/gtfionxtdg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yvedp.cn/Article/details/gtiaqcygbm.html

[Q32] 分组拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtfguqcotn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtcqmygtpl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jianghu66.top/Article/details/gtoauxpici.html

[Q33] 多列分组
来源：http://dali.ydzc1.top/Article/details/gtmxhwqioj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gtikxqwhqg.html

[Q34] 每组取第一条
来源：http://dali.tianlin.xyz/Article/details/gtvftorkfw.html

SELECT * FROM (
来源：http://dali.nanxuanxn.top/Article/details/gtkpiqhpml.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuanzx.com/Article/details/gtihhjyymp.html

) t WHERE rn = 1;
来源：http://dali.hywenlv.cn/Article/details/gtjpxbdcmh.html

[Q35] 内连接
来源：http://dali.fengsongda.top/Article/details/gtvpswqxuo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gtruzxkgve.html

[Q36] 左连接
来源：http://dali.nwbrower.top/Article/details/gtyteuhjwh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtcgwhgnvq.html

[Q37] 右连接
来源：http://dali.ivvv.top/Article/details/gtqrhrzqpn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gthodmuzzp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigfzy.top/Article/details/gtljbfftns.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj202588.top/Article/details/gtdgekaplf.html

[Q39] 自连接（查上下级）
来源：http://dali.wangdashe.top/Article/details/gttuuwastd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nwbrower.top/Article/details/gtyjcwfubv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenlongwang.top/Article/details/gtqmepquyl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tianlin.xyz/Article/details/gtoysqllui.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.smart0.xyz/Article/details/gtvsfrbgfl.html

[Q41] 多表连接
来源：http://dali.vqdsnc.cn/Article/details/gtmugydhlz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgufenzy.top/Article/details/gtxmcvhxoj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.mhx1999.top/Article/details/gtenbmhjte.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gtpyjeawhe.html

[Q42] 连接条件附加过滤
来源：http://dali.redwolf501.top/Article/details/gtdafbtcxg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.mhx1999.top/Article/details/gtaehdgqeu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cashguo.top/Article/details/gtyniwcogx.html

[Q43] 标量子查询
来源：http://dali.yueranfly.top/Article/details/gtdaybdeyl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yongpay.top/Article/details/gtcgyfytpd.html

[Q44] IN 子查询
来源：http://dali.aizwys.cn/Article/details/gtzjeczaqh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnqzz.top/Article/details/gtphtrszfj.html

[Q45] EXISTS 判断存在
来源：http://dali.haohaochexian.top/Article/details/gtfqycpwlx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gtpzjrpqkw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guowangkeji.top/Article/details/gtscinuuwm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbowkuyuo.html

[Q47] 与平均值比较
来源：http://dali.xinyue.icu/Article/details/gtsqhtsgti.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtottcbq.html

[Q48] CTE 公用表表达式
来源：http://dali.ydzc1.top/Article/details/gtgwrnrpls.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gtazgluvre.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nwbrower.top/Article/details/gtfvfxvnvj.html

[Q49] 更新单行
来源：http://dali.nwbrower.top/Article/details/gtyelenaeo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtdkaflmxi.html

[Q50] 批量更新
来源：http://dali.yvedp.cn/Article/details/gturnbtsne.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.birdmap.top/Article/details/gtvoremdvw.html

[Q51] 用子查询更新
来源：http://dali.ivvv.top/Article/details/gtvqjrnaah.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dianchejie.cn/Article/details/gtdxumnskt.html

[Q52] 删除指定行
来源：http://dali.yongpay.top/Article/details/gtbwnrygyr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtuoclomni.html

[Q53] 按条件删除
来源：http://dali.fengsongda.top/Article/details/gtvnstiynj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.meibo888.top/Article/details/gtsfudhhrn.html

[Q54] 清空表
来源：http://dali.shzxlz.cn/Article/details/gtaunvoezw.html

TRUNCATE TABLE logs;
来源：http://dali.wangshuangyany.cn/Article/details/gtbofahtbk.html

[Q55] 排名（并列占位）
来源：http://dali.snrcjt.cn/Article/details/gtsmxbtzjz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gtsgkcsbuc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.feifeiyinyue.top/Article/details/gtgsjxntyb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnqzz.top/Article/details/gtncwfbwee.html

[Q57] 行号
来源：http://dali.jiagoushi.top/Article/details/gtafetdvdz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtkfilvkkg.html

[Q58] 累计求和
来源：http://dali.hysaishi.cn/Article/details/gtcjiwspss.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtlrdwrzel.html

[Q59] 分组内累计
来源：http://dali.c1oappe.top/Article/details/gtfxttznlm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtsaphqkij.html

[Q60] 取上一行 / 下一行
来源：http://dali.sweek.top/Article/details/gtrovdzgnx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.smart0.xyz/Article/details/gtjpbnldvu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gttvuynril.html

[Q61] 移动平均
来源：http://dali.zycfv.cn/Article/details/gtoksecwgs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtjhzoxiic.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gtycbdopod.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtssguqfyd.html

[Q63] 开启事务
来源：http://dali.xuetiantiany.cn/Article/details/gteakjrkzo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yonumen.top/Article/details/gtcmymfwyo.html

[Q64] 提交事务
来源：http://dali.yongpay.top/Article/details/gtuthuspxi.html

COMMIT;
来源：http://dali.nwbrower.top/Article/details/gtglcgkpqp.html

[Q65] 回滚事务
来源：http://dali.sysykeji.top/Article/details/gtipqqhrqc.html

ROLLBACK;
来源：http://dali.gotoacloud.top/Article/details/gtgmkbquuf.html

[Q66] 行锁查询
来源：http://dali.aibaodan.cn/Article/details/gtoqwpyjpm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjyjhdaaq.html

[Q67] 设置隔离级别
来源：http://dali.yonumen.top/Article/details/gtqnlmsecv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shuidangran.top/Article/details/gtthcajuet.html

[Q68] 保存点
来源：http://dali.snrcjt.cn/Article/details/gtrngqnznr.html

SAVEPOINT sp1;
来源：http://dali.ivvv.top/Article/details/gtsbjbafxl.html

ROLLBACK TO sp1;
来源：http://dali.daria6918.cn/Article/details/gttftyecsb.html

[Q69] 查看执行计划
来源：http://dali.ppjwa.cn/Article/details/gtdqzrtqzi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yueranfly.top/Article/details/gtgfaovqpx.html

[Q70] 更新统计信息
来源：http://dali.gzhubu.top/Article/details/gtkvgxhlps.html

ANALYZE TABLE users;
来源：http://dali.yuxming.cn/Article/details/gtmmzvcjls.html

[Q71] 查看建表语句
来源：http://dali.hnqzz.top/Article/details/gtwottwkdd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.wangdashe.top/Article/details/gtqiqhqzzw.html

[Q72] 查看索引
来源：http://dali.xuanzx.com/Article/details/gtevbnlhey.html

SHOW INDEX FROM users;
来源：http://dali.yj20258888.top/Article/details/gtkmufsjbd.html

[Q73] 查看表状态
来源：http://dali.yanxiufei.cn/Article/details/gtlrhutssm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ivvv.top/Article/details/gtvpejvcip.html

[Q74] 强制使用索引
来源：http://dali.svipenyu.cn/Article/details/gthrwkxoje.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangdashe.top/Article/details/gtjjvstlde.html

[Q75] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtwqsagrok.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtaqnvjgnh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinghuilouyu.cn/Article/details/gtodgxsytl.html

[Q76] 按天统计
来源：http://dali.gaohongyu789.top/Article/details/gtyfldielb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcbuentd.html

[Q77] 时间加减
来源：http://dali.nwbrower.top/Article/details/gtktohgmuj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fengsongda.top/Article/details/gtjzisaxcj.html

[Q78] 当前时间
来源：http://dali.c1oappe.top/Article/details/gthpprscbn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yongpay.top/Article/details/gtsozwyubx.html

[Q79] 字符串拼接
来源：http://dali.sysykeji.top/Article/details/gttpnyguey.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nwbrower.top/Article/details/gthunvxeqk.html

[Q80] 字符串截取
来源：http://dali.svipenyu.cn/Article/details/gtpavhvclj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtcttmimhj.html

[Q81] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gthgwzvogl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtjxswgikh.html

[Q82] 字符长度与字节长度
来源：http://dali.gzhubu.top/Article/details/gtjhqyrgbe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnoevboqn.html

[Q83] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvapvgkae.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtqqpvdfyh.html

[Q84] 去除首尾空格
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdzwxegh.html

SELECT TRIM(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtfkatpgbz.html

[Q85] 数值取整
来源：http://dali.yuanzhike.top/Article/details/gtzlrkhoma.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xuanzx.com/Article/details/gtfdebogqu.html

[Q86] 读取 JSON 字段
来源：http://dali.cashguo.top/Article/details/gtguyjhowy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygfqpfwc.html

[Q87] JSON 字段做条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzfuoqqw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.bjfxy.top/Article/details/gtaokzevsb.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj202588.top/Article/details/gtnlqbupds.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnqzz.top/Article/details/gtggnpbywy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gthggzlrgu.html

[Q89] 判断表是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtdccsckqa.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cheryme.top/Article/details/gtsbmwbkem.html

[Q90] 生成序号列
来源：http://dali.yonumen.top/Article/details/gtwiwwroxb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jlsjyb.cn/Article/details/gtuqjzewes.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtmueemjnb.html

R. Bash 专题
来源：http://dali.ydzc1.top/Article/details/gtoxnygaeh.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtkuczhyit.html

[R01] shebang 与严格模式
来源：http://dali.yvedp.cn/Article/details/gtiswldovg.html

#!/usr/bin/env bash
来源：http://dali.guowangkeji.top/Article/details/gtgwrvvpzh.html

set -euo pipefail
来源：http://dali.iojbl.cn/Article/details/gtkujifakl.html

[R02] 变量赋值与使用
来源：http://dali.hywenlv.cn/Article/details/gtvqahxkat.html

name="Tom"; echo "$name"
来源：http://dali.sufxvd.cn/Article/details/gtejujgidn.html

[R03] 只读变量
来源：http://dali.jqgufenzy.top/Article/details/gtpjwkxrrz.html

readonly PI=3.14
来源：http://dali.snrcjt.cn/Article/details/gtmddyfylm.html

[R04] 位置参数
来源：http://dali.yvedp.cn/Article/details/gtpnhialks.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.0kj1m.cn/Article/details/gtibulyvhf.html

[R05] 参数默认值
来源：http://dali.xinyue.icu/Article/details/gtqefkrcum.html

name="${1:-default}"
来源：http://dali.zhiwuduotai.top/Article/details/gtrbyypyou.html

[R06] 判断命令是否存在
来源：http://dali.jianghu66.top/Article/details/gtejdthznf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gtrugrkvln.html

[R07] if 判断文件
来源：http://dali.mhx1999.top/Article/details/gtgjiyiwxs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fengsongda.top/Article/details/gtrtbeeldt.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gtyjtufgwx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenlongwang.top/Article/details/gtoklnntns.html

[R09] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gtpzutmmmx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtidsioign.html

[R10] 正则匹配
来源：http://dali.vqdsnc.cn/Article/details/gtudryowza.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.svipenyu.cn/Article/details/gtokxwfuls.html

[R11] case 多分支
来源：http://dali.meibo888.top/Article/details/gtwmyibpdk.html

case "$1" in
来源：http://dali.sufxvd.cn/Article/details/gtgviztzkp.html

start) echo "启动" ;;
来源：http://dali.haohaochexian.top/Article/details/gtylfxzluj.html

stop)  echo "停止" ;;
来源：http://dali.havefunace.top/Article/details/gthtmerrpb.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gtsdbcoimp.html

esac
来源：http://dali.yuxming.cn/Article/details/gtgmbvczxc.html

[R12] for 遍历文件
来源：http://dali.xziqi.cn/Article/details/gtqbbmuejc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj202588.top/Article/details/gthiznqtfp.html

[R13] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gtcaifdrdh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gtrvttpgia.html

[R14] C 风格 for
来源：http://dali.xziqi.cn/Article/details/gtohawshfz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvfgdqgh.html

[R15] while 逐行读文件
来源：http://dali.316326.xyz/Article/details/gtxhvjjwki.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yvedp.cn/Article/details/gtbpixixtc.html

[R16] until 等待条件
来源：http://dali.smart0.xyz/Article/details/gtpbwicqad.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtzdmkdpfo.html

[R17] 数组定义与取值
来源：http://dali.cashguo.top/Article/details/gtrvsqkfxb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnxiangtu.top/Article/details/gtwucnrjgx.html

[R18] 遍历数组
来源：http://dali.dashuyun.cn/Article/details/gtywwqkzsp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ivvv.top/Article/details/gtbixjdssp.html

[R19] 数组长度
来源：http://dali.xylfe.cn/Article/details/gtmjaapofb.html

echo "${#arr[@]}"
来源：http://dali.cdnleiting.top/Article/details/gtuiuuphdg.html

[R20] 关联数组（字典）
来源：http://dali.sufxvd.cn/Article/details/gtudzbaclj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258888.top/Article/details/gtonyntziv.html

[R21] 字符串长度
来源：http://dali.fengsongda.top/Article/details/gtewouxifb.html

echo "${#s}"
来源：http://dali.daria6918.cn/Article/details/gtkwvdhkbv.html

[R22] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gtvwdvombg.html

echo "${s:0:5}"
来源：http://dali.birdmap.top/Article/details/gtdiavjxnc.html

[R23] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtxrwoymfj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hywenlv.cn/Article/details/gtfxjljzsa.html

[R24] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gtcmciuddy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj202588.top/Article/details/gtdmvqixwo.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtirmcyrml.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnwyudra.html

[R26] 命令替换
来源：http://dali.gogol.net.cn/Article/details/gtsfcmpmch.html

now=$(date +%F); echo "$now"
来源：http://dali.gzhubu.top/Article/details/gtmdwlzyha.html

[R27] 算术展开
来源：http://dali.ivvv.top/Article/details/gtmrlmwigx.html

echo $((1 + 2 * 3))
来源：http://dali.fzhhl.top/Article/details/gtmpsbrtqv.html

[R28] 浮点运算
来源：http://dali.fengsongda.top/Article/details/gtvcqiooeb.html

echo "scale=2; 10/3" | bc
来源：http://dali.gzhubu.top/Article/details/gtnnmtwaqz.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gtantvbruh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhiwuduotai.top/Article/details/gtwcrvjuho.html

[R30] 函数返回状态码
来源：http://dali.andypj.xyz/Article/details/gtgvtvceug.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xinyue.icu/Article/details/gtfdrdndzv.html

[R31] 局部变量
来源：http://dali.316326.xyz/Article/details/gttdptvzij.html

f() { local x=1; echo "$x"; }
来源：http://dali.ppjwa.cn/Article/details/gtwjyhzide.html

[R32] 参数个数校验
来源：http://dali.shzxlz.cn/Article/details/gteulhrsce.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gtkubnntyb.html

[R33] 捕获错误并提示行号
来源：http://dali.zhixingplan.top/Article/details/gtdlxfbpyf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhixingplan.top/Article/details/gtfbalixus.html

[R34] 退出时清理
来源：http://dali.gotoacloud.top/Article/details/gtpsdprbdw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gtgjidfqob.html

[R35] 后台执行并等待
来源：http://dali.nanxuanxn.top/Article/details/gtpikbbkbv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cheryme.top/Article/details/gtejfbekev.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gtyurnengo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hongshengwenyu.top/Article/details/gtpkvsqaur.html

[R37] 把输出赋给变量
来源：http://dali.yj20258.top/Article/details/gtgvedrfhx.html

files=$(ls -1)
来源：http://dali.hongshengwenyu.top/Article/details/gthbyklxgp.html

[R38] 管道串联
来源：http://dali.xziqi.cn/Article/details/gtvaxxlzrm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cqqwz.cn/Article/details/gthwtzqcyi.html

[R39] 重定向标准输出与错误
来源：http://dali.haohaochexian.top/Article/details/gticdefwig.html

cmd > out.log 2>&1
来源：http://dali.jianghu66.top/Article/details/gtlcheushp.html

[R40] 追加写日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmuecjzj.html

echo "log" >> out.log
来源：http://dali.hammf.cn/Article/details/gtuxhwgofv.html

[R41] 丢弃输出
来源：http://dali.c1oappe.top/Article/details/gtvnumggmf.html

cmd >/dev/null 2>&1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapnvtkmy.html

[R42] 输入重定向
来源：http://dali.xinyue.icu/Article/details/gtzlffgcki.html

wc -l < a.txt
来源：http://dali.0kj1m.cn/Article/details/gtxgebgibs.html

[R43] 按名字查找文件
来源：http://dali.smart0.xyz/Article/details/gtbnvctgdm.html


<!-- 参考信息 -->