代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.smart0.xyz/Article/details/gthwuccooz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.mhx1999.top/Article/details/gtetzwoepm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yueranfly.top/Article/details/gtyfhjdjbf.html

[P08] 处理浮点精度问题
来源：http://dali.jqgfzy.top/Article/details/gtjoowbiop.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.bjfxy.top/Article/details/gtibbcyysg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.andypj.xyz/Article/details/gtozcmicea.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gogol.net.cn/Article/details/gtttmrjhdz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvzrbfce.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tian-w.cn/Article/details/gtnxcoojjn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shuidangran.top/Article/details/gtimzachky.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yongpay.top/Article/details/gtjchxbuwd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.snrcjt.cn/Article/details/gtjbsegpbc.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtshyxwqya.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258.top/Article/details/gtudpipbqd.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtnsyaqqqi.html

[Q01] 创建表
来源：http://dali.tian-w.cn/Article/details/gtlczjwepd.html

CREATE TABLE users (
来源：http://dali.vqdsnc.cn/Article/details/gtqirfcifw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gtveeyccki.html

name VARCHAR(50) NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gtrzqoucmc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xuanzx.com/Article/details/gtujmhhqwn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jyoumei.cn/Article/details/gtkioloyqs.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsywzqmxd.html

[Q02] 创建带外键的表
来源：http://dali.ppjwa.cn/Article/details/gtwaquzydw.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gtoyoncvec.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gtougojcli.html

user_id INT NOT NULL,
来源：http://dali.tanke756.top/Article/details/gthoccruwt.html

amount DECIMAL(10, 2),
来源：http://dali.nwbrower.top/Article/details/gtkgltsoto.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangdashe.top/Article/details/gtsbglnltm.html

);
来源：http://dali.cashguo.top/Article/details/gtndyuzzhn.html

[Q03] 增加列
来源：http://dali.nanxinkj.top/Article/details/gtpxczmrfr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.smart0.xyz/Article/details/gtpzevyzuf.html

[Q04] 修改列类型
来源：http://dali.aibaodan.cn/Article/details/gtixgfqxwh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhoulong.xyz/Article/details/gtribcjzvx.html

[Q05] 重命名列
来源：http://dali.sysykeji.top/Article/details/gtponevqkc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cdnleiting.top/Article/details/gtrtgdcrob.html

[Q06] 删除列
来源：http://dali.jinqigfzy.top/Article/details/gtkgjnplae.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.svipenyu.cn/Article/details/gtxsiqfqid.html

[Q07] 删除表
来源：http://dali.havefunace.top/Article/details/gtuydhmdvv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fzhhl.top/Article/details/gtxytjuigr.html

[Q08] 创建普通索引
来源：http://dali.yanxiufei.cn/Article/details/gteydcddsr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ivvv.top/Article/details/gtzvqhjcdn.html

[Q09] 创建唯一索引
来源：http://dali.sufxvd.cn/Article/details/gtmnyhuwht.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gtveftjodi.html

[Q10] 插入单行
来源：http://dali.yuxming.cn/Article/details/gtnzrxyzfj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnocckdto.html

[Q11] 一次插入多行
来源：http://dali.zhoulong.xyz/Article/details/gtxcvtnsmv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtveofwnux.html

[Q12] 插入后取自增 ID
来源：http://dali.pengpengdd.cyou/Article/details/gtcrcbhgyg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.daxiang520.top/Article/details/gtczfbydsc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jlsjyb.cn/Article/details/gtlzqnbzsr.html

[Q13] 忽略重复插入
来源：http://dali.wangshuangyany.cn/Article/details/gtzcrjwrhi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daria6918.cn/Article/details/gtfpltkuam.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj202588.top/Article/details/gtuyzovznu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ppjwa.cn/Article/details/gtkxiuorgl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xylfe.cn/Article/details/gtzlazfeck.html

[Q15] 查询全部
来源：http://dali.yj202588.top/Article/details/gtuowclrwq.html

SELECT * FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtrkuuqkay.html

[Q16] 查询指定列
来源：http://dali.ehwqpu.com/Article/details/gtejgghyoo.html

SELECT id, name FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtlbtroavg.html

[Q17] 条件查询
来源：http://dali.9152youxi.cn/Article/details/gtewdpfopl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtggirfmju.html

[Q18] 模糊匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtswlkcvna.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.guowangkeji.top/Article/details/gtkhzsruww.html

[Q19] 范围查询
来源：http://dali.dashuyun.cn/Article/details/gtsjkaveuu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pycfn.com/Article/details/gtnewsmhqe.html

[Q20] IN 列表
来源：http://dali.nanxuanxn.top/Article/details/gtdmkegoai.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yueranfly.top/Article/details/gtkogbzaav.html

[Q21] 空值判断
来源：http://dali.dashuyun.cn/Article/details/gtqmblcpbf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.birdmap.top/Article/details/gtxtphwrjr.html

[Q22] 排序
来源：http://dali.meibo888.top/Article/details/gthiigucse.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ivvv.top/Article/details/gtteifgsgw.html

[Q23] 分页
来源：http://dali.hfpthk.cn/Article/details/gtdurxhjdf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gtpqsgobfs.html

[Q24] 去重
来源：http://dali.yj202588.top/Article/details/gtvzydjrcl.html

SELECT DISTINCT city FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtcwzyutom.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxaywlsg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cucudq.cn/Article/details/gtpqztxhpc.html

[Q26] 计数
来源：http://dali.jianghu66.top/Article/details/gtudtaiuuc.html

SELECT COUNT(*) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtolocdtxe.html

[Q27] 条件计数
来源：http://dali.zdqjudy.top/Article/details/gtqwoaench.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cucudq.cn/Article/details/gtqxxhzooj.html

[Q28] 求和与平均
来源：http://dali.aizwys.cn/Article/details/gtbvypcgle.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtleegpdul.html

[Q29] 最大最小值
来源：http://dali.zhoulong.xyz/Article/details/gtfqppooya.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtwwcxvfzq.html

[Q30] 分组统计
来源：http://dali.xziqi.cn/Article/details/gtdiqihfnb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtfenqifma.html

[Q31] 分组后过滤
来源：http://dali.cdnleiting.top/Article/details/gtxnpupbnf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cashguo.top/Article/details/gteuzqawhh.html

[Q32] 分组拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtjjyptoxd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtlygdwspo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangshuangyany.cn/Article/details/gtqskrphst.html

[Q33] 多列分组
来源：http://dali.vqdsnc.cn/Article/details/gtdxjbobeb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guannengcc.top/Article/details/gtuuqumeth.html

[Q34] 每组取第一条
来源：http://dali.ppjwa.cn/Article/details/gtbegbzbws.html

SELECT * FROM (
来源：http://dali.smart0.xyz/Article/details/gtvcktsmss.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhengqikj.top/Article/details/gtxcafygvv.html

) t WHERE rn = 1;
来源：http://dali.fengsongda.top/Article/details/gtneebviyn.html

[Q35] 内连接
来源：http://dali.pycfn.com/Article/details/gtvlqlzsnj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gtprxkwqyc.html

[Q36] 左连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtolajrm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gtzkdudvkd.html

[Q37] 右连接
来源：http://dali.shangyingyoupin.top/Article/details/gtncoqejfj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cqqwz.cn/Article/details/gtlpqusrgz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fengsongda.top/Article/details/gtlurqydtw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.c1oappe.top/Article/details/gtuuxsznsz.html

[Q39] 自连接（查上下级）
来源：http://dali.fzhhl.top/Article/details/gtojmrpngh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.bjfxy.top/Article/details/gtojqbifcd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dashuyun.cn/Article/details/gtmnwsoegd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sysykeji.top/Article/details/gtuhizpozq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfmymluc.html

[Q41] 多表连接
来源：http://dali.yj20258.top/Article/details/gtfdefyqfj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.redwolf501.top/Article/details/gtbcspnfxr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yvedp.cn/Article/details/gtygrymvze.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nwbrower.top/Article/details/gtklnuvlhm.html

[Q42] 连接条件附加过滤
来源：http://dali.gogol.net.cn/Article/details/gtslgmfvbi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jianghu66.top/Article/details/gtjrrgzyzx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yanxiufei.cn/Article/details/gthzvjpujk.html

[Q43] 标量子查询
来源：http://dali.sweek.top/Article/details/gtuqvnnuns.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nanxinkj.top/Article/details/gtodroqsnz.html

[Q44] IN 子查询
来源：http://dali.hywenlv.cn/Article/details/gtataysvqt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ppjwa.cn/Article/details/gtkvjimioe.html

[Q45] EXISTS 判断存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpeftnfcy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gtgukxjarl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhoulong.xyz/Article/details/gthvwpxhmy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gtcwvsnxwx.html

[Q47] 与平均值比较
来源：http://dali.yj20258.top/Article/details/gtymovaoyc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgufenzy.top/Article/details/gtnmtvqvir.html

[Q48] CTE 公用表表达式
来源：http://dali.cdnleiting.top/Article/details/gtpyqjnbzk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.kuanghao11.cn/Article/details/gtlolzvpjq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hfpthk.cn/Article/details/gtbfukewdm.html

[Q49] 更新单行
来源：http://dali.pycfn.com/Article/details/gttifruudt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtllwmmbmo.html

[Q50] 批量更新
来源：http://dali.yj202588.top/Article/details/gtgkaxjjwp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.haohaochexian.top/Article/details/gtirsxeypc.html

[Q51] 用子查询更新
来源：http://dali.quarkkingdee.top/Article/details/gtmwjeztcs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jiagoushi.top/Article/details/gtndqhxnjj.html

[Q52] 删除指定行
来源：http://dali.shangyingyoupin.top/Article/details/gtifofruxx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.0kj1m.cn/Article/details/gteoxwizol.html

[Q53] 按条件删除
来源：http://dali.ppjwa.cn/Article/details/gtosanoxsg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenzaomai.com/Article/details/gtcpudtavv.html

[Q54] 清空表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqdqxpht.html

TRUNCATE TABLE logs;
来源：http://dali.xziqi.cn/Article/details/gtacvrredv.html

[Q55] 排名（并列占位）
来源：http://dali.xuanzx.com/Article/details/gtsujuetbh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.316326.xyz/Article/details/gtybjstccm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhengqikj.top/Article/details/gtropugjof.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ehwqpu.com/Article/details/gtoqustbmv.html

[Q57] 行号
来源：http://dali.smart0.xyz/Article/details/gtyzgbxsvw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyehcuczk.html

[Q58] 累计求和
来源：http://dali.316326.xyz/Article/details/gtxtqlwrwu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtykejlbul.html

[Q59] 分组内累计
来源：http://dali.zycfv.cn/Article/details/gtabkypcav.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhnztvna.html

[Q60] 取上一行 / 下一行
来源：http://dali.ppjwa.cn/Article/details/gtdlwuhkii.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gogol.net.cn/Article/details/gtxfmqpzqv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtqwlxwjxg.html

[Q61] 移动平均
来源：http://dali.wangshuangyany.cn/Article/details/gthpjmirue.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtbxbhtpag.html

[Q62] 分组占比
来源：http://dali.hnqzz.top/Article/details/gtqchmlppg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtldayvmam.html

[Q63] 开启事务
来源：http://dali.ivvv.top/Article/details/gtpfqzvovr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinghuilouyu.cn/Article/details/gtrstkpvva.html

[Q64] 提交事务
来源：http://dali.birdmap.top/Article/details/gtfyuadwsw.html

COMMIT;
来源：http://dali.9152youxi.cn/Article/details/gtyepesukc.html

[Q65] 回滚事务
来源：http://dali.svipenyu.cn/Article/details/gtjxiiznaf.html

ROLLBACK;
来源：http://dali.gzhubu.top/Article/details/gtbfbssakh.html

[Q66] 行锁查询
来源：http://dali.pengpengdd.cyou/Article/details/gtsdkhwzcw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenjidiqi.icu/Article/details/gtuwvgwmef.html

[Q67] 设置隔离级别
来源：http://dali.xuetiantiany.cn/Article/details/gtulttxngu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhixingplan.top/Article/details/gtjpxlsoyg.html

[Q68] 保存点
来源：http://dali.xziqi.cn/Article/details/gtqvxynwlf.html

SAVEPOINT sp1;
来源：http://dali.fengsongda.top/Article/details/gttczzrdxd.html

ROLLBACK TO sp1;
来源：http://dali.aibaodan.cn/Article/details/gthgjygkyo.html

[Q69] 查看执行计划
来源：http://dali.pengpengdd.cyou/Article/details/gtnqbarxja.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.c1oappe.top/Article/details/gtnozakbnc.html

[Q70] 更新统计信息
来源：http://dali.shzxlz.cn/Article/details/gtkafoting.html

ANALYZE TABLE users;
来源：http://dali.jianghu66.top/Article/details/gtnitxwmek.html

[Q71] 查看建表语句
来源：http://dali.wangshuangyany.cn/Article/details/gtwrdiqqnl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hysaishi.cn/Article/details/gtkjtjcezt.html

[Q72] 查看索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqzdocjz.html

SHOW INDEX FROM users;
来源：http://dali.xinyue.icu/Article/details/gteuqbelyo.html

[Q73] 查看表状态
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsvzpqbe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gogol.net.cn/Article/details/gtjwfjrwtn.html

[Q74] 强制使用索引
来源：http://dali.smart0.xyz/Article/details/gtyomzaedl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yueranfly.top/Article/details/gtnrgxjyeg.html

[Q75] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtagmcfsak.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtrkytfruu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yonumen.top/Article/details/gtvvirtpwk.html

[Q76] 按天统计
来源：http://dali.hammf.cn/Article/details/gtoyjhxyiv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gtvtpmybqi.html

[Q77] 时间加减
来源：http://dali.yonumen.top/Article/details/gtctbhnsml.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigufen.top/Article/details/gtdjrryzfs.html

[Q78] 当前时间
来源：http://dali.hywenlv.cn/Article/details/gtwoubzcbo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenzaomai.com/Article/details/gtixqitxoj.html

[Q79] 字符串拼接
来源：http://dali.sweek.top/Article/details/gtltfdzkqw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenzaomai.com/Article/details/gtrbdgetrn.html

[Q80] 字符串截取
来源：http://dali.chenzaomai.com/Article/details/gtronbprbu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtivuhytql.html

[Q81] 字符串替换
来源：http://dali.hammf.cn/Article/details/gtkxxyaofu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.meibo888.top/Article/details/gtgbmgpzez.html

[Q82] 字符长度与字节长度
来源：http://dali.mhx1999.top/Article/details/gthmkollqe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtxqzsicnk.html

[Q83] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtepybdnpc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtkjqxqooi.html

[Q84] 去除首尾空格
来源：http://dali.yonumen.top/Article/details/gtcfzsbrnf.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtvvlcylss.html

[Q85] 数值取整
来源：http://dali.jqgufenzy.top/Article/details/gtcannqrxt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.c1oappe.top/Article/details/gtkdiltthu.html

[Q86] 读取 JSON 字段
来源：http://dali.sufxvd.cn/Article/details/gtvjqynbeo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jlsjyb.cn/Article/details/gtsdhaxjjm.html

[Q87] JSON 字段做条件
来源：http://dali.bjfxy.top/Article/details/gtlzobmvpb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhoulong.xyz/Article/details/gtzucolcka.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhixingplan.top/Article/details/gtmoskkakp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cdnleiting.top/Article/details/gthxxrlxjk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvgllyxt.html

[Q89] 判断表是否存在
来源：http://dali.jqgfzy.top/Article/details/gtfbxyqdmj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cdnleiting.top/Article/details/gtmplfjwwx.html

[Q90] 生成序号列
来源：http://dali.shzxlz.cn/Article/details/gtwgvgimtg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tian-w.cn/Article/details/gtldkqicme.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtechscyhd.html

R. Bash 专题
来源：http://dali.dashuyun.cn/Article/details/gtpnycibvm.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtynuvbxan.html

[R01] shebang 与严格模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebdrnpzw.html

#!/usr/bin/env bash
来源：http://dali.yongpay.top/Article/details/gtmfjeaomx.html

set -euo pipefail
来源：http://dali.tian-w.cn/Article/details/gtsmylnwcb.html

[R02] 变量赋值与使用
来源：http://dali.xylfe.cn/Article/details/gtbwscpobo.html

name="Tom"; echo "$name"
来源：http://dali.gogol.net.cn/Article/details/gtjxcslsim.html

[R03] 只读变量
来源：http://dali.yj202588.top/Article/details/gtiblkcesp.html

readonly PI=3.14
来源：http://dali.shanyushiyangtech.top/Article/details/gtgotwfsir.html

[R04] 位置参数
来源：http://dali.zdqjudy.top/Article/details/gthxlnqbtj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gtyflpxzcl.html

[R05] 参数默认值
来源：http://dali.gogol.net.cn/Article/details/gtwamixkar.html

name="${1:-default}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezjjoxxt.html

[R06] 判断命令是否存在
来源：http://dali.hywenlv.cn/Article/details/gtigzvymlo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gteiovoozc.html

[R07] if 判断文件
来源：http://dali.zycfv.cn/Article/details/gtybvylbao.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtlvrpovfr.html

[R08] 数值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcghxcpwp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258888.top/Article/details/gtveaoqjlx.html

[R09] 字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtqyxdrfqg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.c1oappe.top/Article/details/gtlhzkdhrw.html

[R10] 正则匹配
来源：http://dali.kuanghao11.cn/Article/details/gtwgrjmjdp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cucudq.cn/Article/details/gtgykpryal.html

[R11] case 多分支
来源：http://dali.yvedp.cn/Article/details/gtzoucbehr.html

case "$1" in
来源：http://dali.hnxiangtu.top/Article/details/gtvfcsjdxs.html

start) echo "启动" ;;
来源：http://dali.ehwqpu.com/Article/details/gtyipoarqr.html

stop)  echo "停止" ;;
来源：http://dali.nanxinkj.top/Article/details/gtddvbtspb.html

*)     echo "未知命令" ;;
来源：http://dali.nwbrower.top/Article/details/gtlvgpztew.html

esac
来源：http://dali.svipenyu.cn/Article/details/gtjgsrdrtd.html

[R12] for 遍历文件
来源：http://dali.ydzc1.top/Article/details/gthculmamj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuanzhike.top/Article/details/gtuizpohah.html

[R13] for 计数循环
来源：http://dali.wangshuangyany.cn/Article/details/gtsxxqtsfx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtebuzprtr.html

[R14] C 风格 for
来源：http://dali.0kj1m.cn/Article/details/gtfwtbakfl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtnorbaoqw.html

[R15] while 逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtsgwliazx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnqzz.top/Article/details/gtqanlvxld.html

[R16] until 等待条件
来源：http://dali.ppjwa.cn/Article/details/gtmskhpgvb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gtngkovxkt.html

[R17] 数组定义与取值
来源：http://dali.zdqjudy.top/Article/details/gtblanwgwg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cqqwz.cn/Article/details/gtkpsbaprh.html

[R18] 遍历数组
来源：http://dali.daria6918.cn/Article/details/gtevhrtycf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxuanxn.top/Article/details/gtgovmfhaf.html

[R19] 数组长度
来源：http://dali.yonumen.top/Article/details/gtunwyzmok.html

echo "${#arr[@]}"
来源：http://dali.c1oappe.top/Article/details/gtejgfjyod.html

[R20] 关联数组（字典）
来源：http://dali.jinqigufen.top/Article/details/gtucpgwuas.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangdashe.top/Article/details/gtkxmeasow.html

[R21] 字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gtgapvilib.html

echo "${#s}"
来源：http://dali.yueranfly.top/Article/details/gtyehoysxd.html

[R22] 截取子串
来源：http://dali.yj20258.top/Article/details/gtygdzgflh.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gtvpthilms.html

[R23] 字符串替换
来源：http://dali.yj20258.top/Article/details/gtolczxvxj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfuckxbm.html

[R24] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtfgxsixek.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.havefunace.top/Article/details/gtavbbtlib.html

[R25] 去后缀 / 去前缀
来源：http://dali.dianchejie.cn/Article/details/gtokrjrbye.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fzhhl.top/Article/details/gtvugeshoo.html

[R26] 命令替换
来源：http://dali.hnqzz.top/Article/details/gtuwwupfnr.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gtelrivljb.html

[R27] 算术展开
来源：http://dali.haohaochexian.top/Article/details/gtzhjkgssu.html

echo $((1 + 2 * 3))
来源：http://dali.gogol.net.cn/Article/details/gtnncpptcq.html

[R28] 浮点运算
来源：http://dali.zhiwuduotai.top/Article/details/gtcbrmzocp.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhxmougu.html

[R29] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtkuovasrm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yanxiufei.cn/Article/details/gtqewhvxfw.html

[R30] 函数返回状态码
来源：http://dali.cheryme.top/Article/details/gtzxlkeumg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhixingplan.top/Article/details/gtatgjzrgh.html

[R31] 局部变量
来源：http://dali.cdnleiting.top/Article/details/gtqroltyzv.html

f() { local x=1; echo "$x"; }
来源：http://dali.daria6918.cn/Article/details/gtcwmxumjk.html

[R32] 参数个数校验
来源：http://dali.hfpthk.cn/Article/details/gtmvmkbsyy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gtjsmcczkm.html

[R33] 捕获错误并提示行号
来源：http://dali.meibo888.top/Article/details/gtpfqmfcbd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hfpthk.cn/Article/details/gtitgqpsba.html

[R34] 退出时清理
来源：http://dali.wangdashe.top/Article/details/gtufkogdtq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gtxrmbozah.html

[R35] 后台执行并等待
来源：http://dali.fzhhl.top/Article/details/gtxunsnkzw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aizwys.cn/Article/details/gtyvxieawu.html

[R36] 并发执行多个任务
来源：http://dali.hnqzz.top/Article/details/gtmpaklrfj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.snrcjt.cn/Article/details/gtwvtmajjk.html

[R37] 把输出赋给变量
来源：http://dali.shuidangran.top/Article/details/gtumgncipn.html


<!-- 参考信息 -->