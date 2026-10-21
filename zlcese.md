代发 wailian999

CREATE TABLE users (
来源：http://dali.hongshengwenyu.top/Article/details/gtxmnnqwui.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gtizoaauex.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gtxqthtcly.html

email VARCHAR(100) UNIQUE,
来源：http://dali.mhx1999.top/Article/details/gtcgewnhuj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuetiantiany.cn/Article/details/gtediapqdb.html

);
来源：http://dali.ehwqpu.com/Article/details/gtybafvzns.html

[Q02] 创建带外键的表
来源：http://dali.zhengqikj.top/Article/details/gtfhlwjfbn.html

CREATE TABLE orders (
来源：http://dali.guowangkeji.top/Article/details/gtscjfbzje.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtsdtzouwd.html

user_id INT NOT NULL,
来源：http://dali.wangdashe.top/Article/details/gtrvsxxebw.html

amount DECIMAL(10, 2),
来源：http://dali.guannengcc.top/Article/details/gtkcltdnrb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aibaodan.cn/Article/details/gtpdkntfdx.html

);
来源：http://dali.tian-w.cn/Article/details/gtbzcdcbhl.html

[Q03] 增加列
来源：http://dali.hnxiangtu.top/Article/details/gtecrpncii.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sufxvd.cn/Article/details/gtnrznofce.html

[Q04] 修改列类型
来源：http://dali.shuidangran.top/Article/details/gtmkgukmtz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jiagoushi.top/Article/details/gtlmsrbfgq.html

[Q05] 重命名列
来源：http://dali.gogol.net.cn/Article/details/gtfleqraej.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shzxlz.cn/Article/details/gtxyinwucv.html

[Q06] 删除列
来源：http://dali.ivvv.top/Article/details/gtcxcpzbyx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.redwolf501.top/Article/details/gtqqcapwhx.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gtwfyizckh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwmqggxc.html

[Q08] 创建普通索引
来源：http://dali.haohaochexian.top/Article/details/gtkprsakgq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.mhx1999.top/Article/details/gtmzhipdji.html

[Q09] 创建唯一索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnoesonz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gtrscumnss.html

[Q10] 插入单行
来源：http://dali.yvedp.cn/Article/details/gthhysrsbx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gotoacloud.top/Article/details/gtqzkayihu.html

[Q11] 一次插入多行
来源：http://dali.jlsjyb.cn/Article/details/gtjqeoiwol.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nwbrower.top/Article/details/gtsunrkmjg.html

[Q12] 插入后取自增 ID
来源：http://dali.zhongyouzk.top/Article/details/gtwasxcepb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.haohaochexian.top/Article/details/gtmunkjzwn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhongyouzk.top/Article/details/gtikecucfc.html

[Q13] 忽略重复插入
来源：http://dali.shuidangran.top/Article/details/gticxchvec.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtbsadasmr.html

[Q14] 存在则更新（upsert）
来源：http://dali.snrcjt.cn/Article/details/gtljnyoczt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yanxiufei.cn/Article/details/gtlhhbpigm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xziqi.cn/Article/details/gtrwhepamq.html

[Q15] 查询全部
来源：http://dali.yongpay.top/Article/details/gtelskqmfc.html

SELECT * FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwnkxsyo.html

[Q16] 查询指定列
来源：http://dali.cdnleiting.top/Article/details/gtfmfneaqr.html

SELECT id, name FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtqshzeozn.html

[Q17] 条件查询
来源：http://dali.zycfv.cn/Article/details/gtwlbxxcuk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsyntpign.html

[Q18] 模糊匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtmmtirfxg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.iojbl.cn/Article/details/gtizbyvtsc.html

[Q19] 范围查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymlaexpd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daxiang520.top/Article/details/gtiulmluhh.html

[Q20] IN 列表
来源：http://dali.fzhhl.top/Article/details/gtoftrdmcq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tian-w.cn/Article/details/gttxwtymsr.html

[Q21] 空值判断
来源：http://dali.xinyue.icu/Article/details/gtytzbktkp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gotoacloud.top/Article/details/gtwsrlycag.html

[Q22] 排序
来源：http://dali.meibo888.top/Article/details/gtkbvfuggv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gtdzfjyssa.html

[Q23] 分页
来源：http://dali.zdqjudy.top/Article/details/gtamxnocsq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.9152youxi.cn/Article/details/gtogcwvjjj.html

[Q24] 去重
来源：http://dali.aizwys.cn/Article/details/gtramilmhq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtyvskdbko.html

[Q25] 只取前 N 条
来源：http://dali.yj202588.top/Article/details/gttkokdvuh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xziqi.cn/Article/details/gtfnfyrfvn.html

[Q26] 计数
来源：http://dali.andypj.xyz/Article/details/gtdlanmjfl.html

SELECT COUNT(*) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtopuakaqs.html

[Q27] 条件计数
来源：http://dali.meibo888.top/Article/details/gtlijaoedu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtlkzaqjof.html

[Q28] 求和与平均
来源：http://dali.cdnleiting.top/Article/details/gtwljluaxe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtumypowya.html

[Q29] 最大最小值
来源：http://dali.sxryk.cn/Article/details/gtvstitgfi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.havefunace.top/Article/details/gtodhdgntp.html

[Q30] 分组统计
来源：http://dali.pengpengdd.cyou/Article/details/gtfocqrtao.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gttjxvnpds.html

[Q31] 分组后过滤
来源：http://dali.mhx1999.top/Article/details/gtkfwhgqgr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hysaishi.cn/Article/details/gtktvifblr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtxqiorvpb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtpmxxlbwb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guannengcc.top/Article/details/gtescrcxrf.html

[Q33] 多列分组
来源：http://dali.meibo888.top/Article/details/gtccdqiaar.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cqqwz.cn/Article/details/gtrukjlbcu.html

[Q34] 每组取第一条
来源：http://dali.pengpengdd.cyou/Article/details/gtdlqowcqm.html

SELECT * FROM (
来源：http://dali.snrcjt.cn/Article/details/gtddaawczz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tian-w.cn/Article/details/gtnyksqkxl.html

) t WHERE rn = 1;
来源：http://dali.cdnleiting.top/Article/details/gtblwdsodx.html

[Q35] 内连接
来源：http://dali.0kj1m.cn/Article/details/gtmmgtrnga.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gtjmkazafd.html

[Q36] 左连接
来源：http://dali.nwbrower.top/Article/details/gtwfqjicog.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gtqkfgkfsf.html

[Q37] 右连接
来源：http://dali.andypj.xyz/Article/details/gtyyrxosve.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigfzy.top/Article/details/gttujifnxi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fengsongda.top/Article/details/gtvuxnosrq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangdashe.top/Article/details/gthjoddmgx.html

[Q39] 自连接（查上下级）
来源：http://dali.xylfe.cn/Article/details/gtdbwkpzjx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yueranfly.top/Article/details/gtzsdmfidl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gttdjslqao.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tian-w.cn/Article/details/gtcknqizns.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.bjfxy.top/Article/details/gtyzpqnydz.html

[Q41] 多表连接
来源：http://dali.meibo888.top/Article/details/gtkiqveyam.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenzaomai.com/Article/details/gtbhcailsl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zdqjudy.top/Article/details/gtjlgufnwc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.birdmap.top/Article/details/gtiubexvdg.html

[Q42] 连接条件附加过滤
来源：http://dali.gogol.net.cn/Article/details/gtnyzuoghx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.dashuyun.cn/Article/details/gtxgybdcne.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cdnleiting.top/Article/details/gtpncegpqh.html

[Q43] 标量子查询
来源：http://dali.svipenyu.cn/Article/details/gtujrrxvgc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.snrcjt.cn/Article/details/gtqvoaxwrp.html

[Q44] IN 子查询
来源：http://dali.hfpthk.cn/Article/details/gtwsngqoni.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenlongwang.top/Article/details/gtmjzeoknh.html

[Q45] EXISTS 判断存在
来源：http://dali.gaohongyu789.top/Article/details/gtuwwbcsfx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gtxoupvaom.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cdnleiting.top/Article/details/gtakycaydz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gtkwqcxwyf.html

[Q47] 与平均值比较
来源：http://dali.svipenyu.cn/Article/details/gtlxsmiget.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpfscswi.html

[Q48] CTE 公用表表达式
来源：http://dali.chenlongwang.top/Article/details/gtzubzacfe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhixingplan.top/Article/details/gtoakqqzox.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.smart0.xyz/Article/details/gtzvguyqhq.html

[Q49] 更新单行
来源：http://dali.bjfxy.top/Article/details/gtlpcereuz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gterdtgkpd.html

[Q50] 批量更新
来源：http://dali.hnxiangtu.top/Article/details/gtbngdxngs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tianlin.xyz/Article/details/gtetbhegzh.html

[Q51] 用子查询更新
来源：http://dali.zycfv.cn/Article/details/gtnelusjkr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cdnleiting.top/Article/details/gtrlqlmwyq.html

[Q52] 删除指定行
来源：http://dali.kuanghao11.cn/Article/details/gtoppwebge.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gtmmgejrdk.html

[Q53] 按条件删除
来源：http://dali.cqqwz.cn/Article/details/gtvsrnkvxy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xylfe.cn/Article/details/gtpqwuvndu.html

[Q54] 清空表
来源：http://dali.hnxiangtu.top/Article/details/gtpgyzsxtf.html

TRUNCATE TABLE logs;
来源：http://dali.kuanghao11.cn/Article/details/gtrplpjeci.html

[Q55] 排名（并列占位）
来源：http://dali.ydzc1.top/Article/details/gthprqpoln.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sxryk.cn/Article/details/gtobgozutp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtngrlrucz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xziqi.cn/Article/details/gtmsdxxwlj.html

[Q57] 行号
来源：http://dali.yuxming.cn/Article/details/gthtzpffaq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ybcxt.top/Article/details/gtoluamqlx.html

[Q58] 累计求和
来源：http://dali.jyoumei.cn/Article/details/gtbgorypjw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtprjokesv.html

[Q59] 分组内累计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgvgbant.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtofmjfacx.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmvmbwul.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zdqjudy.top/Article/details/gtxbqexjoy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtmysfbiqd.html

[Q61] 移动平均
来源：http://dali.jqgfzy.top/Article/details/gtijtslysv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpkdujdq.html

[Q62] 分组占比
来源：http://dali.gogol.net.cn/Article/details/gtajfyztwa.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtjalvupiy.html

[Q63] 开启事务
来源：http://dali.kuanghao11.cn/Article/details/gtoybsqhwj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xinyue.icu/Article/details/gtbvabeepm.html

[Q64] 提交事务
来源：http://dali.tianlin.xyz/Article/details/gtztzkpzml.html

COMMIT;
来源：http://dali.yonumen.top/Article/details/gtdotcpmpj.html

[Q65] 回滚事务
来源：http://dali.wangshuangyany.cn/Article/details/gtkbapczfv.html

ROLLBACK;
来源：http://dali.tianlin.xyz/Article/details/gtthrqpmpd.html

[Q66] 行锁查询
来源：http://dali.9152youxi.cn/Article/details/gtrwrroatf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibusudwh.html

[Q67] 设置隔离级别
来源：http://dali.fengsongda.top/Article/details/gtoccglyvc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuanzhike.top/Article/details/gtkvbkpbli.html

[Q68] 保存点
来源：http://dali.yj202588.top/Article/details/gtbxdqddkn.html

SAVEPOINT sp1;
来源：http://dali.guannengcc.top/Article/details/gtkwwpuhsx.html

ROLLBACK TO sp1;
来源：http://dali.guannengcc.top/Article/details/gtreqcpced.html

[Q69] 查看执行计划
来源：http://dali.zhixingplan.top/Article/details/gtvybkqlal.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuanzx.com/Article/details/gtumqfaftk.html

[Q70] 更新统计信息
来源：http://dali.ehwqpu.com/Article/details/gtnfuclkks.html

ANALYZE TABLE users;
来源：http://dali.redwolf501.top/Article/details/gtebwjfruc.html

[Q71] 查看建表语句
来源：http://dali.cashguo.top/Article/details/gtcpfhgkfd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.bjfxy.top/Article/details/gtdtibnafy.html

[Q72] 查看索引
来源：http://dali.xziqi.cn/Article/details/gtfaxithvj.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnppjiaab.html

[Q73] 查看表状态
来源：http://dali.jiagoushi.top/Article/details/gtkiuhenni.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.redwolf501.top/Article/details/gtrwhhqisp.html

[Q74] 强制使用索引
来源：http://dali.sysykeji.top/Article/details/gtxnnypvwp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yvedp.cn/Article/details/gtwagkxwvr.html

[Q75] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gtqutnfyjl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtqvjezfda.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gtmdmsglwi.html

[Q76] 按天统计
来源：http://dali.sysykeji.top/Article/details/gtgambsreg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.mhx1999.top/Article/details/gtgtoywnvz.html

[Q77] 时间加减
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjthclqe.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shangyingyoupin.top/Article/details/gtzwrvtouk.html

[Q78] 当前时间
来源：http://dali.yanxiufei.cn/Article/details/gtmlodauzc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yvedp.cn/Article/details/gtyynrzhym.html

[Q79] 字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gtrwccuijg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shuidangran.top/Article/details/gtzeizkvtk.html

[Q80] 字符串截取
来源：http://dali.hammf.cn/Article/details/gtwmizyzin.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjxixdxw.html

[Q81] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gtobhcxasm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yangfankeji.com/Article/details/gttmdsvwlp.html

[Q82] 字符长度与字节长度
来源：http://dali.yueranfly.top/Article/details/gtqtkukmjl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtxusqiite.html

[Q83] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtltgeclkh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtsshrtxte.html

[Q84] 去除首尾空格
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbrycofd.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtynfwuxwb.html

[Q85] 数值取整
来源：http://dali.cashguo.top/Article/details/gtwnfbouul.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yvedp.cn/Article/details/gtqjikeuql.html

[Q86] 读取 JSON 字段
来源：http://dali.dianchejie.cn/Article/details/gtbdiqgeul.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hammf.cn/Article/details/gtrdilnjev.html

[Q87] JSON 字段做条件
来源：http://dali.yvedp.cn/Article/details/gtuycesbcz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.kuanghao11.cn/Article/details/gtljqtrmpd.html

[Q88] 行转列（条件聚合）
来源：http://dali.hywenlv.cn/Article/details/gtdjczcwia.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ppjwa.cn/Article/details/gtiodeusam.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtnzxjgrvs.html

[Q89] 判断表是否存在
来源：http://dali.zycfv.cn/Article/details/gtpfosbwme.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenzaomai.com/Article/details/gtjlymlwks.html

[Q90] 生成序号列
来源：http://dali.ehwqpu.com/Article/details/gtpuighwku.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.birdmap.top/Article/details/gtyvpcgtcr.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtabtaxscb.html

R. Bash 专题
来源：http://dali.xuanzx.com/Article/details/gtqyswdoms.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtlufeeggo.html

[R01] shebang 与严格模式
来源：http://dali.gzhubu.top/Article/details/gtaxijreej.html

#!/usr/bin/env bash
来源：http://dali.tianlin.xyz/Article/details/gtpasczjbw.html

set -euo pipefail
来源：http://dali.yongpay.top/Article/details/gthihnqdjb.html

[R02] 变量赋值与使用
来源：http://dali.pengpengdd.cyou/Article/details/gthcvnvppk.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxzolmjg.html

[R03] 只读变量
来源：http://dali.jqgufenzy.top/Article/details/gtjbaytjvk.html

readonly PI=3.14
来源：http://dali.haohaochexian.top/Article/details/gttpstooql.html

[R04] 位置参数
来源：http://dali.gzhubu.top/Article/details/gtbjbcjwen.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aizwys.cn/Article/details/gtkvckiodh.html

[R05] 参数默认值
来源：http://dali.c1oappe.top/Article/details/gtumllplvy.html

name="${1:-default}"
来源：http://dali.ppjwa.cn/Article/details/gtlkwnuqxl.html

[R06] 判断命令是否存在
来源：http://dali.yongpay.top/Article/details/gtyfceduwb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gtbsureupv.html

[R07] if 判断文件
来源：http://dali.jqgfzy.top/Article/details/gtndsexomz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guowangkeji.top/Article/details/gtigcyacjo.html

[R08] 数值比较
来源：http://dali.ppjwa.cn/Article/details/gttmzxdwna.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shuidangran.top/Article/details/gtlxgbevop.html

[R09] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gtbydonikc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ybcxt.top/Article/details/gtguewcojs.html

[R10] 正则匹配
来源：http://dali.guowangkeji.top/Article/details/gtczczenbx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhixingplan.top/Article/details/gtkwyxzkqj.html

[R11] case 多分支
来源：http://dali.bjfxy.top/Article/details/gtngrixgmj.html

case "$1" in
来源：http://dali.redwolf501.top/Article/details/gtxpnouldg.html

start) echo "启动" ;;
来源：http://dali.aibaodan.cn/Article/details/gtgijascea.html

stop)  echo "停止" ;;
来源：http://dali.nanxinkj.top/Article/details/gtdjpwvndj.html

*)     echo "未知命令" ;;
来源：http://dali.ydzc1.top/Article/details/gteokghnwk.html

esac
来源：http://dali.fzhhl.top/Article/details/gtvyksfujn.html

[R12] for 遍历文件
来源：http://dali.quarkkingdee.top/Article/details/gtxmcotwwk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gtolebvpwc.html

[R13] for 计数循环
来源：http://dali.hnqzz.top/Article/details/gtbrxwrtxt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gtwgnvcaen.html

[R14] C 风格 for
来源：http://dali.hnxiangtu.top/Article/details/gtmlxaoxrj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gtwpbyenie.html

[R15] while 逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtaglqtass.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivihrjvr.html

[R16] until 等待条件
来源：http://dali.yj20258.top/Article/details/gtfpyvcbkp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gtiqzibwmm.html

[R17] 数组定义与取值
来源：http://dali.zhoulong.xyz/Article/details/gtdohkjvrj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258.top/Article/details/gtibkelnmr.html

[R18] 遍历数组
来源：http://dali.chenzaomai.com/Article/details/gtqhqwwqwu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tian-w.cn/Article/details/gtljrtgmrd.html

[R19] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gtmlxcjjse.html

echo "${#arr[@]}"
来源：http://dali.jqgufenzy.top/Article/details/gtbsyzgmyn.html

[R20] 关联数组（字典）
来源：http://dali.hnqzz.top/Article/details/gtfnfhaduo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sysykeji.top/Article/details/gthhjgpjzj.html

[R21] 字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakacbnuc.html

echo "${#s}"
来源：http://dali.hywenlv.cn/Article/details/gtblnnjosi.html

[R22] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gtlpacbkcn.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gtssifjlwg.html

[R23] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gtjdtbttle.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.snrcjt.cn/Article/details/gtygmhwpah.html

[R24] 大小写转换
来源：http://dali.birdmap.top/Article/details/gtulcyvtaj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ybcxt.top/Article/details/gtdyqzbawk.html

[R25] 去后缀 / 去前缀
来源：http://dali.hywenlv.cn/Article/details/gtlnmqowur.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258.top/Article/details/gtcejujotv.html

[R26] 命令替换
来源：http://dali.yj20258888.top/Article/details/gtvjxylobr.html

now=$(date +%F); echo "$now"
来源：http://dali.jinghuilouyu.cn/Article/details/gtjndrsrna.html

[R27] 算术展开
来源：http://dali.9152youxi.cn/Article/details/gtbsvcgbhg.html

echo $((1 + 2 * 3))
来源：http://dali.yvedp.cn/Article/details/gtxdpdllej.html

[R28] 浮点运算
来源：http://dali.sxryk.cn/Article/details/gtpxgpqoeo.html

echo "scale=2; 10/3" | bc
来源：http://dali.pengpengdd.cyou/Article/details/gtgyhwgbii.html

[R29] 定义函数
来源：http://dali.fzhhl.top/Article/details/gthwscezzu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.vqdsnc.cn/Article/details/gtcznmasgo.html

[R30] 函数返回状态码
来源：http://dali.yueranfly.top/Article/details/gtrtxqbfcu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yueranfly.top/Article/details/gtuubparip.html

[R31] 局部变量
来源：http://dali.jinqigufen.top/Article/details/gtumlroqjp.html

f() { local x=1; echo "$x"; }
来源：http://dali.guannengcc.top/Article/details/gtjqgdixdq.html

[R32] 参数个数校验
来源：http://dali.aizwys.cn/Article/details/gtwkoxsuvc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtauutpjan.html

[R33] 捕获错误并提示行号
来源：http://dali.bjfxy.top/Article/details/gtslmbljpw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhtluhcw.html

[R34] 退出时清理
来源：http://dali.hammf.cn/Article/details/gtdtrrqjiy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gtgiduqoyf.html

[R35] 后台执行并等待
来源：http://dali.sufxvd.cn/Article/details/gtzjgpjnea.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.c1oappe.top/Article/details/gtabvnmbcy.html

[R36] 并发执行多个任务
来源：http://dali.shzxlz.cn/Article/details/gtdvwuyqzu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.svipenyu.cn/Article/details/gtgqhpsyuw.html

[R37] 把输出赋给变量
来源：http://dali.vqdsnc.cn/Article/details/gttjjtgaqa.html

files=$(ls -1)
来源：http://dali.ppjwa.cn/Article/details/gtrsobkxpy.html

[R38] 管道串联
来源：http://dali.svipenyu.cn/Article/details/gtsciomfui.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jiagoushi.top/Article/details/gttbuhseyh.html

[R39] 重定向标准输出与错误
来源：http://dali.nwbrower.top/Article/details/gtmrhljxgl.html

cmd > out.log 2>&1
来源：http://dali.andypj.xyz/Article/details/gtdapgjvyg.html

[R40] 追加写日志
来源：http://dali.daria6918.cn/Article/details/gttpltsqou.html

echo "log" >> out.log
来源：http://dali.shuidangran.top/Article/details/gtypkmwhvq.html

[R41] 丢弃输出
来源：http://dali.hnxiangtu.top/Article/details/gthqrfgnnr.html

cmd >/dev/null 2>&1
来源：http://dali.xziqi.cn/Article/details/gtxvojqyil.html

[R42] 输入重定向
来源：http://dali.hammf.cn/Article/details/gtfqvryypm.html

wc -l < a.txt
来源：http://dali.sufxvd.cn/Article/details/gtqdxvcjxl.html

[R43] 按名字查找文件
来源：http://dali.hywenlv.cn/Article/details/gtquntbing.html

find . -name "*.log" -type f
来源：http://dali.sxryk.cn/Article/details/gtsumhtisq.html

[R44] 按修改时间查找
来源：http://dali.wangshuangyany.cn/Article/details/gteeefuwel.html

find . -mtime -7 -type f
来源：http://dali.hfpthk.cn/Article/details/gtinwwmceu.html

[R45] 批量删除
来源：http://dali.sysykeji.top/Article/details/gtovrdvzaj.html


<!-- 参考信息 -->