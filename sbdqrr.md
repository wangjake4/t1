代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.wangdashe.top/Article/details/gt2vaezvwky.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gt2aumxirkz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gt2blvojwhv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2aabzzefi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hysaishi.cn/Article/details/gt2fskkbluh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.meibo888.top/Article/details/gt2nibnhefv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aibaodan.cn/Article/details/gt2gxxglbng.html

[P08] 处理浮点精度问题
来源：http://dali.daria6918.cn/Article/details/gt2dtylvbng.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yanxiufei.cn/Article/details/gt2zlmzmvew.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yongpay.top/Article/details/gt2woffjlns.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dashuyun.cn/Article/details/gt2kdgynacj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gt2nvclsxok.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pengpengdd.cyou/Article/details/gt2otcutqke.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.snrcjt.cn/Article/details/gt2ygwjlsmv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gogol.net.cn/Article/details/gt2nlhjknok.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sufxvd.cn/Article/details/gt2uzhusynk.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2isyqkbgi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guannengcc.top/Article/details/gt2tbjjfgyi.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2fmxdlppw.html

[Q01] 创建表
来源：http://dali.kuanghao11.cn/Article/details/gt2papstetf.html

CREATE TABLE users (
来源：http://dali.redwolf501.top/Article/details/gt2cjbgaezs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.smart0.xyz/Article/details/gt2qeyktdhm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gt2vcrllpge.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yanxiufei.cn/Article/details/gt2ifaivwfe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gogol.net.cn/Article/details/gt2vraxojsm.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fjigjrll.html

[Q02] 创建带外键的表
来源：http://dali.sxryk.cn/Article/details/gt2cljipvaf.html

CREATE TABLE orders (
来源：http://dali.cheryme.top/Article/details/gt2wssdppsf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gt2qjkyyidi.html

user_id INT NOT NULL,
来源：http://dali.gotoacloud.top/Article/details/gt2dtvxzbhx.html

amount DECIMAL(10, 2),
来源：http://dali.snrcjt.cn/Article/details/gt2msiytoia.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yvedp.cn/Article/details/gt2nnukrgqt.html

);
来源：http://dali.vqdsnc.cn/Article/details/gt2wbffwttc.html

[Q03] 增加列
来源：http://dali.guowangkeji.top/Article/details/gt2snyumwlx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hfpthk.cn/Article/details/gt2lpurkpzc.html

[Q04] 修改列类型
来源：http://dali.jinqigufen.top/Article/details/gt2xhhzlehz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ydzc1.top/Article/details/gt2anphtjed.html

[Q05] 重命名列
来源：http://dali.chenlongwang.top/Article/details/gt2qclafopl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxuanxn.top/Article/details/gt2tnutmgtd.html

[Q06] 删除列
来源：http://dali.shangyingyoupin.top/Article/details/gt2xptrwfza.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2elxdgatq.html

[Q07] 删除表
来源：http://dali.xylfe.cn/Article/details/gt2rjcjzkzb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gzhubu.top/Article/details/gt2kosipkqh.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tyowjvnb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gt2xmuduszw.html

[Q09] 创建唯一索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2yehlista.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gt2cnpxwpdr.html

[Q10] 插入单行
来源：http://dali.bjfxy.top/Article/details/gt2fblcwahi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gt2ktnnaepf.html

[Q11] 一次插入多行
来源：http://dali.quarkkingdee.top/Article/details/gt2rrgwbjhm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.meibo888.top/Article/details/gt2jkovvdbm.html

[Q12] 插入后取自增 ID
来源：http://dali.daxiang520.top/Article/details/gt2qnpjyoae.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yueranfly.top/Article/details/gt2waasuwbo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.pengpengdd.cyou/Article/details/gt2krfmjobf.html

[Q13] 忽略重复插入
来源：http://dali.316326.xyz/Article/details/gt2irahitwj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yvedp.cn/Article/details/gt2wapgenue.html

[Q14] 存在则更新（upsert）
来源：http://dali.yonumen.top/Article/details/gt2czcuhyjs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cucudq.cn/Article/details/gt2tklprrme.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmerqhab.html

[Q15] 查询全部
来源：http://dali.sufxvd.cn/Article/details/gt2butuizwm.html

SELECT * FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2vqgjnsfk.html

[Q16] 查询指定列
来源：http://dali.yj20258888.top/Article/details/gt2ndmhfacy.html

SELECT id, name FROM users;
来源：http://dali.sweek.top/Article/details/gt2nwwriwbs.html

[Q17] 条件查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2qbvnalzt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258888.top/Article/details/gt2dmfwtxya.html

[Q18] 模糊匹配
来源：http://dali.fengsongda.top/Article/details/gt2wdhhfdvt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gogol.net.cn/Article/details/gt2nmdadaar.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsnsbyo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gogol.net.cn/Article/details/gt2ypnpmsyg.html

[Q20] IN 列表
来源：http://dali.hysaishi.cn/Article/details/gt2yuqqzzkw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuxming.cn/Article/details/gt2bqehaulv.html

[Q21] 空值判断
来源：http://dali.hywenlv.cn/Article/details/gt2deboizvu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.havefunace.top/Article/details/gt2qdhhwkzn.html

[Q22] 排序
来源：http://dali.sxryk.cn/Article/details/gt2iavygpwe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hongshengwenyu.top/Article/details/gt2caxpavpa.html

[Q23] 分页
来源：http://dali.jinqigfzy.top/Article/details/gt2pybtzkkf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dianchejie.cn/Article/details/gt2qkjajvpx.html

[Q24] 去重
来源：http://dali.xylfe.cn/Article/details/gt2wtjqsoae.html

SELECT DISTINCT city FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2evkdulav.html

[Q25] 只取前 N 条
来源：http://dali.xuetiantiany.cn/Article/details/gt2mkgkmpnz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dashuyun.cn/Article/details/gt2xlesmrhx.html

[Q26] 计数
来源：http://dali.316326.xyz/Article/details/gt2hzqwciep.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2gocyyixu.html

[Q27] 条件计数
来源：http://dali.jiagoushi.top/Article/details/gt2omninxav.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sweek.top/Article/details/gt2mwomrhhy.html

[Q28] 求和与平均
来源：http://dali.vqdsnc.cn/Article/details/gt2jrfazvus.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2krmobqos.html

[Q29] 最大最小值
来源：http://dali.bjfxy.top/Article/details/gt2nytaihfp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2ynevehkx.html

[Q30] 分组统计
来源：http://dali.dianchejie.cn/Article/details/gt2ltcakmbx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gt2nrfqtirv.html

[Q31] 分组后过滤
来源：http://dali.zhixingplan.top/Article/details/gt2ngutasxs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hysaishi.cn/Article/details/gt2szvgwagj.html

[Q32] 分组拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gt2bubybmiy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gt2snbigfae.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xinyue.icu/Article/details/gt2vrxvnxae.html

[Q33] 多列分组
来源：http://dali.jqgufenzy.top/Article/details/gt2nggiezfv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gaohongyu789.top/Article/details/gt2gnluulac.html

[Q34] 每组取第一条
来源：http://dali.0kj1m.cn/Article/details/gt2nfrwllks.html

SELECT * FROM (
来源：http://dali.shzxlz.cn/Article/details/gt2lqbrhvyn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yongpay.top/Article/details/gt2ljmosxfr.html

) t WHERE rn = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2hqcjvsdz.html

[Q35] 内连接
来源：http://dali.guowangkeji.top/Article/details/gt2sjrlhozm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gt2vmprzkws.html

[Q36] 左连接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pasrbeal.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gt2fuhkcabr.html

[Q37] 右连接
来源：http://dali.sysykeji.top/Article/details/gt2vssbnwui.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sysykeji.top/Article/details/gt2ofmniprt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenjidiqi.icu/Article/details/gt2nylhkhpi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ybcxt.top/Article/details/gt2zittvbqb.html

[Q39] 自连接（查上下级）
来源：http://dali.shuidangran.top/Article/details/gt2yqhblbwl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.svipenyu.cn/Article/details/gt2rbeslqdu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.guowangkeji.top/Article/details/gt2serrozph.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sufxvd.cn/Article/details/gt2jzjbktfq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.daria6918.cn/Article/details/gt2oruxjwkn.html

[Q41] 多表连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kwppzqbf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj202588.top/Article/details/gt2djazbwsi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xinyue.icu/Article/details/gt2rvfomnzb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenjidiqi.icu/Article/details/gt2jtrrqjeo.html

[Q42] 连接条件附加过滤
来源：http://dali.aizwys.cn/Article/details/gt2etdoyxrf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sujsuuex.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fzhhl.top/Article/details/gt2fwdepzzf.html

[Q43] 标量子查询
来源：http://dali.ydzc1.top/Article/details/gt2tnbyqktn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dashuyun.cn/Article/details/gt2ejzdszfd.html

[Q44] IN 子查询
来源：http://dali.dianchejie.cn/Article/details/gt2xgrmzhtj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jiagoushi.top/Article/details/gt2bdejjjje.html

[Q45] EXISTS 判断存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2xvybqgph.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gt2vmcswbkj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.redwolf501.top/Article/details/gt2cwclmtkq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxkisyun.html

[Q47] 与平均值比较
来源：http://dali.cheryme.top/Article/details/gt2hvkailli.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guowangkeji.top/Article/details/gt2ydarfwoh.html

[Q48] CTE 公用表表达式
来源：http://dali.shuidangran.top/Article/details/gt2mppngriw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuanzhike.top/Article/details/gt2xfehsmsx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.iojbl.cn/Article/details/gt2ylmygqnz.html

[Q49] 更新单行
来源：http://dali.zhongyouzk.top/Article/details/gt2hqgdflxp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gt2ckcwzmuq.html

[Q50] 批量更新
来源：http://dali.guowangkeji.top/Article/details/gt2mdvaaavh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tanke756.top/Article/details/gt2ffmkrawn.html

[Q51] 用子查询更新
来源：http://dali.zhengqikj.top/Article/details/gt2nrresrmv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cashguo.top/Article/details/gt2suybocrp.html

[Q52] 删除指定行
来源：http://dali.hywenlv.cn/Article/details/gt2paqbuhgn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uaxbbckq.html

[Q53] 按条件删除
来源：http://dali.cheryme.top/Article/details/gt2cztzrxkk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgfzy.top/Article/details/gt2dlxtvuys.html

[Q54] 清空表
来源：http://dali.nanxuanxn.top/Article/details/gt2yximxhrq.html

TRUNCATE TABLE logs;
来源：http://dali.aizwys.cn/Article/details/gt2jmkhfhmf.html

[Q55] 排名（并列占位）
来源：http://dali.zycfv.cn/Article/details/gt2jfribxol.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daria6918.cn/Article/details/gt2rlugmoor.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigfzy.top/Article/details/gt2dctohgex.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gt2zswvvbpl.html

[Q57] 行号
来源：http://dali.svipenyu.cn/Article/details/gt2hicdkxfm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cheryme.top/Article/details/gt2imkoprrp.html

[Q58] 累计求和
来源：http://dali.hnqzz.top/Article/details/gt2aosngypy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2aqroqauf.html

[Q59] 分组内累计
来源：http://dali.yj20258888.top/Article/details/gt2pnmvrkvv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eufzcsce.html

[Q60] 取上一行 / 下一行
来源：http://dali.tianlin.xyz/Article/details/gt2zlltduxd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aibaodan.cn/Article/details/gt2tvrqowfl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2kqjpluqd.html

[Q61] 移动平均
来源：http://dali.hywenlv.cn/Article/details/gt2jlgcjzdo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2soowqyvu.html

[Q62] 分组占比
来源：http://dali.sweek.top/Article/details/gt2xqepxuwc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gt2gflagerx.html

[Q63] 开启事务
来源：http://dali.jqgfzy.top/Article/details/gt2sxbhviic.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cheryme.top/Article/details/gt2fnlssitv.html

[Q64] 提交事务
来源：http://dali.fengsongda.top/Article/details/gt2tlheoyeg.html

COMMIT;
来源：http://dali.zycfv.cn/Article/details/gt2guwecwit.html

[Q65] 回滚事务
来源：http://dali.andypj.xyz/Article/details/gt2svkiyvao.html

ROLLBACK;
来源：http://dali.jyoumei.cn/Article/details/gt2deuiwycw.html

[Q66] 行锁查询
来源：http://dali.cdnleiting.top/Article/details/gt2vzzeaapl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.snrcjt.cn/Article/details/gt2czttfocr.html

[Q67] 设置隔离级别
来源：http://dali.nanxinkj.top/Article/details/gt2pbcbwwit.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhiwuduotai.top/Article/details/gt2yyswipsr.html

[Q68] 保存点
来源：http://dali.zhiwuduotai.top/Article/details/gt2wiuahcqm.html

SAVEPOINT sp1;
来源：http://dali.smart0.xyz/Article/details/gt2jdxbqjac.html

ROLLBACK TO sp1;
来源：http://dali.iojbl.cn/Article/details/gt2tpxranyg.html

[Q69] 查看执行计划
来源：http://dali.xylfe.cn/Article/details/gt2uruygboo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj202588.top/Article/details/gt2zsiluokv.html

[Q70] 更新统计信息
来源：http://dali.nanxinkj.top/Article/details/gt2lvpyeaqo.html

ANALYZE TABLE users;
来源：http://dali.nwbrower.top/Article/details/gt2zyveyfni.html

[Q71] 查看建表语句
来源：http://dali.guannengcc.top/Article/details/gt2qsxpwoxv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258888.top/Article/details/gt2pzuznqms.html

[Q72] 查看索引
来源：http://dali.shzxlz.cn/Article/details/gt2bpidapig.html

SHOW INDEX FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2covbyydc.html

[Q73] 查看表状态
来源：http://dali.hfpthk.cn/Article/details/gt2ghggrkhz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zgexzkzo.html

[Q74] 强制使用索引
来源：http://dali.iojbl.cn/Article/details/gt2lpkjkgmw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nwbrower.top/Article/details/gt2vmygtcqf.html

[Q75] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gt2fwgjcwyk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gt2jhsfxcro.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sysykeji.top/Article/details/gt2ubkdphoc.html

[Q76] 按天统计
来源：http://dali.guowangkeji.top/Article/details/gt2xrxxnhgi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jlsjyb.cn/Article/details/gt2dqjijgww.html

[Q77] 时间加减
来源：http://dali.jianghu66.top/Article/details/gt2scwccdgm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gotoacloud.top/Article/details/gt2ooochvsn.html

[Q78] 当前时间
来源：http://dali.wangdashe.top/Article/details/gt2nrjqidzu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shangyingyoupin.top/Article/details/gt2wqkuuiyx.html

[Q79] 字符串拼接
来源：http://dali.tanke756.top/Article/details/gt2zqegsaym.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.mhx1999.top/Article/details/gt2hxihlqtf.html

[Q80] 字符串截取
来源：http://dali.tianlin.xyz/Article/details/gt2zrrudfir.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2anbfjadf.html

[Q81] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gt2qxcrfcol.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2qslsuors.html

[Q82] 字符长度与字节长度
来源：http://dali.daria6918.cn/Article/details/gt2vutcsusx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2gcrsqnjd.html

[Q83] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2pumeylie.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2vzchtwgn.html

[Q84] 去除首尾空格
来源：http://dali.sxryk.cn/Article/details/gt2ozsnwjds.html

SELECT TRIM(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2bweezxbm.html

[Q85] 数值取整
来源：http://dali.hnxiangtu.top/Article/details/gt2dcsuyqql.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuxming.cn/Article/details/gt2gtvrdtht.html

[Q86] 读取 JSON 字段
来源：http://dali.gogol.net.cn/Article/details/gt2prabotwa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2frtrvzwy.html

[Q87] JSON 字段做条件
来源：http://dali.gotoacloud.top/Article/details/gt2ehxuxzwf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shuidangran.top/Article/details/gt2qabnuopp.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2alcugxjf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.9152youxi.cn/Article/details/gt2hwiizcmw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jnggeaed.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gt2icnwuhbf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jiagoushi.top/Article/details/gt2lrdcbpro.html

[Q90] 生成序号列
来源：http://dali.wangdashe.top/Article/details/gt2yyilugle.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hejgmsgt.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2jpwgzdcx.html

R. Bash 专题
来源：http://dali.xylfe.cn/Article/details/gt2kmgcosre.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2jdexnvdf.html

[R01] shebang 与严格模式
来源：http://dali.xinyue.icu/Article/details/gt2uixopnrs.html

#!/usr/bin/env bash
来源：http://dali.316326.xyz/Article/details/gt2ptnlhysk.html

set -euo pipefail
来源：http://dali.zhixingplan.top/Article/details/gt2midsbrma.html

[R02] 变量赋值与使用
来源：http://dali.dashuyun.cn/Article/details/gt2kfqgphay.html

name="Tom"; echo "$name"
来源：http://dali.pengpengdd.cyou/Article/details/gt2akwyvseh.html

[R03] 只读变量
来源：http://dali.sufxvd.cn/Article/details/gt2afwfgxzp.html

readonly PI=3.14
来源：http://dali.sweek.top/Article/details/gt2nrjiiaba.html

[R04] 位置参数
来源：http://dali.xziqi.cn/Article/details/gt2rruxwyej.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cheryme.top/Article/details/gt2govtfmbd.html

[R05] 参数默认值
来源：http://dali.chenlongwang.top/Article/details/gt2ekmcdlwj.html

name="${1:-default}"
来源：http://dali.hysaishi.cn/Article/details/gt2tlingube.html

[R06] 判断命令是否存在
来源：http://dali.zhongyouzk.top/Article/details/gt2zqsnjrtl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gt2gofjpwqk.html

[R07] if 判断文件
来源：http://dali.quarkkingdee.top/Article/details/gt2erfzbcdx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj202588.top/Article/details/gt2qmfwxuwb.html

[R08] 数值比较
来源：http://dali.guannengcc.top/Article/details/gt2egbrwsme.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gt2ovgxpirj.html

[R09] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gt2hwjiozea.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yongpay.top/Article/details/gt2nztybqaa.html

[R10] 正则匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqnvkboc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.quarkkingdee.top/Article/details/gt2nmprlqkc.html

[R11] case 多分支
来源：http://dali.bjfxy.top/Article/details/gt2dgibkyyg.html

case "$1" in
来源：http://dali.sufxvd.cn/Article/details/gt2szhumiqr.html

start) echo "启动" ;;
来源：http://dali.yanxiufei.cn/Article/details/gt2trcnedxs.html

stop)  echo "停止" ;;
来源：http://dali.haohaochexian.top/Article/details/gt2ybkcalhk.html

*)     echo "未知命令" ;;
来源：http://dali.zycfv.cn/Article/details/gt2amzxpkfp.html

esac
来源：http://dali.yj20258888.top/Article/details/gt2ghasrjze.html

[R12] for 遍历文件
来源：http://dali.kuanghao11.cn/Article/details/gt2dmxdcvea.html

for f in *.txt; do echo "$f"; done
来源：http://dali.andypj.xyz/Article/details/gt2aomrhdbk.html

[R13] for 计数循环
来源：http://dali.ybcxt.top/Article/details/gt2lknqioxs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2julnredo.html

[R14] C 风格 for
来源：http://dali.shangyingyoupin.top/Article/details/gt2cpugulvk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.birdmap.top/Article/details/gt2wahzsfnf.html

[R15] while 逐行读文件
来源：http://dali.cheryme.top/Article/details/gt2aqwvtors.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fengsongda.top/Article/details/gt2xzjrobpq.html

[R16] until 等待条件
来源：http://dali.smart0.xyz/Article/details/gt2klzxthtx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xozgchpy.html

[R17] 数组定义与取值
来源：http://dali.aizwys.cn/Article/details/gt2trqponrc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhixingplan.top/Article/details/gt2rcupddkg.html

[R18] 遍历数组
来源：http://dali.yuanzhike.top/Article/details/gt2ktxvzkto.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2gixdifoi.html

[R19] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gt2sdvevfas.html

echo "${#arr[@]}"
来源：http://dali.yj202588.top/Article/details/gt2qxcxhyse.html

[R20] 关联数组（字典）
来源：http://dali.dashuyun.cn/Article/details/gt2cgdcmcnx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shuidangran.top/Article/details/gt2avuaqleh.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gt2xgxvluza.html

echo "${#s}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ifrfrkgw.html

[R22] 截取子串
来源：http://dali.cucudq.cn/Article/details/gt2fssoyaoh.html

echo "${s:0:5}"
来源：http://dali.dashuyun.cn/Article/details/gt2esmdjhxl.html

[R23] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gt2ulqxdiob.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.iojbl.cn/Article/details/gt2nvclstet.html

[R24] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gt2rcmwvhxf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2guptjqdc.html

[R25] 去后缀 / 去前缀
来源：http://dali.cheryme.top/Article/details/gt2fqghslcr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aizwys.cn/Article/details/gt2lwcngarj.html

[R26] 命令替换
来源：http://dali.hfpthk.cn/Article/details/gt2uzndgooe.html

now=$(date +%F); echo "$now"
来源：http://dali.9152youxi.cn/Article/details/gt2nozpbdua.html

[R27] 算术展开
来源：http://dali.daria6918.cn/Article/details/gt2obnvubaz.html

echo $((1 + 2 * 3))
来源：http://dali.daxiang520.top/Article/details/gt2zwdawfpt.html

[R28] 浮点运算
来源：http://dali.smart0.xyz/Article/details/gt2guocpfyu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhiwuduotai.top/Article/details/gt2ohocaesw.html

[R29] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gt2uuznxyxh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2vkkgkpxd.html

[R30] 函数返回状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tazojnzv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgfzy.top/Article/details/gt2dekxiabp.html

[R31] 局部变量
来源：http://dali.daria6918.cn/Article/details/gt2ocjpatzo.html

f() { local x=1; echo "$x"; }
来源：http://dali.snrcjt.cn/Article/details/gt2btscyljw.html

[R32] 参数个数校验
来源：http://dali.shzxlz.cn/Article/details/gt2ujyehqyq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gt2tisugzbr.html

[R33] 捕获错误并提示行号
来源：http://dali.fengsongda.top/Article/details/gt2ymjwvwkd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ivvv.top/Article/details/gt2ewibsghg.html

[R34] 退出时清理
来源：http://dali.jinqigufen.top/Article/details/gt2azjgialt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gt2uezcdbqb.html

[R35] 后台执行并等待
来源：http://dali.feifeiyinyue.top/Article/details/gt2imtexdph.html


<!-- 参考信息 -->