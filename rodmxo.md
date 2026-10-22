代发 wailian999

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzdvltsp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.0kj1m.cn/Article/details/gtcqidkckd.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtfvidaiis.html

[Q01] 创建表
来源：http://dali.havefunace.top/Article/details/gtjaiffiwa.html

CREATE TABLE users (
来源：http://dali.guannengcc.top/Article/details/gtnpahttcv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gtsnxlpagu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gtvlztuhgi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hongshengwenyu.top/Article/details/gttxpjiubr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pycfn.com/Article/details/gtzsiqtcwa.html

);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtximdhmnn.html

[Q02] 创建带外键的表
来源：http://dali.xinyue.icu/Article/details/gtoclchlat.html

CREATE TABLE orders (
来源：http://dali.yuxming.cn/Article/details/gtmnqbpfqs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcfjlyyj.html

user_id INT NOT NULL,
来源：http://dali.ivvv.top/Article/details/gteajyosfv.html

amount DECIMAL(10, 2),
来源：http://dali.ywan-chungtsiang.top/Article/details/gticbrazyd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yangfankeji.com/Article/details/gtgkdrjulu.html

);
来源：http://dali.fengsongda.top/Article/details/gtrxvrjjkv.html

[Q03] 增加列
来源：http://dali.xinyue.icu/Article/details/gtgxztetaz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.mhx1999.top/Article/details/gteluzseyr.html

[Q04] 修改列类型
来源：http://dali.meibo888.top/Article/details/gtivymfpxx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.andypj.xyz/Article/details/gtryuwqysu.html

[Q05] 重命名列
来源：http://dali.zdqjudy.top/Article/details/gtwongfclj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.bjfxy.top/Article/details/gtayvbbsld.html

[Q06] 删除列
来源：http://dali.nanxuanxn.top/Article/details/gtpsxtwcpa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gogol.net.cn/Article/details/gtrpyaxzom.html

[Q07] 删除表
来源：http://dali.shuidangran.top/Article/details/gtjdscqhos.html

DROP TABLE IF EXISTS orders;
来源：http://dali.quarkkingdee.top/Article/details/gtohcmfmse.html

[Q08] 创建普通索引
来源：http://dali.aibaodan.cn/Article/details/gtdcndztbd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gtzeazerhq.html

[Q09] 创建唯一索引
来源：http://dali.316326.xyz/Article/details/gtvlfseaar.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tanke756.top/Article/details/gtymctjsss.html

[Q10] 插入单行
来源：http://dali.jinqigfzy.top/Article/details/gtiwoifmwm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangdashe.top/Article/details/gtnuapfiqv.html

[Q11] 一次插入多行
来源：http://dali.iojbl.cn/Article/details/gtvwwngnye.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtyvrhzaoq.html

[Q12] 插入后取自增 ID
来源：http://dali.9152youxi.cn/Article/details/gtmaqrucpd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.9152youxi.cn/Article/details/gtlhxlzdem.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhixingplan.top/Article/details/gtdeghvqhj.html

[Q13] 忽略重复插入
来源：http://dali.fengsongda.top/Article/details/gtodwepamv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gtbftpgmex.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenjidiqi.icu/Article/details/gtzpxvybge.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xylfe.cn/Article/details/gtybjmxojc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.316326.xyz/Article/details/gtbuipgvwl.html

[Q15] 查询全部
来源：http://dali.jqgufenzy.top/Article/details/gtfbvzexji.html

SELECT * FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtaqlxeytg.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtskoidcwk.html

SELECT id, name FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtjwylskjx.html

[Q17] 条件查询
来源：http://dali.chenzaomai.com/Article/details/gtztsxlihw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ppjwa.cn/Article/details/gtensybtow.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gteayfvoqr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinghuilouyu.cn/Article/details/gtckqzkojx.html

[Q19] 范围查询
来源：http://dali.sufxvd.cn/Article/details/gtziakqppt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuanzhike.top/Article/details/gtuifrotee.html

[Q20] IN 列表
来源：http://dali.316326.xyz/Article/details/gtonsnnivd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jiagoushi.top/Article/details/gthmpsltyx.html

[Q21] 空值判断
来源：http://dali.cashguo.top/Article/details/gtqxfssxni.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenzaomai.com/Article/details/gtjoaohjad.html

[Q22] 排序
来源：http://dali.tian-w.cn/Article/details/gttlpdmxqq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.bjfxy.top/Article/details/gtuwgewriz.html

[Q23] 分页
来源：http://dali.jinghuilouyu.cn/Article/details/gtkggxpnia.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cdnleiting.top/Article/details/gtqjslpwfw.html

[Q24] 去重
来源：http://dali.aizwys.cn/Article/details/gtjenrrfpp.html

SELECT DISTINCT city FROM users;
来源：http://dali.mhx1999.top/Article/details/gthmuwweyd.html

[Q25] 只取前 N 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsutgwywk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jiagoushi.top/Article/details/gtnakrwkal.html

[Q26] 计数
来源：http://dali.birdmap.top/Article/details/gtnzdpbvvo.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuanzx.com/Article/details/gttgepggce.html

[Q27] 条件计数
来源：http://dali.yvedp.cn/Article/details/gtcliluhxe.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yvedp.cn/Article/details/gthfgsvgra.html

[Q28] 求和与平均
来源：http://dali.yanxiufei.cn/Article/details/gtiozsufgb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtwqvqzjcc.html

[Q29] 最大最小值
来源：http://dali.xinyue.icu/Article/details/gtldepcglz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtznxxpkfz.html

[Q30] 分组统计
来源：http://dali.xuanzx.com/Article/details/gtsqgljngs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtwsjbslth.html

[Q31] 分组后过滤
来源：http://dali.yongpay.top/Article/details/gtiykvxchz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhixingplan.top/Article/details/gtpwirecbu.html

[Q32] 分组拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtwcpwtayz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtokkvieky.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.birdmap.top/Article/details/gtxyhbnfum.html

[Q33] 多列分组
来源：http://dali.hnqzz.top/Article/details/gtzecixeem.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hysaishi.cn/Article/details/gttjjkyqpq.html

[Q34] 每组取第一条
来源：http://dali.daria6918.cn/Article/details/gtcvqbirbf.html

SELECT * FROM (
来源：http://dali.chenlongwang.top/Article/details/gtzenepipm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yonumen.top/Article/details/gtknxnoqir.html

) t WHERE rn = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtrdkqrxlo.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gtnkostflo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gtztkryxwx.html

[Q36] 左连接
来源：http://dali.yangfankeji.com/Article/details/gtbbdyujzh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcuucnwbu.html

[Q37] 右连接
来源：http://dali.haohaochexian.top/Article/details/gtpxpaojga.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gaohongyu789.top/Article/details/gtjinhgkad.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tanke756.top/Article/details/gtdgwnmzeq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fzhhl.top/Article/details/gtgkruihfa.html

[Q39] 自连接（查上下级）
来源：http://dali.cashguo.top/Article/details/gtycikgfea.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangshuangyany.cn/Article/details/gtsavevqka.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pycfn.com/Article/details/gtvkcdmkjq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhiwuduotai.top/Article/details/gtweyjguga.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.c1oappe.top/Article/details/gtleoouulg.html

[Q41] 多表连接
来源：http://dali.havefunace.top/Article/details/gtlankfarz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jiagoushi.top/Article/details/gtzderisfd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fengsongda.top/Article/details/gtnhjvslmz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.haohaochexian.top/Article/details/gtnerhilkn.html

[Q42] 连接条件附加过滤
来源：http://dali.yanxiufei.cn/Article/details/gtdjpvbmet.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhongyouzk.top/Article/details/gttetbcevl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgfzy.top/Article/details/gtbsleysit.html

[Q43] 标量子查询
来源：http://dali.yongpay.top/Article/details/gtzjhxrdiz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuetiantiany.cn/Article/details/gtwkxuedrc.html

[Q44] IN 子查询
来源：http://dali.ybcxt.top/Article/details/gtckaktopo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.mhx1999.top/Article/details/gtryyoitjc.html

[Q45] EXISTS 判断存在
来源：http://dali.cqqwz.cn/Article/details/gtwkjtrpto.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gtytmhcttu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.birdmap.top/Article/details/gtuxhsohxm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gtxpkjnpdi.html

[Q47] 与平均值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgjnopda.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guannengcc.top/Article/details/gthludpraz.html

[Q48] CTE 公用表表达式
来源：http://dali.yangfankeji.com/Article/details/gtzzyepbbg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.quarkkingdee.top/Article/details/gtofatritm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.smart0.xyz/Article/details/gtcckldzgv.html

[Q49] 更新单行
来源：http://dali.yanxiufei.cn/Article/details/gtemmyxchn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sxryk.cn/Article/details/gtaboinzhc.html

[Q50] 批量更新
来源：http://dali.cashguo.top/Article/details/gteosjikdz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gtsyjtxyky.html

[Q51] 用子查询更新
来源：http://dali.9152youxi.cn/Article/details/gteeqmbyba.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzowapbls.html

[Q52] 删除指定行
来源：http://dali.yj20258888.top/Article/details/gtvkcxuvcr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yangfankeji.com/Article/details/gtfrcotilx.html

[Q53] 按条件删除
来源：http://dali.jinqigfzy.top/Article/details/gteansjiqb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gzhubu.top/Article/details/gtdxihwtmp.html

[Q54] 清空表
来源：http://dali.tian-w.cn/Article/details/gteizozugx.html

TRUNCATE TABLE logs;
来源：http://dali.hongshengwenyu.top/Article/details/gtrwjaemwk.html

[Q55] 排名（并列占位）
来源：http://dali.bjfxy.top/Article/details/gtlennjwhr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xinyue.icu/Article/details/gtwwayhrtv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258888.top/Article/details/gtkbxztczq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dashuyun.cn/Article/details/gtenndaiho.html

[Q57] 行号
来源：http://dali.guannengcc.top/Article/details/gtrlekmgtj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xinyue.icu/Article/details/gtlvbtqmdm.html

[Q58] 累计求和
来源：http://dali.smart0.xyz/Article/details/gtjksqeqcf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ivvv.top/Article/details/gtkewghndf.html

[Q59] 分组内累计
来源：http://dali.sysykeji.top/Article/details/gtwxwvvurw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtjodknnrf.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenlongwang.top/Article/details/gtorqloopr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gogol.net.cn/Article/details/gtaxthyolq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtqmeuldff.html

[Q61] 移动平均
来源：http://dali.yvedp.cn/Article/details/gtgcxdyfiz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtfmjnsujc.html

[Q62] 分组占比
来源：http://dali.vqdsnc.cn/Article/details/gtpbdgudwl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtvupmlijn.html

[Q63] 开启事务
来源：http://dali.iojbl.cn/Article/details/gtgbzzmscr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgfzy.top/Article/details/gtcoxbhsco.html

[Q64] 提交事务
来源：http://dali.xuetiantiany.cn/Article/details/gtgdrfqxpq.html

COMMIT;
来源：http://dali.birdmap.top/Article/details/gttcmkljwh.html

[Q65] 回滚事务
来源：http://dali.xinyue.icu/Article/details/gtnvcybxfh.html

ROLLBACK;
来源：http://dali.nanxuanxn.top/Article/details/gtvdqqdwso.html

[Q66] 行锁查询
来源：http://dali.yonumen.top/Article/details/gtqvmqeqli.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xinyue.icu/Article/details/gtckgttrzu.html

[Q67] 设置隔离级别
来源：http://dali.chenlongwang.top/Article/details/gtwunqrgsg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cqqwz.cn/Article/details/gtxlapoepf.html

[Q68] 保存点
来源：http://dali.316326.xyz/Article/details/gtwqncqjzb.html

SAVEPOINT sp1;
来源：http://dali.xziqi.cn/Article/details/gttsvjndwc.html

ROLLBACK TO sp1;
来源：http://dali.yongpay.top/Article/details/gtixuzmmiz.html

[Q69] 查看执行计划
来源：http://dali.hnxiangtu.top/Article/details/gtwhchdatg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.smart0.xyz/Article/details/gtrejkzpvj.html

[Q70] 更新统计信息
来源：http://dali.yanxiufei.cn/Article/details/gtfxxdjtrt.html

ANALYZE TABLE users;
来源：http://dali.c1oappe.top/Article/details/gthmrfbmza.html

[Q71] 查看建表语句
来源：http://dali.hfpthk.cn/Article/details/gtlkxqqqiu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuanzx.com/Article/details/gtaaetselj.html

[Q72] 查看索引
来源：http://dali.havefunace.top/Article/details/gtreahimfw.html

SHOW INDEX FROM users;
来源：http://dali.bjfxy.top/Article/details/gtnajxwqha.html

[Q73] 查看表状态
来源：http://dali.316326.xyz/Article/details/gtqcpwwlgv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.meibo888.top/Article/details/gtblvvuehh.html

[Q74] 强制使用索引
来源：http://dali.cdnleiting.top/Article/details/gtbfveyqgw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gogol.net.cn/Article/details/gtdvfyaqzu.html

[Q75] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtmmqdpkkx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtysmmjmge.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gtznqhgekw.html

[Q76] 按天统计
来源：http://dali.chenzaomai.com/Article/details/gtuurhmbao.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jyoumei.cn/Article/details/gtrdhvdyhf.html

[Q77] 时间加减
来源：http://dali.xuanzx.com/Article/details/gtucpuabpt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhoulong.xyz/Article/details/gtwruqprrz.html

[Q78] 当前时间
来源：http://dali.jinqigufen.top/Article/details/gtfmcegjjl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zdqjudy.top/Article/details/gtkrffcvqp.html

[Q79] 字符串拼接
来源：http://dali.hywenlv.cn/Article/details/gtbsnamwyi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hysaishi.cn/Article/details/gtduexaevx.html

[Q80] 字符串截取
来源：http://dali.havefunace.top/Article/details/gtoydeewqj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sweek.top/Article/details/gtqzoxmzkd.html

[Q81] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gttghkgfwc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtxmuotbgy.html

[Q82] 字符长度与字节长度
来源：http://dali.zhengqikj.top/Article/details/gtzhzqtdve.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtqvarsmrs.html

[Q83] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtspmdiyge.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtgjceulqq.html

[Q84] 去除首尾空格
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhobxgbx.html

SELECT TRIM(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtixxebbvb.html

[Q85] 数值取整
来源：http://dali.sweek.top/Article/details/gtovwjagdj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xylfe.cn/Article/details/gtbfdhyyvz.html

[Q86] 读取 JSON 字段
来源：http://dali.xylfe.cn/Article/details/gtonggtcgm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hammf.cn/Article/details/gtnvpqwdtf.html

[Q87] JSON 字段做条件
来源：http://dali.sufxvd.cn/Article/details/gtfaebvgco.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigfzy.top/Article/details/gtwlegvjip.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenlongwang.top/Article/details/gtnbjybwgd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.vqdsnc.cn/Article/details/gtafbkwdxk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtodociiir.html

[Q89] 判断表是否存在
来源：http://dali.yuanzhike.top/Article/details/gtmslxmiqz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gtsrxlebia.html

[Q90] 生成序号列
来源：http://dali.tanke756.top/Article/details/gtammqrdwv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gtysgulsnf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtpiczdaen.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gtxldfzbzk.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtmcaxitwq.html

[R01] shebang 与严格模式
来源：http://dali.ydzc1.top/Article/details/gtimybjabt.html

#!/usr/bin/env bash
来源：http://dali.wangshuangyany.cn/Article/details/gtnrwrsera.html

set -euo pipefail
来源：http://dali.yj20258888.top/Article/details/gtbjncknpl.html

[R02] 变量赋值与使用
来源：http://dali.pengpengdd.cyou/Article/details/gtjmbvdkoj.html

name="Tom"; echo "$name"
来源：http://dali.gotoacloud.top/Article/details/gtfhitabue.html

[R03] 只读变量
来源：http://dali.fzhhl.top/Article/details/gtkmjsefhf.html

readonly PI=3.14
来源：http://dali.vqdsnc.cn/Article/details/gtyvvvomfk.html

[R04] 位置参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxxzoyqq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaibyhaem.html

[R05] 参数默认值
来源：http://dali.c1oappe.top/Article/details/gtymnpggzf.html

name="${1:-default}"
来源：http://dali.cucudq.cn/Article/details/gttcapiltl.html

[R06] 判断命令是否存在
来源：http://dali.cdnleiting.top/Article/details/gthhcojvny.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gtwvkcdhdj.html

[R07] if 判断文件
来源：http://dali.feifeiyinyue.top/Article/details/gtrialrihl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenlongwang.top/Article/details/gtmmqiklhr.html

[R08] 数值比较
来源：http://dali.0kj1m.cn/Article/details/gtibcqzyie.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhengqikj.top/Article/details/gtatsmsyoz.html

[R09] 字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtfjwlegam.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtojyaxmia.html

[R10] 正则匹配
来源：http://dali.zhongyouzk.top/Article/details/gtyuysckja.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.meibo888.top/Article/details/gtasztabpr.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gteohhtizt.html

case "$1" in
来源：http://dali.zhengqikj.top/Article/details/gtxguumiqv.html

start) echo "启动" ;;
来源：http://dali.meibo888.top/Article/details/gtlwsnkzzz.html

stop)  echo "停止" ;;
来源：http://dali.tian-w.cn/Article/details/gtmvlbdpjs.html

*)     echo "未知命令" ;;
来源：http://dali.hywenlv.cn/Article/details/gtzdbqexaq.html

esac
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrwsplaz.html

[R12] for 遍历文件
来源：http://dali.yonumen.top/Article/details/gthupuvbxk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cucudq.cn/Article/details/gtclzxadmu.html

[R13] for 计数循环
来源：http://dali.yueranfly.top/Article/details/gtjkegtcln.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtqucxdyss.html

[R14] C 风格 for
来源：http://dali.jqgufenzy.top/Article/details/gtyalttrqr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gtirrsznlb.html

[R15] while 逐行读文件
来源：http://dali.yonumen.top/Article/details/gtmigyeupb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ybcxt.top/Article/details/gtuxioujxs.html

[R16] until 等待条件
来源：http://dali.sysykeji.top/Article/details/gtbidsbhsj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gtrsbaijuc.html

[R17] 数组定义与取值
来源：http://dali.yj202588.top/Article/details/gtyfotozcc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fzhhl.top/Article/details/gtoofwscdi.html

[R18] 遍历数组
来源：http://dali.0kj1m.cn/Article/details/gthsiesywv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenlongwang.top/Article/details/gttpubskjx.html

[R19] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gtnxmnxqbe.html

echo "${#arr[@]}"
来源：http://dali.cashguo.top/Article/details/gtvuojyztb.html

[R20] 关联数组（字典）
来源：http://dali.tanke756.top/Article/details/gttahicypf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.svipenyu.cn/Article/details/gtpjolgdkb.html

[R21] 字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gtdcxcfyae.html

echo "${#s}"
来源：http://dali.yanxiufei.cn/Article/details/gtyvkndhjv.html

[R22] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzhdkmns.html

echo "${s:0:5}"
来源：http://dali.nanxinkj.top/Article/details/gtesuyhawx.html

[R23] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtslxslgnn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhengqikj.top/Article/details/gtqwxeacbc.html

[R24] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gtkxigpkja.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aibaodan.cn/Article/details/gticnaqcwr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gtcrhpkthn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cdnleiting.top/Article/details/gtipwfndfy.html

[R26] 命令替换
来源：http://dali.jiagoushi.top/Article/details/gtddzhdoxo.html

now=$(date +%F); echo "$now"
来源：http://dali.gogol.net.cn/Article/details/gtpftgtgdx.html

[R27] 算术展开
来源：http://dali.yanxiufei.cn/Article/details/gtbjjpjkpp.html

echo $((1 + 2 * 3))
来源：http://dali.mhx1999.top/Article/details/gtcqgqrkyg.html

[R28] 浮点运算
来源：http://dali.yj202588.top/Article/details/gtxnfmdcal.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gtnjeplrdm.html

[R29] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gtbwmgxhau.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gotoacloud.top/Article/details/gtkfenktmz.html

[R30] 函数返回状态码
来源：http://dali.guowangkeji.top/Article/details/gtpavapjen.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jyoumei.cn/Article/details/gtwxzqzkps.html

[R31] 局部变量
来源：http://dali.gaohongyu789.top/Article/details/gtgtjvjgjd.html

f() { local x=1; echo "$x"; }
来源：http://dali.cashguo.top/Article/details/gtcxhprbex.html

[R32] 参数个数校验
来源：http://dali.hywenlv.cn/Article/details/gtqkrallce.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gtamnkbnek.html

[R33] 捕获错误并提示行号
来源：http://dali.316326.xyz/Article/details/gtagfdqatr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fengsongda.top/Article/details/gtnblpzyce.html

[R34] 退出时清理
来源：http://dali.meibo888.top/Article/details/gtewnwpzjk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gtclatqshn.html

[R35] 后台执行并等待
来源：http://dali.jinqigfzy.top/Article/details/gtmjnrhgto.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmomfylly.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gtfpcfjtuq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tianlin.xyz/Article/details/gthcxsfrvd.html

[R37] 把输出赋给变量
来源：http://dali.wangshuangyany.cn/Article/details/gtbbsublhz.html

files=$(ls -1)
来源：http://dali.jqgfzy.top/Article/details/gtpemsnimf.html

[R38] 管道串联
来源：http://dali.redwolf501.top/Article/details/gtugkglidd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnppnwabo.html

[R39] 重定向标准输出与错误
来源：http://dali.wangdashe.top/Article/details/gtqkjnravk.html

cmd > out.log 2>&1
来源：http://dali.hnqzz.top/Article/details/gtmbaxrdib.html

[R40] 追加写日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtraqelwgc.html

echo "log" >> out.log
来源：http://dali.yj202588.top/Article/details/gttohcpuya.html

[R41] 丢弃输出
来源：http://dali.cheryme.top/Article/details/gteeondrnd.html

cmd >/dev/null 2>&1
来源：http://dali.sxryk.cn/Article/details/gtbdhsptpe.html

[R42] 输入重定向
来源：http://dali.fzhhl.top/Article/details/gtgdghhmne.html

wc -l < a.txt
来源：http://dali.zhengqikj.top/Article/details/gtbuhbwvxx.html

[R43] 按名字查找文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtduxbagdm.html


<!-- 参考信息 -->