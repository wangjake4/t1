代发 wailian999

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnesakxrj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gtmblblenw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gtwwauvuwf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.guannengcc.top/Article/details/gtwaewvgci.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.fengsongda.top/Article/details/gtgzqpddln.html

);
来源：http://dali.cucudq.cn/Article/details/gtalqejsbg.html

[Q02] 创建带外键的表
来源：http://dali.ybcxt.top/Article/details/gtxcwhpwgg.html

CREATE TABLE orders (
来源：http://dali.feifeiyinyue.top/Article/details/gtuenahpeu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtjfqkclsk.html

user_id INT NOT NULL,
来源：http://dali.shangyingyoupin.top/Article/details/gtkspffkxw.html

amount DECIMAL(10, 2),
来源：http://dali.wangshuangyany.cn/Article/details/gtiwdmfolp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ehwqpu.com/Article/details/gtwheqqldn.html

);
来源：http://dali.ydzc1.top/Article/details/gtnwzlnvlc.html

[Q03] 增加列
来源：http://dali.jqgufenzy.top/Article/details/gtuzwujxnr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.wangshuangyany.cn/Article/details/gtdywfznpz.html

[Q04] 修改列类型
来源：http://dali.snrcjt.cn/Article/details/gtpucqccvq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guannengcc.top/Article/details/gtroceosuh.html

[Q05] 重命名列
来源：http://dali.hfpthk.cn/Article/details/gtjdaiughy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aibaodan.cn/Article/details/gtqvcadmrm.html

[Q06] 删除列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahoapyjt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.kuanghao11.cn/Article/details/gteestxhte.html

[Q07] 删除表
来源：http://dali.zhengqikj.top/Article/details/gthacgonhi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.vqdsnc.cn/Article/details/gtmcbjgcnx.html

[Q08] 创建普通索引
来源：http://dali.zhiwuduotai.top/Article/details/gtjtgafqwj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daxiang520.top/Article/details/gtuelkwixs.html

[Q09] 创建唯一索引
来源：http://dali.mhx1999.top/Article/details/gtqtiswbxb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gthiqyfzwu.html

[Q10] 插入单行
来源：http://dali.haohaochexian.top/Article/details/gtvwpzfczp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtqepshmbo.html

[Q11] 一次插入多行
来源：http://dali.yueranfly.top/Article/details/gtxbeajpiv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtliozsfsd.html

[Q12] 插入后取自增 ID
来源：http://dali.xuetiantiany.cn/Article/details/gtllhcgorw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pengpengdd.cyou/Article/details/gtofhrptvk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aizwys.cn/Article/details/gtjjhijuwf.html

[Q13] 忽略重复插入
来源：http://dali.guowangkeji.top/Article/details/gtfwcvtetz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtsgvyzzvd.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj20258.top/Article/details/gtoxhzeuiw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgzbrzxi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenlongwang.top/Article/details/gtbdacqbxk.html

[Q15] 查询全部
来源：http://dali.dashuyun.cn/Article/details/gtgmtmnnew.html

SELECT * FROM users;
来源：http://dali.hammf.cn/Article/details/gtcdhvtiyq.html

[Q16] 查询指定列
来源：http://dali.cucudq.cn/Article/details/gtfviuoupt.html

SELECT id, name FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtlxibimlq.html

[Q17] 条件查询
来源：http://dali.jqgfzy.top/Article/details/gtdtauqsiv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xylfe.cn/Article/details/gtsmpkblaj.html

[Q18] 模糊匹配
来源：http://dali.chenlongwang.top/Article/details/gtdasbieip.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.vqdsnc.cn/Article/details/gtyivpbkmb.html

[Q19] 范围查询
来源：http://dali.daria6918.cn/Article/details/gtltyvqknd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.snrcjt.cn/Article/details/gtxosxhlke.html

[Q20] IN 列表
来源：http://dali.xuanzx.com/Article/details/gtmwsghkrj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ppjwa.cn/Article/details/gtdzmddzyl.html

[Q21] 空值判断
来源：http://dali.zdqjudy.top/Article/details/gtchamnjuf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jlsjyb.cn/Article/details/gtgfndjjna.html

[Q22] 排序
来源：http://dali.fzhhl.top/Article/details/gtzhkpirrx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgufenzy.top/Article/details/gtgzvtiwqa.html

[Q23] 分页
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuknwmesu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daria6918.cn/Article/details/gtqwqjxpjl.html

[Q24] 去重
来源：http://dali.smart0.xyz/Article/details/gtfrkevjir.html

SELECT DISTINCT city FROM users;
来源：http://dali.hammf.cn/Article/details/gtgnacbilf.html

[Q25] 只取前 N 条
来源：http://dali.chenjidiqi.icu/Article/details/gthjxjvvwk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hongshengwenyu.top/Article/details/gtlpxgmkkc.html

[Q26] 计数
来源：http://dali.c1oappe.top/Article/details/gtapqvvgyg.html

SELECT COUNT(*) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtmzhrnljr.html

[Q27] 条件计数
来源：http://dali.cashguo.top/Article/details/gtlaetuxrk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258888.top/Article/details/gtsowgzmjy.html

[Q28] 求和与平均
来源：http://dali.dianchejie.cn/Article/details/gtrcxgskeg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtjvyyaiar.html

[Q29] 最大最小值
来源：http://dali.cdnleiting.top/Article/details/gtjanmypaq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtmqvbblyj.html

[Q30] 分组统计
来源：http://dali.guowangkeji.top/Article/details/gtjbscyfsn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gtfxlyhuhc.html

[Q31] 分组后过滤
来源：http://dali.tian-w.cn/Article/details/gtfszrjile.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgfzy.top/Article/details/gtbzediear.html

[Q32] 分组拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtbhkmhgre.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtufsjxpid.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgufenzy.top/Article/details/gtqnyrjhxo.html

[Q33] 多列分组
来源：http://dali.pengpengdd.cyou/Article/details/gtcidznnrk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hywenlv.cn/Article/details/gtlusfwtto.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gtrszabiur.html

SELECT * FROM (
来源：http://dali.aibaodan.cn/Article/details/gtmymamhpa.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ydzc1.top/Article/details/gtezctielf.html

) t WHERE rn = 1;
来源：http://dali.yongpay.top/Article/details/gtxgvoqebe.html

[Q35] 内连接
来源：http://dali.havefunace.top/Article/details/gtitwzvump.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtrnebkxpl.html

[Q36] 左连接
来源：http://dali.snrcjt.cn/Article/details/gthivyalhb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gtdztibgif.html

[Q37] 右连接
来源：http://dali.yj20258.top/Article/details/gtajaldzii.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guowangkeji.top/Article/details/gthbkabeew.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttybxlrrh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gotoacloud.top/Article/details/gteevjxptu.html

[Q39] 自连接（查上下级）
来源：http://dali.yvedp.cn/Article/details/gtphpixpgz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.meibo888.top/Article/details/gtslaxrjii.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.guannengcc.top/Article/details/gtxfkdqulu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zycfv.cn/Article/details/gtnnlfxlqa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aibaodan.cn/Article/details/gthokjxzsn.html

[Q41] 多表连接
来源：http://dali.zhengqikj.top/Article/details/gtrkrqdkaj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhoulong.xyz/Article/details/gttfihgsco.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuxming.cn/Article/details/gtuzwpfekt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtsosicjnm.html

[Q42] 连接条件附加过滤
来源：http://dali.hysaishi.cn/Article/details/gtwrpfnema.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258.top/Article/details/gtuznbafve.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aibaodan.cn/Article/details/gtsgityxad.html

[Q43] 标量子查询
来源：http://dali.yvedp.cn/Article/details/gtfecyixlr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyekurxde.html

[Q44] IN 子查询
来源：http://dali.ppjwa.cn/Article/details/gtjdacjnpv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yangfankeji.com/Article/details/gtvngwdlxp.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigfzy.top/Article/details/gtrgjqikpz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtpexwyeaf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cdnleiting.top/Article/details/gtawiwbeui.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gtpgummlfe.html

[Q47] 与平均值比较
来源：http://dali.hywenlv.cn/Article/details/gturpgzwil.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhengqikj.top/Article/details/gtgxzrtwst.html

[Q48] CTE 公用表表达式
来源：http://dali.chenzaomai.com/Article/details/gtbrjgnpmb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.snrcjt.cn/Article/details/gtmphkverx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aizwys.cn/Article/details/gtnbdraznq.html

[Q49] 更新单行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjewpsgre.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yangfankeji.com/Article/details/gtjuqwlrhw.html

[Q50] 批量更新
来源：http://dali.yvedp.cn/Article/details/gttralkbix.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.haohaochexian.top/Article/details/gtbxgcmiix.html

[Q51] 用子查询更新
来源：http://dali.zdqjudy.top/Article/details/gtmdptcsyx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yuxming.cn/Article/details/gtfypobncx.html

[Q52] 删除指定行
来源：http://dali.gogol.net.cn/Article/details/gtbozyjjwv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtqfwscmdc.html

[Q53] 按条件删除
来源：http://dali.shuidangran.top/Article/details/gtulmkjqtz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.c1oappe.top/Article/details/gtfazygirz.html

[Q54] 清空表
来源：http://dali.zhixingplan.top/Article/details/gtwmmbwqld.html

TRUNCATE TABLE logs;
来源：http://dali.jqgufenzy.top/Article/details/gtmmmwyicn.html

[Q55] 排名（并列占位）
来源：http://dali.yj202588.top/Article/details/gtmbcptsdu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gtckkrrdru.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hywenlv.cn/Article/details/gtpouwvtdb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.316326.xyz/Article/details/gtaeyfwstq.html

[Q57] 行号
来源：http://dali.jiagoushi.top/Article/details/gtfkaeqvvv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shuidangran.top/Article/details/gtbjxiqyws.html

[Q58] 累计求和
来源：http://dali.yongpay.top/Article/details/gtfsmobqsv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ivvv.top/Article/details/gtxwyjhykr.html

[Q59] 分组内累计
来源：http://dali.jinqigufen.top/Article/details/gtuarxfhsy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtlmeyxwfw.html

[Q60] 取上一行 / 下一行
来源：http://dali.jyoumei.cn/Article/details/gtbwrhffms.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jlsjyb.cn/Article/details/gtqesitlen.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtohsnsmug.html

[Q61] 移动平均
来源：http://dali.zdqjudy.top/Article/details/gtvlsoneag.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pycfn.com/Article/details/gtsdlajfvr.html

[Q62] 分组占比
来源：http://dali.zdqjudy.top/Article/details/gtwcwnrqgu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtfxduwqyw.html

[Q63] 开启事务
来源：http://dali.tianlin.xyz/Article/details/gttcndbmaw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shzxlz.cn/Article/details/gtklmvcupb.html

[Q64] 提交事务
来源：http://dali.cheryme.top/Article/details/gtjixesjlo.html

COMMIT;
来源：http://dali.bjfxy.top/Article/details/gtbbcvvuaa.html

[Q65] 回滚事务
来源：http://dali.cqqwz.cn/Article/details/gtgsaeavay.html

ROLLBACK;
来源：http://dali.yanxiufei.cn/Article/details/gtiktkcksf.html

[Q66] 行锁查询
来源：http://dali.tanke756.top/Article/details/gtqvycuyhp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrdxjxxu.html

[Q67] 设置隔离级别
来源：http://dali.gogol.net.cn/Article/details/gtriuidgky.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gotoacloud.top/Article/details/gtobsfhwmi.html

[Q68] 保存点
来源：http://dali.ehwqpu.com/Article/details/gtzvuumxsx.html

SAVEPOINT sp1;
来源：http://dali.fengsongda.top/Article/details/gtmudabqkh.html

ROLLBACK TO sp1;
来源：http://dali.yuanzhike.top/Article/details/gtojmxqann.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gtlfvgjtwt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.meibo888.top/Article/details/gtiimqqthl.html

[Q70] 更新统计信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzojvnwf.html

ANALYZE TABLE users;
来源：http://dali.snrcjt.cn/Article/details/gtztgccssx.html

[Q71] 查看建表语句
来源：http://dali.shzxlz.cn/Article/details/gtvpbcpzmi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.fengsongda.top/Article/details/gtiqjrzxmz.html

[Q72] 查看索引
来源：http://dali.yvedp.cn/Article/details/gtjovgtwye.html

SHOW INDEX FROM users;
来源：http://dali.fzhhl.top/Article/details/gtwnblrhcr.html

[Q73] 查看表状态
来源：http://dali.bjfxy.top/Article/details/gtwwjgjdcs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gtorruouwh.html

[Q74] 强制使用索引
来源：http://dali.jlsjyb.cn/Article/details/gtamcilvcr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenlongwang.top/Article/details/gtlnelbncm.html

[Q75] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtwddiraqi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtdgotovwi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.vqdsnc.cn/Article/details/gtueevubkp.html

[Q76] 按天统计
来源：http://dali.fzhhl.top/Article/details/gtiwzphayl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhengqikj.top/Article/details/gtusjcqhjg.html

[Q77] 时间加减
来源：http://dali.birdmap.top/Article/details/gtynvpnois.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jiagoushi.top/Article/details/gtsdqgmbdc.html

[Q78] 当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrevtzmju.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cucudq.cn/Article/details/gtamuqhhba.html

[Q79] 字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gtllujahwn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigufen.top/Article/details/gtqkvzrbzg.html

[Q80] 字符串截取
来源：http://dali.zdqjudy.top/Article/details/gtlduljrqv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtoygjeyit.html

[Q81] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gtpdoangnx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pycfn.com/Article/details/gtwsirvtmw.html

[Q82] 字符长度与字节长度
来源：http://dali.hammf.cn/Article/details/gtcnylxpvm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gttxgaklja.html

[Q83] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gtlkqbymew.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtaezhfvop.html

[Q84] 去除首尾空格
来源：http://dali.yuanzhike.top/Article/details/gtxdzhfarx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtizmjfkzy.html

[Q85] 数值取整
来源：http://dali.hammf.cn/Article/details/gtaetburjs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnxiangtu.top/Article/details/gtkjeuruib.html

[Q86] 读取 JSON 字段
来源：http://dali.feifeiyinyue.top/Article/details/gtzpdjycpj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dianchejie.cn/Article/details/gtvoeobdzw.html

[Q87] JSON 字段做条件
来源：http://dali.tanke756.top/Article/details/gtczydzbbd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.havefunace.top/Article/details/gttiotootx.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenzaomai.com/Article/details/gtrczjmwcx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinqigufen.top/Article/details/gtkdrqmbaf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtmhbnzeqc.html

[Q89] 判断表是否存在
来源：http://dali.yuanzhike.top/Article/details/gtmaztojep.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.0kj1m.cn/Article/details/gtebfszcrh.html

[Q90] 生成序号列
来源：http://dali.dashuyun.cn/Article/details/gtbcbnqsmq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuetiantiany.cn/Article/details/gtbfnrvtlr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtoifzppnj.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gtdilklatp.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtspbveksx.html

[R01] shebang 与严格模式
来源：http://dali.guannengcc.top/Article/details/gtslkozjio.html

#!/usr/bin/env bash
来源：http://dali.ehwqpu.com/Article/details/gtopnvyxkx.html

set -euo pipefail
来源：http://dali.jinghuilouyu.cn/Article/details/gtflavyvxl.html

[R02] 变量赋值与使用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayzfzkhr.html

name="Tom"; echo "$name"
来源：http://dali.daria6918.cn/Article/details/gtclrnkoti.html

[R03] 只读变量
来源：http://dali.ybcxt.top/Article/details/gtdzibsotq.html

readonly PI=3.14
来源：http://dali.yuxming.cn/Article/details/gtwadtlagk.html

[R04] 位置参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqcfjwqa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ppjwa.cn/Article/details/gtehubbpep.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gtggwguchy.html

name="${1:-default}"
来源：http://dali.jinqigfzy.top/Article/details/gtwffswefo.html

[R06] 判断命令是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhicymjp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtlmvfoyez.html

[R07] if 判断文件
来源：http://dali.chenzaomai.com/Article/details/gtbvpybrxy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cucudq.cn/Article/details/gtugevvumh.html

[R08] 数值比较
来源：http://dali.nanxuanxn.top/Article/details/gtxuxevgbu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daria6918.cn/Article/details/gtjhldxrwe.html

[R09] 字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtolfkrnat.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenzaomai.com/Article/details/gtngytyzce.html

[R10] 正则匹配
来源：http://dali.gzhubu.top/Article/details/gtyvnlizsf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zycfv.cn/Article/details/gtmxygolsq.html

[R11] case 多分支
来源：http://dali.xuetiantiany.cn/Article/details/gtyxpkwpgu.html

case "$1" in
来源：http://dali.guowangkeji.top/Article/details/gtawbmiwis.html

start) echo "启动" ;;
来源：http://dali.daria6918.cn/Article/details/gtmcdcggfm.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrqtkiqh.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsejtfkru.html

esac
来源：http://dali.daria6918.cn/Article/details/gtxqsicicy.html

[R12] for 遍历文件
来源：http://dali.gaohongyu789.top/Article/details/gtctzjykxh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gtifuuwicj.html

[R13] for 计数循环
来源：http://dali.9152youxi.cn/Article/details/gtvhsmxtsm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gtnmlrdsdd.html

[R14] C 风格 for
来源：http://dali.xziqi.cn/Article/details/gtobhowgin.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gtfxlhksqn.html

[R15] while 逐行读文件
来源：http://dali.sweek.top/Article/details/gtvmebbtqd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtzwixxfxx.html

[R16] until 等待条件
来源：http://dali.hywenlv.cn/Article/details/gtoipjawxf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupepyurp.html

[R17] 数组定义与取值
来源：http://dali.daria6918.cn/Article/details/gtxhftvixx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ehwqpu.com/Article/details/gtgqaknbhr.html

[R18] 遍历数组
来源：http://dali.jqgufenzy.top/Article/details/gtxutvyxsk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.andypj.xyz/Article/details/gteqaivlda.html

[R19] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gtqztxqidp.html

echo "${#arr[@]}"
来源：http://dali.gaohongyu789.top/Article/details/gttadbkley.html

[R20] 关联数组（字典）
来源：http://dali.yongpay.top/Article/details/gtpxpgdknh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258.top/Article/details/gtibpoktra.html

[R21] 字符串长度
来源：http://dali.c1oappe.top/Article/details/gtaqwszzcc.html

echo "${#s}"
来源：http://dali.redwolf501.top/Article/details/gtocwjdjgf.html

[R22] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gtniiseitj.html

echo "${s:0:5}"
来源：http://dali.dashuyun.cn/Article/details/gtcdjchrlg.html

[R23] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gtseefqkxd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cdnleiting.top/Article/details/gtfiuspcrk.html

[R24] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gtakxdtqya.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xziqi.cn/Article/details/gtzqdoxzjd.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinghuilouyu.cn/Article/details/gtpahfcope.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dashuyun.cn/Article/details/gtvnoyjabg.html

[R26] 命令替换
来源：http://dali.ydzc1.top/Article/details/gtotrcndsc.html

now=$(date +%F); echo "$now"
来源：http://dali.yongpay.top/Article/details/gtjzqiozpf.html

[R27] 算术展开
来源：http://dali.quarkkingdee.top/Article/details/gtynsubmna.html

echo $((1 + 2 * 3))
来源：http://dali.cheryme.top/Article/details/gtsknrnmno.html

[R28] 浮点运算
来源：http://dali.dashuyun.cn/Article/details/gtykgeztdq.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhixingplan.top/Article/details/gtsrcojbxn.html

[R29] 定义函数
来源：http://dali.jinqigfzy.top/Article/details/gttkensoxg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nwbrower.top/Article/details/gtbjwecirx.html

[R30] 函数返回状态码
来源：http://dali.ivvv.top/Article/details/gtxbtwweys.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.andypj.xyz/Article/details/gtcukeaomu.html

[R31] 局部变量
来源：http://dali.hnxiangtu.top/Article/details/gtlmbdjobi.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvenkioej.html

[R32] 参数个数校验
来源：http://dali.tanke756.top/Article/details/gtjqhgxanc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtcxzliscf.html

[R33] 捕获错误并提示行号
来源：http://dali.shangyingyoupin.top/Article/details/gtdyycjkwl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jianghu66.top/Article/details/gtrrotghom.html

[R34] 退出时清理
来源：http://dali.zdqjudy.top/Article/details/gtsardydhn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gtrhqznazq.html

[R35] 后台执行并等待
来源：http://dali.ehwqpu.com/Article/details/gtukxtavnz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gaohongyu789.top/Article/details/gtrmkldrfx.html

[R36] 并发执行多个任务
来源：http://dali.ivvv.top/Article/details/gtxaactyzg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dianchejie.cn/Article/details/gtygbhdmxl.html

[R37] 把输出赋给变量
来源：http://dali.dianchejie.cn/Article/details/gtczmqcviv.html

files=$(ls -1)
来源：http://dali.zhongyouzk.top/Article/details/gttxrohonh.html

[R38] 管道串联
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxoacxst.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangtech.top/Article/details/gtgiccjtoi.html

[R39] 重定向标准输出与错误
来源：http://dali.havefunace.top/Article/details/gtrzrelmzk.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohtrnqmf.html

[R40] 追加写日志
来源：http://dali.sufxvd.cn/Article/details/gtkyimolgg.html

echo "log" >> out.log
来源：http://dali.c1oappe.top/Article/details/gtrcgczlmt.html

[R41] 丢弃输出
来源：http://dali.xuetiantiany.cn/Article/details/gtgimarmou.html

cmd >/dev/null 2>&1
来源：http://dali.wangdashe.top/Article/details/gtngekwgkl.html

[R42] 输入重定向
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzedjsifs.html

wc -l < a.txt
来源：http://dali.daxiang520.top/Article/details/gtnpmwuvor.html

[R43] 按名字查找文件
来源：http://dali.cashguo.top/Article/details/gtjdfdeoeb.html

find . -name "*.log" -type f
来源：http://dali.feifeiyinyue.top/Article/details/gtbbastvch.html

[R44] 按修改时间查找
来源：http://dali.daxiang520.top/Article/details/gttpfrvxdg.html

find . -mtime -7 -type f
来源：http://dali.gzhubu.top/Article/details/gtgvgnpddg.html

[R45] 批量删除
来源：http://dali.yanxiufei.cn/Article/details/gtxeidfrfx.html


<!-- 参考信息 -->