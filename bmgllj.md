代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.daxiang520.top/Article/details/gt2hyiegcft.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gt2xwvgmadv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gt2knodelhk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hywenlv.cn/Article/details/gt2fwsugovu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cdnleiting.top/Article/details/gt2wzembdsj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxinkj.top/Article/details/gt2eptkjtio.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.mhx1999.top/Article/details/gt2iiiuhohi.html

[P08] 处理浮点精度问题
来源：http://dali.zdqjudy.top/Article/details/gt2abpuqvdj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fengsongda.top/Article/details/gt2hoqbulch.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jianghu66.top/Article/details/gt2mbgsdtkm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuanzx.com/Article/details/gt2cnujmtlv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sweek.top/Article/details/gt2qrtnohfq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258.top/Article/details/gt2cjymldyr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigfzy.top/Article/details/gt2hianykfu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nwbrower.top/Article/details/gt2rgjbguha.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ydzc1.top/Article/details/gt2lthrgbft.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2jszfjiqw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hywenlv.cn/Article/details/gt2rtmfptuc.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2piqvohnh.html

[Q01] 创建表
来源：http://dali.fzhhl.top/Article/details/gt2wbrqsvxg.html

CREATE TABLE users (
来源：http://dali.hnxiangtu.top/Article/details/gt2xzluhtts.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gt2rknwjilv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gt2smjrhign.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenzaomai.com/Article/details/gt2jmndblmc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uiaslrws.html

);
来源：http://dali.jiagoushi.top/Article/details/gt2kokfevgi.html

[Q02] 创建带外键的表
来源：http://dali.yuxming.cn/Article/details/gt2qumyryjo.html

CREATE TABLE orders (
来源：http://dali.ybcxt.top/Article/details/gt2igrqrfdj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gt2qwagpcbl.html

user_id INT NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gt2pxlfzgtx.html

amount DECIMAL(10, 2),
来源：http://dali.quarkkingdee.top/Article/details/gt2hpchywxf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sbhuufds.html

);
来源：http://dali.yonumen.top/Article/details/gt2rmixwoio.html

[Q03] 增加列
来源：http://dali.zhoulong.xyz/Article/details/gt2bviwybjd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xinyue.icu/Article/details/gt2sknpbukm.html

[Q04] 修改列类型
来源：http://dali.jinqigufen.top/Article/details/gt2xxhkrhvw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhongyouzk.top/Article/details/gt2gaojlwcu.html

[Q05] 重命名列
来源：http://dali.yongpay.top/Article/details/gt2ilugrauv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.bjfxy.top/Article/details/gt2wfemhkkd.html

[Q06] 删除列
来源：http://dali.snrcjt.cn/Article/details/gt2ljgtdgfl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ocgmzqhi.html

[Q07] 删除表
来源：http://dali.cdnleiting.top/Article/details/gt2zgognoqf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.birdmap.top/Article/details/gt2dcjbgrel.html

[Q08] 创建普通索引
来源：http://dali.cqqwz.cn/Article/details/gt2xxgqlwcy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gt2okvkivmz.html

[Q09] 创建唯一索引
来源：http://dali.shangyingyoupin.top/Article/details/gt2ahugolag.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wmjwledt.html

[Q10] 插入单行
来源：http://dali.zycfv.cn/Article/details/gt2dbqwebru.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gt2shdcrgcq.html

[Q11] 一次插入多行
来源：http://dali.cqqwz.cn/Article/details/gt2uibqdnqo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.c1oappe.top/Article/details/gt2hzctddsp.html

[Q12] 插入后取自增 ID
来源：http://dali.mhx1999.top/Article/details/gt2fxedpksf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cashguo.top/Article/details/gt2enfxizyu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sysykeji.top/Article/details/gt2xfzddnoz.html

[Q13] 忽略重复插入
来源：http://dali.hongshengwenyu.top/Article/details/gt2nbsgoomg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hammf.cn/Article/details/gt2zktvywua.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pnetohgj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gogol.net.cn/Article/details/gt2qzxfunel.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.quarkkingdee.top/Article/details/gt2gaqlwwip.html

[Q15] 查询全部
来源：http://dali.hammf.cn/Article/details/gt2yqwdzlpz.html

SELECT * FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2dsogjnwj.html

[Q16] 查询指定列
来源：http://dali.sweek.top/Article/details/gt2yxdayjys.html

SELECT id, name FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2kygvkktu.html

[Q17] 条件查询
来源：http://dali.yj20258.top/Article/details/gt2flzagebw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cucudq.cn/Article/details/gt2lwoehmqo.html

[Q18] 模糊匹配
来源：http://dali.shzxlz.cn/Article/details/gt2tcwkoxgw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cdnleiting.top/Article/details/gt2ngwbgojz.html

[Q19] 范围查询
来源：http://dali.c1oappe.top/Article/details/gt2sijmeszx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.iojbl.cn/Article/details/gt2jdbzsipa.html

[Q20] IN 列表
来源：http://dali.aibaodan.cn/Article/details/gt2sujpbvwn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj202588.top/Article/details/gt2albrpdoa.html

[Q21] 空值判断
来源：http://dali.yueranfly.top/Article/details/gt2bzdglefi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.smart0.xyz/Article/details/gt2ryzfnwpi.html

[Q22] 排序
来源：http://dali.dashuyun.cn/Article/details/gt2eigkdknf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ybcxt.top/Article/details/gt2vheqrauw.html

[Q23] 分页
来源：http://dali.nanxuanxn.top/Article/details/gt2fngsgspr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zycfv.cn/Article/details/gt2ucqfonik.html

[Q24] 去重
来源：http://dali.gogol.net.cn/Article/details/gt2ddmxiwhg.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2dpqendyl.html

[Q25] 只取前 N 条
来源：http://dali.cheryme.top/Article/details/gt2urzozobr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenjidiqi.icu/Article/details/gt2jsjvpfjg.html

[Q26] 计数
来源：http://dali.wangshuangyany.cn/Article/details/gt2pouqjcax.html

SELECT COUNT(*) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2jvjbirha.html

[Q27] 条件计数
来源：http://dali.shzxlz.cn/Article/details/gt2ihsljqbj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2xtdnczxe.html

[Q28] 求和与平均
来源：http://dali.hnqzz.top/Article/details/gt2awwddfeu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2vtpezkgk.html

[Q29] 最大最小值
来源：http://dali.jinqigfzy.top/Article/details/gt2hgygredq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xciudpdn.html

[Q30] 分组统计
来源：http://dali.ydzc1.top/Article/details/gt2uojlviyr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gt2dwfrrhir.html

[Q31] 分组后过滤
来源：http://dali.316326.xyz/Article/details/gt2ggvgxxbv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daria6918.cn/Article/details/gt2pgwpqovd.html

[Q32] 分组拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gt2ifooryjy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gt2pcqymqve.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgufenzy.top/Article/details/gt2kkljwbjk.html

[Q33] 多列分组
来源：http://dali.hongshengwenyu.top/Article/details/gt2kscvffvi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.svipenyu.cn/Article/details/gt2nlgsjits.html

[Q34] 每组取第一条
来源：http://dali.yj20258888.top/Article/details/gt2rpqzxbqy.html

SELECT * FROM (
来源：http://dali.guowangkeji.top/Article/details/gt2umztsdei.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.smart0.xyz/Article/details/gt2navjvvgu.html

) t WHERE rn = 1;
来源：http://dali.xylfe.cn/Article/details/gt2nmozcajh.html

[Q35] 内连接
来源：http://dali.chenzaomai.com/Article/details/gt2iuxkudlp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2kknlosnm.html

[Q36] 左连接
来源：http://dali.jinqigufen.top/Article/details/gt2tjquolzr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gt2vxtgyqvq.html

[Q37] 右连接
来源：http://dali.chenzaomai.com/Article/details/gt2vgbkqwbg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zycfv.cn/Article/details/gt2xsicorcg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jiagoushi.top/Article/details/gt2lbwzakxr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxuanxn.top/Article/details/gt2daycipam.html

[Q39] 自连接（查上下级）
来源：http://dali.hysaishi.cn/Article/details/gt2jaggdkpe.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xziqi.cn/Article/details/gt2keiztzcs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenlongwang.top/Article/details/gt2qfccsmoz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dianchejie.cn/Article/details/gt2dpnyixjg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.daxiang520.top/Article/details/gt2bisfgwph.html

[Q41] 多表连接
来源：http://dali.yanxiufei.cn/Article/details/gt2bccgsrfq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxinkj.top/Article/details/gt2xlfmxfax.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cdnleiting.top/Article/details/gt2genhjnhb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.vqdsnc.cn/Article/details/gt2zzrxanxo.html

[Q42] 连接条件附加过滤
来源：http://dali.zhengqikj.top/Article/details/gt2qdqptmcq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigufen.top/Article/details/gt2kmoiqufg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cqqwz.cn/Article/details/gt2tudpwjmi.html

[Q43] 标量子查询
来源：http://dali.316326.xyz/Article/details/gt2suzzildg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgufenzy.top/Article/details/gt2dwnzftxm.html

[Q44] IN 子查询
来源：http://dali.9152youxi.cn/Article/details/gt2vhzljxxt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ratgponj.html

[Q45] EXISTS 判断存在
来源：http://dali.wangdashe.top/Article/details/gt2yeemjfwz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xmepitqf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2izlexwkh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gt2avfzfvvp.html

[Q47] 与平均值比较
来源：http://dali.jinqigufen.top/Article/details/gt2pjqivqyr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ytsgwkvm.html

[Q48] CTE 公用表表达式
来源：http://dali.hongshengwenyu.top/Article/details/gt2tuejwfmt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhixingplan.top/Article/details/gt2fvuxixxv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tianlin.xyz/Article/details/gt2mwhkasej.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gt2roweyopq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.dianchejie.cn/Article/details/gt2nxjzwdvn.html

[Q50] 批量更新
来源：http://dali.bjfxy.top/Article/details/gt2lpsktgyj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ivvv.top/Article/details/gt2yoblotlq.html

[Q51] 用子查询更新
来源：http://dali.aizwys.cn/Article/details/gt2umwjmleu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ivvv.top/Article/details/gt2dwzkpwii.html

[Q52] 删除指定行
来源：http://dali.cqqwz.cn/Article/details/gt2javdkxgx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gt2tfnarqvk.html

[Q53] 按条件删除
来源：http://dali.havefunace.top/Article/details/gt2ijlxnzik.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqzuaxeh.html

[Q54] 清空表
来源：http://dali.gogol.net.cn/Article/details/gt2taumfwdg.html

TRUNCATE TABLE logs;
来源：http://dali.zycfv.cn/Article/details/gt2tkmguoaz.html

[Q55] 排名（并列占位）
来源：http://dali.gaohongyu789.top/Article/details/gt2sbswwikp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daxiang520.top/Article/details/gt2jhlgmmct.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuanzhike.top/Article/details/gt2ivjcthgm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.meibo888.top/Article/details/gt2ooeefset.html

[Q57] 行号
来源：http://dali.jyoumei.cn/Article/details/gt2grtsgxmz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2wfyvfdur.html

[Q58] 累计求和
来源：http://dali.svipenyu.cn/Article/details/gt2nvakhlov.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2flymcgbl.html

[Q59] 分组内累计
来源：http://dali.quarkkingdee.top/Article/details/gt2jqjxuaun.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drcjqwkk.html

[Q60] 取上一行 / 下一行
来源：http://dali.iojbl.cn/Article/details/gt2lcaqqiwd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jianghu66.top/Article/details/gt2vdhhtwjp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2apzrpblm.html

[Q61] 移动平均
来源：http://dali.shanyushiyangtech.top/Article/details/gt2adulfqtg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2kjjwnmjo.html

[Q62] 分组占比
来源：http://dali.bjfxy.top/Article/details/gt2ifisvouc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gt2gjydhpcy.html

[Q63] 开启事务
来源：http://dali.zhiwuduotai.top/Article/details/gt2ngceluad.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dianchejie.cn/Article/details/gt2ddifqwdc.html

[Q64] 提交事务
来源：http://dali.ppjwa.cn/Article/details/gt2ivzidrrq.html

COMMIT;
来源：http://dali.hnqzz.top/Article/details/gt2yelmtskg.html

[Q65] 回滚事务
来源：http://dali.xuanzx.com/Article/details/gt2ggnqcxcs.html

ROLLBACK;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lbiwdmxz.html

[Q66] 行锁查询
来源：http://dali.smart0.xyz/Article/details/gt2xitdfnub.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hysaishi.cn/Article/details/gt2otbabbbt.html

[Q67] 设置隔离级别
来源：http://dali.yj202588.top/Article/details/gt2msdwbojw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.kuanghao11.cn/Article/details/gt2kyodvgea.html

[Q68] 保存点
来源：http://dali.wangdashe.top/Article/details/gt2hpanlvia.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pqympjbk.html

ROLLBACK TO sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2bihdoggv.html

[Q69] 查看执行计划
来源：http://dali.cheryme.top/Article/details/gt2zyjuzbpk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigfzy.top/Article/details/gt2wojutpxt.html

[Q70] 更新统计信息
来源：http://dali.daxiang520.top/Article/details/gt2lizkgtvi.html

ANALYZE TABLE users;
来源：http://dali.cheryme.top/Article/details/gt2xglkajbc.html

[Q71] 查看建表语句
来源：http://dali.cucudq.cn/Article/details/gt2ylwgeafm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.havefunace.top/Article/details/gt2gvlzyamk.html

[Q72] 查看索引
来源：http://dali.shzxlz.cn/Article/details/gt2zbjfpbql.html

SHOW INDEX FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2flpsvgrp.html

[Q73] 查看表状态
来源：http://dali.haohaochexian.top/Article/details/gt2znrbdovr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dianchejie.cn/Article/details/gt2ksqfwjly.html

[Q74] 强制使用索引
来源：http://dali.fengsongda.top/Article/details/gt2smbxjvtx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vhwpbalb.html

[Q75] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gt2edgdiphy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2aedlfyeh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pwqengoe.html

[Q76] 按天统计
来源：http://dali.cqqwz.cn/Article/details/gt2ghcjbmty.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ygjnydbk.html

[Q77] 时间加减
来源：http://dali.jiagoushi.top/Article/details/gt2dcqthduo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guowangkeji.top/Article/details/gt2bffuexky.html

[Q78] 当前时间
来源：http://dali.yj20258888.top/Article/details/gt2airbuylj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhoulong.xyz/Article/details/gt2bpdrwlhj.html

[Q79] 字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gt2wolipzlg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shangyingyoupin.top/Article/details/gt2hmelvbbe.html

[Q80] 字符串截取
来源：http://dali.ehwqpu.com/Article/details/gt2hzujykpv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2yskvywjk.html

[Q81] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gt2znfjqsqe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2dpurwvsc.html

[Q82] 字符长度与字节长度
来源：http://dali.chenzaomai.com/Article/details/gt2umtowrps.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2cvofkgqu.html

[Q83] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gt2akxnxghw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2euqhmnno.html

[Q84] 去除首尾空格
来源：http://dali.zhiwuduotai.top/Article/details/gt2azkhdeit.html

SELECT TRIM(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2olvopeqc.html

[Q85] 数值取整
来源：http://dali.zhongyouzk.top/Article/details/gt2pbkwnfvd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yongpay.top/Article/details/gt2pttahbnf.html

[Q86] 读取 JSON 字段
来源：http://dali.jianghu66.top/Article/details/gt2hmlsaeau.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shangyingyoupin.top/Article/details/gt2nwmqluee.html

[Q87] JSON 字段做条件
来源：http://dali.cqqwz.cn/Article/details/gt2mfktnsml.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzyawmgk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhixingplan.top/Article/details/gt2anegorjw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.redwolf501.top/Article/details/gt2molmgnci.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj20258.top/Article/details/gt2bgrtkuor.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gt2swpoiwtb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yongpay.top/Article/details/gt2fzsxfagf.html

[Q90] 生成序号列
来源：http://dali.gotoacloud.top/Article/details/gt2aryllvyc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.birdmap.top/Article/details/gt2lvjbmftz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2scqocyqm.html

R. Bash 专题
来源：http://dali.wangshuangyany.cn/Article/details/gt2pqvseekd.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2qfvjqhiw.html

[R01] shebang 与严格模式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zgpkbsuu.html

#!/usr/bin/env bash
来源：http://dali.jinqigfzy.top/Article/details/gt2vtsqcnyy.html

set -euo pipefail
来源：http://dali.bjfxy.top/Article/details/gt2jmgzqksv.html

[R02] 变量赋值与使用
来源：http://dali.smart0.xyz/Article/details/gt2jtpnowmb.html

name="Tom"; echo "$name"
来源：http://dali.hywenlv.cn/Article/details/gt2fysatqok.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gt2mxfbqjdt.html

readonly PI=3.14
来源：http://dali.0kj1m.cn/Article/details/gt2iufubtxt.html

[R04] 位置参数
来源：http://dali.yj20258.top/Article/details/gt2waszstpq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xylfe.cn/Article/details/gt2dorvfktt.html

[R05] 参数默认值
来源：http://dali.sufxvd.cn/Article/details/gt2gwxolxmn.html

name="${1:-default}"
来源：http://dali.vqdsnc.cn/Article/details/gt2jkakymzk.html

[R06] 判断命令是否存在
来源：http://dali.jinqigfzy.top/Article/details/gt2ivinmhqu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gt2ypmbxzcg.html

[R07] if 判断文件
来源：http://dali.xziqi.cn/Article/details/gt2ksbsfpgb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.svipenyu.cn/Article/details/gt2opywabcu.html

[R08] 数值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mqkwwlpk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nwbrower.top/Article/details/gt2ikxslfvw.html

[R09] 字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2tmswudbs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xziqi.cn/Article/details/gt2kppgxmrj.html

[R10] 正则匹配
来源：http://dali.ydzc1.top/Article/details/gt2ymnpvvyf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cheryme.top/Article/details/gt2vqgxyaof.html

[R11] case 多分支
来源：http://dali.jinqigufen.top/Article/details/gt2emxhkdcc.html

case "$1" in
来源：http://dali.yvedp.cn/Article/details/gt2vrwvaakh.html

start) echo "启动" ;;
来源：http://dali.quarkkingdee.top/Article/details/gt2adidlulm.html

stop)  echo "停止" ;;
来源：http://dali.birdmap.top/Article/details/gt2ufwkqogt.html

*)     echo "未知命令" ;;
来源：http://dali.daria6918.cn/Article/details/gt2vdtprcbs.html

esac
来源：http://dali.jyoumei.cn/Article/details/gt2yfeaxcbq.html

[R12] for 遍历文件
来源：http://dali.gogol.net.cn/Article/details/gt2ugfexjgc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnqzz.top/Article/details/gt2nrbkrndu.html

[R13] for 计数循环
来源：http://dali.aizwys.cn/Article/details/gt2xvmpjata.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gt2arlkpkmu.html

[R14] C 风格 for
来源：http://dali.snrcjt.cn/Article/details/gt2mmpmbsyz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gt2qybdcchp.html

[R15] while 逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gt2nmnlhiia.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.meibo888.top/Article/details/gt2venawinr.html

[R16] until 等待条件
来源：http://dali.quarkkingdee.top/Article/details/gt2jxbnzhlk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gt2fqxiwzix.html

[R17] 数组定义与取值
来源：http://dali.jqgfzy.top/Article/details/gt2vjtkglfo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258.top/Article/details/gt2jhijbzwv.html

[R18] 遍历数组
来源：http://dali.yanxiufei.cn/Article/details/gt2uqeoqnsy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ydzc1.top/Article/details/gt2doqnoulo.html

[R19] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2azwwuski.html

echo "${#arr[@]}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2xazrjagk.html

[R20] 关联数组（字典）
来源：http://dali.jinqigfzy.top/Article/details/gt2yyehkwbj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jiagoushi.top/Article/details/gt2pfsacvxh.html

[R21] 字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2ghpgqeny.html

echo "${#s}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2lpzhwkcb.html

[R22] 截取子串
来源：http://dali.jlsjyb.cn/Article/details/gt2yqtxmshh.html

echo "${s:0:5}"
来源：http://dali.yj20258.top/Article/details/gt2pedwnilf.html

[R23] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gt2dzrpzjwp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hammf.cn/Article/details/gt2gqgwsihp.html

[R24] 大小写转换
来源：http://dali.ydzc1.top/Article/details/gt2mzzkxdmw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.redwolf501.top/Article/details/gt2hkiklutx.html

[R25] 去后缀 / 去前缀
来源：http://dali.pengpengdd.cyou/Article/details/gt2xgyogxgc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xziqi.cn/Article/details/gt2qexvhlmv.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gt2orihcazu.html

now=$(date +%F); echo "$now"
来源：http://dali.svipenyu.cn/Article/details/gt2yfzcmyhe.html

[R27] 算术展开
来源：http://dali.birdmap.top/Article/details/gt2uskepngc.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ctabsniy.html

[R28] 浮点运算
来源：http://dali.cheryme.top/Article/details/gt2zjelycyc.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxuanxn.top/Article/details/gt2kwyzyszp.html

[R29] 定义函数
来源：http://dali.yj20258.top/Article/details/gt2koshqzdu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuanzx.com/Article/details/gt2xjpgizss.html

[R30] 函数返回状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zstssftx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jlsjyb.cn/Article/details/gt2oxxdzkyp.html

[R31] 局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2iphfmpsf.html

f() { local x=1; echo "$x"; }
来源：http://dali.yonumen.top/Article/details/gt2ewrqeoyg.html

[R32] 参数个数校验
来源：http://dali.cucudq.cn/Article/details/gt2uiicbezk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gt2vxltluqn.html

[R33] 捕获错误并提示行号
来源：http://dali.xuanzx.com/Article/details/gt2yjerfuje.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ronqiptk.html

[R34] 退出时清理
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxjnfzlm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gt2jfuxpelo.html

[R35] 后台执行并等待
来源：http://dali.cdnleiting.top/Article/details/gt2zfmoiqtp.html


<!-- 参考信息 -->