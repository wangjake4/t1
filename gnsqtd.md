代发 wailian999

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2gkqldeks.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sxryk.cn/Article/details/gt2zmcmfsti.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2abemgcyt.html

[Q01] 创建表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kfyukndl.html

CREATE TABLE users (
来源：http://dali.ppjwa.cn/Article/details/gt2gbhgwkbx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gt2yvyhsjgg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gt2djnzqjip.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gzhubu.top/Article/details/gt2ctswdvjs.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zdqjudy.top/Article/details/gt2bffrpmdl.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjyhcwvb.html

[Q02] 创建带外键的表
来源：http://dali.nwbrower.top/Article/details/gt2coviqnox.html

CREATE TABLE orders (
来源：http://dali.yanxiufei.cn/Article/details/gt2tjvoceno.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gt2bblkfdtu.html

user_id INT NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gt2fsuwblhx.html

amount DECIMAL(10, 2),
来源：http://dali.tianlin.xyz/Article/details/gt2akbyhcrz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dianchejie.cn/Article/details/gt2ucclqtqx.html

);
来源：http://dali.yj202588.top/Article/details/gt2ggvisses.html

[Q03] 增加列
来源：http://dali.jyoumei.cn/Article/details/gt2sonyzamy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxinkj.top/Article/details/gt2txfxkzko.html

[Q04] 修改列类型
来源：http://dali.tianlin.xyz/Article/details/gt2gdyyiixr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.316326.xyz/Article/details/gt2zvsyafpn.html

[Q05] 重命名列
来源：http://dali.zdqjudy.top/Article/details/gt2xrnntkgy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.birdmap.top/Article/details/gt2dpmwgmlt.html

[Q06] 删除列
来源：http://dali.jiagoushi.top/Article/details/gt2horqaewl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tianlin.xyz/Article/details/gt2kdhcmwiv.html

[Q07] 删除表
来源：http://dali.yanxiufei.cn/Article/details/gt2qbamrfrl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2ossoanrw.html

[Q08] 创建普通索引
来源：http://dali.gotoacloud.top/Article/details/gt2dgaypzmm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gt2zkkcosxa.html

[Q09] 创建唯一索引
来源：http://dali.ivvv.top/Article/details/gt2anltyflu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gt2avnyewse.html

[Q10] 插入单行
来源：http://dali.daxiang520.top/Article/details/gt2iylfefeg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.mhx1999.top/Article/details/gt2mkzfpfqo.html

[Q11] 一次插入多行
来源：http://dali.zycfv.cn/Article/details/gt2teiyewos.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnqzz.top/Article/details/gt2uazzzekn.html

[Q12] 插入后取自增 ID
来源：http://dali.guowangkeji.top/Article/details/gt2kkfuwfmh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenjidiqi.icu/Article/details/gt2cfvbilml.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shangyingyoupin.top/Article/details/gt2ontynrjs.html

[Q13] 忽略重复插入
来源：http://dali.pengpengdd.cyou/Article/details/gt2eguqrwep.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yongpay.top/Article/details/gt2cnmuazob.html

[Q14] 存在则更新（upsert）
来源：http://dali.aibaodan.cn/Article/details/gt2wmfibeqw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhengqikj.top/Article/details/gt2kovrmfrc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gaohongyu789.top/Article/details/gt2dvhffusr.html

[Q15] 查询全部
来源：http://dali.dianchejie.cn/Article/details/gt2qlvbeeym.html

SELECT * FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uvwojskx.html

[Q16] 查询指定列
来源：http://dali.zdqjudy.top/Article/details/gt2foxtpnew.html

SELECT id, name FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2sborgyjf.html

[Q17] 条件查询
来源：http://dali.nwbrower.top/Article/details/gt2hqmrpkpc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2alkufmkb.html

[Q18] 模糊匹配
来源：http://dali.iojbl.cn/Article/details/gt2btsggfhi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.andypj.xyz/Article/details/gt2byqtyuuh.html

[Q19] 范围查询
来源：http://dali.aizwys.cn/Article/details/gt2ekfpcskb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhengqikj.top/Article/details/gt2knbfhhtr.html

[Q20] IN 列表
来源：http://dali.aizwys.cn/Article/details/gt2rvqfzkeb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhengqikj.top/Article/details/gt2ehznzjku.html

[Q21] 空值判断
来源：http://dali.bjfxy.top/Article/details/gt2rgafyoum.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenlongwang.top/Article/details/gt2ohhlpldb.html

[Q22] 排序
来源：http://dali.guannengcc.top/Article/details/gt2hhqckkly.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.meibo888.top/Article/details/gt2wsmsiect.html

[Q23] 分页
来源：http://dali.iojbl.cn/Article/details/gt2ddndoxdw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hysaishi.cn/Article/details/gt2pojdjxfu.html

[Q24] 去重
来源：http://dali.yueranfly.top/Article/details/gt2pvejhnwm.html

SELECT DISTINCT city FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2emkieyvg.html

[Q25] 只取前 N 条
来源：http://dali.yueranfly.top/Article/details/gt2prmtfkxm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinqigufen.top/Article/details/gt2pzmwqgxe.html

[Q26] 计数
来源：http://dali.zhoulong.xyz/Article/details/gt2rlgmdhij.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zjhslpff.html

[Q27] 条件计数
来源：http://dali.jianghu66.top/Article/details/gt2enqzzoke.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2zjppchog.html

[Q28] 求和与平均
来源：http://dali.ybcxt.top/Article/details/gt2rhznkicx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2meoigsbg.html

[Q29] 最大最小值
来源：http://dali.gogol.net.cn/Article/details/gt2giiklcsz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2kmrjuwnt.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlaixns.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gt2jzvvnnkr.html

[Q31] 分组后过滤
来源：http://dali.sweek.top/Article/details/gt2xbsqkqmf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xinyue.icu/Article/details/gt2hovyenaa.html

[Q32] 分组拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gt2mmmteeeb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gt2dzjmefre.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ivvv.top/Article/details/gt2halgelqj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ropahbit.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigfzy.top/Article/details/gt2bnwdiyro.html

[Q34] 每组取第一条
来源：http://dali.chenlongwang.top/Article/details/gt2dvjmnoqd.html

SELECT * FROM (
来源：http://dali.bjfxy.top/Article/details/gt2gkgqtpvl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxuanxn.top/Article/details/gt2jgblgmeu.html

) t WHERE rn = 1;
来源：http://dali.ybcxt.top/Article/details/gt2gsfcjnbf.html

[Q35] 内连接
来源：http://dali.havefunace.top/Article/details/gt2hjsyhzeq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2tuohzqdw.html

[Q36] 左连接
来源：http://dali.zhixingplan.top/Article/details/gt2agryxfkg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgufenzy.top/Article/details/gt2iojlozsi.html

[Q37] 右连接
来源：http://dali.yuanzhike.top/Article/details/gt2emybgcyx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2hugkbatj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rvovkwnb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sysykeji.top/Article/details/gt2xbqtbgfb.html

[Q39] 自连接（查上下级）
来源：http://dali.yanxiufei.cn/Article/details/gt2plwkwuqq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hpuwenqa.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nwbrower.top/Article/details/gt2kzomglne.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cxzkkgsi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.birdmap.top/Article/details/gt2vswzdcqn.html

[Q41] 多表连接
来源：http://dali.jinqigufen.top/Article/details/gt2ysjnrhdl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.feifeiyinyue.top/Article/details/gt2mygryazw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.quarkkingdee.top/Article/details/gt2oxcrlreo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ctwvtvvj.html

[Q42] 连接条件附加过滤
来源：http://dali.fengsongda.top/Article/details/gt2doanfgah.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hammf.cn/Article/details/gt2moqokyse.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sysykeji.top/Article/details/gt2vjetfixw.html

[Q43] 标量子查询
来源：http://dali.birdmap.top/Article/details/gt2gicfjckc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigufen.top/Article/details/gt2iusgyayu.html

[Q44] IN 子查询
来源：http://dali.tanke756.top/Article/details/gt2huqoaywf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xinyue.icu/Article/details/gt2lydugslp.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zvzuevgu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.316326.xyz/Article/details/gt2lvkridto.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.quarkkingdee.top/Article/details/gt2gsohmalk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gt2gnhedqyx.html

[Q47] 与平均值比较
来源：http://dali.cqqwz.cn/Article/details/gt2tfeoiseg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cqqwz.cn/Article/details/gt2mwfqbwhr.html

[Q48] CTE 公用表表达式
来源：http://dali.0kj1m.cn/Article/details/gt2xmdocbow.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sweek.top/Article/details/gt2ptsexycf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aibaodan.cn/Article/details/gt2zpmziikd.html

[Q49] 更新单行
来源：http://dali.nanxinkj.top/Article/details/gt2dpwyqksn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gt2yfniyzrw.html

[Q50] 批量更新
来源：http://dali.hammf.cn/Article/details/gt2rbgrvvlp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aizwys.cn/Article/details/gt2mykoimet.html

[Q51] 用子查询更新
来源：http://dali.xuanzx.com/Article/details/gt2yrgbfedd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2rpievudn.html

[Q52] 删除指定行
来源：http://dali.shuidangran.top/Article/details/gt2mxiaubbp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gt2asomeqlz.html

[Q53] 按条件删除
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tbeqzhcd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2imthrxhi.html

[Q54] 清空表
来源：http://dali.tianlin.xyz/Article/details/gt2tytfmzkv.html

TRUNCATE TABLE logs;
来源：http://dali.sweek.top/Article/details/gt2xviqymfn.html

[Q55] 排名（并列占位）
来源：http://dali.bjfxy.top/Article/details/gt2jzkaehhl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gt2fgwatijy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2aazfkgjh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cheryme.top/Article/details/gt2lzqsqkss.html

[Q57] 行号
来源：http://dali.iojbl.cn/Article/details/gt2reifbgke.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2vnzixnfa.html

[Q58] 累计求和
来源：http://dali.jianghu66.top/Article/details/gt2zrqeerch.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2etdjooch.html

[Q59] 分组内累计
来源：http://dali.quarkkingdee.top/Article/details/gt2pouewtey.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gt2lmfwzvyd.html

[Q60] 取上一行 / 下一行
来源：http://dali.jlsjyb.cn/Article/details/gt2qygzbuah.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangshuangyany.cn/Article/details/gt2rdhighjh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2tkykuhqp.html

[Q61] 移动平均
来源：http://dali.ybcxt.top/Article/details/gt2aljjfadn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2kjvcetzr.html

[Q62] 分组占比
来源：http://dali.jianghu66.top/Article/details/gt2wqjrmxkl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gt2wcqfggio.html

[Q63] 开启事务
来源：http://dali.sxryk.cn/Article/details/gt2qupspzvk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czdsgrhw.html

[Q64] 提交事务
来源：http://dali.sweek.top/Article/details/gt2zlwozaoj.html

COMMIT;
来源：http://dali.gogol.net.cn/Article/details/gt2kvlarucl.html

[Q65] 回滚事务
来源：http://dali.chenjidiqi.icu/Article/details/gt2hbzroacz.html

ROLLBACK;
来源：http://dali.hywenlv.cn/Article/details/gt2nistvxir.html

[Q66] 行锁查询
来源：http://dali.feifeiyinyue.top/Article/details/gt2iztddscj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenjidiqi.icu/Article/details/gt2zptvvjkp.html

[Q67] 设置隔离级别
来源：http://dali.xuetiantiany.cn/Article/details/gt2ckgruglc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258.top/Article/details/gt2qmzainet.html

[Q68] 保存点
来源：http://dali.redwolf501.top/Article/details/gt2nwmcvaro.html

SAVEPOINT sp1;
来源：http://dali.jqgufenzy.top/Article/details/gt2ldjwklsu.html

ROLLBACK TO sp1;
来源：http://dali.cdnleiting.top/Article/details/gt2xvapqpqe.html

[Q69] 查看执行计划
来源：http://dali.yongpay.top/Article/details/gt2tdfeqwrm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xinyue.icu/Article/details/gt2txonbjvf.html

[Q70] 更新统计信息
来源：http://dali.haohaochexian.top/Article/details/gt2xpvfbzhz.html

ANALYZE TABLE users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2gqqpfbhw.html

[Q71] 查看建表语句
来源：http://dali.hammf.cn/Article/details/gt2lgiiarnd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ukumfdva.html

[Q72] 查看索引
来源：http://dali.shzxlz.cn/Article/details/gt2adqqixiz.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2yzulmcdg.html

[Q73] 查看表状态
来源：http://dali.zdqjudy.top/Article/details/gt2xybkaqyv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jwhrrjap.html

[Q74] 强制使用索引
来源：http://dali.zhengqikj.top/Article/details/gt2wlwwgopr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sweek.top/Article/details/gt2gkjogghj.html

[Q75] 日期格式化
来源：http://dali.meibo888.top/Article/details/gt2ayxgyiyt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2ffoxosqq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhixingplan.top/Article/details/gt2tvtconlw.html

[Q76] 按天统计
来源：http://dali.sysykeji.top/Article/details/gt2vdzwssfr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxuanxn.top/Article/details/gt2eouvgxhl.html

[Q77] 时间加减
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sfsoixpj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xylfe.cn/Article/details/gt2euhtyhmg.html

[Q78] 当前时间
来源：http://dali.jiagoushi.top/Article/details/gt2bramvjqn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgfzy.top/Article/details/gt2cucviwcl.html

[Q79] 字符串拼接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xwzmdqgj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhengqikj.top/Article/details/gt2kkxzddsh.html

[Q80] 字符串截取
来源：http://dali.zycfv.cn/Article/details/gt2ywilcwdh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lnuvvlty.html

[Q81] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gt2jbhtcdng.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yongpay.top/Article/details/gt2gccpbjve.html

[Q82] 字符长度与字节长度
来源：http://dali.svipenyu.cn/Article/details/gt2pgexhfko.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2aleitbkd.html

[Q83] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gt2cjhnqtjd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2jefmwqxk.html

[Q84] 去除首尾空格
来源：http://dali.yangfankeji.com/Article/details/gt2ewzhvfgz.html

SELECT TRIM(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2brxcrijk.html

[Q85] 数值取整
来源：http://dali.wangshuangyany.cn/Article/details/gt2qxxghovu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2clyetqpw.html

[Q86] 读取 JSON 字段
来源：http://dali.bjfxy.top/Article/details/gt2lwphrpdo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fengsongda.top/Article/details/gt2wjbtyhjd.html

[Q87] JSON 字段做条件
来源：http://dali.tian-w.cn/Article/details/gt2wpglepan.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xziqi.cn/Article/details/gt2zmyuvodz.html

[Q88] 行转列（条件聚合）
来源：http://dali.yanxiufei.cn/Article/details/gt2rjjyayra.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.meibo888.top/Article/details/gt2oqprjzoc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2jalytmst.html

[Q89] 判断表是否存在
来源：http://dali.guowangkeji.top/Article/details/gt2sadeespg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ehwqpu.com/Article/details/gt2oadghxzt.html

[Q90] 生成序号列
来源：http://dali.xuetiantiany.cn/Article/details/gt2horwvdxv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fbzygikf.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjxpscif.html

R. Bash 专题
来源：http://dali.shuidangran.top/Article/details/gt2uvsfdpsk.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2kcimlzau.html

[R01] shebang 与严格模式
来源：http://dali.jqgufenzy.top/Article/details/gt2vgectzro.html

#!/usr/bin/env bash
来源：http://dali.zhengqikj.top/Article/details/gt2fxbiktbp.html

set -euo pipefail
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ivulivcq.html

[R02] 变量赋值与使用
来源：http://dali.ehwqpu.com/Article/details/gt2egmcoiqc.html

name="Tom"; echo "$name"
来源：http://dali.shuidangran.top/Article/details/gt2eipmnqii.html

[R03] 只读变量
来源：http://dali.sweek.top/Article/details/gt2knomjtgw.html

readonly PI=3.14
来源：http://dali.hnqzz.top/Article/details/gt2vcnzgoxq.html

[R04] 位置参数
来源：http://dali.jqgufenzy.top/Article/details/gt2ojoqukip.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhongyouzk.top/Article/details/gt2dsjvbxxv.html

[R05] 参数默认值
来源：http://dali.yj202588.top/Article/details/gt2tllpkhuj.html

name="${1:-default}"
来源：http://dali.haohaochexian.top/Article/details/gt2yymccyap.html

[R06] 判断命令是否存在
来源：http://dali.c1oappe.top/Article/details/gt2mththzak.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2urykxhmj.html

[R07] if 判断文件
来源：http://dali.yonumen.top/Article/details/gt2lqjhkgzn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnqzz.top/Article/details/gt2bozswxrr.html

[R08] 数值比较
来源：http://dali.fengsongda.top/Article/details/gt2npkplvku.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zlwahlvu.html

[R09] 字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gt2acpanfha.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cucudq.cn/Article/details/gt2ewgbnnvl.html

[R10] 正则匹配
来源：http://dali.jianghu66.top/Article/details/gt2csfvxaqj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuxming.cn/Article/details/gt2ntkeilye.html

[R11] case 多分支
来源：http://dali.cqqwz.cn/Article/details/gt2gyelnqhn.html

case "$1" in
来源：http://dali.quarkkingdee.top/Article/details/gt2tporbkhn.html

start) echo "启动" ;;
来源：http://dali.ivvv.top/Article/details/gt2nblxlzoy.html

stop)  echo "停止" ;;
来源：http://dali.yj20258.top/Article/details/gt2zsoqocly.html

*)     echo "未知命令" ;;
来源：http://dali.redwolf501.top/Article/details/gt2tqmpcsyo.html

esac
来源：http://dali.ybcxt.top/Article/details/gt2whhvcdth.html

[R12] for 遍历文件
来源：http://dali.yj202588.top/Article/details/gt2htvyjbyd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhixingplan.top/Article/details/gt2pqnbuycb.html

[R13] for 计数循环
来源：http://dali.hammf.cn/Article/details/gt2eziqkzuv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gt2ystpujnk.html

[R14] C 风格 for
来源：http://dali.jinqigufen.top/Article/details/gt2nwbljzhe.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gt2yjgcmcay.html

[R15] while 逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gt2gaedjyfa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxinkj.top/Article/details/gt2fukshwoe.html

[R16] until 等待条件
来源：http://dali.gotoacloud.top/Article/details/gt2jegwlqpe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gt2xjurfwco.html

[R17] 数组定义与取值
来源：http://dali.feifeiyinyue.top/Article/details/gt2txatfxsn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xziqi.cn/Article/details/gt2iujzvykb.html

[R18] 遍历数组
来源：http://dali.xuanzx.com/Article/details/gt2pzdymxue.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.haohaochexian.top/Article/details/gt2wkcontpk.html

[R19] 数组长度
来源：http://dali.yj202588.top/Article/details/gt2uzdnhxjs.html

echo "${#arr[@]}"
来源：http://dali.gotoacloud.top/Article/details/gt2phmnlcow.html

[R20] 关联数组（字典）
来源：http://dali.havefunace.top/Article/details/gt2wrydvrdm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fengsongda.top/Article/details/gt2oqsppekk.html

[R21] 字符串长度
来源：http://dali.9152youxi.cn/Article/details/gt2ypsapbnd.html

echo "${#s}"
来源：http://dali.hnxiangtu.top/Article/details/gt2kytjxljt.html

[R22] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gt2ukeythwi.html

echo "${s:0:5}"
来源：http://dali.xylfe.cn/Article/details/gt2dwyccxhd.html

[R23] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sayifbfa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2foulfjyc.html

[R24] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2mczelluz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zdqjudy.top/Article/details/gt2mrsvuoym.html

[R25] 去后缀 / 去前缀
来源：http://dali.snrcjt.cn/Article/details/gt2dswalazr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xziqi.cn/Article/details/gt2mgbyhdyf.html

[R26] 命令替换
来源：http://dali.yj20258.top/Article/details/gt2gzcooqro.html

now=$(date +%F); echo "$now"
来源：http://dali.ybcxt.top/Article/details/gt2cekxaqjd.html

[R27] 算术展开
来源：http://dali.jlsjyb.cn/Article/details/gt2dtvnwbvm.html

echo $((1 + 2 * 3))
来源：http://dali.snrcjt.cn/Article/details/gt2rvxonacb.html

[R28] 浮点运算
来源：http://dali.jiagoushi.top/Article/details/gt2gpsivorn.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigufen.top/Article/details/gt2gfmemxfd.html

[R29] 定义函数
来源：http://dali.redwolf501.top/Article/details/gt2avbvxedp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.redwolf501.top/Article/details/gt2hxzhbwwh.html

[R30] 函数返回状态码
来源：http://dali.andypj.xyz/Article/details/gt2vydrpdyw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hysaishi.cn/Article/details/gt2tntafrwh.html

[R31] 局部变量
来源：http://dali.shzxlz.cn/Article/details/gt2pyynacct.html

f() { local x=1; echo "$x"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2fnklhlxp.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gt2myzjqswn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gt2ucsycfmb.html

[R33] 捕获错误并提示行号
来源：http://dali.fengsongda.top/Article/details/gt2xnreifsk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuanzx.com/Article/details/gt2mdybhovm.html

[R34] 退出时清理
来源：http://dali.chenlongwang.top/Article/details/gt2zcalxrij.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gt2qldroebg.html

[R35] 后台执行并等待
来源：http://dali.xziqi.cn/Article/details/gt2kgenywst.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gotoacloud.top/Article/details/gt2lgehzznx.html

[R36] 并发执行多个任务
来源：http://dali.jianghu66.top/Article/details/gt2kmbtdiio.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xylfe.cn/Article/details/gt2oljuiyib.html

[R37] 把输出赋给变量
来源：http://dali.sysykeji.top/Article/details/gt2vllfndbu.html

files=$(ls -1)
来源：http://dali.nanxinkj.top/Article/details/gt2iwgymeai.html

[R38] 管道串联
来源：http://dali.9152youxi.cn/Article/details/gt2yyvzvlpy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daxiang520.top/Article/details/gt2yslydrvw.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gt2woxzafrx.html

cmd > out.log 2>&1
来源：http://dali.xuanzx.com/Article/details/gt2yopgygxh.html

[R40] 追加写日志
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mdiewogl.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmgkxoc.html

[R41] 丢弃输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2smcpwhau.html

cmd >/dev/null 2>&1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ttvjehig.html

[R42] 输入重定向
来源：http://dali.daxiang520.top/Article/details/gt2bqyeykbs.html

wc -l < a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2gayfydad.html

[R43] 按名字查找文件
来源：http://dali.sysykeji.top/Article/details/gt2mrhkxqlw.html


<!-- 参考信息 -->