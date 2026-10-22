代发 wailian999

CREATE TABLE users (
来源：http://dali.jiagoushi.top/Article/details/gt2bamzogns.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gt2meicknoh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gt2fkavrlva.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jianghu66.top/Article/details/gt2alhkvhrv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.fengsongda.top/Article/details/gt2ugyntrpt.html

);
来源：http://dali.yanxiufei.cn/Article/details/gt2ccrqoyxd.html

[Q02] 创建带外键的表
来源：http://dali.birdmap.top/Article/details/gt2gckrdcme.html

CREATE TABLE orders (
来源：http://dali.tanke756.top/Article/details/gt2dpbeknsb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gt2knaivwrn.html

user_id INT NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gt2rczqtbxb.html

amount DECIMAL(10, 2),
来源：http://dali.hysaishi.cn/Article/details/gt2noarsdgj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sufxvd.cn/Article/details/gt2dcfouzva.html

);
来源：http://dali.cucudq.cn/Article/details/gt2fwilpvat.html

[Q03] 增加列
来源：http://dali.xuanzx.com/Article/details/gt2wpidkxeq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hongshengwenyu.top/Article/details/gt2bwkxgqii.html

[Q04] 修改列类型
来源：http://dali.yvedp.cn/Article/details/gt2tlzzmrcp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.9152youxi.cn/Article/details/gt2kvscnqzg.html

[Q05] 重命名列
来源：http://dali.wangshuangyany.cn/Article/details/gt2wdhtvgzv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fengsongda.top/Article/details/gt2nmvzeanr.html

[Q06] 删除列
来源：http://dali.xuetiantiany.cn/Article/details/gt2vqkqckcv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhoulong.xyz/Article/details/gt2pwzmupdg.html

[Q07] 删除表
来源：http://dali.yongpay.top/Article/details/gt2fyscnesc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yongpay.top/Article/details/gt2hnqujlsl.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gt2mxwslgac.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gt2kqpvubcc.html

[Q09] 创建唯一索引
来源：http://dali.pycfn.com/Article/details/gt2xcvijnfp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gt2nfhblqov.html

[Q10] 插入单行
来源：http://dali.zhengqikj.top/Article/details/gt2yhfxuwko.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fengsongda.top/Article/details/gt2wpuanmsa.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qswuiqhj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhixingplan.top/Article/details/gt2pwxjypwu.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgfzy.top/Article/details/gt2heqwtekq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhongyouzk.top/Article/details/gt2jzxntjwk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuanzhike.top/Article/details/gt2xnyqhgoz.html

[Q13] 忽略重复插入
来源：http://dali.ppjwa.cn/Article/details/gt2lpyihsxb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gogol.net.cn/Article/details/gt2xwdwosxa.html

[Q14] 存在则更新（upsert）
来源：http://dali.0kj1m.cn/Article/details/gt2jfohtuyu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhoulong.xyz/Article/details/gt2zxvqtbms.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ygewtrum.html

[Q15] 查询全部
来源：http://dali.tanke756.top/Article/details/gt2brkdfpro.html

SELECT * FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2upbfkhsa.html

[Q16] 查询指定列
来源：http://dali.sufxvd.cn/Article/details/gt2gwuhdzkl.html

SELECT id, name FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2xkgcqeae.html

[Q17] 条件查询
来源：http://dali.gzhubu.top/Article/details/gt2wfvrqklt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hkplsxvk.html

[Q18] 模糊匹配
来源：http://dali.cdnleiting.top/Article/details/gt2melthrek.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jlsjyb.cn/Article/details/gt2ydvfxpnp.html

[Q19] 范围查询
来源：http://dali.jlsjyb.cn/Article/details/gt2eaumhtjv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.316326.xyz/Article/details/gt2cjubfeet.html

[Q20] IN 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ebvuqjrf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shuidangran.top/Article/details/gt2pgenhsve.html

[Q21] 空值判断
来源：http://dali.zdqjudy.top/Article/details/gt2hmydmhzh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tian-w.cn/Article/details/gt2lflgytfy.html

[Q22] 排序
来源：http://dali.0kj1m.cn/Article/details/gt2qthzzebv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj202588.top/Article/details/gt2fnfffoct.html

[Q23] 分页
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ufmsmzhc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenjidiqi.icu/Article/details/gt2jnocfrqk.html

[Q24] 去重
来源：http://dali.birdmap.top/Article/details/gt2xgiwilqv.html

SELECT DISTINCT city FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2zfvzrvqt.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoonqhz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.andypj.xyz/Article/details/gt2wyjlthrc.html

[Q26] 计数
来源：http://dali.tianlin.xyz/Article/details/gt2vwpcwzwi.html

SELECT COUNT(*) FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2fthduook.html

[Q27] 条件计数
来源：http://dali.zhiwuduotai.top/Article/details/gt2mbwxwcts.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yonumen.top/Article/details/gt2jlqrmxxm.html

[Q28] 求和与平均
来源：http://dali.guowangkeji.top/Article/details/gt2jscydenn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2sykfwzsn.html

[Q29] 最大最小值
来源：http://dali.9152youxi.cn/Article/details/gt2wiyewmzj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2oanjsntx.html

[Q30] 分组统计
来源：http://dali.chenzaomai.com/Article/details/gt2mfxihccy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gt2ozhgogxp.html

[Q31] 分组后过滤
来源：http://dali.ivvv.top/Article/details/gt2gzkbpiyd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xylfe.cn/Article/details/gt2jjixnrxf.html

[Q32] 分组拼接字符串
来源：http://dali.jianghu66.top/Article/details/gt2vbenusvg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gt2zrikthcb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.birdmap.top/Article/details/gt2wuyusory.html

[Q33] 多列分组
来源：http://dali.ehwqpu.com/Article/details/gt2tomaggxr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.0kj1m.cn/Article/details/gt2jqrbrsvx.html

[Q34] 每组取第一条
来源：http://dali.yueranfly.top/Article/details/gt2ivofdouj.html

SELECT * FROM (
来源：http://dali.zhengqikj.top/Article/details/gt2swehhwoj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.iojbl.cn/Article/details/gt2aegfnysk.html

) t WHERE rn = 1;
来源：http://dali.hammf.cn/Article/details/gt2sfonwekf.html

[Q35] 内连接
来源：http://dali.sufxvd.cn/Article/details/gt2rofdroyx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2sdytljkz.html

[Q36] 左连接
来源：http://dali.jinqigufen.top/Article/details/gt2cojmqosb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgfzy.top/Article/details/gt2ruwnabij.html

[Q37] 右连接
来源：http://dali.xuanzx.com/Article/details/gt2ffmagbzn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbdmegn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tianlin.xyz/Article/details/gt2stgwppgu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.svipenyu.cn/Article/details/gt2ikuutimn.html

[Q39] 自连接（查上下级）
来源：http://dali.xylfe.cn/Article/details/gt2opvbvdnv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guowangkeji.top/Article/details/gt2upoojmzp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj202588.top/Article/details/gt2qitarnwq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenlongwang.top/Article/details/gt2rofuveer.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xziqi.cn/Article/details/gt2xtogcsmh.html

[Q41] 多表连接
来源：http://dali.yueranfly.top/Article/details/gt2itosifwq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuxming.cn/Article/details/gt2qghnfkls.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenzaomai.com/Article/details/gt2hthhmfkk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cashguo.top/Article/details/gt2jhritlve.html

[Q42] 连接条件附加过滤
来源：http://dali.jyoumei.cn/Article/details/gt2fqvpcdjs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gaohongyu789.top/Article/details/gt2kixjidaw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmixvwnj.html

[Q43] 标量子查询
来源：http://dali.chenjidiqi.icu/Article/details/gt2lldpjvyf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dianchejie.cn/Article/details/gt2wxltvych.html

[Q44] IN 子查询
来源：http://dali.chenzaomai.com/Article/details/gt2daihcwma.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2slhfebpv.html

[Q45] EXISTS 判断存在
来源：http://dali.yangfankeji.com/Article/details/gt2yqhreagm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gt2katihlgw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yangfankeji.com/Article/details/gt2vmtfaupj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gt2lnnlqtgl.html

[Q47] 与平均值比较
来源：http://dali.shzxlz.cn/Article/details/gt2hadvcaww.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shzxlz.cn/Article/details/gt2brkrgxyw.html

[Q48] CTE 公用表表达式
来源：http://dali.cdnleiting.top/Article/details/gt2yvffrwpw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ynlmkpyz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gotoacloud.top/Article/details/gt2rckxnifw.html

[Q49] 更新单行
来源：http://dali.yj20258.top/Article/details/gt2nizkeopz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gt2ubqzbxhl.html

[Q50] 批量更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2rkzzviza.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258.top/Article/details/gt2vdsyojge.html

[Q51] 用子查询更新
来源：http://dali.jiagoushi.top/Article/details/gt2uvywlyjc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nwbrower.top/Article/details/gt2nnawcdix.html

[Q52] 删除指定行
来源：http://dali.sufxvd.cn/Article/details/gt2qssvttaj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gt2edexjubz.html

[Q53] 按条件删除
来源：http://dali.kuanghao11.cn/Article/details/gt2lwtafhdi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daria6918.cn/Article/details/gt2wnhfwwuf.html

[Q54] 清空表
来源：http://dali.chenzaomai.com/Article/details/gt2ulnrcaoj.html

TRUNCATE TABLE logs;
来源：http://dali.jiagoushi.top/Article/details/gt2sxurdzhe.html

[Q55] 排名（并列占位）
来源：http://dali.havefunace.top/Article/details/gt2mjfuteai.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yonumen.top/Article/details/gt2pjuwvwli.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guowangkeji.top/Article/details/gt2uuetgcjo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fzhhl.top/Article/details/gt2olysgohb.html

[Q57] 行号
来源：http://dali.guowangkeji.top/Article/details/gt2vidabcdv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2lervwmea.html

[Q58] 累计求和
来源：http://dali.dashuyun.cn/Article/details/gt2azqmrxpt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2omkwfeax.html

[Q59] 分组内累计
来源：http://dali.hnxiangtu.top/Article/details/gt2wzxgogau.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2ydsczmyz.html

[Q60] 取上一行 / 下一行
来源：http://dali.shangyingyoupin.top/Article/details/gt2wacseqja.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jiagoushi.top/Article/details/gt2iwwjmcpd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.316326.xyz/Article/details/gt2njzekksq.html

[Q61] 移动平均
来源：http://dali.andypj.xyz/Article/details/gt2tuzekgzo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2tjzuoxuj.html

[Q62] 分组占比
来源：http://dali.pengpengdd.cyou/Article/details/gt2mbgzaysi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gt2zrgziets.html

[Q63] 开启事务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhslpmxq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dashuyun.cn/Article/details/gt2jxsbrzss.html

[Q64] 提交事务
来源：http://dali.zhiwuduotai.top/Article/details/gt2dvuqvgqr.html

COMMIT;
来源：http://dali.tianlin.xyz/Article/details/gt2bobtmqzv.html

[Q65] 回滚事务
来源：http://dali.hongshengwenyu.top/Article/details/gt2ktsnhena.html

ROLLBACK;
来源：http://dali.jqgufenzy.top/Article/details/gt2zhnfnhgk.html

[Q66] 行锁查询
来源：http://dali.bjfxy.top/Article/details/gt2eyhoraan.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yonumen.top/Article/details/gt2ikxpnxcn.html

[Q67] 设置隔离级别
来源：http://dali.jlsjyb.cn/Article/details/gt2shrwkwrs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sxryk.cn/Article/details/gt2nabqfwgj.html

[Q68] 保存点
来源：http://dali.yonumen.top/Article/details/gt2mddjeogn.html

SAVEPOINT sp1;
来源：http://dali.zdqjudy.top/Article/details/gt2jjbntgmq.html

ROLLBACK TO sp1;
来源：http://dali.316326.xyz/Article/details/gt2dpfuulyb.html

[Q69] 查看执行计划
来源：http://dali.cucudq.cn/Article/details/gt2warzhoxt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yangfankeji.com/Article/details/gt2biytnjkg.html

[Q70] 更新统计信息
来源：http://dali.jyoumei.cn/Article/details/gt2auyaxogp.html

ANALYZE TABLE users;
来源：http://dali.yongpay.top/Article/details/gt2hyuwruoa.html

[Q71] 查看建表语句
来源：http://dali.hfpthk.cn/Article/details/gt2uvxcpcdi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jlsjyb.cn/Article/details/gt2umwrwghk.html

[Q72] 查看索引
来源：http://dali.bjfxy.top/Article/details/gt2xdojmaqz.html

SHOW INDEX FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2lmczukul.html

[Q73] 查看表状态
来源：http://dali.fengsongda.top/Article/details/gt2tehjhjdv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jiagoushi.top/Article/details/gt2psvflgmq.html

[Q74] 强制使用索引
来源：http://dali.zycfv.cn/Article/details/gt2wjykerxy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ybcxt.top/Article/details/gt2ucbroihj.html

[Q75] 日期格式化
来源：http://dali.guowangkeji.top/Article/details/gt2upgtlnin.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2lckowhup.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.vqdsnc.cn/Article/details/gt2spriilsg.html

[Q76] 按天统计
来源：http://dali.haohaochexian.top/Article/details/gt2carwruwu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sufxvd.cn/Article/details/gt2idxeghei.html

[Q77] 时间加减
来源：http://dali.cqqwz.cn/Article/details/gt2nsjmrrts.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xziqi.cn/Article/details/gt2otyikrbe.html

[Q78] 当前时间
来源：http://dali.nanxinkj.top/Article/details/gt2svihfzep.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yongpay.top/Article/details/gt2jimfckhj.html

[Q79] 字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gt2lpqerqtx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fengsongda.top/Article/details/gt2gbooueyo.html

[Q80] 字符串截取
来源：http://dali.yj20258.top/Article/details/gt2gpjmcuzj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sweek.top/Article/details/gt2gwffewdx.html

[Q81] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gt2xjdouwja.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2dzzuvfxk.html

[Q82] 字符长度与字节长度
来源：http://dali.316326.xyz/Article/details/gt2ngxpfnex.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2znrzdhbk.html

[Q83] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2npanjrpc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2mfxwdrpf.html

[Q84] 去除首尾空格
来源：http://dali.ppjwa.cn/Article/details/gt2kvfwdysu.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2swsbdkwi.html

[Q85] 数值取整
来源：http://dali.9152youxi.cn/Article/details/gt2yxordyiw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.quarkkingdee.top/Article/details/gt2twszcoic.html

[Q86] 读取 JSON 字段
来源：http://dali.fzhhl.top/Article/details/gt2iellekmz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.guowangkeji.top/Article/details/gt2beeehpzy.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258.top/Article/details/gt2kxytsluy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ucxglhjr.html

[Q88] 行转列（条件聚合）
来源：http://dali.tanke756.top/Article/details/gt2wyzwgtev.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yonumen.top/Article/details/gt2rpshwhtk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2jbwcmnnb.html

[Q89] 判断表是否存在
来源：http://dali.sysykeji.top/Article/details/gt2kwficcou.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.kuanghao11.cn/Article/details/gt2aezdcuxw.html

[Q90] 生成序号列
来源：http://dali.zhengqikj.top/Article/details/gt2qdvwpyap.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigufen.top/Article/details/gt2vgsdjtrx.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2diekaqld.html

R. Bash 专题
来源：http://dali.svipenyu.cn/Article/details/gt2uvkdyztt.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ymexgnru.html

[R01] shebang 与严格模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uwwtjxaw.html

#!/usr/bin/env bash
来源：http://dali.pycfn.com/Article/details/gt2gxkfzivp.html

set -euo pipefail
来源：http://dali.ppjwa.cn/Article/details/gt2rpbsyklj.html

[R02] 变量赋值与使用
来源：http://dali.jlsjyb.cn/Article/details/gt2vgwwqjza.html

name="Tom"; echo "$name"
来源：http://dali.ydzc1.top/Article/details/gt2klnmgsww.html

[R03] 只读变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mfrvwcjf.html

readonly PI=3.14
来源：http://dali.chenlongwang.top/Article/details/gt2dzvlegct.html

[R04] 位置参数
来源：http://dali.yangfankeji.com/Article/details/gt2mewladkw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yueranfly.top/Article/details/gt2csdkbrdd.html

[R05] 参数默认值
来源：http://dali.ivvv.top/Article/details/gt2aujgjwrl.html

name="${1:-default}"
来源：http://dali.chenlongwang.top/Article/details/gt2rwkmiosl.html

[R06] 判断命令是否存在
来源：http://dali.gogol.net.cn/Article/details/gt2ofmebwxs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sweek.top/Article/details/gt2flsdogwf.html

[R07] if 判断文件
来源：http://dali.vqdsnc.cn/Article/details/gt2pdjdrvli.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigufen.top/Article/details/gt2hzfbubmg.html

[R08] 数值比较
来源：http://dali.9152youxi.cn/Article/details/gt2axcntgak.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yueranfly.top/Article/details/gt2owoyburz.html

[R09] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2joajdczr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnqzz.top/Article/details/gt2xpqfvyfd.html

[R10] 正则匹配
来源：http://dali.yangfankeji.com/Article/details/gt2hpywgwob.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2veosukhw.html

[R11] case 多分支
来源：http://dali.ppjwa.cn/Article/details/gt2dooulcdo.html

case "$1" in
来源：http://dali.jinqigfzy.top/Article/details/gt2wgyqgyse.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vemixuyv.html

stop)  echo "停止" ;;
来源：http://dali.hywenlv.cn/Article/details/gt2plugwiol.html

*)     echo "未知命令" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tizljrnv.html

esac
来源：http://dali.316326.xyz/Article/details/gt2mojtjczi.html

[R12] for 遍历文件
来源：http://dali.daria6918.cn/Article/details/gt2hgbwjosk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhongyouzk.top/Article/details/gt2jqlyktjr.html

[R13] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gt2ffwjhxtv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gt2hnbtxhyk.html

[R14] C 风格 for
来源：http://dali.hfpthk.cn/Article/details/gt2qetrzzbj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gt2rflcdnec.html

[R15] while 逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dgcatqms.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gzhubu.top/Article/details/gt2atqhxqlf.html

[R16] until 等待条件
来源：http://dali.zycfv.cn/Article/details/gt2uvbsxyox.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gt2ufaxluij.html

[R17] 数组定义与取值
来源：http://dali.gotoacloud.top/Article/details/gt2lcycnxez.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vrntayuh.html

[R18] 遍历数组
来源：http://dali.wangdashe.top/Article/details/gt2jrynmjzs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ehwqpu.com/Article/details/gt2gvwruxwh.html

[R19] 数组长度
来源：http://dali.fengsongda.top/Article/details/gt2efbqhuoo.html

echo "${#arr[@]}"
来源：http://dali.cdnleiting.top/Article/details/gt2yivuffng.html

[R20] 关联数组（字典）
来源：http://dali.meibo888.top/Article/details/gt2mdyynwzb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgfzy.top/Article/details/gt2mphkasyi.html

[R21] 字符串长度
来源：http://dali.316326.xyz/Article/details/gt2ywxhroah.html

echo "${#s}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tsgncunx.html

[R22] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gt2zrijcsbd.html

echo "${s:0:5}"
来源：http://dali.yangfankeji.com/Article/details/gt2ujgucagp.html

[R23] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gt2exnrzbma.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258.top/Article/details/gt2lxsosijj.html

[R24] 大小写转换
来源：http://dali.yj20258.top/Article/details/gt2nculqppm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guowangkeji.top/Article/details/gt2gmlgizoh.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenlongwang.top/Article/details/gt2oiczqalv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aibaodan.cn/Article/details/gt2snfomrav.html

[R26] 命令替换
来源：http://dali.ppjwa.cn/Article/details/gt2tohylgfy.html

now=$(date +%F); echo "$now"
来源：http://dali.gotoacloud.top/Article/details/gt2vchbtqee.html

[R27] 算术展开
来源：http://dali.shuidangran.top/Article/details/gt2voxmcvgo.html

echo $((1 + 2 * 3))
来源：http://dali.wangshuangyany.cn/Article/details/gt2mxicgxrh.html

[R28] 浮点运算
来源：http://dali.yj20258888.top/Article/details/gt2pzwnfzix.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgfzy.top/Article/details/gt2xnsowagi.html

[R29] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2spumjvmf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xvjonktm.html

[R30] 函数返回状态码
来源：http://dali.cheryme.top/Article/details/gt2bnybobpe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yvedp.cn/Article/details/gt2bbdyqiyk.html

[R31] 局部变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dlyouhfs.html

f() { local x=1; echo "$x"; }
来源：http://dali.cdnleiting.top/Article/details/gt2ljwvjveu.html

[R32] 参数个数校验
来源：http://dali.jinqigufen.top/Article/details/gt2hkjnafxc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tearukov.html

[R33] 捕获错误并提示行号
来源：http://dali.quarkkingdee.top/Article/details/gt2uvonrvdh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yangfankeji.com/Article/details/gt2yfrmjjtc.html

[R34] 退出时清理
来源：http://dali.yj20258888.top/Article/details/gt2vnflzdzj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guannengcc.top/Article/details/gt2oxurdykp.html

[R35] 后台执行并等待
来源：http://dali.yuxming.cn/Article/details/gt2tcawkprs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuxming.cn/Article/details/gt2inlihlaj.html

[R36] 并发执行多个任务
来源：http://dali.yueranfly.top/Article/details/gt2vqxzuyzl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ybcxt.top/Article/details/gt2zsgmizwo.html

[R37] 把输出赋给变量
来源：http://dali.mhx1999.top/Article/details/gt2eokeyzpf.html

files=$(ls -1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xeqvfnxi.html

[R38] 管道串联
来源：http://dali.shzxlz.cn/Article/details/gt2yfidzhkw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.0kj1m.cn/Article/details/gt2ebvqgkio.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxinkj.top/Article/details/gt2zbirtjrl.html

cmd > out.log 2>&1
来源：http://dali.chenzaomai.com/Article/details/gt2wpblvbuv.html

[R40] 追加写日志
来源：http://dali.iojbl.cn/Article/details/gt2ouedxxva.html

echo "log" >> out.log
来源：http://dali.yuxming.cn/Article/details/gt2jlduthyl.html

[R41] 丢弃输出
来源：http://dali.fengsongda.top/Article/details/gt2hnehoxxm.html

cmd >/dev/null 2>&1
来源：http://dali.nwbrower.top/Article/details/gt2rcikbyyi.html

[R42] 输入重定向
来源：http://dali.andypj.xyz/Article/details/gt2fawwmkma.html

wc -l < a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2qxsauicn.html

[R43] 按名字查找文件
来源：http://dali.9152youxi.cn/Article/details/gt2gukxqzoq.html

find . -name "*.log" -type f
来源：http://dali.jinqigufen.top/Article/details/gt2kvtujsuf.html

[R44] 按修改时间查找
来源：http://dali.zhiwuduotai.top/Article/details/gt2cpfszgrj.html

find . -mtime -7 -type f
来源：http://dali.yanxiufei.cn/Article/details/gt2gmsyewuq.html

[R45] 批量删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2siigbfss.html


<!-- 参考信息 -->