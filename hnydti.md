代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenlongwang.top/Article/details/gtlfjxadvh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuetiantiany.cn/Article/details/gttcwuqamy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zdqjudy.top/Article/details/gtffthjfjj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jianghu66.top/Article/details/gtiasiwyly.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jianghu66.top/Article/details/gtterplqxc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigufen.top/Article/details/gtavcmzkpq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ybcxt.top/Article/details/gtfeioymzu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.c1oappe.top/Article/details/gtghphsitu.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtkydydvuo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.andypj.xyz/Article/details/gtfpcjtgii.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtcjmpbhqx.html

[Q01] 创建表
来源：http://dali.gotoacloud.top/Article/details/gthhqnryll.html

CREATE TABLE users (
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybjlzrcw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ybcxt.top/Article/details/gtoxqxzjaw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gtorvfwmtv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.guowangkeji.top/Article/details/gtmmtezdao.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258.top/Article/details/gtqfnbvstr.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gtmhaamxdq.html

[Q02] 创建带外键的表
来源：http://dali.tian-w.cn/Article/details/gtykxzquwk.html

CREATE TABLE orders (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrbvdyhc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gtyfbsxrsd.html

user_id INT NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gtdhvwghtm.html

amount DECIMAL(10, 2),
来源：http://dali.zhongyouzk.top/Article/details/gtisvawdsy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fengsongda.top/Article/details/gterpfmhfv.html

);
来源：http://dali.bjfxy.top/Article/details/gtftghxykr.html

[Q03] 增加列
来源：http://dali.redwolf501.top/Article/details/gtrjirkksj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.aizwys.cn/Article/details/gtvqklxyqt.html

[Q04] 修改列类型
来源：http://dali.zhixingplan.top/Article/details/gtceylvkre.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgufenzy.top/Article/details/gtksnhiofu.html

[Q05] 重命名列
来源：http://dali.xuetiantiany.cn/Article/details/gthksgngop.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gogol.net.cn/Article/details/gtlnpbtbby.html

[Q06] 删除列
来源：http://dali.quarkkingdee.top/Article/details/gtfodqjzir.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhixingplan.top/Article/details/gtmsfmzvnt.html

[Q07] 删除表
来源：http://dali.xuanzx.com/Article/details/gtpwznuoax.html

DROP TABLE IF EXISTS orders;
来源：http://dali.haohaochexian.top/Article/details/gtehpxvghr.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gtuicnmioi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gtnnhnhrvc.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gtfywzsmvm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gtzhpawkuq.html

[Q10] 插入单行
来源：http://dali.shuidangran.top/Article/details/gtmetbengw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.mhx1999.top/Article/details/gtqihrbdbn.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gtqqataauk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtyupqrlzf.html

[Q12] 插入后取自增 ID
来源：http://dali.0kj1m.cn/Article/details/gtxrtenocl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangshuangyany.cn/Article/details/gtwtwuxeks.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.vqdsnc.cn/Article/details/gtzxrbtvtd.html

[Q13] 忽略重复插入
来源：http://dali.c1oappe.top/Article/details/gtuyzitakh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gtsnohcnxh.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj20258.top/Article/details/gtxvobwmkj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.bjfxy.top/Article/details/gtzvfzvlmr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hysaishi.cn/Article/details/gttpigtcab.html

[Q15] 查询全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlagdofl.html

SELECT * FROM users;
来源：http://dali.cucudq.cn/Article/details/gtxsnzcwob.html

[Q16] 查询指定列
来源：http://dali.jlsjyb.cn/Article/details/gtinkxbtlk.html

SELECT id, name FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtbwjvzoik.html

[Q17] 条件查询
来源：http://dali.zdqjudy.top/Article/details/gtobzoenyf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pycfn.com/Article/details/gtxzrvycxa.html

[Q18] 模糊匹配
来源：http://dali.kuanghao11.cn/Article/details/gtsrluejwh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ehwqpu.com/Article/details/gtfvgaenrc.html

[Q19] 范围查询
来源：http://dali.0kj1m.cn/Article/details/gtpldnczyl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shuidangran.top/Article/details/gtizleufak.html

[Q20] IN 列表
来源：http://dali.aizwys.cn/Article/details/gtgmvxigls.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuxming.cn/Article/details/gtnlxmpctf.html

[Q21] 空值判断
来源：http://dali.yvedp.cn/Article/details/gtblkffoqg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fzhhl.top/Article/details/gtebgvpdac.html

[Q22] 排序
来源：http://dali.nanxuanxn.top/Article/details/gtmpuyqflb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinghuilouyu.cn/Article/details/gtintunvsb.html

[Q23] 分页
来源：http://dali.jinqigufen.top/Article/details/gtopzkzeoi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuanzx.com/Article/details/gtogcquwki.html

[Q24] 去重
来源：http://dali.sweek.top/Article/details/gtrpgzxyhm.html

SELECT DISTINCT city FROM users;
来源：http://dali.gzhubu.top/Article/details/gtrmsrkwxl.html

[Q25] 只取前 N 条
来源：http://dali.yueranfly.top/Article/details/gtgulomaat.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenjidiqi.icu/Article/details/gtupvaufta.html

[Q26] 计数
来源：http://dali.svipenyu.cn/Article/details/gtvadahjek.html

SELECT COUNT(*) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtmcbsvsne.html

[Q27] 条件计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydgczfnt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtklquhloj.html

[Q28] 求和与平均
来源：http://dali.andypj.xyz/Article/details/gtmctgqjbc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtkatcvzub.html

[Q29] 最大最小值
来源：http://dali.jianghu66.top/Article/details/gthpcvzsym.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtifabqaii.html

[Q30] 分组统计
来源：http://dali.shzxlz.cn/Article/details/gtidzgrpcz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtduczuhnz.html

[Q31] 分组后过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtahsmoufk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ybcxt.top/Article/details/gtuyhlbogx.html

[Q32] 分组拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtceiviuds.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtungoynic.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hysaishi.cn/Article/details/gtwmrpwuqk.html

[Q33] 多列分组
来源：http://dali.hfpthk.cn/Article/details/gthrrcxwmk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hysaishi.cn/Article/details/gteemmwqvv.html

[Q34] 每组取第一条
来源：http://dali.316326.xyz/Article/details/gtceekuruj.html

SELECT * FROM (
来源：http://dali.havefunace.top/Article/details/gtyhzxodnw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigfzy.top/Article/details/gtvnkgphzz.html

) t WHERE rn = 1;
来源：http://dali.nwbrower.top/Article/details/gtxvzsxquk.html

[Q35] 内连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabwzejqn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibavoxlk.html

[Q36] 左连接
来源：http://dali.smart0.xyz/Article/details/gtnyxaycpi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtzndwpmyk.html

[Q37] 右连接
来源：http://dali.fengsongda.top/Article/details/gtordfbdtk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjirumvxf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.dashuyun.cn/Article/details/gtuazlquts.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fengsongda.top/Article/details/gtqiqmpoxg.html

[Q39] 自连接（查上下级）
来源：http://dali.hammf.cn/Article/details/gtrqkcknpj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgfzy.top/Article/details/gtsqavrejf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ivvv.top/Article/details/gtrvpffrwz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.iojbl.cn/Article/details/gtcdlofmjr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dianchejie.cn/Article/details/gtrlemleky.html

[Q41] 多表连接
来源：http://dali.shuidangran.top/Article/details/gtipddrosz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj202588.top/Article/details/gtxswqljwv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hywenlv.cn/Article/details/gthjoiukry.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nwbrower.top/Article/details/gtwhhaxibb.html

[Q42] 连接条件附加过滤
来源：http://dali.quarkkingdee.top/Article/details/gtfetaqgii.html

SELECT u.name, o.amount FROM users u
来源：http://dali.mhx1999.top/Article/details/gtrqaosgcd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yanxiufei.cn/Article/details/gtjliwqnuv.html

[Q43] 标量子查询
来源：http://dali.guannengcc.top/Article/details/gtehcnmwmd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cheryme.top/Article/details/gtixmflfcq.html

[Q44] IN 子查询
来源：http://dali.haohaochexian.top/Article/details/gtgxvmvwzd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fengsongda.top/Article/details/gtvnqlhspg.html

[Q45] EXISTS 判断存在
来源：http://dali.hnqzz.top/Article/details/gtdmppgelg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gtudjblxcd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shzxlz.cn/Article/details/gtwtllsxdk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gtpsocwrmy.html

[Q47] 与平均值比较
来源：http://dali.fengsongda.top/Article/details/gtaulvrvom.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.316326.xyz/Article/details/gtmcxhkorm.html

[Q48] CTE 公用表表达式
来源：http://dali.sufxvd.cn/Article/details/gtkvcbocld.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shangyingyoupin.top/Article/details/gtpggeoacp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pycfn.com/Article/details/gtqhijcbar.html

[Q49] 更新单行
来源：http://dali.dashuyun.cn/Article/details/gtmidlkmdg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtljrgbzam.html

[Q50] 批量更新
来源：http://dali.xziqi.cn/Article/details/gtbxvzijmz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gtcffngyfp.html

[Q51] 用子查询更新
来源：http://dali.ppjwa.cn/Article/details/gtuumnnmtg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gzhubu.top/Article/details/gtqhrqcabo.html

[Q52] 删除指定行
来源：http://dali.cucudq.cn/Article/details/gtzetvhuvh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.snrcjt.cn/Article/details/gtsikuuego.html

[Q53] 按条件删除
来源：http://dali.pycfn.com/Article/details/gtoqghomdj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqddxlrp.html

[Q54] 清空表
来源：http://dali.haohaochexian.top/Article/details/gtcrkvqnsr.html

TRUNCATE TABLE logs;
来源：http://dali.tanke756.top/Article/details/gtagaloukt.html

[Q55] 排名（并列占位）
来源：http://dali.xuanzx.com/Article/details/gtvnnevvff.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yongpay.top/Article/details/gthfwcpnhi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgfzy.top/Article/details/gtbdxrqhkf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gtribcudow.html

[Q57] 行号
来源：http://dali.hysaishi.cn/Article/details/gttonxpfhk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gtbninoqit.html

[Q58] 累计求和
来源：http://dali.yueranfly.top/Article/details/gtszubdmok.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.birdmap.top/Article/details/gthsgehoze.html

[Q59] 分组内累计
来源：http://dali.nanxuanxn.top/Article/details/gtbdorffom.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtzoktowog.html

[Q60] 取上一行 / 下一行
来源：http://dali.havefunace.top/Article/details/gtpovcqlsz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.andypj.xyz/Article/details/gtggyqvnkq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cheryme.top/Article/details/gtunbcpijc.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gtaumnfrva.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtfhjibaog.html

[Q62] 分组占比
来源：http://dali.yvedp.cn/Article/details/gtlxhavpka.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gtnuffytkt.html

[Q63] 开启事务
来源：http://dali.snrcjt.cn/Article/details/gtaxkauhbl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xziqi.cn/Article/details/gtwrshcunr.html

[Q64] 提交事务
来源：http://dali.ppjwa.cn/Article/details/gtdccdogaa.html

COMMIT;
来源：http://dali.zhixingplan.top/Article/details/gtkmafdtbr.html

[Q65] 回滚事务
来源：http://dali.nanxuanxn.top/Article/details/gtfqwlvoma.html

ROLLBACK;
来源：http://dali.shangyingyoupin.top/Article/details/gtebpxlpmw.html

[Q66] 行锁查询
来源：http://dali.hammf.cn/Article/details/gteowijjbr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gzhubu.top/Article/details/gtbtlqjwas.html

[Q67] 设置隔离级别
来源：http://dali.shzxlz.cn/Article/details/gtwlagwuef.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ydzc1.top/Article/details/gtpdrixpwd.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gtplzpxizm.html

SAVEPOINT sp1;
来源：http://dali.gzhubu.top/Article/details/gthtibitan.html

ROLLBACK TO sp1;
来源：http://dali.tian-w.cn/Article/details/gtbteqyitv.html

[Q69] 查看执行计划
来源：http://dali.0kj1m.cn/Article/details/gtjzcbafce.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.andypj.xyz/Article/details/gthlkmuhap.html

[Q70] 更新统计信息
来源：http://dali.hnqzz.top/Article/details/gtdtpglovt.html

ANALYZE TABLE users;
来源：http://dali.cashguo.top/Article/details/gtrzpmltas.html

[Q71] 查看建表语句
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadsjdury.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zdqjudy.top/Article/details/gtqwosdcok.html

[Q72] 查看索引
来源：http://dali.sweek.top/Article/details/gtpfrzbswu.html

SHOW INDEX FROM users;
来源：http://dali.wangdashe.top/Article/details/gtzgazoucw.html

[Q73] 查看表状态
来源：http://dali.hysaishi.cn/Article/details/gtitaccfak.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yonumen.top/Article/details/gtoyqkzxhi.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtadpwexmy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinghuilouyu.cn/Article/details/gttpzjwafo.html

[Q75] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gtcletnnag.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtuctelgzj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangshuangyany.cn/Article/details/gtrewbwamm.html

[Q76] 按天统计
来源：http://dali.zhixingplan.top/Article/details/gtudbbouxg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yonumen.top/Article/details/gtvjwlysei.html

[Q77] 时间加减
来源：http://dali.birdmap.top/Article/details/gtgemupphf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jlsjyb.cn/Article/details/gtdvnitrok.html

[Q78] 当前时间
来源：http://dali.yj202588.top/Article/details/gtlximofuc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sysykeji.top/Article/details/gtuecuwcvr.html

[Q79] 字符串拼接
来源：http://dali.cashguo.top/Article/details/gtcuiqxmnw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sufxvd.cn/Article/details/gtiupzfktg.html

[Q80] 字符串截取
来源：http://dali.ivvv.top/Article/details/gtisifsjox.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtelwkfcvh.html

[Q81] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gtcuxfpive.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtpuoizqmc.html

[Q82] 字符长度与字节长度
来源：http://dali.bjfxy.top/Article/details/gtnzbyiurq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtrrprlbhp.html

[Q83] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtvhduispa.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtccukvicl.html

[Q84] 去除首尾空格
来源：http://dali.shuidangran.top/Article/details/gtxevvqlim.html

SELECT TRIM(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtlzqvpznl.html

[Q85] 数值取整
来源：http://dali.cdnleiting.top/Article/details/gteevenkxh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cqqwz.cn/Article/details/gtshtmwkqj.html

[Q86] 读取 JSON 字段
来源：http://dali.jlsjyb.cn/Article/details/gtrmdayvrb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigufen.top/Article/details/gtxbnlirek.html

[Q87] JSON 字段做条件
来源：http://dali.jyoumei.cn/Article/details/gtqxaqljiw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.svipenyu.cn/Article/details/gtwlyionzs.html

[Q88] 行转列（条件聚合）
来源：http://dali.tanke756.top/Article/details/gtdwqqyilg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.316326.xyz/Article/details/gtejotjtml.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtvgsgixkw.html

[Q89] 判断表是否存在
来源：http://dali.mhx1999.top/Article/details/gtyxuqdris.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxuanxn.top/Article/details/gtpdvbmntx.html

[Q90] 生成序号列
来源：http://dali.haohaochexian.top/Article/details/gtafhnjbrr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guowangkeji.top/Article/details/gtbghkgohu.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtsiosmrdj.html

R. Bash 专题
来源：http://dali.sxryk.cn/Article/details/gtsevvfxnr.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtigmhxrnv.html

[R01] shebang 与严格模式
来源：http://dali.316326.xyz/Article/details/gtwobgwehz.html

#!/usr/bin/env bash
来源：http://dali.svipenyu.cn/Article/details/gttuqbimcn.html

set -euo pipefail
来源：http://dali.sysykeji.top/Article/details/gtnemvirmh.html

[R02] 变量赋值与使用
来源：http://dali.jinqigufen.top/Article/details/gtccobibfl.html

name="Tom"; echo "$name"
来源：http://dali.gogol.net.cn/Article/details/gtodbjryjc.html

[R03] 只读变量
来源：http://dali.quarkkingdee.top/Article/details/gtryiabghj.html

readonly PI=3.14
来源：http://dali.cqqwz.cn/Article/details/gtqolfsjyf.html

[R04] 位置参数
来源：http://dali.zycfv.cn/Article/details/gtlzhblesw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigfzy.top/Article/details/gtwzfckbwd.html

[R05] 参数默认值
来源：http://dali.jiagoushi.top/Article/details/gtisgavdye.html

name="${1:-default}"
来源：http://dali.zdqjudy.top/Article/details/gtmajurgfl.html

[R06] 判断命令是否存在
来源：http://dali.daxiang520.top/Article/details/gttadleckr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.meibo888.top/Article/details/gtywzpzgfa.html

[R07] if 判断文件
来源：http://dali.jinqigfzy.top/Article/details/gtjdnouurk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258888.top/Article/details/gtuwkwjkgd.html

[R08] 数值比较
来源：http://dali.pycfn.com/Article/details/gtbvabcvcv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zdqjudy.top/Article/details/gtyyanyzee.html

[R09] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtmhewrbyh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtkzfifssl.html

[R10] 正则匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtcprlrlyc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.mhx1999.top/Article/details/gtwrwdpwtr.html

[R11] case 多分支
来源：http://dali.hnxiangtu.top/Article/details/gtlouizlsb.html

case "$1" in
来源：http://dali.cheryme.top/Article/details/gtietjljiz.html

start) echo "启动" ;;
来源：http://dali.yangfankeji.com/Article/details/gtkqagqnyx.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtqsbdtynx.html

*)     echo "未知命令" ;;
来源：http://dali.gzhubu.top/Article/details/gtwgotszsa.html

esac
来源：http://dali.jinqigufen.top/Article/details/gtycwskbhx.html

[R12] for 遍历文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxtalnlq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuanzx.com/Article/details/gteaitbfwz.html

[R13] for 计数循环
来源：http://dali.vqdsnc.cn/Article/details/gtsqzmoqrm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gtmtjjgslj.html

[R14] C 风格 for
来源：http://dali.ydzc1.top/Article/details/gtlgktypfy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gttqmtmrwp.html

[R15] while 逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtzwqaqmqc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tanke756.top/Article/details/gtuwhjfkfl.html

[R16] until 等待条件
来源：http://dali.daria6918.cn/Article/details/gtvcwbncov.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gtrikjluqj.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gtivliqork.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj202588.top/Article/details/gtklwzktlr.html

[R18] 遍历数组
来源：http://dali.snrcjt.cn/Article/details/gtbufwtjcn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.andypj.xyz/Article/details/gtnbumqcgc.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gtencuqabp.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjapdecyn.html

[R20] 关联数组（字典）
来源：http://dali.yueranfly.top/Article/details/gtvmoacihe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.redwolf501.top/Article/details/gtazrdkirc.html

[R21] 字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdezulqkp.html

echo "${#s}"
来源：http://dali.cucudq.cn/Article/details/gtiadtmifk.html

[R22] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gttyhyjvej.html

echo "${s:0:5}"
来源：http://dali.jiagoushi.top/Article/details/gtborxxoty.html

[R23] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gthkptgkha.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenzaomai.com/Article/details/gtizoyagfv.html

[R24] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtzusxttjk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.bjfxy.top/Article/details/gttvjtbyfm.html

[R25] 去后缀 / 去前缀
来源：http://dali.sufxvd.cn/Article/details/gttojilucd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.0kj1m.cn/Article/details/gtozuxopnw.html

[R26] 命令替换
来源：http://dali.jinqigfzy.top/Article/details/gtoymylbyz.html

now=$(date +%F); echo "$now"
来源：http://dali.ivvv.top/Article/details/gtdvxvobpo.html

[R27] 算术展开
来源：http://dali.sxryk.cn/Article/details/gthvdthrkq.html

echo $((1 + 2 * 3))
来源：http://dali.yangfankeji.com/Article/details/gtwrcbuaaj.html

[R28] 浮点运算
来源：http://dali.yuanzhike.top/Article/details/gtywtkjegg.html

echo "scale=2; 10/3" | bc
来源：http://dali.yongpay.top/Article/details/gtzaonulhm.html

[R29] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gtkfptxjqo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ydzc1.top/Article/details/gtazpxwwye.html

[R30] 函数返回状态码
来源：http://dali.redwolf501.top/Article/details/gtqbfxhwhb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhiwuduotai.top/Article/details/gtuxlpsuir.html

[R31] 局部变量
来源：http://dali.hfpthk.cn/Article/details/gtjsnhrbic.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhoulong.xyz/Article/details/gtnxcextga.html

[R32] 参数个数校验
来源：http://dali.jinqigfzy.top/Article/details/gteaghwrsn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtlacdmwye.html

[R33] 捕获错误并提示行号
来源：http://dali.sxryk.cn/Article/details/gtfiyoiyfp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenlongwang.top/Article/details/gtbpczbipv.html

[R34] 退出时清理
来源：http://dali.nanxinkj.top/Article/details/gtbtjmrlgf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gtdfiihbhx.html

[R35] 后台执行并等待
来源：http://dali.tian-w.cn/Article/details/gtroldbwwi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgufenzy.top/Article/details/gtbnfahuuz.html

[R36] 并发执行多个任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvghlecie.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pycfn.com/Article/details/gtrbvmagyv.html

[R37] 把输出赋给变量
来源：http://dali.zhongyouzk.top/Article/details/gtxscfqmcv.html

files=$(ls -1)
来源：http://dali.zhoulong.xyz/Article/details/gtcefmlcrp.html

[R38] 管道串联
来源：http://dali.havefunace.top/Article/details/gtuaktobqx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ybcxt.top/Article/details/gtittlcnql.html

[R39] 重定向标准输出与错误
来源：http://dali.dashuyun.cn/Article/details/gtvxgzshbs.html


<!-- 参考信息 -->