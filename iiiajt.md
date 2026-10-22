代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.hammf.cn/Article/details/gt2ldnuupqf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuxming.cn/Article/details/gt2lsuejchj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2wuehxgvs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fivbgawe.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhoulong.xyz/Article/details/gt2yuzazbcj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenzaomai.com/Article/details/gt2wvmtfkus.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.316326.xyz/Article/details/gt2guhszvol.html

[P08] 处理浮点精度问题
来源：http://dali.c1oappe.top/Article/details/gt2qfixtpyx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhengqikj.top/Article/details/gt2xasatcby.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sufxvd.cn/Article/details/gt2txcyibvg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daria6918.cn/Article/details/gt2onhqdnnr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gt2qeejkppi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.aibaodan.cn/Article/details/gt2lfdkkzwq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nanxuanxn.top/Article/details/gt2ixoensfm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jdnjdyxx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.0kj1m.cn/Article/details/gt2miusqeuf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qqrbfjtb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qprxjsnj.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2gbkpluga.html

[Q01] 创建表
来源：http://dali.cheryme.top/Article/details/gt2rcmzepwb.html

CREATE TABLE users (
来源：http://dali.shzxlz.cn/Article/details/gt2chthusxf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gt2vorgxjrl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwmyukwp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.andypj.xyz/Article/details/gt2eadcusyy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dianchejie.cn/Article/details/gt2kmxkpmas.html

);
来源：http://dali.yj202588.top/Article/details/gt2jioyrcve.html

[Q02] 创建带外键的表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2whoarzpq.html

CREATE TABLE orders (
来源：http://dali.hongshengwenyu.top/Article/details/gt2oymrvjjc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gt2rxdwxiwb.html

user_id INT NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gt2dbhftgst.html

amount DECIMAL(10, 2),
来源：http://dali.cashguo.top/Article/details/gt2bcccnkax.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nwbrower.top/Article/details/gt2nqberelf.html

);
来源：http://dali.yanxiufei.cn/Article/details/gt2sbcmisbk.html

[Q03] 增加列
来源：http://dali.jqgfzy.top/Article/details/gt2mlupovma.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhixingplan.top/Article/details/gt2ssxknplb.html

[Q04] 修改列类型
来源：http://dali.xylfe.cn/Article/details/gt2viopizgp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.redwolf501.top/Article/details/gt2qnfejtur.html

[Q05] 重命名列
来源：http://dali.gogol.net.cn/Article/details/gt2jrncdcwm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.iojbl.cn/Article/details/gt2mxvszlsi.html

[Q06] 删除列
来源：http://dali.fzhhl.top/Article/details/gt2cokibzhz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xylfe.cn/Article/details/gt2breyupgw.html

[Q07] 删除表
来源：http://dali.wangshuangyany.cn/Article/details/gt2gzvbgnsw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinqigufen.top/Article/details/gt2xxpbxhsc.html

[Q08] 创建普通索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qwupjzpg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gt2cinaziqa.html

[Q09] 创建唯一索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hjlyngne.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gt2wrxniygl.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gt2lyryimix.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ppjwa.cn/Article/details/gt2obgilcdu.html

[Q11] 一次插入多行
来源：http://dali.snrcjt.cn/Article/details/gt2oqqpzyzj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj202588.top/Article/details/gt2ueuzufmd.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgfzy.top/Article/details/gt2stlqwddy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.iojbl.cn/Article/details/gt2bgxnbzdm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iaijngzi.html

[Q13] 忽略重复插入
来源：http://dali.316326.xyz/Article/details/gt2nwnqnlzg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnqzz.top/Article/details/gt2mnqhrscz.html

[Q14] 存在则更新（upsert）
来源：http://dali.yvedp.cn/Article/details/gt2fpftibno.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.smart0.xyz/Article/details/gt2fhktnzkv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cashguo.top/Article/details/gt2zmrimlez.html

[Q15] 查询全部
来源：http://dali.zhoulong.xyz/Article/details/gt2weltppyz.html

SELECT * FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2tkelofao.html

[Q16] 查询指定列
来源：http://dali.fengsongda.top/Article/details/gt2nkzesyxr.html

SELECT id, name FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ohlyrxni.html

[Q17] 条件查询
来源：http://dali.yj20258888.top/Article/details/gt2gxdfpuih.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2kjvqilyu.html

[Q18] 模糊匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2urjjmjne.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hongshengwenyu.top/Article/details/gt2mjlycxdw.html

[Q19] 范围查询
来源：http://dali.tian-w.cn/Article/details/gt2xrkbxmjp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.redwolf501.top/Article/details/gt2uavsedhq.html

[Q20] IN 列表
来源：http://dali.zhoulong.xyz/Article/details/gt2cbwpyxwx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.aibaodan.cn/Article/details/gt2qjfzmuwo.html

[Q21] 空值判断
来源：http://dali.birdmap.top/Article/details/gt2zczcjxjs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eaqbkyio.html

[Q22] 排序
来源：http://dali.iojbl.cn/Article/details/gt2gugcxtfz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangdashe.top/Article/details/gt2qfdqvzvu.html

[Q23] 分页
来源：http://dali.daxiang520.top/Article/details/gt2wipdllem.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ppfgnksn.html

[Q24] 去重
来源：http://dali.yj202588.top/Article/details/gt2acumokjq.html

SELECT DISTINCT city FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2prrhrpjj.html

[Q25] 只取前 N 条
来源：http://dali.chenjidiqi.icu/Article/details/gt2yfzszctr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhongyouzk.top/Article/details/gt2ljgejeyw.html

[Q26] 计数
来源：http://dali.sufxvd.cn/Article/details/gt2ihqcqqdk.html

SELECT COUNT(*) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2rjncfipm.html

[Q27] 条件计数
来源：http://dali.hnqzz.top/Article/details/gt2zublqwjt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2rsckpeqb.html

[Q28] 求和与平均
来源：http://dali.feifeiyinyue.top/Article/details/gt2ojziytzs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2vhapxrnr.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gt2vqjnldua.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2ibqnlfym.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2djfqlcdf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gt2yceissjp.html

[Q31] 分组后过滤
来源：http://dali.birdmap.top/Article/details/gt2loxhynia.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnxiangtu.top/Article/details/gt2onfaytnq.html

[Q32] 分组拼接字符串
来源：http://dali.shuidangran.top/Article/details/gt2zxlszmpe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gt2lqbcjqgy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuanzhike.top/Article/details/gt2vaiafiwk.html

[Q33] 多列分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2zvabdlnp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhiwuduotai.top/Article/details/gt2owjehalr.html

[Q34] 每组取第一条
来源：http://dali.ydzc1.top/Article/details/gt2arqdxphx.html

SELECT * FROM (
来源：http://dali.316326.xyz/Article/details/gt2npsfpgxm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gogol.net.cn/Article/details/gt2fkdvbpxq.html

) t WHERE rn = 1;
来源：http://dali.sysykeji.top/Article/details/gt2yqeghgdm.html

[Q35] 内连接
来源：http://dali.shzxlz.cn/Article/details/gt2tlyrjzqk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gt2pqbmqlug.html

[Q36] 左连接
来源：http://dali.0kj1m.cn/Article/details/gt2yfeednwn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gt2mbxuwcmf.html

[Q37] 右连接
来源：http://dali.0kj1m.cn/Article/details/gt2lryyothx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ydzc1.top/Article/details/gt2hqflhnen.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ehwqpu.com/Article/details/gt2vcxazzfg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qkorcsoj.html

[Q39] 自连接（查上下级）
来源：http://dali.pengpengdd.cyou/Article/details/gt2eztoiduc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nwbrower.top/Article/details/gt2mwqhgwfb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jrfgitww.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hysaishi.cn/Article/details/gt2irqdeoym.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shuidangran.top/Article/details/gt2fkyujjnt.html

[Q41] 多表连接
来源：http://dali.yueranfly.top/Article/details/gt2mtvqzsis.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daxiang520.top/Article/details/gt2vlhlhlvv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.feifeiyinyue.top/Article/details/gt2vsyozojp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bdjzpzuh.html

[Q42] 连接条件附加过滤
来源：http://dali.daxiang520.top/Article/details/gt2ikqvcydj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.kuanghao11.cn/Article/details/gt2rezcetbt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sysykeji.top/Article/details/gt2rbhavsut.html

[Q43] 标量子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cjymohml.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ehwqpu.com/Article/details/gt2nkovuxxm.html

[Q44] IN 子查询
来源：http://dali.jyoumei.cn/Article/details/gt2qhzlyrzq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fengsongda.top/Article/details/gt2mpttbgab.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigfzy.top/Article/details/gt2zqdjxxjz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gt2qsbhdlka.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hysaishi.cn/Article/details/gt2hzprzkce.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnxiangtu.top/Article/details/gt2oyhteyba.html

[Q47] 与平均值比较
来源：http://dali.kuanghao11.cn/Article/details/gt2zzhzlanc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yuxming.cn/Article/details/gt2vkczfzbl.html

[Q48] CTE 公用表表达式
来源：http://dali.c1oappe.top/Article/details/gt2fjajmttu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yueranfly.top/Article/details/gt2lamqbbbs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.c1oappe.top/Article/details/gt2edhatnzr.html

[Q49] 更新单行
来源：http://dali.redwolf501.top/Article/details/gt2vpdbtjcv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gt2lbrfrwcm.html

[Q50] 批量更新
来源：http://dali.ehwqpu.com/Article/details/gt2nmlekkcr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.316326.xyz/Article/details/gt2vioqcxcz.html

[Q51] 用子查询更新
来源：http://dali.guowangkeji.top/Article/details/gt2uteknpqg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xylfe.cn/Article/details/gt2muflratu.html

[Q52] 删除指定行
来源：http://dali.ppjwa.cn/Article/details/gt2xiihupjb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gt2fqylqers.html

[Q53] 按条件删除
来源：http://dali.yuxming.cn/Article/details/gt2ptyczbfj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgfzy.top/Article/details/gt2jjbdjyjt.html

[Q54] 清空表
来源：http://dali.iojbl.cn/Article/details/gt2xukitjbd.html

TRUNCATE TABLE logs;
来源：http://dali.cdnleiting.top/Article/details/gt2jdmmoeic.html

[Q55] 排名（并列占位）
来源：http://dali.fengsongda.top/Article/details/gt2neakeehi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gt2pawtbahq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gzhubu.top/Article/details/gt2ljcwaabn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gt2zfxnpkdi.html

[Q57] 行号
来源：http://dali.pengpengdd.cyou/Article/details/gt2sciocowk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2xzmvzkos.html

[Q58] 累计求和
来源：http://dali.gaohongyu789.top/Article/details/gt2lvqldheg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cucudq.cn/Article/details/gt2ublpcyhx.html

[Q59] 分组内累计
来源：http://dali.sweek.top/Article/details/gt2yxskemxg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gt2ipkrmyly.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgufenzy.top/Article/details/gt2lazfbyhq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hysaishi.cn/Article/details/gt2ccrprcif.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2nalkiubc.html

[Q61] 移动平均
来源：http://dali.ivvv.top/Article/details/gt2akqgjpff.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vgntgrvs.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gt2kuyctkyt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gt2keumipbz.html

[Q63] 开启事务
来源：http://dali.jinqigufen.top/Article/details/gt2ozfgrwti.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shuidangran.top/Article/details/gt2ccalghvm.html

[Q64] 提交事务
来源：http://dali.9152youxi.cn/Article/details/gt2mebufalq.html

COMMIT;
来源：http://dali.yonumen.top/Article/details/gt2xvjupxrw.html

[Q65] 回滚事务
来源：http://dali.nwbrower.top/Article/details/gt2mlaxcsan.html

ROLLBACK;
来源：http://dali.sufxvd.cn/Article/details/gt2hunbwdav.html

[Q66] 行锁查询
来源：http://dali.snrcjt.cn/Article/details/gt2muwqqxgq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnqzz.top/Article/details/gt2maxawhyi.html

[Q67] 设置隔离级别
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghtvtxci.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dashuyun.cn/Article/details/gt2geyucetx.html

[Q68] 保存点
来源：http://dali.guowangkeji.top/Article/details/gt2esoyiopc.html

SAVEPOINT sp1;
来源：http://dali.jqgufenzy.top/Article/details/gt2afonodnj.html

ROLLBACK TO sp1;
来源：http://dali.jqgfzy.top/Article/details/gt2svshfqah.html

[Q69] 查看执行计划
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kjlcmkjq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shangyingyoupin.top/Article/details/gt2cruxgpso.html

[Q70] 更新统计信息
来源：http://dali.yueranfly.top/Article/details/gt2kbxyzjnl.html

ANALYZE TABLE users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xipllxao.html

[Q71] 查看建表语句
来源：http://dali.birdmap.top/Article/details/gt2qaqvuisz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenzaomai.com/Article/details/gt2yadgjxbl.html

[Q72] 查看索引
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fmgwwzip.html

SHOW INDEX FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2oytevumx.html

[Q73] 查看表状态
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lfzhzzxb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hfpthk.cn/Article/details/gt2gpihywoj.html

[Q74] 强制使用索引
来源：http://dali.mhx1999.top/Article/details/gt2xbcsswhp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.svipenyu.cn/Article/details/gt2lbzmiilb.html

[Q75] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gt2uhdflqgf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2gcyfbivh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.c1oappe.top/Article/details/gt2xqvvlral.html

[Q76] 按天统计
来源：http://dali.jinqigfzy.top/Article/details/gt2eettktxi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jyoumei.cn/Article/details/gt2ujzoxena.html

[Q77] 时间加减
来源：http://dali.feifeiyinyue.top/Article/details/gt2iqhrdchs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.smart0.xyz/Article/details/gt2njxtkjse.html

[Q78] 当前时间
来源：http://dali.vqdsnc.cn/Article/details/gt2xobsjqqa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dianchejie.cn/Article/details/gt2jfjsiuvz.html

[Q79] 字符串拼接
来源：http://dali.meibo888.top/Article/details/gt2tntqzyln.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.havefunace.top/Article/details/gt2vkagwxji.html

[Q80] 字符串截取
来源：http://dali.wangshuangyany.cn/Article/details/gt2uhjwehin.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2xaeeezot.html

[Q81] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gt2awuhrlac.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2evkrkdrq.html

[Q82] 字符长度与字节长度
来源：http://dali.dashuyun.cn/Article/details/gt2hcmpoqws.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2dcqothfr.html

[Q83] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gt2tslccmmi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2rcmwneqz.html

[Q84] 去除首尾空格
来源：http://dali.jyoumei.cn/Article/details/gt2jgrxydgt.html

SELECT TRIM(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2osuoqtmt.html

[Q85] 数值取整
来源：http://dali.dashuyun.cn/Article/details/gt2xtxwluwp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.snrcjt.cn/Article/details/gt2mxgdgtnt.html

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gt2bqhsdime.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhengqikj.top/Article/details/gt2mrpgyglp.html

[Q87] JSON 字段做条件
来源：http://dali.zhongyouzk.top/Article/details/gt2jzhrwuod.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hammf.cn/Article/details/gt2sinfzjfq.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangshuangyany.cn/Article/details/gt2vbtluipk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhixingplan.top/Article/details/gt2nyxnyvfc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2iirpxzum.html

[Q89] 判断表是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2qeptnmpk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zukddiqn.html

[Q90] 生成序号列
来源：http://dali.ppjwa.cn/Article/details/gt2eckucltv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cheryme.top/Article/details/gt2ahpfuvel.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2yrlexwih.html

R. Bash 专题
来源：http://dali.fengsongda.top/Article/details/gt2qexssodw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2qviztqms.html

[R01] shebang 与严格模式
来源：http://dali.ydzc1.top/Article/details/gt2gwemcqhl.html

#!/usr/bin/env bash
来源：http://dali.jyoumei.cn/Article/details/gt2bdslhyyg.html

set -euo pipefail
来源：http://dali.ppjwa.cn/Article/details/gt2cotbnymm.html

[R02] 变量赋值与使用
来源：http://dali.haohaochexian.top/Article/details/gt2vfotnagq.html

name="Tom"; echo "$name"
来源：http://dali.guannengcc.top/Article/details/gt2cqyeqiks.html

[R03] 只读变量
来源：http://dali.meibo888.top/Article/details/gt2mdlqukmh.html

readonly PI=3.14
来源：http://dali.tanke756.top/Article/details/gt2iiiycbbv.html

[R04] 位置参数
来源：http://dali.jlsjyb.cn/Article/details/gt2yepkpoeb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.quarkkingdee.top/Article/details/gt2ldedbzkd.html

[R05] 参数默认值
来源：http://dali.wangshuangyany.cn/Article/details/gt2lmepuzjg.html

name="${1:-default}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2sexrtxaw.html

[R06] 判断命令是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ndosjlnx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gt2snstvvtq.html

[R07] if 判断文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mxckznom.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tanke756.top/Article/details/gt2eywqmmhu.html

[R08] 数值比较
来源：http://dali.fzhhl.top/Article/details/gt2njhwupuk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2mliexhvv.html

[R09] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gt2dlqznnlq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yueranfly.top/Article/details/gt2uibsbtik.html

[R10] 正则匹配
来源：http://dali.xziqi.cn/Article/details/gt2cfdxciyk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sglcxkcn.html

[R11] case 多分支
来源：http://dali.sweek.top/Article/details/gt2axskgjcq.html

case "$1" in
来源：http://dali.jqgfzy.top/Article/details/gt2agyagajh.html

start) echo "启动" ;;
来源：http://dali.cdnleiting.top/Article/details/gt2iqwsudbe.html

stop)  echo "停止" ;;
来源：http://dali.nwbrower.top/Article/details/gt2gafzdohm.html

*)     echo "未知命令" ;;
来源：http://dali.316326.xyz/Article/details/gt2ioqrftpt.html

esac
来源：http://dali.birdmap.top/Article/details/gt2nqleurgi.html

[R12] for 遍历文件
来源：http://dali.nanxinkj.top/Article/details/gt2zshdwrvy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258888.top/Article/details/gt2msbwfrvh.html

[R13] for 计数循环
来源：http://dali.yj202588.top/Article/details/gt2vhywazne.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gt2ttqltfsz.html

[R14] C 风格 for
来源：http://dali.shzxlz.cn/Article/details/gt2knryzxcl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gt2lnsadvmn.html

[R15] while 逐行读文件
来源：http://dali.daria6918.cn/Article/details/gt2ebkicqpp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.meibo888.top/Article/details/gt2cqpruswn.html

[R16] until 等待条件
来源：http://dali.yanxiufei.cn/Article/details/gt2namvgucq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gt2tngxnkys.html

[R17] 数组定义与取值
来源：http://dali.iojbl.cn/Article/details/gt2hpgvyevh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pycfn.com/Article/details/gt2dkykandf.html

[R18] 遍历数组
来源：http://dali.fzhhl.top/Article/details/gt2kpgokeiv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tian-w.cn/Article/details/gt2doonwajc.html

[R19] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gt2lqxbyeue.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rruqgafu.html

[R20] 关联数组（字典）
来源：http://dali.zhoulong.xyz/Article/details/gt2yislsvjs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.iojbl.cn/Article/details/gt2gqduyokc.html

[R21] 字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2yomgvigy.html

echo "${#s}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xcnygqea.html

[R22] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gt2qnxlnejk.html

echo "${s:0:5}"
来源：http://dali.jiagoushi.top/Article/details/gt2befgetag.html

[R23] 字符串替换
来源：http://dali.dianchejie.cn/Article/details/gt2zwutrjjp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.bjfxy.top/Article/details/gt2hooasfyw.html

[R24] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2agzlolgd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2tsygwgea.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258.top/Article/details/gt2eixoymrl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yvedp.cn/Article/details/gt2mpbxwhvt.html

[R26] 命令替换
来源：http://dali.ybcxt.top/Article/details/gt2wxvnberb.html

now=$(date +%F); echo "$now"
来源：http://dali.cheryme.top/Article/details/gt2pbxrsubf.html

[R27] 算术展开
来源：http://dali.cdnleiting.top/Article/details/gt2ufwjzwwe.html

echo $((1 + 2 * 3))
来源：http://dali.yj202588.top/Article/details/gt2tdobhzud.html

[R28] 浮点运算
来源：http://dali.guannengcc.top/Article/details/gt2zjejoucn.html

echo "scale=2; 10/3" | bc
来源：http://dali.havefunace.top/Article/details/gt2jwibbufj.html

[R29] 定义函数
来源：http://dali.316326.xyz/Article/details/gt2nkvzyvtu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhongyouzk.top/Article/details/gt2gpvokckf.html

[R30] 函数返回状态码
来源：http://dali.gzhubu.top/Article/details/gt2jtunihla.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgufenzy.top/Article/details/gt2ubzaumjc.html

[R31] 局部变量
来源：http://dali.haohaochexian.top/Article/details/gt2xqpoycoo.html

f() { local x=1; echo "$x"; }
来源：http://dali.sysykeji.top/Article/details/gt2btzrpkma.html

[R32] 参数个数校验
来源：http://dali.shzxlz.cn/Article/details/gt2hlquyfsf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gt2jrbfetsq.html

[R33] 捕获错误并提示行号
来源：http://dali.gogol.net.cn/Article/details/gt2pbgrsdgv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuxming.cn/Article/details/gt2mrdgqakq.html

[R34] 退出时清理
来源：http://dali.guowangkeji.top/Article/details/gt2swgtcclz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gt2dvfcyytu.html

[R35] 后台执行并等待
来源：http://dali.shangyingyoupin.top/Article/details/gt2ydhxoyop.html


<!-- 参考信息 -->