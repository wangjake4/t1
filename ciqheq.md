代发 wailian999

CREATE TABLE users (
来源：http://dali.hywenlv.cn/Article/details/gt2rrblsagn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gt2mzjygwap.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dianchejie.cn/Article/details/gt2uecpotwl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenjidiqi.icu/Article/details/gt2tpkhexyx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ivvv.top/Article/details/gt2uwepkmol.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ncjlwnyo.html

[Q02] 创建带外键的表
来源：http://dali.dashuyun.cn/Article/details/gt2bzfqnixe.html

CREATE TABLE orders (
来源：http://dali.kuanghao11.cn/Article/details/gt2eyrtcfbr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yongpay.top/Article/details/gt2rojvunnl.html

user_id INT NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gt2hvnhkpmf.html

amount DECIMAL(10, 2),
来源：http://dali.zdqjudy.top/Article/details/gt2hwyixidd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hammf.cn/Article/details/gt2heoqrqip.html

);
来源：http://dali.guannengcc.top/Article/details/gt2iazsdfzd.html

[Q03] 增加列
来源：http://dali.cucudq.cn/Article/details/gt2uqzkmtjg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yonumen.top/Article/details/gt2boqemmbl.html

[Q04] 修改列类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2tjenxdfg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhoulong.xyz/Article/details/gt2aegmtuhg.html

[Q05] 重命名列
来源：http://dali.iojbl.cn/Article/details/gt2ybfzyqkv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgfzy.top/Article/details/gt2ottxtgfu.html

[Q06] 删除列
来源：http://dali.wangshuangyany.cn/Article/details/gt2fsfxcjwl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gt2eqglptrx.html

[Q07] 删除表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xvomypee.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sysykeji.top/Article/details/gt2qvvauzil.html

[Q08] 创建普通索引
来源：http://dali.daria6918.cn/Article/details/gt2rihxuyfr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gt2zczuebby.html

[Q09] 创建唯一索引
来源：http://dali.nanxuanxn.top/Article/details/gt2hoopfpgm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xrmdxwnk.html

[Q10] 插入单行
来源：http://dali.ehwqpu.com/Article/details/gt2nfwmwxux.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ydzc1.top/Article/details/gt2xmdgjyqw.html

[Q11] 一次插入多行
来源：http://dali.iojbl.cn/Article/details/gt2bxfulojr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gt2dglakgwh.html

[Q12] 插入后取自增 ID
来源：http://dali.pengpengdd.cyou/Article/details/gt2oatefgay.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhengqikj.top/Article/details/gt2jjygxssg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ehwqpu.com/Article/details/gt2mbrnumjg.html

[Q13] 忽略重复插入
来源：http://dali.ppjwa.cn/Article/details/gt2ocutyeny.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj202588.top/Article/details/gt2rmftxruk.html

[Q14] 存在则更新（upsert）
来源：http://dali.ydzc1.top/Article/details/gt2uomkqfqx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj20258888.top/Article/details/gt2hvamdamf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhongyouzk.top/Article/details/gt2fauqwovq.html

[Q15] 查询全部
来源：http://dali.gotoacloud.top/Article/details/gt2llgncqik.html

SELECT * FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2jombtkkr.html

[Q16] 查询指定列
来源：http://dali.xziqi.cn/Article/details/gt2irdcbzbj.html

SELECT id, name FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2irvawfni.html

[Q17] 条件查询
来源：http://dali.hammf.cn/Article/details/gt2owkqeper.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2oqoeumis.html

[Q18] 模糊匹配
来源：http://dali.jinqigufen.top/Article/details/gt2hwupbwvr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hysaishi.cn/Article/details/gt2ambdbbun.html

[Q19] 范围查询
来源：http://dali.yanxiufei.cn/Article/details/gt2psmclyzc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qbnxibvy.html

[Q20] IN 列表
来源：http://dali.yueranfly.top/Article/details/gt2xoizomse.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj202588.top/Article/details/gt2ypgbrjcu.html

[Q21] 空值判断
来源：http://dali.mhx1999.top/Article/details/gt2eblmwaox.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hysaishi.cn/Article/details/gt2wsidafks.html

[Q22] 排序
来源：http://dali.guannengcc.top/Article/details/gt2vjidogzx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.snrcjt.cn/Article/details/gt2ytzcvrzd.html

[Q23] 分页
来源：http://dali.gaohongyu789.top/Article/details/gt2hovuayxd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jlsjyb.cn/Article/details/gt2cmbrwhmo.html

[Q24] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gt2dfnrafhi.html

SELECT DISTINCT city FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2yncabslq.html

[Q25] 只取前 N 条
来源：http://dali.chenlongwang.top/Article/details/gt2pismxktf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yongpay.top/Article/details/gt2pmjqulxy.html

[Q26] 计数
来源：http://dali.jqgfzy.top/Article/details/gt2fxrrfijt.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ikdhbqnr.html

[Q27] 条件计数
来源：http://dali.zhixingplan.top/Article/details/gt2zzegvlsq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2aczfauax.html

[Q28] 求和与平均
来源：http://dali.aizwys.cn/Article/details/gt2tlllyfpw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gt2dqeduvxi.html

[Q29] 最大最小值
来源：http://dali.c1oappe.top/Article/details/gt2gwlqdddy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2vecwsnps.html

[Q30] 分组统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kqbsxevc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gt2vwlwdvkw.html

[Q31] 分组后过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yssqmnin.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.andypj.xyz/Article/details/gt2milsivju.html

[Q32] 分组拼接字符串
来源：http://dali.fzhhl.top/Article/details/gt2ivmsmwdx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gt2jjmenypm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nwbrower.top/Article/details/gt2dqjnvmtq.html

[Q33] 多列分组
来源：http://dali.xuanzx.com/Article/details/gt2loadtpuf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sxryk.cn/Article/details/gt2yyrknxxu.html

[Q34] 每组取第一条
来源：http://dali.shzxlz.cn/Article/details/gt2njtflfhi.html

SELECT * FROM (
来源：http://dali.kuanghao11.cn/Article/details/gt2vcolfdvi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenlongwang.top/Article/details/gt2vncxsqct.html

) t WHERE rn = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2uzavrhdg.html

[Q35] 内连接
来源：http://dali.jiagoushi.top/Article/details/gt2xapamslz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gt2ubcdfavx.html

[Q36] 左连接
来源：http://dali.jqgfzy.top/Article/details/gt2nrqiobpi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gt2pspvmbfh.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gt2oswvdyrt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ydzc1.top/Article/details/gt2lqgktgnn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zfidnsyl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nwbrower.top/Article/details/gt2gbvzjift.html

[Q39] 自连接（查上下级）
来源：http://dali.chenlongwang.top/Article/details/gt2wpwsbtqr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.0kj1m.cn/Article/details/gt2eorxgcvd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj20258.top/Article/details/gt2wnjhfztb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gotoacloud.top/Article/details/gt2yacqbahs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gotoacloud.top/Article/details/gt2vpdjrmso.html

[Q41] 多表连接
来源：http://dali.fzhhl.top/Article/details/gt2cbvudljz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.havefunace.top/Article/details/gt2mnbdftqp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xylfe.cn/Article/details/gt2ubgccjkt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tianlin.xyz/Article/details/gt2wrlltrpc.html

[Q42] 连接条件附加过滤
来源：http://dali.shzxlz.cn/Article/details/gt2fuwznjiz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnxiangtu.top/Article/details/gt2mmglnlnk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zdqjudy.top/Article/details/gt2neqbgttd.html

[Q43] 标量子查询
来源：http://dali.cucudq.cn/Article/details/gt2aegusazf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.snrcjt.cn/Article/details/gt2sdczvlne.html

[Q44] IN 子查询
来源：http://dali.yvedp.cn/Article/details/gt2brmzvhoz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yueranfly.top/Article/details/gt2hpxgcnew.html

[Q45] EXISTS 判断存在
来源：http://dali.havefunace.top/Article/details/gt2ayuekatm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qgucscrz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sysykeji.top/Article/details/gt2zgdbkboj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.havefunace.top/Article/details/gt2byelbetl.html

[Q47] 与平均值比较
来源：http://dali.cqqwz.cn/Article/details/gt2mniwpfgp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258.top/Article/details/gt2fxsemxat.html

[Q48] CTE 公用表表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bhvdsdcu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yanxiufei.cn/Article/details/gt2xfcdylen.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gogol.net.cn/Article/details/gt2qjtcrlwk.html

[Q49] 更新单行
来源：http://dali.yangfankeji.com/Article/details/gt2vfatvciz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gt2vllhcfli.html

[Q50] 批量更新
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rytxautj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhiwuduotai.top/Article/details/gt2zuynwbff.html

[Q51] 用子查询更新
来源：http://dali.jiagoushi.top/Article/details/gt2dfkxfokp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ydzc1.top/Article/details/gt2kmvdmamx.html

[Q52] 删除指定行
来源：http://dali.yanxiufei.cn/Article/details/gt2hlplkxyu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gt2kzyjxvyn.html

[Q53] 按条件删除
来源：http://dali.daxiang520.top/Article/details/gt2uotonqaz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yonumen.top/Article/details/gt2eliuwwgn.html

[Q54] 清空表
来源：http://dali.zhixingplan.top/Article/details/gt2fqvbhgoy.html

TRUNCATE TABLE logs;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2flxptnsu.html

[Q55] 排名（并列占位）
来源：http://dali.mhx1999.top/Article/details/gt2iqlkvgal.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daxiang520.top/Article/details/gt2qigjehnd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2esnocxma.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gotoacloud.top/Article/details/gt2pjslqplb.html

[Q57] 行号
来源：http://dali.cdnleiting.top/Article/details/gt2cvxptwlp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2zmlzkvfv.html

[Q58] 累计求和
来源：http://dali.ybcxt.top/Article/details/gt2ifmphjfa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tian-w.cn/Article/details/gt2fjuhoukh.html

[Q59] 分组内累计
来源：http://dali.316326.xyz/Article/details/gt2udrfinnz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2xlvnslku.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgpzmvr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zdqjudy.top/Article/details/gt2astwxoff.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2vlmrazew.html

[Q61] 移动平均
来源：http://dali.xylfe.cn/Article/details/gt2siwkakmj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2eqyikycd.html

[Q62] 分组占比
来源：http://dali.hywenlv.cn/Article/details/gt2aicqrmxb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gt2dlekzctx.html

[Q63] 开启事务
来源：http://dali.cucudq.cn/Article/details/gt2hjqktcrc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ivvv.top/Article/details/gt2rojjlndq.html

[Q64] 提交事务
来源：http://dali.ybcxt.top/Article/details/gt2ziyjfkbu.html

COMMIT;
来源：http://dali.ivvv.top/Article/details/gt2cxbfnruz.html

[Q65] 回滚事务
来源：http://dali.zhoulong.xyz/Article/details/gt2nzzazwtc.html

ROLLBACK;
来源：http://dali.dashuyun.cn/Article/details/gt2ndumrkjm.html

[Q66] 行锁查询
来源：http://dali.xuanzx.com/Article/details/gt2rswcwlmv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tianlin.xyz/Article/details/gt2dejjjtsa.html

[Q67] 设置隔离级别
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aosumnej.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.9152youxi.cn/Article/details/gt2kgdqxizd.html

[Q68] 保存点
来源：http://dali.9152youxi.cn/Article/details/gt2lntgxvwg.html

SAVEPOINT sp1;
来源：http://dali.yj202588.top/Article/details/gt2qqzftnju.html

ROLLBACK TO sp1;
来源：http://dali.tianlin.xyz/Article/details/gt2pjnkcchl.html

[Q69] 查看执行计划
来源：http://dali.vqdsnc.cn/Article/details/gt2wbmxcguk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ppjwa.cn/Article/details/gt2dwwyxfvs.html

[Q70] 更新统计信息
来源：http://dali.xylfe.cn/Article/details/gt2neghvufz.html

ANALYZE TABLE users;
来源：http://dali.jianghu66.top/Article/details/gt2ojvecksv.html

[Q71] 查看建表语句
来源：http://dali.cheryme.top/Article/details/gt2tzbkkywx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xziqi.cn/Article/details/gt2gopkmgzx.html

[Q72] 查看索引
来源：http://dali.gaohongyu789.top/Article/details/gt2wkdycxyf.html

SHOW INDEX FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2exsznlae.html

[Q73] 查看表状态
来源：http://dali.ivvv.top/Article/details/gt2gsfyxvig.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fzhhl.top/Article/details/gt2mogpqwpw.html

[Q74] 强制使用索引
来源：http://dali.jinqigufen.top/Article/details/gt2qzmfpfuh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hnqzz.top/Article/details/gt2goincfhn.html

[Q75] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gt2nelghyjo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2rlzaotqz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xinyue.icu/Article/details/gt2gvwovzoh.html

[Q76] 按天统计
来源：http://dali.yanxiufei.cn/Article/details/gt2ioexhstf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sweek.top/Article/details/gt2ieclpfko.html

[Q77] 时间加减
来源：http://dali.yongpay.top/Article/details/gt2jjjvcnjx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tian-w.cn/Article/details/gt2mkakczxw.html

[Q78] 当前时间
来源：http://dali.daxiang520.top/Article/details/gt2oohkcvyw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ivvv.top/Article/details/gt2lyrlcjew.html

[Q79] 字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gt2qknpsksf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.feifeiyinyue.top/Article/details/gt2mysrztkb.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqrcprtp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2cjzxkvyn.html

[Q81] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gt2gnxjudfe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2akmanbzt.html

[Q82] 字符长度与字节长度
来源：http://dali.birdmap.top/Article/details/gt2gatlshnr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2bpvgfxch.html

[Q83] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gt2ndgesvdc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2nyhmdcqy.html

[Q84] 去除首尾空格
来源：http://dali.haohaochexian.top/Article/details/gt2rtxscvnu.html

SELECT TRIM(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2vjucxfjn.html

[Q85] 数值取整
来源：http://dali.hywenlv.cn/Article/details/gt2kmtojcjd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ddlkknav.html

[Q86] 读取 JSON 字段
来源：http://dali.zhixingplan.top/Article/details/gt2mfvxzmag.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jiagoushi.top/Article/details/gt2tpdncofl.html

[Q87] JSON 字段做条件
来源：http://dali.xylfe.cn/Article/details/gt2fulftjps.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigfzy.top/Article/details/gt2rldwrwpz.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258.top/Article/details/gt2rmdsiswi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258888.top/Article/details/gt2lngmajlf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ezxnurjf.html

[Q89] 判断表是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2rarjkvvt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.snrcjt.cn/Article/details/gt2yrifvwnq.html

[Q90] 生成序号列
来源：http://dali.zhixingplan.top/Article/details/gt2zmkrzlky.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cucudq.cn/Article/details/gt2xhhirirw.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2gbxwlrza.html

R. Bash 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mfasiaut.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2zrghyedc.html

[R01] shebang 与严格模式
来源：http://dali.xziqi.cn/Article/details/gt2szaynipt.html

#!/usr/bin/env bash
来源：http://dali.sweek.top/Article/details/gt2wipjsdop.html

set -euo pipefail
来源：http://dali.hfpthk.cn/Article/details/gt2cjhctbae.html

[R02] 变量赋值与使用
来源：http://dali.nanxinkj.top/Article/details/gt2fhptzarz.html

name="Tom"; echo "$name"
来源：http://dali.ivvv.top/Article/details/gt2qiorwuls.html

[R03] 只读变量
来源：http://dali.sxryk.cn/Article/details/gt2dkcolbyb.html

readonly PI=3.14
来源：http://dali.cheryme.top/Article/details/gt2eupcufsq.html

[R04] 位置参数
来源：http://dali.svipenyu.cn/Article/details/gt2pacdashe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hysaishi.cn/Article/details/gt2cdineuwh.html

[R05] 参数默认值
来源：http://dali.redwolf501.top/Article/details/gt2szrvazgz.html

name="${1:-default}"
来源：http://dali.nanxinkj.top/Article/details/gt2gakyhpav.html

[R06] 判断命令是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qbvruaqm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpqrgpht.html

[R07] if 判断文件
来源：http://dali.wangdashe.top/Article/details/gt2zqazguyt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2txxhtmnd.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gt2utttsjmm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yongpay.top/Article/details/gt2szjklgyu.html

[R09] 字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gt2hcgrnbsp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hywenlv.cn/Article/details/gt2yjtvnvif.html

[R10] 正则匹配
来源：http://dali.jiagoushi.top/Article/details/gt2gpygcdvw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuanzhike.top/Article/details/gt2yzsygsxk.html

[R11] case 多分支
来源：http://dali.zhongyouzk.top/Article/details/gt2nstyjjao.html

case "$1" in
来源：http://dali.ehwqpu.com/Article/details/gt2kyiudoir.html

start) echo "启动" ;;
来源：http://dali.hywenlv.cn/Article/details/gt2lfpfznby.html

stop)  echo "停止" ;;
来源：http://dali.316326.xyz/Article/details/gt2pondrxkg.html

*)     echo "未知命令" ;;
来源：http://dali.gzhubu.top/Article/details/gt2gujwyiow.html

esac
来源：http://dali.bjfxy.top/Article/details/gt2qkhzpqch.html

[R12] for 遍历文件
来源：http://dali.fzhhl.top/Article/details/gt2lwtbdoor.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2bezndgah.html

[R13] for 计数循环
来源：http://dali.yueranfly.top/Article/details/gt2mgvzbyxr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gt2ofblrfjh.html

[R14] C 风格 for
来源：http://dali.cdnleiting.top/Article/details/gt2yrfakvcg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2sklrvkty.html

[R15] while 逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbaeusrf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigufen.top/Article/details/gt2dyebpcci.html

[R16] until 等待条件
来源：http://dali.smart0.xyz/Article/details/gt2jbnlhlfc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gt2dwnmlfln.html

[R17] 数组定义与取值
来源：http://dali.guowangkeji.top/Article/details/gt2bechorte.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gaohongyu789.top/Article/details/gt2lubrqjai.html

[R18] 遍历数组
来源：http://dali.sxryk.cn/Article/details/gt2hfmrzoek.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gzhubu.top/Article/details/gt2pejbxqyb.html

[R19] 数组长度
来源：http://dali.yvedp.cn/Article/details/gt2jhqgygvs.html

echo "${#arr[@]}"
来源：http://dali.jqgfzy.top/Article/details/gt2dolfttlc.html

[R20] 关联数组（字典）
来源：http://dali.xziqi.cn/Article/details/gt2wvukkkji.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnqzz.top/Article/details/gt2fowzrwsw.html

[R21] 字符串长度
来源：http://dali.shzxlz.cn/Article/details/gt2sbplmfcr.html

echo "${#s}"
来源：http://dali.yuxming.cn/Article/details/gt2mfnbtkwk.html

[R22] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gt2shkbpwac.html

echo "${s:0:5}"
来源：http://dali.nanxinkj.top/Article/details/gt2zlvkvyqk.html

[R23] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qzeswxna.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ivvv.top/Article/details/gt2sbhcqzvd.html

[R24] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gt2qxuywymr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuanzhike.top/Article/details/gt2paomzqog.html

[R25] 去后缀 / 去前缀
来源：http://dali.cqqwz.cn/Article/details/gt2krsyggat.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shzxlz.cn/Article/details/gt2ampaaapc.html

[R26] 命令替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lqmybonp.html

now=$(date +%F); echo "$now"
来源：http://dali.snrcjt.cn/Article/details/gt2pkwxjzdt.html

[R27] 算术展开
来源：http://dali.iojbl.cn/Article/details/gt2kubwmdnb.html

echo $((1 + 2 * 3))
来源：http://dali.yuxming.cn/Article/details/gt2kdahjmme.html

[R28] 浮点运算
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wssrrjbv.html

echo "scale=2; 10/3" | bc
来源：http://dali.cdnleiting.top/Article/details/gt2pntxiynd.html

[R29] 定义函数
来源：http://dali.xuanzx.com/Article/details/gt2mwwtwjbz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ybcxt.top/Article/details/gt2rnwolhsb.html

[R30] 函数返回状态码
来源：http://dali.hfpthk.cn/Article/details/gt2dlfhpfbb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pycfn.com/Article/details/gt2qgrjmoty.html

[R31] 局部变量
来源：http://dali.yj20258888.top/Article/details/gt2jdejzotj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2itrpmzhu.html

[R32] 参数个数校验
来源：http://dali.iojbl.cn/Article/details/gt2oltlqena.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gt2lohzfweg.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigfzy.top/Article/details/gt2ufkwjvuw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.smart0.xyz/Article/details/gt2htefpsjp.html

[R34] 退出时清理
来源：http://dali.zhongyouzk.top/Article/details/gt2qmlzzoua.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gt2csvzzoyp.html

[R35] 后台执行并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hpmczwkw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guowangkeji.top/Article/details/gt2dqufztmr.html

[R36] 并发执行多个任务
来源：http://dali.svipenyu.cn/Article/details/gt2vvqrgted.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.smart0.xyz/Article/details/gt2bltvuzhx.html

[R37] 把输出赋给变量
来源：http://dali.pycfn.com/Article/details/gt2eojlvhzh.html

files=$(ls -1)
来源：http://dali.yvedp.cn/Article/details/gt2bcgupnbd.html

[R38] 管道串联
来源：http://dali.shzxlz.cn/Article/details/gt2ezllbmeg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.redwolf501.top/Article/details/gt2hjsgdqed.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgfzy.top/Article/details/gt2dxhgwuae.html

cmd > out.log 2>&1
来源：http://dali.dashuyun.cn/Article/details/gt2vdpqbqrz.html

[R40] 追加写日志
来源：http://dali.pengpengdd.cyou/Article/details/gt2dwxyctvo.html

echo "log" >> out.log
来源：http://dali.nanxuanxn.top/Article/details/gt2zhjztzxc.html

[R41] 丢弃输出
来源：http://dali.zhiwuduotai.top/Article/details/gt2rewmvzib.html

cmd >/dev/null 2>&1
来源：http://dali.xylfe.cn/Article/details/gt2wqjvovde.html

[R42] 输入重定向
来源：http://dali.fzhhl.top/Article/details/gt2ulxeswiu.html

wc -l < a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2veqabhyk.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2emwcjraj.html

find . -name "*.log" -type f
来源：http://dali.bjfxy.top/Article/details/gt2vebldwpe.html

[R44] 按修改时间查找
来源：http://dali.xuetiantiany.cn/Article/details/gt2qjjgtngr.html

find . -mtime -7 -type f
来源：http://dali.gogol.net.cn/Article/details/gt2hessgjue.html

[R45] 批量删除
来源：http://dali.aizwys.cn/Article/details/gt2xcdicgft.html


<!-- 参考信息 -->