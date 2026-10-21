代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yangfankeji.com/Article/details/gtvwokvxic.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jlsjyb.cn/Article/details/gtxyytcqnx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.feifeiyinyue.top/Article/details/gtodxcelne.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gtjvoiqcjg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gtdlsbjktt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.0kj1m.cn/Article/details/gtogtqulat.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ydzc1.top/Article/details/gtyzbwnwra.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigfzy.top/Article/details/gtnmooxfrx.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtwafnizsy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmwxxlei.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtowfcoqws.html

[Q01] 创建表
来源：http://dali.yongpay.top/Article/details/gtmwlzuukx.html

CREATE TABLE users (
来源：http://dali.9152youxi.cn/Article/details/gtpzqxsoid.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gtsvyvsskx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gthpggiwni.html

email VARCHAR(100) UNIQUE,
来源：http://dali.birdmap.top/Article/details/gtwtvkbepx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgufenzy.top/Article/details/gtzyrqyute.html

);
来源：http://dali.hywenlv.cn/Article/details/gtnwddlcfk.html

[Q02] 创建带外键的表
来源：http://dali.iojbl.cn/Article/details/gtyresmvju.html

CREATE TABLE orders (
来源：http://dali.tian-w.cn/Article/details/gtcuttbmao.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gtcbkigrda.html

user_id INT NOT NULL,
来源：http://dali.yj202588.top/Article/details/gtohcyyrtj.html

amount DECIMAL(10, 2),
来源：http://dali.smart0.xyz/Article/details/gtblkanqip.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxuanxn.top/Article/details/gtwbkadhjk.html

);
来源：http://dali.yuxming.cn/Article/details/gtzegambct.html

[Q03] 增加列
来源：http://dali.xuanzx.com/Article/details/gtndsnoobt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jyoumei.cn/Article/details/gtcbuydwyd.html

[Q04] 修改列类型
来源：http://dali.nanxuanxn.top/Article/details/gtxlscjdsw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nanxuanxn.top/Article/details/gtaxzakesl.html

[Q05] 重命名列
来源：http://dali.zhixingplan.top/Article/details/gtvyqnszoz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gzhubu.top/Article/details/gtxpwhkkkn.html

[Q06] 删除列
来源：http://dali.zdqjudy.top/Article/details/gtsbfxtrjv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuanzhike.top/Article/details/gttwjakbus.html

[Q07] 删除表
来源：http://dali.dashuyun.cn/Article/details/gtoxdtuair.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pycfn.com/Article/details/gthkcyuitl.html

[Q08] 创建普通索引
来源：http://dali.aizwys.cn/Article/details/gtxnmjxlau.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gticdahiww.html

[Q09] 创建唯一索引
来源：http://dali.cdnleiting.top/Article/details/gtiikaskak.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dianchejie.cn/Article/details/gtqkycbnwk.html

[Q10] 插入单行
来源：http://dali.yonumen.top/Article/details/gterhtatni.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtvlwmklnh.html

[Q11] 一次插入多行
来源：http://dali.yanxiufei.cn/Article/details/gtxxffdhyr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ydzc1.top/Article/details/gthfrepias.html

[Q12] 插入后取自增 ID
来源：http://dali.jinqigfzy.top/Article/details/gtwsggjird.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sufxvd.cn/Article/details/gtgzmzqkjl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sysykeji.top/Article/details/gteguuuxys.html

[Q13] 忽略重复插入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyshjasku.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.316326.xyz/Article/details/gtuwkeyzqp.html

[Q14] 存在则更新（upsert）
来源：http://dali.cdnleiting.top/Article/details/gtiburgxah.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangdashe.top/Article/details/gtzcaahjpi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.9152youxi.cn/Article/details/gttfieuwsq.html

[Q15] 查询全部
来源：http://dali.ehwqpu.com/Article/details/gtjprpfboz.html

SELECT * FROM users;
来源：http://dali.pycfn.com/Article/details/gtmunmmxgy.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gtrugaqxns.html

SELECT id, name FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtafsxgghu.html

[Q17] 条件查询
来源：http://dali.yj202588.top/Article/details/gtmutbqmxx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gzhubu.top/Article/details/gtjxzprsmf.html

[Q18] 模糊匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtgyecddaf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlehgotij.html

[Q19] 范围查询
来源：http://dali.yonumen.top/Article/details/gtzamtyoac.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ehwqpu.com/Article/details/gtgyxgmxxh.html

[Q20] IN 列表
来源：http://dali.tian-w.cn/Article/details/gtunspxfzq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtabyojtly.html

[Q21] 空值判断
来源：http://dali.ppjwa.cn/Article/details/gtkeaaueyn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj202588.top/Article/details/gthoxgacjx.html

[Q22] 排序
来源：http://dali.yuxming.cn/Article/details/gtgwvfbzkz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.guowangkeji.top/Article/details/gtkjgivtef.html

[Q23] 分页
来源：http://dali.0kj1m.cn/Article/details/gtwnozaajs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhongyouzk.top/Article/details/gtletyelzv.html

[Q24] 去重
来源：http://dali.ybcxt.top/Article/details/gtfxvkmbua.html

SELECT DISTINCT city FROM users;
来源：http://dali.zycfv.cn/Article/details/gtcqpmamgu.html

[Q25] 只取前 N 条
来源：http://dali.yueranfly.top/Article/details/gtjbxrwmkd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hysaishi.cn/Article/details/gtgzxmicvs.html

[Q26] 计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjwbwgju.html

SELECT COUNT(*) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtiphecuid.html

[Q27] 条件计数
来源：http://dali.tanke756.top/Article/details/gtoxfxlrdj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtotoevfor.html

[Q28] 求和与平均
来源：http://dali.hnxiangtu.top/Article/details/gtqelvtdez.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtbajdbzkg.html

[Q29] 最大最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynujftgo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yongpay.top/Article/details/gtgtudozfq.html

[Q30] 分组统计
来源：http://dali.xinyue.icu/Article/details/gtcrmovgwv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtodfkfteb.html

[Q31] 分组后过滤
来源：http://dali.sufxvd.cn/Article/details/gtkulphaab.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yanxiufei.cn/Article/details/gtjeztpimk.html

[Q32] 分组拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtpibmkdwo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gtyqxjcwgo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.havefunace.top/Article/details/gtriouiazh.html

[Q33] 多列分组
来源：http://dali.tian-w.cn/Article/details/gtwlszdvra.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.feifeiyinyue.top/Article/details/gtfpejgwsr.html

[Q34] 每组取第一条
来源：http://dali.chenlongwang.top/Article/details/gtznfbrfon.html

SELECT * FROM (
来源：http://dali.tanke756.top/Article/details/gtdkohdakk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.meibo888.top/Article/details/gtsjayooxy.html

) t WHERE rn = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtmqdyedod.html

[Q35] 内连接
来源：http://dali.shzxlz.cn/Article/details/gticbpbswr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gtrjemuend.html

[Q36] 左连接
来源：http://dali.andypj.xyz/Article/details/gtnzwwoglh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gtlmcdtzup.html

[Q37] 右连接
来源：http://dali.hongshengwenyu.top/Article/details/gtitgvhqdx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtclwehjhu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daria6918.cn/Article/details/gtgaqfovzs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jianghu66.top/Article/details/gtcvhrhpsg.html

[Q39] 自连接（查上下级）
来源：http://dali.ehwqpu.com/Article/details/gtrbhmvnyh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daria6918.cn/Article/details/gtpfztizpj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenjidiqi.icu/Article/details/gtetaedxcn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nwbrower.top/Article/details/gtlhfmnqsd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zdqjudy.top/Article/details/gtkpsrnqju.html

[Q41] 多表连接
来源：http://dali.yuxming.cn/Article/details/gtbncztkpf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gaohongyu789.top/Article/details/gthaltqqba.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwfhuudc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tanke756.top/Article/details/gtnvhwoesw.html

[Q42] 连接条件附加过滤
来源：http://dali.ehwqpu.com/Article/details/gteamnxjli.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hfpthk.cn/Article/details/gtokavzhlc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yongpay.top/Article/details/gtqcrmsgrw.html

[Q43] 标量子查询
来源：http://dali.zhixingplan.top/Article/details/gtyssdoykz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gogol.net.cn/Article/details/gtpbefvlex.html

[Q44] IN 子查询
来源：http://dali.hnqzz.top/Article/details/gtwqkxkdvh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ydzc1.top/Article/details/gtezcruvak.html

[Q45] EXISTS 判断存在
来源：http://dali.9152youxi.cn/Article/details/gtantulqay.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gthjcduxoz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yvedp.cn/Article/details/gtqwhmakhe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hfpthk.cn/Article/details/gteawqoanr.html

[Q47] 与平均值比较
来源：http://dali.hysaishi.cn/Article/details/gtchlojsak.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sweek.top/Article/details/gtqvofegmy.html

[Q48] CTE 公用表表达式
来源：http://dali.dashuyun.cn/Article/details/gtcyzclyyc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlagnfnhh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gzhubu.top/Article/details/gtgyssjuvx.html

[Q49] 更新单行
来源：http://dali.hnqzz.top/Article/details/gtzaejvfym.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gtejzjdnwc.html

[Q50] 批量更新
来源：http://dali.ydzc1.top/Article/details/gttedshabx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jianghu66.top/Article/details/gtomzswjvz.html

[Q51] 用子查询更新
来源：http://dali.zdqjudy.top/Article/details/gtdpgpofhb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.9152youxi.cn/Article/details/gtrmkuzlhe.html

[Q52] 删除指定行
来源：http://dali.cucudq.cn/Article/details/gtibkxbygl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzqiqkqw.html

[Q53] 按条件删除
来源：http://dali.cashguo.top/Article/details/gtxcaleupx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gtxczmnbyx.html

[Q54] 清空表
来源：http://dali.sufxvd.cn/Article/details/gtzofbcgvv.html

TRUNCATE TABLE logs;
来源：http://dali.tianlin.xyz/Article/details/gtqzbeicek.html

[Q55] 排名（并列占位）
来源：http://dali.cucudq.cn/Article/details/gtvunhatcp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gtcxltbgqj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shangyingyoupin.top/Article/details/gtjypkdfnk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gtdcfofvwj.html

[Q57] 行号
来源：http://dali.cdnleiting.top/Article/details/gthlsxlxis.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aizwys.cn/Article/details/gtnwwcvynt.html

[Q58] 累计求和
来源：http://dali.chenzaomai.com/Article/details/gtqgfqhkzd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtbbbripce.html

[Q59] 分组内累计
来源：http://dali.zdqjudy.top/Article/details/gtlrravdcm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtyzewtovx.html

[Q60] 取上一行 / 下一行
来源：http://dali.ybcxt.top/Article/details/gtvsmuriux.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nwbrower.top/Article/details/gtmpnumkbw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gthabjibxg.html

[Q61] 移动平均
来源：http://dali.gotoacloud.top/Article/details/gtjisgagvv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtwqmvnxjm.html

[Q62] 分组占比
来源：http://dali.zycfv.cn/Article/details/gtbkuxrhbe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtnfxjqcej.html

[Q63] 开启事务
来源：http://dali.gotoacloud.top/Article/details/gtsmrrbjom.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jlsjyb.cn/Article/details/gtkvopukcr.html

[Q64] 提交事务
来源：http://dali.nwbrower.top/Article/details/gtlvydjncl.html

COMMIT;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvakrhpor.html

[Q65] 回滚事务
来源：http://dali.svipenyu.cn/Article/details/gtrpacrrnu.html

ROLLBACK;
来源：http://dali.yuxming.cn/Article/details/gtgggntxoq.html

[Q66] 行锁查询
来源：http://dali.zycfv.cn/Article/details/gtijwpvjyy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yonumen.top/Article/details/gtbtpjgibz.html

[Q67] 设置隔离级别
来源：http://dali.aizwys.cn/Article/details/gtkncqyxex.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yangfankeji.com/Article/details/gttqhfftvb.html

[Q68] 保存点
来源：http://dali.jyoumei.cn/Article/details/gtihnbwtpd.html

SAVEPOINT sp1;
来源：http://dali.hnxiangtu.top/Article/details/gtxfthrpme.html

ROLLBACK TO sp1;
来源：http://dali.hnxiangtu.top/Article/details/gtctbneljt.html

[Q69] 查看执行计划
来源：http://dali.dashuyun.cn/Article/details/gtyezocsbw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.feifeiyinyue.top/Article/details/gtqjxkuesw.html

[Q70] 更新统计信息
来源：http://dali.yuxming.cn/Article/details/gtitdeqygt.html

ANALYZE TABLE users;
来源：http://dali.jqgfzy.top/Article/details/gtcqqreydc.html

[Q71] 查看建表语句
来源：http://dali.aizwys.cn/Article/details/gtgcsenpdg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.kuanghao11.cn/Article/details/gtjljncoah.html

[Q72] 查看索引
来源：http://dali.zdqjudy.top/Article/details/gtwrtcqpcp.html

SHOW INDEX FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtypodipzu.html

[Q73] 查看表状态
来源：http://dali.yonumen.top/Article/details/gtoieypntz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tianlin.xyz/Article/details/gtzplnfmry.html

[Q74] 强制使用索引
来源：http://dali.gotoacloud.top/Article/details/gtguyjhmks.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangdashe.top/Article/details/gtguoohpha.html

[Q75] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtqovxnoqx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtecswnsrz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shuidangran.top/Article/details/gtyidqsbdt.html

[Q76] 按天统计
来源：http://dali.9152youxi.cn/Article/details/gtifdspwpx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.snrcjt.cn/Article/details/gtdeesepxw.html

[Q77] 时间加减
来源：http://dali.pycfn.com/Article/details/gtpnwawstx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yangfankeji.com/Article/details/gtltjnfozl.html

[Q78] 当前时间
来源：http://dali.pycfn.com/Article/details/gtrsnjiffp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gotoacloud.top/Article/details/gtltsxfejo.html

[Q79] 字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gtgeqixxey.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.havefunace.top/Article/details/gtqmnpxuxe.html

[Q80] 字符串截取
来源：http://dali.hfpthk.cn/Article/details/gtvwgbeysm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtmnvydzif.html

[Q81] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gtndzetggm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cashguo.top/Article/details/gtgbyszmfq.html

[Q82] 字符长度与字节长度
来源：http://dali.wangdashe.top/Article/details/gtjvwkajwg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtdzzlsczp.html

[Q83] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gtxnbiuaxc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoaovfibv.html

[Q84] 去除首尾空格
来源：http://dali.gaohongyu789.top/Article/details/gtxsqqpxqr.html

SELECT TRIM(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtfgtrjtyv.html

[Q85] 数值取整
来源：http://dali.ivvv.top/Article/details/gtfkhmgcij.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cdnleiting.top/Article/details/gtnjegrnpi.html

[Q86] 读取 JSON 字段
来源：http://dali.sufxvd.cn/Article/details/gtzxnliucs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jiagoushi.top/Article/details/gtbmofical.html

[Q87] JSON 字段做条件
来源：http://dali.hammf.cn/Article/details/gtnjoolhsw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258888.top/Article/details/gtswtqagyv.html

[Q88] 行转列（条件聚合）
来源：http://dali.jyoumei.cn/Article/details/gtdpqhxyny.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.0kj1m.cn/Article/details/gtdkecajpj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gtmeumqspn.html

[Q89] 判断表是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtqocagkck.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhixingplan.top/Article/details/gtpcdopljj.html

[Q90] 生成序号列
来源：http://dali.xuetiantiany.cn/Article/details/gtmjzwavnx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgufenzy.top/Article/details/gtzuyqfvdl.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtluuvjzzf.html

R. Bash 专题
来源：http://dali.xuetiantiany.cn/Article/details/gtlmqbccol.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtprjuqjnv.html

[R01] shebang 与严格模式
来源：http://dali.yueranfly.top/Article/details/gtedrozwdn.html

#!/usr/bin/env bash
来源：http://dali.smart0.xyz/Article/details/gtjcdqetcq.html

set -euo pipefail
来源：http://dali.yonumen.top/Article/details/gtgfxuszam.html

[R02] 变量赋值与使用
来源：http://dali.aizwys.cn/Article/details/gtbzdwveoc.html

name="Tom"; echo "$name"
来源：http://dali.yuanzhike.top/Article/details/gtmcvmxoab.html

[R03] 只读变量
来源：http://dali.xziqi.cn/Article/details/gtluuiazno.html

readonly PI=3.14
来源：http://dali.chenzaomai.com/Article/details/gtjnascjum.html

[R04] 位置参数
来源：http://dali.9152youxi.cn/Article/details/gtzumankbt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nwbrower.top/Article/details/gtpjxjuinq.html

[R05] 参数默认值
来源：http://dali.nwbrower.top/Article/details/gtspyektkf.html

name="${1:-default}"
来源：http://dali.hnqzz.top/Article/details/gtbpfpnjdh.html

[R06] 判断命令是否存在
来源：http://dali.pycfn.com/Article/details/gtxrwpwdlt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gtnwqakevw.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gtvtmhcgoc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daria6918.cn/Article/details/gttdjlewtg.html

[R08] 数值比较
来源：http://dali.pycfn.com/Article/details/gteltfreqb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jianghu66.top/Article/details/gtixlzbilr.html

[R09] 字符串比较
来源：http://dali.nanxinkj.top/Article/details/gtacsmtrpu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtfgznwghk.html

[R10] 正则匹配
来源：http://dali.fengsongda.top/Article/details/gtkebvknrv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.iojbl.cn/Article/details/gtddoribzo.html

[R11] case 多分支
来源：http://dali.yuanzhike.top/Article/details/gtoalzmcyi.html

case "$1" in
来源：http://dali.mhx1999.top/Article/details/gtmmqmhhbx.html

start) echo "启动" ;;
来源：http://dali.bjfxy.top/Article/details/gtwywivuft.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gtlymlbsst.html

*)     echo "未知命令" ;;
来源：http://dali.jiagoushi.top/Article/details/gtytukhuxl.html

esac
来源：http://dali.pengpengdd.cyou/Article/details/gttizspkoj.html

[R12] for 遍历文件
来源：http://dali.0kj1m.cn/Article/details/gtoovrdkgy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ydzc1.top/Article/details/gtpikehhud.html

[R13] for 计数循环
来源：http://dali.sxryk.cn/Article/details/gttezzdoxu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtyyweapdf.html

[R14] C 风格 for
来源：http://dali.svipenyu.cn/Article/details/gtcpqhjwmx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnvqwjoo.html

[R15] while 逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrhhqyxj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cashguo.top/Article/details/gtrwzfbsos.html

[R16] until 等待条件
来源：http://dali.ybcxt.top/Article/details/gtgprkuuww.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gtfjantpst.html

[R17] 数组定义与取值
来源：http://dali.daxiang520.top/Article/details/gtlplykqtq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.bjfxy.top/Article/details/gtndfrdkni.html

[R18] 遍历数组
来源：http://dali.hnqzz.top/Article/details/gtarlgdqfd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jqgfzy.top/Article/details/gtyeguaynd.html

[R19] 数组长度
来源：http://dali.ivvv.top/Article/details/gtdqrtgzua.html

echo "${#arr[@]}"
来源：http://dali.dashuyun.cn/Article/details/gturrkankc.html

[R20] 关联数组（字典）
来源：http://dali.redwolf501.top/Article/details/gthjgorcbl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xylfe.cn/Article/details/gtjbvxcony.html

[R21] 字符串长度
来源：http://dali.shzxlz.cn/Article/details/gtrobzltit.html

echo "${#s}"
来源：http://dali.ybcxt.top/Article/details/gtekqmvhqg.html

[R22] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gtgdowpqta.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnohdjxj.html

[R23] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gtynmhfria.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dianchejie.cn/Article/details/gtjvdgpwtz.html

[R24] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gtpzrxfomp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.smart0.xyz/Article/details/gtmrkuboln.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuetiantiany.cn/Article/details/gtlbnyvdpn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.andypj.xyz/Article/details/gthfmplmlx.html

[R26] 命令替换
来源：http://dali.svipenyu.cn/Article/details/gtchhulaqx.html

now=$(date +%F); echo "$now"
来源：http://dali.meibo888.top/Article/details/gtgmmvnrcl.html

[R27] 算术展开
来源：http://dali.fzhhl.top/Article/details/gtexpsmsgj.html

echo $((1 + 2 * 3))
来源：http://dali.jqgfzy.top/Article/details/gtukberuuw.html

[R28] 浮点运算
来源：http://dali.xinyue.icu/Article/details/gtrhapeonh.html

echo "scale=2; 10/3" | bc
来源：http://dali.ehwqpu.com/Article/details/gtsrovxqkc.html

[R29] 定义函数
来源：http://dali.cucudq.cn/Article/details/gttpiufjlv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cashguo.top/Article/details/gtololmygh.html

[R30] 函数返回状态码
来源：http://dali.hnqzz.top/Article/details/gtknjbznug.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauounlav.html

[R31] 局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtgopzapmo.html

f() { local x=1; echo "$x"; }
来源：http://dali.ydzc1.top/Article/details/gtrpsrrmvo.html

[R32] 参数个数校验
来源：http://dali.shuidangran.top/Article/details/gtrnxzsugc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gtkhpkiblo.html

[R33] 捕获错误并提示行号
来源：http://dali.smart0.xyz/Article/details/gtxetjsmqq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hfpthk.cn/Article/details/gtsueiovsl.html

[R34] 退出时清理
来源：http://dali.yongpay.top/Article/details/gtcgbktdhm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gtbapmvsst.html

[R35] 后台执行并等待
来源：http://dali.sweek.top/Article/details/gtbhsgqwja.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ybcxt.top/Article/details/gtfzhwygwq.html

[R36] 并发执行多个任务
来源：http://dali.gaohongyu789.top/Article/details/gtgdfsbqxv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.mhx1999.top/Article/details/gtghyungiv.html

[R37] 把输出赋给变量
来源：http://dali.pycfn.com/Article/details/gtnnfkplsz.html

files=$(ls -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtbufvtudm.html

[R38] 管道串联
来源：http://dali.xuetiantiany.cn/Article/details/gtavzulzik.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuanzx.com/Article/details/gtsbkuqpqa.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigfzy.top/Article/details/gtqjrvpdfr.html


<!-- 参考信息 -->