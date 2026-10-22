代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fzhhl.top/Article/details/gt2zekmzunk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aizwys.cn/Article/details/gt2ekqjdvsj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.meibo888.top/Article/details/gt2rwyvjscf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxgaafst.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uwutsbhy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shuidangran.top/Article/details/gt2uddkevqr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hvrettbk.html

[Q01] 创建表
来源：http://dali.tianlin.xyz/Article/details/gt2jrjxbclo.html

CREATE TABLE users (
来源：http://dali.ybcxt.top/Article/details/gt2veujtnfa.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gt2pjsbgqsv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gt2qihmwwnm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.smart0.xyz/Article/details/gt2ygemxdpe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yvedp.cn/Article/details/gt2zullldlm.html

);
来源：http://dali.sysykeji.top/Article/details/gt2giqbtavq.html

[Q02] 创建带外键的表
来源：http://dali.tianlin.xyz/Article/details/gt2jlouffsw.html

CREATE TABLE orders (
来源：http://dali.yvedp.cn/Article/details/gt2pusjjizl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gt2cmeavscu.html

user_id INT NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gt2oewzmsbe.html

amount DECIMAL(10, 2),
来源：http://dali.svipenyu.cn/Article/details/gt2hzaheutf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.smart0.xyz/Article/details/gt2rkytlgsr.html

);
来源：http://dali.zdqjudy.top/Article/details/gt2lbvjmwkb.html

[Q03] 增加列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bormluam.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xuanzx.com/Article/details/gt2jwkrctsi.html

[Q04] 修改列类型
来源：http://dali.zhoulong.xyz/Article/details/gt2auxbikif.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yongpay.top/Article/details/gt2pmpyvhzd.html

[Q05] 重命名列
来源：http://dali.svipenyu.cn/Article/details/gt2znumtqtw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhixingplan.top/Article/details/gt2osaieuvr.html

[Q06] 删除列
来源：http://dali.gzhubu.top/Article/details/gt2oxpkydlq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxinkj.top/Article/details/gt2apsaauzo.html

[Q07] 删除表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hbzxmqum.html

DROP TABLE IF EXISTS orders;
来源：http://dali.0kj1m.cn/Article/details/gt2eqhkafre.html

[Q08] 创建普通索引
来源：http://dali.hywenlv.cn/Article/details/gt2bfapzypy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gt2jklfdpdn.html

[Q09] 创建唯一索引
来源：http://dali.yongpay.top/Article/details/gt2agtafhfg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gt2hfrymugy.html

[Q10] 插入单行
来源：http://dali.cucudq.cn/Article/details/gt2szzykvpq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gt2vnomgrcm.html

[Q11] 一次插入多行
来源：http://dali.hfpthk.cn/Article/details/gt2jfxqimcm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cashguo.top/Article/details/gt2sfsxuptw.html

[Q12] 插入后取自增 ID
来源：http://dali.iojbl.cn/Article/details/gt2basxxypn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hywenlv.cn/Article/details/gt2qbrhtdxs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.wangshuangyany.cn/Article/details/gt2otdhijwx.html

[Q13] 忽略重复插入
来源：http://dali.xylfe.cn/Article/details/gt2deerhilz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hammf.cn/Article/details/gt2pmmuglro.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnqzz.top/Article/details/gt2yujzrgon.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gaohongyu789.top/Article/details/gt2nhzddjtv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hfpthk.cn/Article/details/gt2hlkrprrg.html

[Q15] 查询全部
来源：http://dali.daxiang520.top/Article/details/gt2ntivnsqd.html

SELECT * FROM users;
来源：http://dali.cashguo.top/Article/details/gt2xbhrqvoj.html

[Q16] 查询指定列
来源：http://dali.hnxiangtu.top/Article/details/gt2qrinvndj.html

SELECT id, name FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2vkiwxlgo.html

[Q17] 条件查询
来源：http://dali.ppjwa.cn/Article/details/gt2ykratbzm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2ikrlzzpv.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ygmlzyxn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aizwys.cn/Article/details/gt2cqupzrhr.html

[Q19] 范围查询
来源：http://dali.hnxiangtu.top/Article/details/gt2gwlbqprj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258888.top/Article/details/gt2otllpfvu.html

[Q20] IN 列表
来源：http://dali.kuanghao11.cn/Article/details/gt2utmlgizq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xinyue.icu/Article/details/gt2yeqmavvb.html

[Q21] 空值判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2waifqlat.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.redwolf501.top/Article/details/gt2ttjcmnyt.html

[Q22] 排序
来源：http://dali.hywenlv.cn/Article/details/gt2lhiycewf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sysykeji.top/Article/details/gt2uzzhgfgt.html

[Q23] 分页
来源：http://dali.xziqi.cn/Article/details/gt2sqzlgwez.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yanxiufei.cn/Article/details/gt2sxlgorgd.html

[Q24] 去重
来源：http://dali.aibaodan.cn/Article/details/gt2bjjmsyct.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258.top/Article/details/gt2vxjzhgqg.html

[Q25] 只取前 N 条
来源：http://dali.jqgfzy.top/Article/details/gt2zzimlixl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ybcxt.top/Article/details/gt2gydmdphc.html

[Q26] 计数
来源：http://dali.wangshuangyany.cn/Article/details/gt2pqrsetts.html

SELECT COUNT(*) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2iravkmir.html

[Q27] 条件计数
来源：http://dali.jqgufenzy.top/Article/details/gt2onvtmlzg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pycfn.com/Article/details/gt2umiatcrh.html

[Q28] 求和与平均
来源：http://dali.yangfankeji.com/Article/details/gt2egjmjhqm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gt2rlpbfjjj.html

[Q29] 最大最小值
来源：http://dali.sufxvd.cn/Article/details/gt2ygrnypbr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2kbtbrqmx.html

[Q30] 分组统计
来源：http://dali.fengsongda.top/Article/details/gt2xsnxhxoq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gt2gdzoivox.html

[Q31] 分组后过滤
来源：http://dali.jinqigfzy.top/Article/details/gt2jbyqnsts.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhongyouzk.top/Article/details/gt2lpiswujf.html

[Q32] 分组拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gt2sdvrjifh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gt2rketdxde.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cqqwz.cn/Article/details/gt2vugqhqng.html

[Q33] 多列分组
来源：http://dali.ydzc1.top/Article/details/gt2soucvdsg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pycfn.com/Article/details/gt2zirxkzvu.html

[Q34] 每组取第一条
来源：http://dali.yonumen.top/Article/details/gt2bwcbotpd.html

SELECT * FROM (
来源：http://dali.shzxlz.cn/Article/details/gt2vlubvedl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cashguo.top/Article/details/gt2gooeudpm.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ipkxespp.html

[Q35] 内连接
来源：http://dali.tanke756.top/Article/details/gt2ocztknpj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gt2ldutbskn.html

[Q36] 左连接
来源：http://dali.jinqigufen.top/Article/details/gt2emyihlck.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2pilgizdv.html

[Q37] 右连接
来源：http://dali.bjfxy.top/Article/details/gt2rjixafci.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sufxvd.cn/Article/details/gt2tcuurazu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.quarkkingdee.top/Article/details/gt2lipvedri.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rxjrdjwp.html

[Q39] 自连接（查上下级）
来源：http://dali.pengpengdd.cyou/Article/details/gt2vzasagzx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xuanzx.com/Article/details/gt2vozltdme.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.9152youxi.cn/Article/details/gt2lugkbhuj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenjidiqi.icu/Article/details/gt2dosomyiz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pglhfjfl.html

[Q41] 多表连接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hpafpvgb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.vqdsnc.cn/Article/details/gt2dvymiiei.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ppjwa.cn/Article/details/gt2odaqjqct.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daria6918.cn/Article/details/gt2ralglxfi.html

[Q42] 连接条件附加过滤
来源：http://dali.zycfv.cn/Article/details/gt2hyjfeekd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.smart0.xyz/Article/details/gt2cazjbpbh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhiwuduotai.top/Article/details/gt2iwvvssnm.html

[Q43] 标量子查询
来源：http://dali.zhixingplan.top/Article/details/gt2stafiwxi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.kuanghao11.cn/Article/details/gt2hzrtilat.html

[Q44] IN 子查询
来源：http://dali.meibo888.top/Article/details/gt2eycbtsnt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.quarkkingdee.top/Article/details/gt2cldgulkg.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2udjddaqs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gt2litkkkcr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jhxvukku.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gt2lcswxkcc.html

[Q47] 与平均值比较
来源：http://dali.hywenlv.cn/Article/details/gt2pcnvfblq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.bjfxy.top/Article/details/gt2biuwpphz.html

[Q48] CTE 公用表表达式
来源：http://dali.wangdashe.top/Article/details/gt2djmvdhpd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jyoumei.cn/Article/details/gt2icevkgew.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.andypj.xyz/Article/details/gt2glfmfmpm.html

[Q49] 更新单行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rbmnsqvm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gt2exqdrzkk.html

[Q50] 批量更新
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zvstohdp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cfnfznkq.html

[Q51] 用子查询更新
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rndbflmi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangdashe.top/Article/details/gt2sbuhdqpx.html

[Q52] 删除指定行
来源：http://dali.zhoulong.xyz/Article/details/gt2pimuizbv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gt2tyhswcol.html

[Q53] 按条件删除
来源：http://dali.hnxiangtu.top/Article/details/gt2thufjwgs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhengqikj.top/Article/details/gt2shooesms.html

[Q54] 清空表
来源：http://dali.sweek.top/Article/details/gt2fidaervf.html

TRUNCATE TABLE logs;
来源：http://dali.cheryme.top/Article/details/gt2duqffeec.html

[Q55] 排名（并列占位）
来源：http://dali.pycfn.com/Article/details/gt2wrxjmlbi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hysaishi.cn/Article/details/gt2mlewedch.html

[Q56] 密集排名（并列不占位）
来源：http://dali.havefunace.top/Article/details/gt2jhgyqznu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258888.top/Article/details/gt2nlvfglmw.html

[Q57] 行号
来源：http://dali.bjfxy.top/Article/details/gt2bfuwhqzx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2czykrgxy.html

[Q58] 累计求和
来源：http://dali.sxryk.cn/Article/details/gt2lhzkytyj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2khrbeawd.html

[Q59] 分组内累计
来源：http://dali.svipenyu.cn/Article/details/gt2dhiropgj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2ddrywifq.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhoulong.xyz/Article/details/gt2gcaikxei.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ppjwa.cn/Article/details/gt2livpmkak.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2xmdlosxy.html

[Q61] 移动平均
来源：http://dali.zhiwuduotai.top/Article/details/gt2wunvvlye.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2clzuymil.html

[Q62] 分组占比
来源：http://dali.hfpthk.cn/Article/details/gt2uflulodu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gt2jiyqvuag.html

[Q63] 开启事务
来源：http://dali.xuanzx.com/Article/details/gt2ifaqldcq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.316326.xyz/Article/details/gt2eelpxogq.html

[Q64] 提交事务
来源：http://dali.0kj1m.cn/Article/details/gt2xkggreul.html

COMMIT;
来源：http://dali.dianchejie.cn/Article/details/gt2pwtidqrs.html

[Q65] 回滚事务
来源：http://dali.yvedp.cn/Article/details/gt2jixqplzz.html

ROLLBACK;
来源：http://dali.meibo888.top/Article/details/gt2jhxupntz.html

[Q66] 行锁查询
来源：http://dali.sufxvd.cn/Article/details/gt2fixqwvzn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.svipenyu.cn/Article/details/gt2sdxtopjl.html

[Q67] 设置隔离级别
来源：http://dali.0kj1m.cn/Article/details/gt2txejedjb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shuidangran.top/Article/details/gt2ajyjcdny.html

[Q68] 保存点
来源：http://dali.guowangkeji.top/Article/details/gt2jhiobdob.html

SAVEPOINT sp1;
来源：http://dali.dashuyun.cn/Article/details/gt2ufzrxbxb.html

ROLLBACK TO sp1;
来源：http://dali.mhx1999.top/Article/details/gt2ibcnesje.html

[Q69] 查看执行计划
来源：http://dali.bjfxy.top/Article/details/gt2tcwrvghk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenjidiqi.icu/Article/details/gt2gkdwiwoo.html

[Q70] 更新统计信息
来源：http://dali.ybcxt.top/Article/details/gt2tuvzxpgt.html

ANALYZE TABLE users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2icuykwqx.html

[Q71] 查看建表语句
来源：http://dali.bjfxy.top/Article/details/gt2bsfyjbrg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ivvv.top/Article/details/gt2dmixxcry.html

[Q72] 查看索引
来源：http://dali.nanxuanxn.top/Article/details/gt2ircteqgp.html

SHOW INDEX FROM users;
来源：http://dali.yonumen.top/Article/details/gt2moppqkhn.html

[Q73] 查看表状态
来源：http://dali.zhongyouzk.top/Article/details/gt2xzugwvup.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.mhx1999.top/Article/details/gt2nkzckjfb.html

[Q74] 强制使用索引
来源：http://dali.9152youxi.cn/Article/details/gt2stoinloc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.snrcjt.cn/Article/details/gt2upynggjy.html

[Q75] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gt2zvgmprvt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2agufewgj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tianlin.xyz/Article/details/gt2ayauijva.html

[Q76] 按天统计
来源：http://dali.aibaodan.cn/Article/details/gt2vfzmeksl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shangyingyoupin.top/Article/details/gt2aioctjfa.html

[Q77] 时间加减
来源：http://dali.yj20258.top/Article/details/gt2tseefqyr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xuetiantiany.cn/Article/details/gt2bwuodzlq.html

[Q78] 当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2xbtercnj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sxryk.cn/Article/details/gt2yibhprsr.html

[Q79] 字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gt2hbwuhnjy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yvedp.cn/Article/details/gt2rukfslmt.html

[Q80] 字符串截取
来源：http://dali.daria6918.cn/Article/details/gt2xxqunaln.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2muxqcxle.html

[Q81] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gt2lghurxeo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2hkudmsps.html

[Q82] 字符长度与字节长度
来源：http://dali.svipenyu.cn/Article/details/gt2jjkxrxxv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oedjarfe.html

[Q83] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gt2wcdjpvfu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2yxjycaro.html

[Q84] 去除首尾空格
来源：http://dali.redwolf501.top/Article/details/gt2tcmloksl.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjakybuu.html

[Q85] 数值取整
来源：http://dali.sufxvd.cn/Article/details/gt2crcrkuwm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnxiangtu.top/Article/details/gt2esvflmkk.html

[Q86] 读取 JSON 字段
来源：http://dali.shzxlz.cn/Article/details/gt2kdjiuqrw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jianghu66.top/Article/details/gt2kapzknuw.html

[Q87] JSON 字段做条件
来源：http://dali.jlsjyb.cn/Article/details/gt2qmurljmq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.snrcjt.cn/Article/details/gt2nkmoerlp.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gt2phwlzkqg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cashguo.top/Article/details/gt2swyebrjq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2sekmkmqr.html

[Q89] 判断表是否存在
来源：http://dali.birdmap.top/Article/details/gt2rphpruly.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.meibo888.top/Article/details/gt2yfkihpyh.html

[Q90] 生成序号列
来源：http://dali.cdnleiting.top/Article/details/gt2qdygheqc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnxiangtu.top/Article/details/gt2veqxwdgo.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2zfjjbwnq.html

R. Bash 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mrqmieuo.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2mdhmrxbd.html

[R01] shebang 与严格模式
来源：http://dali.9152youxi.cn/Article/details/gt2yvozqwiv.html

#!/usr/bin/env bash
来源：http://dali.daria6918.cn/Article/details/gt2iottrala.html

set -euo pipefail
来源：http://dali.daria6918.cn/Article/details/gt2swtwclqr.html

[R02] 变量赋值与使用
来源：http://dali.ydzc1.top/Article/details/gt2eqadoxci.html

name="Tom"; echo "$name"
来源：http://dali.gzhubu.top/Article/details/gt2ujzuysge.html

[R03] 只读变量
来源：http://dali.dashuyun.cn/Article/details/gt2kepfpnzt.html

readonly PI=3.14
来源：http://dali.sufxvd.cn/Article/details/gt2jrsxoemk.html

[R04] 位置参数
来源：http://dali.shuidangran.top/Article/details/gt2vajuiqew.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shangyingyoupin.top/Article/details/gt2andsckhk.html

[R05] 参数默认值
来源：http://dali.birdmap.top/Article/details/gt2ejgrzcrm.html

name="${1:-default}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2vgbfiugf.html

[R06] 判断命令是否存在
来源：http://dali.quarkkingdee.top/Article/details/gt2gaqvsvte.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gt2lljsgezk.html

[R07] if 判断文件
来源：http://dali.daria6918.cn/Article/details/gt2hcxerjlg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.haohaochexian.top/Article/details/gt2bdqhkbja.html

[R08] 数值比较
来源：http://dali.jianghu66.top/Article/details/gt2kjdctxpm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.andypj.xyz/Article/details/gt2jtkxmrja.html

[R09] 字符串比较
来源：http://dali.daria6918.cn/Article/details/gt2sbpyycgj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.havefunace.top/Article/details/gt2yijskbke.html

[R10] 正则匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2umqowuqq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xylfe.cn/Article/details/gt2wqamkgsc.html

[R11] case 多分支
来源：http://dali.daria6918.cn/Article/details/gt2qpqkhvum.html

case "$1" in
来源：http://dali.jinghuilouyu.cn/Article/details/gt2raioxhdv.html

start) echo "启动" ;;
来源：http://dali.yj202588.top/Article/details/gt2xuvvybuz.html

stop)  echo "停止" ;;
来源：http://dali.yongpay.top/Article/details/gt2fafilsut.html

*)     echo "未知命令" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gt2myxudxhv.html

esac
来源：http://dali.316326.xyz/Article/details/gt2qgxfiiwv.html

[R12] for 遍历文件
来源：http://dali.yj20258.top/Article/details/gt2szrwfbgs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2llzpjyxv.html

[R13] for 计数循环
来源：http://dali.cashguo.top/Article/details/gt2ikjsyuhn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gt2trsvljcp.html

[R14] C 风格 for
来源：http://dali.sweek.top/Article/details/gt2rmiyjkhs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gt2tsgrunem.html

[R15] while 逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2npbiozvk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwfnsjdh.html

[R16] until 等待条件
来源：http://dali.zhongyouzk.top/Article/details/gt2hxtvrbys.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2suvamsvk.html

[R17] 数组定义与取值
来源：http://dali.dianchejie.cn/Article/details/gt2xnvbmrgy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jlsjyb.cn/Article/details/gt2hktufaik.html

[R18] 遍历数组
来源：http://dali.yuanzhike.top/Article/details/gt2niftduiq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dianchejie.cn/Article/details/gt2dbqbmaje.html

[R19] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gt2npvftnye.html

echo "${#arr[@]}"
来源：http://dali.gaohongyu789.top/Article/details/gt2ivowhwxz.html

[R20] 关联数组（字典）
来源：http://dali.tianlin.xyz/Article/details/gt2alhsrjwn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ivvv.top/Article/details/gt2iromzezw.html

[R21] 字符串长度
来源：http://dali.cheryme.top/Article/details/gt2fevvpgfw.html

echo "${#s}"
来源：http://dali.zdqjudy.top/Article/details/gt2kawbxbpx.html

[R22] 截取子串
来源：http://dali.nwbrower.top/Article/details/gt2zxqttvga.html

echo "${s:0:5}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2bfcsfuul.html

[R23] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gt2agjxtflt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xylfe.cn/Article/details/gt2pexhbrzs.html

[R24] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2qvehcwhb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhongyouzk.top/Article/details/gt2ogjapolx.html

[R25] 去后缀 / 去前缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbnwtlle.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.snrcjt.cn/Article/details/gt2njuxqvvb.html

[R26] 命令替换
来源：http://dali.smart0.xyz/Article/details/gt2oyybmkci.html

now=$(date +%F); echo "$now"
来源：http://dali.yueranfly.top/Article/details/gt2wypbykds.html

[R27] 算术展开
来源：http://dali.ivvv.top/Article/details/gt2czgzswkl.html

echo $((1 + 2 * 3))
来源：http://dali.aizwys.cn/Article/details/gt2jxuygpmd.html

[R28] 浮点运算
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zkccvifj.html

echo "scale=2; 10/3" | bc
来源：http://dali.quarkkingdee.top/Article/details/gt2ttgglagl.html

[R29] 定义函数
来源：http://dali.aizwys.cn/Article/details/gt2mxcgndbt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ibhmctwt.html

[R30] 函数返回状态码
来源：http://dali.ydzc1.top/Article/details/gt2jsbfyzic.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dashuyun.cn/Article/details/gt2hqthmqkv.html

[R31] 局部变量
来源：http://dali.zdqjudy.top/Article/details/gt2yqaduzqv.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258.top/Article/details/gt2mvevqnup.html

[R32] 参数个数校验
来源：http://dali.wangshuangyany.cn/Article/details/gt2zbjbcsrn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gt2bnmjlxji.html

[R33] 捕获错误并提示行号
来源：http://dali.hysaishi.cn/Article/details/gt2wnpvlsxk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.iojbl.cn/Article/details/gt2ttmpfjby.html

[R34] 退出时清理
来源：http://dali.aizwys.cn/Article/details/gt2njpeymgy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gt2lwgmkeji.html

[R35] 后台执行并等待
来源：http://dali.nanxinkj.top/Article/details/gt2kbzxheez.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xziqi.cn/Article/details/gt2ifrjespf.html

[R36] 并发执行多个任务
来源：http://dali.meibo888.top/Article/details/gt2gjiabgcs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hfpthk.cn/Article/details/gt2uzsrswgk.html

[R37] 把输出赋给变量
来源：http://dali.tian-w.cn/Article/details/gt2cxvpzneh.html

files=$(ls -1)
来源：http://dali.snrcjt.cn/Article/details/gt2nlzpomqp.html

[R38] 管道串联
来源：http://dali.sufxvd.cn/Article/details/gt2lummryfi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sufxvd.cn/Article/details/gt2grgjists.html

[R39] 重定向标准输出与错误
来源：http://dali.pycfn.com/Article/details/gt2rvmkxnrl.html

cmd > out.log 2>&1
来源：http://dali.0kj1m.cn/Article/details/gt2ngcyxmqu.html

[R40] 追加写日志
来源：http://dali.cdnleiting.top/Article/details/gt2nftvktxk.html

echo "log" >> out.log
来源：http://dali.vqdsnc.cn/Article/details/gt2ivozqrpr.html

[R41] 丢弃输出
来源：http://dali.jlsjyb.cn/Article/details/gt2cvofulvd.html


<!-- 参考信息 -->