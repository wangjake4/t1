代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.dashuyun.cn/Article/details/gtokutazhd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jlsjyb.cn/Article/details/gtfipsouzw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yuanzhike.top/Article/details/gtbqegneti.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gtwlfkydkp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yongpay.top/Article/details/gtkfdikzdh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daria6918.cn/Article/details/gtmrzuzwij.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.pengpengdd.cyou/Article/details/gtvbumbanc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nwbrower.top/Article/details/gtthvhakif.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtxkwuvkvf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnxiangtu.top/Article/details/gttdboipge.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtqrzogkts.html

[Q01] 创建表
来源：http://dali.kuanghao11.cn/Article/details/gtkotinshq.html

CREATE TABLE users (
来源：http://dali.gaohongyu789.top/Article/details/gtkuzqjhmj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gtznbxrrlh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtfigojhrl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aibaodan.cn/Article/details/gtjdywjxzg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnxiangtu.top/Article/details/gtchfkduax.html

);
来源：http://dali.redwolf501.top/Article/details/gtwbrptgld.html

[Q02] 创建带外键的表
来源：http://dali.mhx1999.top/Article/details/gtgrgmiwqk.html

CREATE TABLE orders (
来源：http://dali.yangfankeji.com/Article/details/gttopesjcc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gtixdnatuf.html

user_id INT NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gtnabfbmgk.html

amount DECIMAL(10, 2),
来源：http://dali.xinyue.icu/Article/details/gttghluhgs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.havefunace.top/Article/details/gtuzfuyowf.html

);
来源：http://dali.jqgufenzy.top/Article/details/gtyhoysjpn.html

[Q03] 增加列
来源：http://dali.iojbl.cn/Article/details/gtvjbseshh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.daxiang520.top/Article/details/gttxcppflg.html

[Q04] 修改列类型
来源：http://dali.andypj.xyz/Article/details/gtzypzygob.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhoulong.xyz/Article/details/gtjsgxahcv.html

[Q05] 重命名列
来源：http://dali.jqgfzy.top/Article/details/gtacmtdxdp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigufen.top/Article/details/gteelmjtdz.html

[Q06] 删除列
来源：http://dali.pycfn.com/Article/details/gtzizscgrn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnxiangtu.top/Article/details/gtpylcqiaw.html

[Q07] 删除表
来源：http://dali.andypj.xyz/Article/details/gttpkqfgzd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gaohongyu789.top/Article/details/gttrisnnnz.html

[Q08] 创建普通索引
来源：http://dali.zhoulong.xyz/Article/details/gtkdvqtwop.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gtdlvzxppc.html

[Q09] 创建唯一索引
来源：http://dali.yj20258888.top/Article/details/gtmiyncftf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.andypj.xyz/Article/details/gtmqpsggaj.html

[Q10] 插入单行
来源：http://dali.yueranfly.top/Article/details/gtcwcsixiq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gzhubu.top/Article/details/gthxygfxir.html

[Q11] 一次插入多行
来源：http://dali.cheryme.top/Article/details/gtwadvaivx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtkdnguime.html

[Q12] 插入后取自增 ID
来源：http://dali.zhengqikj.top/Article/details/gtekopteoz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenlongwang.top/Article/details/gtpyschikn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.feifeiyinyue.top/Article/details/gttyeixfvr.html

[Q13] 忽略重复插入
来源：http://dali.sxryk.cn/Article/details/gtebutbcos.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xuanzx.com/Article/details/gtvzloxmlq.html

[Q14] 存在则更新（upsert）
来源：http://dali.bjfxy.top/Article/details/gtyxzksvrr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.snrcjt.cn/Article/details/gtjvdftwsc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxscolhl.html

[Q15] 查询全部
来源：http://dali.yueranfly.top/Article/details/gtypjvegmn.html

SELECT * FROM users;
来源：http://dali.yuxming.cn/Article/details/gtutxhqale.html

[Q16] 查询指定列
来源：http://dali.snrcjt.cn/Article/details/gthmsrxakb.html

SELECT id, name FROM users;
来源：http://dali.316326.xyz/Article/details/gtsyfziesa.html

[Q17] 条件查询
来源：http://dali.gzhubu.top/Article/details/gttlmddcoj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuanzhike.top/Article/details/gtsmrcrjnh.html

[Q18] 模糊匹配
来源：http://dali.mhx1999.top/Article/details/gtdgmexnok.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigufen.top/Article/details/gtldibnwgq.html

[Q19] 范围查询
来源：http://dali.zycfv.cn/Article/details/gtotlkniqn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnxiangtu.top/Article/details/gtmatboclr.html

[Q20] IN 列表
来源：http://dali.ydzc1.top/Article/details/gtrhsaukqt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.smart0.xyz/Article/details/gtlhzbihth.html

[Q21] 空值判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlamhsozf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.dashuyun.cn/Article/details/gtunnfuojq.html

[Q22] 排序
来源：http://dali.daria6918.cn/Article/details/gtxbhdltel.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.havefunace.top/Article/details/gttnrecgeh.html

[Q23] 分页
来源：http://dali.aibaodan.cn/Article/details/gtuepvgxkn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aibaodan.cn/Article/details/gtbtwnmoni.html

[Q24] 去重
来源：http://dali.havefunace.top/Article/details/gtgwtflwey.html

SELECT DISTINCT city FROM users;
来源：http://dali.zycfv.cn/Article/details/gtftvqzchx.html

[Q25] 只取前 N 条
来源：http://dali.dashuyun.cn/Article/details/gtjxmxrlrx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.quarkkingdee.top/Article/details/gttdtwzvmw.html

[Q26] 计数
来源：http://dali.iojbl.cn/Article/details/gttvwzyabe.html

SELECT COUNT(*) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtkgustxth.html

[Q27] 条件计数
来源：http://dali.yuxming.cn/Article/details/gtxjyzccbu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtybivljuk.html

[Q28] 求和与平均
来源：http://dali.dianchejie.cn/Article/details/gtbvngzfxa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtfwvyptyc.html

[Q29] 最大最小值
来源：http://dali.chenlongwang.top/Article/details/gtjmouckep.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtodqmvoao.html

[Q30] 分组统计
来源：http://dali.haohaochexian.top/Article/details/gtuuoxizth.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gtvegpdeaz.html

[Q31] 分组后过滤
来源：http://dali.cheryme.top/Article/details/gtunmgxsmq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltmawntp.html

[Q32] 分组拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtuwhxajhp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gtgpcsxaka.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.meibo888.top/Article/details/gtdmkkqznk.html

[Q33] 多列分组
来源：http://dali.svipenyu.cn/Article/details/gtdjczvvjp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xziqi.cn/Article/details/gtxgpbocoi.html

[Q34] 每组取第一条
来源：http://dali.cucudq.cn/Article/details/gtagelokka.html

SELECT * FROM (
来源：http://dali.gaohongyu789.top/Article/details/gtosfrrpog.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xylfe.cn/Article/details/gtxxoomady.html

) t WHERE rn = 1;
来源：http://dali.xziqi.cn/Article/details/gtwwrgdmpv.html

[Q35] 内连接
来源：http://dali.jiagoushi.top/Article/details/gtqoibfrff.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gtlnukokzn.html

[Q36] 左连接
来源：http://dali.dashuyun.cn/Article/details/gtryxtfrqi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gtlxsfwhok.html

[Q37] 右连接
来源：http://dali.yangfankeji.com/Article/details/gtfvpfcvpo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbkcpjih.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yongpay.top/Article/details/gtfwaggnen.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.redwolf501.top/Article/details/gtpgoaxjtf.html

[Q39] 自连接（查上下级）
来源：http://dali.gogol.net.cn/Article/details/gtdbtjjtxq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gzhubu.top/Article/details/gtlellqter.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuetiantiany.cn/Article/details/gtdmahnnhs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.vqdsnc.cn/Article/details/gtosmihuvq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guannengcc.top/Article/details/gtfeauabis.html

[Q41] 多表连接
来源：http://dali.chenlongwang.top/Article/details/gtuxmcybep.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.iojbl.cn/Article/details/gtggvfrflp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj202588.top/Article/details/gtsvziojkd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ybcxt.top/Article/details/gtptwioxov.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxinkj.top/Article/details/gtxnulcrly.html

SELECT u.name, o.amount FROM users u
来源：http://dali.c1oappe.top/Article/details/gtcvhcepkj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hywenlv.cn/Article/details/gtmobweiim.html

[Q43] 标量子查询
来源：http://dali.yongpay.top/Article/details/gtlxrhjkkb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shangyingyoupin.top/Article/details/gtdnnmrwym.html

[Q44] IN 子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrupwwtck.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhongyouzk.top/Article/details/gtsjleabun.html

[Q45] EXISTS 判断存在
来源：http://dali.yangfankeji.com/Article/details/gthnilvfih.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gtwsrrbuca.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258888.top/Article/details/gtcjpeigiq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtlgdyrrjr.html

[Q47] 与平均值比较
来源：http://dali.andypj.xyz/Article/details/gtyldcssty.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guannengcc.top/Article/details/gtxgkuects.html

[Q48] CTE 公用表表达式
来源：http://dali.iojbl.cn/Article/details/gtangnpujo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.meibo888.top/Article/details/gtvjqqlyyl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cdnleiting.top/Article/details/gtircfckqa.html

[Q49] 更新单行
来源：http://dali.aibaodan.cn/Article/details/gtlikbiome.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gthttygquj.html

[Q50] 批量更新
来源：http://dali.cdnleiting.top/Article/details/gtjmoeabnb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jiagoushi.top/Article/details/gtcksaaytw.html

[Q51] 用子查询更新
来源：http://dali.bjfxy.top/Article/details/gtadlmijje.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.havefunace.top/Article/details/gtcvrbcmmt.html

[Q52] 删除指定行
来源：http://dali.cheryme.top/Article/details/gtqdhdvwfi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnqzz.top/Article/details/gtxjukrbgl.html

[Q53] 按条件删除
来源：http://dali.jinghuilouyu.cn/Article/details/gteatjxlmm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xinyue.icu/Article/details/gthymjyauw.html

[Q54] 清空表
来源：http://dali.zhengqikj.top/Article/details/gtcmpkuzju.html

TRUNCATE TABLE logs;
来源：http://dali.gaohongyu789.top/Article/details/gtlibsyxlw.html

[Q55] 排名（并列占位）
来源：http://dali.sysykeji.top/Article/details/gtzovmoyaa.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklqhbkpy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ybcxt.top/Article/details/gtbykghort.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hysaishi.cn/Article/details/gtdbcrecvb.html

[Q57] 行号
来源：http://dali.yj20258.top/Article/details/gthloqulpm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtykowsjgr.html

[Q58] 累计求和
来源：http://dali.xziqi.cn/Article/details/gtntehkvcb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmxdcxwf.html

[Q59] 分组内累计
来源：http://dali.xuanzx.com/Article/details/gtwixaanfs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtoyflgoqw.html

[Q60] 取上一行 / 下一行
来源：http://dali.havefunace.top/Article/details/gteydusxes.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gogol.net.cn/Article/details/gtzyplflvv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtczhogres.html

[Q61] 移动平均
来源：http://dali.chenjidiqi.icu/Article/details/gtnygkdbhw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtuhwempda.html

[Q62] 分组占比
来源：http://dali.wangshuangyany.cn/Article/details/gtyqmxnesn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtiaskweex.html

[Q63] 开启事务
来源：http://dali.quarkkingdee.top/Article/details/gtryngpmle.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.feifeiyinyue.top/Article/details/gtpptjsecd.html

[Q64] 提交事务
来源：http://dali.nanxinkj.top/Article/details/gtfhprfqec.html

COMMIT;
来源：http://dali.svipenyu.cn/Article/details/gtgqcjpdjc.html

[Q65] 回滚事务
来源：http://dali.gogol.net.cn/Article/details/gtkixygglx.html

ROLLBACK;
来源：http://dali.shangyingyoupin.top/Article/details/gtmrizcvbw.html

[Q66] 行锁查询
来源：http://dali.aizwys.cn/Article/details/gttroegbtv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgotyfoxd.html

[Q67] 设置隔离级别
来源：http://dali.ppjwa.cn/Article/details/gtqepekazn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cucudq.cn/Article/details/gtlpyrmpks.html

[Q68] 保存点
来源：http://dali.hammf.cn/Article/details/gteiwgghri.html

SAVEPOINT sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwzmktto.html

ROLLBACK TO sp1;
来源：http://dali.nwbrower.top/Article/details/gtzmqebszj.html

[Q69] 查看执行计划
来源：http://dali.nanxinkj.top/Article/details/gtpgfvfaxy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangdashe.top/Article/details/gtbdvfzwkb.html

[Q70] 更新统计信息
来源：http://dali.ppjwa.cn/Article/details/gtplpfctgx.html

ANALYZE TABLE users;
来源：http://dali.sufxvd.cn/Article/details/gtcfwlnnxg.html

[Q71] 查看建表语句
来源：http://dali.zdqjudy.top/Article/details/gtaiuxbwad.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobfbtddq.html

[Q72] 查看索引
来源：http://dali.0kj1m.cn/Article/details/gtbqhjdxhj.html

SHOW INDEX FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtcpaqmlgm.html

[Q73] 查看表状态
来源：http://dali.dashuyun.cn/Article/details/gtkpmhzsty.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.9152youxi.cn/Article/details/gtnlijyrbk.html

[Q74] 强制使用索引
来源：http://dali.yj20258888.top/Article/details/gtzvuakadq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuanzx.com/Article/details/gtwlmqdhwl.html

[Q75] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtxvwrdnlf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtsdlmnbqd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gogol.net.cn/Article/details/gtfldknwwp.html

[Q76] 按天统计
来源：http://dali.gogol.net.cn/Article/details/gtmigzisxv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guowangkeji.top/Article/details/gtydbajmze.html

[Q77] 时间加减
来源：http://dali.dashuyun.cn/Article/details/gticncqdot.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmoaadwq.html

[Q78] 当前时间
来源：http://dali.jlsjyb.cn/Article/details/gtlmqgoqve.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.kuanghao11.cn/Article/details/gtmhhejgth.html

[Q79] 字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gtagftrmzk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwwrywnb.html

[Q80] 字符串截取
来源：http://dali.jianghu66.top/Article/details/gtwuginmud.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtzdigyjer.html

[Q81] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gttoxnnlxl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtfgipkrkd.html

[Q82] 字符长度与字节长度
来源：http://dali.shzxlz.cn/Article/details/gtmcsktron.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtwhlfmjjm.html

[Q83] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gtcqzqjgme.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtmrdtagjm.html

[Q84] 去除首尾空格
来源：http://dali.cashguo.top/Article/details/gtwatvlauz.html

SELECT TRIM(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtqeigbzpa.html

[Q85] 数值取整
来源：http://dali.yueranfly.top/Article/details/gtcsphdjzf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxhcxgzw.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxuanxn.top/Article/details/gtqnqsuush.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhixingplan.top/Article/details/gtpbltnsap.html

[Q87] JSON 字段做条件
来源：http://dali.chenlongwang.top/Article/details/gtgwdaoldf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sweek.top/Article/details/gtxdavyfxq.html

[Q88] 行转列（条件聚合）
来源：http://dali.svipenyu.cn/Article/details/gtcmawobxk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gogol.net.cn/Article/details/gtgdnkgcgm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtnvxicgqh.html

[Q89] 判断表是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtcxgfvwnc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gogol.net.cn/Article/details/gtkzlxyyux.html

[Q90] 生成序号列
来源：http://dali.nwbrower.top/Article/details/gtdvnhtigo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shangyingyoupin.top/Article/details/gtevvficah.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtqtzlyruq.html

R. Bash 专题
来源：http://dali.zhoulong.xyz/Article/details/gtayvaksgt.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtchasngwz.html

[R01] shebang 与严格模式
来源：http://dali.yuxming.cn/Article/details/gtgaieaytn.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangtech.top/Article/details/gtfszxpmwb.html

set -euo pipefail
来源：http://dali.birdmap.top/Article/details/gtspvizxtl.html

[R02] 变量赋值与使用
来源：http://dali.hongshengwenyu.top/Article/details/gtydqlqknz.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gtnxrxsyzd.html

[R03] 只读变量
来源：http://dali.yj20258.top/Article/details/gtalyrcrgd.html

readonly PI=3.14
来源：http://dali.316326.xyz/Article/details/gtnycmylcp.html

[R04] 位置参数
来源：http://dali.sweek.top/Article/details/gttxasuwcl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gogol.net.cn/Article/details/gtiqbatiwe.html

[R05] 参数默认值
来源：http://dali.birdmap.top/Article/details/gtolsnrmbn.html

name="${1:-default}"
来源：http://dali.jianghu66.top/Article/details/gtunbwcuaf.html

[R06] 判断命令是否存在
来源：http://dali.pycfn.com/Article/details/gtwoalrswp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gtztwhuogn.html

[R07] if 判断文件
来源：http://dali.haohaochexian.top/Article/details/gtdkauyhff.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.bjfxy.top/Article/details/gtlbmtwaus.html

[R08] 数值比较
来源：http://dali.havefunace.top/Article/details/gtkxgekxyj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cdnleiting.top/Article/details/gtfulassat.html

[R09] 字符串比较
来源：http://dali.chenlongwang.top/Article/details/gtviqgduoi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.havefunace.top/Article/details/gtfnjvfqma.html

[R10] 正则匹配
来源：http://dali.jyoumei.cn/Article/details/gtdjnbfgfm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhengqikj.top/Article/details/gtzdxwgwmx.html

[R11] case 多分支
来源：http://dali.jqgufenzy.top/Article/details/gteuggkyrf.html

case "$1" in
来源：http://dali.zdqjudy.top/Article/details/gtfsfcxihx.html

start) echo "启动" ;;
来源：http://dali.zhengqikj.top/Article/details/gtbuyxhkxm.html

stop)  echo "停止" ;;
来源：http://dali.cheryme.top/Article/details/gtwlahzxim.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtaljwnjog.html

esac
来源：http://dali.andypj.xyz/Article/details/gtzwksnaqj.html

[R12] for 遍历文件
来源：http://dali.hywenlv.cn/Article/details/gttjqfovzu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jqgufenzy.top/Article/details/gtnkjstpih.html

[R13] for 计数循环
来源：http://dali.yangfankeji.com/Article/details/gtccgixwgi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gtxzskmnbe.html

[R14] C 风格 for
来源：http://dali.xinyue.icu/Article/details/gtqxqiptyb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gthlgokteu.html

[R15] while 逐行读文件
来源：http://dali.yongpay.top/Article/details/gtmrvjwtai.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.birdmap.top/Article/details/gtfemkfnvf.html

[R16] until 等待条件
来源：http://dali.yuxming.cn/Article/details/gtylmpjogp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtzbvjippw.html

[R17] 数组定义与取值
来源：http://dali.dianchejie.cn/Article/details/gtmcfbvftf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daxiang520.top/Article/details/gtwlsururd.html

[R18] 遍历数组
来源：http://dali.nwbrower.top/Article/details/gtflsjxdnh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjwjtcaz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gtpqclaibx.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfjihadt.html

[R20] 关联数组（字典）
来源：http://dali.aizwys.cn/Article/details/gttwkbiyhh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zycfv.cn/Article/details/gttbpixoft.html

[R21] 字符串长度
来源：http://dali.fzhhl.top/Article/details/gtkuxativd.html

echo "${#s}"
来源：http://dali.ppjwa.cn/Article/details/gtgxldrkto.html

[R22] 截取子串
来源：http://dali.birdmap.top/Article/details/gthnewsshh.html

echo "${s:0:5}"
来源：http://dali.xziqi.cn/Article/details/gtiilthjdu.html

[R23] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gtlsvcmsxg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daria6918.cn/Article/details/gtupsiptcm.html

[R24] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtxfnbkfhw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhoulong.xyz/Article/details/gtkniaowap.html

[R25] 去后缀 / 去前缀
来源：http://dali.dashuyun.cn/Article/details/gtwtqfihld.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guannengcc.top/Article/details/gthgwwnfds.html

[R26] 命令替换
来源：http://dali.xuanzx.com/Article/details/gtpffpzagh.html

now=$(date +%F); echo "$now"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtzrzykg.html

[R27] 算术展开
来源：http://dali.nanxinkj.top/Article/details/gtnmjthrnm.html

echo $((1 + 2 * 3))
来源：http://dali.yongpay.top/Article/details/gtvulyvnqu.html

[R28] 浮点运算
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnilouit.html

echo "scale=2; 10/3" | bc
来源：http://dali.tanke756.top/Article/details/gtisptusif.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtofijveay.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jyoumei.cn/Article/details/gtdprhjhqf.html

[R30] 函数返回状态码
来源：http://dali.nanxinkj.top/Article/details/gtvpvxrcik.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczahenlg.html

[R31] 局部变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqvpcole.html

f() { local x=1; echo "$x"; }
来源：http://dali.ivvv.top/Article/details/gttehjdhzn.html

[R32] 参数个数校验
来源：http://dali.jqgufenzy.top/Article/details/gtezoxgxra.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnbqtnfzn.html

[R33] 捕获错误并提示行号
来源：http://dali.yangfankeji.com/Article/details/gtazbymjlr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ppjwa.cn/Article/details/gttiqdfvmu.html

[R34] 退出时清理
来源：http://dali.tian-w.cn/Article/details/gtvkpzdmib.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimmhvoit.html

[R35] 后台执行并等待
来源：http://dali.dianchejie.cn/Article/details/gthfexesuj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gotoacloud.top/Article/details/gtmxrytxyq.html

[R36] 并发执行多个任务
来源：http://dali.vqdsnc.cn/Article/details/gtxkseudmo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhongyouzk.top/Article/details/gteqfrgfwa.html

[R37] 把输出赋给变量
来源：http://dali.fzhhl.top/Article/details/gthdgdfpee.html

files=$(ls -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtjrukutnd.html

[R38] 管道串联
来源：http://dali.zycfv.cn/Article/details/gtspuhsrpd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigufen.top/Article/details/gtmppafuxq.html

[R39] 重定向标准输出与错误
来源：http://dali.gzhubu.top/Article/details/gtygpimhys.html


<!-- 参考信息 -->