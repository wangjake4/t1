代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gtkgfdzewg.html

user_id INT NOT NULL,
来源：http://dali.havefunace.top/Article/details/gtkmgcujgh.html

amount DECIMAL(10, 2),
来源：http://dali.ybcxt.top/Article/details/gtdnyiownv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj202588.top/Article/details/gtiwdfxkqn.html

);
来源：http://dali.svipenyu.cn/Article/details/gtqtwmkhot.html

[Q03] 增加列
来源：http://dali.havefunace.top/Article/details/gtxekhhtej.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yongpay.top/Article/details/gtnzzcxvzx.html

[Q04] 修改列类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgluvvqah.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nanxinkj.top/Article/details/gtkazvxdqk.html

[Q05] 重命名列
来源：http://dali.daxiang520.top/Article/details/gtfwhqcres.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenlongwang.top/Article/details/gtwnpxdwoy.html

[Q06] 删除列
来源：http://dali.sysykeji.top/Article/details/gtdrmiticf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gzhubu.top/Article/details/gtedrttzde.html

[Q07] 删除表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwamdvxgn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yvedp.cn/Article/details/gtifwvzsiw.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gtsxgwkcqy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.bjfxy.top/Article/details/gtaoympvfj.html

[Q09] 创建唯一索引
来源：http://dali.nwbrower.top/Article/details/gtnznvhask.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gthyzlftmt.html

[Q10] 插入单行
来源：http://dali.c1oappe.top/Article/details/gtqytoqnkk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gtampulyto.html

[Q11] 一次插入多行
来源：http://dali.nanxinkj.top/Article/details/gtqhgzkkio.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzushbpj.html

[Q12] 插入后取自增 ID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzykwjrhi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sufxvd.cn/Article/details/gteepidwmj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.redwolf501.top/Article/details/gtagrcuwwn.html

[Q13] 忽略重复插入
来源：http://dali.zhengqikj.top/Article/details/gtykuucndq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.bjfxy.top/Article/details/gtoymsmdnj.html

[Q14] 存在则更新（upsert）
来源：http://dali.snrcjt.cn/Article/details/gtpitvxoio.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ybcxt.top/Article/details/gtpduwzago.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ppjwa.cn/Article/details/gtrrcbixan.html

[Q15] 查询全部
来源：http://dali.yvedp.cn/Article/details/gthpippnim.html

SELECT * FROM users;
来源：http://dali.tian-w.cn/Article/details/gtjcidiimr.html

[Q16] 查询指定列
来源：http://dali.zhixingplan.top/Article/details/gtpndvjrcw.html

SELECT id, name FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqukoxjk.html

[Q17] 条件查询
来源：http://dali.sxryk.cn/Article/details/gtmuzebfiq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258.top/Article/details/gtobobzbmu.html

[Q18] 模糊匹配
来源：http://dali.jinqigfzy.top/Article/details/gtoedrlvdo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shangyingyoupin.top/Article/details/gtbrfwpxkt.html

[Q19] 范围查询
来源：http://dali.cheryme.top/Article/details/gtlcxsdepy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.316326.xyz/Article/details/gtewozpjfu.html

[Q20] IN 列表
来源：http://dali.ppjwa.cn/Article/details/gtyppfgett.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.aibaodan.cn/Article/details/gtuxzxjsqr.html

[Q21] 空值判断
来源：http://dali.aibaodan.cn/Article/details/gtvygrizye.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tianlin.xyz/Article/details/gtatallhkg.html

[Q22] 排序
来源：http://dali.yangfankeji.com/Article/details/gtrtdvjhvt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuxming.cn/Article/details/gtctcddbls.html

[Q23] 分页
来源：http://dali.zhoulong.xyz/Article/details/gtleshxopy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tian-w.cn/Article/details/gtaqdodnmm.html

[Q24] 去重
来源：http://dali.hfpthk.cn/Article/details/gtmqahohps.html

SELECT DISTINCT city FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtswgogerm.html

[Q25] 只取前 N 条
来源：http://dali.cqqwz.cn/Article/details/gtvtrtzhff.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yanxiufei.cn/Article/details/gtzebqjcuw.html

[Q26] 计数
来源：http://dali.yj20258888.top/Article/details/gtpwxhydmv.html

SELECT COUNT(*) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtedpscdov.html

[Q27] 条件计数
来源：http://dali.hnqzz.top/Article/details/gtdctpckyw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gzhubu.top/Article/details/gtyplueqik.html

[Q28] 求和与平均
来源：http://dali.ydzc1.top/Article/details/gtwrqkeduj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtdzofilkv.html

[Q29] 最大最小值
来源：http://dali.chenzaomai.com/Article/details/gtgvavhkto.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtzyydwrvh.html

[Q30] 分组统计
来源：http://dali.ivvv.top/Article/details/gteoqlnsyz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtcgggdczl.html

[Q31] 分组后过滤
来源：http://dali.redwolf501.top/Article/details/gtaregvurh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jianghu66.top/Article/details/gtnthyubjk.html

[Q32] 分组拼接字符串
来源：http://dali.yj20258.top/Article/details/gtwnmkyvea.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gtvfhwdmta.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.quarkkingdee.top/Article/details/gtimwwziai.html

[Q33] 多列分组
来源：http://dali.wangshuangyany.cn/Article/details/gtdusncgec.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pycfn.com/Article/details/gtgffojwxo.html

[Q34] 每组取第一条
来源：http://dali.iojbl.cn/Article/details/gtrbwagzvd.html

SELECT * FROM (
来源：http://dali.aibaodan.cn/Article/details/gtofahwuym.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.meibo888.top/Article/details/gtwfqwmuiw.html

) t WHERE rn = 1;
来源：http://dali.mhx1999.top/Article/details/gtuiikdtct.html

[Q35] 内连接
来源：http://dali.xziqi.cn/Article/details/gtpqqpwbrx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gtblwoxalo.html

[Q36] 左连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwcusosx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gtaueekiqg.html

[Q37] 右连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvsmzmetz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuxming.cn/Article/details/gtlrvbhknt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.smart0.xyz/Article/details/gtozxgvgkc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pycfn.com/Article/details/gtapafrgdi.html

[Q39] 自连接（查上下级）
来源：http://dali.xuanzx.com/Article/details/gthhvqhpir.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gogol.net.cn/Article/details/gtcvhtznho.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tian-w.cn/Article/details/gtptzburay.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ybcxt.top/Article/details/gtuhithufk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gtwlznittv.html

[Q41] 多表连接
来源：http://dali.wangshuangyany.cn/Article/details/gtmdlddyqc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnxiangtu.top/Article/details/gtkqxmokow.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258888.top/Article/details/gtcdjurofl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cqqwz.cn/Article/details/gtqgshatcj.html

[Q42] 连接条件附加过滤
来源：http://dali.tanke756.top/Article/details/gtebzdnjtw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ehwqpu.com/Article/details/gtjkiqxkpu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aibaodan.cn/Article/details/gteiepetfs.html

[Q43] 标量子查询
来源：http://dali.tanke756.top/Article/details/gtjiywlqfu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tianlin.xyz/Article/details/gtxbelslcn.html

[Q44] IN 子查询
来源：http://dali.ybcxt.top/Article/details/gtzezrxail.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gaohongyu789.top/Article/details/gtffijspys.html

[Q45] EXISTS 判断存在
来源：http://dali.ydzc1.top/Article/details/gtumeybyaq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdayweole.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fzhhl.top/Article/details/gtmkiwqwop.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gtnlvyxras.html

[Q47] 与平均值比较
来源：http://dali.hywenlv.cn/Article/details/gtwleoqhft.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenzaomai.com/Article/details/gtwaerlnfn.html

[Q48] CTE 公用表表达式
来源：http://dali.fzhhl.top/Article/details/gtwaamzzfo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hfpthk.cn/Article/details/gturhtoolp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hywenlv.cn/Article/details/gtqtllnxyx.html

[Q49] 更新单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnkplkxb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gteaxrbhfg.html

[Q50] 批量更新
来源：http://dali.jinqigufen.top/Article/details/gtzjjzqbtj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuxming.cn/Article/details/gtkvdrqklj.html

[Q51] 用子查询更新
来源：http://dali.yj20258888.top/Article/details/gtxyrbrdjz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tianlin.xyz/Article/details/gtlfuqgsmm.html

[Q52] 删除指定行
来源：http://dali.ybcxt.top/Article/details/gtbflcejrf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gtlwugqwtl.html

[Q53] 按条件删除
来源：http://dali.tanke756.top/Article/details/gtrhrngpcv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxinkj.top/Article/details/gtgrrzndyp.html

[Q54] 清空表
来源：http://dali.sufxvd.cn/Article/details/gtqauvpqol.html

TRUNCATE TABLE logs;
来源：http://dali.chenlongwang.top/Article/details/gtfkhxfalg.html

[Q55] 排名（并列占位）
来源：http://dali.jyoumei.cn/Article/details/gtudrooymi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangdashe.top/Article/details/gtukqlnoyd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hammf.cn/Article/details/gtgdcitomp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guannengcc.top/Article/details/gtlgprwdfg.html

[Q57] 行号
来源：http://dali.nanxinkj.top/Article/details/gtsttykcen.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuxming.cn/Article/details/gtpxcplwyt.html

[Q58] 累计求和
来源：http://dali.sweek.top/Article/details/gtvawhxylp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.mhx1999.top/Article/details/gthjtypeak.html

[Q59] 分组内累计
来源：http://dali.meibo888.top/Article/details/gtesicngve.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtubjcrwrr.html

[Q60] 取上一行 / 下一行
来源：http://dali.snrcjt.cn/Article/details/gtxcakybfb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pengpengdd.cyou/Article/details/gttyuqrrni.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtdjdumgvm.html

[Q61] 移动平均
来源：http://dali.tian-w.cn/Article/details/gtmtvtqdyt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtvquxfjkk.html

[Q62] 分组占比
来源：http://dali.hnqzz.top/Article/details/gtlljwbdgf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gtusvazeej.html

[Q63] 开启事务
来源：http://dali.gotoacloud.top/Article/details/gtmzfcozet.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sufxvd.cn/Article/details/gtbxqfdtac.html

[Q64] 提交事务
来源：http://dali.haohaochexian.top/Article/details/gtoxqvfnrc.html

COMMIT;
来源：http://dali.daxiang520.top/Article/details/gtyzhpcztm.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangtech.top/Article/details/gttyebwbwm.html

ROLLBACK;
来源：http://dali.nanxinkj.top/Article/details/gtcnibybhy.html

[Q66] 行锁查询
来源：http://dali.cqqwz.cn/Article/details/gtkmohlrpz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnqzz.top/Article/details/gtvaamhjbn.html

[Q67] 设置隔离级别
来源：http://dali.ivvv.top/Article/details/gtvcnphhru.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj202588.top/Article/details/gtxrkwwdac.html

[Q68] 保存点
来源：http://dali.ydzc1.top/Article/details/gtctavzzdp.html

SAVEPOINT sp1;
来源：http://dali.nwbrower.top/Article/details/gtvdpjlzbo.html

ROLLBACK TO sp1;
来源：http://dali.ivvv.top/Article/details/gtzvkgwxhg.html

[Q69] 查看执行计划
来源：http://dali.gogol.net.cn/Article/details/gtlnqubmlr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.mhx1999.top/Article/details/gtrchcvsfq.html

[Q70] 更新统计信息
来源：http://dali.ppjwa.cn/Article/details/gtecdhbpsu.html

ANALYZE TABLE users;
来源：http://dali.yangfankeji.com/Article/details/gteouayuzf.html

[Q71] 查看建表语句
来源：http://dali.fengsongda.top/Article/details/gtpdscitvo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhengqikj.top/Article/details/gtfjbclqho.html

[Q72] 查看索引
来源：http://dali.ehwqpu.com/Article/details/gtrnoykkaa.html

SHOW INDEX FROM users;
来源：http://dali.tanke756.top/Article/details/gtspwguilm.html

[Q73] 查看表状态
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuwkweof.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj202588.top/Article/details/gthuvmvpcu.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gtwgxrgmzv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sxryk.cn/Article/details/gtikxbmroy.html

[Q75] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gtswmkxdwn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtygqstksg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ybcxt.top/Article/details/gtejsbujea.html

[Q76] 按天统计
来源：http://dali.quarkkingdee.top/Article/details/gtqlnrkpcp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhengqikj.top/Article/details/gtoyrdqqpo.html

[Q77] 时间加减
来源：http://dali.yuxming.cn/Article/details/gtzsviylxl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangdashe.top/Article/details/gtsbpqfgkt.html

[Q78] 当前时间
来源：http://dali.cdnleiting.top/Article/details/gtvzzvuiat.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.haohaochexian.top/Article/details/gthznskxzx.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gtalhazqwq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.9152youxi.cn/Article/details/gtuakuqxzk.html

[Q80] 字符串截取
来源：http://dali.dashuyun.cn/Article/details/gtydbjgsxy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtadnzwvqo.html

[Q81] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gtdhnhfhbo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtvjyugwql.html

[Q82] 字符长度与字节长度
来源：http://dali.xuetiantiany.cn/Article/details/gtxrkhcbkh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtquhsggma.html

[Q83] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gtghqbtrtu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtppbxtugj.html

[Q84] 去除首尾空格
来源：http://dali.daria6918.cn/Article/details/gtaltehhkx.html

SELECT TRIM(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gteexxdtor.html

[Q85] 数值取整
来源：http://dali.jianghu66.top/Article/details/gtrukvrasz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shuidangran.top/Article/details/gtxcfabmxg.html

[Q86] 读取 JSON 字段
来源：http://dali.ybcxt.top/Article/details/gtwufwwvzm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.feifeiyinyue.top/Article/details/gtxyynfuty.html

[Q87] JSON 字段做条件
来源：http://dali.vqdsnc.cn/Article/details/gtrbpbxlus.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cqqwz.cn/Article/details/gtspxbxutu.html

[Q88] 行转列（条件聚合）
来源：http://dali.cdnleiting.top/Article/details/gtbzvzszka.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gtwvqvguyz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjyteevyf.html

[Q89] 判断表是否存在
来源：http://dali.smart0.xyz/Article/details/gtusqplxsd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shuidangran.top/Article/details/gtpcgqhptz.html

[Q90] 生成序号列
来源：http://dali.c1oappe.top/Article/details/gtvnkiuveh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangdashe.top/Article/details/gtweoywbnv.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gttieqhsfn.html

R. Bash 专题
来源：http://dali.yueranfly.top/Article/details/gtxlvbaovv.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtklzveacj.html

[R01] shebang 与严格模式
来源：http://dali.cucudq.cn/Article/details/gtypxhfpwi.html

#!/usr/bin/env bash
来源：http://dali.chenjidiqi.icu/Article/details/gtekychkvr.html

set -euo pipefail
来源：http://dali.zhongyouzk.top/Article/details/gtjzgacxan.html

[R02] 变量赋值与使用
来源：http://dali.redwolf501.top/Article/details/gteghfljsi.html

name="Tom"; echo "$name"
来源：http://dali.tanke756.top/Article/details/gtsxfgakfh.html

[R03] 只读变量
来源：http://dali.quarkkingdee.top/Article/details/gtktiumble.html

readonly PI=3.14
来源：http://dali.pengpengdd.cyou/Article/details/gtflzjnmcl.html

[R04] 位置参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznnpnhcj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hongshengwenyu.top/Article/details/gtdrqnpblz.html

[R05] 参数默认值
来源：http://dali.guannengcc.top/Article/details/gtfreqknxd.html

name="${1:-default}"
来源：http://dali.ppjwa.cn/Article/details/gthigeipjz.html

[R06] 判断命令是否存在
来源：http://dali.aibaodan.cn/Article/details/gtztkzfmpj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sysykeji.top/Article/details/gtlmsiextd.html

[R07] if 判断文件
来源：http://dali.xuetiantiany.cn/Article/details/gtzebrhhaq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtrfuvxczh.html

[R08] 数值比较
来源：http://dali.yanxiufei.cn/Article/details/gtvkmuuurm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shzxlz.cn/Article/details/gtgqcqvwfq.html

[R09] 字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gtrfruamxj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.bjfxy.top/Article/details/gtfpqgsqil.html

[R10] 正则匹配
来源：http://dali.zhongyouzk.top/Article/details/gtdkgicxmy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtdqtrvjjn.html

[R11] case 多分支
来源：http://dali.meibo888.top/Article/details/gtcblendjh.html

case "$1" in
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzbygzjv.html

start) echo "启动" ;;
来源：http://dali.tanke756.top/Article/details/gtyqatacfl.html

stop)  echo "停止" ;;
来源：http://dali.cashguo.top/Article/details/gtnpccingu.html

*)     echo "未知命令" ;;
来源：http://dali.yueranfly.top/Article/details/gtkseooyrk.html

esac
来源：http://dali.yj20258.top/Article/details/gtfysmhpnq.html

[R12] for 遍历文件
来源：http://dali.guannengcc.top/Article/details/gtltswhhmy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvwgpnir.html

[R13] for 计数循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvmkyait.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gtbueiifwm.html

[R14] C 风格 for
来源：http://dali.316326.xyz/Article/details/gtkctlagct.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gtoybdxjdk.html

[R15] while 逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtxwfqwijp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtevssslru.html

[R16] until 等待条件
来源：http://dali.sweek.top/Article/details/gtxnjzvkxj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gtfphjpiro.html

[R17] 数组定义与取值
来源：http://dali.ppjwa.cn/Article/details/gtddfkqjha.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xylfe.cn/Article/details/gtnmqkkhmu.html

[R18] 遍历数组
来源：http://dali.sufxvd.cn/Article/details/gtzuoojcom.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jqgfzy.top/Article/details/gtfqamseoz.html

[R19] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gtsqqmmedp.html

echo "${#arr[@]}"
来源：http://dali.yongpay.top/Article/details/gtmtbzhuez.html

[R20] 关联数组（字典）
来源：http://dali.meibo888.top/Article/details/gtspcnyjfh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gotoacloud.top/Article/details/gtfsxtcteg.html

[R21] 字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gthnjhzzda.html

echo "${#s}"
来源：http://dali.shzxlz.cn/Article/details/gttnhuorfi.html

[R22] 截取子串
来源：http://dali.yj202588.top/Article/details/gtyuldieei.html

echo "${s:0:5}"
来源：http://dali.ydzc1.top/Article/details/gtuzrblcrl.html

[R23] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gtskdyfuub.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hfpthk.cn/Article/details/gtkekfktrp.html

[R24] 大小写转换
来源：http://dali.sweek.top/Article/details/gtthenoblk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aibaodan.cn/Article/details/gtiknkhqfr.html

[R25] 去后缀 / 去前缀
来源：http://dali.dianchejie.cn/Article/details/gtjirdrkpn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ybcxt.top/Article/details/gtjheiilxq.html

[R26] 命令替换
来源：http://dali.havefunace.top/Article/details/gtndzsvocm.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gtxsorptur.html

[R27] 算术展开
来源：http://dali.gaohongyu789.top/Article/details/gtnewuoxpy.html

echo $((1 + 2 * 3))
来源：http://dali.gotoacloud.top/Article/details/gtdhccjdxw.html

[R28] 浮点运算
来源：http://dali.wangdashe.top/Article/details/gtgrtohpgn.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgunwfkn.html

[R29] 定义函数
来源：http://dali.cucudq.cn/Article/details/gtolypqafo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gtphemndmf.html

[R30] 函数返回状态码
来源：http://dali.zycfv.cn/Article/details/gtliukaybk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigfzy.top/Article/details/gttkxrcwof.html

[R31] 局部变量
来源：http://dali.hysaishi.cn/Article/details/gtzsoynxio.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtybxhlavr.html

[R32] 参数个数校验
来源：http://dali.dianchejie.cn/Article/details/gtgmlhpciq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gtbunnuwde.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gtwijscglg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnymzdnwp.html

[R34] 退出时清理
来源：http://dali.jinqigfzy.top/Article/details/gtplqdrtfy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenlongwang.top/Article/details/gtblyvceaq.html

[R35] 后台执行并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdzxquwj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ydzc1.top/Article/details/gttyewqyii.html

[R36] 并发执行多个任务
来源：http://dali.jqgfzy.top/Article/details/gtywexgptt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ydzc1.top/Article/details/gtwlfitfcq.html

[R37] 把输出赋给变量
来源：http://dali.redwolf501.top/Article/details/gtauyfmywv.html

files=$(ls -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtbuvpkzqm.html

[R38] 管道串联
来源：http://dali.shuidangran.top/Article/details/gtlnygazak.html

cat a.txt | grep -i error | wc -l
来源：http://dali.9152youxi.cn/Article/details/gtdrxpzriw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgggugvmr.html

cmd > out.log 2>&1
来源：http://dali.sweek.top/Article/details/gtirzeoimx.html

[R40] 追加写日志
来源：http://dali.aibaodan.cn/Article/details/gtobjauudd.html

echo "log" >> out.log
来源：http://dali.hfpthk.cn/Article/details/gtzlagvljs.html

[R41] 丢弃输出
来源：http://dali.hongshengwenyu.top/Article/details/gtaxrkvaci.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258.top/Article/details/gtlkfhblww.html

[R42] 输入重定向
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbfntvel.html

wc -l < a.txt
来源：http://dali.hywenlv.cn/Article/details/gtfgpoiexi.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gtucqihpym.html

find . -name "*.log" -type f
来源：http://dali.ydzc1.top/Article/details/gtmgcdqjqh.html

[R44] 按修改时间查找
来源：http://dali.chenzaomai.com/Article/details/gtrkmhcrzm.html

find . -mtime -7 -type f
来源：http://dali.cucudq.cn/Article/details/gtxtdnoupi.html

[R45] 批量删除
来源：http://dali.svipenyu.cn/Article/details/gtkgbblvub.html

find . -name "*.tmp" -delete
来源：http://dali.pycfn.com/Article/details/gtptgxvjdg.html

[R46] 递归替换文件内容
来源：http://dali.0kj1m.cn/Article/details/gtwghnbyxm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yueranfly.top/Article/details/gtqaontmut.html

[R47] sed 单行替换
来源：http://dali.yonumen.top/Article/details/gtkwiebbjy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cucudq.cn/Article/details/gttjlqtvkt.html

[R48] awk 取指定列
来源：http://dali.snrcjt.cn/Article/details/gtbgkkcbms.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtksxuziia.html

[R49] awk 带条件
来源：http://dali.chenzaomai.com/Article/details/gtprnnddlh.html


<!-- 参考信息 -->