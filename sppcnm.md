代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj202588.top/Article/details/gt2nqqxbtpr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.mhx1999.top/Article/details/gt2tlfgamkq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sysykeji.top/Article/details/gt2konfboeo.html

[P08] 处理浮点精度问题
来源：http://dali.shzxlz.cn/Article/details/gt2hchsegyn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.havefunace.top/Article/details/gt2ktmbgqfa.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cdnleiting.top/Article/details/gt2hbrsqzik.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhengqikj.top/Article/details/gt2xzvcbgue.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gt2ecyuuqbv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sweek.top/Article/details/gt2lxaepkej.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hammf.cn/Article/details/gt2skmcallm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hongshengwenyu.top/Article/details/gt2smnxcihc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.birdmap.top/Article/details/gt2xacierrw.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2ndmbfpnb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ppjwa.cn/Article/details/gt2hopubdgs.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2htymiavn.html

[Q01] 创建表
来源：http://dali.mhx1999.top/Article/details/gt2oxaapbts.html

CREATE TABLE users (
来源：http://dali.snrcjt.cn/Article/details/gt2tglvgbzy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gt2etnqixpf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gt2ynduddfx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nwbrower.top/Article/details/gt2epdnqafl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258888.top/Article/details/gt2jmlerhjx.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zybcbkkg.html

[Q02] 创建带外键的表
来源：http://dali.316326.xyz/Article/details/gt2bvspvirm.html

CREATE TABLE orders (
来源：http://dali.fzhhl.top/Article/details/gt2gnpzfhhn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gt2ododayjb.html

user_id INT NOT NULL,
来源：http://dali.meibo888.top/Article/details/gt2cxnssunf.html

amount DECIMAL(10, 2),
来源：http://dali.chenlongwang.top/Article/details/gt2nigbsyah.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gzhubu.top/Article/details/gt2pjgvqpot.html

);
来源：http://dali.ppjwa.cn/Article/details/gt2wblhkiub.html

[Q03] 增加列
来源：http://dali.nanxuanxn.top/Article/details/gt2zpkzxxrd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gogol.net.cn/Article/details/gt2rznvqlka.html

[Q04] 修改列类型
来源：http://dali.yueranfly.top/Article/details/gt2nxoquuha.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.kuanghao11.cn/Article/details/gt2ogkklbnt.html

[Q05] 重命名列
来源：http://dali.andypj.xyz/Article/details/gt2uiwctspc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jlsjyb.cn/Article/details/gt2yebaqpot.html

[Q06] 删除列
来源：http://dali.chenjidiqi.icu/Article/details/gt2gvrdbqmo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jianghu66.top/Article/details/gt2iuxsdkph.html

[Q07] 删除表
来源：http://dali.sxryk.cn/Article/details/gt2inovtcfq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhixingplan.top/Article/details/gt2ghskjmtf.html

[Q08] 创建普通索引
来源：http://dali.yueranfly.top/Article/details/gt2qbhkrltk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gt2ybeoxcju.html

[Q09] 创建唯一索引
来源：http://dali.cucudq.cn/Article/details/gt2nmclwqzn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gt2exqckxgt.html

[Q10] 插入单行
来源：http://dali.wangdashe.top/Article/details/gt2ffweqpdp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nanxinkj.top/Article/details/gt2hpbhzxfg.html

[Q11] 一次插入多行
来源：http://dali.haohaochexian.top/Article/details/gt2jsfuwnuw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ehwqpu.com/Article/details/gt2haeuslty.html

[Q12] 插入后取自增 ID
来源：http://dali.hfpthk.cn/Article/details/gt2vmgkkmap.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cheryme.top/Article/details/gt2dqtloaap.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.pengpengdd.cyou/Article/details/gt2lfgiicgp.html

[Q13] 忽略重复插入
来源：http://dali.yueranfly.top/Article/details/gt2eiiqavyn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cashguo.top/Article/details/gt2vdclonio.html

[Q14] 存在则更新（upsert）
来源：http://dali.nwbrower.top/Article/details/gt2ocaeqhgj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhixingplan.top/Article/details/gt2aprpjfes.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jianghu66.top/Article/details/gt2wbmtzinm.html

[Q15] 查询全部
来源：http://dali.yongpay.top/Article/details/gt2cqcnenfp.html

SELECT * FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2tjoxhqdu.html

[Q16] 查询指定列
来源：http://dali.zhongyouzk.top/Article/details/gt2xwambatc.html

SELECT id, name FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2ewfevndo.html

[Q17] 条件查询
来源：http://dali.smart0.xyz/Article/details/gt2ohdzibuh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2ituvzjkg.html

[Q18] 模糊匹配
来源：http://dali.xziqi.cn/Article/details/gt2uvpblccn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aibaodan.cn/Article/details/gt2kkucxdtn.html

[Q19] 范围查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2znwlodrk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cucudq.cn/Article/details/gt2wmczynak.html

[Q20] IN 列表
来源：http://dali.xuetiantiany.cn/Article/details/gt2qtdojzkv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tian-w.cn/Article/details/gt2mwyihgdi.html

[Q21] 空值判断
来源：http://dali.gaohongyu789.top/Article/details/gt2wyjqvabp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.c1oappe.top/Article/details/gt2atfhnmgb.html

[Q22] 排序
来源：http://dali.ehwqpu.com/Article/details/gt2byxjdjma.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.vqdsnc.cn/Article/details/gt2jdlkvhjz.html

[Q23] 分页
来源：http://dali.daria6918.cn/Article/details/gt2glgwcfov.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbmnrudb.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzxvprw.html

SELECT DISTINCT city FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2vbaiotet.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2memllvnc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yongpay.top/Article/details/gt2qpzokkya.html

[Q26] 计数
来源：http://dali.birdmap.top/Article/details/gt2sylwqwgq.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2nrzrzamb.html

[Q27] 条件计数
来源：http://dali.yongpay.top/Article/details/gt2autsjfhc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zvajjbvp.html

[Q28] 求和与平均
来源：http://dali.yuanzhike.top/Article/details/gt2mxzrzrue.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2mzsgogfb.html

[Q29] 最大最小值
来源：http://dali.yangfankeji.com/Article/details/gt2zekcbtwr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2jetoxnox.html

[Q30] 分组统计
来源：http://dali.sufxvd.cn/Article/details/gt2sjujryyu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gt2uwuodfrz.html

[Q31] 分组后过滤
来源：http://dali.jqgfzy.top/Article/details/gt2stfkvbtz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.316326.xyz/Article/details/gt2yhufkujr.html

[Q32] 分组拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2wrpzxnye.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gt2udgnmxuj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yangfankeji.com/Article/details/gt2imkufhlx.html

[Q33] 多列分组
来源：http://dali.9152youxi.cn/Article/details/gt2bjaqhism.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hysaishi.cn/Article/details/gt2nsnxnira.html

[Q34] 每组取第一条
来源：http://dali.hammf.cn/Article/details/gt2jrioocnu.html

SELECT * FROM (
来源：http://dali.hywenlv.cn/Article/details/gt2becirbrb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.bjfxy.top/Article/details/gt2uoqnzoal.html

) t WHERE rn = 1;
来源：http://dali.tian-w.cn/Article/details/gt2vomhaxny.html

[Q35] 内连接
来源：http://dali.sysykeji.top/Article/details/gt2qwxwmanb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gt2gfhtubxe.html

[Q36] 左连接
来源：http://dali.jinqigufen.top/Article/details/gt2xymauzwj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgufenzy.top/Article/details/gt2bmsramzk.html

[Q37] 右连接
来源：http://dali.zhixingplan.top/Article/details/gt2edragjri.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.haohaochexian.top/Article/details/gt2lylykidv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj202588.top/Article/details/gt2rriirhdq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulxwghsl.html

[Q39] 自连接（查上下级）
来源：http://dali.yuanzhike.top/Article/details/gt2axdjeztx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenjidiqi.icu/Article/details/gt2rsnpgsbf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwdmzoar.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nanxuanxn.top/Article/details/gt2aaedlpru.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ydzc1.top/Article/details/gt2mxbfwuqr.html

[Q41] 多表连接
来源：http://dali.cqqwz.cn/Article/details/gt2bvaqybwg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.mhx1999.top/Article/details/gt2wdaqbkoe.html

JOIN users u ON u.id = o.user_id
来源：http://dali.kuanghao11.cn/Article/details/gt2dcmredsd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.wangdashe.top/Article/details/gt2hbaqdnjl.html

[Q42] 连接条件附加过滤
来源：http://dali.havefunace.top/Article/details/gt2ayujpjno.html

SELECT u.name, o.amount FROM users u
来源：http://dali.0kj1m.cn/Article/details/gt2cpiedlzz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigfzy.top/Article/details/gt2xhvloawr.html

[Q43] 标量子查询
来源：http://dali.yvedp.cn/Article/details/gt2eqvbupjl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gaohongyu789.top/Article/details/gt2qjgklxrc.html

[Q44] IN 子查询
来源：http://dali.xziqi.cn/Article/details/gt2vguimqdc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnqzz.top/Article/details/gt2tzmllrfy.html

[Q45] EXISTS 判断存在
来源：http://dali.ydzc1.top/Article/details/gt2fwssinzv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gt2cvaxfyvd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sufxvd.cn/Article/details/gt2octbewaq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gt2nbobjlcq.html

[Q47] 与平均值比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2bcuxwuiq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xinyue.icu/Article/details/gt2krffrrde.html

[Q48] CTE 公用表表达式
来源：http://dali.feifeiyinyue.top/Article/details/gt2lsgluaqk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pengpengdd.cyou/Article/details/gt2sgtqngej.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zdqjudy.top/Article/details/gt2mhqiomri.html

[Q49] 更新单行
来源：http://dali.gaohongyu789.top/Article/details/gt2xolzfjzk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gt2zhdecafd.html

[Q50] 批量更新
来源：http://dali.zhongyouzk.top/Article/details/gt2qhjhmqxd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ehwqpu.com/Article/details/gt2stkydypf.html

[Q51] 用子查询更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmxrvjou.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.bjfxy.top/Article/details/gt2sjrblsmm.html

[Q52] 删除指定行
来源：http://dali.vqdsnc.cn/Article/details/gt2dfikmzdx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gt2ofrqthjy.html

[Q53] 按条件删除
来源：http://dali.gogol.net.cn/Article/details/gt2irlcampi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fzhhl.top/Article/details/gt2pfpdlshx.html

[Q54] 清空表
来源：http://dali.yj20258888.top/Article/details/gt2tahywkbq.html

TRUNCATE TABLE logs;
来源：http://dali.yonumen.top/Article/details/gt2wukwvwod.html

[Q55] 排名（并列占位）
来源：http://dali.9152youxi.cn/Article/details/gt2jytetshk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hmqpdspk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.smart0.xyz/Article/details/gt2sgkowhwg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gt2xkdadxnp.html

[Q57] 行号
来源：http://dali.zhoulong.xyz/Article/details/gt2dpcqcfde.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2haxslmgq.html

[Q58] 累计求和
来源：http://dali.hnxiangtu.top/Article/details/gt2fojdnuob.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gt2qxtcvpml.html

[Q59] 分组内累计
来源：http://dali.gogol.net.cn/Article/details/gt2jafsbqtl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2vfenitys.html

[Q60] 取上一行 / 下一行
来源：http://dali.sxryk.cn/Article/details/gt2dnycnlvu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinqigufen.top/Article/details/gt2lnntjaqn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2iwikazts.html

[Q61] 移动平均
来源：http://dali.jqgfzy.top/Article/details/gt2qrydzqfa.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2aqiecpxu.html

[Q62] 分组占比
来源：http://dali.ehwqpu.com/Article/details/gt2wsybkpjk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mtrtiywc.html

[Q63] 开启事务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ngvdioyy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ivvv.top/Article/details/gt2mdexkiqh.html

[Q64] 提交事务
来源：http://dali.jyoumei.cn/Article/details/gt2ossxekgp.html

COMMIT;
来源：http://dali.sweek.top/Article/details/gt2vhhctidk.html

[Q65] 回滚事务
来源：http://dali.zhongyouzk.top/Article/details/gt2dlptbfyy.html

ROLLBACK;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tinlaozw.html

[Q66] 行锁查询
来源：http://dali.daxiang520.top/Article/details/gt2pivtdmps.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jiagoushi.top/Article/details/gt2grzqlfca.html

[Q67] 设置隔离级别
来源：http://dali.fengsongda.top/Article/details/gt2hisujsyd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnxiangtu.top/Article/details/gt2kbyfumfb.html

[Q68] 保存点
来源：http://dali.wangshuangyany.cn/Article/details/gt2rrqmiotw.html

SAVEPOINT sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jonhkcyl.html

ROLLBACK TO sp1;
来源：http://dali.ydzc1.top/Article/details/gt2lkpvvpyf.html

[Q69] 查看执行计划
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2isplzrgr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yanxiufei.cn/Article/details/gt2fqlntnaa.html

[Q70] 更新统计信息
来源：http://dali.jinqigfzy.top/Article/details/gt2bqleeuay.html

ANALYZE TABLE users;
来源：http://dali.xinyue.icu/Article/details/gt2mznalxdx.html

[Q71] 查看建表语句
来源：http://dali.quarkkingdee.top/Article/details/gt2grfempsb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gt2evkkeycv.html

[Q72] 查看索引
来源：http://dali.jqgufenzy.top/Article/details/gt2dqgtjslo.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eldwrrkp.html

[Q73] 查看表状态
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cetkyici.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.kuanghao11.cn/Article/details/gt2vbrllonr.html

[Q74] 强制使用索引
来源：http://dali.zhengqikj.top/Article/details/gt2mscgscqz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.snrcjt.cn/Article/details/gt2ejpzylms.html

[Q75] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gt2qdmdqsfp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gpttbzjz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shzxlz.cn/Article/details/gt2hchroabq.html

[Q76] 按天统计
来源：http://dali.vqdsnc.cn/Article/details/gt2rilrwpsd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangdashe.top/Article/details/gt2shgecrye.html

[Q77] 时间加减
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wnpngwhs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenzaomai.com/Article/details/gt2mpvsejjz.html

[Q78] 当前时间
来源：http://dali.bjfxy.top/Article/details/gt2mkokcfhl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenlongwang.top/Article/details/gt2gqkaojeu.html

[Q79] 字符串拼接
来源：http://dali.yj20258888.top/Article/details/gt2bmpurhai.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.smart0.xyz/Article/details/gt2zsqdahsa.html

[Q80] 字符串截取
来源：http://dali.shzxlz.cn/Article/details/gt2kitenqlr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2fsldqrwk.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhgppcn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mdjwhwil.html

[Q82] 字符长度与字节长度
来源：http://dali.mhx1999.top/Article/details/gt2tkqnhpbc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhxwvnat.html

[Q83] 大小写转换
来源：http://dali.316326.xyz/Article/details/gt2iqqnlujx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2mvbldmkw.html

[Q84] 去除首尾空格
来源：http://dali.zhixingplan.top/Article/details/gt2zegdvqmg.html

SELECT TRIM(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2wjazuxrl.html

[Q85] 数值取整
来源：http://dali.smart0.xyz/Article/details/gt2eqmakkzk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxuanxn.top/Article/details/gt2oirjtuqi.html

[Q86] 读取 JSON 字段
来源：http://dali.jyoumei.cn/Article/details/gt2jwzquphq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.svipenyu.cn/Article/details/gt2bzljoytf.html

[Q87] JSON 字段做条件
来源：http://dali.fzhhl.top/Article/details/gt2xladbrzc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ybcxt.top/Article/details/gt2mrqfdimp.html

[Q88] 行转列（条件聚合）
来源：http://dali.svipenyu.cn/Article/details/gt2hfhrkhwz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yangfankeji.com/Article/details/gt2hwvmkmgo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2bvhollda.html

[Q89] 判断表是否存在
来源：http://dali.guowangkeji.top/Article/details/gt2rcwwypna.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.bjfxy.top/Article/details/gt2sihdieem.html

[Q90] 生成序号列
来源：http://dali.jiagoushi.top/Article/details/gt2znvafchn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dashuyun.cn/Article/details/gt2hkuhlipz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2thpofhvz.html

R. Bash 专题
来源：http://dali.hammf.cn/Article/details/gt2mytbmfot.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2rjwwetwk.html

[R01] shebang 与严格模式
来源：http://dali.zycfv.cn/Article/details/gt2qypkimwn.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gt2uefrwosr.html

set -euo pipefail
来源：http://dali.chenlongwang.top/Article/details/gt2qxogjbvt.html

[R02] 变量赋值与使用
来源：http://dali.snrcjt.cn/Article/details/gt2gatxuyzv.html

name="Tom"; echo "$name"
来源：http://dali.316326.xyz/Article/details/gt2iosthzuw.html

[R03] 只读变量
来源：http://dali.guowangkeji.top/Article/details/gt2bqxbizmm.html

readonly PI=3.14
来源：http://dali.tanke756.top/Article/details/gt2slvfqsrk.html

[R04] 位置参数
来源：http://dali.yvedp.cn/Article/details/gt2tcrucmwq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuxming.cn/Article/details/gt2dowakind.html

[R05] 参数默认值
来源：http://dali.guannengcc.top/Article/details/gt2mtomatfo.html

name="${1:-default}"
来源：http://dali.316326.xyz/Article/details/gt2thlawkcv.html

[R06] 判断命令是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2qtjttexp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gt2mfbwashf.html

[R07] if 判断文件
来源：http://dali.yj202588.top/Article/details/gt2tewffptt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2tcvslqdf.html

[R08] 数值比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2gsgvzgwf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.birdmap.top/Article/details/gt2guqkoiba.html

[R09] 字符串比较
来源：http://dali.haohaochexian.top/Article/details/gt2rfvtuvoq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yongpay.top/Article/details/gt2jdsjhibt.html

[R10] 正则匹配
来源：http://dali.guannengcc.top/Article/details/gt2pzhvbkaj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nwbrower.top/Article/details/gt2zhmrifai.html

[R11] case 多分支
来源：http://dali.sysykeji.top/Article/details/gt2ugahxynq.html

case "$1" in
来源：http://dali.zhixingplan.top/Article/details/gt2ofwchuds.html

start) echo "启动" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qsbmjgxz.html

stop)  echo "停止" ;;
来源：http://dali.haohaochexian.top/Article/details/gt2livmivez.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gt2futachgl.html

esac
来源：http://dali.cucudq.cn/Article/details/gt2zmnlpfes.html

[R12] for 遍历文件
来源：http://dali.hnxiangtu.top/Article/details/gt2sgskvkql.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bcaudrsz.html

[R13] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gt2rnhgeedc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gt2vzcluxza.html

[R14] C 风格 for
来源：http://dali.yj202588.top/Article/details/gt2gecxphjk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gt2cdxqkgdk.html

[R15] while 逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2jzuhpexv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hywenlv.cn/Article/details/gt2bzagqhgh.html

[R16] until 等待条件
来源：http://dali.dianchejie.cn/Article/details/gt2detkbfdi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gt2oklnoxrw.html

[R17] 数组定义与取值
来源：http://dali.xuetiantiany.cn/Article/details/gt2moxjyfnr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gt2gbdydybc.html

[R18] 遍历数组
来源：http://dali.9152youxi.cn/Article/details/gt2dlnyjwsy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xylfe.cn/Article/details/gt2euebrauz.html

[R19] 数组长度
来源：http://dali.fengsongda.top/Article/details/gt2ghfcpdou.html

echo "${#arr[@]}"
来源：http://dali.jianghu66.top/Article/details/gt2hlwoqjge.html

[R20] 关联数组（字典）
来源：http://dali.cashguo.top/Article/details/gt2nijffmcg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cdnleiting.top/Article/details/gt2pyufvldt.html

[R21] 字符串长度
来源：http://dali.xuanzx.com/Article/details/gt2dlvpnbzg.html

echo "${#s}"
来源：http://dali.ydzc1.top/Article/details/gt2dequjfrs.html

[R22] 截取子串
来源：http://dali.sweek.top/Article/details/gt2radvrnpy.html

echo "${s:0:5}"
来源：http://dali.jinqigufen.top/Article/details/gt2zamuolxy.html

[R23] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2eduehaba.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gotoacloud.top/Article/details/gt2hdpfcbzk.html

[R24] 大小写转换
来源：http://dali.sweek.top/Article/details/gt2byitmdwi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daria6918.cn/Article/details/gt2hkzxgcbc.html

[R25] 去后缀 / 去前缀
来源：http://dali.pycfn.com/Article/details/gt2qawzmzkd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hfpthk.cn/Article/details/gt2zgetnvvc.html

[R26] 命令替换
来源：http://dali.tanke756.top/Article/details/gt2ghfcltnh.html

now=$(date +%F); echo "$now"
来源：http://dali.bjfxy.top/Article/details/gt2dvtrraux.html

[R27] 算术展开
来源：http://dali.yj202588.top/Article/details/gt2jfndfxly.html

echo $((1 + 2 * 3))
来源：http://dali.gaohongyu789.top/Article/details/gt2kmebnsdm.html

[R28] 浮点运算
来源：http://dali.gaohongyu789.top/Article/details/gt2makdqocx.html

echo "scale=2; 10/3" | bc
来源：http://dali.bjfxy.top/Article/details/gt2fypxlbor.html

[R29] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lopzcefj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aizwys.cn/Article/details/gt2rbfdxetl.html

[R30] 函数返回状态码
来源：http://dali.bjfxy.top/Article/details/gt2myvbhcoq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hongshengwenyu.top/Article/details/gt2agtgtgdi.html

[R31] 局部变量
来源：http://dali.sufxvd.cn/Article/details/gt2eiwlrqsm.html

f() { local x=1; echo "$x"; }
来源：http://dali.jyoumei.cn/Article/details/gt2lsjodunr.html

[R32] 参数个数校验
来源：http://dali.chenlongwang.top/Article/details/gt2aastjwts.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gt2eqfhapjf.html

[R33] 捕获错误并提示行号
来源：http://dali.yongpay.top/Article/details/gt2qfxzybjo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gt2duddxkvj.html

[R34] 退出时清理
来源：http://dali.cdnleiting.top/Article/details/gt2pnevuuxm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gt2xzcezgud.html

[R35] 后台执行并等待
来源：http://dali.gotoacloud.top/Article/details/gt2jqthvhsp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.iojbl.cn/Article/details/gt2zidigwhx.html

[R36] 并发执行多个任务
来源：http://dali.zhoulong.xyz/Article/details/gt2rfjblsts.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xinyue.icu/Article/details/gt2wxenspnc.html

[R37] 把输出赋给变量
来源：http://dali.vqdsnc.cn/Article/details/gt2gydlpmwu.html


<!-- 参考信息 -->