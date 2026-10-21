代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gttdpenbko.html

user_id INT NOT NULL,
来源：http://dali.chenzaomai.com/Article/details/gtqubkecth.html

amount DECIMAL(10, 2),
来源：http://dali.daria6918.cn/Article/details/gtgucrcuwk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tian-w.cn/Article/details/gtjqlfwtic.html

);
来源：http://dali.9152youxi.cn/Article/details/gtutkhcqci.html

[Q03] 增加列
来源：http://dali.yj20258.top/Article/details/gtxygvxbbh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.smart0.xyz/Article/details/gtpmgtcpab.html

[Q04] 修改列类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtojdjjimk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuanzhike.top/Article/details/gtsrooiyhs.html

[Q05] 重命名列
来源：http://dali.snrcjt.cn/Article/details/gtzbbtgnqb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pycfn.com/Article/details/gtzavbslsv.html

[Q06] 删除列
来源：http://dali.dashuyun.cn/Article/details/gtmyjxzsas.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jlsjyb.cn/Article/details/gthafxxtic.html

[Q07] 删除表
来源：http://dali.fzhhl.top/Article/details/gtbbtnpxqr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.0kj1m.cn/Article/details/gthmudbyux.html

[Q08] 创建普通索引
来源：http://dali.dianchejie.cn/Article/details/gtsfdloqel.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gteijppfvs.html

[Q09] 创建唯一索引
来源：http://dali.shuidangran.top/Article/details/gtbuflolql.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.quarkkingdee.top/Article/details/gtncirxcoe.html

[Q10] 插入单行
来源：http://dali.jinqigufen.top/Article/details/gtdnqhnmlq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gtgpqtyphg.html

[Q11] 一次插入多行
来源：http://dali.ehwqpu.com/Article/details/gtuckrqefc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjuankhyb.html

[Q12] 插入后取自增 ID
来源：http://dali.shzxlz.cn/Article/details/gtebucardv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gaohongyu789.top/Article/details/gtccnjnfjd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.smart0.xyz/Article/details/gtqcctcshu.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcmrxbse.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.snrcjt.cn/Article/details/gtkwuzawui.html

[Q14] 存在则更新（upsert）
来源：http://dali.quarkkingdee.top/Article/details/gtewsohxaw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yongpay.top/Article/details/gtuqxglcgl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwrrvayk.html

[Q15] 查询全部
来源：http://dali.sysykeji.top/Article/details/gttszbluzo.html

SELECT * FROM users;
来源：http://dali.cashguo.top/Article/details/gtqrcshowm.html

[Q16] 查询指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzulsyxfk.html

SELECT id, name FROM users;
来源：http://dali.xinyue.icu/Article/details/gtglfudihq.html

[Q17] 条件查询
来源：http://dali.wangdashe.top/Article/details/gtsfnpwsbc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhixingplan.top/Article/details/gthrxvcpkn.html

[Q18] 模糊匹配
来源：http://dali.yj20258.top/Article/details/gtxbwoprnk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sufxvd.cn/Article/details/gtxnbjkxkd.html

[Q19] 范围查询
来源：http://dali.jinqigfzy.top/Article/details/gtafazdytt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ydzc1.top/Article/details/gteotznxiq.html

[Q20] IN 列表
来源：http://dali.chenzaomai.com/Article/details/gtmbczwiuv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zdqjudy.top/Article/details/gtlbgplrfi.html

[Q21] 空值判断
来源：http://dali.xuanzx.com/Article/details/gtwacrdwsc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jlsjyb.cn/Article/details/gtelokpxbr.html

[Q22] 排序
来源：http://dali.daxiang520.top/Article/details/gtkupowlpe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shuidangran.top/Article/details/gtzeyurqud.html

[Q23] 分页
来源：http://dali.ppjwa.cn/Article/details/gtszgawlwl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenlongwang.top/Article/details/gteezbiwwu.html

[Q24] 去重
来源：http://dali.sweek.top/Article/details/gttazbxrze.html

SELECT DISTINCT city FROM users;
来源：http://dali.fzhhl.top/Article/details/gtiosveqon.html

[Q25] 只取前 N 条
来源：http://dali.jqgfzy.top/Article/details/gtlmwwllpp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.havefunace.top/Article/details/gtjverohyc.html

[Q26] 计数
来源：http://dali.xinyue.icu/Article/details/gtyflxizyt.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtauevgott.html

[Q27] 条件计数
来源：http://dali.haohaochexian.top/Article/details/gtewtqgten.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cashguo.top/Article/details/gtmqmilfcw.html

[Q28] 求和与平均
来源：http://dali.nanxinkj.top/Article/details/gthuykfglz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtayllyitc.html

[Q29] 最大最小值
来源：http://dali.sufxvd.cn/Article/details/gtbhvgsqsa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtukpbjyak.html

[Q30] 分组统计
来源：http://dali.vqdsnc.cn/Article/details/gtwtauxncu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtyynytvsv.html

[Q31] 分组后过滤
来源：http://dali.hfpthk.cn/Article/details/gtnwhdshnu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yonumen.top/Article/details/gtesancwzy.html

[Q32] 分组拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtooxiyrwc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtqmfnsryl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.aizwys.cn/Article/details/gtuxqehxyd.html

[Q33] 多列分组
来源：http://dali.haohaochexian.top/Article/details/gtnhkhahhr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gogol.net.cn/Article/details/gtrxpbwube.html

[Q34] 每组取第一条
来源：http://dali.birdmap.top/Article/details/gtxaajcrbp.html

SELECT * FROM (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqfgdnea.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yangfankeji.com/Article/details/gtajjqutwf.html

) t WHERE rn = 1;
来源：http://dali.hammf.cn/Article/details/gtipknhcze.html

[Q35] 内连接
来源：http://dali.tian-w.cn/Article/details/gtucdzqtaq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gthzqpgqdc.html

[Q36] 左连接
来源：http://dali.gaohongyu789.top/Article/details/gtomxojkgr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gtxdpkbfgf.html

[Q37] 右连接
来源：http://dali.yvedp.cn/Article/details/gtanutmmoz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fzhhl.top/Article/details/gtzotctpkn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.redwolf501.top/Article/details/gtobttsqau.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnqzz.top/Article/details/gtikayglkc.html

[Q39] 自连接（查上下级）
来源：http://dali.yj20258888.top/Article/details/gtwknmkahg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.pengpengdd.cyou/Article/details/gttmaacuwt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daria6918.cn/Article/details/gtdiauivau.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.andypj.xyz/Article/details/gtgemlsyjd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.316326.xyz/Article/details/gtfjxxuicc.html

[Q41] 多表连接
来源：http://dali.shzxlz.cn/Article/details/gtisdkulyh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.c1oappe.top/Article/details/gthotjnqcq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shuidangran.top/Article/details/gtxqnjnfck.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gtcgktlqug.html

[Q42] 连接条件附加过滤
来源：http://dali.zycfv.cn/Article/details/gtkugqfgcb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigfzy.top/Article/details/gtionjgvam.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.0kj1m.cn/Article/details/gtjeldrnwc.html

[Q43] 标量子查询
来源：http://dali.hysaishi.cn/Article/details/gtwtitygbq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yangfankeji.com/Article/details/gtevfpfgba.html

[Q44] IN 子查询
来源：http://dali.tianlin.xyz/Article/details/gtmglpyoki.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tanke756.top/Article/details/gtttvqozes.html

[Q45] EXISTS 判断存在
来源：http://dali.dashuyun.cn/Article/details/gtgpgtezau.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gthvcewrqv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenjidiqi.icu/Article/details/gtitjcvsca.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gttwnqbmcv.html

[Q47] 与平均值比较
来源：http://dali.yj20258888.top/Article/details/gtnezbjrmi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.iojbl.cn/Article/details/gtsfxcwwzr.html

[Q48] CTE 公用表表达式
来源：http://dali.dashuyun.cn/Article/details/gtwiquabgi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhongyouzk.top/Article/details/gtryqhzdjk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangdashe.top/Article/details/gtcqdzssjn.html

[Q49] 更新单行
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdyyfitc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtfpjvwgnc.html

[Q50] 批量更新
来源：http://dali.zhiwuduotai.top/Article/details/gtwzeyzvuh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258888.top/Article/details/gtkegaofmi.html

[Q51] 用子查询更新
来源：http://dali.hywenlv.cn/Article/details/gtmyonsalp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gtfljeckty.html

[Q52] 删除指定行
来源：http://dali.jiagoushi.top/Article/details/gtdcncvspi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gtpfmtjsqi.html

[Q53] 按条件删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtegmgzclp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gtuqnvcovg.html

[Q54] 清空表
来源：http://dali.zycfv.cn/Article/details/gtzznffgdd.html

TRUNCATE TABLE logs;
来源：http://dali.bjfxy.top/Article/details/gtgphtlbrc.html

[Q55] 排名（并列占位）
来源：http://dali.pycfn.com/Article/details/gtxmfnusvc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gtmttkqsny.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fzhhl.top/Article/details/gtwazdccbv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gtjzgbknqd.html

[Q57] 行号
来源：http://dali.zycfv.cn/Article/details/gticxtobwz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shuidangran.top/Article/details/gtmkskcevx.html

[Q58] 累计求和
来源：http://dali.yongpay.top/Article/details/gtfgvfsdah.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtvxgolfzd.html

[Q59] 分组内累计
来源：http://dali.vqdsnc.cn/Article/details/gtzmoziydn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtdjzahgtr.html

[Q60] 取上一行 / 下一行
来源：http://dali.daria6918.cn/Article/details/gtilsxrlyy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pycfn.com/Article/details/gtipybbsmg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtkrxlchjf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gtzhqdltbn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gthkkfnloy.html

[Q62] 分组占比
来源：http://dali.xinyue.icu/Article/details/gtcoiqjphb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtdfsjuplw.html

[Q63] 开启事务
来源：http://dali.gzhubu.top/Article/details/gtthwsqqxj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yanxiufei.cn/Article/details/gtpggchagd.html

[Q64] 提交事务
来源：http://dali.hammf.cn/Article/details/gtthfugcus.html

COMMIT;
来源：http://dali.hammf.cn/Article/details/gtkynfenxi.html

[Q65] 回滚事务
来源：http://dali.iojbl.cn/Article/details/gtdbnflgav.html

ROLLBACK;
来源：http://dali.ppjwa.cn/Article/details/gtoptgthib.html

[Q66] 行锁查询
来源：http://dali.zycfv.cn/Article/details/gtgztvxcri.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnqzz.top/Article/details/gtfumzaopo.html

[Q67] 设置隔离级别
来源：http://dali.tianlin.xyz/Article/details/gtbwparidj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cdnleiting.top/Article/details/gthcskhfkf.html

[Q68] 保存点
来源：http://dali.jinqigfzy.top/Article/details/gtnuexcjdq.html

SAVEPOINT sp1;
来源：http://dali.cucudq.cn/Article/details/gtfvsatrrb.html

ROLLBACK TO sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gtfzohrnpa.html

[Q69] 查看执行计划
来源：http://dali.mhx1999.top/Article/details/gteuzjiskk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsnyalzl.html

[Q70] 更新统计信息
来源：http://dali.xuanzx.com/Article/details/gtrccfroqv.html

ANALYZE TABLE users;
来源：http://dali.zhongyouzk.top/Article/details/gtxqdxnobg.html

[Q71] 查看建表语句
来源：http://dali.jinyuanbaomall.cn/Article/details/gtksxdkmwz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.feifeiyinyue.top/Article/details/gtzfsqjqgw.html

[Q72] 查看索引
来源：http://dali.hnxiangtu.top/Article/details/gtmnwtytcj.html

SHOW INDEX FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtxfpvmnes.html

[Q73] 查看表状态
来源：http://dali.hywenlv.cn/Article/details/gtkqqonjty.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinqigufen.top/Article/details/gtbczuqjwf.html

[Q74] 强制使用索引
来源：http://dali.yueranfly.top/Article/details/gtilxvtfut.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daria6918.cn/Article/details/gtgklqfots.html

[Q75] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gtgtmvtqol.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cashguo.top/Article/details/gteixxkkhn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuanzhike.top/Article/details/gtnskhrvaa.html

[Q76] 按天统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyjjsurt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nwbrower.top/Article/details/gttknhgwmk.html

[Q77] 时间加减
来源：http://dali.sweek.top/Article/details/gtxxgtbcjw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj20258888.top/Article/details/gtveclcxsp.html

[Q78] 当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gtnsmfbvlw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xylfe.cn/Article/details/gtmqbzwepx.html

[Q79] 字符串拼接
来源：http://dali.cdnleiting.top/Article/details/gtoixcbanf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yvedp.cn/Article/details/gtlnnhbdnh.html

[Q80] 字符串截取
来源：http://dali.sweek.top/Article/details/gttspyiden.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtyxivbjik.html

[Q81] 字符串替换
来源：http://dali.yj202588.top/Article/details/gtxsjufslh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtltnhuivs.html

[Q82] 字符长度与字节长度
来源：http://dali.dianchejie.cn/Article/details/gtvgftpwie.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnjyvvre.html

[Q83] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnxrgjlw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gththfmaga.html

[Q84] 去除首尾空格
来源：http://dali.ybcxt.top/Article/details/gtpfvwcplf.html

SELECT TRIM(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtyxbpucxa.html

[Q85] 数值取整
来源：http://dali.cdnleiting.top/Article/details/gtsifhpewb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.birdmap.top/Article/details/gtkzpwwdkf.html

[Q86] 读取 JSON 字段
来源：http://dali.nwbrower.top/Article/details/gtobstjfka.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jlsjyb.cn/Article/details/gtzrnufbnu.html

[Q87] JSON 字段做条件
来源：http://dali.sufxvd.cn/Article/details/gtklmuxvdb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.dianchejie.cn/Article/details/gtxcxbiyxl.html

[Q88] 行转列（条件聚合）
来源：http://dali.tianlin.xyz/Article/details/gtfrrmefhc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shzxlz.cn/Article/details/gtaxwdhtfm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.mhx1999.top/Article/details/gtbeoizssg.html

[Q89] 判断表是否存在
来源：http://dali.sysykeji.top/Article/details/gtkcbiyxag.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pycfn.com/Article/details/gtifgtppvd.html

[Q90] 生成序号列
来源：http://dali.c1oappe.top/Article/details/gtvurzmgeq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258888.top/Article/details/gtczdhrkqr.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtwjqktbig.html

R. Bash 专题
来源：http://dali.xuetiantiany.cn/Article/details/gtrfqacbah.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtakjklydz.html

[R01] shebang 与严格模式
来源：http://dali.meibo888.top/Article/details/gttpkdythd.html

#!/usr/bin/env bash
来源：http://dali.nanxinkj.top/Article/details/gtchrhbpgb.html

set -euo pipefail
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahnhlpqr.html

[R02] 变量赋值与使用
来源：http://dali.hnxiangtu.top/Article/details/gtjugztnrb.html

name="Tom"; echo "$name"
来源：http://dali.hammf.cn/Article/details/gtfgzzxxvv.html

[R03] 只读变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefuciwzr.html

readonly PI=3.14
来源：http://dali.ehwqpu.com/Article/details/gtycnffkjc.html

[R04] 位置参数
来源：http://dali.gzhubu.top/Article/details/gtjaiunmwk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.9152youxi.cn/Article/details/gttslcjmsq.html

[R05] 参数默认值
来源：http://dali.sxryk.cn/Article/details/gtohqsfadr.html

name="${1:-default}"
来源：http://dali.bjfxy.top/Article/details/gtmzdshqek.html

[R06] 判断命令是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtmipfzieg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gtwjtvclni.html

[R07] if 判断文件
来源：http://dali.feifeiyinyue.top/Article/details/gtyecjslij.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ydzc1.top/Article/details/gthvtlwrqq.html

[R08] 数值比较
来源：http://dali.xziqi.cn/Article/details/gtvgyegoef.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtyvzfqvjg.html

[R09] 字符串比较
来源：http://dali.yj202588.top/Article/details/gtzbwqyofl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtfqtouikk.html

[R10] 正则匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtvohngdvv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yvedp.cn/Article/details/gtucnzeltw.html

[R11] case 多分支
来源：http://dali.shangyingyoupin.top/Article/details/gtstzxyspa.html

case "$1" in
来源：http://dali.pycfn.com/Article/details/gtubhupovh.html

start) echo "启动" ;;
来源：http://dali.shzxlz.cn/Article/details/gtnytyrejn.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gtonqqszlu.html

*)     echo "未知命令" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtgbenjiam.html

esac
来源：http://dali.cqqwz.cn/Article/details/gtbkxmzrpy.html

[R12] for 遍历文件
来源：http://dali.zhiwuduotai.top/Article/details/gtocqdbekf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhengqikj.top/Article/details/gthwhwiqyz.html

[R13] for 计数循环
来源：http://dali.shzxlz.cn/Article/details/gtstanfswv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gtmtvlibtn.html

[R14] C 风格 for
来源：http://dali.fengsongda.top/Article/details/gtwnlvzeca.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gtxpbofozp.html

[R15] while 逐行读文件
来源：http://dali.yj202588.top/Article/details/gtnrayikoq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gttztxlgzg.html

[R16] until 等待条件
来源：http://dali.zhixingplan.top/Article/details/gthjyiacet.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtrpeaudzp.html

[R17] 数组定义与取值
来源：http://dali.tian-w.cn/Article/details/gtqzabqzga.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yueranfly.top/Article/details/gtekkwucwq.html

[R18] 遍历数组
来源：http://dali.shzxlz.cn/Article/details/gtdvffbigl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigfzy.top/Article/details/gtqmibxwgn.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gtzwpyopkb.html

echo "${#arr[@]}"
来源：http://dali.cdnleiting.top/Article/details/gtnqubevwn.html

[R20] 关联数组（字典）
来源：http://dali.cdnleiting.top/Article/details/gtabcbmsyp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtouymmflo.html

[R21] 字符串长度
来源：http://dali.guannengcc.top/Article/details/gtzaorqqlk.html

echo "${#s}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaprehqxj.html

[R22] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gtrzblvlkb.html

echo "${s:0:5}"
来源：http://dali.havefunace.top/Article/details/gtahmsydzu.html

[R23] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gtweuqjdvo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenlongwang.top/Article/details/gtamchutqk.html

[R24] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtbdgcoexi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthplcycni.html

[R25] 去后缀 / 去前缀
来源：http://dali.birdmap.top/Article/details/gtvzwcsjqr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gogol.net.cn/Article/details/gtczxmqldg.html

[R26] 命令替换
来源：http://dali.wangshuangyany.cn/Article/details/gtgqlupjco.html

now=$(date +%F); echo "$now"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzibibgt.html

[R27] 算术展开
来源：http://dali.andypj.xyz/Article/details/gtsjzixwhy.html

echo $((1 + 2 * 3))
来源：http://dali.andypj.xyz/Article/details/gteyiitzvx.html

[R28] 浮点运算
来源：http://dali.kuanghao11.cn/Article/details/gttgugqvun.html

echo "scale=2; 10/3" | bc
来源：http://dali.tanke756.top/Article/details/gtpiqcvjfz.html

[R29] 定义函数
来源：http://dali.meibo888.top/Article/details/gtzwxwbjvq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnqzz.top/Article/details/gtennmbkil.html

[R30] 函数返回状态码
来源：http://dali.zhengqikj.top/Article/details/gtlkozapbx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuxming.cn/Article/details/gtcnwyhjsg.html

[R31] 局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gtbldboeuu.html

f() { local x=1; echo "$x"; }
来源：http://dali.ivvv.top/Article/details/gtdoyaywlr.html

[R32] 参数个数校验
来源：http://dali.haohaochexian.top/Article/details/gtluinxrbo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipxdkeqj.html

[R33] 捕获错误并提示行号
来源：http://dali.gaohongyu789.top/Article/details/gtsmjvagay.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangshuangyany.cn/Article/details/gtspztjmsg.html

[R34] 退出时清理
来源：http://dali.tanke756.top/Article/details/gtrvrixgwf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenlongwang.top/Article/details/gtlssxqpzw.html

[R35] 后台执行并等待
来源：http://dali.zhengqikj.top/Article/details/gtfztjqaug.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gtzbctztgm.html

[R36] 并发执行多个任务
来源：http://dali.yangfankeji.com/Article/details/gttdjugjnm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gaohongyu789.top/Article/details/gtgzbjpnad.html

[R37] 把输出赋给变量
来源：http://dali.smart0.xyz/Article/details/gtysjymfro.html

files=$(ls -1)
来源：http://dali.dashuyun.cn/Article/details/gtrxwlbucd.html

[R38] 管道串联
来源：http://dali.cheryme.top/Article/details/gtivoudrwo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cucudq.cn/Article/details/gtafnosorc.html

[R39] 重定向标准输出与错误
来源：http://dali.guannengcc.top/Article/details/gtqczblwha.html

cmd > out.log 2>&1
来源：http://dali.guannengcc.top/Article/details/gtfwsgybbl.html

[R40] 追加写日志
来源：http://dali.zhongyouzk.top/Article/details/gtqvqyqgzb.html

echo "log" >> out.log
来源：http://dali.nanxuanxn.top/Article/details/gtrgqdfatv.html

[R41] 丢弃输出
来源：http://dali.nwbrower.top/Article/details/gtyaatoony.html

cmd >/dev/null 2>&1
来源：http://dali.9152youxi.cn/Article/details/gtuqrrmuso.html

[R42] 输入重定向
来源：http://dali.0kj1m.cn/Article/details/gtjoiekupg.html

wc -l < a.txt
来源：http://dali.cqqwz.cn/Article/details/gtirlrpior.html

[R43] 按名字查找文件
来源：http://dali.shzxlz.cn/Article/details/gtyxliagiy.html

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gtxpkzsetv.html

[R44] 按修改时间查找
来源：http://dali.birdmap.top/Article/details/gtynujglrd.html

find . -mtime -7 -type f
来源：http://dali.cashguo.top/Article/details/gtkxzclzeu.html

[R45] 批量删除
来源：http://dali.fzhhl.top/Article/details/gtmqyvvams.html

find . -name "*.tmp" -delete
来源：http://dali.xuetiantiany.cn/Article/details/gtmvbluzyz.html

[R46] 递归替换文件内容
来源：http://dali.0kj1m.cn/Article/details/gtkjywjpax.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.daria6918.cn/Article/details/gtbqpfsaez.html

[R47] sed 单行替换
来源：http://dali.zhengqikj.top/Article/details/gtuxgrjkal.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ivvv.top/Article/details/gtgxasewqc.html

[R48] awk 取指定列
来源：http://dali.xuanzx.com/Article/details/gtvtwbpvjm.html

awk '{print $1, $3}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtotkgdjoy.html

[R49] awk 带条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljtvcbhh.html


<!-- 参考信息 -->